

# Slot: Source (dct_source)


_This property is intended to be used with non-literal values. The described resource may be derived from the related resource in whole or in part. Best practice is to identify the related resource by means of a URI or a string conforming to a formal identification system._






This slot occurs 4749751 times.


URI: [dct:source](http://purl.org/dc/terms/source)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsW3id.orgBiolinkVocabEnvironmentalFeature](../classes/HttpsW3id.orgBiolinkVocabEnvironmentalFeature.md) |  |  no  |
| [HttpsW3id.orgBiolinkVocabDisease](../classes/HttpsW3id.orgBiolinkVocabDisease.md) |  |  no  |
| [HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH](../classes/HttpsPurl.orgOknFrinkKgSpokeSchemaSDoH.md) |  |  no  |
| [HttpsW3id.orgBiolinkVocabChemicalEntity](../classes/HttpsW3id.orgBiolinkVocabChemicalEntity.md) |  |  no  |
| [HttpsW3id.orgBiolinkVocabOrganismTaxon](../classes/HttpsW3id.orgBiolinkVocabOrganismTaxon.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)





## Comments

* description: A related resource from which the described resource is derived.



## LinkML Source

<details>

```yaml
name: dct_source
description: This property is intended to be used with non-literal values. The described
  resource may be derived from the related resource in whole or in part. Best practice
  is to identify the related resource by means of a URI or a string conforming to
  a formal identification system.
title: Source
notes:
- No occurrences of this slot in the graph.
comments:
- 'description: A related resource from which the described resource is derived.'
from_schema: okns:dc
source: http://purl.org/dc/terms/
slot_uri: dct:source
domain_of:
- https___purl.org_okn_frink_kg_spoke_schema_SDoH
- https___w3id.org_biolink_vocab_ChemicalEntity
- https___w3id.org_biolink_vocab_Disease
- https___w3id.org_biolink_vocab_EnvironmentalFeature
- https___w3id.org_biolink_vocab_OrganismTaxon
subproperty_of: dct_relation
range: Any

```
</details>