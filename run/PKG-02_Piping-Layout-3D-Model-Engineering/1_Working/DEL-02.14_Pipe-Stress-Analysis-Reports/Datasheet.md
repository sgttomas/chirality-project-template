# Datasheet: DEL-02.14 Pipe Stress Analysis Report(s)

## 1. Identification

| Field | Value |
|-------|-------|
| **Deliverable ID** | DEL-02.14 |
| **Deliverable Name** | Pipe Stress Analysis Report(s) |
| **Package** | PKG-02 (Piping, Layout & 3D Model Engineering) |
| **Discipline** | Piping / Stress |
| **Document Type** | Report |
| **Responsible Party** | Engineering Contractor |
| **Document Number** | TBD - Per Document & Tag Numbering Instruction Plan (DEL-00.02) |
| **Revision** | TBD |
| **Status** | OPEN |

## 2. Attributes

| Attribute | Value |
|-----------|-------|
| **Output Format** | Stress analysis reports (PDF) + Native model files |
| **Phase Applicability** | Detailed Design (IFC) |
| **Revision Cycle** | Preliminary -> IFR -> IFC -> As-Built (if required) |
| **Native File Requirement** | Yes - Stress model files required per SOW-0259 |
| **Software** | TBD - Industry standard stress analysis software (e.g., CAESAR II, AutoPIPE) |

### 2.1 Report Content Elements

| Element | Description |
|---------|-------------|
| Executive Summary | Summary of analysis scope, key findings, and conclusions |
| Analysis Basis | Design codes, load cases, material properties, operating conditions |
| Piping Isometric/Sketch | Schematic representation of analyzed system |
| Stress Results | Sustained, displacement, occasional stress results vs allowables |
| Support Loads | Calculated loads at each support location |
| Equipment Nozzle Loads | Loads at equipment nozzle connections |
| Expansion Loops/Flexibility | Details of flexibility provisions |
| Code Compliance Summary | Pass/fail summary for all code checks |
| Appendices | Detailed output, input summaries, calculation sheets |

### 2.2 Piping Systems Requiring Analysis

| System | Criticality | Analysis Type |
|--------|-------------|---------------|
| Booster Pump Suction | High - pump nozzle loads | Full flexibility + nozzle load check |
| Booster Pump Discharge | High - high pressure, pump nozzle | Full flexibility + nozzle load check |
| 5x6 Manifold | High - multiple branches, thermal | Full flexibility analysis |
| Tie-In Piping | High - existing system impact | Flexibility + existing system verification |
| Large Diameter Headers | Medium - NPS 12 and above | Full flexibility analysis |
| Sump Tank Piping | Medium | Simplified or full as required |

### 2.3 Operating Conditions

| Parameter | Value | Source |
|-----------|-------|--------|
| Design Flow Rate | 315,000 bpd (2,100 m3/h) peak | SOW-0002 |
| Operating Temperature Range | TBD - per process data | Process discipline |
| Design Pressure | TBD - per P&IDs | DEL-01.03 |
| Ambient Temperature Range | TBD - site conditions | Site data |

## 3. Conditions

### 3.1 Input Requirements

| Input | Source | Status Required |
|-------|--------|-----------------|
| 3D CAD Model | DEL-02.28 | Design-complete for stress-critical lines |
| Line List | DEL-02.01 | Current revision |
| Line Designation Table (LDT) | DEL-02.18 | Current revision |
| P&IDs | DEL-01.03 | IFD minimum |
| Equipment Datasheets | PKG-03 | Approved |
| Vendor Allowable Nozzle Loads | Vendors | Approved/certified |
| Piping Material Specifications | DEL-02.26 | Approved |
| Site Ambient Data | Site records | Available |
| Support & Pipe Stress Execution Plan | DEL-02.15 | Approved |

### 3.2 Design Basis Conditions

| Parameter | Value | Source |
|-----------|-------|--------|
| Site Location | SW corner of Tank TK-102, Sumas Tank Farm | SOW-0003 |
| Pump Configuration | 5 x VS6 (2 large, 2 small, 1 medium) | SOW-0004 |
| Existing Systems | Adjacent piping at TK-102 requiring verification | SOW-0240 |

