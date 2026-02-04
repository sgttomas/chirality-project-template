# Procedure: DEL-01.02 Process Flow Diagrams (PFDs)

**Document ID:** DEL-01.02-PR
**Revision:** Phase 2.2 (INITIALIZED)
**Date:** 2026-02-01
**Status:** INITIALIZED

---

## Purpose

### Procedure Objective

This procedure defines the step-by-step process for developing, reviewing, and issuing Process Flow Diagrams (PFDs) for the Puget Sound Optimization project at Sumas Tank Farm.

### Scope

This procedure covers:
- PFD development from initiation through IFC issue
- HAZOP and design review incorporation per SOW §3.2.3.14
- Vendor data integration
- Internal review and TM approval processes

---

## Prerequisites

### Required Inputs

| Input | Source | Status |
|-------|--------|--------|
| Design Basis Memorandum (DBM) | DEL-01.01 | Required before PFD development |
| TM Symbol Library | TM Document Control | **TBD** - Required before drafting |
| TM Drawing Standards | TM Document Control | **TBD** - Required before drafting |
| Existing Facility PFDs | TM Archives | **TBD** - Required for brownfield context |
| Input PFD (Appendix B) | Project workspace | Available |
| Hydraulic Analysis Data | DEL-01.07 | Concurrent development |

### Required Resources

| Resource | Role |
|----------|------|
| Lead Process Engineer | PFD Owner, technical content |
| Process Engineers | Supporting development |
| CAD Technician | Drawing production |
| Document Controller | Document management |

### Required Authorizations

| Authorization | Authority | Required For |
|---------------|-----------|--------------|
| Drawing Template Approval | Engineering Manager | Start of drafting |
| IFR Release | Engineering Manager | IFR submission |
| IFD Release | Engineering Manager + TM | IFD issue |
| IFC Release | Project Director + TM | IFC issue |

---

## Steps

### Phase 1: Initiation and Setup

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 1.1 | Obtain DBM parameters from DEL-01.01 (design basis, flow rates, P/T) | Lead Process Engineer | Design basis extract |
| 1.2 | Review input PFD (Appendix B) for baseline understanding | Lead Process Engineer | Review notes |
| 1.3 | Request TM symbol library and drawing standards | CAD Technician | Standards package |
| 1.4 | Obtain existing Sumas Terminal PFDs for brownfield context | Document Controller | Reference drawings |
| 1.5 | Establish drawing numbering with TM Document Control | Document Controller | Drawing numbers |
| 1.6 | Setup CAD template per TM standards | CAD Technician | Template file |
| 1.7 | Define PFD scope (number of sheets, boundaries, systems covered) | Lead Process Engineer | PFD scope definition |

### Phase 2: Development

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 2.1 | Develop overall system block diagram showing pumps, manifold, blending | Lead Process Engineer | Block diagram sketch |
| 2.2 | Define equipment list with preliminary tags (5 VS6 pumps: 2 Large + 2 Small + 1 Medium, VFDs, flow meters) | Lead Process Engineer | Equipment list |
| 2.3 | Define stream list with preliminary numbers | Lead Process Engineer | Stream list |
| 2.4 | Draft PFD schematic layout based on Appendix B and DEL-01.01 DBM | CAD Technician | Draft PFD |
| 2.5 | Add equipment symbols and tags (all 5 pumps with VFDs per SOW §2.3.1) | CAD Technician | Updated PFD |
| 2.6 | Add process lines with stream numbers and flow directions | CAD Technician | Updated PFD |
| 2.7 | Add major control loops (blending ratio control per SOW §2.3.1.4) | Lead Process Engineer | Updated PFD |
| 2.8 | Coordinate with DEL-01.07 Hydraulic Analysis for stream data (concurrent development) | Lead Process Engineer | Stream data |
| 2.9 | Populate stream data table (sustainable 275,000 bpd / 1,822 m³/h and peak 315,000 bpd / 2,100 m³/h flow cases) | Lead Process Engineer | Completed stream table |
| 2.10 | Add battery limits and tie-in identifications to existing Sumas Terminal | Lead Process Engineer | Updated PFD |
| 2.11 | Complete legend and notes | CAD Technician | Completed PFD |
| 2.12 | Complete title block per TM format | CAD Technician | Completed PFD |

### Phase 3: Internal Review

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.1 | Conduct internal technical review against DEL-01.01 DBM | Assigned Reviewer | Review comments |
| 3.2 | Conduct interdisciplinary review (Piping, I&C, Electrical) | Discipline Leads | IDC comments |
| 3.3 | Address review comments | Lead Process Engineer + CAD | Updated PFD |
| 3.4 | Verify stream data against DEL-01.07 Hydraulic Analysis (as available) | Lead Process Engineer | Verification record |
| 3.5 | Obtain internal approval | Engineering Manager | Approval signature |

