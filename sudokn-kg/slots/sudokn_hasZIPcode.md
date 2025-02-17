

# Slot: sudokn_hasZIPcode


_No slot (predicate) description specified_






This slot occurs 20424 times.


URI: [sudokn:hasZIPcode](http://asu.edu/semantics/SUDOKN/hasZIPcode)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SudoknGeospatialLocation](../classes/SudoknGeospatialLocation.md) | No class (type) description specified |  yes  |







## Properties

* Range: [SudoknUSPostalCode](../classes/SudoknUSPostalCode.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sudokn_GeospatialLocation | sudokn_USPostalCode | sudokn:101PIPE-site | sudokn:101PIPE-site-zip | 20424 |




## LinkML Source

<details>

```yaml
name: sudokn_hasZIPcode
annotations:
  count:
    tag: count
    value: 20424
description: No slot (predicate) description specified
examples:
- object:
    example_object: sudokn:101PIPE-site-zip
    example_object_type: sudokn_USPostalCode
    example_predicate: sudokn:hasZIPcode
    example_subject: sudokn:101PIPE-site
    example_subject_type: sudokn_GeospatialLocation
from_schema: sudokn-kg
rank: 1000
slot_uri: sudokn:hasZIPcode
alias: sudokn_hasZIPcode
domain_of:
- sudokn_GeospatialLocation
range: sudokn_USPostalCode

```
</details>