# Guidance: DEL-01.10 Valve Numbering Diagrams

**Document ID:** DEL-01.10-GD
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Purpose

### 1.1 Document Intent

This guidance document provides recommendations and best practices for developing Valve Numbering Diagrams for the Puget Sound Optimization project. Valve numbering diagrams provide a clear schematic representation of all valves within the project scope, enabling field personnel to identify and locate valves during construction, commissioning, and operation.

### 1.2 Target Audience

- Process Engineers (lead and supporting)
- Piping Engineers
- Drafting Personnel
- Construction/Commissioning Personnel
- Operations Personnel
- Project Engineers

---

## 2. Principles

### 2.1 Foundational Principles

| Principle | Description |
|-----------|-------------|
| Clarity | Diagrams must be clear and easy to read in the field |
| Consistency | Tag numbering must follow TM convention consistently |
| Completeness | All valves shown on P&IDs must appear on valve numbering diagrams |
| Traceability | Cross-references to P&IDs must be clear and accurate |
| Maintainability | Diagrams must be updated through IFC incorporating all changes (per SOW-0222) |

### 2.2 Coordination Principles

| Principle | Application |
|-----------|-------------|
| P&ID Alignment | Valve numbering must match P&IDs exactly |
| Valve List Alignment | Valve numbering must match valve list inventory (DEL-02.02) |
| HAZOP Integration | New valves from HAZOP (DEL-01.15) must be incorporated |
| Model Review | Valve additions from model review must be incorporated |

---

## 3. Considerations

### 3.1 Technical Considerations

#### 3.1.1 Valve Numbering Convention

Valve tag numbers should follow TM's established convention:
- **Area/Unit Identifier**: e.g., ST for Sumas Terminal (**ASSUMPTION**)
- **Valve Type Identifier**: e.g., XV for block valves, FV for flow control valves (**TBD**)
- **Sequential Number**: Unique within area/type

**ASSUMPTION:** TM has an established valve tagging convention that will be applied. Confirm convention before starting.

#### 3.1.2 Valve Types to Include

| Valve Type | Include? | Notes |
|------------|----------|-------|
| Gate Valves | Yes | Isolation service |
| Ball Valves | Yes | Isolation service |
| Plug Valves | Yes | If used |
| Globe Valves | Yes | If used |
| Check Valves | Yes | Pump discharge, other locations |
| Control Valves | Yes | All modulating valves |
| Emergency Shutdown Valves | Yes | Critical safety valves |
| Relief Valves (PRV) | Yes | Overpressure protection (per DEL-01.06) |
| Relief Valves (TRV) | Yes | Thermal relief (per DEL-01.06) |
| Vent/Drain Valves | Optional | Per TM standard practice |
| Sample Valves | Optional | Per TM standard practice |

#### 3.1.3 Information to Show

For each valve on the diagram:
- **Tag Number**: Unique valve identifier (mandatory)
- **Valve Symbol**: Per legend, indicating valve type (mandatory)
- **Line Number**: Associated pipe line number (mandatory)
- **P&ID Reference**: Cross-reference to source P&ID (mandatory)
- **Size/Rating**: Optional (may be on valve list only)
- **Actuator Type**: Optional for actuated valves (shown by symbol)

#### 3.1.4 Drawing Layout Considerations

| Consideration | Recommendation |
|---------------|----------------|
| Flow Direction | Show clearly with arrows |
| Equipment Reference | Show major equipment (pumps, vessels) for orientation |
| System Organization | Group valves by system/area |
| Legend | Include comprehensive symbol legend |
| North Arrow | Include if diagram shows spatial orientation |

### 3.2 Project Considerations

| Consideration | Recommendation |
|---------------|----------------|
| TM Drawing Standards | Obtain and follow TM drawing standards |
| CAD Standards | Use TM-approved CAD blocks and layers |
| Title Block | Use TM standard title block |
| Drawing Numbering | Follow TM drawing numbering convention |
| Revisions | Maintain revision history per TM requirements |

### 3.3 Quality Considerations

| Aspect | Recommendation |
|--------|----------------|
| P&ID Cross-Check | Systematic comparison with P&IDs (DEL-01.03) at each revision |
| Valve List Reconciliation | Verify against valve list (DEL-02.02 in PKG-02) |
| HAZOP Tracking | Track HAZOP (DEL-01.15) valve additions for incorporation |
| Model Review Tracking | Track model review valve additions |
| Drawing Check | Independent drawing check before issue |

---

