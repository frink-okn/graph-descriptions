

# Slot: jxdm72_CaseJudge




This slot occurs 4424121 times.


URI: [jxdm72:CaseJudge](http://release.niem.gov/niem/domains/jxdm/7.2/CaseJudge)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) |  |  no  |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Jxdm72CaseJudge](../classes/Jxdm72CaseJudge.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [Jxdm72CaseJudge](../classes/Jxdm72CaseJudge.md) | any_of[range] | [Jxdm72CaseJudge](../classes/Jxdm72CaseJudge.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [Jxdm72CaseJudge](../classes/Jxdm72CaseJudge.md) | any_of[range] | [Jxdm72CaseJudge](../classes/Jxdm72CaseJudge.md) |








## LinkML Source

<details>

```yaml
name: jxdm72_CaseJudge
from_schema: okns:scales-kg
rank: 1000
slot_uri: jxdm72:CaseJudge
alias: jxdm72_CaseJudge
domain_of:
- scales_CivilCase
- scales_CriminalCase
range: Any
any_of:
- range: jxdm72_CaseJudge
- range: uri

```
</details>