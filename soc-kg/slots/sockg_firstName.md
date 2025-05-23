

# Slot: No slot (predicate) name specified (sockg_firstName)


_No slot (predicate) description specified_






This slot occurs 98 times.


URI: [sockg:firstName](https://idir.uta.edu/sockg-ontology/docs/firstName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPerson](../classes/SockgPerson.md) | A Person represents an individual involved in agricultural activities, servin... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Person | string | sockg:individuals/203534 | Steve | 98 |




## LinkML Source

<details>

```yaml
name: sockg_firstName
annotations:
  count:
    tag: count
    value: 98
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Steve
    example_object_type: string
    example_predicate: sockg:firstName
    example_subject: sockg:individuals/203534
    example_subject_type: sockg_Person
from_schema: soc-kg
rank: 1000
domain: sockg_Person
slot_uri: sockg:firstName
alias: sockg_firstName
domain_of:
- sockg_Person
range: string

```
</details>