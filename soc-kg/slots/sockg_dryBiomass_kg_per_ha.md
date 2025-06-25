

# Slot: No slot (predicate) name specified (sockg_dryBiomass_kg_per_ha)


_No slot (predicate) description specified_






This slot occurs 7547 times.


URI: [sockg:dryBiomass_kg_per_ha](https://idir.uta.edu/sockg-ontology/docs/dryBiomass_kg_per_ha)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgHarvestFraction](../classes/SockgHarvestFraction.md) | The HarvestFraction class represents the quantifiable metrics and characteris... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_HarvestFraction | double | sockg:individuals/191262 | 79.6 | 7547 |




## LinkML Source

<details>

```yaml
name: sockg_dryBiomass_kg_per_ha
annotations:
  count:
    tag: count
    value: 7547
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '79.6'
    example_object_type: double
    example_predicate: sockg:dryBiomass_kg_per_ha
    example_subject: sockg:individuals/191262
    example_subject_type: sockg_HarvestFraction
from_schema: soc-kg
rank: 1000
domain: sockg_HarvestFraction
slot_uri: sockg:dryBiomass_kg_per_ha
alias: sockg_dryBiomass_kg_per_ha
domain_of:
- sockg_HarvestFraction
range: Any
any_of:
- range: float
- range: double

```
</details>