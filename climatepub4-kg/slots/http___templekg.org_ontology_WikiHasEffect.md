

# Slot: http___templekg.org_ontology_WikiHasEffect




This slot occurs 46 times.


URI: [http://templekg.org/ontology/WikiHasEffect](http://templekg.org/ontology/WikiHasEffect)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md) |  |  no  |
| [HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md) |  |  no  |
| [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |  |  no  |
| [HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md) |  |  no  |
| [HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md) |  |  no  |
| [HttpTemplekg.orgOntologyNaturalHazard](../classes/HttpTemplekg.orgOntologyNaturalHazard.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyNaturalHazard](../classes/HttpTemplekg.orgOntologyNaturalHazard.md)&nbsp;or&nbsp;<br />[SdosProject](../classes/SdosProject.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md)







## LinkML Source

<details>

```yaml
name: http___templekg.org_ontology_WikiHasEffect
from_schema: okns:climatepub4-kg
rank: 1000
slot_uri: http://templekg.org/ontology/WikiHasEffect
alias: http___templekg.org_ontology_WikiHasEffect
domain_of:
- http___templekg.org_ontology_Instrument
- http___templekg.org_ontology_Model
- http___templekg.org_ontology_NaturalHazard
- http___templekg.org_ontology_Others
- http___templekg.org_ontology_Platform
- http___templekg.org_ontology_WeatherEvent
range: Any
any_of:
- range: http___templekg.org_ontology_NaturalHazard
- range: sdos_Project
- range: http___templekg.org_ontology_Instrument
- range: http___templekg.org_ontology_Others

```
</details>