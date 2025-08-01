

# Slot: has FRS Id (fio-epa-frs_hasFRSId)


_has Identifier in EPA Facility Registry Service_






This slot occurs 529535 times.


URI: [fio-epa-frs:hasFRSId](http://w3id.org/fio/v1/epa-frs#hasFRSId)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |
| [Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md) | Facility identified as potentially handling PFAS in EPA PFAS Analytic tools b... |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)







## LinkML Source

<details>

```yaml
name: fio-epa-frs_hasFRSId
description: has Identifier in EPA Facility Registry Service
title: has FRS Id
from_schema: okns:fiokg
exact_mappings:
- http://w3id.org/fio/v1/epa-frs#hasFRSId
rank: 1000
slot_uri: fio-epa-frs:hasFRSId
alias: fio_epa_frs_hasFRSId
domain_of:
- fio-epa-frs_EPA-PFAS-Facility
- fio-epa-frs_FRS-Facility
subproperty_of: dct_identifier
union_of:
- owl_Thing
- __node359
- fio-epa-frs_FRS-Facility
- fio_Facility
range: Any
any_of:
- range: rdfs_Literal
- range: string

```
</details>