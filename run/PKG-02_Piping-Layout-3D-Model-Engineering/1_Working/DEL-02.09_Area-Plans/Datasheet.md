# Datasheet: DEL-02.09 Area Plans

## Document Information
| Field | Value |
|-------|-------|
| Deliverable ID | DEL-02.09 |
| Deliverable Name | Area Plans |
| Package | PKG-02 (Piping, Layout & 3D Model Engineering) |
| Discipline | Piping |
| Document Type | Drawing |
| Revision | Draft A |
| Status | INITIALIZED |
| Date | 2026-02-01 |

## Deliverable Summary
Area plan drawing(s) for affected areas within the Puget Sound Optimization Project at Sumas Tank Farm, providing detailed plan views of specific zones including the booster pump station area, manifold area, and associated infrastructure zones.

## Technical Parameters

### Drawing Requirements
| Parameter | Value | Source |
|-----------|-------|--------|
| Drawing Format | TBD (per TM CAD standards) | ASSUMPTION: TM standards apply |
| Scale | TBD (typically 1:100 or 1:200 for area plans) | ASSUMPTION: Standard practice |
| Coordinate System | TBD (per existing site survey) | ASSUMPTION: Match existing site model |
| North Arrow | Required | Standard practice |
| Legend | Required | Standard practice |
| Grid Reference | Required | Per site survey datum |

### Scope Coverage
| Area | Description | Source |
|------|-------------|--------|
| Booster Pump Station Area | Five VS6 pumps, VFDs, local panels | SOW: Section 2.3.1.2 (p5) |
| Manifold Area | 5x6 manifold with actuated valves | SOW: Section 2.3.1.1 (p5) |
| Containment Area | Secondary containment, sump tank system | SOW: Section 2.3.1.1 (p5) |
| Electrical Building Area | New electrical service building | SOW: Section 3.1.5.1 (p10) |
| Tie-In Areas | Connections to existing facilities | SOW: Section 2.3.1.1 (p5) |

### Content Requirements
| Element | Required | Notes |
|---------|----------|-------|
| Equipment locations | Yes | All major equipment with tags |
| Equipment footprints | Yes | Accurate outlines with dimensions |
| Piping routing | Yes | Major piping with line numbers |
| Valve locations | Yes | All valves with tags |
| Instrument locations | Yes | Coordinate with I&C |
| Access ways | Yes | Walkways, platforms, ladders |
| Structural elements | Yes | Buildings, supports, foundations |
| Containment boundaries | Yes | Walls, curbs, drainage |
| Match lines | Yes | Reference to plot plan and GA drawings |
| Dimensions | Yes | Key equipment coordinates |

### Area Parameters
| Parameter | Value | Source |
|-----------|-------|--------|
| Project Location | SW corner of Tank TK-102 | SOW: Section 2.3.1.1 (p5) |
| Booster Pump Configuration | 2 large, 2 small, 1 medium | SOW: Section 2.3.1.2 (p5) |
| Manifold Configuration | 5x6 (5 suction headers, 6 discharge) | SOW: Section 2.3.1.1 (p5) |
| Containment Requirements | Secondary containment per regulations | ASSUMPTION: API 2610, EPA requirements |

### Revision Cycle
| Phase | Status | Description |
|-------|--------|-------------|
| FEED | IFR -> IFD | Initial issue for review, progressing to Issued for Design |
| Detailed Design | IFC | Issued for Construction |

## Interface Requirements
| Interface | Deliverable | Description |
|-----------|-------------|-------------|
| Piping | DEL-02.08 (Overall Plot Plan) | Context and match lines |
| Piping | DEL-02.10 (Equipment Layout Plans) | Detailed equipment arrangement |
| Piping | DEL-02.12 (GA Drawings) | Detailed piping arrangement |
| Civil | DEL-04.06 (Civil Site Plans) | Grading and drainage |
| Civil | DEL-04.17 (Foundation Plans) | Foundation locations |
| Civil | DEL-04.21 (Containment) | Containment details |
| Structural | DEL-04.27 (Structural Plans) | Steel and platforms |
| Electrical | DEL-06.12 (Area Classification) | Hazardous areas |
| I&C | DEL-07.04 (Instrument Location Plan) | Instrument locations |
| 3D Model | DEL-02.28 (Sitewide 3D Model) | 3D model-derived views |

## Applicable Codes and Standards
| Code/Standard | Description | Source |
|---------------|-------------|--------|
| CSA Z662 | Oil and Gas Pipeline Systems | SOW: Section 4.1.3 (p33) |
| API 2610 | Design of Tank Farms | ASSUMPTION: Spacing and layout |
| OSHA 1910 | Walking-Working Surfaces | ASSUMPTION: Access requirements |
| TM CAD Standards | Drawing format and symbology | ASSUMPTION: TM standards apply |
| TMP Standards and Specifications | Governing project standards | SOW: Section 4.1.2 (p33) |

## Assumptions
1. ASSUMPTION: Area plans will cover all affected areas within PSO project scope.
2. ASSUMPTION: Multiple sheets organized by area with consistent scale.
3. ASSUMPTION: Area plans provide intermediate detail between plot plan and equipment layouts.
4. ASSUMPTION: Match lines coordinate with overall plot plan (DEL-02.08).

## TBD Items
1. TBD: Specific TM CAD standards and templates.
2. TBD: Number of area plan sheets required.
3. TBD: Area designations and sheet coverage boundaries.
4. TBD: Finalized equipment layout coordinates.
5. TBD: Hazardous area classification zones.
6. TBD: Access platform and walkway requirements.

## Source References
- Decomposition: Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md
- SOW: Exhibit A - Scope of Work PS.pdf, Sections 2.3.1, 3.1.3, 3.2.4.8
- DBM: Puget Sound Optimization Project DBM.pdf
- Appendix A-1: PSO - ST - New Utility Area - Proposed Layout
- Scope Items: SOW-0247
