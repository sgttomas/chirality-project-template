# Procedure: DEL-01.12 Battery Limit Table

**Document ID:** DEL-01.12-PR
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Purpose

### 1.1 Procedure Objective

This procedure defines the step-by-step process for developing, reviewing, and issuing the Battery Limit Table for the Puget Sound Optimization project. This procedure works in conjunction with DEL-00.05 Interface Management Plan and DEL-00.06 Interface Register/Schedule.

### 1.2 Scope

This procedure covers:
- Interface identification and definition
- Battery Limit Table development
- Coordination with related deliverables (DEL-01.01, DEL-01.03, DEL-01.07, DEL-02.01, DEL-02.03)
- TM verification of interface conditions
- Internal review and approval
- Revision and update management

---

## 2. Prerequisites

### 2.1 Required Inputs

| Input | Source | Status |
|-------|--------|--------|
| Process Design Basis Memorandum | DEL-01.01 | Required before start |
| P&IDs (preliminary) | DEL-01.03 | Required for interface locations |
| Hydraulic Analysis (preliminary) | DEL-01.07 | Required for pressure/flow conditions |
| Line List (preliminary) | DEL-02.01 | Required for line designations |
| Tie-In List (preliminary) | DEL-02.03 | Required for interface coordination |
| Interface Management Plan | DEL-00.05 | Required for interface management approach |
| Existing Facility P&IDs | TM Document Control | Required for existing conditions |

### 2.2 Required Resources

| Resource | Role |
|----------|------|
| Lead Process Engineer | Battery Limit Table Owner |
| Piping Engineer | Tie-in coordination (DEL-02.03) |
| Operations Representative | Existing facility input |
| Project Engineer | Interface coordination (DEL-00.05, DEL-00.06) |
| Document Controller | Document management (PKG-00) |

### 2.3 Required Authorizations

| Authorization | Authority | Required For |
|---------------|-----------|--------------|
| Project Kickoff | Project Manager | Procedure initiation |
| TM Interface Verification | TM Operations | Interface conditions |
| IFR Release | Engineering Manager | IFR submission |
| IFC Release | Engineering Manager + TM | IFC issue |

---

## 3. Steps

### 3.1 Phase 1: Interface Identification

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 1.1 | Review DBM (DEL-01.01) for battery limit scope definition | Lead Process Engineer | Scope understanding |
| 1.2 | Review Interface Management Plan (DEL-00.05) | Lead Process Engineer | Interface management approach |
| 1.3 | Request existing facility P&IDs from TM | Project Engineer | Existing P&ID set |
| 1.4 | Identify all process piping interfaces on P&IDs (DEL-01.03) | Lead Process Engineer | Interface list (preliminary) |
| 1.5 | Identify utility interfaces (coordinate with PKG-06, PKG-07) | Lead Process Engineer | Utility interface list |
| 1.6 | Coordinate with tie-in list development (DEL-02.03) | Lead Process Engineer + Piping Engineer | Aligned interface list |
| 1.7 | Update Interface Register (DEL-00.06) with identified interfaces | Project Engineer | Updated interface register |
| 1.8 | Establish Battery Limit Table template | Lead Process Engineer | Template file (Excel) |

### 3.2 Phase 2: Condition Definition

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 2.1 | Obtain design conditions from DBM (DEL-01.01) | Lead Process Engineer | Design parameters |
| 2.2 | Obtain operating conditions from hydraulic analysis (DEL-01.07) | Lead Process Engineer | Operating parameters |
| 2.3 | Request existing facility design data from TM | Project Engineer | Existing facility data |
| 2.4 | Request historical operating data from TM | Project Engineer | Historical operating data |
| 2.5 | Define design conditions at each interface | Lead Process Engineer | Design conditions table |
| 2.6 | Define normal operating conditions at each interface | Lead Process Engineer | Operating conditions table |
| 2.7 | Specify fluid properties at each interface (from DEL-01.01) | Lead Process Engineer | Fluid properties |
| 2.8 | Verify consistency with hydraulic analysis (DEL-01.07) | Lead Process Engineer | Consistency check record |

### 3.3 Phase 3: Table Development

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.1 | Populate Battery Limit Table with all interfaces | Lead Process Engineer | Draft Battery Limit Table |
| 3.2 | Add P&ID cross-references (from DEL-01.03) | Lead Process Engineer | P&ID references added |
| 3.3 | Add line number cross-references (from DEL-02.01) | Lead Process Engineer | Line number references added |
| 3.4 | Specify pipe sizes and ratings per ASME B16.5 | Lead Process Engineer | Size/rating data |
| 3.5 | Document special requirements (insulation, heat tracing) | Lead Process Engineer | Special requirements |
| 3.6 | Flag TBD items and assumptions | Lead Process Engineer | TBD/Assumption log |
| 3.7 | Verify consistency with tie-in list (DEL-02.03) | Lead Process Engineer + Piping Engineer | Consistency check record |
| 3.8 | Update Interface Register (DEL-00.06) with conditions | Project Engineer | Updated interface register |

### 3.4 Phase 4: TM Verification

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 4.1 | Submit Battery Limit Table to TM for verification | Project Engineer | Transmittal |
| 4.2 | TM verifies interface conditions against existing facilities | TM Operations | TM verification response |
| 4.3 | Address TM comments and discrepancies | Lead Process Engineer | Updated Battery Limit Table |
| 4.4 | Update related deliverables if changes required (DEL-01.03, DEL-01.07, DEL-02.03) | Lead Process Engineer | Updated deliverables |
| 4.5 | Obtain TM confirmation of interface conditions | Project Manager | TM confirmation record |
| 4.6 | Update Interface Register (DEL-00.06) with TM verification status | Project Engineer | Updated interface register |