## 4. Trade-offs

### 4.1 Drawing Organization Trade-offs

| Trade-off | Single Diagram | Multiple Diagrams | Recommendation |
|-----------|----------------|-------------------|----------------|
| Small System | All valves on one diagram | Not needed | Single diagram for simplicity |
| Large System | Crowded, hard to read | Clear, organized by area | Multiple diagrams for clarity |
| Complex Manifold | May need detail view | Separate manifold diagram | Detail views as needed |

### 4.2 Detail Level Trade-offs

| Trade-off | More Detail | Less Detail | Recommendation |
|-----------|-------------|-------------|----------------|
| Valve Information | Size, rating, actuator on diagram | Tag only, reference valve list | Tag + type on diagram; details on valve list |
| Equipment Detail | Show all equipment | Show only major equipment | Show equipment for orientation |
| Piping Detail | Show all piping | Show only main headers | Show enough for valve location context |

### 4.3 Timing Trade-offs

| Trade-off | Early Issue | Late Issue | Recommendation |
|-----------|-------------|------------|----------------|
| FEED Phase | Preliminary (may change) | After P&ID freeze | Issue with P&IDs; update for HAZOP |
| Detailed Design | Before model complete | After all changes | IFD after model review; IFC after HAZOP |

---

## 5. Examples

### 5.1 Valve Numbering Diagram Structure

```
+------------------------------------------+
| TITLE BLOCK                              |
| Drawing No: PSO-VND-001                  |
| Title: Valve Numbering Diagram - Area 1  |
| Rev: A                                   |
+------------------------------------------+

+------------------------------------------+
| LEGEND                                   |
| [Gate Valve Symbol] - Gate Valve         |
| [Ball Valve Symbol] - Ball Valve         |
| [Check Valve Symbol] - Check Valve       |
| [Control Valve Symbol] - Control Valve   |
| [Relief Valve Symbol] - Relief Valve     |
| ...                                      |
+------------------------------------------+

+------------------------------------------+
| DIAGRAM AREA                             |
|                                          |
|    TK-101          P-101         |       |
|    [Tank]----XV-101---[Pump]-----XV-102--|
|         |                  |             |
|      TRV-101           CV-101           |
|                                          |
|    Line: 6"-PL-101-B    Line: 6"-PL-102-B|
|    P&ID: PSO-PID-001    P&ID: PSO-PID-002|
+------------------------------------------+

+------------------------------------------+
| NOTES                                    |
| 1. All valves shown per P&IDs           |
| 2. Tag numbers per TM convention        |
| 3. Refer to valve list for details      |
+------------------------------------------+

+------------------------------------------+
| REVISION HISTORY                         |
| Rev A - Issued for Review                |
+------------------------------------------+
```

### 5.2 Valve Tag Table (Cross-Reference)

| Valve Tag | Type | Size | Line No. | P&ID Ref | Notes |
|-----------|------|------|----------|----------|-------|
| XV-101 | Gate | 6" | 6"-PL-101-B | PSO-PID-001 | Tank outlet |
| XV-102 | Gate | 6" | 6"-PL-102-B | PSO-PID-002 | Pump discharge |
| CV-101 | Control | 6" | 6"-PL-102-B | PSO-PID-002 | Flow control |
| TRV-101 | TRV | 3/4" | 6"-PL-101-B | PSO-PID-001 | Thermal relief |

### 5.3 Common Pitfalls to Avoid

- Missing valves that appear on P&IDs
- Tag numbers not matching P&IDs
- Inconsistent valve symbols
- Missing line numbers
- Missing P&ID cross-references
- Not updating for HAZOP/model review changes (per SOW-0222)
- Unclear flow direction
- Overcrowded diagrams (split into multiple sheets)

---

## 6. Additional Resources

### 6.1 Related Guidance Documents

| Document | Relevance |
|----------|-----------|
| DEL-01.03-GD | P&IDs are primary source for valve information |
| DEL-01.06-GD | Relief system design defines relief valve requirements |
| DEL-01.15-GD | HAZOP may add new valves |
| DEL-02.02-GD (PKG-02) | Valve list must match valve numbering diagrams |
| DEL-02.12-GD (PKG-02) | Piping GAs show physical valve locations |

### 6.2 Industry References

| Reference | Application |
|-----------|-------------|
| ISA 5.1 | Valve symbol standards |
| TM Drawing Standards | Project-specific format requirements |
| TM Tag Numbering Convention | Valve numbering format |

---

*End of Guidance*
