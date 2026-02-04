# Procedure: DEL-01.04 Equipment Sizing Calculations

**Document ID:** DEL-01.04-PR
**Revision:** Phase 2.2 (PASS2-COMPLETE)
**Date:** 2026-02-01
**Status:** PASS2-COMPLETE

---

## Purpose

### Procedure Objective

This procedure defines the step-by-step process for developing, reviewing, and issuing Equipment Sizing Calculations for the Puget Sound Optimization project at Sumas Tank Farm.

### Scope

This procedure covers:
- Equipment sizing calculation development from initiation through IFC
- Verification of preliminary sizing per SOW §2.3.1.6
- Internal review and TM approval processes
- Coordination with related deliverables (DEL-01.05 Line Sizing, DEL-01.07 Hydraulic Analysis)

---

## Prerequisites

### Required Inputs

| Input | Source | Status |
|-------|--------|--------|
| Design Basis Memorandum (DBM) | DEL-01.01 | Required before calculations |
| Hydraulic Analysis Data | DEL-01.07 | Required (concurrent development) |
| Preliminary Hydraulic Report | Appendix C | Available - reference |
| PFDs | DEL-01.02 | Required for process overview |
| Fluid Properties | DEL-01.01 / TM | **TBD** |
| TMP Standards | Attachment A08 | **TBD** - Not in workspace |
| Existing Engineering (Preliminary) | TM | Per SOW §2.3.1.6 - for verification |

### Required Resources

| Resource | Role |
|----------|------|
| Lead Process Engineer | Calculation Owner, technical content |
| Process Engineers | Supporting calculations |
| Mechanical Engineer | Pump/equipment input |
| I&C Engineer | Flow meter input |
| Document Controller | Document management |

### Required Authorizations

| Authorization | Authority | Required For |
|---------------|-----------|--------------|
| Calculation Template Approval | Engineering Manager | Start of calculations |
| IFR Release | Engineering Manager | IFR submission |
| IFD Release | Engineering Manager + TM | IFD issue |
| IFC Release | Project Director + TM | IFC issue |

---

## Steps

### Phase 1: Preparation and Data Gathering

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 1.1 | Obtain design basis from DEL-01.01 (flow rates, P/T, fluid properties) | Lead Process Engineer | Design basis extract |
| 1.2 | Obtain/review preliminary hydraulic data from Appendix C | Lead Process Engineer | Hydraulic data summary |
| 1.3 | Coordinate with DEL-01.07 for hydraulic analysis inputs (TDH, NPSH, system curve) | Lead Process Engineer | Hydraulic inputs |
| 1.4 | Review existing preliminary engineering per SOW §2.3.1.6 | Lead Process Engineer | Preliminary sizing review |
| 1.5 | Obtain TMP Standards (Attachment A08) if available | Document Controller | Standards reference |
| 1.6 | Obtain document number from TM Document Control | Document Controller | Assigned document number |
| 1.7 | Establish calculation report structure | Lead Process Engineer | Report template |

### Phase 2: Booster Pump Sizing

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 2.1 | Define pump duty allocation (2L+2S+1M per SOW §2.3.1.2) | Lead Process Engineer | Duty allocation table |
| 2.2 | Calculate flow requirements for each pump type (total 315,000 bpd / 2,100 m³/h) | Process Engineer | Flow calculations |
| 2.3 | Calculate TDH requirements using DEL-01.07 data | Process Engineer | Head calculations |
| 2.4 | Calculate NPSH available based on suction conditions | Process Engineer | NPSH calculations |
| 2.5 | Determine hydraulic power and efficiency requirements | Process Engineer | Power calculations |
| 2.6 | Select preliminary pump sizes based on calculations | Lead Process Engineer | Pump selection summary |
| 2.7 | Compare with preliminary engineering and document differences | Lead Process Engineer | Comparison table |

