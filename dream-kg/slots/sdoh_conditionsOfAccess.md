

# Slot: conditionsOfAccess (sdoh_conditionsOfAccess)


_Conditions that affect the availability of, or method(s) of access to, an item. Typically used for real world items such as an [[ArchiveComponent]] held by an [[ArchiveOrganization]]. This property is not suitable for use as a general Web access control mechanism. It is expressed only in natural language.\n\nFor example "Available by appointment from the Reading Room" or "Accessible only from logged-in accounts ". _





URI: [sdoh:conditionsOfAccess](http://schema.org/conditionsOfAccess)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohTextObject](../classes/SdohTextObject.md) | A text file |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| dreamkg:service/desc/5481658659373056 sdoh:conditionsOfAccess Anyone can access this service. |

## Comments

* 88 occurrences with subject type sdoh_TextObject and object type string.

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
| self | sdoh:conditionsOfAccess |
| native | dream-kg/:sdoh_conditionsOfAccess |




## LinkML Source

<details>
```yaml
name: sdoh_conditionsOfAccess
description: 'Conditions that affect the availability of, or method(s) of access to,
  an item. Typically used for real world items such as an [[ArchiveComponent]] held
  by an [[ArchiveOrganization]]. This property is not suitable for use as a general
  Web access control mechanism. It is expressed only in natural language.\n\nFor example
  "Available by appointment from the Reading Room" or "Accessible only from logged-in
  accounts ". '
title: conditionsOfAccess
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 88 occurrences with subject type sdoh_TextObject and object type string.
examples:
- value: dreamkg:service/desc/5481658659373056 sdoh:conditionsOfAccess Anyone can
    access this service.
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:conditionsOfAccess
alias: sdoh_conditionsOfAccess
domain_of:
- sdoh_TextObject
range: string

```
</details>