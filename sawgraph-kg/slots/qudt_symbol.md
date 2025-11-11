

# Slot: symbol (qudt_symbol)


_The symbol is a glyph that is used to represent some concept, typically a unit or a quantity, in a compact form. ␊  For example, the symbol for an Ohm is $ohm$. ␊  This contrasts with 'unit:abbreviation', which gives a short alphanumeric abbreviation for the unit, 'ohm' for Ohm._






This slot occurs 7 times.


URI: [qudt:symbol](http://qudt.org/schema/qudt/symbol)



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
| [QudtBinaryPrefix](../classes/QudtBinaryPrefix.md) | A <em>Binary Prefix</em> is a prefix for multiples of units in data processin... |  no  |
| [QudtLogarithmicUnit](../classes/QudtLogarithmicUnit.md) | Logarithmic units are abstract mathematical units that can be used to express... |  no  |
| [QudtDecimalPrefix](../classes/QudtDecimalPrefix.md) | A <em>Decimal Prefix</em> is a prefix for multiples of units that are powers ... |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)







## LinkML Source

<details>

```yaml
name: qudt_symbol
description: The symbol is a glyph that is used to represent some concept, typically
  a unit or a quantity, in a compact form. ␊  For example, the symbol for an Ohm is
  $ohm$. ␊  This contrasts with 'unit:abbreviation', which gives a short alphanumeric
  abbreviation for the unit, 'ohm' for Ohm.
title: symbol
from_schema: okns:qudt
source: http://qudt.org/schema/qudt
slot_uri: qudt:symbol
domain_of:
- qudt_BinaryPrefix
- qudt_ContextualUnit
- qudt_CountingUnit
- qudt_CurrencyUnit
- qudt_DecimalPrefix
- qudt_DerivedUnit
- qudt_DimensionlessUnit
- qudt_LogarithmicUnit
- qudt_Unit
subproperty_of: dtype_literal
range: string

```
</details>