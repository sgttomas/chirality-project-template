# Guidance: Hydrostatic Test Packages

## 1. Purpose

### 1.1 Document Intent
This guidance document provides direction on developing hydrostatic test packages for the Puget Sound Optimization Project, addressing practical considerations, industry best practices, and project-specific requirements.

### 1.2 Target Audience
- Piping Engineers
- Piping Designers
- Construction Supervisors
- QA/QC Inspectors

## 2. Principles

### 2.1 Core Principles

| Principle | Description |
|-----------|-------------|
| **Safety First** | Test packages must ensure safe execution of hydrotests |
| **Complete Coverage** | All new piping must be covered by a test package |
| **Efficient Boundaries** | Minimize number of tests while maintaining practical boundaries |
| **Constructability** | Design test boundaries considering field execution |

### 2.2 Test Package Hierarchy
```
Hydrotest Master Index
    └── Test Package (per test number)
            ├── Boundary Drawing (colored isometric/GA)
            ├── Pressure Calculation Sheet
            ├── Vent/Drain Schedule
            ├── Isolation/Blind List
            ├── Water Management Plan
            └── Equipment Protection List
```

## 3. Considerations

### 3.1 Project-Specific Considerations

| Consideration | Details |
|---------------|---------|
| **Booster Pump Piping** | Each pump suction/discharge may be separate test |
| **Manifold Testing** | 5x6 manifold requires careful boundary planning |
| **Tie-Ins** | Coordinate tie-in tests with existing operations |
| **Seasonal Constraints** | Consider freezing conditions for water-filled tests |
| **Water Source** | Identify adequate water supply at Sumas Tank Farm |

### 3.2 Technical Considerations

| Topic | Guidance |
|-------|----------|
| **Test Pressure** | Calculate per weakest component in boundary; typically 1.5x design pressure |
| **Equipment Protection** | Remove or isolate instruments, control valves, relief valves |
| **Support Adequacy** | Verify pipe supports rated for hydrotest weight |
| **Air Elimination** | Position vents at high points for complete air removal |
| **Drainage** | Ensure complete drainage capability after test |

### 3.3 Coordination Requirements
- Coordinate with Operations for tie-in test windows
- Coordinate with Construction for water supply logistics
- Coordinate with Environmental for water disposal requirements
- Align with CWP/FIWP sequencing

## 4. Trade-offs

### 4.1 Test Boundary Size

| Approach | Pros | Cons |
|----------|------|------|
| **Large Boundaries** | Fewer tests, less setup time | Higher water volume, longer fill time |
| **Small Boundaries** | Easier logistics, faster individual tests | More tests, more setup overhead |
| **System-Based** | Logical grouping, aligns with commissioning | May cross physical boundaries |

**ASSUMPTION**: Project will use system-based boundaries aligned with commissioning sequence.

### 4.2 Test Sequence Strategy

| Trade-off | Recommendation |
|-----------|----------------|
| **Shop vs. Field Test** | Maximize shop testing to reduce field work |
| **Early vs. Late Testing** | Test as soon as practical after installation |
| **Individual vs. Combined** | Combine where practical, separate critical systems |

## 5. Examples

### 5.1 Sample Test Package Number Format (**ASSUMPTION** - confirm with TM)
```
HT-XXX-NNN

Where:
HT   = Hydrotest prefix
XXX  = Area/System code (e.g., BPS = Booster Pump Station)
NNN  = Sequential number
```

### 5.2 Sample Test Boundary Definition

| Test No | Description | Lines Included | Test Pressure | Volume |
|---------|-------------|----------------|---------------|--------|
| HT-BPS-001 | P-101 Discharge to MF-001 | SF-OIL-0800-001 through 003 | 2220 kPa | TBD m3 |

### 5.3 Color Coding Standard (**TBD** - confirm with project)

| Color | Meaning |
|-------|---------|
| Green | Test boundary - this test package |
| Red | Previously tested |
| Blue | Future test / not in scope |
| Yellow | Existing piping (not tested) |

### 5.4 Common Issues to Avoid
1. Forgetting to include temporary blinds in material list
2. Inadequate vent locations leading to trapped air
3. Test pressure exceeding flange ratings
4. Insufficient pipe support for test weight
5. No plan for water disposal containing test additives

---
*Pass 1 Draft - Generated 2026-02-01*
