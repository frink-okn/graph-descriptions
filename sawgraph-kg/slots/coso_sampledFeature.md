

# Slot: sampled feature (coso_sampledFeature)


_A relation between an observation of a contaminant from a sample and the feature that was sampled._







URI: [coso:sampledFeature](http://w3id.org/coso/v1/contaminoso#sampledFeature)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[CosoSampledFeature](../classes/CosoSampledFeature.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)&nbsp;or&nbsp;<br />[SosaFeatureOfInterest](../classes/SosaFeatureOfInterest.md)&nbsp;or&nbsp;<br />[CosoFeature](../classes/CosoFeature.md)





## Comments

* No occurrences of this slot in the graph.



## LinkML Source

<details>

```yaml
name: coso_sampledFeature
description: A relation between an observation of a contaminant from a sample and
  the feature that was sampled.
title: sampled feature
comments:
- No occurrences of this slot in the graph.
from_schema: sawgraph-kg
rank: 1000
slot_uri: coso:sampledFeature
alias: coso_sampledFeature
subproperty_of: coso_hasFeatureOfInterest
union_of:
- '{''domain'': ''owl_Thing''}'
- '{''domain'': ''sosa_Observation''}'
- '{''domain'': ''coso_ContaminantSampleObservation''}'
- '{''domain'': ''coso_ContaminantObservation''}'
range: Any
any_of:
- range: owl_Thing
- range: geo_Feature
- range: coso_SampledFeature
- range: geo_SpatialObject
- range: sosa_FeatureOfInterest
- range: coso_Feature

```
</details>