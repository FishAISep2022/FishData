# Samansette driftsdata for fangst (setel) og fartøy 
Av Randi S. Sletten Hopland, Tove Aasheim Per 14.01.2022

## Innhald \\

Datasettet er eit samansett datasett som inneheld fangstdata frå Fiskeridirektoratets landings- og sluttseddelregister og fartøydata frå Fiskeridirektoratets merkeregister. Datasettet inkluderer all fangst av norske fartøy og fangst av utanlandske fartøy som er landa i Norge. Tidsserien startar på år 2000. Datasettet inneheld driftsdata. Driftsdata gjennomgår same kvalitetssikring som data for offisiell statistikk. Medan data for offisiell statistikk på eit tidspunkt vert låst for vidare endringar vil driftsdata «leve» vidare og fortsatt kunne oppdaterast og verte endra. Driftsdata vil i hovudsak nyttast til forvaltnings- og kontrollformål. \\
Datasettet inneheld informasjon om all fiske og fangst i sjøen tatt av norskregistrerte fiskefartøy samt fangst av utanlandske fartøy som er landa i Noreg. Datasettet skal også innehalde informasjon om forskingsfangst, skulefangst samt all førstehandsomsetning av fritidsfiske. \\
Datasettet inneheld både sluttsetlar og landingssetlar. I tabellen vert landingssetlane nedskrivne etter kvart som fangsten vert omsett og sluttsetelført. Fleirtalet av landingssetlane vil difor etter ei tid stå med 0 i kvantum. Eventuelle restkvanta som vert ståande att på landingssetlane vil vere fangst som av ulike årsaker ikkje har vorte omsett. \\
For åra 2000-2014 er tal for sjøfiske av laks og sjøaure er lagt inn i tabellen på basis av kommunestatistikk for desse artane som vi mottok frå SSB. Desse tala inneheldt berre kvantum og ikkje verdi. \\

## Metode for kopling av fangstdata og fartøydata \\

Fangstdata og fartøydata er kopla saman ved bruk av siste fangstdato og fartøyet sine gyldighetsperiodar; siste fangstdato må vere i ein periode der fartøyet er gyldig for å bli kopla mot fartøyet. Dersom fangsten ikkje har ein siste fangstdato som ligg i ein gyldig periode for fartøyet, vil denne fangsten ikkje bli knytta mot ein Fartøy ID og heller ikkje mot fartøykarakteristika. Fangst som hamnar utanfor gyldighetsperiodar til fartøya vil difor hamne på "uoppgitt fangst" med omsyn til alle fartøyvariablar (t.d. fartøykommune, største lengde, bruttotonnasje m.m.). Registreringsmerke og radiokallesignal er derimot henta frå setel, og vil difor vere med uavhengig av treff i fartøydata. \\

## Eining \\
Eininga er dokument (sluttsetel/landingssetel). Eininga vert repetert for kvar varelinje. Ved landing/sal vert det fylt ut ein landingssetel/sluttsetel som inneheldt dei sentrale opplysningar ved landinga/salet. Etter Fiskesalslagslova er det vidare krav om at viltlevande marine ressursar i første hand skal omsettast gjennom eller med godkjenning av eit fiskesalslag. Fiskesalslaga leverer desse opplysningane vidare til Fiskeridirektoratet i elektronisk form, og det er desse dokumenta som dannar hovudgrunnlaget for innhaldet i datasettet.

## Datakvalitet \\

Fangst 

Datasettet er komplett frå og med år 2000, men ein kan finna kvalitetsavvik på feltnivå. Det har vore ei utviding undervegs, der både nye felt og nye kodar for innhaldet har kome til. Alle kodelister vert vedlikehalde fortløpande og nye kodar vert etablert ved behov. \\
Sluttsetlar er med i datasettet for alle år. Implementering av landingssetlar er vorten gjort over tid. Vi starta å få inn landingssetlar frå Norges Råfisklag heilt i slutten av 2002, men det er ikkje komplett dei første åra. Sunnmøre og Romsdal Fiskesalslag starta vi å ta inn i 2007, også nokre dokument gjeldande for 2006 og nokre få for 2005 kom då inn. Vest-Norges Fiskesalslag og Norges Sildesalgslag starta vi å ta inn i 2011, då også nokre få dokument gjeldande for 2010. Skagerakfisk er tatt inn i 2013. For heilt ferske data bør ein vera oppmerksam på faren for at kvantum kan ligga dobbelt, dvs både på sluttsetel og landingssetel, dersom kvantum enno ikkje er korrekt nedskrive på landingssetel. \\
Enkelte felt er frivillig å fylle ut og kan difor i større grad mangle innhald. Det er heller ikkje gjort kvalitetssikring av alle felt. Der vil difor kunne vera stor variasjon på kvaliteten mellom dei ulike felta i datamaterialet. \\
I løpet av 2013 vart det innført nytt system for overføring av seteldata frå salslaga til Fiskeridirektoratet. I det nye regimet vert setlar overført fortløpande frå kjøpar via laga til oss, slik at tidslegg skal vera kraftig redusert. Samstundes vart det innført fleire automatiske testar i mottaket, slik at ein kan forvente ei auke i kvaliteten på dataene etter denne tid. F.o.m. 2014 er alle salslaga over på dette nye systemet.

Fartøy 

Innføring av fartøy i merkeregisteret, endring i opplysningar om eigar/fartøy i registeret og sletting av fartøy frå registeret vert gjort på bakgrunn av melding frå fartøyets eigar. \\
Som eit ledd i sakshandsaminga ved innføring av fartøy i merkeregisteret eller ved føring av endringar i merkeregisteret vert dei gitte opplysningane kontrollert opp mot opplysningar frå eksterne registre som Skipsregisteret (NOR) samt mot etterspurt og tilsendt dokumentasjon. Endringar som skjer i eksterne registre utanom innførings- og endringstidspunkt blir ikkje automatisk fanga opp. \\
Som ledd i kvalitetssikring av opplysningane i merkeregisteret "vaskast" med ulike mellomrom opplysningane mot andre offentlege registre, og nødvendige granskingar med påfølgande rettingar blir gjort i merkeregisteret på bakgrunn av dette.

Fiskeridirektoratet arbeider kontinuerlig, gjennom kvalitetssikring av sakshandsamingsrutiner og ved gjennomføring av spørreundersøkelser, å avdekke mulige feil og få retta opp disse. Rettingar kan også skje bakover i tid.

## Kjelde \\

- Fiskeridirektoratets landings- og sluttseddelregister
- Fiskeridirektoratets merkeregister
  
**Tidsperiode**: 2000 - Fortløpande oppdatert 

---

## Dokumentnummer: Dokumentnummer \\

Dokumentnummer som er trykka på fysisk setel. Løpenummer som skal vera unikt innanfor eit salslag innanfor eit år. Frå rundt 2004 til og med 2017 er nummeret bygd opp med 12 siffer, første siffer angir salslag, andre siffer dokumenttype og deretter løpenummer med leiande nullar. Denne forma er komplett frå og med 2005 med unntak av eigengenererte setlar (i Fiskeridirektoratet) på Salslag (kode) lik 10. Denne forma gjev unike nummer på tvers av alle salslag. Frå og med 2018 er nummeret ikkje bygd opp med denne forma lenger for alle salslag, men består for enkelte salslag berre av eit løpenummer. Ein må då ha med informasjon frå felta Dokumenttype og Salgslag i tillegg til Dokumentnummer for å generere eit unikt nummer. \\
Informasjonen er komplett. \\
## Dokumenttype (kode): Dokumenttype \\

Dokumenttype seier noko om kva for type dokument det er. Denne tabellen inneheldt berre dokumenttype 0=sluttsetel og 1=landingssetel. \\
Implementering av landingssetlar er gjort over tid. Vi starta å få inn landingssetlar frå Norges Råfisklag heilt i slutten av 2002, men det er ikkje komplett dei første åra. Sunnmøre og Romsdal Fiskesalslag starta vi å ta inn i 2007, også nokre dokument gjeldande for 2006 og nokre få for 2005 kom då inn. Vest-Norges Fiskesalslag og Norges Sildesalgslag starta vi å ta inn i 2011, då også nokre få dokument gjeldande for 2010. Skagerakfisk er tatt inn i 2013. \\
For heilt ferske data bør ein vera merksam på at kvantum kan ligga dobbelt, dvs både på sluttsetel og landingssetel, dersom kvantum enno ikkje er korrekt nedskrive på landingssetel.

## Kode Nemning \\

0 Sluttseddeldokument 
1 Landingsdokument 
2 Landingsdokument ved transitt 
3 Bryggeseddel 
4 Landingsdokument fra føringsfartøy
5 Fangstsertifikat 
9 Innmeldingsdokument

## Dokumenttype: Beskrivelse av kode for dokumenttype \\

Feltet inneheld nærare beskriving/ledetekst til kode for dokumenttype.

## Dokument versjonsnummer: Versjonsnummer \\

