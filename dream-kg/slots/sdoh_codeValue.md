

# Slot: codeValue (sdoh_codeValue)


_A short textual code that uniquely identifies the value._





URI: [sdoh:codeValue](http://schema.org/codeValue)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohCategoryCode](../classes/SdohCategoryCode.md) | A Category Code |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| dreamkg:category/service/main/CounselingMedicalCare sdoh:codeValue counseling medical care |

## Comments

* 158 occurrences with subject type sdoh_CategoryCode and object type string.

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
| self | sdoh:codeValue |
| native | dream-kg/:sdoh_codeValue |




## LinkML Source

<details>
```yaml
name: sdoh_codeValue
description: A short textual code that uniquely identifies the value.
title: codeValue
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 158 occurrences with subject type sdoh_CategoryCode and object type string.
examples:
- value: dreamkg:category/service/main/CounselingMedicalCare sdoh:codeValue counseling
    medical care
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:codeValue
alias: sdoh_codeValue
domain_of:
- sdoh_CategoryCode
range: string

```
</details>