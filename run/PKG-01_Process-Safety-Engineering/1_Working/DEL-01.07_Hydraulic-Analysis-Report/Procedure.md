# Procedure: DEL-01.07 Hydraulic Analysis Report

**Document ID:** DEL-01.07-PR
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Purpose

### 1.1 Procedure Intent

This procedure defines the step-by-step process for developing, reviewing, and finalizing the Hydraulic Analysis Report for the Puget Sound Optimization (PSO) project. Following this procedure ensures systematic development of the steady-state hydraulic model, proper coordination with TM's Puget system model, and complete documentation of analysis results.

### 1.2 Applicability

This procedure applies to:
- FEED phase hydraulic model refinement (per SOW-0130)
- Detailed design phase model update to IFC status (per SOW-0220)
- All steady-state hydraulic analysis within PKG-01 scope
- Coordination with TM hydraulic analyst

---

## 2. Prerequisites

### 2.1 Required Inputs

| Input | Source | Status Required |
|-------|--------|-----------------|
| Process Design Basis | DEL-01.01 | Approved or IFR |
| Process Flow Diagrams | DEL-01.02 | IFR minimum |
| P&IDs | DEL-01.03 | IFR minimum |
| Equipment Sizing Calculations | DEL-01.04 | Concurrent acceptable |
| Line Sizing Calculations | DEL-01.05 | Concurrent acceptable |
| Reference Hydraulic Report | Appendix C (Draft REV 0) | Available |
| TM Puget System Model | TM | Access required |

### 2.2 Required Standards and References

| Document | Purpose |
|----------|---------|
| API 610 | Pump application including operating range (70-110% BEP) |
| Hydraulic Institute Standards | NPSH margin requirements (1.0m minimum), pump operating range |
| CSA Z662 | Pipeline design |
| ASME B31.4 | Piping design |
| Crane TP-410 | Pressure drop calculations (reference) |
| TM Standards | Project-specific requirements (**TBD**) |

### 2.3 Required Tools

| Tool | Purpose |
|------|---------|
| Hydraulic modeling software | **TBD** - Industry-standard software (coordinate with TM) |
| Pump curve digitization | Extracting vendor pump curves |
| Spreadsheet software | Supporting calculations |
| Physical property database | Fluid properties (Heavy, Light, Blended) |

### 2.4 Personnel Requirements

| Role | Qualification |
|------|---------------|
| Lead Process/Hydraulic Engineer | Hydraulic modeling experience |
| TM Hydraulic Analyst | Coordination role (TM side) |
| Technical Reviewer | Independent hydraulic review |

---

## 3. Steps

### 3.1 Phase 1: Preparation and Coordination

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 1.1 | Initiate coordination with TM hydraulic analyst (per SOW-0130) | Lead Engineer | Kickoff meeting |
| 1.2 | Obtain access to TM Puget system model (or boundary conditions) | Lead Engineer | Model access/data |
| 1.3 | Review Appendix C (Draft Hydraulic Report REV 0) | Hydraulic Engineer | Understanding of baseline |
| 1.4 | Gather current design documents (PFDs, P&IDs) | Hydraulic Engineer | Document set |
| 1.5 | Define system boundaries for PSO model | Hydraulic Engineer | Boundary definition |
| 1.6 | Establish coordination schedule with TM | Lead Engineer | Meeting schedule |
| 1.7 | Resolve manifold configuration (5x6 vs. 6x5) with TM | Lead Engineer | Configuration confirmation |
| 1.8 | Confirm operating case requirements (baseline vs. extended NEAT) | Lead Engineer | Case matrix confirmation |

