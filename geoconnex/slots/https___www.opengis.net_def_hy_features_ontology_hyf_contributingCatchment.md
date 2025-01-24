

# Slot: https___www.opengis.net_def_hy_features_ontology_hyf_contributingCatchment


_No slot (predicate) description specified_





URI: [https://www.opengis.net/def/hy_features/ontology/hyf/contributingCatchment](https://www.opengis.net/def/hy_features/ontology/hyf/contributingCatchment)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RdfsResource](../classes/RdfsResource.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rdfs_Resource → uri | https://geoconnex.ca/id/catchment/02OJ*CA | https://www.opengis.net/def/hy_features/ontology/hyf/contributingCatchment | https://cida-test.er.usgs.gov/chyld-pilot/id/hu_nexus/02OJ*CA-inflow |
| rdfs_Resource → rdfs_Resource | https://geoconnex.us/chyld-pilot/id/hu_nexus/041504081604-inflow | https://www.opengis.net/def/hy_features/ontology/hyf/contributingCatchment | https://geoconnex.us/chyld-pilot/id/hu/041504081603-drainage_basin |


## Comments

* 1 occurrences with subject type rdfs_Resource and object type uri.
* 374 occurrences with subject type rdfs_Resource and object type rdfs_Resource.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | https://www.opengis.net/def/hy_features/ontology/hyf/contributingCatchment |
| native | geoconnex/:https___www.opengis.net_def_hy_features_ontology_hyf_contributingCatchment |




## LinkML Source

<details>
```yaml
name: https___www.opengis.net_def_hy_features_ontology_hyf_contributingCatchment
description: No slot (predicate) description specified
comments:
- 1 occurrences with subject type rdfs_Resource and object type uri.
- 374 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
examples:
- description: rdfs_Resource → uri
  object:
    example_object: https://cida-test.er.usgs.gov/chyld-pilot/id/hu_nexus/02OJ*CA-inflow
    example_predicate: https://www.opengis.net/def/hy_features/ontology/hyf/contributingCatchment
    example_subject: https://geoconnex.ca/id/catchment/02OJ*CA
- description: rdfs_Resource → rdfs_Resource
  object:
    example_object: https://geoconnex.us/chyld-pilot/id/hu/041504081603-drainage_basin
    example_predicate: https://www.opengis.net/def/hy_features/ontology/hyf/contributingCatchment
    example_subject: https://geoconnex.us/chyld-pilot/id/hu_nexus/041504081604-inflow
from_schema: geoconnex
rank: 1000
slot_uri: https://www.opengis.net/def/hy_features/ontology/hyf/contributingCatchment
alias: https___www.opengis.net_def_hy_features_ontology_hyf_contributingCatchment
domain_of:
- rdfs_Resource
range: Any
any_of:
- range: uri
- range: rdfs_Resource

```
</details>