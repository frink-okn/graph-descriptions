

# Slot: No slot (predicate) name specified (sockg_measNutrEff_UID)


_No slot (predicate) description specified_






This slot occurs 2791 times.


URI: [sockg:measNutrEff_UID](https://idir.uta.edu/sockg-ontology/docs/measNutrEff_UID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgNutrientEfficiency](../classes/SockgNutrientEfficiency.md) | The NutrientEfficiency class represents the effectiveness of nutrient utiliza... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_NutrientEfficiency | string | sockg:individuals/200732 | AgCros_MNMOCAL_614_2014-09-15 | 2791 |




## LinkML Source

<details>

```yaml
name: sockg_measNutrEff_UID
annotations:
  count:
    tag: count
    value: 2791
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: AgCros_MNMOCAL_614_2014-09-15
    example_object_type: string
    example_predicate: sockg:measNutrEff_UID
    example_subject: sockg:individuals/200732
    example_subject_type: sockg_NutrientEfficiency
from_schema: soc-kg
rank: 1000
domain: sockg_NutrientEfficiency
slot_uri: sockg:measNutrEff_UID
alias: sockg_measNutrEff_UID
domain_of:
- sockg_NutrientEfficiency
range: string

```
</details>