

# Slot: sudokn_hasIntegerValue


_No slot (predicate) description specified_






This slot occurs 18729 times.


URI: [sudokn:hasIntegerValue](http://asu.edu/semantics/SUDOKN/hasIntegerValue)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SudoknUSPostalCode](../classes/SudoknUSPostalCode.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sudokn_USPostalCode | string | sudokn:101PIPE-site-FONTANA-92335-site-zip | 92335 | 18729 |




## LinkML Source

<details>

```yaml
name: sudokn_hasIntegerValue
annotations:
  count:
    tag: count
    value: 18729
description: No slot (predicate) description specified
examples:
- object:
    example_object: '92335'
    example_object_type: string
    example_predicate: sudokn:hasIntegerValue
    example_subject: sudokn:101PIPE-site-FONTANA-92335-site-zip
    example_subject_type: sudokn_USPostalCode
from_schema: sudokn-kg
rank: 1000
slot_uri: sudokn:hasIntegerValue
alias: sudokn_hasIntegerValue
domain_of:
- sudokn_USPostalCode
range: string

```
</details>