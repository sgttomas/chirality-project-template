# Guidance: Piping Material Takeoff (MTO)

**Deliverable ID:** DEL-02.19
**Package:** PKG-02 (Piping, Layout & 3D Model Engineering)
**Version:** 0.1 (Initial Draft)
**Status:** INITIALIZED
**Date:** 2026-02-01

---

## 1. Purpose

This guidance document provides direction for developing the Piping Material Takeoff (MTO) for the Puget Sound Optimization Project (PSO). It clarifies expectations, provides best practices, and addresses common questions.

---

## 2. Context

### 2.1 Project Background
The PSO project involves installing five new VS6-type booster pumps, a 5x6 manifold, a containment wall, and associated infrastructure at Sumas Tank Farm (SW corner of TK-102). The Piping MTO is critical for accurate cost estimation, procurement planning, and construction execution.

### 2.2 Relationship to Other Deliverables

| Deliverable | Relationship |
|-------------|--------------|
| DEL-02.13 (Isometrics) | Primary source for pipe/fittings - INPUT |
| DEL-02.02 (Valve List) | Valve quantities - INPUT |
| DEL-02.20 (Specialty Datasheets) | Specialty items - INPUT |
| DEL-02.25 (PMC Index) | Material specs - INPUT |
| DEL-02.28 (3D Model) | Model quantities - INPUT |
| Cost Estimate | Uses MTO for pricing - OUTPUT |
| Procurement | Purchase basis - OUTPUT |

---

## 3. Development Approach

### 3.1 Phased Development

**FEED Phase:**
- Preliminary MTO for cost estimation
- Based on P&IDs and preliminary routing
- Expected accuracy: +/- 20%
- Focus on major items (large pipe, valves, specialty items)

**Detailed Design Phase (IFD):**
- Refined MTO from developed isometrics
- Expected accuracy: +/- 10%
- Include all commodity categories
- Suitable for procurement bid packages

**Detailed Design Phase (IFC):**
- Final MTO from approved isometrics
- Expected accuracy: +/- 5%
- Final quantities for construction
- Includes all allowances

### 3.2 Quantity Derivation Workflow

```
Step 1: Extract pipe and fitting quantities from 3D model
    |
Step 2: Verify against isometric BOMs (if available)
    |
Step 3: Add valve quantities from Valve List
    |
Step 4: Add specialty items from datasheets
    |
Step 5: Calculate bolting and gaskets from flange count
    |
Step 6: Add support materials from support drawings
    |
Step 7: Apply appropriate allowances
    |
Step 8: Organize and summarize by commodity/class
```

### 3.3 Coordination Points

| Activity | Timing | Participants |
|----------|--------|--------------|
| MTO basis/template kickoff | Early FEED | Piping Lead, Cost Estimator |
| Valve list reconciliation | Mid FEED | Piping, Valve Engineer |
| Model-based quantity review | End FEED | Piping, 3D Coordinator |
| Procurement coordination | IFD | Piping, Procurement |
| Final quantity freeze | Pre-IFC | All disciplines |

---

## 4. Technical Guidance

### 4.1 Pipe Quantity Takeoff

| Factor | Guidance |
|--------|----------|
| Measurement | Measure centerline length (not cut length) |
| Rounding | Round up to standard lengths |
| Stock Lengths | Account for standard stock lengths (6m, 12m) |
| Waste Factor | Include cutting waste in allowance |

**Common Issues:**
- Double counting at fittings
- Missing small runs
- Incorrect conversion of lengths

### 4.2 Fitting Quantity Takeoff

| Fitting Type | Counting Method |
|--------------|-----------------|
| Elbows | Count each bend point |
| Tees | Count each branch |
| Reducers | Count at each size change |
| Caps | Count dead ends |

**Guidelines:**
- Use 3D model extraction when available
- Verify against isometric sketches
- Include stub-ins and connections

### 4.3 Flange Quantity Takeoff

| Connection Type | Flange Count |
|-----------------|--------------|
| Pipe-to-Pipe | 2 flanges per joint |
| Pipe-to-Valve | 1 flange (valve has matching) |
| Pipe-to-Equipment | 1 flange (equip has matching) |
| Blind End | 1 blind flange |

**Guidelines:**
- Match flange type to service/class
- Include spectacle blinds for maintenance
- Account for future connections

### 4.4 Valve Quantity Takeoff

