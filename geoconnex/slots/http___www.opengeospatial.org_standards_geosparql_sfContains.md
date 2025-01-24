

# Slot: http___www.opengeospatial.org_standards_geosparql_sfContains


_No slot (predicate) description specified_





URI: [http://www.opengeospatial.org/standards/geosparql/sfContains](http://www.opengeospatial.org/standards/geosparql/sfContains)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RdfsResource](../classes/RdfsResource.md) | No class (type) description specified |  no  |
| [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) | No class (type) description specified |  no  |







## Properties

* Range: [HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rdfs_Resource → http___geosciences.ca_def_groundwater#GW_Well | https://geoconnex.us/chyld-pilot/id/nat_aq/N100GLCIAL | http://www.opengeospatial.org/standards/geosparql/sfContains | https://geoconnex.us/chyld-pilot/id/well/USGS-443646073124901 |
| http___geosciences.ca_def_groundwater#GW_AquiferSystem → http___geosciences.ca_def_groundwater#GW_Well | https://geoconnex.us/chyld-pilot/id/nat_aq/N300NYSDSN | http://www.opengeospatial.org/standards/geosparql/sfContains | https://geoconnex.us/chyld-pilot/id/well/USGS-445052073350201 |


## Comments

* 14 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_Well.
* 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type http___geosciences.ca_def_groundwater#GW_Well.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | http://www.opengeospatial.org/standards/geosparql/sfContains |
| native | geoconnex/:http___www.opengeospatial.org_standards_geosparql_sfContains |




## LinkML Source

<details>
```yaml
name: http___www.opengeospatial.org_standards_geosparql_sfContains
description: No slot (predicate) description specified
comments:
- 14 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_Well.
- 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem
  and object type http___geosciences.ca_def_groundwater#GW_Well.
examples:
- description: rdfs_Resource → http___geosciences.ca_def_groundwater#GW_Well
  object:
    example_object: https://geoconnex.us/chyld-pilot/id/well/USGS-443646073124901
    example_predicate: http://www.opengeospatial.org/standards/geosparql/sfContains
    example_subject: https://geoconnex.us/chyld-pilot/id/nat_aq/N100GLCIAL
- description: http___geosciences.ca_def_groundwater#GW_AquiferSystem → http___geosciences.ca_def_groundwater#GW_Well
  object:
    example_object: https://geoconnex.us/chyld-pilot/id/well/USGS-445052073350201
    example_predicate: http://www.opengeospatial.org/standards/geosparql/sfContains
    example_subject: https://geoconnex.us/chyld-pilot/id/nat_aq/N300NYSDSN
from_schema: geoconnex
rank: 1000
slot_uri: http://www.opengeospatial.org/standards/geosparql/sfContains
alias: http___www.opengeospatial.org_standards_geosparql_sfContains
domain_of:
- http___geosciences.ca_def_groundwater#GW_AquiferSystem
- rdfs_Resource
range: http___geosciences.ca_def_groundwater#GW_Well

```
</details>