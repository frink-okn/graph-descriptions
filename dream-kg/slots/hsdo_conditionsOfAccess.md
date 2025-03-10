

# Slot: hsdo_conditionsOfAccess


_Conditions that affect the availability of, or method(s) of access to, an item. Typically used for real world items such as an [[ArchiveComponent]] held by an [[ArchiveOrganization]]. This property is not suitable for use as a general Web access control mechanism. It is expressed only in natural language.\n\nFor example "Available by appointment from the Reading Room" or "Accessible only from logged-in accounts ". _






This slot occurs 88 times.


URI: [schema:conditionsOfAccess](http://schema.org/conditionsOfAccess)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoTextObject](../classes/HsdoTextObject.md) | No class (type) description specified |  yes  |
| [ProvEntity](../classes/ProvEntity.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| prov_Entity | string | dreamkg:service/desc/4542572480692224 | Must have Medical Assistance (Medicaid). This program helps people who are 13 to 19 years old. | 88 |
| hsdo_TextObject | string | dreamkg:service/desc/4542572480692224 | Must have Medical Assistance (Medicaid). This program helps people who are 13 to 19 years old. | 88 |




## LinkML Source

<details>

```yaml
name: hsdo_conditionsOfAccess
annotations:
  count:
    tag: count
    value: 88
description: 'Conditions that affect the availability of, or method(s) of access to,
  an item. Typically used for real world items such as an [[ArchiveComponent]] held
  by an [[ArchiveOrganization]]. This property is not suitable for use as a general
  Web access control mechanism. It is expressed only in natural language.\n\nFor example
  "Available by appointment from the Reading Room" or "Accessible only from logged-in
  accounts ". '
examples:
- object:
    example_object: Must have Medical Assistance (Medicaid). This program helps people
      who are 13 to 19 years old.
    example_object_type: string
    example_predicate: schema:conditionsOfAccess
    example_subject: dreamkg:service/desc/4542572480692224
    example_subject_type: prov_Entity
- object:
    example_object: Must have Medical Assistance (Medicaid). This program helps people
      who are 13 to 19 years old.
    example_object_type: string
    example_predicate: schema:conditionsOfAccess
    example_subject: dreamkg:service/desc/4542572480692224
    example_subject_type: hsdo_TextObject
from_schema: dream-kg
rank: 1000
slot_uri: schema:conditionsOfAccess
alias: hsdo_conditionsOfAccess
domain_of:
- hsdo_TextObject
- prov_Entity
range: string

```
</details>