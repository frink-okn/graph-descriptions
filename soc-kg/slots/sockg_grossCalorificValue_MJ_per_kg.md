

# Slot: No slot (predicate) name specified (sockg_grossCalorificValue_MJ_per_kg)


_No slot (predicate) description specified_






This slot occurs 795 times.


URI: [sockg:grossCalorificValue_MJ_per_kg](https://idir.uta.edu/sockg-ontology/docs/grossCalorificValue_MJ_per_kg)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgBioMassEnergy](../classes/SockgBioMassEnergy.md) | BioMassEnergy represents the energy content derived from agricultural biomass... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_BioMassEnergy | double | sockg:individuals/39163 | 18.6668 | 795 |


## See Also

* [https://lod.nal.usda.gov/nalt/21409](https://lod.nal.usda.gov/nalt/21409)



## LinkML Source

<details>

```yaml
name: sockg_grossCalorificValue_MJ_per_kg
annotations:
  count:
    tag: count
    value: 795
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '18.6668'
    example_object_type: double
    example_predicate: sockg:grossCalorificValue_MJ_per_kg
    example_subject: sockg:individuals/39163
    example_subject_type: sockg_BioMassEnergy
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/21409
rank: 1000
domain: sockg_BioMassEnergy
slot_uri: sockg:grossCalorificValue_MJ_per_kg
alias: sockg_grossCalorificValue_MJ_per_kg
domain_of:
- sockg_BioMassEnergy
range: Any
any_of:
- range: double
- range: float

```
</details>