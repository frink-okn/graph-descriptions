

# Slot: sockg_note


_No slot description provided_





URI: [sockg:note](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/note)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPerson](../classes/SockgPerson.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#203375 sockg:note nan |
| neo4j://graph.individuals#203328 sockg:note Dr. Cantrell no longer works for ARS at this time. |

## Comments

* 86 occurrences with subject type sockg:Person and object type xsd:double.
* 12 occurrences with subject type sockg:Person and object type string.

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
| self | sockg:note |
| native | soc-kg/main/:sockg_note |




## LinkML Source

<details>
```yaml
name: sockg_note
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 86 occurrences with subject type sockg:Person and object type xsd:double.
- 12 occurrences with subject type sockg:Person and object type string.
examples:
- value: neo4j://graph.individuals#203375 sockg:note nan
- value: neo4j://graph.individuals#203328 sockg:note Dr. Cantrell no longer works
    for ARS at this time.
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:note
alias: sockg_note
domain_of:
- sockg_Person
range: Any
any_of:
- range: double
- range: string

```
</details>