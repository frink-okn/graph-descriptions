

# Slot: http___templekg.org_ontology_WikiOppositeOf




This slot occurs 45 times.


URI: [http://templekg.org/ontology/WikiOppositeOf](http://templekg.org/ontology/WikiOppositeOf)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md) |  |  no  |
| [HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md) |  |  no  |
| [HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md) |  |  no  |
| [HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyVariable](../classes/HttpTemplekg.orgOntologyVariable.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyOthers](../classes/HttpTemplekg.orgOntologyOthers.md)&nbsp;or&nbsp;<br />[SdosProject](../classes/SdosProject.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyLocation](../classes/HttpTemplekg.orgOntologyLocation.md)&nbsp;or&nbsp;<br />[HttpTemplekg.orgOntologyInstrument](../classes/HttpTemplekg.orgOntologyInstrument.md)







## LinkML Source

<details>

```yaml
name: http___templekg.org_ontology_WikiOppositeOf
from_schema: okns:climatepub4-kg
rank: 1000
slot_uri: http://templekg.org/ontology/WikiOppositeOf
alias: http___templekg.org_ontology_WikiOppositeOf
domain_of:
- http___templekg.org_ontology_Instrument
- http___templekg.org_ontology_Location
- http___templekg.org_ontology_Others
- http___templekg.org_ontology_Variable
range: Any
any_of:
- range: http___templekg.org_ontology_Variable
- range: http___templekg.org_ontology_Others
- range: sdos_Project
- range: http___templekg.org_ontology_Location
- range: http___templekg.org_ontology_Instrument

```
</details>