# Procedure: DEL-02.28 Sitewide 3D Model (As-Built + Design Integrated)

## Purpose

### Objective
This procedure defines the steps for developing, coordinating, verifying, and maintaining the Sitewide 3D Model for the Puget Sound Optimization Project at Sumas Tank Farm, ensuring accurate integration of existing conditions with new detailed design.

### Scope
Applies to all 3D modeling activities for PSO facilities, including existing site integration, new facility modeling, multi-discipline coordination, clash detection, and as-built updates.

### Responsibilities
| Role | Responsibility |
|------|----------------|
| 3D Model Coordinator | Overall model management, coordination, clash detection, reviews |
| Piping Designers/Modelers | Piping system modeling, isometric extraction support |
| Structural Modelers | Foundation and structural steel modeling |
| Electrical/I&C Modelers | Electrical equipment and cable tray modeling; instrument placement |
| Discipline Engineers | Technical review, clash resolution decisions |
| Lead Piping Engineer | Piping discipline approval, stress analysis coordination |
| Construction Lead | Constructability review input |
| Client (TM) | Review, approval, and as-built verification |

## Prerequisites

### Input Documents Required
| Document | Deliverable ID | Status Required |
|----------|----------------|-----------------|
| 3D Model Implementation Plan | DEL-02.27 | Approved |
| TM Existing Site Model | TM-provided | Received |
| Laser Scan Data (if available) | TM/Survey | Received |
| P&IDs | DEL-01.03 | IFD minimum for DD start |
| Equipment Datasheets | DEL-03.02 | Issued |
| Vendor Equipment Models | Vendors | Received for major equipment |
| Civil/Structural GAs | DEL-04.* | Draft minimum |
| Process Data | DEL-01.09 | Approved |

### Resources Required
| Resource | Role |
|----------|------|
| 3D Model Coordinator | Model management and coordination |
| Piping Designers/Modelers | Piping system modeling (quantity per schedule) |
| Structural Modelers | Foundation and steel modeling |
| Electrical/I&C Modelers | E&I system modeling |
| CAD Technicians | Support and extraction |

### Preconditions
- [ ] DEL-02.27 (3D Model Implementation Plan) approved
- [ ] TM existing site model received and reviewed
- [ ] Software platform installed and configured
- [ ] Coordinate system established and verified against TM model
- [ ] P&IDs at IFD status minimum
- [ ] Key vendor equipment models received
- [ ] Team trained on platform and procedures

## Steps

### Phase 1: Model Setup

| Step | Action | Responsible | Verification |
|------|--------|-------------|--------------|
| 1.1 | Establish project model environment per DEL-02.27 | 3D Model Coordinator | Environment tested and verified |
| 1.2 | Define coordinate system and datum points aligned with TM | 3D Model Coordinator | Alignment verified with TM model |
| 1.3 | Set up model hierarchy per DEL-02.27 structure | 3D Model Coordinator | Structure established |
| 1.4 | Import TM existing site model as reference | 3D Model Coordinator | Model imported and positioned |
| 1.5 | Integrate laser scan point cloud (if available) | 3D Model Coordinator | Point cloud loaded and aligned |
| 1.6 | Verify tie-in point locations against existing model/scan | Piping Engineer | Tie-in locations confirmed |
| 1.7 | Set up version control and backup procedures | CAD Manager | Backup procedures tested |
| 1.8 | Establish clash detection configuration | 3D Model Coordinator | Clash rules configured |

### Phase 2: FEED Model Development

| Step | Action | Responsible | Verification |
|------|--------|-------------|--------------|
| 2.1 | Place major equipment at preliminary locations | Piping Designer | Equipment positioned per layout |
| 2.2 | Route primary piping headers (main crude lines) | Piping Designer | Primary routing complete |
| 2.3 | Model preliminary structural elements | Structural Designer | Major structure in place |
| 2.4 | Conduct FEED model internal review | 3D Model Coordinator | Review comments logged |
| 2.5 | Address internal review comments | All Disciplines | Comments resolved |
| 2.6 | Conduct FEED model TM review | 3D Model Coordinator | TM review held |
| 2.7 | Address TM comments | All Disciplines | TM comments resolved |
| 2.8 | Issue approved FEED model | 3D Model Coordinator | FEED model issued |

### Phase 3: Detailed Design Model Development

| Step | Action | Responsible | Verification |
|------|--------|-------------|--------------|
| 3.1 | Import and position vendor equipment models | 3D Model Coordinator | Vendor models integrated |
| 3.2 | Complete equipment modeling with accurate nozzles | Piping Designer | Nozzle positions verified |
| 3.3 | Route all piping to final locations per P&IDs | Piping Designer | Piping routing complete |
| 3.4 | Model pipe supports per stress analysis requirements | Piping/Structural | Supports coordinated with stress |
| 3.5 | Complete structural modeling (foundations, steel, platforms) | Structural Designer | Structural complete |
| 3.6 | Model electrical equipment and cable trays | Electrical Designer | Electrical systems modeled |
| 3.7 | Model instrumentation and instrument stands | I&C Designer | Instrumentation complete |
| 3.8 | Model underground utilities | All Disciplines | Underground modeled |
| 3.9 | Model insulation envelopes | Piping Designer | Insulation added for clash |
| 3.10 | Model valve operator envelopes | Piping Designer | Operator envelopes added |

