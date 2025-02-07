

# Slot: hsdo_conditionsOfAccess


_No slot (predicate) description specified_





URI: [hsdo:conditionsOfAccess](http://schema.org/conditionsOfAccess)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoTextObject](../classes/HsdoTextObject.md) | A text file |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_TextObject → string | dreamkg:service/desc/4542572480692224 | hsdo:conditionsOfAccess | Must have Medical Assistance (Medicaid). This program helps people who are 13 to 19 years old. |


## Comments

* 88 occurrences with subject type hsdo_TextObject and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:conditionsOfAccess |
| native | dream-kg/:hsdo_conditionsOfAccess |




## LinkML Source

<details>
```yaml
name: hsdo_conditionsOfAccess
description: No slot (predicate) description specified
comments:
- 88 occurrences with subject type hsdo_TextObject and object type string.
examples:
- description: hsdo_TextObject → string
  object:
    example_object: Must have Medical Assistance (Medicaid). This program helps people
      who are 13 to 19 years old.
    example_object_type: string
    example_predicate: hsdo:conditionsOfAccess
    example_subject: dreamkg:service/desc/4542572480692224
    example_subject_type: hsdo_TextObject
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:conditionsOfAccess
alias: hsdo_conditionsOfAccess
domain_of:
- hsdo_TextObject
range: string

```
</details>