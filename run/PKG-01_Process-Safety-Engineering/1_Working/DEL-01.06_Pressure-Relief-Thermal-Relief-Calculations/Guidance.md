# Guidance: DEL-01.06 Pressure Relief / Thermal Relief Calculations

**Document ID:** DEL-01.06-GD
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Purpose

### 1.1 Document Intent

This guidance document provides recommendations and best practices for developing Pressure Relief and Thermal Relief Calculations for the Puget Sound Optimization project. It supplements the formal specification with practical considerations for relief device need verification and sizing.

### 1.2 Target Audience

- Process Engineers (lead and supporting)
- Safety Engineers
- Piping Engineers (for inlet/outlet piping)
- Mechanical Engineers (for device selection)
- Project Engineers

---

## 2. Principles

### 2.1 Foundational Principles

| Principle | Description |
|-----------|-------------|
| Safety Priority | Overpressure protection is a safety-critical function; err on the conservative side |
| Worst-Case Scenario | Size devices for the most demanding credible scenario |
| Code Compliance | Follow API 520/521 methodology strictly |
| Traceability | Document all assumptions and data sources clearly |
| Consistency | Ensure relief calculations align with hydraulic analysis and P&IDs |

### 2.2 Integration Principles

| Principle | Application |
|-----------|-------------|
| Early Identification | Identify relief requirements during PFD/P&ID development |
| HAZOP Coordination | Use HAZOP to validate relief scenarios |
| Vendor Coordination | Coordinate with valve vendors for final selection |

---

## 3. Considerations

### 3.1 Technical Considerations

#### 3.1.1 Relief Scenario Identification

For the PSO booster pump station, consider the following scenarios:
- **Blocked Outlet**: Centrifugal pump dead-head condition
- **Thermal Expansion**: Liquid trapped between closed valves exposed to solar heating or fire
- **Control System Failure**: Failure of flow/pressure control causing overpressure (coordinate with DEL-01.15 HAZOP)
- **Check Valve Failure**: Reverse flow scenarios (less common for PRVs)
- **Fire Case**: External fire impingement (**TBD** - if applicable per API 521 screening criteria)
- **Power Failure / Surge**: Transient pressure events (coordinate with DEL-01.08 transient analysis)

**ASSUMPTION:** For typical liquid pipeline service, thermal relief is often the governing case for blocked-in sections.

#### 3.1.2 Pump Relief Considerations

- Centrifugal pumps may require TRV protection on the casing when isolated
- Pump discharge relief may be needed if downstream block valves can close against running pump
- **ASSUMPTION:** VFD-controlled pumps may have reduced relief requirements due to controlled shutdown, but this must be verified

#### 3.1.3 Manifold Relief Considerations

- 5x6 manifold configuration may create multiple blocked-in sections
- Each independent section requiring isolation must be evaluated for thermal relief
- Header interconnections may provide alternative relief paths

### 3.2 Project Considerations

| Consideration | Recommendation |
|---------------|----------------|
| Existing System | Verify relief requirements for tie-in points to existing systems |
| TM Standards | Confirm TM-specific relief requirements and preferred device types |
| Downstream Disposal | Coordinate relief discharge disposition with layout/environmental |
| Noise/Environmental | Consider noise and environmental requirements for atmospheric discharge |

### 3.3 Quality Considerations

| Aspect | Recommendation |
|--------|----------------|
| Independent Check | Have relief calculations independently checked by qualified engineer |
| Assumption Documentation | Maintain detailed assumption log for HAZOP/review discussion |
| Sensitivity Analysis | Perform sensitivity analysis on key parameters |

---

## 4. Trade-offs

### 4.1 Design Trade-offs

| Trade-off | Option A | Option B | Recommendation |
|-----------|----------|----------|----------------|
| Relief Device Type | Conventional PRV | Pilot-operated PRV | Per application; pilot-operated for high-pressure, large orifice |
| Backpressure Tolerance | Conventional (limited) | Balanced bellows | Balanced bellows if backpressure variable |
| Thermal Relief | Individual TRVs | Shared relief headers | Individual TRVs simpler; shared may reduce count |
| Discharge Disposition | Atmospheric | Closed system | **TBD** - Per TM and environmental requirements |

### 4.2 Sizing Trade-offs

| Trade-off | Conservative | Optimized | Recommendation |
|-----------|--------------|-----------|----------------|
| Orifice Size | Next larger standard | Exact fit | Use next larger standard orifice (API 526) |
| Set Pressure | Lower (more margin) | Higher (max capacity) | Per TM standards; typically MAWP or below |
| Inlet Line Size | Larger (lower dP) | Smaller (cost) | Size to meet 3% rule with margin |

### 4.3 Risk Considerations

| Risk | Mitigation |
|------|------------|
| Missed relief scenarios | Systematic review of all equipment; validation with DEL-01.15 HAZOP and DEL-01.08 transient analysis |
| Incorrect fluid properties | Verify properties with DEL-01.01 DBM, DEL-01.07 hydraulic analysis, and DEL-01.09 datasheets |
| Inadequate inlet piping | Include piping dP in sizing (3% rule); iterate with piping discipline |
| Inadequate outlet piping | Verify built-up backpressure (10% limit for conventional PRVs); iterate with piping discipline |
| Late design changes | Plan for IFC update based on final vendor data and HAZOP |

---

## 5. Examples

### 5.1 Relief Calculation Structure (Typical)

```
1. Equipment/System Identification
   - Tag number, P&ID reference
   - Protected equipment description

2. Relief Scenarios
   - List all applicable scenarios
   - Identify governing scenario

3. Design Conditions
   - Design pressure, MAWP
   - Design temperature
   - Set pressure selection

4. Fluid Properties (at Relieving Conditions)
   - Density
   - Viscosity
   - Compressibility (if applicable)

5. Required Relieving Rate
   - Calculation methodology
   - Governing case flow rate

6. Orifice Sizing
   - API 520 calculation
   - Selected orifice designation

7. Inlet Piping Verification
   - Pressure drop calculation
   - 3% rule compliance

8. Outlet Piping Verification
   - Backpressure calculation
   - Built-up backpressure limits

9. Summary
   - Selected device specification
   - Key parameters
```

### 5.2 Typical PRV/TRV Data Summary Table

| Tag | Service | Set Pressure (kPag) | Orifice | Capacity (m3/h) | Inlet Size | Outlet Size | Notes |
|-----|---------|---------------------|---------|-----------------|------------|-------------|-------|
| **TBD** | **TBD** | **TBD** | **TBD** | **TBD** | **TBD** | **TBD** | |

### 5.3 Common Pitfalls to Avoid

- Forgetting to account for built-up backpressure in capacity calculation
- Using properties at wrong conditions (operating vs. relieving)
- Ignoring two-phase flow potential
- Undersizing inlet piping (causing chatter - violating 3% rule)
- Undersizing outlet piping (causing excessive backpressure - violating 10% rule)
- Not updating calculations for design changes from HAZOP or transient analysis

---

## 6. Additional Resources

### 6.1 Related Guidance Documents

| Document | Relevance |
|----------|-----------|
| DEL-01.07 Guidance | Hydraulic analysis provides operating pressures |
| DEL-01.08 Guidance | Transient analysis may identify surge scenarios |
| DEL-01.15 Guidance | HAZOP coordination |

### 6.2 Industry References

| Reference | Application |
|-----------|-------------|
| API 520 Part I | Sizing methodology |
| API 520 Part II | Installation requirements |
| API 521 | Relief scenarios and systems |
| CCPS Guidelines | Process safety considerations |

---

*End of Guidance*
