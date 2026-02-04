# Specification: Line Designation Table (LDT)

**Deliverable ID:** DEL-02.18
**Package:** PKG-02 (Piping, Layout & 3D Model Engineering)
**Version:** 0.1 (Initial Draft)
**Status:** INITIALIZED
**Date:** 2026-02-01

---

## 1. Purpose

This specification defines the requirements for developing the Line Designation Table (LDT) for the Puget Sound Optimization Project (PSO) at Sumas Tank Farm. The LDT shall provide a comprehensive listing of all process piping lines with their associated attributes.

---

## 2. Scope

### 2.1 Applicable Facilities
- New booster pump station (5 x VS6-type booster pumps) at SW corner of TK-102
- New 5x6 manifold system
- Associated infrastructure piping and connections
- Tie-ins to existing systems

### 2.2 Applicable Systems
- Main process piping (crude oil service)
- Utility piping within scope
- Drain and vent piping
- Interconnecting piping

---

## 3. Normative References

### 3.1 Codes and Standards (Mandatory)

| Code/Standard | Title | Application |
|---------------|-------|-------------|
| CSA Z662 | Oil and Gas Pipeline Systems | Primary code per SOW Section 4.1.3 |
| ASME B31.4 | Pipeline Transportation Systems for Liquids and Slurries | Supplemental piping code |

### 3.2 Project References

| Reference | Description |
|-----------|-------------|
| TM Standards and Specifications | Per SOW Section 4.1.2 (Attachment A08 - TBD) |
| Design Basis Memorandum | DEL-01.01 |
| Process & Instrumentation Diagrams | DEL-01.03 |
| Piping Material Class Index | DEL-02.25 |
| Line List | DEL-02.01 |

---

## 4. Technical Requirements

### 4.1 General Requirements

4.1.1 The LDT shall include all process piping lines within the PSO scope.

4.1.2 Each line shall have a unique line number per project/TM convention.

4.1.3 All data shall be traceable to source documents (P&IDs, DBM, specifications).

4.1.4 The LDT shall be maintained as a living document throughout the project.

4.1.5 The LDT shall be delivered in editable native format (Excel) per SOW Section 3.2.4.24.

### 4.2 Mandatory Data Fields

Per SOW Section 3.2.4.11, the LDT shall include at minimum:

| Field Category | Required Fields |
|----------------|-----------------|
| Identification | Line Number, P&ID Reference |
| Sizing | Nominal Size |
| Material | Piping Class |
| Routing | From, To |
| Conditions | Design Pressure, Design Temperature, Operating Pressure, Operating Temperature |
| Examination | NDE Requirements |
| Testing | Leak Test, Hydro Test Requirements |
| Other | Service/Fluid, Insulation, Heat Tracing, PWHT, Coating |

### 4.3 Data Field Specifications

#### 4.3.1 Line Number
- Format: Per TM line numbering convention (TBD)
- Unique within project scope
- Consistent with P&ID line tags

#### 4.3.2 Pipe Size
- Unit: NPS (inches) or DN (mm) per TM standard
- Range: As required for process requirements

#### 4.3.3 Piping Class
- Reference: PMC Index (DEL-02.25)
- Format: Per TM piping class designation system

#### 4.3.4 Design Conditions
- Pressure: kPag or psig per TM standard
- Temperature: Degrees C or F per TM standard
- Source: Design Basis Memorandum (DEL-01.01)

#### 4.3.5 NDE Requirements
- Code: RT (Radiography), UT (Ultrasonic), MT (Magnetic Particle), PT (Penetrant), VT (Visual)
- Extent: Percentage as applicable (100%, 10%, etc.)
- Source: PMC specifications, CSA Z662 requirements

#### 4.3.6 Testing Requirements
- Hydro Test: Test pressure in kPag/psig
- Leak Test: Method (pneumatic, service, etc.)
- Source: Code calculations, project specifications

### 4.4 Data Integrity Requirements

4.4.1 All mandatory fields shall be populated - no blank entries for required data.

