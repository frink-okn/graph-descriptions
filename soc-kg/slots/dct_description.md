

# Slot: Description (dct_description)


_Description may include but is not limited to: an abstract, a table of contents, a graphical representation, or a free-text account of the resource._






This slot occurs 1230 times.


URI: [dct:description](http://purl.org/dc/terms/description)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [QudtDerivedUnit](../classes/QudtDerivedUnit.md) | A DerivedUnit is a type specification for units that are derived from other u... |  no  |
| [QudtBinaryPrefix](../classes/QudtBinaryPrefix.md) | A <em>Binary Prefix</em> is a prefix for multiples of units in data processin... |  no  |
| [QudtLogarithmicUnit](../classes/QudtLogarithmicUnit.md) | Logarithmic units are abstract mathematical units that can be used to express... |  no  |
| [QudtContextualUnit](../classes/QudtContextualUnit.md) |  |  no  |
| [QudtCardinalityType](../classes/QudtCardinalityType.md) | In mathematics, the cardinality of a set is a measure of the number of elemen... |  no  |
| [HttpsIdir.uta.eduSockg-ontology#FertilizerAmendment](../classes/HttpsIdir.uta.eduSockg-ontology#FertilizerAmendment.md) |  |  no  |
| [QudtUnit](../classes/QudtUnit.md) | A unit of measure, or unit, is a particular quantity value that has been chos... |  no  |
| [HttpsIdir.uta.eduSockg-ontology#ProjectScenario](../classes/HttpsIdir.uta.eduSockg-ontology#ProjectScenario.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#Rotation](../classes/HttpsIdir.uta.eduSockg-ontology#Rotation.md) |  |  no  |
| [QudtSolidAngleUnit](../classes/QudtSolidAngleUnit.md) | The solid angle subtended by a surface S is defined as the surface area of a ... |  no  |
| [QudtCountingUnit](../classes/QudtCountingUnit.md) | Used for all units that express counts |  no  |
| [HttpsIdir.uta.eduSockg-ontology#Timing](../classes/HttpsIdir.uta.eduSockg-ontology#Timing.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#Project](../classes/HttpsIdir.uta.eduSockg-ontology#Project.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#CoverCrop](../classes/HttpsIdir.uta.eduSockg-ontology#CoverCrop.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#Location](../classes/HttpsIdir.uta.eduSockg-ontology#Location.md) |  |  no  |
| [QudtPlaneAngleUnit](../classes/QudtPlaneAngleUnit.md) |  |  no  |
| [QudtAngleUnit](../classes/QudtAngleUnit.md) | All units relating to specification of angles |  no  |
| [VaemGraphRole](../classes/VaemGraphRole.md) | GraphRole is used to characterize how a graph of resources participates in an... |  no  |
| [QudtDimensionlessUnit](../classes/QudtDimensionlessUnit.md) | A Dimensionless Unit is a quantity for which all the exponents of the factors... |  no  |
| [QudtDecimalPrefix](../classes/QudtDecimalPrefix.md) | A <em>Decimal Prefix</em> is a prefix for multiples of units that are powers ... |  no  |
| [HttpsIdir.uta.eduSockg-ontology#ResidueRemoval](../classes/HttpsIdir.uta.eduSockg-ontology#ResidueRemoval.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#Thesis](../classes/HttpsIdir.uta.eduSockg-ontology#Thesis.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#GrazingRate](../classes/HttpsIdir.uta.eduSockg-ontology#GrazingRate.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#AnimalSpecies](../classes/HttpsIdir.uta.eduSockg-ontology#AnimalSpecies.md) |  |  no  |
| [QudtCurrencyUnit](../classes/QudtCurrencyUnit.md) | Currency Units have their own subclass of unit because: (a) they have additon... |  no  |
| [HttpsIdir.uta.eduSockg-ontology#Tillage](../classes/HttpsIdir.uta.eduSockg-ontology#Tillage.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#Proceedings](../classes/HttpsIdir.uta.eduSockg-ontology#Proceedings.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#JournalArticle](../classes/HttpsIdir.uta.eduSockg-ontology#JournalArticle.md) |  |  no  |
| [HttpsIdir.uta.eduSockg-ontology#Treatment](../classes/HttpsIdir.uta.eduSockg-ontology#Treatment.md) |  |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)





## Comments

* description: An account of the resource.



## LinkML Source

<details>

```yaml
name: dct_description
description: 'Description may include but is not limited to: an abstract, a table
  of contents, a graphical representation, or a free-text account of the resource.'
title: Description
comments:
- 'description: An account of the resource.'
from_schema: okns:dc
source: http://purl.org/dc/terms/
slot_uri: dct:description
domain_of:
- qudt_BinaryPrefix
- qudt_CardinalityType
- qudt_ContextualUnit
- qudt_CountingUnit
- qudt_DecimalPrefix
- qudt_DerivedUnit
- qudt_DimensionlessUnit
- qudt_LogarithmicUnit
- qudt_Unit
- vaem_GraphRole
- https___idir.uta.edu_sockg-ontology#AnimalSpecies
- https___idir.uta.edu_sockg-ontology#CoverCrop
- https___idir.uta.edu_sockg-ontology#FertilizerAmendment
- https___idir.uta.edu_sockg-ontology#GrazingRate
- https___idir.uta.edu_sockg-ontology#JournalArticle
- https___idir.uta.edu_sockg-ontology#Location
- https___idir.uta.edu_sockg-ontology#Proceedings
- https___idir.uta.edu_sockg-ontology#Project
- https___idir.uta.edu_sockg-ontology#ProjectScenario
- https___idir.uta.edu_sockg-ontology#ResidueRemoval
- https___idir.uta.edu_sockg-ontology#Rotation
- https___idir.uta.edu_sockg-ontology#Thesis
- https___idir.uta.edu_sockg-ontology#Tillage
- https___idir.uta.edu_sockg-ontology#Timing
- https___idir.uta.edu_sockg-ontology#Treatment
subproperty_of: dc_description
range: string

```
</details>