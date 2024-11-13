

# Slot: sockg_startDate


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:startDate](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/startDate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgAmendment](../classes/SockgAmendment.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgExperiment](../classes/SockgExperiment.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgGrazingManagementEvent](../classes/SockgGrazingManagementEvent.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#6073 sockg:startDate 2010-04-23 |
| neo4j://graph.individuals#52263 sockg:startDate 2004-04-01 |
| neo4j://graph.individuals#172393 sockg:startDate 1996-08-15 |
| neo4j://graph.individuals#54995 sockg:startDate nan |
| neo4j://graph.individuals#51687 sockg:startDate 2009-01-01 |

## Comments

* 37796 occurrences with subject type sockg:Amendment and object type string.
* 3178 occurrences with subject type sockg:ExperimentalUnit and object type string.
* 1951 occurrences with subject type sockg:GrazingManagementEvent and object type string.
* 631 occurrences with subject type sockg:ExperimentalUnit and object type xsd:double.
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
| self | sockg:startDate |
| native | soc-kg/main/:sockg_startDate |




## LinkML Source

<details>
```yaml
name: sockg_startDate
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 37796 occurrences with subject type sockg:Amendment and object type string.
- 3178 occurrences with subject type sockg:ExperimentalUnit and object type string.
- 1951 occurrences with subject type sockg:GrazingManagementEvent and object type
  string.
- 631 occurrences with subject type sockg:ExperimentalUnit and object type xsd:double.
- 55 occurrences with subject type sockg:Experiment and object type string.
examples:
- value: neo4j://graph.individuals#6073 sockg:startDate 2010-04-23
- value: neo4j://graph.individuals#52263 sockg:startDate 2004-04-01
- value: neo4j://graph.individuals#172393 sockg:startDate 1996-08-15
- value: neo4j://graph.individuals#54995 sockg:startDate nan
- value: neo4j://graph.individuals#51687 sockg:startDate 2009-01-01
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:startDate
alias: sockg_startDate
domain_of:
- sockg_Amendment
- sockg_Experiment
- sockg_ExperimentalUnit
- sockg_GrazingManagementEvent
range: Any
any_of:
- range: string
- range: double

```
</details>