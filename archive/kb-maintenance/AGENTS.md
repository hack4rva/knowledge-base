# AI Agent Guidelines for Knowledge Base Maintenance

**Companion to .cursorrules - Detailed procedures and examples**

---

## Purpose

This document provides detailed procedures, examples, and workflows for AI agents maintaining the Richmond Civic Hackathon knowledge base. It complements the `.cursorrules` file with practical guidance and real-world scenarios.

**See also:** `../../.cursorrules` for rules, `./KB-AUDIT-FINDINGS.md` for audit results, `./DOCUMENT-STATUS-MATRIX.md` for file status

---

## Quick Reference: When to Use This Guide

**Use this document when:**
- Creating new documents
- Updating existing documents
- Detecting inconsistencies
- Propagating changes
- Auditing KB health
- Unsure about KB standards

---

## Writing Quality Standards (ALWAYS APPLY FIRST)

Before creating or editing any document, apply the **Complete Writing Framework** (see `./complete-writing-framework.md`).

### Quick Reference: Writing Standards

**For ALL documents:**
1. **Be Direct:** Sentences under 30 words, no wordy phrases
2. **Use Data:** Replace adjectives with numbers ("40% increase" not "significant")
3. **Avoid Jargon:** Explain terms, use everyday language
4. **"So What?" Test:** Why does this matter? What should reader do?
5. **Clear Thinking:** Writing forces clarity; use it to understand ideas

**For participant/sponsor-facing documents, ADD:**
- **Voice:** Human, not robotic
- **Hook:** First line creates tension
- **Concrete:** Abstract concepts with vivid examples
- **Curiosity:** Structure as discovery
- **Emotion:** Show why it matters
- **Momentum:** End points forward

### Writing Process (Every Document)

**Pass 1: AWS Clarity**
- Cut sentences to <30 words
- Replace adjectives with data
- Remove jargon
- Add "so what?"

**Pass 2: Voice** (when appropriate)
- Read aloud for rhythm
- Add hook
- Make abstract concrete
- Check: sounds human?

**Pass 3: Tighten**
- Cut 20% of words
- Each paragraph earns next
- Remove throat-clearing
- Ending points forward

**Pass 4: Empathy**
- Smart outsider follow?
- Stay awake?
- Feel something?
- Act?

### Example: Before & After

**Before (Weak):**
> "The Richmond Civic Hackathon will significantly improve civic engagement through innovative technology solutions that will help the community."

**After (AWS Principles):**
> "The Richmond Civic Hackathon builds 8-10 solutions for City challenges. These solutions enter a 6-month implementation pathway with micro-grants up to $5,000."

**After (+ Bar-Raising for participant materials):**
> "Build something Richmond uses. The hackathon creates 8-10 solutions for real City challenges. The best ones get $5,000 and 6 months of support to make them real. Last year, three became City services. This year, one could be yours."

### When to Use Which Approach

**AWS Principles ONLY:**
- Meeting notes
- Budget spreadsheets
- Internal team docs
- Technical specifications

**AWS + Bar-Raising:**
- Participant-facing (registration.md, what-to-expect.md)
- Sponsor materials (prospectus, pitch)
- Event descriptions
- Challenge descriptions
- Blog posts, press releases
- Leadership communications

**Quality Checklist (Before Publishing):**
- [ ] Sentences <30 words?
- [ ] Data replaces adjectives?
- [ ] Jargon removed?
- [ ] "So what?" answered?
- [ ] Hook in opening? (if external-facing)
- [ ] Sounds human when read aloud? (if external-facing)
- [ ] Cut 20% of words?
- [ ] Ending points forward?

### Practical Examples: Applying the Framework

#### Example 1: Meeting Notes (AWS Principles Only)

**Before:**
> "We had a really productive conversation with Heather about potential community partners. She had some great ideas about organizations we should definitely reach out to, and we think this could be a game-changer for the event."

**After (AWS Principles Applied):**
> **Meeting: Heather Lyne - Leadership Advisory Committee**  
> **Date:** November 12, 2025  
> **Key Decision:** Focus exclusively on Mayor's Pillar 4: A Thriving Economy  
> **Action Items:**  
> - Reach out to 5 priority organizations: Venture Richmond, Community Foundation, PlanRVA, StartupVA, RVA Rising  
> - Each sponsors mission-aligned award category  
> - Ford + Heather develop outreach strategy by November 19

