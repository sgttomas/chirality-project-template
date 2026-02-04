# Guidance: Pipe Support Standard Drawings

**Deliverable ID:** DEL-02.16
**Package:** PKG-02 (Piping, Layout & 3D Model Engineering)
**Version:** 0.1 (Initial Draft)
**Status:** INITIALIZED
**Date:** 2026-02-01

---

## 1. Purpose

This guidance document provides direction for developing Pipe Support Standard Drawings for the Puget Sound Optimization Project (PSO). It clarifies expectations, provides best practices, and addresses common questions.

---

## 2. Context

### 2.1 Project Background
The PSO project involves installing five new VS6-type booster pumps, a 5x6 manifold, a containment wall, and associated infrastructure at Sumas Tank Farm (SW corner of TK-102). The pipe support standard drawings provide the basis for all support fabrication and installation within this scope.

### 2.2 Relationship to Other Deliverables

| Deliverable | Relationship |
|-------------|--------------|
| DEL-02.14 (Stress Analysis) | Provides support loads and locations - INPUT |
| DEL-02.15 (Execution Plan) | Defines methodology - REFERENCE |
| DEL-02.17 (Location Plans) | Uses standard drawings for placement - OUTPUT |
| DEL-02.13 (Isometrics) | References standard drawings - OUTPUT |
| DEL-02.28 (3D Model) | Supports modeled per standards - OUTPUT |

---

## 3. Development Approach

### 3.1 Phased Development

**FEED Phase:**
- Develop preliminary standard drawings for main support types
- Focus on critical/long-lead supports
- Sufficient detail for cost estimation and constructability review

**Detailed Design Phase:**
- Finalize all standard drawings to IFC quality
- Incorporate stress analysis results
- Complete all support types including specials

### 3.2 Leveraging Existing Standards

Per SOW Section 3.1.5.1, the project should leverage existing designs where applicable. Consider:
- TM existing standard support drawings (if available)
- Industry standard details (MSS SP-58/69/89)
- Manufacturer standard designs for spring hangers and special supports

### 3.3 Coordination Points

| Activity | Timing | Participants |
|----------|--------|--------------|
| Support type kick-off | Early FEED | Piping Lead, Stress Engineer |
| Load table development | Mid FEED | Stress Engineer |
| Structural interface meeting | Mid FEED | Piping, Structural Leads |
| 3D model coordination | Ongoing | Piping, Model Coordinator |
| Constructability review | IFD milestone | Piping, Construction Rep |

---

## 4. Technical Guidance

### 4.1 Support Selection Criteria

When selecting support types, consider:

| Factor | Consideration |
|--------|---------------|
| Pipe movement | Static vs. dynamic, thermal expansion range |
| Load magnitude | Dead weight, occasional, sustained |
| Space constraints | Available structural steel, clearances |
| Accessibility | Maintenance and inspection access |
| Cost | Standard vs. special supports |
| Schedule | Lead time for special supports |

### 4.2 Common Support Applications (PSO-Specific)

**Booster Pump Station Piping:**
- Trunnion supports for pump suction/discharge
- Guides to control thermal movement
- Spring hangers where significant vertical displacement expected

**Manifold Piping:**
- Line stops/anchors at manifold header connections
- Shoes on pipe rack steel
- Guides for directional control

**Yard Piping:**
- Standard shoes at regular intervals
- Anchors at direction changes
- Sliding supports for thermal movement

### 4.3 Material Considerations

**Crude Oil Service:**
- Carbon steel supports for CS piping
- Insulation considerations for cold weather operation
- Corrosion protection per site environment (galvanizing, painting)

**Outdoor Installation:**
- Hot-dip galvanizing preferred for long-term durability
- Consider solar radiation effects on thermal loads
- Drainage provisions to prevent water accumulation

### 4.4 Seismic Considerations

Per SOW Section 4.1.3, seismic requirements shall be addressed. Guidance:
- Coordinate seismic zone classification with Structural (PKG-04)
- Consider lateral restraints for seismic loading
- Special detailing may be required for spring hangers in seismic zones

---

## 5. Common Issues and Solutions

### 5.1 Load Table Development

**Issue:** Stress analysis may not be complete when standard drawings are initiated.

**Solution:**
- Use preliminary loads based on similar facilities
- Mark load tables as "preliminary" during FEED
- Update to final loads during Detailed Design
- Ensure clear communication of load basis

### 5.2 Pipe Size Range Coverage

**Issue:** Multiple drawings for each pipe size is inefficient.

**Solution:**
- Design supports for pipe size ranges (e.g., 2"-4", 6"-10", 12"-16", 18"-24")
- Use adjustable components where practical
- Provide tables showing dimensions per pipe size

### 5.3 Insulation Accommodation

**Issue:** Insulation thickness varies and affects support dimensions.

**Solution:**
- Show support dimensions for bare pipe
- Provide adjustment dimensions for insulation thicknesses
- Consider pre-insulated supports where appropriate

### 5.4 Standardization vs. Optimization

**Issue:** Balancing standard designs with site-specific optimization.

**Solution:**
- Use standard designs for 80%+ of supports
- Limit custom/special supports to unique situations
- Document rationale for non-standard supports

---

## 6. Quality Considerations

### 6.1 Completeness Checklist

Before issue, verify:
- [ ] All support types used in project have standard drawings
- [ ] Dimensions are complete and clear
- [ ] Material specifications are defined
- [ ] Load capacities are stated
- [ ] Fabrication notes are included
- [ ] Weld details are specified
- [ ] Bill of materials is complete
- [ ] Drawing references are correct

### 6.2 Coordination Verification

Verify coordination with:
- [ ] Pipe stress analysis (loads match)
- [ ] Structural engineering (attachment details)
- [ ] 3D model (support geometry modeled)
- [ ] Isometrics (callouts reference correct drawings)

---

## 7. Lessons Learned (Industry Best Practices)

### 7.1 Drawing Clarity
- Use consistent symbology across all drawings
- Provide multiple views for complex supports
- Include isometric views for 3D understanding

### 7.2 Field Usability
- Design for field adjustment within tolerances
- Consider access for bolt installation
- Provide adequate clearance for welding

### 7.3 Documentation
- Maintain support type register for tracking
- Cross-reference between standard drawings and location plans
- Document basis for load capacities

---

## 8. References

| Reference | Description |
|-----------|-------------|
| SOW Section 3.2.4.3 | Standard pipe support drawings requirement |
| SOW Section 3.2.4.14 | Pipeline alignment drawings (support details) |
| MSS SP-58 | Pipe Hangers and Supports - Materials, Design and Manufacture |
| MSS SP-69 | Pipe Hangers and Supports - Selection and Application |
| MSS SP-89 | Pipe Hangers and Supports - Fabrication and Installation Practices |
| CSA Z662 | Oil and Gas Pipeline Systems |

---

## 9. Contact Points (TBD)

| Role | Name | Responsibility |
|------|------|----------------|
| Piping Lead | TBD | Standard drawing development oversight |
| Stress Engineer | TBD | Load inputs and support location coordination |
| Structural Lead | TBD | Steel/concrete attachment interface |
| Document Control | TBD | Drawing numbering and issue |

---

*Guidance generated as initial draft. Content to be refined based on project-specific requirements and TM direction.*
