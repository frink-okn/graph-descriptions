

# Slot: hsdo_codeValue


_No slot (predicate) description specified_





URI: [hsdo:codeValue](http://schema.org/codeValue)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoCategoryCode](HsdoCategoryCode.md) | A Category Code |  no  |







## Properties

* Range: [String](String.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_CategoryCode → string | dreamkg:category/availability/Available | hsdo:codeValue | available |


## Comments

* 158 occurrences with subject type hsdo_CategoryCode and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:codeValue |
| native | dream-kg/:hsdo_codeValue |




## LinkML Source

<details>
```yaml
name: hsdo_codeValue
description: No slot (predicate) description specified
comments:
- 158 occurrences with subject type hsdo_CategoryCode and object type string.
examples:
- description: hsdo_CategoryCode → string
  object:
    example_object: available
    example_object_type: string
    example_predicate: hsdo:codeValue
    example_subject: dreamkg:category/availability/Available
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