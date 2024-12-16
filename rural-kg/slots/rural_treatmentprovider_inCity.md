

# Slot: rural_treatmentprovider_inCity


_No slot (predicate) description specified_





URI: [rural:treatmentprovider/inCity](http://sail.ua.edu/ruralkg/treatmentprovider/inCity)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralTreatmentproviderTreatmentProvider](../classes/RuralTreatmentproviderTreatmentProvider.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[RuralAdministrativeareaCity](../classes/RuralAdministrativeareaCity.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rural_treatmentprovider_TreatmentProvider → rural_administrativearea_City | rural:treatmentprovider/TP_999 | rural:treatmentprovider/inCity | rural:administrativearea/City_1840020296 |
| rural_treatmentprovider_TreatmentProvider → uri | rural:treatmentprovider/TP_1107 | rural:treatmentprovider/inCity | rural:administrativearea/City_None |


## Comments

* 8117 occurrences with subject type rural_treatmentprovider_TreatmentProvider and object type rural_administrativearea_City.
* 920 occurrences with subject type rural_treatmentprovider_TreatmentProvider and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:treatmentprovider/inCity |
| native | rural-kg/:rural_treatmentprovider_inCity |




## LinkML Source

<details>
```yaml
name: rural_treatmentprovider_inCity
description: No slot (predicate) description specified
comments:
- 8117 occurrences with subject type rural_treatmentprovider_TreatmentProvider and
  object type rural_administrativearea_City.
- 920 occurrences with subject type rural_treatmentprovider_TreatmentProvider and
  object type uri.
examples:
- description: rural_treatmentprovider_TreatmentProvider → rural_administrativearea_City
  object:
    example_object: rural:administrativearea/City_1840020296
    example_predicate: rural:treatmentprovider/inCity
    example_subject: rural:treatmentprovider/TP_999
- description: rural_treatmentprovider_TreatmentProvider → uri
  object:
    example_object: rural:administrativearea/City_None
    example_predicate: rural:treatmentprovider/inCity
    example_subject: rural:treatmentprovider/TP_1107
from_schema: rural-kg
rank: 1000
slot_uri: rural:treatmentprovider/inCity
alias: rural_treatmentprovider_inCity
domain_of:
- rural_treatmentprovider_TreatmentProvider
range: Any
any_of:
- range: uri
- range: rural_administrativearea_City

```
</details>