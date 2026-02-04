# Procedure: DEL-00.07 External Responsibility Matrix (ERM)

## Document Information
| Field | Value |
|-------|-------|
| Deliverable ID | DEL-00.07 |
| Deliverable Name | External Responsibility Matrix (ERM) |
| Revision | 0 (Initial Draft) |
| Status | INITIALIZED |
| Date | 2026-02-01 |

## 1. Purpose
This procedure defines the steps for developing, approving, and maintaining the External Responsibility Matrix (ERM) throughout the PSO project.

## 2. Scope
Applies to defining responsibilities among:
- Trans Mountain (TM)
- Engineering Contractor (EC)
- Main Automation Contractor (MAC)
- Other contractors and vendors
- Regulatory bodies (as applicable)

## 3. Responsibilities

| Role | Responsibilities |
|------|------------------|
| Interface Coordinator | Develop and maintain ERM; facilitate reviews |
| Project Manager | Review ERM; coordinate with parties; approve EC-controlled sections |
| TM Project Lead | Approve final ERM; resolve disputes |
| Discipline Leads | Confirm discipline-specific responsibility assignments |
| MAC Coordinator | Confirm MAC-related responsibility assignments |

## 4. Procedure Steps

### 4.1 ERM Development
| Step | Action | Responsible | Output | Verifies Req |
|------|--------|-------------|--------|--------------|
| 4.1.1 | Obtain or create ERM template per TM requirements | Interface Coordinator | Blank ERM template | SPEC-07.20, SPEC-07.22 |
| 4.1.2 | Identify all external parties from SOW and contracts | Interface Coordinator | Party list | SPEC-07.01, SPEC-07.02, SPEC-07.03 |
| 4.1.3 | List all major activities requiring external coordination | Interface Coordinator + Discipline Leads | Activity list | SPEC-07.04, SPEC-07.10-07.15 |
| 4.1.4 | Assign initial RACI designations based on SOW | Interface Coordinator | Draft ERM | SPEC-07.05 |
| 4.1.5 | Verify each activity has exactly one Accountable party | Interface Coordinator | Validation record | SPEC-07.06 |
| 4.1.6 | Circulate draft to all parties for review | Interface Coordinator | Review comments | SPEC-07.40 |
| 4.1.7 | Conduct ERM review meeting to resolve conflicts | Project Manager | Meeting minutes | SPEC-07.42 |
| 4.1.8 | Incorporate agreed changes | Interface Coordinator | Revised ERM | SPEC-07.40 |
| 4.1.9 | Submit to TM for approval | Project Manager | Submission record | SPEC-07.41 |
| 4.1.10 | Incorporate TM comments and obtain final approval | Interface Coordinator | Approved ERM | SPEC-07.41 |

### 4.2 ERM Approval Workflow
| Step | Action | Responsible | Approval Level |
|------|--------|-------------|----------------|
| 4.2.1 | Verify all parties have reviewed | Interface Coordinator | N/A |
| 4.2.2 | Confirm no unresolved conflicts | Project Manager | Internal |
| 4.2.3 | EC Project Manager approval | EC Project Manager | EC Internal |
| 4.2.4 | TM Project Lead approval | TM Project Lead | TM Final |
| 4.2.5 | Distribute approved ERM | Interface Coordinator | N/A |

### 4.3 ERM Implementation
| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 4.3.1 | Communicate ERM to all project team members | Interface Coordinator | Distribution record |
| 4.3.2 | Post ERM to project document control system | Interface Coordinator | EDMS record |
| 4.3.3 | Reference ERM in kick-off meetings | Project Manager | Meeting record |
| 4.3.4 | Use ERM to assign interface owners | Interface Coordinator | Interface Register updates |

### 4.4 ERM Maintenance
| Step | Action | Responsible | Trigger | Verifies Req |
|------|--------|-------------|---------|--------------|
| 4.4.1 | Identify need for ERM update | Any team member | Change in scope/parties | SPEC-07.30 |
| 4.4.2 | Propose change to Interface Coordinator | Originator | Change request | SPEC-07.31 |
| 4.4.3 | Assess impact and affected parties | Interface Coordinator | Impact assessment | SPEC-07.30 |
| 4.4.4 | Circulate proposed change to affected parties | Interface Coordinator | Review request | SPEC-07.40 |
| 4.4.5 | Obtain agreement from affected parties | Interface Coordinator | Agreement record | SPEC-07.40 |
| 4.4.6 | Update ERM and issue new revision | Interface Coordinator | Revised ERM | SPEC-07.31 |
| 4.4.7 | Obtain approval per 4.2 workflow | Project Manager | Approved revision | SPEC-07.31 |
| 4.4.8 | Distribute updated ERM | Interface Coordinator | Distribution record | SPEC-07.21 |

