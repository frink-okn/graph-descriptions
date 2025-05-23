

# Slot: No slot (predicate) name specified (sockg_bulkDensitySd_g_per_cm_cubed)


_No slot (predicate) description specified_






This slot occurs 50 times.


URI: [sockg:bulkDensitySd_g_per_cm_cubed](https://idir.uta.edu/sockg-ontology/docs/bulkDensitySd_g_per_cm_cubed)



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
| sockg_SoilPhysicalSample | double | sockg:individuals/310002 | 0.07 | 50 |


## See Also

* [https://lod.nal.usda.gov/nalt/20349](https://lod.nal.usda.gov/nalt/20349)



## LinkML Source

<details>

```yaml
name: sockg_bulkDensitySd_g_per_cm_cubed
annotations:
  count:
    tag: count
    value: 50
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '0.07'
    example_object_type: double
    example_predicate: sockg:bulkDensitySd_g_per_cm_cubed
    example_subject: sockg:individuals/310002
    example_subject_type: sockg_SoilPhysicalSample
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/20349
rank: 1000
domain: sockg_SoilPhysicalSample
slot_uri: sockg:bulkDensitySd_g_per_cm_cubed
alias: sockg_bulkDensitySd_g_per_cm_cubed
domain_of:
- sockg_SoilPhysicalSample
range: Any
any_of:
- range: float
- range: double

```
</details>