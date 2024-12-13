

# Slot: rural_substanceabuse_year


_No slot description provided_





URI: [rural:substanceabuse/year](http://sail.ua.edu/ruralkg/substanceabuse/year)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralSubstanceabuseSubstance](../classes/RuralSubstanceabuseSubstance.md) | Types of substances that can be abused |  no  |
| [RuralSubstanceabuseSubstanceRelatedIncident](../classes/RuralSubstanceabuseSubstanceRelatedIncident.md) | Types of incidents related to substance abuse |  no  |







## Properties

* Range: [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| None |  |  |  |
| None |  |  |  |


## Comments

* 25 occurrences with subject type rural_substanceabuse_Substance and object type integer.
* 17 occurrences with subject type rural_substanceabuse_SubstanceRelatedIncident and object type integer.

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
| self | rural:substanceabuse/year |
| native | rural-kg/:rural_substanceabuse_year |




## LinkML Source

<details>
```yaml
name: rural_substanceabuse_year
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 25 occurrences with subject type rural_substanceabuse_Substance and object type
  integer.
- 17 occurrences with subject type rural_substanceabuse_SubstanceRelatedIncident and
  object type integer.
examples:
- value: rural:substanceabuse/Substance_13 rural:substanceabuse/year 2022
- value: rural:substanceabuse/SIT_4 rural:substanceabuse/year 2022
from_schema: rural-kg
rank: 1000
slot_uri: rural:substanceabuse/year
alias: rural_substanceabuse_year
domain_of:
- rural_substanceabuse_Substance
- rural_substanceabuse_SubstanceRelatedIncident
range: integer

```
</details>