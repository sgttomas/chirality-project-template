# Specification: DEL-01.07 Hydraulic Analysis Report

**Document ID:** DEL-01.07-SP
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Scope

### 1.1 Purpose

This specification defines the requirements for the Hydraulic Analysis Report for the Puget Sound Optimization (PSO) project. The report shall document steady-state hydraulic analysis supporting final sizing and system performance verification for the booster pump station, manifold, and associated piping systems at Sumas Tank Farm.

### 1.2 Applicability

This specification applies to:
- FEED phase hydraulic model refinement and optimization (per SOW-0130)
- Detailed design phase hydraulic model update to IFC status (per SOW-0220)
- Coordination with TM hydraulic analyst and Puget system model
- All process systems within PKG-01 scope

### 1.3 Boundaries

| Boundary | Description |
|----------|-------------|
| In Scope | Steady-state hydraulic analysis, pump selection verification, NPSH analysis, system optimization, 6 operating cases |
| Out of Scope | Transient analysis (DEL-01.08), line sizing calculations (DEL-01.05), equipment sizing (DEL-01.04) |

---

## 2. Requirements

### 2.1 Functional Requirements

| Req ID | Requirement | Priority | Verification |
|--------|-------------|----------|--------------|
| FR-01 | Analysis shall demonstrate system capability to achieve 275,000 bpd sustainable flow | Mandatory | Calculation |
| FR-02 | Analysis shall demonstrate system capability to achieve 315,000 bpd peak flow | Mandatory | Calculation |
| FR-03 | Analysis shall verify adequate NPSH margin for all operating cases (NPSHa >= NPSHr + 1.0m minimum) | Mandatory | Calculation |
| FR-04 | Analysis shall optimize piping/valve sizes and pump performance | Mandatory | Review |
| FR-05 | Analysis shall be coordinated with TM Puget system model (per SOW-0130, SOW-0220) | Mandatory | Coordination |
| FR-06 | Analysis shall verify blending capability: 20%/80% baseline (SOW-0005); 10%-100% NEAT extended range (DBM) | Mandatory | Calculation |
| FR-07 | Analysis shall verify pump operating points within 70-110% BEP for all cases | Mandatory | Calculation |

### 2.2 Content Requirements

| Req ID | Requirement | Priority |
|--------|-------------|----------|
| CR-01 | Include executive summary with key findings | Mandatory |
| CR-02 | Include complete system description and boundaries | Mandatory |
| CR-03 | Document methodology, software, and assumptions | Mandatory |
| CR-04 | Include fluid property basis for all cases (Heavy, Light, Blended) | Mandatory |
| CR-05 | Include piping and equipment input data | Mandatory |
| CR-06 | Include pump curves and operating point verification (70-110% BEP) | Mandatory |
| CR-07 | Include pressure profiles for all operating cases (Cases 1-6) | Mandatory |
| CR-08 | Include NPSH verification for all pumps (NPSHa >= NPSHr + 1.0m) | Mandatory |
| CR-09 | Document optimization recommendations | Mandatory |
| CR-10 | Include model input/output appendices | Mandatory |

### 2.3 Performance Requirements

| Req ID | Requirement | Acceptance Criteria |
|--------|-------------|---------------------|
| PR-01 | System shall achieve target flow rates | Model demonstrates 275,000/315,000 bpd capability |
| PR-02 | Pump operating points within acceptable range | 70%-110% of BEP for all pumps, all cases |
| PR-03 | NPSH margin adequate | NPSHa >= NPSHr + 1.0m for all pumps, all cases |
| PR-04 | Line velocities within limits | Per DEL-01.05 line sizing criteria |
| PR-05 | System handles blending range | Baseline 20/80; Extended 10-100% NEAT per DBM |

### 2.4 Operating Case Requirements

