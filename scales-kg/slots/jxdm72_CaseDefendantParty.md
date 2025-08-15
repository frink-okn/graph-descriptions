

# Slot: jxdm72_CaseDefendantParty




This slot occurs 6231746 times.


URI: [jxdm72:CaseDefendantParty](http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) |  |  no  |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Jxdm72CaseDefendantParty](../classes/Jxdm72CaseDefendantParty.md)&nbsp;or&nbsp;<br />[ScalesParty](../classes/ScalesParty.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Jxdm72Charge](../classes/Jxdm72Charge.md) | [jxdm72_ChargeSubject](../slots/jxdm72_ChargeSubject.md) | range | [Jxdm72CaseDefendantParty](../classes/Jxdm72CaseDefendantParty.md) |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [Jxdm72CaseDefendantParty](../classes/Jxdm72CaseDefendantParty.md) | any_of[range] | [Jxdm72CaseDefendantParty](../classes/Jxdm72CaseDefendantParty.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [Jxdm72CaseDefendantParty](../classes/Jxdm72CaseDefendantParty.md) | any_of[range] | [Jxdm72CaseDefendantParty](../classes/Jxdm72CaseDefendantParty.md) |








## LinkML Source

<details>

```yaml
name: jxdm72_CaseDefendantParty
from_schema: okns:scales-kg
rank: 1000
slot_uri: jxdm72:CaseDefendantParty
alias: jxdm72_CaseDefendantParty
domain_of:
- scales_CivilCase
- scales_CriminalCase
range: Any
any_of:
- range: jxdm72_CaseDefendantParty
- range: scales_Party

```
</details>