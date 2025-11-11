

# Slot: of feature type (coso_ofFeatureType)


_A relation between a feature and a controlled vocabulary term that describes the type of feature_






This slot occurs 8021 times.


URI: [coso:ofFeatureType](http://w3id.org/coso/v1/contaminoso#ofFeatureType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePointType](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePointType.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[CosoFeatureType](../classes/CosoFeatureType.md)







## LinkML Source

<details>

```yaml
name: coso_ofFeatureType
description: A relation between a feature and a controlled vocabulary term that describes
  the type of feature
title: of feature type
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:ofFeatureType
alias: coso_ofFeatureType
domain_of:
- http___w3id.org_sawgraph_v1_me-egad#EGAD-SampledFeature
range: Any
any_of:
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SamplePointType
- range: owl_Thing
- range: owl_NamedIndividual
- range: coso_FeatureType

```
</details>