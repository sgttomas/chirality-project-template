# Guidance: DEL-01.12 Battery Limit Table

**Document ID:** DEL-01.12-GD
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Purpose

### 1.1 Document Intent

This guidance document provides recommendations and best practices for developing the Battery Limit Table for the Puget Sound Optimization project. It supplements the formal specification (DEL-01.12-SP) with practical considerations for defining process interfaces.

### 1.2 Target Audience

- Process Engineers (developing DEL-01.01, DEL-01.03, DEL-01.07)
- Piping Engineers (developing DEL-02.01, DEL-02.03)
- Project Engineers (interface coordination per DEL-00.05, DEL-00.06)
- Interface Coordinators
- Operations representatives

---

## 2. Principles

### 2.1 Foundational Principles

| Principle | Description |
|-----------|-------------|
| Clarity | Interface conditions must be unambiguous and clearly defined |
| Compatibility | Conditions at battery limits must be compatible with existing facilities |
| Traceability | Each interface must trace to P&IDs (DEL-01.03), tie-in list (DEL-02.03), and existing documentation |
| Conservatism | Design conditions should account for worst-case scenarios per CSA Z662 and ASME B31.4 |
| Coordination | Early coordination with TM operations and existing facility documentation |

### 2.2 Integration Principles

| Principle | Application |
|-----------|-------------|
| Brownfield Context | Account for existing facility constraints and operating practices |
| Hydraulic Alignment | Interface conditions must support hydraulic model assumptions (DEL-01.07) |
| Tie-In Coordination | Battery limits must align with tie-in list (DEL-02.03) and piping scope |
| Design Basis Alignment | All parameters must trace to Design Basis Memorandum (DEL-01.01) |

---

## 3. Considerations

### 3.1 Technical Considerations

#### 3.1.1 Suction Side Interfaces
- Tank TK-101 and TK-102 suction connections per DBM (DEL-01.01)
- Consider low suction pressure concerns at increased throughput rates (per DEL-01.01 Section 2.2.2.4)
- Suction pressures based on tank head, static conditions, and hydraulic analysis (DEL-01.07)
- Verify compatibility with existing suction piping design

#### 3.1.2 Discharge Side Interfaces
- Puget Sound Pipeline delivery point
- 5x6 manifold discharge connections (per DBM Section 2.2.2)
- Consider blending ratio requirements:
  - SOW requirement: 20% Heavy to 80% Light
  - DBM flexibility: 10%-100% NEAT (per DEL-01.01)
- Discharge pressure per hydraulic analysis (DEL-01.07)

#### 3.1.3 Utility Interfaces
- Instrument air supply from existing terminal infrastructure
- Electrical power from new/existing substations (coordinate with PKG-06)
- Fire water from existing fire protection system
- Instrumentation signals (coordinate with PKG-07)

### 3.2 Project Considerations

| Consideration | Recommendation |
|---------------|----------------|
| Existing Drawings | Obtain latest TM P&IDs and plot plans for existing interfaces |
| Operating Data | Request historical operating data from TM for normal conditions |
| Shutdown Planning | Consider implications for tie-in activities (per DEL-02.03 procedure) |
| Future Expansion | Document whether battery limits should accommodate future growth |
| Interface Management | Follow DEL-00.05 Interface Management Plan requirements |

### 3.3 Quality Considerations

| Aspect | Recommendation |
|--------|----------------|
| TM Verification | Obtain TM confirmation that interface conditions match existing facility design |
| Consistency Check | Verify battery limit conditions are consistent with DEL-01.01 and DEL-01.07 |
| Piping Coordination | Coordinate with piping discipline on DEL-02.03 tie-in list development |
| Line Designation | Verify line numbers match DEL-02.01 Line List |
| P&ID Alignment | Ensure interface locations match DEL-01.03 P&IDs |

---

## 4. Trade-offs

### 4.1 Design Trade-offs

| Trade-off | Option A | Option B | Recommendation |
|-----------|----------|----------|----------------|
| Pressure Rating | Match existing | Higher rating for margin | Verify with TM; follow CSA Z662 requirements |
| Temperature Range | Normal operating range | Full design range | Include full design range per DEL-01.01 |
| Flow Capacity | Current throughput (275,000 bpd) | Peak capacity (315,000 bpd) | Design for peak per SOW Section 2.2.1 |

