# Guidance: DEL-01.13 Operating Envelopes

**Document ID:** DEL-01.13-GD
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Purpose

### 1.1 Document Intent

This guidance document provides recommendations and best practices for developing the Operating Envelopes document for the Puget Sound Optimization project. It supplements the formal specification with practical considerations for defining safe and efficient operating ranges.

### 1.2 Target Audience

- Process Engineers
- Operations Engineers
- Control Systems Engineers
- Safety Engineers
- TM Operations representatives

---

## 2. Principles

### 2.1 Foundational Principles

| Principle | Description |
|-----------|-------------|
| Safety First | Operating envelopes must ensure safe operation under all conditions |
| Operability | Envelopes must be practical for operations personnel to implement |
| Flexibility | Provide operational flexibility within safe limits |
| Clarity | Limits must be unambiguous and easy to understand |
| Conservatism | Include appropriate margins from equipment design limits |

### 2.2 Integration Principles

| Principle | Application |
|-----------|-------------|
| OL&PDS Alignment | Operating envelopes must align with TM protective device settings |
| Control System Integration | Envelopes must be implementable by the control system (DEL-07.09) |
| Hydraulic Consistency | Envelopes must be supported by hydraulic analysis (DEL-01.07) |
| Transient Compatibility | Envelopes must account for transient conditions (DEL-01.08) |

---

## 3. Considerations

### 3.1 Technical Considerations

#### 3.1.1 Throughput Targets
- Sustainable rate: 275,000 bpd (1,822 m3/h) per SOW-0232
- Peak rate: 315,000 bpd (2,100 m3/h) per SOW-0232
- Define turndown limits for each pump configuration (per DEL-01.04 equipment sizing)
- Consider minimum flow requirements for pump protection
- Reference hydraulic analysis (DEL-01.07) for flow capacity validation

#### 3.1.2 Blending Constraints
- **Open Issue (OI-002):** Blending ratio acceptance criteria differ between SOW-0232 and DBM (DEL-01.01)
  - SOW-0232: 20% Heavy to 80% Light
  - DBM (DEL-01.01): 10% - 100% (NEAT) component volumes
- Requires TM confirmation before finalizing operating envelopes
- Define acceptable blending accuracy/tolerance
- Coordinate with control narratives (DEL-07.09) for blending control implementation

#### 3.1.3 Pump Operating Envelopes
- Each pump type (large, small, medium) has unique performance envelope per DEL-01.04
- VFD provides variable speed operation within limits
- Consider pump curve stability at different speeds
- Define minimum continuous stable flow for each pump
- Consider NPSH requirements at all operating points
- Verify pump envelopes against vendor data and process datasheets (DEL-01.09)

#### 3.1.4 Suction Constraints
- Per DBM (DEL-01.01): Prevent reduction of tank operating volume due to low suction at increased rates
- Define minimum suction pressure for each pump
- Consider tank level vs. flow rate constraints
- Reference hydraulic analysis (DEL-01.07) for suction pressure validation

#### 3.1.5 Dynamic Operating Limits
- Consider transient conditions from start/stop operations
- Reference transient analysis (DEL-01.08) for surge pressures and flow transients
- Define safe ramp rates for flow changes
- Consider pressure wave propagation effects

### 3.2 Project Considerations

| Consideration | Recommendation |
|---------------|----------------|
| Existing Operations | Coordinate with TM operations for consistency |
| OL&PDS Updates | Determine if OL&PDS requires updates for new equipment |
| Operator Training | Envelopes should be clear for operations personnel |
| Control Narratives | Coordinate with DEL-07.09 for control implementation |
| HAZOP Integration | Operating envelopes will be reviewed during HAZOP (DEL-01.15) |

### 3.3 Quality Considerations

| Aspect | Recommendation |
|--------|----------------|
| Vendor Coordination | Obtain vendor-confirmed operating limits |
| Hydraulic Support | All limits should be supported by hydraulic analysis (DEL-01.07) |
| Transient Support | Dynamic limits validated by transient analysis (DEL-01.08) |
| Operations Input | Engage TM operations early in envelope development |
| Safety Review | HAZOP (DEL-01.15) will review envelopes for hazard identification |

---

## 4. Trade-offs

### 4.1 Design Trade-offs

| Trade-off | Option A | Option B | Recommendation |
|-----------|----------|----------|----------------|
| Operating Margin | Large margins (reduced capacity) | Tight margins (maximized capacity) | **TBD** - Per TM preference; validate with DEL-01.07 |
| Pump Selection | Run fewer large pumps | Run more small pumps | Based on efficiency optimization (DEL-01.04) |
| Blending Control | Tight ratio control | Wider ratio tolerance | **TBD** - Per product specs; OI-002 resolution |

### 4.2 Operability Trade-offs

