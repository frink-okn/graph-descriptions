

# Slot: rural_mentalhealthservice_code


_No slot (predicate) description specified_





URI: [rural:mentalhealthservice/code](http://sail.ua.edu/ruralkg/mentalhealthservice/code)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralMentalhealthserviceMentalHealthService](../classes/RuralMentalhealthserviceMentalHealthService.md) | No class (type) description specified |  no  |
| [RuralMentalhealthserviceMentalHealthServiceCategory](../classes/RuralMentalhealthserviceMentalHealthServiceCategory.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rural_mentalhealthservice_MentalHealthService → string | rural:mentalhealthservice/MHS_ACT | rural:mentalhealthservice/code | ACT |
| rural_mentalhealthservice_MentalHealthServiceCategory → string | rural:mentalhealthservice/MHSC_AGE | rural:mentalhealthservice/code | AGE |


## Comments

* 176 occurrences with subject type rural_mentalhealthservice_MentalHealthService and object type string.
* 21 occurrences with subject type rural_mentalhealthservice_MentalHealthServiceCategory and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:mentalhealthservice/code |
| native | rural-kg/:rural_mentalhealthservice_code |




## LinkML Source

<details>
```yaml
name: rural_mentalhealthservice_code
description: No slot (predicate) description specified
comments:
- 176 occurrences with subject type rural_mentalhealthservice_MentalHealthService
  and object type string.
- 21 occurrences with subject type rural_mentalhealthservice_MentalHealthServiceCategory
  and object type string.
examples:
- description: rural_mentalhealthservice_MentalHealthService → string
  object:
    example_object: ACT
    example_predicate: rural:mentalhealthservice/code
    example_subject: rural:mentalhealthservice/MHS_ACT
- description: rural_mentalhealthservice_MentalHealthServiceCategory → string
  object:
    example_object: AGE
    example_predicate: rural:mentalhealthservice/code
    example_subject: rural:mentalhealthservice/MHSC_AGE
from_schema: rural-kg
rank: 1000
slot_uri: rural:mentalhealthservice/code
alias: rural_mentalhealthservice_code
domain_of:
- rural_mentalhealthservice_MentalHealthService
- rural_mentalhealthservice_MentalHealthServiceCategory
range: string

```
</details>