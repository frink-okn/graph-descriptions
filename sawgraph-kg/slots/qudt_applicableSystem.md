

# Slot: qudt_applicableSystem


_No slot (predicate) description specified_






This slot occurs 20 times.


URI: [qudt:applicableSystem](http://qudt.org/schema/qudt/applicableSystem)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [QudtDerivedUnit](../classes/QudtDerivedUnit.md) | A DerivedUnit is a type specification for units that are derived from other u... |  no  |
| [QudtUnit](../classes/QudtUnit.md) | A unit of measure, or unit, is a particular quantity value that has been chos... |  yes  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| qudt_Unit | uri | http://qudt.org/vocab/unit/MicroGM-PER-KiloGM | http://qudt.org/vocab/sou/CGS | 20 |




## LinkML Source

<details>

```yaml
name: qudt_applicableSystem
annotations:
  count:
    tag: count
    value: 20
description: No slot (predicate) description specified
examples:
- object:
    example_object: http://qudt.org/vocab/sou/CGS
    example_object_type: uri
    example_predicate: qudt:applicableSystem
    example_subject: http://qudt.org/vocab/unit/MicroGM-PER-KiloGM
    example_subject_type: qudt_Unit
from_schema: sawgraph-kg
rank: 1000
slot_uri: qudt:applicableSystem
alias: qudt_applicableSystem
domain_of:
- qudt_Unit
range: uri

```
</details>