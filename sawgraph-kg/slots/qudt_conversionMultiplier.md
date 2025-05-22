

# Slot: qudt_conversionMultiplier


_No slot (predicate) description specified_






This slot occurs 5 times.


URI: [qudt:conversionMultiplier](http://qudt.org/schema/qudt/conversionMultiplier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [QudtDerivedUnit](../classes/QudtDerivedUnit.md) | A DerivedUnit is a type specification for units that are derived from other u... |  no  |
| [QudtUnit](../classes/QudtUnit.md) | A unit of measure, or unit, is a particular quantity value that has been chos... |  yes  |







## Properties

* Range: [xsd:decimal](http://www.w3.org/2001/XMLSchema#decimal)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| qudt_Unit | decimal | http://qudt.org/vocab/unit/MicroGM-PER-KiloGM | 0.000000001 | 5 |




## LinkML Source

<details>

```yaml
name: qudt_conversionMultiplier
annotations:
  count:
    tag: count
    value: 5
description: No slot (predicate) description specified
examples:
- object:
    example_object: '0.000000001'
    example_object_type: decimal
    example_predicate: qudt:conversionMultiplier
    example_subject: http://qudt.org/vocab/unit/MicroGM-PER-KiloGM
    example_subject_type: qudt_Unit
from_schema: sawgraph-kg
rank: 1000
slot_uri: qudt:conversionMultiplier
alias: qudt_conversionMultiplier
domain_of:
- qudt_Unit
range: decimal

```
</details>