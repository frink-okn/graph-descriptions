

# Slot: skos_inScheme


_No slot (predicate) description specified_





URI: [skos:inScheme](http://www.w3.org/2004/02/skos/core#inScheme)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SkosConcept](../classes/SkosConcept.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:anyURI](xsd:anyURI)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| skos_Concept → uri | https://gcmd.earthdata.nasa.gov/kms/concept/0006e246-4296-448c-9b81-a0831cad7f1c | skos:inScheme | https://gcmd.earthdata.nasa.gov/kms/concepts/concept_scheme/ |


## Comments

* 16359 occurrences with subject type skos_Concept and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: climatepub4-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | skos:inScheme |
| native | climatepub4-kg/:skos_inScheme |




## LinkML Source

<details>
```yaml
name: skos_inScheme
description: No slot (predicate) description specified
comments:
- 16359 occurrences with subject type skos_Concept and object type uri.
examples:
- description: skos_Concept → uri
  object:
    example_object: https://gcmd.earthdata.nasa.gov/kms/concepts/concept_scheme/
    example_object_type: uri
    example_predicate: skos:inScheme
    example_subject: https://gcmd.earthdata.nasa.gov/kms/concept/0006e246-4296-448c-9b81-a0831cad7f1c
    example_subject_type: skos_Concept
from_schema: climatepub4-kg
rank: 1000
slot_uri: skos:inScheme
alias: skos_inScheme
domain_of:
- skos_Concept
range: uri

```
</details>