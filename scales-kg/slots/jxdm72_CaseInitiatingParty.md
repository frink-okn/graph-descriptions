

# Slot: jxdm72_CaseInitiatingParty


_No slot (predicate) description specified_





URI: [jxdm72:CaseInitiatingParty](http://release.niem.gov/niem/domains/jxdm/7.2/#CaseInitiatingParty)



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
| scales_Case → uri | scales/CaseCivil | jxdm72:CaseInitiatingParty | scales/Agent/almd;;1:16-cv-00016_a0 |


## Comments

* 920509 occurrences with subject type scales_Case and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | jxdm72:CaseInitiatingParty |
| native | scales-kg-new/:jxdm72_CaseInitiatingParty |




## LinkML Source

<details>

```yaml
name: jxdm72_CaseInitiatingParty
description: No slot (predicate) description specified
comments:
- 920509 occurrences with subject type scales_Case and object type uri.
examples:
- description: scales_Case → uri
  object:
    example_object: scales/Agent/almd;;1:16-cv-00016_a0
    example_object_type: uri
    example_predicate: jxdm72:CaseInitiatingParty
    example_subject: scales/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg-new
rank: 1000
slot_uri: jxdm72:CaseInitiatingParty
alias: jxdm72_CaseInitiatingParty
domain_of:
- scales_Case
range: uri

```
</details>