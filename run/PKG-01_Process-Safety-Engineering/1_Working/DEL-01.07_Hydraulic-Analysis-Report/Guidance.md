# Guidance: DEL-01.07 Hydraulic Analysis Report

**Document ID:** DEL-01.07-GD
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Purpose

### 1.1 Document Intent

This guidance document provides recommendations and best practices for developing the Hydraulic Analysis Report for the Puget Sound Optimization project. It supplements the formal specification with practical considerations for steady-state hydraulic analysis and coordination with the TM Puget system model.

### 1.2 Target Audience

- Process Engineers (lead and supporting)
- Hydraulic Analysts
- Pump Application Engineers
- Project Engineers
- TM Hydraulic Analyst (coordination)

---

## 2. Principles

### 2.1 Foundational Principles

| Principle | Description |
|-----------|-------------|
| System Integration | Model must integrate with existing TM Puget system model |
| Validation | Model setup must be validated against existing operational data where available |
| Completeness | Analyze all operating cases including turndown and off-design |
| Conservatism | Use conservative assumptions where data is uncertain |
| Traceability | Document all input data sources and assumptions |

### 2.2 Integration Principles

| Principle | Application |
|-----------|-------------|
| Early TM Coordination | Engage TM hydraulic analyst from project start |
| Iterative Refinement | Plan for model updates as design progresses (IFR -> IFD -> IFC) |
| Multi-disciplinary Input | Gather input from piping, mechanical, and controls disciplines |

---

## 3. Considerations

### 3.1 Technical Considerations

#### 3.1.1 System Boundaries

For the PSO hydraulic analysis, define boundaries carefully:
- **Upstream Boundary**: Tank suction connections (TK-101, TK-102)
- **Downstream Boundary**: Delivery point to Puget Sound Pipeline
- **Lateral Boundaries**: All process piping within PSO scope
- **Interface with TM Model**: Coordinate boundary conditions with TM Puget system model

**ASSUMPTION:** The PSO model will be integrated with or calibrated to the existing TM system-wide hydraulic model.

#### 3.1.2 Pump Modeling

For the 5 VS6-type booster pumps (2 large, 2 small, 1 medium):
- Obtain preliminary pump curves from vendor or use similar equipment data
- Model VFD capability for variable speed operation
- Verify NPSH available vs. required across operating range (minimum margin 1.0m above NPSHr)
- Consider pump combinations for different operating scenarios
- Target pump operating points within 70-110% of BEP (Best Efficiency Point)

**TIP:** Early pump vendor engagement helps obtain realistic performance curves for modeling.

#### 3.1.3 Blending System Modeling

Per SOW and DBM requirements:
- **Baseline Case**: Model 20%/80% Heavy/Light blend ratio (SOW-0005 baseline)
- **Extended Range**: Model 10%-100% NEAT component range (DBM requirement) - **TBD confirmation with TM**
- Account for different fluid properties for each component (density, viscosity, vapor pressure)
- Verify flow ratio control feasibility across operating range

**NOTE:** Confirm with TM whether all NEAT cases (100% Heavy, 100% Light) must be analyzed or if baseline blend is sufficient for initial design.

#### 3.1.4 Manifold Modeling

5x6 manifold per SOW (Note: DBM references 6x5 - **TBD confirmation with TM**):
- Model pressure drop through manifold headers
- Verify flow distribution capability
- Model isolation scenarios (pump out of service)
- Consider symmetry for flexible operation

**ACTION ITEM:** Resolve manifold configuration discrepancy between SOW (5x6) and DBM (6x5) before finalizing model.

### 3.2 Project Considerations

| Consideration | Recommendation |
|---------------|----------------|
| Reference Document | Use Appendix C (Draft PSO Hydraulic Report REV 0) as starting point |
| TM Coordination | Schedule regular coordination calls with TM hydraulic analyst |
| Design Iterations | Plan for model updates at 30/60/90% design stages (IFR/IFD/IFC) |
| Vendor Data | Identify long-lead vendor data requirements early (pump curves critical) |
| Software Selection | Select industry-standard hydraulic modeling software (**TBD** - coordinate with TM) |

### 3.3 Quality Considerations

| Aspect | Recommendation |
|--------|----------------|
| Model Validation | Compare to existing operational data if available |
| Sensitivity Analysis | Assess impact of uncertain parameters (fluid properties, roughness) |
| Independent Review | Have model reviewed by second hydraulic engineer |
| Documentation | Document all model setup decisions and assumptions |
| NPSH Verification | Verify all pumps meet NPSHa >= NPSHr + 1.0m minimum margin |

---

## 4. Trade-offs

### 4.1 Design Trade-offs

| Trade-off | Option A | Option B | Recommendation |
|-----------|----------|----------|----------------|
| Pipe Sizing | Larger (lower velocity, higher cost) | Smaller (higher velocity, lower cost) | Optimize per DEL-01.05 criteria |
| Pump Selection | Fewer large pumps | More smaller pumps | Per vendor optimization; balance flexibility vs. efficiency |
| Control Strategy | Throttling control | VFD speed control | VFD per SOW; model both for comparison |
| Manifold Design | Symmetric flow split | Optimized for specific cases | Symmetric for operational flexibility |

