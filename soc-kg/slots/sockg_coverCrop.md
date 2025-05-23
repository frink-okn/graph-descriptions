

# Slot: No slot (predicate) name specified (sockg_coverCrop)


_No slot (predicate) description specified_






This slot occurs 194 times.


URI: [sockg:coverCrop](https://idir.uta.edu/sockg-ontology/docs/coverCrop)



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
| sockg_Treatment | string | sockg:individuals/363568 | Avena strigosa/Secale cereale (Black Oat/Rye) | 194 |


## See Also

* [https://lod.nal.usda.gov/nalt/28616](https://lod.nal.usda.gov/nalt/28616)



## LinkML Source

<details>

```yaml
name: sockg_coverCrop
annotations:
  count:
    tag: count
    value: 194
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Avena strigosa/Secale cereale (Black Oat/Rye)
    example_object_type: string
    example_predicate: sockg:coverCrop
    example_subject: sockg:individuals/363568
    example_subject_type: sockg_Treatment
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/28616
rank: 1000
domain: sockg_Treatment
slot_uri: sockg:coverCrop
alias: sockg_coverCrop
domain_of:
- sockg_Treatment
range: string

```
</details>