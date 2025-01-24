

# Slot: http___rdfs.org_ns_void#property


_No slot (predicate) description specified_





URI: [http://rdfs.org/ns/void#property](http://rdfs.org/ns/void#property)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RdfsResource](../classes/RdfsResource.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:anyURI](xsd:anyURI)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rdfs_Resource → uri | https://info.geoconnex.us/chyld-pilot/data/node/connect | http://rdfs.org/ns/void#property | https://geoconnex.ca/id/properties/connectedTo |


## Comments

* 1 occurrences with subject type rdfs_Resource and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | http://rdfs.org/ns/void#property |
| native | geoconnex/:http___rdfs.org_ns_void#property |




## LinkML Source

<details>
```yaml
name: http___rdfs.org_ns_void#property
description: No slot (predicate) description specified
comments:
- 1 occurrences with subject type rdfs_Resource and object type uri.
examples:
- description: rdfs_Resource → uri
  object:
    example_object: https://geoconnex.ca/id/properties/connectedTo
    example_predicate: http://rdfs.org/ns/void#property
    example_subject: https://info.geoconnex.us/chyld-pilot/data/node/connect
from_schema: geoconnex
rank: 1000
slot_uri: http://rdfs.org/ns/void#property
alias: http___rdfs.org_ns_void#property
domain_of:
- rdfs_Resource
range: uri

```
</details>