

# Slot: TODO -- tell the world what this slot (predicate) describes. (contaminoso_fromSamplePoint)


_TODO -- tell the world what this slot (predicate) describes._





URI: [contaminoso:fromSamplePoint](http://sawgraph.spatialai.org/v1/contaminoso#fromSamplePoint)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoMaterialSample](../classes/ContaminosoMaterialSample.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ContaminosoPoint](../classes/ContaminosoPoint.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-Sample.ME0400899.10282021 contaminoso:fromSamplePoint http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-SamplePoint.ME0400899.10282021 |

## Comments

* 18128 occurrences with subject type contaminoso_MaterialSample and object type contaminoso_Point.

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
| self | contaminoso:fromSamplePoint |
| native | sawgraph-kg/:contaminoso_fromSamplePoint |




## LinkML Source

<details>
```yaml
name: contaminoso_fromSamplePoint
description: TODO -- tell the world what this slot (predicate) describes.
title: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 18128 occurrences with subject type contaminoso_MaterialSample and object type contaminoso_Point.
examples:
- value: http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-Sample.ME0400899.10282021
    contaminoso:fromSamplePoint http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-SamplePoint.ME0400899.10282021
from_schema: sawgraph-kg
rank: 1000
slot_uri: contaminoso:fromSamplePoint
alias: contaminoso_fromSamplePoint
domain_of:
- contaminoso_MaterialSample
range: Any
any_of:
- range: contaminoso_Point
- range: uri

```
</details>