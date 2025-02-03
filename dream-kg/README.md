# dream-kg

No schema description specified



## IRI prefixes

* dreamkg: http://www.semanticweb.org/dreamkg/ijcai/
* hsdo: http://schema.org/
* linkml: https://w3id.org/linkml/
* prov: http://www.w3.org/ns/prov#
* rdf: http://www.w3.org/1999/02/22-rdf-syntax-ns#
* xsd: http://www.w3.org/2001/XMLSchema#
* shex: http://www.w3.org/ns/shex#
* schema: http://schema.org/



## Classes

| Class | Description |
| --- | --- |
| [HsdoAdministrativeArea](HsdoAdministrativeArea.md) | A geographical region, typically under the jurisdiction of a particular government.<br/>Class with 39 occurrences.| 
| [HsdoAudience](HsdoAudience.md) | Intended audience for an item, i.e. the group for whom the item was created.<br/>Class with 81 occurrences.| 
| [HsdoCategoryCode](HsdoCategoryCode.md) | A Category Code.<br/>Class with 157 occurrences.| 
| [HsdoContactPoint](HsdoContactPoint.md) | A contact point&#x2014;for example, a Customer Complaints department.<br/>Class with 87 occurrences.| 
| [HsdoOpeningHoursSpecification](HsdoOpeningHoursSpecification.md) | A structured value providing information about the opening hours of a place or a certain service inside a place.\n\n␊The place is __open__ if the [[opens]] property is specified, and __closed__ otherwise.\n\nIf the value for the [[closes]] property is less than the value for the [[opens]] property then the hour range is assumed to span over the next day.␊      <br/>Class with 609 occurrences.| 
| [HsdoOrganization](HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc.<br/>Class with 87 occurrences.| 
| [HsdoPlace](HsdoPlace.md) | Entities that have a somewhat fixed, physical extension.<br/>Class with 87 occurrences.| 
| [HsdoService](HsdoService.md) | A service provided by an organization, e.g. delivery service, print services, etc.<br/>Class with 87 occurrences.| 
| [HsdoServiceChannel](HsdoServiceChannel.md) | A means for accessing a service, e.g. a government office location, web site, or phone number.<br/>Class with 174 occurrences.| 
| [HsdoTextObject](HsdoTextObject.md) | A text file. The text can be unformatted or contain markup, html, etc.<br/>Class with 87 occurrences.| 
| [HsdoWebPage](HsdoWebPage.md) | A web page. Every web page is implicitly assumed to be declared to be of type WebPage, so the various properties about that webpage, such as <code>breadcrumb</code> may be used. We recommend explicit declaration if these properties are specified, but if they are found outside of an itemscope, they will be assumed to be about the page.<br/>Class with 87 occurrences.| 
| [ProvActivity](ProvActivity.md) | No class (type) description specified<br/>Class with 1 occurrences.| 
| [ProvCollection](ProvCollection.md) | No class (type) description specified<br/>Class with 2 occurrences.| 
| [ProvEntity](ProvEntity.md) | No class (type) description specified<br/>Class with 1586 occurrences.| 





## Slots

| Slot | Description |
| --- | --- |
| [hsdo_address](hsdo_address.md) | No slot (predicate) description specified<br/>93 occurrences with subject type hsdo_Place and object type string.|
| [hsdo_areaServed](hsdo_areaServed.md) | No slot (predicate) description specified<br/>87 occurrences with subject type hsdo_Service and object type string.|
| [hsdo_audienceType](hsdo_audienceType.md) | No slot (predicate) description specified<br/>81 occurrences with subject type hsdo_Audience and object type string.|
| [hsdo_availableChannel](hsdo_availableChannel.md) | No slot (predicate) description specified<br/>174 occurrences with subject type hsdo_Service and object type hsdo_ServiceChannel.|
| [hsdo_category](hsdo_category.md) | No slot (predicate) description specified<br/>539 occurrences with subject type hsdo_Service and object type hsdo_Audience.<br/>806 occurrences with subject type hsdo_Service and object type hsdo_CategoryCode.|
| [hsdo_closes](hsdo_closes.md) | No slot (predicate) description specified<br/>623 occurrences with subject type hsdo_OpeningHoursSpecification and object type string.|
| [hsdo_codeValue](hsdo_codeValue.md) | No slot (predicate) description specified<br/>158 occurrences with subject type hsdo_CategoryCode and object type string.|
| [hsdo_conditionsOfAccess](hsdo_conditionsOfAccess.md) | No slot (predicate) description specified<br/>88 occurrences with subject type hsdo_TextObject and object type string.|
| [hsdo_containedInPlace](hsdo_containedInPlace.md) | No slot (predicate) description specified<br/>88 occurrences with subject type hsdo_Place and object type hsdo_AdministrativeArea.|
| [hsdo_dayOfWeek](hsdo_dayOfWeek.md) | No slot (predicate) description specified<br/>609 occurrences with subject type hsdo_OpeningHoursSpecification and object type string.|
| [hsdo_description](hsdo_description.md) | No slot (predicate) description specified<br/>87 occurrences with subject type hsdo_Service and object type hsdo_TextObject.|
| [hsdo_disambiguatingDescription](hsdo_disambiguatingDescription.md) | No slot (predicate) description specified<br/>174 occurrences with subject type hsdo_ServiceChannel and object type string.|
| [hsdo_hasMap](hsdo_hasMap.md) | No slot (predicate) description specified<br/>88 occurrences with subject type hsdo_Place and object type uri.|
| [hsdo_hoursAvailable](hsdo_hoursAvailable.md) | No slot (predicate) description specified<br/>609 occurrences with subject type hsdo_Service and object type hsdo_OpeningHoursSpecification.|
| [hsdo_identifier](hsdo_identifier.md) | No slot (predicate) description specified<br/>87 occurrences with subject type hsdo_Service and object type string.<br/>39 occurrences with subject type hsdo_AdministrativeArea and object type string.|
| [hsdo_inCodeSet](hsdo_inCodeSet.md) | No slot (predicate) description specified<br/>157 occurrences with subject type hsdo_CategoryCode and object type uri.|
| [hsdo_latitude](hsdo_latitude.md) | No slot (predicate) description specified<br/>89 occurrences with subject type hsdo_Place and object type decimal.|
| [hsdo_longitude](hsdo_longitude.md) | No slot (predicate) description specified<br/>89 occurrences with subject type hsdo_Place and object type decimal.|
| [hsdo_name](hsdo_name.md) | No slot (predicate) description specified<br/>88 occurrences with subject type hsdo_Service and object type string.<br/>89 occurrences with subject type hsdo_Organization and object type string.|
| [hsdo_opens](hsdo_opens.md) | No slot (predicate) description specified<br/>631 occurrences with subject type hsdo_OpeningHoursSpecification and object type string.|
| [hsdo_provider](hsdo_provider.md) | No slot (predicate) description specified<br/>87 occurrences with subject type hsdo_Service and object type hsdo_Organization.|
| [hsdo_sameAs](hsdo_sameAs.md) | No slot (predicate) description specified<br/>127 occurrences with subject type hsdo_Organization and object type uri.|
| [hsdo_serviceLocation](hsdo_serviceLocation.md) | No slot (predicate) description specified<br/>87 occurrences with subject type hsdo_ServiceChannel and object type hsdo_Place.|
| [hsdo_servicePhone](hsdo_servicePhone.md) | No slot (predicate) description specified<br/>87 occurrences with subject type hsdo_ServiceChannel and object type hsdo_ContactPoint.|
| [hsdo_serviceUrl](hsdo_serviceUrl.md) | No slot (predicate) description specified<br/>188 occurrences with subject type hsdo_ServiceChannel and object type uri.|
| [hsdo_telephone](hsdo_telephone.md) | No slot (predicate) description specified<br/>87 occurrences with subject type hsdo_ContactPoint and object type string.|
| [hsdo_text](hsdo_text.md) | No slot (predicate) description specified<br/>90 occurrences with subject type hsdo_TextObject and object type string.|
| [prov_generated](prov_generated.md) | No slot (predicate) description specified<br/>81 occurrences with subject type prov_Activity and object type hsdo_Audience.<br/>157 occurrences with subject type prov_Activity and object type hsdo_CategoryCode.<br/>87 occurrences with subject type prov_Activity and object type hsdo_Service.<br/>174 occurrences with subject type prov_Activity and object type prov_Entity.<br/>87 occurrences with subject type prov_Activity and object type hsdo_TextObject.<br/>609 occurrences with subject type prov_Activity and object type hsdo_OpeningHoursSpecification.<br/>87 occurrences with subject type prov_Activity and object type hsdo_Place.<br/>87 occurrences with subject type prov_Activity and object type hsdo_ContactPoint.<br/>87 occurrences with subject type prov_Activity and object type hsdo_Organization.<br/>39 occurrences with subject type prov_Activity and object type hsdo_AdministrativeArea.|
| [prov_hadMember](prov_hadMember.md) | No slot (predicate) description specified<br/>87 occurrences with subject type prov_Collection and object type hsdo_Service.<br/>174 occurrences with subject type prov_Collection and object type prov_Entity.<br/>87 occurrences with subject type prov_Collection and object type hsdo_TextObject.<br/>609 occurrences with subject type prov_Collection and object type hsdo_OpeningHoursSpecification.<br/>87 occurrences with subject type prov_Collection and object type hsdo_Place.<br/>87 occurrences with subject type prov_Collection and object type hsdo_ContactPoint.<br/>87 occurrences with subject type prov_Collection and object type hsdo_Organization.<br/>87 occurrences with subject type prov_Collection and object type hsdo_WebPage.|
| [prov_influenced](prov_influenced.md) | No slot (predicate) description specified<br/>162 occurrences with subject type prov_Entity and object type hsdo_Audience.<br/>314 occurrences with subject type prov_Entity and object type hsdo_CategoryCode.<br/>174 occurrences with subject type prov_Entity and object type hsdo_Service.<br/>348 occurrences with subject type prov_Entity and object type prov_Entity.<br/>174 occurrences with subject type prov_Entity and object type hsdo_TextObject.<br/>1218 occurrences with subject type prov_Entity and object type hsdo_OpeningHoursSpecification.<br/>174 occurrences with subject type prov_Entity and object type hsdo_Place.<br/>174 occurrences with subject type prov_Entity and object type hsdo_ContactPoint.<br/>174 occurrences with subject type prov_Entity and object type hsdo_Organization.<br/>78 occurrences with subject type prov_Entity and object type hsdo_AdministrativeArea.<br/>243 occurrences with untyped subjects and object type hsdo_Audience.<br/>471 occurrences with untyped subjects and object type hsdo_CategoryCode.<br/>117 occurrences with untyped subjects and object type hsdo_AdministrativeArea.<br/>81 occurrences with subject type prov_Activity and object type hsdo_Audience.<br/>157 occurrences with subject type prov_Activity and object type hsdo_CategoryCode.<br/>87 occurrences with subject type prov_Activity and object type hsdo_Service.<br/>174 occurrences with subject type prov_Activity and object type prov_Entity.<br/>87 occurrences with subject type prov_Activity and object type hsdo_TextObject.<br/>609 occurrences with subject type prov_Activity and object type hsdo_OpeningHoursSpecification.<br/>87 occurrences with subject type prov_Activity and object type hsdo_Place.<br/>87 occurrences with subject type prov_Activity and object type hsdo_ContactPoint.<br/>87 occurrences with subject type prov_Activity and object type hsdo_Organization.<br/>39 occurrences with subject type prov_Activity and object type hsdo_AdministrativeArea.<br/>87 occurrences with subject type hsdo_Service and object type prov_Collection.<br/>174 occurrences with subject type prov_Entity and object type prov_Collection.<br/>87 occurrences with subject type hsdo_TextObject and object type prov_Collection.<br/>609 occurrences with subject type hsdo_OpeningHoursSpecification and object type prov_Collection.<br/>87 occurrences with subject type hsdo_Place and object type prov_Collection.<br/>87 occurrences with subject type hsdo_ContactPoint and object type prov_Collection.<br/>87 occurrences with subject type hsdo_Organization and object type prov_Collection.<br/>87 occurrences with subject type hsdo_WebPage and object type prov_Collection.<br/>87 occurrences with subject type hsdo_WebPage and object type hsdo_Service.<br/>174 occurrences with subject type hsdo_WebPage and object type prov_Entity.<br/>87 occurrences with subject type hsdo_WebPage and object type hsdo_TextObject.<br/>609 occurrences with subject type hsdo_WebPage and object type hsdo_OpeningHoursSpecification.<br/>87 occurrences with subject type hsdo_WebPage and object type hsdo_Place.<br/>87 occurrences with subject type hsdo_WebPage and object type hsdo_ContactPoint.<br/>87 occurrences with subject type hsdo_WebPage and object type hsdo_Organization.|
| [prov_wasDerivedFrom](prov_wasDerivedFrom.md) | No slot (predicate) description specified<br/>162 occurrences with subject type hsdo_Audience and object type prov_Entity.<br/>314 occurrences with subject type hsdo_CategoryCode and object type prov_Entity.<br/>174 occurrences with subject type hsdo_Service and object type prov_Entity.<br/>348 occurrences with subject type prov_Entity and object type prov_Entity.<br/>174 occurrences with subject type hsdo_TextObject and object type prov_Entity.<br/>1218 occurrences with subject type hsdo_OpeningHoursSpecification and object type prov_Entity.<br/>174 occurrences with subject type hsdo_Place and object type prov_Entity.<br/>174 occurrences with subject type hsdo_ContactPoint and object type prov_Entity.<br/>174 occurrences with subject type hsdo_Organization and object type prov_Entity.<br/>78 occurrences with subject type hsdo_AdministrativeArea and object type prov_Entity.|
| [prov_wasGeneratedBy](prov_wasGeneratedBy.md) | No slot (predicate) description specified<br/>81 occurrences with subject type hsdo_Audience and object type prov_Activity.<br/>157 occurrences with subject type hsdo_CategoryCode and object type prov_Activity.<br/>87 occurrences with subject type hsdo_Service and object type prov_Activity.<br/>174 occurrences with subject type prov_Entity and object type prov_Activity.<br/>87 occurrences with subject type hsdo_TextObject and object type prov_Activity.<br/>609 occurrences with subject type hsdo_OpeningHoursSpecification and object type prov_Activity.<br/>87 occurrences with subject type hsdo_Place and object type prov_Activity.<br/>87 occurrences with subject type hsdo_ContactPoint and object type prov_Activity.<br/>87 occurrences with subject type hsdo_Organization and object type prov_Activity.<br/>39 occurrences with subject type hsdo_AdministrativeArea and object type prov_Activity.|
| [prov_wasInfluencedBy](prov_wasInfluencedBy.md) | No slot (predicate) description specified<br/>162 occurrences with subject type hsdo_Audience and object type prov_Entity.<br/>243 occurrences with subject type hsdo_Audience and object type uri.<br/>81 occurrences with subject type hsdo_Audience and object type prov_Activity.<br/>314 occurrences with subject type hsdo_CategoryCode and object type prov_Entity.<br/>471 occurrences with subject type hsdo_CategoryCode and object type uri.<br/>157 occurrences with subject type hsdo_CategoryCode and object type prov_Activity.<br/>87 occurrences with subject type prov_Collection and object type hsdo_Service.<br/>174 occurrences with subject type prov_Collection and object type prov_Entity.<br/>87 occurrences with subject type prov_Collection and object type hsdo_TextObject.<br/>609 occurrences with subject type prov_Collection and object type hsdo_OpeningHoursSpecification.<br/>87 occurrences with subject type prov_Collection and object type hsdo_Place.<br/>87 occurrences with subject type prov_Collection and object type hsdo_ContactPoint.<br/>87 occurrences with subject type prov_Collection and object type hsdo_Organization.<br/>87 occurrences with subject type prov_Collection and object type hsdo_WebPage.<br/>174 occurrences with subject type hsdo_Service and object type prov_Entity.<br/>87 occurrences with subject type hsdo_Service and object type prov_Activity.<br/>87 occurrences with subject type hsdo_Service and object type hsdo_WebPage.<br/>348 occurrences with subject type prov_Entity and object type prov_Entity.<br/>174 occurrences with subject type prov_Entity and object type prov_Activity.<br/>174 occurrences with subject type prov_Entity and object type hsdo_WebPage.<br/>174 occurrences with subject type hsdo_TextObject and object type prov_Entity.<br/>87 occurrences with subject type hsdo_TextObject and object type prov_Activity.<br/>87 occurrences with subject type hsdo_TextObject and object type hsdo_WebPage.<br/>1218 occurrences with subject type hsdo_OpeningHoursSpecification and object type prov_Entity.<br/>609 occurrences with subject type hsdo_OpeningHoursSpecification and object type prov_Activity.<br/>609 occurrences with subject type hsdo_OpeningHoursSpecification and object type hsdo_WebPage.<br/>174 occurrences with subject type hsdo_Place and object type prov_Entity.<br/>87 occurrences with subject type hsdo_Place and object type prov_Activity.<br/>87 occurrences with subject type hsdo_Place and object type hsdo_WebPage.<br/>174 occurrences with subject type hsdo_ContactPoint and object type prov_Entity.<br/>87 occurrences with subject type hsdo_ContactPoint and object type prov_Activity.<br/>87 occurrences with subject type hsdo_ContactPoint and object type hsdo_WebPage.<br/>174 occurrences with subject type hsdo_Organization and object type prov_Entity.<br/>87 occurrences with subject type hsdo_Organization and object type prov_Activity.<br/>87 occurrences with subject type hsdo_Organization and object type hsdo_WebPage.<br/>78 occurrences with subject type hsdo_AdministrativeArea and object type prov_Entity.<br/>117 occurrences with subject type hsdo_AdministrativeArea and object type uri.<br/>39 occurrences with subject type hsdo_AdministrativeArea and object type prov_Activity.|






## Types

| Type | Description |
| --- | --- |
| [Boolean](Boolean.md) | A binary (true or false) value |
| [Curie](Curie.md) | a compact URI |
| [Date](Date.md) | a date (year, month and day) in an idealized calendar |
| [DateOrDatetime](DateOrDatetime.md) | Either a date or a datetime |
| [Datetime](Datetime.md) | The combination of a date and time |
| [Decimal](Decimal.md) | A real number with arbitrary precision that conforms to the xsd:decimal speci... |
| [Double](Double.md) | A real number that conforms to the xsd:double specification |
| [Float](Float.md) | A real number that conforms to the xsd:float specification |
| [Integer](Integer.md) | An integer |
| [Jsonpath](Jsonpath.md) | A string encoding a JSON Path |
| [Jsonpointer](Jsonpointer.md) | A string encoding a JSON Pointer |
| [Ncname](Ncname.md) | Prefix part of CURIE |
| [Nodeidentifier](Nodeidentifier.md) | A URI, CURIE or BNODE that represents a node in a model |
| [Objectidentifier](Objectidentifier.md) | A URI or CURIE that represents an object in the model |
| [Sparqlpath](Sparqlpath.md) | A string encoding a SPARQL Property Path |
| [String](String.md) | A character string |
| [Time](Time.md) | A time object represents a (local) time of day, independent of any particular... |
| [Uri](Uri.md) | a complete URI |
| [Uriorcurie](Uriorcurie.md) | a URI or a CURIE |



