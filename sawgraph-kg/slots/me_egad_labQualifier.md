

# Slot: egad - lab qualifier (me_egad_labQualifier)


_No slot (predicate) description specified_






This slot occurs 489050 times.


URI: [me_egad:labQualifier](http://sawgraph.spatialai.org/v1/me-egad#labQualifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) | No class (type) description specified |  yes  |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-ConcentrationQualifier](../classes/MeEgadEGAD-ConcentrationQualifier.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-SinglePFAS-Concentration | me_egad_EGAD-ConcentrationQualifier | me_egad_data:result.101365P.NA.20130507.1763231 | me_egad_data:concentrationQualifier.U | 464360 |
| me_egad_EGAD-SinglePFAS-Concentration | owl_NamedIndividual | me_egad_data:result.101365P.NA.20130507.1763231 | me_egad_data:concentrationQualifier.U | 464360 |
| me_egad_EGAD-AggregatePFAS-Concentration | me_egad_EGAD-ConcentrationQualifier | me_egad_data:result.101365P.NA.20130507.DEP18010 | me_egad_data:concentrationQualifier.U | 24690 |
| me_egad_EGAD-AggregatePFAS-Concentration | owl_NamedIndividual | me_egad_data:result.101365P.NA.20130507.DEP18010 | me_egad_data:concentrationQualifier.U | 24690 |




## LinkML Source

<details>

```yaml
name: me_egad_labQualifier
annotations:
  count:
    tag: count
    value: 489050
description: No slot (predicate) description specified
title: egad - lab qualifier
examples:
- object:
    example_object: me_egad_data:concentrationQualifier.U
    example_object_type: me_egad_EGAD-ConcentrationQualifier
    example_predicate: me_egad:labQualifier
    example_subject: me_egad_data:result.101365P.NA.20130507.1763231
    example_subject_type: me_egad_EGAD-SinglePFAS-Concentration
- object:
    example_object: me_egad_data:concentrationQualifier.U
    example_object_type: owl_NamedIndividual
    example_predicate: me_egad:labQualifier
    example_subject: me_egad_data:result.101365P.NA.20130507.1763231
    example_subject_type: me_egad_EGAD-SinglePFAS-Concentration
- object:
    example_object: me_egad_data:concentrationQualifier.U
    example_object_type: me_egad_EGAD-ConcentrationQualifier
    example_predicate: me_egad:labQualifier
    example_subject: me_egad_data:result.101365P.NA.20130507.DEP18010
    example_subject_type: me_egad_EGAD-AggregatePFAS-Concentration
- object:
    example_object: me_egad_data:concentrationQualifier.U
    example_object_type: owl_NamedIndividual
    example_predicate: me_egad:labQualifier
    example_subject: me_egad_data:result.101365P.NA.20130507.DEP18010
    example_subject_type: me_egad_EGAD-AggregatePFAS-Concentration
from_schema: sawgraph-kg
rank: 1000
slot_uri: me_egad:labQualifier
alias: me_egad_labQualifier
domain_of:
- me_egad_EGAD-AggregatePFAS-Concentration
- me_egad_EGAD-SinglePFAS-Concentration
subproperty_of: coso_resultAnnotation
range: Any
any_of:
- range: me_egad_EGAD-ConcentrationQualifier
- range: owl_NamedIndividual

```
</details>