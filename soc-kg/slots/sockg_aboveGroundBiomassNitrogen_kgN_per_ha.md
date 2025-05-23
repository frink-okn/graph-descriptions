

# Slot: No slot (predicate) name specified (sockg_aboveGroundBiomassNitrogen_kgN_per_ha)


_No slot (predicate) description specified_






This slot occurs 2149 times.


URI: [sockg:aboveGroundBiomassNitrogen_kgN_per_ha](https://idir.uta.edu/sockg-ontology/docs/aboveGroundBiomassNitrogen_kgN_per_ha)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGrazing](../classes/SockgGrazing.md) | The Grazing class represents the assessment of various productivity metrics a... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Grazing | double | sockg:individuals/164143 | 76.07716 | 2149 |


## See Also

* [https://lod.nal.usda.gov/nalt/7829](https://lod.nal.usda.gov/nalt/7829)



## LinkML Source

<details>

```yaml
name: sockg_aboveGroundBiomassNitrogen_kgN_per_ha
annotations:
  count:
    tag: count
    value: 2149
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '76.07716'
    example_object_type: double
    example_predicate: sockg:aboveGroundBiomassNitrogen_kgN_per_ha
    example_subject: sockg:individuals/164143
    example_subject_type: sockg_Grazing
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/7829
rank: 1000
domain: sockg_Grazing
slot_uri: sockg:aboveGroundBiomassNitrogen_kgN_per_ha
alias: sockg_aboveGroundBiomassNitrogen_kgN_per_ha
domain_of:
- sockg_Grazing
range: Any
any_of:
- range: float
- range: double

```
</details>