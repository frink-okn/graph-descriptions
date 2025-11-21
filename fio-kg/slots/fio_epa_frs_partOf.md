

# Slot: fio_epa_frs_partOf




This slot occurs 3 times.


URI: [fio-epa-frs:partOf](http://w3id.org/fio/v1/epa-frs#partOf)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Fio-epa-frsReportingSystem](../classes/Fio-epa-frsReportingSystem.md) |  |  no  |
| [Fio-epa-frsPermitSystem](../classes/Fio-epa-frsPermitSystem.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[Fio-epa-frsReportingSystem](../classes/Fio-epa-frsReportingSystem.md)&nbsp;or&nbsp;<br />[Fio-epa-frsProgramInformationSystem](../classes/Fio-epa-frsProgramInformationSystem.md)







## LinkML Source

<details>

```yaml
name: fio-epa-frs_partOf
from_schema: okns:fio-kg
rank: 1000
slot_uri: fio-epa-frs:partOf
alias: fio_epa_frs_partOf
domain_of:
- fio-epa-frs_PermitSystem
- fio-epa-frs_ReportingSystem
range: Any
any_of:
- range: rdfs_Resource
- range: fio-epa-frs_ReportingSystem
- range: fio-epa-frs_ProgramInformationSystem

```
</details>