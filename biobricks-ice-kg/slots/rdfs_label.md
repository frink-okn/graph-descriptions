

# Slot: rdfs_label


_No slot description provided_





URI: [rdfs:label](http://www.w3.org/2000/01/rdf-schema#label)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Cheminf000000](../classes/Cheminf000000.md) | No type description provided |  no  |
| [Bao0000015](../classes/Bao0000015.md) | No type description provided |  no  |
| [Cheminf000568](../classes/Cheminf000568.md) | No type description provided |  no  |
| [Cheminf000446](../classes/Cheminf000446.md) | No type description provided |  no  |
| [Bao0000179](../classes/Bao0000179.md) | No type description provided |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Value |
| --- |
| http://example.com/ice/ADME_Parameters_Data.parquet/dtxsid/DTXSID001009966/Chemical_Entity rdfs:label Tegafur |
| http://example.com/ice/ADME_Parameters_Data.parquet/record_id/httk2.2.2_DTXSID001009966/dtxsid/DTXSID001009966/endpoint/Fu/Endpoint rdfs:label Fu |
| http://identifiers.org/cas/10-00-4 rdfs:label Uliginosin B |
| https://comptox.epa.gov/dashboard/chemical/details/DTXSID001002091 rdfs:label N-[3-(Dimethylamino)propyl]octadeca-9,12-dienimidic acid |
| http://example.com/ice/ADME_Parameters_Data.parquet/assay/httk%2C%20Human%20Hepatic%20Intrinsic%20Clearance/Assay rdfs:label httk, Human Hepatic Intrinsic Clearance |

## Comments

* 197214 occurrences with subject type cheminf_000000 and object type string.
* 413168 occurrences with subject type bao_0000179 and object type string.
* 542470 occurrences with subject type cheminf_000446 and object type string.
* 542456 occurrences with subject type cheminf_000568 and object type string.
* 2063 occurrences with subject type bao_0000015 and object type string.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: biobricks-ice-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rdfs:label |
| native | biobricks-ice-kg/:rdfs_label |




## LinkML Source

<details>
```yaml
name: rdfs_label
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 197214 occurrences with subject type cheminf_000000 and object type string.
- 413168 occurrences with subject type bao_0000179 and object type string.
- 542470 occurrences with subject type cheminf_000446 and object type string.
- 542456 occurrences with subject type cheminf_000568 and object type string.
- 2063 occurrences with subject type bao_0000015 and object type string.
examples:
- value: http://example.com/ice/ADME_Parameters_Data.parquet/dtxsid/DTXSID001009966/Chemical_Entity
    rdfs:label Tegafur
- value: http://example.com/ice/ADME_Parameters_Data.parquet/record_id/httk2.2.2_DTXSID001009966/dtxsid/DTXSID001009966/endpoint/Fu/Endpoint
    rdfs:label Fu
- value: http://identifiers.org/cas/10-00-4 rdfs:label Uliginosin B
- value: https://comptox.epa.gov/dashboard/chemical/details/DTXSID001002091 rdfs:label
    N-[3-(Dimethylamino)propyl]octadeca-9,12-dienimidic acid
- value: http://example.com/ice/ADME_Parameters_Data.parquet/assay/httk%2C%20Human%20Hepatic%20Intrinsic%20Clearance/Assay
    rdfs:label httk, Human Hepatic Intrinsic Clearance
from_schema: biobricks-ice-kg
rank: 1000
slot_uri: rdfs:label
alias: rdfs_label
domain_of:
- bao_0000015
- bao_0000179
- cheminf_000000
- cheminf_000446
- cheminf_000568
range: string

```
</details>