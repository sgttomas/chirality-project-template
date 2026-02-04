# Guidance: DEL-01.01 Process Design Basis / DBM (Design Basis & Design Criteria)

**Document ID:** DEL-01.01-GD
**Revision:** Phase 2.2 (INITIALIZED)
**Date:** 2026-02-01
**Status:** INITIALIZED

---

## Purpose

### Document Intent

This guidance document provides direction for developing the Process Design Basis / Design Basis Memorandum (DBM) for the Puget Sound Optimization Project. The DBM serves as the foundational document establishing process parameters, design criteria, and equipment basis that all other engineering deliverables must reference and align with.

### Target Audience

- Process Engineers (lead and supporting)
- Safety Engineers
- Project Engineers
- Engineering Managers
- Document Control personnel

---

## Principles

### Foundational Principles

| Principle | Description |
|-----------|-------------|
| Single Source of Truth | The DBM shall serve as the authoritative source for process design parameters. All other deliverables (PFDs, P&IDs, equipment sizing, line sizing) must derive their design basis from this document. |
| Traceability | All design basis values shall be traceable to source documents (SOW, preliminary DBM, hydraulic reports, or TM direction). Where engineering judgment is applied, document the basis and rationale. |
| Conservative Design Basis | Where uncertainty exists in input parameters, apply conservative assumptions that result in robust equipment sizing while remaining cost-effective. Document all assumptions clearly. |
| Consistency | Parameters must be internally consistent across all sections and aligned with downstream deliverables. |
| Regulatory Alignment | The DBM shall establish design basis parameters that support compliance with applicable regulations (CER, CSA Z662, PHMSA) without requiring variances unless explicitly approved. |

### Integration Principles

| Principle | Application |
|-----------|-------------|
| Early Coordination | Engage all disciplines during DBM development |
| Living Document | Plan for revisions as project progresses (IFR → IFD → IFC) |
| Baseline Establishment | Lock parameters at key milestones |
| Flexibility and Operability | Accommodate required operating flexibility per DBM §2.2.2.1-§2.2.2.4 |

---

## Considerations

### Technical Considerations

#### Battery Limits and Interface Definition
- Clearly define project battery limits (physical boundaries of new work scope)
- Identify all interface points with existing Sumas Terminal facilities
- Document interface conditions (pressures, temperatures, flow rates, tie-in requirements)
- Coordinate with existing facility drawings and data (Source: SOW §3.2.2.15)

#### Hydraulic Performance Integration
- Coordinate closely with hydraulic modeling (Appendix C) to ensure design basis aligns with system hydraulics (Source: SOW §3.1.3.2)
- Verify suction conditions at tanks under peak flow scenarios
- Account for manifold and valve pressure drops
- Optimize piping/valve sizes and pump performance for cost and performance (Source: SOW §3.1.3.2)

#### Blending Control Philosophy
- Document basis for flow ratio control between heavy and light streams
- **Open Issue:** Blend range differs between SOW (20% Heavy/80% Light) and DBM (10%-100% NEAT where NEAT = 100% undiluted heavy crude) - confirm with TM which range to use
- **Terminology Note:** NEAT typically means undiluted product; 100% NEAT = pure heavy crude, 10% NEAT = 10% heavy/90% light
- Address minimum turndown requirements for individual pumps (typically 50% of rated capacity for VS6 pumps - **ASSUMPTION**)
- Consider VFD operating range implications (typically 30-100% speed)

#### Equipment Basis Verification
- The SOW notes preliminary engineering is informational only (Source: SOW §4.2.2.2)
- Verify and finalize equipment sizing basis during FEED (Source: SOW §2.3.1.6)
- Document any changes from preliminary DBM with justification
- Confirm pump sizes: 2 large-capacity, 2 small-capacity, 1 medium-capacity (Source: SOW §2.3.1.2)

#### Existing Facility Integration
- Document interface conditions with existing Sumas Terminal infrastructure (Source: SOW §3.2.2.15)
- Address tie-in conditions and transition requirements
- Consider brownfield constraints (access, shutdown windows)
- Reference latest TM drawing revisions per SOW requirements

