

# Slot: sudokn_organizationLocatedIn


_No slot (predicate) description specified_






This slot occurs 20728 times.


URI: [sudokn:organizationLocatedIn](http://asu.edu/semantics/SUDOKN/organizationLocatedIn)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | No class (type) description specified |  yes  |







## Properties

* Range: [SudoknGeospatialLocation](../classes/SudoknGeospatialLocation.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| io_Manufacturer | sudokn_GeospatialLocation | sudokn:101PIPE-company-inst | sudokn:101PIPE-site | 20728 |




## LinkML Source

<details>

```yaml
name: sudokn_organizationLocatedIn
annotations:
  count:
    tag: count
    value: 20728
description: No slot (predicate) description specified
examples:
- object:
    example_object: sudokn:101PIPE-site
    example_object_type: sudokn_GeospatialLocation
    example_predicate: sudokn:organizationLocatedIn
    example_subject: sudokn:101PIPE-company-inst
    example_subject_type: io_Manufacturer
from_schema: sudokn-kg
rank: 1000
slot_uri: sudokn:organizationLocatedIn
alias: sudokn_organizationLocatedIn
domain_of:
- io_Manufacturer
range: sudokn_GeospatialLocation

```
</details>