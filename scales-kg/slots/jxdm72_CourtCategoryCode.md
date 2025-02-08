

# Slot: jxdm72_CourtCategoryCode


_No slot (predicate) description specified_





URI: [jxdm72:CourtCategoryCode](http://release.niem.gov/niem/domains/jxdm/7.2/#CourtCategoryCode)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Jxdm72Court](../classes/Jxdm72Court.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| jxdm72_Court → string | scales/Court/almd | jxdm72:CourtCategoryCode | FED |
| None → string | scales:Court/akd | jxdm72:CourtCategoryCode | FED |


## Comments

* 94 occurrences with subject type jxdm72_Court and object type string.
* 94 occurrences with untyped subjects and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | jxdm72:CourtCategoryCode |
| native | scales-kg-new/:jxdm72_CourtCategoryCode |




## LinkML Source

<details>

```yaml
name: jxdm72_CourtCategoryCode
description: No slot (predicate) description specified
comments:
- 94 occurrences with subject type jxdm72_Court and object type string.
- 94 occurrences with untyped subjects and object type string.
examples:
- description: jxdm72_Court → string
  object:
    example_object: FED
    example_object_type: string
    example_predicate: jxdm72:CourtCategoryCode
    example_subject: scales/Court/almd
    example_subject_type: jxdm72_Court
- description: None → string
  object:
    example_object: FED
    example_object_type: string
    example_predicate: jxdm72:CourtCategoryCode
    example_subject: scales:Court/akd
    example_subject_type: None
from_schema: scales-kg-new
rank: 1000
slot_uri: jxdm72:CourtCategoryCode
alias: jxdm72_CourtCategoryCode
domain_of:
- jxdm72_Court
range: string

```
</details>