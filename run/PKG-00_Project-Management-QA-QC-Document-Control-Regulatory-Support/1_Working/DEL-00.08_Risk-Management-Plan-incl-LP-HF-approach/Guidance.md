# Guidance: DEL-00.08 Risk Management Plan (incl LP/HF approach)

## Document Information
| Field | Value |
|-------|-------|
| Deliverable ID | DEL-00.08 |
| Deliverable Name | Risk Management Plan (incl LP/HF approach) |
| Revision | 0 (Initial Draft) |
| Status | INITIALIZED |
| Date | 2026-02-01 |

## 1. Overview
This guidance document provides direction for developing the Risk Management Plan for the PSO project. The plan establishes the framework for managing technical, safety, schedule, and other risks throughout FEED and Detailed Design phases.

## 2. Key Principles

### 2.1 Integrated Risk Approach
- Risk management, loss prevention, and human factors are interconnected
- Findings from one area inform the others
- All activities contribute to safe, operable, maintainable design

### 2.2 Proactive Risk Identification
- Identify risks early when mitigation options are most flexible
- Use multiple identification techniques (workshops, checklists, reviews)
- Engage all disciplines in risk identification

### 2.3 Action-Oriented Management
- Every identified risk requires an owner and a response plan
- Track actions to closure with documented evidence
- Escalate unresolved items appropriately

## 3. Risk Management Framework (ASSUMPTION)

### 3.1 Risk Categories
| Category | Description | Project-Specific Examples |
|----------|-------------|---------------------------|
| Technical | Design/engineering uncertainties | Pump sizing, hydraulic performance, blending accuracy |
| Schedule | Timeline threats | Long-lead equipment, permitting, MAC coordination |
| Cost | Budget impacts | Scope changes, market conditions, unknowns |
| Safety | Personnel and process safety | VS6 pump operation, VFD hazards, containment integrity |
| Regulatory | Compliance risks | CER requirements, BCSA/ABSA registration |
| Interface | Coordination failures | TM approvals, MAC integration, vendor data |

### 3.2 Risk Evaluation Matrix (ASSUMPTION)
| Likelihood | Rare (1) | Unlikely (2) | Possible (3) | Likely (4) | Almost Certain (5) |
|------------|----------|--------------|--------------|------------|-------------------|
| **Catastrophic (5)** | Medium | High | High | Extreme | Extreme |
| **Major (4)** | Medium | Medium | High | High | Extreme |
| **Moderate (3)** | Low | Medium | Medium | High | High |
| **Minor (2)** | Low | Low | Medium | Medium | Medium |
| **Insignificant (1)** | Low | Low | Low | Low | Medium |

### 3.3 Risk Response Strategies
| Strategy | Application | Example |
|----------|-------------|---------|
| Avoid | Eliminate the risk source | Change design approach |
| Mitigate | Reduce likelihood or consequence | Add redundancy, improve procedures |
| Transfer | Share risk with another party | Insurance, contractual allocation |
| Accept | Monitor without active mitigation | Low risks with acceptable exposure |

## 4. Loss Prevention Guidance

### 4.1 LP Review Focus Areas
| Area | Key Project Considerations |
|------|---------------------------|
| Process Safety | Hydrocarbon containment, pressure protection, emergency shutdown |
| Fire Protection | Area classification, detection systems, suppression capability |
| Spill Prevention | Secondary containment (new containment wall per SOW), leak detection |
| Mechanical Integrity | Pump reliability, valve integrity, piping corrosion protection |
| Emergency Response | Access routes, emergency equipment, communication systems |

### 4.2 LP Review Timing (ASSUMPTION)
| Design Stage | LP Review Focus |
|--------------|-----------------|
| FEED (IFR) | Hazard identification, preliminary safeguard assessment |
| 30% DD | Layout review, access assessment, initial LP recommendations |
| 60% DD | Detailed safeguard review, equipment spacing verification |
| 90% DD | Final LP compliance verification, outstanding item resolution |

