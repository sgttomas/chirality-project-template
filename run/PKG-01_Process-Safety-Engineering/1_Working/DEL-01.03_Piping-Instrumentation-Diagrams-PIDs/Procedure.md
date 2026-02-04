# Procedure: DEL-01.03 Piping & Instrumentation Diagrams (P&IDs)

**Document ID:** DEL-01.03-PR
**Revision:** Phase 2.2 (INITIALIZED)
**Date:** 2026-02-01
**Status:** INITIALIZED

---

## Purpose

### Procedure Objective

This procedure defines the step-by-step process for developing, reviewing, and issuing Piping and Instrumentation Diagrams (P&IDs) for the Puget Sound Optimization project at Sumas Tank Farm.

### Scope

This procedure covers:
- P&ID development from initiation through IFC issue
- Vendor P&ID transformation per SOW §3.2.3.5
- HAZOP and design review incorporation per SOW §3.2.3.4
- Internal review and TM approval processes

---

## Prerequisites

### Required Inputs

| Input | Source | Status |
|-------|--------|--------|
| Design Basis Memorandum (DBM) | DEL-01.01 | Required before P&ID development |
| Process Flow Diagrams (PFDs) | DEL-01.02 | Required before P&ID development |
| TM P&ID Symbol Library | TM Document Control | **TBD** - Required before drafting |
| TM Drawing Standards | TM Document Control | **TBD** - Required before drafting |
| Control Philosophy | TM / PKG-07 | **TBD** - Required per SOW §3.1.7.12 |
| Existing Facility P&IDs | TM Archives | **TBD** - Required for brownfield context |
| Vendor P&IDs | Vendor packages | **TBD** - Required during development |

### Required Resources

| Resource | Role |
|----------|------|
| Lead Process Engineer | P&ID Owner, technical content |
| Process Engineers | Supporting development |
| I&C Engineers | Instrumentation content, control loops |
| CAD Technician | Drawing production |
| Document Controller | Document management |

### Required Authorizations

| Authorization | Authority | Required For |
|---------------|-----------|--------------|
| Drawing Template Approval | Engineering Manager | Start of drafting |
| Tagging Convention Approval | TM | Start of drafting |
| IFR Release | Engineering Manager | IFR submission |
| IFD Release | Engineering Manager + TM | IFD issue |
| IFC Release | Project Director + TM | IFC issue |

---

## Steps

### Phase 1: Initiation and Setup

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 1.1 | Obtain DBM parameters from DEL-01.01 | Lead Process Engineer | Design basis extract |
| 1.2 | Obtain PFDs from DEL-01.02 | Lead Process Engineer | PFD reference |
| 1.3 | Request TM P&ID symbol library and standards | CAD Technician | Standards package |
| 1.4 | Obtain existing Sumas Terminal P&IDs for brownfield context | Document Controller | Reference drawings |
| 1.5 | Establish tagging conventions with TM (equipment, lines, instruments, valves) | Lead Process Engineer | Tagging convention document |
| 1.6 | Establish drawing numbering with TM Document Control | Document Controller | Drawing numbers |
| 1.7 | Setup CAD template per TM standards | CAD Technician | Template file |
| 1.8 | Define P&ID scope and sheet organization (5 pumps, manifold, auxiliaries) | Lead Process Engineer | P&ID scope definition |

### Phase 2: Equipment and Line Development

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 2.1 | Develop equipment list with tags (5 VS6 pumps, VFDs, flow meters per SOW §2.3.1) | Lead Process Engineer | Equipment list |
| 2.2 | Develop preliminary line list coordinated with DEL-02.01 (Line List) | Lead Process Engineer | Preliminary line list |
| 2.3 | Develop preliminary valve list coordinated with DEL-02.02 (Valve List) | Lead Process Engineer | Preliminary valve list |
| 2.4 | Coordinate with I&C for instrument list aligned with DEL-07.02 (Instrument Index) | I&C Engineers | Preliminary instrument list |
| 2.5 | Draft P&ID layouts (one per sheet based on scope definition) | CAD Technician | Draft P&ID layouts |
| 2.6 | Add equipment symbols and tags (all 5 pumps, VFDs, manifold) | CAD Technician | Updated P&IDs |
| 2.7 | Add piping with line numbers and specs per DEL-02.01 | CAD Technician | Updated P&IDs |
| 2.8 | Add valves with tags and types per DEL-02.02 | CAD Technician | Updated P&IDs |

