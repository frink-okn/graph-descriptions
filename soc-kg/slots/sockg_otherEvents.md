

# Slot: sockg_otherEvents


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:otherEvents](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/otherEvents)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGrazingManagementEvent](../classes/SockgGrazingManagementEvent.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#171317 sockg:otherEvents nan |
| neo4j://graph.individuals#172156 sockg:otherEvents fertilizer application |

## Comments

* 1947 occurrences with subject type sockg:GrazingManagementEvent and object type xsd:double.
* 4 occurrences with subject type sockg:GrazingManagementEvent and object type string.

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
| self | sockg:otherEvents |
| native | soc-kg/main/:sockg_otherEvents |




## LinkML Source

<details>
```yaml
name: sockg_otherEvents
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 1947 occurrences with subject type sockg:GrazingManagementEvent and object type
  xsd:double.
- 4 occurrences with subject type sockg:GrazingManagementEvent and object type string.
examples:
- value: neo4j://graph.individuals#171317 sockg:otherEvents nan
- value: neo4j://graph.individuals#172156 sockg:otherEvents fertilizer application
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:otherEvents
alias: sockg_otherEvents
domain_of:
- sockg_GrazingManagementEvent
range: Any
any_of:
- range: double
- range: string

```
</details>