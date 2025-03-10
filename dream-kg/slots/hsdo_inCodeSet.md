

# Slot: hsdo_inCodeSet


_A [[CategoryCodeSet]] that contains this category code._






This slot occurs 157 times.


URI: [schema:inCodeSet](http://schema.org/inCodeSet)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |
| [HsdoCategoryCode](../classes/HsdoCategoryCode.md) | A Category Code |  yes  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| prov_Entity | uri | dreamkg:category/availability/Available | dreamkg:__CategoryCodeSet_Availability | 157 |
| hsdo_CategoryCode | uri | dreamkg:category/availability/Available | dreamkg:__CategoryCodeSet_Availability | 157 |




## LinkML Source

<details>

```yaml
name: hsdo_inCodeSet
annotations:
  count:
    tag: count
    value: 157
description: A [[CategoryCodeSet]] that contains this category code.
examples:
- object:
    example_object: dreamkg:__CategoryCodeSet_Availability
    example_object_type: uri
    example_predicate: schema:inCodeSet
    example_subject: dreamkg:category/availability/Available
    example_subject_type: prov_Entity
- object:
    example_object: dreamkg:__CategoryCodeSet_Availability
    example_object_type: uri
    example_predicate: schema:inCodeSet
    example_subject: dreamkg:category/availability/Available
    example_subject_type: hsdo_CategoryCode
from_schema: dream-kg
rank: 1000
slot_uri: schema:inCodeSet
alias: hsdo_inCodeSet
domain_of:
- hsdo_CategoryCode
- prov_Entity
range: uri

```
</details>