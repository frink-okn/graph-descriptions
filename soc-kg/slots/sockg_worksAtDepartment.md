

# Slot: No slot (predicate) name specified (sockg_worksAtDepartment)


_No slot (predicate) description specified_






This slot occurs 91 times.


URI: [sockg:worksAtDepartment](https://idir.uta.edu/sockg-ontology/docs/worksAtDepartment)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPerson](../classes/SockgPerson.md) | A Person represents an individual involved in agricultural activities, servin... |  yes  |







## Properties

* Range: [SockgDepartment](../classes/SockgDepartment.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Person | sockg_Department | sockg:individuals/203534 | sockg:individuals/51833 | 91 |




## LinkML Source

<details>

```yaml
name: sockg_worksAtDepartment
annotations:
  count:
    tag: count
    value: 91
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/51833
    example_object_type: sockg_Department
    example_predicate: sockg:worksAtDepartment
    example_subject: sockg:individuals/203534
    example_subject_type: sockg_Person
from_schema: soc-kg
rank: 1000
domain: sockg_Person
slot_uri: sockg:worksAtDepartment
alias: sockg_worksAtDepartment
domain_of:
- sockg_Person
range: sockg_Department

```
</details>