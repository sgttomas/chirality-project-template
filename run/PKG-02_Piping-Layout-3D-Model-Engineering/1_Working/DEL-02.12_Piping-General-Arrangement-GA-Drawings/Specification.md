# Specification: DEL-02.12 Piping General Arrangement (GA) Drawings

## 1. Scope

### 1.1 Purpose
This specification defines the requirements for developing Piping General Arrangement (GA) Drawings for the Puget Sound Optimization (PSO) Project at Sumas Tank Farm. These drawings shall depict the routing and arrangement of all piping within the project scope, including equipment connections, instrument locations, and supporting infrastructure.

### 1.2 Applicability
- All new piping associated with the five VS6 booster pumps
- 5x6 manifold piping system and headers
- Tie-in connections to existing Sumas Tank Farm systems
- Above-ground and below-ground piping
- Pipe bridges, road crossings, and elevated pipe racks
- Sump tank piping and auxiliary systems
- Cathodic protection connection points

### 1.3 Scope Boundaries

| In Scope | Out of Scope |
|----------|--------------|
| All process piping routing and arrangement | Instrument tubing details (PKG-07 scope) |
| Equipment nozzle connections | Piping internal to vendor packages |
| Valve and instrument locations | Isometric fabrication details (DEL-02.13) |
| Below-ground piping with depth references | Pipe stress calculations (DEL-02.14) |
| Road crossings and pipe bridges | Detailed support designs (DEL-02.16) |
| CP test station and anode locations | Hot tap procedures (by others per SOW-0249) |

## 2. Requirements

### 2.1 Content Requirements

| Req ID | Requirement | Priority | Verification Method |
|--------|-------------|----------|---------------------|
| GAR-001 | Show all piping routes in plan view with line numbers | Mandatory | P&ID walkdown |
| GAR-002 | Provide sections and elevations for vertical routing clarity | Mandatory | Drawing review |
| GAR-003 | Indicate pipe sizes, line numbers, and flow direction for headers | Mandatory | Line list check |
| GAR-004 | Show equipment outlines with nozzle connections and orientations | Mandatory | Vendor data check |
| GAR-005 | Locate in-line instruments, control valves, and flow meters | Mandatory | P&ID comparison |
| GAR-006 | Identify all valves with tag numbers per Valve List | Mandatory | Valve list check |
| GAR-007 | Show general pipe support locations | Mandatory | Stress analysis input |
| GAR-008 | Indicate road crossings with elevation and crossing type | Mandatory | Drawing review |
| GAR-009 | Show pipe bridge/rack configurations and routing | Mandatory | Drawing review |
| GAR-010 | Mark cathodic protection test stations and ground anode locations | Mandatory | CP design coordination |
| GAR-011 | Include key dimensions from site grid/benchmarks | Mandatory | Drawing review |
| GAR-012 | Coordinate below-ground piping with civil drawings | Mandatory | Civil coordination |
| GAR-013 | Show tie-in locations to existing facilities | Mandatory | Tie-in list check |
| GAR-014 | Indicate demolition scope where applicable | As required | Drawing review |

### 2.2 Drawing Organization Requirements

| Element | Requirement |
|---------|-------------|
| Plan Views | Organized by area and/or elevation level |
| Section Views | At equipment connections, road crossings, complex routing |
| Elevation Views | For vertical piping runs and rack configurations |
| Match Lines | Consistent with Key Plan (DEL-02.04) references |
| Drawing Index | Cross-referenced in Key Plan |

### 2.3 Format Requirements

| Aspect | Requirement |
|--------|-------------|
| Drawing Size | Per TMP CAD standards (TBD - typically D or E size) |
| Native Format | CAD .dwg format (or as specified by TMP CAD standards) |
| PDF Output | Required for IFR/IFD/IFC submissions |
| Scale | Consistent across set; typical 1:50 or 1:100 |
| Layer Naming | Per TMP CAD layer standards (TBD) |
| Title Block | Per TMP drawing template |
| Revision Control | Clouds and history per project procedures |

### 2.4 Accuracy Requirements

| Aspect | Requirement |
|--------|-------------|
| Piping Routes | Extracted from verified 3D model (DEL-02.28) |
| Equipment Positions | Match Equipment Layout Plans (DEL-02.10) |
| Nozzle Orientations | Per approved vendor certified drawings |
| Dimensional Tolerance | Within construction tolerance (TBD) |
| Model Consistency | GA to match 3D model at each revision milestone |

### 2.5 Vendor Data Integration
- Verify vendor equipment/nozzle locations per SOW-0245
- Update GA drawings for any vendor data changes
- Document vendor drawing references on GA drawings

