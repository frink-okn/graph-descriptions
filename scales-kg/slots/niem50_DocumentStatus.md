

# Slot: niem50_DocumentStatus


_No slot (predicate) description specified_





URI: [niem50:DocumentStatus](http://release.niem.gov/niem/niem-core/5.0/DocumentStatus)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Jxdm72ChargeInstrument](../classes/Jxdm72ChargeInstrument.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| jxdm72_ChargeInstrument → string | scales/ChargeInstrument/1835274 | niem50:DocumentStatus | Filed |


## Comments

* 101588 occurrences with subject type jxdm72_ChargeInstrument and object type string.



## LinkML Source

<details>

```yaml
name: niem50_DocumentStatus
description: No slot (predicate) description specified
comments:
- 101588 occurrences with subject type jxdm72_ChargeInstrument and object type string.
examples:
- description: jxdm72_ChargeInstrument → string
  object:
    example_object: Filed
    example_object_type: string
    example_predicate: niem50:DocumentStatus
    example_subject: scales/ChargeInstrument/1835274
    example_subject_type: jxdm72_ChargeInstrument
from_schema: scales-kg-new
rank: 1000
slot_uri: niem50:DocumentStatus
alias: niem50_DocumentStatus
domain_of:
- jxdm72_ChargeInstrument
range: string

```
</details>