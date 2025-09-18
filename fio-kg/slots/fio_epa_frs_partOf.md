

# Slot: fio_epa_frs_partOf




This slot occurs 3 times.


URI: [fio-epa-frs:partOf](http://w3id.org/fio/v1/epa-frs#partOf)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Fio-epa-frsPermitSystem](../classes/Fio-epa-frsPermitSystem.md) |  |  no  |
| [Fio-epa-frsReportingSystem](../classes/Fio-epa-frsReportingSystem.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md)&nbsp;or&nbsp;<br />[Fio-epa-frsReportingSystem](../classes/Fio-epa-frsReportingSystem.md)







## LinkML Source

<details>

```yaml
name: fio-epa-frs_partOf
from_schema: okns:fio-kg
exact_mappings:
- http://w3id.org/fio/v1/epa-frs#partOf
rank: 1000
slot_uri: fio-epa-frs:partOf
alias: fio_epa_frs_partOf
domain_of:
- fio-epa-frs_PermitSystem
- fio-epa-frs_ReportingSystem
range: Any
any_of:
- range: fio-epa-frs_ProgramInformationSystem
- range: fio-epa-frs_ReportingSystem

```
</details>