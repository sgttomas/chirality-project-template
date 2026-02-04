# Specification: DEL-02.26 Bolt List

## Scope

### Purpose
The Bolt List provides a comprehensive inventory of all bolted flange connections within the piping scope for the Puget Sound Optimization (PSO) project. This document supports material procurement, construction planning, and installation verification for the booster pump station and manifold piping systems at Sumas Tank Farm.

### Boundaries
- **Included:**
  - All bolted connections within PKG-02 piping scope
  - Pipe-to-pipe flange connections
  - Pipe-to-equipment nozzle connections
  - Pipe-to-valve connections
  - Blind flanges and spectacle blinds
  - Tie-in connections to existing systems
- **Excluded:**
  - Structural bolting (covered under Civil/Structural package PKG-04)
  - Equipment internal bolting (covered under Mechanical Equipment package PKG-03)
  - Instrumentation tubing connections (covered under I&C package PKG-07)
  - Vendor package internal bolting (unless specifically required)
  - Temporary construction bolting

### Deliverables
- Bolt List document (native Excel format .xlsx)
- Bolt List document (PDF format for review/approval)
- **ASSUMPTION** - Summary statistics by material grade, size, and rating class

## Requirements

### Functional Requirements
| ID | Requirement |
|----|-------------|
| FR-01 | List shall include all bolted flange connections identified on IFC piping isometrics |
| FR-02 | Each entry shall be uniquely identified and traceable to source isometric and P&ID |
| FR-03 | Bolt specifications shall match PMC requirements for each service class |
| FR-04 | List shall support MTO generation and procurement activities |
| FR-05 | List shall be sortable and filterable by line, size, material, location, and rating |
| FR-06 | List shall identify special requirements (low temperature, sour service, etc.) |

### Data Requirements
| ID | Requirement |
|----|-------------|
| DR-01 | Bolt tag/identifier unique across project scope |
| DR-02 | Line number per Line List / LDT designation |
| DR-03 | Flange type, rating, and facing per PMC |
| DR-04 | Bolt and nut material grades per ASTM standards |
| DR-05 | Bolt diameter, length, and quantity per connection |
| DR-06 | Reference to P&ID and Isometric drawing numbers |
| DR-07 | Service/fluid designation per process requirements |
| DR-08 | Coating or treatment requirements where applicable |
| DR-09 | Washer requirements where specified by PMC or specification |

### Performance Requirements
| ID | Requirement |
|----|-------------|
| PR-01 | Document shall be updated to reflect approved design changes within **TBD** working days |
| PR-02 | Accuracy of bolt count shall be verified against isometrics prior to IFC release |
| PR-03 | All entries shall be validated against PMC requirements before issue |

## Standards

### Applicable Codes
| Code | Description |
|------|-------------|
| CSA Z662 | Oil and Gas Pipeline Systems |
| ASME B31.3 | Process Piping |
| ASME B16.5 | Pipe Flanges and Flanged Fittings (NPS 1/2 through NPS 24) |
| ASME B16.47 | Large Diameter Steel Flanges (NPS 26 through NPS 60) |
| ASME B16.20 | Metallic Gaskets for Pipe Flanges |
| ASME B18.2.1 | Square, Hex, Heavy Hex, and Askew Head Bolts and Hex Nuts |

### Material Standards
| Standard | Description |
|----------|-------------|
| ASTM A193 | Alloy-Steel and Stainless Steel Bolting for High Temperature or High Pressure Service |
| ASTM A194 | Carbon Steel, Alloy Steel, and Stainless Steel Nuts for Bolts for High Pressure or High Temperature Service |
| ASTM A320 | Alloy-Steel and Stainless Steel Bolting for Low-Temperature Service |

### Project Standards
| Standard | Description |
|----------|-------------|
| TM Standards | Trans Mountain Pipeline standards for bolting specifications (**TBD**) |
| PMC Requirements | Piping Material Class requirements for bolt material selection |
| Project Specification | **TBD** - Project-specific bolting specification document |

## Verification

### Review Requirements
| Review Type | Description |
|-------------|-------------|
| Internal Check | Engineering Contractor internal QA/QC review by Checker |
| Discipline Review | Review by Lead Piping Engineer |
| Cross-discipline | Coordination verification with Piping Material Engineer and Procurement |
| Client Review | TM review and approval per document control procedure |

### Verification Methods
| Method | Application |
|--------|-------------|
| Document Comparison | Verify bolt list entries against IFC isometrics (100% check) |
| PMC Cross-check | Verify material grades match PMC specifications for service class |
| Quantity Audit | Sample verification of bolt quantities per ASME B16.5/B16.47 tables |
| MTO Reconciliation | Reconcile bolt list totals with Piping MTO quantities |
| Temperature Verification | Verify material grades suitable for design temperature range |

### Acceptance Criteria
| Criterion | Requirement |
|-----------|-------------|
| Completeness | 100% of bolted connections from IFC isometrics captured in list |
| Material Accuracy | Material grades match PMC requirements for all entries |
| Traceability | Every entry traceable to source P&ID and isometric |
| Format Compliance | Document format per TM deliverable requirements |
| Quantity Accuracy | Bolt quantities match ASME B16.5/B16.47 standard patterns |

## Documentation

### Submittal Requirements
| Requirement | Description |
|-------------|-------------|
| Format | Native Excel (.xlsx) and PDF |
| Naming Convention | Per TM document numbering system (**TBD**) |
| Transmittal | Via project document control system |
| Revision Tracking | Per TM revision control requirements |

### Submission Milestones
| Milestone | Status |
|-----------|--------|
| Detailed Design 60% | Issue for Review (IFR) |
| Detailed Design 90% | Issue for Review (IFR) |
| Detailed Design IFC | Issue for Construction (IFC) |
| As-Built | Final as-built revision |

### Archive Requirements
| Requirement | Description |
|-------------|-------------|
| Retention Period | **TBD** - Per TM document retention policy |
| Archive Format | Native Excel and PDF |
| Metadata | Document control metadata per TM requirements |

---
*Generated by 4_DOCUMENTS Agent - 2026-02-01*
