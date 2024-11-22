

# Slot: TODO -- tell the world what this slot (predicate) describes. (meegad_validationQualifier)


_TODO -- tell the world what this slot (predicate) describes._





URI: [meegad:validationQualifier](http://sawgraph.spatialai.org/v1/me-egad#validationQualifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoAggregateContaminantMeasurement](../classes/ContaminosoAggregateContaminantMeasurement.md) | TODO -- tell the world what this class (type) describes |  no  |
| [ContaminosoContaminantMeasurement](../classes/ContaminosoContaminantMeasurement.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ContaminosoResultQualifier](../classes/ContaminosoResultQualifier.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.1763231 meegad:validationQualifier meegad:concentrationQualifier.J |
| http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.DEP18018 meegad:validationQualifier meegad:concentrationQualifier.J |
| http://sawgraph.spatialai.org/v1/me-egad-data#result.320623561.TA.20200701.335671 meegad:validationQualifier meegad:concentrationQualifier.M |
| http://sawgraph.spatialai.org/v1/me-egad-data#result.320623562.TA.20200701.DEP18010 meegad:validationQualifier meegad:concentrationQualifier.M |

## Comments

* 60592 occurrences with subject type contaminoso_ContaminantMeasurement and object type contaminoso_ResultQualifier.
* 17314 occurrences with subject type contaminoso_AggregateContaminantMeasurement and object type contaminoso_ResultQualifier.
* 45 occurrences with subject type contaminoso_ContaminantMeasurement and object type uri.
* 8 occurrences with subject type contaminoso_AggregateContaminantMeasurement and object type uri.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: sawgraph-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | meegad:validationQualifier |
| native | sawgraph-kg/:meegad_validationQualifier |




## LinkML Source

<details>
```yaml
name: meegad_validationQualifier
description: TODO -- tell the world what this slot (predicate) describes.
title: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 60592 occurrences with subject type contaminoso_ContaminantMeasurement and object
  type contaminoso_ResultQualifier.
- 17314 occurrences with subject type contaminoso_AggregateContaminantMeasurement
  and object type contaminoso_ResultQualifier.
- 45 occurrences with subject type contaminoso_ContaminantMeasurement and object type
  uri.
- 8 occurrences with subject type contaminoso_AggregateContaminantMeasurement and
  object type uri.
examples:
- value: http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.1763231
    meegad:validationQualifier meegad:concentrationQualifier.J
- value: http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.DEP18018
    meegad:validationQualifier meegad:concentrationQualifier.J
- value: http://sawgraph.spatialai.org/v1/me-egad-data#result.320623561.TA.20200701.335671
    meegad:validationQualifier meegad:concentrationQualifier.M
- value: http://sawgraph.spatialai.org/v1/me-egad-data#result.320623562.TA.20200701.DEP18010
    meegad:validationQualifier meegad:concentrationQualifier.M
from_schema: sawgraph-kg
rank: 1000
slot_uri: meegad:validationQualifier
alias: meegad_validationQualifier
domain_of:
- contaminoso_AggregateContaminantMeasurement
- contaminoso_ContaminantMeasurement
subproperty_of: contaminoso_resultAnnotation
range: Any
any_of:
- range: contaminoso_ResultQualifier
- range: uri

```
</details>