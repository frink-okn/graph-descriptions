

# Slot: sockg_type


_No slot description provided_





URI: [sockg:type](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/type)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgAmendment](../classes/SockgAmendment.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#22483 sockg:type Ammonium Sulfate |
| neo4j://graph.individuals#18536 sockg:type nan |

## Comments

* 22884 occurrences with subject type sockg:Amendment and object type string.
* 14912 occurrences with subject type sockg:Amendment and object type xsd:double.

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
| self | sockg:type |
| native | soc-kg/main/:sockg_type |




## LinkML Source

<details>
```yaml
name: sockg_type
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 22884 occurrences with subject type sockg:Amendment and object type string.
- 14912 occurrences with subject type sockg:Amendment and object type xsd:double.
examples:
- value: neo4j://graph.individuals#22483 sockg:type Ammonium Sulfate
- value: neo4j://graph.individuals#18536 sockg:type nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:type
alias: sockg_type
domain_of:
- sockg_Amendment
range: Any
any_of:
- range: string
- range: double

```
</details>