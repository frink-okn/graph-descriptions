# No schema name specified

SUDOKN Ontology is developed at the Semantic Computing Lab ast ASU. SUDOKN provides the necessary semantics for describing the capabilities of manufacturing companies. SUDOKN used BFO as the top-level ontology and IOF Core and IOF Supply Chain as the mid-level ontologies



## Schema Diagram

```mermaid
erDiagram
IoGroupOfPersons {

}
IoIdentifier {

}
IoInformationContentEntity {

}
IoManufacturer {
    uri sudokn_hasManagementCapability  
    uri sudokn_hasWebAddress  
    uri sudokn_hasEmailAddress  
    uri sudokn_hasNumberOfEmployees  
    integer sudokn_hasNumberOfEmployees  
    uri sudokn_hasProcessCapability  
    uri sudokn_hasPostalAddress  
    string rdfs_label  
    uri sudokn_hasMaterialCapability  
    uri sudokn_manufactures  
    uri sudokn_hasCertificate  
    uri sudokn_suppliesToIndustry  
    string sudokn_hasOrganizationYearOfEstablishment  
    uri sudokn_hasNAICSClassifier  
    uri sudokn_hasOwnershipStatusClassifier  
}
IoMaterialProduct {
    string rdfs_label  
}
IoPhysicalLocationIdentifier {

}
IoscIndustry {

}
IoscProductionCapability {

}
OboBFO0000019 {

}
OboBFO0000029 {

}
OwlAllDisjointClasses {
    uri owl_members  
}
OwlNamedIndividual {
    uri sudokn_hasManagementCapability  
    uri sudokn_hasWebAddress  
    uri sudokn_hasEmailAddress  
    uri sudokn_hasProcessCapability  
    uri sudokn_attestsTo  
    uri sudokn_hasPostalAddress  
    uri sudokn_hasMaterialCapability  
    uri sudokn_hasNAICSClassifier  
    uri sudokn_hasCertificate  
    uri sudokn_suppliesToIndustry  
    string rdfs_label  
    string skos_altLabel  
    uri sudokn_hasOwnershipStatusClassifier  
}
Sudokn2-AxisCNCTurningCapability {
    string rdfs_label  
}
Sudokn3DPrintingCapability {
    string rdfs_label  
}
SudoknAS9000Certificate {
    string rdfs_label  
}
SudoknAS9003Certificate {

}
SudoknAS9100 {
    string rdfs_label  
}
SudoknAS9100Certificate {
    uri sudokn_attestsTo  
    string rdfs_label  
}
SudoknAS9102Certificate {
    string rdfs_label  
}
SudoknASCertificate {

}
SudoknASME {
    string rdfs_label  
}
SudoknASMECertificate {
    string rdfs_label  
}
SudoknAWSWelderCertificate {
    string rdfs_label  
}
SudoknAbrasiveCleaningCapability {
    string rdfs_label  
}
SudoknAbrassiveMachiningCapability {
    string rdfs_label  
}
SudoknAccommodationAndFoodServices {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknAcetalProcessingCapability {
    string rdfs_label  
}
SudoknAcrylicFabricationCapability {
    string rdfs_label  
}
SudoknAdditiveManufacturingCapability {
    string rdfs_label  
}
SudoknAddtiveManufacturingCapability {
    string rdfs_label  
}
SudoknAdministrativeAndSupportAndWasteServices {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknAerospaceIndustry {
    string rdfs_label  
}
SudoknAgricultureForestryFishingAndHunting {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknAgricultureIndustry {
    string rdfs_label  
}
SudoknAlloySteelProcessingCapability {
    string rdfs_label  
}
SudoknAluminumProcessingCapability {
    string rdfs_label  
}
SudoknAnnealingCapability {
    string rdfs_label  
}
SudoknAnodizingCapability {
    string rdfs_label  
}
SudoknApparelIndustry {
    string rdfs_label  
}
SudoknArtsEnterntainmentAndRecreation {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknAssemblyCapability {
    string rdfs_label  
}
SudoknAssemblyCapibility {

}
SudoknAtomicHydrogenWeldingCapability {
    string rdfs_label  
}
SudoknAutomotiveIndustry {
    string rdfs_label  
}
SudoknBABACertificate {
    string rdfs_label  
}
SudoknBeltSandingCapability {
    string rdfs_label  
}
SudoknBendingCapability {
    string rdfs_label  
}
SudoknBerylliumProcessingCapability {
    string rdfs_label  
}
SudoknBeverageIndustry {
    string rdfs_label  
}
SudoknBlackOxideCoatingCapability {
    string rdfs_label  
}
SudoknBoringCapability {
    string rdfs_label  
}
SudoknBrandName {

}
SudoknBrassBlackeningCapability {
    string rdfs_label  
}
SudoknBrassProcessingCapability {
    string rdfs_label  
}
SudoknBrazeWeldingCapability {
    string rdfs_label  
}
SudoknBrazingCapability {
    string rdfs_label  
}
SudoknBritishRetailConsortiumAccreditation {
    string rdfs_label  
}
SudoknBritishRetailConsortiumCertificate {

}
SudoknBroachingCapability {
    string rdfs_label  
}
SudoknBronzeProcessingCapability {
    string rdfs_label  
}
SudoknBuildingNumber {

}
SudoknBusinessEquipmentIndustry {
    string rdfs_label  
}
SudoknButtWeldingCapability {
    string rdfs_label  
}
SudoknCADCAMCapability {

}
SudoknCADCapability {
    string rdfs_label  
}
SudoknCAECapability {

}
SudoknCNCBendingCapability {
    string rdfs_label  
}
SudoknCNCClyndricalGrindingCapability {
    string rdfs_label  
}
SudoknCNCCuttingCapability {
    string rdfs_label  
}
SudoknCNCCylindricalGrindingCapability {
    string rdfs_label  
}
SudoknCNCFormingCapability {
    string rdfs_label  
}
SudoknCNCGrindingCapability {
    string rdfs_label  
}
SudoknCNCHorizontalTurningCapability {
    string rdfs_label  
}
SudoknCNCLaserCuttingCapability {
    string rdfs_label  
}
SudoknCNCLatheCapability {
    string rdfs_label  
}
SudoknCNCMachiningCapability {
    string rdfs_label  
}
SudoknCNCMillingCapability {
    string rdfs_label  
}
SudoknCNCPlasmaCuttingCapability {
    string rdfs_label  
}
SudoknCNCPressBrakeCapability {
    string rdfs_label  
}
SudoknCNCTurningCapability {
    string rdfs_label  
}
SudoknCNCVerticalMillingCapability {
    string rdfs_label  
}
SudoknCNCWireBendingCapability {
    string rdfs_label  
}
SudoknCNCmillingCapability {
    string rdfs_label  
}
SudoknCarbideProcessingCapability {
    string rdfs_label  
}
SudoknCarbonArcBrazingCapability {
    string rdfs_label  
}
SudoknCarbonArcWeldingCapability {
    string rdfs_label  
}
SudoknCarbonGraphiteProcessingCapability {
    string rdfs_label  
}
SudoknCarbonProcessingCapability {

}
SudoknCarbonitridingCapability {
    string rdfs_label  
}
SudoknCarburizingCapability {
    string rdfs_label  
}
SudoknCastingCapability {
    string rdfs_label  
}
SudoknCenterlessGrindingCapability {
    string rdfs_label  
}
SudoknCentrifugalCastingCapability {
    string rdfs_label  
}
SudoknCerakoteCoatingCapability {
    string rdfs_label  
}
SudoknCeramicMoldCastingCapability {
    string rdfs_label  
}
SudoknCeramicProcessingCapability {
    string rdfs_label  
}
SudoknCertificate {

}
SudoknChemicalAndPetrochemicalIndustry {
    string rdfs_label  
}
SudoknChemicalCleaningCapability {
    string rdfs_label  
}
SudoknChemicalCoatingCapability {
    string rdfs_label  
}
SudoknChemicalProcessingCapability {
    string rdfs_label  
}
SudoknChemicalsProcessingCapability {
    string rdfs_label  
}
SudoknChromateConversionCoatingCapability {
    string rdfs_label  
}
SudoknChromiumProcessingCapability {
    string rdfs_label  
}
SudoknCity {
    string rdfs_label  
}
SudoknCityOfAddress {

}
SudoknClassifier {

}
SudoknClyndricalGrindingCapability {
    string rdfs_label  
}
SudoknCoatingCapability {
    string rdfs_label  
}
SudoknCobaltProcessingCapability {
    string rdfs_label  
}
SudoknColdRolledSteelProcessingCapability {
    string rdfs_label  
}
SudoknCombustableGasWeldingCapability {
    string rdfs_label  
}
SudoknCommunicationAndElectronicPowerUtilitiesIndustry {
    string rdfs_label  
}
SudoknCommunicationIndustry {
    string rdfs_label  
}
SudoknCommunicationandElectronicPowerUtilitiesIndustry {
    string rdfs_label  
}
SudoknCommunicationsIndustry {

}
SudoknCompositeProcessingCapability {
    string rdfs_label  
}
SudoknComputerIndustry {
    string rdfs_label  
}
SudoknComputersandElectronicProductsIndustry {
    string rdfs_label  
}
SudoknConstruction {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknConstructionIndustry {
    string rdfs_label  
}
SudoknConsumerGoods {
    string rdfs_label  
}
SudoknConsumerGoodsIndustry {
    string rdfs_label  
}
SudoknContinuousCastingCapability {
    string rdfs_label  
}
SudoknCopperProcessingCapability {
    string rdfs_label  
}
SudoknCounterBoringCapability {
    string rdfs_label  
}
SudoknCounterSinkingCapability {
    string rdfs_label  
}
SudoknCountry {

}
SudoknCountryOfAddress {

}
SudoknCounty {

}
SudoknCreepFeedGrindingCapability {
    string rdfs_label  
}
SudoknCrochetCapability {

}
SudoknCustomFoamCuttingCapability {
    string rdfs_label  
}
SudoknCuttingCapability {
    string rdfs_label  
}
SudoknCylindricalGrindingCapability {
    string rdfs_label  
}
SudoknDeburringCapability {
    string rdfs_label  
}
SudoknDeepFreezingCapability {
    string rdfs_label  
}
SudoknDeepHoleDrillingCapability {
    string rdfs_label  
}
SudoknDelrinProcessingCapability {
    string rdfs_label  
}
SudoknDesignativeName {

}
SudoknDieCastingCapability {
    string rdfs_label  
}
SudoknDieDesignCapability {

}
SudoknDieMakingCapability {
    string rdfs_label  
}
SudoknDifficultToMachineMaterialsProcessingCapability {
    string rdfs_label  
}
SudoknDiffusionBondingCapability {
    string rdfs_label  
}
SudoknDiffusionHardeningCapability {
    string rdfs_label  
}
SudoknDigitalPrintingCapability {
    string rdfs_label  
}
SudoknDipBrazingCapability {
    string rdfs_label  
}
SudoknDrawingCapability {
    string rdfs_label  
}
SudoknDrillingCapability {
    string rdfs_label  
}
SudoknDyeingCapability {

}
SudoknEDMCapability {
    string rdfs_label  
}
SudoknEducationIndustry {
    string rdfs_label  
}
SudoknEducationalInstitutionsIndustry {
    string rdfs_label  
}
SudoknEducationalServices {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknElectolessNickelPlatingCapability {
    string rdfs_label  
}
SudoknElectricArcWeldingCapability {
    string rdfs_label  
}
SudoknElectricAutomotiveIndustry {
    string rdfs_label  
}
SudoknElectricVehiclesIndustry {
    string rdfs_label  
}
SudoknElectricalDischargeMachiningCapability {
    string rdfs_label  
}
SudoknElectricalResistanceWeldingCapability {
    string rdfs_label  
}
SudoknElectroPlatingCapability {
    string rdfs_label  
}
SudoknElectroSlagWeldingCapability {
    string rdfs_label  
}
SudoknElectrolessNickelPlating {
    string rdfs_label  
}
SudoknElectrolessNickelPlatingCapability {
    string rdfs_label  
}
SudoknElectrolessPlatingCapability {
    string rdfs_label  
}
SudoknElectronBeamWeldingCapability {
    string rdfs_label  
}
SudoknElectronicAutomotiveInudstry {
    string rdfs_label  
}
SudoknElectronicProcessingCapability {

}
SudoknElectronicProductIndustry {
    string rdfs_label  
}
SudoknElectroplatingCapability {
    string rdfs_label  
}
SudoknElectropolishingCapability {
    string rdfs_label  
}
SudoknEmailAddress {

}
SudoknEmbossingCapability {
    string rdfs_label  
}
SudoknEndFormingCapability {
    string rdfs_label  
}
SudoknEndMillingCapability {
    string rdfs_label  
}
SudoknEngineeringCapability {

}
SudoknEngineeringDesignCapability {
    string rdfs_label  
}
SudoknEtchingCapability {
    string rdfs_label  
}
SudoknExoticMaterialProcessingCapability {
    string rdfs_label  
}
SudoknExplosiveWeldingCapability {
    string rdfs_label  
}
SudoknExtremelyHardMaterialProcessingCapability {
    string rdfs_label  
}
SudoknExtrudingCapability {
    string rdfs_label  
}
SudoknExtrusionCapability {
    string rdfs_label  
}
SudoknFDA-GMPCertificate {
    string rdfs_label  
}
SudoknFDA-PMACertificate {
    string rdfs_label  
}
SudoknFDACertificate {
    string rdfs_label  
}
SudoknFDAGMPCompliant {
    string rdfs_label  
}
SudoknFabricatingCapability {
    string rdfs_label  
}
SudoknFabricationCapability {
    string rdfs_label  
}
SudoknFaceMillingCapability {
    string rdfs_label  
}
SudoknFasteningCapability {
    string rdfs_label  
}
SudoknFiberOpticLaserCuttingCapability {
    string rdfs_label  
}
SudoknFiberProcessingCapability {

}
SudoknFillingCapability {
    string rdfs_label  
}
SudoknFinanceAndInsurance {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknFinishingCapability {
    string rdfs_label  
}
SudoknFixtureDesignCapability {
    string rdfs_label  
}
SudoknFixturingCapability {
    string rdfs_label  
}
SudoknFlameSprayingCapability {
    string rdfs_label  
}
SudoknFoamProcessingCapability {
    string rdfs_label  
}
SudoknFoodIndustry {
    string rdfs_label  
}
SudoknForgingCapability {
    string rdfs_label  
}
SudoknFormingCapability {
    string rdfs_label  
}
SudoknFrictionWeldingCapability {
    string rdfs_label  
}
SudoknFurnaceBrazingCapability {
    string rdfs_label  
}
SudoknFurnitureIndustry {
    string rdfs_label  
}
SudoknGWOCertificate {

}
SudoknGalvanizingCapability {
    string rdfs_label  
}
SudoknGasBrazingCapability {
    string rdfs_label  
}
SudoknGasMetalArcWeldingCapability {
    string rdfs_label  
}
SudoknGasTungstenArcWeldingCapability {
    string rdfs_label  
}
SudoknGasWeldingCapability {
    string rdfs_label  
}
SudoknGearCuttingCapability {
    string rdfs_label  
}
SudoknGearHobbingCapability {
    string rdfs_label  
}
SudoknGeopoliticalSite {

}
SudoknGeospatialLocation {
    uri sudokn_hasPostalAddress  
}
SudoknGlassProcessingCapability {
    string rdfs_label  
}
SudoknGoldProcessingCapability {
    string rdfs_label  
}
SudoknGovermentIndustry {
    string rdfs_label  
}
SudoknGovernmentIndustry {
    string rdfs_label  
}
SudoknGraphiteProcessingCapability {
    string rdfs_label  
}
SudoknGrindingCapability {
    string rdfs_label  
}
SudoknHAACPCertificate {
    string rdfs_label  
}
SudoknHardeningCapability {
    string rdfs_label  
}
SudoknHarperizingCapability {
    string rdfs_label  
}
SudoknHastelloyProcessingCapability {
    string rdfs_label  
}
SudoknHealthCareServicesIndustry {
    string rdfs_label  
}
SudoknHealthcareAndSocialAssistance {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknHealthcareServices {

}
SudoknHealthcareServicesIndustry {
    string rdfs_label  
}
SudoknHeatTreatingCapability {
    string rdfs_label  
}
SudoknHighEnergyBeamMachiningCapability {

}
SudoknHighEnergyBeamWeldingCapability {
    string rdfs_label  
}
SudoknHighGradeAluminumProcessingCapability {
    string rdfs_label  
}
SudoknHoleDrillingEDMCapability {
    string rdfs_label  
}
SudoknHoleMakingCapability {
    string rdfs_label  
}
SudoknHoningCapability {
    string rdfs_label  
}
SudoknHorizontalMillingCapability {
    string rdfs_label  
}
SudoknHotDipGalvanizingCapability {
    string rdfs_label  
}
SudoknIATF16949Certificate {
    string rdfs_label  
}
SudoknIS-TS16949 {
    string rdfs_label  
}
SudoknISO13485 {
    string rdfs_label  
}
SudoknISO13485Certificate {
    string rdfs_label  
}
SudoknISO14000Certificate {
    string rdfs_label  
}
SudoknISO14001 {
    string rdfs_label  
}
SudoknISO14001Certificate {
    string rdfs_label  
}
SudoknISO17265Certificate {
    string rdfs_label  
}
SudoknISO27001Certificate {
    string rdfs_label  
}
SudoknISO9000 {
    string rdfs_label  
}
SudoknISO9000Certificate {
    uri sudokn_attestsTo  
    string rdfs_label  
}
SudoknISO9001 {
    string rdfs_label  
}
SudoknISO9001Certificate {
    string rdfs_label  
}
SudoknISOCertificate {
    string rdfs_label  
}
SudoknISTS-16949Certificate {

}
SudoknISTS16949Certificate {
    string rdfs_label  
}
SudoknISTSCertificate {

}
SudoknITARCertificate {
    string rdfs_label  
}
SudoknITARCompliant {
    string rdfs_label  
}
SudoknInconelProcessingCapability {
    string rdfs_label  
}
SudoknInductionBrazingCapability {
    string rdfs_label  
}
SudoknInductionHeatingCapability {
    string rdfs_label  
}
SudoknIndustrialMachineryandEquipmentIndustry {
    string rdfs_label  
}
SudoknIndustry {
    string rdfs_label  
}
SudoknInformation {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknInfraredBrazingCapability {
    string rdfs_label  
}
SudoknInjectionMoldingCapability {
    string rdfs_label  
}
SudoknInstallationCapability {
    string rdfs_label  
}
SudoknInvarProcessingCapability {
    string rdfs_label  
}
SudoknInvestmentCastingCapability {
    string rdfs_label  
}
SudoknIronProcessingCapability {
    string rdfs_label  
}
SudoknJoiningCapability {
    string rdfs_label  
}
SudoknKOSHERApproved {
    string rdfs_label  
}
SudoknKaptonProcessingCapability {
    string rdfs_label  
}
SudoknKittingCapability {
    string rdfs_label  
}
SudoknKnittingCapability {
    string rdfs_label  
}
SudoknKnurlingCapability {
    string rdfs_label  
}
SudoknKosherApprovedCertificate {

}
SudoknKovarProcessingCapability {
    string rdfs_label  
}
SudoknLEEDCertificate {
    string rdfs_label  
}
SudoknLaserBeamWeldingCapability {
    string rdfs_label  
}
SudoknLaserCuttingCapability {
    string rdfs_label  
}
SudoknLaserEtchingCapability {
    string rdfs_label  
}
SudoknLaserProcessingCapability {
    string rdfs_label  
}
SudoknLaserWeldingCapability {
    string rdfs_label  
}
SudoknLatheWorkCapability {
    string rdfs_label  
}
SudoknLeadProcessingCapability {
    string rdfs_label  
}
SudoknLexanProcessingCapability {
    string rdfs_label  
}
SudoknLiquidCoatingCapability {
    string rdfs_label  
}
SudoknLiveToolingCapability {
    string rdfs_label  
}
SudoknLowAlloySteelProcessingCapability {
    string rdfs_label  
}
SudoknMIGWeldinCapability {
    string rdfs_label  
}
SudoknMIGWeldingCapability {
    string rdfs_label  
}
SudoknMachinaryAndEquipmentIndustry {
    string rdfs_label  
}
SudoknMachineBuildingCapability {
    string rdfs_label  
}
SudoknMachiningCapability {
    string rdfs_label  
}
SudoknMagnesiumAlloyProcessingCapability {
    string rdfs_label  
}
SudoknMagnesiumProcessingCapability {
    string rdfs_label  
}
SudoknManMadeFiberProcessingCapability {
    string rdfs_label  
}
SudoknManagementOfCompaniesAndEnterprise {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknManufacturing {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknManufacturingProcessCapability {

}
SudoknMaterialProcessingCapability {

}
SudoknMechanicalAssemblyCapability {
    string rdfs_label  
}
SudoknMechanicalCoatingCapability {
    string rdfs_label  
}
SudoknMechanicalJoiningCapability {
    string rdfs_label  
}
SudoknMechanicalWeldingCapability {
    string rdfs_label  
}
SudoknMediaBlastingCapability {
    string rdfs_label  
}
SudoknMetalFabricationCapability {
    string rdfs_label  
}
SudoknMetalProcessingCapability {
    string rdfs_label  
}
SudoknMetalProductionIndustry {
    string rdfs_label  
}
SudoknMetalProductsIndustry {

}
SudoknMetalSpinningCapability {
    string rdfs_label  
}
SudoknMetalStampingCapability {
    string rdfs_label  
}
SudoknMetalsProductsIndustry {
    string rdfs_label  
}
SudoknMetalworkingCapability {
    string rdfs_label  
}
SudoknMigWeldingCapability {
    string rdfs_label  
}
SudoknMilitaryIndustry {
    string rdfs_label  
}
SudoknMillingCapability {
    string rdfs_label  
}
SudoknMining {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknMiningIndustry {
    string rdfs_label  
}
SudoknMoldMakingCapability {
    string rdfs_label  
}
SudoknMoldingCapability {
    string rdfs_label  
}
SudoknMolybdenumProcessingCapability {
    string rdfs_label  
}
SudoknMultiPointCuttingCapability {
    string rdfs_label  
}
SudoknNADCAPAC7004 {
    string rdfs_label  
}
SudoknNADCAPCertificate {
    string rdfs_label  
}
SudoknNAICS332111 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332112 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332114 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332115 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332116 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332117 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332211 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332212 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332213 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332214 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332311 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332312 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332313 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332321 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332322 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332323 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332410 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332420 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332431 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332439 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332510 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332611 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332612 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332618 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332710 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332721 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332722 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332811 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332812 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332813 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332911 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332912 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332913 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332919 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332991 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332992 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332994 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332995 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332996 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332997 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332998 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICS332999 {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNAICSClassifier {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknNIST-800-171Certificate {

}
SudoknNISTCertificate {

}
SudoknNaturalFiberProcessingCapability {
    string rdfs_label  
}
SudoknNickelPlatingCapability {
    string rdfs_label  
}
SudoknNickelProcessingCapability {
    string rdfs_label  
}
SudoknNitridingCapability {
    string rdfs_label  
}
SudoknNomexProcessingCapability {
    string rdfs_label  
}
SudoknNotchingCapability {
    string rdfs_label  
}
SudoknNylonProcessingCapability {
    string rdfs_label  
}
SudoknOffshoreWindIndustry {
    string rdfs_label  
}
SudoknOilAndGasIndustry {
    string rdfs_label  
}
SudoknOilGroovingCapability {
    string rdfs_label  
}
SudoknOrganizationName {

}
SudoknOwnershipStatusClassifier {
    string rdfs_label  
    string skos_altLabel  
}
SudoknOxy-FuelCuttingCapability {
    string rdfs_label  
}
SudoknPLCProgrammingCapability {
    string rdfs_label  
}
SudoknPackagingCapability {
    string rdfs_label  
}
SudoknPackingCapability {
    string rdfs_label  
}
SudoknPaintingCapability {
    string rdfs_label  
}
SudoknPalladiumProcessingCapability {
    string rdfs_label  
}
SudoknPaperIndustry {
    string rdfs_label  
}
SudoknPaperandPaperboardProductsIndustry {
    string rdfs_label  
}
SudoknPaperboardProductsIndustry {
    string rdfs_label  
}
SudoknPassivationCapability {
    string rdfs_label  
}
SudoknPemInsertionCapability {
    string rdfs_label  
}
SudoknPercussionWeldingCapability {
    string rdfs_label  
}
SudoknPermanentMoldCastingCapability {
    string rdfs_label  
}
SudoknPhosBronzeProcessingCapability {
    string rdfs_label  
}
SudoknPhosphateCoatingCapability {
    string rdfs_label  
}
SudoknPhosphorBronzeProcessingCapability {
    string rdfs_label  
}
SudoknPhysicalVaporDepositionCapability {
    string rdfs_label  
}
SudoknPipingFabricationCapability {
    string rdfs_label  
}
SudoknPlaningCapability {
    string rdfs_label  
}
SudoknPlasmaArcWeldingCapability {
    string rdfs_label  
}
SudoknPlasmaCuttingCapability {
    string rdfs_label  
}
SudoknPlasmaSprayingCapability {
    string rdfs_label  
}
SudoknPlasterMoldCastingCapability {
    string rdfs_label  
}
SudoknPlasticAndRubberIndustry {
    string rdfs_label  
}
SudoknPlasticMachiningCapability {
    string rdfs_label  
}
SudoknPlasticProcessingCapability {
    string rdfs_label  
}
SudoknPlasticsandRubberProductsIndustry {
    string rdfs_label  
}
SudoknPlatingCapability {
    string rdfs_label  
}
SudoknPlatinumProcessingCapability {
    string rdfs_label  
}
SudoknPolishingCapability {
    string rdfs_label  
}
SudoknPolycarbonateProcessingCapability {
    string rdfs_label  
}
SudoknPolycrystallineDiamondMachiningCapability {
    string rdfs_label  
}
SudoknPostalAddress {
    string iosc_hasTextValue  
}
SudoknPowderCoatingCapability {
    string rdfs_label  
}
SudoknPreciousMaterialProcessingCapability {
    string rdfs_label  
}
SudoknPressBrakingCapability {
    string rdfs_label  
}
SudoknPressingCapability {
    string rdfs_label  
}
SudoknPressureWeldingCapability {
    string rdfs_label  
}
SudoknPrintingAndInformationIndustry {
    string rdfs_label  
}
SudoknPrintingCapability {
    string rdfs_label  
}
SudoknProductDesignCapability {
    string rdfs_label  
}
SudoknProfessionalScientificAndTechnicalServices {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknProfessionalServices {

}
SudoknProfessionalServicesIndustry {
    string rdfs_label  
}
SudoknProjectionWeldingCapability {
    string rdfs_label  
}
SudoknPrototypeManufacturingCapability {
    string rdfs_label  
}
SudoknPrototypingCapability {
    string rdfs_label  
}
SudoknPublicAdministration {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknPulsedElectrochemicalMachiningCapability {
    string rdfs_label  
}
SudoknPunchingCapability {
    string rdfs_label  
}
SudoknQS9000 {
    string rdfs_label  
}
SudoknQS9000Certificate {
    string rdfs_label  
}
SudoknQSCertificate {

}
SudoknQualityCertificate {

}
SudoknQualityManagementCapability {

}
SudoknRAMEDMCapability {
    string rdfs_label  
}
SudoknRAMEdmCapability {
    string rdfs_label  
}
SudoknRamEDMCapability {
    string rdfs_label  
}
SudoknRapidPrototypingCapability {
    string rdfs_label  
}
SudoknRealEstateRentalAndLeasing {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknReamingCapability {
    string rdfs_label  
}
SudoknRecyclingIndustry {
    string rdfs_label  
}
SudoknResistanceBrazingCapability {
    string rdfs_label  
}
SudoknResistanceWeldingCapability {
    string rdfs_label  
}
SudoknRestaurantIndustry {
    string rdfs_label  
}
SudoknRetailIndustry {
    string rdfs_label  
}
SudoknRetailTrade {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknRetailTradeIndustry {
    string rdfs_label  
}
SudoknReverseEngineeringCapability {
    string rdfs_label  
}
SudoknRivetingCapability {
    string rdfs_label  
}
SudoknRivettingCapability {
    string rdfs_label  
}
SudoknRoboticWeldingCapability {
    string rdfs_label  
}
SudoknRollingCapability {
    string rdfs_label  
}
SudoknRubberProcessingCapability {
    string rdfs_label  
}
SudoknSandBlastingCapability {
    string rdfs_label  
}
SudoknSandCastingCapability {
    string rdfs_label  
}
SudoknSanitaryWeldingCapability {
    string rdfs_label  
}
SudoknSawingCapability {
    string rdfs_label  
}
SudoknScreenPrintingCapability {
    string rdfs_label  
}
SudoknSeamWeldingCapability {
    string rdfs_label  
}
SudoknSewingCapability {
    string rdfs_label  
}
SudoknShapingCapability {
    string rdfs_label  
}
SudoknShearingCapability {
    string rdfs_label  
}
SudoknSheeringCapability {
    string rdfs_label  
}
SudoknSheetMetalFabricationCapability {
    string rdfs_label  
}
SudoknSheetMetalFormingCapability {
    string rdfs_label  
}
SudoknSheetMetalProcessingCapability {
    string rdfs_label  
}
SudoknShellMoldCastingCapability {
    string rdfs_label  
}
SudoknShieldedMetalArcWeldingCapability {
    string rdfs_label  
}
SudoknShotPeeningCapability {
    string rdfs_label  
}
SudoknShrinkFittingCapability {
    string rdfs_label  
}
SudoknSiliconeProcessingCapability {
    string rdfs_label  
}
SudoknSilkScreeningCapability {
    string rdfs_label  
}
SudoknSilverProcessingCapability {
    string rdfs_label  
}
SudoknSinglePointCuttingCapability {
    string rdfs_label  
}
SudoknSinkerEDMCapability {
    string rdfs_label  
}
SudoknSinkerEdmCapability {
    string rdfs_label  
}
SudoknSinteringCapability {
    string rdfs_label  
}
SudoknSlabMillingCapability {
    string rdfs_label  
}
SudoknSmeltingCapability {
    string rdfs_label  
}
SudoknSolderingCapability {
    string rdfs_label  
}
SudoknSpecialBusinessStatusClassifier {

}
SudoknSpecialMaterialsProcessingCapability {
    string rdfs_label  
}
SudoknSpinningCapability {
    string rdfs_label  
}
SudoknSportsAndLeisureIndustry {
    string rdfs_label  
}
SudoknSportsandLeisureIndustry {
    string rdfs_label  
}
SudoknSpotWeldingCapability {
    string rdfs_label  
}
SudoknStainlessSteelProcessingCapability {
    string rdfs_label  
}
SudoknStampingCapability {
    string rdfs_label  
}
SudoknState {
    string rdfs_label  
}
SudoknStateOfAddress {

}
SudoknSteelAlloyProcessingCapability {
    string rdfs_label  
}
SudoknSteelManufacturingCapability {
    string rdfs_label  
}
SudoknSteelProcessingCapability {
    string rdfs_label  
}
SudoknStreetAddress {

}
SudoknStretchFormingCapability {
    string rdfs_label  
}
SudoknStudWeldingCapability {
    string rdfs_label  
}
SudoknSubmergedArcWeldingCapability {
    string rdfs_label  
}
SudoknSurfaceFinishingCapability {
    string rdfs_label  
}
SudoknSurfaceGrindingCapability {
    string rdfs_label  
}
SudoknSurfaceHardeningCapability {
    string rdfs_label  
}
SudoknSurfacePreparationCapability {
    string rdfs_label  
}
SudoknSwissMachiningCapability {
    string rdfs_label  
}
SudoknSwissTurningCapability {
    string rdfs_label  
}
SudoknTI-9000Certificate {

}
SudoknTI9000Certificate {
    string rdfs_label  
}
SudoknTICertificate {

}
SudoknTIGWeldingCapability {
    string rdfs_label  
}
SudoknTantalumProcessingCapability {
    string rdfs_label  
}
SudoknTappingCapability {
    string rdfs_label  
}
SudoknTeflonProcessingCapability {
    string rdfs_label  
}
SudoknTextileProcessCapability {

}
SudoknTextiles {
    string rdfs_label  
}
SudoknTextilesIndustry {
    string rdfs_label  
}
SudoknThermaJoiningCapability {
    string rdfs_label  
}
SudoknThermalCoatingCapability {
    string rdfs_label  
}
SudoknThermalSubtractionCapability {

}
SudoknThermalWeldingCapability {
    string rdfs_label  
}
SudoknThermoformingCapability {
    string rdfs_label  
}
SudoknTinProcessingCapability {
    string rdfs_label  
}
SudoknTitaniumProcessingCapability {
    string rdfs_label  
}
SudoknToolDesignCapability {

}
SudoknToolMakingCapability {
    string rdfs_label  
}
SudoknTorchBrazingCapability {
    string rdfs_label  
}
SudoknTorchCuttingCapability {

}
SudoknTransportationAndWarehousing {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknTransportationIndustry {
    string rdfs_label  
}
SudoknTubeBendingCapability {
    string rdfs_label  
}
SudoknTubeFormingCapability {
    string rdfs_label  
}
SudoknTubingCapability {
    string rdfs_label  
}
SudoknTungstenProcessingCapability {
    string rdfs_label  
}
SudoknTurningCapability {
    string rdfs_label  
}
SudoknTurretPunchingCapability {
    string rdfs_label  
}
SudoknTwoDimensionalCartesianSpatialCoordinateDatum {
    uri sudokn_hasLatitudeValue  
    string sudokn_hasLatitudeValue  
    uri sudokn_hasLongitudeValue  
    string sudokn_hasLongitudeValue  
}
SudoknUSPostalCode {
    string sudokn_hasIntegerValue  
}
SudoknUltrasonicWeldingCapability {
    string rdfs_label  
}
SudoknUnitedStatesPostalCode {

}
SudoknUrethaneProcessingCapability {
    string rdfs_label  
}
SudoknUtilities {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknUtilitiesIndustry {
    string rdfs_label  
}
SudoknVacuumCastingCapability {
    string rdfs_label  
}
SudoknVacuumFormingCapability {
    string rdfs_label  
}
SudoknVacuumHardeningCapability {
    string rdfs_label  
}
SudoknVacuumPackagingCapability {
    string rdfs_label  
}
SudoknVaporizedMetalCoatingCapability {
    string rdfs_label  
}
SudoknVerticalMillingCapability {
    string rdfs_label  
}
SudoknVitualLocationIdentifier {

}
SudoknWarehousingAndStorageIndustry {
    string rdfs_label  
}
SudoknWaspaloyProcessingCapability {
    string rdfs_label  
}
SudoknWaterAndSewerUtilitiesIndustry {
    string rdfs_label  
}
SudoknWaterJetCuttingCapability {
    string rdfs_label  
}
SudoknWaterandSewerUtilitiesIndustry {
    string rdfs_label  
}
SudoknWaterjetCuttimgCapability {
    string rdfs_label  
}
SudoknWaterjetCuttingCapability {
    string rdfs_label  
}
SudoknWeavingCapability {

}
SudoknWebAddress {

}
SudoknWeldingCapability {
    string rdfs_label  
}
SudoknWetPaintingCapability {
    string rdfs_label  
}
SudoknWholesaleTrade {
    uri sudokn_hasNAICSCodeValue  
    integer sudokn_hasNAICSCodeValue  
    uri sudokn_hasNAICSTextValue  
    string sudokn_hasNAICSTextValue  
}
SudoknWireBendingCapability {
    string rdfs_label  
}
SudoknWireEDMCapability {
    string rdfs_label  
}
SudoknWireFormingCapability {
    string rdfs_label  
}
SudoknWireHarnessAssemblyCapability {
    string rdfs_label  
}
SudoknWiringCapability {
    string rdfs_label  
}
SudoknWoodProcessingCapability {
    string rdfs_label  
}
SudoknWoodProductManufacturingIndustry {
    string rdfs_label  
}
SudoknWoodWorkingCapability {
    string rdfs_label  
}
SudoknWoodworkingCapability {
    string rdfs_label  
}
SudoknZincAlloyProcessingCapability {
    string rdfs_label  
}
SudoknZincArcSprayCapability {
    string rdfs_label  
}
SudoknZincProcessingCapability {
    string rdfs_label  
}
SudoknZirconProcessingCapability {
    string rdfs_label  
}
SudoknOrganizationSize {

}

IoManufacturer ||--|o OwlNamedIndividual : "sudokn_hasManagementCapability"
IoManufacturer ||--|o SudoknQualityManagementCapability : "sudokn_hasManagementCapability"
IoManufacturer ||--|o OwlNamedIndividual : "sudokn_hasName"
IoManufacturer ||--|o SudoknOrganizationName : "sudokn_hasName"
IoManufacturer ||--|o OwlNamedIndividual : "sudokn_hasWebAddress"
IoManufacturer ||--|o SudoknWebAddress : "sudokn_hasWebAddress"
IoManufacturer ||--|o OwlNamedIndividual : "sudokn_hasEmailAddress"
IoManufacturer ||--|o SudoknEmailAddress : "sudokn_hasEmailAddress"
IoManufacturer ||--|o SudoknCenterlessGrindingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknElectronBeamWeldingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknLiveToolingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknInductionHeatingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknRoboticWeldingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknDeepFreezingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknLaserCuttingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknRamEDMCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCNCCuttingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCNCTurningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknAssemblyCapibility : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPLCProgrammingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknElectolessNickelPlatingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknHoningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPlasticMachiningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknEDMCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCNCmillingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknLatheWorkCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPulsedElectrochemicalMachiningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCNCVerticalMillingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknTubingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknSwissMachiningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknNickelPlatingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknVacuumFormingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPlasmaSprayingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknRivettingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknSanitaryWeldingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknZincArcSprayCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknMoldingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCNCMillingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknWaterjetCuttimgCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknSheetMetalFormingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknMachineBuildingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknEndFormingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknSandBlastingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknSmeltingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknGrindingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknDieCastingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknMediaBlastingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknWaterjetCuttingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCylindricalGrindingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknWireFormingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknFixtureDesignCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknElectricalDischargeMachiningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCustomFoamCuttingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknWireEDMCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknFixturingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknHardeningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o Sudokn3DPrintingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPackagingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknReverseEngineeringCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknKnittingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknWaterJetCuttingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknRollingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknExtrusionCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknAssemblyCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknMechanicalJoiningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknNotchingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknBroachingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknFormingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknNitridingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknGalvanizingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknMetalStampingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCarburizingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknFabricatingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknMetalFabricationCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCNCLaserCuttingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknMIGWeldingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPemInsertionCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknElectropolishingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknAnnealingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknLaserProcessingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknEtchingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPaintingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknVacuumPackagingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknMillingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknScreenPrintingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknContinuousCastingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknVacuumCastingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknThermoformingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCNCLatheCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCoatingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknWoodworkingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCADCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknChemicalProcessingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknSurfaceFinishingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknMetalworkingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknSurfacePreparationCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPunchingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCNCPressBrakeCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknTappingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknWiringCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPackingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCreepFeedGrindingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknToolMakingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCNCMachiningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknMachiningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o Sudokn2-AxisCNCTurningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPhosphateCoatingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknAddtiveManufacturingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknExtrudingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCNCCylindricalGrindingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPlatingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknResistanceWeldingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknTurningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknKittingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknTubeFormingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknStampingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknWetPaintingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknFinishingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknInvestmentCastingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPolishingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknVacuumHardeningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknRAMEdmCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknSteelManufacturingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknEmbossingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknDrawingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPassivationCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCNCGrindingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknLaserWeldingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCerakoteCoatingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPrintingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknBendingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknHarperizingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknForgingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknRivetingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknRapidPrototypingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknProductDesignCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPipingFabricationCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknSwissTurningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknBrassBlackeningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknHeatTreatingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknChemicalCoatingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknWireBendingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknSinteringCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPressingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknBrazingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknSolderingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknFlameSprayingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPressBrakingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknWeldingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknFasteningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCentrifugalCastingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCuttingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknSilkScreeningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCNCWireBendingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknMigWeldingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknShearingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknSewingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknEngineeringDesignCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknVerticalMillingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknWireHarnessAssemblyCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknMetalSpinningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o OwlNamedIndividual : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCeramicMoldCastingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknAdditiveManufacturingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknSandCastingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknWoodWorkingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknInstallationCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknSpotWeldingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknChromateConversionCoatingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknMoldMakingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPhysicalVaporDepositionCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknElectrolessNickelPlatingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknElectrolessPlatingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknHorizontalMillingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknMechanicalAssemblyCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknDieMakingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPrototypeManufacturingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPlasmaCuttingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCarbonitridingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknOxy-FuelCuttingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknDigitalPrintingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknDrillingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCNCPlasmaCuttingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknDeepHoleDrillingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknHotDipGalvanizingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknAbrasiveCleaningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknDeburringCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknSpinningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknLiquidCoatingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknAnodizingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknAcrylicFabricationCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPolycrystallineDiamondMachiningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPlaningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknVaporizedMetalCoatingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknBlackOxideCoatingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknReamingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknMIGWeldinCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknSurfaceGrindingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknBoringCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCastingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknSheetMetalProcessingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknShrinkFittingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknTIGWeldingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknSinkerEdmCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknShapingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknKnurlingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknElectroplatingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknElectroPlatingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPowderCoatingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknSheetMetalFabricationCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknFillingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknTurretPunchingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknOilGroovingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknTubeBendingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCNCFormingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPlasterMoldCastingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknGearCuttingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCNCBendingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPermanentMoldCastingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknLaserEtchingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknChemicalCleaningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknPrototypingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknSinkerEDMCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknShellMoldCastingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknFabricationCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknFiberOpticLaserCuttingCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknCNCHorizontalTurningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o SudoknJoiningCapability : "sudokn_hasProcessCapability"
IoManufacturer ||--|o OwlNamedIndividual : "sudokn_hasPostalAddress"
IoManufacturer ||--|o SudoknPostalAddress : "sudokn_hasPostalAddress"
IoManufacturer ||--|o SudoknUnitedStatesPostalCode : "sudokn_hasPostalAddress"
IoManufacturer ||--|o SudoknNAICS332116 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332618 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332913 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332321 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332722 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332991 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332811 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332813 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332212 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332510 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332312 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332420 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332213 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332997 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332410 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332612 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332995 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332611 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332211 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332912 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332999 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332812 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332998 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332311 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332112 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332919 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332117 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332322 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332710 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332439 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332115 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332114 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332431 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICSClassifier : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332111 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332992 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332721 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332994 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332911 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332214 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332323 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332996 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknNAICS332313 : "sudokn_hasPrimaryNAICSClassifier"
IoManufacturer ||--|o SudoknGeospatialLocation : "sudokn_organizationLocatedIn"
IoManufacturer ||--|o SudoknNAICSClassifier : "sudokn_hasSecondaryNAICSClassifier"
IoManufacturer ||--|o SudoknMetalProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknTeflonProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknZirconProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknTinProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknColdRolledSteelProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknCopperProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknTungstenProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknKovarProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknPhosBronzeProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknGraphiteProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknPlasticProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknAlloySteelProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknSiliconeProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknAcetalProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknMolybdenumProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknInvarProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknWoodProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknPlatinumProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknPreciousMaterialProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknDifficultToMachineMaterialsProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknPolycarbonateProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknZincProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknPhosphorBronzeProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknBronzeProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknSteelProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknUrethaneProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknInconelProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknStainlessSteelProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknRubberProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknHastelloyProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknExoticMaterialProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknZincAlloyProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknWaspaloyProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknExtremelyHardMaterialProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknBrassProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknGoldProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknChromiumProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknIronProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknKaptonProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknNomexProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknGlassProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknFoamProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknManMadeFiberProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknHighGradeAluminumProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknLeadProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknAluminumProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknPalladiumProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknCompositeProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknCeramicProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknNylonProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknCarbideProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknChemicalsProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknNaturalFiberProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknTantalumProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknMagnesiumProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknSilverProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o OwlNamedIndividual : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknLexanProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknTitaniumProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknSpecialMaterialsProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknCobaltProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknBerylliumProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknNickelProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknSteelAlloyProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknLowAlloySteelProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknDelrinProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o SudoknCarbonGraphiteProcessingCapability : "sudokn_hasMaterialCapability"
IoManufacturer ||--|o IoMaterialProduct : "sudokn_manufactures"
IoManufacturer ||--|o SudoknFDACertificate : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknHAACPCertificate : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknISO9000 : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknITARCompliant : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknIATF16949Certificate : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknQS9000Certificate : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknISO14001Certificate : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknASME : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknFDAGMPCompliant : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknISO14000Certificate : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknISO9001 : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknISO9000Certificate : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknBABACertificate : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknISO13485Certificate : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknAS9100 : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknISO9001Certificate : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknISTS16949Certificate : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknIS-TS16949 : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknLEEDCertificate : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknTI9000Certificate : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknNADCAPCertificate : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknAWSWelderCertificate : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknAS9100Certificate : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknISOCertificate : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknBritishRetailConsortiumAccreditation : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknITARCertificate : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknQS9000 : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknAS9102Certificate : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknNADCAPAC7004 : "sudokn_hasCertificate"
IoManufacturer ||--|o OwlNamedIndividual : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknASMECertificate : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknAS9000Certificate : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknISO13485 : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknISO14001 : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknKOSHERApproved : "sudokn_hasCertificate"
IoManufacturer ||--|o SudoknElectronicAutomotiveInudstry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknHealthCareServicesIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknIndustrialMachineryandEquipmentIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknWaterandSewerUtilitiesIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknRetailTradeIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknEducationIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknAutomotiveIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknOffshoreWindIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknPaperIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknConstructionIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknCommunicationandElectronicPowerUtilitiesIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknPrintingAndInformationIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknConsumerGoods : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknElectronicProductIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknProfessionalServicesIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknMiningIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknComputersandElectronicProductsIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknWoodProductManufacturingIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknAgricultureIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknWarehousingAndStorageIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknSportsAndLeisureIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknConsumerGoodsIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknOilAndGasIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknBusinessEquipmentIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknTextiles : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknRetailIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknPaperandPaperboardProductsIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknTransportationIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknHealthcareServicesIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknGovernmentIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknUtilitiesIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknRecyclingIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknSportsandLeisureIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknFoodIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknPlasticAndRubberIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknTextilesIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknApparelIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknEducationalInstitutionsIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknAerospaceIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknGovermentIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknMachinaryAndEquipmentIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o OwlNamedIndividual : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknMetalProductionIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknMetalsProductsIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknPlasticsandRubberProductsIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknChemicalAndPetrochemicalIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknElectricVehiclesIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknMilitaryIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknFurnitureIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o SudoknCommunicationIndustry : "sudokn_suppliesToIndustry"
IoManufacturer ||--|o OwlNamedIndividual : "sudokn_hasNAICSClassifier"
IoManufacturer ||--|o SudoknNAICSClassifier : "sudokn_hasNAICSClassifier"
IoManufacturer ||--|o OwlNamedIndividual : "sudokn_hasOwnershipStatusClassifier"
IoManufacturer ||--|o SudoknOwnershipStatusClassifier : "sudokn_hasOwnershipStatusClassifier"
OwlNamedIndividual ||--|o OwlNamedIndividual : "sudokn_hasManagementCapability"
OwlNamedIndividual ||--|o SudoknQualityManagementCapability : "sudokn_hasManagementCapability"
OwlNamedIndividual ||--|o OwlNamedIndividual : "sudokn_hasName"
OwlNamedIndividual ||--|o SudoknOrganizationName : "sudokn_hasName"
OwlNamedIndividual ||--|o OwlNamedIndividual : "sudokn_hasWebAddress"
OwlNamedIndividual ||--|o SudoknWebAddress : "sudokn_hasWebAddress"
OwlNamedIndividual ||--|o OwlNamedIndividual : "sudokn_hasEmailAddress"
OwlNamedIndividual ||--|o SudoknEmailAddress : "sudokn_hasEmailAddress"
OwlNamedIndividual ||--|o SudoknCenterlessGrindingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknElectronBeamWeldingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknLiveToolingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknInductionHeatingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknRoboticWeldingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknDeepFreezingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknLaserCuttingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknRamEDMCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCNCCuttingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCNCTurningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknAssemblyCapibility : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPLCProgrammingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknElectolessNickelPlatingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknHoningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPlasticMachiningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknEDMCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCNCmillingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknLatheWorkCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPulsedElectrochemicalMachiningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCNCVerticalMillingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknTubingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknSwissMachiningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknNickelPlatingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknVacuumFormingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPlasmaSprayingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknRivettingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknSanitaryWeldingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknZincArcSprayCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknMoldingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCNCMillingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknWaterjetCuttimgCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknSheetMetalFormingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknMachineBuildingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknEndFormingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknSandBlastingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknSmeltingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknGrindingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknDieCastingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknMediaBlastingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknWaterjetCuttingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCylindricalGrindingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknWireFormingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknFixtureDesignCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknElectricalDischargeMachiningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCustomFoamCuttingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknWireEDMCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknFixturingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknHardeningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o Sudokn3DPrintingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPackagingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknReverseEngineeringCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknKnittingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknWaterJetCuttingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknRollingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknExtrusionCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknAssemblyCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknMechanicalJoiningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknNotchingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknBroachingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknFormingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknNitridingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknGalvanizingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknMetalStampingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCarburizingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknFabricatingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknMetalFabricationCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCNCLaserCuttingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknMIGWeldingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPemInsertionCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknElectropolishingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknAnnealingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknLaserProcessingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknEtchingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPaintingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknVacuumPackagingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknMillingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknScreenPrintingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknContinuousCastingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknVacuumCastingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknThermoformingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCNCLatheCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCoatingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknWoodworkingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCADCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknChemicalProcessingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknSurfaceFinishingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknMetalworkingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknSurfacePreparationCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPunchingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCNCPressBrakeCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknTappingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknWiringCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPackingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCreepFeedGrindingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknToolMakingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCNCMachiningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknMachiningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o Sudokn2-AxisCNCTurningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPhosphateCoatingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknAddtiveManufacturingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknExtrudingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCNCCylindricalGrindingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPlatingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknResistanceWeldingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknTurningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknKittingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknTubeFormingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknStampingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknWetPaintingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknFinishingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknInvestmentCastingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPolishingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknVacuumHardeningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknRAMEdmCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknSteelManufacturingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknEmbossingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknDrawingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPassivationCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCNCGrindingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknLaserWeldingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCerakoteCoatingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPrintingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknBendingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknHarperizingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknForgingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknRivetingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknRapidPrototypingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknProductDesignCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPipingFabricationCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknSwissTurningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknBrassBlackeningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknHeatTreatingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknChemicalCoatingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknWireBendingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknSinteringCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPressingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknBrazingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknSolderingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknFlameSprayingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPressBrakingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknWeldingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknFasteningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCentrifugalCastingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCuttingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknSilkScreeningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCNCWireBendingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknMigWeldingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknShearingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknSewingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknEngineeringDesignCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknVerticalMillingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknWireHarnessAssemblyCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknMetalSpinningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o OwlNamedIndividual : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCeramicMoldCastingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknAdditiveManufacturingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknSandCastingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknWoodWorkingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknInstallationCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknSpotWeldingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknChromateConversionCoatingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknMoldMakingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPhysicalVaporDepositionCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknElectrolessNickelPlatingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknElectrolessPlatingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknHorizontalMillingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknMechanicalAssemblyCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknDieMakingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPrototypeManufacturingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPlasmaCuttingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCarbonitridingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknOxy-FuelCuttingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknDigitalPrintingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknDrillingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCNCPlasmaCuttingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknDeepHoleDrillingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknHotDipGalvanizingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknAbrasiveCleaningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknDeburringCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknSpinningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknLiquidCoatingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknAnodizingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknAcrylicFabricationCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPolycrystallineDiamondMachiningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPlaningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknVaporizedMetalCoatingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknBlackOxideCoatingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknReamingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknMIGWeldinCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknSurfaceGrindingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknBoringCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCastingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknSheetMetalProcessingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknShrinkFittingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknTIGWeldingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknSinkerEdmCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknShapingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknKnurlingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknElectroplatingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknElectroPlatingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPowderCoatingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknSheetMetalFabricationCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknFillingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknTurretPunchingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknOilGroovingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknTubeBendingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCNCFormingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPlasterMoldCastingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknGearCuttingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCNCBendingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPermanentMoldCastingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknLaserEtchingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknChemicalCleaningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknPrototypingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknSinkerEDMCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknShellMoldCastingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknFabricationCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknFiberOpticLaserCuttingCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknCNCHorizontalTurningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o SudoknJoiningCapability : "sudokn_hasProcessCapability"
OwlNamedIndividual ||--|o OwlNamedIndividual : "sudokn_attestsTo"
OwlNamedIndividual ||--|o SudoknQualityManagementCapability : "sudokn_attestsTo"
OwlNamedIndividual ||--|o OwlNamedIndividual : "sudokn_hasPostalAddress"
OwlNamedIndividual ||--|o SudoknPostalAddress : "sudokn_hasPostalAddress"
OwlNamedIndividual ||--|o SudoknUnitedStatesPostalCode : "sudokn_hasPostalAddress"
OwlNamedIndividual ||--|o SudoknMetalProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknTeflonProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknZirconProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknTinProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknColdRolledSteelProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknCopperProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknTungstenProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknKovarProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknPhosBronzeProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknGraphiteProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknPlasticProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknAlloySteelProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknSiliconeProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknAcetalProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknMolybdenumProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknInvarProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknWoodProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknPlatinumProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknPreciousMaterialProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknDifficultToMachineMaterialsProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknPolycarbonateProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknZincProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknPhosphorBronzeProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknBronzeProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknSteelProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknUrethaneProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknInconelProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknStainlessSteelProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknRubberProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknHastelloyProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknExoticMaterialProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknZincAlloyProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknWaspaloyProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknExtremelyHardMaterialProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknBrassProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknGoldProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknChromiumProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknIronProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknKaptonProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknNomexProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknGlassProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknFoamProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknManMadeFiberProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknHighGradeAluminumProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknLeadProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknAluminumProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknPalladiumProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknCompositeProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknCeramicProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknNylonProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknCarbideProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknChemicalsProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknNaturalFiberProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknTantalumProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknMagnesiumProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknSilverProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o OwlNamedIndividual : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknLexanProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknTitaniumProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknSpecialMaterialsProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknCobaltProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknBerylliumProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknNickelProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknSteelAlloyProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknLowAlloySteelProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknDelrinProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o SudoknCarbonGraphiteProcessingCapability : "sudokn_hasMaterialCapability"
OwlNamedIndividual ||--|o OwlNamedIndividual : "sudokn_hasNAICSClassifier"
OwlNamedIndividual ||--|o SudoknNAICSClassifier : "sudokn_hasNAICSClassifier"
OwlNamedIndividual ||--|o SudoknFDACertificate : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknHAACPCertificate : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknISO9000 : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknITARCompliant : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknIATF16949Certificate : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknQS9000Certificate : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknISO14001Certificate : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknASME : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknFDAGMPCompliant : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknISO14000Certificate : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknISO9001 : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknISO9000Certificate : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknBABACertificate : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknISO13485Certificate : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknAS9100 : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknISO9001Certificate : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknISTS16949Certificate : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknIS-TS16949 : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknLEEDCertificate : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknTI9000Certificate : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknNADCAPCertificate : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknAWSWelderCertificate : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknAS9100Certificate : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknISOCertificate : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknBritishRetailConsortiumAccreditation : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknITARCertificate : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknQS9000 : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknAS9102Certificate : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknNADCAPAC7004 : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o OwlNamedIndividual : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknASMECertificate : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknAS9000Certificate : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknISO13485 : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknISO14001 : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknKOSHERApproved : "sudokn_hasCertificate"
OwlNamedIndividual ||--|o SudoknElectronicAutomotiveInudstry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknHealthCareServicesIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknIndustrialMachineryandEquipmentIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknWaterandSewerUtilitiesIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknRetailTradeIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknEducationIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknAutomotiveIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknOffshoreWindIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknPaperIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknConstructionIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknCommunicationandElectronicPowerUtilitiesIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknPrintingAndInformationIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknConsumerGoods : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknElectronicProductIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknProfessionalServicesIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknMiningIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknComputersandElectronicProductsIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknWoodProductManufacturingIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknAgricultureIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknWarehousingAndStorageIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknSportsAndLeisureIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknConsumerGoodsIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknOilAndGasIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknBusinessEquipmentIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknTextiles : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknRetailIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknPaperandPaperboardProductsIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknTransportationIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknHealthcareServicesIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknGovernmentIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknUtilitiesIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknRecyclingIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknSportsandLeisureIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknFoodIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknPlasticAndRubberIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknTextilesIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknApparelIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknEducationalInstitutionsIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknAerospaceIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknGovermentIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknMachinaryAndEquipmentIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o OwlNamedIndividual : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknMetalProductionIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknMetalsProductsIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknPlasticsandRubberProductsIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknChemicalAndPetrochemicalIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknElectricVehiclesIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknMilitaryIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknFurnitureIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o SudoknCommunicationIndustry : "sudokn_suppliesToIndustry"
OwlNamedIndividual ||--|o OwlNamedIndividual : "sudokn_hasOwnershipStatusClassifier"
OwlNamedIndividual ||--|o SudoknOwnershipStatusClassifier : "sudokn_hasOwnershipStatusClassifier"
SudoknAS9100Certificate ||--|o OwlNamedIndividual : "sudokn_attestsTo"
SudoknAS9100Certificate ||--|o SudoknQualityManagementCapability : "sudokn_attestsTo"
SudoknCity ||--|o SudoknState : "sudokn_locatedInState"
SudoknGeospatialLocation ||--|o SudoknUSPostalCode : "sudokn_hasZIPcode"
SudoknGeospatialLocation ||--|o SudoknTwoDimensionalCartesianSpatialCoordinateDatum : "sudokn_hasSpatialCoordinates"
SudoknGeospatialLocation ||--|o SudoknCity : "sudokn_locatedInCity"
SudoknGeospatialLocation ||--|o OwlNamedIndividual : "sudokn_hasPostalAddress"
SudoknGeospatialLocation ||--|o SudoknPostalAddress : "sudokn_hasPostalAddress"
SudoknGeospatialLocation ||--|o SudoknUnitedStatesPostalCode : "sudokn_hasPostalAddress"
SudoknISO9000Certificate ||--|o OwlNamedIndividual : "sudokn_attestsTo"
SudoknISO9000Certificate ||--|o SudoknQualityManagementCapability : "sudokn_attestsTo"

```



