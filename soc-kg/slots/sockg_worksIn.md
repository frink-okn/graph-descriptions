

# Slot: sockg_worksIn


_No slot description provided_





URI: [sockg:worksIn](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/worksIn)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPerson](../classes/SockgPerson.md) | No type description provided |  no  |







## Properties

* Range: [SockgSite](../classes/SockgSite.md)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#203313 sockg:worksIn neo4j://graph.individuals#230713 |

## Comments

* 165 occurrences with subject type sockg:Person and object type sockg:Site.

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
| self | sockg:worksIn |
| native | soc-kg/main/:sockg_worksIn |




## LinkML Source

<details>
```yaml
name: sockg_worksIn
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 165 occurrences with subject type sockg:Person and object type sockg:Site.
examples:
- value: neo4j://graph.individuals#203313 sockg:worksIn neo4j://graph.individuals#230713
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:worksIn
alias: sockg_worksIn
domain_of:
- sockg_Person
range: sockg_Site

```
</details>