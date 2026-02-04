# Datasheet: DEL-00.07 External Responsibility Matrix (ERM)

## Document Information
| Field | Value |
|-------|-------|
| Deliverable ID | DEL-00.07 |
| Deliverable Name | External Responsibility Matrix (ERM) |
| Parent Package | PKG-00 Project Management, QA/QC, Document Control & Regulatory Support |
| Document Type | Matrix |
| Revision | 0 (Initial Draft) |
| Status | INITIALIZED |
| Prepared By | 4_DOCUMENTS Sub-Agent (Type 2) |
| Date | 2026-02-01 |

## Purpose
The External Responsibility Matrix (ERM) defines responsibilities and interfaces among contractors and the TM project team for the PSO project. It clarifies who is responsible, accountable, consulted, and informed for key project activities and deliverables.

## Scope Alignment
| Source Reference | Requirement Summary |
|------------------|---------------------|
| SOW: Section 4.4.2.1-4.4.4.1 (p41) | Develop an External Responsibility Matrix (ERM) |
| Decomposition: SOW-0451 | Perform interface management including ERM development |
| Vocabulary Map | ERM = External Responsibility Matrix - Interface management artifact |

## Matrix Schema (ASSUMPTION - RACI Format)
| Column | Description | Data Type |
|--------|-------------|-----------|
| Activity/Deliverable ID | Unique identifier for activity or deliverable | String |
| Activity/Deliverable Name | Description of the activity or deliverable | String |
| Category | Grouping (e.g., Design, Procurement, Construction Support) | String |
| TM | Trans Mountain responsibility designation | R/A/C/I |
| Engineering Contractor | Engineering Contractor responsibility designation | R/A/C/I |
| MAC | Main Automation Contractor responsibility designation | R/A/C/I |
| Other Contractors | Other contractor responsibility designation | R/A/C/I |
| Regulatory Bodies | Regulatory authority involvement | C/I |
| Notes | Clarifications or special conditions | Text |

## RACI Legend
| Code | Meaning | Definition |
|------|---------|------------|
| R | Responsible | Performs the work / produces the deliverable |
| A | Accountable | Final authority / approval; only one per activity |
| C | Consulted | Provides input; two-way communication |
| I | Informed | Kept updated; one-way communication |

## Attributes
| Attribute | Value |
|-----------|-------|
| Format | Excel (.xlsx) with PDF export (ASSUMPTION) |
| Update Frequency | As interfaces change; formal revision at phase gates |
| Distribution | TM Project Team, Engineering Contractor, MAC, other contractors |
| Retention | Project duration + 7 years (TBD - per TM requirements) |

## Key Parties to Include
| Party | Abbreviation | Role |
|-------|--------------|------|
| Trans Mountain | TM | Owner/Operator, Project Sponsor |
| Engineering Contractor | EC | FEED and Detailed Design execution (ASSUMPTION) |
| Main Automation Contractor | MAC | ICSS coordination and supply (TBD - confirm scope) |
| Construction Contractor(s) | CC | Construction execution (TBD - not yet contracted) |
| Regulatory Bodies | REG | CER, BCSA, ABSA as applicable |
| Vendors/Suppliers | VND | Equipment and material suppliers |

## Activity Categories (ASSUMPTION)

### Engineering Activities
- Design Basis Development
- Discipline Engineering (Process, Piping, Mechanical, Civil, Electrical, I&C)
- HAZOP and Risk Assessments
- Design Reviews
- Document Preparation and Submission

### Procurement Activities
- Material Requisition Preparation
- Technical Bid Evaluation
- Vendor Document Review
- FAT Coordination

### Construction Support Activities
- Construction Work Package Development
- Constructability Reviews
- Field Engineering Support
- As-Built Documentation

### Project Management Activities
- Progress Reporting
- Interface Management
- Change Control
- Document Control

## Dependencies
- Upstream: DEL-00.05 Interface Management Plan
- Parallel: DEL-00.06 Interface Register & Schedule
- Downstream: All discipline deliverable packages

## Open Items / TBD
| Item | Description |
|------|-------------|
| TBD-01 | Confirm complete list of external parties |
| TBD-02 | Obtain TM template for ERM (if applicable) |
| TBD-03 | Clarify MAC boundaries and responsibilities |
| TBD-04 | Identify other contractors requiring inclusion |
| TBD-05 | Confirm procurement/supply split for fiber optic and ICSS |

## Source Citations
- Decomposition: `run/_Decomposition/Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md`
- SOW Reference: Exhibit A - Scope of Work PS.pdf, Section 4.4.2.1-4.4.4.1 (p41)
- Vocabulary Map: ERM definition
