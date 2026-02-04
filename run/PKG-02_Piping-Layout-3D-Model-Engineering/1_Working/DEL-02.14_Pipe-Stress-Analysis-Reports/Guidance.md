# Guidance: DEL-02.14 Pipe Stress Analysis Report(s)

## 1. Purpose

### 1.1 Document Intent
This guidance document provides practical direction for developing Pipe Stress Analysis Reports for the PSO Project at Sumas Tank Farm. It addresses analysis methodology, critical considerations for pump piping, brownfield verification requirements, and common issues to avoid.

### 1.2 Target Audience
- Stress Engineers
- Piping Engineers
- Piping Designers
- Mechanical Engineers (equipment interface)

### 1.3 Context
Pipe stress analysis is critical for the PSO Project due to:
- Five new VS6 booster pumps with sensitive nozzle load requirements
- High-pressure discharge piping with thermal effects
- Complex 5x6 manifold with multiple branches
- Brownfield tie-ins requiring verification of existing system impacts
- CSA Z662 compliance requirements for pipeline facilities

## 2. Principles

### 2.1 Core Principles

| Principle | Description |
|-----------|-------------|
| **Code Compliance** | All stress results must comply with applicable code limits (CSA Z662, ASME B31.3) |
| **Equipment Protection** | Nozzle loads must be within vendor allowables to protect equipment |
| **Support Adequacy** | Support design must accommodate all load cases |
| **Existing System Protection** | Changes must not overstress existing adjacent systems |
| **Documentation** | Analysis must be thoroughly documented for review and future reference |

### 2.2 Analysis Hierarchy

```
Support & Pipe Stress Execution Plan (DEL-02.15)
    |
    +-- Critical Line Identification
    |       |
    |       +-- Line List screening
    |       +-- High temperature/pressure lines
    |       +-- Pump suction/discharge
    |       +-- Large diameter (NPS 12+)
    |
    +-- Stress Analysis
    |       |
    |       +-- Model building from 3D/isometrics
    |       +-- Load case analysis
    |       +-- Code compliance verification
    |
    +-- Output Generation
            |
            +-- Support loads -> DEL-02.16, DEL-02.17
            +-- Nozzle loads -> Equipment verification
            +-- Reports -> DEL-02.14
```

## 3. Considerations

### 3.1 Project-Specific Considerations (PSO)

| Factor | Impact | Guidance |
|--------|--------|----------|
| VS6 Booster Pumps | Sensitive to nozzle loads | Obtain allowable loads early; iterate on routing if needed |
| High Discharge Pressure | Significant sustained stresses | Verify wall thickness adequacy; check sustained stress |
| 5x6 Manifold | Multiple branches, thermal interaction | Model complete manifold system; check branch stresses |
| Brownfield Tie-Ins | Existing system verification required | Model sufficient length of existing piping; verify no overstress |
| VFDs on Pumps | Variable operating conditions | Consider multiple operating cases if temperature varies |
| Crude Oil Service | Temperature variation with blend | Confirm operating temperature range with Process |

### 3.2 Technical Considerations

| Topic | Guidance |
|-------|----------|
| **Operating Cases** | Confirm all operating temperature cases with Process; consider startup/shutdown if significant |
| **Pump Alignment** | Consider pump thermal growth in nozzle load calculation |
| **Friction Loads** | Use appropriate friction coefficients; verify slide plates at expansion points |
| **Anchor Locations** | Locate anchors to control thermal movement; verify anchor loads with structural |
| **Flexibility Provisions** | Use expansion loops or bends rather than bellows where practical |
| **Spring Hangers** | Use variable springs for vertical lines with significant thermal movement |

### 3.3 Existing System Verification (SOW-0240)

| Aspect | Guidance |
|--------|----------|
| Extent of Modeling | Model sufficient length of existing piping to capture interaction effects |
| Existing Support Conditions | Obtain as-built support information; field verify if uncertain |
| Operating Conditions | Confirm operating conditions for existing systems |
| Code Applicability | Apply same code provisions as original design where possible |
| Documentation | Clearly document assumptions about existing system conditions |

### 3.4 Equipment Nozzle Considerations

| Equipment | Consideration |
|-----------|---------------|
| VS6 Booster Pumps | API 610 nozzle loads; both suction and discharge |
| Flow Meters | Sensitive instruments; verify low loads |
| Control Valves | Confirm actuator weight included; verify support |
| Heat Exchangers | If applicable, check nozzle loads |

