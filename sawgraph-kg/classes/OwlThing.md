

# Class: Thing (owl_Thing)


_The class of OWL individuals._






This class occurs 14758 times.


URI: [owl:Thing](http://www.w3.org/2002/07/owl#Thing)






```mermaid
 classDiagram
    class OwlThing
    click OwlThing href "../OwlThing"
      OwlThing <|-- OwlNamedIndividual
        click OwlNamedIndividual href "../OwlNamedIndividual"
      OwlThing <|-- OwlNothing
        click OwlNothing href "../OwlNothing"
      OwlThing <|-- QudtComment
        click QudtComment href "../QudtComment"
      OwlThing <|-- QudtConcept
        click QudtConcept href "../QudtConcept"
      OwlThing <|-- ProvSoftwareAgent
        click ProvSoftwareAgent href "../ProvSoftwareAgent"
      OwlThing <|-- DtypeEnumeratedValue
        click DtypeEnumeratedValue href "../DtypeEnumeratedValue"
      OwlThing <|-- DtypeEnumeration
        click DtypeEnumeration href "../DtypeEnumeration"
      OwlThing <|-- DtypeValueReference
        click DtypeValueReference href "../DtypeValueReference"
      OwlThing <|-- VaemDimension
        click VaemDimension href "../VaemDimension"
      OwlThing <|-- VaemGraphMetaData
        click VaemGraphMetaData href "../VaemGraphMetaData"
      OwlThing <|-- VaemGraphRole
        click VaemGraphRole href "../VaemGraphRole"
      OwlThing <|-- VaemParty
        click VaemParty href "../VaemParty"
      OwlThing <|-- TimeDayOfWeek
        click TimeDayOfWeek href "../TimeDayOfWeek"
      OwlThing <|-- TimeTemporalEntity
        click TimeTemporalEntity href "../TimeTemporalEntity"
      OwlThing <|-- FoafOnlineAccount
        click FoafOnlineAccount href "../FoafOnlineAccount"
      OwlThing <|-- VoagAssignedRole
        click VoagAssignedRole href "../VoagAssignedRole"
      OwlThing <|-- VoagCreativeCommonsJurisdiction
        click VoagCreativeCommonsJurisdiction href "../VoagCreativeCommonsJurisdiction"
      OwlThing <|-- VoagCreativeCommonsWork
        click VoagCreativeCommonsWork href "../VoagCreativeCommonsWork"
      OwlThing <|-- VoagDocument
        click VoagDocument href "../VoagDocument"
      OwlThing <|-- VoagEvent
        click VoagEvent href "../VoagEvent"
      OwlThing <|-- VoagImage
        click VoagImage href "../VoagImage"
      OwlThing <|-- VoagIssue
        click VoagIssue href "../VoagIssue"
      OwlThing <|-- VoagProcess
        click VoagProcess href "../VoagProcess"
      OwlThing <|-- VoagQualifier
        click VoagQualifier href "../VoagQualifier"
      OwlThing <|-- VoagService
        click VoagService href "../VoagService"
      OwlThing <|-- CosoDetectQuantityValue
        click CosoDetectQuantityValue href "../CosoDetectQuantityValue"
      OwlThing <|-- CosoDetectionLimit
        click CosoDetectionLimit href "../CosoDetectionLimit"
      OwlThing <|-- CosoFeatureType
        click CosoFeatureType href "../CosoFeatureType"
      OwlThing <|-- CosoNonDetectQuantityValue
        click CosoNonDetectQuantityValue href "../CosoNonDetectQuantityValue"
      OwlThing <|-- CosoObservationAnnotation
        click CosoObservationAnnotation href "../CosoObservationAnnotation"
      OwlThing <|-- CosoQuantitationLimit
        click CosoQuantitationLimit href "../CosoQuantitationLimit"
      OwlThing <|-- CosoQuantityValue
        click CosoQuantityValue href "../CosoQuantityValue"
      OwlThing <|-- CosoResultQualifier
        click CosoResultQualifier href "../CosoResultQualifier"
      OwlThing <|-- CosoSampleAnnotation
        click CosoSampleAnnotation href "../CosoSampleAnnotation"
      OwlThing <|-- CosoSampleMaterialType
        click CosoSampleMaterialType href "../CosoSampleMaterialType"
      OwlThing <|-- CosoSubstance
        click CosoSubstance href "../CosoSubstance"
      OwlThing <|-- CosoSubstanceCollection
        click CosoSubstanceCollection href "../CosoSubstanceCollection"
      OwlThing <|-- CosoOfComptoxSubstance
        click CosoOfComptoxSubstance href "../CosoOfComptoxSubstance"
      OwlThing <|-- CosoOfDatasetSubstance
        click CosoOfDatasetSubstance href "../CosoOfDatasetSubstance"
      OwlThing <|-- HttpW3id.orgComptoxCompToxChemicalEntity
        click HttpW3id.orgComptoxCompToxChemicalEntity href "../HttpW3id.orgComptoxCompToxChemicalEntity"
      OwlThing <|-- HttpW3id.orgSawgraphV1Me-egad#EGAD-ConcentrationQualifier
        click HttpW3id.orgSawgraphV1Me-egad#EGAD-ConcentrationQualifier href "../HttpW3id.orgSawgraphV1Me-egad#EGAD-ConcentrationQualifier"
      OwlThing <|-- HttpW3id.orgSawgraphV1Me-egad#EGAD-MethodDetectionLimit
        click HttpW3id.orgSawgraphV1Me-egad#EGAD-MethodDetectionLimit href "../HttpW3id.orgSawgraphV1Me-egad#EGAD-MethodDetectionLimit"
      OwlThing <|-- HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName
        click HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName href "../HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName"
      OwlThing <|-- HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit
        click HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit href "../HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit"
      OwlThing <|-- HttpW3id.orgSawgraphV1Me-egad#EGAD-ResultType
        click HttpW3id.orgSawgraphV1Me-egad#EGAD-ResultType href "../HttpW3id.orgSawgraphV1Me-egad#EGAD-ResultType"
      OwlThing <|-- HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleCollectionMethod
        click HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleCollectionMethod href "../HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleCollectionMethod"
      OwlThing <|-- HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleDetailedLocation
        click HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleDetailedLocation href "../HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleDetailedLocation"
      OwlThing <|-- HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialType
        click HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialType href "../HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialType"
      OwlThing <|-- HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialTypeQualifier
        click HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialTypeQualifier href "../HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialTypeQualifier"
      OwlThing <|-- HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePointType
        click HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePointType href "../HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePointType"
      OwlThing <|-- HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleTreatmentStatus
        click HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleTreatmentStatus href "../HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleTreatmentStatus"
      OwlThing <|-- HttpW3id.orgSawgraphV1Me-egad#EGAD-SiteType
        click HttpW3id.orgSawgraphV1Me-egad#EGAD-SiteType href "../HttpW3id.orgSawgraphV1Me-egad#EGAD-SiteType"
      OwlThing <|-- HttpW3id.orgSawgraphV1Me-egad#EGAD-ValidationLevel
        click HttpW3id.orgSawgraphV1Me-egad#EGAD-ValidationLevel href "../HttpW3id.orgSawgraphV1Me-egad#EGAD-ValidationLevel"
      OwlThing <|-- KwgoS2CellLevel13
        click KwgoS2CellLevel13 href "../KwgoS2CellLevel13"
      OwlThing <|-- KwgoStatisticalArea
        click KwgoStatisticalArea href "../KwgoStatisticalArea"
      OwlThing <|-- MeEgadEGAD-ConcentrationQualifier
        click MeEgadEGAD-ConcentrationQualifier href "../MeEgadEGAD-ConcentrationQualifier"
      OwlThing <|-- MeEgadEGAD-MethodDetectionLimit
        click MeEgadEGAD-MethodDetectionLimit href "../MeEgadEGAD-MethodDetectionLimit"
      OwlThing <|-- MeEgadEGAD-PFAS-ParameterName
        click MeEgadEGAD-PFAS-ParameterName href "../MeEgadEGAD-PFAS-ParameterName"
      OwlThing <|-- MeEgadEGAD-ReportingLimit
        click MeEgadEGAD-ReportingLimit href "../MeEgadEGAD-ReportingLimit"
      OwlThing <|-- MeEgadEGAD-ResultType
        click MeEgadEGAD-ResultType href "../MeEgadEGAD-ResultType"
      OwlThing <|-- MeEgadEGAD-SampleCollectionMethod
        click MeEgadEGAD-SampleCollectionMethod href "../MeEgadEGAD-SampleCollectionMethod"
      OwlThing <|-- MeEgadEGAD-SampleDetailedLocation
        click MeEgadEGAD-SampleDetailedLocation href "../MeEgadEGAD-SampleDetailedLocation"
      OwlThing <|-- MeEgadEGAD-SampleMaterialType
        click MeEgadEGAD-SampleMaterialType href "../MeEgadEGAD-SampleMaterialType"
      OwlThing <|-- MeEgadEGAD-SampleMaterialTypeQualifier
        click MeEgadEGAD-SampleMaterialTypeQualifier href "../MeEgadEGAD-SampleMaterialTypeQualifier"
      OwlThing <|-- MeEgadEGAD-SamplePointType
        click MeEgadEGAD-SamplePointType href "../MeEgadEGAD-SamplePointType"
      OwlThing <|-- MeEgadEGAD-SampleTreatmentStatus
        click MeEgadEGAD-SampleTreatmentStatus href "../MeEgadEGAD-SampleTreatmentStatus"
      OwlThing <|-- MeEgadEGAD-SiteType
        click MeEgadEGAD-SiteType href "../MeEgadEGAD-SiteType"
      OwlThing <|-- MeEgadEGAD-ValidationLevel
        click MeEgadEGAD-ValidationLevel href "../MeEgadEGAD-ValidationLevel"
      OwlThing <|-- OboBFO0000040
        click OboBFO0000040 href "../OboBFO0000040"
      OwlThing <|-- OboFOODON00001002
        click OboFOODON00001002 href "../OboFOODON00001002"
      OwlThing <|-- OboFOODON00001006
        click OboFOODON00001006 href "../OboFOODON00001006"
      OwlThing <|-- OboFOODON00001015
        click OboFOODON00001015 href "../OboFOODON00001015"
      OwlThing <|-- OboFOODON00001040
        click OboFOODON00001040 href "../OboFOODON00001040"
      OwlThing <|-- OboFOODON00001041
        click OboFOODON00001041 href "../OboFOODON00001041"
      OwlThing <|-- OboFOODON00001046
        click OboFOODON00001046 href "../OboFOODON00001046"
      OwlThing <|-- OboFOODON00001057
        click OboFOODON00001057 href "../OboFOODON00001057"
      OwlThing <|-- OboFOODON00001092
        click OboFOODON00001092 href "../OboFOODON00001092"
      OwlThing <|-- OboFOODON00001093
        click OboFOODON00001093 href "../OboFOODON00001093"
      OwlThing <|-- OboFOODON00001105
        click OboFOODON00001105 href "../OboFOODON00001105"
      OwlThing <|-- OboFOODON00001131
        click OboFOODON00001131 href "../OboFOODON00001131"
      OwlThing <|-- OboFOODON00001134
        click OboFOODON00001134 href "../OboFOODON00001134"
      OwlThing <|-- OboFOODON00001147
        click OboFOODON00001147 href "../OboFOODON00001147"
      OwlThing <|-- OboFOODON00001172
        click OboFOODON00001172 href "../OboFOODON00001172"
      OwlThing <|-- OboFOODON00001173
        click OboFOODON00001173 href "../OboFOODON00001173"
      OwlThing <|-- OboFOODON00001175
        click OboFOODON00001175 href "../OboFOODON00001175"
      OwlThing <|-- OboFOODON00001176
        click OboFOODON00001176 href "../OboFOODON00001176"
      OwlThing <|-- OboFOODON00001209
        click OboFOODON00001209 href "../OboFOODON00001209"
      OwlThing <|-- OboFOODON00001242
        click OboFOODON00001242 href "../OboFOODON00001242"
      OwlThing <|-- OboFOODON00001248
        click OboFOODON00001248 href "../OboFOODON00001248"
      OwlThing <|-- OboFOODON00001250
        click OboFOODON00001250 href "../OboFOODON00001250"
      OwlThing <|-- OboFOODON00001251
        click OboFOODON00001251 href "../OboFOODON00001251"
      OwlThing <|-- OboFOODON00001256
        click OboFOODON00001256 href "../OboFOODON00001256"
      OwlThing <|-- OboFOODON00001257
        click OboFOODON00001257 href "../OboFOODON00001257"
      OwlThing <|-- OboFOODON00001261
        click OboFOODON00001261 href "../OboFOODON00001261"
      OwlThing <|-- OboFOODON00001262
        click OboFOODON00001262 href "../OboFOODON00001262"
      OwlThing <|-- OboFOODON00001264
        click OboFOODON00001264 href "../OboFOODON00001264"
      OwlThing <|-- OboFOODON00001274
        click OboFOODON00001274 href "../OboFOODON00001274"
      OwlThing <|-- OboFOODON00001275
        click OboFOODON00001275 href "../OboFOODON00001275"
      OwlThing <|-- OboFOODON00001283
        click OboFOODON00001283 href "../OboFOODON00001283"
      OwlThing <|-- OboFOODON00001291
        click OboFOODON00001291 href "../OboFOODON00001291"
      OwlThing <|-- OboFOODON00001293
        click OboFOODON00001293 href "../OboFOODON00001293"
      OwlThing <|-- OboFOODON00001628
        click OboFOODON00001628 href "../OboFOODON00001628"
      OwlThing <|-- OboFOODON00001635
        click OboFOODON00001635 href "../OboFOODON00001635"
      OwlThing <|-- OboFOODON00001678
        click OboFOODON00001678 href "../OboFOODON00001678"
      OwlThing <|-- OboFOODON00001783
        click OboFOODON00001783 href "../OboFOODON00001783"
      OwlThing <|-- OboFOODON00001792
        click OboFOODON00001792 href "../OboFOODON00001792"
      OwlThing <|-- OboFOODON00002044
        click OboFOODON00002044 href "../OboFOODON00002044"
      OwlThing <|-- OboFOODON00002051
        click OboFOODON00002051 href "../OboFOODON00002051"
      OwlThing <|-- OboFOODON00002140
        click OboFOODON00002140 href "../OboFOODON00002140"
      OwlThing <|-- OboFOODON00002142
        click OboFOODON00002142 href "../OboFOODON00002142"
      OwlThing <|-- OboFOODON00002143
        click OboFOODON00002143 href "../OboFOODON00002143"
      OwlThing <|-- OboFOODON00002147
        click OboFOODON00002147 href "../OboFOODON00002147"
      OwlThing <|-- OboFOODON00002150
        click OboFOODON00002150 href "../OboFOODON00002150"
      OwlThing <|-- OboFOODON00002153
        click OboFOODON00002153 href "../OboFOODON00002153"
      OwlThing <|-- OboFOODON00002156
        click OboFOODON00002156 href "../OboFOODON00002156"
      OwlThing <|-- OboFOODON00002159
        click OboFOODON00002159 href "../OboFOODON00002159"
      OwlThing <|-- OboFOODON00002165
        click OboFOODON00002165 href "../OboFOODON00002165"
      OwlThing <|-- OboFOODON00002236
        click OboFOODON00002236 href "../OboFOODON00002236"
      OwlThing <|-- OboFOODON00002265
        click OboFOODON00002265 href "../OboFOODON00002265"
      OwlThing <|-- OboFOODON00002309
        click OboFOODON00002309 href "../OboFOODON00002309"
      OwlThing <|-- OboFOODON00002381
        click OboFOODON00002381 href "../OboFOODON00002381"
      OwlThing <|-- OboFOODON00002403
        click OboFOODON00002403 href "../OboFOODON00002403"
      OwlThing <|-- OboFOODON00002452
        click OboFOODON00002452 href "../OboFOODON00002452"
      OwlThing <|-- OboFOODON00002477
        click OboFOODON00002477 href "../OboFOODON00002477"
      OwlThing <|-- OboFOODON00002576
        click OboFOODON00002576 href "../OboFOODON00002576"
      OwlThing <|-- OboFOODON00002581
        click OboFOODON00002581 href "../OboFOODON00002581"
      OwlThing <|-- OboFOODON00002616
        click OboFOODON00002616 href "../OboFOODON00002616"
      OwlThing <|-- OboFOODON00002689
        click OboFOODON00002689 href "../OboFOODON00002689"
      OwlThing <|-- OboFOODON00002753
        click OboFOODON00002753 href "../OboFOODON00002753"
      OwlThing <|-- OboFOODON00002765
        click OboFOODON00002765 href "../OboFOODON00002765"
      OwlThing <|-- OboFOODON00002819
        click OboFOODON00002819 href "../OboFOODON00002819"
      OwlThing <|-- OboFOODON00003004
        click OboFOODON00003004 href "../OboFOODON00003004"
      OwlThing <|-- OboFOODON00003042
        click OboFOODON00003042 href "../OboFOODON00003042"
      OwlThing <|-- OboFOODON00003083
        click OboFOODON00003083 href "../OboFOODON00003083"
      OwlThing <|-- OboFOODON00003204
        click OboFOODON00003204 href "../OboFOODON00003204"
      OwlThing <|-- OboFOODON00003425
        click OboFOODON00003425 href "../OboFOODON00003425"
      OwlThing <|-- OboFOODON00003567
        click OboFOODON00003567 href "../OboFOODON00003567"
      OwlThing <|-- OboFOODON00003572
        click OboFOODON00003572 href "../OboFOODON00003572"
      OwlThing <|-- OboFOODON00003814
        click OboFOODON00003814 href "../OboFOODON00003814"
      OwlThing <|-- OboFOODON00003816
        click OboFOODON00003816 href "../OboFOODON00003816"
      OwlThing <|-- OboFOODON00004172
        click OboFOODON00004172 href "../OboFOODON00004172"
      OwlThing <|-- OboFOODON00004183
        click OboFOODON00004183 href "../OboFOODON00004183"
      OwlThing <|-- OboFOODON00004242
        click OboFOODON00004242 href "../OboFOODON00004242"
      OwlThing <|-- OboFOODON00004298
        click OboFOODON00004298 href "../OboFOODON00004298"
      OwlThing <|-- OboFOODON00004331
        click OboFOODON00004331 href "../OboFOODON00004331"
      OwlThing <|-- OboFOODON00004332
        click OboFOODON00004332 href "../OboFOODON00004332"
      OwlThing <|-- OboFOODON00004333
        click OboFOODON00004333 href "../OboFOODON00004333"
      OwlThing <|-- OboFOODON00004436
        click OboFOODON00004436 href "../OboFOODON00004436"
      OwlThing <|-- OboFOODON00004460
        click OboFOODON00004460 href "../OboFOODON00004460"
      OwlThing <|-- OboFOODON00004859
        click OboFOODON00004859 href "../OboFOODON00004859"
      OwlThing <|-- OboFOODON00004862
        click OboFOODON00004862 href "../OboFOODON00004862"
      OwlThing <|-- OboFOODON00004918
        click OboFOODON00004918 href "../OboFOODON00004918"
      OwlThing <|-- OboFOODON00004921
        click OboFOODON00004921 href "../OboFOODON00004921"
      OwlThing <|-- OboFOODON02010001
        click OboFOODON02010001 href "../OboFOODON02010001"
      OwlThing <|-- OboFOODON02010005
        click OboFOODON02010005 href "../OboFOODON02010005"
      OwlThing <|-- OboFOODON02010006
        click OboFOODON02010006 href "../OboFOODON02010006"
      OwlThing <|-- OboFOODON02010012
        click OboFOODON02010012 href "../OboFOODON02010012"
      OwlThing <|-- OboFOODON02010013
        click OboFOODON02010013 href "../OboFOODON02010013"
      OwlThing <|-- OboFOODON02010014
        click OboFOODON02010014 href "../OboFOODON02010014"
      OwlThing <|-- OboFOODON02010015
        click OboFOODON02010015 href "../OboFOODON02010015"
      OwlThing <|-- OboFOODON02010024
        click OboFOODON02010024 href "../OboFOODON02010024"
      OwlThing <|-- OboFOODON02010028
        click OboFOODON02010028 href "../OboFOODON02010028"
      OwlThing <|-- OboFOODON02010029
        click OboFOODON02010029 href "../OboFOODON02010029"
      OwlThing <|-- OboFOODON02010030
        click OboFOODON02010030 href "../OboFOODON02010030"
      OwlThing <|-- OboFOODON02010031
        click OboFOODON02010031 href "../OboFOODON02010031"
      OwlThing <|-- OboFOODON02010032
        click OboFOODON02010032 href "../OboFOODON02010032"
      OwlThing <|-- OboFOODON02010033
        click OboFOODON02010033 href "../OboFOODON02010033"
      OwlThing <|-- OboFOODON02010042
        click OboFOODON02010042 href "../OboFOODON02010042"
      OwlThing <|-- OboFOODON02010045
        click OboFOODON02010045 href "../OboFOODON02010045"
      OwlThing <|-- OboFOODON02010107
        click OboFOODON02010107 href "../OboFOODON02010107"
      OwlThing <|-- OboFOODON02010108
        click OboFOODON02010108 href "../OboFOODON02010108"
      OwlThing <|-- OboFOODON02010111
        click OboFOODON02010111 href "../OboFOODON02010111"
      OwlThing <|-- OboFOODON02010112
        click OboFOODON02010112 href "../OboFOODON02010112"
      OwlThing <|-- OboFOODON02020840
        click OboFOODON02020840 href "../OboFOODON02020840"
      OwlThing <|-- OboFOODON02020892
        click OboFOODON02020892 href "../OboFOODON02020892"
      OwlThing <|-- OboFOODON02021651
        click OboFOODON02021651 href "../OboFOODON02021651"
      OwlThing <|-- OboFOODON02021802
        click OboFOODON02021802 href "../OboFOODON02021802"
      OwlThing <|-- OboFOODON02021803
        click OboFOODON02021803 href "../OboFOODON02021803"
      OwlThing <|-- OboFOODON03301293
        click OboFOODON03301293 href "../OboFOODON03301293"
      OwlThing <|-- OboFOODON03302001
        click OboFOODON03302001 href "../OboFOODON03302001"
      OwlThing <|-- OboFOODON03303380
        click OboFOODON03303380 href "../OboFOODON03303380"
      OwlThing <|-- OboFOODON03304313
        click OboFOODON03304313 href "../OboFOODON03304313"
      OwlThing <|-- OboFOODON03304497
        click OboFOODON03304497 href "../OboFOODON03304497"
      OwlThing <|-- OboFOODON03304616
        click OboFOODON03304616 href "../OboFOODON03304616"
      OwlThing <|-- OboFOODON03306306
        click OboFOODON03306306 href "../OboFOODON03306306"
      OwlThing <|-- OboFOODON03309997
        click OboFOODON03309997 href "../OboFOODON03309997"
      OwlThing <|-- OboFOODON03310611
        click OboFOODON03310611 href "../OboFOODON03310611"
      OwlThing <|-- OboFOODON03310961
        click OboFOODON03310961 href "../OboFOODON03310961"
      OwlThing <|-- OboFOODON03315150
        click OboFOODON03315150 href "../OboFOODON03315150"
      OwlThing <|-- OboFOODON03315173
        click OboFOODON03315173 href "../OboFOODON03315173"
      OwlThing <|-- OboFOODON03315308
        click OboFOODON03315308 href "../OboFOODON03315308"
      OwlThing <|-- OboFOODON03315468
        click OboFOODON03315468 href "../OboFOODON03315468"
      OwlThing <|-- OboFOODON03315769
        click OboFOODON03315769 href "../OboFOODON03315769"
      OwlThing <|-- OboFOODON03315883
        click OboFOODON03315883 href "../OboFOODON03315883"
      OwlThing <|-- OboFOODON03316061
        click OboFOODON03316061 href "../OboFOODON03316061"
      OwlThing <|-- OboFOODON03317076
        click OboFOODON03317076 href "../OboFOODON03317076"
      OwlThing <|-- OboFOODON03317170
        click OboFOODON03317170 href "../OboFOODON03317170"
      OwlThing <|-- OboFOODON03411005
        click OboFOODON03411005 href "../OboFOODON03411005"
      OwlThing <|-- OboFOODON03411006
        click OboFOODON03411006 href "../OboFOODON03411006"
      OwlThing <|-- OboFOODON03411013
        click OboFOODON03411013 href "../OboFOODON03411013"
      OwlThing <|-- OboFOODON03411017
        click OboFOODON03411017 href "../OboFOODON03411017"
      OwlThing <|-- OboFOODON03411018
        click OboFOODON03411018 href "../OboFOODON03411018"
      OwlThing <|-- OboFOODON03411021
        click OboFOODON03411021 href "../OboFOODON03411021"
      OwlThing <|-- OboFOODON03411022
        click OboFOODON03411022 href "../OboFOODON03411022"
      OwlThing <|-- OboFOODON03411024
        click OboFOODON03411024 href "../OboFOODON03411024"
      OwlThing <|-- OboFOODON03411036
        click OboFOODON03411036 href "../OboFOODON03411036"
      OwlThing <|-- OboFOODON03411047
        click OboFOODON03411047 href "../OboFOODON03411047"
      OwlThing <|-- OboFOODON03411048
        click OboFOODON03411048 href "../OboFOODON03411048"
      OwlThing <|-- OboFOODON03411057
        click OboFOODON03411057 href "../OboFOODON03411057"
      OwlThing <|-- OboFOODON03411058
        click OboFOODON03411058 href "../OboFOODON03411058"
      OwlThing <|-- OboFOODON03411062
        click OboFOODON03411062 href "../OboFOODON03411062"
      OwlThing <|-- OboFOODON03411121
        click OboFOODON03411121 href "../OboFOODON03411121"
      OwlThing <|-- OboFOODON03411129
        click OboFOODON03411129 href "../OboFOODON03411129"
      OwlThing <|-- OboFOODON03411134
        click OboFOODON03411134 href "../OboFOODON03411134"
      OwlThing <|-- OboFOODON03411136
        click OboFOODON03411136 href "../OboFOODON03411136"
      OwlThing <|-- OboFOODON03411139
        click OboFOODON03411139 href "../OboFOODON03411139"
      OwlThing <|-- OboFOODON03411140
        click OboFOODON03411140 href "../OboFOODON03411140"
      OwlThing <|-- OboFOODON03411142
        click OboFOODON03411142 href "../OboFOODON03411142"
      OwlThing <|-- OboFOODON03411151
        click OboFOODON03411151 href "../OboFOODON03411151"
      OwlThing <|-- OboFOODON03411156
        click OboFOODON03411156 href "../OboFOODON03411156"
      OwlThing <|-- OboFOODON03411174
        click OboFOODON03411174 href "../OboFOODON03411174"
      OwlThing <|-- OboFOODON03411179
        click OboFOODON03411179 href "../OboFOODON03411179"
      OwlThing <|-- OboFOODON03411183
        click OboFOODON03411183 href "../OboFOODON03411183"
      OwlThing <|-- OboFOODON03411184
        click OboFOODON03411184 href "../OboFOODON03411184"
      OwlThing <|-- OboFOODON03411194
        click OboFOODON03411194 href "../OboFOODON03411194"
      OwlThing <|-- OboFOODON03411213
        click OboFOODON03411213 href "../OboFOODON03411213"
      OwlThing <|-- OboFOODON03411222
        click OboFOODON03411222 href "../OboFOODON03411222"
      OwlThing <|-- OboFOODON03411223
        click OboFOODON03411223 href "../OboFOODON03411223"
      OwlThing <|-- OboFOODON03411231
        click OboFOODON03411231 href "../OboFOODON03411231"
      OwlThing <|-- OboFOODON03411232
        click OboFOODON03411232 href "../OboFOODON03411232"
      OwlThing <|-- OboFOODON03411236
        click OboFOODON03411236 href "../OboFOODON03411236"
      OwlThing <|-- OboFOODON03411266
        click OboFOODON03411266 href "../OboFOODON03411266"
      OwlThing <|-- OboFOODON03411293
        click OboFOODON03411293 href "../OboFOODON03411293"
      OwlThing <|-- OboFOODON03411297
        click OboFOODON03411297 href "../OboFOODON03411297"
      OwlThing <|-- OboFOODON03411319
        click OboFOODON03411319 href "../OboFOODON03411319"
      OwlThing <|-- OboFOODON03411324
        click OboFOODON03411324 href "../OboFOODON03411324"
      OwlThing <|-- OboFOODON03411325
        click OboFOODON03411325 href "../OboFOODON03411325"
      OwlThing <|-- OboFOODON03411328
        click OboFOODON03411328 href "../OboFOODON03411328"
      OwlThing <|-- OboFOODON03411331
        click OboFOODON03411331 href "../OboFOODON03411331"
      OwlThing <|-- OboFOODON03411365
        click OboFOODON03411365 href "../OboFOODON03411365"
      OwlThing <|-- OboFOODON03411374
        click OboFOODON03411374 href "../OboFOODON03411374"
      OwlThing <|-- OboFOODON03411380
        click OboFOODON03411380 href "../OboFOODON03411380"
      OwlThing <|-- OboFOODON03411393
        click OboFOODON03411393 href "../OboFOODON03411393"
      OwlThing <|-- OboFOODON03411409
        click OboFOODON03411409 href "../OboFOODON03411409"
      OwlThing <|-- OboFOODON03411433
        click OboFOODON03411433 href "../OboFOODON03411433"
      OwlThing <|-- OboFOODON03411439
        click OboFOODON03411439 href "../OboFOODON03411439"
      OwlThing <|-- OboFOODON03411447
        click OboFOODON03411447 href "../OboFOODON03411447"
      OwlThing <|-- OboFOODON03411454
        click OboFOODON03411454 href "../OboFOODON03411454"
      OwlThing <|-- OboFOODON03411457
        click OboFOODON03411457 href "../OboFOODON03411457"
      OwlThing <|-- OboFOODON03411491
        click OboFOODON03411491 href "../OboFOODON03411491"
      OwlThing <|-- OboFOODON03411500
        click OboFOODON03411500 href "../OboFOODON03411500"
      OwlThing <|-- OboFOODON03411539
        click OboFOODON03411539 href "../OboFOODON03411539"
      OwlThing <|-- OboFOODON03411557
        click OboFOODON03411557 href "../OboFOODON03411557"
      OwlThing <|-- OboFOODON03411563
        click OboFOODON03411563 href "../OboFOODON03411563"
      OwlThing <|-- OboFOODON03411564
        click OboFOODON03411564 href "../OboFOODON03411564"
      OwlThing <|-- OboFOODON03411566
        click OboFOODON03411566 href "../OboFOODON03411566"
      OwlThing <|-- OboFOODON03411567
        click OboFOODON03411567 href "../OboFOODON03411567"
      OwlThing <|-- OboFOODON03411568
        click OboFOODON03411568 href "../OboFOODON03411568"
      OwlThing <|-- OboFOODON03411579
        click OboFOODON03411579 href "../OboFOODON03411579"
      OwlThing <|-- OboFOODON03411581
        click OboFOODON03411581 href "../OboFOODON03411581"
      OwlThing <|-- OboFOODON03411583
        click OboFOODON03411583 href "../OboFOODON03411583"
      OwlThing <|-- OboFOODON03411592
        click OboFOODON03411592 href "../OboFOODON03411592"
      OwlThing <|-- OboFOODON03411594
        click OboFOODON03411594 href "../OboFOODON03411594"
      OwlThing <|-- OboFOODON03411595
        click OboFOODON03411595 href "../OboFOODON03411595"
      OwlThing <|-- OboFOODON03411597
        click OboFOODON03411597 href "../OboFOODON03411597"
      OwlThing <|-- OboFOODON03411599
        click OboFOODON03411599 href "../OboFOODON03411599"
      OwlThing <|-- OboFOODON03411607
        click OboFOODON03411607 href "../OboFOODON03411607"
      OwlThing <|-- OboFOODON03411614
        click OboFOODON03411614 href "../OboFOODON03411614"
      OwlThing <|-- OboFOODON03411617
        click OboFOODON03411617 href "../OboFOODON03411617"
      OwlThing <|-- OboFOODON03411669
        click OboFOODON03411669 href "../OboFOODON03411669"
      OwlThing <|-- OboFOODON03411818
        click OboFOODON03411818 href "../OboFOODON03411818"
      OwlThing <|-- OboFOODON03411826
        click OboFOODON03411826 href "../OboFOODON03411826"
      OwlThing <|-- OboFOODON03411892
        click OboFOODON03411892 href "../OboFOODON03411892"
      OwlThing <|-- OboFOODON03412004
        click OboFOODON03412004 href "../OboFOODON03412004"
      OwlThing <|-- OboFOODON03412112
        click OboFOODON03412112 href "../OboFOODON03412112"
      OwlThing <|-- OboFOODON03412113
        click OboFOODON03412113 href "../OboFOODON03412113"
      OwlThing <|-- OboFOODON03412241
        click OboFOODON03412241 href "../OboFOODON03412241"
      OwlThing <|-- OboFOODON03412331
        click OboFOODON03412331 href "../OboFOODON03412331"
      OwlThing <|-- OboFOODON03412362
        click OboFOODON03412362 href "../OboFOODON03412362"
      OwlThing <|-- OboFOODON03412409
        click OboFOODON03412409 href "../OboFOODON03412409"
      OwlThing <|-- OboFOODON03412426
        click OboFOODON03412426 href "../OboFOODON03412426"
      OwlThing <|-- OboFOODON03412453
        click OboFOODON03412453 href "../OboFOODON03412453"
      OwlThing <|-- OboFOODON03412665
        click OboFOODON03412665 href "../OboFOODON03412665"
      OwlThing <|-- OboFOODON03413357
        click OboFOODON03413357 href "../OboFOODON03413357"
      OwlThing <|-- OboFOODON03413358
        click OboFOODON03413358 href "../OboFOODON03413358"
      OwlThing <|-- OboFOODON03413360
        click OboFOODON03413360 href "../OboFOODON03413360"
      OwlThing <|-- OboFOODON03413372
        click OboFOODON03413372 href "../OboFOODON03413372"
      OwlThing <|-- OboFOODON03413377
        click OboFOODON03413377 href "../OboFOODON03413377"
      OwlThing <|-- OboFOODON03413378
        click OboFOODON03413378 href "../OboFOODON03413378"
      OwlThing <|-- OboFOODON03413406
        click OboFOODON03413406 href "../OboFOODON03413406"
      OwlThing <|-- OboFOODON03413448
        click OboFOODON03413448 href "../OboFOODON03413448"
      OwlThing <|-- OboFOODON03413807
        click OboFOODON03413807 href "../OboFOODON03413807"
      OwlThing <|-- OboFOODON03413808
        click OboFOODON03413808 href "../OboFOODON03413808"
      OwlThing <|-- OboFOODON03414051
        click OboFOODON03414051 href "../OboFOODON03414051"
      OwlThing <|-- OboFOODON03414209
        click OboFOODON03414209 href "../OboFOODON03414209"
      OwlThing <|-- OboFOODON03414282
        click OboFOODON03414282 href "../OboFOODON03414282"
      OwlThing <|-- OboFOODON03414302
        click OboFOODON03414302 href "../OboFOODON03414302"
      OwlThing <|-- OboFOODON03414374
        click OboFOODON03414374 href "../OboFOODON03414374"
      OwlThing <|-- OboFOODON03414381
        click OboFOODON03414381 href "../OboFOODON03414381"
      OwlThing <|-- OboFOODON03414459
        click OboFOODON03414459 href "../OboFOODON03414459"
      OwlThing <|-- OboFOODON03414460
        click OboFOODON03414460 href "../OboFOODON03414460"
      OwlThing <|-- OboFOODON03414494
        click OboFOODON03414494 href "../OboFOODON03414494"
      OwlThing <|-- OboFOODON03414741
        click OboFOODON03414741 href "../OboFOODON03414741"
      OwlThing <|-- OboFOODON03414742
        click OboFOODON03414742 href "../OboFOODON03414742"
      OwlThing <|-- OboFOODON03414745
        click OboFOODON03414745 href "../OboFOODON03414745"
      OwlThing <|-- OboFOODON03414934
        click OboFOODON03414934 href "../OboFOODON03414934"
      OwlThing <|-- OboFOODON03414972
        click OboFOODON03414972 href "../OboFOODON03414972"
      OwlThing <|-- OboFOODON03420101
        click OboFOODON03420101 href "../OboFOODON03420101"
      OwlThing <|-- OboFOODON03420106
        click OboFOODON03420106 href "../OboFOODON03420106"
      OwlThing <|-- OboFOODON03420116
        click OboFOODON03420116 href "../OboFOODON03420116"
      OwlThing <|-- OboFOODON03420122
        click OboFOODON03420122 href "../OboFOODON03420122"
      OwlThing <|-- OboFOODON03420127
        click OboFOODON03420127 href "../OboFOODON03420127"
      OwlThing <|-- OboFOODON03420129
        click OboFOODON03420129 href "../OboFOODON03420129"
      OwlThing <|-- OboFOODON03420144
        click OboFOODON03420144 href "../OboFOODON03420144"
      OwlThing <|-- OboFOODON03420145
        click OboFOODON03420145 href "../OboFOODON03420145"
      OwlThing <|-- OboFOODON03420148
        click OboFOODON03420148 href "../OboFOODON03420148"
      OwlThing <|-- OboFOODON03420150
        click OboFOODON03420150 href "../OboFOODON03420150"
      OwlThing <|-- OboFOODON03420164
        click OboFOODON03420164 href "../OboFOODON03420164"
      OwlThing <|-- OboFOODON03420181
        click OboFOODON03420181 href "../OboFOODON03420181"
      OwlThing <|-- OboFOODON03420183
        click OboFOODON03420183 href "../OboFOODON03420183"
      OwlThing <|-- OboFOODON03420194
        click OboFOODON03420194 href "../OboFOODON03420194"
      OwlThing <|-- OboFOODON03420202
        click OboFOODON03420202 href "../OboFOODON03420202"
      OwlThing <|-- OboFOODON03420218
        click OboFOODON03420218 href "../OboFOODON03420218"
      OwlThing <|-- OboFOODON03420238
        click OboFOODON03420238 href "../OboFOODON03420238"
      OwlThing <|-- OboFOODON03420239
        click OboFOODON03420239 href "../OboFOODON03420239"
      OwlThing <|-- OboFOODON03460177
        click OboFOODON03460177 href "../OboFOODON03460177"
      OwlThing <|-- OboFOODON03602002
        click OboFOODON03602002 href "../OboFOODON03602002"
      OwlThing <|-- OboNCBITaxon1003242
        click OboNCBITaxon1003242 href "../OboNCBITaxon1003242"
      OwlThing <|-- OboNCBITaxon1003875
        click OboNCBITaxon1003875 href "../OboNCBITaxon1003875"
      OwlThing <|-- OboNCBITaxon1003877
        click OboNCBITaxon1003877 href "../OboNCBITaxon1003877"
      OwlThing <|-- OboNCBITaxon10184
        click OboNCBITaxon10184 href "../OboNCBITaxon10184"
      OwlThing <|-- OboNCBITaxon102804
        click OboNCBITaxon102804 href "../OboNCBITaxon102804"
      OwlThing <|-- OboNCBITaxon102809
        click OboNCBITaxon102809 href "../OboNCBITaxon102809"
      OwlThing <|-- OboNCBITaxon102810
        click OboNCBITaxon102810 href "../OboNCBITaxon102810"
      OwlThing <|-- OboNCBITaxon102812
        click OboNCBITaxon102812 href "../OboNCBITaxon102812"
      OwlThing <|-- OboNCBITaxon102814
        click OboNCBITaxon102814 href "../OboNCBITaxon102814"
      OwlThing <|-- OboNCBITaxon102818
        click OboNCBITaxon102818 href "../OboNCBITaxon102818"
      OwlThing <|-- OboNCBITaxon109170
        click OboNCBITaxon109170 href "../OboNCBITaxon109170"
      OwlThing <|-- OboNCBITaxon1110380
        click OboNCBITaxon1110380 href "../OboNCBITaxon1110380"
      OwlThing <|-- OboNCBITaxon1110386
        click OboNCBITaxon1110386 href "../OboNCBITaxon1110386"
      OwlThing <|-- OboNCBITaxon112818
        click OboNCBITaxon112818 href "../OboNCBITaxon112818"
      OwlThing <|-- OboNCBITaxon115479
        click OboNCBITaxon115479 href "../OboNCBITaxon115479"
      OwlThing <|-- OboNCBITaxon117571
        click OboNCBITaxon117571 href "../OboNCBITaxon117571"
      OwlThing <|-- OboNCBITaxon1176516
        click OboNCBITaxon1176516 href "../OboNCBITaxon1176516"
      OwlThing <|-- OboNCBITaxon1184124
        click OboNCBITaxon1184124 href "../OboNCBITaxon1184124"
      OwlThing <|-- OboNCBITaxon119950
        click OboNCBITaxon119950 href "../OboNCBITaxon119950"
      OwlThing <|-- OboNCBITaxon120289
        click OboNCBITaxon120289 href "../OboNCBITaxon120289"
      OwlThing <|-- OboNCBITaxon1203511
        click OboNCBITaxon1203511 href "../OboNCBITaxon1203511"
      OwlThing <|-- OboNCBITaxon123366
        click OboNCBITaxon123366 href "../OboNCBITaxon123366"
      OwlThing <|-- OboNCBITaxon123368
        click OboNCBITaxon123368 href "../OboNCBITaxon123368"
      OwlThing <|-- OboNCBITaxon123369
        click OboNCBITaxon123369 href "../OboNCBITaxon123369"
      OwlThing <|-- OboNCBITaxon125009
        click OboNCBITaxon125009 href "../OboNCBITaxon125009"
      OwlThing <|-- OboNCBITaxon126735
        click OboNCBITaxon126735 href "../OboNCBITaxon126735"
      OwlThing <|-- OboNCBITaxon128017
        click OboNCBITaxon128017 href "../OboNCBITaxon128017"
      OwlThing <|-- OboNCBITaxon1307774
        click OboNCBITaxon1307774 href "../OboNCBITaxon1307774"
      OwlThing <|-- OboNCBITaxon1307775
        click OboNCBITaxon1307775 href "../OboNCBITaxon1307775"
      OwlThing <|-- OboNCBITaxon1307796
        click OboNCBITaxon1307796 href "../OboNCBITaxon1307796"
      OwlThing <|-- OboNCBITaxon1308840
        click OboNCBITaxon1308840 href "../OboNCBITaxon1308840"
      OwlThing <|-- OboNCBITaxon1329799
        click OboNCBITaxon1329799 href "../OboNCBITaxon1329799"
      OwlThing <|-- OboNCBITaxon13336
        click OboNCBITaxon13336 href "../OboNCBITaxon13336"
      OwlThing <|-- OboNCBITaxon1338369
        click OboNCBITaxon1338369 href "../OboNCBITaxon1338369"
      OwlThing <|-- OboNCBITaxon13424
        click OboNCBITaxon13424 href "../OboNCBITaxon13424"
      OwlThing <|-- OboNCBITaxon13426
        click OboNCBITaxon13426 href "../OboNCBITaxon13426"
      OwlThing <|-- OboNCBITaxon13492
        click OboNCBITaxon13492 href "../OboNCBITaxon13492"
      OwlThing <|-- OboNCBITaxon13749
        click OboNCBITaxon13749 href "../OboNCBITaxon13749"
      OwlThing <|-- OboNCBITaxon1437010
        click OboNCBITaxon1437010 href "../OboNCBITaxon1437010"
      OwlThing <|-- OboNCBITaxon1437180
        click OboNCBITaxon1437180 href "../OboNCBITaxon1437180"
      OwlThing <|-- OboNCBITaxon1437183
        click OboNCBITaxon1437183 href "../OboNCBITaxon1437183"
      OwlThing <|-- OboNCBITaxon1437197
        click OboNCBITaxon1437197 href "../OboNCBITaxon1437197"
      OwlThing <|-- OboNCBITaxon1437201
        click OboNCBITaxon1437201 href "../OboNCBITaxon1437201"
      OwlThing <|-- OboNCBITaxon144561
        click OboNCBITaxon144561 href "../OboNCBITaxon144561"
      OwlThing <|-- OboNCBITaxon1463138
        click OboNCBITaxon1463138 href "../OboNCBITaxon1463138"
      OwlThing <|-- OboNCBITaxon147366
        click OboNCBITaxon147366 href "../OboNCBITaxon147366"
      OwlThing <|-- OboNCBITaxon147368
        click OboNCBITaxon147368 href "../OboNCBITaxon147368"
      OwlThing <|-- OboNCBITaxon147369
        click OboNCBITaxon147369 href "../OboNCBITaxon147369"
      OwlThing <|-- OboNCBITaxon147370
        click OboNCBITaxon147370 href "../OboNCBITaxon147370"
      OwlThing <|-- OboNCBITaxon147389
        click OboNCBITaxon147389 href "../OboNCBITaxon147389"
      OwlThing <|-- OboNCBITaxon147429
        click OboNCBITaxon147429 href "../OboNCBITaxon147429"
      OwlThing <|-- OboNCBITaxon147949
        click OboNCBITaxon147949 href "../OboNCBITaxon147949"
      OwlThing <|-- OboNCBITaxon1489341
        click OboNCBITaxon1489341 href "../OboNCBITaxon1489341"
      OwlThing <|-- OboNCBITaxon1489388
        click OboNCBITaxon1489388 href "../OboNCBITaxon1489388"
      OwlThing <|-- OboNCBITaxon1489793
        click OboNCBITaxon1489793 href "../OboNCBITaxon1489793"
      OwlThing <|-- OboNCBITaxon1489872
        click OboNCBITaxon1489872 href "../OboNCBITaxon1489872"
      OwlThing <|-- OboNCBITaxon1489922
        click OboNCBITaxon1489922 href "../OboNCBITaxon1489922"
      OwlThing <|-- OboNCBITaxon1489923
        click OboNCBITaxon1489923 href "../OboNCBITaxon1489923"
      OwlThing <|-- OboNCBITaxon1489940
        click OboNCBITaxon1489940 href "../OboNCBITaxon1489940"
      OwlThing <|-- OboNCBITaxon15105
        click OboNCBITaxon15105 href "../OboNCBITaxon15105"
      OwlThing <|-- OboNCBITaxon151069
        click OboNCBITaxon151069 href "../OboNCBITaxon151069"
      OwlThing <|-- OboNCBITaxon151071
        click OboNCBITaxon151071 href "../OboNCBITaxon151071"
      OwlThing <|-- OboNCBITaxon1521262
        click OboNCBITaxon1521262 href "../OboNCBITaxon1521262"
      OwlThing <|-- OboNCBITaxon1538097
        click OboNCBITaxon1538097 href "../OboNCBITaxon1538097"
      OwlThing <|-- OboNCBITaxon1545897
        click OboNCBITaxon1545897 href "../OboNCBITaxon1545897"
      OwlThing <|-- OboNCBITaxon1549675
        click OboNCBITaxon1549675 href "../OboNCBITaxon1549675"
      OwlThing <|-- OboNCBITaxon156152
        click OboNCBITaxon156152 href "../OboNCBITaxon156152"
      OwlThing <|-- OboNCBITaxon1589896
        click OboNCBITaxon1589896 href "../OboNCBITaxon1589896"
      OwlThing <|-- OboNCBITaxon159053
        click OboNCBITaxon159053 href "../OboNCBITaxon159053"
      OwlThing <|-- OboNCBITaxon1609961
        click OboNCBITaxon1609961 href "../OboNCBITaxon1609961"
      OwlThing <|-- OboNCBITaxon1609962
        click OboNCBITaxon1609962 href "../OboNCBITaxon1609962"
      OwlThing <|-- OboNCBITaxon162743
        click OboNCBITaxon162743 href "../OboNCBITaxon162743"
      OwlThing <|-- OboNCBITaxon163487
        click OboNCBITaxon163487 href "../OboNCBITaxon163487"
      OwlThing <|-- OboNCBITaxon16360
        click OboNCBITaxon16360 href "../OboNCBITaxon16360"
      OwlThing <|-- OboNCBITaxon163735
        click OboNCBITaxon163735 href "../OboNCBITaxon163735"
      OwlThing <|-- OboNCBITaxon163743
        click OboNCBITaxon163743 href "../OboNCBITaxon163743"
      OwlThing <|-- OboNCBITaxon1648004
        click OboNCBITaxon1648004 href "../OboNCBITaxon1648004"
      OwlThing <|-- OboNCBITaxon1648017
        click OboNCBITaxon1648017 href "../OboNCBITaxon1648017"
      OwlThing <|-- OboNCBITaxon1648033
        click OboNCBITaxon1648033 href "../OboNCBITaxon1648033"
      OwlThing <|-- OboNCBITaxon165297
        click OboNCBITaxon165297 href "../OboNCBITaxon165297"
      OwlThing <|-- OboNCBITaxon169617
        click OboNCBITaxon169617 href "../OboNCBITaxon169617"
      OwlThing <|-- OboNCBITaxon169618
        click OboNCBITaxon169618 href "../OboNCBITaxon169618"
      OwlThing <|-- OboNCBITaxon169642
        click OboNCBITaxon169642 href "../OboNCBITaxon169642"
      OwlThing <|-- OboNCBITaxon169655
        click OboNCBITaxon169655 href "../OboNCBITaxon169655"
      OwlThing <|-- OboNCBITaxon169697
        click OboNCBITaxon169697 href "../OboNCBITaxon169697"
      OwlThing <|-- OboNCBITaxon169700
        click OboNCBITaxon169700 href "../OboNCBITaxon169700"
      OwlThing <|-- OboNCBITaxon169703
        click OboNCBITaxon169703 href "../OboNCBITaxon169703"
      OwlThing <|-- OboNCBITaxon169705
        click OboNCBITaxon169705 href "../OboNCBITaxon169705"
      OwlThing <|-- OboNCBITaxon169725
        click OboNCBITaxon169725 href "../OboNCBITaxon169725"
      OwlThing <|-- OboNCBITaxon169733
        click OboNCBITaxon169733 href "../OboNCBITaxon169733"
      OwlThing <|-- OboNCBITaxon169746
        click OboNCBITaxon169746 href "../OboNCBITaxon169746"
      OwlThing <|-- OboNCBITaxon1699513
        click OboNCBITaxon1699513 href "../OboNCBITaxon1699513"
      OwlThing <|-- OboNCBITaxon1699523
        click OboNCBITaxon1699523 href "../OboNCBITaxon1699523"
      OwlThing <|-- OboNCBITaxon17047
        click OboNCBITaxon17047 href "../OboNCBITaxon17047"
      OwlThing <|-- OboNCBITaxon1705104
        click OboNCBITaxon1705104 href "../OboNCBITaxon1705104"
      OwlThing <|-- OboNCBITaxon171637
        click OboNCBITaxon171637 href "../OboNCBITaxon171637"
      OwlThing <|-- OboNCBITaxon171638
        click OboNCBITaxon171638 href "../OboNCBITaxon171638"
      OwlThing <|-- OboNCBITaxon1728959
        click OboNCBITaxon1728959 href "../OboNCBITaxon1728959"
      OwlThing <|-- OboNCBITaxon173691
        click OboNCBITaxon173691 href "../OboNCBITaxon173691"
      OwlThing <|-- OboNCBITaxon174217
        click OboNCBITaxon174217 href "../OboNCBITaxon174217"
      OwlThing <|-- OboNCBITaxon178174
        click OboNCBITaxon178174 href "../OboNCBITaxon178174"
      OwlThing <|-- OboNCBITaxon180118
        click OboNCBITaxon180118 href "../OboNCBITaxon180118"
      OwlThing <|-- OboNCBITaxon1804623
        click OboNCBITaxon1804623 href "../OboNCBITaxon1804623"
      OwlThing <|-- OboNCBITaxon181185
        click OboNCBITaxon181185 href "../OboNCBITaxon181185"
      OwlThing <|-- OboNCBITaxon183218
        click OboNCBITaxon183218 href "../OboNCBITaxon183218"
      OwlThing <|-- OboNCBITaxon184451
        click OboNCBITaxon184451 href "../OboNCBITaxon184451"
      OwlThing <|-- OboNCBITaxon186265
        click OboNCBITaxon186265 href "../OboNCBITaxon186265"
      OwlThing <|-- OboNCBITaxon186623
        click OboNCBITaxon186623 href "../OboNCBITaxon186623"
      OwlThing <|-- OboNCBITaxon186625
        click OboNCBITaxon186625 href "../OboNCBITaxon186625"
      OwlThing <|-- OboNCBITaxon186626
        click OboNCBITaxon186626 href "../OboNCBITaxon186626"
      OwlThing <|-- OboNCBITaxon186628
        click OboNCBITaxon186628 href "../OboNCBITaxon186628"
      OwlThing <|-- OboNCBITaxon186634
        click OboNCBITaxon186634 href "../OboNCBITaxon186634"
      OwlThing <|-- OboNCBITaxon1874399
        click OboNCBITaxon1874399 href "../OboNCBITaxon1874399"
      OwlThing <|-- OboNCBITaxon19205
        click OboNCBITaxon19205 href "../OboNCBITaxon19205"
      OwlThing <|-- OboNCBITaxon1927087
        click OboNCBITaxon1927087 href "../OboNCBITaxon1927087"
      OwlThing <|-- OboNCBITaxon193297
        click OboNCBITaxon193297 href "../OboNCBITaxon193297"
      OwlThing <|-- OboNCBITaxon194251
        click OboNCBITaxon194251 href "../OboNCBITaxon194251"
      OwlThing <|-- OboNCBITaxon1968271
        click OboNCBITaxon1968271 href "../OboNCBITaxon1968271"
      OwlThing <|-- OboNCBITaxon1968429
        click OboNCBITaxon1968429 href "../OboNCBITaxon1968429"
      OwlThing <|-- OboNCBITaxon1977918
        click OboNCBITaxon1977918 href "../OboNCBITaxon1977918"
      OwlThing <|-- OboNCBITaxon198777
        click OboNCBITaxon198777 href "../OboNCBITaxon198777"
      OwlThing <|-- OboNCBITaxon19955
        click OboNCBITaxon19955 href "../OboNCBITaxon19955"
      OwlThing <|-- OboNCBITaxon201017
        click OboNCBITaxon201017 href "../OboNCBITaxon201017"
      OwlThing <|-- OboNCBITaxon214693
        click OboNCBITaxon214693 href "../OboNCBITaxon214693"
      OwlThing <|-- OboNCBITaxon214697
        click OboNCBITaxon214697 href "../OboNCBITaxon214697"
      OwlThing <|-- OboNCBITaxon21472
        click OboNCBITaxon21472 href "../OboNCBITaxon21472"
      OwlThing <|-- OboNCBITaxon214907
        click OboNCBITaxon214907 href "../OboNCBITaxon214907"
      OwlThing <|-- OboNCBITaxon214908
        click OboNCBITaxon214908 href "../OboNCBITaxon214908"
      OwlThing <|-- OboNCBITaxon214929
        click OboNCBITaxon214929 href "../OboNCBITaxon214929"
      OwlThing <|-- OboNCBITaxon215450
        click OboNCBITaxon215450 href "../OboNCBITaxon215450"
      OwlThing <|-- OboNCBITaxon21563
        click OboNCBITaxon21563 href "../OboNCBITaxon21563"
      OwlThing <|-- OboNCBITaxon21571
        click OboNCBITaxon21571 href "../OboNCBITaxon21571"
      OwlThing <|-- OboNCBITaxon216703
        click OboNCBITaxon216703 href "../OboNCBITaxon216703"
      OwlThing <|-- OboNCBITaxon217033
        click OboNCBITaxon217033 href "../OboNCBITaxon217033"
      OwlThing <|-- OboNCBITaxon217035
        click OboNCBITaxon217035 href "../OboNCBITaxon217035"
      OwlThing <|-- OboNCBITaxon217037
        click OboNCBITaxon217037 href "../OboNCBITaxon217037"
      OwlThing <|-- OboNCBITaxon217062
        click OboNCBITaxon217062 href "../OboNCBITaxon217062"
      OwlThing <|-- OboNCBITaxon219121
        click OboNCBITaxon219121 href "../OboNCBITaxon219121"
      OwlThing <|-- OboNCBITaxon219134
        click OboNCBITaxon219134 href "../OboNCBITaxon219134"
      OwlThing <|-- OboNCBITaxon221251
        click OboNCBITaxon221251 href "../OboNCBITaxon221251"
      OwlThing <|-- OboNCBITaxon22140
        click OboNCBITaxon22140 href "../OboNCBITaxon22140"
      OwlThing <|-- OboNCBITaxon2231382
        click OboNCBITaxon2231382 href "../OboNCBITaxon2231382"
      OwlThing <|-- OboNCBITaxon2231383
        click OboNCBITaxon2231383 href "../OboNCBITaxon2231383"
      OwlThing <|-- OboNCBITaxon2231390
        click OboNCBITaxon2231390 href "../OboNCBITaxon2231390"
      OwlThing <|-- OboNCBITaxon2231393
        click OboNCBITaxon2231393 href "../OboNCBITaxon2231393"
      OwlThing <|-- OboNCBITaxon2233838
        click OboNCBITaxon2233838 href "../OboNCBITaxon2233838"
      OwlThing <|-- OboNCBITaxon2233839
        click OboNCBITaxon2233839 href "../OboNCBITaxon2233839"
      OwlThing <|-- OboNCBITaxon2233855
        click OboNCBITaxon2233855 href "../OboNCBITaxon2233855"
      OwlThing <|-- OboNCBITaxon2233857
        click OboNCBITaxon2233857 href "../OboNCBITaxon2233857"
      OwlThing <|-- OboNCBITaxon22663
        click OboNCBITaxon22663 href "../OboNCBITaxon22663"
      OwlThing <|-- OboNCBITaxon22665
        click OboNCBITaxon22665 href "../OboNCBITaxon22665"
      OwlThing <|-- OboNCBITaxon22774
        click OboNCBITaxon22774 href "../OboNCBITaxon22774"
      OwlThing <|-- OboNCBITaxon22973
        click OboNCBITaxon22973 href "../OboNCBITaxon22973"
      OwlThing <|-- OboNCBITaxon22978
        click OboNCBITaxon22978 href "../OboNCBITaxon22978"
      OwlThing <|-- OboNCBITaxon2304100
        click OboNCBITaxon2304100 href "../OboNCBITaxon2304100"
      OwlThing <|-- OboNCBITaxon23066
        click OboNCBITaxon23066 href "../OboNCBITaxon23066"
      OwlThing <|-- OboNCBITaxon23139
        click OboNCBITaxon23139 href "../OboNCBITaxon23139"
      OwlThing <|-- OboNCBITaxon23216
        click OboNCBITaxon23216 href "../OboNCBITaxon23216"
      OwlThing <|-- OboNCBITaxon23222
        click OboNCBITaxon23222 href "../OboNCBITaxon23222"
      OwlThing <|-- OboNCBITaxon232347
        click OboNCBITaxon232347 href "../OboNCBITaxon232347"
      OwlThing <|-- OboNCBITaxon233713
        click OboNCBITaxon233713 href "../OboNCBITaxon233713"
      OwlThing <|-- OboNCBITaxon233715
        click OboNCBITaxon233715 href "../OboNCBITaxon233715"
      OwlThing <|-- OboNCBITaxon233880
        click OboNCBITaxon233880 href "../OboNCBITaxon233880"
      OwlThing <|-- OboNCBITaxon23461
        click OboNCBITaxon23461 href "../OboNCBITaxon23461"
      OwlThing <|-- OboNCBITaxon23513
        click OboNCBITaxon23513 href "../OboNCBITaxon23513"
      OwlThing <|-- OboNCBITaxon235595
        click OboNCBITaxon235595 href "../OboNCBITaxon235595"
      OwlThing <|-- OboNCBITaxon23672
        click OboNCBITaxon23672 href "../OboNCBITaxon23672"
      OwlThing <|-- OboNCBITaxon23808
        click OboNCBITaxon23808 href "../OboNCBITaxon23808"
      OwlThing <|-- OboNCBITaxon241778
        click OboNCBITaxon241778 href "../OboNCBITaxon241778"
      OwlThing <|-- OboNCBITaxon241780
        click OboNCBITaxon241780 href "../OboNCBITaxon241780"
      OwlThing <|-- OboNCBITaxon241789
        click OboNCBITaxon241789 href "../OboNCBITaxon241789"
      OwlThing <|-- OboNCBITaxon241793
        click OboNCBITaxon241793 href "../OboNCBITaxon241793"
      OwlThing <|-- OboNCBITaxon241799
        click OboNCBITaxon241799 href "../OboNCBITaxon241799"
      OwlThing <|-- OboNCBITaxon241800
        click OboNCBITaxon241800 href "../OboNCBITaxon241800"
      OwlThing <|-- OboNCBITaxon241806
        click OboNCBITaxon241806 href "../OboNCBITaxon241806"
      OwlThing <|-- OboNCBITaxon245205
        click OboNCBITaxon245205 href "../OboNCBITaxon245205"
      OwlThing <|-- OboNCBITaxon24646
        click OboNCBITaxon24646 href "../OboNCBITaxon24646"
      OwlThing <|-- OboNCBITaxon24663
        click OboNCBITaxon24663 href "../OboNCBITaxon24663"
      OwlThing <|-- OboNCBITaxon24966
        click OboNCBITaxon24966 href "../OboNCBITaxon24966"
      OwlThing <|-- OboNCBITaxon259381
        click OboNCBITaxon259381 href "../OboNCBITaxon259381"
      OwlThing <|-- OboNCBITaxon25996
        click OboNCBITaxon25996 href "../OboNCBITaxon25996"
      OwlThing <|-- OboNCBITaxon260143
        click OboNCBITaxon260143 href "../OboNCBITaxon260143"
      OwlThing <|-- OboNCBITaxon260718
        click OboNCBITaxon260718 href "../OboNCBITaxon260718"
      OwlThing <|-- OboNCBITaxon26468
        click OboNCBITaxon26468 href "../OboNCBITaxon26468"
      OwlThing <|-- OboNCBITaxon26496
        click OboNCBITaxon26496 href "../OboNCBITaxon26496"
      OwlThing <|-- OboNCBITaxon26867
        click OboNCBITaxon26867 href "../OboNCBITaxon26867"
      OwlThing <|-- OboNCBITaxon2706
        click OboNCBITaxon2706 href "../OboNCBITaxon2706"
      OwlThing <|-- OboNCBITaxon2732585
        click OboNCBITaxon2732585 href "../OboNCBITaxon2732585"
      OwlThing <|-- OboNCBITaxon2759
        click OboNCBITaxon2759 href "../OboNCBITaxon2759"
      OwlThing <|-- OboNCBITaxon27592
        click OboNCBITaxon27592 href "../OboNCBITaxon27592"
      OwlThing <|-- OboNCBITaxon27705
        click OboNCBITaxon27705 href "../OboNCBITaxon27705"
      OwlThing <|-- OboNCBITaxon27706
        click OboNCBITaxon27706 href "../OboNCBITaxon27706"
      OwlThing <|-- OboNCBITaxon27778
        click OboNCBITaxon27778 href "../OboNCBITaxon27778"
      OwlThing <|-- OboNCBITaxon278205
        click OboNCBITaxon278205 href "../OboNCBITaxon278205"
      OwlThing <|-- OboNCBITaxon2785011
        click OboNCBITaxon2785011 href "../OboNCBITaxon2785011"
      OwlThing <|-- OboNCBITaxon2785015
        click OboNCBITaxon2785015 href "../OboNCBITaxon2785015"
      OwlThing <|-- OboNCBITaxon284555
        click OboNCBITaxon284555 href "../OboNCBITaxon284555"
      OwlThing <|-- OboNCBITaxon28974
        click OboNCBITaxon28974 href "../OboNCBITaxon28974"
      OwlThing <|-- OboNCBITaxon2908833
        click OboNCBITaxon2908833 href "../OboNCBITaxon2908833"
      OwlThing <|-- OboNCBITaxon290983
        click OboNCBITaxon290983 href "../OboNCBITaxon290983"
      OwlThing <|-- OboNCBITaxon29132
        click OboNCBITaxon29132 href "../OboNCBITaxon29132"
      OwlThing <|-- OboNCBITaxon296036
        click OboNCBITaxon296036 href "../OboNCBITaxon296036"
      OwlThing <|-- OboNCBITaxon2976026
        click OboNCBITaxon2976026 href "../OboNCBITaxon2976026"
      OwlThing <|-- OboNCBITaxon29780
        click OboNCBITaxon29780 href "../OboNCBITaxon29780"
      OwlThing <|-- OboNCBITaxon301453
        click OboNCBITaxon301453 href "../OboNCBITaxon301453"
      OwlThing <|-- OboNCBITaxon301959
        click OboNCBITaxon301959 href "../OboNCBITaxon301959"
      OwlThing <|-- OboNCBITaxon303185
        click OboNCBITaxon303185 href "../OboNCBITaxon303185"
      OwlThing <|-- OboNCBITaxon314145
        click OboNCBITaxon314145 href "../OboNCBITaxon314145"
      OwlThing <|-- OboNCBITaxon314146
        click OboNCBITaxon314146 href "../OboNCBITaxon314146"
      OwlThing <|-- OboNCBITaxon314147
        click OboNCBITaxon314147 href "../OboNCBITaxon314147"
      OwlThing <|-- OboNCBITaxon32443
        click OboNCBITaxon32443 href "../OboNCBITaxon32443"
      OwlThing <|-- OboNCBITaxon32519
        click OboNCBITaxon32519 href "../OboNCBITaxon32519"
      OwlThing <|-- OboNCBITaxon32523
        click OboNCBITaxon32523 href "../OboNCBITaxon32523"
      OwlThing <|-- OboNCBITaxon32524
        click OboNCBITaxon32524 href "../OboNCBITaxon32524"
      OwlThing <|-- OboNCBITaxon32525
        click OboNCBITaxon32525 href "../OboNCBITaxon32525"
      OwlThing <|-- OboNCBITaxon32561
        click OboNCBITaxon32561 href "../OboNCBITaxon32561"
      OwlThing <|-- OboNCBITaxon3268
        click OboNCBITaxon3268 href "../OboNCBITaxon3268"
      OwlThing <|-- OboNCBITaxon3275
        click OboNCBITaxon3275 href "../OboNCBITaxon3275"
      OwlThing <|-- OboNCBITaxon3282
        click OboNCBITaxon3282 href "../OboNCBITaxon3282"
      OwlThing <|-- OboNCBITaxon3296
        click OboNCBITaxon3296 href "../OboNCBITaxon3296"
      OwlThing <|-- OboNCBITaxon3297
        click OboNCBITaxon3297 href "../OboNCBITaxon3297"
      OwlThing <|-- OboNCBITaxon33090
        click OboNCBITaxon33090 href "../OboNCBITaxon33090"
      OwlThing <|-- OboNCBITaxon33154
        click OboNCBITaxon33154 href "../OboNCBITaxon33154"
      OwlThing <|-- OboNCBITaxon33208
        click OboNCBITaxon33208 href "../OboNCBITaxon33208"
      OwlThing <|-- OboNCBITaxon33213
        click OboNCBITaxon33213 href "../OboNCBITaxon33213"
      OwlThing <|-- OboNCBITaxon33317
        click OboNCBITaxon33317 href "../OboNCBITaxon33317"
      OwlThing <|-- OboNCBITaxon33511
        click OboNCBITaxon33511 href "../OboNCBITaxon33511"
      OwlThing <|-- OboNCBITaxon3394
        click OboNCBITaxon3394 href "../OboNCBITaxon3394"
      OwlThing <|-- OboNCBITaxon3395
        click OboNCBITaxon3395 href "../OboNCBITaxon3395"
      OwlThing <|-- OboNCBITaxon3398
        click OboNCBITaxon3398 href "../OboNCBITaxon3398"
      OwlThing <|-- OboNCBITaxon3400
        click OboNCBITaxon3400 href "../OboNCBITaxon3400"
      OwlThing <|-- OboNCBITaxon3440
        click OboNCBITaxon3440 href "../OboNCBITaxon3440"
      OwlThing <|-- OboNCBITaxon34542
        click OboNCBITaxon34542 href "../OboNCBITaxon34542"
      OwlThing <|-- OboNCBITaxon3465
        click OboNCBITaxon3465 href "../OboNCBITaxon3465"
      OwlThing <|-- OboNCBITaxon3468
        click OboNCBITaxon3468 href "../OboNCBITaxon3468"
      OwlThing <|-- OboNCBITaxon34815
        click OboNCBITaxon34815 href "../OboNCBITaxon34815"
      OwlThing <|-- OboNCBITaxon3487
        click OboNCBITaxon3487 href "../OboNCBITaxon3487"
      OwlThing <|-- OboNCBITaxon3488
        click OboNCBITaxon3488 href "../OboNCBITaxon3488"
      OwlThing <|-- OboNCBITaxon3489
        click OboNCBITaxon3489 href "../OboNCBITaxon3489"
      OwlThing <|-- OboNCBITaxon3493
        click OboNCBITaxon3493 href "../OboNCBITaxon3493"
      OwlThing <|-- OboNCBITaxon3497
        click OboNCBITaxon3497 href "../OboNCBITaxon3497"
      OwlThing <|-- OboNCBITaxon3499
        click OboNCBITaxon3499 href "../OboNCBITaxon3499"
      OwlThing <|-- OboNCBITaxon3524
        click OboNCBITaxon3524 href "../OboNCBITaxon3524"
      OwlThing <|-- OboNCBITaxon3542
        click OboNCBITaxon3542 href "../OboNCBITaxon3542"
      OwlThing <|-- OboNCBITaxon35500
        click OboNCBITaxon35500 href "../OboNCBITaxon35500"
      OwlThing <|-- OboNCBITaxon3558
        click OboNCBITaxon3558 href "../OboNCBITaxon3558"
      OwlThing <|-- OboNCBITaxon3563
        click OboNCBITaxon3563 href "../OboNCBITaxon3563"
      OwlThing <|-- OboNCBITaxon3564
        click OboNCBITaxon3564 href "../OboNCBITaxon3564"
      OwlThing <|-- OboNCBITaxon3568
        click OboNCBITaxon3568 href "../OboNCBITaxon3568"
      OwlThing <|-- OboNCBITaxon3587
        click OboNCBITaxon3587 href "../OboNCBITaxon3587"
      OwlThing <|-- OboNCBITaxon359160
        click OboNCBITaxon359160 href "../OboNCBITaxon359160"
      OwlThing <|-- OboNCBITaxon3593
        click OboNCBITaxon3593 href "../OboNCBITaxon3593"
      OwlThing <|-- OboNCBITaxon3602
        click OboNCBITaxon3602 href "../OboNCBITaxon3602"
      OwlThing <|-- OboNCBITaxon3603
        click OboNCBITaxon3603 href "../OboNCBITaxon3603"
      OwlThing <|-- OboNCBITaxon3608
        click OboNCBITaxon3608 href "../OboNCBITaxon3608"
      OwlThing <|-- OboNCBITaxon3615
        click OboNCBITaxon3615 href "../OboNCBITaxon3615"
      OwlThing <|-- OboNCBITaxon3618
        click OboNCBITaxon3618 href "../OboNCBITaxon3618"
      OwlThing <|-- OboNCBITaxon3620
        click OboNCBITaxon3620 href "../OboNCBITaxon3620"
      OwlThing <|-- OboNCBITaxon3623
        click OboNCBITaxon3623 href "../OboNCBITaxon3623"
      OwlThing <|-- OboNCBITaxon3624
        click OboNCBITaxon3624 href "../OboNCBITaxon3624"
      OwlThing <|-- OboNCBITaxon3629
        click OboNCBITaxon3629 href "../OboNCBITaxon3629"
      OwlThing <|-- OboNCBITaxon3640
        click OboNCBITaxon3640 href "../OboNCBITaxon3640"
      OwlThing <|-- OboNCBITaxon364270
        click OboNCBITaxon364270 href "../OboNCBITaxon364270"
      OwlThing <|-- OboNCBITaxon3646
        click OboNCBITaxon3646 href "../OboNCBITaxon3646"
      OwlThing <|-- OboNCBITaxon3647
        click OboNCBITaxon3647 href "../OboNCBITaxon3647"
      OwlThing <|-- OboNCBITaxon3649
        click OboNCBITaxon3649 href "../OboNCBITaxon3649"
      OwlThing <|-- OboNCBITaxon3650
        click OboNCBITaxon3650 href "../OboNCBITaxon3650"
      OwlThing <|-- OboNCBITaxon3653
        click OboNCBITaxon3653 href "../OboNCBITaxon3653"
      OwlThing <|-- OboNCBITaxon3655
        click OboNCBITaxon3655 href "../OboNCBITaxon3655"
      OwlThing <|-- OboNCBITaxon3660
        click OboNCBITaxon3660 href "../OboNCBITaxon3660"
      OwlThing <|-- OboNCBITaxon36603
        click OboNCBITaxon36603 href "../OboNCBITaxon36603"
      OwlThing <|-- OboNCBITaxon36609
        click OboNCBITaxon36609 href "../OboNCBITaxon36609"
      OwlThing <|-- OboNCBITaxon3669
        click OboNCBITaxon3669 href "../OboNCBITaxon3669"
      OwlThing <|-- OboNCBITaxon3671
        click OboNCBITaxon3671 href "../OboNCBITaxon3671"
      OwlThing <|-- OboNCBITaxon3676
        click OboNCBITaxon3676 href "../OboNCBITaxon3676"
      OwlThing <|-- OboNCBITaxon3683
        click OboNCBITaxon3683 href "../OboNCBITaxon3683"
      OwlThing <|-- OboNCBITaxon3684
        click OboNCBITaxon3684 href "../OboNCBITaxon3684"
      OwlThing <|-- OboNCBITaxon3688
        click OboNCBITaxon3688 href "../OboNCBITaxon3688"
      OwlThing <|-- OboNCBITaxon3699
        click OboNCBITaxon3699 href "../OboNCBITaxon3699"
      OwlThing <|-- OboNCBITaxon3700
        click OboNCBITaxon3700 href "../OboNCBITaxon3700"
      OwlThing <|-- OboNCBITaxon3705
        click OboNCBITaxon3705 href "../OboNCBITaxon3705"
      OwlThing <|-- OboNCBITaxon3707
        click OboNCBITaxon3707 href "../OboNCBITaxon3707"
      OwlThing <|-- OboNCBITaxon3737
        click OboNCBITaxon3737 href "../OboNCBITaxon3737"
      OwlThing <|-- OboNCBITaxon3740
        click OboNCBITaxon3740 href "../OboNCBITaxon3740"
      OwlThing <|-- OboNCBITaxon3744
        click OboNCBITaxon3744 href "../OboNCBITaxon3744"
      OwlThing <|-- OboNCBITaxon3745
        click OboNCBITaxon3745 href "../OboNCBITaxon3745"
      OwlThing <|-- OboNCBITaxon3746
        click OboNCBITaxon3746 href "../OboNCBITaxon3746"
      OwlThing <|-- OboNCBITaxon3749
        click OboNCBITaxon3749 href "../OboNCBITaxon3749"
      OwlThing <|-- OboNCBITaxon3754
        click OboNCBITaxon3754 href "../OboNCBITaxon3754"
      OwlThing <|-- OboNCBITaxon3766
        click OboNCBITaxon3766 href "../OboNCBITaxon3766"
      OwlThing <|-- OboNCBITaxon3801
        click OboNCBITaxon3801 href "../OboNCBITaxon3801"
      OwlThing <|-- OboNCBITaxon3803
        click OboNCBITaxon3803 href "../OboNCBITaxon3803"
      OwlThing <|-- OboNCBITaxon3804
        click OboNCBITaxon3804 href "../OboNCBITaxon3804"
      OwlThing <|-- OboNCBITaxon3807
        click OboNCBITaxon3807 href "../OboNCBITaxon3807"
      OwlThing <|-- OboNCBITaxon381124
        click OboNCBITaxon381124 href "../OboNCBITaxon381124"
      OwlThing <|-- OboNCBITaxon3814
        click OboNCBITaxon3814 href "../OboNCBITaxon3814"
      OwlThing <|-- OboNCBITaxon3822
        click OboNCBITaxon3822 href "../OboNCBITaxon3822"
      OwlThing <|-- OboNCBITaxon3853
        click OboNCBITaxon3853 href "../OboNCBITaxon3853"
      OwlThing <|-- OboNCBITaxon38820
        click OboNCBITaxon38820 href "../OboNCBITaxon38820"
      OwlThing <|-- OboNCBITaxon3883
        click OboNCBITaxon3883 href "../OboNCBITaxon3883"
      OwlThing <|-- OboNCBITaxon3884
        click OboNCBITaxon3884 href "../OboNCBITaxon3884"
      OwlThing <|-- OboNCBITaxon3885
        click OboNCBITaxon3885 href "../OboNCBITaxon3885"
      OwlThing <|-- OboNCBITaxon3904
        click OboNCBITaxon3904 href "../OboNCBITaxon3904"
      OwlThing <|-- OboNCBITaxon3906
        click OboNCBITaxon3906 href "../OboNCBITaxon3906"
      OwlThing <|-- OboNCBITaxon3913
        click OboNCBITaxon3913 href "../OboNCBITaxon3913"
      OwlThing <|-- OboNCBITaxon3917
        click OboNCBITaxon3917 href "../OboNCBITaxon3917"
      OwlThing <|-- OboNCBITaxon3928
        click OboNCBITaxon3928 href "../OboNCBITaxon3928"
      OwlThing <|-- OboNCBITaxon3931
        click OboNCBITaxon3931 href "../OboNCBITaxon3931"
      OwlThing <|-- OboNCBITaxon4011
        click OboNCBITaxon4011 href "../OboNCBITaxon4011"
      OwlThing <|-- OboNCBITaxon4014
        click OboNCBITaxon4014 href "../OboNCBITaxon4014"
      OwlThing <|-- OboNCBITaxon4018
        click OboNCBITaxon4018 href "../OboNCBITaxon4018"
      OwlThing <|-- OboNCBITaxon4019
        click OboNCBITaxon4019 href "../OboNCBITaxon4019"
      OwlThing <|-- OboNCBITaxon4020
        click OboNCBITaxon4020 href "../OboNCBITaxon4020"
      OwlThing <|-- OboNCBITaxon4033
        click OboNCBITaxon4033 href "../OboNCBITaxon4033"
      OwlThing <|-- OboNCBITaxon4037
        click OboNCBITaxon4037 href "../OboNCBITaxon4037"
      OwlThing <|-- OboNCBITaxon4038
        click OboNCBITaxon4038 href "../OboNCBITaxon4038"
      OwlThing <|-- OboNCBITaxon4039
        click OboNCBITaxon4039 href "../OboNCBITaxon4039"
      OwlThing <|-- OboNCBITaxon40548
        click OboNCBITaxon40548 href "../OboNCBITaxon40548"
      OwlThing <|-- OboNCBITaxon4055
        click OboNCBITaxon4055 href "../OboNCBITaxon4055"
      OwlThing <|-- OboNCBITaxon4056
        click OboNCBITaxon4056 href "../OboNCBITaxon4056"
      OwlThing <|-- OboNCBITaxon40674
        click OboNCBITaxon40674 href "../OboNCBITaxon40674"
      OwlThing <|-- OboNCBITaxon40685
        click OboNCBITaxon40685 href "../OboNCBITaxon40685"
      OwlThing <|-- OboNCBITaxon4069
        click OboNCBITaxon4069 href "../OboNCBITaxon4069"
      OwlThing <|-- OboNCBITaxon4070
        click OboNCBITaxon4070 href "../OboNCBITaxon4070"
      OwlThing <|-- OboNCBITaxon4071
        click OboNCBITaxon4071 href "../OboNCBITaxon4071"
      OwlThing <|-- OboNCBITaxon4072
        click OboNCBITaxon4072 href "../OboNCBITaxon4072"
      OwlThing <|-- OboNCBITaxon4107
        click OboNCBITaxon4107 href "../OboNCBITaxon4107"
      OwlThing <|-- OboNCBITaxon4113
        click OboNCBITaxon4113 href "../OboNCBITaxon4113"
      OwlThing <|-- OboNCBITaxon4118
        click OboNCBITaxon4118 href "../OboNCBITaxon4118"
      OwlThing <|-- OboNCBITaxon4119
        click OboNCBITaxon4119 href "../OboNCBITaxon4119"
      OwlThing <|-- OboNCBITaxon4136
        click OboNCBITaxon4136 href "../OboNCBITaxon4136"
      OwlThing <|-- OboNCBITaxon4143
        click OboNCBITaxon4143 href "../OboNCBITaxon4143"
      OwlThing <|-- OboNCBITaxon4144
        click OboNCBITaxon4144 href "../OboNCBITaxon4144"
      OwlThing <|-- OboNCBITaxon41665
        click OboNCBITaxon41665 href "../OboNCBITaxon41665"
      OwlThing <|-- OboNCBITaxon41705
        click OboNCBITaxon41705 href "../OboNCBITaxon41705"
      OwlThing <|-- OboNCBITaxon41768
        click OboNCBITaxon41768 href "../OboNCBITaxon41768"
      OwlThing <|-- OboNCBITaxon41773
        click OboNCBITaxon41773 href "../OboNCBITaxon41773"
      OwlThing <|-- OboNCBITaxon41937
        click OboNCBITaxon41937 href "../OboNCBITaxon41937"
      OwlThing <|-- OboNCBITaxon41938
        click OboNCBITaxon41938 href "../OboNCBITaxon41938"
      OwlThing <|-- OboNCBITaxon41944
        click OboNCBITaxon41944 href "../OboNCBITaxon41944"
      OwlThing <|-- OboNCBITaxon41945
        click OboNCBITaxon41945 href "../OboNCBITaxon41945"
      OwlThing <|-- OboNCBITaxon41946
        click OboNCBITaxon41946 href "../OboNCBITaxon41946"
      OwlThing <|-- OboNCBITaxon41947
        click OboNCBITaxon41947 href "../OboNCBITaxon41947"
      OwlThing <|-- OboNCBITaxon4199
        click OboNCBITaxon4199 href "../OboNCBITaxon4199"
      OwlThing <|-- OboNCBITaxon4200
        click OboNCBITaxon4200 href "../OboNCBITaxon4200"
      OwlThing <|-- OboNCBITaxon4201
        click OboNCBITaxon4201 href "../OboNCBITaxon4201"
      OwlThing <|-- OboNCBITaxon4204
        click OboNCBITaxon4204 href "../OboNCBITaxon4204"
      OwlThing <|-- OboNCBITaxon4206
        click OboNCBITaxon4206 href "../OboNCBITaxon4206"
      OwlThing <|-- OboNCBITaxon4210
        click OboNCBITaxon4210 href "../OboNCBITaxon4210"
      OwlThing <|-- OboNCBITaxon42148
        click OboNCBITaxon42148 href "../OboNCBITaxon42148"
      OwlThing <|-- OboNCBITaxon4216
        click OboNCBITaxon4216 href "../OboNCBITaxon4216"
      OwlThing <|-- OboNCBITaxon42219
        click OboNCBITaxon42219 href "../OboNCBITaxon42219"
      OwlThing <|-- OboNCBITaxon4231
        click OboNCBITaxon4231 href "../OboNCBITaxon4231"
      OwlThing <|-- OboNCBITaxon4235
        click OboNCBITaxon4235 href "../OboNCBITaxon4235"
      OwlThing <|-- OboNCBITaxon424551
        click OboNCBITaxon424551 href "../OboNCBITaxon424551"
      OwlThing <|-- OboNCBITaxon424573
        click OboNCBITaxon424573 href "../OboNCBITaxon424573"
      OwlThing <|-- OboNCBITaxon426106
        click OboNCBITaxon426106 href "../OboNCBITaxon426106"
      OwlThing <|-- OboNCBITaxon4268
        click OboNCBITaxon4268 href "../OboNCBITaxon4268"
      OwlThing <|-- OboNCBITaxon4281
        click OboNCBITaxon4281 href "../OboNCBITaxon4281"
      OwlThing <|-- OboNCBITaxon4294
        click OboNCBITaxon4294 href "../OboNCBITaxon4294"
      OwlThing <|-- OboNCBITaxon432663
        click OboNCBITaxon432663 href "../OboNCBITaxon432663"
      OwlThing <|-- OboNCBITaxon4335
        click OboNCBITaxon4335 href "../OboNCBITaxon4335"
      OwlThing <|-- OboNCBITaxon4345
        click OboNCBITaxon4345 href "../OboNCBITaxon4345"
      OwlThing <|-- OboNCBITaxon43690
        click OboNCBITaxon43690 href "../OboNCBITaxon43690"
      OwlThing <|-- OboNCBITaxon43707
        click OboNCBITaxon43707 href "../OboNCBITaxon43707"
      OwlThing <|-- OboNCBITaxon43860
        click OboNCBITaxon43860 href "../OboNCBITaxon43860"
      OwlThing <|-- OboNCBITaxon4410
        click OboNCBITaxon4410 href "../OboNCBITaxon4410"
      OwlThing <|-- OboNCBITaxon4447
        click OboNCBITaxon4447 href "../OboNCBITaxon4447"
      OwlThing <|-- OboNCBITaxon4454
        click OboNCBITaxon4454 href "../OboNCBITaxon4454"
      OwlThing <|-- OboNCBITaxon4479
        click OboNCBITaxon4479 href "../OboNCBITaxon4479"
      OwlThing <|-- OboNCBITaxon4577
        click OboNCBITaxon4577 href "../OboNCBITaxon4577"
      OwlThing <|-- OboNCBITaxon4581
        click OboNCBITaxon4581 href "../OboNCBITaxon4581"
      OwlThing <|-- OboNCBITaxon45918
        click OboNCBITaxon45918 href "../OboNCBITaxon45918"
      OwlThing <|-- OboNCBITaxon4609
        click OboNCBITaxon4609 href "../OboNCBITaxon4609"
      OwlThing <|-- OboNCBITaxon4610
        click OboNCBITaxon4610 href "../OboNCBITaxon4610"
      OwlThing <|-- OboNCBITaxon4613
        click OboNCBITaxon4613 href "../OboNCBITaxon4613"
      OwlThing <|-- OboNCBITaxon46145
        click OboNCBITaxon46145 href "../OboNCBITaxon46145"
      OwlThing <|-- OboNCBITaxon4615
        click OboNCBITaxon4615 href "../OboNCBITaxon4615"
      OwlThing <|-- OboNCBITaxon4618
        click OboNCBITaxon4618 href "../OboNCBITaxon4618"
      OwlThing <|-- OboNCBITaxon46260
        click OboNCBITaxon46260 href "../OboNCBITaxon46260"
      OwlThing <|-- OboNCBITaxon4637
        click OboNCBITaxon4637 href "../OboNCBITaxon4637"
      OwlThing <|-- OboNCBITaxon4638
        click OboNCBITaxon4638 href "../OboNCBITaxon4638"
      OwlThing <|-- OboNCBITaxon4639
        click OboNCBITaxon4639 href "../OboNCBITaxon4639"
      OwlThing <|-- OboNCBITaxon4640
        click OboNCBITaxon4640 href "../OboNCBITaxon4640"
      OwlThing <|-- OboNCBITaxon4641
        click OboNCBITaxon4641 href "../OboNCBITaxon4641"
      OwlThing <|-- OboNCBITaxon4642
        click OboNCBITaxon4642 href "../OboNCBITaxon4642"
      OwlThing <|-- OboNCBITaxon4668
        click OboNCBITaxon4668 href "../OboNCBITaxon4668"
      OwlThing <|-- OboNCBITaxon4671
        click OboNCBITaxon4671 href "../OboNCBITaxon4671"
      OwlThing <|-- OboNCBITaxon4678
        click OboNCBITaxon4678 href "../OboNCBITaxon4678"
      OwlThing <|-- OboNCBITaxon4710
        click OboNCBITaxon4710 href "../OboNCBITaxon4710"
      OwlThing <|-- OboNCBITaxon4719
        click OboNCBITaxon4719 href "../OboNCBITaxon4719"
      OwlThing <|-- OboNCBITaxon4731
        click OboNCBITaxon4731 href "../OboNCBITaxon4731"
      OwlThing <|-- OboNCBITaxon4732
        click OboNCBITaxon4732 href "../OboNCBITaxon4732"
      OwlThing <|-- OboNCBITaxon4734
        click OboNCBITaxon4734 href "../OboNCBITaxon4734"
      OwlThing <|-- OboNCBITaxon47605
        click OboNCBITaxon47605 href "../OboNCBITaxon47605"
      OwlThing <|-- OboNCBITaxon479623
        click OboNCBITaxon479623 href "../OboNCBITaxon479623"
      OwlThing <|-- OboNCBITaxon50173
        click OboNCBITaxon50173 href "../OboNCBITaxon50173"
      OwlThing <|-- OboNCBITaxon50174
        click OboNCBITaxon50174 href "../OboNCBITaxon50174"
      OwlThing <|-- OboNCBITaxon50190
        click OboNCBITaxon50190 href "../OboNCBITaxon50190"
      OwlThing <|-- OboNCBITaxon50384
        click OboNCBITaxon50384 href "../OboNCBITaxon50384"
      OwlThing <|-- OboNCBITaxon504568
        click OboNCBITaxon504568 href "../OboNCBITaxon504568"
      OwlThing <|-- OboNCBITaxon50457
        click OboNCBITaxon50457 href "../OboNCBITaxon50457"
      OwlThing <|-- OboNCBITaxon516948
        click OboNCBITaxon516948 href "../OboNCBITaxon516948"
      OwlThing <|-- OboNCBITaxon51952
        click OboNCBITaxon51952 href "../OboNCBITaxon51952"
      OwlThing <|-- OboNCBITaxon52838
        click OboNCBITaxon52838 href "../OboNCBITaxon52838"
      OwlThing <|-- OboNCBITaxon53868
        click OboNCBITaxon53868 href "../OboNCBITaxon53868"
      OwlThing <|-- OboNCBITaxon54476
        click OboNCBITaxon54476 href "../OboNCBITaxon54476"
      OwlThing <|-- OboNCBITaxon557010
        click OboNCBITaxon557010 href "../OboNCBITaxon557010"
      OwlThing <|-- OboNCBITaxon55961
        click OboNCBITaxon55961 href "../OboNCBITaxon55961"
      OwlThing <|-- OboNCBITaxon57918
        click OboNCBITaxon57918 href "../OboNCBITaxon57918"
      OwlThing <|-- OboNCBITaxon58023
        click OboNCBITaxon58023 href "../OboNCBITaxon58023"
      OwlThing <|-- OboNCBITaxon58024
        click OboNCBITaxon58024 href "../OboNCBITaxon58024"
      OwlThing <|-- OboNCBITaxon58228
        click OboNCBITaxon58228 href "../OboNCBITaxon58228"
      OwlThing <|-- OboNCBITaxon58486
        click OboNCBITaxon58486 href "../OboNCBITaxon58486"
      OwlThing <|-- OboNCBITaxon58860
        click OboNCBITaxon58860 href "../OboNCBITaxon58860"
      OwlThing <|-- OboNCBITaxon59165
        click OboNCBITaxon59165 href "../OboNCBITaxon59165"
      OwlThing <|-- OboNCBITaxon6072
        click OboNCBITaxon6072 href "../OboNCBITaxon6072"
      OwlThing <|-- OboNCBITaxon641307
        click OboNCBITaxon641307 href "../OboNCBITaxon641307"
      OwlThing <|-- OboNCBITaxon6447
        click OboNCBITaxon6447 href "../OboNCBITaxon6447"
      OwlThing <|-- OboNCBITaxon6544
        click OboNCBITaxon6544 href "../OboNCBITaxon6544"
      OwlThing <|-- OboNCBITaxon6545
        click OboNCBITaxon6545 href "../OboNCBITaxon6545"
      OwlThing <|-- OboNCBITaxon6547
        click OboNCBITaxon6547 href "../OboNCBITaxon6547"
      OwlThing <|-- OboNCBITaxon6548
        click OboNCBITaxon6548 href "../OboNCBITaxon6548"
      OwlThing <|-- OboNCBITaxon6550
        click OboNCBITaxon6550 href "../OboNCBITaxon6550"
      OwlThing <|-- OboNCBITaxon6599
        click OboNCBITaxon6599 href "../OboNCBITaxon6599"
      OwlThing <|-- OboNCBITaxon6602
        click OboNCBITaxon6602 href "../OboNCBITaxon6602"
      OwlThing <|-- OboNCBITaxon6604
        click OboNCBITaxon6604 href "../OboNCBITaxon6604"
      OwlThing <|-- OboNCBITaxon6605
        click OboNCBITaxon6605 href "../OboNCBITaxon6605"
      OwlThing <|-- OboNCBITaxon6606
        click OboNCBITaxon6606 href "../OboNCBITaxon6606"
      OwlThing <|-- OboNCBITaxon66670
        click OboNCBITaxon66670 href "../OboNCBITaxon66670"
      OwlThing <|-- OboNCBITaxon66672
        click OboNCBITaxon66672 href "../OboNCBITaxon66672"
      OwlThing <|-- OboNCBITaxon69108
        click OboNCBITaxon69108 href "../OboNCBITaxon69108"
      OwlThing <|-- OboNCBITaxon69109
        click OboNCBITaxon69109 href "../OboNCBITaxon69109"
      OwlThing <|-- OboNCBITaxon693794
        click OboNCBITaxon693794 href "../OboNCBITaxon693794"
      OwlThing <|-- OboNCBITaxon703407
        click OboNCBITaxon703407 href "../OboNCBITaxon703407"
      OwlThing <|-- OboNCBITaxon71243
        click OboNCBITaxon71243 href "../OboNCBITaxon71243"
      OwlThing <|-- OboNCBITaxon71274
        click OboNCBITaxon71274 href "../OboNCBITaxon71274"
      OwlThing <|-- OboNCBITaxon71275
        click OboNCBITaxon71275 href "../OboNCBITaxon71275"
      OwlThing <|-- OboNCBITaxon71611
        click OboNCBITaxon71611 href "../OboNCBITaxon71611"
      OwlThing <|-- OboNCBITaxon72025
        click OboNCBITaxon72025 href "../OboNCBITaxon72025"
      OwlThing <|-- OboNCBITaxon72171
        click OboNCBITaxon72171 href "../OboNCBITaxon72171"
      OwlThing <|-- OboNCBITaxon721789
        click OboNCBITaxon721789 href "../OboNCBITaxon721789"
      OwlThing <|-- OboNCBITaxon721813
        click OboNCBITaxon721813 href "../OboNCBITaxon721813"
      OwlThing <|-- OboNCBITaxon73496
        click OboNCBITaxon73496 href "../OboNCBITaxon73496"
      OwlThing <|-- OboNCBITaxon742010
        click OboNCBITaxon742010 href "../OboNCBITaxon742010"
      OwlThing <|-- OboNCBITaxon745060
        click OboNCBITaxon745060 href "../OboNCBITaxon745060"
      OwlThing <|-- OboNCBITaxon7711
        click OboNCBITaxon7711 href "../OboNCBITaxon7711"
      OwlThing <|-- OboNCBITaxon7742
        click OboNCBITaxon7742 href "../OboNCBITaxon7742"
      OwlThing <|-- OboNCBITaxon7776
        click OboNCBITaxon7776 href "../OboNCBITaxon7776"
      OwlThing <|-- OboNCBITaxon78536
        click OboNCBITaxon78536 href "../OboNCBITaxon78536"
      OwlThing <|-- OboNCBITaxon7898
        click OboNCBITaxon7898 href "../OboNCBITaxon7898"
      OwlThing <|-- OboNCBITaxon79331
        click OboNCBITaxon79331 href "../OboNCBITaxon79331"
      OwlThing <|-- OboNCBITaxon7952
        click OboNCBITaxon7952 href "../OboNCBITaxon7952"
      OwlThing <|-- OboNCBITaxon7968
        click OboNCBITaxon7968 href "../OboNCBITaxon7968"
      OwlThing <|-- OboNCBITaxon7969
        click OboNCBITaxon7969 href "../OboNCBITaxon7969"
      OwlThing <|-- OboNCBITaxon7971
        click OboNCBITaxon7971 href "../OboNCBITaxon7971"
      OwlThing <|-- OboNCBITaxon7995
        click OboNCBITaxon7995 href "../OboNCBITaxon7995"
      OwlThing <|-- OboNCBITaxon7996
        click OboNCBITaxon7996 href "../OboNCBITaxon7996"
      OwlThing <|-- OboNCBITaxon8006
        click OboNCBITaxon8006 href "../OboNCBITaxon8006"
      OwlThing <|-- OboNCBITaxon8007
        click OboNCBITaxon8007 href "../OboNCBITaxon8007"
      OwlThing <|-- OboNCBITaxon8008
        click OboNCBITaxon8008 href "../OboNCBITaxon8008"
      OwlThing <|-- OboNCBITaxon8009
        click OboNCBITaxon8009 href "../OboNCBITaxon8009"
      OwlThing <|-- OboNCBITaxon8010
        click OboNCBITaxon8010 href "../OboNCBITaxon8010"
      OwlThing <|-- OboNCBITaxon8015
        click OboNCBITaxon8015 href "../OboNCBITaxon8015"
      OwlThing <|-- OboNCBITaxon8033
        click OboNCBITaxon8033 href "../OboNCBITaxon8033"
      OwlThing <|-- OboNCBITaxon8038
        click OboNCBITaxon8038 href "../OboNCBITaxon8038"
      OwlThing <|-- OboNCBITaxon8111
        click OboNCBITaxon8111 href "../OboNCBITaxon8111"
      OwlThing <|-- OboNCBITaxon8112
        click OboNCBITaxon8112 href "../OboNCBITaxon8112"
      OwlThing <|-- OboNCBITaxon8165
        click OboNCBITaxon8165 href "../OboNCBITaxon8165"
      OwlThing <|-- OboNCBITaxon8166
        click OboNCBITaxon8166 href "../OboNCBITaxon8166"
      OwlThing <|-- OboNCBITaxon8167
        click OboNCBITaxon8167 href "../OboNCBITaxon8167"
      OwlThing <|-- OboNCBITaxon8180
        click OboNCBITaxon8180 href "../OboNCBITaxon8180"
      OwlThing <|-- OboNCBITaxon8181
        click OboNCBITaxon8181 href "../OboNCBITaxon8181"
      OwlThing <|-- OboNCBITaxon8182
        click OboNCBITaxon8182 href "../OboNCBITaxon8182"
      OwlThing <|-- OboNCBITaxon83431
        click OboNCBITaxon83431 href "../OboNCBITaxon83431"
      OwlThing <|-- OboNCBITaxon84005
        click OboNCBITaxon84005 href "../OboNCBITaxon84005"
      OwlThing <|-- OboNCBITaxon84860
        click OboNCBITaxon84860 href "../OboNCBITaxon84860"
      OwlThing <|-- OboNCBITaxon8492
        click OboNCBITaxon8492 href "../OboNCBITaxon8492"
      OwlThing <|-- OboNCBITaxon85249
        click OboNCBITaxon85249 href "../OboNCBITaxon85249"
      OwlThing <|-- OboNCBITaxon85571
        click OboNCBITaxon85571 href "../OboNCBITaxon85571"
      OwlThing <|-- OboNCBITaxon866800
        click OboNCBITaxon866800 href "../OboNCBITaxon866800"
      OwlThing <|-- OboNCBITaxon8782
        click OboNCBITaxon8782 href "../OboNCBITaxon8782"
      OwlThing <|-- OboNCBITaxon8825
        click OboNCBITaxon8825 href "../OboNCBITaxon8825"
      OwlThing <|-- OboNCBITaxon89151
        click OboNCBITaxon89151 href "../OboNCBITaxon89151"
      OwlThing <|-- OboNCBITaxon8976
        click OboNCBITaxon8976 href "../OboNCBITaxon8976"
      OwlThing <|-- OboNCBITaxon9005
        click OboNCBITaxon9005 href "../OboNCBITaxon9005"
      OwlThing <|-- OboNCBITaxon9031
        click OboNCBITaxon9031 href "../OboNCBITaxon9031"
      OwlThing <|-- OboNCBITaxon9072
        click OboNCBITaxon9072 href "../OboNCBITaxon9072"
      OwlThing <|-- OboNCBITaxon9102
        click OboNCBITaxon9102 href "../OboNCBITaxon9102"
      OwlThing <|-- OboNCBITaxon9103
        click OboNCBITaxon9103 href "../OboNCBITaxon9103"
      OwlThing <|-- OboNCBITaxon911341
        click OboNCBITaxon911341 href "../OboNCBITaxon911341"
      OwlThing <|-- OboNCBITaxon91561
        click OboNCBITaxon91561 href "../OboNCBITaxon91561"
      OwlThing <|-- OboNCBITaxon91835
        click OboNCBITaxon91835 href "../OboNCBITaxon91835"
      OwlThing <|-- OboNCBITaxon91836
        click OboNCBITaxon91836 href "../OboNCBITaxon91836"
      OwlThing <|-- OboNCBITaxon91882
        click OboNCBITaxon91882 href "../OboNCBITaxon91882"
      OwlThing <|-- OboNCBITaxon91888
        click OboNCBITaxon91888 href "../OboNCBITaxon91888"
      OwlThing <|-- OboNCBITaxon9347
        click OboNCBITaxon9347 href "../OboNCBITaxon9347"
      OwlThing <|-- OboNCBITaxon96479
        click OboNCBITaxon96479 href "../OboNCBITaxon96479"
      OwlThing <|-- OboNCBITaxon980193
        click OboNCBITaxon980193 href "../OboNCBITaxon980193"
      OwlThing <|-- OboNCBITaxon981071
        click OboNCBITaxon981071 href "../OboNCBITaxon981071"
      OwlThing <|-- OboNCBITaxon9821
        click OboNCBITaxon9821 href "../OboNCBITaxon9821"
      OwlThing <|-- OboNCBITaxon9823
        click OboNCBITaxon9823 href "../OboNCBITaxon9823"
      OwlThing <|-- OboNCBITaxon9825
        click OboNCBITaxon9825 href "../OboNCBITaxon9825"
      OwlThing <|-- OboNCBITaxon9850
        click OboNCBITaxon9850 href "../OboNCBITaxon9850"
      OwlThing <|-- OboNCBITaxon986140
        click OboNCBITaxon986140 href "../OboNCBITaxon986140"
      OwlThing <|-- OboNCBITaxon9895
        click OboNCBITaxon9895 href "../OboNCBITaxon9895"
      OwlThing <|-- OboNCBITaxon9900
        click OboNCBITaxon9900 href "../OboNCBITaxon9900"
      OwlThing <|-- OboNCBITaxon9903
        click OboNCBITaxon9903 href "../OboNCBITaxon9903"
      OwlThing <|-- OboNCBITaxon9913
        click OboNCBITaxon9913 href "../OboNCBITaxon9913"
      OwlThing <|-- OboNCBITaxon9922
        click OboNCBITaxon9922 href "../OboNCBITaxon9922"
      OwlThing <|-- OboNCBITaxon9925
        click OboNCBITaxon9925 href "../OboNCBITaxon9925"
      OwlThing <|-- OboNCBITaxon9935
        click OboNCBITaxon9935 href "../OboNCBITaxon9935"
      OwlThing <|-- OboNCBITaxon9940
        click OboNCBITaxon9940 href "../OboNCBITaxon9940"
      OwlThing <|-- OboNCBITaxon99568
        click OboNCBITaxon99568 href "../OboNCBITaxon99568"
      OwlThing <|-- OboNCBITaxon9963
        click OboNCBITaxon9963 href "../OboNCBITaxon9963"
      OwlThing <|-- OboNCBITaxon9989
        click OboNCBITaxon9989 href "../OboNCBITaxon9989"
      OwlThing <|-- OboOBI0100026
        click OboOBI0100026 href "../OboOBI0100026"
      OwlThing <|-- OboPO0000003
        click OboPO0000003 href "../OboPO0000003"
      OwlThing <|-- OboPO0025034
        click OboPO0025034 href "../OboPO0025034"
      OwlThing <|-- OboUBERON0000948
        click OboUBERON0000948 href "../OboUBERON0000948"
      OwlThing <|-- OboUBERON0001913
        click OboUBERON0001913 href "../OboUBERON0001913"
      OwlThing <|-- OboUBERON0002097
        click OboUBERON0002097 href "../OboUBERON0002097"
      OwlThing <|-- OboUBERON0002107
        click OboUBERON0002107 href "../OboUBERON0002107"
      OwlThing <|-- OboUBERON0005079
        click OboUBERON0005079 href "../OboUBERON0005079"
      OwlThing <|-- OboUBERON0007378
        click OboUBERON0007378 href "../OboUBERON0007378"
      OwlThing <|-- OboUBERON0007379
        click OboUBERON0007379 href "../OboUBERON0007379"
      OwlThing <|-- OboUBERON0008944
        click OboUBERON0008944 href "../OboUBERON0008944"
      OwlThing <|-- QudtEnumeratedQuantity
        click QudtEnumeratedQuantity href "../QudtEnumeratedQuantity"
      OwlThing <|-- SosaProcedure
        click SosaProcedure href "../SosaProcedure"
      OwlThing <|-- SosaProperty
        click SosaProperty href "../SosaProperty"
      OwlThing <|-- SosaSample
        click SosaSample href "../SosaSample"
      OwlThing <|-- StadQualityKind
        click StadQualityKind href "../StadQualityKind"
      OwlThing <|-- StadQuantity
        click StadQuantity href "../StadQuantity"
      OwlThing <|-- StadSingleData
        click StadSingleData href "../StadSingleData"
      OwlThing <|-- StadStatisticalAggregateData
        click StadStatisticalAggregateData href "../StadStatisticalAggregateData"
      OwlThing <|-- StadStatisticalQuantityKind
        click StadStatisticalQuantityKind href "../StadStatisticalQuantityKind"
      
      
```





## Inheritance
* **OwlThing**
    * [OwlNamedIndividual](../classes/OwlNamedIndividual.md)
    * [OwlNothing](../classes/OwlNothing.md)
    * [QudtComment](../classes/QudtComment.md)
    * [QudtConcept](../classes/QudtConcept.md)
    * [ProvSoftwareAgent](../classes/ProvSoftwareAgent.md)
    * [DtypeEnumeratedValue](../classes/DtypeEnumeratedValue.md)
    * [DtypeEnumeration](../classes/DtypeEnumeration.md)
    * [DtypeValueReference](../classes/DtypeValueReference.md)
    * [VaemDimension](../classes/VaemDimension.md)
    * [VaemGraphMetaData](../classes/VaemGraphMetaData.md)
    * [VaemGraphRole](../classes/VaemGraphRole.md)
    * [VaemParty](../classes/VaemParty.md)
    * [TimeDayOfWeek](../classes/TimeDayOfWeek.md)
    * [TimeTemporalEntity](../classes/TimeTemporalEntity.md)
    * [FoafOnlineAccount](../classes/FoafOnlineAccount.md)
    * [VoagAssignedRole](../classes/VoagAssignedRole.md)
    * [VoagCreativeCommonsJurisdiction](../classes/VoagCreativeCommonsJurisdiction.md)
    * [VoagCreativeCommonsWork](../classes/VoagCreativeCommonsWork.md)
    * [VoagDocument](../classes/VoagDocument.md)
    * [VoagEvent](../classes/VoagEvent.md)
    * [VoagImage](../classes/VoagImage.md)
    * [VoagIssue](../classes/VoagIssue.md)
    * [VoagProcess](../classes/VoagProcess.md)
    * [VoagQualifier](../classes/VoagQualifier.md)
    * [VoagService](../classes/VoagService.md)
    * [CosoDetectQuantityValue](../classes/CosoDetectQuantityValue.md)
    * [CosoDetectionLimit](../classes/CosoDetectionLimit.md)
    * [CosoFeatureType](../classes/CosoFeatureType.md)
    * [CosoNonDetectQuantityValue](../classes/CosoNonDetectQuantityValue.md)
    * [CosoObservationAnnotation](../classes/CosoObservationAnnotation.md)
    * [CosoQuantitationLimit](../classes/CosoQuantitationLimit.md)
    * [CosoQuantityValue](../classes/CosoQuantityValue.md)
    * [CosoResultQualifier](../classes/CosoResultQualifier.md)
    * [CosoSampleAnnotation](../classes/CosoSampleAnnotation.md)
    * [CosoSampleMaterialType](../classes/CosoSampleMaterialType.md)
    * [CosoSubstance](../classes/CosoSubstance.md)
    * [CosoSubstanceCollection](../classes/CosoSubstanceCollection.md)
    * [CosoOfComptoxSubstance](../classes/CosoOfComptoxSubstance.md)
    * [CosoOfDatasetSubstance](../classes/CosoOfDatasetSubstance.md)
    * [HttpW3id.orgComptoxCompToxChemicalEntity](../classes/HttpW3id.orgComptoxCompToxChemicalEntity.md)
    * [HttpW3id.orgSawgraphV1Me-egad#EGAD-ConcentrationQualifier](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ConcentrationQualifier.md)
    * [HttpW3id.orgSawgraphV1Me-egad#EGAD-MethodDetectionLimit](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-MethodDetectionLimit.md)
    * [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName.md)
    * [HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit.md)
    * [HttpW3id.orgSawgraphV1Me-egad#EGAD-ResultType](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ResultType.md)
    * [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleCollectionMethod](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleCollectionMethod.md)
    * [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleDetailedLocation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleDetailedLocation.md)
    * [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialType](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialType.md)
    * [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialTypeQualifier](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialTypeQualifier.md)
    * [HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePointType](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePointType.md)
    * [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleTreatmentStatus](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleTreatmentStatus.md)
    * [HttpW3id.orgSawgraphV1Me-egad#EGAD-SiteType](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SiteType.md)
    * [HttpW3id.orgSawgraphV1Me-egad#EGAD-ValidationLevel](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ValidationLevel.md)
    * [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md)
    * [KwgoStatisticalArea](../classes/KwgoStatisticalArea.md)
    * [MeEgadEGAD-ConcentrationQualifier](../classes/MeEgadEGAD-ConcentrationQualifier.md)
    * [MeEgadEGAD-MethodDetectionLimit](../classes/MeEgadEGAD-MethodDetectionLimit.md)
    * [MeEgadEGAD-PFAS-ParameterName](../classes/MeEgadEGAD-PFAS-ParameterName.md)
    * [MeEgadEGAD-ReportingLimit](../classes/MeEgadEGAD-ReportingLimit.md)
    * [MeEgadEGAD-ResultType](../classes/MeEgadEGAD-ResultType.md)
    * [MeEgadEGAD-SampleCollectionMethod](../classes/MeEgadEGAD-SampleCollectionMethod.md)
    * [MeEgadEGAD-SampleDetailedLocation](../classes/MeEgadEGAD-SampleDetailedLocation.md)
    * [MeEgadEGAD-SampleMaterialType](../classes/MeEgadEGAD-SampleMaterialType.md)
    * [MeEgadEGAD-SampleMaterialTypeQualifier](../classes/MeEgadEGAD-SampleMaterialTypeQualifier.md)
    * [MeEgadEGAD-SamplePointType](../classes/MeEgadEGAD-SamplePointType.md)
    * [MeEgadEGAD-SampleTreatmentStatus](../classes/MeEgadEGAD-SampleTreatmentStatus.md)
    * [MeEgadEGAD-SiteType](../classes/MeEgadEGAD-SiteType.md)
    * [MeEgadEGAD-ValidationLevel](../classes/MeEgadEGAD-ValidationLevel.md)
    * [OboBFO0000040](../classes/OboBFO0000040.md)
    * [OboFOODON00001002](../classes/OboFOODON00001002.md)
    * [OboFOODON00001006](../classes/OboFOODON00001006.md)
    * [OboFOODON00001015](../classes/OboFOODON00001015.md)
    * [OboFOODON00001040](../classes/OboFOODON00001040.md)
    * [OboFOODON00001041](../classes/OboFOODON00001041.md)
    * [OboFOODON00001046](../classes/OboFOODON00001046.md)
    * [OboFOODON00001057](../classes/OboFOODON00001057.md)
    * [OboFOODON00001092](../classes/OboFOODON00001092.md)
    * [OboFOODON00001093](../classes/OboFOODON00001093.md)
    * [OboFOODON00001105](../classes/OboFOODON00001105.md)
    * [OboFOODON00001131](../classes/OboFOODON00001131.md)
    * [OboFOODON00001134](../classes/OboFOODON00001134.md)
    * [OboFOODON00001147](../classes/OboFOODON00001147.md)
    * [OboFOODON00001172](../classes/OboFOODON00001172.md)
    * [OboFOODON00001173](../classes/OboFOODON00001173.md)
    * [OboFOODON00001175](../classes/OboFOODON00001175.md)
    * [OboFOODON00001176](../classes/OboFOODON00001176.md)
    * [OboFOODON00001209](../classes/OboFOODON00001209.md)
    * [OboFOODON00001242](../classes/OboFOODON00001242.md)
    * [OboFOODON00001248](../classes/OboFOODON00001248.md)
    * [OboFOODON00001250](../classes/OboFOODON00001250.md)
    * [OboFOODON00001251](../classes/OboFOODON00001251.md)
    * [OboFOODON00001256](../classes/OboFOODON00001256.md)
    * [OboFOODON00001257](../classes/OboFOODON00001257.md)
    * [OboFOODON00001261](../classes/OboFOODON00001261.md)
    * [OboFOODON00001262](../classes/OboFOODON00001262.md)
    * [OboFOODON00001264](../classes/OboFOODON00001264.md)
    * [OboFOODON00001274](../classes/OboFOODON00001274.md)
    * [OboFOODON00001275](../classes/OboFOODON00001275.md)
    * [OboFOODON00001283](../classes/OboFOODON00001283.md)
    * [OboFOODON00001291](../classes/OboFOODON00001291.md)
    * [OboFOODON00001293](../classes/OboFOODON00001293.md)
    * [OboFOODON00001628](../classes/OboFOODON00001628.md)
    * [OboFOODON00001635](../classes/OboFOODON00001635.md)
    * [OboFOODON00001678](../classes/OboFOODON00001678.md)
    * [OboFOODON00001783](../classes/OboFOODON00001783.md)
    * [OboFOODON00001792](../classes/OboFOODON00001792.md)
    * [OboFOODON00002044](../classes/OboFOODON00002044.md)
    * [OboFOODON00002051](../classes/OboFOODON00002051.md)
    * [OboFOODON00002140](../classes/OboFOODON00002140.md)
    * [OboFOODON00002142](../classes/OboFOODON00002142.md)
    * [OboFOODON00002143](../classes/OboFOODON00002143.md)
    * [OboFOODON00002147](../classes/OboFOODON00002147.md)
    * [OboFOODON00002150](../classes/OboFOODON00002150.md)
    * [OboFOODON00002153](../classes/OboFOODON00002153.md)
    * [OboFOODON00002156](../classes/OboFOODON00002156.md)
    * [OboFOODON00002159](../classes/OboFOODON00002159.md)
    * [OboFOODON00002165](../classes/OboFOODON00002165.md)
    * [OboFOODON00002236](../classes/OboFOODON00002236.md)
    * [OboFOODON00002265](../classes/OboFOODON00002265.md)
    * [OboFOODON00002309](../classes/OboFOODON00002309.md)
    * [OboFOODON00002381](../classes/OboFOODON00002381.md)
    * [OboFOODON00002403](../classes/OboFOODON00002403.md)
    * [OboFOODON00002452](../classes/OboFOODON00002452.md)
    * [OboFOODON00002477](../classes/OboFOODON00002477.md)
    * [OboFOODON00002576](../classes/OboFOODON00002576.md)
    * [OboFOODON00002581](../classes/OboFOODON00002581.md)
    * [OboFOODON00002616](../classes/OboFOODON00002616.md)
    * [OboFOODON00002689](../classes/OboFOODON00002689.md)
    * [OboFOODON00002753](../classes/OboFOODON00002753.md)
    * [OboFOODON00002765](../classes/OboFOODON00002765.md)
    * [OboFOODON00002819](../classes/OboFOODON00002819.md)
    * [OboFOODON00003004](../classes/OboFOODON00003004.md)
    * [OboFOODON00003042](../classes/OboFOODON00003042.md)
    * [OboFOODON00003083](../classes/OboFOODON00003083.md)
    * [OboFOODON00003204](../classes/OboFOODON00003204.md)
    * [OboFOODON00003425](../classes/OboFOODON00003425.md)
    * [OboFOODON00003567](../classes/OboFOODON00003567.md)
    * [OboFOODON00003572](../classes/OboFOODON00003572.md)
    * [OboFOODON00003814](../classes/OboFOODON00003814.md)
    * [OboFOODON00003816](../classes/OboFOODON00003816.md)
    * [OboFOODON00004172](../classes/OboFOODON00004172.md)
    * [OboFOODON00004183](../classes/OboFOODON00004183.md)
    * [OboFOODON00004242](../classes/OboFOODON00004242.md)
    * [OboFOODON00004298](../classes/OboFOODON00004298.md)
    * [OboFOODON00004331](../classes/OboFOODON00004331.md)
    * [OboFOODON00004332](../classes/OboFOODON00004332.md)
    * [OboFOODON00004333](../classes/OboFOODON00004333.md)
    * [OboFOODON00004436](../classes/OboFOODON00004436.md)
    * [OboFOODON00004460](../classes/OboFOODON00004460.md)
    * [OboFOODON00004859](../classes/OboFOODON00004859.md)
    * [OboFOODON00004862](../classes/OboFOODON00004862.md)
    * [OboFOODON00004918](../classes/OboFOODON00004918.md)
    * [OboFOODON00004921](../classes/OboFOODON00004921.md)
    * [OboFOODON02010001](../classes/OboFOODON02010001.md)
    * [OboFOODON02010005](../classes/OboFOODON02010005.md)
    * [OboFOODON02010006](../classes/OboFOODON02010006.md)
    * [OboFOODON02010012](../classes/OboFOODON02010012.md)
    * [OboFOODON02010013](../classes/OboFOODON02010013.md)
    * [OboFOODON02010014](../classes/OboFOODON02010014.md)
    * [OboFOODON02010015](../classes/OboFOODON02010015.md)
    * [OboFOODON02010024](../classes/OboFOODON02010024.md)
    * [OboFOODON02010028](../classes/OboFOODON02010028.md)
    * [OboFOODON02010029](../classes/OboFOODON02010029.md)
    * [OboFOODON02010030](../classes/OboFOODON02010030.md)
    * [OboFOODON02010031](../classes/OboFOODON02010031.md)
    * [OboFOODON02010032](../classes/OboFOODON02010032.md)
    * [OboFOODON02010033](../classes/OboFOODON02010033.md)
    * [OboFOODON02010042](../classes/OboFOODON02010042.md)
    * [OboFOODON02010045](../classes/OboFOODON02010045.md)
    * [OboFOODON02010107](../classes/OboFOODON02010107.md)
    * [OboFOODON02010108](../classes/OboFOODON02010108.md)
    * [OboFOODON02010111](../classes/OboFOODON02010111.md)
    * [OboFOODON02010112](../classes/OboFOODON02010112.md)
    * [OboFOODON02020840](../classes/OboFOODON02020840.md)
    * [OboFOODON02020892](../classes/OboFOODON02020892.md)
    * [OboFOODON02021651](../classes/OboFOODON02021651.md)
    * [OboFOODON02021802](../classes/OboFOODON02021802.md)
    * [OboFOODON02021803](../classes/OboFOODON02021803.md)
    * [OboFOODON03301293](../classes/OboFOODON03301293.md)
    * [OboFOODON03302001](../classes/OboFOODON03302001.md)
    * [OboFOODON03303380](../classes/OboFOODON03303380.md)
    * [OboFOODON03304313](../classes/OboFOODON03304313.md)
    * [OboFOODON03304497](../classes/OboFOODON03304497.md)
    * [OboFOODON03304616](../classes/OboFOODON03304616.md)
    * [OboFOODON03306306](../classes/OboFOODON03306306.md)
    * [OboFOODON03309997](../classes/OboFOODON03309997.md)
    * [OboFOODON03310611](../classes/OboFOODON03310611.md)
    * [OboFOODON03310961](../classes/OboFOODON03310961.md)
    * [OboFOODON03315150](../classes/OboFOODON03315150.md)
    * [OboFOODON03315173](../classes/OboFOODON03315173.md)
    * [OboFOODON03315308](../classes/OboFOODON03315308.md)
    * [OboFOODON03315468](../classes/OboFOODON03315468.md)
    * [OboFOODON03315769](../classes/OboFOODON03315769.md)
    * [OboFOODON03315883](../classes/OboFOODON03315883.md)
    * [OboFOODON03316061](../classes/OboFOODON03316061.md)
    * [OboFOODON03317076](../classes/OboFOODON03317076.md)
    * [OboFOODON03317170](../classes/OboFOODON03317170.md)
    * [OboFOODON03411005](../classes/OboFOODON03411005.md)
    * [OboFOODON03411006](../classes/OboFOODON03411006.md)
    * [OboFOODON03411013](../classes/OboFOODON03411013.md)
    * [OboFOODON03411017](../classes/OboFOODON03411017.md)
    * [OboFOODON03411018](../classes/OboFOODON03411018.md)
    * [OboFOODON03411021](../classes/OboFOODON03411021.md)
    * [OboFOODON03411022](../classes/OboFOODON03411022.md)
    * [OboFOODON03411024](../classes/OboFOODON03411024.md)
    * [OboFOODON03411036](../classes/OboFOODON03411036.md)
    * [OboFOODON03411047](../classes/OboFOODON03411047.md)
    * [OboFOODON03411048](../classes/OboFOODON03411048.md)
    * [OboFOODON03411057](../classes/OboFOODON03411057.md)
    * [OboFOODON03411058](../classes/OboFOODON03411058.md)
    * [OboFOODON03411062](../classes/OboFOODON03411062.md)
    * [OboFOODON03411121](../classes/OboFOODON03411121.md)
    * [OboFOODON03411129](../classes/OboFOODON03411129.md)
    * [OboFOODON03411134](../classes/OboFOODON03411134.md)
    * [OboFOODON03411136](../classes/OboFOODON03411136.md)
    * [OboFOODON03411139](../classes/OboFOODON03411139.md)
    * [OboFOODON03411140](../classes/OboFOODON03411140.md)
    * [OboFOODON03411142](../classes/OboFOODON03411142.md)
    * [OboFOODON03411151](../classes/OboFOODON03411151.md)
    * [OboFOODON03411156](../classes/OboFOODON03411156.md)
    * [OboFOODON03411174](../classes/OboFOODON03411174.md)
    * [OboFOODON03411179](../classes/OboFOODON03411179.md)
    * [OboFOODON03411183](../classes/OboFOODON03411183.md)
    * [OboFOODON03411184](../classes/OboFOODON03411184.md)
    * [OboFOODON03411194](../classes/OboFOODON03411194.md)
    * [OboFOODON03411213](../classes/OboFOODON03411213.md)
    * [OboFOODON03411222](../classes/OboFOODON03411222.md)
    * [OboFOODON03411223](../classes/OboFOODON03411223.md)
    * [OboFOODON03411231](../classes/OboFOODON03411231.md)
    * [OboFOODON03411232](../classes/OboFOODON03411232.md)
    * [OboFOODON03411236](../classes/OboFOODON03411236.md)
    * [OboFOODON03411266](../classes/OboFOODON03411266.md)
    * [OboFOODON03411293](../classes/OboFOODON03411293.md)
    * [OboFOODON03411297](../classes/OboFOODON03411297.md)
    * [OboFOODON03411319](../classes/OboFOODON03411319.md)
    * [OboFOODON03411324](../classes/OboFOODON03411324.md)
    * [OboFOODON03411325](../classes/OboFOODON03411325.md)
    * [OboFOODON03411328](../classes/OboFOODON03411328.md)
    * [OboFOODON03411331](../classes/OboFOODON03411331.md)
    * [OboFOODON03411365](../classes/OboFOODON03411365.md)
    * [OboFOODON03411374](../classes/OboFOODON03411374.md)
    * [OboFOODON03411380](../classes/OboFOODON03411380.md)
    * [OboFOODON03411393](../classes/OboFOODON03411393.md)
    * [OboFOODON03411409](../classes/OboFOODON03411409.md)
    * [OboFOODON03411433](../classes/OboFOODON03411433.md)
    * [OboFOODON03411439](../classes/OboFOODON03411439.md)
    * [OboFOODON03411447](../classes/OboFOODON03411447.md)
    * [OboFOODON03411454](../classes/OboFOODON03411454.md)
    * [OboFOODON03411457](../classes/OboFOODON03411457.md)
    * [OboFOODON03411491](../classes/OboFOODON03411491.md)
    * [OboFOODON03411500](../classes/OboFOODON03411500.md)
    * [OboFOODON03411539](../classes/OboFOODON03411539.md)
    * [OboFOODON03411557](../classes/OboFOODON03411557.md)
    * [OboFOODON03411563](../classes/OboFOODON03411563.md)
    * [OboFOODON03411564](../classes/OboFOODON03411564.md)
    * [OboFOODON03411566](../classes/OboFOODON03411566.md)
    * [OboFOODON03411567](../classes/OboFOODON03411567.md)
    * [OboFOODON03411568](../classes/OboFOODON03411568.md)
    * [OboFOODON03411579](../classes/OboFOODON03411579.md)
    * [OboFOODON03411581](../classes/OboFOODON03411581.md)
    * [OboFOODON03411583](../classes/OboFOODON03411583.md)
    * [OboFOODON03411592](../classes/OboFOODON03411592.md)
    * [OboFOODON03411594](../classes/OboFOODON03411594.md)
    * [OboFOODON03411595](../classes/OboFOODON03411595.md)
    * [OboFOODON03411597](../classes/OboFOODON03411597.md)
    * [OboFOODON03411599](../classes/OboFOODON03411599.md)
    * [OboFOODON03411607](../classes/OboFOODON03411607.md)
    * [OboFOODON03411614](../classes/OboFOODON03411614.md)
    * [OboFOODON03411617](../classes/OboFOODON03411617.md)
    * [OboFOODON03411669](../classes/OboFOODON03411669.md)
    * [OboFOODON03411818](../classes/OboFOODON03411818.md)
    * [OboFOODON03411826](../classes/OboFOODON03411826.md)
    * [OboFOODON03411892](../classes/OboFOODON03411892.md)
    * [OboFOODON03412004](../classes/OboFOODON03412004.md)
    * [OboFOODON03412112](../classes/OboFOODON03412112.md)
    * [OboFOODON03412113](../classes/OboFOODON03412113.md)
    * [OboFOODON03412241](../classes/OboFOODON03412241.md)
    * [OboFOODON03412331](../classes/OboFOODON03412331.md)
    * [OboFOODON03412362](../classes/OboFOODON03412362.md)
    * [OboFOODON03412409](../classes/OboFOODON03412409.md)
    * [OboFOODON03412426](../classes/OboFOODON03412426.md)
    * [OboFOODON03412453](../classes/OboFOODON03412453.md)
    * [OboFOODON03412665](../classes/OboFOODON03412665.md)
    * [OboFOODON03413357](../classes/OboFOODON03413357.md)
    * [OboFOODON03413358](../classes/OboFOODON03413358.md)
    * [OboFOODON03413360](../classes/OboFOODON03413360.md)
    * [OboFOODON03413372](../classes/OboFOODON03413372.md)
    * [OboFOODON03413377](../classes/OboFOODON03413377.md)
    * [OboFOODON03413378](../classes/OboFOODON03413378.md)
    * [OboFOODON03413406](../classes/OboFOODON03413406.md)
    * [OboFOODON03413448](../classes/OboFOODON03413448.md)
    * [OboFOODON03413807](../classes/OboFOODON03413807.md)
    * [OboFOODON03413808](../classes/OboFOODON03413808.md)
    * [OboFOODON03414051](../classes/OboFOODON03414051.md)
    * [OboFOODON03414209](../classes/OboFOODON03414209.md)
    * [OboFOODON03414282](../classes/OboFOODON03414282.md)
    * [OboFOODON03414302](../classes/OboFOODON03414302.md)
    * [OboFOODON03414374](../classes/OboFOODON03414374.md)
    * [OboFOODON03414381](../classes/OboFOODON03414381.md)
    * [OboFOODON03414459](../classes/OboFOODON03414459.md)
    * [OboFOODON03414460](../classes/OboFOODON03414460.md)
    * [OboFOODON03414494](../classes/OboFOODON03414494.md)
    * [OboFOODON03414741](../classes/OboFOODON03414741.md)
    * [OboFOODON03414742](../classes/OboFOODON03414742.md)
    * [OboFOODON03414745](../classes/OboFOODON03414745.md)
    * [OboFOODON03414934](../classes/OboFOODON03414934.md)
    * [OboFOODON03414972](../classes/OboFOODON03414972.md)
    * [OboFOODON03420101](../classes/OboFOODON03420101.md)
    * [OboFOODON03420106](../classes/OboFOODON03420106.md)
    * [OboFOODON03420116](../classes/OboFOODON03420116.md)
    * [OboFOODON03420122](../classes/OboFOODON03420122.md)
    * [OboFOODON03420127](../classes/OboFOODON03420127.md)
    * [OboFOODON03420129](../classes/OboFOODON03420129.md)
    * [OboFOODON03420144](../classes/OboFOODON03420144.md)
    * [OboFOODON03420145](../classes/OboFOODON03420145.md)
    * [OboFOODON03420148](../classes/OboFOODON03420148.md)
    * [OboFOODON03420150](../classes/OboFOODON03420150.md)
    * [OboFOODON03420164](../classes/OboFOODON03420164.md)
    * [OboFOODON03420181](../classes/OboFOODON03420181.md)
    * [OboFOODON03420183](../classes/OboFOODON03420183.md)
    * [OboFOODON03420194](../classes/OboFOODON03420194.md)
    * [OboFOODON03420202](../classes/OboFOODON03420202.md)
    * [OboFOODON03420218](../classes/OboFOODON03420218.md)
    * [OboFOODON03420238](../classes/OboFOODON03420238.md)
    * [OboFOODON03420239](../classes/OboFOODON03420239.md)
    * [OboFOODON03460177](../classes/OboFOODON03460177.md)
    * [OboFOODON03602002](../classes/OboFOODON03602002.md)
    * [OboNCBITaxon1003242](../classes/OboNCBITaxon1003242.md)
    * [OboNCBITaxon1003875](../classes/OboNCBITaxon1003875.md)
    * [OboNCBITaxon1003877](../classes/OboNCBITaxon1003877.md)
    * [OboNCBITaxon10184](../classes/OboNCBITaxon10184.md)
    * [OboNCBITaxon102804](../classes/OboNCBITaxon102804.md)
    * [OboNCBITaxon102809](../classes/OboNCBITaxon102809.md)
    * [OboNCBITaxon102810](../classes/OboNCBITaxon102810.md)
    * [OboNCBITaxon102812](../classes/OboNCBITaxon102812.md)
    * [OboNCBITaxon102814](../classes/OboNCBITaxon102814.md)
    * [OboNCBITaxon102818](../classes/OboNCBITaxon102818.md)
    * [OboNCBITaxon109170](../classes/OboNCBITaxon109170.md)
    * [OboNCBITaxon1110380](../classes/OboNCBITaxon1110380.md)
    * [OboNCBITaxon1110386](../classes/OboNCBITaxon1110386.md)
    * [OboNCBITaxon112818](../classes/OboNCBITaxon112818.md)
    * [OboNCBITaxon115479](../classes/OboNCBITaxon115479.md)
    * [OboNCBITaxon117571](../classes/OboNCBITaxon117571.md)
    * [OboNCBITaxon1176516](../classes/OboNCBITaxon1176516.md)
    * [OboNCBITaxon1184124](../classes/OboNCBITaxon1184124.md)
    * [OboNCBITaxon119950](../classes/OboNCBITaxon119950.md)
    * [OboNCBITaxon120289](../classes/OboNCBITaxon120289.md)
    * [OboNCBITaxon1203511](../classes/OboNCBITaxon1203511.md)
    * [OboNCBITaxon123366](../classes/OboNCBITaxon123366.md)
    * [OboNCBITaxon123368](../classes/OboNCBITaxon123368.md)
    * [OboNCBITaxon123369](../classes/OboNCBITaxon123369.md)
    * [OboNCBITaxon125009](../classes/OboNCBITaxon125009.md)
    * [OboNCBITaxon126735](../classes/OboNCBITaxon126735.md)
    * [OboNCBITaxon128017](../classes/OboNCBITaxon128017.md)
    * [OboNCBITaxon1307774](../classes/OboNCBITaxon1307774.md)
    * [OboNCBITaxon1307775](../classes/OboNCBITaxon1307775.md)
    * [OboNCBITaxon1307796](../classes/OboNCBITaxon1307796.md)
    * [OboNCBITaxon1308840](../classes/OboNCBITaxon1308840.md)
    * [OboNCBITaxon1329799](../classes/OboNCBITaxon1329799.md)
    * [OboNCBITaxon13336](../classes/OboNCBITaxon13336.md)
    * [OboNCBITaxon1338369](../classes/OboNCBITaxon1338369.md)
    * [OboNCBITaxon13424](../classes/OboNCBITaxon13424.md)
    * [OboNCBITaxon13426](../classes/OboNCBITaxon13426.md)
    * [OboNCBITaxon13492](../classes/OboNCBITaxon13492.md)
    * [OboNCBITaxon13749](../classes/OboNCBITaxon13749.md)
    * [OboNCBITaxon1437010](../classes/OboNCBITaxon1437010.md)
    * [OboNCBITaxon1437180](../classes/OboNCBITaxon1437180.md)
    * [OboNCBITaxon1437183](../classes/OboNCBITaxon1437183.md)
    * [OboNCBITaxon1437197](../classes/OboNCBITaxon1437197.md)
    * [OboNCBITaxon1437201](../classes/OboNCBITaxon1437201.md)
    * [OboNCBITaxon144561](../classes/OboNCBITaxon144561.md)
    * [OboNCBITaxon1463138](../classes/OboNCBITaxon1463138.md)
    * [OboNCBITaxon147366](../classes/OboNCBITaxon147366.md)
    * [OboNCBITaxon147368](../classes/OboNCBITaxon147368.md)
    * [OboNCBITaxon147369](../classes/OboNCBITaxon147369.md)
    * [OboNCBITaxon147370](../classes/OboNCBITaxon147370.md)
    * [OboNCBITaxon147389](../classes/OboNCBITaxon147389.md)
    * [OboNCBITaxon147429](../classes/OboNCBITaxon147429.md)
    * [OboNCBITaxon147949](../classes/OboNCBITaxon147949.md)
    * [OboNCBITaxon1489341](../classes/OboNCBITaxon1489341.md)
    * [OboNCBITaxon1489388](../classes/OboNCBITaxon1489388.md)
    * [OboNCBITaxon1489793](../classes/OboNCBITaxon1489793.md)
    * [OboNCBITaxon1489872](../classes/OboNCBITaxon1489872.md)
    * [OboNCBITaxon1489922](../classes/OboNCBITaxon1489922.md)
    * [OboNCBITaxon1489923](../classes/OboNCBITaxon1489923.md)
    * [OboNCBITaxon1489940](../classes/OboNCBITaxon1489940.md)
    * [OboNCBITaxon15105](../classes/OboNCBITaxon15105.md)
    * [OboNCBITaxon151069](../classes/OboNCBITaxon151069.md)
    * [OboNCBITaxon151071](../classes/OboNCBITaxon151071.md)
    * [OboNCBITaxon1521262](../classes/OboNCBITaxon1521262.md)
    * [OboNCBITaxon1538097](../classes/OboNCBITaxon1538097.md)
    * [OboNCBITaxon1545897](../classes/OboNCBITaxon1545897.md)
    * [OboNCBITaxon1549675](../classes/OboNCBITaxon1549675.md)
    * [OboNCBITaxon156152](../classes/OboNCBITaxon156152.md)
    * [OboNCBITaxon1589896](../classes/OboNCBITaxon1589896.md)
    * [OboNCBITaxon159053](../classes/OboNCBITaxon159053.md)
    * [OboNCBITaxon1609961](../classes/OboNCBITaxon1609961.md)
    * [OboNCBITaxon1609962](../classes/OboNCBITaxon1609962.md)
    * [OboNCBITaxon162743](../classes/OboNCBITaxon162743.md)
    * [OboNCBITaxon163487](../classes/OboNCBITaxon163487.md)
    * [OboNCBITaxon16360](../classes/OboNCBITaxon16360.md)
    * [OboNCBITaxon163735](../classes/OboNCBITaxon163735.md)
    * [OboNCBITaxon163743](../classes/OboNCBITaxon163743.md)
    * [OboNCBITaxon1648004](../classes/OboNCBITaxon1648004.md)
    * [OboNCBITaxon1648017](../classes/OboNCBITaxon1648017.md)
    * [OboNCBITaxon1648033](../classes/OboNCBITaxon1648033.md)
    * [OboNCBITaxon165297](../classes/OboNCBITaxon165297.md)
    * [OboNCBITaxon169617](../classes/OboNCBITaxon169617.md)
    * [OboNCBITaxon169618](../classes/OboNCBITaxon169618.md)
    * [OboNCBITaxon169642](../classes/OboNCBITaxon169642.md)
    * [OboNCBITaxon169655](../classes/OboNCBITaxon169655.md)
    * [OboNCBITaxon169697](../classes/OboNCBITaxon169697.md)
    * [OboNCBITaxon169700](../classes/OboNCBITaxon169700.md)
    * [OboNCBITaxon169703](../classes/OboNCBITaxon169703.md)
    * [OboNCBITaxon169705](../classes/OboNCBITaxon169705.md)
    * [OboNCBITaxon169725](../classes/OboNCBITaxon169725.md)
    * [OboNCBITaxon169733](../classes/OboNCBITaxon169733.md)
    * [OboNCBITaxon169746](../classes/OboNCBITaxon169746.md)
    * [OboNCBITaxon1699513](../classes/OboNCBITaxon1699513.md)
    * [OboNCBITaxon1699523](../classes/OboNCBITaxon1699523.md)
    * [OboNCBITaxon17047](../classes/OboNCBITaxon17047.md)
    * [OboNCBITaxon1705104](../classes/OboNCBITaxon1705104.md)
    * [OboNCBITaxon171637](../classes/OboNCBITaxon171637.md)
    * [OboNCBITaxon171638](../classes/OboNCBITaxon171638.md)
    * [OboNCBITaxon1728959](../classes/OboNCBITaxon1728959.md)
    * [OboNCBITaxon173691](../classes/OboNCBITaxon173691.md)
    * [OboNCBITaxon174217](../classes/OboNCBITaxon174217.md)
    * [OboNCBITaxon178174](../classes/OboNCBITaxon178174.md)
    * [OboNCBITaxon180118](../classes/OboNCBITaxon180118.md)
    * [OboNCBITaxon1804623](../classes/OboNCBITaxon1804623.md)
    * [OboNCBITaxon181185](../classes/OboNCBITaxon181185.md)
    * [OboNCBITaxon183218](../classes/OboNCBITaxon183218.md)
    * [OboNCBITaxon184451](../classes/OboNCBITaxon184451.md)
    * [OboNCBITaxon186265](../classes/OboNCBITaxon186265.md)
    * [OboNCBITaxon186623](../classes/OboNCBITaxon186623.md)
    * [OboNCBITaxon186625](../classes/OboNCBITaxon186625.md)
    * [OboNCBITaxon186626](../classes/OboNCBITaxon186626.md)
    * [OboNCBITaxon186628](../classes/OboNCBITaxon186628.md)
    * [OboNCBITaxon186634](../classes/OboNCBITaxon186634.md)
    * [OboNCBITaxon1874399](../classes/OboNCBITaxon1874399.md)
    * [OboNCBITaxon19205](../classes/OboNCBITaxon19205.md)
    * [OboNCBITaxon1927087](../classes/OboNCBITaxon1927087.md)
    * [OboNCBITaxon193297](../classes/OboNCBITaxon193297.md)
    * [OboNCBITaxon194251](../classes/OboNCBITaxon194251.md)
    * [OboNCBITaxon1968271](../classes/OboNCBITaxon1968271.md)
    * [OboNCBITaxon1968429](../classes/OboNCBITaxon1968429.md)
    * [OboNCBITaxon1977918](../classes/OboNCBITaxon1977918.md)
    * [OboNCBITaxon198777](../classes/OboNCBITaxon198777.md)
    * [OboNCBITaxon19955](../classes/OboNCBITaxon19955.md)
    * [OboNCBITaxon201017](../classes/OboNCBITaxon201017.md)
    * [OboNCBITaxon214693](../classes/OboNCBITaxon214693.md)
    * [OboNCBITaxon214697](../classes/OboNCBITaxon214697.md)
    * [OboNCBITaxon21472](../classes/OboNCBITaxon21472.md)
    * [OboNCBITaxon214907](../classes/OboNCBITaxon214907.md)
    * [OboNCBITaxon214908](../classes/OboNCBITaxon214908.md)
    * [OboNCBITaxon214929](../classes/OboNCBITaxon214929.md)
    * [OboNCBITaxon215450](../classes/OboNCBITaxon215450.md)
    * [OboNCBITaxon21563](../classes/OboNCBITaxon21563.md)
    * [OboNCBITaxon21571](../classes/OboNCBITaxon21571.md)
    * [OboNCBITaxon216703](../classes/OboNCBITaxon216703.md)
    * [OboNCBITaxon217033](../classes/OboNCBITaxon217033.md)
    * [OboNCBITaxon217035](../classes/OboNCBITaxon217035.md)
    * [OboNCBITaxon217037](../classes/OboNCBITaxon217037.md)
    * [OboNCBITaxon217062](../classes/OboNCBITaxon217062.md)
    * [OboNCBITaxon219121](../classes/OboNCBITaxon219121.md)
    * [OboNCBITaxon219134](../classes/OboNCBITaxon219134.md)
    * [OboNCBITaxon221251](../classes/OboNCBITaxon221251.md)
    * [OboNCBITaxon22140](../classes/OboNCBITaxon22140.md)
    * [OboNCBITaxon2231382](../classes/OboNCBITaxon2231382.md)
    * [OboNCBITaxon2231383](../classes/OboNCBITaxon2231383.md)
    * [OboNCBITaxon2231390](../classes/OboNCBITaxon2231390.md)
    * [OboNCBITaxon2231393](../classes/OboNCBITaxon2231393.md)
    * [OboNCBITaxon2233838](../classes/OboNCBITaxon2233838.md)
    * [OboNCBITaxon2233839](../classes/OboNCBITaxon2233839.md)
    * [OboNCBITaxon2233855](../classes/OboNCBITaxon2233855.md)
    * [OboNCBITaxon2233857](../classes/OboNCBITaxon2233857.md)
    * [OboNCBITaxon22663](../classes/OboNCBITaxon22663.md)
    * [OboNCBITaxon22665](../classes/OboNCBITaxon22665.md)
    * [OboNCBITaxon22774](../classes/OboNCBITaxon22774.md)
    * [OboNCBITaxon22973](../classes/OboNCBITaxon22973.md)
    * [OboNCBITaxon22978](../classes/OboNCBITaxon22978.md)
    * [OboNCBITaxon2304100](../classes/OboNCBITaxon2304100.md)
    * [OboNCBITaxon23066](../classes/OboNCBITaxon23066.md)
    * [OboNCBITaxon23139](../classes/OboNCBITaxon23139.md)
    * [OboNCBITaxon23216](../classes/OboNCBITaxon23216.md)
    * [OboNCBITaxon23222](../classes/OboNCBITaxon23222.md)
    * [OboNCBITaxon232347](../classes/OboNCBITaxon232347.md)
    * [OboNCBITaxon233713](../classes/OboNCBITaxon233713.md)
    * [OboNCBITaxon233715](../classes/OboNCBITaxon233715.md)
    * [OboNCBITaxon233880](../classes/OboNCBITaxon233880.md)
    * [OboNCBITaxon23461](../classes/OboNCBITaxon23461.md)
    * [OboNCBITaxon23513](../classes/OboNCBITaxon23513.md)
    * [OboNCBITaxon235595](../classes/OboNCBITaxon235595.md)
    * [OboNCBITaxon23672](../classes/OboNCBITaxon23672.md)
    * [OboNCBITaxon23808](../classes/OboNCBITaxon23808.md)
    * [OboNCBITaxon241778](../classes/OboNCBITaxon241778.md)
    * [OboNCBITaxon241780](../classes/OboNCBITaxon241780.md)
    * [OboNCBITaxon241789](../classes/OboNCBITaxon241789.md)
    * [OboNCBITaxon241793](../classes/OboNCBITaxon241793.md)
    * [OboNCBITaxon241799](../classes/OboNCBITaxon241799.md)
    * [OboNCBITaxon241800](../classes/OboNCBITaxon241800.md)
    * [OboNCBITaxon241806](../classes/OboNCBITaxon241806.md)
    * [OboNCBITaxon245205](../classes/OboNCBITaxon245205.md)
    * [OboNCBITaxon24646](../classes/OboNCBITaxon24646.md)
    * [OboNCBITaxon24663](../classes/OboNCBITaxon24663.md)
    * [OboNCBITaxon24966](../classes/OboNCBITaxon24966.md)
    * [OboNCBITaxon259381](../classes/OboNCBITaxon259381.md)
    * [OboNCBITaxon25996](../classes/OboNCBITaxon25996.md)
    * [OboNCBITaxon260143](../classes/OboNCBITaxon260143.md)
    * [OboNCBITaxon260718](../classes/OboNCBITaxon260718.md)
    * [OboNCBITaxon26468](../classes/OboNCBITaxon26468.md)
    * [OboNCBITaxon26496](../classes/OboNCBITaxon26496.md)
    * [OboNCBITaxon26867](../classes/OboNCBITaxon26867.md)
    * [OboNCBITaxon2706](../classes/OboNCBITaxon2706.md)
    * [OboNCBITaxon2732585](../classes/OboNCBITaxon2732585.md)
    * [OboNCBITaxon2759](../classes/OboNCBITaxon2759.md)
    * [OboNCBITaxon27592](../classes/OboNCBITaxon27592.md)
    * [OboNCBITaxon27705](../classes/OboNCBITaxon27705.md)
    * [OboNCBITaxon27706](../classes/OboNCBITaxon27706.md)
    * [OboNCBITaxon27778](../classes/OboNCBITaxon27778.md)
    * [OboNCBITaxon278205](../classes/OboNCBITaxon278205.md)
    * [OboNCBITaxon2785011](../classes/OboNCBITaxon2785011.md)
    * [OboNCBITaxon2785015](../classes/OboNCBITaxon2785015.md)
    * [OboNCBITaxon284555](../classes/OboNCBITaxon284555.md)
    * [OboNCBITaxon28974](../classes/OboNCBITaxon28974.md)
    * [OboNCBITaxon2908833](../classes/OboNCBITaxon2908833.md)
    * [OboNCBITaxon290983](../classes/OboNCBITaxon290983.md)
    * [OboNCBITaxon29132](../classes/OboNCBITaxon29132.md)
    * [OboNCBITaxon296036](../classes/OboNCBITaxon296036.md)
    * [OboNCBITaxon2976026](../classes/OboNCBITaxon2976026.md)
    * [OboNCBITaxon29780](../classes/OboNCBITaxon29780.md)
    * [OboNCBITaxon301453](../classes/OboNCBITaxon301453.md)
    * [OboNCBITaxon301959](../classes/OboNCBITaxon301959.md)
    * [OboNCBITaxon303185](../classes/OboNCBITaxon303185.md)
    * [OboNCBITaxon314145](../classes/OboNCBITaxon314145.md)
    * [OboNCBITaxon314146](../classes/OboNCBITaxon314146.md)
    * [OboNCBITaxon314147](../classes/OboNCBITaxon314147.md)
    * [OboNCBITaxon32443](../classes/OboNCBITaxon32443.md)
    * [OboNCBITaxon32519](../classes/OboNCBITaxon32519.md)
    * [OboNCBITaxon32523](../classes/OboNCBITaxon32523.md)
    * [OboNCBITaxon32524](../classes/OboNCBITaxon32524.md)
    * [OboNCBITaxon32525](../classes/OboNCBITaxon32525.md)
    * [OboNCBITaxon32561](../classes/OboNCBITaxon32561.md)
    * [OboNCBITaxon3268](../classes/OboNCBITaxon3268.md)
    * [OboNCBITaxon3275](../classes/OboNCBITaxon3275.md)
    * [OboNCBITaxon3282](../classes/OboNCBITaxon3282.md)
    * [OboNCBITaxon3296](../classes/OboNCBITaxon3296.md)
    * [OboNCBITaxon3297](../classes/OboNCBITaxon3297.md)
    * [OboNCBITaxon33090](../classes/OboNCBITaxon33090.md)
    * [OboNCBITaxon33154](../classes/OboNCBITaxon33154.md)
    * [OboNCBITaxon33208](../classes/OboNCBITaxon33208.md)
    * [OboNCBITaxon33213](../classes/OboNCBITaxon33213.md)
    * [OboNCBITaxon33317](../classes/OboNCBITaxon33317.md)
    * [OboNCBITaxon33511](../classes/OboNCBITaxon33511.md)
    * [OboNCBITaxon3394](../classes/OboNCBITaxon3394.md)
    * [OboNCBITaxon3395](../classes/OboNCBITaxon3395.md)
    * [OboNCBITaxon3398](../classes/OboNCBITaxon3398.md)
    * [OboNCBITaxon3400](../classes/OboNCBITaxon3400.md)
    * [OboNCBITaxon3440](../classes/OboNCBITaxon3440.md)
    * [OboNCBITaxon34542](../classes/OboNCBITaxon34542.md)
    * [OboNCBITaxon3465](../classes/OboNCBITaxon3465.md)
    * [OboNCBITaxon3468](../classes/OboNCBITaxon3468.md)
    * [OboNCBITaxon34815](../classes/OboNCBITaxon34815.md)
    * [OboNCBITaxon3487](../classes/OboNCBITaxon3487.md)
    * [OboNCBITaxon3488](../classes/OboNCBITaxon3488.md)
    * [OboNCBITaxon3489](../classes/OboNCBITaxon3489.md)
    * [OboNCBITaxon3493](../classes/OboNCBITaxon3493.md)
    * [OboNCBITaxon3497](../classes/OboNCBITaxon3497.md)
    * [OboNCBITaxon3499](../classes/OboNCBITaxon3499.md)
    * [OboNCBITaxon3524](../classes/OboNCBITaxon3524.md)
    * [OboNCBITaxon3542](../classes/OboNCBITaxon3542.md)
    * [OboNCBITaxon35500](../classes/OboNCBITaxon35500.md)
    * [OboNCBITaxon3558](../classes/OboNCBITaxon3558.md)
    * [OboNCBITaxon3563](../classes/OboNCBITaxon3563.md)
    * [OboNCBITaxon3564](../classes/OboNCBITaxon3564.md)
    * [OboNCBITaxon3568](../classes/OboNCBITaxon3568.md)
    * [OboNCBITaxon3587](../classes/OboNCBITaxon3587.md)
    * [OboNCBITaxon359160](../classes/OboNCBITaxon359160.md)
    * [OboNCBITaxon3593](../classes/OboNCBITaxon3593.md)
    * [OboNCBITaxon3602](../classes/OboNCBITaxon3602.md)
    * [OboNCBITaxon3603](../classes/OboNCBITaxon3603.md)
    * [OboNCBITaxon3608](../classes/OboNCBITaxon3608.md)
    * [OboNCBITaxon3615](../classes/OboNCBITaxon3615.md)
    * [OboNCBITaxon3618](../classes/OboNCBITaxon3618.md)
    * [OboNCBITaxon3620](../classes/OboNCBITaxon3620.md)
    * [OboNCBITaxon3623](../classes/OboNCBITaxon3623.md)
    * [OboNCBITaxon3624](../classes/OboNCBITaxon3624.md)
    * [OboNCBITaxon3629](../classes/OboNCBITaxon3629.md)
    * [OboNCBITaxon3640](../classes/OboNCBITaxon3640.md)
    * [OboNCBITaxon364270](../classes/OboNCBITaxon364270.md)
    * [OboNCBITaxon3646](../classes/OboNCBITaxon3646.md)
    * [OboNCBITaxon3647](../classes/OboNCBITaxon3647.md)
    * [OboNCBITaxon3649](../classes/OboNCBITaxon3649.md)
    * [OboNCBITaxon3650](../classes/OboNCBITaxon3650.md)
    * [OboNCBITaxon3653](../classes/OboNCBITaxon3653.md)
    * [OboNCBITaxon3655](../classes/OboNCBITaxon3655.md)
    * [OboNCBITaxon3660](../classes/OboNCBITaxon3660.md)
    * [OboNCBITaxon36603](../classes/OboNCBITaxon36603.md)
    * [OboNCBITaxon36609](../classes/OboNCBITaxon36609.md)
    * [OboNCBITaxon3669](../classes/OboNCBITaxon3669.md)
    * [OboNCBITaxon3671](../classes/OboNCBITaxon3671.md)
    * [OboNCBITaxon3676](../classes/OboNCBITaxon3676.md)
    * [OboNCBITaxon3683](../classes/OboNCBITaxon3683.md)
    * [OboNCBITaxon3684](../classes/OboNCBITaxon3684.md)
    * [OboNCBITaxon3688](../classes/OboNCBITaxon3688.md)
    * [OboNCBITaxon3699](../classes/OboNCBITaxon3699.md)
    * [OboNCBITaxon3700](../classes/OboNCBITaxon3700.md)
    * [OboNCBITaxon3705](../classes/OboNCBITaxon3705.md)
    * [OboNCBITaxon3707](../classes/OboNCBITaxon3707.md)
    * [OboNCBITaxon3737](../classes/OboNCBITaxon3737.md)
    * [OboNCBITaxon3740](../classes/OboNCBITaxon3740.md)
    * [OboNCBITaxon3744](../classes/OboNCBITaxon3744.md)
    * [OboNCBITaxon3745](../classes/OboNCBITaxon3745.md)
    * [OboNCBITaxon3746](../classes/OboNCBITaxon3746.md)
    * [OboNCBITaxon3749](../classes/OboNCBITaxon3749.md)
    * [OboNCBITaxon3754](../classes/OboNCBITaxon3754.md)
    * [OboNCBITaxon3766](../classes/OboNCBITaxon3766.md)
    * [OboNCBITaxon3801](../classes/OboNCBITaxon3801.md)
    * [OboNCBITaxon3803](../classes/OboNCBITaxon3803.md)
    * [OboNCBITaxon3804](../classes/OboNCBITaxon3804.md)
    * [OboNCBITaxon3807](../classes/OboNCBITaxon3807.md)
    * [OboNCBITaxon381124](../classes/OboNCBITaxon381124.md)
    * [OboNCBITaxon3814](../classes/OboNCBITaxon3814.md)
    * [OboNCBITaxon3822](../classes/OboNCBITaxon3822.md)
    * [OboNCBITaxon3853](../classes/OboNCBITaxon3853.md)
    * [OboNCBITaxon38820](../classes/OboNCBITaxon38820.md)
    * [OboNCBITaxon3883](../classes/OboNCBITaxon3883.md)
    * [OboNCBITaxon3884](../classes/OboNCBITaxon3884.md)
    * [OboNCBITaxon3885](../classes/OboNCBITaxon3885.md)
    * [OboNCBITaxon3904](../classes/OboNCBITaxon3904.md)
    * [OboNCBITaxon3906](../classes/OboNCBITaxon3906.md)
    * [OboNCBITaxon3913](../classes/OboNCBITaxon3913.md)
    * [OboNCBITaxon3917](../classes/OboNCBITaxon3917.md)
    * [OboNCBITaxon3928](../classes/OboNCBITaxon3928.md)
    * [OboNCBITaxon3931](../classes/OboNCBITaxon3931.md)
    * [OboNCBITaxon4011](../classes/OboNCBITaxon4011.md)
    * [OboNCBITaxon4014](../classes/OboNCBITaxon4014.md)
    * [OboNCBITaxon4018](../classes/OboNCBITaxon4018.md)
    * [OboNCBITaxon4019](../classes/OboNCBITaxon4019.md)
    * [OboNCBITaxon4020](../classes/OboNCBITaxon4020.md)
    * [OboNCBITaxon4033](../classes/OboNCBITaxon4033.md)
    * [OboNCBITaxon4037](../classes/OboNCBITaxon4037.md)
    * [OboNCBITaxon4038](../classes/OboNCBITaxon4038.md)
    * [OboNCBITaxon4039](../classes/OboNCBITaxon4039.md)
    * [OboNCBITaxon40548](../classes/OboNCBITaxon40548.md)
    * [OboNCBITaxon4055](../classes/OboNCBITaxon4055.md)
    * [OboNCBITaxon4056](../classes/OboNCBITaxon4056.md)
    * [OboNCBITaxon40674](../classes/OboNCBITaxon40674.md)
    * [OboNCBITaxon40685](../classes/OboNCBITaxon40685.md)
    * [OboNCBITaxon4069](../classes/OboNCBITaxon4069.md)
    * [OboNCBITaxon4070](../classes/OboNCBITaxon4070.md)
    * [OboNCBITaxon4071](../classes/OboNCBITaxon4071.md)
    * [OboNCBITaxon4072](../classes/OboNCBITaxon4072.md)
    * [OboNCBITaxon4107](../classes/OboNCBITaxon4107.md)
    * [OboNCBITaxon4113](../classes/OboNCBITaxon4113.md)
    * [OboNCBITaxon4118](../classes/OboNCBITaxon4118.md)
    * [OboNCBITaxon4119](../classes/OboNCBITaxon4119.md)
    * [OboNCBITaxon4136](../classes/OboNCBITaxon4136.md)
    * [OboNCBITaxon4143](../classes/OboNCBITaxon4143.md)
    * [OboNCBITaxon4144](../classes/OboNCBITaxon4144.md)
    * [OboNCBITaxon41665](../classes/OboNCBITaxon41665.md)
    * [OboNCBITaxon41705](../classes/OboNCBITaxon41705.md)
    * [OboNCBITaxon41768](../classes/OboNCBITaxon41768.md)
    * [OboNCBITaxon41773](../classes/OboNCBITaxon41773.md)
    * [OboNCBITaxon41937](../classes/OboNCBITaxon41937.md)
    * [OboNCBITaxon41938](../classes/OboNCBITaxon41938.md)
    * [OboNCBITaxon41944](../classes/OboNCBITaxon41944.md)
    * [OboNCBITaxon41945](../classes/OboNCBITaxon41945.md)
    * [OboNCBITaxon41946](../classes/OboNCBITaxon41946.md)
    * [OboNCBITaxon41947](../classes/OboNCBITaxon41947.md)
    * [OboNCBITaxon4199](../classes/OboNCBITaxon4199.md)
    * [OboNCBITaxon4200](../classes/OboNCBITaxon4200.md)
    * [OboNCBITaxon4201](../classes/OboNCBITaxon4201.md)
    * [OboNCBITaxon4204](../classes/OboNCBITaxon4204.md)
    * [OboNCBITaxon4206](../classes/OboNCBITaxon4206.md)
    * [OboNCBITaxon4210](../classes/OboNCBITaxon4210.md)
    * [OboNCBITaxon42148](../classes/OboNCBITaxon42148.md)
    * [OboNCBITaxon4216](../classes/OboNCBITaxon4216.md)
    * [OboNCBITaxon42219](../classes/OboNCBITaxon42219.md)
    * [OboNCBITaxon4231](../classes/OboNCBITaxon4231.md)
    * [OboNCBITaxon4235](../classes/OboNCBITaxon4235.md)
    * [OboNCBITaxon424551](../classes/OboNCBITaxon424551.md)
    * [OboNCBITaxon424573](../classes/OboNCBITaxon424573.md)
    * [OboNCBITaxon426106](../classes/OboNCBITaxon426106.md)
    * [OboNCBITaxon4268](../classes/OboNCBITaxon4268.md)
    * [OboNCBITaxon4281](../classes/OboNCBITaxon4281.md)
    * [OboNCBITaxon4294](../classes/OboNCBITaxon4294.md)
    * [OboNCBITaxon432663](../classes/OboNCBITaxon432663.md)
    * [OboNCBITaxon4335](../classes/OboNCBITaxon4335.md)
    * [OboNCBITaxon4345](../classes/OboNCBITaxon4345.md)
    * [OboNCBITaxon43690](../classes/OboNCBITaxon43690.md)
    * [OboNCBITaxon43707](../classes/OboNCBITaxon43707.md)
    * [OboNCBITaxon43860](../classes/OboNCBITaxon43860.md)
    * [OboNCBITaxon4410](../classes/OboNCBITaxon4410.md)
    * [OboNCBITaxon4447](../classes/OboNCBITaxon4447.md)
    * [OboNCBITaxon4454](../classes/OboNCBITaxon4454.md)
    * [OboNCBITaxon4479](../classes/OboNCBITaxon4479.md)
    * [OboNCBITaxon4577](../classes/OboNCBITaxon4577.md)
    * [OboNCBITaxon4581](../classes/OboNCBITaxon4581.md)
    * [OboNCBITaxon45918](../classes/OboNCBITaxon45918.md)
    * [OboNCBITaxon4609](../classes/OboNCBITaxon4609.md)
    * [OboNCBITaxon4610](../classes/OboNCBITaxon4610.md)
    * [OboNCBITaxon4613](../classes/OboNCBITaxon4613.md)
    * [OboNCBITaxon46145](../classes/OboNCBITaxon46145.md)
    * [OboNCBITaxon4615](../classes/OboNCBITaxon4615.md)
    * [OboNCBITaxon4618](../classes/OboNCBITaxon4618.md)
    * [OboNCBITaxon46260](../classes/OboNCBITaxon46260.md)
    * [OboNCBITaxon4637](../classes/OboNCBITaxon4637.md)
    * [OboNCBITaxon4638](../classes/OboNCBITaxon4638.md)
    * [OboNCBITaxon4639](../classes/OboNCBITaxon4639.md)
    * [OboNCBITaxon4640](../classes/OboNCBITaxon4640.md)
    * [OboNCBITaxon4641](../classes/OboNCBITaxon4641.md)
    * [OboNCBITaxon4642](../classes/OboNCBITaxon4642.md)
    * [OboNCBITaxon4668](../classes/OboNCBITaxon4668.md)
    * [OboNCBITaxon4671](../classes/OboNCBITaxon4671.md)
    * [OboNCBITaxon4678](../classes/OboNCBITaxon4678.md)
    * [OboNCBITaxon4710](../classes/OboNCBITaxon4710.md)
    * [OboNCBITaxon4719](../classes/OboNCBITaxon4719.md)
    * [OboNCBITaxon4731](../classes/OboNCBITaxon4731.md)
    * [OboNCBITaxon4732](../classes/OboNCBITaxon4732.md)
    * [OboNCBITaxon4734](../classes/OboNCBITaxon4734.md)
    * [OboNCBITaxon47605](../classes/OboNCBITaxon47605.md)
    * [OboNCBITaxon479623](../classes/OboNCBITaxon479623.md)
    * [OboNCBITaxon50173](../classes/OboNCBITaxon50173.md)
    * [OboNCBITaxon50174](../classes/OboNCBITaxon50174.md)
    * [OboNCBITaxon50190](../classes/OboNCBITaxon50190.md)
    * [OboNCBITaxon50384](../classes/OboNCBITaxon50384.md)
    * [OboNCBITaxon504568](../classes/OboNCBITaxon504568.md)
    * [OboNCBITaxon50457](../classes/OboNCBITaxon50457.md)
    * [OboNCBITaxon516948](../classes/OboNCBITaxon516948.md)
    * [OboNCBITaxon51952](../classes/OboNCBITaxon51952.md)
    * [OboNCBITaxon52838](../classes/OboNCBITaxon52838.md)
    * [OboNCBITaxon53868](../classes/OboNCBITaxon53868.md)
    * [OboNCBITaxon54476](../classes/OboNCBITaxon54476.md)
    * [OboNCBITaxon557010](../classes/OboNCBITaxon557010.md)
    * [OboNCBITaxon55961](../classes/OboNCBITaxon55961.md)
    * [OboNCBITaxon57918](../classes/OboNCBITaxon57918.md)
    * [OboNCBITaxon58023](../classes/OboNCBITaxon58023.md)
    * [OboNCBITaxon58024](../classes/OboNCBITaxon58024.md)
    * [OboNCBITaxon58228](../classes/OboNCBITaxon58228.md)
    * [OboNCBITaxon58486](../classes/OboNCBITaxon58486.md)
    * [OboNCBITaxon58860](../classes/OboNCBITaxon58860.md)
    * [OboNCBITaxon59165](../classes/OboNCBITaxon59165.md)
    * [OboNCBITaxon6072](../classes/OboNCBITaxon6072.md)
    * [OboNCBITaxon641307](../classes/OboNCBITaxon641307.md)
    * [OboNCBITaxon6447](../classes/OboNCBITaxon6447.md)
    * [OboNCBITaxon6544](../classes/OboNCBITaxon6544.md)
    * [OboNCBITaxon6545](../classes/OboNCBITaxon6545.md)
    * [OboNCBITaxon6547](../classes/OboNCBITaxon6547.md)
    * [OboNCBITaxon6548](../classes/OboNCBITaxon6548.md)
    * [OboNCBITaxon6550](../classes/OboNCBITaxon6550.md)
    * [OboNCBITaxon6599](../classes/OboNCBITaxon6599.md)
    * [OboNCBITaxon6602](../classes/OboNCBITaxon6602.md)
    * [OboNCBITaxon6604](../classes/OboNCBITaxon6604.md)
    * [OboNCBITaxon6605](../classes/OboNCBITaxon6605.md)
    * [OboNCBITaxon6606](../classes/OboNCBITaxon6606.md)
    * [OboNCBITaxon66670](../classes/OboNCBITaxon66670.md)
    * [OboNCBITaxon66672](../classes/OboNCBITaxon66672.md)
    * [OboNCBITaxon69108](../classes/OboNCBITaxon69108.md)
    * [OboNCBITaxon69109](../classes/OboNCBITaxon69109.md)
    * [OboNCBITaxon693794](../classes/OboNCBITaxon693794.md)
    * [OboNCBITaxon703407](../classes/OboNCBITaxon703407.md)
    * [OboNCBITaxon71243](../classes/OboNCBITaxon71243.md)
    * [OboNCBITaxon71274](../classes/OboNCBITaxon71274.md)
    * [OboNCBITaxon71275](../classes/OboNCBITaxon71275.md)
    * [OboNCBITaxon71611](../classes/OboNCBITaxon71611.md)
    * [OboNCBITaxon72025](../classes/OboNCBITaxon72025.md)
    * [OboNCBITaxon72171](../classes/OboNCBITaxon72171.md)
    * [OboNCBITaxon721789](../classes/OboNCBITaxon721789.md)
    * [OboNCBITaxon721813](../classes/OboNCBITaxon721813.md)
    * [OboNCBITaxon73496](../classes/OboNCBITaxon73496.md)
    * [OboNCBITaxon742010](../classes/OboNCBITaxon742010.md)
    * [OboNCBITaxon745060](../classes/OboNCBITaxon745060.md)
    * [OboNCBITaxon7711](../classes/OboNCBITaxon7711.md)
    * [OboNCBITaxon7742](../classes/OboNCBITaxon7742.md)
    * [OboNCBITaxon7776](../classes/OboNCBITaxon7776.md)
    * [OboNCBITaxon78536](../classes/OboNCBITaxon78536.md)
    * [OboNCBITaxon7898](../classes/OboNCBITaxon7898.md)
    * [OboNCBITaxon79331](../classes/OboNCBITaxon79331.md)
    * [OboNCBITaxon7952](../classes/OboNCBITaxon7952.md)
    * [OboNCBITaxon7968](../classes/OboNCBITaxon7968.md)
    * [OboNCBITaxon7969](../classes/OboNCBITaxon7969.md)
    * [OboNCBITaxon7971](../classes/OboNCBITaxon7971.md)
    * [OboNCBITaxon7995](../classes/OboNCBITaxon7995.md)
    * [OboNCBITaxon7996](../classes/OboNCBITaxon7996.md)
    * [OboNCBITaxon8006](../classes/OboNCBITaxon8006.md)
    * [OboNCBITaxon8007](../classes/OboNCBITaxon8007.md)
    * [OboNCBITaxon8008](../classes/OboNCBITaxon8008.md)
    * [OboNCBITaxon8009](../classes/OboNCBITaxon8009.md)
    * [OboNCBITaxon8010](../classes/OboNCBITaxon8010.md)
    * [OboNCBITaxon8015](../classes/OboNCBITaxon8015.md)
    * [OboNCBITaxon8033](../classes/OboNCBITaxon8033.md)
    * [OboNCBITaxon8038](../classes/OboNCBITaxon8038.md)
    * [OboNCBITaxon8111](../classes/OboNCBITaxon8111.md)
    * [OboNCBITaxon8112](../classes/OboNCBITaxon8112.md)
    * [OboNCBITaxon8165](../classes/OboNCBITaxon8165.md)
    * [OboNCBITaxon8166](../classes/OboNCBITaxon8166.md)
    * [OboNCBITaxon8167](../classes/OboNCBITaxon8167.md)
    * [OboNCBITaxon8180](../classes/OboNCBITaxon8180.md)
    * [OboNCBITaxon8181](../classes/OboNCBITaxon8181.md)
    * [OboNCBITaxon8182](../classes/OboNCBITaxon8182.md)
    * [OboNCBITaxon83431](../classes/OboNCBITaxon83431.md)
    * [OboNCBITaxon84005](../classes/OboNCBITaxon84005.md)
    * [OboNCBITaxon84860](../classes/OboNCBITaxon84860.md)
    * [OboNCBITaxon8492](../classes/OboNCBITaxon8492.md)
    * [OboNCBITaxon85249](../classes/OboNCBITaxon85249.md)
    * [OboNCBITaxon85571](../classes/OboNCBITaxon85571.md)
    * [OboNCBITaxon866800](../classes/OboNCBITaxon866800.md)
    * [OboNCBITaxon8782](../classes/OboNCBITaxon8782.md)
    * [OboNCBITaxon8825](../classes/OboNCBITaxon8825.md)
    * [OboNCBITaxon89151](../classes/OboNCBITaxon89151.md)
    * [OboNCBITaxon8976](../classes/OboNCBITaxon8976.md)
    * [OboNCBITaxon9005](../classes/OboNCBITaxon9005.md)
    * [OboNCBITaxon9031](../classes/OboNCBITaxon9031.md)
    * [OboNCBITaxon9072](../classes/OboNCBITaxon9072.md)
    * [OboNCBITaxon9102](../classes/OboNCBITaxon9102.md)
    * [OboNCBITaxon9103](../classes/OboNCBITaxon9103.md)
    * [OboNCBITaxon911341](../classes/OboNCBITaxon911341.md)
    * [OboNCBITaxon91561](../classes/OboNCBITaxon91561.md)
    * [OboNCBITaxon91835](../classes/OboNCBITaxon91835.md)
    * [OboNCBITaxon91836](../classes/OboNCBITaxon91836.md)
    * [OboNCBITaxon91882](../classes/OboNCBITaxon91882.md)
    * [OboNCBITaxon91888](../classes/OboNCBITaxon91888.md)
    * [OboNCBITaxon9347](../classes/OboNCBITaxon9347.md)
    * [OboNCBITaxon96479](../classes/OboNCBITaxon96479.md)
    * [OboNCBITaxon980193](../classes/OboNCBITaxon980193.md)
    * [OboNCBITaxon981071](../classes/OboNCBITaxon981071.md)
    * [OboNCBITaxon9821](../classes/OboNCBITaxon9821.md)
    * [OboNCBITaxon9823](../classes/OboNCBITaxon9823.md)
    * [OboNCBITaxon9825](../classes/OboNCBITaxon9825.md)
    * [OboNCBITaxon9850](../classes/OboNCBITaxon9850.md)
    * [OboNCBITaxon986140](../classes/OboNCBITaxon986140.md)
    * [OboNCBITaxon9895](../classes/OboNCBITaxon9895.md)
    * [OboNCBITaxon9900](../classes/OboNCBITaxon9900.md)
    * [OboNCBITaxon9903](../classes/OboNCBITaxon9903.md)
    * [OboNCBITaxon9913](../classes/OboNCBITaxon9913.md)
    * [OboNCBITaxon9922](../classes/OboNCBITaxon9922.md)
    * [OboNCBITaxon9925](../classes/OboNCBITaxon9925.md)
    * [OboNCBITaxon9935](../classes/OboNCBITaxon9935.md)
    * [OboNCBITaxon9940](../classes/OboNCBITaxon9940.md)
    * [OboNCBITaxon99568](../classes/OboNCBITaxon99568.md)
    * [OboNCBITaxon9963](../classes/OboNCBITaxon9963.md)
    * [OboNCBITaxon9989](../classes/OboNCBITaxon9989.md)
    * [OboOBI0100026](../classes/OboOBI0100026.md)
    * [OboPO0000003](../classes/OboPO0000003.md)
    * [OboPO0025034](../classes/OboPO0025034.md)
    * [OboUBERON0000948](../classes/OboUBERON0000948.md)
    * [OboUBERON0001913](../classes/OboUBERON0001913.md)
    * [OboUBERON0002097](../classes/OboUBERON0002097.md)
    * [OboUBERON0002107](../classes/OboUBERON0002107.md)
    * [OboUBERON0005079](../classes/OboUBERON0005079.md)
    * [OboUBERON0007378](../classes/OboUBERON0007378.md)
    * [OboUBERON0007379](../classes/OboUBERON0007379.md)
    * [OboUBERON0008944](../classes/OboUBERON0008944.md)
    * [QudtEnumeratedQuantity](../classes/QudtEnumeratedQuantity.md)
    * [SosaProcedure](../classes/SosaProcedure.md)
    * [SosaProperty](../classes/SosaProperty.md)
    * [SosaSample](../classes/SosaSample.md)
    * [StadQualityKind](../classes/StadQualityKind.md)
    * [StadQuantity](../classes/StadQuantity.md)
    * [StadSingleData](../classes/StadSingleData.md)
    * [StadStatisticalAggregateData](../classes/StadStatisticalAggregateData.md)
    * [StadStatisticalQuantityKind](../classes/StadStatisticalQuantityKind.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [B00af777bec4da87c5aebb51d94b2d478](../classes/B00af777bec4da87c5aebb51d94b2d478.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [B00af777bec4da87c5aebb51d94b2d478](../classes/B00af777bec4da87c5aebb51d94b2d478.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [B036a3008450d6ce37e35cf5a98355a60](../classes/B036a3008450d6ce37e35cf5a98355a60.md) | [obo_RO_0002162](../slots/obo_RO_0002162.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [B036a3008450d6ce37e35cf5a98355a60](../classes/B036a3008450d6ce37e35cf5a98355a60.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [B036a3008450d6ce37e35cf5a98355a60](../classes/B036a3008450d6ce37e35cf5a98355a60.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [B085dcda89ed6aae0d3b229e767f0a1ca](../classes/B085dcda89ed6aae0d3b229e767f0a1ca.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [B085dcda89ed6aae0d3b229e767f0a1ca](../classes/B085dcda89ed6aae0d3b229e767f0a1ca.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [B0d427a711311f1499a234aa8af2c66d1](../classes/B0d427a711311f1499a234aa8af2c66d1.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [B0d427a711311f1499a234aa8af2c66d1](../classes/B0d427a711311f1499a234aa8af2c66d1.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [B215b3a432e1c482d3680398a554edbbf](../classes/B215b3a432e1c482d3680398a554edbbf.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [B215b3a432e1c482d3680398a554edbbf](../classes/B215b3a432e1c482d3680398a554edbbf.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [B27231c83f17c76e178e0c9f5e10acc55](../classes/B27231c83f17c76e178e0c9f5e10acc55.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [B27231c83f17c76e178e0c9f5e10acc55](../classes/B27231c83f17c76e178e0c9f5e10acc55.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [B37977f50d3140da51a9630b8a57396a1](../classes/B37977f50d3140da51a9630b8a57396a1.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [B37977f50d3140da51a9630b8a57396a1](../classes/B37977f50d3140da51a9630b8a57396a1.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [B3cc7b3721547b07a4068dc98b6444b8b](../classes/B3cc7b3721547b07a4068dc98b6444b8b.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [B3cc7b3721547b07a4068dc98b6444b8b](../classes/B3cc7b3721547b07a4068dc98b6444b8b.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [B423a0e253807f20386fc3ccbbd7e0378](../classes/B423a0e253807f20386fc3ccbbd7e0378.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [B423a0e253807f20386fc3ccbbd7e0378](../classes/B423a0e253807f20386fc3ccbbd7e0378.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [B44bec873efc8b96cad5f525429c64e0a](../classes/B44bec873efc8b96cad5f525429c64e0a.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [B44bec873efc8b96cad5f525429c64e0a](../classes/B44bec873efc8b96cad5f525429c64e0a.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [B4fd286b2a5a12e342d61412628b6e4c2](../classes/B4fd286b2a5a12e342d61412628b6e4c2.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [B4fd286b2a5a12e342d61412628b6e4c2](../classes/B4fd286b2a5a12e342d61412628b6e4c2.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [B53622dee107de372b2d0566f64ab6e3a](../classes/B53622dee107de372b2d0566f64ab6e3a.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [B53622dee107de372b2d0566f64ab6e3a](../classes/B53622dee107de372b2d0566f64ab6e3a.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [B5e93e815b548435105d9273d424fa0e8](../classes/B5e93e815b548435105d9273d424fa0e8.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [B5e93e815b548435105d9273d424fa0e8](../classes/B5e93e815b548435105d9273d424fa0e8.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [B611b8dff312692e7f32a69834c787a60](../classes/B611b8dff312692e7f32a69834c787a60.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [B611b8dff312692e7f32a69834c787a60](../classes/B611b8dff312692e7f32a69834c787a60.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [B623b56ef58fd82dd088819e22d655c08](../classes/B623b56ef58fd82dd088819e22d655c08.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [B623b56ef58fd82dd088819e22d655c08](../classes/B623b56ef58fd82dd088819e22d655c08.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [B75dbc5841338872cea35dced609fcd77](../classes/B75dbc5841338872cea35dced609fcd77.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [B75dbc5841338872cea35dced609fcd77](../classes/B75dbc5841338872cea35dced609fcd77.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [B75e45ed04b2b903b9029968cada06faa](../classes/B75e45ed04b2b903b9029968cada06faa.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [B75e45ed04b2b903b9029968cada06faa](../classes/B75e45ed04b2b903b9029968cada06faa.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [B7728f65369357f97de36b133c9d1d5e0](../classes/B7728f65369357f97de36b133c9d1d5e0.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [B7728f65369357f97de36b133c9d1d5e0](../classes/B7728f65369357f97de36b133c9d1d5e0.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [B8aa8791a0418cd594c8b56ad21351f72](../classes/B8aa8791a0418cd594c8b56ad21351f72.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [B8aa8791a0418cd594c8b56ad21351f72](../classes/B8aa8791a0418cd594c8b56ad21351f72.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [Ba6d85f816540f9fec5b71ba42fc2cca6](../classes/Ba6d85f816540f9fec5b71ba42fc2cca6.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [Ba6d85f816540f9fec5b71ba42fc2cca6](../classes/Ba6d85f816540f9fec5b71ba42fc2cca6.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [Ba76635ffb4afc02e78b9ef49973d089f](../classes/Ba76635ffb4afc02e78b9ef49973d089f.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [Ba76635ffb4afc02e78b9ef49973d089f](../classes/Ba76635ffb4afc02e78b9ef49973d089f.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [Bb0125be5bc4dc7be7e8452e7d22445f6](../classes/Bb0125be5bc4dc7be7e8452e7d22445f6.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [Bb0125be5bc4dc7be7e8452e7d22445f6](../classes/Bb0125be5bc4dc7be7e8452e7d22445f6.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [Bb71af62f2f3e5e5b5e0fe81f24eca409](../classes/Bb71af62f2f3e5e5b5e0fe81f24eca409.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [Bb71af62f2f3e5e5b5e0fe81f24eca409](../classes/Bb71af62f2f3e5e5b5e0fe81f24eca409.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [Bbefc37cbdd03cae92dadef76b34dbf16](../classes/Bbefc37cbdd03cae92dadef76b34dbf16.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [Bbefc37cbdd03cae92dadef76b34dbf16](../classes/Bbefc37cbdd03cae92dadef76b34dbf16.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [Bbf63deb85414ddecd89e46bce27e7f0a](../classes/Bbf63deb85414ddecd89e46bce27e7f0a.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [Bbf63deb85414ddecd89e46bce27e7f0a](../classes/Bbf63deb85414ddecd89e46bce27e7f0a.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [Be047d68edc8eb3ce96d7edbad5217bfc](../classes/Be047d68edc8eb3ce96d7edbad5217bfc.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [Be047d68edc8eb3ce96d7edbad5217bfc](../classes/Be047d68edc8eb3ce96d7edbad5217bfc.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [Be497d3b0c2656040c05e303873a2d541](../classes/Be497d3b0c2656040c05e303873a2d541.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [Be497d3b0c2656040c05e303873a2d541](../classes/Be497d3b0c2656040c05e303873a2d541.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [Beb7217b5b32080b9606028314249e33b](../classes/Beb7217b5b32080b9606028314249e33b.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [Beb7217b5b32080b9606028314249e33b](../classes/Beb7217b5b32080b9606028314249e33b.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [Beb7217b5b32080b9606028314249e33b](../classes/Beb7217b5b32080b9606028314249e33b.md) | [http___w3id.org_comptox_sameAsComptoxSubstance](../slots/http___w3id.org_comptox_sameAsComptoxSubstance.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [Beb77c26f8c395403edc359fd5f6dfb28](../classes/Beb77c26f8c395403edc359fd5f6dfb28.md) | [obo_RO_0002162](../slots/obo_RO_0002162.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [Beb77c26f8c395403edc359fd5f6dfb28](../classes/Beb77c26f8c395403edc359fd5f6dfb28.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [Beb77c26f8c395403edc359fd5f6dfb28](../classes/Beb77c26f8c395403edc359fd5f6dfb28.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [Bf04685c17c0e71ae3c98e08c75cbdfcc](../classes/Bf04685c17c0e71ae3c98e08c75cbdfcc.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [Bf04685c17c0e71ae3c98e08c75cbdfcc](../classes/Bf04685c17c0e71ae3c98e08c75cbdfcc.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [Bf584e1bfd1c74de0eb37e7b926538b83](../classes/Bf584e1bfd1c74de0eb37e7b926538b83.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [Bf584e1bfd1c74de0eb37e7b926538b83](../classes/Bf584e1bfd1c74de0eb37e7b926538b83.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalBloodSample](../classes/CosoAnimalBloodSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalBloodSample](../classes/CosoAnimalBloodSample.md) | [coso_sampleAnnotation](../slots/coso_sampleAnnotation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalBloodSample](../classes/CosoAnimalBloodSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalBloodSample](../classes/CosoAnimalBloodSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalBloodSample](../classes/CosoAnimalBloodSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalBloodSample](../classes/CosoAnimalBloodSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalBloodSample](../classes/CosoAnimalBloodSample.md) | [coso_fromSamplePoint](../slots/coso_fromSamplePoint.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalMaterialSample](../classes/CosoAnimalMaterialSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalMaterialSample](../classes/CosoAnimalMaterialSample.md) | [coso_sampleAnnotation](../slots/coso_sampleAnnotation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalMaterialSample](../classes/CosoAnimalMaterialSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalMaterialSample](../classes/CosoAnimalMaterialSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalMaterialSample](../classes/CosoAnimalMaterialSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalMaterialSample](../classes/CosoAnimalMaterialSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalMaterialSample](../classes/CosoAnimalMaterialSample.md) | [coso_fromSamplePoint](../slots/coso_fromSamplePoint.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalMilkSample](../classes/CosoAnimalMilkSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalMilkSample](../classes/CosoAnimalMilkSample.md) | [coso_sampleAnnotation](../slots/coso_sampleAnnotation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalMilkSample](../classes/CosoAnimalMilkSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalMilkSample](../classes/CosoAnimalMilkSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalMilkSample](../classes/CosoAnimalMilkSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalMilkSample](../classes/CosoAnimalMilkSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleTreatmentStatus](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleTreatmentStatus.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalMilkSample](../classes/CosoAnimalMilkSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalMilkSample](../classes/CosoAnimalMilkSample.md) | [coso_fromSamplePoint](../slots/coso_fromSamplePoint.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalOrganSample](../classes/CosoAnimalOrganSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalOrganSample](../classes/CosoAnimalOrganSample.md) | [coso_sampleAnnotation](../slots/coso_sampleAnnotation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalOrganSample](../classes/CosoAnimalOrganSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalOrganSample](../classes/CosoAnimalOrganSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalOrganSample](../classes/CosoAnimalOrganSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalOrganSample](../classes/CosoAnimalOrganSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalOrganSample](../classes/CosoAnimalOrganSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalOrganSample](../classes/CosoAnimalOrganSample.md) | [coso_fromSamplePoint](../slots/coso_fromSamplePoint.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalTissueSample](../classes/CosoAnimalTissueSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalTissueSample](../classes/CosoAnimalTissueSample.md) | [coso_sampleAnnotation](../slots/coso_sampleAnnotation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalTissueSample](../classes/CosoAnimalTissueSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalTissueSample](../classes/CosoAnimalTissueSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalTissueSample](../classes/CosoAnimalTissueSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalTissueSample](../classes/CosoAnimalTissueSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalTissueSample](../classes/CosoAnimalTissueSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoAnimalTissueSample](../classes/CosoAnimalTissueSample.md) | [coso_fromSamplePoint](../slots/coso_fromSamplePoint.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoContaminantConcentrationQuantityKind](../classes/CosoContaminantConcentrationQuantityKind.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [CosoContaminantConcentrationQuantityKind](../classes/CosoContaminantConcentrationQuantityKind.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [CosoContaminantVolumeQuantityKind](../classes/CosoContaminantVolumeQuantityKind.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [CosoContaminantVolumeQuantityKind](../classes/CosoContaminantVolumeQuantityKind.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [CosoContaminationProperty](../classes/CosoContaminationProperty.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [CosoContaminationProperty](../classes/CosoContaminationProperty.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [CosoDetectQuantityValue](../classes/CosoDetectQuantityValue.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [CosoDetectQuantityValue](../classes/CosoDetectQuantityValue.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [CosoDrinkingWaterSample](../classes/CosoDrinkingWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [CosoDrinkingWaterSample](../classes/CosoDrinkingWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [CosoGroundWaterSample](../classes/CosoGroundWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [CosoGroundWaterSample](../classes/CosoGroundWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [CosoNonDetectQuantityValue](../classes/CosoNonDetectQuantityValue.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [CosoNonDetectQuantityValue](../classes/CosoNonDetectQuantityValue.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [CosoPlantMaterialSample](../classes/CosoPlantMaterialSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoPlantMaterialSample](../classes/CosoPlantMaterialSample.md) | [coso_sampleAnnotation](../slots/coso_sampleAnnotation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoPlantMaterialSample](../classes/CosoPlantMaterialSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoPlantMaterialSample](../classes/CosoPlantMaterialSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoPlantMaterialSample](../classes/CosoPlantMaterialSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [CosoPlantMaterialSample](../classes/CosoPlantMaterialSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [CosoPlantMaterialSample](../classes/CosoPlantMaterialSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoPlantMaterialSample](../classes/CosoPlantMaterialSample.md) | [coso_fromSamplePoint](../slots/coso_fromSamplePoint.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [CosoSubstanceCollection](../classes/CosoSubstanceCollection.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [CosoSubstanceCollection](../classes/CosoSubstanceCollection.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [CosoSurfaceWaterSample](../classes/CosoSurfaceWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [CosoSurfaceWaterSample](../classes/CosoSurfaceWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [CosoTreatedWaterSample](../classes/CosoTreatedWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [CosoTreatedWaterSample](../classes/CosoTreatedWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [CosoWasteWaterSample](../classes/CosoWasteWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [CosoWasteWaterSample](../classes/CosoWasteWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [CosoWaterSample](../classes/CosoWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [CosoWaterSample](../classes/CosoWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [CosoWaterSampleBySource](../classes/CosoWaterSampleBySource.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [CosoWaterSampleBySource](../classes/CosoWaterSampleBySource.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [CosoWaterSampleByTreatment](../classes/CosoWaterSampleByTreatment.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [CosoWaterSampleByTreatment](../classes/CosoWaterSampleByTreatment.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgComptoxCompToxChemicalEntity](../classes/HttpW3id.orgComptoxCompToxChemicalEntity.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgComptoxCompToxChemicalEntity](../classes/HttpW3id.orgComptoxCompToxChemicalEntity.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration.md) | [coso_resultAnnotation](../slots/coso_resultAnnotation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration.md) | [http___w3id.org_sawgraph_v1_me_egad#methodDetectionLimit](../slots/http___w3id.org_sawgraph_v1_me_egad#methodDetectionLimit.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration.md) | [http___w3id.org_sawgraph_v1_me_egad#validationQualifier](../slots/http___w3id.org_sawgraph_v1_me_egad#validationQualifier.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration.md) | [http___w3id.org_sawgraph_v1_me_egad#reportingLimit](../slots/http___w3id.org_sawgraph_v1_me_egad#reportingLimit.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration.md) | [http___w3id.org_sawgraph_v1_me_egad#validationLevel](../slots/http___w3id.org_sawgraph_v1_me_egad#validationLevel.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-AnalysisMethod](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-AnalysisMethod.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-AnalysisMethod](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-AnalysisMethod.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-ConcentrationQualifier](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ConcentrationQualifier.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-ConcentrationQualifier](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ConcentrationQualifier.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-MethodDetectionLimit](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-MethodDetectionLimit.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-MethodDetectionLimit](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-MethodDetectionLimit.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) | [coso_observedAtSamplePoint](../slots/coso_observedAtSamplePoint.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) | [CosoOfDatasetSubstance](../classes/CosoOfDatasetSubstance.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) | [coso_ofSubstance](../slots/coso_ofSubstance.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) | [coso_analyzedSample](../slots/coso_analyzedSample.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) | [coso_observedAtPoint](../slots/coso_observedAtPoint.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) | [coso_hasAnyFeatureOfInterest](../slots/coso_hasAnyFeatureOfInterest.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) | [http___w3id.org_sawgraph_v1_me_egad#resultType](../slots/http___w3id.org_sawgraph_v1_me_egad#resultType.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) | [coso_hasResult](../slots/coso_hasResult.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) | [coso_observationAnnotation](../slots/coso_observationAnnotation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) | [coso_observedProperty](../slots/coso_observedProperty.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) | [coso_hasFeatureOfInterest](../slots/coso_hasFeatureOfInterest.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName.md) | [http___w3id.org_comptox_sameAsComptoxSubstance](../slots/http___w3id.org_comptox_sameAsComptoxSubstance.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Site](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Site.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Site](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Site.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Site](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Site.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Site](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Site.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-ResultType](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ResultType.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-ResultType](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ResultType.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample.md) | [coso_sampleAnnotation](../slots/coso_sampleAnnotation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleTreatmentStatus](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleTreatmentStatus.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample.md) | [coso_fromSamplePoint](../slots/coso_fromSamplePoint.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleCollectionMethod](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleCollectionMethod.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleCollectionMethod](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleCollectionMethod.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleDetailedLocation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleDetailedLocation.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleDetailedLocation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleDetailedLocation.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialType](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialType.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialType](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialType.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialTypeQualifier](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialTypeQualifier.md) | [obo_RO_0002162](../slots/obo_RO_0002162.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialTypeQualifier](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialTypeQualifier.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialTypeQualifier](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleMaterialTypeQualifier.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint.md) | [http___w3id.org_sawgraph_v1_me_egad#samplePointType](../slots/http___w3id.org_sawgraph_v1_me_egad#samplePointType.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint.md) | [coso_pointFromFeature](../slots/coso_pointFromFeature.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePointType](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePointType.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePointType](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePointType.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleTreatmentStatus](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleTreatmentStatus.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleTreatmentStatus](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleTreatmentStatus.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature.md) | [http___w3id.org_sawgraph_v1_me_egad#sampledFeatureType](../slots/http___w3id.org_sawgraph_v1_me_egad#sampledFeatureType.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature.md) | [coso_ofFeatureType](../slots/coso_ofFeatureType.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration.md) | [coso_resultAnnotation](../slots/coso_resultAnnotation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration.md) | [http___w3id.org_sawgraph_v1_me_egad#methodDetectionLimit](../slots/http___w3id.org_sawgraph_v1_me_egad#methodDetectionLimit.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration.md) | [http___w3id.org_sawgraph_v1_me_egad#validationQualifier](../slots/http___w3id.org_sawgraph_v1_me_egad#validationQualifier.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration.md) | [http___w3id.org_sawgraph_v1_me_egad#reportingLimit](../slots/http___w3id.org_sawgraph_v1_me_egad#reportingLimit.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration.md) | [http___w3id.org_sawgraph_v1_me_egad#validationLevel](../slots/http___w3id.org_sawgraph_v1_me_egad#validationLevel.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SiteType](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SiteType.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SiteType](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SiteType.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-ValidationLevel](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ValidationLevel.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-ValidationLevel](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ValidationLevel.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample.md) | [coso_sampleAnnotation](../slots/coso_sampleAnnotation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample.md) | [coso_fromSamplePoint](../slots/coso_fromSamplePoint.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample.md) | [coso_sampleAnnotation](../slots/coso_sampleAnnotation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleTreatmentStatus](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleTreatmentStatus.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample.md) | [coso_fromSamplePoint](../slots/coso_fromSamplePoint.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md) | [coso_sampleAnnotation](../slots/coso_sampleAnnotation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleTreatmentStatus](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleTreatmentStatus.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md) | [coso_fromSamplePoint](../slots/coso_fromSamplePoint.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample.md) | [coso_sampleAnnotation](../slots/coso_sampleAnnotation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample.md) | [coso_fromSamplePoint](../slots/coso_fromSamplePoint.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample.md) | [coso_sampleAnnotation](../slots/coso_sampleAnnotation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleTreatmentStatus](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleTreatmentStatus.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample.md) | [coso_fromSamplePoint](../slots/coso_fromSamplePoint.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample.md) | [coso_isSampleOf](../slots/coso_isSampleOf.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample.md) | [coso_sampleAnnotation](../slots/coso_sampleAnnotation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample.md) | [http___w3id.org_sawgraph_v1_me_egad#sampleTreatmentStatus](../slots/http___w3id.org_sawgraph_v1_me_egad#sampleTreatmentStatus.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample.md) | [coso_fromSamplePoint](../slots/coso_fromSamplePoint.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#DefWQPGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Us-wqp#DefWQPGroundWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#DefWQPGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Us-wqp#DefWQPGroundWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#DefWQPSurfaceWaterSample](../classes/HttpW3id.orgSawgraphV1Us-wqp#DefWQPSurfaceWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#DefWQPSurfaceWaterSample](../classes/HttpW3id.orgSawgraphV1Us-wqp#DefWQPSurfaceWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#DefWQPWasteWaterSample](../classes/HttpW3id.orgSawgraphV1Us-wqp#DefWQPWasteWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#DefWQPWasteWaterSample](../classes/HttpW3id.orgSawgraphV1Us-wqp#DefWQPWasteWaterSample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#Observation](../classes/HttpW3id.orgSawgraphV1Us-wqp#Observation.md) | [coso_observedAtSamplePoint](../slots/coso_observedAtSamplePoint.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#Observation](../classes/HttpW3id.orgSawgraphV1Us-wqp#Observation.md) | [coso_analyzedSample](../slots/coso_analyzedSample.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#Observation](../classes/HttpW3id.orgSawgraphV1Us-wqp#Observation.md) | [coso_hasResult](../slots/coso_hasResult.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#Observation](../classes/HttpW3id.orgSawgraphV1Us-wqp#Observation.md) | [coso_observedProperty](../slots/coso_observedProperty.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#Observation](../classes/HttpW3id.orgSawgraphV1Us-wqp#Observation.md) | [CosoOfDatasetSubstance](../classes/CosoOfDatasetSubstance.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#Observation](../classes/HttpW3id.orgSawgraphV1Us-wqp#Observation.md) | [coso_hasFeatureOfInterest](../slots/coso_hasFeatureOfInterest.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#Sample](../classes/HttpW3id.orgSawgraphV1Us-wqp#Sample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#Sample](../classes/HttpW3id.orgSawgraphV1Us-wqp#Sample.md) | [coso_fromSamplePoint](../slots/coso_fromSamplePoint.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration.md) | [coso_hasResultQualifier](../slots/coso_hasResultQualifier.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [HttpW3id.orgSawgraphV1Us-wqp#Site](../classes/HttpW3id.orgSawgraphV1Us-wqp#Site.md) | [coso_pointFromFeature](../slots/coso_pointFromFeature.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) | [coso_resultAnnotation](../slots/coso_resultAnnotation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) | [me_egad_methodDetectionLimit](../slots/me_egad_methodDetectionLimit.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) | [me_egad_validationLevel](../slots/me_egad_validationLevel.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) | [me_egad_reportingLimit](../slots/me_egad_reportingLimit.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) | [me_egad_validationQualifier](../slots/me_egad_validationQualifier.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-AnalysisMethod](../classes/MeEgadEGAD-AnalysisMethod.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-AnalysisMethod](../classes/MeEgadEGAD-AnalysisMethod.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-ConcentrationQualifier](../classes/MeEgadEGAD-ConcentrationQualifier.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-ConcentrationQualifier](../classes/MeEgadEGAD-ConcentrationQualifier.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-MethodDetectionLimit](../classes/MeEgadEGAD-MethodDetectionLimit.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-MethodDetectionLimit](../classes/MeEgadEGAD-MethodDetectionLimit.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | [coso_observedAtSamplePoint](../slots/coso_observedAtSamplePoint.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | [coso_analyzedSample](../slots/coso_analyzedSample.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | [coso_hasAnyFeatureOfInterest](../slots/coso_hasAnyFeatureOfInterest.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | [me_egad_resultType](../slots/me_egad_resultType.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | [coso_hasResult](../slots/coso_hasResult.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | [coso_observationAnnotation](../slots/coso_observationAnnotation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | [coso_observedAtPoint](../slots/coso_observedAtPoint.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | [coso_hasFeatureOfInterest](../slots/coso_hasFeatureOfInterest.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | [coso_ofSubstance](../slots/coso_ofSubstance.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-PFAS-ParameterName](../classes/MeEgadEGAD-PFAS-ParameterName.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-PFAS-ParameterName](../classes/MeEgadEGAD-PFAS-ParameterName.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-PFAS-Site](../classes/MeEgadEGAD-PFAS-Site.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-PFAS-Site](../classes/MeEgadEGAD-PFAS-Site.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-PFAS-Site](../classes/MeEgadEGAD-PFAS-Site.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-PFAS-Site](../classes/MeEgadEGAD-PFAS-Site.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-ReportingLimit](../classes/MeEgadEGAD-ReportingLimit.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-ReportingLimit](../classes/MeEgadEGAD-ReportingLimit.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-ResultType](../classes/MeEgadEGAD-ResultType.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-ResultType](../classes/MeEgadEGAD-ResultType.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) | [coso_sampleAnnotation](../slots/coso_sampleAnnotation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) | [me_egad_sampleTreatmentStatus](../slots/me_egad_sampleTreatmentStatus.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) | [me_egad_sampleCollectionMethod](../slots/me_egad_sampleCollectionMethod.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) | [me_egad_sampleCollectionLocation](../slots/me_egad_sampleCollectionLocation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) | [coso_sampleOfMaterialType](../slots/coso_sampleOfMaterialType.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) | [coso_fromSamplePoint](../slots/coso_fromSamplePoint.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SampleCollectionMethod](../classes/MeEgadEGAD-SampleCollectionMethod.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SampleCollectionMethod](../classes/MeEgadEGAD-SampleCollectionMethod.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SampleDetailedLocation](../classes/MeEgadEGAD-SampleDetailedLocation.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SampleDetailedLocation](../classes/MeEgadEGAD-SampleDetailedLocation.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SampleMaterialType](../classes/MeEgadEGAD-SampleMaterialType.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SampleMaterialType](../classes/MeEgadEGAD-SampleMaterialType.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SampleMaterialTypeQualifier](../classes/MeEgadEGAD-SampleMaterialTypeQualifier.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SampleMaterialTypeQualifier](../classes/MeEgadEGAD-SampleMaterialTypeQualifier.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md) | [coso_pointFromFeature](../slots/coso_pointFromFeature.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md) | [spatial_spatiallyRelatedTo](../slots/spatial_spatiallyRelatedTo.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md) | [me_egad_samplePointType](../slots/me_egad_samplePointType.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md) | [spatial_connectedTo](../slots/spatial_connectedTo.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SamplePointType](../classes/MeEgadEGAD-SamplePointType.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SamplePointType](../classes/MeEgadEGAD-SamplePointType.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SampleTreatmentStatus](../classes/MeEgadEGAD-SampleTreatmentStatus.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SampleTreatmentStatus](../classes/MeEgadEGAD-SampleTreatmentStatus.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SampledFeature](../classes/MeEgadEGAD-SampledFeature.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SampledFeature](../classes/MeEgadEGAD-SampledFeature.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) | [coso_resultAnnotation](../slots/coso_resultAnnotation.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) | [me_egad_methodDetectionLimit](../slots/me_egad_methodDetectionLimit.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) | [me_egad_validationLevel](../slots/me_egad_validationLevel.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) | [me_egad_reportingLimit](../slots/me_egad_reportingLimit.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) | [me_egad_validationQualifier](../slots/me_egad_validationQualifier.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SiteType](../classes/MeEgadEGAD-SiteType.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-SiteType](../classes/MeEgadEGAD-SiteType.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-ValidationLevel](../classes/MeEgadEGAD-ValidationLevel.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [MeEgadEGAD-ValidationLevel](../classes/MeEgadEGAD-ValidationLevel.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON00001093](../classes/OboFOODON00001093.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON00001093](../classes/OboFOODON00001093.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON00002165](../classes/OboFOODON00002165.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON00002165](../classes/OboFOODON00002165.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON00002477](../classes/OboFOODON00002477.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON00002477](../classes/OboFOODON00002477.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON00003042](../classes/OboFOODON00003042.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON00003042](../classes/OboFOODON00003042.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON00003083](../classes/OboFOODON00003083.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON00003083](../classes/OboFOODON00003083.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON00003425](../classes/OboFOODON00003425.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON00003425](../classes/OboFOODON00003425.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON00003572](../classes/OboFOODON00003572.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON00003572](../classes/OboFOODON00003572.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON00004172](../classes/OboFOODON00004172.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON00004172](../classes/OboFOODON00004172.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON00004436](../classes/OboFOODON00004436.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON00004436](../classes/OboFOODON00004436.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON00004460](../classes/OboFOODON00004460.md) | [obo_RO_0002162](../slots/obo_RO_0002162.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON00004460](../classes/OboFOODON00004460.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON00004460](../classes/OboFOODON00004460.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02010012](../classes/OboFOODON02010012.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02010012](../classes/OboFOODON02010012.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02010015](../classes/OboFOODON02010015.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02010015](../classes/OboFOODON02010015.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02010032](../classes/OboFOODON02010032.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02010032](../classes/OboFOODON02010032.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02010042](../classes/OboFOODON02010042.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02010042](../classes/OboFOODON02010042.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02010045](../classes/OboFOODON02010045.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02010045](../classes/OboFOODON02010045.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02010107](../classes/OboFOODON02010107.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02010107](../classes/OboFOODON02010107.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02020840](../classes/OboFOODON02020840.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02020840](../classes/OboFOODON02020840.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02020892](../classes/OboFOODON02020892.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02020892](../classes/OboFOODON02020892.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02021651](../classes/OboFOODON02021651.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02021651](../classes/OboFOODON02021651.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02021803](../classes/OboFOODON02021803.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02021803](../classes/OboFOODON02021803.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02021805](../classes/OboFOODON02021805.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON02021805](../classes/OboFOODON02021805.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03301761](../classes/OboFOODON03301761.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03301761](../classes/OboFOODON03301761.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03411057](../classes/OboFOODON03411057.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03411057](../classes/OboFOODON03411057.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03411183](../classes/OboFOODON03411183.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03411183](../classes/OboFOODON03411183.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03411236](../classes/OboFOODON03411236.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03411236](../classes/OboFOODON03411236.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03411324](../classes/OboFOODON03411324.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03411324](../classes/OboFOODON03411324.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03411325](../classes/OboFOODON03411325.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03411325](../classes/OboFOODON03411325.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03411328](../classes/OboFOODON03411328.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03411328](../classes/OboFOODON03411328.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03411457](../classes/OboFOODON03411457.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03411457](../classes/OboFOODON03411457.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03411566](../classes/OboFOODON03411566.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03411566](../classes/OboFOODON03411566.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03411583](../classes/OboFOODON03411583.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03411583](../classes/OboFOODON03411583.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03411669](../classes/OboFOODON03411669.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03411669](../classes/OboFOODON03411669.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03413358](../classes/OboFOODON03413358.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03413358](../classes/OboFOODON03413358.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03413378](../classes/OboFOODON03413378.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03413378](../classes/OboFOODON03413378.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03420116](../classes/OboFOODON03420116.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03420116](../classes/OboFOODON03420116.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03420147](../classes/OboFOODON03420147.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03420147](../classes/OboFOODON03420147.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03420150](../classes/OboFOODON03420150.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03420150](../classes/OboFOODON03420150.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03420181](../classes/OboFOODON03420181.md) | [obo_RO_0002162](../slots/obo_RO_0002162.md) | any_of[range] | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03420181](../classes/OboFOODON03420181.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03420181](../classes/OboFOODON03420181.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03420194](../classes/OboFOODON03420194.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboFOODON03420194](../classes/OboFOODON03420194.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboNCBITaxon147949](../classes/OboNCBITaxon147949.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboNCBITaxon147949](../classes/OboNCBITaxon147949.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboNCBITaxon27706](../classes/OboNCBITaxon27706.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboNCBITaxon27706](../classes/OboNCBITaxon27706.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboNCBITaxon381124](../classes/OboNCBITaxon381124.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboNCBITaxon381124](../classes/OboNCBITaxon381124.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboNCBITaxon8010](../classes/OboNCBITaxon8010.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboNCBITaxon8010](../classes/OboNCBITaxon8010.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboNCBITaxon8038](../classes/OboNCBITaxon8038.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboNCBITaxon8038](../classes/OboNCBITaxon8038.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [OboNCBITaxon8182](../classes/OboNCBITaxon8182.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [OboNCBITaxon8182](../classes/OboNCBITaxon8182.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [StadQualityKind](../classes/StadQualityKind.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [StadQualityKind](../classes/StadQualityKind.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |
| [StadStatisticalQuantityKind](../classes/StadStatisticalQuantityKind.md) | [owl_sameAs](../slots/owl_sameAs.md) | domain | [OwlThing](../classes/OwlThing.md) |
| [StadStatisticalQuantityKind](../classes/StadStatisticalQuantityKind.md) | [owl_sameAs](../slots/owl_sameAs.md) | range | [OwlThing](../classes/OwlThing.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: owl_Thing
description: The class of OWL individuals.
title: Thing
from_schema: okns:owl-rdf-rdfs
source: http://www.w3.org/2002/07/owl#
class_uri: owl:Thing

```
</details>

### Induced

<details>

```yaml
name: owl_Thing
description: The class of OWL individuals.
title: Thing
from_schema: okns:owl-rdf-rdfs
source: http://www.w3.org/2002/07/owl#
class_uri: owl:Thing

```
</details>