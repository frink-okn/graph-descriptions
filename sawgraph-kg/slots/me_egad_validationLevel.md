

# Slot: egad - validation level (me_egad_validationLevel)


_No slot (predicate) description specified_






This slot occurs 567749 times.


URI: [me_egad:validationLevel](http://sawgraph.spatialai.org/v1/me-egad#validationLevel)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) | No class (type) description specified |  yes  |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-ValidationLevel](../classes/MeEgadEGAD-ValidationLevel.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-AggregatePFAS-Concentration | me_egad_EGAD-ValidationLevel | me_egad_data:result.101365P.NA.20130507.DEP18010 | me_egad_data:validationLevel.DEP | 37474 |
| me_egad_EGAD-AggregatePFAS-Concentration | owl_NamedIndividual | me_egad_data:result.101365P.NA.20130507.DEP18010 | me_egad_data:validationLevel.DEP | 37474 |
| me_egad_EGAD-SinglePFAS-Concentration | me_egad_EGAD-ValidationLevel | me_egad_data:result.1028303.ELL.20190405.335671 | me_egad_data:validationLevel.DEP | 528882 |
| me_egad_EGAD-SinglePFAS-Concentration | owl_NamedIndividual | me_egad_data:result.1028303.ELL.20190405.335671 | me_egad_data:validationLevel.DEP | 528882 |
| me_egad_EGAD-SinglePFAS-Concentration | uri | me_egad_data:result.170094201.VAL.20170725.108427538 | me_egad_data:validationLevel.T2 | 1316 |
| me_egad_EGAD-AggregatePFAS-Concentration | uri | me_egad_data:result.170098413.VAL.20170802.DEP18016 | me_egad_data:validationLevel.T2 | 77 |




## LinkML Source

<details>

```yaml
name: me_egad_validationLevel
annotations:
  count:
    tag: count
    value: 567749
description: No slot (predicate) description specified
title: egad - validation level
examples:
- object:
    example_object: me_egad_data:validationLevel.DEP
    example_object_type: me_egad_EGAD-ValidationLevel
    example_predicate: me_egad:validationLevel
    example_subject: me_egad_data:result.101365P.NA.20130507.DEP18010
    example_subject_type: me_egad_EGAD-AggregatePFAS-Concentration
- object:
    example_object: me_egad_data:validationLevel.DEP
    example_object_type: owl_NamedIndividual
    example_predicate: me_egad:validationLevel
    example_subject: me_egad_data:result.101365P.NA.20130507.DEP18010
    example_subject_type: me_egad_EGAD-AggregatePFAS-Concentration
- object:
    example_object: me_egad_data:validationLevel.DEP
    example_object_type: me_egad_EGAD-ValidationLevel
    example_predicate: me_egad:validationLevel
    example_subject: me_egad_data:result.1028303.ELL.20190405.335671
    example_subject_type: me_egad_EGAD-SinglePFAS-Concentration
- object:
    example_object: me_egad_data:validationLevel.DEP
    example_object_type: owl_NamedIndividual
    example_predicate: me_egad:validationLevel
    example_subject: me_egad_data:result.1028303.ELL.20190405.335671
    example_subject_type: me_egad_EGAD-SinglePFAS-Concentration
- object:
    example_object: me_egad_data:validationLevel.T2
    example_object_type: uri
    example_predicate: me_egad:validationLevel
    example_subject: me_egad_data:result.170094201.VAL.20170725.108427538
    example_subject_type: me_egad_EGAD-SinglePFAS-Concentration
- object:
    example_object: me_egad_data:validationLevel.T2
    example_object_type: uri
    example_predicate: me_egad:validationLevel
    example_subject: me_egad_data:result.170098413.VAL.20170802.DEP18016
    example_subject_type: me_egad_EGAD-AggregatePFAS-Concentration
from_schema: sawgraph-kg
rank: 1000
slot_uri: me_egad:validationLevel
alias: me_egad_validationLevel
domain_of:
- me_egad_EGAD-AggregatePFAS-Concentration
- me_egad_EGAD-SinglePFAS-Concentration
subproperty_of: coso_resultAnnotation
range: Any
any_of:
- range: me_egad_EGAD-ValidationLevel
- range: uri
- range: owl_NamedIndividual

```
</details>