# Guidance: DEL-02.15 Support & Pipe Stress Execution Plan

## 1. Purpose

### 1.1 Document Intent
This guidance document provides practical direction for developing the Support & Pipe Stress Execution Plan for the PSO Project at Sumas Tank Farm. It addresses plan development considerations, critical line identification, and coordination requirements.

### 1.2 Target Audience
- Lead Stress Engineer
- Piping Lead Engineer
- Project Engineering Manager
- Discipline Leads (Structural, Mechanical)

### 1.3 Context
The Support & Pipe Stress Execution Plan establishes the framework for all stress analysis work on the PSO Project. It must be approved before stress analysis begins and serves as the governing document for methodology, criteria, and deliverables. Given the brownfield nature of the project and pump-intensive scope, the plan must address:
- Critical line identification for 5 new booster pumps
- Existing system verification requirements
- Interface with support structural design
- Schedule integration with piping design milestones

## 2. Principles

### 2.1 Core Principles

| Principle | Description |
|-----------|-------------|
| **Early Definition** | Plan must be issued before stress analysis begins to ensure consistent approach |
| **Code Compliance** | All methodology must comply with applicable codes (CSA Z662, ASME B31.3) |
| **Clarity** | Clear screening criteria to identify which lines require analysis |
| **Coordination** | Well-defined interfaces with Piping, Structural, Mechanical disciplines |
| **Scalability** | Appropriate level of analysis for each line category |

### 2.2 Plan Development Sequence

```
Project Kickoff
    |
    +-- Obtain TM Standards and Requirements
    |
    +-- Draft Execution Plan
    |       |
    |       +-- Define critical line criteria
    |       +-- Specify analysis methodology
    |       +-- Define load cases
    |       +-- Establish support philosophy
    |       +-- List deliverables
    |
    +-- Internal Review (Piping, Structural, Mechanical)
    |
    +-- Submit for TM Review
    |
    +-- Address TM Comments
    |
    +-- TM Approval
    |
    +-- Begin Stress Analysis per Plan
```

## 3. Considerations

### 3.1 Project-Specific Considerations (PSO)

| Factor | Consideration |
|--------|---------------|
| VS6 Booster Pumps | All 5 pump suction and discharge lines are stress-critical |
| 5x6 Manifold | Complex system requires full flexibility analysis |
| Brownfield Tie-Ins | Existing system verification per SOW-0240 |
| Crude Oil Service | Temperature variations with blend components |
| Cold Climate | Consider low ambient temperature effects |
| VFD Operation | Variable operating conditions may need multiple cases |

### 3.2 Critical Line Criteria Considerations

| Criterion | Guidance |
|----------|----------|
| Temperature | Set threshold based on material properties and expected temperature range |
| Pipe Size | NPS 12 is typical threshold; adjust based on TM requirements |
| Rotating Equipment | Include all pump and compressor connections |
| High Pressure | Consider stress implications of high-pressure systems |
| Tie-Ins | All tie-ins require analysis including existing system modeling |

### 3.3 Software and Methodology Considerations

| Topic | Consideration |
|-------|---------------|
| Software Selection | Confirm with TM if specific software is required |
| Code Selection | CSA Z662 for pipeline; ASME B31.3 for station piping |
| Friction Coefficients | Define standard values; note when slide plates used |
| Spring Selection | Define spring selection criteria if used |
| Modeling Extent | Define how far to model existing systems at tie-ins |

### 3.4 Interface Considerations

| Interface | Coordination Requirements |
|-----------|---------------------------|
| Piping Design | Routing input, support location coordination |
| Structural (PKG-04) | Support load transfer, anchor design |
| Mechanical (PKG-03) | Equipment nozzle allowables, thermal growth |
| Process (PKG-01) | Operating conditions, temperature cases |
| 3D Model (DEL-02.28) | Geometry extraction, model updates |

## 4. Trade-offs

### 4.1 Analysis Depth vs. Efficiency

| Approach | Pros | Cons | Recommendation |
|----------|------|------|----------------|
| Analyze All Lines | Complete coverage | Time-consuming, expensive | Not recommended |
| Strict Screening | Efficient, focused | May miss borderline cases | Preferred with conservative criteria |
| Engineering Judgment | Flexible | Inconsistent, risk of missing lines | Not recommended as sole criterion |

### 4.2 Screening Criteria Stringency

| Stringency | Pros | Cons | Guidance |
|------------|------|------|----------|
| Conservative (lower thresholds) | More lines analyzed, lower risk | More analysis effort | Recommended for critical systems |
| Liberal (higher thresholds) | Less analysis effort | Risk of missing stress issues | Not recommended for pump piping |

