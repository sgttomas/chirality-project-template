# Datasheet: DEL-01.03 Piping & Instrumentation Diagrams (P&IDs)

**Document ID:** DEL-01.03-DS
**Revision:** Phase 2.2 (INITIALIZED)
**Date:** 2026-02-01
**Status:** INITIALIZED

---

## Identification

| Field | Value |
|-------|-------|
| Deliverable ID | DEL-01.03 |
| Deliverable Name | Piping & Instrumentation Diagrams (P&IDs) |
| Parent Package | PKG-01 Process & Safety Engineering |
| Discipline | Process/Safety |
| Document Type | Drawing |
| Responsible Party | Engineering Contractor |

---

## Attributes

### Technical Attributes

| Attribute | Value | Notes |
|-----------|-------|-------|
| Drawing Size | **TBD** | **ASSUMPTION:** D-size (22"x34") typical |
| Drawing Format | CAD (AutoCAD/MicroStation) | Per TM requirements |
| Scale | Not to scale (schematic) | Standard for P&IDs |
| Numbering Convention | **TBD** | Per TM drawing numbering system |

### Drawing Set Composition

| Component | Estimated Count | Notes |
|-----------|-----------------|-------|
| Booster Pump Station P&IDs | **TBD** | 5 VS6-type pumps (2 Large+2 Small+1 Medium) per SOW §2.3.1.2 |
| Manifold System P&IDs | **TBD** | 5x6 manifold headers per SOW §2.3.1.1 (interpretation TBD with TM) |
| Auxiliary Systems P&IDs | **TBD** | Sump, reinjection, dewatering per SOW §3.2.3.10 |
| Legend/Symbol Sheet | 1 | Per TM standards |
| Vendor P&ID Transformations | **TBD** | Convert vendor P&IDs per SOW §3.2.3.5 |

### Document Attributes

| Attribute | Value |
|-----------|-------|
| Anticipated Artifacts | P&ID drawing set |
| Native Format | CAD (dwg/dgn) |
| Deliverable Format | PDF + Native CAD files per SOW §3.2.3.18 |
| Revision Cycle | IFR → IFD → IFC |
| Phase Coverage | FEED through Detailed Design |

---

## Conditions

### Design Parameters (from DBM)

| Parameter | Value | Units | Source |
|-----------|-------|-------|--------|
| Sustainable Flow Rate | 275,000 | bpd | SOW §2.2.1 |
| Sustainable Flow Rate | 1,822 | m³/h | Converted |
| Design (Peak) Flow Rate | 315,000 | bpd | SOW §2.2.1 |
| Design (Peak) Flow Rate | 2,100 | m³/h | DBM §2.2.1.1 |
| Blending Range (SOW) | 20% Heavy to 80% Light | - | SOW §2.3.1.4 |
| NEAT Operation (DBM) | 10-100% component | - | DBM §2.2.2.2 |
| Design Pressure | **TBD** | kPag | Per DEL-01.01 |
| Design Temperature | **TBD** | °C | Per DEL-01.01 |

### Equipment to be Depicted

| Equipment Type | Quantity | Tag Prefix | Source |
|----------------|----------|------------|--------|
| Booster Pumps (VS6) | 5 | P-[NNN]-X | SOW §2.3.1.1 (tags TBD with TM) |
| Large Capacity Pumps | 2 | P-[NNN]-A/B | SOW §2.3.1.2 |
| Small Capacity Pumps | 2 | P-[NNN]-C/D | SOW §2.3.1.2 |
| Medium Capacity Pump | 1 | P-[NNN]-E | SOW §2.3.1.2 |
| VFDs (one per pump) | 5 | VFD-[NNN] | SOW §2.3.1.4 (tags TBD) |
| Flow Meters (Discharge) | 5 | FT-[NNNN] | SOW §2.3.1.4, DEL-07.02 |
| Manifold Headers | 5x6 config | **TBD** | SOW §2.3.1.1 (interpretation TBD) |
| Control Valves | **TBD** | CV-[NNNN] | Per blending/isolation (tags TBD) |
| Sump Tank | **TBD** | T-[NNN] | SOW §3.2.3.10 (tags TBD) |
| Reinjection Pumps | **TBD** | P-[NNN] | SOW §3.2.3.10 (tags TBD) |