#### Material Selection Criteria
- Establish preliminary material selection based on:
  - Crude oil properties and corrosivity
  - TMP material standards (Attachment A08 - **TBD**)
  - Environmental conditions (temperature, seismic)
  - Design life requirements (typically 25-30 years - **ASSUMPTION**)
  - Corrosion allowance requirements per TMP standards
- Document any special material requirements for blending service

### Process Considerations

| Consideration | Recommendation |
|---------------|----------------|
| Stakeholder Input | Obtain TM confirmation on blending range requirements (SOW vs DBM discrepancy noted) |
| Operating Envelope | Confirm acceptable operating envelope boundaries with TM operations, including minimum turndown |
| Revision Management | Maintain clear revision history; issue formal revisions at IFR, IFD, and IFC milestones |
| Assumption Tracking | Track all assumptions that impact other deliverables in assumptions register |
| Preliminary DBM Use | Treat preliminary DBM as informational only per SOW §4.2.2.2; verify all parameters during FEED |
| Regulatory Verification | Confirm applicability of BC and Washington State regulations early in FEED |
| Deviation Management | Track any deviations from TMP standards; obtain TM approval before finalizing |

### Quality Considerations

| Aspect | Recommendation |
|--------|----------------|
| Peer Review | Conduct internal peer review before IFR |
| Calculation Backup | Reference supporting calculations |
| Assumption Log | Maintain separate assumption tracking log with confirmation status |
| IDC Review | Ensure interdisciplinary check before each issue stage |

---

## Trade-offs

### Design Trade-offs

| Trade-off | Option A | Option B | Recommendation |
|-----------|----------|----------|----------------|
| Design Margin | Higher margins (15-20%) provide operational flexibility | Lower margins (10%) reduce capital cost | **ASSUMPTION** - Apply standard industry margins (typically 10-15%) pending TM guidance |
| Blending Range | Wide range (10-100% NEAT per DBM) requires larger equipment | Narrow range (20-80% per SOW) allows optimization | Confirm with TM; document agreed range in DBM |
| Flow Rate Basis | Size all equipment for peak (315,000 bpd) | Size for sustainable (275,000 bpd) with turndown | SOW requires equipment sized for peak; document accordingly |
| Conservative Assumptions | More conservative = larger equipment, higher cost | Less conservative = tighter margins, performance risk | Balance conservatism with cost; document basis for each parameter |
| Code Selection | CSA Z662 only | CSA Z662 + ASME B31.4 | Use both as applicable per jurisdiction |

### Schedule Trade-offs

| Trade-off | Fast Track | Standard | Recommendation |
|-----------|------------|----------|----------------|
| DBM Completion | Preliminary issue, early | Final issue, later | Align with FEED schedule milestones |
| TM Review Cycles | Parallel development | Sequential review | **TBD** - Per project schedule agreement |

### Risk Considerations

| Risk | Mitigation |
|------|------------|
| Incomplete TM standards (Attachment A08 not in workspace) | Early request for standards package; escalate if delayed |
| Hydraulic model changes | Document assumptions, plan for updates per DEL-01.07 |
| Blending range discrepancy (SOW vs DBM) | Submit clarification RFI to TM; document resolution in DBM |
| Scope creep | Formal change control process per PKG-00 |
| Late vendor data | Identify long-lead items early; plan for DBM updates at IFD/IFC stages |
| Unconfirmed regulatory requirements | Verify BC and Washington State applicability early; consult regulatory specialist if needed |
| Material selection without TMP standards | Use conservative industry practice until TMP standards received |

---

## Examples

### Example 1: DBM Section Structure (Typical)

```
1. Introduction and Project Overview
2. Scope and Boundaries
   2.1 Project Scope
   2.2 Exclusions (Laurel Pump Station excluded)
3. Design Codes and Standards
   3.1 CER OPR, CSA Z662, PHMSA 195
   3.2 TMP Standards and Specifications
4. Process Design Criteria
   4.1 Fluid Properties
   4.2 Flow Rates (275,000 bpd sustainable, 315,000 bpd peak)
   4.3 Pressures and Temperatures
   4.4 Blending Requirements
5. Equipment Design Basis
   5.1 Booster Pumps (5 VS6-type)
   5.2 Manifold (5x6 configuration)
   5.3 VFDs and Flow Metering
6. Environmental Conditions
   6.1 Ambient Conditions
   6.2 Seismic Criteria
7. Material Selection Criteria
8. Safety and Overpressure Protection
9. Interface Definitions
   9.1 Existing Tank Farm Interfaces
   9.2 Downstream Pipeline Interface
10. Deviations from Standards
11. Appendices
```

