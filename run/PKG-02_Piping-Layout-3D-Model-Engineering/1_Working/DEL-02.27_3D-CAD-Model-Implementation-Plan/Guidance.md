# Guidance: DEL-02.27 3D CAD Model Implementation Plan

## Purpose

### Intent
The 3D CAD Model Implementation Plan establishes the framework for consistent, coordinated 3D model development across the PSO project. This guidance ensures the plan addresses practical considerations, aligns with TM requirements, and enables efficient deliverable extraction and construction support.

### Context
The Implementation Plan is a foundational document that must be approved before detailed modeling begins. It defines "how we will model" for the project and ensures all disciplines work within a common framework. For the PSO brownfield expansion, integration with TM's existing site model is critical.

### Stakeholders
| Stakeholder | Interest |
|-------------|----------|
| 3D Model Coordinator | Model management, coordination procedures, clash detection |
| Lead Piping Engineer | Piping model content, isometric extraction, stress analysis interface |
| Discipline Leads | Discipline-specific modeling requirements and workflows |
| CAD Manager | Software platform, technical procedures, deliverable extraction |
| Project Management | Schedule integration, resource planning, milestone alignment |
| IT Support | Infrastructure, software licensing, backup systems |
| Client (TM) | Standards compliance, model turnover, integration with existing model |

## Principles

### Core Principles
| Principle | Description |
|-----------|-------------|
| **Integration** | Seamless integration with TM existing Sumas Terminal site model |
| **Coordination** | Multi-discipline coordination through single federated model environment |
| **Accuracy** | Model accuracy suitable for design development, clash detection, and construction |
| **Extractability** | All 2D deliverables (drawings, isometrics) extractable from 3D model |
| **Maintainability** | Model structure supports updates through construction and as-built phases |
| **Standardization** | Consistent naming, layering, and organization across all disciplines |

### Model Hierarchy
```
Project Model (PSO)
    |
    +-- 00_Project_Setup/
    |       +-- Coordinate_System
    |       +-- Project_Standards
    |
    +-- 01_Existing_Site/ (TM provided)
    |       +-- Sumas_Terminal_Existing
    |
    +-- 02_Booster_Pump_Station/
    |       +-- Civil_Structural/
    |       +-- Mechanical_Equipment/
    |       +-- Piping/
    |       +-- Electrical/
    |       +-- Instrumentation/
    |
    +-- 03_Manifold_Area/
    |       +-- [Discipline folders]
    |
    +-- 04_Interconnecting_Piping/
            +-- [Discipline folders]
```

## Considerations

### Project-Specific Considerations
| Consideration | Details |
|---------------|---------|
| **Brownfield Integration** | Existing Sumas Terminal model must be incorporated without modification |
| **Laser Scan Data** | SOW requires use of drawings/laser scan data for as-built accuracy verification |
| **TM Model Format** | Software platform must be compatible with TM existing model or have proven exchange capability |
| **Multi-discipline Scope** | Piping, structural, electrical, I&C must coexist in coordinated model |
| **Constructability Support** | Model must support constructability reviews and construction work package development |
| **Model Turnover** | Final model becomes TM asset; plan must address turnover requirements |

### Technical Considerations
| Topic | Guidance |
|-------|----------|
| **Coordinate System** | Use TM site grid system; confirm datum points and units with TM (**TBD**) |
| **Level of Detail** | FEED: LOD 200; Detailed Design 60%: LOD 300; IFC: LOD 350-400 (**ASSUMPTION**) |
| **Clash Detection Frequency** | Weekly during peak design; 48-hour resolution target for hard clashes |
| **Model Freeze Dates** | Establish freeze dates aligned with deliverable milestones |
| **File Size Management** | Consider model splitting by area if file size impacts performance |
| **Insulation Modeling** | Model insulation envelopes for clash detection (parametric where supported) |
| **Valve Operators** | Model handwheel swing arcs and actuator envelopes |

### Coordination Requirements
| Requirement | Frequency |
|-------------|-----------|
| Model integration | Daily during peak design periods |
| Multi-discipline coordination meetings | Weekly |
| Formal design reviews using model visualization | At 30/60/90% and IFC milestones |
| Clash resolution tracking and reporting | Weekly status |
| Constructability reviews | Per milestone schedule |

