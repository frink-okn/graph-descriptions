

# Slot: observed at point (coso_observedAtPoint)


_A relation between an observation of a contaminant and the point that the observation applies to._






This slot occurs 1154228 times.


URI: [coso:observedAtPoint](http://w3id.org/coso/v1/contaminoso#observedAtPoint)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) |  |  no  |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)&nbsp;or&nbsp;<br />[SosaFeatureOfInterest](../classes/SosaFeatureOfInterest.md)&nbsp;or&nbsp;<br />[CosoPoint](../classes/CosoPoint.md)







## LinkML Source

<details>

```yaml
name: coso_observedAtPoint
description: A relation between an observation of a contaminant and the point that
  the observation applies to.
title: observed at point
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:observedAtPoint
alias: coso_observedAtPoint
domain_of:
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Observation
- me_egad_EGAD-PFAS-Observation
subproperty_of: coso_hasAnyFeatureOfInterest
union_of:
- coso_ContaminantObservation
- owl_Thing
- sosa_Observation
range: Any
any_of:
- range: geo_Feature
- range: owl_Thing
- range: me_egad_EGAD-SamplePoint
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SamplePoint
- range: geo_SpatialObject
- range: sosa_FeatureOfInterest
- range: coso_Point

```
</details>