### 4.2 Modeling Trade-offs

| Trade-off | Simple | Detailed | Recommendation |
|-----------|--------|----------|----------------|
| Fluid Model | Single average fluid | Multi-component blending | Multi-component for blending analysis (6 cases) |
| Temperature Effects | Isothermal | Temperature-dependent | Include temperature effects on viscosity |
| Minor Losses | Approximate K-factors | Detailed fitting analysis | Detailed for critical paths (pump suction) |

### 4.3 Risk Considerations

| Risk | Mitigation |
|------|------------|
| Model mismatch with TM system | Early and regular TM coordination (per SOW-0130, SOW-0220) |
| Inaccurate fluid properties | Obtain TM fluid data; sensitivity analysis on density/viscosity |
| Pump curve uncertainty | Use vendor preliminary curves; update with certified data at IFD/IFC |
| Scope changes | Design model for easy modification; modular approach |
| Manifold configuration uncertainty | Resolve 5x6 vs. 6x5 discrepancy early |

---

## 5. Examples

### 5.1 Hydraulic Analysis Report Structure (Typical)

```
1. Executive Summary
   - Key findings
   - Flow rate capability confirmation (275,000/315,000 bpd)
   - Major recommendations

2. Introduction and Scope
   - Project overview
   - Analysis boundaries
   - Reference documents

3. System Description
   - Equipment summary (5 pumps, manifold, piping)
   - Piping configuration
   - Control philosophy

4. Methodology
   - Software description
   - Modeling approach
   - Assumptions

5. Input Data
   - Fluid properties (Heavy, Light, Blended)
   - Piping data
   - Equipment data
   - Boundary conditions (TM coordination)

6. Operating Cases
   - Case definitions (Cases 1-6 per Datasheet)
   - Results summary table

7. Detailed Results
   - Pressure profiles
   - Pump operating points (verify 70-110% BEP)
   - NPSH verification (NPSHa >= NPSHr + 1.0m)

8. Sensitivity Analysis
   - Key parameter variations
   - Impact assessment

9. Optimization Recommendations
   - Pipe sizing
   - Pump selection
   - Control strategy

10. Conclusions and Recommendations
    - Summary of findings
    - Action items

11. Appendices
    - Model input listings
    - Detailed output tables
    - Pump curves
```

### 5.2 Operating Case Matrix (Template)

| Case ID | Description | Flow Rate (m3/h) | Fluid | Pump Config | Notes |
|---------|-------------|------------------|-------|-------------|-------|
| Case 1 | Normal - Sustainable | 1,822 | Blended 20/80 | **TBD** | Baseline per SOW |
| Case 2 | Peak - Design | 2,100 | Blended 20/80 | **TBD** | Maximum per SOW |
| Case 3 | Minimum Turndown | **TBD** | Blended 20/80 | Single pump | Minimum flow |
| Case 4 | Tank-to-Tank Transfer | **TBD** | **TBD** | **TBD** | Per DBM |
| Case 5 | Heavy NEAT | **TBD** | Heavy 100% | **TBD** | Extended range per DBM |
| Case 6 | Light NEAT | **TBD** | Light 100% | **TBD** | Extended range per DBM |

**NOTE:** Confirm with TM which cases are critical for FEED vs. Detailed Design phases.

### 5.3 NPSH Verification Table (Example Format)

| Pump | Case | Flow (m3/h) | NPSHr (m) | NPSHa (m) | Margin (m) | Status |
|------|------|-------------|-----------|-----------|------------|--------|
| P-101 | 1 | **TBD** | **TBD** | **TBD** | **TBD** | **TBD** |
| P-101 | 2 | **TBD** | **TBD** | **TBD** | **TBD** | **TBD** |

**ACCEPTANCE:** NPSHa >= NPSHr + 1.0m minimum margin (or per pump vendor recommendation if more stringent)

### 5.4 Common Pitfalls to Avoid

- Not coordinating with TM hydraulic analyst early enough (SOW-0130 requires early coordination)
- Using outdated or incorrect fluid properties (obtain from TM/DBM)
- Ignoring off-design operating cases (all 6 cases must be analyzed)
- Not verifying NPSH for all pump combinations (critical for system reliability)
- Forgetting to account for future fouling/degradation (add margin to pressure drop)
- Inconsistent manifold configuration (resolve 5x6 vs. 6x5 discrepancy)
- Missing operating range verification (pump operating points outside 70-110% BEP)

---

## 6. Additional Resources

### 6.1 Related Guidance Documents

| Document | Relevance |
|----------|-----------|
| DEL-01.01 Guidance | DBM provides design basis including blend ratios and operating envelope |
| DEL-01.05 Guidance | Line sizing criteria for velocity limits |
| DEL-01.08 Guidance | Transient analysis builds on hydraulic model |

### 6.2 Industry References

| Reference | Application |
|-----------|-------------|
| API 610 | Pump application guidelines including operating range (70-110% BEP typical) |
| Hydraulic Institute Standards | NPSH margin requirements (1.0m minimum typical for hydrocarbon service) |
| Crane TP-410 | Pressure drop calculations and K-factors |
| Cameron Hydraulic Data | Reference data for fluid properties and calculations |

---

*End of Guidance*