### Phase 3: Instrumentation and Control

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.1 | Obtain control philosophy from TM/I&C per SOW §3.1.7.12 | Lead Process Engineer | Control philosophy |
| 3.2 | Add instrument symbols and tags (flow meters per SOW §2.3.1.4) | I&C Engineers | Updated P&IDs |
| 3.3 | Add control loops (blending ratio control per SOW §2.3.1.4) | I&C Engineers | Updated P&IDs |
| 3.4 | Add interlocks and ESD connections | I&C Engineers | Updated P&IDs |
| 3.5 | Verify instrument tags against DEL-07.02 Instrument Index | I&C Engineers | Verification record |

### Phase 4: Vendor P&ID Integration

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 4.1 | Receive vendor P&IDs from procurement (pumps, VFDs, packages) | Document Controller | Vendor P&ID package |
| 4.2 | Review vendor P&IDs for completeness | Lead Process Engineer | Review notes |
| 4.3 | Map vendor tags to project tags (coordinate with DEL-02.01, DEL-02.02, DEL-07.02) | Lead Process Engineer | Tag mapping table |
| 4.4 | Transform vendor P&IDs to TM standards per SOW §3.2.3.5 (symbols/legends/tagging) | CAD Technician | Transformed P&IDs |
| 4.5 | Integrate transformed P&IDs into drawing set | CAD Technician | Updated P&ID set |
| 4.6 | Verify transformation completeness against vendor scope | Lead Process Engineer | Verification record |
| 4.7 | Develop auxiliary system P&IDs as needed per SOW §3.2.3.6 | Process Engineer | Auxiliary P&IDs |

### Phase 5: Completion and Internal Review

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 5.1 | Add battery limits and tie-in identifications to existing Sumas Terminal | Lead Process Engineer | Updated P&IDs |
| 5.2 | Complete notes and references to DEL-01.02 PFDs | CAD Technician | Updated P&IDs |
| 5.3 | Complete legend and symbol sheet per TM standards | CAD Technician | Legend sheet |
| 5.4 | Complete title blocks | CAD Technician | Completed P&IDs |
| 5.5 | Conduct internal technical review | Assigned Reviewer | Review comments |
| 5.6 | Conduct interdisciplinary review (Piping, I&C, Electrical, Mechanical) | Discipline Leads | IDC comments |
| 5.7 | Address review comments | Lead Process Engineer + CAD | Updated P&IDs |
| 5.8 | Verify consistency with DEL-02.01 (Line List), DEL-02.02 (Valve List), DEL-07.02 (Instrument Index) | Lead Process Engineer | Cross-reference verification record |
| 5.9 | Obtain internal approval | Engineering Manager | Approval signature |

### Phase 6: Client Review (IFR)

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 6.1 | Issue P&ID set as IFR to TM per SOW §3.1.2.2 | Document Controller | Transmittal |
| 6.2 | Track TM review timeline | Project Engineer | Status updates |
| 6.3 | Receive and log TM comments | Document Controller | Comment register |
| 6.4 | Address TM comments | Lead Process Engineer | Comment responses |
| 6.5 | Update P&IDs based on comments | CAD Technician | Revised P&IDs |

### Phase 7: IFD Issue

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 7.1 | Resolve all IFR comments | Lead Process Engineer | Comment closeout |
| 7.2 | Conduct final internal review | Engineering Manager | Final approval |
| 7.3 | Obtain TM approval for IFD | Project Manager | TM approval |
| 7.4 | Issue P&ID set as IFD (end of FEED) | Document Controller | IFD transmittal |

### Phase 8: Detailed Design Updates (IFD to IFC)

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 8.1 | Incorporate HAZOP findings per SOW §3.2.3.4 and DEL-01.15 (HAZOP Report) | Lead Process Engineer | Updated P&IDs |
| 8.2 | Incorporate model review findings per SOW §3.2.3.4 | Lead Process Engineer | Updated P&IDs |
| 8.3 | Incorporate vendor data updates per SOW §3.2.3.4 | Lead Process Engineer | Updated P&IDs |
| 8.4 | Incorporate change notices per SOW §3.2.3.4 | Lead Process Engineer | Updated P&IDs |
| 8.5 | Final verification against DEL-02.01 (Line List), DEL-02.02 (Valve List), DEL-07.02 (Instrument Index) | Lead Process Engineer | Final cross-reference verification |
| 8.6 | Conduct IFC internal review | Engineering Manager | Final approval |
| 8.7 | Obtain TM approval for IFC | Project Director | TM approval |
| 8.8 | Issue P&ID set as IFC | Document Controller | IFC transmittal |

---

## Verification

### Quality Checks

