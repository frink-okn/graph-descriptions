

# Slot: elevation (sdos_elevation)


_The elevation of a location ([WGS 84](https://en.wikipedia.org/wiki/World_Geodetic_System)). Values may be of the form 'NUMBER UNIT\_OF\_MEASUREMENT' (e.g., '1,000 m', '3,200 ft') while numbers alone should be assumed to be a value in meters._






This slot occurs 5858958 times.


URI: [sdos:elevation](https://schema.org/elevation)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosNumber](../classes/SdosNumber.md)&nbsp;or&nbsp;<br />[SdosText](../classes/SdosText.md)







## LinkML Source

<details>

```yaml
name: sdos_elevation
description: The elevation of a location ([WGS 84](https://en.wikipedia.org/wiki/World_Geodetic_System)).
  Values may be of the form 'NUMBER UNIT\_OF\_MEASUREMENT' (e.g., '1,000 m', '3,200
  ft') while numbers alone should be assumed to be a value in meters.
title: elevation
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
slot_uri: sdos:elevation
union_of:
- sdos_GeoShape
- sdos_GeoCoordinates
range: Any
any_of:
- range: sdos_Number
- range: sdos_Text

```
</details>