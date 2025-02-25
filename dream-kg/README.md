# UF-OKN

No schema description specified



## Schema Diagram

```mermaid
erDiagram
HsdoAdministrativeArea {
    uri prov_wasInfluencedBy  
    string hsdo_identifier  
}
HsdoAudience {
    uri prov_wasInfluencedBy  
    string hsdo_audienceType  
}
HsdoCategoryCode {
    uri prov_wasInfluencedBy  
    string hsdo_codeValue  
    uri hsdo_inCodeSet  
}
HsdoContactPoint {
    string hsdo_telephone  
    uri prov_wasInfluencedBy  
}
HsdoOpeningHoursSpecification {
    uri prov_wasInfluencedBy  
    string hsdo_dayOfWeek  
    string hsdo_opens  
    string hsdo_closes  
}
HsdoOrganization {
    uri hsdo_sameAs  
    string hsdo_name  
    uri prov_wasInfluencedBy  
}
HsdoPlace {
    string hsdo_address  
    uri hsdo_hasMap  
    uri prov_wasInfluencedBy  
    decimal hsdo_latitude  
    decimal hsdo_longitude  
}
HsdoService {
    string hsdo_name  
    string hsdo_areaServed  
    uri prov_wasInfluencedBy  
    string hsdo_identifier  
}
HsdoServiceChannel {
    string hsdo_disambiguatingDescription  
    uri hsdo_serviceUrl  
}
HsdoTextObject {
    string hsdo_conditionsOfAccess  
    string hsdo_text  
    uri prov_wasInfluencedBy  
}
HsdoWebPage {

}
ProvActivity {

}
ProvCollection {
    uri prov_wasInfluencedBy  
}
ProvEntity {
    uri hsdo_sameAs  
    string hsdo_identifier  
    string hsdo_opens  
    string hsdo_audienceType  
    string hsdo_text  
    string hsdo_areaServed  
    string hsdo_conditionsOfAccess  
    string hsdo_address  
    string hsdo_telephone  
    uri hsdo_hasMap  
    string hsdo_dayOfWeek  
    string hsdo_name  
    uri prov_wasInfluencedBy  
    string hsdo_codeValue  
    decimal hsdo_latitude  
    decimal hsdo_longitude  
    uri hsdo_inCodeSet  
    string hsdo_closes  
}

HsdoAdministrativeArea ||--|o HsdoWebPage : "prov_wasInfluencedBy"
HsdoAdministrativeArea ||--|o HsdoTextObject : "prov_wasInfluencedBy"
HsdoAdministrativeArea ||--|o HsdoService : "prov_wasInfluencedBy"
HsdoAdministrativeArea ||--|o HsdoOpeningHoursSpecification : "prov_wasInfluencedBy"
HsdoAdministrativeArea ||--|o HsdoOrganization : "prov_wasInfluencedBy"
HsdoAdministrativeArea ||--|o ProvEntity : "prov_wasInfluencedBy"
HsdoAdministrativeArea ||--|o ProvActivity : "prov_wasInfluencedBy"
HsdoAdministrativeArea ||--|o HsdoPlace : "prov_wasInfluencedBy"
HsdoAdministrativeArea ||--|o HsdoContactPoint : "prov_wasInfluencedBy"
HsdoAdministrativeArea ||--|o ProvEntity : "prov_wasDerivedFrom"
HsdoAdministrativeArea ||--|o ProvActivity : "prov_wasGeneratedBy"
HsdoAudience ||--|o HsdoWebPage : "prov_wasInfluencedBy"
HsdoAudience ||--|o HsdoTextObject : "prov_wasInfluencedBy"
HsdoAudience ||--|o HsdoService : "prov_wasInfluencedBy"
HsdoAudience ||--|o HsdoOpeningHoursSpecification : "prov_wasInfluencedBy"
HsdoAudience ||--|o HsdoOrganization : "prov_wasInfluencedBy"
HsdoAudience ||--|o ProvEntity : "prov_wasInfluencedBy"
HsdoAudience ||--|o ProvActivity : "prov_wasInfluencedBy"
HsdoAudience ||--|o HsdoPlace : "prov_wasInfluencedBy"
HsdoAudience ||--|o HsdoContactPoint : "prov_wasInfluencedBy"
HsdoAudience ||--|o ProvEntity : "prov_wasDerivedFrom"
HsdoAudience ||--|o ProvActivity : "prov_wasGeneratedBy"
HsdoCategoryCode ||--|o ProvEntity : "prov_wasDerivedFrom"
HsdoCategoryCode ||--|o ProvActivity : "prov_wasGeneratedBy"
HsdoCategoryCode ||--|o HsdoWebPage : "prov_wasInfluencedBy"
HsdoCategoryCode ||--|o HsdoTextObject : "prov_wasInfluencedBy"
HsdoCategoryCode ||--|o HsdoService : "prov_wasInfluencedBy"
HsdoCategoryCode ||--|o HsdoOpeningHoursSpecification : "prov_wasInfluencedBy"
HsdoCategoryCode ||--|o HsdoOrganization : "prov_wasInfluencedBy"
HsdoCategoryCode ||--|o ProvEntity : "prov_wasInfluencedBy"
HsdoCategoryCode ||--|o ProvActivity : "prov_wasInfluencedBy"
HsdoCategoryCode ||--|o HsdoPlace : "prov_wasInfluencedBy"
HsdoCategoryCode ||--|o HsdoContactPoint : "prov_wasInfluencedBy"
HsdoContactPoint ||--|o ProvEntity : "prov_wasDerivedFrom"
HsdoContactPoint ||--|o ProvActivity : "prov_wasGeneratedBy"
HsdoContactPoint ||--|o HsdoTextObject : "prov_influenced"
HsdoContactPoint ||--|o HsdoService : "prov_influenced"
HsdoContactPoint ||--|o HsdoOpeningHoursSpecification : "prov_influenced"
HsdoContactPoint ||--|o HsdoOrganization : "prov_influenced"
HsdoContactPoint ||--|o ProvCollection : "prov_influenced"
HsdoContactPoint ||--|o ProvEntity : "prov_influenced"
HsdoContactPoint ||--|o HsdoCategoryCode : "prov_influenced"
HsdoContactPoint ||--|o HsdoAudience : "prov_influenced"
HsdoContactPoint ||--|o HsdoPlace : "prov_influenced"
HsdoContactPoint ||--|o HsdoContactPoint : "prov_influenced"
HsdoContactPoint ||--|o HsdoAdministrativeArea : "prov_influenced"
HsdoContactPoint ||--|o HsdoWebPage : "prov_wasInfluencedBy"
HsdoContactPoint ||--|o HsdoTextObject : "prov_wasInfluencedBy"
HsdoContactPoint ||--|o HsdoService : "prov_wasInfluencedBy"
HsdoContactPoint ||--|o HsdoOpeningHoursSpecification : "prov_wasInfluencedBy"
HsdoContactPoint ||--|o HsdoOrganization : "prov_wasInfluencedBy"
HsdoContactPoint ||--|o ProvEntity : "prov_wasInfluencedBy"
HsdoContactPoint ||--|o ProvActivity : "prov_wasInfluencedBy"
HsdoContactPoint ||--|o HsdoPlace : "prov_wasInfluencedBy"
HsdoContactPoint ||--|o HsdoContactPoint : "prov_wasInfluencedBy"
HsdoOpeningHoursSpecification ||--|o ProvEntity : "prov_wasDerivedFrom"
HsdoOpeningHoursSpecification ||--|o ProvActivity : "prov_wasGeneratedBy"
HsdoOpeningHoursSpecification ||--|o HsdoTextObject : "prov_influenced"
HsdoOpeningHoursSpecification ||--|o HsdoService : "prov_influenced"
HsdoOpeningHoursSpecification ||--|o HsdoOpeningHoursSpecification : "prov_influenced"
HsdoOpeningHoursSpecification ||--|o HsdoOrganization : "prov_influenced"
HsdoOpeningHoursSpecification ||--|o ProvCollection : "prov_influenced"
HsdoOpeningHoursSpecification ||--|o ProvEntity : "prov_influenced"
HsdoOpeningHoursSpecification ||--|o HsdoCategoryCode : "prov_influenced"
HsdoOpeningHoursSpecification ||--|o HsdoAudience : "prov_influenced"
HsdoOpeningHoursSpecification ||--|o HsdoPlace : "prov_influenced"
HsdoOpeningHoursSpecification ||--|o HsdoContactPoint : "prov_influenced"
HsdoOpeningHoursSpecification ||--|o HsdoAdministrativeArea : "prov_influenced"
HsdoOpeningHoursSpecification ||--|o HsdoWebPage : "prov_wasInfluencedBy"
HsdoOpeningHoursSpecification ||--|o HsdoTextObject : "prov_wasInfluencedBy"
HsdoOpeningHoursSpecification ||--|o HsdoService : "prov_wasInfluencedBy"
HsdoOpeningHoursSpecification ||--|o HsdoOpeningHoursSpecification : "prov_wasInfluencedBy"
HsdoOpeningHoursSpecification ||--|o HsdoOrganization : "prov_wasInfluencedBy"
HsdoOpeningHoursSpecification ||--|o ProvEntity : "prov_wasInfluencedBy"
HsdoOpeningHoursSpecification ||--|o ProvActivity : "prov_wasInfluencedBy"
HsdoOpeningHoursSpecification ||--|o HsdoPlace : "prov_wasInfluencedBy"
HsdoOpeningHoursSpecification ||--|o HsdoContactPoint : "prov_wasInfluencedBy"
HsdoOrganization ||--|o ProvEntity : "prov_wasDerivedFrom"
HsdoOrganization ||--|o ProvActivity : "prov_wasGeneratedBy"
HsdoOrganization ||--|o HsdoTextObject : "prov_influenced"
HsdoOrganization ||--|o HsdoService : "prov_influenced"
HsdoOrganization ||--|o HsdoOpeningHoursSpecification : "prov_influenced"
HsdoOrganization ||--|o HsdoOrganization : "prov_influenced"
HsdoOrganization ||--|o ProvCollection : "prov_influenced"
HsdoOrganization ||--|o ProvEntity : "prov_influenced"
HsdoOrganization ||--|o HsdoCategoryCode : "prov_influenced"
HsdoOrganization ||--|o HsdoAudience : "prov_influenced"
HsdoOrganization ||--|o HsdoPlace : "prov_influenced"
HsdoOrganization ||--|o HsdoContactPoint : "prov_influenced"
HsdoOrganization ||--|o HsdoAdministrativeArea : "prov_influenced"
HsdoOrganization ||--|o HsdoWebPage : "prov_wasInfluencedBy"
HsdoOrganization ||--|o HsdoTextObject : "prov_wasInfluencedBy"
HsdoOrganization ||--|o HsdoService : "prov_wasInfluencedBy"
HsdoOrganization ||--|o HsdoOpeningHoursSpecification : "prov_wasInfluencedBy"
HsdoOrganization ||--|o HsdoOrganization : "prov_wasInfluencedBy"
HsdoOrganization ||--|o ProvEntity : "prov_wasInfluencedBy"
HsdoOrganization ||--|o ProvActivity : "prov_wasInfluencedBy"
HsdoOrganization ||--|o HsdoPlace : "prov_wasInfluencedBy"
HsdoOrganization ||--|o HsdoContactPoint : "prov_wasInfluencedBy"
HsdoPlace ||--|o ProvEntity : "prov_wasDerivedFrom"
HsdoPlace ||--|o ProvActivity : "prov_wasGeneratedBy"
HsdoPlace ||--|o HsdoTextObject : "prov_influenced"
HsdoPlace ||--|o HsdoService : "prov_influenced"
HsdoPlace ||--|o HsdoOpeningHoursSpecification : "prov_influenced"
HsdoPlace ||--|o HsdoOrganization : "prov_influenced"
HsdoPlace ||--|o ProvCollection : "prov_influenced"
HsdoPlace ||--|o ProvEntity : "prov_influenced"
HsdoPlace ||--|o HsdoCategoryCode : "prov_influenced"
HsdoPlace ||--|o HsdoAudience : "prov_influenced"
HsdoPlace ||--|o HsdoPlace : "prov_influenced"
HsdoPlace ||--|o HsdoContactPoint : "prov_influenced"
HsdoPlace ||--|o HsdoAdministrativeArea : "prov_influenced"
HsdoPlace ||--|o ProvEntity : "hsdo_containedInPlace"
HsdoPlace ||--|o HsdoAdministrativeArea : "hsdo_containedInPlace"
HsdoPlace ||--|o HsdoWebPage : "prov_wasInfluencedBy"
HsdoPlace ||--|o HsdoTextObject : "prov_wasInfluencedBy"
HsdoPlace ||--|o HsdoService : "prov_wasInfluencedBy"
HsdoPlace ||--|o HsdoOpeningHoursSpecification : "prov_wasInfluencedBy"
HsdoPlace ||--|o HsdoOrganization : "prov_wasInfluencedBy"
HsdoPlace ||--|o ProvEntity : "prov_wasInfluencedBy"
HsdoPlace ||--|o ProvActivity : "prov_wasInfluencedBy"
HsdoPlace ||--|o HsdoPlace : "prov_wasInfluencedBy"
HsdoPlace ||--|o HsdoContactPoint : "prov_wasInfluencedBy"
HsdoService ||--|o ProvEntity : "hsdo_hoursAvailable"
HsdoService ||--|o HsdoOpeningHoursSpecification : "hsdo_hoursAvailable"
HsdoService ||--|o ProvEntity : "hsdo_description"
HsdoService ||--|o HsdoTextObject : "hsdo_description"
HsdoService ||--|o ProvEntity : "prov_wasDerivedFrom"
HsdoService ||--|o HsdoTextObject : "prov_influenced"
HsdoService ||--|o HsdoService : "prov_influenced"
HsdoService ||--|o HsdoOpeningHoursSpecification : "prov_influenced"
HsdoService ||--|o HsdoOrganization : "prov_influenced"
HsdoService ||--|o ProvCollection : "prov_influenced"
HsdoService ||--|o ProvEntity : "prov_influenced"
HsdoService ||--|o HsdoCategoryCode : "prov_influenced"
HsdoService ||--|o HsdoAudience : "prov_influenced"
HsdoService ||--|o HsdoPlace : "prov_influenced"
HsdoService ||--|o HsdoContactPoint : "prov_influenced"
HsdoService ||--|o HsdoAdministrativeArea : "prov_influenced"
HsdoService ||--|o ProvActivity : "prov_wasGeneratedBy"
HsdoService ||--|o HsdoWebPage : "prov_wasInfluencedBy"
HsdoService ||--|o HsdoTextObject : "prov_wasInfluencedBy"
HsdoService ||--|o HsdoService : "prov_wasInfluencedBy"
HsdoService ||--|o HsdoOpeningHoursSpecification : "prov_wasInfluencedBy"
HsdoService ||--|o HsdoOrganization : "prov_wasInfluencedBy"
HsdoService ||--|o ProvEntity : "prov_wasInfluencedBy"
HsdoService ||--|o ProvActivity : "prov_wasInfluencedBy"
HsdoService ||--|o HsdoPlace : "prov_wasInfluencedBy"
HsdoService ||--|o HsdoContactPoint : "prov_wasInfluencedBy"
HsdoService ||--|o HsdoServiceChannel : "hsdo_availableChannel"
HsdoService ||--|o HsdoAudience : "hsdo_category"
HsdoService ||--|o ProvEntity : "hsdo_category"
HsdoService ||--|o HsdoCategoryCode : "hsdo_category"
HsdoService ||--|o ProvEntity : "hsdo_provider"
HsdoService ||--|o HsdoOrganization : "hsdo_provider"
HsdoServiceChannel ||--|o ProvEntity : "hsdo_servicePhone"
HsdoServiceChannel ||--|o HsdoContactPoint : "hsdo_servicePhone"
HsdoServiceChannel ||--|o ProvEntity : "hsdo_serviceLocation"
HsdoServiceChannel ||--|o HsdoPlace : "hsdo_serviceLocation"
HsdoTextObject ||--|o ProvEntity : "prov_wasDerivedFrom"
HsdoTextObject ||--|o ProvActivity : "prov_wasGeneratedBy"
HsdoTextObject ||--|o HsdoTextObject : "prov_influenced"
HsdoTextObject ||--|o HsdoService : "prov_influenced"
HsdoTextObject ||--|o HsdoOpeningHoursSpecification : "prov_influenced"
HsdoTextObject ||--|o HsdoOrganization : "prov_influenced"
HsdoTextObject ||--|o ProvCollection : "prov_influenced"
HsdoTextObject ||--|o ProvEntity : "prov_influenced"
HsdoTextObject ||--|o HsdoCategoryCode : "prov_influenced"
HsdoTextObject ||--|o HsdoAudience : "prov_influenced"
HsdoTextObject ||--|o HsdoPlace : "prov_influenced"
HsdoTextObject ||--|o HsdoContactPoint : "prov_influenced"
HsdoTextObject ||--|o HsdoAdministrativeArea : "prov_influenced"
HsdoTextObject ||--|o HsdoWebPage : "prov_wasInfluencedBy"
HsdoTextObject ||--|o HsdoTextObject : "prov_wasInfluencedBy"
HsdoTextObject ||--|o HsdoService : "prov_wasInfluencedBy"
HsdoTextObject ||--|o HsdoOpeningHoursSpecification : "prov_wasInfluencedBy"
HsdoTextObject ||--|o HsdoOrganization : "prov_wasInfluencedBy"
HsdoTextObject ||--|o ProvEntity : "prov_wasInfluencedBy"
HsdoTextObject ||--|o ProvActivity : "prov_wasInfluencedBy"
HsdoTextObject ||--|o HsdoPlace : "prov_wasInfluencedBy"
HsdoTextObject ||--|o HsdoContactPoint : "prov_wasInfluencedBy"
HsdoWebPage ||--|o HsdoTextObject : "prov_influenced"
HsdoWebPage ||--|o HsdoService : "prov_influenced"
HsdoWebPage ||--|o HsdoOpeningHoursSpecification : "prov_influenced"
HsdoWebPage ||--|o HsdoOrganization : "prov_influenced"
HsdoWebPage ||--|o ProvCollection : "prov_influenced"
HsdoWebPage ||--|o ProvEntity : "prov_influenced"
HsdoWebPage ||--|o HsdoCategoryCode : "prov_influenced"
HsdoWebPage ||--|o HsdoAudience : "prov_influenced"
HsdoWebPage ||--|o HsdoPlace : "prov_influenced"
HsdoWebPage ||--|o HsdoContactPoint : "prov_influenced"
HsdoWebPage ||--|o HsdoAdministrativeArea : "prov_influenced"
ProvActivity ||--|o HsdoTextObject : "prov_generated"
ProvActivity ||--|o HsdoService : "prov_generated"
ProvActivity ||--|o HsdoOpeningHoursSpecification : "prov_generated"
ProvActivity ||--|o HsdoOrganization : "prov_generated"
ProvActivity ||--|o ProvEntity : "prov_generated"
ProvActivity ||--|o HsdoCategoryCode : "prov_generated"
ProvActivity ||--|o HsdoAudience : "prov_generated"
ProvActivity ||--|o HsdoPlace : "prov_generated"
ProvActivity ||--|o HsdoContactPoint : "prov_generated"
ProvActivity ||--|o HsdoAdministrativeArea : "prov_generated"
ProvActivity ||--|o HsdoTextObject : "prov_influenced"
ProvActivity ||--|o HsdoService : "prov_influenced"
ProvActivity ||--|o HsdoOpeningHoursSpecification : "prov_influenced"
ProvActivity ||--|o HsdoOrganization : "prov_influenced"
ProvActivity ||--|o ProvCollection : "prov_influenced"
ProvActivity ||--|o ProvEntity : "prov_influenced"
ProvActivity ||--|o HsdoCategoryCode : "prov_influenced"
ProvActivity ||--|o HsdoAudience : "prov_influenced"
ProvActivity ||--|o HsdoPlace : "prov_influenced"
ProvActivity ||--|o HsdoContactPoint : "prov_influenced"
ProvActivity ||--|o HsdoAdministrativeArea : "prov_influenced"
ProvCollection ||--|o HsdoWebPage : "prov_hadMember"
ProvCollection ||--|o HsdoTextObject : "prov_hadMember"
ProvCollection ||--|o HsdoOpeningHoursSpecification : "prov_hadMember"
ProvCollection ||--|o HsdoService : "prov_hadMember"
ProvCollection ||--|o HsdoOrganization : "prov_hadMember"
ProvCollection ||--|o ProvEntity : "prov_hadMember"
ProvCollection ||--|o HsdoPlace : "prov_hadMember"
ProvCollection ||--|o HsdoContactPoint : "prov_hadMember"
ProvCollection ||--|o HsdoWebPage : "prov_wasInfluencedBy"
ProvCollection ||--|o HsdoTextObject : "prov_wasInfluencedBy"
ProvCollection ||--|o HsdoService : "prov_wasInfluencedBy"
ProvCollection ||--|o HsdoOpeningHoursSpecification : "prov_wasInfluencedBy"
ProvCollection ||--|o HsdoOrganization : "prov_wasInfluencedBy"
ProvCollection ||--|o ProvEntity : "prov_wasInfluencedBy"
ProvCollection ||--|o ProvActivity : "prov_wasInfluencedBy"
ProvCollection ||--|o HsdoPlace : "prov_wasInfluencedBy"
ProvCollection ||--|o HsdoContactPoint : "prov_wasInfluencedBy"
ProvEntity ||--|o ProvEntity : "prov_wasDerivedFrom"
ProvEntity ||--|o ProvEntity : "hsdo_description"
ProvEntity ||--|o HsdoTextObject : "hsdo_description"
ProvEntity ||--|o HsdoWebPage : "prov_hadMember"
ProvEntity ||--|o HsdoTextObject : "prov_hadMember"
ProvEntity ||--|o HsdoOpeningHoursSpecification : "prov_hadMember"
ProvEntity ||--|o HsdoService : "prov_hadMember"
ProvEntity ||--|o HsdoOrganization : "prov_hadMember"
ProvEntity ||--|o ProvEntity : "prov_hadMember"
ProvEntity ||--|o HsdoPlace : "prov_hadMember"
ProvEntity ||--|o HsdoContactPoint : "prov_hadMember"
ProvEntity ||--|o ProvEntity : "hsdo_provider"
ProvEntity ||--|o HsdoOrganization : "hsdo_provider"
ProvEntity ||--|o ProvEntity : "hsdo_hoursAvailable"
ProvEntity ||--|o HsdoOpeningHoursSpecification : "hsdo_hoursAvailable"
ProvEntity ||--|o ProvActivity : "prov_wasGeneratedBy"
ProvEntity ||--|o HsdoAudience : "hsdo_category"
ProvEntity ||--|o ProvEntity : "hsdo_category"
ProvEntity ||--|o HsdoCategoryCode : "hsdo_category"
ProvEntity ||--|o HsdoServiceChannel : "hsdo_availableChannel"
ProvEntity ||--|o HsdoTextObject : "prov_influenced"
ProvEntity ||--|o HsdoService : "prov_influenced"
ProvEntity ||--|o HsdoOpeningHoursSpecification : "prov_influenced"
ProvEntity ||--|o HsdoOrganization : "prov_influenced"
ProvEntity ||--|o ProvCollection : "prov_influenced"
ProvEntity ||--|o ProvEntity : "prov_influenced"
ProvEntity ||--|o HsdoCategoryCode : "prov_influenced"
ProvEntity ||--|o HsdoAudience : "prov_influenced"
ProvEntity ||--|o HsdoPlace : "prov_influenced"
ProvEntity ||--|o HsdoContactPoint : "prov_influenced"
ProvEntity ||--|o HsdoAdministrativeArea : "prov_influenced"
ProvEntity ||--|o ProvEntity : "hsdo_containedInPlace"
ProvEntity ||--|o HsdoAdministrativeArea : "hsdo_containedInPlace"
ProvEntity ||--|o HsdoWebPage : "prov_wasInfluencedBy"
ProvEntity ||--|o HsdoTextObject : "prov_wasInfluencedBy"
ProvEntity ||--|o HsdoService : "prov_wasInfluencedBy"
ProvEntity ||--|o HsdoOpeningHoursSpecification : "prov_wasInfluencedBy"
ProvEntity ||--|o HsdoOrganization : "prov_wasInfluencedBy"
ProvEntity ||--|o ProvEntity : "prov_wasInfluencedBy"
ProvEntity ||--|o ProvActivity : "prov_wasInfluencedBy"
ProvEntity ||--|o HsdoPlace : "prov_wasInfluencedBy"
ProvEntity ||--|o HsdoContactPoint : "prov_wasInfluencedBy"

```



