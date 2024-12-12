

# Slot: sockg_irrigationType


_No slot description provided_





URI: [sockg:irrigationType](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/irrigationType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgAmendment](../classes/SockgAmendment.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#16031 sockg:irrigationType nan |
| neo4j://graph.individuals#19703 sockg:irrigationType Linear Move Sprinkler |

## Comments

* 33571 occurrences with subject type sockg:Amendment and object type xsd:double.
* 4225 occurrences with subject type sockg:Amendment and object type string.

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
| self | sockg:irrigationType |
| native | soc-kg/main/:sockg_irrigationType |




## LinkML Source

<details>
```yaml
name: sockg_irrigationType
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 33571 occurrences with subject type sockg:Amendment and object type xsd:double.
- 4225 occurrences with subject type sockg:Amendment and object type string.
examples:
- value: neo4j://graph.individuals#16031 sockg:irrigationType nan
- value: neo4j://graph.individuals#19703 sockg:irrigationType Linear Move Sprinkler
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:irrigationType
alias: sockg_irrigationType
domain_of:
- sockg_Amendment
range: Any
any_of:
- range: double
- range: string

```
</details>