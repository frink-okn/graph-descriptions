

# Slot: No slot (predicate) name specified (sockg_mineralMatter_g_per_kg)


_No slot (predicate) description specified_






This slot occurs 799 times.


URI: [sockg:mineralMatter_g_per_kg](https://idir.uta.edu/sockg-ontology/docs/mineralMatter_g_per_kg)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgBioMassEnergy](../classes/SockgBioMassEnergy.md) | BioMassEnergy represents the energy content derived from agricultural biomass... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_BioMassEnergy | double | sockg:individuals/39163 | 73.2 | 799 |


## See Also

* [https://lod.nal.usda.gov/nalt/12905](https://lod.nal.usda.gov/nalt/12905)



## LinkML Source

<details>

```yaml
name: sockg_mineralMatter_g_per_kg
annotations:
  count:
    tag: count
    value: 799
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '73.2'
    example_object_type: double
    example_predicate: sockg:mineralMatter_g_per_kg
    example_subject: sockg:individuals/39163
    example_subject_type: sockg_BioMassEnergy
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/12905
rank: 1000
domain: sockg_BioMassEnergy
slot_uri: sockg:mineralMatter_g_per_kg
alias: sockg_mineralMatter_g_per_kg
domain_of:
- sockg_BioMassEnergy
range: Any
any_of:
- range: float
- range: double

```
</details>