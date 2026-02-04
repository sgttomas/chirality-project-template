# Guidance: DEL-01.15 HAZOP Final Report & Closeout Items

**Document ID:** DEL-01.15-GU
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Purpose

This guidance document provides context, best practices, and recommendations for conducting the HAZOP study and developing the Final Report and Closeout Items for the Puget Sound Optimization (PSO) project. Effective HAZOP execution is critical for identifying and mitigating process hazards before commissioning.

---

## 2. Principles

### 2.1 Systematic Approach

- Follow IEC 61882 methodology consistently
- Apply guidewords systematically to each parameter
- Do not skip nodes or shortcut the analysis
- Document all discussions, even where no hazard identified

### 2.2 Team Engagement

- Ensure active participation from all disciplines
- Value operational experience highly
- Encourage open discussion of potential hazards
- Avoid dismissing concerns without proper consideration

### 2.3 Documentation Quality

- Record sufficient detail to understand decisions later
- Document safeguards and their limitations
- Capture the basis for risk rankings
- Maintain clear action item descriptions

### 2.4 Action Closure Rigor

- Track all recommendations through to closure
- Require evidence of implementation
- Re-assess risk after mitigation implemented
- Do not close actions without proper verification

---

## 3. Considerations

### 3.1 Technical Considerations

| Consideration | Guidance |
|---------------|----------|
| Node Selection | Define nodes at meaningful process boundaries; not too large (miss detail) or too small (inefficient) |
| Interface Nodes | Pay special attention to tie-ins with existing systems |
| Control System | Include control system failures and cybersecurity considerations |
| Human Factors | Consider operator actions and potential for human error |
| Maintenance | Include scenarios during maintenance activities |
| Startup/Shutdown | Analyze non-steady-state operations |

### 3.2 PSO-Specific Considerations

| Area | Consideration | Source |
|------|---------------|--------|
| Multiple Pumps | 5 booster pumps with VFDs - consider parallel operation scenarios | SOW 2.3.1.2 |
| Blending System | Flow ratio control, composition deviations | SOW 2.3.1.4 |
| Tie-ins | Interface with existing TK-101, TK-102 suction systems | SOW 2.3.1.1 |
| Containment | Sump tank, reinjection pumps, containment wall integrity | SOW 2.3.1.1 |
| Pipeline Interface | Discharge to Puget Sound Pipeline | Project scope |

### 3.3 Common Hazard Categories

| Category | Example Scenarios |
|----------|-------------------|
| Overpressure | Blocked discharge, thermal expansion, hydraulic surge |
| Loss of Containment | Flange leak, pump seal failure, corrosion |
| Fire/Explosion | Leak + ignition source, static discharge |
| Environmental | Spill to ground, containment overflow |
| Equipment Damage | Cavitation, deadhead, reverse rotation |
| Process Upset | Off-spec product, incorrect blend ratio |

---

## 4. Trade-offs

### 4.1 Study Depth vs. Schedule

| Approach | Advantages | Disadvantages |
|----------|------------|---------------|
| Thorough Study | Comprehensive hazard identification | More time required |
| Abbreviated Study | Faster completion | Risk of missing hazards |
| **Recommended:** Allocate adequate time; do not compress HAZOP schedule to meet deadlines |

### 4.2 Action Item Specificity

| Approach | Advantages | Disadvantages |
|----------|------------|---------------|
| Highly Specific Actions | Clear scope, easy to close | May be overly prescriptive |
| General Recommendations | Flexibility in implementation | Ambiguous closure criteria |
| **Recommended:** Specific enough to verify closure; allow reasonable design flexibility |

### 4.3 Risk Ranking Approach

| Approach | Advantages | Disadvantages |
|----------|------------|---------------|
| Conservative Ranking | Highlights more scenarios for action | May dilute focus on true high risks |
| Realistic Ranking | Focuses resources on genuine hazards | Risk of underestimating |
| **Recommended:** Apply consistent criteria using TM-approved risk matrix; escalate borderline cases for team discussion |

### 4.4 Safeguard Credit

| Approach | Advantages | Disadvantages |
|----------|------------|---------------|
| Credit All Safeguards | Lower risk rankings | May overstate protection |
| Limited Safeguard Credit | Conservative approach | May generate unnecessary actions |
| **Recommended:** Credit only independent, reliable safeguards; document basis for credit |

---

## 5. Examples

### 5.1 Example Node Definition

**Node: Booster Pump Suction System**

| Element | Description |
|---------|-------------|
| Node ID | PSO-NODE-001 |
| Description | Pump suction system from TK-102 isolation valve to pump suction nozzle |
| P&ID Reference | PID-PSO-001, Rev B |
| Design Intent | Provide adequate NPSH to booster pumps under all operating conditions |
| Operating Conditions | Flow: 0-2,100 m3/h; Pressure: **TBD** kPag; Temp: **TBD** degC |
| Parameters | Flow, Pressure, Level (tank), Temperature, Composition |

### 5.2 Example HAZOP Worksheet Entry

| Field | Content |
|-------|---------|
| Node | PSO-NODE-001 - Pump Suction |
| Guideword | NO |
| Parameter | Flow |
| Deviation | No flow to pump suction |
| Cause | 1) Suction valve closed; 2) Suction strainer blocked; 3) Tank empty |
| Consequence | Pump runs dry, seal damage, potential fire from seal failure |
| Safeguards | Low suction pressure trip, pump vibration monitoring |
| Risk Ranking (Pre) | C3 (Medium - per TM-approved matrix) |
| Recommendation | Add low-low flow trip interlock to protect pump |
| Risk Ranking (Post) | C2 (Low) |
| Action ID | HAZOP-PSO-001 |

### 5.3 Example Action Item Entry

| Field | Content |
|-------|---------|
| Action ID | HAZOP-PSO-001 |
| Node | PSO-NODE-001 |
| Deviation | No flow to pump suction |
| Cause | Suction valve closed, strainer blocked, tank empty |
| Consequence | Pump seal damage, potential fire |
| Safeguard | Low suction pressure trip, vibration monitoring |
| Recommendation | Add low-low flow trip interlock to protect pump from dry running |
| Risk Ranking (Pre) | C3 (Medium) |
| Response | Flow interlock added to logic; pump trips on low-low flow with 5-second delay |
| Responsible Party | Contractor - I&C Engineering |
| Due Date | IFD P&ID Issue |
| Status | Closed |
| Closure Evidence | P&ID PID-PSO-001 Rev C shows interlock; Cause & Effect Diagram CEL-001 includes logic |
| Verified By | Lead Process Engineer |
| Closure Date | 2026-XX-XX |
| Risk Ranking (Post) | C2 (Low) |

### 5.4 Common Pitfalls to Avoid

1. **Rushing the study** - Inadequate time leads to incomplete analysis
2. **Inexperienced facilitator** - Poor facilitation results in missed hazards
3. **Missing stakeholders** - Lack of operations input limits practical insight
4. **Vague actions** - Unclear recommendations are difficult to close
5. **Poor follow-through** - Actions not tracked lead to unmitigated hazards
6. **Insufficient documentation** - Cannot reconstruct decisions made during study
7. **Using outdated P&IDs** - Study results do not match actual design

---

*End of Guidance*
