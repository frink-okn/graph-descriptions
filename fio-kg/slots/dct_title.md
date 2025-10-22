

# Slot: Title (dct_title)


_A name given to the resource._






This slot occurs 529535 times.


URI: [dct:title](http://purl.org/dc/terms/title)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md) | Facility identified as potentially handling PFAS in EPA PFAS Analytic tools b... |  no  |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |
| [VaemGraphMetaData](../classes/VaemGraphMetaData.md) | "vaem:GraphMetaData" defines basic metadata for the registration and publishi... |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[RdfsLiteral](../classes/RdfsLiteral.md)







## LinkML Source

<details>

```yaml
name: dct_title
description: A name given to the resource.
title: Title
from_schema: okns:dc
source: http://purl.org/dc/terms/
slot_uri: dct:title
domain_of:
- vaem_GraphMetaData
- fio-epa-frs_EPA-PFAS-Facility
- fio-epa-frs_FRS-Facility
subproperty_of: dc_title
range: Any
any_of:
- range: string
- range: rdfs_Literal

```
</details>