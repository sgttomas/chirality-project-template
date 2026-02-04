# Procedure: DEL-02.27 3D CAD Model Implementation Plan

## Purpose

### Objective
This procedure defines the steps for developing, reviewing, approving, and maintaining the 3D CAD Model Implementation Plan for the Puget Sound Optimization Project at Sumas Tank Farm.

### Scope
Applies to the development of the implementation plan that governs all 3D modeling activities for PSO facilities, including integration with TM's existing site model and multi-discipline coordination.

### Responsibilities
| Role | Responsibility |
|------|----------------|
| 3D Model Coordinator | Lead author, coordinate inputs, compile plan, manage updates |
| CAD Manager | Technical procedures, software configuration, extraction methods |
| Lead Piping Engineer | Piping-specific requirements, isometric extraction, stress interface |
| Discipline Leads | Discipline-specific modeling requirements and review |
| IT Support | Infrastructure requirements, backup procedures, access control |
| Project Manager | Schedule alignment, resource allocation, approval coordination |
| Document Controller | Revision control, transmittal, distribution |
| Client (TM) | Standards input, review, and approval |

## Prerequisites

### Input Documents Required
| Document | Source | Status Required |
|----------|--------|-----------------|
| TM 3D CAD Standards | TM | Confirmed (**TBD**) |
| TM Existing Site Model Information | TM | Provided |
| Project Scope Definition | Project Management | Approved |
| Software Platform Decision | TM/Contractor | Confirmed (**TBD**) |
| Laser Scan Data (if available) | TM/Survey | Provided |
| Project Schedule | Project Management | Approved baseline |

### Resources Required
| Resource | Role |
|----------|------|
| 3D Model Coordinator | Lead author and compiler |
| CAD Manager | Technical input and review |
| Lead Piping Engineer | Piping requirements input |
| Discipline Leads | Discipline-specific input |
| IT Support | Infrastructure and software input |

### Preconditions
- [ ] TM 3D CAD standards obtained or confirmed as TBD
- [ ] Software platform decision made or in progress
- [ ] Project scope and layout requirements defined
- [ ] Key personnel identified (Model Coordinator, Discipline Leads)
- [ ] Access to TM existing site model information

## Steps

### Phase 1: Planning and Information Gathering

| Step | Action | Responsible | Verification |
|------|--------|-------------|--------------|
| 1.1 | Request and obtain TM 3D CAD standards and requirements | 3D Model Coordinator | Standards received or TBD status confirmed |
| 1.2 | Confirm software platform with TM | 3D Model Coordinator | Platform decision documented |
| 1.3 | Obtain existing Sumas Terminal site model information | 3D Model Coordinator | Model format and coordinate system documented |
| 1.4 | Review project scope and facility layout requirements | 3D Model Coordinator | Scope summary prepared |
| 1.5 | Identify discipline lead contacts and schedule input sessions | 3D Model Coordinator | Contact list and meeting schedule established |
| 1.6 | Obtain project schedule for phase alignment | 3D Model Coordinator | Schedule milestones identified |

### Phase 2: Plan Development

| Step | Action | Responsible | Verification |
|------|--------|-------------|--------------|
| 2.1 | Define model strategy and phasing approach | 3D Model Coordinator | Strategy section drafted |
| 2.2 | Document software platform, version, and licensing | CAD Manager | Platform section drafted |
| 2.3 | Develop model hierarchical structure (project, area, discipline) | 3D Model Coordinator | Structure diagram completed |
| 2.4 | Define coordinate system and datum alignment with TM site | 3D Model Coordinator | Coordinate system section drafted |
| 2.5 | Establish naming conventions for model elements | 3D Model Coordinator | Naming convention section drafted |
| 2.6 | Define level of detail requirements by project phase | 3D Model Coordinator | LOD table completed |
| 2.7 | Develop multi-discipline coordination workflows | 3D Model Coordinator | Workflow diagrams completed |
| 2.8 | Define clash detection procedures and schedule | 3D Model Coordinator | Clash detection section drafted |
| 2.9 | Document deliverable extraction methods | CAD Manager | Extraction procedures drafted |
| 2.10 | Develop QA/QC procedures for model verification | 3D Model Coordinator | QA/QC section drafted |
| 2.11 | Define integration approach for TM existing model | 3D Model Coordinator | Integration section drafted |
| 2.12 | Document data exchange formats and protocols | CAD Manager | Exchange format section drafted |
| 2.13 | Establish version control and backup procedures | CAD Manager / IT | Version control section drafted |
| 2.14 | Define model review session procedures | 3D Model Coordinator | Review procedures drafted |
| 2.15 | Document as-built update procedures | 3D Model Coordinator | As-built section drafted |
| 2.16 | Define model turnover requirements | 3D Model Coordinator | Turnover section drafted |

