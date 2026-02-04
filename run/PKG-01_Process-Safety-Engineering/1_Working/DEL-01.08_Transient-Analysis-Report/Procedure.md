# Procedure: DEL-01.08 Transient Analysis Report

**Document ID:** DEL-01.08-PR
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Purpose

### 1.1 Procedure Intent

This procedure defines the step-by-step process for developing, reviewing, and finalizing the Transient Analysis Report for the Puget Sound Optimization (PSO) project. Following this procedure ensures systematic identification of transient scenarios, proper model development based on the validated steady-state model, and complete documentation of surge/waterhammer analysis results.

### 1.2 Applicability

This procedure applies to:
- FEED phase transient screening and preliminary analysis
- Detailed design phase comprehensive transient analysis
- All transient hydraulic analysis within PKG-01 scope
- Surge and waterhammer evaluation for the booster pump station and piping systems

---

## 2. Prerequisites

### 2.1 Required Inputs

| Input | Source | Status Required |
|-------|--------|-----------------|
| Process Design Basis | DEL-01.01 | Approved or IFR |
| Process Flow Diagrams | DEL-01.02 | IFR minimum |
| P&IDs | DEL-01.03 | IFR minimum |
| Equipment Sizing Calculations | DEL-01.04 | Required (pump data) |
| Line Sizing Calculations | DEL-01.05 | Required (pipe data) |
| Hydraulic Analysis | DEL-01.07 | Required (steady-state basis) |
| Pump Vendor Data | Vendors | Preferred (inertia, curves) |
| Valve Vendor Data | Vendors | Preferred (closure characteristics) |
| Control System Timing | PKG-07 | Required for valve timing |

### 2.2 Required Standards and References

| Document | Purpose |
|----------|---------|
| ASME B31.4 | Design pressure considerations |
| CSA Z662 | Pipeline transient requirements |
| API 1160 | System integrity management |
| AWWA M11 | Surge analysis guidance (reference) |
| CER Regulations | Canadian pipeline safety requirements |
| Title 49 CFR Part 195 | U.S. hazardous liquid pipeline regulations |

### 2.3 Required Tools

| Tool | Purpose |
|------|---------|
| Transient modeling software | AFT Impulse, PIPENET Transient, or Synergi Pipeline Simulator |
| Steady-state hydraulic model | Basis for transient model (from DEL-01.07) |
| Spreadsheet software | Supporting calculations |
| Physical property database | Fluid properties, wave speed calculation |

### 2.4 Personnel Requirements

| Role | Qualification |
|------|---------------|
| Transient Analysis Engineer | Transient/surge analysis experience |
| Technical Reviewer | Independent transient analysis review |
| Controls Engineer | Valve timing coordination (PKG-07) |

---

## 3. Steps

### 3.1 Phase 1: Preparation and Scenario Identification

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 1.1 | Review DEL-01.07 hydraulic analysis for system understanding | Transient Engineer | System understanding |
| 1.2 | Gather P&IDs (DEL-01.03) and identify all pumps, valves, check valves | Transient Engineer | Equipment list |
| 1.3 | Identify potential transient events (pump trip, valve closure, etc.) | Transient Engineer | Event list |
| 1.4 | Review DEL-01.15 HAZOP findings for transient scenarios | Transient Engineer | HAZOP input |
| 1.5 | Develop transient scenario matrix per datasheet Section 4.2 | Transient Engineer | Scenario matrix |
| 1.6 | Prioritize scenarios by severity/likelihood | Transient Engineer | Prioritized list |
| 1.7 | Define system boundaries for transient model | Transient Engineer | Boundary definition |

### 3.2 Phase 2: Data Gathering

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 2.1 | Obtain piping data from DEL-01.05 (lengths, diameters, wall thickness) | Transient Engineer | Piping database |
| 2.2 | Obtain pipe material properties (for wave speed) | Transient Engineer | Material data |
| 2.3 | Obtain pump data from DEL-01.04 and vendors (curves, inertia WR2) | Transient Engineer | Pump data |
| 2.4 | Obtain valve data (closure times, characteristics) | Transient Engineer | Valve data |
| 2.5 | Obtain check valve data (slam velocity limits) | Transient Engineer | Check valve data |
| 2.6 | Obtain fluid properties from DEL-01.01 (density, bulk modulus) | Transient Engineer | Fluid data |
| 2.7 | Calculate pressure wave speed for all pipes | Transient Engineer | Wave speed data |
| 2.8 | Coordinate with PKG-07 controls for valve timing | Transient Engineer | Valve timing data |

### 3.3 Phase 3: Model Development

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.1 | Set up transient model based on DEL-01.07 steady-state model | Transient Engineer | Base transient model |
| 3.2 | Input piping network with wave speed properties | Transient Engineer | Piping network |
| 3.3 | Input pump models with inertia and four-quadrant curves | Transient Engineer | Pump models |
| 3.4 | Input valve models with closure characteristics | Transient Engineer | Valve models |
| 3.5 | Input check valve models with closure dynamics | Transient Engineer | Check valve models |
| 3.6 | Define boundary conditions | Transient Engineer | Complete model |
| 3.7 | Validate transient model against DEL-01.07 steady-state | Transient Engineer | Validation record |
| 3.8 | Document model setup and assumptions | Transient Engineer | Model documentation |

