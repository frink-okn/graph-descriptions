

# Class: Result Qualifier (coso_ResultQualifier)


_Something that qualifies the result, such as quality control assessment, limitation on the precision or minimum detectable amount._







URI: [coso:ResultQualifier](http://w3id.org/coso/v1/contaminoso#ResultQualifier)






```mermaid
 classDiagram
    class CosoResultQualifier
    click CosoResultQualifier href "../CosoResultQualifier"
      OwlThing <|-- CosoResultQualifier
        click OwlThing href "../OwlThing"
      
      
```





## Inheritance
* [OwlThing](../classes/OwlThing.md)
    * **CosoResultQualifier**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration.md) | [http___w3id.org_sawgraph_v1_me_egad#methodDetectionLimit](../slots/http___w3id.org_sawgraph_v1_me_egad#methodDetectionLimit.md) | any_of[range] | [CosoResultQualifier](../classes/CosoResultQualifier.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration.md) | [http___w3id.org_sawgraph_v1_me_egad#reportingLimit](../slots/http___w3id.org_sawgraph_v1_me_egad#reportingLimit.md) | any_of[range] | [CosoResultQualifier](../classes/CosoResultQualifier.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration.md) | [http___w3id.org_sawgraph_v1_me_egad#methodDetectionLimit](../slots/http___w3id.org_sawgraph_v1_me_egad#methodDetectionLimit.md) | any_of[range] | [CosoResultQualifier](../classes/CosoResultQualifier.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration.md) | [http___w3id.org_sawgraph_v1_me_egad#reportingLimit](../slots/http___w3id.org_sawgraph_v1_me_egad#reportingLimit.md) | any_of[range] | [CosoResultQualifier](../classes/CosoResultQualifier.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration.md) | [coso_hasResultQualifier](../slots/coso_hasResultQualifier.md) | any_of[range] | [CosoResultQualifier](../classes/CosoResultQualifier.md) |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) | [me_egad_methodDetectionLimit](../slots/me_egad_methodDetectionLimit.md) | any_of[range] | [CosoResultQualifier](../classes/CosoResultQualifier.md) |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) | [me_egad_reportingLimit](../slots/me_egad_reportingLimit.md) | any_of[range] | [CosoResultQualifier](../classes/CosoResultQualifier.md) |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) | [me_egad_methodDetectionLimit](../slots/me_egad_methodDetectionLimit.md) | any_of[range] | [CosoResultQualifier](../classes/CosoResultQualifier.md) |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) | [me_egad_reportingLimit](../slots/me_egad_reportingLimit.md) | any_of[range] | [CosoResultQualifier](../classes/CosoResultQualifier.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: coso_ResultQualifier
description: Something that qualifies the result, such as quality control assessment,
  limitation on the precision or minimum detectable amount.
title: Result Qualifier
from_schema: okns:sawgraph-kg
rank: 1000
is_a: owl_Thing
class_uri: coso:ResultQualifier

```
</details>

### Induced

<details>

```yaml
name: coso_ResultQualifier
description: Something that qualifies the result, such as quality control assessment,
  limitation on the precision or minimum detectable amount.
title: Result Qualifier
from_schema: okns:sawgraph-kg
rank: 1000
is_a: owl_Thing
class_uri: coso:ResultQualifier

```
</details>