# Guidance: Piping Site Plan

## 1. Purpose

### 1.1 Document Intent
This guidance document provides direction on developing the Piping Site Plan for the Puget Sound Optimization Project, addressing practical considerations, industry best practices, and project-specific requirements.

### 1.2 Target Audience
- Piping Engineers
- Piping Designers
- CAD Technicians
- 3D Model Coordinators

## 2. Principles

### 2.1 Core Principles
| Principle | Description |
|-----------|-------------|
| **Routing Overview** | The Site Plan shows overall piping routing across the project footprint |
| **Model Consistency** | Drawing must be consistent with 3D model |
| **Construction Reference** | Serves as primary reference for piping installation planning |
| **Coordination Tool** | Used for clash detection with other disciplines |

### 2.2 Drawing Hierarchy
```
Key Plan (Site Overview + Index)
    └── Site Plan (Piping Overview) <-- This deliverable
            └── Area Plans (Zone Details)
                    └── GA Drawings (Equipment/Piping Details)
                            └── Isometrics (Fabrication Details)
```

## 3. Considerations

### 3.1 Project-Specific Considerations

| Consideration | Details |
|---------------|---------|
| **Booster Pump Piping** | 5 new VS6 pumps with suction/discharge piping |
| **Manifold Piping** | 5x6 manifold header system |
| **Containment Wall** | New containment affecting piping routing |
| **Existing Systems** | Tie-ins to existing tank farm piping |
| **Flow Capacity** | Lines sized for 315,000 bpd peak |

### 3.2 Technical Considerations

| Topic | Guidance |
|-------|----------|
| **Above-Ground Routing** | Show on sleepers/racks with support locations |
| **Below-Ground Routing** | Show dashed with depth annotations |
| **Road Crossings** | Coordinate with Civil for bridge/culvert requirements |
| **Valve Locations** | Show major isolation and control valves |
| **Expansion Loops** | Show thermal expansion provisions |

### 3.3 Coordination Requirements
- Coordinate with Civil for underground utility conflicts
- Coordinate with Structural for pipe rack/support loads
- Coordinate with Electrical for cable tray routing conflicts
- Coordinate with Process for P&ID consistency
- Extract from 3D model for accuracy

## 4. Trade-offs

### 4.1 Routing Approaches

| Approach | Pros | Cons |
|----------|------|------|
| **Above-Ground** | Accessible for maintenance | More supports, visual impact |
| **Below-Ground** | Protected, out of way | Excavation cost, access difficulty |
| **Pipe Racks** | Organized, shared supports | Higher initial cost |
| **Sleepers** | Lower cost for single lines | More ground footprint |

### 4.2 Drawing Detail Level

| Detail Level | Pros | Cons |
|--------------|------|------|
| **High Detail** | More information visible | Cluttered, harder to read |
| **Low Detail** | Clean, easy to read | May miss critical information |

**Recommendation**: Show sufficient detail for routing clarity; detailed dimensions in GA drawings.

## 5. Examples

### 5.1 Sample Line Representation
```
Above-Ground Piping:
────────────────  (solid line with line number)
    8"-SF-OIL-001-A1A1

Below-Ground Piping:
- - - - - - - -   (dashed line with line number)
    6"-SF-OIL-002-A1A1 (BG)

Pipe Rack:
══════════════  (double line with designation)
    RACK-01
```

### 5.2 Sample Drawing Layers (**ASSUMPTION** - confirm with TM)

| Layer Name | Content | Color |
|------------|---------|-------|
| PIPE-AG | Above-ground piping | Red |
| PIPE-BG | Below-ground piping | Magenta |
| PIPE-RACK | Pipe racks/sleepers | Gray |
| EQUIP | Equipment outlines | Cyan |
| GRID | Coordinate grid | Green |
| TXT-LINE | Line numbers | White |

### 5.3 Common Issues to Avoid
1. Piping routes not matching 3D model
2. Missing below-ground piping representation
3. Inconsistent line numbering with Line List
4. Missing tie-in points
5. No coordination with underground utilities
6. Scale not suitable for detail visibility

### 5.4 SOW Traceability
This deliverable supports the following SOW requirements:
- **SOW-0123**: Produce FEED piping site plan (GA) - per SOW Section 3.1.3.1 (p7-8)
- **SOW-0247**: Update/finalize site-specific drawings (area/key/equipment layout/module location/plot plan/GA drawings) - per SOW Section 3.2.4.8 (p19)
- **SOW-0252**: Develop piping general arrangement drawings depicting above/below ground piping, equipment connections, instrument/nozzle locations, road crossings/pipe bridges, and CP connection points/ground anodes - per SOW Section 3.2.4.13 (p20)

---
*Generated 2026-02-01 | SOW Refs: SOW-0123, SOW-0247, SOW-0252*
