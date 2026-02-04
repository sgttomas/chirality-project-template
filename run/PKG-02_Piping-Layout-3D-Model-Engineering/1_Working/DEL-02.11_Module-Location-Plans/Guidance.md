# Guidance: DEL-02.11 Module Location Plans

## 1. Purpose

### 1.1 Document Intent
This guidance document provides practical direction for developing Module Location Plans for the PSO Project at Sumas Tank Farm. It addresses common challenges, recommended approaches, and considerations for modular construction placement at brownfield sites.

### 1.2 Target Audience
- Piping/Layout Engineers
- 3D Model Coordinators
- CAD Technicians
- Construction Planners
- Discipline Lead Engineers

### 1.3 Context
Module Location Plans bridge the gap between detailed equipment layouts and overall site plans by showing where prefabricated assemblies will be positioned. For the PSO Project, this is particularly important given:
- Brownfield installation constraints at an operating tank farm (Sumas Tank Farm)
- Multiple pump skids and manifold assemblies requiring precise positioning
- Interface management between new modules and existing TK-102 infrastructure
- Limited access routes and laydown areas at the site

## 2. Principles

### 2.1 Core Principles

| Principle | Description |
|-----------|-------------|
| **Clarity First** | Module boundaries and interfaces must be immediately recognizable without reference to other drawings |
| **Constructability Focus** | Plans should support installation planning, not just document design intent |
| **Coordination Integrity** | All positions must derive from a single source of truth (3D model) |
| **Brownfield Awareness** | Existing infrastructure constraints must be prominently shown |
| **Installation Sequence** | Module positions should accommodate logical installation order |

### 2.2 Design Philosophy
- **Modular Thinking**: Treat each module as a self-contained unit with defined interface boundaries
- **Access Preservation**: Maintain access for maintenance even after all modules are installed
- **Reference Consistency**: Use the same coordinate grid and reference points as all related drawings
- **Future Flexibility**: Consider potential module repositioning needs during construction sequencing

### 2.3 Relationship to Other Drawings

```
Overall Plot Plan (DEL-02.08)
    |
    +-- Area Plans (DEL-02.09)
            |
            +-- Equipment Layout Plans (DEL-02.10)
                    |
                    +-- Module Location Plans (DEL-02.11) <-- This deliverable
                            |
                            +-- Piping GA Drawings (DEL-02.12)
                            |
                            +-- Module/Prefab List (DEL-02.27)
```

## 3. Considerations

### 3.1 Project-Specific Considerations (Sumas Tank Farm)

| Factor | Impact | Consideration |
|--------|--------|---------------|
| Proximity to TK-102 | Limited maneuvering space for module installation | Plan installation sequence to avoid trapped modules |
| Existing Infrastructure | Underground utilities, foundations, piping | Verify as-built conditions via survey/scan before finalizing positions |
| Operating Facility | Safety zones and operational access during installation | Coordinate with TM Operations for constraints |
| Containment Requirements | New containment wall per SOW-0003 | Sequence modules relative to containment construction |
| Site Access | Limited access routes for heavy transport | Confirm transport routes and crane positions early |

### 3.2 Technical Considerations

| Topic | Guidance |
|-------|----------|
| **Foundation Interface** | Module locations must align precisely with civil/structural foundation designs; coordinate early with PKG-04 |
| **Piping Flexibility** | Allow for field adjustment at module interfaces; consider flexible connectors or spool pieces |
| **Equipment Envelope** | Include maintenance envelopes and equipment removal paths in positioning decisions |
| **Cathodic Protection** | Consider CP ground bed locations and anode positions when siting modules near existing tanks |
| **Crane Access** | Ensure crane reach and load path for module setting; show swing radius if critical |
| **Elevation Control** | Match module base elevations to foundation top elevation; verify drainage |

### 3.3 Interface Considerations

| Interface Type | Guidance |
|----------------|----------|
| **Piping Interfaces** | Show flange faces and orientation at module boundaries; consider alignment tolerance |
| **Electrical Interfaces** | Indicate junction box locations and cable entry points; coordinate with PKG-06 |
| **Instrument Interfaces** | Show tubing/cable termination points; coordinate with PKG-07 |
| **Structural Interfaces** | Reference anchor bolt patterns and embedments; coordinate with PKG-04 |

### 3.4 Coordination Requirements
- Coordinate with Mechanical (PKG-03) for equipment skid boundaries and weights
- Coordinate with Civil/Structural (PKG-04) for foundation design and anchor locations
- Coordinate with Electrical (PKG-06) for power connection points and cable routing
- Coordinate with I&C (PKG-07) for instrument connections and cable trays
- Align with Construction for installation sequence and laydown planning

## 4. Trade-offs

### 4.1 Modularization Approaches

| Approach | Pros | Cons | Recommendation |
|----------|------|------|----------------|
| Maximum Modularization | Reduced site labor, better quality control, faster installation | Transport constraints, higher upfront engineering, larger crane requirements | Consider for pump skids with integrated piping |
| Minimum Modularization | Flexibility, lower transport cost, smaller lifts | More site labor, weather exposure, longer schedule | May apply for some piping assemblies |
| Hybrid Approach | Balanced benefits, optimized for site constraints | Coordination complexity | ASSUMPTION: Likely approach for PSO |

