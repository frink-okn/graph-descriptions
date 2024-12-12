

# Slot: sockg_endDate


_No slot description provided_





URI: [sockg:endDate](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/endDate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgAmendment](../classes/SockgAmendment.md) | No type description provided |  no  |
| [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | No type description provided |  no  |
| [SockgGrazingManagementEvent](../classes/SockgGrazingManagementEvent.md) | No type description provided |  no  |
| [SockgExperiment](../classes/SockgExperiment.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#11898 sockg:endDate nan |
| neo4j://graph.individuals#52943 sockg:endDate nan |
| neo4j://graph.individuals#52582 sockg:endDate 2009-11-11 |
| neo4j://graph.individuals#172114 sockg:endDate 2005-08-08 |
| neo4j://graph.individuals#51722 sockg:endDate 2011-05-18 |

## Comments

* 37796 occurrences with subject type sockg:Amendment and object type xsd:double.
* 2026 occurrences with subject type sockg:ExperimentalUnit and object type xsd:double.
* 1783 occurrences with subject type sockg:ExperimentalUnit and object type string.
* 1951 occurrences with subject type sockg:GrazingManagementEvent and object type string.
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
| self | sockg:endDate |
| native | soc-kg/main/:sockg_endDate |




## LinkML Source

<details>
```yaml
name: sockg_endDate
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 37796 occurrences with subject type sockg:Amendment and object type xsd:double.
- 2026 occurrences with subject type sockg:ExperimentalUnit and object type xsd:double.
- 1783 occurrences with subject type sockg:ExperimentalUnit and object type string.
- 1951 occurrences with subject type sockg:GrazingManagementEvent and object type
  string.
- 55 occurrences with subject type sockg:Experiment and object type string.
examples:
- value: neo4j://graph.individuals#11898 sockg:endDate nan
- value: neo4j://graph.individuals#52943 sockg:endDate nan
- value: neo4j://graph.individuals#52582 sockg:endDate 2009-11-11
- value: neo4j://graph.individuals#172114 sockg:endDate 2005-08-08
- value: neo4j://graph.individuals#51722 sockg:endDate 2011-05-18
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:endDate
alias: sockg_endDate
domain_of:
- sockg_Amendment
- sockg_Experiment
- sockg_ExperimentalUnit
- sockg_GrazingManagementEvent
range: Any
any_of:
- range: double
- range: string

```
</details>