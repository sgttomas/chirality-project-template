# Guidance: DEL-00.02 Document & Tag Numbering Instruction Plan

**Document ID:** DEL-00.02-GD
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** Draft - Pending Review

---

## 1. Purpose

### 1.1 Document Intent

This guidance document provides practical direction for developing and implementing the Document & Tag Numbering Instruction Plan for the Puget Sound Optimization Project (PSO). It supplements the formal Specification by offering context, best practices, and recommendations for effective implementation.

### 1.2 Audience

- Document Control personnel
- Engineering leads and discipline managers
- Instrumentation and controls engineers
- Piping engineers
- All personnel creating deliverables

---

## 2. Principles

### 2.1 Core Principles

| Principle | Description |
|-----------|-------------|
| **Uniqueness** | Every number must be unique within its domain to prevent confusion |
| **Consistency** | Follow established patterns to enable intuitive identification |
| **Traceability** | Numbers must support tracking from design through construction and operation |
| **Integration** | Numbers must work with TM systems (EDMS, asset databases, control systems) |
| **Clarity** | Numbers should be self-describing where practical |

### 2.2 Guiding Philosophy

A well-designed numbering system is foundational to project success. It enables:
- Efficient document retrieval and management
- Clear asset identification throughout lifecycle
- Seamless integration with owner systems
- Reduced errors in fabrication, installation, and operation

---

## 3. Considerations

### 3.1 Document Numbering Considerations

| Consideration | Guidance |
|---------------|----------|
| **TM Conventions First** | Always start with TM-provided conventions; do not invent new structures. |
| **Project Identifier** | Include project code (e.g., "2500" or "PSO") in document numbers. |
| **Discipline Codes** | Use standard discipline codes (e.g., PROC, PIPE, ELEC, INST, CIVL). |
| **Document Type Codes** | Use codes identifying document type (e.g., PFD, P&ID, SLD, ISO, CAL). |
| **Sequential Numbers** | Use sequential numbers within categories; reserve blocks for disciplines. |
| **Revision Numbering** | Define clear revision numbering (e.g., Rev 0, Rev A, Rev 1) per TM convention. |
| **EDMS Compatibility** | Ensure document numbering structure aligns with TM EDMS metadata fields. |

### 3.2 Equipment Tag Considerations

| Consideration | Guidance |
|---------------|----------|
| **Existing Patterns** | Review existing Sumas Terminal tags to maintain consistency. |
| **Type Identification** | Include equipment type code (e.g., P for pump, V for vessel, TK for tank). |
| **Area/Unit Codes** | Consider area or unit codes if applicable to the site layout. |
| **Sequence Numbers** | Use meaningful sequences that group related equipment. |
| **Avoid Conflicts** | Check against existing asset database before assigning new tags. |
| **Asset Database Compatibility** | Ensure equipment tag structure is compatible with TM asset database fields and formats. |

### 3.3 Instrument Tag Considerations

| Consideration | Guidance |
|---------------|----------|
| **ISA-5.1 Compliance** | Follow ISA-5.1 unless TM specifies different convention. |
| **Measured Variable** | First letters indicate measured variable (e.g., P=Pressure, F=Flow, L=Level). |
| **Function Letters** | Subsequent letters indicate function (e.g., I=Indicator, T=Transmitter, C=Controller). |
| **Loop Numbers** | Use loop numbers consistent with control system requirements. |
| **Suffix Conventions** | Define conventions for redundant instruments, elements, etc. |
| **Control System Compatibility** | Ensure instrument tags are compatible with control system configuration and point naming. |

### 3.4 Line Numbering Considerations

| Consideration | Guidance |
|---------------|----------|
| **Existing Patterns** | Maintain consistency with existing site line numbering. |
| **Service Codes** | Use service codes indicating fluid type (e.g., OIL, WAT, AIR). |
| **Size Indication** | Include nominal pipe size in the number. |
| **Material Class** | Reference piping material class specification. |
| **Area/System** | Consider including area or system identifier. |
| **P&ID and LDT Consistency** | Ensure line numbering is consistent with P&ID and Line Designation Table (LDT) conventions. |

---

## 4. Trade-offs

### 4.1 Descriptive vs. Simple Numbers

| Option | Advantages | Disadvantages |
|--------|------------|---------------|
| **Highly Descriptive** (embedded codes for type, area, discipline) | Self-describing; easy identification | Longer; more complex to assign |
| **Simple Sequential** | Short; easy to assign | Requires lookup to understand meaning |

**Recommendation:** Follow TM convention; if discretion allowed, prefer descriptive approach for equipment/instrument tags.

### 4.2 Centralized vs. Distributed Number Assignment

| Option | Advantages | Disadvantages |
|--------|------------|---------------|
| **Centralized** (Document Control assigns all) | Guaranteed uniqueness; controlled | Potential bottleneck |
| **Distributed** (Disciplines self-assign from blocks) | Faster; distributed workload | Risk of conflicts; requires block management |

**Recommendation:** Use centralized approach for TM-assigned numbers; distributed block allocation for contractor-managed numbers.

---

## 5. Examples

### 5.1 Document Number Structure Example (**ASSUMPTION**)

```
[Project]-[Discipline]-[Type]-[Sequence]
Example: 2500-PROC-PFD-001
         2500-PIPE-ISO-001
         2500-ELEC-SLD-001
```

### 5.2 Equipment Tag Structure Example (**ASSUMPTION**)

```
[Type][Area/Unit]-[Sequence]
Example: P-201 (Pump in Unit 2, Sequence 01)
         TK-102 (Tank, Sequence 102)
         VS6-001 (VS6 Pump, Sequence 001)
```

### 5.3 Instrument Tag Structure Example (ISA-5.1 Based)

```
[Measured Variable + Function]-[Loop Number]
Example: FIT-2001 (Flow Indicating Transmitter, Loop 2001)
         PT-2002 (Pressure Transmitter, Loop 2002)
         LIC-2003 (Level Indicating Controller, Loop 2003)
```

### 5.4 Line Number Structure Example (**ASSUMPTION**)

```
[Size]-[Service]-[Sequence]-[Class]
Example: 12-OIL-001-A1A
         6-WAT-001-B2
```

---

## 6. Common Pitfalls

| Pitfall | Prevention Strategy |
|---------|---------------------|
| **Duplicate Numbers** | Implement central registry; validate before assignment |
| **Conflicts with Existing** | Obtain existing tag inventory from TM before starting |
| **Inconsistent Application** | Train all personnel; publish clear examples |
| **Changing Conventions Mid-Project** | Lock conventions early; manage changes through formal process |
| **Ignoring TM Requirements** | Engage TM Document Control early; get approval before use |

---

## 7. Notes and Assumptions

1. **ASSUMPTION:** Examples shown are illustrative; actual conventions per TM requirements.
2. **ASSUMPTION:** ISA-5.1 applies for instrument tagging unless TM specifies otherwise.
3. **TBD:** TM-specific numbering conventions not yet provided.
4. **TBD:** Existing site tag inventory not yet available for conflict checking.

---

*Generated: Pass 2 - Cross-Reference Consistency Check*
*Source: PSO Decomposition REVISED v2, Industry Best Practices, ISA-5.1*
*Updates: Added guidance for revision numbering, EDMS compatibility, asset database compatibility, control system compatibility, and P&ID/LDT consistency to address all Specification requirements*
