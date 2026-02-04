# Specification: DEL-01.06 Pressure Relief / Thermal Relief Calculations

**Document ID:** DEL-01.06-SP
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Scope

### 1.1 Purpose

This specification defines the requirements for Pressure Relief and Thermal Relief Calculations for the Puget Sound Optimization (PSO) project. These calculations shall verify the need for relief devices, size the devices, and ensure adequate overpressure protection for all applicable equipment and piping systems.

### 1.2 Applicability

This specification applies to:
- FEED phase relief device need verification and preliminary sizing
- Detailed design phase final sizing and specification
- All process equipment and piping within PKG-01 scope requiring overpressure protection

### 1.3 Boundaries

| Boundary | Description |
|----------|-------------|
| In Scope | PRV/TRV need verification, sizing calculations, inlet/outlet piping verification, discharge disposition (atmospheric vs. closed) |
| Out of Scope | Relief device procurement (DEL-01.16), P&ID development (DEL-01.03), mechanical datasheets (PKG-03), detailed discharge system design |

---

## 2. Requirements

### 2.1 Functional Requirements

| Req ID | Requirement | Priority | Verification |
|--------|-------------|----------|--------------|
| FR-01 | Calculations shall identify all equipment/systems requiring overpressure protection | Mandatory | Review |
| FR-02 | Calculations shall determine the governing relief scenario for each device | Mandatory | Review |
| FR-03 | Calculations shall size relief devices per applicable API/ASME standards | Mandatory | Calculation Check |
| FR-04 | Calculations shall verify inlet pressure drop meets 3% of set pressure limit (API 520 Part II) | Mandatory | Calculation Check |
| FR-05 | Calculations shall verify built-up backpressure is within device limits | Mandatory | Calculation Check |
| FR-06 | Calculations shall specify relief device set pressure and capacity | Mandatory | Review |

### 2.2 Content Requirements

| Req ID | Requirement | Priority |
|--------|-------------|----------|
| CR-01 | Include equipment/system identification and P&ID reference | Mandatory |
| CR-02 | Document all relief scenarios considered | Mandatory |
| CR-03 | Identify governing (worst-case) scenario | Mandatory |
| CR-04 | Include fluid properties at relieving conditions | Mandatory |
| CR-05 | Include required relieving rate calculation | Mandatory |
| CR-06 | Include orifice sizing calculation | Mandatory |
| CR-07 | Include inlet/outlet piping pressure drop verification | Mandatory |
| CR-08 | Summarize selected device specifications | Mandatory |

### 2.3 Performance Requirements

| Req ID | Requirement | Acceptance Criteria |
|--------|-------------|---------------------|
| PR-01 | All protected equipment shall be safe from overpressure | No equipment exceeds MAWP during relief |
| PR-02 | Relief devices shall provide adequate capacity | Relieving capacity >= required relief rate |
| PR-03 | Inlet piping shall not cause chatter | Inlet pressure drop <= 3% of set pressure (API 520 Part II) |
| PR-04 | Outlet piping shall not impair relief capacity | Built-up backpressure <= 10% of set pressure for conventional PRVs |

---

## 3. Standards

### 3.1 Applicable Codes and Standards

| Standard | Title | Application |
|----------|-------|-------------|
| API 520 Part I | Sizing, Selection, and Installation of Pressure-relieving Devices - Sizing and Selection | Relief device sizing methodology |
| API 520 Part II | Sizing, Selection, and Installation of Pressure-relieving Devices - Installation | Installation requirements, inlet/outlet piping |
| API 521 | Pressure-relieving and Depressuring Systems | Relief scenarios, system design |
| API 526 | Flanged Steel Pressure-relief Valves | Standard orifice designations |
| CSA Z662 | Oil and Gas Pipeline Systems | Pipeline relief requirements |
| ASME B31.4 | Pipeline Transportation Systems for Liquids and Slurries | Piping design code |
| TM-**TBD** | Trans Mountain Engineering Standards | Project-specific requirements |

### 3.2 Regulatory Requirements

| Regulation | Jurisdiction | Application |
|------------|--------------|-------------|
| CER Regulations | Federal (Canada) | Pipeline safety |
| BC Safety Standards Act | Provincial (BC) | Pressure equipment registration |
| Washington State Regulations | State (USA) | **TBD** - Cross-border aspects |

---

## 4. Verification

### 4.1 Verification Methods

| Method | Description | Applicability |
|--------|-------------|---------------|
| Independent Calculation Check | Second engineer verification | All sizing calculations |
| Document Review | Review of methodology and assumptions | All content |
| Interdisciplinary Check | Verify consistency with P&IDs/hydraulic analysis | Relief scenarios, set pressures |
| TM Review | Client review and approval | All content |

### 4.2 Acceptance Criteria

| Criteria ID | Criteria | Method |
|-------------|----------|--------|
| AC-01 | All equipment requiring relief protection identified | Review vs. P&IDs |
| AC-02 | Governing scenarios correctly identified | Technical review |
| AC-03 | Calculations per API 520/521 methodology | Calculation check |
| AC-04 | Inlet/outlet piping meets API 520 Part II | Calculation check |
| AC-05 | Results consistent with DEL-01.07 hydraulic analysis and DEL-01.08 transient analysis | Cross-check |
| AC-06 | TM approval obtained | Sign-off |

### 4.3 Review Stages

| Stage | Milestone | Reviewer |
|-------|-----------|----------|
| IFR | FEED submission (need verification + preliminary sizing) | Engineering Lead |
| IFD | FEED completion | TM Review |
| IFC | Detailed Design completion (final sizing) | TM Approval |

---

## 5. Documentation

### 5.1 Deliverable Documentation

| Document | Format | Quantity |
|----------|--------|----------|
| Calculation Report(s) | PDF | 1 per system or consolidated |
| Calculation Spreadsheets | Excel | Native files |
| Relief Device Summary | Excel/PDF | 1 |

### 5.2 Records

| Record | Retention | Location |
|--------|-----------|----------|
| Review Comments | Project duration + 7 years | Document Control |
| Calculation Check Records | Project duration + 7 years | Document Control |
| Revision History | Permanent | Within document |

### 5.3 Revision Control

| Revision | Description | Date |
|----------|-------------|------|
| Pass 1 | Initial draft generation | 2026-02-01 |
| Pass 2 | Cross-reference consistency check | 2026-02-01 |
| **TBD** | IFR submission | **TBD** |
| **TBD** | IFD submission | **TBD** |
| **TBD** | IFC submission | **TBD** |

---

*End of Specification*
