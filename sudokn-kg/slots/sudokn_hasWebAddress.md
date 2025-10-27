

# Slot: has web address (sudokn_hasWebAddress)




This slot occurs 1 times.


URI: [sudokn:hasWebAddress](http://asu.edu/semantics/SUDOKN/hasWebAddress)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[SudoknWebAddress](../classes/SudoknWebAddress.md)







## LinkML Source

<details>

```yaml
name: sudokn_hasWebAddress
title: has web address
from_schema: okns:sudokn-kg
rank: 1000
domain: io_Organization
slot_uri: sudokn:hasWebAddress
alias: sudokn_hasWebAddress
domain_of:
- io_Manufacturer
range: Any
any_of:
- range: owl_NamedIndividual
- range: sudokn_WebAddress

```
</details>