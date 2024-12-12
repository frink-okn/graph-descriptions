

# Slot: sockg_phoneNumber


_No slot description provided_





URI: [sockg:phoneNumber](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/phoneNumber)



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
| neo4j://graph.individuals#203304 sockg:phoneNumber nan |
| neo4j://graph.individuals#203340 sockg:phoneNumber 806-749-5560x5233 |

## Comments

* 15 occurrences with subject type sockg:Person and object type xsd:double.
* 83 occurrences with subject type sockg:Person and object type string.

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
| self | sockg:phoneNumber |
| native | soc-kg/main/:sockg_phoneNumber |




## LinkML Source

<details>
```yaml
name: sockg_phoneNumber
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 15 occurrences with subject type sockg:Person and object type xsd:double.
- 83 occurrences with subject type sockg:Person and object type string.
examples:
- value: neo4j://graph.individuals#203304 sockg:phoneNumber nan
- value: neo4j://graph.individuals#203340 sockg:phoneNumber 806-749-5560x5233
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:phoneNumber
alias: sockg_phoneNumber
domain_of:
- sockg_Person
range: Any
any_of:
- range: double
- range: string

```
</details>