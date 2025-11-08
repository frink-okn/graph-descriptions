

# Slot: Description (dct_description)


_Description may include but is not limited to: an abstract, a table of contents, a graphical representation, or a free-text account of the resource._






This slot occurs 6 times.


URI: [dct:description](http://purl.org/dc/terms/description)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [QudtCurrencyUnit](../classes/QudtCurrencyUnit.md) | Currency Units have their own subclass of unit because: (a) they have additon... |  no  |
| [QudtPlaneAngleUnit](../classes/QudtPlaneAngleUnit.md) |  |  no  |
| [QudtCardinalityType](../classes/QudtCardinalityType.md) | In mathematics, the cardinality of a set is a measure of the number of elemen... |  no  |
| [VaemGraphRole](../classes/VaemGraphRole.md) | GraphRole is used to characterize how a graph of resources participates in an... |  no  |
| [QudtDerivedUnit](../classes/QudtDerivedUnit.md) | A DerivedUnit is a type specification for units that are derived from other u... |  no  |
| [QudtSolidAngleUnit](../classes/QudtSolidAngleUnit.md) | The solid angle subtended by a surface S is defined as the surface area of a ... |  no  |
| [QudtUnit](../classes/QudtUnit.md) | A unit of measure, or unit, is a particular quantity value that has been chos... |  no  |
| [QudtContextualUnit](../classes/QudtContextualUnit.md) |  |  no  |
| [QudtCountingUnit](../classes/QudtCountingUnit.md) | Used for all units that express counts |  no  |
| [QudtAngleUnit](../classes/QudtAngleUnit.md) | All units relating to specification of angles |  no  |
| [QudtDimensionlessUnit](../classes/QudtDimensionlessUnit.md) | A Dimensionless Unit is a quantity for which all the exponents of the factors... |  no  |
| [QudtBinaryPrefix](../classes/QudtBinaryPrefix.md) | A <em>Binary Prefix</em> is a prefix for multiples of units in data processin... |  no  |
| [QudtLogarithmicUnit](../classes/QudtLogarithmicUnit.md) | Logarithmic units are abstract mathematical units that can be used to express... |  no  |
| [QudtDecimalPrefix](../classes/QudtDecimalPrefix.md) | A <em>Decimal Prefix</em> is a prefix for multiples of units that are powers ... |  no  |







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
subproperty_of: dc_description
range: string

```
</details>