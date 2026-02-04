# Specification: DEL-02.27 3D CAD Model Implementation Plan

## Scope

### Purpose
The 3D CAD Model Implementation Plan defines the strategy, structure, standards, and procedures for developing and maintaining the 3D model for the Puget Sound Optimization Project at Sumas Tank Farm. This plan ensures consistent, coordinated modeling across all disciplines and enables integration with TM's existing site model.

### Boundaries
- **Included:**
  - 3D model development for all PSO facilities
  - Integration approach with TM existing Sumas Terminal model
  - Multi-discipline coordination (Piping, Civil/Structural, Mechanical, Electrical, I&C)
  - Brownfield as-built incorporation methodology
  - Model-based deliverable extraction procedures
  - Clash detection and resolution workflows
- **Excluded:**
  - Model development itself (covered by DEL-02.28)
  - Vendor package internal model development (integration approach only)
  - TM internal model maintenance procedures (post-project turnover)

### Deliverables
- 3D CAD Model Implementation Plan (Word native format)
- 3D CAD Model Implementation Plan (PDF for review/approval)
- Supporting diagrams and flowcharts (native format within document)

## Requirements

### Content Requirements
| ID | Requirement |
|----|-------------|
| REQ-01 | Model strategy and phasing approach (FEED, DD, IFC, As-Built) |
| REQ-02 | Software platform specification with version |
| REQ-03 | Model hierarchical structure definition (project, area, discipline, system) |
| REQ-04 | Coordinate system specification with datum references aligned to TM site grid |
| REQ-05 | Naming conventions for all model elements (equipment, piping, structural, etc.) |
| REQ-06 | Level of detail (LOD) requirements by project phase |
| REQ-07 | Multi-discipline model coordination procedures |
| REQ-08 | Clash detection workflow with frequency, tolerances, and resolution process |
| REQ-09 | Deliverable extraction procedures (drawings, isometrics, GAs, reports, MTOs) |
| REQ-10 | QA/QC procedures for model accuracy and completeness |
| REQ-11 | Integration approach with TM existing site model |
| REQ-12 | Data exchange formats and protocols (IFC, DWG, PDF, native) |
| REQ-13 | Version control, backup, and recovery procedures |
| REQ-14 | Model review session procedures (formal and informal) |
| REQ-15 | As-built model update procedures during construction |
| REQ-16 | Model turnover requirements to TM at project completion |

### Format Requirements
| ID | Requirement |
|----|-------------|
| FMT-01 | Document format: Word (.docx) native with PDF for issue |
| FMT-02 | Structured sections with clear headings per document template |
| FMT-03 | Diagrams for workflows, model structure, and coordination processes |
| FMT-04 | Reference to all applicable standards |
| FMT-05 | Appendices for detailed procedures as required |

### Alignment Requirements
| ID | Requirement |
|----|-------------|
| ALN-01 | Shall align with TM 3D CAD standards (**TBD** - to be confirmed) |
| ALN-02 | Shall be compatible with TM existing model format and coordinate system |
| ALN-03 | Shall support laser scan data integration for as-built verification |
| ALN-04 | Shall enable construction work package (CWP/FIWP) extraction |
| ALN-05 | Shall support regulatory documentation requirements |

## Standards

### Applicable Standards
| Standard | Description |
|----------|-------------|
| TM-STD-3D-001 | TM 3D CAD Standard (**TBD** - reference to be confirmed) |
| ISO 15926 | Industrial automation systems and integration (**ASSUMPTION**) |
| ISO 19650 | Organization and digitization of information about buildings and civil engineering works (**ASSUMPTION**) |
| Project CAD Standard | Project-specific CAD requirements (**TBD**) |

### Platform Standards
| Standard | Description |
|----------|-------------|
| Platform-specific | Per selected 3D modeling platform (AVEVA, Bentley, or other) (**TBD**) |
| Exchange Formats | IFC 4.0 or later for model exchange (**ASSUMPTION**) |

## Verification

### Review Requirements
| Review Type | Description |
|-------------|-------------|
| Internal Review | Engineering Contractor discipline leads review |
| Technical Review | 3D Model Coordinator and CAD Manager review |
| Alignment Check | Verification against TM standards |
| Client Review | TM review and approval |

### Verification Methods
| Method | Description |
|--------|-------------|
| Standards Comparison | Verify alignment with TM 3D CAD standards |
| Compatibility Check | Verify coordinate system compatible with existing site model |
| Workflow Demonstration | Walk through key procedures to confirm practicality |
| Completeness Audit | Verify all required sections addressed per REQ list |

### Acceptance Criteria
| Criterion | Requirement |
|-----------|-------------|
| Completeness | All required sections per REQ-01 through REQ-16 addressed |
| Standards Alignment | Alignment with TM 3D CAD standards confirmed by TM |
| Coordinate Compatibility | Coordinate system verified compatible with existing site model |
| Workflow Practicality | Workflows reviewed and confirmed achievable by discipline leads |
| Client Approval | TM formal review and approval obtained |

## Documentation

### Submittal Requirements
| Requirement | Description |
|-------------|-------------|
| Format | Native Word (.docx) and PDF |
| Supporting Files | Diagrams in native format (Visio, PowerPoint, or embedded) |
| Naming Convention | Per TM document numbering system (**TBD**) |
| Transmittal | Via project document control system |

### Submission Milestones
| Milestone | Status |
|-----------|--------|
| Project Kick-off | Draft for TM review |
| FEED Start | Approved baseline version |
| Detailed Design Start | Updated as required for DD phase |
| As-Built Phase | Final update for as-built procedures |

### Related Documents
| Document | Relationship |
|----------|--------------|
| DEL-02.28 | Sitewide 3D Model - developed per this plan |
| DEL-02.08 | Overall Plot Plan - extracted from model |
| DEL-02.09 | Area Plans - extracted from model |
| DEL-02.10 | Equipment Layout Plans - extracted from model |
| DEL-02.12 | Piping GAs - extracted from model |
| DEL-02.13 | Piping Isometrics - extracted from model |
| DEL-02.14 | Pipe Stress Analysis Reports - model provides geometry input |

---
*Generated by 4_DOCUMENTS Agent - 2026-02-01*
