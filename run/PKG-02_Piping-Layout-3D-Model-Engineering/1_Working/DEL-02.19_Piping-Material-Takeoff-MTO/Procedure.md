# Procedure: Piping Material Takeoff (MTO)

**Deliverable ID:** DEL-02.19
**Package:** PKG-02 (Piping, Layout & 3D Model Engineering)
**Version:** 0.1 (Initial Draft)
**Status:** INITIALIZED
**Date:** 2026-02-01

---

## 1. Purpose

This procedure defines the step-by-step process for developing the Piping Material Takeoff (MTO) for the Puget Sound Optimization Project (PSO).

---

## 2. Scope

This procedure applies to the development of piping MTOs for all materials within the PSO scope at Sumas Tank Farm, including pipe, fittings, flanges, valves, specialty items, bolting, gaskets, and support materials.

---

## 3. Responsibilities

| Role | Responsibility |
|------|----------------|
| Piping Lead | Overall deliverable ownership, technical approval |
| Piping Designer | MTO development and quantity takeoff |
| 3D Coordinator | Model-based quantity extraction |
| Cost Estimator | Pricing input and verification |
| Procurement | Material coding and specifications |
| Checker | Independent quantity verification |
| Document Controller | Version control, issue, transmittal |

---

## 4. Prerequisites

Before initiating MTO development:

| Prerequisite | Source | Status |
|--------------|--------|--------|
| P&IDs (IFR minimum) | DEL-01.03 | Required |
| Line Designation Table | DEL-02.18 | Required |
| PMC Index | DEL-02.25 | Required |
| Valve List | DEL-02.02 | Required for valve quantities |
| Piping Isometrics | DEL-02.13 | Required for IFC MTO |
| Specialty Item Datasheets | DEL-02.20 | Required for specialty items |
| 3D Model | DEL-02.28 | Required for model-based takeoff |
| Support Drawings | DEL-02.16 | Required for support materials |

---

## 5. Procedure

### Step 1: Establish MTO Structure

**1.1** Obtain or develop MTO template:
- Confirm TM MTO format requirements
- Establish commodity categories
- Define column structure
- Set up summary sheets

**1.2** Define commodity coding:
- Align with TM commodity system
- Establish sub-categories
- Create coding legend

**1.3** Set up data validation:
- Material specification dropdowns
- Unit of measure validation
- Piping class validation

**1.4** Submit template for Piping Lead approval.

**Deliverable:** Approved MTO template

---

### Step 2: Extract Pipe Quantities

**2.1** Extract pipe quantities from 3D model:
- Run model quantity reports by size and class
- Export to MTO format
- Verify extraction completeness

**2.2** If no model available, estimate from routing:
- Measure from layout drawings
- Apply parametric factors
- Document estimation basis

**2.3** Organize pipe quantities:
- Group by nominal size
- Group by piping class
- Apply standard stock lengths
- Calculate total lengths

**Deliverable:** Pipe quantity section of MTO

---

### Step 3: Extract Fitting Quantities

**3.1** Extract fitting quantities from 3D model:
- Run fitting reports by type, size, and class
- Include all fitting types (elbows, tees, reducers, caps)
- Export to MTO format

**3.2** If isometrics available, verify against BOMs:
- Compare model quantities to isometric totals
- Investigate discrepancies
- Use isometric quantities for IFC

**3.3** Organize fitting quantities:
- Group by fitting type
- Group by size and class
- Include rating and end type

**Deliverable:** Fitting quantity section of MTO

---

### Step 4: Extract Flange Quantities

**4.1** Extract flange quantities from model/isometrics:
- Count all pipe flanges
- Identify flange types (WN, SO, blind)
- Include spectacle blinds and spacers

**4.2** Verify flange-to-equipment connections:
- Cross-check with equipment list
- Confirm mating flanges

**4.3** Organize flange quantities:
- Group by flange type
- Group by size, rating, and class
- Include facing details

**Deliverable:** Flange quantity section of MTO

---

### Step 5: Add Valve Quantities

**5.1** Obtain valve quantities from Valve List (DEL-02.02):
- Extract all valves within scope
- Verify count against P&IDs
- Confirm specifications

**5.2** Include valve accessories:
- Actuators (electric, pneumatic, hydraulic)
- Operators (gear, lever, handwheel)
- Limit switches, positioners

**5.3** Organize valve quantities:
- Group by valve type
- Group by size and class
- Reference valve datasheet numbers

**Deliverable:** Valve quantity section of MTO

---

### Step 6: Add Specialty Items

**6.1** Obtain specialty item quantities:
- Reference Specialty Datasheets (DEL-02.20)
- Extract from P&IDs
- Verify against model

**6.2** Include all specialty categories:
- Strainers and Y-strainers
- Filters
- Expansion joints
- Flame arrestors
- Check valves (specialty types)
- Relief valves

**6.3** Organize specialty quantities:
- Group by item type
- Reference datasheet numbers
- Include complete specifications

**Deliverable:** Specialty item quantity section of MTO

---

### Step 7: Calculate Bolting Quantities

**7.1** Calculate bolt quantities from flange count:
- Identify flange sizes and ratings
- Apply bolt count per flange (from PMC)
- Include valve and equipment bolting

**7.2** Determine bolt specifications:
- Material grade per PMC
- Length per flange thickness
- Nut and washer quantities

