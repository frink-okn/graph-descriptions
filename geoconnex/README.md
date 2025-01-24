# No schema name specified

No schema description specified



## Schema Diagram

```mermaid
erDiagram
HsdoBreadcrumbList {

}
HsdoDate {

}
GeoWktLiteral {

}
HsdoEntryPoint {
    string hsdo_urlTemplate  
}
HsdoImageObject {
    integer hsdo_width  
    uri hsdo_url  
    integer hsdo_height  
    string hsdo_caption  
}
HsdoListItem {
    string hsdo_nextItem  
    string hsdo_name  
    string hsdo_item  
    integer hsdo_position  
    string hsdo_previousItem  
}
HsdoNewsArticle {
    uri hsdo_image  
    string hsdo_image  
    string hsdo_description  
    string hsdo_headline  
}
HsdoOrganization {
    uri hsdo_image  
    string hsdo_image  
    string hsdo_name  
    uri hsdo_url  
    uri hsdo_sameAs  
}
HsdoPerson {
    string hsdo_name  
}
HsdoSearchAction {
    string hsdo_query_input  
}
HsdoWebPage {
    string hsdo_about  
    uri hsdo_provider  
    string hsdo_provider  
    string hsdo_name  
    string hsdo_description  
    string hsdo_inLanguage  
    uri hsdo_url  
}
HsdoWebSite {
    string hsdo_name  
    string hsdo_description  
    string hsdo_inLanguage  
    uri hsdo_url  
}
HsdoError {
    string hsdo_description  
}
HttpGeosciencesCaDefGroundwaterCaGWAquiferSystem {
    string rdfs_label  
    uri http___wwwopengeospatialorg_standards_geosparql_sfIntersects  
    uri hsdo_subjectOf  
}
HttpGeosciencesCaDefGroundwaterCaGWAquiferUnit {

}
HttpGeosciencesCaDefGroundwaterCaGWHydrogeoUnit {
    string rdfs_label  
    uri http___wwwopengeospatialorg_standards_geosparql_sfIntersects  
    uri hsdo_image  
    string hsdo_image  
    string hsdo_name  
    string hsdo_description  
    uri http___geosciencesCa_def_groundwaterCagwAquiferSystem  
}
HttpGeosciencesCaDefGroundwaterCaGWWell {
    string rdfs_label  
    uri hsdo_subjectOf  
}
HttpGeosciencesCaDefHydraulicCaHYCatchment {

}
HttpRdfsorgNsVoidCaDataset {
    string dc_description  
    uri dct_conformsTo  
    string dct_conformsTo  
    uri schema_provider  
    schema_url schema_provider  
    uri https___geoconnexCa_id_connectedTo  
    string rdfs_label  
    string dct_format  
    uri hsdo_provider  
    string hsdo_provider  
    uri hsdo_subjectOf  
}
HttpRdfsorgNsVoidCaLinkSet {

}
HttpRdfsorgNsVoidCaLinkset {

}
HttpWwwopengeospatialorgStandardsWaterml2HyFeaturesHYHydroLocation {
    uri schema_geo  
    string schema_name  
    uri http___wwwopengeospatialorg_standards_waterml2_hy_features_flowpath  
    string schema_identifier  
    uri schema_geoWithin  
    string schema_geoWithin  
    string hyf_HY_HydroLocationType  
    uri schema_subjectOf  
    uri http___wwwopengeospatialorg_standards_waterml2_hy_features_HY_HydroLocationType  
}
HttpsOpengeospatialgithubioSELFIEDataNodeConnectionLinkSet {

}
HttpsOpengeospatialgithubioSELFIEDataNodeFeatureCatalog {

}
HttpsOpengeospatialgithubioSELFIEDataNodeFeatureLinkSet {

}
HttpsWwwopengisnetDefAppschemaHyFeaturesHyfHYCatchment {
    string hsdo_description  
    string hsdo_name  
}
HttpsWwwopengisnetDefAppschemaHyFeaturesHyfHYCatchmentDivide {

}
HttpsWwwopengisnetDefAppschemaHyFeaturesHyfHYHydrographicNetwork {

}
HttpsWwwopengisnetDefAppschemaHyFeaturesHyfHYHydrometricFeature {

}
HttpsWwwopengisnetDefAppschemaHyFeaturesHyfHYHydrometricNetwork {
    string hsdo_description  
    string hsdo_name  
}
HttpsWwwopengisnetDefHyFeaturesOntologyHyfHYCatchment {

}
HttpsWwwopengisnetDefHyFeaturesOntologyHyfHYCatchmentAggregate {

}
HttpsWwwopengisnetDefHyFeaturesOntologyHyfHYDendriticCatchment {

}
HttpsWwwopengisnetDefHyFeaturesOntologyHyfHYFlowpath {

}
HttpsWwwopengisnetDefHyFeaturesOntologyHyfHYHydroNetwork {

}
HttpsWwwopengisnetDefHyFeaturesOntologyHyfHYHydroNexus {

}
HttpsWwwopengisnetDefHyFeaturesOntologyHyfHYHydroloLocation {

}
HttpsWwwopengisnetDefHyFeaturesOntologyHyfHYHydrometricFeature {

}
HttpsWwwopengisnetDefHyFeaturesOntologyHyfHYHydrometricNetwork {

}
HyfHYFlowPath {

}
HyfHYWaterBody {

}
HyfHYFlowPath {

}
HyfHYHydroLocation {
    string schema_name  
    uri schema_geo  
    uri hyf_referencedPosition  
    uri schema_provider  
    schema_url schema_provider  
    string hyf__HY_HydroLocationType  
    string schema_description  
    string schema_identifier  
    uri schema_geoWithin  
    string schema_geoWithin  
    uri hyf__referencedPosition  
    string hyf_HY_HydroLocationType  
    uri schema_subjectOf  
    string hyf__HydroLocationType  
}
HyfHYHydrometricFeature {

}
LocTypeAtmosphere {

}
LocTypeCanal {

}
LocTypeCoastal {

}
LocTypeDitch {

}
LocTypeDiversion {

}
LocTypeEstuary {

}
LocTypeLake {

}
LocTypeLand {

}
LocTypeOcean {

}
LocTypeOutfall {

}
LocTypeShore {

}
LocTypeSinkhole {

}
LocTypeSpring {

}
LocTypeStream {

}
LocTypeSubsurface {

}
LocTypeWell {

}
LocTypeWetland {

}
OwlThing {

}
RdfsResource {
    uri http___geosciencesCa_def_hydraulicCacontains  
    string dc_description  
    string rdfs_label  
    uri rdf_type  
    uri http___rdfsorg_ns_voidCatarget  
    string dct_format  
    uri http___wwwopengeospatialorg_standards_geosparql_sfIntersects  
    uri https___wwwopengisnet_def_hy_features_ontology_hyf_upperCatchment  
    uri https___wwwopengisnet_def_hy_features_ontology_hyf_contributingCatchment  
    uri hsdo_subjectOf  
    uri http___rdfsorg_ns_voidCaproperty  
    uri dct_conformsTo  
    string dct_conformsTo  
    uri schema_provider  
    schema_url schema_provider  
    string hsdo_name  
    uri hsdo_provider  
    string hsdo_provider  
}
SchemaCreativeWork {
    string schema_name  
    string schema_identifier  
}
SchemaDataDownload {
    string schema_encodingFormat  
    string schema_name  
    uri dct_conformsTo  
    string dct_conformsTo  
    string schema_contentUrl  
}
SchemaDataset {
    string schema_name  
    uri schema_provider  
    schema_url schema_provider  
    string schema_temporalCoverage  
    string schema_url  
    string schema_description  
}
SchemaGeoCoordinates {
    integer schema_longitude  
    double schema_longitude  
    integer schema_latitude  
    double schema_latitude  
}
SchemaGeoShape {
    string schema_polygon  
    string schema_line  
}
SchemaGovernmentOrganization {
    string schema_name  
    string schema_url  
}
SchemaOrganization {
    string schema_name  
    string schema_identifier  
    string schema_url  
}
SchemaPlace {
    uri schema_geo  
    string schema_name  
    string schema_url  
    uri badwdt_P403  
    integer badwdt_P2053  
    double badwdt_P2053  
    uri schema_about  
    uri sosa_hasFeatureOfInterest  
    string sosa_hasFeatureOfInterest  
    uri schema_subjectOf  
    uri http___wwwopengeospatialorg_standards_waterml2_hy_features_flowpath  
    string schema_description  
    string schema_geoIntersects  
    uri schema_geoWithin  
    string schema_geoWithin  
    uri schema_location  
    uri schema_supersededBy  
    uri badwdt_P885  
    string sosa_ObservationCollection  
    uri schema_provider  
    schema_url schema_provider  
    integer badwdt_P2043  
    string badwdt_P2043  
    double badwdt_P2043  
    uri schema_isBasedOn  
    uri hyf__containingCatchment  
}
SchemaPropertyValue {
    string schema_name  
    string schema_measurementTechnique  
    string schema_propertyID  
    string schema_url  
    string schema_description  
    uri schema_measurementMethod  
    string schema_unitText  
    string schema_PropertyID  
    string schema_value  
}
SfCaGeometryCollection {

}
SfCaLineString {

}
SfCaMultiPolygon {

}
SfCaPoint {
    uri geo_crs  
}
SfCaPolygon {

}

HsdoBreadcrumbList ||--|o HsdoListItem : "hsdo_itemListElement"
HsdoImageObject ||--|o HsdoWebPage : "hsdo_url"
HsdoListItem ||--|o HsdoWebPage : "hsdo_item"
HsdoNewsArticle ||--|o HsdoPerson : "hsdo_author"
HsdoNewsArticle ||--|o HsdoDate : "hsdo_datePublished"
HsdoNewsArticle ||--|o HsdoWebPage : "hsdo_mainEntityOfPage"
HsdoNewsArticle ||--|o HsdoImageObject : "hsdo_image"
HsdoNewsArticle ||--|o HsdoOrganization : "hsdo_publisher"
HsdoNewsArticle ||--|o HsdoDate : "hsdo_dateModified"
HsdoOrganization ||--|o HsdoImageObject : "hsdo_image"
HsdoOrganization ||--|o HsdoImageObject : "hsdo_logo"
HsdoOrganization ||--|o HsdoWebPage : "hsdo_url"
HsdoSearchAction ||--|o HsdoEntryPoint : "hsdo_target"
HsdoWebPage ||--|o HsdoBreadcrumbList : "hsdo_breadcrumb"
HsdoWebPage ||--|o HsdoDate : "hsdo_datePublished"
HsdoWebPage ||--|o HsdoWebSite : "hsdo_isPartOf"
HsdoWebPage ||--|o HsdoWebPage : "hsdo_url"
HsdoWebPage ||--|o HsdoDate : "hsdo_dateModified"
HsdoWebSite ||--|o HsdoSearchAction : "hsdo_potentialAction"
HsdoWebSite ||--|o HsdoOrganization : "hsdo_publisher"
HsdoWebSite ||--|o HsdoWebPage : "hsdo_url"
HttpGeosciencesCaDefGroundwaterCaGWAquiferSystem ||--|o HttpGeosciencesCaDefGroundwaterCaGWHydrogeoUnit : "owl_sameAs"
HttpGeosciencesCaDefGroundwaterCaGWAquiferSystem ||--|o HttpGeosciencesCaDefGroundwaterCaGWAquiferSystem : "owl_sameAs"
HttpGeosciencesCaDefGroundwaterCaGWAquiferSystem ||--|o RdfsResource : "owl_sameAs"
HttpGeosciencesCaDefGroundwaterCaGWAquiferSystem ||--|o HttpGeosciencesCaDefGroundwaterCaGWWell : "owl_sameAs"
HttpGeosciencesCaDefGroundwaterCaGWAquiferSystem ||--|o HttpGeosciencesCaDefGroundwaterCaGWAquiferSystem : "http___wwwopengeospatialorg_standards_geosparql_sfIntersects"
HttpGeosciencesCaDefGroundwaterCaGWAquiferSystem ||--|o RdfsResource : "http___wwwopengeospatialorg_standards_geosparql_sfIntersects"
HttpGeosciencesCaDefGroundwaterCaGWAquiferSystem ||--|o HttpGeosciencesCaDefGroundwaterCaGWHydrogeoUnit : "http___wwwopengeospatialorg_standards_geosparql_sfIntersects"
HttpGeosciencesCaDefGroundwaterCaGWAquiferSystem ||--|o HttpGeosciencesCaDefGroundwaterCaGWWell : "http___wwwopengeospatialorg_standards_geosparql_sfContains"
HttpGeosciencesCaDefGroundwaterCaGWAquiferSystem ||--|o RdfsResource : "hsdo_subjectOf"
HttpGeosciencesCaDefGroundwaterCaGWAquiferSystem ||--|o HttpRdfsorgNsVoidCaDataset : "hsdo_subjectOf"
HttpGeosciencesCaDefGroundwaterCaGWHydrogeoUnit ||--|o HttpGeosciencesCaDefGroundwaterCaGWHydrogeoUnit : "owl_sameAs"
HttpGeosciencesCaDefGroundwaterCaGWHydrogeoUnit ||--|o HttpGeosciencesCaDefGroundwaterCaGWAquiferSystem : "owl_sameAs"
HttpGeosciencesCaDefGroundwaterCaGWHydrogeoUnit ||--|o RdfsResource : "owl_sameAs"
HttpGeosciencesCaDefGroundwaterCaGWHydrogeoUnit ||--|o HttpGeosciencesCaDefGroundwaterCaGWWell : "owl_sameAs"
HttpGeosciencesCaDefGroundwaterCaGWHydrogeoUnit ||--|o HttpGeosciencesCaDefGroundwaterCaGWAquiferSystem : "http___wwwopengeospatialorg_standards_geosparql_sfIntersects"
HttpGeosciencesCaDefGroundwaterCaGWHydrogeoUnit ||--|o RdfsResource : "http___wwwopengeospatialorg_standards_geosparql_sfIntersects"
HttpGeosciencesCaDefGroundwaterCaGWHydrogeoUnit ||--|o HttpGeosciencesCaDefGroundwaterCaGWHydrogeoUnit : "http___wwwopengeospatialorg_standards_geosparql_sfIntersects"
HttpGeosciencesCaDefGroundwaterCaGWHydrogeoUnit ||--|o HsdoImageObject : "hsdo_image"
HttpGeosciencesCaDefGroundwaterCaGWWell ||--|o HttpGeosciencesCaDefGroundwaterCaGWAquiferSystem : "http___wwwopengeospatialorg_standards_geosparql_sfWithin"
HttpGeosciencesCaDefGroundwaterCaGWWell ||--|o RdfsResource : "http___wwwopengeospatialorg_standards_geosparql_sfWithin"
HttpGeosciencesCaDefGroundwaterCaGWWell ||--|o RdfsResource : "hsdo_subjectOf"
HttpGeosciencesCaDefGroundwaterCaGWWell ||--|o HttpRdfsorgNsVoidCaDataset : "hsdo_subjectOf"
HttpGeosciencesCaDefGroundwaterCaGWWell ||--|o HttpGeosciencesCaDefGroundwaterCaGWHydrogeoUnit : "owl_sameAs"
HttpGeosciencesCaDefGroundwaterCaGWWell ||--|o HttpGeosciencesCaDefGroundwaterCaGWAquiferSystem : "owl_sameAs"
HttpGeosciencesCaDefGroundwaterCaGWWell ||--|o RdfsResource : "owl_sameAs"
HttpGeosciencesCaDefGroundwaterCaGWWell ||--|o HttpGeosciencesCaDefGroundwaterCaGWWell : "owl_sameAs"
HttpRdfsorgNsVoidCaDataset ||--|o SchemaGovernmentOrganization : "schema_provider"
HttpRdfsorgNsVoidCaDataset ||--|o RdfsResource : "hsdo_subjectOf"
HttpRdfsorgNsVoidCaDataset ||--|o HttpRdfsorgNsVoidCaDataset : "hsdo_subjectOf"
HttpWwwopengeospatialorgStandardsWaterml2HyFeaturesHYHydroLocation ||--|o SfCaLineString : "geo_hasGeometry"
HttpWwwopengeospatialorgStandardsWaterml2HyFeaturesHYHydroLocation ||--|o SfCaPoint : "geo_hasGeometry"
HttpWwwopengeospatialorgStandardsWaterml2HyFeaturesHYHydroLocation ||--|o SfCaGeometryCollection : "geo_hasGeometry"
HttpWwwopengeospatialorgStandardsWaterml2HyFeaturesHYHydroLocation ||--|o SfCaMultiPolygon : "geo_hasGeometry"
HttpWwwopengeospatialorgStandardsWaterml2HyFeaturesHYHydroLocation ||--|o SfCaPolygon : "geo_hasGeometry"
HttpWwwopengeospatialorgStandardsWaterml2HyFeaturesHYHydroLocation ||--|o SchemaGeoShape : "schema_geo"
HttpWwwopengeospatialorgStandardsWaterml2HyFeaturesHYHydroLocation ||--|o SchemaGeoCoordinates : "schema_geo"
HttpWwwopengeospatialorgStandardsWaterml2HyFeaturesHYHydroLocation ||--|o SchemaPropertyValue : "schema_identifier"
HttpWwwopengeospatialorgStandardsWaterml2HyFeaturesHYHydroLocation ||--|o SchemaPlace : "schema_geoWithin"
HttpWwwopengeospatialorgStandardsWaterml2HyFeaturesHYHydroLocation ||--|o SchemaDataset : "schema_subjectOf"
HttpsWwwopengisnetDefAppschemaHyFeaturesHyfHYCatchment ||--|o HttpsWwwopengisnetDefAppschemaHyFeaturesHyfHYHydrometricNetwork : "https___wwwopengisnet_def_appschema_hy_features_hyf_catchmentRealization"
HttpsWwwopengisnetDefAppschemaHyFeaturesHyfHYCatchment ||--|o HttpsWwwopengisnetDefAppschemaHyFeaturesHyfHYCatchmentDivide : "https___wwwopengisnet_def_appschema_hy_features_hyf_catchmentRealization"
HttpsWwwopengisnetDefAppschemaHyFeaturesHyfHYCatchment ||--|o HttpsWwwopengisnetDefAppschemaHyFeaturesHyfHYHydrographicNetwork : "https___wwwopengisnet_def_appschema_hy_features_hyf_catchmentRealization"
HttpsWwwopengisnetDefAppschemaHyFeaturesHyfHYHydrometricNetwork ||--|o HttpsWwwopengisnetDefAppschemaHyFeaturesHyfHYHydrometricFeature : "https___wwwopengisnet_def_appschema_hy_features_hyf_networkStation"
HttpsWwwopengisnetDefAppschemaHyFeaturesHyfHYHydrometricNetwork ||--|o HttpsWwwopengisnetDefAppschemaHyFeaturesHyfHYCatchment : "https___wwwopengisnet_def_appschema_hy_features_hyf_realizedCatchment"
HyfHYHydroLocation ||--|o SfCaLineString : "geo_hasGeometry"
HyfHYHydroLocation ||--|o SfCaPoint : "geo_hasGeometry"
HyfHYHydroLocation ||--|o SfCaGeometryCollection : "geo_hasGeometry"
HyfHYHydroLocation ||--|o SfCaMultiPolygon : "geo_hasGeometry"
HyfHYHydroLocation ||--|o SfCaPolygon : "geo_hasGeometry"
HyfHYHydroLocation ||--|o SchemaGeoShape : "schema_geo"
HyfHYHydroLocation ||--|o SchemaGeoCoordinates : "schema_geo"
HyfHYHydroLocation ||--|o SchemaGovernmentOrganization : "schema_provider"
HyfHYHydroLocation ||--|o SchemaPropertyValue : "schema_identifier"
HyfHYHydroLocation ||--|o SchemaPlace : "schema_geoWithin"
HyfHYHydroLocation ||--|o SchemaDataset : "schema_subjectOf"
HyfHYHydroLocation ||--|o SfCaPoint : "gsp_hasGeometry"
HyfHYHydroLocation ||--|o SfCaPolygon : "gsp_hasGeometry"
HyfHYHydroLocation ||--|o SfCaMultiPolygon : "gsp_hasGeometry"
RdfsResource ||--|o RdfsResource : "https___wwwopengisnet_def_hy_features_ontology_hyf_inflow"
RdfsResource ||--|o HttpGeosciencesCaDefGroundwaterCaGWHydrogeoUnit : "owl_sameAs"
RdfsResource ||--|o HttpGeosciencesCaDefGroundwaterCaGWAquiferSystem : "owl_sameAs"
RdfsResource ||--|o RdfsResource : "owl_sameAs"
RdfsResource ||--|o HttpGeosciencesCaDefGroundwaterCaGWWell : "owl_sameAs"
RdfsResource ||--|o RdfsResource : "https___wwwopengisnet_def_hy_features_ontology_hyf_realizedCatchment"
RdfsResource ||--|o HttpGeosciencesCaDefGroundwaterCaGWWell : "http___wwwopengeospatialorg_standards_geosparql_sfContains"
RdfsResource ||--|o RdfsResource : "https___wwwopengisnet_def_hy_features_ontology_hyf_networkStation"
RdfsResource ||--|o RdfsResource : "https___wwwopengisnet_def_hy_features_ontology_hyf_realizedNexus"
RdfsResource ||--|o HttpRdfsorgNsVoidCaDataset : "http___rdfsorg_ns_voidCatarget"
RdfsResource ||--|o RdfsResource : "https___wwwopengisnet_def_hy_features_ontology_hyf_exorheicDrainage"
RdfsResource ||--|o RdfsResource : "rdfs_subClassOf"
RdfsResource ||--|o HttpGeosciencesCaDefGroundwaterCaGWAquiferSystem : "http___wwwopengeospatialorg_standards_geosparql_sfIntersects"
RdfsResource ||--|o RdfsResource : "http___wwwopengeospatialorg_standards_geosparql_sfIntersects"
RdfsResource ||--|o HttpGeosciencesCaDefGroundwaterCaGWHydrogeoUnit : "http___wwwopengeospatialorg_standards_geosparql_sfIntersects"
RdfsResource ||--|o RdfsResource : "https___wwwopengisnet_def_hy_features_ontology_hyf_upperCatchment"
RdfsResource ||--|o RdfsResource : "https___wwwopengisnet_def_hy_features_ontology_hyf_nexusRealization"
RdfsResource ||--|o RdfsResource : "https___wwwopengisnet_def_hy_features_ontology_hyf_contributingCatchment"
RdfsResource ||--|o RdfsResource : "https___wwwopengisnet_def_hy_features_ontology_hyf_outflow"
RdfsResource ||--|o RdfsResource : "hsdo_subjectOf"
RdfsResource ||--|o HttpRdfsorgNsVoidCaDataset : "hsdo_subjectOf"
RdfsResource ||--|o RdfsResource : "https___wwwopengisnet_def_hy_features_ontology_hyf_receivingCatchment"
RdfsResource ||--|o SchemaGovernmentOrganization : "schema_provider"
RdfsResource ||--|o RdfsResource : "owl_equivalentClass"
RdfsResource ||--|o RdfsResource : "https___wwwopengisnet_def_hy_features_ontology_hyf_catchmentRealization"
RdfsResource ||--|o RdfsResource : "https___wwwopengisnet_def_hy_features_ontology_hyf_encompassingCatchment"
RdfsResource ||--|o RdfsResource : "https___wwwopengisnet_def_hy_features_ontology_hyf_lowerCatchment"
RdfsResource ||--|o RdfsResource : "https___wwwopengisnet_def_hy_features_ontology_hyf_hydrometricNetwork"
SchemaCreativeWork ||--|o SchemaPropertyValue : "schema_identifier"
SchemaDataset ||--|o SchemaPropertyValue : "schema_variableMeasured"
SchemaDataset ||--|o SchemaGovernmentOrganization : "schema_provider"
SchemaDataset ||--|o SchemaDataDownload : "schema_distribution"
SchemaOrganization ||--|o SchemaPropertyValue : "schema_identifier"
SchemaPlace ||--|o SchemaGeoShape : "schema_geo"
SchemaPlace ||--|o SchemaGeoCoordinates : "schema_geo"
SchemaPlace ||--|o SchemaPlace : "schema_sameAs"
SchemaPlace ||--|o SfCaLineString : "geo_hasGeometry"
SchemaPlace ||--|o SfCaPoint : "geo_hasGeometry"
SchemaPlace ||--|o SfCaGeometryCollection : "geo_hasGeometry"
SchemaPlace ||--|o SfCaMultiPolygon : "geo_hasGeometry"
SchemaPlace ||--|o SfCaPolygon : "geo_hasGeometry"
SchemaPlace ||--|o SchemaPlace : "hyf_encompassingCatchment"
SchemaPlace ||--|o SchemaDataset : "schema_subjectOf"
SchemaPlace ||--|o SchemaPlace : "hyf_downstreamWaterbody"
SchemaPlace ||--|o SchemaPlace : "schema_geoWithin"
SchemaPlace ||--|o SchemaPlace : "schema_supersededBy"
SchemaPlace ||--|o SfCaPoint : "gsp_hasGeometry"
SchemaPlace ||--|o SfCaPolygon : "gsp_hasGeometry"
SchemaPlace ||--|o SfCaMultiPolygon : "gsp_hasGeometry"
SchemaPlace ||--|o SchemaGovernmentOrganization : "schema_provider"
SchemaPlace ||--|o SchemaPlace : "hyf__containingCatchment"
SfCaGeometryCollection ||--|o GeoWktLiteral : "geo_asWKT"
SfCaLineString ||--|o GeoWktLiteral : "geo_asWKT"
SfCaMultiPolygon ||--|o GeoWktLiteral : "geo_asWKT"
SfCaMultiPolygon ||--|o GeoWktLiteral : "gsp_asWKT"
SfCaPoint ||--|o GeoWktLiteral : "geo_asWKT"
SfCaPoint ||--|o GeoWktLiteral : "gsp_asWKT"
SfCaPoint ||--|o GeoWktLiteral : "geosparql_asWKT"
SfCaPolygon ||--|o GeoWktLiteral : "geo_asWKT"
SfCaPolygon ||--|o GeoWktLiteral : "gsp_asWKT"

```


