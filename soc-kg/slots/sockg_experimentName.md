

# Slot: sockg_experimentName


_No slot description provided_





URI: [sockg:experimentName](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/experimentName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgExperiment](../classes/SockgExperiment.md) | No type description provided |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#51733 sockg:experimentName Barnyard experiment of gas emissions, and nutrient concentrations in leachate and runoff from dairy cattle lots with different surface materials |

## Comments

* 55 occurrences with subject type sockg:Experiment and object type string.

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
| self | sockg:experimentName |
| native | soc-kg/main/:sockg_experimentName |




## LinkML Source

<details>
```yaml
name: sockg_experimentName
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 55 occurrences with subject type sockg:Experiment and object type string.
examples:
- value: neo4j://graph.individuals#51733 sockg:experimentName Barnyard experiment
    of gas emissions, and nutrient concentrations in leachate and runoff from dairy
    cattle lots with different surface materials
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:experimentName
alias: sockg_experimentName
domain_of:
- sockg_Experiment
range: string

```
</details>