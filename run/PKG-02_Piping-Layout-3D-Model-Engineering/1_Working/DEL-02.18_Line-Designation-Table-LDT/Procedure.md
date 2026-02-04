# Procedure: Line Designation Table (LDT)

**Deliverable ID:** DEL-02.18
**Package:** PKG-02 (Piping, Layout & 3D Model Engineering)
**Version:** 0.1 (Initial Draft)
**Status:** INITIALIZED
**Date:** 2026-02-01

---

## 1. Purpose

This procedure defines the step-by-step process for developing the Line Designation Table (LDT) for the Puget Sound Optimization Project (PSO).

---

## 2. Scope

This procedure applies to the development and maintenance of the LDT for all process piping lines within the PSO scope at Sumas Tank Farm.

---

## 3. Responsibilities

| Role | Responsibility |
|------|----------------|
| Piping Lead | Overall deliverable ownership, technical approval |
| Piping Designer | LDT development and data entry |
| Process Engineer | Design conditions input |
| Materials Engineer | Piping class validation |
| Checker | Independent data verification |
| Document Controller | Version control, issue, transmittal |

---

## 4. Prerequisites

Before initiating LDT development:

| Prerequisite | Source | Status |
|--------------|--------|--------|
| Design Basis Memorandum | DEL-01.01 | Required |
| P&IDs (preliminary minimum) | DEL-01.03 | Required |
| Line List (preliminary) | DEL-02.01 | Required |
| PMC Index | DEL-02.25 | Required |
| TM LDT Template (if available) | TM | Preferred |
| NDE/Testing Specifications | Project Specs | Required |

---

## 5. Procedure

### Step 1: Obtain and Review Inputs

**1.1** Obtain the following input documents:
- Design Basis Memorandum (DEL-01.01)
- Latest P&IDs (DEL-01.03)
- Preliminary Line List (DEL-02.01)
- PMC Index (DEL-02.25)
- Insulation and heat tracing schedules
- Project NDE and testing specifications

**1.2** Review TM LDT template (if available) or establish project template.

**1.3** Confirm column requirements with Piping Lead and TM.

**Deliverable:** Input package assembled, template confirmed

---

### Step 2: Establish LDT Template

**2.1** Create or obtain LDT Excel template with required columns:

| Column Group | Columns |
|--------------|---------|
| Identification | Line Number, P&ID Reference |
| Size/Material | Nominal Size, Piping Class |
| Routing | From, To |
| Design Conditions | Design Pressure, Design Temperature |
| Operating Conditions | Operating Pressure, Operating Temperature |
| Service | Fluid/Service Description |
| Insulation | Insulation Code, Thickness, Heat Tracing |
| Examination | NDE Requirements |
| Testing | Hydro Test Pressure, Leak Test |
| Other | PWHT, Coating, Remarks |
| Status | Line Status (New/Existing/Modified) |

**2.2** Set up data validation:
- Dropdown lists for piping classes (from PMC Index)
- Dropdown lists for NDE codes
- Dropdown lists for line status
- Numerical validation for pressures and temperatures

**2.3** Format template:
- Freeze header row
- Enable filters
- Apply consistent formatting
- Create legend sheet

**2.4** Submit template for Piping Lead approval.

**Deliverable:** Approved LDT template

---

### Step 3: Extract Line Data from P&IDs

**3.1** Systematically review each P&ID within scope:
- Identify all new lines
- Identify modified existing lines
- Identify demolished lines

**3.2** For each line, record:
- Line number (exactly as shown on P&ID)
- P&ID sheet number
- From and To locations
- Nominal pipe size
- Service/fluid description

**3.3** Verify no lines are missed:
- Count lines per P&ID
- Cross-check against Line List (DEL-02.01)
- Flag any discrepancies for resolution

**Deliverable:** LDT populated with line identification data

---

### Step 4: Populate Design and Operating Conditions

**4.1** Obtain design conditions from DBM (DEL-01.01):
- Design pressure for each service
- Design temperature (max and min)
- Operating pressure
- Operating temperature

**4.2** Assign conditions to each line based on service.

**4.3** Verify conditions are appropriate:
- Design pressure >= operating pressure
- Design temperature covers operating range
- Conditions consistent with piping class rating

**4.4** Document source for each condition in Remarks if not standard.

**Deliverable:** LDT with design/operating conditions

---

### Step 5: Assign Piping Classes

**5.1** Reference PMC Index (DEL-02.25) for valid piping classes.

**5.2** For each line, assign piping class based on:
- Fluid service
- Design pressure
- Design temperature
- Special requirements (corrosion, etc.)

**5.3** Verify selected class is appropriate:
- Pressure rating adequate
- Temperature rating adequate
- Material compatible with fluid

**5.4** Flag any lines requiring new or non-standard classes.

**Deliverable:** LDT with piping class assignments

---

### Step 6: Determine NDE and Testing Requirements

