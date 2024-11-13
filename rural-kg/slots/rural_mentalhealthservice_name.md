

# Slot: rural_mentalhealthservice_name


_TODO -- tell the world what this slot (predicate) describes._





URI: [rural:mentalhealthservice/name](http://sail.ua.edu/ruralkg/mentalhealthservice/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralMentalhealthserviceMentalHealthServiceCategory](../classes/RuralMentalhealthserviceMentalHealthServiceCategory.md) | TODO -- tell the world what this class (type) describes |  no  |
| [RuralMentalhealthserviceMentalHealthService](../classes/RuralMentalhealthserviceMentalHealthService.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| rural:mentalhealthservice/MHS_DV rural:mentalhealthservice/name Clients who have experienced intimate partner violence, domestic violence |
| rural:mentalhealthservice/MHSC_ECS rural:mentalhealthservice/name Education and Counseling Services |

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
| self | rural:mentalhealthservice/name |
| native | rural-kg/:rural_mentalhealthservice_name |




## LinkML Source

<details>
```yaml
name: rural_mentalhealthservice_name
description: TODO -- tell the world what this slot (predicate) describes.
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
- value: rural:mentalhealthservice/MHS_DV rural:mentalhealthservice/name Clients who
    have experienced intimate partner violence, domestic violence
- value: rural:mentalhealthservice/MHSC_ECS rural:mentalhealthservice/name Education
    and Counseling Services
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