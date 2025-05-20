

# Slot: No slot (predicate) name specified (sockg_stockingRate_number_animals_per_ha)


_No slot (predicate) description specified_






This slot occurs 1951 times.


URI: [sockg:stockingRate_number_animals_per_ha](https://idir.uta.edu/sockg-ontology/docs/stockingRate_number_animals_per_ha)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGrazingManagementEvent](../classes/SockgGrazingManagementEvent.md) | A GrazingManagementEvent represents a specific instance of land management pr... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_GrazingManagementEvent | double | sockg:individuals/170955 | 0.0 | 1951 |


## See Also

* [https://lod.nal.usda.gov/nalt/9267](https://lod.nal.usda.gov/nalt/9267)



## LinkML Source

<details>

```yaml
name: sockg_stockingRate_number_animals_per_ha
annotations:
  count:
    tag: count
    value: 1951
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '0.0'
    example_object_type: double
    example_predicate: sockg:stockingRate_number_animals_per_ha
    example_subject: sockg:individuals/170955
    example_subject_type: sockg_GrazingManagementEvent
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/9267
rank: 1000
domain: sockg_GrazingManagementEvent
slot_uri: sockg:stockingRate_number_animals_per_ha
alias: sockg_stockingRate_number_animals_per_ha
domain_of:
- sockg_GrazingManagementEvent
range: Any
any_of:
- range: double
- range: float

```
</details>