

# Slot: No slot (predicate) name specified (sockg_pesticidePlacement)


_No slot (predicate) description specified_






This slot occurs 230 times.


URI: [sockg:pesticidePlacement](https://idir.uta.edu/sockg-ontology/docs/pesticidePlacement)



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
| sockg_Pesticide | string | sockg:individuals/203636 | Under soil with planter | 230 |


## See Also

* [https://lod.nal.usda.gov/nalt/142739](https://lod.nal.usda.gov/nalt/142739)



## LinkML Source

<details>

```yaml
name: sockg_pesticidePlacement
annotations:
  count:
    tag: count
    value: 230
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Under soil with planter
    example_object_type: string
    example_predicate: sockg:pesticidePlacement
    example_subject: sockg:individuals/203636
    example_subject_type: sockg_Pesticide
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/142739
rank: 1000
domain: sockg_Pesticide
slot_uri: sockg:pesticidePlacement
alias: sockg_pesticidePlacement
domain_of:
- sockg_Pesticide
range: string

```
</details>