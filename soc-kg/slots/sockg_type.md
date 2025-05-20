

# Slot: No slot (predicate) name specified (sockg_type)


_No slot (predicate) description specified_






This slot occurs 23230 times.


URI: [sockg:type](https://idir.uta.edu/sockg-ontology/docs/type)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgAmendment](../classes/SockgAmendment.md) | An Amendment represents a specific alteration or addition made to agricultura... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Amendment | string | sockg:individuals/1 | Lime | 23230 |


## See Also

* [https://lod.nal.usda.gov/nalt/63193](https://lod.nal.usda.gov/nalt/63193)



## LinkML Source

<details>

```yaml
name: sockg_type
annotations:
  count:
    tag: count
    value: 23230
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Lime
    example_object_type: string
    example_predicate: sockg:type
    example_subject: sockg:individuals/1
    example_subject_type: sockg_Amendment
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/63193
rank: 1000
slot_uri: sockg:type
alias: sockg_type
domain_of:
- sockg_Amendment
union_of:
- '{''domain'': ''sockg_Amendment''}'
- '{''domain'': ''sockg_Publication''}'
range: string

```
</details>