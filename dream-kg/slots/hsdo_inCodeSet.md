

# Slot: inCodeSet (hsdo_inCodeSet)


_A [[CategoryCodeSet]] that contains this category code._






This slot occurs 157 times.


URI: [hsdo:inCodeSet](http://schema.org/inCodeSet)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoCategoryCode](../classes/HsdoCategoryCode.md) | A Category Code |  yes  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_CategoryCode | uri | dreamkg:category/service/main/ResidentialCare | dreamkg:_CategoryCodeSet_Services_Main | 157 |




## LinkML Source

<details>

```yaml
name: hsdo_inCodeSet
annotations:
  count:
    tag: count
    value: 157
description: A [[CategoryCodeSet]] that contains this category code.
title: inCodeSet
examples:
- description: hsdo_CategoryCode→uri
  object:
    example_object: dreamkg:_CategoryCodeSet_Services_Main
    example_object_type: uri
    example_predicate: hsdo:inCodeSet
    example_subject: dreamkg:category/service/main/ResidentialCare
    example_subject_type: hsdo_CategoryCode
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:inCodeSet
alias: hsdo_inCodeSet
domain_of:
- hsdo_CategoryCode
range: uri

```
</details>