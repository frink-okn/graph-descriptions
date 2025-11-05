

# Slot: Date Modified (dct_modified)


_Recommended practice is to describe the date, date/time, or period of time as recommended for the property Date, of which this is a subproperty._






This slot occurs 3211 times.


URI: [dct:modified](http://purl.org/dc/terms/modified)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpAopkb.orgAopOntology#AdverseOutcomePathway](../classes/HttpAopkb.orgAopOntology#AdverseOutcomePathway.md) |  |  no  |
| [HttpAopkb.orgAopOntology#KeyEventRelationship](../classes/HttpAopkb.orgAopOntology#KeyEventRelationship.md) |  |  no  |
| [HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571](../classes/HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:date](xsd:date)&nbsp;or&nbsp;<br />[RdfsLiteral](../classes/RdfsLiteral.md)





## Comments

* description: Date on which the resource was changed.



## LinkML Source

<details>

```yaml
name: dct_modified
description: Recommended practice is to describe the date, date/time, or period of
  time as recommended for the property Date, of which this is a subproperty.
title: Date Modified
comments:
- 'description: Date on which the resource was changed.'
from_schema: okns:dc
source: http://purl.org/dc/terms/
slot_uri: dct:modified
domain_of:
- http___aopkb.org_aop_ontology#AdverseOutcomePathway
- http___aopkb.org_aop_ontology#KeyEventRelationship
- http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
subproperty_of: dct_date
range: Any
any_of:
- range: date
- range: rdfs_Literal

```
</details>