

# Slot: rdfs_subClassOf


_No slot (predicate) description specified_





URI: [rdfs:subClassOf](http://www.w3.org/2000/01/rdf-schema#subClassOf)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RdfsResource](../classes/RdfsResource.md) | No class (type) description specified |  no  |







## Properties

* Range: [RdfsResource](../classes/RdfsResource.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rdfs_Resource → rdfs_Resource | https://www.opengis.net/def/hy_features/ontology/hyf/HY_HydrometricNetwork | rdfs:subClassOf | https://www.opengis.net/def/hy_features/ontology/hyf/HY_HydrometricNetwork |


## Comments

* 43 occurrences with subject type rdfs_Resource and object type rdfs_Resource.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rdfs:subClassOf |
| native | geoconnex/:rdfs_subClassOf |




## LinkML Source

<details>
```yaml
name: rdfs_subClassOf
description: No slot (predicate) description specified
comments:
- 43 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
examples:
- description: rdfs_Resource → rdfs_Resource
  object:
    example_object: https://www.opengis.net/def/hy_features/ontology/hyf/HY_HydrometricNetwork
    example_predicate: rdfs:subClassOf
    example_subject: https://www.opengis.net/def/hy_features/ontology/hyf/HY_HydrometricNetwork
from_schema: geoconnex
rank: 1000
slot_uri: rdfs:subClassOf
alias: rdfs_subClassOf
domain_of:
- rdfs_Resource
range: rdfs_Resource

```
</details>