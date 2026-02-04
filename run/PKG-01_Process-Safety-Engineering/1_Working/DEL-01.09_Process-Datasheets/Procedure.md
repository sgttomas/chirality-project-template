# Procedure: DEL-01.09 Process Datasheets

**Document ID:** DEL-01.09-PR
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Purpose

### 1.1 Procedure Intent

This procedure defines the step-by-step process for developing, reviewing, and finalizing Process Datasheets for the Puget Sound Optimization (PSO) project. Following this procedure ensures complete and accurate process data transfer to Mechanical and Instrumentation disciplines for equipment specification and procurement.

### 1.2 Applicability

This procedure applies to:
- FEED phase preliminary process datasheets (per SOW-0119, SOW-0177)
- Detailed design phase complete process datasheets (per SOW-0224)
- All mechanical and instrumentation equipment within PKG-01 scope
- Packaged equipment components requiring process data

---

## 2. Prerequisites

### 2.1 Required Inputs

| Input | Source | Status Required |
|-------|--------|-----------------|
| Process Design Basis | DEL-01.01 | IFR minimum |
| Process Flow Diagrams | DEL-01.02 | IFR minimum |
| P&IDs | DEL-01.03 | IFR minimum (for tag numbers) |
| Equipment Sizing Calculations | DEL-01.04 | Required |
| Line Sizing Calculations | DEL-01.05 | Required |
| Relief Calculations | DEL-01.06 | Required (for relief devices) |
| Hydraulic Analysis | DEL-01.07 | Required (for operating data) |
| TM Datasheet Templates | TM | Required |

### 2.2 Required Standards and References

| Document | Purpose |
|----------|---------|
| API 610 | Pump datasheet format reference |
| API 526 | Relief valve datasheet format |
| API 650 | Tank datasheet format (if applicable) |
| ISA 75.01 | Control valve sizing data format |
| ISA 20 | Instrument specification forms |
| IEC 60534 | Control valve specifications |
| TM Templates | Project-specific templates (**TBD**) |

### 2.3 Required Tools

| Tool | Purpose |
|------|---------|
| Datasheet templates | Project standard format (TM or standard) |
| Spreadsheet software | Managing datasheet data |
| Physical property database | Fluid properties |

### 2.4 Personnel Requirements

| Role | Qualification |
|------|---------------|
| Process Engineer | Process datasheet development experience |
| Technical Reviewer | Peer review |
| Mechanical/I&C Engineers | Discipline review for adequacy |

---

## 3. Steps

### 3.1 Phase 1: Preparation

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 1.1 | Obtain TM datasheet templates (or confirm standard templates) | Lead Engineer | Approved templates |
| 1.2 | Compile equipment list from P&IDs (DEL-01.03) | Process Engineer | Equipment list |
| 1.3 | Cross-reference with DEL-01.04 equipment sizing | Process Engineer | Sizing data |
| 1.4 | Cross-reference with DEL-01.07 hydraulic analysis | Process Engineer | Operating data |
| 1.5 | Establish datasheet numbering convention | Process Engineer | Numbering convention |
| 1.6 | Coordinate with Mechanical/I&C on data requirements | Process Engineer | Requirements confirmation |

### 3.2 Phase 2: Data Compilation

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 2.1 | Extract design conditions from DEL-01.01 DBM | Process Engineer | Design basis data |
| 2.2 | Extract operating conditions from DEL-01.07 hydraulic analysis | Process Engineer | Operating data |
| 2.3 | Extract equipment sizing parameters from DEL-01.04 | Process Engineer | Sizing parameters |
| 2.4 | Extract valve sizing parameters from DEL-01.05 line sizing | Process Engineer | Valve sizing data |
| 2.5 | Extract relief device parameters from DEL-01.06 | Process Engineer | Relief device data |
| 2.6 | Compile fluid properties at relevant conditions | Process Engineer | Property data |

### 3.3 Phase 3: Datasheet Population

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.1 | Populate pump process datasheets | Process Engineer | Pump datasheets |
| 3.2 | Populate control valve process datasheets | Process Engineer | Control valve datasheets |
| 3.3 | Populate block valve process datasheets | Process Engineer | Block valve datasheets |
| 3.4 | Populate relief device process datasheets | Process Engineer | Relief device datasheets |
| 3.5 | Populate flow meter process datasheets | Process Engineer | Flow meter datasheets |
| 3.6 | Populate other instrument process datasheets | Process Engineer | Instrument datasheets |
| 3.7 | Populate tank/vessel process datasheets (if applicable) | Process Engineer | Vessel datasheets |
| 3.8 | Review each datasheet for completeness | Process Engineer | Completed datasheets |

### 3.4 Phase 4: Internal Review

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 4.1 | Perform self-check for completeness | Process Engineer | Self-check record |
| 4.2 | Cross-check against source documents (DEL-01.01/04/05/06/07) | Process Engineer | Cross-check record |
| 4.3 | Verify tag numbers match P&IDs (DEL-01.03) | Process Engineer | Tag verification |
| 4.4 | Peer review by second process engineer | Peer Reviewer | Review comments |
| 4.5 | Address peer review comments | Process Engineer | Revised datasheets |

