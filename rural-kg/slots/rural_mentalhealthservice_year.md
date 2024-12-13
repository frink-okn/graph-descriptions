

# Slot: rural_mentalhealthservice_year


_No slot description provided_





URI: [rural:mentalhealthservice/year](http://sail.ua.edu/ruralkg/mentalhealthservice/year)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralMentalhealthserviceMentalHealthServiceCategory](../classes/RuralMentalhealthserviceMentalHealthServiceCategory.md) | Categories of mental health services |  no  |
| [RuralMentalhealthserviceMentalHealthService](../classes/RuralMentalhealthserviceMentalHealthService.md) | Specific mental health services offered |  no  |







## Properties

* Range: [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| None |  |  |  |
| None |  |  |  |


## Comments

* 176 occurrences with subject type rural_mentalhealthservice_MentalHealthService and object type integer.
* 21 occurrences with subject type rural_mentalhealthservice_MentalHealthServiceCategory and object type integer.

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
| self | rural:mentalhealthservice/year |
| native | rural-kg/:rural_mentalhealthservice_year |




## LinkML Source

<details>
```yaml
name: rural_mentalhealthservice_year
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 176 occurrences with subject type rural_mentalhealthservice_MentalHealthService
  and object type integer.
- 21 occurrences with subject type rural_mentalhealthservice_MentalHealthServiceCategory
  and object type integer.
examples:
- value: rural:mentalhealthservice/MHS_PEER rural:mentalhealthservice/year 2022
- value: rural:mentalhealthservice/MHSC_SCR rural:mentalhealthservice/year 2022
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