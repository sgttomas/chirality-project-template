# Guidance: DEL-02.28 Sitewide 3D Model (As-Built + Design Integrated)

## Purpose

### Intent
The Sitewide 3D Model serves as the single source of geometric truth for the PSO project, integrating existing as-built conditions with new detailed design. This guidance ensures consistent model development, effective multi-discipline coordination, and successful deliverable extraction.

### Context
The 3D model is central to modern engineering practice, enabling clash detection, design visualization, and automated drawing extraction. For the PSO brownfield expansion at Sumas Tank Farm, accurate integration of existing conditions is critical to avoid field conflicts.

### Stakeholders
| Stakeholder | Interest |
|-------------|----------|
| 3D Model Coordinator | Overall model management, coordination, clash detection |
| Piping Engineers/Designers | Piping routing, isometric extraction, support coordination |
| Structural Engineers | Foundation and support modeling, structural clash resolution |
| Electrical Engineers | Cable tray routing, equipment placement |
| I&C Engineers | Instrument locations, cable routing |
| Construction | Constructability input, CWP/FIWP support |
| TM Operations | Maintainability review, as-built accuracy |
| Client (TM) | Standards compliance, model turnover, integration |

## Principles

### Core Principles
| Principle | Description |
|-----------|-------------|
| **Single Source of Truth** | The 3D model is the master geometric representation for all disciplines |
| **As-Built Accuracy** | Existing conditions accurately represented from TM model and laser scan |
| **Design Intent** | New design accurately modeled to enable construction without conflicts |
| **Multi-discipline Coordination** | All disciplines coordinated through single federated model |
| **Extractability** | All 2D deliverables (drawings, isometrics) extractable from model |
| **Constructability** | Model supports construction planning and work package development |

### Model Development Phases
```
Phase 1: As-Built Integration
    +-- Import/verify TM existing site model
    +-- Integrate laser scan data (if available)
    +-- Verify tie-in point locations against field data
    +-- Establish coordinate system alignment

Phase 2: FEED Model Development
    +-- Preliminary equipment placement
    +-- Preliminary piping routing
    +-- Spatial allocation confirmation
    +-- FEED model review and approval

Phase 3: Detailed Design Model
    +-- Vendor equipment model integration
    +-- Detailed piping routing with supports
    +-- Complete structural modeling
    +-- Electrical and I&C modeling
    +-- Weekly clash detection and resolution
    +-- Multi-discipline reviews (30/60/90%)

Phase 4: IFC and As-Built
    +-- Final model verification (zero hard clashes)
    +-- IFC deliverable extraction
    +-- As-built updates during construction
    +-- Final as-built model turnover
```

## Considerations

### Project-Specific Considerations
| Consideration | Details |
|---------------|---------|
| **Brownfield Environment** | SW corner of TK-102; integrate with existing tank farm without disruption |
| **Booster Pump Configuration** | 5 pumps (2 large, 2 small, 1 medium per SOW) with VFDs; careful nozzle orientation |
| **Manifold Complexity** | 5x6 manifold requires careful routing, valve access, and support design |
| **Tie-In Points** | Multiple tie-ins to existing systems; field verification critical |
| **Access Requirements** | Maintenance access per TM operational requirements |
| **Underground Conflicts** | Existing underground utilities must be verified and avoided |

### Technical Considerations
| Topic | Guidance |
|-------|----------|
| **Laser Scan Integration** | Use point cloud for existing condition verification where available |
| **Equipment Models** | Obtain vendor 3D models early; simplify complex models if needed for performance |
| **Pipe Routing** | Model all pipes 2" NPS and above; model smaller in congested areas |
| **Insulation Thickness** | Include insulation envelopes for accurate clash detection |
| **Valve Operators** | Model handwheel swing arcs (90 degrees minimum) and actuator envelopes |
| **Pipe Supports** | Coordinate with stress analysis for support locations and types |
| **Nozzle Loads** | Model equipment nozzle orientations accurately for stress analysis interface |

### Coordination Requirements
| Requirement | Frequency |
|-------------|-----------|
| Model Integration | Daily during peak design periods |
| Clash Detection | Weekly during detailed design |
| Multi-discipline Reviews | At 30/60/90% milestones |
| Constructability Reviews | At 60% and 90% milestones |
| Operator/Maintainability Reviews | At 90% milestone |

## Trade-offs

### Level of Detail Trade-offs
| LOD | Content | Application |
|-----|---------|-------------|
| LOD 200 | Approximate geometry, generic elements | FEED phase; distant context areas |
| LOD 300 | Accurate geometry, specific elements | 30-60% DD |
| LOD 350 | Construction document level | 90% DD; pipe supports, instrumentation |
| LOD 400 | Fabrication detail | IFC; piping spool details |

### Model Performance Trade-offs
| Trade-off | Recommendation |
|-----------|----------------|
| Full detail vs. Performance | Use simplified representations for distant/context areas to maintain performance |
| Single vs. Split model | Split by area if file size exceeds performance threshold |
| Insulation modeling | Model as cylinders/parametric; avoid complex geometry |
| Small bore piping | Model 2" and above standard; smaller by exception in congested areas |
| Vendor models | Simplify complex vendor models to essential geometry |

### Clash Detection Trade-offs
| Tolerance | Application |
|-----------|-------------|
| 0mm (Hard clash) | Physical intersection; must resolve before IFC |
| 25mm (Soft clash) | Insulation, access clearance; resolve or document |
| 50mm (Clearance) | Maintenance access; review and document |
| 150mm+ (Workflow) | Construction sequence conflicts; review at milestone |

## Examples

### Model Content by Area
| Area | Key Content |
|------|-------------|
| **Booster Pump Station** | 5 VS6 pumps, VFDs, suction/discharge headers, foundations, electrical building, pipe supports |
| **Manifold Area** | 5x6 manifold headers, gate/check valves, instruments, pipe supports, valve access platforms |
| **Containment Wall** | Concrete wall, sumps, drain piping, grade beams |
| **Interconnecting Piping** | Piping between areas, pipe rack, underground utilities, cathodic protection |
| **Existing Facilities** | TM-provided existing model (reference only, not modified) |

### Clash Category Resolution
| Category | Example | Priority | Resolution |
|----------|---------|----------|------------|
| **Hard Clash** | Pipe through steel member | Immediate | Route change or structural revision |
| **Soft Clash** | Insulation overlap | Before IFC | Adjust routing or insulation thickness |
| **Clearance Clash** | Valve handwheel access < 450mm | Before IFC | Relocate valve or add platform |
| **Workflow Clash** | Crane swing conflict | Design review | Sequence adjustment |

### Common Issues to Avoid
1. Ignoring existing conditions from as-built data leading to field conflicts
2. Late vendor model integration causing significant rework
3. Inadequate clash detection frequency missing developing conflicts
4. Missing insulation in clash detection leading to field interference
5. Not modeling valve operator/handwheel envelopes leading to access issues
6. Inconsistent coordinate systems between model portions
7. Missing underground utilities causing field surprises
8. Insufficient LOD for pipe supports and instrumentation
9. Model too large for effective review sessions
10. No as-built update process leading to inaccurate final model

---
*Generated by 4_DOCUMENTS Agent - 2026-02-01*
