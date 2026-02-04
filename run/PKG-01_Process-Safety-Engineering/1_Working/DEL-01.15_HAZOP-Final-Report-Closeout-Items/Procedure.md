# Procedure: DEL-01.15 HAZOP Final Report & Closeout Items

**Document ID:** DEL-01.15-PR
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Purpose

This procedure defines the step-by-step process for planning, executing, documenting, and closing out the HAZOP study for the Puget Sound Optimization (PSO) project.

---

## 2. Prerequisites

### 2.1 Required Inputs

| Input | Source | Status Required |
|-------|--------|-----------------|
| P&IDs | DEL-01.03 | IFR or better |
| Process Design Basis | DEL-01.01 | Approved |
| Operating Envelopes | DEL-01.13 | Draft minimum |
| Control Narratives | DEL-07.09 | Draft minimum |
| Equipment List | DEL-01.07 | IFR minimum |
| Cause & Effect Diagrams | DEL-07.10 | Draft minimum |
| TM-Approved Risk Matrix | TM Safety | Approved |

### 2.2 Required Resources

- Qualified HAZOP facilitator (per IEC 61882 / TM requirements)
- Meeting room with display capability (or virtual meeting platform)
- Recording secretary / scribe
- HAZOP software or worksheet templates
- Study team members (see below)

### 2.3 Study Team Composition

| Role | Organization | Expertise |
|------|--------------|-----------|
| Facilitator | **TBD** - Independent | HAZOP methodology (qualified per IEC 61882) |
| Process Engineer | Engineering Contractor | PSO process design |
| Operations Representative | TM Operations | Operating experience |
| Safety Representative | TM Safety / HSE | Safety requirements |
| I&C Engineer | Engineering Contractor | Control systems |
| Mechanical Engineer | Engineering Contractor | Equipment knowledge |
| Electrical Engineer | Engineering Contractor | Electrical systems |
| Scribe | Engineering Contractor | Documentation |

### 2.4 Required Approvals

- Study scope approved by TM before study
- Final report approved by TM after study

---

## 3. Steps

### Step 1: HAZOP Planning
**Responsible:** Lead Process Engineer / Facilitator

1.1. Define study scope and objectives

1.2. Identify study team members and confirm availability

1.3. Schedule study sessions (allow adequate time - **ASSUMPTION:** 3-5 days for PSO scope)

1.4. Prepare node definitions:
   - Review P&IDs and identify logical node boundaries
   - Prepare node drawings/sketches
   - Define design intent for each node

1.5. Select guidewords and parameters for each node:
   - NO / NOT (Flow, Level, Pressure)
   - MORE (Flow, Pressure, Temperature, Level)
   - LESS (Flow, Pressure, Temperature, Level)
   - REVERSE (Flow, Sequence)
   - AS WELL AS (Composition, Contamination)
   - PART OF (Composition)
   - OTHER THAN (Operation, Maintenance)

1.6. Distribute pre-reading package to team:
   - P&IDs (IFR or better)
   - Node definitions
   - Process descriptions
   - Operating envelopes

1.7. Obtain TM approval of study scope

**Output:** Approved study scope, scheduled sessions, prepared materials

---

### Step 2: Conduct HAZOP Sessions
**Responsible:** Facilitator / Study Team

2.1. Open each session:
   - Review objectives and scope
   - Confirm team composition and record attendance
   - Review ground rules

2.2. For each node:
   - Present node description and design intent
   - Systematically apply guidewords to each parameter
   - Identify causes, consequences, and existing safeguards
   - Rank risk using TM-approved risk matrix
   - Develop recommendations where required
   - Assign actions to responsible parties

2.3. Scribe documents:
   - All deviations analyzed
   - Causes and consequences identified
   - Safeguards noted
   - Risk rankings assigned (pre- and post-mitigation)
   - Recommendations and actions

2.4. Review session summary at end of each day

2.5. Complete all nodes in study scope

**Output:** Completed HAZOP worksheets, action items identified

---

### Step 3: Prepare Draft HAZOP Report
**Responsible:** Facilitator / Process Engineer

3.1. Compile all worksheets into report format

3.2. Write executive summary:
   - Study scope and methodology
   - Key findings and statistics
   - High-priority recommendations

