# Guidance: DEL-00.13 Systems Completion Plan

**Document ID:** DEL-00.13-GD
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** Draft - Pending Review

---

## 1. Purpose

### 1.1 Document Intent

This guidance document provides practical direction for developing the Systems Completion Plan for the Puget Sound Optimization Project (PSO). It supplements the formal Specification by offering context, best practices, and recommendations for effective systems completion planning.

### 1.2 Audience

- Project management team
- Systems completion / commissioning personnel
- Engineering discipline leads
- Construction management
- TM project team

---

## 2. Principles

### 2.1 Core Principles

| Principle | Description |
|-----------|-------------|
| **System-Based Approach** | Organize completion around systems, not areas or disciplines |
| **Sequential Logic** | Define logical sequence that supports safe startup |
| **Clear Boundaries** | Establish unambiguous system boundaries |
| **Traceability** | Ensure completion status is traceable and verifiable |
| **Integration** | Align with construction, commissioning, and operations |

### 2.2 Guiding Philosophy

The Systems Completion Plan establishes the framework for transitioning from construction to operations. It ensures:
- Systems are completed in a logical sequence
- Engineering support is available when needed
- Turnover documentation is complete and organized
- Performance testing confirms design intent
- Handover to operations is smooth and well-documented

---

## 3. Considerations

### 3.1 System Definition Considerations

| Consideration | Guidance |
|---------------|----------|
| **System Boundaries** | Define clear boundaries between systems. Use P&IDs and other design documents as basis. Avoid overlapping boundaries. (See Specification SCP-C-002) |
| **Sub-Systems** | Break large systems into sub-systems where logical. This enables phased completion and turnover. |
| **Utility Interdependencies** | Identify utility systems required by other systems. Ensure utilities are commissioned first. |
| **PSO Systems** | For PSO at Sumas, key systems include: booster pumps, manifold piping, electrical systems, instrumentation/controls, civil/structural, fire protection (**ASSUMPTION**). (See Section 5.2 for sample system list) |

### 3.2 Completion Sequence Considerations

| Consideration | Guidance |
|---------------|----------|
| **Safety Systems First** | Complete safety-related systems (fire protection, emergency shutdown) before others (See Specification SCP-C-003) |
| **Utilities Before Users** | Complete power, control air, and other utilities before systems that depend on them |
| **Construction Constraints** | Align completion sequence with construction progress and access (See Specification SCP-C-010 for schedule alignment) |
| **Commissioning Windows** | Consider weather, operations constraints, and pipeline schedule |

### 3.3 Engineering Support Considerations

| Consideration | Guidance |
|---------------|----------|
| **Field Engineering** | Plan for engineering presence during construction completion to resolve queries (See Specification SCP-C-006) |
| **As-Built Verification** | Engineer verification of as-built conditions per SOW requirements (SOW-0472, Section 4.8.1, p44) |
| **Change Resolution** | Process for resolving field changes and queries |
| **Commissioning Support** | Engineering support during commissioning activities (See Specification SCP-F-002) |

---

## 4. Trade-offs

### 4.1 System Granularity

| Option | Advantages | Disadvantages |
|--------|------------|---------------|
| **Large Systems** (fewer turnover packages) | Simpler administration; fewer interfaces | Longer completion time; less flexible |
| **Small Sub-Systems** (more turnover packages) | Phased turnover; flexible | More administrative burden; more interfaces |

**Recommendation:** Use a moderate number of systems aligned with functional groupings. For PSO, **ASSUMPTION:** 5-10 main systems with sub-systems as needed.

### 4.2 Turnover Package Content

| Option | Advantages | Disadvantages |
|--------|------------|---------------|
| **Comprehensive Packages** | Self-contained; complete record | Larger; longer to compile |
| **Reference-Based Packages** | Smaller; references existing documents | Requires document control; references may change |

**Recommendation:** Use reference-based approach with mandatory attachment of critical documents (e.g., test records, punch lists). Include complete documents in FD Package.

### 4.3 Timing of Plan Development

| Option | Advantages | Disadvantages |
|--------|------------|---------------|
| **Early Development** (during FEED) | Shapes design for completion; long lead time | May require significant revisions |
| **Later Development** (during DD) | Better design basis; fewer revisions | Less time to prepare; may miss optimization |

**Recommendation:** Develop draft plan during FEED; finalize during Detailed Design with confirmed system boundaries and sequence.

---

## 5. Examples

### 5.1 Sample Plan Structure

