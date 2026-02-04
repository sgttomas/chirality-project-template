# Guidance: DEL-02.30 Piping Technical Requisitions (Engineering)

## Purpose

### Intent
Piping Technical Requisitions provide complete technical packages for procurement of piping materials, valves, and specialty items. This guidance ensures requisitions are complete, technically accurate, and enable effective vendor bidding and material procurement.

### Context
Technical requisitions are the bridge between engineering design and material procurement. The Engineering Contractor provides technical content that is combined with TM commercial terms for vendor inquiry. Quality of technical requisitions directly impacts material quality, lead times, and project cost.

### Stakeholders
| Stakeholder | Interest |
|-------------|----------|
| Lead Piping Engineer | Technical accuracy, approval, bid evaluation support |
| Piping Engineers | Datasheet preparation, specification compliance |
| Materials Engineer | Material specification verification |
| TM Procurement | Commercial terms integration, vendor management |
| TM Engineering | Technical review and approval |
| Quality | QA/QC requirements, ITP basis |
| Vendors | Clear requirements for competitive bidding |

## Principles

### Core Principles
| Principle | Description |
|-----------|-------------|
| **Technical Completeness** | All information needed for vendor quotation included |
| **Clarity** | Requirements unambiguous and clearly stated |
| **Compliance** | Requirements meet applicable codes and regulations |
| **Competitiveness** | Specifications enable competitive bidding (not sole-source unless required) |
| **Traceability** | Requirements traceable to design documents |
| **Timeliness** | Requisitions issued to support procurement schedule |

### Requisition Package Structure
```
Technical Requisition Package
|
+-- Cover Sheet / Index
|   +-- Requisition number, revision, date
|   +-- Item description and quantity summary
|
+-- Technical Specification
|   +-- Referenced TM or project specification
|   +-- Project-specific requirements (if any)
|
+-- Datasheets
|   +-- Process/mechanical datasheets per item
|   +-- Completed with design data
|
+-- Drawings
|   +-- Reference drawings (GA, details)
|   +-- Drawing list with revisions
|
+-- Quality Requirements
|   +-- QC/QA requirements
|   +-- ITP requirements (if applicable)
|
+-- Documentation Requirements
|   +-- Vendor document list
|   +-- Certification requirements
|
+-- Regulatory Requirements
|   +-- CRN/ABSA/BCSA requirements
|
+-- Delivery Requirements
|   +-- Shipping, packaging, preservation
```

## Considerations

### Project-Specific Considerations
| Consideration | Details |
|---------------|---------|
| **TM Standards** | TM specifications take precedence; project specs supplement where needed |
| **Crude Oil Service** | Material compatibility with Heavy/Light crude blend |
| **Regulatory Requirements** | CRN required for pressure equipment per SOW-0213 |
| **Long-Lead Items** | Identify and expedite requisitions for long-lead valves and specialty items |
| **Brownfield Context** | Consider compatibility with existing installed equipment |
| **Booster Pump Application** | VS6 pump suction/discharge valve requirements |

### Technical Considerations
| Topic | Guidance |
|-------|----------|
| **Material Selection** | Per PMC for each service class; verify compatibility |
| **Pressure Ratings** | Specify per design pressure; consider test pressure |
| **Temperature Range** | Specify design temperature range including upset conditions |
| **Sizing Data** | Include Cv/Kv for control valves; flow data for sizing verification |
| **Actuation** | Specify actuator type, fail position, air supply for actuated valves |
| **Accessories** | Clearly define limit switches, solenoids, positioners in scope |
| **Spares** | Define spare parts requirements per TM standards |

### Coordination Requirements
| Requirement | Details |
|-------------|---------|
| Procurement Schedule | Align requisition issue with procurement milestone dates |
| TM Review | Allow time for TM technical review before RFQ |
| Vendor Qualification | Reference AVL or specify vendor qualification requirements |
| Regulatory Lead Time | Allow time for CRN registration process |
| Bid Evaluation | Plan for technical bid evaluation support |

## Trade-offs

