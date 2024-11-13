

# Slot: sockg_amendmentPlacement


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:amendmentPlacement](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/amendmentPlacement)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgAmendment](../classes/SockgAmendment.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#13919 sockg:amendmentPlacement Broadcast Surface |
| neo4j://graph.individuals#23486 sockg:amendmentPlacement nan |

## Comments

* 22264 occurrences with subject type sockg:Amendment and object type string.
* 15532 occurrences with subject type sockg:Amendment and object type xsd:double.

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
| self | sockg:amendmentPlacement |
| native | soc-kg/main/:sockg_amendmentPlacement |




## LinkML Source

<details>
```yaml
name: sockg_amendmentPlacement
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 22264 occurrences with subject type sockg:Amendment and object type string.
- 15532 occurrences with subject type sockg:Amendment and object type xsd:double.
examples:
- value: neo4j://graph.individuals#13919 sockg:amendmentPlacement Broadcast Surface
- value: neo4j://graph.individuals#23486 sockg:amendmentPlacement nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:amendmentPlacement
alias: sockg_amendmentPlacement
domain_of:
- sockg_Amendment
range: Any
any_of:
- range: string
- range: double

```
</details>