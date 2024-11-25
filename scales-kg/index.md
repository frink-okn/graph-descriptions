# TODO_Give_this_schema_a_name!

TODO -- tell the world what this schema describes.

URI: scales-kg

Name: scales-kg



## Schema Diagram

```mermaid
erDiagram
Any {

}
ScalesAgent {
    string scales_hasExtraInfo  
    string scales_hasName  
    string scales_hasAgentType  
    uri scales_hasReferenceInExtraInfo  
    uri scales_isInstanceOfEntity  
    string scales_hasRoleInCase  
    string scales_hasAddress  
}
ScalesCaseCivil {
    double scales_hasIdbAmtrec  
    string scales_hasCause  
    string scales_hasPacerID  
    double scales_hasIdbOrigin  
    double scales_hasIdbJudgment  
    double scales_hasIdbTapeyear  
    string scales_hasIdbArbit  
    string scales_hasIdbMdldock  
    string scales_hasIdbTransorg  
    string scales_hasIdbTrmarb  
    string scales_hasIdbFdateuse  
    double scales_hasIdbNoj  
    double scales_hasIdbProse  
    string scales_hasIdbSection  
    string scales_hasIdbTransdat  
    double scales_hasIdbProcprog  
    string scales_hasIdbSubsect  
    double scales_hasIdbTransdoc  
    double scales_hasIdbDemanded  
    string scales_hasIdbOffice  
    string scales_hasIdbDistrict  
    string scales_hasIdbTribegan  
    string scales_hasIdbDocket  
    string scales_hasStatus  
    double scales_hasIdbClassact  
    boolean scales_hasIdbIs_stub  
    double scales_hasIdbDisp  
    string scales_hasIdbPretrial  
    string scales_hasIdbTitl  
    string scales_hasIdbJury  
    string scales_hasIdbPlt  
    double scales_hasIdbResidenc  
    double scales_hasIdbJuris  
    double scales_hasIdbCircuit  
    string scales_hasJurisdiction  
    string scales_hasIdbStatuscd  
    string scales_hasIdbTrialend  
    string scales_hasIdbDef  
    datetime scales_hasIdbFiledate  
    double scales_hasIdbTrclact  
    string scales_hasIdbTransoff  
    double scales_hasIdbCounty  
    string scales_hasIdbTdateuse  
    string scales_hasIdbIfp  
    string scales_hasIdbDjoined  
    string scales_hasIdbNos  
    string scales_hasNatureSuit  
    datetime scales_hasIdbTermdate  
}
ScalesCaseCriminal {
    double scales_hasIdbProbtot  
    double scales_hasIdbFofflvl2  
    double scales_hasIdbDisp1  
    string scales_hasIdbFtitle3  
    double scales_hasIdbDisp4  
    double scales_hasIdbTapeyear  
    double scales_hasIdbDisp2  
    double scales_hasIdbProbmon2  
    double scales_hasIdbVer  
    double scales_hasIdbCtfilwor  
    double scales_hasIdbFcounsel  
    double scales_hasIdbMagdock  
    double scales_hasIdbSupvrel2  
    string scales_hasIdbDeflgky  
    double scales_hasIdbCttrr  
    string scales_hasIdbDispdate  
    double scales_hasIdbCtdef  
    double scales_hasIdbFoffcd3  
    string scales_hasIdbDocket  
    double scales_hasIdbPristim4  
    double scales_hasIdbProbmon3  
    double scales_hasIdbFineamt2  
    string scales_hasIdbFgenddate  
    string scales_hasIdbFgstrtdate  
    double scales_hasIdbFineamt1  
    double scales_hasIdbD2foffcd1  
    string scales_hasIdbTsev1  
    string scales_hasIdbTypemag  
    string scales_hasIdbTtitle5  
    double scales_hasIdbCttrtrn  
    double scales_hasIdbD2toffcd2  
    double scales_hasIdbTrandef  
    double scales_hasIdbCttrwor  
    double scales_hasIdbD2foffcd4  
    double scales_hasIdbToffcd2  
    double scales_hasIdbCtfilr  
    string scales_hasIdbFsev1  
    double scales_hasIdbFofflvl1  
    string scales_hasIdbAppcd  
    double scales_hasIdbFiscalyr  
    string scales_hasIdbTtitle2  
    string scales_hasIdbSentdate  
    double scales_hasIdbInt1  
    string scales_hasIdbTtitle3  
    string scales_hasStatus  
    boolean scales_hasIdbIs_stub  
    string scales_hasIdbTypereg  
    double scales_hasIdbInt2  
    double scales_hasIdbCttr  
    double scales_hasIdbToffcd4  
    datetime scales_hasIdbFiledate  
    double scales_hasIdbMagdef  
    double scales_hasIdbTofflvl4  
    double scales_hasIdbCounty  
    double scales_hasIdbD2toffcd1  
    string scales_hasIdbFtitle5  
    double scales_hasIdbInt3  
    double scales_hasIdbDisp3  
    datetime scales_hasIdbTermdate  
    double scales_hasIdbFinetot  
    double scales_hasIdbPristim5  
    double scales_hasIdbFineamt4  
    string scales_hasIdbProbcd1  
    double scales_hasIdbTofflvl1  
    double scales_hasIdbPristim1  
    string scales_hasPacerID  
    double scales_hasIdbTcounsel  
    double scales_hasIdbD2toffcd4  
    double scales_hasIdbCtpnwof  
    double scales_hasIdbProccd  
    double scales_hasIdbFoffcd2  
    double scales_hasIdbFoffcd4  
    string scales_hasIdbCaslgky  
    double scales_hasIdbSupvrel5  
    double scales_hasIdbToffcd5  
    double scales_hasIdbDefno  
    string scales_hasIdbFsev2  
    double scales_hasIdbD2foffcd3  
    double scales_hasIdbPristim3  
    string scales_hasIdbFtitle2  
    double scales_hasIdbFoffcd1  
    double scales_hasIdbReopseq  
    double scales_hasIdbTofflvl3  
    string scales_hasIdbTtitle1  
    double scales_hasIdbD2foffcd2  
    string scales_hasIdbStatuscd  
    string scales_hasIdbAppdate  
    double scales_hasIdbToffcd3  
    double scales_hasIdbProbmon4  
    string scales_hasIdbProcdate  
    double scales_hasIdbFineamt5  
    string scales_hasIdbPriscd3  
    string scales_hasIdbFsev3  
    double scales_hasIdbToffcd1  
    double scales_hasIdbD2toffcd5  
    double scales_hasIdbPristim2  
    double scales_hasIdbSupvrel4  
    double scales_hasIdbTrandock  
    double scales_hasIdbProbmon1  
    string scales_hasIdbFtitle1  
    double scales_hasIdbCtfiltrn  
    double scales_hasIdbFofflvl4  
    string scales_hasIdbPriscd1  
    string scales_hasIdbFtitle4  
    double scales_hasIdbFoffcd5  
    string scales_hasIdbLoaddate  
    double scales_hasIdbTofflvl5  
    string scales_hasIdbOffice  
    string scales_hasIdbTtitle4  
    string scales_hasIdbDistrict  
    double scales_hasIdbSupvrel1  
    double scales_hasIdbCtpn  
    double scales_hasIdbProbmon5  
    double scales_hasIdbD2toffcd3  
    string scales_hasIdbUpdate  
    string scales_hasIdbFugstat  
    double scales_hasIdbCircuit  
    string scales_hasJurisdiction  
    string scales_hasIdbPriscd2  
    double scales_hasIdbFineamt3  
    double scales_hasIdbFofflvl5  
    double scales_hasIdbTofflvl2  
    double scales_hasIdbD2foffcd5  
    double scales_hasIdbSupvrel3  
    double scales_hasIdbDisp5  
    double scales_hasIdbCtfil  
    double scales_hasIdbFofflvl3  
    double scales_hasIdbPristot  
}
ScalesCharge {
    string scales_hasPacerID  
    string scales_hasContents  
}
ScalesCourt {
    string scales_isInCourtSystem  
    string scales_hasName  
    string scales_isInCircuit  
}
ScalesDocketEntry {
    uri scales_hasIfpLabel  
    string scales_hasPacerID  
    string scales_hasContents  
    uri scales_hasOntologyLabel  
    uri scales_hasIfpJudgeAttribution  
}
ScalesDocketTable {

}

ScalesAgent ||--|o ScalesAgent : "scales_isInFirm"
ScalesAgent ||--|o ScalesAgent : "scales_assignedToDefendant"
ScalesAgent ||--|o ScalesCharge : "scales_hasCharge"
ScalesAgent ||--|o ScalesAgent : "scales_hasRepresentation"
ScalesCaseCivil ||--|o Any : "scales_hasFilingDate"
ScalesCaseCivil ||--|o Any : "scales_hasRelatedCase"
ScalesCaseCivil ||--|o ScalesAgent : "scales_hasAgent"
ScalesCaseCivil ||--|o Any : "scales_hasTerminatingDate"
ScalesCaseCivil ||--|o ScalesCaseCivil : "scales_hasMemberCase"
ScalesCaseCivil ||--|o ScalesCourt : "scales_isInCourt"
ScalesCaseCivil ||--|o ScalesDocketTable : "scales_hasDocketTable"
ScalesCaseCriminal ||--|o Any : "scales_hasRelatedCase"
ScalesCaseCriminal ||--|o Any : "scales_hasIdbTsev2"
ScalesCaseCriminal ||--|o Any : "scales_hasIdbPriscd5"
ScalesCaseCriminal ||--|o Any : "scales_hasIdbFsev5"
ScalesCaseCriminal ||--|o ScalesCaseCivil : "scales_hasMemberCase"
ScalesCaseCriminal ||--|o Any : "scales_hasIdbProbcd2"
ScalesCaseCriminal ||--|o Any : "scales_hasIdbProbcd5"
ScalesCaseCriminal ||--|o Any : "scales_hasIdbPriscd4"
ScalesCaseCriminal ||--|o Any : "scales_hasIdbTypetrn"
ScalesCaseCriminal ||--|o ScalesCharge : "scales_hasCharge"
ScalesCaseCriminal ||--|o ScalesDocketTable : "scales_hasDocketTable"
ScalesCaseCriminal ||--|o Any : "scales_hasIdbFsev4"
ScalesCaseCriminal ||--|o Any : "scales_hasFilingDate"
ScalesCaseCriminal ||--|o Any : "scales_hasIdbTrandist"
ScalesCaseCriminal ||--|o ScalesAgent : "scales_hasAgent"
ScalesCaseCriminal ||--|o Any : "scales_hasIdbTsev5"
ScalesCaseCriminal ||--|o Any : "scales_hasIdbProbcd3"
ScalesCaseCriminal ||--|o Any : "scales_hasIdbProbcd4"
ScalesCaseCriminal ||--|o Any : "scales_hasIdbTsev4"
ScalesCaseCriminal ||--|o Any : "scales_hasIdbTsev3"
ScalesCaseCriminal ||--|o ScalesCourt : "scales_isInCourt"
ScalesCaseCriminal ||--|o Any : "scales_hasIdbTermoff"
ScalesCaseCriminal ||--|o Any : "scales_hasIdbTranoff"
ScalesCaseCriminal ||--|o Any : "scales_hasTerminatingDate"
ScalesDocketEntry ||--|o Any : "scales_hasFilingDate"
ScalesDocketEntry ||--|o Any : "scales_hasReference"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1856"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2089"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1302"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__909"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1156"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__358"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1326"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1934"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2121"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__81"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1179"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1219"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1369"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__917"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3199"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1482"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__966"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3502"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3415"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3736"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__899"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1739"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2341"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2846"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4558"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1728"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3684"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3247"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3410"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1311"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3036"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3256"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2820"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__822"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3856"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__631"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4143"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1136"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__614"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2447"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3660"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3922"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3073"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2641"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1819"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1330"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3908"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__397"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1141"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4640"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2448"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4346"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3305"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4621"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2180"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3675"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2541"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3884"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3881"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__183"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__436"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3171"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__413"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1610"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2520"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1296"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3750"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3758"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2871"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2144"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__686"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2652"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__240"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2860"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1364"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1397"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1817"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4470"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3189"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3076"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1117"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3287"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__335"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4239"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2390"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4629"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3727"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__616"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1940"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4177"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3456"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__396"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__512"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1052"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1277"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3739"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4338"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__230"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__801"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4602"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__46"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__728"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2170"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__910"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3334"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1201"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4222"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__316"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2433"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3954"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2279"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3999"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__716"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3596"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4739"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__40"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2651"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1028"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3680"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2301"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__638"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3857"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1598"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3484"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3991"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4267"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1722"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__386"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1918"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4539"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2343"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3599"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1188"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2665"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4069"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4601"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__689"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1075"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1275"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3699"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3885"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1102"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3168"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1215"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2838"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3523"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1229"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4219"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2859"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__833"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3588"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2031"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2784"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4020"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__475"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__829"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__612"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__274"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4255"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2922"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4272"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__806"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2194"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2865"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__681"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__594"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__713"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3980"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3015"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1809"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3021"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1983"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__255"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3082"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4279"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4323"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4277"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2769"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4589"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1119"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1162"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2177"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4213"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3695"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2482"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1627"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3027"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3231"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4394"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3226"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4726"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2654"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4325"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2417"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2358"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__942"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__824"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2721"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3243"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3863"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4775"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__471"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__399"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1488"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3731"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4748"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1682"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__326"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1829"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2062"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3448"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3712"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4299"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__357"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2864"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3838"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1697"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3019"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__170"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4356"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__650"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3441"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2685"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1127"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2409"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__393"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4729"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2502"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3611"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2813"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2944"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2618"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1349"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2427"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3655"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4492"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3446"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4749"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2639"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3928"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4203"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4529"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2950"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2984"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3931"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__28"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__823"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4816"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2804"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__70"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4036"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__62"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__5"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1128"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1025"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2101"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3526"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3718"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1500"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1587"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4751"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__717"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2255"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2598"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2164"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__172"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2997"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1684"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3033"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3241"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3435"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4475"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1492"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1796"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3976"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2483"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1443"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3364"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3190"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1549"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3737"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__82"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3920"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3016"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4026"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2152"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4820"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4718"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3195"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1556"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1928"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3356"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3730"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3221"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2568"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4154"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3510"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__693"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2941"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3501"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1672"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3766"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__953"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4198"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2947"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__767"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3298"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4133"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2163"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3346"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2302"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3351"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3648"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2816"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1816"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__533"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1266"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3990"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__382"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2381"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4189"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2100"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2595"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4214"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2004"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__597"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2874"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__75"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4132"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4296"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2703"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3669"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__179"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2340"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3117"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4268"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1166"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3724"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__470"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__679"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2262"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__327"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2442"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2017"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__557"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__510"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2967"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4567"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1029"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2600"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1552"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2299"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2828"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3393"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4095"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3983"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1527"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2588"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1762"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4685"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4023"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1962"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3952"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3071"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__807"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1637"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1815"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1990"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3266"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4275"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4686"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__692"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3290"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4764"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2497"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3409"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3658"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1006"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3102"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4098"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__437"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1915"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__727"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4626"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2008"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__675"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1555"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3443"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__965"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1841"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1336"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1503"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3026"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4442"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2268"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1987"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3143"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__949"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__655"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1268"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2148"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2242"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3225"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__746"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1886"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2522"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1755"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3235"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__374"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__207"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__809"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1593"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1704"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2258"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2376"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__642"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3422"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2524"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1083"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4019"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1505"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4545"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2151"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4728"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3847"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__493"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1486"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3039"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4731"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__414"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__604"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1800"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__484"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2766"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3772"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4246"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__113"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1694"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3406"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3457"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2099"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__890"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4834"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1415"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3486"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__193"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3138"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1861"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4201"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4803"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1389"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1345"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__945"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3673"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4037"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4419"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4462"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4503"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2306"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1973"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1220"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__158"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2217"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__246"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__577"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1061"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1808"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2955"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1200"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4251"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1467"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2471"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4804"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1960"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3233"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1901"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4195"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4256"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__250"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3476"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4505"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4575"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4432"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__952"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3910"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2316"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4563"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2323"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2216"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1267"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1258"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1885"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3308"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4212"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3937"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__842"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3366"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1797"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3327"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4499"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4109"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3383"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2957"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4772"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1977"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1551"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1404"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2388"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1976"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2719"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2962"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__832"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__736"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2129"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2338"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3876"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3325"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4457"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1422"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2951"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3299"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1407"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1740"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2276"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__541"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__571"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1440"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__257"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3694"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4185"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1721"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1144"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4359"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1851"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__236"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3429"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3533"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__485"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1656"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2705"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__879"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4210"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3764"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__659"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1561"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2631"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2771"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3052"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1388"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2872"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__313"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__508"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__198"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3259"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__840"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3289"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1821"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1712"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1520"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3508"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3613"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3654"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4643"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4084"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1197"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4223"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4537"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3439"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1222"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2720"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1699"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4794"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__370"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4193"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2239"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2849"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2248"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3280"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__765"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4163"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2077"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1663"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1513"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4075"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2293"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2928"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1812"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2492"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3391"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4207"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1910"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3780"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1607"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1163"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__122"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4451"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3063"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__395"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1435"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1852"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4400"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3061"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4711"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__338"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3800"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3748"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2453"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3359"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3238"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1406"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3471"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4784"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__719"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2230"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3255"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3957"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4334"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4392"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2776"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2848"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4266"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__340"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4471"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3513"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1898"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3372"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4425"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__498"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__652"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1708"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2854"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1833"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2468"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2564"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4436"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3165"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2544"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__293"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__634"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4590"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3417"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4418"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__906"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2679"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2359"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1481"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3738"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1544"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3707"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3932"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4582"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1978"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2673"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__812"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2454"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2649"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1168"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__11"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__342"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2556"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1888"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3104"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3560"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4548"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1547"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4722"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3690"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3751"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2171"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2214"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4452"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3961"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4066"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2912"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1716"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4725"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4211"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4433"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4408"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2157"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2733"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1024"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1175"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1120"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4635"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1563"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4709"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2534"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1421"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1393"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1763"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1381"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2197"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4187"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3163"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1099"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__851"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3272"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__352"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__874"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3275"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3453"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__667"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2123"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1840"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1853"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2783"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2205"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1858"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2535"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3962"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3329"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1189"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__908"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3087"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1062"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__975"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3023"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4329"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2731"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3375"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3817"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3408"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2800"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3503"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3872"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4401"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1195"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1726"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1137"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3784"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__564"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2218"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__460"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3978"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1836"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1423"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4243"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2515"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4806"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__836"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3814"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3551"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__855"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3723"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__780"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__831"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__866"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__523"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3395"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__868"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__438"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__889"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1842"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2408"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1403"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3056"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3122"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1955"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__345"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__701"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2467"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4274"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1718"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__867"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__838"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__862"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2632"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3401"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1105"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3986"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3267"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2603"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3384"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4123"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2579"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3149"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4778"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2425"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__891"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2933"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1320"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1368"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1579"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3239"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4005"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4042"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2310"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4318"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4675"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1965"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3797"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__636"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2116"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3569"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__551"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__49"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1271"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2393"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2460"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3657"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3771"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__48"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__449"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__666"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__164"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__886"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2091"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2117"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4073"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4687"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3302"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4441"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__281"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3038"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__419"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4542"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1017"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1372"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2366"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__750"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1623"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__757"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__961"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2545"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3096"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3193"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3688"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3089"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3803"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__565"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1262"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4577"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4702"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__331"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__774"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3821"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2606"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3187"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3413"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2437"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4472"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2498"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2799"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__758"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2758"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1408"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1496"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__403"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2701"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__100"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3620"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3084"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1648"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3121"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3733"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3859"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4554"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1378"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1300"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3388"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2883"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2349"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1899"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2945"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__265"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3829"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1365"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2718"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4512"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2414"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__210"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__827"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1446"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1257"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1690"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2092"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2463"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__433"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4220"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4312"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__220"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3357"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1502"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1635"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__607"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3808"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4138"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3301"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2615"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1441"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__611"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__124"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2810"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1328"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__333"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4756"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1092"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__987"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__260"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2477"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3303"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2642"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4157"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__515"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3095"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4798"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1780"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1867"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2397"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1431"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__237"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__561"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__381"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1478"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2549"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1057"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1081"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1631"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1911"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__64"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2525"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3552"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3924"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3629"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1323"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1147"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1713"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__819"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3109"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__446"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3110"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__579"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4795"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1080"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2698"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3070"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1569"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2029"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3389"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2020"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4814"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2108"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2396"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__273"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__554"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2994"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3066"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3092"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2181"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1246"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4049"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__462"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3639"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__653"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__286"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1844"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2480"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__766"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2264"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2806"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1666"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__585"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1086"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1759"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2155"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3543"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1734"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2402"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__428"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3064"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3337"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__79"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3972"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4320"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__725"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4340"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4412"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__29"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__818"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3315"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4298"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4818"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1504"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2439"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1491"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1158"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4002"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3172"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__705"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4230"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1792"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__740"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__796"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1027"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__898"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2830"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3106"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3178"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4482"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4618"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4785"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2726"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1538"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2154"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3004"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3646"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2115"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4693"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2992"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2076"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1490"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2098"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1030"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__935"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1339"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1889"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2607"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3837"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4387"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4088"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4162"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2966"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4566"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__578"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__298"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3528"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1948"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__516"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3160"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1917"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3511"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4481"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2902"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4796"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2913"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3477"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3529"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2087"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2670"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3464"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3935"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3512"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4031"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4809"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__971"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__418"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4047"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3182"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2043"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3651"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1640"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4519"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1675"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4724"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2048"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2504"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2650"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2095"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2173"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1485"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2886"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3248"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1616"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3682"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4287"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__582"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4396"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1410"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__369"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__894"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4159"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4067"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1984"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2904"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4596"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__999"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1929"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2042"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2903"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3656"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1122"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__821"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3042"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3752"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3875"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__640"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4091"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3763"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3710"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4166"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4696"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2687"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4754"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__310"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1160"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1192"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1234"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1355"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__421"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2274"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4120"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4293"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__627"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1864"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2292"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__21"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1770"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3373"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__924"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1470"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1019"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1810"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2619"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1732"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2901"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3139"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4782"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3099"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3504"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2079"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3200"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3672"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4714"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1107"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3603"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__262"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3546"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3028"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4390"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__447"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__915"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2069"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3169"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__626"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2088"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1060"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1239"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2288"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__931"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3324"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4708"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3081"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__119"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3374"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2403"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1668"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__478"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3853"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__710"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__673"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3994"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4565"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2451"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3336"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3879"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3644"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2919"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2386"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3705"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1098"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1908"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2740"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1974"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3677"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4738"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__684"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4253"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3367"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4488"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2280"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4227"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2404"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3332"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3263"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1475"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4599"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__291"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__762"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4659"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2307"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__150"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2526"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__480"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4431"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1803"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3181"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2449"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2621"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__464"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__339"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2046"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3029"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3703"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3940"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1396"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__222"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2182"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3281"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3862"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1626"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__947"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3093"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4281"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__658"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1324"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1913"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4140"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2802"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3179"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3167"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1863"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2269"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__789"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__341"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__753"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3382"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3430"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__973"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__503"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__450"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4386"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4802"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__610"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__221"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4608"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1048"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1217"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1776"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2272"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4721"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3312"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3192"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__456"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1233"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__902"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1644"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3671"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4118"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__231"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2982"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3246"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1715"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__690"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3474"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3918"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3338"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1148"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4841"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__608"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__143"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1835"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2532"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2586"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__720"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1273"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3058"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4448"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__98"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2893"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2821"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__52"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3153"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2797"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__496"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__764"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2514"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__354"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__936"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__30"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__856"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1939"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2420"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3459"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4257"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__199"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2109"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3347"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3984"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3342"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__15"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2494"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1232"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2822"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3754"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4641"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4665"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2601"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3293"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2475"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1517"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1941"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3897"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4572"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1963"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2219"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2036"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3595"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2236"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1553"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3050"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1159"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1034"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__511"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2419"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2695"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1449"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__459"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4310"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2464"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1698"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1589"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1993"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__913"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3465"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3594"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1832"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4007"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__581"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3133"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3572"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2993"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__402"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1121"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2485"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2572"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1935"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2553"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__50"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__123"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__587"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__888"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2054"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2801"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3265"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3630"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2174"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3888"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2969"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1646"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3428"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2304"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2924"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1937"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2074"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__83"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2146"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2321"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2550"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3313"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1427"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3271"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1124"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2920"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3054"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2499"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3686"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1196"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4517"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3183"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2135"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__656"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1351"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2611"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1111"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2015"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__911"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3556"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4171"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2882"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3589"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2184"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4215"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4270"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__562"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3561"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1472"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2479"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__120"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1719"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2259"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3774"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1979"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4474"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4591"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1023"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1108"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4311"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1264"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__861"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2318"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4716"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2840"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3831"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4284"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4439"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2400"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2630"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__787"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__800"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1226"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2958"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3111"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3250"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1916"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4057"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4082"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1424"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3294"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3397"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1705"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__35"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1469"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2250"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3479"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1879"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__549"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4534"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__132"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1070"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__955"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2814"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2625"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__51"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1115"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4136"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4247"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1964"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2942"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1434"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3261"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1992"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3614"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__651"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3276"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4671"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2717"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1727"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3118"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2843"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1180"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3296"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3647"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4477"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__309"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2203"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__271"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2090"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3760"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1782"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4495"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1518"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__489"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3291"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3022"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4089"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1655"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3204"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__514"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2324"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2053"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__289"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2853"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__321"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2938"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2591"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1398"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1580"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2212"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3170"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__895"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3547"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4081"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__156"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__127"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2825"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4161"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2737"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4480"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3257"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3176"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4362"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__324"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__873"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4381"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__682"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__964"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3031"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2858"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3394"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3891"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4260"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4030"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4263"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1756"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2002"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2885"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2141"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3945"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4580"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3014"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__280"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__468"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1866"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3608"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1100"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2734"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3497"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1480"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3209"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4610"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4252"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__518"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__424"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3447"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4048"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1416"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__18"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__74"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4054"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1291"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4158"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2824"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__905"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2910"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__253"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2126"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1958"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3449"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4040"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3156"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4324"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1456"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4363"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2395"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2033"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1900"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__166"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4101"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1169"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__439"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__137"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4130"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2070"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1970"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4062"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2459"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1242"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__167"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2104"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4624"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3874"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4765"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__398"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1590"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2890"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__904"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2314"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2196"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4597"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3363"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1116"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3292"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2371"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2474"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1700"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2961"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4715"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2677"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__134"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2834"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2113"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3402"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3130"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2368"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__160"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2422"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1933"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2013"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2831"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3330"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3328"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4206"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__368"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2192"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__994"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__391"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__933"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1730"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2392"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4097"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3350"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2723"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4553"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1459"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2384"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4676"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2249"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4700"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4791"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4445"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4736"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1912"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4351"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2972"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4459"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__141"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1453"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1016"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1605"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1878"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1971"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__542"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1554"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1205"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1657"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1982"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3088"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3557"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1749"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1375"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2183"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4056"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2911"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2215"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2569"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2574"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1506"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__334"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2732"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__988"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2949"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__520"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1022"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2739"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3981"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2357"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3850"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__33"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4153"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2281"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2512"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3697"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2378"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3834"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__185"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1405"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2521"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3685"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1251"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2240"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3995"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1333"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2456"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3048"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__411"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4730"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2507"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__323"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4044"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2965"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2150"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1208"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__726"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1811"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2671"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2694"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3224"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4759"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3147"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2594"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4524"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1474"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3427"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1860"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4341"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4790"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1772"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3131"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3701"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__782"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3565"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3971"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4156"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__0"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2351"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1751"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2335"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2510"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3236"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1831"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1639"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1353"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2682"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__93"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4805"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__685"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1688"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__366"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2952"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4090"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1011"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4350"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__22"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4771"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3550"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__380"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1097"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4131"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3963"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1464"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4719"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1051"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__641"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2283"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3871"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3947"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4450"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3698"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2424"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3866"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1288"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__588"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2678"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4421"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4061"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3977"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4508"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__264"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__618"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2124"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4167"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__487"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3331"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3602"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4587"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1597"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1309"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2833"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4134"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3996"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4510"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2604"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4141"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2749"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1515"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3069"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2160"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4391"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__589"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__606"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2127"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2857"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2762"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3032"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3100"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3951"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4170"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2647"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1524"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3268"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__268"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1343"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3582"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3740"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4183"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2107"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4378"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__628"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1287"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1426"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3144"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__36"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4426"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4454"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__58"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1945"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4613"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1765"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__252"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1968"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2836"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2915"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2363"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__647"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4812"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__131"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__596"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1454"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2071"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1752"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4127"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3711"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1001"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3979"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4543"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__986"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__472"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4443"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2792"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4826"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3950"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__422"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4327"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3939"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__90"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__483"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1476"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1975"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__491"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4491"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__453"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1854"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2032"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2430"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3001"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1567"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4307"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3542"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4639"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1534"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2939"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1301"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2347"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2624"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3469"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2809"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2823"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2793"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2317"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__802"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1473"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2081"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1429"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1981"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1020"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1806"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2355"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3211"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1692"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3768"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3034"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3040"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3274"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4388"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3103"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1260"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2635"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4417"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3444"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__173"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1906"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1079"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2049"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3770"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__683"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__921"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1380"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3146"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2710"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4832"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4762"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3010"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1458"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2260"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1297"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2571"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1143"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3570"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__105"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3488"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4164"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4678"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1044"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__182"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1804"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2700"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4694"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__903"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1938"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1702"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2582"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3674"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3782"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4283"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3013"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__224"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1430"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1357"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3612"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1617"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3154"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4308"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__477"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4681"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3411"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__568"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1652"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1848"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__435"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1447"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__261"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4135"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3360"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2455"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2444"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1045"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3917"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3790"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2223"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2278"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4476"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4533"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4733"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3902"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__275"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__755"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2787"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__580"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__625"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4747"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4654"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3865"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4760"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__843"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4504"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2478"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3355"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2894"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3481"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__590"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1536"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3120"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4244"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1046"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1775"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2120"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3135"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1172"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2022"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1067"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2714"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3339"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1002"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1936"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2638"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__367"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3696"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4688"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2790"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1437"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__7"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4478"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4758"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1529"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3756"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4218"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3309"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1135"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1479"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1943"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2001"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__513"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__452"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3670"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1541"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2257"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4080"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1133"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3627"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1720"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2590"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3965"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4631"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4679"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__863"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__440"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1056"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__556"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__42"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__928"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__761"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3381"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__731"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1395"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3157"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2246"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3284"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3709"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4174"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__930"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4322"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2297"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4644"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4823"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3353"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__197"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4071"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4743"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__555"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__425"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__451"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1255"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4723"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4328"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2513"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__887"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1313"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4139"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__637"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2648"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3420"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1247"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1707"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3260"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4204"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1230"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1150"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__828"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4317"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3129"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__361"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3475"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3745"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4658"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3635"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__820"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1003"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1332"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2443"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4438"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__615"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__110"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3781"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3380"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2900"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__900"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2136"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4315"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__941"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2252"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__39"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2401"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__507"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3493"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__600"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1064"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4332"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__215"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1129"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4673"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2452"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2656"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1071"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4422"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__712"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__734"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2757"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1564"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1009"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1703"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2094"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3535"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2312"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3793"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3904"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2461"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3926"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__962"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2172"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3368"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2187"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1847"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1307"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__645"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3499"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1329"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2169"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4619"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2261"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4449"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2959"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3091"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2722"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2491"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4750"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__174"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1093"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2563"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2580"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3527"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4594"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3911"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1265"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1986"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1559"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__593"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__927"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2208"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4337"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1826"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__811"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3960"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2772"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__66"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3559"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3775"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4144"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1417"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4238"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1096"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2035"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2190"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3288"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2313"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2768"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2616"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2746"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__704"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2112"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__388"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__661"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3216"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2546"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4249"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3426"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4648"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4128"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4264"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1736"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__71"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1377"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1801"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1786"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2791"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4017"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__34"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1457"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1293"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3929"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2537"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4050"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3762"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1531"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2780"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2066"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__308"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4288"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3716"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1109"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1084"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__967"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4395"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__6"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1331"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4600"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2855"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__499"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3518"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__488"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3142"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3090"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4509"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__432"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__881"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1999"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2744"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4500"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4701"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4405"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__932"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3348"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4190"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2923"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3650"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__698"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2847"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4032"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2929"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1972"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4060"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2895"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1818"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3946"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4541"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2495"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4339"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4527"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1560"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3715"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__646"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2540"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2943"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3462"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2030"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2850"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__319"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2225"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4096"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2661"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2413"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__8"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4129"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1164"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3575"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__225"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2429"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2519"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__283"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__814"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3191"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__804"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1290"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1191"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1362"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1711"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3340"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3343"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3742"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2175"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2210"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1442"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__623"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__189"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1820"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__303"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1528"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2291"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3468"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3773"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2812"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3842"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__918"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3445"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2826"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4668"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2057"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4125"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__88"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1601"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1687"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2884"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4540"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4612"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2209"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__457"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3269"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4063"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4825"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__674"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3840"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3982"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1021"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__45"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__146"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__194"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1591"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2311"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2684"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3590"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__259"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4113"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3125"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3162"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2275"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3969"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4376"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1033"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3531"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4331"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4707"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1252"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__201"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__306"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4294"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__106"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1980"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4366"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4627"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1774"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3721"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4497"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3666"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2529"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2899"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__668"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3520"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3967"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1400"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__770"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3851"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3794"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4099"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__958"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1893"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3227"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4456"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3161"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__707"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3548"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2466"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1114"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2724"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2446"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__783"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2068"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2985"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1038"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1350"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__243"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2979"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4008"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2105"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4145"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3880"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__445"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3072"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4808"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2213"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3953"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1725"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2488"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__466"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1095"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2277"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1190"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__613"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2983"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2484"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3140"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__974"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1186"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1789"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2195"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4549"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__546"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3047"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__168"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4576"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1310"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2878"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1279"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1522"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1926"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2817"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2547"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__355"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1053"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__389"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__989"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2738"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1837"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2964"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4058"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1072"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2382"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3134"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1055"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1625"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2026"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4511"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4573"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4617"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3011"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1392"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__232"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__991"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2132"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1766"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1146"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__934"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2041"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3942"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4051"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4461"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2976"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2980"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1101"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2415"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2704"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3593"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__175"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2897"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4304"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1042"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3786"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3636"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2660"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__742"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2680"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2789"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__509"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4531"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4763"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4774"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4092"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2730"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3787"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3792"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3487"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__574"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3592"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__59"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1558"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1744"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3860"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1374"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4819"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1802"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__664"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__630"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3277"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3645"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1628"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2592"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4799"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1125"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1091"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2084"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2782"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2489"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2224"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2736"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4786"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__696"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1650"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4670"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4372"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3112"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4434"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1922"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2233"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4041"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1178"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2118"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2926"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2609"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__711"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3206"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__844"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__390"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2691"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1174"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1667"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2692"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3234"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3725"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4636"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__322"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1604"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1733"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1660"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3322"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2365"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4695"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3059"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__344"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3759"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__517"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__860"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2106"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__401"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4018"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__284"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1346"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2989"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2243"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1795"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2303"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2702"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3747"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2189"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4254"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3581"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1570"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3659"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1209"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4233"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__347"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3326"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4463"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2995"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3621"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2748"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3208"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2570"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3927"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3558"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1957"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2807"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1925"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4241"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4364"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__467"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2585"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3358"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1089"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1577"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__532"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3425"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1618"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__147"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2605"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4022"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3562"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4623"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1010"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1050"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4522"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4202"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2676"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3127"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3370"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2166"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__279"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4703"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1341"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__214"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2715"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1461"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2493"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__563"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3643"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4306"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4706"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__870"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__883"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2589"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2756"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2970"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2559"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__779"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1243"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1592"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3440"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2179"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2971"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1303"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4822"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3213"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__426"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3361"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1391"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1846"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3242"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4035"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2851"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3708"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2613"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4746"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1370"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2389"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1868"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2602"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__103"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3540"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1065"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4053"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3813"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2158"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4160"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4680"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2289"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2778"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4485"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2325"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__290"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2211"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1294"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1312"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1771"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1791"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4538"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3823"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__486"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1997"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2407"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1787"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3833"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3973"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__65"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4578"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4821"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1783"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2028"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2909"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2178"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3107"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3573"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__234"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1768"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1966"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__415"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__227"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1157"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1511"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3921"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1308"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4121"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4079"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1487"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4704"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1881"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4342"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4817"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__91"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4633"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__101"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__111"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__121"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3466"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1571"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__662"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1211"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2829"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__479"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__643"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2238"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3024"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4498"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__25"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1576"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4383"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3717"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4622"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3919"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1903"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__539"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__47"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__956"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3783"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4110"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1909"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1359"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__482"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__978"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1106"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2490"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2862"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2114"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3222"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__38"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2038"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3970"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2284"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4038"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4087"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__14"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4292"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3767"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3811"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1543"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1394"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2097"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3549"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1151"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4815"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3205"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3492"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3619"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3500"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2458"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__850"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4637"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__251"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__769"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__979"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2707"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__575"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3779"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3886"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4699"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2331"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__330"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3825"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4309"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__133"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3974"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4717"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1696"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__790"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2072"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1236"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1754"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4833"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4176"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1173"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__892"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1594"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1695"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3044"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__854"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3734"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4271"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2202"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1203"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__992"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3002"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2990"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__586"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2786"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1823"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3609"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__383"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1927"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3571"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3849"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3461"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3173"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3907"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4682"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__245"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__691"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4226"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1595"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__680"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3989"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__969"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4151"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3124"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1785"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3137"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3744"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4261"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1619"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2286"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1843"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3519"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__145"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3836"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__372"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4262"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4603"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1632"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2271"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4569"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__786"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1165"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__353"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2981"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3194"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3868"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4300"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__897"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4228"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3883"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4607"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__694"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3228"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4367"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__944"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2356"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4112"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__605"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__810"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2818"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3017"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1514"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1130"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4321"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__282"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1238"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__592"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2745"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3993"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4493"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1743"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1545"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1873"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1321"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3534"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__43"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1516"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4046"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2052"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1123"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__846"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3000"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2794"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4800"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2988"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3416"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1769"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__107"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__102"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2383"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3700"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__266"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__792"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4119"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3877"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__504"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1465"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3379"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4102"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4657"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2342"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__795"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2690"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2866"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__469"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2917"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1872"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2298"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2963"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4236"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1207"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1882"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__687"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3414"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__849"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2149"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__300"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2290"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2577"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2614"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3509"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3321"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4660"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3051"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__86"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2620"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4072"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4137"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3249"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4416"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2021"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2285"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4530"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1602"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1767"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__92"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__427"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1535"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3392"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1630"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1167"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3524"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__923"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__267"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1949"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4108"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3463"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2085"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3539"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2760"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2940"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3765"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2617"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2399"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3806"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__248"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4103"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2584"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3637"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1436"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__409"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__186"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3841"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4373"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2147"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3992"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4076"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2709"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3826"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3555"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__109"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__878"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3796"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3941"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2014"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__77"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2227"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1568"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1432"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3323"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2435"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4698"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2394"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3544"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1507"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3141"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4186"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2294"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__706"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3617"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1706"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3691"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2270"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3713"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4343"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3955"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3007"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1149"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1316"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4286"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4348"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1212"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4114"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2137"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2110"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3003"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__85"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1256"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1724"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1892"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2879"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__654"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1298"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__733"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1484"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2770"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1185"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__41"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4535"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1546"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4105"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3067"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1074"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3037"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3845"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4677"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1790"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1859"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2354"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4165"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3574"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2131"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3436"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3822"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__649"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1113"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4544"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4672"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1950"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2360"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__455"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1745"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1985"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3316"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__852"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1118"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1634"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__474"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2697"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4192"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__118"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2465"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3676"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4742"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3801"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3785"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4625"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1068"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1047"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1462"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__375"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2788"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1087"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__206"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4737"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1327"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4382"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2827"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1758"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3055"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3761"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1828"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__676"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4428"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__99"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3282"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4184"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1887"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1073"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3968"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3132"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1007"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3018"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4547"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__813"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__337"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1731"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1662"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2374"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__153"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3223"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3882"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2868"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__670"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3196"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1676"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3114"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__688"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2061"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3584"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__497"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2328"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3166"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2364"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1069"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4588"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4055"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4468"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1738"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1643"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1425"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3846"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__157"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2339"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1035"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1088"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1959"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2754"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__196"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3895"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__703"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4684"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1347"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__392"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4446"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2006"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3576"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4276"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3735"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4444"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4560"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4712"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1896"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4169"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2080"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__379"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__481"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__657"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__732"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2348"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3229"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4420"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2056"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3164"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3755"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3854"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3870"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4326"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1850"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3887"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4836"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2266"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3212"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1367"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__387"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__178"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2875"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4792"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4360"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2716"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4752"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__371"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4598"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4447"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__53"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4375"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__242"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2712"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3809"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1145"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4520"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__907"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4029"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2377"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2856"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4666"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1673"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4117"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3041"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1110"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__916"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4655"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2565"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1779"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2795"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__465"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3345"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3554"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2005"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__17"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__431"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1153"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1584"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__724"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3378"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2557"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1581"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3079"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4630"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4487"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4010"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4740"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2142"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4237"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__622"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1723"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4379"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4831"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2168"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__151"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3319"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__977"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4043"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4781"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__914"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2668"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__993"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1920"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2450"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3232"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__530"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4235"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__672"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__272"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1103"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2905"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__492"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3094"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3175"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2593"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2067"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1679"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__410"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2469"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3279"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3480"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3692"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__364"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3820"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1944"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4250"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__841"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__781"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4397"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3532"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3728"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4094"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2688"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1825"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2815"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__407"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1379"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3899"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1748"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1930"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2767"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1322"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2122"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2763"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2096"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4024"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1989"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__152"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1026"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1495"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3108"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__885"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__476"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1463"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1499"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__778"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4384"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4403"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__23"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__19"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1822"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3894"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3898"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__635"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3152"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1216"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__996"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1325"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2523"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2627"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3283"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4406"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2728"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3903"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1849"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4528"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3702"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2713"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2462"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1152"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1305"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2743"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1274"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__759"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2159"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2040"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__412"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1573"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3043"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__808"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__73"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1012"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2683"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3113"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2375"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1373"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4374"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1834"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4741"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1014"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1358"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1387"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1578"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1318"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1701"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2380"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3244"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3399"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1991"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3155"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__983"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1218"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2012"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4319"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3078"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4205"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1566"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2608"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3262"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3537"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3722"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1270"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2044"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2434"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3506"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3743"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4393"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2199"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__148"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__602"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1090"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__205"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2027"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__315"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3489"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2045"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__130"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2880"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__302"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__204"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__13"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1231"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3286"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3591"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4124"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4182"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1641"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1585"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__76"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__162"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1952"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__544"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2023"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2128"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2421"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4209"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3936"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__136"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2869"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3437"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__44"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__144"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__926"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4453"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3505"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4052"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1283"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3184"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2139"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2222"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2873"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4414"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4502"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1244"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2039"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__165"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__239"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__943"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2653"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1177"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2138"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2796"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1154"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2667"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4691"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__875"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1063"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__209"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__718"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2597"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1525"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2626"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2706"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2888"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__771"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3218"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3251"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__730"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1228"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4830"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2581"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__54"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2973"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4611"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__442"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__648"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__735"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__519"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1171"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3310"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1249"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4689"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2637"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__620"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2059"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3295"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4064"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1653"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3631"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4455"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4521"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__545"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__748"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2352"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3892"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4330"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1049"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1521"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__601"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1876"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3371"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__884"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4827"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4344"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3433"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4336"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3633"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3578"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3827"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__256"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4780"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4217"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4278"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__572"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1904"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3115"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3352"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3959"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__97"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1036"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4021"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2861"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2517"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1572"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3045"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2369"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2759"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4245"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3795"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__752"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4011"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__228"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__87"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2487"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3906"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2747"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4078"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2500"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1621"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__929"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1221"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3869"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4513"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2699"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3472"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__939"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1649"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4194"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4652"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3494"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1420"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1411"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4801"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3349"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__997"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4242"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2516"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4093"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1280"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4813"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__89"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2332"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2975"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__793"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1638"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3177"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4415"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__660"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3896"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4810"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__301"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1932"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3668"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2320"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4025"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2024"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4289"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__69"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__68"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1729"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3912"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1013"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4039"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4479"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4559"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__314"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3105"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4632"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__394"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3802"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3230"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2111"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1498"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__219"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__57"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__729"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__880"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1451"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__377"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2232"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3180"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3583"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3432"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1419"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3661"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1471"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1278"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__540"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1182"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3418"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3975"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4368"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4424"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1807"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2528"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3944"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__877"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1418"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1735"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__982"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2165"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4526"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2263"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__114"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__142"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1608"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3818"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3720"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__115"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__775"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2353"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3485"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2207"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2669"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1946"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3689"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1304"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4303"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3925"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__538"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4634"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1059"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2832"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2835"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1004"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2086"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1438"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4371"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2689"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2457"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2998"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__865"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3258"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2664"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4361"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2666"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3202"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2927"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2956"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1508"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3622"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__709"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3128"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__839"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3769"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2808"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3421"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1241"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__223"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1664"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4086"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1995"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3273"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3923"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3653"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4240"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2622"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2552"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2987"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4407"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3046"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2578"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1670"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1248"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2742"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__176"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2805"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4840"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1134"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3586"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__161"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2876"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3387"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3901"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__384"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2308"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1788"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2508"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3460"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2267"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2412"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2543"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2326"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4111"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4365"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4783"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2016"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__434"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2931"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4829"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1094"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2968"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3320"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1497"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__351"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2398"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3049"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3964"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4811"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4586"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4435"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__500"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2628"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3678"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1651"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__777"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__723"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3077"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4083"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4295"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4115"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2245"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4484"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2761"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1477"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3798"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1058"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3568"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2161"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3530"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3086"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4122"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__187"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2914"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2505"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4150"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__269"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2025"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2954"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4316"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3116"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2681"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3136"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4568"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3580"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3948"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4777"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__776"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3278"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3600"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1383"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1606"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1781"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3083"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4427"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__791"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1674"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2037"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4486"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4662"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2640"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__80"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1761"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1356"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4172"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1282"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1385"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__826"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2134"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__922"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__163"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1314"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2083"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3587"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4000"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4458"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1636"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3197"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4561"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__385"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__537"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__858"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1245"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1348"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3719"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4369"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4389"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__830"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3810"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1557"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1750"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2333"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3915"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4208"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1923"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1678"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4353"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__404"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4410"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3198"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__871"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3664"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2643"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3068"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2201"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__96"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__420"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2198"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1340"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3253"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1319"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__864"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__558"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4620"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2501"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3377"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__798"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3749"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4769"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__373"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__378"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2191"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3080"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4404"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__117"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3333"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4347"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2727"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__845"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3005"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4606"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2441"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1235"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1875"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3776"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2916"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3300"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4333"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__135"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4532"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__940"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1483"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__328"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__603"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3683"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__24"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2655"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1402"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2153"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1996"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3816"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4180"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4464"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4550"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4314"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4690"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2587"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3640"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1352"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1399"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3148"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3988"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4614"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4650"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3158"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4757"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__677"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__244"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__912"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2436"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2755"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__747"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__307"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2779"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3186"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4034"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1757"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3217"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1142"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4767"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4574"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1335"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3009"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4473"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2530"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__963"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1845"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2367"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3030"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3252"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3482"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__599"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4732"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__526"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1956"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4835"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__494"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1683"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1066"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2226"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2282"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3008"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3404"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4440"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4667"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__423"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4789"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1961"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2221"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2934"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1869"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1237"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1181"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4179"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3431"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1338"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2319"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1193"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2634"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4232"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__191"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3873"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3369"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1376"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1661"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__954"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2418"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2889"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3566"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1947"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4104"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2576"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1132"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1954"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__896"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2063"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__505"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2496"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1611"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3491"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3344"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2898"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4175"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__311"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1206"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2560"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3861"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1337"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4282"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4768"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__217"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__177"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1870"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2708"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__171"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3626"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3757"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3905"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__159"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3997"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4399"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1565"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2548"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1967"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__754"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1439"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1633"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3998"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__258"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__531"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2977"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4557"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2361"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__233"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__837"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__976"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2932"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4191"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1509"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1530"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3778"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4489"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1671"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3174"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4807"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__699"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__84"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4788"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__495"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3311"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4516"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4231"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3423"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__216"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2287"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2633"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4552"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3649"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3098"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3909"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1284"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1742"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3201"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3270"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4070"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4465"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4152"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__200"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__202"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1039"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1281"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2663"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4045"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4100"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4469"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__760"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__959"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3507"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__763"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__235"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1931"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__20"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2693"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3314"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2251"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__948"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3788"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2247"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4824"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2206"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2741"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__534"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1360"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1077"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2925"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2999"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1778"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3610"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2773"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3815"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2610"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4352"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__738"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2078"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__920"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2946"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__739"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2839"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2863"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2506"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3714"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__55"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2373"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3889"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2309"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1942"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1924"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4466"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2058"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__548"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__700"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2295"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3101"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__527"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__180"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__32"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__299"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2686"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2539"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2387"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__346"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3285"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3665"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__972"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2751"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1532"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1005"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__715"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1654"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2558"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1344"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__525"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__794"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3245"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__263"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3732"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3777"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4016"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3390"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1199"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3625"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4536"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4345"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__218"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2350"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2538"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3799"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1600"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4065"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1764"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1988"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2047"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__461"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4653"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1689"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__169"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__617"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__938"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__336"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1658"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1194"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__621"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1269"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1691"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1884"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__799"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3424"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3150"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1969"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2750"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3470"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3601"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2102"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3662"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3985"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3454"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__125"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4009"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1894"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2996"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__155"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__663"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4059"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4605"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1384"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2362"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__305"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1032"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1693"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2675"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__882"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2503"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3858"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4604"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2432"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1054"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4001"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__946"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__343"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4585"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__349"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__363"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4027"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__552"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1104"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2143"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1784"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1642"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2431"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3207"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3839"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1126"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2527"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1227"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4697"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__797"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3396"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2509"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3819"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3126"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3624"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3741"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4646"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__408"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2887"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__376"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2253"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3240"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4710"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3318"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1897"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4181"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2481"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3585"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2978"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2892"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__56"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4592"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__528"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__241"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3362"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2372"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4411"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2055"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4146"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2133"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2185"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1613"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__278"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1620"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1798"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1184"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__270"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1315"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1805"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3365"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3943"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4077"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1276"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2470"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3638"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3706"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4837"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__430"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__448"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1210"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2410"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1112"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2774"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3062"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__195"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3805"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3855"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2229"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1994"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2819"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2867"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__644"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3791"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4014"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3893"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4188"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4398"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4584"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3219"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4377"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2411"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4173"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3753"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3987"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4370"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3615"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4354"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2145"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4797"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__584"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__139"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1000"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1250"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__990"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1709"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2566"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1824"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__184"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3606"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3097"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4713"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1306"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3119"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2445"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2082"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3966"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3652"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2646"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4265"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1777"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1240"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2844"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3618"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2953"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__702"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3564"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__60"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3215"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__859"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1354"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4494"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__417"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__629"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__803"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1586"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4033"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4467"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2370"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2472"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3623"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4555"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3185"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__721"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__463"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__570"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1018"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__872"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2906"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3679"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__521"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3607"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3824"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2231"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4178"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__817"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1299"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2531"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__609"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3398"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4126"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4744"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3616"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3830"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1455"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1386"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1891"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4229"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4258"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1460"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1202"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3515"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3852"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2300"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2735"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3220"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__94"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__751"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2140"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3306"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__848"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2334"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__678"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__876"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1139"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1537"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1540"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2930"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2991"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3496"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4349"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__619"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4068"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__72"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3934"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__126"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1921"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4006"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2060"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4649"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2785"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2554"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2186"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1213"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__697"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4570"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4645"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4839"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2075"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2764"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3151"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__211"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1361"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2176"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1466"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3541"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__473"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__835"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4664"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__547"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4766"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__847"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2391"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4501"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3483"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1710"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4638"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2518"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1085"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__12"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3237"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__957"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3916"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1444"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2220"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3605"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4683"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__566"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__297"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1317"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__937"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__359"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3832"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4571"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4720"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3407"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4269"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2752"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2051"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4430"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4142"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__576"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4216"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__633"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__853"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1510"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3835"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1838"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4507"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1371"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3075"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2130"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2204"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1665"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4674"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3203"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1907"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3403"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2629"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__116"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4579"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2921"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__212"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2426"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3536"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4259"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1865"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4496"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2379"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2406"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3065"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__318"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1334"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3498"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__360"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1596"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3522"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2018"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2935"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2305"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__294"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1615"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1741"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2881"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4013"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3545"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3604"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4409"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1582"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__429"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1685"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4523"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__444"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1161"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2125"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1877"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2405"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3386"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3804"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3020"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4358"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2596"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1574"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3434"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2918"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2729"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1919"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1272"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__560"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2659"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__825"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2599"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3376"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2337"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3900"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__743"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__320"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1433"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4106"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__737"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2244"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3478"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2623"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4628"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4727"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3400"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__108"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__27"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1450"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__490"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1603"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2034"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2296"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4402"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__951"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4551"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4004"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4564"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1753"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1890"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2960"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1512"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4609"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4663"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2438"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2765"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1131"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__229"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2344"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4828"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1445"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__312"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2336"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__768"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3490"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2273"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__329"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3335"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3828"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4285"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4518"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1452"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1224"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__208"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1599"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1037"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1170"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2896"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4085"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__543"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__772"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3525"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4661"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4773"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__869"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__893"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1254"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1501"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1624"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1714"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1839"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2327"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3074"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3254"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3405"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1138"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3495"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4168"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1289"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__805"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3307"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1830"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4615"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4761"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__226"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__400"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3848"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__968"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1214"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__857"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3628"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4525"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4755"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1382"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3681"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2473"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2870"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4199"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4656"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2725"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1493"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2322"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1078"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2162"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3789"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4705"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2228"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2658"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4616"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__573"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1413"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1187"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2674"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4196"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3123"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2974"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__632"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4221"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1746"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2562"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2073"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__443"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4273"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2188"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__9"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2583"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__744"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1043"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__559"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1814"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4460"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4651"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2781"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__598"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4669"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3632"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2907"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2050"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4248"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4515"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1494"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__276"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1176"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2936"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__188"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__624"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1686"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__406"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__203"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3956"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3812"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4200"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2237"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2416"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3567"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4753"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3025"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4562"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1366"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1813"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3726"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4787"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3473"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__190"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__129"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1253"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1862"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2103"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4380"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1363"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__669"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4197"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__501"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1793"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3687"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2877"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1428"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3317"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4483"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4642"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1883"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3419"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3516"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4302"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1647"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__304"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3579"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2265"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2753"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3913"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1874"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__522"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4581"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__317"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3641"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2811"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2891"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1285"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4107"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1645"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3521"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4028"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2696"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1008"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1041"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3053"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2007"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1614"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2511"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__458"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__535"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3642"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4224"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__591"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1871"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__10"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2193"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__61"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3188"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__524"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2612"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2551"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3458"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3933"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1542"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__95"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__247"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__671"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__722"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4595"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2329"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4779"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__362"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1575"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1263"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2019"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2662"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1204"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__140"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1198"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4234"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4355"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3553"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__815"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1677"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2011"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3890"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3634"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2841"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__277"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1533"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2777"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__78"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1905"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__834"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1489"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__454"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1519"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1680"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4838"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4429"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4015"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__741"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__595"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1583"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3517"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4423"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2200"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__981"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__287"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1880"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2235"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1855"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4003"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3012"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3958"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__213"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2428"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1031"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1895"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__285"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2561"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2798"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2986"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__441"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__569"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2315"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2542"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3385"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3597"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3455"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3264"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__695"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1448"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3938"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__356"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2948"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2573"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3467"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__984"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__192"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__31"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2852"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3145"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__567"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1401"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3035"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4297"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3930"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3729"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__138"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4735"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2254"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__756"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2536"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2711"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2645"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2003"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__639"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__348"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1412"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__416"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1747"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4413"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4647"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2346"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__714"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2065"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__254"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__365"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__784"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4593"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1342"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4074"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__63"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2476"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4437"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2908"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1609"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3060"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2156"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4225"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__970"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__506"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__104"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4155"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1659"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2842"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3563"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1914"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4506"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1737"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2167"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2385"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1409"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1953"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2010"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__502"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2636"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3304"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1295"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3514"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1799"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2345"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3867"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1082"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2064"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3704"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4149"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__181"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3452"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__788"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3598"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3577"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__325"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1140"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__536"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3412"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__583"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__980"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1040"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__238"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__529"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1951"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__67"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2567"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2644"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1076"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2672"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__960"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__995"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4546"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1550"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2119"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1827"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2803"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1015"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3354"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4385"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1998"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4148"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__773"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__154"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2241"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4335"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__950"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1622"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1223"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4490"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__249"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__26"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3057"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__296"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1523"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3159"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3807"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__16"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3214"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4291"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4734"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1526"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__112"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2093"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1468"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2256"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1286"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2837"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4301"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4745"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__288"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3297"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4770"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2937"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1588"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__985"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1539"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1183"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1259"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__149"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2533"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4514"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__925"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2555"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3341"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__292"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3210"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2234"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1390"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1794"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2657"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4012"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3438"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3949"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1902"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4313"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__550"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2775"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2440"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3085"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3746"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1681"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3843"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2575"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2423"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2845"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1669"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3844"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4280"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4305"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4793"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__37"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__553"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1292"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3663"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3864"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4556"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__405"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1717"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1548"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1773"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3878"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1562"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2000"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__350"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1414"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4116"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__332"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3667"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4776"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2009"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1760"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__998"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2486"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4357"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3450"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__901"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1629"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1612"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__295"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__919"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1225"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__665"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__816"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3451"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4147"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4583"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__749"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__745"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__785"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3006"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__128"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__2330"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3442"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1261"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3914"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1155"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3693"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__1857"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__3538"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4290"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__4692"
ScalesDocketTable ||--|o ScalesDocketEntry : "rdf__708"

```


