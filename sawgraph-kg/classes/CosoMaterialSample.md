

# Class: No class (entity type) name specified -- this class is noted as a superclass of another class in this graph but has not itself been defined. (coso_MaterialSample)


_No class (type) description specified_







URI: [coso:MaterialSample](http://w3id.org/coso/v1/contaminoso#MaterialSample)






```mermaid
 classDiagram
    class CosoMaterialSample
    click CosoMaterialSample href "../CosoMaterialSample"
      CosoMaterialSample <|-- MeEgadEGAD-Sample
        click MeEgadEGAD-Sample href "../MeEgadEGAD-Sample"
      
      
```





## Inheritance
* **CosoMaterialSample**
    * [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | [coso_analyzedSample](../slots/coso_analyzedSample.md) | any_of[range] | [CosoMaterialSample](../classes/CosoMaterialSample.md) |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) | [coso_fromSamplePoint](../slots/coso_fromSamplePoint.md) | domain | [CosoMaterialSample](../classes/CosoMaterialSample.md) |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | domain | [CosoMaterialSample](../classes/CosoMaterialSample.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: coso_MaterialSample
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: sawgraph-kg
rank: 1000
class_uri: coso:MaterialSample

```
</details>

### Induced

<details>

```yaml
name: coso_MaterialSample
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: sawgraph-kg
rank: 1000
class_uri: coso:MaterialSample

```
</details>