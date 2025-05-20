

# Slot: No slot (predicate) name specified (sockg_grainNitrogenSd_kgN_per_ha)


_No slot (predicate) description specified_






This slot occurs 70 times.


URI: [sockg:grainNitrogenSd_kgN_per_ha](https://idir.uta.edu/sockg-ontology/docs/grainNitrogenSd_kgN_per_ha)



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
| sockg_Harvest | double | sockg:individuals/182268 | 7.88 | 70 |


## See Also

* [https://lod.nal.usda.gov/nalt/325751](https://lod.nal.usda.gov/nalt/325751)



## LinkML Source

<details>

```yaml
name: sockg_grainNitrogenSd_kgN_per_ha
annotations:
  count:
    tag: count
    value: 70
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '7.88'
    example_object_type: double
    example_predicate: sockg:grainNitrogenSd_kgN_per_ha
    example_subject: sockg:individuals/182268
    example_subject_type: sockg_Harvest
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/325751
rank: 1000
domain: sockg_Harvest
slot_uri: sockg:grainNitrogenSd_kgN_per_ha
alias: sockg_grainNitrogenSd_kgN_per_ha
domain_of:
- sockg_Harvest
range: Any
any_of:
- range: double
- range: float

```
</details>