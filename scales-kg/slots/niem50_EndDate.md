

# Slot: niem50_EndDate


_No slot (predicate) description specified_





URI: [niem50:EndDate](http://release.niem.gov/niem/niem-core/5.0/EndDate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:date](xsd:date)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| scales_Case → date | scales/CaseCivil | niem50:EndDate | 1968-03-14 |


## Comments

* 9629 occurrences with subject type scales_Case and object type date.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | niem50:EndDate |
| native | scales-kg-new/:niem50_EndDate |




## LinkML Source

<details>

```yaml
name: niem50_EndDate
description: No slot (predicate) description specified
comments:
- 9629 occurrences with subject type scales_Case and object type date.
examples:
- description: scales_Case → date
  object:
    example_object: '1968-03-14'
    example_object_type: date
    example_predicate: niem50:EndDate
    example_subject: scales/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg-new
rank: 1000
slot_uri: niem50:EndDate
alias: niem50_EndDate
domain_of:
- scales_Case
range: date

```
</details>