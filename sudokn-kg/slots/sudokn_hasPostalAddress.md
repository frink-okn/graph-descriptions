

# Slot: No slot (predicate) name specified (sudokn_hasPostalAddress)


_No slot (predicate) description specified_






This slot occurs 20729 times.


URI: [sudokn:hasPostalAddress](http://asu.edu/semantics/SUDOKN/hasPostalAddress)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SudoknGeospatialLocation](../classes/SudoknGeospatialLocation.md) | No class (type) description specified |  yes  |
| [IoManufacturer](../classes/IoManufacturer.md) | No class (type) description specified |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[SudoknPostalAddress](../classes/SudoknPostalAddress.md)&nbsp;or&nbsp;<br />[SudoknUnitedStatesPostalCode](../classes/SudoknUnitedStatesPostalCode.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sudokn_GeospatialLocation | sudokn_PostalAddress | sudokn:101PIPE-site-FONTANA-92335 | sudokn:101PIPE-site-FONTANA-92335-postal-address | 6948 |
| sudokn_GeospatialLocation | uri | sudokn:4FELDCO-site-DESPLAINES-60018 | sudokn:4FELDCO-site-DESPLAINES-60018-postal-address | 2414 |
| owl_NamedIndividual | owl_NamedIndividual | sudokn:/Manufacturer_1 | sudokn:/UnitedStatesPostalCode_1 | 1 |
| owl_NamedIndividual | sudokn_UnitedStatesPostalCode | sudokn:/Manufacturer_1 | sudokn:/UnitedStatesPostalCode_1 | 1 |
| io_Manufacturer | owl_NamedIndividual | sudokn:/Manufacturer_1 | sudokn:/UnitedStatesPostalCode_1 | 1 |
| io_Manufacturer | sudokn_UnitedStatesPostalCode | sudokn:/Manufacturer_1 | sudokn:/UnitedStatesPostalCode_1 | 1 |
| io_Manufacturer | sudokn_PostalAddress | sudokn:101PIPE-company-inst | sudokn:101PIPE-PostalAddress | 11366 |




## LinkML Source

<details>

```yaml
name: sudokn_hasPostalAddress
annotations:
  count:
    tag: count
    value: 20729
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sudokn:101PIPE-site-FONTANA-92335-postal-address
    example_object_type: sudokn_PostalAddress
    example_predicate: sudokn:hasPostalAddress
    example_subject: sudokn:101PIPE-site-FONTANA-92335
    example_subject_type: sudokn_GeospatialLocation
- object:
    example_object: sudokn:4FELDCO-site-DESPLAINES-60018-postal-address
    example_object_type: uri
    example_predicate: sudokn:hasPostalAddress
    example_subject: sudokn:4FELDCO-site-DESPLAINES-60018
    example_subject_type: sudokn_GeospatialLocation
- object:
    example_object: sudokn:/UnitedStatesPostalCode_1
    example_object_type: owl_NamedIndividual
    example_predicate: sudokn:hasPostalAddress
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: owl_NamedIndividual
- object:
    example_object: sudokn:/UnitedStatesPostalCode_1
    example_object_type: sudokn_UnitedStatesPostalCode
    example_predicate: sudokn:hasPostalAddress
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: owl_NamedIndividual
- object:
    example_object: sudokn:/UnitedStatesPostalCode_1
    example_object_type: owl_NamedIndividual
    example_predicate: sudokn:hasPostalAddress
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: io_Manufacturer
- object:
    example_object: sudokn:/UnitedStatesPostalCode_1
    example_object_type: sudokn_UnitedStatesPostalCode
    example_predicate: sudokn:hasPostalAddress
    example_subject: sudokn:/Manufacturer_1
    example_subject_type: io_Manufacturer
- object:
    example_object: sudokn:101PIPE-PostalAddress
    example_object_type: sudokn_PostalAddress
    example_predicate: sudokn:hasPostalAddress
    example_subject: sudokn:101PIPE-company-inst
    example_subject_type: io_Manufacturer
from_schema: sudokn-kg
rank: 1000
slot_uri: sudokn:hasPostalAddress
alias: sudokn_hasPostalAddress
domain_of:
- io_Manufacturer
- owl_NamedIndividual
- sudokn_GeospatialLocation
range: Any
any_of:
- range: owl_NamedIndividual
- range: sudokn_PostalAddress
- range: sudokn_UnitedStatesPostalCode
- range: uri

```
</details>