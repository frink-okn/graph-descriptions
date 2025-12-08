

# Slot: sameAs (sdos_sameAs)


_URL of a reference Web page that unambiguously indicates the item's identity. E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website._






This slot occurs 19502 times.


URI: [sdos:sameAs](https://schema.org/sameAs)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdosDayOfWeek](../classes/SdosDayOfWeek.md) | The day of the week, e |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosURL](../classes/SdosURL.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)







## LinkML Source

<details>

```yaml
name: sdos_sameAs
description: URL of a reference Web page that unambiguously indicates the item's identity.
  E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website.
title: sameAs
from_schema: okns:sdo
domain: sdos_Thing
slot_uri: sdos:sameAs
domain_of:
- sdos_DayOfWeek
range: Any
any_of:
- range: sdos_URL
- range: uri

```
</details>