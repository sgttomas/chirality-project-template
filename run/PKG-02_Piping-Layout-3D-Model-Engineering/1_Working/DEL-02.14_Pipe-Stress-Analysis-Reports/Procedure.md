# Procedure: DEL-02.14 Pipe Stress Analysis Report(s)

## 1. Purpose

### 1.1 Objective
This procedure defines the step-by-step process for developing, reviewing, and issuing Pipe Stress Analysis Reports for the PSO Project at Sumas Tank Farm.

### 1.2 Scope
- Covers stress analysis workflow from critical line identification through IFC report issuance
- Applies to all critical piping systems per the Support & Pipe Stress Execution Plan (DEL-02.15)
- Addresses existing system verification requirements per SOW-0240

## 2. Prerequisites

### 2.1 Input Documents Required

| Input | Source | Status Required |
|-------|--------|-----------------|
| Support & Pipe Stress Execution Plan | DEL-02.15 | Approved |
| 3D CAD Model | DEL-02.28 | Design-complete for stress-critical lines |
| Piping Isometrics | DEL-02.13 | Draft minimum for routing |
| Line List | DEL-02.01 | Current revision |
| Line Designation Table (LDT) | DEL-02.18 | Current revision |
| P&IDs | DEL-01.03 | IFD minimum |
| Process Datasheets | DEL-01.09 | Current revision |
| Equipment Datasheets | PKG-03 | Approved |
| Vendor Allowable Nozzle Loads | Vendors | Approved/certified |
| Piping Material Specifications | DEL-02.26 | Approved |
| Site Ambient Data | Site records | Available |
| Existing System As-Builts | TM records | For tie-in verification |

### 2.2 Resources Required

| Resource | Role |
|----------|------|
| Lead Stress Engineer | Analysis development, report preparation |
| Stress Engineer | Model building, analysis support |
| Piping Designer | Routing coordination |
| Piping Engineer | Technical review |
| Mechanical Engineer | Equipment nozzle data coordination |

### 2.3 Tools and Systems

| Tool | Purpose |
|------|---------|
| Stress Analysis Software | CAESAR II, AutoPIPE, or equivalent (TBD) |
| 3D CAD Software | Geometry reference |
| Document Control System | Report registration |
| TM EDMS | Final submission |

### 2.4 Preconditions
- Support & Pipe Stress Execution Plan (DEL-02.15) approved
- Critical lines identified per execution plan
- Equipment nozzle allowable loads available
- Piping routing sufficiently developed for analysis

## 3. Steps

### 3.1 Preparation Phase

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.1.1 | Review Support & Pipe Stress Execution Plan (DEL-02.15) | Stress Engineer | Understanding of methodology |
| 3.1.2 | Identify critical lines per execution plan criteria | Stress Engineer | Critical line list |
| 3.1.3 | Obtain piping routing (isometrics, 3D model views) | Stress Engineer | Routing information |
| 3.1.4 | Obtain operating conditions from Process | Stress Engineer | Temperature, pressure data |
| 3.1.5 | Obtain equipment nozzle allowable loads | Stress Engineer | Vendor load limits |
| 3.1.6 | Obtain material properties from specifications | Stress Engineer | Material data |
| 3.1.7 | Establish node numbering convention | Stress Engineer | Numbering standard |

### 3.2 Model Building Phase

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.2.1 | Create stress model geometry from isometrics/3D | Stress Engineer | Base model |
| 3.2.2 | Verify model geometry against source documents | Stress Engineer | Geometry verification |
| 3.2.3 | Input pipe properties (size, schedule, material) | Stress Engineer | Pipe data |
| 3.2.4 | Input operating conditions (temperature, pressure) | Stress Engineer | Operating cases |
| 3.2.5 | Define support types and locations | Stress Engineer | Support definitions |
| 3.2.6 | Define equipment connections and boundary conditions | Stress Engineer | Equipment interfaces |
| 3.2.7 | For tie-ins: model sufficient existing system length | Stress Engineer | Existing system in model |
| 3.2.8 | Input spring hanger data if applicable | Stress Engineer | Spring data |

### 3.3 Analysis Phase

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.3.1 | Define load cases per execution plan | Stress Engineer | Load case definitions |
| 3.3.2 | Run static analysis for all load cases | Stress Engineer | Analysis results |
| 3.3.3 | Review results for errors or warnings | Stress Engineer | Error check |
| 3.3.4 | Extract code stress results | Stress Engineer | Stress summary |
| 3.3.5 | Extract support loads | Stress Engineer | Support load table |
| 3.3.6 | Extract equipment nozzle loads | Stress Engineer | Nozzle load summary |
| 3.3.7 | Compare nozzle loads to vendor allowables | Stress Engineer | Nozzle load check |
| 3.3.8 | Identify any overstressed conditions | Stress Engineer | Issue list |

### 3.4 Issue Resolution Phase (if required)

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.4.1 | Evaluate options for resolving overstress | Stress Engineer | Options analysis |
| 3.4.2 | Coordinate routing changes with Piping Designer | Stress + Piping | Revised routing |
| 3.4.3 | Modify supports as needed | Stress Engineer | Revised supports |
| 3.4.4 | Re-run analysis with modifications | Stress Engineer | Updated results |
| 3.4.5 | Verify all stresses and loads acceptable | Stress Engineer | Compliance verification |

