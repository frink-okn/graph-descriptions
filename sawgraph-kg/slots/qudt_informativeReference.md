

# Slot: informative reference (qudt_informativeReference)


_Provides a way to reference a source that provided useful but non-normative information._






This slot occurs 2 times.


URI: [qudt:informativeReference](http://qudt.org/schema/qudt/informativeReference)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [QudtCurrencyUnit](../classes/QudtCurrencyUnit.md) | Currency Units have their own subclass of unit because: (a) they have additon... |  no  |
| [QudtPlaneAngleUnit](../classes/QudtPlaneAngleUnit.md) |  |  no  |
| [QudtDerivedUnit](../classes/QudtDerivedUnit.md) | A DerivedUnit is a type specification for units that are derived from other u... |  no  |
| [QudtSolidAngleUnit](../classes/QudtSolidAngleUnit.md) | The solid angle subtended by a surface S is defined as the surface area of a ... |  no  |
| [QudtUnit](../classes/QudtUnit.md) | A unit of measure, or unit, is a particular quantity value that has been chos... |  no  |
| [QudtDecimalPrefix](../classes/QudtDecimalPrefix.md) | A <em>Decimal Prefix</em> is a prefix for multiples of units that are powers ... |  no  |
| [QudtCountingUnit](../classes/QudtCountingUnit.md) | Used for all units that express counts |  no  |
| [QudtContextualUnit](../classes/QudtContextualUnit.md) |  |  no  |
| [QudtAngleUnit](../classes/QudtAngleUnit.md) | All units relating to specification of angles |  no  |
| [QudtDimensionlessUnit](../classes/QudtDimensionlessUnit.md) | A Dimensionless Unit is a quantity for which all the exponents of the factors... |  no  |
| [QudtLogarithmicUnit](../classes/QudtLogarithmicUnit.md) | Logarithmic units are abstract mathematical units that can be used to express... |  no  |
| [QudtCardinalityType](../classes/QudtCardinalityType.md) | In mathematics, the cardinality of a set is a measure of the number of elemen... |  no  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)







## LinkML Source

<details>

```yaml
name: qudt_informativeReference
description: Provides a way to reference a source that provided useful but non-normative
  information.
title: informative reference
from_schema: okns:qudt
source: http://qudt.org/schema/qudt
slot_uri: qudt:informativeReference
domain_of:
- qudt_CardinalityType
- qudt_ContextualUnit
- qudt_CountingUnit
- qudt_CurrencyUnit
- qudt_DecimalPrefix
- qudt_DerivedUnit
- qudt_DimensionlessUnit
- qudt_LogarithmicUnit
- qudt_Unit
range: uri

```
</details>