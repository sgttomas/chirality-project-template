# Specification: DEL-01.11 Utility Summary

**Document ID:** DEL-01.11-SP
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Scope

### 1.1 Purpose

This specification defines the requirements for the Utility Summary table for the Puget Sound Optimization (PSO) project. The Utility Summary consolidates all utility demands for new and modified facilities at Sumas Tank Farm to support detailed design, procurement, and construction planning.

### 1.2 Applicability

This specification applies to:
- Detailed Design phase utility demand compilation
- IFC deliverables package (per SOW-0232)
- All utility types serving new PSO facilities

### 1.3 Boundaries

| Boundary | Description |
|----------|-------------|
| In Scope | All utility demands for new PSO facilities (booster pumps, manifold, electrical building, containment) |
| Out of Scope | Existing facility utility demands (unless modified by PSO scope) |

---

## 2. Requirements

### 2.1 Functional Requirements

| Req ID | Requirement | Priority | Verification |
|--------|-------------|----------|--------------|
| FR-01 | Utility Summary shall list all utility types consumed by PSO facilities per DEL-01.11-DS Section 3.1 | Mandatory | Review |
| FR-02 | Utility Summary shall provide connected loads for each consumer | Mandatory | Review |
| FR-03 | Utility Summary shall provide operating loads for each consumer | Mandatory | Review |
| FR-04 | Utility Summary shall identify peak/upset demands where applicable | Mandatory | Review |
| FR-05 | Utility Summary shall provide totals by utility type | Mandatory | Calculation verification |

### 2.2 Content Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| CR-01 | Include electrical power demands by voltage level | Mandatory | DEL-06.03 (Electrical Load List) |
| CR-02 | Include instrument air consumption | Mandatory | DEL-01.03 (P&IDs), ISA-5.1 |
| CR-03 | Include cooling water demands (if applicable) | Mandatory | DEL-01.09 (Process Datasheets) |
| CR-04 | Include fire water demands | Mandatory | Fire protection design |
| CR-05 | Include building utility demands (HVAC, lighting) | Mandatory | DEL-09.01 (HVAC calculations) |
| CR-06 | Cross-reference equipment tags to equipment list | Mandatory | DEL-03.01 (Equipment List) |

### 2.3 Format Requirements

| Req ID | Requirement | Acceptance Criteria |
|--------|-------------|---------------------|
| FM-01 | Utility Summary shall be provided in tabular format | Excel + PDF per SOW-0232 |
| FM-02 | Table columns shall be clearly labeled with units per DEL-01.11-DS Section 4.1 | All columns have headers and units |
| FM-03 | Summary totals shall be provided for each utility type | Subtotal rows present |
| FM-04 | Document shall include revision history | Revision table on cover sheet |

---

## 3. Standards

### 3.1 Applicable Codes and Standards

| Standard | Title | Application |
|----------|-------|-------------|
| TM Engineering Standards | Trans Mountain project-specific standards | Utility summary format (**TBD**) |
| API RP 500 | Classification of Locations for Electrical Installations | Area classification for electrical utilities |
| API RP 686 | Machinery Installation and Installation Design | Rotating equipment utility requirements |
| ISA-5.1 | Instrumentation Symbols and Identification | Instrument air utility requirements |
| NFPA 30 | Flammable and Combustible Liquids Code | Fire water requirements basis |

### 3.2 Regulatory Requirements

| Regulation | Jurisdiction | Application |
|------------|--------------|-------------|
| CER OPR | Federal (Canada) | Safety systems including fire protection |
| BC Fire Code | Provincial (BC) | Fire water requirements |
| WISHA/OSHA | State (WA) / Federal (USA) | **TBD** - Cross-border aspects |

---

## 4. Verification

### 4.1 Verification Methods

| Method | Description | Applicability |
|--------|-------------|---------------|
| Document Review | Independent review of content completeness | All requirements |
| Cross-Reference Check | Verify consistency with equipment list (DEL-03.01) and load lists (DEL-06.03, DEL-09.01) | FR-01 through FR-05, CR-01 through CR-06 |
| Calculation Verification | Confirm totals are accurate | FR-05 |

### 4.2 Acceptance Criteria

| Criteria ID | Criteria | Method |
|-------------|----------|--------|
| AC-01 | All utility types per DEL-01.11-DS Section 3.1 identified and quantified | Document Review |
| AC-02 | Values consistent with source documents (DEL-03.01, DEL-06.03, DEL-09.01, DEL-01.09) | Cross-Reference Check |
| AC-03 | Totals are mathematically correct | Calculation Verification |
| AC-04 | All equipment tags traceable to equipment list (DEL-03.01) | Cross-Reference Check |

### 4.3 Review Stages

| Stage | Milestone | Reviewer |
|-------|-----------|----------|
| IFR | Detailed Design 30% | Engineering Lead |
| IFD | Detailed Design 60% | TM Review |
| IFC | Detailed Design completion | TM Approval |

---

## 5. Documentation

### 5.1 Deliverable Documentation

| Document | Format | Quantity |
|----------|--------|----------|
| Utility Summary Table | Excel + PDF | 1 set |
| Revision History | Within document | Included |

### 5.2 Records

| Record | Retention | Location |
|--------|-----------|----------|
| Review Comments | Project duration + 7 years | Document Control |
| Source Data (equipment datasheets) | Project duration + 7 years | Document Control |
| Approval Records | Permanent | Document Control |

### 5.3 Revision Control

| Revision | Description | Date |
|----------|-------------|------|
| Pass 1 | Initial draft generation | 2026-02-01 |
| Pass 2 | Cross-reference consistency check | 2026-02-01 |
| **TBD** | IFR submission | **TBD** |
| **TBD** | IFC submission | **TBD** |

---

*End of Specification*
