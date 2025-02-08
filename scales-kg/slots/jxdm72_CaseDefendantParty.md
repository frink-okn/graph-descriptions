

# Slot: jxdm72_CaseDefendantParty


_No slot (predicate) description specified_





URI: [jxdm72:CaseDefendantParty](http://release.niem.gov/niem/domains/jxdm/7.2/#CaseDefendantParty)



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
| scales_Case → uri | scales/CaseCivil | jxdm72:CaseDefendantParty | scales/Agent/almd;;1:16-cv-00016_a1 |


## Comments

* 1852839 occurrences with subject type scales_Case and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | jxdm72:CaseDefendantParty |
| native | scales-kg-new/:jxdm72_CaseDefendantParty |




## LinkML Source

<details>

```yaml
name: jxdm72_CaseDefendantParty
description: No slot (predicate) description specified
comments:
- 1852839 occurrences with subject type scales_Case and object type uri.
examples:
- description: scales_Case → uri
  object:
    example_object: scales/Agent/almd;;1:16-cv-00016_a1
    example_object_type: uri
    example_predicate: jxdm72:CaseDefendantParty
    example_subject: scales/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg-new
rank: 1000
slot_uri: jxdm72:CaseDefendantParty
alias: jxdm72_CaseDefendantParty
domain_of:
- scales_Case
range: uri

```
</details>