# Specification: DEL-01.01 Process Design Basis / DBM (Design Basis & Design Criteria)

**Document ID:** DEL-01.01-SP
**Revision:** Phase 2.2 (INITIALIZED)
**Date:** 2026-02-01
**Status:** INITIALIZED

---

## Scope

### Purpose

This specification defines the requirements for the Process Design Basis / Design Basis Memorandum (DBM) for the Puget Sound Optimization (PSO) project at Sumas Tank Farm. The DBM establishes the fundamental process design parameters, criteria, and constraints that govern all subsequent engineering deliverables.

### Applicability

This specification applies to:
- FEED phase design basis development
- Detailed design phase updates and refinements
- All process and safety engineering scope within PKG-01

### Boundaries

| Boundary | Description |
|----------|-------------|
| In Scope | Process design basis, design criteria, operating parameters, equipment basis, safety philosophy, interface conditions |
| In Scope | Blending requirements and control philosophy basis |
| In Scope | Sumas Tank Farm upgrades: 5 VS6 booster pumps, 5x6 manifold, containment wall |
| Out of Scope | Detailed calculations (covered by DEL-01.04 through DEL-01.08) |
| Out of Scope | Laurel Pump Station (explicitly excluded per SOW) |

---

## Requirements

### Functional Requirements

| Req ID | Requirement | Priority | Source | Verification |
|--------|-------------|----------|--------|--------------|
| FR-01 | Define sustainable throughput of 275,000 bpd (1,822 m³/h) | Mandatory | SOW §2.2.1 | Review |
| FR-02 | Define design (peak) throughput of 315,000 bpd (2,100 m³/h) | Mandatory | SOW §2.2.1 | Review |
| FR-03 | Document blending requirements (ratio range: SOW specifies 20%-80%, DBM specifies 10%-100% NEAT - confirm with TM) | Mandatory | SOW §2.3.1.4, DBM §2.2.2.2 | TM Review |
| FR-04 | Document pump configuration basis (2 large, 2 small, 1 medium VS6-type) | Mandatory | SOW §2.3.1.2 | Review |
| FR-05 | Document manifold configuration basis (5x6) | Mandatory | SOW §2.3.1.1 | Review |
| FR-06 | Define VFD and flow metering requirements per pump | Mandatory | SOW §2.3.1.4 | Review |
| FR-07 | Document interface conditions with existing Sumas Terminal facilities | Mandatory | SOW §3.2.2.15 | Review |
| FR-08 | Define operating flexibility requirements (tank utilization, transfers) | Mandatory | DBM §2.2.2.1-§2.2.2.4 | Review |
| FR-09 | Establish design life (typically 25-30 years, confirm with TM) | Mandatory | TMP Standards, **ASSUMPTION** | TM Review |
| FR-09A | Establish corrosion allowances per TMP standards | Mandatory | TMP Standards | TM Review |
| FR-10 | Define project battery limits and interface points | Mandatory | Project scope | Review |
| FR-11 | Define minimum turndown flow rate for pump operation | Mandatory | VFD/pump capabilities | Review |

### Content Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| CR-01 | Include project scope summary and overview | Mandatory | SOW §3.1.3.1 |
| CR-02 | Include design basis and design criteria sections | Mandatory | SOW §3.1.3.1 |
| CR-03 | Define process fluid properties and compositions | Mandatory | Process requirements |
| CR-04 | Specify design pressure and temperature ranges | Mandatory | Process requirements |
| CR-05 | Document safety factors and design margins | Mandatory | Industry practice |
| CR-06 | Document preliminary engineering DBM as informational reference | Mandatory | SOW §4.2.2.2 |
| CR-07 | Confirm design suitability for intended purpose | Mandatory | SOW §4.2.2.3 |
| CR-08 | List TMP specification deviations (if any) with approval status | Mandatory | SOW §3.2.2.3 |
| CR-09 | Include preliminary material selection criteria based on fluid compatibility and TMP standards | Mandatory | Industry practice, TMP Standards |
| CR-10 | Clarify terminology for blending range (NEAT = 100% undiluted heavy crude) | Mandatory | DBM §2.2.2.2 |

