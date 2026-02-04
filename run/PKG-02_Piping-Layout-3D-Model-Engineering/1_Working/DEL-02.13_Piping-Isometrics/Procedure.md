# Procedure: DEL-02.13 Piping Isometrics

## 1. Purpose

### 1.1 Objective
This procedure defines the step-by-step process for developing, reviewing, and issuing Piping Isometric Drawings for the PSO Project at Sumas Tank Farm.

### 1.2 Scope
- Covers the development workflow from design completion through IFC and as-built updates
- Applies to all piping isometrics required for fabrication and installation
- Addresses weld tracking, BOM generation, and coordination with stress analysis

## 2. Prerequisites

### 2.1 Input Documents Required

| Input | Source | Status Required |
|-------|--------|-----------------|
| 3D CAD Model | DEL-02.28 | 90% design complete for IFC isometrics |
| Line List | DEL-02.01 | Current revision |
| Line Designation Table (LDT) | DEL-02.18 | Current revision |
| Valve List | DEL-02.02 | Current revision |
| Pipe Stress Analysis | DEL-02.14 | Complete for stress-critical lines |
| PMC Index / Specifications | DEL-02.26 | Approved |
| GA Drawings | DEL-02.12 | IFD minimum |
| Pipe Support Location Plans | DEL-02.17 | Draft minimum |
| Document Numbering Plan | DEL-00.02 | Approved |

### 2.2 Resources Required

| Resource | Role |
|----------|------|
| Piping Designer (Lead) | Isometric generation and annotation |
| 3D Model Coordinator | Model extraction support |
| Piping Engineer | Technical review, NDT/PWHT requirements |
| Stress Engineer | Support location verification |
| Piping Lead Engineer | Approval authority |
| QC Representative | Fabrication quality review |

### 2.3 Tools and Systems

| Tool | Purpose |
|------|---------|
| 3D CAD Software with ISO module | Isometric extraction (TBD per project) |
| 2D CAD Software | ISO editing and annotation |
| Weld Register | Weld tracking database/spreadsheet |
| Document Control System | Drawing registration and transmittal |
| TM EDMS | Final document submission |

### 2.4 Preconditions
- 3D model design-complete for lines to be issued
- Stress analysis complete for stress-critical lines
- PMCs and piping specifications approved
- Isometric numbering convention established per DEL-00.02
- Weld numbering convention established

## 3. Steps

### 3.1 Preparation Phase

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.1.1 | Confirm 3D model is design-complete for isometric scope | 3D Coordinator | Readiness confirmation |
| 3.1.2 | Obtain isometric drawing template per TMP standards | Document Control | Template ready |
| 3.1.3 | Establish weld numbering register for project | Piping Designer | Weld register initialized |
| 3.1.4 | Obtain stress analysis results for support locations | Stress Engineer | Support location data |
| 3.1.5 | Obtain current LDT for NDT and test requirements | Piping Designer | LDT (current rev) |
| 3.1.6 | Obtain drawing numbers from document control | Document Control | Numbers assigned |
| 3.1.7 | Plan isometric subdivision for long/complex lines | Piping Designer | ISO index plan |

### 3.2 Isometric Generation Phase

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.2.1 | Extract isometric views from 3D model | Piping Designer | Raw ISO extraction |
| 3.2.2 | Verify extracted geometry matches model | Piping Designer | Geometry verification |
| 3.2.3 | Define spool breaks per fabrication/transport limits | Piping Designer | Spool breaks defined |
| 3.2.4 | Assign spool numbers | Piping Designer | Spools numbered |
| 3.2.5 | Identify all weld locations | Piping Designer | Welds identified |
| 3.2.6 | Assign unique weld numbers per project convention | Piping Designer | Welds numbered |
| 3.2.7 | Distinguish shop welds from field welds | Piping Designer | Shop/field designated |
| 3.2.8 | Add fabrication dimensions (cut lengths, angles, offsets) | Piping Designer | Dimensions added |
| 3.2.9 | Add elevation references | Piping Designer | Elevations noted |
| 3.2.10 | Add pipe support locations and type references | Piping Designer | Supports shown |

