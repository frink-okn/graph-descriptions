

# Slot: No slot (predicate) name specified (sockg_title)


_No slot (predicate) description specified_






This slot occurs 136 times.


URI: [sockg:title](https://idir.uta.edu/sockg-ontology/docs/title)



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
| sockg_Publication | string | sockg:individuals/227449 | Nutrient concentrations in leachate and runoff from dairy cattle lots with different surface materials | 136 |




## LinkML Source

<details>

```yaml
name: sockg_title
annotations:
  count:
    tag: count
    value: 136
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Nutrient concentrations in leachate and runoff from dairy cattle
      lots with different surface materials
    example_object_type: string
    example_predicate: sockg:title
    example_subject: sockg:individuals/227449
    example_subject_type: sockg_Publication
from_schema: soc-kg
rank: 1000
domain: sockg_Publication
slot_uri: sockg:title
alias: sockg_title
domain_of:
- sockg_Publication
range: string

```
</details>