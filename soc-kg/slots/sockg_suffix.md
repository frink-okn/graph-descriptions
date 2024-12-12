

# Slot: sockg_suffix


_No slot description provided_





URI: [sockg:suffix](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/suffix)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPerson](../classes/SockgPerson.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#203302 sockg:suffix PhD |
| neo4j://graph.individuals#203309 sockg:suffix nan |

## Comments

* 32 occurrences with subject type sockg:Person and object type string.
* 66 occurrences with subject type sockg:Person and object type xsd:double.

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
| self | sockg:suffix |
| native | soc-kg/main/:sockg_suffix |




## LinkML Source

<details>
```yaml
name: sockg_suffix
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 32 occurrences with subject type sockg:Person and object type string.
- 66 occurrences with subject type sockg:Person and object type xsd:double.
examples:
- value: neo4j://graph.individuals#203302 sockg:suffix PhD
- value: neo4j://graph.individuals#203309 sockg:suffix nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:suffix
alias: sockg_suffix
domain_of:
- sockg_Person
range: Any
any_of:
- range: string
- range: double

```
</details>