# Specification: DEL-01.16 Material Requisitions (Process) (Engineering)

**Document ID:** DEL-01.16-SP
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Scope

### 1.1 Purpose

This specification defines the requirements for Process Engineering Material Requisitions (MRs) for the Puget Sound Optimization (PSO) project. MRs are procurement documents that define technical requirements for equipment and materials to be purchased.

### 1.2 Boundaries

- **In Scope:** Process-prepared MRs for:
  - Booster pumps (5 units)
  - Sump tank and reinjection pumps
  - Dewatering equipment
  - Process valves (where specified by Process)
  - Piping bulks (process specification)
  - Flow meters and temperature relief valves
  - Other process equipment as identified in SOW

- **Out of Scope:**
  - Electrical equipment MRs (PKG-06)
  - Instrumentation MRs (PKG-07, except flow meters)
  - Piping fabrication MRs (PKG-02)
  - Structural/Civil MRs (PKG-04/05)

### 1.3 Interfaces

| Interface | Description |
|-----------|-------------|
| TM Procurement | Coordination on vendor lists, commercial terms, schedule |
| TM Engineering | Technical review and approval of specifications |
| Other Disciplines | Interface specifications for packaged equipment |
| Vendors | Technical clarifications during bidding |

---

## 2. Requirements

### 2.1 General MR Requirements

| ID | Requirement | Priority |
|----|-------------|----------|
| REQ-01 | MRs shall be prepared for all equipment requiring procurement | Mandatory |
| REQ-02 | MRs shall use TM-approved templates where available | Mandatory |
| REQ-03 | MRs shall include complete technical specifications | Mandatory |
| REQ-04 | MRs shall reference applicable industry standards | Mandatory |
| REQ-05 | MRs shall include process datasheets per DEL-01.09 | Mandatory |
| REQ-06 | MRs shall identify approved/preferred vendors | Mandatory |
| REQ-07 | MRs shall specify testing and inspection requirements | Mandatory |
| REQ-08 | MRs shall specify spare parts requirements | Recommended |

### 2.2 Equipment-Specific Requirements

**Booster Pumps (REQ-10 series):**

| ID | Requirement | Priority |
|----|-------------|----------|
| REQ-10 | Pumps shall be API 610 VS6 type per SOW Section 2.3.1.2 | Mandatory |
| REQ-11 | Pumps shall be rated for VFD operation | Mandatory |
| REQ-12 | Hydraulic performance shall cover full operating range per DEL-01.04 | Mandatory |
| REQ-13 | Materials shall be suitable for crude oil service | Mandatory |
| REQ-14 | Mechanical seals shall be API 682 compliant | Mandatory |
| REQ-15 | Shop testing per API 610 required | Mandatory |

**Valves (REQ-20 series):**

| ID | Requirement | Priority |
|----|-------------|----------|
| REQ-20 | Valves shall meet applicable API standards | Mandatory |
| REQ-21 | Materials shall match piping class specifications per PKG-02 | Mandatory |
| REQ-22 | Actuated valves shall include actuator specifications | Mandatory |
| REQ-23 | Fire-safe valves required where specified | Mandatory |

**Flow Meters (REQ-30 series):**

| ID | Requirement | Priority |
|----|-------------|----------|
| REQ-30 | Flow meters shall be custody transfer grade accuracy (per DEL-01.01) | **TBD** |
| REQ-31 | Flow meters shall be suitable for crude oil service | Mandatory |
| REQ-32 | Communication protocol shall match DCS requirements per PKG-07 | Mandatory |
| REQ-33 | Factory calibration required | Mandatory |

### 2.3 Documentation Requirements

| Requirement | Description |
|-------------|-------------|
| Datasheets | Complete process datasheets (DEL-01.09) attached |
| Drawings | P&IDs (DEL-01.03), GAs, and other reference drawings listed |
| Standards | All applicable standards clearly referenced |
| Vendor Data | Specify vendor documentation requirements |
| QA/QC | Quality assurance/control requirements specified |

---

## 3. Standards

### 3.1 Applicable Standards

| Standard | Equipment | Description |
|----------|-----------|-------------|
| API 610 | Pumps | Centrifugal Pumps for Petroleum Industry |
| API 682 | Pump Seals | Pumps - Shaft Sealing Systems |
| API 600 | Valves | Steel Gate Valves |
| API 602 | Valves | Steel Gate, Globe, and Check Valves |
| API 6D | Valves | Pipeline Valves |
| ASME B16.5 | Flanges | Pipe Flanges and Flanged Fittings |
| ASME B31.4 | Piping | Pipeline Transportation Systems |
| CSA Z662 | General | Oil and Gas Pipeline Systems |

### 3.2 TM Standards

| Standard | Description |
|----------|-------------|
| TM Equipment Specifications | **TBD** - Company-specific requirements |
| TM Material Standards | **TBD** - Material selection requirements |
| TM Procurement Procedures | **TBD** - Procurement process requirements |

### 3.3 Compliance Requirements

- All MRs shall comply with TM procurement procedures
- Equipment shall meet or exceed TM minimum specifications
- Deviations from TM standards require approval per TM change control procedures

---

## 4. Verification

### 4.1 Verification Methods

| Requirement | Method | Acceptance Criteria |
|-------------|--------|---------------------|
| REQ-01 | Review | MR exists for each equipment item per DEL-01.07 |
| REQ-02 | Review | TM template used correctly |
| REQ-03 | Review | Technical spec complete per checklist |
| REQ-04 | Review | Standards referenced and current |
| REQ-05 | Cross-check | Datasheet (DEL-01.09) attached and matches |
| REQ-06 | Review | Vendor list included |
| REQ-07 | Review | Test requirements specified |

### 4.2 Review Checklist

- [ ] MR number assigned per project convention
- [ ] Equipment tag matches equipment list (DEL-01.07)
- [ ] Technical specification complete
- [ ] Process datasheet attached (current revision per DEL-01.09)
- [ ] Reference drawings listed with revisions (DEL-01.03)
- [ ] Applicable standards referenced
- [ ] Vendor list included
- [ ] Testing requirements specified
- [ ] Spare parts requirements included
- [ ] Quality requirements specified
- [ ] Delivery requirements stated

### 4.3 Approval Requirements

| Approval | Approver | Timing |
|----------|----------|--------|
| Technical Review | Lead Process Engineer | Before issue |
| TM Technical Approval | TM Engineering | Before bid issue |
| Commercial Approval | TM Procurement | Before bid issue |

---

## 5. Documentation

### 5.1 Deliverable Documents

| Document | Format | Purpose |
|----------|--------|---------|
| Material Requisition Package | PDF + native | Complete procurement package |
| Technical Specification | PDF + Word | Equipment technical requirements |
| Process Datasheet (DEL-01.09) | PDF + Excel | Equipment parameters |

### 5.2 Supporting Documentation

- Equipment sizing calculations (DEL-01.04 - basis for specifications)
- Vendor technical clarifications
- Bid evaluation documentation
- TM approval correspondence

### 5.3 Revision Control

- MRs follow project document revision procedures
- Revisions during bidding tracked and communicated to bidders
- Final specifications incorporated into purchase order
- **TBD** - Specific revision requirements per TM procedures

---

*End of Specification*