### Phase 3: Internal Review and Validation

| Step | Action | Responsible | Verification |
|------|--------|-------------|--------------|
| 3.1 | Compile draft plan document | 3D Model Coordinator | Draft document complete |
| 3.2 | Distribute to discipline leads for review | 3D Model Coordinator | Distribution confirmed |
| 3.3 | Conduct discipline-specific reviews | Discipline Leads | Review comments received |
| 3.4 | Validate coordinate system compatibility with TM existing model | 3D Model Coordinator | Compatibility confirmed or issues identified |
| 3.5 | Validate workflows are practical and achievable | CAD Manager | Workflow validation complete |
| 3.6 | Review by Lead Piping Engineer for piping-specific content | Lead Piping Engineer | Piping review complete |
| 3.7 | Address internal review comments | 3D Model Coordinator | Comments resolved |
| 3.8 | Obtain internal approval | Project Manager | Internal approval documented |

### Phase 4: Client Review and Approval

| Step | Action | Responsible | Verification |
|------|--------|-------------|--------------|
| 4.1 | Submit plan for TM review | Document Controller | Transmittal record created |
| 4.2 | Conduct TM review meeting (if requested) | 3D Model Coordinator | Meeting held and minutes recorded |
| 4.3 | Receive and log TM review comments | 3D Model Coordinator | Comments logged |
| 4.4 | Address TM comments and update plan | 3D Model Coordinator | Comments addressed |
| 4.5 | Resubmit for TM approval | Document Controller | Resubmittal confirmed |
| 4.6 | Obtain TM formal approval | Project Manager | Approval documented |
| 4.7 | Issue approved baseline version | Document Controller | Baseline version issued |
| 4.8 | Distribute to project team | Document Controller | Distribution confirmed |

### Phase 5: Maintenance and Updates

| Step | Action | Responsible | Verification |
|------|--------|-------------|--------------|
| 5.1 | Review plan at project phase transitions (FEED to DD, etc.) | 3D Model Coordinator | Phase review complete |
| 5.2 | Incorporate lessons learned during execution | 3D Model Coordinator | Lessons learned documented |
| 5.3 | Update plan for significant process changes | 3D Model Coordinator | Updates incorporated |
| 5.4 | Obtain approval for significant revisions | Project Manager | Revision approved |
| 5.5 | Reissue plan with updated revision number | Document Controller | Revised plan issued |
| 5.6 | Communicate changes to project team | 3D Model Coordinator | Communication completed |

## Verification

### Quality Checks
| Check | Method | Acceptance Criteria |
|-------|--------|---------------------|
| Completeness | Checklist against REQ-01 to REQ-16 | All required sections addressed |
| Standards Alignment | Comparison with TM 3D CAD standards | Compatible with TM requirements |
| Coordinate Compatibility | Technical verification against existing model | Coordinate system aligned |
| Workflow Practicality | Discipline lead review | Workflows confirmed achievable |
| Software Compatibility | CAD Manager verification | Platform and exchange formats confirmed |

### Review and Approval
| Review Stage | Reviewer | Criteria |
|--------------|----------|----------|
| Draft Review | Discipline Leads | Technical content and practicality |
| Technical Review | CAD Manager | Procedures and software configuration |
| Piping Review | Lead Piping Engineer | Piping-specific requirements |
| Internal Approval | Project Manager | Readiness for client submission |
| Client Review | TM | Standards compliance and acceptance |
| Final Approval | TM | Formal approval for use |

### Validation Activities
| Activity | Description |
|----------|-------------|
| Standards Check | Verify plan aligns with TM 3D CAD standards |
| Compatibility Test | Verify coordinate system compatibility with existing model |
| Workflow Walkthrough | Walk through key procedures with team |
| Extraction Test | Test deliverable extraction procedures |

## Records

### Generated Records
| Record | Format | Retention |
|--------|--------|-----------|
| 3D Model Implementation Plan | Word (.docx) + PDF | Project life + **TBD** years per TM policy |
| Plan Revisions | Word (.docx) + PDF | Project life + **TBD** years |
| Supporting Diagrams | Native format within document | Project life + **TBD** years |

### Supporting Records
| Record | Format | Retention |
|--------|--------|-----------|
| Internal Review Comments | PDF/Email | Project life |
| TM Review Comments | PDF/Email | Project life |
| Approval Records | PDF | Project life + **TBD** years |
| Meeting Minutes | PDF | Project life |

### Document Control
| Requirement | Description |
|-------------|-------------|
| Numbering | Per TM document numbering system (**TBD**) |
| Revision Control | Track all revisions with revision history in document |
| Distribution | Per project distribution matrix |
| Storage | Project document management system |
| Access Control | Per project security requirements |

---
*Generated by 4_DOCUMENTS Agent - 2026-02-01*
