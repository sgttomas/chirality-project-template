# Guidance: DEL-02.09 Area Plans

## Document Information
| Field | Value |
|-------|-------|
| Deliverable ID | DEL-02.09 |
| Deliverable Name | Area Plans |
| Package | PKG-02 (Piping, Layout & 3D Model Engineering) |
| Revision | Draft A |
| Status | INITIALIZED |
| Date | 2026-02-01 |

## 1. Introduction

### 1.1 Purpose of This Guidance
This document provides guidance for developing the Area Plans for the Puget Sound Optimization Project (PSO). It supplements the Specification and Procedure documents with practical advice for producing detailed area plan drawings that effectively bridge overall plot plans and detailed equipment/piping arrangements.

### 1.2 Intended Audience
- Piping Engineers and Designers
- CAD Technicians
- Discipline Leads
- Design Review Participants
- Construction Planning Teams

## 2. Key Considerations

### 2.1 Understanding the Area Plan Role
Area plans serve as the primary working drawings for construction layout:

**Primary Functions:**
- Detailed layout of equipment within specific zones
- Context for equipment installation activities
- Reference for piping routing and valve access
- Coordination drawing for multi-discipline interfaces
- Basis for constructability reviews

**Level of Detail:**
- More detailed than overall plot plan
- Less detailed than equipment layout plans or GA drawings
- Focus on equipment locations and major piping
- Include access routes and safety features

### 2.2 Area Organization for PSO Project

| Area | Key Elements | Coordination Focus |
|------|--------------|-------------------|
| Booster Pump Station | 5 VS6 pumps, VFDs, local panels | Mechanical, Electrical, I&C |
| Manifold Area | 5x6 manifold, actuated valves | Process, I&C, Structural |
| Containment Area | Walls, sump tank, reinjection pumps | Civil, Process |
| Electrical Building | Building, cable routes, HVAC | Electrical, Architectural |
| Tie-In Areas | Connections to existing facilities | Operations coordination |

### 2.3 Coordination with Related Deliverables

| Deliverable | Coordination Need |
|-------------|------------------|
| DEL-02.08 (Plot Plan) | Match lines, boundary consistency |
| DEL-02.10 (Equipment Layout) | Equipment detail consistency |
| DEL-02.12 (GA Drawings) | Piping routing alignment |
| DEL-04.17 (Foundation Plans) | Foundation location verification |
| DEL-04.21 (Containment) | Containment boundary alignment |
| DEL-04.27 (Structural Plans) | Platform and support coordination |
| DEL-06.12 (Area Classification) | Hazardous area boundary alignment |
| DEL-02.28 (3D Model) | Model extraction and verification |

## 3. Best Practices

### 3.1 Drawing Development

#### 3.1.1 Area Definition
- Define logical area boundaries based on:
  - Functional groupings (pumps, manifold, etc.)
  - Construction work package alignment
  - Natural break points (roads, containment walls)
- Ensure complete coverage with no gaps
- Minimize overlap between sheets

#### 3.1.2 Scale Selection
- Use consistent scale across all area plan sheets
- Typical scales: 1:100 for detailed areas, 1:200 for larger zones
- Ensure equipment labels readable at chosen scale
- Include enlarged details for congested areas if needed

#### 3.1.3 Sheet Organization
- Organize sheets in logical sequence (geographic or functional)
- Use key plan on each sheet showing coverage
- Consistent match line locations between sheets
- Number sheets within drawing set systematically

### 3.2 Content Development

#### 3.2.1 Equipment Representation
- Show equipment footprints accurately (from datasheets/vendor data)
- Include equipment tags prominently displayed
- Show major nozzle orientations for coordination
- Include driver and auxiliary equipment locations

