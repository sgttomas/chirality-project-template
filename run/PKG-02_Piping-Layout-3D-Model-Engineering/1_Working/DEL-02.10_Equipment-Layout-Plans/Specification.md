# Specification: DEL-02.10 Equipment Layout Plans

## Document Information
| Field | Value |
|-------|-------|
| Deliverable ID | DEL-02.10 |
| Deliverable Name | Equipment Layout Plans |
| Package | PKG-02 (Piping, Layout & 3D Model Engineering) |
| Revision | Draft A |
| Status | INITIALIZED |
| Date | 2026-02-01 |

## 1. Purpose and Scope

### 1.1 Purpose
This specification defines the requirements for the Equipment Layout Plan drawing(s) to be developed as part of the Puget Sound Optimization Project (PSO) at Sumas Tank Farm. The equipment layout plans shall provide detailed arrangement information for major mechanical equipment supporting procurement, foundation design, piping design, and installation.

### 1.2 Scope
The Equipment Layout Plans shall cover:
- Five VS6 booster pumps (2 large, 2 small, 1 medium capacity)
- 5x6 manifold system with actuated valves
- Sump tank and reinjection pump system
- VFDs and motors
- Associated auxiliary equipment (lube systems, seal systems, etc.)

### 1.3 Exclusions
- Vendor internal equipment drawings (provided by vendors)
- Electrical equipment layouts (covered by PKG-06)
- Instrumentation layouts (covered by PKG-07)
- Structural steel details (covered by PKG-04)

## 2. Technical Requirements

### 2.1 Drawing Content Requirements

#### 2.1.1 General Requirements
| Requirement | Specification |
|-------------|---------------|
| Drawing Size | TBD (per TM CAD standards, typically D-size or E-size) |
| Scale | Appropriate for equipment detail (typically 1:50 or 1:25) |
| Orientation | North arrow required, consistent with area plans |
| Title Block | Per TM document control requirements |
| Revision Block | Per TM document control requirements |

#### 2.1.2 Plan View Content
Each equipment layout shall include:

1. **Equipment Representation**
   - Accurate equipment outline from vendor data
   - Equipment tag and description
   - Overall dimensions (L x W x H)
   - Centerline and reference point identification

2. **Nozzle Information**
   - All process nozzle locations
   - Nozzle identification (matching vendor data)
   - Nozzle size and rating
   - Nozzle facing/orientation
   - Flange type notation

3. **Foundation Interface**
   - Anchor bolt pattern (from vendor data)
   - Baseplate outline
   - Grout requirements notation
   - Reference to foundation details

4. **Access and Clearances**
   - Maintenance clearance requirements
   - Removal/pull space for components
   - Access platform references
   - Lifting provisions

5. **Auxiliary Equipment**
   - Driver (motor) location and orientation
   - Coupling/spacer details (reference)
   - Lube oil system location (if applicable)
   - Seal system location (if applicable)
   - Local instrumentation/controls

#### 2.1.3 Elevation/Section Views
Include as required to show:
- Equipment height and key elevations
- Nozzle elevations
- Suction/discharge centerlines
- Platform and access elevations
- Clearances for maintenance operations

#### 2.1.4 Nozzle Schedule
Each equipment layout shall include or reference:
| Column | Content |
|--------|---------|
| Nozzle Mark | Vendor nozzle identification |
| Service | Process service description |
| Size | Nominal pipe size |
| Rating | Pressure class |
| Facing | Raised face, RTJ, etc. |
| Orientation | Degrees from reference or cardinal direction |
| Elevation | Height above reference datum |

### 2.2 Equipment-Specific Requirements

#### 2.2.1 Booster Pumps (VS6)
| Requirement | Details |
|-------------|---------|
| Pump outline | Per vendor certified drawings |
| Motor/driver | Location and orientation |
| Suction nozzle | Location, size, rating, elevation |
| Discharge nozzle | Location, size, rating, elevation |
| Seal system | Location and connections |
| Cooling connections | If applicable |
| Drain/vent points | Locations |
| Anchor bolts | Pattern and size from vendor |

#### 2.2.2 Manifold System
| Requirement | Details |
|-------------|---------|
| Header arrangement | 5 suction, 6 discharge headers |
| Valve locations | All actuated valve positions |
| Actuator orientation | For access and cable routing |
| Support locations | Pipe support points |
| Access requirements | Valve operation and maintenance |

