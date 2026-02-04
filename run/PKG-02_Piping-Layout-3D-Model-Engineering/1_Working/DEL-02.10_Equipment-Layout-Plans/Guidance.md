# Guidance: DEL-02.10 Equipment Layout Plans

## Document Information
| Field | Value |
|-------|-------|
| Deliverable ID | DEL-02.10 |
| Deliverable Name | Equipment Layout Plans |
| Package | PKG-02 (Piping, Layout & 3D Model Engineering) |
| Revision | Draft A |
| Status | INITIALIZED |
| Date | 2026-02-01 |

## 1. Introduction

### 1.1 Purpose of This Guidance
This document provides guidance for developing the Equipment Layout Plans for the Puget Sound Optimization Project (PSO). It supplements the Specification and Procedure documents with practical advice for producing detailed equipment arrangement drawings that support procurement, foundation design, piping design, and installation.

### 1.2 Intended Audience
- Piping Engineers and Designers
- Mechanical Engineers
- CAD Technicians
- Discipline Leads
- Procurement Teams
- Construction Planning Teams

## 2. Key Considerations

### 2.1 Understanding Equipment Layout Plan Role
Equipment layout plans serve as the critical interface between equipment vendor data and site design:

**Primary Functions:**
- Document equipment physical arrangement
- Define foundation interface requirements
- Provide nozzle data for piping design
- Establish maintenance access requirements
- Support procurement and installation planning

**Relationship to Other Deliverables:**
- More detailed than area plans (DEL-02.09)
- Foundation design input (DEL-04.17, DEL-04.18)
- Basis for piping GA drawings (DEL-02.12)
- Extracted from 3D model (DEL-02.28)

### 2.2 PSO Project Equipment
The project includes the following major equipment:

| Equipment | Key Design Features | Layout Considerations |
|-----------|---------------------|----------------------|
| VS6 Booster Pumps (5) | Vertical suction, variable capacity | Suction piping, maintenance access |
| 5x6 Manifold | Multiple headers, actuated valves | Valve access, actuator orientation |
| Sump Tank | Containment drainage collection | Drain piping, level instrumentation |
| Reinjection Pumps | Return to process | NPSH, maintenance access |
| VFDs | Motor control | Cable routing, cooling |

### 2.3 Coordination with Related Deliverables

| Deliverable | Coordination Need |
|-------------|------------------|
| DEL-02.09 (Area Plans) | Equipment location consistency |
| DEL-02.12 (GA Drawings) | Nozzle orientations for piping |
| DEL-03.01 (Equipment List) | Equipment identification |
| DEL-03.02 (Equipment Datasheets) | Equipment specifications |
| DEL-03.04 (Vendor Data) | Certified dimensional data |
| DEL-04.17 (Foundation Plans) | Foundation coordination |
| DEL-04.18 (Foundation Details) | Anchor bolt patterns |
| DEL-02.28 (3D Model) | Model verification |

## 3. Best Practices

### 3.1 Vendor Data Management

#### 3.1.1 FEED Phase (Preliminary Data)
- Use preliminary/budgetary equipment data for initial layouts
- Clearly mark drawings as "PRELIMINARY - SUBJECT TO VENDOR DATA"
- Include dimensional allowances for vendor variations
- Document assumptions for later verification

#### 3.1.2 Detailed Design Phase (Certified Data)
- Update layouts with certified vendor dimensional data
- Verify anchor bolt patterns against vendor certified drawings
- Update nozzle schedules with vendor data
- Confirm maintenance clearance requirements

#### 3.1.3 Data Tracking
Maintain a log of vendor data status:
| Equipment | Preliminary Data | Budgetary Dwg | Certified Dwg | Layout Updated |
|-----------|------------------|---------------|---------------|----------------|
| Pump 1 | Date | Date | Date | Date |
| ... | ... | ... | ... | ... |

### 3.2 Drawing Development

#### 3.2.1 Equipment Representation
- Use accurate outlines from vendor data (not simplified symbols)
- Show true equipment footprint and envelope
- Include all major components (drivers, auxiliaries)
- Show equipment orientation clearly

#### 3.2.2 Nozzle Documentation
- Show all process nozzles with clear identification
- Document nozzle size, rating, and facing
- Show orientation (degrees or cardinal directions)
- Include elevation references

#### 3.2.3 Foundation Interface
- Show anchor bolt patterns from vendor data
- Include baseplate outline
- Reference foundation drawing for details
- Note grout requirements

#### 3.2.4 Clearance Requirements
- Show minimum maintenance clearances
- Include component removal paths (pump rotors, etc.)
- Verify against vendor O&M requirements
- Consider construction access needs

### 3.3 Quality Control

#### 3.3.1 Self-Check Questions
Before submitting for review, verify:
- [ ] Equipment outline matches vendor data?
- [ ] All nozzles shown with correct identification?
- [ ] Nozzle schedule complete and accurate?
- [ ] Anchor bolt pattern from vendor data?
- [ ] Maintenance clearances verified?
- [ ] Elevations referenced to project datum?
- [ ] Cross-references to related drawings correct?
- [ ] Legend complete for all symbols used?

