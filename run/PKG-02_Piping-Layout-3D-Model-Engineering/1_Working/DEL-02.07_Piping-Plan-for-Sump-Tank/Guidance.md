# Guidance: DEL-02.07 Piping Plan for Sump Tank

## Document Information
| Field | Value |
|-------|-------|
| Deliverable ID | DEL-02.07 |
| Deliverable Name | Piping Plan for Sump Tank |
| Package | PKG-02 (Piping, Layout & 3D Model Engineering) |
| Revision | Draft A |
| Status | INITIALIZED |
| Date | 2026-02-01 |

## 1. Introduction

### 1.1 Purpose of This Guidance
This document provides guidance for developing the Piping Plan for Sump Tank for the Puget Sound Optimization Project (PSO). It supplements the Specification and Procedure documents with practical advice for producing high-quality sump tank piping drawings.

### 1.2 Intended Audience
- Piping Engineers and Designers
- CAD Technicians
- Discipline Leads
- Design Review Participants

## 2. Key Considerations

### 2.1 Understanding the Sump Tank System
The sump tank system is a critical component of the booster pump station infrastructure:

**Primary Functions:**
- Collection of drainage from secondary containment areas
- Holding tank for hydrocarbon-contaminated water
- Source for reinjection pumps returning oil to process
- Interface with dewatering equipment for water separation

**Key Design Considerations:**
- Adequate capacity for containment drainage events
- Proper pump suction conditions (NPSH)
- Level instrumentation for automatic pump operation
- Vent sizing for filling/emptying operations
- Maintenance access for pump service

### 2.2 Coordination with Related Systems

| System | Coordination Requirement |
|--------|-------------------------|
| Secondary Containment | Drain piping routing and sizing from containment walls |
| Booster Pumps | Seal drain or other drainage connections |
| Manifold Area | Drainage collection from manifold piping area |
| Process Returns | Reinjection destination (tanks or process) |
| Dewatering | Oil/water separation and water disposal |

### 2.3 Related Deliverables Coordination

| Deliverable | Coordination Need |
|-------------|------------------|
| DEL-01.03 (P&IDs) | System definition and line/valve requirements |
| DEL-01.09 (Process Datasheets) | Tank and pump process conditions |
| DEL-02.12 (GA Drawings) | Context within overall piping layout |
| DEL-02.13 (Isometrics) | Detailed piping routing |
| DEL-03.01 (Equipment List) | Tank and pump specifications |
| DEL-04.21 (Containment Plans) | Drain connection locations |
| DEL-07.04 (Instrument Location) | Instrumentation coordination |

## 3. Best Practices

### 3.1 Layout Considerations

#### 3.1.1 Tank Positioning
- Locate tank at low point of containment area for gravity drainage
- Consider maintenance access requirements (minimum clearances)
- Allow space for pump removal and service
- Consider future expansion potential

#### 3.1.2 Pump Arrangement
- Position pumps to minimize suction line length
- Ensure adequate NPSH margin
- Provide isolation valves for pump maintenance
- Consider spare pump requirements (if applicable)
- Orient pumps for easy maintenance access

#### 3.1.3 Piping Routing
- Slope drain piping toward tank (minimum 1:100 recommended)
- Minimize pressure drop in suction lines
- Provide proper venting to prevent vapor lock
- Include sample points for fluid characterization
- Consider freeze protection requirements

### 3.2 Drawing Development

#### 3.2.1 Plan View Organization
- Show sufficient context (adjacent equipment, containment boundaries)
- Dimension from established grid references
- Clearly identify all equipment and major piping
- Use consistent orientation with other site drawings

#### 3.2.2 Sections and Details
- Include at least one elevation/section for vertical clarity
- Show pump elevations relative to tank levels
- Detail complex connections or transitions
- Reference standard details where applicable

#### 3.2.3 Clarity and Completeness
- All items on P&ID must appear on plan
- All valves tagged and identified
- Instrument connections shown with process connections
- Support locations referenced or shown

### 3.3 Safety and Operability

#### 3.3.1 Safety Considerations
- Overflow provisions to prevent tank overfill
- Vent sizing for worst-case inflow
- High-level alarm provisions
- Emergency pump stop locations (coordinate with I&C)
- Confined space entry considerations

