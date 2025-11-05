

# Slot: has name (sudokn_hasName)




This slot occurs 1 times.


URI: [sudokn:hasName](http://asu.edu/semantics/SUDOKN/hasName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[SudoknOrganizationName](../classes/SudoknOrganizationName.md)







## LinkML Source

<details>

```yaml
name: sudokn_hasName
title: has name
from_schema: okns:sudokn-kg
rank: 1000
slot_uri: sudokn:hasName
alias: sudokn_hasName
domain_of:
- io_Manufacturer
subproperty_of: io_denotedBy
range: Any
any_of:
- range: owl_NamedIndividual
- range: sudokn_OrganizationName

```
</details>