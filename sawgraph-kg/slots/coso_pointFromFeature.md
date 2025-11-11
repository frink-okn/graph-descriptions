

# Slot: point from feature (coso_pointFromFeature)


_A relation between a point location and the larger geospatial feature it is a part of._






This slot occurs 16468 times.


URI: [coso:pointFromFeature](http://w3id.org/coso/v1/contaminoso#pointFromFeature)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Us-wqp#Site](../classes/HttpW3id.orgSawgraphV1Us-wqp#Site.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#SampledFeature](../classes/HttpW3id.orgSawgraphV1Us-wqp#SampledFeature.md)&nbsp;or&nbsp;<br />[GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SampledFeature](../classes/MeEgadEGAD-SampledFeature.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[CosoFeature](../classes/CosoFeature.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature.md)&nbsp;or&nbsp;<br />[SosaFeatureOfInterest](../classes/SosaFeatureOfInterest.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)







## LinkML Source

<details>

```yaml
name: coso_pointFromFeature
description: A relation between a point location and the larger geospatial feature
  it is a part of.
title: point from feature
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:pointFromFeature
alias: coso_pointFromFeature
domain_of:
- http___w3id.org_sawgraph_v1_me-egad#EGAD-SamplePoint
- http___w3id.org_sawgraph_v1_us-wqp#Site
- me_egad_EGAD-SamplePoint
union_of:
- geo_Feature
- owl_Thing
- geo_SpatialObject
- sosa_FeatureOfInterest
- coso_Point
range: Any
any_of:
- range: http___w3id.org_sawgraph_v1_us-wqp#SampledFeature
- range: geo_Feature
- range: me_egad_EGAD-SampledFeature
- range: owl_Thing
- range: coso_Feature
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SampledFeature
- range: sosa_FeatureOfInterest
- range: geo_SpatialObject

```
</details>