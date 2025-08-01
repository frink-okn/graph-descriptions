

# Class: No class (type) name specified (scales_CriminalCase)


_No class (type) description specified_






This class occurs 2368748 times.


URI: [scales:CriminalCase](http://schemas.scales-okn.org/rdf/scales#CriminalCase)






```mermaid
 classDiagram
    class ScalesCriminalCase
    click ScalesCriminalCase href "../ScalesCriminalCase"
      ScalesCriminalCase : http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge
        
          
    
    
    ScalesCriminalCase --> "0..1" HttpRelease.niem.govNiemDomainsJxdm7.2Charge : http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge
    click HttpRelease.niem.govNiemDomainsJxdm7.2Charge href "../HttpRelease.niem.govNiemDomainsJxdm7.2Charge"

        
      ScalesCriminalCase : http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt
    click Any href "../Any"

        
      ScalesCriminalCase : http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    click Any href "../Any"

        
      ScalesCriminalCase : http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    click Any href "../Any"

        
      ScalesCriminalCase : http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
    click Any href "../Any"

        
      ScalesCriminalCase : niem50_CaseDocketID
        
          
    
    
    ScalesCriminalCase --> "0..1" String : niem50_CaseDocketID
    click String href "../String"

        
      ScalesCriminalCase : niem50_CaseGeneralCategoryText
        
          
    
    
    ScalesCriminalCase --> "0..1" String : niem50_CaseGeneralCategoryText
    click String href "../String"

        
      ScalesCriminalCase : niem50_EndDate
        
          
    
    
    ScalesCriminalCase --> "0..1" Date : niem50_EndDate
    click Date href "../Date"

        
      ScalesCriminalCase : niem50_JurisdictionText
        
          
    
    
    ScalesCriminalCase --> "0..1" String : niem50_JurisdictionText
    click String href "../String"

        
      ScalesCriminalCase : niem50_StartDate
        
          
    
    
    ScalesCriminalCase --> "0..1" Date : niem50_StartDate
    click Date href "../Date"

        
      ScalesCriminalCase : niem50_StatusDescriptionText
        
          
    
    
    ScalesCriminalCase --> "0..1" String : niem50_StatusDescriptionText
    click String href "../String"

        
      ScalesCriminalCase : scales_DocketTable
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_DocketTable
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbAppcd
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbAppcd
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbAppdate
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbAppdate
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbCaslgky
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbCaslgky
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbCircuit
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCircuit
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCounty
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCounty
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCtdef
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCtdef
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCtfil
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCtfil
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCtfilr
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCtfilr
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCtfiltrn
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCtfiltrn
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCtfilwor
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCtfilwor
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCtpn
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCtpn
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCtpnwof
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCtpnwof
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCttr
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCttr
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCttrr
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCttrr
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCttrtrn
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCttrtrn
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbCttrwor
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbCttrwor
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbD2foffcd1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbD2foffcd1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbD2foffcd2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbD2foffcd2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbD2foffcd3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbD2foffcd3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbD2foffcd4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbD2foffcd4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbD2foffcd5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbD2foffcd5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbD2toffcd1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbD2toffcd1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbD2toffcd2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbD2toffcd2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbD2toffcd3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbD2toffcd3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbD2toffcd4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbD2toffcd4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbD2toffcd5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbD2toffcd5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbDeflgky
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbDeflgky
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbDefno
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbDefno
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbDisp1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbDisp1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbDisp2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbDisp2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbDisp3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbDisp3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbDisp4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbDisp4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbDisp5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbDisp5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbDispdate
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbDispdate
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbDistrict
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbDistrict
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbDocket
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbDocket
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFcounsel
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFcounsel
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFgenddate
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFgenddate
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFgstrtdate
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFgstrtdate
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFiledate
        
          
    
    
    ScalesCriminalCase --> "0..1" Datetime : scales_hasIdbFiledate
    click Datetime href "../Datetime"

        
      ScalesCriminalCase : scales_hasIdbFineamt1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFineamt1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFineamt2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFineamt2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFineamt3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFineamt3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFineamt4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFineamt4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFineamt5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFineamt5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFinetot
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFinetot
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFiscalyr
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFiscalyr
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFoffcd1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFoffcd1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFoffcd2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFoffcd2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFoffcd3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFoffcd3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFoffcd4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFoffcd4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFoffcd5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFoffcd5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFofflvl1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFofflvl1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFofflvl2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFofflvl2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFofflvl3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFofflvl3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFofflvl4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFofflvl4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFofflvl5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbFofflvl5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbFsev1
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFsev1
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFsev2
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFsev2
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFsev3
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFsev3
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFsev4
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbFsev4
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbFsev5
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbFsev5
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbFtitle1
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFtitle1
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFtitle2
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFtitle2
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFtitle3
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFtitle3
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFtitle4
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFtitle4
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFtitle5
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFtitle5
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbFugstat
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbFugstat
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbInt1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbInt1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbInt2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbInt2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbInt3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbInt3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbIs_stub
        
          
    
    
    ScalesCriminalCase --> "0..1" Boolean : scales_hasIdbIs_stub
    click Boolean href "../Boolean"

        
      ScalesCriminalCase : scales_hasIdbLoaddate
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbLoaddate
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbMagdef
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbMagdef
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbMagdock
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbMagdock
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbOffice
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbOffice
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbPriscd1
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbPriscd1
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbPriscd2
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbPriscd2
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbPriscd3
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbPriscd3
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbPriscd4
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbPriscd4
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbPriscd5
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbPriscd5
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbPristim1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbPristim1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbPristim2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbPristim2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbPristim3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbPristim3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbPristim4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbPristim4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbPristim5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbPristim5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbPristot
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbPristot
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbProbcd1
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbProbcd1
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbProbcd2
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbProbcd2
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbProbcd3
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbProbcd3
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbProbcd4
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbProbcd4
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbProbcd5
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbProbcd5
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbProbmon1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbProbmon1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbProbmon2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbProbmon2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbProbmon3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbProbmon3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbProbmon4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbProbmon4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbProbmon5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbProbmon5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbProbtot
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbProbtot
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbProccd
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbProccd
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbProcdate
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbProcdate
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbReopseq
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbReopseq
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbSentdate
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbSentdate
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbStatuscd
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbStatuscd
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbSupvrel1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbSupvrel1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbSupvrel2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbSupvrel2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbSupvrel3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbSupvrel3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbSupvrel4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbSupvrel4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbSupvrel5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbSupvrel5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTapeyear
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbTapeyear
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTcounsel
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbTcounsel
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTermdate
        
          
    
    
    ScalesCriminalCase --> "0..1" Datetime : scales_hasIdbTermdate
    click Datetime href "../Datetime"

        
      ScalesCriminalCase : scales_hasIdbTermoff
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbTermoff
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbToffcd1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbToffcd1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbToffcd2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbToffcd2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbToffcd3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbToffcd3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbToffcd4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbToffcd4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbToffcd5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbToffcd5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTofflvl1
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbTofflvl1
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTofflvl2
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbTofflvl2
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTofflvl3
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbTofflvl3
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTofflvl4
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbTofflvl4
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTofflvl5
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbTofflvl5
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTrandef
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbTrandef
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTrandist
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbTrandist
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbTrandock
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbTrandock
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasIdbTranoff
        
          
    
    
    ScalesCriminalCase --> "0..1" Integer : scales_hasIdbTranoff
    click Integer href "../Integer"

        
      ScalesCriminalCase : scales_hasIdbTsev1
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbTsev1
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbTsev2
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbTsev2
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbTsev3
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbTsev3
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbTsev4
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbTsev4
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbTsev5
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbTsev5
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbTtitle1
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbTtitle1
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbTtitle2
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbTtitle2
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbTtitle3
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbTtitle3
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbTtitle4
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbTtitle4
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbTtitle5
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbTtitle5
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbTypemag
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbTypemag
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbTypereg
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbTypereg
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbTypetrn
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasIdbTypetrn
    click Any href "../Any"

        
      ScalesCriminalCase : scales_hasIdbUpdate
        
          
    
    
    ScalesCriminalCase --> "0..1" String : scales_hasIdbUpdate
    click String href "../String"

        
      ScalesCriminalCase : scales_hasIdbVer
        
          
    
    
    ScalesCriminalCase --> "0..1" Double : scales_hasIdbVer
    click Double href "../Double"

        
      ScalesCriminalCase : scales_hasMemberCase
        
          
    
    
    ScalesCriminalCase --> "0..1" ScalesCivilCase : scales_hasMemberCase
    click ScalesCivilCase href "../ScalesCivilCase"

        
      ScalesCriminalCase : scales_hasRelatedCase
        
          
    
    
    ScalesCriminalCase --> "0..1" Any : scales_hasRelatedCase
    click Any href "../Any"

        
      ScalesCriminalCase : scales_Party
        
          
    
    
    ScalesCriminalCase --> "0..1" ScalesParty : scales_Party
    click ScalesParty href "../ScalesParty"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [scales_hasIdbTranoff](../slots/scales_hasIdbTranoff.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbPriscd3](../slots/scales_hasIdbPriscd3.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFiscalyr](../slots/scales_hasIdbFiscalyr.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFineamt4](../slots/scales_hasIdbFineamt4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTcounsel](../slots/scales_hasIdbTcounsel.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFcounsel](../slots/scales_hasIdbFcounsel.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbSentdate](../slots/scales_hasIdbSentdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTermoff](../slots/scales_hasIdbTermoff.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTapeyear](../slots/scales_hasIdbTapeyear.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTypemag](../slots/scales_hasIdbTypemag.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbD2toffcd2](../slots/scales_hasIdbD2toffcd2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbCaslgky](../slots/scales_hasIdbCaslgky.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbCtpnwof](../slots/scales_hasIdbCtpnwof.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [niem50_CaseDocketID](../slots/niem50_CaseDocketID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 2368748 |
| [scales_hasIdbProbmon4](../slots/scales_hasIdbProbmon4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbMagdef](../slots/scales_hasIdbMagdef.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFgstrtdate](../slots/scales_hasIdbFgstrtdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbCtpn](../slots/scales_hasIdbCtpn.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTsev3](../slots/scales_hasIdbTsev3.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFineamt3](../slots/scales_hasIdbFineamt3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTsev5](../slots/scales_hasIdbTsev5.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbDisp2](../slots/scales_hasIdbDisp2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbReopseq](../slots/scales_hasIdbReopseq.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbProbmon1](../slots/scales_hasIdbProbmon1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFtitle4](../slots/scales_hasIdbFtitle4.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFtitle2](../slots/scales_hasIdbFtitle2.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbDispdate](../slots/scales_hasIdbDispdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFineamt1](../slots/scales_hasIdbFineamt1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbProbcd1](../slots/scales_hasIdbProbcd1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbLoaddate](../slots/scales_hasIdbLoaddate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbPristim2](../slots/scales_hasIdbPristim2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbD2foffcd4](../slots/scales_hasIdbD2foffcd4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbSupvrel4](../slots/scales_hasIdbSupvrel4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFoffcd5](../slots/scales_hasIdbFoffcd5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [niem50_EndDate](../slots/niem50_EndDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) | No slot (predicate) description specified <br/>  | direct | 2204518 |
| [scales_hasIdbFoffcd3](../slots/scales_hasIdbFoffcd3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTermdate](../slots/scales_hasIdbTermdate.md) | 0..1 <br/> [xsd:dateTime](http://www.w3.org/2001/XMLSchema#dateTime) | No slot (predicate) description specified <br/>  | direct | 50408 |
| [scales_hasIdbProbmon2](../slots/scales_hasIdbProbmon2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbDocket](../slots/scales_hasIdbDocket.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFsev2](../slots/scales_hasIdbFsev2.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFtitle3](../slots/scales_hasIdbFtitle3.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTtitle3](../slots/scales_hasIdbTtitle3.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTypetrn](../slots/scales_hasIdbTypetrn.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTtitle2](../slots/scales_hasIdbTtitle2.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFtitle1](../slots/scales_hasIdbFtitle1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFgenddate](../slots/scales_hasIdbFgenddate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasMemberCase](../slots/scales_hasMemberCase.md) | 0..1 <br/> [ScalesCivilCase](../classes/ScalesCivilCase.md) | No slot (predicate) description specified <br/>  | direct | 1 |
| [scales_hasIdbCtfilr](../slots/scales_hasIdbCtfilr.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbOffice](../slots/scales_hasIdbOffice.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbPristot](../slots/scales_hasIdbPristot.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbPristim4](../slots/scales_hasIdbPristim4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbProbmon3](../slots/scales_hasIdbProbmon3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbAppdate](../slots/scales_hasIdbAppdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFofflvl5](../slots/scales_hasIdbFofflvl5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTrandist](../slots/scales_hasIdbTrandist.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbCttrtrn](../slots/scales_hasIdbCttrtrn.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFsev5](../slots/scales_hasIdbFsev5.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2CaseJudge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseJudge.md) | No slot (predicate) description specified <br/>  | direct | 2363117 |
| [niem50_StatusDescriptionText](../slots/niem50_StatusDescriptionText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 2277147 |
| [scales_hasIdbSupvrel2](../slots/scales_hasIdbSupvrel2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbMagdock](../slots/scales_hasIdbMagdock.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbToffcd1](../slots/scales_hasIdbToffcd1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFineamt5](../slots/scales_hasIdbFineamt5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbDisp5](../slots/scales_hasIdbDisp5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbSupvrel5](../slots/scales_hasIdbSupvrel5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTtitle5](../slots/scales_hasIdbTtitle5.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbD2toffcd5](../slots/scales_hasIdbD2toffcd5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFugstat](../slots/scales_hasIdbFugstat.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbProbcd2](../slots/scales_hasIdbProbcd2.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTsev1](../slots/scales_hasIdbTsev1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbCtfil](../slots/scales_hasIdbCtfil.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [niem50_JurisdictionText](../slots/niem50_JurisdictionText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 2131217 |
| [scales_hasIdbToffcd3](../slots/scales_hasIdbToffcd3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbVer](../slots/scales_hasIdbVer.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [niem50_StartDate](../slots/niem50_StartDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) | No slot (predicate) description specified <br/>  | direct | 2277147 |
| [scales_hasIdbPristim1](../slots/scales_hasIdbPristim1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFsev4](../slots/scales_hasIdbFsev4.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbCtfilwor](../slots/scales_hasIdbCtfilwor.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTrandock](../slots/scales_hasIdbTrandock.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbCttr](../slots/scales_hasIdbCttr.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbD2foffcd2](../slots/scales_hasIdbD2foffcd2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbDistrict](../slots/scales_hasIdbDistrict.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFofflvl2](../slots/scales_hasIdbFofflvl2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFineamt2](../slots/scales_hasIdbFineamt2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFofflvl4](../slots/scales_hasIdbFofflvl4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge.md) | 0..1 <br/> [HttpRelease.niem.govNiemDomainsJxdm7.2Charge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Charge.md) | No slot (predicate) description specified <br/>  | direct | 607725 |
| [scales_hasIdbTofflvl3](../slots/scales_hasIdbTofflvl3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFtitle5](../slots/scales_hasIdbFtitle5.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTofflvl1](../slots/scales_hasIdbTofflvl1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbCounty](../slots/scales_hasIdbCounty.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbCttrwor](../slots/scales_hasIdbCttrwor.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTsev4](../slots/scales_hasIdbTsev4.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbToffcd4](../slots/scales_hasIdbToffcd4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbDeflgky](../slots/scales_hasIdbDeflgky.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_DocketTable](../slots/scales_DocketTable.md) | 0..1 <br/> [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction.md) | No slot (predicate) description specified <br/>  | direct | 2511005 |
| [scales_hasIdbD2toffcd4](../slots/scales_hasIdbD2toffcd4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbToffcd2](../slots/scales_hasIdbToffcd2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasRelatedCase](../slots/scales_hasRelatedCase.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[ScalesCivilCase](../classes/ScalesCivilCase.md)&nbsp;or&nbsp;<br />[ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No slot (predicate) description specified <br/>  | direct | 3540 |
| [scales_hasIdbPristim5](../slots/scales_hasIdbPristim5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFoffcd1](../slots/scales_hasIdbFoffcd1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTofflvl2](../slots/scales_hasIdbTofflvl2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFiledate](../slots/scales_hasIdbFiledate.md) | 0..1 <br/> [xsd:dateTime](http://www.w3.org/2001/XMLSchema#dateTime) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbUpdate](../slots/scales_hasIdbUpdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbD2foffcd1](../slots/scales_hasIdbD2foffcd1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty.md) | 0..1 <br/> [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md)&nbsp;or&nbsp;<br />[ScalesParty](../classes/ScalesParty.md) | No slot (predicate) description specified <br/>  | direct | 2562309 |
| [scales_hasIdbFinetot](../slots/scales_hasIdbFinetot.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTofflvl4](../slots/scales_hasIdbTofflvl4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbAppcd](../slots/scales_hasIdbAppcd.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbPriscd4](../slots/scales_hasIdbPriscd4.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbCircuit](../slots/scales_hasIdbCircuit.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbCttrr](../slots/scales_hasIdbCttrr.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTypereg](../slots/scales_hasIdbTypereg.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbD2toffcd1](../slots/scales_hasIdbD2toffcd1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFsev1](../slots/scales_hasIdbFsev1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2Court](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Court.md) | No slot (predicate) description specified <br/>  | direct | 2277147 |
| [scales_hasIdbPriscd5](../slots/scales_hasIdbPriscd5.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbInt1](../slots/scales_hasIdbInt1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTofflvl5](../slots/scales_hasIdbTofflvl5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbCtdef](../slots/scales_hasIdbCtdef.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbProbcd3](../slots/scales_hasIdbProbcd3.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFofflvl1](../slots/scales_hasIdbFofflvl1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbProcdate](../slots/scales_hasIdbProcdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbDefno](../slots/scales_hasIdbDefno.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_Party](../slots/scales_Party.md) | 0..1 <br/> [ScalesParty](../classes/ScalesParty.md) | No slot (predicate) description specified <br/>  | direct | 19710 |
| [scales_hasIdbInt2](../slots/scales_hasIdbInt2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTsev2](../slots/scales_hasIdbTsev2.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbStatuscd](../slots/scales_hasIdbStatuscd.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbSupvrel1](../slots/scales_hasIdbSupvrel1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbCtfiltrn](../slots/scales_hasIdbCtfiltrn.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFoffcd4](../slots/scales_hasIdbFoffcd4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbD2foffcd3](../slots/scales_hasIdbD2foffcd3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbProbtot](../slots/scales_hasIdbProbtot.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTtitle1](../slots/scales_hasIdbTtitle1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty.md) | 0..1 <br/> [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md)&nbsp;or&nbsp;<br />[ScalesParty](../classes/ScalesParty.md) | No slot (predicate) description specified <br/>  | direct | 2212899 |
| [scales_hasIdbTrandef](../slots/scales_hasIdbTrandef.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbD2toffcd3](../slots/scales_hasIdbD2toffcd3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbPriscd1](../slots/scales_hasIdbPriscd1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbD2foffcd5](../slots/scales_hasIdbD2foffcd5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbProbcd4](../slots/scales_hasIdbProbcd4.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbDisp1](../slots/scales_hasIdbDisp1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbProccd](../slots/scales_hasIdbProccd.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbProbcd5](../slots/scales_hasIdbProbcd5.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbSupvrel3](../slots/scales_hasIdbSupvrel3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbInt3](../slots/scales_hasIdbInt3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbPriscd2](../slots/scales_hasIdbPriscd2.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFsev3](../slots/scales_hasIdbFsev3.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbProbmon5](../slots/scales_hasIdbProbmon5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFofflvl3](../slots/scales_hasIdbFofflvl3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbDisp4](../slots/scales_hasIdbDisp4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbFoffcd2](../slots/scales_hasIdbFoffcd2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbTtitle4](../slots/scales_hasIdbTtitle4.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [niem50_CaseGeneralCategoryText](../slots/niem50_CaseGeneralCategoryText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 2277147 |
| [scales_hasIdbDisp3](../slots/scales_hasIdbDisp3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbToffcd5](../slots/scales_hasIdbToffcd5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbIs_stub](../slots/scales_hasIdbIs_stub.md) | 0..1 <br/> [xsd:boolean](http://www.w3.org/2001/XMLSchema#boolean) | No slot (predicate) description specified <br/>  | direct | 121785 |
| [scales_hasIdbPristim3](../slots/scales_hasIdbPristim3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 121785 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Booking](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Booking.md) | [scales_BookingCase](../slots/scales_BookingCase.md) | range | [ScalesCriminalCase](../classes/ScalesCriminalCase.md) |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [scales_hasRelatedCase](../slots/scales_hasRelatedCase.md) | any_of[range] | [ScalesCriminalCase](../classes/ScalesCriminalCase.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [scales_hasRelatedCase](../slots/scales_hasRelatedCase.md) | any_of[range] | [ScalesCriminalCase](../classes/ScalesCriminalCase.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: scales_CriminalCase
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 2368748
description: No class (type) description specified
title: No class (type) name specified
from_schema: scales-kg
rank: 1000
slots:
- scales_hasIdbTranoff
- scales_hasIdbPriscd3
- scales_hasIdbFiscalyr
- scales_hasIdbFineamt4
- scales_hasIdbTcounsel
- scales_hasIdbFcounsel
- scales_hasIdbSentdate
- scales_hasIdbTermoff
- scales_hasIdbTapeyear
- scales_hasIdbTypemag
- scales_hasIdbD2toffcd2
- scales_hasIdbCaslgky
- scales_hasIdbCtpnwof
- niem50_CaseDocketID
- scales_hasIdbProbmon4
- scales_hasIdbMagdef
- scales_hasIdbFgstrtdate
- scales_hasIdbCtpn
- scales_hasIdbTsev3
- scales_hasIdbFineamt3
- scales_hasIdbTsev5
- scales_hasIdbDisp2
- scales_hasIdbReopseq
- scales_hasIdbProbmon1
- scales_hasIdbFtitle4
- scales_hasIdbFtitle2
- scales_hasIdbDispdate
- scales_hasIdbFineamt1
- scales_hasIdbProbcd1
- scales_hasIdbLoaddate
- scales_hasIdbPristim2
- scales_hasIdbD2foffcd4
- scales_hasIdbSupvrel4
- scales_hasIdbFoffcd5
- niem50_EndDate
- scales_hasIdbFoffcd3
- scales_hasIdbTermdate
- scales_hasIdbProbmon2
- scales_hasIdbDocket
- scales_hasIdbFsev2
- scales_hasIdbFtitle3
- scales_hasIdbTtitle3
- scales_hasIdbTypetrn
- scales_hasIdbTtitle2
- scales_hasIdbFtitle1
- scales_hasIdbFgenddate
- scales_hasMemberCase
- scales_hasIdbCtfilr
- scales_hasIdbOffice
- scales_hasIdbPristot
- scales_hasIdbPristim4
- scales_hasIdbProbmon3
- scales_hasIdbAppdate
- scales_hasIdbFofflvl5
- scales_hasIdbTrandist
- scales_hasIdbCttrtrn
- scales_hasIdbFsev5
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
- niem50_StatusDescriptionText
- scales_hasIdbSupvrel2
- scales_hasIdbMagdock
- scales_hasIdbToffcd1
- scales_hasIdbFineamt5
- scales_hasIdbDisp5
- scales_hasIdbSupvrel5
- scales_hasIdbTtitle5
- scales_hasIdbD2toffcd5
- scales_hasIdbFugstat
- scales_hasIdbProbcd2
- scales_hasIdbTsev1
- scales_hasIdbCtfil
- niem50_JurisdictionText
- scales_hasIdbToffcd3
- scales_hasIdbVer
- niem50_StartDate
- scales_hasIdbPristim1
- scales_hasIdbFsev4
- scales_hasIdbCtfilwor
- scales_hasIdbTrandock
- scales_hasIdbCttr
- scales_hasIdbD2foffcd2
- scales_hasIdbDistrict
- scales_hasIdbFofflvl2
- scales_hasIdbFineamt2
- scales_hasIdbFofflvl4
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge
- scales_hasIdbTofflvl3
- scales_hasIdbFtitle5
- scales_hasIdbTofflvl1
- scales_hasIdbCounty
- scales_hasIdbCttrwor
- scales_hasIdbTsev4
- scales_hasIdbToffcd4
- scales_hasIdbDeflgky
- scales_DocketTable
- scales_hasIdbD2toffcd4
- scales_hasIdbToffcd2
- scales_hasRelatedCase
- scales_hasIdbPristim5
- scales_hasIdbFoffcd1
- scales_hasIdbTofflvl2
- scales_hasIdbFiledate
- scales_hasIdbUpdate
- scales_hasIdbD2foffcd1
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- scales_hasIdbFinetot
- scales_hasIdbTofflvl4
- scales_hasIdbAppcd
- scales_hasIdbPriscd4
- scales_hasIdbCircuit
- scales_hasIdbCttrr
- scales_hasIdbTypereg
- scales_hasIdbD2toffcd1
- scales_hasIdbFsev1
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt
- scales_hasIdbPriscd5
- scales_hasIdbInt1
- scales_hasIdbTofflvl5
- scales_hasIdbCtdef
- scales_hasIdbProbcd3
- scales_hasIdbFofflvl1
- scales_hasIdbProcdate
- scales_hasIdbDefno
- scales_Party
- scales_hasIdbInt2
- scales_hasIdbTsev2
- scales_hasIdbStatuscd
- scales_hasIdbSupvrel1
- scales_hasIdbCtfiltrn
- scales_hasIdbFoffcd4
- scales_hasIdbD2foffcd3
- scales_hasIdbProbtot
- scales_hasIdbTtitle1
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
- scales_hasIdbTrandef
- scales_hasIdbD2toffcd3
- scales_hasIdbPriscd1
- scales_hasIdbD2foffcd5
- scales_hasIdbProbcd4
- scales_hasIdbDisp1
- scales_hasIdbProccd
- scales_hasIdbProbcd5
- scales_hasIdbSupvrel3
- scales_hasIdbInt3
- scales_hasIdbPriscd2
- scales_hasIdbFsev3
- scales_hasIdbProbmon5
- scales_hasIdbFofflvl3
- scales_hasIdbDisp4
- scales_hasIdbFoffcd2
- scales_hasIdbTtitle4
- niem50_CaseGeneralCategoryText
- scales_hasIdbDisp3
- scales_hasIdbToffcd5
- scales_hasIdbIs_stub
- scales_hasIdbPristim3
slot_usage:
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Charge:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
        value: 607725
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Court:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Court
        value: 145961
      string:
        tag: string
        value: 2131186
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
        value: 406320
      scales_Party:
        tag: scales_Party
        value: 2155989
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
        value: 146490
      scales_Party:
        tag: scales_Party
        value: 2066409
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
        value: 2131186
      uri:
        tag: uri
        value: 231931
  niem50_CaseDocketID:
    name: niem50_CaseDocketID
    annotations:
      string:
        tag: string
        value: 2368748
  niem50_CaseGeneralCategoryText:
    name: niem50_CaseGeneralCategoryText
    annotations:
      string:
        tag: string
        value: 2277147
  niem50_EndDate:
    name: niem50_EndDate
    annotations:
      date:
        tag: date
        value: 2204518
  niem50_JurisdictionText:
    name: niem50_JurisdictionText
    annotations:
      string:
        tag: string
        value: 2131217
  niem50_StartDate:
    name: niem50_StartDate
    annotations:
      date:
        tag: date
        value: 2277147
  niem50_StatusDescriptionText:
    name: niem50_StatusDescriptionText
    annotations:
      string:
        tag: string
        value: 2277147
  scales_DocketTable:
    name: scales_DocketTable
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
        value: 145842
      http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
        value: 2365163
  scales_Party:
    name: scales_Party
    annotations:
      scales_Party:
        tag: scales_Party
        value: 19710
  scales_hasIdbAppcd:
    name: scales_hasIdbAppcd
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbAppdate:
    name: scales_hasIdbAppdate
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbCaslgky:
    name: scales_hasIdbCaslgky
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbCircuit:
    name: scales_hasIdbCircuit
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCounty:
    name: scales_hasIdbCounty
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCtdef:
    name: scales_hasIdbCtdef
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCtfil:
    name: scales_hasIdbCtfil
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCtfilr:
    name: scales_hasIdbCtfilr
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCtfiltrn:
    name: scales_hasIdbCtfiltrn
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCtfilwor:
    name: scales_hasIdbCtfilwor
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCtpn:
    name: scales_hasIdbCtpn
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCtpnwof:
    name: scales_hasIdbCtpnwof
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCttr:
    name: scales_hasIdbCttr
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCttrr:
    name: scales_hasIdbCttrr
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCttrtrn:
    name: scales_hasIdbCttrtrn
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCttrwor:
    name: scales_hasIdbCttrwor
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbD2foffcd1:
    name: scales_hasIdbD2foffcd1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbD2foffcd2:
    name: scales_hasIdbD2foffcd2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbD2foffcd3:
    name: scales_hasIdbD2foffcd3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbD2foffcd4:
    name: scales_hasIdbD2foffcd4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbD2foffcd5:
    name: scales_hasIdbD2foffcd5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbD2toffcd1:
    name: scales_hasIdbD2toffcd1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbD2toffcd2:
    name: scales_hasIdbD2toffcd2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbD2toffcd3:
    name: scales_hasIdbD2toffcd3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbD2toffcd4:
    name: scales_hasIdbD2toffcd4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbD2toffcd5:
    name: scales_hasIdbD2toffcd5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbDeflgky:
    name: scales_hasIdbDeflgky
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbDefno:
    name: scales_hasIdbDefno
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbDisp1:
    name: scales_hasIdbDisp1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbDisp2:
    name: scales_hasIdbDisp2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbDisp3:
    name: scales_hasIdbDisp3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbDisp4:
    name: scales_hasIdbDisp4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbDisp5:
    name: scales_hasIdbDisp5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbDispdate:
    name: scales_hasIdbDispdate
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbDistrict:
    name: scales_hasIdbDistrict
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbDocket:
    name: scales_hasIdbDocket
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFcounsel:
    name: scales_hasIdbFcounsel
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFgenddate:
    name: scales_hasIdbFgenddate
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFgstrtdate:
    name: scales_hasIdbFgstrtdate
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFiledate:
    name: scales_hasIdbFiledate
    annotations:
      datetime:
        tag: datetime
        value: 121785
  scales_hasIdbFineamt1:
    name: scales_hasIdbFineamt1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFineamt2:
    name: scales_hasIdbFineamt2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFineamt3:
    name: scales_hasIdbFineamt3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFineamt4:
    name: scales_hasIdbFineamt4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFineamt5:
    name: scales_hasIdbFineamt5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFinetot:
    name: scales_hasIdbFinetot
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFiscalyr:
    name: scales_hasIdbFiscalyr
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFoffcd1:
    name: scales_hasIdbFoffcd1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFoffcd2:
    name: scales_hasIdbFoffcd2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFoffcd3:
    name: scales_hasIdbFoffcd3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFoffcd4:
    name: scales_hasIdbFoffcd4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFoffcd5:
    name: scales_hasIdbFoffcd5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFofflvl1:
    name: scales_hasIdbFofflvl1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFofflvl2:
    name: scales_hasIdbFofflvl2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFofflvl3:
    name: scales_hasIdbFofflvl3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFofflvl4:
    name: scales_hasIdbFofflvl4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFofflvl5:
    name: scales_hasIdbFofflvl5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFsev1:
    name: scales_hasIdbFsev1
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFsev2:
    name: scales_hasIdbFsev2
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFsev3:
    name: scales_hasIdbFsev3
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFsev4:
    name: scales_hasIdbFsev4
    annotations:
      integer:
        tag: integer
        value: 1529
      string:
        tag: string
        value: 120256
  scales_hasIdbFsev5:
    name: scales_hasIdbFsev5
    annotations:
      integer:
        tag: integer
        value: 3512
      string:
        tag: string
        value: 118273
  scales_hasIdbFtitle1:
    name: scales_hasIdbFtitle1
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFtitle2:
    name: scales_hasIdbFtitle2
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFtitle3:
    name: scales_hasIdbFtitle3
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFtitle4:
    name: scales_hasIdbFtitle4
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFtitle5:
    name: scales_hasIdbFtitle5
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFugstat:
    name: scales_hasIdbFugstat
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbInt1:
    name: scales_hasIdbInt1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbInt2:
    name: scales_hasIdbInt2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbInt3:
    name: scales_hasIdbInt3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbIs_stub:
    name: scales_hasIdbIs_stub
    annotations:
      boolean:
        tag: boolean
        value: 121785
  scales_hasIdbLoaddate:
    name: scales_hasIdbLoaddate
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbMagdef:
    name: scales_hasIdbMagdef
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbMagdock:
    name: scales_hasIdbMagdock
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbOffice:
    name: scales_hasIdbOffice
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbPriscd1:
    name: scales_hasIdbPriscd1
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbPriscd2:
    name: scales_hasIdbPriscd2
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbPriscd3:
    name: scales_hasIdbPriscd3
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbPriscd4:
    name: scales_hasIdbPriscd4
    annotations:
      integer:
        tag: integer
        value: 16399
      string:
        tag: string
        value: 105386
  scales_hasIdbPriscd5:
    name: scales_hasIdbPriscd5
    annotations:
      integer:
        tag: integer
        value: 56347
      string:
        tag: string
        value: 65438
  scales_hasIdbPristim1:
    name: scales_hasIdbPristim1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbPristim2:
    name: scales_hasIdbPristim2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbPristim3:
    name: scales_hasIdbPristim3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbPristim4:
    name: scales_hasIdbPristim4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbPristim5:
    name: scales_hasIdbPristim5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbPristot:
    name: scales_hasIdbPristot
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbProbcd1:
    name: scales_hasIdbProbcd1
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbProbcd2:
    name: scales_hasIdbProbcd2
    annotations:
      integer:
        tag: integer
        value: 7063
      string:
        tag: string
        value: 114722
  scales_hasIdbProbcd3:
    name: scales_hasIdbProbcd3
    annotations:
      integer:
        tag: integer
        value: 50115
      string:
        tag: string
        value: 71670
  scales_hasIdbProbcd4:
    name: scales_hasIdbProbcd4
    annotations:
      integer:
        tag: integer
        value: 70539
      string:
        tag: string
        value: 51246
  scales_hasIdbProbcd5:
    name: scales_hasIdbProbcd5
    annotations:
      integer:
        tag: integer
        value: 111249
      string:
        tag: string
        value: 10536
  scales_hasIdbProbmon1:
    name: scales_hasIdbProbmon1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbProbmon2:
    name: scales_hasIdbProbmon2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbProbmon3:
    name: scales_hasIdbProbmon3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbProbmon4:
    name: scales_hasIdbProbmon4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbProbmon5:
    name: scales_hasIdbProbmon5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbProbtot:
    name: scales_hasIdbProbtot
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbProccd:
    name: scales_hasIdbProccd
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbProcdate:
    name: scales_hasIdbProcdate
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbReopseq:
    name: scales_hasIdbReopseq
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbSentdate:
    name: scales_hasIdbSentdate
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbStatuscd:
    name: scales_hasIdbStatuscd
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbSupvrel1:
    name: scales_hasIdbSupvrel1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbSupvrel2:
    name: scales_hasIdbSupvrel2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbSupvrel3:
    name: scales_hasIdbSupvrel3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbSupvrel4:
    name: scales_hasIdbSupvrel4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbSupvrel5:
    name: scales_hasIdbSupvrel5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTapeyear:
    name: scales_hasIdbTapeyear
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTcounsel:
    name: scales_hasIdbTcounsel
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTermdate:
    name: scales_hasIdbTermdate
    annotations:
      datetime:
        tag: datetime
        value: 50408
  scales_hasIdbTermoff:
    name: scales_hasIdbTermoff
    annotations:
      integer:
        tag: integer
        value: 113263
      string:
        tag: string
        value: 8522
  scales_hasIdbToffcd1:
    name: scales_hasIdbToffcd1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbToffcd2:
    name: scales_hasIdbToffcd2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbToffcd3:
    name: scales_hasIdbToffcd3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbToffcd4:
    name: scales_hasIdbToffcd4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbToffcd5:
    name: scales_hasIdbToffcd5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTofflvl1:
    name: scales_hasIdbTofflvl1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTofflvl2:
    name: scales_hasIdbTofflvl2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTofflvl3:
    name: scales_hasIdbTofflvl3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTofflvl4:
    name: scales_hasIdbTofflvl4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTofflvl5:
    name: scales_hasIdbTofflvl5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTrandef:
    name: scales_hasIdbTrandef
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTrandist:
    name: scales_hasIdbTrandist
    annotations:
      integer:
        tag: integer
        value: 102710
      string:
        tag: string
        value: 19075
  scales_hasIdbTrandock:
    name: scales_hasIdbTrandock
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTranoff:
    name: scales_hasIdbTranoff
    annotations:
      integer:
        tag: integer
        value: 121785
  scales_hasIdbTsev1:
    name: scales_hasIdbTsev1
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbTsev2:
    name: scales_hasIdbTsev2
    annotations:
      integer:
        tag: integer
        value: 7475
      string:
        tag: string
        value: 114310
  scales_hasIdbTsev3:
    name: scales_hasIdbTsev3
    annotations:
      integer:
        tag: integer
        value: 12133
      string:
        tag: string
        value: 109652
  scales_hasIdbTsev4:
    name: scales_hasIdbTsev4
    annotations:
      integer:
        tag: integer
        value: 14181
      string:
        tag: string
        value: 107604
  scales_hasIdbTsev5:
    name: scales_hasIdbTsev5
    annotations:
      integer:
        tag: integer
        value: 21394
      string:
        tag: string
        value: 100391
  scales_hasIdbTtitle1:
    name: scales_hasIdbTtitle1
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbTtitle2:
    name: scales_hasIdbTtitle2
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbTtitle3:
    name: scales_hasIdbTtitle3
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbTtitle4:
    name: scales_hasIdbTtitle4
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbTtitle5:
    name: scales_hasIdbTtitle5
    annotations:
      integer:
        tag: integer
        value: 95
      string:
        tag: string
        value: 121690
  scales_hasIdbTypemag:
    name: scales_hasIdbTypemag
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbTypereg:
    name: scales_hasIdbTypereg
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbTypetrn:
    name: scales_hasIdbTypetrn
    annotations:
      integer:
        tag: integer
        value: 34728
      string:
        tag: string
        value: 87057
  scales_hasIdbUpdate:
    name: scales_hasIdbUpdate
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbVer:
    name: scales_hasIdbVer
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasMemberCase:
    name: scales_hasMemberCase
    annotations:
      scales_CivilCase:
        tag: scales_CivilCase
        value: 1
  scales_hasRelatedCase:
    name: scales_hasRelatedCase
    annotations:
      scales_CivilCase:
        tag: scales_CivilCase
        value: 337
      uri:
        tag: uri
        value: 3203
class_uri: scales:CriminalCase

```
</details>

### Induced

<details>

```yaml
name: scales_CriminalCase
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 2368748
description: No class (type) description specified
title: No class (type) name specified
from_schema: scales-kg
rank: 1000
slot_usage:
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Charge:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
        value: 607725
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Court:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Court
        value: 145961
      string:
        tag: string
        value: 2131186
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
        value: 406320
      scales_Party:
        tag: scales_Party
        value: 2155989
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
        value: 146490
      scales_Party:
        tag: scales_Party
        value: 2066409
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
        value: 2131186
      uri:
        tag: uri
        value: 231931
  niem50_CaseDocketID:
    name: niem50_CaseDocketID
    annotations:
      string:
        tag: string
        value: 2368748
  niem50_CaseGeneralCategoryText:
    name: niem50_CaseGeneralCategoryText
    annotations:
      string:
        tag: string
        value: 2277147
  niem50_EndDate:
    name: niem50_EndDate
    annotations:
      date:
        tag: date
        value: 2204518
  niem50_JurisdictionText:
    name: niem50_JurisdictionText
    annotations:
      string:
        tag: string
        value: 2131217
  niem50_StartDate:
    name: niem50_StartDate
    annotations:
      date:
        tag: date
        value: 2277147
  niem50_StatusDescriptionText:
    name: niem50_StatusDescriptionText
    annotations:
      string:
        tag: string
        value: 2277147
  scales_DocketTable:
    name: scales_DocketTable
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
        value: 145842
      http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
        value: 2365163
  scales_Party:
    name: scales_Party
    annotations:
      scales_Party:
        tag: scales_Party
        value: 19710
  scales_hasIdbAppcd:
    name: scales_hasIdbAppcd
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbAppdate:
    name: scales_hasIdbAppdate
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbCaslgky:
    name: scales_hasIdbCaslgky
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbCircuit:
    name: scales_hasIdbCircuit
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCounty:
    name: scales_hasIdbCounty
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCtdef:
    name: scales_hasIdbCtdef
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCtfil:
    name: scales_hasIdbCtfil
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCtfilr:
    name: scales_hasIdbCtfilr
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCtfiltrn:
    name: scales_hasIdbCtfiltrn
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCtfilwor:
    name: scales_hasIdbCtfilwor
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCtpn:
    name: scales_hasIdbCtpn
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCtpnwof:
    name: scales_hasIdbCtpnwof
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCttr:
    name: scales_hasIdbCttr
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCttrr:
    name: scales_hasIdbCttrr
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCttrtrn:
    name: scales_hasIdbCttrtrn
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbCttrwor:
    name: scales_hasIdbCttrwor
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbD2foffcd1:
    name: scales_hasIdbD2foffcd1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbD2foffcd2:
    name: scales_hasIdbD2foffcd2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbD2foffcd3:
    name: scales_hasIdbD2foffcd3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbD2foffcd4:
    name: scales_hasIdbD2foffcd4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbD2foffcd5:
    name: scales_hasIdbD2foffcd5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbD2toffcd1:
    name: scales_hasIdbD2toffcd1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbD2toffcd2:
    name: scales_hasIdbD2toffcd2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbD2toffcd3:
    name: scales_hasIdbD2toffcd3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbD2toffcd4:
    name: scales_hasIdbD2toffcd4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbD2toffcd5:
    name: scales_hasIdbD2toffcd5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbDeflgky:
    name: scales_hasIdbDeflgky
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbDefno:
    name: scales_hasIdbDefno
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbDisp1:
    name: scales_hasIdbDisp1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbDisp2:
    name: scales_hasIdbDisp2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbDisp3:
    name: scales_hasIdbDisp3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbDisp4:
    name: scales_hasIdbDisp4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbDisp5:
    name: scales_hasIdbDisp5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbDispdate:
    name: scales_hasIdbDispdate
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbDistrict:
    name: scales_hasIdbDistrict
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbDocket:
    name: scales_hasIdbDocket
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFcounsel:
    name: scales_hasIdbFcounsel
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFgenddate:
    name: scales_hasIdbFgenddate
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFgstrtdate:
    name: scales_hasIdbFgstrtdate
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFiledate:
    name: scales_hasIdbFiledate
    annotations:
      datetime:
        tag: datetime
        value: 121785
  scales_hasIdbFineamt1:
    name: scales_hasIdbFineamt1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFineamt2:
    name: scales_hasIdbFineamt2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFineamt3:
    name: scales_hasIdbFineamt3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFineamt4:
    name: scales_hasIdbFineamt4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFineamt5:
    name: scales_hasIdbFineamt5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFinetot:
    name: scales_hasIdbFinetot
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFiscalyr:
    name: scales_hasIdbFiscalyr
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFoffcd1:
    name: scales_hasIdbFoffcd1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFoffcd2:
    name: scales_hasIdbFoffcd2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFoffcd3:
    name: scales_hasIdbFoffcd3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFoffcd4:
    name: scales_hasIdbFoffcd4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFoffcd5:
    name: scales_hasIdbFoffcd5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFofflvl1:
    name: scales_hasIdbFofflvl1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFofflvl2:
    name: scales_hasIdbFofflvl2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFofflvl3:
    name: scales_hasIdbFofflvl3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFofflvl4:
    name: scales_hasIdbFofflvl4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFofflvl5:
    name: scales_hasIdbFofflvl5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbFsev1:
    name: scales_hasIdbFsev1
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFsev2:
    name: scales_hasIdbFsev2
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFsev3:
    name: scales_hasIdbFsev3
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFsev4:
    name: scales_hasIdbFsev4
    annotations:
      integer:
        tag: integer
        value: 1529
      string:
        tag: string
        value: 120256
  scales_hasIdbFsev5:
    name: scales_hasIdbFsev5
    annotations:
      integer:
        tag: integer
        value: 3512
      string:
        tag: string
        value: 118273
  scales_hasIdbFtitle1:
    name: scales_hasIdbFtitle1
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFtitle2:
    name: scales_hasIdbFtitle2
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFtitle3:
    name: scales_hasIdbFtitle3
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFtitle4:
    name: scales_hasIdbFtitle4
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFtitle5:
    name: scales_hasIdbFtitle5
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbFugstat:
    name: scales_hasIdbFugstat
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbInt1:
    name: scales_hasIdbInt1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbInt2:
    name: scales_hasIdbInt2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbInt3:
    name: scales_hasIdbInt3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbIs_stub:
    name: scales_hasIdbIs_stub
    annotations:
      boolean:
        tag: boolean
        value: 121785
  scales_hasIdbLoaddate:
    name: scales_hasIdbLoaddate
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbMagdef:
    name: scales_hasIdbMagdef
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbMagdock:
    name: scales_hasIdbMagdock
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbOffice:
    name: scales_hasIdbOffice
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbPriscd1:
    name: scales_hasIdbPriscd1
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbPriscd2:
    name: scales_hasIdbPriscd2
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbPriscd3:
    name: scales_hasIdbPriscd3
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbPriscd4:
    name: scales_hasIdbPriscd4
    annotations:
      integer:
        tag: integer
        value: 16399
      string:
        tag: string
        value: 105386
  scales_hasIdbPriscd5:
    name: scales_hasIdbPriscd5
    annotations:
      integer:
        tag: integer
        value: 56347
      string:
        tag: string
        value: 65438
  scales_hasIdbPristim1:
    name: scales_hasIdbPristim1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbPristim2:
    name: scales_hasIdbPristim2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbPristim3:
    name: scales_hasIdbPristim3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbPristim4:
    name: scales_hasIdbPristim4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbPristim5:
    name: scales_hasIdbPristim5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbPristot:
    name: scales_hasIdbPristot
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbProbcd1:
    name: scales_hasIdbProbcd1
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbProbcd2:
    name: scales_hasIdbProbcd2
    annotations:
      integer:
        tag: integer
        value: 7063
      string:
        tag: string
        value: 114722
  scales_hasIdbProbcd3:
    name: scales_hasIdbProbcd3
    annotations:
      integer:
        tag: integer
        value: 50115
      string:
        tag: string
        value: 71670
  scales_hasIdbProbcd4:
    name: scales_hasIdbProbcd4
    annotations:
      integer:
        tag: integer
        value: 70539
      string:
        tag: string
        value: 51246
  scales_hasIdbProbcd5:
    name: scales_hasIdbProbcd5
    annotations:
      integer:
        tag: integer
        value: 111249
      string:
        tag: string
        value: 10536
  scales_hasIdbProbmon1:
    name: scales_hasIdbProbmon1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbProbmon2:
    name: scales_hasIdbProbmon2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbProbmon3:
    name: scales_hasIdbProbmon3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbProbmon4:
    name: scales_hasIdbProbmon4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbProbmon5:
    name: scales_hasIdbProbmon5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbProbtot:
    name: scales_hasIdbProbtot
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbProccd:
    name: scales_hasIdbProccd
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbProcdate:
    name: scales_hasIdbProcdate
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbReopseq:
    name: scales_hasIdbReopseq
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbSentdate:
    name: scales_hasIdbSentdate
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbStatuscd:
    name: scales_hasIdbStatuscd
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbSupvrel1:
    name: scales_hasIdbSupvrel1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbSupvrel2:
    name: scales_hasIdbSupvrel2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbSupvrel3:
    name: scales_hasIdbSupvrel3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbSupvrel4:
    name: scales_hasIdbSupvrel4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbSupvrel5:
    name: scales_hasIdbSupvrel5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTapeyear:
    name: scales_hasIdbTapeyear
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTcounsel:
    name: scales_hasIdbTcounsel
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTermdate:
    name: scales_hasIdbTermdate
    annotations:
      datetime:
        tag: datetime
        value: 50408
  scales_hasIdbTermoff:
    name: scales_hasIdbTermoff
    annotations:
      integer:
        tag: integer
        value: 113263
      string:
        tag: string
        value: 8522
  scales_hasIdbToffcd1:
    name: scales_hasIdbToffcd1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbToffcd2:
    name: scales_hasIdbToffcd2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbToffcd3:
    name: scales_hasIdbToffcd3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbToffcd4:
    name: scales_hasIdbToffcd4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbToffcd5:
    name: scales_hasIdbToffcd5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTofflvl1:
    name: scales_hasIdbTofflvl1
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTofflvl2:
    name: scales_hasIdbTofflvl2
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTofflvl3:
    name: scales_hasIdbTofflvl3
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTofflvl4:
    name: scales_hasIdbTofflvl4
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTofflvl5:
    name: scales_hasIdbTofflvl5
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTrandef:
    name: scales_hasIdbTrandef
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTrandist:
    name: scales_hasIdbTrandist
    annotations:
      integer:
        tag: integer
        value: 102710
      string:
        tag: string
        value: 19075
  scales_hasIdbTrandock:
    name: scales_hasIdbTrandock
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasIdbTranoff:
    name: scales_hasIdbTranoff
    annotations:
      integer:
        tag: integer
        value: 121785
  scales_hasIdbTsev1:
    name: scales_hasIdbTsev1
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbTsev2:
    name: scales_hasIdbTsev2
    annotations:
      integer:
        tag: integer
        value: 7475
      string:
        tag: string
        value: 114310
  scales_hasIdbTsev3:
    name: scales_hasIdbTsev3
    annotations:
      integer:
        tag: integer
        value: 12133
      string:
        tag: string
        value: 109652
  scales_hasIdbTsev4:
    name: scales_hasIdbTsev4
    annotations:
      integer:
        tag: integer
        value: 14181
      string:
        tag: string
        value: 107604
  scales_hasIdbTsev5:
    name: scales_hasIdbTsev5
    annotations:
      integer:
        tag: integer
        value: 21394
      string:
        tag: string
        value: 100391
  scales_hasIdbTtitle1:
    name: scales_hasIdbTtitle1
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbTtitle2:
    name: scales_hasIdbTtitle2
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbTtitle3:
    name: scales_hasIdbTtitle3
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbTtitle4:
    name: scales_hasIdbTtitle4
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbTtitle5:
    name: scales_hasIdbTtitle5
    annotations:
      integer:
        tag: integer
        value: 95
      string:
        tag: string
        value: 121690
  scales_hasIdbTypemag:
    name: scales_hasIdbTypemag
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbTypereg:
    name: scales_hasIdbTypereg
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbTypetrn:
    name: scales_hasIdbTypetrn
    annotations:
      integer:
        tag: integer
        value: 34728
      string:
        tag: string
        value: 87057
  scales_hasIdbUpdate:
    name: scales_hasIdbUpdate
    annotations:
      string:
        tag: string
        value: 121785
  scales_hasIdbVer:
    name: scales_hasIdbVer
    annotations:
      double:
        tag: double
        value: 121785
  scales_hasMemberCase:
    name: scales_hasMemberCase
    annotations:
      scales_CivilCase:
        tag: scales_CivilCase
        value: 1
  scales_hasRelatedCase:
    name: scales_hasRelatedCase
    annotations:
      scales_CivilCase:
        tag: scales_CivilCase
        value: 337
      uri:
        tag: uri
        value: 3203
attributes:
  scales_hasIdbTranoff:
    name: scales_hasIdbTranoff
    annotations:
      integer:
        tag: integer
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbTranoff
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTranoff
    alias: scales_hasIdbTranoff
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: integer
  scales_hasIdbPriscd3:
    name: scales_hasIdbPriscd3
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbPriscd3
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPriscd3
    alias: scales_hasIdbPriscd3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbFiscalyr:
    name: scales_hasIdbFiscalyr
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '2016.0'
        example_object_type: double
        example_predicate: scales:hasIdbFiscalyr
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFiscalyr
    alias: scales_hasIdbFiscalyr
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFineamt4:
    name: scales_hasIdbFineamt4
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFineamt4
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFineamt4
    alias: scales_hasIdbFineamt4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTcounsel:
    name: scales_hasIdbTcounsel
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '2.0'
        example_object_type: double
        example_predicate: scales:hasIdbTcounsel
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTcounsel
    alias: scales_hasIdbTcounsel
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFcounsel:
    name: scales_hasIdbFcounsel
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '2.0'
        example_object_type: double
        example_predicate: scales:hasIdbFcounsel
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFcounsel
    alias: scales_hasIdbFcounsel
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbSentdate:
    name: scales_hasIdbSentdate
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 08/01/2016
        example_object_type: string
        example_predicate: scales:hasIdbSentdate
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSentdate
    alias: scales_hasIdbSentdate
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbTermoff:
    name: scales_hasIdbTermoff
    annotations:
      integer:
        tag: integer
        value: 113263
      string:
        tag: string
        value: 8522
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1'
        example_object_type: integer
        example_predicate: scales:hasIdbTermoff
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    - object:
        example_object: '1'
        example_object_type: string
        example_predicate: scales:hasIdbTermoff
        example_subject: scales:/CriminalCase/cand;;1:16-cr-00325
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTermoff
    alias: scales_hasIdbTermoff
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: string
    - range: integer
  scales_hasIdbTapeyear:
    name: scales_hasIdbTapeyear
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '2018.0'
        example_object_type: double
        example_predicate: scales:hasIdbTapeyear
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: '2016.0'
        example_object_type: double
        example_predicate: scales:hasIdbTapeyear
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTapeyear
    alias: scales_hasIdbTapeyear
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: double
  scales_hasIdbTypemag:
    name: scales_hasIdbTypemag
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTypemag
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTypemag
    alias: scales_hasIdbTypemag
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbD2toffcd2:
    name: scales_hasIdbD2toffcd2
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '4530.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2toffcd2
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2toffcd2
    alias: scales_hasIdbD2toffcd2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbCaslgky:
    name: scales_hasIdbCaslgky
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 097-11600001CR0
        example_object_type: string
        example_predicate: scales:hasIdbCaslgky
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCaslgky
    alias: scales_hasIdbCaslgky
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbCtpnwof:
    name: scales_hasIdbCtpnwof
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCtpnwof
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtpnwof
    alias: scales_hasIdbCtpnwof
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  niem50_CaseDocketID:
    name: niem50_CaseDocketID
    annotations:
      string:
        tag: string
        value: 2368748
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 1:16-cv-00001
        example_object_type: string
        example_predicate: niem50:CaseDocketID
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: 1:16-cr-00001
        example_object_type: string
        example_predicate: niem50:CaseDocketID
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: niem50:CaseDocketID
    alias: niem50_CaseDocketID
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: string
  scales_hasIdbProbmon4:
    name: scales_hasIdbProbmon4
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbProbmon4
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbmon4
    alias: scales_hasIdbProbmon4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbMagdef:
    name: scales_hasIdbMagdef
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbMagdef
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbMagdef
    alias: scales_hasIdbMagdef
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFgstrtdate:
    name: scales_hasIdbFgstrtdate
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 01/01/1900
        example_object_type: string
        example_predicate: scales:hasIdbFgstrtdate
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFgstrtdate
    alias: scales_hasIdbFgstrtdate
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbCtpn:
    name: scales_hasIdbCtpn
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCtpn
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtpn
    alias: scales_hasIdbCtpn
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTsev3:
    name: scales_hasIdbTsev3
    annotations:
      integer:
        tag: integer
        value: 12133
      string:
        tag: string
        value: 109652
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTsev3
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbTsev3
        example_subject: scales:/CriminalCase/ared;;4:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTsev3
    alias: scales_hasIdbTsev3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: string
    - range: integer
  scales_hasIdbFineamt3:
    name: scales_hasIdbFineamt3
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFineamt3
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFineamt3
    alias: scales_hasIdbFineamt3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTsev5:
    name: scales_hasIdbTsev5
    annotations:
      integer:
        tag: integer
        value: 21394
      string:
        tag: string
        value: 100391
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTsev5
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbTsev5
        example_subject: scales:/CriminalCase/ared;;4:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTsev5
    alias: scales_hasIdbTsev5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: string
    - range: integer
  scales_hasIdbDisp2:
    name: scales_hasIdbDisp2
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '4.0'
        example_object_type: double
        example_predicate: scales:hasIdbDisp2
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDisp2
    alias: scales_hasIdbDisp2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbReopseq:
    name: scales_hasIdbReopseq
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbReopseq
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbReopseq
    alias: scales_hasIdbReopseq
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbProbmon1:
    name: scales_hasIdbProbmon1
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbProbmon1
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbmon1
    alias: scales_hasIdbProbmon1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFtitle4:
    name: scales_hasIdbFtitle4
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFtitle4
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFtitle4
    alias: scales_hasIdbFtitle4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbFtitle2:
    name: scales_hasIdbFtitle2
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFtitle2
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFtitle2
    alias: scales_hasIdbFtitle2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbDispdate:
    name: scales_hasIdbDispdate
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 02/09/2016
        example_object_type: string
        example_predicate: scales:hasIdbDispdate
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDispdate
    alias: scales_hasIdbDispdate
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbFineamt1:
    name: scales_hasIdbFineamt1
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbFineamt1
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFineamt1
    alias: scales_hasIdbFineamt1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbProbcd1:
    name: scales_hasIdbProbcd1
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbProbcd1
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbcd1
    alias: scales_hasIdbProbcd1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbLoaddate:
    name: scales_hasIdbLoaddate
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 09/12/2016
        example_object_type: string
        example_predicate: scales:hasIdbLoaddate
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbLoaddate
    alias: scales_hasIdbLoaddate
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbPristim2:
    name: scales_hasIdbPristim2
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-1.0'
        example_object_type: double
        example_predicate: scales:hasIdbPristim2
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristim2
    alias: scales_hasIdbPristim2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbD2foffcd4:
    name: scales_hasIdbD2foffcd4
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2foffcd4
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2foffcd4
    alias: scales_hasIdbD2foffcd4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbSupvrel4:
    name: scales_hasIdbSupvrel4
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbSupvrel4
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSupvrel4
    alias: scales_hasIdbSupvrel4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFoffcd5:
    name: scales_hasIdbFoffcd5
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFoffcd5
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFoffcd5
    alias: scales_hasIdbFoffcd5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  niem50_EndDate:
    name: niem50_EndDate
    annotations:
      date:
        tag: date
        value: 2204518
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '2018-05-21'
        example_object_type: date
        example_predicate: niem50:EndDate
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: '2016-08-04'
        example_object_type: date
        example_predicate: niem50:EndDate
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: niem50:EndDate
    alias: niem50_EndDate
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: date
  scales_hasIdbFoffcd3:
    name: scales_hasIdbFoffcd3
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFoffcd3
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFoffcd3
    alias: scales_hasIdbFoffcd3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTermdate:
    name: scales_hasIdbTermdate
    annotations:
      datetime:
        tag: datetime
        value: 50408
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '2018-05-21T00:00:00'
        example_object_type: datetime
        example_predicate: scales:hasIdbTermdate
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: '2016-08-01T00:00:00'
        example_object_type: datetime
        example_predicate: scales:hasIdbTermdate
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTermdate
    alias: scales_hasIdbTermdate
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: datetime
  scales_hasIdbProbmon2:
    name: scales_hasIdbProbmon2
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbProbmon2
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbmon2
    alias: scales_hasIdbProbmon2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbDocket:
    name: scales_hasIdbDocket
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1600001'
        example_object_type: string
        example_predicate: scales:hasIdbDocket
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: '1600001'
        example_object_type: string
        example_predicate: scales:hasIdbDocket
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDocket
    alias: scales_hasIdbDocket
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: string
  scales_hasIdbFsev2:
    name: scales_hasIdbFsev2
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFsev2
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFsev2
    alias: scales_hasIdbFsev2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbFtitle3:
    name: scales_hasIdbFtitle3
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFtitle3
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFtitle3
    alias: scales_hasIdbFtitle3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbTtitle3:
    name: scales_hasIdbTtitle3
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTtitle3
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTtitle3
    alias: scales_hasIdbTtitle3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbTypetrn:
    name: scales_hasIdbTypetrn
    annotations:
      integer:
        tag: integer
        value: 34728
      string:
        tag: string
        value: 87057
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTypetrn
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbTypetrn
        example_subject: scales:/CriminalCase/almd;;1:16-cr-00441
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTypetrn
    alias: scales_hasIdbTypetrn
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: string
    - range: integer
  scales_hasIdbTtitle2:
    name: scales_hasIdbTtitle2
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 26:7203C.M
        example_object_type: string
        example_predicate: scales:hasIdbTtitle2
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTtitle2
    alias: scales_hasIdbTtitle2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbFtitle1:
    name: scales_hasIdbFtitle1
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 26:7203C.M
        example_object_type: string
        example_predicate: scales:hasIdbFtitle1
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFtitle1
    alias: scales_hasIdbFtitle1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbFgenddate:
    name: scales_hasIdbFgenddate
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 01/01/1900
        example_object_type: string
        example_predicate: scales:hasIdbFgenddate
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFgenddate
    alias: scales_hasIdbFgenddate
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasMemberCase:
    name: scales_hasMemberCase
    annotations:
      scales_CivilCase:
        tag: scales_CivilCase
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/CivilCase/akd;;3:16-cv-00183
        example_object_type: scales_CivilCase
        example_predicate: scales:hasMemberCase
        example_subject: scales:/CivilCase/akd;;3:16-cv-00172
        example_subject_type: scales_CivilCase
    - object:
        example_object: scales:/CivilCase/almd;;2:16-cv-00342
        example_object_type: scales_CivilCase
        example_predicate: scales:hasMemberCase
        example_subject: scales:/CivilCase/almd;;2:15-cv-00852
        example_subject_type: None
    - object:
        example_object: scales:/CivilCase/ohsd;;1:16-cv-00014
        example_object_type: scales_CivilCase
        example_predicate: scales:hasMemberCase
        example_subject: scales:/CriminalCase/ohsd;;1:16-cr-00004
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasMemberCase
    alias: scales_hasMemberCase
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: scales_CivilCase
  scales_hasIdbCtfilr:
    name: scales_hasIdbCtfilr
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCtfilr
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtfilr
    alias: scales_hasIdbCtfilr
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbOffice:
    name: scales_hasIdbOffice
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1'
        example_object_type: string
        example_predicate: scales:hasIdbOffice
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: '1'
        example_object_type: string
        example_predicate: scales:hasIdbOffice
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbOffice
    alias: scales_hasIdbOffice
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: string
  scales_hasIdbPristot:
    name: scales_hasIdbPristot
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '12.0'
        example_object_type: double
        example_predicate: scales:hasIdbPristot
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristot
    alias: scales_hasIdbPristot
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbPristim4:
    name: scales_hasIdbPristim4
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbPristim4
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristim4
    alias: scales_hasIdbPristim4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbProbmon3:
    name: scales_hasIdbProbmon3
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbProbmon3
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbmon3
    alias: scales_hasIdbProbmon3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbAppdate:
    name: scales_hasIdbAppdate
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 02/09/2016
        example_object_type: string
        example_predicate: scales:hasIdbAppdate
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbAppdate
    alias: scales_hasIdbAppdate
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbFofflvl5:
    name: scales_hasIdbFofflvl5
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFofflvl5
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFofflvl5
    alias: scales_hasIdbFofflvl5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTrandist:
    name: scales_hasIdbTrandist
    annotations:
      integer:
        tag: integer
        value: 102710
      string:
        tag: string
        value: 19075
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTrandist
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbTrandist
        example_subject: scales:/CriminalCase/almd;;1:16-cr-00441
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTrandist
    alias: scales_hasIdbTrandist
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: string
    - range: integer
  scales_hasIdbCttrtrn:
    name: scales_hasIdbCttrtrn
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1.0'
        example_object_type: double
        example_predicate: scales:hasIdbCttrtrn
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCttrtrn
    alias: scales_hasIdbCttrtrn
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFsev5:
    name: scales_hasIdbFsev5
    annotations:
      integer:
        tag: integer
        value: 3512
      string:
        tag: string
        value: 118273
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFsev5
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbFsev5
        example_subject: scales:/CriminalCase/txsd;;4:16-cr-00241
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFsev5
    alias: scales_hasIdbFsev5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: string
    - range: integer
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
        value: 2131186
      uri:
        tag: uri
        value: 231931
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/Agent/akd;;1:16-cv-00001_a2
        example_object_type: uri
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseJudge
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: scales:/Agent/akd;;1:16-cr-00001_a2
        example_object_type: uri
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseJudge
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    - object:
        example_object: scales:Judge/ga-clayton-magistrate-civil;;0:00-cm-00001_3
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseJudge
        example_subject: scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: scales:Judge/ga-clayton-magistrate;;0:00-bc-00001_0
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseJudge
        example_subject: scales:Case/ga-clayton-magistrate;;0:00-bc-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseJudge
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: Any
    any_of:
    - range: uri
    - range: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
  niem50_StatusDescriptionText:
    name: niem50_StatusDescriptionText
    annotations:
      string:
        tag: string
        value: 2277147
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: closed
        example_object_type: string
        example_predicate: niem50:StatusDescriptionText
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: closed
        example_object_type: string
        example_predicate: niem50:StatusDescriptionText
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: niem50:StatusDescriptionText
    alias: niem50_StatusDescriptionText
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: string
  scales_hasIdbSupvrel2:
    name: scales_hasIdbSupvrel2
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '12.0'
        example_object_type: double
        example_predicate: scales:hasIdbSupvrel2
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSupvrel2
    alias: scales_hasIdbSupvrel2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbMagdock:
    name: scales_hasIdbMagdock
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbMagdock
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbMagdock
    alias: scales_hasIdbMagdock
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbToffcd1:
    name: scales_hasIdbToffcd1
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '4530.0'
        example_object_type: double
        example_predicate: scales:hasIdbToffcd1
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbToffcd1
    alias: scales_hasIdbToffcd1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFineamt5:
    name: scales_hasIdbFineamt5
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFineamt5
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFineamt5
    alias: scales_hasIdbFineamt5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbDisp5:
    name: scales_hasIdbDisp5
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbDisp5
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDisp5
    alias: scales_hasIdbDisp5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbSupvrel5:
    name: scales_hasIdbSupvrel5
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbSupvrel5
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSupvrel5
    alias: scales_hasIdbSupvrel5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTtitle5:
    name: scales_hasIdbTtitle5
    annotations:
      integer:
        tag: integer
        value: 95
      string:
        tag: string
        value: 121690
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTtitle5
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbTtitle5
        example_subject: scales:/CriminalCase/ilnd;;1:21-cr-00003
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTtitle5
    alias: scales_hasIdbTtitle5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: string
    - range: integer
  scales_hasIdbD2toffcd5:
    name: scales_hasIdbD2toffcd5
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2toffcd5
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2toffcd5
    alias: scales_hasIdbD2toffcd5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFugstat:
    name: scales_hasIdbFugstat
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: N
        example_object_type: string
        example_predicate: scales:hasIdbFugstat
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFugstat
    alias: scales_hasIdbFugstat
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbProbcd2:
    name: scales_hasIdbProbcd2
    annotations:
      integer:
        tag: integer
        value: 7063
      string:
        tag: string
        value: 114722
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbProbcd2
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbProbcd2
        example_subject: scales:/CriminalCase/casd;;3:17-cr-00163
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbcd2
    alias: scales_hasIdbProbcd2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: string
    - range: integer
  scales_hasIdbTsev1:
    name: scales_hasIdbTsev1
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: C19
        example_object_type: string
        example_predicate: scales:hasIdbTsev1
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTsev1
    alias: scales_hasIdbTsev1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbCtfil:
    name: scales_hasIdbCtfil
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1.0'
        example_object_type: double
        example_predicate: scales:hasIdbCtfil
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtfil
    alias: scales_hasIdbCtfil
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  niem50_JurisdictionText:
    name: niem50_JurisdictionText
    annotations:
      string:
        tag: string
        value: 2131217
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: U.S. Government Defendant
        example_object_type: string
        example_predicate: niem50:JurisdictionText
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: Ct. 1s
        example_object_type: string
        example_predicate: niem50:JurisdictionText
        example_subject: scales:/CriminalCase/txed;;4:17-cr-00092
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: niem50:JurisdictionText
    alias: niem50_JurisdictionText
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: string
  scales_hasIdbToffcd3:
    name: scales_hasIdbToffcd3
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbToffcd3
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbToffcd3
    alias: scales_hasIdbToffcd3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbVer:
    name: scales_hasIdbVer
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1.0'
        example_object_type: double
        example_predicate: scales:hasIdbVer
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbVer
    alias: scales_hasIdbVer
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  niem50_StartDate:
    name: niem50_StartDate
    annotations:
      date:
        tag: date
        value: 2277147
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '2016-01-04'
        example_object_type: date
        example_predicate: niem50:StartDate
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: '2016-02-03'
        example_object_type: date
        example_predicate: niem50:StartDate
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: niem50:StartDate
    alias: niem50_StartDate
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: date
  scales_hasIdbPristim1:
    name: scales_hasIdbPristim1
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '12.0'
        example_object_type: double
        example_predicate: scales:hasIdbPristim1
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristim1
    alias: scales_hasIdbPristim1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFsev4:
    name: scales_hasIdbFsev4
    annotations:
      integer:
        tag: integer
        value: 1529
      string:
        tag: string
        value: 120256
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFsev4
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbFsev4
        example_subject: scales:/CriminalCase/ilnd;;1:19-cr-00728
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFsev4
    alias: scales_hasIdbFsev4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: string
    - range: integer
  scales_hasIdbCtfilwor:
    name: scales_hasIdbCtfilwor
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1.0'
        example_object_type: double
        example_predicate: scales:hasIdbCtfilwor
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtfilwor
    alias: scales_hasIdbCtfilwor
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTrandock:
    name: scales_hasIdbTrandock
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTrandock
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTrandock
    alias: scales_hasIdbTrandock
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbCttr:
    name: scales_hasIdbCttr
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1.0'
        example_object_type: double
        example_predicate: scales:hasIdbCttr
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCttr
    alias: scales_hasIdbCttr
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbD2foffcd2:
    name: scales_hasIdbD2foffcd2
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2foffcd2
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2foffcd2
    alias: scales_hasIdbD2foffcd2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbDistrict:
    name: scales_hasIdbDistrict
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: akd
        example_object_type: string
        example_predicate: scales:hasIdbDistrict
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: akd
        example_object_type: string
        example_predicate: scales:hasIdbDistrict
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDistrict
    alias: scales_hasIdbDistrict
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: string
  scales_hasIdbFofflvl2:
    name: scales_hasIdbFofflvl2
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFofflvl2
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFofflvl2
    alias: scales_hasIdbFofflvl2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFineamt2:
    name: scales_hasIdbFineamt2
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbFineamt2
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFineamt2
    alias: scales_hasIdbFineamt2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFofflvl4:
    name: scales_hasIdbFofflvl4
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFofflvl4
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFofflvl4
    alias: scales_hasIdbFofflvl4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Charge:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
        value: 607725
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/Charge/akd;;1:16-cr-00001_c0-1-3
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCharge
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCharge
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
  scales_hasIdbTofflvl3:
    name: scales_hasIdbTofflvl3
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTofflvl3
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTofflvl3
    alias: scales_hasIdbTofflvl3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFtitle5:
    name: scales_hasIdbFtitle5
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFtitle5
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFtitle5
    alias: scales_hasIdbFtitle5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbTofflvl1:
    name: scales_hasIdbTofflvl1
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '3.0'
        example_object_type: double
        example_predicate: scales:hasIdbTofflvl1
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTofflvl1
    alias: scales_hasIdbTofflvl1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbCounty:
    name: scales_hasIdbCounty
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '2020.0'
        example_object_type: double
        example_predicate: scales:hasIdbCounty
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: '2110.0'
        example_object_type: double
        example_predicate: scales:hasIdbCounty
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCounty
    alias: scales_hasIdbCounty
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: double
  scales_hasIdbCttrwor:
    name: scales_hasIdbCttrwor
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1.0'
        example_object_type: double
        example_predicate: scales:hasIdbCttrwor
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCttrwor
    alias: scales_hasIdbCttrwor
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTsev4:
    name: scales_hasIdbTsev4
    annotations:
      integer:
        tag: integer
        value: 14181
      string:
        tag: string
        value: 107604
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTsev4
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbTsev4
        example_subject: scales:/CriminalCase/ared;;4:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTsev4
    alias: scales_hasIdbTsev4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: string
    - range: integer
  scales_hasIdbToffcd4:
    name: scales_hasIdbToffcd4
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbToffcd4
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbToffcd4
    alias: scales_hasIdbToffcd4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbDeflgky:
    name: scales_hasIdbDeflgky
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 097-11600001CR0010
        example_object_type: string
        example_predicate: scales:hasIdbDeflgky
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDeflgky
    alias: scales_hasIdbDeflgky
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_DocketTable:
    name: scales_DocketTable
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
        value: 145842
      http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
        value: 2365163
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/DocketTable/akd;;1:16-cv-00001
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
        example_predicate: scales:DocketTable
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: scales:/DocketTable/akd;;1:16-cv-00001
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
        example_predicate: scales:DocketTable
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: scales:/DocketTable/akd;;1:16-cr-00001
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
        example_predicate: scales:DocketTable
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    - object:
        example_object: scales:/DocketTable/akd;;1:16-cr-00001
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
        example_predicate: scales:DocketTable
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:DocketTable
    alias: scales_DocketTable
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: Any
    any_of:
    - range: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
    - range: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
  scales_hasIdbD2toffcd4:
    name: scales_hasIdbD2toffcd4
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2toffcd4
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2toffcd4
    alias: scales_hasIdbD2toffcd4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbToffcd2:
    name: scales_hasIdbToffcd2
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '4530.0'
        example_object_type: double
        example_predicate: scales:hasIdbToffcd2
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbToffcd2
    alias: scales_hasIdbToffcd2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasRelatedCase:
    name: scales_hasRelatedCase
    annotations:
      scales_CivilCase:
        tag: scales_CivilCase
        value: 337
      uri:
        tag: uri
        value: 3203
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/CriminalCase/akd;;1:12-cr-00001-1
        example_object_type: uri
        example_predicate: scales:hasRelatedCase
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: scales:/CivilCase/akd;;1:16-cv-00009
        example_object_type: scales_CivilCase
        example_predicate: scales:hasRelatedCase
        example_subject: scales:/CivilCase/akd;;1:16-cv-00018
        example_subject_type: scales_CivilCase
    - object:
        example_object: scales:/CriminalCase/iand;;1:17-cr-00012
        example_object_type: scales_CriminalCase
        example_predicate: scales:hasRelatedCase
        example_subject: scales:/CivilCase/iand;;1:17-cv-00106
        example_subject_type: scales_CivilCase
    - object:
        example_object: scales:/CivilCase/alsd;;1:18-cv-00296
        example_object_type: uri
        example_predicate: scales:hasRelatedCase
        example_subject: scales:/CriminalCase/alsd;;1:16-cr-00008
        example_subject_type: scales_CriminalCase
    - object:
        example_object: scales:/CivilCase/alsd;;1:17-cv-00277
        example_object_type: scales_CivilCase
        example_predicate: scales:hasRelatedCase
        example_subject: scales:/CriminalCase/alsd;;1:16-cr-00015
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasRelatedCase
    alias: scales_hasRelatedCase
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: Any
    any_of:
    - range: uri
    - range: scales_CivilCase
    - range: scales_CriminalCase
  scales_hasIdbPristim5:
    name: scales_hasIdbPristim5
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbPristim5
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristim5
    alias: scales_hasIdbPristim5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFoffcd1:
    name: scales_hasIdbFoffcd1
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '4530.0'
        example_object_type: double
        example_predicate: scales:hasIdbFoffcd1
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFoffcd1
    alias: scales_hasIdbFoffcd1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTofflvl2:
    name: scales_hasIdbTofflvl2
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '3.0'
        example_object_type: double
        example_predicate: scales:hasIdbTofflvl2
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTofflvl2
    alias: scales_hasIdbTofflvl2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFiledate:
    name: scales_hasIdbFiledate
    annotations:
      datetime:
        tag: datetime
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '2016-01-04T00:00:00'
        example_object_type: datetime
        example_predicate: scales:hasIdbFiledate
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: '2016-02-03T00:00:00'
        example_object_type: datetime
        example_predicate: scales:hasIdbFiledate
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFiledate
    alias: scales_hasIdbFiledate
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: datetime
  scales_hasIdbUpdate:
    name: scales_hasIdbUpdate
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 01/01/1900
        example_object_type: string
        example_predicate: scales:hasIdbUpdate
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbUpdate
    alias: scales_hasIdbUpdate
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbD2foffcd1:
    name: scales_hasIdbD2foffcd1
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '4530.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2foffcd1
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2foffcd1
    alias: scales_hasIdbD2foffcd1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
        value: 406320
      scales_Party:
        tag: scales_Party
        value: 2155989
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/Agent/akd;;1:16-cv-00001_a1
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: scales:/Agent/akd;;1:16-cr-00001_a0
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    - object:
        example_object: scales:Agent/ga-clayton-magistrate-civil;;0:00-cm-00001_a2
        example_object_type: scales_Party
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty
        example_subject: scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: scales:Agent/ga-clayton-magistrate;;0:00-bc-00001_a0
        example_object_type: scales_Party
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty
        example_subject: scales:Case/ga-clayton-magistrate;;0:00-bc-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: Any
    any_of:
    - range: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - range: scales_Party
  scales_hasIdbFinetot:
    name: scales_hasIdbFinetot
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbFinetot
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFinetot
    alias: scales_hasIdbFinetot
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTofflvl4:
    name: scales_hasIdbTofflvl4
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTofflvl4
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTofflvl4
    alias: scales_hasIdbTofflvl4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbAppcd:
    name: scales_hasIdbAppcd
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1'
        example_object_type: string
        example_predicate: scales:hasIdbAppcd
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbAppcd
    alias: scales_hasIdbAppcd
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbPriscd4:
    name: scales_hasIdbPriscd4
    annotations:
      integer:
        tag: integer
        value: 16399
      string:
        tag: string
        value: 105386
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbPriscd4
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbPriscd4
        example_subject: scales:/CriminalCase/azd;;4:16-cr-01355
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPriscd4
    alias: scales_hasIdbPriscd4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: string
    - range: integer
  scales_hasIdbCircuit:
    name: scales_hasIdbCircuit
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '9.0'
        example_object_type: double
        example_predicate: scales:hasIdbCircuit
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: '9.0'
        example_object_type: double
        example_predicate: scales:hasIdbCircuit
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCircuit
    alias: scales_hasIdbCircuit
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: double
  scales_hasIdbCttrr:
    name: scales_hasIdbCttrr
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCttrr
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCttrr
    alias: scales_hasIdbCttrr
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTypereg:
    name: scales_hasIdbTypereg
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: CR
        example_object_type: string
        example_predicate: scales:hasIdbTypereg
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTypereg
    alias: scales_hasIdbTypereg
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbD2toffcd1:
    name: scales_hasIdbD2toffcd1
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '4530.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2toffcd1
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2toffcd1
    alias: scales_hasIdbD2toffcd1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFsev1:
    name: scales_hasIdbFsev1
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: C19
        example_object_type: string
        example_predicate: scales:hasIdbFsev1
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFsev1
    alias: scales_hasIdbFsev1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Court:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Court
        value: 145961
      string:
        tag: string
        value: 2131186
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/Court/akd
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Court
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: scales:/Court/akd
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Court
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    - object:
        example_object: ga-clayton-magistrate-civil
        example_object_type: string
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt
        example_subject: scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: ga-clayton-magistrate
        example_object_type: string
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt
        example_subject: scales:Case/ga-clayton-magistrate;;0:00-bc-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: Any
    any_of:
    - range: string
    - range: http___release.niem.gov_niem_domains_jxdm_7.2_Court
  scales_hasIdbPriscd5:
    name: scales_hasIdbPriscd5
    annotations:
      integer:
        tag: integer
        value: 56347
      string:
        tag: string
        value: 65438
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbPriscd5
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbPriscd5
        example_subject: scales:/CriminalCase/akd;;1:17-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPriscd5
    alias: scales_hasIdbPriscd5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: string
    - range: integer
  scales_hasIdbInt1:
    name: scales_hasIdbInt1
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbInt1
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbInt1
    alias: scales_hasIdbInt1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTofflvl5:
    name: scales_hasIdbTofflvl5
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTofflvl5
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTofflvl5
    alias: scales_hasIdbTofflvl5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbCtdef:
    name: scales_hasIdbCtdef
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1.0'
        example_object_type: double
        example_predicate: scales:hasIdbCtdef
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtdef
    alias: scales_hasIdbCtdef
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbProbcd3:
    name: scales_hasIdbProbcd3
    annotations:
      integer:
        tag: integer
        value: 50115
      string:
        tag: string
        value: 71670
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbProbcd3
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbProbcd3
        example_subject: scales:/CriminalCase/ared;;4:17-cr-00002
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbcd3
    alias: scales_hasIdbProbcd3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: string
    - range: integer
  scales_hasIdbFofflvl1:
    name: scales_hasIdbFofflvl1
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '3.0'
        example_object_type: double
        example_predicate: scales:hasIdbFofflvl1
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFofflvl1
    alias: scales_hasIdbFofflvl1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbProcdate:
    name: scales_hasIdbProcdate
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 02/03/2016
        example_object_type: string
        example_predicate: scales:hasIdbProcdate
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProcdate
    alias: scales_hasIdbProcdate
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbDefno:
    name: scales_hasIdbDefno
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1.0'
        example_object_type: double
        example_predicate: scales:hasIdbDefno
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDefno
    alias: scales_hasIdbDefno
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_Party:
    name: scales_Party
    annotations:
      scales_Party:
        tag: scales_Party
        value: 19710
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/Agent/akd;;1:16-cv-00008_a7
        example_object_type: scales_Party
        example_predicate: scales:Party
        example_subject: scales:/CivilCase/akd;;1:16-cv-00008
        example_subject_type: scales_CivilCase
    - object:
        example_object: scales:/Agent/almd;;1:16-cr-00571_a3
        example_object_type: scales_Party
        example_predicate: scales:Party
        example_subject: scales:/CriminalCase/almd;;1:16-cr-00571
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:Party
    alias: scales_Party
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: scales_Party
  scales_hasIdbInt2:
    name: scales_hasIdbInt2
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbInt2
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbInt2
    alias: scales_hasIdbInt2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTsev2:
    name: scales_hasIdbTsev2
    annotations:
      integer:
        tag: integer
        value: 7475
      string:
        tag: string
        value: 114310
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: C19
        example_object_type: string
        example_predicate: scales:hasIdbTsev2
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbTsev2
        example_subject: scales:/CriminalCase/ilnd;;1:20-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTsev2
    alias: scales_hasIdbTsev2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: string
    - range: integer
  scales_hasIdbStatuscd:
    name: scales_hasIdbStatuscd
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: L
        example_object_type: string
        example_predicate: scales:hasIdbStatuscd
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: J
        example_object_type: string
        example_predicate: scales:hasIdbStatuscd
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbStatuscd
    alias: scales_hasIdbStatuscd
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: string
  scales_hasIdbSupvrel1:
    name: scales_hasIdbSupvrel1
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '12.0'
        example_object_type: double
        example_predicate: scales:hasIdbSupvrel1
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSupvrel1
    alias: scales_hasIdbSupvrel1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbCtfiltrn:
    name: scales_hasIdbCtfiltrn
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1.0'
        example_object_type: double
        example_predicate: scales:hasIdbCtfiltrn
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtfiltrn
    alias: scales_hasIdbCtfiltrn
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFoffcd4:
    name: scales_hasIdbFoffcd4
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFoffcd4
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFoffcd4
    alias: scales_hasIdbFoffcd4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbD2foffcd3:
    name: scales_hasIdbD2foffcd3
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2foffcd3
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2foffcd3
    alias: scales_hasIdbD2foffcd3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbProbtot:
    name: scales_hasIdbProbtot
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbProbtot
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbtot
    alias: scales_hasIdbProbtot
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTtitle1:
    name: scales_hasIdbTtitle1
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 26:7203C.M
        example_object_type: string
        example_predicate: scales:hasIdbTtitle1
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTtitle1
    alias: scales_hasIdbTtitle1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
        value: 146490
      scales_Party:
        tag: scales_Party
        value: 2066409
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/Agent/akd;;1:16-cv-00001_a0
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: scales:/Agent/akd;;1:16-cr-00001_a1
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    - object:
        example_object: scales:Agent/ga-clayton-magistrate-civil;;0:00-cm-00001_a0
        example_object_type: scales_Party
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty
        example_subject: scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: scales:Agent/ga-clayton-magistrate;;0:00-co-00002_a0
        example_object_type: scales_Party
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty
        example_subject: scales:Case/ga-clayton-magistrate;;0:00-co-00002
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: Any
    any_of:
    - range: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    - range: scales_Party
  scales_hasIdbTrandef:
    name: scales_hasIdbTrandef
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTrandef
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTrandef
    alias: scales_hasIdbTrandef
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbD2toffcd3:
    name: scales_hasIdbD2toffcd3
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2toffcd3
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2toffcd3
    alias: scales_hasIdbD2toffcd3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbPriscd1:
    name: scales_hasIdbPriscd1
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: S003
        example_object_type: string
        example_predicate: scales:hasIdbPriscd1
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPriscd1
    alias: scales_hasIdbPriscd1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbD2foffcd5:
    name: scales_hasIdbD2foffcd5
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2foffcd5
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2foffcd5
    alias: scales_hasIdbD2foffcd5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbProbcd4:
    name: scales_hasIdbProbcd4
    annotations:
      integer:
        tag: integer
        value: 70539
      string:
        tag: string
        value: 51246
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbProbcd4
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbProbcd4
        example_subject: scales:/CriminalCase/almd;;1:17-cr-00011
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbcd4
    alias: scales_hasIdbProbcd4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: string
    - range: integer
  scales_hasIdbDisp1:
    name: scales_hasIdbDisp1
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '4.0'
        example_object_type: double
        example_predicate: scales:hasIdbDisp1
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDisp1
    alias: scales_hasIdbDisp1
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbProccd:
    name: scales_hasIdbProccd
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '2.0'
        example_object_type: double
        example_predicate: scales:hasIdbProccd
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProccd
    alias: scales_hasIdbProccd
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbProbcd5:
    name: scales_hasIdbProbcd5
    annotations:
      integer:
        tag: integer
        value: 111249
      string:
        tag: string
        value: 10536
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbProbcd5
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbProbcd5
        example_subject: scales:/CriminalCase/akd;;1:17-cr-00015
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbcd5
    alias: scales_hasIdbProbcd5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: Any
    any_of:
    - range: string
    - range: integer
  scales_hasIdbSupvrel3:
    name: scales_hasIdbSupvrel3
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbSupvrel3
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSupvrel3
    alias: scales_hasIdbSupvrel3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbInt3:
    name: scales_hasIdbInt3
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '174.0'
        example_object_type: double
        example_predicate: scales:hasIdbInt3
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbInt3
    alias: scales_hasIdbInt3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbPriscd2:
    name: scales_hasIdbPriscd2
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: S001
        example_object_type: string
        example_predicate: scales:hasIdbPriscd2
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPriscd2
    alias: scales_hasIdbPriscd2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbFsev3:
    name: scales_hasIdbFsev3
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFsev3
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFsev3
    alias: scales_hasIdbFsev3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  scales_hasIdbProbmon5:
    name: scales_hasIdbProbmon5
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbProbmon5
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbmon5
    alias: scales_hasIdbProbmon5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFofflvl3:
    name: scales_hasIdbFofflvl3
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFofflvl3
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFofflvl3
    alias: scales_hasIdbFofflvl3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbDisp4:
    name: scales_hasIdbDisp4
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbDisp4
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDisp4
    alias: scales_hasIdbDisp4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbFoffcd2:
    name: scales_hasIdbFoffcd2
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFoffcd2
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFoffcd2
    alias: scales_hasIdbFoffcd2
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbTtitle4:
    name: scales_hasIdbTtitle4
    annotations:
      string:
        tag: string
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTtitle4
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTtitle4
    alias: scales_hasIdbTtitle4
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: string
  niem50_CaseGeneralCategoryText:
    name: niem50_CaseGeneralCategoryText
    annotations:
      string:
        tag: string
        value: 2277147
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: civil
        example_object_type: string
        example_predicate: niem50:CaseGeneralCategoryText
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: criminal
        example_object_type: string
        example_predicate: niem50:CaseGeneralCategoryText
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: niem50:CaseGeneralCategoryText
    alias: niem50_CaseGeneralCategoryText
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: string
  scales_hasIdbDisp3:
    name: scales_hasIdbDisp3
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbDisp3
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDisp3
    alias: scales_hasIdbDisp3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbToffcd5:
    name: scales_hasIdbToffcd5
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbToffcd5
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbToffcd5
    alias: scales_hasIdbToffcd5
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
  scales_hasIdbIs_stub:
    name: scales_hasIdbIs_stub
    annotations:
      boolean:
        tag: boolean
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 'false'
        example_object_type: boolean
        example_predicate: scales:hasIdbIs_stub
        example_subject: scales:/CivilCase/akd;;1:16-cv-00001
        example_subject_type: scales_CivilCase
    - object:
        example_object: 'false'
        example_object_type: boolean
        example_predicate: scales:hasIdbIs_stub
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbIs_stub
    alias: scales_hasIdbIs_stub
    owner: scales_CriminalCase
    domain_of:
    - scales_CivilCase
    - scales_CriminalCase
    range: boolean
  scales_hasIdbPristim3:
    name: scales_hasIdbPristim3
    annotations:
      double:
        tag: double
        value: 121785
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbPristim3
        example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
        example_subject_type: scales_CriminalCase
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristim3
    alias: scales_hasIdbPristim3
    owner: scales_CriminalCase
    domain_of:
    - scales_CriminalCase
    range: double
class_uri: scales:CriminalCase

```
</details>