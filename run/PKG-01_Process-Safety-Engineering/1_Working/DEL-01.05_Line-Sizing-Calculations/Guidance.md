# Guidance: DEL-01.05 Line Sizing Calculations

**Document ID:** DEL-01.05-GD
**Revision:** Phase 2.2 (INITIALIZED)
**Date:** 2026-02-01
**Status:** INITIALIZED

---

## Purpose

### Document Intent

This guidance document provides recommendations and best practices for developing Line Sizing Calculations for the Puget Sound Optimization (PSO) project. It supplements the formal specification with practical considerations for sizing process piping at the booster pump station and manifold system at Sumas Tank Farm.

### Target Audience

- Process Engineers (lead and supporting)
- Piping Engineers
- Engineering Managers

---

## Principles

### Foundational Principles

| Principle | Description |
|-----------|-------------|
| Design Basis Traceability | All sizing must trace to DEL-01.01 (DBM) parameters |
| Hydraulic Optimization | Optimize line sizes for cost and performance per SOW-0130 |
| Velocity Compliance | Maintain velocities within code-prescribed limits |
| Coordination | Coordinate with DEL-01.04 (Equipment Sizing) and DEL-01.07 (Hydraulic Analysis) |
| Documentation | Document all assumptions, sources, and TBDs clearly |

### PSO-Specific Considerations

| Consideration | Application | Source |
|---------------|-------------|--------|
| Peak Flow Sizing | Size all lines for 315,000 bpd (2,100 m³/h) | SOW §2.2.1 |
| Manifold Configuration | 5x6 manifold - 5 inlet headers, 6 outlet headers | SOW §2.3.1.1 |
| Pump Suction/Discharge | 5 individual pump lines | SOW §2.3.1.1 |
| Blending Lines | Heavy and Light component lines | SOW §2.3.1.4 |
| Hydraulic Optimization | Coordinate with TM hydraulic analyst | SOW-0130 |

---

## Considerations

### Technical Considerations

#### Velocity Criteria

**ASSUMPTION:** Typical velocity limits for liquid hydrocarbon service:

| Line Type | Recommended Velocity | Considerations |
|-----------|---------------------|----------------|
| Pump Suction | 1.0 - 2.0 m/s | NPSH preservation, low dP |
| Pump Discharge | 3.0 - 5.0 m/s | Erosion limits, economic sizing |
| Manifold Headers | 3.0 - 5.0 m/s | Same as discharge |
| Control Valve Inlet | 2.0 - 3.0 m/s | Noise, cavitation |

Confirm velocity criteria with TMP Standards (Attachment A08) when available.

#### Pressure Drop Budget

Coordinate with DEL-01.07 to establish pressure drop budget:

| Line Segment | dP Allocation | Notes |
|--------------|---------------|-------|
| Tank to Manifold Suction | **TBD** | Preserve NPSHa |
| Manifold Headers | **TBD** | Minimize to preserve pump head |
| Pump Discharge to Pipeline | **TBD** | Balance with pump TDH |

#### Manifold Configuration

Per SOW §2.3.1.1, 5x6 manifold:

| Component | Sizing Considerations |
|-----------|----------------------|
| 5 Inlet Headers | Size for tank suction flows, NPSH |
| 6 Outlet Headers | Size for pump discharge, blending |
| Crossover Piping | Size for flexibility requirements |
| **ASSUMPTION:** Confirm 5x6 interpretation with TM |

#### Line Categories and Sizing Approach

| Line Category | Flow Basis | Critical Parameter |
|---------------|------------|-------------------|
| Tank Suction | Peak total flow | NPSH, low velocity |
| Pump Suction | Individual pump flow | NPSH, low dP |
| Pump Discharge | Individual pump flow | Velocity limits |
| Discharge Headers | Combined flow | Velocity, erosion |
| Blending Lines | Component ratio flows | Turndown, control |
| Auxiliaries | Service-specific | Code requirements |

### Integration Considerations

| Integration Point | Recommendation |
|-------------------|----------------|
| DEL-01.01 DBM | Source for design basis, fluid properties |
| DEL-01.04 Equipment Sizing | Coordinate manifold/header sizes |
| DEL-01.07 Hydraulic Analysis | Source for dP budget, system optimization |
| DEL-02.01 Line List | Output feeds line list development |
| PKG-02 Piping | Coordinate for stress, routing, MTOs |
| Appendix C Hydraulic Report | Reference for preliminary hydraulic data |

---

## Trade-offs

### Design Trade-offs

| Trade-off | Larger Lines | Smaller Lines | Recommendation |
|-----------|--------------|---------------|----------------|
| Capital Cost | Higher (more material) | Lower | Optimize per SOW-0130 |
| Operating Cost (dP) | Lower (less pumping) | Higher | Balance with pump sizing |
| NPSH | Better (lower losses) | Worse | Preserve adequate NPSHa |
| Flexibility | More operational margin | Less margin | Provide reasonable margin |

