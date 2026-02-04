# Procedure: DEL-01.05 Line Sizing Calculations

**Document ID:** DEL-01.05-PR
**Revision:** Phase 2.2 (INITIALIZED)
**Date:** 2026-02-01
**Status:** INITIALIZED

---

## Purpose

### Procedure Objective

This procedure defines the step-by-step process for developing, reviewing, and issuing Line Sizing Calculations for the Puget Sound Optimization project at Sumas Tank Farm.

### Scope

This procedure covers:
- Line sizing calculation development from initiation through IFC
- Hydraulic optimization coordination per SOW-0130
- Internal review and TM approval processes
- Coordination with related deliverables (equipment sizing, hydraulic analysis, line list)

---

## Prerequisites

### Required Inputs

| Input | Source | Status |
|-------|--------|--------|
| Design Basis Memorandum (DBM) | DEL-01.01 | Required before calculations |
| Hydraulic Analysis Data | DEL-01.07 | Required (concurrent development) |
| Preliminary Hydraulic Report | Appendix C | Available - reference |
| PFDs | DEL-01.02 | Required for process overview |
| Equipment Sizing | DEL-01.04 | Concurrent - for coordination |
| Fluid Properties | DEL-01.01 / TM | **TBD** |
| TMP Standards (Piping) | Attachment A08 | **TBD** - Not in workspace |

### Required Resources

| Resource | Role |
|----------|------|
| Lead Process Engineer | Calculation Owner, technical content |
| Process Engineers | Supporting calculations |
| Piping Engineer | Piping class input, stress coordination |
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
| 1.3 | Coordinate with DEL-01.07 for pressure drop budget | Lead Process Engineer | dP budget |
| 1.4 | Obtain TMP Standards (Attachment A08) for velocity/sizing criteria (when available) | Document Controller | Standards reference |
| 1.5 | Coordinate with DEL-01.04 for manifold header sizing | Lead Process Engineer | Equipment sizing inputs |
| 1.6 | Obtain document number from TM Document Control | Document Controller | Assigned document number |
| 1.7 | Establish calculation report structure | Lead Process Engineer | Report template |

### Phase 2: Establish Sizing Criteria

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 2.1 | Define velocity limits by line category (suction/discharge/headers) | Lead Process Engineer | Velocity criteria table |
| 2.2 | Define pressure drop allowances per line category | Lead Process Engineer | dP criteria |
| 2.3 | Define pipe class designations per service and P/T | Piping Engineer | Pipe class list |
| 2.4 | Document criteria sources and any assumptions | Lead Process Engineer | Criteria documentation |

### Phase 3: Tank and Manifold Header Sizing

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.1 | Calculate tank suction header sizes (peak flow, low velocity) | Process Engineer | Header sizing |
| 3.2 | Calculate manifold inlet header sizes (5 inlet headers per SOW §2.3.1.1) | Process Engineer | Inlet header sizing |
| 3.3 | Calculate manifold outlet header sizes (6 outlet headers per SOW §2.3.1.1) | Process Engineer | Outlet header sizing |
| 3.4 | Verify velocities within limits | Process Engineer | Velocity check |
| 3.5 | Calculate pressure drops | Process Engineer | dP calculations |
| 3.6 | Coordinate manifold sizing with DEL-01.04 | Lead Process Engineer | Coordination record |

### Phase 4: Pump Line Sizing

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 4.1 | Calculate pump suction line sizes (5 lines - NPSH priority) | Process Engineer | Suction line sizing |
| 4.2 | Verify suction line velocities (low per NPSH) | Process Engineer | Velocity check |
| 4.3 | Calculate pump discharge line sizes (5 lines) | Process Engineer | Discharge line sizing |
| 4.4 | Verify discharge line velocities within limits | Process Engineer | Velocity check |
| 4.5 | Calculate discharge header sizes (combined flow) | Process Engineer | Discharge header sizing |
| 4.6 | Calculate pressure drops for pump lines | Process Engineer | dP calculations |

### Phase 5: Blending and Auxiliary Line Sizing

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 5.1 | Calculate blending line sizes (Heavy/Light per SOW §2.3.1.4) | Process Engineer | Blending line sizing |
| 5.2 | Consider blending turndown requirements | Process Engineer | Turndown analysis |
| 5.3 | Calculate auxiliary line sizes (sump, reinjection per SOW §3.2.3.10) | Process Engineer | Auxiliary sizing |
| 5.4 | Calculate drain and vent line sizes | Process Engineer | D&V sizing |

### Phase 6: Documentation and Internal Review

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 6.1 | Compile line sizing summary table | Lead Process Engineer | Summary table |
| 6.2 | Document all assumptions with basis and status | Lead Process Engineer | Assumptions log |
| 6.3 | Document all TBDs with required inputs and timing | Lead Process Engineer | TBD log |
| 6.4 | Compile calculation report per established structure | Lead Process Engineer | Draft calculation report |
| 6.5 | Conduct internal technical review | Assigned Reviewer | Review comments |
| 6.6 | Conduct interdisciplinary review (Piping PKG-02) | Piping Lead | IDC comments |
| 6.7 | Address review comments | Lead Process Engineer | Updated calculations |
| 6.8 | Verify consistency with DEL-01.07 hydraulic analysis | Lead Process Engineer | Verification record |
| 6.9 | Obtain internal approval | Engineering Manager | Approval signature |

