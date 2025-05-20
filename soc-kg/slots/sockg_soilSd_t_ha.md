

# Slot: No slot (predicate) name specified (sockg_soilSd_t_ha)


_No slot (predicate) description specified_






This slot occurs 15 times.


URI: [sockg:soilSd_t_ha](https://idir.uta.edu/sockg-ontology/docs/soilSd_t_ha)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | The WindErosionArea class represents regions affected by wind erosion, detail... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WindErosionArea | double | sockg:individuals/624572 | 4.4 | 15 |


## See Also

* [https://lod.nal.usda.gov/nalt/281219](https://lod.nal.usda.gov/nalt/281219)



## LinkML Source

<details>

```yaml
name: sockg_soilSd_t_ha
annotations:
  count:
    tag: count
    value: 15
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '4.4'
    example_object_type: double
    example_predicate: sockg:soilSd_t_ha
    example_subject: sockg:individuals/624572
    example_subject_type: sockg_WindErosionArea
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/281219
rank: 1000
domain: sockg_WindErosionArea
slot_uri: sockg:soilSd_t_ha
alias: sockg_soilSd_t_ha
domain_of:
- sockg_WindErosionArea
range: Any
any_of:
- range: double
- range: float

```
</details>