

# Slot: Source (dct_source)


_This property is intended to be used with non-literal values. The described resource may be derived from the related resource in whole or in part. Best practice is to identify the related resource by means of a URI or a string conforming to a formal identification system._






This slot occurs 3 times.


URI: [dct:source](http://purl.org/dc/terms/source)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [QudtSolidAngleUnit](../classes/QudtSolidAngleUnit.md) | The solid angle subtended by a surface S is defined as the surface area of a ... |  no  |
| [QudtCountingUnit](../classes/QudtCountingUnit.md) | Used for all units that express counts |  no  |
| [Fio-epa-frsSiteSystem](../classes/Fio-epa-frsSiteSystem.md) |  |  no  |
| [QudtUnit](../classes/QudtUnit.md) | A unit of measure, or unit, is a particular quantity value that has been chos... |  no  |
| [QudtPlaneAngleUnit](../classes/QudtPlaneAngleUnit.md) |  |  no  |
| [Fio-epa-frsLegacySystem](../classes/Fio-epa-frsLegacySystem.md) |  |  no  |
| [QudtAngleUnit](../classes/QudtAngleUnit.md) | All units relating to specification of angles |  no  |
| [QudtDerivedUnit](../classes/QudtDerivedUnit.md) | A DerivedUnit is a type specification for units that are derived from other u... |  no  |
| [QudtContextualUnit](../classes/QudtContextualUnit.md) |  |  no  |
| [Fio-epa-frsProjectSystem](../classes/Fio-epa-frsProjectSystem.md) |  |  no  |
| [QudtDimensionlessUnit](../classes/QudtDimensionlessUnit.md) | A Dimensionless Unit is a quantity for which all the exponents of the factors... |  no  |
| [QudtLogarithmicUnit](../classes/QudtLogarithmicUnit.md) | Logarithmic units are abstract mathematical units that can be used to express... |  no  |
| [Fio-epa-frsReportingSystem](../classes/Fio-epa-frsReportingSystem.md) |  |  no  |
| [QudtCurrencyUnit](../classes/QudtCurrencyUnit.md) | Currency Units have their own subclass of unit because: (a) they have additon... |  no  |







## Properties

* Range: [Any](../classes/Any.md)





## Comments

* description: A related resource from which the described resource is derived.



## LinkML Source

<details>

```yaml
name: dct_source
description: This property is intended to be used with non-literal values. The described
  resource may be derived from the related resource in whole or in part. Best practice
  is to identify the related resource by means of a URI or a string conforming to
  a formal identification system.
title: Source
notes:
- No occurrences of this slot in the graph.
comments:
- 'description: A related resource from which the described resource is derived.'
from_schema: okns:dc
source: http://purl.org/dc/terms/
slot_uri: dct:source
domain_of:
- qudt_Unit
- fio-epa-frs_LegacySystem
- fio-epa-frs_ProjectSystem
- fio-epa-frs_ReportingSystem
- fio-epa-frs_SiteSystem
subproperty_of: dct_relation
range: Any

```
</details>