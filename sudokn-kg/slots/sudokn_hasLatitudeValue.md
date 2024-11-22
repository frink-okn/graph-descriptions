

# Slot: has latitude value (sudokn_hasLatitudeValue)


_TODO -- tell the world what this slot (predicate) describes._





URI: [sudokn:hasLatitudeValue](http://asu.edu/semantics/SUDOKN/hasLatitudeValue)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SudoknTwoDimensionalCartesianSpatialCoordinateDatum](../classes/SudoknTwoDimensionalCartesianSpatialCoordinateDatum.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| sudokn:101PIPE-site-FONTANA-92335-coordinates sudokn:hasLatitudeValue 34.0677902 |

## Comments

* 19082 occurrences with subject type sudokn_TwoDimensionalCartesianSpatialCoordinateDatum and object type string.

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
| self | sudokn:hasLatitudeValue |
| native | sudokn-kg/:sudokn_hasLatitudeValue |




## LinkML Source

<details>
```yaml
name: sudokn_hasLatitudeValue
description: TODO -- tell the world what this slot (predicate) describes.
title: has latitude value
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 19082 occurrences with subject type sudokn_TwoDimensionalCartesianSpatialCoordinateDatum
  and object type string.
examples:
- value: sudokn:101PIPE-site-FONTANA-92335-coordinates sudokn:hasLatitudeValue 34.0677902
from_schema: sudokn-kg
rank: 1000
slot_uri: sudokn:hasLatitudeValue
alias: sudokn_hasLatitudeValue
domain_of:
- sudokn_TwoDimensionalCartesianSpatialCoordinateDatum
subproperty_of: owl_topDataProperty
range: Any
any_of:
- range: uri
- range: string

```
</details>