# Specification: DEL-02.11 Module Location Plans

## 1. Scope

### 1.1 Purpose
This specification defines the requirements for developing Module Location Plans for the Puget Sound Optimization (PSO) Project at Sumas Tank Farm. These drawings shall depict the location, orientation, and interface points of prefabricated modules within the facility layout to support construction planning and installation.

### 1.2 Applicability
- Applies when modularization strategies are adopted for the new booster pump station, manifold, and associated infrastructure
- Covers all prefabricated modules and skid-mounted assemblies intended for installation at the SW corner of Tank TK-102
- Conditional deliverable - required only if modular construction approach is confirmed during constructability assessment

### 1.3 Scope Boundaries

| In Scope | Out of Scope |
|----------|--------------|
| Module footprint locations and dimensions | Detailed module internal layouts (covered in DEL-02.10) |
| Module-to-module interface locations | Structural design of modules (PKG-04 scope) |
| Site positioning coordinates and elevations | Fabrication shop drawings (vendor scope) |
| Installation sequence references | Transport logistics (by others) |
| Tie-in locations to existing facilities | Hot tap procedures (by others per SOW-0249) |
| Access and clearance zones | Vendor package internal arrangements |

## 2. Requirements

### 2.1 Functional Requirements

| Req ID | Requirement | Priority | Verification Method |
|--------|-------------|----------|---------------------|
| MLR-001 | Show all module boundaries with dimensions referenced to site coordinate grid | Mandatory | Drawing review |
| MLR-002 | Indicate module identification tags consistent with Module/Prefabrication List (DEL-02.27) | Mandatory | Cross-reference check |
| MLR-003 | Show module orientation with respect to true north | Mandatory | Drawing review |
| MLR-004 | Depict interface points between modules (piping, electrical, instrument) | Mandatory | Drawing review |
| MLR-005 | Show tie-in locations to existing facilities | Mandatory | Coordination check |
| MLR-006 | Indicate lifting points and handling clearances where applicable | Recommended | Drawing review |
| MLR-007 | Reference foundation/support locations per civil/structural drawings | Mandatory | Cross-reference check |
| MLR-008 | Include match lines to adjacent area/plot plan drawings | Mandatory | Drawing review |
| MLR-009 | Provide installation sequence notes where applicable | Recommended | Constructability review |
| MLR-010 | Show required access and maintenance clearance zones | Mandatory | Drawing review |

### 2.2 Drawing Content Requirements

| Element | Requirement |
|---------|-------------|
| Title Block | Per TMP drawing standards (TBD) - includes drawing number, revision, date, approvals |
| Scale | Appropriate for clarity; typical 1:100 or 1:200 for site-level plans |
| North Arrow | True north orientation clearly indicated |
| Grid System | Site coordinate grid with labeled axes (Northing/Easting) |
| Module Outlines | Closed polylines with distinct fill/hatch for identification |
| Module Tags | Tag numbers matching DEL-02.27 module list |
| Equipment References | Major equipment tag numbers shown within module footprints |
| Interface Symbols | Standardized symbols for pipe, electrical, and I&C interfaces |
| Dimensions | Key dimensions from grid lines and between modules |
| Elevations | Base/finish floor elevations referenced to site datum |
| Legend | Complete legend explaining all symbols and abbreviations |
| General Notes | Standard notes for interpretation, tolerances, references |
| Revision Cloud | Changes highlighted per drawing revision protocol |

### 2.3 Format Requirements

| Aspect | Requirement |
|--------|-------------|
| Drawing Size | Per TMP CAD standards (TBD - typically D or E size) |
| Native Format | CAD .dwg format (or as specified by TMP CAD standards) |
| PDF Output | Required for IFR/IFD/IFC submissions |
| Layer Naming | Per TMP CAD layer standards (TBD) |
| File Naming | Per Document & Tag Numbering Instruction Plan (DEL-00.02) |

### 2.4 Coordination Requirements

| Coordination Item | Related Document | Verification |
|-------------------|------------------|--------------|
| Module positions | 3D CAD Model (DEL-02.28) | Overlay comparison |
| Foundation locations | Civil/Structural drawings (PKG-04) | Cross-discipline review |
| Equipment arrangement | Equipment Layout Plans (DEL-02.10) | Consistency check |
| Piping interfaces | GA Drawings (DEL-02.12) | Interface alignment |
| Electrical interfaces | Electrical layouts (PKG-06) | Interface coordination |
| Module inventory | Module/Prefabrication List (DEL-02.27) | Completeness check |

