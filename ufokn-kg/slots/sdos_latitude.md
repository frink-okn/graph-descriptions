

# Slot: latitude (sdos_latitude)


_The latitude of a location. For example ```37.42242``` ([WGS 84](https://en.wikipedia.org/wiki/World_Geodetic_System))._






This slot occurs 5927018 times.


URI: [sdos:latitude](https://schema.org/latitude)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosNumber](../classes/SdosNumber.md)&nbsp;or&nbsp;<br />[SdosText](../classes/SdosText.md)







## LinkML Source

<details>

```yaml
name: sdos_latitude
description: The latitude of a location. For example ```37.42242``` ([WGS 84](https://en.wikipedia.org/wiki/World_Geodetic_System)).
title: latitude
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
slot_uri: sdos:latitude
union_of:
- sdos_Place
- sdos_GeoCoordinates
range: Any
any_of:
- range: sdos_Number
- range: sdos_Text

```
</details>