# Guidance: DEL-01.02 Process Flow Diagrams (PFDs)

**Document ID:** DEL-01.02-GD
**Revision:** Phase 2.2 (INITIALIZED)
**Date:** 2026-02-01
**Status:** INITIALIZED

---

## Purpose

### Document Intent

This guidance document provides recommendations and best practices for developing Process Flow Diagrams (PFDs) for the Puget Sound Optimization (PSO) project. It supplements the formal specification with practical considerations specific to the booster pump station, manifold system, and blending control at Sumas Tank Farm.

### Target Audience

- Process Engineers (lead and supporting)
- CAD/Drafting personnel
- Engineering Managers
- Document Control personnel

---

## Principles

### Foundational Principles

| Principle | Description |
|-----------|-------------|
| Clarity | PFDs should be easily readable and understood by all disciplines |
| Completeness | All major equipment and process streams should be represented |
| Consistency | Symbols, tagging, and formats should be consistent throughout |
| Traceability | Stream data should trace to DEL-01.01 DBM and DEL-01.07 Hydraulic Analysis |
| Maintainability | Structure should support efficient revision through IFC |
| Input Alignment | Reference Appendix B PFD as basis for development |

### PSO-Specific Considerations

| Consideration | Application | Source |
|---------------|-------------|--------|
| Booster Pump System | Five VS6-type pumps (2 Large + 2 Small + 1 Medium configuration) - show all units | SOW §2.3.1.2 |
| Manifold System | 5x6 manifold header - depict flow paths clearly | SOW §2.3.1.1 |
| Blending System | Show flow meters and control loops for blend ratio control | SOW §2.3.1.4 |
| VFD Integration | Each pump with VFD - indicate on PFD | SOW §2.3.1.4 |
| Flow Metering | Dedicated discharge flow meter per pump | SOW §2.3.1.4 |
| Brownfield Integration | Clearly identify tie-ins to existing Sumas Terminal systems | Site context |

---

## Considerations

### Technical Considerations

#### Flow Rate Representation

- Show both sustainable (275,000 bpd / 1,822 m³/h) and peak (315,000 bpd / 2,100 m³/h) flow cases (Source: SOW §2.2.1)
- Coordinate with DEL-01.07 Hydraulic Analysis for stream data
- Optimize piping/valve sizes and pump performance per SOW §3.1.3.2

#### Equipment Representation

| Equipment | Key Details to Show | Source |
|-----------|---------------------|--------|
| Booster Pumps (5) | Pump designation, VFD indication, discharge flow meter | SOW §2.3.1.1-4 |
| Large Capacity (2) | P-XXX-A, P-XXX-B with individual VFDs | SOW §2.3.1.2 |
| Small Capacity (2) | P-XXX-C, P-XXX-D with individual VFDs | SOW §2.3.1.2 |
| Medium Capacity (1) | P-XXX-E with individual VFD | SOW §2.3.1.2 |
| Manifold Headers | 5x6 configuration, flow paths | SOW §2.3.1.1 |
| Tanks | TK-102 reference (installation location SW corner) | SOW §2.3.1.1 |
| Control Valves | Major blending/isolation valves | Control philosophy |

#### Stream Data Tables

Recommended stream data parameters per stream:
- Stream number
- Description
- Flow rate (sustainable/design)
- Pressure (design per DEL-01.01 DBM)
- Temperature (design per DEL-01.01 DBM)
- Fluid type (crude, blend ratio if applicable - pending TM confirmation)

### Integration Considerations

| Integration Point | Recommendation |
|-------------------|----------------|
| DEL-01.01 DBM | Ensure stream data consistent with design basis - single source of truth |
| DEL-01.03 P&IDs | Use consistent equipment tagging for downstream development |
| DEL-01.07 Hydraulic Analysis | Reference hydraulic analysis for flow/pressure data |
| DEL-01.15 HAZOP | Structure PFDs to support HAZOP node identification |
| Appendix B Input PFD | Use as reference baseline for new PFD development |

### Brownfield Considerations

| Aspect | Recommendation |
|--------|----------------|
| Existing Facilities | Obtain latest TM PFDs for Sumas Terminal context |
| Tie-in Points | Clearly mark battery limits and tie-in identifications |
| Consistency | Match existing TM symbology where possible |
| Location Reference | Note SW corner of TK-102 as installation area |

---

## Trade-offs

### Design Trade-offs

