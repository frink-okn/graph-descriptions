

# Slot: qudt_plainTextDescription


_No slot (predicate) description specified_






This slot occurs 3 times.


URI: [qudt:plainTextDescription](http://qudt.org/schema/qudt/plainTextDescription)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [QudtDerivedUnit](../classes/QudtDerivedUnit.md) | A DerivedUnit is a type specification for units that are derived from other u... |  no  |
| [QudtUnit](../classes/QudtUnit.md) | A unit of measure, or unit, is a particular quantity value that has been chos... |  yes  |
| [QudtOrderedType](../classes/QudtOrderedType.md) | Describes how a data or information structure is ordered |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| qudt_Unit | string | http://qudt.org/vocab/unit/MicroGM-PER-KiloGM | mass ratio as 0.000000001-fold of the SI base unit kilogram divided by the SI base unit kilogram | 3 |




## LinkML Source

<details>

```yaml
name: qudt_plainTextDescription
annotations:
  count:
    tag: count
    value: 3
description: No slot (predicate) description specified
examples:
- object:
    example_object: mass ratio as 0.000000001-fold of the SI base unit kilogram divided
      by the SI base unit kilogram
    example_object_type: string
    example_predicate: qudt:plainTextDescription
    example_subject: http://qudt.org/vocab/unit/MicroGM-PER-KiloGM
    example_subject_type: qudt_Unit
from_schema: sawgraph-kg
rank: 1000
slot_uri: qudt:plainTextDescription
alias: qudt_plainTextDescription
domain_of:
- qudt_OrderedType
- qudt_Unit
range: string

```
</details>