**6.1** Review project specifications and code requirements:
- CSA Z662 examination requirements
- Project-specific NDE tables
- PWHT requirements per material/thickness

**6.2** Assign NDE requirements to each line:
- Radiography (RT) percentage
- Ultrasonic (UT) if alternative to RT
- Surface examination (MT/PT) requirements
- Visual (VT) requirements

**6.3** Calculate hydrostatic test pressures:
- Per CSA Z662 or ASME B31.4 formula
- Document calculation basis
- Round to standard test gauge pressure

**6.4** Determine PWHT requirements:
- Per code based on material and thickness
- Per stress analysis requirements

**Deliverable:** LDT with NDE and testing data

---

### Step 7: Add Insulation and Coating Data

**7.1** Obtain insulation schedule for:
- Insulation type/code
- Insulation thickness
- Heat tracing requirements

**7.2** Obtain coating specification for:
- External coating system
- Special coatings for buried/underwater

**7.3** Populate LDT with insulation and coating codes.

**Deliverable:** LDT with insulation and coating data

---

### Step 8: Internal Review and Validation

**8.1** Perform self-check:
- All mandatory fields populated
- No blank cells in required columns
- No duplicate line numbers
- Unit consistency

**8.2** Perform data validation checks:
- Piping classes valid per PMC Index
- Design pressures within class ratings
- NDE codes valid
- Test pressures calculated correctly

**8.3** Submit to Checker for independent review:
- Verify against source documents
- Check calculations
- Review completeness

**8.4** Address review comments and document resolution.

**Deliverable:** Reviewed LDT with comment resolution

---

### Step 9: Cross-Discipline Coordination

**9.1** Issue LDT for coordination review:
- Process Engineering: Verify conditions
- Stress Engineering: Verify PWHT requirements
- Materials: Verify piping class selections
- QA/QC: Verify NDE requirements

**9.2** Conduct coordination meeting if required.

**9.3** Resolve all comments and update LDT.

**Deliverable:** Coordinated LDT

---

### Step 10: Issue for Review (IFR)

**10.1** Prepare LDT for IFR submission:
- Apply IFR revision status
- Complete document header
- Generate PDF version

**10.2** Submit to Document Control for:
- Document number assignment
- Transmittal preparation
- Issue to TM for review

**10.3** Track TM comments and prepare responses.

**Deliverable:** IFR LDT package

---

### Step 11: Comment Resolution and Updates

**11.1** Receive and log TM review comments.

**11.2** Prepare comment responses:
- Accept: incorporate change
- Reject: provide justification
- Clarify: provide additional information

**11.3** Update LDT to incorporate accepted comments.

**11.4** Issue updated revision (IFD at end of FEED).

**Deliverable:** Updated LDT with comment responses

---

### Step 12: Detailed Design Maintenance

**12.1** Maintain LDT throughout Detailed Design:
- Add new lines as identified
- Update conditions if changed
- Refine NDE/testing requirements
- Remove deleted lines

**12.2** Track all changes in revision log.

**12.3** Coordinate with isometric development (DEL-02.13) and MTO (DEL-02.19).

**Deliverable:** Progressive LDT revisions

---

### Step 13: Issue for Construction (IFC)

**13.1** Finalize LDT:
- All TBD items resolved
- All lines captured
- All data validated
- All review comments closed

**13.2** Perform final review and obtain approvals.

**13.3** Issue as IFC through Document Control.

**13.4** Archive native Excel file per SOW requirements.

**Deliverable:** IFC LDT (Excel + PDF)

---

## 6. Records

| Record | Retention | Location |
|--------|-----------|----------|
| LDT (all revisions) | Project life | TM EDMS |
| Review Comment Logs | Project life | TM EDMS |
| Calculation Backup (test pressures) | Project life | TM EDMS |
| Coordination Verification | Project life | TM EDMS |

---

## 7. Quality Control Checkpoints

| Checkpoint | Timing | Verification |
|------------|--------|--------------|
| Template approval | Step 2.4 | Piping Lead sign-off |
| Line extraction complete | Step 3.3 | Cross-check vs. P&IDs |
| Conditions populated | Step 4.4 | Verify vs. DBM |
| Classes assigned | Step 5.4 | PMC Index validation |
| Internal review complete | Step 8.4 | Checker sign-off |
| IFR issue | Step 10.2 | Document Control transmittal |
| IFC issue | Step 13.3 | Final approval sign-off |

---

## 8. References

| Document | Description |
|----------|-------------|
| SOW Section 3.2.4.11 | LDT requirements |
| SOW Section 3.2.4.23-24 | Native file requirements |
| DEL-00.03 | Deliverable Review & Verification Plan |
| CSA Z662 | Oil and Gas Pipeline Systems |

---

## 9. Revision History

| Rev | Date | Description | Author |
|-----|------|-------------|--------|
| 0.1 | 2026-02-01 | Initial draft | 4_DOCUMENTS Agent |

---

*Procedure generated as initial draft. To be refined based on project-specific requirements and TM direction.*
