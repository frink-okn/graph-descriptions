

# Slot: No slot (predicate) name specified (sockg_soilTemperatureSd_degC)


_No slot (predicate) description specified_






This slot occurs 6403 times.


URI: [sockg:soilTemperatureSd_degC](https://idir.uta.edu/sockg-ontology/docs/soilTemperatureSd_degC)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGasSample](../classes/SockgGasSample.md) | GasSample represents a collection of measurements related to greenhouse gas e... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_GasSample | double | sockg:individuals/114567 | 0.65 | 6403 |


## See Also

* [https://lod.nal.usda.gov/nalt/61641](https://lod.nal.usda.gov/nalt/61641)



## LinkML Source

<details>

```yaml
name: sockg_soilTemperatureSd_degC
annotations:
  count:
    tag: count
    value: 6403
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '0.65'
    example_object_type: double
    example_predicate: sockg:soilTemperatureSd_degC
    example_subject: sockg:individuals/114567
    example_subject_type: sockg_GasSample
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/61641
rank: 1000
domain: sockg_GasSample
slot_uri: sockg:soilTemperatureSd_degC
alias: sockg_soilTemperatureSd_degC
domain_of:
- sockg_GasSample
range: Any
any_of:
- range: double
- range: float

```
</details>