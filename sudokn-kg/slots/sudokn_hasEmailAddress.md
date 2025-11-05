

# Slot: has email address (sudokn_hasEmailAddress)




This slot occurs 1 times.


URI: [sudokn:hasEmailAddress](http://asu.edu/semantics/SUDOKN/hasEmailAddress)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[SudoknEmailAddress](../classes/SudoknEmailAddress.md)







## LinkML Source

<details>

```yaml
name: sudokn_hasEmailAddress
title: has email address
from_schema: okns:sudokn-kg
rank: 1000
domain: io_Organization
slot_uri: sudokn:hasEmailAddress
alias: sudokn_hasEmailAddress
domain_of:
- io_Manufacturer
range: Any
any_of:
- range: owl_NamedIndividual
- range: sudokn_EmailAddress

```
</details>