| Trade-off | Option A | Option B | Recommendation |
|-----------|----------|----------|----------------|
| Detail Level | High detail (near P&ID) | Simplified overview | Simplified per PFD intent; detail in DEL-01.03 |
| Multiple Cases | Single operating case | Multiple cases (sustainable, peak) | Show key operating cases per SOW §2.2.1 |
| Blending Detail | Single blend case | Multiple blend ratios | **TBD** - Per TM direction on blend range |

### Presentation Trade-offs

| Trade-off | Option A | Option B | Recommendation |
|-----------|----------|----------|----------------|
| Drawing Count | Single comprehensive PFD | Multiple unit PFDs | Based on complexity; separate if needed for clarity |
| Stream Table | On-drawing | Separate document | On-drawing preferred for traceability |
| Pump Grouping | All 5 pumps on one sheet | Separate by capacity | Consider clarity; group logically |

### Risk Considerations

| Risk | Mitigation |
|------|------------|
| TM symbol library unavailable | Request early from TM; use ISA as interim reference |
| Hydraulic data incomplete | Document assumptions in stream table; flag for update with DEL-01.07 |
| Scope creep to P&ID detail | Maintain PFD-level abstraction; save detail for DEL-01.03 |
| Blending requirements unclear | Flag open item per SOW/DBM discrepancy; show conceptual approach |
| Input PFD interpretation | Review Appendix B with process team; clarify with TM if needed |

---

## Examples

### Example 1: Typical PFD Layout Structure

```
+--------------------------------------------------+
| TITLE BLOCK (TM Format)                          |
+--------------------------------------------------+
|                                                  |
|  LEGEND/NOTES                   STREAM TABLE     |
|  - Symbols                      - Stream No.     |
|  - Abbreviations                - Flow (sust/pk) |
|  - References to P&IDs          - P/T (design)   |
|                                                  |
+--------------------------------------------------+
|                                                  |
|              PROCESS SCHEMATIC                   |
|                                                  |
|  [Tanks] --> [5x6 Manifold] --> [5 VS6 Pumps]   |
|       (TK-102 area)     |            |          |
|                         v            v          |
|                   [Blending]  [To Puget Sound   |
|                   Control     Pipeline]          |
|                                                  |
+--------------------------------------------------+
|  REVISION BLOCK                                  |
+--------------------------------------------------+
```

### Example 2: Pump Representation (PSO Specific)

```
Booster Pump Configuration per SOW §2.3.1.2:

Large Capacity:
- P-XXX-A (Large) with VFD-XXX-A, FT-XXX-A
- P-XXX-B (Large) with VFD-XXX-B, FT-XXX-B

Small Capacity:
- P-XXX-C (Small) with VFD-XXX-C, FT-XXX-C
- P-XXX-D (Small) with VFD-XXX-D, FT-XXX-D

Medium Capacity:
- P-XXX-E (Medium) with VFD-XXX-E, FT-XXX-E

Each pump shall show:
- VFD indication (symbol or note)
- Discharge flow meter (FT-XXX)
- Connection to manifold
- Discharge to pipeline
```

### Example 3: Stream Numbering Convention

**ASSUMPTION:** Follow TM convention if available; otherwise:
```
Stream Numbering: NNN-SS

Where:
  NNN = Area/System identifier
  SS  = Sequential stream number

Example:
  100-01 = Tank outlet to manifold suction
  100-02 = Manifold header flow
  100-10 = Combined pump discharge to pipeline
  100-20 = Heavy crude stream (blending)
  100-21 = Light crude stream (blending)
```

---

## Additional Resources

### Related Guidance Documents

| Document | Relevance |
|----------|-----------|
| DEL-01.01 Guidance | Design basis parameters - stream data source |
| DEL-01.03 Guidance | P&ID development from PFDs |
| DEL-01.07 Guidance | Hydraulic analysis coordination - flow/pressure data |

### Reference Documents

| Reference | Application |
|-----------|-------------|
| Appendix B - PFD (IFR 2025-05-16) | Input PFD for reference and basis |
| ISA 5.1 | Symbol standards |
| API RP 14C | Process safety system representation reference |

### Coordination Checklist

- [ ] Obtain TM symbol library
- [ ] Review input PFD (Appendix B)
- [ ] Coordinate with DEL-01.01 DBM for design basis parameters
- [ ] Coordinate with DEL-01.07 Hydraulic Analysis for stream data (concurrent)
- [ ] Establish equipment tagging convention with TM
- [ ] Confirm drawing numbering with TM Document Control
- [ ] Clarify blending range requirements with TM (SOW vs DBM discrepancy)

---

*End of Guidance*