Nummer som angir versjon av dokumentet. Dokument som vert endra skal få nytt versjonsnummer for kvar endring som vert sendt oss frå salslaga. Dokument som er endra av Fiskeridirektoratet får versjonsnummer 99. Berre siste gjeldande versjon av dokumentet vises i tabellen. \\
Informasjonen er komplett. \\

## Dokument salgsdato: Formulardato \\

Dato for underskrift av det fysiske dokumentet. \\

## Dokument versjonstidspunkt: Elektronisk dokumentdato \\ 

Dato for generering av elektronisk utgåve av gjeldande versjon av dokumentet. Når til dømes eit salslag sender korreksjon til ein setel, vil denne få ny elektronisk dokumentdato. \\
Informasjonen er komplett. \\

## Salgslag ID: Organisasjonsnummer salslag \\

Organisasjonsnummer for det salslag fangsten er omsett gjennom. \\
Informasjonen er komplett og korrekt frå og med 2001 med unntak av to dokument i 2007 og eit dokument i 2002. \\

## Kode Nemning \\ 

915442730 Rogaland Fiskesalgslag SL 
916437110 Sunnmøre og Romsdal Fiskesalslag
924821779 Vest-Norges Fiskesalslag 
938469148 Norges Råfisklag 
946768871 Skagerakfisk S/L 
951206091 Norges Sildesalgslag 

## Salgslag (kode): Identitetsnummer salslag 

Kode for kva for eit salslag fangsten er omsett gjennom. \\
Informasjonen er komplett. \\

## Kode Nemning \\

10 Fangst registrert på annen måte \\
2 Skagerakfisk S/L \\
3 Rogaland Fiskesalgslag SL \\
4 Vest-Norges Fiskesalslag \\
6 Sunnmøre og Romsdal Fiskesalslag\\
7 Norges Råfisklag \\
8 Norges Sildesalgslag\\

## Salgslag: Nemning for kode for fiskesalslag \\

Feltet inneheld nærare beskriving/ledetekst til kode for salslag.

## Mottaker ID: Organisasjonsnummer mottakar/kjøpar \\

Organisasjonsnummer mottakar/kjøpar for norske aktørar. \\
Mottaker ID er ikkje komplett utfylt. Feltet har historisk ikkje vorte kvalitetssikra av Fiskeridirektoratet, det har med andre ord ikkje vore føretatt kontroll av om mottakaridentitetar som kjem inn er gyldige. For åra 2000-2001 er feltet svært mangelfullt utfylt. Også for 2002 er der til dels store manglar. Også noko ikkje oppgjeve i seinare år.

I løpet av 2013 er der innført kontroll av om nummeret som er oppgjeve er eit gyldig organisasjonsnummer/fødselsnummer. Dette vert gjort ved hjelp av berekning av kontrollsiffer. Nummeret vert ikkje kontrollert opp mot kjøparregisteret. I tillegg er det innført krav om at mottakaridentitet alltid skal vere oppgjeve for norske aktørar. \\
Dersom fødselsnummer er oppgjeve som mottakaridentitet frå laga, er dette sletta i datasettet. \\
## Mottakernasjonalitet (kode): Nasjonalitet mottakar/kjøpar \\

Nasjonaliteten til mottakar/kjøpar, oppgjeve med 3-bokstavs landkode (ISO-3166). \\
Feltet er ikkje komplett utfylt. For åra før 2005 er andel ikkje oppgjeve omkring 5-14% av dokumenta - 0,5-1% av rundvekt. Frå 2005 og nyare dato er andel ikkje oppgjeven under 0,5 prosent av dokumenta og under 1 promille av rundvekt. I løpet av 2013 er det innført krav om at nasjonaliteten til mottakar/kjøpar alltid skal vera oppgjeve. \\
## Kode Nemning 
ABW ARUBA \\
AFG AFGHANISTAN \\
AGO ANGOLA \\
AIA ANGUILLA \\
ALB ALBANIA \\
AND ANDORRA \\
ANT ANTILLENE \\
ARE DE FORENTE ARABISKE EMIRATER \\
ARG ARGENTINA \\
ARM ARMENIA \\
ASM AMERIKANSK SAMOA \\
ATA ANTARKTIS \\

12 koder er listet ut her. \\
## Mottakernasjonalitet: Nemning for mottakarnasjonalitet \\

Feltet inneheld nærare beskriving/ledetekst til kode for nasjonaliteten til mottakar/kjøpar. \\
# Mottaksstasjon: Mottaksstasjon \\

Kode som angir den fysiske staden der fangsten er landa. Vert oppgjeve med Mattilsynets godkjenningsnummer ved landing til Norske anlegg, unntakskoder i samsvar med kodeliste (som til dømes Fylke-KAI ved kaisal) eller nasjonskode ved landing i utlandet. For nokre år er fryselager ikkje definert som landingsmottak i Mattilsynets godkjenningsliste. Desse anlegga er gjevne eigne kodar av Fiskeridirektoratet. \\
Feltet er ikkje komplett utfylt. Det vert ikkje føretatt full kontroll av om anleggskoder som kjem inn er gyldige i samsvar med Mattilsynets lister. I løpet av 2013 er det innført automatisk kontroll som sikrar komplett utfylling for alle landingar i Noreg. Frå same tidspunkt er det ikkje lenger krav om å gjenta nasjonskoden i dette feltet ved landing i utlandet. \\
## Landingskommune (kode): Mottaksstasjonens kommunenummer 

Kommunenummer for den kommune kor mottaksstasjonen er plassert eller den kommune kor fangsten vert henta frå lås, leveret til fryseskip eller vert henta av føringsbåt. Dersom fangsten ikkje vert brakt på land skal det nyttast kode for den kommune der kjøparfartøy overtar fangsten. Vert oppgitt med SSBs kommunekode for norske kommunar eller FDIRs landkodar for utland/ikkje oppgitt. \\
Spesielt for eldre år var der ein del tilfelle der det vart fylt ut kjøpars kommunenummer i staden for reell landingskommune. Dette var størst problem den første tida ein gjorde bruk av nøytrale fryselagar ved landing. Ein antar dette har betra seg i nyare år.

2000-2004: Landing til russiske frysefartøy koda som 8801. \\ 
2005-2009: Landing til russiske frysefartøy koda inn med kommunekode for der båten faktisk ligg. \\
2004-2009 og 2000: Ikkje komplett utfylt for utland. Dette gjeld nokre få landingar i land det ikkje er oppretta "kommunekode" (URY, ZAF). \\
I løpet av 2013 har ein gått vekk i frå bruk av FDIRs landkodar for utland, og feltet vil då vera NULL for landingar i utlandet. \\

## Kode Nemning 
0101 HALDEN 
0102 SARPSBORG før 1992 
0103 FREDRIKSTAD før 1994
0104 MOSS 
0105 SARPSBORG 
0106 FREDRIKSTAD 
0111 HVALER 
0113 BORGE før 1994 
0114 VARTEIG før 1992 
0115 SKJEBERG før 1992 
0118 AREMARK 
0119 MARKER 

12 koder er listet ut her. 

## Landingskommune: Namn på landingskommune 

Feltet inneheld namnet på landingskommunen. 

## Landingsfylke (kode): Kode for landingsfylke 
Fylkeskode, numerisk, for fylket fangsten er landa i. Fylkeskoden er generert ut frå kode for landingskommune i dei tilfella innhaldet i feltet for landingskommune (kode) er eit norsk kommunenummer. 

Spesielt for eldre år var det ein del tilfelle der det vart fylt ut kjøpars kommunenummer i staden for reell landingskommune. Dette var størst problem den første tida ein gjorde bruk av nøytrale fryselagar ved landing. Ein antar dette har betra seg i nyare år. 

## Landingsfylke: Namn på landingsfylke 

Feltet inneheld namnet på landingsfylket. 

## Landingsnasjon (kode): Landingsnasjon 
Nasjon fangsten vert landa i, angitt med 3-bokstavs landkode (ISO-3166). 

Informasjonen er komplett. 

## Kode Nemning 
ABW ARUBA 
AFG AFGHANISTAN 
AGO ANGOLA 
AIA ANGUILLA 
ALB ALBANIA 
AND ANDORRA 
ANT ANTILLENE 
ARE DE FORENTE ARABISKE EMIRATER
ARG ARGENTINA 
ARM ARMENIA 
ASM AMERIKANSK SAMOA 
ATA ANTARKTIS 

12 koder er listet ut her. 

## Landingsnasjon: Nemning for landingsnasjon 
Feltet inneheld namnet på nasjonen fangsten er landa i. 

## Produksjonsanlegg: Produksjonsanlegg 

Produksjonsanlegg er der fangsten skal produserast. Kan vera lik eller ulik mottaksstasjon. 

Ikkje komplett utfylt og ikkje kvalitetssikra hjå Fiskeridirektoratet. 

## Produksjonskommune (kode): Produksjonsanleggets kommunenummer 

Kommunenummer for kommunen der det fysiske produksjonsanlegget er plassert. 

Ikkje komplett utfylt og ikkje kvalitetssikra hjå Fiskeridirektoratet. 