4.4.2 Dropdown validation lists shall be used for coded fields (pipe class, NDE codes, etc.).

4.4.3 Data validation rules shall prevent invalid entries.

4.4.4 Revision tracking shall be maintained for all changes.

---

## 5. Format and Presentation

### 5.1 File Format

| Requirement | Specification |
|-------------|---------------|
| Primary Format | Microsoft Excel (.xlsx) |
| Secondary Format | PDF export for review/distribution |
| Compatibility | Excel 2016 or later |

### 5.2 Workbook Structure

| Sheet | Content |
|-------|---------|
| Cover | Document identification, revision history |
| LDT | Main line designation data |
| Legend | Abbreviations and codes |
| References | Source document list |

### 5.3 Column Organization

5.3.1 Columns shall be organized in logical groups (ID, Size/Material, Conditions, Testing, etc.).

5.3.2 Column headers shall be frozen for scrolling.

5.3.3 Filters shall be enabled on all data columns.

5.3.4 Column widths shall accommodate maximum field lengths.

### 5.4 Formatting Standards

| Element | Requirement |
|---------|-------------|
| Font | Arial or similar, 10-11 pt |
| Headers | Bold, centered |
| Data | Left-aligned for text, right-aligned for numbers |
| Borders | Gridlines for all data cells |
| Shading | Alternate row shading for readability (optional) |

---

## 6. Interface Requirements

### 6.1 Upstream Interfaces (Inputs)

| Source | Data Provided |
|--------|---------------|
| DEL-01.01 (DBM) | Design conditions |
| DEL-01.03 (P&IDs) | Line tags, routing, fluid |
| DEL-02.01 (Line List) | Preliminary line identification |
| DEL-02.25 (PMC Index) | Piping class designations |

### 6.2 Downstream Interfaces (Outputs)

| Consumer | Data Used |
|----------|-----------|
| DEL-02.13 (Isometrics) | Line number, size, class for titleblock |
| DEL-02.19 (MTO) | Line-based takeoff organization |
| DEL-02.21 (Hydrotest) | Test pressures, line groupings |
| DEL-02.14 (Stress Analysis) | Design conditions, PWHT requirements |

### 6.3 Consistency Requirements

6.3.1 Line numbers shall be consistent across LDT, P&IDs, isometrics, and 3D model.

6.3.2 Design conditions shall match DBM and P&ID data.

6.3.3 Piping classes shall match PMC Index valid classes.

---

## 7. Quality Assurance

### 7.1 Design Verification

- LDT shall be checked per Deliverable Review & Verification Plan (DEL-00.03)
- Cross-verification with P&IDs for line coverage and data consistency
- Validation of piping classes against PMC Index

### 7.2 Completeness Check

- All P&ID lines within scope shall have LDT entries
- All mandatory fields shall be populated
- No orphan lines (lines not on P&IDs)

### 7.3 Data Quality Check

- Numerical values within valid ranges
- Coded values match validation lists
- No duplicate line numbers

---

## 8. Deliverables

| Item | Format | Quantity |
|------|--------|----------|
| Line Designation Table | Excel (.xlsx) | 1 (native) |
| Line Designation Table | PDF | 1 (for distribution) |
| Transmittal | Per TM requirements | Per submission |

---

## 9. TBD Items

| Item | Description | Owner |
|------|-------------|-------|
| TBD-01 | TM LDT template (if existing) | TM Piping Lead |
| TBD-02 | Line numbering convention | TM |
| TBD-03 | Complete column list requirements | TM |
| TBD-04 | Unit conventions (metric vs. imperial) | TM |

---

## 10. Source References

| Reference | Document | Section |
|-----------|----------|---------|
| SOW | Exhibit A - Scope of Work PS.pdf | Section 3.2.4.11 (p19) |
| SOW | Exhibit A - Scope of Work PS.pdf | Section 3.2.4.23-24 (p21) |
| Decomposition | PSO Decomposition REVISED v2 | DEL-02.18, SOW-0250, SOW-0259 |

---

*Specification generated as initial draft. All TBD items require resolution during FEED/Detailed Design phases.*
