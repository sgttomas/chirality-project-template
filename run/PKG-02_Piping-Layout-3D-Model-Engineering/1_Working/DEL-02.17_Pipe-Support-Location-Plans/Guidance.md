# Guidance: Pipe Support Location Plans

**Deliverable ID:** DEL-02.17
**Package:** PKG-02 (Piping, Layout & 3D Model Engineering)
**Version:** 0.1 (Initial Draft)
**Status:** INITIALIZED
**Date:** 2026-02-01

---

## 1. Purpose

This guidance document provides direction for developing Pipe Support Location Plans for the Puget Sound Optimization Project (PSO). It clarifies expectations, provides best practices, and addresses common questions.

---

## 2. Context

### 2.1 Project Background
The PSO project involves installing five new VS6-type booster pumps, a 5x6 manifold, a containment wall, and associated infrastructure at Sumas Tank Farm (SW corner of TK-102). The support location plans show where each support is positioned to enable construction.

### 2.2 Relationship to Other Deliverables

| Deliverable | Relationship |
|-------------|--------------|
| DEL-02.16 (Standard Drawings) | Provides support type details - REFERENCE |
| DEL-02.14 (Stress Analysis) | Provides support locations - INPUT |
| DEL-02.12 (Piping GAs) | Provides base plan - INPUT |
| DEL-02.13 (Isometrics) | Uses support marks - OUTPUT |
| DEL-02.28 (3D Model) | Source for coordinates - INPUT |

---

## 3. Development Approach

### 3.1 Phased Development

**FEED Phase:**
- Develop preliminary location plans based on initial stress analysis
- Focus on critical areas (pump station, manifold)
- Sufficient detail for cost estimation and steel design

**Detailed Design Phase:**
- Finalize all location plans to IFC quality
- Incorporate final stress analysis results
- Complete coverage of all areas
- Coordinate with as-built survey data

### 3.2 Model-Based Development

Per SOW Section 3.2.3.3 and 3.2.4.4, a comprehensive 3D model is required. Location plans should be:
- Extracted from the 3D model where possible
- Verified against model coordinates
- Updated when model changes

### 3.3 Coordination Points

| Activity | Timing | Participants |
|----------|--------|--------------|
| Base plan alignment | Early FEED | Piping, Civil/Structural |
| Support location review | Mid FEED | Piping Lead, Stress Engineer |
| Structural steel coordination | Mid FEED | Piping, Structural |
| Model coordination | Ongoing | Piping, Model Coordinator |
| Constructability review | IFD milestone | Piping, Construction Rep |

---

## 4. Technical Guidance

### 4.1 Plan Organization

Organize plans by area for clarity:

| Area | Recommended Scale | Notes |
|------|-------------------|-------|
| Booster Pump Station | 1:50 | Congested area, may need details |
| Manifold Area | 1:50 | Complex routing |
| Yard Piping | 1:100 | Long runs, less congested |
| Tank Connections | 1:50 | Interface area |

### 4.2 Support Spacing Guidelines

While stress analysis determines actual locations, typical guidelines (ASSUMPTION - verify per TM standards):

| Pipe Size | Maximum Span (Horizontal) | Notes |
|-----------|---------------------------|-------|
| 2" - 4" | 3.0 - 4.0 m | Varies with schedule |
| 6" - 10" | 4.0 - 5.0 m | |
| 12" - 16" | 5.0 - 6.0 m | |
| 18" - 24" | 6.0 - 7.0 m | |

### 4.3 Critical Support Locations

Pay particular attention to:

| Location | Consideration |
|----------|---------------|
| Near equipment | Pump suction/discharge, valve operators |
| At anchors | Fixed points with high loads |
| Direction changes | Elbows, tees require adjacent support |
| At expansion joints | Guides on either side |
| Heavy components | In-line valves, flow meters |

### 4.4 Elevation Considerations

- Reference elevation to a consistent datum
- Show elevation at top of support steel (attachment point)
- Coordinate with structural steel elevations
- Consider slope requirements for drain lines

---

## 5. Common Issues and Solutions

### 5.1 Congested Areas

**Issue:** Too many supports to show clearly on one plan.

**Solution:**
- Use enlarged detail views at larger scale
- Create separate sheets for different elevations
- Use support schedule for detailed information
- Reference enlarged details from main plan

### 5.2 Coordinate Accuracy

**Issue:** Field survey reveals discrepancies from design coordinates.

**Solution:**
- Use as-built survey data during detailed design
- Allow field adjustment tolerance in design
- Update model and plans after field verification
- Communicate tolerances to construction

### 5.3 Structural Steel Availability

**Issue:** Support locations fall where no structural steel exists.

**Solution:**
- Early coordination with structural engineering
- Identify secondary steel requirements
- Consider alternative support arrangements
- Document structural additions required

### 5.4 Support Type Changes

**Issue:** Stress analysis changes require different support types.

**Solution:**
- Maintain coordination with stress engineer
- Track support changes in a log
- Update both location plans and isometrics
- Verify standard drawings cover new types

---

## 6. Quality Considerations

### 6.1 Completeness Checklist

Before issue, verify:
- [ ] All stress model supports are shown on plans
- [ ] Support marks are unique and properly formatted
- [ ] Standard drawing references are correct
- [ ] Coordinates match 3D model
- [ ] Elevations are correctly noted
- [ ] Legend is complete
- [ ] Match lines reference correct sheets
- [ ] North arrow is shown

### 6.2 Coordination Verification

Verify coordination with:
- [ ] Stress analysis support list (all supports included)
- [ ] Structural steel drawings (attachment points exist)
- [ ] Piping isometrics (support marks match)
- [ ] 3D model (coordinates consistent)

---

## 7. Best Practices

### 7.1 Numbering Consistency
- Establish numbering convention early
- Maintain register of all support marks
- Avoid renumbering during project (use suffixes if needed)

### 7.2 Layered Information
- Use CAD layers effectively
- Allow different views (with/without text) for different uses
- Consider construction use when organizing information

### 7.3 Version Control
- Track plan versions carefully
- Ensure all related documents reference same version
- Manage hold points when plans are under revision

### 7.4 Field Usability
- Consider how plans will be used in the field
- Provide clear match line references
- Include adequate reference information

---

## 8. References

| Reference | Description |
|-----------|-------------|
| SOW Section 3.2.4.3 | Pipe support standard drawings and location plans |
| SOW Section 3.2.4.4 | 3D CAD model requirements |
| DEL-02.14 | Pipe Stress Analysis Report(s) |
| DEL-02.15 | Support & Pipe Stress Execution Plan |
| DEL-02.16 | Pipe Support Standard Drawings |

---

## 9. Contact Points (TBD)

| Role | Name | Responsibility |
|------|------|----------------|
| Piping Lead | TBD | Location plan development oversight |
| Stress Engineer | TBD | Support location inputs |
| Model Coordinator | TBD | 3D model coordination |
| Structural Lead | TBD | Steel attachment coordination |

---

*Guidance generated as initial draft. Content to be refined based on project-specific requirements and TM direction.*
