

# Slot: is sample of (coso_isSampleOf)


_A relation between a physcial material sample and the geographic feature the sample was taken from._







URI: [coso:isSampleOf](http://w3id.org/coso/v1/contaminoso#isSampleOf)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[CosoSampledFeature](../classes/CosoSampledFeature.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)&nbsp;or&nbsp;<br />[SosaFeatureOfInterest](../classes/SosaFeatureOfInterest.md)&nbsp;or&nbsp;<br />[CosoFeature](../classes/CosoFeature.md)





## Comments

* No occurrences of this slot in the graph.



## LinkML Source

<details>

```yaml
name: coso_isSampleOf
description: A relation between a physcial material sample and the geographic feature
  the sample was taken from.
title: is sample of
comments:
- No occurrences of this slot in the graph.
from_schema: sawgraph-kg
rank: 1000
slot_uri: coso:isSampleOf
alias: coso_isSampleOf
subproperty_of: sosa_isSampleOf
union_of:
- '{''domain'': ''sosa_Sample''}'
- '{''domain'': ''owl_Thing''}'
- '{''domain'': ''coso_MaterialSample''}'
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