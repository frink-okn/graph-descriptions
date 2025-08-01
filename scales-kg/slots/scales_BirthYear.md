

# Slot: scales_BirthYear


_No slot (predicate) description specified_






This slot occurs 91623 times.


URI: [scales:BirthYear](http://schemas.scales-okn.org/rdf/scales#BirthYear)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Niem50Person](../classes/Niem50Person.md) | No class (type) description specified |  yes  |







## Properties

* Range: [XsdGYear](../types/XsdGYear.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| niem50_Person | xsd_gYear | scales:ArrestSubject/ga-atlanta-pd-100720495 | 1975 | 91623 |




## LinkML Source

<details>

```yaml
name: scales_BirthYear
annotations:
  count:
    tag: count
    value: 91623
description: No slot (predicate) description specified
examples:
- object:
    example_object: '1975'
    example_object_type: xsd_gYear
    example_predicate: scales:BirthYear
    example_subject: scales:ArrestSubject/ga-atlanta-pd-100720495
    example_subject_type: niem50_Person
from_schema: scales-kg
rank: 1000
slot_uri: scales:BirthYear
alias: scales_BirthYear
domain_of:
- niem50_Person
range: xsd_gYear

```
</details>