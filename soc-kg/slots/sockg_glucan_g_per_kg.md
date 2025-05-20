

# Slot: No slot (predicate) name specified (sockg_glucan_g_per_kg)


_No slot (predicate) description specified_






This slot occurs 1367 times.


URI: [sockg:glucan_g_per_kg](https://idir.uta.edu/sockg-ontology/docs/glucan_g_per_kg)



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
| sockg_BioMassCarbohydrate | double | sockg:individuals/37796 | 441.3036 | 1367 |


## See Also

* [https://lod.nal.usda.gov/nalt/16831](https://lod.nal.usda.gov/nalt/16831)



## LinkML Source

<details>

```yaml
name: sockg_glucan_g_per_kg
annotations:
  count:
    tag: count
    value: 1367
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '441.3036'
    example_object_type: double
    example_predicate: sockg:glucan_g_per_kg
    example_subject: sockg:individuals/37796
    example_subject_type: sockg_BioMassCarbohydrate
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/16831
rank: 1000
domain: sockg_BioMassCarbohydrate
slot_uri: sockg:glucan_g_per_kg
alias: sockg_glucan_g_per_kg
domain_of:
- sockg_BioMassCarbohydrate
range: Any
any_of:
- range: double
- range: float

```
</details>