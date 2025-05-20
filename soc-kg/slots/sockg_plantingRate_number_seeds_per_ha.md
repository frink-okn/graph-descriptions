

# Slot: sockg_plantingRate_number_seeds_per_ha


_No slot (predicate) description specified_






This slot occurs 17377 times.


URI: [sockg:plantingRate_number_seeds_per_ha](https://idir.uta.edu/sockg-ontology/docs/plantingRate_number_seeds_per_ha)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPlantingEvent](../classes/SockgPlantingEvent.md) | An event involving the act of planting, which includes considerations for spa... |  yes  |







## Properties

* Range: [xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_PlantingEvent | double | sockg:individuals/203990 | 69188.0 | 17377 |




## LinkML Source

<details>

```yaml
name: sockg_plantingRate_number_seeds_per_ha
annotations:
  count:
    tag: count
    value: 17377
description: No slot (predicate) description specified
examples:
- object:
    example_object: '69188.0'
    example_object_type: double
    example_predicate: sockg:plantingRate_number_seeds_per_ha
    example_subject: sockg:individuals/203990
    example_subject_type: sockg_PlantingEvent
from_schema: soc-kg
rank: 1000
slot_uri: sockg:plantingRate_number_seeds_per_ha
alias: sockg_plantingRate_number_seeds_per_ha
domain_of:
- sockg_PlantingEvent
range: double

```
</details>