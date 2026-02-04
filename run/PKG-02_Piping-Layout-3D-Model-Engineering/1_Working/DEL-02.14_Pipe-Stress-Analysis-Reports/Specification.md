# Specification: DEL-02.14 Pipe Stress Analysis Report(s)

## 1. Scope

### 1.1 Purpose
This specification defines the requirements for developing Pipe Stress Analysis Reports for the Puget Sound Optimization (PSO) Project at Sumas Tank Farm. These reports shall document the flexibility analysis of critical piping systems, verify code compliance, provide support loads, and confirm equipment nozzle loads are within allowables.

### 1.2 Applicability
- All critical piping systems as defined in the Support & Pipe Stress Execution Plan (DEL-02.15)
- Booster pump suction and discharge piping for 5 VS6 units
- 5x6 manifold piping system
- Tie-in piping connecting to existing Sumas Tank Farm systems
- Large diameter headers (typically NPS 12 and above)
- Verification of impacts to adjacent existing piping/equipment per SOW-0240

### 1.3 Scope Boundaries

| In Scope | Out of Scope |
|----------|--------------|
| Flexibility/stress analysis for critical systems | Non-critical small bore piping (per execution plan) |
| Equipment nozzle load verification | Pressure design (covered by line class) |
| Support load calculations | Detailed support structural design (PKG-04) |
| Existing system impact verification | Operating procedures |
| Code compliance documentation | Piping layout design (DEL-02.12) |

## 2. Requirements

### 2.1 Analysis Requirements (per SOW-0240)

| Req ID | Requirement | Priority | Verification Method |
|--------|-------------|----------|---------------------|
| SAR-001 | Perform stress analysis for all critical piping systems | Mandatory | Report review |
| SAR-002 | Verify adjacent pre-existing piping/equipment compliance with CSA code under revised conditions | Mandatory | Report review |
| SAR-003 | Verify equipment nozzle loads are within vendor allowables | Mandatory | Nozzle load summary |
| SAR-004 | Calculate support loads for all stress-critical supports | Mandatory | Support load table |
| SAR-005 | Verify thermal expansion is accommodated | Mandatory | Displacement results |
| SAR-006 | Analyze sustained, displacement, and occasional load cases | Mandatory | Code check results |
| SAR-007 | Verify seismic loads where applicable | As required | Seismic analysis |
| SAR-008 | Provide native stress model files per SOW-0259 | Mandatory | File submission |

### 2.2 Report Content Requirements

| Section | Content |
|---------|---------|
| Executive Summary | Scope, key findings, pass/fail summary, recommendations |
| Analysis Basis | Design codes, load cases, materials, operating conditions |
| System Description | Description of analyzed piping system(s) |
| Analysis Model | Node diagram, support types, boundary conditions |
| Operating Cases | Operating temperature and pressure for each case |
| Stress Results | Sustained, displacement, occasional stresses vs allowables |
| Code Compliance | Pass/fail for all code requirements |
| Support Loads | Load table with directions (X, Y, Z, moments) |
| Equipment Nozzle Loads | Loads compared to allowable with utilization % |
| Recommendations | Support modifications, routing changes if required |
| Appendices | Detailed output, input file summary, calculation sheets |

### 2.3 Load Case Requirements

| Load Case | Description | Code Reference |
|-----------|-------------|----------------|
| Sustained (W+P) | Weight + Pressure | CSA Z662 / ASME B31.3 |
| Expansion (Thermal) | Operating temperature displacement | CSA Z662 / ASME B31.3 |
| Occasional | Occasional loads (wind, earthquake) | As applicable |
| Hydrotest | Hydrostatic test condition | ASME B31.3 |
| Startup/Shutdown | Transient thermal conditions | If significant |

### 2.4 Format Requirements

| Aspect | Requirement |
|--------|-------------|
| Report Format | PDF document per TMP report standards (TBD) |
| Native Files | Stress software native format (e.g., .c2, .mod) |
| Model Documentation | Node diagram, isometric extract with node numbers |
| Results Tables | Tabular presentation of stress ratios, loads |
| Graphics | Stress diagrams, displacement plots where helpful |

