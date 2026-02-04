# Guidance: DEL-01.16 Material Requisitions (Process) (Engineering)

**Document ID:** DEL-01.16-GU
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Purpose

This guidance document provides context, best practices, and recommendations for developing Process Engineering Material Requisitions (MRs) for the Puget Sound Optimization (PSO) project. Well-prepared MRs ensure that procured equipment meets technical requirements while supporting competitive bidding and schedule objectives.

---

## 2. Principles

### 2.1 Technical Completeness

- Include all information needed for vendors to provide accurate bids
- Specify performance requirements clearly and unambiguously
- Reference applicable standards for areas not explicitly detailed
- Attach complete datasheets (DEL-01.09) with design parameters

### 2.2 Procurement Efficiency

- Allow reasonable alternatives where equivalent performance can be achieved
- Avoid over-specification that limits competition or increases cost
- Provide clear bid evaluation criteria
- Coordinate schedule requirements with TM Procurement

### 2.3 Quality Assurance

- Specify testing and inspection requirements appropriate to equipment criticality
- Include quality documentation requirements
- Define acceptance criteria for factory tests
- Specify vendor data requirements clearly

### 2.4 Standardization

- Align with TM existing equipment where possible
- Consider spare parts commonality with existing fleet
- Use TM-preferred vendors where available and competitive
- Follow TM naming conventions and documentation standards

---

## 3. Considerations

### 3.1 Technical Considerations

| Consideration | Guidance |
|---------------|----------|
| Operating Range | Specify full operating range, not just design point (per DEL-01.04) |
| Turndown | Consider minimum flow and turndown requirements |
| Future Expansion | Consider capacity for potential future expansion |
| Maintainability | Specify maintenance access and requirements |
| Spares Interchangeability | Consider commonality with existing TM equipment |

### 3.2 PSO-Specific Considerations

| Item | Consideration | Source |
|------|---------------|--------|
| Pump Type | VS6 vertical inline pumps specified in SOW | SOW Section 2.3.1.2 |
| VFD Operation | All pumps to be VFD-driven; specify VFD-rated motors | SOW Section 2.3.1.2 |
| Pump Sizing | 2 large + 2 small + 1 medium configuration | SOW Section 2.3.1.2 |
| Flow Metering | 5 discharge flow meters for blending control | SOW Section 2.3.1.4 |
| Service | Heavy/light crude blending service | Project scope (DEL-01.01) |
| Site Constraints | Limited footprint at Sumas Tank Farm | SOW Section 2.3.1.1 |

### 3.3 Lead Time Considerations

| Equipment | Typical Lead Time | MR Timing |
|-----------|-------------------|-----------|
| Booster Pumps (API 610) | 20-30 weeks | Early in detailed design |
| Flow Meters | 12-16 weeks | With pump MRs |
| Valves (large/special) | 16-24 weeks | Early in detailed design |
| Valves (standard) | 8-12 weeks | Mid detailed design |
| Piping Bulks | 8-12 weeks | Per fabrication schedule |

**ASSUMPTION:** Lead times based on typical industry experience; confirm with vendors.

---

## 4. Trade-offs

### 4.1 Specification Detail vs. Flexibility

| Approach | Advantages | Disadvantages |
|----------|------------|---------------|
| Highly Detailed Spec | Precise requirements, easier evaluation | Limits competition, may increase cost |
| Performance-Based Spec | More flexibility, broader competition | Harder to evaluate, may get surprises |
| **Recommended:** Specify critical performance and safety requirements precisely; allow flexibility on non-critical features |

### 4.2 Approved Vendor List

| Approach | Advantages | Disadvantages |
|----------|------------|---------------|
| Restrictive List | Known quality, proven track record | Limited competition, potentially higher cost |
| Open Bidding | More competition, potentially lower cost | Risk of unknown vendors, more evaluation effort |
| **Recommended:** Use TM-approved vendor list as preferred; allow alternates with additional qualification |

### 4.3 Testing Requirements

