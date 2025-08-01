

# Slot: fio_epa_frs_replacedBy




This slot occurs 4 times.


URI: [fio-epa-frs:replacedBy](http://w3id.org/fio/v1/epa-frs#replacedBy)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Fio-epa-frsLegacySystem](../classes/Fio-epa-frsLegacySystem.md) |  |  no  |
| [Fio-epa-frsReportingSystem](../classes/Fio-epa-frsReportingSystem.md) |  |  no  |
| [Fio-epa-frsSiteSystem](../classes/Fio-epa-frsSiteSystem.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[Fio-epa-frsSiteSystem](../classes/Fio-epa-frsSiteSystem.md)&nbsp;or&nbsp;<br />[Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md)&nbsp;or&nbsp;<br />[Fio-epa-frsPermitSystem](../classes/Fio-epa-frsPermitSystem.md)







## LinkML Source

<details>

```yaml
name: fio-epa-frs_replacedBy
from_schema: okns:fiokg
exact_mappings:
- http://w3id.org/fio/v1/epa-frs#replacedBy
rank: 1000
slot_uri: fio-epa-frs:replacedBy
alias: fio_epa_frs_replacedBy
domain_of:
- fio-epa-frs_LegacySystem
- fio-epa-frs_ReportingSystem
- fio-epa-frs_SiteSystem
range: Any
any_of:
- range: owl_Thing
- range: fio-epa-frs_SiteSystem
- range: fio-epa-frs_ProgramInformationSystem
- range: fio-epa-frs_PermitSystem

```
</details>