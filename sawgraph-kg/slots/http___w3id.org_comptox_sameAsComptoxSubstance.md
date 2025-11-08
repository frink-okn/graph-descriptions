

# Slot: same as comptox substance (http___w3id.org_comptox_sameAsComptoxSubstance)


_A relation between an dataset specific substance and the same substance as identified in comptox._






This slot occurs 55 times.


URI: [http://w3id.org/comptox/sameAsComptoxSubstance](http://w3id.org/comptox/sameAsComptoxSubstance)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName.md) |  |  no  |
| [Beb7217b5b32080b9606028314249e33b](../classes/Beb7217b5b32080b9606028314249e33b.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[HttpW3id.orgComptoxCompToxChemicalEntity](../classes/HttpW3id.orgComptoxCompToxChemicalEntity.md)&nbsp;or&nbsp;<br />[CosoSubstance](../classes/CosoSubstance.md)&nbsp;or&nbsp;<br />[Beb7217b5b32080b9606028314249e33b](../classes/Beb7217b5b32080b9606028314249e33b.md)







## LinkML Source

<details>

```yaml
name: http___w3id.org_comptox_sameAsComptoxSubstance
description: A relation between an dataset specific substance and the same substance
  as identified in comptox.
title: same as comptox substance
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: http://w3id.org/comptox/sameAsComptoxSubstance
alias: http___w3id.org_comptox_sameAsComptoxSubstance
domain_of:
- __Beb7217b5b32080b9606028314249e33b
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-ParameterName
range: Any
any_of:
- range: owl_Thing
- range: http___w3id.org_comptox_CompTox_ChemicalEntity
- range: coso_Substance
- range: __Beb7217b5b32080b9606028314249e33b

```
</details>