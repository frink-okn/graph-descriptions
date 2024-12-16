

# Slot: rural_mentalhealthservice_description


_No slot (predicate) description specified_





URI: [rural:mentalhealthservice/description](http://sail.ua.edu/ruralkg/mentalhealthservice/description)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralMentalhealthserviceMentalHealthService](../classes/RuralMentalhealthserviceMentalHealthService.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rural_mentalhealthservice_MentalHealthService → string | rural:mentalhealthservice/MHS_ACT | rural:mentalhealthservice/description | A multi-disciplinary clinical team approach, helps those with serious mental illness live in the community by providing 24-hour intensive community services in the individual's natural setting. |


## Comments

* 176 occurrences with subject type rural_mentalhealthservice_MentalHealthService and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:mentalhealthservice/description |
| native | rural-kg/:rural_mentalhealthservice_description |




## LinkML Source

<details>
```yaml
name: rural_mentalhealthservice_description
description: No slot (predicate) description specified
comments:
- 176 occurrences with subject type rural_mentalhealthservice_MentalHealthService
  and object type string.
examples:
- description: rural_mentalhealthservice_MentalHealthService → string
  object:
    example_object: A multi-disciplinary clinical team approach, helps those with
      serious mental illness live in the community by providing 24-hour intensive
      community services in the individual's natural setting.
    example_predicate: rural:mentalhealthservice/description
    example_subject: rural:mentalhealthservice/MHS_ACT
from_schema: rural-kg
rank: 1000
slot_uri: rural:mentalhealthservice/description
alias: rural_mentalhealthservice_description
domain_of:
- rural_mentalhealthservice_MentalHealthService
range: string

```
</details>