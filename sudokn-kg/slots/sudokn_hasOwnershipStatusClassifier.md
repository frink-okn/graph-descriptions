

# Slot: No slot (predicate) name specified (sudokn_hasOwnershipStatusClassifier)


_No slot (predicate) description specified_






This slot occurs 1120 times.


URI: [sudokn:hasOwnershipStatusClassifier](http://asu.edu/semantics/SUDOKN/hasOwnershipStatusClassifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | No class (type) description specified |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[SudoknOwnershipStatusClassifier](../classes/SudoknOwnershipStatusClassifier.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | [sudokn_hasOwnershipStatusClassifier](../slots/sudokn_hasOwnershipStatusClassifier.md) | domain | [sudokn_hasOwnershipStatusClassifier](../slots/sudokn_hasOwnershipStatusClassifier.md) |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | [sudokn_hasOwnershipStatusClassifier](../slots/sudokn_hasOwnershipStatusClassifier.md) | domain | [sudokn_hasOwnershipStatusClassifier](../slots/sudokn_hasOwnershipStatusClassifier.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_NamedIndividual | owl_NamedIndividual | sudokn:/Manufacturer_1 | sudokn:VeteranOwned | 1 |
| owl_NamedIndividual | sudokn_OwnershipStatusClassifier | sudokn:/Manufacturer_1 | sudokn:VeteranOwned | 1 |
| io_Manufacturer | owl_NamedIndividual | sudokn:/Manufacturer_1 | sudokn:VeteranOwned | 1036 |
| io_Manufacturer | sudokn_OwnershipStatusClassifier | sudokn:/Manufacturer_1 | sudokn:VeteranOwned | 1120 |




## LinkML Source

<details>

```yaml
name: sudokn_hasOwnershipStatusClassifier
annotations:
  count:
    tag: count
    value: 1120
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sudokn:VeteranOwned
    example_object_type: owl_NamedIndividual
    example_predicate: sudokn:hasOwnershipStatusClassifier
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: owl_NamedIndividual
- object:
    example_object: sudokn:VeteranOwned
    example_object_type: sudokn_OwnershipStatusClassifier
    example_predicate: sudokn:hasOwnershipStatusClassifier
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: owl_NamedIndividual
- object:
    example_object: sudokn:VeteranOwned
    example_object_type: owl_NamedIndividual
    example_predicate: sudokn:hasOwnershipStatusClassifier
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: io_Manufacturer
- object:
    example_object: sudokn:VeteranOwned
    example_object_type: sudokn_OwnershipStatusClassifier
    example_predicate: sudokn:hasOwnershipStatusClassifier
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: io_Manufacturer
from_schema: sudokn-kg
rank: 1000
domain: sudokn_hasOwnershipStatusClassifier
slot_uri: sudokn:hasOwnershipStatusClassifier
alias: sudokn_hasOwnershipStatusClassifier
domain_of:
- io_Manufacturer
- owl_NamedIndividual
range: Any
any_of:
- range: owl_NamedIndividual
- range: uri
- range: sudokn_OwnershipStatusClassifier

```
</details>