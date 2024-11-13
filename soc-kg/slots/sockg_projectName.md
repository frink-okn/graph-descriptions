

# Slot: sockg_projectName


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:projectName](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/projectName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgExperiment](../classes/SockgExperiment.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgProject](../classes/SockgProject.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#51735 sockg:projectName NUOnet |
| neo4j://graph.individuals#227188 sockg:projectName NUOnet Alumbre, Ecuador, Phase 1 |

## Comments

* 55 occurrences with subject type sockg:Experiment and object type string.
* 9 occurrences with subject type sockg:Project and object type string.

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
| self | sockg:projectName |
| native | soc-kg/main/:sockg_projectName |




## LinkML Source

<details>
```yaml
name: sockg_projectName
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 55 occurrences with subject type sockg:Experiment and object type string.
- 9 occurrences with subject type sockg:Project and object type string.
examples:
- value: neo4j://graph.individuals#51735 sockg:projectName NUOnet
- value: neo4j://graph.individuals#227188 sockg:projectName NUOnet Alumbre, Ecuador,
    Phase 1
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:projectName
alias: sockg_projectName
domain_of:
- sockg_Experiment
- sockg_Project
range: string

```
</details>