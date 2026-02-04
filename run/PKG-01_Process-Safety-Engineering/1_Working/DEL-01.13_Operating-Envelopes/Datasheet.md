# Datasheet: DEL-01.13 Operating Envelopes

**Document ID:** DEL-01.13-DS
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Identification

| Field | Value |
|-------|-------|
| Deliverable ID | DEL-01.13 |
| Deliverable Name | Operating Envelopes |
| Parent Package | PKG-01 Process & Safety Engineering |
| Discipline | Process/Safety |
| Document Type | Document |
| Responsible Party | Engineering Contractor |

---

## 2. Attributes

### 2.1 Technical Attributes

| Attribute | Value | Notes |
|-----------|-------|-------|
| Project Phase | Detailed Design | Per SOW-0232 (IFC deliverables set) |
| Facility Location | Sumas Tank Farm | Per PSO project scope |
| Operating Modes | Normal, Startup, Shutdown, Upset, Turndown | **ASSUMPTION:** Typical operating modes |
| Fluid Types | Heavy Crude, Light Crude, Blended Product | Per blending requirements |

### 2.2 Document Attributes

| Attribute | Value |
|-----------|-------|
| Anticipated Artifacts | Operating envelopes document |
| Native Format | Word/Excel (.docx/.xlsx) |
| Deliverable Format | PDF + Native editable files |
| Revision Cycle | IFR -> IFD -> IFC |

---

## 3. Conditions

### 3.1 Operating Parameters

| Parameter | Unit | Min | Normal | Max | Notes |
|-----------|------|-----|--------|-----|-------|
| Throughput Rate (sustainable) | bpd | **TBD** | 275,000 | 275,000 | SOW-0232: Section 2.2.1 |
| Throughput Rate (peak) | bpd | **TBD** | **TBD** | 315,000 | SOW-0232: Section 2.2.1 |
| Throughput Rate (sustainable) | m3/h | **TBD** | 1,822 | 1,822 | SOW-0232: Section 2.2.1 |
| Throughput Rate (peak) | m3/h | **TBD** | **TBD** | 2,100 | SOW-0232: Section 2.2.1 |
| Suction Pressure | kPag | **TBD** | **TBD** | **TBD** | Per hydraulic analysis (DEL-01.07) |
| Discharge Pressure | kPag | **TBD** | **TBD** | **TBD** | Per hydraulic analysis (DEL-01.07) |
| Operating Temperature | degC | **TBD** | **TBD** | **TBD** | Per fluid properties |

### 3.2 Blending Parameters

| Parameter | Value | Notes |
|-----------|-------|-------|
| Blend Ratio (SOW) | 20% Heavy to 80% Light | SOW-0232: Section 2.3.1.4 |
| Component Volume Range (DBM) | 10% - 100% (NEAT) | DBM (DEL-01.01): Referenced in SOW notes |
| Blend Control | Flow ratio control via VFDs + flow meters | Per SOW-0232: Section 2.3.1.4 |

**Open Issue (OI-002):** Blending ratio acceptance criteria differ between SOW-0232 (20/80) and DBM/DEL-01.01 (10-100% NEAT). Requires TM confirmation per decomposition OI-002.

### 3.3 Pump Operating Envelopes

| Pump Type | Quantity | Flow Range | Head Range | Notes |
|-----------|----------|------------|------------|-------|
| Large-Capacity Booster | 2 | **TBD** | **TBD** | Per SOW-0232: Section 2.3.1.2; Equipment sizing DEL-01.04 |
| Small-Capacity Booster | 2 | **TBD** | **TBD** | Per SOW-0232: Section 2.3.1.2; Equipment sizing DEL-01.04 |
| Medium-Capacity Booster | 1 | **TBD** | **TBD** | Per SOW-0232: Section 2.3.1.2; Equipment sizing DEL-01.04 |

---

## 4. Construction

### 4.1 Document Structure (Typical)

| Section | Description |
|---------|-------------|
| Introduction | Purpose, scope, and applicability |
| Operating Modes | Definition of operating modes (normal, startup, shutdown, upset) |
| Throughput Envelopes | Flow rate ranges and constraints |
| Pressure Envelopes | Suction and discharge pressure limits |
| Temperature Envelopes | Operating temperature ranges |
| Blending Envelopes | Blend ratio ranges and constraints |
| Pump Operating Maps | Individual pump performance envelopes |
| System Constraints | Limitations and restrictions |
| Upset/Abnormal Conditions | Response to abnormal operations |
| Appendices | Supporting data, curves, calculations |

### 4.2 Content Requirements

The Operating Envelopes document shall include:
- Allowable operating ranges for all key process parameters
- Constraints and limitations on operations
- Pump performance envelopes with VFD speed ranges
- Blending ratio constraints and control philosophy
- Relationship to protective device settings (OL&PDS)
- Operating mode definitions and transitions
- Alarm and trip setpoints (coordinated with DEL-07.09)

### 4.3 Dependencies

| Dependency | Source | Status |
|------------|--------|--------|
| Process Design Basis / DBM | DEL-01.01 | **TBD** |
| Equipment Sizing Calculations | DEL-01.04 | **TBD** |
| Hydraulic Analysis Report | DEL-01.07 | **TBD** |
| Transient Analysis | DEL-01.08 | **TBD** |
| Process Datasheets | DEL-01.09 | **TBD** |
| Pump Vendor Data | Procurement | **TBD** |
| TM OL&PDS | TM Document Control | **TBD** |
| Blending Ratio Confirmation | TM (OI-002 resolution) | **TBD** |

---

## 5. References

### 5.1 Source Documents

| Document | Reference |
|----------|-----------|
| SOW Reference | SOW-0232: Provide IFC process deliverables set including... operating envelopes... |
| Decomposition | Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md |
| Open Issue | OI-002: Blending range acceptance criteria (TM confirmation required) |

### 5.2 Related Deliverables

| Deliverable ID | Relationship |
|----------------|--------------|
| DEL-01.01 | Design Basis Memorandum (DBM) provides design basis parameters |
| DEL-01.04 | Equipment Sizing Calculations define capacity limits |
| DEL-01.07 | Hydraulic Analysis Report defines pressure envelopes |
| DEL-01.08 | Transient Analysis defines dynamic limits |
| DEL-01.09 | Process Datasheets document equipment limits |
| DEL-01.15 | HAZOP reviews operating envelopes and identifies hazards |
| DEL-07.09 | Control Narratives implement operating constraints |

### 5.3 Applicable Standards

| Standard | Description |
|----------|-------------|
| CSA Z662 | Oil and Gas Pipeline Systems |
| API 610 | Centrifugal Pumps for Petroleum |
| API 682 | Pumps - Shaft Sealing Systems |
| HI 9.6.3 | Pump Allowable Operating Region |
| ISA-18.2 | Alarm Management |
| TM OL&PDS | Operating Limits and Protective Device Settings Manual |

---

*End of Datasheet*
