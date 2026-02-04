# Procedure: DEL-01.06 Pressure Relief / Thermal Relief Calculations

**Document ID:** DEL-01.06-PR
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Purpose

### 1.1 Procedure Intent

This procedure defines the step-by-step process for developing, reviewing, and finalizing Pressure Relief and Thermal Relief Calculations for the Puget Sound Optimization (PSO) project. Following this procedure ensures systematic identification of relief requirements, consistent calculation methodology, and compliance with applicable codes and standards.

### 1.2 Applicability

This procedure applies to:
- FEED phase relief device need verification and preliminary sizing
- Detailed design phase final sizing and specification
- All PRV and TRV calculations within PKG-01 scope

---

## 2. Prerequisites

### 2.1 Required Inputs

| Input | Source | Status Required |
|-------|--------|-----------------|
| Process Design Basis | DEL-01.01 | Approved or IFR |
| Process Flow Diagrams | DEL-01.02 | IFR minimum |
| P&IDs | DEL-01.03 | IFR minimum |
| Equipment Sizing Calculations | DEL-01.04 | Concurrent acceptable |
| Line Sizing Calculations | DEL-01.05 | Concurrent acceptable |
| Hydraulic Analysis | DEL-01.07 | Concurrent acceptable |
| Transient Analysis | DEL-01.08 | Concurrent acceptable |
| Process Datasheets | DEL-01.09 | Concurrent acceptable |
| Equipment MAWP Data | PKG-03 Equipment Datasheets | Required |

### 2.2 Required Standards and References

| Document | Purpose |
|----------|---------|
| API 520 Part I | Sizing methodology |
| API 520 Part II | Installation requirements |
| API 521 | Scenario identification, system design |
| API 526 | Standard orifice designations |
| CSA Z662 | Pipeline relief requirements |
| TM Standards | Project-specific requirements (**TBD**) |

### 2.3 Required Tools

| Tool | Purpose |
|------|---------|
| Calculation software | Relief sizing (Excel/Mathcad or specialized) |
| Calculation template | Project-standard format |
| Physical property database | Fluid properties at relieving conditions |
| P&ID markup tools | Identifying relief locations |

### 2.4 Personnel Requirements

| Role | Qualification |
|------|---------------|
| Lead Process Engineer | Relief device sizing experience |
| Technical Reviewer | Independent engineer, relief calculation experience |
| Checker | Arithmetic verification |

---

## 3. Steps

### 3.1 Phase 1: Preparation and Data Gathering

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 1.1 | Obtain current revision P&IDs and PFDs | Process Engineer | Document set |
| 1.2 | Mark up P&IDs to identify all potential relief locations | Process Engineer | Marked P&IDs |
| 1.3 | Compile equipment list with design pressures (MAWP) | Process Engineer | Equipment list |
| 1.4 | Obtain process conditions from DEL-01.07 hydraulic analysis | Process Engineer | Operating data |
| 1.5 | Obtain fluid physical properties at design conditions | Process Engineer | Property data |
| 1.6 | Identify discharge system configuration (atmospheric/closed) | Process Engineer | Backpressure data |
| 1.7 | Establish set pressure basis for each device | Process Engineer | Set pressure table |

### 3.2 Phase 2: Relief Scenario Identification

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 2.1 | Complete API 521 scenario checklist for each location | Process Engineer | Completed checklists |
| 2.2 | Identify thermal relief requirements for blocked-in liquid | Process Engineer | TRV location list |
| 2.3 | Review HAZOP preliminary findings for additional scenarios | Process Engineer | HAZOP scenarios |
| 2.4 | Document all credible scenarios per device | Process Engineer | Scenario summary |
| 2.5 | Determine governing (worst-case) scenario for each device | Process Engineer | Governing case selection |

### 3.3 Phase 3: Relief Device Sizing Calculations

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.1 | Prepare calculation cover sheet with project information | Process Engineer | Cover sheet |
| 3.2 | Document all assumptions clearly | Process Engineer | Assumptions section |
| 3.3 | Calculate required relief rate for governing scenario | Process Engineer | Relief rate calculation |
| 3.4 | Select relief device type (conventional, balanced, pilot) | Process Engineer | Device type selection |
| 3.5 | Size orifice per API 520 methodology | Process Engineer | Orifice sizing |
| 3.6 | Select next larger standard orifice per API 526 | Process Engineer | Selected orifice |
| 3.7 | Calculate inlet piping pressure drop (verify <= 3% of set pressure) | Process Engineer | Inlet dP verification |
| 3.8 | Calculate outlet piping built-up backpressure | Process Engineer | Backpressure calculation |
| 3.9 | Verify built-up backpressure within device limits (10% for conventional) | Process Engineer | Backpressure compliance |

