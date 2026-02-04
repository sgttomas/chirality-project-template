# Datasheet: DEL-02.13 Piping Isometrics

## 1. Identification

| Field | Value |
|-------|-------|
| **Deliverable ID** | DEL-02.13 |
| **Deliverable Name** | Piping Isometrics |
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
| **Output Format** | Isometric drawing set - CAD (DWG) + PDF |
| **Phase Applicability** | Detailed Design (IFC) |
| **Revision Cycle** | IFR (60%) -> IFA (90%) -> IFC -> As-Built |
| **Native File Requirement** | Yes - CAD native files required per SOW-0259 |
| **Scale** | Not to Scale (NTS) - isometric projection |
| **Purpose** | Fabrication, installation, testing, NDT, PWHT, heat tracing, insulation, coating support |

### 2.1 Drawing Content Elements (per SOW-0248)

| Element | Description |
|---------|-------------|
| Piping Geometry | 3D isometric representation of pipe routing |
| Dimensions | Fabrication dimensions (cut lengths, offsets, angles, elevations) |
| Materials | Pipe size, schedule, material specification, PMC reference |
| Components | Fittings (elbows, tees, reducers), flanges, gaskets |
| Valves | Valve tags, types, orientation |
| Specialty Items | Strainers, flow elements, expansion joints |
| Welds | Weld locations with unique weld numbers, weld symbols |
| Supports | Support locations, types, and tags |
| NDT Requirements | NDE/NDT requirements per weld per LDT |
| PWHT | Post-weld heat treatment requirements where applicable |
| Hydrotesting | Test package reference, test boundaries |
| Heat Tracing | Heat tracing requirements and type |
| Insulation | Insulation type and thickness |
| Coating | Coating/painting requirements |
| BOM | Bill of materials for all components |

### 2.2 Piping Systems Covered

| System | Description | Criticality |
|--------|-------------|-------------|
| Booster Pump Suction | Suction piping for 5 VS6 pumps | High - stress critical |
| Booster Pump Discharge | Discharge piping with flow meters | High - stress critical |
| 5x6 Manifold | Manifold headers and branch connections | High - blending system |
| Tie-In Spools | Connection spools to existing systems | High - brownfield interface |
| Sump Tank Piping | Sump tank and reinjection lines | Medium |
| Auxiliary Systems | Drain, vent, utility connections | Standard |

### 2.3 Service Conditions

| Parameter | Value | Source |
|-----------|-------|--------|
| Design Flow Rate | 315,000 bpd (2,100 m3/h) peak | SOW-0002 |
| Service | Crude oil (blend components) | SOW-0005 |
| Blending Ratio | 20% Heavy to 80% Light | SOW-0005 |

## 3. Conditions

### 3.1 Input Requirements

| Input | Source | Status Required |
|-------|--------|-----------------|
| 3D CAD Model | DEL-02.28 | 90% design complete for IFC isometrics |
| Line List | DEL-02.01 | Current revision |
| Line Designation Table (LDT) | DEL-02.18 | Current revision (NDT, test requirements) |
| Valve List | DEL-02.02 | Current revision |
| Pipe Stress Analysis | DEL-02.14 | Complete for stress-critical lines |
| PMC Index | DEL-02.26 | Approved |
| GA Drawings | DEL-02.12 | IFD minimum |
| Vendor Equipment Data | Vendors | Approved/certified |
| Stress Support Loads | DEL-02.14 | Issued for support design |

### 3.2 Design Basis Conditions

| Parameter | Value | Source |
|-----------|-------|--------|
| Site Location | SW corner of Tank TK-102, Sumas Tank Farm | SOW-0003 |
| Primary Systems | 5 x VS6 booster pumps, 5x6 manifold | SOW-0003, SOW-0004 |
| Pump Configuration | 2 large, 2 small, 1 medium capacity | SOW-0004 |

### 3.3 Code Compliance

