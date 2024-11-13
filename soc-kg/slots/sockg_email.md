

# Slot: sockg_email


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:email](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/email)



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
| neo4j://graph.individuals#203351 sockg:email wayne.polumsky@ars.usda.gov |
| neo4j://graph.individuals#203284 sockg:email nan |

## Comments

* 86 occurrences with subject type sockg:Person and object type string.
* 12 occurrences with subject type sockg:Person and object type xsd:double.

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
| self | sockg:email |
| native | soc-kg/main/:sockg_email |




## LinkML Source

<details>
```yaml
name: sockg_email
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 86 occurrences with subject type sockg:Person and object type string.
- 12 occurrences with subject type sockg:Person and object type xsd:double.
examples:
- value: neo4j://graph.individuals#203351 sockg:email wayne.polumsky@ars.usda.gov
- value: neo4j://graph.individuals#203284 sockg:email nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:email
alias: sockg_email
domain_of:
- sockg_Person
range: Any
any_of:
- range: string
- range: double

```
</details>