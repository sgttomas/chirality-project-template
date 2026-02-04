# Guidance: DEL-00.07 External Responsibility Matrix (ERM)

## Document Information
| Field | Value |
|-------|-------|
| Deliverable ID | DEL-00.07 |
| Deliverable Name | External Responsibility Matrix (ERM) |
| Revision | 0 (Initial Draft) |
| Status | INITIALIZED |
| Date | 2026-02-01 |

## 1. Overview
This guidance document provides direction for developing and maintaining the External Responsibility Matrix (ERM) for the PSO project. The ERM is a key interface management artifact that clarifies responsibilities among all external project parties.

## 2. Key Principles

### 2.1 Purpose and Value
The ERM serves multiple critical functions:
- **Clarity**: Eliminates ambiguity about who does what (Rationale for SPEC-07.01-07.03)
- **Accountability**: Ensures one decision-maker per activity (Rationale for SPEC-07.06)
- **Coordination**: Facilitates communication across party boundaries (Rationale for SPEC-07.04)
- **Risk reduction**: Prevents work falling between organizational gaps (Rationale for SPEC-07.42)

### 2.2 RACI Framework (ASSUMPTION - Rationale for SPEC-07.05)
The ERM uses the RACI framework to define responsibilities:

| Role | Definition | Guidelines | Rationale |
|------|------------|------------|-----------|
| **Responsible (R)** | Performs the work | Can be multiple parties; at least one required | Identifies who executes the work |
| **Accountable (A)** | Final decision authority | Only one party per activity; cannot be delegated | Prevents decision paralysis (SPEC-07.06) |
| **Consulted (C)** | Provides input before action | Two-way communication required | Ensures expertise informs decisions |
| **Informed (I)** | Notified after action | One-way communication; kept in the loop | Maintains situational awareness |

### 2.3 Coverage Completeness (Rationale for SPEC-07.10-07.15)
The ERM must cover all key project activity domains to be effective:
- **Engineering deliverables** (SPEC-07.10): Core technical work product responsibilities
- **Document control** (SPEC-07.11): Information management across parties
- **Procurement support** (SPEC-07.12): Material/equipment acquisition responsibilities
- **Regulatory support** (SPEC-07.13): Compliance and submission responsibilities
- **Construction support** (SPEC-07.14): Field execution interface responsibilities
- **ICSS/automation coordination** (SPEC-07.15): Control system interface responsibilities

Coverage principles:
- All external interfaces should be captured
- Avoid gaps where no party is accountable
- Avoid overlaps where accountability is unclear
- Consider the full project lifecycle (FEED, DD, Construction Support)

### 2.4 Granularity Balance
- Activities should be granular enough to avoid ambiguity
- Activities should be high-level enough to be manageable
- Group similar activities where responsibilities are identical

### 2.5 Format and Maintenance (Rationale for SPEC-07.20-07.22, SPEC-07.30-07.32)
**Controlled format** (SPEC-07.20): ERM must be revisable as project evolves
**PDF export capability** (SPEC-07.21): Enables distribution to parties without edit access
**EDMS compatibility** (SPEC-07.22): Integrates with TM document management system
**Change-driven updates** (SPEC-07.30): ERM stays current with actual project organization
**Formal revision control** (SPEC-07.31): Prevents unauthorized or undocumented changes
**Phase transition reviews** (SPEC-07.32): Responsibilities often shift between FEED and DD phases

### 2.6 Quality and Validation (Rationale for SPEC-07.40-07.42)
**Party confirmation** (SPEC-07.40): Each party must agree to their assigned responsibilities before ERM is finalized; prevents disputes about "who agreed to what"
**TM review and approval** (SPEC-07.41): Owner has final authority on responsibility assignments
**Conflict resolution** (SPEC-07.42): Proactive identification and resolution of responsibility gaps or overlaps prevents downstream execution issues

## 3. Party Identification

### 3.1 Primary Parties
| Party | Abbreviation | Typical Role |
|-------|--------------|--------------|
| Trans Mountain | TM | Owner/Operator; typically Accountable for approvals |
| Engineering Contractor | EC | Typically Responsible for engineering deliverables (ASSUMPTION) |
| Main Automation Contractor | MAC | Responsible for ICSS; Consulted on I&C design (TBD - confirm scope) |

### 3.2 Secondary Parties (ASSUMPTION)
| Party | Abbreviation | Typical Role |
|-------|--------------|--------------|
| Construction Contractor(s) | CC | Responsible for construction; Consulted on constructability (TBD - not yet contracted) |
| Vendors/Suppliers | VND | Responsible for equipment supply; Consulted on integration |
| Regulatory Bodies | REG | Informed of submissions; Consulted on requirements |

## 4. Activity Categorization (ASSUMPTION - Example assignments)

