

# Slot: has unit (qudt_hasUnit)


_This property relates a factor unit its unit_






This slot occurs 3381570 times.


URI: [qudt:hasUnit](http://qudt.org/schema/qudt/hasUnit)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[QudtUnit](../classes/QudtUnit.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[QudtContextualUnit](../classes/QudtContextualUnit.md)&nbsp;or&nbsp;<br />[QudtLogarithmicUnit](../classes/QudtLogarithmicUnit.md)&nbsp;or&nbsp;<br />[QudtCurrencyUnit](../classes/QudtCurrencyUnit.md)&nbsp;or&nbsp;<br />[QudtDerivedUnit](../classes/QudtDerivedUnit.md)&nbsp;or&nbsp;<br />[QudtCountingUnit](../classes/QudtCountingUnit.md)





## Comments

* description: This property relates a factor unit to its unit or a system of units with a unit of measure that is either a) defined by the system, or b) accepted for use by the system and is convertible to a unit of equivalent dimension that is defined by the system. Systems of units may distinguish between base and derived units. Base units are the units which measure the base quantities for the corresponding system of quantities. The base units are used to define units for all other quantities as products of powers of the base units. Such units are called derived units for the system.
* title: hasUnit



## LinkML Source

<details>

```yaml
name: qudt_hasUnit
description: This property relates a factor unit its unit
title: has unit
comments:
- 'description: This property relates a factor unit to its unit or a system of units
  with a unit of measure that is either a) defined by the system, or b) accepted for
  use by the system and is convertible to a unit of equivalent dimension that is defined
  by the system. Systems of units may distinguish between base and derived units.
  Base units are the units which measure the base quantities for the corresponding
  system of quantities. The base units are used to define units for all other quantities
  as products of powers of the base units. Such units are called derived units for
  the system.'
- 'title: hasUnit'
from_schema: okns:qudt
source: http://qudt.org/schema/qudt
slot_uri: qudt:hasUnit
range: Any
any_of:
- range: qudt_Unit
- range: uri
- range: qudt_ContextualUnit
- range: qudt_LogarithmicUnit
- range: qudt_CurrencyUnit
- range: qudt_DerivedUnit
- range: qudt_CountingUnit

```
</details>