

# Slot: hasMap (hsdo_hasMap)


_A URL to a map of the place._






This slot occurs 88 times.


URI: [hsdo:hasMap](http://schema.org/hasMap)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoPlace](../classes/HsdoPlace.md) | Entities that have a somewhat fixed, physical extension |  yes  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| hsdo_Place | uri | dreamkg:service/location/5552002522939392 | https://www.google.com/maps/?q=2107+West+Tioga+Street,+Philadelphia,+PA+19140/ | 88 |




## LinkML Source

<details>

```yaml
name: hsdo_hasMap
annotations:
  count:
    tag: count
    value: 88
description: A URL to a map of the place.
title: hasMap
examples:
- description: hsdo_Place→uri
  object:
    example_object: https://www.google.com/maps/?q=2107+West+Tioga+Street,+Philadelphia,+PA+19140/
    example_object_type: uri
    example_predicate: hsdo:hasMap
    example_subject: dreamkg:service/location/5552002522939392
    example_subject_type: hsdo_Place
from_schema: dream-kg
rank: 1000
slot_uri: hsdo:hasMap
alias: hsdo_hasMap
domain_of:
- hsdo_Place
range: uri

```
</details>