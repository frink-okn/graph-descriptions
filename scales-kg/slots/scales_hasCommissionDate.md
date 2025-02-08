

# Slot: scales_hasCommissionDate


_No slot (predicate) description specified_





URI: [scales:hasCommissionDate](http://schemas.scales-okn.org/rdf/scales#hasCommissionDate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Jxdm72Judge](../classes/Jxdm72Judge.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:date](xsd:date)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| jxdm72_Judge → date | scales/JudgeEntity/SJ000004 | scales:hasCommissionDate | 1987-01-01 |


## Comments

* 4257 occurrences with subject type jxdm72_Judge and object type date.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | scales:hasCommissionDate |
| native | scales-kg-new/:scales_hasCommissionDate |




## LinkML Source

<details>
```yaml
name: scales_hasCommissionDate
description: No slot (predicate) description specified
comments:
- 4257 occurrences with subject type jxdm72_Judge and object type date.
examples:
- description: jxdm72_Judge → date
  object:
    example_object: '1987-01-01'
    example_object_type: date
    example_predicate: scales:hasCommissionDate
    example_subject: scales/JudgeEntity/SJ000004
    example_subject_type: jxdm72_Judge
from_schema: scales-kg-new
rank: 1000
slot_uri: scales:hasCommissionDate
alias: scales_hasCommissionDate
domain_of:
- jxdm72_Judge
range: date

```
</details>