

# Slot: sockg_animalClass


_No slot description provided_





URI: [sockg:animalClass](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/animalClass)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGrazingManagementEvent](../classes/SockgGrazingManagementEvent.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#171465 sockg:animalClass Neutered male |
| neo4j://graph.individuals#172634 sockg:animalClass nan |

## Comments

* 1833 occurrences with subject type sockg:GrazingManagementEvent and object type string.
* 118 occurrences with subject type sockg:GrazingManagementEvent and object type xsd:double.

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
| self | sockg:animalClass |
| native | soc-kg/main/:sockg_animalClass |




## LinkML Source

<details>
```yaml
name: sockg_animalClass
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 1833 occurrences with subject type sockg:GrazingManagementEvent and object type
  string.
- 118 occurrences with subject type sockg:GrazingManagementEvent and object type xsd:double.
examples:
- value: neo4j://graph.individuals#171465 sockg:animalClass Neutered male
- value: neo4j://graph.individuals#172634 sockg:animalClass nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:animalClass
alias: sockg_animalClass
domain_of:
- sockg_GrazingManagementEvent
range: Any
any_of:
- range: string
- range: double

```
</details>