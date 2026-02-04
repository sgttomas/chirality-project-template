# Procedure: DEL-01.13 Operating Envelopes

**Document ID:** DEL-01.13-PR
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Purpose

### 1.1 Procedure Objective

This procedure defines the step-by-step process for developing, reviewing, and issuing the Operating Envelopes document for the Puget Sound Optimization project.

### 1.2 Scope

This procedure covers:
- Operating envelope definition for new PSO facilities
- Coordination with hydraulic analysis and equipment sizing
- OL&PDS alignment and update coordination
- TM operations review and approval
- Revision and update management

---

## 2. Prerequisites

### 2.1 Required Inputs

| Input | Source | Status |
|-------|--------|--------|
| Process Design Basis / DBM | DEL-01.01 | Required before start |
| Equipment Sizing Calculations | DEL-01.04 | Required for equipment limits |
| Hydraulic Analysis Report | DEL-01.07 | Required for pressure/flow limits |
| Transient Analysis | DEL-01.08 | Required for dynamic limits |
| Process Datasheets | DEL-01.09 | Required for equipment specifications |
| Pump Vendor Data | Procurement | Required for pump envelopes |
| TM OL&PDS | TM Document Control | Required for protective settings |
| Blending Ratio Confirmation | TM (OI-002 resolution) | Required before finalization |

### 2.2 Required Resources

| Resource | Role |
|----------|------|
| Lead Process Engineer | Operating Envelopes Owner |
| Hydraulic Engineer | Hydraulic analysis support (DEL-01.07) |
| Safety Engineer | Transient analysis support (DEL-01.08) |
| Control Systems Engineer | Control implementation input (DEL-07.09) |
| Mechanical Engineer | Equipment limits verification |
| TM Operations Representative | Operations input and review |

### 2.3 Required Authorizations

| Authorization | Authority | Required For |
|---------------|-----------|--------------|
| Blending Ratio Confirmation | TM Engineering | Resolve OI-002 |
| OL&PDS Update Scope | TM Operations | Changes to protective settings |
| IFR Release | Engineering Manager | IFR submission |
| IFC Release | Engineering Manager + TM Ops | IFC issue |

---

## 3. Steps

### 3.1 Phase 1: Data Gathering

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 1.1 | Review DBM (DEL-01.01) for design basis parameters | Lead Process Engineer | Design parameters |
| 1.2 | Obtain hydraulic analysis results (DEL-01.07) | Lead Process Engineer | Pressure/flow data |
| 1.3 | Obtain transient analysis results (DEL-01.08) | Lead Process Engineer | Dynamic limits |
| 1.4 | Obtain equipment sizing calculations (DEL-01.04) | Lead Process Engineer | Equipment limits |
| 1.5 | Review process datasheets (DEL-01.09) | Lead Process Engineer | Equipment specifications |
| 1.6 | Request pump performance curves from vendor | Project Engineer | Vendor data |
| 1.7 | Request existing OL&PDS from TM | Project Engineer | OL&PDS document |
| 1.8 | Confirm blending ratio requirements with TM (OI-002) | Project Manager | TM confirmation |

### 3.2 Phase 2: Envelope Definition

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 2.1 | Define throughput envelope (min/normal/max) | Lead Process Engineer | Flow envelope |
| 2.2 | Define pressure envelopes (suction/discharge) | Lead Process Engineer | Pressure envelope |
| 2.3 | Define temperature envelopes | Lead Process Engineer | Temperature envelope |
| 2.4 | Define blending ratio envelope (per OI-002 resolution) | Lead Process Engineer | Blending envelope |
| 2.5 | Define individual pump operating maps | Lead Process Engineer | Pump envelopes |
| 2.6 | Define VFD speed ranges | Lead Process Engineer | Speed envelope |
| 2.7 | Define operating modes and transitions | Lead Process Engineer | Mode definitions |
| 2.8 | Identify alarm and trip setpoints | Lead Process Engineer | Setpoint list |

### 3.3 Phase 3: Document Development

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.1 | Establish Operating Envelopes document structure | Lead Process Engineer | Document template |
| 3.2 | Draft operating envelope tables and figures | Lead Process Engineer | Draft content |
| 3.3 | Document constraints and limitations | Lead Process Engineer | Constraint section |
| 3.4 | Document relationship to OL&PDS | Lead Process Engineer | OL&PDS section |
| 3.5 | Document upset/abnormal condition responses | Lead Process Engineer | Upset section |
| 3.6 | Include supporting data as appendices | Lead Process Engineer | Appendices |
| 3.7 | Flag TBDs and assumptions | Lead Process Engineer | TBD/Assumption log |

### 3.4 Phase 4: Review and Verification

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 4.1 | Verify envelopes against hydraulic analysis (DEL-01.07) | Hydraulic Engineer | Verification record |
| 4.2 | Verify envelopes against transient analysis (DEL-01.08) | Safety Engineer | Verification record |
| 4.3 | Verify envelopes against pump vendor curves | Mechanical Engineer | Verification record |
| 4.4 | Verify alignment with OL&PDS | Safety Engineer | OL&PDS check |
| 4.5 | Coordinate with control narratives (DEL-07.09) | Control Systems Engineer | Control coordination |
| 4.6 | Conduct internal peer review | Assigned Reviewer | Review comments |
| 4.7 | Address review comments | Lead Process Engineer | Updated document |
| 4.8 | Obtain internal approval | Engineering Manager | Approval signature |

