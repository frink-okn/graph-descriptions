

# Slot: sockg_identifier


_No slot description provided_





URI: [sockg:identifier](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPublication](../classes/SockgPublication.md) | No type description provided |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#227247 sockg:identifier doi:10.2134/jeq2012.0129 |

## Comments

* 114 occurrences with subject type sockg:Publication and object type string.

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
| self | sockg:identifier |
| native | soc-kg/main/:sockg_identifier |




## LinkML Source

<details>
```yaml
name: sockg_identifier
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 114 occurrences with subject type sockg:Publication and object type string.
examples:
- value: neo4j://graph.individuals#227247 sockg:identifier doi:10.2134/jeq2012.0129
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:identifier
alias: sockg_identifier
domain_of:
- sockg_Publication
range: string

```
</details>