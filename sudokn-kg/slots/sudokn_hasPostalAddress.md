

# Slot: has postal address (sudokn_hasPostalAddress)


_TODO -- tell the world what this slot (predicate) describes._





URI: [sudokn:hasPostalAddress](http://asu.edu/semantics/SUDOKN/hasPostalAddress)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SudoknGeospatialLocation](../classes/SudoknGeospatialLocation.md) | TODO -- tell the world what this class (type) describes |  no  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | TODO -- tell the world what this class (type) describes |  no  |
| [IoManufacturer](../classes/IoManufacturer.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SudoknPostalAddress](../classes/SudoknPostalAddress.md)&nbsp;or&nbsp;<br />[SudoknUnitedStatesPostalCode](../classes/SudoknUnitedStatesPostalCode.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| sudokn:ZURN-site-SANFORD-27330 sudokn:hasPostalAddress sudokn:ZURN-site-SANFORD-27330-postal-address |
| sudokn:4FELDCO-site-DESPLAINES-60018 sudokn:hasPostalAddress sudokn:4FELDCO-site-DESPLAINES-60018-postal-address |
| sudokn:/Manufacturer_1 sudokn:hasPostalAddress sudokn:/UnitedStatesPostalCode_1 |
| sudokn:qualityproducts sudokn:hasPostalAddress sudokn:qualityproducts-PostalAddress |

## Comments

* 6948 occurrences with subject type sudokn_GeospatialLocation and object type sudokn_PostalAddress.
* 2414 occurrences with subject type sudokn_GeospatialLocation and object type uri.
* 1 occurrences with subject type owl_NamedIndividual and object type sudokn_UnitedStatesPostalCode.
* 11366 occurrences with subject type io_Manufacturer and object type sudokn_PostalAddress.

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
| self | sudokn:hasPostalAddress |
| native | sudokn-kg/:sudokn_hasPostalAddress |




## LinkML Source

<details>
```yaml
name: sudokn_hasPostalAddress
description: TODO -- tell the world what this slot (predicate) describes.
title: has postal address
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 6948 occurrences with subject type sudokn_GeospatialLocation and object type sudokn_PostalAddress.
- 2414 occurrences with subject type sudokn_GeospatialLocation and object type uri.
- 1 occurrences with subject type owl_NamedIndividual and object type sudokn_UnitedStatesPostalCode.
- 11366 occurrences with subject type io_Manufacturer and object type sudokn_PostalAddress.
examples:
- value: sudokn:ZURN-site-SANFORD-27330 sudokn:hasPostalAddress sudokn:ZURN-site-SANFORD-27330-postal-address
- value: sudokn:4FELDCO-site-DESPLAINES-60018 sudokn:hasPostalAddress sudokn:4FELDCO-site-DESPLAINES-60018-postal-address
- value: sudokn:/Manufacturer_1 sudokn:hasPostalAddress sudokn:/UnitedStatesPostalCode_1
- value: sudokn:qualityproducts sudokn:hasPostalAddress sudokn:qualityproducts-PostalAddress
from_schema: sudokn-kg
rank: 1000
slot_uri: sudokn:hasPostalAddress
alias: sudokn_hasPostalAddress
domain_of:
- io_Manufacturer
- owl_NamedIndividual
- sudokn_GeospatialLocation
subproperty_of: io_denotedBy
range: Any
any_of:
- range: sudokn_PostalAddress
- range: sudokn_UnitedStatesPostalCode
- range: uri

```
</details>