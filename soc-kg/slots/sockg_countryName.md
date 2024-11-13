

# Slot: sockg_countryName


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:countryName](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/countryName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgCountry](../classes/SockgCountry.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#46721 sockg:countryName United States |

## Comments

* 3 occurrences with subject type sockg:Country and object type string.

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
| self | sockg:countryName |
| native | soc-kg/main/:sockg_countryName |




## LinkML Source

<details>
```yaml
name: sockg_countryName
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 3 occurrences with subject type sockg:Country and object type string.
examples:
- value: neo4j://graph.individuals#46721 sockg:countryName United States
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:countryName
alias: sockg_countryName
domain_of:
- sockg_Country
range: string

```
</details>