### 3.5 Existing System Verification (per SOW-0240)

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.5.1 | Identify tie-in points to existing systems | Stress Engineer | Tie-in list |
| 3.5.2 | Obtain as-built information for existing piping | Stress Engineer | Existing system data |
| 3.5.3 | Model existing piping adjacent to tie-ins | Stress Engineer | Extended model |
| 3.5.4 | Analyze impact of new loads on existing system | Stress Engineer | Impact analysis |
| 3.5.5 | Verify existing system remains code-compliant | Stress Engineer | Compliance check |
| 3.5.6 | Document verification results | Stress Engineer | Documentation |

### 3.6 Report Preparation Phase

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.6.1 | Prepare executive summary | Stress Engineer | Summary section |
| 3.6.2 | Document analysis basis | Stress Engineer | Basis section |
| 3.6.3 | Prepare node diagram/isometric with node numbers | Stress Engineer | Model diagram |
| 3.6.4 | Prepare stress results summary tables | Stress Engineer | Stress tables |
| 3.6.5 | Prepare support load tables | Stress Engineer | Support load tables |
| 3.6.6 | Prepare nozzle load summary with comparison | Stress Engineer | Nozzle load tables |
| 3.6.7 | Document any recommendations | Stress Engineer | Recommendations |
| 3.6.8 | Compile appendices (detailed output) | Stress Engineer | Appendices |
| 3.6.9 | Package native model files | Stress Engineer | Native files |

### 3.7 Review Phase

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.7.1 | Perform self-check of report | Stress Engineer | Self-check record |
| 3.7.2 | Submit for independent check (critical systems) | Independent Checker | Check markup |
| 3.7.3 | Address checker comments | Stress Engineer | Comments resolved |
| 3.7.4 | Submit for Lead Stress Engineer approval | Lead Stress Engineer | Discipline approval |
| 3.7.5 | Coordinate support loads with Structural (PKG-04) | Stress + Structural | Support load confirmation |
| 3.7.6 | Confirm nozzle loads acceptable with Mechanical | Stress + Mechanical | Nozzle load acceptance |
| 3.7.7 | Prepare transmittal for TM review | Document Control | Transmittal prepared |
| 3.7.8 | Submit to TM for review | Document Control | Submission confirmation |
| 3.7.9 | Address TM comments | Stress Engineer | Revised report |
| 3.7.10 | Resubmit as required until approval | Document Control | Approval record |

### 3.8 Issuance Phase

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.8.1 | Finalize report with IFC status | Stress Engineer | Final report |
| 3.8.2 | Generate PDF | Stress Engineer | PDF file |
| 3.8.3 | Package native model files per SOW-0259 | Stress Engineer | Native file package |
| 3.8.4 | Update MDR (DEL-00.01) | Document Control | MDR updated |
| 3.8.5 | Submit to TM EDMS per SOW-0442 | Document Control | EDMS submission |
| 3.8.6 | Issue support loads to Structural for design | Document Control | Support load issue |
| 3.8.7 | Issue support locations to Piping (DEL-02.17) | Document Control | Support location issue |
| 3.8.8 | Archive working files | Stress Engineer | Files archived |

## 4. Verification

### 4.1 In-Process Verification

| Checkpoint | Verification Action | Acceptance Criteria |
|------------|---------------------|---------------------|
| After Step 3.2.2 | Verify model geometry | Matches isometrics/3D |
| After Step 3.3.4 | Review stress results | All stresses < allowable |
| After Step 3.3.7 | Verify nozzle loads | All loads < vendor allowable |
| After Step 3.5.5 | Verify existing system | No overstress introduced |

### 4.2 Final Verification Checklist

| Item | Verified By | Date |
|------|-------------|------|
| All critical lines analyzed per execution plan | | |
| Model geometry matches source documents | | |
| All load cases per execution plan included | | |
| All stress ratios < 1.0 (or justified) | | |
| All nozzle loads within vendor allowables | | |
| Existing system verification complete | | |
| Support loads issued to Structural | | |
| Native files packaged for submission | | |
| Report complete per specification | | |

### 4.3 Quality Hold Points

| Hold Point | Gate Criteria | Approver |
|------------|---------------|----------|
| Pre-Report Issue | Self-check + independent check complete | Lead Stress Engineer |
| Pre-IFC | TM comments addressed, nozzle loads verified | Engineer of Record |
| Support Load Release | Analysis complete, loads verified | Lead Stress Engineer |

## 5. Records

### 5.1 Records Generated

| Record | Format | Retention | Location |
|--------|--------|-----------|----------|
| Stress Analysis Reports | PDF | Project life + 10 years | TM EDMS |
| Native Stress Model Files | Software format | Project life + 10 years | TM EDMS |
| Support Load Summaries | Excel/PDF | Project life + 10 years | TM EDMS |
| Nozzle Load Summaries | Excel/PDF | Project life + 10 years | TM EDMS |
| Independent Check Markups | PDF | Project life | Project archive |
| TM Comment Logs | PDF/Excel | Project life | Project archive |

### 5.2 MDR Entry Requirements

| Field | Value |
|-------|-------|
| Document Type | Report |
| Discipline | Piping / Stress |
| Deliverable ID | DEL-02.14 |
| Status | Per current revision status |
| Native File Reference | Yes |
| Related Deliverables | DEL-02.13, DEL-02.15, DEL-02.16, DEL-02.17 |

### 5.3 Revision History Maintenance
- Maintain revision log in report
- Document all revisions with description of changes
- Maintain native model version control
- Archive superseded versions

### 5.4 Traceability
- Reference isometric/3D model revision used
- Document equipment nozzle data source and revision
- Reference execution plan (DEL-02.15) for methodology
- Link support loads to structural design (PKG-04)

---
*Document generated 2026-02-01 | Deliverable Status: OPEN*