## Trade-offs

### Platform Considerations
| Platform | Advantages | Disadvantages |
|----------|------------|---------------|
| **AVEVA E3D** | Industry standard for oil/gas, strong piping, good catalog | Licensing cost, learning curve |
| **Bentley OpenPlant** | Good interoperability, owner/operator adoption | Moderate learning curve |
| **AutoCAD Plant 3D** | Familiar interface, lower cost | Limited for large complex projects |

**TBD**: Confirm TM preferred/required platform and existing model format.

### Model Approach Trade-offs
| Trade-off | Options | Recommendation |
|-----------|---------|----------------|
| Single model vs. Federated | Single for small projects; Federated for multi-area | Federated by area with master assembly for PSO |
| Full detail vs. Simplified | Full for new scope; Simplified for context | Full detail for new; simplified for existing distant areas |
| Early freeze vs. Late flexibility | Early for schedule certainty; Late for design optimization | Progressive freeze by system aligned with IFC sequence |
| Manual vs. Auto-extraction | Manual for control; Auto for efficiency | Auto-extraction with manual QC check |

### Level of Detail Trade-offs
| LOD | Content | Typical Use | PSO Application |
|-----|---------|-------------|-----------------|
| LOD 200 | Approximate geometry, generic elements | Conceptual | FEED phase |
| LOD 300 | Accurate geometry, specific elements | Design development | 30-60% DD |
| LOD 350 | Fabrication-level detail | Construction documents | 90% DD |
| LOD 400 | Shop drawing detail | Fabrication | IFC |

## Examples

### Sample Model Structure
```
PSO_Project_Model/
|
+-- 00_Project_Setup/
|   +-- Coordinate_System.dgn
|   +-- Project_Standards.dgn
|   +-- Project_Templates/
|
+-- 01_Existing_Site/
|   +-- Sumas_Terminal_Existing.dgn (TM provided - reference only)
|   +-- Laser_Scan_Point_Cloud/ (if applicable)
|
+-- 02_Booster_Pump_Station/
|   +-- BPS_Civil_Structural/
|   |   +-- BPS_Foundations.dgn
|   |   +-- BPS_Steel.dgn
|   +-- BPS_Mechanical/
|   |   +-- BPS_Equipment.dgn
|   +-- BPS_Piping/
|   |   +-- BPS_Piping_Lines.dgn
|   |   +-- BPS_Pipe_Supports.dgn
|   +-- BPS_Electrical/
|   +-- BPS_Instrumentation/
|
+-- 03_Manifold_Area/
|   +-- [Similar discipline structure]
|
+-- 04_Interconnecting/
    +-- [Pipe rack and underground utilities]
```

### Sample Naming Convention
```
[Area]-[Discipline]-[System]-[Type]-[Sequence]

Examples:
BPS-PIPE-OIL-LINE-001    (Booster Pump Station, Piping, Oil system, Line, 001)
BPS-STRC-FDN-CONC-001    (Booster Pump Station, Structural, Foundation, Concrete, 001)
MAN-ELEC-PWR-TRAY-001    (Manifold Area, Electrical, Power, Cable tray, 001)
BPS-MECH-PMP-VS6-001     (Booster Pump Station, Mechanical, Pump, VS6 type, 001)

Where:
BPS = Booster Pump Station
MAN = Manifold Area
INT = Interconnecting
PIPE/STRC/ELEC/MECH/INST = Discipline codes
```
**ASSUMPTION** - Naming convention to be confirmed with TM standards.

### Common Issues to Avoid
1. Misaligned coordinate systems between existing and new model portions
2. Inconsistent naming conventions across disciplines
3. Inadequate clash detection frequency during peak design
4. Late vendor model integration causing rework
5. No clear version control procedures leading to data loss
6. Insufficient model backup strategy
7. Missing insulation and valve operator envelopes in clash detection
8. Unclear model ownership and access control
9. No defined model review checkpoints
10. Incomplete as-built update procedures

---
*Generated by 4_DOCUMENTS Agent - 2026-02-01*
