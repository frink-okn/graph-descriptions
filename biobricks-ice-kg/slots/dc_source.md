

# Slot: dc_source


_No slot description provided_





URI: [dc:source](http://purl.org/dc/elements/1.1/source)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Cheminf000446](../classes/Cheminf000446.md) | No type description provided |  no  |
| [Bao0000015](../classes/Bao0000015.md) | No type description provided |  no  |
| [Cheminf000568](../classes/Cheminf000568.md) | No type description provided |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Value |
| --- |
| http://identifiers.org/cas/10-00-4 dc:source CAS |
| https://comptox.epa.gov/dashboard/chemical/details/DTXSID001002091 dc:source CompTox |
| https://comptox.epa.gov/dashboard/assay-endpoints/ACEA_AR_agonist_80hr dc:source ICE |

## Comments

* 538147 occurrences with subject type cheminf_000446 and object type string.
* 538131 occurrences with subject type cheminf_000568 and object type string.
* 3990 occurrences with subject type bao_0000015 and object type string.

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
| self | dc:source |
| native | biobricks-ice-kg/:dc_source |




## LinkML Source

<details>
```yaml
name: dc_source
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 538147 occurrences with subject type cheminf_000446 and object type string.
- 538131 occurrences with subject type cheminf_000568 and object type string.
- 3990 occurrences with subject type bao_0000015 and object type string.
examples:
- value: http://identifiers.org/cas/10-00-4 dc:source CAS
- value: https://comptox.epa.gov/dashboard/chemical/details/DTXSID001002091 dc:source
    CompTox
- value: https://comptox.epa.gov/dashboard/assay-endpoints/ACEA_AR_agonist_80hr dc:source
    ICE
from_schema: biobricks-ice-kg
rank: 1000
slot_uri: dc:source
alias: dc_source
domain_of:
- bao_0000015
- cheminf_000446
- cheminf_000568
range: string

```
</details>