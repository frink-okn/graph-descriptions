

# Slot: No slot (predicate) name specified (sudokn_hasWebAddress)


_No slot (predicate) description specified_






This slot occurs 1 times.


URI: [sudokn:hasWebAddress](http://asu.edu/semantics/SUDOKN/hasWebAddress)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | No class (type) description specified |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[SudoknWebAddress](../classes/SudoknWebAddress.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | [sudokn_hasWebAddress](../slots/sudokn_hasWebAddress.md) | domain | [sudokn_hasWebAddress](../slots/sudokn_hasWebAddress.md) |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | [sudokn_hasWebAddress](../slots/sudokn_hasWebAddress.md) | domain | [sudokn_hasWebAddress](../slots/sudokn_hasWebAddress.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_NamedIndividual | owl_NamedIndividual | sudokn:/Manufacturer_1 | sudokn:/WebAddress_1 | 1 |
| owl_NamedIndividual | sudokn_WebAddress | sudokn:/Manufacturer_1 | sudokn:/WebAddress_1 | 1 |
| io_Manufacturer | owl_NamedIndividual | sudokn:/Manufacturer_1 | sudokn:/WebAddress_1 | 1 |
| io_Manufacturer | sudokn_WebAddress | sudokn:/Manufacturer_1 | sudokn:/WebAddress_1 | 1 |




## LinkML Source

<details>

```yaml
name: sudokn_hasWebAddress
annotations:
  count:
    tag: count
    value: 1
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sudokn:/WebAddress_1
    example_object_type: owl_NamedIndividual
    example_predicate: sudokn:hasWebAddress
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: owl_NamedIndividual
- object:
    example_object: sudokn:/WebAddress_1
    example_object_type: sudokn_WebAddress
    example_predicate: sudokn:hasWebAddress
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: owl_NamedIndividual
- object:
    example_object: sudokn:/WebAddress_1
    example_object_type: owl_NamedIndividual
    example_predicate: sudokn:hasWebAddress
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: io_Manufacturer
- object:
    example_object: sudokn:/WebAddress_1
    example_object_type: sudokn_WebAddress
    example_predicate: sudokn:hasWebAddress
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: io_Manufacturer
from_schema: sudokn-kg
rank: 1000
domain: sudokn_hasWebAddress
slot_uri: sudokn:hasWebAddress
alias: sudokn_hasWebAddress
domain_of:
- io_Manufacturer
- owl_NamedIndividual
range: Any
any_of:
- range: owl_NamedIndividual
- range: sudokn_WebAddress
- range: uri

```
</details>