### Phase 4: Coordination and Clash Detection

| Step | Action | Responsible | Verification |
|------|--------|-------------|--------------|
| 4.1 | Run weekly clash detection during detailed design | 3D Model Coordinator | Clash reports generated |
| 4.2 | Issue clash reports to discipline leads | 3D Model Coordinator | Reports distributed |
| 4.3 | Resolve assigned clashes within **TBD** working days | Discipline Designers | Clashes resolved or escalated |
| 4.4 | Track clash resolution status | 3D Model Coordinator | Tracking log maintained |
| 4.5 | Conduct multi-discipline model reviews (30/60/90%) | All Disciplines | Reviews held and documented |
| 4.6 | Address review comments and update model | All Disciplines | Comments resolved |
| 4.7 | Conduct constructability review | Construction Lead | Constructability review complete |
| 4.8 | Conduct operator/maintainability review | TM Operations | Maintainability review complete |
| 4.9 | Escalate unresolved clashes to Piping Lead/Project | 3D Model Coordinator | Escalations documented |

### Phase 5: IFC Model

| Step | Action | Responsible | Verification |
|------|--------|-------------|--------------|
| 5.1 | Complete all piping routing and supports | Piping Designer | Piping 100% complete |
| 5.2 | Run final clash detection | 3D Model Coordinator | Zero hard clashes confirmed |
| 5.3 | Document any accepted soft clashes with justification | 3D Model Coordinator | Soft clash register complete |
| 5.4 | Extract IFC drawings (isometrics, GAs, etc.) | All Disciplines | Drawings extracted |
| 5.5 | Verify extracted deliverables match model | All Disciplines | Spot check verification |
| 5.6 | Conduct IFC model review | All Disciplines | IFC review complete |
| 5.7 | Address IFC review comments | All Disciplines | Comments resolved |
| 5.8 | Issue IFC model | 3D Model Coordinator | IFC model issued |

### Phase 6: As-Built Updates

| Step | Action | Responsible | Verification |
|------|--------|-------------|--------------|
| 6.1 | Receive field as-built redlines/data | Construction | As-built data received |
| 6.2 | Incorporate as-built changes into model | Discipline Designers | Changes incorporated |
| 6.3 | Verify as-built updates against field data | 3D Model Coordinator | Updates verified |
| 6.4 | Run as-built clash check | 3D Model Coordinator | No new clashes introduced |
| 6.5 | Conduct final as-built model verification | 3D Model Coordinator | As-built model verified |
| 6.6 | Issue final as-built model | 3D Model Coordinator | As-built model issued |
| 6.7 | Prepare model for TM turnover | 3D Model Coordinator | Turnover package prepared |
| 6.8 | Complete model turnover to TM | 3D Model Coordinator | Turnover accepted by TM |

## Verification

### Quality Checks
| Check | Method | Acceptance Criteria |
|-------|--------|---------------------|
| Completeness | Visual review of all scope areas | All scope areas modeled |
| Accuracy | Sample dimensional check against drawings | Dimensions match source documents |
| Clash-Free | Automated clash detection | Zero hard clashes at IFC |
| Coordination | Multi-discipline review | All discipline conflicts resolved |
| Extractability | Sample drawing extraction | Drawings extract correctly |

### Review and Approval
| Review Stage | Reviewer | Criteria |
|--------------|----------|----------|
| FEED Review | TM, Discipline Leads | FEED scope complete and coordinated |
| 30% DD Review | Discipline Leads | Design development on track |
| 60% DD Review | TM, Discipline Leads, Construction | Coordination progress, constructability |
| 90% DD Review | TM, Discipline Leads, Operations | Near-IFC readiness, maintainability |
| IFC Review | TM | IFC quality and completeness |
| As-Built Review | TM | As-built accuracy |

### Validation Activities
| Activity | Description |
|----------|-------------|
| Coordinate Check | Verify sample locations against field survey or laser scan |
| Nozzle Verification | Verify equipment nozzle positions against vendor data |
| Support Coordination | Verify pipe support locations with stress analysis |
| Extraction Test | Test drawing extraction procedures |

## Records

### Generated Records
| Record | Format | Retention |
|--------|--------|-----------|
| 3D Model Files (all versions) | Native format | Project life + **TBD** years per TM policy |
| Model Extracts | IFC, DWG, PDF | Project life + **TBD** years |
| Clash Reports | PDF/Excel | Project life |
| Model Review Records | PDF | Project life |
| As-Built Model | Native format | Project life + **TBD** years |

### Supporting Records
| Record | Format | Retention |
|--------|--------|-----------|
| Clash Resolution Log | Excel | Project life |
| Model Review Meeting Minutes | PDF | Project life |
| TM Approval Records | PDF | Project life + **TBD** years |
| Turnover Documentation | PDF | Project life + **TBD** years |

### Document Control
| Requirement | Description |
|-------------|-------------|
| Version Control | Per DEL-02.27 (3D Model Implementation Plan) |
| Backup | Daily incremental, weekly full backup |
| Distribution | Per project distribution matrix |
| Storage | Project model server with access control |

---
*Generated by 4_DOCUMENTS Agent - 2026-02-01*
