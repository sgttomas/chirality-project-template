# Guidance: DEL-02.13 Piping Isometrics

## 1. Purpose

### 1.1 Document Intent
This guidance document provides practical direction for developing Piping Isometric Drawings for the PSO Project at Sumas Tank Farm. It addresses fabrication considerations, spool organization, weld tracking, and best practices for producing construction-ready isometrics.

### 1.2 Target Audience
- Piping Designers
- 3D Model Coordinators
- Piping Engineers
- Fabrication Shop Personnel
- Construction/Installation Teams
- QC/QA Personnel

### 1.3 Context
Piping isometrics are the primary fabrication documents for the PSO Project. They must provide complete information for shop prefabrication, field installation, welding, NDT, hydrotesting, and finishing (heat trace, insulation, coating). For brownfield tie-ins at Sumas Tank Farm, special attention is required for field verification dimensions.

## 2. Principles

### 2.1 Core Principles

| Principle | Description |
|-----------|-------------|
| **Fabrication Focus** | Isometrics are shop fabrication documents first; all information for spool production must be present |
| **Completeness** | All information needed for fabrication, installation, and testing on one drawing or clearly referenced |
| **Accuracy** | Dimensions match verified 3D model exactly; errors cause rework |
| **Traceability** | Unique weld numbering enables full traceability through fabrication, NDT, and testing |
| **Clarity** | Unambiguous presentation; fabricator should not need to guess |

### 2.2 Isometric Purpose Hierarchy

```
Piping Isometrics support:
    |
    +-- Spool Fabrication (shop)
    |       +-- Cut list generation
    |       +-- Material procurement (BOM)
    |       +-- Fit-up and welding
    |
    +-- Field Installation
    |       +-- Spool identification
    |       +-- Field weld locations
    |       +-- Support locations
    |
    +-- Welding and NDT Tracking
    |       +-- Weld register basis
    |       +-- NDT extent per weld
    |       +-- PWHT requirements
    |
    +-- Hydrotest Boundary Definition
    |       +-- Test package boundaries
    |       +-- Isolation points
    |
    +-- As-Built Documentation
            +-- Final record of installed piping
```

## 3. Considerations

### 3.1 Project-Specific Considerations (PSO)

| Factor | Impact | Guidance |
|--------|--------|----------|
| Crude Oil Service | Material and welding requirements | Verify PMC specifications for sour/sweet service considerations |
| Booster Pump Piping | High-pressure discharge lines | Stress-critical; coordinate support locations with DEL-02.14 |
| 5x6 Manifold | Many branch connections, complex geometry | Plan isometric subdivision carefully |
| Tie-In Spools | Connection to existing systems | Mark "FIELD VERIFY" on tie-in dimensions |
| VFD/Flow Meters | Discharge flow meters at each pump | Verify straight run requirements |
| Winter Conditions | PWHT and coating for temperature extremes | Include all cold-weather requirements |

### 3.2 Technical Considerations

| Topic | Guidance |
|-------|----------|
| **Spool Breaks** | Break at flanges for field flexibility; consider transport and handling limits |
| **Shop vs Field Welds** | Maximize shop welds for quality control; field welds at tie-ins and final closures |
| **Support Locations** | Coordinate with stress analysis (DEL-02.14) for all support points |
| **Valve Orientation** | Confirm actuator/handwheel orientation matches equipment layout |
| **Flow Direction** | Show flow direction arrows on headers for clarity |
| **Slope Requirements** | Show slope for drain lines; indicate slope direction and rate |

### 3.3 Information Completeness Checklist

| Category | Required Items |
|----------|----------------|
| **Geometry** | Pipe lengths, offsets, angles, elevations, coordinates |
| **Materials** | Line class, pipe spec, schedule, PMC reference |
| **Welds** | Weld type, weld number, shop/field, WPS reference |
| **Testing** | NDT extent per weld, hydrotest package reference |
| **Coatings** | Primer, finish coat, special coatings, holiday testing |
| **Insulation** | Type, thickness, jacket material, heat tracer type |
| **Supports** | Location, type reference, tag number |

### 3.4 Tie-In Spool Considerations

| Issue | Guidance |
|-------|----------|
| Existing Dimensions | Field verify all existing dimensions before final spool fabrication |
| Dimensional Tolerance | Show theoretical dimension with tolerance allowance |
| Field Weld Procedures | Reference applicable field weld procedures |
| Isolation Requirements | Coordinate with tie-in plan and Operations |
| Hot Tap References | Reference hot tap procedures if applicable (by others per SOW-0249) |

## 4. Trade-offs

### 4.1 Isometric Detail Level

| Approach | Pros | Cons | Recommendation |
|----------|------|------|----------------|
| Highly Detailed | Complete fabrication info, fewer RFIs | More drafting time, cluttered drawings | Use for complex/critical lines |
| Minimal Detail | Faster production | Relies on specs, more RFIs | Avoid - not suitable for IFC |
| Standard Notes | Consistent, less clutter | May miss line-specific exceptions | Balance with explicit callouts for exceptions |

### 4.2 Spool Organization Strategies

