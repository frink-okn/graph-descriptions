

# Slot: niem50_PersonRaceText


_No slot (predicate) description specified_





URI: [niem50:PersonRaceText](http://release.niem.gov/niem/niem-core/5.0/PersonRaceText)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Jxdm72Judge](../classes/Jxdm72Judge.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| jxdm72_Judge → string | scales/JudgeEntity/SJ000004 | niem50:PersonRaceText | White |


## Comments

* 3762 occurrences with subject type jxdm72_Judge and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | niem50:PersonRaceText |
| native | scales-kg-new/:niem50_PersonRaceText |




## LinkML Source

<details>

```yaml
name: niem50_PersonRaceText
description: No slot (predicate) description specified
comments:
- 3762 occurrences with subject type jxdm72_Judge and object type string.
examples:
- description: jxdm72_Judge → string
  object:
    example_object: White
    example_object_type: string
    example_predicate: niem50:PersonRaceText
    example_subject: scales/JudgeEntity/SJ000004
    example_subject_type: jxdm72_Judge
from_schema: scales-kg-new
rank: 1000
slot_uri: niem50:PersonRaceText
alias: niem50_PersonRaceText
domain_of:
- jxdm72_Judge
range: string

```
</details>