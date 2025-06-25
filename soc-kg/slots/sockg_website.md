

# Slot: No slot (predicate) name specified (sockg_website)


_No slot (predicate) description specified_






This slot occurs 29 times.


URI: [sockg:website](https://idir.uta.edu/sockg-ontology/docs/website)



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
| sockg_Person | string | sockg:individuals/203534 | http://www.ars.usda.gov/pandp/people/people.htm?personid=36958 | 29 |




## LinkML Source

<details>

```yaml
name: sockg_website
annotations:
  count:
    tag: count
    value: 29
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: http://www.ars.usda.gov/pandp/people/people.htm?personid=36958
    example_object_type: string
    example_predicate: sockg:website
    example_subject: sockg:individuals/203534
    example_subject_type: sockg_Person
from_schema: soc-kg
rank: 1000
domain: sockg_Person
slot_uri: sockg:website
alias: sockg_website
domain_of:
- sockg_Person
range: string

```
</details>