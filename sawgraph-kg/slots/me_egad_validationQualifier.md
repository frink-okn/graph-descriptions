

# Slot: egad - validation qualifier (me_egad_validationQualifier)


_No slot (predicate) description specified_






This slot occurs 505846 times.


URI: [me_egad:validationQualifier](http://sawgraph.spatialai.org/v1/me-egad#validationQualifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) | No class (type) description specified |  yes  |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[MeEgadEGAD-ConcentrationQualifier](../classes/MeEgadEGAD-ConcentrationQualifier.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-SinglePFAS-Concentration | me_egad_EGAD-ConcentrationQualifier | me_egad_data:result.1028303.ELL.20190405.335671 | me_egad_data:concentrationQualifier.U | 477283 |
| me_egad_EGAD-SinglePFAS-Concentration | owl_NamedIndividual | me_egad_data:result.1028303.ELL.20190405.335671 | me_egad_data:concentrationQualifier.U | 477283 |
| me_egad_EGAD-AggregatePFAS-Concentration | me_egad_EGAD-ConcentrationQualifier | me_egad_data:result.1039233.ELL.20190412.DEP18010 | me_egad_data:concentrationQualifier.J | 28510 |
| me_egad_EGAD-AggregatePFAS-Concentration | owl_NamedIndividual | me_egad_data:result.1039233.ELL.20190412.DEP18010 | me_egad_data:concentrationQualifier.J | 28510 |
| me_egad_EGAD-SinglePFAS-Concentration | uri | me_egad_data:result.320623561.TA.20200701.335671 | me_egad_data:concentrationQualifier.M | 45 |
| me_egad_EGAD-AggregatePFAS-Concentration | uri | me_egad_data:result.320623562.TA.20200701.DEP18010 | me_egad_data:concentrationQualifier.M | 8 |




## LinkML Source

<details>

```yaml
name: me_egad_validationQualifier
annotations:
  count:
    tag: count
    value: 505846
description: No slot (predicate) description specified
title: egad - validation qualifier
examples:
- object:
    example_object: me_egad_data:concentrationQualifier.U
    example_object_type: me_egad_EGAD-ConcentrationQualifier
    example_predicate: me_egad:validationQualifier
    example_subject: me_egad_data:result.1028303.ELL.20190405.335671
    example_subject_type: me_egad_EGAD-SinglePFAS-Concentration
- object:
    example_object: me_egad_data:concentrationQualifier.U
    example_object_type: owl_NamedIndividual
    example_predicate: me_egad:validationQualifier
    example_subject: me_egad_data:result.1028303.ELL.20190405.335671
    example_subject_type: me_egad_EGAD-SinglePFAS-Concentration
- object:
    example_object: me_egad_data:concentrationQualifier.J
    example_object_type: me_egad_EGAD-ConcentrationQualifier
    example_predicate: me_egad:validationQualifier
    example_subject: me_egad_data:result.1039233.ELL.20190412.DEP18010
    example_subject_type: me_egad_EGAD-AggregatePFAS-Concentration
- object:
    example_object: me_egad_data:concentrationQualifier.J
    example_object_type: owl_NamedIndividual
    example_predicate: me_egad:validationQualifier
    example_subject: me_egad_data:result.1039233.ELL.20190412.DEP18010
    example_subject_type: me_egad_EGAD-AggregatePFAS-Concentration
- object:
    example_object: me_egad_data:concentrationQualifier.M
    example_object_type: uri
    example_predicate: me_egad:validationQualifier
    example_subject: me_egad_data:result.320623561.TA.20200701.335671
    example_subject_type: me_egad_EGAD-SinglePFAS-Concentration
- object:
    example_object: me_egad_data:concentrationQualifier.M
    example_object_type: uri
    example_predicate: me_egad:validationQualifier
    example_subject: me_egad_data:result.320623562.TA.20200701.DEP18010
    example_subject_type: me_egad_EGAD-AggregatePFAS-Concentration
from_schema: sawgraph-kg
rank: 1000
slot_uri: me_egad:validationQualifier
alias: me_egad_validationQualifier
domain_of:
- me_egad_EGAD-AggregatePFAS-Concentration
- me_egad_EGAD-SinglePFAS-Concentration
subproperty_of: coso_resultAnnotation
range: Any
any_of:
- range: uri
- range: me_egad_EGAD-ConcentrationQualifier
- range: owl_NamedIndividual

```
</details>