### 4.3 Support Philosophy Options

| Approach | Pros | Cons | When to Use |
|----------|------|------|-------------|
| Standard Supports | Consistent, familiar to construction | May not optimize for every case | Majority of supports |
| Engineered Supports | Optimized for specific loads | More engineering effort | High load locations |
| Variable Springs | Accommodates vertical movement | Higher cost, maintenance | Vertical runs with thermal movement |

## 5. Examples

### 5.1 Execution Plan Table of Contents Example

```
1. INTRODUCTION
   1.1 Purpose
   1.2 Scope
   1.3 Project Background

2. APPLICABLE CODES AND STANDARDS
   2.1 Primary Codes
   2.2 TM Standards
   2.3 Reference Documents

3. CRITICAL LINE CRITERIA
   3.1 Screening Criteria
   3.2 Critical Line List (Reference Appendix A)
   3.3 Non-Critical Line Treatment

4. ANALYSIS METHODOLOGY
   4.1 Software
   4.2 Modeling Approach
   4.3 Material Properties
   4.4 Operating Conditions
   4.5 Assumptions

5. LOAD CASES
   5.1 Sustained Loads
   5.2 Thermal Expansion
   5.3 Occasional Loads
   5.4 Test Conditions
   5.5 Load Combinations

6. SUPPORT DESIGN PHILOSOPHY
   6.1 Support Types
   6.2 Standard Support Details
   6.3 Support Spacing Guidelines
   6.4 Special Support Requirements

7. EXISTING SYSTEM VERIFICATION
   7.1 Tie-In Identification
   7.2 Modeling Approach
   7.3 Acceptance Criteria

8. DELIVERABLES
   8.1 Stress Analysis Reports
   8.2 Support Drawings
   8.3 Native Files

9. SCHEDULE
   9.1 Key Milestones
   9.2 Dependencies

10. INTERFACES
    10.1 Piping Design
    10.2 Structural Design
    10.3 Mechanical Equipment
    10.4 Process Engineering

11. QUALITY ASSURANCE
    11.1 Check Requirements
    11.2 Review Requirements
    11.3 Approval Requirements

APPENDIX A - Critical Line List
APPENDIX B - Support Standard Summary
APPENDIX C - Report Template
```

### 5.2 Critical Line Criteria Table Example

| Criterion | Threshold | Notes |
|-----------|-----------|-------|
| Operating Temperature | > 65C (150F) or < -30C (-20F) | Based on material allowable stress variation |
| Pipe Size | >= NPS 12 | Reduced flexibility requires analysis |
| Rotating Equipment | All pump S/D lines | API 610 nozzle load verification |
| Sensitive Equipment | All connections | Heat exchangers, vessels |
| Design Pressure | > 100 barg (TBD) | High-pressure stress effects |
| Jacketed Piping | All | Complex thermal behavior |
| Expansion Joints | All | Bellows or slip joints |
| Tie-Ins | All | Existing system verification required |
| Project-Designated | As specified | Lines identified during design |

### 5.3 Load Case Summary Example

| Case ID | Description | Temperature | Pressure | Wind | Seismic |
|---------|-------------|-------------|----------|------|---------|
| SUS | Weight + Pressure | Ambient | Design | - | - |
| OPE-1 | Operating Case 1 | 60C | Operating | - | - |
| OPE-2 | Operating Case 2 | 40C | Operating | - | - |
| OPE-3 | Operating Cold | -10C | Operating | - | - |
| EXP-1 | Expansion (OPE-1 to Ambient) | Range | - | - | - |
| EXP-2 | Expansion (OPE-2 to Ambient) | Range | - | - | - |
| EXP-3 | Expansion (OPE-3 to Ambient) | Range | - | - | - |
| OCC-W | Occasional - Wind | - | - | Design | - |
| OCC-S | Occasional - Seismic | - | - | - | OBE |
| HYD | Hydrotest | Ambient | Test | - | - |

### 5.4 Common Issues to Avoid

| Issue | Consequence | Prevention |
|-------|-------------|------------|
| Vague screening criteria | Inconsistent line selection | Define specific, measurable thresholds |
| Missing load cases | Non-compliant analysis | Cross-reference code requirements |
| Undefined interfaces | Coordination gaps | Document interface requirements clearly |
| Late plan approval | Delays stress analysis start | Submit plan early in project |
| No existing system approach | Inadequate tie-in verification | Include specific methodology per SOW-0240 |

---
*Document generated 2026-02-01 | Deliverable Status: OPEN*
