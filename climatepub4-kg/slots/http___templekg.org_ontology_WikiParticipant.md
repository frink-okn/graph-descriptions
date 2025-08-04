

# Slot: http___templekg.org_ontology_WikiParticipant




This slot occurs 35 times.


URI: [http://templekg.org/ontology/WikiParticipant](http://templekg.org/ontology/WikiParticipant)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md) |  |  no  |
| [HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md) |  |  no  |
| [HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md) |  |  no  |
| [HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md)&nbsp;or&nbsp;<br />[SdosProject](../classes/SdosProject.md)







## LinkML Source

<details>

```yaml
name: http___templekg.org_ontology_WikiParticipant
from_schema: okns:climatepub4-kg
rank: 1000
slot_uri: http://templekg.org/ontology/WikiParticipant
alias: http___templekg.org_ontology_WikiParticipant
domain_of:
- http___templekg.org_ontology_Instrument
- http___templekg.org_ontology_Location
- http___templekg.org_ontology_Others
- http___templekg.org_ontology_Provider
range: Any
any_of:
- range: http___templekg.org_ontology_Provider
- range: http___templekg.org_ontology_Location
- range: sdos_Project

```
</details>