# Guidance: DEL-01.03 Piping & Instrumentation Diagrams (P&IDs)

**Document ID:** DEL-01.03-GD
**Revision:** Phase 2.2 (INITIALIZED)
**Date:** 2026-02-01
**Status:** INITIALIZED

---

## Purpose

### Document Intent

This guidance document provides recommendations and best practices for developing Piping and Instrumentation Diagrams (P&IDs) for the Puget Sound Optimization (PSO) project. It supplements the formal specification with practical considerations specific to the booster pump station, manifold system, and blending control at Sumas Tank Farm.

### Target Audience

- Process Engineers (lead and supporting)
- Instrumentation Engineers
- CAD/Drafting personnel
- Engineering Managers

---

## Principles

### Foundational Principles

| Principle | Description |
|-----------|-------------|
| Accuracy | P&IDs must accurately represent the as-designed system |
| Completeness | All equipment, piping, and instrumentation must be shown |
| Consistency | Tags, symbols, and formats must be consistent throughout |
| Traceability | All elements must trace to DEL-02.01 (Line List), DEL-02.02 (Valve List), DEL-07.02 (Instrument Index) |
| HAZOP Support | P&IDs must support HAZOP study execution per DEL-01.15 |
| Vendor Integration | Vendor P&IDs must be transformed per TM standards (SOW §3.2.3.5) |

### PSO-Specific Considerations

| Consideration | Application | Source |
|---------------|-------------|--------|
| Booster Pump Configuration | 5 pumps (2L+2S+1M) with individual VFDs and flow meters | SOW §2.3.1.1-4 |
| Manifold System | 5x6 manifold - show all header/branch configurations | SOW §2.3.1.1 |
| Blending Control | Flow ratio control with dedicated flow meters | SOW §2.3.1.4 |
| Brownfield Integration | Tie-ins to existing Sumas Terminal systems | Site context |
| Vendor P&ID Integration | Transform vendor drawings to project standards | SOW §3.2.3.5 |
| Auxiliary Systems | Sump tank, reinjection pumps, dewatering | SOW §3.2.3.10 |

---

## Considerations

### Technical Considerations

#### Booster Pump Representation

Each of the 5 booster pumps (VS6-type) shall show per SOW §2.3.1:
- Pump symbol with motor indication
- VFD symbol/indication (one per pump per SOW §2.3.1.4)
- Suction piping and valves
- Discharge piping and valves
- Discharge flow meter (FT) and transmitter per SOW §2.3.1.4
- Minimum flow protection (if applicable)
- Seal/flush systems (if applicable)
- Vent and drain connections

Pump sizing per SOW §2.3.1.2:
- 2 Large Capacity: P-[NNN]-A, P-[NNN]-B
- 2 Small Capacity: P-[NNN]-C, P-[NNN]-D
- 1 Medium Capacity: P-[NNN]-E
(Tag numbering to be confirmed with TM)

#### Manifold System Representation

5x6 Manifold considerations per SOW §2.3.1.1:
- **ASSUMPTION:** 5 inlet headers, 6 outlet headers (interpretation TBD - confirm with TM)
- Show all header piping with appropriate sizes per DEL-01.05 (Pipe Sizing Criteria)
- Show all isolation valves and check valves coordinated with DEL-02.02
- Show manifold instrumentation (pressure, flow) coordinated with DEL-07.02
- Consider clarity for complex valve arrangements - may require separate detail sheets

#### Blending Control System

| Element | P&ID Representation | Source |
|---------|---------------------|--------|
| Flow Meters | FT tag on each pump discharge | SOW §2.3.1.4 |
| Flow Controllers | FC for ratio control | Control philosophy |
| Blend Setpoint | Connection to control system | TM control philosophy |
| Control Valves | CV if applicable for fine control | **TBD** |

#### Control Philosophy Integration

Per SOW §3.1.7.12:
- Apply control philosophy prepared by TM
- Confirm design operability and interface protocols with existing control system
- Show existing control system interfaces clearly

### Vendor P&ID Transformation

Per SOW §3.2.3.5 (transform vendor P&IDs) and §3.2.3.6 (develop auxiliary P&IDs):

| Source | Transformation Required |
|--------|------------------------|
| Pump Vendor P&IDs | Convert to TM symbols/legends/tagging |
| VFD Vendor Diagrams | Integrate with project P&IDs |
| Package Unit P&IDs | Integrate with project P&IDs |
| Control Panel Schematics | Reference or integrate as appropriate |

Steps for transformation:
1. Obtain vendor P&IDs early in procurement
2. Map vendor tags to project tags (maintain mapping table)
3. Redraw using TM symbols and CAD standards
4. Verify completeness against vendor scope
5. Review with I&C for control system integration
6. Coordinate with PKG-03 for equipment verification

### Brownfield Considerations

| Aspect | Recommendation |
|--------|----------------|
| Existing P&IDs | Obtain latest TM P&IDs for tie-in areas |
| Tie-in Points | Mark clearly with battery limit symbols at existing Sumas Terminal interface |
| Existing Equipment | Reference existing tags, do not re-tag |
| Match Lines | Use standard match line conventions per TM standards |
| Location | SW corner of TK-102 is installation area per SOW §2.3.1.1 |

---

## Trade-offs

### Design Trade-offs

| Trade-off | Option A | Option B | Recommendation |
|-----------|----------|----------|----------------|
| P&ID Density | High density (fewer sheets) | Lower density (more sheets) | Per TM preference; clarity priority |
| Auxiliary Systems | Include on main P&IDs | Separate auxiliary P&IDs | Separate for clarity |
| Vendor Integration | Full integration | Reference vendor drawings | Full integration per SOW §3.2.3.5 |
| Manifold Detail | All on one sheet | Multiple detail sheets | Based on complexity; consider clarity |

