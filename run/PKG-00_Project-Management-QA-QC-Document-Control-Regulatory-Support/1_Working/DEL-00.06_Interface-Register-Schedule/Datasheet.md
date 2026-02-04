# Datasheet: DEL-00.06 Interface Register & Schedule

## Document Information
| Field | Value |
|-------|-------|
| Deliverable ID | DEL-00.06 |
| Deliverable Name | Interface Register & Schedule |
| Parent Package | PKG-00 Project Management, QA/QC, Document Control & Regulatory Support |
| Document Type | Register |
| Revision | 0 (Initial Draft) |
| Status | INITIALIZED |
| Prepared By | 4_DOCUMENTS Sub-Agent (Type 2) |
| Date | 2026-02-01 |

## Purpose
The Interface Register & Schedule captures all project interfaces, their owners, due dates, and resolution status. It supports SOW-0451 requirements for interface management across the PSO project at Sumas Tank Farm.

## Scope Alignment
| Source Reference | Requirement Summary |
|------------------|---------------------|
| SOW: Section 4.4.2.1-4.4.4.1 (p41) | Prepare/maintain/implement interface plans/procedures/registers/schedules |
| Decomposition: SOW-0451 | Perform interface management (external + internal) |

## Register Schema (ASSUMPTION)
| Column | Description | Data Type |
|--------|-------------|-----------|
| Interface ID | Unique identifier (e.g., INT-001) | String |
| Interface Name | Descriptive name of the interface | String |
| Interface Type | Internal / External | Enum |
| Discipline A | First discipline/party involved | String |
| Discipline B | Second discipline/party involved | String |
| Interface Owner | Person/role responsible for interface resolution | String |
| Description | Detailed description of the interface point | Text |
| Related Deliverables | Associated DEL-xx.yy IDs | String (comma-separated) |
| Due Date | Date by which interface must be resolved | Date |
| Status | Open / In Progress / Closed | Enum |
| Resolution Notes | Notes on how interface was resolved | Text |
| Last Updated | Date of last update | Date |

## Attributes
| Attribute | Value |
|-----------|-------|
| Format | Excel (.xlsx) with PDF export (ASSUMPTION) |
| Update Frequency | Weekly minimum during active phases (ASSUMPTION) |
| Distribution | TM Project Team, Engineering Contractor leads, authorized interface-related parties |
| Retention | Project duration + 7 years (TBD - per TM requirements) |

## Dependencies
- Upstream: DEL-00.05 Interface Management Plan (defines procedures for register use)
- Downstream: ERM (DEL-00.07), Design Review Packages (DEL-00.10)
- Related: DEL-00.04 Design Change Control Log (changes may trigger new interfaces), DEL-00.08 Risk Management Plan (critical interfaces may warrant risk entries)

## Key Interfaces to Track (ASSUMPTION - Initial Categories)
| Category | Example Interfaces |
|----------|-------------------|
| TM / Engineering Contractor | Design basis clarifications, drawing approvals, specification confirmations |
| Engineering Contractor / MAC | ICSS integration, control philosophy alignment, network architecture |
| Discipline-to-Discipline | Process-to-Piping (P&IDs), Electrical-to-I&C (cable schedules), Civil-to-Piping (pipe supports) |
| Engineering / Construction | Constructability reviews, CWP handoffs, pre-fabrication coordination |
| Vendor Interfaces | Equipment data integration, FAT witnessing, documentation turnover |

## Open Items / TBD
| Item | Description |
|------|-------------|
| TBD-01 | TM template for interface register (if applicable) - confirm format requirements |
| TBD-02 | Specific interface categories required by TM - validate proposed categories (TEC, ORG, SCH, PHY) |
| TBD-03 | Integration with TM project tracking systems - clarify data exchange requirements |
| TBD-04 | Escalation thresholds and procedures - confirm with TM Project Lead |
| TBD-05 | Access control mechanism for authorized interface-related parties - specify technical implementation |

## Source Citations
- Decomposition: `run/_Decomposition/Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md`
- SOW Reference: Exhibit A - Scope of Work PS.pdf, Section 4.4.2.1-4.4.4.1 (p41)
