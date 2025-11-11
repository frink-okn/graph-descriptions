

# Slot: of Dataset Substance (coso_ofDatasetSubstance)


_A relation between an entity and a chemical substance as identified in a dataset specific controlled vocabulary_






This slot occurs 705437 times.


URI: [coso:ofDatasetSubstance](http://w3id.org/coso/v1/contaminoso#ofDatasetSubstance)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Us-wqp#Observation](../classes/HttpW3id.orgSawgraphV1Us-wqp#Observation.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[CosoSubstanceCollection](../classes/CosoSubstanceCollection.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#Characteristic](../classes/HttpW3id.orgSawgraphV1Us-wqp#Characteristic.md)&nbsp;or&nbsp;<br />[Beb7217b5b32080b9606028314249e33b](../classes/Beb7217b5b32080b9606028314249e33b.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName.md)







## LinkML Source

<details>

```yaml
name: coso_ofDatasetSubstance
description: A relation between an entity and a chemical substance as identified in
  a dataset specific controlled vocabulary
title: of Dataset Substance
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:ofDatasetSubstance
alias: coso_ofDatasetSubstance
domain_of:
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Observation
- http___w3id.org_sawgraph_v1_us-wqp#Observation
subproperty_of: coso_ofSubstance
union_of:
- coso_ContaminantObservation
- owl_Thing
- sosa_Observation
range: Any
any_of:
- range: owl_NamedIndividual
- range: coso_SubstanceCollection
- range: uri
- range: http___w3id.org_sawgraph_v1_us-wqp#Characteristic
- range: __Beb7217b5b32080b9606028314249e33b
- range: owl_Thing
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-ParameterName

```
</details>