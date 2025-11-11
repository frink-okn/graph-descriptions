

# Slot: has feature of interest (coso_hasFeatureOfInterest)


_A relation between an observation of a contaminant and a feature it is the subject of._






This slot occurs 1282898 times.


URI: [coso:hasFeatureOfInterest](http://w3id.org/coso/v1/contaminoso#hasFeatureOfInterest)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Us-wqp#Observation](../classes/HttpW3id.orgSawgraphV1Us-wqp#Observation.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) |  |  no  |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SampledFeature](../classes/MeEgadEGAD-SampledFeature.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[CosoFeature](../classes/CosoFeature.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature.md)&nbsp;or&nbsp;<br />[SosaFeatureOfInterest](../classes/SosaFeatureOfInterest.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)







## LinkML Source

<details>

```yaml
name: coso_hasFeatureOfInterest
description: A relation between an observation of a contaminant and a feature it is
  the subject of.
title: has feature of interest
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:hasFeatureOfInterest
alias: coso_hasFeatureOfInterest
domain_of:
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Observation
- http___w3id.org_sawgraph_v1_us-wqp#Observation
- me_egad_EGAD-PFAS-Observation
subproperty_of: coso_hasAnyFeatureOfInterest
union_of:
- coso_ContaminantObservation
- owl_Thing
- sosa_Observation
range: Any
any_of:
- range: geo_Feature
- range: me_egad_EGAD-SampledFeature
- range: uri
- range: owl_Thing
- range: coso_Feature
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SampledFeature
- range: sosa_FeatureOfInterest
- range: geo_SpatialObject

```
</details>