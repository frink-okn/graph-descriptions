

# Class: EGAD - Method Detection Limit (me_egad_EGAD-MethodDetectionLimit)


_Areas with land use activities which are potential and/or actual sources of contamination and areas where biological and surface water sampling is conducted._







URI: [me_egad:EGAD-MethodDetectionLimit](http://sawgraph.spatialai.org/v1/me-egad#EGAD-MethodDetectionLimit)






```mermaid
 classDiagram
    class MeEgadEGAD-MethodDetectionLimit
    click MeEgadEGAD-MethodDetectionLimit href "../MeEgadEGAD-MethodDetectionLimit"
      CosoDetectionLimit <|-- MeEgadEGAD-MethodDetectionLimit
        click CosoDetectionLimit href "../CosoDetectionLimit"
      
      
```





## Inheritance
* [CosoDetectionLimit](../classes/CosoDetectionLimit.md)
    * **MeEgadEGAD-MethodDetectionLimit**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) | [me_egad_methodDetectionLimit](../slots/me_egad_methodDetectionLimit.md) | any_of[range] | [MeEgadEGAD-MethodDetectionLimit](../classes/MeEgadEGAD-MethodDetectionLimit.md) |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) | [me_egad_methodDetectionLimit](../slots/me_egad_methodDetectionLimit.md) | any_of[range] | [MeEgadEGAD-MethodDetectionLimit](../classes/MeEgadEGAD-MethodDetectionLimit.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: me_egad_EGAD-MethodDetectionLimit
conforms_to: No schema conformance document specified
description: Areas with land use activities which are potential and/or actual sources
  of contamination and areas where biological and surface water sampling is conducted.
title: EGAD - Method Detection Limit
from_schema: sawgraph-kg
rank: 1000
is_a: coso_DetectionLimit
class_uri: me_egad:EGAD-MethodDetectionLimit

```
</details>

### Induced

<details>

```yaml
name: me_egad_EGAD-MethodDetectionLimit
conforms_to: No schema conformance document specified
description: Areas with land use activities which are potential and/or actual sources
  of contamination and areas where biological and surface water sampling is conducted.
title: EGAD - Method Detection Limit
from_schema: sawgraph-kg
rank: 1000
is_a: coso_DetectionLimit
class_uri: me_egad:EGAD-MethodDetectionLimit

```
</details>