### 3.5 Phase 5: Internal Review and Issue

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 5.1 | Conduct internal peer review | Assigned Reviewer | Review comments |
| 5.2 | Conduct interdisciplinary review with piping | Piping Lead | IDC comments |
| 5.3 | Verify cross-references to DEL-01.01, DEL-01.03, DEL-01.07, DEL-02.01, DEL-02.03 | Lead Process Engineer | Cross-reference verification |
| 5.4 | Address review comments | Lead Process Engineer | Updated Battery Limit Table |
| 5.5 | Obtain internal approval | Engineering Manager | Approval signature |
| 5.6 | Issue Battery Limit Table as IFR | Document Controller | IFR transmittal |
| 5.7 | Update for detailed design changes | Lead Process Engineer | Revised Battery Limit Table |
| 5.8 | Issue as IFC (per SOW-0232) | Document Controller | IFC transmittal |

---

## 4. Verification

### 4.1 Quality Checks

| Check | Criteria | Method | Timing |
|-------|----------|--------|--------|
| Completeness | All interfaces identified per DEL-00.05 | Interface checklist | Before TM verification |
| Consistency - DBM | Conditions match DEL-01.01 | Cross-reference check | Before TM verification |
| Consistency - Hydraulic | Conditions match DEL-01.07 | Cross-reference check | Before TM verification |
| Consistency - P&IDs | Interface locations match DEL-01.03 | Cross-reference check | Before TM verification |
| Consistency - Line List | Line numbers match DEL-02.01 | Cross-reference check | Before TM verification |
| Consistency - Tie-In List | Interface points match DEL-02.03 | Cross-reference check | Before TM verification |
| TM Alignment | Conditions match existing facilities | TM verification | Before IFR |
| Code Compliance | Design per CSA Z662 and ASME B31.4 | Engineering review | Before IFR |

### 4.2 Hold Points

| Hold Point | Criteria to Proceed | Authority |
|------------|---------------------|-----------|
| HP-01 | Existing facility data obtained | TM Operations |
| HP-02 | DEL-01.01 DBM approved | Engineering Manager |
| HP-03 | DEL-01.07 Hydraulic Analysis (preliminary) complete | Engineering Manager |
| HP-04 | TM verification complete | TM Operations |
| HP-05 | Internal review complete | Engineering Manager |

### 4.3 Verification Records

| Record | Content | Retention |
|--------|---------|-----------|
| TM Verification Record | TM confirmation of interface conditions | Permanent |
| Review Comments | All comments and responses | Project duration + 7 years |
| Consistency Check | Cross-reference verification with DEL-01.01, DEL-01.03, DEL-01.07, DEL-02.01, DEL-02.03 | Project duration + 7 years |

---

## 5. Records

### 5.1 Required Records

| Record | Format | Location | Responsibility |
|--------|--------|----------|----------------|
| Battery Limit Table (all revisions) | Excel + PDF | Document Control (PKG-00) | Document Controller |
| TM Verification Correspondence | PDF | Document Control (PKG-00) | Project Engineer |
| Review Comments | Excel/PDF | Document Control (PKG-00) | Lead Process Engineer |
| Transmittals | PDF | Document Control (PKG-00) | Document Controller |
| Interface Register Updates | Excel/PDF | Document Control (PKG-00) | Project Engineer |

### 5.2 Record Retention

| Category | Retention Period | Disposition |
|----------|------------------|-------------|
| Final Issue Documents | Permanent | Archive |
| TM Verification Records | Permanent | Archive |
| Draft Documents | Project completion + 5 years | Destroy |
| Review Records | Project completion + 7 years | Archive |

### 5.3 Document Control Requirements

- All Battery Limit Table revisions shall be issued through formal document control (per PKG-00)
- TM verification shall be documented before IFR issue
- Native Excel files shall be submitted per SOW-0232 requirements
- Interface Register (DEL-00.06) shall be updated at key milestones

---

## 6. Appendices

### 6.1 Battery Limit Table Development Checklist

- [ ] DEL-01.01 Design Basis Memorandum reviewed
- [ ] DEL-00.05 Interface Management Plan reviewed
- [ ] Existing facility P&IDs obtained from TM
- [ ] All process interfaces identified on DEL-01.03 P&IDs
- [ ] All utility interfaces identified (PKG-06, PKG-07)
- [ ] Design conditions obtained from DEL-01.01
- [ ] Operating conditions obtained from DEL-01.07
- [ ] Fluid properties obtained from DEL-01.01
- [ ] Pipe sizes and ratings specified per ASME B16.5
- [ ] Cross-references to DEL-01.03 P&IDs added
- [ ] Cross-references to DEL-02.01 Line List added
- [ ] Alignment with DEL-02.03 Tie-In List verified
- [ ] DEL-00.06 Interface Register updated
- [ ] TM verification obtained
- [ ] Internal review complete
- [ ] IFR issued per SOW-0232
- [ ] IFC issued per SOW-0232

### 6.2 Related Procedures

| Procedure | Reference |
|-----------|-----------|
| Document Control Procedure | PKG-00 |
| Interface Management Procedure | DEL-00.05-PR |
| Design Basis Development Procedure | DEL-01.01-PR |
| P&ID Development Procedure | DEL-01.03-PR |
| Hydraulic Analysis Procedure | DEL-01.07-PR |
| Line List Development Procedure | DEL-02.01-PR |
| Tie-In List Development Procedure | DEL-02.03-PR |

---

*End of Procedure*
