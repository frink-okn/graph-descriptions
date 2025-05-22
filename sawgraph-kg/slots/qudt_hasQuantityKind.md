

# Slot: has quantity kind (qudt_hasQuantityKind)


_No slot (predicate) description specified_






This slot occurs 576776 times.


URI: [qudt:hasQuantityKind](http://qudt.org/schema/qudt/hasQuantityKind)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) | No class (type) description specified |  yes  |
| [QudtDerivedUnit](../classes/QudtDerivedUnit.md) | A DerivedUnit is a type specification for units that are derived from other u... |  no  |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) | No class (type) description specified |  yes  |
| [QudtUnit](../classes/QudtUnit.md) | A unit of measure, or unit, is a particular quantity value that has been chos... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[QudtQuantityKind](../classes/QudtQuantityKind.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[CosoContaminantConcentrationQuantityKind](../classes/CosoContaminantConcentrationQuantityKind.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| qudt_Unit | uri | http://qudt.org/vocab/unit/MicroGM-PER-KiloGM | http://qudt.org/vocab/quantitykind/MassRatio | 13 |
| me_egad_EGAD-SinglePFAS-Concentration | owl_NamedIndividual | me_egad_data:result.101365P.NA.20130507.1763231 | coso:SingleContaminantConcentrationQuantityKind | 539086 |
| me_egad_EGAD-SinglePFAS-Concentration | coso_ContaminantConcentrationQuantityKind | me_egad_data:result.101365P.NA.20130507.1763231 | coso:SingleContaminantConcentrationQuantityKind | 539086 |
| me_egad_EGAD-AggregatePFAS-Concentration | uri | me_egad_data:result.101365P.NA.20130507.DEP18010 | coso:AggregateContaminantConcentrationQuantityKind | 37677 |




## LinkML Source

<details>

```yaml
name: qudt_hasQuantityKind
annotations:
  count:
    tag: count
    value: 576776
description: No slot (predicate) description specified
title: has quantity kind
examples:
- object:
    example_object: http://qudt.org/vocab/quantitykind/MassRatio
    example_object_type: uri
    example_predicate: qudt:hasQuantityKind
    example_subject: http://qudt.org/vocab/unit/MicroGM-PER-KiloGM
    example_subject_type: qudt_Unit
- object:
    example_object: coso:SingleContaminantConcentrationQuantityKind
    example_object_type: owl_NamedIndividual
    example_predicate: qudt:hasQuantityKind
    example_subject: me_egad_data:result.101365P.NA.20130507.1763231
    example_subject_type: me_egad_EGAD-SinglePFAS-Concentration
- object:
    example_object: coso:SingleContaminantConcentrationQuantityKind
    example_object_type: coso_ContaminantConcentrationQuantityKind
    example_predicate: qudt:hasQuantityKind
    example_subject: me_egad_data:result.101365P.NA.20130507.1763231
    example_subject_type: me_egad_EGAD-SinglePFAS-Concentration
- object:
    example_object: coso:AggregateContaminantConcentrationQuantityKind
    example_object_type: uri
    example_predicate: qudt:hasQuantityKind
    example_subject: me_egad_data:result.101365P.NA.20130507.DEP18010
    example_subject_type: me_egad_EGAD-AggregatePFAS-Concentration
from_schema: sawgraph-kg
source: http://qudt.org/2.1/schema/qudt
rank: 1000
slot_uri: qudt:hasQuantityKind
alias: qudt_hasQuantityKind
domain_of:
- qudt_Unit
- me_egad_EGAD-AggregatePFAS-Concentration
- me_egad_EGAD-SinglePFAS-Concentration
range: Any
any_of:
- range: owl_NamedIndividual
- range: qudt_QuantityKind
- range: uri
- range: coso_ContaminantConcentrationQuantityKind

```
</details>