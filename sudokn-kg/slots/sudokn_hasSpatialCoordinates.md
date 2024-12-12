

# Slot: has spatial coordinates (sudokn_hasSpatialCoordinates)


_No slot description provided_





URI: [sudokn:hasSpatialCoordinates](http://asu.edu/semantics/SUDOKN/hasSpatialCoordinates)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SudoknGeospatialLocation](../classes/SudoknGeospatialLocation.md) | No type description provided |  no  |







## Properties

* Range: [SudoknTwoDimensionalCartesianSpatialCoordinateDatum](../classes/SudoknTwoDimensionalCartesianSpatialCoordinateDatum.md)






## Examples

| Value |
| --- |
| sudokn:qualityproducts-Site sudokn:hasSpatialCoordinates sudokn:qualityproducts-Coordinates |

## Comments

* 20728 occurrences with subject type sudokn_GeospatialLocation and object type sudokn_TwoDimensionalCartesianSpatialCoordinateDatum.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: sudokn-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sudokn:hasSpatialCoordinates |
| native | sudokn-kg/:sudokn_hasSpatialCoordinates |




## LinkML Source

<details>
```yaml
name: sudokn_hasSpatialCoordinates
description: No slot description provided
title: has spatial coordinates
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 20728 occurrences with subject type sudokn_GeospatialLocation and object type sudokn_TwoDimensionalCartesianSpatialCoordinateDatum.
examples:
- value: sudokn:qualityproducts-Site sudokn:hasSpatialCoordinates sudokn:qualityproducts-Coordinates
from_schema: sudokn-kg
rank: 1000
slot_uri: sudokn:hasSpatialCoordinates
alias: sudokn_hasSpatialCoordinates
domain_of:
- sudokn_GeospatialLocation
subproperty_of: io_denotedBy
range: sudokn_TwoDimensionalCartesianSpatialCoordinateDatum

```
</details>