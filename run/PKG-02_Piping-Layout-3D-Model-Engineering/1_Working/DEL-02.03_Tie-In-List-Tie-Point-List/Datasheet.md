# Datasheet: Tie-In List / Tie Point List

## 1. Identification

| Field | Value |
|-------|-------|
| **Deliverable ID** | DEL-02.03 |
| **Deliverable Name** | Tie-In List / Tie Point List |
| **Package** | PKG-02: Piping, Layout & 3D Model Engineering |
| **Discipline** | Piping |
| **Deliverable Type** | List |
| **Responsible Party** | Engineering Contractor |
| **Document Number** | **TBD** |
| **Revision** | **TBD** |

## 2. Attributes

| Attribute | Value |
|-----------|-------|
| **Format** | Excel spreadsheet (TIL) |
| **Output** | Tie-in list/table |
| **Phase Coverage** | FEED + Detailed Design |
| **Maintenance** | Maintained through IFC |

### 2.1 Tie-In List Data Fields (**ASSUMPTION** - based on industry standard and SOW requirements)

| Column | Description |
|--------|-------------|
| Tie-In Number | Unique tie-in point identifier |
| Line Number | New line number being connected |
| Existing Line Number | Existing line number being tied into |
| Tie-In Description | Description of tie-in connection |
| P&ID Reference | Source P&ID drawing number(s) |
| Size | Connection size |
| Rating | Pressure class |
| Connection Type | Flanged, welded, hot tap, etc. |
| Location | Physical location description |
| Coordinates | Easting/Northing or grid reference |
| Isolation Requirements | Valves/blinds required for isolation |
| Execution Method | Cold cut, hot tap, etc. |
| Shutdown Required | Yes/No and duration estimate |
| Status | Active, planned, completed |

## 3. Conditions

| Condition Type | Description |
|----------------|-------------|
| **Input Requirements** | P&IDs (DEL-01.03), Line List (DEL-02.01), Existing drawings (TM-provided) |
| **Design Basis** | Connection of new booster pumps and 5x6 manifold to existing Sumas Tank Farm systems |
| **Operating Environment** | Sumas Tank Farm, live crude oil system |
| **Code Compliance** | CSA Z662, TM tie-in procedures (**ASSUMPTION**) |

## 4. Construction

| Aspect | Details |
|--------|---------|
| **Tie-In Numbering** | Per TM naming convention (**TBD** - confirm with Owner) |
| **New Connections** | Booster pump suction/discharge, manifold headers |
| **Existing Systems** | Tank suction/transfer lines, existing pump systems |
| **Execution Notes** | Hot taps and other tie-in activities excluded (by others per SOW) |

## 5. References

| Reference Type | Document |
|----------------|----------|
| **SOW Reference** | SOW-0121: Produce FEED tie-in list (TIL) - SOW Section 3.1.3.1 (p7-8) |
| **SOW Reference** | SOW-0249: Develop piping tie-in table (line number, tie-in description, P&ID number, tie-in number); hot taps and other tie-in activities excluded (by others) - SOW Section 3.2.4.10 (p19) |
| **Source** | Puget Sound Optimization Project Decomposition |
| **Related Deliverables** | DEL-01.03 (P&IDs), DEL-02.01 (Line List), DEL-02.04 (Key Plan), DEL-02.05 (Site Plan) |
| **Standards** | CSA Z662, ASME B31.3, TM Tie-In Procedures (**TBD**) |
| **Owner Standards** | Trans Mountain Pipeline tie-in specifications (**TBD**) |

---
*Generated 2026-02-01 | SOW Refs: SOW-0121, SOW-0249*
