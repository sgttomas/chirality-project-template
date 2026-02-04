# Procedure: DEL-02.12 Piping General Arrangement (GA) Drawings

## 1. Purpose

### 1.1 Objective
This procedure defines the step-by-step process for developing, reviewing, and issuing Piping General Arrangement (GA) Drawings for the PSO Project at Sumas Tank Farm.

### 1.2 Scope
- Covers the development workflow from FEED through IFC and as-built updates
- Applies to all GA drawings for above-ground and below-ground piping within the PSO project scope
- Addresses coordination with 3D model, P&IDs, and related piping deliverables

## 2. Prerequisites

### 2.1 Input Documents Required

| Input | Source | Status Required |
|-------|--------|-----------------|
| P&IDs | DEL-01.03 | IFR minimum for FEED; IFD for DD |
| Line List | DEL-02.01 | Current revision |
| Valve List | DEL-02.02 | Current revision |
| Equipment Layout Plans | DEL-02.10 | IFR minimum |
| 3D CAD Model | DEL-02.28 | 30% for FEED; 60%+ for DD |
| Piping Key Plan | DEL-02.04 | Established |
| Vendor Equipment Data | Vendors | Approved/certified |
| Site Survey Data | Existing TM records | Verified current |
| Document Numbering Plan | DEL-00.02 | Approved |
| Stress Analysis (preliminary) | DEL-02.14 | For support locations |

### 2.2 Resources Required

| Resource | Role |
|----------|------|
| Piping Designer (Lead) | Drawing development |
| 3D Model Coordinator | Model extraction and coordination |
| CAD Technician | Drawing production support |
| Piping Engineer | Technical review |
| Piping Lead Engineer | Approval authority |
| Process Engineer | P&ID consistency review |
| Construction Representative | Constructability input |

### 2.3 Tools and Systems

| Tool | Purpose |
|------|---------|
| 3D CAD Software | Model viewing and extraction (TBD per project) |
| 2D CAD Software | Drawing production (TBD per project) |
| Document Control System | Drawing registration and transmittal |
| TM EDMS | Final document submission |

### 2.4 Preconditions
- 3D model developed to appropriate level for current phase
- P&IDs issued for review/design as applicable
- Equipment layout confirmed
- Drawing numbering assigned per DEL-00.02
- CAD template available per TMP standards

## 3. Steps

### 3.1 Drawing Set Planning

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.1.1 | Review P&IDs and Line List to understand scope | Piping Designer | Scope understanding |
| 3.1.2 | Determine number of drawings required based on site extent | Piping Lead | Drawing count estimate |
| 3.1.3 | Define drawing limits and match lines per Key Plan (DEL-02.04) | Piping Designer | Drawing boundaries |
| 3.1.4 | Plan view elevations (grade level, pipe rack, etc.) | Piping Designer | View plan |
| 3.1.5 | Identify sections required (equipment connections, crossings) | Piping Designer | Section list |
| 3.1.6 | Obtain drawing numbers from document control per DEL-00.02 | Document Control | Numbers assigned |
| 3.1.7 | Create drawing index and update Key Plan | Piping Designer | Index created |

### 3.2 Base Drawing Setup

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.2.1 | Set up drawing template per TMP CAD standards | CAD Technician | Template ready |
| 3.2.2 | Import site grid/survey reference as base layer | CAD Technician | Grid established |
| 3.2.3 | Import equipment layout as background | CAD Technician | Equipment context |
| 3.2.4 | Set up drawing layers per TMP CAD layer standards | CAD Technician | Layers configured |
| 3.2.5 | Add title block, north arrow, scale bar | CAD Technician | Drawing setup complete |

