

# Slot: No slot (predicate) name specified (sockg_otherEvents)


_No slot (predicate) description specified_






This slot occurs 4 times.


URI: [sockg:otherEvents](https://idir.uta.edu/sockg-ontology/docs/otherEvents)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGrazingManagementEvent](../classes/SockgGrazingManagementEvent.md) | A GrazingManagementEvent represents a specific instance of land management pr... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_GrazingManagementEvent | string | sockg:individuals/172406 | Across rows | 4 |


## See Also

* [https://lod.nal.usda.gov/nalt/9183](https://lod.nal.usda.gov/nalt/9183)



## LinkML Source

<details>

```yaml
name: sockg_otherEvents
annotations:
  count:
    tag: count
    value: 4
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Across rows
    example_object_type: string
    example_predicate: sockg:otherEvents
    example_subject: sockg:individuals/172406
    example_subject_type: sockg_GrazingManagementEvent
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/9183
rank: 1000
domain: sockg_GrazingManagementEvent
slot_uri: sockg:otherEvents
alias: sockg_otherEvents
domain_of:
- sockg_GrazingManagementEvent
range: string

```
</details>