| Strategy | When to Use | Considerations |
|----------|-------------|----------------|
| Maximum Shop Fab | Quality-critical systems | Larger spools, fewer field welds, verify transport limits |
| Transport-Limited | Large diameter piping | Break spools at transport limits (typically 12m length, 3m width) |
| Handling-Limited | Heavy wall pipe | Consider crane capacity, rigging points |
| Flange Breaks | Tie-ins, isolation points | Provides field flexibility, easier leak testing |
| Installation Sequence | Congested areas | Plan spool installation order |

### 4.3 BOM Detail Level

| Approach | Pros | Cons | Recommendation |
|----------|------|------|----------------|
| Complete BOM per ISO | Self-contained document | More drawing space | Preferred for fabrication |
| Summary BOM with references | Less cluttered | Requires cross-reference | Acceptable for simple lines |
| BOM on separate sheet | More drawing space for ISO | Extra document to track | For very complex isometrics |

## 5. Examples

### 5.1 Isometric Drawing Checklist

**Header Information:**
- [ ] Line number prominently displayed
- [ ] Service description
- [ ] P&ID reference
- [ ] North arrow indicated
- [ ] GA drawing reference

**Geometry and Dimensions:**
- [ ] All fabrication dimensions shown (cut lengths, offsets)
- [ ] Elevation references at changes
- [ ] Coordinate references for key points
- [ ] Spool marks and breaks identified
- [ ] Continuation references to adjacent isometrics

**Welding:**
- [ ] All welds numbered with unique weld IDs
- [ ] Shop vs field welds distinguished
- [ ] Weld symbols per applicable standard
- [ ] WPS reference (or note "Per WPS")
- [ ] PWHT requirements indicated

**Testing and Finishing:**
- [ ] NDT requirements per weld (or reference to LDT)
- [ ] Hydrotest package reference
- [ ] Insulation type and thickness
- [ ] Heat trace requirements
- [ ] Coating/painting requirements

**Bill of Materials:**
- [ ] Complete BOM with all components
- [ ] Correct quantities
- [ ] Material specifications
- [ ] Valve and specialty item tags
- [ ] Weight estimate (recommended for heavy spools)

**Administrative:**
- [ ] Title block complete
- [ ] Revision history current
- [ ] Approval signatures (for issued revisions)

### 5.2 Weld Numbering Convention (ASSUMPTION - confirm with TM)

```
Format: W-LLLL-SSS-NNN

Where:
W     = Weld prefix
LLLL  = Line number (abbreviated, e.g., 2501 for line 16"-P-2501-C3B)
SSS   = Spool number (e.g., 001)
NNN   = Sequential weld number on that spool (001, 002, etc.)

Example: W-2501-003-005 = 5th weld on spool 003 of line 2501

Shop Welds:  W-2501-003-005 (standard notation)
Field Welds: FW-2501-003-005 (FW prefix)
```

### 5.3 BOM Format Example

| Item | Qty | Description | Size | Material/Class | Tag | Remarks |
|------|-----|-------------|------|----------------|-----|---------|
| 1 | 4.5m | Pipe, Smls | 16" | A106B/C3B | - | Sch 40 |
| 2 | 2 | 90 Deg LR Elbow | 16" | A234WPB/C3B | - | BW |
| 3 | 1 | Gate Valve | 16" | Class 300 | V-2501 | RF Flanged |
| 4 | 2 | Weld Neck Flange | 16" | A105/300# | - | RF |
| 5 | 2 | Spiral Wound Gasket | 16" | 316SS/Graph | - | 300# RF |

### 5.4 Common Issues to Avoid

| Issue | Consequence | Prevention |
|-------|-------------|------------|
| Dimension errors between model and isometric | Fabrication errors, rework | Automated extraction with verification |
| Missing welds in weld count | Incomplete NDT, documentation gaps | Complete weld register before issue |
| Incorrect material specification callouts | Wrong material fabricated | Verify PMC reference on every isometric |
| Spool too large for transport | Field rework, schedule impact | Check transport limits during spool planning |
| Missing insulation/heat trace requirements | Incomplete installation | Include all finishing requirements |
| Inconsistent flow direction arrows | Confusion during installation | Consistent convention across all isometrics |
| Missing tie-in field verification notes | Fit-up issues in field | Mark "FIELD VERIFY" on all tie-in dimensions |
| Incomplete continuation references | Lost context between drawings | Verify continuation references match |

### 5.5 Tie-In Spool Annotation Example

```
NOTES FOR TIE-IN SPOOL:
1. DIMENSION "A" IS THEORETICAL. FIELD VERIFY ACTUAL
   DIMENSION BEFORE SPOOL FABRICATION.
   TOLERANCE: +/- 25mm
2. REFER TO TIE-IN LIST (DEL-02.03) FOR TIE-IN DETAILS
3. COORDINATE WITH OPERATIONS FOR TIE-IN SEQUENCE
4. FIELD WELD FW-2501-TI-001 PER WPS-XXX
```

---
*Document generated 2026-02-01 | Deliverable Status: OPEN*