### Phase 3: VFD and Flow Meter Sizing

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.1 | Calculate motor power requirements for each pump | Process Engineer | Motor sizing |
| 3.2 | Determine VFD speed range requirements (turndown for blending) | Process Engineer | VFD requirements |
| 3.3 | Size VFDs for each pump (5 total) per SOW §2.3.1.4 | Process Engineer | VFD sizing |
| 3.4 | Calculate flow meter range requirements per pump discharge (5 total) | Process Engineer | Flow range calculations |
| 3.5 | Determine flow meter accuracy requirements for blending control | I&C Engineer | Accuracy requirements |
| 3.6 | Select preliminary flow meter types | I&C Engineer | Meter selection |

### Phase 4: Manifold and Auxiliary Equipment Sizing

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 4.1 | Calculate manifold header sizes (5x6 configuration) based on velocity limits | Process Engineer | Header sizing |
| 4.2 | Calculate manifold pressure drops | Process Engineer | Pressure drop calculations |
| 4.3 | Size control valves for blending (if applicable) | Process Engineer | Control valve sizing |
| 4.4 | Size sump tank per SOW §3.2.3.10 requirements | Process Engineer | Sump sizing |
| 4.5 | Size reinjection pumps per SOW §3.2.3.10 | Process Engineer | Reinjection pump sizing |
| 4.6 | Coordinate header sizing with DEL-01.05 (Line Sizing) | Lead Process Engineer | Coordination record |

### Phase 5: Documentation and Internal Review

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 5.1 | Document all assumptions with basis and status | Lead Process Engineer | Assumptions log |
| 5.2 | Document all TBDs with required inputs and timing | Lead Process Engineer | TBD log |
| 5.3 | Compile calculation report per established structure | Lead Process Engineer | Draft calculation report |
| 5.4 | Prepare equipment selection summary table | Lead Process Engineer | Selection summary |
| 5.5 | Conduct internal technical review | Assigned Reviewer | Review comments |
| 5.6 | Conduct interdisciplinary review (Mechanical, I&C, Electrical) | Discipline Leads | IDC comments |
| 5.7 | Address review comments | Lead Process Engineer | Updated calculations |
| 5.8 | Obtain internal approval | Engineering Manager | Approval signature |

### Phase 6: Client Review (IFR)

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 6.1 | Issue calculation report as IFR to TM per SOW §3.1.2.2 | Document Controller | Transmittal |
| 6.2 | Track TM review timeline | Project Engineer | Status updates |
| 6.3 | Receive and log TM comments | Document Controller | Comment register |
| 6.4 | Address TM comments | Lead Process Engineer | Comment responses |
| 6.5 | Update calculations based on comments | Lead Process Engineer | Revised calculations |

### Phase 7: IFD Issue

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 7.1 | Resolve all IFR comments | Lead Process Engineer | Comment closeout |
| 7.2 | Update with finalized DEL-01.07 hydraulic data | Lead Process Engineer | Updated calculations |
| 7.3 | Conduct final internal review | Engineering Manager | Final approval |
| 7.4 | Obtain TM approval for IFD | Project Manager | TM approval |
| 7.5 | Issue calculation report as IFD (end of FEED) | Document Controller | IFD transmittal |

### Phase 8: Detailed Design Updates and IFC Issue

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 8.1 | Incorporate vendor data updates | Lead Process Engineer | Updated calculations |
| 8.2 | Incorporate HAZOP findings (if applicable) | Lead Process Engineer | Updated calculations |
| 8.3 | Finalize all TBDs | Lead Process Engineer | Completed calculations |
| 8.4 | Verify consistency with DEL-01.09 (Process Datasheets) | Lead Process Engineer | Verification record |
| 8.5 | Conduct IFC internal review | Engineering Manager | Final approval |
| 8.6 | Obtain TM approval for IFC | Project Director | TM approval |
| 8.7 | Issue calculation report as IFC | Document Controller | IFC transmittal |
| 8.8 | Register in MDR per DEL-00.01 | Document Controller | MDR entry |

---

## Verification

### Quality Checks

