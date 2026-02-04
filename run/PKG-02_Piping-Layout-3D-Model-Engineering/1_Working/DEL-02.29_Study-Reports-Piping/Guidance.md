# Guidance: DEL-02.29 Study Report(s) (Piping)

## Purpose

### Intent
Piping Study Reports provide documented technical analysis and recommendations for specific design challenges encountered during detailed design. This guidance ensures studies are conducted systematically, documented consistently, and lead to actionable recommendations.

### Context
Studies are triggered by specific design issues requiring investigation beyond routine design calculations. Common triggers include HAZOP actions, design review findings, unusual operating conditions, constructability concerns, or TM requests. Studies differ from routine calculations in that they evaluate alternatives, assess risks, and provide recommendations.

### Stakeholders
| Stakeholder | Interest |
|-------------|----------|
| Lead Piping Engineer | Study sponsorship, approval, recommendation implementation |
| Piping Engineers | Study authorship, technical content |
| Stress Engineers | Flexibility and support studies |
| Materials Engineers | Material selection studies |
| Construction | Constructability study input and review |
| TM Operations | Operational impact assessment |
| Client (TM) | Study approval, recommendation acceptance |

## Principles

### Core Principles
| Principle | Description |
|-----------|-------------|
| **Objective Clarity** | Each study must have a clearly defined objective and scope |
| **Technical Rigor** | Analysis must be thorough, defensible, and based on sound engineering |
| **Actionable Recommendations** | Conclusions must lead to practical, implementable actions |
| **Traceability** | All data sources, assumptions, and references documented |
| **Timeliness** | Studies completed in time to inform design decisions |

### Study Report Structure
```
1. Executive Summary
   - Key findings and recommendations (1 page max)

2. Introduction
   2.1 Background
   2.2 Study Objective
   2.3 Scope and Limitations

3. Methodology
   3.1 Approach
   3.2 Tools and Methods
   3.3 Assumptions

4. Input Data
   4.1 Design Data
   4.2 Process Conditions
   4.3 Reference Documents

5. Analysis
   5.1 [Analysis sections per methodology]
   5.2 Alternative Evaluation (if applicable)

6. Results
   6.1 Findings
   6.2 Comparison of Alternatives

7. Discussion
   7.1 Interpretation
   7.2 Limitations
   7.3 Sensitivity

8. Conclusions

9. Recommendations
   9.1 Recommended Actions
   9.2 Implementation Considerations

10. References

Appendices
   A. Calculations
   B. Supporting Data
   C. Drawings/Figures
```

## Considerations

### Project-Specific Considerations
| Consideration | Details |
|---------------|---------|
| **Brownfield Environment** | Studies may address tie-in methodology and existing system impacts |
| **High Flow Rates** | 315,000 bpd peak may require flexibility/thermal expansion studies |
| **Blending Service** | Heavy/Light crude blending considerations for material and flow |
| **Booster Pump Piping** | Pump nozzle loads, flexibility at pump connections |
| **Manifold Complexity** | 5x6 manifold may require operability and constructability studies |
| **Existing Conditions** | Studies involving existing systems require field verification |

### Technical Considerations
| Topic | Guidance |
|-------|----------|
| **Study Triggers** | HAZOP actions, design review findings, unusual conditions, TM requests, code interpretation questions |
| **Data Currency** | Use latest approved design data; note data freeze date in study |
| **Assumptions** | Document all assumptions clearly; flag for verification if critical |
| **Sensitivity Analysis** | Consider sensitivity for critical parameters affecting conclusions |
| **Alternatives Evaluation** | Evaluate alternatives where multiple solutions exist |
| **Risk Assessment** | Consider risk implications of recommendations |

### Coordination Requirements
| Requirement | Details |
|-------------|---------|
| Process Engineering | Coordinate for operating conditions, upset scenarios |
| Stress Engineering | Coordinate for flexibility concerns, support requirements |
| Mechanical Engineering | Coordinate for equipment constraints, nozzle loads |
| Construction | Coordinate for constructability studies, sequencing |
| Operations (TM) | Coordinate for operational impacts, maintainability |

