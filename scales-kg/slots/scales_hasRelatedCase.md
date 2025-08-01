

# Slot: scales_hasRelatedCase


_No slot (predicate) description specified_






This slot occurs 125197 times.


URI: [scales:hasRelatedCase](http://schemas.scales-okn.org/rdf/scales#hasRelatedCase)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[ScalesCivilCase](../classes/ScalesCivilCase.md)&nbsp;or&nbsp;<br />[ScalesCriminalCase](../classes/ScalesCriminalCase.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CivilCase | uri | scales:/CivilCase/akd;;1:16-cv-00001 | scales:/CriminalCase/akd;;1:12-cr-00001-1 | 54415 |
| scales_CivilCase | scales_CivilCase | scales:/CivilCase/akd;;1:16-cv-00018 | scales:/CivilCase/akd;;1:16-cv-00009 | 67241 |
| scales_CivilCase | scales_CriminalCase | scales:/CivilCase/iand;;1:17-cv-00106 | scales:/CriminalCase/iand;;1:17-cr-00012 | 1 |
| scales_CriminalCase | uri | scales:/CriminalCase/alsd;;1:16-cr-00008 | scales:/CivilCase/alsd;;1:18-cv-00296 | 3203 |
| scales_CriminalCase | scales_CivilCase | scales:/CriminalCase/alsd;;1:16-cr-00015 | scales:/CivilCase/alsd;;1:17-cv-00277 | 337 |




## LinkML Source

<details>

```yaml
name: scales_hasRelatedCase
annotations:
  count:
    tag: count
    value: 125197
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/CriminalCase/akd;;1:12-cr-00001-1
    example_object_type: uri
    example_predicate: scales:hasRelatedCase
    example_subject: scales:/CivilCase/akd;;1:16-cv-00001
    example_subject_type: scales_CivilCase
- object:
    example_object: scales:/CivilCase/akd;;1:16-cv-00009
    example_object_type: scales_CivilCase
    example_predicate: scales:hasRelatedCase
    example_subject: scales:/CivilCase/akd;;1:16-cv-00018
    example_subject_type: scales_CivilCase
- object:
    example_object: scales:/CriminalCase/iand;;1:17-cr-00012
    example_object_type: scales_CriminalCase
    example_predicate: scales:hasRelatedCase
    example_subject: scales:/CivilCase/iand;;1:17-cv-00106
    example_subject_type: scales_CivilCase
- object:
    example_object: scales:/CivilCase/alsd;;1:18-cv-00296
    example_object_type: uri
    example_predicate: scales:hasRelatedCase
    example_subject: scales:/CriminalCase/alsd;;1:16-cr-00008
    example_subject_type: scales_CriminalCase
- object:
    example_object: scales:/CivilCase/alsd;;1:17-cv-00277
    example_object_type: scales_CivilCase
    example_predicate: scales:hasRelatedCase
    example_subject: scales:/CriminalCase/alsd;;1:16-cr-00015
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasRelatedCase
alias: scales_hasRelatedCase
domain_of:
- scales_CivilCase
- scales_CriminalCase
range: Any
any_of:
- range: uri
- range: scales_CivilCase
- range: scales_CriminalCase

```
</details>