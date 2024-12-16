

# Slot: rural_substanceabuse_name


_No slot (predicate) description specified_





URI: [rural:substanceabuse/name](http://sail.ua.edu/ruralkg/substanceabuse/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralSubstanceabuseSubstance](../classes/RuralSubstanceabuseSubstance.md) | No class (type) description specified |  no  |
| [RuralSubstanceabuseSubstanceRelatedIncident](../classes/RuralSubstanceabuseSubstanceRelatedIncident.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rural_substanceabuse_SubstanceRelatedIncident → string | rural:substanceabuse/SIT_1 | rural:substanceabuse/name | Drive Under Influence |
| rural_substanceabuse_Substance → string | rural:substanceabuse/Substance_1 | rural:substanceabuse/name | nicotine |


## Comments

* 17 occurrences with subject type rural_substanceabuse_SubstanceRelatedIncident and object type string.
* 25 occurrences with subject type rural_substanceabuse_Substance and object type string.

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
description: No slot (predicate) description specified
comments:
- 17 occurrences with subject type rural_substanceabuse_SubstanceRelatedIncident and
  object type string.
- 25 occurrences with subject type rural_substanceabuse_Substance and object type
  string.
examples:
- description: rural_substanceabuse_SubstanceRelatedIncident → string
  object:
    example_object: Drive Under Influence
    example_predicate: rural:substanceabuse/name
    example_subject: rural:substanceabuse/SIT_1
- description: rural_substanceabuse_Substance → string
  object:
    example_object: nicotine
    example_predicate: rural:substanceabuse/name
    example_subject: rural:substanceabuse/Substance_1
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