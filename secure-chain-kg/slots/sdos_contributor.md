

# Slot: contributor (sdos_contributor)


_A secondary contributor to the CreativeWork or Event._






This slot occurs 32408 times.


URI: [sdos:contributor](https://schema.org/contributor)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SdosMusicAlbumReleaseType](../classes/SdosMusicAlbumReleaseType.md) | The kind of release which this album is: single, EP or album |  no  |
| [SdosDayOfWeek](../classes/SdosDayOfWeek.md) | The day of the week, e |  no  |
| [SdosLegalValueLevel](../classes/SdosLegalValueLevel.md) | A list of possible levels for the legal validity of a legislation |  no  |
| [SdosLegalForceStatus](../classes/SdosLegalForceStatus.md) | A list of possible statuses for the legal force of a legislation |  no  |
| [SdosMusicReleaseFormatType](../classes/SdosMusicReleaseFormatType.md) | Format of this release (the type of recording media used, i |  no  |
| [SdosDeliveryMethod](../classes/SdosDeliveryMethod.md) | A delivery method is a standardized procedure for transferring the product or... |  no  |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) |  |  no  |
| [SdosMusicAlbumProductionType](../classes/SdosMusicAlbumProductionType.md) | Classification of the album by its type of content: soundtrack, live album, s... |  no  |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |  |  no  |
| [SdosDriveWheelConfigurationValue](../classes/SdosDriveWheelConfigurationValue.md) | A value indicating which roadwheels will receive torque |  no  |
| [SdosCarUsageType](../classes/SdosCarUsageType.md) | A value indicating a special usage of a car, e |  no  |
| [SdosSteeringPositionValue](../classes/SdosSteeringPositionValue.md) | A value indicating a steering position |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdosOrganization](../classes/SdosOrganization.md)&nbsp;or&nbsp;<br />[SdosPerson](../classes/SdosPerson.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)







## LinkML Source

<details>

```yaml
name: sdos_contributor
description: A secondary contributor to the CreativeWork or Event.
title: contributor
from_schema: okns:sdo
slot_uri: sdos:contributor
domain_of:
- sdos_CarUsageType
- sdos_DayOfWeek
- sdos_DeliveryMethod
- sdos_DriveWheelConfigurationValue
- sdos_LegalForceStatus
- sdos_LegalValueLevel
- sdos_MusicAlbumProductionType
- sdos_MusicAlbumReleaseType
- sdos_MusicReleaseFormatType
- sdos_SteeringPositionValue
- securechain_Software
union_of:
- sdos_CreativeWork
- sdos_Event
range: Any
any_of:
- range: sdos_Organization
- range: sdos_Person
- range: uri

```
</details>