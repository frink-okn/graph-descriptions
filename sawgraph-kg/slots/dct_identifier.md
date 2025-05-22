

# Slot: No slot (predicate) name specified -- this slot is noted as a subproperty of another slot in this graph but has not itself been defined. (dct_identifier)


_No slot (predicate) description specified_






This slot occurs 31071 times.


URI: [dct:identifier](http://purl.org/dc/terms/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) | No class (type) description specified |  yes  |
| [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-Sample | string | me_egad_data:sample.AAL210144001R.20210112 | BETH WILLIAMS ACF | 23031 |
| me_egad_EGAD-SamplePoint | integer | me_egad_data:samplePoint.100410 | 100410 | 8040 |




## LinkML Source

<details>

```yaml
name: dct_identifier
annotations:
  count:
    tag: count
    value: 31071
description: No slot (predicate) description specified
title: No slot (predicate) name specified -- this slot is noted as a subproperty of
  another slot in this graph but has not itself been defined.
examples:
- object:
    example_object: BETH WILLIAMS ACF
    example_object_type: string
    example_predicate: dct:identifier
    example_subject: me_egad_data:sample.AAL210144001R.20210112
    example_subject_type: me_egad_EGAD-Sample
- object:
    example_object: '100410'
    example_object_type: integer
    example_predicate: dct:identifier
    example_subject: me_egad_data:samplePoint.100410
    example_subject_type: me_egad_EGAD-SamplePoint
from_schema: sawgraph-kg
rank: 1000
slot_uri: dct:identifier
alias: dct_identifier
domain_of:
- me_egad_EGAD-Sample
- me_egad_EGAD-SamplePoint
range: Any
any_of:
- range: string
- range: integer

```
</details>