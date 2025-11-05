

# Slot: additionalType (sdos_additionalType)


_An additional type for the item, typically used for adding more specific types from external vocabularies in microdata syntax. This is a relationship between something and a class that the thing is in. Typically the value is a URI-identified RDF class, and in this case corresponds to the␊    use of rdf:type in RDF. Text values can be used sparingly, for cases where useful information can be added without their being an appropriate schema to reference. In the case of text values, the class label should follow the schema.org <a href="https://schema.org/docs/styleguide.html">style guide</a>._






This slot occurs 17557248 times.


URI: [sdos:additionalType](https://schema.org/additionalType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Kwgos#S2Cell](../classes/Kwgos#S2Cell.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosURL](../classes/SdosURL.md)&nbsp;or&nbsp;<br />[SdosText](../classes/SdosText.md)







## LinkML Source

<details>

```yaml
name: sdos_additionalType
description: An additional type for the item, typically used for adding more specific
  types from external vocabularies in microdata syntax. This is a relationship between
  something and a class that the thing is in. Typically the value is a URI-identified
  RDF class, and in this case corresponds to the␊    use of rdf:type in RDF. Text
  values can be used sparingly, for cases where useful information can be added without
  their being an appropriate schema to reference. In the case of text values, the
  class label should follow the schema.org <a href="https://schema.org/docs/styleguide.html">style
  guide</a>.
title: additionalType
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
domain: sdos_Thing
slot_uri: sdos:additionalType
domain_of:
- kwgos_#S2Cell
subproperty_of: rdf_type
range: Any
any_of:
- range: sdos_URL
- range: sdos_Text

```
</details>