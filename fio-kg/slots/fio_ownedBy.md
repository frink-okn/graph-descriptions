

# Slot: fio_ownedBy




This slot occurs 1477 times.


URI: [fio:ownedBy](http://w3id.org/fio/v1/fio#ownedBy)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md) | Facility identified as potentially handling PFAS in EPA PFAS Analytic tools b... |  no  |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Fio-epa-frsAgency](../classes/Fio-epa-frsAgency.md)&nbsp;or&nbsp;<br />[Fio-epa-frsAgency.Commerce](../classes/Fio-epa-frsAgency.Commerce.md)&nbsp;or&nbsp;<br />[Fio-epa-frsAgency.Interior](../classes/Fio-epa-frsAgency.Interior.md)&nbsp;or&nbsp;<br />[Fio-epa-frsAgency.Justice](../classes/Fio-epa-frsAgency.Justice.md)&nbsp;or&nbsp;<br />[Fio-epa-frsAgency.Transportation](../classes/Fio-epa-frsAgency.Transportation.md)&nbsp;or&nbsp;<br />[Fio-epa-frsAgency.HealthandHumanServices](../classes/Fio-epa-frsAgency.HealthandHumanServices.md)&nbsp;or&nbsp;<br />[Fio-epa-frsAgency.Energy](../classes/Fio-epa-frsAgency.Energy.md)&nbsp;or&nbsp;<br />[Fio-epa-frsAgency.Defense](../classes/Fio-epa-frsAgency.Defense.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[Fio-epa-frsAgency.Agriculture](../classes/Fio-epa-frsAgency.Agriculture.md)&nbsp;or&nbsp;<br />[Fio-epa-frsAgency.VeteransAffairs](../classes/Fio-epa-frsAgency.VeteransAffairs.md)&nbsp;or&nbsp;<br />[Fio-epa-frsAgency.HomelandSecurity](../classes/Fio-epa-frsAgency.HomelandSecurity.md)







## LinkML Source

<details>

```yaml
name: fio_ownedBy
from_schema: okns:fio-kg
exact_mappings:
- http://w3id.org/fio/v1/fio#ownedBy
rank: 1000
slot_uri: fio:ownedBy
alias: fio_ownedBy
domain_of:
- fio-epa-frs_EPA-PFAS-Facility
- fio-epa-frs_FRS-Facility
range: Any
any_of:
- range: fio-epa-frs_Agency
- range: fio-epa-frs_Agency.Commerce
- range: fio-epa-frs_Agency.Interior
- range: fio-epa-frs_Agency.Justice
- range: fio-epa-frs_Agency.Transportation
- range: fio-epa-frs_Agency.HealthandHumanServices
- range: fio-epa-frs_Agency.Energy
- range: fio-epa-frs_Agency.Defense
- range: owl_NamedIndividual
- range: fio-epa-frs_Agency.Agriculture
- range: fio-epa-frs_Agency.VeteransAffairs
- range: fio-epa-frs_Agency.HomelandSecurity

```
</details>