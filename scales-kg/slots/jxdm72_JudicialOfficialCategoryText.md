

# Slot: jxdm72_JudicialOfficialCategoryText


_No slot (predicate) description specified_





URI: [jxdm72:JudicialOfficialCategoryText](http://release.niem.gov/niem/domains/jxdm/7.2/#JudicialOfficialCategoryText)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Jxdm72Judge](../classes/Jxdm72Judge.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| jxdm72_Judge → string | scales/JudgeEntity/SJ000000 | jxdm72:JudicialOfficialCategoryText | Magistrate_Judge |
| None → string | http://schemas.scales-okn.org/rdf/ijp#JudgeEntity/SJ000000 | jxdm72:JudicialOfficialCategoryText | Magistrate_Judge |


## Comments

* 5385 occurrences with subject type jxdm72_Judge and object type string.
* 5385 occurrences with untyped subjects and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | jxdm72:JudicialOfficialCategoryText |
| native | scales-kg-new/:jxdm72_JudicialOfficialCategoryText |




## LinkML Source

<details>

```yaml
name: jxdm72_JudicialOfficialCategoryText
description: No slot (predicate) description specified
comments:
- 5385 occurrences with subject type jxdm72_Judge and object type string.
- 5385 occurrences with untyped subjects and object type string.
examples:
- description: jxdm72_Judge → string
  object:
    example_object: Magistrate_Judge
    example_object_type: string
    example_predicate: jxdm72:JudicialOfficialCategoryText
    example_subject: scales/JudgeEntity/SJ000000
    example_subject_type: jxdm72_Judge
- description: None → string
  object:
    example_object: Magistrate_Judge
    example_object_type: string
    example_predicate: jxdm72:JudicialOfficialCategoryText
    example_subject: http://schemas.scales-okn.org/rdf/ijp#JudgeEntity/SJ000000
    example_subject_type: None
from_schema: scales-kg-new
rank: 1000
slot_uri: jxdm72:JudicialOfficialCategoryText
alias: jxdm72_JudicialOfficialCategoryText
domain_of:
- jxdm72_Judge
range: string

```
</details>