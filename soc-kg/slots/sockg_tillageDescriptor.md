

# Slot: sockg_tillageDescriptor


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:tillageDescriptor](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/tillageDescriptor)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgTreatment](../classes/SockgTreatment.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#359547 sockg:tillageDescriptor Strip Till |
| neo4j://graph.individuals#359460 sockg:tillageDescriptor nan |

## Comments

* 719 occurrences with subject type sockg:Treatment and object type string.
* 50 occurrences with subject type sockg:Treatment and object type xsd:double.

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
| self | sockg:tillageDescriptor |
| native | soc-kg/main/:sockg_tillageDescriptor |




## LinkML Source

<details>
```yaml
name: sockg_tillageDescriptor
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 719 occurrences with subject type sockg:Treatment and object type string.
- 50 occurrences with subject type sockg:Treatment and object type xsd:double.
examples:
- value: neo4j://graph.individuals#359547 sockg:tillageDescriptor Strip Till
- value: neo4j://graph.individuals#359460 sockg:tillageDescriptor nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:tillageDescriptor
alias: sockg_tillageDescriptor
domain_of:
- sockg_Treatment
range: Any
any_of:
- range: string
- range: double

```
</details>