# Datasheet: DEL-01.04 Equipment Sizing Calculations

**Document ID:** DEL-01.04-DS
**Revision:** Phase 2.2 (PASS2-COMPLETE)
**Date:** 2026-02-01
**Status:** PASS2-COMPLETE

---

## Identification

| Field | Value |
|-------|-------|
| Deliverable ID | DEL-01.04 |
| Deliverable Name | Equipment Sizing Calculations |
| Parent Package | PKG-01 Process & Safety Engineering |
| Discipline | Process/Safety |
| Document Type | Calculation |
| Responsible Party | Engineering Contractor |

---

## Attributes

### Technical Attributes

| Parameter | Value | Units | Source |
|-----------|-------|-------|--------|
| Sustainable Flow Rate | 275,000 | bpd | SOW §2.2.1 |
| Sustainable Flow Rate | 1,822 | m³/h | Converted |
| Design (Peak) Flow Rate | 315,000 | bpd | SOW §2.2.1 |
| Design (Peak) Flow Rate | 2,100 | m³/h | Converted per DEL-01.01 |
| Pump Type | VS6-type vertically suspended | - | SOW §2.3.1.1 |
| Total Booster Pumps | 5 | units | SOW §2.3.1.1 |
| Pump Configuration | 2 large, 2 small, 1 medium | - | SOW §2.3.1.2 |
| VFD Requirement | Each pump with VFD (5 total) | - | SOW §2.3.1.4 |
| Flow Meter Requirement | Each pump discharge (5 total) | - | SOW §2.3.1.4 |
| Manifold Configuration | 5x6 | - | SOW §2.3.1.1 |

### Equipment Coverage

| Equipment Type | Quantity | Sizing Basis | Source |
|----------------|----------|--------------|--------|
| Large Capacity Booster Pumps | 2 | Peak flow allocation | SOW §2.3.1.2 |
| Small Capacity Booster Pumps | 2 | Peak flow allocation | SOW §2.3.1.2 |
| Medium Capacity Booster Pump | 1 | Peak flow allocation | SOW §2.3.1.2 |
| VFDs | 5 | Motor sizing per pump | SOW §2.3.1.4 |
| Flow Meters | 5 | Pump discharge flow | SOW §2.3.1.4 |
| Manifold Headers | 5x6 | Peak flow velocity limits | SOW §2.3.1.1 |
| Control Valves | **TBD** | Blending control requirements | SOW §2.3.1.4 |
| Sump Tank | **TBD** | Drainage/containment requirements | SOW §3.2.3.10 |
| Reinjection Pumps | **TBD** | Sump drainage requirements | SOW §3.2.3.10 |

### Document Attributes

| Attribute | Value |
|-----------|-------|
| Anticipated Artifacts | Calculation report(s) |
| Native Format | Excel/MathCAD/Word (editable) |
| Deliverable Format | PDF + Native editable files per SOW §3.2.3.18 |
| Revision Cycle | IFR → IFD → IFC |
| Phase Coverage | FEED (verification) + Detailed Design (finalization) |

---

## Conditions

### Design Conditions

| Parameter | Value | Units | Source |
|-----------|-------|-------|--------|
| Design Flow Rate (Peak) | 315,000 | bpd | SOW §2.2.1 - sizing basis |
| Design Flow Rate (Peak) | 2,100 | m³/h | Converted per DEL-01.01 |
| Sustainable Flow Rate | 275,000 | bpd | SOW §2.2.1 - normal operating |
| Sustainable Flow Rate | 1,822 | m³/h | Converted |
| Blending Range | **TBD** | % | Pending TM confirmation |
| Design Pressure | **TBD** | kPag | Per DEL-01.01 (DBM) |
| Design Temperature | **TBD** | °C | Per DEL-01.01 (DBM) |
| Fluid Density | **TBD** | kg/m³ | Per DEL-01.01 (DBM) |
| Fluid Viscosity | **TBD** | cSt | Per DEL-01.01 (DBM) |
| Suction Pressure (at tank) | **TBD** | kPag | Per DEL-01.07 (Hydraulic Analysis) |
| Discharge Pressure (required) | **TBD** | kPag | Per DEL-01.07 (Hydraulic Analysis) |
| Total Dynamic Head (TDH) | **TBD** | m | Per DEL-01.07 (Hydraulic Analysis) |
| NPSH Available | **TBD** | m | Per DEL-01.07 (Hydraulic Analysis) |

