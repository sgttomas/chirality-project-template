# Specification: DEL-01.13 Operating Envelopes

**Document ID:** DEL-01.13-SP
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Scope

### 1.1 Purpose

This specification defines the requirements for the Operating Envelopes document for the Puget Sound Optimization (PSO) project. The Operating Envelopes establish the allowable operating conditions and constraints for the new booster pump station and manifold facilities at Sumas Tank Farm.

### 1.2 Applicability

This specification applies to:
- Detailed Design phase operating envelope definition
- IFC deliverables package (per SOW-0232)
- All new PSO facilities (booster pumps, manifold, blending systems)

### 1.3 Boundaries

| Boundary | Description |
|----------|-------------|
| In Scope | Operating envelopes for new PSO booster pump station and manifold facilities |
| Out of Scope | Existing facility operating limits (governed by existing OL&PDS) |

---

## 2. Requirements

### 2.1 Functional Requirements

| Req ID | Requirement | Priority | Verification |
|--------|-------------|----------|--------------|
| FR-01 | Operating Envelopes shall define allowable flow rate ranges | Mandatory | Review |
| FR-02 | Operating Envelopes shall define allowable pressure ranges (suction and discharge) | Mandatory | Review |
| FR-03 | Operating Envelopes shall define allowable temperature ranges | Mandatory | Review |
| FR-04 | Operating Envelopes shall define blending ratio constraints | Mandatory | Review |
| FR-05 | Operating Envelopes shall define individual pump operating maps | Mandatory | Review |
| FR-06 | Operating Envelopes shall define VFD speed ranges | Mandatory | Review |

### 2.2 Content Requirements

| Req ID | Requirement | Priority |
|--------|-------------|----------|
| CR-01 | Define operating modes (normal, startup, shutdown, turndown, upset) | Mandatory |
| CR-02 | Specify minimum and maximum throughput rates | Mandatory |
| CR-03 | Specify pump minimum flow requirements | Mandatory |
| CR-04 | Document blending control philosophy | Mandatory |
| CR-05 | Define constraints for tank-to-tank transfers | Mandatory |
| CR-06 | Identify relationship to OL&PDS protective settings | Mandatory |
| CR-07 | Define alarm and trip setpoints | Mandatory |

### 2.3 Performance Requirements

| Req ID | Requirement | Acceptance Criteria |
|--------|-------------|---------------------|
| PR-01 | Operating Envelopes shall support 275,000 bpd sustainable throughput | Confirmed by hydraulic analysis (DEL-01.07) |
| PR-02 | Operating Envelopes shall support 315,000 bpd peak throughput | Confirmed by hydraulic analysis (DEL-01.07) |
| PR-03 | Operating Envelopes shall prevent reduction of tank operating volume due to low suction | Confirmed by hydraulic analysis (DEL-01.07) |

---

## 3. Standards

### 3.1 Applicable Codes and Standards

| Standard | Title | Application |
|----------|-------|-------------|
| CSA Z662 | Oil and Gas Pipeline Systems | Operating requirements |
| API 610 | Centrifugal Pumps for Petroleum | Pump operating limits |
| API 682 | Pumps - Shaft Sealing Systems | Seal operating limits |
| HI 9.6.3 | Pump Allowable Operating Region | Pump envelope definition |
| ISA-18.2 | Alarm Management | Alarm setpoint definition |
| TM OL&PDS | Operating Limits and Protective Device Settings | Protective settings alignment |

### 3.2 Regulatory Requirements

| Regulation | Jurisdiction | Application |
|------------|--------------|-------------|
| CER OPR | Federal (Canada) | Operating integrity |
| PHMSA 49 CFR 195 | Federal (USA) | Pipeline operating requirements |

---

## 4. Verification

### 4.1 Verification Methods

| Method | Description | Applicability |
|--------|-------------|---------------|
| Document Review | Independent review of content completeness | All requirements |
| Hydraulic Verification | Confirm operating ranges are supported by hydraulic analysis (DEL-01.07) | FR-01, FR-02, PR-01, PR-02, PR-03 |
| Transient Verification | Confirm dynamic limits from transient analysis (DEL-01.08) | FR-01, FR-02 |
| Vendor Data Verification | Confirm pump envelopes align with vendor performance curves | FR-05, FR-06 |
| Equipment Sizing Verification | Confirm consistency with equipment sizing (DEL-01.04) | FR-01, FR-05 |
| OL&PDS Alignment | Verify consistency with TM OL&PDS | CR-06, CR-07 |

### 4.2 Acceptance Criteria

| Criteria ID | Criteria | Method |
|-------------|----------|--------|
| AC-01 | All operating parameters have defined ranges | Document Review |
| AC-02 | Operating ranges are within equipment design limits | Vendor Data Verification |
| AC-03 | Operating ranges are supported by hydraulic analysis | Hydraulic Verification |
| AC-04 | Protective settings are consistent with operating envelopes | OL&PDS Alignment |
| AC-05 | Blending ratio constraints are documented and approved by TM (OI-002 resolved) | TM Review |

### 4.3 Review Stages

| Stage | Milestone | Reviewer |
|-------|-----------|----------|
| IFR | Detailed Design 60% | Engineering Lead |
| IFD | Detailed Design 90% | TM Review |
| IFC | Detailed Design completion | TM Approval + Operations |

---

## 5. Documentation

### 5.1 Deliverable Documentation

| Document | Format | Quantity |
|----------|--------|----------|
| Operating Envelopes Document | PDF | 1 (plus revisions) |
| Native Files | Word/Excel | 1 set |
| Pump Performance Curves | PDF | As applicable |
| Supporting Calculations | PDF | As applicable |

### 5.2 Records

| Record | Retention | Location |
|--------|-----------|----------|
| TM Review Comments | Project duration + 7 years | Document Control |
| OL&PDS Coordination Records | Project duration + 7 years | Document Control |
| Vendor Data References | Project duration + 7 years | Document Control |
| Hydraulic Verification Records (DEL-01.07) | Project duration + 7 years | Document Control |

### 5.3 Related Deliverables

| Deliverable ID | Relationship |
|----------------|--------------|
| DEL-01.01 | Design Basis Memorandum provides design parameters |
| DEL-01.04 | Equipment Sizing Calculations define capacity limits |
| DEL-01.07 | Hydraulic Analysis Report defines pressure/flow envelopes |
| DEL-01.08 | Transient Analysis defines dynamic limits |
| DEL-01.09 | Process Datasheets document equipment limits |
| DEL-01.15 | HAZOP reviews operating envelopes |
| DEL-07.09 | Control Narratives implement operating constraints |

### 5.4 Revision Control

| Revision | Description | Date |
|----------|-------------|------|
| Pass 1 | Initial draft generation | 2026-02-01 |
| Pass 2 | Cross-reference consistency check | 2026-02-01 |
| **TBD** | IFR submission | **TBD** |
| **TBD** | IFC submission | **TBD** |

---

*End of Specification*
