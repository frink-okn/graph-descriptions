

# Slot: iosc_hasTextValue


_No slot (predicate) description specified_






This slot occurs 19102 times.


URI: [iosc:hasTextValue](https://spec.industrialontologies.org/ontology/supplychain/SupplyChain/hasTextValue)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SudoknPostalAddress](../classes/SudoknPostalAddress.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sudokn_PostalAddress | string | sudokn:101PIPE-PostalAddress | 10255 BEECH AVENUE | 19102 |




## LinkML Source

<details>

```yaml
name: iosc_hasTextValue
annotations:
  count:
    tag: count
    value: 19102
description: No slot (predicate) description specified
examples:
- object:
    example_object: 10255 BEECH AVENUE
    example_object_type: string
    example_predicate: iosc:hasTextValue
    example_subject: sudokn:101PIPE-PostalAddress
    example_subject_type: sudokn_PostalAddress
from_schema: sudokn-kg
rank: 1000
slot_uri: iosc:hasTextValue
alias: iosc_hasTextValue
domain_of:
- sudokn_PostalAddress
range: string

```
</details>