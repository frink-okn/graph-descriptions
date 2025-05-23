

# Slot: No slot (predicate) name specified (sockg_grazingRate)


_No slot (predicate) description specified_






This slot occurs 20 times.


URI: [sockg:grazingRate](https://idir.uta.edu/sockg-ontology/docs/grazingRate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgTreatment](../classes/SockgTreatment.md) | The Treatment class encompasses various agricultural practices and management... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Treatment | string | sockg:individuals/363643 | Low | 20 |


## See Also

* [https://lod.nal.usda.gov/nalt/43782](https://lod.nal.usda.gov/nalt/43782)



## LinkML Source

<details>

```yaml
name: sockg_grazingRate
annotations:
  count:
    tag: count
    value: 20
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Low
    example_object_type: string
    example_predicate: sockg:grazingRate
    example_subject: sockg:individuals/363643
    example_subject_type: sockg_Treatment
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/43782
rank: 1000
domain: sockg_Treatment
slot_uri: sockg:grazingRate
alias: sockg_grazingRate
domain_of:
- sockg_Treatment
range: string

```
</details>