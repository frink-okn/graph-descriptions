

# Slot: atLocation (prov_atLocation)


_The Location of any resource._






This slot occurs 1881 times.


URI: [prov:atLocation](http://www.w3.org/ns/prov#atLocation)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md) |  |  no  |
| [HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md) |  |  no  |
| [HttpTemplekg.orgOntologyWeatherEvent](../classes/HttpTemplekg.orgOntologyWeatherEvent.md) |  |  no  |
| [HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md) |  |  no  |
| [HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md) |  |  no  |
| [HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md) |  |  no  |
| [HttpTemplekg.orgOntologyTeleconnection](../classes/HttpTemplekg.orgOntologyTeleconnection.md) |  |  no  |
| [HttpTemplekg.orgOntologyExperiment](../classes/HttpTemplekg.orgOntologyExperiment.md) |  |  no  |
| [HttpTemplekg.orgOntologyModel](../classes/HttpTemplekg.orgOntologyModel.md) |  |  no  |
| [HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md) |  |  no  |
| [HttpTemplekg.orgOntologyOceanCirculation](../classes/HttpTemplekg.orgOntologyOceanCirculation.md) |  |  no  |
| [HttpTemplekg.orgOntologyNaturalHazard](../classes/HttpTemplekg.orgOntologyNaturalHazard.md) |  |  no  |







## Properties

* Range: [ProvLocation](../classes/ProvLocation.md)





## Comments

* description: This property has multiple RDFS domains to suit multiple OWL Profiles. See <a href="#owl-profile">PROV-O OWL Profile</a>.
* No occurrences of this slot in the graph.



## LinkML Source

<details>

```yaml
name: prov_atLocation
description: The Location of any resource.
title: atLocation
comments:
- 'description: This property has multiple RDFS domains to suit multiple OWL Profiles.
  See <a href="#owl-profile">PROV-O OWL Profile</a>.'
- No occurrences of this slot in the graph.
from_schema: okns:prov
source: http://www.w3.org/ns/prov-o#
slot_uri: prov:atLocation
domain_of:
- http___templekg.org_ontology_Experiment
- http___templekg.org_ontology_Instrument
- http___templekg.org_ontology_Location
- http___templekg.org_ontology_Model
- http___templekg.org_ontology_NaturalHazard
- http___templekg.org_ontology_OceanCirculation
- http___templekg.org_ontology_Others
- http___templekg.org_ontology_Platform
- http___templekg.org_ontology_Provider
- http___templekg.org_ontology_Teleconnection
- http___templekg.org_ontology_Variable
- http___templekg.org_ontology_WeatherEvent
range: prov_Location

```
</details>