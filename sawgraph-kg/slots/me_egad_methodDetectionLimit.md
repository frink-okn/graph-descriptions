

# Slot: egad - method detection limit (me_egad_methodDetectionLimit)


_No slot (predicate) description specified_






This slot occurs 577732 times.


URI: [me_egad:methodDetectionLimit](http://sawgraph.spatialai.org/v1/me-egad#methodDetectionLimit)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) | No class (type) description specified |  yes  |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[MeEgadEGAD-MethodDetectionLimit](../classes/MeEgadEGAD-MethodDetectionLimit.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-SinglePFAS-Concentration | uri | me_egad_data:result.1028303.ELL.20190405.335671 | me_egad_data:mdl.1.1.NG/G | 540043 |
| me_egad_EGAD-AggregatePFAS-Concentration | uri | me_egad_data:result.1028303.ELL.20190405.DEP18010 | me_egad_data:mdl.1.1.NG/G | 37689 |




## LinkML Source

<details>

```yaml
name: me_egad_methodDetectionLimit
annotations:
  count:
    tag: count
    value: 577732
description: No slot (predicate) description specified
title: egad - method detection limit
examples:
- object:
    example_object: me_egad_data:mdl.1.1.NG/G
    example_object_type: uri
    example_predicate: me_egad:methodDetectionLimit
    example_subject: me_egad_data:result.1028303.ELL.20190405.335671
    example_subject_type: me_egad_EGAD-SinglePFAS-Concentration
- object:
    example_object: me_egad_data:mdl.1.1.NG/G
    example_object_type: uri
    example_predicate: me_egad:methodDetectionLimit
    example_subject: me_egad_data:result.1028303.ELL.20190405.DEP18010
    example_subject_type: me_egad_EGAD-AggregatePFAS-Concentration
from_schema: sawgraph-kg
rank: 1000
slot_uri: me_egad:methodDetectionLimit
alias: me_egad_methodDetectionLimit
domain_of:
- me_egad_EGAD-AggregatePFAS-Concentration
- me_egad_EGAD-SinglePFAS-Concentration
subproperty_of: coso_resultAnnotation
range: Any
any_of:
- range: uri
- range: me_egad_EGAD-MethodDetectionLimit

```
</details>