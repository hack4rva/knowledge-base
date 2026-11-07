# Agent Guidelines for RVA Hacks Knowledge Base

This document defines how different agents (humans, AI assistants, automated systems) should interact with the knowledge base and the production application.

## System Overview

```
Knowledge Base (Staging) ──(approved by human)──> Application Code (Production)
     ↑                                                    ↓
     └────────── (NO REVERSE SYNC) ──────────────────────┘
```

The knowledge base is where all information is worked out, debated, and finalized. The application code implements decisions from the knowledge base. **There is NO automated reverse sync.**

---

## Agent Roles & Responsibilities

### 1. Human Developer / Project Lead
**Primary Role**: Bridge between knowledge base and application

**Knowledge Base Responsibilities:**
- Review and update KB files regularly
- Approve content changes before they're implemented in the app
- Decide when KB information should be migrated to the application
- Flag inconsistencies between KB and app for resolution
- Archive outdated information

**Application Responsibilities:**
- Implement changes approved from the KB
- Add JSDoc references to KB files when implementing non-obvious features
- Flag KB updates needed (but don't make the update unilaterally)
- Review PRs to ensure they reference KB sources where appropriate

**Decision Authority:**
- Only the human decides what moves from KB to app
- Only the human decides if KB information should be updated based on app learnings

---

### 2. Cursor IDE / Local Development Assistant
**Primary Role**: Support development while maintaining KB/app separation

**Knowledge Base Rules:**
- ✓ Read KB files for context before implementing features
- ✓ Suggest references to KB when editing app code
- ✓ Help organize and refine KB content
- ✗ NEVER auto-sync KB to app
- ✗ NEVER update KB based on code changes
- ✗ NEVER make assumptions; ask the human

**Application Rules:**
- ✓ Enforce code quality (TypeScript, linting, component structure)
- ✓ Suggest KB references for non-obvious decisions
- ✓ Require JSDoc citations for complex features
- ✓ Check that content isn't hardcoded without KB sourcing
- ✓ Help implement KB specifications accurately

**Example Cursor Behavior:**
```
Developer: "Let me add the team member bios to the Team page"

Cursor: "I found team info in knowledge-base/02-team-governance/.
Should I use the content from there? (Yes/No)"

Developer: "Yes, pull from that file"

Cursor: "Great. I'll add this JSDoc reference:
// Data sourced from knowledge-base/02-team-governance/team-structure.md"
```

---

### 3. Claude / Remote AI Assistant
**Primary Role**: Research, ideation, and documentation support

**Knowledge Base Work:**
- ✓ Help research and compile information
- ✓ Structure and organize KB documents
- ✓ Suggest improvements and clarifications
- ✓ Create comprehensive documentation
- ✓ Flag outdated or conflicting information
- ✗ NEVER assume decisions are final
- ✗ NEVER update KB without explicit human approval
- ✗ NEVER sync changes to the app

**Application Work:**
- ✓ Implement features specified in KB
- ✓ Create or update components based on KB content
- ✓ Add references to KB sources in code
- ✓ Flag KB gaps or inconsistencies discovered during implementation
- ✓ Suggest KB updates needed (let human approve)
- ✗ NEVER modify KB from code observations
- ✗ NEVER assume implementation should drive KB changes

**Example Claude Behavior:**
```
Task: "Implement the Event Format component"

Claude: "[Checking knowledge-base/08-participant-experience/...]
I found the event format details. Before implementing, I should note:
1. The KB says 'TBD' for the competition duration
2. Recommend flagging this with the human before implementation
3. I'll implement with a // TODO and reference"

[Implements with reference to KB]

Claude: "Implementation complete. NOTE: The schedule details in
08-participant-experience/ marked 'TBD' - human should confirm
before publishing this component."
```

---

### 4. Automated Systems / Scripts
**Primary Role**: Read-only access to KB for information needs

**Allowed Operations:**
- ✓ Read KB files to extract information
- ✓ Generate reports from KB data
- ✓ Validate KB consistency
- ✓ Create analytics from KB content
- ✗ NEVER modify KB or app files
- ✗ NEVER sync between KB and app

**Example**: A script that extracts team member names from KB for email lists

---

## Interaction Patterns

### Pattern 1: Feature Implementation (Normal Workflow)

```
1. Human: "Add the challenges section to the website"

2. Cursor/Claude: Checks knowledge-base/06-challenge-design/
   - Reviews challenge specifications
   - Notes any TODOs or pending decisions
   - Identifies content needed

3. Claude: Asks human if any TBDs need resolution before coding

4. Human: Approves or updates KB with missing information

5. Claude: Implements components based on KB
   - Adds JSDoc: "See knowledge-base/06-challenge-design/challenges.md"
   - Flags any implementation concerns
   - Opens PR for human review

6. Human: Reviews PR, merges if KB references are correct

7. Result: App code is implementation of KB; KB remains unchanged
```

### Pattern 2: KB Update (Discovery Workflow)

```
1. Claude: During implementation discovers "We need to decide on X"

2. Claude: Flags in code/comment: "TODO: KB needs decision on X"
   - Does NOT update KB
   - Does NOT assume anything

3. Claude: Suggests KB update to human in PR comments or summary

4. Human: Reviews suggestion, updates KB if appropriate
   - This is a human decision point
   - Ensures quality and consistency

5. Human: Merges app code; separately updates KB if needed

6. Result: App and KB both update, but through explicit human decision
```

### Pattern 3: KB Content Refinement (Staging Workflow)

```
1. Human: "Let me work out the marketing messaging in the KB"
   - Works in knowledge-base/07-marketing-comms/

2. Human iterates, discusses with team, refines in KB

3. Human: "This is finalized - please implement on the website"

4. Claude/Cursor: Implements from finalized KB
   - Mirrors content structure
   - Adds proper references
   - Handles formatting for web

5. Result: KB is staging; app reflects current approved version
```

---

## Content Change Management

### When to Update KB
- **Decision made** after research and discussion
- **Strategy finalized** and ready for implementation
- **Specification complete** and detailed enough for development
- **Approval given** by project leadership

### When to Flag KB Needs Update
- **Implementation discovered gap** in specification
- **Assumption clarification needed** before building
- **Timeline conflict** between KB and app
- **New information** changes original decision

### Decision Points (ONLY Human)
- Which KB content moves to app
- When KB information is outdated
- How to handle KB ↔ app conflicts
- Whether implementation suggests KB revisions

---

## Special Cases

### Case 1: Conflicting Information
```
KB says: "Team size is 12"
App code has: "Team size is 15"

Decision: Human mediates
- Is app outdated? Update from KB
- Is KB outdated? Update KB, then app
- Do they need different values? Document why
```

### Case 2: TBD/Incomplete Information
```
KB has: "Prizes TBD - finalize by [date]"

App should:
- Add a // TODO comment
- NOT hardcode placeholder
- Implement in a way that's easy to update
- Wait for human approval before going live

Claude should: Flag this in PR comments
```

### Case 3: Implementation Simplification
```
KB specifies: "Complex 3-step validation process"
Claude implements: "Simpler 2-step validation works and meets goals"

Decision:
- Flag to human: "KB says 3 steps, I implemented 2. Discuss?"
- NEVER assume app is better than KB strategy
- Let human decide if KB should update
```

### Case 4: Bug Fix
```
Bug discovered in deployed code

Decision:
- Fix the bug in app immediately
- Separately decide: does KB need updating?
- Don't couple bug fix with KB updates
- Let human approve KB changes separately
```

---

## Quality Assurance Checklist

### For KB Updates (By Any Agent)
- [ ] Is this a specification, not an assumption?
- [ ] Is this decision-quality, not exploratory?
- [ ] Does this reflect consensus or approval?
- [ ] Are there references to supporting documentation?
- [ ] Is there a clear action item if TBD?

### For App Implementation (By Any Agent)
- [ ] Did I check KB first for requirements?
- [ ] Does my implementation match KB specification?
- [ ] Did I flag KB gaps or TODOs?
- [ ] Is my code referenced back to KB source?
- [ ] Did I NOT modify KB files?

### For Synchronization (By Human Only)
- [ ] Is KB content finalized and approved?
- [ ] Is app implementation accurate to KB?
- [ ] Are there any TODOs or open questions?
- [ ] Have I documented the KB source in code?
- [ ] Is versioning clear (what version of KB is this app based on)?

---

## Implementation Details by Framework

### When Using Cursor IDE
Cursor reads `.cursorrules` at `/Users/williamprior/Development/GitHub/rvahacks/.cursorrules`
This file defines:
- What Cursor suggests about KB/app separation
- How Cursor should reference KB files
- Code quality standards
- When to prompt for human decisions

### When Using Claude (Remote)
This file (`AGENTS.md`) defines:
- How Claude should treat KB vs app
- When Claude should flag decisions
- What Claude should NOT do automatically
- How to handle uncertainty

### When Using Local Git Workflows
Both KB and app are in same repo but separate:
```
rvahacks/
├── knowledge-base/    # Working directory for strategy/content
├── src/               # Production code
└── .cursorrules       # IDE rules for developer assistance
```

No automated sync between them. Developers make intentional commits to both.

---

## Communication & Escalation

### Clear Escalation Paths

**Cursor: "I'm not sure what the requirements are"**
→ Suggest human check KB or ask clarifying questions

**Claude: "The KB doesn't specify this"**
→ Flag it clearly; implement conservatively; ask human to decide

**Human: "Why didn't you implement X?"**
→ Check if KB specified it; if not, show KB gap

**Human: "KB says one thing, app does another"**
→ Investigate which is correct; respect human's authority

---

## The Golden Rule

> **The knowledge base is the source of truth. The application is an implementation of that truth. Changes flow one way: KB → App. No automated sync. All decisions are human decisions.**

---

## Questions?

If an agent (human or AI) is unsure about KB/app interaction:

1. **Is this KB content or app code?** → Different rules apply
2. **Am I changing something?** → Check if this should be KB or app
3. **Should this sync?** → NO. Only explicit human migration
4. **Should I ask the human?** → YES. When in doubt
5. **Can I assume this is final?** → NO. Check with human if unsure

Remember: The human is the decision-maker. Agents support; humans decide.