### Example 2: Design Parameters Table Structure

| Parameter | Value | Units | Basis/Source | Notes |
|-----------|-------|-------|--------------|-------|
| Design Flow Rate (Peak) | 315,000 | bpd | SOW §2.2.1 | Equipment sizing basis |
| Design Flow Rate (Peak) | 2,100 | m³/h | Converted | SI equivalent |
| Sustainable Flow Rate | 275,000 | bpd | SOW §2.2.1 | Normal operating basis |
| Minimum Flow Rate | **TBD** | bpd | TM Confirmation | Turndown requirement |
| Blend Ratio (Heavy) - SOW | 20-80 | % | SOW §2.3.1.4 | SOW specification |
| Blend Ratio (Heavy) - DBM | 10-100 | % NEAT | DBM §2.2.2.2 | DBM specification (NEAT = undiluted) |
| Blend Ratio - Final | **TBD** | % | TM Confirmation Required | **CONFLICT:** Resolve SOW vs DBM discrepancy |
| Minimum Flow Rate (Turndown) | **TBD** | bpd | **ASSUMPTION:** 50% of rated | VFD/pump capability basis |
| Number of Booster Pumps | 5 | units | SOW §2.3.1.1 | VS6-type |
| Large Capacity Pumps | 2 | units | SOW §2.3.1.2 | |
| Small Capacity Pumps | 2 | units | SOW §2.3.1.2 | |
| Medium Capacity Pumps | 1 | units | SOW §2.3.1.2 | |

### Example 3: Assumption Documentation Format

```
ASSUMPTION: The minimum pump flow rate is assumed to be 50% of rated
capacity based on typical VS6 pump turndown characteristics.

Basis: Industry practice for vertically suspended pumps
Impact: Affects control valve sizing and VFD range requirements
Action Required: Confirm with pump vendor during FEED
Status: OPEN - Pending vendor data
```

### Example 4: Reference Documents Checklist

- [ ] TM Engineering Standards (Attachment A08) - **TBD** - CRITICAL for material selection and design criteria
- [x] Preliminary DBM (Puget Sound Optimization Project DBM.pdf) - Use as informational reference only per SOW §4.2.2.2
- [x] Appendix B - PFD reference
- [x] Appendix C - Hydraulic Report
- [x] Appendix A-1, A-2 - Layout references
- [ ] Existing facility P&IDs - **TBD** - Required for interface definition
- [ ] Geotechnical reports - **TBD** - Required for seismic and foundation design
- [ ] Environmental assessments - **TBD** - May affect regulatory requirements
- [ ] Crude oil specifications/assays - **TBD** - Required for material selection and fluid properties
- [ ] Regulatory confirmation (BC, Washington State) - **TBD** - Verify applicability

---

## Conflict Resolution Table

The following table documents conflicts identified during Pass 2 cross-reference consistency check that require resolution:

| Conflict ID | Issue | Source A | Source B | Impact | Resolution Required | Status |
|-------------|-------|----------|----------|--------|---------------------|--------|
| CONF-01 | Blending range discrepancy | SOW §2.3.1.4: "20% Heavy to 80% Light" | DBM §2.2.2.2: "10%-100% NEAT" | Equipment sizing may be over/under-designed depending on actual operating range | TM to confirm required blending range; clarify if NEAT terminology (100% = undiluted heavy) differs from ratio presentation | **OPEN** |

**Resolution Actions Required:**
- Submit RFI to TM requesting clarification on blending range requirement
- Confirm if terminology difference (ratio vs NEAT) represents actual operating envelope difference
- Update DBM to reflect confirmed range
- Verify impact on equipment sizing (DEL-01.04) and line sizing (DEL-01.05)

---

*End of Guidance*
