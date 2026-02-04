# Specification: DEL-02.13 Piping Isometrics

## 1. Scope

### 1.1 Purpose
This specification defines the requirements for developing Piping Isometric Drawings for the Puget Sound Optimization (PSO) Project at Sumas Tank Farm. These drawings shall provide all information necessary for pipe spool fabrication, field installation, welding, non-destructive testing, hydrostatic testing, heat tracing, insulation, and coating.

### 1.2 Applicability
- All new piping within PSO project scope
- Booster pump suction and discharge piping for 5 VS6 units
- 5x6 manifold piping system
- Tie-in spools connecting to existing Sumas Tank Farm systems
- Sump tank and auxiliary piping systems
- Modified existing piping requiring new fabrication

### 1.3 Scope Boundaries

| In Scope | Out of Scope |
|----------|--------------|
| All project piping per Line List | Instrument tubing (PKG-07 scope) |
| Fabrication and field weld details | Piping internal to vendor packages |
| BOM for all components | Prefabricated vendor skid piping |
| Support locations | Detailed support design (DEL-02.16) |
| NDT and test requirements | NDT procedures (QC scope) |
| Insulation and coating requirements | Insulation application procedures |

## 2. Requirements

### 2.1 Content Requirements (per SOW-0248)

| Req ID | Requirement | Priority | Verification Method |
|--------|-------------|----------|---------------------|
| ISR-001 | Show piping geometry in isometric projection | Mandatory | Drawing review |
| ISR-002 | Provide all fabrication dimensions (cut lengths, angles, offsets) | Mandatory | Model verification |
| ISR-003 | Indicate pipe size, schedule, and material per PMC | Mandatory | PMC check |
| ISR-004 | Show all fittings with descriptions and component codes | Mandatory | BOM verification |
| ISR-005 | Identify all weld locations with unique weld numbers | Mandatory | Weld register check |
| ISR-006 | Distinguish shop welds from field welds | Mandatory | Drawing review |
| ISR-007 | Include pipe support locations and type references | Mandatory | Stress analysis check |
| ISR-008 | Indicate NDT/NDE requirements per weld per LDT | Mandatory | LDT cross-reference |
| ISR-009 | Show PWHT requirements where applicable | Mandatory | Drawing review |
| ISR-010 | Reference hydrotest package number and boundaries | Mandatory | Hydrotest package check |
| ISR-011 | Indicate heat tracing requirements | Mandatory | Drawing review |
| ISR-012 | Show insulation type and thickness | Mandatory | Drawing review |
| ISR-013 | Include coating/painting requirements | Mandatory | Drawing review |
| ISR-014 | Provide complete bill of materials (BOM) | Mandatory | Component count |
| ISR-015 | Include continuation references to adjacent isometrics | Mandatory | Drawing review |
| ISR-016 | Show flow direction on headers | Recommended | Drawing review |

### 2.2 Spool Organization Requirements

| Requirement | Description |
|-------------|-------------|
| Logical Spool Breaks | Break at flanges, transport limits, installation sequence |
| Transport Limits | Maximum spool dimensions per transport constraints (TBD) |
| Handling Limits | Maximum spool weight per handling/rigging limits (TBD) |
| Shop vs Field Welds | Maximize shop welds for quality; clearly mark field welds |
| Spool Numbering | Unique spool numbers per line |

### 2.3 Format Requirements

| Aspect | Requirement |
|--------|-------------|
| Drawing Size | Per TMP CAD standards (TBD - typically D size) |
| Native Format | CAD .dwg format (or as specified) |
| PDF Output | Required for fabrication and field use |
| Organization | One isometric per line number (or logical subdivision for long lines) |
| Title Block | Per TMP drawing template |
| BOM Location | Standard location on drawing (typically right side or bottom) |
| North Arrow | North arrow for orientation reference |

### 2.4 BOM Requirements

| Column | Content |
|--------|---------|
| Item No. | Sequential item number |
| Qty | Quantity of component |
| Description | Full component description |
| Size | Nominal pipe size |
| Material/Class | Material and PMC reference |
| Tag/Mark | Valve or specialty item tag |
| Remarks | Special notes (PWHT, coating, etc.) |

### 2.5 Weld Requirements

| Requirement | Description |
|-------------|-------------|
| Unique Weld Numbers | Each weld uniquely numbered across project |
| Weld Symbols | Standard weld symbols per applicable code |
| WPS Reference | Reference to applicable welding procedure |
| Shop/Field Designation | Clear indication of shop vs field weld |
| NDT Requirements | Per LDT (DEL-02.18) requirements |

