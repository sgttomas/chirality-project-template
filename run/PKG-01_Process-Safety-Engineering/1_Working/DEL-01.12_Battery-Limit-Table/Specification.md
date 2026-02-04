# Specification: DEL-01.12 Battery Limit Table

**Document ID:** DEL-01.12-SP
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Scope

### 1.1 Purpose

This specification defines the requirements for the Battery Limit Table for the Puget Sound Optimization (PSO) project. The Battery Limit Table defines the process interfaces and boundary conditions between the PSO scope and existing Sumas Tank Farm facilities.

### 1.2 Applicability

This specification applies to:
- FEED phase interface definition (preliminary)
- Detailed Design phase finalization
- IFC deliverables package (per SOW-0232)
- All process piping and utility interfaces between PSO scope and existing facilities

### 1.3 Boundaries

| Boundary | Description |
|----------|-------------|
| In Scope | All process/utility interfaces between PSO new facilities and existing Sumas Terminal |
| Out of Scope | Internal interfaces within PSO scope (covered by P&IDs and tie-in list) |

---

## 2. Requirements

### 2.1 Functional Requirements

| Req ID | Requirement | Priority | Verification |
|--------|-------------|----------|--------------|
| FR-01 | Battery Limit Table shall identify all process interfaces between PSO scope and existing facilities | Mandatory | Document Review |
| FR-02 | Battery Limit Table shall define design conditions at each interface per DEL-01.01 and DEL-01.07 | Mandatory | Cross-Reference Check |
| FR-03 | Battery Limit Table shall define normal operating conditions at each interface | Mandatory | Document Review |
| FR-04 | Battery Limit Table shall specify fluid properties at each interface per DEL-01.01 | Mandatory | Cross-Reference Check |
| FR-05 | Battery Limit Table shall cross-reference P&IDs (DEL-01.03) and line numbers (DEL-02.01) | Mandatory | Cross-Reference Check |
| FR-06 | Battery Limit Table shall align with tie-in list (DEL-02.03) | Mandatory | Cross-Reference Check |
| FR-07 | Battery Limit Table shall be managed per Interface Management Plan (DEL-00.05) | Mandatory | Procedure Compliance |

### 2.2 Content Requirements

| Req ID | Requirement | Priority |
|--------|-------------|----------|
| CR-01 | Include all suction/inlet interfaces per DBM (DEL-01.01) | Mandatory |
| CR-02 | Include all discharge/outlet interfaces per DBM (DEL-01.01) | Mandatory |
| CR-03 | Include utility interfaces (instrument air, cooling water, fire water) coordinated with PKG-06 and PKG-07 | Mandatory |
| CR-04 | Specify design pressure and temperature at each interface per DEL-01.01 and DEL-01.07 | Mandatory |
| CR-05 | Specify normal operating conditions at each interface per DEL-01.07 | Mandatory |
| CR-06 | Identify pipe size and rating at each interface per ASME B16.5 | Mandatory |
| CR-07 | Include flow rates per SOW-0232 (275,000 bpd sustainable; 315,000 bpd peak) | Mandatory |

### 2.3 Interface Requirements

| Req ID | Requirement | Acceptance Criteria |
|--------|-------------|---------------------|
| IF-01 | Interface conditions shall be consistent with existing facility design | Confirmed by TM review |
| IF-02 | Interface locations shall align with tie-in list (DEL-02.03) | Cross-reference check |
| IF-03 | Interface conditions shall support hydraulic model (DEL-01.07) | Confirmed by DEL-01.07 engineer |
| IF-04 | Interface parameters shall align with design basis (DEL-01.01) | Cross-reference check |
| IF-05 | Interface locations shall be shown on P&IDs (DEL-01.03) | Cross-reference check |
| IF-06 | Interface tracking shall be maintained in Interface Register (DEL-00.06) | Procedure compliance |

---

## 3. Standards

### 3.1 Applicable Codes and Standards

