# Conversation Summary: Initial Design Session
**Date:** December 25, 2024  
**Topics:** Core architecture, utility connections, standard adoption

---

## What We Accomplished Today

### 1. Clarified Container Design
- **Single utility end** (rear only) - simpler, cheaper than dual connections
- **Bi-directional docking** - can back in OR drive in, utility block at far end works either way
- **Consistent orientation** - front always has doors, rear always has utilities
- No double-door configuration needed (saves $7,000-12,000 per container)

### 2. Adopted Proven Standards (RV/Food Truck Industry)
Rather than inventing custom solutions, we're using 50+ years of proven technology:
- **Electrical:** NEMA 14-50 (same as RV/Tesla)
- **Water:** Garden hose thread (RV city water standard)
- **Wastewater:** 3" RV dump connection
- **Propane:** ACME/POL quick-disconnect (RV standard)
- **HVAC:** Rooftop heat pump (RV/food truck standard)

**Impact:** Utility block costs drop from $15,000-25,000 (custom) to $3,000-5,000 (RV pedestal + mods)

### 3. Defined Hub Configuration
- Central building with radial or linear dock positions
- Each dock has utility block at far end
- Container parks with rear to utility block, front (doors) facing building
- Covered walkway connects building to container entrance
- Guest experience: walk from building lobby into container through full-width doors

### 4. Mobile Operation Strategy
- Truck configuration: [CAB] → [UTILITIES MODULE] → [CONTAINER]
- Utilities (generator, batteries, tanks, solar) protected between cab and container
- Container rear connects to utilities module when mobile
- Container front (doors) at truck rear for customer access
- Reduced functionality vs. hub (8-12 hours operation, limited water, simplified use)
- Cost: $15,000-25,000 for mobile utilities module (vs. $40,000+ full parity)

### 5. Scoped the Standard
**Core Standard (required):**
- Electrical: 50A/240V
- Data: Cat6 ethernet
- HVAC: 12" duct coupling

**Optional Extensions:**
- Water/wastewater (for food service, housing)
- Propane (for cooking, heating)
- Higher amperage (100A, 200A for intensive use)

**Benefit:** "Basic docks" for entertainment/retail much cheaper than full-service docks

### 6. Established Open Standard Philosophy
- Not proprietary - anyone can build to spec
- Enable competition (manufacturers, hub operators)
- Create network effects (more hubs = more value)
- Like USB, shipping containers, electrical outlets (universal standards)

### 7. Identified Critical Questions
Created master list of 70+ technical questions across categories:
- Physical infrastructure (15)
- Utilities & systems (16)
- Mobility & transport (12)
- Operational viability (7)
- Climate durability (4)
- Use case specific (14)
- Economic viability (8)
- Regulatory & permitting (16)
- Network effects & scaling (13)

**Priority questions to answer next:**
1. Can 20' container meet ADA requirements?
2. Is 50A enough for commercial kitchen?
3. Can containers meet residential building codes?
4. What's realistic container swap time?
5. Grease trap requirements (per container or per hub)?

### 8. Clarified Long-Term Vision
**Phase 1:** Entertainment (escape rooms, D&D venues) - prove modularity, generate revenue
**Phase 2:** Food service & retail - expand applications, test higher-intensity utilities
**Phase 3:** Affordable housing - apply proven infrastructure to residential, enable mobility

**Funding model:** Entertainment/food profits → housing R&D → open standard → systemic change

---

## Key Insights

### Design Principles That Emerged
1. **Proven over novel** - Don't reinvent what RV industry perfected
2. **Simple over comprehensive** - Minimum viable standard, optional extensions
3. **Flexible over rigid** - Bi-directional docking, tiered dock levels
4. **Accessible over exclusive** - Open standard, not proprietary system

### Value Propositions Clarified
- **For operators:** Own your container, mobility between hubs, lower upfront cost
- **For hub developers:** Proven technology, lower risk, swap containers easily
- **For vendors:** Geographic flexibility, no franchise fees, build equity
- **For housing:** Affordability + dignity + mobility when life changes

### The "Aha" Moments
1. **RV standards solve everything** - Don't need custom engineering
2. **Bi-directional docking is free** - Utility block position enables both approaches
3. **Mobile doesn't need parity** - Reduced functionality is acceptable (and cheaper)
4. **Entertainment funds housing** - Commercial viability enables social impact
5. **Network effects are the moat** - Open standard creates defensibility through adoption

---

## What Changed From Initial Concept

### Started With:
- Vague idea about modular escape rooms in containers
- Thought we needed custom connections
- Planned for dual utilities (both ends)
- Assumed mobile needed full hub capabilities
- Focused on proprietary advantage

