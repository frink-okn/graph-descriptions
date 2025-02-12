

# Slot: codeValue (hsdo_codeValue)


_A short textual code that uniquely identifies the value._






This slot occurs 158 times.


URI: [hsdo:codeValue](http://schema.org/codeValue)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoCategoryCode](../classes/HsdoCategoryCode.md) | A Category Code |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_CategoryCode | string | dreamkg:category/service/main/ResidentialCare | residential care | 158 |




## LinkML Source

<details>

```yaml
name: hsdo_codeValue
annotations:
  count:
    tag: count
    value: 158
description: A short textual code that uniquely identifies the value.
title: codeValue
examples:
- description: hsdo_CategoryCode→string
  object:
    example_object: residential care
    example_object_type: string
    example_predicate: hsdo:codeValue
    example_subject: dreamkg:category/service/main/ResidentialCare
    example_subject_type: hsdo_CategoryCode
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:codeValue
alias: hsdo_codeValue
domain_of:
- hsdo_CategoryCode
range: string

```
</details>