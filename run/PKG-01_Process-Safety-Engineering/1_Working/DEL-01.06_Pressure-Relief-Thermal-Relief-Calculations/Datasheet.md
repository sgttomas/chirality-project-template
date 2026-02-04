# Datasheet: DEL-01.06 Pressure Relief / Thermal Relief Calculations

**Document ID:** DEL-01.06-DS
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Identification

| Field | Value |
|-------|-------|
| Deliverable ID | DEL-01.06 |
| Deliverable Name | Pressure Relief / Thermal Relief Calculations |
| Parent Package | PKG-01 Process & Safety Engineering |
| Discipline | Process/Safety |
| Document Type | Calculation |
| Responsible Party | Engineering Contractor |

---

## 2. Attributes

### 2.1 Technical Attributes

| Attribute | Value | Notes |
|-----------|-------|-------|
| Project Phase | FEED + Detailed Design | Per decomposition; IFR -> IFD -> IFC cycle |
| Calculation Type | Relief Device Need Verification and Sizing | PRV and TRV |
| Relief Device Types | PRV (Pressure Relief Valve), TRV (Thermal Relief Valve) | Per SOW-0115, SOW-0225 |
| Design Codes | API 520/521, CSA Z662, ASME B31.4 | **ASSUMPTION:** Standard relief device codes |
| Applicable Systems | Booster pump station, manifold, associated piping | Per PSO scope at Sumas Tank Farm |

### 2.2 Document Attributes

| Attribute | Value |
|-----------|-------|
| Anticipated Artifacts | Calculation report(s) |
| Native Format | Excel/Mathcad + Word/PDF |
| Deliverable Format | PDF + Native editable files |
| Revision Cycle | IFR -> Comment Resolution -> IFD -> IFC |

### 2.3 Calculation Scope

| System/Equipment | Relief Device Type | Notes |
|------------------|-------------------|-------|
| Booster Pump Discharge | PRV/TRV | **TBD** - Per hydraulic analysis |
| Manifold Headers | TRV | **ASSUMPTION:** Thermal relief for blocked-in liquid sections |
| Suction Piping | TRV | **TBD** - If required per thermal exposure |
| Pump Casing | TRV | **ASSUMPTION:** Standard practice for centrifugal pumps |

---

## 3. Conditions

### 3.1 Design Conditions (Relief Sizing Basis)

| Parameter | Value | Source |
|-----------|-------|--------|
| Maximum Operating Pressure (MOP) | **TBD** kPag | Per DEL-01.01 DBM |
| Design Pressure | **TBD** kPag | Per DEL-01.01 DBM |
| Set Pressure (PRV) | **TBD** kPag | Typically at or below design pressure |
| Relieving Pressure | **TBD** kPag | **ASSUMPTION:** 110% of set pressure per API 520 |
| Design Temperature Range | **TBD** deg C | Per DEL-01.01 DBM |
| Maximum Ambient Temperature | **TBD** deg C | For thermal relief calculations |
| Fluid Density | **TBD** kg/m3 | At relieving conditions |
| Fluid Viscosity | **TBD** cSt | At relieving conditions |

### 3.2 Relief Scenarios to be Evaluated

| Scenario | Applicability | Notes |
|----------|---------------|-------|
| Blocked Outlet (Pump) | Yes | Standard scenario for centrifugal pump relief |
| Thermal Expansion (Liquid) | Yes | For blocked-in liquid sections exposed to solar/fire |
| Fire Case | **TBD** | **TBD** - if applicable per API 521 screening criteria |
| Control Valve Failure | **TBD** | Per HAZOP findings (DEL-01.15) |
| Power Failure / Surge | **TBD** | Per transient analysis (DEL-01.08) |

### 3.3 Relief Device Sizing Parameters

