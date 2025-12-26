---
title: "Core Design Decisions"
date: 2024-12-25
layout: page
permalink: /decisions/2024-12-25-core-design-decisions/
---

## Utility Connection Strategy

**Decision:** Containers have utilities at ONE end (rear) only, not both ends.

**Rationale:**
- Simpler design (no duplicate systems)
- Lower cost (~$1,500 vs. $7,000-12,000 for dual utilities)
- Maintains standard shipping container structural integrity
- Uses proven single-door configuration
- Still allows bi-directional docking (see below)

**Implications:**
- Container orientation is consistent: FRONT = doors, BACK = utilities
- No double-door configuration needed
- Easier to manufacture/maintain

**Alternatives Considered:**
- Dual utility connections (both ends) - REJECTED: too expensive, unnecessary
- Dual doors (both ends) - REJECTED: structural concerns, cost, not needed

---

## Bi-Directional Docking

**Decision:** Utility block positioned at FAR END of dock pad allows containers to dock either direction.

**Rationale:**
- Container can BACK IN (rear goes first) → utilities connect, doors face building
- Container can DRIVE IN (front goes first) → utilities still connect, doors still face building
- Same final position, different approach direction
- Provides site flexibility without changing container or dock design

**Implications:**
- Dock positions can be configured based on site constraints
- Traffic flow can be optimized
- Driver preference accommodated
- No additional cost or complexity

**Alternatives Considered:**
- Side-entry docking - REJECTED: loses dramatic full-width door entrance
- Fixed single-direction approach - REJECTED: too limiting for varied sites

---

## Standard Connections (RV Industry)

**Decision:** Use existing RV/food truck connection standards rather than custom engineering.

**Rationale:**
- 50+ years proven reliability
- Off-the-shelf parts (cheap, available everywhere)
- Familiar to electricians, plumbers, operators
- Service network already exists (RV shops nationwide)
- Weatherproof, mobile-rated, code-compliant
- Dramatically lower cost than custom solutions

**Specific Standards Adopted:**
- **Electrical:** NEMA 14-50 (50A/240V) - same as large RVs, Tesla chargers
- **Water:** ¾" GHT (garden hose thread) with pressure regulator - universal RV standard
- **Wastewater:** 3" bayonet/twist-lock - RV dump station standard
- **Propane:** ACME/POL quick-disconnect - RV/BBQ standard
- **HVAC:** 12" round duct - standard HVAC component
- **Data:** Cat6 ethernet - only non-RV element (but common/cheap)

**Implications:**
- Utility block can be based on RV pedestal design ($2,000-5,000 vs. $15,000-25,000 custom)
- Parts sourcing is trivial (hardware stores, RV suppliers)
- Maintenance/repair is easy (any RV shop can help)
- User familiarity ("it's like RV hookups") reduces training
- Credibility with inspectors (known, approved systems)

**Alternatives Considered:**
- Custom connection system - REJECTED: expensive, unnecessary, no service network
- Industrial connectors (Cam-Lok, etc.) - REJECTED: overkill for this application
- Residential-style hardwired - REJECTED: not suited for frequent connect/disconnect

---

## HVAC Approach

**Decision:** Rooftop heat pump units (RV-style) rather than mini-split systems.

**Rationale:**
- Simpler installation (one piece vs. indoor + outdoor units)
- No refrigerant lines to connect/disconnect
- Proven for mobile/vibration (RVs, food trucks)
- Roof space otherwise unused
- Self-contained (everything in one box)
- Easy replacement if unit fails

**Implications:**
- 15,000 BTU rooftop unit standard (~$1,200-2,500)
- Can run on battery/generator (mobile operation)
- Hub dock provides ducted connection as backup/supplement
- Standard part (Dometic, Coleman, Carrier brands)

**Alternatives Considered:**
- Mini-split (indoor + outdoor units) - REJECTED: complex connections, refrigerant handling
- Window units - REJECTED: not suited for container construction
- Building HVAC only (no self-contained) - REJECTED: doesn't work for mobile use

---

## Mobile Utilities Configuration

**Decision:** Utilities module positioned BETWEEN cab and container (mid-truck).

**Truck Layout:** [CAB] → [UTILITIES MODULE] → [CONTAINER]

**Rationale:**
- Container rear (utilities) faces forward, connects to module
- Container front (doors) at truck rear, accessible to customers
- Utilities module protected between cab and container
- Balanced weight distribution
- Accessible for maintenance (not inside container)
- Matches food truck configuration patterns