| Code/Standard | Application |
|---------------|-------------|
| CSA Z662 | Oil and gas pipeline systems - pipeline and station piping |
| ASME B31.3 | Process Piping |
| ASME B16 series | Fittings, flanges, valves |
| TMP Standards | Trans Mountain piping specifications (TBD - Attachment A08) |

## 4. Construction

### 4.1 Isometric Construction Requirements

| Aspect | Details |
|--------|---------|
| **Spool Breaks** | Logical breaks at flanges, transport limits, installation sequence |
| **Shop vs Field Welds** | Maximize shop welds; clearly identify field welds |
| **Bill of Materials** | Complete BOM on each isometric |
| **Weld Numbering** | Unique weld number system per project standard |
| **Drawing Standards** | Per TMP isometric standards (TBD) |
| **Continuation References** | Clear references between connected isometrics |

### 4.2 Fabrication Support Information

| Information | Requirement |
|-------------|-------------|
| Cut Lengths | Accurate cut-to-cut dimensions |
| Angles | Miter cut angles where applicable |
| Bend Radii | Standard or special bend requirements |
| Bevels | Weld bevel preparation requirements |
| Fit-Up | Fit-up requirements for field welds |

### 4.3 Integration Points

| Integration | Related Deliverable | Coordination |
|-------------|---------------------|--------------|
| Routing Consistency | DEL-02.12 (GA Drawings) | Isometric matches GA routing |
| Line Attributes | DEL-02.01, DEL-02.18 | Line designation, NDT, testing |
| Stress Requirements | DEL-02.14 | Support locations, critical welds |
| Support Details | DEL-02.16, DEL-02.17 | Support types and locations |
| MTO | DEL-02.19 | BOM feeds piping MTO |
| Hydrotest Boundaries | DEL-02.21 | Test package references |
| 3D Geometry | DEL-02.28 | Source geometry for extraction |

## 5. References

### 5.1 SOW References

| SOW ID | Description | Relevance |
|--------|-------------|-----------|
| SOW-0248 | Develop piping isometrics with information supporting MTO/spool fabrication/installation/pipe supports/PWHT/NDT/hydrotesting/heat tracing/insulation/coating | Primary requirement |
| SOW-0254 | Develop hydrostatic test packages (isometrics, test pressures, etc.) | Hydrotest boundary support |
| SOW-0259 | Submit editable native files for piping drawings (CAD isometrics) | Native file requirement |

### 5.2 Objective Mapping

| Objective ID | Objective | Relationship |
|--------------|-----------|--------------|
| OBJ-004 | Deliver IFD/IFC Engineering Packages | Primary deliverable contribution |
| OBJ-005 | Code/Standard Compliance | Fabrication per code requirements |
| OBJ-006 | Document Control + Turnover | Native file delivery |

### 5.3 Related Deliverables

| Deliverable ID | Name | Relationship |
|----------------|------|--------------|
| DEL-02.01 | Line List | Line identification |
| DEL-02.02 | Valve List | Valve identification |
| DEL-02.12 | GA Drawings | Routing reference |
| DEL-02.14 | Pipe Stress Analysis | Support locations, critical welds |
| DEL-02.16 | Pipe Support Standard Drawings | Support details |
| DEL-02.17 | Pipe Support Location Plans | Support positions |
| DEL-02.18 | Line Designation Table | NDT, testing requirements |
| DEL-02.19 | Piping MTO | BOM aggregation |
| DEL-02.21 | Hydrostatic Test Packages | Test boundaries |
| DEL-02.28 | 3D CAD Model | Source geometry |

### 5.4 Applicable Standards

| Standard | Description | Application |
|----------|-------------|-------------|
| TMP Standards & Specifications | Trans Mountain project standards | Primary (Attachment A08 - TBD) |
| CSA Z662 | Oil and gas pipeline systems | Pipeline code compliance |
| ASME B31.3 | Process Piping | Station piping |
| ASME B16.5, B16.9, B16.11, B16.25, B16.47 | Fittings and flanges | Component standards |
| AWS D1.1 or applicable | Welding standards | ASSUMPTION - confirm with TM |

---
*Document generated 2026-02-01 | Deliverable Status: OPEN*
