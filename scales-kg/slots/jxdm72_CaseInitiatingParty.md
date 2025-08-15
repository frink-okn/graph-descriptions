

# Slot: jxdm72_CaseInitiatingParty




This slot occurs 4892601 times.


URI: [jxdm72:CaseInitiatingParty](http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) |  |  no  |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Jxdm72CaseInitiatingParty](../classes/Jxdm72CaseInitiatingParty.md)&nbsp;or&nbsp;<br />[ScalesParty](../classes/ScalesParty.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [Jxdm72CaseInitiatingParty](../classes/Jxdm72CaseInitiatingParty.md) | any_of[range] | [Jxdm72CaseInitiatingParty](../classes/Jxdm72CaseInitiatingParty.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [Jxdm72CaseInitiatingParty](../classes/Jxdm72CaseInitiatingParty.md) | any_of[range] | [Jxdm72CaseInitiatingParty](../classes/Jxdm72CaseInitiatingParty.md) |








## LinkML Source

<details>

```yaml
name: jxdm72_CaseInitiatingParty
from_schema: okns:scales-kg
rank: 1000
slot_uri: jxdm72:CaseInitiatingParty
alias: jxdm72_CaseInitiatingParty
domain_of:
- scales_CivilCase
- scales_CriminalCase
range: Any
any_of:
- range: jxdm72_CaseInitiatingParty
- range: scales_Party

```
</details>