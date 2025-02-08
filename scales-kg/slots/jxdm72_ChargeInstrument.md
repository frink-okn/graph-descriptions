

# Slot: jxdm72_ChargeInstrument


_No slot (predicate) description specified_





URI: [jxdm72:ChargeInstrument](http://release.niem.gov/niem/domains/jxdm/7.2/#ChargeInstrument)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Jxdm72Charge](../classes/Jxdm72Charge.md) | No class (type) description specified |  no  |







## Properties

* Range: [Jxdm72ChargeInstrument](../classes/Jxdm72ChargeInstrument.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Jxdm72Charge](../classes/Jxdm72Charge.md) | [Jxdm72ChargeInstrument](../classes/Jxdm72ChargeInstrument.md) | range | [Jxdm72ChargeInstrument](../classes/Jxdm72ChargeInstrument.md) |







## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| jxdm72_Charge → jxdm72_ChargeInstrument | scales/Charge/8379993_c16887006-gafulton0110620219 | jxdm72:ChargeInstrument | scales/ChargeInstrument/8229996 |


## Comments

* 199210 occurrences with subject type jxdm72_Charge and object type jxdm72_ChargeInstrument.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | jxdm72:ChargeInstrument |
| native | scales-kg-new/:Jxdm72ChargeInstrument |




## LinkML Source

<details>

```yaml
name: jxdm72_ChargeInstrument
description: No slot (predicate) description specified
comments:
- 199210 occurrences with subject type jxdm72_Charge and object type jxdm72_ChargeInstrument.
examples:
- description: jxdm72_Charge → jxdm72_ChargeInstrument
  object:
    example_object: scales/ChargeInstrument/8229996
    example_object_type: jxdm72_ChargeInstrument
    example_predicate: jxdm72:ChargeInstrument
    example_subject: scales/Charge/8379993_c16887006-gafulton0110620219
    example_subject_type: jxdm72_Charge
from_schema: scales-kg-new
rank: 1000
slot_uri: jxdm72:ChargeInstrument
alias: jxdm72_ChargeInstrument
domain_of:
- jxdm72_Charge
range: jxdm72_ChargeInstrument

```
</details>