## Trade-offs

### Study Depth vs. Schedule
| Approach | Advantages | Disadvantages | Application |
|----------|------------|---------------|-------------|
| Comprehensive Study | Thorough, defensible, covers edge cases | Time-consuming, may delay design | High consequence decisions |
| Focused Study | Quick, targeted, timely | May miss related issues | Low-to-medium consequence |
| Phased Study | Progressive detail, early input | Requires clear stopping points | Complex issues with schedule constraints |

**Recommendation**: Match study depth to consequence level and decision timeline.

### Report Format Trade-offs
| Trade-off | Recommendation |
|-----------|----------------|
| Length vs. Clarity | Prefer concise; use appendices for detailed calculations |
| Standalone vs. Referenced | Standalone for TM review; may reference other docs for internal |
| Multiple studies vs. Combined | Separate if scopes distinct; combine if closely interrelated |
| Formal vs. Technical Memo | Formal report for TM-reviewed studies; memo for internal-only |

## Examples

### Common Piping Study Types for PSO

| Study Type | Typical Trigger | Key Content |
|------------|-----------------|-------------|
| **Flexibility Study** | High temperature differential, long runs | Expansion analysis, loop sizing, spring supports |
| **Tie-In Methodology** | Brownfield connections | Isolation approach, hot tap vs. cold cut, risk assessment |
| **Constructability Study** | Complex routing, access constraints | Sequencing, access, lift plans, spool sizing |
| **Support Optimization** | Stress resolution, cost reduction | Support count reduction, standardization |
| **Material Selection** | Corrosion/erosion concern | Material options, life-cycle cost, compatibility |
| **Valve Operability** | Access concerns | Handwheel clearance, platform requirements |

### Sample Study Outline: Tie-In Methodology Study

```
1. Executive Summary
   - 12 tie-in points identified
   - Recommended: 8 cold cut, 4 hot tap
   - Key risk: Existing line condition at TI-003

2. Introduction
   2.1 Background: PSO project requires connection to existing
       Sumas Tank Farm piping systems
   2.2 Objective: Define safe, efficient tie-in methodology
       for each connection point
   2.3 Scope: 12 identified tie-in points per drawing XYZ

3. Methodology
   3.1 Review existing system data (drawings, condition)
   3.2 Assess isolation options for each tie-in
   3.3 Evaluate hot tap vs. cold cut suitability
   3.4 Risk assessment per tie-in location

4. Input Data
   4.1 Existing system P&IDs and isometrics
   4.2 Operating conditions per process data
   4.3 Valve and isolation locations

5. Analysis
   5.1 Tie-in point characterization
   5.2 Isolation capability assessment
   5.3 Hot tap suitability evaluation
   5.4 Risk assessment results

6. Results
   - Summary table: method per tie-in point
   - Equipment requirements
   - Outage requirements

7. Conclusions
   - Cold cut suitable for 8 of 12 tie-ins
   - Hot tap required for 4 tie-ins in continuous service lines

8. Recommendations
   - Proceed with cold cut for TI-001, 002, 004-009
   - Procure hot tap equipment for TI-003, 010-012
   - Conduct NDE on existing piping at TI-003

Appendices
   A. Tie-in point data sheets
   B. Risk assessment matrices
   C. Existing system drawings
```

### Common Issues to Avoid
1. Undefined study objective leading to scope creep
2. Using outdated design data without noting data freeze date
3. Undocumented assumptions that affect conclusions
4. Conclusions not clearly supported by analysis
5. Recommendations without implementation path or responsibility
6. Missing peer review before issue
7. No tracking of recommendation implementation
8. Study closed without confirming recommendations implemented

---
*Generated by 4_DOCUMENTS Agent - 2026-02-01*
