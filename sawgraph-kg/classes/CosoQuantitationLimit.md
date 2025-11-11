

# Class: Quantitation Limit (coso_QuantitationLimit)


_The lowest concentration of a substance that can be reliably measured with acceptable precision and accuracy._







URI: [coso:QuantitationLimit](http://w3id.org/coso/v1/contaminoso#QuantitationLimit)






```mermaid
 classDiagram
    class CosoQuantitationLimit
    click CosoQuantitationLimit href "../CosoQuantitationLimit"
      OwlThing <|-- CosoQuantitationLimit
        click OwlThing href "../OwlThing"
      
      
```





## Inheritance
* [OwlThing](../classes/OwlThing.md)
    * **CosoQuantitationLimit**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration.md) | [http___w3id.org_sawgraph_v1_me_egad#reportingLimit](../slots/http___w3id.org_sawgraph_v1_me_egad#reportingLimit.md) | any_of[range] | [CosoQuantitationLimit](../classes/CosoQuantitationLimit.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration.md) | [http___w3id.org_sawgraph_v1_me_egad#reportingLimit](../slots/http___w3id.org_sawgraph_v1_me_egad#reportingLimit.md) | any_of[range] | [CosoQuantitationLimit](../classes/CosoQuantitationLimit.md) |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) | [me_egad_reportingLimit](../slots/me_egad_reportingLimit.md) | any_of[range] | [CosoQuantitationLimit](../classes/CosoQuantitationLimit.md) |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) | [me_egad_reportingLimit](../slots/me_egad_reportingLimit.md) | any_of[range] | [CosoQuantitationLimit](../classes/CosoQuantitationLimit.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: coso_QuantitationLimit
description: The lowest concentration of a substance that can be reliably measured
  with acceptable precision and accuracy.
title: Quantitation Limit
from_schema: okns:sawgraph-kg
rank: 1000
is_a: owl_Thing
class_uri: coso:QuantitationLimit

```
</details>

### Induced

<details>

```yaml
name: coso_QuantitationLimit
description: The lowest concentration of a substance that can be reliably measured
  with acceptable precision and accuracy.
title: Quantitation Limit
from_schema: okns:sawgraph-kg
rank: 1000
is_a: owl_Thing
class_uri: coso:QuantitationLimit

```
</details>