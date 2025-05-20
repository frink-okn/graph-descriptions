

# Slot: sockg_citationType


_No slot (predicate) description specified_






This slot occurs 153 times.


URI: [sockg:citationType](https://idir.uta.edu/sockg-ontology/docs/citationType)



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
| sockg_Publication | string | sockg:individuals/227449 | Journal article about data | 153 |




## LinkML Source

<details>

```yaml
name: sockg_citationType
annotations:
  count:
    tag: count
    value: 153
description: No slot (predicate) description specified
examples:
- object:
    example_object: Journal article about data
    example_object_type: string
    example_predicate: sockg:citationType
    example_subject: sockg:individuals/227449
    example_subject_type: sockg_Publication
from_schema: soc-kg
rank: 1000
slot_uri: sockg:citationType
alias: sockg_citationType
domain_of:
- sockg_Publication
range: string

```
</details>