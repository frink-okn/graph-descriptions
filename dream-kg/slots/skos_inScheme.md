

# Slot: skos_inScheme


_No slot (predicate) description specified_






This slot occurs 16359 times.


URI: [skos:inScheme](http://www.w3.org/2004/02/skos/core#inScheme)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SkosConcept](../classes/SkosConcept.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| skos_Concept | uri | https://gcmd.earthdata.nasa.gov/kms/concept/0006e246-4296-448c-9b81-a0831cad7f1c | https://gcmd.earthdata.nasa.gov/kms/concepts/concept_scheme/ | 16359 |




## LinkML Source

<details>

```yaml
name: skos_inScheme
annotations:
  count:
    tag: count
    value: 16359
description: No slot (predicate) description specified
examples:
- object:
    example_object: https://gcmd.earthdata.nasa.gov/kms/concepts/concept_scheme/
    example_object_type: uri
    example_predicate: skos:inScheme
    example_subject: https://gcmd.earthdata.nasa.gov/kms/concept/0006e246-4296-448c-9b81-a0831cad7f1c
    example_subject_type: skos_Concept
from_schema: dream-kg
rank: 1000
slot_uri: skos:inScheme
alias: skos_inScheme
domain_of:
- skos_Concept
range: uri

```
</details>