### Specification Approach
| Approach | Advantages | Disadvantages | Application |
|----------|------------|---------------|-------------|
| TM Standard Spec | Established, approved, vendor familiarity | May not cover all requirements | Standard items |
| Project-Specific Spec | Tailored to project needs | Development time, TM approval needed | Special requirements |
| Performance Spec | Flexibility, innovation | Less control, more evaluation | Complex equipment |
| Prescriptive Spec | Clear requirements, easy evaluation | May limit competition | Critical items |

### Vendor Restriction
| Approach | Advantages | Disadvantages |
|----------|------------|---------------|
| Open Bidding | Maximum competition, best price | More evaluation effort |
| AVL Restriction | Known quality, faster evaluation | Limited competition |
| Sole Source | Proven performance, commonality | No competition, risk |

**Recommendation**: Use TM-approved vendor lists where available; open bidding with qualification requirements for others.

### Requisition Packaging
| Approach | Advantages | Disadvantages |
|----------|------------|---------------|
| Single Item Packages | Clear scope, focused | More packages to manage |
| Grouped by Type | Economies of scale, fewer packages | Mixed sources possible |
| Grouped by System | Single vendor per system | May not optimize pricing |

**ASSUMPTION**: Packaging approach to be determined based on TM procurement strategy.

## Examples

### Sample Requisition: Gate Valves

```
TECHNICAL REQUISITION

Requisition No.: REQ-PSO-PIP-001
Revision: A
Date: YYYY-MM-DD

ITEM: Gate Valves (Manual)
QUANTITY: Per attached valve list extract

1. SCOPE OF SUPPLY
   - Gate valves per attached datasheet and valve list
   - Handwheels
   - Lifting lugs (where required)
   - Certification documentation

2. TECHNICAL SPECIFICATION
   - Primary: TM-SPEC-VLV-001 (TBD)
   - Supplementary: API 600 / API 602

3. DATASHEETS
   - Attached: Valve datasheets per valve tag

4. QUALITY REQUIREMENTS
   - Per TM-QA-001 (TBD)
   - Hydrostatic test certification required
   - Material test reports required

5. REGULATORY REQUIREMENTS
   - CRN registration required (Alberta)
   - Provide CRN number with quotation or timeline for registration

6. DOCUMENTATION
   - GA drawings
   - Material certificates (3.1)
   - Test certificates
   - O&M manual

7. DELIVERY
   - Ex-works pricing required
   - Delivery to: Sumas Tank Farm (TBD)
   - Packaging per TM-PACK-001 (TBD)

ATTACHMENTS:
A. Valve List Extract
B. Valve Datasheets
C. P&ID References
```

### Typical Requisition Categories for PSO

| Category | Typical Items | Key Requirements |
|----------|---------------|------------------|
| **Gate Valves** | 2" to 20" Class 150-600 | API 600/602, CRN |
| **Ball Valves** | 2" to 12" Class 150-600 | API 6D/608, CRN |
| **Check Valves** | 2" to 20" Class 150-600 | API 6D/594, CRN |
| **Control Valves** | Per control valve list | ISA datasheets, CRN |
| **Pipe (Carbon Steel)** | Various sizes and schedules | CSA Z245.1 / ASTM A106 |
| **Fittings** | Various sizes | ASTM A234, ASME B16.9 |
| **Flanges** | Various sizes and ratings | ASTM A105, ASME B16.5 |
| **Specialty Items** | Strainers, meters, pig equipment | Per item specification |

### Common Issues to Avoid
1. Incomplete datasheets with missing process data
2. Referencing obsolete specification revisions
3. Conflicting requirements between spec and datasheet
4. Missing regulatory requirements (CRN, ABSA)
5. Unclear scope of supply (accessories, spares)
6. Quantities not matching MTO or valve list
7. Missing delivery and packaging requirements
8. Insufficient time for TM review before RFQ
9. Not specifying documentation requirements
10. Vague quality requirements that can't be verified

---
*Generated by 4_DOCUMENTS Agent - 2026-02-01*
