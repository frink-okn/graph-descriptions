

# Slot: No slot (predicate) name specified (sockg_nonHarvestedResidueMoisturePercent)


_No slot (predicate) description specified_






This slot occurs 1372 times.


URI: [sockg:nonHarvestedResidueMoisturePercent](https://idir.uta.edu/sockg-ontology/docs/nonHarvestedResidueMoisturePercent)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgHarvest](../classes/SockgHarvest.md) | Harvest represents the process of collecting mature crops from the fields, wi... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Harvest | double | sockg:individuals/173031 | 3.055556 | 1372 |


## See Also

* [https://lod.nal.usda.gov/nalt/18883](https://lod.nal.usda.gov/nalt/18883)



## LinkML Source

<details>

```yaml
name: sockg_nonHarvestedResidueMoisturePercent
annotations:
  count:
    tag: count
    value: 1372
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '3.055556'
    example_object_type: double
    example_predicate: sockg:nonHarvestedResidueMoisturePercent
    example_subject: sockg:individuals/173031
    example_subject_type: sockg_Harvest
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/18883
rank: 1000
domain: sockg_Harvest
slot_uri: sockg:nonHarvestedResidueMoisturePercent
alias: sockg_nonHarvestedResidueMoisturePercent
domain_of:
- sockg_Harvest
range: Any
any_of:
- range: float
- range: double

```
</details>