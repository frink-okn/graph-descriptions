

# Slot: observed at sample point (coso_observedAtSamplePoint)


_A relation between an observation of a contaminant from a material sample and the point where the sample was taken._






This slot occurs 1282902 times.


URI: [coso:observedAtSamplePoint](http://w3id.org/coso/v1/contaminoso#observedAtSamplePoint)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Us-wqp#Observation](../classes/HttpW3id.orgSawgraphV1Us-wqp#Observation.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) |  |  no  |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#Site](../classes/HttpW3id.orgSawgraphV1Us-wqp#Site.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)&nbsp;or&nbsp;<br />[CosoSamplePoint](../classes/CosoSamplePoint.md)&nbsp;or&nbsp;<br />[SosaFeatureOfInterest](../classes/SosaFeatureOfInterest.md)&nbsp;or&nbsp;<br />[CosoPoint](../classes/CosoPoint.md)







## LinkML Source

<details>

```yaml
name: coso_observedAtSamplePoint
description: A relation between an observation of a contaminant from a material sample
  and the point where the sample was taken.
title: observed at sample point
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:observedAtSamplePoint
alias: coso_observedAtSamplePoint
domain_of:
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Observation
- http___w3id.org_sawgraph_v1_us-wqp#Observation
- me_egad_EGAD-PFAS-Observation
subproperty_of: coso_observedAtPoint
union_of:
- coso_ContaminantObservation
- owl_Thing
- sosa_Observation
- coso_ContaminantSampleObservation
range: Any
any_of:
- range: geo_Feature
- range: uri
- range: http___w3id.org_sawgraph_v1_us-wqp#Site
- range: owl_Thing
- range: me_egad_EGAD-SamplePoint
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SamplePoint
- range: geo_SpatialObject
- range: coso_SamplePoint
- range: sosa_FeatureOfInterest
- range: coso_Point

```
</details>