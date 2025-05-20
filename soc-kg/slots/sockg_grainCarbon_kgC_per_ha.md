

# Slot: No slot (predicate) name specified (sockg_grainCarbon_kgC_per_ha)


_No slot (predicate) description specified_






This slot occurs 13693 times.


URI: [sockg:grainCarbon_kgC_per_ha](https://idir.uta.edu/sockg-ontology/docs/grainCarbon_kgC_per_ha)



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
| sockg_Harvest | double | sockg:individuals/172911 | 3887.817 | 13693 |


## See Also

* [https://lod.nal.usda.gov/nalt/325752](https://lod.nal.usda.gov/nalt/325752)



## LinkML Source

<details>

```yaml
name: sockg_grainCarbon_kgC_per_ha
annotations:
  count:
    tag: count
    value: 13693
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '3887.817'
    example_object_type: double
    example_predicate: sockg:grainCarbon_kgC_per_ha
    example_subject: sockg:individuals/172911
    example_subject_type: sockg_Harvest
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/325752
rank: 1000
domain: sockg_Harvest
slot_uri: sockg:grainCarbon_kgC_per_ha
alias: sockg_grainCarbon_kgC_per_ha
domain_of:
- sockg_Harvest
range: Any
any_of:
- range: double
- range: float

```
</details>