## 3. Standards

### 3.1 Governing Codes and Standards

| Standard | Description | Application |
|----------|-------------|-------------|
| CSA Z662 | Oil and gas pipeline systems | Primary stress code for pipeline scope |
| ASME B31.3 | Process Piping | Station/facility piping stress |
| ASME B31.4 | Pipeline Transportation Systems | If applicable to pipeline segments |
| API 610 | Centrifugal Pumps | Pump nozzle allowable loads |
| TMP Standards | Trans Mountain stress analysis standards (TBD) |

### 3.2 Project-Specific Standards

| Standard | Description |
|----------|-------------|
| DEL-02.15 | Support & Pipe Stress Execution Plan - analysis methodology |
| TMP Stress Analysis Standards | Criteria, software, load cases (TBD) |
| Drawing Numbering | Per Document & Tag Numbering Plan (DEL-00.02) |

### 3.3 Software Requirements
- Industry-standard pipe stress analysis software (TBD - e.g., CAESAR II, AutoPIPE)
- Licensed and validated for applicable codes
- Native files to be submitted per SOW-0259

## 4. Verification

### 4.1 Verification Methods

| Method | Description | Application |
|--------|-------------|-------------|
| Model Verification | Verify model geometry matches 3D/isometrics | Accuracy |
| Code Check Review | Review stress ratios against code limits | Compliance |
| Nozzle Load Check | Verify loads vs vendor allowables | Equipment protection |
| Support Load Review | Review support loads for reasonableness | Support design |
| Independent Check | Independent verification of critical systems | QA requirement |

### 4.2 Acceptance Criteria

| Criterion | Acceptance Standard |
|-----------|---------------------|
| Sustained Stress | Less than code allowable (typically 1.0 ratio) |
| Displacement Stress | Less than code allowable |
| Occasional Stress | Less than code allowable |
| Nozzle Loads | Within vendor allowable (typically < 100% utilization) |
| Existing System Impact | No overstress introduced to existing systems |
| Support Loads | Reasonable magnitude, no excessive uplift/friction |
| TM Approval | Owner review and approval obtained |

### 4.3 Review Stages

| Stage | Review Type | Participants | Focus |
|-------|-------------|--------------|-------|
| Preliminary | Routing review | Piping, Stress | Critical routing issues |
| 60% DD | Progress review | Piping, Stress, TM | Preliminary stress results |
| 90% DD | Pre-IFC review | All disciplines, TM | Final analysis, support loads |
| IFC | Final approval | TM, Engineer of Record | Code compliance, approval |

## 5. Documentation

### 5.1 Deliverable Components

| Component | Format | Requirement |
|-----------|--------|-------------|
| Stress Analysis Reports | PDF | Required |
| Native Stress Model Files | Software native | Required per SOW-0259 |
| Support Load Summaries | Excel/PDF | Required |
| Nozzle Load Summaries | Excel/PDF | Required |
| MDR Entry | Per DEL-00.01 | Required |

### 5.2 Submission Requirements
- Submit reports per TM document control procedures (SOW-0430)
- Register in MDR (DEL-00.01) with appropriate metadata
- Provide native stress model files per SOW-0259
- Upload to TM EDMS per SOW-0441, SOW-0442

### 5.3 Revision Control
- Report revision tracking per TMP procedures
- Document all revisions with description of changes
- Maintain native model version control

### 5.4 Cross-References

| Document | Purpose |
|----------|---------|
| DEL-02.15 | Execution Plan - analysis methodology |
| DEL-02.12 | GA Drawings - routing reference |
| DEL-02.13 | Isometrics - detailed routing, supports |
| DEL-02.16 | Support Standard Drawings - support types |
| DEL-02.17 | Support Location Plans - support positions |
| PKG-03 | Mechanical - equipment nozzle data |

---
*Document generated 2026-02-01 | Deliverable Status: OPEN*
