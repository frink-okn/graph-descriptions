

# Slot: scales_appointedByParty


_No slot (predicate) description specified_





URI: [scales:appointedByParty](http://schemas.scales-okn.org/rdf/scales#appointedByParty)



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
| jxdm72_Judge → string | scales/JudgeEntity/SJ000004 | scales:appointedByParty | Republican |


## Comments

* 3912 occurrences with subject type jxdm72_Judge and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | scales:appointedByParty |
| native | scales-kg-new/:scales_appointedByParty |




## LinkML Source

<details>

```yaml
name: scales_appointedByParty
description: No slot (predicate) description specified
comments:
- 3912 occurrences with subject type jxdm72_Judge and object type string.
examples:
- description: jxdm72_Judge → string
  object:
    example_object: Republican
    example_object_type: string
    example_predicate: scales:appointedByParty
    example_subject: scales/JudgeEntity/SJ000004
    example_subject_type: jxdm72_Judge
from_schema: scales-kg-new
rank: 1000
slot_uri: scales:appointedByParty
alias: scales_appointedByParty
domain_of:
- jxdm72_Judge
range: string

```
</details>