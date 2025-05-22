

# Class: Feature (coso_Feature)


_No class (type) description specified_







URI: [coso:Feature](http://w3id.org/coso/v1/contaminoso#Feature)






```mermaid
 classDiagram
    class CosoFeature
    click CosoFeature href "../CosoFeature"
      SosaFeatureOfInterest <|-- CosoFeature
        click SosaFeatureOfInterest href "../SosaFeatureOfInterest"
      

      CosoFeature <|-- CosoReleaseFeature
        click CosoReleaseFeature href "../CosoReleaseFeature"
      
      
      
```





## Inheritance
* [SosaFeatureOfInterest](../classes/SosaFeatureOfInterest.md)
    * **CosoFeature**
        * [CosoReleaseFeature](../classes/CosoReleaseFeature.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | [coso_hasFeatureOfInterest](../slots/coso_hasFeatureOfInterest.md) | any_of[range] | [CosoFeature](../classes/CosoFeature.md) |
| [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md) | [coso_pointFromFeature](../slots/coso_pointFromFeature.md) | any_of[range] | [CosoFeature](../classes/CosoFeature.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: coso_Feature
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: Feature
from_schema: sawgraph-kg
rank: 1000
is_a: sosa_FeatureOfInterest
class_uri: coso:Feature

```
</details>

### Induced

<details>

```yaml
name: coso_Feature
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: Feature
from_schema: sawgraph-kg
rank: 1000
is_a: sosa_FeatureOfInterest
class_uri: coso:Feature

```
</details>