### Operating Scenarios

| Scenario | Description | Sizing Impact |
|----------|-------------|---------------|
| Peak Operation | 315,000 bpd total flow | Primary equipment sizing case |
| Sustainable Operation | 275,000 bpd total flow | Normal operating case |
| Blending Operation | Heavy/Light ratio control | VFD range and control valve sizing |
| NEAT Operation | 10-100% single component | Turndown requirements |
| Tank Transfer | Tank-to-tank flexibility | Pump selection flexibility |

---

## Construction

### Calculation Content Requirements

Equipment sizing calculations shall include:
- Design basis summary (from DEL-01.01 DBM)
- Hydraulic data inputs (from DEL-01.07 Hydraulic Analysis)
- Pump sizing methodology and selection
- VFD sizing and selection (5 units)
- Flow meter sizing and selection (5 units)
- Manifold header sizing (velocity limits)
- Control valve sizing (if applicable)
- Auxiliary equipment sizing (sump, reinjection)
- Safety factors and design margins
- Assumptions and TBDs log
- References to applicable standards

### Calculation Methodology

| Equipment | Sizing Methodology | Key Parameters |
|-----------|-------------------|----------------|
| Booster Pumps | Hydraulic head and flow requirements | Q, TDH, NPSH, efficiency |
| VFDs | Motor power and speed range | HP, RPM range, turndown |
| Flow Meters | Flow range and accuracy | Q range, rangeability, accuracy |
| Manifold Headers | Velocity and pressure drop limits | Velocity (m/s), dP (kPa) |
| Control Valves | Cv and pressure drop | Cv, dP, rangeability |
| Sump Tank | Drainage volume and residence time | Volume, drainage rate |
| Reinjection Pumps | Sump drainage requirements | Q, TDH |

### Dependencies

| Dependency | Source | Status |
|------------|--------|--------|
| Design Basis (DBM) | DEL-01.01 | Required |
| Hydraulic Analysis | DEL-01.07 | Required for head/pressure data |
| PFDs | DEL-01.02 | Required for process conditions |
| Fluid Properties | DEL-01.01 / TM | **TBD** |
| TMP Standards | Attachment A08 | **TBD** - Not in workspace |

---

## References

### Source Documents

| Document | Reference |
|----------|-----------|
| SOW Reference | SOW-0113: Produce FEED equipment sizing calculations |
| SOW Reference | SOW-0006: Verify and finalize equipment sizing during FEED |
| Hydraulic Report | Appendix C-Draft PSO - Hydraulic Report - REV 0 - 25.07.16.pdf |
| Decomposition | Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md |

### Related Deliverables

| Deliverable ID | Relationship |
|----------------|--------------|
| DEL-01.01 | DBM provides design basis and fluid properties |
| DEL-01.02 | PFDs provide process overview |
| DEL-01.03 | P&IDs show equipment configuration |
| DEL-01.05 | Line sizing calculations (interdependent) |
| DEL-01.07 | Hydraulic analysis provides head/pressure data |
| DEL-01.09 | Process datasheets populated from sizing |
| DEL-00.01 | MDR registration required |

### Applicable Standards

| Standard | Description |
|----------|-------------|
| API 610 | Centrifugal Pumps for Petroleum, Petrochemical and Natural Gas Industries |
| API 674/675 | Positive Displacement Pumps (if applicable) |
| HI 9.6 series | Hydraulic Institute pump standards |
| ISA 75.01 | Flow Equations for Sizing Control Valves |
| TMP Standards | **TBD** - Per Attachment A08 |

---

*End of Datasheet*
