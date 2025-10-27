

# Slot: attests to (sudokn_attestsTo)




This slot occurs 2 times.


URI: [sudokn:attestsTo](http://asu.edu/semantics/SUDOKN/attestsTo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SudoknAS9100Certificate](../classes/SudoknAS9100Certificate.md) |  |  no  |
| [SudoknISO9000Certificate](../classes/SudoknISO9000Certificate.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[IoCapability](../classes/IoCapability.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[SudoknQualityManagementCapability](../classes/SudoknQualityManagementCapability.md)







## LinkML Source

<details>

```yaml
name: sudokn_attestsTo
title: attests to
from_schema: okns:sudokn-kg
rank: 1000
domain: sudokn_Certificate
slot_uri: sudokn:attestsTo
alias: sudokn_attestsTo
domain_of:
- sudokn_AS9100Certificate
- sudokn_ISO9000Certificate
range: Any
any_of:
- range: io_Capability
- range: owl_NamedIndividual
- range: sudokn_QualityManagementCapability

```
</details>