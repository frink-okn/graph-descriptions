

# Slot: TODO -- tell the world what this slot (predicate) describes. (contaminoso_resultAnnotation)


_TODO -- tell the world what this slot (predicate) describes._





URI: [contaminoso:resultAnnotation](http://sawgraph.spatialai.org/v1/contaminoso#resultAnnotation)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoResultQualifier](../classes/ContaminosoResultQualifier.md) | TODO -- tell the world what this class (type) describes |  no  |
| [MeegadEGAD-ValidationLevel](../classes/MeegadEGAD-ValidationLevel.md) | TODO -- tell the world what this class (type) describes |  no  |
| [PfasQuantitationLimit](../classes/PfasQuantitationLimit.md) | TODO -- tell the world what this class (type) describes |  no  |
| [ContaminosoContaminantMeasurement](../classes/ContaminosoContaminantMeasurement.md) | TODO -- tell the world what this class (type) describes |  no  |
| [MeegadEGAD-LabQualifier](../classes/MeegadEGAD-LabQualifier.md) | TODO -- tell the world what this class (type) describes |  no  |
| [PfasMethodDetectionLimit](../classes/PfasMethodDetectionLimit.md) | TODO -- tell the world what this class (type) describes |  no  |
| [ContaminosoAggregateContaminantMeasurement](../classes/ContaminosoAggregateContaminantMeasurement.md) | TODO -- tell the world what this class (type) describes |  no  |
| [PfasReportingLimit](../classes/PfasReportingLimit.md) | TODO -- tell the world what this class (type) describes |  no  |
| [MeegadEGAD-ValidationQualifier](../classes/MeegadEGAD-ValidationQualifier.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ContaminosoResultQualifier](../classes/ContaminosoResultQualifier.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.1763231 contaminoso:resultAnnotation meegad:validationLevel.DEP |
| http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.DEP18018 contaminoso:resultAnnotation meegad:validationLevel.DEP |
| http://sawgraph.spatialai.org/v1/me-egad-data#result.170094201.VAL.20170725.108427538 contaminoso:resultAnnotation meegad:validationLevel.TierII-EPA-NE-REGION-1-GUIDELINES |
| http://sawgraph.spatialai.org/v1/me-egad-data#result.170098413.VAL.20170802.DEP18016 contaminoso:resultAnnotation meegad:validationLevel.TierII-EPA-NE-REGION-1-GUIDELINES |
| http://sawgraph.spatialai.org/v1/me-egad-data#mdl.WG17410824.AAWH.20230125.DEP18018 contaminoso:resultAnnotation http://sawgraph.spatialai.org/v1/me-egad-data#rl.WG17410824.AAWH.20230125.DEP18018 |

## Comments

* 180161 occurrences with subject type contaminoso_ContaminantMeasurement and object type contaminoso_ResultQualifier.
* 44340 occurrences with subject type contaminoso_AggregateContaminantMeasurement and object type contaminoso_ResultQualifier.
* 535 occurrences with subject type contaminoso_ContaminantMeasurement and object type uri.
* 72 occurrences with subject type contaminoso_AggregateContaminantMeasurement and object type uri.
* 283759 occurrences with subject type contaminoso_ResultQualifier and object type contaminoso_ResultQualifier.

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
| self | contaminoso:resultAnnotation |
| native | sawgraph-kg/:contaminoso_resultAnnotation |




## LinkML Source

<details>
```yaml
name: contaminoso_resultAnnotation
description: TODO -- tell the world what this slot (predicate) describes.
title: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 180161 occurrences with subject type contaminoso_ContaminantMeasurement and object
  type contaminoso_ResultQualifier.
- 44340 occurrences with subject type contaminoso_AggregateContaminantMeasurement
  and object type contaminoso_ResultQualifier.
- 535 occurrences with subject type contaminoso_ContaminantMeasurement and object
  type uri.
- 72 occurrences with subject type contaminoso_AggregateContaminantMeasurement and
  object type uri.
- 283759 occurrences with subject type contaminoso_ResultQualifier and object type
  contaminoso_ResultQualifier.
examples:
- value: http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.1763231
    contaminoso:resultAnnotation meegad:validationLevel.DEP
- value: http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.DEP18018
    contaminoso:resultAnnotation meegad:validationLevel.DEP
- value: http://sawgraph.spatialai.org/v1/me-egad-data#result.170094201.VAL.20170725.108427538
    contaminoso:resultAnnotation meegad:validationLevel.TierII-EPA-NE-REGION-1-GUIDELINES
- value: http://sawgraph.spatialai.org/v1/me-egad-data#result.170098413.VAL.20170802.DEP18016
    contaminoso:resultAnnotation meegad:validationLevel.TierII-EPA-NE-REGION-1-GUIDELINES
- value: http://sawgraph.spatialai.org/v1/me-egad-data#mdl.WG17410824.AAWH.20230125.DEP18018
    contaminoso:resultAnnotation http://sawgraph.spatialai.org/v1/me-egad-data#rl.WG17410824.AAWH.20230125.DEP18018
from_schema: sawgraph-kg
rank: 1000
slot_uri: contaminoso:resultAnnotation
alias: contaminoso_resultAnnotation
domain_of:
- contaminoso_AggregateContaminantMeasurement
- contaminoso_ContaminantMeasurement
- contaminoso_ResultQualifier
range: Any
any_of:
- range: contaminoso_ResultQualifier
- range: uri

```
</details>