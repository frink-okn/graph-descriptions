

# Slot: hsdo_inCodeSet


_No slot (predicate) description specified_





URI: [hsdo:inCodeSet](http://schema.org/inCodeSet)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoCategoryCode](../classes/HsdoCategoryCode.md) | A Category Code |  no  |







## Properties

* Range: [xsd:anyURI](xsd:anyURI)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_CategoryCode → uri | dreamkg:category/availability/Available | hsdo:inCodeSet | dreamkg:__CategoryCodeSet_Availability |


## Comments

* 157 occurrences with subject type hsdo_CategoryCode and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:inCodeSet |
| native | dream-kg/:hsdo_inCodeSet |




## LinkML Source

<details>
```yaml
name: hsdo_inCodeSet
description: No slot (predicate) description specified
comments:
- 157 occurrences with subject type hsdo_CategoryCode and object type uri.
examples:
- description: hsdo_CategoryCode → uri
  object:
    example_object: dreamkg:__CategoryCodeSet_Availability
    example_object_type: uri
    example_predicate: hsdo:inCodeSet
    example_subject: dreamkg:category/availability/Available
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