

# Slot: niem50_DocumentEffectiveDate


_No slot (predicate) description specified_





URI: [niem50:DocumentEffectiveDate](http://release.niem.gov/niem/niem-core/5.0/DocumentEffectiveDate)



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
| jxdm72_ChargeInstrument → date | scales/ChargeInstrument/1835274 | niem50:DocumentEffectiveDate | 2013-09-01 |


## Comments

* 92142 occurrences with subject type jxdm72_ChargeInstrument and object type date.



## LinkML Source

<details>

```yaml
name: niem50_DocumentEffectiveDate
description: No slot (predicate) description specified
comments:
- 92142 occurrences with subject type jxdm72_ChargeInstrument and object type date.
examples:
- description: jxdm72_ChargeInstrument → date
  object:
    example_object: '2013-09-01'
    example_object_type: date
    example_predicate: niem50:DocumentEffectiveDate
    example_subject: scales/ChargeInstrument/1835274
    example_subject_type: jxdm72_ChargeInstrument
from_schema: scales-kg-new
rank: 1000
slot_uri: niem50:DocumentEffectiveDate
alias: niem50_DocumentEffectiveDate
domain_of:
- jxdm72_ChargeInstrument
range: date

```
</details>