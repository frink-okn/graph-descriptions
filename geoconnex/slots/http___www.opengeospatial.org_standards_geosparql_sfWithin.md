

# Slot: http___www.opengeospatial.org_standards_geosparql_sfWithin


_No slot (predicate) description specified_





URI: [http://www.opengeospatial.org/standards/geosparql/sfWithin](http://www.opengeospatial.org/standards/geosparql/sfWithin)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpGeosciences.caDefGroundwater#GWWell](../classes/HttpGeosciences.caDefGroundwater#GWWell.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| http___geosciences.ca_def_groundwater#GW_Well → rdfs_Resource | https://geoconnex.us/chyld-pilot/id/well/USGS-445052073350201 | http://www.opengeospatial.org/standards/geosparql/sfWithin | https://geoconnex.us/chyld-pilot/id/hu/041504081603 |
| http___geosciences.ca_def_groundwater#GW_Well → http___geosciences.ca_def_groundwater#GW_AquiferSystem | https://geoconnex.us/chyld-pilot/id/well/USGS-445052073350201 | http://www.opengeospatial.org/standards/geosparql/sfWithin | https://geoconnex.us/chyld-pilot/id/nat_aq/N300NYSDSN |


## Comments

* 14 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type rdfs_Resource.
* 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type http___geosciences.ca_def_groundwater#GW_AquiferSystem.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | http://www.opengeospatial.org/standards/geosparql/sfWithin |
| native | geoconnex/:http___www.opengeospatial.org_standards_geosparql_sfWithin |




## LinkML Source

<details>
```yaml
name: http___www.opengeospatial.org_standards_geosparql_sfWithin
description: No slot (predicate) description specified
comments:
- 14 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and
  object type rdfs_Resource.
- 1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and
  object type http___geosciences.ca_def_groundwater#GW_AquiferSystem.
examples:
- description: http___geosciences.ca_def_groundwater#GW_Well → rdfs_Resource
  object:
    example_object: https://geoconnex.us/chyld-pilot/id/hu/041504081603
    example_predicate: http://www.opengeospatial.org/standards/geosparql/sfWithin
    example_subject: https://geoconnex.us/chyld-pilot/id/well/USGS-445052073350201
- description: http___geosciences.ca_def_groundwater#GW_Well → http___geosciences.ca_def_groundwater#GW_AquiferSystem
  object:
    example_object: https://geoconnex.us/chyld-pilot/id/nat_aq/N300NYSDSN
    example_predicate: http://www.opengeospatial.org/standards/geosparql/sfWithin
    example_subject: https://geoconnex.us/chyld-pilot/id/well/USGS-445052073350201
from_schema: geoconnex
rank: 1000
slot_uri: http://www.opengeospatial.org/standards/geosparql/sfWithin
alias: http___www.opengeospatial.org_standards_geosparql_sfWithin
domain_of:
- http___geosciences.ca_def_groundwater#GW_Well
range: Any
any_of:
- range: http___geosciences.ca_def_groundwater#GW_AquiferSystem
- range: rdfs_Resource

```
</details>