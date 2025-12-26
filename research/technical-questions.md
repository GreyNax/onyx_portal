# Technical Questions Master List

**Last Updated:** December 25, 2024  
**Status Overview:** 
- ✅ Answered: 8
- 🔄 In Progress: 3
- ⏳ Priority Next: 10
- 📋 To Research: 50+

---

## ANSWERED ✅

### Physical Infrastructure
- [x] **Should utilities connect at one end or both ends of container?**
  - **Answer:** One end (back of container) only
  - **Rationale:** Simpler, cheaper, uses standard shipping container door config
  - **Source:** Conversation 2024-12-25
  - **Implications:** Container has consistent orientation (front=doors, back=utilities)

- [x] **Can containers dock facing either direction (front-in or back-in)?**
  - **Answer:** YES - both directions work
  - **Rationale:** Utility block at far end of dock means container can back in OR drive in forward
  - **Source:** Conversation 2024-12-25
  - **Implications:** Site flexibility, easier maneuvering, adaptive to different lot layouts

### Utilities & Systems
- [x] **Can we use RV-style electrical connections?**
  - **Answer:** YES - NEMA 14-50 (50A/240V) standard
  - **Rationale:** Proven for decades, parts everywhere, electricians know it
  - **Source:** RV industry standards research
  - **Implications:** Lower cost, easier sourcing, familiar to operators

- [x] **Can we use garden hose connections for water?**
  - **Answer:** YES - ¾" GHT (garden hose thread) with pressure regulator
  - **Rationale:** RV standard, dead simple, universally available
  - **Source:** RV industry standards
  - **Implications:** No custom parts needed, easy to connect/service

- [x] **What wastewater connection standard?**
  - **Answer:** 3" bayonet/twist-lock (RV dump station standard)
  - **Rationale:** Proven, cheap ($30), every RV dump station compatible
  - **Source:** RV industry standards
  - **Implications:** Can dump at any RV facility when mobile

- [x] **Should we use mini-split or rooftop HVAC?**
  - **Answer:** Rooftop unit (RV-style)
  - **Rationale:** Simpler (one piece), proven for mobile use, no refrigerant lines
  - **Source:** Food truck and RV industry standard
  - **Implications:** Easier installation, more reliable for transport

### Mobility & Transport
- [x] **Where should utilities go on truck configuration?**
  - **Answer:** Between cab and container (mid-truck)
  - **Rationale:** Protected, accessible, balanced weight, connects to container rear
  - **Source:** Food truck configuration analysis
  - **Implications:** Container rear faces forward when trucking

- [x] **Can same container work at hub AND mobile?**
  - **Answer:** YES - same rear connection panel accepts hub utilities OR truck utilities
  - **Rationale:** Standard connection point, different sources
  - **Source:** Design decision 2024-12-25
  - **Implications:** True modularity, containers swap between hub and mobile use

---

## IN PROGRESS 🔄

### Physical Infrastructure
- [ ] **What insulation R-value is needed for year-round operation?**
  - **Status:** Researching climate zone requirements
  - **Next Steps:** Check commercial building codes for different regions
  - **Priority:** HIGH

### Utilities & Systems
- [ ] **Is 50A/240V actually enough for full commercial kitchen?**
  - **Status:** Need to calculate load for typical equipment
  - **Notes:** Food trucks typically run 8-12kW generators, so 12kW (50A) might be tight
  - **Next Steps:** List common kitchen equipment wattage
  - **Priority:** HIGH

### Operational Viability
- [ ] **What's realistic container swap time?**
  - **Status:** Estimating based on RV hookup time (30 min) + stabilization
  - **Notes:** RV hookups = 15-30 min, container probably 30-60 min
  - **Next Steps:** Build scale model to test sequence
  - **Priority:** MEDIUM

---

## PRIORITY NEXT ⏳

### Critical Path (Must Answer Before Prototype)

1. **Can 20' container meet ADA requirements with full accessibility?**
   - Category: Physical Infrastructure
   - Why Critical: Regulatory requirement, affects market viability
   - Research Needed: ADA turning radius, door width, path clearance

2. **What's the minimum dock spacing for radial hub configuration?**
   - Category: Physical Infrastructure
   - Why Critical: Determines land requirements, hub economics
   - Research Needed: Vehicle turning radius, walkway clearances

3. **Can containers meet residential building codes, or stuck as "RV/temporary"?**
   - Category: Regulatory
   - Why Critical: Housing application depends on this
   - Research Needed: IRC vs. RV standards, state-by-state variations

