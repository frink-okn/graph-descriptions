

# Slot: sockg_stageAtHarvest


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:stageAtHarvest](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/stageAtHarvest)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgResidueManagementEvent](../classes/SockgResidueManagementEvent.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#228839 sockg:stageAtHarvest Maturity |
| neo4j://graph.individuals#227698 sockg:stageAtHarvest nan |

## Comments

* 1650 occurrences with subject type sockg:ResidueManagementEvent and object type string.
* 1658 occurrences with subject type sockg:ResidueManagementEvent and object type xsd:double.

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
| self | sockg:stageAtHarvest |
| native | soc-kg/main/:sockg_stageAtHarvest |




## LinkML Source

<details>
```yaml
name: sockg_stageAtHarvest
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 1650 occurrences with subject type sockg:ResidueManagementEvent and object type
  string.
- 1658 occurrences with subject type sockg:ResidueManagementEvent and object type
  xsd:double.
examples:
- value: neo4j://graph.individuals#228839 sockg:stageAtHarvest Maturity
- value: neo4j://graph.individuals#227698 sockg:stageAtHarvest nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:stageAtHarvest
alias: sockg_stageAtHarvest
domain_of:
- sockg_ResidueManagementEvent
range: Any
any_of:
- range: string
- range: double

```
</details>