

# Slot: niem50_PersonFullName


_No slot (predicate) description specified_





URI: [niem50:PersonFullName](http://release.niem.gov/niem/niem-core/5.0/PersonFullName)



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
| None → string | scales/Agent/almd;;1:16-cr-00020_a2 | niem50:PersonFullName | Honorable Judge Myron H. Thompson |
| jxdm72_Judge → string | scales/JudgeEntity/SJ000000 | niem50:PersonFullName | Cj Williams |


## Comments

* 4973752 occurrences with untyped subjects and object type string.
* 5385 occurrences with subject type jxdm72_Judge and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | niem50:PersonFullName |
| native | scales-kg-new/:niem50_PersonFullName |




## LinkML Source

<details>
```yaml
name: niem50_PersonFullName
description: No slot (predicate) description specified
comments:
- 4973752 occurrences with untyped subjects and object type string.
- 5385 occurrences with subject type jxdm72_Judge and object type string.
examples:
- description: None → string
  object:
    example_object: Honorable Judge Myron H. Thompson
    example_object_type: string
    example_predicate: niem50:PersonFullName
    example_subject: scales/Agent/almd;;1:16-cr-00020_a2
    example_subject_type: None
- description: jxdm72_Judge → string
  object:
    example_object: Cj Williams
    example_object_type: string
    example_predicate: niem50:PersonFullName
    example_subject: scales/JudgeEntity/SJ000000
    example_subject_type: jxdm72_Judge
from_schema: scales-kg-new
rank: 1000
slot_uri: niem50:PersonFullName
alias: niem50_PersonFullName
domain_of:
- jxdm72_Judge
range: string

```
</details>