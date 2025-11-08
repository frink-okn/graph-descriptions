

# Class: Sampled Feature (coso_SampledFeature)


_The discrete spatial phenomenon that is the target of a sample observation._







URI: [coso:SampledFeature](http://w3id.org/coso/v1/contaminoso#SampledFeature)






```mermaid
 classDiagram
    class CosoSampledFeature
    click CosoSampledFeature href "../CosoSampledFeature"
      SosaFeatureOfInterest <|-- CosoSampledFeature
        click SosaFeatureOfInterest href "../SosaFeatureOfInterest"
      

      CosoSampledFeature <|-- HttpW3id.orgSawgraphV1Us-wqp#SampledFeature
        click HttpW3id.orgSawgraphV1Us-wqp#SampledFeature href "../HttpW3id.orgSawgraphV1Us-wqp#SampledFeature"
      
      
      
```





## Inheritance
* [SosaFeatureOfInterest](../classes/SosaFeatureOfInterest.md)
    * **CosoSampledFeature**
        * [HttpW3id.orgSawgraphV1Us-wqp#SampledFeature](../classes/HttpW3id.orgSawgraphV1Us-wqp#SampledFeature.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [CosoAnimalBloodSample](../classes/CosoAnimalBloodSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [CosoSampledFeature](../classes/CosoSampledFeature.md) |
| [CosoAnimalMaterialSample](../classes/CosoAnimalMaterialSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [CosoSampledFeature](../classes/CosoSampledFeature.md) |
| [CosoAnimalMilkSample](../classes/CosoAnimalMilkSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [CosoSampledFeature](../classes/CosoSampledFeature.md) |
| [CosoAnimalOrganSample](../classes/CosoAnimalOrganSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [CosoSampledFeature](../classes/CosoSampledFeature.md) |
| [CosoAnimalTissueSample](../classes/CosoAnimalTissueSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [CosoSampledFeature](../classes/CosoSampledFeature.md) |
| [CosoPlantMaterialSample](../classes/CosoPlantMaterialSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [CosoSampledFeature](../classes/CosoSampledFeature.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [CosoSampledFeature](../classes/CosoSampledFeature.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [CosoSampledFeature](../classes/CosoSampledFeature.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [CosoSampledFeature](../classes/CosoSampledFeature.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [CosoSampledFeature](../classes/CosoSampledFeature.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [CosoSampledFeature](../classes/CosoSampledFeature.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [CosoSampledFeature](../classes/CosoSampledFeature.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [CosoSampledFeature](../classes/CosoSampledFeature.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: coso_SampledFeature
description: The discrete spatial phenomenon that is the target of a sample observation.
title: Sampled Feature
from_schema: okns:sawgraph-kg
rank: 1000
is_a: sosa_FeatureOfInterest
class_uri: coso:SampledFeature

```
</details>

### Induced

<details>

```yaml
name: coso_SampledFeature
description: The discrete spatial phenomenon that is the target of a sample observation.
title: Sampled Feature
from_schema: okns:sawgraph-kg
rank: 1000
is_a: sosa_FeatureOfInterest
class_uri: coso:SampledFeature

```
</details>