### 3.2 Phase 2: Data Gathering

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 2.1 | Compile piping data (lengths, diameters, elevations) | Hydraulic Engineer | Piping database |
| 2.2 | Obtain pump performance curves (preliminary or vendor) | Hydraulic Engineer | Pump curves |
| 2.3 | Gather valve data (Cv, pressure drop characteristics) | Hydraulic Engineer | Valve data |
| 2.4 | Obtain fluid properties (density, viscosity, vapor pressure) for Heavy/Light/Blended | Hydraulic Engineer | Property data |
| 2.5 | Define operating cases per DBM and SOW (Cases 1-6) | Hydraulic Engineer | Case matrix |
| 2.6 | Confirm boundary conditions with TM | Hydraulic Engineer | Boundary conditions |

### 3.3 Phase 3: Model Development

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.1 | Set up hydraulic model with project-specific data | Hydraulic Engineer | Base model |
| 3.2 | Input piping network geometry | Hydraulic Engineer | Piping network |
| 3.3 | Input pump curves and configurations (5 pumps: 2L+2S+1M) | Hydraulic Engineer | Pump models |
| 3.4 | Input control valve characteristics | Hydraulic Engineer | Valve models |
| 3.5 | Define fluid property models (Heavy, Light, Blended) | Hydraulic Engineer | Fluid models |
| 3.6 | Apply boundary conditions (coordinated with TM) | Hydraulic Engineer | Complete model |
| 3.7 | Perform model validation checks | Hydraulic Engineer | Validation record |

### 3.4 Phase 4: Analysis Execution

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 4.1 | Run Case 1: Normal operation (1,822 m3/h, Blended 20/80) | Hydraulic Engineer | Case 1 results |
| 4.2 | Run Case 2: Peak operation (2,100 m3/h, Blended 20/80) | Hydraulic Engineer | Case 2 results |
| 4.3 | Run Case 3: Minimum turndown (Single pump, Blended 20/80) | Hydraulic Engineer | Case 3 results |
| 4.4 | Run Case 4: Tank-to-Tank Transfer | Hydraulic Engineer | Case 4 results |
| 4.5 | Run Case 5: Heavy NEAT (100% Heavy) | Hydraulic Engineer | Case 5 results |
| 4.6 | Run Case 6: Light NEAT (100% Light) | Hydraulic Engineer | Case 6 results |
| 4.7 | Verify NPSH available vs. required for all cases (NPSHa >= NPSHr + 1.0m) | Hydraulic Engineer | NPSH verification |
| 4.8 | Check pump operating points on curves (verify 70-110% BEP) | Hydraulic Engineer | Operating point plot |
| 4.9 | Verify line velocities within limits (per DEL-01.05 criteria) | Hydraulic Engineer | Velocity check |
| 4.10 | Perform sensitivity analyses on key parameters | Hydraulic Engineer | Sensitivity results |

### 3.5 Phase 5: Optimization (If Required)

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 5.1 | Identify optimization opportunities | Hydraulic Engineer | Optimization list |
| 5.2 | Evaluate pipe sizing alternatives | Hydraulic Engineer | Sizing analysis |
| 5.3 | Evaluate pump configuration alternatives | Hydraulic Engineer | Pump analysis |
| 5.4 | Coordinate optimization findings with TM | Hydraulic Engineer | TM coordination |
| 5.5 | Document optimization recommendations | Hydraulic Engineer | Recommendations |

### 3.6 Phase 6: Documentation

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 6.1 | Prepare report outline per guidance structure | Hydraulic Engineer | Report outline |
| 6.2 | Write executive summary | Hydraulic Engineer | Executive summary |
| 6.3 | Document methodology and assumptions | Hydraulic Engineer | Methodology section |
| 6.4 | Prepare results sections with figures/tables (all 6 cases) | Hydraulic Engineer | Results sections |
| 6.5 | Compile appendices (model outputs, input data) | Hydraulic Engineer | Appendices |
| 6.6 | Prepare conclusions and recommendations | Hydraulic Engineer | Conclusions |
| 6.7 | Verify all acceptance criteria documented (NPSHa, BEP range, flow rates) | Hydraulic Engineer | Criteria verification |

