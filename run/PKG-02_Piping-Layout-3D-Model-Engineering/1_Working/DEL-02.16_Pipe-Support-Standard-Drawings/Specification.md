# Specification: Pipe Support Standard Drawings

**Deliverable ID:** DEL-02.16
**Package:** PKG-02 (Piping, Layout & 3D Model Engineering)
**Version:** 0.1 (Initial Draft)
**Status:** INITIALIZED
**Date:** 2026-02-01

---

## 1. Purpose

This specification defines the requirements for developing Pipe Support Standard Drawings for the Puget Sound Optimization Project (PSO) at Sumas Tank Farm. These drawings shall detail each type of pipe support used in the project scope.

---

## 2. Scope

### 2.1 Applicable Facilities
- New booster pump station (5 x VS6-type booster pumps) at SW corner of TK-102
- New 5x6 manifold system
- Associated infrastructure piping and connections
- Containment wall area piping supports

### 2.2 Applicable Systems
- Main process piping (crude oil service)
- Utility piping (if applicable)
- Drain and vent piping

---

## 3. Normative References

### 3.1 Codes and Standards (Mandatory)

| Code/Standard | Title | Application |
|---------------|-------|-------------|
| CSA Z662 | Oil and Gas Pipeline Systems | Primary code per SOW Section 4.1.3 |
| ASME B31.4 | Pipeline Transportation Systems for Liquids and Slurries | Supplemental piping code |
| MSS SP-58 | Pipe Hangers and Supports - Materials, Design and Manufacture | Support design basis |
| MSS SP-69 | Pipe Hangers and Supports - Selection and Application | Support selection criteria |
| MSS SP-89 | Pipe Hangers and Supports - Fabrication and Installation Practices | Fabrication requirements |

### 3.2 Project References

| Reference | Description |
|-----------|-------------|
| TM Standards and Specifications | Per SOW Section 4.1.2 (Attachment A08 - TBD) |
| Support & Pipe Stress Execution Plan | DEL-02.15 |
| Pipe Stress Analysis Report(s) | DEL-02.14 |
| Line Designation Table | DEL-02.18 |
| Piping Material Class Index | DEL-02.25 |

---

## 4. Technical Requirements

### 4.1 General Requirements

4.1.1 Each standard drawing shall depict one support type with all necessary dimensions, materials, and fabrication notes.

4.1.2 Drawings shall be developed to allow direct use by fabrication and construction contractors.

4.1.3 All support types used in the project shall have a corresponding standard drawing.

4.1.4 Drawings shall indicate applicability by pipe size range, temperature range, and load capacity.

### 4.2 Content Requirements

Each standard drawing shall include:

| Element | Requirement |
|---------|-------------|
| Support geometry | Fully dimensioned with tolerances |
| Material specification | Per PMC and structural steel specs |
| Weld details | Size, type, and inspection requirements |
| Bill of materials | Component list with quantities |
| Finish/coating | Painting/galvanizing requirements |
| Load capacity | Maximum allowable loads in all directions |
| Pipe size range | Applicable pipe diameters |
| Attachment method | To pipe and to structural steel/concrete |
| Notes | Installation, fabrication, and QC notes |

### 4.3 Support Type Categories

Standard drawings shall be provided for the following support categories (ASSUMPTION - to be confirmed):

**4.3.1 Rest Supports**
- Standard pipe shoe (various heights)
- Adjustable pipe shoe
- Wear pads for sliding surfaces

**4.3.2 Restraint Supports**
- Line stops / anchors
- Guides (single and double acting)
- Limit stops

**4.3.3 Hanger Supports**
- Rigid hangers
- Variable spring hangers (if required per stress analysis)
- Constant load hangers (if required per stress analysis)

**4.3.4 Special Supports**
- Trunnion supports for heavy loads
- Dummy legs for equipment connections
- U-bolts for small bore piping
- Clamps for auxiliary attachments

### 4.4 Material Requirements

