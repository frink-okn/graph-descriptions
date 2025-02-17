

# Slot: sudokn_locatedInCity


_No slot (predicate) description specified_






This slot occurs 19022 times.


URI: [sudokn:locatedInCity](http://asu.edu/semantics/SUDOKN/locatedInCity)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SudoknGeospatialLocation](../classes/SudoknGeospatialLocation.md) | No class (type) description specified |  yes  |







## Properties

* Range: [SudoknCity](../classes/SudoknCity.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sudokn_GeospatialLocation | sudokn_City | sudokn:101PIPE-site | sudokn:FONTANA-City | 19022 |




## LinkML Source

<details>

```yaml
name: sudokn_locatedInCity
annotations:
  count:
    tag: count
    value: 19022
description: No slot (predicate) description specified
examples:
- object:
    example_object: sudokn:FONTANA-City
    example_object_type: sudokn_City
    example_predicate: sudokn:locatedInCity
    example_subject: sudokn:101PIPE-site
    example_subject_type: sudokn_GeospatialLocation
from_schema: sudokn-kg
rank: 1000
slot_uri: sudokn:locatedInCity
alias: sudokn_locatedInCity
domain_of:
- sudokn_GeospatialLocation
range: sudokn_City

```
</details>