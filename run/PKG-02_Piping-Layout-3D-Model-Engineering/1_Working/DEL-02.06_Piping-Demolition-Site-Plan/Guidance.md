# Guidance: DEL-02.06 Piping Demolition Site Plan

## Document Information
| Field | Value |
|-------|-------|
| Deliverable ID | DEL-02.06 |
| Deliverable Name | Piping Demolition Site Plan |
| Package | PKG-02 (Piping, Layout & 3D Model Engineering) |
| Revision | Draft A |
| Status | INITIALIZED |
| Date | 2026-02-01 |

## 1. Introduction

### 1.1 Purpose of This Guidance
This document provides guidance for developing the Piping Demolition Site Plan for the Puget Sound Optimization Project (PSO). It supplements the Specification and Procedure documents by offering practical advice, best practices, and lessons learned for producing high-quality demolition drawings.

### 1.2 Intended Audience
- Piping Engineers and Designers
- CAD Technicians
- Discipline Leads
- Design Review Participants

## 2. Key Considerations

### 2.1 Understanding the Demolition Scope
The PSO project involves significant brownfield modifications at Sumas Tank Farm, including:
- Installation of five new VS6 booster pumps
- Installation of a 5x6 manifold
- Associated infrastructure in the SW corner of Tank TK-102

**Key Guidance:**
- The demolition scope should be developed in close coordination with the new design layout (DEL-02.05 Piping Site Plan)
- Early identification of demolition requirements supports long-lead procurement and construction planning
- Consider temporary operational requirements during demolition/construction phases

### 2.2 Existing Conditions Assessment
Before developing demolition drawings:

1. **Gather Available Documentation**
   - Request as-built drawings from TM
   - Obtain laser scan data if available (per SOW-0221)
   - Review existing P&IDs for tie-in identification

2. **Field Verification**
   - Site walkdowns may be required to verify existing conditions
   - Document discrepancies between as-builts and field conditions
   - Photograph existing installations for reference

3. **Documentation Gaps**
   - Flag missing or incomplete as-built information
   - Coordinate with TM to obtain required documentation
   - Consider assumptions carefully and document clearly

### 2.3 Coordination with Related Deliverables

| Related Deliverable | Coordination Action |
|---------------------|---------------------|
| DEL-01.03 (P&IDs) | Source for identifying piping to be demolished; confirm process intent |
| DEL-02.03 (Tie-In List) | Coordinate cut/tie-in locations and numbering |
| DEL-02.05 (Piping Site Plan) | Ensure demolition boundaries support new design |
| DEL-02.28 (3D Model) | Include demolition scope in model for clash detection |
| DEL-04.24 (C/S Demolition) | Align structural and piping demolition scope |

## 3. Best Practices

### 3.1 Drawing Development

#### 3.1.1 Clarity of Presentation
- Use distinct, consistent symbology for demolition items
- Avoid overcrowding; use multiple sheets if necessary
- Provide clear legends explaining all symbols and notations
- Use color coding in working drafts (convert to appropriate symbology for issued drawings)

#### 3.1.2 Comprehensive Coverage
- Ensure all demolition items are captured (piping, valves, supports, instrumentation connections)
- Include reference to items to remain with clear "EXIST TO REMAIN" notation
- Show preservation/protection requirements for adjacent facilities

#### 3.1.3 Logical Organization
- Organize multi-sheet sets with clear key plan
- Use consistent orientation across sheets
- Match line locations should be practical for construction use

### 3.2 Quality Control

#### 3.2.1 Self-Check Questions
Before submitting for review, verify:
- [ ] All demolished items referenced back to P&IDs?
- [ ] Cut points clearly identified with tie-in references?
- [ ] Items to remain clearly distinguished from demolition scope?
- [ ] Coordination with civil/structural demolition complete?
- [ ] Drawing cross-references complete and accurate?
- [ ] Legend complete and consistent with drawing content?

