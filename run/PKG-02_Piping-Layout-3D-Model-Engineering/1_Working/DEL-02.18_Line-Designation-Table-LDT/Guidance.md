# Guidance: Line Designation Table (LDT)

**Deliverable ID:** DEL-02.18
**Package:** PKG-02 (Piping, Layout & 3D Model Engineering)
**Version:** 0.1 (Initial Draft)
**Status:** INITIALIZED
**Date:** 2026-02-01

---

## 1. Purpose

This guidance document provides direction for developing the Line Designation Table (LDT) for the Puget Sound Optimization Project (PSO). It clarifies expectations, provides best practices, and addresses common questions.

---

## 2. Context

### 2.1 Project Background
The PSO project involves installing five new VS6-type booster pumps, a 5x6 manifold, a containment wall, and associated infrastructure at Sumas Tank Farm (SW corner of TK-102). The LDT is the primary document for capturing all piping line attributes required for design, fabrication, and construction.

### 2.2 Relationship to Other Deliverables

| Deliverable | Relationship |
|-------------|--------------|
| DEL-01.01 (DBM) | Provides design conditions - INPUT |
| DEL-01.03 (P&IDs) | Provides line tags and routing - INPUT |
| DEL-02.01 (Line List) | Initial line identification - INPUT |
| DEL-02.25 (PMC Index) | Piping class definitions - INPUT |
| DEL-02.13 (Isometrics) | Uses LDT data for titleblocks - OUTPUT |
| DEL-02.19 (MTO) | Organized by LDT lines - OUTPUT |
| DEL-02.21 (Hydrotest) | Test pressures from LDT - OUTPUT |

---

## 3. Development Approach

### 3.1 Phased Development

**FEED Phase:**
- Establish LDT structure and column definitions
- Populate preliminary data from P&IDs and DBM
- Identify TBD items for Detailed Design
- Sufficient detail for cost estimation

**Detailed Design Phase:**
- Finalize all line attributes
- Complete NDE and testing requirements
- Resolve all TBD items
- Final coordination with related deliverables

### 3.2 Data Collection Workflow

```
Step 1: Extract line tags from P&IDs (DEL-01.03)
    |
Step 2: Obtain design conditions from DBM (DEL-01.01)
    |
Step 3: Assign piping classes from PMC Index (DEL-02.25)
    |
Step 4: Determine NDE/PWHT from specs and code
    |
Step 5: Calculate test pressures per code
    |
Step 6: Add insulation/heat tracing from schedules
    |
Step 7: Review and validate all data
```

### 3.3 Coordination Points

| Activity | Timing | Participants |
|----------|--------|--------------|
| LDT kickoff/template review | Early FEED | Piping Lead, Process Lead |
| P&ID cross-check | Mid FEED | Piping, Process |
| PMC validation | Mid FEED | Piping Lead, Materials |
| NDE/testing review | Late FEED | Piping, QA/QC |
| Final data freeze | Pre-IFC | All disciplines |

---

## 4. Technical Guidance

### 4.1 Line Numbering Best Practices

| Consideration | Guidance |
|---------------|----------|
| Uniqueness | Every line must have a unique number - no duplicates |
| Consistency | Format must be consistent across all documents |
| Traceability | Line numbers must match P&IDs exactly |
| Continuity | Use same number for entire line segment |

**Common Numbering Errors:**
- Using different numbers on P&ID vs. LDT
- Duplicating numbers for different lines
- Inconsistent format (leading zeros, separators)
- Changing numbers during project without updating all documents

### 4.2 Design Conditions Guidelines

| Condition | Source | Notes |
|-----------|--------|-------|
| Design Pressure | DBM/Process | Use design case, not operating |
| Design Temperature | DBM/Process | Include both max and min if applicable |
| Operating Conditions | DBM/Process | Normal steady-state values |

**Common Issues:**
- Using operating pressure as design pressure
- Missing temperature extremes (min winter, max summer)
- Not accounting for blocked-in conditions

### 4.3 Piping Class Selection

| Factor | Consideration |
|--------|---------------|
| Pressure Rating | Must exceed design pressure |
| Temperature Rating | Must cover design temperature range |
| Corrosion Allowance | Per service and design life |
| Material | Compatible with fluid and environment |

