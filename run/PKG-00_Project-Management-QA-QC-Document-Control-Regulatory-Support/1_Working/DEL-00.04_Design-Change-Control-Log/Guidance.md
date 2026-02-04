# Guidance: DEL-00.04 Design Change Control Log (Pass 2 — Cross-Reference & Enriched)

**Document ID:** DEL-00.04-GD
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** Draft - Pending Review

---

## 1. Purpose

### 1.1 Document Intent

This guidance document provides practical direction for developing and maintaining the Design Change Control Log for the Puget Sound Optimization Project (PSO). It supplements the formal Specification by offering context, best practices, and recommendations for effective implementation.

### 1.2 Audience

- Project management team
- Engineering leads and discipline managers
- QA/QC personnel
- Document control personnel

---

## 2. Principles

### 2.1 Core Principles

| Principle | Description | Pass 2 Cross-Reference |
|-----------|-------------|------------------------|
| **Proactive Logging** | Log changes before implementation, not after | Specification: CCL-P-001, CCL-P-003; Procedure: Step 3.2.8, Step 3.4.1; Datasheet: Section 3.3 (Constraint) |
| **Complete Capture** | Every design change must be recorded, regardless of size | Specification: CCL-F-001; Procedure: Section 4.1 (All changes logged); Datasheet: Section 2.1 (Scope Coverage) |
| **Traceability** | Link changes to affected documents and approvals | Specification: CCL-F-003, CCL-C-006; Procedure: Steps 3.2.6, 3.3.7, 3.4.3; Datasheet: Section 2.3 (Affected Documents field) |
| **Transparency** | Log must be accessible for review at any time | Specification: CCL-P-004; Procedure: Step 3.6.2; Datasheet: Section 4.1 (Reporting) |
| **Closure Discipline** | Changes are not closed until fully implemented and verified | Specification: CCL-C-007; Procedure: Section 3.5 (Closure steps); Datasheet: Section 2.3 (Closure Date field) |

### 2.2 Guiding Philosophy

Effective change control is essential for maintaining design integrity and managing scope. The log serves as:
- A single source of truth for all design changes
- An audit trail for regulatory and quality purposes
- A management tool for tracking change impacts
- A record for lessons learned and project history

---

## 3. Considerations

### 3.1 Change Classification Considerations

| Change Type | Description | Approval Level (**ASSUMPTION**) | Pass 2 Cross-Reference |
|-------------|-------------|---------------------------------|------------------------|
| **Scope Change** | Changes to contracted scope of work | TM approval required | Specification: CCL-C-004; Datasheet: Section 2.2 (Change Types); Procedure: Step 3.2.4, Step 3.3.4 (TM submission) |
| **Design Modification** | Changes to design within scope | Discipline lead + internal | Specification: CCL-C-004; Datasheet: Section 2.2; Procedure: Step 3.3.2 (Discipline lead approval); Example in Section 5.1 |
| **Deviation** | Departure from TM standards/specifications | TM approval required | Specification: CCL-P-002; Datasheet: Section 2.2; Procedure: Steps 3.3.4-3.3.6 (TM approval tracking); Section 5.2 (Related to DEL-01.14) |
| **MOC** | Management of Change for safety/operability | Per MOC procedure | Specification: CCL-F-004; Datasheet: Section 2.2; Example in Section 5.2 (HAZOP-driven change) |
| **Correction** | Error correction without design change | Internal | Implicit category; Example in Section 5.2 (dimension error) |

### 3.2 When to Log a Change

| Log | Do Not Log |
|-----|------------|
| Scope changes from TM direction | Normal design development/iteration |
| Design modifications after baseline | Comment responses within review cycle |
| Deviations from TM standards | Formatting or editorial corrections |
| HAZOP-driven design changes | Vendor data updates within spec |
| Cost or schedule impacting changes | Minor clarifications |

### 3.3 Affected Document Identification

| Consideration | Guidance |
|---------------|----------|
| **Direct Impact** | Documents that must be revised due to change |
| **Indirect Impact** | Documents that reference affected items |
| **Cascade Tracking** | Track downstream impacts across disciplines |
| **MDR Linkage** | Use MDR document numbers for cross-reference |

---

## 4. Trade-offs

### 4.1 Logging Threshold

| Option | Advantages | Disadvantages |
|--------|------------|---------------|
| **Log Everything** | Complete record; no missed items | High administrative burden |
| **Threshold-Based** | Focuses on significant items | Risk of missing important changes |

