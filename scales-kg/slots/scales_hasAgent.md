

# Slot: scales_hasAgent


_TODO -- tell the world what this slot (predicate) describes._





URI: [scales:hasAgent](http://schemas.scales-okn.org/rdf/scales#hasAgent)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCaseCriminal](../classes/ScalesCaseCriminal.md) | TODO -- tell the world what this class (type) describes |  no  |
| [ScalesCaseCivil](../classes/ScalesCaseCivil.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [ScalesAgent](../classes/ScalesAgent.md)






## Examples

| Value |
| --- |
| scales:CaseCivil/wyd;;2:17-cv-00211 scales:hasAgent scales:Agent/wyd;;2:17-cv-00211_a9 |
| scales:CaseCriminal/wyd;;6:17-cr-00033 scales:hasAgent scales:Agent/wyd;;6:17-cr-00033_a5 |

## Comments

* 9582250 occurrences with subject type scales_CaseCivil and object type scales_Agent.
* 1437899 occurrences with subject type scales_CaseCriminal and object type scales_Agent.

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
| self | scales:hasAgent |
| native | scales-kg/:scales_hasAgent |




## LinkML Source

<details>
```yaml
name: scales_hasAgent
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 9582250 occurrences with subject type scales_CaseCivil and object type scales_Agent.
- 1437899 occurrences with subject type scales_CaseCriminal and object type scales_Agent.
examples:
- value: scales:CaseCivil/wyd;;2:17-cv-00211 scales:hasAgent scales:Agent/wyd;;2:17-cv-00211_a9
- value: scales:CaseCriminal/wyd;;6:17-cr-00033 scales:hasAgent scales:Agent/wyd;;6:17-cr-00033_a5
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasAgent
alias: scales_hasAgent
domain_of:
- scales_CaseCivil
- scales_CaseCriminal
range: scales_Agent

```
</details>