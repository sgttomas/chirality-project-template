# Guidance: Line List

## 1. Purpose

### 1.1 Document Intent
This guidance document provides direction on developing the Line List for the Puget Sound Optimization Project, addressing practical considerations, industry best practices, and project-specific requirements.

### 1.2 Target Audience
- Piping Engineers
- Piping Designers
- Document Controllers
- 3D Model Coordinators

## 2. Principles

### 2.1 Core Principles
| Principle | Description |
|-----------|-------------|
| **Single Source of Truth** | The Line List serves as the master reference for all piping in the project scope |
| **Traceability** | Every line must be traceable to its source P&ID and process data |
| **Consistency** | Line numbering and data formats must be consistent across all deliverables |
| **Maintainability** | Structure to support updates through all project phases |

### 2.2 Data Hierarchy
```
P&IDs (Process Source)
    └── Line List (Master Register)
            ├── Line Designation Table (Detailed Attributes)
            ├── Valve List (Component Extraction)
            ├── Piping Isometrics (Fabrication Details)
            └── 3D Model (Spatial Representation)
```

## 3. Considerations

### 3.1 Project-Specific Considerations

| Consideration | Details |
|---------------|---------|
| **Booster Pump Piping** | 5 new VS6-type pumps with dedicated discharge flow meters |
| **Manifold Configuration** | 5x6 manifold requires systematic line numbering |
| **Blending Service** | Heavy/Light crude blending (20%/80% per SOW) |
| **Flow Capacity** | Design for 315,000 bpd peak flow rate |
| **Existing Systems** | Coordinate with existing Sumas Tank Farm piping |

### 3.2 Technical Considerations

| Topic | Guidance |
|-------|----------|
| **Line Numbering** | Coordinate with TM to confirm naming convention before starting (**TBD**) |
| **Stress Critical Lines** | Flag lines requiring stress analysis (high temp, large bore, equipment connections) |
| **Insulation** | Identify all heat-traced and insulated lines for material takeoff |
| **Test Boundaries** | Consider hydrotest package boundaries when assigning line numbers |

### 3.3 Coordination Requirements
- Coordinate with Process Engineering for design conditions
- Coordinate with Instrumentation for in-line instruments
- Coordinate with Mechanical for equipment nozzle data
- Align with 3D model line numbering

## 4. Trade-offs

### 4.1 Line Numbering Approaches

| Approach | Pros | Cons |
|----------|------|------|
| **Area-Based Numbering** | Easy to locate physically | May not align with process flow |
| **System-Based Numbering** | Follows process logic | Harder to locate in field |
| **Sequential Numbering** | Simple administration | No inherent meaning |

**ASSUMPTION**: Project will follow TM existing line numbering convention.

### 4.2 Data Management Trade-offs

| Trade-off | Recommendation |
|-----------|----------------|
| **Manual vs. Auto-extraction** | Use 3D model auto-extraction with manual verification |
| **Single file vs. Multiple** | Single consolidated file with area filters |
| **Early freeze vs. Late updates** | Progressive freeze by area/system |

## 5. Examples

### 5.1 Sample Line Number Format (**ASSUMPTION** - confirm with TM)
```
XX-YYY-ZZZZ-NNN-SSSS

Where:
XX    = Area code (e.g., SF = Sumas Farm)
YYY   = Commodity code (e.g., OIL, DRN)
ZZZZ  = Line size (e.g., 0600 = 6")
NNN   = Sequence number
SSSS  = Piping class (e.g., A1A1)
```

### 5.2 Sample Line List Entry

| Line No | Size | Class | Service | From | To | Des P | Des T | Op P | Op T |
|---------|------|-------|---------|------|----|----|----|----|-----|
| SF-OIL-0800-001-A1A1 | 8" | A1A1 | Crude Oil | P-101 Disch | MF-001 | 1480 kPa | 50C | 1200 kPa | 35C |

### 5.3 Common Issues to Avoid
1. Duplicate line numbers across areas
2. Mismatched P&ID references
3. Missing design conditions for new lines
4. Inconsistent service descriptions
5. Omitting tie-in lines to existing systems

### 5.4 SOW Traceability
This deliverable supports the following SOW requirements:
- **SOW-0117**: Produce FEED line list (LST) - per SOW Section 3.1.3.1 (p7)
- **SOW-0250**: Develop Process Piping Line Designation Table (LDT) with required line attributes (line number/size/class/P&ID/from-to/conditions/NDE/testing/etc) - per SOW Section 3.2.4.11 (p19)

---
*Generated 2026-02-01 | SOW Refs: SOW-0117, SOW-0250*
