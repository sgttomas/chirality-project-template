# Datasheet: Line List

## 1. Identification

| Field | Value |
|-------|-------|
| **Deliverable ID** | DEL-02.01 |
| **Deliverable Name** | Line List |
| **Package** | PKG-02: Piping, Layout & 3D Model Engineering |
| **Discipline** | Piping |
| **Deliverable Type** | List |
| **Responsible Party** | Engineering Contractor |
| **Document Number** | **TBD** |
| **Revision** | **TBD** |

## 2. Attributes

| Attribute | Value |
|-----------|-------|
| **Format** | Excel spreadsheet (LST) |
| **Output** | Line list |
| **Phase Coverage** | FEED + Detailed Design |
| **Maintenance** | Maintained through IFC |
| **Required Columns** | Line number, size, class, service, from/to, design conditions, test requirements, insulation, heat tracing, P&ID reference |

### 2.1 Line List Data Fields (**ASSUMPTION** - based on industry standard)

| Column | Description |
|--------|-------------|
| Line Number | Unique line identifier per naming convention |
| Nominal Size | Pipe diameter (inches or mm) |
| Piping Class | Material class code per PMC index |
| Service | Fluid service description |
| From | Origin equipment/line tag |
| To | Destination equipment/line tag |
| Design Pressure | Maximum design pressure |
| Design Temperature | Maximum design temperature |
| Operating Pressure | Normal operating pressure |
| Operating Temperature | Normal operating temperature |
| Insulation Type | Insulation specification code |
| Heat Tracing | Yes/No and type if applicable |
| Test Requirement | Hydrostatic test pressure |
| P&ID Reference | Source P&ID drawing number |

## 3. Conditions

| Condition Type | Description |
|----------------|-------------|
| **Input Requirements** | P&IDs (DEL-01.03), Process Data (DEL-01.08), PMC Index (DEL-02.25) |
| **Design Basis** | SOW flow rates: 275,000 bpd sustainable, 315,000 bpd peak |
| **Operating Environment** | Sumas Tank Farm, crude oil service (Heavy/Light blend) |
| **Code Compliance** | ASME B31.3, CSA Z662 (**ASSUMPTION**) |

## 4. Construction

| Aspect | Details |
|--------|---------|
| **Line Numbering** | Per TM naming convention (**TBD** - confirm with Owner) |
| **Material Classes** | Per PMC Index (DEL-02.25) |
| **New Lines** | Associated with 5 new booster pumps, 5x6 manifold |
| **Tie-Ins** | To existing Sumas Tank Farm piping |

## 5. References

| Reference Type | Document |
|----------------|----------|
| **SOW Reference** | SOW-0117: Produce FEED line list (LST) - SOW Section 3.1.3.1 (p7) |
| **SOW Reference** | SOW-0250: Develop Process Piping Line Designation Table (LDT) - SOW Section 3.2.4.11 (p19) |
| **Source** | Puget Sound Optimization Project Decomposition |
| **Related Deliverables** | DEL-01.03 (P&IDs), DEL-02.02 (Valve List), DEL-02.03 (Tie-In List), DEL-02.18 (LDT) |
| **Standards** | ASME B31.3, CSA Z662, TM Piping Specifications (**TBD**) |
| **Owner Standards** | Trans Mountain Pipeline specifications (**TBD**) |

---
*Generated 2026-02-01 | SOW Refs: SOW-0117, SOW-0250*
