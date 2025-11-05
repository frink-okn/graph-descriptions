

# Slot: has postal address (sudokn_hasPostalAddress)




This slot occurs 20729 times.


URI: [sudokn:hasPostalAddress](http://asu.edu/semantics/SUDOKN/hasPostalAddress)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SudoknGeospatialLocation](../classes/SudoknGeospatialLocation.md) |  |  no  |
| [IoManufacturer](../classes/IoManufacturer.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SudoknPostalAddress](../classes/SudoknPostalAddress.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[SudoknUSPostalCode](../classes/SudoknUSPostalCode.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)







## LinkML Source

<details>

```yaml
name: sudokn_hasPostalAddress
title: has postal address
from_schema: okns:sudokn-kg
rank: 1000
slot_uri: sudokn:hasPostalAddress
alias: sudokn_hasPostalAddress
domain_of:
- io_Manufacturer
- sudokn_GeospatialLocation
subproperty_of: io_denotedBy
range: Any
any_of:
- range: sudokn_PostalAddress
- range: owl_NamedIndividual
- range: sudokn_USPostalCode
- range: uri

```
</details>