3.3. Prepare introduction and methodology sections

3.4. Document system descriptions and node definitions

3.5. Include complete HAZOP worksheets

3.6. Compile action item register:
   - Assign unique action IDs
   - Confirm responsible parties
   - Set target completion dates
   - Include all required fields per Datasheet Section 4.2

3.7. Include appendices:
   - Attendance records
   - P&IDs (reference list with revisions)
   - TM-approved risk matrix used

3.8. Facilitator review and sign-off on draft

**Output:** Draft HAZOP report

---

### Step 4: Review and Finalize Report
**Responsible:** Lead Process Engineer / TM Engineering

4.1. Distribute draft report to study team for review

4.2. Collect and address review comments

4.3. Update report to final status

4.4. Submit to TM for approval

4.5. Incorporate TM comments (if any)

4.6. Obtain TM approval/acceptance of final report

4.7. Issue final HAZOP report

**Output:** Approved final HAZOP report

---

### Step 5: Implement Recommendations
**Responsible:** Assigned Responsible Parties

5.1. For each action item:
   - Review recommendation in detail
   - Develop implementation approach
   - Implement in design documents (P&IDs, specifications, etc.)
   - Document response to action

5.2. Update action register with:
   - Response description
   - Implementation status
   - Target completion date (revised if needed)

5.3. Regular status reviews:
   - Weekly engineering team review
   - Monthly report to project management

**Output:** Recommendations implemented in design

---

### Step 6: Close Out Actions
**Responsible:** Lead Process Engineer / TM Engineering

6.1. For each action:
   - Verify implementation is complete
   - Collect closure evidence (marked-up P&IDs, calculations, etc.)
   - Confirm response addresses recommendation intent
   - Update residual risk ranking (post-mitigation)

6.2. Document closure:
   - Record closure evidence reference
   - Record verified by name
   - Record closure date
   - Update status to "Closed"

6.3. Obtain TM concurrence on action closure (for safety-critical items)

6.4. Update closeout log

**Output:** Closed action items with documented evidence

---

### Step 7: Final Closeout
**Responsible:** Lead Process Engineer / Project Manager

7.1. Verify all actions closed or transferred to operations/commissioning

7.2. Prepare final closeout summary:
   - Total actions generated
   - Actions closed before IFC
   - Actions deferred to commissioning (with justification)

7.3. Obtain TM sign-off on HAZOP closeout

7.4. Archive HAZOP documentation

**Output:** HAZOP study fully closed out

---

## 4. Verification

### 4.1 Verification Checklist

| Item | Check | Verified By |
|------|-------|-------------|
| All nodes studied | Compare node list to P&IDs | Facilitator |
| All guidewords applied | Review worksheets | Facilitator |
| Actions assigned | Check all have responsible party | Lead Process Engineer |
| Actions tracked | Review register status | Project Engineer |
| Closure evidence | Audit closed actions | TM Engineering |

### 4.2 Quality Gates

| Gate | Criteria | Approver |
|------|----------|----------|
| Study Scope | Scope approved before study | TM Engineering |
| Report Approval | Final report accepted | TM Engineering |
| IFC Closeout | Critical actions closed before IFC | TM Engineering |
| Final Closeout | All actions closed or transferred | TM Operations / Safety |

---

## 5. Records

### 5.1 Required Records

| Record | Retention | Location |
|--------|-----------|----------|
| HAZOP Final Report | Facility life | TM Document Management |
| HAZOP Worksheets | Facility life | TM Document Management |
| Action Register | Facility life | Project Document Management |
| Closeout Log | Facility life | Project Document Management |
| Attendance Records | Project life + 7 years | Project Files |
| P&IDs (study basis) | Facility life | TM Document Management |

### 5.2 Reporting

| Report | Frequency | Audience |
|--------|-----------|----------|
| Action Status Summary | Weekly during active closeout | Project Team |
| HAZOP Status Report | Monthly | Project Management, TM |
| Final Closeout Report | Project completion | TM Operations, Safety |

### 5.3 Handover

- Outstanding actions transferred to TM Operations with pre-startup checklist
- HAZOP report included in facility documentation package
- Closeout log included in commissioning documentation

---

*End of Procedure*
