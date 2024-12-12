

# Slot: sdoh_hoursAvailable


_No slot description provided_





URI: [sdoh:hoursAvailable](http://schema.org/hoursAvailable)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdohService](../classes/SdohService.md) | A service provided by an organization, e |  no  |







## Properties

* Range: [SdohOpeningHoursSpecification](../classes/SdohOpeningHoursSpecification.md)






## Examples

| Value |
| --- |
| dreamkg:service/4874573658193920 sdoh:hoursAvailable dreamkg:service/hours/thursday/4874573658193920 |

## Comments

* 609 occurrences with subject type sdoh_Service and object type sdoh_OpeningHoursSpecification.

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
| self | sdoh:hoursAvailable |
| native | dream-kg/:sdoh_hoursAvailable |




## LinkML Source

<details>
```yaml
name: sdoh_hoursAvailable
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 609 occurrences with subject type sdoh_Service and object type sdoh_OpeningHoursSpecification.
examples:
- value: dreamkg:service/4874573658193920 sdoh:hoursAvailable dreamkg:service/hours/thursday/4874573658193920
from_schema: dream-kg
rank: 1000
slot_uri: sdoh:hoursAvailable
alias: sdoh_hoursAvailable
domain_of:
- sdoh_Service
range: sdoh_OpeningHoursSpecification

```
</details>