## Classes

| Class | Description | Occurrences |
| --- | --- | --- |
| [HsdoAdministrativeArea](classes/HsdoAdministrativeArea.md) | A geographical region, typically under the jurisdiction of a particular government.<br/>| 39 | 
| [HsdoAudience](classes/HsdoAudience.md) | Intended audience for an item, i.e. the group for whom the item was created.<br/>| 81 | 
| [HsdoCategoryCode](classes/HsdoCategoryCode.md) | A Category Code.<br/>| 157 | 
| [HsdoContactPoint](classes/HsdoContactPoint.md) | A contact point&#x2014;for example, a Customer Complaints department.<br/>| 87 | 
| [HsdoOpeningHoursSpecification](classes/HsdoOpeningHoursSpecification.md) | A structured value providing information about the opening hours of a place or a certain service inside a place.\n\n␊The place is __open__ if the [[opens]] property is specified, and __closed__ otherwise.\n\nIf the value for the [[closes]] property is less than the value for the [[opens]] property then the hour range is assumed to span over the next day.␊      <br/>| 609 | 
| [HsdoOrganization](classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc.<br/>| 87 | 
| [HsdoPlace](classes/HsdoPlace.md) | Entities that have a somewhat fixed, physical extension.<br/>| 87 | 
| [HsdoService](classes/HsdoService.md) | A service provided by an organization, e.g. delivery service, print services, etc.<br/>| 87 | 
| [HsdoServiceChannel](classes/HsdoServiceChannel.md) | A means for accessing a service, e.g. a government office location, web site, or phone number.<br/>| 174 | 
| [HsdoTextObject](classes/HsdoTextObject.md) | A text file. The text can be unformatted or contain markup, html, etc.<br/>| 87 | 
| [HsdoWebPage](classes/HsdoWebPage.md) | A web page. Every web page is implicitly assumed to be declared to be of type WebPage, so the various properties about that webpage, such as <code>breadcrumb</code> may be used. We recommend explicit declaration if these properties are specified, but if they are found outside of an itemscope, they will be assumed to be about the page.<br/>| 87 | 
| [ProvActivity](classes/ProvActivity.md) | No class (type) description specified<br/>| 1 | 
| [ProvCollection](classes/ProvCollection.md) | No class (type) description specified<br/>| 2 | 
| [ProvEntity](classes/ProvEntity.md) | No class (type) description specified<br/>| 1586 | 





## Slots

| Slot | Description | Occurrences |
| --- | --- | --- |
| [hsdo_address](slots/hsdo_address.md) | Physical address of the item<br/>| 93 |
| [hsdo_areaServed](slots/hsdo_areaServed.md) | The geographic area where a service or offered item is provided<br/>| 87 |
| [hsdo_audienceType](slots/hsdo_audienceType.md) | The target group associated with a given audience (e<br/>| 81 |
| [hsdo_availableChannel](slots/hsdo_availableChannel.md) | A means of accessing the service (e<br/>| 174 |
| [hsdo_category](slots/hsdo_category.md) | A category for the item<br/>| 1345 |
| [hsdo_closes](slots/hsdo_closes.md) | The closing hour of the place or service on the given day(s) of the week<br/>| 623 |
| [hsdo_codeValue](slots/hsdo_codeValue.md) | A short textual code that uniquely identifies the value<br/>| 158 |
| [hsdo_conditionsOfAccess](slots/hsdo_conditionsOfAccess.md) | Conditions that affect the availability of, or method(s) of access to, an ite...<br/>| 88 |
| [hsdo_containedInPlace](slots/hsdo_containedInPlace.md) | The basic containment relation between a place and one that contains it<br/>| 88 |
| [hsdo_dayOfWeek](slots/hsdo_dayOfWeek.md) | The day of the week for which these opening hours are valid<br/>| 609 |
| [hsdo_description](slots/hsdo_description.md) | A description of the item<br/>| 87 |
| [hsdo_disambiguatingDescription](slots/hsdo_disambiguatingDescription.md) | A sub property of description<br/>| 174 |
| [hsdo_hasMap](slots/hsdo_hasMap.md) | A URL to a map of the place<br/>| 88 |
| [hsdo_hoursAvailable](slots/hsdo_hoursAvailable.md) | The hours during which this service or contact is available<br/>| 609 |
| [hsdo_identifier](slots/hsdo_identifier.md) | The identifier property represents any kind of identifier for any kind of [[T...<br/>| 126 |
| [hsdo_inCodeSet](slots/hsdo_inCodeSet.md) | A [[CategoryCodeSet]] that contains this category code<br/>| 157 |
| [hsdo_latitude](slots/hsdo_latitude.md) | The latitude of a location<br/>| 89 |
| [hsdo_longitude](slots/hsdo_longitude.md) | The longitude of a location<br/>| 89 |
| [hsdo_name](slots/hsdo_name.md) | The name of the item<br/>| 177 |
| [hsdo_opens](slots/hsdo_opens.md) | The opening hour of the place or service on the given day(s) of the week<br/>| 631 |
| [hsdo_provider](slots/hsdo_provider.md) | The service provider, service operator, or service performer; the goods produ...<br/>| 87 |
| [hsdo_sameAs](slots/hsdo_sameAs.md) | URL of a reference Web page that unambiguously indicates the item's identity<br/>| 127 |
| [hsdo_serviceLocation](slots/hsdo_serviceLocation.md) | The location (e<br/>| 87 |
| [hsdo_servicePhone](slots/hsdo_servicePhone.md) | The phone number to use to access the service<br/>| 87 |
| [hsdo_serviceUrl](slots/hsdo_serviceUrl.md) | The website to access the service<br/>| 188 |
| [hsdo_telephone](slots/hsdo_telephone.md) | The telephone number<br/>| 87 |
| [hsdo_text](slots/hsdo_text.md) | The textual content of this CreativeWork<br/>| 90 |
| [prov_generated](slots/prov_generated.md) | No slot (predicate) description specified<br/>| 1495 |
| [prov_hadMember](slots/prov_hadMember.md) | No slot (predicate) description specified<br/>| 1305 |
| [prov_influenced](slots/prov_influenced.md) | No slot (predicate) description specified<br/>| 7839 |
| [prov_wasDerivedFrom](slots/prov_wasDerivedFrom.md) | No slot (predicate) description specified<br/>| 2990 |
| [prov_wasGeneratedBy](slots/prov_wasGeneratedBy.md) | No slot (predicate) description specified<br/>| 1495 |
| [prov_wasInfluencedBy](slots/prov_wasInfluencedBy.md) | No slot (predicate) description specified<br/>| 7839 |









## IRI prefixes

* dreamkg: http://www.semanticweb.org/dreamkg/ijcai/
* hsdo: http://schema.org/
* linkml: https://w3id.org/linkml/
* prov: http://www.w3.org/ns/prov#
* xsd: http://www.w3.org/2001/XMLSchema#
* shex: http://www.w3.org/ns/shex#
* schema: http://schema.org/
