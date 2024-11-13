

# Slot: sockg_equipmentType


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:equipmentType](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/equipmentType)



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
| neo4j://graph.individuals#230492 sockg:equipmentType diaper |
| neo4j://graph.individuals#228275 sockg:equipmentType nan |

## Comments

* 3044 occurrences with subject type sockg:ResidueManagementEvent and object type string.
* 264 occurrences with subject type sockg:ResidueManagementEvent and object type xsd:double.

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
| self | sockg:equipmentType |
| native | soc-kg/main/:sockg_equipmentType |




## LinkML Source

<details>
```yaml
name: sockg_equipmentType
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 3044 occurrences with subject type sockg:ResidueManagementEvent and object type
  string.
- 264 occurrences with subject type sockg:ResidueManagementEvent and object type xsd:double.
examples:
- value: neo4j://graph.individuals#230492 sockg:equipmentType diaper
- value: neo4j://graph.individuals#228275 sockg:equipmentType nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:equipmentType
alias: sockg_equipmentType
domain_of:
- sockg_ResidueManagementEvent
range: Any
any_of:
- range: string
- range: double

```
</details>