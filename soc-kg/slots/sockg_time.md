

# Slot: No slot (predicate) name specified (sockg_time)


_No slot (predicate) description specified_






This slot occurs 5471 times.


URI: [sockg:time](https://idir.uta.edu/sockg-ontology/docs/time)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGasSample](../classes/SockgGasSample.md) | GasSample represents a collection of measurements related to greenhouse gas e... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:time](http://www.w3.org/2001/XMLSchema#time)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_GasSample | string | sockg:individuals/156223 | 11:48:00 | 5471 |




## LinkML Source

<details>

```yaml
name: sockg_time
annotations:
  count:
    tag: count
    value: 5471
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '11:48:00'
    example_object_type: string
    example_predicate: sockg:time
    example_subject: sockg:individuals/156223
    example_subject_type: sockg_GasSample
from_schema: soc-kg
rank: 1000
slot_uri: sockg:time
alias: sockg_time
domain_of:
- sockg_GasSample
union_of:
- '{''domain'': ''sockg_WaterQualityArea''}'
- '{''domain'': ''sockg_WindErosionArea''}'
- '{''domain'': ''sockg_WaterQualityConc''}'
- '{''domain'': ''sockg_GasNutrientLoss''}'
- '{''domain'': ''sockg_GasSample''}'
range: Any
any_of:
- range: time
- range: string

```
</details>