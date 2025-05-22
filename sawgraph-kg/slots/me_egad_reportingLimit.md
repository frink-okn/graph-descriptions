

# Slot: egad - reporting limit (me_egad_reportingLimit)


_No slot (predicate) description specified_






This slot occurs 579249 times.


URI: [me_egad:reportingLimit](http://sawgraph.spatialai.org/v1/me-egad#reportingLimit)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) | No class (type) description specified |  yes  |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[MeEgadEGAD-ReportingLimit](../classes/MeEgadEGAD-ReportingLimit.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-SinglePFAS-Concentration | uri | me_egad_data:result.101365P.NA.20130507.1763231 | me_egad_data:rl.0.04.UG/L | 541392 |
| me_egad_EGAD-AggregatePFAS-Concentration | uri | me_egad_data:result.101365P.NA.20130507.DEP18010 | me_egad_data:rl.0.02.UG/L | 37857 |




## LinkML Source

<details>

```yaml
name: me_egad_reportingLimit
annotations:
  count:
    tag: count
    value: 579249
description: No slot (predicate) description specified
title: egad - reporting limit
examples:
- object:
    example_object: me_egad_data:rl.0.04.UG/L
    example_object_type: uri
    example_predicate: me_egad:reportingLimit
    example_subject: me_egad_data:result.101365P.NA.20130507.1763231
    example_subject_type: me_egad_EGAD-SinglePFAS-Concentration
- object:
    example_object: me_egad_data:rl.0.02.UG/L
    example_object_type: uri
    example_predicate: me_egad:reportingLimit
    example_subject: me_egad_data:result.101365P.NA.20130507.DEP18010
    example_subject_type: me_egad_EGAD-AggregatePFAS-Concentration
from_schema: sawgraph-kg
rank: 1000
slot_uri: me_egad:reportingLimit
alias: me_egad_reportingLimit
domain_of:
- me_egad_EGAD-AggregatePFAS-Concentration
- me_egad_EGAD-SinglePFAS-Concentration
subproperty_of: coso_resultAnnotation
range: Any
any_of:
- range: uri
- range: me_egad_EGAD-ReportingLimit

```
</details>