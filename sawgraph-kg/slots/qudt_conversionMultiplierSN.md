

# Slot: qudt_conversionMultiplierSN


_No slot (predicate) description specified_






This slot occurs 5 times.


URI: [qudt:conversionMultiplierSN](http://qudt.org/schema/qudt/conversionMultiplierSN)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [QudtDerivedUnit](../classes/QudtDerivedUnit.md) | A DerivedUnit is a type specification for units that are derived from other u... |  no  |
| [QudtUnit](../classes/QudtUnit.md) | A unit of measure, or unit, is a particular quantity value that has been chos... |  yes  |







## Properties

* Range: [xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| qudt_Unit | double | http://qudt.org/vocab/unit/MicroGM-PER-KiloGM | 1e-09 | 5 |




## LinkML Source

<details>

```yaml
name: qudt_conversionMultiplierSN
annotations:
  count:
    tag: count
    value: 5
description: No slot (predicate) description specified
examples:
- object:
    example_object: 1e-09
    example_object_type: double
    example_predicate: qudt:conversionMultiplierSN
    example_subject: http://qudt.org/vocab/unit/MicroGM-PER-KiloGM
    example_subject_type: qudt_Unit
from_schema: sawgraph-kg
rank: 1000
slot_uri: qudt:conversionMultiplierSN
alias: qudt_conversionMultiplierSN
domain_of:
- qudt_Unit
range: double

```
</details>