

# Slot: sockg_worksAtDepartment


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:worksAtDepartment](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/worksAtDepartment)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPerson](../classes/SockgPerson.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [SockgDepartment](../classes/SockgDepartment.md)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#203333 sockg:worksAtDepartment neo4j://graph.individuals#51672 |

## Comments

* 91 occurrences with subject type sockg:Person and object type sockg:Department.

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
| self | sockg:worksAtDepartment |
| native | soc-kg/main/:sockg_worksAtDepartment |




## LinkML Source

<details>
```yaml
name: sockg_worksAtDepartment
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 91 occurrences with subject type sockg:Person and object type sockg:Department.
examples:
- value: neo4j://graph.individuals#203333 sockg:worksAtDepartment neo4j://graph.individuals#51672
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:worksAtDepartment
alias: sockg_worksAtDepartment
domain_of:
- sockg_Person
range: sockg_Department

```
</details>