

# Slot: manufactures (sudokn_manufactures)


_TODO -- tell the world what this slot (predicate) describes._





URI: [sudokn:manufactures](http://asu.edu/semantics/SUDOKN/manufactures)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[IoMaterialProduct](../classes/IoMaterialProduct.md)






## Examples

| Value |
| --- |
| sudokn:PTPMANUFACTURING-company-inst sudokn:manufactures sudokn:WaterTreatmentComponents-product |

## Comments

* 71660 occurrences with subject type io_Manufacturer and object type io_MaterialProduct.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: sudokn-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sudokn:manufactures |
| native | sudokn-kg/:sudokn_manufactures |




## LinkML Source

<details>
```yaml
name: sudokn_manufactures
description: TODO -- tell the world what this slot (predicate) describes.
title: manufactures
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 71660 occurrences with subject type io_Manufacturer and object type io_MaterialProduct.
examples:
- value: sudokn:PTPMANUFACTURING-company-inst sudokn:manufactures sudokn:WaterTreatmentComponents-product
from_schema: sudokn-kg
rank: 1000
domain: io_Organization
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