### 4.2 Drawing Organization Options

| Option | When to Use | Recommendation |
|--------|-------------|----------------|
| Combined with Equipment Layout | Small scope with few modules | Not recommended for PSO scope |
| Separate Module Plans | Multiple modules requiring clarity | Preferred approach |
| Organized by Installation Phase | Phased installation sequence | Consider if construction phasing is defined |
| Organized by Area | Large site with distinct areas | May not apply to concentrated PSO footprint |

### 4.3 Detail Level Trade-offs

| Aspect | More Detail | Less Detail | Balance Point |
|--------|-------------|-------------|---------------|
| Equipment shown | All equipment in modules | Module outlines only | Show major equipment tags for reference |
| Dimensions | All critical dimensions | Reference to grid only | Dimension from grid plus key module-to-module |
| Annotations | Extensive notes | Minimal notes | Standard notes; reference separate procedures |
| Interfaces | All connection details | Interface locations only | Show interface type and reference detail drawings |

## 5. Examples

### 5.1 Typical Drawing Content Layout

```
+------------------------------------------------------------------+
|  MODULE LOCATION PLAN - BOOSTER PUMP AREA                        |
|  Drawing No: 2500-PKG02-MP-001  Rev: 0                           |
+------------------------------------------------------------------+
|                                                                   |
|   [NORTH ARROW]                     [KEY PLAN REFERENCE]          |
|                                                                   |
|   GRID REFERENCES: N 1234500 / E 567800                          |
|                                                                   |
|   +-------------+  +-------------+  +-------------+               |
|   |  MODULE 1   |  |  MODULE 2   |  |  MODULE 3   |               |
|   |  P-101 SKID |  |  P-102 SKID |  |  P-103 SKID |               |
|   | (LARGE CAP) |  | (LARGE CAP) |  | (MEDIUM)    |               |
|   |   [VFD]     |  |   [VFD]     |  |   [VFD]     |               |
|   +------+------+  +------+------+  +------+------+               |
|          |                |                |                      |
|   -------+----------------+----------------+--------              |
|          MANIFOLD MODULE (5x6 HEADER)                             |
|   --------------------------------------------------              |
|          |                |                                       |
|   +------+------+  +------+------+                                |
|   |  MODULE 4   |  |  MODULE 5   |                                |
|   |  P-104 SKID |  |  P-105 SKID |                                |
|   | (SMALL CAP) |  | (SMALL CAP) |                                |
|   +-------------+  +-------------+                                |
|                                                                   |
|   LEGEND:                            GENERAL NOTES:               |
|   +---+ Module Boundary              1. See DEL-02.27 for         |
|   --+-- Pipe Interface                  module attributes         |
|   --o-- Electrical Interface         2. Coordinates per site      |
|   --x-- Instrument Interface            survey datum              |
|                                      3. Refer to DEL-02.10 for    |
|                                         equipment details         |
+------------------------------------------------------------------+
```

### 5.2 Module Interface Schedule Example

| Interface ID | From Module | To Module | Type | Size/Rating | Notes |
|--------------|-------------|-----------|------|-------------|-------|
| IF-001 | P-101 Skid | Manifold | Pipe | 16" 300# RF | Spool piece at interface |
| IF-002 | P-102 Skid | Manifold | Pipe | 16" 300# RF | Spool piece at interface |
| IF-003 | P-103 Skid | Manifold | Pipe | 12" 300# RF | Flexible connector |
| IF-004 | VFD Bldg | P-101 Skid | Elec | 4160V | Refer to electrical SLD |
| IF-005 | JB-101 | P-101 Skid | Inst | Multi-pair | Refer to I&C loop diagrams |

### 5.3 Common Mistakes to Avoid

| Mistake | Consequence | Prevention |
|---------|-------------|------------|
| Using outdated 3D model extraction | Module positions do not match current design | Establish model freeze dates aligned with drawing milestones |
| Omitting lifting/handling clearances | Installation conflicts, crane access issues | Include crane swing radius and rigging clearances on plan |
| Ignoring underground utilities | Field relocations required | Overlay existing underground drawings; verify with survey |
| Inconsistent tagging | Confusion during installation | Single source for module tags (DEL-02.27) |
| Missing interface details | Field fit-up issues | Clearly show interface locations with references to detail drawings |
| Not coordinating with foundations | Module/foundation mismatch | Joint review with civil/structural at each milestone |

### 5.4 Coordination Checklist

- [ ] Module positions verified against latest 3D model (DEL-02.28)
- [ ] Foundation locations confirmed with civil/structural (PKG-04)
- [ ] Access and egress paths reviewed for adequacy
- [ ] Interface points coordinated with piping isometrics (DEL-02.13)
- [ ] Electrical interface locations confirmed (PKG-06)
- [ ] I&C interface locations confirmed (PKG-07)
- [ ] Constructability review conducted with construction team
- [ ] Module list (DEL-02.27) cross-referenced for completeness
- [ ] Existing underground utilities verified
- [ ] Crane access and lift paths reviewed
- [ ] Laydown areas identified if applicable

---
*Document generated 2026-02-01 | Deliverable Status: OPEN*
