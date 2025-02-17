

# Slot: No slot (predicate) name specified (sudokn_hasSpatialCoordinates)


_No slot (predicate) description specified_






This slot occurs 20728 times.


URI: [sudokn:hasSpatialCoordinates](http://asu.edu/semantics/SUDOKN/hasSpatialCoordinates)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SudoknGeospatialLocation](../classes/SudoknGeospatialLocation.md) | No class (type) description specified |  yes  |







## Properties

* Range: [SudoknTwoDimensionalCartesianSpatialCoordinateDatum](../classes/SudoknTwoDimensionalCartesianSpatialCoordinateDatum.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sudokn_GeospatialLocation | sudokn_TwoDimensionalCartesianSpatialCoordinateDatum | sudokn:101PIPE-site | sudokn:101PIPE-site-coordinates | 20728 |




## LinkML Source

<details>

```yaml
name: sudokn_hasSpatialCoordinates
annotations:
  count:
    tag: count
    value: 20728
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sudokn:101PIPE-site-coordinates
    example_object_type: sudokn_TwoDimensionalCartesianSpatialCoordinateDatum
    example_predicate: sudokn:hasSpatialCoordinates
    example_subject: sudokn:101PIPE-site
    example_subject_type: sudokn_GeospatialLocation
from_schema: sudokn-kg
rank: 1000
slot_uri: sudokn:hasSpatialCoordinates
alias: sudokn_hasSpatialCoordinates
domain_of:
- sudokn_GeospatialLocation
range: sudokn_TwoDimensionalCartesianSpatialCoordinateDatum

```
</details>