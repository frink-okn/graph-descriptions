

# Slot: jxdm72_CaseCourt


_No slot (predicate) description specified_





URI: [jxdm72:CaseCourt](http://release.niem.gov/niem/domains/jxdm/7.2/#CaseCourt)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  no  |







## Properties

* Range: [Jxdm72Court](../classes/Jxdm72Court.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| scales_Case → jxdm72_Court | scales/CaseCriminal | jxdm72:CaseCourt | scales/Court/wyd |


## Comments

* 143 occurrences with subject type scales_Case and object type jxdm72_Court.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | jxdm72:CaseCourt |
| native | scales-kg-new/:jxdm72_CaseCourt |




## LinkML Source

<details>
```yaml
name: jxdm72_CaseCourt
description: No slot (predicate) description specified
comments:
- 143 occurrences with subject type scales_Case and object type jxdm72_Court.
examples:
- description: scales_Case → jxdm72_Court
  object:
    example_object: scales/Court/wyd
    example_object_type: jxdm72_Court
    example_predicate: jxdm72:CaseCourt
    example_subject: scales/CaseCriminal
    example_subject_type: scales_Case
from_schema: scales-kg-new
rank: 1000
slot_uri: jxdm72:CaseCourt
alias: jxdm72_CaseCourt
domain_of:
- scales_Case
range: jxdm72_Court

```
</details>