

# Slot: Description (dct_description)


_Description may include but is not limited to: an abstract, a table of contents, a graphical representation, or a free-text account of the resource._






This slot occurs 13188 times.


URI: [dct:description](http://purl.org/dc/terms/description)



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

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)





## Comments

* description: An account of the resource.



## LinkML Source

<details>

```yaml
name: dct_description
description: 'Description may include but is not limited to: an abstract, a table
  of contents, a graphical representation, or a free-text account of the resource.'
title: Description
comments:
- 'description: An account of the resource.'
from_schema: okns:dc
source: http://purl.org/dc/terms/
slot_uri: dct:description
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
subproperty_of: dc_description
range: string

```
</details>