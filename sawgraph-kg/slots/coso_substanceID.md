

# Slot: substance identifier (coso_substanceID)


_The unique identifier for the substance._






This slot occurs 194 times.


URI: [coso:substanceID](http://w3id.org/coso/v1/contaminoso#substanceID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [CosoSubstanceCollection](../classes/CosoSubstanceCollection.md) | A collection of more than one substances |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName.md) |  |  no  |
| [Beb7217b5b32080b9606028314249e33b](../classes/Beb7217b5b32080b9606028314249e33b.md) |  |  no  |
| [Ba76635ffb4afc02e78b9ef49973d089f](../classes/Ba76635ffb4afc02e78b9ef49973d089f.md) |  |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)







## LinkML Source

<details>

```yaml
name: coso_substanceID
description: The unique identifier for the substance.
title: substance identifier
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:substanceID
alias: coso_substanceID
domain_of:
- __Ba76635ffb4afc02e78b9ef49973d089f
- __Beb7217b5b32080b9606028314249e33b
- coso_SubstanceCollection
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-ParameterName
subproperty_of: dct_identifier
range: string

```
</details>