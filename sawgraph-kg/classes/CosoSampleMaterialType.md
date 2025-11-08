

# Class: Sample Material Type (coso_SampleMaterialType)


_The type of material that was sampled_







URI: [coso:SampleMaterialType](http://w3id.org/coso/v1/contaminoso#SampleMaterialType)






```mermaid
 classDiagram
    class CosoSampleMaterialType
    click CosoSampleMaterialType href "../CosoSampleMaterialType"
      OwlThing <|-- CosoSampleMaterialType
        click OwlThing href "../OwlThing"
      

      CosoSampleMaterialType <|-- HttpW3id.orgSawgraphV1Us-wqp#SampleMedia
        click HttpW3id.orgSawgraphV1Us-wqp#SampleMedia href "../HttpW3id.orgSawgraphV1Us-wqp#SampleMedia"
      CosoSampleMaterialType <|-- HttpW3id.orgSawgraphV1Us-wqp#Taxon
        click HttpW3id.orgSawgraphV1Us-wqp#Taxon href "../HttpW3id.orgSawgraphV1Us-wqp#Taxon"
      
      
      
```





## Inheritance
* [OwlThing](../classes/OwlThing.md)
    * **CosoSampleMaterialType**
        * [HttpW3id.orgSawgraphV1Us-wqp#SampleMedia](../classes/HttpW3id.orgSawgraphV1Us-wqp#SampleMedia.md)
        * [HttpW3id.orgSawgraphV1Us-wqp#Taxon](../classes/HttpW3id.orgSawgraphV1Us-wqp#Taxon.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [CosoAnimalBloodSample](../classes/CosoAnimalBloodSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [CosoSampleMaterialType](../classes/CosoSampleMaterialType.md) |
| [CosoAnimalMaterialSample](../classes/CosoAnimalMaterialSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [CosoSampleMaterialType](../classes/CosoSampleMaterialType.md) |
| [CosoAnimalMilkSample](../classes/CosoAnimalMilkSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [CosoSampleMaterialType](../classes/CosoSampleMaterialType.md) |
| [CosoAnimalOrganSample](../classes/CosoAnimalOrganSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [CosoSampleMaterialType](../classes/CosoSampleMaterialType.md) |
| [CosoAnimalTissueSample](../classes/CosoAnimalTissueSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [CosoSampleMaterialType](../classes/CosoSampleMaterialType.md) |
| [CosoPlantMaterialSample](../classes/CosoPlantMaterialSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [CosoSampleMaterialType](../classes/CosoSampleMaterialType.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [CosoSampleMaterialType](../classes/CosoSampleMaterialType.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [CosoSampleMaterialType](../classes/CosoSampleMaterialType.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [CosoSampleMaterialType](../classes/CosoSampleMaterialType.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [CosoSampleMaterialType](../classes/CosoSampleMaterialType.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [CosoSampleMaterialType](../classes/CosoSampleMaterialType.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [CosoSampleMaterialType](../classes/CosoSampleMaterialType.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [CosoSampleMaterialType](../classes/CosoSampleMaterialType.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#Sample](../classes/HttpW3id.orgSawgraphV1Us-wqp#Sample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [CosoSampleMaterialType](../classes/CosoSampleMaterialType.md) |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [CosoSampleMaterialType](../classes/CosoSampleMaterialType.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: coso_SampleMaterialType
description: The type of material that was sampled
title: Sample Material Type
from_schema: okns:sawgraph-kg
rank: 1000
is_a: owl_Thing
class_uri: coso:SampleMaterialType

```
</details>

### Induced

<details>

```yaml
name: coso_SampleMaterialType
description: The type of material that was sampled
title: Sample Material Type
from_schema: okns:sawgraph-kg
rank: 1000
is_a: owl_Thing
class_uri: coso:SampleMaterialType

```
</details>