| Trade-off | Option A | Option B | Recommendation |
|-----------|----------|----------|----------------|
| Mode Transitions | Manual intervention | Automatic sequences | **TBD** - Per control philosophy (DEL-07.09) |
| Upset Response | Conservative shutdown | Attempt recovery | **TBD** - Per safety philosophy; HAZOP review (DEL-01.15) |

### 4.3 Risk Considerations

| Risk | Mitigation |
|------|------------|
| Envelope too restrictive | Operations input in development |
| Envelope too permissive | Engineering review with safety margins |
| Blending ratio unclear | Obtain TM confirmation (OI-002) |
| Pump damage from minimum flow | Define minimum flow trips/alarms |
| Surge/transient damage | Validate with transient analysis (DEL-01.08) |
| Operational hazards | HAZOP review (DEL-01.15) will identify hazards |

---

## 5. Examples

### 5.1 Operating Envelope Format (Typical)

#### 5.1.1 Throughput Envelope

| Parameter | Unit | Minimum | Normal | Maximum | Alarm (Low) | Alarm (High) | Trip |
|-----------|------|---------|--------|---------|-------------|--------------|------|
| Total System Flow | m3/h | **TBD** | 1,822 | 2,100 | **TBD** | **TBD** | **TBD** |
| Per-Pump Flow (Large) | m3/h | **TBD** | **TBD** | **TBD** | **TBD** | N/A | **TBD** |
| Per-Pump Flow (Small) | m3/h | **TBD** | **TBD** | **TBD** | **TBD** | N/A | **TBD** |

**Note:** Values to be confirmed by hydraulic analysis (DEL-01.07) and equipment sizing (DEL-01.04)

#### 5.1.2 Pressure Envelope

| Parameter | Unit | Minimum | Normal | Maximum | Alarm | Trip |
|-----------|------|---------|--------|---------|-------|------|
| Suction Pressure | kPag | **TBD** | **TBD** | **TBD** | **TBD** | **TBD** |
| Discharge Pressure | kPag | **TBD** | **TBD** | **TBD** | **TBD** | **TBD** |

**Note:** Values from hydraulic analysis (DEL-01.07) and transient analysis (DEL-01.08)

### 5.2 Pump Operating Map (Conceptual)

```
Head (m)
  |
  |    *  *  *  *  *  *  *  <- Maximum Speed (60 Hz)
  |   *                    *
  |  *   OPERATING         *
  | *     ENVELOPE          *
  |*                         *
  |   *  *  *  *  *  *  *  * <- Minimum Speed (30 Hz)
  |
  +---------------------------- Flow (m3/h)
       Min Flow    Max Flow
```

**Note:** Actual curves to be based on vendor data and verified against DEL-01.04 and DEL-01.09

### 5.3 Operating Mode Matrix

| Mode | Pumps Running | Flow Range | Special Conditions |
|------|---------------|------------|-------------------|
| Normal - Full Rate | 2L + 1M or 2L + 2S | 1,500 - 2,100 m3/h | VFD speed control active |
| Normal - Reduced Rate | 1L + 1S or 2S | 800 - 1,500 m3/h | **TBD** |
| Turndown | 1S | **TBD** | Minimum practical flow |
| Startup | Per sequence | N/A | Line packing considerations (DEL-01.08) |
| Shutdown | Per sequence | N/A | Line pack preservation (DEL-01.08) |

**Note:** Modes and transitions to be coordinated with control narratives (DEL-07.09)

---

## 6. Additional Resources

### 6.1 Related Guidance Documents

| Document | Relevance |
|----------|-----------|
| DEL-01.01-GD | Design Basis Memorandum guidance for design parameters |
| DEL-01.04-GD | Equipment Sizing guidance for capacity limits |
| DEL-01.07-GD | Hydraulic Analysis guidance for pressure/flow envelopes |
| DEL-01.08-GD | Transient Analysis guidance for dynamic limits |
| DEL-01.09-GD | Process Datasheets guidance for equipment specifications |
| DEL-01.15-GD | HAZOP guidance for safety review of operating envelopes |
| DEL-07.09-GD | Control Narratives guidance for control implementation |

### 6.2 Industry References

| Reference | Application |
|-----------|-------------|
| API 610 | Pump operating limits |
| HI 9.6.3 | Pump allowable operating region |
| ISA-18.2 | Alarm management |
| CSA Z662 | Pipeline operating requirements |

### 6.3 Integration Points

| Integration Point | Related Deliverable | Purpose |
|-------------------|---------------------|---------|
| Design Basis | DEL-01.01 | Fundamental design parameters |
| Equipment Limits | DEL-01.04, DEL-01.09 | Equipment capacity and specifications |
| Hydraulic Validation | DEL-01.07 | Steady-state flow/pressure validation |
| Transient Validation | DEL-01.08 | Dynamic conditions validation |
| Control Implementation | DEL-07.09 | Control system implementation of envelopes |
| Safety Review | DEL-01.15 | HAZOP review of operating envelopes |

---

*End of Guidance*
