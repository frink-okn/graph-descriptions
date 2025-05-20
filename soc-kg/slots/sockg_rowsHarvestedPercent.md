

# Slot: No slot (predicate) name specified (sockg_rowsHarvestedPercent)


_No slot (predicate) description specified_






This slot occurs 3308 times.


URI: [sockg:rowsHarvestedPercent](https://idir.uta.edu/sockg-ontology/docs/rowsHarvestedPercent)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgResidueManagementEvent](../classes/SockgResidueManagementEvent.md) | A ResidueManagementEvent represents a specific instance of managing agricultu... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_ResidueManagementEvent | integer | sockg:individuals/227674 | 0 | 3308 |




## LinkML Source

<details>

```yaml
name: sockg_rowsHarvestedPercent
annotations:
  count:
    tag: count
    value: 3308
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '0'
    example_object_type: integer
    example_predicate: sockg:rowsHarvestedPercent
    example_subject: sockg:individuals/227674
    example_subject_type: sockg_ResidueManagementEvent
from_schema: soc-kg
rank: 1000
domain: sockg_ResidueManagementEvent
slot_uri: sockg:rowsHarvestedPercent
alias: sockg_rowsHarvestedPercent
domain_of:
- sockg_ResidueManagementEvent
range: Any
any_of:
- range: integer
- range: float

```
</details>