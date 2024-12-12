

# Slot: sdoh_closes


_No slot description provided_





URI: [sdoh:closes](http://schema.org/closes)



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
| dreamkg:service/hours/tuesday/4666716061171712 sdoh:closes 17:00 |

## Comments

* 623 occurrences with subject type sdoh_OpeningHoursSpecification and object type string.

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
| self | sdoh:closes |
| native | dream-kg/:sdoh_closes |




## LinkML Source

<details>
```yaml
name: sdoh_closes
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 623 occurrences with subject type sdoh_OpeningHoursSpecification and object type
  string.
examples:
- value: dreamkg:service/hours/tuesday/4666716061171712 sdoh:closes 17:00
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:closes
alias: sdoh_closes
domain_of:
- sdoh_OpeningHoursSpecification
range: string

```
</details>