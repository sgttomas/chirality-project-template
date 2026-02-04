# Datasheet: DEL-00.14 IVARA Data Input Package

**Document ID:** DEL-00.14-DS
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** Draft - Cross-Referenced

---

## 1. Identification

| Attribute | Value |
|-----------|-------|
| **Deliverable ID** | DEL-00.14 |
| **Deliverable Name** | IVARA Data Input Package |
| **Parent Package** | PKG-00 Project Management, QA/QC, Document Control & Regulatory Support |
| **Discipline** | Project Controls / Maintenance |
| **Deliverable Type** | Data |
| **Responsible Party** | Engineering Contractor |
| **Project** | Puget Sound Optimization Project (PSO) |
| **Facility** | Sumas Tank Farm (Sumas Terminal) |

---

## 2. Attributes

### 2.1 Physical/Format Attributes

| Attribute | Value |
|-----------|-------|
| **Format** | Data files per TM IVARA system requirements |
| **Template Source** | TM-provided IVARA templates (**TBD**) |
| **Native File Format** | .xlsx, .csv, or TM-specified format (**TBD**) |
| **Data Structure** | Per TM IVARA database schema (**TBD**) |
| **Version Control** | Sequential revision numbering |

### 2.2 Content Attributes

| Attribute | Value |
|-----------|-------|
| **Scope Coverage** | Equipment data for TM maintenance software (IVARA) |
| **Equipment Coverage** | All new equipment within PSO scope |
| **Data Types** | Equipment identification, specifications, maintenance requirements |
| **Integration** | Supports TM maintenance database population |

### 2.3 Key Data Fields (**ASSUMPTION** - per typical maintenance database)

| Field Name | Description | Mandatory |
|------------|-------------|-----------|
| Equipment Tag | Unique identifier per TM tagging convention | Yes |
| Equipment Description | Descriptive name | Yes |
| Equipment Type | Category/class | Yes |
| Manufacturer | Equipment manufacturer | Yes |
| Model | Manufacturer model number | Yes |
| Serial Number | Unique serial number | **ASSUMPTION** |
| Location | Installation location | Yes |
| System | Parent system assignment | **ASSUMPTION** |
| Criticality | Criticality rating | **TBD** |
| Maintenance Strategy | Preventive/predictive/corrective | **TBD** |
| Maintenance Intervals | PM intervals | **TBD** |
| Spare Parts | Associated spare parts list | **TBD** |
| Documentation Links | Links to O&M manuals, drawings | **ASSUMPTION** |

---

## 3. Conditions

### 3.1 Prerequisites

- TM IVARA template and data requirements
- Equipment list (DEL-03.01)
- Equipment datasheets from all disciplines
- TM tagging/numbering conventions

### 3.2 Dependencies

| Dependency | Source | Status |
|------------|--------|--------|
| IVARA Template/Format | TM | **TBD** |
| Equipment List | DEL-03.01 (Mechanical) | Pending |
| Equipment Datasheets | Various PKGs | Pending |
| Instrument Index | DEL-07.02 (I&C) | Pending |
| Electrical Equipment List | DEL-06.03 (Electrical) | Pending |
| TM Tagging Convention | TM / DEL-00.02 | **TBD** |

### 3.3 Constraints

- Data must be compatible with TM IVARA system
- Data format must match TM template requirements
- Equipment tags must follow TM numbering convention

---

## 4. Construction / Compilation

### 4.1 Development Approach

| Phase | Activity |
|-------|----------|
| Planning | Obtain IVARA template and requirements from TM |
| Data Collection | Compile equipment data from discipline deliverables |
| Data Population | Populate IVARA template with equipment data |
| Validation | Validate data completeness and format |
| Submission | Submit to TM for IVARA database population |

### 4.2 Update Frequency

- Initial submission with IFC deliverables (**ASSUMPTION**)
- Updates as equipment data is finalized (vendor data, as-built)
- Final submission for turnover

### 4.3 Quality Control

- Validation against equipment lists and datasheets
- Format compliance check against IVARA template
- Completeness check for mandatory fields

---

## 5. References

### 5.1 Source Documents

| Reference | Document | Section |
|-----------|----------|---------|
| SOW-0217 | Exhibit A - Scope of Work PS.pdf | Section 3.2.2.17 (p15) |

### 5.2 Related Deliverables

| Deliverable ID | Name | Relationship |
|----------------|------|--------------|
| DEL-03.01 | Mechanical Equipment List | Source for mechanical equipment data |
| DEL-03.02 | Mechanical Equipment Datasheets | Source for mechanical specs |
| DEL-06.03 | Electrical Equipment List | Source for electrical equipment data |
| DEL-07.02 | Instrument Index | Source for instrument data |
| DEL-00.15 | O&M Binders | Documentation links |
| DEL-00.02 | Document & Tag Numbering Instruction Plan | Tag numbering reference |

### 5.3 Applicable Standards

- TM Standards and Specifications (**TBD** - Attachment A08 not available)
- TM IVARA system requirements (**TBD**)

---

## 6. Notes and Assumptions

1. **ASSUMPTION:** IVARA data format will be provided by TM as template.
2. **ASSUMPTION:** Data fields listed are based on typical maintenance database; actual fields TBD per TM.
3. **TBD:** TM IVARA template and specific data requirements.
4. **TBD:** Equipment criticality and maintenance strategy requirements.
5. **ASSUMPTION:** IVARA data submission timing aligns with equipment turnover.

---

*Generated: Pass 1 - Initial Draft*
*Updated: Pass 2 - Cross-Reference Consistency Check (2026-02-01)*
*Source: PSO Decomposition REVISED v2, DEL-00.14 Context, SOW Section 3.2.2.17*
