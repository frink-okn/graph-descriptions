

# Slot: sockg_profession


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:profession](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/profession)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPerson](../classes/SockgPerson.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#203288 sockg:profession Research Leader/Soil Scientist |
| neo4j://graph.individuals#203344 sockg:profession nan |

## Comments

* 93 occurrences with subject type sockg:Person and object type string.
* 5 occurrences with subject type sockg:Person and object type xsd:double.

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
| self | sockg:profession |
| native | soc-kg/main/:sockg_profession |




## LinkML Source

<details>
```yaml
name: sockg_profession
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 93 occurrences with subject type sockg:Person and object type string.
- 5 occurrences with subject type sockg:Person and object type xsd:double.
examples:
- value: neo4j://graph.individuals#203288 sockg:profession Research Leader/Soil Scientist
- value: neo4j://graph.individuals#203344 sockg:profession nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:profession
alias: sockg_profession
domain_of:
- sockg_Person
range: Any
any_of:
- range: string
- range: double

```
</details>