

# Slot: jxdm72_RegisterActionDate


_No slot (predicate) description specified_





URI: [jxdm72:RegisterActionDate](http://release.niem.gov/niem/domains/jxdm/7.2/#RegisterActionDate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Jxdm72RegisterAction](../classes/Jxdm72RegisterAction.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:date](http://www.w3.org/2001/XMLSchema#date)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| jxdm72_RegisterAction → date | scales/Docket/100271 | jxdm72:RegisterActionDate | 2002-02-01 |
| None → date | scales/DocketEntry/almd;;1:16-cr-00020_de0 | jxdm72:RegisterActionDate | 2016-02-02 |


## Comments

* 421518 occurrences with subject type jxdm72_RegisterAction and object type date.
* 19671603 occurrences with untyped subjects and object type date.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | jxdm72:RegisterActionDate |
| native | scales-kg-new/:jxdm72_RegisterActionDate |




## LinkML Source

<details>

```yaml
name: jxdm72_RegisterActionDate
description: No slot (predicate) description specified
comments:
- 421518 occurrences with subject type jxdm72_RegisterAction and object type date.
- 19671603 occurrences with untyped subjects and object type date.
examples:
- description: jxdm72_RegisterAction → date
  object:
    example_object: '2002-02-01'
    example_object_type: date
    example_predicate: jxdm72:RegisterActionDate
    example_subject: scales/Docket/100271
    example_subject_type: jxdm72_RegisterAction
- description: None → date
  object:
    example_object: '2016-02-02'
    example_object_type: date
    example_predicate: jxdm72:RegisterActionDate
    example_subject: scales/DocketEntry/almd;;1:16-cr-00020_de0
    example_subject_type: None
from_schema: scales-kg-new
rank: 1000
slot_uri: jxdm72:RegisterActionDate
alias: jxdm72_RegisterActionDate
domain_of:
- jxdm72_RegisterAction
range: date

```
</details>