# No schema name specified

No schema description specified



## Schema Diagram

```mermaid
erDiagram
GeoFeature {
    uri owl_sameAs  
}
GeoGeometry {
    uri owl_sameAs  
}
Gwml22GWAquifer {
    string memgs2_SAWidAquifer  
    uri owl_sameAs  
    uri rdfs_comment  
    string rdfs_comment  
}
HyfHYFlowPath {
    float badwdt_P2043  
    uri owl_sameAs  
    string sawwater_hasFTYPE  
    string schema_name  
    string sawwater_hasFCODE  
    string sawwater_hasCOMID  
    string sawwater_hasReachCode  
}
HyfHYWaterBody {
    uri owl_sameAs  
    uri rdfs_label  
    string rdfs_label  
    uri rdfs_comment  
    string rdfs_comment  
}
HyfHYWaterbody {
    float badwdt_P2043  
    uri owl_sameAs  
    string sawwater_hasFTYPE  
    string schema_name  
    string sawwater_hasFCODE  
    string sawwater_hasCOMID  
    string sawwater_hasReachCode  
}
KwgoS2CellLevel13 {
    uri owl_sameAs  
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
    uri rdfs_comment  
    string rdfs_comment  
    uri rdfs_range  
    uri owl_sameAs  
    uri rdfs_label  
    string rdfs_label  
    string sawwater_hasFTYPE  
    string schema_name  
    float badwdt_P2043  
    string sawwater_hasFCODE  
    string sawwater_hasCOMID  
    string memgs2_SAWidAquifer  
    uri rdfs_domain  
    string sawwater_hasReachCode  
}
OwlNegativePropertyAssertion {

}
OwlNothing {
    uri rdfs_comment  
    string rdfs_comment  
    uri rdfs_range  
    uri owl_sameAs  
    uri rdfs_label  
    string rdfs_label  
    string sawwater_hasFTYPE  
    string schema_name  
    float badwdt_P2043  
    string sawwater_hasFCODE  
    string sawwater_hasCOMID  
    string memgs2_SAWidAquifer  
    uri rdfs_domain  
    string sawwater_hasReachCode  
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
    uri rdfs_comment  
    string rdfs_comment  
    uri rdfs_range  
    uri owl_sameAs  
    uri rdfs_label  
    string rdfs_label  
    string sawwater_hasFTYPE  
    string schema_name  
    float badwdt_P2043  
    string sawwater_hasFCODE  
    string sawwater_hasCOMID  
    string memgs2_SAWidAquifer  
    uri rdfs_domain  
    string sawwater_hasReachCode  
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
    uri rdfs_domain  
    uri owl_sameAs  
    uri rdfs_range  
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
SchemaPlace {
    float badwdt_P2043  
    uri owl_sameAs  
    string sawwater_hasFTYPE  
    string schema_name  
    string sawwater_hasFCODE  
    string sawwater_hasCOMID  
    string sawwater_hasReachCode  
}
Sf#LineString {
    uri owl_sameAs  
}
Sf#MultiPolygon {
    uri owl_sameAs  
}
Sf#Polygon {
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

GeoFeature ||--|o HyfHYWaterBody : "owl_sameAs"
GeoFeature ||--|o KwgoS2CellLevel13 : "owl_sameAs"
GeoFeature ||--|o OwlThing : "owl_sameAs"
GeoFeature ||--|o Sf#LineString : "owl_sameAs"
GeoFeature ||--|o Sf#Polygon : "owl_sameAs"
GeoFeature ||--|o Sf#MultiPolygon : "owl_sameAs"
GeoFeature ||--|o HyfHYWaterbody : "owl_sameAs"
GeoFeature ||--|o RdfList : "owl_sameAs"
GeoFeature ||--|o GeoFeature : "owl_sameAs"
GeoFeature ||--|o GeoGeometry : "owl_sameAs"
GeoFeature ||--|o HyfHYFlowPath : "owl_sameAs"
GeoFeature ||--|o SchemaPlace : "owl_sameAs"
GeoFeature ||--|o Gwml22GWAquifer : "owl_sameAs"
GeoFeature ||--|o RdfObjectProperty : "owl_sameAs"
GeoFeature ||--|o OwlThing : "geo_hasGeometry"
GeoFeature ||--|o Sf#LineString : "geo_hasGeometry"
GeoFeature ||--|o Sf#Polygon : "geo_hasGeometry"
GeoFeature ||--|o Sf#MultiPolygon : "geo_hasGeometry"
GeoFeature ||--|o GeoGeometry : "geo_hasGeometry"
GeoFeature ||--|o OwlThing : "geo_defaultGeometry"
GeoFeature ||--|o Sf#LineString : "geo_defaultGeometry"
GeoFeature ||--|o Sf#Polygon : "geo_defaultGeometry"
GeoFeature ||--|o Sf#MultiPolygon : "geo_defaultGeometry"
GeoFeature ||--|o GeoGeometry : "geo_defaultGeometry"
GeoGeometry ||--|o GeoWktLiteral : "geo_asWKT"
GeoGeometry ||--|o HyfHYWaterBody : "owl_sameAs"
GeoGeometry ||--|o KwgoS2CellLevel13 : "owl_sameAs"
GeoGeometry ||--|o OwlThing : "owl_sameAs"
GeoGeometry ||--|o Sf#LineString : "owl_sameAs"
GeoGeometry ||--|o Sf#Polygon : "owl_sameAs"
GeoGeometry ||--|o Sf#MultiPolygon : "owl_sameAs"
GeoGeometry ||--|o HyfHYWaterbody : "owl_sameAs"
GeoGeometry ||--|o RdfList : "owl_sameAs"
GeoGeometry ||--|o GeoFeature : "owl_sameAs"
GeoGeometry ||--|o GeoGeometry : "owl_sameAs"
GeoGeometry ||--|o HyfHYFlowPath : "owl_sameAs"
GeoGeometry ||--|o SchemaPlace : "owl_sameAs"
GeoGeometry ||--|o Gwml22GWAquifer : "owl_sameAs"
GeoGeometry ||--|o RdfObjectProperty : "owl_sameAs"
Gwml22GWAquifer ||--|o HyfHYWaterBody : "owl_sameAs"
Gwml22GWAquifer ||--|o KwgoS2CellLevel13 : "owl_sameAs"
Gwml22GWAquifer ||--|o OwlThing : "owl_sameAs"
Gwml22GWAquifer ||--|o Sf#LineString : "owl_sameAs"
Gwml22GWAquifer ||--|o Sf#Polygon : "owl_sameAs"
Gwml22GWAquifer ||--|o Sf#MultiPolygon : "owl_sameAs"
Gwml22GWAquifer ||--|o HyfHYWaterbody : "owl_sameAs"
Gwml22GWAquifer ||--|o RdfList : "owl_sameAs"
Gwml22GWAquifer ||--|o GeoFeature : "owl_sameAs"
Gwml22GWAquifer ||--|o GeoGeometry : "owl_sameAs"
Gwml22GWAquifer ||--|o HyfHYFlowPath : "owl_sameAs"
Gwml22GWAquifer ||--|o SchemaPlace : "owl_sameAs"
Gwml22GWAquifer ||--|o Gwml22GWAquifer : "owl_sameAs"
Gwml22GWAquifer ||--|o RdfObjectProperty : "owl_sameAs"
Gwml22GWAquifer ||--|o HyfHYWaterBody : "kwgo_sfOverlaps"
Gwml22GWAquifer ||--|o KwgoS2CellLevel13 : "kwgo_sfOverlaps"
Gwml22GWAquifer ||--|o OwlThing : "kwgo_sfOverlaps"
Gwml22GWAquifer ||--|o Gwml22GWAquifer : "kwgo_sfOverlaps"
Gwml22GWAquifer ||--|o OwlThing : "prov_hadPrimarySource"
Gwml22GWAquifer ||--|o OwlThing : "geo_hasGeometry"
Gwml22GWAquifer ||--|o Sf#LineString : "geo_hasGeometry"
Gwml22GWAquifer ||--|o Sf#Polygon : "geo_hasGeometry"
Gwml22GWAquifer ||--|o Sf#MultiPolygon : "geo_hasGeometry"
Gwml22GWAquifer ||--|o GeoGeometry : "geo_hasGeometry"
Gwml22GWAquifer ||--|o KwgoS2CellLevel13 : "kwgo_sfContains"
Gwml22GWAquifer ||--|o OwlThing : "kwgo_sfContains"
Gwml22GWAquifer ||--|o OwlThing : "geo_defaultGeometry"
Gwml22GWAquifer ||--|o Sf#LineString : "geo_defaultGeometry"
Gwml22GWAquifer ||--|o Sf#Polygon : "geo_defaultGeometry"
Gwml22GWAquifer ||--|o Sf#MultiPolygon : "geo_defaultGeometry"
Gwml22GWAquifer ||--|o GeoGeometry : "geo_defaultGeometry"
HyfHYFlowPath ||--|o GeoFeature : "badwdt_P403"
HyfHYFlowPath ||--|o OwlThing : "badwdt_P403"
HyfHYFlowPath ||--|o HyfHYWaterBody : "owl_sameAs"
HyfHYFlowPath ||--|o KwgoS2CellLevel13 : "owl_sameAs"
HyfHYFlowPath ||--|o OwlThing : "owl_sameAs"
HyfHYFlowPath ||--|o Sf#LineString : "owl_sameAs"
HyfHYFlowPath ||--|o Sf#Polygon : "owl_sameAs"
HyfHYFlowPath ||--|o Sf#MultiPolygon : "owl_sameAs"
HyfHYFlowPath ||--|o HyfHYWaterbody : "owl_sameAs"
HyfHYFlowPath ||--|o RdfList : "owl_sameAs"
HyfHYFlowPath ||--|o GeoFeature : "owl_sameAs"
HyfHYFlowPath ||--|o GeoGeometry : "owl_sameAs"
HyfHYFlowPath ||--|o HyfHYFlowPath : "owl_sameAs"
HyfHYFlowPath ||--|o SchemaPlace : "owl_sameAs"
HyfHYFlowPath ||--|o Gwml22GWAquifer : "owl_sameAs"
HyfHYFlowPath ||--|o RdfObjectProperty : "owl_sameAs"
HyfHYFlowPath ||--|o KwgoS2CellLevel13 : "kwgo_sfCrosses"
HyfHYFlowPath ||--|o OwlThing : "kwgo_sfCrosses"
HyfHYFlowPath ||--|o HyfHYWaterbody : "kwgo_sfCrosses"
HyfHYFlowPath ||--|o HyfHYFlowPath : "kwgo_sfCrosses"
HyfHYFlowPath ||--|o SchemaPlace : "kwgo_sfCrosses"
HyfHYFlowPath ||--|o HyfHYFlowPath : "hyf__downstreamWaterbodyTC"
HyfHYFlowPath ||--|o SchemaPlace : "hyf__downstreamWaterbodyTC"
HyfHYFlowPath ||--|o OwlThing : "hyf__downstreamWaterbodyTC"
HyfHYFlowPath ||--|o HyfHYWaterbody : "hyf__downstreamWaterbodyTC"
HyfHYFlowPath ||--|o HyfHYFlowPath : "hyf__downstreamWaterbody"
HyfHYFlowPath ||--|o SchemaPlace : "hyf__downstreamWaterbody"
HyfHYFlowPath ||--|o OwlThing : "hyf__downstreamWaterbody"
HyfHYFlowPath ||--|o HyfHYWaterbody : "hyf__downstreamWaterbody"
HyfHYFlowPath ||--|o OwlThing : "geo_hasGeometry"
HyfHYFlowPath ||--|o Sf#LineString : "geo_hasGeometry"
HyfHYFlowPath ||--|o Sf#Polygon : "geo_hasGeometry"
HyfHYFlowPath ||--|o Sf#MultiPolygon : "geo_hasGeometry"
HyfHYFlowPath ||--|o GeoGeometry : "geo_hasGeometry"
HyfHYFlowPath ||--|o GeoFeature : "badwdt_P885"
HyfHYFlowPath ||--|o OwlThing : "badwdt_P885"
HyfHYFlowPath ||--|o OwlThing : "geo_defaultGeometry"
HyfHYFlowPath ||--|o Sf#LineString : "geo_defaultGeometry"
HyfHYFlowPath ||--|o Sf#Polygon : "geo_defaultGeometry"
HyfHYFlowPath ||--|o Sf#MultiPolygon : "geo_defaultGeometry"
HyfHYFlowPath ||--|o GeoGeometry : "geo_defaultGeometry"
HyfHYWaterBody ||--|o HyfHYWaterBody : "owl_sameAs"
HyfHYWaterBody ||--|o KwgoS2CellLevel13 : "owl_sameAs"
HyfHYWaterBody ||--|o OwlThing : "owl_sameAs"
HyfHYWaterBody ||--|o Sf#LineString : "owl_sameAs"
HyfHYWaterBody ||--|o Sf#Polygon : "owl_sameAs"
HyfHYWaterBody ||--|o Sf#MultiPolygon : "owl_sameAs"
HyfHYWaterBody ||--|o HyfHYWaterbody : "owl_sameAs"
HyfHYWaterBody ||--|o RdfList : "owl_sameAs"
HyfHYWaterBody ||--|o GeoFeature : "owl_sameAs"
HyfHYWaterBody ||--|o GeoGeometry : "owl_sameAs"
HyfHYWaterBody ||--|o HyfHYFlowPath : "owl_sameAs"
HyfHYWaterBody ||--|o SchemaPlace : "owl_sameAs"
HyfHYWaterBody ||--|o Gwml22GWAquifer : "owl_sameAs"
HyfHYWaterBody ||--|o RdfObjectProperty : "owl_sameAs"
HyfHYWaterBody ||--|o OwlThing : "geo_hasGeometry"
HyfHYWaterBody ||--|o Sf#LineString : "geo_hasGeometry"
HyfHYWaterBody ||--|o Sf#Polygon : "geo_hasGeometry"
HyfHYWaterBody ||--|o Sf#MultiPolygon : "geo_hasGeometry"
HyfHYWaterBody ||--|o GeoGeometry : "geo_hasGeometry"
HyfHYWaterBody ||--|o OwlThing : "geo_defaultGeometry"
HyfHYWaterBody ||--|o Sf#LineString : "geo_defaultGeometry"
HyfHYWaterBody ||--|o Sf#Polygon : "geo_defaultGeometry"
HyfHYWaterBody ||--|o Sf#MultiPolygon : "geo_defaultGeometry"
HyfHYWaterBody ||--|o GeoGeometry : "geo_defaultGeometry"
HyfHYWaterbody ||--|o GeoFeature : "badwdt_P403"
HyfHYWaterbody ||--|o OwlThing : "badwdt_P403"
HyfHYWaterbody ||--|o HyfHYWaterBody : "owl_sameAs"
HyfHYWaterbody ||--|o KwgoS2CellLevel13 : "owl_sameAs"
HyfHYWaterbody ||--|o OwlThing : "owl_sameAs"
HyfHYWaterbody ||--|o Sf#LineString : "owl_sameAs"
HyfHYWaterbody ||--|o Sf#Polygon : "owl_sameAs"
HyfHYWaterbody ||--|o Sf#MultiPolygon : "owl_sameAs"
HyfHYWaterbody ||--|o HyfHYWaterbody : "owl_sameAs"
HyfHYWaterbody ||--|o RdfList : "owl_sameAs"
HyfHYWaterbody ||--|o GeoFeature : "owl_sameAs"
HyfHYWaterbody ||--|o GeoGeometry : "owl_sameAs"
HyfHYWaterbody ||--|o HyfHYFlowPath : "owl_sameAs"
HyfHYWaterbody ||--|o SchemaPlace : "owl_sameAs"
HyfHYWaterbody ||--|o Gwml22GWAquifer : "owl_sameAs"
HyfHYWaterbody ||--|o RdfObjectProperty : "owl_sameAs"
HyfHYWaterbody ||--|o KwgoS2CellLevel13 : "kwgo_sfCrosses"
HyfHYWaterbody ||--|o OwlThing : "kwgo_sfCrosses"
HyfHYWaterbody ||--|o HyfHYWaterbody : "kwgo_sfCrosses"
HyfHYWaterbody ||--|o HyfHYFlowPath : "kwgo_sfCrosses"
HyfHYWaterbody ||--|o SchemaPlace : "kwgo_sfCrosses"
HyfHYWaterbody ||--|o HyfHYFlowPath : "hyf__downstreamWaterbodyTC"
HyfHYWaterbody ||--|o SchemaPlace : "hyf__downstreamWaterbodyTC"
HyfHYWaterbody ||--|o OwlThing : "hyf__downstreamWaterbodyTC"
HyfHYWaterbody ||--|o HyfHYWaterbody : "hyf__downstreamWaterbodyTC"
HyfHYWaterbody ||--|o HyfHYFlowPath : "hyf__downstreamWaterbody"
HyfHYWaterbody ||--|o SchemaPlace : "hyf__downstreamWaterbody"
HyfHYWaterbody ||--|o OwlThing : "hyf__downstreamWaterbody"
HyfHYWaterbody ||--|o HyfHYWaterbody : "hyf__downstreamWaterbody"
HyfHYWaterbody ||--|o OwlThing : "geo_hasGeometry"
HyfHYWaterbody ||--|o Sf#LineString : "geo_hasGeometry"
HyfHYWaterbody ||--|o Sf#Polygon : "geo_hasGeometry"
HyfHYWaterbody ||--|o Sf#MultiPolygon : "geo_hasGeometry"
HyfHYWaterbody ||--|o GeoGeometry : "geo_hasGeometry"
HyfHYWaterbody ||--|o GeoFeature : "badwdt_P885"
HyfHYWaterbody ||--|o OwlThing : "badwdt_P885"
HyfHYWaterbody ||--|o OwlThing : "geo_defaultGeometry"
HyfHYWaterbody ||--|o Sf#LineString : "geo_defaultGeometry"
HyfHYWaterbody ||--|o Sf#Polygon : "geo_defaultGeometry"
HyfHYWaterbody ||--|o Sf#MultiPolygon : "geo_defaultGeometry"
HyfHYWaterbody ||--|o GeoGeometry : "geo_defaultGeometry"
KwgoS2CellLevel13 ||--|o HyfHYWaterBody : "kwgo_sfWithin"
KwgoS2CellLevel13 ||--|o OwlThing : "kwgo_sfWithin"
KwgoS2CellLevel13 ||--|o Gwml22GWAquifer : "kwgo_sfWithin"
KwgoS2CellLevel13 ||--|o HyfHYWaterBody : "owl_sameAs"
KwgoS2CellLevel13 ||--|o KwgoS2CellLevel13 : "owl_sameAs"
KwgoS2CellLevel13 ||--|o OwlThing : "owl_sameAs"
KwgoS2CellLevel13 ||--|o Sf#LineString : "owl_sameAs"
KwgoS2CellLevel13 ||--|o Sf#Polygon : "owl_sameAs"
KwgoS2CellLevel13 ||--|o Sf#MultiPolygon : "owl_sameAs"
KwgoS2CellLevel13 ||--|o HyfHYWaterbody : "owl_sameAs"
KwgoS2CellLevel13 ||--|o RdfList : "owl_sameAs"
KwgoS2CellLevel13 ||--|o GeoFeature : "owl_sameAs"
KwgoS2CellLevel13 ||--|o GeoGeometry : "owl_sameAs"
KwgoS2CellLevel13 ||--|o HyfHYFlowPath : "owl_sameAs"
KwgoS2CellLevel13 ||--|o SchemaPlace : "owl_sameAs"
KwgoS2CellLevel13 ||--|o Gwml22GWAquifer : "owl_sameAs"
KwgoS2CellLevel13 ||--|o RdfObjectProperty : "owl_sameAs"
KwgoS2CellLevel13 ||--|o HyfHYWaterBody : "kwgo_sfOverlaps"
KwgoS2CellLevel13 ||--|o KwgoS2CellLevel13 : "kwgo_sfOverlaps"
KwgoS2CellLevel13 ||--|o OwlThing : "kwgo_sfOverlaps"
KwgoS2CellLevel13 ||--|o Gwml22GWAquifer : "kwgo_sfOverlaps"
KwgoS2CellLevel13 ||--|o KwgoS2CellLevel13 : "kwgo_sfCrosses"
KwgoS2CellLevel13 ||--|o OwlThing : "kwgo_sfCrosses"
KwgoS2CellLevel13 ||--|o HyfHYWaterbody : "kwgo_sfCrosses"
KwgoS2CellLevel13 ||--|o HyfHYFlowPath : "kwgo_sfCrosses"
KwgoS2CellLevel13 ||--|o SchemaPlace : "kwgo_sfCrosses"
OwlNamedIndividual ||--|o GeoFeature : "badwdt_P403"
OwlNamedIndividual ||--|o OwlThing : "badwdt_P403"
OwlNamedIndividual ||--|o KwgoS2CellLevel13 : "kwgo_sfCrosses"
OwlNamedIndividual ||--|o OwlThing : "kwgo_sfCrosses"
OwlNamedIndividual ||--|o HyfHYWaterbody : "kwgo_sfCrosses"
OwlNamedIndividual ||--|o HyfHYFlowPath : "kwgo_sfCrosses"
OwlNamedIndividual ||--|o SchemaPlace : "kwgo_sfCrosses"
OwlNamedIndividual ||--|o GeoFeature : "badwdt_P885"
OwlNamedIndividual ||--|o OwlThing : "badwdt_P885"
OwlNamedIndividual ||--|o OwlClass : "rdfs_range"
OwlNamedIndividual ||--|o RdfsClass : "rdfs_range"
OwlNamedIndividual ||--|o OwlThing : "rdfs_range"
OwlNamedIndividual ||--|o HyfHYWaterBody : "kwgo_sfWithin"
OwlNamedIndividual ||--|o OwlThing : "kwgo_sfWithin"
OwlNamedIndividual ||--|o Gwml22GWAquifer : "kwgo_sfWithin"
OwlNamedIndividual ||--|o HyfHYWaterBody : "owl_sameAs"
OwlNamedIndividual ||--|o KwgoS2CellLevel13 : "owl_sameAs"
OwlNamedIndividual ||--|o OwlThing : "owl_sameAs"
OwlNamedIndividual ||--|o Sf#LineString : "owl_sameAs"
OwlNamedIndividual ||--|o Sf#Polygon : "owl_sameAs"
OwlNamedIndividual ||--|o Sf#MultiPolygon : "owl_sameAs"
OwlNamedIndividual ||--|o HyfHYWaterbody : "owl_sameAs"
OwlNamedIndividual ||--|o RdfList : "owl_sameAs"
OwlNamedIndividual ||--|o GeoFeature : "owl_sameAs"
OwlNamedIndividual ||--|o GeoGeometry : "owl_sameAs"
OwlNamedIndividual ||--|o HyfHYFlowPath : "owl_sameAs"
OwlNamedIndividual ||--|o SchemaPlace : "owl_sameAs"
OwlNamedIndividual ||--|o Gwml22GWAquifer : "owl_sameAs"
OwlNamedIndividual ||--|o RdfObjectProperty : "owl_sameAs"
OwlNamedIndividual ||--|o HyfHYWaterBody : "kwgo_sfOverlaps"
OwlNamedIndividual ||--|o KwgoS2CellLevel13 : "kwgo_sfOverlaps"
OwlNamedIndividual ||--|o OwlThing : "kwgo_sfOverlaps"
OwlNamedIndividual ||--|o Gwml22GWAquifer : "kwgo_sfOverlaps"
OwlNamedIndividual ||--|o OwlThing : "prov_hadPrimarySource"
OwlNamedIndividual ||--|o HyfHYFlowPath : "hyf__downstreamWaterbody"
OwlNamedIndividual ||--|o SchemaPlace : "hyf__downstreamWaterbody"
OwlNamedIndividual ||--|o OwlThing : "hyf__downstreamWaterbody"
OwlNamedIndividual ||--|o HyfHYWaterbody : "hyf__downstreamWaterbody"
OwlNamedIndividual ||--|o OwlThing : "geo_hasGeometry"
OwlNamedIndividual ||--|o Sf#LineString : "geo_hasGeometry"
OwlNamedIndividual ||--|o Sf#Polygon : "geo_hasGeometry"
OwlNamedIndividual ||--|o Sf#MultiPolygon : "geo_hasGeometry"
OwlNamedIndividual ||--|o GeoGeometry : "geo_hasGeometry"
OwlNamedIndividual ||--|o GeoWktLiteral : "geo_asWKT"
OwlNamedIndividual ||--|o KwgoS2CellLevel13 : "kwgo_sfContains"
OwlNamedIndividual ||--|o OwlThing : "kwgo_sfContains"
OwlNamedIndividual ||--|o HyfHYFlowPath : "hyf__downstreamWaterbodyTC"
OwlNamedIndividual ||--|o SchemaPlace : "hyf__downstreamWaterbodyTC"
OwlNamedIndividual ||--|o OwlThing : "hyf__downstreamWaterbodyTC"
OwlNamedIndividual ||--|o HyfHYWaterbody : "hyf__downstreamWaterbodyTC"
OwlNamedIndividual ||--|o OwlClass : "rdfs_domain"
OwlNamedIndividual ||--|o RdfsClass : "rdfs_domain"
OwlNamedIndividual ||--|o OwlThing : "rdfs_domain"
OwlNamedIndividual ||--|o OwlThing : "geo_defaultGeometry"
OwlNamedIndividual ||--|o Sf#LineString : "geo_defaultGeometry"
OwlNamedIndividual ||--|o Sf#Polygon : "geo_defaultGeometry"
OwlNamedIndividual ||--|o Sf#MultiPolygon : "geo_defaultGeometry"
OwlNamedIndividual ||--|o GeoGeometry : "geo_defaultGeometry"
OwlNothing ||--|o GeoFeature : "badwdt_P403"
OwlNothing ||--|o OwlThing : "badwdt_P403"
OwlNothing ||--|o KwgoS2CellLevel13 : "kwgo_sfCrosses"
OwlNothing ||--|o OwlThing : "kwgo_sfCrosses"
OwlNothing ||--|o HyfHYWaterbody : "kwgo_sfCrosses"
OwlNothing ||--|o HyfHYFlowPath : "kwgo_sfCrosses"
OwlNothing ||--|o SchemaPlace : "kwgo_sfCrosses"
OwlNothing ||--|o GeoFeature : "badwdt_P885"
OwlNothing ||--|o OwlThing : "badwdt_P885"
OwlNothing ||--|o OwlClass : "rdfs_range"
OwlNothing ||--|o RdfsClass : "rdfs_range"
OwlNothing ||--|o OwlThing : "rdfs_range"
OwlNothing ||--|o HyfHYWaterBody : "kwgo_sfWithin"
OwlNothing ||--|o OwlThing : "kwgo_sfWithin"
OwlNothing ||--|o Gwml22GWAquifer : "kwgo_sfWithin"
OwlNothing ||--|o HyfHYWaterBody : "owl_sameAs"
OwlNothing ||--|o KwgoS2CellLevel13 : "owl_sameAs"
OwlNothing ||--|o OwlThing : "owl_sameAs"
OwlNothing ||--|o Sf#LineString : "owl_sameAs"
OwlNothing ||--|o Sf#Polygon : "owl_sameAs"
OwlNothing ||--|o Sf#MultiPolygon : "owl_sameAs"
OwlNothing ||--|o HyfHYWaterbody : "owl_sameAs"
OwlNothing ||--|o RdfList : "owl_sameAs"
OwlNothing ||--|o GeoFeature : "owl_sameAs"
OwlNothing ||--|o GeoGeometry : "owl_sameAs"
OwlNothing ||--|o HyfHYFlowPath : "owl_sameAs"
OwlNothing ||--|o SchemaPlace : "owl_sameAs"
OwlNothing ||--|o Gwml22GWAquifer : "owl_sameAs"
OwlNothing ||--|o RdfObjectProperty : "owl_sameAs"
OwlNothing ||--|o HyfHYWaterBody : "kwgo_sfOverlaps"
OwlNothing ||--|o KwgoS2CellLevel13 : "kwgo_sfOverlaps"
OwlNothing ||--|o OwlThing : "kwgo_sfOverlaps"
OwlNothing ||--|o Gwml22GWAquifer : "kwgo_sfOverlaps"
OwlNothing ||--|o OwlThing : "prov_hadPrimarySource"
OwlNothing ||--|o HyfHYFlowPath : "hyf__downstreamWaterbody"
OwlNothing ||--|o SchemaPlace : "hyf__downstreamWaterbody"
OwlNothing ||--|o OwlThing : "hyf__downstreamWaterbody"
OwlNothing ||--|o HyfHYWaterbody : "hyf__downstreamWaterbody"
OwlNothing ||--|o OwlThing : "geo_hasGeometry"
OwlNothing ||--|o Sf#LineString : "geo_hasGeometry"
OwlNothing ||--|o Sf#Polygon : "geo_hasGeometry"
OwlNothing ||--|o Sf#MultiPolygon : "geo_hasGeometry"
OwlNothing ||--|o GeoGeometry : "geo_hasGeometry"
OwlNothing ||--|o GeoWktLiteral : "geo_asWKT"
OwlNothing ||--|o KwgoS2CellLevel13 : "kwgo_sfContains"
OwlNothing ||--|o OwlThing : "kwgo_sfContains"
OwlNothing ||--|o HyfHYFlowPath : "hyf__downstreamWaterbodyTC"
OwlNothing ||--|o SchemaPlace : "hyf__downstreamWaterbodyTC"
OwlNothing ||--|o OwlThing : "hyf__downstreamWaterbodyTC"
OwlNothing ||--|o HyfHYWaterbody : "hyf__downstreamWaterbodyTC"
OwlNothing ||--|o OwlClass : "rdfs_domain"
OwlNothing ||--|o RdfsClass : "rdfs_domain"
OwlNothing ||--|o OwlThing : "rdfs_domain"
OwlNothing ||--|o OwlThing : "geo_defaultGeometry"
OwlNothing ||--|o Sf#LineString : "geo_defaultGeometry"
OwlNothing ||--|o Sf#Polygon : "geo_defaultGeometry"
OwlNothing ||--|o Sf#MultiPolygon : "geo_defaultGeometry"
OwlNothing ||--|o GeoGeometry : "geo_defaultGeometry"
OwlThing ||--|o GeoFeature : "badwdt_P403"
OwlThing ||--|o OwlThing : "badwdt_P403"
OwlThing ||--|o KwgoS2CellLevel13 : "kwgo_sfCrosses"
OwlThing ||--|o OwlThing : "kwgo_sfCrosses"
OwlThing ||--|o HyfHYWaterbody : "kwgo_sfCrosses"
OwlThing ||--|o HyfHYFlowPath : "kwgo_sfCrosses"
OwlThing ||--|o SchemaPlace : "kwgo_sfCrosses"
OwlThing ||--|o GeoFeature : "badwdt_P885"
OwlThing ||--|o OwlThing : "badwdt_P885"
OwlThing ||--|o OwlClass : "rdfs_range"
OwlThing ||--|o RdfsClass : "rdfs_range"
OwlThing ||--|o OwlThing : "rdfs_range"
OwlThing ||--|o HyfHYWaterBody : "kwgo_sfWithin"
OwlThing ||--|o OwlThing : "kwgo_sfWithin"
OwlThing ||--|o Gwml22GWAquifer : "kwgo_sfWithin"
OwlThing ||--|o HyfHYWaterBody : "owl_sameAs"
OwlThing ||--|o KwgoS2CellLevel13 : "owl_sameAs"
OwlThing ||--|o OwlThing : "owl_sameAs"
OwlThing ||--|o Sf#LineString : "owl_sameAs"
OwlThing ||--|o Sf#Polygon : "owl_sameAs"
OwlThing ||--|o Sf#MultiPolygon : "owl_sameAs"
OwlThing ||--|o HyfHYWaterbody : "owl_sameAs"
OwlThing ||--|o RdfList : "owl_sameAs"
OwlThing ||--|o GeoFeature : "owl_sameAs"
OwlThing ||--|o GeoGeometry : "owl_sameAs"
OwlThing ||--|o HyfHYFlowPath : "owl_sameAs"
OwlThing ||--|o SchemaPlace : "owl_sameAs"
OwlThing ||--|o Gwml22GWAquifer : "owl_sameAs"
OwlThing ||--|o RdfObjectProperty : "owl_sameAs"
OwlThing ||--|o HyfHYWaterBody : "kwgo_sfOverlaps"
OwlThing ||--|o KwgoS2CellLevel13 : "kwgo_sfOverlaps"
OwlThing ||--|o OwlThing : "kwgo_sfOverlaps"
OwlThing ||--|o Gwml22GWAquifer : "kwgo_sfOverlaps"
OwlThing ||--|o OwlThing : "prov_hadPrimarySource"
OwlThing ||--|o HyfHYFlowPath : "hyf__downstreamWaterbody"
OwlThing ||--|o SchemaPlace : "hyf__downstreamWaterbody"
OwlThing ||--|o OwlThing : "hyf__downstreamWaterbody"
OwlThing ||--|o HyfHYWaterbody : "hyf__downstreamWaterbody"
OwlThing ||--|o OwlThing : "geo_hasGeometry"
OwlThing ||--|o Sf#LineString : "geo_hasGeometry"
OwlThing ||--|o Sf#Polygon : "geo_hasGeometry"
OwlThing ||--|o Sf#MultiPolygon : "geo_hasGeometry"
OwlThing ||--|o GeoGeometry : "geo_hasGeometry"
OwlThing ||--|o GeoWktLiteral : "geo_asWKT"
OwlThing ||--|o KwgoS2CellLevel13 : "kwgo_sfContains"
OwlThing ||--|o OwlThing : "kwgo_sfContains"
OwlThing ||--|o HyfHYFlowPath : "hyf__downstreamWaterbodyTC"
OwlThing ||--|o SchemaPlace : "hyf__downstreamWaterbodyTC"
OwlThing ||--|o OwlThing : "hyf__downstreamWaterbodyTC"
OwlThing ||--|o HyfHYWaterbody : "hyf__downstreamWaterbodyTC"
OwlThing ||--|o OwlClass : "rdfs_domain"
OwlThing ||--|o RdfsClass : "rdfs_domain"
OwlThing ||--|o OwlThing : "rdfs_domain"
OwlThing ||--|o OwlThing : "geo_defaultGeometry"
OwlThing ||--|o Sf#LineString : "geo_defaultGeometry"
OwlThing ||--|o Sf#Polygon : "geo_defaultGeometry"
OwlThing ||--|o Sf#MultiPolygon : "geo_defaultGeometry"
OwlThing ||--|o GeoGeometry : "geo_defaultGeometry"
RdfList ||--|o HyfHYWaterBody : "owl_sameAs"
RdfList ||--|o KwgoS2CellLevel13 : "owl_sameAs"
RdfList ||--|o OwlThing : "owl_sameAs"
RdfList ||--|o Sf#LineString : "owl_sameAs"
RdfList ||--|o Sf#Polygon : "owl_sameAs"
RdfList ||--|o Sf#MultiPolygon : "owl_sameAs"
RdfList ||--|o HyfHYWaterbody : "owl_sameAs"
RdfList ||--|o RdfList : "owl_sameAs"
RdfList ||--|o GeoFeature : "owl_sameAs"
RdfList ||--|o GeoGeometry : "owl_sameAs"
RdfList ||--|o HyfHYFlowPath : "owl_sameAs"
RdfList ||--|o SchemaPlace : "owl_sameAs"
RdfList ||--|o Gwml22GWAquifer : "owl_sameAs"
RdfList ||--|o RdfObjectProperty : "owl_sameAs"
RdfObjectProperty ||--|o OwlClass : "rdfs_domain"
RdfObjectProperty ||--|o RdfsClass : "rdfs_domain"
RdfObjectProperty ||--|o OwlThing : "rdfs_domain"
RdfObjectProperty ||--|o HyfHYWaterBody : "owl_sameAs"
RdfObjectProperty ||--|o KwgoS2CellLevel13 : "owl_sameAs"
RdfObjectProperty ||--|o OwlThing : "owl_sameAs"
RdfObjectProperty ||--|o Sf#LineString : "owl_sameAs"
RdfObjectProperty ||--|o Sf#Polygon : "owl_sameAs"
RdfObjectProperty ||--|o Sf#MultiPolygon : "owl_sameAs"
RdfObjectProperty ||--|o HyfHYWaterbody : "owl_sameAs"
RdfObjectProperty ||--|o RdfList : "owl_sameAs"
RdfObjectProperty ||--|o GeoFeature : "owl_sameAs"
RdfObjectProperty ||--|o GeoGeometry : "owl_sameAs"
RdfObjectProperty ||--|o HyfHYFlowPath : "owl_sameAs"
RdfObjectProperty ||--|o SchemaPlace : "owl_sameAs"
RdfObjectProperty ||--|o Gwml22GWAquifer : "owl_sameAs"
RdfObjectProperty ||--|o RdfObjectProperty : "owl_sameAs"
RdfObjectProperty ||--|o OwlClass : "rdfs_range"
RdfObjectProperty ||--|o RdfsClass : "rdfs_range"
RdfObjectProperty ||--|o OwlThing : "rdfs_range"
SchemaPlace ||--|o GeoFeature : "badwdt_P403"
SchemaPlace ||--|o OwlThing : "badwdt_P403"
SchemaPlace ||--|o HyfHYWaterBody : "owl_sameAs"
SchemaPlace ||--|o KwgoS2CellLevel13 : "owl_sameAs"
SchemaPlace ||--|o OwlThing : "owl_sameAs"
SchemaPlace ||--|o Sf#LineString : "owl_sameAs"
SchemaPlace ||--|o Sf#Polygon : "owl_sameAs"
SchemaPlace ||--|o Sf#MultiPolygon : "owl_sameAs"
SchemaPlace ||--|o HyfHYWaterbody : "owl_sameAs"
SchemaPlace ||--|o RdfList : "owl_sameAs"
SchemaPlace ||--|o GeoFeature : "owl_sameAs"
SchemaPlace ||--|o GeoGeometry : "owl_sameAs"
SchemaPlace ||--|o HyfHYFlowPath : "owl_sameAs"
SchemaPlace ||--|o SchemaPlace : "owl_sameAs"
SchemaPlace ||--|o Gwml22GWAquifer : "owl_sameAs"
SchemaPlace ||--|o RdfObjectProperty : "owl_sameAs"
SchemaPlace ||--|o KwgoS2CellLevel13 : "kwgo_sfCrosses"
SchemaPlace ||--|o OwlThing : "kwgo_sfCrosses"
SchemaPlace ||--|o HyfHYWaterbody : "kwgo_sfCrosses"
SchemaPlace ||--|o HyfHYFlowPath : "kwgo_sfCrosses"
SchemaPlace ||--|o SchemaPlace : "kwgo_sfCrosses"
SchemaPlace ||--|o HyfHYFlowPath : "hyf__downstreamWaterbodyTC"
SchemaPlace ||--|o SchemaPlace : "hyf__downstreamWaterbodyTC"
SchemaPlace ||--|o OwlThing : "hyf__downstreamWaterbodyTC"
SchemaPlace ||--|o HyfHYWaterbody : "hyf__downstreamWaterbodyTC"
SchemaPlace ||--|o HyfHYFlowPath : "hyf__downstreamWaterbody"
SchemaPlace ||--|o SchemaPlace : "hyf__downstreamWaterbody"
SchemaPlace ||--|o OwlThing : "hyf__downstreamWaterbody"
SchemaPlace ||--|o HyfHYWaterbody : "hyf__downstreamWaterbody"
SchemaPlace ||--|o OwlThing : "geo_hasGeometry"
SchemaPlace ||--|o Sf#LineString : "geo_hasGeometry"
SchemaPlace ||--|o Sf#Polygon : "geo_hasGeometry"
SchemaPlace ||--|o Sf#MultiPolygon : "geo_hasGeometry"
SchemaPlace ||--|o GeoGeometry : "geo_hasGeometry"
SchemaPlace ||--|o GeoFeature : "badwdt_P885"
SchemaPlace ||--|o OwlThing : "badwdt_P885"
SchemaPlace ||--|o OwlThing : "geo_defaultGeometry"
SchemaPlace ||--|o Sf#LineString : "geo_defaultGeometry"
SchemaPlace ||--|o Sf#Polygon : "geo_defaultGeometry"
SchemaPlace ||--|o Sf#MultiPolygon : "geo_defaultGeometry"
SchemaPlace ||--|o GeoGeometry : "geo_defaultGeometry"
Sf#LineString ||--|o GeoWktLiteral : "geo_asWKT"
Sf#LineString ||--|o HyfHYWaterBody : "owl_sameAs"
Sf#LineString ||--|o KwgoS2CellLevel13 : "owl_sameAs"
Sf#LineString ||--|o OwlThing : "owl_sameAs"
Sf#LineString ||--|o Sf#LineString : "owl_sameAs"
Sf#LineString ||--|o Sf#Polygon : "owl_sameAs"
Sf#LineString ||--|o Sf#MultiPolygon : "owl_sameAs"
Sf#LineString ||--|o HyfHYWaterbody : "owl_sameAs"
Sf#LineString ||--|o RdfList : "owl_sameAs"
Sf#LineString ||--|o GeoFeature : "owl_sameAs"
Sf#LineString ||--|o GeoGeometry : "owl_sameAs"
Sf#LineString ||--|o HyfHYFlowPath : "owl_sameAs"
Sf#LineString ||--|o SchemaPlace : "owl_sameAs"
Sf#LineString ||--|o Gwml22GWAquifer : "owl_sameAs"
Sf#LineString ||--|o RdfObjectProperty : "owl_sameAs"
Sf#MultiPolygon ||--|o GeoWktLiteral : "geo_asWKT"
Sf#MultiPolygon ||--|o HyfHYWaterBody : "owl_sameAs"
Sf#MultiPolygon ||--|o KwgoS2CellLevel13 : "owl_sameAs"
Sf#MultiPolygon ||--|o OwlThing : "owl_sameAs"
Sf#MultiPolygon ||--|o Sf#LineString : "owl_sameAs"
Sf#MultiPolygon ||--|o Sf#Polygon : "owl_sameAs"
Sf#MultiPolygon ||--|o Sf#MultiPolygon : "owl_sameAs"
Sf#MultiPolygon ||--|o HyfHYWaterbody : "owl_sameAs"
Sf#MultiPolygon ||--|o RdfList : "owl_sameAs"
Sf#MultiPolygon ||--|o GeoFeature : "owl_sameAs"
Sf#MultiPolygon ||--|o GeoGeometry : "owl_sameAs"
Sf#MultiPolygon ||--|o HyfHYFlowPath : "owl_sameAs"
Sf#MultiPolygon ||--|o SchemaPlace : "owl_sameAs"
Sf#MultiPolygon ||--|o Gwml22GWAquifer : "owl_sameAs"
Sf#MultiPolygon ||--|o RdfObjectProperty : "owl_sameAs"
Sf#Polygon ||--|o GeoWktLiteral : "geo_asWKT"
Sf#Polygon ||--|o HyfHYWaterBody : "owl_sameAs"
Sf#Polygon ||--|o KwgoS2CellLevel13 : "owl_sameAs"
Sf#Polygon ||--|o OwlThing : "owl_sameAs"
Sf#Polygon ||--|o Sf#LineString : "owl_sameAs"
Sf#Polygon ||--|o Sf#Polygon : "owl_sameAs"
Sf#Polygon ||--|o Sf#MultiPolygon : "owl_sameAs"
Sf#Polygon ||--|o HyfHYWaterbody : "owl_sameAs"
Sf#Polygon ||--|o RdfList : "owl_sameAs"
Sf#Polygon ||--|o GeoFeature : "owl_sameAs"
Sf#Polygon ||--|o GeoGeometry : "owl_sameAs"
Sf#Polygon ||--|o HyfHYFlowPath : "owl_sameAs"
Sf#Polygon ||--|o SchemaPlace : "owl_sameAs"
Sf#Polygon ||--|o Gwml22GWAquifer : "owl_sameAs"
Sf#Polygon ||--|o RdfObjectProperty : "owl_sameAs"

```