**7.3** Add spares:
- Apply spare percentage (typically 5-10%)
- Round up to package quantities

**7.4** Organize bolting quantities:
- Group by bolt size and grade
- Show lengths separately

**Deliverable:** Bolting quantity section of MTO

---

### Step 8: Calculate Gasket Quantities

**8.1** Calculate gasket quantities from flange count:
- One gasket per flanged joint
- Match gasket type to service

**8.2** Determine gasket specifications:
- Material per PMC
- Size per flange rating
- Special gaskets for specialty connections

**8.3** Add spares:
- Apply spare percentage
- Round up to package quantities

**8.4** Organize gasket quantities:
- Group by gasket type and size
- Reference PMC gasket specifications

**Deliverable:** Gasket quantity section of MTO

---

### Step 9: Add Support Materials

**9.1** Extract support quantities from:
- Support location plans (DEL-02.17)
- Standard support drawings (DEL-02.16)
- Stress analysis output (for springs)

**9.2** Include support material categories:
- Fabricated supports (steel)
- Pipe shoes and clamps
- Spring hangers
- U-bolts and hardware

**9.3** Organize support quantities:
- Group by support type
- Include structural steel weights
- Reference support drawing numbers

**Deliverable:** Support material quantity section of MTO

---

### Step 10: Apply Allowances

**10.1** Apply phase-appropriate allowances:

| Category | FEED | IFD | IFC |
|----------|------|-----|-----|
| Pipe | +15% | +10% | +5% |
| Fittings | +20% | +15% | +10% |
| Valves | 0% | 0% | 0% |
| Bolting | +10% | +5% | +5% |
| Gaskets | +10% | +5% | +5% |

**10.2** Document allowance basis.

**10.3** Create separate columns for base and total quantities.

**Deliverable:** MTO with allowances applied

---

### Step 11: Compile and Summarize

**11.1** Compile all commodity sections into single workbook.

**11.2** Create summary sheets:
- Total by commodity type
- Total by piping class
- Total by area (if applicable)
- Weight summary

**11.3** Verify all cross-references and totals.

**11.4** Complete cover sheet with document information.

**Deliverable:** Complete MTO workbook

---

### Step 12: Internal Review

**12.1** Perform self-check:
- All categories complete
- Calculations correct
- Specifications valid
- Formatting consistent

**12.2** Submit to Checker for verification:
- Sample quantity verification
- Cross-check key totals
- Specification validation

**12.3** Address review comments.

**Deliverable:** Reviewed MTO with comment resolution

---

### Step 13: Coordination Review

**13.1** Issue MTO for coordination:
- Cost Estimator: Verify for estimating use
- Procurement: Verify specifications and coding
- 3D Coordinator: Reconcile with model quantities

**13.2** Resolve all coordination comments.

**13.3** Update MTO as required.

**Deliverable:** Coordinated MTO

---

### Step 14: Issue for Review (IFR)

**14.1** Prepare MTO for IFR submission:
- Apply IFR revision status
- Generate PDF version
- Complete transmittal

**14.2** Submit to Document Control for issue to TM.

**14.3** Track TM comments and prepare responses.

**Deliverable:** IFR MTO package

---

### Step 15: Comment Resolution and Progressive Updates

**15.1** Address TM review comments.

**15.2** Update MTO through design phases:
- Revise as isometrics develop
- Update valve quantities as finalized
- Refine specialty item specifications

**15.3** Issue updated revisions (IFD, IFC).

**Deliverable:** Progressive MTO revisions

---

### Step 16: Issue for Construction (IFC)

**16.1** Finalize MTO:
- All quantities based on approved isometrics
- All specifications confirmed
- All TBD items resolved

**16.2** Perform final verification.

**16.3** Issue as IFC through Document Control.

**16.4** Archive native files per SOW requirements.

**Deliverable:** IFC MTO (Excel + PDF)

---

## 6. Records

| Record | Retention | Location |
|--------|-----------|----------|
| MTO (all revisions) | Project life | TM EDMS |
| Quantity calculation backup | Project life | TM EDMS |
| Review comment logs | Project life | TM EDMS |
| Reconciliation records | Project life | TM EDMS |

---

## 7. Quality Control Checkpoints

| Checkpoint | Timing | Verification |
|------------|--------|--------------|
| Template approval | Step 1.4 | Piping Lead sign-off |
| Pipe quantities | Step 2.3 | Model verification |
| Valve reconciliation | Step 5.1 | Match Valve List |
| Specialty items | Step 6.3 | Match datasheets |
| Internal review | Step 12.3 | Checker sign-off |
| Coordination | Step 13.3 | Multi-discipline sign-off |
| IFC issue | Step 16.3 | Final approval |

---

## 8. References

| Document | Description |
|----------|-------------|
| SOW Section 3.1.3.1 | FEED MTO requirements |
| SOW Section 3.2.4.9 | Isometric/MTO requirements |
| SOW Section 3.2.4.12 | MTO development |
| DEL-00.03 | Deliverable Review & Verification Plan |

---

## 9. Revision History

| Rev | Date | Description | Author |
|-----|------|-------------|--------|
| 0.1 | 2026-02-01 | Initial draft | 4_DOCUMENTS Agent |

---

*Procedure generated as initial draft. To be refined based on project-specific requirements and TM direction.*
