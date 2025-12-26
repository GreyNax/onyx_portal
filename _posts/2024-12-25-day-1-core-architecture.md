---
layout: post
title: "Day 1: Core Architecture Decisions"
date: 2024-12-25
categories: [design, decisions]
tags: [containers, utilities, RV-standards, docking]
---

Today was the first deep design session for the Obsidian Portal. We started with a vague concept about modular escape rooms in shipping containers and ended with a coherent technical approach that leverages 50+ years of proven RV industry standards.

## The Big Decisions

### Single Utility End (Not Both)

**Decision:** Containers have utilities at ONE end (rear) only.

I initially thought we'd need utility connections at both ends for maximum flexibility. But that would mean:
- Duplicate plumbing/electrical systems (+$7,000-12,000 per container)
- More maintenance points
- Structural complications

Instead, we're going with:
- **Front:** Full-width doors (7'8" opening) for dramatic guest entrance
- **Rear:** Solid wall + single utility panel

**Why this works:** The utility block positioning at the hub makes bi-directional docking possible anyway (see below).

### Bi-Directional Docking Discovery

**The insight:** If the utility block is at the FAR END of the dock pad, containers can approach from either direction and still end up in the correct position.

```
Back in:  [Building] ⇔ [Container FRONT...BACK] ← [Utility Block]
Drive in: [Building] ⇔ [Container FRONT...BACK] ← [Utility Block]
```

Same final position, different approach. This gives us:
- Site flexibility (work around obstacles)
- Driver preference (some better at backing, some prefer forward)
- Traffic flow optimization
- No cost increase

**I love solutions where constraints create unexpected benefits.**

### Don't Reinvent the Wheel - Use RV Standards

This was the breakthrough moment. Instead of custom-engineering everything, we're adopting proven RV and food truck connection standards:

**Electrical:** NEMA 14-50 (50A/240V)
- Same plug as large RVs and Tesla chargers
- Parts at every hardware store
- Every electrician knows it
- Locking weatherproof versions available

**Water:** ¾" garden hose thread (GHT) with pressure regulator
- Literally a garden hose connection
- RV city water standard
- Universal, cheap, simple

**Wastewater:** 3" RV dump station connection
- Bayonet/twist-lock
- Can dump at any RV facility when mobile
- $30 in parts vs. thousands for custom

**Impact on costs:**
- Utility block: ~$3,000-5,000 (modified RV pedestal)
- vs. $15,000-25,000 for custom engineering
- **Savings: ~$10,000-20,000 per dock position**

Plus: Service network already exists. Every town has RV repair shops. This isn't theoretical—it's proven for decades.

### Mobile Strategy: Reduced Functionality is OK

Initially I thought mobile containers needed full parity with hub operations. But that's wrong.

**Reality check:**
- Mobile events are 4-8 hours, not 12+ hour daily operation
- Food trucks work with limited water/power, so can we
- Battery + generator sufficient for event duration
- Simpler systems = lower cost = more accessible

**Mobile module:** $15,000-25,000  
**Full parity module:** $40,000+

The cost difference enables more people to participate. And for permanent operation, that's what hubs are for.

## Technical Approach Solidified

### The Core Standard (Minimum Required)
1. Electrical: NEMA 14-50 (50A/240V)
2. Data: Cat6 ethernet (4 ports)
3. HVAC: 12" round duct coupling

### Optional Extensions
4. Water/wastewater (for food service, housing)
5. Propane (for cooking, heating)
6. Higher amperage (100A, 200A for intensive use)

This lets us have:
- **"Basic docks"** for entertainment/retail (~$5,000)
- **"Food service docks"** with full utilities (~$15,000-20,000)
- **"Residential docks"** for housing (~$25,000-35,000)

Build what you need, not what you might need someday.

## The Vision Crystalized

**Phase 1:** Entertainment (escape rooms, D&D venues)
- Prove modularity commercially
- Generate revenue
- Build operator community

**Phase 2:** Food service & retail
- Test higher-intensity utilities
- Grow hub network
- Enable vendor mobility

**Phase 3:** Affordable housing
- Apply proven infrastructure
- Portable homeownership
- Economic mobility

**The funding model:** Entertainment profits → housing R&D → open standard → systemic change.

## Why Open Standard?

The more I think about this, the more convinced I am that this only works as an open standard, not a proprietary system.

**Network effects are the moat:**
- 1 hub = limited value
- 10 hubs = regional mobility  
- 50+ hubs = national network
- Each new hub benefits ALL participants

Like shipping containers themselves (ISO standard), USB connectors, or electrical outlets - the value is in universal compatibility.

Anyone should be able to:
- Build containers to spec
- Operate hub locations
- Manufacture components
- Compete on quality/service/price

We're not selling a product. We're creating infrastructure standards that enable an ecosystem.

## Questions That Keep Me Up

**Is 50A actually enough for a commercial kitchen?**
Food trucks run on 8-12kW generators, so 12kW (50A @ 240V) should work. But I need to calculate actual loads for common equipment. This is a critical question—if we need 100A, that changes the whole electrical spec.

**Can 160 sq ft meet ADA requirements?**
Wheelchair turning radius is 60" diameter. Container interior is 90" wide. Theoretically yes, but need to validate with actual layouts. This affects ALL use cases.

**What building code classification?**
Are these "temporary structures" or "permanent buildings"? Varies by jurisdiction. Temporary = easier permitting but limited uses. Permanent = harder permitting but enables housing. Need to research this jurisdiction by jurisdiction.

## What Changed Today

Started with: "Modular escape rooms in containers"

Ended with:
- Clear three-phase vision (entertainment → commerce → housing)
- Proven technology approach (RV standards, not custom)
- Open standard philosophy (network effects over ownership)
- Practical path forward (scale model → prototype → hub)

**The concept went from "interesting idea" to "this might actually work."**

## Next Steps

1. Design 1:12 scale model (3D printable components)
2. Answer priority questions (ADA, electrical loads, building codes)
3. Calculate commercial kitchen power requirements
4. Draft technical specification v1.0
5. Start reaching out to potential test operators

The research phase is just beginning, but at least now I know what questions to answer.

---

*All design decisions documented in [/decisions/2024-12-25-core-design-decisions](/decisions/2024-12-25-core-design-decisions/)*

*Full technical questions list: [/research/technical-questions](/research/technical-questions/)*