### 3.4 Phase 4: Thermal Relief Calculations

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 4.1 | Identify blocked-in liquid volumes | Process Engineer | Volume data |
| 4.2 | Calculate thermal expansion rate | Process Engineer | Expansion rate |
| 4.3 | Size TRV for liquid relief per API 520 | Process Engineer | TRV sizing |
| 4.4 | Verify set pressure below lowest connected MAWP | Process Engineer | Set pressure verification |
| 4.5 | Document TRV specifications | Process Engineer | TRV summary |

### 3.5 Phase 5: Documentation and Summary

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 5.1 | Compile all calculations into calculation package | Process Engineer | Calculation package |
| 5.2 | Prepare relief device summary table | Process Engineer | Summary table |
| 5.3 | Cross-reference with P&IDs for device tags | Process Engineer | Tag verification |
| 5.4 | Complete table of contents and appendices | Process Engineer | Final document |

### 3.6 Phase 6: Review and Finalization

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 6.1 | Perform calculation self-check | Process Engineer | Self-check record |
| 6.2 | Submit for independent technical review | Process Engineer | Review submission |
| 6.3 | Technical reviewer performs calculation check | Technical Reviewer | Review comments |
| 6.4 | Address review comments | Process Engineer | Revised calculations |
| 6.5 | Obtain discipline lead approval | Discipline Lead | Approval signature |
| 6.6 | Submit for TM review | Lead Engineer | Transmittal |
| 6.7 | Address TM comments | Process Engineer | Comment responses |
| 6.8 | Finalize and issue | Process Engineer | Final issue |

---

## 4. Verification

### 4.1 Self-Check Checklist

| Check Item | Verified | Date |
|------------|----------|------|
| All relief locations from P&IDs addressed | [ ] | |
| All credible scenarios evaluated per API 521 | [ ] | |
| Governing scenario correctly identified | [ ] | |
| Input data traceable to source documents | [ ] | |
| Physical properties at correct conditions | [ ] | |
| Correct API 520 equations applied | [ ] | |
| Standard orifice size selected (API 526) | [ ] | |
| Inlet piping meets 3% of set pressure rule (API 520 Part II) | [ ] | |
| Built-up backpressure within device limits (10% for conventional PRVs) | [ ] | |
| Thermal relief locations identified | [ ] | |
| Set pressures appropriate | [ ] | |
| Units consistent throughout | [ ] | |
| Arithmetic verified | [ ] | |

### 4.2 Technical Review Requirements

| Review Element | Requirement |
|----------------|-------------|
| Methodology | Correct application of API 520/521 |
| Scenario completeness | All credible scenarios addressed |
| Input data | Verified against source documents |
| Calculations | Arithmetic checked |
| Results | Reasonable and conservative |

### 4.3 Approval Requirements

| Approval Stage | Approver | Signature |
|----------------|----------|-----------|
| Technical Review | Independent Engineer | Required |
| Discipline Review | Process Lead | Required |
| Client Review | TM Representative | Per contract |

---

## 5. Records

### 5.1 Deliverable Documents

| Document | Format | Retention |
|----------|--------|-----------|
| Calculation Report(s) | PDF + native files | Project + 7 years |
| Relief Device Summary Table | Excel/PDF | Project + 7 years |
| Review Comment Log | Excel/PDF | Project + 7 years |
| Superseded Revisions | PDF | Project + 7 years |

### 5.2 Quality Records

| Record | Location | Retention |
|--------|----------|-----------|
| Self-Check Records | Calculation package | Project + 7 years |
| Technical Review Records | Document Control | Project + 7 years |
| TM Review Comments | Document Control | Project + 7 years |
| Approval Signatures | Within document | Permanent |

### 5.3 Revision History

| Revision | Date | Description | By | Checked | Approved |
|----------|------|-------------|-----|---------|----------|
| Pass 1 | 2026-02-01 | Initial draft | **TBD** | **TBD** | **TBD** |
| Pass 2 | 2026-02-01 | Cross-reference consistency check | **TBD** | **TBD** | **TBD** |
| A | **TBD** | IFR Issue | **TBD** | **TBD** | **TBD** |
| 0 | **TBD** | IFD Issue | **TBD** | **TBD** | **TBD** |
| 1 | **TBD** | IFC Issue | **TBD** | **TBD** | **TBD** |

---

*End of Procedure*
