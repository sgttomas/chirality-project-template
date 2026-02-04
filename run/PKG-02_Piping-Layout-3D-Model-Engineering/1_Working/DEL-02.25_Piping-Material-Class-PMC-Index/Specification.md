# Specification: Piping Material Class (PMC) Index

## 1. Scope

### 1.1 Purpose
This specification defines the requirements for developing and maintaining the PMC Index for the Puget Sound Optimization Project at Sumas Tank Farm.

### 1.2 Applicability
- All piping material classes used on the project
- Both existing TM PMCs and new project-specific PMCs
- Version control and change history tracking

### 1.3 Exclusions
- Detailed PMC sheets (separate documents referenced by index)
- Vendor package internal piping material specifications
- Instrument tubing material classes (Instrumentation scope)

## 2. Requirements

### 2.1 Index Content Requirements

| Requirement | Description |
|-------------|-------------|
| REQ-01 | Each PMC shall have a unique identifier code |
| REQ-02 | Index shall include PMC description and intended service |
| REQ-03 | Index shall include pressure-temperature rating summary |
| REQ-04 | Index shall include base material designation |
| REQ-05 | Index shall include applicable design code reference |
| REQ-06 | Index shall include current revision status |
| REQ-07 | Index shall include change history for each PMC |
| REQ-08 | Index shall reference detailed PMC sheet document number |

### 2.2 Version Control Requirements

| Requirement | Description |
|-------------|-------------|
| REQ-09 | Each PMC shall have a revision number and date |
| REQ-10 | Change history shall document reason for each revision |
| REQ-11 | Superseded PMC revisions shall be identified |
| REQ-12 | Index revision shall track overall document changes |

### 2.3 Format Requirements
- Excel spreadsheet with sortable columns
- Filter capability by service, material, rating
- PDF summary for distribution
- Version control per project document management requirements

### 2.4 Linkage Requirements

| Requirement | Description |
|-------------|-------------|
| REQ-13 | Cross-reference to PMC Verification Report (DEL-02.24) |
| REQ-14 | Cross-reference to Line List (DEL-02.01) for PMC usage |
| REQ-15 | Hyperlinks to detailed PMC sheets where practical |
| REQ-16 | Linkage to 3D model material class data (**TBD**) |

## 3. Standards

| Standard | Description |
|----------|-------------|
| ASME B31.3 | Process Piping - material class basis |
| CSA Z662 | Oil and Gas Pipeline Systems (**ASSUMPTION**) |
| ASME B16.5 | Flange rating classes |
| ASME B16.34 | Valve rating classes |
| TM-STD-PMC-001 | TM PMC Numbering Standard (**TBD**) |
| TM-DOC-STD-001 | TM Document Control Standard (**TBD**) |

## 4. Verification

### 4.1 Verification Methods

| Method | Description |
|--------|-------------|
| Completeness Check | All project PMCs included in index |
| Accuracy Check | Data matches PMC sheet content |
| Cross-Reference Check | Verify linkages to related documents |
| Version Check | Revision status current and accurate |

### 4.2 Acceptance Criteria
- All PMCs used on project listed in index
- All required data fields populated
- Change history complete and accurate
- Cross-references verified
- Owner review and approval

## 5. Documentation

### 5.1 Deliverable Format
- Native: Excel (.xlsx)
- PDF export for distribution
- Integration with document management system

### 5.2 Submission Requirements

| Milestone | Status |
|-----------|--------|
| 30% Design | Preliminary index |
| 60% Design | Draft index with all project PMCs |
| 90% Design | IFR index |
| IFC | Approved index |

### 5.3 Maintenance Requirements
- Update index when PMC sheets are revised
- Track all changes in change history
- Issue revised index with design package updates
- Maintain alignment with PMC Verification Report

### 5.4 Related Documents
- DEL-02.24: PMC Verification Report
- DEL-02.01: Line List
- DEL-02.19: Piping MTO
- TM PMC Sheets (detailed material class specifications)

---
*Generated: 2026-02-01 | Status: INITIALIZED*