| Section | Content |
|---------|---------|
| 1. Introduction | Purpose, scope, references |
| 2. Definitions | Terms, abbreviations, system/sub-system definitions |
| 3. Systems Completion Philosophy | Overall approach, phases, milestones |
| 4. System List and Boundaries | Table of systems with boundary descriptions |
| 5. Completion Sequence | Sequence logic, dependencies, schedule alignment |
| 6. Turnover Package Requirements | Package content, format, approval process |
| 7. Engineering Support | Scope, resources, field engineering approach |
| 8. Performance Testing | Testing approach, criteria, acceptance |
| 9. Punch List Management | Categorization, closure process |
| 10. Roles and Responsibilities | RACI matrix |
| Appendices | System boundary drawings, templates, checklists |

### 5.2 Sample System List for PSO (**ASSUMPTION**)

| System ID | System Name | Description |
|-----------|-------------|-------------|
| SYS-001 | Booster Pump System | Five booster pumps with VFDs, flow meters, discharge piping |
| SYS-002 | Manifold System | 5x6 manifold header and associated valves |
| SYS-003 | Electrical Power | Power distribution, MCC, VFDs, lighting |
| SYS-004 | Instrumentation & Controls | Instruments, PLCs, HMI, communication |
| SYS-005 | Fire Protection | Fire water supply, detection, suppression |
| SYS-006 | Civil/Structural | Foundations, containment wall, paving |
| SYS-007 | Auxiliary Systems | Sump, reinjection, dewatering |

### 5.3 Sample Turnover Package Content (**ASSUMPTION**)

| Category | Documents |
|----------|-----------|
| Design | P&IDs (as-built), equipment datasheets, drawings |
| Construction | Weld maps, NDE records, test records, redlines |
| Pre-Commissioning | Cleaning records, leak test records, loop checks |
| Commissioning | Function test records, interlock tests |
| Punch List | Category A (closed), Category B (deferred with approval) |
| O&M | Vendor manuals, spare parts, O&M binder reference |

---

## 6. Common Pitfalls

| Pitfall | Prevention Strategy |
|---------|---------------------|
| **Unclear System Boundaries** | Use P&IDs to define; document boundaries explicitly (Specification SCP-C-002) |
| **Sequence Conflicts** | Model dependencies; validate with construction (Specification SCP-C-003) |
| **Missing Engineering Support** | Plan resources early; align with project schedule (Specification SCP-C-006) |
| **Incomplete Turnover Packages** | Use checklists; verify completeness before turnover (Specification SCP-C-005) |
| **Late Performance Testing Planning** | Define testing approach early; confirm criteria with TM (Specification SCP-C-007, SCP-F-003) |
| **Punch List Backlog** | Establish clear categorization; enforce closure timelines (Specification SCP-C-008) |

---

## 7. Integration Points

### 7.1 Relationship to CMR (DEL-00.11)

- CMR (Completion Management Report) is prepared per the Systems Completion Plan approach
- CMR confirms completion status for sites/areas prior to work
- Plan defines how CMRs integrate into overall completion process
- Reference: Datasheet Section 5.2 (Related Deliverables)

### 7.2 Relationship to O&M Binders (DEL-00.15)

- O&M (Operation & Maintenance) Binders are part of turnover package content
- Plan defines O&M binder requirements for each system
- O&M Binders support operations readiness
- Reference: Datasheet Section 5.2 (Related Deliverables); Section 5.3 (sample turnover package content)

### 7.3 Relationship to FD Package (DEL-00.16)

- FD (Final Documentation) Package compiles final documentation across all systems
- Plan defines documentation requirements that feed FD Package
- Turnover packages become inputs to FD Package
- Reference: Datasheet Section 5.2 (Related Deliverables)

---

## 8. Notes and Assumptions

1. **ASSUMPTION:** Systems Completion Plan format to be developed by contractor.
2. **ASSUMPTION:** System list for PSO includes 5-10 main systems at Sumas Tank Farm.
3. **TBD:** TM turnover package requirements and acceptance criteria.
4. **TBD:** Performance testing scope and criteria (ref: OI-008).
5. **TBD:** Commissioning dossier content requirements.

---

*Generated: Pass 2 - Cross-Reference Check*
*Source: PSO Decomposition REVISED v2, SOW Sections 4.8.1 (p44), 4.8.2 (p45), Industry Best Practices*
*Cross-referenced with Datasheet, Specification, and Procedure documents*
