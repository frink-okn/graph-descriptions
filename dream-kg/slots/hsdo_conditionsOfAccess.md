

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
| hsdo_TextObject → string | dreamkg:service/desc/5373543795916800 | hsdo:conditionsOfAccess | This program accepts Medicaid and Medicare. |


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
    example_object: This program accepts Medicaid and Medicare.
    example_predicate: hsdo:conditionsOfAccess
    example_subject: dreamkg:service/desc/5373543795916800
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:conditionsOfAccess
alias: hsdo_conditionsOfAccess
domain_of:
- hsdo_TextObject
range: string

```
</details>