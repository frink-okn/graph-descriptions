

# Slot: http___templekg.org_ontology_WikiDepicts




This slot occurs 12 times.


URI: [http://templekg.org/ontology/WikiDepicts](http://templekg.org/ontology/WikiDepicts)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md) |  |  no  |
| [HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md) |  |  no  |
| [HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md) |  |  no  |
| [HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md)&nbsp;or&nbsp;<br />[SdosProject](../classes/SdosProject.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md)







## LinkML Source

<details>

```yaml
name: http___templekg.org_ontology_WikiDepicts
from_schema: okns:climatepub4-kg
rank: 1000
slot_uri: http://templekg.org/ontology/WikiDepicts
alias: http___templekg.org_ontology_WikiDepicts
domain_of:
- http___templekg.org_ontology_Instrument
- http___templekg.org_ontology_Location
- http___templekg.org_ontology_Others
- http___templekg.org_ontology_Platform
range: Any
any_of:
- range: http___templekg.org_ontology_Platform
- range: sdos_Project
- range: http___templekg.org_ontology_Instrument
- range: http___templekg.org_ontology_Others

```
</details>