### Sizing Trade-offs

| Trade-off | Option A | Option B | Recommendation |
|-----------|----------|----------|----------------|
| Velocity Approach | Target low velocity | Target economic velocity | Balance per hydraulic optimization |
| Suction Sizing | Conservative (larger) | Optimized (smaller) | Conservative for NPSH |
| Manifold Headers | Uniform size | Variable sizes | **TBD** - Per hydraulic analysis |

### Risk Considerations

| Risk | Mitigation |
|------|------------|
| Incomplete hydraulic data from DEL-01.07 | Use Appendix C as interim; document assumptions |
| Velocity criteria uncertainty | Document assumed criteria; verify with TMP Standards (Attachment A08) |
| dP budget uncertainty | Coordinate with DEL-01.07 development |
| Fluid property variations | Apply appropriate safety factors |

---

## Examples

### Example 1: Line Sizing Summary Table

```
| Line No. | Service | Size (in) | Flow (m³/h) | Velocity (m/s) | dP (kPa) | Class |
|----------|---------|-----------|-------------|----------------|----------|-------|
| HC-XX-001| Tank Suction Header | TBD | TBD | TBD | TBD | TBD |
| HC-XX-002| Manifold Inlet | TBD | TBD | TBD | TBD | TBD |
| HC-XX-010| Pump A Suction | TBD | TBD | TBD | TBD | TBD |
| HC-XX-011| Pump A Discharge | TBD | TBD | TBD | TBD | TBD |
| ... | ... | ... | ... | ... | ... | ... |
```

### Example 2: Calculation Report Structure

```
1. Introduction and Scope
2. Design Basis Summary (from DEL-01.01)
   2.1 Flow Rates (275,000 bpd sustainable, 315,000 bpd peak)
   2.2 Fluid Properties
   2.3 Design Conditions
3. Hydraulic Data (from DEL-01.07)
   3.1 System Pressures
   3.2 Pressure Drop Budget
4. Sizing Criteria
   4.1 Velocity Limits
   4.2 Pressure Drop Allowances
   4.3 Applicable Standards
5. Line Sizing Calculations
   5.1 Tank Suction Headers
   5.2 Manifold Headers (5 inlet, 6 outlet)
   5.3 Pump Suction Lines (5)
   5.4 Pump Discharge Lines (5)
   5.5 Discharge Headers
   5.6 Blending Lines
   5.7 Auxiliary Lines
6. Line Size Summary
7. Pipe Class Designations
8. Assumptions and TBDs
9. References
Appendix A: Calculation Sheets
Appendix B: Hydraulic Data Extracts
```

### Example 3: Velocity Calculation Example

```
Line: Pump A Discharge (HC-XX-011)

Given:
- Flow Rate (Q): TBD m³/h = TBD m³/s
- Pipe Size: TBD inches = TBD mm
- Pipe ID: TBD mm = TBD m

Calculation:
- Area (A) = π × (ID/2)² = TBD m²
- Velocity (V) = Q / A = TBD m/s

Check:
- Allowable Velocity: 3.0 - 5.0 m/s
- Calculated Velocity: TBD m/s
- Status: TBD (OK / REVISE)
```

### Example 4: Assumption Documentation Format

```
ASSUMPTION: Pump suction line velocity is limited to 2.0 m/s maximum to
ensure adequate NPSH margin at the pump suction.

Basis: Industry practice for vertically suspended pumps, API 610
Impact: Determines suction line size, affects NPSH available
Action Required: Verify with TMP Standards (Attachment A08) and pump vendor requirements
Status: OPEN - Pending TMP Standards review
```

---

## Additional Resources

### Related Guidance Documents

| Document | Relevance |
|----------|-----------|
| DEL-01.01 Guidance | Design basis parameters - input source |
| DEL-01.04 Guidance | Equipment sizing coordination |
| DEL-01.07 Guidance | Hydraulic analysis - dP budget source |
| DEL-02.01 Guidance | Line List - output coordination |

### Coordination Checklist

- [ ] Obtain design basis from DEL-01.01 (flow rates, fluid properties)
- [ ] Obtain hydraulic data from DEL-01.07 (concurrent development)
- [ ] Review Appendix C Hydraulic Report for preliminary data
- [ ] Confirm velocity criteria with TMP Standards (Attachment A08) when available
- [ ] Coordinate manifold sizing with DEL-01.04 (Equipment Sizing)
- [ ] Confirm 5x6 manifold interpretation (5 inlet, 6 outlet) with TM
- [ ] Coordinate with PKG-02 for piping stress and routing
- [ ] Provide line sizing output to DEL-02.01 (Line List)
- [ ] Document all assumptions and TBDs

---

*End of Guidance*
