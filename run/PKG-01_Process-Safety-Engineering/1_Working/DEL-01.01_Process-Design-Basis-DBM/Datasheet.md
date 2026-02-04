# Datasheet: DEL-01.01 Process Design Basis / DBM (Design Basis & Design Criteria)

**Document ID:** DEL-01.01-DS
**Revision:** Phase 2.2 (INITIALIZED)
**Date:** 2026-02-01
**Status:** INITIALIZED

---

## Identification

| Attribute | Value |
|-----------|-------|
| Deliverable ID | DEL-01.01 |
| Deliverable Name | Process Design Basis / DBM (Design Basis & Design Criteria) |
| Parent Package | PKG-01 Process & Safety Engineering |
| Discipline | Process/Safety |
| Document Type | Document |
| Responsible Party | Engineering Contractor |

---

## Attributes

### Technical Attributes

| Parameter | Value | Units | Source |
|-----------|-------|-------|--------|
| Project | Puget Sound Optimization Project (PSO) | - | SOW §1.1.1 |
| Location | Sumas Tank Farm (Sumas Terminal) | - | SOW §2.3.1.1 |
| Sustainable Flow Rate | 275,000 | bpd | SOW §2.2.1 |
| Sustainable Flow Rate | 1,822 | m³/h | SOW §2.2.1 (converted) |
| Design (Peak) Flow Rate | 315,000 | bpd | SOW §2.2.1 |
| Design (Peak) Flow Rate | 2,100 | m³/h | DBM §2.2.1.1 |
| Blending Ratio (SOW) | 20% Heavy to 80% Light | - | SOW §2.3.1.4 |
| Blending Range (DBM) | 10%-100% NEAT (100% = undiluted heavy crude) | - | DBM §2.2.2.2 |
| Blending Range Status | **TBD** - Confirm with TM (SOW vs DBM discrepancy) | - | Open Issue |
| Minimum Turndown Flow Rate | **TBD** | bpd | **ASSUMPTION:** Typically 50% of rated pump capacity | VFD operating range |
| Pump Type | VS6-type vertically suspended | - | SOW §2.3.1.1 |
| Pump Configuration | 2 large, 2 small, 1 medium capacity | - | SOW §2.3.1.2 |
| Total Booster Pumps | 5 | units | SOW §2.3.1.1 |
| Manifold Configuration | 5x6 (5 pumps × 6 discharge connections) | - | SOW §2.3.1.1 |
| VFD Requirement | Each pump with VFD | - | SOW §2.3.1.4 |
| Flow Meter Requirement | Dedicated discharge flow meter per pump | - | SOW §2.3.1.4 |
| Design Life | **TBD** | years | **ASSUMPTION:** Typically 25-30 years |
| Design Codes | CER OPR, CSA Z662, PHMSA 195 | - | SOW §4.1.3 |

### Document Attributes

| Attribute | Value |
|-----------|-------|
| Anticipated Artifacts | DBM / design basis document |
| Native Format | Word/PDF (editable) |
| Deliverable Format | PDF + Native editable files per SOW §3.2.3.18 |
| Revision Cycle | IFR → Comment Resolution → IFD → IFC |
| Phase Coverage | FEED + Detailed Design |

---

## Conditions

### Design Conditions

| Parameter | Value | Source | Notes |
|-----------|-------|--------|-------|
| Design Pressure | **TBD** | Per hydraulic analysis | Derived from DEL-01.07 |
| Design Temperature (Max) | **TBD** | Per process requirements | |
| Design Temperature (Min) | **TBD** | Site ambient conditions | |
| Ambient Temperature Range | **TBD** | Site-specific data | Sumas, WA area |
| Seismic Zone | **TBD** | Per geotechnical data | |
| Corrosion Allowance | **TBD** | mm | Per TMP standards |
| Material Selection Basis | **TBD** | - | Per TMP standards and fluid compatibility |

### Operating Conditions

| Parameter | Sustainable | Peak | Units | Notes |
|-----------|-------------|------|-------|-------|
| Flow Rate | 275,000 | 315,000 | bpd | Per SOW §2.2.1 |
| Flow Rate | 1,822 | 2,100 | m³/h | Converted |
| Operating Pressure | **TBD** | **TBD** | kPag | Per hydraulic model |
| Operating Temperature | **TBD** | **TBD** | °C | |
| Blend Ratio Range | **TBD** | **TBD** | % Heavy | Pending TM confirmation (SOW vs DBM) |

---

## Construction

### Content Requirements

The DBM shall include:
- Project scope definition and boundaries (including battery limits)
- Design philosophy and criteria (Source: SOW §3.1.3.1)
- Applicable codes and standards (Source: SOW §4.1.3)
- Process design parameters (flow, pressure, temperature, fluid properties)
- Environmental and site conditions
- Equipment design basis (pumps, manifold, metering)
- Material selection criteria (preliminary)
- Interface definitions with existing Sumas Terminal facilities
- Safety and overpressure protection philosophy
- Blending requirements and control philosophy basis
- Quality requirements per TMP Standards
- Documentation of any deviations from TMP standards with approval status

### Dependencies

| Dependency | Source | Status |
|------------|--------|--------|
| TMP Standards/Specifications (Attachment A08) | Trans Mountain | **TBD** - Not in workspace |
| Preliminary DBM | Puget Sound Optimization Project DBM.pdf | Available (informational only per SOW §4.2.2.2) |
| Appendix B - PFD | Appendix B-PFD-xxxx-ST00-GSxxxx_0_IFR_2025-05-16.pdf | Available |
| Appendix C - Hydraulic Report | Appendix C-Draft PSO - Hydraulic Report - REV 0 - 25.07.16.pdf | Available |
| Site Survey Data | Existing documentation | **TBD** |
| Geotechnical Data | Existing or PKG-04 | **TBD** |

---

## References

### Source Documents

| Document | Reference | Notes |
|----------|-----------|-------|
| SOW | Exhibit A - Scope of Work PS.pdf | Rev 0; Effective 2025/07/24 |
| Preliminary DBM | Puget Sound Optimization Project DBM.pdf | Rev 0; Effective 2025/07/15; informational only |
| SSOW Reference | SOW-0110: Produce FEED DBM including Design Basis and Design Criteria (GS) | |
| Decomposition | Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md | |

### Related Deliverables

| Deliverable ID | Relationship |
|----------------|--------------|
| DEL-01.02 | PFDs based on DBM parameters |
| DEL-01.03 | P&IDs based on DBM parameters |
| DEL-01.04 | Equipment sizing per DBM criteria |
| DEL-01.05 | Line sizing per DBM criteria |
| DEL-01.06 | Relief calculations per DBM philosophy |
| DEL-01.07 | Hydraulic analysis per DBM criteria |
| DEL-00.01 | MDR registration required |

### Applicable Standards

| Standard | Description | Applicability |
|----------|-------------|---------------|
| CER OPR | Canada Energy Regulator Onshore Pipeline Regulations | Federal pipeline regulations |
| CSA Z662 | Oil and Gas Pipeline Systems | Pipeline design standard |
| ASME B31.4 | Pipeline Transportation Systems for Liquids | Liquid piping |
| Title 49 PHMSA Part 195 | Transportation of Hazardous Liquids by Pipeline | US regulatory (cross-border) |
| TMP Standards | Trans Mountain Pipeline Standards | **TBD** - Attachment A08 not provided |
| API Standards | **ASSUMPTION** - Relevant API standards for equipment | Industry practice |

---

*End of Datasheet*
