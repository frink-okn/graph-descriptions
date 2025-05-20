

# Slot: No slot (predicate) name specified (sockg_description)


_No slot (predicate) description specified_






This slot occurs 53 times.


URI: [sockg:description](https://idir.uta.edu/sockg-ontology/docs/description)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPublication](../classes/SockgPublication.md) | A Publication is a documented work that disseminates findings, research, or i... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Publication | string | sockg:individuals/227450 | N2O | 53 |


## See Also

* [https://lod.nal.usda.gov/nalt/2179](https://lod.nal.usda.gov/nalt/2179)



## LinkML Source

<details>

```yaml
name: sockg_description
annotations:
  count:
    tag: count
    value: 53
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: N2O
    example_object_type: string
    example_predicate: sockg:description
    example_subject: sockg:individuals/227450
    example_subject_type: sockg_Publication
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/2179
rank: 1000
domain: sockg_MiscellaneousMeasurement
slot_uri: sockg:description
alias: sockg_description
domain_of:
- sockg_Publication
range: string

```
</details>