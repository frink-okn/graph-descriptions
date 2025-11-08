

# Slot: coso_hasMember




This slot occurs 13 times.


URI: [coso:hasMember](http://w3id.org/coso/v1/contaminoso#hasMember)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [CosoSubstanceCollection](../classes/CosoSubstanceCollection.md) | A collection of more than one substances |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName.md) |  |  no  |
| [Beb7217b5b32080b9606028314249e33b](../classes/Beb7217b5b32080b9606028314249e33b.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName.md)&nbsp;or&nbsp;<br />[Beb7217b5b32080b9606028314249e33b](../classes/Beb7217b5b32080b9606028314249e33b.md)







## LinkML Source

<details>

```yaml
name: coso_hasMember
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:hasMember
alias: coso_hasMember
domain_of:
- __Beb7217b5b32080b9606028314249e33b
- coso_SubstanceCollection
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-ParameterName
range: Any
any_of:
- range: owl_NamedIndividual
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-ParameterName
- range: __Beb7217b5b32080b9606028314249e33b

```
</details>