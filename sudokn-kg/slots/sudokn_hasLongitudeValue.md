

# Slot: No slot (predicate) name specified (sudokn_hasLongitudeValue)


_No slot (predicate) description specified_






This slot occurs 19083 times.


URI: [sudokn:hasLongitudeValue](http://asu.edu/semantics/SUDOKN/hasLongitudeValue)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SudoknTwoDimensionalCartesianSpatialCoordinateDatum](../classes/SudoknTwoDimensionalCartesianSpatialCoordinateDatum.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sudokn_TwoDimensionalCartesianSpatialCoordinateDatum | string | sudokn:101PIPE-site-FONTANA-92335-coordinates | -117.4708951 | 19083 |




## LinkML Source

<details>

```yaml
name: sudokn_hasLongitudeValue
annotations:
  count:
    tag: count
    value: 19083
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '-117.4708951'
    example_object_type: string
    example_predicate: sudokn:hasLongitudeValue
    example_subject: sudokn:101PIPE-site-FONTANA-92335-coordinates
    example_subject_type: sudokn_TwoDimensionalCartesianSpatialCoordinateDatum
from_schema: sudokn-kg
rank: 1000
slot_uri: sudokn:hasLongitudeValue
alias: sudokn_hasLongitudeValue
domain_of:
- sudokn_TwoDimensionalCartesianSpatialCoordinateDatum
range: Any
any_of:
- range: uri
- range: string

```
</details>