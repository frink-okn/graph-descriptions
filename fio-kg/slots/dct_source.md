

# Slot: Source (dct_source)


_This property is intended to be used with non-literal values. The described resource may be derived from the related resource in whole or in part. Best practice is to identify the related resource by means of a URI or a string conforming to a formal identification system._






This slot occurs 3 times.


URI: [dct:source](http://purl.org/dc/terms/source)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Fio-epa-frsLegacySystem](../classes/Fio-epa-frsLegacySystem.md) |  |  no  |
| [Fio-epa-frsReportingSystem](../classes/Fio-epa-frsReportingSystem.md) |  |  no  |
| [Fio-epa-frsProjectSystem](../classes/Fio-epa-frsProjectSystem.md) |  |  no  |
| [Fio-epa-frsSiteSystem](../classes/Fio-epa-frsSiteSystem.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)





## Comments

* description: A related resource from which the described resource is derived.
* No occurrences of this slot in the graph.



## LinkML Source

<details>

```yaml
name: dct_source
description: This property is intended to be used with non-literal values. The described
  resource may be derived from the related resource in whole or in part. Best practice
  is to identify the related resource by means of a URI or a string conforming to
  a formal identification system.
title: Source
comments:
- 'description: A related resource from which the described resource is derived.'
- No occurrences of this slot in the graph.
from_schema: okns:dc
source: http://purl.org/dc/terms/
slot_uri: dct:source
domain_of:
- fio-epa-frs_LegacySystem
- fio-epa-frs_ProjectSystem
- fio-epa-frs_ReportingSystem
- fio-epa-frs_SiteSystem
subproperty_of: dct_relation
range: Any

```
</details>