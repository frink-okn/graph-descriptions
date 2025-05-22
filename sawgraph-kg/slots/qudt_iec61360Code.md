

# Slot: qudt_iec61360Code


_No slot (predicate) description specified_






This slot occurs 3 times.


URI: [qudt:iec61360Code](http://qudt.org/schema/qudt/iec61360Code)



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
| qudt_Unit | string | http://qudt.org/vocab/unit/MicroGM-PER-KiloGM | 0112/2///62720#UAA083 | 3 |




## LinkML Source

<details>

```yaml
name: qudt_iec61360Code
annotations:
  count:
    tag: count
    value: 3
description: No slot (predicate) description specified
examples:
- object:
    example_object: 0112/2///62720#UAA083
    example_object_type: string
    example_predicate: qudt:iec61360Code
    example_subject: http://qudt.org/vocab/unit/MicroGM-PER-KiloGM
    example_subject_type: qudt_Unit
from_schema: sawgraph-kg
rank: 1000
slot_uri: qudt:iec61360Code
alias: qudt_iec61360Code
domain_of:
- qudt_Unit
range: string

```
</details>