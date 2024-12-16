

# Slot: rural_mentalhealthservice_containsService


_No slot (predicate) description specified_





URI: [rural:mentalhealthservice/containsService](http://sail.ua.edu/ruralkg/mentalhealthservice/containsService)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralMentalhealthserviceMentalHealthServiceCategory](../classes/RuralMentalhealthserviceMentalHealthServiceCategory.md) | No class (type) description specified |  no  |







## Properties

* Range: [RuralMentalhealthserviceMentalHealthService](../classes/RuralMentalhealthserviceMentalHealthService.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rural_mentalhealthservice_MentalHealthServiceCategory → rural_mentalhealthservice_MentalHealthService | rural:mentalhealthservice/MHSC_TC | rural:mentalhealthservice/containsService | rural:mentalhealthservice/MHS_SUMH |


## Comments

* 176 occurrences with subject type rural_mentalhealthservice_MentalHealthServiceCategory and object type rural_mentalhealthservice_MentalHealthService.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:mentalhealthservice/containsService |
| native | rural-kg/:rural_mentalhealthservice_containsService |




## LinkML Source

<details>
```yaml
name: rural_mentalhealthservice_containsService
description: No slot (predicate) description specified
comments:
- 176 occurrences with subject type rural_mentalhealthservice_MentalHealthServiceCategory
  and object type rural_mentalhealthservice_MentalHealthService.
examples:
- description: rural_mentalhealthservice_MentalHealthServiceCategory → rural_mentalhealthservice_MentalHealthService
  object:
    example_object: rural:mentalhealthservice/MHS_SUMH
    example_predicate: rural:mentalhealthservice/containsService
    example_subject: rural:mentalhealthservice/MHSC_TC
from_schema: rural-kg
rank: 1000
slot_uri: rural:mentalhealthservice/containsService
alias: rural_mentalhealthservice_containsService
domain_of:
- rural_mentalhealthservice_MentalHealthServiceCategory
range: rural_mentalhealthservice_MentalHealthService

```
</details>