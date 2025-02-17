

# Slot: skos_altLabel


_No slot (predicate) description specified_






This slot occurs 1 times.


URI: [skos:altLabel](http://www.w3.org/2004/02/skos/core#altLabel)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SudoknOwnershipStatusClassifier](../classes/SudoknOwnershipStatusClassifier.md) | No class (type) description specified |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_NamedIndividual | string | sudokn:SmallDisadvantagedBusiness | 8(a) | 1 |
| sudokn_OwnershipStatusClassifier | string | sudokn:SmallDisadvantagedBusiness | 8(a) | 1 |




## LinkML Source

<details>

```yaml
name: skos_altLabel
annotations:
  count:
    tag: count
    value: 1
description: No slot (predicate) description specified
examples:
- object:
    example_object: 8(a)
    example_object_type: string
    example_predicate: skos:altLabel
    example_subject: sudokn:SmallDisadvantagedBusiness
    example_subject_type: owl_NamedIndividual
- object:
    example_object: 8(a)
    example_object_type: string
    example_predicate: skos:altLabel
    example_subject: sudokn:SmallDisadvantagedBusiness
    example_subject_type: sudokn_OwnershipStatusClassifier
from_schema: sudokn-kg
rank: 1000
slot_uri: skos:altLabel
alias: skos_altLabel
domain_of:
- owl_NamedIndividual
- sudokn_OwnershipStatusClassifier
range: string

```
</details>