4. **What cooking equipment can actually run on 50A service?**
   - Category: Utilities
   - Why Critical: Determines food service viability
   - Research Needed: Equipment load calculations

5. **Is grease trap required per container or per hub?**
   - Category: Regulatory (Food Service)
   - Why Critical: Major cost difference ($500 vs. $5000+)
   - Research Needed: Health department requirements by jurisdiction

6. **What's the cost crossover: build vs. buy containers?**
   - Category: Economic
   - Why Critical: Business model depends on container acquisition strategy
   - Research Needed: Custom fabrication quotes vs. used container + modification

7. **Can containers be craned on/off truck, or need to slide/roll?**
   - Category: Mobility
   - Why Critical: Affects truck design and dock requirements
   - Research Needed: Container handling equipment, safety considerations

8. **What ground surfaces work for container placement?**
   - Category: Physical Infrastructure
   - Why Critical: Determines site requirements, limits deployment locations
   - Research Needed: Stabilizer load distribution, ground pressure

9. **Do we need fire suppression in container, or does building system cover it?**
   - Category: Safety & Code
   - Why Critical: Major cost and design implication
   - Research Needed: Fire code for temporary vs. permanent structures

10. **How many hub locations before vendor mobility becomes valuable?**
    - Category: Network Effects
    - Why Critical: Determines go-to-market strategy
    - Research Needed: Vendor survey, comparable networks (franchises, etc.)

---

## TO RESEARCH 📋

### Physical Infrastructure (15 questions)
- [ ] What reinforcement needed for container structural integrity?
- [ ] What's actual weight limit for fully-built container?
- [ ] Does French cleat system weaken container walls?
- [ ] How does container floor height affect ADA compliance?
- [ ] What's maximum distance utility block can be from container?
- [ ] How do we handle drainage/slope at outdoor docks?
- [ ] What's realistic connect/disconnect time (1 person vs. 2)?
- [ ] Do connections need tool-free operation?
- [ ] What's failure rate of RV connections under daily use?
- [ ] Can single person safely connect all utilities?
- [ ] Are hydraulic jacks necessary or manual stabilizers sufficient?
- [ ] Does container need ground anchoring for wind safety?
- [ ] Can stabilizers deploy while on truck?
- [ ] What's max transport distance before equipment damage?
- [ ] How do we protect interior during transport?

### Utilities & Systems (12 questions)
- [ ] Can we rely on battery backup or just nice-to-have?
- [ ] Does rooftop solar generate enough to matter?
- [ ] What's load profile: escape room vs. food service?
- [ ] Need separate circuits for HVAC vs. general use?
- [ ] Can one rooftop unit heat/cool in extreme climates?
- [ ] What happens if container sits unused for weeks?
- [ ] Need ventilation beyond HVAC (makeup air)?
- [ ] Can mobile HVAC run on battery or requires generator?
- [ ] What's realistic water usage per application?
- [ ] Can we use composting toilets to eliminate black water?
- [ ] Need hot water heater per container or use hub's?
- [ ] How often do grease traps need emptying?

### Data/Network (4 questions)
- [ ] Is ethernet essential or cellular adequate?
- [ ] What bandwidth needed for POS/streaming/cameras?
- [ ] Need redundant internet (fiber + cellular)?
- [ ] Can containers share network or each need dedicated?

### Mobility & Transport (8 questions)
- [ ] What truck chassis needed for 20' container + utilities?
- [ ] Can non-CDL driver operate safely?
- [ ] Is utilities-between-cab stable when driving?
- [ ] Can container be at event while truck picks up another?
- [ ] Can containers move when fully loaded or must be empty?
- [ ] What equipment does hub need to swap containers?
- [ ] What ground anchoring needed?
- [ ] Can all systems be serviced from outside?

### Operational Viability (7 questions)
- [ ] How often can containers swap without excessive wear?
- [ ] Is weekly rotation practical or monthly better?
- [ ] What's maintenance burden of constant connecting?
- [ ] Do connection points need replacing after X swaps?
- [ ] Where do repairs happen - hub or shop?
- [ ] Expected lifespan: weekly swaps vs. permanent?
- [ ] Need redundant systems for uptime?

### Climate Durability (4 questions)
- [ ] Can containers operate in sub-zero temps?
- [ ] What's heat limit - 110°F desert climates ok?
- [ ] Does freeze/thaw damage connections?
- [ ] How handle snow/ice on roof (solar/HVAC)?

