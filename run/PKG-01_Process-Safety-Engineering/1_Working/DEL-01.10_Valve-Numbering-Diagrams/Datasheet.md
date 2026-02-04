# Datasheet: DEL-01.10 Valve Numbering Diagrams

**Document ID:** DEL-01.10-DS
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Identification

| Field | Value |
|-------|-------|
| Deliverable ID | DEL-01.10 |
| Deliverable Name | Valve Numbering Diagrams |
| Parent Package | PKG-01 Process & Safety Engineering |
| Discipline | Process/Safety |
| Document Type | Drawing |
| Responsible Party | Engineering Contractor |

---

## 2. Attributes

### 2.1 Technical Attributes

| Attribute | Value | Notes |
|-----------|-------|-------|
| Project Phase | FEED + Detailed Design | Maintained through IFC per SOW-0222 and SOW-0232 |
| Drawing Purpose | Show valve locations with unique tag numbers | Schematic representation |
| Drawing Type | Valve numbering diagram (schematic) | Not to scale |
| Coordination Required | P&IDs, Valve List, Piping Layout | Cross-discipline alignment |
| Numbering Convention | **TBD** | Per TM tag numbering system |

### 2.2 Drawing Attributes

| Attribute | Value | Notes |
|-----------|-------|-------|
| Drawing Size | **TBD** | **ASSUMPTION:** D-size (22"x34") typical |
| Drawing Format | CAD (AutoCAD/MicroStation) | Per TM requirements |
| Scale | Not to scale (schematic) | Standard for valve diagrams |
| Symbol Standard | TM Standard / ISA | **TBD** - Per TM symbol library |

### 2.3 Document Attributes

| Attribute | Value |
|-----------|-------|
| Anticipated Artifacts | Valve numbering diagrams |
| Native Format | CAD (dwg/dgn) |
| Deliverable Format | PDF + Native CAD files |
| Revision Cycle | IFR -> IFD -> IFC |

### 2.4 Drawing Set Composition

| Component | Estimated Count | Notes |
|-----------|-----------------|-------|
| Overall System Valve Diagram | **TBD** | System overview with all valves |
| Area-Specific Diagrams | **TBD** | If system is large |
| Legend/Symbol Sheet | 1 | Per TM standards |

---

## 3. Conditions

### 3.1 Valve Types to be Shown

| Valve Type | Symbol | Tag Prefix | Notes |
|------------|--------|------------|-------|
| Gate Valves | **TBD** | **TBD** | Isolation service |
| Ball Valves | **TBD** | **TBD** | Isolation service |
| Check Valves | **TBD** | **TBD** | Pump discharge |
| Control Valves | **TBD** | **TBD** | Flow/pressure control |
| Relief Valves (PRV) | **TBD** | **TBD** | Overpressure protection |
| Relief Valves (TRV) | **TBD** | **TBD** | Thermal relief |
| Plug Valves | **TBD** | **TBD** | If applicable |

### 3.2 Valve Numbering Format

| Component | Format | Example | Notes |
|-----------|--------|---------|-------|
| Tag Number | **TBD** | **TBD** | Per TM numbering convention |
| Area/Unit Identifier | **TBD** | ST (Sumas Terminal) | **ASSUMPTION** |
| Valve Type Identifier | **TBD** | **TBD** | Per TM convention |
| Sequential Number | **TBD** | 001, 002, etc. | Per area/system |

### 3.3 Information to be Shown per Valve

| Information | Required | Notes |
|-------------|----------|-------|
| Valve Tag Number | Yes | Unique identifier |
| Valve Type | Yes | Symbol per legend |
| Line Number | Yes | Associated pipe |
| P&ID Reference | Yes | Cross-reference |
| Size | Optional | Shown on P&ID |
| Rating | Optional | Shown on valve list |

---

## 4. Construction

### 4.1 Drawing Content Requirements

Each Valve Numbering Diagram shall include:
- Title block with drawing number, revision, date
- System/area identification
- Process flow direction indication
- All valves with unique tag numbers
- Line numbers for associated piping
- Major equipment references (pumps, vessels)
- P&ID cross-references
- Legend for valve symbols
- Notes section
- Revision history

### 4.2 Drawing Standards

| Standard | Application | Notes |
|----------|-------------|-------|
| TM Drawing Standards | Format, title block, numbering | **TBD** - Obtain from TM |
| ISA 5.1 | Valve symbol standards | Reference |
| TM Symbol Library | Project-specific symbols | **TBD** |

### 4.3 Valve Inventory (Preliminary)

| System | Valve Category | Estimated Count | Notes |
|--------|----------------|-----------------|-------|
| Booster Pump Suction | Isolation | **TBD** | 5 pumps |
| Booster Pump Discharge | Isolation + Check | **TBD** | 5 pumps |
| 5x6 Manifold | Isolation/Control | **TBD** | Per manifold design |
| Tank Connections | Isolation | **TBD** | TK-101, TK-102 |
| Relief Systems | PRV/TRV | **TBD** | Per DEL-01.06 |
| Blending System | Control | **TBD** | Flow ratio control |
| Total Estimated | All types | **TBD** | To be confirmed |

### 4.4 Dependencies

| Dependency | Source | Status |
|------------|--------|--------|
| Design Basis (DBM) | DEL-01.01 | Required |
| Process Flow Diagrams | DEL-01.02 | Required |
| P&IDs | DEL-01.03 | Required (primary source) |
| TM Tag Numbering Convention | TM | **TBD** |
| TM Drawing Standards | TM | **TBD** |
| TM Symbol Library | TM | **TBD** |
| Valve List | DEL-02.02 (PKG-02) | Concurrent |
| Piping General Arrangements | DEL-02.12 (PKG-02) | Reference |

---

## 5. References

### 5.1 Source Documents

| Document | Reference |
|----------|-----------|
| SOW Reference | SOW-0222: Update/finalize valve numbering diagrams to IFC incorporating HAZOP/model review/change notice/vendor data updates |
| SOW Reference | SOW-0232: Provide IFC process deliverables including valve numbering diagrams |
| Decomposition | Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md |

### 5.2 Related Deliverables

| Deliverable ID | Relationship |
|----------------|--------------|
| DEL-01.02 | PFDs show major valves |
| DEL-01.03 | P&IDs are primary source for valve locations |
| DEL-01.06 | Relief system design defines relief valves |
| DEL-01.15 | HAZOP may require valve additions |
| DEL-02.02 (PKG-02) | Valve list provides valve inventory |
| DEL-02.12 (PKG-02) | Piping GAs show physical valve locations |

### 5.3 Applicable Standards

| Standard | Description |
|----------|-------------|
| ISA 5.1 | Instrumentation Symbols and Identification |
| TM Drawing Standards | Trans Mountain project-specific (**TBD**) |
| TM Tag Numbering Convention | Trans Mountain project-specific (**TBD**) |

---

*End of Datasheet*
