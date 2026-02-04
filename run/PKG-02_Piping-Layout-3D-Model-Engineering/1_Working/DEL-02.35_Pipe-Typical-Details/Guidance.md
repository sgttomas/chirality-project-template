# Guidance: Pipe Typical Details

## 1. Purpose

### 1.1 Document Intent
This guidance document provides direction on developing Pipe Typical Detail drawings for the Puget Sound Optimization Project, addressing practical considerations, industry best practices, and project-specific requirements.

### 1.2 Target Audience
- Piping Designers
- Piping Engineers
- Construction Supervisors
- Fabrication Shop Personnel
- QC Inspectors

## 2. Principles

### 2.1 Core Principles
| Principle | Description |
|-----------|-------------|
| **Standardization** | Use consistent details across the project for efficiency |
| **Constructability** | Details shall be practical for shop and field execution |
| **Clarity** | Clear, unambiguous information for fabrication/installation |
| **Code Compliance** | All details meet applicable code requirements |
| **TM Alignment** | Leverage existing TM standards where applicable |

### 2.2 Typical Detail Hierarchy
```
Project Typical Details
    ├── TM Standard Details (adopted where applicable)
    │       └── Project modifications/clarifications
    └── Project-Specific Details
            └── Developed for PSO requirements
```

### 2.3 Detail Development Flow
```
Identify Need → Review TM Standards → Develop/Adapt Detail → Code Check → Constructability Review → Issue
```

## 3. Considerations

### 3.1 Project-Specific Considerations

| Consideration | Details |
|---------------|---------|
| **Booster Pump Environment** | Details for pump piping connections and supports |
| **Manifold Configuration** | Details for 5x6 manifold connections and headers |
| **Brownfield Integration** | Match existing Sumas Tank Farm details where connecting |
| **Crude Oil Service** | Material selections and coating requirements |
| **Cold Climate** | Heat trace details, insulation for freeze protection |

### 3.2 Technical Considerations

| Topic | Guidance |
|-------|----------|
| **Support Spacing** | Refer to DEL-02.14 stress analysis for specific requirements |
| **Material Selection** | Per PMC Index (DEL-02.25) for each service |
| **Weld Details** | Coordinate with WPS requirements |
| **Coating/Lining** | Per corrosion protection requirements |
| **Accessibility** | Consider maintenance access in all details |

### 3.3 Coordination Requirements
- Coordinate support details with structural steel design
- Align valve details with procurement datasheets
- Coordinate insulation details with HVAC/heat trace design
- Align underground details with civil/grading

## 4. Trade-offs

### 4.1 Standardization vs. Optimization

| Approach | Pros | Cons |
|----------|------|------|
| **Maximum Standardization** | Easier fabrication, reduced errors | May not optimize for specific conditions |
| **Case-by-Case Design** | Optimized for each location | More engineering, higher fabrication complexity |
| **Hybrid Approach** | Balance of efficiency and optimization | Requires clear selection criteria |

**ASSUMPTION**: Hybrid approach recommended - standardize common details, develop specific details for unique conditions.

### 4.2 Shop vs. Field Fabrication

| Approach | Pros | Cons |
|----------|------|------|
| **Shop Fabrication Focus** | Better quality control, faster field install | Transport constraints, fit-up tolerance |
| **Field Fabrication Focus** | Flexibility for as-built conditions | Weather dependent, access challenges |

**Recommendation**: Maximize shop fabrication per Module/Prefabrication List (DEL-02.23).

### 4.3 TM Standard Adoption

| Scenario | Recommendation |
|----------|----------------|
| TM standard exists and is suitable | Adopt TM standard with reference |
| TM standard exists but requires modification | Adapt and document deviation (DEL-02.31) |
| No TM standard exists | Develop project-specific detail |

## 5. Examples

### 5.1 Sample Typical Detail Index

| Detail Number | Title | Category |
|---------------|-------|----------|
| TYP-PIP-SUP-001 | Resting Support - U-Bolt Type | Pipe Support |
| TYP-PIP-SUP-002 | Guide Support - Channel Type | Pipe Support |
| TYP-PIP-SUP-003 | Anchor Support | Pipe Support |
| TYP-PIP-SUP-004 | Spring Hanger | Pipe Support |
| TYP-PIP-SUP-005 | Pipe Shoe - Standard | Pipe Support |
| TYP-PIP-SUP-006 | Pipe Shoe - Insulated | Pipe Support |
| TYP-PIP-CON-001 | Branch Connection - Weldolet | Connection |
| TYP-PIP-CON-002 | Branch Connection - Reinforced | Connection |
| TYP-PIP-CON-003 | Flanged Connection Assembly | Connection |
| TYP-PIP-VLV-001 | Gate Valve Installation | Valve |
| TYP-PIP-VLV-002 | Check Valve Installation | Valve |
| TYP-PIP-VLV-003 | Control Valve Station | Valve |
| TYP-PIP-GEN-001 | Low Point Drain | General |
| TYP-PIP-GEN-002 | High Point Vent | General |
| TYP-PIP-GEN-003 | Flow Meter Installation | General |
| TYP-PIP-GEN-004 | Sample Connection | General |
| TYP-PIP-INS-001 | Insulation Termination - Flange | Insulation |
| TYP-PIP-INS-002 | Insulation Termination - Support | Insulation |
| TYP-PIP-HT-001 | Heat Trace - Single Tube | Heat Trace |
| TYP-PIP-UG-001 | Underground Pipe Installation | Underground |

### 5.2 Sample Detail Content Requirements

| Element | Requirement |
|---------|-------------|
| Title Block | Per project CAD standard |
| Scale | Appropriate for detail clarity |
| Dimensions | All critical dimensions with tolerances |
| Materials | Full material specification callouts |
| Notes | Fabrication and installation notes |
| Code Reference | Applicable code/standard reference |
| Cross-Reference | Reference to related drawings/details |

### 5.3 Common Issues to Avoid
1. Inconsistent dimensioning or missing tolerances
2. Incomplete material callouts
3. Missing weld symbols or weld procedure references
4. Conflicting details between drawings
5. Details not practical for field installation
6. Missing reference to applicable codes/standards
7. Inconsistent detail numbering

### 5.4 Quality Checklist for Typical Details

| Check | Description |
|-------|-------------|
| [ ] | All dimensions provided with appropriate tolerances |
| [ ] | Material specifications complete and per PMC |
| [ ] | Weld symbols and WPS references included |
| [ ] | Notes complete for fabrication/installation |
| [ ] | Code compliance verified |
| [ ] | Constructability reviewed |
| [ ] | Cross-references to isometrics validated |
| [ ] | TM standard alignment verified or deviation documented |

---
*Document generated: 2026-02-01*
*Source: SOW-0260, Decomposition DEL-02.35*
