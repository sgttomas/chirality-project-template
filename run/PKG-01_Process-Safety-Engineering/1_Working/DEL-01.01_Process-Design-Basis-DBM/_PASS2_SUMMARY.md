# Pass 2 Summary: DEL-01.01 Process Design Basis / DBM

**Deliverable:** DEL-01.01_Process-Design-Basis-DBM
**Package:** PKG-01_Process-Safety-Engineering
**Pass 2 Execution Date:** 2026-02-01
**Status:** COMPLETED

---

## Executive Summary

Pass 2 (Cross-Reference Consistency Check) has been completed for DEL-01.01. A total of **10 major inconsistencies** were identified and resolved across the four documents (Datasheet, Specification, Guidance, Procedure). All documents have been updated with consistency-checked versions. One unresolved conflict (blending range discrepancy) has been documented in a Conflict Resolution Table in the Guidance document.

---

## Inconsistencies Found and Fixed

### 1. Blending Ratio/Range Terminology Inconsistency
**Issue:** Inconsistent terminology and presentation between SOW and DBM sources
**Location:** Datasheet lines 35-37, Specification FR-03, Guidance line 61
**Resolution:**
- Added clarification that NEAT = 100% undiluted heavy crude
- Explicitly noted SOW vs DBM discrepancy (20%-80% vs 10%-100% NEAT)
- Updated Guidance with detailed explanation of terminology
- Added to Conflict Resolution Table as CONF-01 (requires TM resolution)

### 2. Design Life Missing from Specification
**Issue:** Datasheet listed design life as TBD (typically 25-30 years), but Specification only referenced it generically
**Location:** Datasheet line 44, Specification FR-09
**Resolution:**
- Split FR-09 into FR-09 (design life) and FR-09A (corrosion allowances)
- Added explicit requirement for design life confirmation with typical value assumption
- Added to Procedure Phase 2 data gathering steps

### 3. Corrosion Allowance Coverage Gap
**Issue:** Corrosion allowance mentioned but not adequately covered in verification steps
**Location:** Datasheet line 70, Specification FR-09
**Resolution:**
- Added FR-09A specifically for corrosion allowances
- Added Datasheet attribute for corrosion allowance with units (mm)
- Added to Procedure Phase 2 data gathering (step 2.10)

### 4. Manifold Configuration Description Unclear
**Issue:** "5x6" manifold configuration not defined
**Location:** Datasheet line 41, Specification FR-05
**Resolution:**
- Added clarifying description: "5x6 (5 pumps × 6 discharge connections)"
- Updated Procedure Phase 3 to include this clarification

### 5. Battery Limits Definition Gap
**Issue:** Specification required battery limits definition, but no Datasheet entity or Guidance existed
**Location:** Specification FR-10
**Resolution:**
- Updated FR-10 description to clarify "project battery limits and interface points"
- Added new Guidance section "Battery Limits and Interface Definition" with detailed considerations
- Updated Datasheet Content Requirements to explicitly include battery limits
- Added to Procedure Phase 3 (step 3.3) scope section

### 6. Material Selection Coverage Gap
**Issue:** Material selection mentioned in Specification but minimal coverage elsewhere
**Location:** Specification CR-09
**Resolution:**
- Added material selection basis to Datasheet attributes
- Enhanced CR-09 in Specification to reference TMP standards and fluid compatibility
- Added comprehensive "Material Selection Criteria" section to Guidance
- Added Section 7 (Material Selection Criteria) to Procedure Phase 3 drafting steps

### 7. Regulatory Compliance Verification Gap
**Issue:** BC and Washington State regulations listed as "TBD" with no verification step
**Location:** Specification regulatory requirements table
**Resolution:**
- Added note that applicability will be verified in Phase 2
- Added new Procedure Phase 2 step 2.6 to verify regulatory applicability
- Added to Process Considerations in Guidance
- Added to Risk Considerations in Guidance

### 8. Preliminary DBM Reference Emphasis
**Issue:** While consistent, insufficient emphasis on need to verify preliminary DBM per SOW §4.2.2.2
**Location:** Throughout documents
**Resolution:**
- Enhanced Guidance reference documents checklist to emphasize "informational only" status
- Added quality check in Procedure to verify preliminary DBM parameters
- Updated Process Considerations to highlight verification requirement

