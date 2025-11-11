

# Slot: ucum code (qudt_ucumCode)


_<p><em>ucumCode</em> associates a QUDT unit with its UCUM code (case-sensitive). </p><p>In SHACL the values are derived from specific ucum properties using 'sh:values'.</p>_






This slot occurs 12 times.


URI: [qudt:ucumCode](http://qudt.org/schema/qudt/ucumCode)



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

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[QudtUCUMcs](../types/QudtUCUMcs.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)





## See Also

* [https://ucum.org/ucum.html](https://ucum.org/ucum.html)



## LinkML Source

<details>

```yaml
name: qudt_ucumCode
description: <p><em>ucumCode</em> associates a QUDT unit with its UCUM code (case-sensitive).
  </p><p>In SHACL the values are derived from specific ucum properties using 'sh:values'.</p>
title: ucum code
from_schema: okns:qudt
source: http://qudt.org/schema/qudt
see_also:
- https://ucum.org/ucum.html
slot_uri: qudt:ucumCode
domain_of:
- qudt_BinaryPrefix
- qudt_ContextualUnit
- qudt_CountingUnit
- qudt_CurrencyUnit
- qudt_DecimalPrefix
- qudt_DerivedUnit
- qudt_LogarithmicUnit
- qudt_Unit
subproperty_of: skos_notation
range: Any
any_of:
- range: qudt_UCUMcs
- range: string

```
</details>