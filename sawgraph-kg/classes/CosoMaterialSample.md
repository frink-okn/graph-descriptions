

# Class: Material Sample (coso_MaterialSample)


_A physical, tangible sample._







URI: [coso:MaterialSample](http://w3id.org/coso/v1/contaminoso#MaterialSample)






```mermaid
 classDiagram
    class CosoMaterialSample
    click CosoMaterialSample href "../CosoMaterialSample"
      SosaSample <|-- CosoMaterialSample
        click SosaSample href "../SosaSample"
      

      CosoMaterialSample <|-- CosoAirSample
        click CosoAirSample href "../CosoAirSample"
      CosoMaterialSample <|-- CosoSolidMaterialSample
        click CosoSolidMaterialSample href "../CosoSolidMaterialSample"
      CosoMaterialSample <|-- HttpW3id.orgSawgraphV1Us-wqp#Sample
        click HttpW3id.orgSawgraphV1Us-wqp#Sample href "../HttpW3id.orgSawgraphV1Us-wqp#Sample"
      
      
      
```





## Inheritance
* [OwlThing](../classes/OwlThing.md)
    * [SosaSample](../classes/SosaSample.md)
        * **CosoMaterialSample**
            * [CosoAirSample](../classes/CosoAirSample.md)
            * [CosoSolidMaterialSample](../classes/CosoSolidMaterialSample.md)
            * [HttpW3id.orgSawgraphV1Us-wqp#Sample](../classes/HttpW3id.orgSawgraphV1Us-wqp#Sample.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) | [coso_analyzedSample](../slots/coso_analyzedSample.md) | any_of[range] | [CosoMaterialSample](../classes/CosoMaterialSample.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#Observation](../classes/HttpW3id.orgSawgraphV1Us-wqp#Observation.md) | [coso_analyzedSample](../slots/coso_analyzedSample.md) | any_of[range] | [CosoMaterialSample](../classes/CosoMaterialSample.md) |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | [coso_analyzedSample](../slots/coso_analyzedSample.md) | any_of[range] | [CosoMaterialSample](../classes/CosoMaterialSample.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: coso_MaterialSample
description: A physical, tangible sample.
title: Material Sample
from_schema: okns:sawgraph-kg
rank: 1000
is_a: sosa_Sample
class_uri: coso:MaterialSample

```
</details>

### Induced

<details>

```yaml
name: coso_MaterialSample
description: A physical, tangible sample.
title: Material Sample
from_schema: okns:sawgraph-kg
rank: 1000
is_a: sosa_Sample
class_uri: coso:MaterialSample

```
</details>