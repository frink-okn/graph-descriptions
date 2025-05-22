

# Slot: qudt_ucumCode


_No slot (predicate) description specified_






This slot occurs 11 times.


URI: [qudt:ucumCode](http://qudt.org/schema/qudt/ucumCode)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [QudtDerivedUnit](../classes/QudtDerivedUnit.md) | A DerivedUnit is a type specification for units that are derived from other u... |  no  |
| [QudtUnit](../classes/QudtUnit.md) | A unit of measure, or unit, is a particular quantity value that has been chos... |  yes  |







## Properties

* Range: [QudtUCUMcs](../types/QudtUCUMcs.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| qudt_Unit | qudt_UCUMcs | http://qudt.org/vocab/unit/MicroGM-PER-KiloGM | ug.kg-1 | 11 |




## LinkML Source

<details>

```yaml
name: qudt_ucumCode
annotations:
  count:
    tag: count
    value: 11
description: No slot (predicate) description specified
examples:
- object:
    example_object: ug.kg-1
    example_object_type: qudt_UCUMcs
    example_predicate: qudt:ucumCode
    example_subject: http://qudt.org/vocab/unit/MicroGM-PER-KiloGM
    example_subject_type: qudt_Unit
from_schema: sawgraph-kg
rank: 1000
slot_uri: qudt:ucumCode
alias: qudt_ucumCode
domain_of:
- qudt_Unit
range: qudt_UCUMcs

```
</details>