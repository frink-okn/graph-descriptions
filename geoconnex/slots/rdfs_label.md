

# Slot: rdfs_label


_No slot (predicate) description specified_





URI: [rdfs:label](http://www.w3.org/2000/01/rdf-schema#label)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) | No class (type) description specified |  no  |
| [HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md) | No class (type) description specified |  no  |
| [HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) | No class (type) description specified |  no  |
| [RdfsResource](../classes/RdfsResource.md) | No class (type) description specified |  no  |
| [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rdfs_Resource → string | http://geosciences.ca/def/groundwater#GW_AquiferSystem | rdfs:label | Aquifer System |
| None → string | http://water.usgs.gov/ogw/aquiferbasics/nycarbon.html | rdfs:label | Aquifer Summary Page |
| http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → string | https://geoconnex.ca/id/hydrogeounits/Richelieu1 | rdfs:label | Hydrogeologic unit : Southern St Lawrence Platform |
| http___rdfs.org_ns_void#Dataset → string | https://geoconnex.us/chyld-pilot/id/LOD_Node/US_Hydro_LOD_Node | rdfs:label | Hydrography Linked Data Node - United States of America |
| http___geosciences.ca_def_groundwater#GW_AquiferSystem → string | https://geoconnex.us/chyld-pilot/id/nat_aq/N300NYSDSN | rdfs:label | New York sandstone aquifers |
| http___geosciences.ca_def_groundwater#GW_Well → string | https://geoconnex.us/chyld-pilot/id/well/USGS-434217073010601 | rdfs:label | VT-PFW    8 |


## Comments

* 1514 occurrences with subject type rdfs_Resource and object type string.
* 3204 occurrences with untyped subjects and object type string.
* 2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type string.
* 5 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type string.
* 2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type string.
* 5 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rdfs:label |
| native | geoconnex/:rdfs_label |




## LinkML Source

<details>
```yaml
name: rdfs_label
description: No slot (predicate) description specified
comments:
- 1514 occurrences with subject type rdfs_Resource and object type string.
- 3204 occurrences with untyped subjects and object type string.
- 2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
  and object type string.
- 5 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type
  string.
- 2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem
  and object type string.
- 5 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and
  object type string.
examples:
- description: rdfs_Resource → string
  object:
    example_object: Aquifer System
    example_predicate: rdfs:label
    example_subject: http://geosciences.ca/def/groundwater#GW_AquiferSystem
- description: None → string
  object:
    example_object: Aquifer Summary Page
    example_predicate: rdfs:label
    example_subject: http://water.usgs.gov/ogw/aquiferbasics/nycarbon.html
- description: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → string
  object:
    example_object: 'Hydrogeologic unit : Southern St Lawrence Platform'
    example_predicate: rdfs:label
    example_subject: https://geoconnex.ca/id/hydrogeounits/Richelieu1
- description: http___rdfs.org_ns_void#Dataset → string
  object:
    example_object: Hydrography Linked Data Node - United States of America
    example_predicate: rdfs:label
    example_subject: https://geoconnex.us/chyld-pilot/id/LOD_Node/US_Hydro_LOD_Node
- description: http___geosciences.ca_def_groundwater#GW_AquiferSystem → string
  object:
    example_object: New York sandstone aquifers
    example_predicate: rdfs:label
    example_subject: https://geoconnex.us/chyld-pilot/id/nat_aq/N300NYSDSN
- description: http___geosciences.ca_def_groundwater#GW_Well → string
  object:
    example_object: VT-PFW    8
    example_predicate: rdfs:label
    example_subject: https://geoconnex.us/chyld-pilot/id/well/USGS-434217073010601
from_schema: geoconnex
rank: 1000
slot_uri: rdfs:label
alias: rdfs_label
domain_of:
- http___geosciences.ca_def_groundwater#GW_AquiferSystem
- http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
- http___geosciences.ca_def_groundwater#GW_Well
- http___rdfs.org_ns_void#Dataset
- rdfs_Resource
range: string

```
</details>