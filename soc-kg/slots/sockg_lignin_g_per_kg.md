

# Slot: No slot (predicate) name specified (sockg_lignin_g_per_kg)


_No slot (predicate) description specified_






This slot occurs 799 times.


URI: [sockg:lignin_g_per_kg](https://idir.uta.edu/sockg-ontology/docs/lignin_g_per_kg)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgBioMassCarbohydrate](../classes/SockgBioMassCarbohydrate.md) | BioMassCarbohydrate represents the carbohydrate content in biomass derived fr... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_BioMassCarbohydrate | double | sockg:individuals/37991 | 42.0 | 799 |


## See Also

* [https://lod.nal.usda.gov/nalt/50048](https://lod.nal.usda.gov/nalt/50048)



## LinkML Source

<details>

```yaml
name: sockg_lignin_g_per_kg
annotations:
  count:
    tag: count
    value: 799
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '42.0'
    example_object_type: double
    example_predicate: sockg:lignin_g_per_kg
    example_subject: sockg:individuals/37991
    example_subject_type: sockg_BioMassCarbohydrate
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/50048
rank: 1000
domain: sockg_BioMassCarbohydrate
slot_uri: sockg:lignin_g_per_kg
alias: sockg_lignin_g_per_kg
domain_of:
- sockg_BioMassCarbohydrate
range: Any
any_of:
- range: double
- range: float

```
</details>