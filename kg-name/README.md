# kg-name

No schema description specified



## Schema Diagram

```mermaid
erDiagram
HsdoAdministrativeArea {
    string hsdo_identifier  
}
HsdoAudience {
    string hsdo_audienceType  
}
HsdoCategoryCode {
    string hsdo_codeValue  
    uri hsdo_inCodeSet  
}
HsdoContactPoint {
    string hsdo_telephone  
}
HsdoOpeningHoursSpecification {
    string hsdo_dayOfWeek  
    string hsdo_closes  
    string hsdo_opens  
}
HsdoOrganization {
    uri hsdo_sameAs  
    string hsdo_name  
}
HsdoPlace {
    uri hsdo_hasMap  
    string hsdo_address  
    decimal hsdo_latitude  
    decimal hsdo_longitude  
}
HsdoService {
    string hsdo_identifier  
    string hsdo_areaServed  
    string hsdo_name  
}
HsdoServiceChannel {
    uri hsdo_serviceUrl  
    string hsdo_disambiguatingDescription  
}
HsdoTextObject {
    string hsdo_conditionsOfAccess  
    string hsdo_text  
}

HsdoPlace ||--|o HsdoAdministrativeArea : "hsdo_containedInPlace"
HsdoService ||--|o HsdoCategoryCode : "hsdo_category"
HsdoService ||--|o HsdoAudience : "hsdo_category"
HsdoService ||--|o HsdoServiceChannel : "hsdo_availableChannel"
HsdoService ||--|o HsdoOpeningHoursSpecification : "hsdo_hoursAvailable"
HsdoService ||--|o HsdoOrganization : "hsdo_provider"
HsdoService ||--|o HsdoTextObject : "hsdo_description"
HsdoServiceChannel ||--|o HsdoContactPoint : "hsdo_servicePhone"
HsdoServiceChannel ||--|o HsdoPlace : "hsdo_serviceLocation"

```


## IRI prefixes

* dreamkg: http://www.semanticweb.org/dreamkg/ijcai/
* hsdo: http://schema.org/
* linkml: https://w3id.org/linkml/
* rdf: http://www.w3.org/1999/02/22-rdf-syntax-ns#



## Classes

