# Specification: Pipe Support Location Plans

**Deliverable ID:** DEL-02.17
**Package:** PKG-02 (Piping, Layout & 3D Model Engineering)
**Version:** 0.1 (Initial Draft)
**Status:** INITIALIZED
**Date:** 2026-02-01

---

## 1. Purpose

This specification defines the requirements for developing Pipe Support Location Plans for the Puget Sound Optimization Project (PSO) at Sumas Tank Farm. These plans shall show the placement and specification of all pipe supports within the project scope.

---

## 2. Scope

### 2.1 Applicable Facilities
- New booster pump station (5 x VS6-type booster pumps) at SW corner of TK-102
- New 5x6 manifold system
- Associated infrastructure piping and connections
- Containment wall area piping

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
| TM Standards | Trans Mountain Pipeline Standards | Per SOW Section 4.1.2 |

### 3.2 Project References

| Reference | Description |
|-----------|-------------|
| DEL-02.16 | Pipe Support Standard Drawings |
| DEL-02.14 | Pipe Stress Analysis Report(s) |
| DEL-02.15 | Support & Pipe Stress Execution Plan |
| DEL-02.12 | Piping General Arrangement Drawings |
| DEL-02.13 | Piping Isometrics |
| DEL-02.28 | Sitewide 3D Model |

---

## 4. Technical Requirements

### 4.1 General Requirements

4.1.1 Location plans shall show all pipe supports within the PSO scope boundaries.

4.1.2 Each support shall be uniquely identified with a support mark number.

4.1.3 Plans shall be developed based on the sitewide 3D model (DEL-02.28).

4.1.4 Plans shall be coordinated with piping GA drawings (DEL-02.12) for base plan consistency.

### 4.2 Content Requirements

Each location plan shall include:

| Element | Requirement |
|---------|-------------|
| Base plan | Piping and structural steel layout |
| Support symbols | Standard symbols per legend |
| Support marks | Unique identifier for each support |
| Standard drawing reference | Callout to DEL-02.16 drawings |
| Coordinates | North/East coordinates or grid reference |
| Elevation callout | Elevation of support attachment |
| Line identification | Line number for supported pipe |
| Legend | Symbol definitions and abbreviations |
| North arrow | Orientation reference |
| Match lines | References to adjacent sheets |

### 4.3 Support Identification

**4.3.1 Support Mark Numbering**

Support marks shall follow format: [Area]-[Type]-[Number]

Example: BPS-SH-001 (Booster Pump Station - Shoe - 001)

(ASSUMPTION - numbering format to be confirmed per TM standards)

**4.3.2 Area Designators (ASSUMPTION)**

| Designator | Area |
|------------|------|
| BPS | Booster Pump Station |
| MAN | Manifold Area |
| YRD | Yard Piping |
| CNT | Containment Area |

### 4.4 Callout Requirements

Each support location callout shall include:

| Element | Example |
|---------|---------|
| Support mark | BPS-SH-001 |
| Standard drawing reference | STD-PS-001 |
| Line number | 12"-CR-1001-A1A |
| Elevation | EL. 100.500 |
| Special notes | (if applicable) |

### 4.5 Scale and Presentation

| Requirement | Specification |
|-------------|---------------|
| Primary scale | 1:50 or 1:100 (based on area size) |
| Detail views | 1:20 or 1:25 for congested areas |
| Clarity | Support locations clearly visible |
| Overcrowding | Use enlarged details or separate sheets |

### 4.6 Coordinate System

4.6.1 Plans shall use the project coordinate system (TBD - per survey/civil deliverables).

4.6.2 Grid references shall match structural and civil drawings.

4.6.3 Elevations shall reference project datum.

---

## 5. Drawing Format and Presentation

### 5.1 Drawing Standards

| Requirement | Specification |
|-------------|---------------|
| CAD Software | AutoCAD or equivalent per TM standards |
| Drawing Size | TBD (per TM requirements) |
| Title Block | TM standard title block format |
| Numbering | Per TM document numbering system |

### 5.2 Layer Organization

| Layer | Content |
|-------|---------|
| Piping | Piping centerlines and outlines |
| Steel | Structural steel outlines |
| Supports | Support symbols and marks |
| Text | Callouts, dimensions, notes |
| Grid | Coordinate grid |

### 5.3 Symbology

Standard symbols shall be used for:
- Rest supports (shoes)
- Guides (single and double acting)
- Anchors/Line stops
- Hangers (rigid, spring, constant)
- Trunnions
- Special supports

(Symbol legend to be developed per TM standards)

### 5.4 Revision Control

5.4.1 Drawings shall be developed through: IFR -> IFD -> IFC.

5.4.2 Revision clouds and triangles per TM standards.

5.4.3 Revision history maintained on title block.

---

## 6. Interface Requirements

### 6.1 3D Model Interface
- Support locations extracted from 3D model
- Coordinates verified against model
- Location plans synchronized with model updates

### 6.2 Stress Analysis Interface
- Support locations per stress analysis requirements
- Any location changes coordinated with stress engineer

### 6.3 Structural Interface
- Attachment points coordinated with structural drawings
- Support loads communicated to structural engineering

### 6.4 Isometric Interface
- Support marks consistent between location plans and isometrics
- Standard drawing references matched

---

## 7. Quality Assurance

### 7.1 Design Verification
- All supports in stress model represented on plans
- Coordinates verified against 3D model
- Callout information complete

### 7.2 Coordination Check
- Cross-checked with structural steel drawings
- Verified against piping GA drawings
- Isometric support callouts matched

### 7.3 Constructability Review
- Access for installation verified
- Installation sequence considered
- No conflicts with other disciplines

---

## 8. Deliverables

| Item | Format | Quantity |
|------|--------|----------|
| Support Location Plans | Native CAD + PDF | TBD (5-10 sheets estimated) |
| Support Schedule | Excel | 1 (listing all supports) |
| Drawing Transmittal | Per TM requirements | Per submission |

---

## 9. TBD Items

| Item | Description | Owner |
|------|-------------|-------|
| TBD-01 | TM CAD standards and symbology | TM Document Control |
| TBD-02 | Support numbering convention | TM Piping Lead |
| TBD-03 | Project coordinate system | Survey / Civil |
| TBD-04 | Drawing scale preferences | TM |

---

## 10. Source References

| Reference | Document | Section |
|-----------|----------|---------|
| SOW | Exhibit A - Scope of Work PS.pdf | Section 3.2.4.3 (p18) |
| Decomposition | PSO Decomposition REVISED v2 | DEL-02.17, SOW-0242 |

---

*Specification generated as initial draft. All TBD items require resolution during FEED/Detailed Design phases.*