**Why this works:** Direct, data-driven, actionable. No weasel words. Clear "so what?"

---

#### Example 2: Participant-Facing Content (AWS + Bar-Raising)

**Before:**
> "The Richmond Civic Hackathon provides an excellent opportunity for talented individuals to work on meaningful civic technology projects that can make a real difference in our community. We welcome participants from all backgrounds."

**After (AWS Principles):**
> "The Richmond Civic Hackathon brings together 150-200 participants to build solutions for City challenges. Teams of 3-6 work for 2 days. Winners receive up to $5,000 in micro-grants and 6 months of City support for implementation."

**After (+ Bar-Raising):**
> "Your weekend. Richmond's future.
> 
> March 6-8, 2026. 150-200 builders. 8-10 real City challenges.
> 
> You pick your day: hack Friday (if you can swing the PTO) or Saturday (if weekends work better). Either way, you're building something Richmond might actually use.
> 
> The best solutions don't just win prizes—they get $5,000 and 6 months of support to become real City services. Last year, three teams made it happen. This year, one of them could be yours."

**Why this works:** Opens with tension. Human voice. Concrete details. Stakes are clear. Ends pointing forward.

---

#### Example 3: Sponsor Prospectus (AWS + Bar-Raising)

**Before:**
> "Sponsoring the Richmond Civic Hackathon is a great way to demonstrate your company's commitment to innovation and community engagement while getting valuable brand exposure to Richmond's tech community."

**After (AWS Principles):**
> "Diamond Tier ($10,000-15,000) includes: Logo on all materials, 15-minute keynote, judging panel seat, 10 mentor volunteer spots, access to participant resumes, private interview room."

**After (+ Bar-Raising):**
> **Why sponsor the Richmond Civic Hackathon?**
> 
> Because the Mayor is watching. And so are 150-200 of Richmond's best builders.
> 
> This isn't a branding play. It's access. Your engineers mentor teams solving real City problems. Your recruiters meet talent before they hit the market. Your brand gets associated with solutions that might run Richmond by 2027.
> 
> **Diamond Tier ($10-15K):** Your logo everywhere. Your leader on stage. Your team in the room. First look at every project. Private space for conversations that matter.
> 
> Three teams from last year's event are now City vendors. Where will this year's winners come from?"

