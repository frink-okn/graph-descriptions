

# Slot: has ownership status classifier (sudokn_hasOwnershipStatusClassifier)




This slot occurs 1120 times.


URI: [sudokn:hasOwnershipStatusClassifier](http://asu.edu/semantics/SUDOKN/hasOwnershipStatusClassifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [IoManufacturer](../classes/IoManufacturer.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SudoknOwnershipStatusClassifier](../classes/SudoknOwnershipStatusClassifier.md)&nbsp;or&nbsp;<br />[OwlClass](../classes/OwlClass.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)







## LinkML Source

<details>

```yaml
name: sudokn_hasOwnershipStatusClassifier
title: has ownership status classifier
from_schema: okns:sudokn-kg
rank: 1000
domain: io_Organization
slot_uri: sudokn:hasOwnershipStatusClassifier
alias: sudokn_hasOwnershipStatusClassifier
domain_of:
- io_Manufacturer
range: Any
any_of:
- range: sudokn_OwnershipStatusClassifier
- range: owl_Class
- range: owl_NamedIndividual

```
</details>