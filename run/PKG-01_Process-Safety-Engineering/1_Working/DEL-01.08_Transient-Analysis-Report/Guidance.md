# Guidance: DEL-01.08 Transient Analysis Report

**Document ID:** DEL-01.08-GD
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Purpose

### 1.1 Document Intent

This guidance document provides recommendations and best practices for developing the Transient Analysis Report for the Puget Sound Optimization project. It supplements the formal specification with practical considerations for surge and waterhammer analysis.

### 1.2 Target Audience

- Process Engineers (lead and supporting)
- Hydraulic Analysts / Transient Specialists
- Pump Application Engineers
- Controls Engineers
- Piping Engineers
- Project Engineers

---

## 2. Principles

### 2.1 Foundational Principles

| Principle | Description |
|-----------|-------------|
| Safety Focus | Transient analysis is critical for system integrity and safety |
| Worst-Case Analysis | Identify and analyze worst-case credible scenarios |
| Validated Model | Build transient model on validated steady-state hydraulic model |
| Conservative Assumptions | Use conservative assumptions for uncertain parameters |
| Mitigation-Ready | Be prepared to recommend mitigation measures if required |

### 2.2 Integration Principles

| Principle | Application |
|-----------|-------------|
| Steady-State Basis | Transient model must be consistent with DEL-01.07 steady-state model |
| Vendor Coordination | Obtain pump inertia and valve closure data from vendors |
| Controls Integration | Coordinate with PKG-07 controls discipline for realistic valve timing |

---

## 3. Considerations

### 3.1 Technical Considerations

#### 3.1.1 Key Transient Events

For the PSO booster pump station, the following transient events are typically critical:
- **Pump Trip**: Most critical event; sudden loss of pump head creates pressure wave
- **Power Failure**: All pumps trip simultaneously; worst-case scenario
- **Check Valve Closure**: Reverse flow and valve slam after pump trip
- **Emergency Valve Closure**: Rapid closure of emergency shutdown valves
- **Pump Startup**: Can cause pressure transients, especially with empty lines
- **VFD Speed Changes**: Rapid speed changes during operation

**ASSUMPTION:** Power failure with simultaneous trip of all running pumps is typically the governing case.

#### 3.1.2 Wave Speed Calculation

Accurate wave speed is critical for transient analysis:
- Depends on fluid bulk modulus and pipe wall elasticity
- Affected by pipe material, diameter, wall thickness, and restraint
- Air/gas content significantly reduces wave speed
- **ASSUMPTION:** For liquid petroleum products in steel pipe, wave speed typically 900-1200 m/s

#### 3.1.3 Pump Characteristics

Critical pump data for transient analysis:
- Complete pump curves (head, power, efficiency vs. flow)
- Pump inertia (WR2) for rundown/startup calculation
- NPSH required curve for cavitation prediction
- **ASSUMPTION:** If vendor data unavailable at IFR, estimate inertia from impeller diameter and speed

#### 3.1.4 Valve Characteristics

Critical valve data for transient analysis:
- Closure time (full open to full closed)
- Closure curve shape (linear, equal percentage, quick-opening)
- Check valve slam velocity limits
- **ASSUMPTION:** Typical check valve slam limit is 1.5-2.0 m/s reverse velocity at closure

### 3.2 Project Considerations

| Consideration | Recommendation |
|---------------|----------------|
| VFD Impact | VFD-controlled pumps may have controlled rundown; verify with vendor |
| Check Valve Selection | Non-slam check valves may be required if slam predicted |
| Surge Protection | Evaluate need for surge vessels, relief valves, or surge control |
| System Boundaries | Coordinate boundary conditions with TM existing system |
| HAZOP Integration | Review DEL-01.15 HAZOP findings for transient scenarios |

### 3.3 Quality Considerations

| Aspect | Recommendation |
|--------|----------------|
| Model Validation | Validate against steady-state (DEL-01.07) before running transients |
| Parameter Sensitivity | Run sensitivity on wave speed, pump inertia, valve timing |
| Peer Review | Have analysis reviewed by experienced transient analyst |
| Documentation | Document all model settings and assumptions clearly |

---

## 4. Trade-offs

### 4.1 Design Trade-offs

