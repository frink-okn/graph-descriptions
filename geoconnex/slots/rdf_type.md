

# Slot: rdf_type


_No slot (predicate) description specified_





URI: [rdf:type](http://www.w3.org/1999/02/22-rdf-syntax-ns#type)



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
| rdfs_Resource → uri | http://geosciences.ca/def/groundwater#GW_AquiferSystem | rdf:type | rdfs:Class |


## Comments

* 34 occurrences with subject type rdfs_Resource and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rdf:type |
| native | geoconnex/:rdf_type |




## LinkML Source

<details>
```yaml
name: rdf_type
description: No slot (predicate) description specified
comments:
- 34 occurrences with subject type rdfs_Resource and object type uri.
examples:
- description: rdfs_Resource → uri
  object:
    example_object: rdfs:Class
    example_predicate: rdf:type
    example_subject: http://geosciences.ca/def/groundwater#GW_AquiferSystem
from_schema: geoconnex
rank: 1000
slot_uri: rdf:type
alias: rdf_type
domain_of:
- rdfs_Resource
range: uri

```
</details>