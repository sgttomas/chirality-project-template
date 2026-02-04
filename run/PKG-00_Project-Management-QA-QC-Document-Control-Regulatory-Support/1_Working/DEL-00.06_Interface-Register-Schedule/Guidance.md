# Guidance: DEL-00.06 Interface Register & Schedule

## Document Information
| Field | Value |
|-------|-------|
| Deliverable ID | DEL-00.06 |
| Deliverable Name | Interface Register & Schedule |
| Revision | 0 (Initial Draft) |
| Status | INITIALIZED |
| Date | 2026-02-01 |

## 1. Overview
This guidance document provides direction for developing and maintaining the Interface Register & Schedule throughout the PSO project lifecycle. The register is a companion document to the Interface Management Plan (DEL-00.05) and provides the working mechanism for tracking interface resolution.

## 2. Key Principles

### 2.1 Interface Identification
- Interfaces should be identified early and captured promptly
- Consider all touchpoints: technical, organizational, schedule, and physical
- Engage discipline leads to identify discipline-specific interfaces
- Review design basis documents and P&IDs for physical interfaces

### 2.2 Interface Categorization (ASSUMPTION)
| Category | Description | Examples |
|----------|-------------|----------|
| Technical | Engineering data/design exchanges | Process data to I&C, equipment loads to structural |
| Organizational | Coordination between parties | TM approvals, MAC coordination, vendor interactions |
| Schedule | Timing dependencies | Long-lead procurement, construction sequencing |
| Physical | Tie-ins and connections | Existing systems, utilities, adjacent facilities |

### 2.3 Priority and Risk Assessment (ASSUMPTION)
| Priority | Criteria | Response |
|----------|----------|----------|
| Critical | Schedule-impacting or safety-related | Weekly tracking, escalation if delayed |
| High | Could impact deliverable quality | Bi-weekly tracking |
| Medium | Standard coordination | Monthly tracking |
| Low | Administrative or informational | As needed |

## 3. Register Population Guidance

### 3.1 Initial Population
1. Review SOW and decomposition for contractual interfaces
2. Review design basis documents for technical interfaces
3. Conduct discipline lead workshop to capture known interfaces
4. Review similar project registers (if available) for common interfaces

### 3.2 Ongoing Maintenance
- Update register at minimum weekly during active phases (see Specification SPEC-06.30)
- Review open interfaces at project coordination meetings
- Add new interfaces as identified through design development
- Close interfaces only when resolution is documented (see Procedure Section 4.4)
- Log all changes with date and modifier per Specification SPEC-06.31

### 3.3 Interface Naming Convention (ASSUMPTION - see Specification SPEC-06.13)
```
INT-[Category]-[Sequential Number]
Example: INT-TEC-001 (first technical interface)
Categories: TEC (Technical), ORG (Organizational), SCH (Schedule), PHY (Physical)
```
Note: This naming convention should be formalized in the Interface Management Plan (DEL-00.05) and confirmed with TM prior to implementation.

## 4. Coordination with Other Deliverables

| Related Deliverable | Coordination Point |
|---------------------|-------------------|
| DEL-00.05 Interface Management Plan | Procedures governing register use |
| DEL-00.07 External Responsibility Matrix (ERM) | Responsibility assignments inform interface owners |
| DEL-00.08 Risk Management Plan | Critical interfaces may warrant risk register entries |
| DEL-00.10 Design Review Packages | Interface status reported at design reviews |

## 5. Common Interfaces for PSO Project (ASSUMPTION)

### 5.1 TM / Engineering Contractor Interfaces
- Design basis clarifications and approvals
- TMP Standards and Specifications interpretations
- Drawing and document review cycles
- Schedule and progress reporting
- Regulatory submission support

### 5.2 MAC Coordination Interfaces
- ICSS requirements and configuration
- Control philosophy alignment
- Network architecture integration
- Hardware/software interface specifications
- FAT and SAT coordination

### 5.3 Discipline Interfaces
- Process to Piping: P&IDs, line list, equipment data
- Piping to Structural: Pipe supports, loads, routing
- Electrical to I&C: Cable schedules, JB allocations
- Civil to Piping: Underground routing, foundations
- All disciplines to 3D Model: Model updates and clash resolution

### 5.4 Vendor Interfaces
- Equipment data integration into design
- Documentation requirements specification
- FAT witnessing arrangements
- As-built documentation turnover

## 6. Escalation Guidance (ASSUMPTION)
| Condition | Escalation Level | Timeframe |
|-----------|-----------------|-----------|
| Interface overdue < 1 week | Discipline Lead | Immediate |
| Interface overdue 1-2 weeks | Project Manager | Within 2 days |
| Interface overdue > 2 weeks | TM Project Lead | Within 1 day |
| Critical interface at risk | Project Manager + TM | Immediate |

## 7. Quality Considerations
- Ensure consistency in interface descriptions
- Verify owner assignments with responsible parties
- Align due dates with project schedule milestones
- Document resolution rationale for closed interfaces
- Maintain revision history for auditable trail

## 8. Source References
- Decomposition Document: SOW-0451
- SOW: Section 4.4.2.1-4.4.4.1 (p41)
- Related: DEL-00.05 Interface Management Plan
