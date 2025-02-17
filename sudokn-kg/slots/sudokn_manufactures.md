

# Slot: No slot (predicate) name specified (sudokn_manufactures)


_No slot (predicate) description specified_






This slot occurs 71660 times.


URI: [sudokn:manufactures](http://asu.edu/semantics/SUDOKN/manufactures)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[IoMaterialProduct](../classes/IoMaterialProduct.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | [sudokn_manufactures](../slots/sudokn_manufactures.md) | domain | [sudokn_manufactures](../slots/sudokn_manufactures.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| io_Manufacturer | io_MaterialProduct | sudokn:101PIPE-company-inst | sudokn:BlowoffStations-product | 71660 |




## LinkML Source

<details>

```yaml
name: sudokn_manufactures
annotations:
  count:
    tag: count
    value: 71660
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sudokn:BlowoffStations-product
    example_object_type: io_MaterialProduct
    example_predicate: sudokn:manufactures
    example_subject: sudokn:101PIPE-company-inst
    example_subject_type: io_Manufacturer
from_schema: sudokn-kg
rank: 1000
domain: sudokn_manufactures
slot_uri: sudokn:manufactures
alias: sudokn_manufactures
domain_of:
- io_Manufacturer
range: Any
any_of:
- range: uri
- range: io_MaterialProduct

```
</details>