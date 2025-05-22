

# Slot: No slot (predicate) name specified (dct_description)


_No slot (predicate) description specified_






This slot occurs 5 times.


URI: [dct:description](http://purl.org/dc/terms/description)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [QudtEnumeratedValue](../classes/QudtEnumeratedValue.md) | <p>This class is for all enumerated and/or coded values |  yes  |
| [Vaem#GraphMetaData](../classes/Vaem#GraphMetaData.md) | No class (type) description specified |  yes  |
| [QudtEndianType](../classes/QudtEndianType.md) | No class (type) description specified |  no  |
| [QudtTransformType](../classes/QudtTransformType.md) | No class (type) description specified |  no  |
| [QudtUnit](../classes/QudtUnit.md) | A unit of measure, or unit, is a particular quantity value that has been chos... |  yes  |
| [Vaem#Party](../classes/Vaem#Party.md) | No class (type) description specified |  yes  |
| [QudtCardinalityType](../classes/QudtCardinalityType.md) | ␊  In mathematics, the cardinality of a set is a measure of the number of ele... |  yes  |
| [QudtRuleType](../classes/QudtRuleType.md) | No class (type) description specified |  no  |
| [QudtDerivedUnit](../classes/QudtDerivedUnit.md) | A DerivedUnit is a type specification for units that are derived from other u... |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[RdfHTML](../types/RdfHTML.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| qudt_Unit | rdf_HTML | http://qudt.org/vocab/unit/MicroGM-PER-KiloGM | mass ratio as 0.000000001-fold of the SI base unit kilogram divided by the SI base unit kilogram | 4 |
| qudt_EnumeratedValue | string | coso:non-detect | Non-Detect Value | 1 |




## LinkML Source

<details>

```yaml
name: dct_description
annotations:
  count:
    tag: count
    value: 5
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: mass ratio as 0.000000001-fold of the SI base unit kilogram divided
      by the SI base unit kilogram
    example_object_type: rdf_HTML
    example_predicate: dct:description
    example_subject: http://qudt.org/vocab/unit/MicroGM-PER-KiloGM
    example_subject_type: qudt_Unit
- object:
    example_object: Non-Detect Value
    example_object_type: string
    example_predicate: dct:description
    example_subject: coso:non-detect
    example_subject_type: qudt_EnumeratedValue
from_schema: sawgraph-kg
rank: 1000
slot_uri: dct:description
alias: dct_description
domain_of:
- qudt_CardinalityType
- qudt_EnumeratedValue
- qudt_Unit
- vaem_#GraphMetaData
- vaem_#Party
range: Any
any_of:
- range: rdf_HTML
- range: string

```
</details>