### 3.3 Piping Extraction from 3D Model

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.3.1 | Request piping extraction from 3D model | Piping Designer | Extraction request |
| 3.3.2 | Extract piping views from 3D model at specified elevations | 3D Coordinator | Extracted geometry files |
| 3.3.3 | Import extracted geometry into CAD drawings | CAD Technician | Piping imported |
| 3.3.4 | Organize geometry by layer (piping, equipment, structural) | CAD Technician | Layers organized |
| 3.3.5 | Verify extracted data matches current model revision | Piping Designer | Verification record |

### 3.4 Annotation and Detailing

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.4.1 | Add line numbers per Line List (DEL-02.01) | Piping Designer | Line numbers annotated |
| 3.4.2 | Add pipe sizes at size changes and key locations | Piping Designer | Sizes annotated |
| 3.4.3 | Add valve tag numbers per Valve List (DEL-02.02) | Piping Designer | Valves annotated |
| 3.4.4 | Show instrument locations per P&ID | Piping Designer | Instruments located |
| 3.4.5 | Add flow direction arrows on major headers | Piping Designer | Flow direction shown |
| 3.4.6 | Add key dimensions from grid/benchmarks | Piping Designer | Dimensions added |
| 3.4.7 | Add elevation annotations for vertical changes | Piping Designer | Elevations noted |
| 3.4.8 | Indicate pipe support locations (general) | Piping Designer | Supports shown |
| 3.4.9 | Create section views for complex areas | CAD Technician | Sections created |
| 3.4.10 | Add match line references to adjacent drawings | Piping Designer | Match lines added |
| 3.4.11 | Add section cut references | Piping Designer | Section callouts added |
| 3.4.12 | Complete legend and general notes | Piping Designer | Legend/notes complete |
| 3.4.13 | Add cross-references to isometrics (DEL-02.13) | Piping Designer | ISO references added |

### 3.5 Coordination Phase

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.5.1 | Verify all P&ID piping is represented (P&ID walkdown) | Piping Engineer | P&ID verification record |
| 3.5.2 | Check line numbers against Line List (DEL-02.01) | Piping Designer | Line list check |
| 3.5.3 | Verify valve tags against Valve List (DEL-02.02) | Piping Designer | Valve list check |
| 3.5.4 | Confirm equipment connections match vendor data per SOW-0245 | Piping Engineer | Vendor data verification |
| 3.5.5 | Coordinate below-ground routing with civil drawings | Piping Lead + Civil Lead | Civil coordination record |
| 3.5.6 | Conduct 3D clash detection | 3D Coordinator | Clash report |
| 3.5.7 | Resolve clashes and update 3D model/drawings | Piping Designer | Clashes resolved |
| 3.5.8 | Review for constructability with construction team | Construction Rep | Constructability comments |

### 3.6 Review Phase

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.6.1 | Perform self-check using checklist | Piping Designer | Self-check record |
| 3.6.2 | Submit for internal discipline check | Independent Checker | Check markup |
| 3.6.3 | Address checker comments | Piping Designer | Comments resolved |
| 3.6.4 | Submit for Piping Lead approval | Piping Lead | Discipline approval |
| 3.6.5 | Submit for Process Engineer P&ID consistency review | Process Engineer | Process approval |
| 3.6.6 | Prepare transmittal for TM review | Document Control | Transmittal prepared |
| 3.6.7 | Submit to TM for review (IFR/milestone) | Document Control | Submission confirmation |
| 3.6.8 | Receive and log TM comments | Document Control | Comment log |
| 3.6.9 | Address TM comments and update drawings | Piping Designer | Revised drawings |
| 3.6.10 | Resubmit as required until approval | Document Control | Approval record |

### 3.7 Issuance Phase

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.7.1 | Finalize drawings with approved status (IFD/IFC) | Piping Designer | Final drawings |
| 3.7.2 | Add revision clouds for changes from previous issue | CAD Technician | Changes highlighted |
| 3.7.3 | Update revision block in title block | CAD Technician | Revision documented |
| 3.7.4 | Generate PDF for submission | CAD Technician | PDF files |
| 3.7.5 | Package native CAD files per SOW-0259 | CAD Technician | Native file package |
| 3.7.6 | Update MDR (DEL-00.01) with drawing details | Document Control | MDR updated |
| 3.7.7 | Submit to TM EDMS per SOW-0442 | Document Control | EDMS submission |
| 3.7.8 | Archive working files per project procedures | CAD Technician | Files archived |

