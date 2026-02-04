# Guidance: DEL-02.12 Piping General Arrangement (GA) Drawings

## 1. Purpose

### 1.1 Document Intent
This guidance document provides practical direction for developing Piping General Arrangement (GA) Drawings for the PSO Project at Sumas Tank Farm. It addresses routing considerations, brownfield coordination, and best practices for producing construction-ready drawings.

### 1.2 Target Audience
- Piping Designers and Layout Engineers
- 3D Model Coordinators
- Piping Engineers
- Construction Planners

### 1.3 Context
Piping GA drawings are the primary documents for communicating pipe routing and arrangement to construction. For the PSO Project, these drawings must address:
- Integration with existing Sumas Tank Farm infrastructure (brownfield)
- New booster pump station and manifold piping systems
- Tie-in coordination with operating facilities
- Above-ground and below-ground piping considerations

## 2. Principles

### 2.1 Core Principles

| Principle | Description |
|-----------|-------------|
| **Model-Based Delivery** | GA drawings extracted from validated 3D model; drawings and model remain synchronized |
| **Constructability** | Layout supports practical fabrication, installation, and testing |
| **Operability** | Routing provides access for operation, maintenance, and emergency response |
| **Integration** | Seamless coordination with existing Sumas Tank Farm infrastructure |
| **Clarity** | Clear communication of routing intent without cluttering |

### 2.2 Drawing Hierarchy

```
Piping Key Plan (DEL-02.04)
    |
    +-- Piping Site Plan (DEL-02.05)
            |
            +-- Demolition Plan (DEL-02.06)
            |
            +-- Area Plans (DEL-02.09)
                    |
                    +-- Equipment Layout (DEL-02.10)
                            |
                            +-- Piping GA Drawings (DEL-02.12) <-- This deliverable
                                    |
                                    +-- Piping Isometrics (DEL-02.13)
                                    |
                                    +-- Support Location Plans (DEL-02.17)
```

### 2.3 Relationship to Other Deliverables
- **P&IDs (DEL-01.03)**: GA must show all piping represented on P&IDs
- **Line List (DEL-02.01)**: Line numbers on GA must match Line List
- **Isometrics (DEL-02.13)**: GA routing must be consistent with isometric details
- **3D Model (DEL-02.28)**: GA extracted from and verified against model

## 3. Considerations

### 3.1 Project-Specific Considerations (Sumas Tank Farm)

| Factor | Impact | Guidance |
|--------|--------|----------|
| Brownfield Site | Tie-ins to existing systems | Coordinate early with TM Operations; verify as-built conditions |
| Booster Pumps (5 units) | Multiple suction/discharge routes | Organize routing to minimize crossings; maintain pump isolation capability |
| 5x6 Manifold | Complex header routing | Plan manifold arrangement for blending flexibility per SOW-0005 |
| Flow Meters | Each pump discharge has meter | Allow straight run requirements per meter specifications |
| VFDs | Electrical routing adjacent to piping | Coordinate with electrical for cable tray separation |
| Existing Tank TK-102 | Proximity constraint | Maintain required clearances; verify tank shell clearance zones |

### 3.2 Technical Routing Considerations

| Topic | Guidance |
|-------|----------|
| **Pipe Routing** | Minimize pipe lengths while maintaining access; follow rack routing where practical |
| **Valve Access** | Ensure operators can reach handwheels (typical 1.5m height) and actuators |
| **Instrument Access** | Provide access for calibration and maintenance; consider platform needs |
| **Drain Points** | Locate at low points for complete drainage; size per design requirements |
| **Vent Points** | Locate at high points for air release; ensure accessible |
| **Thermal Expansion** | Allow for thermal movement; coordinate with stress analysis (DEL-02.14) |
| **Pigging Considerations** | If applicable, ensure piggable routing with pig launcher/receiver access |

### 3.3 Below-Ground Piping Considerations

| Topic | Guidance |
|-------|----------|
| Depth of Cover | Minimum per CSA Z662 and frost requirements (TBD) |
| Pipe Crossings | Coordinate with civil for road crossing details and sleeve requirements |
| Cathodic Protection | Show CP test stations, ground beds, and anode locations per CP design |
| Utility Conflicts | Verify no conflicts with existing underground utilities via survey |
| Coating Requirements | Note coating specifications for buried sections |
| Backfill Requirements | Reference civil specifications for backfill materials |

### 3.4 Coordination Requirements