## 3. Standards

### 3.1 Governing Codes and Standards

| Standard | Description | Application |
|----------|-------------|-------------|
| TMP Standards & Specifications | Trans Mountain project standards | Primary (Attachment A08 - TBD) |
| CSA Z662 | Oil and gas pipeline systems | Pipeline code compliance |
| ASME B31.3 | Process Piping | Station piping |
| ASME B16.5 | Pipe Flanges and Flanged Fittings | Flange standards |
| ASME B16.9 | Factory-Made Wrought Buttwelding Fittings | Fitting standards |
| ASME B16.11 | Forged Fittings, Socket-Welding and Threaded | SW/THD fittings |
| ASME B16.25 | Buttwelding Ends | Weld end preparation |
| ASME B16.47 | Large Diameter Steel Flanges | Large flanges |

### 3.2 Project-Specific Standards

| Standard | Description |
|----------|-------------|
| TMP Isometric Standards | Drawing format, symbols, conventions (TBD) |
| TMP Welding Standards | Weld symbols, WPS references (TBD) |
| Project Weld Numbering | Weld numbering convention (TBD) |
| Drawing Numbering | Per Document & Tag Numbering Plan (DEL-00.02) |

### 3.3 Quality Standards
- Design verification per Deliverable Review & Verification Plan (DEL-00.03)
- Drawing checking per engineering QA/QC procedures
- Fabricator review for buildability

## 4. Verification

### 4.1 Verification Methods

| Method | Description | Application |
|--------|-------------|-------------|
| Model Verification | Verify dimensions against 3D model | Accuracy |
| Line List Check | Verify all lines have isometrics | Completeness |
| Weld Register Check | Verify weld numbers unique and complete | Weld tracking |
| BOM Verification | Verify component counts | MTO accuracy |
| LDT Cross-Reference | Verify NDT/test requirements | Code compliance |
| Stress Analysis Check | Verify support locations | Stress requirements |
| Constructability Review | Fabricator/field review | Buildability |

### 4.2 Acceptance Criteria

| Criterion | Acceptance Standard |
|-----------|---------------------|
| Completeness | All lines from Line List (DEL-02.01) have corresponding isometrics |
| Dimensional Accuracy | Dimensions verified against 3D model within tolerance |
| Weld Tracking | All welds uniquely numbered; weld register complete |
| BOM Accuracy | Component counts match model; no missing items |
| Support Locations | All stress-required supports shown |
| Code Compliance | NDT and test requirements per LDT (DEL-02.18) |
| TM Approval | Owner review and approval obtained |

### 4.3 Review Stages

| Stage | Review Type | Participants | Focus |
|-------|-------------|--------------|-------|
| 60% DD | Progress review | Piping team, Stress | Support locations, spool breaks |
| 90% DD | Pre-IFC review | All disciplines, QC | Fabrication readiness |
| IFC | Final approval | TM, Engineer of Record | Construction release |
| Pre-Fab | Fabricator review | Fabricator, QC | Buildability |
| As-Built | Final verification | Construction, QC | As-constructed condition |

## 5. Documentation

### 5.1 Deliverable Components

| Component | Format | Requirement |
|-----------|--------|-------------|
| Isometric Drawing Set | PDF + Native CAD | Required |
| Weld Register | Excel | Required |
| BOM Summary | Excel (feeds MTO) | Required |
| MDR Entry | Per DEL-00.01 | Required |

### 5.2 Submission Requirements
- Submit drawings per TM document control procedures (SOW-0430)
- Register in MDR (DEL-00.01) with appropriate metadata
- Provide native CAD files per SOW-0259
- Upload to TM EDMS per SOW-0441, SOW-0442

### 5.3 Revision Control
- Revision letters for working drafts (A, B, C...)
- Numeric revisions for issued versions (0, 1, 2...)
- Revision clouds to highlight changes
- Track affected welds/spools in revision description
- Complete revision history in title block

### 5.4 Cross-References

| Document | Purpose |
|----------|---------|
| DEL-02.01 | Line List - line identification |
| DEL-02.02 | Valve List - valve identification |
| DEL-02.12 | GA Drawings - routing reference |
| DEL-02.14 | Pipe Stress Analysis - support locations |
| DEL-02.18 | LDT - NDT and test requirements |
| DEL-02.19 | Piping MTO - BOM aggregation |
| DEL-02.21 | Hydrotest Packages - test boundaries |
| DEL-02.28 | 3D Model - source geometry |

---
*Document generated 2026-02-01 | Deliverable Status: OPEN*
