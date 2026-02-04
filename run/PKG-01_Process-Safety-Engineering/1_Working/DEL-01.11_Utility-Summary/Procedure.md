# Procedure: DEL-01.11 Utility Summary

**Document ID:** DEL-01.11-PR
**Revision:** Pass 2 (Cross-Reference Consistency Check)
**Date:** 2026-02-01
**Status:** DRAFT - Pass 2

---

## 1. Purpose

### 1.1 Procedure Objective

This procedure defines the step-by-step process for developing, reviewing, and issuing the Utility Summary table for the Puget Sound Optimization project in accordance with DEL-01.11-SP (Specification) and DEL-01.11-GD (Guidance).

### 1.2 Scope

This procedure covers:
- Data collection from all disciplines
- Utility Summary table development
- Internal review and verification
- TM (client) review coordination
- Revision and update management

---

## 2. Prerequisites

### 2.1 Required Inputs

| Input | Source | Status |
|-------|--------|--------|
| Equipment List | DEL-03.01 | Required before completion |
| P&IDs (preliminary) | DEL-01.03 | Required for instrument air consumers |
| Electrical Load List | DEL-06.03 | Required for electrical utilities |
| HVAC Load Calculations | DEL-09.01 | Required for building loads |
| Process Datasheets | DEL-01.09 | Required for process equipment |
| Design Basis Memorandum | DEL-01.01 | Required for design basis parameters |
| Vendor Data | Procurement | As available |

### 2.2 Required Resources

| Resource | Role |
|----------|------|
| Lead Process Engineer | Utility Summary Owner |
| Electrical Engineer | Electrical utility inputs |
| Mechanical Engineer | Rotating equipment inputs |
| I&C Engineer | Instrument air inputs |
| HVAC Engineer | Building utility inputs |
| Document Controller | Document management |

### 2.3 Required Authorizations

| Authorization | Authority | Required For |
|---------------|-----------|--------------|
| Project Kickoff | Project Manager | Procedure initiation |
| IFR Release | Engineering Manager | IFR submission |
| IFC Release | Engineering Manager + TM | IFC issue |

---

## 3. Steps

### 3.1 Phase 1: Preparation

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 1.1 | Review SOW requirements for Utility Summary (SOW-0232) | Lead Process Engineer | Requirements understanding |
| 1.2 | Establish Utility Summary table template per DEL-01.11-DS | Lead Process Engineer | Template file (Excel) |
| 1.3 | Identify all utility types applicable to PSO scope | Lead Process Engineer | Utility types list |
| 1.4 | Request equipment list from mechanical discipline (DEL-03.01) | Lead Process Engineer | Equipment list (draft) |
| 1.5 | Request P&IDs from process discipline (DEL-01.03) | Lead Process Engineer | P&ID set (draft) |

### 3.2 Phase 2: Data Collection

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 2.1 | Compile electrical load data from electrical load list (DEL-06.03) | Electrical Engineer | Electrical load summary |
| 2.2 | Identify instrument air consumers from P&IDs (DEL-01.03) | I&C Engineer | Instrument air consumer list |
| 2.3 | Calculate instrument air consumption rates per ISA-5.1 | I&C Engineer | Instrument air totals |
| 2.4 | Obtain cooling water requirements from process datasheets (DEL-01.09) | Mechanical Engineer | Cooling water demands |
| 2.5 | Obtain fire water demands from fire protection design | Lead Process Engineer | Fire water requirements |
| 2.6 | Obtain building utility demands from HVAC calculations (DEL-09.01) | HVAC Engineer | Building utility loads |
| 2.7 | Compile vendor data for specific equipment | Lead Process Engineer | Vendor data summary |

### 3.3 Phase 3: Table Development

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 3.1 | Populate Utility Summary table with collected data | Lead Process Engineer | Draft Utility Summary |
| 3.2 | Verify equipment tags match equipment list (DEL-03.01) | Lead Process Engineer | Tag verification log |
| 3.3 | Calculate subtotals for each utility type | Lead Process Engineer | Subtotal rows |
| 3.4 | Calculate grand totals for all utilities | Lead Process Engineer | Grand total rows |
| 3.5 | Document sources and references for each entry | Lead Process Engineer | Reference column populated |
| 3.6 | Flag TBD items and assumptions per DEL-01.11-GD | Lead Process Engineer | TBD/Assumption log |