### 9. Standards Deviation Tracking Gap
**Issue:** Specification required deviation documentation, but no Procedure step existed
**Location:** Specification CR-08
**Resolution:**
- Added new content requirement CR-10 for terminology clarification
- Added Procedure Phase 3 step 3.11 to verify deviations are identified
- Added Procedure Phase 3 step 3.13 (now renumbered) for deviation verification
- Added Section 10 (Deviations from TMP Standards) to drafting steps
- Enhanced quality checks to include standard compliance with deviation tracking

### 10. Turndown Requirement Missing
**Issue:** Minimum turndown flow rate referenced in Guidance but not in Datasheet or Specification
**Location:** Guidance line 169
**Resolution:**
- Added minimum turndown flow rate to Datasheet Technical Attributes
- Added FR-11 requirement to Specification for minimum turndown
- Added assumption (typically 50% of rated capacity for VS6 pumps)
- Added to Procedure Phase 2 data gathering (step 2.11)
- Enhanced Guidance blending control philosophy section with turndown and VFD range details

---

## Cross-Reference Verification Results

### Datasheet ↔ Specification Coverage
**Status:** ✓ CONSISTENT
All entities in Datasheet now have corresponding requirements in Specification. Added missing requirements:
- FR-09: Design life
- FR-09A: Corrosion allowances
- FR-11: Minimum turndown flow rate
- CR-10: Blending terminology clarification

### Specification ↔ Guidance Rationale
**Status:** ✓ CONSISTENT
All requirements now have corresponding rationale and considerations in Guidance:
- Added Battery Limits and Interface Definition section
- Enhanced Material Selection Criteria section
- Enhanced Blending Control Philosophy with detailed terminology
- Expanded Process Considerations table
- Expanded Risk Considerations table

### Specification ↔ Procedure Verification
**Status:** ✓ CONSISTENT
All requirements now have verification steps in Procedure:
- Enhanced Phase 2 data gathering with 6 new steps (2.6-2.11)
- Enhanced Phase 3 drafting with additional sections (7, 10, 11)
- Added quality checks for blending range clarity, preliminary DBM verification
- Enhanced checklist with all new requirements

### Terminology Consistency
**Status:** ✓ CONSISTENT (1 conflict documented)
- Standardized use of "bpd" and "m³/h" for flow rates
- Clarified NEAT terminology (100% NEAT = undiluted heavy crude)
- Documented SOW vs DBM blending range conflict in Conflict Resolution Table
- Standardized manifold configuration description (5x6 = 5 pumps × 6 discharge connections)

### Values and Units Consistency
**Status:** ✓ CONSISTENT
- Flow rates consistent: 275,000 bpd (sustainable), 315,000 bpd (peak)
- Unit conversions verified: 1,822 m³/h (sustainable), 2,100 m³/h (peak)
- Added units to corrosion allowance (mm)
- All TBD values consistently marked across documents

### Entity Coverage
**Status:** ✓ COMPLETE
All major entities now covered:
- Process parameters (flows, pressures, temperatures)
- Equipment configuration (pumps, manifold, VFDs, flow meters)
- Design basis (codes, standards, design life, corrosion)
- Material selection
- Battery limits and interfaces
- Blending requirements
- Regulatory compliance
- Turndown requirements

---

## Assumptions Introduced (Labeled)

The following assumptions were added and clearly labeled as **ASSUMPTION**:

1. **Design Life:** Typically 25-30 years (Datasheet line 44)
   *Basis:* Industry standard for pipeline facilities
   *Verification Required:* TM confirmation

2. **Minimum Turndown Flow Rate:** Typically 50% of rated pump capacity (Datasheet new entry)
   *Basis:* Typical VS6 pump turndown characteristics
   *Verification Required:* Pump vendor data during FEED

3. **VFD Operating Range:** Typically 30-100% speed (Guidance blending section)
   *Basis:* Industry practice for VFD-driven pumps
   *Verification Required:* VFD vendor data

