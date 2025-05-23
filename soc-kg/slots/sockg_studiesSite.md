

# Slot: No slot (predicate) name specified (sockg_studiesSite)


_No slot (predicate) description specified_






This slot occurs 123 times.


URI: [sockg:studiesSite](https://idir.uta.edu/sockg-ontology/docs/studiesSite)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPublication](../classes/SockgPublication.md) | A Publication is a documented work that disseminates findings, research, or i... |  yes  |







## Properties

* Range: [SockgSite](../classes/SockgSite.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Publication | sockg_Site | sockg:individuals/227447 | sockg:individuals/231061 | 123 |




## LinkML Source

<details>

```yaml
name: sockg_studiesSite
annotations:
  count:
    tag: count
    value: 123
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/231061
    example_object_type: sockg_Site
    example_predicate: sockg:studiesSite
    example_subject: sockg:individuals/227447
    example_subject_type: sockg_Publication
from_schema: soc-kg
rank: 1000
domain: sockg_Publication
slot_uri: sockg:studiesSite
alias: sockg_studiesSite
domain_of:
- sockg_Publication
range: sockg_Site

```
</details>