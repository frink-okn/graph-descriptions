

# Slot: niem50_DocumentDescriptionText


_No slot (predicate) description specified_





URI: [niem50:DocumentDescriptionText](http://release.niem.gov/niem/niem-core/5.0/DocumentDescriptionText)



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
| jxdm72_ChargeInstrument → string | scales/ChargeInstrument/1835274 | niem50:DocumentDescriptionText | Accusation Filed |


## Comments

* 94949 occurrences with subject type jxdm72_ChargeInstrument and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | niem50:DocumentDescriptionText |
| native | scales-kg-new/:niem50_DocumentDescriptionText |




## LinkML Source

<details>

```yaml
name: niem50_DocumentDescriptionText
description: No slot (predicate) description specified
comments:
- 94949 occurrences with subject type jxdm72_ChargeInstrument and object type string.
examples:
- description: jxdm72_ChargeInstrument → string
  object:
    example_object: Accusation Filed
    example_object_type: string
    example_predicate: niem50:DocumentDescriptionText
    example_subject: scales/ChargeInstrument/1835274
    example_subject_type: jxdm72_ChargeInstrument
from_schema: scales-kg-new
rank: 1000
slot_uri: niem50:DocumentDescriptionText
alias: niem50_DocumentDescriptionText
domain_of:
- jxdm72_ChargeInstrument
range: string

```
</details>