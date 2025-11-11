

# Slot: of Comptox Substance (coso_ofComptoxSubstance)


_A relation between an entity and a chemical substance as identified by Comptox_







URI: [coso:ofComptoxSubstance](http://w3id.org/coso/v1/contaminoso#ofComptoxSubstance)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpW3id.orgComptoxV1ChemicalEntity](../classes/HttpW3id.orgComptoxV1ChemicalEntity.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[HttpW3id.orgComptoxCompToxChemicalEntity](../classes/HttpW3id.orgComptoxCompToxChemicalEntity.md)&nbsp;or&nbsp;<br />[CosoSubstance](../classes/CosoSubstance.md)







## LinkML Source

<details>

```yaml
name: coso_ofComptoxSubstance
description: A relation between an entity and a chemical substance as identified by
  Comptox
title: of Comptox Substance
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:ofComptoxSubstance
alias: coso_ofComptoxSubstance
subproperty_of: coso_ofSubstance
union_of:
- coso_ContaminantObservation
- owl_Thing
- sosa_Observation
range: Any
any_of:
- range: http___w3id.org_comptox_v1_ChemicalEntity
- range: owl_Thing
- range: http___w3id.org_comptox_CompTox_ChemicalEntity
- range: coso_Substance

```
</details>