# Guidance: Piping Material Class (PMC) Verification Report

## 1. Purpose

### 1.1 Document Intent
This guidance document provides direction on developing the PMC Verification Report for the Puget Sound Optimization Project, addressing practical considerations, industry best practices, and project-specific requirements.

### 1.2 Target Audience
- Piping Materials Engineers
- Piping Engineers
- QA/QC Engineers
- Owner Technical Representatives

## 2. Principles

### 2.1 Core Principles

| Principle | Description |
|-----------|-------------|
| **Code Compliance** | PMCs must comply with latest applicable codes |
| **Traceability** | All verification results traceable to code references |
| **Conservative Approach** | When code interpretation is unclear, use conservative approach |
| **Transparency** | All discrepancies openly documented with clear resolutions |

### 2.2 Verification Hierarchy
```
PMC Verification
    ├── Pressure-Temperature Ratings
    │       └── ASME B31.3 Table A-1, ASME B16.5
    ├── Material Specifications
    │       └── ASTM/ASME specifications
    ├── Component Specifications
    │       ├── Flanges (B16.5, B16.47)
    │       ├── Valves (B16.34)
    │       ├── Fittings (B16.9, B16.11)
    │       └── Gaskets/Bolts (B16.20, B16.5)
    └── Service Compatibility
            └── Corrosion, H2S, low temp, etc.
```

## 3. Considerations

### 3.1 Project-Specific Considerations

| Consideration | Details |
|---------------|---------|
| **Crude Oil Service** | Heavy/Light blend (20%/80% per SOW) |
| **Design Pressure** | Per booster pump discharge requirements |
| **Design Temperature** | Ambient to moderate temperature service |
| **Existing TM PMCs** | Leverage existing TM material classes where applicable |
| **Code Jurisdiction** | CSA Z662 and ASME B31.3 applicability (**TBD**) |

### 3.2 Technical Considerations

| Topic | Guidance |
|-------|----------|
| **Code Edition** | Use latest edition at project freeze date |
| **P-T Ratings** | Verify ratings at design temperature, not ambient |
| **Material Upgrades** | Consider if code changes require material upgrades |
| **Corrosion Allowance** | Verify CA is adequate per service |
| **Low Temperature** | Check for MDMT requirements if applicable |

### 3.3 Common Verification Areas

| Area | Check Items |
|------|-------------|
| **Pipe** | Material spec, wall thickness basis, SMYS |
| **Flanges** | Rating class, material, facing |
| **Valves** | Rating, material, trim, seat type |
| **Fittings** | Schedule, material, dimensions |
| **Gaskets** | Material compatibility, pressure rating |
| **Bolting** | Material, strength, compatibility |

## 4. Trade-offs

### 4.1 Code Edition Selection

| Approach | Pros | Cons |
|----------|------|------|
| **Latest Code** | Most current requirements | May trigger PMC changes |
| **Original PMC Code** | Minimal changes | May not meet current best practice |
| **Owner Specified** | Clear direction | May differ from contractor standard |

**ASSUMPTION**: Verification will use latest code editions as of project kick-off.

### 4.2 Discrepancy Resolution

| Approach | Pros | Cons |
|----------|------|------|
| **Upgrade PMC** | Full compliance | Cost, schedule impact |
| **Engineering Evaluation** | Case-by-case basis | Documentation burden |
| **Owner Deviation Approval** | Maintains existing | Requires formal approval |

## 5. Examples

### 5.1 Sample Discrepancy Entry

| Field | Example |
|-------|---------|
| Discrepancy ID | DISC-001 |
| PMC Affected | A1A1 |
| Code Reference | ASME B16.34-2020 Table 2-1.1 |
| Description | Valve material ASTM A216 WCB rating updated in 2020 edition |
| Severity | Medium |
| Recommendation | Update PMC to reference current rating values |
| Resolution Status | Open |

### 5.2 Sample Verification Checklist

| Item | PMC | Code | Compliant | Notes |
|------|-----|------|-----------|-------|
| Pipe material | A1A1 | ASTM A106 Gr B | Yes | Verified per B31.3 |
| Flange rating | A1A1 | Class 150 @ 38C | Yes | Per B16.5 Table 2-1.1 |
| Valve trim | A1A1 | 13Cr | Yes | Suitable for crude service |

### 5.3 Code Reference Table (**ASSUMPTION** - verify editions)

| Standard | Edition | Description |
|----------|---------|-------------|
| ASME B31.3 | 2022 | Process Piping |
| CSA Z662 | 2023 | Oil and Gas Pipeline Systems |
| ASME B16.5 | 2020 | Flanges NPS 1/2 - 24 |
| ASME B16.34 | 2020 | Valves |
| ASME B16.47 | 2020 | Large Diameter Flanges |

### 5.4 Common Issues to Avoid
1. Using outdated code editions for verification
2. Not documenting code interpretation decisions
3. Overlooking gasket/bolt compatibility
4. Ignoring service-specific requirements (H2S, low temp)
5. Not tracking discrepancy resolution to closure

---
*Pass 1 Draft - Generated 2026-02-01*
