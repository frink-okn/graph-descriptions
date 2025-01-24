

# Slot: http___www.opengeospatial.org_standards_geosparql_sfIntersects


_No slot (predicate) description specified_





URI: [http://www.opengeospatial.org/standards/geosparql/sfIntersects](http://www.opengeospatial.org/standards/geosparql/sfIntersects)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) | No class (type) description specified |  no  |
| [RdfsResource](../classes/RdfsResource.md) | No class (type) description specified |  no  |
| [HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[HttpGeosciences.caDefGroundwater#GWAquiferSystem](../classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](../classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → rdfs_Resource | https://geoconnex.ca/id/hydrogeounits/Richelieu1 | http://www.opengeospatial.org/standards/geosparql/sfIntersects | https://geoconnex.us/chyld-pilot/id/hu/041504081507-drainage_basin |
| http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → uri | https://geoconnex.ca/id/hydrogeounits/Richelieu1 | http://www.opengeospatial.org/standards/geosparql/sfIntersects | https://cida-test.er.usgs.gov/chyld-pilot/id/hu/041504081005 |
| rdfs_Resource → http___geosciences.ca_def_groundwater#GW_AquiferSystem | https://geoconnex.us/chyld-pilot/id/hu/041504081604 | http://www.opengeospatial.org/standards/geosparql/sfIntersects | https://geoconnex.us/chyld-pilot/id/nat_aq/N400NYNECB |
| rdfs_Resource → http___geosciences.ca_def_groundwater#GW_HydrogeoUnit | https://geoconnex.us/chyld-pilot/id/hu/041504081507-drainage_basin | http://www.opengeospatial.org/standards/geosparql/sfIntersects | https://geoconnex.ca/id/hydrogeounits/Richelieu1 |
| http___geosciences.ca_def_groundwater#GW_AquiferSystem → rdfs_Resource | https://geoconnex.us/chyld-pilot/id/nat_aq/N400NYNECB | http://www.opengeospatial.org/standards/geosparql/sfIntersects | https://geoconnex.us/chyld-pilot/id/hu/041504081604 |


## Comments

* 14 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type rdfs_Resource.
* 13 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type uri.
* 108 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_AquiferSystem.
* 14 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit.
* 108 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type rdfs_Resource.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | http://www.opengeospatial.org/standards/geosparql/sfIntersects |
| native | geoconnex/:http___www.opengeospatial.org_standards_geosparql_sfIntersects |




## LinkML Source

<details>
```yaml
name: http___www.opengeospatial.org_standards_geosparql_sfIntersects
description: No slot (predicate) description specified
comments:
- 14 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
  and object type rdfs_Resource.
- 13 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
  and object type uri.
- 108 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_AquiferSystem.
- 14 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit.
- 108 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem
  and object type rdfs_Resource.
examples:
- description: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → rdfs_Resource
  object:
    example_object: https://geoconnex.us/chyld-pilot/id/hu/041504081507-drainage_basin
    example_predicate: http://www.opengeospatial.org/standards/geosparql/sfIntersects
    example_subject: https://geoconnex.ca/id/hydrogeounits/Richelieu1
- description: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit → uri
  object:
    example_object: https://cida-test.er.usgs.gov/chyld-pilot/id/hu/041504081005
    example_predicate: http://www.opengeospatial.org/standards/geosparql/sfIntersects
    example_subject: https://geoconnex.ca/id/hydrogeounits/Richelieu1
- description: rdfs_Resource → http___geosciences.ca_def_groundwater#GW_AquiferSystem
  object:
    example_object: https://geoconnex.us/chyld-pilot/id/nat_aq/N400NYNECB
    example_predicate: http://www.opengeospatial.org/standards/geosparql/sfIntersects
    example_subject: https://geoconnex.us/chyld-pilot/id/hu/041504081604
- description: rdfs_Resource → http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
  object:
    example_object: https://geoconnex.ca/id/hydrogeounits/Richelieu1
    example_predicate: http://www.opengeospatial.org/standards/geosparql/sfIntersects
    example_subject: https://geoconnex.us/chyld-pilot/id/hu/041504081507-drainage_basin
- description: http___geosciences.ca_def_groundwater#GW_AquiferSystem → rdfs_Resource
  object:
    example_object: https://geoconnex.us/chyld-pilot/id/hu/041504081604
    example_predicate: http://www.opengeospatial.org/standards/geosparql/sfIntersects
    example_subject: https://geoconnex.us/chyld-pilot/id/nat_aq/N400NYNECB
from_schema: geoconnex
rank: 1000
slot_uri: http://www.opengeospatial.org/standards/geosparql/sfIntersects
alias: http___www.opengeospatial.org_standards_geosparql_sfIntersects
domain_of:
- http___geosciences.ca_def_groundwater#GW_AquiferSystem
- http___geosciences.ca_def_groundwater#GW_HydrogeoUnit
- rdfs_Resource
range: Any
any_of:
- range: uri
- range: http___geosciences.ca_def_groundwater#GW_AquiferSystem
- range: rdfs_Resource
- range: http___geosciences.ca_def_groundwater#GW_HydrogeoUnit

```
</details>