**Recommendation:** Log all changes that affect design basis, scope, cost, or schedule; do not log normal iteration within review cycles.

### 4.2 Approval Workflow

| Option | Advantages | Disadvantages |
|--------|------------|---------------|
| **Paper-Based** | Tangible signatures | Slow; hard to track |
| **Email-Based** | Easy to implement | Inconsistent; hard to compile |
| **System-Based** | Structured; auditable | Requires system setup |

**Recommendation:** Use email-based with structured format initially; consider system if volume warrants.

### 4.3 Reporting Frequency

| Option | Advantages | Disadvantages |
|--------|------------|---------------|
| **Real-Time Dashboard** | Always current | Requires infrastructure |
| **Weekly Summary** | Regular rhythm | May miss urgent visibility |
| **On-Demand** | Flexible | Reactive rather than proactive |

**Recommendation:** Weekly internal summary; provide log to TM on request.

---

## 5. Examples

### 5.1 Change Log Entry Example

| Field | Example Value |
|-------|---------------|
| Change ID | DCN-2026-0015 |
| Change Title | Increase Booster Pump Capacity - Pump P-201 |
| Description | Increase pump rated capacity from 1,000 m3/h to 1,100 m3/h based on revised hydraulic analysis |
| Discipline | Process |
| Change Type | Design Modification |
| Reason | Hydraulic analysis (DEL-01.07) identified need for additional capacity margin |
| Affected Documents | DEL-01.09 (Process Datasheet), DEL-03.01 (Equipment List), DEL-01.03 (P&IDs) |
| Cost Impact | TBD - Pending vendor update |
| Schedule Impact | None expected |
| Originator | J. Smith |
| Date Initiated | 2026-03-15 |
| Approval Status | Pending Internal |
| Approver(s) | Process Lead, Project Manager |
| Implementation Status | Not Started |

### 5.2 Change Type Classification Examples

| Change | Classification |
|--------|----------------|
| TM directs addition of spare pump | Scope Change |
| Designer optimizes pipe routing | Design Modification |
| Use of non-TM-standard valve type | Deviation |
| HAZOP recommends additional safety interlock | MOC |
| Correcting dimension error on drawing | Correction |

### 5.3 Approval Workflow Example

```
Change Initiated
    |
    v
Internal Technical Review (Discipline Lead)
    |
    v
Cost/Schedule Impact Assessment (Project Controls)
    |
    v
[If Scope Change or Deviation]
    |
    v
TM Submission and Approval
    |
    v
Implementation Authorization
    |
    v
Document Revisions Completed
    |
    v
Verification and Closure
```

---

## 6. Common Pitfalls

| Pitfall | Prevention Strategy |
|---------|---------------------|
| **Changes Not Logged** | Make logging a gate for document revision |
| **Approval Bypass** | Do not issue revised documents without approval |
| **Incomplete Closure** | Verify all affected documents revised before closing |
| **Lost History** | Maintain log in controlled location; backup regularly |
| **Unclear Classification** | Provide training; establish review for borderline cases |

---

## 7. Notes and Assumptions

1. **ASSUMPTION:** Change classifications shown are illustrative; confirm with project change control procedure.
2. **ASSUMPTION:** Approval levels shown are typical; confirm with TM requirements.
3. **TBD:** TM approval thresholds for different change types.
4. **TBD:** Integration with TM change management systems.

---

## 8. Pass 2 Cross-Reference Notes

### 8.1 Consistency Verification

All change type classifications (Section 3.1) are consistent with:
- Datasheet Section 2.2 (Change Types)
- Specification CCL-C-004 (Change type classification requirement)
- Procedure Step 3.2.4 (Classify change type)
- Example Section 5.2 (Change Type Classification Examples)

### 8.2 Approval Workflow Consistency

The approval workflow example (Section 5.3) aligns with:
- Specification CCL-P-001, CCL-P-002 (Process requirements)
- Procedure Section 3.3 (Approval Process detailed steps)
- Datasheet Section 2.3 (Approval Status, Approver fields)

### 8.3 Best Practice Alignment

Recommendations in Sections 4.1-4.3 (Trade-offs) support:
- Specification requirements marked as "ASSUMPTION" (CCL-F-005, CCL-FM-003)
- Procedure assumptions (weekly reporting, email-based workflow)
- Practical implementation considerations

---

*Generated: Pass 2 - Cross-Reference Consistency Check*
*Source: PSO Decomposition REVISED v2, Industry Best Practices*
