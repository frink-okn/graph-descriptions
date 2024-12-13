

# Slot: rural_substanceabuse_name


_No slot description provided_





URI: [rural:substanceabuse/name](http://sail.ua.edu/ruralkg/substanceabuse/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralSubstanceabuseSubstance](../classes/RuralSubstanceabuseSubstance.md) | Types of substances that can be abused |  no  |
| [RuralSubstanceabuseSubstanceRelatedIncident](../classes/RuralSubstanceabuseSubstanceRelatedIncident.md) | Types of incidents related to substance abuse |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| None |  |  |  |
| None |  |  |  |


## Comments

* 25 occurrences with subject type rural_substanceabuse_Substance and object type string.
* 17 occurrences with subject type rural_substanceabuse_SubstanceRelatedIncident and object type string.

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
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 25 occurrences with subject type rural_substanceabuse_Substance and object type
  string.
- 17 occurrences with subject type rural_substanceabuse_SubstanceRelatedIncident and
  object type string.
examples:
- value: rural:substanceabuse/Substance_16 rural:substanceabuse/name pcp
- value: rural:substanceabuse/SIT_13 rural:substanceabuse/name On Parole
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