### Presentation Trade-offs

| Trade-off | Option A | Option B | Recommendation |
|-----------|----------|----------|----------------|
| Sheet Organization | By system | By area | By system preferred |
| Control Detail | Full loop diagrams | P&ID level only | P&ID level; loops in DEL-07.17 |
| Pump Grouping | All 5 on one sheet | Separate sheets | Consider clarity; separate if needed |

### Risk Considerations

| Risk | Mitigation |
|------|------------|
| TM symbol library unavailable | Request early from TM; use ISA as interim reference |
| Vendor P&IDs delayed | Flag dependency; develop placeholders; track in project schedule |
| HAZOP changes significant | Plan for IFC update cycle; maintain HAZOP action tracker |
| Tagging conflicts | Establish convention early with TM and coordinate with DEL-02.01, DEL-02.02, DEL-07.02 |
| Manifold complexity | Consider isometric or separate detail drawings for clarity |

---

## Examples

### Example 1: Typical P&ID Sheet Organization

```
Sheet 1: Legend and Symbol Sheet (per TM standards)
Sheet 2: Overall Key Diagram (if needed for navigation)
Sheet 3-4: Booster Pump P-[NNN]-A (Large)
Sheet 5-6: Booster Pump P-[NNN]-B (Large)
Sheet 7: Booster Pump P-[NNN]-C (Small)
Sheet 8: Booster Pump P-[NNN]-D (Small)
Sheet 9: Booster Pump P-[NNN]-E (Medium)
Sheet 10-11: Manifold System (5x6)
Sheet 12: Sump Tank and Reinjection System (per SOW §3.2.3.10)
Sheet 13-N: Utility Systems (as needed)
```

### Example 2: Pump P&ID Template Elements

```
+----------------------------------------------------------+
|  SUCTION SIDE           |  DISCHARGE SIDE                |
|                         |                                |
|  [From Manifold]        |     [FT-NNNN] (per SOW §2.3.1.4)|
|       |                 |        |                       |
|   [XV-NNNN]             |    [PI-NNNN]                   |
|       |                 |        |                       |
|   [PSV-NNNN]            |   [XV-NNNN]--->[To Pipeline]   |
|       |                 |        |                       |
|   [PI-NNNN]             |   [Min Flow Return]            |
|       |                 |                                |
|  [P-[NNN]-X]----[VFD]---+  (VFD per SOW §2.3.1.4)        |
|  (VS6 Pump)             |                                |
+----------------------------------------------------------+
Note: Tags shown are placeholders pending TM numbering convention
```

### Example 3: Line Numbering Convention

**ASSUMPTION:** Follow TM convention if available; otherwise typical format:
```
Line Number Format: SS-NNN-AAA-BB-CC-DD

Where:
  SS  = Service code (e.g., HC = Hydrocarbon)
  NNN = Nominal pipe size (inches)
  AAA = Sequential number
  BB  = Piping class
  CC  = Insulation code
  DD  = Heat trace code (if applicable)

Example:
  HC-16-001-A1-N-N = 16" Hydrocarbon line, Class A1, No insulation, No heat trace

**CRITICAL:** Coordinate with DEL-02.01 (Line List) and DEL-02.02 (Valve List) for consistency.
All line numbers on P&IDs must match Line List entries.
```

### Example 4: Instrument Tagging per ISA 5.1

```
Tag Format: XXXY-NNNN

Where:
  XXX = Function letters (e.g., FT = Flow Transmitter)
  Y   = Modifier (if applicable)
  NNNN = Loop/tag number

Examples for PSO scope:
  FT-1001  = Flow Transmitter, Pump A discharge (per SOW §2.3.1.4)
  FIC-1001 = Flow Indicating Controller, Loop 1001 (blending control)
  PSV-2001 = Pressure Safety Valve, Tag 2001
  XV-3001  = On/Off Valve, Tag 3001

**CRITICAL:** Coordinate with DEL-07.02 (Instrument Index) for consistency.
All instrument tags on P&IDs must match Instrument Index entries.
```

---

## Additional Resources

### Related Guidance Documents

| Document | Relevance |
|----------|-----------|
| DEL-01.01 Guidance | Design basis parameters - source for process data |
| DEL-01.02 Guidance | PFD consistency - P&IDs derived from PFDs |
| DEL-01.15 Guidance | HAZOP coordination - P&IDs must incorporate findings |
| DEL-07.02 Guidance | Instrument Index coordination |

### Coordination Points

| Discipline | Coordination Topic |
|------------|-------------------|
| Piping (PKG-02) | Line numbers, tie-in details, DEL-02.01 Line List |
| I&C (PKG-07) | Instrument tags, control philosophy, DEL-07.02 Index |
| Electrical (PKG-06) | VFD connections, motor details |
| Mechanical (PKG-03) | Equipment tags, ratings, vendor P&IDs |

### Coordination Checklist

- [ ] Obtain TM P&ID symbol library
- [ ] Obtain existing Sumas Terminal P&IDs for tie-in context
- [ ] Establish tagging conventions with TM
- [ ] Obtain control philosophy from TM per SOW §3.1.7.12
- [ ] Coordinate with I&C for instrument tags (DEL-07.02)
- [ ] Establish line numbering with Piping (DEL-02.01)
- [ ] Plan for vendor P&ID receipt and transformation per SOW §3.2.3.5
- [ ] Confirm 5x6 manifold interpretation with TM

---

*End of Guidance*
