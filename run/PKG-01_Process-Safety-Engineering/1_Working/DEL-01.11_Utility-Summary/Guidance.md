# Guidance: DEL-01.11 Utility Summary

**Document ID:** DEL-01.11-GD
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Purpose

### 1.1 Document Intent

This guidance document provides recommendations and best practices for developing the Utility Summary table for the Puget Sound Optimization project. It supplements the formal specification (DEL-01.11-SP) with practical considerations for compiling utility demands.

### 1.2 Target Audience

- Process Engineers
- Electrical Engineers
- Mechanical Engineers
- HVAC Engineers
- Instrumentation & Controls Engineers
- Project Engineers

---

## 2. Principles

### 2.1 Foundational Principles

| Principle | Description |
|-----------|-------------|
| Completeness | All utility consumers must be captured, no omissions |
| Accuracy | Values must align with equipment datasheets and calculations |
| Traceability | Each entry must be traceable to source documentation |
| Consistency | Units and naming conventions must be consistent throughout |
| Conservatism | Use nameplate/connected loads where operating data is unavailable |

### 2.2 Integration Principles

| Principle | Application |
|-----------|-------------|
| Cross-Discipline Coordination | Gather inputs from all disciplines (electrical, mechanical, HVAC, I&C) |
| Equipment List Alignment | Utility Summary equipment tags must match equipment list (DEL-03.01) |
| Design Basis Alignment | Utility demands must be consistent with DBM parameters (DEL-01.01) |

---

## 3. Considerations

### 3.1 Technical Considerations

#### 3.1.1 Electrical Power
- **ASSUMPTION:** New 25kV utility feed assessment may impact electrical utility summary
- Consider VFD efficiency when determining operating loads
- Include building loads (lighting, HVAC, receptacles) for new electrical building
- Document demand factors used for calculating operating loads
- Cross-reference with electrical load list (DEL-06.03)

#### 3.1.2 Instrument Air
- Account for all pneumatic actuators identified on P&IDs (DEL-01.03)
- Include continuous consumers (positioners, purge air) and intermittent consumers (actuators)
- Apply appropriate diversity factors
- Reference ISA-5.1 for instrumentation utility requirements

#### 3.1.3 Cooling Water
- VFD cooling requirements depend on enclosure type (air-cooled vs. water-cooled)
- Pump seal cooling requirements per process datasheets (DEL-01.09)
- **TBD:** Confirm VFD cooling method with electrical/mechanical disciplines

#### 3.1.4 Fire Water
- Fire water demands based on fire protection philosophy and NFPA requirements
- Coordinate with fire protection engineering (within PKG-01 scope)
- **ASSUMPTION:** Fire water requirements determined by separate fire protection analysis

### 3.2 Project Considerations

| Consideration | Recommendation |
|---------------|----------------|
| Brownfield Integration | Coordinate with existing Sumas Terminal utility infrastructure |
| Existing Utility Capacity | Confirm existing utilities can support new loads |
| Future Expansion | Consider whether design margins should account for future growth |
| Cross-Border Aspects | Verify applicable standards for US-side facilities |

### 3.3 Quality Considerations

| Aspect | Recommendation |
|--------|----------------|
| Source Documentation | Reference specific datasheets and calculations for each value |
| Unit Consistency | Use consistent units throughout (e.g., kW not HP for power) |
| Peer Review | Cross-check totals with discipline leads before submission |
| Version Control | Maintain revision history per document control requirements |

---

## 4. Trade-offs

### 4.1 Data Collection Trade-offs

| Trade-off | Option A | Option B | Recommendation |
|-----------|----------|----------|----------------|
| Load Values | Use vendor data (when available) | Use calculated estimates | Prefer vendor data; use calculations for early phases |
| Diversity Factors | Conservative (low diversity) | Optimized (higher diversity) | **TBD** - Per TM preference |
| Future Allowance | Include growth margin | Exclude growth margin | **TBD** - Per project requirements |

### 4.2 Format Trade-offs

| Trade-off | Option A | Option B | Recommendation |
|-----------|----------|----------|----------------|
| Granularity | Individual equipment | System-level summaries | Individual equipment preferred for traceability |
| Breakdown | By area/system | By utility type | Both views useful; primary by utility type |

### 4.3 Risk Considerations

| Risk | Mitigation |
|------|------------|
| Incomplete equipment list | Coordinate with DEL-03.01 development schedule |
| Missing vendor data | Use engineering estimates; flag for update at IFD/IFC |
| Utility infrastructure constraints | Early coordination with TM operations |
| Cross-discipline inconsistencies | Establish utility summary data collection schedule per DEL-01.11-PR |

---

## 5. Examples

### 5.1 Utility Summary Table Structure (Typical)

| Utility Type | Tag No. | Description | Connected Load | Operating Load | Peak Load | Units | Remarks |
|--------------|---------|-------------|----------------|----------------|-----------|-------|---------|
| Electrical (480V) | P-2501A | Booster Pump #1 | **TBD** | **TBD** | **TBD** | kW | Large-capacity pump |
| Electrical (480V) | VFD-2501A | VFD for P-2501A | **TBD** | **TBD** | **TBD** | kW | Included in pump load |
| Instrument Air | FV-2501 | Flow Control Valve | 2 | 0.5 | 2 | SCFM | Continuous positioner |
| **SUBTOTAL** | | Electrical (480V) | **TBD** | **TBD** | **TBD** | kW | |

### 5.2 Typical Utility Types for Pipeline Terminal

| Utility Type | Typical Consumers | Notes |
|--------------|-------------------|-------|
| Electrical (25kV) | Main power feed | Distribution to substations |
| Electrical (4.16kV) | Large motors >200HP | **TBD** - Confirm motor sizes |
| Electrical (480V) | Motors, VFDs, building loads | Majority of consumers |
| Electrical (120V) | Instrumentation, lighting, receptacles | Control systems, building |
| Instrument Air | Actuators, instruments | Pneumatic devices |
| Cooling Water | Pump seals, VFD cooling | **TBD** - Confirm applicability |
| Fire Water | Deluge, hydrants, monitors | Per fire protection design |

### 5.3 Data Collection Checklist

- [ ] Equipment list finalized (DEL-03.01)
- [ ] Pump motor ratings confirmed (DEL-01.09)
- [ ] VFD ratings and quantities confirmed (DEL-06.03)
- [ ] Instrument air consumers identified from P&IDs (DEL-01.03)
- [ ] Building HVAC loads calculated (DEL-09.01)
- [ ] Fire protection demands determined
- [ ] Existing utility capacity confirmed with TM
- [ ] All equipment tags verified against equipment list

---

## 6. Additional Resources

### 6.1 Related Guidance Documents

| Document | Relevance |
|----------|-----------|
| DEL-01.01 Guidance | Design basis methodology |
| DEL-01.03 Guidance | P&ID development |
| DEL-03.01 Guidance | Equipment list development |
| DEL-06.03 Guidance | Electrical load list |
| DEL-09.01 Guidance | HVAC load calculations |

### 6.2 Industry References

| Reference | Application |
|-----------|-------------|
| API RP 686 | Rotating equipment utility requirements |
| ISA-5.1 | Instrumentation utility requirements |
| ASHRAE Handbook | Building utility requirements |
| NFPA 30 | Flammable liquids facilities |

---

*End of Guidance*
