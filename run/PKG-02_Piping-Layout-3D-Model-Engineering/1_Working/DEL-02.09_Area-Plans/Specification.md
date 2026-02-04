# Specification: DEL-02.09 Area Plans

## Document Information
| Field | Value |
|-------|-------|
| Deliverable ID | DEL-02.09 |
| Deliverable Name | Area Plans |
| Package | PKG-02 (Piping, Layout & 3D Model Engineering) |
| Revision | Draft A |
| Status | INITIALIZED |
| Date | 2026-02-01 |

## 1. Purpose and Scope

### 1.1 Purpose
This specification defines the requirements for the Area Plan drawing(s) to be developed as part of the Puget Sound Optimization Project (PSO) at Sumas Tank Farm. The area plans shall provide detailed plan views of specific project zones, bridging the overall plot plan and detailed equipment/piping arrangements.

### 1.2 Scope
The Area Plans shall cover:
- Booster pump station area
- Manifold area
- Containment and sump system area
- Electrical building area
- Tie-in and interface areas with existing facilities

### 1.3 Exclusions
- Detailed equipment internal arrangements (covered by vendor drawings)
- Detailed piping isometrics (covered by DEL-02.13)
- Civil/structural detail drawings (covered by PKG-04)

## 2. Technical Requirements

### 2.1 Drawing Content Requirements

#### 2.1.1 General Requirements
| Requirement | Specification |
|-------------|---------------|
| Drawing Size | TBD (per TM CAD standards, typically D-size or E-size) |
| Scale | Appropriate for area detail (typically 1:100 or 1:200) |
| Orientation | North arrow required, consistent with plot plan |
| Title Block | Per TM document control requirements |
| Revision Block | Per TM document control requirements |

#### 2.1.2 Area Coverage
Each area plan sheet shall include:

1. **Equipment Representation**
   - Equipment outlines with accurate footprints
   - Equipment tags and identifications
   - Nozzle orientations (major equipment)
   - Driver and auxiliary equipment locations

2. **Piping Systems**
   - Major piping routing (centerlines)
   - Line numbers and flow directions
   - Valve locations with tags
   - Instrumentation taps and connections

3. **Structural Elements**
   - Building outlines and entrances
   - Platform and walkway locations
   - Pipe support locations (reference)
   - Foundation outlines

4. **Safety and Access**
   - Access routes and egress paths
   - Emergency equipment locations
   - Safety shower/eyewash (if required)
   - Hazardous area boundaries (or reference)

5. **Reference Information**
   - Coordinate grid with labels
   - Match lines to adjacent sheets
   - Reference to plot plan
   - Key plan showing coverage

#### 2.1.3 Area-Specific Content

**Booster Pump Station Area:**
- Five VS6 pump locations (2 large, 2 small, 1 medium)
- VFD/motor locations
- Local control panels
- Suction and discharge piping
- Cooling/seal systems (if applicable)

**Manifold Area:**
- 5x6 manifold arrangement
- Actuated valve locations
- Header piping arrangement
- Instrumentation locations
- Access platforms

**Containment Area:**
- Containment wall extents
- Sump tank location
- Reinjection pump location
- Drain piping routing
- Vent systems

**Electrical Building Area:**
- Building footprint and entrances
- Cable routing corridors
- Grounding system (reference)
- HVAC equipment (if applicable)

### 2.2 Dimensional Requirements

| Dimension Type | Requirement |
|----------------|-------------|
| Equipment coordinates | Reference to site grid |
| Equipment spacing | Critical clearances dimensioned |
| Access widths | Minimum clearances shown |
| Elevations | Reference to project datum |
| Match line coordinates | Shown at boundaries |

### 2.3 Symbology and Notation

#### 2.3.1 Equipment Symbology
- Standard symbols per TM CAD standards
- Equipment tags prominently displayed
- Consistent representation across sheets
- ASSUMPTION: TM symbology library applies

#### 2.3.2 Piping Symbology
- Line weights per pipe size (or consistent weight)
- Flow direction arrows
- Line number labels
- Valve symbols per project standards

#### 2.3.3 Standard Notations
- North arrow on each sheet
- Scale notation (both ratio and graphic)
- Revision notation
- Drawing references

### 2.4 Coordination Requirements

#### 2.4.1 Drawing Set Coordination
| Drawing | Coordination Requirement |
|---------|-------------------------|
| DEL-02.08 (Plot Plan) | Match lines, boundary consistency |
| DEL-02.10 (Equipment Layout) | Equipment location consistency |
| DEL-02.12 (GA Drawings) | Piping routing consistency |
| DEL-04.xx (Civil drawings) | Foundation, grading alignment |
| DEL-06.xx (Electrical drawings) | Area classification, cable routes |

#### 2.4.2 3D Model Integration
- Area plans shall be extracted from or verified against 3D model
- Any 2D-only additions shall be incorporated into 3D model
- Clash detection to verify clearances

## 3. Quality Requirements

### 3.1 Accuracy Requirements
| Requirement | Specification |
|-------------|---------------|
| Coordinate accuracy | Per survey datum tolerance |
| Equipment placement | Within model tolerance |
| Completeness | All area features represented |
| Consistency | Aligned with related drawings |

### 3.2 Checking Requirements
- Internal discipline check per DEL-00.03
- Inter-discipline coordination check
- 3D model consistency check
- Compliance check against TM CAD standards

### 3.3 Deliverable Quality Criteria
- Complete representation of each area
- Consistent symbology across all sheets
- Proper cross-referencing to related drawings
- Clear, readable at issued scale

## 4. Deliverable Format

### 4.1 Native Files
| Format | Description |
|--------|-------------|
| CAD native format | TBD (per TM CAD standards) |
| 3D model extract | Plan views from sitewide model |

### 4.2 Issued Documents
| Format | Description |
|--------|-------------|
| PDF | Issued drawings in PDF format |
| Plot files | As required per TM submission requirements |

### 4.3 Naming Convention
- Per TM document numbering system (reference DEL-00.02)
- TBD: Specific document number format and sheet numbering

## 5. Revision and Approval

### 5.1 Revision Cycle
| Phase | Revision | Description |
|-------|----------|-------------|
| FEED | IFR | Initial issue for review |
| FEED | IFD | Issued for Design (end of FEED) |
| Detailed Design | IFC | Issued for Construction |

### 5.2 Approval Requirements
- Piping Lead approval
- Multi-discipline coordination sign-off
- TM review and comment resolution

## 6. Applicable Standards
| Standard | Application |
|----------|-------------|
| CSA Z662 | Oil and gas pipeline systems |
| API 2610 | Tank farm design reference |
| OSHA 1910 | Walking-working surfaces |
| TMP Standards and Specifications | Project-specific requirements |
| TM CAD Standards | Drawing format and production |

## 7. Assumptions
1. ASSUMPTION: Multiple sheets organized by distinct areas.
2. ASSUMPTION: Consistent scale across area plan sheets.
3. ASSUMPTION: TM CAD standards and templates will be provided.
4. ASSUMPTION: 3D model available for plan extraction.

## 8. TBD Items
1. TBD: Number of area plan sheets required.
2. TBD: Specific area boundaries and designations.
3. TBD: TM CAD standards and templates.
4. TBD: Document numbering convention.
5. TBD: Hazardous area classification details.
6. TBD: Platform and access requirements.

## 9. Source References
- Decomposition: Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md
- SOW: Exhibit A - Scope of Work PS.pdf
- DBM: Puget Sound Optimization Project DBM.pdf
- Scope Items: SOW-0247
