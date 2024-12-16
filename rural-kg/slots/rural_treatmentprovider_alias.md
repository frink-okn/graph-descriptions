

# Slot: rural_treatmentprovider_alias


_No slot (predicate) description specified_





URI: [rural:treatmentprovider/alias](http://sail.ua.edu/ruralkg/treatmentprovider/alias)



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
| rural_treatmentprovider_TreatmentProvider → string | rural:treatmentprovider/TP_1 | rural:treatmentprovider/alias | Henry County Clinic |


## Comments

* 9037 occurrences with subject type rural_treatmentprovider_TreatmentProvider and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:treatmentprovider/alias |
| native | rural-kg/:rural_treatmentprovider_alias |




## LinkML Source

<details>
```yaml
name: rural_treatmentprovider_alias
description: No slot (predicate) description specified
comments:
- 9037 occurrences with subject type rural_treatmentprovider_TreatmentProvider and
  object type string.
examples:
- description: rural_treatmentprovider_TreatmentProvider → string
  object:
    example_object: Henry County Clinic
    example_predicate: rural:treatmentprovider/alias
    example_subject: rural:treatmentprovider/TP_1
from_schema: rural-kg
rank: 1000
slot_uri: rural:treatmentprovider/alias
alias: rural_treatmentprovider_alias
domain_of:
- rural_treatmentprovider_TreatmentProvider
range: string

```
</details>