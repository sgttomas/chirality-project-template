# Procedure: DEL-02.26 Bolt List

## Purpose

### Objective
This procedure defines the steps for developing, verifying, and maintaining the Bolt List for the PSO project piping scope, ensuring complete and accurate documentation of all bolted flange connections at Sumas Tank Farm.

### Scope
Applies to all bolted flange connections within PKG-02 piping scope, including pipe-to-pipe, pipe-to-valve, pipe-to-equipment, blind flange, and spectacle blind connections for the booster pump station, manifold, and associated piping systems.

### Responsibilities
| Role | Responsibility |
|------|----------------|
| Piping Designer | Initial bolt list extraction/compilation from isometrics, data population |
| Piping Engineer | Technical review, PMC compliance verification, issue resolution |
| Piping Lead Engineer | Approval, coordination with MTO/Procurement, final sign-off |
| Checker | Independent verification of data accuracy |
| Document Controller | Revision control, transmittal, distribution |
| Client (TM) | Review and acceptance |

## Prerequisites

### Input Documents Required
| Document | Deliverable ID | Status Required |
|----------|----------------|-----------------|
| P&IDs | DEL-01.03 | IFC or approved |
| Line List | DEL-02.01 | Approved |
| Valve List | DEL-02.02 | Approved or IFC |
| Piping Isometrics | DEL-02.13 | Substantially complete (80%+ for initial, 100% for IFC) |
| Line Designation Table (LDT) | DEL-02.18 | Approved or IFC |
| Piping Material Classes (PMC) | DEL-02.25 | Approved |
| Valve/Specialty Item Datasheets | DEL-02.20 | Substantially complete |
| Equipment Datasheets | DEL-03.02 | Issued (for nozzle flange data) |

### Tools and Resources
| Tool/Resource | Purpose |
|---------------|---------|
| 3D CAD Model | Bolt list extraction (if model-based approach used) |
| Bolt List Template | **TBD** - Standard template per TM format requirements |
| PMC Reference Tables | Material grade and bolting pattern lookup |
| ASME B16.5 / B16.47 | Standard flange bolting patterns and dimensions |
| Bolt Length Tables | Standard bolt length by flange class and gasket type |

### Preconditions
- [ ] Piping isometrics substantially complete for scope area (minimum 80%)
- [ ] PMCs finalized and approved by TM
- [ ] Valve datasheets available with flange rating confirmation
- [ ] Equipment nozzle data confirmed from vendor documentation
- [ ] Bolt list template approved for use
- [ ] Coordinate system and line numbering finalized

## Steps

### Phase 1: Preparation

| Step | Action | Responsible | Verification |
|------|--------|-------------|--------------|
| 1.1 | Obtain latest revision of approved PMCs and identify bolting requirements for each material class | Piping Engineer | PMC revision status confirmed |
| 1.2 | Obtain approved Bolt List template from document control | Document Controller | Template approved for use |
| 1.3 | Confirm design temperature limits from process data | Piping Engineer | Process data confirmed |
| 1.4 | Identify any special service requirements (sour service, low temp, etc.) | Piping Engineer | Special requirements documented |

### Phase 2: Data Extraction

| Step | Action | Responsible | Verification |
|------|--------|-------------|--------------|
| 2.1 | **ASSUMPTION** - Extract bolt connection data from 3D CAD model OR compile manually from isometrics | Piping Designer | All isometrics in scope covered |
| 2.2 | Populate bolt list template with connection identification (unique tag, line number, P&ID ref, ISO ref) | Piping Designer | Unique tag assigned to each connection |
| 2.3 | Identify flange type, rating, and NPS for each connection from isometrics | Piping Designer | Cross-reference with isometrics |
| 2.4 | Record connection type (pipe-to-pipe, pipe-to-valve, pipe-to-equipment, blind, etc.) | Piping Designer | Connection types categorized |
| 2.5 | Assign bolt specification (type, size, material, quantity) per PMC and ASME B16.5/B16.47 | Piping Designer | PMC compliance verified |
| 2.6 | Record nut material specification per PMC | Piping Designer | Nut grades match bolt grades |
| 2.7 | Record washer requirements if specified by PMC | Piping Designer | Washer requirements noted |
| 2.8 | Calculate bolt length per flange configuration and gasket type | Piping Engineer | Length calculation documented |

### Phase 3: Technical Review

| Step | Action | Responsible | Verification |
|------|--------|-------------|--------------|
| 3.1 | Verify bolt materials match PMC requirements for each line class | Piping Engineer | 100% entries checked |
| 3.2 | Verify bolt quantities match standard flange patterns per ASME B16.5/B16.47 | Piping Engineer | Standard tables referenced |
| 3.3 | Verify bolt lengths appropriate for flange configuration and gasket type | Piping Engineer | Sample lengths verified by calculation |
| 3.4 | Cross-reference valve flange ratings with line class requirements | Piping Engineer | Valve datasheet confirmation |
| 3.5 | Verify equipment nozzle flange ratings from vendor data | Piping Engineer | Vendor data confirmation |
| 3.6 | Verify temperature ratings suitable for design conditions | Piping Engineer | Temperature limits checked |
| 3.7 | Identify and resolve any discrepancies or special requirements | Piping Engineer | Discrepancy log cleared |
| 3.8 | Independent check by Checker | Checker | Check signature obtained |

