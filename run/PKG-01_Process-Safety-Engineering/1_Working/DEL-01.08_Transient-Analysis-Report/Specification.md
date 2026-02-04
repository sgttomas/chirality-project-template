# Specification: DEL-01.08 Transient Analysis Report

**Document ID:** DEL-01.08-SP
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Scope

### 1.1 Purpose

This specification defines the requirements for the Transient Analysis Report for the Puget Sound Optimization (PSO) project. The report shall document transient hydraulic analysis (surge/waterhammer) for the booster pump station, manifold, and associated piping systems, identifying potential transient hazards and recommending mitigation measures as required.

### 1.2 Applicability

This specification applies to:
- FEED phase transient screening and preliminary analysis
- Detailed design phase comprehensive transient analysis
- All process systems within PKG-01 scope subject to transient events
- Integration with hydraulic analysis (DEL-01.07)

### 1.3 Boundaries

| Boundary | Description |
|----------|-------------|
| In Scope | Transient hydraulic analysis, surge/waterhammer evaluation, mitigation recommendations |
| Out of Scope | Steady-state hydraulic analysis (DEL-01.07), relief device sizing (DEL-01.06), control system design (PKG-07) |

---

## 2. Requirements

### 2.1 Functional Requirements

| Req ID | Requirement | Priority | Verification |
|--------|-------------|----------|--------------|
| FR-01 | Analysis shall evaluate pump trip scenarios (single and multiple) per datasheet TS-01, TS-02 | Mandatory | Calculation |
| FR-02 | Analysis shall evaluate pump startup transients per datasheet TS-03, TS-04 | Mandatory | Calculation |
| FR-03 | Analysis shall evaluate valve closure/opening transients per datasheet TS-05, TS-08 | Mandatory | Calculation |
| FR-04 | Analysis shall verify maximum surge pressures below design limits per ASME B31.4 | Mandatory | Calculation |
| FR-05 | Analysis shall verify minimum pressures above vapor pressure (no column separation) | Mandatory | Calculation |
| FR-06 | Analysis shall evaluate check valve slam per datasheet TS-06 | Mandatory | Calculation |
| FR-07 | Analysis shall evaluate VFD speed change transients per datasheet TS-07 | Mandatory | Calculation |
| FR-08 | Analysis shall recommend mitigation measures if required | Mandatory | Review |

### 2.2 Content Requirements

| Req ID | Requirement | Priority |
|--------|-------------|----------|
| CR-01 | Include executive summary with key findings | Mandatory |
| CR-02 | Include system description and model boundaries | Mandatory |
| CR-03 | Document methodology, software, and assumptions | Mandatory |
| CR-04 | Include all transient scenarios TS-01 through TS-08 analyzed | Mandatory |
| CR-05 | Include pressure/flow vs. time plots for each scenario | Mandatory |
| CR-06 | Include maximum/minimum pressure envelopes | Mandatory |
| CR-07 | Document equipment response (pump inertia, valve closure curves) | Mandatory |
| CR-08 | Include mitigation measures analysis (if applicable) | As Required |
| CR-09 | Include conclusions and recommendations | Mandatory |
| CR-10 | Include model output appendices | Mandatory |
| CR-11 | Document consistency with DEL-01.07 steady-state model | Mandatory |

### 2.3 Performance Requirements

| Req ID | Requirement | Acceptance Criteria |
|--------|-------------|---------------------|
| PR-01 | Maximum surge pressure within limits | Max pressure <= Design pressure (with margin per ASME B31.4) |
| PR-02 | No column separation | Min pressure > Vapor pressure at all locations |
| PR-03 | Check valve closure acceptable | Reverse velocity at closure <= manufacturer limit |
| PR-04 | Pressure rise rates acceptable | If specified by TM or equipment vendor |
| PR-05 | Model validation | Steady-state conditions match DEL-01.07 at t=0 |

---

## 3. Standards

### 3.1 Applicable Codes and Standards

| Standard | Title | Application |
|----------|-------|-------------|
| ASME B31.4 | Pipeline Transportation Systems for Liquids | Design pressure considerations |
| CSA Z662 | Oil and Gas Pipeline Systems | Pipeline transient requirements |
| API 1160 | Managing System Integrity for Hazardous Liquid Pipelines | Risk-based considerations |
| AWWA M11 | Steel Pipe Design and Installation | Surge analysis guidance (reference) |

### 3.2 Regulatory Requirements

| Regulation | Jurisdiction | Application |
|------------|--------------|-------------|
| CER Regulations | Federal (Canada) | Pipeline safety |
| Title 49 CFR Part 195 | Federal (USA) | Hazardous liquid pipelines |

---

## 4. Verification

### 4.1 Verification Methods

| Method | Description | Applicability |
|--------|-------------|---------------|
| Model Validation | Verify model setup against DEL-01.07 steady-state | Model initialization |
| Independent Review | Second engineer review of model/results | All analyses |
| Sensitivity Analysis | Assess impact of key variables | Wave speed, pump inertia |
| HAZOP Integration | Cross-reference with DEL-01.15 HAZOP scenarios | Scenario identification |

### 4.2 Acceptance Criteria

| Criteria ID | Criteria | Method |
|-------------|----------|--------|
| AC-01 | All credible transient scenarios (TS-01 through TS-08) analyzed | Completeness check |
| AC-02 | Max pressures within design limits per ASME B31.4 | Model results vs. design pressure |
| AC-03 | No column separation predicted | Model results vs. vapor pressure |
| AC-04 | Mitigation measures effective (if required) | Analysis of mitigated cases |
| AC-05 | Consistent with DEL-01.07 steady-state model | Cross-check |
| AC-06 | TM approval obtained | Sign-off |

### 4.3 Review Stages

| Stage | Milestone | Reviewer |
|-------|-----------|----------|
| IFR | FEED submission (screening/preliminary) | Engineering Lead |
| IFD | FEED completion | TM Review |
| IFC | Detailed Design completion (comprehensive) | TM Approval |

---

## 5. Documentation

### 5.1 Deliverable Documentation

| Document | Format | Quantity |
|----------|--------|----------|
| Transient Analysis Report | PDF | 1 |
| Model Input/Output Files | Software native format | 1 set |
| Time History Data | Excel/CSV | Key scenarios |
| Executive Summary | PDF (within report) | 1 |

### 5.2 Records

| Record | Retention | Location |
|--------|-----------|----------|
| Review Comments | Project duration + 7 years | Document Control |
| Model Files (all versions) | Project duration + 7 years | Document Control |
| Vendor Data (pump curves, valve data) | Project duration + 7 years | Document Control |
| Cross-reference records (DEL-01.06, DEL-01.07, DEL-01.13) | Project duration + 7 years | Document Control |

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
