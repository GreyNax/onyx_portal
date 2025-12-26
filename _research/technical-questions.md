---
title: "Technical Questions Master List"
layout: page
permalink: /research/technical-questions/
---

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
  - **Source:** [Day 1 Design Session](/blog/2024/12/25/day-1-core-architecture/)
  - **Implications:** Container has consistent orientation (front=doors, back=utilities)

- [x] **Can containers dock facing either direction (front-in or back-in)?**
  - **Answer:** YES - both directions work
  - **Rationale:** Utility block at far end of dock means container can back in OR drive in forward
  - **Source:** [Day 1 Design Session](/blog/2024/12/25/day-1-core-architecture/)
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

*Full list of priority questions and all research categories in the [GitHub repository](https://github.com/GreyNax/onyx_portal).*

1. **Can 20' container meet ADA requirements?**
2. **Is 50A enough for commercial kitchen?**
3. **Can containers meet residential building codes?**
4. **Grease trap per container or per hub?**
5. **Cost crossover: build vs. buy containers?**

[See complete technical questions →](https://github.com/GreyNax/onyx_portal/blob/main/research/technical-questions.md)

---

*This page is continuously updated as research progresses.*