### Deliverable Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| DR-01 | Provide editable native files | Mandatory | SOW §3.2.3.18 |
| DR-02 | Provide PDF version for formal submission | Mandatory | SOW §4.3.5.1 |
| DR-03 | Follow TM document numbering conventions | Mandatory | SOW §4.3.4.1 |
| DR-04 | Register in Master Document Register (MDR) | Mandatory | SOW §3.2.2.7 |
| DR-05 | Submit at IFR, IFD, and IFC milestones | Mandatory | SOW §3.1.2.2 |

### Performance Requirements

| Req ID | Requirement | Acceptance Criteria | Source |
|--------|-------------|---------------------|--------|
| PR-01 | DBM shall support hydraulic model optimization | Confirmed by DEL-01.07 | SOW §3.1.3.2 |
| PR-02 | DBM shall enable equipment sizing | Confirmed by DEL-01.04 | SOW §3.1.3.1 |
| PR-03 | DBM shall enable line sizing | Confirmed by DEL-01.05 | SOW §3.1.3.1 |
| PR-04 | DBM shall support HAZOP execution | Confirmed by DEL-01.15 | SOW §4.5.1 |

---

## Standards

### Applicable Codes and Standards

| Standard | Title | Application |
|----------|-------|-------------|
| CER OPR | Canada Energy Regulator Onshore Pipeline Regulations | Federal pipeline regulations |
| CSA Z662 | Oil and Gas Pipeline Systems | Primary design code |
| ASME B31.4 | Pipeline Transportation Systems for Liquids | Liquid piping |
| Title 49 PHMSA Part 195 | Transportation of Hazardous Liquids by Pipeline | US regulatory (cross-border) |
| API 2350 | Overfill Protection for Storage Tanks | Tank systems (if applicable) |
| TMP Standards | Trans Mountain Engineering Standards | **TBD** - Attachment A08 |

### Regulatory Requirements

| Regulation | Jurisdiction | Application |
|------------|--------------|-------------|
| CER Regulations | Federal (Canada) | Pipeline safety - primary |
| BC Oil and Gas Activities Act | Provincial (BC) | **TBD** - Confirm applicability (to be verified in Phase 2) |
| Washington State Regulations | State (USA) | Cross-border aspects at Sumas (to be verified in Phase 2) |

---

## Verification

### Verification Methods

| Method | Description | Applicability |
|--------|-------------|---------------|
| Document Review | Independent review of DBM content | All requirements |
| Interdisciplinary Check | Cross-discipline verification | Interface requirements |
| TM Review | Client review and approval | All content |
| Standards Compliance Check | Verify alignment with TMP Standards | Deviations documented and approved |

### Acceptance Criteria

| Criteria ID | Criteria | Method |
|-------------|----------|--------|
| AC-01 | All mandatory content sections complete | Document Review |
| AC-02 | Parameters consistent with TM standards | TM Review |
| AC-03 | No unresolved TBDs in final issue (IFC) | Document Review |
| AC-04 | Approved deviations documented | TM Review |
| AC-05 | DBM parameters align with PFDs, P&IDs, sizing calculations | IDC Review |

### Review Stages

| Stage | Milestone | Reviewer | Gate |
|-------|-----------|----------|------|
| IFR | FEED submission | Engineering Lead | Internal approval |
| IFD | FEED completion | TM Review | TM approval |
| IFC | Detailed Design completion | TM Approval | Final acceptance |

---

## Documentation

### Deliverable Documentation

| Document | Format | Quantity | Submission |
|----------|--------|----------|------------|
| DBM Document | PDF | 1 (plus revisions) | Per milestone |
| Native Files | Word/Excel | 1 set | Per SOW §3.2.3.18 |
| Appendices | PDF | As required | With DBM |
| Comment Response Log | Excel/PDF | 1 per review cycle | Per review |

### Records

| Record | Retention | Location |
|--------|-----------|----------|
| DBM (all revisions) | Permanent | TM Document Control |
| Review Comments | Project duration + 7 years | Document Control |
| Revision History | Permanent | Within document |
| Approval Records | Project duration + 7 years | Document Control |
| Assumptions Register | Project duration | Deliverable folder |

### Revision Control

| Revision | Description | Date |
|----------|-------------|------|
| Phase 2.2 | INITIALIZED - Documents generated | 2026-02-01 |
| **TBD** | IFR submission | **TBD** |
| **TBD** | IFD submission | **TBD** |
| **TBD** | IFC submission | **TBD** |

---

*End of Specification*