### 4.2 Documentation Trade-offs

| Trade-off | Option A | Option B | Recommendation |
|-----------|----------|----------|----------------|
| Granularity | Individual connections | Aggregated by system | Individual connections for traceability |
| Operating Data | Design conditions only | Include normal/min/max | Include all operating cases per specification |
| Cross-References | Minimal | Comprehensive | Comprehensive per DEL-00.05 |

### 4.3 Risk Considerations

| Risk | Mitigation |
|------|------------|
| Incomplete existing facility data | Early request for TM documentation; follow up via DEL-00.06 |
| Interface condition mismatch | TM verification before IFD; coordinate via DEL-00.05 |
| Hydraulic model changes | Document assumptions; plan for updates aligned with DEL-01.07 |
| Tie-in scope changes | Maintain alignment with DEL-02.03 Tie-In List |

---

## 5. Examples

### 5.1 Battery Limit Table Structure (Typical)

| BL ID | P&ID | Line No. | Service | Dir | Size | Class | Design P (kPa) | Design T (°C) | Normal Flow (m³/h) | Fluid | Remarks |
|-------|------|----------|---------|-----|------|-------|----------------|---------------|-------------------|-------|---------|
| BL-001 | P&ID-001 | 24"-HC-001 | Heavy Crude Suction | IN | 24" | 300# | Per DEL-01.07 | Per DEL-01.01 | 1,822 (sustainable) | Heavy Crude | From TK-102 |
| BL-002 | P&ID-001 | 24"-LC-001 | Light Crude Suction | IN | 24" | 300# | Per DEL-01.07 | Per DEL-01.01 | 1,822 (sustainable) | Light Crude | From TK-101 |
| BL-003 | P&ID-002 | 30"-BL-001 | Blended Discharge | OUT | 30" | 600# | Per DEL-01.07 | Per DEL-01.01 | 2,100 (peak) | Blended | To PS Pipeline |

### 5.2 Typical Battery Limit Parameters

| Parameter | Typical Range | Notes |
|-----------|---------------|-------|
| Design Pressure | Per DEL-01.07 hydraulic analysis | Include surge/transient margin per ASME B31.4 |
| Design Temperature (Max) | +65°C to +100°C | Per crude properties in DEL-01.01 |
| Design Temperature (Min) | -29°C to -40°C | Per ambient conditions in DEL-01.01 |
| Corrosion Allowance | Per TM standards | Verify with existing facility data |

### 5.3 Coordination Checklist

- [ ] Existing facility P&IDs obtained from TM
- [ ] Existing line numbers/sizes confirmed with TM
- [ ] Existing pressure classes confirmed with TM
- [ ] Historical operating data obtained from TM
- [ ] TM operations consulted
- [ ] Tie-in list alignment verified (DEL-02.03)
- [ ] Line list alignment verified (DEL-02.01)
- [ ] P&ID alignment verified (DEL-01.03)
- [ ] Hydraulic model interface conditions aligned (DEL-01.07)
- [ ] Design basis parameters aligned (DEL-01.01)
- [ ] Interface register updated (DEL-00.06)
- [ ] TM verification obtained

---

## 6. Additional Resources

### 6.1 Related Guidance Documents

| Document | Relevance |
|----------|-----------|
| DEL-01.01-GD | Design basis parameters and fluid properties |
| DEL-01.03-GD | P&ID development and interface representation |
| DEL-01.07-GD | Hydraulic analysis integration and pressure/flow data |
| DEL-02.01-GD | Line list coordination and line numbering |
| DEL-02.03-GD | Tie-in list coordination and interface activities |
| DEL-00.05-GD | Interface management principles and procedures |
| DEL-00.06-GD | Interface register/schedule tracking |

### 6.2 Industry References

| Reference | Application |
|-----------|-------------|
| CSA Z662 | Oil and Gas Pipeline Systems - design requirements |
| ASME B31.4 | Pipeline Transportation Systems for Liquids |
| ASME B16.5 | Pipe Flanges and Flanged Fittings - rating tables |
| API RP 14C | Analysis, Design, Installation, and Testing of Basic Surface Safety Systems |
| ISA-5.1 | Instrumentation Symbols and Identification |

---

*End of Guidance*
