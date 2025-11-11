

# Slot: of substance (coso_ofSubstance)


_A relation between an observation of a contaminant and the substance or substances being observed._






This slot occurs 1153526 times.


URI: [coso:ofSubstance](http://w3id.org/coso/v1/contaminoso#ofSubstance)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) |  |  no  |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[CosoSubstanceCollection](../classes/CosoSubstanceCollection.md)&nbsp;or&nbsp;<br />[Beb7217b5b32080b9606028314249e33b](../classes/Beb7217b5b32080b9606028314249e33b.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName.md)&nbsp;or&nbsp;<br />[Ba76635ffb4afc02e78b9ef49973d089f](../classes/Ba76635ffb4afc02e78b9ef49973d089f.md)







## LinkML Source

<details>

```yaml
name: coso_ofSubstance
description: A relation between an observation of a contaminant and the substance
  or substances being observed.
title: of substance
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:ofSubstance
alias: coso_ofSubstance
domain_of:
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Observation
- me_egad_EGAD-PFAS-Observation
union_of:
- coso_ContaminantObservation
- owl_Thing
- sosa_Observation
range: Any
any_of:
- range: owl_NamedIndividual
- range: coso_SubstanceCollection
- range: __Beb7217b5b32080b9606028314249e33b
- range: owl_Thing
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-ParameterName
- range: __Ba76635ffb4afc02e78b9ef49973d089f

```
</details>