### 3.4 Phase 4: Analysis Execution

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 4.1 | Run TS-01: Single pump trip scenario (base case) | Transient Engineer | TS-01 results |
| 4.2 | Run TS-02: All-pump trip scenario (power failure) | Transient Engineer | TS-02 results |
| 4.3 | Run TS-03: Pump startup scenarios | Transient Engineer | TS-03 results |
| 4.4 | Run TS-04: Sequential pump startup | Transient Engineer | TS-04 results |
| 4.5 | Run TS-05: Control valve closure scenarios | Transient Engineer | TS-05 results |
| 4.6 | Run TS-06: Check valve slam evaluation | Transient Engineer | TS-06 results |
| 4.7 | Run TS-07: VFD speed change transient | Transient Engineer | TS-07 results |
| 4.8 | Run TS-08: ESD valve closure (if applicable) | Transient Engineer | TS-08 results |
| 4.9 | Extract maximum pressure envelopes | Transient Engineer | Max pressure data |
| 4.10 | Extract minimum pressure envelopes | Transient Engineer | Min pressure data |
| 4.11 | Check for column separation potential | Transient Engineer | Cavitation check |
| 4.12 | Perform sensitivity analyses | Transient Engineer | Sensitivity results |

### 3.5 Phase 5: Mitigation Analysis (If Required)

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 5.1 | Evaluate if max/min pressures exceed limits per datasheet Section 3.4 | Transient Engineer | Limit assessment |
| 5.2 | Identify mitigation options (surge vessel, slow closure, etc.) | Transient Engineer | Mitigation options |
| 5.3 | Model mitigation measures | Transient Engineer | Mitigated model |
| 5.4 | Run mitigated scenarios | Transient Engineer | Mitigated results |
| 5.5 | Verify mitigation effectiveness | Transient Engineer | Verification |
| 5.6 | Document mitigation recommendations | Transient Engineer | Recommendations |

### 3.6 Phase 6: Documentation

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 6.1 | Prepare report outline per guidance document structure | Transient Engineer | Report outline |
| 6.2 | Write executive summary | Transient Engineer | Executive summary |
| 6.3 | Document methodology and model setup | Transient Engineer | Methodology section |
| 6.4 | Prepare pressure/flow vs. time plots | Transient Engineer | Time history plots |
| 6.5 | Prepare pressure envelope diagrams | Transient Engineer | Envelope plots |
| 6.6 | Document mitigation analysis (if applicable) | Transient Engineer | Mitigation section |
| 6.7 | Compile appendices (model outputs, time histories) | Transient Engineer | Appendices |
| 6.8 | Prepare conclusions and recommendations | Transient Engineer | Conclusions |

### 3.7 Phase 7: Review and Finalization

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 7.1 | Perform internal self-review | Transient Engineer | Self-review record |
| 7.2 | Independent technical review | Technical Reviewer | Review comments |
| 7.3 | Address review comments | Transient Engineer | Revised report |
| 7.4 | Cross-check with DEL-01.06 relief calculations | Transient Engineer | Cross-check record |
| 7.5 | Cross-check with DEL-01.13 operating envelopes | Transient Engineer | Cross-check record |
| 7.6 | Discipline lead approval | Discipline Lead | Approval |
| 7.7 | Submit for TM formal review | Lead Engineer | Transmittal |
| 7.8 | Address TM comments | Transient Engineer | Comment responses |
| 7.9 | Finalize and issue | Transient Engineer | Final report |

---

## 4. Verification

### 4.1 Model Verification Checklist

| Check Item | Verified | Date |
|------------|----------|------|
| Model matches DEL-01.07 steady-state at t=0 | [ ] | |
| Piping data correctly entered from DEL-01.05 | [ ] | |
| Wave speeds correctly calculated | [ ] | |
| Pump inertia values reasonable/verified | [ ] | |
| Valve closure times coordinated with PKG-07 | [ ] | |
| Check valve characteristics correct | [ ] | |
| Boundary conditions appropriate | [ ] | |
| Time step appropriate for wave speed | [ ] | |

### 4.2 Results Verification Checklist

| Check Item | Verified | Date |
|------------|----------|------|
| Max pressures below design pressure (with margin per ASME B31.4) | [ ] | |
| Min pressures above vapor pressure | [ ] | |
| No column separation predicted | [ ] | |
| Check valve reverse velocity within limits | [ ] | |
| All scenarios TS-01 through TS-08 analyzed | [ ] | |
| Sensitivity analysis completed | [ ] | |
| Mitigation effective (if required) | [ ] | |
| Results consistent with DEL-01.07 | [ ] | |

### 4.3 Approval Requirements

| Approval Stage | Approver | Signature |
|----------------|----------|-----------|
| Technical Review | Independent Engineer | Required |
| Discipline Review | Process Lead | Required |
| Client Review | TM Representative | Per contract |

---

## 5. Records

### 5.1 Deliverable Documents

| Document | Format | Retention |
|----------|--------|-----------|
| Transient Analysis Report | PDF | Project + 7 years |
| Model Files | Software native | Project + 7 years |
| Time History Data | Excel/CSV | Project + 7 years |
| Input Data Files | Excel | Project + 7 years |

### 5.2 Quality Records

| Record | Location | Retention |
|--------|----------|-----------|
| Vendor Data Records | Document Control | Project + 7 years |
| Technical Review Records | Document Control | Project + 7 years |
| Model Validation Records | Within report | Project + 7 years |
| Approval Signatures | Within document | Permanent |

### 5.3 Revision History

| Revision | Date | Description | By | Checked | Approved |
|----------|------|-------------|-----|---------|----------|
| Pass 1 | 2026-02-01 | Initial draft | **TBD** | **TBD** | **TBD** |
| Pass 2 | 2026-02-01 | Cross-reference check | **TBD** | **TBD** | **TBD** |
| A | **TBD** | IFR Issue | **TBD** | **TBD** | **TBD** |
| 0 | **TBD** | IFD Issue | **TBD** | **TBD** | **TBD** |
| 1 | **TBD** | IFC Issue | **TBD** | **TBD** | **TBD** |

---

*End of Procedure*
