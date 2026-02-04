# Specification: DEL-02.28 Sitewide 3D Model (As-Built + Design Integrated)

## Scope

### Purpose
The Sitewide 3D Model provides an integrated, coordinated geometric representation of existing as-built conditions and new PSO design at Sumas Tank Farm. The model serves as the single source of geometric truth for the project, enabling clash detection, design coordination, and extraction of 2D deliverables.

### Boundaries
- **Included:**
  - All new PSO facilities at Sumas Tank Farm
  - Existing facilities within tie-in and interface zones
  - Multi-discipline content (Piping, Structural, Mechanical, Electrical, I&C)
  - Equipment, piping, structures, and infrastructure
  - Underground utilities within project scope
  - Vendor equipment models (integrated)
- **Excluded:**
  - TM internal model maintenance (post-project turnover)
  - Areas outside PSO project footprint (unless required for context)
  - Temporary construction facilities (unless specifically specified)
  - Process simulation models (separate from geometric model)

### Deliverables
- Native 3D model files (per selected platform)
- Model extracts in exchange formats (IFC, DWG as required)
- Clash reports (PDF/Excel)
- Extracted 2D drawings (isometrics, GAs, plot plans - via other DELs)
- Model review presentations and walkthroughs

## Requirements

### Content Requirements
| ID | Requirement |
|----|-------------|
| REQ-01 | As-built representation of existing site conditions from TM model and/or laser scan |
| REQ-02 | All new booster pump station facilities (5 pumps, VFDs, electrical building, foundations) |
| REQ-03 | 5x6 manifold system with all headers, valves, instruments, and connections |
| REQ-04 | New containment wall per civil design |
| REQ-05 | All new and modified piping systems including underground |
| REQ-06 | Structural elements (foundations, pipe supports, pipe racks, buildings, platforms) |
| REQ-07 | Major electrical equipment and cable routing (trays, conduits) |
| REQ-08 | Instrumentation locations and cable routing |
| REQ-09 | Equipment with accurate dimensions and nozzle orientations |
| REQ-10 | Underground utilities within project scope |
| REQ-11 | Access and maintenance clearances verified |
| REQ-12 | Vendor equipment models integrated |
| REQ-13 | Insulation envelopes for clash detection |
| REQ-14 | Valve operator/handwheel envelopes |

### Accuracy Requirements
| ID | Requirement |
|----|-------------|
| ACC-01 | Piping: All elements modeled to correct size, class, and routing per isometrics |
| ACC-02 | Equipment: Accurate dimensions with correct nozzle locations per vendor data |
| ACC-03 | Structures: Accurate member sizes and connection locations |
| ACC-04 | Existing: Based on TM model, laser scan, and/or verified drawings |
| ACC-05 | Coordinate system aligned with TM site grid |

### Coordination Requirements
| ID | Requirement |
|----|-------------|
| COORD-01 | Clash-free design across all disciplines at IFC |
| COORD-02 | Clear access/egress paths maintained per safety requirements |
| COORD-03 | Maintenance access requirements accommodated |
| COORD-04 | Constructability considerations addressed |
| COORD-05 | Operator accessibility for valves and instruments verified |

### Performance Requirements
| ID | Requirement |
|----|-------------|
| PERF-01 | Model file size manageable for design review sessions |
| PERF-02 | Clash detection completes within reasonable timeframe |
| PERF-03 | Drawing extraction automated where supported by platform |

## Standards

### Applicable Standards
| Standard | Description |
|----------|-------------|
| TM-STD-3D-001 | TM 3D CAD Standard (**TBD** - reference to be confirmed) |
| DEL-02.27 | 3D Model Implementation Plan (project-specific procedures) |
| ISO 15926 | Industrial automation systems and integration (**ASSUMPTION**) |
| ISO 19650 | BIM information management (**ASSUMPTION**) |
| Project CAD Standard | Project-specific requirements (**TBD**) |

### Platform Standards
| Standard | Description |
|----------|-------------|
| Platform-specific | Per selected 3D modeling platform (AVEVA, Bentley, or other) (**TBD**) |
| Exchange Formats | IFC 4.0 or later for model exchange (**ASSUMPTION**) |

## Verification

### Review Requirements
| Review Type | Description |
|-------------|-------------|
| Discipline Reviews | Individual discipline model review at milestones |
| Multi-discipline Reviews | Integrated model review at 30/60/90% and IFC |
| Constructability Review | Review with Construction at key milestones |
| Operator Review | TM Operations review for maintainability |
| Client Review | TM formal review at milestones |

### Verification Methods
| Method | Description |
|--------|-------------|
| Clash Detection | Automated clash detection per schedule defined in DEL-02.27 |
| Model Review | Visual review sessions (discipline and multi-discipline) |
| Dimensional Spot Check | Sample dimensional verification against source documents |
| Virtual Walkthrough | Model walkthrough for access and operability |
| Extraction Verification | Verify extracted drawings match model content |

### Acceptance Criteria
| Criterion | Requirement |
|-----------|-------------|
| Zero Hard Clashes | No hard clashes remaining at IFC |
| Soft Clash Resolution | All soft clashes resolved or documented with justification |
| Design Accuracy | Model accurately represents design intent per drawings |
| Extractability | Drawings and reports extractable correctly from model |
| Coordinate Alignment | Coordinate system aligned with TM existing model |
| Client Approval | TM review and approval at milestones |

## Documentation

### Submittal Requirements
| Requirement | Description |
|-------------|-------------|
| Native Format | Native model files per selected platform |
| Exchange Format | IFC, DWG, PDF extracts as required |
| Clash Reports | PDF/Excel at milestone and weekly during peak design |
| Naming Convention | Per TM document numbering and DEL-02.27 |

### Submission Milestones
| Milestone | Model Status |
|-----------|--------------|
| FEED IFR | FEED model for review |
| FEED IFD | FEED model approved |
| 30% Detailed Design | DD model progress review |
| 60% Detailed Design | DD model progress review |
| 90% Detailed Design | Model near IFC status |
| IFC | Issue for Construction model |
| As-Built | Final as-built model |

### Related Documents
| Document | Relationship |
|----------|--------------|
| DEL-02.27 | 3D Model Implementation Plan - governing procedures |
| DEL-02.04 | Piping Key Plans - extracted from model |
| DEL-02.08 | Overall Plot Plan - extracted from model |
| DEL-02.09 | Area Plans - extracted from model |
| DEL-02.10 | Equipment Layout Plans - extracted from model |
| DEL-02.12 | Piping GAs - extracted from model |
| DEL-02.13 | Piping Isometrics - extracted from model |

---
*Generated by 4_DOCUMENTS Agent - 2026-02-01*