### Phase 4: Coordination

| Step | Action | Responsible | Verification |
|------|--------|-------------|--------------|
| 4.1 | Coordinate with MTO development to ensure bolt list supports procurement quantities | Piping Lead | MTO alignment confirmed |
| 4.2 | Coordinate with Materials Engineer on any special coating/treatment requirements | Piping Engineer | **TBD** - Special requirements identified |
| 4.3 | Coordinate with Construction on installation sequence and delivery requirements | Piping Lead | **TBD** - Delivery schedule alignment |
| 4.4 | Resolve any cross-discipline interface issues (equipment, structural) | Piping Lead | Interface issues closed |
| 4.5 | Confirm spare bolting requirements with Operations/Construction | Piping Lead | **TBD** - Spare quantity defined |

### Phase 5: Finalization

| Step | Action | Responsible | Verification |
|------|--------|-------------|--------------|
| 5.1 | Perform final QA check of bolt list for completeness and accuracy | Checker | QA checklist complete |
| 5.2 | Generate summary statistics (total by material, size, rating) | Piping Designer | Summary tables complete |
| 5.3 | Prepare bolt list in required formats (native Excel and PDF) | Piping Designer | Format compliance confirmed |
| 5.4 | Submit for Piping Lead Engineer approval | Piping Designer | Approval signature obtained |
| 5.5 | Transmit to TM for review and acceptance | Document Controller | Transmittal record created |
| 5.6 | Address TM review comments and resubmit if required | Piping Engineer | Comments addressed |
| 5.7 | Obtain TM acceptance | Document Controller | Acceptance recorded |

### Phase 6: Maintenance

| Step | Action | Responsible | Verification |
|------|--------|-------------|--------------|
| 6.1 | Monitor design changes that affect bolted connections (MOC, design revisions) | Piping Engineer | Change tracking active |
| 6.2 | Update bolt list for approved changes within **TBD** working days | Piping Designer | Updates incorporated |
| 6.3 | Re-verify updated entries against PMC and isometrics | Piping Engineer | Verification complete |
| 6.4 | Issue revised bolt list with updated revision status | Document Controller | Revision issued |
| 6.5 | Maintain alignment between bolt list and IFC isometrics | Piping Engineer | Alignment verified at IFC |
| 6.6 | Update for as-built conditions during construction | Piping Engineer | As-built updates incorporated |

## Verification

### Quality Checks
| Check | Method | Acceptance Criteria |
|-------|--------|---------------------|
| Completeness | Compare connection count to isometric joint count | 100% connections captured |
| Material Accuracy | Cross-reference PMC specifications | All entries match PMC requirements |
| Quantity Accuracy | Spot-check against ASME B16.5/B16.47 tables | Sample (minimum 10%) verified correct |
| Length Accuracy | Verify sample calculations | Lengths correct per flange/gasket configuration |
| Traceability | Verify source references | All entries have valid P&ID and ISO references |
| Format Compliance | Check against template requirements | All required fields populated |

### Review and Approval
| Review Stage | Reviewer | Criteria |
|--------------|----------|----------|
| Self-Check | Piping Designer | Data entry accuracy |
| Independent Check | Checker | Technical accuracy and completeness |
| Discipline Approval | Piping Lead Engineer | Readiness for client submission |
| Client Review | TM | Compliance with project requirements |
| Final Acceptance | TM | Formal acceptance for use |

### Validation Activities
| Activity | Description |
|----------|-------------|
| Isometric Cross-check | Verify sample of bolt list entries against source isometrics (minimum 10%) |
| PMC Audit | Verify sample of material grades against PMC specifications |
| MTO Reconciliation | Confirm bolt list quantities reconcile with Piping MTO totals |

## Records

### Generated Records
| Record | Format | Retention |
|--------|--------|-----------|
| Bolt List (IFR/IFC/As-Built) | Excel (.xlsx) and PDF | Project life + **TBD** years per TM policy |
| Bolt List Revisions | Excel (.xlsx) and PDF | Project life + **TBD** years |
| Summary Statistics | PDF (within Bolt List document) | Project life + **TBD** years |

### Supporting Records
| Record | Format | Retention |
|--------|--------|-----------|
| QA/Check Checklist | PDF | Project life + **TBD** years |
| Review Comments | PDF/Native | Project life |
| Transmittal Records | PDF | Project life + **TBD** years |
| Revision History Log | Within document | Project life + **TBD** years |
| TM Acceptance Records | PDF | Project life + **TBD** years |

### Document Control
| Requirement | Description |
|-------------|-------------|
| Numbering | Per TM document numbering system (**TBD**) |
| Revision Control | Per TM revision control procedure; revision history within document |
| Distribution | Via project document control system per distribution matrix |
| Access Control | **TBD** - Per project security requirements |

---
*Generated by 4_DOCUMENTS Agent - 2026-02-01*