### Evolved To:
- Clear three-phase vision (entertainment → food → housing)
- Adopt proven RV/food truck standards
- Single utility end (rear) with bi-directional docking
- Accepted mobile/hub capability split
- Open standard philosophy (network effects over ownership)

---

## Documentation Created

### Research
- **technical-questions.md** - Master list with status tracking (8 answered, 62+ to research)

### White Paper
- **draft-outline.md** - Complete white paper structure with section drafts
  - Problem statement
  - Solution overview
  - Technical specification
  - Economic model
  - Implementation roadmap
  - Open standard framework
  - Social impact vision

### Decisions
- **2024-12-25-core-design-decisions.md** - Today's key decisions with rationale
  - Utility connection strategy
  - Bi-directional docking discovery
  - RV standard adoption
  - HVAC approach (rooftop units)
  - Mobile vs. hub functionality split
  - Standard scope (core + optional)

### Project Files
- **README.md** - Project overview, current status, roadmap
- Directory structure created: /research, /white-paper, /decisions, /scale-model

---

## Next Session Goals

### Priority Research
1. **ADA compliance** - Can 20' container meet requirements?
2. **Kitchen electrical** - Calculate loads, confirm 50A is sufficient (or not)
3. **Building codes** - What classification? Temporary vs. permanent?
4. **Grease trap** - Per container or per hub? (Major cost driver)

### Scale Model
- Design 1:12 scale components for 3D printing
- Container shell (removable roof, doors)
- Utility block pedestal
- Hub configuration layout
- Mobile truck configuration
- Human figures for spatial testing

### Documentation
- Begin answering priority technical questions
- Expand white paper sections from outline to full draft
- Create pitch deck outline
- Start cataloging reference materials

### Validation
- Research commercial kitchen equipment loads
- Contact RV pedestal manufacturers for quotes
- Review ADA guidelines for small spaces
- Look up building codes in potential pilot cities

---

## Open Questions for Future Sessions

### Technical
- What happens in extreme cold (sub-zero)? Freeze protection?
- Can French cleat system actually support heavy props/equipment?
- What's realistic for solar contribution (marketing or meaningful)?
- Fire suppression: per container or building system covers it?

### Business Model
- What's pricing: per container, per dock position, or hybrid?
- Do operators own containers and rent docks? Or rent both?
- Can we charge enough to make hub development profitable?
- What's the path to first hub (bootstrap, investor, grant)?

### Strategic
- Should we build first container ourselves or partner with operator?
- Which use case to prove first: escape room or food service?
- Do we need nonprofit arm for housing, or for-profit with open licensing?
- How do we prevent fork/fragmentation once standard is released?

---

## Resources to Investigate

### Industry Standards
- RV Industry Association (RVIA) - connection specifications
- National Fire Protection Association (NFPA) - propane/gas codes
- Americans with Disabilities Act (ADA) - accessibility requirements
- International Building Code (IBC) / International Residential Code (IRC)

### Potential Partners
- Escape room operators (test case for modularity)
- Food truck operators (convert to container model?)
- Container modification companies (get quotes, learn process)
- RV pedestal manufacturers (Eaton, Siemens, Midwest Electric)
- Housing nonprofits (future housing partners)

### Comparable Projects
- Boxpark (UK) - shipping container mall, what can we learn?
- Koda (Estonia) - prefab tiny homes, different model but related
- Kasita - failed modular housing startup, what went wrong?
- Food truck parks/courts - similar hub concept for mobile food

---

## Project Momentum

**What's working:**
- Clear vision emerging from brainstorming
- Practical approach (use proven tech, don't invent)
- Compelling long-term impact (housing)
- Fundable path (entertainment → housing)

**What needs work:**
- Too many unknowns (70+ questions to research)
- Economics unproven (need prototype data)
- Regulatory uncertainty (varies by jurisdiction)
- Network effects require critical mass (chicken-egg problem)

**Confidence level:**
- **Concept viability:** HIGH (modular spaces + standard connections makes sense)
- **Technical feasibility:** MEDIUM-HIGH (RV standards proven, need to validate specific use cases)
- **Economic viability:** MEDIUM (need to validate unit economics with real data)
- **Market demand:** MEDIUM (need to prove people want rotation/mobility)
- **Regulatory approval:** LOW-MEDIUM (biggest unknown, jurisdiction-dependent)

---

## Personal Reflections (Christopher)

[Space for you to add thoughts after reviewing]

---

*This summary will be updated as project evolves. Next summary after scale model completion or next major design session.*
