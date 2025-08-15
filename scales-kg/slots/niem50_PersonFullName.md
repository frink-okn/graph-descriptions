

# Slot: niem50_PersonFullName




This slot occurs 17954252 times.


URI: [niem50:PersonFullName](http://release.niem.gov/niem/niem-core/5.0/PersonFullName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Jxdm72Judge](../classes/Jxdm72Judge.md) |  |  no  |
| [Jxdm72CaseJudge](../classes/Jxdm72CaseJudge.md) |  |  no  |
| [Jxdm72CaseDefenseAttorney](../classes/Jxdm72CaseDefenseAttorney.md) |  |  no  |
| [ScalesParty](../classes/ScalesParty.md) |  |  no  |
| [Jxdm72CaseDefendantParty](../classes/Jxdm72CaseDefendantParty.md) |  |  no  |
| [Jxdm72Attorney](../classes/Jxdm72Attorney.md) |  |  no  |
| [Jxdm72CaseInitiatingAttorney](../classes/Jxdm72CaseInitiatingAttorney.md) |  |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)







## LinkML Source

<details>

```yaml
name: niem50_PersonFullName
from_schema: okns:scales-kg
rank: 1000
slot_uri: niem50:PersonFullName
alias: niem50_PersonFullName
domain_of:
- jxdm72_Attorney
- jxdm72_CaseDefendantParty
- jxdm72_CaseDefenseAttorney
- jxdm72_CaseInitiatingAttorney
- jxdm72_CaseJudge
- jxdm72_Judge
- scales_Party
range: string

```
</details>