### 3.3 Annotation and Detail Phase

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.3.1 | Add line number and service description | Piping Designer | Line ID complete |
| 3.3.2 | Add north arrow and orientation reference | Piping Designer | Orientation shown |
| 3.3.3 | Add P&ID and GA drawing references | Piping Designer | References added |
| 3.3.4 | Populate bill of materials (BOM) | Piping Designer | BOM complete |
| 3.3.5 | Add NDT requirements per weld per LDT | Piping Engineer | NDT requirements noted |
| 3.3.6 | Indicate PWHT requirements where applicable | Piping Engineer | PWHT noted |
| 3.3.7 | Add hydrotest package reference and boundaries | Piping Designer | Hydrotest info added |
| 3.3.8 | Add insulation type and thickness | Piping Designer | Insulation noted |
| 3.3.9 | Add heat tracing requirements | Piping Designer | Heat trace noted |
| 3.3.10 | Add coating/painting requirements | Piping Designer | Coating noted |
| 3.3.11 | Add continuation references to adjacent isometrics | Piping Designer | Continuations complete |
| 3.3.12 | Add flow direction arrows on headers | Piping Designer | Flow direction shown |
| 3.3.13 | Complete title block information | Piping Designer | Title block complete |

### 3.4 Special Handling: Tie-In Spools

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.4.1 | Identify all tie-in spools connecting to existing systems | Piping Designer | Tie-in spools identified |
| 3.4.2 | Mark "FIELD VERIFY DIMENSION" on tie-in measurements | Piping Designer | FV notes added |
| 3.4.3 | Show theoretical dimension with tolerance | Piping Designer | Tolerance noted |
| 3.4.4 | Add reference to Tie-In List (DEL-02.03) | Piping Designer | Tie-in list referenced |
| 3.4.5 | Note coordination requirements with Operations | Piping Designer | Ops notes added |

### 3.5 Verification Phase

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.5.1 | Verify all dimensions against 3D model | Piping Designer | Dimension verification |
| 3.5.2 | Cross-check BOM against model components | Piping Designer | BOM verification |
| 3.5.3 | Verify weld count and numbering against weld register | Piping Engineer | Weld register check |
| 3.5.4 | Confirm support locations match stress analysis | Stress Engineer | Support verification |
| 3.5.5 | Verify NDT requirements match LDT | Piping Engineer | NDT verification |
| 3.5.6 | Perform self-check using checklist | Piping Designer | Self-check record |
| 3.5.7 | Submit for internal technical check | Independent Checker | Check markup |
| 3.5.8 | Address checker comments | Piping Designer | Comments resolved |

### 3.6 Review Phase

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.6.1 | Submit for Piping Lead approval | Piping Lead | Discipline approval |
| 3.6.2 | Submit for fabricator/constructability review | Construction Rep / Fabricator | Constructability comments |
| 3.6.3 | Address constructability comments | Piping Designer | Comments resolved |
| 3.6.4 | Prepare transmittal for TM review | Document Control | Transmittal prepared |
| 3.6.5 | Submit to TM for review (60%/90%/IFC) | Document Control | Submission confirmation |
| 3.6.6 | Receive and log TM comments | Document Control | Comment log |
| 3.6.7 | Address TM comments and update isometrics | Piping Designer | Revised isometrics |
| 3.6.8 | Resubmit as required until approval | Document Control | Approval record |

### 3.7 Issuance Phase

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.7.1 | Finalize isometrics with IFC status | Piping Designer | Final isometrics |
| 3.7.2 | Add revision clouds for changes from previous issue | Piping Designer | Changes highlighted |
| 3.7.3 | Update revision block in title block | Piping Designer | Revision documented |
| 3.7.4 | Update weld register with final weld numbers | Piping Designer | Weld register finalized |
| 3.7.5 | Generate PDF for fabrication/field use | Piping Designer | PDF files |
| 3.7.6 | Package native CAD files per SOW-0259 | Piping Designer | Native file package |
| 3.7.7 | Update MDR (DEL-00.01) with isometric details | Document Control | MDR updated |
| 3.7.8 | Submit to TM EDMS per SOW-0442 | Document Control | EDMS submission |
| 3.7.9 | Distribute to fabricator per distribution matrix | Document Control | Fab shop distribution |
| 3.7.10 | Archive working files per project procedures | Piping Designer | Files archived |

