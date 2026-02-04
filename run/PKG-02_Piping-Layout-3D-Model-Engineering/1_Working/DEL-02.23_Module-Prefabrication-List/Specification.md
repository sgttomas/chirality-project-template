# Specification: Module & Prefabrication List

## 1. Scope

### 1.1 Purpose
This specification defines the requirements for developing and maintaining the Module & Prefabrication List for the Puget Sound Optimization Project at Sumas Tank Farm.

### 1.2 Applicability
- All piping modules and prefabricated assemblies
- Equipment skids within piping scope
- Shop-fabricated pipe spools
- Pre-assembled pipe supports
- Any component designated for off-site fabrication

### 1.3 Exclusions
- Vendor package equipment (tracked in Equipment List)
- Field-fabricated items not requiring tracking
- Bulk materials (tracked in MTO)

## 2. Requirements

### 2.1 Content Requirements

| Requirement | Description |
|-------------|-------------|
| REQ-01 | Unique identifier for each module/prefab item |
| REQ-02 | Clear description of item contents |
| REQ-03 | Overall dimensions (length, width, height) |
| REQ-04 | Weight (dry and operating where applicable) |
| REQ-05 | Fabrication location designation |
| REQ-06 | Delivery priority ranking |
| REQ-07 | Required on Site (ROS) date |
| REQ-08 | Reference to associated engineering drawings |
| REQ-09 | Current status tracking |

### 2.2 Dimensional Requirements

| Requirement | Description |
|-------------|-------------|
| REQ-10 | Dimensions shall consider transport envelope limits |
| REQ-11 | Weight shall include rigging allowances |
| REQ-12 | Lifting points shall be identified for heavy modules |
| REQ-13 | COG (center of gravity) identified for modules > 10 tonnes |

### 2.3 Format Requirements
- Excel spreadsheet with sortable columns
- Filter capability by type, priority, status
- Version control and revision tracking
- Linkage to 3D model data where applicable

### 2.4 Tracking Requirements

| Requirement | Description |
|-------------|-------------|
| REQ-14 | Track design status (preliminary, IFR, IFA, IFC) |
| REQ-15 | Track fabrication status (not started, in progress, complete) |
| REQ-16 | Track delivery status (at fab yard, shipped, received) |
| REQ-17 | Track installation status (stored, rigged, installed) |

## 3. Standards

| Standard | Description |
|----------|-------------|
| DOT Transport Regulations | Highway transport limits (**ASSUMPTION**) |
| OSHA 1926.251 | Rigging equipment for material handling |
| ASME BTH-1 | Design of Below-the-Hook Lifting Devices |
| TM-STD-MOD-001 | TM Modularization Standard (**TBD**) |

## 4. Verification

### 4.1 Verification Methods

| Method | Description |
|--------|-------------|
| 3D Model Review | Verify dimensions from model |
| Weight Calculation | Verify weight estimates/calculations |
| Transport Review | Verify dimensions within transport limits |
| Constructability Review | Review with Construction for feasibility |

### 4.2 Acceptance Criteria
- All prefabricated items identified and listed
- Dimensions verified against 3D model or drawings
- Weights calculated or estimated with basis stated
- Delivery sequence aligned with construction schedule
- Owner review and approval

## 5. Documentation

### 5.1 Deliverable Format
- Native: Excel (.xlsx)
- PDF export for review/approval cycles
- Integration with project scheduling system (**TBD**)

### 5.2 Submission Requirements

| Milestone | Status |
|-----------|--------|
| 30% Design | Preliminary list for strategy review |
| 60% Design | IFR list with dimensions |
| 90% Design | IFD list with final weights |
| IFC | Issue for Construction/Procurement |

### 5.3 Related Documents
- DEL-02.11: Module Location Plans
- DEL-02.13: Piping Isometrics
- DEL-02.19: Piping MTO
- DEL-02.28: Sitewide 3D Model
- DEL-02.33: Construction Work Packages

---
*Pass 1 Draft - Generated 2026-02-01*
