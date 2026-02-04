# Specification: Piping Specialty Items Datasheets & Specifications

**Deliverable ID:** DEL-02.20
**Package:** PKG-02 (Piping, Layout & 3D Model Engineering)
**Version:** 0.1 (Initial Draft)
**Status:** INITIALIZED
**Date:** 2026-02-01

---

## 1. Purpose

This specification defines the requirements for developing Piping Specialty Item Datasheets and Specifications for the Puget Sound Optimization Project (PSO) at Sumas Tank Farm. This includes datasheets, specifications, and the specialty item register.

---

## 2. Scope

### 2.1 Applicable Facilities
- New booster pump station (5 x VS6-type booster pumps) at SW corner of TK-102
- New 5x6 manifold system
- Associated infrastructure piping and connections

### 2.2 Specialty Item Categories

| Category | Typical Items |
|----------|---------------|
| Filtration | Strainers, filters, separators |
| Flow Control | Check valves (special types), flow elements |
| Pressure Protection | Relief valves, rupture discs, vacuum breakers |
| Expansion | Expansion joints, flexible connectors |
| Safety | Flame arrestors, detonation arrestors |
| Pigging | Pig launchers, receivers, traps |
| Visual | Sight glasses, level gauges |
| Miscellaneous | Special fittings, spectacle blinds, sample connections |

---

## 3. Normative References

### 3.1 Codes and Standards (Mandatory)

| Code/Standard | Title | Application |
|---------------|-------|-------------|
| CSA Z662 | Oil and Gas Pipeline Systems | Primary code per SOW |
| ASME B31.4 | Pipeline Transportation Systems | Supplemental code |
| API 6D | Pipeline and Piping Valves | Valve specialty items |
| API 594 | Check Valves | Check valve requirements |
| API 2000 | Venting Atmospheric and Low-Pressure Storage Tanks | Relief devices |
| ASME Section VIII | Pressure Vessels | Filter/strainer vessels |
| EJMA | Standards of the Expansion Joint Manufacturers Association | Expansion joints |

### 3.2 Project References

| Reference | Description |
|-----------|-------------|
| TM Standards and Specifications | Per SOW Section 4.1.2 |
| Design Basis Memorandum | DEL-01.01 |
| Process & Instrumentation Diagrams | DEL-01.03 |
| Piping Material Class Index | DEL-02.25 |
| Valve List | DEL-02.02 |

---

## 4. Technical Requirements

### 4.1 General Requirements

4.1.1 Each specialty item identified on P&IDs or required for the project shall have a datasheet.

4.1.2 Datasheets shall contain sufficient technical information for procurement and fabrication.

4.1.3 All datasheets shall reference applicable codes and standards.

4.1.4 A specialty item register shall be maintained listing all items and datasheet references.

4.1.5 Manufacturer certified drawings shall be reviewed and endorsed as required.

### 4.2 Datasheet Content Requirements

Each datasheet shall include, as applicable:

| Section | Content |
|---------|---------|
| General | Tag number, service description, P&ID reference |
| Design Conditions | Pressure, temperature, flow rate |
| Materials | Body, trim, seals, internals |
| Dimensions | Size, ratings, connections |
| Performance | Capacity, Cv, pressure drop |
| Accessories | Indicators, operators, actuators |
| Testing | Hydro test, leak test, performance test |
| Notes | Special requirements, deviations |

### 4.3 Category-Specific Requirements

#### 4.3.1 Strainers

| Parameter | Requirement |
|-----------|-------------|
| Type | Y-strainer, basket, duplex, automatic |
| Mesh Size | Micron rating per process requirements |
| Materials | Body and screen materials per PMC |
| Blowdown | Blowdown connection if required |
| Differential Pressure | Maximum clean and dirty DP |

#### 4.3.2 Check Valves (Specialty Types)

| Parameter | Requirement |
|-----------|-------------|
| Type | Wafer, tilting disc, piston, nozzle |
| Cracking Pressure | Minimum pressure to open |
| Slam Characteristics | Soft closure if required |
| Materials | Body and internals per PMC |

#### 4.3.3 Relief Valves

| Parameter | Requirement |
|-----------|-------------|
| Set Pressure | Per relief study calculations |
| Capacity | Flow rate at relieving conditions |
| Materials | Per fluid and temperature |
| Certification | ASME/NB certification |
| Testing | Test requirements and frequency |

#### 4.3.4 Expansion Joints

