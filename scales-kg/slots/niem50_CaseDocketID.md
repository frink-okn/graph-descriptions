

# Slot: niem50_CaseDocketID


_No slot (predicate) description specified_





URI: [niem50:CaseDocketID](http://release.niem.gov/niem/niem-core/5.0/CaseDocketID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Jxdm72Case](../classes/Jxdm72Case.md) | No class (type) description specified |  no  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| scales_Case → string | scales/CaseCivil | niem50:CaseDocketID | 0:15-cv-04235 |
| jxdm72_Case → integer | scales/CaseCriminal/ga/fulton/01/100271 | niem50:CaseDocketID | 100271 |


## Comments

* 272547 occurrences with subject type scales_Case and object type string.
* 96011 occurrences with subject type jxdm72_Case and object type integer.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | niem50:CaseDocketID |
| native | scales-kg-new/:niem50_CaseDocketID |




## LinkML Source

<details>

```yaml
name: niem50_CaseDocketID
description: No slot (predicate) description specified
comments:
- 272547 occurrences with subject type scales_Case and object type string.
- 96011 occurrences with subject type jxdm72_Case and object type integer.
examples:
- description: scales_Case → string
  object:
    example_object: 0:15-cv-04235
    example_object_type: string
    example_predicate: niem50:CaseDocketID
    example_subject: scales/CaseCivil
    example_subject_type: scales_Case
- description: jxdm72_Case → integer
  object:
    example_object: '100271'
    example_object_type: integer
    example_predicate: niem50:CaseDocketID
    example_subject: scales/CaseCriminal/ga/fulton/01/100271
    example_subject_type: jxdm72_Case
from_schema: scales-kg-new
rank: 1000
slot_uri: niem50:CaseDocketID
alias: niem50_CaseDocketID
domain_of:
- jxdm72_Case
- scales_Case
range: Any
any_of:
- range: integer
- range: string

```
</details>