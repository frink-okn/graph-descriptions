

# Slot: seeAlso (rdfs_seeAlso)


_Further information about the subject resource._






This slot occurs 6 times.


URI: [rdfs:seeAlso](http://www.w3.org/2000/01/rdf-schema#seeAlso)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [QudtCurrencyUnit](../classes/QudtCurrencyUnit.md) | Currency Units have their own subclass of unit because: (a) they have additon... |  no  |
| [QudtPlaneAngleUnit](../classes/QudtPlaneAngleUnit.md) |  |  no  |
| [QudtDerivedUnit](../classes/QudtDerivedUnit.md) | A DerivedUnit is a type specification for units that are derived from other u... |  no  |
| [QudtSolidAngleUnit](../classes/QudtSolidAngleUnit.md) | The solid angle subtended by a surface S is defined as the surface area of a ... |  no  |
| [RdfsDatatype](../classes/RdfsDatatype.md) | The class of RDF datatypes |  no  |
| [QudtUnit](../classes/QudtUnit.md) | A unit of measure, or unit, is a particular quantity value that has been chos... |  no  |
| [OwlDataRange](../classes/OwlDataRange.md) | The class of OWL data ranges, which are special kinds of datatypes |  no  |
| [DcamVocabularyEncodingScheme](../classes/DcamVocabularyEncodingScheme.md) | An enumerated set of resources |  no  |
| [QudtContextualUnit](../classes/QudtContextualUnit.md) |  |  no  |
| [QudtCountingUnit](../classes/QudtCountingUnit.md) | Used for all units that express counts |  no  |
| [QudtAngleUnit](../classes/QudtAngleUnit.md) | All units relating to specification of angles |  no  |
| [QudtDimensionlessUnit](../classes/QudtDimensionlessUnit.md) | A Dimensionless Unit is a quantity for which all the exponents of the factors... |  no  |
| [QudtLogarithmicUnit](../classes/QudtLogarithmicUnit.md) | Logarithmic units are abstract mathematical units that can be used to express... |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)







## LinkML Source

<details>

```yaml
name: rdfs_seeAlso
description: Further information about the subject resource.
title: seeAlso
from_schema: okns:owl-rdf-rdfs
source: http://www.w3.org/2000/01/rdf-schema#
domain: rdfs_Resource
slot_uri: rdfs:seeAlso
domain_of:
- dcam_VocabularyEncodingScheme
- rdfs_Datatype
- qudt_DerivedUnit
- qudt_Unit
range: Any
any_of:
- range: rdfs_Resource
- range: uri

```
</details>