

# Slot: rural_mentalhealthservice_code


_No slot description provided_





URI: [rural:mentalhealthservice/code](http://sail.ua.edu/ruralkg/mentalhealthservice/code)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralMentalhealthserviceMentalHealthServiceCategory](../classes/RuralMentalhealthserviceMentalHealthServiceCategory.md) | Categories of mental health services |  no  |
| [RuralMentalhealthserviceMentalHealthService](../classes/RuralMentalhealthserviceMentalHealthService.md) | Specific mental health services offered |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| None |  |  |  |
| None |  |  |  |


## Comments

* 176 occurrences with subject type rural_mentalhealthservice_MentalHealthService and object type string.
* 21 occurrences with subject type rural_mentalhealthservice_MentalHealthServiceCategory and object type string.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

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
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 176 occurrences with subject type rural_mentalhealthservice_MentalHealthService
  and object type string.
- 21 occurrences with subject type rural_mentalhealthservice_MentalHealthServiceCategory
  and object type string.
examples:
- value: rural:mentalhealthservice/MHS_AH rural:mentalhealthservice/code AH
- value: rural:mentalhealthservice/MHSC_OL rural:mentalhealthservice/code OL
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