# No schema name specified

No schema description specified



## Schema Diagram

```mermaid
erDiagram
GeoGeometry {
    string rdfs_label  
    uri rdfs_label  
    uri owl_sameAs  
}
KwgoAdministrativeRegion1 {
    uri owl_sameAs  
    string rdfs_label  
    uri rdfs_label  
    string kwgo_hasFIPS  
}
KwgoAdministrativeRegion2 {
    uri owl_sameAs  
    string rdfs_label  
    uri rdfs_label  
    string kwgo_hasFIPS  
}
KwgoAdministrativeRegion3 {
    uri owl_sameAs  
    string rdfs_label  
    uri rdfs_label  
    string kwgo_hasFIPS  
}
KwgoS2CellLevel13 {
    integer kwgo_cellID  
    float geo_hasMetricArea  
    uri owl_sameAs  
    string rdfs_label  
    uri rdfs_label  
}
OwlAllDifferent {

}
OwlAllDisjointClasses {

}
OwlAllDisjointProperties {

}
OwlAnnotation {

}
OwlAnnotationProperty {

}
OwlAsymmetricProperty {

}
OwlAxiom {

}
OwlClass {

}
OwlDataRange {

}
OwlDatatypeProperty {

}
OwlDeprecatedClass {

}
OwlDeprecatedProperty {

}
OwlFunctionalProperty {

}
OwlInverseFunctionalProperty {

}
OwlIrreflexiveProperty {

}
OwlNamedIndividual {
    string kwgo_hasFIPS  
    integer kwgo_cellID  
    float geo_hasMetricArea  
    uri owl_sameAs  
    uri rdfs_domain  
    string rdfs_label  
    uri rdfs_label  
    uri rdfs_range  
}
OwlNegativePropertyAssertion {

}
OwlNothing {
    string kwgo_hasFIPS  
    integer kwgo_cellID  
    float geo_hasMetricArea  
    uri owl_sameAs  
    uri rdfs_domain  
    string rdfs_label  
    uri rdfs_label  
    uri rdfs_range  
}
OwlObjectProperty {

}
OwlOntology {

}
OwlOntologyProperty {

}
OwlReflexiveProperty {

}
OwlRestriction {

}
OwlSymmetricProperty {

}
OwlThing {
    string kwgo_hasFIPS  
    integer kwgo_cellID  
    float geo_hasMetricArea  
    uri owl_sameAs  
    uri rdfs_domain  
    string rdfs_label  
    uri rdfs_label  
    uri rdfs_range  
}
OwlTransitiveProperty {

}
OwlRational {

}
OwlReal {

}
RdfAlt {

}
RdfBag {

}
RdfList {
    uri owl_sameAs  
}
RdfObjectProperty {
    uri owl_sameAs  
    uri rdfs_range  
    uri rdfs_domain  
}
RdfPlainLiteral {

}
RdfProperty {

}
RdfSeq {

}
RdfStatement {

}
RdfXMLLiteral {

}
RdfsClass {

}
RdfsContainer {

}
RdfsContainerMembershipProperty {

}
RdfsDatatype {

}
RdfsLiteral {

}
RdfsResource {

}
SfPolygon {
    string rdfs_label  
    uri rdfs_label  
    uri owl_sameAs  
}
XsdNCName {

}
XsdNMTOKEN {

}
XsdName {

}
XsdAnyURI {

}
XsdBase64Binary {

}
XsdBoolean {

}
XsdByte {

}
XsdDateTime {

}
XsdDateTimeStamp {

}
XsdDecimal {

}
XsdDouble {

}
XsdFloat {

}
XsdHexBinary {

}
XsdInt {

}
XsdInteger {

}
XsdLanguage {

}
XsdLong {

}
XsdNegativeInteger {

}
XsdNonNegativeInteger {

}
XsdNonPositiveInteger {

}
XsdNormalizedString {

}
XsdPositiveInteger {

}
XsdShort {

}
XsdString {

}
XsdToken {

}
XsdUnsignedByte {

}
XsdUnsignedInt {

}
XsdUnsignedLong {

}
XsdUnsignedShort {

}
GeoWktLiteral {

}

GeoGeometry ||--|o GeoWktLiteral : "geo_asWKT"
GeoGeometry ||--|o GeoGeometry : "owl_sameAs"
GeoGeometry ||--|o RdfObjectProperty : "owl_sameAs"
GeoGeometry ||--|o RdfList : "owl_sameAs"
GeoGeometry ||--|o KwgoAdministrativeRegion1 : "owl_sameAs"
GeoGeometry ||--|o OwlThing : "owl_sameAs"
GeoGeometry ||--|o SfPolygon : "owl_sameAs"
GeoGeometry ||--|o KwgoAdministrativeRegion3 : "owl_sameAs"
GeoGeometry ||--|o KwgoAdministrativeRegion2 : "owl_sameAs"
GeoGeometry ||--|o KwgoS2CellLevel13 : "owl_sameAs"
KwgoAdministrativeRegion1 ||--|o OwlThing : "kwgo_administrativePartOf"
KwgoAdministrativeRegion1 ||--|o KwgoAdministrativeRegion2 : "kwgo_administrativePartOf"
KwgoAdministrativeRegion1 ||--|o KwgoAdministrativeRegion1 : "kwgo_administrativePartOf"
KwgoAdministrativeRegion1 ||--|o OwlThing : "kwgo_sfOverlaps"
KwgoAdministrativeRegion1 ||--|o KwgoAdministrativeRegion1 : "kwgo_sfOverlaps"
KwgoAdministrativeRegion1 ||--|o KwgoAdministrativeRegion3 : "kwgo_sfOverlaps"
KwgoAdministrativeRegion1 ||--|o KwgoS2CellLevel13 : "kwgo_sfOverlaps"
KwgoAdministrativeRegion1 ||--|o KwgoAdministrativeRegion2 : "kwgo_sfOverlaps"
KwgoAdministrativeRegion1 ||--|o OwlThing : "kwgo_sfContains"
KwgoAdministrativeRegion1 ||--|o KwgoS2CellLevel13 : "kwgo_sfContains"
KwgoAdministrativeRegion1 ||--|o GeoGeometry : "owl_sameAs"
KwgoAdministrativeRegion1 ||--|o RdfObjectProperty : "owl_sameAs"
KwgoAdministrativeRegion1 ||--|o RdfList : "owl_sameAs"
KwgoAdministrativeRegion1 ||--|o KwgoAdministrativeRegion1 : "owl_sameAs"
KwgoAdministrativeRegion1 ||--|o OwlThing : "owl_sameAs"
KwgoAdministrativeRegion1 ||--|o SfPolygon : "owl_sameAs"
KwgoAdministrativeRegion1 ||--|o KwgoAdministrativeRegion3 : "owl_sameAs"
KwgoAdministrativeRegion1 ||--|o KwgoAdministrativeRegion2 : "owl_sameAs"
KwgoAdministrativeRegion1 ||--|o KwgoS2CellLevel13 : "owl_sameAs"
KwgoAdministrativeRegion1 ||--|o SfPolygon : "geo_hasGeometry"
KwgoAdministrativeRegion1 ||--|o GeoGeometry : "geo_hasGeometry"
KwgoAdministrativeRegion1 ||--|o OwlThing : "geo_hasGeometry"
KwgoAdministrativeRegion1 ||--|o SfPolygon : "geo_hasDefaultGeometry"
KwgoAdministrativeRegion1 ||--|o GeoGeometry : "geo_hasDefaultGeometry"
KwgoAdministrativeRegion1 ||--|o OwlThing : "geo_hasDefaultGeometry"
KwgoAdministrativeRegion1 ||--|o OwlThing : "kwgo_sfWithin"
KwgoAdministrativeRegion1 ||--|o KwgoAdministrativeRegion2 : "kwgo_sfWithin"
KwgoAdministrativeRegion1 ||--|o KwgoAdministrativeRegion3 : "kwgo_sfWithin"
KwgoAdministrativeRegion1 ||--|o KwgoAdministrativeRegion1 : "kwgo_sfWithin"
KwgoAdministrativeRegion2 ||--|o OwlThing : "kwgo_administrativePartOf"
KwgoAdministrativeRegion2 ||--|o KwgoAdministrativeRegion2 : "kwgo_administrativePartOf"
KwgoAdministrativeRegion2 ||--|o KwgoAdministrativeRegion1 : "kwgo_administrativePartOf"
KwgoAdministrativeRegion2 ||--|o OwlThing : "kwgo_sfOverlaps"
KwgoAdministrativeRegion2 ||--|o KwgoAdministrativeRegion1 : "kwgo_sfOverlaps"
KwgoAdministrativeRegion2 ||--|o KwgoAdministrativeRegion3 : "kwgo_sfOverlaps"
KwgoAdministrativeRegion2 ||--|o KwgoS2CellLevel13 : "kwgo_sfOverlaps"
KwgoAdministrativeRegion2 ||--|o KwgoAdministrativeRegion2 : "kwgo_sfOverlaps"
KwgoAdministrativeRegion2 ||--|o OwlThing : "kwgo_sfContains"
KwgoAdministrativeRegion2 ||--|o KwgoS2CellLevel13 : "kwgo_sfContains"
KwgoAdministrativeRegion2 ||--|o GeoGeometry : "owl_sameAs"
KwgoAdministrativeRegion2 ||--|o RdfObjectProperty : "owl_sameAs"
KwgoAdministrativeRegion2 ||--|o RdfList : "owl_sameAs"
KwgoAdministrativeRegion2 ||--|o KwgoAdministrativeRegion1 : "owl_sameAs"
KwgoAdministrativeRegion2 ||--|o OwlThing : "owl_sameAs"
KwgoAdministrativeRegion2 ||--|o SfPolygon : "owl_sameAs"
KwgoAdministrativeRegion2 ||--|o KwgoAdministrativeRegion3 : "owl_sameAs"
KwgoAdministrativeRegion2 ||--|o KwgoAdministrativeRegion2 : "owl_sameAs"
KwgoAdministrativeRegion2 ||--|o KwgoS2CellLevel13 : "owl_sameAs"
KwgoAdministrativeRegion2 ||--|o SfPolygon : "geo_hasGeometry"
KwgoAdministrativeRegion2 ||--|o GeoGeometry : "geo_hasGeometry"
KwgoAdministrativeRegion2 ||--|o OwlThing : "geo_hasGeometry"
KwgoAdministrativeRegion2 ||--|o SfPolygon : "geo_hasDefaultGeometry"
KwgoAdministrativeRegion2 ||--|o GeoGeometry : "geo_hasDefaultGeometry"
KwgoAdministrativeRegion2 ||--|o OwlThing : "geo_hasDefaultGeometry"
KwgoAdministrativeRegion2 ||--|o OwlThing : "kwgo_sfWithin"
KwgoAdministrativeRegion2 ||--|o KwgoAdministrativeRegion2 : "kwgo_sfWithin"
KwgoAdministrativeRegion2 ||--|o KwgoAdministrativeRegion3 : "kwgo_sfWithin"
KwgoAdministrativeRegion2 ||--|o KwgoAdministrativeRegion1 : "kwgo_sfWithin"
KwgoAdministrativeRegion3 ||--|o OwlThing : "kwgo_administrativePartOf"
KwgoAdministrativeRegion3 ||--|o KwgoAdministrativeRegion2 : "kwgo_administrativePartOf"
KwgoAdministrativeRegion3 ||--|o KwgoAdministrativeRegion1 : "kwgo_administrativePartOf"
KwgoAdministrativeRegion3 ||--|o SfPolygon : "geo_defaultGeometry"
KwgoAdministrativeRegion3 ||--|o GeoGeometry : "geo_defaultGeometry"
KwgoAdministrativeRegion3 ||--|o OwlThing : "geo_defaultGeometry"
KwgoAdministrativeRegion3 ||--|o OwlThing : "kwgo_sfOverlaps"
KwgoAdministrativeRegion3 ||--|o KwgoAdministrativeRegion1 : "kwgo_sfOverlaps"
KwgoAdministrativeRegion3 ||--|o KwgoAdministrativeRegion3 : "kwgo_sfOverlaps"
KwgoAdministrativeRegion3 ||--|o KwgoS2CellLevel13 : "kwgo_sfOverlaps"
KwgoAdministrativeRegion3 ||--|o KwgoAdministrativeRegion2 : "kwgo_sfOverlaps"
KwgoAdministrativeRegion3 ||--|o OwlThing : "kwgo_sfContains"
KwgoAdministrativeRegion3 ||--|o KwgoS2CellLevel13 : "kwgo_sfContains"
KwgoAdministrativeRegion3 ||--|o GeoGeometry : "owl_sameAs"
KwgoAdministrativeRegion3 ||--|o RdfObjectProperty : "owl_sameAs"
KwgoAdministrativeRegion3 ||--|o RdfList : "owl_sameAs"
KwgoAdministrativeRegion3 ||--|o KwgoAdministrativeRegion1 : "owl_sameAs"
KwgoAdministrativeRegion3 ||--|o OwlThing : "owl_sameAs"
KwgoAdministrativeRegion3 ||--|o SfPolygon : "owl_sameAs"
KwgoAdministrativeRegion3 ||--|o KwgoAdministrativeRegion3 : "owl_sameAs"
KwgoAdministrativeRegion3 ||--|o KwgoAdministrativeRegion2 : "owl_sameAs"
KwgoAdministrativeRegion3 ||--|o KwgoS2CellLevel13 : "owl_sameAs"
KwgoAdministrativeRegion3 ||--|o SfPolygon : "geo_hasGeometry"
KwgoAdministrativeRegion3 ||--|o GeoGeometry : "geo_hasGeometry"
KwgoAdministrativeRegion3 ||--|o OwlThing : "geo_hasGeometry"
KwgoAdministrativeRegion3 ||--|o OwlThing : "kwgo_sfWithin"
KwgoAdministrativeRegion3 ||--|o KwgoAdministrativeRegion2 : "kwgo_sfWithin"
KwgoAdministrativeRegion3 ||--|o KwgoAdministrativeRegion3 : "kwgo_sfWithin"
KwgoAdministrativeRegion3 ||--|o KwgoAdministrativeRegion1 : "kwgo_sfWithin"
KwgoS2CellLevel13 ||--|o OwlThing : "kwgo_sfOverlaps"
KwgoS2CellLevel13 ||--|o KwgoAdministrativeRegion1 : "kwgo_sfOverlaps"
KwgoS2CellLevel13 ||--|o KwgoAdministrativeRegion3 : "kwgo_sfOverlaps"
KwgoS2CellLevel13 ||--|o KwgoS2CellLevel13 : "kwgo_sfOverlaps"
KwgoS2CellLevel13 ||--|o KwgoAdministrativeRegion2 : "kwgo_sfOverlaps"
KwgoS2CellLevel13 ||--|o GeoGeometry : "owl_sameAs"
KwgoS2CellLevel13 ||--|o RdfObjectProperty : "owl_sameAs"
KwgoS2CellLevel13 ||--|o RdfList : "owl_sameAs"
KwgoS2CellLevel13 ||--|o KwgoAdministrativeRegion1 : "owl_sameAs"
KwgoS2CellLevel13 ||--|o OwlThing : "owl_sameAs"
KwgoS2CellLevel13 ||--|o SfPolygon : "owl_sameAs"
KwgoS2CellLevel13 ||--|o KwgoAdministrativeRegion3 : "owl_sameAs"
KwgoS2CellLevel13 ||--|o KwgoAdministrativeRegion2 : "owl_sameAs"
KwgoS2CellLevel13 ||--|o KwgoS2CellLevel13 : "owl_sameAs"
KwgoS2CellLevel13 ||--|o OwlThing : "kwgo_sfTouches"
KwgoS2CellLevel13 ||--|o KwgoS2CellLevel13 : "kwgo_sfTouches"
KwgoS2CellLevel13 ||--|o SfPolygon : "geo_hasGeometry"
KwgoS2CellLevel13 ||--|o GeoGeometry : "geo_hasGeometry"
KwgoS2CellLevel13 ||--|o OwlThing : "geo_hasGeometry"
KwgoS2CellLevel13 ||--|o SfPolygon : "geo_hasDefaultGeometry"
KwgoS2CellLevel13 ||--|o GeoGeometry : "geo_hasDefaultGeometry"
KwgoS2CellLevel13 ||--|o OwlThing : "geo_hasDefaultGeometry"
KwgoS2CellLevel13 ||--|o OwlThing : "kwgo_sfWithin"
KwgoS2CellLevel13 ||--|o KwgoAdministrativeRegion2 : "kwgo_sfWithin"
KwgoS2CellLevel13 ||--|o KwgoAdministrativeRegion3 : "kwgo_sfWithin"
KwgoS2CellLevel13 ||--|o KwgoAdministrativeRegion1 : "kwgo_sfWithin"
OwlNamedIndividual ||--|o OwlThing : "kwgo_administrativePartOf"
OwlNamedIndividual ||--|o KwgoAdministrativeRegion2 : "kwgo_administrativePartOf"
OwlNamedIndividual ||--|o KwgoAdministrativeRegion1 : "kwgo_administrativePartOf"
OwlNamedIndividual ||--|o SfPolygon : "geo_defaultGeometry"
OwlNamedIndividual ||--|o GeoGeometry : "geo_defaultGeometry"
OwlNamedIndividual ||--|o OwlThing : "geo_defaultGeometry"
OwlNamedIndividual ||--|o OwlThing : "kwgo_sfOverlaps"
OwlNamedIndividual ||--|o KwgoAdministrativeRegion1 : "kwgo_sfOverlaps"
OwlNamedIndividual ||--|o KwgoAdministrativeRegion3 : "kwgo_sfOverlaps"
OwlNamedIndividual ||--|o KwgoS2CellLevel13 : "kwgo_sfOverlaps"
OwlNamedIndividual ||--|o KwgoAdministrativeRegion2 : "kwgo_sfOverlaps"
OwlNamedIndividual ||--|o OwlThing : "kwgo_sfContains"
OwlNamedIndividual ||--|o KwgoS2CellLevel13 : "kwgo_sfContains"
OwlNamedIndividual ||--|o GeoGeometry : "owl_sameAs"
OwlNamedIndividual ||--|o RdfObjectProperty : "owl_sameAs"
OwlNamedIndividual ||--|o RdfList : "owl_sameAs"
OwlNamedIndividual ||--|o KwgoAdministrativeRegion1 : "owl_sameAs"
OwlNamedIndividual ||--|o OwlThing : "owl_sameAs"
OwlNamedIndividual ||--|o SfPolygon : "owl_sameAs"
OwlNamedIndividual ||--|o KwgoAdministrativeRegion3 : "owl_sameAs"
OwlNamedIndividual ||--|o KwgoAdministrativeRegion2 : "owl_sameAs"
OwlNamedIndividual ||--|o KwgoS2CellLevel13 : "owl_sameAs"
OwlNamedIndividual ||--|o OwlThing : "kwgo_sfTouches"
OwlNamedIndividual ||--|o KwgoS2CellLevel13 : "kwgo_sfTouches"
OwlNamedIndividual ||--|o SfPolygon : "geo_hasGeometry"
OwlNamedIndividual ||--|o GeoGeometry : "geo_hasGeometry"
OwlNamedIndividual ||--|o OwlThing : "geo_hasGeometry"
OwlNamedIndividual ||--|o OwlThing : "rdfs_domain"
OwlNamedIndividual ||--|o OwlClass : "rdfs_domain"
OwlNamedIndividual ||--|o RdfsClass : "rdfs_domain"
OwlNamedIndividual ||--|o SfPolygon : "geo_hasDefaultGeometry"
OwlNamedIndividual ||--|o GeoGeometry : "geo_hasDefaultGeometry"
OwlNamedIndividual ||--|o OwlThing : "geo_hasDefaultGeometry"
OwlNamedIndividual ||--|o OwlThing : "kwgo_sfWithin"
OwlNamedIndividual ||--|o KwgoAdministrativeRegion2 : "kwgo_sfWithin"
OwlNamedIndividual ||--|o KwgoAdministrativeRegion3 : "kwgo_sfWithin"
OwlNamedIndividual ||--|o KwgoAdministrativeRegion1 : "kwgo_sfWithin"
OwlNamedIndividual ||--|o OwlThing : "rdfs_range"
OwlNamedIndividual ||--|o OwlClass : "rdfs_range"
OwlNamedIndividual ||--|o RdfsClass : "rdfs_range"
OwlNamedIndividual ||--|o GeoWktLiteral : "geo_asWKT"
OwlNothing ||--|o OwlThing : "kwgo_administrativePartOf"
OwlNothing ||--|o KwgoAdministrativeRegion2 : "kwgo_administrativePartOf"
OwlNothing ||--|o KwgoAdministrativeRegion1 : "kwgo_administrativePartOf"
OwlNothing ||--|o SfPolygon : "geo_defaultGeometry"
OwlNothing ||--|o GeoGeometry : "geo_defaultGeometry"
OwlNothing ||--|o OwlThing : "geo_defaultGeometry"
OwlNothing ||--|o OwlThing : "kwgo_sfOverlaps"
OwlNothing ||--|o KwgoAdministrativeRegion1 : "kwgo_sfOverlaps"
OwlNothing ||--|o KwgoAdministrativeRegion3 : "kwgo_sfOverlaps"
OwlNothing ||--|o KwgoS2CellLevel13 : "kwgo_sfOverlaps"
OwlNothing ||--|o KwgoAdministrativeRegion2 : "kwgo_sfOverlaps"
OwlNothing ||--|o OwlThing : "kwgo_sfContains"
OwlNothing ||--|o KwgoS2CellLevel13 : "kwgo_sfContains"
OwlNothing ||--|o GeoGeometry : "owl_sameAs"
OwlNothing ||--|o RdfObjectProperty : "owl_sameAs"
OwlNothing ||--|o RdfList : "owl_sameAs"
OwlNothing ||--|o KwgoAdministrativeRegion1 : "owl_sameAs"
OwlNothing ||--|o OwlThing : "owl_sameAs"
OwlNothing ||--|o SfPolygon : "owl_sameAs"
OwlNothing ||--|o KwgoAdministrativeRegion3 : "owl_sameAs"
OwlNothing ||--|o KwgoAdministrativeRegion2 : "owl_sameAs"
OwlNothing ||--|o KwgoS2CellLevel13 : "owl_sameAs"
OwlNothing ||--|o OwlThing : "kwgo_sfTouches"
OwlNothing ||--|o KwgoS2CellLevel13 : "kwgo_sfTouches"
OwlNothing ||--|o SfPolygon : "geo_hasGeometry"
OwlNothing ||--|o GeoGeometry : "geo_hasGeometry"
OwlNothing ||--|o OwlThing : "geo_hasGeometry"
OwlNothing ||--|o OwlThing : "rdfs_domain"
OwlNothing ||--|o OwlClass : "rdfs_domain"
OwlNothing ||--|o RdfsClass : "rdfs_domain"
OwlNothing ||--|o SfPolygon : "geo_hasDefaultGeometry"
OwlNothing ||--|o GeoGeometry : "geo_hasDefaultGeometry"
OwlNothing ||--|o OwlThing : "geo_hasDefaultGeometry"
OwlNothing ||--|o OwlThing : "kwgo_sfWithin"
OwlNothing ||--|o KwgoAdministrativeRegion2 : "kwgo_sfWithin"
OwlNothing ||--|o KwgoAdministrativeRegion3 : "kwgo_sfWithin"
OwlNothing ||--|o KwgoAdministrativeRegion1 : "kwgo_sfWithin"
OwlNothing ||--|o OwlThing : "rdfs_range"
OwlNothing ||--|o OwlClass : "rdfs_range"
OwlNothing ||--|o RdfsClass : "rdfs_range"
OwlNothing ||--|o GeoWktLiteral : "geo_asWKT"
OwlThing ||--|o OwlThing : "kwgo_administrativePartOf"
OwlThing ||--|o KwgoAdministrativeRegion2 : "kwgo_administrativePartOf"
OwlThing ||--|o KwgoAdministrativeRegion1 : "kwgo_administrativePartOf"
OwlThing ||--|o SfPolygon : "geo_defaultGeometry"
OwlThing ||--|o GeoGeometry : "geo_defaultGeometry"
OwlThing ||--|o OwlThing : "geo_defaultGeometry"
OwlThing ||--|o OwlThing : "kwgo_sfOverlaps"
OwlThing ||--|o KwgoAdministrativeRegion1 : "kwgo_sfOverlaps"
OwlThing ||--|o KwgoAdministrativeRegion3 : "kwgo_sfOverlaps"
OwlThing ||--|o KwgoS2CellLevel13 : "kwgo_sfOverlaps"
OwlThing ||--|o KwgoAdministrativeRegion2 : "kwgo_sfOverlaps"
OwlThing ||--|o OwlThing : "kwgo_sfContains"
OwlThing ||--|o KwgoS2CellLevel13 : "kwgo_sfContains"
OwlThing ||--|o GeoGeometry : "owl_sameAs"
OwlThing ||--|o RdfObjectProperty : "owl_sameAs"
OwlThing ||--|o RdfList : "owl_sameAs"
OwlThing ||--|o KwgoAdministrativeRegion1 : "owl_sameAs"
OwlThing ||--|o OwlThing : "owl_sameAs"
OwlThing ||--|o SfPolygon : "owl_sameAs"
OwlThing ||--|o KwgoAdministrativeRegion3 : "owl_sameAs"
OwlThing ||--|o KwgoAdministrativeRegion2 : "owl_sameAs"
OwlThing ||--|o KwgoS2CellLevel13 : "owl_sameAs"
OwlThing ||--|o OwlThing : "kwgo_sfTouches"
OwlThing ||--|o KwgoS2CellLevel13 : "kwgo_sfTouches"
OwlThing ||--|o SfPolygon : "geo_hasGeometry"
OwlThing ||--|o GeoGeometry : "geo_hasGeometry"
OwlThing ||--|o OwlThing : "geo_hasGeometry"
OwlThing ||--|o OwlThing : "rdfs_domain"
OwlThing ||--|o OwlClass : "rdfs_domain"
OwlThing ||--|o RdfsClass : "rdfs_domain"
OwlThing ||--|o SfPolygon : "geo_hasDefaultGeometry"
OwlThing ||--|o GeoGeometry : "geo_hasDefaultGeometry"
OwlThing ||--|o OwlThing : "geo_hasDefaultGeometry"
OwlThing ||--|o OwlThing : "kwgo_sfWithin"
OwlThing ||--|o KwgoAdministrativeRegion2 : "kwgo_sfWithin"
OwlThing ||--|o KwgoAdministrativeRegion3 : "kwgo_sfWithin"
OwlThing ||--|o KwgoAdministrativeRegion1 : "kwgo_sfWithin"
OwlThing ||--|o OwlThing : "rdfs_range"
OwlThing ||--|o OwlClass : "rdfs_range"
OwlThing ||--|o RdfsClass : "rdfs_range"
OwlThing ||--|o GeoWktLiteral : "geo_asWKT"
RdfList ||--|o GeoGeometry : "owl_sameAs"
RdfList ||--|o RdfObjectProperty : "owl_sameAs"
RdfList ||--|o RdfList : "owl_sameAs"
RdfList ||--|o KwgoAdministrativeRegion1 : "owl_sameAs"
RdfList ||--|o OwlThing : "owl_sameAs"
RdfList ||--|o SfPolygon : "owl_sameAs"
RdfList ||--|o KwgoAdministrativeRegion3 : "owl_sameAs"
RdfList ||--|o KwgoAdministrativeRegion2 : "owl_sameAs"
RdfList ||--|o KwgoS2CellLevel13 : "owl_sameAs"
RdfObjectProperty ||--|o GeoGeometry : "owl_sameAs"
RdfObjectProperty ||--|o RdfObjectProperty : "owl_sameAs"
RdfObjectProperty ||--|o RdfList : "owl_sameAs"
RdfObjectProperty ||--|o KwgoAdministrativeRegion1 : "owl_sameAs"
RdfObjectProperty ||--|o OwlThing : "owl_sameAs"
RdfObjectProperty ||--|o SfPolygon : "owl_sameAs"
RdfObjectProperty ||--|o KwgoAdministrativeRegion3 : "owl_sameAs"
RdfObjectProperty ||--|o KwgoAdministrativeRegion2 : "owl_sameAs"
RdfObjectProperty ||--|o KwgoS2CellLevel13 : "owl_sameAs"
RdfObjectProperty ||--|o OwlThing : "rdfs_range"
RdfObjectProperty ||--|o OwlClass : "rdfs_range"
RdfObjectProperty ||--|o RdfsClass : "rdfs_range"
RdfObjectProperty ||--|o OwlThing : "rdfs_domain"
RdfObjectProperty ||--|o OwlClass : "rdfs_domain"
RdfObjectProperty ||--|o RdfsClass : "rdfs_domain"
SfPolygon ||--|o GeoWktLiteral : "geo_asWKT"
SfPolygon ||--|o GeoGeometry : "owl_sameAs"
SfPolygon ||--|o RdfObjectProperty : "owl_sameAs"
SfPolygon ||--|o RdfList : "owl_sameAs"
SfPolygon ||--|o KwgoAdministrativeRegion1 : "owl_sameAs"
SfPolygon ||--|o OwlThing : "owl_sameAs"
SfPolygon ||--|o SfPolygon : "owl_sameAs"
SfPolygon ||--|o KwgoAdministrativeRegion3 : "owl_sameAs"
SfPolygon ||--|o KwgoAdministrativeRegion2 : "owl_sameAs"
SfPolygon ||--|o KwgoS2CellLevel13 : "owl_sameAs"

```



