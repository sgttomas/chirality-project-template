# Guidance: Piping Material Class (PMC) Index

## 1. Purpose

### 1.1 Document Intent
This guidance document provides direction on developing and maintaining the PMC Index for the Puget Sound Optimization Project, addressing practical considerations, industry best practices, and project-specific requirements.

### 1.2 Target Audience
- Piping Materials Engineers
- Piping Engineers
- Piping Designers
- Document Control Personnel
- Procurement Coordinators

## 2. Principles

### 2.1 Core Principles

| Principle | Description |
|-----------|-------------|
| **Single Source of Truth** | Index is the authoritative reference for PMC status |
| **Complete Coverage** | All project PMCs tracked in one location |
| **Current Status** | Index always reflects latest approved revisions |
| **Traceability** | Full change history maintained for audit trail |

### 2.2 PMC Hierarchy
```
PMC Index (Master List)
    ├── PMC Code (e.g., A1A1)
    │       ├── Summary Data (in index)
    │       └── Detailed PMC Sheet (separate document)
    │               ├── Pipe specifications
    │               ├── Fitting specifications
    │               ├── Flange specifications
    │               ├── Valve specifications
    │               ├── Gasket specifications
    │               └── Bolt specifications
    └── Change History
            └── Revision log per PMC
```

## 3. Considerations

### 3.1 Project-Specific Considerations

| Consideration | Details |
|---------------|---------|
| **TM Base PMCs** | Leverage existing TM material classes where suitable |
| **Crude Oil Service** | Heavy/Light blend (20%/80% per SOW) |
| **Utility Services** | Water, air, nitrogen for auxiliary systems |
| **Code Basis** | CSA Z662 for pipeline, ASME B31.3 for process piping (**ASSUMPTION**) |
| **Existing Infrastructure** | Compatibility with existing TM piping systems |

### 3.2 Technical Considerations

| Topic | Guidance |
|-------|----------|
| **PMC Naming Convention** | Follow TM standard convention (**TBD**) |
| **Rating Basis** | Use ASME B16.5 flange class as primary rating identifier |
| **Material Groups** | Organize by base material (CS, SS, alloy) |
| **Service Categories** | Group by fluid service for easy reference |
| **Temperature Range** | Document both max and min design temperatures |

### 3.3 Coordination Requirements
- Coordinate with Piping for PMC selection per line
- Coordinate with Materials Engineer for PMC verification status
- Coordinate with Procurement for PMC availability
- Coordinate with Document Control for revision tracking

## 4. Trade-offs

### 4.1 Index Detail Level

| Approach | Pros | Cons |
|----------|------|------|
| **Summary Only** | Easy to read, quick reference | Users must access PMC sheets for detail |
| **Comprehensive** | All data in one place | Large document, harder to maintain |
| **Hybrid** | Balance of summary and key details | Requires clear scope definition |

**ASSUMPTION**: Project will use hybrid approach with key parameters in index, detail in PMC sheets.

### 4.2 PMC Consolidation

| Approach | Pros | Cons |
|----------|------|------|
| **Many Specific PMCs** | Optimized for each service | More classes to manage |
| **Fewer General PMCs** | Simpler to manage | May over-specify some applications |
| **Service-Based Groups** | Logical organization | May not fit all cases |

**ASSUMPTION**: Minimize number of PMCs while meeting all service requirements.

## 5. Examples

### 5.1 Sample PMC Code Format (**ASSUMPTION** - confirm with TM)
```
XNYZ

Where:
X  = Material group (A=Carbon Steel, B=Low Alloy, C=Stainless Steel)
N  = Pressure class (1=150#, 2=300#, 3=600#, etc.)
Y  = Service code (A=Hydrocarbon, B=Utility, C=Drain, etc.)
Z  = Variant number (1, 2, 3, etc.)

Example: A1A1 = Carbon Steel, 150#, Hydrocarbon Service, Variant 1
```

### 5.2 Sample Index Entry

| PMC | Description | Service | Material | Class | Max P | Max T | MDMT | CA | Code | Rev | Sheet No |
|-----|-------------|---------|----------|-------|-------|-------|------|----|----|-----|----------|
| A1A1 | CS 150# Crude Oil | Crude Oil | CS | 150 | 1480 kPa | 100C | -29C | 3mm | B31.3 | 2 | PMC-A1A1-R2 |
| A2A1 | CS 300# Crude Oil | Crude Oil | CS | 300 | 2960 kPa | 100C | -29C | 3mm | B31.3 | 1 | PMC-A2A1-R1 |
| A1B1 | CS 150# Service Water | Utility Water | CS | 150 | 1035 kPa | 50C | -10C | 1.5mm | B31.3 | 1 | PMC-A1B1-R1 |

### 5.3 Sample Change History Entry

| PMC | Rev | Date | Change Description | Changed By | Approved By |
|-----|-----|------|-------------------|------------|-------------|
| A1A1 | 1 | 2025-01-15 | Initial issue | J. Smith | A. Jones |
| A1A1 | 2 | 2026-01-20 | Updated flange rating per B16.5-2020 | J. Smith | A. Jones |

### 5.4 Common Issues to Avoid
1. Not updating index when PMC sheets are revised
2. Inconsistent PMC naming conventions
3. Missing change history entries
4. Incorrect cross-references to PMC sheets
5. Outdated code references in index
6. Not tracking superseded PMC revisions

---
*Generated: 2026-02-01 | Status: INITIALIZED*
