

# Slot: No slot (predicate) name specified (qudt_enumeratedValue)


_No slot (predicate) description specified_






This slot occurs 435002 times.


URI: [qudt:enumeratedValue](http://qudt.org/schema/qudt/enumeratedValue)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [CosoNonDetectQuantityValue](../classes/CosoNonDetectQuantityValue.md) | No class (type) description specified |  yes  |
| [CosoDetectQuantityValue](../classes/CosoDetectQuantityValue.md) | No class (type) description specified |  yes  |







## Properties

* Range: [QudtEnumeratedValue](../classes/QudtEnumeratedValue.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| coso_NonDetectQuantityValue | qudt_EnumeratedValue | me_egad_data:quantityValue.101365P.NA.20130507.1763231 | coso:non-detect | 435002 |
| coso_DetectQuantityValue | qudt_EnumeratedValue | me_egad_data:quantityValue.1095743.ELL.20190627.2706903 | coso:non-detect | 416 |




## LinkML Source

<details>

```yaml
name: qudt_enumeratedValue
annotations:
  count:
    tag: count
    value: 435002
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: coso:non-detect
    example_object_type: qudt_EnumeratedValue
    example_predicate: qudt:enumeratedValue
    example_subject: me_egad_data:quantityValue.101365P.NA.20130507.1763231
    example_subject_type: coso_NonDetectQuantityValue
- object:
    example_object: coso:non-detect
    example_object_type: qudt_EnumeratedValue
    example_predicate: qudt:enumeratedValue
    example_subject: me_egad_data:quantityValue.1095743.ELL.20190627.2706903
    example_subject_type: coso_DetectQuantityValue
from_schema: sawgraph-kg
rank: 1000
slot_uri: qudt:enumeratedValue
alias: qudt_enumeratedValue
domain_of:
- coso_DetectQuantityValue
- coso_NonDetectQuantityValue
range: qudt_EnumeratedValue

```
</details>