

# Slot: description (hsdo_description)


_A description of the item._






This slot occurs 87 times.


URI: [hsdo:description](http://schema.org/description)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoService](../classes/HsdoService.md) | A service provided by an organization, e |  yes  |







## Properties

* Range: [HsdoTextObject](../classes/HsdoTextObject.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Service | hsdo_TextObject | dreamkg:service/6379467169595392 | dreamkg:service/desc/6379467169595392 | 87 |




## LinkML Source

<details>

```yaml
name: hsdo_description
annotations:
  count:
    tag: count
    value: 87
description: A description of the item.
title: description
examples:
- description: hsdo_Service→hsdo_TextObject
  object:
    example_object: dreamkg:service/desc/6379467169595392
    example_object_type: hsdo_TextObject
    example_predicate: hsdo:description
    example_subject: dreamkg:service/6379467169595392
    example_subject_type: hsdo_Service
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:description
alias: hsdo_description
domain_of:
- hsdo_Service
range: hsdo_TextObject

```
</details>