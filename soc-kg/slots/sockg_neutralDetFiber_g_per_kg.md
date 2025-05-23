

# Slot: No slot (predicate) name specified (sockg_neutralDetFiber_g_per_kg)


_No slot (predicate) description specified_






This slot occurs 799 times.


URI: [sockg:neutralDetFiber_g_per_kg](https://idir.uta.edu/sockg-ontology/docs/neutralDetFiber_g_per_kg)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgBioMassCarbohydrate](../classes/SockgBioMassCarbohydrate.md) | BioMassCarbohydrate represents the carbohydrate content in biomass derived fr... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_BioMassCarbohydrate | double | sockg:individuals/37991 | 800.0 | 799 |


## See Also

* [https://lod.nal.usda.gov/nalt/40032](https://lod.nal.usda.gov/nalt/40032)



## LinkML Source

<details>

```yaml
name: sockg_neutralDetFiber_g_per_kg
annotations:
  count:
    tag: count
    value: 799
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '800.0'
    example_object_type: double
    example_predicate: sockg:neutralDetFiber_g_per_kg
    example_subject: sockg:individuals/37991
    example_subject_type: sockg_BioMassCarbohydrate
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/40032
rank: 1000
domain: sockg_BioMassCarbohydrate
slot_uri: sockg:neutralDetFiber_g_per_kg
alias: sockg_neutralDetFiber_g_per_kg
domain_of:
- sockg_BioMassCarbohydrate
range: Any
any_of:
- range: float
- range: double

```
</details>