### Phase 7: Client Review (IFR)

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 7.1 | Issue calculation report as IFR to TM per SOW §3.1.2.2 | Document Controller | Transmittal |
| 7.2 | Track TM review timeline | Project Engineer | Status updates |
| 7.3 | Receive and log TM comments | Document Controller | Comment register |
| 7.4 | Address TM comments | Lead Process Engineer | Comment responses |
| 7.5 | Update calculations based on comments | Lead Process Engineer | Revised calculations |

### Phase 8: IFD Issue

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 8.1 | Resolve all IFR comments | Lead Process Engineer | Comment closeout |
| 8.2 | Update with finalized DEL-01.07 hydraulic data | Lead Process Engineer | Updated calculations |
| 8.3 | Conduct final internal review | Engineering Manager | Final approval |
| 8.4 | Obtain TM approval for IFD | Project Manager | TM approval |
| 8.5 | Issue calculation report as IFD (end of FEED) | Document Controller | IFD transmittal |
| 8.6 | Provide sizing data to DEL-02.01 (Line List) | Lead Process Engineer | Line list input |

### Phase 9: Detailed Design Updates and IFC Issue

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 9.1 | Update for hydraulic optimization findings per SOW-0130 | Lead Process Engineer | Updated calculations |
| 9.2 | Incorporate vendor data updates | Lead Process Engineer | Updated calculations |
| 9.3 | Finalize all TBDs | Lead Process Engineer | Completed calculations |
| 9.4 | Verify final consistency with DEL-02.01 (Line List) | Lead Process Engineer | Verification record |
| 9.5 | Conduct IFC internal review | Engineering Manager | Final approval |
| 9.6 | Obtain TM approval for IFC | Project Director | TM approval |
| 9.7 | Issue calculation report as IFC | Document Controller | IFC transmittal |

---

## Verification

### Quality Checks

| Check | Criteria | Method | Timing |
|-------|----------|--------|--------|
| Design Basis Consistency | Inputs match DEL-01.01 | Cross-reference | Before IFR |
| Hydraulic Data Consistency | Inputs match DEL-01.07 | Cross-reference | Before IFR |
| Velocity Compliance | All velocities within limits | Calculation review | Before IFR |
| Pressure Drop | Within hydraulic budget | Cross-reference | Before IFR |
| Manifold Configuration | Supports 5x6 (5 inlet, 6 outlet) per SOW §2.3.1.1 | Calculation review | Before IFR |
| TBD Resolution | All TBDs resolved or justified | TBD log review | Before IFC |
| Line List Alignment | Consistent with DEL-02.01 | Cross-reference | Before IFC |

### Hold Points

| Hold Point | Criteria to Proceed | Authority |
|------------|---------------------|-----------|
| HP-01 | DBM (DEL-01.01) available | Lead Process Engineer |
| HP-02 | Hydraulic data from DEL-01.07 available | Lead Process Engineer |
| HP-03 | Velocity criteria established | Lead Process Engineer |
| HP-04 | Internal review complete | Engineering Manager |
| HP-05 | TM IFR comments resolved | Project Manager |
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
| Line Size Summary Table | Excel/PDF | Deliverable folder | Lead Process Engineer |
| Assumptions Log | Excel/PDF | Deliverable folder | Lead Process Engineer |
| Review Comments | Excel/PDF | Document Control | Lead Process Engineer |
| Transmittals | PDF | Document Control | Document Controller |

### Record Retention

| Category | Retention Period | Disposition |
|----------|------------------|-------------|
| IFC Calculations | Permanent | Archive |
| Superseded Calculations | Project completion + 5 years | Destroy |
| Review Records | Project completion + 7 years | Archive |

### Native File Requirements

Per SOW-0231:
- Submit editable native files (Excel/MathCAD)
- Include all referenced data and formulas
- Include corresponding PDF reports

---

## Appendices

### Line Sizing Calculation Checklist

- [ ] DBM (DEL-01.01) obtained and reviewed
- [ ] Hydraulic data from DEL-01.07 obtained (or Appendix C as interim)
- [ ] Velocity criteria established
- [ ] Pressure drop budget established
- [ ] Tank suction header sizing complete
- [ ] Manifold header sizing complete (5 inlet, 6 outlet)
- [ ] Pump suction line sizing complete (5 lines)
- [ ] Pump discharge line sizing complete (5 lines)
- [ ] Discharge header sizing complete
- [ ] Blending line sizing complete
- [ ] Auxiliary line sizing complete
- [ ] Assumptions documented
- [ ] TBDs logged
- [ ] Internal review complete
- [ ] IDC review complete (Piping)
- [ ] IFR issued
- [ ] TM comments addressed
- [ ] IFD issued
- [ ] Data provided to DEL-02.01 (Line List)
- [ ] IFC issued

### Related Procedures

| Procedure | Reference |
|-----------|-----------|
| Document Control Procedure | DEL-00.01 |
| Change Management Procedure | DEL-00.04 |
| Calculation Verification Procedure | Standard |

---

*End of Procedure*
