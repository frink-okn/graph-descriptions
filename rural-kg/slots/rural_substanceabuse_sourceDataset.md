

# Slot: rural_substanceabuse_sourceDataset


_No slot description provided_





URI: [rural:substanceabuse/sourceDataset](http://sail.ua.edu/ruralkg/substanceabuse/sourceDataset)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralSubstanceabuseSubstanceRelatedIncident](../classes/RuralSubstanceabuseSubstanceRelatedIncident.md) | Types of incidents related to substance abuse |  no  |
| [RuralSubstanceabuseSubstance](../classes/RuralSubstanceabuseSubstance.md) | Types of substances that can be abused |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| rural:substanceabuse/SIT_4 rural:substanceabuse/sourceDataset NSDUH |
| rural:substanceabuse/Substance_2 rural:substanceabuse/sourceDataset NSDUH |

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
| self | rural:substanceabuse/sourceDataset |
| native | rural-kg/:rural_substanceabuse_sourceDataset |




## LinkML Source

<details>
```yaml
name: rural_substanceabuse_sourceDataset
description: No slot description provided
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
- value: rural:substanceabuse/SIT_4 rural:substanceabuse/sourceDataset NSDUH
- value: rural:substanceabuse/Substance_2 rural:substanceabuse/sourceDataset NSDUH
from_schema: rural-kg
rank: 1000
slot_uri: rural:substanceabuse/sourceDataset
alias: rural_substanceabuse_sourceDataset
domain_of:
- rural_substanceabuse_Substance
- rural_substanceabuse_SubstanceRelatedIncident
range: string

```
</details>