### Operating Modes

| Mode | Description | Notes |
|------|-------------|-------|
| Normal Operation | Sustainable flow (275,000 bpd) | Primary design case |
| Peak Operation | Design flow (315,000 bpd) | Equipment sizing case |
| Blending | Heavy/Light ratio control | Per SOW §2.3.1.4 |
| NEAT Operation | Single component | 10-100% per DBM |
| Tank Transfer | Tank-to-tank | Flexibility per DBM §2.2.2.1 |

---

## Construction

### P&ID Content Requirements

Each P&ID shall include:
- All process equipment with tag numbers
- All piping with line numbers, sizes, and specifications
- All valves (manual, control, safety, check) with tags
- All instruments with ISA 5.1 identification
- Control loops and interlocks
- Equipment ratings and data
- Line specifications and insulation requirements
- Utility connections
- Battery limits and tie-ins to existing Sumas Terminal
- Notes and references to DEL-01.02 PFDs

### Symbol Standards

| Item | Standard | Notes |
|------|----------|-------|
| Equipment | TM Standard / ISA | All equipment types |
| Valves | TM Standard / ISA | Per TM symbols/legends/tagging |
| Instruments | ISA 5.1 | Full instrument identification |
| Piping | TM Standard | Line type, specifications |
| Control Logic | ISA 5.1 | Control loops, interlocks |
| VFDs | TM Standard | Variable frequency drive |

### Vendor P&ID Transformation Requirements

Per SOW §3.2.3.5 (transform vendor P&IDs) and §3.2.3.6 (develop auxiliary P&IDs):
- Transform vendor P&IDs to project P&IDs per TM symbols/legends/tagging
- Develop new P&IDs for auxiliary systems as needed
- Ensure consistent tagging throughout drawing set
- Coordinate all tags with DEL-02.01 (Line List), DEL-02.02 (Valve List), DEL-07.02 (Instrument Index)

### Dependencies

| Dependency | Source | Status |
|------------|--------|--------|
| Design Basis (DBM) | DEL-01.01 | Required before P&ID development |
| Process Flow Diagrams | DEL-01.02 | Required before P&ID development |
| Line List | DEL-02.01 | Coordinate for line numbering |
| Valve List | DEL-02.02 | Coordinate for valve tagging |
| Instrument Index | DEL-07.02 | Coordinate for instrument tagging |
| TM Symbol Library | TM Standards | **TBD** - Required before drafting |
| Control Philosophy | TM / PKG-07 | **TBD** per SOW §3.1.7.12 |
| Vendor P&IDs | Vendor packages | **TBD** - For transformation |
| Existing P&IDs | TM Archives | **TBD** - For brownfield context |

---

## References

### Source Documents

| Document | Reference |
|----------|-----------|
| SOW Reference | SOW-0112: Produce FEED P&IDs (GS) |
| SOW Reference | SOW-0223: Update/finalize P&IDs to IFC |
| SOW Reference | SOW-0232: IFC process deliverables including P&IDs |
| Decomposition | Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md |

### Related Deliverables

| Deliverable ID | Relationship |
|----------------|--------------|
| DEL-01.01 | DBM provides design basis |
| DEL-01.02 | PFDs provide process overview |
| DEL-01.10 | Valve Numbering Diagrams - derived from P&IDs |
| DEL-01.15 | HAZOP Report - P&IDs updated per findings (IFC stage) |
| DEL-02.01 | Line List - coordinate line numbers with P&IDs |
| DEL-02.02 | Valve List - coordinate valve tags with P&IDs |
| DEL-07.02 | Instrument Index - coordinate instrument tags with P&IDs |
| DEL-00.01 | MDR registration required |

### Applicable Standards

| Standard | Description |
|----------|-------------|
| ISA 5.1 | Instrumentation Symbols and Identification |
| TM Drawing Standards | **TBD** - Project-specific |
| TM P&ID Standards | **TBD** - Symbols/legends/tagging per SOW §3.2.3.5 |

---

*End of Datasheet*
