# Datasheet: DEL-01.11 Utility Summary

**Document ID:** DEL-01.11-DS
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Identification

| Field | Value |
|-------|-------|
| Deliverable ID | DEL-01.11 |
| Deliverable Name | Utility Summary |
| Parent Package | PKG-01 Process & Safety Engineering |
| Discipline | Process/Safety |
| Document Type | Table |
| Responsible Party | Engineering Contractor |

---

## 2. Attributes

### 2.1 Technical Attributes

| Attribute | Value | Notes |
|-----------|-------|-------|
| Project Phase | Detailed Design | Per SOW-0232 (IFC deliverables set) |
| Facility Location | Sumas Tank Farm | Per PSO project scope |
| Utility Systems | Electrical, Instrument Air, Cooling Water, Fuel Gas, Fire Water, Potable Water, etc. | **ASSUMPTION:** Typical pipeline terminal utilities |
| Format | Tabular summary | Per SOW-0232 requirement |

### 2.2 Document Attributes

| Attribute | Value |
|-----------|-------|
| Anticipated Artifacts | Utility Summary table |
| Native Format | Excel (.xlsx) |
| Deliverable Format | PDF + Excel native |
| Revision Cycle | IFR -> IFD -> IFC |

---

## 3. Conditions

### 3.1 Utility Categories

| Utility Type | Description | Units | Notes |
|--------------|-------------|-------|-------|
| Electrical Power | Total connected/operating load | kW | By voltage level (480V, 4.16kV, 25kV) |
| Instrument Air | Consumption for instruments/actuators | SCFM | **TBD** - Per equipment count |
| Cooling Water | Pump/VFD cooling requirements | gpm | **TBD** - Per equipment datasheets |
| Fire Water | Fire suppression/deluge requirements | gpm | **TBD** - Per fire protection design |
| Potable Water | Building/safety shower requirements | gpm | **ASSUMPTION:** Minimal for unmanned facility |
| Nitrogen | Purging/blanketing (if applicable) | SCFH | **TBD** - Confirm applicability |
| Fuel Gas | Building heating (if applicable) | SCFH | **TBD** - Confirm applicability |

### 3.2 Design Basis

| Parameter | Value | Source |
|-----------|-------|--------|
| Site Location | Sumas Tank Farm, SW corner of TK-102 | SOW: Section 2.3.1.1 |
| New Equipment | 5 VS6 booster pumps, 5x6 manifold, containment wall | SOW: Section 2.3.1.1 |
| VFD Count | 5 (one per booster pump) | SOW: Section 2.3.1.4 |
| Flow Meters | 5 (discharge, one per pump) | SOW: Section 2.3.1.4 |
| New Electrical Building | Yes | SOW: Section 3.1.5 |

---

## 4. Construction

### 4.1 Table Structure (Typical)

| Column | Description |
|--------|-------------|
| Utility Type | Category of utility service |
| Tag Number | Equipment/system tag |
| Description | Brief description of consumer |
| Connected Load | Maximum/nameplate demand |
| Operating Load | Typical/normal demand |
| Peak Load | Short-duration peak demand |
| Units | Unit of measurement |
| Remarks | Notes, references, or conditions |

### 4.2 Content Requirements

The Utility Summary shall include:
- All utility demands for new PSO facilities at Sumas Tank Farm
- Both connected and operating loads
- Peak/upset condition demands where applicable
- Cross-reference to equipment list (DEL-03.01) and electrical load list (DEL-06.03)
- Summary totals by utility type

### 4.3 Dependencies

| Dependency | Source | Status |
|------------|--------|--------|
| Equipment List | DEL-03.01 | **TBD** |
| Electrical Load List | DEL-06.03 | **TBD** |
| Process Datasheets | DEL-01.09 | **TBD** |
| P&IDs | DEL-01.03 | **TBD** |
| HVAC Load Calculations | DEL-09.01 | **TBD** |

---

## 5. References

### 5.1 Source Documents

| Document | Reference |
|----------|-----------|
| SOW Reference | SOW-0232: Provide IFC process deliverables set including... utility summary... |
| Decomposition | Puget_Sound_Optimization_Project_Decomposition_REVISED_v2.md |

### 5.2 Related Deliverables

| Deliverable ID | Relationship |
|----------------|--------------|
| DEL-01.01 | DBM provides design basis for utility requirements |
| DEL-01.03 | P&IDs identify utility consumers |
| DEL-01.09 | Process datasheets provide equipment utility requirements |
| DEL-03.01 | Equipment list provides connected loads |
| DEL-06.03 | Electrical load list provides power requirements |
| DEL-09.01 | HVAC calculations provide heating/cooling loads |

### 5.3 Applicable Standards

| Standard | Description |
|----------|-------------|
| TM Engineering Standards | Trans Mountain project-specific standards (**TBD**) |
| API RP 500/505 | Electrical area classification |
| API RP 686 | Rotating equipment utility requirements |
| NFPA 30 | Flammable liquids code |

---

*End of Datasheet*