## 3. Standards

### 3.1 Governing Codes and Standards

| Standard | Description | Application |
|----------|-------------|-------------|
| TMP Standards & Specifications | Trans Mountain project standards | Primary (Attachment A08 - TBD) |
| CSA Z662 | Oil and gas pipeline systems | Pipeline systems compliance |
| ASME B31.3 | Process Piping | Station piping design |
| Title 49 PHMSA Part 195 | Pipeline safety (US jurisdiction) | If applicable per SOW-0404 |
| ASME Y14.1 | Drawing sheet size and format | ASSUMPTION - Drawing format |
| ASME Y14.100 | Engineering Drawing Practices | ASSUMPTION - Practices |

### 3.2 Project-Specific Standards

| Standard | Description |
|----------|-------------|
| TMP CAD Standards | Layer naming, symbology, title block format (TBD) |
| Project Coordinate System | Survey datum and grid reference (TBD) |
| Drawing Numbering | Per Document & Tag Numbering Plan (DEL-00.02) |
| Piping Material Classes | Per DEL-02.26 PMC verification |

### 3.3 Quality Standards
- Design verification per Deliverable Review & Verification Plan (DEL-00.03)
- Drawing checking per engineering QA/QC procedures (PKG-00)
- 3D model coordination via clash detection (DEL-02.28)

## 4. Verification

### 4.1 Verification Methods

| Method | Description | Application |
|--------|-------------|-------------|
| P&ID Walkdown | Verify all P&ID piping represented | Completeness |
| Model Overlay | Compare drawing to 3D model extraction | Accuracy |
| Line List Check | Verify line numbers match DEL-02.01 | Consistency |
| Valve List Check | Verify valve tags match DEL-02.02 | Consistency |
| Vendor Data Check | Confirm nozzle positions per vendor drawings | Equipment interface |
| Clash Review | 3D model clash detection | Spatial conflicts |
| Constructability Review | Installation feasibility review | Buildability |

### 4.2 Acceptance Criteria

| Criterion | Acceptance Standard |
|-----------|---------------------|
| Completeness | All P&ID piping represented in GA drawings |
| Equipment Interface | Connections match approved vendor data |
| Line Numbering | Consistent with Line List (DEL-02.01) |
| Support Locations | Shown at all critical locations per stress analysis |
| Model Consistency | Drawings match current 3D model revision |
| Code Compliance | Routing complies with CSA Z662 / ASME B31.3 requirements |
| TM Approval | Owner review and approval obtained |

### 4.3 Review Stages

| Stage | Review Type | Participants | Focus |
|-------|-------------|--------------|-------|
| IFR (FEED) | Preliminary design review | TM, Piping Lead | Routing concept |
| IFD (End of FEED) | Design freeze review | TM, All disciplines | Design completion |
| 30% DD | Progress review | Design team, TM | Vendor data integration |
| 60% DD | Interdisciplinary review | All disciplines, TM | Coordination |
| 90% DD | Pre-IFC review | All disciplines, Construction | Constructability |
| IFC | Final approval | TM, Engineer of Record | Construction release |
| As-Built | Final verification | Construction, TM | As-constructed condition |

## 5. Documentation

### 5.1 Deliverable Components

| Component | Format | Requirement |
|-----------|--------|-------------|
| GA Drawing Set | PDF + Native CAD | Required |
| Drawing Index | Included in Key Plan (DEL-02.04) | Required |
| MDR Entry | Per DEL-00.01 | Required |
| Native CAD Files | Per SOW-0259 | Required |

### 5.2 Submission Requirements
- Submit drawings per TM document control procedures (SOW-0430)
- Register in MDR (DEL-00.01) with appropriate metadata
- Provide native CAD files per SOW-0259
- Upload to TM EDMS per SOW-0441, SOW-0442

### 5.3 Revision Control
- Revision letters for working drafts (A, B, C...)
- Numeric revisions for issued versions (0, 1, 2...)
- Revision clouds to highlight changes
- Complete revision history in title block
- Track affected line numbers in revision descriptions

### 5.4 Cross-References

| Document | Purpose |
|----------|---------|
| DEL-01.03 | P&IDs - process definition |
| DEL-02.01 | Line List - line attributes |
| DEL-02.02 | Valve List - valve identification |
| DEL-02.04 | Key Plan - drawing index |
| DEL-02.10 | Equipment Layout - equipment positions |
| DEL-02.13 | Isometrics - fabrication details |
| DEL-02.17 | Support Plans - support locations |
| DEL-02.28 | 3D Model - source geometry |

---
*Document generated 2026-02-01 | Deliverable Status: OPEN*
