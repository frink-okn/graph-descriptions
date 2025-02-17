

# Slot: No slot (predicate) name specified (sudokn_hasName)


_No slot (predicate) description specified_






This slot occurs 1 times.


URI: [sudokn:hasName](http://asu.edu/semantics/SUDOKN/hasName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | No class (type) description specified |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[SudoknOrganizationName](../classes/SudoknOrganizationName.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_NamedIndividual | owl_NamedIndividual | sudokn:/Manufacturer_1 | sudokn:/OrganizationName_1 | 1 |
| owl_NamedIndividual | sudokn_OrganizationName | sudokn:/Manufacturer_1 | sudokn:/OrganizationName_1 | 1 |
| io_Manufacturer | owl_NamedIndividual | sudokn:/Manufacturer_1 | sudokn:/OrganizationName_1 | 1 |
| io_Manufacturer | sudokn_OrganizationName | sudokn:/Manufacturer_1 | sudokn:/OrganizationName_1 | 1 |




## LinkML Source

<details>

```yaml
name: sudokn_hasName
annotations:
  count:
    tag: count
    value: 1
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sudokn:/OrganizationName_1
    example_object_type: owl_NamedIndividual
    example_predicate: sudokn:hasName
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: owl_NamedIndividual
- object:
    example_object: sudokn:/OrganizationName_1
    example_object_type: sudokn_OrganizationName
    example_predicate: sudokn:hasName
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: owl_NamedIndividual
- object:
    example_object: sudokn:/OrganizationName_1
    example_object_type: owl_NamedIndividual
    example_predicate: sudokn:hasName
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: io_Manufacturer
- object:
    example_object: sudokn:/OrganizationName_1
    example_object_type: sudokn_OrganizationName
    example_predicate: sudokn:hasName
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: io_Manufacturer
from_schema: sudokn-kg
rank: 1000
slot_uri: sudokn:hasName
alias: sudokn_hasName
domain_of:
- io_Manufacturer
- owl_NamedIndividual
range: Any
any_of:
- range: owl_NamedIndividual
- range: sudokn_OrganizationName

```
</details>