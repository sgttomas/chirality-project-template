# Guidance: Valve List (Piping)

## 1. Purpose

### 1.1 Document Intent
This guidance document provides direction on developing the Valve List for the Puget Sound Optimization Project, addressing practical considerations, industry best practices, and project-specific requirements.

### 1.2 Target Audience
- Piping Engineers
- Piping Designers
- Procurement Specialists
- Document Controllers

## 2. Principles

### 2.1 Core Principles
| Principle | Description |
|-----------|-------------|
| **Single Source of Truth** | The Valve List serves as the master reference for all valves in the project scope |
| **Traceability** | Every valve must be traceable to its source P&ID and line |
| **Procurement Support** | Structure to support valve procurement and MTO development |
| **Maintainability** | Structure to support updates through all project phases |

### 2.2 Data Hierarchy
```
P&IDs (Process Source)
    └── Valve List (Master Register)
            ├── MTO (Procurement Quantities)
            ├── Specialty Items List (Special Valves)
            ├── Piping Isometrics (Installation Details)
            └── Valve Datasheets (Technical Details)
```

## 3. Considerations

### 3.1 Project-Specific Considerations

| Consideration | Details |
|---------------|---------|
| **Booster Pump Valves** | Suction/discharge isolation for 5 new VS6 pumps |
| **Manifold Valves** | 5x6 manifold requires extensive isolation capability |
| **Blending Control** | Valves supporting flow ratio control (20% Heavy / 80% Light) |
| **Flow Capacity** | Size valves for 315,000 bpd peak flow rate |
| **Existing Systems** | Coordinate with existing Sumas Tank Farm valve inventory |

### 3.2 Technical Considerations

| Topic | Guidance |
|-------|----------|
| **Valve Tagging** | Coordinate with TM to confirm tagging convention before starting (**TBD**) |
| **Actuated Valves** | Coordinate with I&C for actuator requirements and fail positions |
| **Check Valves** | Ensure correct orientation and type for pump discharge applications |
| **Emergency Isolation** | Identify ESD valves and coordinate with Safety Engineering |

### 3.3 Coordination Requirements
- Coordinate with Process Engineering for valve sizing basis
- Coordinate with Instrumentation for actuated valve requirements
- Coordinate with Mechanical for vendor-supplied valves
- Align with Line List for line number references

## 4. Trade-offs

### 4.1 Valve Selection Considerations

| Topic | Trade-off | Recommendation |
|-------|-----------|----------------|
| **Gate vs. Ball** | Gate for tight shutoff; Ball for quick operation | Per TM standard (**TBD**) |
| **Flanged vs. BW** | Flanged for maintenance access; BW for leak prevention | Per piping class and size |
| **MOV vs. AOV** | MOV for fail-in-place; AOV for fail-safe | Per process safety requirements |

### 4.2 Data Management Trade-offs

| Trade-off | Recommendation |
|-----------|----------------|
| **Manual vs. Auto-extraction** | Use P&ID extraction with manual verification |
| **Single file vs. Multiple** | Single consolidated file with system/area filters |
| **Early freeze vs. Late updates** | Progressive freeze aligned with procurement |

## 5. Examples

### 5.1 Sample Valve Tag Format (**ASSUMPTION** - confirm with TM)
```
VV-XXXXX-NNN

Where:
VV    = Valve type code (e.g., XV = isolation, CV = control, CK = check)
XXXXX = Area/system code
NNN   = Sequence number
```

### 5.2 Sample Valve List Entry

| Tag | Line No | Type | Size | Rating | Class | Ends | Operator | Fail | Service |
|-----|---------|------|------|--------|-------|------|----------|------|---------|
| XV-SF001-001 | SF-OIL-0800-001 | Gate | 8" | 300# | A1A1 | RF | MOV | As-Is | Crude Oil |
| CK-SF001-002 | SF-OIL-0800-001 | Check | 8" | 300# | A1A1 | RF | - | - | Crude Oil |

### 5.3 Common Issues to Avoid
1. Duplicate valve tags across systems
2. Missing actuator fail position for control/ESD valves
3. Inconsistent valve type designations
4. Missing check valves shown on P&IDs
5. Mismatched line number references

### 5.4 SOW Traceability
This deliverable supports the following SOW requirements:
- **SOW-0120**: Produce FEED valve list (VLL) - per SOW Section 3.1.3.1 (p7-8)
- **SOW-0119**: Produce FEED mechanical/electrical datasheets for valves (incl check valves/actuators) - per SOW Section 3.1.3.1 (p7)

---
*Generated 2026-02-01 | SOW Refs: SOW-0119, SOW-0120*
