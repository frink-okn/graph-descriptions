

# Slot: owl_equivalentClass


_No slot (predicate) description specified_





URI: [owl:equivalentClass](http://www.w3.org/2002/07/owl#equivalentClass)



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
| rdfs_Resource → rdfs_Resource | https://www.opengis.net/def/hy_features/ontology/hyf/HY_HydrometricNetwork | owl:equivalentClass | https://www.opengis.net/def/hy_features/ontology/hyf/HY_HydrometricNetwork |


## Comments

* 17 occurrences with subject type rdfs_Resource and object type rdfs_Resource.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | owl:equivalentClass |
| native | geoconnex/:owl_equivalentClass |




## LinkML Source

<details>
```yaml
name: owl_equivalentClass
description: No slot (predicate) description specified
comments:
- 17 occurrences with subject type rdfs_Resource and object type rdfs_Resource.
examples:
- description: rdfs_Resource → rdfs_Resource
  object:
    example_object: https://www.opengis.net/def/hy_features/ontology/hyf/HY_HydrometricNetwork
    example_predicate: owl:equivalentClass
    example_subject: https://www.opengis.net/def/hy_features/ontology/hyf/HY_HydrometricNetwork
from_schema: geoconnex
rank: 1000
slot_uri: owl:equivalentClass
alias: owl_equivalentClass
domain_of:
- rdfs_Resource
range: rdfs_Resource

```
</details>