## Kode Nemning 
0101 HALDEN 
0102 SARPSBORG før 1992 
0103 FREDRIKSTAD før 1994
0104 MOSS 
0105 SARPSBORG 
0106 FREDRIKSTAD 
0111 HVALER 
0113 BORGE før 1994 
0114 VARTEIG før 1992 
0115 SKJEBERG før 1992 
0118 AREMARK 
0119 MARKER 
12 koder er listet ut her. 
Produksjonskommune: Namn på produksjonskommune 
Feltet inneheld namnet på kommunen der det fysiske produksjonsanlegget er plassert. 
Mottakende fartøy reg.merke: Fartøyets registreringsmerke ved landing til fartøy 
Registreringsmerke til fartøy som mottar fangst. Brukast i tilfelle der fangsten vert levert til 
kjøpefartøy, føringsbåt, fryseskip mv. 
Mottakende fartøy rkal: Kjenningssignal/MMSI-nr ved landing til fartøy 
Kjenningssignal/MMSI-nr til fartøy som mottar fangst. Brukast i tilfelle der fangsten vert 
levert til kjøpefartøy, føringsbåt, fryseskip mv. 
Mottakende fartøytype (kode): Fartøy type ved landing til fartøy 
Kode for fartøytype for fartøy som mottar fangst. 
Kode Nemning 
01 Fiskefartøy 
02 Transportfartøy 
03 Brønnbåt 
04 Leiefartøy (Erstatningsfartøy)
05 Kjøpefartøy 
06 Samfiskefartøy 
07 Partrållag 
08 Forskningsfartøy 
09 Skolefartøy 
10 Landnotfartøy 
11 Taretråler 
12 Fritidsfartøy 
Mottakende fart.type: Nemning for fartøytype for fartøy som mottar fangst 
Feltet inneheld nemning for kode for fartøytype for fartøy som mottar fangst. 
Mottakende fartøynasj. (kode): Nasjonalitet for fartøy (flaggstat) ved landing til fartøy 
Nasjonalitet for fartøy (flaggstat) som mottar fangst, angitt med 3-bokstavs landkode (ISO3166). 
Kode Nemning 
ABW ARUBA 
AFG AFGHANISTAN 
AGO ANGOLA 
AIA ANGUILLA 
ALB ALBANIA 
AND ANDORRA 
ANT ANTILLENE 
ARE DE FORENTE ARABISKE EMIRATER
ARG ARGENTINA 
ARM ARMENIA 
ASM AMERIKANSK SAMOA 
ATA ANTARKTIS 
12 koder er listet ut her. 
## Mottakende fart.nasj: Nemning for nasjonalitet for fartøy som mottar fangst 

Feltet inneheld nemning for nasjonalitet for fartøy som mottar fangst. 

## Fisker ID: Identitetsnummer fiskar 
Identitetsnummer til den som landar/fiskar. Kan vere fødselsnummer, organisasjonsnummer  eller salslagets interne kundenummer. 

Feltet er ikkje komplett utfylt. Feltet har historisk ikkje vorte kvalitetssikra, det har med andre ord ikkje vore føretatt kontroll av om fødselsnummer/organisasjonsnummer som kjem inn er gyldige. Ikkje oppgjeve nummer er utfylt med 0. 

I løpet av 2013 er det innført kontroll av om nummeret som vert oppgjeve er eit gyldig fødselsnummer/organisasjonsnummer. Dette vert gjort ved hjelp av berekning av kontrollsiffer. Nummeret vert ikkje kontrollert opp mot fiskarmanntalet. I tillegg er det innført krav om at identitetsnummer alltid skal vere oppgjeve for norske aktørar. 

Dersom fødselsnummer eller internt kundenummer hos salslaget er oppgitt, vil dette vere sletta i datasettet. 

## Fiskerkommune (kode): Fiskarkommune 
Skattekommunenummer til den som landar/fiskar oppgjeve med SSBs kommunekodar for norske kommunar eller FDIRs landkodar for utland/ikkje oppgjeve. Det er ikkje dette feltet som vert brukt til kommunestatistikk. For statistikk på fartøykommune bruk informasjon i feltet Fartøykommune (kode). 

Feltet er ikkje komplett utfylt for alle år. I løpet av 2013 har ein gått vekk i frå bruk av FDIRs landkodar for utland, og feltet vil då vera NULL for utlendingar. For informasjon om nasjonalitet sjå feltet Fiskernasjonalitet (kode). 

## Kode Nemning 
0101 HALDEN 
0102 SARPSBORG før 1992 
0103 FREDRIKSTAD før 1994
0104 MOSS 
0105 SARPSBORG 
0106 FREDRIKSTAD 
0111 HVALER 
0113 BORGE før 1994 
0114 VARTEIG før 1992 
0115 SKJEBERG før 1992 
0118 AREMARK 
0119 MARKER 
12 koder er listet ut her. 

## Fiskerkommune: Namn på fiskarkommune 
Feltet inneheld namn på skattekommunen til den som landar/fiskar. 