## IRI prefixes

* badwdt: https://www.wikidata.org/wiki/Property:
* dc: http://purl.org/dc/elements/1.1/
* dct: http://purl.org/dc/terms/
* geo: http://www.opengis.net/ont/geosparql#
* hsdo: http://schema.org/
* hyf: https://www.opengis.net/def/schema/hy_features/hyf
* linkml: https://w3id.org/linkml/
* owl: http://www.w3.org/2002/07/owl#
* rdf: http://www.w3.org/1999/02/22-rdf-syntax-ns#
* rdfs: http://www.w3.org/2000/01/rdf-schema#
* schema: https://schema.org/
* sf: http://www.opengis.net/ont/sf
* sosa: http://www.w3.org/ns/sosa/



## Classes

| Class | Description |
| --- | --- |
| [GeoWktLiteral](classes/GeoWktLiteral.md) | None<br/>| 
| [HsdoBreadcrumbList](classes/HsdoBreadcrumbList.md) | A BreadcrumbList is an ItemList consisting of a chain of linked Web pages, typically described using at least their URL and their name, and typically ending with the current page.\n\nThe [[position]] property is used to reconstruct the order of the items in a BreadcrumbList. The convention is that a breadcrumb list has an [[itemListOrder]] of [[ItemListOrderAscending]] (lower values listed first), and that the first items in this list correspond to the "top" or beginning of the breadcrumb trail, e.g. with a site or section homepage. The specific values of 'position' are not assigned meaning for a BreadcrumbList, but they should be integers, e.g. beginning with '1' for the first item in the list.      <br/>Class with 3 occurrences.| 
| [HsdoDate](classes/HsdoDate.md) | None<br/>| 
| [HsdoEntryPoint](classes/HsdoEntryPoint.md) | An entry point, within some Web-based protocol.<br/>Class with 1 occurrences.| 
| [HsdoError](classes/HsdoError.md) | For failed actions, more information on the cause of the failure.<br/>Class with 17 occurrences.| 
| [HsdoImageObject](classes/HsdoImageObject.md) | An image file.<br/>Class with 5 occurrences.| 
| [HsdoListItem](classes/HsdoListItem.md) | An list item, e.g. a step in a checklist or how-to description.<br/>Class with 3 occurrences.| 
| [HsdoNewsArticle](classes/HsdoNewsArticle.md) | A NewsArticle is an article whose content reports news, or provides background context and supporting materials for understanding the news. A more detailed overview of [schema.org News markup](/docs/news.html) is also available.<br/>Class with 2 occurrences.| 
| [HsdoOrganization](classes/HsdoOrganization.md) | An organization such as a school, NGO, corporation, club, etc.<br/>Class with 3 occurrences.| 
| [HsdoPerson](classes/HsdoPerson.md) | A person (alive, dead, undead, or fictional).<br/>Class with 2 occurrences.| 
| [HsdoSearchAction](classes/HsdoSearchAction.md) | The act of searching for an object.\n\nRelated actions:\n\n* [[FindAction]]: SearchAction generally leads to a FindAction, but not necessarily.<br/>Class with 1 occurrences.| 
| [HsdoWebPage](classes/HsdoWebPage.md) | A web page. Every web page is implicitly assumed to be declared to be of type WebPage, so the various properties about that webpage, such as <code>breadcrumb</code> may be used. We recommend explicit declaration if these properties are specified, but if they are found outside of an itemscope, they will be assumed to be about the page.<br/>Class with 48678 occurrences.| 
| [HsdoWebSite](classes/HsdoWebSite.md) | A WebSite is a set of related web pages and other items typically served from a single web domain and accessible via URLs.<br/>Class with 1 occurrences.| 
| [HttpGeosciences.caDefGroundwater#GWAquiferSystem](classes/HttpGeosciences.caDefGroundwater#GWAquiferSystem.md) | No class (type) description specified<br/>Class with 2 occurrences.| 
| [HttpGeosciences.caDefGroundwater#GWAquiferUnit](classes/HttpGeosciences.caDefGroundwater#GWAquiferUnit.md) | No class (type) description specified<br/>Class with 2 occurrences.| 
| [HttpGeosciences.caDefGroundwater#GWHydrogeoUnit](classes/HttpGeosciences.caDefGroundwater#GWHydrogeoUnit.md) | No class (type) description specified<br/>Class with 3 occurrences.| 
| [HttpGeosciences.caDefGroundwater#GWWell](classes/HttpGeosciences.caDefGroundwater#GWWell.md) | No class (type) description specified<br/>Class with 5 occurrences.| 
| [HttpGeosciences.caDefHydraulic#HYCatchment](classes/HttpGeosciences.caDefHydraulic#HYCatchment.md) | No class (type) description specified<br/>Class with 1 occurrences.| 
| [HttpRdfs.orgNsVoid#Dataset](classes/HttpRdfs.orgNsVoid#Dataset.md) | No class (type) description specified<br/>Class with 2 occurrences.| 
| [HttpRdfs.orgNsVoid#Linkset](classes/HttpRdfs.orgNsVoid#Linkset.md) | No class (type) description specified<br/>Class with 1 occurrences.| 
| [HttpRdfs.orgNsVoid#LinkSet](classes/HttpRdfs.orgNsVoid#LinkSet.md) | No class (type) description specified<br/>Class with 1 occurrences.| 
| [HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation](classes/HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation.md) | No class (type) description specified<br/>Class with 1620787 occurrences.| 
| [HttpsOpengeospatial.github.ioSELFIEDataNodeConnectionLinkSet](classes/HttpsOpengeospatial.github.ioSELFIEDataNodeConnectionLinkSet.md) | No class (type) description specified<br/>Class with 1 occurrences.| 
| [HttpsOpengeospatial.github.ioSELFIEDataNodeFeatureCatalog](classes/HttpsOpengeospatial.github.ioSELFIEDataNodeFeatureCatalog.md) | No class (type) description specified<br/>Class with 1 occurrences.| 
| [HttpsOpengeospatial.github.ioSELFIEDataNodeFeatureLinkSet](classes/HttpsOpengeospatial.github.ioSELFIEDataNodeFeatureLinkSet.md) | No class (type) description specified<br/>Class with 1 occurrences.| 
| [HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYCatchment](classes/HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYCatchment.md) | No class (type) description specified<br/>Class with 1 occurrences.| 
| [HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYCatchmentDivide](classes/HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYCatchmentDivide.md) | No class (type) description specified<br/>Class with 1 occurrences.| 
| [HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYHydrographicNetwork](classes/HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYHydrographicNetwork.md) | No class (type) description specified<br/>Class with 1 occurrences.| 
| [HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYHydrometricFeature](classes/HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYHydrometricFeature.md) | No class (type) description specified<br/>Class with 15 occurrences.| 
| [HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYHydrometricNetwork](classes/HttpsWww.opengis.netDefAppschemaHyFeaturesHyfHYHydrometricNetwork.md) | No class (type) description specified<br/>Class with 1 occurrences.| 
| [HttpsWww.opengis.netDefHyFeaturesOntologyHyfHYCatchment](classes/HttpsWww.opengis.netDefHyFeaturesOntologyHyfHYCatchment.md) | No class (type) description specified<br/>Class with 382 occurrences.| 
| [HttpsWww.opengis.netDefHyFeaturesOntologyHyfHYCatchmentAggregate](classes/HttpsWww.opengis.netDefHyFeaturesOntologyHyfHYCatchmentAggregate.md) | No class (type) description specified<br/>Class with 8 occurrences.| 
| [HttpsWww.opengis.netDefHyFeaturesOntologyHyfHYDendriticCatchment](classes/HttpsWww.opengis.netDefHyFeaturesOntologyHyfHYDendriticCatchment.md) | No class (type) description specified<br/>Class with 382 occurrences.| 
| [HttpsWww.opengis.netDefHyFeaturesOntologyHyfHYFlowpath](classes/HttpsWww.opengis.netDefHyFeaturesOntologyHyfHYFlowpath.md) | No class (type) description specified<br/>Class with 187 occurrences.| 
| [HttpsWww.opengis.netDefHyFeaturesOntologyHyfHYHydroloLocation](classes/HttpsWww.opengis.netDefHyFeaturesOntologyHyfHYHydroloLocation.md) | No class (type) description specified<br/>Class with 187 occurrences.| 
| [HttpsWww.opengis.netDefHyFeaturesOntologyHyfHYHydrometricFeature](classes/HttpsWww.opengis.netDefHyFeaturesOntologyHyfHYHydrometricFeature.md) | No class (type) description specified<br/>Class with 37 occurrences.| 
| [HttpsWww.opengis.netDefHyFeaturesOntologyHyfHYHydrometricNetwork](classes/HttpsWww.opengis.netDefHyFeaturesOntologyHyfHYHydrometricNetwork.md) | No class (type) description specified<br/>Class with 415 occurrences.| 
| [HttpsWww.opengis.netDefHyFeaturesOntologyHyfHYHydroNetwork](classes/HttpsWww.opengis.netDefHyFeaturesOntologyHyfHYHydroNetwork.md) | No class (type) description specified<br/>Class with 187 occurrences.| 
| [HttpsWww.opengis.netDefHyFeaturesOntologyHyfHYHydroNexus](classes/HttpsWww.opengis.netDefHyFeaturesOntologyHyfHYHydroNexus.md) | No class (type) description specified<br/>Class with 99 occurrences.| 
| [HyfHYFlowPath](classes/HyfHYFlowPath.md) | No class (type) description specified<br/>Class with 33851 occurrences.| 
| [HyfHYHydroLocation](classes/HyfHYHydroLocation.md) | No class (type) description specified<br/>Class with 201357 occurrences.| 
| [HyfHYHydrometricFeature](classes/HyfHYHydrometricFeature.md) | No class (type) description specified<br/>Class with 201357 occurrences.| 
| [HyfHYFlowPath](classes/HyfHYFlowPath.md) | No class (type) description specified<br/>Class with 34082 occurrences.| 
| [HyfHYWaterBody](classes/HyfHYWaterBody.md) | No class (type) description specified<br/>Class with 34082 occurrences.| 
| [LocTypeAtmosphere](classes/LocTypeAtmosphere.md) | No class (type) description specified<br/>Class with 844 occurrences.| 
| [LocTypeCanal](classes/LocTypeCanal.md) | No class (type) description specified<br/>Class with 176 occurrences.| 
| [LocTypeCoastal](classes/LocTypeCoastal.md) | No class (type) description specified<br/>Class with 25 occurrences.| 
| [LocTypeDitch](classes/LocTypeDitch.md) | No class (type) description specified<br/>Class with 52 occurrences.| 
| [LocTypeDiversion](classes/LocTypeDiversion.md) | No class (type) description specified<br/>Class with 15 occurrences.| 
| [LocTypeEstuary](classes/LocTypeEstuary.md) | No class (type) description specified<br/>Class with 154 occurrences.| 
| [LocTypeLake](classes/LocTypeLake.md) | No class (type) description specified<br/>Class with 1 occurrences.| 
| [LocTypeLand](classes/LocTypeLand.md) | No class (type) description specified<br/>Class with 5 occurrences.| 
| [LocTypeOcean](classes/LocTypeOcean.md) | No class (type) description specified<br/>Class with 5 occurrences.| 
| [LocTypeOutfall](classes/LocTypeOutfall.md) | No class (type) description specified<br/>Class with 2 occurrences.| 
| [LocTypeShore](classes/LocTypeShore.md) | No class (type) description specified<br/>Class with 1 occurrences.| 
| [LocTypeSinkhole](classes/LocTypeSinkhole.md) | No class (type) description specified<br/>Class with 1 occurrences.| 
| [LocTypeSpring](classes/LocTypeSpring.md) | No class (type) description specified<br/>Class with 74 occurrences.| 
| [LocTypeStream](classes/LocTypeStream.md) | No class (type) description specified<br/>Class with 9098 occurrences.| 
| [LocTypeSubsurface](classes/LocTypeSubsurface.md) | No class (type) description specified<br/>Class with 1 occurrences.| 
| [LocTypeWell](classes/LocTypeWell.md) | No class (type) description specified<br/>Class with 2987 occurrences.| 
| [LocTypeWetland](classes/LocTypeWetland.md) | No class (type) description specified<br/>Class with 30 occurrences.| 
| [OwlThing](classes/OwlThing.md) | No class (type) description specified<br/>Class with 1506 occurrences.| 
| [RdfsResource](classes/RdfsResource.md) | No class (type) description specified<br/>Class with 1527 occurrences.| 
| [SchemaCreativeWork](classes/SchemaCreativeWork.md) | The most generic kind of creative work, including books, movies, photographs, software programs, etc.<br/>Class with 165029 occurrences.| 
| [SchemaDataDownload](classes/SchemaDataDownload.md) | All or part of a [[Dataset]] in downloadable form. <br/>Class with 56432 occurrences.| 
| [SchemaDataset](classes/SchemaDataset.md) | A body of structured information describing some topic(s) of interest.<br/>Class with 28220 occurrences.| 
| [SchemaGeoCoordinates](classes/SchemaGeoCoordinates.md) | The geographic coordinates of a place or event.<br/>Class with 761166 occurrences.| 
| [SchemaGeoShape](classes/SchemaGeoShape.md) | The geographic shape of a place. A GeoShape can be described using several properties whose values are based on latitude/longitude pairs. Either whitespace or commas can be used to separate latitude and longitude; whitespace should be used when writing a list of several such points.<br/>Class with 427818 occurrences.| 
| [SchemaGovernmentOrganization](classes/SchemaGovernmentOrganization.md) | A governmental organization or agency.<br/>Class with 41703 occurrences.| 
| [SchemaOrganization](classes/SchemaOrganization.md) | An organization such as a school, NGO, corporation, club, etc.<br/>Class with 247 occurrences.| 
| [SchemaPlace](classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension.<br/>Class with 253321 occurrences.| 
| [SchemaPropertyValue](classes/SchemaPropertyValue.md) | A property-value pair, e.g. representing a feature of a product or place. Use the 'name' property for the name of the property. If there is an additional human-readable version of the value, put that into the 'description' property.\n\n Always use specific schema.org properties when a) they exist and b) you can populate them. Using PropertyValue as a substitute will typically not trigger the same effect as using the original, specific property.<br/>Class with 82692 occurrences.| 
| [Sf#GeometryCollection](classes/Sf#GeometryCollection.md) | No class (type) description specified<br/>Class with 5 occurrences.| 
| [Sf#LineString](classes/Sf#LineString.md) | No class (type) description specified<br/>Class with 101788 occurrences.| 
| [Sf#MultiPolygon](classes/Sf#MultiPolygon.md) | No class (type) description specified<br/>Class with 320382 occurrences.| 
| [Sf#Point](classes/Sf#Point.md) | No class (type) description specified<br/>Class with 763180 occurrences.| 
| [Sf#Polygon](classes/Sf#Polygon.md) | No class (type) description specified<br/>Class with 32964 occurrences.| 





## Slots

| Slot | Description |
| --- | --- |
| [badwdt_P2043](slots/badwdt_P2043.md) | No slot (predicate) description specified<br/>34082 occurrences with subject type schema_Place and object type string.<br/>3458 occurrences with subject type schema_Place and object type integer.<br/>30393 occurrences with subject type schema_Place and object type double.|
| [badwdt_P2053](slots/badwdt_P2053.md) | No slot (predicate) description specified<br/>30375 occurrences with subject type schema_Place and object type double.<br/>3476 occurrences with subject type schema_Place and object type integer.|
| [badwdt_P403](slots/badwdt_P403.md) | No slot (predicate) description specified<br/>63891 occurrences with subject type schema_Place and object type uri.|
| [badwdt_P885](slots/badwdt_P885.md) | No slot (predicate) description specified<br/>63522 occurrences with subject type schema_Place and object type uri.|
| [dc_description](slots/dc_description.md) | No slot (predicate) description specified<br/>1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type string.<br/>2 occurrences with subject type rdfs_Resource and object type string.|
| [dct_conformsTo](slots/dct_conformsTo.md) | No slot (predicate) description specified<br/>56432 occurrences with subject type schema_DataDownload and object type string.<br/>3194 occurrences with untyped subjects and object type uri.<br/>2 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type uri.<br/>4 occurrences with subject type rdfs_Resource and object type uri.|
| [dct_format](slots/dct_format.md) | No slot (predicate) description specified<br/>7697 occurrences with untyped subjects and object type string.<br/>3 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type string.<br/>6 occurrences with subject type rdfs_Resource and object type string.|
| [geo_asWKT](slots/geo_asWKT.md) | No slot (predicate) description specified<br/>762910 occurrences with subject type sf_#Point and object type geo_wktLiteral.<br/>317560 occurrences with subject type sf_#MultiPolygon and object type geo_wktLiteral.<br/>32768 occurrences with subject type sf_#Polygon and object type geo_wktLiteral.<br/>101773 occurrences with subject type sf_#LineString and object type geo_wktLiteral.<br/>4 occurrences with subject type sf_#GeometryCollection and object type geo_wktLiteral.|
| [geo_crs](slots/geo_crs.md) | No slot (predicate) description specified<br/>13487 occurrences with subject type sf_#Point and object type uri.|
| [geo_hasGeometry](slots/geo_hasGeometry.md) | No slot (predicate) description specified<br/>319697 occurrences with subject type schema_Place and object type sf_#MultiPolygon.<br/>101786 occurrences with subject type schema_Place and object type sf_#LineString.<br/>32790 occurrences with subject type schema_Place and object type sf_#Polygon.<br/>200617 occurrences with subject type schema_Place and object type sf_#Point.<br/>387017 occurrences with subject type hyf__HY_HydroLocation and object type sf_#Point.<br/>10247 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type sf_#Point.<br/>5 occurrences with subject type schema_Place and object type sf_#GeometryCollection.|
| [geosparql_asWKT](slots/geosparql_asWKT.md) | No slot (predicate) description specified<br/>6 occurrences with subject type sf_#Point and object type geo_wktLiteral.|
| [geosparql_hasGeometry](slots/geosparql_hasGeometry.md) | No slot (predicate) description specified<br/>6 occurrences with untyped subjects and object type http://www.opengis.net/ont/sf#Point.|
| [gsp_asWKT](slots/gsp_asWKT.md) | No slot (predicate) description specified<br/>351 occurrences with subject type sf_#MultiPolygon and object type geo_wktLiteral.<br/>264 occurrences with subject type sf_#Point and object type geo_wktLiteral.<br/>171 occurrences with subject type sf_#Polygon and object type geo_wktLiteral.|
| [gsp_hasGeometry](slots/gsp_hasGeometry.md) | No slot (predicate) description specified<br/>187 occurrences with subject type schema_Place and object type sf_#Point.<br/>77 occurrences with subject type hyf__HY_HydroLocation and object type sf_#Point.<br/>353 occurrences with subject type schema_Place and object type sf_#MultiPolygon.<br/>171 occurrences with subject type schema_Place and object type sf_#Polygon.|
| [hsdo_about](slots/hsdo_about.md) | No slot (predicate) description specified<br/>48672 occurrences with subject type hsdo_WebPage and object type string.|
| [hsdo_author](slots/hsdo_author.md) | No slot (predicate) description specified<br/>2 occurrences with subject type hsdo_NewsArticle and object type hsdo_Person.|
| [hsdo_breadcrumb](slots/hsdo_breadcrumb.md) | No slot (predicate) description specified<br/>3 occurrences with subject type hsdo_WebPage and object type hsdo_BreadcrumbList.|
| [hsdo_caption](slots/hsdo_caption.md) | No slot (predicate) description specified<br/>3 occurrences with subject type hsdo_ImageObject and object type string.|
| [hsdo_dateModified](slots/hsdo_dateModified.md) | No slot (predicate) description specified<br/>2 occurrences with subject type hsdo_NewsArticle and object type hsdo_Date.<br/>3 occurrences with subject type hsdo_WebPage and object type hsdo_Date.|
| [hsdo_datePublished](slots/hsdo_datePublished.md) | No slot (predicate) description specified<br/>2 occurrences with subject type hsdo_NewsArticle and object type hsdo_Date.<br/>3 occurrences with subject type hsdo_WebPage and object type hsdo_Date.|
| [hsdo_description](slots/hsdo_description.md) | No slot (predicate) description specified<br/>1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type string.<br/>1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment and object type string.<br/>1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork and object type string.<br/>48677 occurrences with subject type hsdo_WebPage and object type string.<br/>1 occurrences with subject type hsdo_WebSite and object type string.<br/>17 occurrences with subject type hsdo_error and object type string.<br/>2 occurrences with subject type hsdo_NewsArticle and object type string.|
| [hsdo_headline](slots/hsdo_headline.md) | No slot (predicate) description specified<br/>2 occurrences with subject type hsdo_NewsArticle and object type string.|
| [hsdo_height](slots/hsdo_height.md) | No slot (predicate) description specified<br/>3 occurrences with subject type hsdo_ImageObject and object type integer.|
| [hsdo_image](slots/hsdo_image.md) | No slot (predicate) description specified<br/>1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type string.<br/>1 occurrences with subject type hsdo_Organization and object type hsdo_ImageObject.<br/>2 occurrences with subject type hsdo_NewsArticle and object type uri.|
| [hsdo_inLanguage](slots/hsdo_inLanguage.md) | No slot (predicate) description specified<br/>1 occurrences with subject type hsdo_WebSite and object type string.<br/>3 occurrences with subject type hsdo_WebPage and object type string.|
| [hsdo_isPartOf](slots/hsdo_isPartOf.md) | No slot (predicate) description specified<br/>3 occurrences with subject type hsdo_WebPage and object type hsdo_WebSite.|
| [hsdo_item](slots/hsdo_item.md) | No slot (predicate) description specified<br/>2 occurrences with subject type hsdo_ListItem and object type hsdo_WebPage.<br/>1 occurrences with subject type hsdo_ListItem and object type string.|
| [hsdo_itemListElement](slots/hsdo_itemListElement.md) | No slot (predicate) description specified<br/>5 occurrences with subject type hsdo_BreadcrumbList and object type hsdo_ListItem.|
| [hsdo_logo](slots/hsdo_logo.md) | No slot (predicate) description specified<br/>5 occurrences with subject type hsdo_Organization and object type hsdo_ImageObject.|
| [hsdo_mainEntityOfPage](slots/hsdo_mainEntityOfPage.md) | No slot (predicate) description specified<br/>2 occurrences with subject type hsdo_NewsArticle and object type hsdo_WebPage.|
| [hsdo_name](slots/hsdo_name.md) | No slot (predicate) description specified<br/>1 occurrences with subject type rdfs_Resource and object type string.<br/>1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type string.<br/>1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment and object type string.<br/>1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork and object type string.<br/>2 occurrences with subject type hsdo_Person and object type string.<br/>3 occurrences with subject type hsdo_Organization and object type string.<br/>48677 occurrences with subject type hsdo_WebPage and object type string.<br/>3 occurrences with subject type hsdo_ListItem and object type string.<br/>1 occurrences with subject type hsdo_WebSite and object type string.|
| [hsdo_nextItem](slots/hsdo_nextItem.md) | No slot (predicate) description specified<br/>2 occurrences with subject type hsdo_ListItem and object type string.|
| [hsdo_position](slots/hsdo_position.md) | No slot (predicate) description specified<br/>3 occurrences with subject type hsdo_ListItem and object type integer.|
| [hsdo_potentialAction](slots/hsdo_potentialAction.md) | No slot (predicate) description specified<br/>1 occurrences with subject type hsdo_WebSite and object type hsdo_SearchAction.|
| [hsdo_previousItem](slots/hsdo_previousItem.md) | No slot (predicate) description specified<br/>2 occurrences with subject type hsdo_ListItem and object type string.|
| [hsdo_provider](slots/hsdo_provider.md) | No slot (predicate) description specified<br/>3194 occurrences with untyped subjects and object type uri.<br/>1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type uri.<br/>2 occurrences with subject type rdfs_Resource and object type uri.<br/>48672 occurrences with subject type hsdo_WebPage and object type string.|
| [hsdo_publisher](slots/hsdo_publisher.md) | No slot (predicate) description specified<br/>1 occurrences with subject type hsdo_WebSite and object type hsdo_Organization.<br/>2 occurrences with subject type hsdo_NewsArticle and object type hsdo_Organization.|
| [hsdo_query_input](slots/hsdo_query_input.md) | No slot (predicate) description specified<br/>1 occurrences with subject type hsdo_SearchAction and object type string.|
| [hsdo_sameAs](slots/hsdo_sameAs.md) | No slot (predicate) description specified<br/>3 occurrences with subject type hsdo_Organization and object type uri.|
| [hsdo_subjectOf](slots/hsdo_subjectOf.md) | No slot (predicate) description specified<br/>1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type http___rdfs.org_ns_void#Dataset.<br/>2 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type rdfs_Resource.<br/>3227 occurrences with subject type rdfs_Resource and object type uri.<br/>6 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type uri.<br/>15 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type uri.|
| [hsdo_target](slots/hsdo_target.md) | No slot (predicate) description specified<br/>1 occurrences with subject type hsdo_SearchAction and object type hsdo_EntryPoint.|
| [hsdo_url](slots/hsdo_url.md) | No slot (predicate) description specified<br/>5 occurrences with subject type hsdo_ImageObject and object type uri.<br/>4 occurrences with subject type hsdo_WebPage and object type hsdo_WebPage.<br/>1 occurrences with subject type hsdo_Organization and object type hsdo_WebPage.<br/>1 occurrences with subject type hsdo_WebSite and object type hsdo_WebPage.<br/>1 occurrences with subject type hsdo_WebPage and object type uri.|
| [hsdo_urlTemplate](slots/hsdo_urlTemplate.md) | No slot (predicate) description specified<br/>1 occurrences with subject type hsdo_EntryPoint and object type string.|
| [hsdo_width](slots/hsdo_width.md) | No slot (predicate) description specified<br/>3 occurrences with subject type hsdo_ImageObject and object type integer.|
| [http___geosciences.ca_def_groundwater#gwAquiferSystem](slots/http___geosciences.ca_def_groundwater#gwAquiferSystem.md) | No slot (predicate) description specified<br/>1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type uri.|
| [http___geosciences.ca_def_hydraulic#contains](slots/http___geosciences.ca_def_hydraulic#contains.md) | No slot (predicate) description specified<br/>1 occurrences with subject type rdfs_Resource and object type uri.|
| [http___rdfs.org_ns_void#property](slots/http___rdfs.org_ns_void#property.md) | No slot (predicate) description specified<br/>1 occurrences with subject type rdfs_Resource and object type uri.|
| [http___rdfs.org_ns_void#target](slots/http___rdfs.org_ns_void#target.md) | No slot (predicate) description specified<br/>1 occurrences with subject type rdfs_Resource and object type http___rdfs.org_ns_void#Dataset.<br/>1 occurrences with subject type rdfs_Resource and object type uri.|
| [http___www.opengeospatial.org_standards_geosparql_sfContains](slots/http___www.opengeospatial.org_standards_geosparql_sfContains.md) | No slot (predicate) description specified<br/>14 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_Well.<br/>1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type http___geosciences.ca_def_groundwater#GW_Well.|
| [http___www.opengeospatial.org_standards_geosparql_sfIntersects](slots/http___www.opengeospatial.org_standards_geosparql_sfIntersects.md) | No slot (predicate) description specified<br/>14 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type rdfs_Resource.<br/>13 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type uri.<br/>108 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_AquiferSystem.<br/>14 occurrences with subject type rdfs_Resource and object type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit.<br/>108 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type rdfs_Resource.|
| [http___www.opengeospatial.org_standards_geosparql_sfWithin](slots/http___www.opengeospatial.org_standards_geosparql_sfWithin.md) | No slot (predicate) description specified<br/>14 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type rdfs_Resource.<br/>1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type http___geosciences.ca_def_groundwater#GW_AquiferSystem.|
| [http___www.opengeospatial.org_standards_waterml2_hy_features_flowpath](slots/http___www.opengeospatial.org_standards_waterml2_hy_features_flowpath.md) | No slot (predicate) description specified<br/>2536 occurrences with subject type schema_Place and object type uri.<br/>3416 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type uri.|
| [http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocationType](slots/http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocationType.md) | No slot (predicate) description specified<br/>3416 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type uri.|
| [https___geoconnex.ca_id_connectedTo](slots/https___geoconnex.ca_id_connectedTo.md) | No slot (predicate) description specified<br/>1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type uri.|
| [https___www.opengis.net_def_appschema_hy_features_hyf_catchmentRealization](slots/https___www.opengis.net_def_appschema_hy_features_hyf_catchmentRealization.md) | No slot (predicate) description specified<br/>1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment and object type https___www.opengis.net_def_appschema_hy_features_hyf_HY_CatchmentDivide.<br/>1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment and object type https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork.<br/>1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment and object type https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrographicNetwork.|
| [https___www.opengis.net_def_appschema_hy_features_hyf_networkStation](slots/https___www.opengis.net_def_appschema_hy_features_hyf_networkStation.md) | No slot (predicate) description specified<br/>15 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork and object type https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricFeature.|
| [https___www.opengis.net_def_appschema_hy_features_hyf_realizedCatchment](slots/https___www.opengis.net_def_appschema_hy_features_hyf_realizedCatchment.md) | No slot (predicate) description specified<br/>1 occurrences with subject type https___www.opengis.net_def_appschema_hy_features_hyf_HY_HydrometricNetwork and object type https___www.opengis.net_def_appschema_hy_features_hyf_HY_Catchment.|
| [https___www.opengis.net_def_hy_features_ontology_hyf_catchmentRealization](slots/https___www.opengis.net_def_hy_features_ontology_hyf_catchmentRealization.md) | No slot (predicate) description specified<br/>789 occurrences with subject type rdfs_Resource and object type rdfs_Resource.|
| [https___www.opengis.net_def_hy_features_ontology_hyf_contributingCatchment](slots/https___www.opengis.net_def_hy_features_ontology_hyf_contributingCatchment.md) | No slot (predicate) description specified<br/>1 occurrences with subject type rdfs_Resource and object type uri.<br/>374 occurrences with subject type rdfs_Resource and object type rdfs_Resource.|
| [https___www.opengis.net_def_hy_features_ontology_hyf_encompassingCatchment](slots/https___www.opengis.net_def_hy_features_ontology_hyf_encompassingCatchment.md) | No slot (predicate) description specified<br/>187 occurrences with subject type rdfs_Resource and object type rdfs_Resource.|
| [https___www.opengis.net_def_hy_features_ontology_hyf_exorheicDrainage](slots/https___www.opengis.net_def_hy_features_ontology_hyf_exorheicDrainage.md) | No slot (predicate) description specified<br/>187 occurrences with subject type rdfs_Resource and object type rdfs_Resource.|
| [https___www.opengis.net_def_hy_features_ontology_hyf_hydrometricNetwork](slots/https___www.opengis.net_def_hy_features_ontology_hyf_hydrometricNetwork.md) | No slot (predicate) description specified<br/>74 occurrences with subject type rdfs_Resource and object type rdfs_Resource.|
| [https___www.opengis.net_def_hy_features_ontology_hyf_inflow](slots/https___www.opengis.net_def_hy_features_ontology_hyf_inflow.md) | No slot (predicate) description specified<br/>99 occurrences with subject type rdfs_Resource and object type rdfs_Resource.|
| [https___www.opengis.net_def_hy_features_ontology_hyf_lowerCatchment](slots/https___www.opengis.net_def_hy_features_ontology_hyf_lowerCatchment.md) | No slot (predicate) description specified<br/>374 occurrences with subject type rdfs_Resource and object type rdfs_Resource.|
| [https___www.opengis.net_def_hy_features_ontology_hyf_networkStation](slots/https___www.opengis.net_def_hy_features_ontology_hyf_networkStation.md) | No slot (predicate) description specified<br/>74 occurrences with subject type rdfs_Resource and object type rdfs_Resource.|
| [https___www.opengis.net_def_hy_features_ontology_hyf_nexusRealization](slots/https___www.opengis.net_def_hy_features_ontology_hyf_nexusRealization.md) | No slot (predicate) description specified<br/>187 occurrences with subject type rdfs_Resource and object type rdfs_Resource.|
| [https___www.opengis.net_def_hy_features_ontology_hyf_outflow](slots/https___www.opengis.net_def_hy_features_ontology_hyf_outflow.md) | No slot (predicate) description specified<br/>374 occurrences with subject type rdfs_Resource and object type rdfs_Resource.|
| [https___www.opengis.net_def_hy_features_ontology_hyf_realizedCatchment](slots/https___www.opengis.net_def_hy_features_ontology_hyf_realizedCatchment.md) | No slot (predicate) description specified<br/>789 occurrences with subject type rdfs_Resource and object type rdfs_Resource.|
| [https___www.opengis.net_def_hy_features_ontology_hyf_realizedNexus](slots/https___www.opengis.net_def_hy_features_ontology_hyf_realizedNexus.md) | No slot (predicate) description specified<br/>187 occurrences with subject type rdfs_Resource and object type rdfs_Resource.|
| [https___www.opengis.net_def_hy_features_ontology_hyf_receivingCatchment](slots/https___www.opengis.net_def_hy_features_ontology_hyf_receivingCatchment.md) | No slot (predicate) description specified<br/>99 occurrences with subject type rdfs_Resource and object type rdfs_Resource.|
| [https___www.opengis.net_def_hy_features_ontology_hyf_upperCatchment](slots/https___www.opengis.net_def_hy_features_ontology_hyf_upperCatchment.md) | No slot (predicate) description specified<br/>374 occurrences with subject type rdfs_Resource and object type rdfs_Resource.<br/>2 occurrences with subject type rdfs_Resource and object type uri.|
| [hyf__containingCatchment](slots/hyf__containingCatchment.md) | No slot (predicate) description specified<br/>83018 occurrences with subject type schema_Place and object type schema_Place.<br/>9 occurrences with subject type schema_Place and object type uri.|
| [hyf__distanceDescription](slots/hyf__distanceDescription.md) | No slot (predicate) description specified<br/>298086 occurrences with untyped subjects and object type uri.|
| [hyf__distanceExpression](slots/hyf__distanceExpression.md) | No slot (predicate) description specified<br/>298086 occurrences with untyped subjects and object type uri.|
| [hyf__HY_DistanceDescription](slots/hyf__HY_DistanceDescription.md) | No slot (predicate) description specified<br/>298086 occurrences with untyped subjects and object type string.|
| [hyf__HY_DistanceFromReferent](slots/hyf__HY_DistanceFromReferent.md) | No slot (predicate) description specified<br/>298086 occurrences with untyped subjects and object type uri.|
| [hyf__HY_HydroLocationType](slots/hyf__HY_HydroLocationType.md) | No slot (predicate) description specified<br/>187886 occurrences with subject type hyf__HY_HydroLocation and object type string.|
| [hyf__HY_IndirectPosition](slots/hyf__HY_IndirectPosition.md) | No slot (predicate) description specified<br/>621349 occurrences with untyped subjects and object type uri.|
| [hyf__HydroLocationType](slots/hyf__HydroLocationType.md) | No slot (predicate) description specified<br/>13471 occurrences with subject type hyf__HY_HydroLocation and object type string.|
| [hyf__interpolative](slots/hyf__interpolative.md) | No slot (predicate) description specified<br/>269358 occurrences with untyped subjects and object type double.<br/>28728 occurrences with untyped subjects and object type integer.|
| [hyf__linearElement](slots/hyf__linearElement.md) | No slot (predicate) description specified<br/>296195 occurrences with untyped subjects and object type uri.<br/>323140 occurrences with untyped subjects and object type https://schema.org/Place.<br/>2014 occurrences with untyped subjects and object type string.|
| [hyf__referencedPosition](slots/hyf__referencedPosition.md) | No slot (predicate) description specified<br/>481919 occurrences with subject type hyf__HY_HydroLocation and object type uri.|
| [hyf_distanceDescription](slots/hyf_distanceDescription.md) | No slot (predicate) description specified<br/>6 occurrences with untyped subjects and object type uri.|
| [hyf_distanceExpression](slots/hyf_distanceExpression.md) | No slot (predicate) description specified<br/>6 occurrences with untyped subjects and object type uri.|
| [hyf_downstreamWaterbody](slots/hyf_downstreamWaterbody.md) | No slot (predicate) description specified<br/>31952 occurrences with subject type schema_Place and object type schema_Place.|
| [hyf_encompassingCatchment](slots/hyf_encompassingCatchment.md) | No slot (predicate) description specified<br/>87699 occurrences with subject type schema_Place and object type schema_Place.|
| [hyf_HY_DistanceDescription](slots/hyf_HY_DistanceDescription.md) | No slot (predicate) description specified<br/>6 occurrences with untyped subjects and object type string.|
| [hyf_HY_DistanceFromReferent](slots/hyf_HY_DistanceFromReferent.md) | No slot (predicate) description specified<br/>6 occurrences with untyped subjects and object type uri.|
| [hyf_HY_HydroLocationType](slots/hyf_HY_HydroLocationType.md) | No slot (predicate) description specified<br/>42 occurrences with subject type hyf__HY_HydroLocation and object type string.<br/>1617371 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type string.|
| [hyf_HY_IndirectPosition](slots/hyf_HY_IndirectPosition.md) | No slot (predicate) description specified<br/>10 occurrences with untyped subjects and object type uri.|
| [hyf_interpolative](slots/hyf_interpolative.md) | No slot (predicate) description specified<br/>2 occurrences with untyped subjects and object type integer.<br/>4 occurrences with untyped subjects and object type double.|
| [hyf_linearElement](slots/hyf_linearElement.md) | No slot (predicate) description specified<br/>10 occurrences with untyped subjects and object type string.|
| [hyf_referencedPosition](slots/hyf_referencedPosition.md) | No slot (predicate) description specified<br/>10 occurrences with subject type hyf__HY_HydroLocation and object type uri.|
| [owl_equivalentClass](slots/owl_equivalentClass.md) | No slot (predicate) description specified<br/>17 occurrences with subject type rdfs_Resource and object type rdfs_Resource.|
| [owl_sameAs](slots/owl_sameAs.md) | No slot (predicate) description specified<br/>1498 occurrences with subject type rdfs_Resource and object type rdfs_Resource.<br/>1 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit.<br/>2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type http___geosciences.ca_def_groundwater#GW_AquiferSystem.<br/>5 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type http___geosciences.ca_def_groundwater#GW_Well.|
| [rdf_type](slots/rdf_type.md) | No slot (predicate) description specified<br/>34 occurrences with subject type rdfs_Resource and object type uri.|
| [rdfs_label](slots/rdfs_label.md) | No slot (predicate) description specified<br/>1514 occurrences with subject type rdfs_Resource and object type string.<br/>3204 occurrences with untyped subjects and object type string.<br/>2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_HydrogeoUnit and object type string.<br/>5 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type string.<br/>2 occurrences with subject type http___geosciences.ca_def_groundwater#GW_AquiferSystem and object type string.<br/>5 occurrences with subject type http___geosciences.ca_def_groundwater#GW_Well and object type string.|
| [rdfs_subClassOf](slots/rdfs_subClassOf.md) | No slot (predicate) description specified<br/>43 occurrences with subject type rdfs_Resource and object type rdfs_Resource.|
| [schema_about](slots/schema_about.md) | No slot (predicate) description specified<br/>2536 occurrences with subject type schema_Place and object type uri.|
| [schema_contentUrl](slots/schema_contentUrl.md) | No slot (predicate) description specified<br/>56432 occurrences with subject type schema_DataDownload and object type string.|
| [schema_description](slots/schema_description.md) | No slot (predicate) description specified<br/>28216 occurrences with subject type schema_Dataset and object type string.<br/>28217 occurrences with subject type schema_PropertyValue and object type string.<br/>17510 occurrences with untyped subjects and object type string.<br/>187886 occurrences with subject type hyf__HY_HydroLocation and object type string.<br/>107289 occurrences with subject type schema_Place and object type string.|
| [schema_distribution](slots/schema_distribution.md) | No slot (predicate) description specified<br/>56432 occurrences with subject type schema_Dataset and object type schema_DataDownload.|
| [schema_encodingFormat](slots/schema_encodingFormat.md) | No slot (predicate) description specified<br/>56432 occurrences with subject type schema_DataDownload and object type string.|
| [schema_geo](slots/schema_geo.md) | No slot (predicate) description specified<br/>427661 occurrences with subject type schema_Place and object type schema_GeoShape.<br/>1944 occurrences with subject type schema_Place and object type uri.<br/>6 occurrences with untyped subjects and object type schema:GeoCoordinates.<br/>200804 occurrences with subject type schema_Place and object type schema_GeoCoordinates.<br/>10247 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type schema_GeoCoordinates.<br/>385003 occurrences with subject type hyf__HY_HydroLocation and object type schema_GeoCoordinates.|
| [schema_geoIntersects](slots/schema_geoIntersects.md) | No slot (predicate) description specified<br/>45668 occurrences with subject type schema_Place and object type string.|
| [schema_geoWithin](slots/schema_geoWithin.md) | No slot (predicate) description specified<br/>53554 occurrences with subject type schema_Place and object type schema_Place.<br/>2536 occurrences with subject type schema_Place and object type uri.<br/>2014 occurrences with subject type hyf__HY_HydroLocation and object type string.<br/>3416 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type schema_Place.<br/>3075 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type uri.|
| [schema_identifier](slots/schema_identifier.md) | No slot (predicate) description specified<br/>40988 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type schema_PropertyValue.<br/>247 occurrences with subject type schema_Organization and object type schema_PropertyValue.<br/>165029 occurrences with subject type schema_CreativeWork and object type string.<br/>13487 occurrences with subject type hyf__HY_HydroLocation and object type schema_PropertyValue.|
| [schema_isBasedOn](slots/schema_isBasedOn.md) | No slot (predicate) description specified<br/>85031 occurrences with subject type schema_Place and object type uri.|
| [schema_latitude](slots/schema_latitude.md) | No slot (predicate) description specified<br/>761101 occurrences with subject type schema_GeoCoordinates and object type double.<br/>65 occurrences with subject type schema_GeoCoordinates and object type integer.|
| [schema_line](slots/schema_line.md) | No slot (predicate) description specified<br/>101773 occurrences with subject type schema_GeoShape and object type string.|
| [schema_location](slots/schema_location.md) | No slot (predicate) description specified<br/>17510 occurrences with subject type schema_Place and object type uri.|
| [schema_longitude](slots/schema_longitude.md) | No slot (predicate) description specified<br/>761097 occurrences with subject type schema_GeoCoordinates and object type double.<br/>69 occurrences with subject type schema_GeoCoordinates and object type integer.|
| [schema_measurementMethod](slots/schema_measurementMethod.md) | No slot (predicate) description specified<br/>28216 occurrences with subject type schema_PropertyValue and object type uri.|
| [schema_measurementTechnique](slots/schema_measurementTechnique.md) | No slot (predicate) description specified<br/>28216 occurrences with subject type schema_PropertyValue and object type string.|
| [schema_name](slots/schema_name.md) | No slot (predicate) description specified<br/>28216 occurrences with subject type schema_Dataset and object type string.<br/>56432 occurrences with subject type schema_DataDownload and object type string.<br/>41703 occurrences with subject type schema_GovernmentOrganization and object type string.<br/>28216 occurrences with subject type schema_PropertyValue and object type string.<br/>45727 occurrences with untyped subjects and object type string.<br/>243268 occurrences with subject type schema_Place and object type string.<br/>201357 occurrences with subject type hyf__HY_HydroLocation and object type string.<br/>2741 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type string.<br/>247 occurrences with subject type schema_Organization and object type string.<br/>165029 occurrences with subject type schema_CreativeWork and object type string.|
| [schema_polygon](slots/schema_polygon.md) | No slot (predicate) description specified<br/>325888 occurrences with subject type schema_GeoShape and object type string.|
| [schema_PropertyID](slots/schema_PropertyID.md) | No slot (predicate) description specified<br/>40988 occurrences with subject type schema_PropertyValue and object type string.|
| [schema_propertyID](slots/schema_propertyID.md) | No slot (predicate) description specified<br/>41704 occurrences with subject type schema_PropertyValue and object type string.|
| [schema_provider](slots/schema_provider.md) | No slot (predicate) description specified<br/>28216 occurrences with subject type schema_Dataset and object type schema_GovernmentOrganization.<br/>1 occurrences with subject type http___rdfs.org_ns_void#Dataset and object type uri.<br/>2 occurrences with subject type rdfs_Resource and object type uri.<br/>98534 occurrences with subject type schema_Place and object type schema_url.<br/>185872 occurrences with subject type hyf__HY_HydroLocation and object type uri.<br/>13487 occurrences with subject type hyf__HY_HydroLocation and object type schema_GovernmentOrganization.|
| [schema_publisher](slots/schema_publisher.md) | No slot (predicate) description specified<br/>28216 occurrences with untyped subjects and object type string.|
| [schema_sameAs](slots/schema_sameAs.md) | No slot (predicate) description specified<br/>118 occurrences with subject type schema_Place and object type schema_Place.|
| [schema_subjectOf](slots/schema_subjectOf.md) | No slot (predicate) description specified<br/>78891 occurrences with subject type schema_Place and object type uri.<br/>8804 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type uri.<br/>185645 occurrences with subject type hyf__HY_HydroLocation and object type uri.<br/>28216 occurrences with subject type hyf__HY_HydroLocation and object type schema_Dataset.|
| [schema_supersededBy](slots/schema_supersededBy.md) | No slot (predicate) description specified<br/>214 occurrences with subject type schema_Place and object type schema_Place.<br/>18 occurrences with subject type schema_Place and object type uri.|
| [schema_temporalCoverage](slots/schema_temporalCoverage.md) | No slot (predicate) description specified<br/>28169 occurrences with subject type schema_Dataset and object type string.|
| [schema_unitText](slots/schema_unitText.md) | No slot (predicate) description specified<br/>28216 occurrences with subject type schema_PropertyValue and object type string.|
| [schema_url](slots/schema_url.md) | No slot (predicate) description specified<br/>28216 occurrences with subject type schema_Dataset and object type string.<br/>41703 occurrences with subject type schema_GovernmentOrganization and object type string.<br/>28217 occurrences with subject type schema_PropertyValue and object type string.<br/>185722 occurrences with untyped subjects and object type string.<br/>2535 occurrences with subject type schema_Place and object type string.<br/>247 occurrences with subject type schema_Organization and object type string.|
| [schema_value](slots/schema_value.md) | No slot (predicate) description specified<br/>44093 occurrences with subject type schema_PropertyValue and object type string.|
| [schema_variableMeasured](slots/schema_variableMeasured.md) | No slot (predicate) description specified<br/>28216 occurrences with subject type schema_Dataset and object type schema_PropertyValue.|
| [sosa_hasFeatureOfInterest](slots/sosa_hasFeatureOfInterest.md) | No slot (predicate) description specified<br/>1 occurrences with subject type schema_Place and object type uri.<br/>1 occurrences with subject type schema_Place and object type string.|
| [sosa_ObservationCollection](slots/sosa_ObservationCollection.md) | No slot (predicate) description specified<br/>6788 occurrences with subject type schema_Place and object type string.|







