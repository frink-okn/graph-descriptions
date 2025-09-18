

# Slot: Date Created (dct_created)


_Recommended practice is to describe the date, date/time, or period of time as recommended for the property Date, of which this is a subproperty._






This slot occurs 529535 times.


URI: [dct:created](http://purl.org/dc/terms/created)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |
| [VaemGraphMetaData](../classes/VaemGraphMetaData.md) | "vaem:GraphMetaData" defines basic metadata for the registration and publishi... |  no  |
| [Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md) | Facility identified as potentially handling PFAS in EPA PFAS Analytic tools b... |  no  |







## Properties

* Range: [RdfsLiteral](../classes/RdfsLiteral.md)





## Comments

* description: Date of creation of the resource.



## LinkML Source

<details>

```yaml
name: dct_created
description: Recommended practice is to describe the date, date/time, or period of
  time as recommended for the property Date, of which this is a subproperty.
title: Date Created
notes:
- No occurrences of this slot in the graph.
comments:
- 'description: Date of creation of the resource.'
from_schema: okns:dc
source: http://purl.org/dc/terms/
slot_uri: dct:created
domain_of:
- vaem_GraphMetaData
- fio-epa-frs_EPA-PFAS-Facility
- fio-epa-frs_FRS-Facility
subproperty_of: dct_date
range: rdfs_Literal

```
</details>