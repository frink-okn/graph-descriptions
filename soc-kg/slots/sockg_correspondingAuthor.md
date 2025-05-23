

# Slot: No slot (predicate) name specified (sockg_correspondingAuthor)


_No slot (predicate) description specified_






This slot occurs 126 times.


URI: [sockg:correspondingAuthor](https://idir.uta.edu/sockg-ontology/docs/correspondingAuthor)



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
| sockg_Publication | string | sockg:individuals/227450 | Halvorson | 126 |




## LinkML Source

<details>

```yaml
name: sockg_correspondingAuthor
annotations:
  count:
    tag: count
    value: 126
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Halvorson
    example_object_type: string
    example_predicate: sockg:correspondingAuthor
    example_subject: sockg:individuals/227450
    example_subject_type: sockg_Publication
from_schema: soc-kg
rank: 1000
domain: sockg_Publication
slot_uri: sockg:correspondingAuthor
alias: sockg_correspondingAuthor
domain_of:
- sockg_Publication
range: string

```
</details>