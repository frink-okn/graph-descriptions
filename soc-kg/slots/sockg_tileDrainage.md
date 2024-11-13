

# Slot: sockg_tileDrainage


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:tileDrainage](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/tileDrainage)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgTreatment](../classes/SockgTreatment.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#359754 sockg:tileDrainage nan |
| neo4j://graph.individuals#359184 sockg:tileDrainage No |

## Comments

* 331 occurrences with subject type sockg:Treatment and object type xsd:double.
* 438 occurrences with subject type sockg:Treatment and object type string.

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
| self | sockg:tileDrainage |
| native | soc-kg/main/:sockg_tileDrainage |




## LinkML Source

<details>
```yaml
name: sockg_tileDrainage
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 331 occurrences with subject type sockg:Treatment and object type xsd:double.
- 438 occurrences with subject type sockg:Treatment and object type string.
examples:
- value: neo4j://graph.individuals#359754 sockg:tileDrainage nan
- value: neo4j://graph.individuals#359184 sockg:tileDrainage No
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:tileDrainage
alias: sockg_tileDrainage
domain_of:
- sockg_Treatment
range: Any
any_of:
- range: double
- range: string

```
</details>