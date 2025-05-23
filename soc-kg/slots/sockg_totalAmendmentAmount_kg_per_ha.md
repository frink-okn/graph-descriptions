

# Slot: No slot (predicate) name specified (sockg_totalAmendmentAmount_kg_per_ha)


_No slot (predicate) description specified_






This slot occurs 17555 times.


URI: [sockg:totalAmendmentAmount_kg_per_ha](https://idir.uta.edu/sockg-ontology/docs/totalAmendmentAmount_kg_per_ha)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgAmendment](../classes/SockgAmendment.md) | An Amendment represents a specific alteration or addition made to agricultura... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Amendment | double | sockg:individuals/1 | 3363.0 | 17555 |


## See Also

* [https://lod.nal.usda.gov/nalt/1555434](https://lod.nal.usda.gov/nalt/1555434)



## LinkML Source

<details>

```yaml
name: sockg_totalAmendmentAmount_kg_per_ha
annotations:
  count:
    tag: count
    value: 17555
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '3363.0'
    example_object_type: double
    example_predicate: sockg:totalAmendmentAmount_kg_per_ha
    example_subject: sockg:individuals/1
    example_subject_type: sockg_Amendment
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/1555434
rank: 1000
domain: sockg_Amendment
slot_uri: sockg:totalAmendmentAmount_kg_per_ha
alias: sockg_totalAmendmentAmount_kg_per_ha
domain_of:
- sockg_Amendment
range: Any
any_of:
- range: float
- range: double

```
</details>