

# Slot: rural_treatmentprovider_name


_No slot (predicate) description specified_





URI: [rural:treatmentprovider/name](http://sail.ua.edu/ruralkg/treatmentprovider/name)



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
| rural_treatmentprovider_TreatmentProvider → string | rural:treatmentprovider/TP_1 | rural:treatmentprovider/name | SpectraCare Health Systems |


## Comments

* 9037 occurrences with subject type rural_treatmentprovider_TreatmentProvider and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:treatmentprovider/name |
| native | rural-kg/:rural_treatmentprovider_name |




## LinkML Source

<details>
```yaml
name: rural_treatmentprovider_name
description: No slot (predicate) description specified
comments:
- 9037 occurrences with subject type rural_treatmentprovider_TreatmentProvider and
  object type string.
examples:
- description: rural_treatmentprovider_TreatmentProvider → string
  object:
    example_object: SpectraCare Health Systems
    example_predicate: rural:treatmentprovider/name
    example_subject: rural:treatmentprovider/TP_1
from_schema: rural-kg
rank: 1000
slot_uri: rural:treatmentprovider/name
alias: rural_treatmentprovider_name
domain_of:
- rural_treatmentprovider_TreatmentProvider
range: string

```
</details>