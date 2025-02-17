

# Slot: No slot (predicate) name specified (sudokn_hasEmailAddress)


_No slot (predicate) description specified_






This slot occurs 1 times.


URI: [sudokn:hasEmailAddress](http://asu.edu/semantics/SUDOKN/hasEmailAddress)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | No class (type) description specified |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[SudoknEmailAddress](../classes/SudoknEmailAddress.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | [sudokn_hasEmailAddress](../slots/sudokn_hasEmailAddress.md) | domain | [sudokn_hasEmailAddress](../slots/sudokn_hasEmailAddress.md) |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | [sudokn_hasEmailAddress](../slots/sudokn_hasEmailAddress.md) | domain | [sudokn_hasEmailAddress](../slots/sudokn_hasEmailAddress.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_NamedIndividual | owl_NamedIndividual | sudokn:/Manufacturer_1 | sudokn:/EmailAddress_1 | 1 |
| owl_NamedIndividual | sudokn_EmailAddress | sudokn:/Manufacturer_1 | sudokn:/EmailAddress_1 | 1 |
| io_Manufacturer | owl_NamedIndividual | sudokn:/Manufacturer_1 | sudokn:/EmailAddress_1 | 1 |
| io_Manufacturer | sudokn_EmailAddress | sudokn:/Manufacturer_1 | sudokn:/EmailAddress_1 | 1 |




## LinkML Source

<details>

```yaml
name: sudokn_hasEmailAddress
annotations:
  count:
    tag: count
    value: 1
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sudokn:/EmailAddress_1
    example_object_type: owl_NamedIndividual
    example_predicate: sudokn:hasEmailAddress
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: owl_NamedIndividual
- object:
    example_object: sudokn:/EmailAddress_1
    example_object_type: sudokn_EmailAddress
    example_predicate: sudokn:hasEmailAddress
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: owl_NamedIndividual
- object:
    example_object: sudokn:/EmailAddress_1
    example_object_type: owl_NamedIndividual
    example_predicate: sudokn:hasEmailAddress
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: io_Manufacturer
- object:
    example_object: sudokn:/EmailAddress_1
    example_object_type: sudokn_EmailAddress
    example_predicate: sudokn:hasEmailAddress
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: io_Manufacturer
from_schema: sudokn-kg
rank: 1000
domain: sudokn_hasEmailAddress
slot_uri: sudokn:hasEmailAddress
alias: sudokn_hasEmailAddress
domain_of:
- io_Manufacturer
- owl_NamedIndividual
range: Any
any_of:
- range: owl_NamedIndividual
- range: uri
- range: sudokn_EmailAddress

```
</details>