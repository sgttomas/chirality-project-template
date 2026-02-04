# Datasheet: DEL-01.15 HAZOP Final Report & Closeout Items

**Document ID:** DEL-01.15-DS
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Identification

| Field | Value |
|-------|-------|
| Deliverable ID | DEL-01.15 |
| Deliverable Name | HAZOP Final Report & Closeout Items |
| Parent Package | PKG-01 Process & Safety Engineering |
| Discipline | Process/Safety |
| Document Type | Report |
| Responsible Party | Engineering Contractor |

---

## 2. Attributes

### 2.1 Technical Attributes

| Attribute | Value | Notes |
|-----------|-------|-------|
| Project Phase | Detailed Design / Pre-IFC | HAZOP study completed before IFC |
| Facility Location | Sumas Tank Farm | Per PSO project scope |
| Study Type | HAZOP (Hazard and Operability Study) | Per IEC 61882 / TM requirements |
| Scope | PSO modifications and tie-ins | New and modified systems |

### 2.2 Document Attributes

| Attribute | Value |
|-----------|-------|
| Anticipated Artifacts | HAZOP final report, closeout log |
| Native Format | Word (.docx) + Excel (.xlsx) for action tracking |
| Deliverable Format | PDF + Native editable files |
| Revision Cycle | Draft -> Review -> Final |

---

## 3. Conditions

### 3.1 HAZOP Study Scope

| System/Node | Description | Notes |
|-------------|-------------|-------|
| Booster Pump System | New VS6 booster pumps (5 units) | Primary scope |
| Pump Manifold | 5x6 pump suction/discharge manifold | New installation |
| Tank Suction | Tie-ins to TK-101, TK-102 | Interface with existing |
| Pipeline Discharge | Connection to Puget Sound Pipeline | Interface with existing |
| Control System | VFD control, flow metering, blending control | Per SOW Section 2.3.1.4 |
| Containment | Sump tank, reinjection pumps, containment wall | Per SOW Section 2.3.1.1 |

### 3.2 Guidewords Applied

| Guideword | Parameters | Application |
|-----------|------------|-------------|
| NO / NOT | Flow, Level, Pressure | Loss of intended function |
| MORE | Flow, Pressure, Temperature, Level | Increase beyond design |
| LESS | Flow, Pressure, Temperature, Level | Decrease below design |
| REVERSE | Flow, Sequence | Opposite direction/order |
| AS WELL AS | Composition, Contamination | Additional unintended material |
| PART OF | Composition | Incomplete intended material |
| OTHER THAN | Operation, Maintenance | Unintended activities |

### 3.3 Study Parameters

| Parameter | Requirement | Notes |
|-----------|-------------|-------|
| Study Team | Multidisciplinary | Process, Operations, Safety, I&C, Electrical |
| Facilitator | Qualified HAZOP Leader (per IEC 61882) | **TBD** - Per TM/Contractor agreement |
| P&ID Basis | IFR or better | Study conducted on near-final P&IDs |
| Participation | TM Operations, TM Safety, TM Engineering | Per TM requirements |

---

## 4. Construction

### 4.1 Report Structure (Typical)

| Section | Content |
|---------|---------|
| Executive Summary | Key findings, statistics, conclusions |
| Introduction | Purpose, scope, study basis |
| Methodology | HAZOP approach, guidewords, team composition |
| System Description | Overview of systems studied |
| Node Definitions | Node boundaries and descriptions |
| HAZOP Worksheets | Detailed node-by-node analysis |
| Action Item Register | All recommendations with assignments |
| Risk Matrix | Risk ranking methodology and results |
| Conclusions | Summary of findings and residual risks |
| Appendices | Attendance records, P&IDs studied, references |

### 4.2 Closeout Log Structure

| Column | Description |
|--------|-------------|
| Action ID | Unique identifier (e.g., HAZOP-PSO-001) |
| Node | Associated study node |
| Deviation | Hazardous deviation identified |
| Cause | Potential cause of deviation |
| Consequence | Potential consequence |
| Safeguard | Existing safeguards identified |
| Recommendation | Action recommended by study team |
| Risk Ranking (Pre) | Pre-mitigation risk level |
| Response | Action taken or planned |
| Responsible Party | Owner of action (TM, Contractor, Other) |
| Due Date | Target completion date |
| Status | Open / In Progress / Closed |
| Closure Evidence | Documentation of completion |
| Verified By | Person confirming closure |
| Closure Date | Date action closed |
| Risk Ranking (Post) | Post-mitigation residual risk level |

### 4.3 Content Requirements

The HAZOP deliverable shall include:
- Complete HAZOP report documenting all study sessions
- Node-by-node analysis worksheets
- Action item register with all recommendations
- Closeout tracking for each action item
- Risk ranking per TM-approved risk matrix
- Signatures/acknowledgments from study participants

### 4.4 Dependencies

| Dependency | Source | Status |
|------------|--------|--------|
| P&IDs (IFR or better) | DEL-01.03 | **TBD** |
| Process Design Basis | DEL-01.01 | **TBD** |
| Operating Envelopes | DEL-01.13 | **TBD** |
| Control Narratives | DEL-07.09 | **TBD** |
| Cause & Effect Diagrams | DEL-07.10 | **TBD** |
| Equipment List | DEL-01.07 | **TBD** |
| TM Operations Input | TM Operations | **TBD** |
| TM-Approved Risk Matrix | TM Safety | **TBD** |

---

## 5. References

### 5.1 Source Documents

| Document | Reference |
|----------|-----------|
| SOW Reference | SOW-0232: HAZOP participation and action item closeout |
| Decomposition | Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md |

### 5.2 Related Deliverables

| Deliverable ID | Relationship |
|----------------|--------------|
| DEL-01.03 | P&IDs form basis for HAZOP study |
| DEL-01.01 | Process Design Basis provides operating parameters |
| DEL-01.13 | Operating envelopes define operating limits reviewed |
| DEL-01.07 | Equipment List identifies equipment studied |
| DEL-07.09 | Control narratives provide control philosophy input |
| DEL-07.10 | Cause & effect diagrams show safety system logic |
| DEL-01.14 | Deviations may result from HAZOP recommendations |

### 5.3 Applicable Standards

| Standard | Description |
|----------|-------------|
| IEC 61882 | Hazard and operability studies (HAZOP studies) - Application guide |
| IEC 61511 | Functional safety - Safety instrumented systems |
| CSA Z662 | Oil and Gas Pipeline Systems - Safety requirements |
| API RP 750 | Management of Process Hazards |
| TM Safety Standards | Trans Mountain HAZOP requirements (**TBD**) |

---

*End of Datasheet*
