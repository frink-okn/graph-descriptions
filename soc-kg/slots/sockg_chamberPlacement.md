

# Slot: sockg_chamberPlacement


_No slot description provided_





URI: [sockg:chamberPlacement](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/chamberPlacement)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGasSample](../classes/SockgGasSample.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#116000 sockg:chamberPlacement Across rows |
| neo4j://graph.individuals#104909 sockg:chamberPlacement nan |

## Comments

* 103543 occurrences with subject type sockg:GasSample and object type string.
* 3811 occurrences with subject type sockg:GasSample and object type xsd:double.

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
| self | sockg:chamberPlacement |
| native | soc-kg/main/:sockg_chamberPlacement |




## LinkML Source

<details>
```yaml
name: sockg_chamberPlacement
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 103543 occurrences with subject type sockg:GasSample and object type string.
- 3811 occurrences with subject type sockg:GasSample and object type xsd:double.
examples:
- value: neo4j://graph.individuals#116000 sockg:chamberPlacement Across rows
- value: neo4j://graph.individuals#104909 sockg:chamberPlacement nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:chamberPlacement
alias: sockg_chamberPlacement
domain_of:
- sockg_GasSample
range: Any
any_of:
- range: string
- range: double

```
</details>