#### 3.3.2 Common Issues to Avoid
| Issue | Prevention |
|-------|------------|
| Outdated vendor data | Track vendor data versions |
| Missing nozzles | Cross-check against P&ID |
| Incorrect anchor bolts | Verify against certified data |
| Insufficient clearances | Review vendor O&M requirements |
| Inconsistent orientations | Verify against 3D model |

## 4. Common Challenges and Solutions

### 4.1 Vendor Data Timing
**Challenge:** Equipment vendor data not available during FEED.

**Solutions:**
- Use preliminary/budgetary data for initial layout
- Include dimensional contingency in layout
- Clearly mark as preliminary
- Plan for update cycle when vendor data received

### 4.2 Multiple Equipment Vendors
**Challenge:** Different pumps may come from different vendors.

**Solutions:**
- Track vendor data status for each equipment item
- Standardize layout format regardless of vendor
- Coordinate nozzle orientations for piping optimization
- Document any vendor-specific requirements

### 4.3 Nozzle Orientation Optimization
**Challenge:** Optimizing nozzle orientations for piping design.

**Solutions:**
- Coordinate early with piping routing
- Consider pump rotation flexibility with vendor
- Optimize for maintenance access
- Document orientation requirements in RFQ/PO

### 4.4 Maintenance Access Conflicts
**Challenge:** Limited space for maintenance activities.

**Solutions:**
- Review vendor O&M manual requirements
- Verify pull space for rotating elements
- Coordinate with structural for platforms
- Consider monorail/hoist requirements

## 5. VS6 Booster Pump Layout Considerations

### 5.1 Typical VS6 Pump Layout Elements
- Vertical suction orientation
- Top discharge (or side discharge depending on model)
- Motor mounted above pump
- Possible VFD on pump structure or separate
- Seal system connections

### 5.2 Key Layout Dimensions
- Overall height for structural clearances
- Suction/discharge nozzle elevations
- Motor rotation and orientation
- Coupling access for maintenance
- Seal system piping connections

### 5.3 Maintenance Considerations
- Pump/motor removal access (overhead)
- Seal replacement access
- Bearing maintenance access
- Local control/instrumentation access

## 6. Manifold Layout Considerations

### 6.1 Key Layout Elements
- Header arrangement (5 suction, 6 discharge)
- Actuated valve spacing
- Actuator orientation for access
- Support locations
- Instrument connections

### 6.2 Access Requirements
- Valve handwheel/actuator access
- Actuator maintenance access
- Instrumentation access
- Potential future expansion

## 7. Review and Approval

### 7.1 Internal Review Focus Areas
| Reviewer | Focus Areas |
|----------|-------------|
| Piping Lead | Nozzle orientations, piping access |
| Mechanical Lead | Equipment data accuracy, vendor coordination |
| Civil/Structural Lead | Foundation interface, structural supports |
| Electrical Lead | Motor orientation, cable access |
| Operations (if available) | Maintenance access, operability |

### 7.2 Vendor Data Verification
- Compare layout against certified vendor drawings
- Verify all dimensions and nozzle data
- Confirm anchor bolt patterns
- Document any discrepancies for resolution

## 8. Documentation and Traceability

### 8.1 Records to Maintain
- Vendor data receipt log
- Layout revision correlation to vendor data
- Coordination meeting notes
- Comment resolution logs

### 8.2 Cross-References
Ensure proper cross-referencing to:
- Equipment datasheets (DEL-03.02)
- Foundation details (DEL-04.18)
- Piping GA drawings (DEL-02.12)
- Vendor certified drawings

## 9. Assumptions and TBD Resolution

### 9.1 Current Assumptions
| ID | Assumption | Resolution Path |
|----|------------|-----------------|
| A1 | VS6 pumps are vertically oriented | Confirm with pump specification |
| A2 | VFDs mounted separately (not on pump) | Confirm with electrical/mechanical |
| A3 | Preliminary sizing adequate for FEED layout | Confirm with process/mechanical |
| A4 | Standard maintenance clearances apply | Verify with vendor O&M |

### 9.2 TBD Items for Resolution
| ID | TBD Item | Owner | Target Resolution |
|----|----------|-------|-------------------|
| T1 | Pump vendor selection | Procurement | FEED |
| T2 | Certified pump dimensions | Mechanical | Detailed Design |
| T3 | VFD arrangement | Electrical | FEED |
| T4 | Sump tank sizing | Process | FEED |
| T5 | Reinjection pump selection | Mechanical | FEED |

## 10. Source References
- Decomposition: Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md
- SOW: Exhibit A - Scope of Work PS.pdf, Sections 2.3.1, 3.2.4.8
- DBM: Puget Sound Optimization Project DBM.pdf
- Scope Items: SOW-0247
