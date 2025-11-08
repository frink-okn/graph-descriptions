

# Class: Feature Type (coso_FeatureType)


_A category applied to differentiate discrete spatial phenomenon._







URI: [coso:FeatureType](http://w3id.org/coso/v1/contaminoso#FeatureType)






```mermaid
 classDiagram
    class CosoFeatureType
    click CosoFeatureType href "../CosoFeatureType"
      OwlThing <|-- CosoFeatureType
        click OwlThing href "../OwlThing"
      

      CosoFeatureType <|-- HttpW3id.orgSawgraphV1Us-wqp#LocationType
        click HttpW3id.orgSawgraphV1Us-wqp#LocationType href "../HttpW3id.orgSawgraphV1Us-wqp#LocationType"
      
      
      
```





## Inheritance
* [OwlThing](../classes/OwlThing.md)
    * **CosoFeatureType**
        * [HttpW3id.orgSawgraphV1Us-wqp#LocationType](../classes/HttpW3id.orgSawgraphV1Us-wqp#LocationType.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature.md) | [http___w3id.org_sawgraph_v1_me_egad#sampledFeatureType](../slots/http___w3id.org_sawgraph_v1_me_egad#sampledFeatureType.md) | any_of[range] | [CosoFeatureType](../classes/CosoFeatureType.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature.md) | [coso_ofFeatureType](../slots/coso_ofFeatureType.md) | any_of[range] | [CosoFeatureType](../classes/CosoFeatureType.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: coso_FeatureType
description: A category applied to differentiate discrete spatial phenomenon.
title: Feature Type
from_schema: okns:sawgraph-kg
rank: 1000
is_a: owl_Thing
class_uri: coso:FeatureType

```
</details>

### Induced

<details>

```yaml
name: coso_FeatureType
description: A category applied to differentiate discrete spatial phenomenon.
title: Feature Type
from_schema: okns:sawgraph-kg
rank: 1000
is_a: owl_Thing
class_uri: coso:FeatureType

```
</details>