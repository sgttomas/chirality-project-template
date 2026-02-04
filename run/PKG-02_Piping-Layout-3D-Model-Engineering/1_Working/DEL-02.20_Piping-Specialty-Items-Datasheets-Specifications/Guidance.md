# Guidance: Piping Specialty Items Datasheets & Specifications

**Deliverable ID:** DEL-02.20
**Package:** PKG-02 (Piping, Layout & 3D Model Engineering)
**Version:** 0.1 (Initial Draft)
**Status:** INITIALIZED
**Date:** 2026-02-01

---

## 1. Purpose

This guidance document provides direction for developing Piping Specialty Item Datasheets and Specifications for the Puget Sound Optimization Project (PSO). It clarifies expectations, provides best practices, and addresses common questions.

---

## 2. Context

### 2.1 Project Background
The PSO project involves installing five new VS6-type booster pumps, a 5x6 manifold, a containment wall, and associated infrastructure at Sumas Tank Farm (SW corner of TK-102). Specialty item datasheets are critical for accurate procurement and ensuring equipment meets design requirements.

### 2.2 Definition of "Specialty Item"
Specialty items are piping components that require individual specification beyond standard piping material class (PMC) coverage. They typically:
- Have specific performance requirements
- Require vendor-specific selection
- Need individual datasheets for procurement
- May require manufacturer certified drawings

### 2.3 Relationship to Other Deliverables

| Deliverable | Relationship |
|-------------|--------------|
| DEL-01.03 (P&IDs) | Specialty item identification - INPUT |
| DEL-01.01 (DBM) | Design conditions - INPUT |
| DEL-02.25 (PMC Index) | Material specifications - INPUT |
| DEL-02.02 (Valve List) | Valve specialty items - RELATED |
| DEL-02.19 (MTO) | Specialty item quantities - OUTPUT |
| Procurement | Purchase requisitions - OUTPUT |

---

## 3. Development Approach

### 3.1 Phased Development

**FEED Phase:**
- Identify all specialty items from P&IDs
- Develop preliminary datasheets for long-lead items
- Establish specialty item register
- Focus on items affecting cost estimate

**Detailed Design Phase:**
- Finalize all specialty item datasheets
- Complete vendor drawing reviews
- Update register with procurement status
- Resolve all TBD items

### 3.2 Specialty Item Identification Workflow

```
Step 1: Review P&IDs for specialty symbols
    |
Step 2: Cross-check with Valve List for special valves
    |
Step 3: Review process requirements for special equipment
    |
Step 4: Compile specialty item list
    |
Step 5: Assign tag numbers
    |
Step 6: Develop datasheets
    |
Step 7: Maintain register
```

### 3.3 Coordination Points

| Activity | Timing | Participants |
|----------|--------|--------------|
| Specialty item kickoff | Early FEED | Piping Lead, Process Lead |
| P&ID specialty item extraction | Mid FEED | Piping Designer |
| Datasheet development | FEED/Detailed | Piping Engineer |
| Vendor drawing review | Detailed Design | Piping Engineer |
| Procurement coordination | IFD onwards | Piping, Procurement |

---

## 4. Technical Guidance

### 4.1 Item Identification Guidelines

| P&ID Symbol | Likely Specialty Item |
|-------------|----------------------|
| Strainer symbol | Y-strainer, basket strainer |
| Check valve (special) | Wafer check, tilting disc |
| Relief valve | PRV, PSV, vacuum breaker |
| Filter | Coalescing filter, cartridge |
| Expansion loop/joint | Bellows, slip joint |
| Flame arrestor | In-line or end-of-line |

### 4.2 Datasheet Development Best Practices

| Aspect | Guidance |
|--------|----------|
| Design Conditions | Use maximum credible conditions, not just normal operating |
| Materials | Specify per PMC; document deviations |
| Sizing | Include sizing basis/calculations in project files |
| Accessories | Specify all required accessories (indicators, actuators) |
| Testing | Include test requirements (shop test, field test) |

### 4.3 Category-Specific Guidance

#### 4.3.1 Strainers

**Selection Factors:**
- Y-strainer: Low-cost, small DP requirement
- Basket strainer: Higher dirt-holding capacity
- Duplex: Continuous operation, online maintenance
- Automatic: Unmanned or remote locations

**Key Parameters:**
- Mesh size based on downstream equipment protection
- Clean/dirty differential pressure
- Blowdown provisions for crude service

#### 4.3.2 Check Valves

**Selection Factors:**
- Swing check: Standard, low-cost
- Wafer check: Space constraints
- Tilting disc: Low pressure drop
- Nozzle check: Fast closure, water hammer prevention

**Key Parameters:**
- Cracking pressure for start-up
- Closure speed for surge prevention
- Seat leakage class

#### 4.3.3 Relief Valves

**Selection Factors:**
- Conventional: Standard applications
- Balanced bellows: Variable backpressure
- Pilot operated: High capacity, tight shutoff

