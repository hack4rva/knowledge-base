# Mayor's Action Plan (MAP) Alignment

**Complete mapping of hackathon challenges to Mayor Danny Avula's seven-pillar Mayoral Action Plan**

---

## 📊 Overview of the Seven Pillars

Mayor Avula's MAP organizes Richmond's priorities around seven interconnected pillars:

1. **A Thriving City Hall** (that gets things done)
2. **Thriving Neighborhoods** (that meet our housing needs)
3. **Thriving Families** (where every child succeeds)
4. **A Thriving Economy** (that leaves no one behind)
5. **Thriving and Inclusive Communities** (where everyone's rights are protected)
6. **A Thriving and Sustainable Built Environment** (planned for future generations)
7. **A City That Tells its Stories** (and tells the truth about its past)

---

## 🎯 Challenge Selection Strategy

### High-Priority Pillars for Hackathon (Based on Tech Feasibility)

**Tier 1: Highest Tech Fit (3-5 challenges)**
1. **Thriving City Hall** - Digital services, process optimization, 311 improvements
2. **Sustainable Built Environment** - GIS/mapping, environmental data, transit
3. **Thriving Economy** - Business information, job access, economic data

**Tier 2: Strong Fit (2-3 challenges)**
4. **Thriving Neighborhoods** - Housing data, neighborhood amenities, safety data
5. **Thriving and Inclusive Communities** - Language access, equity data visualization

**Tier 3: Specialized Fit (0-2 challenges)**
6. **Thriving Families** - After-school program finder, family services navigation
7. **City That Tells its Stories** - Digital archives, historical mapping, storytelling platforms

### CoStar "PropTech for Public Good" Track
**Must include 1-2 challenges leveraging CoStar's expertise:**
- GIS and mapping capabilities
- Environmental/sustainability data
- Real estate and built environment intelligence

---

## 🏛️ PILLAR 1: A Thriving City Hall (that gets things done)

### Goals Most Relevant to Hackathon

**E. Provide white-glove service**
- SOPs & SLAs for all RVA 311 request types
- More staff trained in customer response
- Faster permitting, business licensing, tax discrepancy resolution

**F. Improve resident satisfaction & trust**
- More users finding City systems easy
- More residents reporting City is responsive and taking action

**C. Keep standards high**
- Responsible AI/digital transformation
- Process improvements

---

### 🎯 Challenge Ideas: Thriving City Hall

#### Challenge 1.1: One-Click RVA Reporting (311 Enhancement)

**The Problem:**
Citizens struggle to report non-emergency issues (potholes, broken streetlights, graffiti) through fragmented systems. Calls often get routed to wrong departments, causing delays and frustration.

**10-Hour Challenge:**
Design a streamlined mobile-first interface that:
- Simplifies issue reporting (photo + location + auto-category)
- Uses AI/ML to route to correct department automatically
- Provides real-time status updates to reporter
- Shows trending issues on neighborhood map

**City Benefit:**
- Reduced internal service request misdirection
- Higher citizen satisfaction with responsiveness
- Data-driven identification of systemic issues

**Implementation KPI:**
Reduction in internal service request misdirection rate (measured 3 months post-pilot)

**Department Champion:** RVA 311 / Customer Service

**Data Needed:**
- Sample 311 request data (anonymized)
- Department routing rules
- Geographic boundaries

**Tech Stack Suggestions:**
- Mobile web app (React Native, Flutter)
- Computer vision for image categorization
- Mapping API integration

---

#### Challenge 1.2: Permit Progress Tracker

**The Problem:**
Business owners and residents have no visibility into permit application status. They make repeated calls asking "where is my permit?" creating staff burden.

**10-Hour Challenge:**
Create a permit status dashboard that:
- Shows permit application progress (submitted → under review → approved)
- Provides estimated completion dates
- Alerts applicants when action is needed
- Shows common reasons for delays with how to fix

**City Benefit:**
- Reduced phone inquiries to permit office
- Faster permit resolution (applicants know what's needed)
- Improved business satisfaction

**Implementation KPI:**
Reduction in permit status inquiry calls; faster average permit processing time

**Department Champion:** Department of Planning and Development Review

**Data Needed:**
- Permit application statuses (sample/anonymized)
- Typical processing timelines
- Common issues causing delays

---

#### Challenge 1.3: City Services Navigation (AI-Powered Assistant)

**The Problem:**
Residents don't know which City service they need or how to access it. "I have a problem with X" doesn't map cleanly to City department structure.

**10-Hour Challenge:**
Build a conversational interface (chatbot or guided wizard) that:
- Asks plain-language questions about resident's issue
- Maps to correct City service/department
- Provides next steps and contact information
- Available in multiple languages

**City Benefit:**
- Residents find right service faster
- Reduced burden on staff from misdirected inquiries
- Better accessibility for non-English speakers

**Implementation KPI:**
User satisfaction with finding correct service; reduction in transferred calls

**Department Champion:** RVA 311 / Department of Information Technology

**Data Needed:**
- City services catalog
- Common resident inquiries and correct routing
- Language translation needs

---

## 🏘️ PILLAR 2: Thriving Neighborhoods (that meet our housing needs)

### Goals Most Relevant to Hackathon

**C. Connect neighborhoods to amenities**
- More annual visits to Parks & Rec, Library branches, Human Services locations
- Annual Richmond 300 update

**A. Build more homes**
- More new housing units; more affordable units with City support

**D. Keep neighborhoods safe & prepared**
- Faster 911 responses
- Maintain/improve positive community-public safety interactions

---

### 🎯 Challenge Ideas: Thriving Neighborhoods

#### Challenge 2.1: Richmond Neighborhood Resource Mapper

**The Problem:**
New residents and families don't know what amenities exist in their neighborhood (parks, libraries, rec centers, community services). Information is scattered across multiple websites.

**10-Hour Challenge:**
Create an interactive neighborhood map showing:
- Parks, playgrounds, rec centers, libraries
- Community centers and Human Services locations
- Public WiFi locations
- Transit access
- Filter by amenity type and accessibility features

**City Benefit:**
- Increased awareness and usage of Parks & Rec, Libraries, Human Services
- Better data on amenity deserts (where to invest)
- Improved resident satisfaction

**Implementation KPI:**
Increase in Parks & Rec visits (tracked by district); user satisfaction with finding amenities

**Department Champion:** Parks & Recreation / Library / Human Services

**Data Needed:**
- City facility locations and hours
- Richmond 300 neighborhood boundaries
- Accessibility information

---

#### Challenge 2.2: Affordable Housing Navigator

**The Problem:**
Residents seeking affordable housing don't know what programs they qualify for or how to apply. Information about City-supported affordable units is not centralized.

**10-Hour Challenge:**
Build a housing resource finder that:
- Simple questionnaire determines eligibility for programs
- Shows available affordable units (City-supported)
- Links to application processes
- Provides eviction prevention resources

**City Benefit:**
- More residents accessing affordable housing programs
- Reduced administrative burden answering eligibility questions
- Data on unmet housing needs

**Implementation KPI:**
Increase in affordable housing program applications; user satisfaction

**Department Champion:** Department of Housing & Community Development

**Data Needed:**
- Affordable housing programs and eligibility criteria
- Available City-supported affordable units (if any public data)
- Eviction prevention services

---

## 💼 PILLAR 4: A Thriving Economy (that leaves no one behind)

### Goals Most Relevant to Hackathon

**D. Support small, minority/women/worker-owned businesses**
- More businesses receiving City technical/financial support
- Higher % City procurement with minority-owned businesses

**B. Connect people to jobs**
- More jobs reachable by public transit
- More residents finding work via City initiatives

**C. Reduce poverty & build wealth**
- Lower poverty levels; higher education and homeownership

---

### 🎯 Challenge Ideas: Thriving Economy

#### Challenge 4.1: Richmond Business Navigator

**The Problem:**
New small business owners struggle to understand zoning restrictions, required licenses, and permits. They waste time applying for wrong permits or choosing impossible locations.

**10-Hour Challenge:**
Create a searchable business startup guide that:
- "I want to open a [type] business in [location]"
- Shows zoning compatibility, required licenses, permit process
- Estimates timeline and costs
- Links to City technical/financial support programs

**City Benefit:**
- More small businesses successfully launching
- Reduced confusion and back-and-forth with City
- Better data on business startup barriers

**Implementation KPI:**
Citizen satisfaction with business startup information; reduction in zoning violation applications

**Department Champion:** Office of Economic Development / Planning & Development Review

**Data Needed:**
- Zoning regulations by location
- Business license requirements by type
- City support programs for small/minority-owned businesses

---

#### Challenge 4.2: Jobs + Transit Map

**The Problem:**
Job seekers without cars don't know which jobs they can realistically reach via public transit. Employers don't understand transit accessibility of their locations.

**10-Hour Challenge:**
Create a map/tool that:
- Shows job locations overlaid with GRTC routes
- Calculates commute time from any address via transit
- Identifies "job deserts" (employment centers with poor transit)
- Helps job seekers find accessible opportunities

**City Benefit:**
- More residents connecting to employment via transit
- Data to advocate for transit route improvements
- Support for "more jobs reachable by public transit" goal

**Implementation KPI:**
Usage by job seekers; transit route advocacy informed by data

**Department Champion:** Office of Economic Development / GRTC partnership

**Data Needed:**
- Major employer locations and job counts
- GRTC routes and schedules (API if available)
- Census tract employment data

---

## 🌱 PILLAR 6: A Thriving and Sustainable Built Environment (planned for future generations)

**This pillar has the STRONGEST alignment with CoStar's PropTech expertise and should be prioritized for the "PropTech for Public Good" track.**

### Goals Most Relevant to Hackathon

**B. Advance RVAgreen 2050**
- More residents within 10-minute walk of quality green space
- Fewer flooding incidents/standing water calls

**D. Build/maintain/repair City infrastructure**
- Fewer unplanned utility interruptions
- Fewer open sidewalk requests
- Better Pavement Condition Index

**E. Make it easier to get around (walk/roll/ride/bus)**
- More overall GRTC usage and bike-lane miles
- Expand regional BRT

---

### 🎯 Challenge Ideas: Sustainable Built Environment (COSTAR PROPTECH TRACK)

#### Challenge 6.1: Tree Equity Scorecard Dashboard ⭐ (PropTech for Public Good)

**The Problem:**
Richmond lacks public-facing data on tree canopy coverage and urban heat islands. Communities most affected by heat often have the least tree coverage, but data isn't accessible to residents or community advocates.

**10-Hour Challenge:**
Design a simplified GIS dashboard that:
- Shows tree canopy density by neighborhood
- Overlays socioeconomic data and heat vulnerability
- Identifies critical planting zones
- Tracks progress toward RVAgreen 2050 goals
- Community can request tree planting in their area

**City Benefit:**
- Data-driven tree planting prioritization
- Community engagement in greening efforts
- Visual progress tracking toward RVAgreen 2050

**Implementation KPI:**
Pilot readiness score; City Parks Department adoption of dashboard; community tree planting requests

**Department Champion:** Parks & Recreation / Office of Sustainability

**CoStar Expertise Leverage:**
- GIS mapping and spatial analysis
- Environmental data visualization
- Real estate data overlay (property values, demographics)

**Data Needed:**
- Tree canopy data (LiDAR or satellite imagery)
- Heat island mapping
- Demographic data by census tract
- RVAgreen 2050 benchmarks

---

#### Challenge 6.2: Flood Risk & Resilience Mapper ⭐ (PropTech for Public Good)

**The Problem:**
Residents don't know if their property is at flood risk. The City receives standing water complaints but lacks public tool to show flood-prone areas and climate adaptation plans.

**10-Hour Challenge:**
Create an interactive flood risk map that:
- Shows historical flooding locations
- Displays predicted flood zones under climate scenarios
- Overlays City infrastructure projects addressing flooding
- Allows residents to report standing water issues
- Provides property-level resilience recommendations

**City Benefit:**
- Better resident awareness of flood risk
- Data collection on flooding issues
- Progress tracking toward RVAgreen 2050 resilience goals

**Implementation KPI:**
Reduction in standing water calls (better reporting); resident satisfaction with flood risk information

**Department Champion:** Department of Public Utilities / Office of Sustainability

**CoStar Expertise Leverage:**
- Flood risk layers (similar to CoStar's flood risk data for commercial real estate)
- GIS and property-level mapping
- Environmental data integration

**Data Needed:**
- Historical flood/standing water complaint locations
- FEMA flood zones
- City stormwater infrastructure projects
- Climate projection data

---

#### Challenge 6.3: Green Space Access & Quality Map ⭐ (PropTech for Public Good)

**The Problem:**
RVAgreen 2050 goal: more residents within 10-minute walk of quality green space. But what counts as "quality"? Where are the gaps?

**10-Hour Challenge:**
Build a map/tool that:
- Shows parks and green spaces with quality indicators (amenities, maintenance, safety)
- Calculates 10-minute walk accessibility by address
- Identifies neighborhoods without access
- Allows community to rate park quality and suggest improvements

**City Benefit:**
- Identify green space investment priorities
- Track progress toward RVAgreen 2050 goal
- Community engagement in park quality

**Implementation KPI:**
% residents within 10-minute walk of quality green space (baseline and tracking)

**Department Champion:** Parks & Recreation

**CoStar Expertise Leverage:**
- Walkability analysis (similar to CoStar's walkability scores)
- GIS spatial analysis
- Property and neighborhood data overlay

**Data Needed:**
- Park locations, sizes, and amenities
- Walkability/pedestrian network data
- Neighborhood boundaries

---

#### Challenge 6.4: Sidewalk & Bike Lane Gap Analyzer

**The Problem:**
The City receives sidewalk repair requests but lacks public visibility into sidewalk network completeness and bike lane connectivity. Residents don't know safe walking/biking routes.

**10-Hour Challenge:**
Create a multimodal transportation map showing:
- Sidewalk network (complete, incomplete, requested repairs)
- Existing bike lanes and gaps
- Safe walking/biking routes to key destinations (schools, transit, jobs)
- Community can report missing sidewalks or bike lane needs

**City Benefit:**
- Prioritize sidewalk/bike lane investments
- Progress toward "make it easier to get around" goal
- Reduced open sidewalk requests (better tracking)

**Implementation KPI:**
Better Pavement Condition Index; more bike-lane miles added in priority areas

**Department Champion:** Department of Public Works

**Data Needed:**
- Sidewalk network data
- Bike lane locations
- Sidewalk repair requests
- Pedestrian/bike crash data (for safety overlay)

---

## 🌈 PILLAR 5: Thriving and Inclusive Communities (where everyone's rights are protected)

### Goals Most Relevant to Hackathon

**A. Support immigrant communities**
- Higher participation of non-English-speaking households in Human Services
- More City staff completing Language Access Plan training

**D. Address racial inequities in health/wealth/well-being**
- Higher life expectancy for African American and Latino residents
- Better economic security

---

### 🎯 Challenge Ideas: Thriving and Inclusive Communities

#### Challenge 5.1: Multilingual City Services Access

**The Problem:**
Non-English-speaking residents struggle to access City services. Information and forms are primarily in English, creating barriers to Human Services, 311, and other programs.

**10-Hour Challenge:**
Build a tool that:
- Translates City service information into top languages (Spanish, Arabic, etc.)
- Provides translated intake forms
- Connects to interpretation services
- Tracks which services need better language access

**City Benefit:**
- Higher participation of non-English speakers in Human Services
- Reduced language access barriers
- Data on translation needs to inform Language Access Plan

**Implementation KPI:**
Increase in non-English-speaking household participation in Human Services

**Department Champion:** Human Services / Office of Immigrant & Refugee Affairs (if exists)

**Data Needed:**
- City services catalog
- Top languages spoken in Richmond (census data)
- Current translation availability

---

#### Challenge 5.2: Equity Data Dashboard

**The Problem:**
Racial inequities in health, wealth, and well-being are tracked but not accessible to community advocates and residents. Data transparency is needed to drive action.

**10-Hour Challenge:**
Create a public dashboard visualizing:
- Life expectancy by race and neighborhood
- Economic security metrics by race
- Access to quality healthcare, education, housing
- Progress tracking toward equity goals

**City Benefit:**
- Transparency and accountability on equity goals
- Community engagement informed by data
- Identify priority areas for intervention

**Implementation KPI:**
Community usage of dashboard; data-informed advocacy and policy

**Department Champion:** Office of Community Wealth Building / Mayor's Office

**Data Needed:**
- Health outcomes by race (from County Health Rankings)
- Economic data by race (census, employment)
- Housing, education access data

---

## 👨‍👩‍👧‍👦 PILLAR 3: Thriving Families (where every child succeeds)

### Goals Most Relevant to Hackathon

**D. Connect school-age kids to activities**
- More middle/high-school participation in OST (out-of-school time) programs

**C. Kindergarten readiness**
- Higher enrollment in RPS & partner pre-K programs

**F. Respond to families in crisis**
- Faster processing for services; more clients served

---

### 🎯 Challenge Ideas: Thriving Families

#### Challenge 3.1: After-School & Summer Program Finder

**The Problem:**
Parents don't know what after-school, summer, and OST programs are available for their children. Information is scattered across City, RPS, and nonprofit websites.

**10-Hour Challenge:**
Create a searchable program directory that:
- Filter by age, location, cost, type of activity
- Shows program quality indicators (accreditation, reviews)
- Direct links to enrollment
- Highlights violence prevention programs

**City Benefit:**
- Increased participation in OST programs
- More youth in violence prevention
- Better data on program availability gaps

**Implementation KPI:**
Increase in middle/high-school OST program participation

**Department Champion:** Parks & Recreation / Youth Development (if exists)

**Data Needed:**
- City-run OST programs
- Partner organization programs
- Locations, costs, age ranges

---

## 📖 PILLAR 7: A City That Tells its Stories (and tells the truth about its past)

### Goals Most Relevant to Hackathon

**A. Share Shockoe with the world as a place for reckoning & repair**

**C. Share and document Richmond's rich cultural history**

**B. Champion arts & culture communities in telling Richmond's stories**

---

### 🎯 Challenge Ideas: City That Tells its Stories

#### Challenge 7.1: Richmond Historical Mapping Project

**The Problem:**
Richmond's Black empowerment history, Civil Rights history, and stories of slavery/racism are not easily accessible to residents or visitors in a digital format.

**10-Hour Challenge:**
Create an interactive historical map/app that:
- Shows historical sites with stories (Shockoe, Jackson Ward, etc.)
- Integrates oral histories (audio/video)
- Self-guided walking tour functionality
- Community can contribute stories and photos

**City Benefit:**
- Visitor-friendly historical education
- Digital preservation of oral histories
- Support Virginia 250 commemorations

**Implementation KPI:**
Usage by residents and visitors; community story contributions

**Department Champion:** Office of Arts & Culture (if exists) / Richmond Public Library

**Data Needed:**
- Historical site locations and stories
- Oral history recordings (if available)
- Existing historical documentation

---

## 🎯 Recommended Challenge Portfolio (8-10 Challenges)

### Tier 1: Must-Have (5 challenges)

**CoStar PropTech for Public Good Track (2):**
1. **Tree Equity Scorecard Dashboard** (Pillar 6)
2. **Flood Risk & Resilience Mapper** (Pillar 6)

**City Hall Modernization (2):**
3. **One-Click RVA Reporting** (Pillar 1)
4. **Permit Progress Tracker** (Pillar 1)

**Economic Opportunity (1):**
5. **Richmond Business Navigator** (Pillar 4)

### Tier 2: High Value (3 challenges)

6. **Green Space Access & Quality Map** (Pillar 6 - PropTech)
7. **Neighborhood Resource Mapper** (Pillar 2)
8. **Jobs + Transit Map** (Pillar 4)

### Tier 3: Stretch Goals (2 challenges)

9. **Multilingual City Services Access** (Pillar 5)
10. **After-School Program Finder** (Pillar 3)

---

## 📊 Challenge Selection Criteria Scorecard

| Challenge | MAP Alignment | CoStar Leverage | 10-hr Feasible | City Champion | Data Available | Implementation Likely | Total Score |
|-----------|---------------|-----------------|----------------|---------------|----------------|----------------------|-------------|
| Tree Equity Scorecard | ✅✅✅ | ✅✅✅ | ✅✅ | ✅✅ | ✅✅ | ✅✅ | 15/18 |
| One-Click RVA 311 | ✅✅✅ | ✅ | ✅✅✅ | ✅✅✅ | ✅✅ | ✅✅ | 16/18 |
| Business Navigator | ✅✅✅ | ✅ | ✅✅ | ✅✅ | ✅✅ | ✅✅ | 14/18 |
| Flood Risk Mapper | ✅✅✅ | ✅✅✅ | ✅✅ | ✅✅ | ✅ | ✅✅ | 14/18 |
| Permit Tracker | ✅✅✅ | ✅ | ✅✅✅ | ✅✅ | ✅✅ | ✅✅ | 15/18 |

---

## 📝 Next Steps

1. **Schedule meetings with City departments** (via Michael Colby)
   - RVA 311 / Customer Service
   - Planning & Development Review
   - Parks & Recreation
   - Office of Sustainability
   - Economic Development

2. **Validate challenge ideas with department champions**
   - Is this a real pain point?
   - Would you use this solution?
   - What data is available?

3. **Refine challenges based on feedback**
   - Ensure 10-hour feasibility
   - Confirm Implementation Champion
   - Verify data access

4. **Get Mayor's Office sign-off on final challenge portfolio**
   - Aligns with MAP priorities
   - Political visibility potential
   - Implementation commitment

---

**Last Updated:** October 25, 2025  
**Source:** Mayor Danny Avula's Mayoral Action Plan (October 15, 2025)

