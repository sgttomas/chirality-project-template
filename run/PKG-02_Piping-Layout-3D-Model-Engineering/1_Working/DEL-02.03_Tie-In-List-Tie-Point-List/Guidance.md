# Guidance: Tie-In List / Tie Point List

## 1. Purpose

### 1.1 Document Intent
This guidance document provides direction on developing the Tie-In List for the Puget Sound Optimization Project, addressing practical considerations, industry best practices, and project-specific requirements for brownfield tie-in management.

### 1.2 Target Audience
- Piping Engineers
- Construction Planners
- Operations Representatives
- Field Engineers

## 2. Principles

### 2.1 Core Principles
| Principle | Description |
|-----------|-------------|
| **Safety First** | All tie-ins must be planned with consideration for live system hazards |
| **Operational Continuity** | Minimize shutdown duration and operational impact |
| **Traceability** | Every tie-in must be traceable to P&IDs and existing system drawings |
| **Coordination** | Early coordination with Operations is essential |

### 2.2 Tie-In Planning Hierarchy
```
P&IDs (Define Connections)
    └── Tie-In List (Master Register)
            ├── Site Plan (Location Visualization)
            ├── Isolation Plan (By Operations)
            ├── Execution Plan (By Construction)
            └── Turnover Package (Completion)
```

## 3. Considerations

### 3.1 Project-Specific Considerations

| Consideration | Details |
|---------------|---------|
| **Brownfield Environment** | Sumas Tank Farm is an operating facility |
| **Live System Tie-Ins** | Crude oil service requires careful isolation planning |
| **Booster Pump Connections** | 5 new VS6 pumps connecting to existing tank systems |
| **Manifold Integration** | 5x6 manifold connecting to existing headers |
| **Execution by Others** | Hot taps and tie-in execution excluded per SOW |

### 3.2 Technical Considerations

| Topic | Guidance |
|-------|----------|
| **Isolation Planning** | Identify double block and bleed requirements |
| **Hot Tap vs. Cold Cut** | Recommend method based on shutdown constraints |
| **Sequence Planning** | Consider dependencies between tie-ins |
| **Field Verification** | Survey existing conditions before finalizing locations |

### 3.3 Coordination Requirements
- Early engagement with TM Operations for isolation requirements
- Coordinate with Construction for execution sequencing
- Verify existing drawings against field conditions
- Align with shutdown planning windows

## 4. Trade-offs

### 4.1 Tie-In Execution Approaches

| Approach | Pros | Cons |
|----------|------|------|
| **Hot Tap** | No shutdown required | Higher cost, special equipment |
| **Cold Cut** | Lower cost, simpler | Requires shutdown |
| **Prefabricated Spool** | Quality controlled | Requires precise measurements |

### 4.2 Sequencing Considerations

| Trade-off | Recommendation |
|-----------|----------------|
| **Parallel vs. Sequential** | Sequential for shared isolation points |
| **Early vs. Late Tie-Ins** | Early for commissioning path items |
| **Grouped vs. Individual** | Group by isolation boundary where possible |

## 5. Examples

### 5.1 Sample Tie-In Number Format (**ASSUMPTION** - confirm with TM)
```
TI-XXX-NNN

Where:
TI  = Tie-In prefix
XXX = System/area code
NNN = Sequence number
```

### 5.2 Sample Tie-In List Entry

| TI No | New Line | Existing Line | Description | P&ID | Size | Type | Location | Isolation | Method |
|-------|----------|---------------|-------------|------|------|------|----------|-----------|--------|
| TI-SF-001 | SF-OIL-0800-001 | 8"-OIL-101 | BP-101 Suction | P-001 | 8" | Flange | SW TK-102 | XV-101, XV-102 | Cold Cut |
| TI-SF-002 | SF-OIL-0600-002 | 6"-OIL-103 | Manifold Tie-In | P-002 | 6" | Hot Tap | N of MF-001 | N/A | Hot Tap |

### 5.3 Common Issues to Avoid
1. Incomplete isolation identification
2. Inaccurate location coordinates
3. Missing field verification before IFC
4. Underestimated shutdown durations
5. Conflicting tie-in sequences
6. Missing coordination with Operations

### 5.4 SOW Traceability
This deliverable supports the following SOW requirements:
- **SOW-0121**: Produce FEED tie-in list (TIL) - per SOW Section 3.1.3.1 (p7-8)
- **SOW-0249**: Develop piping tie-in table (line number, tie-in description, P&ID number, tie-in number); hot taps and other tie-in activities excluded (by others) - per SOW Section 3.2.4.10 (p19)

---
*Generated 2026-02-01 | SOW Refs: SOW-0121, SOW-0249*