#### 3.2.2 Common Issues to Avoid
| Issue | Prevention |
|-------|------------|
| Missing items | Cross-check against P&IDs and equipment list |
| Conflicting information | Verify against latest design iteration |
| Unclear boundaries | Define precise limits of demolition |
| Orphaned supports | Ensure structural supports are addressed |
| Instrument connections | Coordinate with I&C for instrument removal |

### 3.3 Constructability Considerations

When developing demolition plans, consider:

1. **Sequence of Work**
   - Identify dependencies between demolition activities
   - Note requirements for isolations and shutdowns
   - Consider access constraints during demolition

2. **Safety Considerations**
   - Identify potential hazards (residual hydrocarbons, confined spaces)
   - Note requirements for energy isolation
   - Consider fall protection requirements for elevated work

3. **Environmental Considerations**
   - Note requirements for containment during demolition
   - Consider waste handling/disposal requirements
   - Identify any hazardous materials (e.g., insulation, coatings)

## 4. Common Challenges and Solutions

### 4.1 Incomplete As-Built Information
**Challenge:** As-built drawings may be incomplete or out of date.

**Solutions:**
- Schedule field verification walks early in FEED
- Use laser scan data to supplement as-builts
- Document assumptions clearly on drawings
- Flag items requiring field verification in construction notes

### 4.2 Scope Creep During Design Development
**Challenge:** Demolition scope may change as new design evolves.

**Solutions:**
- Maintain close coordination with design development
- Use revision control to track scope changes
- Hold regular coordination meetings with affected disciplines
- Document change history for traceability

### 4.3 Interface with Operating Facilities
**Challenge:** Demolition must be coordinated with ongoing operations.

**Solutions:**
- Clearly identify tie-in points and isolation requirements
- Coordinate with Operations for shutdown planning
- Note phasing requirements on drawings
- Reference relevant procedures for hot work, isolations, etc.

## 5. Review and Approval Guidance

### 5.1 Internal Review Focus Areas
| Reviewer | Focus Areas |
|----------|-------------|
| Piping Lead | Technical accuracy, completeness of scope |
| Process | Confirmation of process intent, tie-in verification |
| Civil/Structural | Structural demolition coordination |
| Mechanical | Equipment removal coordination |
| I&C | Instrument connection removal |
| CAD Lead | Standards compliance, drawing quality |

### 5.2 Client Review Considerations
When submitting for TM review:
- Highlight key assumptions and TBD items
- Identify items requiring TM input or confirmation
- Note any deviations from TM standards
- Provide context for demolition decisions in transmittal

## 6. Documentation and Traceability

### 6.1 Records to Maintain
- Working files and intermediate drafts (per project document control)
- Field verification records and photographs
- Comment resolution logs from reviews
- Change history documentation

### 6.2 Cross-References
Ensure proper cross-referencing to:
- Source P&IDs and equipment lists
- Tie-in list (DEL-02.03)
- 3D model (DEL-02.28)
- Related demolition drawings in other disciplines

## 7. Assumptions and TBD Resolution

### 7.1 Current Assumptions
| ID | Assumption | Resolution Path |
|----|------------|-----------------|
| A1 | As-built drawings available from TM | Confirm with TM document control |
| A2 | Laser scan data available for existing conditions | Confirm with TM/survey contractor |
| A3 | TM CAD standards apply | Obtain TM CAD standards |
| A4 | Hot tap execution by others | Confirmed per SOW-0249 |

### 7.2 TBD Items for Resolution
| ID | TBD Item | Owner | Target Resolution |
|----|----------|-------|-------------------|
| T1 | TM CAD standards and templates | TM | Prior to FEED drawing production |
| T2 | Document numbering convention | TM/Doc Control | Prior to IFR issue |
| T3 | Demolition symbology | TM/Piping Lead | During FEED |
| T4 | Specific demolition scope | Design Team | During FEED layout development |

## 8. Source References
- Decomposition: Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md
- SOW: Exhibit A - Scope of Work PS.pdf
- Scope Items: SOW-0124, SOW-0247
- Related Deliverables: DEL-02.03, DEL-02.05, DEL-02.28, DEL-04.24
