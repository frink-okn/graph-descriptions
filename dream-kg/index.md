# dream-kg

TODO -- tell the world what this schema describes.

URI: dream-kg

Name: dream-kg



## Classes

| Class | Description |
| --- | --- |
| [Any](classes/Any.md) | None |
| [SdohAdministrativeArea](classes/SdohAdministrativeArea.md) | A geographical region, typically under the jurisdiction of a particular government. |
| [SdohAudience](classes/SdohAudience.md) | Intended audience for an item, i.e. the group for whom the item was created. |
| [SdohCategoryCode](classes/SdohCategoryCode.md) | A Category Code. |
| [SdohContactPoint](classes/SdohContactPoint.md) | A contact point&#x2014;for example, a Customer Complaints department. |
| [SdohOpeningHoursSpecification](classes/SdohOpeningHoursSpecification.md) | A structured value providing information about the opening hours of a place or a certain service inside a place.\n\n
The place is __open__ if the [[opens]] property is specified, and __closed__ otherwise.\n\nIf the value for the [[closes]] property is less than the value for the [[opens]] property then the hour range is assumed to span over the next day.
       |
| [SdohOrganization](classes/SdohOrganization.md) | An organization such as a school, NGO, corporation, club, etc. |
| [SdohPlace](classes/SdohPlace.md) | Entities that have a somewhat fixed, physical extension. |
| [SdohService](classes/SdohService.md) | A service provided by an organization, e.g. delivery service, print services, etc. |
| [SdohServiceChannel](classes/SdohServiceChannel.md) | A means for accessing a service, e.g. a government office location, web site, or phone number. |
| [SdohTextObject](classes/SdohTextObject.md) | A text file. The text can be unformatted or contain markup, html, etc. |



## Slots

| Slot | Description |
| --- | --- |
| [sdoh_address](slots/sdoh_address.md) | Physical address of the item |
| [sdoh_areaServed](slots/sdoh_areaServed.md) | The geographic area where a service or offered item is provided |
| [sdoh_audienceType](slots/sdoh_audienceType.md) | The target group associated with a given audience (e |
| [sdoh_availableChannel](slots/sdoh_availableChannel.md) | A means of accessing the service (e |
| [sdoh_category](slots/sdoh_category.md) | A category for the item |
| [sdoh_closes](slots/sdoh_closes.md) | The closing hour of the place or service on the given day(s) of the week |
| [sdoh_codeValue](slots/sdoh_codeValue.md) | A short textual code that uniquely identifies the value |
| [sdoh_conditionsOfAccess](slots/sdoh_conditionsOfAccess.md) | Conditions that affect the availability of, or method(s) of access to, an ite... |
| [sdoh_containedInPlace](slots/sdoh_containedInPlace.md) | The basic containment relation between a place and one that contains it |
| [sdoh_dayOfWeek](slots/sdoh_dayOfWeek.md) | The day of the week for which these opening hours are valid |
| [sdoh_description](slots/sdoh_description.md) | A description of the item |
| [sdoh_disambiguatingDescription](slots/sdoh_disambiguatingDescription.md) | A sub property of description |
| [sdoh_hasMap](slots/sdoh_hasMap.md) | A URL to a map of the place |
| [sdoh_hoursAvailable](slots/sdoh_hoursAvailable.md) | The hours during which this service or contact is available |
| [sdoh_identifier](slots/sdoh_identifier.md) | The identifier property represents any kind of identifier for any kind of [[T... |
| [sdoh_inCodeSet](slots/sdoh_inCodeSet.md) | A [[CategoryCodeSet]] that contains this category code |
| [sdoh_latitude](slots/sdoh_latitude.md) | The latitude of a location |
| [sdoh_longitude](slots/sdoh_longitude.md) | The longitude of a location |
| [sdoh_name](slots/sdoh_name.md) | The name of the item |
| [sdoh_opens](slots/sdoh_opens.md) | The opening hour of the place or service on the given day(s) of the week |
| [sdoh_provider](slots/sdoh_provider.md) | The service provider, service operator, or service performer; the goods produ... |
| [sdoh_sameAs](slots/sdoh_sameAs.md) | URL of a reference Web page that unambiguously indicates the item's identity |
| [sdoh_serviceLocation](slots/sdoh_serviceLocation.md) | The location (e |
| [sdoh_servicePhone](slots/sdoh_servicePhone.md) | The phone number to use to access the service |
| [sdoh_serviceUrl](slots/sdoh_serviceUrl.md) | The website to access the service |
| [sdoh_telephone](slots/sdoh_telephone.md) | The telephone number |
| [sdoh_text](slots/sdoh_text.md) | The textual content of this CreativeWork |


## Enumerations

| Enumeration | Description |
| --- | --- |


## Types

| Type | Description |
| --- | --- |


## Subsets

| Subset | Description |
| --- | --- |