## 3. Standards

### 3.1 Governing Codes and Standards

| Standard | Description | Application |
|----------|-------------|-------------|
| TMP Standards & Specifications | Trans Mountain project standards | Primary governing standard (Attachment A08 - TBD) |
| CSA Z662 | Oil and gas pipeline systems | General compliance for pipeline facilities |
| ASME Y14.1 | Drawing sheet size and format | ASSUMPTION - Drawing format basis |
| ASME Y14.100 | Engineering Drawing Practices | ASSUMPTION - Drawing practices basis |
| ASME B31.3 | Process Piping | Piping module design basis |

### 3.2 Project-Specific Standards

| Standard | Description |
|----------|-------------|
| TMP CAD Standards | Layer naming, symbology, title block format (TBD) |
| Project Coordinate System | Survey datum and grid reference (TBD) |
| Drawing Numbering | Per Document & Tag Numbering Instruction Plan (DEL-00.02) |
| Module Tagging | Per Module/Prefabrication List conventions (DEL-02.27) |

### 3.3 Quality Standards
- Design verification per Deliverable Review & Verification Plan (DEL-00.03)
- Drawing checking per engineering QA/QC procedures (PKG-00)
- Model coordination via 3D clash detection (DEL-02.28)

## 4. Verification

### 4.1 Verification Methods

| Method | Description | Application |
|--------|-------------|-------------|
| Drawing Review | Technical review of drawing content and format | All content requirements |
| Cross-Reference Check | Verification against related drawings and lists | Module list, plot plans, layouts |
| Model Coordination | 3D model extraction verification | Geometry accuracy |
| Overlay Comparison | Overlay module plan on plot plan/area plans | Position consistency |
| Constructability Review | Review by construction/installation team | Installation feasibility |
| Clash Detection | 3D model clash check for module envelopes | Interference identification |

### 4.2 Acceptance Criteria

| Criterion | Acceptance Standard |
|-----------|---------------------|
| Completeness | All modules from Module/Prefabrication List (DEL-02.27) represented |
| Dimensional Accuracy | Consistent with 3D model within drawing tolerance |
| Coordinate Accuracy | Grid references verified against site survey datum |
| Legibility | All text and symbols readable at plotted scale |
| Coordination | No unresolved conflicts with related drawings |
| Format Compliance | Adherence to TMP drawing standards |
| Interface Alignment | All interface points coordinated with adjacent systems |

### 4.3 Review Stages

| Stage | Review Type | Participants | Output |
|-------|-------------|--------------|--------|
| IFR (FEED) | Preliminary design review | TM Engineering, Piping Lead | Review comments |
| IFD (End of FEED) | Design freeze review | TM Engineering, Construction | Approval for DD |
| 30% DD | Progress review | Design team, TM | Progress comments |
| 60% DD | Interdisciplinary coordination review | All disciplines, TM | Coordination signoff |
| 90% DD | Pre-IFC review | All disciplines, TM, Construction | Final comments |
| IFC | Final approval | TM, Engineer of Record | Issued for Construction |
| As-Built | Final verification | Construction, TM | As-built approval |

## 5. Documentation

### 5.1 Deliverable Components

| Component | Format | Requirement |
|-----------|--------|-------------|
| Module Location Plan Drawings | PDF + Native CAD | Required |
| Drawing Register Entry | MDR update (DEL-00.01) | Required |
| Revision History | Per drawing title block | Required |
| Native CAD Files | Per SOW-0259 | Required |

### 5.2 Submission Requirements
- Submit drawings per TM document control procedures (SOW-0430)
- Include in MDR (DEL-00.01) with appropriate metadata
- Provide native CAD files per SOW-0259
- Upload to TM EDMS per SOW-0441, SOW-0442

### 5.3 Revision Control
- Drawings shall carry revision letters (A, B, C... for working drafts; 0, 1, 2... for issued revisions)
- Revision clouds shall highlight changes from previous issue
- Revision history block shall document all changes with date and description

### 5.4 Cross-References

| Document | Purpose |
|----------|---------|
| DEL-02.27 | Module/Prefabrication List - module identification source |
| DEL-02.08 | Overall Plot Plan - site context |
| DEL-02.09 | Area Plans - area context |
| DEL-02.10 | Equipment Layout Plans - equipment detail |
| DEL-00.01 | MDR - document registration |
| DEL-00.02 | Numbering Plan - drawing number assignment |

---
*Document generated 2026-02-01 | Deliverable Status: OPEN*