| Check | Criteria | Method | Timing |
|-------|----------|--------|--------|
| Design Basis Consistency | Inputs match DEL-01.01 (DBM) | Cross-reference | Before IFR |
| Hydraulic Data Consistency | Inputs match DEL-01.07 (Hydraulic Analysis) | Cross-reference | Before IFR |
| Pump Configuration | Supports 2L+2S+1M per SOW §2.3.1.2 | Calculation review | Before IFR |
| VFD/Flow Meter Per Pump | 5 VFDs, 5 flow meters per SOW §2.3.1.4 | Calculation review | Before IFR |
| Preliminary Verification | Compared with existing engineering | Documentation review | Before IFD |
| TBD Resolution | All TBDs resolved or justified | TBD log review | Before IFC |

### Hold Points

| Hold Point | Criteria to Proceed | Authority |
|------------|---------------------|-----------|
| HP-01 | DBM (DEL-01.01) available | Lead Process Engineer |
| HP-02 | Hydraulic data from DEL-01.07 available | Lead Process Engineer |
| HP-03 | Internal review complete | Engineering Manager |
| HP-04 | TM IFR comments resolved | Project Manager |
| HP-05 | Vendor data incorporated | Lead Process Engineer |
| HP-06 | TM IFC approval received | Project Director |

### Verification Records

| Record | Content | Retention |
|--------|---------|-----------|
| Review Checklist | Completed quality checks | Project duration + 7 years |
| Comment Register | All comments and responses | Project duration + 7 years |
| Cross-Reference Verification | Comparison to DEL-01.01, DEL-01.07 | Project duration + 7 years |

---

## Records

### Required Records

| Record | Format | Location | Responsibility |
|--------|--------|----------|----------------|
| Calculation Report (all revisions) | PDF + Native | TM Document Control | Document Controller |
| Native Calculation Files | Excel/MathCAD | Document Control | Lead Process Engineer |
| Assumptions Log | Excel/PDF | Deliverable folder | Lead Process Engineer |
| Review Comments | Excel/PDF | Document Control | Lead Process Engineer |
| Transmittals | PDF | Document Control | Document Controller |
| Approval Records | PDF | Document Control | Project Engineer |

### Record Retention

| Category | Retention Period | Disposition |
|----------|------------------|-------------|
| IFC Calculations | Permanent | Archive |
| Superseded Calculations | Project completion + 5 years | Destroy |
| Review Records | Project completion + 7 years | Archive |

### Native File Requirements

Per SOW §3.2.3.18:
- Submit editable native files (Excel/MathCAD/Word)
- Include all referenced data and formulas
- Include corresponding PDF reports

---

## Appendices

### Equipment Sizing Calculation Checklist

- [ ] DBM (DEL-01.01) obtained and reviewed
- [ ] Hydraulic data from DEL-01.07 obtained (or Appendix C as interim)
- [ ] Preliminary engineering reviewed per SOW §2.3.1.6
- [ ] Pump duty allocation defined (2L+2S+1M)
- [ ] Pump sizing calculations complete (5 pumps total)
- [ ] VFD sizing calculations complete (5 units per SOW §2.3.1.4)
- [ ] Flow meter sizing calculations complete (5 units per SOW §2.3.1.4)
- [ ] Manifold header sizing complete (5x6 configuration)
- [ ] Auxiliary equipment sizing complete (sump, reinjection)
- [ ] Assumptions documented
- [ ] TBDs logged
- [ ] Internal review complete
- [ ] IDC review complete
- [ ] IFR issued
- [ ] TM comments addressed
- [ ] IFD issued
- [ ] Vendor data incorporated
- [ ] IFC issued
- [ ] Registered in MDR per DEL-00.01

### Related Procedures

| Procedure | Reference |
|-----------|-----------|
| Document Control Procedure | DEL-00.01 (MDR) |
| Change Management Procedure | DEL-00.04 (Design Change Control) |
| Calculation Verification Procedure | Standard |

---

*End of Procedure*
