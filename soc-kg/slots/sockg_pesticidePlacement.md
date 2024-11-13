

# Slot: sockg_pesticidePlacement


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:pesticidePlacement](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/pesticidePlacement)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPesticide](../classes/SockgPesticide.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#203406 sockg:pesticidePlacement nan |
| neo4j://graph.individuals#203699 sockg:pesticidePlacement Tractor mounted spray boom |

## Comments

* 126 occurrences with subject type sockg:Pesticide and object type xsd:double.
* 230 occurrences with subject type sockg:Pesticide and object type string.

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
| self | sockg:pesticidePlacement |
| native | soc-kg/main/:sockg_pesticidePlacement |




## LinkML Source

<details>
```yaml
name: sockg_pesticidePlacement
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 126 occurrences with subject type sockg:Pesticide and object type xsd:double.
- 230 occurrences with subject type sockg:Pesticide and object type string.
examples:
- value: neo4j://graph.individuals#203406 sockg:pesticidePlacement nan
- value: neo4j://graph.individuals#203699 sockg:pesticidePlacement Tractor mounted
    spray boom
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:pesticidePlacement
alias: sockg_pesticidePlacement
domain_of:
- sockg_Pesticide
range: Any
any_of:
- range: double
- range: string

```
</details>