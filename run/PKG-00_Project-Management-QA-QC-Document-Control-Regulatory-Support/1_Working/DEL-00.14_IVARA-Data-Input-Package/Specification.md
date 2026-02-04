# Specification: DEL-00.14 IVARA Data Input Package

**Document ID:** DEL-00.14-SP
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** Draft - Cross-Referenced

---

## 1. Scope

### 1.1 Purpose

This specification defines the requirements for the IVARA Data Input Package to be developed by the Engineering Contractor for the Puget Sound Optimization Project (PSO). The IVARA Data Input Package provides equipment data inputs for TM's maintenance management software (IVARA) to support maintenance database population.

### 1.2 Applicability

This specification applies to:
- All new equipment within PSO scope at Sumas Tank Farm
- Data inputs for TM IVARA maintenance management system
- Equipment from all disciplines (mechanical, electrical, instrumentation)

### 1.3 Boundaries

**In Scope:**
- Equipment identification and attributes
- Equipment specifications and parameters
- Maintenance-relevant data fields
- Documentation links and references

**Out of Scope:**
- IVARA system configuration (TM responsibility)
- Maintenance scheduling setup (TM responsibility)
- Work order generation (TM responsibility)
- Existing equipment data updates (unless within PSO scope)

---

## 2. Requirements

### 2.1 Functional Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| IVARA-F-001 | Package shall provide data inputs per TM IVARA software requirements | Mandatory | SOW-0217 |
| IVARA-F-002 | Package shall cover all new equipment within PSO scope | Mandatory | SOW-0217 |
| IVARA-F-003 | Package shall use TM-provided template format | Mandatory | **ASSUMPTION** |
| IVARA-F-004 | Package shall be compatible with TM IVARA database import | Mandatory | **ASSUMPTION** |
| IVARA-F-005 | Package shall include all mandatory data fields per TM requirements | Mandatory | **TBD** |

### 2.2 Content Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| IVARA-C-001 | Package shall include equipment tag per TM convention | Mandatory | **ASSUMPTION** |
| IVARA-C-002 | Package shall include equipment description | Mandatory | **ASSUMPTION** |
| IVARA-C-003 | Package shall include equipment type/class | Mandatory | **ASSUMPTION** |
| IVARA-C-004 | Package shall include manufacturer and model | Mandatory | **ASSUMPTION** |
| IVARA-C-005 | Package shall include installation location | Mandatory | **ASSUMPTION** |
| IVARA-C-006 | Package shall include serial number | **ASSUMPTION** | Best Practice |
| IVARA-C-007 | Package shall include system/sub-system assignment | **ASSUMPTION** | Best Practice |
| IVARA-C-008 | Package shall include criticality rating | **TBD** | **TBD** |
| IVARA-C-009 | Package shall include maintenance strategy | **TBD** | **TBD** |
| IVARA-C-010 | Package shall include maintenance intervals | **TBD** | **TBD** |
| IVARA-C-011 | Package shall include links to O&M documentation | **ASSUMPTION** | Best Practice |

### 2.3 Format Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| IVARA-FM-001 | Package shall use TM-provided IVARA template | Mandatory | **TBD** |
| IVARA-FM-002 | Package shall be provided in .xlsx or .csv format (per TM) | Mandatory | **TBD** |
| IVARA-FM-003 | Package shall comply with TM data schema | Mandatory | **TBD** |
| IVARA-FM-004 | Package shall use TM-approved tag naming convention | Mandatory | DEL-00.02 |

### 2.4 Submission Requirements

| Req ID | Requirement | Priority | Source |
|--------|-------------|----------|--------|
| IVARA-S-001 | Package shall be submitted to TM for IVARA database population | Mandatory | SOW-0217 |
| IVARA-S-002 | Initial package shall be submitted with IFC deliverables | **ASSUMPTION** | Best Practice |
| IVARA-S-003 | Final package shall be submitted for turnover | Mandatory | **ASSUMPTION** |

---

## 3. Standards

### 3.1 Applicable Standards

| Standard | Description | Application |
|----------|-------------|-------------|
| TM Standards and Specifications | TM corporate standards | Data requirements (**TBD** - Attachment A08) |
| TM IVARA System Requirements | IVARA data schema and format | Template and fields (**TBD**) |
| TM Tag Numbering Convention | Equipment tagging standard | Tag format (via DEL-00.02) |

### 3.2 Codes and Regulations

- No specific codes or regulations apply directly to IVARA data format
- Equipment data supports maintenance program compliance

### 3.3 TM-Specific Requirements

- IVARA template per TM requirements (**TBD**)
- Data field definitions per TM IVARA schema (**TBD**)
- Import format compatibility (**TBD**)

---

## 4. Verification

### 4.1 Verification Methods

| Req ID | Method | Acceptance Criteria |
|--------|--------|---------------------|
| IVARA-F-001 | Inspection | Data format matches TM requirements |
| IVARA-F-002 | Audit | All PSO equipment included |
| IVARA-F-003 | Inspection | Template format used correctly |
| IVARA-F-004 | Test | TM confirms data imports successfully |
| IVARA-F-005 | Inspection | All mandatory fields populated |
| IVARA-C-001 to C-005 | Inspection | All mandatory content fields present |
| IVARA-C-006 | Inspection | Serial numbers populated where available |
| IVARA-C-007 | Inspection | System assignments complete |
| IVARA-C-008 to C-010 | Inspection | Maintenance fields per TM requirements |
| IVARA-C-011 | Inspection | Documentation links populated |
| IVARA-FM-001 to FM-004 | Inspection | Format requirements met |
| IVARA-S-001 to S-003 | Review | Submission records complete |

### 4.2 Review and Approval

| Milestone | Review Activity | Approver |
|-----------|-----------------|----------|
| Draft Package | Internal review | Contractor Engineering Lead |
| Package Submission | TM review | TM Project Team |
| Database Import | Import verification | TM IVARA Administrator |

### 4.3 Quality Checks

- Cross-check equipment list against discipline deliverables
- Validate data completeness for mandatory fields
- Verify tag naming convention compliance
- Check format compatibility with TM template

---

## 5. Documentation

### 5.1 Deliverables

| Document | Format | Timing |
|----------|--------|--------|
| IVARA Data Input Package | .xlsx / .csv (per TM) | Per schedule |
| Data Validation Report | .pdf | With submission (**ASSUMPTION**) |

### 5.2 Records

- Package transmittal records
- TM review comments and responses
- Import confirmation records
- Package revision history

### 5.3 Retention

- All package versions retained per TM document retention requirements (**TBD**)
- Package included in Final Documentation Package

---

## 6. Notes and Assumptions

1. **ASSUMPTION:** TM will provide IVARA template and data field requirements.
2. **ASSUMPTION:** Data fields listed are typical; actual fields TBD per TM requirements.
3. **TBD:** TM IVARA template and specific data schema.
4. **TBD:** Equipment criticality and maintenance strategy definitions.
5. **ASSUMPTION:** Package submission timing aligns with equipment turnover milestones.

---

*Generated: Pass 1 - Initial Draft*
*Updated: Pass 2 - Cross-Reference Consistency Check (2026-02-01)*
*Source: PSO Decomposition REVISED v2, SOW Section 3.2.2.17*
