

# Slot: No slot (predicate) name specified (sockg_identifier)


_No slot (predicate) description specified_






This slot occurs 114 times.


URI: [sockg:identifier](https://idir.uta.edu/sockg-ontology/docs/identifier)



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
| sockg_Publication | string | sockg:individuals/227447 | https://www.soils.org/publications/sssaj | 114 |




## LinkML Source

<details>

```yaml
name: sockg_identifier
annotations:
  count:
    tag: count
    value: 114
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: https://www.soils.org/publications/sssaj
    example_object_type: string
    example_predicate: sockg:identifier
    example_subject: sockg:individuals/227447
    example_subject_type: sockg_Publication
from_schema: soc-kg
rank: 1000
domain: sockg_Publication
slot_uri: sockg:identifier
alias: sockg_identifier
domain_of:
- sockg_Publication
range: string

```
</details>