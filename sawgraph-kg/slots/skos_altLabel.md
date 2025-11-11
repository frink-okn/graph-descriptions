

# Slot: alternative label (skos_altLabel)


_An alternative lexical label for a resource._






This slot occurs 16572 times.


URI: [skos:altLabel](http://www.w3.org/2004/02/skos/core#altLabel)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [QudtCurrencyUnit](../classes/QudtCurrencyUnit.md) | Currency Units have their own subclass of unit because: (a) they have additon... |  no  |
| [QudtPlaneAngleUnit](../classes/QudtPlaneAngleUnit.md) |  |  no  |
| [QudtDimensionlessUnit](../classes/QudtDimensionlessUnit.md) | A Dimensionless Unit is a quantity for which all the exponents of the factors... |  no  |
| [Beb7217b5b32080b9606028314249e33b](../classes/Beb7217b5b32080b9606028314249e33b.md) |  |  no  |
| [QudtDerivedUnit](../classes/QudtDerivedUnit.md) | A DerivedUnit is a type specification for units that are derived from other u... |  no  |
| [QudtSolidAngleUnit](../classes/QudtSolidAngleUnit.md) | The solid angle subtended by a surface S is defined as the surface area of a ... |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint.md) |  |  no  |
| [QudtUnit](../classes/QudtUnit.md) | A unit of measure, or unit, is a particular quantity value that has been chos... |  no  |
| [QudtLogarithmicUnit](../classes/QudtLogarithmicUnit.md) | Logarithmic units are abstract mathematical units that can be used to express... |  no  |
| [QudtCountingUnit](../classes/QudtCountingUnit.md) | Used for all units that express counts |  no  |
| [CosoSubstanceCollection](../classes/CosoSubstanceCollection.md) | A collection of more than one substances |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName.md) |  |  no  |
| [MeEgadEGAD-PFAS-ParameterName](../classes/MeEgadEGAD-PFAS-ParameterName.md) |  |  no  |
| [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md) |  |  no  |
| [QudtAngleUnit](../classes/QudtAngleUnit.md) | All units relating to specification of angles |  no  |
| [QudtContextualUnit](../classes/QudtContextualUnit.md) |  |  no  |
| [Ba76635ffb4afc02e78b9ef49973d089f](../classes/Ba76635ffb4afc02e78b9ef49973d089f.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)





## Comments

* description: skos:prefLabel, skos:altLabel and skos:hiddenLabel are pairwise disjoint properties.
* description: The range of skos:altLabel is the class of RDF plain literals.



## LinkML Source

<details>

```yaml
name: skos_altLabel
description: An alternative lexical label for a resource.
title: alternative label
notes:
- No occurrences of this slot in the graph.
comments:
- 'description: skos:prefLabel, skos:altLabel and skos:hiddenLabel are pairwise disjoint
  properties.'
- 'description: The range of skos:altLabel is the class of RDF plain literals.'
from_schema: okns:skos
source: http://www.w3.org/2004/02/skos/core
slot_uri: skos:altLabel
domain_of:
- qudt_CountingUnit
- qudt_DerivedUnit
- qudt_Unit
- __Ba76635ffb4afc02e78b9ef49973d089f
- __Beb7217b5b32080b9606028314249e33b
- coso_SubstanceCollection
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-ParameterName
- http___w3id.org_sawgraph_v1_me-egad#EGAD-SamplePoint
- me_egad_EGAD-PFAS-ParameterName
- me_egad_EGAD-SamplePoint
subproperty_of: rdfs_label
range: Any

```
</details>