

# Slot: sockg_firstName


_No slot description provided_





URI: [sockg:firstName](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/firstName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPerson](../classes/SockgPerson.md) | No type description provided |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#203296 sockg:firstName Michael |

## Comments

* 98 occurrences with subject type sockg:Person and object type string.

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
| self | sockg:firstName |
| native | soc-kg/main/:sockg_firstName |




## LinkML Source

<details>
```yaml
name: sockg_firstName
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 98 occurrences with subject type sockg:Person and object type string.
examples:
- value: neo4j://graph.individuals#203296 sockg:firstName Michael
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:firstName
alias: sockg_firstName
domain_of:
- sockg_Person
range: string

```
</details>