### 3.3 Code Compliance Requirements

| Code/Standard | Application |
|---------------|-------------|
| CSA Z662 | Oil and gas pipeline systems - stress provisions |
| ASME B31.3 | Process Piping - station piping stress requirements |
| API 610 | Pump nozzle load limits |
| Vendor Specifications | Equipment-specific allowable loads |
| TMP Standards | Trans Mountain stress analysis standards (TBD) |

## 4. Construction

### 4.1 Report Construction Requirements

| Aspect | Details |
|--------|---------|
| **Report Format** | Per TMP report standards (TBD) |
| **Model Documentation** | Analysis model description, node diagrams |
| **Load Cases** | Sustained, expansion, occasional per code |
| **Results Presentation** | Tabular and graphical stress summaries |
| **Support Schedule** | Type, location, load for each support |
| **Nozzle Load Summary** | Compared to vendor allowables |

### 4.2 Analysis Scope per SOW-0240

| Requirement | Details |
|-------------|---------|
| Critical Piping Systems | All critical piping systems per execution plan criteria |
| Adjacent Existing Piping | Verify existing piping/equipment compliance under revised conditions |
| CSA Code Provisions | Verify compliance with CSA Z662 provisions |
| Support Design Input | Provide loads for support design (DEL-02.16, DEL-02.17) |

### 4.3 Integration Points

| Integration | Related Deliverable | Coordination |
|-------------|---------------------|--------------|
| Piping Routing | DEL-02.12 (GA), DEL-02.13 (Isometrics) | Routing input |
| Support Design | DEL-02.16, DEL-02.17 | Support loads and locations |
| Equipment Interface | PKG-03 | Nozzle load verification |
| Process Conditions | DEL-01.09 (Process Datasheets) | Operating conditions |
| Execution Plan | DEL-02.15 | Analysis methodology |

## 5. References

### 5.1 SOW References

| SOW ID | Description | Relevance |
|--------|-------------|-----------|
| SOW-0240 | Develop piping stress analysis reports for all critical piping systems and verify adjacent pre-existing piping/equipment compliance with CSA code provisions under revised conditions | Primary requirement |
| SOW-0241 | Develop and submit a Support and Pipe Stress Execution Plan | Execution plan requirement |
| SOW-0259 | Submit editable native files for piping calculations (stress files) plus reports and PDFs | Native file requirement |

### 5.2 Objective Mapping

| Objective ID | Objective | Relationship |
|--------------|-----------|--------------|
| OBJ-004 | Deliver IFD/IFC Engineering Packages | Primary deliverable |
| OBJ-005 | Code/Standard Compliance | CSA Z662 / ASME B31.3 compliance verification |
| OBJ-006 | Document Control + Turnover | Native file delivery |

### 5.3 Related Deliverables

| Deliverable ID | Name | Relationship |
|----------------|------|--------------|
| DEL-02.01 | Line List | Line identification |
| DEL-02.12 | GA Drawings | Routing reference |
| DEL-02.13 | Piping Isometrics | Detailed routing, support locations |
| DEL-02.15 | Support & Pipe Stress Execution Plan | Analysis methodology |
| DEL-02.16 | Pipe Support Standard Drawings | Support design output |
| DEL-02.17 | Pipe Support Location Plans | Support locations |
| DEL-02.18 | Line Designation Table | Line attributes |
| DEL-02.28 | 3D CAD Model | Geometry source |

### 5.4 Applicable Standards

| Standard | Description | Application |
|----------|-------------|-------------|
| TMP Standards & Specifications | Trans Mountain project standards | Primary (Attachment A08 - TBD) |
| CSA Z662 | Oil and gas pipeline systems | Primary stress code |
| ASME B31.3 | Process Piping | Station piping stress |
| ASME B31.4 | Pipeline Transportation Systems | If applicable |
| API 610 | Centrifugal Pumps | Pump nozzle allowables |
| API 617 | Centrifugal Compressors | If applicable |

---
*Document generated 2026-02-01 | Deliverable Status: OPEN*
