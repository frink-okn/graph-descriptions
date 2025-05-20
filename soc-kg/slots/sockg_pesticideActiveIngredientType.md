

# Slot: No slot (predicate) name specified (sockg_pesticideActiveIngredientType)


_No slot (predicate) description specified_






This slot occurs 353 times.


URI: [sockg:pesticideActiveIngredientType](https://idir.uta.edu/sockg-ontology/docs/pesticideActiveIngredientType)



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
| sockg_Pesticide | string | sockg:individuals/203633 | 2,4-D; CAS No. 94-75-7 | 353 |


## See Also

* [https://lod.nal.usda.gov/nalt/3927](https://lod.nal.usda.gov/nalt/3927)



## LinkML Source

<details>

```yaml
name: sockg_pesticideActiveIngredientType
annotations:
  count:
    tag: count
    value: 353
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: 2,4-D; CAS No. 94-75-7
    example_object_type: string
    example_predicate: sockg:pesticideActiveIngredientType
    example_subject: sockg:individuals/203633
    example_subject_type: sockg_Pesticide
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/3927
rank: 1000
domain: sockg_Pesticide
slot_uri: sockg:pesticideActiveIngredientType
alias: sockg_pesticideActiveIngredientType
domain_of:
- sockg_Pesticide
range: string

```
</details>