

# Slot: http___templekg.org_ontology_WikiFollowedBy




This slot occurs 253 times.


URI: [http://templekg.org/ontology/WikiFollowedBy](http://templekg.org/ontology/WikiFollowedBy)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md) |  |  no  |
| [HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md) |  |  no  |
| [HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md) |  |  no  |
| [HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md) |  |  no  |
| [HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md) |  |  no  |
| [HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyPlatform](../classes/HttpTemplekg.orgOntologyPlatform.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyProvider](../classes/HttpTemplekg.orgOntologyProvider.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md)&nbsp;or&nbsp;<br />[SdosProject](../classes/SdosProject.md)







## LinkML Source

<details>

```yaml
name: http___templekg.org_ontology_WikiFollowedBy
from_schema: okns:climatepub4-kg
rank: 1000
slot_uri: http://templekg.org/ontology/WikiFollowedBy
alias: http___templekg.org_ontology_WikiFollowedBy
domain_of:
- http___templekg.org_ontology_Instrument
- http___templekg.org_ontology_Location
- http___templekg.org_ontology_Others
- http___templekg.org_ontology_Platform
- http___templekg.org_ontology_Provider
- http___templekg.org_ontology_Variable
range: Any
any_of:
- range: http___templekg.org_ontology_Platform
- range: http___templekg.org_ontology_Variable
- range: http___templekg.org_ontology_Others
- range: http___templekg.org_ontology_Provider
- range: http___templekg.org_ontology_Location
- range: http___templekg.org_ontology_Instrument
- range: sdos_Project

```
</details>