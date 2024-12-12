

# Slot: sockg_harvestedFrac


_No slot description provided_





URI: [sockg:harvestedFrac](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/harvestedFrac)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgHarvest](../classes/SockgHarvest.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#180946 sockg:harvestedFrac Grain |
| neo4j://graph.individuals#187090 sockg:harvestedFrac nan |

## Comments

* 18047 occurrences with subject type sockg:Harvest and object type string.
* 309 occurrences with subject type sockg:Harvest and object type xsd:double.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: soc-kg/main




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sockg:harvestedFrac |
| native | soc-kg/main/:sockg_harvestedFrac |




## LinkML Source

<details>
```yaml
name: sockg_harvestedFrac
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 18047 occurrences with subject type sockg:Harvest and object type string.
- 309 occurrences with subject type sockg:Harvest and object type xsd:double.
examples:
- value: neo4j://graph.individuals#180946 sockg:harvestedFrac Grain
- value: neo4j://graph.individuals#187090 sockg:harvestedFrac nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:harvestedFrac
alias: sockg_harvestedFrac
domain_of:
- sockg_Harvest
range: Any
any_of:
- range: string
- range: double

```
</details>