#### 3.2.2 Piping Representation
- Show major piping routing (typically 3" and larger)
- Include line numbers on all significant lines
- Show flow direction arrows
- Indicate valve locations with proper symbols

#### 3.2.3 Access and Safety
- Show access routes between equipment
- Verify minimum clearances for maintenance
- Include emergency egress paths
- Show safety equipment locations (if required)

### 3.3 Quality Control

#### 3.3.1 Self-Check Questions
Before submitting for review, verify:
- [ ] All equipment from equipment list shown?
- [ ] Equipment locations match 3D model?
- [ ] Major piping routing shown with line numbers?
- [ ] Valve locations shown and accessible?
- [ ] Match lines coordinate with adjacent drawings?
- [ ] Key plan accurate for sheet coverage?
- [ ] Coordinate grid complete and labeled?
- [ ] Legend complete for all symbols used?

#### 3.3.2 Common Issues to Avoid
| Issue | Prevention |
|-------|------------|
| Equipment overlaps | Extract from coordinated 3D model |
| Missing match lines | Plan sheet coverage before development |
| Inconsistent scale | Establish scale standard at project start |
| Missing equipment | Cross-check against equipment list |
| Access blocked | Verify clearances in 3D model |

## 4. Common Challenges and Solutions

### 4.1 Congested Areas
**Challenge:** Pump station and manifold areas have high equipment density.

**Solutions:**
- Use larger scale (1:50) for inset details
- Provide section views for vertical congestion
- Reference detailed equipment layout drawings
- Consider separate sheets for complex areas

### 4.2 Multi-Discipline Coordination
**Challenge:** Area plans require input from many disciplines.

**Solutions:**
- Establish area plan as coordination document
- Hold regular coordination meetings by area
- Use 3D model as single source of truth
- Document and resolve conflicts promptly

### 4.3 Design Evolution
**Challenge:** Layout changes during design development.

**Solutions:**
- Update area plans with each design revision
- Maintain link to 3D model for updates
- Track changes through revision control
- Communicate changes to affected disciplines

### 4.4 Vendor Data Integration
**Challenge:** Equipment dimensions change with vendor data.

**Solutions:**
- Use preliminary sizing for FEED
- Plan for updates during detailed design
- Maintain dimensional flexibility where possible
- Track vendor data status and incorporation

## 5. Constructability Considerations

### 5.1 Construction Sequence
When developing area plans, consider:
- Module or pre-assembly opportunities
- Equipment installation sequence
- Crane access and lifting requirements
- Material laydown areas

### 5.2 Access Requirements
- Maintenance access for equipment service
- Valve handwheel access (standing or platform)
- Instrument access for calibration/maintenance
- Emergency egress routes

### 5.3 Interface with Existing Facilities
- Clear delineation of tie-in boundaries
- Temporary construction interfaces
- Operational interfaces during construction
- Isolation requirements

## 6. Review and Approval

### 6.1 Internal Review Focus Areas
| Reviewer | Focus Areas |
|----------|-------------|
| Piping Lead | Equipment layout, piping routing optimization |
| Process | Process requirements met, operability |
| Mechanical | Equipment access, maintenance provisions |
| Civil/Structural | Foundation alignment, structural coordination |
| Electrical | Area classification, cable routes |
| I&C | Instrument access, control panel locations |
| Construction | Constructability, sequencing |

### 6.2 Client Review Considerations
- Verify alignment with TM operations preferences
- Confirm maintenance access meets TM standards
- Address any regulatory or permit requirements
- Coordinate with TM existing facility drawings

## 7. Documentation and Traceability

### 7.1 Records to Maintain
- Working files and coordination drafts
- Discipline coordination comments
- Change history documentation
- 3D model revision correlation

### 7.2 Cross-References
Ensure proper cross-referencing to:
- Overall plot plan (DEL-02.08)
- Equipment layout plans (DEL-02.10)
- GA drawings (DEL-02.12)
- Foundation plans (DEL-04.17)
- 3D model (DEL-02.28)

## 8. Assumptions and TBD Resolution

### 8.1 Current Assumptions
| ID | Assumption | Resolution Path |
|----|------------|-----------------|
| A1 | 4-5 area plan sheets required | Verify during layout development |
| A2 | 1:100 scale suitable for most areas | Verify during development |
| A3 | Consistent sheet organization across set | Establish at project start |
| A4 | 3D model available for extraction | Coordinate with 3D modeling team |

### 8.2 TBD Items for Resolution
| ID | TBD Item | Owner | Target Resolution |
|----|----------|-------|-------------------|
| T1 | Number of sheets required | Piping Lead | Early FEED |
| T2 | Area boundary definitions | Piping Lead | Early FEED |
| T3 | TM CAD standards | TM | Prior to development |
| T4 | Hazardous area boundaries | Electrical | During FEED |
| T5 | Platform/access requirements | Structural | During FEED |

## 9. Source References
- Decomposition: Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md
- SOW: Exhibit A - Scope of Work PS.pdf, Sections 2.3.1, 3.2.4.8
- DBM: Puget Sound Optimization Project DBM.pdf
- Appendix A-1: PSO - ST - New Utility Area - Proposed Layout
- Scope Items: SOW-0247
