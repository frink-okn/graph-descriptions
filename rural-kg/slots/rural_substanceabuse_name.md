

# Slot: rural_substanceabuse_name


_TODO -- tell the world what this slot (predicate) describes._





URI: [rural:substanceabuse/name](http://sail.ua.edu/ruralkg/substanceabuse/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralSubstanceabuseSubstanceRelatedIncident](../classes/RuralSubstanceabuseSubstanceRelatedIncident.md) | TODO -- tell the world what this class (type) describes |  no  |
| [RuralSubstanceabuseSubstance](../classes/RuralSubstanceabuseSubstance.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| rural:substanceabuse/SIT_10 rural:substanceabuse/name Used an Illicit Drug |
| rural:substanceabuse/Substance_12 rural:substanceabuse/name tranquilizer |

## Comments

* 17 occurrences with subject type rural_substanceabuse_SubstanceRelatedIncident and object type string.
* 25 occurrences with subject type rural_substanceabuse_Substance and object type string.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:substanceabuse/name |
| native | rural-kg/:rural_substanceabuse_name |




## LinkML Source

<details>
```yaml
name: rural_substanceabuse_name
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 17 occurrences with subject type rural_substanceabuse_SubstanceRelatedIncident and
  object type string.
- 25 occurrences with subject type rural_substanceabuse_Substance and object type
  string.
examples:
- value: rural:substanceabuse/SIT_10 rural:substanceabuse/name Used an Illicit Drug
- value: rural:substanceabuse/Substance_12 rural:substanceabuse/name tranquilizer
from_schema: rural-kg
rank: 1000
slot_uri: rural:substanceabuse/name
alias: rural_substanceabuse_name
domain_of:
- rural_substanceabuse_Substance
- rural_substanceabuse_SubstanceRelatedIncident
range: string

```
</details>