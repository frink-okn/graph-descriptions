

# Slot: sdoh_dayOfWeek


_No slot description provided_





URI: [sdoh:dayOfWeek](http://schema.org/dayOfWeek)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohOpeningHoursSpecification](../classes/SdohOpeningHoursSpecification.md) | A structured value providing information about the opening hours of a place o... |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Value |
| --- |
| dreamkg:service/hours/saturday/5186727883833344 sdoh:dayOfWeek Saturday |

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
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 609 occurrences with subject type sdoh_OpeningHoursSpecification and object type
  string.
examples:
- value: dreamkg:service/hours/saturday/5186727883833344 sdoh:dayOfWeek Saturday
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:dayOfWeek
alias: sdoh_dayOfWeek
domain_of:
- sdoh_OpeningHoursSpecification
range: string

```
</details>