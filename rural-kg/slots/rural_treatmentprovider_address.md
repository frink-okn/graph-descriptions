

# Slot: rural_treatmentprovider_address


_No slot (predicate) description specified_





URI: [rural:treatmentprovider/address](http://sail.ua.edu/ruralkg/treatmentprovider/address)



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
| rural_treatmentprovider_TreatmentProvider → string | rural:treatmentprovider/TP_1 | rural:treatmentprovider/address | 219 Dothan Road, NaN |


## Comments

* 9037 occurrences with subject type rural_treatmentprovider_TreatmentProvider and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:treatmentprovider/address |
| native | rural-kg/:rural_treatmentprovider_address |




## LinkML Source

<details>
```yaml
name: rural_treatmentprovider_address
description: No slot (predicate) description specified
comments:
- 9037 occurrences with subject type rural_treatmentprovider_TreatmentProvider and
  object type string.
examples:
- description: rural_treatmentprovider_TreatmentProvider → string
  object:
    example_object: 219 Dothan Road, NaN
    example_predicate: rural:treatmentprovider/address
    example_subject: rural:treatmentprovider/TP_1
from_schema: rural-kg
rank: 1000
slot_uri: rural:treatmentprovider/address
alias: rural_treatmentprovider_address
domain_of:
- rural_treatmentprovider_TreatmentProvider
range: string

```
</details>