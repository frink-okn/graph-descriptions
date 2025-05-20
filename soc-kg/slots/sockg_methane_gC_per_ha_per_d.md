

# Slot: No slot (predicate) name specified (sockg_methane_gC_per_ha_per_d)


_No slot (predicate) description specified_






This slot occurs 107090 times.


URI: [sockg:methane_gC_per_ha_per_d](https://idir.uta.edu/sockg-ontology/docs/methane_gC_per_ha_per_d)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGasSample](../classes/SockgGasSample.md) | GasSample represents a collection of measurements related to greenhouse gas e... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_GasSample | double | sockg:individuals/100000 | -2.77317 | 107090 |


## See Also

* [https://lod.nal.usda.gov/nalt/6475](https://lod.nal.usda.gov/nalt/6475)



## LinkML Source

<details>

```yaml
name: sockg_methane_gC_per_ha_per_d
annotations:
  count:
    tag: count
    value: 107090
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '-2.77317'
    example_object_type: double
    example_predicate: sockg:methane_gC_per_ha_per_d
    example_subject: sockg:individuals/100000
    example_subject_type: sockg_GasSample
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/6475
rank: 1000
domain: sockg_GasSample
slot_uri: sockg:methane_gC_per_ha_per_d
alias: sockg_methane_gC_per_ha_per_d
domain_of:
- sockg_GasSample
range: Any
any_of:
- range: double
- range: float

```
</details>