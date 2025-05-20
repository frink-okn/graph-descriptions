

# Slot: No slot (predicate) name specified (sockg_grainMoisturePercent)


_No slot (predicate) description specified_






This slot occurs 8426 times.


URI: [sockg:grainMoisturePercent](https://idir.uta.edu/sockg-ontology/docs/grainMoisturePercent)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgHarvest](../classes/SockgHarvest.md) | Harvest represents the process of collecting mature crops from the fields, wi... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Harvest | double | sockg:individuals/172906 | 21.3 | 8426 |




## LinkML Source

<details>

```yaml
name: sockg_grainMoisturePercent
annotations:
  count:
    tag: count
    value: 8426
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '21.3'
    example_object_type: double
    example_predicate: sockg:grainMoisturePercent
    example_subject: sockg:individuals/172906
    example_subject_type: sockg_Harvest
from_schema: soc-kg
rank: 1000
domain: sockg_Harvest
slot_uri: sockg:grainMoisturePercent
alias: sockg_grainMoisturePercent
domain_of:
- sockg_Harvest
range: Any
any_of:
- range: double
- range: float

```
</details>