| Approach | Advantages | Disadvantages |
|----------|------------|---------------|
| Extensive Shop Testing | Higher confidence, problems found early | Additional cost, longer schedule |
| Minimum Required Testing | Lower cost, faster delivery | Risk of field problems |
| **Recommended:** Full API testing for critical equipment (pumps); standard testing for commodity items |

### 4.4 Spare Parts Strategy

| Approach | Advantages | Disadvantages |
|----------|------------|---------------|
| Comprehensive Initial Spares | Ready availability, may get better pricing | Higher initial cost, storage requirements |
| Minimal Initial Spares | Lower initial cost | Risk of delays if parts needed |
| **Recommended:** Capital spares and 2-year operating spares with initial order; consider existing TM inventory |

---

## 5. Examples

### 5.1 Example MR Structure - Booster Pump

**MR-PSO-PROC-001: Booster Pumps (VS6)**

| Section | Content Summary |
|---------|-----------------|
| 1. Scope | Supply of 5 VS6 vertical inline booster pumps per API 610 |
| 2. Design Conditions | Per datasheet DS-P-101 through DS-P-105 (DEL-01.09) |
| 3. Technical Requirements | API 610, 12th Edition compliance; VFD-rated motors; mechanical seals per API 682 |
| 4. Materials | Casing: Carbon steel; Impeller: 12% Cr steel; Shaft: 17-4PH SS |
| 5. Testing | Full API 610 testing including: Hydrostatic, Performance, NPSH, Mechanical |
| 6. Documentation | Per API 610; include certified curves, GA drawings, O&M manual |
| 7. Spare Parts | Per attached spare parts list; 2-year operating spares |
| 8. Quality | ISO 9001 certified manufacturer; TM inspection during manufacture |
| Attachments | Datasheet (DEL-01.09), P&ID reference (DEL-01.03), GA sketch, approved vendor list |

### 5.2 Example Datasheet Extract - Pump

| Parameter | Value | Notes |
|-----------|-------|-------|
| Tag | P-101 | Large capacity pump (per DEL-01.07) |
| Service | Heavy Crude Booster | Blending service |
| Design Flow | **TBD** m3/h | Per sizing calc (DEL-01.04) |
| Design Head | **TBD** m | Per sizing calc (DEL-01.04) |
| NPSH Available | **TBD** m | Per hydraulic analysis (DEL-01.04) |
| Fluid | Crude Oil | SG: 0.85-0.95 (per DEL-01.01) |
| Design Temp | **TBD** degC | Per Design Basis Memo (DEL-01.01) |
| Design Pressure | **TBD** kPag | Per hydraulic analysis (DEL-01.04) |
| Driver | Electric Motor, VFD | Per SOW Section 2.3.1.2 |
| Motor Power | **TBD** kW | Per sizing calc (DEL-01.04) |

### 5.3 Common Pitfalls to Avoid

1. **Incomplete datasheets** - Missing process conditions lead to incorrect sizing (verify DEL-01.09 complete)
2. **Vague specifications** - Ambiguous requirements create bid evaluation difficulties
3. **Over-specification** - Unnecessary requirements increase cost without benefit
4. **Missing standards** - Failure to reference applicable codes creates quality gaps
5. **Inadequate testing** - Insufficient testing leads to field problems
6. **Ignoring lead time** - Late MR issue impacts project schedule
7. **Poor coordination** - Mismatch between process and other discipline requirements (coordinate with PKG-02, PKG-06, PKG-07)

### 5.4 Example MR Review Checklist

| Item | Check |
|------|-------|
| Equipment tag matches equipment list (DEL-01.07) | [ ] |
| Datasheet current revision attached (DEL-01.09) | [ ] |
| Design conditions match simulation/calculations (DEL-01.04) | [ ] |
| Material specifications complete (per PKG-02 for piping) | [ ] |
| Testing requirements appropriate for criticality | [ ] |
| Vendor list reviewed with TM | [ ] |
| Spare parts requirements included | [ ] |
| Documentation requirements stated | [ ] |
| Delivery requirements coordinated with schedule | [ ] |
| Commercial terms coordinated with Procurement | [ ] |

---

*End of Guidance*
