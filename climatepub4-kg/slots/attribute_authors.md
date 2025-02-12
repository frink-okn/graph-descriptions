

# Slot: attribute_authors


_No slot (predicate) description specified_






This slot occurs 287 times.


URI: [attribute:authors](http://attribute.org/authors)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoPaper](../classes/HsdoPaper.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_paper | string | https://climateKG.org/entity/008b3eddfa29b8dc6e8d97472e4526bec2c9c2cb | James N Ianelli; Anne B Hollowed; Alan C Haynie; Franz J Mueter; Nicholas A Bond | 287 |




## LinkML Source

<details>

```yaml
name: attribute_authors
annotations:
  count:
    tag: count
    value: 287
description: No slot (predicate) description specified
examples:
- description: hsdo_paper→string
  object:
    example_object: James N Ianelli; Anne B Hollowed; Alan C Haynie; Franz J Mueter;
      Nicholas A Bond
    example_object_type: string
    example_predicate: attribute:authors
    example_subject: https://climateKG.org/entity/008b3eddfa29b8dc6e8d97472e4526bec2c9c2cb
    example_subject_type: hsdo_paper
from_schema: climatepub4-kg
rank: 1000
slot_uri: attribute:authors
alias: attribute_authors
domain_of:
- hsdo_paper
range: string

```
</details>