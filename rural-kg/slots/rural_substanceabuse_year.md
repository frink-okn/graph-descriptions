

# Slot: rural_substanceabuse_year


_No slot (predicate) description specified_





URI: [rural:substanceabuse/year](http://sail.ua.edu/ruralkg/substanceabuse/year)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralSubstanceabuseSubstance](../classes/RuralSubstanceabuseSubstance.md) | No class (type) description specified |  no  |
| [RuralSubstanceabuseSubstanceRelatedIncident](../classes/RuralSubstanceabuseSubstanceRelatedIncident.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:integer](xsd:integer)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rural_substanceabuse_SubstanceRelatedIncident → integer | rural:substanceabuse/SIT_1 | rural:substanceabuse/year | 2022 |
| rural_substanceabuse_Substance → integer | rural:substanceabuse/Substance_1 | rural:substanceabuse/year | 2022 |


## Comments

* 17 occurrences with subject type rural_substanceabuse_SubstanceRelatedIncident and object type integer.
* 25 occurrences with subject type rural_substanceabuse_Substance and object type integer.

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
description: No slot (predicate) description specified
comments:
- 17 occurrences with subject type rural_substanceabuse_SubstanceRelatedIncident and
  object type integer.
- 25 occurrences with subject type rural_substanceabuse_Substance and object type
  integer.
examples:
- description: rural_substanceabuse_SubstanceRelatedIncident → integer
  object:
    example_object: '2022'
    example_predicate: rural:substanceabuse/year
    example_subject: rural:substanceabuse/SIT_1
- description: rural_substanceabuse_Substance → integer
  object:
    example_object: '2022'
    example_predicate: rural:substanceabuse/year
    example_subject: rural:substanceabuse/Substance_1
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