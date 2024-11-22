

# Slot: TODO -- tell the world what this slot (predicate) describes. (meegad_validationLevel)


_TODO -- tell the world what this slot (predicate) describes._





URI: [meegad:validationLevel](http://sawgraph.spatialai.org/v1/me-egad#validationLevel)



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
| http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.1763231 meegad:validationLevel meegad:validationLevel.DEP |
| http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.DEP18018 meegad:validationLevel meegad:validationLevel.DEP |
| http://sawgraph.spatialai.org/v1/me-egad-data#result.170094201.VAL.20170725.108427538 meegad:validationLevel meegad:validationLevel.TierII-EPA-NE-REGION-1-GUIDELINES |
| http://sawgraph.spatialai.org/v1/me-egad-data#result.170098413.VAL.20170802.DEP18016 meegad:validationLevel meegad:validationLevel.TierII-EPA-NE-REGION-1-GUIDELINES |

## Comments

* 113547 occurrences with subject type contaminoso_ContaminantMeasurement and object type contaminoso_ResultQualifier.
* 26147 occurrences with subject type contaminoso_AggregateContaminantMeasurement and object type contaminoso_ResultQualifier.
* 490 occurrences with subject type contaminoso_ContaminantMeasurement and object type uri.
* 64 occurrences with subject type contaminoso_AggregateContaminantMeasurement and object type uri.

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
| self | meegad:validationLevel |
| native | sawgraph-kg/:meegad_validationLevel |




## LinkML Source

<details>
```yaml
name: meegad_validationLevel
description: TODO -- tell the world what this slot (predicate) describes.
title: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 113547 occurrences with subject type contaminoso_ContaminantMeasurement and object
  type contaminoso_ResultQualifier.
- 26147 occurrences with subject type contaminoso_AggregateContaminantMeasurement
  and object type contaminoso_ResultQualifier.
- 490 occurrences with subject type contaminoso_ContaminantMeasurement and object
  type uri.
- 64 occurrences with subject type contaminoso_AggregateContaminantMeasurement and
  object type uri.
examples:
- value: http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.1763231
    meegad:validationLevel meegad:validationLevel.DEP
- value: http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.DEP18018
    meegad:validationLevel meegad:validationLevel.DEP
- value: http://sawgraph.spatialai.org/v1/me-egad-data#result.170094201.VAL.20170725.108427538
    meegad:validationLevel meegad:validationLevel.TierII-EPA-NE-REGION-1-GUIDELINES
- value: http://sawgraph.spatialai.org/v1/me-egad-data#result.170098413.VAL.20170802.DEP18016
    meegad:validationLevel meegad:validationLevel.TierII-EPA-NE-REGION-1-GUIDELINES
from_schema: sawgraph-kg
rank: 1000
slot_uri: meegad:validationLevel
alias: meegad_validationLevel
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