## Classes

| Class | Description | Occurrences |
| --- | --- | --- |
| [GeoGeometry](classes/GeoGeometry.md) | No class (type) description specified<br/>| 251854 | 
| [GeoWktLiteral](classes/GeoWktLiteral.md) | No class (type) description specified<br/>| 0 | 
| [KwgoAdministrativeRegion1](classes/KwgoAdministrativeRegion1.md) | No class (type) description specified<br/>| 2 | 
| [KwgoAdministrativeRegion2](classes/KwgoAdministrativeRegion2.md) | No class (type) description specified<br/>| 118 | 
| [KwgoAdministrativeRegion3](classes/KwgoAdministrativeRegion3.md) | No class (type) description specified<br/>| 2225 | 
| [KwgoS2CellLevel13](classes/KwgoS2CellLevel13.md) | No class (type) description specified<br/>| 249509 | 
| [OwlObjectProperty](classes/OwlObjectProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlAsymmetricProperty](classes/OwlAsymmetricProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlInverseFunctionalProperty](classes/OwlInverseFunctionalProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlIrreflexiveProperty](classes/OwlIrreflexiveProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlReflexiveProperty](classes/OwlReflexiveProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlSymmetricProperty](classes/OwlSymmetricProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlTransitiveProperty](classes/OwlTransitiveProperty.md) | No class (type) description specified<br/>| 0 | 
| [OwlThing](classes/OwlThing.md) | No class (type) description specified<br/>| 571175 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlNamedIndividual](classes/OwlNamedIndividual.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlNothing](classes/OwlNothing.md) | No class (type) description specified<br/>| 0 | 
| [RdfList](classes/RdfList.md) | No class (type) description specified<br/>| 1 | 
| [RdfObjectProperty](classes/RdfObjectProperty.md) | No class (type) description specified<br/>| 1 | 
| [RdfProperty](classes/RdfProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlAnnotationProperty](classes/OwlAnnotationProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlDatatypeProperty](classes/OwlDatatypeProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlDeprecatedProperty](classes/OwlDeprecatedProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlFunctionalProperty](classes/OwlFunctionalProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlOntologyProperty](classes/OwlOntologyProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RdfsContainerMembershipProperty](classes/RdfsContainerMembershipProperty.md) | No class (type) description specified<br/>| 0 | 
| [RdfStatement](classes/RdfStatement.md) | No class (type) description specified<br/>| 0 | 
| [RdfsClass](classes/RdfsClass.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlClass](classes/OwlClass.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlRestriction](classes/OwlRestriction.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlDeprecatedClass](classes/OwlDeprecatedClass.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RdfsDatatype](classes/RdfsDatatype.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlDataRange](classes/OwlDataRange.md) | No class (type) description specified<br/>| 0 | 
| [RdfsContainer](classes/RdfsContainer.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RdfAlt](classes/RdfAlt.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RdfBag](classes/RdfBag.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RdfSeq](classes/RdfSeq.md) | No class (type) description specified<br/>| 0 | 
| [RdfsLiteral](classes/RdfsLiteral.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlRational](classes/OwlRational.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlReal](classes/OwlReal.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RdfPlainLiteral](classes/RdfPlainLiteral.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RdfXMLLiteral](classes/RdfXMLLiteral.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdAnyURI](classes/XsdAnyURI.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdBase64Binary](classes/XsdBase64Binary.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdBoolean](classes/XsdBoolean.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdByte](classes/XsdByte.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdDateTime](classes/XsdDateTime.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdDateTimeStamp](classes/XsdDateTimeStamp.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdDecimal](classes/XsdDecimal.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdDouble](classes/XsdDouble.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdFloat](classes/XsdFloat.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdHexBinary](classes/XsdHexBinary.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdInt](classes/XsdInt.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdInteger](classes/XsdInteger.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdLanguage](classes/XsdLanguage.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdLong](classes/XsdLong.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdName](classes/XsdName.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdNCName](classes/XsdNCName.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdNegativeInteger](classes/XsdNegativeInteger.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdNMTOKEN](classes/XsdNMTOKEN.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdNonNegativeInteger](classes/XsdNonNegativeInteger.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdNonPositiveInteger](classes/XsdNonPositiveInteger.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdNormalizedString](classes/XsdNormalizedString.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdPositiveInteger](classes/XsdPositiveInteger.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdShort](classes/XsdShort.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdString](classes/XsdString.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdToken](classes/XsdToken.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdUnsignedByte](classes/XsdUnsignedByte.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdUnsignedInt](classes/XsdUnsignedInt.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdUnsignedLong](classes/XsdUnsignedLong.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[XsdUnsignedShort](classes/XsdUnsignedShort.md) | No class (type) description specified<br/>| 0 | 
| [RdfsResource](classes/RdfsResource.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlAllDifferent](classes/OwlAllDifferent.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlAllDisjointClasses](classes/OwlAllDisjointClasses.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlAllDisjointProperties](classes/OwlAllDisjointProperties.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlAnnotation](classes/OwlAnnotation.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlAxiom](classes/OwlAxiom.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlNegativePropertyAssertion](classes/OwlNegativePropertyAssertion.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlOntology](classes/OwlOntology.md) | No class (type) description specified<br/>| 0 | 
| [Sf#Polygon](classes/Sf#Polygon.md) | No class (type) description specified<br/>| 251736 | 





## Slots

| Slot | Description | Occurrences |
| --- | --- | --- |
| [geo_asWKT](slots/geo_asWKT.md) | No slot (predicate) description specified<br/>| 251854 |
| [geo_defaultGeometry](slots/geo_defaultGeometry.md) | No slot (predicate) description specified<br/>| 2225 |
| [geo_hasDefaultGeometry](slots/geo_hasDefaultGeometry.md) | No slot (predicate) description specified<br/>| 249629 |
| [geo_hasGeometry](slots/geo_hasGeometry.md) | No slot (predicate) description specified<br/>| 251854 |
| [geo_hasMetricArea](slots/geo_hasMetricArea.md) | No slot (predicate) description specified<br/>| 249509 |
| [kwgo_administrativePartOf](slots/kwgo_administrativePartOf.md) | No slot (predicate) description specified<br/>| 2345 |
| [kwgo_cellID](slots/kwgo_cellID.md) | No slot (predicate) description specified<br/>| 249509 |
| [kwgo_hasFIPS](slots/kwgo_hasFIPS.md) | No slot (predicate) description specified<br/>| 2345 |
| [kwgo_sfContains](slots/kwgo_sfContains.md) | No slot (predicate) description specified<br/>| 923206 |
| [kwgo_sfOverlaps](slots/kwgo_sfOverlaps.md) | No slot (predicate) description specified<br/>| 287124 |
| [kwgo_sfTouches](slots/kwgo_sfTouches.md) | No slot (predicate) description specified<br/>| 2007528 |
| [kwgo_sfWithin](slots/kwgo_sfWithin.md) | No slot (predicate) description specified<br/>| 925551 |
| [owl_allValuesFrom](slots/owl_allValuesFrom.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_annotatedProperty](slots/owl_annotatedProperty.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_annotatedSource](slots/owl_annotatedSource.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_annotatedTarget](slots/owl_annotatedTarget.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_assertionProperty](slots/owl_assertionProperty.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_backwardCompatibleWith](slots/owl_backwardCompatibleWith.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_bottomDataProperty](slots/owl_bottomDataProperty.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_bottomObjectProperty](slots/owl_bottomObjectProperty.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_cardinality](slots/owl_cardinality.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_complementOf](slots/owl_complementOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_datatypeComplementOf](slots/owl_datatypeComplementOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_deprecated](slots/owl_deprecated.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_differentFrom](slots/owl_differentFrom.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_disjointUnionOf](slots/owl_disjointUnionOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_disjointWith](slots/owl_disjointWith.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_distinctMembers](slots/owl_distinctMembers.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_equivalentClass](slots/owl_equivalentClass.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_equivalentProperty](slots/owl_equivalentProperty.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_hasKey](slots/owl_hasKey.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_hasSelf](slots/owl_hasSelf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_hasValue](slots/owl_hasValue.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_imports](slots/owl_imports.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_incompatibleWith](slots/owl_incompatibleWith.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_intersectionOf](slots/owl_intersectionOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_inverseOf](slots/owl_inverseOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_maxCardinality](slots/owl_maxCardinality.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_maxQualifiedCardinality](slots/owl_maxQualifiedCardinality.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_members](slots/owl_members.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_minCardinality](slots/owl_minCardinality.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_minQualifiedCardinality](slots/owl_minQualifiedCardinality.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_onClass](slots/owl_onClass.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_onDataRange](slots/owl_onDataRange.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_onDatatype](slots/owl_onDatatype.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_oneOf](slots/owl_oneOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_onProperties](slots/owl_onProperties.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_onProperty](slots/owl_onProperty.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_priorVersion](slots/owl_priorVersion.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_propertyChainAxiom](slots/owl_propertyChainAxiom.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_propertyDisjointWith](slots/owl_propertyDisjointWith.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_qualifiedCardinality](slots/owl_qualifiedCardinality.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_sameAs](slots/owl_sameAs.md) | No slot (predicate) description specified<br/>| 571175 |
| [owl_someValuesFrom](slots/owl_someValuesFrom.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_sourceIndividual](slots/owl_sourceIndividual.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_targetIndividual](slots/owl_targetIndividual.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_targetValue](slots/owl_targetValue.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_topDataProperty](slots/owl_topDataProperty.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_unionOf](slots/owl_unionOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_versionInfo](slots/owl_versionInfo.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_versionIRI](slots/owl_versionIRI.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_withRestrictions](slots/owl_withRestrictions.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf__1](slots/rdf__1.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_first](slots/rdf_first.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_langRange](slots/rdf_langRange.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_object](slots/rdf_object.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_predicate](slots/rdf_predicate.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_rest](slots/rdf_rest.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_subject](slots/rdf_subject.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_type](slots/rdf_type.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_value](slots/rdf_value.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdfs_comment](slots/rdfs_comment.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdfs_domain](slots/rdfs_domain.md) | No slot (predicate) description specified<br/>| 1 |
| [rdfs_isDefinedBy](slots/rdfs_isDefinedBy.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdfs_label](slots/rdfs_label.md) | No slot (predicate) description specified<br/>| 503708 |
| [rdfs_range](slots/rdfs_range.md) | No slot (predicate) description specified<br/>| 1 |
| [rdfs_seeAlso](slots/rdfs_seeAlso.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdfs_subClassOf](slots/rdfs_subClassOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdfs_subPropertyOf](slots/rdfs_subPropertyOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_length](slots/xsd_length.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_maxExclusive](slots/xsd_maxExclusive.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_maxInclusive](slots/xsd_maxInclusive.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_maxLength](slots/xsd_maxLength.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_minExclusive](slots/xsd_minExclusive.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_minInclusive](slots/xsd_minInclusive.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_minLength](slots/xsd_minLength.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_pattern](slots/xsd_pattern.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |









## IRI prefixes

* geo: http://www.opengis.net/ont/geosparql#
* kwgo: http://stko-kwg.geog.ucsb.edu/lod/ontology/
* kwgr: http://stko-kwg.geog.ucsb.edu/lod/resource/
* linkml: https://w3id.org/linkml/
* owl: http://www.w3.org/2002/07/owl#
* rdf: http://www.w3.org/1999/02/22-rdf-syntax-ns#
* rdfs: http://www.w3.org/2000/01/rdf-schema#
* sf: http://www.opengis.net/ont/sf
* xsd: http://www.w3.org/2001/XMLSchema#
* shex: http://www.w3.org/ns/shex#
* schema: http://schema.org/