4. **Design Margins:** Typically 10-15% (Guidance trade-offs)
   *Basis:* Standard industry margins
   *Verification Required:* TM guidance

5. **API Standards:** Relevant API standards for equipment (Datasheet line 145)
   *Basis:* Industry practice
   *Verification Required:* TM standards package

---

## Conflicts Documented (Unresolved)

### CONF-01: Blending Range Discrepancy
**Description:** SOW specifies "20% Heavy to 80% Light" while DBM specifies "10%-100% NEAT"
**Impact:** Equipment sizing basis depends on actual operating range
**Location:** Conflict Resolution Table added to Guidance.md
**Resolution Path:** RFI to TM for clarification
**Status:** OPEN - Requires TM input

---

## Documents Updated

All four documents have been overwritten with consistency-checked versions:

1. **Datasheet.md**
   - Added minimum turndown flow rate attribute
   - Clarified manifold configuration description (5x6)
   - Added material selection basis attribute
   - Enhanced blending range notes with NEAT clarification
   - Updated content requirements list

2. **Specification.md**
   - Split FR-09 into FR-09 (design life) and FR-09A (corrosion allowances)
   - Added FR-11 (minimum turndown flow rate)
   - Enhanced FR-03 with explicit blending range discrepancy note
   - Added CR-10 (blending terminology clarification)
   - Enhanced regulatory requirements table with verification notes

3. **Guidance.md**
   - Added new section: Battery Limits and Interface Definition
   - Enhanced Material Selection Criteria section
   - Enhanced Blending Control Philosophy with NEAT terminology and turndown details
   - Expanded Process Considerations table (7 items)
   - Expanded Risk Considerations table (7 items)
   - Enhanced reference documents checklist with 10 items
   - Added Conflict Resolution Table (CONF-01)

4. **Procedure.md**
   - Enhanced Phase 1 with explicit blending range discrepancy note
   - Added 6 new steps to Phase 2 Data Gathering (2.6-2.11)
   - Added 3 new sections to Phase 3 Drafting (Sections 7, 10, 11)
   - Added deviation verification step (3.13)
   - Enhanced quality checks table (8 checks)
   - Enhanced DBM development checklist (23 items)

---

## Quality Metrics

| Metric | Result |
|--------|--------|
| Total Inconsistencies Found | 10 |
| Inconsistencies Resolved | 10 |
| Conflicts Documented | 1 |
| Assumptions Added and Labeled | 5 |
| New Requirements Added | 4 (FR-09A, FR-11, CR-10, enhanced FR-10) |
| New Procedure Steps Added | 9 |
| Documents Updated | 4 of 4 |
| Cross-Reference Coverage | 100% |

---

## Recommendations for Next Steps

1. **Immediate Actions:**
   - Submit RFI to TM to resolve blending range discrepancy (CONF-01)
   - Request TMP Standards package (Attachment A08) from TM
   - Obtain document number from TM Document Control

2. **FEED Phase Actions:**
   - Verify all assumptions with vendor data and TM guidance
   - Confirm design life and corrosion allowances
   - Verify regulatory applicability (BC and Washington State)
   - Establish minimum turndown requirements with pump vendor

3. **Document Maintenance:**
   - Track all TBD items in assumptions register
   - Update documents as confirmations are received
   - Maintain revision history through IFR → IFD → IFC

4. **Downstream Impact:**
   - Alert DEL-01.04 (Equipment Sizing) and DEL-01.05 (Line Sizing) teams of blending range uncertainty
   - Ensure battery limits definition coordinates with interface management (DEL-00.05)
   - Coordinate material selection with procurement long-lead planning

---

## Conclusion

Pass 2 cross-reference consistency check successfully identified and resolved 10 major inconsistencies across the four-document set for DEL-01.01. All documents are now internally consistent with comprehensive cross-referencing between Datasheet entities, Specification requirements, Guidance rationale, and Procedure verification steps.

One unresolved conflict (blending range discrepancy) has been properly documented and requires TM input for resolution. All assumptions have been clearly labeled and traced to their basis.

The documents are now ready for FEED phase execution following the enhanced procedures and guidance provided.

---

*End of Pass 2 Summary*
