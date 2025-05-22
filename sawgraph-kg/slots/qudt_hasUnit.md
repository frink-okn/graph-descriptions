

# Slot: has unit (qudt_hasUnit)


_This property relates a system of units with a unit of measure that is either a) defined by the system, or b) accepted for use by the system and is convertible to a unit of equivalent dimension that is defined by the system. Systems of units may distinguish between base and derived units. Base units are the units which measure the base quantities for the corresponding system of quantities. The base units are used to define units for all other quantities as products of powers of the base units. Such units are called derived units for the system._






This slot occurs 154043 times.


URI: [qudt:hasUnit](http://qudt.org/schema/qudt/hasUnit)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [CosoNonDetectQuantityValue](../classes/CosoNonDetectQuantityValue.md) | No class (type) description specified |  yes  |
| [CosoDetectQuantityValue](../classes/CosoDetectQuantityValue.md) | No class (type) description specified |  yes  |







## Properties

* Range: [QudtUnit](../classes/QudtUnit.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| None | qudt_Unit | me_egad_data:mdl.0.0.NG/L | http://qudt.org/vocab/unit/NanoGM-PER-L | 11486 |
| coso_DetectQuantityValue | qudt_Unit | me_egad_data:quantityValue.1028303.ELL.20190405.45298906 | coso:NanoGM-PER-GM | 142557 |
| coso_NonDetectQuantityValue | qudt_Unit | me_egad_data:quantityValue.1095743.ELL.20190627.2706903 | http://qudt.org/vocab/unit/NanoGM-PER-L | 416 |




## LinkML Source

<details>

```yaml
name: qudt_hasUnit
annotations:
  count:
    tag: count
    value: 154043
  qudt_Unit:
    tag: qudt_Unit
    value: 11486
description: This property relates a system of units with a unit of measure that is
  either a) defined by the system, or b) accepted for use by the system and is convertible
  to a unit of equivalent dimension that is defined by the system. Systems of units
  may distinguish between base and derived units. Base units are the units which measure
  the base quantities for the corresponding system of quantities. The base units are
  used to define units for all other quantities as products of powers of the base
  units. Such units are called derived units for the system.
title: has unit
examples:
- object:
    example_object: http://qudt.org/vocab/unit/NanoGM-PER-L
    example_object_type: qudt_Unit
    example_predicate: qudt:hasUnit
    example_subject: me_egad_data:mdl.0.0.NG/L
    example_subject_type: None
- object:
    example_object: coso:NanoGM-PER-GM
    example_object_type: qudt_Unit
    example_predicate: qudt:hasUnit
    example_subject: me_egad_data:quantityValue.1028303.ELL.20190405.45298906
    example_subject_type: coso_DetectQuantityValue
- object:
    example_object: http://qudt.org/vocab/unit/NanoGM-PER-L
    example_object_type: qudt_Unit
    example_predicate: qudt:hasUnit
    example_subject: me_egad_data:quantityValue.1095743.ELL.20190627.2706903
    example_subject_type: coso_NonDetectQuantityValue
from_schema: sawgraph-kg
source: http://qudt.org/2.1/schema/qudt
rank: 1000
slot_uri: qudt:hasUnit
alias: qudt_hasUnit
domain_of:
- coso_DetectQuantityValue
- coso_NonDetectQuantityValue
range: qudt_Unit

```
</details>