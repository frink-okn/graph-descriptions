

# Class: No class (type) name specified (http___release.niem.gov_niem_domains_jxdm_7.2_Case)


_No class (type) description specified_






This class occurs 2 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/Case](http://release.niem.gov/niem/domains/jxdm/7.2/Case)






```mermaid
 classDiagram
    class HttpRelease.niem.govNiemDomainsJxdm7.2Case
    click HttpRelease.niem.govNiemDomainsJxdm7.2Case href "../HttpRelease.niem.govNiemDomainsJxdm7.2Case"
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" HttpRelease.niem.govNiemDomainsJxdm7.2Charge : http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge
    click HttpRelease.niem.govNiemDomainsJxdm7.2Charge href "../HttpRelease.niem.govNiemDomainsJxdm7.2Charge"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" HttpRelease.niem.govNiemDomainsJxdm7.2Court : http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt
    click HttpRelease.niem.govNiemDomainsJxdm7.2Court href "../HttpRelease.niem.govNiemDomainsJxdm7.2Court"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty : http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    click HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty href "../HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty : http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    click HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty href "../HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Uri : http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
    click Uri href "../Uri"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Any : http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
    click Any href "../Any"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : http___release.niem.gov_niem_domains_jxdm_7.2_StatuteKeywordText
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : http___release.niem.gov_niem_domains_jxdm_7.2_StatuteKeywordText
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : niem50_CaseDocketID
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : niem50_CaseDocketID
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : niem50_CaseGeneralCategoryText
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : niem50_CaseGeneralCategoryText
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : niem50_CaseSubCategoryText
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : niem50_CaseSubCategoryText
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : niem50_EndDate
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Date : niem50_EndDate
    click Date href "../Date"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : niem50_JurisdictionText
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : niem50_JurisdictionText
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : niem50_StartDate
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Date : niem50_StartDate
    click Date href "../Date"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : niem50_StatusDescriptionText
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : niem50_StatusDescriptionText
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbAmtrec
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbAmtrec
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbAppcd
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbAppcd
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbAppdate
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbAppdate
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbArbit
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbArbit
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbCaslgky
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbCaslgky
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbCircuit
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbCircuit
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbClassact
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbClassact
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbCounty
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbCounty
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbCtdef
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbCtdef
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbCtfil
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbCtfil
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbCtfilr
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbCtfilr
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbCtfiltrn
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbCtfiltrn
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbCtfilwor
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbCtfilwor
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbCtpn
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbCtpn
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbCtpnwof
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbCtpnwof
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbCttr
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbCttr
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbCttrr
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbCttrr
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbCttrtrn
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbCttrtrn
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbCttrwor
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbCttrwor
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbD2foffcd1
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbD2foffcd1
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbD2foffcd2
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbD2foffcd2
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbD2foffcd3
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbD2foffcd3
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbD2foffcd4
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbD2foffcd4
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbD2foffcd5
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbD2foffcd5
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbD2toffcd1
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbD2toffcd1
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbD2toffcd2
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbD2toffcd2
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbD2toffcd3
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbD2toffcd3
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbD2toffcd4
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbD2toffcd4
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbD2toffcd5
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbD2toffcd5
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbDef
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbDef
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbDeflgky
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbDeflgky
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbDefno
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbDefno
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbDemanded
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbDemanded
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbDisp
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbDisp
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbDisp1
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbDisp1
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbDisp2
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbDisp2
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbDisp3
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbDisp3
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbDisp4
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbDisp4
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbDisp5
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbDisp5
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbDispdate
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbDispdate
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbDistrict
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbDistrict
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbDjoined
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbDjoined
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbDocket
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbDocket
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFcounsel
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbFcounsel
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFdateuse
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbFdateuse
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFgenddate
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbFgenddate
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFgstrtdate
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbFgstrtdate
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFiledate
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Datetime : scales_hasIdbFiledate
    click Datetime href "../Datetime"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFineamt1
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbFineamt1
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFineamt2
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbFineamt2
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFineamt3
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbFineamt3
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFineamt4
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbFineamt4
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFineamt5
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbFineamt5
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFinetot
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbFinetot
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFiscalyr
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbFiscalyr
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFoffcd1
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbFoffcd1
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFoffcd2
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbFoffcd2
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFoffcd3
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbFoffcd3
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFoffcd4
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbFoffcd4
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFoffcd5
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbFoffcd5
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFofflvl1
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbFofflvl1
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFofflvl2
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbFofflvl2
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFofflvl3
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbFofflvl3
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFofflvl4
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbFofflvl4
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFofflvl5
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbFofflvl5
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFsev1
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbFsev1
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFsev2
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbFsev2
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFsev3
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbFsev3
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFsev4
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbFsev4
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFsev5
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbFsev5
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFtitle1
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbFtitle1
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFtitle2
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbFtitle2
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFtitle3
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbFtitle3
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFtitle4
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbFtitle4
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFtitle5
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbFtitle5
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbFugstat
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbFugstat
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbIfp
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbIfp
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbInt1
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbInt1
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbInt2
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbInt2
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbInt3
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbInt3
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbIs_stub
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Boolean : scales_hasIdbIs_stub
    click Boolean href "../Boolean"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbJudgment
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbJudgment
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbJuris
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbJuris
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbJury
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbJury
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbLoaddate
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbLoaddate
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbMagdef
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbMagdef
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbMagdock
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbMagdock
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbMdldock
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbMdldock
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbNoj
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbNoj
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbNos
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbNos
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbOffice
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbOffice
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbOrigin
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbOrigin
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbPlt
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbPlt
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbPretrial
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbPretrial
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbPriscd1
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbPriscd1
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbPriscd2
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbPriscd2
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbPriscd3
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbPriscd3
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbPriscd4
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbPriscd4
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbPriscd5
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Any : scales_hasIdbPriscd5
    click Any href "../Any"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbPristim1
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbPristim1
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbPristim2
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbPristim2
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbPristim3
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbPristim3
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbPristim4
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbPristim4
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbPristim5
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbPristim5
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbPristot
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbPristot
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbProbcd1
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbProbcd1
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbProbcd2
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Any : scales_hasIdbProbcd2
    click Any href "../Any"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbProbcd3
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Any : scales_hasIdbProbcd3
    click Any href "../Any"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbProbcd4
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Any : scales_hasIdbProbcd4
    click Any href "../Any"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbProbcd5
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Integer : scales_hasIdbProbcd5
    click Integer href "../Integer"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbProbmon1
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbProbmon1
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbProbmon2
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbProbmon2
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbProbmon3
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbProbmon3
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbProbmon4
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbProbmon4
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbProbmon5
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbProbmon5
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbProbtot
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbProbtot
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbProccd
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbProccd
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbProcdate
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbProcdate
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbProcprog
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbProcprog
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbProse
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbProse
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbReopseq
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbReopseq
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbResidenc
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbResidenc
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbSection
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbSection
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbSentdate
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbSentdate
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbStatuscd
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbStatuscd
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbSubsect
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbSubsect
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbSupvrel1
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbSupvrel1
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbSupvrel2
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbSupvrel2
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbSupvrel3
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbSupvrel3
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbSupvrel4
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbSupvrel4
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbSupvrel5
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbSupvrel5
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTapeyear
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbTapeyear
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTcounsel
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbTcounsel
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTdateuse
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbTdateuse
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTermdate
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Datetime : scales_hasIdbTermdate
    click Datetime href "../Datetime"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTermoff
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Integer : scales_hasIdbTermoff
    click Integer href "../Integer"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTitl
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbTitl
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbToffcd1
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbToffcd1
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbToffcd2
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbToffcd2
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbToffcd3
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbToffcd3
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbToffcd4
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbToffcd4
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbToffcd5
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbToffcd5
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTofflvl1
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbTofflvl1
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTofflvl2
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbTofflvl2
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTofflvl3
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbTofflvl3
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTofflvl4
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbTofflvl4
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTofflvl5
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbTofflvl5
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTrandef
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbTrandef
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTrandist
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Integer : scales_hasIdbTrandist
    click Integer href "../Integer"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTrandock
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbTrandock
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTranoff
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Integer : scales_hasIdbTranoff
    click Integer href "../Integer"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTransdoc
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbTransdoc
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTransoff
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbTransoff
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTransorg
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbTransorg
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTrclact
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbTrclact
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTrialend
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbTrialend
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTribegan
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbTribegan
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTrmarb
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbTrmarb
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTsev1
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbTsev1
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTsev2
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbTsev2
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTsev3
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbTsev3
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTsev4
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbTsev4
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTsev5
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbTsev5
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTtitle1
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbTtitle1
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTtitle2
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbTtitle2
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTtitle3
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbTtitle3
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTtitle4
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbTtitle4
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTtitle5
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbTtitle5
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTypemag
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbTypemag
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTypereg
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbTypereg
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbTypetrn
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Any : scales_hasIdbTypetrn
    click Any href "../Any"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbUpdate
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" String : scales_hasIdbUpdate
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasIdbVer
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Double : scales_hasIdbVer
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasMemberCase
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Any : scales_hasMemberCase
    click Any href "../Any"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_hasRelatedCase
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" Any : scales_hasRelatedCase
    click Any href "../Any"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Case : scales_Party
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Case --> "0..1" ScalesParty : scales_Party
    click ScalesParty href "../ScalesParty"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [scales_hasIdbPretrial](../slots/scales_hasIdbPretrial.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 185 |
| [scales_hasMemberCase](../slots/scales_hasMemberCase.md) | 0..1 <br/> [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md)&nbsp;or&nbsp;<br />[ScalesCase](../classes/ScalesCase.md) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbAppcd](../slots/scales_hasIdbAppcd.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 4 |
| [scales_hasIdbTitl](../slots/scales_hasIdbTitl.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 19 |
| [scales_hasIdbToffcd4](../slots/scales_hasIdbToffcd4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 12 |
| [scales_hasIdbFoffcd4](../slots/scales_hasIdbFoffcd4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 22 |
| [scales_hasIdbReopseq](../slots/scales_hasIdbReopseq.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 1 |
| [scales_hasIdbTsev3](../slots/scales_hasIdbTsev3.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 16 |
| [niem50_StatusDescriptionText](../slots/niem50_StatusDescriptionText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 4 |
| [scales_hasIdbDisp](../slots/scales_hasIdbDisp.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 19 |
| [scales_hasIdbFiscalyr](../slots/scales_hasIdbFiscalyr.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbTofflvl2](../slots/scales_hasIdbTofflvl2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 4 |
| [scales_hasIdbFgenddate](../slots/scales_hasIdbFgenddate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 167 |
| [scales_hasIdbTsev4](../slots/scales_hasIdbTsev4.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 13 |
| [scales_hasIdbDemanded](../slots/scales_hasIdbDemanded.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 92 |
| [scales_hasIdbCtpnwof](../slots/scales_hasIdbCtpnwof.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbProbmon5](../slots/scales_hasIdbProbmon5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbClassact](../slots/scales_hasIdbClassact.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbProbmon4](../slots/scales_hasIdbProbmon4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbFdateuse](../slots/scales_hasIdbFdateuse.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 9 |
| [scales_hasIdbSupvrel1](../slots/scales_hasIdbSupvrel1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 12 |
| [scales_hasIdbDisp1](../slots/scales_hasIdbDisp1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 10 |
| [scales_hasIdbPriscd3](../slots/scales_hasIdbPriscd3.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 3 |
| [scales_hasIdbPristim1](../slots/scales_hasIdbPristim1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 68 |
| [scales_hasIdbSupvrel3](../slots/scales_hasIdbSupvrel3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 6 |
| [scales_hasIdbUpdate](../slots/scales_hasIdbUpdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 1 |
| [scales_hasIdbProbtot](../slots/scales_hasIdbProbtot.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 8 |
| [scales_hasIdbCtfil](../slots/scales_hasIdbCtfil.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbFgstrtdate](../slots/scales_hasIdbFgstrtdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 176 |
| [scales_hasIdbTsev5](../slots/scales_hasIdbTsev5.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 7 |
| [scales_hasIdbD2toffcd2](../slots/scales_hasIdbD2toffcd2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 28 |
| [scales_hasIdbTribegan](../slots/scales_hasIdbTribegan.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 12 |
| [scales_hasIdbD2toffcd1](../slots/scales_hasIdbD2toffcd1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 41 |
| [scales_hasIdbMagdef](../slots/scales_hasIdbMagdef.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 3 |
| [scales_hasIdbProbcd3](../slots/scales_hasIdbProbcd3.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbTtitle4](../slots/scales_hasIdbTtitle4.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 14 |
| [scales_hasIdbTrclact](../slots/scales_hasIdbTrclact.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 3 |
| [scales_hasIdbDisp2](../slots/scales_hasIdbDisp2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 5 |
| [scales_hasIdbFtitle5](../slots/scales_hasIdbFtitle5.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 17 |
| [scales_hasIdbProse](../slots/scales_hasIdbProse.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 4 |
| [scales_hasIdbSentdate](../slots/scales_hasIdbSentdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 258 |
| [niem50_CaseSubCategoryText](../slots/niem50_CaseSubCategoryText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 69 |
| [scales_hasIdbCttrr](../slots/scales_hasIdbCttrr.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 1 |
| [scales_hasIdbFtitle2](../slots/scales_hasIdbFtitle2.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 87 |
| [scales_hasIdbSection](../slots/scales_hasIdbSection.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 114 |
| [scales_hasIdbPristim2](../slots/scales_hasIdbPristim2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 37 |
| [scales_hasIdbIfp](../slots/scales_hasIdbIfp.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbTdateuse](../slots/scales_hasIdbTdateuse.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 56 |
| [scales_hasIdbTermdate](../slots/scales_hasIdbTermdate.md) | 0..1 <br/> [xsd:dateTime](http://www.w3.org/2001/XMLSchema#dateTime) | No slot (predicate) description specified <br/>  | direct | 808 |
| [scales_hasIdbPriscd2](../slots/scales_hasIdbPriscd2.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 6 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty.md) | 0..1 <br/> [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | No slot (predicate) description specified <br/>  | direct | 8389 |
| [scales_hasIdbInt2](../slots/scales_hasIdbInt2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 61 |
| [scales_hasIdbProbmon2](../slots/scales_hasIdbProbmon2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 3 |
| [scales_hasIdbToffcd3](../slots/scales_hasIdbToffcd3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 17 |
| [scales_hasIdbFineamt4](../slots/scales_hasIdbFineamt4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 2 |
| [niem50_CaseGeneralCategoryText](../slots/niem50_CaseGeneralCategoryText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbTrandef](../slots/scales_hasIdbTrandef.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 1 |
| [scales_hasIdbToffcd5](../slots/scales_hasIdbToffcd5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 7 |
| [scales_hasIdbProbcd1](../slots/scales_hasIdbProbcd1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 3 |
| [scales_hasIdbDocket](../slots/scales_hasIdbDocket.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 4927 |
| [scales_hasIdbToffcd2](../slots/scales_hasIdbToffcd2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 26 |
| [scales_hasIdbD2toffcd4](../slots/scales_hasIdbD2toffcd4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 12 |
| [scales_hasIdbLoaddate](../slots/scales_hasIdbLoaddate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 26 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty.md) | 0..1 <br/> [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | No slot (predicate) description specified <br/>  | direct | 5633 |
| [scales_hasIdbTransorg](../slots/scales_hasIdbTransorg.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 1 |
| [scales_hasIdbCttr](../slots/scales_hasIdbCttr.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbProbmon3](../slots/scales_hasIdbProbmon3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbVer](../slots/scales_hasIdbVer.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 4 |
| [scales_hasIdbFofflvl4](../slots/scales_hasIdbFofflvl4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 4 |
| [scales_hasIdbDjoined](../slots/scales_hasIdbDjoined.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 237 |
| [scales_hasIdbProccd](../slots/scales_hasIdbProccd.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 8 |
| [scales_hasIdbDistrict](../slots/scales_hasIdbDistrict.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbTrmarb](../slots/scales_hasIdbTrmarb.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 1 |
| [scales_hasIdbFoffcd3](../slots/scales_hasIdbFoffcd3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 35 |
| [scales_hasIdbFofflvl1](../slots/scales_hasIdbFofflvl1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 3 |
| [scales_hasIdbDispdate](../slots/scales_hasIdbDispdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 293 |
| [scales_hasIdbTrandock](../slots/scales_hasIdbTrandock.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 1 |
| [scales_hasIdbFsev3](../slots/scales_hasIdbFsev3.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 38 |
| [scales_hasIdbAppdate](../slots/scales_hasIdbAppdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 234 |
| [scales_hasIdbFoffcd5](../slots/scales_hasIdbFoffcd5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 12 |
| [scales_hasIdbAmtrec](../slots/scales_hasIdbAmtrec.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 18 |
| [scales_hasIdbDisp5](../slots/scales_hasIdbDisp5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 3 |
| [scales_hasIdbJudgment](../slots/scales_hasIdbJudgment.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 6 |
| [scales_hasIdbTofflvl5](../slots/scales_hasIdbTofflvl5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 3 |
| [scales_hasIdbTypemag](../slots/scales_hasIdbTypemag.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbFsev4](../slots/scales_hasIdbFsev4.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 25 |
| [scales_hasIdbProcdate](../slots/scales_hasIdbProcdate.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 176 |
| [scales_hasIdbSubsect](../slots/scales_hasIdbSubsect.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 83 |
| [scales_hasRelatedCase](../slots/scales_hasRelatedCase.md) | 0..1 <br/> [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[ScalesCase](../classes/ScalesCase.md) | No slot (predicate) description specified <br/>  | direct | 7 |
| [scales_hasIdbTypetrn](../slots/scales_hasIdbTypetrn.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbFoffcd2](../slots/scales_hasIdbFoffcd2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 44 |
| [scales_hasIdbD2foffcd1](../slots/scales_hasIdbD2foffcd1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 65 |
| [scales_hasIdbTofflvl3](../slots/scales_hasIdbTofflvl3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 4 |
| [scales_hasIdbCounty](../slots/scales_hasIdbCounty.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 31 |
| [scales_hasIdbNoj](../slots/scales_hasIdbNoj.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 7 |
| [scales_hasIdbDisp3](../slots/scales_hasIdbDisp3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 5 |
| [scales_hasIdbResidenc](../slots/scales_hasIdbResidenc.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 18 |
| [scales_hasIdbTrialend](../slots/scales_hasIdbTrialend.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 13 |
| [scales_hasIdbDisp4](../slots/scales_hasIdbDisp4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 4 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified <br/>  | direct | 6948 |
| [scales_hasIdbTtitle5](../slots/scales_hasIdbTtitle5.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 8 |
| [scales_hasIdbFineamt5](../slots/scales_hasIdbFineamt5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbTransoff](../slots/scales_hasIdbTransoff.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 1 |
| [scales_hasIdbPlt](../slots/scales_hasIdbPlt.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 1098 |
| [scales_hasIdbDefno](../slots/scales_hasIdbDefno.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbSupvrel2](../slots/scales_hasIdbSupvrel2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 9 |
| [scales_hasIdbFugstat](../slots/scales_hasIdbFugstat.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbFtitle4](../slots/scales_hasIdbFtitle4.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 35 |
| [scales_hasIdbTtitle1](../slots/scales_hasIdbTtitle1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 68 |
| [scales_hasIdbPriscd5](../slots/scales_hasIdbPriscd5.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbFiledate](../slots/scales_hasIdbFiledate.md) | 0..1 <br/> [xsd:dateTime](http://www.w3.org/2001/XMLSchema#dateTime) | No slot (predicate) description specified <br/>  | direct | 327 |
| [scales_hasIdbTofflvl4](../slots/scales_hasIdbTofflvl4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 4 |
| [scales_hasIdbCttrtrn](../slots/scales_hasIdbCttrtrn.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbTapeyear](../slots/scales_hasIdbTapeyear.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 10 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_StatuteKeywordText](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_StatuteKeywordText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 211 |
| [scales_hasIdbStatuscd](../slots/scales_hasIdbStatuscd.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 4 |
| [scales_hasIdbD2foffcd4](../slots/scales_hasIdbD2foffcd4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 24 |
| [scales_hasIdbInt1](../slots/scales_hasIdbInt1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 29 |
| [scales_hasIdbTermoff](../slots/scales_hasIdbTermoff.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbFcounsel](../slots/scales_hasIdbFcounsel.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 4 |
| [scales_hasIdbFoffcd1](../slots/scales_hasIdbFoffcd1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 60 |
| [scales_hasIdbTrandist](../slots/scales_hasIdbTrandist.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 1 |
| [scales_hasIdbInt3](../slots/scales_hasIdbInt3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 136 |
| [scales_hasIdbIs_stub](../slots/scales_hasIdbIs_stub.md) | 0..1 <br/> [xsd:boolean](http://www.w3.org/2001/XMLSchema#boolean) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbTcounsel](../slots/scales_hasIdbTcounsel.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 5 |
| [scales_hasIdbFineamt3](../slots/scales_hasIdbFineamt3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbArbit](../slots/scales_hasIdbArbit.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 1 |
| [scales_hasIdbDef](../slots/scales_hasIdbDef.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 1034 |
| [scales_hasIdbFofflvl2](../slots/scales_hasIdbFofflvl2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 4 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge.md) | 0..1 <br/> [HttpRelease.niem.govNiemDomainsJxdm7.2Charge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Charge.md) | No slot (predicate) description specified <br/>  | direct | 6280 |
| [scales_hasIdbTtitle2](../slots/scales_hasIdbTtitle2.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 40 |
| [scales_hasIdbTransdoc](../slots/scales_hasIdbTransdoc.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 1 |
| [scales_hasIdbPristim4](../slots/scales_hasIdbPristim4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 3 |
| [scales_hasIdbOffice](../slots/scales_hasIdbOffice.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbProbmon1](../slots/scales_hasIdbProbmon1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 8 |
| [scales_hasIdbTofflvl1](../slots/scales_hasIdbTofflvl1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 4 |
| [scales_hasIdbCtfilr](../slots/scales_hasIdbCtfilr.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 1 |
| [scales_hasIdbProbcd4](../slots/scales_hasIdbProbcd4.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbTsev1](../slots/scales_hasIdbTsev1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 44 |
| [niem50_StartDate](../slots/niem50_StartDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) | No slot (predicate) description specified <br/>  | direct | 327 |
| [scales_hasIdbFtitle3](../slots/scales_hasIdbFtitle3.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 57 |
| [scales_hasIdbOrigin](../slots/scales_hasIdbOrigin.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 6 |
| [scales_hasIdbPristot](../slots/scales_hasIdbPristot.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 68 |
| [scales_hasIdbProcprog](../slots/scales_hasIdbProcprog.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 13 |
| [scales_hasIdbCircuit](../slots/scales_hasIdbCircuit.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbDeflgky](../slots/scales_hasIdbDeflgky.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 3441 |
| [scales_hasIdbFtitle1](../slots/scales_hasIdbFtitle1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 114 |
| [scales_hasIdbCtpn](../slots/scales_hasIdbCtpn.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbCaslgky](../slots/scales_hasIdbCaslgky.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 3441 |
| [scales_hasIdbJury](../slots/scales_hasIdbJury.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 4 |
| [scales_hasIdbTypereg](../slots/scales_hasIdbTypereg.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbFsev2](../slots/scales_hasIdbFsev2.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 56 |
| [scales_hasIdbFofflvl5](../slots/scales_hasIdbFofflvl5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 3 |
| [scales_hasIdbD2toffcd3](../slots/scales_hasIdbD2toffcd3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 16 |
| [scales_hasIdbFsev5](../slots/scales_hasIdbFsev5.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 15 |
| [scales_hasIdbCtfiltrn](../slots/scales_hasIdbCtfiltrn.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 1 |
| [scales_hasIdbCtfilwor](../slots/scales_hasIdbCtfilwor.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 2 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions.md) | 0..1 <br/> [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction.md)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md) | No slot (predicate) description specified <br/>  | direct | 9999 |
| [scales_hasIdbSupvrel4](../slots/scales_hasIdbSupvrel4.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 3 |
| [scales_hasIdbFineamt1](../slots/scales_hasIdbFineamt1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 14 |
| [scales_hasIdbPriscd4](../slots/scales_hasIdbPriscd4.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbMdldock](../slots/scales_hasIdbMdldock.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 6 |
| [scales_hasIdbD2toffcd5](../slots/scales_hasIdbD2toffcd5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 7 |
| [scales_hasIdbTranoff](../slots/scales_hasIdbTranoff.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 1 |
| [scales_hasIdbNos](../slots/scales_hasIdbNos.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 69 |
| [scales_hasIdbTtitle3](../slots/scales_hasIdbTtitle3.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 20 |
| [scales_hasIdbFsev1](../slots/scales_hasIdbFsev1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 60 |
| [scales_hasIdbCtdef](../slots/scales_hasIdbCtdef.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbSupvrel5](../slots/scales_hasIdbSupvrel5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbProbcd5](../slots/scales_hasIdbProbcd5.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 1 |
| [scales_hasIdbJuris](../slots/scales_hasIdbJuris.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 4 |
| [niem50_EndDate](../slots/niem50_EndDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) | No slot (predicate) description specified <br/>  | direct | 1106 |
| [scales_hasIdbCttrwor](../slots/scales_hasIdbCttrwor.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 2 |
| [niem50_JurisdictionText](../slots/niem50_JurisdictionText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 4 |
| [scales_hasIdbFofflvl3](../slots/scales_hasIdbFofflvl3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 4 |
| [scales_hasIdbToffcd1](../slots/scales_hasIdbToffcd1.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 38 |
| [scales_hasIdbFinetot](../slots/scales_hasIdbFinetot.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 13 |
| [scales_hasIdbTsev2](../slots/scales_hasIdbTsev2.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 31 |
| [scales_hasIdbFineamt2](../slots/scales_hasIdbFineamt2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbMagdock](../slots/scales_hasIdbMagdock.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 3216 |
| [scales_Party](../slots/scales_Party.md) | 0..1 <br/> [ScalesParty](../classes/ScalesParty.md) | No slot (predicate) description specified <br/>  | direct | 2319 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt.md) | 0..1 <br/> [HttpRelease.niem.govNiemDomainsJxdm7.2Court](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Court.md) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbPriscd1](../slots/scales_hasIdbPriscd1.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 8 |
| [scales_hasIdbD2foffcd3](../slots/scales_hasIdbD2foffcd3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 37 |
| [scales_hasIdbD2foffcd2](../slots/scales_hasIdbD2foffcd2.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 51 |
| [scales_hasIdbPristim5](../slots/scales_hasIdbPristim5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 2 |
| [scales_hasIdbD2foffcd5](../slots/scales_hasIdbD2foffcd5.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 13 |
| [scales_hasIdbProbcd2](../slots/scales_hasIdbProbcd2.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | No slot (predicate) description specified <br/>  | direct | 4 |
| [niem50_CaseDocketID](../slots/niem50_CaseDocketID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 5000 |
| [scales_hasIdbPristim3](../slots/scales_hasIdbPristim3.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 15 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | [scales_hasMemberCase](../slots/scales_hasMemberCase.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | [scales_hasRelatedCase](../slots/scales_hasRelatedCase.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) |
| [ScalesCase](../classes/ScalesCase.md) | [scales_hasMemberCase](../slots/scales_hasMemberCase.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) |
| [ScalesCase](../classes/ScalesCase.md) | [scales_hasRelatedCase](../slots/scales_hasRelatedCase.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_Case
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 2
description: No class (type) description specified
title: No class (type) name specified
rank: 1000
slots:
- scales_hasIdbPretrial
- scales_hasMemberCase
- scales_hasIdbAppcd
- scales_hasIdbTitl
- scales_hasIdbToffcd4
- scales_hasIdbFoffcd4
- scales_hasIdbReopseq
- scales_hasIdbTsev3
- niem50_StatusDescriptionText
- scales_hasIdbDisp
- scales_hasIdbFiscalyr
- scales_hasIdbTofflvl2
- scales_hasIdbFgenddate
- scales_hasIdbTsev4
- scales_hasIdbDemanded
- scales_hasIdbCtpnwof
- scales_hasIdbProbmon5
- scales_hasIdbClassact
- scales_hasIdbProbmon4
- scales_hasIdbFdateuse
- scales_hasIdbSupvrel1
- scales_hasIdbDisp1
- scales_hasIdbPriscd3
- scales_hasIdbPristim1
- scales_hasIdbSupvrel3
- scales_hasIdbUpdate
- scales_hasIdbProbtot
- scales_hasIdbCtfil
- scales_hasIdbFgstrtdate
- scales_hasIdbTsev5
- scales_hasIdbD2toffcd2
- scales_hasIdbTribegan
- scales_hasIdbD2toffcd1
- scales_hasIdbMagdef
- scales_hasIdbProbcd3
- scales_hasIdbTtitle4
- scales_hasIdbTrclact
- scales_hasIdbDisp2
- scales_hasIdbFtitle5
- scales_hasIdbProse
- scales_hasIdbSentdate
- niem50_CaseSubCategoryText
- scales_hasIdbCttrr
- scales_hasIdbFtitle2
- scales_hasIdbSection
- scales_hasIdbPristim2
- scales_hasIdbIfp
- scales_hasIdbTdateuse
- scales_hasIdbTermdate
- scales_hasIdbPriscd2
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- scales_hasIdbInt2
- scales_hasIdbProbmon2
- scales_hasIdbToffcd3
- scales_hasIdbFineamt4
- niem50_CaseGeneralCategoryText
- scales_hasIdbTrandef
- scales_hasIdbToffcd5
- scales_hasIdbProbcd1
- scales_hasIdbDocket
- scales_hasIdbToffcd2
- scales_hasIdbD2toffcd4
- scales_hasIdbLoaddate
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
- scales_hasIdbTransorg
- scales_hasIdbCttr
- scales_hasIdbProbmon3
- scales_hasIdbVer
- scales_hasIdbFofflvl4
- scales_hasIdbDjoined
- scales_hasIdbProccd
- scales_hasIdbDistrict
- scales_hasIdbTrmarb
- scales_hasIdbFoffcd3
- scales_hasIdbFofflvl1
- scales_hasIdbDispdate
- scales_hasIdbTrandock
- scales_hasIdbFsev3
- scales_hasIdbAppdate
- scales_hasIdbFoffcd5
- scales_hasIdbAmtrec
- scales_hasIdbDisp5
- scales_hasIdbJudgment
- scales_hasIdbTofflvl5
- scales_hasIdbTypemag
- scales_hasIdbFsev4
- scales_hasIdbProcdate
- scales_hasIdbSubsect
- scales_hasRelatedCase
- scales_hasIdbTypetrn
- scales_hasIdbFoffcd2
- scales_hasIdbD2foffcd1
- scales_hasIdbTofflvl3
- scales_hasIdbCounty
- scales_hasIdbNoj
- scales_hasIdbDisp3
- scales_hasIdbResidenc
- scales_hasIdbTrialend
- scales_hasIdbDisp4
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
- scales_hasIdbTtitle5
- scales_hasIdbFineamt5
- scales_hasIdbTransoff
- scales_hasIdbPlt
- scales_hasIdbDefno
- scales_hasIdbSupvrel2
- scales_hasIdbFugstat
- scales_hasIdbFtitle4
- scales_hasIdbTtitle1
- scales_hasIdbPriscd5
- scales_hasIdbFiledate
- scales_hasIdbTofflvl4
- scales_hasIdbCttrtrn
- scales_hasIdbTapeyear
- http___release.niem.gov_niem_domains_jxdm_7.2_StatuteKeywordText
- scales_hasIdbStatuscd
- scales_hasIdbD2foffcd4
- scales_hasIdbInt1
- scales_hasIdbTermoff
- scales_hasIdbFcounsel
- scales_hasIdbFoffcd1
- scales_hasIdbTrandist
- scales_hasIdbInt3
- scales_hasIdbIs_stub
- scales_hasIdbTcounsel
- scales_hasIdbFineamt3
- scales_hasIdbArbit
- scales_hasIdbDef
- scales_hasIdbFofflvl2
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge
- scales_hasIdbTtitle2
- scales_hasIdbTransdoc
- scales_hasIdbPristim4
- scales_hasIdbOffice
- scales_hasIdbProbmon1
- scales_hasIdbTofflvl1
- scales_hasIdbCtfilr
- scales_hasIdbProbcd4
- scales_hasIdbTsev1
- niem50_StartDate
- scales_hasIdbFtitle3
- scales_hasIdbOrigin
- scales_hasIdbPristot
- scales_hasIdbProcprog
- scales_hasIdbCircuit
- scales_hasIdbDeflgky
- scales_hasIdbFtitle1
- scales_hasIdbCtpn
- scales_hasIdbCaslgky
- scales_hasIdbJury
- scales_hasIdbTypereg
- scales_hasIdbFsev2
- scales_hasIdbFofflvl5
- scales_hasIdbD2toffcd3
- scales_hasIdbFsev5
- scales_hasIdbCtfiltrn
- scales_hasIdbCtfilwor
- http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
- scales_hasIdbSupvrel4
- scales_hasIdbFineamt1
- scales_hasIdbPriscd4
- scales_hasIdbMdldock
- scales_hasIdbD2toffcd5
- scales_hasIdbTranoff
- scales_hasIdbNos
- scales_hasIdbTtitle3
- scales_hasIdbFsev1
- scales_hasIdbCtdef
- scales_hasIdbSupvrel5
- scales_hasIdbProbcd5
- scales_hasIdbJuris
- niem50_EndDate
- scales_hasIdbCttrwor
- niem50_JurisdictionText
- scales_hasIdbFofflvl3
- scales_hasIdbToffcd1
- scales_hasIdbFinetot
- scales_hasIdbTsev2
- scales_hasIdbFineamt2
- scales_hasIdbMagdock
- scales_Party
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt
- scales_hasIdbPriscd1
- scales_hasIdbD2foffcd3
- scales_hasIdbD2foffcd2
- scales_hasIdbPristim5
- scales_hasIdbD2foffcd5
- scales_hasIdbProbcd2
- niem50_CaseDocketID
- scales_hasIdbPristim3
slot_usage:
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Charge:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
        value: 6280
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Court:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Court
        value: 2
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
        value: 8389
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
        value: 5633
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
    annotations:
      uri:
        tag: uri
        value: 6948
  http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
        value: 4999
      http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
        value: 5000
  http___release.niem.gov_niem_domains_jxdm_7.2_StatuteKeywordText:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_StatuteKeywordText
    annotations:
      string:
        tag: string
        value: 211
  niem50_CaseDocketID:
    name: niem50_CaseDocketID
    annotations:
      string:
        tag: string
        value: 5000
  niem50_CaseGeneralCategoryText:
    name: niem50_CaseGeneralCategoryText
    annotations:
      string:
        tag: string
        value: 2
  niem50_CaseSubCategoryText:
    name: niem50_CaseSubCategoryText
    annotations:
      string:
        tag: string
        value: 69
  niem50_EndDate:
    name: niem50_EndDate
    annotations:
      date:
        tag: date
        value: 1106
  niem50_JurisdictionText:
    name: niem50_JurisdictionText
    annotations:
      string:
        tag: string
        value: 4
  niem50_StartDate:
    name: niem50_StartDate
    annotations:
      date:
        tag: date
        value: 327
  niem50_StatusDescriptionText:
    name: niem50_StatusDescriptionText
    annotations:
      string:
        tag: string
        value: 4
  scales_Party:
    name: scales_Party
    annotations:
      scales_Party:
        tag: scales_Party
        value: 2319
  scales_hasIdbAmtrec:
    name: scales_hasIdbAmtrec
    annotations:
      double:
        tag: double
        value: 18
  scales_hasIdbAppcd:
    name: scales_hasIdbAppcd
    annotations:
      string:
        tag: string
        value: 4
  scales_hasIdbAppdate:
    name: scales_hasIdbAppdate
    annotations:
      string:
        tag: string
        value: 234
  scales_hasIdbArbit:
    name: scales_hasIdbArbit
    annotations:
      string:
        tag: string
        value: 1
  scales_hasIdbCaslgky:
    name: scales_hasIdbCaslgky
    annotations:
      string:
        tag: string
        value: 3441
  scales_hasIdbCircuit:
    name: scales_hasIdbCircuit
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbClassact:
    name: scales_hasIdbClassact
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbCounty:
    name: scales_hasIdbCounty
    annotations:
      double:
        tag: double
        value: 31
  scales_hasIdbCtdef:
    name: scales_hasIdbCtdef
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbCtfil:
    name: scales_hasIdbCtfil
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbCtfilr:
    name: scales_hasIdbCtfilr
    annotations:
      double:
        tag: double
        value: 1
  scales_hasIdbCtfiltrn:
    name: scales_hasIdbCtfiltrn
    annotations:
      double:
        tag: double
        value: 1
  scales_hasIdbCtfilwor:
    name: scales_hasIdbCtfilwor
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbCtpn:
    name: scales_hasIdbCtpn
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbCtpnwof:
    name: scales_hasIdbCtpnwof
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbCttr:
    name: scales_hasIdbCttr
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbCttrr:
    name: scales_hasIdbCttrr
    annotations:
      double:
        tag: double
        value: 1
  scales_hasIdbCttrtrn:
    name: scales_hasIdbCttrtrn
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbCttrwor:
    name: scales_hasIdbCttrwor
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbD2foffcd1:
    name: scales_hasIdbD2foffcd1
    annotations:
      double:
        tag: double
        value: 65
  scales_hasIdbD2foffcd2:
    name: scales_hasIdbD2foffcd2
    annotations:
      double:
        tag: double
        value: 51
  scales_hasIdbD2foffcd3:
    name: scales_hasIdbD2foffcd3
    annotations:
      double:
        tag: double
        value: 37
  scales_hasIdbD2foffcd4:
    name: scales_hasIdbD2foffcd4
    annotations:
      double:
        tag: double
        value: 24
  scales_hasIdbD2foffcd5:
    name: scales_hasIdbD2foffcd5
    annotations:
      double:
        tag: double
        value: 13
  scales_hasIdbD2toffcd1:
    name: scales_hasIdbD2toffcd1
    annotations:
      double:
        tag: double
        value: 41
  scales_hasIdbD2toffcd2:
    name: scales_hasIdbD2toffcd2
    annotations:
      double:
        tag: double
        value: 28
  scales_hasIdbD2toffcd3:
    name: scales_hasIdbD2toffcd3
    annotations:
      double:
        tag: double
        value: 16
  scales_hasIdbD2toffcd4:
    name: scales_hasIdbD2toffcd4
    annotations:
      double:
        tag: double
        value: 12
  scales_hasIdbD2toffcd5:
    name: scales_hasIdbD2toffcd5
    annotations:
      double:
        tag: double
        value: 7
  scales_hasIdbDef:
    name: scales_hasIdbDef
    annotations:
      string:
        tag: string
        value: 1034
  scales_hasIdbDeflgky:
    name: scales_hasIdbDeflgky
    annotations:
      string:
        tag: string
        value: 3441
  scales_hasIdbDefno:
    name: scales_hasIdbDefno
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbDemanded:
    name: scales_hasIdbDemanded
    annotations:
      double:
        tag: double
        value: 92
  scales_hasIdbDisp:
    name: scales_hasIdbDisp
    annotations:
      double:
        tag: double
        value: 19
  scales_hasIdbDisp1:
    name: scales_hasIdbDisp1
    annotations:
      double:
        tag: double
        value: 10
  scales_hasIdbDisp2:
    name: scales_hasIdbDisp2
    annotations:
      double:
        tag: double
        value: 5
  scales_hasIdbDisp3:
    name: scales_hasIdbDisp3
    annotations:
      double:
        tag: double
        value: 5
  scales_hasIdbDisp4:
    name: scales_hasIdbDisp4
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbDisp5:
    name: scales_hasIdbDisp5
    annotations:
      double:
        tag: double
        value: 3
  scales_hasIdbDispdate:
    name: scales_hasIdbDispdate
    annotations:
      string:
        tag: string
        value: 293
  scales_hasIdbDistrict:
    name: scales_hasIdbDistrict
    annotations:
      string:
        tag: string
        value: 2
  scales_hasIdbDjoined:
    name: scales_hasIdbDjoined
    annotations:
      string:
        tag: string
        value: 237
  scales_hasIdbDocket:
    name: scales_hasIdbDocket
    annotations:
      string:
        tag: string
        value: 4927
  scales_hasIdbFcounsel:
    name: scales_hasIdbFcounsel
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbFdateuse:
    name: scales_hasIdbFdateuse
    annotations:
      string:
        tag: string
        value: 9
  scales_hasIdbFgenddate:
    name: scales_hasIdbFgenddate
    annotations:
      string:
        tag: string
        value: 167
  scales_hasIdbFgstrtdate:
    name: scales_hasIdbFgstrtdate
    annotations:
      string:
        tag: string
        value: 176
  scales_hasIdbFiledate:
    name: scales_hasIdbFiledate
    annotations:
      datetime:
        tag: datetime
        value: 327
  scales_hasIdbFineamt1:
    name: scales_hasIdbFineamt1
    annotations:
      double:
        tag: double
        value: 14
  scales_hasIdbFineamt2:
    name: scales_hasIdbFineamt2
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbFineamt3:
    name: scales_hasIdbFineamt3
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbFineamt4:
    name: scales_hasIdbFineamt4
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbFineamt5:
    name: scales_hasIdbFineamt5
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbFinetot:
    name: scales_hasIdbFinetot
    annotations:
      double:
        tag: double
        value: 13
  scales_hasIdbFiscalyr:
    name: scales_hasIdbFiscalyr
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbFoffcd1:
    name: scales_hasIdbFoffcd1
    annotations:
      double:
        tag: double
        value: 60
  scales_hasIdbFoffcd2:
    name: scales_hasIdbFoffcd2
    annotations:
      double:
        tag: double
        value: 44
  scales_hasIdbFoffcd3:
    name: scales_hasIdbFoffcd3
    annotations:
      double:
        tag: double
        value: 35
  scales_hasIdbFoffcd4:
    name: scales_hasIdbFoffcd4
    annotations:
      double:
        tag: double
        value: 22
  scales_hasIdbFoffcd5:
    name: scales_hasIdbFoffcd5
    annotations:
      double:
        tag: double
        value: 12
  scales_hasIdbFofflvl1:
    name: scales_hasIdbFofflvl1
    annotations:
      double:
        tag: double
        value: 3
  scales_hasIdbFofflvl2:
    name: scales_hasIdbFofflvl2
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbFofflvl3:
    name: scales_hasIdbFofflvl3
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbFofflvl4:
    name: scales_hasIdbFofflvl4
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbFofflvl5:
    name: scales_hasIdbFofflvl5
    annotations:
      double:
        tag: double
        value: 3
  scales_hasIdbFsev1:
    name: scales_hasIdbFsev1
    annotations:
      string:
        tag: string
        value: 60
  scales_hasIdbFsev2:
    name: scales_hasIdbFsev2
    annotations:
      string:
        tag: string
        value: 56
  scales_hasIdbFsev3:
    name: scales_hasIdbFsev3
    annotations:
      string:
        tag: string
        value: 38
  scales_hasIdbFsev4:
    name: scales_hasIdbFsev4
    annotations:
      string:
        tag: string
        value: 25
  scales_hasIdbFsev5:
    name: scales_hasIdbFsev5
    annotations:
      string:
        tag: string
        value: 15
  scales_hasIdbFtitle1:
    name: scales_hasIdbFtitle1
    annotations:
      string:
        tag: string
        value: 114
  scales_hasIdbFtitle2:
    name: scales_hasIdbFtitle2
    annotations:
      string:
        tag: string
        value: 87
  scales_hasIdbFtitle3:
    name: scales_hasIdbFtitle3
    annotations:
      string:
        tag: string
        value: 57
  scales_hasIdbFtitle4:
    name: scales_hasIdbFtitle4
    annotations:
      string:
        tag: string
        value: 35
  scales_hasIdbFtitle5:
    name: scales_hasIdbFtitle5
    annotations:
      string:
        tag: string
        value: 17
  scales_hasIdbFugstat:
    name: scales_hasIdbFugstat
    annotations:
      string:
        tag: string
        value: 2
  scales_hasIdbIfp:
    name: scales_hasIdbIfp
    annotations:
      string:
        tag: string
        value: 2
  scales_hasIdbInt1:
    name: scales_hasIdbInt1
    annotations:
      double:
        tag: double
        value: 29
  scales_hasIdbInt2:
    name: scales_hasIdbInt2
    annotations:
      double:
        tag: double
        value: 61
  scales_hasIdbInt3:
    name: scales_hasIdbInt3
    annotations:
      double:
        tag: double
        value: 136
  scales_hasIdbIs_stub:
    name: scales_hasIdbIs_stub
    annotations:
      boolean:
        tag: boolean
        value: 2
  scales_hasIdbJudgment:
    name: scales_hasIdbJudgment
    annotations:
      double:
        tag: double
        value: 6
  scales_hasIdbJuris:
    name: scales_hasIdbJuris
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbJury:
    name: scales_hasIdbJury
    annotations:
      string:
        tag: string
        value: 4
  scales_hasIdbLoaddate:
    name: scales_hasIdbLoaddate
    annotations:
      string:
        tag: string
        value: 26
  scales_hasIdbMagdef:
    name: scales_hasIdbMagdef
    annotations:
      double:
        tag: double
        value: 3
  scales_hasIdbMagdock:
    name: scales_hasIdbMagdock
    annotations:
      double:
        tag: double
        value: 3216
  scales_hasIdbMdldock:
    name: scales_hasIdbMdldock
    annotations:
      string:
        tag: string
        value: 6
  scales_hasIdbNoj:
    name: scales_hasIdbNoj
    annotations:
      double:
        tag: double
        value: 7
  scales_hasIdbNos:
    name: scales_hasIdbNos
    annotations:
      string:
        tag: string
        value: 69
  scales_hasIdbOffice:
    name: scales_hasIdbOffice
    annotations:
      string:
        tag: string
        value: 2
  scales_hasIdbOrigin:
    name: scales_hasIdbOrigin
    annotations:
      double:
        tag: double
        value: 6
  scales_hasIdbPlt:
    name: scales_hasIdbPlt
    annotations:
      string:
        tag: string
        value: 1098
  scales_hasIdbPretrial:
    name: scales_hasIdbPretrial
    annotations:
      string:
        tag: string
        value: 185
  scales_hasIdbPriscd1:
    name: scales_hasIdbPriscd1
    annotations:
      string:
        tag: string
        value: 8
  scales_hasIdbPriscd2:
    name: scales_hasIdbPriscd2
    annotations:
      string:
        tag: string
        value: 6
  scales_hasIdbPriscd3:
    name: scales_hasIdbPriscd3
    annotations:
      string:
        tag: string
        value: 3
  scales_hasIdbPriscd4:
    name: scales_hasIdbPriscd4
    annotations:
      string:
        tag: string
        value: 2
  scales_hasIdbPriscd5:
    name: scales_hasIdbPriscd5
    annotations:
      integer:
        tag: integer
        value: 1
      string:
        tag: string
        value: 1
  scales_hasIdbPristim1:
    name: scales_hasIdbPristim1
    annotations:
      double:
        tag: double
        value: 68
  scales_hasIdbPristim2:
    name: scales_hasIdbPristim2
    annotations:
      double:
        tag: double
        value: 37
  scales_hasIdbPristim3:
    name: scales_hasIdbPristim3
    annotations:
      double:
        tag: double
        value: 15
  scales_hasIdbPristim4:
    name: scales_hasIdbPristim4
    annotations:
      double:
        tag: double
        value: 3
  scales_hasIdbPristim5:
    name: scales_hasIdbPristim5
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbPristot:
    name: scales_hasIdbPristot
    annotations:
      double:
        tag: double
        value: 68
  scales_hasIdbProbcd1:
    name: scales_hasIdbProbcd1
    annotations:
      string:
        tag: string
        value: 3
  scales_hasIdbProbcd2:
    name: scales_hasIdbProbcd2
    annotations:
      integer:
        tag: integer
        value: 1
      string:
        tag: string
        value: 3
  scales_hasIdbProbcd3:
    name: scales_hasIdbProbcd3
    annotations:
      integer:
        tag: integer
        value: 1
      string:
        tag: string
        value: 1
  scales_hasIdbProbcd4:
    name: scales_hasIdbProbcd4
    annotations:
      integer:
        tag: integer
        value: 1
      string:
        tag: string
        value: 1
  scales_hasIdbProbcd5:
    name: scales_hasIdbProbcd5
    annotations:
      integer:
        tag: integer
        value: 1
  scales_hasIdbProbmon1:
    name: scales_hasIdbProbmon1
    annotations:
      double:
        tag: double
        value: 8
  scales_hasIdbProbmon2:
    name: scales_hasIdbProbmon2
    annotations:
      double:
        tag: double
        value: 3
  scales_hasIdbProbmon3:
    name: scales_hasIdbProbmon3
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbProbmon4:
    name: scales_hasIdbProbmon4
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbProbmon5:
    name: scales_hasIdbProbmon5
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbProbtot:
    name: scales_hasIdbProbtot
    annotations:
      double:
        tag: double
        value: 8
  scales_hasIdbProccd:
    name: scales_hasIdbProccd
    annotations:
      double:
        tag: double
        value: 8
  scales_hasIdbProcdate:
    name: scales_hasIdbProcdate
    annotations:
      string:
        tag: string
        value: 176
  scales_hasIdbProcprog:
    name: scales_hasIdbProcprog
    annotations:
      double:
        tag: double
        value: 13
  scales_hasIdbProse:
    name: scales_hasIdbProse
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbReopseq:
    name: scales_hasIdbReopseq
    annotations:
      double:
        tag: double
        value: 1
  scales_hasIdbResidenc:
    name: scales_hasIdbResidenc
    annotations:
      double:
        tag: double
        value: 18
  scales_hasIdbSection:
    name: scales_hasIdbSection
    annotations:
      string:
        tag: string
        value: 114
  scales_hasIdbSentdate:
    name: scales_hasIdbSentdate
    annotations:
      string:
        tag: string
        value: 258
  scales_hasIdbStatuscd:
    name: scales_hasIdbStatuscd
    annotations:
      string:
        tag: string
        value: 4
  scales_hasIdbSubsect:
    name: scales_hasIdbSubsect
    annotations:
      string:
        tag: string
        value: 83
  scales_hasIdbSupvrel1:
    name: scales_hasIdbSupvrel1
    annotations:
      double:
        tag: double
        value: 12
  scales_hasIdbSupvrel2:
    name: scales_hasIdbSupvrel2
    annotations:
      double:
        tag: double
        value: 9
  scales_hasIdbSupvrel3:
    name: scales_hasIdbSupvrel3
    annotations:
      double:
        tag: double
        value: 6
  scales_hasIdbSupvrel4:
    name: scales_hasIdbSupvrel4
    annotations:
      double:
        tag: double
        value: 3
  scales_hasIdbSupvrel5:
    name: scales_hasIdbSupvrel5
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbTapeyear:
    name: scales_hasIdbTapeyear
    annotations:
      double:
        tag: double
        value: 10
  scales_hasIdbTcounsel:
    name: scales_hasIdbTcounsel
    annotations:
      double:
        tag: double
        value: 5
  scales_hasIdbTdateuse:
    name: scales_hasIdbTdateuse
    annotations:
      string:
        tag: string
        value: 56
  scales_hasIdbTermdate:
    name: scales_hasIdbTermdate
    annotations:
      datetime:
        tag: datetime
        value: 808
  scales_hasIdbTermoff:
    name: scales_hasIdbTermoff
    annotations:
      integer:
        tag: integer
        value: 2
  scales_hasIdbTitl:
    name: scales_hasIdbTitl
    annotations:
      string:
        tag: string
        value: 19
  scales_hasIdbToffcd1:
    name: scales_hasIdbToffcd1
    annotations:
      double:
        tag: double
        value: 38
  scales_hasIdbToffcd2:
    name: scales_hasIdbToffcd2
    annotations:
      double:
        tag: double
        value: 26
  scales_hasIdbToffcd3:
    name: scales_hasIdbToffcd3
    annotations:
      double:
        tag: double
        value: 17
  scales_hasIdbToffcd4:
    name: scales_hasIdbToffcd4
    annotations:
      double:
        tag: double
        value: 12
  scales_hasIdbToffcd5:
    name: scales_hasIdbToffcd5
    annotations:
      double:
        tag: double
        value: 7
  scales_hasIdbTofflvl1:
    name: scales_hasIdbTofflvl1
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbTofflvl2:
    name: scales_hasIdbTofflvl2
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbTofflvl3:
    name: scales_hasIdbTofflvl3
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbTofflvl4:
    name: scales_hasIdbTofflvl4
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbTofflvl5:
    name: scales_hasIdbTofflvl5
    annotations:
      double:
        tag: double
        value: 3
  scales_hasIdbTrandef:
    name: scales_hasIdbTrandef
    annotations:
      double:
        tag: double
        value: 1
  scales_hasIdbTrandist:
    name: scales_hasIdbTrandist
    annotations:
      integer:
        tag: integer
        value: 1
  scales_hasIdbTrandock:
    name: scales_hasIdbTrandock
    annotations:
      double:
        tag: double
        value: 1
  scales_hasIdbTranoff:
    name: scales_hasIdbTranoff
    annotations:
      integer:
        tag: integer
        value: 1
  scales_hasIdbTransdoc:
    name: scales_hasIdbTransdoc
    annotations:
      double:
        tag: double
        value: 1
  scales_hasIdbTransoff:
    name: scales_hasIdbTransoff
    annotations:
      string:
        tag: string
        value: 1
  scales_hasIdbTransorg:
    name: scales_hasIdbTransorg
    annotations:
      string:
        tag: string
        value: 1
  scales_hasIdbTrclact:
    name: scales_hasIdbTrclact
    annotations:
      double:
        tag: double
        value: 3
  scales_hasIdbTrialend:
    name: scales_hasIdbTrialend
    annotations:
      string:
        tag: string
        value: 13
  scales_hasIdbTribegan:
    name: scales_hasIdbTribegan
    annotations:
      string:
        tag: string
        value: 12
  scales_hasIdbTrmarb:
    name: scales_hasIdbTrmarb
    annotations:
      string:
        tag: string
        value: 1
  scales_hasIdbTsev1:
    name: scales_hasIdbTsev1
    annotations:
      string:
        tag: string
        value: 44
  scales_hasIdbTsev2:
    name: scales_hasIdbTsev2
    annotations:
      string:
        tag: string
        value: 31
  scales_hasIdbTsev3:
    name: scales_hasIdbTsev3
    annotations:
      string:
        tag: string
        value: 16
  scales_hasIdbTsev4:
    name: scales_hasIdbTsev4
    annotations:
      string:
        tag: string
        value: 13
  scales_hasIdbTsev5:
    name: scales_hasIdbTsev5
    annotations:
      string:
        tag: string
        value: 7
  scales_hasIdbTtitle1:
    name: scales_hasIdbTtitle1
    annotations:
      string:
        tag: string
        value: 68
  scales_hasIdbTtitle2:
    name: scales_hasIdbTtitle2
    annotations:
      string:
        tag: string
        value: 40
  scales_hasIdbTtitle3:
    name: scales_hasIdbTtitle3
    annotations:
      string:
        tag: string
        value: 20
  scales_hasIdbTtitle4:
    name: scales_hasIdbTtitle4
    annotations:
      string:
        tag: string
        value: 14
  scales_hasIdbTtitle5:
    name: scales_hasIdbTtitle5
    annotations:
      string:
        tag: string
        value: 8
  scales_hasIdbTypemag:
    name: scales_hasIdbTypemag
    annotations:
      string:
        tag: string
        value: 2
  scales_hasIdbTypereg:
    name: scales_hasIdbTypereg
    annotations:
      string:
        tag: string
        value: 2
  scales_hasIdbTypetrn:
    name: scales_hasIdbTypetrn
    annotations:
      integer:
        tag: integer
        value: 1
      string:
        tag: string
        value: 1
  scales_hasIdbUpdate:
    name: scales_hasIdbUpdate
    annotations:
      string:
        tag: string
        value: 1
  scales_hasIdbVer:
    name: scales_hasIdbVer
    annotations:
      double:
        tag: double
        value: 4
  scales_hasMemberCase:
    name: scales_hasMemberCase
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Case:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Case
        value: 1
      scales_Case:
        tag: scales_Case
        value: 1
  scales_hasRelatedCase:
    name: scales_hasRelatedCase
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Case:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Case
        value: 3
      scales_Case:
        tag: scales_Case
        value: 3
      uri:
        tag: uri
        value: 1
class_uri: http://release.niem.gov/niem/domains/jxdm/7.2/Case

```
</details>

### Induced

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_Case
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 2
description: No class (type) description specified
title: No class (type) name specified
rank: 1000
slot_usage:
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Charge:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
        value: 6280
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Court:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Court
        value: 2
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
        value: 8389
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
        value: 5633
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
    annotations:
      uri:
        tag: uri
        value: 6948
  http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
        value: 4999
      http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
        value: 5000
  http___release.niem.gov_niem_domains_jxdm_7.2_StatuteKeywordText:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_StatuteKeywordText
    annotations:
      string:
        tag: string
        value: 211
  niem50_CaseDocketID:
    name: niem50_CaseDocketID
    annotations:
      string:
        tag: string
        value: 5000
  niem50_CaseGeneralCategoryText:
    name: niem50_CaseGeneralCategoryText
    annotations:
      string:
        tag: string
        value: 2
  niem50_CaseSubCategoryText:
    name: niem50_CaseSubCategoryText
    annotations:
      string:
        tag: string
        value: 69
  niem50_EndDate:
    name: niem50_EndDate
    annotations:
      date:
        tag: date
        value: 1106
  niem50_JurisdictionText:
    name: niem50_JurisdictionText
    annotations:
      string:
        tag: string
        value: 4
  niem50_StartDate:
    name: niem50_StartDate
    annotations:
      date:
        tag: date
        value: 327
  niem50_StatusDescriptionText:
    name: niem50_StatusDescriptionText
    annotations:
      string:
        tag: string
        value: 4
  scales_Party:
    name: scales_Party
    annotations:
      scales_Party:
        tag: scales_Party
        value: 2319
  scales_hasIdbAmtrec:
    name: scales_hasIdbAmtrec
    annotations:
      double:
        tag: double
        value: 18
  scales_hasIdbAppcd:
    name: scales_hasIdbAppcd
    annotations:
      string:
        tag: string
        value: 4
  scales_hasIdbAppdate:
    name: scales_hasIdbAppdate
    annotations:
      string:
        tag: string
        value: 234
  scales_hasIdbArbit:
    name: scales_hasIdbArbit
    annotations:
      string:
        tag: string
        value: 1
  scales_hasIdbCaslgky:
    name: scales_hasIdbCaslgky
    annotations:
      string:
        tag: string
        value: 3441
  scales_hasIdbCircuit:
    name: scales_hasIdbCircuit
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbClassact:
    name: scales_hasIdbClassact
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbCounty:
    name: scales_hasIdbCounty
    annotations:
      double:
        tag: double
        value: 31
  scales_hasIdbCtdef:
    name: scales_hasIdbCtdef
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbCtfil:
    name: scales_hasIdbCtfil
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbCtfilr:
    name: scales_hasIdbCtfilr
    annotations:
      double:
        tag: double
        value: 1
  scales_hasIdbCtfiltrn:
    name: scales_hasIdbCtfiltrn
    annotations:
      double:
        tag: double
        value: 1
  scales_hasIdbCtfilwor:
    name: scales_hasIdbCtfilwor
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbCtpn:
    name: scales_hasIdbCtpn
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbCtpnwof:
    name: scales_hasIdbCtpnwof
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbCttr:
    name: scales_hasIdbCttr
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbCttrr:
    name: scales_hasIdbCttrr
    annotations:
      double:
        tag: double
        value: 1
  scales_hasIdbCttrtrn:
    name: scales_hasIdbCttrtrn
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbCttrwor:
    name: scales_hasIdbCttrwor
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbD2foffcd1:
    name: scales_hasIdbD2foffcd1
    annotations:
      double:
        tag: double
        value: 65
  scales_hasIdbD2foffcd2:
    name: scales_hasIdbD2foffcd2
    annotations:
      double:
        tag: double
        value: 51
  scales_hasIdbD2foffcd3:
    name: scales_hasIdbD2foffcd3
    annotations:
      double:
        tag: double
        value: 37
  scales_hasIdbD2foffcd4:
    name: scales_hasIdbD2foffcd4
    annotations:
      double:
        tag: double
        value: 24
  scales_hasIdbD2foffcd5:
    name: scales_hasIdbD2foffcd5
    annotations:
      double:
        tag: double
        value: 13
  scales_hasIdbD2toffcd1:
    name: scales_hasIdbD2toffcd1
    annotations:
      double:
        tag: double
        value: 41
  scales_hasIdbD2toffcd2:
    name: scales_hasIdbD2toffcd2
    annotations:
      double:
        tag: double
        value: 28
  scales_hasIdbD2toffcd3:
    name: scales_hasIdbD2toffcd3
    annotations:
      double:
        tag: double
        value: 16
  scales_hasIdbD2toffcd4:
    name: scales_hasIdbD2toffcd4
    annotations:
      double:
        tag: double
        value: 12
  scales_hasIdbD2toffcd5:
    name: scales_hasIdbD2toffcd5
    annotations:
      double:
        tag: double
        value: 7
  scales_hasIdbDef:
    name: scales_hasIdbDef
    annotations:
      string:
        tag: string
        value: 1034
  scales_hasIdbDeflgky:
    name: scales_hasIdbDeflgky
    annotations:
      string:
        tag: string
        value: 3441
  scales_hasIdbDefno:
    name: scales_hasIdbDefno
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbDemanded:
    name: scales_hasIdbDemanded
    annotations:
      double:
        tag: double
        value: 92
  scales_hasIdbDisp:
    name: scales_hasIdbDisp
    annotations:
      double:
        tag: double
        value: 19
  scales_hasIdbDisp1:
    name: scales_hasIdbDisp1
    annotations:
      double:
        tag: double
        value: 10
  scales_hasIdbDisp2:
    name: scales_hasIdbDisp2
    annotations:
      double:
        tag: double
        value: 5
  scales_hasIdbDisp3:
    name: scales_hasIdbDisp3
    annotations:
      double:
        tag: double
        value: 5
  scales_hasIdbDisp4:
    name: scales_hasIdbDisp4
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbDisp5:
    name: scales_hasIdbDisp5
    annotations:
      double:
        tag: double
        value: 3
  scales_hasIdbDispdate:
    name: scales_hasIdbDispdate
    annotations:
      string:
        tag: string
        value: 293
  scales_hasIdbDistrict:
    name: scales_hasIdbDistrict
    annotations:
      string:
        tag: string
        value: 2
  scales_hasIdbDjoined:
    name: scales_hasIdbDjoined
    annotations:
      string:
        tag: string
        value: 237
  scales_hasIdbDocket:
    name: scales_hasIdbDocket
    annotations:
      string:
        tag: string
        value: 4927
  scales_hasIdbFcounsel:
    name: scales_hasIdbFcounsel
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbFdateuse:
    name: scales_hasIdbFdateuse
    annotations:
      string:
        tag: string
        value: 9
  scales_hasIdbFgenddate:
    name: scales_hasIdbFgenddate
    annotations:
      string:
        tag: string
        value: 167
  scales_hasIdbFgstrtdate:
    name: scales_hasIdbFgstrtdate
    annotations:
      string:
        tag: string
        value: 176
  scales_hasIdbFiledate:
    name: scales_hasIdbFiledate
    annotations:
      datetime:
        tag: datetime
        value: 327
  scales_hasIdbFineamt1:
    name: scales_hasIdbFineamt1
    annotations:
      double:
        tag: double
        value: 14
  scales_hasIdbFineamt2:
    name: scales_hasIdbFineamt2
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbFineamt3:
    name: scales_hasIdbFineamt3
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbFineamt4:
    name: scales_hasIdbFineamt4
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbFineamt5:
    name: scales_hasIdbFineamt5
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbFinetot:
    name: scales_hasIdbFinetot
    annotations:
      double:
        tag: double
        value: 13
  scales_hasIdbFiscalyr:
    name: scales_hasIdbFiscalyr
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbFoffcd1:
    name: scales_hasIdbFoffcd1
    annotations:
      double:
        tag: double
        value: 60
  scales_hasIdbFoffcd2:
    name: scales_hasIdbFoffcd2
    annotations:
      double:
        tag: double
        value: 44
  scales_hasIdbFoffcd3:
    name: scales_hasIdbFoffcd3
    annotations:
      double:
        tag: double
        value: 35
  scales_hasIdbFoffcd4:
    name: scales_hasIdbFoffcd4
    annotations:
      double:
        tag: double
        value: 22
  scales_hasIdbFoffcd5:
    name: scales_hasIdbFoffcd5
    annotations:
      double:
        tag: double
        value: 12
  scales_hasIdbFofflvl1:
    name: scales_hasIdbFofflvl1
    annotations:
      double:
        tag: double
        value: 3
  scales_hasIdbFofflvl2:
    name: scales_hasIdbFofflvl2
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbFofflvl3:
    name: scales_hasIdbFofflvl3
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbFofflvl4:
    name: scales_hasIdbFofflvl4
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbFofflvl5:
    name: scales_hasIdbFofflvl5
    annotations:
      double:
        tag: double
        value: 3
  scales_hasIdbFsev1:
    name: scales_hasIdbFsev1
    annotations:
      string:
        tag: string
        value: 60
  scales_hasIdbFsev2:
    name: scales_hasIdbFsev2
    annotations:
      string:
        tag: string
        value: 56
  scales_hasIdbFsev3:
    name: scales_hasIdbFsev3
    annotations:
      string:
        tag: string
        value: 38
  scales_hasIdbFsev4:
    name: scales_hasIdbFsev4
    annotations:
      string:
        tag: string
        value: 25
  scales_hasIdbFsev5:
    name: scales_hasIdbFsev5
    annotations:
      string:
        tag: string
        value: 15
  scales_hasIdbFtitle1:
    name: scales_hasIdbFtitle1
    annotations:
      string:
        tag: string
        value: 114
  scales_hasIdbFtitle2:
    name: scales_hasIdbFtitle2
    annotations:
      string:
        tag: string
        value: 87
  scales_hasIdbFtitle3:
    name: scales_hasIdbFtitle3
    annotations:
      string:
        tag: string
        value: 57
  scales_hasIdbFtitle4:
    name: scales_hasIdbFtitle4
    annotations:
      string:
        tag: string
        value: 35
  scales_hasIdbFtitle5:
    name: scales_hasIdbFtitle5
    annotations:
      string:
        tag: string
        value: 17
  scales_hasIdbFugstat:
    name: scales_hasIdbFugstat
    annotations:
      string:
        tag: string
        value: 2
  scales_hasIdbIfp:
    name: scales_hasIdbIfp
    annotations:
      string:
        tag: string
        value: 2
  scales_hasIdbInt1:
    name: scales_hasIdbInt1
    annotations:
      double:
        tag: double
        value: 29
  scales_hasIdbInt2:
    name: scales_hasIdbInt2
    annotations:
      double:
        tag: double
        value: 61
  scales_hasIdbInt3:
    name: scales_hasIdbInt3
    annotations:
      double:
        tag: double
        value: 136
  scales_hasIdbIs_stub:
    name: scales_hasIdbIs_stub
    annotations:
      boolean:
        tag: boolean
        value: 2
  scales_hasIdbJudgment:
    name: scales_hasIdbJudgment
    annotations:
      double:
        tag: double
        value: 6
  scales_hasIdbJuris:
    name: scales_hasIdbJuris
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbJury:
    name: scales_hasIdbJury
    annotations:
      string:
        tag: string
        value: 4
  scales_hasIdbLoaddate:
    name: scales_hasIdbLoaddate
    annotations:
      string:
        tag: string
        value: 26
  scales_hasIdbMagdef:
    name: scales_hasIdbMagdef
    annotations:
      double:
        tag: double
        value: 3
  scales_hasIdbMagdock:
    name: scales_hasIdbMagdock
    annotations:
      double:
        tag: double
        value: 3216
  scales_hasIdbMdldock:
    name: scales_hasIdbMdldock
    annotations:
      string:
        tag: string
        value: 6
  scales_hasIdbNoj:
    name: scales_hasIdbNoj
    annotations:
      double:
        tag: double
        value: 7
  scales_hasIdbNos:
    name: scales_hasIdbNos
    annotations:
      string:
        tag: string
        value: 69
  scales_hasIdbOffice:
    name: scales_hasIdbOffice
    annotations:
      string:
        tag: string
        value: 2
  scales_hasIdbOrigin:
    name: scales_hasIdbOrigin
    annotations:
      double:
        tag: double
        value: 6
  scales_hasIdbPlt:
    name: scales_hasIdbPlt
    annotations:
      string:
        tag: string
        value: 1098
  scales_hasIdbPretrial:
    name: scales_hasIdbPretrial
    annotations:
      string:
        tag: string
        value: 185
  scales_hasIdbPriscd1:
    name: scales_hasIdbPriscd1
    annotations:
      string:
        tag: string
        value: 8
  scales_hasIdbPriscd2:
    name: scales_hasIdbPriscd2
    annotations:
      string:
        tag: string
        value: 6
  scales_hasIdbPriscd3:
    name: scales_hasIdbPriscd3
    annotations:
      string:
        tag: string
        value: 3
  scales_hasIdbPriscd4:
    name: scales_hasIdbPriscd4
    annotations:
      string:
        tag: string
        value: 2
  scales_hasIdbPriscd5:
    name: scales_hasIdbPriscd5
    annotations:
      integer:
        tag: integer
        value: 1
      string:
        tag: string
        value: 1
  scales_hasIdbPristim1:
    name: scales_hasIdbPristim1
    annotations:
      double:
        tag: double
        value: 68
  scales_hasIdbPristim2:
    name: scales_hasIdbPristim2
    annotations:
      double:
        tag: double
        value: 37
  scales_hasIdbPristim3:
    name: scales_hasIdbPristim3
    annotations:
      double:
        tag: double
        value: 15
  scales_hasIdbPristim4:
    name: scales_hasIdbPristim4
    annotations:
      double:
        tag: double
        value: 3
  scales_hasIdbPristim5:
    name: scales_hasIdbPristim5
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbPristot:
    name: scales_hasIdbPristot
    annotations:
      double:
        tag: double
        value: 68
  scales_hasIdbProbcd1:
    name: scales_hasIdbProbcd1
    annotations:
      string:
        tag: string
        value: 3
  scales_hasIdbProbcd2:
    name: scales_hasIdbProbcd2
    annotations:
      integer:
        tag: integer
        value: 1
      string:
        tag: string
        value: 3
  scales_hasIdbProbcd3:
    name: scales_hasIdbProbcd3
    annotations:
      integer:
        tag: integer
        value: 1
      string:
        tag: string
        value: 1
  scales_hasIdbProbcd4:
    name: scales_hasIdbProbcd4
    annotations:
      integer:
        tag: integer
        value: 1
      string:
        tag: string
        value: 1
  scales_hasIdbProbcd5:
    name: scales_hasIdbProbcd5
    annotations:
      integer:
        tag: integer
        value: 1
  scales_hasIdbProbmon1:
    name: scales_hasIdbProbmon1
    annotations:
      double:
        tag: double
        value: 8
  scales_hasIdbProbmon2:
    name: scales_hasIdbProbmon2
    annotations:
      double:
        tag: double
        value: 3
  scales_hasIdbProbmon3:
    name: scales_hasIdbProbmon3
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbProbmon4:
    name: scales_hasIdbProbmon4
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbProbmon5:
    name: scales_hasIdbProbmon5
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbProbtot:
    name: scales_hasIdbProbtot
    annotations:
      double:
        tag: double
        value: 8
  scales_hasIdbProccd:
    name: scales_hasIdbProccd
    annotations:
      double:
        tag: double
        value: 8
  scales_hasIdbProcdate:
    name: scales_hasIdbProcdate
    annotations:
      string:
        tag: string
        value: 176
  scales_hasIdbProcprog:
    name: scales_hasIdbProcprog
    annotations:
      double:
        tag: double
        value: 13
  scales_hasIdbProse:
    name: scales_hasIdbProse
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbReopseq:
    name: scales_hasIdbReopseq
    annotations:
      double:
        tag: double
        value: 1
  scales_hasIdbResidenc:
    name: scales_hasIdbResidenc
    annotations:
      double:
        tag: double
        value: 18
  scales_hasIdbSection:
    name: scales_hasIdbSection
    annotations:
      string:
        tag: string
        value: 114
  scales_hasIdbSentdate:
    name: scales_hasIdbSentdate
    annotations:
      string:
        tag: string
        value: 258
  scales_hasIdbStatuscd:
    name: scales_hasIdbStatuscd
    annotations:
      string:
        tag: string
        value: 4
  scales_hasIdbSubsect:
    name: scales_hasIdbSubsect
    annotations:
      string:
        tag: string
        value: 83
  scales_hasIdbSupvrel1:
    name: scales_hasIdbSupvrel1
    annotations:
      double:
        tag: double
        value: 12
  scales_hasIdbSupvrel2:
    name: scales_hasIdbSupvrel2
    annotations:
      double:
        tag: double
        value: 9
  scales_hasIdbSupvrel3:
    name: scales_hasIdbSupvrel3
    annotations:
      double:
        tag: double
        value: 6
  scales_hasIdbSupvrel4:
    name: scales_hasIdbSupvrel4
    annotations:
      double:
        tag: double
        value: 3
  scales_hasIdbSupvrel5:
    name: scales_hasIdbSupvrel5
    annotations:
      double:
        tag: double
        value: 2
  scales_hasIdbTapeyear:
    name: scales_hasIdbTapeyear
    annotations:
      double:
        tag: double
        value: 10
  scales_hasIdbTcounsel:
    name: scales_hasIdbTcounsel
    annotations:
      double:
        tag: double
        value: 5
  scales_hasIdbTdateuse:
    name: scales_hasIdbTdateuse
    annotations:
      string:
        tag: string
        value: 56
  scales_hasIdbTermdate:
    name: scales_hasIdbTermdate
    annotations:
      datetime:
        tag: datetime
        value: 808
  scales_hasIdbTermoff:
    name: scales_hasIdbTermoff
    annotations:
      integer:
        tag: integer
        value: 2
  scales_hasIdbTitl:
    name: scales_hasIdbTitl
    annotations:
      string:
        tag: string
        value: 19
  scales_hasIdbToffcd1:
    name: scales_hasIdbToffcd1
    annotations:
      double:
        tag: double
        value: 38
  scales_hasIdbToffcd2:
    name: scales_hasIdbToffcd2
    annotations:
      double:
        tag: double
        value: 26
  scales_hasIdbToffcd3:
    name: scales_hasIdbToffcd3
    annotations:
      double:
        tag: double
        value: 17
  scales_hasIdbToffcd4:
    name: scales_hasIdbToffcd4
    annotations:
      double:
        tag: double
        value: 12
  scales_hasIdbToffcd5:
    name: scales_hasIdbToffcd5
    annotations:
      double:
        tag: double
        value: 7
  scales_hasIdbTofflvl1:
    name: scales_hasIdbTofflvl1
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbTofflvl2:
    name: scales_hasIdbTofflvl2
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbTofflvl3:
    name: scales_hasIdbTofflvl3
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbTofflvl4:
    name: scales_hasIdbTofflvl4
    annotations:
      double:
        tag: double
        value: 4
  scales_hasIdbTofflvl5:
    name: scales_hasIdbTofflvl5
    annotations:
      double:
        tag: double
        value: 3
  scales_hasIdbTrandef:
    name: scales_hasIdbTrandef
    annotations:
      double:
        tag: double
        value: 1
  scales_hasIdbTrandist:
    name: scales_hasIdbTrandist
    annotations:
      integer:
        tag: integer
        value: 1
  scales_hasIdbTrandock:
    name: scales_hasIdbTrandock
    annotations:
      double:
        tag: double
        value: 1
  scales_hasIdbTranoff:
    name: scales_hasIdbTranoff
    annotations:
      integer:
        tag: integer
        value: 1
  scales_hasIdbTransdoc:
    name: scales_hasIdbTransdoc
    annotations:
      double:
        tag: double
        value: 1
  scales_hasIdbTransoff:
    name: scales_hasIdbTransoff
    annotations:
      string:
        tag: string
        value: 1
  scales_hasIdbTransorg:
    name: scales_hasIdbTransorg
    annotations:
      string:
        tag: string
        value: 1
  scales_hasIdbTrclact:
    name: scales_hasIdbTrclact
    annotations:
      double:
        tag: double
        value: 3
  scales_hasIdbTrialend:
    name: scales_hasIdbTrialend
    annotations:
      string:
        tag: string
        value: 13
  scales_hasIdbTribegan:
    name: scales_hasIdbTribegan
    annotations:
      string:
        tag: string
        value: 12
  scales_hasIdbTrmarb:
    name: scales_hasIdbTrmarb
    annotations:
      string:
        tag: string
        value: 1
  scales_hasIdbTsev1:
    name: scales_hasIdbTsev1
    annotations:
      string:
        tag: string
        value: 44
  scales_hasIdbTsev2:
    name: scales_hasIdbTsev2
    annotations:
      string:
        tag: string
        value: 31
  scales_hasIdbTsev3:
    name: scales_hasIdbTsev3
    annotations:
      string:
        tag: string
        value: 16
  scales_hasIdbTsev4:
    name: scales_hasIdbTsev4
    annotations:
      string:
        tag: string
        value: 13
  scales_hasIdbTsev5:
    name: scales_hasIdbTsev5
    annotations:
      string:
        tag: string
        value: 7
  scales_hasIdbTtitle1:
    name: scales_hasIdbTtitle1
    annotations:
      string:
        tag: string
        value: 68
  scales_hasIdbTtitle2:
    name: scales_hasIdbTtitle2
    annotations:
      string:
        tag: string
        value: 40
  scales_hasIdbTtitle3:
    name: scales_hasIdbTtitle3
    annotations:
      string:
        tag: string
        value: 20
  scales_hasIdbTtitle4:
    name: scales_hasIdbTtitle4
    annotations:
      string:
        tag: string
        value: 14
  scales_hasIdbTtitle5:
    name: scales_hasIdbTtitle5
    annotations:
      string:
        tag: string
        value: 8
  scales_hasIdbTypemag:
    name: scales_hasIdbTypemag
    annotations:
      string:
        tag: string
        value: 2
  scales_hasIdbTypereg:
    name: scales_hasIdbTypereg
    annotations:
      string:
        tag: string
        value: 2
  scales_hasIdbTypetrn:
    name: scales_hasIdbTypetrn
    annotations:
      integer:
        tag: integer
        value: 1
      string:
        tag: string
        value: 1
  scales_hasIdbUpdate:
    name: scales_hasIdbUpdate
    annotations:
      string:
        tag: string
        value: 1
  scales_hasIdbVer:
    name: scales_hasIdbVer
    annotations:
      double:
        tag: double
        value: 4
  scales_hasMemberCase:
    name: scales_hasMemberCase
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Case:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Case
        value: 1
      scales_Case:
        tag: scales_Case
        value: 1
  scales_hasRelatedCase:
    name: scales_hasRelatedCase
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Case:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Case
        value: 3
      scales_Case:
        tag: scales_Case
        value: 3
      uri:
        tag: uri
        value: 1
attributes:
  scales_hasIdbPretrial:
    name: scales_hasIdbPretrial
    annotations:
      string:
        tag: string
        value: 185
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 01/04/2017
        example_object_type: string
        example_predicate: scales:hasIdbPretrial
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: 01/04/2017
        example_object_type: string
        example_predicate: scales:hasIdbPretrial
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPretrial
    alias: scales_hasIdbPretrial
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasMemberCase:
    name: scales_hasMemberCase
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Case:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Case
        value: 1
      scales_Case:
        tag: scales_Case
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/CaseCivil
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
        example_predicate: scales:hasMemberCase
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: scales:/CaseCivil
        example_object_type: scales_Case
        example_predicate: scales:hasMemberCase
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: scales:/CaseCivil
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
        example_predicate: scales:hasMemberCase
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    - object:
        example_object: scales:/CaseCivil
        example_object_type: scales_Case
        example_predicate: scales:hasMemberCase
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    - object:
        example_object: scales:/CaseCivil
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
        example_predicate: scales:hasMemberCase
        example_subject: scales:/CaseOther
        example_subject_type: None
    - object:
        example_object: scales:/CaseCivil
        example_object_type: scales_Case
        example_predicate: scales:hasMemberCase
        example_subject: scales:/CaseOther
        example_subject_type: None
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasMemberCase
    alias: scales_hasMemberCase
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: Any
    any_of:
    - range: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - range: scales_Case
  scales_hasIdbAppcd:
    name: scales_hasIdbAppcd
    annotations:
      string:
        tag: string
        value: 4
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbAppcd
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbAppcd
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbAppcd
    alias: scales_hasIdbAppcd
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbTitl:
    name: scales_hasIdbTitl
    annotations:
      string:
        tag: string
        value: 19
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '00'
        example_object_type: string
        example_predicate: scales:hasIdbTitl
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '00'
        example_object_type: string
        example_predicate: scales:hasIdbTitl
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTitl
    alias: scales_hasIdbTitl
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbToffcd4:
    name: scales_hasIdbToffcd4
    annotations:
      double:
        tag: double
        value: 12
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbToffcd4
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbToffcd4
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbToffcd4
    alias: scales_hasIdbToffcd4
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbFoffcd4:
    name: scales_hasIdbFoffcd4
    annotations:
      double:
        tag: double
        value: 22
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFoffcd4
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFoffcd4
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFoffcd4
    alias: scales_hasIdbFoffcd4
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbReopseq:
    name: scales_hasIdbReopseq
    annotations:
      double:
        tag: double
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbReopseq
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbReopseq
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbReopseq
    alias: scales_hasIdbReopseq
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbTsev3:
    name: scales_hasIdbTsev3
    annotations:
      string:
        tag: string
        value: 16
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTsev3
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTsev3
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTsev3
    alias: scales_hasIdbTsev3
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  niem50_StatusDescriptionText:
    name: niem50_StatusDescriptionText
    annotations:
      string:
        tag: string
        value: 4
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: closed
        example_object_type: string
        example_predicate: niem50:StatusDescriptionText
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: closed
        example_object_type: string
        example_predicate: niem50:StatusDescriptionText
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: niem50:StatusDescriptionText
    alias: niem50_StatusDescriptionText
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbDisp:
    name: scales_hasIdbDisp
    annotations:
      double:
        tag: double
        value: 19
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbDisp
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbDisp
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDisp
    alias: scales_hasIdbDisp
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbFiscalyr:
    name: scales_hasIdbFiscalyr
    annotations:
      double:
        tag: double
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '2017.0'
        example_object_type: double
        example_predicate: scales:hasIdbFiscalyr
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '2017.0'
        example_object_type: double
        example_predicate: scales:hasIdbFiscalyr
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFiscalyr
    alias: scales_hasIdbFiscalyr
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbTofflvl2:
    name: scales_hasIdbTofflvl2
    annotations:
      double:
        tag: double
        value: 4
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTofflvl2
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTofflvl2
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTofflvl2
    alias: scales_hasIdbTofflvl2
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbFgenddate:
    name: scales_hasIdbFgenddate
    annotations:
      string:
        tag: string
        value: 167
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 01/01/1900
        example_object_type: string
        example_predicate: scales:hasIdbFgenddate
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: 01/01/1900
        example_object_type: string
        example_predicate: scales:hasIdbFgenddate
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFgenddate
    alias: scales_hasIdbFgenddate
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbTsev4:
    name: scales_hasIdbTsev4
    annotations:
      string:
        tag: string
        value: 13
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTsev4
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTsev4
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTsev4
    alias: scales_hasIdbTsev4
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbDemanded:
    name: scales_hasIdbDemanded
    annotations:
      double:
        tag: double
        value: 92
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbDemanded
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbDemanded
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDemanded
    alias: scales_hasIdbDemanded
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbCtpnwof:
    name: scales_hasIdbCtpnwof
    annotations:
      double:
        tag: double
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCtpnwof
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCtpnwof
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtpnwof
    alias: scales_hasIdbCtpnwof
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbProbmon5:
    name: scales_hasIdbProbmon5
    annotations:
      double:
        tag: double
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbProbmon5
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbProbmon5
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbmon5
    alias: scales_hasIdbProbmon5
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbClassact:
    name: scales_hasIdbClassact
    annotations:
      double:
        tag: double
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbClassact
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbClassact
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbClassact
    alias: scales_hasIdbClassact
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbProbmon4:
    name: scales_hasIdbProbmon4
    annotations:
      double:
        tag: double
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbProbmon4
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbProbmon4
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbmon4
    alias: scales_hasIdbProbmon4
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbFdateuse:
    name: scales_hasIdbFdateuse
    annotations:
      string:
        tag: string
        value: 9
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 04/01/2016
        example_object_type: string
        example_predicate: scales:hasIdbFdateuse
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: 04/01/2016
        example_object_type: string
        example_predicate: scales:hasIdbFdateuse
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFdateuse
    alias: scales_hasIdbFdateuse
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbSupvrel1:
    name: scales_hasIdbSupvrel1
    annotations:
      double:
        tag: double
        value: 12
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbSupvrel1
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbSupvrel1
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSupvrel1
    alias: scales_hasIdbSupvrel1
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbDisp1:
    name: scales_hasIdbDisp1
    annotations:
      double:
        tag: double
        value: 10
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbDisp1
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbDisp1
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDisp1
    alias: scales_hasIdbDisp1
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbPriscd3:
    name: scales_hasIdbPriscd3
    annotations:
      string:
        tag: string
        value: 3
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbPriscd3
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbPriscd3
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPriscd3
    alias: scales_hasIdbPriscd3
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbPristim1:
    name: scales_hasIdbPristim1
    annotations:
      double:
        tag: double
        value: 68
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-1.0'
        example_object_type: double
        example_predicate: scales:hasIdbPristim1
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-1.0'
        example_object_type: double
        example_predicate: scales:hasIdbPristim1
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristim1
    alias: scales_hasIdbPristim1
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbSupvrel3:
    name: scales_hasIdbSupvrel3
    annotations:
      double:
        tag: double
        value: 6
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbSupvrel3
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbSupvrel3
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSupvrel3
    alias: scales_hasIdbSupvrel3
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbUpdate:
    name: scales_hasIdbUpdate
    annotations:
      string:
        tag: string
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 01/01/1900
        example_object_type: string
        example_predicate: scales:hasIdbUpdate
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: 01/01/1900
        example_object_type: string
        example_predicate: scales:hasIdbUpdate
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbUpdate
    alias: scales_hasIdbUpdate
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbProbtot:
    name: scales_hasIdbProbtot
    annotations:
      double:
        tag: double
        value: 8
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbProbtot
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbProbtot
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbtot
    alias: scales_hasIdbProbtot
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbCtfil:
    name: scales_hasIdbCtfil
    annotations:
      double:
        tag: double
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCtfil
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCtfil
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtfil
    alias: scales_hasIdbCtfil
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbFgstrtdate:
    name: scales_hasIdbFgstrtdate
    annotations:
      string:
        tag: string
        value: 176
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 01/01/1900
        example_object_type: string
        example_predicate: scales:hasIdbFgstrtdate
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: 01/01/1900
        example_object_type: string
        example_predicate: scales:hasIdbFgstrtdate
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFgstrtdate
    alias: scales_hasIdbFgstrtdate
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbTsev5:
    name: scales_hasIdbTsev5
    annotations:
      string:
        tag: string
        value: 7
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTsev5
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTsev5
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTsev5
    alias: scales_hasIdbTsev5
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbD2toffcd2:
    name: scales_hasIdbD2toffcd2
    annotations:
      double:
        tag: double
        value: 28
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2toffcd2
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2toffcd2
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2toffcd2
    alias: scales_hasIdbD2toffcd2
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbTribegan:
    name: scales_hasIdbTribegan
    annotations:
      string:
        tag: string
        value: 12
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 01/16/2019
        example_object_type: string
        example_predicate: scales:hasIdbTribegan
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: 01/16/2019
        example_object_type: string
        example_predicate: scales:hasIdbTribegan
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTribegan
    alias: scales_hasIdbTribegan
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbD2toffcd1:
    name: scales_hasIdbD2toffcd1
    annotations:
      double:
        tag: double
        value: 41
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2toffcd1
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2toffcd1
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2toffcd1
    alias: scales_hasIdbD2toffcd1
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbMagdef:
    name: scales_hasIdbMagdef
    annotations:
      double:
        tag: double
        value: 3
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbMagdef
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbMagdef
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbMagdef
    alias: scales_hasIdbMagdef
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbProbcd3:
    name: scales_hasIdbProbcd3
    annotations:
      integer:
        tag: integer
        value: 1
      string:
        tag: string
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbProbcd3
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbProbcd3
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbProbcd3
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbProbcd3
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbcd3
    alias: scales_hasIdbProbcd3
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: Any
    any_of:
    - range: string
    - range: integer
  scales_hasIdbTtitle4:
    name: scales_hasIdbTtitle4
    annotations:
      string:
        tag: string
        value: 14
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTtitle4
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTtitle4
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTtitle4
    alias: scales_hasIdbTtitle4
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbTrclact:
    name: scales_hasIdbTrclact
    annotations:
      double:
        tag: double
        value: 3
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTrclact
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTrclact
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTrclact
    alias: scales_hasIdbTrclact
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbDisp2:
    name: scales_hasIdbDisp2
    annotations:
      double:
        tag: double
        value: 5
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbDisp2
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbDisp2
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDisp2
    alias: scales_hasIdbDisp2
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbFtitle5:
    name: scales_hasIdbFtitle5
    annotations:
      string:
        tag: string
        value: 17
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFtitle5
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFtitle5
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFtitle5
    alias: scales_hasIdbFtitle5
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbProse:
    name: scales_hasIdbProse
    annotations:
      double:
        tag: double
        value: 4
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbProse
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbProse
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProse
    alias: scales_hasIdbProse
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbSentdate:
    name: scales_hasIdbSentdate
    annotations:
      string:
        tag: string
        value: 258
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 01/01/1900
        example_object_type: string
        example_predicate: scales:hasIdbSentdate
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: 01/01/1900
        example_object_type: string
        example_predicate: scales:hasIdbSentdate
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSentdate
    alias: scales_hasIdbSentdate
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  niem50_CaseSubCategoryText:
    name: niem50_CaseSubCategoryText
    annotations:
      string:
        tag: string
        value: 69
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 110 Insurance
        example_object_type: string
        example_predicate: niem50:CaseSubCategoryText
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: 110 Insurance
        example_object_type: string
        example_predicate: niem50:CaseSubCategoryText
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: niem50:CaseSubCategoryText
    alias: niem50_CaseSubCategoryText
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbCttrr:
    name: scales_hasIdbCttrr
    annotations:
      double:
        tag: double
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCttrr
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCttrr
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCttrr
    alias: scales_hasIdbCttrr
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbFtitle2:
    name: scales_hasIdbFtitle2
    annotations:
      string:
        tag: string
        value: 87
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFtitle2
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFtitle2
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFtitle2
    alias: scales_hasIdbFtitle2
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbSection:
    name: scales_hasIdbSection
    annotations:
      string:
        tag: string
        value: 114
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0000'
        example_object_type: string
        example_predicate: scales:hasIdbSection
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '0000'
        example_object_type: string
        example_predicate: scales:hasIdbSection
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSection
    alias: scales_hasIdbSection
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbPristim2:
    name: scales_hasIdbPristim2
    annotations:
      double:
        tag: double
        value: 37
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-1.0'
        example_object_type: double
        example_predicate: scales:hasIdbPristim2
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-1.0'
        example_object_type: double
        example_predicate: scales:hasIdbPristim2
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristim2
    alias: scales_hasIdbPristim2
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbIfp:
    name: scales_hasIdbIfp
    annotations:
      string:
        tag: string
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbIfp
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbIfp
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbIfp
    alias: scales_hasIdbIfp
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbTdateuse:
    name: scales_hasIdbTdateuse
    annotations:
      string:
        tag: string
        value: 56
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 01/01/2017
        example_object_type: string
        example_predicate: scales:hasIdbTdateuse
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: 01/01/2017
        example_object_type: string
        example_predicate: scales:hasIdbTdateuse
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTdateuse
    alias: scales_hasIdbTdateuse
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbTermdate:
    name: scales_hasIdbTermdate
    annotations:
      datetime:
        tag: datetime
        value: 808
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '2016-06-29T00:00:00'
        example_object_type: datetime
        example_predicate: scales:hasIdbTermdate
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '2016-06-29T00:00:00'
        example_object_type: datetime
        example_predicate: scales:hasIdbTermdate
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTermdate
    alias: scales_hasIdbTermdate
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: datetime
  scales_hasIdbPriscd2:
    name: scales_hasIdbPriscd2
    annotations:
      string:
        tag: string
        value: 6
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbPriscd2
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbPriscd2
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPriscd2
    alias: scales_hasIdbPriscd2
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
        value: 8389
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/Agent/casd;;3:16-cv-01644_a1
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: scales:/Agent/casd;;3:16-cv-01644_a1
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
  scales_hasIdbInt2:
    name: scales_hasIdbInt2
    annotations:
      double:
        tag: double
        value: 61
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbInt2
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbInt2
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbInt2
    alias: scales_hasIdbInt2
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbProbmon2:
    name: scales_hasIdbProbmon2
    annotations:
      double:
        tag: double
        value: 3
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbProbmon2
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbProbmon2
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbmon2
    alias: scales_hasIdbProbmon2
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbToffcd3:
    name: scales_hasIdbToffcd3
    annotations:
      double:
        tag: double
        value: 17
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbToffcd3
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbToffcd3
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbToffcd3
    alias: scales_hasIdbToffcd3
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbFineamt4:
    name: scales_hasIdbFineamt4
    annotations:
      double:
        tag: double
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFineamt4
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFineamt4
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFineamt4
    alias: scales_hasIdbFineamt4
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  niem50_CaseGeneralCategoryText:
    name: niem50_CaseGeneralCategoryText
    annotations:
      string:
        tag: string
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: civil
        example_object_type: string
        example_predicate: niem50:CaseGeneralCategoryText
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: civil
        example_object_type: string
        example_predicate: niem50:CaseGeneralCategoryText
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: niem50:CaseGeneralCategoryText
    alias: niem50_CaseGeneralCategoryText
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbTrandef:
    name: scales_hasIdbTrandef
    annotations:
      double:
        tag: double
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTrandef
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTrandef
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTrandef
    alias: scales_hasIdbTrandef
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbToffcd5:
    name: scales_hasIdbToffcd5
    annotations:
      double:
        tag: double
        value: 7
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbToffcd5
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbToffcd5
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbToffcd5
    alias: scales_hasIdbToffcd5
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbProbcd1:
    name: scales_hasIdbProbcd1
    annotations:
      string:
        tag: string
        value: 3
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbProbcd1
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbProbcd1
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbcd1
    alias: scales_hasIdbProbcd1
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbDocket:
    name: scales_hasIdbDocket
    annotations:
      string:
        tag: string
        value: 4927
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1601644'
        example_object_type: string
        example_predicate: scales:hasIdbDocket
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '1601644'
        example_object_type: string
        example_predicate: scales:hasIdbDocket
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDocket
    alias: scales_hasIdbDocket
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbToffcd2:
    name: scales_hasIdbToffcd2
    annotations:
      double:
        tag: double
        value: 26
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbToffcd2
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbToffcd2
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbToffcd2
    alias: scales_hasIdbToffcd2
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbD2toffcd4:
    name: scales_hasIdbD2toffcd4
    annotations:
      double:
        tag: double
        value: 12
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2toffcd4
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2toffcd4
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2toffcd4
    alias: scales_hasIdbD2toffcd4
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbLoaddate:
    name: scales_hasIdbLoaddate
    annotations:
      string:
        tag: string
        value: 26
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 01/02/2018
        example_object_type: string
        example_predicate: scales:hasIdbLoaddate
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: 01/02/2018
        example_object_type: string
        example_predicate: scales:hasIdbLoaddate
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbLoaddate
    alias: scales_hasIdbLoaddate
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
        value: 5633
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/Agent/casd;;3:16-cv-01644_a0
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: scales:/Agent/casd;;3:16-cv-01644_a0
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
  scales_hasIdbTransorg:
    name: scales_hasIdbTransorg
    annotations:
      string:
        tag: string
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTransorg
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTransorg
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTransorg
    alias: scales_hasIdbTransorg
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbCttr:
    name: scales_hasIdbCttr
    annotations:
      double:
        tag: double
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCttr
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCttr
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCttr
    alias: scales_hasIdbCttr
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbProbmon3:
    name: scales_hasIdbProbmon3
    annotations:
      double:
        tag: double
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbProbmon3
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbProbmon3
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbmon3
    alias: scales_hasIdbProbmon3
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbVer:
    name: scales_hasIdbVer
    annotations:
      double:
        tag: double
        value: 4
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbVer
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbVer
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbVer
    alias: scales_hasIdbVer
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbFofflvl4:
    name: scales_hasIdbFofflvl4
    annotations:
      double:
        tag: double
        value: 4
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFofflvl4
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFofflvl4
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFofflvl4
    alias: scales_hasIdbFofflvl4
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbDjoined:
    name: scales_hasIdbDjoined
    annotations:
      string:
        tag: string
        value: 237
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 01/02/2017
        example_object_type: string
        example_predicate: scales:hasIdbDjoined
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: 01/02/2017
        example_object_type: string
        example_predicate: scales:hasIdbDjoined
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDjoined
    alias: scales_hasIdbDjoined
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbProccd:
    name: scales_hasIdbProccd
    annotations:
      double:
        tag: double
        value: 8
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '19.0'
        example_object_type: double
        example_predicate: scales:hasIdbProccd
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '19.0'
        example_object_type: double
        example_predicate: scales:hasIdbProccd
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProccd
    alias: scales_hasIdbProccd
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbDistrict:
    name: scales_hasIdbDistrict
    annotations:
      string:
        tag: string
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: casd
        example_object_type: string
        example_predicate: scales:hasIdbDistrict
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: casd
        example_object_type: string
        example_predicate: scales:hasIdbDistrict
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDistrict
    alias: scales_hasIdbDistrict
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbTrmarb:
    name: scales_hasIdbTrmarb
    annotations:
      string:
        tag: string
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTrmarb
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTrmarb
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTrmarb
    alias: scales_hasIdbTrmarb
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbFoffcd3:
    name: scales_hasIdbFoffcd3
    annotations:
      double:
        tag: double
        value: 35
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFoffcd3
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFoffcd3
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFoffcd3
    alias: scales_hasIdbFoffcd3
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbFofflvl1:
    name: scales_hasIdbFofflvl1
    annotations:
      double:
        tag: double
        value: 3
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1.0'
        example_object_type: double
        example_predicate: scales:hasIdbFofflvl1
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '1.0'
        example_object_type: double
        example_predicate: scales:hasIdbFofflvl1
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFofflvl1
    alias: scales_hasIdbFofflvl1
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbDispdate:
    name: scales_hasIdbDispdate
    annotations:
      string:
        tag: string
        value: 293
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 01/01/1900
        example_object_type: string
        example_predicate: scales:hasIdbDispdate
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: 01/01/1900
        example_object_type: string
        example_predicate: scales:hasIdbDispdate
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDispdate
    alias: scales_hasIdbDispdate
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbTrandock:
    name: scales_hasIdbTrandock
    annotations:
      double:
        tag: double
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTrandock
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTrandock
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTrandock
    alias: scales_hasIdbTrandock
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbFsev3:
    name: scales_hasIdbFsev3
    annotations:
      string:
        tag: string
        value: 38
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFsev3
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFsev3
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFsev3
    alias: scales_hasIdbFsev3
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbAppdate:
    name: scales_hasIdbAppdate
    annotations:
      string:
        tag: string
        value: 234
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 01/01/1900
        example_object_type: string
        example_predicate: scales:hasIdbAppdate
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: 01/01/1900
        example_object_type: string
        example_predicate: scales:hasIdbAppdate
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbAppdate
    alias: scales_hasIdbAppdate
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbFoffcd5:
    name: scales_hasIdbFoffcd5
    annotations:
      double:
        tag: double
        value: 12
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFoffcd5
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFoffcd5
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFoffcd5
    alias: scales_hasIdbFoffcd5
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbAmtrec:
    name: scales_hasIdbAmtrec
    annotations:
      double:
        tag: double
        value: 18
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbAmtrec
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbAmtrec
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbAmtrec
    alias: scales_hasIdbAmtrec
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbDisp5:
    name: scales_hasIdbDisp5
    annotations:
      double:
        tag: double
        value: 3
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbDisp5
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbDisp5
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDisp5
    alias: scales_hasIdbDisp5
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbJudgment:
    name: scales_hasIdbJudgment
    annotations:
      double:
        tag: double
        value: 6
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbJudgment
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbJudgment
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbJudgment
    alias: scales_hasIdbJudgment
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbTofflvl5:
    name: scales_hasIdbTofflvl5
    annotations:
      double:
        tag: double
        value: 3
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTofflvl5
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTofflvl5
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTofflvl5
    alias: scales_hasIdbTofflvl5
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbTypemag:
    name: scales_hasIdbTypemag
    annotations:
      string:
        tag: string
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTypemag
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTypemag
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTypemag
    alias: scales_hasIdbTypemag
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbFsev4:
    name: scales_hasIdbFsev4
    annotations:
      string:
        tag: string
        value: 25
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFsev4
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFsev4
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFsev4
    alias: scales_hasIdbFsev4
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbProcdate:
    name: scales_hasIdbProcdate
    annotations:
      string:
        tag: string
        value: 176
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 01/03/2017
        example_object_type: string
        example_predicate: scales:hasIdbProcdate
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: 01/03/2017
        example_object_type: string
        example_predicate: scales:hasIdbProcdate
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProcdate
    alias: scales_hasIdbProcdate
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbSubsect:
    name: scales_hasIdbSubsect
    annotations:
      string:
        tag: string
        value: 83
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: (A
        example_object_type: string
        example_predicate: scales:hasIdbSubsect
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: (A
        example_object_type: string
        example_predicate: scales:hasIdbSubsect
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSubsect
    alias: scales_hasIdbSubsect
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasRelatedCase:
    name: scales_hasRelatedCase
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Case:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Case
        value: 3
      scales_Case:
        tag: scales_Case
        value: 3
      uri:
        tag: uri
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/CaseCivil
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
        example_predicate: scales:hasRelatedCase
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: scales:/CaseCivil
        example_object_type: scales_Case
        example_predicate: scales:hasRelatedCase
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: scales:/CaseCivil
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
        example_predicate: scales:hasRelatedCase
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    - object:
        example_object: scales:/CaseCivil
        example_object_type: scales_Case
        example_predicate: scales:hasRelatedCase
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    - object:
        example_object: scales:/CaseOther
        example_object_type: uri
        example_predicate: scales:hasRelatedCase
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: scales:/CaseOther
        example_object_type: uri
        example_predicate: scales:hasRelatedCase
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasRelatedCase
    alias: scales_hasRelatedCase
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: Any
    any_of:
    - range: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - range: uri
    - range: scales_Case
  scales_hasIdbTypetrn:
    name: scales_hasIdbTypetrn
    annotations:
      integer:
        tag: integer
        value: 1
      string:
        tag: string
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTypetrn
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTypetrn
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbTypetrn
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbTypetrn
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTypetrn
    alias: scales_hasIdbTypetrn
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: Any
    any_of:
    - range: string
    - range: integer
  scales_hasIdbFoffcd2:
    name: scales_hasIdbFoffcd2
    annotations:
      double:
        tag: double
        value: 44
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFoffcd2
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFoffcd2
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFoffcd2
    alias: scales_hasIdbFoffcd2
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbD2foffcd1:
    name: scales_hasIdbD2foffcd1
    annotations:
      double:
        tag: double
        value: 65
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1100.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2foffcd1
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '1100.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2foffcd1
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2foffcd1
    alias: scales_hasIdbD2foffcd1
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbTofflvl3:
    name: scales_hasIdbTofflvl3
    annotations:
      double:
        tag: double
        value: 4
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTofflvl3
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTofflvl3
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTofflvl3
    alias: scales_hasIdbTofflvl3
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbCounty:
    name: scales_hasIdbCounty
    annotations:
      double:
        tag: double
        value: 31
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '6005.0'
        example_object_type: double
        example_predicate: scales:hasIdbCounty
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '6005.0'
        example_object_type: double
        example_predicate: scales:hasIdbCounty
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCounty
    alias: scales_hasIdbCounty
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbNoj:
    name: scales_hasIdbNoj
    annotations:
      double:
        tag: double
        value: 7
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbNoj
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbNoj
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbNoj
    alias: scales_hasIdbNoj
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbDisp3:
    name: scales_hasIdbDisp3
    annotations:
      double:
        tag: double
        value: 5
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbDisp3
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbDisp3
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDisp3
    alias: scales_hasIdbDisp3
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbResidenc:
    name: scales_hasIdbResidenc
    annotations:
      double:
        tag: double
        value: 18
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbResidenc
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbResidenc
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbResidenc
    alias: scales_hasIdbResidenc
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbTrialend:
    name: scales_hasIdbTrialend
    annotations:
      string:
        tag: string
        value: 13
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 01/16/2019
        example_object_type: string
        example_predicate: scales:hasIdbTrialend
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: 01/16/2019
        example_object_type: string
        example_predicate: scales:hasIdbTrialend
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTrialend
    alias: scales_hasIdbTrialend
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbDisp4:
    name: scales_hasIdbDisp4
    annotations:
      double:
        tag: double
        value: 4
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbDisp4
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbDisp4
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDisp4
    alias: scales_hasIdbDisp4
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
    annotations:
      uri:
        tag: uri
        value: 6948
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/Agent/casd;;3:16-cv-01644_a2
        example_object_type: uri
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseJudge
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: scales:/Agent/casd;;3:16-cv-01644_a2
        example_object_type: uri
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseJudge
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseJudge
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: uri
  scales_hasIdbTtitle5:
    name: scales_hasIdbTtitle5
    annotations:
      string:
        tag: string
        value: 8
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTtitle5
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTtitle5
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTtitle5
    alias: scales_hasIdbTtitle5
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbFineamt5:
    name: scales_hasIdbFineamt5
    annotations:
      double:
        tag: double
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFineamt5
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFineamt5
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFineamt5
    alias: scales_hasIdbFineamt5
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbTransoff:
    name: scales_hasIdbTransoff
    annotations:
      string:
        tag: string
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTransoff
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTransoff
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTransoff
    alias: scales_hasIdbTransoff
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbPlt:
    name: scales_hasIdbPlt
    annotations:
      string:
        tag: string
        value: 1098
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbPlt
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbPlt
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPlt
    alias: scales_hasIdbPlt
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbDefno:
    name: scales_hasIdbDefno
    annotations:
      double:
        tag: double
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1.0'
        example_object_type: double
        example_predicate: scales:hasIdbDefno
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '1.0'
        example_object_type: double
        example_predicate: scales:hasIdbDefno
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDefno
    alias: scales_hasIdbDefno
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbSupvrel2:
    name: scales_hasIdbSupvrel2
    annotations:
      double:
        tag: double
        value: 9
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbSupvrel2
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbSupvrel2
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSupvrel2
    alias: scales_hasIdbSupvrel2
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbFugstat:
    name: scales_hasIdbFugstat
    annotations:
      string:
        tag: string
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: N
        example_object_type: string
        example_predicate: scales:hasIdbFugstat
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: N
        example_object_type: string
        example_predicate: scales:hasIdbFugstat
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFugstat
    alias: scales_hasIdbFugstat
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbFtitle4:
    name: scales_hasIdbFtitle4
    annotations:
      string:
        tag: string
        value: 35
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFtitle4
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFtitle4
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFtitle4
    alias: scales_hasIdbFtitle4
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbTtitle1:
    name: scales_hasIdbTtitle1
    annotations:
      string:
        tag: string
        value: 68
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTtitle1
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTtitle1
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTtitle1
    alias: scales_hasIdbTtitle1
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbPriscd5:
    name: scales_hasIdbPriscd5
    annotations:
      integer:
        tag: integer
        value: 1
      string:
        tag: string
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbPriscd5
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbPriscd5
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbPriscd5
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbPriscd5
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPriscd5
    alias: scales_hasIdbPriscd5
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: Any
    any_of:
    - range: string
    - range: integer
  scales_hasIdbFiledate:
    name: scales_hasIdbFiledate
    annotations:
      datetime:
        tag: datetime
        value: 327
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '2016-04-29T00:00:00'
        example_object_type: datetime
        example_predicate: scales:hasIdbFiledate
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '2016-04-29T00:00:00'
        example_object_type: datetime
        example_predicate: scales:hasIdbFiledate
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFiledate
    alias: scales_hasIdbFiledate
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: datetime
  scales_hasIdbTofflvl4:
    name: scales_hasIdbTofflvl4
    annotations:
      double:
        tag: double
        value: 4
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTofflvl4
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTofflvl4
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTofflvl4
    alias: scales_hasIdbTofflvl4
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbCttrtrn:
    name: scales_hasIdbCttrtrn
    annotations:
      double:
        tag: double
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCttrtrn
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCttrtrn
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCttrtrn
    alias: scales_hasIdbCttrtrn
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbTapeyear:
    name: scales_hasIdbTapeyear
    annotations:
      double:
        tag: double
        value: 10
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '2016.0'
        example_object_type: double
        example_predicate: scales:hasIdbTapeyear
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '2016.0'
        example_object_type: double
        example_predicate: scales:hasIdbTapeyear
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTapeyear
    alias: scales_hasIdbTapeyear
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  http___release.niem.gov_niem_domains_jxdm_7.2_StatuteKeywordText:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_StatuteKeywordText
    annotations:
      string:
        tag: string
        value: 211
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 00:0000 Cause Code Unknown
        example_object_type: string
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/StatuteKeywordText
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: 00:0000 Cause Code Unknown
        example_object_type: string
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/StatuteKeywordText
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/StatuteKeywordText
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_StatuteKeywordText
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbStatuscd:
    name: scales_hasIdbStatuscd
    annotations:
      string:
        tag: string
        value: 4
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: L
        example_object_type: string
        example_predicate: scales:hasIdbStatuscd
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: L
        example_object_type: string
        example_predicate: scales:hasIdbStatuscd
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbStatuscd
    alias: scales_hasIdbStatuscd
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbD2foffcd4:
    name: scales_hasIdbD2foffcd4
    annotations:
      double:
        tag: double
        value: 24
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2foffcd4
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2foffcd4
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2foffcd4
    alias: scales_hasIdbD2foffcd4
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbInt1:
    name: scales_hasIdbInt1
    annotations:
      double:
        tag: double
        value: 29
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbInt1
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbInt1
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbInt1
    alias: scales_hasIdbInt1
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbTermoff:
    name: scales_hasIdbTermoff
    annotations:
      integer:
        tag: integer
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbTermoff
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbTermoff
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTermoff
    alias: scales_hasIdbTermoff
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: integer
  scales_hasIdbFcounsel:
    name: scales_hasIdbFcounsel
    annotations:
      double:
        tag: double
        value: 4
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbFcounsel
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbFcounsel
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFcounsel
    alias: scales_hasIdbFcounsel
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbFoffcd1:
    name: scales_hasIdbFoffcd1
    annotations:
      double:
        tag: double
        value: 60
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1100.0'
        example_object_type: double
        example_predicate: scales:hasIdbFoffcd1
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '1100.0'
        example_object_type: double
        example_predicate: scales:hasIdbFoffcd1
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFoffcd1
    alias: scales_hasIdbFoffcd1
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbTrandist:
    name: scales_hasIdbTrandist
    annotations:
      integer:
        tag: integer
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbTrandist
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbTrandist
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTrandist
    alias: scales_hasIdbTrandist
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: integer
  scales_hasIdbInt3:
    name: scales_hasIdbInt3
    annotations:
      double:
        tag: double
        value: 136
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbInt3
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbInt3
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbInt3
    alias: scales_hasIdbInt3
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbIs_stub:
    name: scales_hasIdbIs_stub
    annotations:
      boolean:
        tag: boolean
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 'false'
        example_object_type: boolean
        example_predicate: scales:hasIdbIs_stub
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: 'false'
        example_object_type: boolean
        example_predicate: scales:hasIdbIs_stub
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbIs_stub
    alias: scales_hasIdbIs_stub
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: boolean
  scales_hasIdbTcounsel:
    name: scales_hasIdbTcounsel
    annotations:
      double:
        tag: double
        value: 5
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTcounsel
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTcounsel
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTcounsel
    alias: scales_hasIdbTcounsel
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbFineamt3:
    name: scales_hasIdbFineamt3
    annotations:
      double:
        tag: double
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFineamt3
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFineamt3
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFineamt3
    alias: scales_hasIdbFineamt3
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbArbit:
    name: scales_hasIdbArbit
    annotations:
      string:
        tag: string
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbArbit
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbArbit
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbArbit
    alias: scales_hasIdbArbit
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbDef:
    name: scales_hasIdbDef
    annotations:
      string:
        tag: string
        value: 1034
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '"BABIES ""R"" US, INC., ET AL"'
        example_object_type: string
        example_predicate: scales:hasIdbDef
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '"BABIES ""R"" US, INC., ET AL"'
        example_object_type: string
        example_predicate: scales:hasIdbDef
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDef
    alias: scales_hasIdbDef
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbFofflvl2:
    name: scales_hasIdbFofflvl2
    annotations:
      double:
        tag: double
        value: 4
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFofflvl2
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFofflvl2
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFofflvl2
    alias: scales_hasIdbFofflvl2
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Charge:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
        value: 6280
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/Charge/casd;;3:17-cr-00001_c0-1
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCharge
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: scales:/Charge/casd;;3:17-cr-00001_c0-1
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCharge
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCharge
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
  scales_hasIdbTtitle2:
    name: scales_hasIdbTtitle2
    annotations:
      string:
        tag: string
        value: 40
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTtitle2
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTtitle2
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTtitle2
    alias: scales_hasIdbTtitle2
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbTransdoc:
    name: scales_hasIdbTransdoc
    annotations:
      double:
        tag: double
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTransdoc
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTransdoc
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTransdoc
    alias: scales_hasIdbTransdoc
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbPristim4:
    name: scales_hasIdbPristim4
    annotations:
      double:
        tag: double
        value: 3
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbPristim4
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbPristim4
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristim4
    alias: scales_hasIdbPristim4
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbOffice:
    name: scales_hasIdbOffice
    annotations:
      string:
        tag: string
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '3'
        example_object_type: string
        example_predicate: scales:hasIdbOffice
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '3'
        example_object_type: string
        example_predicate: scales:hasIdbOffice
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbOffice
    alias: scales_hasIdbOffice
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbProbmon1:
    name: scales_hasIdbProbmon1
    annotations:
      double:
        tag: double
        value: 8
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbProbmon1
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbProbmon1
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbmon1
    alias: scales_hasIdbProbmon1
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbTofflvl1:
    name: scales_hasIdbTofflvl1
    annotations:
      double:
        tag: double
        value: 4
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTofflvl1
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbTofflvl1
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTofflvl1
    alias: scales_hasIdbTofflvl1
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbCtfilr:
    name: scales_hasIdbCtfilr
    annotations:
      double:
        tag: double
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCtfilr
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCtfilr
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtfilr
    alias: scales_hasIdbCtfilr
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbProbcd4:
    name: scales_hasIdbProbcd4
    annotations:
      integer:
        tag: integer
        value: 1
      string:
        tag: string
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbProbcd4
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbProbcd4
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbProbcd4
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbProbcd4
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbcd4
    alias: scales_hasIdbProbcd4
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: Any
    any_of:
    - range: string
    - range: integer
  scales_hasIdbTsev1:
    name: scales_hasIdbTsev1
    annotations:
      string:
        tag: string
        value: 44
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTsev1
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTsev1
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTsev1
    alias: scales_hasIdbTsev1
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  niem50_StartDate:
    name: niem50_StartDate
    annotations:
      date:
        tag: date
        value: 327
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '2016-05-23'
        example_object_type: date
        example_predicate: niem50:StartDate
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '2016-05-23'
        example_object_type: date
        example_predicate: niem50:StartDate
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: niem50:StartDate
    alias: niem50_StartDate
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: date
  scales_hasIdbFtitle3:
    name: scales_hasIdbFtitle3
    annotations:
      string:
        tag: string
        value: 57
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFtitle3
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFtitle3
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFtitle3
    alias: scales_hasIdbFtitle3
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbOrigin:
    name: scales_hasIdbOrigin
    annotations:
      double:
        tag: double
        value: 6
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '13.0'
        example_object_type: double
        example_predicate: scales:hasIdbOrigin
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '13.0'
        example_object_type: double
        example_predicate: scales:hasIdbOrigin
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbOrigin
    alias: scales_hasIdbOrigin
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbPristot:
    name: scales_hasIdbPristot
    annotations:
      double:
        tag: double
        value: 68
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-1.0'
        example_object_type: double
        example_predicate: scales:hasIdbPristot
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-1.0'
        example_object_type: double
        example_predicate: scales:hasIdbPristot
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristot
    alias: scales_hasIdbPristot
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbProcprog:
    name: scales_hasIdbProcprog
    annotations:
      double:
        tag: double
        value: 13
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbProcprog
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbProcprog
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProcprog
    alias: scales_hasIdbProcprog
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbCircuit:
    name: scales_hasIdbCircuit
    annotations:
      double:
        tag: double
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '9.0'
        example_object_type: double
        example_predicate: scales:hasIdbCircuit
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '9.0'
        example_object_type: double
        example_predicate: scales:hasIdbCircuit
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCircuit
    alias: scales_hasIdbCircuit
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbDeflgky:
    name: scales_hasIdbDeflgky
    annotations:
      string:
        tag: string
        value: 3441
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 097431700001CR0010
        example_object_type: string
        example_predicate: scales:hasIdbDeflgky
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: 097431700001CR0010
        example_object_type: string
        example_predicate: scales:hasIdbDeflgky
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbDeflgky
    alias: scales_hasIdbDeflgky
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbFtitle1:
    name: scales_hasIdbFtitle1
    annotations:
      string:
        tag: string
        value: 114
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 16:3372.F
        example_object_type: string
        example_predicate: scales:hasIdbFtitle1
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: 16:3372.F
        example_object_type: string
        example_predicate: scales:hasIdbFtitle1
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFtitle1
    alias: scales_hasIdbFtitle1
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbCtpn:
    name: scales_hasIdbCtpn
    annotations:
      double:
        tag: double
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCtpn
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCtpn
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtpn
    alias: scales_hasIdbCtpn
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbCaslgky:
    name: scales_hasIdbCaslgky
    annotations:
      string:
        tag: string
        value: 3441
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 097431700001CR0
        example_object_type: string
        example_predicate: scales:hasIdbCaslgky
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: 097431700001CR0
        example_object_type: string
        example_predicate: scales:hasIdbCaslgky
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCaslgky
    alias: scales_hasIdbCaslgky
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbJury:
    name: scales_hasIdbJury
    annotations:
      string:
        tag: string
        value: 4
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: B
        example_object_type: string
        example_predicate: scales:hasIdbJury
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: B
        example_object_type: string
        example_predicate: scales:hasIdbJury
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbJury
    alias: scales_hasIdbJury
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbTypereg:
    name: scales_hasIdbTypereg
    annotations:
      string:
        tag: string
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: CR
        example_object_type: string
        example_predicate: scales:hasIdbTypereg
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: CR
        example_object_type: string
        example_predicate: scales:hasIdbTypereg
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTypereg
    alias: scales_hasIdbTypereg
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbFsev2:
    name: scales_hasIdbFsev2
    annotations:
      string:
        tag: string
        value: 56
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFsev2
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFsev2
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFsev2
    alias: scales_hasIdbFsev2
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbFofflvl5:
    name: scales_hasIdbFofflvl5
    annotations:
      double:
        tag: double
        value: 3
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFofflvl5
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFofflvl5
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFofflvl5
    alias: scales_hasIdbFofflvl5
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbD2toffcd3:
    name: scales_hasIdbD2toffcd3
    annotations:
      double:
        tag: double
        value: 16
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2toffcd3
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2toffcd3
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2toffcd3
    alias: scales_hasIdbD2toffcd3
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbFsev5:
    name: scales_hasIdbFsev5
    annotations:
      string:
        tag: string
        value: 15
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFsev5
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbFsev5
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFsev5
    alias: scales_hasIdbFsev5
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbCtfiltrn:
    name: scales_hasIdbCtfiltrn
    annotations:
      double:
        tag: double
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1.0'
        example_object_type: double
        example_predicate: scales:hasIdbCtfiltrn
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '1.0'
        example_object_type: double
        example_predicate: scales:hasIdbCtfiltrn
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtfiltrn
    alias: scales_hasIdbCtfiltrn
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbCtfilwor:
    name: scales_hasIdbCtfilwor
    annotations:
      double:
        tag: double
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCtfilwor
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCtfilwor
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtfilwor
    alias: scales_hasIdbCtfilwor
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
        value: 4999
      http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
        value: 5000
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/DocketTable/casd;;3:16-cv-01644
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterOfActions
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: scales:/DocketTable/casd;;3:16-cv-01644
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterOfActions
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: scales:/DocketTable/casd;;3:16-cv-01644
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterOfActions
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    - object:
        example_object: scales:/DocketTable/casd;;3:16-cv-01644
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterOfActions
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterOfActions
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: Any
    any_of:
    - range: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
    - range: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
  scales_hasIdbSupvrel4:
    name: scales_hasIdbSupvrel4
    annotations:
      double:
        tag: double
        value: 3
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbSupvrel4
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbSupvrel4
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSupvrel4
    alias: scales_hasIdbSupvrel4
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbFineamt1:
    name: scales_hasIdbFineamt1
    annotations:
      double:
        tag: double
        value: 14
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFineamt1
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFineamt1
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFineamt1
    alias: scales_hasIdbFineamt1
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbPriscd4:
    name: scales_hasIdbPriscd4
    annotations:
      string:
        tag: string
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbPriscd4
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbPriscd4
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPriscd4
    alias: scales_hasIdbPriscd4
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbMdldock:
    name: scales_hasIdbMdldock
    annotations:
      string:
        tag: string
        value: 6
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbMdldock
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbMdldock
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbMdldock
    alias: scales_hasIdbMdldock
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbD2toffcd5:
    name: scales_hasIdbD2toffcd5
    annotations:
      double:
        tag: double
        value: 7
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2toffcd5
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2toffcd5
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2toffcd5
    alias: scales_hasIdbD2toffcd5
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbTranoff:
    name: scales_hasIdbTranoff
    annotations:
      integer:
        tag: integer
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbTranoff
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbTranoff
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTranoff
    alias: scales_hasIdbTranoff
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: integer
  scales_hasIdbNos:
    name: scales_hasIdbNos
    annotations:
      string:
        tag: string
        value: 69
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '110'
        example_object_type: string
        example_predicate: scales:hasIdbNos
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '110'
        example_object_type: string
        example_predicate: scales:hasIdbNos
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbNos
    alias: scales_hasIdbNos
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbTtitle3:
    name: scales_hasIdbTtitle3
    annotations:
      string:
        tag: string
        value: 20
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTtitle3
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTtitle3
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTtitle3
    alias: scales_hasIdbTtitle3
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbFsev1:
    name: scales_hasIdbFsev1
    annotations:
      string:
        tag: string
        value: 60
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '013'
        example_object_type: string
        example_predicate: scales:hasIdbFsev1
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '013'
        example_object_type: string
        example_predicate: scales:hasIdbFsev1
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFsev1
    alias: scales_hasIdbFsev1
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbCtdef:
    name: scales_hasIdbCtdef
    annotations:
      double:
        tag: double
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1.0'
        example_object_type: double
        example_predicate: scales:hasIdbCtdef
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '1.0'
        example_object_type: double
        example_predicate: scales:hasIdbCtdef
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCtdef
    alias: scales_hasIdbCtdef
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbSupvrel5:
    name: scales_hasIdbSupvrel5
    annotations:
      double:
        tag: double
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbSupvrel5
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbSupvrel5
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbSupvrel5
    alias: scales_hasIdbSupvrel5
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbProbcd5:
    name: scales_hasIdbProbcd5
    annotations:
      integer:
        tag: integer
        value: 1
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbProbcd5
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbProbcd5
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbcd5
    alias: scales_hasIdbProbcd5
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: integer
  scales_hasIdbJuris:
    name: scales_hasIdbJuris
    annotations:
      double:
        tag: double
        value: 4
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1.0'
        example_object_type: double
        example_predicate: scales:hasIdbJuris
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '1.0'
        example_object_type: double
        example_predicate: scales:hasIdbJuris
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbJuris
    alias: scales_hasIdbJuris
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  niem50_EndDate:
    name: niem50_EndDate
    annotations:
      date:
        tag: date
        value: 1106
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '2016-06-29'
        example_object_type: date
        example_predicate: niem50:EndDate
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '2016-06-29'
        example_object_type: date
        example_predicate: niem50:EndDate
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: niem50:EndDate
    alias: niem50_EndDate
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: date
  scales_hasIdbCttrwor:
    name: scales_hasIdbCttrwor
    annotations:
      double:
        tag: double
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCttrwor
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbCttrwor
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbCttrwor
    alias: scales_hasIdbCttrwor
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  niem50_JurisdictionText:
    name: niem50_JurisdictionText
    annotations:
      string:
        tag: string
        value: 4
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: Diversity
        example_object_type: string
        example_predicate: niem50:JurisdictionText
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: Diversity
        example_object_type: string
        example_predicate: niem50:JurisdictionText
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: niem50:JurisdictionText
    alias: niem50_JurisdictionText
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbFofflvl3:
    name: scales_hasIdbFofflvl3
    annotations:
      double:
        tag: double
        value: 4
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFofflvl3
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFofflvl3
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFofflvl3
    alias: scales_hasIdbFofflvl3
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbToffcd1:
    name: scales_hasIdbToffcd1
    annotations:
      double:
        tag: double
        value: 38
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbToffcd1
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbToffcd1
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbToffcd1
    alias: scales_hasIdbToffcd1
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbFinetot:
    name: scales_hasIdbFinetot
    annotations:
      double:
        tag: double
        value: 13
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbFinetot
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '0.0'
        example_object_type: double
        example_predicate: scales:hasIdbFinetot
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFinetot
    alias: scales_hasIdbFinetot
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbTsev2:
    name: scales_hasIdbTsev2
    annotations:
      string:
        tag: string
        value: 31
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTsev2
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbTsev2
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbTsev2
    alias: scales_hasIdbTsev2
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbFineamt2:
    name: scales_hasIdbFineamt2
    annotations:
      double:
        tag: double
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFineamt2
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbFineamt2
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbFineamt2
    alias: scales_hasIdbFineamt2
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbMagdock:
    name: scales_hasIdbMagdock
    annotations:
      double:
        tag: double
        value: 3216
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbMagdock
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbMagdock
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbMagdock
    alias: scales_hasIdbMagdock
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_Party:
    name: scales_Party
    annotations:
      scales_Party:
        tag: scales_Party
        value: 2319
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/Agent/casd;;3:16-cv-01645_a3
        example_object_type: scales_Party
        example_predicate: scales:Party
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: scales:/Agent/casd;;3:16-cv-01645_a3
        example_object_type: scales_Party
        example_predicate: scales:Party
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:Party
    alias: scales_Party
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: scales_Party
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Court:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Court
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/Court/casd
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Court
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: scales:/Court/casd
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Court
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: http___release.niem.gov_niem_domains_jxdm_7.2_Court
  scales_hasIdbPriscd1:
    name: scales_hasIdbPriscd1
    annotations:
      string:
        tag: string
        value: 8
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbPriscd1
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbPriscd1
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPriscd1
    alias: scales_hasIdbPriscd1
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbD2foffcd3:
    name: scales_hasIdbD2foffcd3
    annotations:
      double:
        tag: double
        value: 37
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2foffcd3
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2foffcd3
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2foffcd3
    alias: scales_hasIdbD2foffcd3
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbD2foffcd2:
    name: scales_hasIdbD2foffcd2
    annotations:
      double:
        tag: double
        value: 51
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2foffcd2
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2foffcd2
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2foffcd2
    alias: scales_hasIdbD2foffcd2
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbPristim5:
    name: scales_hasIdbPristim5
    annotations:
      double:
        tag: double
        value: 2
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbPristim5
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbPristim5
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristim5
    alias: scales_hasIdbPristim5
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbD2foffcd5:
    name: scales_hasIdbD2foffcd5
    annotations:
      double:
        tag: double
        value: 13
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2foffcd5
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbD2foffcd5
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbD2foffcd5
    alias: scales_hasIdbD2foffcd5
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
  scales_hasIdbProbcd2:
    name: scales_hasIdbProbcd2
    annotations:
      integer:
        tag: integer
        value: 1
      string:
        tag: string
        value: 3
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbProbcd2
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: string
        example_predicate: scales:hasIdbProbcd2
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbProbcd2
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8'
        example_object_type: integer
        example_predicate: scales:hasIdbProbcd2
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbProbcd2
    alias: scales_hasIdbProbcd2
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: Any
    any_of:
    - range: string
    - range: integer
  niem50_CaseDocketID:
    name: niem50_CaseDocketID
    annotations:
      string:
        tag: string
        value: 5000
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 3:16-cv-01644
        example_object_type: string
        example_predicate: niem50:CaseDocketID
        example_subject: scales:/CaseCivil
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: 3:16-cv-01644
        example_object_type: string
        example_predicate: niem50:CaseDocketID
        example_subject: scales:/CaseCivil
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: niem50:CaseDocketID
    alias: niem50_CaseDocketID
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: string
  scales_hasIdbPristim3:
    name: scales_hasIdbPristim3
    annotations:
      double:
        tag: double
        value: 15
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbPristim3
        example_subject: scales:/CaseCriminal
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - object:
        example_object: '-8.0'
        example_object_type: double
        example_predicate: scales:hasIdbPristim3
        example_subject: scales:/CaseCriminal
        example_subject_type: scales_Case
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasIdbPristim3
    alias: scales_hasIdbPristim3
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Case
    - scales_Case
    range: double
class_uri: http://release.niem.gov/niem/domains/jxdm/7.2/Case

```
</details>