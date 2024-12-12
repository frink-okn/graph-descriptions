

# Slot: sockg_pesticideActiveIngredientType


_No slot description provided_





URI: [sockg:pesticideActiveIngredientType](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/pesticideActiveIngredientType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPesticide](../classes/SockgPesticide.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#203409 sockg:pesticideActiveIngredientType Sethoxydim; CAS No. 74051-80-2 |
| neo4j://graph.individuals#203707 sockg:pesticideActiveIngredientType nan |

## Comments

* 353 occurrences with subject type sockg:Pesticide and object type string.
* 3 occurrences with subject type sockg:Pesticide and object type xsd:double.

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
| self | sockg:pesticideActiveIngredientType |
| native | soc-kg/main/:sockg_pesticideActiveIngredientType |




## LinkML Source

<details>
```yaml
name: sockg_pesticideActiveIngredientType
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 353 occurrences with subject type sockg:Pesticide and object type string.
- 3 occurrences with subject type sockg:Pesticide and object type xsd:double.
examples:
- value: neo4j://graph.individuals#203409 sockg:pesticideActiveIngredientType Sethoxydim;
    CAS No. 74051-80-2
- value: neo4j://graph.individuals#203707 sockg:pesticideActiveIngredientType nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:pesticideActiveIngredientType
alias: sockg_pesticideActiveIngredientType
domain_of:
- sockg_Pesticide
range: Any
any_of:
- range: string
- range: double

```
</details>