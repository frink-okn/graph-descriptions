

# Slot: scales_Party




This slot occurs 380643 times.


URI: [scales:Party](http://schemas.scales-okn.org/rdf/scales#Party)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) |  |  no  |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) |  |  no  |







## Properties

* Range: [ScalesParty](../classes/ScalesParty.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [Jxdm72CaseInitiatingParty](../classes/Jxdm72CaseInitiatingParty.md) | any_of[range] | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [ScalesParty](../classes/ScalesParty.md) | range | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [Jxdm72CaseDefendantParty](../classes/Jxdm72CaseDefendantParty.md) | any_of[range] | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [Jxdm72CaseInitiatingParty](../classes/Jxdm72CaseInitiatingParty.md) | any_of[range] | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [ScalesParty](../classes/ScalesParty.md) | range | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [Jxdm72CaseDefendantParty](../classes/Jxdm72CaseDefendantParty.md) | any_of[range] | [ScalesParty](../classes/ScalesParty.md) |








## LinkML Source

<details>

```yaml
name: scales_Party
from_schema: okns:scales-kg
rank: 1000
slot_uri: scales:Party
alias: scales_Party
domain_of:
- scales_CivilCase
- scales_CriminalCase
range: scales_Party

```
</details>