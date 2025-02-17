

# Slot: No slot (predicate) name specified (sudokn_hasManagementCapability)


_No slot (predicate) description specified_






This slot occurs 1 times.


URI: [sudokn:hasManagementCapability](http://asu.edu/semantics/SUDOKN/hasManagementCapability)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | No class (type) description specified |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[SudoknQualityManagementCapability](../classes/SudoknQualityManagementCapability.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | [sudokn_hasManagementCapability](../slots/sudokn_hasManagementCapability.md) | domain | [sudokn_hasManagementCapability](../slots/sudokn_hasManagementCapability.md) |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | [sudokn_hasManagementCapability](../slots/sudokn_hasManagementCapability.md) | domain | [sudokn_hasManagementCapability](../slots/sudokn_hasManagementCapability.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_NamedIndividual | owl_NamedIndividual | sudokn:/Manufacturer_1 | sudokn:/QualityManagementCapabiliy_1 | 1 |
| owl_NamedIndividual | sudokn_QualityManagementCapability | sudokn:/Manufacturer_1 | sudokn:/QualityManagementCapabiliy_1 | 1 |
| io_Manufacturer | owl_NamedIndividual | sudokn:/Manufacturer_1 | sudokn:/QualityManagementCapabiliy_1 | 1 |
| io_Manufacturer | sudokn_QualityManagementCapability | sudokn:/Manufacturer_1 | sudokn:/QualityManagementCapabiliy_1 | 1 |




## LinkML Source

<details>

```yaml
name: sudokn_hasManagementCapability
annotations:
  count:
    tag: count
    value: 1
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sudokn:/QualityManagementCapabiliy_1
    example_object_type: owl_NamedIndividual
    example_predicate: sudokn:hasManagementCapability
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: owl_NamedIndividual
- object:
    example_object: sudokn:/QualityManagementCapabiliy_1
    example_object_type: sudokn_QualityManagementCapability
    example_predicate: sudokn:hasManagementCapability
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: owl_NamedIndividual
- object:
    example_object: sudokn:/QualityManagementCapabiliy_1
    example_object_type: owl_NamedIndividual
    example_predicate: sudokn:hasManagementCapability
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: io_Manufacturer
- object:
    example_object: sudokn:/QualityManagementCapabiliy_1
    example_object_type: sudokn_QualityManagementCapability
    example_predicate: sudokn:hasManagementCapability
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: io_Manufacturer
from_schema: sudokn-kg
rank: 1000
domain: sudokn_hasManagementCapability
slot_uri: sudokn:hasManagementCapability
alias: sudokn_hasManagementCapability
domain_of:
- io_Manufacturer
- owl_NamedIndividual
range: Any
any_of:
- range: owl_NamedIndividual
- range: uri
- range: sudokn_QualityManagementCapability

```
</details>