#### 2.2.3 Sump Tank System
| Requirement | Details |
|-------------|---------|
| Tank outline | From vendor or preliminary sizing |
| Nozzle arrangement | All tank connections |
| Pump locations | Reinjection pump arrangement |
| Drain connections | From containment |
| Vent connections | Tank ventilation |
| Level instrumentation | Connection points |

### 2.3 Dimensional Requirements

| Dimension Type | Requirement |
|----------------|-------------|
| Equipment coordinates | Reference to site grid |
| Centerline locations | From grid references |
| Nozzle coordinates | From equipment centerline |
| Elevations | From project datum (e.g., bottom of baseplate) |
| Clearances | Minimum maintenance clearances |
| Anchor bolt pattern | From vendor certified data |

### 2.4 Coordination Requirements

#### 2.4.1 Vendor Data Integration
- Equipment outlines from certified vendor drawings
- Nozzle schedules from vendor data
- Anchor bolt patterns from vendor data
- Weight data for foundation design
- Maintenance requirements from vendor O&M

#### 2.4.2 Discipline Coordination
| Discipline | Coordination Requirement |
|------------|-------------------------|
| Mechanical | Equipment datasheets and vendor data |
| Civil/Structural | Foundation design input |
| Piping | Nozzle locations for piping design |
| Electrical | Motor locations for cable routing |
| I&C | Local instrumentation locations |
| 3D Model | Model verification and extraction |

## 3. Quality Requirements

### 3.1 Accuracy Requirements
| Requirement | Specification |
|-------------|---------------|
| Dimensional accuracy | Match vendor certified drawings |
| Coordinate accuracy | Per survey datum tolerance |
| Completeness | All equipment items represented |
| Consistency | Match equipment datasheets |

### 3.2 Checking Requirements
- Verification against vendor certified drawings
- Internal discipline check per DEL-00.03
- Inter-discipline coordination check
- 3D model consistency check

### 3.3 Deliverable Quality Criteria
- All equipment accurately represented
- Nozzle schedules complete and accurate
- Foundation interface data complete
- Maintenance clearances verified

## 4. Deliverable Format

### 4.1 Native Files
| Format | Description |
|--------|-------------|
| CAD native format | TBD (per TM CAD standards) |
| 3D model extract | Equipment views from sitewide model |

### 4.2 Issued Documents
| Format | Description |
|--------|-------------|
| PDF | Issued drawings in PDF format |
| Plot files | As required per TM submission requirements |

### 4.3 Naming Convention
- Per TM document numbering system (reference DEL-00.02)
- TBD: Specific document number format

## 5. Revision and Approval

### 5.1 Revision Cycle
| Phase | Revision | Description |
|-------|----------|-------------|
| FEED | IFR | Based on preliminary equipment data |
| FEED | IFD | Updated with available vendor data |
| Detailed Design | IFC | Final with certified vendor data |

### 5.2 Approval Requirements
- Piping Lead approval
- Mechanical Lead review for equipment data
- Civil/Structural review for foundation interface
- TM review and comment resolution

## 6. Applicable Standards
| Standard | Application |
|----------|-------------|
| CSA Z662 | Oil and gas pipeline systems |
| API 610 | Centrifugal pump design |
| API 674/675 | Positive displacement pumps |
| NEMA | Motor dimensions |
| TMP Standards and Specifications | Project-specific requirements |
| TM CAD Standards | Drawing format and production |

## 7. Assumptions
1. ASSUMPTION: Equipment vendor selection will occur during FEED.
2. ASSUMPTION: Preliminary equipment sizing available for FEED start.
3. ASSUMPTION: TM CAD standards and templates will be provided.
4. ASSUMPTION: 3D model will be used for layout development.

## 8. TBD Items
1. TBD: Equipment vendor selection and certified data.
2. TBD: Final pump dimensions and nozzle schedules.
3. TBD: VFD/motor specifications and dimensions.
4. TBD: Sump tank design and dimensions.
5. TBD: TM CAD standards and templates.
6. TBD: Document numbering convention.

## 9. Source References
- Decomposition: Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md
- SOW: Exhibit A - Scope of Work PS.pdf
- DBM: Puget Sound Optimization Project DBM.pdf
- Scope Items: SOW-0247