### 3.7 Phase 7: Review and Finalization

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 7.1 | Perform internal self-review | Hydraulic Engineer | Self-review record |
| 7.2 | Coordinate model review with TM hydraulic analyst (per SOW-0130) | Lead Engineer | TM coordination |
| 7.3 | Independent technical review | Technical Reviewer | Review comments |
| 7.4 | Address review comments | Hydraulic Engineer | Revised report |
| 7.5 | Discipline lead approval | Discipline Lead | Approval |
| 7.6 | Submit for TM formal review | Lead Engineer | Transmittal |
| 7.7 | Address TM comments | Hydraulic Engineer | Comment responses |
| 7.8 | Finalize and issue (IFR/IFD/IFC per SOW-0220) | Hydraulic Engineer | Final report |

---

## 4. Verification

### 4.1 Model Verification Checklist

| Check Item | Verified | Date |
|------------|----------|------|
| Model boundaries correctly defined | [ ] | |
| Piping data matches P&IDs and isometrics | [ ] | |
| Pump curves correctly entered (5 pumps: 2L+2S+1M) | [ ] | |
| Fluid properties appropriate for conditions (Heavy/Light/Blended) | [ ] | |
| Boundary conditions consistent with TM model | [ ] | |
| Mass balance verified (in = out) | [ ] | |
| Pressure drops reasonable | [ ] | |
| Convergence achieved for all cases (Cases 1-6) | [ ] | |
| Manifold configuration confirmed (5x6 per SOW) | [ ] | |

### 4.2 Results Verification Checklist

| Check Item | Verified | Date |
|------------|----------|------|
| Flow rate targets achieved (275,000/315,000 bpd) | [ ] | |
| NPSH margins adequate for all pumps (NPSHa >= NPSHr + 1.0m) | [ ] | |
| Pump operating points within acceptable range (70-110% BEP) | [ ] | |
| Line velocities within limits (per DEL-01.05) | [ ] | |
| Pressure profiles reasonable | [ ] | |
| Sensitivity results documented | [ ] | |
| All operating cases analyzed (Cases 1-6) | [ ] | |
| Blending capability verified (20/80 baseline, 10-100% NEAT extended) | [ ] | |

### 4.3 Approval Requirements

| Approval Stage | Approver | Signature |
|----------------|----------|-----------|
| Technical Review | Independent Engineer | Required |
| TM Coordination | TM Hydraulic Analyst | Required (per SOW-0130, SOW-0220) |
| Discipline Review | Process Lead | Required |
| Client Review | TM Representative | Per contract |

---

## 5. Records

### 5.1 Deliverable Documents

| Document | Format | Retention |
|----------|--------|-----------|
| Hydraulic Analysis Report | PDF | Project + 7 years |
| Model Files | Software native | Project + 7 years |
| Input Data Files | Excel | Project + 7 years |
| Model Output Files | Software native | Project + 7 years |

### 5.2 Quality Records

| Record | Location | Retention |
|--------|----------|-----------|
| TM Coordination Records | Document Control | Project + 7 years |
| Technical Review Records | Document Control | Project + 7 years |
| Model Validation Records | Within report | Project + 7 years |
| Approval Signatures | Within document | Permanent |

### 5.3 Revision History

| Revision | Date | Description | By | Checked | Approved |
|----------|------|-------------|-----|---------|----------|
| Pass 1 | 2026-02-01 | Initial draft | **TBD** | **TBD** | **TBD** |
| Pass 2 | 2026-02-01 | Cross-reference consistency check | **TBD** | **TBD** | **TBD** |
| A | **TBD** | IFR Issue | **TBD** | **TBD** | **TBD** |
| 0 | **TBD** | IFD Issue | **TBD** | **TBD** | **TBD** |
| 1 | **TBD** | IFC Issue (per SOW-0220) | **TBD** | **TBD** | **TBD** |

---

*End of Procedure*
