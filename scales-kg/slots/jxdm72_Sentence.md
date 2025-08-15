

# Slot: jxdm72_Sentence




This slot occurs 675670 times.


URI: [jxdm72:Sentence](http://release.niem.gov/niem/domains/jxdm/7.2/Sentence)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Jxdm72RegisterAction](../classes/Jxdm72RegisterAction.md) |  |  no  |
| [ScalesParty](../classes/ScalesParty.md) |  |  no  |







## Properties

* Range: [Jxdm72Sentence](../classes/Jxdm72Sentence.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Jxdm72Charge](../classes/Jxdm72Charge.md) | [jxdm72_ChargeSentence](../slots/jxdm72_ChargeSentence.md) | range | [Jxdm72Sentence](../classes/Jxdm72Sentence.md) |
| [Jxdm72RegisterAction](../classes/Jxdm72RegisterAction.md) | [Jxdm72Sentence](../classes/Jxdm72Sentence.md) | range | [Jxdm72Sentence](../classes/Jxdm72Sentence.md) |
| [ScalesParty](../classes/ScalesParty.md) | [Jxdm72Sentence](../classes/Jxdm72Sentence.md) | range | [Jxdm72Sentence](../classes/Jxdm72Sentence.md) |








## LinkML Source

<details>

```yaml
name: jxdm72_Sentence
from_schema: okns:scales-kg
rank: 1000
slot_uri: jxdm72:Sentence
alias: jxdm72_Sentence
domain_of:
- jxdm72_RegisterAction
- scales_Party
range: jxdm72_Sentence

```
</details>