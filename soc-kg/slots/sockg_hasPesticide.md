

# Slot: No slot (predicate) name specified (sockg_hasPesticide)


_No slot (predicate) description specified_






This slot occurs 42545 times.


URI: [sockg:hasPesticide](https://idir.uta.edu/sockg-ontology/docs/hasPesticide)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgAmendment](../classes/SockgAmendment.md) | An Amendment represents a specific alteration or addition made to agricultura... |  yes  |







## Properties

* Range: [SockgPesticide](../classes/SockgPesticide.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Amendment | sockg_Pesticide | sockg:individuals/0 | sockg:individuals/203632 | 42545 |




## LinkML Source

<details>

```yaml
name: sockg_hasPesticide
annotations:
  count:
    tag: count
    value: 42545
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/203632
    example_object_type: sockg_Pesticide
    example_predicate: sockg:hasPesticide
    example_subject: sockg:individuals/0
    example_subject_type: sockg_Amendment
from_schema: soc-kg
rank: 1000
domain: sockg_Amendment
slot_uri: sockg:hasPesticide
alias: sockg_hasPesticide
domain_of:
- sockg_Amendment
range: sockg_Pesticide

```
</details>