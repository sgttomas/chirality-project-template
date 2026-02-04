# Guidance: DEL-00.15 Operation & Maintenance (O&M) Binders

**Document ID:** DEL-00.15-GD
**Revision:** Pass 2 (Cross-Reference Check)
**Date:** 2026-02-01
**Status:** Draft - Pending Review

---

## 1. Purpose

### 1.1 Document Intent

This guidance document provides practical direction for compiling Operation & Maintenance (O&M) Binders for the Puget Sound Optimization Project (PSO). It supplements the formal Specification by offering context, best practices, and recommendations for effective O&M documentation.

### 1.2 Audience

- Document control personnel
- Engineering discipline leads
- Procurement/vendor management team
- Project controls team
- TM operations and maintenance personnel

---

## 2. Principles

### 2.1 Core Principles

| Principle | Description |
|-----------|-------------|
| **Completeness** | Every equipment item must have comprehensive O&M documentation |
| **Accessibility** | Documentation must be organized for easy retrieval |
| **Currency** | Documentation must reflect as-installed equipment configuration |
| **Usability** | Documentation must be practical for field use |
| **Consistency** | Binder structure must be uniform across all equipment |

### 2.2 Guiding Philosophy

O&M Binders are the primary reference for TM operations and maintenance personnel. Effective O&M Binders:
- Enable safe and efficient equipment operation
- Support effective preventive and corrective maintenance
- Provide troubleshooting guidance when issues arise
- Document spare parts for efficient inventory management
- Serve as a training resource for new personnel

---

## 3. Considerations

### 3.1 Binder Organization Considerations

| Consideration | Guidance |
|---------------|----------|
| **By Equipment** | One binder per major equipment item. Best for complex, standalone equipment (pumps, compressors). |
| **By System** | One binder per system covering multiple related items. Best for integrated systems (control systems, fire protection). |
| **Hybrid** | Major equipment gets individual binders; smaller items grouped by system. **ASSUMPTION:** Confirm approach with TM. |

### 3.2 Content Collection Considerations

| Consideration | Guidance |
|---------------|----------|
| **Vendor Manual Tracking** | Establish tracking system for vendor manual receipt early in project. |
| **Procurement Coordination** | Include O&M documentation requirements in procurement specifications. |
| **Missing Manuals** | Follow up with vendors promptly for missing documentation. |
| **Language** | Ensure manuals are in English or required language per TM requirements. |
| **Quality** | Reject poor-quality scans; request legible originals from vendors. |

### 3.3 Drawing Selection Considerations

| Consideration | Guidance |
|---------------|----------|
| **Relevance** | Include only drawings relevant to the specific equipment/system. |
| **Currency** | Use as-built or IFC drawings; do not include superseded versions. |
| **Types** | Include P&IDs, wiring diagrams, arrangement drawings, loop drawings as applicable. |
| **Excerpts** | Consider equipment-specific excerpts from large drawings. |

---

## 4. Trade-offs

### 4.1 Binder Granularity

| Option | Advantages | Disadvantages |
|--------|------------|---------------|
| **Fine (per equipment)** | Easy to locate; portable | Many binders; some redundancy |
| **Coarse (per system)** | Fewer binders; system context | Larger binders; harder to locate specific info |

**Recommendation:** Use equipment-based binders for major equipment (pumps, motors, control valves); system-based binders for distributed components (instruments, small valves). Confirm with TM.

### 4.2 Electronic vs. Hard Copy

| Option | Advantages | Disadvantages |
|--------|------------|---------------|
| **Electronic Only** | Searchable; easy to update; no storage space | Requires device access; screen readability |
| **Hard Copy Only** | Always accessible; field-friendly | Storage space; update burden |
| **Both** | Flexibility; backup | Dual maintenance; consistency risk |

**Recommendation:** Provide electronic as primary (searchable PDF with bookmarks). Confirm hard copy requirements with TM (**TBD**).

### 4.3 Spare Parts Depth

| Option | Advantages | Disadvantages |
|--------|------------|---------------|
| **Vendor Recommended** | Comprehensive | May include excessive items |
| **Project-Defined** | Focused on critical items | May miss important items |
| **TM Standard** | Aligned with TM inventory | May not cover new equipment |

