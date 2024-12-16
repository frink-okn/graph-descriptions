

# Slot: rural_mentalhealthservice_name


_No slot (predicate) description specified_





URI: [rural:mentalhealthservice/name](http://sail.ua.edu/ruralkg/mentalhealthservice/name)



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
| rural_mentalhealthservice_MentalHealthService → string | rural:mentalhealthservice/MHS_ACT | rural:mentalhealthservice/name | Assertive community treatment |
| rural_mentalhealthservice_MentalHealthServiceCategory → string | rural:mentalhealthservice/MHSC_AGE | rural:mentalhealthservice/name | Age Groups Accepted |


## Comments

* 176 occurrences with subject type rural_mentalhealthservice_MentalHealthService and object type string.
* 21 occurrences with subject type rural_mentalhealthservice_MentalHealthServiceCategory and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:mentalhealthservice/name |
| native | rural-kg/:rural_mentalhealthservice_name |




## LinkML Source

<details>
```yaml
name: rural_mentalhealthservice_name
description: No slot (predicate) description specified
comments:
- 176 occurrences with subject type rural_mentalhealthservice_MentalHealthService
  and object type string.
- 21 occurrences with subject type rural_mentalhealthservice_MentalHealthServiceCategory
  and object type string.
examples:
- description: rural_mentalhealthservice_MentalHealthService → string
  object:
    example_object: Assertive community treatment
    example_predicate: rural:mentalhealthservice/name
    example_subject: rural:mentalhealthservice/MHS_ACT
- description: rural_mentalhealthservice_MentalHealthServiceCategory → string
  object:
    example_object: Age Groups Accepted
    example_predicate: rural:mentalhealthservice/name
    example_subject: rural:mentalhealthservice/MHSC_AGE
from_schema: rural-kg
rank: 1000
slot_uri: rural:mentalhealthservice/name
alias: rural_mentalhealthservice_name
domain_of:
- rural_mentalhealthservice_MentalHealthService
- rural_mentalhealthservice_MentalHealthServiceCategory
range: string

```
</details>