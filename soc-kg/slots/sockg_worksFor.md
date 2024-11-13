

# Slot: sockg_worksFor


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:worksFor](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/worksFor)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPerson](../classes/SockgPerson.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [SockgOrganization](../classes/SockgOrganization.md)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#203294 sockg:worksFor neo4j://graph.individuals#203272 |

## Comments

* 35 occurrences with subject type sockg:Person and object type sockg:Organization.

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
| self | sockg:worksFor |
| native | soc-kg/main/:sockg_worksFor |




## LinkML Source

<details>
```yaml
name: sockg_worksFor
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 35 occurrences with subject type sockg:Person and object type sockg:Organization.
examples:
- value: neo4j://graph.individuals#203294 sockg:worksFor neo4j://graph.individuals#203272
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:worksFor
alias: sockg_worksFor
domain_of:
- sockg_Person
range: sockg_Organization

```
</details>