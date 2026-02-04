# Guidance: Construction Work Packages (CWP) - Piping

## 1. Purpose

### 1.1 Document Intent
This guidance document provides direction on developing Construction Work Packages (CWPs) for piping scope on the Puget Sound Optimization Project, addressing practical considerations, AWP methodology, and project-specific requirements.

### 1.2 Target Audience
- Piping Engineers
- Construction Planners
- Work Package Coordinators
- Project Controls
- Construction Supervisors

## 2. Principles

### 2.1 Core Principles
| Principle | Description |
|-----------|-------------|
| **Path of Construction** | CWPs follow logical construction sequence |
| **Right-Sized Scope** | CWP scope manageable for planning and execution |
| **Clear Boundaries** | Unambiguous geographic and system limits |
| **Complete Information** | All engineering deliverables included |
| **Constraint Identification** | Known constraints documented early |

### 2.2 AWP Hierarchy (**ASSUMPTION** - based on industry AWP methodology)
```
Construction Execution Plan
    └── Construction Work Packages (CWPs)
            └── Field Installation Work Packages (FIWPs)
                    └── Work Tasks/Activities
```

### 2.3 CWP Development Flow
```
Engineering IFC → CWP Definition → Material Planning → FIWP Development → Field Execution
```

## 3. Considerations

### 3.1 Project-Specific Considerations

| Consideration | Details |
|---------------|---------|
| **Pump-by-Pump Approach** | Consider organizing CWPs by individual pump installation |
| **Manifold Complexity** | 5x6 manifold may warrant dedicated CWP |
| **Brownfield Constraints** | Tie-in work may require separate CWPs due to shutdown requirements |
| **Prefabrication** | Align with module/prefab list (DEL-02.23) |
| **Construction Sequence** | Coordinate with civil/structural prerequisites |

### 3.2 Technical Considerations

| Topic | Guidance |
|-------|----------|
| **Boundary Definition** | Use physical breaks (flanges, valves) as boundaries where practical |
| **Material Alignment** | CWP scope should align with material delivery packages |
| **Weld Optimization** | Consider shop vs. field weld distribution |
| **Access Requirements** | Document access constraints for tie-in and confined work |
| **Hydrotest Alignment** | Consider hydrotest package boundaries (DEL-02.21) |

### 3.3 Coordination Requirements
- Coordinate with Civil/Structural for foundation/support prerequisites
- Coordinate with Mechanical for equipment installation sequence
- Coordinate with Electrical/Instrumentation for tie-in timing
- Align with project schedule and construction logic

## 4. Trade-offs

### 4.1 CWP Sizing

| Approach | Pros | Cons |
|----------|------|------|
| **Small CWPs** | Flexible scheduling, early release | More packages to manage |
| **Large CWPs** | Fewer packages, complete systems | Less flexibility, later release |
| **Equipment-Based** | Clear scope, matches commissioning | May not optimize construction sequence |
| **Area-Based** | Optimizes crew movement | May split systems |

**ASSUMPTION**: Balance between equipment-based and area-based approaches for this project.

### 4.2 Timing Considerations

| Trade-off | Recommendation |
|-----------|----------------|
| **Early Release vs. Complete** | Release progressive CWPs as IFC drawings are available |
| **Prefab vs. Field Install** | Maximize prefabrication per module/prefab list |
| **Parallel vs. Sequential** | Identify independent CWPs for parallel execution |

## 5. Examples

### 5.1 Sample CWP Cover Sheet Content

| Field | Example Value |
|-------|---------------|
| CWP ID | CWP-PIP-001 |
| CWP Title | Pump P-101 Suction and Discharge Piping |
| System | Crude Oil Booster System |
| Area | Southwest of TK-102 |
| Boundaries | From manifold header tie-in to pump nozzles |
| Drawing Count | 8 isometrics, 2 GAs |
| Weld Count | 45 field welds |
| Estimated Manhours | **TBD** |
| Constraints | Pump installation complete, foundation ready |
| Successor CWP | CWP-PIP-006 (Manifold) |

### 5.2 Sample CWP Breakdown for PSO Project (**ASSUMPTION**)

| CWP ID | Scope | Dependencies |
|--------|-------|--------------|
| CWP-PIP-001 | P-101 piping | Foundation, pump set |
| CWP-PIP-002 | P-102 piping | Foundation, pump set |
| CWP-PIP-003 | P-103 piping | Foundation, pump set |
| CWP-PIP-004 | P-104 piping | Foundation, pump set |
| CWP-PIP-005 | P-105 piping | Foundation, pump set |
| CWP-PIP-006 | Manifold piping | All pump CWPs |
| CWP-PIP-007 | Tie-in to existing | System isolation |
| CWP-PIP-008 | Sump/drain piping | Containment complete |

### 5.3 Common Issues to Avoid
1. Undefined or overlapping boundaries between CWPs
2. Missing constraints that affect FIWP development
3. Incomplete drawing/isometric lists
4. Material requirements not aligned with delivery schedule
5. Insufficient coordination with other disciplines
6. Late release causing construction delays

---
*Pass 1 Draft - Generated 2026-02-01*
