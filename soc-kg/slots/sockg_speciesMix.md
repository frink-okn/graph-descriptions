

# Slot: No slot (predicate) name specified (sockg_speciesMix)


_No slot (predicate) description specified_






This slot occurs 6995 times.


URI: [sockg:speciesMix](https://idir.uta.edu/sockg-ontology/docs/speciesMix)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGrazing](../classes/SockgGrazing.md) | The Grazing class represents the assessment of various productivity metrics a... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Grazing | string | sockg:individuals/163960 | Bermuda | 6995 |


## See Also

* [https://lod.nal.usda.gov/nalt/41096](https://lod.nal.usda.gov/nalt/41096)



## LinkML Source

<details>

```yaml
name: sockg_speciesMix
annotations:
  count:
    tag: count
    value: 6995
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Bermuda
    example_object_type: string
    example_predicate: sockg:speciesMix
    example_subject: sockg:individuals/163960
    example_subject_type: sockg_Grazing
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/41096
rank: 1000
domain: sockg_Grazing
slot_uri: sockg:speciesMix
alias: sockg_speciesMix
domain_of:
- sockg_Grazing
range: string

```
</details>