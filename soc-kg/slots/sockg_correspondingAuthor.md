

# Slot: sockg_correspondingAuthor


_No slot description provided_





URI: [sockg:correspondingAuthor](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/correspondingAuthor)



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
| neo4j://graph.individuals#227203 sockg:correspondingAuthor Jin, Virginia L. |
| neo4j://graph.individuals#227205 sockg:correspondingAuthor nan |

## Comments

* 105 occurrences with subject type sockg:Publication and object type string.
* 9 occurrences with subject type sockg:Publication and object type xsd:double.

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
| self | sockg:correspondingAuthor |
| native | soc-kg/main/:sockg_correspondingAuthor |




## LinkML Source

<details>
```yaml
name: sockg_correspondingAuthor
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 105 occurrences with subject type sockg:Publication and object type string.
- 9 occurrences with subject type sockg:Publication and object type xsd:double.
examples:
- value: neo4j://graph.individuals#227203 sockg:correspondingAuthor Jin, Virginia
    L.
- value: neo4j://graph.individuals#227205 sockg:correspondingAuthor nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:correspondingAuthor
alias: sockg_correspondingAuthor
domain_of:
- sockg_Publication
range: Any
any_of:
- range: string
- range: double

```
</details>