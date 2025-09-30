

# Slot: longitude (sdos_longitude)


_The longitude of a location. For example ```-122.08585``` ([WGS 84](https://en.wikipedia.org/wiki/World_Geodetic_System))._






This slot occurs 5927018 times.


URI: [sdos:longitude](https://schema.org/longitude)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosNumber](../classes/SdosNumber.md)&nbsp;or&nbsp;<br />[SdosText](../classes/SdosText.md)







## LinkML Source

<details>

```yaml
name: sdos_longitude
description: The longitude of a location. For example ```-122.08585``` ([WGS 84](https://en.wikipedia.org/wiki/World_Geodetic_System)).
title: longitude
notes:
- No occurrences of this slot in the graph.
from_schema: okns:sdo
slot_uri: sdos:longitude
union_of:
- sdos_Place
- sdos_GeoCoordinates
range: Any
any_of:
- range: sdos_Number
- range: sdos_Text

```
</details>