## Classes

| Class | Description | Occurrences |
| --- | --- | --- |
| [IoGroupOfPersons](classes/IoGroupOfPersons.md) | No class (type) description specified<br/>| 0 | 
| [IoIdentifier](classes/IoIdentifier.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknDesignativeName](classes/SudoknDesignativeName.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknBrandName](classes/SudoknBrandName.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknOrganizationName](classes/SudoknOrganizationName.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknVitualLocationIdentifier](classes/SudoknVitualLocationIdentifier.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknEmailAddress](classes/SudoknEmailAddress.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknWebAddress](classes/SudoknWebAddress.md) | No class (type) description specified<br/>| 1 | 
| [IoInformationContentEntity](classes/IoInformationContentEntity.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCertificate](classes/SudoknCertificate.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknQualityCertificate](classes/SudoknQualityCertificate.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknASCertificate](classes/SudoknASCertificate.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknAS9003Certificate](classes/SudoknAS9003Certificate.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknAS9100Certificate](classes/SudoknAS9100Certificate.md) | No class (type) description specified<br/>| 1220 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknAS9102Certificate](classes/SudoknAS9102Certificate.md) | No class (type) description specified<br/>| 9 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknASMECertificate](classes/SudoknASMECertificate.md) | No class (type) description specified<br/>| 804 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknBABACertificate](classes/SudoknBABACertificate.md) | No class (type) description specified<br/>| 3 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknBritishRetailConsortiumCertificate](classes/SudoknBritishRetailConsortiumCertificate.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknFDACertificate](classes/SudoknFDACertificate.md) | No class (type) description specified<br/>| 5 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknFDA-GMPCertificate](classes/SudoknFDA-GMPCertificate.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknFDA-PMACertificate](classes/SudoknFDA-PMACertificate.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknGWOCertificate](classes/SudoknGWOCertificate.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknHAACPCertificate](classes/SudoknHAACPCertificate.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknISOCertificate](classes/SudoknISOCertificate.md) | No class (type) description specified<br/>| 67 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknISO13485Certificate](classes/SudoknISO13485Certificate.md) | No class (type) description specified<br/>| 326 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknISO14000Certificate](classes/SudoknISO14000Certificate.md) | No class (type) description specified<br/>| 12 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknISO14001Certificate](classes/SudoknISO14001Certificate.md) | No class (type) description specified<br/>| 321 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknISO17265Certificate](classes/SudoknISO17265Certificate.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknISO27001Certificate](classes/SudoknISO27001Certificate.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknISO9000Certificate](classes/SudoknISO9000Certificate.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknISO9001Certificate](classes/SudoknISO9001Certificate.md) | No class (type) description specified<br/>| 3466 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknISTSCertificate](classes/SudoknISTSCertificate.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknISTS-16949Certificate](classes/SudoknISTS-16949Certificate.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknITARCertificate](classes/SudoknITARCertificate.md) | No class (type) description specified<br/>| 127 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknKosherApprovedCertificate](classes/SudoknKosherApprovedCertificate.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknNADCAPCertificate](classes/SudoknNADCAPCertificate.md) | No class (type) description specified<br/>| 467 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknNISTCertificate](classes/SudoknNISTCertificate.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknNIST-800-171Certificate](classes/SudoknNIST-800-171Certificate.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknQSCertificate](classes/SudoknQSCertificate.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknQS9000Certificate](classes/SudoknQS9000Certificate.md) | No class (type) description specified<br/>| 41 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknTICertificate](classes/SudoknTICertificate.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknTI-9000Certificate](classes/SudoknTI-9000Certificate.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknClassifier](classes/SudoknClassifier.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknNAICSClassifier](classes/SudoknNAICSClassifier.md) | No class (type) description specified<br/>| 23 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknAccommodationAndFoodServices](classes/SudoknAccommodationAndFoodServices.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknAdministrativeAndSupportAndWasteServices](classes/SudoknAdministrativeAndSupportAndWasteServices.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknAgricultureForestryFishingAndHunting](classes/SudoknAgricultureForestryFishingAndHunting.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknArtsEnterntainmentAndRecreation](classes/SudoknArtsEnterntainmentAndRecreation.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknConstruction](classes/SudoknConstruction.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknEducationalServices](classes/SudoknEducationalServices.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknFinanceAndInsurance](classes/SudoknFinanceAndInsurance.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknHealthcareAndSocialAssistance](classes/SudoknHealthcareAndSocialAssistance.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknInformation](classes/SudoknInformation.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknManagementOfCompaniesAndEnterprise](classes/SudoknManagementOfCompaniesAndEnterprise.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknManufacturing](classes/SudoknManufacturing.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknMining](classes/SudoknMining.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknProfessionalScientificAndTechnicalServices](classes/SudoknProfessionalScientificAndTechnicalServices.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknPublicAdministration](classes/SudoknPublicAdministration.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknRealEstateRentalAndLeasing](classes/SudoknRealEstateRentalAndLeasing.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknRetailTrade](classes/SudoknRetailTrade.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknTransportationAndWarehousing](classes/SudoknTransportationAndWarehousing.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknUtilities](classes/SudoknUtilities.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknWholesaleTrade](classes/SudoknWholesaleTrade.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknSpecialBusinessStatusClassifier](classes/SudoknSpecialBusinessStatusClassifier.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknOwnershipStatusClassifier](classes/SudoknOwnershipStatusClassifier.md) | No class (type) description specified<br/>| 8 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknTwoDimensionalCartesianSpatialCoordinateDatum](classes/SudoknTwoDimensionalCartesianSpatialCoordinateDatum.md) | No class (type) description specified<br/>| 20728 | 
| [IoManufacturer](classes/IoManufacturer.md) | No class (type) description specified<br/>| 11367 | 
| [IoMaterialProduct](classes/IoMaterialProduct.md) | No class (type) description specified<br/>| 44818 | 
| [IoPhysicalLocationIdentifier](classes/IoPhysicalLocationIdentifier.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknBuildingNumber](classes/SudoknBuildingNumber.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCityOfAddress](classes/SudoknCityOfAddress.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCountryOfAddress](classes/SudoknCountryOfAddress.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknPostalAddress](classes/SudoknPostalAddress.md) | No class (type) description specified<br/>| 20728 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknStateOfAddress](classes/SudoknStateOfAddress.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknStreetAddress](classes/SudoknStreetAddress.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknUnitedStatesPostalCode](classes/SudoknUnitedStatesPostalCode.md) | No class (type) description specified<br/>| 1 | 
| [IoscIndustry](classes/IoscIndustry.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknAerospaceIndustry](classes/SudoknAerospaceIndustry.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknAgricultureIndustry](classes/SudoknAgricultureIndustry.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknApparelIndustry](classes/SudoknApparelIndustry.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknAutomotiveIndustry](classes/SudoknAutomotiveIndustry.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknElectricAutomotiveIndustry](classes/SudoknElectricAutomotiveIndustry.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknBusinessEquipmentIndustry](classes/SudoknBusinessEquipmentIndustry.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCommunicationsIndustry](classes/SudoknCommunicationsIndustry.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknConstructionIndustry](classes/SudoknConstructionIndustry.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknConsumerGoodsIndustry](classes/SudoknConsumerGoodsIndustry.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknEducationIndustry](classes/SudoknEducationIndustry.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknElectronicProductIndustry](classes/SudoknElectronicProductIndustry.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknComputerIndustry](classes/SudoknComputerIndustry.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknFoodIndustry](classes/SudoknFoodIndustry.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknBeverageIndustry](classes/SudoknBeverageIndustry.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknRestaurantIndustry](classes/SudoknRestaurantIndustry.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknFurnitureIndustry](classes/SudoknFurnitureIndustry.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknGovernmentIndustry](classes/SudoknGovernmentIndustry.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknHealthcareServices](classes/SudoknHealthcareServices.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknMachinaryAndEquipmentIndustry](classes/SudoknMachinaryAndEquipmentIndustry.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknMetalProductsIndustry](classes/SudoknMetalProductsIndustry.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknMilitaryIndustry](classes/SudoknMilitaryIndustry.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknMiningIndustry](classes/SudoknMiningIndustry.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknOffshoreWindIndustry](classes/SudoknOffshoreWindIndustry.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknPaperIndustry](classes/SudoknPaperIndustry.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknPaperboardProductsIndustry](classes/SudoknPaperboardProductsIndustry.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknPlasticAndRubberIndustry](classes/SudoknPlasticAndRubberIndustry.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknPrintingAndInformationIndustry](classes/SudoknPrintingAndInformationIndustry.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknProfessionalServices](classes/SudoknProfessionalServices.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknRecyclingIndustry](classes/SudoknRecyclingIndustry.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknRetailIndustry](classes/SudoknRetailIndustry.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknSportsAndLeisureIndustry](classes/SudoknSportsAndLeisureIndustry.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknTextilesIndustry](classes/SudoknTextilesIndustry.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknTransportationIndustry](classes/SudoknTransportationIndustry.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknUtilitiesIndustry](classes/SudoknUtilitiesIndustry.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCommunicationAndElectronicPowerUtilitiesIndustry](classes/SudoknCommunicationAndElectronicPowerUtilitiesIndustry.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknWaterAndSewerUtilitiesIndustry](classes/SudoknWaterAndSewerUtilitiesIndustry.md) | No class (type) description specified<br/>| 0 | 
| [IoscProductionCapability](classes/IoscProductionCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknEngineeringCapability](classes/SudoknEngineeringCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCADCAMCapability](classes/SudoknCADCAMCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCADCapability](classes/SudoknCADCapability.md) | No class (type) description specified<br/>| 3 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCAECapability](classes/SudoknCAECapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknEngineeringDesignCapability](classes/SudoknEngineeringDesignCapability.md) | No class (type) description specified<br/>| 28 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknPLCProgrammingCapability](classes/SudoknPLCProgrammingCapability.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknReverseEngineeringCapability](classes/SudoknReverseEngineeringCapability.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknToolDesignCapability](classes/SudoknToolDesignCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknDieDesignCapability](classes/SudoknDieDesignCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknFixtureDesignCapability](classes/SudoknFixtureDesignCapability.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknManufacturingProcessCapability](classes/SudoknManufacturingProcessCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknAssemblyCapibility](classes/SudoknAssemblyCapibility.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknFabricatingCapability](classes/SudoknFabricatingCapability.md) | No class (type) description specified<br/>| 2518 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknKittingCapability](classes/SudoknKittingCapability.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknWireHarnessAssemblyCapability](classes/SudoknWireHarnessAssemblyCapability.md) | No class (type) description specified<br/>| 23 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCastingCapability](classes/SudoknCastingCapability.md) | No class (type) description specified<br/>| 1195 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknFinishingCapability](classes/SudoknFinishingCapability.md) | No class (type) description specified<br/>| 1615 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCoatingCapability](classes/SudoknCoatingCapability.md) | No class (type) description specified<br/>| 1744 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknBlackOxideCoatingCapability](classes/SudoknBlackOxideCoatingCapability.md) | No class (type) description specified<br/>| 228 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknChemicalCoatingCapability](classes/SudoknChemicalCoatingCapability.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknElectroPlatingCapability](classes/SudoknElectroPlatingCapability.md) | No class (type) description specified<br/>| 1339 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknElectrolessNickelPlating](classes/SudoknElectrolessNickelPlating.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknGalvanizingCapability](classes/SudoknGalvanizingCapability.md) | No class (type) description specified<br/>| 72 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknMechanicalCoatingCapability](classes/SudoknMechanicalCoatingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknPowderCoatingCapability](classes/SudoknPowderCoatingCapability.md) | No class (type) description specified<br/>| 679 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknPhosphateCoatingCapability](classes/SudoknPhosphateCoatingCapability.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknPrintingCapability](classes/SudoknPrintingCapability.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknWetPaintingCapability](classes/SudoknWetPaintingCapability.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknThermalCoatingCapability](classes/SudoknThermalCoatingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknVaporizedMetalCoatingCapability](classes/SudoknVaporizedMetalCoatingCapability.md) | No class (type) description specified<br/>| 13 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknPhysicalVaporDepositionCapability](classes/SudoknPhysicalVaporDepositionCapability.md) | No class (type) description specified<br/>| 10 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknSurfacePreparationCapability](classes/SudoknSurfacePreparationCapability.md) | No class (type) description specified<br/>| 550 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknBeltSandingCapability](classes/SudoknBeltSandingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknSandBlastingCapability](classes/SudoknSandBlastingCapability.md) | No class (type) description specified<br/>| 340 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknShotPeeningCapability](classes/SudoknShotPeeningCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknForgingCapability](classes/SudoknForgingCapability.md) | No class (type) description specified<br/>| 609 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknFormingCapability](classes/SudoknFormingCapability.md) | No class (type) description specified<br/>| 1802 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknDrawingCapability](classes/SudoknDrawingCapability.md) | No class (type) description specified<br/>| 1449 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknExtrudingCapability](classes/SudoknExtrudingCapability.md) | No class (type) description specified<br/>| 602 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknRollingCapability](classes/SudoknRollingCapability.md) | No class (type) description specified<br/>| 605 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknHeatTreatingCapability](classes/SudoknHeatTreatingCapability.md) | No class (type) description specified<br/>| 923 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknHardeningCapability](classes/SudoknHardeningCapability.md) | No class (type) description specified<br/>| 269 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknSurfaceHardeningCapability](classes/SudoknSurfaceHardeningCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknDiffusionHardeningCapability](classes/SudoknDiffusionHardeningCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCarburizingCapability](classes/SudoknCarburizingCapability.md) | No class (type) description specified<br/>| 81 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknNitridingCapability](classes/SudoknNitridingCapability.md) | No class (type) description specified<br/>| 45 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknVacuumHardeningCapability](classes/SudoknVacuumHardeningCapability.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknJoiningCapability](classes/SudoknJoiningCapability.md) | No class (type) description specified<br/>| 437 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknMechanicalJoiningCapability](classes/SudoknMechanicalJoiningCapability.md) | No class (type) description specified<br/>| 3 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknMechanicalWeldingCapability](classes/SudoknMechanicalWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknExplosiveWeldingCapability](classes/SudoknExplosiveWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknFrictionWeldingCapability](classes/SudoknFrictionWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknPressureWeldingCapability](classes/SudoknPressureWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknUltrasonicWeldingCapability](classes/SudoknUltrasonicWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknRivetingCapability](classes/SudoknRivetingCapability.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknThermaJoiningCapability](classes/SudoknThermaJoiningCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknBrazingCapability](classes/SudoknBrazingCapability.md) | No class (type) description specified<br/>| 147 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknDipBrazingCapability](classes/SudoknDipBrazingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknFurnaceBrazingCapability](classes/SudoknFurnaceBrazingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknInductionBrazingCapability](classes/SudoknInductionBrazingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknInfraredBrazingCapability](classes/SudoknInfraredBrazingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknResistanceBrazingCapability](classes/SudoknResistanceBrazingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknTorchBrazingCapability](classes/SudoknTorchBrazingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknSolderingCapability](classes/SudoknSolderingCapability.md) | No class (type) description specified<br/>| 271 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknThermalWeldingCapability](classes/SudoknThermalWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknBrazeWeldingCapability](classes/SudoknBrazeWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCarbonArcBrazingCapability](classes/SudoknCarbonArcBrazingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknGasBrazingCapability](classes/SudoknGasBrazingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknDiffusionBondingCapability](classes/SudoknDiffusionBondingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknElectricalResistanceWeldingCapability](classes/SudoknElectricalResistanceWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknButtWeldingCapability](classes/SudoknButtWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknElectroSlagWeldingCapability](classes/SudoknElectroSlagWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknPercussionWeldingCapability](classes/SudoknPercussionWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknProjectionWeldingCapability](classes/SudoknProjectionWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknSeamWeldingCapability](classes/SudoknSeamWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknSpotWeldingCapability](classes/SudoknSpotWeldingCapability.md) | No class (type) description specified<br/>| 3 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknElectricArcWeldingCapability](classes/SudoknElectricArcWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCarbonArcWeldingCapability](classes/SudoknCarbonArcWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknGasMetalArcWeldingCapability](classes/SudoknGasMetalArcWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknMIGWeldingCapability](classes/SudoknMIGWeldingCapability.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknGasTungstenArcWeldingCapability](classes/SudoknGasTungstenArcWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknTIGWeldingCapability](classes/SudoknTIGWeldingCapability.md) | No class (type) description specified<br/>| 3 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknShieldedMetalArcWeldingCapability](classes/SudoknShieldedMetalArcWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknStudWeldingCapability](classes/SudoknStudWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknSubmergedArcWeldingCapability](classes/SudoknSubmergedArcWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknGasWeldingCapability](classes/SudoknGasWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknAtomicHydrogenWeldingCapability](classes/SudoknAtomicHydrogenWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCombustableGasWeldingCapability](classes/SudoknCombustableGasWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknHighEnergyBeamWeldingCapability](classes/SudoknHighEnergyBeamWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknElectronBeamWeldingCapability](classes/SudoknElectronBeamWeldingCapability.md) | No class (type) description specified<br/>| 6 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknLaserBeamWeldingCapability](classes/SudoknLaserBeamWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknPlasmaArcWeldingCapability](classes/SudoknPlasmaArcWeldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknMachiningCapability](classes/SudoknMachiningCapability.md) | No class (type) description specified<br/>| 3494 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknAbrassiveMachiningCapability](classes/SudoknAbrassiveMachiningCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknGrindingCapability](classes/SudoknGrindingCapability.md) | No class (type) description specified<br/>| 1654 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCenterlessGrindingCapability](classes/SudoknCenterlessGrindingCapability.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknClyndricalGrindingCapability](classes/SudoknClyndricalGrindingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCNCClyndricalGrindingCapability](classes/SudoknCNCClyndricalGrindingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknHoningCapability](classes/SudoknHoningCapability.md) | No class (type) description specified<br/>| 460 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCNCMachiningCapability](classes/SudoknCNCMachiningCapability.md) | No class (type) description specified<br/>| 1427 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknMultiPointCuttingCapability](classes/SudoknMultiPointCuttingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknBroachingCapability](classes/SudoknBroachingCapability.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknGearCuttingCapability](classes/SudoknGearCuttingCapability.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknGearHobbingCapability](classes/SudoknGearHobbingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknHoleMakingCapability](classes/SudoknHoleMakingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCounterBoringCapability](classes/SudoknCounterBoringCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCounterSinkingCapability](classes/SudoknCounterSinkingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknDrillingCapability](classes/SudoknDrillingCapability.md) | No class (type) description specified<br/>| 1361 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknDeepHoleDrillingCapability](classes/SudoknDeepHoleDrillingCapability.md) | No class (type) description specified<br/>| 81 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknReamingCapability](classes/SudoknReamingCapability.md) | No class (type) description specified<br/>| 278 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknTappingCapability](classes/SudoknTappingCapability.md) | No class (type) description specified<br/>| 860 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknMillingCapability](classes/SudoknMillingCapability.md) | No class (type) description specified<br/>| 2311 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCNCMillingCapability](classes/SudoknCNCMillingCapability.md) | No class (type) description specified<br/>| 1105 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknHorizontalMillingCapability](classes/SudoknHorizontalMillingCapability.md) | No class (type) description specified<br/>| 181 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknSlabMillingCapability](classes/SudoknSlabMillingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknVerticalMillingCapability](classes/SudoknVerticalMillingCapability.md) | No class (type) description specified<br/>| 437 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknEndMillingCapability](classes/SudoknEndMillingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknFaceMillingCapability](classes/SudoknFaceMillingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknSawingCapability](classes/SudoknSawingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknSinglePointCuttingCapability](classes/SudoknSinglePointCuttingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknPlaningCapability](classes/SudoknPlaningCapability.md) | No class (type) description specified<br/>| 17 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknShapingCapability](classes/SudoknShapingCapability.md) | No class (type) description specified<br/>| 504 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknTurningCapability](classes/SudoknTurningCapability.md) | No class (type) description specified<br/>| 2077 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCNCTurningCapability](classes/SudoknCNCTurningCapability.md) | No class (type) description specified<br/>| 16 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknMoldingCapability](classes/SudoknMoldingCapability.md) | No class (type) description specified<br/>| 644 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknInjectionMoldingCapability](classes/SudoknInjectionMoldingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknPackingCapability](classes/SudoknPackingCapability.md) | No class (type) description specified<br/>| 1765 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknSheetMetalProcessingCapability](classes/SudoknSheetMetalProcessingCapability.md) | No class (type) description specified<br/>| 28 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknBendingCapability](classes/SudoknBendingCapability.md) | No class (type) description specified<br/>| 945 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknWireBendingCapability](classes/SudoknWireBendingCapability.md) | No class (type) description specified<br/>| 3 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknEmbossingCapability](classes/SudoknEmbossingCapability.md) | No class (type) description specified<br/>| 69 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknPunchingCapability](classes/SudoknPunchingCapability.md) | No class (type) description specified<br/>| 7 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknSheeringCapability](classes/SudoknSheeringCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknSpinningCapability](classes/SudoknSpinningCapability.md) | No class (type) description specified<br/>| 38 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknStampingCapability](classes/SudoknStampingCapability.md) | No class (type) description specified<br/>| 1216 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknStretchFormingCapability](classes/SudoknStretchFormingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknTextileProcessCapability](classes/SudoknTextileProcessCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCrochetCapability](classes/SudoknCrochetCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknDyeingCapability](classes/SudoknDyeingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknKnittingCapability](classes/SudoknKnittingCapability.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknWeavingCapability](classes/SudoknWeavingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknThermalSubtractionCapability](classes/SudoknThermalSubtractionCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknEDMCapability](classes/SudoknEDMCapability.md) | No class (type) description specified<br/>| 1114 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknHoleDrillingEDMCapability](classes/SudoknHoleDrillingEDMCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknRAMEDMCapability](classes/SudoknRAMEDMCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknSinkerEDMCapability](classes/SudoknSinkerEDMCapability.md) | No class (type) description specified<br/>| 148 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknWireEDMCapability](classes/SudoknWireEDMCapability.md) | No class (type) description specified<br/>| 644 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknHighEnergyBeamMachiningCapability](classes/SudoknHighEnergyBeamMachiningCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknLaserCuttingCapability](classes/SudoknLaserCuttingCapability.md) | No class (type) description specified<br/>| 581 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCNCLaserCuttingCapability](classes/SudoknCNCLaserCuttingCapability.md) | No class (type) description specified<br/>| 1 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknTorchCuttingCapability](classes/SudoknTorchCuttingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknPlasmaCuttingCapability](classes/SudoknPlasmaCuttingCapability.md) | No class (type) description specified<br/>| 235 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknToolMakingCapability](classes/SudoknToolMakingCapability.md) | No class (type) description specified<br/>| 6 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknMoldMakingCapability](classes/SudoknMoldMakingCapability.md) | No class (type) description specified<br/>| 8 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknWoodWorkingCapability](classes/SudoknWoodWorkingCapability.md) | No class (type) description specified<br/>| 12 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknMaterialProcessingCapability](classes/SudoknMaterialProcessingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCarbonProcessingCapability](classes/SudoknCarbonProcessingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCeramicProcessingCapability](classes/SudoknCeramicProcessingCapability.md) | No class (type) description specified<br/>| 1051 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknChemicalsProcessingCapability](classes/SudoknChemicalsProcessingCapability.md) | No class (type) description specified<br/>| 1344 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCompositeProcessingCapability](classes/SudoknCompositeProcessingCapability.md) | No class (type) description specified<br/>| 1196 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknElectronicProcessingCapability](classes/SudoknElectronicProcessingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknFiberProcessingCapability](classes/SudoknFiberProcessingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknManMadeFiberProcessingCapability](classes/SudoknManMadeFiberProcessingCapability.md) | No class (type) description specified<br/>| 2 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknNaturalFiberProcessingCapability](classes/SudoknNaturalFiberProcessingCapability.md) | No class (type) description specified<br/>| 15 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknFoamProcessingCapability](classes/SudoknFoamProcessingCapability.md) | No class (type) description specified<br/>| 1065 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknGlassProcessingCapability](classes/SudoknGlassProcessingCapability.md) | No class (type) description specified<br/>| 2866 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknMetalProcessingCapability](classes/SudoknMetalProcessingCapability.md) | No class (type) description specified<br/>| 6560 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknAluminumProcessingCapability](classes/SudoknAluminumProcessingCapability.md) | No class (type) description specified<br/>| 5647 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknBrassProcessingCapability](classes/SudoknBrassProcessingCapability.md) | No class (type) description specified<br/>| 2596 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknBronzeProcessingCapability](classes/SudoknBronzeProcessingCapability.md) | No class (type) description specified<br/>| 1754 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCopperProcessingCapability](classes/SudoknCopperProcessingCapability.md) | No class (type) description specified<br/>| 2784 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknIronProcessingCapability](classes/SudoknIronProcessingCapability.md) | No class (type) description specified<br/>| 5903 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknMagnesiumAlloyProcessingCapability](classes/SudoknMagnesiumAlloyProcessingCapability.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknSteelProcessingCapability](classes/SudoknSteelProcessingCapability.md) | No class (type) description specified<br/>| 7200 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknStainlessSteelProcessingCapability](classes/SudoknStainlessSteelProcessingCapability.md) | No class (type) description specified<br/>| 4796 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknTitaniumProcessingCapability](classes/SudoknTitaniumProcessingCapability.md) | No class (type) description specified<br/>| 1349 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknZincAlloyProcessingCapability](classes/SudoknZincAlloyProcessingCapability.md) | No class (type) description specified<br/>| 80 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknPlasticProcessingCapability](classes/SudoknPlasticProcessingCapability.md) | No class (type) description specified<br/>| 4159 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknRubberProcessingCapability](classes/SudoknRubberProcessingCapability.md) | No class (type) description specified<br/>| 1830 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknSiliconeProcessingCapability](classes/SudoknSiliconeProcessingCapability.md) | No class (type) description specified<br/>| 690 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknUrethaneProcessingCapability](classes/SudoknUrethaneProcessingCapability.md) | No class (type) description specified<br/>| 1039 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknWoodProcessingCapability](classes/SudoknWoodProcessingCapability.md) | No class (type) description specified<br/>| 2918 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknQualityManagementCapability](classes/SudoknQualityManagementCapability.md) | No class (type) description specified<br/>| 1 | 
| [OboBFO0000019](classes/OboBFO0000019.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknOrganizationSize](classes/SudoknOrganizationSize.md) | No class (type) description specified<br/>| 1 | 
| [OboBFO0000029](classes/OboBFO0000029.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknGeopoliticalSite](classes/SudoknGeopoliticalSite.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCity](classes/SudoknCity.md) | No class (type) description specified<br/>| 2994 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCountry](classes/SudoknCountry.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknCounty](classes/SudoknCounty.md) | No class (type) description specified<br/>| 0 | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[SudoknState](classes/SudoknState.md) | No class (type) description specified<br/>| 129 | 
| [OwlAllDisjointClasses](classes/OwlAllDisjointClasses.md) | No class (type) description specified<br/>| 14 | 
| [OwlNamedIndividual](classes/OwlNamedIndividual.md) | No class (type) description specified<br/>| 29 | 
| [Sudokn2-AxisCNCTurningCapability](classes/Sudokn2-AxisCNCTurningCapability.md) | No class (type) description specified<br/>| 1 | 
| [Sudokn3DPrintingCapability](classes/Sudokn3DPrintingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknAbrasiveCleaningCapability](classes/SudoknAbrasiveCleaningCapability.md) | No class (type) description specified<br/>| 9 | 
| [SudoknAcetalProcessingCapability](classes/SudoknAcetalProcessingCapability.md) | No class (type) description specified<br/>| 362 | 
| [SudoknAcrylicFabricationCapability](classes/SudoknAcrylicFabricationCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknAdditiveManufacturingCapability](classes/SudoknAdditiveManufacturingCapability.md) | No class (type) description specified<br/>| 209 | 
| [SudoknAddtiveManufacturingCapability](classes/SudoknAddtiveManufacturingCapability.md) | No class (type) description specified<br/>| 337 | 
| [SudoknAlloySteelProcessingCapability](classes/SudoknAlloySteelProcessingCapability.md) | No class (type) description specified<br/>| 825 | 
| [SudoknAnnealingCapability](classes/SudoknAnnealingCapability.md) | No class (type) description specified<br/>| 99 | 
| [SudoknAnodizingCapability](classes/SudoknAnodizingCapability.md) | No class (type) description specified<br/>| 659 | 
| [SudoknAS9000Certificate](classes/SudoknAS9000Certificate.md) | No class (type) description specified<br/>| 5 | 
| [SudoknAS9100](classes/SudoknAS9100.md) | No class (type) description specified<br/>| 20 | 
| [SudoknASME](classes/SudoknASME.md) | No class (type) description specified<br/>| 10 | 
| [SudoknAssemblyCapability](classes/SudoknAssemblyCapability.md) | No class (type) description specified<br/>| 2931 | 
| [SudoknAWSWelderCertificate](classes/SudoknAWSWelderCertificate.md) | No class (type) description specified<br/>| 48 | 
| [SudoknBerylliumProcessingCapability](classes/SudoknBerylliumProcessingCapability.md) | No class (type) description specified<br/>| 360 | 
| [SudoknBoringCapability](classes/SudoknBoringCapability.md) | No class (type) description specified<br/>| 857 | 
| [SudoknBrassBlackeningCapability](classes/SudoknBrassBlackeningCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknBritishRetailConsortiumAccreditation](classes/SudoknBritishRetailConsortiumAccreditation.md) | No class (type) description specified<br/>| 1 | 
| [SudoknCarbideProcessingCapability](classes/SudoknCarbideProcessingCapability.md) | No class (type) description specified<br/>| 786 | 
| [SudoknCarbonGraphiteProcessingCapability](classes/SudoknCarbonGraphiteProcessingCapability.md) | No class (type) description specified<br/>| 13 | 
| [SudoknCarbonitridingCapability](classes/SudoknCarbonitridingCapability.md) | No class (type) description specified<br/>| 43 | 
| [SudoknCentrifugalCastingCapability](classes/SudoknCentrifugalCastingCapability.md) | No class (type) description specified<br/>| 17 | 
| [SudoknCerakoteCoatingCapability](classes/SudoknCerakoteCoatingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknCeramicMoldCastingCapability](classes/SudoknCeramicMoldCastingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknChemicalAndPetrochemicalIndustry](classes/SudoknChemicalAndPetrochemicalIndustry.md) | No class (type) description specified<br/>| 1 | 
| [SudoknChemicalCleaningCapability](classes/SudoknChemicalCleaningCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknChemicalProcessingCapability](classes/SudoknChemicalProcessingCapability.md) | No class (type) description specified<br/>| 194 | 
| [SudoknChromateConversionCoatingCapability](classes/SudoknChromateConversionCoatingCapability.md) | No class (type) description specified<br/>| 139 | 
| [SudoknChromiumProcessingCapability](classes/SudoknChromiumProcessingCapability.md) | No class (type) description specified<br/>| 551 | 
| [SudoknCNCBendingCapability](classes/SudoknCNCBendingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknCNCCuttingCapability](classes/SudoknCNCCuttingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknCNCCylindricalGrindingCapability](classes/SudoknCNCCylindricalGrindingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknCNCFormingCapability](classes/SudoknCNCFormingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknCNCGrindingCapability](classes/SudoknCNCGrindingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknCNCHorizontalTurningCapability](classes/SudoknCNCHorizontalTurningCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknCNCLatheCapability](classes/SudoknCNCLatheCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknCNCmillingCapability](classes/SudoknCNCmillingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknCNCPlasmaCuttingCapability](classes/SudoknCNCPlasmaCuttingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknCNCPressBrakeCapability](classes/SudoknCNCPressBrakeCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknCNCVerticalMillingCapability](classes/SudoknCNCVerticalMillingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknCNCWireBendingCapability](classes/SudoknCNCWireBendingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknCobaltProcessingCapability](classes/SudoknCobaltProcessingCapability.md) | No class (type) description specified<br/>| 303 | 
| [SudoknColdRolledSteelProcessingCapability](classes/SudoknColdRolledSteelProcessingCapability.md) | No class (type) description specified<br/>| 252 | 
| [SudoknCommunicationandElectronicPowerUtilitiesIndustry](classes/SudoknCommunicationandElectronicPowerUtilitiesIndustry.md) | No class (type) description specified<br/>| 1 | 
| [SudoknCommunicationIndustry](classes/SudoknCommunicationIndustry.md) | No class (type) description specified<br/>| 2 | 
| [SudoknComputersandElectronicProductsIndustry](classes/SudoknComputersandElectronicProductsIndustry.md) | No class (type) description specified<br/>| 1 | 
| [SudoknConsumerGoods](classes/SudoknConsumerGoods.md) | No class (type) description specified<br/>| 1 | 
| [SudoknContinuousCastingCapability](classes/SudoknContinuousCastingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknCreepFeedGrindingCapability](classes/SudoknCreepFeedGrindingCapability.md) | No class (type) description specified<br/>| 8 | 
| [SudoknCustomFoamCuttingCapability](classes/SudoknCustomFoamCuttingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknCuttingCapability](classes/SudoknCuttingCapability.md) | No class (type) description specified<br/>| 19 | 
| [SudoknCylindricalGrindingCapability](classes/SudoknCylindricalGrindingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknDeburringCapability](classes/SudoknDeburringCapability.md) | No class (type) description specified<br/>| 86 | 
| [SudoknDeepFreezingCapability](classes/SudoknDeepFreezingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknDelrinProcessingCapability](classes/SudoknDelrinProcessingCapability.md) | No class (type) description specified<br/>| 289 | 
| [SudoknDieCastingCapability](classes/SudoknDieCastingCapability.md) | No class (type) description specified<br/>| 220 | 
| [SudoknDieMakingCapability](classes/SudoknDieMakingCapability.md) | No class (type) description specified<br/>| 6 | 
| [SudoknDifficultToMachineMaterialsProcessingCapability](classes/SudoknDifficultToMachineMaterialsProcessingCapability.md) | No class (type) description specified<br/>| 28 | 
| [SudoknDigitalPrintingCapability](classes/SudoknDigitalPrintingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknEducationalInstitutionsIndustry](classes/SudoknEducationalInstitutionsIndustry.md) | No class (type) description specified<br/>| 1 | 
| [SudoknElectolessNickelPlatingCapability](classes/SudoknElectolessNickelPlatingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknElectricalDischargeMachiningCapability](classes/SudoknElectricalDischargeMachiningCapability.md) | No class (type) description specified<br/>| 197 | 
| [SudoknElectricVehiclesIndustry](classes/SudoknElectricVehiclesIndustry.md) | No class (type) description specified<br/>| 1 | 
| [SudoknElectrolessNickelPlatingCapability](classes/SudoknElectrolessNickelPlatingCapability.md) | No class (type) description specified<br/>| 214 | 
| [SudoknElectrolessPlatingCapability](classes/SudoknElectrolessPlatingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknElectronicAutomotiveInudstry](classes/SudoknElectronicAutomotiveInudstry.md) | No class (type) description specified<br/>| 1 | 
| [SudoknElectroplatingCapability](classes/SudoknElectroplatingCapability.md) | No class (type) description specified<br/>| 3 | 
| [SudoknElectropolishingCapability](classes/SudoknElectropolishingCapability.md) | No class (type) description specified<br/>| 61 | 
| [SudoknEndFormingCapability](classes/SudoknEndFormingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknEtchingCapability](classes/SudoknEtchingCapability.md) | No class (type) description specified<br/>| 487 | 
| [SudoknExoticMaterialProcessingCapability](classes/SudoknExoticMaterialProcessingCapability.md) | No class (type) description specified<br/>| 317 | 
| [SudoknExtremelyHardMaterialProcessingCapability](classes/SudoknExtremelyHardMaterialProcessingCapability.md) | No class (type) description specified<br/>| 12 | 
| [SudoknExtrusionCapability](classes/SudoknExtrusionCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknFabricationCapability](classes/SudoknFabricationCapability.md) | No class (type) description specified<br/>| 121 | 
| [SudoknFasteningCapability](classes/SudoknFasteningCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknFDAGMPCompliant](classes/SudoknFDAGMPCompliant.md) | No class (type) description specified<br/>| 2 | 
| [SudoknFiberOpticLaserCuttingCapability](classes/SudoknFiberOpticLaserCuttingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknFillingCapability](classes/SudoknFillingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknFixturingCapability](classes/SudoknFixturingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknFlameSprayingCapability](classes/SudoknFlameSprayingCapability.md) | No class (type) description specified<br/>| 6 | 
| [SudoknGeospatialLocation](classes/SudoknGeospatialLocation.md) | No class (type) description specified<br/>| 20728 | 
| [SudoknGoldProcessingCapability](classes/SudoknGoldProcessingCapability.md) | No class (type) description specified<br/>| 1302 | 
| [SudoknGovermentIndustry](classes/SudoknGovermentIndustry.md) | No class (type) description specified<br/>| 1 | 
| [SudoknGraphiteProcessingCapability](classes/SudoknGraphiteProcessingCapability.md) | No class (type) description specified<br/>| 472 | 
| [SudoknHarperizingCapability](classes/SudoknHarperizingCapability.md) | No class (type) description specified<br/>| 2 | 
| [SudoknHastelloyProcessingCapability](classes/SudoknHastelloyProcessingCapability.md) | No class (type) description specified<br/>| 321 | 
| [SudoknHealthcareServicesIndustry](classes/SudoknHealthcareServicesIndustry.md) | No class (type) description specified<br/>| 1 | 
| [SudoknHealthCareServicesIndustry](classes/SudoknHealthCareServicesIndustry.md) | No class (type) description specified<br/>| 1 | 
| [SudoknHighGradeAluminumProcessingCapability](classes/SudoknHighGradeAluminumProcessingCapability.md) | No class (type) description specified<br/>| 5 | 
| [SudoknHotDipGalvanizingCapability](classes/SudoknHotDipGalvanizingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknIATF16949Certificate](classes/SudoknIATF16949Certificate.md) | No class (type) description specified<br/>| 330 | 
| [SudoknInconelProcessingCapability](classes/SudoknInconelProcessingCapability.md) | No class (type) description specified<br/>| 906 | 
| [SudoknInductionHeatingCapability](classes/SudoknInductionHeatingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknIndustrialMachineryandEquipmentIndustry](classes/SudoknIndustrialMachineryandEquipmentIndustry.md) | No class (type) description specified<br/>| 1 | 
| [SudoknIndustry](classes/SudoknIndustry.md) | No class (type) description specified<br/>| 1 | 
| [SudoknInstallationCapability](classes/SudoknInstallationCapability.md) | No class (type) description specified<br/>| 2 | 
| [SudoknInvarProcessingCapability](classes/SudoknInvarProcessingCapability.md) | No class (type) description specified<br/>| 219 | 
| [SudoknInvestmentCastingCapability](classes/SudoknInvestmentCastingCapability.md) | No class (type) description specified<br/>| 83 | 
| [SudoknIS-TS16949](classes/SudoknIS-TS16949.md) | No class (type) description specified<br/>| 6 | 
| [SudoknISO13485](classes/SudoknISO13485.md) | No class (type) description specified<br/>| 1 | 
| [SudoknISO14001](classes/SudoknISO14001.md) | No class (type) description specified<br/>| 7 | 
| [SudoknISO9000](classes/SudoknISO9000.md) | No class (type) description specified<br/>| 31 | 
| [SudoknISO9001](classes/SudoknISO9001.md) | No class (type) description specified<br/>| 82 | 
| [SudoknISTS16949Certificate](classes/SudoknISTS16949Certificate.md) | No class (type) description specified<br/>| 4 | 
| [SudoknITARCompliant](classes/SudoknITARCompliant.md) | No class (type) description specified<br/>| 8 | 
| [SudoknKaptonProcessingCapability](classes/SudoknKaptonProcessingCapability.md) | No class (type) description specified<br/>| 32 | 
| [SudoknKnurlingCapability](classes/SudoknKnurlingCapability.md) | No class (type) description specified<br/>| 64 | 
| [SudoknKOSHERApproved](classes/SudoknKOSHERApproved.md) | No class (type) description specified<br/>| 1 | 
| [SudoknKovarProcessingCapability](classes/SudoknKovarProcessingCapability.md) | No class (type) description specified<br/>| 197 | 
| [SudoknLaserEtchingCapability](classes/SudoknLaserEtchingCapability.md) | No class (type) description specified<br/>| 81 | 
| [SudoknLaserProcessingCapability](classes/SudoknLaserProcessingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknLaserWeldingCapability](classes/SudoknLaserWeldingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknLatheWorkCapability](classes/SudoknLatheWorkCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknLeadProcessingCapability](classes/SudoknLeadProcessingCapability.md) | No class (type) description specified<br/>| 2484 | 
| [SudoknLEEDCertificate](classes/SudoknLEEDCertificate.md) | No class (type) description specified<br/>| 1 | 
| [SudoknLexanProcessingCapability](classes/SudoknLexanProcessingCapability.md) | No class (type) description specified<br/>| 461 | 
| [SudoknLiquidCoatingCapability](classes/SudoknLiquidCoatingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknLiveToolingCapability](classes/SudoknLiveToolingCapability.md) | No class (type) description specified<br/>| 287 | 
| [SudoknLowAlloySteelProcessingCapability](classes/SudoknLowAlloySteelProcessingCapability.md) | No class (type) description specified<br/>| 120 | 
| [SudoknMachineBuildingCapability](classes/SudoknMachineBuildingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknMagnesiumProcessingCapability](classes/SudoknMagnesiumProcessingCapability.md) | No class (type) description specified<br/>| 419 | 
| [SudoknMechanicalAssemblyCapability](classes/SudoknMechanicalAssemblyCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknMediaBlastingCapability](classes/SudoknMediaBlastingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknMetalFabricationCapability](classes/SudoknMetalFabricationCapability.md) | No class (type) description specified<br/>| 6 | 
| [SudoknMetalProductionIndustry](classes/SudoknMetalProductionIndustry.md) | No class (type) description specified<br/>| 1 | 
| [SudoknMetalSpinningCapability](classes/SudoknMetalSpinningCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknMetalsProductsIndustry](classes/SudoknMetalsProductsIndustry.md) | No class (type) description specified<br/>| 1 | 
| [SudoknMetalStampingCapability](classes/SudoknMetalStampingCapability.md) | No class (type) description specified<br/>| 2 | 
| [SudoknMetalworkingCapability](classes/SudoknMetalworkingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknMIGWeldinCapability](classes/SudoknMIGWeldinCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknMigWeldingCapability](classes/SudoknMigWeldingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknMolybdenumProcessingCapability](classes/SudoknMolybdenumProcessingCapability.md) | No class (type) description specified<br/>| 382 | 
| [SudoknNADCAPAC7004](classes/SudoknNADCAPAC7004.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332111](classes/SudoknNAICS332111.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332112](classes/SudoknNAICS332112.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332114](classes/SudoknNAICS332114.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332115](classes/SudoknNAICS332115.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332116](classes/SudoknNAICS332116.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332117](classes/SudoknNAICS332117.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332211](classes/SudoknNAICS332211.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332212](classes/SudoknNAICS332212.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332213](classes/SudoknNAICS332213.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332214](classes/SudoknNAICS332214.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332311](classes/SudoknNAICS332311.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332312](classes/SudoknNAICS332312.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332313](classes/SudoknNAICS332313.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332321](classes/SudoknNAICS332321.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332322](classes/SudoknNAICS332322.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332323](classes/SudoknNAICS332323.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332410](classes/SudoknNAICS332410.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332420](classes/SudoknNAICS332420.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332431](classes/SudoknNAICS332431.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332439](classes/SudoknNAICS332439.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332510](classes/SudoknNAICS332510.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332611](classes/SudoknNAICS332611.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332612](classes/SudoknNAICS332612.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332618](classes/SudoknNAICS332618.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332710](classes/SudoknNAICS332710.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332721](classes/SudoknNAICS332721.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332722](classes/SudoknNAICS332722.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332811](classes/SudoknNAICS332811.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332812](classes/SudoknNAICS332812.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332813](classes/SudoknNAICS332813.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332911](classes/SudoknNAICS332911.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332912](classes/SudoknNAICS332912.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332913](classes/SudoknNAICS332913.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332919](classes/SudoknNAICS332919.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332991](classes/SudoknNAICS332991.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332992](classes/SudoknNAICS332992.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332994](classes/SudoknNAICS332994.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332995](classes/SudoknNAICS332995.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332996](classes/SudoknNAICS332996.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332997](classes/SudoknNAICS332997.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332998](classes/SudoknNAICS332998.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNAICS332999](classes/SudoknNAICS332999.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNickelPlatingCapability](classes/SudoknNickelPlatingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknNickelProcessingCapability](classes/SudoknNickelProcessingCapability.md) | No class (type) description specified<br/>| 1603 | 
| [SudoknNomexProcessingCapability](classes/SudoknNomexProcessingCapability.md) | No class (type) description specified<br/>| 58 | 
| [SudoknNotchingCapability](classes/SudoknNotchingCapability.md) | No class (type) description specified<br/>| 109 | 
| [SudoknNylonProcessingCapability](classes/SudoknNylonProcessingCapability.md) | No class (type) description specified<br/>| 1177 | 
| [SudoknOilAndGasIndustry](classes/SudoknOilAndGasIndustry.md) | No class (type) description specified<br/>| 1 | 
| [SudoknOilGroovingCapability](classes/SudoknOilGroovingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknOxy-FuelCuttingCapability](classes/SudoknOxy-FuelCuttingCapability.md) | No class (type) description specified<br/>| 27 | 
| [SudoknPackagingCapability](classes/SudoknPackagingCapability.md) | No class (type) description specified<br/>| 3 | 
| [SudoknPaintingCapability](classes/SudoknPaintingCapability.md) | No class (type) description specified<br/>| 3 | 
| [SudoknPalladiumProcessingCapability](classes/SudoknPalladiumProcessingCapability.md) | No class (type) description specified<br/>| 78 | 
| [SudoknPaperandPaperboardProductsIndustry](classes/SudoknPaperandPaperboardProductsIndustry.md) | No class (type) description specified<br/>| 1 | 
| [SudoknPassivationCapability](classes/SudoknPassivationCapability.md) | No class (type) description specified<br/>| 280 | 
| [SudoknPemInsertionCapability](classes/SudoknPemInsertionCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknPermanentMoldCastingCapability](classes/SudoknPermanentMoldCastingCapability.md) | No class (type) description specified<br/>| 10 | 
| [SudoknPhosBronzeProcessingCapability](classes/SudoknPhosBronzeProcessingCapability.md) | No class (type) description specified<br/>| 12 | 
| [SudoknPhosphorBronzeProcessingCapability](classes/SudoknPhosphorBronzeProcessingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknPipingFabricationCapability](classes/SudoknPipingFabricationCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknPlasmaSprayingCapability](classes/SudoknPlasmaSprayingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknPlasterMoldCastingCapability](classes/SudoknPlasterMoldCastingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknPlasticMachiningCapability](classes/SudoknPlasticMachiningCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknPlasticsandRubberProductsIndustry](classes/SudoknPlasticsandRubberProductsIndustry.md) | No class (type) description specified<br/>| 1 | 
| [SudoknPlatingCapability](classes/SudoknPlatingCapability.md) | No class (type) description specified<br/>| 2 | 
| [SudoknPlatinumProcessingCapability](classes/SudoknPlatinumProcessingCapability.md) | No class (type) description specified<br/>| 225 | 
| [SudoknPolishingCapability](classes/SudoknPolishingCapability.md) | No class (type) description specified<br/>| 456 | 
| [SudoknPolycarbonateProcessingCapability](classes/SudoknPolycarbonateProcessingCapability.md) | No class (type) description specified<br/>| 693 | 
| [SudoknPolycrystallineDiamondMachiningCapability](classes/SudoknPolycrystallineDiamondMachiningCapability.md) | No class (type) description specified<br/>| 70 | 
| [SudoknPreciousMaterialProcessingCapability](classes/SudoknPreciousMaterialProcessingCapability.md) | No class (type) description specified<br/>| 6 | 
| [SudoknPressBrakingCapability](classes/SudoknPressBrakingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknPressingCapability](classes/SudoknPressingCapability.md) | No class (type) description specified<br/>| 6 | 
| [SudoknProductDesignCapability](classes/SudoknProductDesignCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknProfessionalServicesIndustry](classes/SudoknProfessionalServicesIndustry.md) | No class (type) description specified<br/>| 2 | 
| [SudoknPrototypeManufacturingCapability](classes/SudoknPrototypeManufacturingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknPrototypingCapability](classes/SudoknPrototypingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknPulsedElectrochemicalMachiningCapability](classes/SudoknPulsedElectrochemicalMachiningCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknQS9000](classes/SudoknQS9000.md) | No class (type) description specified<br/>| 1 | 
| [SudoknRamEDMCapability](classes/SudoknRamEDMCapability.md) | No class (type) description specified<br/>| 28 | 
| [SudoknRAMEdmCapability](classes/SudoknRAMEdmCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknRapidPrototypingCapability](classes/SudoknRapidPrototypingCapability.md) | No class (type) description specified<br/>| 256 | 
| [SudoknResistanceWeldingCapability](classes/SudoknResistanceWeldingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknRetailTradeIndustry](classes/SudoknRetailTradeIndustry.md) | No class (type) description specified<br/>| 1 | 
| [SudoknRivettingCapability](classes/SudoknRivettingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknRoboticWeldingCapability](classes/SudoknRoboticWeldingCapability.md) | No class (type) description specified<br/>| 2 | 
| [SudoknSandCastingCapability](classes/SudoknSandCastingCapability.md) | No class (type) description specified<br/>| 4 | 
| [SudoknSanitaryWeldingCapability](classes/SudoknSanitaryWeldingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknScreenPrintingCapability](classes/SudoknScreenPrintingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknSewingCapability](classes/SudoknSewingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknShearingCapability](classes/SudoknShearingCapability.md) | No class (type) description specified<br/>| 13 | 
| [SudoknSheetMetalFabricationCapability](classes/SudoknSheetMetalFabricationCapability.md) | No class (type) description specified<br/>| 5 | 
| [SudoknSheetMetalFormingCapability](classes/SudoknSheetMetalFormingCapability.md) | No class (type) description specified<br/>| 2 | 
| [SudoknShellMoldCastingCapability](classes/SudoknShellMoldCastingCapability.md) | No class (type) description specified<br/>| 2 | 
| [SudoknShrinkFittingCapability](classes/SudoknShrinkFittingCapability.md) | No class (type) description specified<br/>| 9 | 
| [SudoknSilkScreeningCapability](classes/SudoknSilkScreeningCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknSilverProcessingCapability](classes/SudoknSilverProcessingCapability.md) | No class (type) description specified<br/>| 1251 | 
| [SudoknSinkerEdmCapability](classes/SudoknSinkerEdmCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknSinteringCapability](classes/SudoknSinteringCapability.md) | No class (type) description specified<br/>| 56 | 
| [SudoknSmeltingCapability](classes/SudoknSmeltingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknSpecialMaterialsProcessingCapability](classes/SudoknSpecialMaterialsProcessingCapability.md) | No class (type) description specified<br/>| 71 | 
| [SudoknSportsandLeisureIndustry](classes/SudoknSportsandLeisureIndustry.md) | No class (type) description specified<br/>| 1 | 
| [SudoknSteelAlloyProcessingCapability](classes/SudoknSteelAlloyProcessingCapability.md) | No class (type) description specified<br/>| 365 | 
| [SudoknSteelManufacturingCapability](classes/SudoknSteelManufacturingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknSurfaceFinishingCapability](classes/SudoknSurfaceFinishingCapability.md) | No class (type) description specified<br/>| 76 | 
| [SudoknSurfaceGrindingCapability](classes/SudoknSurfaceGrindingCapability.md) | No class (type) description specified<br/>| 2 | 
| [SudoknSwissMachiningCapability](classes/SudoknSwissMachiningCapability.md) | No class (type) description specified<br/>| 19 | 
| [SudoknSwissTurningCapability](classes/SudoknSwissTurningCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknTantalumProcessingCapability](classes/SudoknTantalumProcessingCapability.md) | No class (type) description specified<br/>| 234 | 
| [SudoknTeflonProcessingCapability](classes/SudoknTeflonProcessingCapability.md) | No class (type) description specified<br/>| 538 | 
| [SudoknTextiles](classes/SudoknTextiles.md) | No class (type) description specified<br/>| 1 | 
| [SudoknThermoformingCapability](classes/SudoknThermoformingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknTI9000Certificate](classes/SudoknTI9000Certificate.md) | No class (type) description specified<br/>| 1 | 
| [SudoknTinProcessingCapability](classes/SudoknTinProcessingCapability.md) | No class (type) description specified<br/>| 417 | 
| [SudoknTubeBendingCapability](classes/SudoknTubeBendingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknTubeFormingCapability](classes/SudoknTubeFormingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknTubingCapability](classes/SudoknTubingCapability.md) | No class (type) description specified<br/>| 533 | 
| [SudoknTungstenProcessingCapability](classes/SudoknTungstenProcessingCapability.md) | No class (type) description specified<br/>| 820 | 
| [SudoknTurretPunchingCapability](classes/SudoknTurretPunchingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknUSPostalCode](classes/SudoknUSPostalCode.md) | No class (type) description specified<br/>| 20424 | 
| [SudoknVacuumCastingCapability](classes/SudoknVacuumCastingCapability.md) | No class (type) description specified<br/>| 16 | 
| [SudoknVacuumFormingCapability](classes/SudoknVacuumFormingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknVacuumPackagingCapability](classes/SudoknVacuumPackagingCapability.md) | No class (type) description specified<br/>| 2 | 
| [SudoknWarehousingAndStorageIndustry](classes/SudoknWarehousingAndStorageIndustry.md) | No class (type) description specified<br/>| 1 | 
| [SudoknWaspaloyProcessingCapability](classes/SudoknWaspaloyProcessingCapability.md) | No class (type) description specified<br/>| 66 | 
| [SudoknWaterandSewerUtilitiesIndustry](classes/SudoknWaterandSewerUtilitiesIndustry.md) | No class (type) description specified<br/>| 1 | 
| [SudoknWaterjetCuttimgCapability](classes/SudoknWaterjetCuttimgCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknWaterjetCuttingCapability](classes/SudoknWaterjetCuttingCapability.md) | No class (type) description specified<br/>| 373 | 
| [SudoknWaterJetCuttingCapability](classes/SudoknWaterJetCuttingCapability.md) | No class (type) description specified<br/>| 2 | 
| [SudoknWeldingCapability](classes/SudoknWeldingCapability.md) | No class (type) description specified<br/>| 2700 | 
| [SudoknWireFormingCapability](classes/SudoknWireFormingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknWiringCapability](classes/SudoknWiringCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknWoodProductManufacturingIndustry](classes/SudoknWoodProductManufacturingIndustry.md) | No class (type) description specified<br/>| 1 | 
| [SudoknWoodworkingCapability](classes/SudoknWoodworkingCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknZincArcSprayCapability](classes/SudoknZincArcSprayCapability.md) | No class (type) description specified<br/>| 1 | 
| [SudoknZincProcessingCapability](classes/SudoknZincProcessingCapability.md) | No class (type) description specified<br/>| 1266 | 
| [SudoknZirconProcessingCapability](classes/SudoknZirconProcessingCapability.md) | No class (type) description specified<br/>| 240 | 





