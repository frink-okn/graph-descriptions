

# Slot: rural_variable_hasAnswer




This slot occurs 17181 times.


URI: [rural:variable/hasAnswer](http://sail.ua.edu/ruralkg/variable/hasAnswer)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralVariableNSDUH](../classes/RuralVariableNSDUH.md) | Variables from the National Survey on Drug Use and Health dataset |  no  |
| [RuralVariableNIBRS](../classes/RuralVariableNIBRS.md) | Variables from the National Incident-Based Reporting System dataset |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[RuralVariableNIBRSAnswer](../classes/RuralVariableNIBRSAnswer.md)&nbsp;or&nbsp;<br />[RuralVariableNSDUHAnswer](../classes/RuralVariableNSDUHAnswer.md)







## LinkML Source

<details>

```yaml
name: rural_variable_hasAnswer
from_schema: okns:rural-kg
rank: 1000
slot_uri: rural:variable/hasAnswer
alias: rural_variable_hasAnswer
domain_of:
- rural_variable_NIBRS
- rural_variable_NSDUH
range: Any
any_of:
- range: rural_variable_NIBRSAnswer
- range: rural_variable_NSDUHAnswer

```
</details>