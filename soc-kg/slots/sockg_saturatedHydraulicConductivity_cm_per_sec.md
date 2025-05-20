

# Slot: No slot (predicate) name specified (sockg_saturatedHydraulicConductivity_cm_per_sec)


_No slot (predicate) description specified_






This slot occurs 33 times.


URI: [sockg:saturatedHydraulicConductivity_cm_per_sec](https://idir.uta.edu/sockg-ontology/docs/saturatedHydraulicConductivity_cm_per_sec)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSoilPhysicalSample](../classes/SockgSoilPhysicalSample.md) | SoilPhysicalSample represents a comprehensive analysis of soil characteristic... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_SoilPhysicalSample | double | sockg:individuals/334651 | 0.00069444 | 33 |


## See Also

* [https://lod.nal.usda.gov/nalt/46278](https://lod.nal.usda.gov/nalt/46278)



## LinkML Source

<details>

```yaml
name: sockg_saturatedHydraulicConductivity_cm_per_sec
annotations:
  count:
    tag: count
    value: 33
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '0.00069444'
    example_object_type: double
    example_predicate: sockg:saturatedHydraulicConductivity_cm_per_sec
    example_subject: sockg:individuals/334651
    example_subject_type: sockg_SoilPhysicalSample
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/46278
rank: 1000
domain: sockg_SoilPhysicalSample
slot_uri: sockg:saturatedHydraulicConductivity_cm_per_sec
alias: sockg_saturatedHydraulicConductivity_cm_per_sec
domain_of:
- sockg_SoilPhysicalSample
range: Any
any_of:
- range: double
- range: float

```
</details>