

# Slot: sockg_tillageDescriptor


_No slot (predicate) description specified_






This slot occurs 719 times.


URI: [sockg:tillageDescriptor](https://idir.uta.edu/sockg-ontology/docs/tillageDescriptor)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgTreatment](../classes/SockgTreatment.md) | The Treatment class encompasses various agricultural practices and management... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Treatment | string | sockg:individuals/363558 | Conventional Till | 719 |




## LinkML Source

<details>

```yaml
name: sockg_tillageDescriptor
annotations:
  count:
    tag: count
    value: 719
description: No slot (predicate) description specified
examples:
- object:
    example_object: Conventional Till
    example_object_type: string
    example_predicate: sockg:tillageDescriptor
    example_subject: sockg:individuals/363558
    example_subject_type: sockg_Treatment
from_schema: soc-kg
rank: 1000
slot_uri: sockg:tillageDescriptor
alias: sockg_tillageDescriptor
domain_of:
- sockg_Treatment
range: string

```
</details>