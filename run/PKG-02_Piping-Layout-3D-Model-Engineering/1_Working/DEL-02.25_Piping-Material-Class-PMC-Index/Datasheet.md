# Datasheet: Piping Material Class (PMC) Index

## 1. Identification

| Field | Value |
|-------|-------|
| **Deliverable ID** | DEL-02.25 |
| **Deliverable Name** | Piping Material Class (PMC) Index |
| **Package** | PKG-02: Piping, Layout & 3D Model Engineering |
| **Discipline** | Piping |
| **Deliverable Type** | Table |
| **Responsible Party** | Engineering Contractor |
| **Document Number** | **TBD** |
| **Revision** | **TBD** |

## 2. Attributes

| Attribute | Value |
|-----------|-------|
| **Format** | Excel table with PDF summary |
| **Output** | PMC index/table |
| **Phase Coverage** | FEED through IFC |
| **Maintenance** | Maintained with version control and change history |
| **Index Content** | PMC code, description, service, pressure/temperature ratings, base standard |

### 2.1 Index Data Fields (**ASSUMPTION** - based on industry standard)

| Column | Description |
|--------|-------------|
| PMC Code | Unique material class identifier (e.g., A1A1) |
| Description | Material class description |
| Service | Intended fluid service(s) |
| Material | Base material (e.g., Carbon Steel) |
| Flange Rating | ASME B16.5 class (e.g., 150, 300) |
| Design Pressure | Maximum design pressure |
| Design Temperature | Maximum design temperature |
| MDMT | Minimum Design Metal Temperature |
| Corrosion Allowance | Standard CA for class |
| Base Standard | ASME B31.3, CSA Z662, etc. |
| PMC Sheet Reference | Link to detailed PMC sheet |
| Revision | Current revision of PMC |
| Change History | Summary of changes |

### 2.2 PMC Categories (**ASSUMPTION** - based on typical oil/gas project)

| Category | Typical Services |
|----------|------------------|
| Process | Crude oil, process fluids |
| Utility | Water, air, nitrogen |
| Drain | Oily water, closed drain |
| Vent | Atmospheric vents |
| Specialty | High pressure, special alloys |

## 3. Conditions

| Condition Type | Description |
|----------------|-------------|
| **Input Requirements** | TM existing PMC sheets, Design Basis (DEL-01.01), PMC Verification Report (DEL-02.24) |
| **Design Basis** | SOW flow rates: 275,000 bpd sustainable, 315,000 bpd peak |
| **Operating Environment** | Sumas Tank Farm, crude oil service (Heavy/Light blend) |
| **Code Compliance** | ASME B31.3, CSA Z662 (**ASSUMPTION**) |

## 4. Construction

| Aspect | Details |
|--------|---------|
| **Base PMCs** | TM existing material classes (**TBD**) |
| **New PMCs** | Additional classes as required for project (**TBD**) |
| **Version Control** | Revision number and date for each PMC |
| **Change Tracking** | Change history log for each revision |

## 5. References

| Reference Type | Document |
|----------------|----------|
| **Source** | Puget Sound Optimization Project Decomposition |
| **SOW Reference** | SOW-0258 (§3.2.4.19-§3.2.4.22) |
| **Related Deliverables** | DEL-02.24 (PMC Verification Report), DEL-02.01 (Line List), DEL-02.19 (MTO) |
| **Standards** | ASME B31.3, CSA Z662, ASME B16.5, TM Specifications (**TBD**) |
| **Owner Standards** | Trans Mountain Pipeline PMC standards (**TBD**) |

---
*Pass 1 Draft - Generated 2026-02-01*
