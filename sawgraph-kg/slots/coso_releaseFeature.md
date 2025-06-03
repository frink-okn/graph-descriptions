

# Slot: release feature (coso_releaseFeature)


_A relation between an observation of a contaminant that was released and the feature where it was released._







URI: [coso:releaseFeature](http://w3id.org/coso/v1/contaminoso#releaseFeature)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[CosoReleaseFeature](../classes/CosoReleaseFeature.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)&nbsp;or&nbsp;<br />[SosaFeatureOfInterest](../classes/SosaFeatureOfInterest.md)&nbsp;or&nbsp;<br />[CosoFeature](../classes/CosoFeature.md)





## Comments

* No occurrences of this slot in the graph.



## LinkML Source

<details>

```yaml
name: coso_releaseFeature
description: A relation between an observation of a contaminant that was released
  and the feature where it was released.
title: release feature
comments:
- No occurrences of this slot in the graph.
from_schema: sawgraph-kg
rank: 1000
slot_uri: coso:releaseFeature
alias: coso_releaseFeature
subproperty_of: coso_hasFeatureOfInterest
union_of:
- '{''domain'': ''owl_Thing''}'
- '{''domain'': ''sosa_Observation''}'
- '{''domain'': ''coso_ContaminantReleaseObservation''}'
- '{''domain'': ''coso_ContaminantObservation''}'
range: Any
any_of:
- range: owl_Thing
- range: geo_Feature
- range: coso_ReleaseFeature
- range: geo_SpatialObject
- range: sosa_FeatureOfInterest
- range: coso_Feature

```
</details>