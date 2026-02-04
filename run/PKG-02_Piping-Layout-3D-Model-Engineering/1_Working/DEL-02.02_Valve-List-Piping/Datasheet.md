# Datasheet: Valve List (Piping)

## 1. Identification

| Field | Value |
|-------|-------|
| **Deliverable ID** | DEL-02.02 |
| **Deliverable Name** | Valve List (Piping) |
| **Package** | PKG-02: Piping, Layout & 3D Model Engineering |
| **Discipline** | Piping |
| **Deliverable Type** | List |
| **Responsible Party** | Engineering Contractor |
| **Document Number** | **TBD** |
| **Revision** | **TBD** |

## 2. Attributes

| Attribute | Value |
|-----------|-------|
| **Format** | Excel spreadsheet (VLL) |
| **Output** | Valve list |
| **Phase Coverage** | FEED + Detailed Design |
| **Maintenance** | Maintained through IFC |

### 2.1 Valve List Data Fields (**ASSUMPTION** - based on industry standard)

| Column | Description |
|--------|-------------|
| Valve Tag | Unique valve identifier |
| Line Number | Associated line number |
| Valve Type | Gate, globe, ball, check, plug, butterfly, etc. |
| Size | Nominal valve size |
| Rating | Pressure class (e.g., 150#, 300#, 600#) |
| Material Class | Piping class designation |
| End Connection | Flanged, threaded, BW, SW |
| Operator Type | Manual, motor, pneumatic, hydraulic |
| Fail Position | Fail open, fail closed, fail last (if actuated) |
| Service | Fluid service description |
| P&ID Reference | Source P&ID drawing number |
| Spec Reference | Valve specification reference |

## 3. Conditions

| Condition Type | Description |
|----------------|-------------|
| **Input Requirements** | P&IDs (DEL-01.03), Line List (DEL-02.01), PMC Index (DEL-02.25) |
| **Design Basis** | SOW flow rates: 275,000 bpd sustainable, 315,000 bpd peak |
| **Operating Environment** | Sumas Tank Farm, crude oil service |
| **Code Compliance** | ASME B16.34, API 600/602/608, MSS-SP standards (**ASSUMPTION**) |

## 4. Construction

| Aspect | Details |
|--------|---------|
| **Valve Tagging** | Per TM valve numbering convention (**TBD**) |
| **Valve Types** | Isolation, control, check, drain, vent, PSV (**ASSUMPTION**) |
| **Key Equipment Valves** | Booster pump suction/discharge, manifold isolation |
| **Actuated Valves** | MOVs, AOVs per P&ID requirements |

## 5. References

| Reference Type | Document |
|----------------|----------|
| **SOW Reference** | SOW-0120: Produce FEED valve list (VLL) - SOW Section 3.1.3.1 (p7-8) |
| **SOW Reference** | SOW-0119: Produce FEED mechanical/electrical datasheets for valves (incl check valves/actuators) - SOW Section 3.1.3.1 (p7) |
| **Source** | Puget Sound Optimization Project Decomposition |
| **Related Deliverables** | DEL-01.03 (P&IDs), DEL-02.01 (Line List), DEL-02.19 (MTO), DEL-02.20 (Specialty Items) |
| **Standards** | ASME B16.34, API 600, API 602, API 608, TM Valve Specifications (**TBD**) |
| **Owner Standards** | Trans Mountain Pipeline specifications (**TBD**) |

---
*Generated 2026-02-01 | SOW Refs: SOW-0119, SOW-0120*