### 4.1 Engineering Activities
| Activity | TM | EC | MAC | Notes |
|----------|----|----|-----|-------|
| Design Basis Development | A | R | C | TM approves; EC develops (ASSUMPTION) |
| Discipline Engineering | A | R | C* | *MAC consulted for I&C (ASSUMPTION) |
| P&ID Development | A | R | C | MAC consulted for control loops (ASSUMPTION) |
| Equipment Selection | A | R | I | TM approval required (ASSUMPTION) |
| HAZOP Facilitation | A | R | C | All disciplines participate (ASSUMPTION) |

### 4.2 Document Control Activities (ASSUMPTION - Example assignments)
| Activity | TM | EC | MAC | Notes |
|----------|----|----|-----|-------|
| MDR Maintenance | A | R | C | EC maintains; TM approves (ASSUMPTION) |
| Document Numbering | A | R | I | Per TM system (ASSUMPTION) |
| Revision Control | A | R | I | EC manages; TM approves (ASSUMPTION) |
| EDMS Upload | A | R | I | EC submits; TM manages system (ASSUMPTION) |

### 4.3 Procurement Support Activities (ASSUMPTION - Example assignments)
| Activity | TM | EC | MAC | Notes |
|----------|----|----|-----|-------|
| Material Requisition Prep | A | R | C* | *MAC for ICSS items (ASSUMPTION) |
| Technical Bid Evaluation | A | R | C | TM makes final decision (ASSUMPTION) |
| Vendor Document Review | A | R | C | EC reviews; TM approves (ASSUMPTION) |
| FAT Witnessing | A | R/C | R* | *MAC for ICSS; EC for others (ASSUMPTION) |

### 4.4 ICSS/Automation Activities (ASSUMPTION - Example assignments)
| Activity | TM | EC | MAC | Notes |
|----------|----|----|-----|-------|
| Control Philosophy | A | C | R | MAC leads; EC provides process input (TBD - confirm scope) |
| ICSS Configuration | A | C | R | MAC executes; EC provides requirements (TBD - confirm scope) |
| Network Architecture | A | C | R | MAC leads; TM IT consulted (TBD - confirm scope) |
| I&C Deliverables | A | R | C | EC develops; MAC coordinates (ASSUMPTION) |

## 5. Development Process

### 5.1 Initial Development
1. Identify all external parties from SOW and contracts
2. List all major project activities requiring external coordination
3. Assign initial RACI designations based on SOW requirements
4. Review with each party for confirmation
5. Resolve conflicts and gaps
6. Obtain TM approval

### 5.2 Validation Checklist
- [ ] Every activity has exactly one "A"
- [ ] Every activity has at least one "R"
- [ ] No row is empty
- [ ] No party has excessive workload
- [ ] Assignments align with contractual obligations
- [ ] All parties have reviewed and agreed

## 6. Common Pitfalls to Avoid

| Pitfall | Consequence | Prevention |
|---------|-------------|------------|
| Multiple Accountable parties | Unclear decision authority | Enforce single "A" rule |
| No Responsible party | Work not completed | Ensure at least one "R" |
| Over-assignment of "C" | Meeting overload | Limit "C" to those who truly need input |
| Under-assignment of "I" | Stakeholders uninformed | Review communication needs |
| Static matrix | Becomes outdated | Schedule periodic reviews |

## 7. Coordination with Other Deliverables

| Related Deliverable | Coordination Point |
|---------------------|-------------------|
| DEL-00.05 Interface Management Plan | ERM implements plan's responsibility assignments |
| DEL-00.06 Interface Register & Schedule | Interface owners should align with ERM "R" designations |
| DEL-00.01 MDR | Document responsibilities defined in ERM |
| All discipline packages | Deliverable responsibilities defined in ERM |

## 8. Revision Triggers
- New contractor or party added to project
- Contract modification changing responsibilities
- Phase transition (FEED to Detailed Design)
- Significant scope change
- Resolution of interface issues revealing gaps

## 9. Conflict Table (for human ruling)

| Conflict ID | Conflict | Source A | Source B | Impacted Sections | Proposed Authority | Human Ruling |
|-------------|----------|----------|----------|-------------------|-------------------|--------------|
| ERM-C01 | MAC scope and responsibilities unclear | Datasheet: "ICSS coordination and supply (TBD)" | Guidance Section 4.4: Multiple MAC-led activities assumed | Datasheet Key Parties, Guidance 4.4, all ICSS activity assignments | PROPOSAL: Obtain MAC contract or SOW to confirm actual scope | TBD |
| ERM-C02 | Construction Contractor not yet identified | Datasheet: "Construction execution (TBD - not yet contracted)" | Procedure requires CC involvement in reviews | All documents reference CC roles | PROPOSAL: Leave as TBD until CC is contracted; interim ERM excludes CC column | TBD |
| ERM-C03 | Document retention period unconfirmed | Datasheet: "Project duration + 7 years (TBD - per TM requirements)" | N/A | Datasheet Attributes, Procedure Records section | PROPOSAL: Confirm with TM document control standards | TBD |

## 10. Source References
- Decomposition Document: SOW-0451
- SOW: Section 4.4.2.1-4.4.4.1 (p41)
- Related: DEL-00.05 Interface Management Plan, DEL-00.06 Interface Register