| Standard | Title | Application |
|----------|-------|-------------|
| CSA Z662 | Oil and Gas Pipeline Systems | Design basis and pressure/temperature requirements |
| ASME B31.4 | Pipeline Transportation Systems for Liquids and Slurries | Design pressure/temperature and material requirements |
| ASME B16.5 | Pipe Flanges and Flanged Fittings | Pressure class ratings |
| TM Standards | Trans Mountain Engineering Standards | Interface documentation requirements (to be confirmed) |

### 3.2 Regulatory Requirements

| Regulation | Jurisdiction | Application |
|------------|--------------|-------------|
| CER OPR-99 | Federal (Canada) | Pipeline modifications and interface design |
| BC Oil and Gas Commission | Provincial (BC) | Provincial pipeline requirements |
| Washington State | State (USA) | Puget Sound delivery requirements (to be confirmed) |

---

## 4. Verification

### 4.1 Verification Methods

| Method | Description | Applicability |
|--------|-------------|---------------|
| Document Review | Independent review of content completeness | All requirements |
| Cross-Reference Check - DBM | Verify consistency with DEL-01.01 Design Basis Memorandum | FR-02, FR-04, IF-04, CR-01, CR-02, CR-04 |
| Cross-Reference Check - P&IDs | Verify consistency with DEL-01.03 P&IDs | FR-05, IF-05 |
| Cross-Reference Check - Hydraulic | Verify consistency with DEL-01.07 Hydraulic Analysis | FR-02, IF-03, CR-04, CR-05 |
| Cross-Reference Check - Line List | Verify consistency with DEL-02.01 Line List | FR-05 |
| Cross-Reference Check - Tie-In List | Verify consistency with DEL-02.03 Tie-In List | FR-06, IF-02 |
| TM Verification | TM confirms interface conditions match existing facilities | IF-01 |
| Code Compliance Check | Verify design per CSA Z662 and ASME B31.4 | All design requirements |

### 4.2 Acceptance Criteria

| Criteria ID | Criteria | Method |
|-------------|----------|--------|
| AC-01 | All process interfaces identified per DEL-01.01 | Document Review |
| AC-02 | Design conditions specified for all interfaces per DEL-01.01 and DEL-01.07 | Cross-Reference Check |
| AC-03 | Conditions consistent with existing facility data | TM Verification |
| AC-04 | Cross-references to DEL-01.03 accurate and complete | Cross-Reference Check |
| AC-05 | Line numbers match DEL-02.01 Line List | Cross-Reference Check |
| AC-06 | Interface points align with DEL-02.03 Tie-In List | Cross-Reference Check |
| AC-07 | Flow rates match SOW-0232 requirements (275,000/315,000 bpd) | Document Review |
| AC-08 | Design complies with CSA Z662 and ASME B31.4 | Code Compliance Check |

### 4.3 Review Stages

| Stage | Milestone | Reviewer |
|-------|-----------|----------|
| IFR | FEED / Early Detailed Design | Engineering Lead |
| IFD | Detailed Design 60% | TM Review |
| IFC | Detailed Design completion (per SOW-0232) | TM Approval |

---

## 5. Documentation

### 5.1 Deliverable Documentation

| Document | Format | Quantity |
|----------|--------|----------|
| Battery Limit Table | Excel + PDF | 1 set |
| Revision History | Within document | Included |

### 5.2 Records

| Record | Retention | Location |
|--------|-----------|----------|
| TM Interface Confirmation | Permanent | Document Control (PKG-00) |
| Review Comments | Project duration + 7 years | Document Control (PKG-00) |
| Approval Records | Permanent | Document Control (PKG-00) |
| Cross-Reference Verification Records | Project duration + 7 years | Document Control (PKG-00) |

### 5.3 Revision Control

| Revision | Description | Date |
|----------|-------------|------|
| Pass 1 | Initial draft generation | 2026-02-01 |
| Pass 2 | Cross-reference consistency check | 2026-02-01 |
| IFR | IFR submission (planned) | TBD |
| IFC | IFC submission per SOW-0232 (planned) | TBD |

---

*End of Specification*
