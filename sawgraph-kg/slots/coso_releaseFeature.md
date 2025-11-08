

# Slot: release feature (coso_releaseFeature)


_A relation between an observation of a contaminant that was released and the feature where it was released._







URI: [coso:releaseFeature](http://w3id.org/coso/v1/contaminoso#releaseFeature)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[CosoReleaseFeature](../classes/CosoReleaseFeature.md)&nbsp;or&nbsp;<br />[GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[CosoFeature](../classes/CosoFeature.md)&nbsp;or&nbsp;<br />[SosaFeatureOfInterest](../classes/SosaFeatureOfInterest.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)







## LinkML Source

<details>

```yaml
name: coso_releaseFeature
description: A relation between an observation of a contaminant that was released
  and the feature where it was released.
title: release feature
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:releaseFeature
alias: coso_releaseFeature
subproperty_of: coso_hasFeatureOfInterest
union_of:
- coso_ContaminantObservation
- owl_Thing
- coso_ContaminantReleaseObservation
- sosa_Observation
range: Any
any_of:
- range: coso_ReleaseFeature
- range: geo_Feature
- range: owl_Thing
- range: coso_Feature
- range: sosa_FeatureOfInterest
- range: geo_SpatialObject

```
</details>