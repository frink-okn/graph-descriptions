

# Slot: sampled feature (coso_sampledFeature)


_A relation between an observation of a contaminant from a sample and the feature that was sampled._







URI: [coso:sampledFeature](http://w3id.org/coso/v1/contaminoso#sampledFeature)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[CosoSampledFeature](../classes/CosoSampledFeature.md)&nbsp;or&nbsp;<br />[GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[CosoFeature](../classes/CosoFeature.md)&nbsp;or&nbsp;<br />[SosaFeatureOfInterest](../classes/SosaFeatureOfInterest.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)







## LinkML Source

<details>

```yaml
name: coso_sampledFeature
description: A relation between an observation of a contaminant from a sample and
  the feature that was sampled.
title: sampled feature
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:sampledFeature
alias: coso_sampledFeature
subproperty_of: coso_hasFeatureOfInterest
union_of:
- coso_ContaminantObservation
- owl_Thing
- sosa_Observation
- coso_ContaminantSampleObservation
range: Any
any_of:
- range: coso_SampledFeature
- range: geo_Feature
- range: owl_Thing
- range: coso_Feature
- range: sosa_FeatureOfInterest
- range: geo_SpatialObject

```
</details>