## 4. Trade-offs

### 4.1 Routing vs. Support Solutions

| Issue | Routing Solution | Support Solution | Recommendation |
|-------|------------------|------------------|----------------|
| High thermal stress | Add expansion loop | Add more supports | Prefer routing for large movements |
| High nozzle loads | Re-route to reduce loads | Add anchor near equipment | Prefer routing to minimize loads |
| Excessive support loads | Redistribute with routing | Strengthen supports | Balance cost and practicality |

### 4.2 Analysis Detail Level

| Approach | Pros | Cons | When to Use |
|----------|------|------|-------------|
| Full flexibility analysis | Complete results, all load cases | Time-consuming | Critical systems, pump piping |
| Simplified/code rules | Faster, conservative | May be overly conservative | Non-critical, simple routing |
| Screening first | Identifies critical lines efficiently | Two-stage process | Large scope with many lines |

### 4.3 Support Type Selection

| Support Type | Use Case | Trade-off |
|--------------|----------|-----------|
| Rest supports | Vertical load only | Low cost, allows horizontal movement |
| Guides | Limit lateral movement | Controls movement, allows axial |
| Anchors | Full restraint | High loads, protects equipment |
| Spring hangers | Vertical movement | Higher cost, maintenance |
| Slide plates | Low friction | Reduces friction loads |

## 5. Examples

### 5.1 Critical Line Screening Checklist

**Criteria for Full Stress Analysis (ASSUMPTION - per execution plan):**
- [ ] Operating temperature > 65C (150F) or < -30C (-20F)
- [ ] Pipe size NPS 12 and larger
- [ ] Connection to rotating equipment (pumps, compressors)
- [ ] Connection to sensitive equipment (heat exchangers, vessels)
- [ ] Jacketed piping
- [ ] Lines with expansion joints or bellows
- [ ] Tie-ins to existing systems
- [ ] Lines identified as stress-critical by project

### 5.2 Load Case Matrix Example

| Case | Description | Temperature | Pressure | Wind | Seismic |
|------|-------------|-------------|----------|------|---------|
| 1 | Weight + Pressure (Sustained) | Ambient | Design | - | - |
| 2 | Operating Case 1 | 60C | Operating | - | - |
| 3 | Operating Case 2 | 40C | Operating | - | - |
| 4 | Expansion (Case 1 - Ambient) | Range | - | - | - |
| 5 | Occasional (Wind) | - | - | Design | - |
| 6 | Occasional (Seismic) | - | - | - | OBE/SSE |
| 7 | Hydrotest | Ambient | Test | - | - |

### 5.3 Nozzle Load Summary Format

| Equipment Tag | Nozzle | Fx (N) | Fy (N) | Fz (N) | Mx (Nm) | My (Nm) | Mz (Nm) | Allow | Util% | Status |
|---------------|--------|--------|--------|--------|---------|---------|---------|-------|-------|--------|
| P-101 | Suction | 2500 | 1500 | 3000 | 2000 | 1000 | 1500 | API 610 | 75% | OK |
| P-101 | Discharge | 4000 | 2000 | 5000 | 3000 | 2000 | 2500 | API 610 | 88% | OK |

### 5.4 Common Issues to Avoid

| Issue | Consequence | Prevention |
|-------|-------------|------------|
| Incomplete operating cases | Missing worst-case | Confirm all operating scenarios with Process |
| Ignoring pump thermal growth | Nozzle overload | Include equipment thermal movement in model |
| Inadequate existing system modeling | Overstress existing piping | Model sufficient length; verify support conditions |
| Missing occasional loads | Code non-compliance | Include all required occasional load cases |
| Friction coefficient assumptions | Wrong support loads | Use appropriate values; consider slide plates |
| Late discovery of high nozzle loads | Expensive rework | Screen early; iterate routing as needed |
| Inconsistent node numbering | Confusion, errors | Establish consistent numbering convention |

### 5.5 Report Quality Checklist

- [ ] Executive summary captures key findings
- [ ] All applicable load cases analyzed
- [ ] Stress ratios shown vs code allowables
- [ ] All code checks pass (or deviations documented)
- [ ] Support loads tabulated with directions
- [ ] Nozzle loads compared to vendor allowables
- [ ] Node diagram/isometric included
- [ ] Operating conditions documented
- [ ] Assumptions clearly stated
- [ ] Native model files submitted per SOW-0259

---
*Document generated 2026-02-01 | Deliverable Status: OPEN*
