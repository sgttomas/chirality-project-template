# Procedure: DEL-00.14 IVARA Data Input Package

**Document ID:** DEL-00.14-PR
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** Draft - Cross-Referenced

---

## 1. Purpose

### 1.1 Objective

This procedure defines the step-by-step process for developing, validating, and submitting the IVARA Data Input Package for the Puget Sound Optimization Project (PSO).

### 1.2 Scope

This procedure covers:
- IVARA template acquisition and setup
- Equipment data collection from discipline deliverables
- Data population and validation
- Package submission and TM review
- Package updates and finalization

---

## 2. Prerequisites

### 2.1 Required Inputs

| Input | Source | Status |
|-------|--------|--------|
| TM IVARA Template | TM | **TBD** |
| TM Data Field Definitions | TM | **TBD** |
| Mechanical Equipment List | DEL-03.01 | Pending |
| Mechanical Equipment Datasheets | DEL-03.02 | Pending |
| Electrical Equipment List | DEL-06.03 | Pending |
| Instrument Index | DEL-07.02 | Pending |
| Tag Numbering Instruction Plan | DEL-00.02 | Pending |
| Vendor Data | Vendors | As received |

### 2.2 Required Resources

| Resource | Description |
|----------|-------------|
| Data Coordinator | IVARA package owner/compiler |
| Discipline Leads | Data providers (Mechanical, Electrical, I&C) |
| Document Controller | Transmittal and registration |
| TM IVARA Administrator | TM contact for template/import |

### 2.3 Required Authorizations

| Authorization | Holder |
|---------------|--------|
| Package Internal Approval | Contractor Engineering Lead |
| Package Acceptance | TM IVARA Administrator |

---

## 3. Steps

### 3.1 Setup and Template Acquisition

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.1.1 | Request IVARA template from TM | Data Coordinator | Template request |
| 3.1.2 | Obtain IVARA template and field definitions | TM | Template received |
| 3.1.3 | Review template fields and understand requirements | Data Coordinator | Field mapping notes |
| 3.1.4 | Request clarification from TM on any unclear fields | Data Coordinator | Clarifications received |
| 3.1.5 | Map template fields to data sources (deliverables) | Data Coordinator | Field mapping table |

### 3.2 Equipment Identification

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.2.1 | Compile master equipment list from discipline lists | Data Coordinator | Master equipment list |
| 3.2.2 | Cross-check against P&IDs for completeness | Data Coordinator | Verified list |
| 3.2.3 | Confirm equipment tags per TM convention (DEL-00.02) | Data Coordinator | Tags validated |
| 3.2.4 | Identify equipment requiring IVARA data | Data Coordinator | IVARA equipment list |

### 3.3 Data Collection

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.3.1 | Distribute data collection requirements to discipline leads | Data Coordinator | Requirements distributed |
| 3.3.2 | Collect mechanical equipment data | Mechanical Lead | Mechanical data |
| 3.3.3 | Collect electrical equipment data | Electrical Lead | Electrical data |
| 3.3.4 | Collect instrumentation data | I&C Lead | I&C data |
| 3.3.5 | Collect vendor data (serial numbers, specific parameters) | Data Coordinator | Vendor data |
| 3.3.6 | Compile all collected data | Data Coordinator | Compiled data set |

### 3.4 Data Population

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.4.1 | Open IVARA template | Data Coordinator | Template ready |
| 3.4.2 | Populate equipment identification fields | Data Coordinator | ID fields complete |
| 3.4.3 | Populate equipment specification fields (manufacturer, model, serial number) | Data Coordinator | Spec fields complete |
| 3.4.4 | Populate location and system assignment fields | Data Coordinator | Location fields complete |
| 3.4.5 | Populate maintenance-related fields (if required) | Data Coordinator | Maintenance fields complete |
| 3.4.6 | Add documentation links (O&M manuals, drawings) to each equipment item | Data Coordinator | Links added |
| 3.4.7 | Save package with version control | Data Coordinator | Versioned package |

### 3.5 Data Validation

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.5.1 | Check for missing mandatory fields | Data Coordinator | Completeness report |
| 3.5.2 | Check for duplicate equipment tags | Data Coordinator | Duplicate report |
| 3.5.3 | Validate tag format against TM convention | Data Coordinator | Format validation |
| 3.5.4 | Cross-check data against source documents | Data Coordinator | Accuracy verification |
| 3.5.5 | Validate data format against template requirements | Data Coordinator | Format compliance |
| 3.5.6 | Address all validation findings | Data Coordinator | Validated package |

### 3.6 Internal Review

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.6.1 | Circulate package for discipline review | Data Coordinator | Review comments |
| 3.6.2 | Address review comments | Data Coordinator | Revised package |
| 3.6.3 | Obtain internal approval | Engineering Lead | Internal approval |

