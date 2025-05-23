

# Slot: No slot (predicate) name specified (sockg_measYieldNutUptake_UID)


_No slot (predicate) description specified_






This slot occurs 429 times.


URI: [sockg:measYieldNutUptake_UID](https://idir.uta.edu/sockg-ontology/docs/measYieldNutUptake_UID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgYieldNutrientUptake](../classes/SockgYieldNutrientUptake.md) | The YieldNutrientUptake class represents the assessment of nutrient uptake by... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_YieldNutrientUptake | string | sockg:individuals/624587 | AgCros_MNSP4R_U-S100B_2014-11-01 | 429 |




## LinkML Source

<details>

```yaml
name: sockg_measYieldNutUptake_UID
annotations:
  count:
    tag: count
    value: 429
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: AgCros_MNSP4R_U-S100B_2014-11-01
    example_object_type: string
    example_predicate: sockg:measYieldNutUptake_UID
    example_subject: sockg:individuals/624587
    example_subject_type: sockg_YieldNutrientUptake
from_schema: soc-kg
rank: 1000
domain: sockg_YieldNutrientUptake
slot_uri: sockg:measYieldNutUptake_UID
alias: sockg_measYieldNutUptake_UID
domain_of:
- sockg_YieldNutrientUptake
range: string

```
</details>