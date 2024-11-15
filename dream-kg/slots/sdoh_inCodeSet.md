

# Slot: inCodeSet (sdoh_inCodeSet)


_A [[CategoryCodeSet]] that contains this category code._





URI: [sdoh:inCodeSet](http://schema.org/inCodeSet)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohCategoryCode](../classes/SdohCategoryCode.md) | A Category Code |  no  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| dreamkg:category/service/main/Treatment sdoh:inCodeSet dreamkg:_CategoryCodeSet_Services_Main |

## Comments

* 157 occurrences with subject type sdoh_CategoryCode and object type uri.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sdoh:inCodeSet |
| native | dream-kg/:sdoh_inCodeSet |




## LinkML Source

<details>
```yaml
name: sdoh_inCodeSet
description: A [[CategoryCodeSet]] that contains this category code.
title: inCodeSet
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 157 occurrences with subject type sdoh_CategoryCode and object type uri.
examples:
- value: dreamkg:category/service/main/Treatment sdoh:inCodeSet dreamkg:_CategoryCodeSet_Services_Main
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:inCodeSet
alias: sdoh_inCodeSet
domain_of:
- sdoh_CategoryCode
range: uri

```
</details>