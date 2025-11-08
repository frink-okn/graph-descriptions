

# Slot: observed property (coso_observedProperty)


_A relation between an observation and the type of contamination property being observed._






This slot occurs 705437 times.


URI: [coso:observedProperty](http://w3id.org/coso/v1/contaminoso#observedProperty)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Us-wqp#Observation](../classes/HttpW3id.orgSawgraphV1Us-wqp#Observation.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[QudtQuantityKind](../classes/QudtQuantityKind.md)&nbsp;or&nbsp;<br />[CosoContaminantConcentrationQuantityKind](../classes/CosoContaminantConcentrationQuantityKind.md)&nbsp;or&nbsp;<br />[CosoContaminationProperty](../classes/CosoContaminationProperty.md)&nbsp;or&nbsp;<br />[StadQualityKind](../classes/StadQualityKind.md)&nbsp;or&nbsp;<br />[SosaProperty](../classes/SosaProperty.md)







## LinkML Source

<details>

```yaml
name: coso_observedProperty
description: A relation between an observation and the type of contamination property
  being observed.
title: observed property
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:observedProperty
alias: coso_observedProperty
domain_of:
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Observation
- http___w3id.org_sawgraph_v1_us-wqp#Observation
subproperty_of: sosa_observedProperty
union_of:
- coso_ContaminantObservation
- owl_Thing
- sosa_Observation
range: Any
any_of:
- range: owl_NamedIndividual
- range: owl_Thing
- range: qudt_QuantityKind
- range: coso_ContaminantConcentrationQuantityKind
- range: coso_ContaminationProperty
- range: stad_QualityKind
- range: sosa_Property

```
</details>