## Classes

| Class | Description | Occurrences |
| --- | --- | --- |
| [GeoFeature](classes/GeoFeature.md) | No class (type) description specified<br/>| 137674 | 
| [GeoGeometry](classes/GeoGeometry.md) | No class (type) description specified<br/>| 86884 | 
| [GeoWktLiteral](classes/GeoWktLiteral.md) | No class (type) description specified<br/>| 0 | 
| [Gwml22GWAquifer](classes/Gwml22GWAquifer.md) | No class (type) description specified<br/>| 1256 | 
| [HyfHYFlowPath](classes/HyfHYFlowPath.md) | No class (type) description specified<br/>| 68837 | 
| [HyfHYWaterbody](classes/HyfHYWaterbody.md) | No class (type) description specified<br/>| 68837 | 
| [HyfHYWaterBody](classes/HyfHYWaterBody.md) | No class (type) description specified<br/>| 16791 | 
| [KwgoS2CellLevel13](classes/KwgoS2CellLevel13.md) | No class (type) description specified<br/>| 86332 | 
| [OwlObjectProperty](classes/OwlObjectProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlAsymmetricProperty](classes/OwlAsymmetricProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlInverseFunctionalProperty](classes/OwlInverseFunctionalProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlIrreflexiveProperty](classes/OwlIrreflexiveProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlReflexiveProperty](classes/OwlReflexiveProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlSymmetricProperty](classes/OwlSymmetricProperty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[OwlTransitiveProperty](classes/OwlTransitiveProperty.md) | No class (type) description specified<br/>| 0 | 
| [OwlThing](classes/OwlThing.md) | No class (type) description specified<br/>| 586186 | 
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
| [SchemaPlace](classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension.<br/>| 68837 | 
| [Sf#LineString](classes/Sf#LineString.md) | No class (type) description specified<br/>| 68837 | 
| [Sf#MultiPolygon](classes/Sf#MultiPolygon.md) | No class (type) description specified<br/>| 16803 | 
| [Sf#Polygon](classes/Sf#Polygon.md) | No class (type) description specified<br/>| 1244 | 





## Slots

| Slot | Description | Occurrences |
| --- | --- | --- |
| [badwdt_P2043](slots/badwdt_P2043.md) | No slot (predicate) description specified<br/>| 68837 |
| [badwdt_P403](slots/badwdt_P403.md) | No slot (predicate) description specified<br/>| 68837 |
| [badwdt_P885](slots/badwdt_P885.md) | No slot (predicate) description specified<br/>| 68837 |
| [geo_asWKT](slots/geo_asWKT.md) | No slot (predicate) description specified<br/>| 224558 |
| [geo_defaultGeometry](slots/geo_defaultGeometry.md) | No slot (predicate) description specified<br/>| 224558 |
| [geo_hasGeometry](slots/geo_hasGeometry.md) | No slot (predicate) description specified<br/>| 224558 |
| [hyf__downstreamWaterbody](slots/hyf__downstreamWaterbody.md) | No slot (predicate) description specified<br/>| 137664 |
| [hyf__downstreamWaterbodyTC](slots/hyf__downstreamWaterbodyTC.md) | No slot (predicate) description specified<br/>| 66190279 |
| [kwgo_sfContains](slots/kwgo_sfContains.md) | No slot (predicate) description specified<br/>| 395 |
| [kwgo_sfCrosses](slots/kwgo_sfCrosses.md) | No slot (predicate) description specified<br/>| 395346 |
| [kwgo_sfOverlaps](slots/kwgo_sfOverlaps.md) | No slot (predicate) description specified<br/>| 55755 |
| [kwgo_sfWithin](slots/kwgo_sfWithin.md) | No slot (predicate) description specified<br/>| 906 |
| [memgs2_SAWidAquifer](slots/memgs2_SAWidAquifer.md) | No slot (predicate) description specified<br/>| 1256 |
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
| [owl_sameAs](slots/owl_sameAs.md) | No slot (predicate) description specified<br/>| 586186 |
| [owl_someValuesFrom](slots/owl_someValuesFrom.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_sourceIndividual](slots/owl_sourceIndividual.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_targetIndividual](slots/owl_targetIndividual.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_targetValue](slots/owl_targetValue.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_topDataProperty](slots/owl_topDataProperty.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_unionOf](slots/owl_unionOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_versionInfo](slots/owl_versionInfo.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_versionIRI](slots/owl_versionIRI.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [owl_withRestrictions](slots/owl_withRestrictions.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [prov_hadPrimarySource](slots/prov_hadPrimarySource.md) | No slot (predicate) description specified<br/>| 1256 |
| [rdf__1](slots/rdf__1.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_first](slots/rdf_first.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_langRange](slots/rdf_langRange.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_object](slots/rdf_object.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_predicate](slots/rdf_predicate.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_rest](slots/rdf_rest.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_subject](slots/rdf_subject.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_type](slots/rdf_type.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdf_value](slots/rdf_value.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdfs_comment](slots/rdfs_comment.md) | No slot (predicate) description specified<br/>| 51629 |
| [rdfs_domain](slots/rdfs_domain.md) | No slot (predicate) description specified<br/>| 1 |
| [rdfs_isDefinedBy](slots/rdfs_isDefinedBy.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdfs_label](slots/rdfs_label.md) | No slot (predicate) description specified<br/>| 16791 |
| [rdfs_range](slots/rdfs_range.md) | No slot (predicate) description specified<br/>| 1 |
| [rdfs_seeAlso](slots/rdfs_seeAlso.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdfs_subClassOf](slots/rdfs_subClassOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [rdfs_subPropertyOf](slots/rdfs_subPropertyOf.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [sawwater_hasCOMID](slots/sawwater_hasCOMID.md) | No slot (predicate) description specified<br/>| 68837 |
| [sawwater_hasFCODE](slots/sawwater_hasFCODE.md) | No slot (predicate) description specified<br/>| 68837 |
| [sawwater_hasFTYPE](slots/sawwater_hasFTYPE.md) | No slot (predicate) description specified<br/>| 68837 |
| [sawwater_hasReachCode](slots/sawwater_hasReachCode.md) | No slot (predicate) description specified<br/>| 68837 |
| [schema_name](slots/schema_name.md) | The name of the item<br/>| 33928 |
| [xsd_length](slots/xsd_length.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_maxExclusive](slots/xsd_maxExclusive.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_maxInclusive](slots/xsd_maxInclusive.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_maxLength](slots/xsd_maxLength.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_minExclusive](slots/xsd_minExclusive.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_minInclusive](slots/xsd_minInclusive.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_minLength](slots/xsd_minLength.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [xsd_pattern](slots/xsd_pattern.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |









## IRI prefixes

* badwdt: https://www.wikidata.org/wiki/Property:
* geo: http://www.opengis.net/ont/geosparql#
* gwml22: http://www.opengis.net/gwml-main/2.2/
* hyf: https://www.opengis.net/def/schema/hy_features/hyf
* kwgo: http://stko-kwg.geog.ucsb.edu/lod/ontology/
* kwgr: http://stko-kwg.geog.ucsb.edu/lod/resource/
* linkml: https://w3id.org/linkml/
* memgs2: http://sawgraph.spatialai.org/v1/me_mgs#
* owl: http://www.w3.org/2002/07/owl#
* prov: http://www.w3.org/ns/prov#
* rdf: http://www.w3.org/1999/02/22-rdf-syntax-ns#
* rdfs: http://www.w3.org/2000/01/rdf-schema#
* sawwater: http://sawgraph.spatialai.org/v1/saw_water#
* schema: https://schema.org/
* sf: http://www.opengis.net/ont/sf
* xsd: http://www.w3.org/2001/XMLSchema#
* shex: http://www.w3.org/ns/shex#