| Component | Material Specification | Notes |
|-----------|----------------------|-------|
| Structural steel | ASTM A36 or equivalent | Per structural specs |
| Pipe attachment | Compatible with pipe material | Avoid dissimilar metal contact |
| Bolting | TBD per PMC requirements | Hot-dip galvanized for outdoor |
| Wear surfaces | Low friction material | PTFE or similar where required |

### 4.5 Design Load Requirements

4.5.1 Support designs shall accommodate loads from pipe stress analysis (DEL-02.14).

4.5.2 Design loads shall include:
- Dead weight (pipe + contents + insulation)
- Thermal expansion/contraction loads
- Dynamic loads (pressure pulsation, seismic)
- Friction loads at sliding surfaces
- Wind loads (if applicable)
- Test condition loads (hydrotest)

4.5.3 Load tables shall be included on drawings or referenced documents.

### 4.6 Dimensional Requirements

4.6.1 All dimensions shall be in metric (mm) with imperial equivalents where required by TM standards.

4.6.2 Tolerances shall be per MSS SP-89 unless otherwise specified.

4.6.3 Pipe-to-support interface dimensions shall accommodate pipe size ranges and insulation thicknesses.

---

## 5. Drawing Format and Presentation

### 5.1 Drawing Standards

| Requirement | Specification |
|-------------|---------------|
| CAD Software | AutoCAD or equivalent per TM standards |
| Drawing Size | TBD (per TM requirements) |
| Title Block | TM standard title block format |
| Numbering | Per TM document numbering system |
| Scale | As required for clarity (1:10, 1:5 typical) |

### 5.2 Drawing Content Organization

Each drawing sheet shall include:
- Plan view
- Elevation view(s)
- Section details as required
- Bill of materials table
- General notes
- Reference to applicable specifications

### 5.3 Revision Control

5.3.1 Drawings shall be developed through standard revision cycles: IFR -> IFD -> IFC.

5.3.2 Revision clouds and triangles shall identify changes per TM standards.

5.3.3 Revision history shall be maintained on drawing title block.

---

## 6. Interface Requirements

### 6.1 Stress Analysis Interface
- Support locations and loads from stress analysis shall be inputs
- Support stiffness values shall be provided back to stress analysis if required

### 6.2 Structural Interface
- Support reactions shall be provided to structural engineering (PKG-04)
- Attachment details to steel/concrete shall be coordinated

### 6.3 3D Model Interface
- Support geometry shall be modeled in sitewide 3D model (DEL-02.28)
- Clash detection shall be performed

### 6.4 Isometric Interface
- Support callouts on isometrics (DEL-02.13) shall reference standard drawings

---

## 7. Quality Assurance

### 7.1 Design Verification
- Drawings shall be checked per Deliverable Review & Verification Plan (DEL-00.03)
- Load capacities shall be verified against stress analysis requirements

### 7.2 Code Compliance
- Compliance with CSA Z662 and applicable MSS standards shall be documented
- Deviations from TM standards shall be logged per deviation process

### 7.3 Drawing Quality
- Drawings shall be checked for completeness, accuracy, and constructability
- Coordination with related deliverables shall be verified

---

## 8. Deliverables

| Item | Format | Quantity |
|------|--------|----------|
| Standard Support Drawings | Native CAD + PDF | TBD (10-20 sheets estimated) |
| Support Type Register | Excel | 1 |
| Drawing Transmittal | Per TM requirements | Per submission |

---

## 9. TBD Items

| Item | Description | Owner |
|------|-------------|-------|
| TBD-01 | TM CAD standards and title block format | TM Document Control |
| TBD-02 | TM-specific support design requirements | TM Piping Lead |
| TBD-03 | Seismic design parameters | Structural Engineering |
| TBD-04 | Specific manufacturer standards (if any) | TM |

---

## 10. Source References

| Reference | Document | Section |
|-----------|----------|---------|
| SOW | Exhibit A - Scope of Work PS.pdf | Section 3.2.4.3 (p18) |
| SOW | Exhibit A - Scope of Work PS.pdf | Section 4.1.3 (p33) |
| Decomposition | PSO Decomposition REVISED v2 | DEL-02.16, SOW-0242 |

---

*Specification generated as initial draft. All TBD items require resolution during FEED/Detailed Design phases.*