### 4.5 Dispute Resolution
| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 4.5.1 | Document disputed responsibility assignment | Interface Coordinator | Dispute record |
| 4.5.2 | Convene meeting of affected parties | Project Manager | Meeting invitation |
| 4.5.3 | Present positions and seek resolution | Project Manager | Meeting minutes |
| 4.5.4 | Escalate unresolved disputes to TM | Project Manager | Escalation record |
| 4.5.5 | TM decision is final | TM Project Lead | Decision record |
| 4.5.6 | Update ERM per resolution | Interface Coordinator | Updated ERM |

## 5. Requirement Verification Matrix

| Req ID | Requirement | Verification Method | Procedure Step(s) |
|--------|-------------|---------------------|-------------------|
| SPEC-07.01 | TM-EC interface responsibilities defined | Review | 4.1.2, 4.1.4 |
| SPEC-07.02 | MAC interface responsibilities defined | Review | 4.1.2, 4.1.4 |
| SPEC-07.03 | Other contractor responsibilities defined | Review | 4.1.2, 4.1.4 |
| SPEC-07.04 | Cover FEED and DD phases | Review | 4.1.3 |
| SPEC-07.05 | Use standardized responsibility coding | Review | 4.1.4 |
| SPEC-07.06 | One Accountable party per activity | Review | 4.1.5 |
| SPEC-07.10 | Cover engineering deliverables | Review | 4.1.3 |
| SPEC-07.11 | Cover document control | Review | 4.1.3 |
| SPEC-07.12 | Cover procurement support | Review | 4.1.3 |
| SPEC-07.13 | Cover regulatory support | Review | 4.1.3 |
| SPEC-07.14 | Cover construction support | Review | 4.1.3 |
| SPEC-07.15 | Cover ICSS/automation coordination | Review | 4.1.3 |
| SPEC-07.20 | Maintained in controlled format | Inspection | 4.1.1 |
| SPEC-07.21 | Support PDF export | Demonstration | 4.1.1 |
| SPEC-07.22 | Compatible with TM EDMS | Inspection | 4.1.1 |
| SPEC-07.30 | Update when responsibilities change | Review | 4.4.1, 4.4.3 |
| SPEC-07.31 | Revisions formally controlled | Review | 4.4.2, 4.4.6, 4.4.7 |
| SPEC-07.32 | Review at phase transitions | Review | 6.2 |
| SPEC-07.40 | Assignments confirmed with parties | Review | 4.1.6, 4.1.8, 4.4.4, 4.4.5 |
| SPEC-07.41 | TM review prior to implementation | Review | 4.1.9, 4.1.10 |
| SPEC-07.42 | Conflicts/gaps identified and resolved | Review | 4.1.7, 4.5.1-4.5.6 |

## 6. Review Schedule

| Review Point | Scope | Responsible | Verifies Req |
|--------------|-------|-------------|--------------|
| Project Kick-off | Initial ERM development and approval | Interface Coordinator | All |
| End of FEED | Review for Detailed Design phase | Project Manager | SPEC-07.32 |
| Quarterly | Routine check for updates needed | Interface Coordinator | SPEC-07.30 |
| Contract Changes | Review affected responsibilities | Project Manager | SPEC-07.30 |
| New Party Addition | Add party and assign responsibilities | Interface Coordinator | SPEC-07.03 |

## 7. Records
| Record | Retention | Location |
|--------|-----------|----------|
| ERM (current approved version) | Active throughout project | Project document control |
| ERM (superseded revisions) | Project duration + 7 years (TBD) | Archive |
| Review/approval records | Project duration + 7 years (TBD) | Project document control |
| Dispute resolution records | Project duration + 7 years (TBD) | Project document control |

## 8. Related Documents
| Document | Relationship |
|----------|--------------|
| DEL-00.05 Interface Management Plan | Governing plan for ERM use |
| DEL-00.06 Interface Register & Schedule | Uses ERM for owner assignments |
| SOW Exhibit A | Contractual basis for responsibilities |
| MAC Contract | Defines MAC responsibilities (TBD reference) |

## 9. Revision History
| Rev | Date | Description | Author |
|-----|------|-------------|--------|
| 0 | 2026-02-01 | Initial draft | 4_DOCUMENTS Sub-Agent |