**Implications:**
- Generator, batteries, tanks in dedicated mid-section
- Container interior stays clean (no generator inside)
- Can upgrade utilities without modifying container
- Module can be standardized (swap between trucks)

**Alternatives Considered:**
- Utilities inside container - REJECTED: wastes interior space, noise/exhaust issues
- Utilities at truck rear - REJECTED: exposed, hard to access
- Utilities under container - REJECTED: ground clearance issues, hard to service

---

## Mobile vs. Hub Functionality

**Decision:** Mobile version has REDUCED functionality, not full parity with hub.

**Rationale:**
- Mobile is for 4-8 hour events, not 12+ hour daily operation
- Reduced expectations = smaller/cheaper systems
- Battery + generator sufficient for limited duration
- Tank capacity sized for actual mobile use patterns
- Focus on portability over unlimited operation

**Mobile Limitations (Accepted):**
- Limited runtime (8-12 hours max)
- Smaller water/wastewater tanks (50-75 gal vs. unlimited)
- Simplified menu for food service (no dishwasher, pre-prep)
- Adequate climate control (not precise)
- Cellular data (not fiber internet)

**Hub Capabilities (Full Featured):**
- Unlimited runtime (grid power)
- Unlimited water/sewer (municipal)
- Full commercial kitchen possible
- Precise climate control
- High-speed internet

**Implications:**
- Mobile module cost: $15,000-25,000 (not $40,000+)
- Different use cases served appropriately
- Mobile events priced accordingly (shorter duration, limited capacity)
- Operators choose right configuration for their needs

**Alternatives Considered:**
- Full parity (mobile = hub capabilities) - REJECTED: too expensive, overkill
- Mobile only (no hub) - REJECTED: limits applications, no permanent option

---

## Standard Scope

**Decision:** Core standard includes ONLY 3 required connections; everything else is optional extensions.

**Required (Core Standard):**
1. Electrical: NEMA 14-50 (50A/240V)
2. Data: Cat6 ethernet (4 ports)
3. HVAC: 12" round duct coupling

**Optional Extensions:**
4. Water: ¾" GHT inlet (if needed for use case)
5. Wastewater: 3" dump connection (if needed)
6. Propane: Quick-disconnect (if needed)

**Rationale:**
- Escape rooms don't need water (use building restrooms)
- Retail doesn't need gas
- Entertainment doesn't need heavy utilities
- Food service adds what it needs
- Keeps base standard simple/cheap
- Allows tiered dock development

**Implications:**
- "Basic Dock" provides power + data + HVAC (~$5,000)
- "Food Service Dock" adds water + waste + gas (~$10,000-15,000 more)
- "Residential Dock" adds hot water + higher amperage (~$20,000-30,000 total)
- Containers labeled with minimum dock tier required

**Alternatives Considered:**
- Everything required - REJECTED: too expensive for simple uses
- No standard (totally custom) - REJECTED: defeats purpose of interoperability

---

## Key Insights from Today's Session

### Design Principles Established:
1. **Simplicity over comprehensiveness** - minimum viable standard
2. **Proven over novel** - use existing RV/food truck standards
3. **Flexible over rigid** - optional extensions for different uses
4. **Accessible over perfect** - cheaper systems enable more adoption

### Core Value Propositions Clarified:
1. **For operators:** Lower cost + flexibility + mobility
2. **For hub developers:** Proven technology + lower risk
3. **For vendors:** Equipment ownership + geographic freedom
4. **For housing:** Affordable + dignified + mobile

### Critical Path Forward:
1. Build scale model → prove spatial concepts
2. Answer ADA + electrical questions → validate viability
3. Build prototype → test in real world
4. Document + open source → enable network

### What Changed Today:
- Moved from "invent everything" to "adapt proven systems"
- Clarified single-utility-end design
- Understood bi-directional docking benefit
- Accepted mobile/hub capability split
- Scoped standard to minimum viable

---

## Questions Raised (Added to Research)

- Is 50A actually enough for commercial kitchen? (PRIORITY)
- What's realistic container swap time? (need prototype data)
- Can we meet ADA in 160 sq ft? (critical for all uses)
- What insulation R-value needed? (climate-dependent)
- Grease trap per container or per hub? (regulatory/cost issue)

---

*See also: [Day 1 Blog Post](/blog/2024/12/25/day-1-core-architecture/)*