#### 3.3.2 Operability Features
- Manual drain provisions
- Local level indication
- Sample points for fluid testing
- Maintenance isolation capabilities
- Winterization/heat tracing provisions

## 4. Common Challenges and Solutions

### 4.1 Drainage System Sizing
**Challenge:** Ensuring adequate drainage capacity for containment areas.

**Solutions:**
- Coordinate with process/civil for drainage design criteria
- Consider worst-case scenarios (fire water, rain, spill events)
- Size drain piping for gravity flow at required rates
- Provide multiple drain points for large containment areas

### 4.2 Pump NPSH Requirements
**Challenge:** Ensuring adequate pump suction conditions.

**Solutions:**
- Locate tank to provide maximum static head
- Minimize suction line length and fittings
- Size suction piping generously
- Include strainers with adequate area to prevent clogging
- Consider operating temperature effects on NPSH

### 4.3 Winterization
**Challenge:** Preventing freeze damage in cold weather.

**Solutions:**
- Include heat tracing on exposed piping
- Consider insulation requirements
- Provide drain-down provisions for extended shutdowns
- Locate instrumentation in heated enclosures if required

### 4.4 Vendor Data Timing
**Challenge:** Equipment data may not be available during early design.

**Solutions:**
- Use preliminary equipment sizing for FEED layout
- Design with flexibility for vendor data updates
- Clearly note assumptions and preliminary dimensions
- Update during detailed design when vendor data available

## 5. Quality Self-Check

### 5.1 Pre-Submission Checklist
Before submitting for review, verify:

- [ ] All P&ID items represented on drawing?
- [ ] Equipment dimensions match datasheets/vendor data?
- [ ] All nozzles shown with correct size/orientation?
- [ ] Valve tags match P&ID and valve list?
- [ ] Instrument connections shown and tagged?
- [ ] Pipe support locations indicated?
- [ ] Adequate maintenance access provided?
- [ ] Dimensions complete for construction use?
- [ ] Drawing references complete and accurate?
- [ ] Legend includes all symbols used?

### 5.2 Common Issues to Avoid
| Issue | Prevention |
|-------|------------|
| Missing drain points | Cross-check against containment areas |
| Insufficient access | Review with operations/maintenance |
| NPSH problems | Verify pump suction conditions |
| Missing instrument connections | Coordinate with I&C |
| Structural conflicts | Check against foundation/structural plans |

## 6. Coordination Meetings

### 6.1 Recommended Coordination Sessions
| Session | Participants | Purpose |
|---------|--------------|---------|
| Process coordination | Process, Piping | Confirm P&ID requirements and process data |
| Equipment coordination | Mechanical, Piping | Confirm equipment data and connections |
| Structural coordination | Civil/Structural, Piping | Confirm foundation and support locations |
| I&C coordination | I&C, Piping | Confirm instrument connection requirements |
| 3D model review | All disciplines | Verify spatial arrangement and clearances |

## 7. Assumptions and TBD Resolution

### 7.1 Current Assumptions
| ID | Assumption | Resolution Path |
|----|------------|-----------------|
| A1 | Sump tank serves booster station containment | Confirm with process |
| A2 | Reinjection returns to process/storage | Confirm destination with process |
| A3 | Standard piping materials apply | Confirm material class with piping materials |
| A4 | Heat tracing required for winter operation | Confirm with process/operations |

### 7.2 TBD Items for Resolution
| ID | TBD Item | Owner | Target Resolution |
|----|----------|-------|-------------------|
| T1 | Sump tank size/capacity | Process | FEED |
| T2 | Number of reinjection pumps | Process/Mechanical | FEED |
| T3 | Dewatering equipment type | Process/Mechanical | FEED |
| T4 | Material class | Piping Materials | FEED |
| T5 | Instrumentation requirements | I&C | FEED |

## 8. Source References
- Decomposition: Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md
- SOW: Exhibit A - Scope of Work PS.pdf
- Scope Items: SOW-0125, SOW-0226
- Related Deliverables: DEL-01.03, DEL-02.12, DEL-03.01, DEL-04.21
