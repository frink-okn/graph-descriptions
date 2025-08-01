

# Slot: fio_epa_frs_fromSystem




This slot occurs 1231696 times.


URI: [fio-epa-frs:fromSystem](http://w3id.org/fio/v1/epa-frs#fromSystem)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |
| [Node513](../classes/Node513.md) |  |  no  |
| [Node518](../classes/Node518.md) |  |  no  |
| [Fio-epa-frsRecord](../classes/Fio-epa-frsRecord.md) |  |  no  |
| [Node501](../classes/Node501.md) |  |  no  |
| [Node515](../classes/Node515.md) |  |  no  |
| [Node519](../classes/Node519.md) |  |  no  |
| [Node523](../classes/Node523.md) |  |  no  |
| [Node521](../classes/Node521.md) |  |  no  |
| [Fio-epa-frsSupplementalRecord](../classes/Fio-epa-frsSupplementalRecord.md) | Supplemental Record that relates to a facility but primarily identifies somet... |  no  |
| [Node359](../classes/Node359.md) |  |  no  |
| [Node508](../classes/Node508.md) |  |  no  |
| [Node507](../classes/Node507.md) |  |  no  |
| [Node499](../classes/Node499.md) |  |  no  |
| [Node517](../classes/Node517.md) |  |  no  |
| [Node506](../classes/Node506.md) |  |  no  |
| [Node510](../classes/Node510.md) |  |  no  |
| [Node502](../classes/Node502.md) |  |  no  |
| [Node512](../classes/Node512.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Fio-epa-frsStateSystem](../classes/Fio-epa-frsStateSystem.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[Fio-epa-frsRegistrySystem](../classes/Fio-epa-frsRegistrySystem.md)&nbsp;or&nbsp;<br />[Fio-epa-frsLegacySystem](../classes/Fio-epa-frsLegacySystem.md)&nbsp;or&nbsp;<br />[Fio-epa-frsComplianceSystem](../classes/Fio-epa-frsComplianceSystem.md)&nbsp;or&nbsp;<br />[Fio-epa-frsPermitSystem](../classes/Fio-epa-frsPermitSystem.md)&nbsp;or&nbsp;<br />[Fio-epa-frsEnforcementSystem](../classes/Fio-epa-frsEnforcementSystem.md)&nbsp;or&nbsp;<br />[Fio-epa-frsTribalSystem](../classes/Fio-epa-frsTribalSystem.md)&nbsp;or&nbsp;<br />[Fio-epa-frsProjectSystem](../classes/Fio-epa-frsProjectSystem.md)&nbsp;or&nbsp;<br />[Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md)&nbsp;or&nbsp;<br />[Fio-epa-frsSiteSystem](../classes/Fio-epa-frsSiteSystem.md)&nbsp;or&nbsp;<br />[Fio-epa-frsGrantSystem](../classes/Fio-epa-frsGrantSystem.md)&nbsp;or&nbsp;<br />[Fio-epa-frsReportingSystem](../classes/Fio-epa-frsReportingSystem.md)







## LinkML Source

<details>

```yaml
name: fio-epa-frs_fromSystem
from_schema: okns:fiokg
exact_mappings:
- http://w3id.org/fio/v1/epa-frs#fromSystem
rank: 1000
slot_uri: fio-epa-frs:fromSystem
alias: fio_epa_frs_fromSystem
domain_of:
- __node359
- __node499
- __node501
- __node502
- __node506
- __node507
- __node508
- __node510
- __node512
- __node513
- __node515
- __node517
- __node518
- __node519
- __node521
- __node523
- fio-epa-frs_FRS-Facility
- fio-epa-frs_Record
- fio-epa-frs_SupplementalRecord
range: Any
any_of:
- range: fio-epa-frs_StateSystem
- range: owl_Thing
- range: fio-epa-frs_RegistrySystem
- range: fio-epa-frs_LegacySystem
- range: fio-epa-frs_ComplianceSystem
- range: fio-epa-frs_PermitSystem
- range: fio-epa-frs_EnforcementSystem
- range: fio-epa-frs_TribalSystem
- range: fio-epa-frs_ProjectSystem
- range: fio-epa-frs_ProgramInformationSystem
- range: fio-epa-frs_SiteSystem
- range: fio-epa-frs_GrantSystem
- range: fio-epa-frs_ReportingSystem

```
</details>