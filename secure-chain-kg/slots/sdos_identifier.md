

# Slot: identifier (sdos_identifier)


_The identifier property represents any kind of identifier for any kind of [[Thing]], such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links. See [background notes](/docs/datamodel.html#identifierBg) for more details._






This slot occurs 313126 times.


URI: [sdos:identifier](https://schema.org/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SecurechainVulnerabilityType](../classes/SecurechainVulnerabilityType.md) |  |  no  |
| [SecurechainVulnerability](../classes/SecurechainVulnerability.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosURL](../classes/SdosURL.md)&nbsp;or&nbsp;<br />[SdosPropertyValue](../classes/SdosPropertyValue.md)&nbsp;or&nbsp;<br />[SdosText](../classes/SdosText.md)







## LinkML Source

<details>

```yaml
name: sdos_identifier
description: The identifier property represents any kind of identifier for any kind
  of [[Thing]], such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated
  properties for representing many of these, either as textual strings or as URL (URI)
  links. See [background notes](/docs/datamodel.html#identifierBg) for more details.
title: identifier
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
exact_mappings:
- http://purl.org/dc/terms/identifier
domain: sdos_Thing
slot_uri: sdos:identifier
domain_of:
- securechain_Vulnerability
- securechain_VulnerabilityType
range: Any
any_of:
- range: sdos_URL
- range: sdos_PropertyValue
- range: sdos_Text

```
</details>