## Classes

| Class | Description |
| --- | --- |
| [Any](classes/Any.md) | None |
| [ScalesAgent](classes/ScalesAgent.md) | TODO -- tell the world what this class (type) describes. |
| [ScalesCaseCivil](classes/ScalesCaseCivil.md) | TODO -- tell the world what this class (type) describes. |
| [ScalesCaseCriminal](classes/ScalesCaseCriminal.md) | TODO -- tell the world what this class (type) describes. |
| [ScalesCharge](classes/ScalesCharge.md) | TODO -- tell the world what this class (type) describes. |
| [ScalesCourt](classes/ScalesCourt.md) | TODO -- tell the world what this class (type) describes. |
| [ScalesDocketEntry](classes/ScalesDocketEntry.md) | TODO -- tell the world what this class (type) describes. |
| [ScalesDocketTable](classes/ScalesDocketTable.md) | TODO -- tell the world what this class (type) describes. |



## Slots

| Slot | Description |
| --- | --- |
| [rdf__0](slots/rdf__0.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1](slots/rdf__1.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__10](slots/rdf__10.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__100](slots/rdf__100.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1000](slots/rdf__1000.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1001](slots/rdf__1001.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1002](slots/rdf__1002.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1003](slots/rdf__1003.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1004](slots/rdf__1004.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1005](slots/rdf__1005.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1006](slots/rdf__1006.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1007](slots/rdf__1007.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1008](slots/rdf__1008.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1009](slots/rdf__1009.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__101](slots/rdf__101.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1010](slots/rdf__1010.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1011](slots/rdf__1011.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1012](slots/rdf__1012.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1013](slots/rdf__1013.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1014](slots/rdf__1014.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1015](slots/rdf__1015.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1016](slots/rdf__1016.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1017](slots/rdf__1017.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1018](slots/rdf__1018.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1019](slots/rdf__1019.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__102](slots/rdf__102.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1020](slots/rdf__1020.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1021](slots/rdf__1021.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1022](slots/rdf__1022.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1023](slots/rdf__1023.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1024](slots/rdf__1024.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1025](slots/rdf__1025.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1026](slots/rdf__1026.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1027](slots/rdf__1027.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1028](slots/rdf__1028.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1029](slots/rdf__1029.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__103](slots/rdf__103.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1030](slots/rdf__1030.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1031](slots/rdf__1031.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1032](slots/rdf__1032.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1033](slots/rdf__1033.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1034](slots/rdf__1034.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1035](slots/rdf__1035.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1036](slots/rdf__1036.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1037](slots/rdf__1037.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1038](slots/rdf__1038.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1039](slots/rdf__1039.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__104](slots/rdf__104.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1040](slots/rdf__1040.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1041](slots/rdf__1041.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1042](slots/rdf__1042.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1043](slots/rdf__1043.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1044](slots/rdf__1044.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1045](slots/rdf__1045.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1046](slots/rdf__1046.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1047](slots/rdf__1047.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1048](slots/rdf__1048.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1049](slots/rdf__1049.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__105](slots/rdf__105.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1050](slots/rdf__1050.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1051](slots/rdf__1051.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1052](slots/rdf__1052.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1053](slots/rdf__1053.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1054](slots/rdf__1054.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1055](slots/rdf__1055.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1056](slots/rdf__1056.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1057](slots/rdf__1057.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1058](slots/rdf__1058.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1059](slots/rdf__1059.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__106](slots/rdf__106.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1060](slots/rdf__1060.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1061](slots/rdf__1061.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1062](slots/rdf__1062.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1063](slots/rdf__1063.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1064](slots/rdf__1064.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1065](slots/rdf__1065.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1066](slots/rdf__1066.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1067](slots/rdf__1067.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1068](slots/rdf__1068.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1069](slots/rdf__1069.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__107](slots/rdf__107.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1070](slots/rdf__1070.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1071](slots/rdf__1071.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1072](slots/rdf__1072.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1073](slots/rdf__1073.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1074](slots/rdf__1074.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1075](slots/rdf__1075.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1076](slots/rdf__1076.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1077](slots/rdf__1077.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1078](slots/rdf__1078.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1079](slots/rdf__1079.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__108](slots/rdf__108.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1080](slots/rdf__1080.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1081](slots/rdf__1081.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1082](slots/rdf__1082.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1083](slots/rdf__1083.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1084](slots/rdf__1084.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1085](slots/rdf__1085.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1086](slots/rdf__1086.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1087](slots/rdf__1087.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1088](slots/rdf__1088.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1089](slots/rdf__1089.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__109](slots/rdf__109.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1090](slots/rdf__1090.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1091](slots/rdf__1091.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1092](slots/rdf__1092.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1093](slots/rdf__1093.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1094](slots/rdf__1094.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1095](slots/rdf__1095.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1096](slots/rdf__1096.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1097](slots/rdf__1097.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1098](slots/rdf__1098.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1099](slots/rdf__1099.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__11](slots/rdf__11.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__110](slots/rdf__110.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1100](slots/rdf__1100.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1101](slots/rdf__1101.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1102](slots/rdf__1102.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1103](slots/rdf__1103.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1104](slots/rdf__1104.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1105](slots/rdf__1105.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1106](slots/rdf__1106.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1107](slots/rdf__1107.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1108](slots/rdf__1108.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1109](slots/rdf__1109.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__111](slots/rdf__111.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1110](slots/rdf__1110.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1111](slots/rdf__1111.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1112](slots/rdf__1112.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1113](slots/rdf__1113.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1114](slots/rdf__1114.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1115](slots/rdf__1115.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1116](slots/rdf__1116.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1117](slots/rdf__1117.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1118](slots/rdf__1118.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1119](slots/rdf__1119.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__112](slots/rdf__112.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1120](slots/rdf__1120.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1121](slots/rdf__1121.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1122](slots/rdf__1122.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1123](slots/rdf__1123.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1124](slots/rdf__1124.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1125](slots/rdf__1125.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1126](slots/rdf__1126.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1127](slots/rdf__1127.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1128](slots/rdf__1128.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1129](slots/rdf__1129.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__113](slots/rdf__113.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1130](slots/rdf__1130.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1131](slots/rdf__1131.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1132](slots/rdf__1132.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1133](slots/rdf__1133.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1134](slots/rdf__1134.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1135](slots/rdf__1135.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1136](slots/rdf__1136.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1137](slots/rdf__1137.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1138](slots/rdf__1138.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1139](slots/rdf__1139.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__114](slots/rdf__114.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1140](slots/rdf__1140.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1141](slots/rdf__1141.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1142](slots/rdf__1142.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1143](slots/rdf__1143.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1144](slots/rdf__1144.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1145](slots/rdf__1145.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1146](slots/rdf__1146.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1147](slots/rdf__1147.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1148](slots/rdf__1148.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1149](slots/rdf__1149.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__115](slots/rdf__115.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1150](slots/rdf__1150.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1151](slots/rdf__1151.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1152](slots/rdf__1152.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1153](slots/rdf__1153.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1154](slots/rdf__1154.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1155](slots/rdf__1155.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1156](slots/rdf__1156.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1157](slots/rdf__1157.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1158](slots/rdf__1158.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1159](slots/rdf__1159.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__116](slots/rdf__116.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1160](slots/rdf__1160.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1161](slots/rdf__1161.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1162](slots/rdf__1162.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1163](slots/rdf__1163.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1164](slots/rdf__1164.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1165](slots/rdf__1165.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1166](slots/rdf__1166.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1167](slots/rdf__1167.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1168](slots/rdf__1168.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1169](slots/rdf__1169.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__117](slots/rdf__117.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1170](slots/rdf__1170.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1171](slots/rdf__1171.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1172](slots/rdf__1172.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1173](slots/rdf__1173.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1174](slots/rdf__1174.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1175](slots/rdf__1175.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1176](slots/rdf__1176.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1177](slots/rdf__1177.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1178](slots/rdf__1178.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1179](slots/rdf__1179.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__118](slots/rdf__118.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1180](slots/rdf__1180.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1181](slots/rdf__1181.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1182](slots/rdf__1182.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1183](slots/rdf__1183.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1184](slots/rdf__1184.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1185](slots/rdf__1185.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1186](slots/rdf__1186.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1187](slots/rdf__1187.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1188](slots/rdf__1188.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1189](slots/rdf__1189.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__119](slots/rdf__119.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1190](slots/rdf__1190.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1191](slots/rdf__1191.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1192](slots/rdf__1192.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1193](slots/rdf__1193.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1194](slots/rdf__1194.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1195](slots/rdf__1195.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1196](slots/rdf__1196.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1197](slots/rdf__1197.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1198](slots/rdf__1198.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1199](slots/rdf__1199.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__12](slots/rdf__12.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__120](slots/rdf__120.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1200](slots/rdf__1200.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1201](slots/rdf__1201.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1202](slots/rdf__1202.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1203](slots/rdf__1203.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1204](slots/rdf__1204.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1205](slots/rdf__1205.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1206](slots/rdf__1206.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1207](slots/rdf__1207.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1208](slots/rdf__1208.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1209](slots/rdf__1209.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__121](slots/rdf__121.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1210](slots/rdf__1210.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1211](slots/rdf__1211.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1212](slots/rdf__1212.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1213](slots/rdf__1213.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1214](slots/rdf__1214.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1215](slots/rdf__1215.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1216](slots/rdf__1216.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1217](slots/rdf__1217.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1218](slots/rdf__1218.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1219](slots/rdf__1219.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__122](slots/rdf__122.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1220](slots/rdf__1220.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1221](slots/rdf__1221.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1222](slots/rdf__1222.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1223](slots/rdf__1223.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1224](slots/rdf__1224.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1225](slots/rdf__1225.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1226](slots/rdf__1226.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1227](slots/rdf__1227.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1228](slots/rdf__1228.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1229](slots/rdf__1229.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__123](slots/rdf__123.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1230](slots/rdf__1230.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1231](slots/rdf__1231.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1232](slots/rdf__1232.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1233](slots/rdf__1233.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1234](slots/rdf__1234.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1235](slots/rdf__1235.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1236](slots/rdf__1236.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1237](slots/rdf__1237.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1238](slots/rdf__1238.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1239](slots/rdf__1239.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__124](slots/rdf__124.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1240](slots/rdf__1240.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1241](slots/rdf__1241.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1242](slots/rdf__1242.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1243](slots/rdf__1243.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1244](slots/rdf__1244.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1245](slots/rdf__1245.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1246](slots/rdf__1246.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1247](slots/rdf__1247.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1248](slots/rdf__1248.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1249](slots/rdf__1249.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__125](slots/rdf__125.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1250](slots/rdf__1250.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1251](slots/rdf__1251.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1252](slots/rdf__1252.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1253](slots/rdf__1253.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1254](slots/rdf__1254.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1255](slots/rdf__1255.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1256](slots/rdf__1256.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1257](slots/rdf__1257.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1258](slots/rdf__1258.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1259](slots/rdf__1259.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__126](slots/rdf__126.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1260](slots/rdf__1260.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1261](slots/rdf__1261.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1262](slots/rdf__1262.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1263](slots/rdf__1263.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1264](slots/rdf__1264.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1265](slots/rdf__1265.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1266](slots/rdf__1266.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1267](slots/rdf__1267.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1268](slots/rdf__1268.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1269](slots/rdf__1269.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__127](slots/rdf__127.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1270](slots/rdf__1270.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1271](slots/rdf__1271.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1272](slots/rdf__1272.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1273](slots/rdf__1273.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1274](slots/rdf__1274.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1275](slots/rdf__1275.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1276](slots/rdf__1276.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1277](slots/rdf__1277.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1278](slots/rdf__1278.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1279](slots/rdf__1279.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__128](slots/rdf__128.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1280](slots/rdf__1280.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1281](slots/rdf__1281.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1282](slots/rdf__1282.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1283](slots/rdf__1283.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1284](slots/rdf__1284.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1285](slots/rdf__1285.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1286](slots/rdf__1286.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1287](slots/rdf__1287.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1288](slots/rdf__1288.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1289](slots/rdf__1289.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__129](slots/rdf__129.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1290](slots/rdf__1290.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1291](slots/rdf__1291.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1292](slots/rdf__1292.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1293](slots/rdf__1293.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1294](slots/rdf__1294.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1295](slots/rdf__1295.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1296](slots/rdf__1296.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1297](slots/rdf__1297.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1298](slots/rdf__1298.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1299](slots/rdf__1299.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__13](slots/rdf__13.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__130](slots/rdf__130.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1300](slots/rdf__1300.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1301](slots/rdf__1301.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1302](slots/rdf__1302.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1303](slots/rdf__1303.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1304](slots/rdf__1304.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1305](slots/rdf__1305.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1306](slots/rdf__1306.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1307](slots/rdf__1307.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1308](slots/rdf__1308.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1309](slots/rdf__1309.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__131](slots/rdf__131.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1310](slots/rdf__1310.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1311](slots/rdf__1311.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1312](slots/rdf__1312.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1313](slots/rdf__1313.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1314](slots/rdf__1314.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1315](slots/rdf__1315.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1316](slots/rdf__1316.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1317](slots/rdf__1317.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1318](slots/rdf__1318.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1319](slots/rdf__1319.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__132](slots/rdf__132.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1320](slots/rdf__1320.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1321](slots/rdf__1321.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1322](slots/rdf__1322.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1323](slots/rdf__1323.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1324](slots/rdf__1324.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1325](slots/rdf__1325.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1326](slots/rdf__1326.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1327](slots/rdf__1327.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1328](slots/rdf__1328.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1329](slots/rdf__1329.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__133](slots/rdf__133.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1330](slots/rdf__1330.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1331](slots/rdf__1331.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1332](slots/rdf__1332.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1333](slots/rdf__1333.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1334](slots/rdf__1334.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1335](slots/rdf__1335.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1336](slots/rdf__1336.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1337](slots/rdf__1337.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1338](slots/rdf__1338.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1339](slots/rdf__1339.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__134](slots/rdf__134.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1340](slots/rdf__1340.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1341](slots/rdf__1341.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1342](slots/rdf__1342.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1343](slots/rdf__1343.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1344](slots/rdf__1344.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1345](slots/rdf__1345.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1346](slots/rdf__1346.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1347](slots/rdf__1347.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1348](slots/rdf__1348.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1349](slots/rdf__1349.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__135](slots/rdf__135.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1350](slots/rdf__1350.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1351](slots/rdf__1351.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1352](slots/rdf__1352.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1353](slots/rdf__1353.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1354](slots/rdf__1354.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1355](slots/rdf__1355.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1356](slots/rdf__1356.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1357](slots/rdf__1357.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1358](slots/rdf__1358.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1359](slots/rdf__1359.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__136](slots/rdf__136.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1360](slots/rdf__1360.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1361](slots/rdf__1361.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1362](slots/rdf__1362.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1363](slots/rdf__1363.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1364](slots/rdf__1364.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1365](slots/rdf__1365.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1366](slots/rdf__1366.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1367](slots/rdf__1367.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1368](slots/rdf__1368.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1369](slots/rdf__1369.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__137](slots/rdf__137.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1370](slots/rdf__1370.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1371](slots/rdf__1371.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1372](slots/rdf__1372.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1373](slots/rdf__1373.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1374](slots/rdf__1374.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1375](slots/rdf__1375.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1376](slots/rdf__1376.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1377](slots/rdf__1377.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1378](slots/rdf__1378.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1379](slots/rdf__1379.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__138](slots/rdf__138.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1380](slots/rdf__1380.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1381](slots/rdf__1381.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1382](slots/rdf__1382.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1383](slots/rdf__1383.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1384](slots/rdf__1384.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1385](slots/rdf__1385.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1386](slots/rdf__1386.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1387](slots/rdf__1387.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1388](slots/rdf__1388.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1389](slots/rdf__1389.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__139](slots/rdf__139.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1390](slots/rdf__1390.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1391](slots/rdf__1391.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1392](slots/rdf__1392.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1393](slots/rdf__1393.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1394](slots/rdf__1394.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1395](slots/rdf__1395.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1396](slots/rdf__1396.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1397](slots/rdf__1397.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1398](slots/rdf__1398.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1399](slots/rdf__1399.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__14](slots/rdf__14.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__140](slots/rdf__140.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1400](slots/rdf__1400.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1401](slots/rdf__1401.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1402](slots/rdf__1402.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1403](slots/rdf__1403.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1404](slots/rdf__1404.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1405](slots/rdf__1405.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1406](slots/rdf__1406.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1407](slots/rdf__1407.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1408](slots/rdf__1408.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1409](slots/rdf__1409.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__141](slots/rdf__141.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1410](slots/rdf__1410.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1411](slots/rdf__1411.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1412](slots/rdf__1412.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1413](slots/rdf__1413.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1414](slots/rdf__1414.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1415](slots/rdf__1415.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1416](slots/rdf__1416.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1417](slots/rdf__1417.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1418](slots/rdf__1418.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1419](slots/rdf__1419.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__142](slots/rdf__142.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1420](slots/rdf__1420.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1421](slots/rdf__1421.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1422](slots/rdf__1422.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1423](slots/rdf__1423.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1424](slots/rdf__1424.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1425](slots/rdf__1425.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1426](slots/rdf__1426.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1427](slots/rdf__1427.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1428](slots/rdf__1428.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1429](slots/rdf__1429.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__143](slots/rdf__143.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1430](slots/rdf__1430.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1431](slots/rdf__1431.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1432](slots/rdf__1432.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1433](slots/rdf__1433.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1434](slots/rdf__1434.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1435](slots/rdf__1435.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1436](slots/rdf__1436.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1437](slots/rdf__1437.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1438](slots/rdf__1438.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1439](slots/rdf__1439.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__144](slots/rdf__144.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1440](slots/rdf__1440.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1441](slots/rdf__1441.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1442](slots/rdf__1442.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1443](slots/rdf__1443.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1444](slots/rdf__1444.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1445](slots/rdf__1445.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1446](slots/rdf__1446.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1447](slots/rdf__1447.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1448](slots/rdf__1448.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1449](slots/rdf__1449.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__145](slots/rdf__145.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1450](slots/rdf__1450.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1451](slots/rdf__1451.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1452](slots/rdf__1452.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1453](slots/rdf__1453.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1454](slots/rdf__1454.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1455](slots/rdf__1455.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1456](slots/rdf__1456.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1457](slots/rdf__1457.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1458](slots/rdf__1458.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1459](slots/rdf__1459.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__146](slots/rdf__146.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1460](slots/rdf__1460.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1461](slots/rdf__1461.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1462](slots/rdf__1462.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1463](slots/rdf__1463.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1464](slots/rdf__1464.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1465](slots/rdf__1465.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1466](slots/rdf__1466.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1467](slots/rdf__1467.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1468](slots/rdf__1468.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1469](slots/rdf__1469.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__147](slots/rdf__147.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1470](slots/rdf__1470.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1471](slots/rdf__1471.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1472](slots/rdf__1472.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1473](slots/rdf__1473.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1474](slots/rdf__1474.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1475](slots/rdf__1475.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1476](slots/rdf__1476.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1477](slots/rdf__1477.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1478](slots/rdf__1478.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1479](slots/rdf__1479.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__148](slots/rdf__148.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1480](slots/rdf__1480.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1481](slots/rdf__1481.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1482](slots/rdf__1482.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1483](slots/rdf__1483.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1484](slots/rdf__1484.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1485](slots/rdf__1485.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1486](slots/rdf__1486.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1487](slots/rdf__1487.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1488](slots/rdf__1488.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1489](slots/rdf__1489.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__149](slots/rdf__149.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1490](slots/rdf__1490.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1491](slots/rdf__1491.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1492](slots/rdf__1492.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1493](slots/rdf__1493.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1494](slots/rdf__1494.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1495](slots/rdf__1495.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1496](slots/rdf__1496.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1497](slots/rdf__1497.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1498](slots/rdf__1498.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1499](slots/rdf__1499.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__15](slots/rdf__15.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__150](slots/rdf__150.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1500](slots/rdf__1500.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1501](slots/rdf__1501.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1502](slots/rdf__1502.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1503](slots/rdf__1503.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1504](slots/rdf__1504.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1505](slots/rdf__1505.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1506](slots/rdf__1506.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1507](slots/rdf__1507.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1508](slots/rdf__1508.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1509](slots/rdf__1509.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__151](slots/rdf__151.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1510](slots/rdf__1510.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1511](slots/rdf__1511.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1512](slots/rdf__1512.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1513](slots/rdf__1513.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1514](slots/rdf__1514.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1515](slots/rdf__1515.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1516](slots/rdf__1516.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1517](slots/rdf__1517.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1518](slots/rdf__1518.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1519](slots/rdf__1519.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__152](slots/rdf__152.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1520](slots/rdf__1520.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1521](slots/rdf__1521.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1522](slots/rdf__1522.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1523](slots/rdf__1523.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1524](slots/rdf__1524.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1525](slots/rdf__1525.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1526](slots/rdf__1526.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1527](slots/rdf__1527.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1528](slots/rdf__1528.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1529](slots/rdf__1529.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__153](slots/rdf__153.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1530](slots/rdf__1530.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1531](slots/rdf__1531.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1532](slots/rdf__1532.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1533](slots/rdf__1533.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1534](slots/rdf__1534.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1535](slots/rdf__1535.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1536](slots/rdf__1536.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1537](slots/rdf__1537.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1538](slots/rdf__1538.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1539](slots/rdf__1539.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__154](slots/rdf__154.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1540](slots/rdf__1540.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1541](slots/rdf__1541.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1542](slots/rdf__1542.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1543](slots/rdf__1543.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1544](slots/rdf__1544.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1545](slots/rdf__1545.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1546](slots/rdf__1546.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1547](slots/rdf__1547.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1548](slots/rdf__1548.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1549](slots/rdf__1549.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__155](slots/rdf__155.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1550](slots/rdf__1550.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1551](slots/rdf__1551.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1552](slots/rdf__1552.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1553](slots/rdf__1553.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1554](slots/rdf__1554.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1555](slots/rdf__1555.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1556](slots/rdf__1556.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1557](slots/rdf__1557.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1558](slots/rdf__1558.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1559](slots/rdf__1559.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__156](slots/rdf__156.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1560](slots/rdf__1560.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1561](slots/rdf__1561.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1562](slots/rdf__1562.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1563](slots/rdf__1563.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1564](slots/rdf__1564.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1565](slots/rdf__1565.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1566](slots/rdf__1566.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1567](slots/rdf__1567.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1568](slots/rdf__1568.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1569](slots/rdf__1569.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__157](slots/rdf__157.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1570](slots/rdf__1570.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1571](slots/rdf__1571.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1572](slots/rdf__1572.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1573](slots/rdf__1573.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1574](slots/rdf__1574.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1575](slots/rdf__1575.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1576](slots/rdf__1576.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1577](slots/rdf__1577.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1578](slots/rdf__1578.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1579](slots/rdf__1579.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__158](slots/rdf__158.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1580](slots/rdf__1580.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1581](slots/rdf__1581.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1582](slots/rdf__1582.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1583](slots/rdf__1583.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1584](slots/rdf__1584.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1585](slots/rdf__1585.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1586](slots/rdf__1586.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1587](slots/rdf__1587.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1588](slots/rdf__1588.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1589](slots/rdf__1589.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__159](slots/rdf__159.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1590](slots/rdf__1590.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1591](slots/rdf__1591.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1592](slots/rdf__1592.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1593](slots/rdf__1593.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1594](slots/rdf__1594.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1595](slots/rdf__1595.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1596](slots/rdf__1596.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1597](slots/rdf__1597.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1598](slots/rdf__1598.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1599](slots/rdf__1599.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__16](slots/rdf__16.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__160](slots/rdf__160.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1600](slots/rdf__1600.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1601](slots/rdf__1601.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1602](slots/rdf__1602.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1603](slots/rdf__1603.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1604](slots/rdf__1604.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1605](slots/rdf__1605.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1606](slots/rdf__1606.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1607](slots/rdf__1607.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1608](slots/rdf__1608.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1609](slots/rdf__1609.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__161](slots/rdf__161.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1610](slots/rdf__1610.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1611](slots/rdf__1611.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1612](slots/rdf__1612.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1613](slots/rdf__1613.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1614](slots/rdf__1614.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1615](slots/rdf__1615.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1616](slots/rdf__1616.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1617](slots/rdf__1617.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1618](slots/rdf__1618.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1619](slots/rdf__1619.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__162](slots/rdf__162.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1620](slots/rdf__1620.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1621](slots/rdf__1621.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1622](slots/rdf__1622.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1623](slots/rdf__1623.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1624](slots/rdf__1624.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1625](slots/rdf__1625.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1626](slots/rdf__1626.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1627](slots/rdf__1627.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1628](slots/rdf__1628.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1629](slots/rdf__1629.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__163](slots/rdf__163.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1630](slots/rdf__1630.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1631](slots/rdf__1631.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1632](slots/rdf__1632.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1633](slots/rdf__1633.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1634](slots/rdf__1634.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1635](slots/rdf__1635.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1636](slots/rdf__1636.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1637](slots/rdf__1637.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1638](slots/rdf__1638.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1639](slots/rdf__1639.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__164](slots/rdf__164.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1640](slots/rdf__1640.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1641](slots/rdf__1641.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1642](slots/rdf__1642.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1643](slots/rdf__1643.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1644](slots/rdf__1644.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1645](slots/rdf__1645.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1646](slots/rdf__1646.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1647](slots/rdf__1647.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1648](slots/rdf__1648.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1649](slots/rdf__1649.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__165](slots/rdf__165.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1650](slots/rdf__1650.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1651](slots/rdf__1651.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1652](slots/rdf__1652.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1653](slots/rdf__1653.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1654](slots/rdf__1654.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1655](slots/rdf__1655.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1656](slots/rdf__1656.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1657](slots/rdf__1657.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1658](slots/rdf__1658.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1659](slots/rdf__1659.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__166](slots/rdf__166.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1660](slots/rdf__1660.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1661](slots/rdf__1661.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1662](slots/rdf__1662.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1663](slots/rdf__1663.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1664](slots/rdf__1664.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1665](slots/rdf__1665.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1666](slots/rdf__1666.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1667](slots/rdf__1667.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1668](slots/rdf__1668.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1669](slots/rdf__1669.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__167](slots/rdf__167.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1670](slots/rdf__1670.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1671](slots/rdf__1671.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1672](slots/rdf__1672.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1673](slots/rdf__1673.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1674](slots/rdf__1674.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1675](slots/rdf__1675.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1676](slots/rdf__1676.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1677](slots/rdf__1677.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1678](slots/rdf__1678.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1679](slots/rdf__1679.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__168](slots/rdf__168.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1680](slots/rdf__1680.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1681](slots/rdf__1681.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1682](slots/rdf__1682.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1683](slots/rdf__1683.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1684](slots/rdf__1684.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1685](slots/rdf__1685.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1686](slots/rdf__1686.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1687](slots/rdf__1687.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1688](slots/rdf__1688.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1689](slots/rdf__1689.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__169](slots/rdf__169.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1690](slots/rdf__1690.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1691](slots/rdf__1691.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1692](slots/rdf__1692.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1693](slots/rdf__1693.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1694](slots/rdf__1694.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1695](slots/rdf__1695.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1696](slots/rdf__1696.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1697](slots/rdf__1697.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1698](slots/rdf__1698.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1699](slots/rdf__1699.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__17](slots/rdf__17.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__170](slots/rdf__170.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1700](slots/rdf__1700.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1701](slots/rdf__1701.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1702](slots/rdf__1702.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1703](slots/rdf__1703.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1704](slots/rdf__1704.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1705](slots/rdf__1705.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1706](slots/rdf__1706.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1707](slots/rdf__1707.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1708](slots/rdf__1708.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1709](slots/rdf__1709.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__171](slots/rdf__171.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1710](slots/rdf__1710.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1711](slots/rdf__1711.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1712](slots/rdf__1712.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1713](slots/rdf__1713.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1714](slots/rdf__1714.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1715](slots/rdf__1715.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1716](slots/rdf__1716.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1717](slots/rdf__1717.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1718](slots/rdf__1718.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1719](slots/rdf__1719.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__172](slots/rdf__172.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1720](slots/rdf__1720.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1721](slots/rdf__1721.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1722](slots/rdf__1722.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1723](slots/rdf__1723.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1724](slots/rdf__1724.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1725](slots/rdf__1725.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1726](slots/rdf__1726.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1727](slots/rdf__1727.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1728](slots/rdf__1728.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1729](slots/rdf__1729.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__173](slots/rdf__173.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1730](slots/rdf__1730.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1731](slots/rdf__1731.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1732](slots/rdf__1732.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1733](slots/rdf__1733.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1734](slots/rdf__1734.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1735](slots/rdf__1735.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1736](slots/rdf__1736.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1737](slots/rdf__1737.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1738](slots/rdf__1738.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1739](slots/rdf__1739.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__174](slots/rdf__174.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1740](slots/rdf__1740.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1741](slots/rdf__1741.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1742](slots/rdf__1742.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1743](slots/rdf__1743.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1744](slots/rdf__1744.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1745](slots/rdf__1745.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1746](slots/rdf__1746.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1747](slots/rdf__1747.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1748](slots/rdf__1748.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1749](slots/rdf__1749.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__175](slots/rdf__175.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1750](slots/rdf__1750.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1751](slots/rdf__1751.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1752](slots/rdf__1752.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1753](slots/rdf__1753.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1754](slots/rdf__1754.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1755](slots/rdf__1755.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1756](slots/rdf__1756.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1757](slots/rdf__1757.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1758](slots/rdf__1758.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1759](slots/rdf__1759.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__176](slots/rdf__176.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1760](slots/rdf__1760.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1761](slots/rdf__1761.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1762](slots/rdf__1762.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1763](slots/rdf__1763.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1764](slots/rdf__1764.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1765](slots/rdf__1765.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1766](slots/rdf__1766.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1767](slots/rdf__1767.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1768](slots/rdf__1768.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1769](slots/rdf__1769.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__177](slots/rdf__177.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1770](slots/rdf__1770.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1771](slots/rdf__1771.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1772](slots/rdf__1772.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1773](slots/rdf__1773.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1774](slots/rdf__1774.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1775](slots/rdf__1775.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1776](slots/rdf__1776.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1777](slots/rdf__1777.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1778](slots/rdf__1778.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1779](slots/rdf__1779.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__178](slots/rdf__178.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1780](slots/rdf__1780.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1781](slots/rdf__1781.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1782](slots/rdf__1782.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1783](slots/rdf__1783.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1784](slots/rdf__1784.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1785](slots/rdf__1785.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1786](slots/rdf__1786.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1787](slots/rdf__1787.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1788](slots/rdf__1788.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1789](slots/rdf__1789.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__179](slots/rdf__179.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1790](slots/rdf__1790.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1791](slots/rdf__1791.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1792](slots/rdf__1792.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1793](slots/rdf__1793.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1794](slots/rdf__1794.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1795](slots/rdf__1795.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1796](slots/rdf__1796.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1797](slots/rdf__1797.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1798](slots/rdf__1798.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1799](slots/rdf__1799.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__18](slots/rdf__18.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__180](slots/rdf__180.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1800](slots/rdf__1800.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1801](slots/rdf__1801.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1802](slots/rdf__1802.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1803](slots/rdf__1803.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1804](slots/rdf__1804.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1805](slots/rdf__1805.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1806](slots/rdf__1806.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1807](slots/rdf__1807.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1808](slots/rdf__1808.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1809](slots/rdf__1809.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__181](slots/rdf__181.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1810](slots/rdf__1810.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1811](slots/rdf__1811.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1812](slots/rdf__1812.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1813](slots/rdf__1813.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1814](slots/rdf__1814.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1815](slots/rdf__1815.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1816](slots/rdf__1816.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1817](slots/rdf__1817.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1818](slots/rdf__1818.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1819](slots/rdf__1819.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__182](slots/rdf__182.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1820](slots/rdf__1820.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1821](slots/rdf__1821.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1822](slots/rdf__1822.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1823](slots/rdf__1823.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1824](slots/rdf__1824.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1825](slots/rdf__1825.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1826](slots/rdf__1826.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1827](slots/rdf__1827.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1828](slots/rdf__1828.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1829](slots/rdf__1829.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__183](slots/rdf__183.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1830](slots/rdf__1830.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1831](slots/rdf__1831.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1832](slots/rdf__1832.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1833](slots/rdf__1833.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1834](slots/rdf__1834.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1835](slots/rdf__1835.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1836](slots/rdf__1836.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1837](slots/rdf__1837.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1838](slots/rdf__1838.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1839](slots/rdf__1839.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__184](slots/rdf__184.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1840](slots/rdf__1840.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1841](slots/rdf__1841.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1842](slots/rdf__1842.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1843](slots/rdf__1843.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1844](slots/rdf__1844.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1845](slots/rdf__1845.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1846](slots/rdf__1846.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1847](slots/rdf__1847.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1848](slots/rdf__1848.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1849](slots/rdf__1849.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__185](slots/rdf__185.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1850](slots/rdf__1850.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1851](slots/rdf__1851.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1852](slots/rdf__1852.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1853](slots/rdf__1853.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1854](slots/rdf__1854.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1855](slots/rdf__1855.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1856](slots/rdf__1856.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1857](slots/rdf__1857.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1858](slots/rdf__1858.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1859](slots/rdf__1859.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__186](slots/rdf__186.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1860](slots/rdf__1860.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1861](slots/rdf__1861.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1862](slots/rdf__1862.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1863](slots/rdf__1863.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1864](slots/rdf__1864.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1865](slots/rdf__1865.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1866](slots/rdf__1866.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1867](slots/rdf__1867.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1868](slots/rdf__1868.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1869](slots/rdf__1869.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__187](slots/rdf__187.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1870](slots/rdf__1870.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1871](slots/rdf__1871.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1872](slots/rdf__1872.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1873](slots/rdf__1873.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1874](slots/rdf__1874.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1875](slots/rdf__1875.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1876](slots/rdf__1876.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1877](slots/rdf__1877.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1878](slots/rdf__1878.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1879](slots/rdf__1879.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__188](slots/rdf__188.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1880](slots/rdf__1880.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1881](slots/rdf__1881.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1882](slots/rdf__1882.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1883](slots/rdf__1883.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1884](slots/rdf__1884.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1885](slots/rdf__1885.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1886](slots/rdf__1886.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1887](slots/rdf__1887.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1888](slots/rdf__1888.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1889](slots/rdf__1889.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__189](slots/rdf__189.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1890](slots/rdf__1890.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1891](slots/rdf__1891.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1892](slots/rdf__1892.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1893](slots/rdf__1893.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1894](slots/rdf__1894.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1895](slots/rdf__1895.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1896](slots/rdf__1896.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1897](slots/rdf__1897.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1898](slots/rdf__1898.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1899](slots/rdf__1899.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__19](slots/rdf__19.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__190](slots/rdf__190.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1900](slots/rdf__1900.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1901](slots/rdf__1901.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1902](slots/rdf__1902.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1903](slots/rdf__1903.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1904](slots/rdf__1904.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1905](slots/rdf__1905.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1906](slots/rdf__1906.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1907](slots/rdf__1907.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1908](slots/rdf__1908.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1909](slots/rdf__1909.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__191](slots/rdf__191.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1910](slots/rdf__1910.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1911](slots/rdf__1911.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1912](slots/rdf__1912.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1913](slots/rdf__1913.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1914](slots/rdf__1914.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1915](slots/rdf__1915.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1916](slots/rdf__1916.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1917](slots/rdf__1917.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1918](slots/rdf__1918.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1919](slots/rdf__1919.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__192](slots/rdf__192.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1920](slots/rdf__1920.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1921](slots/rdf__1921.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1922](slots/rdf__1922.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1923](slots/rdf__1923.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1924](slots/rdf__1924.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1925](slots/rdf__1925.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1926](slots/rdf__1926.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1927](slots/rdf__1927.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1928](slots/rdf__1928.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1929](slots/rdf__1929.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__193](slots/rdf__193.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1930](slots/rdf__1930.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1931](slots/rdf__1931.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1932](slots/rdf__1932.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1933](slots/rdf__1933.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1934](slots/rdf__1934.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1935](slots/rdf__1935.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1936](slots/rdf__1936.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1937](slots/rdf__1937.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1938](slots/rdf__1938.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1939](slots/rdf__1939.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__194](slots/rdf__194.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1940](slots/rdf__1940.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1941](slots/rdf__1941.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1942](slots/rdf__1942.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1943](slots/rdf__1943.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1944](slots/rdf__1944.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1945](slots/rdf__1945.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1946](slots/rdf__1946.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1947](slots/rdf__1947.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1948](slots/rdf__1948.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1949](slots/rdf__1949.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__195](slots/rdf__195.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1950](slots/rdf__1950.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1951](slots/rdf__1951.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1952](slots/rdf__1952.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1953](slots/rdf__1953.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1954](slots/rdf__1954.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1955](slots/rdf__1955.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1956](slots/rdf__1956.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1957](slots/rdf__1957.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1958](slots/rdf__1958.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1959](slots/rdf__1959.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__196](slots/rdf__196.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1960](slots/rdf__1960.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1961](slots/rdf__1961.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1962](slots/rdf__1962.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1963](slots/rdf__1963.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1964](slots/rdf__1964.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1965](slots/rdf__1965.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1966](slots/rdf__1966.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1967](slots/rdf__1967.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1968](slots/rdf__1968.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1969](slots/rdf__1969.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__197](slots/rdf__197.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1970](slots/rdf__1970.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1971](slots/rdf__1971.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1972](slots/rdf__1972.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1973](slots/rdf__1973.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1974](slots/rdf__1974.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1975](slots/rdf__1975.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1976](slots/rdf__1976.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1977](slots/rdf__1977.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1978](slots/rdf__1978.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1979](slots/rdf__1979.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__198](slots/rdf__198.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1980](slots/rdf__1980.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1981](slots/rdf__1981.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1982](slots/rdf__1982.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1983](slots/rdf__1983.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1984](slots/rdf__1984.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1985](slots/rdf__1985.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1986](slots/rdf__1986.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1987](slots/rdf__1987.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1988](slots/rdf__1988.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1989](slots/rdf__1989.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__199](slots/rdf__199.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1990](slots/rdf__1990.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1991](slots/rdf__1991.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1992](slots/rdf__1992.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1993](slots/rdf__1993.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1994](slots/rdf__1994.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1995](slots/rdf__1995.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1996](slots/rdf__1996.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1997](slots/rdf__1997.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1998](slots/rdf__1998.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__1999](slots/rdf__1999.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2](slots/rdf__2.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__20](slots/rdf__20.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__200](slots/rdf__200.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2000](slots/rdf__2000.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2001](slots/rdf__2001.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2002](slots/rdf__2002.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2003](slots/rdf__2003.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2004](slots/rdf__2004.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2005](slots/rdf__2005.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2006](slots/rdf__2006.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2007](slots/rdf__2007.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2008](slots/rdf__2008.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2009](slots/rdf__2009.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__201](slots/rdf__201.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2010](slots/rdf__2010.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2011](slots/rdf__2011.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2012](slots/rdf__2012.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2013](slots/rdf__2013.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2014](slots/rdf__2014.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2015](slots/rdf__2015.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2016](slots/rdf__2016.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2017](slots/rdf__2017.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2018](slots/rdf__2018.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2019](slots/rdf__2019.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__202](slots/rdf__202.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2020](slots/rdf__2020.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2021](slots/rdf__2021.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2022](slots/rdf__2022.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2023](slots/rdf__2023.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2024](slots/rdf__2024.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2025](slots/rdf__2025.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2026](slots/rdf__2026.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2027](slots/rdf__2027.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2028](slots/rdf__2028.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2029](slots/rdf__2029.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__203](slots/rdf__203.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2030](slots/rdf__2030.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2031](slots/rdf__2031.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2032](slots/rdf__2032.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2033](slots/rdf__2033.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2034](slots/rdf__2034.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2035](slots/rdf__2035.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2036](slots/rdf__2036.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2037](slots/rdf__2037.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2038](slots/rdf__2038.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2039](slots/rdf__2039.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__204](slots/rdf__204.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2040](slots/rdf__2040.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2041](slots/rdf__2041.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2042](slots/rdf__2042.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2043](slots/rdf__2043.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2044](slots/rdf__2044.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2045](slots/rdf__2045.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2046](slots/rdf__2046.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2047](slots/rdf__2047.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2048](slots/rdf__2048.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2049](slots/rdf__2049.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__205](slots/rdf__205.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2050](slots/rdf__2050.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2051](slots/rdf__2051.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2052](slots/rdf__2052.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2053](slots/rdf__2053.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2054](slots/rdf__2054.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2055](slots/rdf__2055.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2056](slots/rdf__2056.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2057](slots/rdf__2057.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2058](slots/rdf__2058.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2059](slots/rdf__2059.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__206](slots/rdf__206.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2060](slots/rdf__2060.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2061](slots/rdf__2061.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2062](slots/rdf__2062.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2063](slots/rdf__2063.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2064](slots/rdf__2064.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2065](slots/rdf__2065.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2066](slots/rdf__2066.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2067](slots/rdf__2067.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2068](slots/rdf__2068.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2069](slots/rdf__2069.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__207](slots/rdf__207.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2070](slots/rdf__2070.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2071](slots/rdf__2071.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2072](slots/rdf__2072.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2073](slots/rdf__2073.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2074](slots/rdf__2074.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2075](slots/rdf__2075.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2076](slots/rdf__2076.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2077](slots/rdf__2077.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2078](slots/rdf__2078.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2079](slots/rdf__2079.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__208](slots/rdf__208.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2080](slots/rdf__2080.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2081](slots/rdf__2081.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2082](slots/rdf__2082.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2083](slots/rdf__2083.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2084](slots/rdf__2084.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2085](slots/rdf__2085.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2086](slots/rdf__2086.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2087](slots/rdf__2087.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2088](slots/rdf__2088.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2089](slots/rdf__2089.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__209](slots/rdf__209.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2090](slots/rdf__2090.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2091](slots/rdf__2091.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2092](slots/rdf__2092.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2093](slots/rdf__2093.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2094](slots/rdf__2094.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2095](slots/rdf__2095.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2096](slots/rdf__2096.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2097](slots/rdf__2097.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2098](slots/rdf__2098.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2099](slots/rdf__2099.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__21](slots/rdf__21.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__210](slots/rdf__210.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2100](slots/rdf__2100.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2101](slots/rdf__2101.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2102](slots/rdf__2102.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2103](slots/rdf__2103.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2104](slots/rdf__2104.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2105](slots/rdf__2105.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2106](slots/rdf__2106.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2107](slots/rdf__2107.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2108](slots/rdf__2108.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2109](slots/rdf__2109.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__211](slots/rdf__211.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2110](slots/rdf__2110.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2111](slots/rdf__2111.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2112](slots/rdf__2112.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2113](slots/rdf__2113.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2114](slots/rdf__2114.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2115](slots/rdf__2115.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2116](slots/rdf__2116.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2117](slots/rdf__2117.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2118](slots/rdf__2118.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2119](slots/rdf__2119.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__212](slots/rdf__212.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2120](slots/rdf__2120.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2121](slots/rdf__2121.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2122](slots/rdf__2122.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2123](slots/rdf__2123.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2124](slots/rdf__2124.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2125](slots/rdf__2125.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2126](slots/rdf__2126.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2127](slots/rdf__2127.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2128](slots/rdf__2128.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2129](slots/rdf__2129.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__213](slots/rdf__213.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2130](slots/rdf__2130.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2131](slots/rdf__2131.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2132](slots/rdf__2132.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2133](slots/rdf__2133.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2134](slots/rdf__2134.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2135](slots/rdf__2135.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2136](slots/rdf__2136.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2137](slots/rdf__2137.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2138](slots/rdf__2138.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2139](slots/rdf__2139.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__214](slots/rdf__214.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2140](slots/rdf__2140.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2141](slots/rdf__2141.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2142](slots/rdf__2142.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2143](slots/rdf__2143.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2144](slots/rdf__2144.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2145](slots/rdf__2145.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2146](slots/rdf__2146.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2147](slots/rdf__2147.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2148](slots/rdf__2148.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2149](slots/rdf__2149.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__215](slots/rdf__215.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2150](slots/rdf__2150.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2151](slots/rdf__2151.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2152](slots/rdf__2152.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2153](slots/rdf__2153.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2154](slots/rdf__2154.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2155](slots/rdf__2155.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2156](slots/rdf__2156.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2157](slots/rdf__2157.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2158](slots/rdf__2158.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2159](slots/rdf__2159.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__216](slots/rdf__216.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2160](slots/rdf__2160.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2161](slots/rdf__2161.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2162](slots/rdf__2162.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2163](slots/rdf__2163.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2164](slots/rdf__2164.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2165](slots/rdf__2165.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2166](slots/rdf__2166.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2167](slots/rdf__2167.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2168](slots/rdf__2168.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2169](slots/rdf__2169.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__217](slots/rdf__217.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2170](slots/rdf__2170.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2171](slots/rdf__2171.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2172](slots/rdf__2172.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2173](slots/rdf__2173.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2174](slots/rdf__2174.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2175](slots/rdf__2175.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2176](slots/rdf__2176.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2177](slots/rdf__2177.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2178](slots/rdf__2178.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2179](slots/rdf__2179.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__218](slots/rdf__218.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2180](slots/rdf__2180.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2181](slots/rdf__2181.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2182](slots/rdf__2182.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2183](slots/rdf__2183.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2184](slots/rdf__2184.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2185](slots/rdf__2185.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2186](slots/rdf__2186.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2187](slots/rdf__2187.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2188](slots/rdf__2188.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2189](slots/rdf__2189.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__219](slots/rdf__219.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2190](slots/rdf__2190.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2191](slots/rdf__2191.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2192](slots/rdf__2192.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2193](slots/rdf__2193.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2194](slots/rdf__2194.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2195](slots/rdf__2195.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2196](slots/rdf__2196.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2197](slots/rdf__2197.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2198](slots/rdf__2198.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2199](slots/rdf__2199.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__22](slots/rdf__22.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__220](slots/rdf__220.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2200](slots/rdf__2200.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2201](slots/rdf__2201.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2202](slots/rdf__2202.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2203](slots/rdf__2203.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2204](slots/rdf__2204.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2205](slots/rdf__2205.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2206](slots/rdf__2206.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2207](slots/rdf__2207.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2208](slots/rdf__2208.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2209](slots/rdf__2209.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__221](slots/rdf__221.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2210](slots/rdf__2210.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2211](slots/rdf__2211.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2212](slots/rdf__2212.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2213](slots/rdf__2213.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2214](slots/rdf__2214.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2215](slots/rdf__2215.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2216](slots/rdf__2216.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2217](slots/rdf__2217.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2218](slots/rdf__2218.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2219](slots/rdf__2219.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__222](slots/rdf__222.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2220](slots/rdf__2220.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2221](slots/rdf__2221.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2222](slots/rdf__2222.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2223](slots/rdf__2223.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2224](slots/rdf__2224.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2225](slots/rdf__2225.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2226](slots/rdf__2226.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2227](slots/rdf__2227.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2228](slots/rdf__2228.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2229](slots/rdf__2229.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__223](slots/rdf__223.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2230](slots/rdf__2230.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2231](slots/rdf__2231.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2232](slots/rdf__2232.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2233](slots/rdf__2233.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2234](slots/rdf__2234.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2235](slots/rdf__2235.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2236](slots/rdf__2236.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2237](slots/rdf__2237.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2238](slots/rdf__2238.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2239](slots/rdf__2239.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__224](slots/rdf__224.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2240](slots/rdf__2240.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2241](slots/rdf__2241.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2242](slots/rdf__2242.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2243](slots/rdf__2243.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2244](slots/rdf__2244.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2245](slots/rdf__2245.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2246](slots/rdf__2246.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2247](slots/rdf__2247.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2248](slots/rdf__2248.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2249](slots/rdf__2249.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__225](slots/rdf__225.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2250](slots/rdf__2250.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2251](slots/rdf__2251.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2252](slots/rdf__2252.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2253](slots/rdf__2253.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2254](slots/rdf__2254.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2255](slots/rdf__2255.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2256](slots/rdf__2256.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2257](slots/rdf__2257.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2258](slots/rdf__2258.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2259](slots/rdf__2259.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__226](slots/rdf__226.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2260](slots/rdf__2260.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2261](slots/rdf__2261.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2262](slots/rdf__2262.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2263](slots/rdf__2263.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2264](slots/rdf__2264.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2265](slots/rdf__2265.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2266](slots/rdf__2266.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2267](slots/rdf__2267.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2268](slots/rdf__2268.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2269](slots/rdf__2269.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__227](slots/rdf__227.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2270](slots/rdf__2270.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2271](slots/rdf__2271.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2272](slots/rdf__2272.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2273](slots/rdf__2273.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2274](slots/rdf__2274.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2275](slots/rdf__2275.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2276](slots/rdf__2276.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2277](slots/rdf__2277.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2278](slots/rdf__2278.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2279](slots/rdf__2279.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__228](slots/rdf__228.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2280](slots/rdf__2280.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2281](slots/rdf__2281.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2282](slots/rdf__2282.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2283](slots/rdf__2283.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2284](slots/rdf__2284.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2285](slots/rdf__2285.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2286](slots/rdf__2286.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2287](slots/rdf__2287.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2288](slots/rdf__2288.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2289](slots/rdf__2289.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__229](slots/rdf__229.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2290](slots/rdf__2290.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2291](slots/rdf__2291.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2292](slots/rdf__2292.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2293](slots/rdf__2293.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2294](slots/rdf__2294.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2295](slots/rdf__2295.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2296](slots/rdf__2296.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2297](slots/rdf__2297.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2298](slots/rdf__2298.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2299](slots/rdf__2299.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__23](slots/rdf__23.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__230](slots/rdf__230.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2300](slots/rdf__2300.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2301](slots/rdf__2301.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2302](slots/rdf__2302.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2303](slots/rdf__2303.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2304](slots/rdf__2304.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2305](slots/rdf__2305.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2306](slots/rdf__2306.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2307](slots/rdf__2307.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2308](slots/rdf__2308.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2309](slots/rdf__2309.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__231](slots/rdf__231.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2310](slots/rdf__2310.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2311](slots/rdf__2311.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2312](slots/rdf__2312.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2313](slots/rdf__2313.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2314](slots/rdf__2314.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2315](slots/rdf__2315.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2316](slots/rdf__2316.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2317](slots/rdf__2317.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2318](slots/rdf__2318.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2319](slots/rdf__2319.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__232](slots/rdf__232.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2320](slots/rdf__2320.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2321](slots/rdf__2321.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2322](slots/rdf__2322.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2323](slots/rdf__2323.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2324](slots/rdf__2324.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2325](slots/rdf__2325.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2326](slots/rdf__2326.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2327](slots/rdf__2327.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2328](slots/rdf__2328.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2329](slots/rdf__2329.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__233](slots/rdf__233.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2330](slots/rdf__2330.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2331](slots/rdf__2331.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2332](slots/rdf__2332.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2333](slots/rdf__2333.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2334](slots/rdf__2334.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2335](slots/rdf__2335.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2336](slots/rdf__2336.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2337](slots/rdf__2337.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2338](slots/rdf__2338.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2339](slots/rdf__2339.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__234](slots/rdf__234.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2340](slots/rdf__2340.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2341](slots/rdf__2341.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2342](slots/rdf__2342.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2343](slots/rdf__2343.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2344](slots/rdf__2344.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2345](slots/rdf__2345.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2346](slots/rdf__2346.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2347](slots/rdf__2347.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2348](slots/rdf__2348.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2349](slots/rdf__2349.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__235](slots/rdf__235.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2350](slots/rdf__2350.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2351](slots/rdf__2351.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2352](slots/rdf__2352.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2353](slots/rdf__2353.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2354](slots/rdf__2354.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2355](slots/rdf__2355.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2356](slots/rdf__2356.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2357](slots/rdf__2357.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2358](slots/rdf__2358.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2359](slots/rdf__2359.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__236](slots/rdf__236.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2360](slots/rdf__2360.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2361](slots/rdf__2361.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2362](slots/rdf__2362.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2363](slots/rdf__2363.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2364](slots/rdf__2364.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2365](slots/rdf__2365.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2366](slots/rdf__2366.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2367](slots/rdf__2367.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2368](slots/rdf__2368.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2369](slots/rdf__2369.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__237](slots/rdf__237.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2370](slots/rdf__2370.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2371](slots/rdf__2371.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2372](slots/rdf__2372.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2373](slots/rdf__2373.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2374](slots/rdf__2374.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2375](slots/rdf__2375.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2376](slots/rdf__2376.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2377](slots/rdf__2377.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2378](slots/rdf__2378.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2379](slots/rdf__2379.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__238](slots/rdf__238.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2380](slots/rdf__2380.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2381](slots/rdf__2381.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2382](slots/rdf__2382.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2383](slots/rdf__2383.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2384](slots/rdf__2384.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2385](slots/rdf__2385.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2386](slots/rdf__2386.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2387](slots/rdf__2387.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2388](slots/rdf__2388.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2389](slots/rdf__2389.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__239](slots/rdf__239.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2390](slots/rdf__2390.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2391](slots/rdf__2391.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2392](slots/rdf__2392.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2393](slots/rdf__2393.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2394](slots/rdf__2394.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2395](slots/rdf__2395.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2396](slots/rdf__2396.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2397](slots/rdf__2397.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2398](slots/rdf__2398.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2399](slots/rdf__2399.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__24](slots/rdf__24.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__240](slots/rdf__240.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2400](slots/rdf__2400.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2401](slots/rdf__2401.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2402](slots/rdf__2402.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2403](slots/rdf__2403.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2404](slots/rdf__2404.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2405](slots/rdf__2405.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2406](slots/rdf__2406.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2407](slots/rdf__2407.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2408](slots/rdf__2408.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2409](slots/rdf__2409.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__241](slots/rdf__241.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2410](slots/rdf__2410.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2411](slots/rdf__2411.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2412](slots/rdf__2412.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2413](slots/rdf__2413.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2414](slots/rdf__2414.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2415](slots/rdf__2415.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2416](slots/rdf__2416.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2417](slots/rdf__2417.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2418](slots/rdf__2418.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2419](slots/rdf__2419.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__242](slots/rdf__242.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2420](slots/rdf__2420.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2421](slots/rdf__2421.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2422](slots/rdf__2422.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2423](slots/rdf__2423.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2424](slots/rdf__2424.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2425](slots/rdf__2425.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2426](slots/rdf__2426.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2427](slots/rdf__2427.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2428](slots/rdf__2428.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2429](slots/rdf__2429.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__243](slots/rdf__243.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2430](slots/rdf__2430.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2431](slots/rdf__2431.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2432](slots/rdf__2432.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2433](slots/rdf__2433.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2434](slots/rdf__2434.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2435](slots/rdf__2435.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2436](slots/rdf__2436.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2437](slots/rdf__2437.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2438](slots/rdf__2438.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2439](slots/rdf__2439.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__244](slots/rdf__244.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2440](slots/rdf__2440.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2441](slots/rdf__2441.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2442](slots/rdf__2442.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2443](slots/rdf__2443.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2444](slots/rdf__2444.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2445](slots/rdf__2445.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2446](slots/rdf__2446.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2447](slots/rdf__2447.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2448](slots/rdf__2448.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2449](slots/rdf__2449.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__245](slots/rdf__245.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2450](slots/rdf__2450.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2451](slots/rdf__2451.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2452](slots/rdf__2452.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2453](slots/rdf__2453.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2454](slots/rdf__2454.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2455](slots/rdf__2455.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2456](slots/rdf__2456.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2457](slots/rdf__2457.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2458](slots/rdf__2458.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2459](slots/rdf__2459.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__246](slots/rdf__246.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2460](slots/rdf__2460.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2461](slots/rdf__2461.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2462](slots/rdf__2462.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2463](slots/rdf__2463.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2464](slots/rdf__2464.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2465](slots/rdf__2465.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2466](slots/rdf__2466.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2467](slots/rdf__2467.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2468](slots/rdf__2468.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2469](slots/rdf__2469.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__247](slots/rdf__247.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2470](slots/rdf__2470.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2471](slots/rdf__2471.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2472](slots/rdf__2472.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2473](slots/rdf__2473.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2474](slots/rdf__2474.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2475](slots/rdf__2475.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2476](slots/rdf__2476.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2477](slots/rdf__2477.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2478](slots/rdf__2478.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2479](slots/rdf__2479.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__248](slots/rdf__248.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2480](slots/rdf__2480.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2481](slots/rdf__2481.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2482](slots/rdf__2482.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2483](slots/rdf__2483.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2484](slots/rdf__2484.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2485](slots/rdf__2485.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2486](slots/rdf__2486.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2487](slots/rdf__2487.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2488](slots/rdf__2488.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2489](slots/rdf__2489.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__249](slots/rdf__249.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2490](slots/rdf__2490.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2491](slots/rdf__2491.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2492](slots/rdf__2492.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2493](slots/rdf__2493.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2494](slots/rdf__2494.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2495](slots/rdf__2495.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2496](slots/rdf__2496.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2497](slots/rdf__2497.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2498](slots/rdf__2498.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2499](slots/rdf__2499.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__25](slots/rdf__25.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__250](slots/rdf__250.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2500](slots/rdf__2500.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2501](slots/rdf__2501.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2502](slots/rdf__2502.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2503](slots/rdf__2503.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2504](slots/rdf__2504.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2505](slots/rdf__2505.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2506](slots/rdf__2506.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2507](slots/rdf__2507.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2508](slots/rdf__2508.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2509](slots/rdf__2509.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__251](slots/rdf__251.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2510](slots/rdf__2510.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2511](slots/rdf__2511.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2512](slots/rdf__2512.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2513](slots/rdf__2513.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2514](slots/rdf__2514.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2515](slots/rdf__2515.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2516](slots/rdf__2516.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2517](slots/rdf__2517.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2518](slots/rdf__2518.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2519](slots/rdf__2519.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__252](slots/rdf__252.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2520](slots/rdf__2520.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2521](slots/rdf__2521.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2522](slots/rdf__2522.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2523](slots/rdf__2523.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2524](slots/rdf__2524.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2525](slots/rdf__2525.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2526](slots/rdf__2526.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2527](slots/rdf__2527.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2528](slots/rdf__2528.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2529](slots/rdf__2529.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__253](slots/rdf__253.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2530](slots/rdf__2530.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2531](slots/rdf__2531.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2532](slots/rdf__2532.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2533](slots/rdf__2533.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2534](slots/rdf__2534.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2535](slots/rdf__2535.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2536](slots/rdf__2536.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2537](slots/rdf__2537.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2538](slots/rdf__2538.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2539](slots/rdf__2539.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__254](slots/rdf__254.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2540](slots/rdf__2540.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2541](slots/rdf__2541.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2542](slots/rdf__2542.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2543](slots/rdf__2543.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2544](slots/rdf__2544.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2545](slots/rdf__2545.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2546](slots/rdf__2546.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2547](slots/rdf__2547.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2548](slots/rdf__2548.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2549](slots/rdf__2549.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__255](slots/rdf__255.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2550](slots/rdf__2550.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2551](slots/rdf__2551.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2552](slots/rdf__2552.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2553](slots/rdf__2553.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2554](slots/rdf__2554.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2555](slots/rdf__2555.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2556](slots/rdf__2556.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2557](slots/rdf__2557.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2558](slots/rdf__2558.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2559](slots/rdf__2559.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__256](slots/rdf__256.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2560](slots/rdf__2560.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2561](slots/rdf__2561.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2562](slots/rdf__2562.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2563](slots/rdf__2563.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2564](slots/rdf__2564.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2565](slots/rdf__2565.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2566](slots/rdf__2566.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2567](slots/rdf__2567.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2568](slots/rdf__2568.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2569](slots/rdf__2569.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__257](slots/rdf__257.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2570](slots/rdf__2570.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2571](slots/rdf__2571.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2572](slots/rdf__2572.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2573](slots/rdf__2573.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2574](slots/rdf__2574.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2575](slots/rdf__2575.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2576](slots/rdf__2576.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2577](slots/rdf__2577.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2578](slots/rdf__2578.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2579](slots/rdf__2579.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__258](slots/rdf__258.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2580](slots/rdf__2580.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2581](slots/rdf__2581.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2582](slots/rdf__2582.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2583](slots/rdf__2583.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2584](slots/rdf__2584.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2585](slots/rdf__2585.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2586](slots/rdf__2586.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2587](slots/rdf__2587.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2588](slots/rdf__2588.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2589](slots/rdf__2589.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__259](slots/rdf__259.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2590](slots/rdf__2590.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2591](slots/rdf__2591.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2592](slots/rdf__2592.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2593](slots/rdf__2593.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2594](slots/rdf__2594.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2595](slots/rdf__2595.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2596](slots/rdf__2596.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2597](slots/rdf__2597.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2598](slots/rdf__2598.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2599](slots/rdf__2599.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__26](slots/rdf__26.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__260](slots/rdf__260.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2600](slots/rdf__2600.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2601](slots/rdf__2601.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2602](slots/rdf__2602.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2603](slots/rdf__2603.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2604](slots/rdf__2604.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2605](slots/rdf__2605.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2606](slots/rdf__2606.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2607](slots/rdf__2607.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2608](slots/rdf__2608.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2609](slots/rdf__2609.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__261](slots/rdf__261.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2610](slots/rdf__2610.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2611](slots/rdf__2611.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2612](slots/rdf__2612.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2613](slots/rdf__2613.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2614](slots/rdf__2614.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2615](slots/rdf__2615.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2616](slots/rdf__2616.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2617](slots/rdf__2617.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2618](slots/rdf__2618.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2619](slots/rdf__2619.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__262](slots/rdf__262.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2620](slots/rdf__2620.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2621](slots/rdf__2621.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2622](slots/rdf__2622.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2623](slots/rdf__2623.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2624](slots/rdf__2624.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2625](slots/rdf__2625.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2626](slots/rdf__2626.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2627](slots/rdf__2627.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2628](slots/rdf__2628.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2629](slots/rdf__2629.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__263](slots/rdf__263.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2630](slots/rdf__2630.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2631](slots/rdf__2631.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2632](slots/rdf__2632.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2633](slots/rdf__2633.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2634](slots/rdf__2634.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2635](slots/rdf__2635.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2636](slots/rdf__2636.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2637](slots/rdf__2637.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2638](slots/rdf__2638.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2639](slots/rdf__2639.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__264](slots/rdf__264.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2640](slots/rdf__2640.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2641](slots/rdf__2641.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2642](slots/rdf__2642.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2643](slots/rdf__2643.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2644](slots/rdf__2644.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2645](slots/rdf__2645.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2646](slots/rdf__2646.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2647](slots/rdf__2647.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2648](slots/rdf__2648.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2649](slots/rdf__2649.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__265](slots/rdf__265.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2650](slots/rdf__2650.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2651](slots/rdf__2651.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2652](slots/rdf__2652.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2653](slots/rdf__2653.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2654](slots/rdf__2654.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2655](slots/rdf__2655.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2656](slots/rdf__2656.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2657](slots/rdf__2657.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2658](slots/rdf__2658.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2659](slots/rdf__2659.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__266](slots/rdf__266.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2660](slots/rdf__2660.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2661](slots/rdf__2661.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2662](slots/rdf__2662.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2663](slots/rdf__2663.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2664](slots/rdf__2664.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2665](slots/rdf__2665.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2666](slots/rdf__2666.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2667](slots/rdf__2667.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2668](slots/rdf__2668.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2669](slots/rdf__2669.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__267](slots/rdf__267.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2670](slots/rdf__2670.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2671](slots/rdf__2671.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2672](slots/rdf__2672.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2673](slots/rdf__2673.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2674](slots/rdf__2674.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2675](slots/rdf__2675.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2676](slots/rdf__2676.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2677](slots/rdf__2677.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2678](slots/rdf__2678.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2679](slots/rdf__2679.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__268](slots/rdf__268.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2680](slots/rdf__2680.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2681](slots/rdf__2681.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2682](slots/rdf__2682.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2683](slots/rdf__2683.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2684](slots/rdf__2684.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2685](slots/rdf__2685.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2686](slots/rdf__2686.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2687](slots/rdf__2687.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2688](slots/rdf__2688.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2689](slots/rdf__2689.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__269](slots/rdf__269.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2690](slots/rdf__2690.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2691](slots/rdf__2691.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2692](slots/rdf__2692.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2693](slots/rdf__2693.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2694](slots/rdf__2694.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2695](slots/rdf__2695.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2696](slots/rdf__2696.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2697](slots/rdf__2697.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2698](slots/rdf__2698.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2699](slots/rdf__2699.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__27](slots/rdf__27.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__270](slots/rdf__270.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2700](slots/rdf__2700.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2701](slots/rdf__2701.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2702](slots/rdf__2702.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2703](slots/rdf__2703.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2704](slots/rdf__2704.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2705](slots/rdf__2705.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2706](slots/rdf__2706.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2707](slots/rdf__2707.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2708](slots/rdf__2708.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2709](slots/rdf__2709.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__271](slots/rdf__271.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2710](slots/rdf__2710.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2711](slots/rdf__2711.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2712](slots/rdf__2712.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2713](slots/rdf__2713.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2714](slots/rdf__2714.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2715](slots/rdf__2715.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2716](slots/rdf__2716.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2717](slots/rdf__2717.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2718](slots/rdf__2718.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2719](slots/rdf__2719.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__272](slots/rdf__272.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2720](slots/rdf__2720.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2721](slots/rdf__2721.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2722](slots/rdf__2722.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2723](slots/rdf__2723.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2724](slots/rdf__2724.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2725](slots/rdf__2725.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2726](slots/rdf__2726.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2727](slots/rdf__2727.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2728](slots/rdf__2728.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2729](slots/rdf__2729.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__273](slots/rdf__273.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2730](slots/rdf__2730.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2731](slots/rdf__2731.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2732](slots/rdf__2732.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2733](slots/rdf__2733.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2734](slots/rdf__2734.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2735](slots/rdf__2735.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2736](slots/rdf__2736.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2737](slots/rdf__2737.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2738](slots/rdf__2738.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2739](slots/rdf__2739.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__274](slots/rdf__274.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2740](slots/rdf__2740.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2741](slots/rdf__2741.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2742](slots/rdf__2742.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2743](slots/rdf__2743.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2744](slots/rdf__2744.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2745](slots/rdf__2745.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2746](slots/rdf__2746.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2747](slots/rdf__2747.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2748](slots/rdf__2748.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2749](slots/rdf__2749.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__275](slots/rdf__275.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2750](slots/rdf__2750.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2751](slots/rdf__2751.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2752](slots/rdf__2752.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2753](slots/rdf__2753.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2754](slots/rdf__2754.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2755](slots/rdf__2755.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2756](slots/rdf__2756.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2757](slots/rdf__2757.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2758](slots/rdf__2758.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2759](slots/rdf__2759.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__276](slots/rdf__276.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2760](slots/rdf__2760.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2761](slots/rdf__2761.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2762](slots/rdf__2762.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2763](slots/rdf__2763.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2764](slots/rdf__2764.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2765](slots/rdf__2765.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2766](slots/rdf__2766.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2767](slots/rdf__2767.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2768](slots/rdf__2768.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2769](slots/rdf__2769.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__277](slots/rdf__277.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2770](slots/rdf__2770.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2771](slots/rdf__2771.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2772](slots/rdf__2772.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2773](slots/rdf__2773.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2774](slots/rdf__2774.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2775](slots/rdf__2775.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2776](slots/rdf__2776.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2777](slots/rdf__2777.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2778](slots/rdf__2778.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2779](slots/rdf__2779.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__278](slots/rdf__278.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2780](slots/rdf__2780.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2781](slots/rdf__2781.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2782](slots/rdf__2782.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2783](slots/rdf__2783.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2784](slots/rdf__2784.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2785](slots/rdf__2785.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2786](slots/rdf__2786.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2787](slots/rdf__2787.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2788](slots/rdf__2788.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2789](slots/rdf__2789.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__279](slots/rdf__279.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2790](slots/rdf__2790.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2791](slots/rdf__2791.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2792](slots/rdf__2792.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2793](slots/rdf__2793.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2794](slots/rdf__2794.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2795](slots/rdf__2795.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2796](slots/rdf__2796.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2797](slots/rdf__2797.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2798](slots/rdf__2798.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2799](slots/rdf__2799.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__28](slots/rdf__28.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__280](slots/rdf__280.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2800](slots/rdf__2800.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2801](slots/rdf__2801.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2802](slots/rdf__2802.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2803](slots/rdf__2803.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2804](slots/rdf__2804.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2805](slots/rdf__2805.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2806](slots/rdf__2806.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2807](slots/rdf__2807.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2808](slots/rdf__2808.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2809](slots/rdf__2809.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__281](slots/rdf__281.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2810](slots/rdf__2810.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2811](slots/rdf__2811.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2812](slots/rdf__2812.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2813](slots/rdf__2813.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2814](slots/rdf__2814.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2815](slots/rdf__2815.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2816](slots/rdf__2816.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2817](slots/rdf__2817.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2818](slots/rdf__2818.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2819](slots/rdf__2819.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__282](slots/rdf__282.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2820](slots/rdf__2820.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2821](slots/rdf__2821.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2822](slots/rdf__2822.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2823](slots/rdf__2823.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2824](slots/rdf__2824.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2825](slots/rdf__2825.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2826](slots/rdf__2826.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2827](slots/rdf__2827.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2828](slots/rdf__2828.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2829](slots/rdf__2829.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__283](slots/rdf__283.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2830](slots/rdf__2830.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2831](slots/rdf__2831.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2832](slots/rdf__2832.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2833](slots/rdf__2833.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2834](slots/rdf__2834.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2835](slots/rdf__2835.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2836](slots/rdf__2836.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2837](slots/rdf__2837.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2838](slots/rdf__2838.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2839](slots/rdf__2839.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__284](slots/rdf__284.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2840](slots/rdf__2840.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2841](slots/rdf__2841.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2842](slots/rdf__2842.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2843](slots/rdf__2843.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2844](slots/rdf__2844.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2845](slots/rdf__2845.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2846](slots/rdf__2846.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2847](slots/rdf__2847.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2848](slots/rdf__2848.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2849](slots/rdf__2849.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__285](slots/rdf__285.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2850](slots/rdf__2850.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2851](slots/rdf__2851.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2852](slots/rdf__2852.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2853](slots/rdf__2853.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2854](slots/rdf__2854.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2855](slots/rdf__2855.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2856](slots/rdf__2856.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2857](slots/rdf__2857.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2858](slots/rdf__2858.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2859](slots/rdf__2859.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__286](slots/rdf__286.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2860](slots/rdf__2860.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2861](slots/rdf__2861.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2862](slots/rdf__2862.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2863](slots/rdf__2863.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2864](slots/rdf__2864.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2865](slots/rdf__2865.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2866](slots/rdf__2866.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2867](slots/rdf__2867.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2868](slots/rdf__2868.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2869](slots/rdf__2869.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__287](slots/rdf__287.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2870](slots/rdf__2870.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2871](slots/rdf__2871.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2872](slots/rdf__2872.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2873](slots/rdf__2873.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2874](slots/rdf__2874.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2875](slots/rdf__2875.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2876](slots/rdf__2876.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2877](slots/rdf__2877.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2878](slots/rdf__2878.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2879](slots/rdf__2879.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__288](slots/rdf__288.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2880](slots/rdf__2880.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2881](slots/rdf__2881.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2882](slots/rdf__2882.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2883](slots/rdf__2883.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2884](slots/rdf__2884.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2885](slots/rdf__2885.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2886](slots/rdf__2886.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2887](slots/rdf__2887.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2888](slots/rdf__2888.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2889](slots/rdf__2889.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__289](slots/rdf__289.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2890](slots/rdf__2890.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2891](slots/rdf__2891.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2892](slots/rdf__2892.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2893](slots/rdf__2893.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2894](slots/rdf__2894.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2895](slots/rdf__2895.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2896](slots/rdf__2896.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2897](slots/rdf__2897.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2898](slots/rdf__2898.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2899](slots/rdf__2899.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__29](slots/rdf__29.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__290](slots/rdf__290.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2900](slots/rdf__2900.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2901](slots/rdf__2901.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2902](slots/rdf__2902.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2903](slots/rdf__2903.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2904](slots/rdf__2904.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2905](slots/rdf__2905.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2906](slots/rdf__2906.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2907](slots/rdf__2907.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2908](slots/rdf__2908.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2909](slots/rdf__2909.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__291](slots/rdf__291.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2910](slots/rdf__2910.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2911](slots/rdf__2911.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2912](slots/rdf__2912.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2913](slots/rdf__2913.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2914](slots/rdf__2914.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2915](slots/rdf__2915.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2916](slots/rdf__2916.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2917](slots/rdf__2917.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2918](slots/rdf__2918.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2919](slots/rdf__2919.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__292](slots/rdf__292.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2920](slots/rdf__2920.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2921](slots/rdf__2921.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2922](slots/rdf__2922.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2923](slots/rdf__2923.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2924](slots/rdf__2924.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2925](slots/rdf__2925.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2926](slots/rdf__2926.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2927](slots/rdf__2927.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2928](slots/rdf__2928.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2929](slots/rdf__2929.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__293](slots/rdf__293.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2930](slots/rdf__2930.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2931](slots/rdf__2931.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2932](slots/rdf__2932.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2933](slots/rdf__2933.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2934](slots/rdf__2934.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2935](slots/rdf__2935.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2936](slots/rdf__2936.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2937](slots/rdf__2937.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2938](slots/rdf__2938.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2939](slots/rdf__2939.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__294](slots/rdf__294.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2940](slots/rdf__2940.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2941](slots/rdf__2941.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2942](slots/rdf__2942.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2943](slots/rdf__2943.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2944](slots/rdf__2944.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2945](slots/rdf__2945.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2946](slots/rdf__2946.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2947](slots/rdf__2947.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2948](slots/rdf__2948.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2949](slots/rdf__2949.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__295](slots/rdf__295.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2950](slots/rdf__2950.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2951](slots/rdf__2951.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2952](slots/rdf__2952.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2953](slots/rdf__2953.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2954](slots/rdf__2954.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2955](slots/rdf__2955.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2956](slots/rdf__2956.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2957](slots/rdf__2957.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2958](slots/rdf__2958.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2959](slots/rdf__2959.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__296](slots/rdf__296.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2960](slots/rdf__2960.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2961](slots/rdf__2961.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2962](slots/rdf__2962.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2963](slots/rdf__2963.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2964](slots/rdf__2964.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2965](slots/rdf__2965.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2966](slots/rdf__2966.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2967](slots/rdf__2967.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2968](slots/rdf__2968.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2969](slots/rdf__2969.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__297](slots/rdf__297.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2970](slots/rdf__2970.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2971](slots/rdf__2971.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2972](slots/rdf__2972.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2973](slots/rdf__2973.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2974](slots/rdf__2974.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2975](slots/rdf__2975.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2976](slots/rdf__2976.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2977](slots/rdf__2977.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2978](slots/rdf__2978.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2979](slots/rdf__2979.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__298](slots/rdf__298.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2980](slots/rdf__2980.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2981](slots/rdf__2981.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2982](slots/rdf__2982.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2983](slots/rdf__2983.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2984](slots/rdf__2984.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2985](slots/rdf__2985.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2986](slots/rdf__2986.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2987](slots/rdf__2987.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2988](slots/rdf__2988.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2989](slots/rdf__2989.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__299](slots/rdf__299.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2990](slots/rdf__2990.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2991](slots/rdf__2991.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2992](slots/rdf__2992.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2993](slots/rdf__2993.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2994](slots/rdf__2994.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2995](slots/rdf__2995.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2996](slots/rdf__2996.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2997](slots/rdf__2997.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2998](slots/rdf__2998.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__2999](slots/rdf__2999.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3](slots/rdf__3.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__30](slots/rdf__30.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__300](slots/rdf__300.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3000](slots/rdf__3000.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3001](slots/rdf__3001.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3002](slots/rdf__3002.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3003](slots/rdf__3003.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3004](slots/rdf__3004.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3005](slots/rdf__3005.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3006](slots/rdf__3006.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3007](slots/rdf__3007.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3008](slots/rdf__3008.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3009](slots/rdf__3009.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__301](slots/rdf__301.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3010](slots/rdf__3010.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3011](slots/rdf__3011.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3012](slots/rdf__3012.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3013](slots/rdf__3013.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3014](slots/rdf__3014.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3015](slots/rdf__3015.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3016](slots/rdf__3016.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3017](slots/rdf__3017.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3018](slots/rdf__3018.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3019](slots/rdf__3019.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__302](slots/rdf__302.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3020](slots/rdf__3020.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3021](slots/rdf__3021.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3022](slots/rdf__3022.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3023](slots/rdf__3023.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3024](slots/rdf__3024.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3025](slots/rdf__3025.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3026](slots/rdf__3026.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3027](slots/rdf__3027.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3028](slots/rdf__3028.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3029](slots/rdf__3029.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__303](slots/rdf__303.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3030](slots/rdf__3030.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3031](slots/rdf__3031.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3032](slots/rdf__3032.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3033](slots/rdf__3033.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3034](slots/rdf__3034.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3035](slots/rdf__3035.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3036](slots/rdf__3036.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3037](slots/rdf__3037.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3038](slots/rdf__3038.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3039](slots/rdf__3039.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__304](slots/rdf__304.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3040](slots/rdf__3040.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3041](slots/rdf__3041.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3042](slots/rdf__3042.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3043](slots/rdf__3043.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3044](slots/rdf__3044.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3045](slots/rdf__3045.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3046](slots/rdf__3046.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3047](slots/rdf__3047.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3048](slots/rdf__3048.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3049](slots/rdf__3049.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__305](slots/rdf__305.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3050](slots/rdf__3050.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3051](slots/rdf__3051.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3052](slots/rdf__3052.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3053](slots/rdf__3053.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3054](slots/rdf__3054.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3055](slots/rdf__3055.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3056](slots/rdf__3056.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3057](slots/rdf__3057.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3058](slots/rdf__3058.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3059](slots/rdf__3059.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__306](slots/rdf__306.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3060](slots/rdf__3060.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3061](slots/rdf__3061.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3062](slots/rdf__3062.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3063](slots/rdf__3063.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3064](slots/rdf__3064.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3065](slots/rdf__3065.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3066](slots/rdf__3066.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3067](slots/rdf__3067.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3068](slots/rdf__3068.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3069](slots/rdf__3069.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__307](slots/rdf__307.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3070](slots/rdf__3070.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3071](slots/rdf__3071.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3072](slots/rdf__3072.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3073](slots/rdf__3073.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3074](slots/rdf__3074.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3075](slots/rdf__3075.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3076](slots/rdf__3076.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3077](slots/rdf__3077.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3078](slots/rdf__3078.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3079](slots/rdf__3079.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__308](slots/rdf__308.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3080](slots/rdf__3080.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3081](slots/rdf__3081.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3082](slots/rdf__3082.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3083](slots/rdf__3083.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3084](slots/rdf__3084.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3085](slots/rdf__3085.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3086](slots/rdf__3086.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3087](slots/rdf__3087.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3088](slots/rdf__3088.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3089](slots/rdf__3089.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__309](slots/rdf__309.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3090](slots/rdf__3090.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3091](slots/rdf__3091.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3092](slots/rdf__3092.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3093](slots/rdf__3093.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3094](slots/rdf__3094.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3095](slots/rdf__3095.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3096](slots/rdf__3096.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3097](slots/rdf__3097.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3098](slots/rdf__3098.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3099](slots/rdf__3099.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__31](slots/rdf__31.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__310](slots/rdf__310.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3100](slots/rdf__3100.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3101](slots/rdf__3101.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3102](slots/rdf__3102.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3103](slots/rdf__3103.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3104](slots/rdf__3104.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3105](slots/rdf__3105.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3106](slots/rdf__3106.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3107](slots/rdf__3107.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3108](slots/rdf__3108.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3109](slots/rdf__3109.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__311](slots/rdf__311.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3110](slots/rdf__3110.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3111](slots/rdf__3111.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3112](slots/rdf__3112.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3113](slots/rdf__3113.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3114](slots/rdf__3114.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3115](slots/rdf__3115.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3116](slots/rdf__3116.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3117](slots/rdf__3117.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3118](slots/rdf__3118.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3119](slots/rdf__3119.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__312](slots/rdf__312.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3120](slots/rdf__3120.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3121](slots/rdf__3121.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3122](slots/rdf__3122.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3123](slots/rdf__3123.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3124](slots/rdf__3124.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3125](slots/rdf__3125.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3126](slots/rdf__3126.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3127](slots/rdf__3127.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3128](slots/rdf__3128.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3129](slots/rdf__3129.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__313](slots/rdf__313.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3130](slots/rdf__3130.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3131](slots/rdf__3131.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3132](slots/rdf__3132.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3133](slots/rdf__3133.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3134](slots/rdf__3134.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3135](slots/rdf__3135.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3136](slots/rdf__3136.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3137](slots/rdf__3137.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3138](slots/rdf__3138.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3139](slots/rdf__3139.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__314](slots/rdf__314.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3140](slots/rdf__3140.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3141](slots/rdf__3141.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3142](slots/rdf__3142.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3143](slots/rdf__3143.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3144](slots/rdf__3144.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3145](slots/rdf__3145.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3146](slots/rdf__3146.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3147](slots/rdf__3147.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3148](slots/rdf__3148.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3149](slots/rdf__3149.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__315](slots/rdf__315.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3150](slots/rdf__3150.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3151](slots/rdf__3151.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3152](slots/rdf__3152.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3153](slots/rdf__3153.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3154](slots/rdf__3154.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3155](slots/rdf__3155.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3156](slots/rdf__3156.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3157](slots/rdf__3157.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3158](slots/rdf__3158.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3159](slots/rdf__3159.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__316](slots/rdf__316.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3160](slots/rdf__3160.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3161](slots/rdf__3161.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3162](slots/rdf__3162.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3163](slots/rdf__3163.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3164](slots/rdf__3164.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3165](slots/rdf__3165.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3166](slots/rdf__3166.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3167](slots/rdf__3167.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3168](slots/rdf__3168.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3169](slots/rdf__3169.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__317](slots/rdf__317.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3170](slots/rdf__3170.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3171](slots/rdf__3171.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3172](slots/rdf__3172.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3173](slots/rdf__3173.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3174](slots/rdf__3174.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3175](slots/rdf__3175.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3176](slots/rdf__3176.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3177](slots/rdf__3177.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3178](slots/rdf__3178.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3179](slots/rdf__3179.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__318](slots/rdf__318.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3180](slots/rdf__3180.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3181](slots/rdf__3181.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3182](slots/rdf__3182.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3183](slots/rdf__3183.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3184](slots/rdf__3184.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3185](slots/rdf__3185.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3186](slots/rdf__3186.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3187](slots/rdf__3187.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3188](slots/rdf__3188.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3189](slots/rdf__3189.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__319](slots/rdf__319.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3190](slots/rdf__3190.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3191](slots/rdf__3191.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3192](slots/rdf__3192.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3193](slots/rdf__3193.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3194](slots/rdf__3194.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3195](slots/rdf__3195.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3196](slots/rdf__3196.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3197](slots/rdf__3197.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3198](slots/rdf__3198.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3199](slots/rdf__3199.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__32](slots/rdf__32.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__320](slots/rdf__320.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3200](slots/rdf__3200.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3201](slots/rdf__3201.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3202](slots/rdf__3202.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3203](slots/rdf__3203.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3204](slots/rdf__3204.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3205](slots/rdf__3205.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3206](slots/rdf__3206.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3207](slots/rdf__3207.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3208](slots/rdf__3208.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3209](slots/rdf__3209.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__321](slots/rdf__321.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3210](slots/rdf__3210.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3211](slots/rdf__3211.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3212](slots/rdf__3212.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3213](slots/rdf__3213.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3214](slots/rdf__3214.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3215](slots/rdf__3215.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3216](slots/rdf__3216.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3217](slots/rdf__3217.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3218](slots/rdf__3218.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3219](slots/rdf__3219.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__322](slots/rdf__322.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3220](slots/rdf__3220.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3221](slots/rdf__3221.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3222](slots/rdf__3222.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3223](slots/rdf__3223.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3224](slots/rdf__3224.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3225](slots/rdf__3225.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3226](slots/rdf__3226.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3227](slots/rdf__3227.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3228](slots/rdf__3228.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3229](slots/rdf__3229.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__323](slots/rdf__323.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3230](slots/rdf__3230.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3231](slots/rdf__3231.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3232](slots/rdf__3232.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3233](slots/rdf__3233.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3234](slots/rdf__3234.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3235](slots/rdf__3235.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3236](slots/rdf__3236.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3237](slots/rdf__3237.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3238](slots/rdf__3238.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3239](slots/rdf__3239.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__324](slots/rdf__324.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3240](slots/rdf__3240.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3241](slots/rdf__3241.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3242](slots/rdf__3242.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3243](slots/rdf__3243.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3244](slots/rdf__3244.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3245](slots/rdf__3245.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3246](slots/rdf__3246.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3247](slots/rdf__3247.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3248](slots/rdf__3248.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3249](slots/rdf__3249.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__325](slots/rdf__325.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3250](slots/rdf__3250.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3251](slots/rdf__3251.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3252](slots/rdf__3252.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3253](slots/rdf__3253.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3254](slots/rdf__3254.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3255](slots/rdf__3255.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3256](slots/rdf__3256.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3257](slots/rdf__3257.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3258](slots/rdf__3258.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3259](slots/rdf__3259.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__326](slots/rdf__326.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3260](slots/rdf__3260.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3261](slots/rdf__3261.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3262](slots/rdf__3262.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3263](slots/rdf__3263.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3264](slots/rdf__3264.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3265](slots/rdf__3265.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3266](slots/rdf__3266.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3267](slots/rdf__3267.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3268](slots/rdf__3268.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3269](slots/rdf__3269.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__327](slots/rdf__327.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3270](slots/rdf__3270.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3271](slots/rdf__3271.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3272](slots/rdf__3272.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3273](slots/rdf__3273.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3274](slots/rdf__3274.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3275](slots/rdf__3275.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3276](slots/rdf__3276.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3277](slots/rdf__3277.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3278](slots/rdf__3278.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3279](slots/rdf__3279.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__328](slots/rdf__328.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3280](slots/rdf__3280.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3281](slots/rdf__3281.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3282](slots/rdf__3282.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3283](slots/rdf__3283.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3284](slots/rdf__3284.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3285](slots/rdf__3285.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3286](slots/rdf__3286.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3287](slots/rdf__3287.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3288](slots/rdf__3288.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3289](slots/rdf__3289.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__329](slots/rdf__329.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3290](slots/rdf__3290.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3291](slots/rdf__3291.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3292](slots/rdf__3292.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3293](slots/rdf__3293.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3294](slots/rdf__3294.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3295](slots/rdf__3295.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3296](slots/rdf__3296.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3297](slots/rdf__3297.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3298](slots/rdf__3298.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3299](slots/rdf__3299.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__33](slots/rdf__33.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__330](slots/rdf__330.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3300](slots/rdf__3300.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3301](slots/rdf__3301.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3302](slots/rdf__3302.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3303](slots/rdf__3303.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3304](slots/rdf__3304.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3305](slots/rdf__3305.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3306](slots/rdf__3306.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3307](slots/rdf__3307.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3308](slots/rdf__3308.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3309](slots/rdf__3309.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__331](slots/rdf__331.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3310](slots/rdf__3310.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3311](slots/rdf__3311.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3312](slots/rdf__3312.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3313](slots/rdf__3313.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3314](slots/rdf__3314.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3315](slots/rdf__3315.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3316](slots/rdf__3316.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3317](slots/rdf__3317.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3318](slots/rdf__3318.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3319](slots/rdf__3319.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__332](slots/rdf__332.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3320](slots/rdf__3320.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3321](slots/rdf__3321.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3322](slots/rdf__3322.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3323](slots/rdf__3323.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3324](slots/rdf__3324.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3325](slots/rdf__3325.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3326](slots/rdf__3326.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3327](slots/rdf__3327.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3328](slots/rdf__3328.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3329](slots/rdf__3329.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__333](slots/rdf__333.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3330](slots/rdf__3330.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3331](slots/rdf__3331.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3332](slots/rdf__3332.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3333](slots/rdf__3333.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3334](slots/rdf__3334.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3335](slots/rdf__3335.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3336](slots/rdf__3336.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3337](slots/rdf__3337.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3338](slots/rdf__3338.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3339](slots/rdf__3339.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__334](slots/rdf__334.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3340](slots/rdf__3340.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3341](slots/rdf__3341.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3342](slots/rdf__3342.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3343](slots/rdf__3343.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3344](slots/rdf__3344.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3345](slots/rdf__3345.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3346](slots/rdf__3346.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3347](slots/rdf__3347.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3348](slots/rdf__3348.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3349](slots/rdf__3349.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__335](slots/rdf__335.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3350](slots/rdf__3350.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3351](slots/rdf__3351.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3352](slots/rdf__3352.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3353](slots/rdf__3353.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3354](slots/rdf__3354.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3355](slots/rdf__3355.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3356](slots/rdf__3356.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3357](slots/rdf__3357.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3358](slots/rdf__3358.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3359](slots/rdf__3359.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__336](slots/rdf__336.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3360](slots/rdf__3360.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3361](slots/rdf__3361.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3362](slots/rdf__3362.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3363](slots/rdf__3363.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3364](slots/rdf__3364.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3365](slots/rdf__3365.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3366](slots/rdf__3366.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3367](slots/rdf__3367.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3368](slots/rdf__3368.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3369](slots/rdf__3369.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__337](slots/rdf__337.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3370](slots/rdf__3370.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3371](slots/rdf__3371.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3372](slots/rdf__3372.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3373](slots/rdf__3373.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3374](slots/rdf__3374.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3375](slots/rdf__3375.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3376](slots/rdf__3376.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3377](slots/rdf__3377.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3378](slots/rdf__3378.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3379](slots/rdf__3379.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__338](slots/rdf__338.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3380](slots/rdf__3380.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3381](slots/rdf__3381.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3382](slots/rdf__3382.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3383](slots/rdf__3383.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3384](slots/rdf__3384.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3385](slots/rdf__3385.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3386](slots/rdf__3386.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3387](slots/rdf__3387.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3388](slots/rdf__3388.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3389](slots/rdf__3389.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__339](slots/rdf__339.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3390](slots/rdf__3390.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3391](slots/rdf__3391.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3392](slots/rdf__3392.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3393](slots/rdf__3393.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3394](slots/rdf__3394.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3395](slots/rdf__3395.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3396](slots/rdf__3396.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3397](slots/rdf__3397.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3398](slots/rdf__3398.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3399](slots/rdf__3399.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__34](slots/rdf__34.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__340](slots/rdf__340.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3400](slots/rdf__3400.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3401](slots/rdf__3401.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3402](slots/rdf__3402.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3403](slots/rdf__3403.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3404](slots/rdf__3404.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3405](slots/rdf__3405.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3406](slots/rdf__3406.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3407](slots/rdf__3407.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3408](slots/rdf__3408.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3409](slots/rdf__3409.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__341](slots/rdf__341.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3410](slots/rdf__3410.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3411](slots/rdf__3411.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3412](slots/rdf__3412.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3413](slots/rdf__3413.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3414](slots/rdf__3414.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3415](slots/rdf__3415.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3416](slots/rdf__3416.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3417](slots/rdf__3417.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3418](slots/rdf__3418.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3419](slots/rdf__3419.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__342](slots/rdf__342.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3420](slots/rdf__3420.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3421](slots/rdf__3421.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3422](slots/rdf__3422.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3423](slots/rdf__3423.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3424](slots/rdf__3424.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3425](slots/rdf__3425.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3426](slots/rdf__3426.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3427](slots/rdf__3427.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3428](slots/rdf__3428.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3429](slots/rdf__3429.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__343](slots/rdf__343.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3430](slots/rdf__3430.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3431](slots/rdf__3431.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3432](slots/rdf__3432.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3433](slots/rdf__3433.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3434](slots/rdf__3434.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3435](slots/rdf__3435.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3436](slots/rdf__3436.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3437](slots/rdf__3437.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3438](slots/rdf__3438.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3439](slots/rdf__3439.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__344](slots/rdf__344.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3440](slots/rdf__3440.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3441](slots/rdf__3441.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3442](slots/rdf__3442.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3443](slots/rdf__3443.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3444](slots/rdf__3444.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3445](slots/rdf__3445.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3446](slots/rdf__3446.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3447](slots/rdf__3447.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3448](slots/rdf__3448.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3449](slots/rdf__3449.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__345](slots/rdf__345.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3450](slots/rdf__3450.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3451](slots/rdf__3451.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3452](slots/rdf__3452.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3453](slots/rdf__3453.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3454](slots/rdf__3454.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3455](slots/rdf__3455.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3456](slots/rdf__3456.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3457](slots/rdf__3457.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3458](slots/rdf__3458.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3459](slots/rdf__3459.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__346](slots/rdf__346.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3460](slots/rdf__3460.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3461](slots/rdf__3461.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3462](slots/rdf__3462.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3463](slots/rdf__3463.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3464](slots/rdf__3464.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3465](slots/rdf__3465.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3466](slots/rdf__3466.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3467](slots/rdf__3467.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3468](slots/rdf__3468.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3469](slots/rdf__3469.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__347](slots/rdf__347.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3470](slots/rdf__3470.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3471](slots/rdf__3471.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3472](slots/rdf__3472.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3473](slots/rdf__3473.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3474](slots/rdf__3474.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3475](slots/rdf__3475.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3476](slots/rdf__3476.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3477](slots/rdf__3477.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3478](slots/rdf__3478.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3479](slots/rdf__3479.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__348](slots/rdf__348.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3480](slots/rdf__3480.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3481](slots/rdf__3481.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3482](slots/rdf__3482.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3483](slots/rdf__3483.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3484](slots/rdf__3484.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3485](slots/rdf__3485.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3486](slots/rdf__3486.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3487](slots/rdf__3487.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3488](slots/rdf__3488.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3489](slots/rdf__3489.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__349](slots/rdf__349.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3490](slots/rdf__3490.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3491](slots/rdf__3491.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3492](slots/rdf__3492.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3493](slots/rdf__3493.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3494](slots/rdf__3494.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3495](slots/rdf__3495.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3496](slots/rdf__3496.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3497](slots/rdf__3497.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3498](slots/rdf__3498.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3499](slots/rdf__3499.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__35](slots/rdf__35.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__350](slots/rdf__350.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3500](slots/rdf__3500.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3501](slots/rdf__3501.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3502](slots/rdf__3502.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3503](slots/rdf__3503.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3504](slots/rdf__3504.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3505](slots/rdf__3505.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3506](slots/rdf__3506.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3507](slots/rdf__3507.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3508](slots/rdf__3508.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3509](slots/rdf__3509.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__351](slots/rdf__351.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3510](slots/rdf__3510.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3511](slots/rdf__3511.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3512](slots/rdf__3512.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3513](slots/rdf__3513.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3514](slots/rdf__3514.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3515](slots/rdf__3515.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3516](slots/rdf__3516.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3517](slots/rdf__3517.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3518](slots/rdf__3518.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3519](slots/rdf__3519.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__352](slots/rdf__352.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3520](slots/rdf__3520.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3521](slots/rdf__3521.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3522](slots/rdf__3522.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3523](slots/rdf__3523.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3524](slots/rdf__3524.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3525](slots/rdf__3525.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3526](slots/rdf__3526.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3527](slots/rdf__3527.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3528](slots/rdf__3528.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3529](slots/rdf__3529.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__353](slots/rdf__353.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3530](slots/rdf__3530.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3531](slots/rdf__3531.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3532](slots/rdf__3532.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3533](slots/rdf__3533.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3534](slots/rdf__3534.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3535](slots/rdf__3535.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3536](slots/rdf__3536.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3537](slots/rdf__3537.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3538](slots/rdf__3538.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3539](slots/rdf__3539.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__354](slots/rdf__354.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3540](slots/rdf__3540.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3541](slots/rdf__3541.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3542](slots/rdf__3542.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3543](slots/rdf__3543.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3544](slots/rdf__3544.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3545](slots/rdf__3545.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3546](slots/rdf__3546.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3547](slots/rdf__3547.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3548](slots/rdf__3548.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3549](slots/rdf__3549.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__355](slots/rdf__355.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3550](slots/rdf__3550.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3551](slots/rdf__3551.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3552](slots/rdf__3552.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3553](slots/rdf__3553.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3554](slots/rdf__3554.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3555](slots/rdf__3555.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3556](slots/rdf__3556.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3557](slots/rdf__3557.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3558](slots/rdf__3558.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3559](slots/rdf__3559.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__356](slots/rdf__356.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3560](slots/rdf__3560.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3561](slots/rdf__3561.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3562](slots/rdf__3562.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3563](slots/rdf__3563.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3564](slots/rdf__3564.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3565](slots/rdf__3565.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3566](slots/rdf__3566.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3567](slots/rdf__3567.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3568](slots/rdf__3568.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3569](slots/rdf__3569.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__357](slots/rdf__357.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3570](slots/rdf__3570.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3571](slots/rdf__3571.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3572](slots/rdf__3572.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3573](slots/rdf__3573.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3574](slots/rdf__3574.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3575](slots/rdf__3575.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3576](slots/rdf__3576.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3577](slots/rdf__3577.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3578](slots/rdf__3578.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3579](slots/rdf__3579.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__358](slots/rdf__358.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3580](slots/rdf__3580.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3581](slots/rdf__3581.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3582](slots/rdf__3582.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3583](slots/rdf__3583.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3584](slots/rdf__3584.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3585](slots/rdf__3585.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3586](slots/rdf__3586.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3587](slots/rdf__3587.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3588](slots/rdf__3588.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3589](slots/rdf__3589.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__359](slots/rdf__359.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3590](slots/rdf__3590.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3591](slots/rdf__3591.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3592](slots/rdf__3592.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3593](slots/rdf__3593.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3594](slots/rdf__3594.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3595](slots/rdf__3595.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3596](slots/rdf__3596.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3597](slots/rdf__3597.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3598](slots/rdf__3598.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3599](slots/rdf__3599.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__36](slots/rdf__36.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__360](slots/rdf__360.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3600](slots/rdf__3600.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3601](slots/rdf__3601.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3602](slots/rdf__3602.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3603](slots/rdf__3603.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3604](slots/rdf__3604.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3605](slots/rdf__3605.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3606](slots/rdf__3606.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3607](slots/rdf__3607.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3608](slots/rdf__3608.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3609](slots/rdf__3609.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__361](slots/rdf__361.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3610](slots/rdf__3610.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3611](slots/rdf__3611.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3612](slots/rdf__3612.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3613](slots/rdf__3613.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3614](slots/rdf__3614.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3615](slots/rdf__3615.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3616](slots/rdf__3616.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3617](slots/rdf__3617.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3618](slots/rdf__3618.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3619](slots/rdf__3619.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__362](slots/rdf__362.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3620](slots/rdf__3620.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3621](slots/rdf__3621.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3622](slots/rdf__3622.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3623](slots/rdf__3623.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3624](slots/rdf__3624.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3625](slots/rdf__3625.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3626](slots/rdf__3626.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3627](slots/rdf__3627.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3628](slots/rdf__3628.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3629](slots/rdf__3629.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__363](slots/rdf__363.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3630](slots/rdf__3630.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3631](slots/rdf__3631.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3632](slots/rdf__3632.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3633](slots/rdf__3633.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3634](slots/rdf__3634.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3635](slots/rdf__3635.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3636](slots/rdf__3636.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3637](slots/rdf__3637.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3638](slots/rdf__3638.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3639](slots/rdf__3639.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__364](slots/rdf__364.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3640](slots/rdf__3640.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3641](slots/rdf__3641.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3642](slots/rdf__3642.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3643](slots/rdf__3643.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3644](slots/rdf__3644.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3645](slots/rdf__3645.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3646](slots/rdf__3646.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3647](slots/rdf__3647.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3648](slots/rdf__3648.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3649](slots/rdf__3649.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__365](slots/rdf__365.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3650](slots/rdf__3650.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3651](slots/rdf__3651.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3652](slots/rdf__3652.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3653](slots/rdf__3653.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3654](slots/rdf__3654.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3655](slots/rdf__3655.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3656](slots/rdf__3656.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3657](slots/rdf__3657.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3658](slots/rdf__3658.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3659](slots/rdf__3659.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__366](slots/rdf__366.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3660](slots/rdf__3660.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3661](slots/rdf__3661.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3662](slots/rdf__3662.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3663](slots/rdf__3663.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3664](slots/rdf__3664.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3665](slots/rdf__3665.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3666](slots/rdf__3666.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3667](slots/rdf__3667.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3668](slots/rdf__3668.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3669](slots/rdf__3669.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__367](slots/rdf__367.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3670](slots/rdf__3670.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3671](slots/rdf__3671.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3672](slots/rdf__3672.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3673](slots/rdf__3673.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3674](slots/rdf__3674.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3675](slots/rdf__3675.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3676](slots/rdf__3676.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3677](slots/rdf__3677.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3678](slots/rdf__3678.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3679](slots/rdf__3679.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__368](slots/rdf__368.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3680](slots/rdf__3680.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3681](slots/rdf__3681.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3682](slots/rdf__3682.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3683](slots/rdf__3683.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3684](slots/rdf__3684.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3685](slots/rdf__3685.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3686](slots/rdf__3686.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3687](slots/rdf__3687.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3688](slots/rdf__3688.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3689](slots/rdf__3689.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__369](slots/rdf__369.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3690](slots/rdf__3690.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3691](slots/rdf__3691.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3692](slots/rdf__3692.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3693](slots/rdf__3693.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3694](slots/rdf__3694.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3695](slots/rdf__3695.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3696](slots/rdf__3696.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3697](slots/rdf__3697.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3698](slots/rdf__3698.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3699](slots/rdf__3699.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__37](slots/rdf__37.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__370](slots/rdf__370.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3700](slots/rdf__3700.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3701](slots/rdf__3701.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3702](slots/rdf__3702.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3703](slots/rdf__3703.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3704](slots/rdf__3704.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3705](slots/rdf__3705.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3706](slots/rdf__3706.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3707](slots/rdf__3707.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3708](slots/rdf__3708.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3709](slots/rdf__3709.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__371](slots/rdf__371.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3710](slots/rdf__3710.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3711](slots/rdf__3711.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3712](slots/rdf__3712.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3713](slots/rdf__3713.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3714](slots/rdf__3714.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3715](slots/rdf__3715.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3716](slots/rdf__3716.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3717](slots/rdf__3717.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3718](slots/rdf__3718.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3719](slots/rdf__3719.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__372](slots/rdf__372.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3720](slots/rdf__3720.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3721](slots/rdf__3721.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3722](slots/rdf__3722.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3723](slots/rdf__3723.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3724](slots/rdf__3724.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3725](slots/rdf__3725.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3726](slots/rdf__3726.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3727](slots/rdf__3727.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3728](slots/rdf__3728.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3729](slots/rdf__3729.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__373](slots/rdf__373.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3730](slots/rdf__3730.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3731](slots/rdf__3731.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3732](slots/rdf__3732.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3733](slots/rdf__3733.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3734](slots/rdf__3734.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3735](slots/rdf__3735.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3736](slots/rdf__3736.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3737](slots/rdf__3737.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3738](slots/rdf__3738.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3739](slots/rdf__3739.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__374](slots/rdf__374.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3740](slots/rdf__3740.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3741](slots/rdf__3741.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3742](slots/rdf__3742.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3743](slots/rdf__3743.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3744](slots/rdf__3744.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3745](slots/rdf__3745.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3746](slots/rdf__3746.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3747](slots/rdf__3747.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3748](slots/rdf__3748.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3749](slots/rdf__3749.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__375](slots/rdf__375.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3750](slots/rdf__3750.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3751](slots/rdf__3751.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3752](slots/rdf__3752.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3753](slots/rdf__3753.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3754](slots/rdf__3754.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3755](slots/rdf__3755.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3756](slots/rdf__3756.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3757](slots/rdf__3757.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3758](slots/rdf__3758.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3759](slots/rdf__3759.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__376](slots/rdf__376.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3760](slots/rdf__3760.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3761](slots/rdf__3761.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3762](slots/rdf__3762.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3763](slots/rdf__3763.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3764](slots/rdf__3764.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3765](slots/rdf__3765.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3766](slots/rdf__3766.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3767](slots/rdf__3767.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3768](slots/rdf__3768.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3769](slots/rdf__3769.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__377](slots/rdf__377.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3770](slots/rdf__3770.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3771](slots/rdf__3771.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3772](slots/rdf__3772.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3773](slots/rdf__3773.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3774](slots/rdf__3774.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3775](slots/rdf__3775.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3776](slots/rdf__3776.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3777](slots/rdf__3777.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3778](slots/rdf__3778.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3779](slots/rdf__3779.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__378](slots/rdf__378.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3780](slots/rdf__3780.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3781](slots/rdf__3781.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3782](slots/rdf__3782.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3783](slots/rdf__3783.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3784](slots/rdf__3784.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3785](slots/rdf__3785.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3786](slots/rdf__3786.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3787](slots/rdf__3787.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3788](slots/rdf__3788.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3789](slots/rdf__3789.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__379](slots/rdf__379.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3790](slots/rdf__3790.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3791](slots/rdf__3791.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3792](slots/rdf__3792.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3793](slots/rdf__3793.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3794](slots/rdf__3794.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3795](slots/rdf__3795.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3796](slots/rdf__3796.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3797](slots/rdf__3797.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3798](slots/rdf__3798.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3799](slots/rdf__3799.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__38](slots/rdf__38.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__380](slots/rdf__380.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3800](slots/rdf__3800.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3801](slots/rdf__3801.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3802](slots/rdf__3802.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3803](slots/rdf__3803.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3804](slots/rdf__3804.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3805](slots/rdf__3805.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3806](slots/rdf__3806.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3807](slots/rdf__3807.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3808](slots/rdf__3808.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3809](slots/rdf__3809.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__381](slots/rdf__381.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3810](slots/rdf__3810.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3811](slots/rdf__3811.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3812](slots/rdf__3812.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3813](slots/rdf__3813.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3814](slots/rdf__3814.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3815](slots/rdf__3815.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3816](slots/rdf__3816.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3817](slots/rdf__3817.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3818](slots/rdf__3818.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3819](slots/rdf__3819.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__382](slots/rdf__382.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3820](slots/rdf__3820.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3821](slots/rdf__3821.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3822](slots/rdf__3822.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3823](slots/rdf__3823.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3824](slots/rdf__3824.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3825](slots/rdf__3825.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3826](slots/rdf__3826.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3827](slots/rdf__3827.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3828](slots/rdf__3828.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3829](slots/rdf__3829.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__383](slots/rdf__383.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3830](slots/rdf__3830.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3831](slots/rdf__3831.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3832](slots/rdf__3832.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3833](slots/rdf__3833.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3834](slots/rdf__3834.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3835](slots/rdf__3835.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3836](slots/rdf__3836.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3837](slots/rdf__3837.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3838](slots/rdf__3838.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3839](slots/rdf__3839.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__384](slots/rdf__384.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3840](slots/rdf__3840.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3841](slots/rdf__3841.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3842](slots/rdf__3842.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3843](slots/rdf__3843.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3844](slots/rdf__3844.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3845](slots/rdf__3845.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3846](slots/rdf__3846.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3847](slots/rdf__3847.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3848](slots/rdf__3848.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3849](slots/rdf__3849.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__385](slots/rdf__385.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3850](slots/rdf__3850.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3851](slots/rdf__3851.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3852](slots/rdf__3852.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3853](slots/rdf__3853.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3854](slots/rdf__3854.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3855](slots/rdf__3855.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3856](slots/rdf__3856.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3857](slots/rdf__3857.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3858](slots/rdf__3858.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3859](slots/rdf__3859.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__386](slots/rdf__386.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3860](slots/rdf__3860.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3861](slots/rdf__3861.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3862](slots/rdf__3862.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3863](slots/rdf__3863.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3864](slots/rdf__3864.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3865](slots/rdf__3865.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3866](slots/rdf__3866.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3867](slots/rdf__3867.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3868](slots/rdf__3868.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3869](slots/rdf__3869.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__387](slots/rdf__387.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3870](slots/rdf__3870.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3871](slots/rdf__3871.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3872](slots/rdf__3872.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3873](slots/rdf__3873.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3874](slots/rdf__3874.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3875](slots/rdf__3875.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3876](slots/rdf__3876.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3877](slots/rdf__3877.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3878](slots/rdf__3878.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3879](slots/rdf__3879.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__388](slots/rdf__388.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3880](slots/rdf__3880.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3881](slots/rdf__3881.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3882](slots/rdf__3882.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3883](slots/rdf__3883.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3884](slots/rdf__3884.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3885](slots/rdf__3885.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3886](slots/rdf__3886.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3887](slots/rdf__3887.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3888](slots/rdf__3888.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3889](slots/rdf__3889.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__389](slots/rdf__389.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3890](slots/rdf__3890.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3891](slots/rdf__3891.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3892](slots/rdf__3892.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3893](slots/rdf__3893.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3894](slots/rdf__3894.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3895](slots/rdf__3895.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3896](slots/rdf__3896.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3897](slots/rdf__3897.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3898](slots/rdf__3898.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3899](slots/rdf__3899.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__39](slots/rdf__39.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__390](slots/rdf__390.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3900](slots/rdf__3900.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3901](slots/rdf__3901.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3902](slots/rdf__3902.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3903](slots/rdf__3903.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3904](slots/rdf__3904.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3905](slots/rdf__3905.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3906](slots/rdf__3906.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3907](slots/rdf__3907.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3908](slots/rdf__3908.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3909](slots/rdf__3909.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__391](slots/rdf__391.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3910](slots/rdf__3910.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3911](slots/rdf__3911.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3912](slots/rdf__3912.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3913](slots/rdf__3913.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3914](slots/rdf__3914.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3915](slots/rdf__3915.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3916](slots/rdf__3916.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3917](slots/rdf__3917.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3918](slots/rdf__3918.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3919](slots/rdf__3919.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__392](slots/rdf__392.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3920](slots/rdf__3920.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3921](slots/rdf__3921.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3922](slots/rdf__3922.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3923](slots/rdf__3923.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3924](slots/rdf__3924.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3925](slots/rdf__3925.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3926](slots/rdf__3926.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3927](slots/rdf__3927.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3928](slots/rdf__3928.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3929](slots/rdf__3929.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__393](slots/rdf__393.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3930](slots/rdf__3930.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3931](slots/rdf__3931.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3932](slots/rdf__3932.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3933](slots/rdf__3933.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3934](slots/rdf__3934.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3935](slots/rdf__3935.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3936](slots/rdf__3936.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3937](slots/rdf__3937.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3938](slots/rdf__3938.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3939](slots/rdf__3939.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__394](slots/rdf__394.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3940](slots/rdf__3940.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3941](slots/rdf__3941.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3942](slots/rdf__3942.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3943](slots/rdf__3943.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3944](slots/rdf__3944.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3945](slots/rdf__3945.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3946](slots/rdf__3946.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3947](slots/rdf__3947.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3948](slots/rdf__3948.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3949](slots/rdf__3949.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__395](slots/rdf__395.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3950](slots/rdf__3950.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3951](slots/rdf__3951.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3952](slots/rdf__3952.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3953](slots/rdf__3953.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3954](slots/rdf__3954.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3955](slots/rdf__3955.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3956](slots/rdf__3956.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3957](slots/rdf__3957.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3958](slots/rdf__3958.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3959](slots/rdf__3959.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__396](slots/rdf__396.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3960](slots/rdf__3960.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3961](slots/rdf__3961.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3962](slots/rdf__3962.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3963](slots/rdf__3963.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3964](slots/rdf__3964.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3965](slots/rdf__3965.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3966](slots/rdf__3966.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3967](slots/rdf__3967.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3968](slots/rdf__3968.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3969](slots/rdf__3969.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__397](slots/rdf__397.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3970](slots/rdf__3970.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3971](slots/rdf__3971.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3972](slots/rdf__3972.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3973](slots/rdf__3973.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3974](slots/rdf__3974.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3975](slots/rdf__3975.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3976](slots/rdf__3976.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3977](slots/rdf__3977.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3978](slots/rdf__3978.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3979](slots/rdf__3979.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__398](slots/rdf__398.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3980](slots/rdf__3980.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3981](slots/rdf__3981.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3982](slots/rdf__3982.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3983](slots/rdf__3983.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3984](slots/rdf__3984.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3985](slots/rdf__3985.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3986](slots/rdf__3986.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3987](slots/rdf__3987.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3988](slots/rdf__3988.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3989](slots/rdf__3989.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__399](slots/rdf__399.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3990](slots/rdf__3990.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3991](slots/rdf__3991.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3992](slots/rdf__3992.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3993](slots/rdf__3993.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3994](slots/rdf__3994.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3995](slots/rdf__3995.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3996](slots/rdf__3996.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3997](slots/rdf__3997.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3998](slots/rdf__3998.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__3999](slots/rdf__3999.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4](slots/rdf__4.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__40](slots/rdf__40.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__400](slots/rdf__400.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4000](slots/rdf__4000.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4001](slots/rdf__4001.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4002](slots/rdf__4002.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4003](slots/rdf__4003.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4004](slots/rdf__4004.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4005](slots/rdf__4005.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4006](slots/rdf__4006.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4007](slots/rdf__4007.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4008](slots/rdf__4008.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4009](slots/rdf__4009.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__401](slots/rdf__401.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4010](slots/rdf__4010.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4011](slots/rdf__4011.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4012](slots/rdf__4012.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4013](slots/rdf__4013.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4014](slots/rdf__4014.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4015](slots/rdf__4015.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4016](slots/rdf__4016.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4017](slots/rdf__4017.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4018](slots/rdf__4018.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4019](slots/rdf__4019.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__402](slots/rdf__402.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4020](slots/rdf__4020.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4021](slots/rdf__4021.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4022](slots/rdf__4022.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4023](slots/rdf__4023.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4024](slots/rdf__4024.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4025](slots/rdf__4025.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4026](slots/rdf__4026.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4027](slots/rdf__4027.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4028](slots/rdf__4028.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4029](slots/rdf__4029.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__403](slots/rdf__403.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4030](slots/rdf__4030.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4031](slots/rdf__4031.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4032](slots/rdf__4032.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4033](slots/rdf__4033.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4034](slots/rdf__4034.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4035](slots/rdf__4035.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4036](slots/rdf__4036.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4037](slots/rdf__4037.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4038](slots/rdf__4038.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4039](slots/rdf__4039.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__404](slots/rdf__404.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4040](slots/rdf__4040.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4041](slots/rdf__4041.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4042](slots/rdf__4042.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4043](slots/rdf__4043.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4044](slots/rdf__4044.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4045](slots/rdf__4045.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4046](slots/rdf__4046.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4047](slots/rdf__4047.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4048](slots/rdf__4048.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4049](slots/rdf__4049.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__405](slots/rdf__405.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4050](slots/rdf__4050.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4051](slots/rdf__4051.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4052](slots/rdf__4052.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4053](slots/rdf__4053.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4054](slots/rdf__4054.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4055](slots/rdf__4055.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4056](slots/rdf__4056.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4057](slots/rdf__4057.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4058](slots/rdf__4058.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4059](slots/rdf__4059.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__406](slots/rdf__406.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4060](slots/rdf__4060.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4061](slots/rdf__4061.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4062](slots/rdf__4062.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4063](slots/rdf__4063.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4064](slots/rdf__4064.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4065](slots/rdf__4065.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4066](slots/rdf__4066.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4067](slots/rdf__4067.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4068](slots/rdf__4068.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4069](slots/rdf__4069.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__407](slots/rdf__407.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4070](slots/rdf__4070.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4071](slots/rdf__4071.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4072](slots/rdf__4072.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4073](slots/rdf__4073.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4074](slots/rdf__4074.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4075](slots/rdf__4075.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4076](slots/rdf__4076.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4077](slots/rdf__4077.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4078](slots/rdf__4078.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4079](slots/rdf__4079.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__408](slots/rdf__408.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4080](slots/rdf__4080.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4081](slots/rdf__4081.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4082](slots/rdf__4082.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4083](slots/rdf__4083.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4084](slots/rdf__4084.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4085](slots/rdf__4085.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4086](slots/rdf__4086.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4087](slots/rdf__4087.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4088](slots/rdf__4088.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4089](slots/rdf__4089.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__409](slots/rdf__409.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4090](slots/rdf__4090.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4091](slots/rdf__4091.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4092](slots/rdf__4092.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4093](slots/rdf__4093.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4094](slots/rdf__4094.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4095](slots/rdf__4095.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4096](slots/rdf__4096.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4097](slots/rdf__4097.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4098](slots/rdf__4098.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4099](slots/rdf__4099.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__41](slots/rdf__41.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__410](slots/rdf__410.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4100](slots/rdf__4100.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4101](slots/rdf__4101.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4102](slots/rdf__4102.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4103](slots/rdf__4103.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4104](slots/rdf__4104.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4105](slots/rdf__4105.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4106](slots/rdf__4106.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4107](slots/rdf__4107.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4108](slots/rdf__4108.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4109](slots/rdf__4109.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__411](slots/rdf__411.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4110](slots/rdf__4110.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4111](slots/rdf__4111.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4112](slots/rdf__4112.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4113](slots/rdf__4113.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4114](slots/rdf__4114.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4115](slots/rdf__4115.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4116](slots/rdf__4116.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4117](slots/rdf__4117.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4118](slots/rdf__4118.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4119](slots/rdf__4119.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__412](slots/rdf__412.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4120](slots/rdf__4120.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4121](slots/rdf__4121.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4122](slots/rdf__4122.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4123](slots/rdf__4123.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4124](slots/rdf__4124.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4125](slots/rdf__4125.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4126](slots/rdf__4126.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4127](slots/rdf__4127.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4128](slots/rdf__4128.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4129](slots/rdf__4129.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__413](slots/rdf__413.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4130](slots/rdf__4130.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4131](slots/rdf__4131.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4132](slots/rdf__4132.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4133](slots/rdf__4133.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4134](slots/rdf__4134.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4135](slots/rdf__4135.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4136](slots/rdf__4136.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4137](slots/rdf__4137.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4138](slots/rdf__4138.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4139](slots/rdf__4139.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__414](slots/rdf__414.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4140](slots/rdf__4140.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4141](slots/rdf__4141.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4142](slots/rdf__4142.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4143](slots/rdf__4143.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4144](slots/rdf__4144.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4145](slots/rdf__4145.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4146](slots/rdf__4146.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4147](slots/rdf__4147.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4148](slots/rdf__4148.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4149](slots/rdf__4149.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__415](slots/rdf__415.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4150](slots/rdf__4150.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4151](slots/rdf__4151.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4152](slots/rdf__4152.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4153](slots/rdf__4153.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4154](slots/rdf__4154.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4155](slots/rdf__4155.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4156](slots/rdf__4156.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4157](slots/rdf__4157.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4158](slots/rdf__4158.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4159](slots/rdf__4159.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__416](slots/rdf__416.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4160](slots/rdf__4160.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4161](slots/rdf__4161.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4162](slots/rdf__4162.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4163](slots/rdf__4163.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4164](slots/rdf__4164.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4165](slots/rdf__4165.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4166](slots/rdf__4166.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4167](slots/rdf__4167.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4168](slots/rdf__4168.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4169](slots/rdf__4169.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__417](slots/rdf__417.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4170](slots/rdf__4170.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4171](slots/rdf__4171.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4172](slots/rdf__4172.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4173](slots/rdf__4173.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4174](slots/rdf__4174.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4175](slots/rdf__4175.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4176](slots/rdf__4176.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4177](slots/rdf__4177.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4178](slots/rdf__4178.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4179](slots/rdf__4179.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__418](slots/rdf__418.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4180](slots/rdf__4180.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4181](slots/rdf__4181.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4182](slots/rdf__4182.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4183](slots/rdf__4183.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4184](slots/rdf__4184.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4185](slots/rdf__4185.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4186](slots/rdf__4186.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4187](slots/rdf__4187.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4188](slots/rdf__4188.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4189](slots/rdf__4189.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__419](slots/rdf__419.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4190](slots/rdf__4190.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4191](slots/rdf__4191.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4192](slots/rdf__4192.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4193](slots/rdf__4193.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4194](slots/rdf__4194.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4195](slots/rdf__4195.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4196](slots/rdf__4196.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4197](slots/rdf__4197.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4198](slots/rdf__4198.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4199](slots/rdf__4199.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__42](slots/rdf__42.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__420](slots/rdf__420.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4200](slots/rdf__4200.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4201](slots/rdf__4201.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4202](slots/rdf__4202.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4203](slots/rdf__4203.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4204](slots/rdf__4204.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4205](slots/rdf__4205.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4206](slots/rdf__4206.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4207](slots/rdf__4207.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4208](slots/rdf__4208.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4209](slots/rdf__4209.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__421](slots/rdf__421.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4210](slots/rdf__4210.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4211](slots/rdf__4211.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4212](slots/rdf__4212.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4213](slots/rdf__4213.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4214](slots/rdf__4214.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4215](slots/rdf__4215.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4216](slots/rdf__4216.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4217](slots/rdf__4217.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4218](slots/rdf__4218.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4219](slots/rdf__4219.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__422](slots/rdf__422.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4220](slots/rdf__4220.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4221](slots/rdf__4221.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4222](slots/rdf__4222.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4223](slots/rdf__4223.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4224](slots/rdf__4224.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4225](slots/rdf__4225.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4226](slots/rdf__4226.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4227](slots/rdf__4227.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4228](slots/rdf__4228.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4229](slots/rdf__4229.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__423](slots/rdf__423.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4230](slots/rdf__4230.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4231](slots/rdf__4231.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4232](slots/rdf__4232.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4233](slots/rdf__4233.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4234](slots/rdf__4234.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4235](slots/rdf__4235.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4236](slots/rdf__4236.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4237](slots/rdf__4237.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4238](slots/rdf__4238.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4239](slots/rdf__4239.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__424](slots/rdf__424.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4240](slots/rdf__4240.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4241](slots/rdf__4241.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4242](slots/rdf__4242.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4243](slots/rdf__4243.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4244](slots/rdf__4244.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4245](slots/rdf__4245.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4246](slots/rdf__4246.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4247](slots/rdf__4247.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4248](slots/rdf__4248.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4249](slots/rdf__4249.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__425](slots/rdf__425.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4250](slots/rdf__4250.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4251](slots/rdf__4251.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4252](slots/rdf__4252.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4253](slots/rdf__4253.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4254](slots/rdf__4254.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4255](slots/rdf__4255.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4256](slots/rdf__4256.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4257](slots/rdf__4257.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4258](slots/rdf__4258.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4259](slots/rdf__4259.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__426](slots/rdf__426.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4260](slots/rdf__4260.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4261](slots/rdf__4261.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4262](slots/rdf__4262.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4263](slots/rdf__4263.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4264](slots/rdf__4264.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4265](slots/rdf__4265.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4266](slots/rdf__4266.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4267](slots/rdf__4267.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4268](slots/rdf__4268.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4269](slots/rdf__4269.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__427](slots/rdf__427.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4270](slots/rdf__4270.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4271](slots/rdf__4271.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4272](slots/rdf__4272.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4273](slots/rdf__4273.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4274](slots/rdf__4274.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4275](slots/rdf__4275.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4276](slots/rdf__4276.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4277](slots/rdf__4277.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4278](slots/rdf__4278.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4279](slots/rdf__4279.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__428](slots/rdf__428.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4280](slots/rdf__4280.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4281](slots/rdf__4281.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4282](slots/rdf__4282.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4283](slots/rdf__4283.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4284](slots/rdf__4284.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4285](slots/rdf__4285.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4286](slots/rdf__4286.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4287](slots/rdf__4287.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4288](slots/rdf__4288.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4289](slots/rdf__4289.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__429](slots/rdf__429.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4290](slots/rdf__4290.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4291](slots/rdf__4291.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4292](slots/rdf__4292.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4293](slots/rdf__4293.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4294](slots/rdf__4294.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4295](slots/rdf__4295.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4296](slots/rdf__4296.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4297](slots/rdf__4297.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4298](slots/rdf__4298.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4299](slots/rdf__4299.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__43](slots/rdf__43.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__430](slots/rdf__430.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4300](slots/rdf__4300.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4301](slots/rdf__4301.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4302](slots/rdf__4302.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4303](slots/rdf__4303.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4304](slots/rdf__4304.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4305](slots/rdf__4305.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4306](slots/rdf__4306.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4307](slots/rdf__4307.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4308](slots/rdf__4308.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4309](slots/rdf__4309.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__431](slots/rdf__431.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4310](slots/rdf__4310.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4311](slots/rdf__4311.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4312](slots/rdf__4312.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4313](slots/rdf__4313.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4314](slots/rdf__4314.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4315](slots/rdf__4315.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4316](slots/rdf__4316.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4317](slots/rdf__4317.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4318](slots/rdf__4318.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4319](slots/rdf__4319.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__432](slots/rdf__432.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4320](slots/rdf__4320.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4321](slots/rdf__4321.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4322](slots/rdf__4322.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4323](slots/rdf__4323.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4324](slots/rdf__4324.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4325](slots/rdf__4325.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4326](slots/rdf__4326.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4327](slots/rdf__4327.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4328](slots/rdf__4328.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4329](slots/rdf__4329.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__433](slots/rdf__433.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4330](slots/rdf__4330.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4331](slots/rdf__4331.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4332](slots/rdf__4332.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4333](slots/rdf__4333.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4334](slots/rdf__4334.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4335](slots/rdf__4335.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4336](slots/rdf__4336.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4337](slots/rdf__4337.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4338](slots/rdf__4338.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4339](slots/rdf__4339.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__434](slots/rdf__434.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4340](slots/rdf__4340.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4341](slots/rdf__4341.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4342](slots/rdf__4342.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4343](slots/rdf__4343.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4344](slots/rdf__4344.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4345](slots/rdf__4345.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4346](slots/rdf__4346.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4347](slots/rdf__4347.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4348](slots/rdf__4348.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4349](slots/rdf__4349.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__435](slots/rdf__435.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4350](slots/rdf__4350.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4351](slots/rdf__4351.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4352](slots/rdf__4352.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4353](slots/rdf__4353.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4354](slots/rdf__4354.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4355](slots/rdf__4355.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4356](slots/rdf__4356.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4357](slots/rdf__4357.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4358](slots/rdf__4358.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4359](slots/rdf__4359.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__436](slots/rdf__436.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4360](slots/rdf__4360.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4361](slots/rdf__4361.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4362](slots/rdf__4362.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4363](slots/rdf__4363.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4364](slots/rdf__4364.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4365](slots/rdf__4365.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4366](slots/rdf__4366.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4367](slots/rdf__4367.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4368](slots/rdf__4368.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4369](slots/rdf__4369.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__437](slots/rdf__437.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4370](slots/rdf__4370.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4371](slots/rdf__4371.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4372](slots/rdf__4372.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4373](slots/rdf__4373.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4374](slots/rdf__4374.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4375](slots/rdf__4375.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4376](slots/rdf__4376.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4377](slots/rdf__4377.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4378](slots/rdf__4378.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4379](slots/rdf__4379.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__438](slots/rdf__438.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4380](slots/rdf__4380.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4381](slots/rdf__4381.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4382](slots/rdf__4382.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4383](slots/rdf__4383.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4384](slots/rdf__4384.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4385](slots/rdf__4385.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4386](slots/rdf__4386.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4387](slots/rdf__4387.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4388](slots/rdf__4388.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4389](slots/rdf__4389.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__439](slots/rdf__439.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4390](slots/rdf__4390.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4391](slots/rdf__4391.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4392](slots/rdf__4392.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4393](slots/rdf__4393.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4394](slots/rdf__4394.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4395](slots/rdf__4395.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4396](slots/rdf__4396.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4397](slots/rdf__4397.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4398](slots/rdf__4398.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4399](slots/rdf__4399.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__44](slots/rdf__44.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__440](slots/rdf__440.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4400](slots/rdf__4400.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4401](slots/rdf__4401.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4402](slots/rdf__4402.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4403](slots/rdf__4403.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4404](slots/rdf__4404.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4405](slots/rdf__4405.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4406](slots/rdf__4406.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4407](slots/rdf__4407.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4408](slots/rdf__4408.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4409](slots/rdf__4409.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__441](slots/rdf__441.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4410](slots/rdf__4410.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4411](slots/rdf__4411.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4412](slots/rdf__4412.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4413](slots/rdf__4413.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4414](slots/rdf__4414.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4415](slots/rdf__4415.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4416](slots/rdf__4416.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4417](slots/rdf__4417.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4418](slots/rdf__4418.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4419](slots/rdf__4419.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__442](slots/rdf__442.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4420](slots/rdf__4420.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4421](slots/rdf__4421.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4422](slots/rdf__4422.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4423](slots/rdf__4423.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4424](slots/rdf__4424.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4425](slots/rdf__4425.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4426](slots/rdf__4426.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4427](slots/rdf__4427.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4428](slots/rdf__4428.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4429](slots/rdf__4429.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__443](slots/rdf__443.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4430](slots/rdf__4430.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4431](slots/rdf__4431.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4432](slots/rdf__4432.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4433](slots/rdf__4433.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4434](slots/rdf__4434.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4435](slots/rdf__4435.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4436](slots/rdf__4436.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4437](slots/rdf__4437.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4438](slots/rdf__4438.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4439](slots/rdf__4439.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__444](slots/rdf__444.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4440](slots/rdf__4440.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4441](slots/rdf__4441.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4442](slots/rdf__4442.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4443](slots/rdf__4443.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4444](slots/rdf__4444.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4445](slots/rdf__4445.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4446](slots/rdf__4446.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4447](slots/rdf__4447.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4448](slots/rdf__4448.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4449](slots/rdf__4449.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__445](slots/rdf__445.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4450](slots/rdf__4450.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4451](slots/rdf__4451.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4452](slots/rdf__4452.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4453](slots/rdf__4453.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4454](slots/rdf__4454.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4455](slots/rdf__4455.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4456](slots/rdf__4456.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4457](slots/rdf__4457.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4458](slots/rdf__4458.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4459](slots/rdf__4459.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__446](slots/rdf__446.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4460](slots/rdf__4460.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4461](slots/rdf__4461.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4462](slots/rdf__4462.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4463](slots/rdf__4463.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4464](slots/rdf__4464.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4465](slots/rdf__4465.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4466](slots/rdf__4466.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4467](slots/rdf__4467.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4468](slots/rdf__4468.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4469](slots/rdf__4469.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__447](slots/rdf__447.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4470](slots/rdf__4470.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4471](slots/rdf__4471.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4472](slots/rdf__4472.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4473](slots/rdf__4473.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4474](slots/rdf__4474.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4475](slots/rdf__4475.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4476](slots/rdf__4476.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4477](slots/rdf__4477.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4478](slots/rdf__4478.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4479](slots/rdf__4479.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__448](slots/rdf__448.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4480](slots/rdf__4480.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4481](slots/rdf__4481.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4482](slots/rdf__4482.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4483](slots/rdf__4483.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4484](slots/rdf__4484.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4485](slots/rdf__4485.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4486](slots/rdf__4486.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4487](slots/rdf__4487.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4488](slots/rdf__4488.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4489](slots/rdf__4489.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__449](slots/rdf__449.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4490](slots/rdf__4490.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4491](slots/rdf__4491.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4492](slots/rdf__4492.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4493](slots/rdf__4493.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4494](slots/rdf__4494.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4495](slots/rdf__4495.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4496](slots/rdf__4496.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4497](slots/rdf__4497.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4498](slots/rdf__4498.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4499](slots/rdf__4499.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__45](slots/rdf__45.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__450](slots/rdf__450.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4500](slots/rdf__4500.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4501](slots/rdf__4501.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4502](slots/rdf__4502.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4503](slots/rdf__4503.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4504](slots/rdf__4504.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4505](slots/rdf__4505.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4506](slots/rdf__4506.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4507](slots/rdf__4507.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4508](slots/rdf__4508.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4509](slots/rdf__4509.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__451](slots/rdf__451.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4510](slots/rdf__4510.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4511](slots/rdf__4511.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4512](slots/rdf__4512.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4513](slots/rdf__4513.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4514](slots/rdf__4514.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4515](slots/rdf__4515.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4516](slots/rdf__4516.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4517](slots/rdf__4517.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4518](slots/rdf__4518.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4519](slots/rdf__4519.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__452](slots/rdf__452.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4520](slots/rdf__4520.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4521](slots/rdf__4521.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4522](slots/rdf__4522.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4523](slots/rdf__4523.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4524](slots/rdf__4524.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4525](slots/rdf__4525.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4526](slots/rdf__4526.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4527](slots/rdf__4527.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4528](slots/rdf__4528.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4529](slots/rdf__4529.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__453](slots/rdf__453.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4530](slots/rdf__4530.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4531](slots/rdf__4531.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4532](slots/rdf__4532.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4533](slots/rdf__4533.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4534](slots/rdf__4534.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4535](slots/rdf__4535.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4536](slots/rdf__4536.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4537](slots/rdf__4537.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4538](slots/rdf__4538.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4539](slots/rdf__4539.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__454](slots/rdf__454.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4540](slots/rdf__4540.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4541](slots/rdf__4541.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4542](slots/rdf__4542.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4543](slots/rdf__4543.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4544](slots/rdf__4544.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4545](slots/rdf__4545.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4546](slots/rdf__4546.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4547](slots/rdf__4547.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4548](slots/rdf__4548.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4549](slots/rdf__4549.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__455](slots/rdf__455.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4550](slots/rdf__4550.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4551](slots/rdf__4551.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4552](slots/rdf__4552.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4553](slots/rdf__4553.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4554](slots/rdf__4554.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4555](slots/rdf__4555.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4556](slots/rdf__4556.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4557](slots/rdf__4557.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4558](slots/rdf__4558.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4559](slots/rdf__4559.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__456](slots/rdf__456.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4560](slots/rdf__4560.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4561](slots/rdf__4561.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4562](slots/rdf__4562.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4563](slots/rdf__4563.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4564](slots/rdf__4564.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4565](slots/rdf__4565.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4566](slots/rdf__4566.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4567](slots/rdf__4567.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4568](slots/rdf__4568.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4569](slots/rdf__4569.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__457](slots/rdf__457.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4570](slots/rdf__4570.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4571](slots/rdf__4571.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4572](slots/rdf__4572.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4573](slots/rdf__4573.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4574](slots/rdf__4574.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4575](slots/rdf__4575.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4576](slots/rdf__4576.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4577](slots/rdf__4577.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4578](slots/rdf__4578.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4579](slots/rdf__4579.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__458](slots/rdf__458.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4580](slots/rdf__4580.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4581](slots/rdf__4581.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4582](slots/rdf__4582.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4583](slots/rdf__4583.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4584](slots/rdf__4584.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4585](slots/rdf__4585.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4586](slots/rdf__4586.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4587](slots/rdf__4587.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4588](slots/rdf__4588.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4589](slots/rdf__4589.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__459](slots/rdf__459.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4590](slots/rdf__4590.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4591](slots/rdf__4591.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4592](slots/rdf__4592.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4593](slots/rdf__4593.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4594](slots/rdf__4594.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4595](slots/rdf__4595.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4596](slots/rdf__4596.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4597](slots/rdf__4597.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4598](slots/rdf__4598.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4599](slots/rdf__4599.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__46](slots/rdf__46.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__460](slots/rdf__460.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4600](slots/rdf__4600.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4601](slots/rdf__4601.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4602](slots/rdf__4602.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4603](slots/rdf__4603.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4604](slots/rdf__4604.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4605](slots/rdf__4605.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4606](slots/rdf__4606.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4607](slots/rdf__4607.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4608](slots/rdf__4608.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4609](slots/rdf__4609.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__461](slots/rdf__461.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4610](slots/rdf__4610.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4611](slots/rdf__4611.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4612](slots/rdf__4612.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4613](slots/rdf__4613.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4614](slots/rdf__4614.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4615](slots/rdf__4615.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4616](slots/rdf__4616.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4617](slots/rdf__4617.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4618](slots/rdf__4618.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4619](slots/rdf__4619.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__462](slots/rdf__462.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4620](slots/rdf__4620.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4621](slots/rdf__4621.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4622](slots/rdf__4622.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4623](slots/rdf__4623.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4624](slots/rdf__4624.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4625](slots/rdf__4625.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4626](slots/rdf__4626.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4627](slots/rdf__4627.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4628](slots/rdf__4628.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4629](slots/rdf__4629.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__463](slots/rdf__463.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4630](slots/rdf__4630.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4631](slots/rdf__4631.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4632](slots/rdf__4632.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4633](slots/rdf__4633.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4634](slots/rdf__4634.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4635](slots/rdf__4635.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4636](slots/rdf__4636.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4637](slots/rdf__4637.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4638](slots/rdf__4638.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4639](slots/rdf__4639.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__464](slots/rdf__464.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4640](slots/rdf__4640.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4641](slots/rdf__4641.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4642](slots/rdf__4642.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4643](slots/rdf__4643.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4644](slots/rdf__4644.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4645](slots/rdf__4645.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4646](slots/rdf__4646.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4647](slots/rdf__4647.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4648](slots/rdf__4648.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4649](slots/rdf__4649.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__465](slots/rdf__465.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4650](slots/rdf__4650.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4651](slots/rdf__4651.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4652](slots/rdf__4652.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4653](slots/rdf__4653.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4654](slots/rdf__4654.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4655](slots/rdf__4655.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4656](slots/rdf__4656.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4657](slots/rdf__4657.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4658](slots/rdf__4658.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4659](slots/rdf__4659.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__466](slots/rdf__466.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4660](slots/rdf__4660.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4661](slots/rdf__4661.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4662](slots/rdf__4662.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4663](slots/rdf__4663.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4664](slots/rdf__4664.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4665](slots/rdf__4665.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4666](slots/rdf__4666.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4667](slots/rdf__4667.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4668](slots/rdf__4668.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4669](slots/rdf__4669.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__467](slots/rdf__467.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4670](slots/rdf__4670.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4671](slots/rdf__4671.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4672](slots/rdf__4672.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4673](slots/rdf__4673.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4674](slots/rdf__4674.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4675](slots/rdf__4675.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4676](slots/rdf__4676.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4677](slots/rdf__4677.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4678](slots/rdf__4678.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4679](slots/rdf__4679.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__468](slots/rdf__468.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4680](slots/rdf__4680.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4681](slots/rdf__4681.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4682](slots/rdf__4682.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4683](slots/rdf__4683.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4684](slots/rdf__4684.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4685](slots/rdf__4685.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4686](slots/rdf__4686.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4687](slots/rdf__4687.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4688](slots/rdf__4688.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4689](slots/rdf__4689.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__469](slots/rdf__469.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4690](slots/rdf__4690.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4691](slots/rdf__4691.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4692](slots/rdf__4692.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4693](slots/rdf__4693.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4694](slots/rdf__4694.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4695](slots/rdf__4695.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4696](slots/rdf__4696.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4697](slots/rdf__4697.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4698](slots/rdf__4698.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4699](slots/rdf__4699.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__47](slots/rdf__47.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__470](slots/rdf__470.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4700](slots/rdf__4700.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4701](slots/rdf__4701.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4702](slots/rdf__4702.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4703](slots/rdf__4703.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4704](slots/rdf__4704.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4705](slots/rdf__4705.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4706](slots/rdf__4706.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4707](slots/rdf__4707.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4708](slots/rdf__4708.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4709](slots/rdf__4709.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__471](slots/rdf__471.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4710](slots/rdf__4710.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4711](slots/rdf__4711.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4712](slots/rdf__4712.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4713](slots/rdf__4713.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4714](slots/rdf__4714.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4715](slots/rdf__4715.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4716](slots/rdf__4716.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4717](slots/rdf__4717.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4718](slots/rdf__4718.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4719](slots/rdf__4719.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__472](slots/rdf__472.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4720](slots/rdf__4720.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4721](slots/rdf__4721.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4722](slots/rdf__4722.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4723](slots/rdf__4723.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4724](slots/rdf__4724.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4725](slots/rdf__4725.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4726](slots/rdf__4726.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4727](slots/rdf__4727.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4728](slots/rdf__4728.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4729](slots/rdf__4729.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__473](slots/rdf__473.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4730](slots/rdf__4730.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4731](slots/rdf__4731.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4732](slots/rdf__4732.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4733](slots/rdf__4733.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4734](slots/rdf__4734.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4735](slots/rdf__4735.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4736](slots/rdf__4736.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4737](slots/rdf__4737.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4738](slots/rdf__4738.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4739](slots/rdf__4739.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__474](slots/rdf__474.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4740](slots/rdf__4740.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4741](slots/rdf__4741.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4742](slots/rdf__4742.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4743](slots/rdf__4743.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4744](slots/rdf__4744.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4745](slots/rdf__4745.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4746](slots/rdf__4746.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4747](slots/rdf__4747.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4748](slots/rdf__4748.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4749](slots/rdf__4749.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__475](slots/rdf__475.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4750](slots/rdf__4750.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4751](slots/rdf__4751.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4752](slots/rdf__4752.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4753](slots/rdf__4753.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4754](slots/rdf__4754.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4755](slots/rdf__4755.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4756](slots/rdf__4756.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4757](slots/rdf__4757.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4758](slots/rdf__4758.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4759](slots/rdf__4759.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__476](slots/rdf__476.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4760](slots/rdf__4760.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4761](slots/rdf__4761.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4762](slots/rdf__4762.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4763](slots/rdf__4763.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4764](slots/rdf__4764.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4765](slots/rdf__4765.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4766](slots/rdf__4766.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4767](slots/rdf__4767.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4768](slots/rdf__4768.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4769](slots/rdf__4769.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__477](slots/rdf__477.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4770](slots/rdf__4770.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4771](slots/rdf__4771.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4772](slots/rdf__4772.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4773](slots/rdf__4773.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4774](slots/rdf__4774.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4775](slots/rdf__4775.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4776](slots/rdf__4776.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4777](slots/rdf__4777.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4778](slots/rdf__4778.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4779](slots/rdf__4779.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__478](slots/rdf__478.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4780](slots/rdf__4780.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4781](slots/rdf__4781.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4782](slots/rdf__4782.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4783](slots/rdf__4783.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4784](slots/rdf__4784.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4785](slots/rdf__4785.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4786](slots/rdf__4786.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4787](slots/rdf__4787.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4788](slots/rdf__4788.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4789](slots/rdf__4789.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__479](slots/rdf__479.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4790](slots/rdf__4790.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4791](slots/rdf__4791.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4792](slots/rdf__4792.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4793](slots/rdf__4793.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4794](slots/rdf__4794.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4795](slots/rdf__4795.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4796](slots/rdf__4796.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4797](slots/rdf__4797.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4798](slots/rdf__4798.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4799](slots/rdf__4799.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__48](slots/rdf__48.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__480](slots/rdf__480.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4800](slots/rdf__4800.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4801](slots/rdf__4801.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4802](slots/rdf__4802.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4803](slots/rdf__4803.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4804](slots/rdf__4804.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4805](slots/rdf__4805.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4806](slots/rdf__4806.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4807](slots/rdf__4807.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4808](slots/rdf__4808.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4809](slots/rdf__4809.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__481](slots/rdf__481.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4810](slots/rdf__4810.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4811](slots/rdf__4811.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4812](slots/rdf__4812.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4813](slots/rdf__4813.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4814](slots/rdf__4814.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4815](slots/rdf__4815.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4816](slots/rdf__4816.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4817](slots/rdf__4817.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4818](slots/rdf__4818.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4819](slots/rdf__4819.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__482](slots/rdf__482.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4820](slots/rdf__4820.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4821](slots/rdf__4821.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4822](slots/rdf__4822.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4823](slots/rdf__4823.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4824](slots/rdf__4824.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4825](slots/rdf__4825.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4826](slots/rdf__4826.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4827](slots/rdf__4827.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4828](slots/rdf__4828.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4829](slots/rdf__4829.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__483](slots/rdf__483.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4830](slots/rdf__4830.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4831](slots/rdf__4831.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4832](slots/rdf__4832.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4833](slots/rdf__4833.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4834](slots/rdf__4834.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4835](slots/rdf__4835.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4836](slots/rdf__4836.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4837](slots/rdf__4837.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4838](slots/rdf__4838.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4839](slots/rdf__4839.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__484](slots/rdf__484.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4840](slots/rdf__4840.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__4841](slots/rdf__4841.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__485](slots/rdf__485.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__486](slots/rdf__486.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__487](slots/rdf__487.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__488](slots/rdf__488.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__489](slots/rdf__489.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__49](slots/rdf__49.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__490](slots/rdf__490.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__491](slots/rdf__491.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__492](slots/rdf__492.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__493](slots/rdf__493.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__494](slots/rdf__494.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__495](slots/rdf__495.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__496](slots/rdf__496.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__497](slots/rdf__497.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__498](slots/rdf__498.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__499](slots/rdf__499.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__5](slots/rdf__5.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__50](slots/rdf__50.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__500](slots/rdf__500.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__501](slots/rdf__501.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__502](slots/rdf__502.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__503](slots/rdf__503.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__504](slots/rdf__504.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__505](slots/rdf__505.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__506](slots/rdf__506.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__507](slots/rdf__507.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__508](slots/rdf__508.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__509](slots/rdf__509.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__51](slots/rdf__51.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__510](slots/rdf__510.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__511](slots/rdf__511.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__512](slots/rdf__512.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__513](slots/rdf__513.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__514](slots/rdf__514.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__515](slots/rdf__515.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__516](slots/rdf__516.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__517](slots/rdf__517.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__518](slots/rdf__518.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__519](slots/rdf__519.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__52](slots/rdf__52.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__520](slots/rdf__520.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__521](slots/rdf__521.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__522](slots/rdf__522.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__523](slots/rdf__523.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__524](slots/rdf__524.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__525](slots/rdf__525.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__526](slots/rdf__526.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__527](slots/rdf__527.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__528](slots/rdf__528.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__529](slots/rdf__529.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__53](slots/rdf__53.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__530](slots/rdf__530.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__531](slots/rdf__531.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__532](slots/rdf__532.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__533](slots/rdf__533.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__534](slots/rdf__534.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__535](slots/rdf__535.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__536](slots/rdf__536.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__537](slots/rdf__537.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__538](slots/rdf__538.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__539](slots/rdf__539.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__54](slots/rdf__54.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__540](slots/rdf__540.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__541](slots/rdf__541.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__542](slots/rdf__542.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__543](slots/rdf__543.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__544](slots/rdf__544.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__545](slots/rdf__545.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__546](slots/rdf__546.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__547](slots/rdf__547.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__548](slots/rdf__548.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__549](slots/rdf__549.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__55](slots/rdf__55.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__550](slots/rdf__550.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__551](slots/rdf__551.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__552](slots/rdf__552.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__553](slots/rdf__553.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__554](slots/rdf__554.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__555](slots/rdf__555.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__556](slots/rdf__556.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__557](slots/rdf__557.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__558](slots/rdf__558.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__559](slots/rdf__559.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__56](slots/rdf__56.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__560](slots/rdf__560.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__561](slots/rdf__561.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__562](slots/rdf__562.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__563](slots/rdf__563.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__564](slots/rdf__564.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__565](slots/rdf__565.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__566](slots/rdf__566.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__567](slots/rdf__567.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__568](slots/rdf__568.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__569](slots/rdf__569.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__57](slots/rdf__57.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__570](slots/rdf__570.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__571](slots/rdf__571.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__572](slots/rdf__572.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__573](slots/rdf__573.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__574](slots/rdf__574.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__575](slots/rdf__575.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__576](slots/rdf__576.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__577](slots/rdf__577.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__578](slots/rdf__578.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__579](slots/rdf__579.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__58](slots/rdf__58.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__580](slots/rdf__580.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__581](slots/rdf__581.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__582](slots/rdf__582.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__583](slots/rdf__583.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__584](slots/rdf__584.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__585](slots/rdf__585.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__586](slots/rdf__586.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__587](slots/rdf__587.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__588](slots/rdf__588.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__589](slots/rdf__589.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__59](slots/rdf__59.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__590](slots/rdf__590.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__591](slots/rdf__591.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__592](slots/rdf__592.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__593](slots/rdf__593.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__594](slots/rdf__594.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__595](slots/rdf__595.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__596](slots/rdf__596.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__597](slots/rdf__597.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__598](slots/rdf__598.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__599](slots/rdf__599.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__6](slots/rdf__6.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__60](slots/rdf__60.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__600](slots/rdf__600.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__601](slots/rdf__601.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__602](slots/rdf__602.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__603](slots/rdf__603.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__604](slots/rdf__604.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__605](slots/rdf__605.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__606](slots/rdf__606.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__607](slots/rdf__607.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__608](slots/rdf__608.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__609](slots/rdf__609.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__61](slots/rdf__61.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__610](slots/rdf__610.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__611](slots/rdf__611.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__612](slots/rdf__612.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__613](slots/rdf__613.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__614](slots/rdf__614.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__615](slots/rdf__615.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__616](slots/rdf__616.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__617](slots/rdf__617.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__618](slots/rdf__618.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__619](slots/rdf__619.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__62](slots/rdf__62.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__620](slots/rdf__620.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__621](slots/rdf__621.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__622](slots/rdf__622.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__623](slots/rdf__623.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__624](slots/rdf__624.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__625](slots/rdf__625.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__626](slots/rdf__626.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__627](slots/rdf__627.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__628](slots/rdf__628.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__629](slots/rdf__629.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__63](slots/rdf__63.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__630](slots/rdf__630.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__631](slots/rdf__631.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__632](slots/rdf__632.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__633](slots/rdf__633.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__634](slots/rdf__634.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__635](slots/rdf__635.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__636](slots/rdf__636.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__637](slots/rdf__637.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__638](slots/rdf__638.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__639](slots/rdf__639.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__64](slots/rdf__64.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__640](slots/rdf__640.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__641](slots/rdf__641.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__642](slots/rdf__642.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__643](slots/rdf__643.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__644](slots/rdf__644.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__645](slots/rdf__645.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__646](slots/rdf__646.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__647](slots/rdf__647.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__648](slots/rdf__648.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__649](slots/rdf__649.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__65](slots/rdf__65.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__650](slots/rdf__650.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__651](slots/rdf__651.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__652](slots/rdf__652.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__653](slots/rdf__653.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__654](slots/rdf__654.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__655](slots/rdf__655.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__656](slots/rdf__656.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__657](slots/rdf__657.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__658](slots/rdf__658.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__659](slots/rdf__659.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__66](slots/rdf__66.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__660](slots/rdf__660.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__661](slots/rdf__661.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__662](slots/rdf__662.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__663](slots/rdf__663.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__664](slots/rdf__664.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__665](slots/rdf__665.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__666](slots/rdf__666.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__667](slots/rdf__667.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__668](slots/rdf__668.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__669](slots/rdf__669.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__67](slots/rdf__67.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__670](slots/rdf__670.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__671](slots/rdf__671.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__672](slots/rdf__672.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__673](slots/rdf__673.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__674](slots/rdf__674.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__675](slots/rdf__675.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__676](slots/rdf__676.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__677](slots/rdf__677.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__678](slots/rdf__678.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__679](slots/rdf__679.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__68](slots/rdf__68.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__680](slots/rdf__680.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__681](slots/rdf__681.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__682](slots/rdf__682.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__683](slots/rdf__683.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__684](slots/rdf__684.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__685](slots/rdf__685.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__686](slots/rdf__686.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__687](slots/rdf__687.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__688](slots/rdf__688.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__689](slots/rdf__689.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__69](slots/rdf__69.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__690](slots/rdf__690.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__691](slots/rdf__691.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__692](slots/rdf__692.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__693](slots/rdf__693.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__694](slots/rdf__694.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__695](slots/rdf__695.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__696](slots/rdf__696.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__697](slots/rdf__697.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__698](slots/rdf__698.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__699](slots/rdf__699.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__7](slots/rdf__7.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__70](slots/rdf__70.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__700](slots/rdf__700.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__701](slots/rdf__701.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__702](slots/rdf__702.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__703](slots/rdf__703.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__704](slots/rdf__704.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__705](slots/rdf__705.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__706](slots/rdf__706.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__707](slots/rdf__707.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__708](slots/rdf__708.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__709](slots/rdf__709.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__71](slots/rdf__71.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__710](slots/rdf__710.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__711](slots/rdf__711.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__712](slots/rdf__712.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__713](slots/rdf__713.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__714](slots/rdf__714.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__715](slots/rdf__715.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__716](slots/rdf__716.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__717](slots/rdf__717.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__718](slots/rdf__718.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__719](slots/rdf__719.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__72](slots/rdf__72.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__720](slots/rdf__720.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__721](slots/rdf__721.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__722](slots/rdf__722.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__723](slots/rdf__723.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__724](slots/rdf__724.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__725](slots/rdf__725.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__726](slots/rdf__726.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__727](slots/rdf__727.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__728](slots/rdf__728.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__729](slots/rdf__729.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__73](slots/rdf__73.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__730](slots/rdf__730.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__731](slots/rdf__731.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__732](slots/rdf__732.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__733](slots/rdf__733.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__734](slots/rdf__734.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__735](slots/rdf__735.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__736](slots/rdf__736.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__737](slots/rdf__737.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__738](slots/rdf__738.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__739](slots/rdf__739.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__74](slots/rdf__74.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__740](slots/rdf__740.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__741](slots/rdf__741.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__742](slots/rdf__742.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__743](slots/rdf__743.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__744](slots/rdf__744.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__745](slots/rdf__745.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__746](slots/rdf__746.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__747](slots/rdf__747.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__748](slots/rdf__748.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__749](slots/rdf__749.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__75](slots/rdf__75.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__750](slots/rdf__750.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__751](slots/rdf__751.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__752](slots/rdf__752.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__753](slots/rdf__753.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__754](slots/rdf__754.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__755](slots/rdf__755.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__756](slots/rdf__756.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__757](slots/rdf__757.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__758](slots/rdf__758.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__759](slots/rdf__759.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__76](slots/rdf__76.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__760](slots/rdf__760.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__761](slots/rdf__761.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__762](slots/rdf__762.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__763](slots/rdf__763.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__764](slots/rdf__764.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__765](slots/rdf__765.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__766](slots/rdf__766.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__767](slots/rdf__767.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__768](slots/rdf__768.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__769](slots/rdf__769.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__77](slots/rdf__77.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__770](slots/rdf__770.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__771](slots/rdf__771.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__772](slots/rdf__772.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__773](slots/rdf__773.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__774](slots/rdf__774.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__775](slots/rdf__775.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__776](slots/rdf__776.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__777](slots/rdf__777.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__778](slots/rdf__778.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__779](slots/rdf__779.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__78](slots/rdf__78.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__780](slots/rdf__780.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__781](slots/rdf__781.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__782](slots/rdf__782.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__783](slots/rdf__783.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__784](slots/rdf__784.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__785](slots/rdf__785.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__786](slots/rdf__786.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__787](slots/rdf__787.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__788](slots/rdf__788.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__789](slots/rdf__789.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__79](slots/rdf__79.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__790](slots/rdf__790.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__791](slots/rdf__791.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__792](slots/rdf__792.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__793](slots/rdf__793.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__794](slots/rdf__794.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__795](slots/rdf__795.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__796](slots/rdf__796.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__797](slots/rdf__797.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__798](slots/rdf__798.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__799](slots/rdf__799.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__8](slots/rdf__8.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__80](slots/rdf__80.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__800](slots/rdf__800.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__801](slots/rdf__801.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__802](slots/rdf__802.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__803](slots/rdf__803.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__804](slots/rdf__804.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__805](slots/rdf__805.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__806](slots/rdf__806.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__807](slots/rdf__807.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__808](slots/rdf__808.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__809](slots/rdf__809.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__81](slots/rdf__81.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__810](slots/rdf__810.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__811](slots/rdf__811.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__812](slots/rdf__812.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__813](slots/rdf__813.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__814](slots/rdf__814.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__815](slots/rdf__815.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__816](slots/rdf__816.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__817](slots/rdf__817.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__818](slots/rdf__818.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__819](slots/rdf__819.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__82](slots/rdf__82.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__820](slots/rdf__820.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__821](slots/rdf__821.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__822](slots/rdf__822.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__823](slots/rdf__823.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__824](slots/rdf__824.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__825](slots/rdf__825.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__826](slots/rdf__826.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__827](slots/rdf__827.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__828](slots/rdf__828.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__829](slots/rdf__829.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__83](slots/rdf__83.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__830](slots/rdf__830.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__831](slots/rdf__831.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__832](slots/rdf__832.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__833](slots/rdf__833.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__834](slots/rdf__834.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__835](slots/rdf__835.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__836](slots/rdf__836.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__837](slots/rdf__837.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__838](slots/rdf__838.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__839](slots/rdf__839.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__84](slots/rdf__84.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__840](slots/rdf__840.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__841](slots/rdf__841.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__842](slots/rdf__842.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__843](slots/rdf__843.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__844](slots/rdf__844.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__845](slots/rdf__845.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__846](slots/rdf__846.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__847](slots/rdf__847.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__848](slots/rdf__848.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__849](slots/rdf__849.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__85](slots/rdf__85.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__850](slots/rdf__850.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__851](slots/rdf__851.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__852](slots/rdf__852.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__853](slots/rdf__853.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__854](slots/rdf__854.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__855](slots/rdf__855.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__856](slots/rdf__856.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__857](slots/rdf__857.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__858](slots/rdf__858.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__859](slots/rdf__859.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__86](slots/rdf__86.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__860](slots/rdf__860.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__861](slots/rdf__861.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__862](slots/rdf__862.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__863](slots/rdf__863.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__864](slots/rdf__864.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__865](slots/rdf__865.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__866](slots/rdf__866.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__867](slots/rdf__867.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__868](slots/rdf__868.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__869](slots/rdf__869.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__87](slots/rdf__87.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__870](slots/rdf__870.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__871](slots/rdf__871.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__872](slots/rdf__872.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__873](slots/rdf__873.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__874](slots/rdf__874.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__875](slots/rdf__875.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__876](slots/rdf__876.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__877](slots/rdf__877.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__878](slots/rdf__878.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__879](slots/rdf__879.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__88](slots/rdf__88.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__880](slots/rdf__880.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__881](slots/rdf__881.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__882](slots/rdf__882.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__883](slots/rdf__883.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__884](slots/rdf__884.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__885](slots/rdf__885.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__886](slots/rdf__886.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__887](slots/rdf__887.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__888](slots/rdf__888.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__889](slots/rdf__889.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__89](slots/rdf__89.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__890](slots/rdf__890.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__891](slots/rdf__891.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__892](slots/rdf__892.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__893](slots/rdf__893.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__894](slots/rdf__894.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__895](slots/rdf__895.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__896](slots/rdf__896.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__897](slots/rdf__897.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__898](slots/rdf__898.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__899](slots/rdf__899.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__9](slots/rdf__9.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__90](slots/rdf__90.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__900](slots/rdf__900.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__901](slots/rdf__901.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__902](slots/rdf__902.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__903](slots/rdf__903.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__904](slots/rdf__904.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__905](slots/rdf__905.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__906](slots/rdf__906.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__907](slots/rdf__907.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__908](slots/rdf__908.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__909](slots/rdf__909.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__91](slots/rdf__91.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__910](slots/rdf__910.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__911](slots/rdf__911.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__912](slots/rdf__912.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__913](slots/rdf__913.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__914](slots/rdf__914.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__915](slots/rdf__915.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__916](slots/rdf__916.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__917](slots/rdf__917.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__918](slots/rdf__918.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__919](slots/rdf__919.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__92](slots/rdf__92.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__920](slots/rdf__920.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__921](slots/rdf__921.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__922](slots/rdf__922.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__923](slots/rdf__923.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__924](slots/rdf__924.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__925](slots/rdf__925.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__926](slots/rdf__926.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__927](slots/rdf__927.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__928](slots/rdf__928.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__929](slots/rdf__929.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__93](slots/rdf__93.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__930](slots/rdf__930.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__931](slots/rdf__931.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__932](slots/rdf__932.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__933](slots/rdf__933.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__934](slots/rdf__934.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__935](slots/rdf__935.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__936](slots/rdf__936.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__937](slots/rdf__937.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__938](slots/rdf__938.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__939](slots/rdf__939.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__94](slots/rdf__94.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__940](slots/rdf__940.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__941](slots/rdf__941.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__942](slots/rdf__942.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__943](slots/rdf__943.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__944](slots/rdf__944.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__945](slots/rdf__945.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__946](slots/rdf__946.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__947](slots/rdf__947.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__948](slots/rdf__948.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__949](slots/rdf__949.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__95](slots/rdf__95.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__950](slots/rdf__950.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__951](slots/rdf__951.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__952](slots/rdf__952.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__953](slots/rdf__953.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__954](slots/rdf__954.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__955](slots/rdf__955.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__956](slots/rdf__956.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__957](slots/rdf__957.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__958](slots/rdf__958.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__959](slots/rdf__959.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__96](slots/rdf__96.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__960](slots/rdf__960.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__961](slots/rdf__961.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__962](slots/rdf__962.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__963](slots/rdf__963.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__964](slots/rdf__964.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__965](slots/rdf__965.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__966](slots/rdf__966.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__967](slots/rdf__967.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__968](slots/rdf__968.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__969](slots/rdf__969.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__97](slots/rdf__97.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__970](slots/rdf__970.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__971](slots/rdf__971.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__972](slots/rdf__972.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__973](slots/rdf__973.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__974](slots/rdf__974.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__975](slots/rdf__975.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__976](slots/rdf__976.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__977](slots/rdf__977.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__978](slots/rdf__978.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__979](slots/rdf__979.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__98](slots/rdf__98.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__980](slots/rdf__980.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__981](slots/rdf__981.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__982](slots/rdf__982.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__983](slots/rdf__983.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__984](slots/rdf__984.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__985](slots/rdf__985.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__986](slots/rdf__986.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__987](slots/rdf__987.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__988](slots/rdf__988.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__989](slots/rdf__989.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__99](slots/rdf__99.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__990](slots/rdf__990.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__991](slots/rdf__991.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__992](slots/rdf__992.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__993](slots/rdf__993.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__994](slots/rdf__994.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__995](slots/rdf__995.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__996](slots/rdf__996.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__997](slots/rdf__997.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__998](slots/rdf__998.md) | TODO -- tell the world what this slot (predicate) describes |
| [rdf__999](slots/rdf__999.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_assignedToDefendant](slots/scales_assignedToDefendant.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasAddress](slots/scales_hasAddress.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasAgent](slots/scales_hasAgent.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasAgentType](slots/scales_hasAgentType.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasCause](slots/scales_hasCause.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasCharge](slots/scales_hasCharge.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasContents](slots/scales_hasContents.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasDocketTable](slots/scales_hasDocketTable.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasExtraInfo](slots/scales_hasExtraInfo.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasFilingDate](slots/scales_hasFilingDate.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasFJCNodeID](slots/scales_hasFJCNodeID.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbAmtrec](slots/scales_hasIdbAmtrec.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbAppcd](slots/scales_hasIdbAppcd.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbAppdate](slots/scales_hasIdbAppdate.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbArbit](slots/scales_hasIdbArbit.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbCaslgky](slots/scales_hasIdbCaslgky.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbCircuit](slots/scales_hasIdbCircuit.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbClassact](slots/scales_hasIdbClassact.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbCounty](slots/scales_hasIdbCounty.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbCtdef](slots/scales_hasIdbCtdef.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbCtfil](slots/scales_hasIdbCtfil.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbCtfilr](slots/scales_hasIdbCtfilr.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbCtfiltrn](slots/scales_hasIdbCtfiltrn.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbCtfilwor](slots/scales_hasIdbCtfilwor.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbCtpn](slots/scales_hasIdbCtpn.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbCtpnwof](slots/scales_hasIdbCtpnwof.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbCttr](slots/scales_hasIdbCttr.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbCttrr](slots/scales_hasIdbCttrr.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbCttrtrn](slots/scales_hasIdbCttrtrn.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbCttrwor](slots/scales_hasIdbCttrwor.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbD2foffcd1](slots/scales_hasIdbD2foffcd1.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbD2foffcd2](slots/scales_hasIdbD2foffcd2.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbD2foffcd3](slots/scales_hasIdbD2foffcd3.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbD2foffcd4](slots/scales_hasIdbD2foffcd4.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbD2foffcd5](slots/scales_hasIdbD2foffcd5.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbD2toffcd1](slots/scales_hasIdbD2toffcd1.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbD2toffcd2](slots/scales_hasIdbD2toffcd2.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbD2toffcd3](slots/scales_hasIdbD2toffcd3.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbD2toffcd4](slots/scales_hasIdbD2toffcd4.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbD2toffcd5](slots/scales_hasIdbD2toffcd5.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbDef](slots/scales_hasIdbDef.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbDeflgky](slots/scales_hasIdbDeflgky.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbDefno](slots/scales_hasIdbDefno.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbDemanded](slots/scales_hasIdbDemanded.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbDisp](slots/scales_hasIdbDisp.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbDisp1](slots/scales_hasIdbDisp1.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbDisp2](slots/scales_hasIdbDisp2.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbDisp3](slots/scales_hasIdbDisp3.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbDisp4](slots/scales_hasIdbDisp4.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbDisp5](slots/scales_hasIdbDisp5.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbDispdate](slots/scales_hasIdbDispdate.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbDistrict](slots/scales_hasIdbDistrict.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbDjoined](slots/scales_hasIdbDjoined.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbDocket](slots/scales_hasIdbDocket.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFcounsel](slots/scales_hasIdbFcounsel.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFdateuse](slots/scales_hasIdbFdateuse.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFgenddate](slots/scales_hasIdbFgenddate.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFgstrtdate](slots/scales_hasIdbFgstrtdate.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFiledate](slots/scales_hasIdbFiledate.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFineamt1](slots/scales_hasIdbFineamt1.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFineamt2](slots/scales_hasIdbFineamt2.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFineamt3](slots/scales_hasIdbFineamt3.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFineamt4](slots/scales_hasIdbFineamt4.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFineamt5](slots/scales_hasIdbFineamt5.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFinetot](slots/scales_hasIdbFinetot.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFiscalyr](slots/scales_hasIdbFiscalyr.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFoffcd1](slots/scales_hasIdbFoffcd1.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFoffcd2](slots/scales_hasIdbFoffcd2.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFoffcd3](slots/scales_hasIdbFoffcd3.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFoffcd4](slots/scales_hasIdbFoffcd4.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFoffcd5](slots/scales_hasIdbFoffcd5.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFofflvl1](slots/scales_hasIdbFofflvl1.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFofflvl2](slots/scales_hasIdbFofflvl2.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFofflvl3](slots/scales_hasIdbFofflvl3.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFofflvl4](slots/scales_hasIdbFofflvl4.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFofflvl5](slots/scales_hasIdbFofflvl5.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFsev1](slots/scales_hasIdbFsev1.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFsev2](slots/scales_hasIdbFsev2.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFsev3](slots/scales_hasIdbFsev3.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFsev4](slots/scales_hasIdbFsev4.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFsev5](slots/scales_hasIdbFsev5.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFtitle1](slots/scales_hasIdbFtitle1.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFtitle2](slots/scales_hasIdbFtitle2.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFtitle3](slots/scales_hasIdbFtitle3.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFtitle4](slots/scales_hasIdbFtitle4.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFtitle5](slots/scales_hasIdbFtitle5.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbFugstat](slots/scales_hasIdbFugstat.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbIfp](slots/scales_hasIdbIfp.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbInt1](slots/scales_hasIdbInt1.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbInt2](slots/scales_hasIdbInt2.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbInt3](slots/scales_hasIdbInt3.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbIs_stub](slots/scales_hasIdbIs_stub.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbJudgment](slots/scales_hasIdbJudgment.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbJuris](slots/scales_hasIdbJuris.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbJury](slots/scales_hasIdbJury.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbLoaddate](slots/scales_hasIdbLoaddate.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbMagdef](slots/scales_hasIdbMagdef.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbMagdock](slots/scales_hasIdbMagdock.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbMdldock](slots/scales_hasIdbMdldock.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbNoj](slots/scales_hasIdbNoj.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbNos](slots/scales_hasIdbNos.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbOffice](slots/scales_hasIdbOffice.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbOrigin](slots/scales_hasIdbOrigin.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbPlt](slots/scales_hasIdbPlt.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbPretrial](slots/scales_hasIdbPretrial.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbPriscd1](slots/scales_hasIdbPriscd1.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbPriscd2](slots/scales_hasIdbPriscd2.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbPriscd3](slots/scales_hasIdbPriscd3.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbPriscd4](slots/scales_hasIdbPriscd4.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbPriscd5](slots/scales_hasIdbPriscd5.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbPristim1](slots/scales_hasIdbPristim1.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbPristim2](slots/scales_hasIdbPristim2.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbPristim3](slots/scales_hasIdbPristim3.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbPristim4](slots/scales_hasIdbPristim4.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbPristim5](slots/scales_hasIdbPristim5.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbPristot](slots/scales_hasIdbPristot.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbProbcd1](slots/scales_hasIdbProbcd1.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbProbcd2](slots/scales_hasIdbProbcd2.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbProbcd3](slots/scales_hasIdbProbcd3.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbProbcd4](slots/scales_hasIdbProbcd4.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbProbcd5](slots/scales_hasIdbProbcd5.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbProbmon1](slots/scales_hasIdbProbmon1.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbProbmon2](slots/scales_hasIdbProbmon2.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbProbmon3](slots/scales_hasIdbProbmon3.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbProbmon4](slots/scales_hasIdbProbmon4.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbProbmon5](slots/scales_hasIdbProbmon5.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbProbtot](slots/scales_hasIdbProbtot.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbProccd](slots/scales_hasIdbProccd.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbProcdate](slots/scales_hasIdbProcdate.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbProcprog](slots/scales_hasIdbProcprog.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbProse](slots/scales_hasIdbProse.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbReopseq](slots/scales_hasIdbReopseq.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbResidenc](slots/scales_hasIdbResidenc.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbSection](slots/scales_hasIdbSection.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbSentdate](slots/scales_hasIdbSentdate.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbStatuscd](slots/scales_hasIdbStatuscd.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbSubsect](slots/scales_hasIdbSubsect.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbSupvrel1](slots/scales_hasIdbSupvrel1.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbSupvrel2](slots/scales_hasIdbSupvrel2.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbSupvrel3](slots/scales_hasIdbSupvrel3.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbSupvrel4](slots/scales_hasIdbSupvrel4.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbSupvrel5](slots/scales_hasIdbSupvrel5.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTapeyear](slots/scales_hasIdbTapeyear.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTcounsel](slots/scales_hasIdbTcounsel.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTdateuse](slots/scales_hasIdbTdateuse.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTermdate](slots/scales_hasIdbTermdate.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTermoff](slots/scales_hasIdbTermoff.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTitl](slots/scales_hasIdbTitl.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbToffcd1](slots/scales_hasIdbToffcd1.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbToffcd2](slots/scales_hasIdbToffcd2.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbToffcd3](slots/scales_hasIdbToffcd3.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbToffcd4](slots/scales_hasIdbToffcd4.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbToffcd5](slots/scales_hasIdbToffcd5.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTofflvl1](slots/scales_hasIdbTofflvl1.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTofflvl2](slots/scales_hasIdbTofflvl2.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTofflvl3](slots/scales_hasIdbTofflvl3.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTofflvl4](slots/scales_hasIdbTofflvl4.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTofflvl5](slots/scales_hasIdbTofflvl5.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTrandef](slots/scales_hasIdbTrandef.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTrandist](slots/scales_hasIdbTrandist.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTrandock](slots/scales_hasIdbTrandock.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTranoff](slots/scales_hasIdbTranoff.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTransdat](slots/scales_hasIdbTransdat.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTransdoc](slots/scales_hasIdbTransdoc.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTransoff](slots/scales_hasIdbTransoff.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTransorg](slots/scales_hasIdbTransorg.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTrclact](slots/scales_hasIdbTrclact.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTrialend](slots/scales_hasIdbTrialend.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTribegan](slots/scales_hasIdbTribegan.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTrmarb](slots/scales_hasIdbTrmarb.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTsev1](slots/scales_hasIdbTsev1.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTsev2](slots/scales_hasIdbTsev2.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTsev3](slots/scales_hasIdbTsev3.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTsev4](slots/scales_hasIdbTsev4.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTsev5](slots/scales_hasIdbTsev5.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTtitle1](slots/scales_hasIdbTtitle1.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTtitle2](slots/scales_hasIdbTtitle2.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTtitle3](slots/scales_hasIdbTtitle3.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTtitle4](slots/scales_hasIdbTtitle4.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTtitle5](slots/scales_hasIdbTtitle5.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTypemag](slots/scales_hasIdbTypemag.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTypereg](slots/scales_hasIdbTypereg.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbTypetrn](slots/scales_hasIdbTypetrn.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbUpdate](slots/scales_hasIdbUpdate.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIdbVer](slots/scales_hasIdbVer.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIfpJudgeAttribution](slots/scales_hasIfpJudgeAttribution.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasIfpLabel](slots/scales_hasIfpLabel.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasJudgeEntityType](slots/scales_hasJudgeEntityType.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasJurisdiction](slots/scales_hasJurisdiction.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasMemberCase](slots/scales_hasMemberCase.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasName](slots/scales_hasName.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasNatureSuit](slots/scales_hasNatureSuit.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasOntologyLabel](slots/scales_hasOntologyLabel.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasPacerID](slots/scales_hasPacerID.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasReference](slots/scales_hasReference.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasReferenceInExtraInfo](slots/scales_hasReferenceInExtraInfo.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasRelatedCase](slots/scales_hasRelatedCase.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasRepresentation](slots/scales_hasRepresentation.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasRoleInCase](slots/scales_hasRoleInCase.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasStatus](slots/scales_hasStatus.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasTerminatingDate](slots/scales_hasTerminatingDate.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_hasUVAJudgeDirID](slots/scales_hasUVAJudgeDirID.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_isInCircuit](slots/scales_isInCircuit.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_isInCourt](slots/scales_isInCourt.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_isInCourtSystem](slots/scales_isInCourtSystem.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_isInFirm](slots/scales_isInFirm.md) | TODO -- tell the world what this slot (predicate) describes |
| [scales_isInstanceOfEntity](slots/scales_isInstanceOfEntity.md) | TODO -- tell the world what this slot (predicate) describes |


## Enumerations

| Enumeration | Description |
| --- | --- |


## Types

| Type | Description |
| --- | --- |


## Subsets

| Subset | Description |
| --- | --- |