### 3.4 Phase 4: Internal Review

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 4.1 | Distribute draft to discipline leads for review | Lead Process Engineer | Review request |
| 4.2 | Electrical discipline verifies electrical data against DEL-06.03 | Electrical Engineer | Review comments |
| 4.3 | I&C discipline verifies instrument air data | I&C Engineer | Review comments |
| 4.4 | Mechanical discipline verifies equipment data against DEL-03.01 | Mechanical Engineer | Review comments |
| 4.5 | Address review comments | Lead Process Engineer | Updated Utility Summary |
| 4.6 | Verify totals are mathematically correct | Lead Process Engineer | Verification record |
| 4.7 | Obtain internal approval | Engineering Manager | Approval signature |

### 3.5 Phase 5: Issue

| Step | Action | Responsible | Output |
|------|--------|-------------|--------|
| 5.1 | Issue Utility Summary as IFR to TM per document control procedure | Document Controller | Transmittal |
| 5.2 | Receive and log TM comments | Document Controller | Comment register |
| 5.3 | Address TM comments | Lead Process Engineer | Comment responses |
| 5.4 | Update Utility Summary as vendor data becomes available | Lead Process Engineer | Revised Utility Summary |
| 5.5 | Issue as IFC per SOW-0232 requirements | Document Controller | IFC transmittal |

---

## 4. Verification

### 4.1 Quality Checks

| Check | Criteria | Method | Timing |
|-------|----------|--------|--------|
| Completeness | All utility types per DEL-01.11-DS Section 3.1 included | Checklist review | Before IFR |
| Accuracy | Values match source documents (DEL-03.01, DEL-06.03, DEL-09.01) | Cross-reference check | Before IFR |
| Traceability | All entries have source references | Document review | Before IFR |
| Mathematical Accuracy | Totals are correct | Calculation check | Before IFR |

### 4.2 Hold Points

| Hold Point | Criteria to Proceed | Authority |
|------------|---------------------|-----------|
| HP-01 | Equipment list (DEL-03.01) available | Mechanical Lead |
| HP-02 | Internal review complete per Section 3.4 | Engineering Manager |
| HP-03 | TM comments resolved | Project Manager |

### 4.3 Verification Records

| Record | Content | Retention |
|--------|---------|-----------|
| Data Collection Log | Sources for each utility value | Project duration + 7 years |
| Review Comments | All comments and responses | Project duration + 7 years |
| Calculation Check | Total verification | Project duration + 7 years |

---

## 5. Records

### 5.1 Required Records

| Record | Format | Location | Responsibility |
|--------|--------|----------|----------------|
| Utility Summary (all revisions) | Excel + PDF | Document Control | Document Controller |
| Source Data References | Excel | Project Files | Lead Process Engineer |
| Review Comments | Excel/PDF | Document Control | Lead Process Engineer |
| Transmittals | PDF | Document Control | Document Controller |

### 5.2 Record Retention

| Category | Retention Period | Disposition |
|----------|------------------|-------------|
| Final Issue Documents | Permanent | Archive |
| Draft Documents | Project completion + 5 years | Destroy |
| Review Records | Project completion + 7 years | Archive |

### 5.3 Document Control Requirements

- All Utility Summary revisions shall be issued through formal document control
- Superseded revisions shall be clearly marked
- Native Excel files shall be submitted per SOW-0232 requirements
- Document revision history shall be maintained per DEL-01.11-SP Section 5.3

---

## 6. Appendices

### 6.1 Utility Summary Development Checklist

- [ ] Equipment list obtained (DEL-03.01)
- [ ] P&IDs reviewed for utility consumers (DEL-01.03)
- [ ] Electrical load data compiled (DEL-06.03)
- [ ] Instrument air consumers identified
- [ ] Cooling water requirements determined (DEL-01.09)
- [ ] Fire water demands included
- [ ] Building loads included (DEL-09.01)
- [ ] All entries have source references
- [ ] Equipment tags verified against DEL-03.01
- [ ] Subtotals calculated
- [ ] Grand totals calculated
- [ ] Internal review complete
- [ ] IFR issued
- [ ] TM comments addressed
- [ ] IFC issued

### 6.2 Related Procedures

| Procedure | Reference |
|-----------|-----------|
| Document Control Procedure | PKG-00 procedures |
| Equipment List Procedure | DEL-03.01-PR |
| Electrical Load List Procedure | DEL-06.03-PR |
| Design Basis Procedure | DEL-01.01-PR |

---

*End of Procedure*
