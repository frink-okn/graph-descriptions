

# Class: No class (entity type) name specified -- this class is noted as a superclass of another class in this graph but has not itself been defined. (coso_SamplePoint)


_No class (type) description specified_







URI: [coso:SamplePoint](http://w3id.org/coso/v1/contaminoso#SamplePoint)






```mermaid
 classDiagram
    class CosoSamplePoint
    click CosoSamplePoint href "../CosoSamplePoint"
      CosoSamplePoint <|-- MeEgadEGAD-SamplePoint
        click MeEgadEGAD-SamplePoint href "../MeEgadEGAD-SamplePoint"
      
      
```





## Inheritance
* **CosoSamplePoint**
    * [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | [coso_observedAtSamplePoint](../slots/coso_observedAtSamplePoint.md) | any_of[range] | [CosoSamplePoint](../classes/CosoSamplePoint.md) |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) | [coso_fromSamplePoint](../slots/coso_fromSamplePoint.md) | any_of[range] | [CosoSamplePoint](../classes/CosoSamplePoint.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: coso_SamplePoint
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: sawgraph-kg
rank: 1000
class_uri: coso:SamplePoint

```
</details>

### Induced

<details>

```yaml
name: coso_SamplePoint
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (entity type) name specified -- this class is noted as a superclass
  of another class in this graph but has not itself been defined.
from_schema: sawgraph-kg
rank: 1000
class_uri: coso:SamplePoint

```
</details>