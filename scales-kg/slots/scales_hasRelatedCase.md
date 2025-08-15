

# Slot: scales_hasRelatedCase




This slot occurs 125197 times.


URI: [scales:hasRelatedCase](http://schemas.scales-okn.org/rdf/scales#hasRelatedCase)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) |  |  no  |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ScalesCivilCase](../classes/ScalesCivilCase.md)&nbsp;or&nbsp;<br />[ScalesCriminalCase](../classes/ScalesCriminalCase.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)







## LinkML Source

<details>

```yaml
name: scales_hasRelatedCase
from_schema: okns:scales-kg
rank: 1000
slot_uri: scales:hasRelatedCase
alias: scales_hasRelatedCase
domain_of:
- scales_CivilCase
- scales_CriminalCase
range: Any
any_of:
- range: scales_CivilCase
- range: scales_CriminalCase
- range: uri

```
</details>