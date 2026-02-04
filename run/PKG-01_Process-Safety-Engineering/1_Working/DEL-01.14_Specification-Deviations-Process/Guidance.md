# Guidance: DEL-01.14 Specification Deviations (Process)

**Document ID:** DEL-01.14-GU
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Purpose

This guidance document provides context, best practices, and recommendations for developing and maintaining the Process Specification Deviations Register for the Puget Sound Optimization (PSO) project. Effective deviation management ensures that departures from standards are properly justified, approved, and documented.

---

## 2. Principles

### 2.1 Early Identification

- Identify deviations as early as possible in the design process
- Do not wait until detailed design is complete to recognize deviations
- Proactive identification allows time for proper approval process

### 2.2 Complete Documentation

- Fully document the standard requirement being deviated from
- Provide clear technical justification for the deviation
- Include cost-benefit analysis where applicable
- Document the risk assessment thoroughly

### 2.3 Transparency

- Maintain open communication with TM regarding deviations
- Do not implement deviations before obtaining approval
- Keep register accessible to all project stakeholders

### 2.4 Traceability

- Link each deviation to affected design documents
- Update design documents when deviations are approved
- Maintain audit trail of approval process

---

## 3. Considerations

### 3.1 Technical Considerations

| Consideration | Guidance |
|---------------|----------|
| Safety Impact | Deviations affecting safety require HAZOP review and higher approval authority |
| Reliability Impact | Consider equipment reliability and availability implications |
| Maintainability | Assess impact on future maintenance and operations |
| Interoperability | Consider compatibility with existing TM systems and procedures |
| Regulatory Compliance | Ensure deviations do not violate CSA Z662 or other regulations |

### 3.2 Common Process Deviation Types

| Type | Examples | Typical Justification |
|------|----------|----------------------|
| Equipment Selection | Non-standard vendor, different pump type | Cost, lead time, performance |
| Design Criteria | Different safety factors, margins | Engineering analysis, risk assessment |
| Materials | Alternative materials of construction | Availability, cost, equivalent performance |
| Operating Parameters | Different operating limits | Process optimization, equipment capability |
| Control Philosophy | Non-standard control approach | System integration, performance requirements |

### 3.3 Approval Timing

- Submit deviations for approval before:
  - Finalizing P&IDs that incorporate the deviation
  - Issuing equipment specifications/requisitions
  - Proceeding with detailed design based on deviation

- Allow adequate time for TM review:
  - Minor deviations: ~2 weeks
  - Significant deviations: ~4 weeks
  - Major deviations: ~6+ weeks

(Note: These timelines align with approval authority levels defined in Datasheet Section 3.3)

---

## 4. Trade-offs

### 4.1 Deviation Quantity vs. Approval Burden

| Approach | Advantages | Disadvantages |
|----------|------------|---------------|
| Request Many Deviations | Flexibility in design, potential cost savings | Heavy approval burden, schedule risk |
| Minimize Deviations | Smoother approvals, predictable schedule | May miss optimization opportunities |
| **Recommended:** Request deviations only where clear technical or commercial benefit exists |

### 4.2 Deviation Scope (Bundled vs. Individual)

| Approach | Advantages | Disadvantages |
|----------|------------|---------------|
| Bundle Related Deviations | Single approval for related items, efficient | Risk of partial rejection |
| Individual Submissions | Clear decision on each item | More administrative burden |
| **Recommended:** Bundle closely related deviations; separate independent items |

### 4.3 Justification Depth

| Approach | Advantages | Disadvantages |
|----------|------------|---------------|
| Minimal Justification | Faster preparation | Higher rejection risk, queries |
| Comprehensive Justification | Higher approval rate, fewer queries | More preparation effort |
| **Recommended:** Provide thorough justification proportional to deviation significance |

---

## 5. Examples

### 5.1 Example Deviation Entry

| Field | Example Content |
|-------|-----------------|
| Deviation ID | SD-PR-001 |
| Date Raised | 2026-01-15 |
| Description | Propose to use API 610 VS6 vertical pumps instead of TM standard OH2 horizontal pumps for booster service |
| TM Spec Reference | TM-ES-PUMP-001, Section 4.3.2 |
| Requirement | "Booster pumps shall be horizontal, overhung (OH2) type per API 610" |
| Proposed Alternative | Vertical inline (VS6) type pumps per API 610 |
| Justification | 1) Reduced footprint for confined Sumas Tank Farm location; 2) Elimination of baseplate/foundation costs; 3) Simplified maintenance access; 4) Equivalent reliability per API 610 |
| Risk Assessment | Safety: LOW, Reliability: LOW, Cost: LOW, Schedule: LOW - VS6 pumps are API 610 compliant with equivalent reliability; maintenance procedures available; spare parts availability confirmed with vendor |
| Status | Approved |
| TM Approval Ref | TM-PSO-DEV-2026-012 |
| Approval Date | 2026-02-01 |
| Conditions | Vendor to provide maintenance training; spare rotor assembly to be included in initial spares order |
| Related Documents | DEL-01.03 P&ID-001, DEL-01.09 DS-P-101 |
| Responsible Engineer | J. Smith, Process Lead |

### 5.2 Example Risk Assessment Matrix

| Impact Category | Low | Medium | High |
|-----------------|-----|--------|------|
| Safety | No safety impact | Minor safety consideration, mitigated | Safety-critical change |
| Reliability | No reliability impact | Minor reliability consideration | Significant reliability risk |
| Cost | Neutral or savings | Minor cost increase | Significant cost increase |
| Schedule | No schedule impact | Minor schedule risk | Significant schedule risk |

### 5.3 Common Pitfalls to Avoid

1. **Implementing before approval** - Never incorporate deviations into design documents before TM approval
2. **Incomplete justification** - Provide sufficient technical basis for TM to make informed decision
3. **Missing risk assessment** - Even low-risk deviations need documented assessment
4. **Poor tracking** - Keep register current; do not allow backlog of unrecorded deviations
5. **Scope creep** - Do not expand deviation scope after partial approval

---

*End of Guidance*