### 3.7 TM Submission

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.7.1 | Prepare transmittal package | Document Controller | Transmittal |
| 3.7.2 | Submit package to TM | Document Controller | Submission confirmed |
| 3.7.3 | Register package in MDR (DEL-00.01) | Document Controller | MDR updated |
| 3.7.4 | Track TM review status | Data Coordinator | Review status |

### 3.8 TM Review and Import

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.8.1 | Receive TM review comments (if any) | Data Coordinator | TM comments |
| 3.8.2 | Address TM comments and revise package | Data Coordinator | Revised package |
| 3.8.3 | Resubmit revised package if required | Document Controller | Resubmission confirmed |
| 3.8.4 | Confirm TM acceptance and import | TM IVARA Administrator | Import confirmed |

### 3.9 Package Updates

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.9.1 | Identify need for package update (new data, corrections) | Data Coordinator | Update trigger |
| 3.9.2 | Update package with new/corrected data | Data Coordinator | Updated package |
| 3.9.3 | Follow Steps 3.5-3.8 for validation and submission | Per steps | Approved update |
| 3.9.4 | Archive previous package version | Document Controller | Archived version |

### 3.10 Final Package (Turnover)

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.10.1 | Incorporate all as-built data | Data Coordinator | As-built data |
| 3.10.2 | Incorporate final vendor data (serial numbers) | Data Coordinator | Final vendor data |
| 3.10.3 | Perform final validation | Data Coordinator | Final validation |
| 3.10.4 | Submit final package for turnover | Document Controller | Final package submitted |
| 3.10.5 | Obtain TM final acceptance | TM | Final acceptance |

---

## 4. Verification

### 4.1 Quality Control Checklist

| Check Item | Verification Method | Pass Criteria |
|------------|---------------------|---------------|
| All equipment included | Compare to master equipment list | 100% coverage |
| Mandatory fields populated | Null check | No blanks |
| Serial numbers included | Field check | Serial numbers populated where available |
| System assignments complete | Field check | System/sub-system assigned |
| Documentation links added | Field check | O&M links populated |
| No duplicate tags | Unique check | No duplicates |
| Tag format compliance | Format validation | Matches TM convention |
| Data accuracy | Cross-check to sources | Matches source documents |
| Template compliance | Format check | Matches TM template |
| Package registered in MDR | Check MDR | Entry exists |

### 4.2 Review Requirements

| Milestone | Reviewer | Approval |
|-----------|----------|----------|
| Draft Package | Discipline Leads | Data validated |
| Internal Review | Engineering Lead | Internal approval |
| TM Submission | TM IVARA Administrator | TM acceptance |

### 4.3 Issue Resolution

| Issue Type | Resolution Process |
|------------|---------------------|
| Missing data | Contact discipline lead; obtain data and update |
| Format error | Correct format; revalidate |
| TM import failure | Review error report; correct data; resubmit |

---

## 5. Records

### 5.1 Generated Records

| Record | Format | Retention |
|--------|--------|-----------|
| IVARA Data Input Package (all versions) | .xlsx / .csv | Project duration + **TBD** years |
| Validation Reports | .pdf | Project duration + **TBD** years |
| TM Review Comments | .pdf or electronic | Project duration + **TBD** years |
| Transmittal Records | .pdf or electronic | Project duration + **TBD** years |
| Import Confirmation | .pdf or electronic | Project duration + **TBD** years |

### 5.2 Storage Location

- Native files: Contractor document management system
- Submitted files: TM EDMS (**TBD**)
- Archive: Per TM document retention requirements

### 5.3 Naming Convention

- **ASSUMPTION:** `[Project Number]-IVARA-[Rev]-[Date].[ext]`
- Example: `2500-IVARA-Rev0-20260601.xlsx`
- Confirm with TM naming convention requirements

---

## 6. Notes and Assumptions

1. **ASSUMPTION:** TM will provide IVARA template and field definitions.
2. **ASSUMPTION:** Progressive package submissions aligned with project milestones.
3. **TBD:** TM IVARA template and specific data requirements.
4. **TBD:** Maintenance strategy field population responsibility.
5. **TBD:** Document retention period.

---

## 7. Revision History

| Revision | Date | Description | Author |
|----------|------|-------------|--------|
| Pass 1 | 2026-02-01 | Initial draft - Pass 1 generation | PSO Team |
| Pass 2 | 2026-02-01 | Cross-reference consistency check | PSO Team |

---

*Generated: Pass 1 - Initial Draft*
*Updated: Pass 2 - Cross-Reference Consistency Check (2026-02-01)*
*Source: PSO Decomposition REVISED v2, SOW Section 3.2.2.17*
