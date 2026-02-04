# Guidance: DEL-00.14 IVARA Data Input Package

**Document ID:** DEL-00.14-GD
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** Draft - Cross-Referenced

---

## 1. Purpose

### 1.1 Document Intent

This guidance document provides practical direction for developing the IVARA Data Input Package for the Puget Sound Optimization Project (PSO). It supplements the formal Specification by offering context, best practices, and recommendations for effective data compilation and submission.

### 1.2 Audience

- Engineering discipline leads
- Document control personnel
- Project controls team
- Data management specialists
- TM maintenance/reliability team

---

## 2. Principles

### 2.1 Core Principles

| Principle | Description |
|-----------|-------------|
| **Accuracy** | Data must accurately reflect as-installed equipment |
| **Completeness** | All required fields must be populated for every equipment item |
| **Consistency** | Data formatting and conventions must be uniform throughout |
| **Traceability** | Data should be traceable to source documents (datasheets, vendor data) |
| **Compatibility** | Data format must match TM IVARA system requirements exactly |

### 2.2 Guiding Philosophy

The IVARA Data Input Package enables TM to efficiently populate their maintenance management system with accurate equipment data. Good IVARA data:
- Eliminates manual data entry by TM operations/maintenance staff
- Ensures consistent equipment identification across systems
- Supports effective maintenance planning from day one
- Links equipment to supporting documentation

---

## 3. Considerations

### 3.1 Template Acquisition

| Consideration | Guidance |
|---------------|----------|
| **Early Request** | Request IVARA template from TM early in project. Template defines required fields and format. |
| **Field Mapping** | Map template fields to discipline deliverable sources (equipment lists, datasheets). |
| **Clarification** | Seek clarification from TM on any ambiguous field definitions. |
| **Sample Data** | Request sample populated template from TM to understand expectations. |

### 3.2 Data Collection Considerations

| Consideration | Guidance |
|---------------|----------|
| **Source Identification** | Identify data sources for each template field (equipment list, datasheets, vendor data, etc.). |
| **Discipline Coordination** | Coordinate with mechanical, electrical, and I&C discipline leads for data inputs. |
| **Timing** | Collect data progressively as discipline deliverables mature; do not wait until the end. |
| **Vendor Data** | Incorporate vendor data (serial numbers, specific parameters) when available. |

### 3.3 Data Quality Considerations

| Consideration | Guidance |
|---------------|----------|
| **Tag Consistency** | Ensure equipment tags exactly match P&IDs, equipment lists, and other design documents. |
| **Serial Numbers** | Include serial numbers when available (especially from vendor data). Serial numbers provide unique equipment tracking for warranty, maintenance history, and spare parts management. |
| **System Assignment** | Assign equipment to parent systems/sub-systems. This enables system-level maintenance planning and supports operations in understanding equipment relationships. |
| **Documentation Links** | Link each equipment item to relevant O&M manuals and drawings. These links enable maintenance staff to quickly access supporting documentation from the IVARA system. |
| **Spelling/Formatting** | Maintain consistent spelling and formatting (capitalization, abbreviations). |
| **Units** | Use units consistent with TM standards; do not mix metric and imperial without clear indication. |
| **Null Values** | Do not leave mandatory fields blank; use TM-approved placeholder if data not available. |

---

## 4. Trade-offs

### 4.1 Data Granularity

| Option | Advantages | Disadvantages |
|--------|------------|---------------|
| **High Detail** (every sub-component) | Comprehensive maintenance tracking | Large data volume; higher effort |
| **Main Equipment Only** | Manageable scope; focused data | May miss maintainable sub-components |

**Recommendation:** Follow TM guidance on equipment hierarchy. **ASSUMPTION:** Include main equipment items; sub-components per TM requirements.

### 4.2 Timing of Submission

| Option | Advantages | Disadvantages |
|--------|------------|---------------|
| **Progressive Submissions** | Earlier IVARA setup; catches issues early | More revision cycles |
| **Single Final Submission** | One comprehensive package | Late discovery of issues; compressed timeline |

**Recommendation:** Plan progressive submissions aligned with discipline milestones (IFD, IFC, As-Built), with final package at turnover.

### 4.3 Maintenance Strategy Population

