

# Slot: No slot (predicate) name specified (sockg_worksIn)


_No slot (predicate) description specified_






This slot occurs 165 times.


URI: [sockg:worksIn](https://idir.uta.edu/sockg-ontology/docs/worksIn)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPerson](../classes/SockgPerson.md) | A Person represents an individual involved in agricultural activities, servin... |  yes  |







## Properties

* Range: [SockgSite](../classes/SockgSite.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Person | sockg_Site | sockg:individuals/203534 | sockg:individuals/231057 | 165 |




## LinkML Source

<details>

```yaml
name: sockg_worksIn
annotations:
  count:
    tag: count
    value: 165
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/231057
    example_object_type: sockg_Site
    example_predicate: sockg:worksIn
    example_subject: sockg:individuals/203534
    example_subject_type: sockg_Person
from_schema: soc-kg
rank: 1000
domain: sockg_Person
slot_uri: sockg:worksIn
alias: sockg_worksIn
domain_of:
- sockg_Person
range: sockg_Site

```
</details>