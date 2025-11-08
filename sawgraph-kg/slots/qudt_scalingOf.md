

# Slot: scalingOf (qudt_scalingOf)


_This property relates a unit that is scaled to the base unit that its qudt:conversionMultiplier converts it to_






This slot occurs 1 times.


URI: [qudt:scalingOf](http://qudt.org/schema/qudt/scalingOf)



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

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[QudtDerivedUnit](../classes/QudtDerivedUnit.md)&nbsp;or&nbsp;<br />[QudtUnit](../classes/QudtUnit.md)&nbsp;or&nbsp;<br />[QudtCountingUnit](../classes/QudtCountingUnit.md)&nbsp;or&nbsp;<br />[QudtCurrencyUnit](../classes/QudtCurrencyUnit.md)





## Comments

* description: This property relates a unit to another unit it is scaled from



## LinkML Source

<details>

```yaml
name: qudt_scalingOf
description: This property relates a unit that is scaled to the base unit that its
  qudt:conversionMultiplier converts it to
title: scalingOf
comments:
- 'description: This property relates a unit to another unit it is scaled from'
from_schema: okns:qudt
source: http://qudt.org/schema/qudt
slot_uri: qudt:scalingOf
domain_of:
- qudt_ContextualUnit
- qudt_CountingUnit
- qudt_CurrencyUnit
- qudt_DerivedUnit
- qudt_Unit
range: Any
any_of:
- range: qudt_DerivedUnit
- range: qudt_Unit
- range: qudt_CountingUnit
- range: qudt_CurrencyUnit

```
</details>