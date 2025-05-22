

# Slot: qudt_symbol


_No slot (predicate) description specified_






This slot occurs 6 times.


URI: [qudt:symbol](http://qudt.org/schema/qudt/symbol)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [QudtDerivedUnit](../classes/QudtDerivedUnit.md) | A DerivedUnit is a type specification for units that are derived from other u... |  no  |
| [QudtUnit](../classes/QudtUnit.md) | A unit of measure, or unit, is a particular quantity value that has been chos... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| qudt_Unit | string | http://qudt.org/vocab/unit/MicroGM-PER-KiloGM | Î¼g/kg | 6 |




## LinkML Source

<details>

```yaml
name: qudt_symbol
annotations:
  count:
    tag: count
    value: 6
description: No slot (predicate) description specified
examples:
- object:
    example_object: Î¼g/kg
    example_object_type: string
    example_predicate: qudt:symbol
    example_subject: http://qudt.org/vocab/unit/MicroGM-PER-KiloGM
    example_subject_type: qudt_Unit
from_schema: sawgraph-kg
rank: 1000
slot_uri: qudt:symbol
alias: qudt_symbol
domain_of:
- qudt_Unit
range: string

```
</details>