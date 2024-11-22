

# Slot: TODO -- tell the world what this slot (predicate) describes. (meegad_parameterName)


_Name of the PFAS parameter (single chemical or aggregate set of chemicals) measured in the EGAD dataset from the state of Maine._





URI: [meegad:parameterName](http://sawgraph.spatialai.org/v1/me-egad#parameterName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoSubstance](../classes/ContaminosoSubstance.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| meegad:parameter.10-2_FTS_A meegad:parameterName 10:2 FLUOROTELOMER SULFONIC ACID |

## Comments

* 93 occurrences with subject type contaminoso_Substance and object type string.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: sawgraph-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | meegad:parameterName |
| native | sawgraph-kg/:meegad_parameterName |




## LinkML Source

<details>
```yaml
name: meegad_parameterName
description: Name of the PFAS parameter (single chemical or aggregate set of chemicals)
  measured in the EGAD dataset from the state of Maine.
title: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 93 occurrences with subject type contaminoso_Substance and object type string.
examples:
- value: meegad:parameter.10-2_FTS_A meegad:parameterName 10:2 FLUOROTELOMER SULFONIC
    ACID
from_schema: sawgraph-kg
rank: 1000
slot_uri: meegad:parameterName
alias: meegad_parameterName
domain_of:
- contaminoso_Substance
range: string

```
</details>