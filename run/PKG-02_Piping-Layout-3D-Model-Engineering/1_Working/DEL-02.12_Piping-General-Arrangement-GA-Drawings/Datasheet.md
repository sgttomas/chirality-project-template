# Datasheet: DEL-02.12 Piping General Arrangement (GA) Drawings

## 1. Identification

| Field | Value |
|-------|-------|
| **Deliverable ID** | DEL-02.12 |
| **Deliverable Name** | Piping General Arrangement (GA) Drawings |
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
| **Output Format** | GA drawing set - CAD (DWG) + PDF |
| **Phase Applicability** | FEED through Detailed Design (IFC) |
| **Revision Cycle** | IFR -> IFD -> IFC -> As-Built |
| **Native File Requirement** | Yes - CAD native files required per SOW-0259 |
| **Scale** | TBD - Typical 1:50 or 1:100 for plan views |
| **Views** | Plans, elevations, sections as required for clarity |

### 2.1 Drawing Content Elements

| Element | Description |
|---------|-------------|
| Above-Ground Piping | All process and utility piping routes with line numbers |
| Below-Ground Piping | Buried piping with depth annotations, CP points |
| Equipment Connections | Nozzle orientations, flange faces, connection details |
| Instrument Locations | In-line instruments, control valves, flow meters |
| Valve Locations | All valves with tag numbers and handwheel positions |
| Road Crossings | Pipe crossing details with elevations |
| Pipe Bridges | Elevated pipe rack/bridge configurations |
| CP Connection Points | Cathodic protection test stations, ground anodes |
| Pipe Supports | General support locations (detail in DEL-02.17) |
| Dimensional References | Key dimensions from site grid/benchmarks |

### 2.2 Piping Systems Covered (per SOW-0003, SOW-0004)

| System | Description |
|--------|-------------|
| Booster Pump Suction | Suction piping from tank manifolds to 5 VS6 pumps |
| Booster Pump Discharge | Discharge piping including flow meters per SOW-0005 |
| 5x6 Manifold | Manifold headers and branch connections |
| Tie-In Piping | Connections to existing Sumas Tank Farm systems |
| Auxiliary Systems | Drain, vent, utility connections, sump piping |

### 2.3 Flow Design Parameters

| Parameter | Value | Source |
|-----------|-------|--------|
| Sustainable Flow Rate | 275,000 bpd (1,822 m3/h) | SOW-0002 |
| Design (Peak) Flow Rate | 315,000 bpd (2,100 m3/h) | SOW-0002 |
| Blending Ratio | 20% Heavy to 80% Light | SOW-0005 |
| Component Range | 10%-100% NEAT (TBD confirmation) | DBM reference |

## 3. Conditions

### 3.1 Input Requirements

| Input | Source | Status Required |
|-------|--------|-----------------|
| P&IDs | DEL-01.03 | IFR minimum for FEED; IFD for DD |
| Line List | DEL-02.01 | Current revision |
| Valve List | DEL-02.02 | Current revision |
| Equipment Layout Plans | DEL-02.10 | IFR minimum |
| 3D CAD Model | DEL-02.28 | 30% for FEED; 60%+ for DD |
| Vendor Equipment Data | Vendors | Approved/certified |
| Site Survey Data | Existing TM records | Verified current |
| Hydraulic Analysis | DEL-01.07 | For line sizing verification |

### 3.2 Design Basis Conditions

| Parameter | Value | Source |
|-----------|-------|--------|
| Site Location | SW corner of Tank TK-102, Sumas Tank Farm | SOW-0003 |
| Primary Systems | 5 x VS6 booster pumps, 5x6 manifold, containment | SOW-0003 |
| Pump Configuration | 2 large, 2 small, 1 medium capacity | SOW-0004 |
| VFD Requirement | Each pump with VFD and discharge flow meter | SOW-0005 |

### 3.3 Code Compliance

| Code/Standard | Application |
|---------------|-------------|
| CSA Z662 | Oil and gas pipeline systems - primary governing code |
| ASME B31.3 | Process Piping - station piping |
| TMP Standards | Trans Mountain standards per Attachment A08 (TBD) |
| Title 49 PHMSA Part 195 | US pipeline safety (if applicable) |