### Phase 4: Client Review (IFR)

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 4.1 | Issue PFD set as IFR to TM per SOW §3.1.2.2 | Document Controller | Transmittal |
| 4.2 | Track TM review timeline | Project Engineer | Status updates |
| 4.3 | Receive and log TM comments | Document Controller | Comment register |
| 4.4 | Address TM comments | Lead Process Engineer | Comment responses |
| 4.5 | Update PFD based on comments | CAD Technician | Revised PFD |
| 4.6 | Re-verify stream data consistency with DEL-01.01 DBM and DEL-01.07 Hydraulic Analysis | Lead Process Engineer | Verification record |

### Phase 5: IFD Issue

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 5.1 | Resolve all IFR comments | Lead Process Engineer | Comment closeout |
| 5.2 | Conduct final internal review | Engineering Manager | Final approval |
| 5.3 | Obtain TM approval for IFD | Project Manager | TM approval |
| 5.4 | Issue PFD set as IFD (end of FEED) | Document Controller | IFD transmittal |

### Phase 6: Detailed Design Updates (IFD to IFC)

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 6.1 | Incorporate HAZOP findings per SOW §3.2.3.14 | Lead Process Engineer | Updated PFD |
| 6.2 | Incorporate model review findings | Lead Process Engineer | Updated PFD |
| 6.3 | Incorporate vendor data updates | Lead Process Engineer | Updated PFD |
| 6.4 | Incorporate change notices | Lead Process Engineer | Updated PFD |
| 6.5 | Update stream data with final hydraulic analysis from DEL-01.07 | Lead Process Engineer | Final stream data |
| 6.6 | Conduct IFC internal review | Engineering Manager | Final approval |
| 6.7 | Obtain TM approval for IFC | Project Director | TM approval |
| 6.8 | Issue PFD set as IFC | Document Controller | IFC transmittal |

---

## Verification

### Quality Checks

| Check | Criteria | Method | Timing |
|-------|----------|--------|--------|
| Equipment Completeness | All 5 VS6 pumps (2 Large + 2 Small + 1 Medium), VFDs, flow meters, manifold shown | Equipment list comparison | Before IFR |
| Stream Data Accuracy | Consistent with DEL-01.01 DBM and DEL-01.07 Hydraulic Analysis | Cross-reference | Before IFR, IFC |
| Symbol Compliance | Per TM standards | Visual inspection | Before IFR |
| Tag Consistency | Match equipment list, align with DEL-01.03 P&ID tags | Cross-reference | Before IFD |
| HAZOP Incorporation | All findings addressed per SOW §3.2.3.14 | HAZOP action tracker | Before IFC |
| Input PFD Alignment | Changes from Appendix B documented | Review | Before IFR |

### Hold Points

| Hold Point | Criteria to Proceed | Authority |
|------------|---------------------|-----------|
| HP-01 | DBM available (DEL-01.01) | Lead Process Engineer |
| HP-02 | TM symbol library obtained | CAD Technician |
| HP-03 | Internal review complete | Engineering Manager |
| HP-04 | TM IFR comments resolved | Project Manager |
| HP-05 | HAZOP findings incorporated | Engineering Manager |
| HP-06 | TM IFC approval received | Project Director |

### Verification Records

| Record | Content | Retention |
|--------|---------|-----------|
| Review Checklist | Completed quality checks | Project duration + 7 years |
| Comment Register | All comments and responses | Project duration + 7 years |
| Stream Data Verification | Cross-reference to DEL-01.01 DBM, DEL-01.07 Hydraulic Analysis | Project duration + 7 years |

---

## Records

### Required Records

| Record | Format | Location | Responsibility |
|--------|--------|----------|----------------|
| PFD Drawing Set (all revisions) | PDF + CAD | TM Document Control | Document Controller |
| Review Comments | Excel/PDF | Document Control | Lead Process Engineer |
| Transmittals | PDF | Document Control | Document Controller |
| Approval Records | PDF | Document Control | Project Engineer |
| HAZOP Markups | PDF | Document Control | Lead Process Engineer |

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

### PFD Development Checklist

- [ ] DBM (DEL-01.01) obtained and reviewed
- [ ] Input PFD (Appendix B) reviewed
- [ ] TM symbol library obtained
- [ ] Drawing numbering established with TM
- [ ] Template approved
- [ ] Equipment list complete (5 pumps: 2 Large + 2 Small + 1 Medium, VFDs, flow meters, manifold)
- [ ] Stream list complete
- [ ] Schematic layout complete
- [ ] Stream data populated (sustainable 275,000 bpd / 1,822 m³/h and peak 315,000 bpd / 2,100 m³/h cases)
- [ ] Battery limits marked
- [ ] Internal review complete
- [ ] IDC review complete
- [ ] IFR issued
- [ ] TM comments addressed
- [ ] IFD issued
- [ ] HAZOP findings incorporated
- [ ] IFC issued

### Related Procedures

| Procedure | Reference |
|-----------|-----------|
| Document Control Procedure | PKG-00 |
| Change Management Procedure | PKG-00 |
| HAZOP Procedure | DEL-01.15 |

---

*End of Procedure*
