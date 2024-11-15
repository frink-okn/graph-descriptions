

# Slot: opens (sdoh_opens)


_The opening hour of the place or service on the given day(s) of the week._





URI: [sdoh:opens](http://schema.org/opens)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohOpeningHoursSpecification](../classes/SdohOpeningHoursSpecification.md) | A structured value providing information about the opening hours of a place o... |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| dreamkg:service/hours/tuesday/5161629360586752 sdoh:opens 08:00 |

## Comments

* 631 occurrences with subject type sdoh_OpeningHoursSpecification and object type string.

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
| self | sdoh:opens |
| native | dream-kg/:sdoh_opens |




## LinkML Source

<details>
```yaml
name: sdoh_opens
description: The opening hour of the place or service on the given day(s) of the week.
title: opens
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 631 occurrences with subject type sdoh_OpeningHoursSpecification and object type
  string.
examples:
- value: dreamkg:service/hours/tuesday/5161629360586752 sdoh:opens 08:00
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:opens
alias: sdoh_opens
domain_of:
- sdoh_OpeningHoursSpecification
range: string

```
</details>