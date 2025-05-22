

# Slot: qudt_qkdvNumerator


_No slot (predicate) description specified_






This slot occurs 1 times.


URI: [qudt:qkdvNumerator](http://qudt.org/schema/qudt/qkdvNumerator)



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
| qudt_Unit | uri | http://qudt.org/vocab/unit/MicroGM-PER-KiloGM | http://qudt.org/vocab/dimensionvector/A0E0L0I0M1H0T0D0 | 1 |




## LinkML Source

<details>

```yaml
name: qudt_qkdvNumerator
annotations:
  count:
    tag: count
    value: 1
description: No slot (predicate) description specified
examples:
- object:
    example_object: http://qudt.org/vocab/dimensionvector/A0E0L0I0M1H0T0D0
    example_object_type: uri
    example_predicate: qudt:qkdvNumerator
    example_subject: http://qudt.org/vocab/unit/MicroGM-PER-KiloGM
    example_subject_type: qudt_Unit
from_schema: sawgraph-kg
rank: 1000
slot_uri: qudt:qkdvNumerator
alias: qudt_qkdvNumerator
domain_of:
- qudt_Unit
range: uri

```
</details>