

# Slot: stad_hasQualityKind




This slot occurs 576776 times.


URI: [stad:hasQualityKind](http://purl.org/spatialai/stad/v2/core/hasQualityKind)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[QudtQuantityKind](../classes/QudtQuantityKind.md)&nbsp;or&nbsp;<br />[CosoContaminantConcentrationQuantityKind](../classes/CosoContaminantConcentrationQuantityKind.md)&nbsp;or&nbsp;<br />[CosoContaminationProperty](../classes/CosoContaminationProperty.md)&nbsp;or&nbsp;<br />[StadQualityKind](../classes/StadQualityKind.md)







## LinkML Source

<details>

```yaml
name: stad_hasQualityKind
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: stad:hasQualityKind
alias: stad_hasQualityKind
domain_of:
- http___w3id.org_sawgraph_v1_me-egad#EGAD-AggregatePFAS-Concentration
- http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
range: Any
any_of:
- range: owl_NamedIndividual
- range: qudt_QuantityKind
- range: coso_ContaminantConcentrationQuantityKind
- range: coso_ContaminationProperty
- range: stad_QualityKind

```
</details>