# Guidance: DEL-02.26 Bolt List

## Purpose

### Intent
The Bolt List serves as the definitive inventory of bolted flange connections for the piping scope, enabling accurate material procurement, installation planning, and as-built documentation. This guidance ensures consistent development and application of the bolt list across the PSO project at Sumas Tank Farm.

### Context
Within the piping engineering workflow, the Bolt List is generated after piping isometrics are substantially complete and piping material classes (PMCs) are finalized. It directly supports the Material Take-Off (MTO) for bolting materials and provides construction with connection-specific bolting requirements.

### Stakeholders
| Stakeholder | Interest |
|-------------|----------|
| Piping Engineering | Source data generation, technical accuracy, PMC compliance |
| Material Management | Procurement quantities, material specifications, lead times |
| Construction | Installation requirements, bolt-up verification, torque values |
| Quality Assurance | Material traceability, compliance verification, inspection |
| Client (TM) | Final approval, as-built records, operational spares |

## Principles

### Core Principles
1. **Completeness**: Every bolted flange connection within piping scope shall be captured
2. **Accuracy**: Bolt specifications shall precisely match PMC requirements and code provisions
3. **Traceability**: Each entry shall reference source documents (P&ID, isometric, line number)
4. **Usability**: Format shall support sorting, filtering, and extraction for procurement and construction
5. **Currency**: Document shall be maintained current with design changes through IFC
6. **Standardization**: Minimize bolt variety where practical to simplify procurement and inventory

### Data Hierarchy
```
Piping Isometrics (Primary Source)
    |
    v
Bolt List (Master Register)
    |
    +---> Piping MTO (Quantity Roll-up)
    |
    +---> Procurement Packages (Material Requisitions)
    |
    +---> CWP/FIWP (Installation Reference)
```

## Considerations

### Technical Considerations
| Consideration | Guidance |
|---------------|----------|
| Material Selection | Use PMC-specified bolt materials; verify temperature suitability per service conditions |
| Flange Rating | Confirm pressure-temperature rating per ASME B16.5 / B16.47 tables matches P&ID class |
| Bolt Length | Account for flange thickness, gasket type, and nut engagement; round up to next standard length |
| Low Temperature | Use ASTM A320 grades for design temperatures below -29C |
| Sour Service | Use A193 B7M / A194 2HM for H2S service if specified by PMC (**TBD** - confirm service) |
| Corrosion Protection | **TBD** - Coordinate with Materials Engineer for coating/treatment requirements |

### Operational Considerations
| Consideration | Guidance |
|---------------|----------|
| Procurement Lead Time | Identify long-lead or specialty bolting materials early for procurement planning |
| Installation Sequence | Consider construction sequence for staged bolt delivery scheduling |
| Torque Requirements | Reference PMC or project specification for required torque values |
| Spare Strategy | **TBD** - Coordinate spare bolting requirements with Operations and Construction |
| Field Verification | Plan for bolt-up inspection per quality plan requirements |

### Coordination Requirements
| Consideration | Guidance |
|---------------|----------|
| Isometric Alignment | Bolt list entries must align with isometric spool designations and joint marks |
| Valve Datasheets | Verify valve flange ratings match line class requirements from valve datasheets |
| Equipment Nozzles | Confirm equipment nozzle flange ratings from vendor data and equipment datasheets |
| MTO Integration | Ensure bolt list format supports automated roll-up into Piping MTO |
| PMC Updates | Monitor PMC revisions and update bolt list for material changes |

## Trade-offs

### Material Grade Selection
| Option | Advantage | Disadvantage | Application |
|--------|-----------|--------------|-------------|
| A193 B7 / A194 2H | Lower cost, readily available, industry standard | Limited low-temperature application (-29C minimum) | Standard hydrocarbon service |
| A320 L7 / A194 7 | Suitable for cold service to -100C | Higher cost, longer lead time | Low-temperature service |
| A193 B7M / A194 2HM | Sour service rated (HRC 22 max) | Higher cost, may require certification | H2S environment |
| A193 B8M / A194 8M | Corrosion resistance (316SS) | Significantly higher cost, galling risk | Corrosive service |

### Documentation Approach
| Option | Advantage | Disadvantage | Recommendation |
|--------|-----------|--------------|----------------|
| Model-extracted list | Efficiency, consistency, automation | Requires validated 3D model with complete data | **ASSUMPTION** - Preferred where model is complete |
| Manual compilation | Works without complete model | Labor intensive, higher error risk | Use during early design phases |
| Hybrid approach | Balance of efficiency and verification | Requires clear process definition | Use for final verification |

### Level of Detail
| Option | Advantage | Disadvantage |
|--------|-----------|--------------|
| Connection-level detail | Precise installation information, supports QC | Large document, more maintenance effort |
| Summary by type/size | Easier for procurement, smaller document | Less installation specificity |
| **Selected: Connection-level** | Supports construction verification and as-built | Requires robust data management |

## Examples

### Typical Bolt List Entry
| Field | Example Value |
|-------|---------------|
| Bolt Tag | BL-PSO-001 |
| Line Number | 8"-CW-001-A1A |
| Joint Reference | J-001 |
| P&ID Reference | PID-PSO-001 |
| Isometric Reference | ISO-PSO-8001 |
| Connection Type | Pipe-to-Valve |
| Flange Rating | Class 300 |
| Flange Type | Weld Neck RF |
| NPS | 8" |
| Bolt Type | Stud Bolt |
| Bolt Size | 7/8" x 5-1/2" |
| Bolt Material | A193 B7 |
| Nut Material | A194 2H |
| Quantity | 12 |
| Service | Crude Oil |
| Remarks | - |

### Common Material Grades by Service
| Service Type | Design Temp | Bolt Grade | Nut Grade |
|--------------|-------------|------------|-----------|
| Standard Hydrocarbon | -29C to 400C | A193 B7 | A194 2H |
| Low Temperature | -100C to -29C | A320 L7 | A194 7 |
| Sour Service | Per NACE MR0175 | A193 B7M | A194 2HM |
| High Temperature | >400C | A193 B16 | A194 4 |

### ASME B16.5 Standard Bolt Quantities (Raised Face)
| NPS | Class 150 | Class 300 | Class 600 | Class 900 |
|-----|-----------|-----------|-----------|-----------|
| 2" | 4 | 8 | 8 | 8 |
| 4" | 8 | 8 | 8 | 8 |
| 6" | 8 | 12 | 12 | 12 |
| 8" | 8 | 12 | 12 | 12 |
| 10" | 12 | 16 | 16 | 16 |
| 12" | 12 | 16 | 20 | 20 |
| 14" | 12 | 20 | 20 | 20 |
| 16" | 16 | 20 | 20 | 20 |

### Common Issues to Avoid
1. Using incorrect bolt length for flange class or gasket type
2. Mismatched bolt/nut material grades (e.g., mixing temperature ratings)
3. Missing washer requirements for raised face flanges where specified
4. Omitting tie-in connection bolts at existing system interfaces
5. Not accounting for gasket thickness in bolt length calculation
6. Inadequate spare allowance for construction
7. Using non-temperature-rated bolts for low-temperature service
8. Missing spectacle blind or spacer bolting requirements

---
*Generated by 4_DOCUMENTS Agent - 2026-02-01*
