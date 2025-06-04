

# Slot: observed at release point (coso_observedAtReleasePoint)


_A relation between an observation of a contaminant that was released and the point where the observation was made and where the release occurred._







URI: [coso:observedAtReleasePoint](http://w3id.org/coso/v1/contaminoso#observedAtReleasePoint)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[CosoReleasePoint](../classes/CosoReleasePoint.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)&nbsp;or&nbsp;<br />[SosaFeatureOfInterest](../classes/SosaFeatureOfInterest.md)&nbsp;or&nbsp;<br />[CosoPoint](../classes/CosoPoint.md)





## Comments

* No occurrences of this slot in the graph.



## LinkML Source

<details>

```yaml
name: coso_observedAtReleasePoint
description: A relation between an observation of a contaminant that was released
  and the point where the observation was made and where the release occurred.
title: observed at release point
comments:
- No occurrences of this slot in the graph.
from_schema: sawgraph-kg
rank: 1000
slot_uri: coso:observedAtReleasePoint
alias: coso_observedAtReleasePoint
subproperty_of: coso_observedAtPoint
union_of:
- '{''domain'': ''owl_Thing''}'
- '{''domain'': ''sosa_Observation''}'
- '{''domain'': ''coso_ContaminantReleaseObservation''}'
- '{''domain'': ''coso_ContaminantObservation''}'
range: Any
any_of:
- range: owl_Thing
- range: geo_Feature
- range: coso_ReleasePoint
- range: geo_SpatialObject
- range: sosa_FeatureOfInterest
- range: coso_Point

```
</details>