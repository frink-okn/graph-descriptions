

# Slot: No slot (predicate) name specified (sockg_worksFor)


_No slot (predicate) description specified_






This slot occurs 35 times.


URI: [sockg:worksFor](https://idir.uta.edu/sockg-ontology/docs/worksFor)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPerson](../classes/SockgPerson.md) | A Person represents an individual involved in agricultural activities, servin... |  yes  |







## Properties

* Range: [SockgOrganization](../classes/SockgOrganization.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Person | sockg_Organization | sockg:individuals/203545 | sockg:individuals/203523 | 35 |




## LinkML Source

<details>

```yaml
name: sockg_worksFor
annotations:
  count:
    tag: count
    value: 35
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/203523
    example_object_type: sockg_Organization
    example_predicate: sockg:worksFor
    example_subject: sockg:individuals/203545
    example_subject_type: sockg_Person
from_schema: soc-kg
rank: 1000
domain: sockg_Person
slot_uri: sockg:worksFor
alias: sockg_worksFor
domain_of:
- sockg_Person
range: sockg_Organization

```
</details>