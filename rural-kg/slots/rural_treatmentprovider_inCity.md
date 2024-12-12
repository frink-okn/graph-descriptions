

# Slot: rural_treatmentprovider_inCity


_No slot description provided_





URI: [rural:treatmentprovider/inCity](http://sail.ua.edu/ruralkg/treatmentprovider/inCity)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralTreatmentproviderTreatmentProvider](../classes/RuralTreatmentproviderTreatmentProvider.md) | Entities that provide treatment services, sourcing from National Directory Of... |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[RuralAdministrativeareaCity](../classes/RuralAdministrativeareaCity.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| rural:treatmentprovider/TP_2390 rural:treatmentprovider/inCity rural:administrativearea/City_1840000494 |
| rural:treatmentprovider/TP_1871 rural:treatmentprovider/inCity rural:administrativearea/City_None |

## Comments

* 8117 occurrences with subject type rural_treatmentprovider_TreatmentProvider and object type rural_administrativearea_City.
* 920 occurrences with subject type rural_treatmentprovider_TreatmentProvider and object type uri.

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
| self | rural:treatmentprovider/inCity |
| native | rural-kg/:rural_treatmentprovider_inCity |




## LinkML Source

<details>
```yaml
name: rural_treatmentprovider_inCity
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 8117 occurrences with subject type rural_treatmentprovider_TreatmentProvider and
  object type rural_administrativearea_City.
- 920 occurrences with subject type rural_treatmentprovider_TreatmentProvider and
  object type uri.
examples:
- value: rural:treatmentprovider/TP_2390 rural:treatmentprovider/inCity rural:administrativearea/City_1840000494
- value: rural:treatmentprovider/TP_1871 rural:treatmentprovider/inCity rural:administrativearea/City_None
from_schema: rural-kg
rank: 1000
slot_uri: rural:treatmentprovider/inCity
alias: rural_treatmentprovider_inCity
domain_of:
- rural_treatmentprovider_TreatmentProvider
range: Any
any_of:
- range: rural_administrativearea_City
- range: uri

```
</details>