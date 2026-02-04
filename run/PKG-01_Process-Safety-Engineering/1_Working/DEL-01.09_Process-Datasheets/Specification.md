# Specification: DEL-01.09 Process Datasheets

**Document ID:** DEL-01.09-SP
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Scope

### 1.1 Purpose

This specification defines the requirements for Process Datasheets for the Puget Sound Optimization (PSO) project. Process datasheets shall provide process conditions and data required by mechanical and instrumentation disciplines for equipment specification, procurement, and installation.

### 1.2 Applicability

This specification applies to:
- FEED phase preliminary process datasheets (per SOW-0119, SOW-0177)
- Detailed design phase complete process datasheets (per SOW-0224)
- All mechanical and instrumentation equipment within PKG-01 scope
- Packaged equipment components requiring process data

### 1.3 Boundaries

| Boundary | Description |
|----------|-------------|
| In Scope | Process conditions, fluid properties, operating ranges for all equipment |
| Out of Scope | Mechanical details (PKG-03), Instrument specifications (PKG-07), Material requisitions (DEL-01.16) |

---

## 2. Requirements

### 2.1 Functional Requirements

| Req ID | Requirement | Priority | Verification |
|--------|-------------|----------|--------------|
| FR-01 | Datasheets shall provide process conditions for all tagged equipment | Mandatory | Review |
| FR-02 | Datasheets shall include normal, minimum, and maximum operating conditions | Mandatory | Review |
| FR-03 | Datasheets shall include design conditions | Mandatory | Review |
| FR-04 | Datasheets shall include fluid properties at operating conditions | Mandatory | Review |
| FR-05 | Datasheets shall reference applicable P&ID | Mandatory | Review |
| FR-06 | Datasheets shall be consistent with hydraulic analysis | Mandatory | Cross-check |

### 2.2 Content Requirements

| Req ID | Requirement | Priority |
|--------|-------------|----------|
| CR-01 | Include equipment tag number and description | Mandatory |
| CR-02 | Include P&ID reference | Mandatory |
| CR-03 | Include service description | Mandatory |
| CR-04 | Include operating pressure (normal/min/max) | Mandatory |
| CR-05 | Include operating temperature (normal/min/max) | Mandatory |
| CR-06 | Include design pressure and temperature | Mandatory |
| CR-07 | Include flow rate (normal/min/max) | Mandatory (flow equipment) |
| CR-08 | Include fluid density and viscosity | Mandatory |
| CR-09 | Include corrosivity/special fluid characteristics | As applicable |
| CR-10 | Include hazardous area classification | Mandatory |

### 2.3 Performance Requirements

| Req ID | Requirement | Acceptance Criteria |
|--------|-------------|---------------------|
| PR-01 | Process data shall support equipment selection | Mechanical/I&C disciplines confirm adequacy |
| PR-02 | Data shall be consistent across related datasheets | Cross-check verification |
| PR-03 | Data shall be traceable to source calculations | Reference to DEL-01.04/05/06/07 |

---

## 3. Standards

### 3.1 Applicable Codes and Standards

| Standard | Title | Application |
|----------|-------|-------------|
| API 610 | Centrifugal Pumps for Petroleum, Petrochemical and Natural Gas Industries | Pump datasheet format reference |
| API 526 | Flanged Steel Pressure-relief Valves | Relief valve datasheet reference |
| API 650 | Welded Tanks for Oil Storage | Tank datasheet reference (if applicable) |
| ISA 75.01 | Flow Equations for Sizing Control Valves | Valve sizing data |
| ISA 20 | Specification Forms for Process Measurement and Control Instruments | Instrument datasheet reference |
| IEC 60534 | Industrial-process control valves | Control valve specifications |
| TM-**TBD** | Trans Mountain Datasheet Templates | Project-specific templates |

### 3.2 Template Requirements

| Equipment Type | Template Source | Notes |
|----------------|-----------------|-------|
| Centrifugal Pumps | TM or API 610 | **TBD** - Confirm with TM |
| Control Valves | TM or ISA 75.01/IEC 60534 | **TBD** |
| Block Valves | TM Standard | **TBD** |
| Relief Valves | TM or API 526 | **TBD** |
| Flow Meters | TM or ISA 20 | **TBD** |
| General Instruments | TM or ISA 20 | **TBD** |
| Tanks/Vessels | TM or API 650 | **TBD** - If applicable |

---

## 4. Verification

### 4.1 Verification Methods

| Method | Description | Applicability |
|--------|-------------|---------------|
| Document Review | Review of completeness and accuracy | All datasheets |
| Interdisciplinary Check | Mechanical/I&C review of process data | All datasheets |
| Calculation Cross-check | Verify against source calculations | Key parameters |
| P&ID Consistency Check | Verify tag numbers and references | All datasheets |

### 4.2 Acceptance Criteria

| Criteria ID | Criteria | Method |
|-------------|----------|--------|
| AC-01 | All required fields populated per CR-01 through CR-10 | Completeness check |
| AC-02 | Data consistent with DEL-01.07 hydraulic analysis | Cross-check |
| AC-03 | Data consistent with DEL-01.01 DBM | Cross-check |
| AC-04 | Data consistent with DEL-01.04 equipment sizing | Cross-check |
| AC-05 | Data consistent with DEL-01.05 line sizing | Cross-check |
| AC-06 | Tag numbers match P&IDs (DEL-01.03) | P&ID comparison |
| AC-07 | Mechanical/I&C disciplines confirm adequacy | Discipline review |
| AC-08 | TM approval obtained | Sign-off |

### 4.3 Review Stages

| Stage | Milestone | Reviewer | Deliverable Status |
|-------|-----------|----------|-------------------|
| IFR | FEED submission (preliminary datasheets) | Engineering Lead | Preliminary datasheets with TBD acceptable |
| IFD | FEED completion | TM Review | Complete datasheets |
| IFC | Detailed Design completion | TM Approval | Final datasheets with vendor data |

---

## 5. Documentation

### 5.1 Deliverable Documentation

| Document | Format | Quantity |
|----------|--------|----------|
| Process Datasheet Set | PDF | 1 set (all equipment) |
| Datasheet Native Files | Excel or Word (editable) | 1 set |
| Datasheet Index | Excel | 1 |

### 5.2 Records

| Record | Retention | Location |
|--------|-----------|----------|
| Review Comments | Project duration + 7 years | Document Control |
| Revision History | Permanent | Within each datasheet |
| Approval Records | Project duration + 7 years | Document Control |

### 5.3 Revision Control

| Revision | Description | Date |
|----------|-------------|------|
| Pass 1 | Initial draft generation | 2026-02-01 |
| Pass 2 | Cross-reference consistency check | 2026-02-01 |
| A | IFR submission (preliminary datasheets) | **TBD** |
| 0 | IFD submission (complete datasheets) | **TBD** |
| 1 | IFC submission (final datasheets) | **TBD** |

---

*End of Specification*
