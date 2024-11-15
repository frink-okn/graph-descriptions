

# Slot: dayOfWeek (sdoh_dayOfWeek)


_The day of the week for which these opening hours are valid._





URI: [sdoh:dayOfWeek](http://schema.org/dayOfWeek)



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
| dreamkg:service/hours/monday/5715375002484736 sdoh:dayOfWeek Monday |

## Comments

* 609 occurrences with subject type sdoh_OpeningHoursSpecification and object type string.

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
| self | sdoh:dayOfWeek |
| native | dream-kg/:sdoh_dayOfWeek |




## LinkML Source

<details>
```yaml
name: sdoh_dayOfWeek
description: The day of the week for which these opening hours are valid.
title: dayOfWeek
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 609 occurrences with subject type sdoh_OpeningHoursSpecification and object type
  string.
examples:
- value: dreamkg:service/hours/monday/5715375002484736 sdoh:dayOfWeek Monday
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:dayOfWeek
alias: sdoh_dayOfWeek
domain_of:
- sdoh_OpeningHoursSpecification
range: string

```
</details>