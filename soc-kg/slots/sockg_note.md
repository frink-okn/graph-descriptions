

# Slot: No slot (predicate) name specified (sockg_note)


_No slot (predicate) description specified_






This slot occurs 11 times.


URI: [sockg:note](https://idir.uta.edu/sockg-ontology/docs/note)



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
| sockg_Person | string | sockg:individuals/203545 | V. Jin is current contact for GRACEnet/REAP DET updates. | 11 |




## LinkML Source

<details>

```yaml
name: sockg_note
annotations:
  count:
    tag: count
    value: 11
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: V. Jin is current contact for GRACEnet/REAP DET updates.
    example_object_type: string
    example_predicate: sockg:note
    example_subject: sockg:individuals/203545
    example_subject_type: sockg_Person
from_schema: soc-kg
rank: 1000
domain: sockg_Person
slot_uri: sockg:note
alias: sockg_note
domain_of:
- sockg_Person
range: string

```
</details>