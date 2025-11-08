

# Slot: applicable system (qudt_applicableSystem)


_This property relates a unit of measure with a unit system that may or may not define the unit, but within which the unit is compatible._






This slot occurs 28 times.


URI: [qudt:applicableSystem](http://qudt.org/schema/qudt/applicableSystem)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [QudtCurrencyUnit](../classes/QudtCurrencyUnit.md) | Currency Units have their own subclass of unit because: (a) they have additon... |  no  |
| [QudtPlaneAngleUnit](../classes/QudtPlaneAngleUnit.md) |  |  no  |
| [QudtDerivedUnit](../classes/QudtDerivedUnit.md) | A DerivedUnit is a type specification for units that are derived from other u... |  no  |
| [QudtSolidAngleUnit](../classes/QudtSolidAngleUnit.md) | The solid angle subtended by a surface S is defined as the surface area of a ... |  no  |
| [QudtUnit](../classes/QudtUnit.md) | A unit of measure, or unit, is a particular quantity value that has been chos... |  no  |
| [QudtCountingUnit](../classes/QudtCountingUnit.md) | Used for all units that express counts |  no  |
| [QudtContextualUnit](../classes/QudtContextualUnit.md) |  |  no  |
| [QudtAngleUnit](../classes/QudtAngleUnit.md) | All units relating to specification of angles |  no  |
| [QudtDimensionlessUnit](../classes/QudtDimensionlessUnit.md) | A Dimensionless Unit is a quantity for which all the exponents of the factors... |  no  |
| [QudtLogarithmicUnit](../classes/QudtLogarithmicUnit.md) | Logarithmic units are abstract mathematical units that can be used to express... |  no  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)







## LinkML Source

<details>

```yaml
name: qudt_applicableSystem
description: This property relates a unit of measure with a unit system that may or
  may not define the unit, but within which the unit is compatible.
title: applicable system
from_schema: okns:qudt
source: http://qudt.org/schema/qudt
slot_uri: qudt:applicableSystem
domain_of:
- qudt_ContextualUnit
- qudt_CountingUnit
- qudt_DerivedUnit
- qudt_DimensionlessUnit
- qudt_LogarithmicUnit
- qudt_Unit
range: uri

```
</details>