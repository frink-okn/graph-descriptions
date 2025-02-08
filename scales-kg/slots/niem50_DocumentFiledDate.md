

# Slot: niem50_DocumentFiledDate


_No slot (predicate) description specified_





URI: [niem50:DocumentFiledDate](http://release.niem.gov/niem/niem-core/5.0/DocumentFiledDate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Jxdm72ChargeInstrument](../classes/Jxdm72ChargeInstrument.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:date](http://www.w3.org/2001/XMLSchema#date)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| jxdm72_ChargeInstrument → date | scales/ChargeInstrument/1835274 | niem50:DocumentFiledDate | 2011-12-01 |


## Comments

* 86007 occurrences with subject type jxdm72_ChargeInstrument and object type date.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | niem50:DocumentFiledDate |
| native | scales-kg-new/:niem50_DocumentFiledDate |




## LinkML Source

<details>

```yaml
name: niem50_DocumentFiledDate
description: No slot (predicate) description specified
comments:
- 86007 occurrences with subject type jxdm72_ChargeInstrument and object type date.
examples:
- description: jxdm72_ChargeInstrument → date
  object:
    example_object: '2011-12-01'
    example_object_type: date
    example_predicate: niem50:DocumentFiledDate
    example_subject: scales/ChargeInstrument/1835274
    example_subject_type: jxdm72_ChargeInstrument
from_schema: scales-kg-new
rank: 1000
slot_uri: niem50:DocumentFiledDate
alias: niem50_DocumentFiledDate
domain_of:
- jxdm72_ChargeInstrument
range: date

```
</details>