**Recommendation:** Include vendor recommended spare parts list; highlight critical/long-lead items. TM to finalize inventory decisions.

---

## 5. Examples

### 5.1 Sample Binder Structure

| Section | Content |
|---------|---------|
| 1. Cover Page | Binder number, equipment tag, description, system |
| 2. Table of Contents | Index with page/section references |
| 3. Equipment Data | Datasheet, nameplate data, specifications |
| 4. Drawings | P&ID excerpt, arrangement, wiring diagram, loop diagram |
| 5. Vendor Manual - Operation | Installation and operating instructions |
| 6. Vendor Manual - Maintenance | Maintenance procedures, intervals, lubrication |
| 7. Troubleshooting | Troubleshooting guide, alarm/fault list |
| 8. Spare Parts | Recommended spare parts list with part numbers |
| 9. Certificates | Test certificates, calibration records, warranties |
| 10. Reference Documents | Cross-references to related documents |

### 5.2 Sample Equipment Coverage for PSO (**ASSUMPTION**)

| Equipment Type | Binder Approach | Key Content |
|----------------|-----------------|-------------|
| Booster Pumps (5) | Individual binder per pump | Pump manual, motor manual, VFD manual, seal plan |
| Flow Meters | System binder | Flow meter manuals, calibration procedures |
| Control Valves | System binder | Valve manuals, actuator manuals, positioner manuals |
| MCC | System binder | MCC manual, starter info, VFD manuals |
| PLC System | System binder | PLC manual, HMI manual, I/O list, network diagram |
| Fire Detection | System binder | Detector manuals, panel manual, test procedures |

### 5.3 Sample Vendor Manual Tracking Log

| Equipment Tag | Vendor | Manual Required | Received | Quality OK | Notes |
|---------------|--------|-----------------|----------|------------|-------|
| P-101A | Flowserve | O&M Manual | Yes | Yes | - |
| P-101A | ABB | Motor Manual | Yes | Yes | - |
| P-101A | Danfoss | VFD Manual | No | - | Follow up 02/15 |
| FT-101 | Emerson | Flow Meter Manual | Yes | No | Re-request higher quality |

---

## 6. Common Pitfalls

| Pitfall | Prevention Strategy |
|---------|---------------------|
| **Missing Vendor Manuals** | Track vendor documentation from procurement; follow up early |
| **Poor Quality Scans** | Specify quality requirements in purchase orders; reject and re-request |
| **Outdated Drawings** | Use as-built or latest IFC drawings; verify revision levels |
| **Inconsistent Organization** | Use standard template; enforce consistent structure |
| **Missing Spare Parts** | Require spare parts lists in vendor scope; compile during procurement |
| **Late Compilation** | Start binder framework early; populate progressively |
| **Overloaded Binders** | Focus on relevant content; avoid unnecessary duplication |

---

## 7. Integration Points

### 7.1 Relationship to IVARA Data (DEL-00.14)

- IVARA data includes links to O&M documentation
- O&M binder references should match IVARA links
- Coordinate binder numbering for consistency

### 7.2 Relationship to Systems Completion Plan (DEL-00.13)

- O&M binders are part of turnover package content
- Systems Completion Plan defines O&M binder requirements per system
- Binder delivery aligned with system turnover sequence

### 7.3 Relationship to FD Package (DEL-00.16)

- O&M binders are components of Final Documentation Package
- Ensure binders are included in FD index
- Coordinate final binder revision with FD compilation

### 7.4 Relationship to Equipment Datasheets

- Datasheets included in O&M binders
- Ensure datasheet revision matches binder revision
- Cross-reference between binder and master datasheet file

---

## 8. Notes and Assumptions

1. **ASSUMPTION:** O&M binder template to be provided by TM or developed per TM requirements.
2. **ASSUMPTION:** Binder organization (by equipment vs. system) TBD per TM preference.
3. **TBD:** TM O&M binder template and content requirements.
4. **TBD:** Electronic vs. hard copy delivery requirements.
5. **ASSUMPTION:** Vendor manual collection and tracking starts during procurement.

---

*Generated: Pass 2 - Cross-Reference Consistency Check*
*Source: PSO Decomposition REVISED v2, Industry Best Practices*
*Pass 2 Updates: Updated revision; no cross-reference inconsistencies found*
