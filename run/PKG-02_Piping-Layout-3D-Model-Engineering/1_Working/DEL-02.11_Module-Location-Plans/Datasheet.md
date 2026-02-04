# Datasheet: DEL-02.11 Module Location Plans

## 1. Identification

| Field | Value |
|-------|-------|
| **Deliverable ID** | DEL-02.11 |
| **Deliverable Name** | Module Location Plans |
| **Package** | PKG-02 (Piping, Layout & 3D Model Engineering) |
| **Discipline** | Piping |
| **Document Type** | Drawing |
| **Responsible Party** | Engineering Contractor |
| **Document Number** | TBD - Per Document & Tag Numbering Instruction Plan (DEL-00.02) |
| **Revision** | TBD |
| **Status** | OPEN |

## 2. Attributes

| Attribute | Value |
|-----------|-------|
| **Output Format** | Module location plan drawing(s) - CAD (DWG) + PDF |
| **Phase Applicability** | FEED through Detailed Design (IFC) |
| **Revision Cycle** | IFR -> IFD -> IFC -> As-Built |
| **Native File Requirement** | Yes - CAD native files required per SOW-0259 |
| **Conditional Applicability** | If applicable (per modularization strategy) |
| **Coordinate System** | TBD - Aligned with project 3D model and site survey datum |
| **Scale** | TBD - Typical 1:100 or 1:200 for site-level plans |

### 2.1 Drawing Content Elements

| Element | Description |
|---------|-------------|
| Module Tag Numbers | Unique identifier for each module/prefab unit per DEL-02.27 |
| Module Footprints | Boundary outlines with overall dimensions (L x W) |
| Orientation | North arrow and rotation reference to site grid |
| Elevation | Finished floor/base elevation references |
| Grid References | Coordinate tie-in to structural/site grid system |
| Access Requirements | Maintenance and installation access clearances |
| Lifting Points | Rigging/lifting point locations (if applicable) |
| Interface Points | Pipe, electrical, I&C connection locations to adjacent systems |
| Match Lines | References to adjacent area/plot plan drawings |

### 2.2 Anticipated Module Types (ASSUMPTION)

| Module Type | Description | Basis |
|-------------|-------------|-------|
| Booster Pump Skids | Prefabricated VS6 pump assemblies (2 large, 2 small, 1 medium) | SOW-0003, SOW-0004 |
| Manifold Assembly | 5x6 manifold pre-assembly (if modularized) | SOW-0003 |
| VFD Building/Enclosure | Variable frequency drive housing modules | SOW-0005 |
| Piping Spools | Pre-fabricated piping assemblies | SOW-0257 |

## 3. Conditions

### 3.1 Applicability Conditions
- Module location plans are produced if modularization strategies are adopted per SOW-0145, SOW-0257, SOW-0291
- Plans are required when prefabricated modules/components are designed for the booster pump station and manifold facilities
- ASSUMPTION: Modularization applicability to be confirmed during constructability assessment

### 3.2 Input Requirements

| Input | Source | Status Required |
|-------|--------|-----------------|
| Module/Prefabrication List | DEL-02.27 | Draft minimum |
| 3D CAD Model | DEL-02.28 | Current extraction with module boundaries |
| Overall Plot Plan | DEL-02.08 | IFR minimum |
| Equipment Layout Plans | DEL-02.10 | IFR minimum |
| Area Plans | DEL-02.09 | IFR minimum |
| Foundation Plans | PKG-04 deliverables | Preliminary coordinated |
| Site Survey Data | Existing TM records | Verified current |

### 3.3 Design Basis Conditions

| Parameter | Value | Source |
|-----------|-------|--------|
| Site Location | SW corner of Tank TK-102, Sumas Tank Farm | SOW-0003 |
| Primary Systems | 5 x VS6 booster pumps, 5x6 manifold, containment wall | SOW-0003, SOW-0004 |
| Pump Configuration | 2 large-capacity, 2 small-capacity, 1 medium-capacity | SOW-0004 |
| Sustainable Flow Rate | 275,000 bpd (1,822 m3/h) | SOW-0002 |
| Design (Peak) Flow Rate | 315,000 bpd (2,100 m3/h) | SOW-0002 |

## 4. Construction

### 4.1 Drawing Construction Requirements

| Aspect | Details |
|--------|---------|
| **Coordinate System** | Site coordinate grid aligned with TM survey datum (TBD) |
| **Drawing Standards** | TMP CAD standards per Attachment A08 (TBD) |
| **Title Block** | Per TMP drawing template |
| **Layer Structure** | Per TMP CAD layer naming conventions (TBD) |
| **Symbology** | Per TMP symbol library |
| **Revision Control** | Revision clouds for changes; history in title block |

### 4.2 Integration Points

| Integration | Related Deliverable | Coordination |
|-------------|---------------------|--------------|
| Site Context | DEL-02.08 (Overall Plot Plan) | Module positions referenced to site grid |
| Area Context | DEL-02.09 (Area Plans) | Consistent area boundaries and references |
| Equipment Detail | DEL-02.10 (Equipment Layout Plans) | Equipment positions within modules |
| Piping Routing | DEL-02.12 (GA Drawings) | Interface locations for piping |
| Module Inventory | DEL-02.27 (Module/Prefabrication List) | Module tags and attributes |
| 3D Geometry | DEL-02.28 (3D CAD Model) | Source geometry for module footprints |
| Foundations | PKG-04 (Civil/Structural) | Foundation anchor points and elevations |

## 5. References

### 5.1 SOW References

| SOW ID | Description | Relevance |
|--------|-------------|-----------|
| SOW-0145 | Develop preliminary construction/installation plans and concepts, including modularization strategies | FEED modularization basis |
| SOW-0247 | Update/finalize site-specific drawings (area/key/equipment layout/module location/plot plan/GA drawings) | Primary IFC requirement |
| SOW-0257 | Develop a module/prefabrication list for prefabricated components/modules | Module list input reference |
| SOW-0259 | Submit editable native files for piping calculations/documents/drawings | Native file submission requirement |
| SOW-0291 | Develop construction and installation plans and concepts, including modularization strategies | Detailed design modularization |

### 5.2 Objective Mapping

| Objective ID | Objective | Relationship |
|--------------|-----------|--------------|
| OBJ-004 | Deliver IFD/IFC Engineering Packages | Primary deliverable contribution |
| OBJ-008 | Constructability + Interface Management | Module installation planning support |

### 5.3 Related Deliverables

| Deliverable ID | Relationship |
|----------------|--------------|
| DEL-02.08 | Overall Plot Plan - site context |
| DEL-02.09 | Area Plans - area context |
| DEL-02.10 | Equipment Layout Plans - equipment detail |
| DEL-02.12 | GA Drawings - piping context |
| DEL-02.27 | Module/Prefabrication List - module inventory |
| DEL-02.28 | 3D CAD Model - source geometry |
| DEL-00.01 | MDR - document registration |
| DEL-00.02 | Numbering Plan - drawing number assignment |

### 5.4 Applicable Standards

| Standard | Description | Application |
|----------|-------------|-------------|
| TMP Standards & Specifications | Trans Mountain project standards (Attachment A08) | Primary governing standard (TBD) |
| CSA Z662 | Oil and gas pipeline systems | General compliance |
| ASME Y14.1 | Drawing sheet size and format | ASSUMPTION - Drawing format |
| ASME Y14.100 | Engineering Drawing Practices | ASSUMPTION - Drawing practices |

---
*Document generated 2026-02-01 | Deliverable Status: OPEN*
