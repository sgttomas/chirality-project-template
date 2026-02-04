# Procedure: Pipe Support Location Plans

**Deliverable ID:** DEL-02.17
**Package:** PKG-02 (Piping, Layout & 3D Model Engineering)
**Version:** 0.1 (Initial Draft)
**Status:** INITIALIZED
**Date:** 2026-02-01

---

## 1. Purpose

This procedure defines the step-by-step process for developing Pipe Support Location Plans for the Puget Sound Optimization Project (PSO).

---

## 2. Scope

This procedure applies to all pipe support location plans developed for the PSO booster pump station, manifold, and associated piping at Sumas Tank Farm.

---

## 3. Responsibilities

| Role | Responsibility |
|------|----------------|
| Piping Lead | Overall deliverable ownership, technical approval |
| Piping Designer | Plan development and revisions |
| Stress Engineer | Support location inputs |
| Model Coordinator | 3D model data extraction |
| Structural Engineer | Attachment point coordination |
| Checker | Independent technical review |
| Document Controller | Drawing numbering, issue, transmittal |

---

## 4. Prerequisites

Before initiating location plan development:

| Prerequisite | Source | Status |
|--------------|--------|--------|
| Piping GA drawings (preliminary) | DEL-02.12 | Required |
| Pipe stress analysis (preliminary) | DEL-02.14 | Required |
| 3D model (preliminary) | DEL-02.28 | Required |
| Support standard drawings | DEL-02.16 | Required |
| Structural steel plans (preliminary) | PKG-04 | Required |
| TM CAD standards | TM Document Control | Required |

---

## 5. Procedure

### Step 1: Establish Base Plans

**1.1** Obtain base plan files from:
- Piping GA drawings (DEL-02.12)
- Structural steel plans (PKG-04)
- Civil/site plans (PKG-04)

**1.2** Verify coordinate system and datum references.

**1.3** Set up drawing templates per TM CAD standards:
- Title block format
- Layer standards
- Symbology standards

**1.4** Establish sheet organization and match lines.

**Deliverable:** Base plan drawing files (preliminary)

---

### Step 2: Extract Support Locations

**2.1** Obtain support location data from:
- 3D model support placement (DEL-02.28)
- Stress analysis support list (DEL-02.14)

**2.2** Verify support list completeness:
- All stress model supports included
- Support types identified
- Coordinates available

**2.3** Reconcile any differences between model and stress analysis.

**Deliverable:** Support location data (verified)

---

### Step 3: Develop Support Schedule

**3.1** Create support schedule with columns:

| Column | Content |
|--------|---------|
| Support Mark | Unique identifier |
| Line Number | Per LDT |
| Support Type | Description |
| Standard Drawing | Reference number |
| Northing | Y coordinate |
| Easting | X coordinate |
| Elevation | Z coordinate / Top of Steel |
| Sheet Reference | Location plan sheet |
| Notes | Special requirements |

**3.2** Assign support mark numbers per naming convention.

**3.3** Review with Piping Lead for approval.

**Deliverable:** Support Schedule (draft)

---

### Step 4: Place Supports on Plans

**4.1** For each support in the schedule:
- Place support symbol at correct location
- Add support mark callout
- Add standard drawing reference
- Add elevation callout
- Add line number reference

**4.2** Verify symbol placement against 3D model.

**4.3** Add callout leaders clearly pointing to support locations.

**4.4** Avoid overcrowding; use enlarged details where needed.

**Deliverable:** Draft location plans

---

### Step 5: Add Drawing Elements

**5.1** Add required drawing elements:
- Legend with symbol definitions
- North arrow
- Scale bar
- Match line references
- Sheet index (if multiple sheets)
- General notes

**5.2** Verify all layers are correctly organized.

**5.3** Check text legibility at intended plot scale.

**Deliverable:** Complete draft drawings

---

### Step 6: Internal Review

**6.1** Perform self-check:
- All supports from schedule shown on plans
- Coordinates match schedule and model
- Callouts complete and correct
- Standard drawing references valid
- Legend complete

