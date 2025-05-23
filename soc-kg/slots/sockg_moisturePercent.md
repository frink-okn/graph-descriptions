

# Slot: No slot (predicate) name specified (sockg_moisturePercent)


_No slot (predicate) description specified_






This slot occurs 846 times.


URI: [sockg:moisturePercent](https://idir.uta.edu/sockg-ontology/docs/moisturePercent)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgHarvestFraction](../classes/SockgHarvestFraction.md) | The HarvestFraction class represents the quantifiable metrics and characteris... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_HarvestFraction | double | sockg:individuals/191555 | 49.01409 | 846 |


## See Also

* [https://lod.nal.usda.gov/nalt/18883](https://lod.nal.usda.gov/nalt/18883)



## LinkML Source

<details>

```yaml
name: sockg_moisturePercent
annotations:
  count:
    tag: count
    value: 846
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '49.01409'
    example_object_type: double
    example_predicate: sockg:moisturePercent
    example_subject: sockg:individuals/191555
    example_subject_type: sockg_HarvestFraction
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/18883
rank: 1000
domain: sockg_HarvestFraction
slot_uri: sockg:moisturePercent
alias: sockg_moisturePercent
domain_of:
- sockg_HarvestFraction
range: Any
any_of:
- range: float
- range: double

```
</details>