| Discipline | Coordination Focus |
|------------|-------------------|
| Process Engineering | P&ID alignment, process requirements |
| Mechanical | Equipment nozzle data, maintenance access |
| Civil/Structural | Below-ground routing, pipe support loads, foundations |
| Electrical | Cable tray separation, hazardous area considerations |
| I&C | Instrument locations, control valve access |
| 3D Modeling | Model consistency at all revision stages |
| Construction | Installation sequence, access, temporary supports |
| TM Operations | Tie-in requirements, operational constraints |

## 4. Trade-offs

### 4.1 Routing Approach Options

| Approach | Pros | Cons | When to Use |
|----------|------|------|-------------|
| Shortest Route | Lower cost, less material | May compromise access, complex support | Non-critical utility lines |
| Organized Rack Routing | Neat appearance, easy access, common supports | Longer pipe runs, higher material cost | Primary process piping |
| Underground Routing | Clears surface space, protects pipe | Higher cost, harder maintenance, CP required | Road crossings, congested areas |

**Recommendation**: Use organized rack routing for primary booster pump and manifold piping; underground only where surface routing is impractical.

### 4.2 Drawing Organization Options

| Option | Pros | Cons | Recommendation |
|--------|------|------|----------------|
| By Elevation | Clear vertical separation | May split systems across drawings | Use for multi-level facilities |
| By Area | Logical grouping, matches Key Plan | May require many match lines | Preferred for PSO site layout |
| By System | Complete system view | Overlaps with other systems | Consider for manifold system |

### 4.3 Annotation Density

| Approach | Pros | Cons | Balance Point |
|----------|------|------|---------------|
| Dense Annotation | All information on one drawing | Cluttered, hard to read | Not recommended |
| Minimal Annotation | Clean appearance | Missing construction information | Not recommended |
| Balanced | Clear communication, readable | Requires judgment | Show line numbers, major dimensions, valve tags; reference isometrics for detail |

## 5. Examples

### 5.1 GA Drawing Content Checklist

**Piping Elements:**
- [ ] All process piping shown with line numbers
- [ ] Pipe sizes indicated at changes
- [ ] Flow direction arrows on major headers
- [ ] Valve locations with tag numbers
- [ ] Instrument locations (flow meters, control valves)
- [ ] Drain and vent locations
- [ ] Tie-in locations marked

**Equipment Interface:**
- [ ] Equipment outlines from layout
- [ ] Nozzle connections shown
- [ ] Nozzle orientations verified against vendor data
- [ ] Pump suction/discharge clearly identified

**Annotation:**
- [ ] Dimensions from grid/benchmarks
- [ ] Elevations for vertical changes
- [ ] Match lines to adjacent drawings
- [ ] Section cut references
- [ ] North arrow and scale
- [ ] Legend and general notes

### 5.2 Typical View Organization for PSO

```
Drawing Set Organization (ASSUMPTION):

DEL-02.12-001: Booster Pump Area - Plan at Grade (EL xxx.xx)
DEL-02.12-002: Booster Pump Area - Plan at Pipe Rack (EL xxx.xx)
DEL-02.12-003: Manifold Area - Plan View
DEL-02.12-004: Tie-In Area - Plan View
DEL-02.12-005: Sections - Equipment Connections
DEL-02.12-006: Sections - Road Crossings and Below-Ground
```

### 5.3 Line Number Annotation Format (ASSUMPTION - confirm with TM)

```
Show on drawings:
  16"-P-2501-C3B-IH
  |    |    |   |
  |    |    |   +-- Insulation/Heat Trace code
  |    |    +------ Piping Material Class
  |    +----------- Line Number
  +---------------- Nominal Pipe Size

Plus: Flow direction arrow for headers
```

### 5.4 Common Issues to Avoid

| Issue | Consequence | Prevention |
|-------|-------------|------------|
| Piping conflicts with structural steel | Field rework, delays | 3D clash detection before issuing |
| Insufficient access for valve operation | Operational difficulties | Review handwheel heights, platform needs |
| Missing support locations at heavy valves | Stress issues, sagging | Coordinate with stress analysis (DEL-02.14) |
| Inadequate clearance at road crossings | Code violation, safety issue | Verify depth of cover requirements |
| Inconsistency between GA and isometrics | Fabrication errors | Single model source for both |
| Missing connections shown on P&ID | Incomplete installation | P&ID walkdown verification |

### 5.5 Brownfield Coordination Checklist

- [ ] Tie-in locations coordinated with TM Operations
- [ ] Existing pipe rack capacity verified (load, space)
- [ ] Underground utility survey obtained and overlaid
- [ ] Existing equipment clearances maintained
- [ ] Operating area access preserved during construction
- [ ] Temporary construction access paths identified
- [ ] Shutdown/tie-in sequence discussed with Operations
- [ ] As-built verification for existing systems completed

---
*Document generated 2026-02-01 | Deliverable Status: OPEN*
