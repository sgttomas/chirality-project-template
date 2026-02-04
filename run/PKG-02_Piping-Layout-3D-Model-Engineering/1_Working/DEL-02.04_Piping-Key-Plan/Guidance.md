# Guidance: Piping Key Plan

## 1. Purpose

### 1.1 Document Intent
This guidance document provides direction on developing the Piping Key Plan for the Puget Sound Optimization Project, addressing practical considerations, industry best practices, and project-specific requirements.

### 1.2 Target Audience
- Piping Engineers
- Piping Designers
- CAD Technicians
- Document Controllers

## 2. Principles

### 2.1 Core Principles
| Principle | Description |
|-----------|-------------|
| **Navigation Aid** | The Key Plan serves as the primary navigation tool for all piping drawings |
| **Consistency** | Grid system must be consistent across all disciplines |
| **Clarity** | Layout must be clear and uncluttered for quick reference |
| **Maintainability** | Structure to support updates as drawings are added/modified |

### 2.2 Drawing Hierarchy
```
Key Plan (Site Overview + Index)
    └── Site Plan (Piping Overview)
            └── Area Plans (Zone Details)
                    └── GA Drawings (Equipment/Piping Details)
                            └── Isometrics (Fabrication Details)
```

## 3. Considerations

### 3.1 Project-Specific Considerations

| Consideration | Details |
|---------------|---------|
| **Site Location** | Sumas Tank Farm, southwest corner of TK-102 |
| **New Facilities** | 5 booster pumps, 5x6 manifold, containment wall |
| **Existing Facilities** | Integrate with existing tank farm layout |
| **Drawing Set Size** | Estimate drawing count to define grid/coverage |

### 3.2 Technical Considerations

| Topic | Guidance |
|-------|----------|
| **Grid System** | Coordinate with Civil/Structural for consistent grid (**TBD**) |
| **Match-Lines** | Plan overlap areas to ensure continuity between sheets |
| **Scale Selection** | Select scale that shows entire site on single sheet if possible |
| **Layer Structure** | Use consistent layer naming per TM standards (**TBD**) |

### 3.3 Coordination Requirements
- Coordinate with Civil for site survey and property boundaries
- Coordinate with other disciplines for consistent grid/area designations
- Align with existing TM site drawings where available
- Verify against 3D model coverage

## 4. Trade-offs

### 4.1 Scale Selection

| Scale | Pros | Cons |
|-------|------|------|
| **1:500** | Good detail visibility | May require multiple sheets |
| **1:1000** | Covers more area | Less detail visible |
| **NTS** | Flexible layout | Difficult to scale dimensions |

**Recommendation**: Use appropriate scale to fit entire PSO area on single sheet; detail in Site Plan and Area Plans.

### 4.2 Drawing Organization

| Approach | Pros | Cons |
|----------|------|------|
| **Single Key Plan** | Simple reference | May be crowded for large sites |
| **Multiple Key Plans** | Better detail per area | Requires additional coordination |

## 5. Examples

### 5.1 Sample Grid System (**ASSUMPTION** - confirm with TM)
```
Grid Naming Convention:
- North-South: Letters (A, B, C, ...)
- East-West: Numbers (1, 2, 3, ...)
- Grid squares: 50m x 50m (ASSUMPTION)

Example: Area A3 covers grid intersection A-3
```

### 5.2 Sample Drawing Index Table

| Drawing No | Title | Area Coverage | Scale |
|------------|-------|---------------|-------|
| PIP-001-01 | Site Plan - Overall | Full Site | 1:500 |
| PIP-001-02 | Site Plan - Booster Pump Area | A3-B4 | 1:200 |
| PIP-002-01 | GA - Booster Pump P-101 | A3 | 1:50 |

### 5.3 Common Issues to Avoid
1. Inconsistent grid references between disciplines
2. Match-line gaps or overlaps causing confusion
3. Outdated drawing index as design evolves
4. Missing areas from grid coverage
5. Incorrect north orientation

### 5.4 SOW Traceability
This deliverable supports the following SOW requirements:
- **SOW-0122**: Produce FEED piping key plan (GA) - per SOW Section 3.1.3.1 (p7-8)
- **SOW-0247**: Update/finalize site-specific drawings (area/key/equipment layout/module location/plot plan/GA drawings) - per SOW Section 3.2.4.8 (p19)

---
*Generated 2026-02-01 | SOW Refs: SOW-0122, SOW-0247*
