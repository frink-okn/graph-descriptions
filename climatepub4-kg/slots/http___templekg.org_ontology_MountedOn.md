

# Slot: http___templekg.org_ontology_MountedOn




This slot occurs 73 times.


URI: [http://templekg.org/ontology/MountedOn](http://templekg.org/ontology/MountedOn)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md) |  |  no  |
| [HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md) |  |  no  |
| [HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md) |  |  no  |
| [HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md)&nbsp;or&nbsp;<br />[SdosProject](../classes/SdosProject.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md)







## LinkML Source

<details>

```yaml
name: http___templekg.org_ontology_MountedOn
from_schema: okns:climatepub4-kg
rank: 1000
slot_uri: http://templekg.org/ontology/MountedOn
alias: http___templekg.org_ontology_MountedOn
domain_of:
- http___templekg.org_ontology_Instrument
- http___templekg.org_ontology_Model
- http___templekg.org_ontology_Others
- http___templekg.org_ontology_Platform
range: Any
any_of:
- range: http___templekg.org_ontology_Platform
- range: http___templekg.org_ontology_Model
- range: http___templekg.org_ontology_Others
- range: http___templekg.org_ontology_Provider
- range: sdos_Project
- range: http___templekg.org_ontology_Location
- range: http___templekg.org_ontology_Instrument

```
</details>