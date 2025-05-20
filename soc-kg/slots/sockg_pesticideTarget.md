

# Slot: No slot (predicate) name specified (sockg_pesticideTarget)


_No slot (predicate) description specified_






This slot occurs 247 times.


URI: [sockg:pesticideTarget](https://idir.uta.edu/sockg-ontology/docs/pesticideTarget)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPesticide](../classes/SockgPesticide.md) | Pesticides are substances used in agriculture to manage pests and diseases th... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Pesticide | string | sockg:individuals/203633 | weeds | 247 |


## See Also

* [https://lod.nal.usda.gov/nalt/839](https://lod.nal.usda.gov/nalt/839)



## LinkML Source

<details>

```yaml
name: sockg_pesticideTarget
annotations:
  count:
    tag: count
    value: 247
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: weeds
    example_object_type: string
    example_predicate: sockg:pesticideTarget
    example_subject: sockg:individuals/203633
    example_subject_type: sockg_Pesticide
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/839
rank: 1000
domain: sockg_Pesticide
slot_uri: sockg:pesticideTarget
alias: sockg_pesticideTarget
domain_of:
- sockg_Pesticide
range: string

```
</details>