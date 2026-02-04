# Datasheet: DEL-01.16 Material Requisitions (Process) (Engineering)

**Document ID:** DEL-01.16-DS
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Identification

| Field | Value |
|-------|-------|
| Deliverable ID | DEL-01.16 |
| Deliverable Name | Material Requisitions (Process) (Engineering) |
| Parent Package | PKG-01 Process & Safety Engineering |
| Discipline | Process/Safety |
| Document Type | Document |
| Responsible Party | Engineering Contractor |

---

## 2. Attributes

### 2.1 Technical Attributes

| Attribute | Value | Notes |
|-----------|-------|-------|
| Project Phase | Detailed Design | MRs support procurement |
| Facility Location | Sumas Tank Farm | Per PSO project scope |
| Equipment Types | Process equipment per SOW | Pumps, valves, instruments, vessels |
| Format | Material Requisition packages | Per TM procurement requirements |

### 2.2 Document Attributes

| Attribute | Value |
|-----------|-------|
| Anticipated Artifacts | Material requisition packages |
| Native Format | Word (.docx) + Excel (.xlsx) + PDF attachments |
| Deliverable Format | PDF for issue, native for TM use |
| Revision Cycle | IFR -> IFC (as procurement documents) |

---

## 3. Conditions

### 3.1 Equipment Categories (per SOW)

| Category | Items | SOW Reference |
|----------|-------|---------------|
| Pumps | Booster pumps (5 VS6 type) | SOW Section 2.3.1.2 |
| Pumps | Sump tank reinjection pumps | SOW Section 2.3.1.1 |
| Pumps | Dewatering equipment | SOW Section 2.3.1.1 |
| Valves | Process valves (manual, control, isolation) | General scope |
| Piping Bulks | Pipe, fittings, flanges | General scope |
| Instrumentation | Flow meters (5 discharge) | SOW Section 2.3.1.4 |
| TRVs | Temperature relief valves | **ASSUMPTION:** Per safety requirements |
| Tanks | Sump tank | SOW Section 2.3.1.1 |

### 3.2 MR Package Contents

| Component | Description | Notes |
|-----------|-------------|-------|
| Requisition Form | Standard TM/project MR form | **TBD** - Template from TM |
| Technical Specification | Equipment-specific technical requirements | Attached to MR |
| Process Datasheets | Equipment datasheets per DEL-01.09 | Attached to MR |
| Drawings | Reference drawings (P&IDs from DEL-01.03, GAs) | Listed references |
| Vendor List | Approved/preferred vendors | Per TM requirements |
| Bid Evaluation Criteria | Criteria for bid comparison | If applicable |

### 3.3 Design Basis Summary

| Parameter | Value | Source |
|-----------|-------|--------|
| Design Flow (sustainable) | 275,000 bpd (1,822 m3/h) | SOW Section 2.2.1 |
| Design Flow (peak) | 315,000 bpd (2,100 m3/h) | SOW Section 2.2.1 |
| Pump Configuration | 5 pumps: 2 large, 2 small, 1 medium | SOW Section 2.3.1.2 |
| Drive Type | Variable Frequency Drives (VFDs) | SOW Section 2.3.1.2 |
| Blending Ratio | 20/80 (per SOW) or 10-100% NEAT (per DBM) | OI-002 pending resolution |
| Service | Heavy/Light crude blending | Per project scope (DEL-01.01) |

---

## 4. Construction

### 4.1 MR Package Structure (Typical)

| Section | Content |
|---------|---------|
| Cover Sheet | MR number, equipment tag, description, revision |
| Requisition Form | Commercial and administrative requirements |
| Scope of Supply | Detailed scope and battery limits |
| Technical Specification | Performance, design, and material requirements |
| Datasheet(s) | Equipment technical parameters (DEL-01.09) |
| Drawing List | Reference drawings with revision status (DEL-01.03) |
| Appendices | Vendor list, spare parts requirements, QA/QC requirements |

### 4.2 Content Requirements by Equipment Type

**Booster Pumps:**
- Hydraulic performance requirements (based on DEL-01.04)
- Driver requirements (VFD compatible motors per PKG-06)
- Material specifications (API 610)
- Mechanical seal requirements
- Testing requirements (shop tests)
- Spare parts requirements

**Valves:**
- Size, rating, and end connections
- Material specifications (per PKG-02)
- Actuation requirements (if applicable per PKG-07)
- Testing requirements

**Piping Bulks:**
- Material specifications per piping class (per PKG-02)
- Quantity summary by size/schedule
- Quality requirements

**Flow Meters:**
- Measurement range and accuracy
- Process conditions (per DEL-01.09)
- Output/communication requirements (per PKG-07)
- Calibration requirements

### 4.3 Dependencies

| Dependency | Source | Status |
|------------|--------|--------|
| Process Design Basis | DEL-01.01 | **TBD** |
| P&IDs | DEL-01.03 | **TBD** |
| Equipment Sizing Calculations | DEL-01.04 | **TBD** |
| Equipment List | DEL-01.07 | **TBD** |
| Process Datasheets | DEL-01.09 | **TBD** |
| Line List | DEL-02.01 | **TBD** |
| Valve List | DEL-02.02 | **TBD** |
| Piping Material Specifications | PKG-02 | **TBD** |
| TM Approved Vendor List | TM Procurement | **TBD** |

---

## 5. References

### 5.1 Source Documents

| Document | Reference |
|----------|-----------|
| SOW Reference | SOW-0232: Material requisitions for equipment identified in SOW |
| Decomposition | Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md |

### 5.2 Related Deliverables

| Deliverable ID | Relationship |
|----------------|--------------|
| DEL-01.01 | Process design basis defines service conditions |
| DEL-01.03 | P&IDs referenced in MRs |
| DEL-01.04 | Equipment sizing calculations define MR technical basis |
| DEL-01.07 | Equipment list coordinates equipment tags |
| DEL-01.09 | Process datasheets attached to MRs |
| DEL-02.01 | Line list informs piping MRs |
| DEL-02.02 | Valve list informs valve MRs |
| PKG-02 | Piping specifications define material requirements |
| PKG-06 | Electrical requirements for motor-driven equipment |
| PKG-07 | Instrumentation interface requirements |

### 5.3 Applicable Standards

| Standard | Description |
|----------|-------------|
| API 610 | Centrifugal Pumps for Petroleum, Petrochemical and Natural Gas Industries |
| API 600/602/603 | Steel Gate/Globe/Check Valves |
| API 682 | Pumps - Shaft Sealing Systems |
| ASME B31.4 | Pipeline Transportation Systems for Liquids |
| CSA Z662 | Oil and Gas Pipeline Systems |
| TM Standards | TM procurement and equipment specifications (**TBD**) |

---

*End of Datasheet*
