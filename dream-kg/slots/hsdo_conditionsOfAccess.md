

# Slot: conditionsOfAccess (hsdo_conditionsOfAccess)


_Conditions that affect the availability of, or method(s) of access to, an item. Typically used for real world items such as an [[ArchiveComponent]] held by an [[ArchiveOrganization]]. This property is not suitable for use as a general Web access control mechanism. It is expressed only in natural language.\n\nFor example "Available by appointment from the Reading Room" or "Accessible only from logged-in accounts ". _






This slot occurs 88 times.


URI: [hsdo:conditionsOfAccess](http://schema.org/conditionsOfAccess)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoTextObject](../classes/HsdoTextObject.md) | A text file |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_TextObject | string | dreamkg:service/desc/6354456388829184 | We serve single men experiencing homelessness. | 88 |




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
title: conditionsOfAccess
examples:
- description: hsdo_TextObject→string
  object:
    example_object: We serve single men experiencing homelessness.
    example_object_type: string
    example_predicate: hsdo:conditionsOfAccess
    example_subject: dreamkg:service/desc/6354456388829184
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