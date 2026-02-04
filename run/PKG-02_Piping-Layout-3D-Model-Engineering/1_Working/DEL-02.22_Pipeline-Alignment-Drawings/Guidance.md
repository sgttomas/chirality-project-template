# Guidance: Pipeline Alignment Drawings

## 1. Purpose

### 1.1 Document Intent
This guidance document provides direction on developing pipeline alignment drawings for the Puget Sound Optimization Project, addressing practical considerations, industry best practices, and project-specific requirements.

### 1.2 Target Audience
- Pipeline Engineers
- Piping Designers
- Civil Engineers
- Survey Coordinators
- Construction Supervisors

## 2. Principles

### 2.1 Core Principles

| Principle | Description |
|-----------|-------------|
| **Survey Accuracy** | Alignment must be based on verified survey data |
| **Code Compliance** | All crossings and depths must meet regulatory requirements |
| **Constructability** | Alignment must be feasible for construction equipment |
| **Environmental Protection** | Minimize environmental impact per permits |

### 2.2 Drawing Set Organization
```
Pipeline Alignment Package
    ├── Key Plan / Index
    ├── Plan & Profile Sheets (continuous stationing)
    ├── Typical Cross-Sections
    ├── Crossing Detail Sheets
    │       ├── Road Crossings
    │       ├── Utility Crossings
    │       └── Watercourse Crossings
    └── Tie-In Details
```

## 3. Considerations

### 3.1 Project-Specific Considerations

| Consideration | Details |
|---------------|---------|
| **Booster Pump Station** | New pipeline from BPS to 5x6 manifold (**ASSUMPTION**) |
| **Existing Infrastructure** | Coordinate with existing TM facilities |
| **Property Boundaries** | Stay within approved right-of-way |
| **Environmental Constraints** | Avoid sensitive areas per environmental permits |
| **Construction Access** | Ensure adequate access for construction equipment |

### 3.2 Technical Considerations

| Topic | Guidance |
|-------|----------|
| **Minimum Cover** | Per CSA Z662 and local requirements (typically 0.9m-1.2m) |
| **Crossing Clearances** | Coordinate with utility owners for crossing agreements |
| **Horizontal Curves** | Minimum bend radius per pipe diameter and material |
| **Vertical Curves** | Overbend and sagbend limits per code |
| **Cathodic Protection** | Coordinate with CP design for test stations and anodes |

### 3.3 Coordination Requirements
- Coordinate with Survey for control points and topographic data
- Coordinate with Civil for grading and drainage
- Coordinate with Environmental for permit constraints
- Coordinate with Operations for tie-in locations
- Coordinate with third-party utility owners for crossings

## 4. Trade-offs

### 4.1 Route Selection Factors

| Factor | Consideration |
|--------|---------------|
| **Shortest Route** | Minimum material, maximum constructability issues |
| **Following Roads** | Good access, more crossings, land agreements |
| **Avoiding Crossings** | Fewer permits, potentially longer route |
| **Existing ROW** | Use existing rights, may have space constraints |

**ASSUMPTION**: Route follows existing TM right-of-way where possible.

### 4.2 Crossing Methods

| Method | Pros | Cons | Typical Use |
|--------|------|------|-------------|
| **Open Cut** | Simple, economical | Traffic disruption | Minor roads |
| **Bore** | No surface disruption | Higher cost | Major roads, rails |
| **HDD** | Long crossings, deep cover | Highest cost | Rivers, major highways |
| **Direct Pipe** | Accurate, no settlement | Specialized equipment | Critical crossings |

## 5. Examples

### 5.1 Sample Stationing Format
```
Station 0+000 = Start point (tie-in to existing)
Station 0+100 = Road crossing center
Station 0+250 = PI (Point of Intersection - horizontal curve)
Station 0+500 = Utility crossing
Station 0+750 = End point (manifold connection)
```

### 5.2 Sample Pipeline Data Block

| Parameter | Value |
|-----------|-------|
| Pipeline | XX"-OIL-001 (**TBD**) |
| Service | Crude Oil |
| Design Pressure | **TBD** kPa |
| Design Temperature | **TBD** C |
| Material | **TBD** (API 5L Grade) |
| Coating | **TBD** (FBE typical) |

### 5.3 Minimum Cover Requirements (**ASSUMPTION** - verify per CSA Z662)

| Location | Minimum Cover |
|----------|---------------|
| Normal soil | 0.9 m |
| Rock | 0.6 m |
| Road crossings | 1.2 m |
| Railroad crossings | 1.5 m |
| Watercourses | 1.2 m below scour depth |

### 5.4 Common Issues to Avoid
1. Mismatched stationing between plan and profile
2. Insufficient crossing clearances
3. Exceeding pipe bend radius limits
4. Inadequate cover in high water table areas
5. Omitting utility crossing agreements
6. Ignoring construction access requirements

---
*Pass 1 Draft - Generated 2026-02-01*
