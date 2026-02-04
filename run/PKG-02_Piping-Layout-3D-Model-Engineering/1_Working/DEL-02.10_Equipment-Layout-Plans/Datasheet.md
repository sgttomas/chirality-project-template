# Datasheet: DEL-02.10 Equipment Layout Plans

## Document Information
| Field | Value |
|-------|-------|
| Deliverable ID | DEL-02.10 |
| Deliverable Name | Equipment Layout Plans |
| Package | PKG-02 (Piping, Layout & 3D Model Engineering) |
| Discipline | Piping |
| Document Type | Drawing |
| Revision | Draft A |
| Status | INITIALIZED |
| Date | 2026-02-01 |

## Deliverable Summary
Equipment layout plan drawing(s) for the Puget Sound Optimization Project at Sumas Tank Farm, providing detailed arrangement views of major equipment including the five VS6 booster pumps, 5x6 manifold system, sump tank, and associated mechanical equipment.

## Technical Parameters

### Drawing Requirements
| Parameter | Value | Source |
|-----------|-------|--------|
| Drawing Format | TBD (per TM CAD standards) | ASSUMPTION: TM standards apply |
| Scale | TBD (typically 1:50 for detailed equipment layouts) | ASSUMPTION: Standard practice |
| Coordinate System | TBD (per existing site survey) | ASSUMPTION: Match existing site model |
| North Arrow | Required | Standard practice |
| Legend | Required | Standard practice |
| Grid Reference | Required | Per site survey datum |

### Scope Coverage
| Equipment Area | Description | Source |
|----------------|-------------|--------|
| Booster Pump Station | Five VS6 booster pumps (2 large, 2 small, 1 medium) | SOW: Section 2.3.1.2 (p5) |
| Manifold System | 5x6 manifold with actuated valves | SOW: Section 2.3.1.1 (p5) |
| Sump Tank System | Sump tank, reinjection pumps, dewatering | SOW: Section 3.2.3.10 (p16-18) |
| VFD/Motor Area | Variable frequency drives and motors | SOW: Section 3.1.5.1 (p10) |

### Content Requirements
| Element | Required | Notes |
|---------|----------|-------|
| Equipment outlines | Yes | Accurate footprints from vendor data |
| Equipment tags | Yes | Per equipment list |
| Nozzle locations | Yes | All process nozzles with orientations |
| Nozzle schedules | Yes | Size, rating, facing |
| Foundation references | Yes | Cross-reference to foundation drawings |
| Clearance dimensions | Yes | Maintenance and access clearances |
| Equipment elevations | Yes | Reference to project datum |
| Anchor bolt patterns | Yes | From vendor data |
| Lifting provisions | Yes | For installation and maintenance |
| Driver locations | Yes | Motors, VFDs, gearboxes |
| Auxiliary equipment | Yes | Lube systems, seal systems, etc. |

### Equipment Parameters
| Equipment | Quantity | Configuration | Source |
|-----------|----------|---------------|--------|
| Large Booster Pumps | 2 | VS6 vertical | SOW: Section 2.3.1.2 |
| Small Booster Pumps | 2 | VS6 vertical | SOW: Section 2.3.1.2 |
| Medium Booster Pump | 1 | VS6 vertical | SOW: Section 2.3.1.2 |
| Manifold System | 1 | 5x6 configuration | SOW: Section 2.3.1.1 |
| Sump Tank | 1 | TBD | SOW: Section 3.2.3.10 |
| Reinjection Pumps | TBD | TBD | SOW: Section 3.2.3.10 |

### Revision Cycle
| Phase | Status | Description |
|-------|--------|-------------|
| FEED | IFR -> IFD | Initial issue for review, progressing to Issued for Design |
| Detailed Design | IFC | Issued for Construction |

## Interface Requirements
| Interface | Deliverable | Description |
|-----------|-------------|-------------|
| Piping | DEL-02.08 (Plot Plan) | Overall equipment locations |
| Piping | DEL-02.09 (Area Plans) | Area context |
| Piping | DEL-02.12 (GA Drawings) | Piping connections |
| Mechanical | DEL-03.01 (Equipment List) | Equipment identification |
| Mechanical | DEL-03.02 (Equipment Datasheets) | Equipment dimensions and data |
| Mechanical | DEL-03.04 (Vendor Data) | Certified vendor drawings |
| Civil | DEL-04.17 (Foundation Plans) | Foundation coordination |
| Civil | DEL-04.18 (Foundation Details) | Anchor bolt patterns |
| Structural | DEL-04.27 (Structural Plans) | Platforms and supports |
| Electrical | DEL-06.04 (Motor Data) | Motor dimensions |
| 3D Model | DEL-02.28 (Sitewide 3D Model) | 3D model representation |

## Applicable Codes and Standards
| Code/Standard | Description | Source |
|---------------|-------------|--------|
| CSA Z662 | Oil and Gas Pipeline Systems | SOW: Section 4.1.3 (p33) |
| API 610 | Centrifugal Pumps | ASSUMPTION: Pump design standard |
| API 674/675 | Positive Displacement Pumps (if applicable) | ASSUMPTION: If PD pumps used |
| NEMA | Motor frame sizes and dimensions | ASSUMPTION: Standard practice |
| TM CAD Standards | Drawing format and symbology | ASSUMPTION: TM standards apply |
| TMP Standards and Specifications | Governing project standards | SOW: Section 4.1.2 (p33) |

## Assumptions
1. ASSUMPTION: Equipment layout plans provide detailed arrangement for major mechanical equipment.
2. ASSUMPTION: Vendor dimensional data required for final equipment layouts.
3. ASSUMPTION: Preliminary layouts based on preliminary sizing pending vendor selection.
4. ASSUMPTION: Multiple sheets organized by equipment groupings.

## TBD Items
1. TBD: Specific TM CAD standards and templates.
2. TBD: Final equipment vendor selection and data.
3. TBD: Pump dimensional data and nozzle schedules.
4. TBD: VFD/motor dimensional data.
5. TBD: Sump tank and reinjection pump specifications.
6. TBD: Anchor bolt patterns and foundation requirements.

## Source References
- Decomposition: Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md
- SOW: Exhibit A - Scope of Work PS.pdf, Sections 2.3.1, 3.1.3, 3.2.4.8
- DBM: Puget Sound Optimization Project DBM.pdf
- Scope Items: SOW-0247