## Fiskernasjonalitet (kode): Nasjonalitet til fiskar 
Nasjonalitet til den som landar/fiskar, oppgjeve med 3-bokstavs landkode (ISO-3166). 
2000-2004: Ikkje komplett utfylt - Nokre manglar for utanlandske fartøy hjå eit salslag. 
2010: Nokre få manglar for norske fartøy hjå eit salslag. 
2011 - : Komplett utfylt frå og med 2011. 
Kode Nemning 
ABW ARUBA 
AFG AFGHANISTAN 
AGO ANGOLA 
AIA ANGUILLA 
ALB ALBANIA 
AND ANDORRA 
ANT ANTILLENE 
ARE DE FORENTE ARABISKE EMIRATER
ARG ARGENTINA 
ARM ARMENIA 
ASM AMERIKANSK SAMOA 
ATA ANTARKTIS 
12 koder er listet ut her. 
Fiskernasjonalitet: Nemning for nasjonaliteten til fiskar 
Feltet inneheld nemning for nasjonaliteten til den som landar/fiskar. 
Fartøy ID: Unik intern identifikasjon av fartøy 
Intern primærnøkkel i Fiskeridirektoratet for grunneininga fartøy. Nummeret består av 10 
teikn, der dei 4 første er årstall då fartøyet blei registrert i merkeregisteret første gong og eit 
løpenummer på 6 siffer. Dette nummeret blir generert automatisk ved første gongs 
registrering av fartøyet. 
Informasjonen er komplett. 
Registreringsmerke (seddel): Fartøyets registreringsmerke 
Registreringsmerket på fartøyet som har fiska. For norske fiskefartøy skal her angis fartøyets 
registreringsmerke i merkeregisteret. Dette består av maks 8 teikn. Fram til og med 2017 
angir teikn 1-2 fylkeskode, 3-6 eit løpenummer og 7-8 angir kommunekode. Frå og med 2018 
vil det ikkje nødvendigvis vere samsvar mellom «fylkeskode» og «kommunekode» i 
registreringsmerket og der fartøyet er heimehøyrande. I samband med regionreforma har 
ein gjort val om at fartøya skal behalde registreringsmerket som viser til tidlegare fartøyfylke 
og -kommune. Ved seinare hendingar på fartøy som normalt fører til nytt 
registreringsmerke, skal fartøyet få eit registreringsmerke med fylkes- og 
kommunebokstavar som viser til kor fartøyet er heimehøyrande. I merkeregisteret er det 
innført eit nytt felt frå og med 2018, kommunenummer, som angir kor fartøyet er 
heimehøyrande. 
Andre typar registreringsmerker for norske fartøy enn fiskefartøy har varierande former for 
oppbygging. Kjente former for konstruerte merker brukt er: 
- Uregistrerte norske fartøy som fritidsfartøy og landnotfartøy: ZZ-kommunekode-ZZ, 
kommunekode=fiskars kommune. 
- Ungdomskvote: Fylkesbokstav-Årstall-UK. Dette tyder at det vert eit felles merke for 
alle som fiskar på slik kvote innan eit fylke. 
- Forskingsfartøy: Fylkesbokstav-9300-Kommunebokstav.I enkelte tilfelle kan nokre 
forskingsfartøy ha eigne merke. Dette gjeld forskingsfartøy som høyrer til 
forskingsinstitusjonar. 
- Taretrålarar: Fylkesbokstav-8xxx-Kommunebokstav, frå og med 2011. 
- Fritidsfartøy: Frå og med 2013 brukast også merke frå register over fritidsbåtar. 
Registreringsmerker for utanlandske fartøy har ulike former for oppbygning, men vil her vera 
oppført utan mellomrom eller bindestrek. 
Ugyldige registreringsmerker kan finnast. Historisk har det ikkje vorte fortlaupande 
kontrollert opp mot merkeregisteret. Ved kopling mot merkeregisteret ved hjelp av dato må 
det difor forventast ein del fråfall, spesielt for tidlege år. I løpet av 2013 er det innført 
automatisk kontroll opp mot merkeregisteret for norske fiskefartøy. Fartøy som då fell 
utanfor gyldig periode vil verta merka med kode 13 i feltet for fartøytype. Frå same tid har 
ein også oppheva kravet om bruk av konstruerte merker, dvs at fartøy som ikkje har reelt 
registreringsmerke kan førast blankt (NULL). Her er desse derimot koda om til ZZ9990ZZ då 
feltet er obligatorisk her. 
Radiokallesignal (seddel): Fartøyets kallesignal 
Fartøyets Kjenningssignal/MMSI-nr. Nummer som identifiserer fartøyet. Det vert nytta enten 
kjenningssignal utstedt av Sjøfartsdirektoratet eller MMSI-nummer (Maritime Mobile Service 
Identity) utstedt av Telenor Kystradio ved teikning av VHF-lisens. For utanlandske fartøy vert 
det nytta tilsvarande nummer utstedt av heimlandet.
Ikkje komplett utfylt. Det er heller ikkje alle fartøy som har kallesignal. Det kan finnast 
ugyldige kallesignal. Historisk har det ikkje vorte fortlaupande kontrollert opp mot 
merkeregisteret. I løpet av 2013 er det innført automatisk kontroll opp mot merkeregisteret 
for norske fiskefartøy. Fartøy som ikkje har kjenningssignal i merkeregisteret kan likevel ha 
feltet utfylt med gyldig kallesignal på sluttsetelen. 
Fartøynavn: Fartøyets namn 
Merkeregisteret skal innehalde opplysning om namn på det enkelte fartøy, sjå 
ervervstillatelsesforskriften § 13. Fartøyet sitt namn vert oppgitt av eigaren til fartøyet. For 
fartøy som også skal førast i Skipsregisteret NOR er det gitt eigne reglar om namn på fartøy i 
forskrift 27. juni 2002 nr 754 om skips navn, kjenningssignal, merking og hjemsted mv. § 4, 
sjå også sjøloven § 7. 
Informasjonen er oppgitt av næringsaktør. Informasjonen er utfylt for alle rader, men kan 
innehalde feil. 
Fartøytype (kode): Fartøytype 
Fartøytype (fartøyrolle) gjev kode for kva for rolle/eigenskap fartøyet opptrer i når det 
landar fangst. Eit og same fartøy kan ha ulike rollar på ulike dokument. 
Ikkje komplett utfylt, kode 00 nytta for ikkje oppgjeve. Feltet vart først tatt i bruk i løpet av 
2004, men dei første åra er det berre delvis tatt i bruk av nokre av salslaga. Meir komplett 
informasjon for nyare år, og i åra etter 2010 er andel ikkje oppgjeven under 0,5% av total 
rundvekt. I løpet av 2013 vart det innført automatisk testing som sikrar komplett utfylling hjå 
alle lag. 
Kode Nemning 
01 Fiskefartøy 
02 Transportfartøy 
03 Brønnbåt 
04 Leiefartøy (Erstatningsfartøy)
05 Kjøpefartøy 
06 Samfiskefartøy 
07 Partrållag 
08 Forskningsfartøy 
09 Skolefartøy 
10 Landnotfartøy 
11 Taretråler 
12 Fritidsfartøy 
12 koder er listet ut her. 
Fartøytype: Nemning for kode for fartøytype, bokmål
Feltet inneheld nærare beskriving/ledetekst til kode for fartøytype på bokmål. 
Kvotefartøy reg.merke: Registreringsmerke på kvotefartøy 
Sluttsetlar inneheldt to fartøyidentifikasjonar i registreringsmerkeformat. Feltet 
Registreringsmerke (seddel) omfattar fartøy som er aktiv i fiske. I enkelte tilfelle skal 
fangsten ikkje kvoteavreknast på det registreringsmerket som står oppført i 
Registreringsmerke (seddel). I slike tilfelle blir dette feltet tatt i bruk. Dette feltet blir fyrst og 
fremst brukt i samband med leigefartøy- og samfiskeordning. 
Ikkje komplett utfylt, spesielt for tidlige år. I løpet av 2013 vart det innført automatisk testing 
som sikrar at feltet alltid vert utfylt i samband med leigefartøy- og samfiskeordninga. 
Besetning: Talet på personar om bord 
Angir kor mange personar som har vore om bord på fartøyet under fiske. 
Ikkje komplett utfylt. 
Fartøykommune (kode): Kode for heimstadkommunen til fartøyet 
Fram til og med 2017 er kommunekoden generert ut frå fylkesbokstavar og 
kommunebokstavar i fartøyets registreringsmerke. Frå og med 2018 vil det ikkje 
nødvendigvis vere samsvar mellom «fylkeskode» og «kommunekode» i registreringsmerket 
og der fartøyet er heimehøyrande. I samband med regionreforma har ein gjort val om at 
fartøya skal behalde registreringsmerket som viser til tidlegare fartøyfylke og -kommune. 
Ved seinare hendingar på fartøy som normalt fører til nytt registreringsmerke, skal fartøyet 
få eit registreringsmerke med fylkes- og kommunebokstavar som viser til kor fartøyet er 
heimehøyrande. I merkeregisteret er det innført eit nytt felt frå og med 2018, 
kommunenummer, som angir kor fartøyet er heimehøyrande. 
Fartøykommune: Heimstadkommunen til fartøyet 
Feltet inneheld namnet på kommunen fartøyet er heimehøyrande i. 
Fartøyfylke (kode): Kode for heimstadfylket til fartøyet 
Fram til og med 2017 er fylkeskoden generert ut frå fylkesbokstaver i fartøyets 
registreringsmerke. Frå og med 2018 vil det ikkje nødvendigvis vere samsvar mellom 
«fylkeskode» og «kommunekode» i registreringsmerket og der fartøyet er heimehøyrande. I 
samband med regionreforma har ein gjort val om at fartøya skal behalde registreringsmerket 
som viser til tidlegare fartøyfylke og -kommune. Ved seinare hendingar på fartøy som 
normalt fører til nytt registreringsmerke, skal fartøyet få eit registreringsmerke med fylkesog kommunebokstavar som viser til kor fartøyet er heimehøyrande. I merkeregisteret er det 
innført eit nytt felt frå og med 2018, kommunenummer, som angir kor fartøyet er 
heimehøyrande. Fylkeskoden/-nummer er dei to første siffera i kommunenummeret (4 
siffer). 
Fartøyfylke: Heimstadfylket til fartøyet 
Feltet inneheld namnet på fylket fartøyet er heimehøyrande i. 
Fartøynasjonalitet (kode): Nasjonalitet fartøy (flaggstat) 
Nasjonalitet til fartøyet (flaggstat), angitt med 3-bokstavs landkode (ISO-3166). 
Informasjonen er komplett. 
Kode Nemning 
ABW ARUBA 
AFG AFGHANISTAN 
AGO ANGOLA 
AIA ANGUILLA 
ALB ALBANIA 
AND ANDORRA 
ANT ANTILLENE 
ARE DE FORENTE ARABISKE EMIRATER
ARG ARGENTINA 
ARM ARMENIA 
ASM AMERIKANSK SAMOA 
ATA ANTARKTIS 
12 koder er listet ut her. 
Fartøynasjonalitet: Nemning for nasjonaliteten til fartøyet 
Feltet inneheld namnet på nasjonen fartøyet er heimehøyrande i. 
Fartøynasjonalitet gruppe: Gruppering av fartøynasjonalitet 
Feltet inneheld gruppering av fartøynasjonalitet – norske eller utanlandske fartøy. 
Største lengde: Fartøyets største lengde 
Merkeregisteret skal omfatte informasjon om fartøyets største lengde, sjå 
ervervstillatelsesforskriften § 13. Største lengde er lengde i meter målt frå framkant av 
fremste del av skroget til akterkant av akterste del av skroget, jfr. forskrift 18. desember 
2009 nr 1694 om måling av skip § 2 bokstav l. 
Informasjonen er oppgitt av næringsaktør. Informasjonen er utfylt for alle rader, men kan 
innehalde feil. 
For fartøy som har stått lenge i merkeregisteret, og som det ikkje er utstedt 
målebrev/identitetsbevis for fordi de ikkje er målepliktige, kan det være usikkert om det er 
kjenningslengde eller største lengde som er oppgitt i merkeregisteret. 
Lengdegruppe (kode): Kode for lengdegruppe 
Lengdegrupper generert ut frå fartøyets største lengde. Inndeling etter Finnmarksmodellen. 
Lengdegruppe: Nemning av lengdegruppe 
Feltet inneheld nemning av lengdegruppe. 
Bruttotonnasje 1969: Bruttotonnasje - 1969 
Merkeregisteret skal omfatte informasjon om fartøyas bruttotonnasje, sjå 
ervervstillatelsesforskriften § 13. 
I denne variabelen, «Bruttotonnasje 1969», er det i dag ført bruttotonnasje for fartøy med 
lengde (L) større eller lik 24 meter (L), målt og berekna i medhald av internasjonal 
konvensjon om måling av fartøy, 1969 (London-konvensjonen 1969). 
Fram til 1982 blei det i det tidlegare elektroniske merkeregisteret for denne variabelen ført 
opp fartøyets nettotonnasje. 
Regler for berekning av et fartøys bruttotonnasje har endra seg over tid. I medhald av 
forskrift av 14. juni 1982 nr. 1044 om måling av fartøy skulle bruttotonnasje etter 18. juli 
1982 bereknast etter 1969-konvensjonens målereglar. Frå 18. juli 1994 fekk 1969-
konvensjonen full verknad for eitkvart fartøy som blei omfatta av konvensjonen. 
Målepliktige fartøy med lengde (L) på 24 meter eller større skulle innan den dato være 
ommålt. 
Fiskerimyndighetene hadde reglar for regulering av tilgang til å drive fiske og regulering av 
fiske basert på det enkelte fartøys bruttotonnasje. Det kunne være stor forskjell på 
bruttotonnasje for same fartøy berekna etter tidligare målereglar og etter 1969-
konvensjonen, spesielt for fartøy med shelterdekk. Fiskerimyndighetene måtte derfor i 
merkeregisteret registrere det enkelte fartøys bruttotonnasje på ein slik måte at det klart 
gjekk fram kva berekningsmetode som vart nytta, samtidig som dette også vart ivaretatt ved 
endring av forskrifter. Frå 1982 er det derfor i merkeregisteret to variablar med opplysning 
om fartøys bruttotonnasje. 
Bruttotonnasje er her oppgitt i samsvar med fartøyets målebrev, og er såleis bare oppgitt for 
fartøy som er målt av Sjøfartsmyndighetene. Det vises til lov 16. februar 2007 nr. 9 om 
skipssikkerhet (skipssikkerhetsloven) § 10 og til forskrift 18. desember 2009 nr 1694 om 
måling av skip. 
Det vises også til tidligare lov 19. juni 1964 nr. 20 om måling av fartøyer og til tidligare 
forskrifter 26. juli 1994 nr. 749 om måling av fartøyer og forskrifter 14. juni 1982 om måling 
av fartøyer. Disse er alle oppheva. 
Informasjonen er oppgitt av næringsaktør. Informasjonen er ikkje utfylt for alle rader. 
Informasjonen kan innehalde feil. 
Bruttotonnasje annen: Bruttotonnasje - annan 
Merkeregisteret skal omfatte informasjon om fartøys bruttotonnasje, sjå 
ervervstillatelsesforskriften § 13. 
I denne variabelen, Bruttotonnasje - annan, er det ført opp bruttotonnasje målt etter andre 
reglar enn London-konvensjonen 1969 for fartøy under 24 meter (L). Det kan vere Norsk 
Innenriks Målebrev (1982) til målepliktig fartøy ved første gangs måling når lengde (L) er 
mindre enn 24 meter, Internasjonalt målebrev (1947) i samsvar med 1947-konvensjonens 
målereglar eller målebrev etter tidligare målereglar. Det kan også vere bruttotonnasje for 
fartøy under 15 meter i Identitetsbevis utstedt etter kjenningsmåling (fastsetting av lengde, 
bredde og djupne) og der bruttotonnasje er ekvivalent som følger: 15 meter ekvivalent til 25 
bruttotonn, 12,5 meter ekvivalent til 20 bruttotonn, 11,5 meter ekvivalent til 15 bruttotonn, 
10 meter ekvivalent til 10 bruttotonn og 8 meter ekvivalent til 4 bruttotonn. 
«Identitetsbevis» vert ikkje lenger utskrive, ordninga vart avslutta 1. januar 2010 av forskrift 
18. desember 2009 nr 1694 om måling av skip. Bruttotonnasje i merkeregisteret er oppgitt i 
medhald av fartøyets målebrev/identitetsbevis, og er såleis berre oppgitt for fartøy som er 
målt eller kjenningsmålt av Sjøfartsmyndighetene. Reglane for måling av fartøy har endra 
seg over tid. Det vises til lov 16. februar 2007 nr 9 om skipssikkerhet (skipssikkerhetsloven) § 
10 og til forskrift 18. desember 2009 nr 1694 om måling av skip. 
Det vises også til tidligare lov 19. juni 1964 nr 20 om måling av fartøyer og til tidligare 
forskrifter 26. juli 1994 nr 749 om måling av fartøyer og 14. juni 1982 om måling av fartøyer. 
Disse er alle oppheva. 
Informasjonen er oppgitt av næringsaktør. Informasjonen er ikkje utfylt for alle rader. 
Informasjonen kan innehalde feil. 
Byggeår: Byggeår fartøy 
Årstall for når skroget blei bygd. 
Informasjonen er ikkje komplett, men det finnes informasjon om byggeår for dei fleste 
fartøy. 
Ombyggingsår: Ombyggingsår fartøy 
Årstall for når fartøyet sist ble ombygd. 
Det er usikkerhet med omsyn til om fartøyeigar alltid gir pliktige opplysningar om 
ombygging. 
Motorkraft: Motorkraft 
Motorkraft oppgitt i hestekrefter (HK). Omrekningsformel frå hestekrefter (HK) til kilowatt 
(kW) er: kW = HK/1,36. 
Informasjonen er ikkje komplett, men det finnes informasjon om motorkraft for de fleste 
fartøy. Det er også usikkerhet med omsyn til om fartøyeigar alltid gir pliktige opplysningar 
om eventuell ny motor og dermed endring i hestekrefter (HK). 
Motorbyggeår: Byggeår motor 
Årstall for når motoren blei bygd. 
Informasjonen er ikkje komplett, men det finnes informasjon om byggeår for motor for dei 
fleste fartøy. Det er også usikkerhet med omsyn til om fartøyeigar alltid gir pliktige 
opplysningar om eventuell ny motor og dermed endring i årstall for bygging av motor. 
Fangstår: Fangstår 
Årstalet for når fangsten er tatt. Fangst tatt i ulike fangstår skal føres på kvar sine setlar. 
Informasjonen er komplett. 
Siste fangstdato: Siste fangstdato 
Siste fangstdato er siste dag fiskefartøyet tar fangst om bord. 
Feltet er først tatt i bruk i løpet av 2004 men hadde ikkje tilstrekkeleg innhald til å kunne tas i 
bruk for 2004-data. Dersom feltet er ugyldig eller ikkje er oppgitt, har dato i dette feltet 
automatisk vorte sett lik landingsdato eller 31.12.fangstår dersom landingsdatoen er i året 
etter, ved mottak av data. I løpet av 2013 er det innført automatiske kontrollar som sikrar 
komplett utfylling hjå alle salslag. 
Kvotetype (kode): Kvotetype 
Kode for kva kvotetype det er fiska på. 
Ikkje komplett utfylt. Før 2005 er det så store manglar at ein ikkje kan bruke informasjonen 
til generell statistikk. Også til dels store manglar i åra 2005-2008. Vert ikkje komplett 
kvalitetssikra hjå Fiskeridirektoratet. Kodelista er betydeleg utvida over tid. 
Kode Nemning 
01 Vanlig kvote 
02 Forskningskvote 
03 Skolekvote 
04 Annet lands kvote 
05 Ungdomskvote 
06 Fritidsfiske 
07 Vanlig kvote med leveringsbetingelser
08 Distriktskvote 
09 Agnkvote 
10 Vanlig kvote, salg til turist 
11 Kongekrabbe-kvote i kvoteområdet. 
12 Bonuskvote, fersk 
12 koder er listet ut her. 
Kvotetype: Nemning for kode for kvotetype 
Feltet inneheld nemning for kode for kvotetype. 
Redskap (kode): Reiskap 
Kode som identifiserer nytta fangstreiskap. Dersom fleire ulike reiskap er brukt på same tur 
er kravet at viktigaste reiskap skal oppgis. 
Det at all fangst på ein setel vert ført på eitt reiskap, kan føra til at det vert nokre tilfelle med 
ulogiske kombinasjonar av fiskeslag og reiskap. For å rydde unna slike ulogiske 
kombinasjonar vert det gjort ei automatisk retting av reiskap for visse fiskeslag. 
Følgjande føringar ligg til grunn for desse rettingane: 
1. Reker - ved anna reiskapskode enn 55-Reketrål, 58-Dobbeltrål eller 59-Trippeltrål 
endrast reiskap til 55-Reketrål. 
2. Krabbe (unntatt kongekrabbe) - ved anna reiskapskode enn 42-Teiner endrast reiskap 
til 42-Teiner. 
3. Kongekrabbe - ved anna reiskapskode enn 42-Teiner, 50-Udefinert trål eller 51-
Bunntrål endrast reiskap til 42-Teiner. 
4. Hummar - ved anna reiskapskode enn 42-Teiner endrast reiskap til 42-Teiner. 
5. Sjøkreps - dersom reiskap er 50-Udefinert trål, 51-Bunntrål, 52-Bunntrål par, 53- 
Flytetrål, 54-Flytetrål par, 58-Dobbeltrål eller 59-Trippeltrål endrast reiskap til 57- 
Krepsetrål. Deretter ved anna reiskap enn 40-Udefinert bur og ruser, 41-Ruser, 42-
Teiner, 55-Reketrål, 56-Bomtrål, 57-Krepsetrål endrast reiskap til 42-Teiner. 
6. Skjell - ved anna reiskap enn 80-Annet, 81-Skjellskrape endrast reiskap til 80-Annet 
7. Ål - ved anna reiskap enn 41-Ruser endrast reiskap til 41-Ruser. 
8. Ikkje oppgitt reiskapskode 99- Uspesifisert endrast til 80-Annet. 
Kode Nemning 
10 Udefinert not 
11 Snurpenot/ringnot 
12 Landnot 
14 Snurpenot med lys 
15 Landnot med lys 
20 Udefinert garn 
21 Drivgarn 
22 Settegarn 
30 Udefinert krokredskap
31 Flyteline 
32 Andre liner 
33 Juksa/pilk 
12 koder er listet ut her. 
Redskap: Nemning for kode for reiskap 
Feltet inneheld nemning for kode for reiskap. 
Redskap – gruppe (kode): Kode for reiskapsgruppe 
Feltet inneheld kode for gruppering av nytta fangstreiskap. 
Reiskap – gruppe: Nemning for kode for reiskapsgruppe 
Feltet inneheld nemning for kode for gruppering av nytta fangstreiskap. 
Redskap - hovedgruppe (kode): Kode for hovudgrupper for reiskap 
Feltet inneheld kode for hovudgruppe for reiskap. 
Redskap - hovedgruppe: Nemning for hovudgrupper for reiskap 
Feltet inneheld nemning for kode for hovudgruppe for reiskap. 
Fangstfelt (kode): Fangstfelt 
Fangstfelt (5-siffer). Samansett av 1. siffer, kyst/hav-kode, 2.-3. siffer hovudområde og 4.-5. 
siffer lokasjon. Definerer viktigaste fangstfelt på turen. 
Dersom det har vore fiska på fleire ulike hovudområde på same tur er kravet at viktigaste 
hovudområde skal oppgis. Fangst tatt i ulike soner skal likevel førast på kvar sin setel. For 
torsketrålarar og reketrålarar har ein i åra før 2017 føretatt ei kvalitetssikring og ei 
ytterlegare detaljering på områdenivå ved hjelp av informasjon frå fangstdagboka. Dette 
vert gjort internt i Fiskeridirektoratet, og er berre gjort for ferdig kvalitetssikra år. Frå og med 
2018 har slik retting på enkeltsetlar ikkje blitt utført hos Fiskeridirektoratet. Informasjon om 
hovudområde vil difor etter 2018 vere det viktigaste hovudområdet i dei tilfella fisket har 
føregått over fleire hovudområde på same tur. 
Nokre få tilfelle med fangstfelt 99999 er brukt for uoppgjeve fangstfelt. 
Kyst/hav (kode): Kyst/hav-kode 
Kyst/hav-kode definerer om fangsten er tatt innanfor eller utanfor tolvmilsgrensa. 
(8=innanfor/0=utanfor 12-mila) 
Komplett utfylt. Nokre få tilfelle med kyst/hav-kode 9 er brukt for uoppgjeve fangstfelt. 
Hovedområde (kode): Hovudområde 
Hovudområde, to siffer. 
Dersom det har vore fiska på fleire ulike hovudområde på same tur er kravet at viktigaste 
hovudområde skal oppgis. Fangst tatt i ulike soner skal likevel førast på kvar sin setel. For 
torsketrålarar og reketrålarar har ein i åra før 2017 føretatt ei kvalitetssikring og ei 
ytterlegare detaljering på områdenivå ved hjelp av informasjon frå fangstdagboka. Dette 
vert gjort internt i Fiskeridirektoratet, og er berre gjort for ferdig kvalitetssikra år. Frå og med 
2018 har slik retting på enkeltsetlar ikkje blitt utført hos Fiskeridirektoratet. Informasjon om 
hovudområde vil difor etter 2018 vere det viktigaste hovudområdet i dei tilfella fisket har 
føregått over fleire hovudområde på same tur. 
Kode Nemning 
00 Vestfjorden (Lofoten) 
01 Kaninbanken 
02 Murmanskkysten 
03 Øst-Finnmark 
04 Vest-Finnmark 
05 Røstbanken til Malangsgrunnen
06 Helgelandsbanken 
07 Storegga-Frøyabanken 
08 Eigersundbanken 
09 Skagerrak 
10 Skolpenbanken 
11 Gåsebanken 
12 koder er listet ut her. 
Hovedområde: Nemning for kode for område 
Feltet inneheld namn på hovudområde. 
Lon (hovedområde): Lengdegrad - hovedområde 
Lengdegrad for midtpunktet til hovedområdet. 
Lat (hovedområde): Breddegrad - hovedområde 
Breddegrad for midtpunktet til hovedområdet. 
Lokasjon (kode): Lokasjon 
Lokasjon, to siffer. Inneheld ei nummerering av rektangel under hovudområde. 
Innhaldet i feltet er av variabel kvalitet, og må nyttast med varsemd. Innhaldet vil kunne ha 
noko betre kvalitet for pelagisk sektor samt for fangst tatt med konvensjonelle reiskap (garn, 
line, snurrevad, ruser, teiner og juksa), for fangstoperasjonar som ikkje går over så store 
områder på same tur. 
Lon (lokasjon): Lengdegrad - lokasjon 
Lengdegrad for midtpunktet til lokasjonen. 
Lat (lokasjon): Breddegrad - lokasjon 
Breddegrad for midtpunktet til lokasjonen. 
Sone (kode): Økonomisk sone 
Den økonomiske sone, vernesone o.s.v. der fangstoperasjonen har føregått. 
Feltet vart innført i 2004, men ikkje tatt fullt i bruk før 2005. Nokre tilfelle er likevel utfylt 
også for tidlegare år. Bør ikkje nyttast for åra før 2005. 
1. 2000-2004: Svært mangelfull - bør ikkje nyttast til generell statistikk. 
2. 2005-2007: Ikkje komplett utfylt. 
3. 2008- : Komplett utfylt fom 2008. 
Kode Nemning 
CAN Canadisk økonomisk sone 
FRO Færøysk økonomisk sone 
GRL Grønlandsk økonomisk sone 
ISL Islandsk økonomiske sone 
NOR Norsk økonomisk sone 
RUS Russisk økonomisk sone 
USA USAs økonomiske sone 
XAA Det tilstøtende området i Barentshavet (
XBS Smutthullet 
XCA CCAMLR-området 
XEU EU - sonen 
XJM Fiskerisonen rundt Jan Mayen 
12 koder er listet ut her. 
Sone: Nemning for kode for økonomisk sone 
Feltet inneheld namn på økonomisk sone. 
Områdegruppering (kode): Kode for områdegruppering 
Denne variabelen inneheld kode for ICES-område eller NAFO-område. Koden inneheld 
prefiks for FAO-område slik at det er mogleg å skilje mellom ICES-område (27) og NAFOområde (21). 
Fram til og med 2004 inneheld variabelen kodar for ICES-områder som var gjeldande fram til 
2010. Eksisterande inndeling i ICES-områder som vart oppretta i 2010 er i datasettet tatt 
med heilt tilbake til 2005. Inndelinga i eksisterande ICES-områder er avhengig av informasjon 
om økonomisk sone. I grunndata kom ikkje sone inn som obligatorisk variable før i 2008. For 
å kunne lage statistikk for nye ICES-områder, har vi etterregistrert informasjon om sone så 
godt som mogleg tilbake til 2005. Setlar som manglar sone eller som har ugyldig 
kombinasjon av fangstfelt og sone, vil ikkje få tildelt kode for områdegruppering. 
Områdegruppering: Nemning for kode for områdegruppering 
Denne variabelen inneheld nemning for kode for ICES-område eller NAFO-område. 
Fram til og med 2004 inneheld variabelen nemning for kodar for ICES-områder som var 
gjeldande fram til 2010. Eksisterande inndeling i ICES-områder som vart oppretta i 2010 er i 
datasettet tatt med heilt tilbake til 2005. Inndelinga i eksisterande ICES-områder er avhengig 
av informasjon om økonomisk sone. I grunndata kom ikkje sone inn som obligatorisk variable 
før i 2008. For å kunne lage statistikk for nye ICES-områder, har vi etterregistrert informasjon 
om sone så godt som mogleg tilbake til 2005. Setlar som manglar sone eller som har ugyldig 
kombinasjon av fangstfelt og sone, vil ikkje få tildelt områdegruppering. 
Hovedområde FAO (kode): Internasjonal fangstregion 
Internasjonal fangstregion (FAO-område). Til dømes angis det nordøstlige Atlanterhav (ICES 
rådgivningsområde) med 27 og det nordvestlige Atlanterhav (NAFOs rådgivningsområde) 
med 21. 
Ikkje komplett utfylt. 
Kode Nemning 
01 Afrika innland 
02 Nord Amerika innland 
03 Sør Amerika innland 
04 Asia innland 
05 Europa innland 
06 Oceania innland 
07 Russland og tidligere sovjetstater
08 Antarktisk innland 
18 Arktiske sjø 
21 Nordvestlige Atlanterhav 
27 Nordøstlige Atlanterhav 
31 Vestlige sentrale Atlanterhav 
12 koder er listet ut her. 
Hovedområde FAO: Nemning for kode for område (FAO) 
Feltet inneheld namn på hovudområde FAO. 
Nord/sør for 62 grader nord: Nord/sør for 62 gradar nord 
Generert ut frå ICES-områder. Nord for 62 gradar nord: ICES Ia, Ib, IIa1, IIa2, IIb1, IIb2. Sør for 
62 gradar nord: ICES IIIa, IVa, IVb, Ivc. 
Fangstdagbok (nummer): Fangstdagboksnummer 
Fangstdagboksnummer, nummer trykt på fysisk fangstdagbok. 
Ikkje komplett utfylt. 
Etter overgang til elektronisk fangstdagbok vert feltet for desse fartøya fylt ut med 99999 
eller liknande standardnummer, då der ikkje er eit dagboksnummer for elektronisk dagbok. 
Fangstdagbok (turnummer): Fangstdagbokas turnummer 
Fangstdagbokas turnummer. 
Ikkje komplett utfylt. 
Elektronisk fangstdagbok inneheldt ikkje begrepet turnummer. Det er difor ikkje mogleg å 
knytte sluttsetel opp mot elektronisk fangstdagbok ved hjelp av dette feltet. 
Landingsdato: Landingsdato 
Landingsdato angitt som den dag landingen er fullført. 
Informasjonen er komplett. Vil i ein del tilfeller kunne innehalde omsetningsdato i staden for 
faktisk landingsdato. NB! Landingsår kan avvike frå fangstår. 
Landingsklokkeslett: Klokkeslett landing 
Klokkeslett lokal tid for fullført landing (timer min). 
Landingsmåned (kode): Nummer på landingsmåned 
Landingsmåned angitt som nummer. 
Landingsmåned: Landingsmåned 
Namn på landingsmåned. 
Landingstidspunkt: Landingstidspunkt 
Landingsdato og klokkeslett. 
Dellanding (signal): Dellevering 
Kode som angir om fangstturen er omfatta av ein eller fleire sluttsetlar. 0 = ingen dellevering 
(det finnes berre éin sluttsetel for denne turen), 1 = dellevering (det finnes minst to 
sluttsetlar for denne turen). 
Usikker kvalitet. 
Neste mottaksstasjon: Neste mottaksstasjon 
Vert nytta ved dellevering; Kode som angir det fysiske anlegget som er neste landingsstad. 
Oppgjeve med Mattilsynets godkjenningsnummer. 
Usikker kvalitet. 
Forrige mottakstasjon: Forrige mottakstasjon 
Brukes ved dellevering; kode som angir det fysiske anlegget som var forrige landingstad. 
Angis med Mattilsynets godkjenningsnummer 
Usikker kvalitet. 
Linjenummer: Linjenummer 
Nummer på varelinje i dokumentet. 
Informasjonen er komplett. 
Art - FDIR (kode): Art/fiskeslag i Fiskeridirektoratets kodeliste 
Kode for art/fiskeslag i Fiskeridirektoratets kodeliste. 
Informasjonen er komplett. 
Kode Nemning 
0101 Niøye 
0102 Gjedde 
0103 Annen ferskvannsbrasme
0104 Karpe 
0105 Suter 
0106 Karuss 
0107 Mort 
0108 Lake 
0109 Abbor 
0111 Gjørs 
0112 Stør, uspes 
0113 Maisild, stamsild 
12 koder er listet ut her. 
Art - FDIR: Artsnamn i Fiskeridirektoratets kodeliste 
Namn på art/fiskeslag i samsvar med Fiskeridirektoratets kodeliste. 
Art (kode): Kode for art/fiskeslag 
Dette er ei samanstilling av artar i Fiskeridirektoratets kodeliste. Dei fleste artane i kodelista 
finnes også på dette nivået, men nokre er slått saman og vises som gruppe. Bakgrunnen for 
at vi har valt å innføre dette nivået er at nokre av artane i Fiskeridirektoratets kodeliste vert 
brukt ulikt av dei ulike fiskesalslaga. 
Art: Nemning av art/fiskeslag 
Dette er ei samanstilling av artar i Fiskeridirektoratets kodeliste. Dei fleste artane i kodelista 
finnes også på dette nivået, men nokre er slått saman og vises som gruppe. Bakgrunnen for 
at vi har valt å innføre dette nivået er at nokre av artane i Fiskeridirektoratets kodeliste vert 
brukt ulikt av dei ulike fiskesalslaga. 
Art - gruppe (kode): Kode for gruppe for art/fiskeslag. 
Kode for grupper av art/fiskeslag. 
Art - gruppe: Nemning av gruppe for art/fiskeslag. 
Nemning av kodar for grupper av art/fiskeslag. 
Art - hovedgruppe (kode): Kode for hovedgrupper for art 
Kode for hovedgruppe for art/fiskeslag. 
Art - hovedgruppe: Beskrivelse av hovedgrupper for art 
Namn på hovedgruppe for art/fiskeslag. 
Art FAO (kode): Artskode FAO 
Artskodar henta frå FAOs (Food and Agriculture Organization of the United Nations) 
kodeliste. 
Art FAO: Nemning for artskode (FAO) 
Namn på art/fiskeslag i samsvar med kodelista til FAO (Food and Agriculture Organization of 
the United Nations). 
Produkttilstand (kode): Produkttilstand 
Kode for produkttilstand. Med dette meiner ein fiskens tilstand slik den er når den vert landa 
og seier noko om fisken er heil eller grad av endring frå heil rå fisk. Produkttilstand omfattar 
også dei ulike biprodukta av fisken som vert landa.
Informasjonen er komplett. 
Kode Nemning 
100 Levende 
110 Rund 
111 Hodekappet 
112 Rund med rogn 
115 Våt tilstand 
210 Sløyd med hode 
211 Sløyd uten hode, rundsnitt 
212 Sløyd uten hode, uten ørebein
213 Sløyd uten hode, uten spord 
214 Sløyd uten hode, rettsnitt 
215 Sløyd uten hode, uten buk 
216 Sløyd m/hode og uten spord 
12 koder er listet ut her. 
Produkttilstand: Nemning for kode for produkttilstand 
Nemning av produkttilstand. 
Konserveringsmåte (kode): Konserveringsmåte 
Kode for konserveringsmåte. Her angis korleis fisken er konservert ved landings-
/leveringstidspunktet. Til dømes fersk, frossen, tørka, salta o.s.b. 
Relativt store andelar er ført som uoppgjeve. Eit stort salslag nytta i mange år mest berre 
kode for uspesifisert. Kvaliteten er betra i nyare år. 
Kode Nemning 
00 Uspesifisert 
01 Ensilert 
02 Fersk/ukonservert
03 Fersk saltkokt 
04 Fersk sjøkokt 
05 Frossen 
06 Frossen saltkokt 
07 Frossen sjøkokt 
08 Gravet 
09 Iset 
10 Rfw 
11 Rsw 
12 koder er listet ut her. 
Konserveringsmåte: Nemning for kode for konserveringsmåte 
Feltet inneheld nemning for konserveringsmåte. 
Landingsmåte (kode): Leveringsmåte 
Kode for leveringsmåte. Angir korleis fisken er oppbevart ved landings-/leveringstidspunktet. 
Til dømes om den er i kassar, emballert, levert i tank, i lås m.m. 
Kode Nemning 
1 i lås 
10 i merd, oppfôret 
11 tank / bil 
12 kar 
13 container 
14 Oppsamlingsfartøy 
15 Fra merd, uten fôring
2 bulk 
3 tank / båt 
4 kasser/tønner 
5 brønnbåt 
6 kvase 
12 koder er listet ut her. 
Landingsmåte: Nemning for kode for landingsmåte 
Feltet inneheld nemning for landingsmåte. 
Kvalitet (kode): Kvalitet 
Kode for kvalitet. Her angis ei vurdering og klassifisering av fisken ut i frå kjøparane sine 
lokale vurderingar i det enkelte salslagsdistrikt. 
Definisjonen av kvalitet er ikkje standardisert. Kodane som vert nytta må tilpassast det 
enkelte salslags kvalitetsomgrep. I ulike salslagsregionar og innan ulike verksemder nyttar 
ein av tradisjon ulike omgrep for same kvalitetsgrad. Denne variabelen er ikkje i bruk for 
pelagisk sektor, her angis utelukkande kode for uoppgjeve. 
Kode Nemning 
10 Ekstra 
11 Prima 
12 Superior 
20 A 
21 Blank 
30 B 
31 Sekunda 
32 Afrika 
33 Frostskadet fos 
34 Gul 
35 Produksjonsrogn
36 Knekt krabbe 
12 koder er listet ut her. 
Kvalitet: Nemning for kode for kvalitet 
Feltet inneheld nemning for kvalitet. 
Størrelsesgruppering (kode): Storleik/sortiment 
Kode for storleik/sortiment. Her angis den storleikssortering som vert brukt på den 
kommersielle marknaden. Storleik kan angis etter ulike målemetodar. Koden består av i alt 7 
siffer. Første siffer angir kode for registreringsmetoden for storleik, dei tre neste siffera angir 
nedre grense for storleiken og dei tre siste siffera gir den øvre grensa. Moglege 
registreringsmetodar er angitt i kodetabell. 
Der er ingen harmonisering av bruken av dette feltet. Kvart enkelt salslag har sine 
grupperingar på storleik, og desse kan vidare variera alt etter type produkt og mellom år. 
Kode Nemning 
1 Stk pr kg metode 
2 millimetermetode 
3 uoppgitt størrelse 
4 hektogrammetode 
5 blandet angivelse (fra i mm, til i hg)
6 blandet angivelse (fra i hg, til i mm)
7 grammetode 
8 metermetode 
9 kilogrammetode 
Anvendelse (kode): Bruken av fangsten/produktet 
Kode som angir kva produktet er tenkt brukt til (intendert bruk) på omsetningstidspunktet. 
Ingen etterfølgande oppdatering i forhold til faktisk bruk sjølv om dette skulle visa seg å 
verta ein annan bruk enn intendert. 
Til dels dårleg kvalitet på detaljnivå. Bør først og fremst nyttast til å skilje mellom 
konsum/ikkje konsum ved hjelp av grupperingstabellar. 
Kode Nemning 
090 Oppdrett 
091 Avlusing 
100 Fersk (konsum) 
110 Fersk eksport (også ising) 
111 Fersk innenlands (også ising)
112 Fersk rensing 
120 Fersk filet 
130 Fersk agn 
200 Frysing 
210 Rundfrysing 
211 Frysing konsum eksport 
212 Frysing konsum innenlands 
12 koder er listet ut her. 
Anvendelse: Nemning for kode for bruk av fangsten/produktet 
Feltet inneheld nærare beskriving/ledetekst til kode for intendert bruk av 
fangsten/produktet. 
Anvendelse hovedgruppe (kode): Kode for hovudgruppe for bruk av fangsten/produktet 
Kode for gruppering av kva fangsten/produktet er tenkt brukt til (intendert bruk). 
Anvendelse hovedgruppe: Nemning for hovudgruppe for bruk av fangsten/produktet 
Feltet inneheld nærare beskriving/ledetekst til kode for hovudgruppe for intendert bruk av 
fangsten/produktet. 
Antall stykk: Antall stykk/antall fisk 
Antall fisk levert. For nokre fiskeri skal antall stykk oppgis på seddel. 
Ikkje komplett informasjon. Varierande kvalitet over tid. 
Bruttovekt: Bruttovekt 
Bruttovekt i kg viser samla vekt av fisk med vatn, emballasje og pallar. 
Innført i 2004 men ikkje tatt komplett i bruk dei første åra. Også noko usikker kvalitet 
seinare år. I 2013 vart det innført automatisk kontroll som sikrar teknisk korrekt utfylling av 
feltet (dvs. det må ha verdi høgare eller lik produktvekt på same varelinje). 
Produktvekt: Produktvekt 
Kvantum i netto produktvekt i kg. 
Informasjonen er komplett. 
Produktvekt over kvote: Produktvekt over kvote 
Kvantum over kvote i kg produktvekt. Vert utrekna som ein del av salslagas 
kontrollverksemd. Gjeld også kvantum som er vedtatt ulovlig av fiskeristyresmaktene. 
Verdi av kvantum over kvote skal inndragast. Dette gjeld også inndraging som følgje av 
vedtak utført av andre. (Mengde i dette feltet skal ikkje endre innhaldet i feltet Produktvekt.) 
Ikkje komplett utfylt 
Rundvekt over kvote: Rundvekt over kvote 
Kvantum over kvote i rundvekt. Produktvekt over kvote * aktuell omrekningsfaktor. 
Ikkje komplett utfylt. 
Rundvekt: Rundvekt 
Rundvekt i kg, også omtala som fiskens levande vekt. Vert berekna ved å ta Produktvekt * 
aktuell omrekningsfaktor. Vil vera 0 for biprodukt.
Enhetspris for kjøper: Kjøpars pris pr måleeining 
Kjøpars pris pr måleeining er den pris som kjøpar betaler for vara. 
Vil vera 0 på alle landingssetlar. Det vil også kunne vera sluttsetlar som har pris 0. Ikkje 
komplett for alle salslag bakover i tid. 
Data for siste 12 månader (løpande) er definert som sensitiv informasjon, og er ikkje med i 
datasettet. 
Beløp for kjøper: Varelinjebeløp kjøpar 
Varelinjebeløp kjøpar er kva kjøpar har betalt for det gitte kvantum fisk han har kjøpt. 
Beløpet er eit produkt av produktvekts kvantum og kjøpars pris per måleeining. 
Meirverdiavgift skal ikkje vera trekt frå. 
Vil vera 0 på alle landingssetlar. Det vil også kunne vera sluttsetlar som har verdi 0. Ikkje 
komplett for alle salslag bakover i tid. 
Data for siste 12 månader (løpande) er definert som sensitiv informasjon, og er ikkje med i 
datasettet. 
Enhetspris for fisker: Fiskars pris pr måleeining 
Fiskars pris pr måleeining er den pris fiskar får betalt for vara, før lagsavgift er trekt i frå. Pris
til fiskar vil normalt vera lik den pris kjøpar må betale. Unntaka er når det vert foretatt ei 
prisutjamning mellom fiskarar og ved landing i utlandet kor fiskar kan vera pålagt å bera ei 
større del av utgiftene ved lossing samanlikna med norske forhold. 
Vil vera 0 på alle landingssetlar. Det vil også kunne vera sluttsetlar som har pris 0. 
Data for siste 12 månader (løpande) er definert som sensitiv informasjon, og er ikkje med i 
datasettet. 
Beløp for fisker: Varelinjebeløp fiskar 
Varelinjebeløp fiskar er kva fiskar får utbetalt for det gitte kvantum fisk han har landa. 
Beløpet skal framkomme som eit produkt av produktvekts kvantum og pris fiskar per 
måleeining. Meirverdiavgift skal ikkje vera trekt frå. 
Vil vera 0 på alle landingssetlar. Det vil også kunne vera sluttsetlar som har verdi 0. 
Data for siste 12 månader (løpande) er definert som sensitiv informasjon, og er ikkje med i 
datasettet. 
Støttebeløp: Støttebeløp 
Støttebeløp i kr er støttebeløp til fiskar. Skal vera spesifisert i NOK u/meirverdiavgift per 
varelinje, dvs. før meirverdiavgift er trekt i frå. (Beløpet i dette feltet skal ikkje endre 
innhaldet i felta Enhetspris for fisker eller Beløp for fisker.) 
Data for siste 12 månader (løpande) er definert som sensitiv informasjon, og er ikkje med i 
datasettet. 
Lagsavgift: Lagsavgift 
Lagsavgift (beløp) i kr er den avgift fiskar må betale til salslaget. Lagsavgifta vert fastsett av 
det enkelte salslag, og kan variere for ulike produkt innan eit salslag. 
Data for siste 12 månader (løpande) er definert som sensitiv informasjon, og er ikkje med i 
datasettet. 
Informasjonen er komplett. 
Inndradd fangstverdi: Inndradd fangstverdi 
Inndradd fangstverdi i kr er den verdi av fangsten som vert inndradd frå fiskar på bakgrunn 
av saksbehandlingsvedtak om brot på Havressurslova. (Beløpet i dette feltet skal ikke endre 
innhaldet i felta Enhetspris for fisker eller Beløp for fisker.) 
Data for siste 12 månader (løpande) er definert som sensitiv informasjon, og er ikkje med i 
datasettet. 
Ikkje komplett utfylt. 
Etterbetaling: Etterbetaling 
Etterbetalt fangstverdi i kr. Beløp fiskar får utbetalt av salslaget på grunn av 
forretningsmessige forhold mellom fiskar og salslag. (Beløpet i dette feltet skal ikke endre 
innholdet i feltene Enhetspris for fisker eller Beløp for fisker.) 
Data for siste 12 månader (løpande) er definert som sensitiv informasjon, og er ikkje med i 
datasettet. 
Fangstverdi: Fangstverdi 
Frå og med 2018 har fangstverdi fått ny definisjon. Dette er gjort då vi meiner dette vil gje eit 
betre bilete av verdiskapinga i fisket, samt at ny definisjon er meir i samsvar med 
verdibegrep som nyttast i andre sammenhengar. 
- Definisjon 2018-: 
- Beløp for fisker + Etterbetaling 
- Definisjon 2000-2017 (utbetalt verdi): 
- Beløp for fisker + Støttebeløp - Lagsavgift - Inndradd fangstverdi + Etterbetaling 
Fangstverdi vil vere 0 på alle landingssetlar. Det vil også kunne vere sluttsetlar som har verdi 
0. 
Data for siste 12 månader (løpande) er definert som sensitiv informasjon, og er ikkje med i 
datasettet. 
Oppdateringstidspunkt: Oppdateringstidspunkt 
Tidspunkt for siste oppdatering av data. Dato og klokkeslett.