

# Slot: rural_mentalhealthservice_year


_No slot (predicate) description specified_





URI: [rural:mentalhealthservice/year](http://sail.ua.edu/ruralkg/mentalhealthservice/year)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralMentalhealthserviceMentalHealthService](../classes/RuralMentalhealthserviceMentalHealthService.md) | No class (type) description specified |  no  |
| [RuralMentalhealthserviceMentalHealthServiceCategory](../classes/RuralMentalhealthserviceMentalHealthServiceCategory.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:integer](xsd:integer)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rural_mentalhealthservice_MentalHealthService → integer | rural:mentalhealthservice/MHS_ACT | rural:mentalhealthservice/year | 2022 |
| rural_mentalhealthservice_MentalHealthServiceCategory → integer | rural:mentalhealthservice/MHSC_AGE | rural:mentalhealthservice/year | 2022 |


## Comments

* 176 occurrences with subject type rural_mentalhealthservice_MentalHealthService and object type integer.
* 21 occurrences with subject type rural_mentalhealthservice_MentalHealthServiceCategory and object type integer.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:mentalhealthservice/year |
| native | rural-kg/:rural_mentalhealthservice_year |




## LinkML Source

<details>
```yaml
name: rural_mentalhealthservice_year
description: No slot (predicate) description specified
comments:
- 176 occurrences with subject type rural_mentalhealthservice_MentalHealthService
  and object type integer.
- 21 occurrences with subject type rural_mentalhealthservice_MentalHealthServiceCategory
  and object type integer.
examples:
- description: rural_mentalhealthservice_MentalHealthService → integer
  object:
    example_object: '2022'
    example_predicate: rural:mentalhealthservice/year
    example_subject: rural:mentalhealthservice/MHS_ACT
- description: rural_mentalhealthservice_MentalHealthServiceCategory → integer
  object:
    example_object: '2022'
    example_predicate: rural:mentalhealthservice/year
    example_subject: rural:mentalhealthservice/MHSC_AGE
from_schema: rural-kg
rank: 1000
slot_uri: rural:mentalhealthservice/year
alias: rural_mentalhealthservice_year
domain_of:
- rural_mentalhealthservice_MentalHealthService
- rural_mentalhealthservice_MentalHealthServiceCategory
range: integer

```
</details>