### 3.8 As-Built Phase

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.8.1 | Receive as-built redlines from fabrication/construction | Piping Engineer | Redline markups |
| 3.8.2 | Verify redlines against actual installed condition | Piping Engineer | Verification record |
| 3.8.3 | Update isometrics to as-built status | Piping Designer | As-built isometrics |
| 3.8.4 | Update weld register with any weld changes | Piping Designer | Weld register as-built |
| 3.8.5 | Submit as-built for approval | Document Control | As-built approval |
| 3.8.6 | Final submission to TM EDMS | Document Control | Final as-built |

## 4. Verification

### 4.1 In-Process Verification

| Checkpoint | Verification Action | Acceptance Criteria |
|------------|---------------------|---------------------|
| After Step 3.2.2 | Verify geometry extraction | Matches 3D model |
| After Step 3.5.3 | Verify weld register | All welds numbered, no duplicates |
| After Step 3.5.4 | Verify support locations | Match stress analysis requirements |
| After Step 3.6.1 | Discipline approval | Piping Lead signoff |

### 4.2 Final Verification Checklist

| Item | Verified By | Date |
|------|-------------|------|
| All lines from Line List have isometrics | | |
| Dimensions verified against 3D model | | |
| BOM complete and accurate | | |
| All welds numbered and in register | | |
| Shop/field welds correctly designated | | |
| Support locations per stress analysis | | |
| NDT requirements per LDT | | |
| Hydrotest package references complete | | |
| Insulation and heat trace noted | | |
| Coating requirements noted | | |
| Tie-in spools marked for field verify | | |
| Title block complete and correct | | |
| Native files match PDF | | |

### 4.3 Quality Hold Points

| Hold Point | Gate Criteria | Approver |
|------------|---------------|----------|
| Pre-60% Issue | Internal check complete | Piping Lead |
| Pre-90% Issue | Support locations verified, NDT requirements confirmed | Piping Lead + Stress |
| Pre-IFC Issue | All comments resolved, fabricator review complete | Engineer of Record |
| Pre-Fabrication | QC review of fabrication package | QC + Piping Lead |
| Pre-As-Built | Field verification complete | Construction + Piping Lead |

## 5. Records

### 5.1 Records Generated

| Record | Format | Retention | Location |
|--------|--------|-----------|----------|
| Piping Isometrics (PDF) | PDF | Project life + 10 years | TM EDMS |
| Piping Isometrics (Native CAD) | DWG | Project life + 10 years | TM EDMS |
| Weld Register | Excel | Project life + 10 years | TM EDMS |
| BOM Summaries | Excel | Project life + 10 years | Project archive |
| Internal Check Markups | PDF | Project life | Project archive |
| TM Comment Logs | PDF/Excel | Project life | Project archive |
| Approval Records | PDF | Project life + 10 years | Document Control |

### 5.2 MDR Entry Requirements

| Field | Value |
|-------|-------|
| Document Type | Drawing |
| Discipline | Piping |
| Deliverable ID | DEL-02.13 |
| Status | Per current revision status |
| Native File Reference | Yes |
| Related Deliverables | DEL-02.01, DEL-02.12, DEL-02.14, DEL-02.18, DEL-02.19, DEL-02.21 |

### 5.3 Revision History Maintenance
- Maintain revision log in drawing title block
- Document revision descriptions (what changed, affected welds/spools)
- Highlight changes with revision clouds
- Update weld register for any weld number changes
- Archive superseded versions per project procedures

### 5.4 Traceability
- Link to 3D model revision/extraction date
- Reference LDT revision for NDT requirements
- Maintain weld register as traceability document
- Document stress analysis revision for support locations

---
*Document generated 2026-02-01 | Deliverable Status: OPEN*
