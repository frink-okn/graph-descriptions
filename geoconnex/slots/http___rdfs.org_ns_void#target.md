

# Slot: http___rdfs.org_ns_void#target


_No slot (predicate) description specified_





URI: [http://rdfs.org/ns/void#target](http://rdfs.org/ns/void#target)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RdfsResource](../classes/RdfsResource.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[HttpRdfs.orgNsVoid#Dataset](../classes/HttpRdfs.orgNsVoid#Dataset.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rdfs_Resource → http___rdfs.org_ns_void#Dataset | https://info.geoconnex.us/chyld-pilot/data/node/connect | http://rdfs.org/ns/void#target | https://geoconnex.us/chyld-pilot/id/LOD_Node/US_Hydro_LOD_Node |
| rdfs_Resource → uri | https://info.geoconnex.us/chyld-pilot/data/node/connect | http://rdfs.org/ns/void#target | https://geoconnex.ca/id/CAN_LOD_Node |


## Comments

* 1 occurrences with subject type rdfs_Resource and object type http___rdfs.org_ns_void#Dataset.
* 1 occurrences with subject type rdfs_Resource and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | http://rdfs.org/ns/void#target |
| native | geoconnex/:http___rdfs.org_ns_void#target |




## LinkML Source

<details>
```yaml
name: http___rdfs.org_ns_void#target
description: No slot (predicate) description specified
comments:
- 1 occurrences with subject type rdfs_Resource and object type http___rdfs.org_ns_void#Dataset.
- 1 occurrences with subject type rdfs_Resource and object type uri.
examples:
- description: rdfs_Resource → http___rdfs.org_ns_void#Dataset
  object:
    example_object: https://geoconnex.us/chyld-pilot/id/LOD_Node/US_Hydro_LOD_Node
    example_predicate: http://rdfs.org/ns/void#target
    example_subject: https://info.geoconnex.us/chyld-pilot/data/node/connect
- description: rdfs_Resource → uri
  object:
    example_object: https://geoconnex.ca/id/CAN_LOD_Node
    example_predicate: http://rdfs.org/ns/void#target
    example_subject: https://info.geoconnex.us/chyld-pilot/data/node/connect
from_schema: geoconnex
rank: 1000
slot_uri: http://rdfs.org/ns/void#target
alias: http___rdfs.org_ns_void#target
domain_of:
- rdfs_Resource
range: Any
any_of:
- range: uri
- range: http___rdfs.org_ns_void#Dataset

```
</details>