| Check | Criteria | Method | Timing |
|-------|----------|--------|--------|
| Equipment Completeness | All 5 VS6 pumps, VFDs, flow meters, manifold shown | Equipment list comparison | Before IFR |
| Piping Completeness | All lines shown per DEL-02.01 | Line list comparison | Before IFR |
| Instrument Completeness | All instruments shown per DEL-07.02 | Instrument index comparison | Before IFR |
| Symbol Compliance | Per TM standards | Visual inspection | Before IFR |
| Tag Consistency | Match DEL-02.01 (Line List), DEL-02.02 (Valve List), DEL-07.02 (Instrument Index) | Cross-reference check | Before IFD |
| HAZOP Incorporation | All findings addressed per DEL-01.15 | HAZOP action tracker | Before IFC |
| Vendor P&ID Integration | All vendor scope shown per SOW §3.2.3.5 | Vendor scope review | Before IFC |

### Hold Points

| Hold Point | Criteria to Proceed | Authority |
|------------|---------------------|-----------|
| HP-01 | PFDs available (DEL-01.02) | Lead Process Engineer |
| HP-02 | Tagging conventions approved by TM | Engineering Manager |
| HP-03 | Internal review complete | Engineering Manager |
| HP-04 | TM IFR comments resolved | Project Manager |
| HP-05 | Vendor P&IDs integrated per SOW §3.2.3.5-§3.2.3.6 | Lead Process Engineer |
| HP-06 | HAZOP findings incorporated per DEL-01.15 | Engineering Manager |
| HP-07 | TM IFC approval received | Project Director |

### Verification Records

| Record | Content | Retention |
|--------|---------|-----------|
| Review Checklist | Completed quality checks | Project duration + 7 years |
| Comment Register | All comments and responses | Project duration + 7 years |
| Cross-Reference Verification | Comparison to DEL-02.01 (Line List), DEL-02.02 (Valve List), DEL-07.02 (Instrument Index) | Project duration + 7 years |
| Vendor P&ID Transformation Log | Mapping and verification | Project duration + 7 years |

---

## Records

### Required Records

| Record | Format | Location | Responsibility |
|--------|--------|----------|----------------|
| P&ID Drawing Set (all revisions) | PDF + CAD | TM Document Control | Document Controller |
| Review Comments | Excel/PDF | Document Control | Lead Process Engineer |
| Transmittals | PDF | Document Control | Document Controller |
| Approval Records | PDF | Document Control | Project Engineer |
| HAZOP Markups | PDF | Document Control | Lead Process Engineer |
| Vendor P&ID Source Files | PDF/CAD | Document Control | Document Controller |
| Tag Mapping Table | Excel | Document Control | Lead Process Engineer |

### Record Retention

| Category | Retention Period | Disposition |
|----------|------------------|-------------|
| IFC Drawings | Permanent | Archive |
| Superseded Drawings | Project completion + 5 years | Destroy |
| Review Records | Project completion + 7 years | Archive |

### Native File Requirements

Per SOW §3.2.3.18:
- Submit editable native CAD files (dwg/dgn)
- Include all xrefs and dependent files
- Include plotstyles and fonts

---

## Appendices

### P&ID Development Checklist

- [ ] DBM (DEL-01.01) obtained and reviewed
- [ ] PFDs (DEL-01.02) obtained and reviewed
- [ ] TM symbol library obtained
- [ ] Tagging conventions established with TM
- [ ] Drawing numbering established with TM
- [ ] Template approved
- [ ] Equipment list complete (5 VS6 pumps, 5 VFDs, 5 flow meters, 5x6 manifold per SOW §2.3.1)
- [ ] Line list coordinated with DEL-02.01 (Line List)
- [ ] Valve list coordinated with DEL-02.02 (Valve List)
- [ ] Instrument list coordinated with DEL-07.02 (Instrument Index)
- [ ] Control philosophy obtained per SOW §3.1.7.12
- [ ] Vendor P&IDs received
- [ ] Vendor P&IDs transformed per SOW §3.2.3.5 (symbols/legends/tagging)
- [ ] Auxiliary P&IDs developed per SOW §3.2.3.6 (as needed)
- [ ] Internal review complete
- [ ] IDC review complete
- [ ] IFR issued
- [ ] TM comments addressed
- [ ] IFD issued
- [ ] HAZOP findings incorporated per SOW §3.2.3.4 and DEL-01.15
- [ ] IFC issued

### Related Procedures

| Procedure | Reference |
|-----------|-----------|
| Document Control Procedure | PKG-00 |
| Change Management Procedure | PKG-00 |
| HAZOP Procedure | DEL-01.15 |
| Vendor P&ID Review Procedure | PKG-03 |

---

*End of Procedure*