| Class | Description |
| --- | --- |
| [HsdoAdministrativeArea](classes/HsdoAdministrativeArea.md) | A geographical region, typically under the jurisdiction of a particular government.<br/>Class with 39 occurrences.| 
| [HsdoAudience](classes/HsdoAudience.md) | Intended audience for an item, i.e. the group for whom the item was created.<br/>Class with 81 occurrences.| 
| [HsdoCategoryCode](classes/HsdoCategoryCode.md) | A Category Code.<br/>Class with 157 occurrences.| 
| [HsdoContactPoint](classes/HsdoContactPoint.md) | A contact point&#x2014;for example, a Customer Complaints department.<br/>Class with 87 occurrences.| 
| [HsdoOpeningHoursSpecification](classes/HsdoOpeningHoursSpecification.md) | A structured value providing information about the opening hours of a place or a certain service inside a place.\n\n␊The place is __open__ if the [[opens]] property is specified, and __closed__ otherwise.\n\nIf the value for the [[closes]] property is less than the value for the [[opens]] property then the hour range is assumed to span over the next day.␊      <br/>Class with 609 occurrences.| 
| [HsdoOrganization](classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc.<br/>Class with 87 occurrences.| 
| [HsdoPlace](classes/HsdoPlace.md) | Entities that have a somewhat fixed, physical extension.<br/>Class with 87 occurrences.| 
| [HsdoService](classes/HsdoService.md) | A service provided by an organization, e.g. delivery service, print services, etc.<br/>Class with 87 occurrences.| 
| [HsdoServiceChannel](classes/HsdoServiceChannel.md) | A means for accessing a service, e.g. a government office location, web site, or phone number.<br/>Class with 174 occurrences.| 
| [HsdoTextObject](classes/HsdoTextObject.md) | A text file. The text can be unformatted or contain markup, html, etc.<br/>Class with 87 occurrences.| 





## Slots

| Slot | Description |
| --- | --- |
| [hsdo_address](slots/hsdo_address.md) | No slot (predicate) description specified<br/>93 occurrences with subject type hsdo_Place and object type string.|
| [hsdo_areaServed](slots/hsdo_areaServed.md) | No slot (predicate) description specified<br/>87 occurrences with subject type hsdo_Service and object type string.|
| [hsdo_audienceType](slots/hsdo_audienceType.md) | No slot (predicate) description specified<br/>81 occurrences with subject type hsdo_Audience and object type string.|
| [hsdo_availableChannel](slots/hsdo_availableChannel.md) | No slot (predicate) description specified<br/>174 occurrences with subject type hsdo_Service and object type hsdo_ServiceChannel.|
| [hsdo_category](slots/hsdo_category.md) | No slot (predicate) description specified<br/>539 occurrences with subject type hsdo_Service and object type hsdo_Audience.<br/>806 occurrences with subject type hsdo_Service and object type hsdo_CategoryCode.|
| [hsdo_closes](slots/hsdo_closes.md) | No slot (predicate) description specified<br/>623 occurrences with subject type hsdo_OpeningHoursSpecification and object type string.|
| [hsdo_codeValue](slots/hsdo_codeValue.md) | No slot (predicate) description specified<br/>158 occurrences with subject type hsdo_CategoryCode and object type string.|
| [hsdo_conditionsOfAccess](slots/hsdo_conditionsOfAccess.md) | No slot (predicate) description specified<br/>88 occurrences with subject type hsdo_TextObject and object type string.|
| [hsdo_containedInPlace](slots/hsdo_containedInPlace.md) | No slot (predicate) description specified<br/>88 occurrences with subject type hsdo_Place and object type hsdo_AdministrativeArea.|
| [hsdo_dayOfWeek](slots/hsdo_dayOfWeek.md) | No slot (predicate) description specified<br/>609 occurrences with subject type hsdo_OpeningHoursSpecification and object type string.|
| [hsdo_description](slots/hsdo_description.md) | No slot (predicate) description specified<br/>87 occurrences with subject type hsdo_Service and object type hsdo_TextObject.|
| [hsdo_disambiguatingDescription](slots/hsdo_disambiguatingDescription.md) | No slot (predicate) description specified<br/>174 occurrences with subject type hsdo_ServiceChannel and object type string.|
| [hsdo_hasMap](slots/hsdo_hasMap.md) | No slot (predicate) description specified<br/>88 occurrences with subject type hsdo_Place and object type uri.|
| [hsdo_hoursAvailable](slots/hsdo_hoursAvailable.md) | No slot (predicate) description specified<br/>609 occurrences with subject type hsdo_Service and object type hsdo_OpeningHoursSpecification.|
| [hsdo_identifier](slots/hsdo_identifier.md) | No slot (predicate) description specified<br/>39 occurrences with subject type hsdo_AdministrativeArea and object type string.<br/>87 occurrences with subject type hsdo_Service and object type string.|
| [hsdo_inCodeSet](slots/hsdo_inCodeSet.md) | No slot (predicate) description specified<br/>157 occurrences with subject type hsdo_CategoryCode and object type uri.|
| [hsdo_latitude](slots/hsdo_latitude.md) | No slot (predicate) description specified<br/>89 occurrences with subject type hsdo_Place and object type decimal.|
| [hsdo_longitude](slots/hsdo_longitude.md) | No slot (predicate) description specified<br/>89 occurrences with subject type hsdo_Place and object type decimal.|
| [hsdo_name](slots/hsdo_name.md) | No slot (predicate) description specified<br/>89 occurrences with subject type hsdo_Organization and object type string.<br/>88 occurrences with subject type hsdo_Service and object type string.|
| [hsdo_opens](slots/hsdo_opens.md) | No slot (predicate) description specified<br/>631 occurrences with subject type hsdo_OpeningHoursSpecification and object type string.|
| [hsdo_provider](slots/hsdo_provider.md) | No slot (predicate) description specified<br/>87 occurrences with subject type hsdo_Service and object type hsdo_Organization.|
| [hsdo_sameAs](slots/hsdo_sameAs.md) | No slot (predicate) description specified<br/>127 occurrences with subject type hsdo_Organization and object type uri.|
| [hsdo_serviceLocation](slots/hsdo_serviceLocation.md) | No slot (predicate) description specified<br/>87 occurrences with subject type hsdo_ServiceChannel and object type hsdo_Place.|
| [hsdo_servicePhone](slots/hsdo_servicePhone.md) | No slot (predicate) description specified<br/>87 occurrences with subject type hsdo_ServiceChannel and object type hsdo_ContactPoint.|
| [hsdo_serviceUrl](slots/hsdo_serviceUrl.md) | No slot (predicate) description specified<br/>188 occurrences with subject type hsdo_ServiceChannel and object type uri.|
| [hsdo_telephone](slots/hsdo_telephone.md) | No slot (predicate) description specified<br/>87 occurrences with subject type hsdo_ContactPoint and object type string.|
| [hsdo_text](slots/hsdo_text.md) | No slot (predicate) description specified<br/>90 occurrences with subject type hsdo_TextObject and object type string.|