| Req ID | Case | Description | Flow Rate | Fluid | Priority |
|--------|------|-------------|-----------|-------|----------|
| OC-01 | Case 1 | Normal - Sustainable | 1,822 m3/h | Blended 20/80 | Mandatory |
| OC-02 | Case 2 | Peak - Design | 2,100 m3/h | Blended 20/80 | Mandatory |
| OC-03 | Case 3 | Minimum Turndown | **TBD** | Blended 20/80 | Mandatory |
| OC-04 | Case 4 | Tank-to-Tank Transfer | **TBD** | **TBD** | Mandatory |
| OC-05 | Case 5 | Heavy NEAT | **TBD** | Heavy 100% | Mandatory |
| OC-06 | Case 6 | Light NEAT | **TBD** | Light 100% | Mandatory |

---

## 3. Standards

### 3.1 Applicable Codes and Standards

| Standard | Title | Application |
|----------|-------|-------------|
| API 610 | Centrifugal Pumps | Pump selection/application; 70-110% BEP operating range guideline |
| Hydraulic Institute Standards | Pump Application Guidelines | NPSH margin (1.0m minimum typical), operating range |
| CSA Z662 | Oil and Gas Pipeline Systems | Pipeline design |
| ASME B31.4 | Pipeline Transportation Systems for Liquids | Piping design |
| Crane TP-410 | Flow of Fluids | Pressure drop calculations (reference) |
| TM-**TBD** | Trans Mountain Engineering Standards | Project-specific requirements |

### 3.2 Regulatory Requirements

| Regulation | Jurisdiction | Application |
|------------|--------------|-------------|
| CER Regulations | Federal (Canada) | Pipeline operations |
| Title 49 CFR Part 195 | Federal (USA) | Hazardous liquid pipelines |

---

## 4. Verification

### 4.1 Verification Methods

| Method | Description | Applicability |
|--------|-------------|---------------|
| Model Validation | Comparison with existing system data | Model setup |
| Independent Review | Second engineer review of model/results | All analyses |
| TM Coordination Review | Review with TM hydraulic analyst (per SOW-0130, SOW-0220) | Model integration |
| Sensitivity Analysis | Assess impact of key variables | Critical parameters |

### 4.2 Acceptance Criteria

| Criteria ID | Criteria | Method |
|-------------|----------|--------|
| AC-01 | Flow rate targets achieved (275,000/315,000 bpd) | Model results |
| AC-02 | NPSH margins adequate (NPSHa >= NPSHr + 1.0m) | Calculation verification |
| AC-03 | Pump operating points acceptable (70-110% BEP) | Pump curve overlay |
| AC-04 | Model consistent with TM Puget system | TM review/coordination |
| AC-05 | All operating cases analyzed (Cases 1-6) | Completeness check |
| AC-06 | TM approval obtained | Sign-off |
| AC-07 | Blending capability verified (20/80 baseline; 10-100% NEAT extended) | Calculation verification |

### 4.3 Review Stages

| Stage | Milestone | Reviewer |
|-------|-----------|----------|
| IFR | FEED submission (refined model per SOW-0130) | Engineering Lead + TM Hydraulic Analyst |
| IFD | FEED completion | TM Review |
| IFC | Detailed Design completion (final model per SOW-0220) | TM Approval |

---

## 5. Documentation

### 5.1 Deliverable Documentation

| Document | Format | Quantity |
|----------|--------|----------|
| Hydraulic Analysis Report | PDF | 1 |
| Model Input/Output Files | Software native format | 1 set |
| Supporting Spreadsheets | Excel | As required |
| Executive Summary | PDF (within report) | 1 |

### 5.2 Records

| Record | Retention | Location |
|--------|-----------|----------|
| Review Comments | Project duration + 7 years | Document Control |
| Model Files (all versions) | Project duration + 7 years | Document Control |
| Coordination Records (TM) | Project duration + 7 years | Document Control |

### 5.3 Revision Control

| Revision | Description | Date |
|----------|-------------|------|
| Pass 1 | Initial draft generation | 2026-02-01 |
| Pass 2 | Cross-reference consistency check | 2026-02-01 |
| **TBD** | IFR submission (per SOW-0130) | **TBD** |
| **TBD** | IFD submission | **TBD** |
| **TBD** | IFC submission (per SOW-0220) | **TBD** |

---

*End of Specification*