### Use Case: Food Service (5 questions)
- [ ] Can mobile meet health dept without permanent sewer?
- [ ] What equipment runs on 50A?
- [ ] Is ventilation adequate or need separate hood?
- [ ] How does grease management work when moving?
- [ ] Can food trucks convert or need complete rebuild?

### Use Case: Entertainment (4 questions)
- [ ] Climate control adequate for electronics/props?
- [ ] Can containers be soundproofed enough?
- [ ] Is lighting power adequate for theatrical effects?
- [ ] How handle reset between groups if mobile?

### Use Case: Housing (5 questions)
- [ ] What's realistic occupancy (1 person? 2? Family)?
- [ ] Can meet residential codes or stuck as "RV"?
- [ ] Is shower/bathroom viable in 160 sq ft?
- [ ] Where does personal storage go?
- [ ] Can someone live in one long-term?

### Economic Viability (4 questions)
- [ ] What's cost: build vs. buy?
- [ ] Cheaper: many containers + few docks OR few containers swapping?
- [ ] Does mobile make money or just subsidize hub?
- [ ] What's payback period on utility block investment?

### Revenue Models (4 questions)
- [ ] Can containers generate revenue in transit?
- [ ] Is demand for rotation or consistent locations?
- [ ] Pricing: per container, per sq ft, or per dock?
- [ ] Do operators own containers and rent docks, or rent both?

### Regulatory & Permitting (8 questions)
- [ ] Are containers "temporary" or "permanent" structures?
- [ ] Does frequent swapping help or hurt permitting?
- [ ] Can residential dock at commercial hubs (zoning)?
- [ ] Max duration at site before different permits?
- [ ] Need fire suppression or building system covers?
- [ ] Egress requirements - one door or need emergency exit?
- [ ] Inspections per container or per dock?
- [ ] Does ADA apply to temporary installations?

### Health Department (Food) (4 questions)
- [ ] Can containers be "commissaries"?
- [ ] Need grease interceptor at every location or hub only?
- [ ] What triggers inspection - moving or time-based?
- [ ] Can same container operate in multiple jurisdictions?

### Standardization & Scaling (9 questions)
- [ ] What's minimum spec for "standard compatible"?
- [ ] Who certifies compliance?
- [ ] How handle version updates (v1.0 → v2.0)?
- [ ] What's enforceable vs. recommended?
- [ ] Can containers be mass-produced or always custom?
- [ ] Is there minimum order quantity?
- [ ] Should we certify manufacturers?
- [ ] What's quality control process?
- [ ] How prevent fragmentation (competing standards)?

### Network Effects (4 questions)
- [ ] How many hubs before vendor mobility valuable?
- [ ] Can we start one city or need multi-city?
- [ ] Chicken-egg: build docks or containers first?
- [ ] Do electrical standards differ enough for regional versions?

### Proof of Concept (4 questions)
- [ ] What must scale model prove?
- [ ] Can we simulate connections with 3D prints?
- [ ] What measurements validate design?
- [ ] Does model need working utilities?

### Prototype Phase (4 questions)
- [ ] Build one container + dock or minimum two each?
- [ ] Test duration - weeks, months, year?
- [ ] Who are test operators?
- [ ] What failure points acceptable in prototype?

### Validation Metrics (4 questions)
- [ ] What proves viability: X swaps? Y hours? Z revenue?
- [ ] How measure "ease of use" quantitatively?
- [ ] What's benchmark - better than food truck? Permanent?
- [ ] When do we know enough for investors?

---

## NOTES & INSIGHTS

### Key Design Decisions Made
1. **Single utility end (back)** - Simplifies container, reduces cost
2. **RV-style connections** - Proven, cheap, serviceable everywhere
3. **Bi-directional docking** - Either approach direction works
4. **Rooftop HVAC** - Simpler than mini-split for mobile use
5. **Utility block at far end of dock** - Container faces building

### Open Questions Themes
- **Regulatory uncertainty** - Biggest unknown, varies by jurisdiction
- **Commercial kitchen power** - 50A might be limiting factor
- **Network effects** - Need critical mass of hubs for value
- **Housing codes** - Can we get residential classification?

### Research Priorities
1. **ADA compliance** - Affects all use cases
2. **Kitchen electrical loads** - Determines food service viability
3. **Building codes** - Housing application depends on this
4. **Grease trap requirements** - Major cost driver

---

*This document is continuously updated as research progresses. Last major update: 2024-12-25*