### 3.5 Phase 5: Discipline Review

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 5.1 | Issue datasheets to Mechanical discipline for review | Process Engineer | Transmittal |
| 5.2 | Mechanical review for data adequacy | Mechanical Engineer | Review comments |
| 5.3 | Issue datasheets to I&C discipline for review | Process Engineer | Transmittal |
| 5.4 | I&C review for data adequacy | I&C Engineer | Review comments |
| 5.5 | Address discipline review comments | Process Engineer | Revised datasheets |
| 5.6 | Confirm disciplines have adequate data | Process Engineer | Confirmation record |

### 3.6 Phase 6: Finalization and Issue

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 6.1 | Discipline lead review and approval | Discipline Lead | Approval |
| 6.2 | Prepare datasheet index | Process Engineer | Datasheet index |
| 6.3 | Submit for TM review | Lead Engineer | Transmittal |
| 6.4 | Address TM comments | Process Engineer | Comment responses |
| 6.5 | Finalize and issue datasheets | Process Engineer | Final datasheet set |
| 6.6 | Distribute to Mechanical/I&C for use | Process Engineer | Distribution record |

### 3.7 Phase 7: Updates and Revisions

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 7.1 | Track design changes affecting datasheets | Process Engineer | Change log |
| 7.2 | Update datasheets for vendor data (when available) | Process Engineer | Updated datasheets |
| 7.3 | Update datasheets for HAZOP findings | Process Engineer | Updated datasheets |
| 7.4 | Issue revised datasheets per project milestones (IFD/IFC) | Process Engineer | IFD/IFC issues |

---

## 4. Verification

### 4.1 Completeness Checklist (Per Datasheet)

| Check Item | Verified | Date |
|------------|----------|------|
| Equipment tag number correct | [ ] | |
| P&ID reference included | [ ] | |
| Normal operating conditions complete | [ ] | |
| Min/Max operating conditions complete | [ ] | |
| Design conditions complete | [ ] | |
| Fluid properties included (density, viscosity, vapor pressure) | [ ] | |
| Corrosivity/special characteristics documented | [ ] | |
| Hazardous area classification included | [ ] | |
| Reference to source calculations (DEL-01.04/05/06/07) | [ ] | |
| All required fields populated | [ ] | |
| Units consistent and correct | [ ] | |

### 4.2 Consistency Verification

| Check Item | Verified | Date |
|------------|----------|------|
| Data consistent with DEL-01.01 DBM (design conditions) | [ ] | |
| Data consistent with DEL-01.07 hydraulic analysis (operating conditions) | [ ] | |
| Data consistent with DEL-01.04 equipment sizing | [ ] | |
| Data consistent with DEL-01.05 line sizing | [ ] | |
| Data consistent with DEL-01.06 relief calculations (relief devices) | [ ] | |
| Tag numbers match P&IDs (DEL-01.03) | [ ] | |
| Related datasheets consistent with each other | [ ] | |

### 4.3 Approval Requirements

| Approval Stage | Approver | Signature |
|----------------|----------|-----------|
| Peer Review | Second Process Engineer | Required |
| Mechanical Review | Mechanical Engineer | Required |
| I&C Review | I&C Engineer | Required (instruments) |
| Discipline Review | Process Lead | Required |
| Client Review | TM Representative | Per contract |

---

## 5. Records

### 5.1 Deliverable Documents

| Document | Format | Retention |
|----------|--------|-----------|
| Process Datasheet Set | PDF + native files (Excel or Word) | Project + 7 years |
| Datasheet Index | Excel | Project + 7 years |
| Superseded Revisions | PDF | Project + 7 years |

### 5.2 Quality Records

| Record | Location | Retention |
|--------|----------|-----------|
| Discipline Review Records | Document Control | Project + 7 years |
| Cross-Check Records | Document Control | Project + 7 years |
| TM Review Comments | Document Control | Project + 7 years |
| Approval Signatures | Within documents | Permanent |

### 5.3 Revision History

| Revision | Date | Description | By | Checked | Approved |
|----------|------|-------------|-----|---------|----------|
| Pass 1 | 2026-02-01 | Initial draft | **TBD** | **TBD** | **TBD** |
| Pass 2 | 2026-02-01 | Cross-reference consistency check | **TBD** | **TBD** | **TBD** |
| A | **TBD** | IFR Issue (preliminary datasheets) | **TBD** | **TBD** | **TBD** |
| 0 | **TBD** | IFD Issue (complete datasheets) | **TBD** | **TBD** | **TBD** |
| 1 | **TBD** | IFC Issue (final datasheets with vendor data) | **TBD** | **TBD** | **TBD** |

---

*End of Procedure*
