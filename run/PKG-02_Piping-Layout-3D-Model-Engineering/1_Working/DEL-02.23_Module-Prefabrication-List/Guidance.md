# Guidance: Module & Prefabrication List

## 1. Purpose

### 1.1 Document Intent
This guidance document provides direction on developing the Module & Prefabrication List for the Puget Sound Optimization Project, addressing practical considerations, industry best practices, and project-specific requirements.

### 1.2 Target Audience
- Piping Engineers
- Construction Managers
- Procurement Coordinators
- Logistics Planners
- Fabrication Supervisors

## 2. Principles

### 2.1 Core Principles

| Principle | Description |
|-----------|-------------|
| **Maximize Prefabrication** | Maximize shop work to reduce field labor and improve quality |
| **Transport Feasibility** | Design modules within practical transport limits |
| **Schedule Integration** | Align delivery with construction sequence |
| **Traceability** | Maintain clear linkage to engineering deliverables |

### 2.2 Prefabrication Hierarchy
```
Modularization Strategy
    ├── Large Modules (transport-limited)
    │       └── Equipment skids, pipe racks
    ├── Medium Assemblies (truck-transportable)
    │       └── Pipe supports, junction boxes
    └── Pipe Spools (standard shipping)
            └── Shop-fabricated spool pieces
```

## 3. Considerations

### 3.1 Project-Specific Considerations

| Consideration | Details |
|---------------|---------|
| **Booster Pump Skids** | Consider pre-assembled pump skids if feasible |
| **Manifold Assembly** | 5x6 manifold may be modularized |
| **Site Access** | Sumas Tank Farm road and gate constraints (**TBD**) |
| **Crane Capacity** | Available lifting capacity on site (**TBD**) |
| **Laydown Space** | Module storage area limitations (**TBD**) |

### 3.2 Technical Considerations

| Topic | Guidance |
|-------|----------|
| **Transport Limits** | Standard truck: ~3.6m W x 4.1m H x 12m L (**ASSUMPTION**) |
| **Weight Limits** | Standard truck: ~20 tonnes; overweight permit required above |
| **Shop vs Field** | Prefer shop fabrication for quality and safety |
| **Weld Locations** | Minimize field welds, locate at accessible positions |
| **Testing** | Consider shop hydrotesting of spool assemblies |

### 3.3 Coordination Requirements
- Coordinate with Construction for site constraints
- Coordinate with Procurement for fabricator capabilities
- Coordinate with Logistics for transport planning
- Coordinate with Scheduling for delivery sequence

## 4. Trade-offs

### 4.1 Module Size Trade-offs

| Size | Pros | Cons |
|------|------|------|
| **Large Modules** | Fewer field connections, faster install | Transport permits, heavy lift |
| **Medium Modules** | Standard transport, reasonable lifts | More field connections |
| **Small Spools** | Easy transport, simple handling | Maximum field work |

**ASSUMPTION**: Project will optimize for medium modules with standard transport where possible.

### 4.2 Fabrication Location Trade-offs

| Location | Pros | Cons |
|----------|------|------|
| **Shop** | Best quality, controlled environment | Transport costs |
| **Fab Yard** | Some control, large assemblies possible | Weather exposure |
| **Field** | No transport issues | Productivity, quality challenges |

## 5. Examples

### 5.1 Sample Module ID Format (**ASSUMPTION** - confirm with project)
```
MOD-XXX-NNN

Where:
MOD  = Module prefix
XXX  = Type code (PIP=Pipe, SKD=Skid, SPL=Spool, SUP=Support)
NNN  = Sequential number
```

### 5.2 Sample List Entry

| ID | Description | Type | L(m) | W(m) | H(m) | Weight(kg) | Fab Loc | Priority | ROS |
|----|-------------|------|------|------|------|------------|---------|----------|-----|
| MOD-PIP-001 | P-101 Discharge Pipe Module | Pipe Module | 8.0 | 2.5 | 3.0 | 4,500 | Shop | 1 | TBD |
| MOD-SPL-001 | MF-001 Header Spool A | Spool | 3.0 | 0.8 | 0.8 | 850 | Shop | 2 | TBD |

### 5.3 Transport Envelope Guidelines (**ASSUMPTION** - verify per jurisdiction)

| Category | Width | Height | Length | Weight |
|----------|-------|--------|--------|--------|
| Standard | 2.6 m | 4.1 m | 12 m | 20 t |
| Permit (typical) | 3.6 m | 4.4 m | 18 m | 45 t |
| Superload | > 3.6 m | > 4.4 m | > 18 m | > 45 t |

### 5.4 Common Issues to Avoid
1. Designing modules that exceed transport limits without permit strategy
2. Underestimating weights (add contingency)
3. Forgetting to include lifting lugs and rigging points
4. Not coordinating delivery sequence with construction schedule
5. Omitting temporary supports for transport

---
*Pass 1 Draft - Generated 2026-02-01*
