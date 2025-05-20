

# Slot: No slot (predicate) name specified (sockg_email)


_No slot (predicate) description specified_






This slot occurs 87 times.


URI: [sockg:email](https://idir.uta.edu/sockg-ontology/docs/email)



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
| sockg_Person | string | sockg:individuals/203534 | steve.delgrosso@ars.usda.gov | 87 |


## See Also

* [https://lod.nal.usda.gov/nalt/35067](https://lod.nal.usda.gov/nalt/35067)



## LinkML Source

<details>

```yaml
name: sockg_email
annotations:
  count:
    tag: count
    value: 87
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: steve.delgrosso@ars.usda.gov
    example_object_type: string
    example_predicate: sockg:email
    example_subject: sockg:individuals/203534
    example_subject_type: sockg_Person
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/35067
rank: 1000
domain: sockg_Person
slot_uri: sockg:email
alias: sockg_email
domain_of:
- sockg_Person
range: string

```
</details>