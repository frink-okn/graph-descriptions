

# Slot: sockg_title


_No slot description provided_





URI: [sockg:title](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/title)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPublication](../classes/SockgPublication.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#227249 sockg:title Greenhouse gas emission from contrasting management scenarios in the northern Corn Belt. |
| neo4j://graph.individuals#227199 sockg:title nan |

## Comments

* 107 occurrences with subject type sockg:Publication and object type string.
* 7 occurrences with subject type sockg:Publication and object type xsd:double.

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
| self | sockg:title |
| native | soc-kg/main/:sockg_title |




## LinkML Source

<details>
```yaml
name: sockg_title
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 107 occurrences with subject type sockg:Publication and object type string.
- 7 occurrences with subject type sockg:Publication and object type xsd:double.
examples:
- value: neo4j://graph.individuals#227249 sockg:title Greenhouse gas emission from
    contrasting management scenarios in the northern Corn Belt.
- value: neo4j://graph.individuals#227199 sockg:title nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:title
alias: sockg_title
domain_of:
- sockg_Publication
range: Any
any_of:
- range: string
- range: double

```
</details>