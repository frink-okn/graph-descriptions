

# Slot: rural_treatmentprovider_phone


_No slot (predicate) description specified_





URI: [rural:treatmentprovider/phone](http://sail.ua.edu/ruralkg/treatmentprovider/phone)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralTreatmentproviderTreatmentProvider](../classes/RuralTreatmentproviderTreatmentProvider.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rural_treatmentprovider_TreatmentProvider → string | rural:treatmentprovider/TP_1 | rural:treatmentprovider/phone | 800-951-4357 |


## Comments

* 9037 occurrences with subject type rural_treatmentprovider_TreatmentProvider and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:treatmentprovider/phone |
| native | rural-kg/:rural_treatmentprovider_phone |




## LinkML Source

<details>
```yaml
name: rural_treatmentprovider_phone
description: No slot (predicate) description specified
comments:
- 9037 occurrences with subject type rural_treatmentprovider_TreatmentProvider and
  object type string.
examples:
- description: rural_treatmentprovider_TreatmentProvider → string
  object:
    example_object: 800-951-4357
    example_predicate: rural:treatmentprovider/phone
    example_subject: rural:treatmentprovider/TP_1
from_schema: rural-kg
rank: 1000
slot_uri: rural:treatmentprovider/phone
alias: rural_treatmentprovider_phone
domain_of:
- rural_treatmentprovider_TreatmentProvider
range: string

```
</details>