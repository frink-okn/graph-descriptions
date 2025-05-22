

# Slot: numeric value (qudt_numericValue)


_No slot (predicate) description specified_






This slot occurs 154542 times.


URI: [qudt:numericValue](http://qudt.org/schema/qudt/numericValue)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [CosoNonDetectQuantityValue](../classes/CosoNonDetectQuantityValue.md) | No class (type) description specified |  yes  |
| [CosoDetectQuantityValue](../classes/CosoDetectQuantityValue.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:decimal](http://www.w3.org/2001/XMLSchema#decimal)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[QudtNumericUnion](../classes/QudtNumericUnion.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| None | decimal | me_egad_data:mdl.0.0.NG/L | 0.0 | 11383 |
| None | double | me_egad_data:mdl.1.18e-06.MG/L | 1.18e-06 | 103 |
| coso_DetectQuantityValue | decimal | me_egad_data:quantityValue.1028303.ELL.20190405.45298906 | 14.0 | 142502 |
| coso_NonDetectQuantityValue | decimal | me_egad_data:quantityValue.1095743.ELL.20190627.2706903 | 16000.0 | 427 |
| coso_DetectQuantityValue | double | me_egad_data:quantityValue.L195312201.AAWH.20191107.375735 | 2.8e-05 | 127 |




## LinkML Source

<details>

```yaml
name: qudt_numericValue
annotations:
  count:
    tag: count
    value: 154542
  decimal:
    tag: decimal
    value: 11383
  double:
    tag: double
    value: 103
description: No slot (predicate) description specified
title: numeric value
examples:
- object:
    example_object: '0.0'
    example_object_type: decimal
    example_predicate: qudt:numericValue
    example_subject: me_egad_data:mdl.0.0.NG/L
    example_subject_type: None
- object:
    example_object: '1.18e-06'
    example_object_type: double
    example_predicate: qudt:numericValue
    example_subject: me_egad_data:mdl.1.18e-06.MG/L
    example_subject_type: None
- object:
    example_object: '14.0'
    example_object_type: decimal
    example_predicate: qudt:numericValue
    example_subject: me_egad_data:quantityValue.1028303.ELL.20190405.45298906
    example_subject_type: coso_DetectQuantityValue
- object:
    example_object: '16000.0'
    example_object_type: decimal
    example_predicate: qudt:numericValue
    example_subject: me_egad_data:quantityValue.1095743.ELL.20190627.2706903
    example_subject_type: coso_NonDetectQuantityValue
- object:
    example_object: '2.8e-05'
    example_object_type: double
    example_predicate: qudt:numericValue
    example_subject: me_egad_data:quantityValue.L195312201.AAWH.20191107.375735
    example_subject_type: coso_DetectQuantityValue
from_schema: sawgraph-kg
source: http://qudt.org/2.1/schema/qudt
rank: 1000
slot_uri: qudt:numericValue
alias: qudt_numericValue
domain_of:
- coso_DetectQuantityValue
- coso_NonDetectQuantityValue
range: Any
any_of:
- range: decimal
- range: double
- range: qudt_NumericUnion

```
</details>