| Parameter | Requirement |
|-----------|-------------|
| Type | Bellows, slip, universal |
| Movements | Axial, lateral, angular |
| Cycles | Fatigue life requirements |
| Materials | Bellows material and liners |
| Accessories | Limit rods, covers |

#### 4.3.5 Flame Arrestors

| Parameter | Requirement |
|-----------|-------------|
| Type | In-line, end-of-line, detonation |
| Gas Group | IIA, IIB, IIC classification |
| Certification | ATEX, FM, CSA as required |
| Maintenance | Cleaning requirements |

### 4.4 Material Requirements

4.4.1 Materials shall be specified per Piping Material Class (DEL-02.25).

4.4.2 Material specifications shall include:
- ASTM/API material designation
- Grade and heat treatment
- Pressure-temperature rating

4.4.3 Special materials shall be specified for:
- Corrosive services
- High or low temperature services
- Sour service (H2S) if applicable

### 4.5 Design Documentation

4.5.1 Design basis for specialty items shall be documented.

4.5.2 Sizing calculations shall be maintained in project files.

4.5.3 Selection rationale shall be documented for non-standard items.

---

## 5. Specialty Item Register

### 5.1 Register Content

| Field | Description |
|-------|-------------|
| Tag Number | Unique identifier |
| Description | Item type and service |
| P&ID Reference | Associated P&ID sheet |
| Datasheet Number | Datasheet document reference |
| Size / Rating | Nominal size and pressure class |
| Vendor | Manufacturer (if specified) |
| Requisition | MR/PO reference (when issued) |
| Status | Development status |

### 5.2 Register Format

| Requirement | Specification |
|-------------|---------------|
| File Format | Microsoft Excel (.xlsx) |
| Organization | By item type or tag number |
| Filters | Enabled for all columns |
| Status Tracking | Current development phase |

---

## 6. Manufacturer Drawing Review

### 6.1 Review Scope

| Drawing Type | Review Required |
|--------------|-----------------|
| Certified Drawings | Yes - all vendor equipment |
| Assembly Drawings | Yes - if provided |
| Installation Drawings | Yes - if provided |
| Spare Parts Lists | Yes - for maintenance planning |

### 6.2 Review Process

6.2.1 Receive manufacturer drawings with vendor data package.

6.2.2 Review for compliance with datasheet requirements.

6.2.3 Mark up any discrepancies or comments.

6.2.4 Endorse or reject with comments.

6.2.5 Return to vendor/procurement with response.

6.2.6 Verify resubmissions address comments.

### 6.3 Endorsement Status

| Status | Meaning |
|--------|---------|
| Code 1 | Approved - no comments |
| Code 2 | Approved with comments - no resubmission required |
| Code 3 | Revise and resubmit |
| Code 4 | Rejected - does not meet requirements |

---

## 7. Quality Assurance

### 7.1 Design Verification

- Datasheets checked per Deliverable Review & Verification Plan (DEL-00.03)
- Design conditions verified against DBM
- Material specifications verified against PMC

### 7.2 Completeness Verification

- All specialty items on P&IDs have datasheets
- All datasheet fields completed or marked N/A
- Register is complete and current

### 7.3 Code Compliance

- Datasheets reference applicable codes
- Deviations documented and approved

---

## 8. Deliverables

| Item | Format | Quantity |
|------|--------|----------|
| Specialty Item Datasheets | PDF + Native | Per item count |
| Specialty Item Register | Excel | 1 |
| Manufacturer Drawing Reviews | PDF markups | Per vendor submission |
| Transmittal | Per TM requirements | Per submission |

---

## 9. TBD Items

| Item | Description | Owner |
|------|-------------|-------|
| TBD-01 | TM datasheet templates | TM Piping Lead |
| TBD-02 | Complete specialty item list | Process / P&ID development |
| TBD-03 | Manufacturer approval list | TM Procurement |
| TBD-04 | Vendor drawing review turnaround time | TM |

---

## 10. Source References

| Reference | Document | Section |
|-----------|----------|---------|
| SOW | Exhibit A - Scope of Work PS.pdf | Section 3.1.3.1 (p7) |
| SOW | Exhibit A - Scope of Work PS.pdf | Section 3.2.4.17 (p20) |
| SOW | Exhibit A - Scope of Work PS.pdf | Section 3.2.4.25 (p21) |
| Decomposition | PSO Decomposition REVISED v2 | DEL-02.20, SOW-0119, SOW-0256, SOW-0260 |

---

*Specification generated as initial draft. All TBD items require resolution during FEED/Detailed Design phases.*
