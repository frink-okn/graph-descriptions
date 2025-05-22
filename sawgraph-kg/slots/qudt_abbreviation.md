

# Slot: abbreviation (qudt_abbreviation)


_An abbreviation for a unit is a short ASCII string that is used in place of the full name for the unit in contexts where non-ASCII characters would be problematic, or where using the abbreviation will enhance readability. When a power of abase unit needs to be expressed, such as squares this can be done using abbreviations rather than symbols. For example, <em>sq ft</em> means <em>square foot</em>, and <em>cu ft</em> means <em>cubic foot</em>._






This slot occurs 1 times.


URI: [qudt:abbreviation](http://qudt.org/schema/qudt/abbreviation)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [QudtEndianType](../classes/QudtEndianType.md) | No class (type) description specified |  no  |
| [QudtEnumeratedValue](../classes/QudtEnumeratedValue.md) | <p>This class is for all enumerated and/or coded values |  yes  |
| [QudtRuleType](../classes/QudtRuleType.md) | No class (type) description specified |  no  |
| [QudtTransformType](../classes/QudtTransformType.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| qudt_EnumeratedValue | string | coso:non-detect | ND | 1 |




## LinkML Source

<details>

```yaml
name: qudt_abbreviation
annotations:
  count:
    tag: count
    value: 1
description: An abbreviation for a unit is a short ASCII string that is used in place
  of the full name for the unit in contexts where non-ASCII characters would be problematic,
  or where using the abbreviation will enhance readability. When a power of abase
  unit needs to be expressed, such as squares this can be done using abbreviations
  rather than symbols. For example, <em>sq ft</em> means <em>square foot</em>, and
  <em>cu ft</em> means <em>cubic foot</em>.
title: abbreviation
examples:
- object:
    example_object: ND
    example_object_type: string
    example_predicate: qudt:abbreviation
    example_subject: coso:non-detect
    example_subject_type: qudt_EnumeratedValue
from_schema: sawgraph-kg
source: http://qudt.org/2.1/schema/qudt
rank: 1000
slot_uri: qudt:abbreviation
alias: qudt_abbreviation
domain_of:
- qudt_EnumeratedValue
range: string

```
</details>