**6.2** Submit to Checker for independent review:
- Technical accuracy
- Completeness
- Coordination with stress analysis
- Coordination with structural drawings
- Constructability

**6.3** Address review comments and document resolution.

**Deliverable:** Reviewed drawings with comment resolution log

---

### Step 7: Coordination Verification

**7.1** Verify coordination with related deliverables:

| Deliverable | Verification |
|-------------|--------------|
| DEL-02.14 (Stress Analysis) | All supports shown, locations match |
| DEL-02.16 (Standard Drawings) | References valid |
| DEL-02.13 (Isometrics) | Support marks consistent |
| DEL-02.28 (3D Model) | Coordinates match |
| PKG-04 (Structural) | Attachment points exist |

**7.2** Document any discrepancies and resolve before issue.

**Deliverable:** Coordination verification record

---

### Step 8: Issue for Review (IFR)

**8.1** Prepare drawings for IFR submission:
- Apply IFR revision status
- Complete title block information
- Generate PDF outputs

**8.2** Finalize support schedule for submission.

**8.3** Submit to Document Control for:
- Drawing number assignment (per TM system)
- Transmittal preparation
- Issue to TM for review

**8.4** Track TM comments and prepare responses.

**Deliverable:** IFR drawing package with transmittal

---

### Step 9: Comment Resolution and IFD Issue

**9.1** Receive and log TM review comments.

**9.2** Prepare comment responses:
- Accept: incorporate change
- Reject: provide justification
- Clarify: provide additional information

**9.3** Update drawings and schedule to incorporate accepted comments.

**9.4** Issue as IFD (Issued for Design) at end of FEED.

**Deliverable:** IFD drawing package

---

### Step 10: Detailed Design Updates

**10.1** During Detailed Design, update plans for:
- Final stress analysis support locations
- Structural steel as-built information
- HAZOP/design review comments
- Vendor equipment interface requirements
- Field verification data

**10.2** Maintain support schedule current with any changes.

**10.3** Update 3D model if plan changes require.

**10.4** Maintain revision control per TM requirements.

**Deliverable:** Updated drawings (progressive revisions)

---

### Step 11: Issue for Construction (IFC)

**11.1** Finalize all location plans:
- All TBD items resolved
- Final locations confirmed
- All review comments closed
- Coordination complete

**11.2** Finalize support schedule.

**11.3** Perform final check and approval:
- Piping Lead technical approval
- Checker verification

**11.4** Issue as IFC through Document Control.

**11.5** Archive native files per SOW Section 3.2.4.24 requirements.

**Deliverable:** IFC drawing package (native + PDF) and final support schedule

---

## 6. Records

| Record | Retention | Location |
|--------|-----------|----------|
| Support Schedule | Project life | TM EDMS |
| Coordination Verification | Project life | TM EDMS |
| Comment Resolution Log | Project life | TM EDMS |
| Native CAD files | As-built retention | TM EDMS |

---

## 7. Quality Control Checkpoints

| Checkpoint | Timing | Verification |
|------------|--------|--------------|
| Base plan setup | Step 1.4 | Piping Lead review |
| Support schedule approval | Step 3.3 | Piping Lead sign-off |
| Internal review complete | Step 6.3 | Checker sign-off |
| Coordination verified | Step 7.2 | Verification record |
| IFR issue | Step 8.3 | Document Control transmittal |
| IFC issue | Step 11.4 | Final approval sign-off |

---

## 8. References

| Document | Description |
|----------|-------------|
| SOW Section 3.2.4.3 | Pipe support location plans |
| SOW Section 3.2.4.23-24 | Native file requirements |
| DEL-00.03 | Deliverable Review & Verification Plan |
| DEL-02.14 | Pipe Stress Analysis Report(s) |
| DEL-02.16 | Pipe Support Standard Drawings |

---

## 9. Revision History

| Rev | Date | Description | Author |
|-----|------|-------------|--------|
| 0.1 | 2026-02-01 | Initial draft | 4_DOCUMENTS Agent |

---

*Procedure generated as initial draft. To be refined based on project-specific requirements and TM direction.*