| Trade-off | Option A | Option B | Recommendation |
|-----------|----------|----------|----------------|
| Surge Protection | Surge vessel | Surge relief valve | Depends on system; evaluate both |
| Check Valve Type | Standard swing check | Non-slam/soft-close | Non-slam if reverse velocity high |
| Valve Closure Time | Fast (simpler, cheaper) | Slow (lower surge) | Balance operational need vs. surge control |
| VFD Ramp Time | Fast response | Slow (surge limiting) | Coordinate with PKG-07 controls discipline |

### 4.2 Modeling Trade-offs

| Trade-off | Simple | Detailed | Recommendation |
|-----------|--------|----------|----------------|
| Model Detail | Lumped parameter | Method of characteristics | Method of characteristics for accuracy |
| Boundary Conditions | Fixed pressure/flow | Full upstream/downstream | Include sufficient system extent |
| Cavitation Model | None | Column separation | Include if pressures approach vapor |

### 4.3 Risk Considerations

| Risk | Mitigation |
|------|------------|
| Inaccurate pump inertia | Obtain vendor data; sensitivity analysis |
| Unknown valve timing | Coordinate with controls; use conservative fast closure |
| Missed scenarios | Systematic scenario identification; review DEL-01.15 HAZOP input |
| Late design changes | Plan for model update at IFC with final data |

---

## 5. Examples

### 5.1 Transient Analysis Report Structure (Typical)

```
1. Executive Summary
   - Key findings
   - Maximum/minimum pressures
   - Mitigation requirements (if any)

2. Introduction and Scope
   - Project overview
   - Analysis objectives
   - Reference documents

3. System Description
   - Physical layout
   - Equipment summary
   - Control philosophy

4. Methodology
   - Software description
   - Modeling approach (method of characteristics, etc.)
   - Model boundaries

5. Input Data
   - Piping data (lengths, diameters, wave speeds)
   - Pump data (curves, inertia)
   - Valve data (closure times, characteristics)
   - Fluid properties

6. Transient Scenarios
   - Scenario matrix
   - Selection rationale
   - Governing case identification

7. Analysis Results
   - Scenario-by-scenario results
   - Pressure/flow vs. time plots
   - Maximum/minimum pressure envelopes

8. Mitigation Analysis (if required)
   - Mitigation options evaluated
   - Recommended solution
   - Mitigated case results

9. Conclusions and Recommendations
   - Summary of findings
   - Recommended actions

10. Appendices
    - Model schematics
    - Detailed time histories
    - Input data listings
```

### 5.2 Transient Scenario Matrix (Template)

| Scenario ID | Description | Initial State | Event | Duration | Priority |
|-------------|-------------|---------------|-------|----------|----------|
| TS-01 | Single pump trip | Max flow, all pumps | Pump 1 trips | Instantaneous | High |
| TS-02 | Power failure | Max flow, all pumps | All pumps trip | Instantaneous | High |
| TS-03 | Pump startup | Idle | Pump 1 starts | VFD ramp | Medium |
| TS-04 | Sequential pump startup | One pump running | Second pump starts | VFD ramp | Medium |
| TS-05 | Control valve close | Normal flow | CV fails closed | **TBD** sec | High |
| TS-06 | Check valve slam | Pump trip | Check valve slams | Per valve dynamics | High |
| TS-07 | VFD speed change | Normal flow | Speed reduction | VFD ramp | Medium |
| TS-08 | ESD valve closure | Normal flow | ESD activated | **TBD** sec | High |

### 5.3 Common Pitfalls to Avoid

- Using incorrect wave speed (often overestimated)
- Not modeling check valve dynamics properly
- Ignoring cavitation/column separation potential
- Using unrealistic valve closure times
- Not validating against steady-state model (DEL-01.07)
- Not coordinating with controls discipline (PKG-07) for valve timing
- Missing scenarios identified in HAZOP (DEL-01.15)

---

## 6. Additional Resources

### 6.1 Related Guidance Documents

| Document | Relevance |
|----------|-----------|
| DEL-01.07 Guidance | Steady-state basis for transient model |
| DEL-01.06 Guidance | Relief device sizing may use transient pressures |
| DEL-01.15 Guidance | HAZOP scenarios inform transient event selection |
| PKG-07 Guidance | Controls discipline for valve timing |

### 6.2 Industry References

| Reference | Application |
|-----------|-------------|
| AWWA M11 | Surge analysis guidelines |
| Wylie & Streeter | Fluid Transients in Systems (textbook) |
| AFT Impulse Manual | Software-specific guidance |
| Hydraulic Institute | Pump transient considerations |

---

*End of Guidance*
