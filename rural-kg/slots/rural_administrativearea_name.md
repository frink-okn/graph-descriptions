

# Slot: rural_administrativearea_name




This slot occurs 34429 times.


URI: [rural:administrativearea/name](http://sail.ua.edu/ruralkg/administrativearea/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralAdministrativeareaState](../classes/RuralAdministrativeareaState.md) | Represents individual states within U |  no  |
| [RuralAdministrativeareaCity](../classes/RuralAdministrativeareaCity.md) | City entities within a county or state |  no  |
| [RuralAdministrativeareaCounty](../classes/RuralAdministrativeareaCounty.md) | Defines counties within a state |  no  |







## Properties

* Range: [xsd:string](xsd:string)







## LinkML Source

<details>

```yaml
name: rural_administrativearea_name
from_schema: okns:rural-kg
rank: 1000
slot_uri: rural:administrativearea/name
alias: rural_administrativearea_name
domain_of:
- rural_administrativearea_City
- rural_administrativearea_County
- rural_administrativearea_State
range: string

```
</details>