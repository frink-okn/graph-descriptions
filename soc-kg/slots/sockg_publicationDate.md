

# Slot: sockg_publicationDate


_No slot (predicate) description specified_






This slot occurs 162 times.


URI: [sockg:publicationDate](https://idir.uta.edu/sockg-ontology/docs/publicationDate)



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
| sockg_Publication | string | sockg:individuals/227447 | 2005-01-01 | 162 |




## LinkML Source

<details>

```yaml
name: sockg_publicationDate
annotations:
  count:
    tag: count
    value: 162
description: No slot (predicate) description specified
examples:
- object:
    example_object: '2005-01-01'
    example_object_type: string
    example_predicate: sockg:publicationDate
    example_subject: sockg:individuals/227447
    example_subject_type: sockg_Publication
from_schema: soc-kg
rank: 1000
slot_uri: sockg:publicationDate
alias: sockg_publicationDate
domain_of:
- sockg_Publication
range: string

```
</details>