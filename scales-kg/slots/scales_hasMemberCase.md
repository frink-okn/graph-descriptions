

# Slot: scales_hasMemberCase


_TODO -- tell the world what this slot (predicate) describes._





URI: [scales:hasMemberCase](http://schemas.scales-okn.org/rdf/scales#hasMemberCase)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCaseCriminal](../classes/ScalesCaseCriminal.md) | TODO -- tell the world what this class (type) describes |  no  |
| [ScalesCaseCivil](../classes/ScalesCaseCivil.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [ScalesCaseCivil](../classes/ScalesCaseCivil.md)






## Examples

| Value |
| --- |
| scales:CaseOther/wvsd;;2:13-md-02440 scales:hasMemberCase scales:CaseCivil/wvsd;;2:16-cv-10447 |
| scales:CaseCivil/wyd;;2:17-cv-00014 scales:hasMemberCase scales:CaseCivil/wyd;;2:17-cv-00023 |
| scales:CaseCriminal/ohsd;;1:16-cr-00004 scales:hasMemberCase scales:CaseCivil/ohsd;;1:16-cv-00014 |

## Comments

* 72187 occurrences with untyped subjects and object type http://schemas.scales-okn.org/rdf/scales#CaseCivil.
* 3609 occurrences with subject type scales_CaseCivil and object type scales_CaseCivil.
* 1 occurrences with subject type scales_CaseCriminal and object type scales_CaseCivil.

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
| self | scales:hasMemberCase |
| native | scales-kg/:scales_hasMemberCase |




## LinkML Source

<details>
```yaml
name: scales_hasMemberCase
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 72187 occurrences with untyped subjects and object type http://schemas.scales-okn.org/rdf/scales#CaseCivil.
- 3609 occurrences with subject type scales_CaseCivil and object type scales_CaseCivil.
- 1 occurrences with subject type scales_CaseCriminal and object type scales_CaseCivil.
examples:
- value: scales:CaseOther/wvsd;;2:13-md-02440 scales:hasMemberCase scales:CaseCivil/wvsd;;2:16-cv-10447
- value: scales:CaseCivil/wyd;;2:17-cv-00014 scales:hasMemberCase scales:CaseCivil/wyd;;2:17-cv-00023
- value: scales:CaseCriminal/ohsd;;1:16-cr-00004 scales:hasMemberCase scales:CaseCivil/ohsd;;1:16-cv-00014
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasMemberCase
alias: scales_hasMemberCase
domain_of:
- scales_CaseCivil
- scales_CaseCriminal
range: scales_CaseCivil

```
</details>