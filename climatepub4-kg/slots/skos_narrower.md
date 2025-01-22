

# Slot: skos_narrower


_No slot (predicate) description specified_





URI: [skos:narrower](http://www.w3.org/2004/02/skos/core#narrower)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SkosConcept](../classes/SkosConcept.md) | No class (type) description specified |  no  |







## Properties

* Range: [SkosConcept](../classes/SkosConcept.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| skos_Concept → skos_Concept | https://gcmd.earthdata.nasa.gov/kms/concept/ffccf1c0-f25d-4747-ac4a-f09444383031 | skos:narrower | https://gcmd.earthdata.nasa.gov/kms/concept/c1c61697-b4bd-467c-9db4-5bd0115545a3 |


## Comments

* 16338 occurrences with subject type skos_Concept and object type skos_Concept.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | skos:narrower |
| native | climatepub4-kg/:skos_narrower |




## LinkML Source

<details>
```yaml
name: skos_narrower
description: No slot (predicate) description specified
comments:
- 16338 occurrences with subject type skos_Concept and object type skos_Concept.
examples:
- description: skos_Concept → skos_Concept
  object:
    example_object: https://gcmd.earthdata.nasa.gov/kms/concept/c1c61697-b4bd-467c-9db4-5bd0115545a3
    example_object_type: skos_Concept
    example_predicate: skos:narrower
    example_subject: https://gcmd.earthdata.nasa.gov/kms/concept/ffccf1c0-f25d-4747-ac4a-f09444383031
    example_subject_type: skos_Concept
from_schema: climatepub4-kg
rank: 1000
slot_uri: skos:narrower
alias: skos_narrower
domain_of:
- skos_Concept
range: skos_Concept

```
</details>