**Guidelines:**
- Reference PMC Index (DEL-02.25) for valid classes
- Consult Materials/Corrosion if uncertain
- Document any special requirements in Remarks

### 4.4 NDE Requirements

| Code Basis | Typical Requirements |
|------------|---------------------|
| CSA Z662 Category I | 100% RT or UT |
| CSA Z662 Category II | Random RT/UT |
| ASME B31.4 | Per design conditions |

**Guidelines:**
- Reference project specification for NDE tables
- Higher criticality = more examination
- Coordinate with stress analysis for PWHT requirements

### 4.5 Testing Requirements

| Test Type | Application |
|-----------|-------------|
| Hydrostatic | Primary test per CSA Z662 |
| Pneumatic | Alternative per code approval |
| Service/Leak | Supplementary testing |

**Test Pressure Calculation:**
- Per CSA Z662 or ASME B31.4 as applicable
- Document calculation basis
- Coordinate with Hydrotest Package (DEL-02.21)

---

## 5. Common Issues and Solutions

### 5.1 Missing Source Data

**Issue:** P&IDs not complete when LDT development starts.

**Solution:**
- Start with available P&IDs
- Mark TBD for missing lines
- Use preliminary line list as placeholder
- Update as P&IDs develop

### 5.2 Conflicting Data Sources

**Issue:** DBM and P&ID show different conditions.

**Solution:**
- DBM takes precedence for design conditions
- Flag discrepancies for resolution
- Document resolution in Remarks
- Update source document if error

### 5.3 Piping Class Not Available

**Issue:** Required pressure/temperature not covered by existing PMC.

**Solution:**
- Request new PMC from Materials
- Document in PMC Verification Report (DEL-02.24)
- Use closest available class with deviation request
- Never downgrade class without engineering approval

### 5.4 Line Count Growth

**Issue:** More lines identified during design than estimated.

**Solution:**
- Update LDT progressively
- Track additions in revision log
- Report significant growth to project management
- Assess impact on MTO and schedule

---

## 6. Quality Considerations

### 6.1 Pre-Issue Checklist

Before issuing LDT, verify:
- [ ] All lines from P&IDs are captured
- [ ] No duplicate line numbers
- [ ] All mandatory fields populated
- [ ] Piping classes valid per PMC Index
- [ ] Design conditions match DBM
- [ ] NDE codes valid
- [ ] Test pressures calculated correctly
- [ ] Unit consistency throughout

### 6.2 Cross-Reference Verification

| Check | Method |
|-------|--------|
| P&ID Coverage | Count lines on P&IDs vs. LDT entries |
| PMC Validity | Validate against PMC Index list |
| Condition Consistency | Spot check against DBM |
| Calculation Accuracy | Verify sample test pressure calculations |

### 6.3 Common Data Entry Errors

| Error Type | Prevention |
|------------|------------|
| Typos in line numbers | Use copy/paste from P&IDs |
| Wrong units | Standardize unit convention |
| Copy/paste errors | Check after paste operations |
| Missing data | Use conditional formatting to highlight blanks |

---

## 7. Lessons Learned (Industry Best Practices)

### 7.1 Template Standardization
- Use consistent template from project start
- Lock column structure after approval
- Avoid adding columns mid-project

### 7.2 Version Control
- Save dated versions at each submission
- Track all changes in revision log
- Use compare function to identify changes

### 7.3 Data Validation
- Use Excel data validation features
- Create dropdown lists for coded fields
- Implement range checks for numerical data

### 7.4 Coordination
- Single owner for LDT maintenance
- Clear process for input from other disciplines
- Regular reconciliation with P&IDs

---

## 8. References

| Reference | Description |
|-----------|-------------|
| SOW Section 3.2.4.11 | LDT requirements |
| SOW Section 3.2.4.23-24 | Native file requirements |
| CSA Z662 | Oil and Gas Pipeline Systems |
| ASME B31.4 | Pipeline Transportation Systems |

---

## 9. Contact Points (TBD)

| Role | Name | Responsibility |
|------|------|----------------|
| Piping Lead | TBD | LDT ownership and approval |
| Process Lead | TBD | Design conditions input |
| Materials Engineer | TBD | PMC validation |
| Document Control | TBD | Version control and issue |

---

*Guidance generated as initial draft. Content to be refined based on project-specific requirements and TM direction.*
