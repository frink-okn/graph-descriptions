

# Slot: scales_hasAddress


_No slot description provided_





URI: [scales:hasAddress](http://schemas.scales-okn.org/rdf/scales#hasAddress)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesAgent](../classes/ScalesAgent.md) | No type description provided |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| scales:Agent/akd;;1:16-cr-00001_a3 scales:hasAddress 425 G Street, Suite 800
Anchorage, AK 99501 |

## Comments

* 2319706 occurrences with subject type scales_Agent and object type string.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | scales:hasAddress |
| native | scales-kg/:scales_hasAddress |




## LinkML Source

<details>
```yaml
name: scales_hasAddress
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 2319706 occurrences with subject type scales_Agent and object type string.
examples:
- value: 'scales:Agent/akd;;1:16-cr-00001_a3 scales:hasAddress 425 G Street, Suite
    800

    Anchorage, AK 99501'
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasAddress
alias: scales_hasAddress
domain_of:
- scales_Agent
range: string

```
</details>