### 3.8 Maintenance and As-Built Phase

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.8.1 | Update drawings for model/design changes as required | Piping Designer | Updated drawings |
| 3.8.2 | Re-issue at appropriate milestones | Document Control | Revised issues |
| 3.8.3 | Receive as-built redlines from construction | Piping Engineer | Redline markups |
| 3.8.4 | Verify redlines against field conditions | Piping Engineer | Verification record |
| 3.8.5 | Update drawings to as-built status | CAD Technician | As-built drawings |
| 3.8.6 | Submit as-built for approval and final EDMS upload | Document Control | Final as-built |

## 4. Verification

### 4.1 In-Process Verification

| Checkpoint | Verification Action | Acceptance Criteria |
|------------|---------------------|---------------------|
| After Step 3.3.5 | Verify extraction matches model | Geometry consistent |
| After Step 3.5.1 | P&ID walkdown complete | All P&ID piping shown |
| After Step 3.5.6 | Clash report reviewed | No unresolved clashes |
| After Step 3.6.4 | Discipline approval obtained | Piping Lead signoff |

### 4.2 Final Verification Checklist

| Item | Verified By | Date |
|------|-------------|------|
| All P&ID piping represented | | |
| Line numbers match Line List (DEL-02.01) | | |
| Valve tags match Valve List (DEL-02.02) | | |
| Equipment connections match vendor data | | |
| Support locations shown | | |
| Match lines consistent with Key Plan | | |
| All sections referenced and complete | | |
| Legend and notes complete | | |
| Title block complete and correct | | |
| Revision history current | | |
| Native files match PDF | | |

### 4.3 Quality Hold Points

| Hold Point | Gate Criteria | Approver |
|------------|---------------|----------|
| Pre-IFR Submission | Internal check complete, P&ID verification | Piping Lead |
| Pre-IFD Submission | FEED comments resolved, coordination complete | Piping Lead + TM |
| Pre-IFC Submission | DD comments resolved, clash-free, constructability verified | Engineer of Record |
| Pre-As-Built | Field verification complete, redlines incorporated | Construction + Piping Lead |

## 5. Records

### 5.1 Records Generated

| Record | Format | Retention | Location |
|--------|--------|-----------|----------|
| GA Drawings (PDF) | PDF | Project life + 10 years | TM EDMS |
| GA Drawings (Native CAD) | DWG | Project life + 10 years | TM EDMS |
| Internal Check Markups | PDF | Project life | Project archive |
| P&ID Walkdown Records | PDF | Project life | Project archive |
| TM Comment Logs | PDF/Excel | Project life | Project archive |
| Clash Reports | PDF | Project life | Project archive |
| Coordination Records | PDF/Email | Project life | Project archive |
| Transmittal Records | PDF | Project life | Document Control system |

### 5.2 MDR Entry Requirements

| Field | Value |
|-------|-------|
| Document Type | Drawing |
| Discipline | Piping |
| Deliverable ID | DEL-02.12 |
| Status | Per current revision status |
| Native File Reference | Yes |
| Related Deliverables | DEL-01.03, DEL-02.01, DEL-02.04, DEL-02.13, DEL-02.28 |

### 5.3 Revision History Maintenance
- Maintain revision log in drawing title block
- Document revision descriptions (what changed, affected line numbers)
- Highlight changes with revision clouds
- Archive superseded versions per project document control procedures

### 5.4 Traceability
- Link to 3D model revision/extraction date
- Reference P&ID revision used
- Document vendor data revision incorporated
- Maintain record of TM approvals at each milestone

---
*Document generated 2026-02-01 | Deliverable Status: OPEN*
