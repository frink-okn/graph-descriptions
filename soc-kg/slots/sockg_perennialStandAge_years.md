

# Slot: No slot (predicate) name specified (sockg_perennialStandAge_years)


_No slot (predicate) description specified_






This slot occurs 826 times.


URI: [sockg:perennialStandAge_years](https://idir.uta.edu/sockg-ontology/docs/perennialStandAge_years)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgResidueManagementEvent](../classes/SockgResidueManagementEvent.md) | A ResidueManagementEvent represents a specific instance of managing agricultu... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[Int32](../types/Int32.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_ResidueManagementEvent | double | sockg:individuals/227783 | 4.0 | 826 |




## LinkML Source

<details>

```yaml
name: sockg_perennialStandAge_years
annotations:
  count:
    tag: count
    value: 826
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '4.0'
    example_object_type: double
    example_predicate: sockg:perennialStandAge_years
    example_subject: sockg:individuals/227783
    example_subject_type: sockg_ResidueManagementEvent
from_schema: soc-kg
rank: 1000
domain: sockg_ResidueManagementEvent
slot_uri: sockg:perennialStandAge_years
alias: sockg_perennialStandAge_years
domain_of:
- sockg_ResidueManagementEvent
range: Any
any_of:
- range: double
- range: int32

```
</details>