**Key Parameters:**
- Set pressure from relief study
- Relieving capacity from calculations
- Backpressure considerations
- ASME/NB certification requirements

#### 4.3.4 Expansion Joints

**Selection Factors:**
- Bellows: Standard expansion
- Universal: Multi-directional movement
- Slip joint: High movement, pipeline applications

**Key Parameters:**
- Movement range (axial, lateral, angular)
- Fatigue cycles based on thermal cycling
- Pressure thrust and anchoring

### 4.4 Material Selection Guidance

| Service | Consideration |
|---------|---------------|
| Crude Oil | Carbon steel standard; check for H2S if sour |
| Low Temperature | Impact tested materials below -29C |
| High Temperature | Creep resistance above 400C |
| Corrosive | Upgrade to stainless or alloy |

---

## 5. Common Issues and Solutions

### 5.1 Incomplete P&IDs

**Issue:** P&IDs not complete, specialty items not yet identified.

**Solution:**
- Use preliminary P&IDs to identify likely items
- Consult similar projects for typical specialty items
- Flag items as "preliminary" in register
- Update as P&IDs develop

### 5.2 Conflicting Requirements

**Issue:** Process requirements conflict with material limitations.

**Solution:**
- Engage process engineering early
- Document design basis clearly
- Consider alternative solutions
- Escalate if resolution not possible

### 5.3 Long Lead Items

**Issue:** Some specialty items have long procurement lead times.

**Solution:**
- Identify long-lead items early in FEED
- Prioritize datasheet development
- Consider pre-ordering strategy
- Coordinate with procurement schedule

### 5.4 Vendor Drawing Delays

**Issue:** Manufacturer drawings not received in time for engineering.

**Solution:**
- Establish aggressive vendor data schedule
- Use preliminary/catalog data for design
- Flag areas dependent on vendor data
- Expedite critical submissions

---

## 6. Quality Considerations

### 6.1 Pre-Issue Checklist

Before issuing datasheets, verify:
- [ ] All required fields completed
- [ ] Design conditions match DBM
- [ ] Materials match PMC or deviations documented
- [ ] Applicable codes referenced
- [ ] Sizing basis documented
- [ ] Accessories specified
- [ ] Testing requirements included
- [ ] Tag number correct

### 6.2 Register Maintenance

| Activity | Frequency |
|----------|-----------|
| Add new items | As identified |
| Update status | Weekly |
| Reconcile with P&IDs | At each P&ID issue |
| Verify datasheet references | At each datasheet issue |

### 6.3 Common Errors to Avoid

| Error | Prevention |
|-------|------------|
| Missing items | Systematic P&ID review |
| Wrong design conditions | Cross-check with DBM |
| Incomplete materials | Reference full PMC specification |
| Missing accessories | Use comprehensive datasheet template |
| Incorrect sizing | Document and check calculations |

---

## 7. Lessons Learned (Industry Best Practices)

### 7.1 Early Identification
- Start specialty item list in early FEED
- Engage process engineering for hidden requirements
- Review vendor catalogs for options

### 7.2 Template Standardization
- Use consistent datasheet templates
- Include all common fields
- Customize for item type

### 7.3 Vendor Coordination
- Establish data submittal requirements early
- Include in purchase order terms
- Track vendor data status

### 7.4 Register Discipline
- Single owner for register maintenance
- Regular updates and reconciliation
- Clear status definitions

---

## 8. Vendor Drawing Review Guidelines

### 8.1 Review Focus Areas

| Area | Review Items |
|------|--------------|
| Dimensions | Fit with piping layout, weight for supports |
| Materials | Match datasheet requirements |
| Performance | Cv, capacity, pressure drop |
| Connections | Size, rating, facing |
| Testing | Shop test requirements met |
| Certification | Required stamps/certifications |

### 8.2 Review Turnaround

| Submission Type | Target Turnaround |
|-----------------|-------------------|
| Initial submission | 10-15 working days |
| Resubmission | 5-10 working days |
| Final (Code 1/2) | 5 working days |

### 8.3 Endorsement Guidance

| Code | When to Use |
|------|-------------|
| Code 1 | Fully compliant, no comments |
| Code 2 | Minor comments, proceed with fabrication |
| Code 3 | Significant issues, must resubmit |
| Code 4 | Fundamental non-compliance |

---

## 9. References

| Reference | Description |
|-----------|-------------|
| SOW Section 3.1.3.1 | FEED datasheet requirements |
| SOW Section 3.2.4.17 | Specialty item requirements |
| SOW Section 3.2.4.25 | Detailed piping deliverables |
| PMC Index (DEL-02.25) | Material specifications |

---

## 10. Contact Points (TBD)

| Role | Name | Responsibility |
|------|------|----------------|
| Piping Lead | TBD | Datasheet approval |
| Process Lead | TBD | Design conditions input |
| Procurement Lead | TBD | Vendor coordination |
| Document Control | TBD | Version control and issue |

---

*Guidance generated as initial draft. Content to be refined based on project-specific requirements and TM direction.*