## 4. Construction

### 4.1 Drawing Construction Requirements

| Aspect | Details |
|--------|---------|
| **Coordinate System** | Site coordinate grid aligned with TM survey datum (TBD) |
| **Drawing Standards** | TMP CAD standards per Attachment A08 (TBD) |
| **Title Block** | Per TMP drawing template |
| **Layer Structure** | Per TMP CAD layer naming conventions (TBD) |
| **View Organization** | Plan views by area/elevation; sections for equipment connections |
| **Match Lines** | Consistent with adjacent drawings (DEL-02.04, DEL-02.05) |

### 4.2 Integration Points

| Integration | Related Deliverable | Coordination |
|-------------|---------------------|--------------|
| Process Definition | DEL-01.03 (P&IDs) | All piping consistent with P&ID |
| Line Attributes | DEL-02.01 (Line List) | Line numbers, sizes, specs |
| Valve Details | DEL-02.02 (Valve List) | Valve tags, types |
| Key Plan Context | DEL-02.04 (Key Plan) | Match lines, references |
| Site Context | DEL-02.05 (Site Plan) | Site orientation |
| Equipment Positions | DEL-02.10 (Equipment Layout) | Nozzle locations |
| Fabrication Details | DEL-02.13 (Isometrics) | Consistent routing |
| Support Locations | DEL-02.17 (Support Plans) | Support positions |
| 3D Geometry | DEL-02.28 (3D Model) | Source geometry |

## 5. References

### 5.1 SOW References

| SOW ID | Description | Relevance |
|--------|-------------|-----------|
| SOW-0122 | Produce FEED piping key plan (GA) | FEED GA development |
| SOW-0123 | Produce FEED piping site plan (GA) | FEED site plan |
| SOW-0124 | Produce FEED demolition piping site plan (GA) | Demolition planning |
| SOW-0245 | Verify vendor-supplied piping design for purchased equipment | Vendor coordination |
| SOW-0247 | Update/finalize site-specific drawings (GA drawings) | IFC development |
| SOW-0252 | Develop piping GA drawings depicting above/below ground piping, equipment connections, instrument/nozzle locations, road crossings/pipe bridges, CP points | Primary requirement |
| SOW-0261 | Review preliminary piping deliverable references | Deliverable confirmation |

### 5.2 Objective Mapping

| Objective ID | Objective | Relationship |
|--------------|-----------|--------------|
| OBJ-004 | Deliver IFD/IFC Engineering Packages | Primary deliverable contribution |
| OBJ-005 | Code/Standard Compliance | Piping routing per code requirements |
| OBJ-008 | Constructability + Interface Management | Installation planning support |

### 5.3 Related Deliverables

| Deliverable ID | Name | Relationship |
|----------------|------|--------------|
| DEL-01.03 | P&IDs | Process definition source |
| DEL-02.01 | Line List | Line attribute source |
| DEL-02.02 | Valve List | Valve identification |
| DEL-02.04 | Piping Key Plan | Overview/index |
| DEL-02.05 | Piping Site Plan | Site context |
| DEL-02.06 | Demolition Site Plan | Removal scope |
| DEL-02.10 | Equipment Layout Plans | Equipment positions |
| DEL-02.13 | Piping Isometrics | Fabrication details |
| DEL-02.17 | Pipe Support Location Plans | Support details |
| DEL-02.28 | 3D CAD Model | Source geometry |

### 5.4 Applicable Standards

| Standard | Description | Application |
|----------|-------------|-------------|
| TMP Standards & Specifications | Trans Mountain project standards | Primary (Attachment A08 - TBD) |
| CSA Z662 | Oil and gas pipeline systems | Pipeline code compliance |
| ASME B31.3 | Process Piping | Station piping |
| ASME Y14.1 | Drawing sheet size and format | ASSUMPTION - Drawing format |

---
*Document generated 2026-02-01 | Deliverable Status: OPEN*