### 3.5 Phase 5: TM Review and Issue

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 5.1 | Issue Operating Envelopes as IFR to TM | Document Controller | Transmittal |
| 5.2 | TM Operations reviews operating envelopes | TM Operations | TM comments |
| 5.3 | Coordinate OL&PDS updates if required | Lead Process Engineer | OL&PDS change request |
| 5.4 | Address TM comments | Lead Process Engineer | Comment responses |
| 5.5 | Obtain TM Operations approval | Project Manager | TM approval |
| 5.6 | Update for vendor data finalization | Lead Process Engineer | Updated document |
| 5.7 | Issue as IFC | Document Controller | IFC transmittal |

---

## 4. Verification

### 4.1 Quality Checks

| Check | Criteria | Method | Timing |
|-------|----------|--------|--------|
| Hydraulic Consistency | Envelopes within hydraulic limits (DEL-01.07) | Cross-reference | Before IFR |
| Transient Limits | Envelopes account for transient conditions (DEL-01.08) | Cross-reference | Before IFR |
| Equipment Limits | Envelopes within equipment capabilities (DEL-01.09) | Vendor data check | Before IFR |
| Control Integration | Envelopes implementable by controls (DEL-07.09) | Control review | Before IFR |
| OL&PDS Alignment | Protective settings consistent | OL&PDS review | Before IFR |
| Operability | Envelopes are practical | Operations review | TM review |

### 4.2 Hold Points

| Hold Point | Criteria to Proceed | Authority |
|------------|---------------------|-----------|
| HP-01 | DBM (DEL-01.01) available | Engineering Lead |
| HP-02 | Hydraulic analysis (DEL-01.07) complete | Engineering Lead |
| HP-03 | Blending ratio confirmed (OI-002 resolved) | TM Engineering |
| HP-04 | Pump vendor data received | Procurement |
| HP-05 | Internal review complete | Engineering Manager |
| HP-06 | TM Operations approval | TM Operations |

### 4.3 Verification Records

| Record | Content | Retention |
|--------|---------|-----------|
| Hydraulic Check Record | Verification against hydraulic analysis (DEL-01.07) | Project duration + 7 years |
| Transient Check Record | Verification against transient analysis (DEL-01.08) | Project duration + 7 years |
| Vendor Data Comparison | Verification against pump curves | Project duration + 7 years |
| OL&PDS Alignment Record | Check against protective settings | Project duration + 7 years |
| Control Coordination Record | Coordination with control narratives (DEL-07.09) | Project duration + 7 years |

---

## 5. Records

### 5.1 Required Records

| Record | Format | Location | Responsibility |
|--------|--------|----------|----------------|
| Operating Envelopes (all revisions) | PDF + Native | Document Control | Document Controller |
| Verification Records | PDF | Document Control | Lead Process Engineer |
| TM Review Comments | PDF | Document Control | Project Engineer |
| TM Operations Approval | PDF | Document Control | Project Manager |
| OI-002 Resolution Record | PDF | Document Control | Project Manager |

### 5.2 Record Retention

| Category | Retention Period | Disposition |
|----------|------------------|-------------|
| Final Issue Documents | Permanent | Archive |
| TM Approvals | Permanent | Archive |
| Draft Documents | Project completion + 5 years | Destroy |
| Verification Records | Project completion + 7 years | Archive |

### 5.3 Document Control Requirements

- All Operating Envelopes revisions shall be issued through formal document control
- TM Operations approval required before IFC
- Native files shall be submitted per SOW-0232 requirements
- OI-002 resolution shall be documented before IFC issue

---

## 6. Appendices

### 6.1 Operating Envelopes Development Checklist

- [ ] DBM parameters obtained (DEL-01.01)
- [ ] Equipment sizing obtained (DEL-01.04)
- [ ] Hydraulic analysis results obtained (DEL-01.07)
- [ ] Transient analysis results obtained (DEL-01.08)
- [ ] Process datasheets reviewed (DEL-01.09)
- [ ] Pump vendor data obtained
- [ ] Blending ratio confirmed (OI-002 resolved)
- [ ] OL&PDS obtained
- [ ] Throughput envelope defined
- [ ] Pressure envelopes defined
- [ ] Temperature envelope defined
- [ ] Blending envelope defined
- [ ] Pump operating maps developed
- [ ] Alarm/trip setpoints defined
- [ ] Control narratives coordinated (DEL-07.09)
- [ ] OL&PDS alignment verified
- [ ] Internal review complete
- [ ] TM Operations review complete
- [ ] IFR issued
- [ ] IFC issued

### 6.2 Related Procedures

| Procedure | Reference |
|-----------|-----------|
| Document Control Procedure | PKG-00 |
| DBM Development Procedure | DEL-01.01-PR |
| Equipment Sizing Procedure | DEL-01.04-PR |
| Hydraulic Analysis Procedure | DEL-01.07-PR |
| Transient Analysis Procedure | DEL-01.08-PR |
| Control Narrative Procedure | DEL-07.09-PR |
| HAZOP Procedure | DEL-01.15-PR |

---

*End of Procedure*
