

# Slot: unece common code (qudt_uneceCommonCode)


_The UN/CEFACT Recommendation 20 provides three character alphabetic and alphanumeric codes for representing units of measurement for length, area, volume/capacity, mass (weight), time, and other quantities used in international trade. The codes are intended for use in manual and/or automated systems for the exchange of information between participants in international trade._






This slot occurs 4 times.


URI: [qudt:uneceCommonCode](http://qudt.org/schema/qudt/uneceCommonCode)



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

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)







## LinkML Source

<details>

```yaml
name: qudt_uneceCommonCode
description: The UN/CEFACT Recommendation 20 provides three character alphabetic and
  alphanumeric codes for representing units of measurement for length, area, volume/capacity,
  mass (weight), time, and other quantities used in international trade. The codes
  are intended for use in manual and/or automated systems for the exchange of information
  between participants in international trade.
title: unece common code
from_schema: okns:qudt
source: http://qudt.org/schema/qudt
slot_uri: qudt:uneceCommonCode
domain_of:
- qudt_ContextualUnit
- qudt_CountingUnit
- qudt_DerivedUnit
- qudt_DimensionlessUnit
- qudt_LogarithmicUnit
- qudt_Unit
range: string

```
</details>