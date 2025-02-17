

# Slot: No slot (predicate) name specified (sudokn_hasNAICSClassifier)


_No slot (predicate) description specified_






This slot occurs 1 times.


URI: [sudokn:hasNAICSClassifier](http://asu.edu/semantics/SUDOKN/hasNAICSClassifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | No class (type) description specified |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[SudoknNAICSClassifier](../classes/SudoknNAICSClassifier.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | [sudokn_hasNAICSClassifier](../slots/sudokn_hasNAICSClassifier.md) | domain | [sudokn_hasNAICSClassifier](../slots/sudokn_hasNAICSClassifier.md) |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | [sudokn_hasNAICSClassifier](../slots/sudokn_hasNAICSClassifier.md) | domain | [sudokn_hasNAICSClassifier](../slots/sudokn_hasNAICSClassifier.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_NamedIndividual | owl_NamedIndividual | sudokn:/Manufacturer_1 | sudokn:/NAICSClassifier_1 | 1 |
| owl_NamedIndividual | sudokn_NAICSClassifier | sudokn:/Manufacturer_1 | sudokn:/NAICSClassifier_1 | 1 |
| io_Manufacturer | owl_NamedIndividual | sudokn:/Manufacturer_1 | sudokn:/NAICSClassifier_1 | 1 |
| io_Manufacturer | sudokn_NAICSClassifier | sudokn:/Manufacturer_1 | sudokn:/NAICSClassifier_1 | 1 |




## LinkML Source

<details>

```yaml
name: sudokn_hasNAICSClassifier
annotations:
  count:
    tag: count
    value: 1
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sudokn:/NAICSClassifier_1
    example_object_type: owl_NamedIndividual
    example_predicate: sudokn:hasNAICSClassifier
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: owl_NamedIndividual
- object:
    example_object: sudokn:/NAICSClassifier_1
    example_object_type: sudokn_NAICSClassifier
    example_predicate: sudokn:hasNAICSClassifier
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: owl_NamedIndividual
- object:
    example_object: sudokn:/NAICSClassifier_1
    example_object_type: owl_NamedIndividual
    example_predicate: sudokn:hasNAICSClassifier
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: io_Manufacturer
- object:
    example_object: sudokn:/NAICSClassifier_1
    example_object_type: sudokn_NAICSClassifier
    example_predicate: sudokn:hasNAICSClassifier
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: io_Manufacturer
from_schema: sudokn-kg
rank: 1000
domain: sudokn_hasNAICSClassifier
slot_uri: sudokn:hasNAICSClassifier
alias: sudokn_hasNAICSClassifier
domain_of:
- io_Manufacturer
- owl_NamedIndividual
range: Any
any_of:
- range: owl_NamedIndividual
- range: uri
- range: sudokn_NAICSClassifier

```
</details>