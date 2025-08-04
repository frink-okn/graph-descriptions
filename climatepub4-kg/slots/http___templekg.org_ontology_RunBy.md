

# Slot: http___templekg.org_ontology_RunBy




This slot occurs 269 times.


URI: [http://templekg.org/ontology/RunBy](http://templekg.org/ontology/RunBy)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md) |  |  no  |
| [HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md) |  |  no  |
| [HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md) |  |  no  |
| [HttpTemplekg.orgOntologyExperiment](../classes/HttpTemplekg.orgOntologyExperiment.md) |  |  no  |
| [HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md) |  |  no  |
| [HttpTemplekg.orgOntologyOceanCirculation](../classes/HttpTemplekg.orgOntologyOceanCirculation.md) |  |  no  |
| [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyTeleconnection](../classes/HttpTemplekg.orgOntologyTeleconnection.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyExperiment](../classes/HttpTemplekg.orgOntologyExperiment.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOceanCirculation](../classes/HttpTemplekg.orgOntologyOceanCirculation.md)&nbsp;or&nbsp;<br />[SdosProject](../classes/SdosProject.md)







## LinkML Source

<details>

```yaml
name: http___templekg.org_ontology_RunBy
from_schema: okns:climatepub4-kg
rank: 1000
slot_uri: http://templekg.org/ontology/RunBy
alias: http___templekg.org_ontology_RunBy
domain_of:
- http___templekg.org_ontology_Experiment
- http___templekg.org_ontology_Model
- http___templekg.org_ontology_OceanCirculation
- http___templekg.org_ontology_Others
- http___templekg.org_ontology_Platform
- http___templekg.org_ontology_Provider
- http___templekg.org_ontology_WeatherEvent
range: Any
any_of:
- range: http___templekg.org_ontology_Platform
- range: http___templekg.org_ontology_Teleconnection
- range: http___templekg.org_ontology_Model
- range: http___templekg.org_ontology_Others
- range: http___templekg.org_ontology_Provider
- range: http___templekg.org_ontology_Experiment
- range: http___templekg.org_ontology_Location
- range: http___templekg.org_ontology_OceanCirculation
- range: sdos_Project

```
</details>