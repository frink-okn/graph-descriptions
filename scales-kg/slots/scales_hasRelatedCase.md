

# Slot: scales_hasRelatedCase


_No slot description provided_





URI: [scales:hasRelatedCase](http://schemas.scales-okn.org/rdf/scales#hasRelatedCase)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCaseCriminal](../classes/ScalesCaseCriminal.md) | No type description provided |  no  |
| [ScalesCaseCivil](../classes/ScalesCaseCivil.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[ScalesCaseCivil](../classes/ScalesCaseCivil.md)&nbsp;or&nbsp;<br />[ScalesCaseCriminal](../classes/ScalesCaseCriminal.md)






## Examples

| Value |
| --- |
| scales:CaseCivil/wyd;;2:17-cv-00025 scales:hasRelatedCase scales:CaseCivil/wyd;;1:16-cv-00148 |
| scales:CaseCivil/akd;;3:16-cv-00293 scales:hasRelatedCase scales:CaseCivil/akd;;3:18-cv-00303 |
| scales:CaseCivil/iand;;1:17-cv-00106 scales:hasRelatedCase scales:CaseCriminal/iand;;1:17-cr-00012 |
| scales:CaseCriminal/alsd;;1:16-cr-00008 scales:hasRelatedCase scales:CaseCivil/alsd;;1:18-cv-00296 |
| scales:CaseCriminal/wvnd;;3:16-cr-00010 scales:hasRelatedCase scales:CaseCivil/wvnd;;3:17-cv-00111 |

## Comments

* 64461 occurrences with subject type scales_CaseCivil and object type scales_CaseCivil.
* 54514 occurrences with subject type scales_CaseCivil and object type uri.
* 1 occurrences with subject type scales_CaseCivil and object type scales_CaseCriminal.
* 3203 occurrences with subject type scales_CaseCriminal and object type uri.
* 337 occurrences with subject type scales_CaseCriminal and object type scales_CaseCivil.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | scales:hasRelatedCase |
| native | scales-kg/:scales_hasRelatedCase |




## LinkML Source

<details>
```yaml
name: scales_hasRelatedCase
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 64461 occurrences with subject type scales_CaseCivil and object type scales_CaseCivil.
- 54514 occurrences with subject type scales_CaseCivil and object type uri.
- 1 occurrences with subject type scales_CaseCivil and object type scales_CaseCriminal.
- 3203 occurrences with subject type scales_CaseCriminal and object type uri.
- 337 occurrences with subject type scales_CaseCriminal and object type scales_CaseCivil.
examples:
- value: scales:CaseCivil/wyd;;2:17-cv-00025 scales:hasRelatedCase scales:CaseCivil/wyd;;1:16-cv-00148
- value: scales:CaseCivil/akd;;3:16-cv-00293 scales:hasRelatedCase scales:CaseCivil/akd;;3:18-cv-00303
- value: scales:CaseCivil/iand;;1:17-cv-00106 scales:hasRelatedCase scales:CaseCriminal/iand;;1:17-cr-00012
- value: scales:CaseCriminal/alsd;;1:16-cr-00008 scales:hasRelatedCase scales:CaseCivil/alsd;;1:18-cv-00296
- value: scales:CaseCriminal/wvnd;;3:16-cr-00010 scales:hasRelatedCase scales:CaseCivil/wvnd;;3:17-cv-00111
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasRelatedCase
alias: scales_hasRelatedCase
domain_of:
- scales_CaseCivil
- scales_CaseCriminal
range: Any
any_of:
- range: uri
- range: scales_CaseCivil
- range: scales_CaseCriminal

```
</details>