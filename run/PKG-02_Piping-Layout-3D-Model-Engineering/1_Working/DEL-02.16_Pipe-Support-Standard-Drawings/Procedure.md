# Procedure: Pipe Support Standard Drawings

**Deliverable ID:** DEL-02.16
**Package:** PKG-02 (Piping, Layout & 3D Model Engineering)
**Version:** 0.1 (Initial Draft)
**Status:** INITIALIZED
**Date:** 2026-02-01

---

## 1. Purpose

This procedure defines the step-by-step process for developing Pipe Support Standard Drawings for the Puget Sound Optimization Project (PSO).

---

## 2. Scope

This procedure applies to all pipe support standard drawings developed for the PSO booster pump station, manifold, and associated piping at Sumas Tank Farm.

---

## 3. Responsibilities

| Role | Responsibility |
|------|----------------|
| Piping Lead | Overall deliverable ownership, technical approval |
| Piping Designer | Drawing development and revisions |
| Stress Engineer | Load inputs, support location requirements |
| Structural Engineer | Attachment interface coordination |
| Checker | Independent technical review |
| Document Controller | Drawing numbering, issue, transmittal |

---

## 4. Prerequisites

Before initiating standard drawing development:

| Prerequisite | Source | Status |
|--------------|--------|--------|
| Line List (preliminary) | DEL-02.01 | Required |
| Line Designation Table (preliminary) | DEL-02.18 | Required |
| PMC Index | DEL-02.25 | Required |
| Support & Pipe Stress Execution Plan | DEL-02.15 | Recommended |
| Preliminary stress analysis (FEED) | DEL-02.14 | Recommended |
| TM CAD standards | TM Document Control | Required |

---

## 5. Procedure

### Step 1: Support Type Identification

**1.1** Review the following to identify required support types:
- Line List (DEL-02.01) for pipe sizes and services
- Preliminary P&IDs (DEL-01.03) for system routing
- Preliminary stress analysis outputs (if available)
- Similar project references / TM existing standards

**1.2** Prepare Support Type Register documenting:
- Support type code
- Description
- Applicable pipe size range
- Typical application
- Drawing number (to be assigned)

**1.3** Review with Piping Lead for approval of support type list.

**Deliverable:** Support Type Register (draft)

---

### Step 2: Obtain Design Inputs

**2.1** Coordinate with Stress Engineer to obtain:
- Preliminary support load tables (dead weight, thermal, occasional)
- Support stiffness requirements (if applicable)
- Special support requirements (spring hangers, constant supports)

**2.2** Coordinate with Structural Engineer to obtain:
- Available attachment points (steel, concrete)
- Allowable loads on structures
- Anchor bolt specifications

**2.3** Obtain project-specific requirements:
- TM standard support details (if available)
- Material specifications per PMC/structural specs
- Coating/galvanizing requirements

**Deliverable:** Design Input Package (documented)

---

### Step 3: Prepare Standard Drawings

**3.1** Set up drawing templates per TM CAD standards:
- Title block format
- Layer standards
- Symbology standards

**3.2** For each support type, develop drawing content:

| Element | Action |
|---------|--------|
| Geometry | Develop fully dimensioned views |
| Materials | Specify per approved material list |
| Welds | Detail weld sizes, types, symbols |
| BOM | Prepare bill of materials table |
| Load table | Include capacity in each direction |
| Notes | Add fabrication, installation, QC notes |

**3.3** Ensure consistency across all standard drawings:
- Common format and presentation
- Consistent symbology
- Clear cross-references

**Deliverable:** Draft standard drawings (IFR quality)

---

### Step 4: Internal Review

**4.1** Perform self-check against Specification (DEL-02.16 Specification.md):
- All content requirements addressed
- Dimensions complete
- Materials specified
- Load capacities stated

**4.2** Submit to Checker for independent review:
- Technical accuracy
- Code compliance
- Constructability
- Completeness

**4.3** Address review comments and document resolution.

**Deliverable:** Reviewed drawings with comment resolution log

---

### Step 5: Coordination Verification

**5.1** Verify coordination with related deliverables:

| Deliverable | Verification |
|-------------|--------------|
| DEL-02.14 (Stress Analysis) | Loads consistent with stress outputs |
| DEL-02.17 (Location Plans) | Support callouts reference correct drawings |
| DEL-02.13 (Isometrics) | Support notes align with standards |
| DEL-02.28 (3D Model) | Support geometry matches model |
| PKG-04 (Structural) | Attachment details coordinated |

**5.2** Document any discrepancies and resolve before issue.

**Deliverable:** Coordination verification record

---

### Step 6: Issue for Review (IFR)

**6.1** Prepare drawings for IFR submission:
- Apply IFR revision status
- Complete title block information
- Generate PDF outputs

**6.2** Submit to Document Control for:
- Drawing number assignment (per TM system)
- Transmittal preparation
- Issue to TM for review

**6.3** Track TM comments and prepare responses.

**Deliverable:** IFR drawing package with transmittal

---

### Step 7: Comment Resolution and IFD Issue

**7.1** Receive and log TM review comments.

**7.2** Prepare comment responses:
- Accept: incorporate change
- Reject: provide justification
- Clarify: provide additional information

**7.3** Update drawings to incorporate accepted comments.

**7.4** Issue as IFD (Issued for Design) at end of FEED.

**Deliverable:** IFD drawing package

---

### Step 8: Detailed Design Updates

**8.1** During Detailed Design, update drawings for:
- Final stress analysis loads
- Vendor equipment interface requirements
- HAZOP/design review comments
- Constructability review findings

**8.2** Incorporate any new support types identified during detailed design.

**8.3** Maintain revision control per TM requirements.

**Deliverable:** Updated drawings (progressive revisions)

---

### Step 9: Issue for Construction (IFC)

**9.1** Finalize all standard drawings:
- All TBD items resolved
- Final loads incorporated
- All review comments closed

**9.2** Perform final check and approval:
- Piping Lead technical approval
- Checker verification

**9.3** Issue as IFC through Document Control.

**9.4** Archive native files per SOW Section 3.2.4.24 requirements.

**Deliverable:** IFC drawing package (native + PDF)

---

## 6. Records

| Record | Retention | Location |
|--------|-----------|----------|
| Support Type Register | Project life | TM EDMS |
| Design Input Package | Project life | TM EDMS |
| Comment Resolution Log | Project life | TM EDMS |
| Coordination Verification | Project life | TM EDMS |
| Native CAD files | As-built retention | TM EDMS |

---

## 7. Quality Control Checkpoints

| Checkpoint | Timing | Verification |
|------------|--------|--------------|
| Support type list approval | Step 1.3 | Piping Lead sign-off |
| Design inputs documented | Step 2.3 | Input package complete |
| Internal review complete | Step 4.3 | Checker sign-off |
| Coordination verified | Step 5.2 | Verification record |
| IFR issue | Step 6.2 | Document Control transmittal |
| IFC issue | Step 9.3 | Final approval sign-off |

---

## 8. References

| Document | Description |
|----------|-------------|
| SOW Section 3.2.4.3 | Standard pipe support drawings |
| SOW Section 3.2.4.23-24 | Native file requirements |
| DEL-00.03 | Deliverable Review & Verification Plan |
| DEL-02.15 | Support & Pipe Stress Execution Plan |

---

## 9. Revision History

| Rev | Date | Description | Author |
|-----|------|-------------|--------|
| 0.1 | 2026-02-01 | Initial draft | 4_DOCUMENTS Agent |

---

*Procedure generated as initial draft. To be refined based on project-specific requirements and TM direction.*