| Source | Application |
|--------|-------------|
| Valve List (DEL-02.02) | Primary reference |
| P&IDs | Verification |
| Isometrics | Final confirmation |

**Guidelines:**
- Use Valve List for all valve counts
- Verify specialty valves have datasheets
- Include actuator/operator accessories

### 4.5 Bolting and Gasket Quantities

| Method | Application |
|--------|-------------|
| Flange Count Method | Count flanges x bolts per flange |
| PMC Tables | Use standard bolt lists per PMC |

**Guidelines:**
- Include spare bolts (typically 5-10%)
- Match gasket type to flange and service
- Include specialty gaskets for specialty connections

### 4.6 Support Material Quantities

| Source | Material Type |
|--------|---------------|
| Support drawings (DEL-02.16) | Standard support materials |
| Location plans (DEL-02.17) | Support count and types |
| Stress analysis (DEL-02.14) | Spring hanger selections |

**Guidelines:**
- Coordinate with structural for steel allocation
- Include clamps, U-bolts, and small items
- Account for field adjustments

---

## 5. Common Issues and Solutions

### 5.1 Incomplete Design Information

**Issue:** MTO needed before design is complete.

**Solution:**
- Use parametric estimating for FEED
- Apply conservative allowances
- Document assumptions clearly
- Update as design progresses

### 5.2 Model-Isometric Discrepancies

**Issue:** 3D model quantities don't match isometric BOMs.

**Solution:**
- Isometrics take precedence for IFC
- Investigate significant differences
- Update model to match isometrics
- Document reconciliation

### 5.3 Specification Changes

**Issue:** PMC or material specifications change during project.

**Solution:**
- Flag affected materials in MTO
- Track revision impact
- Coordinate with procurement
- Update quantities as needed

### 5.4 Missing Categories

**Issue:** MTO missing commodity categories.

**Solution:**
- Use comprehensive commodity checklist
- Review similar project MTOs
- Include "miscellaneous" category
- Regular completeness reviews

---

## 6. Quality Considerations

### 6.1 Pre-Issue Checklist

Before issuing MTO, verify:
- [ ] All commodity categories included
- [ ] Quantities traced to source documents
- [ ] Material specs match PMC Index
- [ ] Valve count matches Valve List
- [ ] Specialty items match datasheets
- [ ] Bolting/gaskets calculated correctly
- [ ] Allowances applied per phase
- [ ] Unit consistency (EA, M, KG)
- [ ] Summary totals correct

### 6.2 Reconciliation Checks

| Check | Method |
|-------|--------|
| Pipe Quantities | Compare model vs. isometric totals |
| Valve Counts | Match MTO to Valve List |
| Specialty Items | Match MTO to datasheet list |
| Weight Totals | Cross-check calculated vs. known weights |

### 6.3 Common Errors to Avoid

| Error | Prevention |
|-------|------------|
| Double counting | Clear rules for connection points |
| Missing items | Use comprehensive checklists |
| Wrong specifications | Validate against PMC |
| Unit errors | Standardize unit convention |
| Allowance errors | Apply per phase guidance |

---

## 7. Lessons Learned (Industry Best Practices)

### 7.1 Organization
- Consistent commodity coding across project
- Clear breakdown structure
- Multiple summary views (by class, by area, by system)

### 7.2 Traceability
- Link each item to source document
- Document assumptions
- Track changes through revisions

### 7.3 Coordination
- Early alignment with procurement
- Regular reconciliation with isometrics
- Integration with project cost system

### 7.4 Accuracy Improvement
- Progressive refinement through phases
- Model-based takeoff when possible
- Systematic verification processes

---

## 8. References

| Reference | Description |
|-----------|-------------|
| SOW Section 3.1.3.1 | FEED MTO requirements |
| SOW Section 3.2.4.9 | Isometric/MTO requirements |
| SOW Section 3.2.4.12 | MTO development requirements |
| PMC Index (DEL-02.25) | Material specifications |

---

## 9. Contact Points (TBD)

| Role | Name | Responsibility |
|------|------|----------------|
| Piping Lead | TBD | MTO ownership and approval |
| Cost Estimator | TBD | Pricing coordination |
| Procurement Lead | TBD | Procurement interface |
| Document Control | TBD | Version control and issue |

---

*Guidance generated as initial draft. Content to be refined based on project-specific requirements and TM direction.*
