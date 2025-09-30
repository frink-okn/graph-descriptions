

# Slot: propertyID (sdos_propertyID)


_A commonly used identifier for the characteristic represented by the property, e.g. a manufacturer or a standard code for a property. propertyID can be␊(1) a prefixed string, mainly meant to be used with standards for product properties; (2) a site-specific, non-prefixed string (e.g. the primary key of the property or the vendor-specific ID of the property), or (3)␊a URL indicating the type of the property, either pointing to an external vocabulary, or a Web resource that describes the property (e.g. a glossary entry).␊Standards bodies should promote a standard prefix for the identifiers of properties from their standards._






This slot occurs 5927018 times.


URI: [sdos:propertyID](https://schema.org/propertyID)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosURL](../classes/SdosURL.md)&nbsp;or&nbsp;<br />[SdosText](../classes/SdosText.md)







## LinkML Source

<details>

```yaml
name: sdos_propertyID
description: A commonly used identifier for the characteristic represented by the
  property, e.g. a manufacturer or a standard code for a property. propertyID can
  be␊(1) a prefixed string, mainly meant to be used with standards for product properties;
  (2) a site-specific, non-prefixed string (e.g. the primary key of the property or
  the vendor-specific ID of the property), or (3)␊a URL indicating the type of the
  property, either pointing to an external vocabulary, or a Web resource that describes
  the property (e.g. a glossary entry).␊Standards bodies should promote a standard
  prefix for the identifiers of properties from their standards.
title: propertyID
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
domain: sdos_PropertyValue
slot_uri: sdos:propertyID
range: Any
any_of:
- range: sdos_URL
- range: sdos_Text

```
</details>