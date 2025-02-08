

# Slot: jxdm72_CaseJudge


_No slot (predicate) description specified_





URI: [jxdm72:CaseJudge](http://release.niem.gov/niem/domains/jxdm/7.2/#CaseJudge)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:anyURI](xsd:anyURI)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| scales_Case → uri | scales/CaseCivil | jxdm72:CaseJudge | scales/Agent/almd;;1:16-cv-00016_a4 |


## Comments

* 837266 occurrences with subject type scales_Case and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | jxdm72:CaseJudge |
| native | scales-kg-new/:jxdm72_CaseJudge |




## LinkML Source

<details>
```yaml
name: jxdm72_CaseJudge
description: No slot (predicate) description specified
comments:
- 837266 occurrences with subject type scales_Case and object type uri.
examples:
- description: scales_Case → uri
  object:
    example_object: scales/Agent/almd;;1:16-cv-00016_a4
    example_object_type: uri
    example_predicate: jxdm72:CaseJudge
    example_subject: scales/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg-new
rank: 1000
slot_uri: jxdm72:CaseJudge
alias: jxdm72_CaseJudge
domain_of:
- scales_Case
range: uri

```
</details>