

# Slot: jxdm72_CaseCourt




This slot occurs 4164091 times.


URI: [jxdm72:CaseCourt](http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) |  |  no  |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Jxdm72Court](../classes/Jxdm72Court.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)







## LinkML Source

<details>

```yaml
name: jxdm72_CaseCourt
from_schema: okns:scales-kg
rank: 1000
slot_uri: jxdm72:CaseCourt
alias: jxdm72_CaseCourt
domain_of:
- scales_CivilCase
- scales_CriminalCase
range: Any
any_of:
- range: jxdm72_Court
- range: string

```
</details>