| Parameter | PRV | TRV | Notes |
|-----------|-----|-----|-------|
| Set Pressure | **TBD** kPag | **TBD** kPag | Per design pressure |
| Blowdown | **TBD** % | N/A | Per API standards |
| Orifice Size | **TBD** | **TBD** | Calculated output |
| Inlet/Outlet Size | **TBD** | **TBD** | Calculated output |

---

## 4. Construction

### 4.1 Calculation Content Requirements

Each relief calculation shall include:
- Identification of protected equipment/system
- Relief scenario description and governing case
- Process conditions at relieving conditions
- Required relieving rate calculation
- Device sizing per applicable API/ASME standards
- Inlet piping pressure drop verification (3% of set pressure per API 520 Part II)
- Outlet piping built-up backpressure verification (10% limit for conventional PRVs)
- Selected device specification summary
- Discharge disposition (atmospheric/closed system)

### 4.2 Calculation Methodology

| Calculation Type | Standard | Notes |
|------------------|----------|-------|
| PRV Sizing (Liquid) | API 520 Part I | Standard methodology |
| PRV Sizing (Two-Phase) | API 520 Part I | If applicable |
| TRV Sizing | API 520 Part I / API 521 | Thermal expansion case |
| Inlet Pressure Drop | API 520 Part II | <= 3% of set pressure |
| Outlet Backpressure | API 520 Part II | Built-up backpressure <= 10% for conventional PRVs |

### 4.3 Dependencies

| Dependency | Source | Status |
|------------|--------|--------|
| Design Basis (DBM) | DEL-01.01 | Required |
| Process Flow Diagrams | DEL-01.02 | Required |
| P&IDs | DEL-01.03 | Required |
| Equipment Sizing | DEL-01.04 | Concurrent |
| Line Sizing | DEL-01.05 | Concurrent |
| Hydraulic Analysis | DEL-01.07 | Concurrent |
| Transient Analysis | DEL-01.08 | Concurrent |
| Process Datasheets | DEL-01.09 | Concurrent |
| HAZOP Findings | DEL-01.15 | For detailed design updates |
| Equipment Datasheets (MAWP) | PKG-03 Mechanical | Required |

---

## 5. References

### 5.1 Source Documents

| Document | Reference |
|----------|-----------|
| SOW Reference | SOW-0115: Verify need for Pressure Relief Valves / Thermal Relief Valves and support with calculations |
| SOW Reference | SOW-0225: Update/finalize safety device calculations to IFC (thermal relief valves) |
| SOW Reference | SOW-0232: Provide IFC process deliverables set including pressure relief calculations |
| Decomposition | Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md |

### 5.2 Related Deliverables

| Deliverable ID | Relationship |
|----------------|--------------|
| DEL-01.01 | DBM provides design basis and criteria |
| DEL-01.02 | PFDs show relief device locations |
| DEL-01.03 | P&IDs show relief device details and tag numbers |
| DEL-01.07 | Hydraulic analysis provides operating pressures |
| DEL-01.08 | Transient analysis identifies surge scenarios |
| DEL-01.09 | Process datasheets provide fluid properties |
| DEL-01.15 | HAZOP identifies relief scenarios |
| DEL-01.16 | Material requisitions for relief devices |
| PKG-03 | Equipment datasheets provide MAWP and mechanical specifications |

### 5.3 Applicable Standards

| Standard | Description |
|----------|-------------|
| API 520 Part I | Sizing, Selection, and Installation of Pressure-relieving Devices - Sizing and Selection |
| API 520 Part II | Sizing, Selection, and Installation of Pressure-relieving Devices - Installation |
| API 521 | Pressure-relieving and Depressuring Systems |
| API 526 | Flanged Steel Pressure-relief Valves (standard orifice designations) |
| CSA Z662 | Oil and Gas Pipeline Systems |
| ASME B31.4 | Pipeline Transportation Systems for Liquids and Slurries |
| TM Standards | Trans Mountain project-specific standards (**TBD**) |

---

*End of Datasheet*