### 4.3 LP Review Checklist Items (ASSUMPTION)
- [ ] Area classification drawings reviewed
- [ ] Fire protection coverage assessed
- [ ] Containment sizing verified
- [ ] Drainage systems adequate
- [ ] Emergency shutdown provisions confirmed
- [ ] Access/egress routes evaluated
- [ ] Equipment spacing meets standards

## 5. Human Factors Guidance

### 5.1 HF Review Focus Areas
| Area | Key Project Considerations |
|------|---------------------------|
| Operability | Control room interface, field operator tasks, startup/shutdown procedures |
| Maintainability | Access platforms, lifting provisions, tool clearances |
| Safety | Ergonomic hazards, noise exposure, lighting adequacy |
| Alarm Management | Alarm rationalization, operator response expectations |

### 5.2 HF Review Timing (ASSUMPTION)
| Design Stage | HF Review Focus |
|--------------|-----------------|
| FEED (IFR) | Control philosophy review, preliminary layout assessment |
| 30% DD | Operator task analysis, initial HF recommendations |
| 60% DD | Detailed operability review, maintenance access verification |
| 90% DD | Final HF compliance verification, alarm rationalization |

### 5.3 HF Review Checklist Items (ASSUMPTION)
- [ ] Control interface design assessed
- [ ] Field operator tasks analyzed
- [ ] Maintenance access provisions verified
- [ ] Valve handwheel accessibility confirmed
- [ ] Local displays and indicators visible
- [ ] Lighting levels adequate
- [ ] Noise levels acceptable

## 6. HAZOP Integration

### 6.1 HAZOP Coordination
- HAZOP is a key risk identification tool
- Results feed into risk register
- Action items tracked per this plan
- Final HAZOP report (DEL-01.15) demonstrates closeout

### 6.2 HAZOP Timing
| Phase | HAZOP Activity |
|-------|----------------|
| FEED | Initial HAZOP on preliminary P&IDs |
| Detailed Design | Update HAZOP with detailed design; close actions |
| Pre-IFC | Final HAZOP closeout verification |

## 7. Risk Register Management

### 7.1 Register Structure (ASSUMPTION)
| Field | Description |
|-------|-------------|
| Risk ID | Unique identifier |
| Category | Technical/Schedule/Cost/Safety/Regulatory/Interface |
| Description | Clear statement of the risk |
| Likelihood | Rating per matrix |
| Consequence | Rating per matrix |
| Risk Level | Calculated from likelihood x consequence |
| Owner | Person responsible for response |
| Response Strategy | Avoid/Mitigate/Transfer/Accept |
| Response Actions | Specific mitigation actions |
| Status | Open/In Progress/Closed |
| Target Date | Date for action completion |

### 7.2 Register Review Frequency
| Risk Level | Review Frequency |
|------------|------------------|
| Extreme | Weekly |
| High | Bi-weekly |
| Medium | Monthly |
| Low | Quarterly |

## 8. Coordination with Design Reviews

### 8.1 Integration Rationale
The Risk Management Plan integrates with the design review process (DEL-00.10) to ensure risk findings influence design decisions at critical milestones. This integration:
- Ensures design review packages include current risk status
- Allows design teams to respond to LP/HF findings before finalizing deliverables
- Provides TM with consolidated risk visibility at approval gates
- Tracks action closeout as a prerequisite for IFC issuance per SOW-0244

### 8.2 Coordination Activities
- Risk status presented at design review milestones (FEED IFR, 30/60/90% DD)
- LP/HF findings incorporated into design review packages (DEL-00.10)
- Action closeout tracked as design review prerequisite
- Risk register distributed with design review submittal packages

## 9. Source References
- Decomposition Document: SOW-0460, OBJ-007
- SOW: Section 4.5.1.1-4.5.1.17 (p42-43)
- SOW: Section 3.2.2.1 (p13) - Design modification incorporation
- Related: DEL-00.09 LP/HF Review Reports, DEL-01.15 HAZOP Final Report