## Slots

| Slot | Description | Occurrences |
| --- | --- | --- |
| [https___spec.industrialontologies.org_ontology_core_meta_AnnotationVocabulary_replacedBy](slots/https___spec.industrialontologies.org_ontology_core_meta_AnnotationVocabulary_replacedBy.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [iosc_hasTextValue](slots/iosc_hasTextValue.md) | No slot (predicate) description specified<br/>| 19102 |
| [owl_members](slots/owl_members.md) | No slot (predicate) description specified<br/>| 14 |
| [rdfs_label](slots/rdfs_label.md) | No slot (predicate) description specified<br/>| 198617 |
| [skos_altLabel](slots/skos_altLabel.md) | No slot (predicate) description specified<br/>| 1 |
| [sudokn_attestsTo](slots/sudokn_attestsTo.md) | No slot (predicate) description specified<br/>| 2 |
| [sudokn_hasAddressPart](slots/sudokn_hasAddressPart.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [sudokn_hasCertificate](slots/sudokn_hasCertificate.md) | No slot (predicate) description specified<br/>| 7430 |
| [sudokn_hasEmailAddress](slots/sudokn_hasEmailAddress.md) | No slot (predicate) description specified<br/>| 1 |
| [sudokn_hasIntegerValue](slots/sudokn_hasIntegerValue.md) | No slot (predicate) description specified<br/>| 18729 |
| [sudokn_hasLatitudeValue](slots/sudokn_hasLatitudeValue.md) | No slot (predicate) description specified<br/>| 19082 |
| [sudokn_hasLongitudeValue](slots/sudokn_hasLongitudeValue.md) | No slot (predicate) description specified<br/>| 19083 |
| [sudokn_hasManagementCapability](slots/sudokn_hasManagementCapability.md) | No slot (predicate) description specified<br/>| 1 |
| [sudokn_hasMaterialCapability](slots/sudokn_hasMaterialCapability.md) | No slot (predicate) description specified<br/>| 77383 |
| [sudokn_hasNAICSClassifier](slots/sudokn_hasNAICSClassifier.md) | No slot (predicate) description specified<br/>| 1 |
| [sudokn_hasNAICSCodeValue](slots/sudokn_hasNAICSCodeValue.md) | No slot (predicate) description specified<br/>| 64 |
| [sudokn_hasNAICSTextValue](slots/sudokn_hasNAICSTextValue.md) | No slot (predicate) description specified<br/>| 65 |
| [sudokn_hasName](slots/sudokn_hasName.md) | No slot (predicate) description specified<br/>| 1 |
| [sudokn_hasNumberOfEmployees](slots/sudokn_hasNumberOfEmployees.md) | No slot (predicate) description specified<br/>| 6931 |
| [sudokn_hasOrganizationYearOfEstablishment](slots/sudokn_hasOrganizationYearOfEstablishment.md) | No slot (predicate) description specified<br/>| 280 |
| [sudokn_hasOwnershipStatusClassifier](slots/sudokn_hasOwnershipStatusClassifier.md) | No slot (predicate) description specified<br/>| 1120 |
| [sudokn_hasPostalAddress](slots/sudokn_hasPostalAddress.md) | No slot (predicate) description specified<br/>| 20729 |
| [sudokn_hasPrimaryNAICSClassifier](slots/sudokn_hasPrimaryNAICSClassifier.md) | No slot (predicate) description specified<br/>| 6624 |
| [sudokn_hasPrimaryNIACSClassifier](slots/sudokn_hasPrimaryNIACSClassifier.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [sudokn_hasProcessCapability](slots/sudokn_hasProcessCapability.md) | No slot (predicate) description specified<br/>| 53953 |
| [sudokn_hasSecondaryNAICSClassifier](slots/sudokn_hasSecondaryNAICSClassifier.md) | No slot (predicate) description specified<br/>| 112 |
| [sudokn_hasSecondaryNIACSClassifier](slots/sudokn_hasSecondaryNIACSClassifier.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [sudokn_hasSpatialCoordinates](slots/sudokn_hasSpatialCoordinates.md) | No slot (predicate) description specified<br/>| 20728 |
| [sudokn_hasSpecialBusinessStatusClassifier](slots/sudokn_hasSpecialBusinessStatusClassifier.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [sudokn_hasWebAddress](slots/sudokn_hasWebAddress.md) | No slot (predicate) description specified<br/>| 1 |
| [sudokn_hasZIPcode](slots/sudokn_hasZIPcode.md) | No slot (predicate) description specified<br/>| 20424 |
| [sudokn_locatedInCity](slots/sudokn_locatedInCity.md) | No slot (predicate) description specified<br/>| 19022 |
| [sudokn_locatedInState](slots/sudokn_locatedInState.md) | No slot (predicate) description specified<br/>| 3734 |
| [sudokn_manufactures](slots/sudokn_manufactures.md) | No slot (predicate) description specified<br/>| 71660 |
| [sudokn_OrganizationLocatedIn](slots/sudokn_OrganizationLocatedIn.md) | No slot (predicate) description specified<br/>No occurrences of this slot in the graph.| 0 |
| [sudokn_organizationLocatedIn](slots/sudokn_organizationLocatedIn.md) | No slot (predicate) description specified<br/>| 20728 |
| [sudokn_suppliesToIndustry](slots/sudokn_suppliesToIndustry.md) | No slot (predicate) description specified<br/>| 26411 |









## IRI prefixes

* io: https://spec.industrialontologies.org/ontology/core/Core/
* iosc: https://spec.industrialontologies.org/ontology/supplychain/SupplyChain/
* linkml: https://w3id.org/linkml/
* obo: http://purl.obolibrary.org/obo/
* owl: http://www.w3.org/2002/07/owl#
* rdf: http://www.w3.org/1999/02/22-rdf-syntax-ns#
* rdfs: http://www.w3.org/2000/01/rdf-schema#
* skos: http://www.w3.org/2004/02/skos/core#
* sudokn: http://asu.edu/semantics/SUDOKN/
* xsd: http://www.w3.org/2001/XMLSchema#
* shex: http://www.w3.org/ns/shex#
* schema: http://schema.org/