| Option | Advantages | Disadvantages |
|--------|------------|---------------|
| **Engineering-Defined** (include in package) | Complete data delivery | May not match TM maintenance philosophy |
| **TM-Defined** (leave for TM) | TM maintains control | Requires TM effort post-turnover |

**Recommendation:** Confirm with TM whether maintenance strategy fields should be populated by Engineering Contractor or left for TM. **TBD**

---

## 5. Examples

### 5.1 Sample Data Fields (**ASSUMPTION** - per typical maintenance database)

| Field | Description | Example |
|-------|-------------|---------|
| Equipment Tag | Unique identifier | P-101A |
| Description | Descriptive name | Booster Pump A |
| Equipment Type | Category | Centrifugal Pump |
| Manufacturer | Make | Flowserve |
| Model | Model number | HPX 6x8-13 |
| Serial Number | Unique serial | FSI-2026-001234 |
| Location | Installation area | Sumas Pump Building |
| System | Parent system | SYS-001 Booster Pump System |
| Criticality | Risk ranking | High |
| PM Interval | Preventive maintenance frequency | 6 months |
| O&M Manual | Link to documentation | O&M-P101-001.pdf |

### 5.2 Sample Equipment Categories for PSO (**ASSUMPTION**)

| Category | Examples |
|----------|----------|
| Rotating Equipment | Pumps, motors, VFDs |
| Static Equipment | Vessels, tanks, heat exchangers |
| Valves | Control valves, isolation valves, relief valves |
| Instruments | Flow transmitters, pressure transmitters, analyzers |
| Electrical | Transformers, switchgear, MCCs |
| Safety Devices | Fire detection, ESD devices |

### 5.3 Sample Data Validation Checklist

| Check | Method | Pass Criteria |
|-------|--------|---------------|
| Equipment count | Compare to equipment list | All items included |
| Tag format | Regex or format check | Matches TM convention |
| Mandatory fields | Null check | No blanks in mandatory fields |
| Duplicate check | Unique tag check | No duplicate tags |
| Cross-reference | Compare to P&IDs | Tags match design documents |

---

## 6. Common Pitfalls

| Pitfall | Prevention Strategy |
|---------|---------------------|
| **Missing Equipment** | Cross-check against master equipment list from each discipline |
| **Tag Mismatches** | Use single source of truth for tags; verify against P&IDs |
| **Format Errors** | Validate against TM template before submission |
| **Late Template Acquisition** | Request IVARA template early in project lifecycle |
| **Incomplete Vendor Data** | Plan vendor data collection; track outstanding items |
| **Inconsistent Naming** | Establish naming conventions; use dropdown lists where possible |

---

## 7. Integration Points

### 7.1 Relationship to Equipment Lists (DEL-03.01, DEL-06.03, DEL-07.02)

- Equipment lists are primary sources for IVARA data
- Tags and descriptions should match exactly
- IVARA data adds maintenance-specific attributes

### 7.2 Relationship to Equipment Datasheets

- Datasheets provide detailed specifications
- Extract relevant fields for IVARA (manufacturer, model, parameters)
- Ensure consistency between datasheet and IVARA data

### 7.3 Relationship to O&M Binders (DEL-00.15)

- IVARA data includes links to O&M documentation
- Use consistent document numbering
- Coordinate O&M binder completion with IVARA data finalization

### 7.4 Relationship to Tag Numbering (DEL-00.02)

- Tag Numbering Instruction Plan defines tag conventions
- IVARA data must comply with established conventions
- Coordinate tag assignments before populating IVARA data

---

## 8. Notes and Assumptions

1. **ASSUMPTION:** IVARA template to be provided by TM.
2. **ASSUMPTION:** Data fields listed are typical; actual fields TBD per TM requirements.
3. **TBD:** TM IVARA template and specific data schema.
4. **TBD:** Whether maintenance strategy fields are populated by contractor or TM.
5. **ASSUMPTION:** Progressive data submission aligned with project milestones.

---

*Generated: Pass 1 - Initial Draft*
*Updated: Pass 2 - Cross-Reference Consistency Check (2026-02-01)*
*Source: PSO Decomposition REVISED v2, Industry Best Practices*
