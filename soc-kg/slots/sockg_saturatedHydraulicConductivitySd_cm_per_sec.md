

# Slot: No slot (predicate) name specified (sockg_saturatedHydraulicConductivitySd_cm_per_sec)


_No slot (predicate) description specified_






This slot occurs 27 times.


URI: [sockg:saturatedHydraulicConductivitySd_cm_per_sec](https://idir.uta.edu/sockg-ontology/docs/saturatedHydraulicConductivitySd_cm_per_sec)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSoilPhysicalSample](../classes/SockgSoilPhysicalSample.md) | SoilPhysicalSample represents a comprehensive analysis of soil characteristic... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_SoilPhysicalSample | double | sockg:individuals/335220 | 0.3903844 | 27 |


## See Also

* [https://lod.nal.usda.gov/nalt/46278](https://lod.nal.usda.gov/nalt/46278)



## LinkML Source

<details>

```yaml
name: sockg_saturatedHydraulicConductivitySd_cm_per_sec
annotations:
  count:
    tag: count
    value: 27
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '0.3903844'
    example_object_type: double
    example_predicate: sockg:saturatedHydraulicConductivitySd_cm_per_sec
    example_subject: sockg:individuals/335220
    example_subject_type: sockg_SoilPhysicalSample
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/46278
rank: 1000
domain: sockg_SoilPhysicalSample
slot_uri: sockg:saturatedHydraulicConductivitySd_cm_per_sec
alias: sockg_saturatedHydraulicConductivitySd_cm_per_sec
domain_of:
- sockg_SoilPhysicalSample
range: Any
any_of:
- range: float
- range: double

```
</details>