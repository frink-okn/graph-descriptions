

# Slot: No slot (predicate) name specified (sockg_fertilizerAmendmentClass)


_No slot (predicate) description specified_






This slot occurs 653 times.


URI: [sockg:fertilizerAmendmentClass](https://idir.uta.edu/sockg-ontology/docs/fertilizerAmendmentClass)



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
| sockg_Treatment | string | sockg:individuals/363559 | Integrated (Combination of organic and synthetic) | 653 |


## See Also

* [https://lod.nal.usda.gov/nalt/5568](https://lod.nal.usda.gov/nalt/5568)



## LinkML Source

<details>

```yaml
name: sockg_fertilizerAmendmentClass
annotations:
  count:
    tag: count
    value: 653
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Integrated (Combination of organic and synthetic)
    example_object_type: string
    example_predicate: sockg:fertilizerAmendmentClass
    example_subject: sockg:individuals/363559
    example_subject_type: sockg_Treatment
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/5568
rank: 1000
domain: sockg_Treatment
slot_uri: sockg:fertilizerAmendmentClass
alias: sockg_fertilizerAmendmentClass
domain_of:
- sockg_Treatment
range: string

```
</details>