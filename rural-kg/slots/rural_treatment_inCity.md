

# Slot: rural_treatment_inCity




This slot occurs 9037 times.


URI: [rural:treatment/inCity](http://sail.ua.edu/ruralkg/treatment/inCity)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralTreatmentTreatmentProvider](../classes/RuralTreatmentTreatmentProvider.md) | Entities that provide treatment services |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[RuralAdministrativeareaCity](../classes/RuralAdministrativeareaCity.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)







## LinkML Source

<details>

```yaml
name: rural_treatment_inCity
from_schema: okns:rural-kg
rank: 1000
slot_uri: rural:treatment/inCity
alias: rural_treatment_inCity
domain_of:
- rural_treatment_TreatmentProvider
range: Any
any_of:
- range: rural_administrativearea_City
- range: uri

```
</details>