**Why this works:** Stakes in opening. Concrete benefits. Emotional hook ("access," "first look"). Proof (last year's results). Challenge at end.

---

#### Example 4: Challenge Description (AWS + Bar-Raising)

**Before:**
> "The City needs innovative solutions to help improve economic development and create opportunities for businesses and entrepreneurs in Richmond's diverse neighborhoods."

**After (AWS Principles):**
> **Challenge: Small Business Permitting Portal**  
> **Problem:** Business permit applications take 45-60 days. 40% of applicants call the City 3+ times for status updates.  
> **Goal:** Build a portal where applicants track permit status in real-time.  
> **Success Metric:** Reduce status inquiry calls by 50% in pilot neighborhood.  
> **Prize:** $3,000 + StartupVA mentorship

**After (+ Bar-Raising):**
> **The 45-Day Wait That Kills Businesses Before They Start**
> 
> You filed your business permit application. Now what?
> 
> You wait 45-60 days. You call the City. You get transferred. You call again. 40% of Richmond's new business owners make this call three times or more.
> 
> Every call is time not spent building their business. Every day of uncertainty is another day rent accumulates. Some give up. Richmond loses what they would have built.
> 
> **Your challenge:** Build the portal that ends the mystery. Real-time permit tracking. Clear status updates. No more "let me transfer you."
> 
> **If you win:** $3,000, StartupVA mentorship, and the knowledge that every business that opens faster because of you is a business that might not have opened at all.
> 
> **Success looks like:** 50% fewer status calls in the pilot neighborhood. Which means 50% more time those business owners spend building.
> 
> Start with one neighborhood. Prove it works. Help the City scale it to all of Richmond.

**Why this works:** Opens with human problem. Stakes are emotional (businesses dying). Concrete metrics. Clear "so what?" Momentum at end.

---

### When NOT to Apply Bar-Raising

**These documents should use AWS Principles ONLY:**

❌ **Budget spreadsheets** - Just the numbers, no story needed  
❌ **Technical specifications** - Clarity only  
❌ **Internal meeting notes** - Facts, decisions, action items  
❌ **Contract templates** - Legal clarity trumps all  
❌ **Insurance documentation** - Precision required  

**Why:** These documents serve internal operational needs. Voice and emotion would distract from their core purpose: clear decision-making and reference.

---

## Document Lifecycle Management

### Creating New Documents

**Step 1: Determine Correct Location**

```
Question: Where should this document go?

Check directory purposes:
- 01-planning-strategy/ → Strategic planning, feasibility
- 02-team-governance/ → Team structure, roles, management
- 03-meeting-notes/ → Historical decisions, meeting records
- 04-partnerships/ → Sponsors, partners, fundraising
- 05-event-operations/ → Logistics, venue, day-of execution
- 06-challenge-design/ → Civic challenges, judging
- 07-marketing-comms/ → Promotion, brand, outreach
- 08-participant-experience/ → Registration, onboarding, support
- 09-legal-compliance/ → Legal, insurance, IP, contracts
- 10-budget-finance/ → Budget, expenses, financial tracking
- 11-post-event/ → Implementation, incubation, sustainability
- 12-impact-measurement/ → KPIs, metrics, evaluation
- 13-resources/ → Templates, checklists, tools
```

**Step 2: Check for Existing Coverage**

```
Before creating:
1. Search for similar content in directory README
2. Check DOCUMENT-STATUS-MATRIX.md
3. Look for related documents in same directory
4. Verify not already covered comprehensively

If content exists:
- Update existing doc rather than create new
- Or create if distinct audience/purpose
- Add cross-reference between related docs
```

**Step 3: Create with Standard Header**

```markdown
# Document Title

> **STATUS:** 📝 DRAFT | ⏳ PENDING [What] | ✅ COMPLETE
> **Action Required:** [If applicable]

**Purpose:** One sentence describing what this document covers

**Audience:** Who should read this

**Last Updated:** November 12, 2025  
**Owner:** [Team member name]
```

**Step 4: Add to Parent README**

```markdown
In directory README.md:

### [new-document.md](./new-document.md) 🆕
**STATUS:** COMPLETE | DRAFT | PENDING  
Brief description of what it contains
- Key sections or highlights
- When to use this document
```

**Step 5: Update DOCUMENT-STATUS-MATRIX.md**

Add entry with status, priority, and notes.

---

### Updating Existing Documents

**Always Follow This Process:**

1. **Read current version fully** before editing
2. **Check .cursorrules** for specific rules about this topic
3. **Verify facts** against other documents (cross-check)
4. **Update "Last Updated" date** to current date
5. **Add cross-references** if new related docs exist
6. **Check for propagation needs** (does this change affect other docs?)

**Example Update Workflow:**

```
Task: Update budget figure in START-HERE.md

Step 1: Read START-HERE.md current content
Step 2: Check .cursorrules § 3 (Budget Standardization)
Step 3: Verify current budget in 10-budget-finance/README.md
Step 4: Update START-HERE with $45,700 (3-day format)
Step 5: Add link to budget README
Step 6: Update "Last Updated" date
Step 7: Check if ACTION-ITEMS-ASAP needs same update (YES)
Step 8: Update ACTION-ITEMS-ASAP too
```

---

### Archiving Documents

**When to Archive:**

- Superseded by newer version
- Decision reversed
- Information outdated/no longer relevant
- Historical reference only

**Archive Process:**

1. Move file to `archive/deprecated/`
2. Add note to top of file: "ARCHIVED: [date] - [reason]"
3. Update any links to archived doc (redirect to new version or note archived)
4. Add entry to `archive/README.md`
5. Remove from parent directory README (note as archived)

**Never delete!** Always archive for historical record.

---

## Conflict Detection & Resolution

### Common Conflicts & How to Fix

#### Conflict 1: Event Format Mismatch

**Detect:**
```
Document mentions:
- "single-day event"
- "Friday 12 PM - 10 PM (10 hours)"
- "One-day hackathon"
```

**Resolve:**
```markdown
OLD: "Join us Friday, March 6 for a 10-hour hackathon"

NEW: "Join us March 6-8 for a 3-day flexible weekend hackathon
- Friday OR Saturday hacking (choose your day)
- Sunday awards ceremony (all welcome)"

ADD: > **Format:** 3-day flexible weekend ⚠️ Pending CoStar 3-day confirmation
```

**Propagate to:** Any document mentioning event format

---

#### Conflict 2: Budget Inconsistency

**Detect:**
```
Budget mentioned as:
- $42,190 (old single-day)
- $40,000-$50,000 (vague range)
- $45,000 (outdated target)
```

**Resolve:**
```markdown
OLD: "Total budget: $42,190"

NEW: "Total budget: $45,700 (3-day format)
- Original single-day: $42,190
- 3-day increase: +$3,500
- Sponsorship target: $47,000-$50,000"

ADD LINK: See [10-budget-finance/README.md](./10-budget-finance/README.md) for details
```

**Propagate to:**
- ACTION-ITEMS-ASAP.md
- FORMAT-DECISION.md
- Any sponsor-facing documents

---

#### Conflict 3: Team Member Name Variations

**Detect:**
```
Same person referenced as:
- "Ford" vs "Ford Prior"
- "Michael" vs "Michael Colby"
- "Crystal" vs "Crystal Harvey"
```

**Resolve:**
```markdown
Use FULL NAMES from .cursorrules § 4:
- Ford Prior ✅
- Crystal Harvey ✅
- Michael Colby ✅

NOT:
- Ford ❌
- Crystal ❌  
- Michael ❌
```

**Standardize:** Across entire KB

---

#### Conflict 4: Outdated Timeline References

**Detect:**
```
Document says:
- "4.5 months out" (written in October)
- "Late October 2025"
- Any fixed time reference
```

**Resolve:**
```markdown
Calculate actual time:
- Event date: March 6, 2026
- Current date: [Use actual current date]
- Calculate weeks: (March 6, 2026 - Current Date) / 7

OLD: "We're 4.5 months out"
NEW: "We're ~16 weeks out (as of November 12, 2025)"

OR USE: Dynamic reference like "See date-selection-validation.md for current timeline"
```

---

#### Conflict 5: Broken Links

**Detect:**
```
Link points to file that doesn't exist:
[Team Roles](./02-team-governance/team-roles.md)

Check: File doesn't exist
```

**Resolve:**

**Option A:** File should exist
```markdown
1. Check DOCUMENT-STATUS-MATRIX.md
2. If HIGH or CRITICAL priority, create it
3. Update matrix with new status
```

**Option B:** File won't be created
```markdown
OLD: [Team Roles](./02-team-governance/team-roles.md)

NEW: [Team Roles](./02-team-governance/README.md#core-team-structure)
(Link to section in existing README that covers this)

OR: Team roles [TBD - see README for current structure]
```

---

## Cross-Referencing Best Practices

### When to Add Cross-References

**Add links when:**
- Mentioning another document's topic
- Referencing data from elsewhere
- Explaining "see X for details"
- Providing additional context

### How to Write Good Cross-References

**Bad:**
```markdown
See the budget document for more information.
```

**Good:**
```markdown
See [10-budget-finance/README.md](./10-budget-finance/README.md) for detailed budget breakdown including 3-day format costs.
```

**Best:**
```markdown
**Budget:** $45,700 for 3-day format

The budget increased from the original single-day estimate due to additional meals and staffing. For complete breakdown:
- **Budget Details:** [10-budget-finance/README.md](./10-budget-finance/README.md)
- **Format Decision Rationale:** [FORMAT-DECISION.md](./FORMAT-DECISION.md#budget-impact)
- **Sponsorship Targets:** [04-partnerships/README.md](./04-partnerships/README.md#sponsorship-tiers)
```

### Bi-directional Links

When adding a cross-reference, consider adding reverse link:

```markdown
Document A references Document B:
→ Also add link from Document B back to Document A (context)

Example:
- FORMAT-DECISION.md links to 10-budget-finance/README.md (budget details)
- 10-budget-finance/README.md should link to FORMAT-DECISION.md (format rationale)
```

---

## Information Propagation Workflows

### Scenario: Event Format Changes

**Trigger:** Format decision updated (e.g., move from 3-day to 2-day)

**Propagation Checklist:**

1. **Update primary documents:**
   - [ ] FORMAT-DECISION.md (decision rationale)
   - [ ] 05-event-operations/EVENT-FORMAT.md (detailed schedule)

2. **Update secondary references:**
   - [ ] README.md (event overview)
   - [ ] START-HERE.md (quick reference)
   - [ ] ACTION-ITEMS-ASAP.md (logistics implications)

3. **Update dependent information:**
   - [ ] 10-budget-finance/README.md (budget impacts)
   - [ ] 05-event-operations/volunteer-management.md (shifts)
   - [ ] 05-event-operations/run-of-show.md (schedule)
   - [ ] 08-participant-experience/registration.md (day selection)

4. **Update participant-facing:**
   - [ ] 08-participant-experience/what-to-expect.md
   - [ ] Any marketing materials

5. **Verify consistency:**
   - [ ] Search KB for all format mentions
   - [ ] Update any missed references
   - [ ] Check .cursorrules still accurate

---

### Scenario: Budget Changes

**Trigger:** Budget figure updated

**Propagation Checklist:**

1. **Update primary source:**
   - [ ] 10-budget-finance/README.md (detailed budget)

2. **Update summaries:**
   - [ ] ACTION-ITEMS-ASAP.md (budget summary box)
   - [ ] START-HERE.md (if budget mentioned)
   - [ ] FORMAT-DECISION.md (budget impact section)

3. **Update sponsor materials:**
   - [ ] 04-partnerships/README.md (sponsorship targets)
   - [ ] Any sponsor prospectuses (when created)

4. **Update assumptions:**
   - [ ] KB-AUDIT-FINDINGS.md (if budget was flagged)

5. **Verify ripple effects:**
   - [ ] Does this affect prize pool?
   - [ ] Does this affect services we can offer?
   - [ ] Update any related documents

---

### Scenario: Team Member Addition/Change

**Trigger:** New team member or role change

**Propagation Checklist:**

1. **Update primary roster:**
   - [ ] 02-team-governance/README.md (detailed roles)
   - [ ] .cursorrules § 4 (team name list)

2. **Update overviews:**
   - [ ] README.md (core team section)
   - [ ] START-HERE.md (team assignments)

3. **Update assignments:**
   - [ ] ACTION-ITEMS-ASAP.md (task owners)
   - [ ] Any documents they now own (Owner: field)

4. **Update contact lists:**
   - [ ] Emergency procedures (if relevant)
   - [ ] Run of show (if staff position)

---

## Document Quality Checks

### Pre-Publish Checklist

Before considering any document "complete":

**Structure:**
- [ ] Clear H1 title
- [ ] Status banner (if needed)
- [ ] Purpose statement
- [ ] Table of contents (if >500 words)
- [ ] Logical section hierarchy
- [ ] Conclusion or next steps

**Content:**
- [ ] No assumptions stated as facts (flag with ⚠️)
- [ ] All claims sourced or noted as pending verification
- [ ] Richmond-specific (not just generic hackathon advice)
- [ ] Actionable (reader knows what to do)
- [ ] Appropriate detail level for audience

**Links & References:**
- [ ] All internal links work (files exist)
- [ ] Cross-references to related docs
- [ ] External links valid
- [ ] Broken links marked [TBD]

**Metadata:**
- [ ] "Last Updated" date (bottom of doc)
- [ ] "Owner" specified
- [ ] "Status" clear (Draft/Complete/Pending)
- [ ] Added to parent directory README
- [ ] Added to DOCUMENT-STATUS-MATRIX (if new)

**Consistency:**
- [ ] Event format = 3-day flexible weekend
- [ ] Budget = $45,700 (3-day)
- [ ] Date = March 6-8, 2026 (with validation note)
- [ ] Team names = full names
- [ ] MLH content cited

---

## Common Editing Scenarios

### Scenario 1: User asks to "update the budget"

**Good Response Process:**

```
1. Clarify what's changing:
   - New total amount?
   - New breakdown?
   - New assumptions?

2. Find all budget references:
   - Primary: 10-budget-finance/README.md
   - Summaries: ACTION-ITEMS-ASAP.md, START-HERE.md
   - Context: FORMAT-DECISION.md

3. Update all consistently

4. Check ripple effects:
   - Does sponsorship target change?
   - Do services need adjustment?

5. Update DOCUMENT-STATUS-MATRIX if impacts missing docs

6. Report what was changed
```

---

### Scenario 2: User asks to "create a new document about X"

**Good Response Process:**

```
1. Determine correct directory (use purposes list)

2. Check if already covered:
   - Look in directory README
   - Check DOCUMENT-STATUS-MATRIX
   - Search for related content

3. If truly new:
   - Create with standard header
   - Use consistent formatting
   - Add cross-references
   - Add to directory README
   - Update STATUS-MATRIX

4. If already covered:
   - Suggest updating existing doc
   - Or explain how existing doc covers it
   - Create only if distinct audience/purpose
```

---

### Scenario 3: User says "check for conflicts in the KB"

**Good Response Process:**

```
1. Run standard checks:
   - Event format consistency
   - Date references and validation status
   - Budget figures
   - Team member names
   - Broken links

2. Generate report:
   - Conflicts found
   - Recommended fixes
   - Priority (critical/high/medium/low)

3. Ask for approval before making changes

4. Make approved changes systematically

5. Update KB-AUDIT-FINDINGS.md with results
```

---

## Maintaining KB Health

### Weekly Maintenance Tasks

**Every Week:**
1. Check for documents >60 days old (flag for review)
2. Verify critical links still work
3. Check for new broken references
4. Update timeline calculations (if date-dependent content exists)
5. Review DOCUMENT-STATUS-MATRIX for completion progress

### Monthly Maintenance Tasks

**Every Month:**
1. Full audit of core documents (README, START-HERE, ACTION-ITEMS)
2. Verify all assumptions still flagged appropriately
3. Check for outdated information
4. Review directory READMEs for accuracy
5. Update KB-AUDIT-FINDINGS if new issues found

### Before Major Milestones

**Before sponsor outreach, registration open, event day:**
1. Full KB audit
2. Ensure all participant-facing docs accurate
3. Verify legal docs approved and current
4. Check operational docs complete
5. Test all links
6. Verify contact info current

---

## Examples of Good vs Bad Practices

### Example 1: Referencing Unverified Information

**Bad:**
```markdown
VCU Spring Break is March 10-14, 2026, so our event won't conflict.
```

**Good:**
```markdown
⚠️ **ASSUMPTION - Needs verification:** VCU Spring Break dates for 2026 are not yet confirmed. If Spring Break is March 6-8 or overlaps, this would severely impact student participation.

**Action Required:** Contact VCU Registrar to confirm 2026 academic calendar.
```

---

### Example 2: Stating Budget

**Bad:**
```markdown
The budget is about $40,000 to $50,000.
```

**Good:**
```markdown
**Budget (3-Day Format):** $45,700
- Original single-day budget: $42,190
- 3-day format increase: +$3,500 (additional F&B, staffing, Sunday setup)
- **Sponsorship Target:** $47,000-$50,000 (includes contingency)
- **Status:** Pending final vendor quotes (December 2025)

See [10-budget-finance/README.md](./10-budget-finance/README.md) for detailed breakdown.
```

---

### Example 3: Documenting Decisions

**Bad:**
```markdown
We decided to do 3 days instead of 1 day because it's better.
```

**Good:**
```markdown
# Format Decision: 3-Day Flexible Weekend

> **STATUS:** ✅ APPROVED | ⚠️ PENDING CoStar 3-Day Venue Confirmation
> **Action Required:** Nick + Ford must confirm with Claire ASAP

**Decision Date:** October 25, 2025

## Rationale

**From:** Single-day Friday (10 hours)
**To:** 3-day flexible weekend

**Why:**
1. **Accessibility:** Working professionals can't take Friday PTO → Saturday option
2. **Inclusion:** Parents/caregivers need flexibility → Choose your day
3. **Quality:** More time → Better projects
4. **Community:** Sunday public event → Civic engagement

**Trade-offs:**
- ✅ 50-100% more participants (better accessibility)
- ✅ Higher diversity potential
- ❌ +$3,500 budget (+8%)
- ❌ More complex logistics (3 days vs 1)
- ⚠️ Requires CoStar 3-day availability (pending)

**Impact:**
- Budget: $42,190 → $45,700
- Sponsorship target: → $47-50K
- Venue: Must confirm 3-day access
- Volunteers: Need ~40-50 (shift system)

**See:** [EVENT-FORMAT.md](./05-event-operations/EVENT-FORMAT.md) for complete schedule
```

---

## Troubleshooting Guide

### Problem: "Can't find where information should go"

**Solution:**
1. Read directory purposes in .cursorrules § 9
2. Check DOCUMENT-STATUS-MATRIX for similar topics
3. Look at existing documents in candidate directories
4. Ask yourself: "Who needs this info and when?"
5. Choose directory based on primary audience/purpose

---

### Problem: "Conflicting information in multiple places"

**Solution:**
1. Identify all locations with conflict
2. Check which is most recent (Last Updated date)
3. Check .cursorrules for rule about this topic
4. Determine single source of truth
5. Update all locations consistently
6. Add cross-references so readers know where to find authoritative version

---

### Problem: "Don't know if this assumption needs flagging"

**Solution:**
1. Check KB-AUDIT-FINDINGS.md Phase 8 (assumptions list)
2. If not on list, ask: "Is this verified fact or assumption?"
3. If assumption: Add ⚠️ flag
4. If verified: Note source
5. If unsure: Flag anyway (better safe than sorry)

---

### Problem: "Should I create new doc or update existing?"

**Decision Tree:**
```
1. Does existing doc cover this topic?
   YES → Update existing doc
   NO → Continue to 2

2. Would adding to existing doc make it too long (>3000 words)?
   YES → Consider creating new doc
   NO → Update existing doc

3. Is this for a different audience than existing docs?
   YES → Create new doc (different purpose)
   NO → Update existing doc

4. Is this a distinct phase/aspect (like event-day vs planning)?
   YES → Create new doc (distinct context)
   NO → Update existing doc
```

---

## Advanced: Bulk Operations

### Updating Multiple Documents Systematically

**When:** A key piece of information changes that affects many docs

**Process:**

1. **Inventory affected documents:**
   ```
   Search KB for keyword (e.g., "budget", "March 6")
   List all files containing it
   Categorize by type of change needed
   ```

2. **Prioritize updates:**
   ```
   Critical: Documents user will see first (README, START-HERE)
   High: Documents in active use
   Medium: Supporting documents
   Low: Historical or infrequently accessed
   ```

3. **Update systematically:**
   ```
   Update in priority order
   Keep consistent wording across all
   Update timestamps on all edited docs
   Keep list of what was changed
   ```

4. **Verify consistency:**
   ```
   Search again for old information
   Check cross-references still accurate
   Test any affected links
   ```

5. **Document changes:**
   ```
   Update KB-AUDIT-FINDINGS if relevant
   Note in any affected READMEs
   Consider adding to version history
   ```

---

## Success Criteria

### KB is healthy when:

✅ Zero format conflicts (all say 3-day weekend)
✅ Zero budget inconsistencies (all say $45,700 for 3-day)
✅ All date references note validation status
✅ No broken links (or marked [TBD])
✅ All documents have Last Updated <30 days (during active planning)
✅ All assumptions flagged with ⚠️
✅ All MLH content properly cited
✅ Directory READMEs accurate
✅ DOCUMENT-STATUS-MATRIX current

### Agent is successful when:

✅ Detects and flags conflicts proactively
✅ Maintains consistency across propagation
✅ Adds appropriate cross-references
✅ Follows .cursorrules without exception
✅ Creates high-quality, useful documents
✅ **Applies writing framework appropriately** (AWS for internal, AWS+Bar-Raising for external)
✅ **Documents are clear, data-driven, and human** (when appropriate)
✅ Helps team stay organized and informed
✅ Saves team time through automation
✅ Prevents misinformation

---

**Document Created:** November 12, 2025  
**Last Updated:** November 12, 2025  
**Version:** 1.1  
**Companion Documents:**
- `../../.cursorrules` for rules
- `./complete-writing-framework.md` for writing standards

**For questions about these procedures, refer to:**
- `../../.cursorrules` for rules
- `./complete-writing-framework.md` for writing quality standards
- `./KB-AUDIT-FINDINGS.md` for audit results
- `./DOCUMENT-STATUS-MATRIX.md` for file status
- Main `../../README.md` for KB architecture

