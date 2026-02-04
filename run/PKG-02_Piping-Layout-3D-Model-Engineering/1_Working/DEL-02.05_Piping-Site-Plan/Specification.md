# Specification: Piping Site Plan

## 1. Scope

### 1.1 Purpose
This specification defines the requirements for developing and maintaining the Piping Site Plan for the Puget Sound Optimization Project at Sumas Tank Farm.

### 1.2 Applicability
- Overall piping layout showing new and modified piping
- Above-ground and below-ground piping routes
- Piping to/from new booster pumps and manifold
- Interconnections with existing tank farm systems

### 1.3 Exclusions
- Piping fabrication details (covered in Isometrics)
- Equipment internal piping (covered in Vendor drawings)
- Instrument tubing routing (covered under Instrumentation)

## 2. Requirements

### 2.1 Content Requirements
The Piping Site Plan shall include:

| Requirement | Description |
|-------------|-------------|
| REQ-01 | Major equipment locations with tag numbers |
| REQ-02 | Above-ground piping routes with line numbers |
| REQ-03 | Below-ground piping routes (dashed) with line numbers |
| REQ-04 | Pipe rack/sleeper locations |
| REQ-05 | Road/access crossings (bridges or underground) |
| REQ-06 | Tie-in point locations |
| REQ-07 | Major valve locations |
| REQ-08 | Coordinate grid references |
| REQ-09 | North arrow and scale |
| REQ-10 | Match-line references to Key Plan |
| REQ-11 | Legend and abbreviations |

### 2.2 Format Requirements
- CAD drawing format (DWG native, PDF for distribution)
- D-size or E-size sheet (**ASSUMPTION**)
- Scale 1:200 or 1:500 as appropriate (**ASSUMPTION**)
- Comply with TM CAD standards (**TBD**)

### 2.3 Accuracy Requirements
- Piping routes consistent with 3D model
- Coordinates consistent with site survey
- Equipment locations consistent with Plot Plan

## 3. Standards

| Standard | Description |
|----------|-------------|
| ASME Y14.1 | Drawing Sheet Size and Format (**ASSUMPTION**) |
| ASME Y14.24 | Types and Applications of Engineering Drawings (**ASSUMPTION**) |
| TM-STD-CAD-001 | TM CAD Standard (**TBD**) |
| TM-STD-DWG-001 | TM Drawing Standard (**TBD**) |
| TM-STD-PIPE-SYM | TM Piping Symbols (**TBD**) |

## 4. Verification

### 4.1 Verification Methods
| Method | Description |
|--------|-------------|
| Review | Technical review by Lead Piping Engineer |
| Model Check | Verification against 3D model |
| Cross-check | Verification against P&IDs and Plot Plan |
| Coordination | Verify with Civil/Structural for underground services |

### 4.2 Acceptance Criteria
- All piping within scope is represented
- Piping routes match 3D model
- Line numbers match Line List
- Tie-in points match Tie-In List
- No conflicts with underground utilities
- Owner review and approval

## 5. Documentation

### 5.1 Deliverable Format
- Native: DWG (AutoCAD or equivalent)
- Distribution: PDF
- Model link: Extracted/referenced from 3D model

### 5.2 Submission Requirements
| Milestone | Status |
|-----------|--------|
| FEED IFR | Issue for Review |
| FEED IFD | Issue for Design |
| Detailed Design IFC | Issue for Construction |
| As-Built | Final as-built revision |

### 5.3 Related Documents
- DEL-02.04: Piping Key Plan
- DEL-02.06: Piping Demolition Site Plan
- DEL-02.08: Overall Plot Plan
- DEL-02.12: Piping GA Drawings
- DEL-02.28: Sitewide 3D Model

### 5.4 SOW Traceability
| SOW Item | Description | Reference |
|----------|-------------|-----------|
| SOW-0123 | Produce FEED piping site plan (GA) | SOW Section 3.1.3.1 (p7-8) |
| SOW-0247 | Update/finalize site-specific drawings (area/key/equipment layout/module location/plot plan/GA drawings) | SOW Section 3.2.4.8 (p19) |
| SOW-0252 | Develop piping general arrangement drawings depicting above/below ground piping, equipment connections, instrument/nozzle locations, road crossings/pipe bridges, and CP connection points/ground anodes | SOW Section 3.2.4.13 (p20) |

---
*Generated 2026-02-01 | SOW Refs: SOW-0123, SOW-0247, SOW-0252*
