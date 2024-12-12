

# Slot: hsdo_conditionsOfAccess


_No slot (predicate) description specified_





URI: [hsdo:conditionsOfAccess](hsdo:conditionsOfAccess)



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
| hsdo_TextObject → string | dreamkg:service/desc/4829363626049536 | hsdo:conditionsOfAccess | Must have Medicare or Medicaid. |


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
    example_object: Must have Medicare or Medicaid.
    example_predicate: hsdo:conditionsOfAccess
    example_subject: dreamkg:service/desc/4829363626049536
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:conditionsOfAccess
alias: hsdo_conditionsOfAccess
domain_of:
- hsdo_TextObject
range: string

```
</details>