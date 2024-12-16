

# Slot: rural_treatmentprovider_providesService


_No slot (predicate) description specified_





URI: [rural:treatmentprovider/providesService](http://sail.ua.edu/ruralkg/treatmentprovider/providesService)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralTreatmentproviderTreatmentProvider](../classes/RuralTreatmentproviderTreatmentProvider.md) | No class (type) description specified |  no  |







## Properties

* Range: [RuralMentalhealthserviceMentalHealthService](../classes/RuralMentalhealthserviceMentalHealthService.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rural_treatmentprovider_TreatmentProvider → rural_mentalhealthservice_MentalHealthService | rural:treatmentprovider/TP_999 | rural:treatmentprovider/providesService | rural:mentalhealthservice/MHS_YAD |


## Comments

* 442841 occurrences with subject type rural_treatmentprovider_TreatmentProvider and object type rural_mentalhealthservice_MentalHealthService.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:treatmentprovider/providesService |
| native | rural-kg/:rural_treatmentprovider_providesService |




## LinkML Source

<details>
```yaml
name: rural_treatmentprovider_providesService
description: No slot (predicate) description specified
comments:
- 442841 occurrences with subject type rural_treatmentprovider_TreatmentProvider and
  object type rural_mentalhealthservice_MentalHealthService.
examples:
- description: rural_treatmentprovider_TreatmentProvider → rural_mentalhealthservice_MentalHealthService
  object:
    example_object: rural:mentalhealthservice/MHS_YAD
    example_predicate: rural:treatmentprovider/providesService
    example_subject: rural:treatmentprovider/TP_999
from_schema: rural-kg
rank: 1000
slot_uri: rural:treatmentprovider/providesService
alias: rural_treatmentprovider_providesService
domain_of:
- rural_treatmentprovider_TreatmentProvider
range: rural_mentalhealthservice_MentalHealthService

```
</details>