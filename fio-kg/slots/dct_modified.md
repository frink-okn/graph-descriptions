

# Slot: Date Modified (dct_modified)


_Recommended practice is to describe the date, date/time, or period of time as recommended for the property Date, of which this is a subproperty._






This slot occurs 519895 times.


URI: [dct:modified](http://purl.org/dc/terms/modified)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [VaemGraphMetaData](../classes/VaemGraphMetaData.md) | "vaem:GraphMetaData" defines basic metadata for the registration and publishi... |  no  |
| [Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md) | Facility identified as potentially handling PFAS in EPA PFAS Analytic tools b... |  no  |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:date](http://www.w3.org/2001/XMLSchema#date)&nbsp;or&nbsp;<br />[RdfsLiteral](../classes/RdfsLiteral.md)





## Comments

* description: Date on which the resource was changed.



## LinkML Source

<details>

```yaml
name: dct_modified
description: Recommended practice is to describe the date, date/time, or period of
  time as recommended for the property Date, of which this is a subproperty.
title: Date Modified
comments:
- 'description: Date on which the resource was changed.'
from_schema: okns:dc
source: http://purl.org/dc/terms/
slot_uri: dct:modified
domain_of:
- vaem_GraphMetaData
- fio-epa-frs_EPA-PFAS-Facility
- fio-epa-frs_FRS-Facility
subproperty_of: dct_date
range: Any
any_of:
- range: date
- range: rdfs_Literal

```
</details>