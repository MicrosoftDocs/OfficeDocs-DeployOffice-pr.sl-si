---
title: Obvezni diagnostični podatki za Office
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Skrbnikom za Office so na voljo informacije o obveznih diagnostičnih podatkih v sistemu Office ter seznam dogodkov in podatkovnih polj.
hideEdit: true
ms.openlocfilehash: a5770d3ed30f86dfbf1cb1dfc4a45bbb15179da8
ms.sourcegitcommit: 4abc1462753e6cb5c01642c9711d19b220dadac0
ms.translationtype: HT
ms.contentlocale: sl-SI
ms.lasthandoff: 10/03/2019
ms.locfileid: "37386981"
---
# <a name="required-diagnostic-data-for-office"></a>Obvezni diagnostični podatki za Office

> [!IMPORTANT]
> Informacije v tem članku veljajo za različico 1904 ali novejšo različico sledeče Officeove odjemalske programske opreme, ki je nameščena v računalniku s sistemom Windows:
> - Office 365 ProPlus in Office 365 Business
> - Office 365 Personal, Office 365 Home ali druge različice Officea, ki so del naročnine na Office 365.
> - Project in Visio, ki sta vključena v nekatere naročniške pakete, kot sta paketa Project Online Professional ali Visio Online 2.
>
> Informacije veljajo tudi za različico 16.28 ali novejšo od teh aplikacij sistema Office za Mac: Excel, Outlook, OneNote, PowerPoint in Word.

Diagnostični podatki so uporabljeni za zaščito, posodobitev ter zaznavanje in odpravljanje težav v Officeu, poleg tega pa tudi za izboljšanje izdelka. Ti podatki ne vključujejo uporabniškega imena ali e-poštnega naslova, vsebine datotek uporabnika ali informacij o aplikacijah, ki niso del Officea.

Diagnostični podatki o uporabljeni programski opremi odjemalca za Office v računalnikih z nameščenim sistemom Windows so bili zbrani in poslani Microsoftu. Nekateri diagnostični podatki so obvezni, medtem ko so drugi izbirni. S kontrolniki zasebnosti lahko izbirate, ali nam boste poslali zahtevane ali izbirne diagnostične podatke, kot so na primer nastavitve pravilnikov za organizacijo. S Pregledovalnikom diagnostičnih podatkov lahko vidite, kateri diagnostični podatki so nam poslani.

***Obvezni diagnostični podatki*** vključujejo najmanjšo nujno količino podatkov, potrebnih za zagotavljanje varnosti, posodobitev in pričakovanega delovanja Officea v napravi, v kateri je sistem nameščen.

Z obveznimi diagnostičnimi podatki prepoznate težave z Officeom, ki so morda povezane z napravo ali konfiguracijo programske opreme. Z njimi lahko na primer prepoznate pogoste zrušitve novo uvedenih Officeovih funkcij v določeni različici operacijskega sistema oz. onemogočene Officeove funkcije. Z obveznimi diagnostičnimi podatki lahko hitreje zaznamo, diagnosticiramo in odpravimo te težave ter tako zmanjšamo njihov vpliv na uporabnike ali organizacije.

Če želite izvedeti več informacij o diagnostičnih podatkih, preberite te članke:

- [Izbirni diagnostični podatki za Office](optional-diagnostic-data.md)
- [Uporaba pregledovalnika diagnostičnih podatkov z Officeom](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

Če ste skrbnik v svoji organizaciji, vas bo morda zanimalo to:

- [Pregled kontrolnikov zasebnosti za Office 365 ProPlus](overview-privacy-controls.md)
- [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office365 ProPlus](manage-privacy-controls.md)
- [Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office za Mac](mac-privacy-preferences.md)

## <a name="categories-data-subtypes-events-and-data-fields-for-required-diagnostic-data"></a>Kategorije, podatkovni podtipi, dogodki in podatkovna polja za obvezne diagnostične podatke

Obvezni diagnostični podatki so organizirani v kategorije in podatkovne podtipe. Posamezni podatkovni tipi so razvrščeni v dogodke, ki vključujejo določena podatkovna polja.

V spodnji tabeli je na voljo seznam kategorij za obvezne diagnostične podatke. Navedeni so podatkovni podtipi znotraj posameznih kategorij ter opisi fokusa posameznih podatkovnih podtipov. Navedene so tudi povezave do posameznih razdelkov podatkovnih podtipov, kjer so na voljo te informacije:

- Seznam dogodkov v določenem podatkovnem podtipu
- Opis posameznih dogodkov
- Seznam podatkovnih polj v posameznih dogodkih
- Opis posameznih podatkovnih polj

| **Kategorija**       | **Podatkovni podtip**| **Opis**    |
| ---------- | ------------- | ---- |
| **Nastavitev programske opreme in inventar** | [Nastavitev Officea in inventar](#office-setup-and-inventory-subtype)   | Nameščeni izdelek, različica in stanje namestitve.  |
| | [Konfiguracija dodatka za Office](#office-add-in-configuration-subtype)  | Dodatki programske opreme in nastavitve.     |
| | [Varnost](#security-subtype)  | Stanje napak dokumentov, funkcij in dodatkov, ki lahko ogrozijo varnost in pripravljenost izdelka za posodobitve.  |
| **Uporaba izdelka in storitev**    | [Uspešnost izvajanja funkcije aplikacije](#application-feature-success-subtype)   | Uspešnost delovanja aplikacije. Omejeno na odpiranje in zapiranje aplikacij in dokumentov, urejanje datoteke ter skupno rabo datotek (sodelovanje). |
| | [Stanje in zagon aplikacije](#application-status-and-boot-subtype)    | Prepoznavanje, ali so bili izvedeni določeni dogodki funkcij, kot je zagon ali ustavitev, oz. če se funkcije izvajajo.   |
| | [Konfiguracija za dostopnost sistema Office](#office-accessibility-configuration-subtype)  | Officeove funkcije dostopnosti       |
| | [Zasebnost](#privacy-subtype)| Nastavitve zasebnosti za Office|
| **Učinkovitost delovanja izdelka in storitve**       | [Nepričakovano zapiranje aplikacije (zrušitev)](#unexpected-application-exit-crash-subtype)  | Nepričakovana zapiranja aplikacije in stanje aplikacije, ko pride do tega.    |
|  | [Učinkovitost delovanja funkcije aplikacije](#application-feature-performance-subtype)  | Slab odzivni čas ali slaba učinkovitost delovanja za scenarije, kot sta zagon aplikacije ali odpiranje datoteke. |
|  | [Napaka dejavnosti aplikacije](#application-activity-error-subtype)   | Napake delovanja funkcij ali uporabniške izkušnje.  |
| **Povezljivost in konfiguracija naprave** | [Povezljivost in konfiguracija naprave](#device-connectivity-and-configuration-subtype) | Stanje omrežne povezave in nastavitve naprave, kot je pomnilnik. |


> [!NOTE]
> - Kategorije so prikazane v Pregledovalniku diagnostičnih podatkov, medtem ko podatkovni tipi niso prikazani.
> - Podatkovno polje, označeno *Zastarelo*, je bilo oz. bo v kratkem odstranjeno iz obveznih diagnostičnih podatkov. Nekatera od teh podatkovnih polj so podvojena zaradi posodobitve diagnostičnih podatkov in so uporabljena za zagotavljanje nemotenega delovanja storitve ter ustvarjanje poročil o nadzoru dinamičnih diagnostičnih podatkov.

## <a name="categories-and-data-fields-that-are-common-for-all-events"></a>Skupne kategorije in podatkovna polja za vse dogodke

Nekatere informacije o dogodkih so skupne za vse dogodke, ne glede na kategorije ali podatkovne podtipe. Te skupne informacije, ki jih včasih imenujemo *podatkovne pogodbe*, so organizirane v kategorije. Posamezne kategorije vključujejo polja, ta polja pa vsebujejo metapodatke in lastnosti posameznih dogodkov. Te informacije si lahko ogledate s Pregledovalnikom diagnostičnih podatkov.

Kategorije zbranih informacij o dogodkih lahko razdelite v dve skupini:

  - [Skupne informacije za vse dogodke](#information-common-to-all-events)
  - [Informacije, ki posebej podpirajo zbiranje diagnostičnih podatkov](#information-that-specifically-supports-diagnostic-data-collection)

### <a name="information-common-to-all-events"></a>*Skupne informacije za vse dogodke*

Informacije, skupne za vse dogodke, so zbrane v teh kategorijah.

#### <a name="app"></a>Aplikacija 

Informacije o aplikaciji. Vsa polja so nespremenljiva za vse seje določene različice aplikacije.

Ta kategorija vsebuje ta polja:

  - **Branch** – Veja posamezne graditve. Omogoča, da določimo vrsto veje posamezne graditve ter tako izberemo ustrezne rešitve.
  - **InstallType** – Popisovalnik, ki določa način uporabnikove namestitve aplikacije. Omogoča prepoznavanje morebitnih težav določenih namestitvenih mehanizmov, ki jih v drugih ni mogoče zaznati.
  - **Name** – Ime aplikacije, ki ustvarja podatke. Omogoča, da določimo, v kateri aplikaciji je prišlo do težave in tako pripravimo ustrezno rešitev.
  - **Platform** – Širša klasifikacija platforme, v kateri se izvaja aplikacija. Omogoča, da določimo, v kateri platformi je prišlo do težav ter te težave razvrstimo po pomembnosti.
  - **Version** – Različica aplikacije. Omogoča, da določimo, v katerih različicah izdelka je prišlo do težave ter te težave razvrstimo po pomembnosti.

#### <a name="client"></a>Odjemalec 

Identifikator, povezan s primerkom sistema Office v napravi. Konstanta za vse seje vseh aplikacij določene različice namestitve za zbirke več aplikacij oz. konstanta za vse seje določene različice aplikacije.

Ta kategorija vsebuje ta polja:

  - **Id** – Enolični identifikator, ki je dodeljen odjemalcu ob času namestitve Officea. Omogoča, da določimo, ali težave vplivajo na izbran nabor namestitev in koliko uporabnikov je zaznalo te težave.

#### <a name="consent"></a>Soglasje

Informacije o uporabnikovem soglasju za uporabo diagnostičnih podatkov in povezanih izkušenj.

Ta kategorija vsebuje ta polja:

  - **UserCategory** – Določa vrsto uporabnika, ki je podelil soglasje. MSAUser, AADUser ali LocalDeviceUser.

  - **DiagnosticConsentLevel** – Označuje raven soglasja za uporabo diagnostičnih podatkov, ki ga je podelil uporabnik.

  - **DiagnosticConsentSourceLocation** – Označuje, kako je uporabnik soglašal z uporabo diagnostičnih podatkov.

  - **DiagnosticConsentConsentTime** – Označuje, kdaj je uporabnik soglašal z uporabo diagnostičnih podatkov. Datum bo prikazan kot človeško berljiv datum ali kot strojno kodiran datum, ki je videti kot veliko število.

  - **ServiceConnectionState** – Označuje, ali je uporabnik izbral, da želi oz. ne želi uporabljati vse povezane izkušnje.

  - **ServiceConnectionStateSourceLocation** – Označuje, kako je uporabnik izbral možnost uporabe vseh povezanih izkušenj.

  - **ServiceConnectionStateConsentTime** – Označuje, kdaj je uporabnik izbral, ali želi uporabljati vse povezane izkušnje. Datum bo prikazan kot človeško berljiv datum ali kot strojno kodiran datum, ki je videti kot veliko število.

  - **ControllerConnectedServicesState** – Označuje, ali ima uporabnik dostop do izbirnih povezanih izkušenj.

  - **ControllerConnectedServicesStateSourceLocation** – Označuje, kako je uporabnik izbral uporabo izbirnih povezanih izkušenj.

  - **ControllerConnectedServicesStateConsentTime** – Označuje, kdaj je uporabnik izbral stanje izbirnih povezanih izkušenj. Datum bo prikazan kot človeško berljiv datum ali kot strojno kodiran datum, ki je videti kot veliko število.

  - **UserContentDependentState** – Označuje, ali je uporabnik omogočil oz. onemogočil povezane izkušnje, ki analizirajo vsebino.

  - **UserContentDependentStateSourceLocation** – Označuje, kako je uporabnik omogočil oz. onemogočil povezane izkušnje, ki analizirajo vsebino.

  - **UserContentDependentStateConsentTime** – Označuje, kdaj je uporabnik omogočil oz. onemogočil povezane izkušnje, ki analizirajo vsebino. Datum bo prikazan kot človeško berljiv datum ali kot strojno kodiran datum, ki je videti kot veliko število.

  - **DownloadContentState** – Označuje, ali je uporabnik omogočil oz. onemogočil povezane izkušnje, ki prenašajo spletno vsebino.

  - **DownloadContentStateSourceLocation** – Označuje, kako je uporabnik omogočil oz. onemogočil povezane izkušnje, ki prenašajo spletno vsebino.

  - **DownloadContentStateConsentTime** – Označuje, kdaj je uporabnik omogočil oz. onemogočil povezane izkušnje, ki prenašajo spletno vsebino. Datum bo prikazan kot človeško berljiv datum ali kot strojno kodiran datum, ki je videti kot veliko število.

#### <a name="device"></a>Naprava 

Informacije o operacijskem sistemu in graditvi.

Ta kategorija vsebuje ta polja:

  - **OsBuild** – Številka graditve operacijskega sistema, ki je nameščena v napravi. Omogoča, da določimo, ali težave različno vplivajo na posamezne servisne pakete oz. različice določenega operacijskega sistema ter jih razvrstimo po pomembnosti.

  - **OsVersion** – Glavna različica operacijskega sistema, ki je nameščena v napravi. Omogoča, da določimo, ali nekatere težave vplivajo na določeno različico operacijskega sistema bolj kot druge ter jih razvrstimo po pomembnosti.

#### <a name="legacy"></a>Starejša različica 

Vsebuje ID aplikacije in različico operacijskega sistema za združljivost z obstoječimi starejšimi postopki zbiranja.

Ta kategorija vsebuje ta polja:

  - **AppId** – Vrednost popisovalnika, ki označuje, katera aplikacija posreduje podatke. Omogoča, da določimo, v kateri aplikaciji je prišlo do težave in tako pripravimo ustrezno rešitev.

  - **OsEnv** – Popisovalnik, ki določa, v katerem operacijskem sistemu se izvaja seja. Omogoča, da določimo, v katerem operacijskem sistemu je prišlo do težav ter te težave razvrstimo po pomembnosti.

#### <a name="release"></a>Izdaja 

Informacije, povezane s kanalom izdaje. Vsa polja so nespremenljiva za vse seje vseh aplikacij določene različice namestitve. Določa skupino vseh naprav znotraj ene faze cikla izdaje izdelka.

Ta kategorija vsebuje ta polja:

  - **Audience** – Določa podskupino občinstva določene skupine občinstva. Omogoča spremljanje podmnožic skupin občinstva za ocenjevanje razširjenosti in ravni pomembnosti težav.

  - **AudienceGroup** – Določa krog, kjer so ustvarjeni podatki. Omogoča postopno uvajanje funkcij in prepoznavanje morebitnih težav, preden te dosežejo večji del uporabnikov.

  - **Channel** – Kanal, v katerem je izdan določen izdelek. Omogoča, da prepoznamo, ali določene težave različno vplivajo na kanale za uvajanje.

  - **Fork** – Določa vejitev izdelka. Omogoča mehanizem za združevanje podatkov v naboru številk graditve za prepoznavanje težav, povezanih z določeno izdajo.

#### <a name="session"></a>Seja 

Informacije o seji obdelave. Vsa polja so nespremenljiva za to sejo.

Ta kategorija vsebuje ta polja:

  - **ABConfigs** – Določa nabor pilotnih različic, ki se izvajajo v določeni seji. Omogoča, da ugotovimo, katere pilotne različice se izvajajo v seji ter tako določimo, ali je pilotna različica izvor uporabnikovih težav.

  - **EcsETag** – Indikator sistema pilotnih različic, ki predstavlja pilotne različice, poslane v računalnik. Omogoča, da določimo, katere pilotne različice morda vplivajo na določeno sejo.

  - **Flags** – Zastavice za sledenje bitne maske celotne seje, trenutno osredotočene predvsem na možnosti vzorčenja in diagnostičnih podatkov. Omogoča nadziranje načina delovanja določene seje v primerjavi z diagnostičnimi podatki, ki jih ustvari seja.

  - **Id** – Enolično identificira določeno podatkovno sejo. Omogoča, da določimo vpliv težav tako, da ocenimo število prizadetih sej in prepoznamo morebitne skupne značilnosti teh sej.

  - **ImpressionId** – Določa nabor pilotnih različic, ki se izvajajo v določeni seji. Omogoča, da ugotovimo, katere pilotne različice se izvajajo v seji ter tako določimo, ali je pilotna različica izvor uporabnikovih težav.

  - **MeasuresEnabled** – Zastavica, ki označuje, ali so podatki trenutne seje vzorčni. Omogoča, da določimo, kako statistično oceniti podatke, zbrane v določeni seji.

  - **SamplingClientId** – ID odjemalca, s katerim določimo, ali je del vzorčenja. Omogoča, da določimo, zakaj so bile posamezne seje vključene oz. izključene iz vzorčenja.

#### <a name="user"></a>Uporabnik

Na voljo so informacije o najemniku za inventarne številke komercialne programske opreme.

Ta kategorija vsebuje ta polja:

  - **PrimaryIdentityHash** – Identifikator s psevdonimom, ki označuje trenutnega uporabnika.

  - **PrimaryIdentitySpace** – Vrsta identitete, ki jo vsebuje polje »PrimaryIdentityHash«. MASCID, OrgIdCID ali UserObjectId.

  - **TenantGroup** – Vrsta najemnika, kamor sodi naročnina. Omogoča, da razvrstimo težave in določimo, ali je težava razširjena oz. omejena na določen nabor uporabnikov.

  - **TenantId** – Najemnik, s katerim je povezana uporabnikova naročnina. Omogoča, da razvrstimo težave in določimo, ali je težava razširjena ali omejena na določen nabor uporabnikov oz. določenega najemnika.

### <a name="information-that-specifically-supports-diagnostic-data-collection"></a>*Informacije, ki posebej podpirajo zbiranje diagnostičnih podatkov*

Informacije, ki posebej podpirajo zbiranje diagnostičnih podatkov, so zbrane v teh kategorijah.

#### <a name="activity"></a>Dejavnost

Informacije, ki omogočajo razumevanje uspešno izvedenega dogodka zbiranja.

Ta kategorija vsebuje ta polja:

  - **AggMode** – Sporoči sistemu, kako naj združi rezultate dejavnosti. Omogoča, da zmanjšamo količino prenesenih informacij iz uporabnikovega računalnika tako, da združimo rezultate dejavnosti v en dogodek, ki ga redno pošiljamo.

  - **Count** – Število izvajanj določene dejavnosti, če skupno število označuje združeni dogodek. Omogoča, da določimo, kolikokrat je bila dejavnost uspešno oz. neuspešno izvedena glede na način združevanja dejavnosti.

  - **CV** – Vrednost, ki določa odnos med dejavnostmi in poddejavnostmi. Omogoča, da lahko znova ustvarimo odnos med ugnezdenimi dejavnostmi.

  - **Duration** – Trajanje izvajanja dejavnosti. Omogoča, da določimo težave z učinkovitostjo delovanja, ki negativno vplivajo na uporabniško izkušnjo.

  - **Result**.**Code** – Koda, ki jo določa aplikacija, za prepoznavanje določenih rezultatov. Omogoča, da določimo podrobnosti napake, kot je koda napake, s katero lahko razvrstimo težave in jih odpravimo.

  - **Result.Tag** – Oznaka za celo število, ki določa lokacijo v kodi, kjer je bil ustvarjen rezultat. Omogoča, da natančno določimo lokacijo v kodi, kjer je bil ustvarjen rezultat, ter tako razvrstimo napake.

  - **Result**.**Type** – Vrsta kode rezultata. Določa vrsto poslane kode rezultata, tako da lahko ustrezno obravnavamo vrednost.

  - **Success** – Zastavica, ki označuje, ali je bila dejavnost uspešna oz. neuspešna. Omogoča, da določimo, ali so bila uporabnikova dejanja v izdelku uspešno oz. neuspešno izvedena. Prepoznamo lahko težave, ki vplivajo na uporabnika.

#### <a name="application"></a>Aplikacija 

Informacije o namestitvi aplikacije, kjer se zbirajo dogodki.

Ta kategorija vsebuje ta polja:

  - **Architecture** – Arhitektura aplikacije. Razvrstimo lahko napake, ki so morda značilne za določeno arhitekturo aplikacije.

  - **Click2RunPackageVersion** – Številka različice paketa »zagon s klikom«, s katerim ste namestili aplikacijo. Omogoča, da določimo, s katero različico namestitvenega programa je bil nameščen Office ter tako prepoznamo težave, povezane z namestitvijo.

  - **DistributionChannel** – Kanal, v katerem je bila uvedena aplikacija. Omogoča, da razdelimo dohodne podatke na particije ter tako ugotovimo, ali težave vplivajo na občinstvo.

  - **InstallMethod** – Ali je bila trenutna graditev Officea nadgrajena iz starejše graditve, je bila povrnjena v starejšo graditev oz. gre za novo namestitev.

  - **IsClickToRunInstall** – Zastavica, ki označuje, ali gre za namestitev »zagon s klikom«. Omogoča, da določimo težave, ko so morda značilne za namestitveni mehanizem »zagon s klikom«.

  - **IsDebug** – Zastavica, ki označuje, ali je to graditev Officea za odpravljanje napak. Omogoča, da določimo, ali so vir težav graditve za odpravljanje težav, ki lahko delujejo na drugačen način.

  - **IsInstalledOnExternalStorage** – Zastavica, ki označuje, ali je bil Office nameščen v zunanjo napravo za shranjevanje. Določimo lahko, ali je težavam mogoče slediti v mesto zunanje shrambe.

  - **IsOEMInstalled** – Zastavica, ki označuje, ali je Office namestil proizvajalec strojne opreme. Določimo lahko, ali je aplikacijo namestil proizvajalec strojne opreme ter tako razvrstimo in prepoznamo težave.

  - **PreviousVersion** – Različica Officea, ki je bila predhodno nameščena v računalniku. Omogoča povrnitev na prejšnjo različico, če ima trenutna različica težave.

  - **ProcessFileName** – Ime datoteke aplikacije. Omogoča določitev imena izvedljive datoteke, ki ustvarja podatke, saj je za isto ime aplikacije lahko na voljo več različnih imen datotek postopka.

#### <a name="client"></a>Odjemalec

Informacije o odjemalcu za Office.

Ta kategorija vsebuje ta polja:

  - **FirstRunTime** – Prvo izvajanje odjemalca. Omogoča nam vpogled v podatke o tem, koliko časa ima odjemalec že nameščen Office.

#### <a name="device"></a>Naprava

Informacije o konfiguraciji naprave in zmogljivostih.

Ta kategorija vsebuje ta polja:

  - **DigitizerInfo** – Informacije o digitalizatorju, ki ga uporablja računalnik. Omogoča razvrstitev podatkov glede na osrednjo napravo.

  - **FormFactor** – Določa dimenzije naprave, ki pošilja podatke. Omogoča razvrstitev podatkov glede na osrednjo napravo.

  - **FormFactorFamily** – Določa dimenzije naprave, ki pošilja podatke. Omogoča razvrstitev podatkov glede na osrednjo napravo.

  - **HorizontalResolution** – Vodoravna ločljivost zaslona naprav. Omogoča razvrstitev podatkov glede na osrednjo napravo.

  - **Id** – Enolični identifikator naprave. Omogoča, da lahko porazdelimo težave v več napravah.

  - **IsEDPPolicyEnabled** – Zastavica, ki označuje, ali je v računalniku omogočena izboljšana zaščita podatkov. Omogoča razvrstitev podatkov glede na osrednjo napravo.

  - **IsTerminalServer** – Zastavica, ki določa, ali je računalnik terminalski strežnik. Omogoča razvrstitev podatkov glede na osrednjo napravo.

  - **Manufacturer** – Proizvajalec naprave. Omogoča razvrstitev podatkov glede na osrednjo napravo.

  - **Model** – Model naprave. Omogoča razvrstitev podatkov glede na osrednjo napravo.

  - **MotherboardUUIDHash** – Zgoščena vrednost enoličnega identifikatorja za matično ploščo. Omogoča razvrstitev podatkov glede na osrednjo napravo.

  - **Name** – Ime naprave. Omogoča razvrstitev podatkov glede na osrednjo napravo.
  
  - **NetworkCost** – Označuje strošek/vrsto omrežja, kot je omejen prenos podatkov, omejeno nad zgornjo mejo.
  
  - **NetworkCountry** – koda države pošiljatelja, ki temelji na neočiščenem naslovu IP odjemalca.

  - **NumProcPhysCores** – Število fizičnih jeder v računalniku. Omogoča razvrstitev podatkov glede na osrednjo napravo.

  - **OsLocale** – Območne nastavitve operacijskega sistema, ki se izvaja. Omogoča razvrstitev podatkov glede na osrednjo napravo.

  - **ProcessorArchitecture** – Arhitektura procesorja. Omogoča razvrstitev podatkov glede na osrednjo napravo.

  - **ProcessorCount** – Število procesorjev v računalniku. Omogoča razvrstitev podatkov glede na osrednjo napravo.

  - **ProcSpeedMHz** – Hitrost procesorja. Omogoča razvrstitev podatkov glede na osrednjo napravo.

  - **RamMB** – Količina pomnilnika v napravi. Omogoča razvrstitev podatkov glede na osrednjo napravo.

  - **ScreenDepth** – Omogoča razvrstitev podatkov glede na osrednjo napravo.

  - **ScreenDPI** – Vrednost DPI zaslona. Omogoča razvrstitev podatkov glede na osrednjo napravo.

  - **SusClientId** – ID za Windows Update za napravo, v kateri se izvaja Office.

  - **SystemVolumeFreeSpaceMB** – Količina nezasedenega prostora v sistemskem nosilcu. Omogoča razvrstitev podatkov glede na osrednjo napravo.

  - **SystemVolumeSizeMB** – Velikost sistemskega nosilca v računalniku. Omogoča razvrstitev podatkov glede na osrednjo napravo.

  - **VerticalResolution** – Navpična ločljivost zaslona naprav. Omogoča razvrstitev podatkov glede na osrednjo napravo.

  - **WindowErrorReportingMachineId** – Enolični identifikator računalnika, ki ga ustvari poročanje sistema Windows o napakah. Omogoča razvrstitev podatkov glede na osrednjo napravo.

  - **WindowSqmMachineId** – Enolični identifikator za računalnik, ki ga ustvari Windows SQM. Omogoča razvrstitev podatkov glede na osrednjo napravo.

#### <a name="event"></a>Dogodek 

Informacije o dogodku, vključno z enoličnim identifikatorjem seje.

Ta kategorija vsebuje ta polja:

  - **Contract** – Seznam morebitnih pogodb, ki jih dogodek uveljavlja. Omogoča, da lahko ocenimo, kateri podatki so del posameznih dogodkov, tako da jih lahko učinkovito obdelamo.

  - **CV** – Vrednost, s katero lahko identificiramo dogodke, ki so medsebojno povezani. Te podatke uporabljamo za diagnostiko, da lahko določimo vzorce povezanega načina delovanja oz. povezanih dogodkov.

  - **Flags** – Informacije, s katerimi lahko spremenimo način odzivanja določenega dogodka. Omogoča, da lahko upravljamo način obravnavanja določenega dogodka za namene prenašanja podatkov Microsoftu.

  - **Id** – Enolični identifikator dogodka. Omogoča enolično identificiranje prejetih dogodkov.

  - **Name** – Ime dogodka. Omogoča določitev dogodka, ki ga je poslal odjemalec.

  - **Rule** – Identifikator pravila, ki je ustvarilo podatke (če je te ustvarilo pravilo). Omogoča določitev vira dela podatkov, tako da lahko preverimo veljavnost parametrov dogodkov in jih upravljamo.

  - **RuleId** – Identifikator pravila, ki je ustvarilo podatke (če je te ustvarilo pravilo). Omogoča določitev vira dela podatkov, tako da lahko preverimo veljavnost parametrov dogodkov in jih upravljamo.

  - **RuleInterfaces** – Vsi vmesniki, ki jih uveljavi določeno pravilo. Omogoča, da razvrstimo in uvozimo podatke glede na njihovo strukturo ter tako poenostavimo obdelavo podatkov.

  - **RuleVersion** – Identifikator pravila, ki je ustvarilo podatke (če je te ustvarilo pravilo). Omogoča določitev vira dela podatkov, tako da lahko preverimo veljavnost parametrov dogodkov in jih upravljamo.

  - **SampleRate** – Navedba odstotka uporabnikov, ki pošiljajo ta del podatkov. Opravimo lahko statistično analizo podatkov in pogostih podatkovnih točk, ki ne zahtevajo, da jih pošiljajo vsi uporabniki.

  - **SchemaVersion** – Različica sheme, ki je uporabljena za ustvarjanje diagnostičnih podatkov. Zahtevano za upravljanje podatkov, ki jih pošlje odjemalec. Omogoča, da lahko sčasoma spremenimo vrsto podatkov, ki jih pošilja odjemalec.

  - **Sequence** – Števec, ki določa vrstni red ustvarjenih dogodkov v odjemalcu. Omogoča razvrstitev prejetih podatkov tako, da lahko prepoznamo korake, ki so odjemalce morda privedli do določnih težav.

  - **Source** – Izvorni cevovod, uporabljen za prenos podatkov. Zahtevano za spremljanje posameznih cevovodov za prenašanje za zagotavljanje ustreznosti stanja sistema in lažje prepoznavanje težav s cevovodom za prenašanje. Omogoča spremljanje posameznih cevovodov za prenašanje za zagotavljanje njihove skladnosti s predpisi.

  - **Time** – Čas, ko je bil dogodek ustvarjen v odjemalcu. Omogoča, da lahko sinhroniziramo in preverimo veljavnost vrstnega reda dogodkov, ustvarjenih v odjemalcu, ter izdelamo metriko učinkovitosti delovanja za navodila za uporabnike. 

#### <a name="host"></a>Gostitelj

Informacije o aplikaciji, ki gosti vdelano aplikacijo.

Ta kategorija vsebuje ta polja:

  - **Id** – Enolični identifikator, ki ga vdelana aplikacija dodeli gostiteljski aplikaciji.

  - **SessionId** – Globalni enolični identifikator za sejo gostitelja.

  - **Version** – Identifikator različice primarne izvedljive seje gostitelja.

#### <a name="legacy"></a>Starejša različica

Informacije, potrebne za združljivost starejše različice sistema.

Ta kategorija vsebuje ta polja:

  - **OsBuild** – Določena številka graditve operacijskega sistema. Omogoča, da določimo, iz katere različice operacijskega sistema izhajajo diagnostični podatki ter tako razvrstimo težave po pomembnosti.

  - **OsBuildRevision** – Številka revizije graditve operacijskega sistema. Omogoča, da določimo, iz katere različice operacijskega sistema izhajajo diagnostični podatki ter tako razvrstimo težave po pomembnosti.

  - **OsMinorVersion** – Podrazličica operacijskega sistema. Omogoča, da določimo, iz katere različice operacijskega sistema izhajajo diagnostični podatki ter tako razvrstimo težave po pomembnosti.

  - **OsVersionString** – Enolični niz, ki predstavlja številko različice operacijskega sistema. Omogoča, da določimo, iz katere različice operacijskega sistema izhajajo diagnostični podatki ter tako razvrstimo težave po pomembnosti.

#### <a name="session"></a>Seja

Informacije o seji obdelave.

Ta kategorija vsebuje ta polja:

  - **ABConfigsDelta** – Spremlja razliko med trenutnimi podatki »ABConfigs« in prejšnjo vrednostjo. Omogoča spremljanje novih pilotnih različic v računalniku, tako da lahko določite, ali je nova pilotna različica morda kriva za težave.

  - **CollectibleClassification** – Razredi informacij, ki jih lahko zbira seja. Omogoča filtriranje sej glede na razpoložljive podatke.

  - **DisableTelemetry** – Zastavica, ki označuje, ali je ključ »DisableTelemetry« nastavljen. Omogoča, da si lahko ogledamo, ali je seja poročala le o diagnostičnih podatkih »EssentialServiceMetadata«.

  - **SamplingKey** – Ključ, uporabljen za določanje, ali je seja vzorčna ali ne. Omogoča prikaz podatkov, ki določajo, ali je seja vzorčna ali ne.

  - **SamplingMethod** – Način, uporabljen za določanje pravilnika vzorčenja. Omogoča razumevanje vrste podatkov, ki jih ustvarja seja.

  - **Sequence** – Enolični številski identifikator seje. Omogoča razvrščanje sej za analizo časov pojava težav.

  - **Start** – Čas zagona seje postopka. Omogoča določitev časa začetka izvajanja seje.

  - **TimeZoneBiasInMinutes** – Razlika med UTC-jem in lokalnim časom v minutah. Omogoča normaliziranje časov UTC v lokalne čase.

  - **SamplingClientIdValue** – Vrednost ključa, s katerim je določeno vzorčenje. Omogoča, da lahko prepoznamo razlog za vzorčenje oz. izključitev iz vzorčenja za določeno sejo.

  - **SamplingDeviceIdValue** – Vrednost ključa, s katerim je določeno vzorčenje. Omogoča, da lahko prepoznamo razlog za vzorčenje oz. izključitev iz vzorčenja za določeno sejo.

  - **SamplingSessionKValue** – Dodatni metapodatki vzorčenja. Omogoča ocenjevanje statističnega pomena prejetih podatkov.

  - **SamplingSessionNValue** – Dodatni metapodatki vzorčenja. Omogoča ocenjevanje statističnega pomena prejetih podatkov.

  - **TelemetryPermissionLevel** – Vrednost, ki določa, katero raven diagnostičnih podatkov je izbral uporabnik. Omogoča razumevanje ravni diagnostičnih podatkov, ki jih bo ustvarila seja.

## <a name="data-fields-that-are-common-for-onenote-events"></a>Podatkovna polja, ki so skupna za dogodke storitve OneNote

Naslednja podatkovna polja so skupna za vse dogodke storitve OneNote za Mac, iOS in Android.

> [!NOTE]
> Kadar uporabljate pregledovalnik diagnostičnih podatkov, je prikazano ime »Dejavnost«, »ReportData« ali »Nepričakovano« za dogodke storitve OneNote za Mac, iOS in Android. Če želite najti dejansko ime dogodka, izberite dogodek in si nato oglejte polje »EventName«.

- **Activity_ActivityType** – označuje vrsto tega dogodka dejavnosti. Dejavnost je lahko normalna dejavnost ali dejavnost z visoko vrednostjo.

- **Activity_AggMode** – sporoči sistemu, kako naj združi rezultate dejavnosti. Omogoča, da zmanjšamo količino prenesenih informacij iz uporabnikovega računalnika tako, da združimo rezultate dejavnosti v en dogodek, ki ga redno pošiljamo.

- **Activity_Count** – število izvajanj določene dejavnosti, če pridobljeno število označuje združeni dogodek. Omogoča, da določimo, kolikokrat je bila dejavnost uspešno oz. neuspešno izvedena glede na način združevanja dejavnosti.

- **Activity_CV** – vrednost, ki določa odnos med dejavnostmi in poddejavnostmi. Omogoča, da lahko znova ustvarimo odnos med ugnezdenimi dejavnostmi.

- **Activity_DetachedDurationInMicroseconds** – čas, ko je dejavnost nedejavna in ne izvaja nobenega dejanskega dela, vendar se čas še vedno sešteva za pridobitev skupnega časa dejavnosti.

- **Activity_DurationInMicroseconds** – trajanje izvajanja dejavnosti. Omogoča, da določimo težave z učinkovitostjo delovanja, ki negativno vplivajo na uporabniško izkušnjo.

- **Activity_Expiration** – datum v številski obliki označuje, kdaj bo prišlo do ustavitve pošiljanja tega dogodka iz odjemalcev.

- **Activity_FailCount** – število, ki pokaže, kolikokrat je bila ta dejavnost neuspešna.

- **Activity_Name** – kratko ime dogodka. Omogoča določitev dogodka, ki ga je poslal odjemalec.

- **Activity_Namespace** – imenski prostor dogodka. Omogoča združevanje dogodkov v skupine.

- **Activity_Reason** – niz, ki označuje razlog, zaradi katerega je dejavnost končana z določenim rezultatom.

- **Activity_Result** – zastavica, ki označuje, ali je bila dejavnost uspešna, neuspešna ali nepričakovano neuspešna. Omogoča, da določimo, ali so bila uporabnikova dejanja v izdelku uspešno oz. neuspešno izvedena. Prepoznamo lahko težave, ki vplivajo na uporabnika.

- **Activity_State** – zastavica označuje, ali je dogodek začetek ali konec dejavnosti uporabnika.

- **Activity_SucceedCount** – število, ki pokaže, kolikokrat je bila ta dejavnost uspešna.

- **ErrorCode** – označuje kodo napake, če je na voljo.

- **ErrorCode2** – označuje drugo kodo napake, če je na voljo.

- **ErrorCode3** – označuje tretjo kodo napake, če je na voljo.

- **ErrorTag** – označuje oznako, ki je povezana s kodo napake, če je na voljo.

- **ErrorType** – označuje vrsto napake, če je na voljo.

- **EventName** – enolično ime dogodka v aplikaciji OneNote. Dogodki v aplikaciji OneNote uporabljajo to polje po meri za določanje enoličnega imena zaradi inženirske omejitve v preteklosti.

- **ExpFeatures** – označuje, ali je uporabnik vklopil stikalo za preskusne funkcije v aplikaciji OneNote ali ne.

- **ExpirationDate** – datum v številski obliki zapisa označuje, kdaj bo ustavljeno pošiljanje tega dogodka iz odjemalcev.

- **IsConsumer** – označuje, ali je uporabnik potrošnik ali ne.

- **IsEdu** – označuje, ali ima uporabnik status uporabnika v izobraževalnem najemniku ali ne

- **IsIW** – označuje, ali je uporabnik poslovni uporabnik ali ne.

- **IsMsftInternal** – označuje, ali je uporabnik zaposleni družbe Microsoft ali ne.

- **IsPremiumUser** – označuje, ali ima uporabnik licenco Premium ali ne.

- **Namespace** – imenski prostor dogodka. Omogoča združevanje dogodkov v skupine.

- **Release_AppStore** – zastavica označuje, ali je graditev pridobljena v trgovini z aplikacijami ali ne.

- **Release_Audience** – določa podskupino občinstva za dano skupino občinstva. Omogoča spremljanje podmnožic skupin občinstva za ocenjevanje razširjenosti in ravni pomembnosti težav.

- **AudienceGroup** – določa krog, kjer so ustvarjeni podatki. Omogoča postopno uvajanje funkcij in prepoznavanje morebitnih težav, preden te dosežejo večji del uporabnikov.

- **Release_Channel** – kanal, v katerem je izdelek izdan. Omogoča, da prepoznamo, ali določene težave različno vplivajo na kanale za uvajanje.

- **RunningMode** – označuje način zagona aplikacije, in sicer s strani uporabnika ali sistemskega procesa.

- **SchemaVersion** – prikazuje trenutno različico sheme telemetrije v telemetrijskem prodajnem lijaku v OneNotu.

- **Session_EcsETag** – indikator sistema pilotnih različic, ki predstavlja pilotne različice, poslane v računalnik. Omogoča, da določimo, katere pilotne različice morda vplivajo na določeno sejo.

- **Session_ImpressionId** – določa nabor pilotnih različic, ki se izvajajo v dani seji. Omogoča, da ugotovimo, katere pilotne različice se izvajajo v seji ter tako določimo, ali je pilotna različica izvor uporabnikovih težav.

- **SessionCorrelationId** – globalni enolični identifikator za sejo gostitelja.

- **SH_ErrorCode** – označuje kodo napake, če je na voljo ob neuspehu dejavnosti.

- **Tag** – oznaka za celo število, ki določa lokacijo v kodi, kjer je ustvarjen dogodek telemetrije.

- **UserInfo_IdType** – niz označuje vrsto uporabniškega računa.

- **UserInfo_OMSTenantId** – najemnik, s katerim je povezana uporabnikova naročnina. Omogoča, da razvrstimo težave in določimo, ali je težava razširjena ali omejena na določen nabor uporabnikov oz. določenega najemnika.

- **UserInfo_OtherId** – seznam psevdonimnih identifikatorjev, ki niso primarni in predstavljajo uporabniške račune.

- **UserInfo_OtherIdType** – seznam vrst računov, ki niso primarni.

## <a name="software-setup-and-inventory-data-events"></a>Dogodki podatkov inventarja in nastavitve programske opreme

V nadaljevanju tega članka so navedeni podatkovni podtipi v tej kategoriji:
- [Nastavitev Officea in inventar](#office-setup-and-inventory-subtype)
- [Konfiguracija dodatka za Office](#office-add-in-configuration-subtype)
- [Varnost](#security-subtype)  

### <a name="office-setup-and-inventory-subtype"></a>*Podtip nastavitve Officea in inventarja*

Nameščeni izdelek, različica in stanje namestitve.

#### <a name="officeclicktorunupdatestatus"></a>Office.ClickToRun.UpdateStatus

Velja za vse aplikacije za Win32. Omogoča razumevanje stanja postopka posodobitve zbirke Office (uspešno ali neuspešno s podrobnostmi o napaki)

Zbrana so ta polja:

- **build** – Trenutno nameščena različica Officea.

- **channel** – Kanal, prek katerega se distribuira Office.

- **errorCode** – Koda napake, ki označuje napako.

- **errorMessage** – Dodatne informacije o napaki.

- **status** – Trenutno stanje posodobitve.

- **targetBuild** – Različica, v katero bo Office posodobljen.

#### <a name="officecompliancefileformatballotdisplayedonfirstboot"></a>Office.Compliance.FileFormatBallotDisplayedOnFirstBoot

Označuje, ali je bilo Officeovo pogovorno okno z izbirami oblike zapisa datoteke prikazano uporabniku ob prvem/drugem zagonu aplikacije Word, Excel ali PowerPoint v sistemu Win32.  Spremlja, ali je prikazano pogovorno okno »Glasovnica za FileFormat« – dogodek je poslan ob prvem/drugem zagonu aplikacije Word, Excel ali PowerPoint v sistemu Win32.

Zbrana so naslednja polja.

- **CountryRegion** – nastavitev regije države uporabnika v sistemu Windows

- **FileFormatBallotBoxAppIDBootedOnce** – označuje, v kateri aplikaciji (Word, Excel, PowerPoint) je bila obdelana logika prikaza glasovnice oblike zapisa datoteke.

- **FileFormatBallotBoxDisplayedOnFirstBoot** – označuje, kakšen je rezultat prikaza za glasovnico oblike zapisa datoteke (prikazan/ni prikazan kot nepričakovan/ni prikazan zaradi licence/ni prikazan zaradi lokacije).

#### <a name="officecompliancefileformatballotoption"></a>Office.Compliance.FileFormatBallotOption

Spremlja, ali je prikazano pogovorno okno »Glasovnica za FileFormat« – dogodek je poslan ob prvem/drugem zagonu aplikacije Word, Excel ali PowerPoint v sistemu Win32.  Označuje, ali je pogovorno okno z izbirami oblike zapisa datoteke prikazano ob prvem ali drugem zagonu aplikacije Word, Excel ali PowerPoint v sistemu Win32.

Zbrana so sledeča polja:

- **FileFormatBallotSelectedOption** – določa možnost oblike zapisa datoteke (OOXML/ODF), ki jo je uporabnik izbral v pogovornem oknu glasovnice oblike zapisa datoteke.


#### <a name="officecorrelationmetadatautccorrelationmetadata"></a>Office.CorrelationMetadata.UTCCorrelationMetadata

Zbira metapodatke Officea prek UTC-ja in jih primerja z enakovrednimi podatki, zbranimi prek cevovoda telemetrije sistema Office za preverjanje ustreznosti in celovitosti podatkov.

Zbrana so ta polja:

- **abConfigs** – Seznam ID-jev funkcij za določanje, katere funkcije so omogočene za odjemalca ali prazne, ko ti podatki niso zbrani.

- **abFlights** – »NoNL:NoFlights«, ko pilotne različice funkcij niso nastavljene. V nasprotnem primeru je izbrana možnost »holdoutinfo=unknown«.

- **AppSessionGuid** – Identifikator določene seje aplikacije, ki se je začela z ustvarjanjem procesa in traja vse do konca procesa. Dogodek je oblikovan kot standardni 128-bitni GUID, sestavljen iz 4 delov. Ti štirje deli v vrstnem redu so (1) 32-bitni ID procesa (2) 16-bitni ID seje (3) 16-bitni ID zagona (4) čas ustvarjanja 64-bitnega procesa v UTC 100ns.

- **appVersionBuild** – Številka različice graditve aplikacije.

- **appVersionMajor** – Številka glavne različice aplikacije.

- **appVersionMinor** – Številka podrazličice aplikacije.

- **appVersionRevision** – Številka različice revizije aplikacije.

- **audienceGroup** – Ime skupine občinstva izdaje.

- **audienceId** – Ime občinstva izdaje.

- **channel** – Kanal, prek katerega se distribuira Office.

- **deviceClass** – Dimenzije naprave v operacijskem sistemu.

- **ecsETag** – Identifikator preskusa za proces.

- **impressionId** – GUID, ki označuje trenutni nabor funkcij.

- **languageTag** – Trenutna jezikovna oznaka za Office UI IETF.

- **officeUserID** – Naključno ustvarjeni GUID za to namestitev Officea.

- **osArchitecture** – Arhitektura operacijskega sistema.

- **osEnvironment** – Celo število, ki označuje operacijski sistem (Windows, Android, iOS, Mac itd.).

- **osVersionString** – Različica operacijskega sistema.

- **sessionID** – Naključno ustvarjeni GUID za prepoznavanje seje aplikacije.

- **UTCReplace_AppSessionGuid** – Logična vrednost konstante. Vedno ima vrednost true.

#### <a name="officeonenotefirstrunfirstrun"></a>Office.OneNote.FirstRun.FirstRun

Kritični signal, ki se uporablja, da lahko novi uporabniki prvič uspešno zaženejo in začnejo uporabljati OneNote.  Telemetrija se uporablja za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in stanja storitve. Če uporabniki prvič ne morejo zagnati aplikacije, bo to sprožilo dogodek z visoko stopnjo resnosti.

- **AfterOneDriveFrozenAccountError** – označuje napako OneDrive, ko je račun zamrznjen.

- **Poskus** – kolikokrat je treba izvesti uporabniško izkušnjo prvega zagona.

- **IsDefaultNotebookCreated** – označuje, ali je OneNote ustvaril uporabniški privzeti zvezek ali ne.

- **IsDelayedSignIn** – označuje, ali je prvi zagon v zakasnitvi pri vpisu, kjer se uporabniku ni treba vpisati.

- **IsMSA** – označuje, ali je račun Microsoftov račun ali ne.

#### <a name="officeonenotefirstrunfirstrunformsa"></a>Office.OneNote.FirstRun.FirstRunForMSA

Kritični signal, ki se uporablja, da lahko novi uporabniki (Microsoftov račun) prvič uspešno zaženejo in začnejo uporabljati OneNote.
Telemetrija, uporabljena za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in stanja storitve. Če uporabniki prvič ne morejo zagnati aplikacije, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so naslednja polja:

- **Poskus** – kolikokrat je treba izvesti uporabniško izkušnjo prvega zagona.

- **Napaka A** – predmet napake označuje napako med napako med prvim zagonom, če pride do nje.

- **FAllowAddingGuide** – označuje, ali bo OneNote omogočil ustvarjanje zvezka za vodenje ali ne.

- **FrozenOneDriveAccount** – označuje, ali je račun OneDrive zamrznjen ali ne.

- **IsDefaultNotebookCreated** – označuje, ali je OneNote ustvaril uporabniški privzeti zvezek ali ne.

- **NoInternetConnection** – označuje, ali naprava nima nameščene internetne povezave.

- **ProvisioningFailure** – predmet napake v OneNote, ki označuje napako pri omogočanju uporabe, če pride do nje.

- **ProvisioningFinishedTime** – označuje končni čas, ko OneNote dokonča omogočanje uporabe zvezka med izkušnjo prvega zagona.

- **ProvisioningStartedTime** – označuje začetni čas, ko OneNote začne omogočati uporabo zvezka med izkušnjo prvega zagona.

- **ShowSuggestedNotebooks** – označuje, ali OneNote prikaže funkcijo predlaganega zvezka ali ne.

#### <a name="officeonenotefirstrunfirstrunfororgid"></a>Office.OneNote.FirstRun.FirstRunForOrgId

Kritični signal, ki se uporablja, da lahko novi poslovni uporabniki(AAD/OrgID) prvič uspešno zaženejo in začnejo uporabljati OneNote.  Telemetrija, uporabljena za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in stanja storitve. Če uporabniki prvič ne morejo zagnati aplikacije, bo to sprožilo dogodek z visoko stopnjo resnosti.

- **Poskus** – kolikokrat je treba izvesti uporabniško izkušnjo prvega zagona.

- **Napaka** – A predmet napake OneNote označuje napako med prvim zagonom, če pride do nje.

- **FAllowAddingGuide** – označuje, ali bo OneNote omogočil ustvarjanje zvezka za vodenje ali ne.

- **IsDefaultNotebookCreated** – označuje, ali je OneNote ustvaril uporabniški privzeti zvezek ali ne.

- **ProvisioningFailure** – A predmet napake v OneNote, ki označuje napako pri omogočanju uporabe, če pride do nje.

- **ProvisioningFinishedTime** – označuje končni čas, ko OneNote dokonča omogočanje uporabe zvezka med izkušnjo prvega zagona.

- **ProvisioningStartedTime** – označuje začetni čas, ko OneNote začne omogočati uporabo zvezka med izkušnjo prvega zagona.

#### <a name="officetargetedmessagingensurecached"></a>Office.TargetedMessaging.EnsureCached 

Spremlja prenos paketa za Dynamic Canvas. Obravnavamo ga kot konfiguracijo programske opreme, ker mora biti paket uspešno prenesen, da odjemalec lahko uporablja ustrezno izkušnjo. Še posebej je pomemben pri naročninah za potrošnike, kjer prek platna komuniciramo z uporabnikom, ki mu je potekla licenca. Z njim spremljamo metapodatke paketa dinamične vsebine, prenesene z izdelkom in shranjene v predpomnilnik, ter rezultatov izvedenih postopkov za paket: napake pri prenosu, napake pri razpakiranju, napake pri preverjanju doslednosti, zadetki v predpomnilniku, uporabe paketa, uspešni prenosi.

Zbrana so ta polja:

  - **Data\_CacheFolderNotCreated** – Logična zastavica, ki označuje, ali je bila mapa predpomnilnika uspešno ustvarjena.

  - **Data\_CdnPath – Izvorni naslov paketa.**

  - **Data\_EnsureCached** – Logična zastavica, ki označuje, ali je bil paket vsebine shranjen v predpomnilnik.

  - **Data\_ExistsAlready** – Logična zastavica, ki označuje, da je bil paket že prenesen v preteklosti in da je bil zaznan vnovični poskus prenosa.

  - **Data\_GetFileStreamFailed** – Izvorni paket ni na voljo v izvorni datoteki.

  - **Data\_GetFileStreamFailedToCreateLocalFolder** – Težave z lokalnim diskom, zaradi katerih prihaja do napak pri ustvarjanju imenika.

  - **Data\_GetFileStreamFromPackageFailed** – Zastavica, ki označuje, da je bil paket prenesen, vendar ga odjemalec ne more brati.

  - **Data\_GetFileStreamFromPackageSuccess** – Uspešni poskusi branja paketa.

  - **Data\_GetFileStreamSuccess** – Ni zaznanih težav z diskom ali konfiguracijo, ki bi preprečevale branje toka datoteke.

  - **Data\_GetRelativePathsFailed** – Relativna pot ne pripelje do dostopnega mesta.

  - **Data\_HashActualValue** – Zgoščena vrednost, pridobljena iz imena datoteke, ko je bil paket uporabljen.

  - **Data\_HashCalculationFailed** – Napaka z izračunom zgoščene vrednosti.

  - **Data\_HashMatchFailed** – Neujemanje zgoščenih vrednosti imena datoteke in predpomnjenih vrednosti registra.

  - **Data\_HashMatchSuccess** – Uspešno preverjanje doslednosti zgoščene vrednosti.

  - **Data\_PackageDownloadRequestFailed** – Paketa ni mogoče prenesti.

  - **Data\_PackageDownloadRequestNoData** – Preneseni paket ne vsebuje nobenih podatkov.

  - **Data\_PackageDownloadRequestSuccess** – Uspešen prenos paketa.

  - **Data\_PackageExplodedSuccess** – Stanja poskusov razpakiranja.

  - **Data\_PackageOpenFailed** – Neuspešni poskusi odpiranja datoteke paketa.

  - **Data\_PackageOpenSuccess** – Uspešni poskusi odpiranja datoteke paketa.

  - **Data\_SuccessHashValue** – Zgoščena vrednost, pridobljena iz imena datoteke, ko je bil paket prenesen.

  - **Data\_SuccessSource** – Platforma, za katero je bil paket prenesen.

#### <a name="officevisiovisiosku"></a>Office.Visio.VisioSKU

Pridobiva inventarne številke za Visio, ne glede na to, ali gre za različico Standard ali Professional. Pomembno za razvrščanje težav glede na inventarne številke.

Zbrana so ta polja:

  - **Data\_VisioSKU**:**integer** – 0 za inventarno številko za različico Standard in 1 za inventarno številko za različico Professional.

### <a name="office-add-in-configuration-subtype"></a>*Podtip konfiguracije dodatka za Office*

Dodatki programske opreme in nastavitve.

#### <a name="exceladdindefinedfunctioncustomfunctionsallinone"></a>Excel.AddinDefinedFunction.CustomFunctionsAllInOne

Zbira informacije o tem, kako delujejo funkcije dodatka po meri. Vzdržuje števce poskusov izvedbe, uspešnih dokončanj, napak infrastrukture in napak uporabniških kod. To se uporablja za identifikacijo težav pri zanesljivosti izdelka in odpravljanju težav, ki vplivajo na uporabnike.
 
Zbrana so sledeča polja:

- **AsyncBegin** – število asinhronih funkcij, ki se začnejo izvajati.

- **AsyncEndAddinError** – število asinhronih funkcij, ki se končajo z napako.

- **AsyncEndInfraFailure** – število asinhronih funkcij, ki se končajo z neuspehom infrastrukture.

- **AsyncEndSuccess** – število asinhronih funkcij, ki se končajo uspešno.

- **AsyncRemoveCancel** – število asinhronih funkcij, ki so bile preklicane. 

- **AsyncRemoveRecycle** – število asinhronih funkcij, ki so bile odstranjene zaradi recikliranja. 

- **StreamingCycles1** – števec ciklov pretakanja.

#### <a name="officeextensibilityappcommandsappcmdprojectionstatus"></a>Office.Extensibility.AppCommands.AppCmdProjectionStatus

Zbira podatke za spremljanje, katere namestitve dodatkov za Office so uspešno oz. neuspešno posodobile trak.

Z njim odpravljamo pogoste težave z registracijo, kjer dodatki niso pravilno nameščeni in se nikoli ne prikažejo, zaradi česar jih ni mogoče uporabljati.

Zbrana so ta polja:

  - Nobeno

#### <a name="officeextensibilityappcommandsaddsolution"></a>Office.Extensibility.AppCommands.AddSolution

Zbira informacije o namestitvi za Officeove dodatke, ki prilagajajo trak.  Uporablja se zaznavanje težav z načini, na katere dodatki po meri spreminjajo Officeov trak.
 
Zbrana so naslednja polja:

- **AppVersion** – različica aplikacije.

- **SolutionId** – ID rešitve.

- **StoreType** – označuje izvor aplikacije.

- **TelemetryId** – ID telemetrije, ki temelji na vpisani identiteti.


#### <a name="officeextensibilitycatalogexchangegetentitlements"></a>Office.Extensibility.Catalog.ExchangeGetEntitlements

Podatki o uspešnem oz. neuspešnem pridobivanju podatkov o upravičenosti do dodatkov za skrbnika najemnika storitve Office 365, ki so mu dodatki dodeljeni. Z njim ustvarjamo metrike ustreznosti stanja, grafikone in analize težav uporabnikov.

Zbrana so ta polja:

  - **CachingResult** – Rezultat poskusa shranjevanja vrnjene vrednosti klica storitve.

  - **ClientParameter** – Identifikator odjemalca, poslanega v klicu storitve.

  - **EntitlementsCount** – Število pričakovanih upravičenosti v odzivu klica.

  - **EntitlementsParsed** – Število razčlenjenih upravičenosti v odzivu.

  - **IsAllEntitlementsParsed** Podatki, ali se število pričakovanih upravičenosti ujema s številom razčlenjenih upravičenosti.

  - **ServiceCallHResult** – Rezultat, ki ga vrne API klica storitve.

  - **TelemetryId** – GUID, ki predstavlja enoličnega uporabnika.

  - **UsedCache** – Podatki, ali je bil uporabljen predpomnjeni odziv namesto klica storitve.

  - **VersionParameter** – Številka različice Officea, poslana v klicu storitve.

#### <a name="officeextensibilitycatalogexchangegetlastupdate"></a>Office.Extensibility.Catalog.ExchangeGetLastUpdate

Podatki o uspešnem oz. neuspešnem pridobivanju posodobljenih podatkov o dodatkih, ki so bili dodeljeni najemniku storitve Office 365. Z njim ustvarjamo metrike ustreznosti stanja, grafikone in analize težav uporabnikov. »ExchangeGetLastUpdate« se vedno začne izvajati ob zagonu kot del kode gostitelja in določa, ali so bile dodelitve dodatkov spremenjene za uporabnika.  V tem primeru je naložen »osf.DLL«, tako da lahko prikličemo »ExchangeGetEntitlements« in pridobimo določene dodelitve (»ExchangeGetManifests« je priklican za pridobivanje morebitnega novega potrebnega manifesta).  Na zahtevo lahko prikličemo tudi »ExchangeGetEntitlements« (in »ExchangeGetManifests«), ko je zagnana gostiteljska aplikacija. Veliki DLL se ne naloži, če ga ne potrebujemo.  Brez tega dogodka v polju »Required« ni mogoče prepoznati, da uporabniki niso uspešno pridobili njim dodeljenih dodatkov, če je bil prvi klic storitve neuspešen.  To je tudi glavni pokazatelj morebitnih težav s preverjanjem pristnosti med povezovanjem s storitvijo.

Zbrana so ta polja:

  - **Abort** – Ali je bil gostitelj zaustavljen med klicem storitve.

  - **AllowPrompt** – Ali je dovoljeno pozivanje preverjanja pristnosti.

  - **AuthScheme** – Shema preverjanja pristnosti, ki jo zahteva Exchange.

  - **BackEndHttpStatus** – Koda http, ki je javljena za uporabo zalednega strežnika Exchange.

  - **BackupUrl** – Sekundarni URL povezavo s strežnikom Exchange.

  - **BEServer** – Ime zalednega strežnika Exchange.

  - **CalculatedBETarget** – Polno ime računalnika z zalednim strežnikom Exchange.

  - **Call(n)\_TokenAuthError** – Napaka preverjanja pristnosti poskusa klica storitve nth.

  - **Call(n)\_TokenIsValid** – Ali je žeton za preverjanje pristnosti poskusa storitve nth veljaven.

  - **CallMethod** – Niz, ki označuje pot kode.

  - **ConfigSvcReady** – Ali je bila storitev konfiguriranja že inicializirana.

  - **Date** – Vrednost, ki jo vrne strežnik Exchange.

  - **DiagInfo** – Informacije, ki jih vrne strežnik Exchange.

  - **End\_TicketAuthError** – Morebitne napake pri pridobivanju vstopnice za preverjanje pristnosti po klicu storitve.

  - **End\_TokenIsValid** – Ali je vstopnica za preverjanje pristnosti veljavna po klicu storitve.

  - **EndingIdentityState** – Navedeno stanje predmetov identitete po klicih storitve.

  - **EwsHandler** – Vrednost, ki jo vrne Exchange.

  - **FEServer** – Čelni strežnik Exchange, ki obdeluje zahtevo.

  - **HResult** – Koda rezultata. 

  - **HttpStatus** – Koda stanja Http, ki jo vrne Exchange.

  - **IsSupportedAuthResponse** – Ali je vrsta preverjanja pristnosti takšna, da jo je mogoče uporabiti.

  - **LastUpdateValueRegistry** – Zgoščena vrednost, pridobljena iz registra.

  - **LastUpdateValueRetrieved** – Zgoščena vrednost, ki jo vrne klic storitve.

  - **MSDiagnostics** – Vrednost, ki jo vrne Exchange.

  - **MsoHttpResult** – Vrednost popisovalnika, ki jo vrne API za http.

  - **NeedRefresh** – To je polje z vrednostjo »true« ali »false«, ki označuje, ali so podatki dodatka zastareli in jih je treba posodobiti.

  - **PrimaryUrl** – Glavni URL za izvajanje klica storitve.

  - **RequestId** – Vrednost, ki jo vrne Exchange.

  - **RequestTryCount** – Število poskusov klicanja storitve.

  - **RequestTryCount** – Število poskusov vzpostavljanja povezave s strežnikom Exchange.

  - **ResultChain** – Niz kod rezultatov posameznih poskusov klicanja storitve.

  - **StartingIdentityState** – Navedeno stanje predmetov identitete pred klici storitve.

  - **TelemetryId** – GUID, ki predstavlja enoličnega uporabnika, za katerega moramo morda izvesti druge klice storitve.

#### <a name="officeextensibilitycatalogexchangegetmanifests"></a>Office.Extensibility.Catalog.ExchangeGetManifests

Podatki o uspešnem oz. neuspešnem pridobivanju podatkov o manifestih dodatkov za skrbnika najemnika storitve Office 365, ki so mu dodatki dodeljeni. Z njim ustvarjamo metrike ustreznosti stanja, grafikone in analize težav uporabnikov.

Zbrana so ta polja:

  - **CachedManifestsParsed** – Število manifestov v predpomnilniku.

  - **IsAllReturnedManifestsParsed** – Ali je bilo mogoče razčleniti vse vrnjene manifeste.

  - **ManifestsRequested** – Število potrebnih manifestov.

  - **ManifestsReturned** – Število manifestov, ki jih je vrnil strežnik.

  - **ManifestsToRetrieve** – Število manifestov, ki jih je treba pridobiti iz strežnika.

  - **ReturnedManifestsParsed** – Število manifestov, ki jih je vrnil strežnik in so bili uspešno razčlenjeni.

  - **TelemetryId** – GUID, ki predstavlja enoličnega uporabnika.

#### <a name="officeextensibilityuxfensureloadosfdll"></a>Office.Extensibility.UX.FEnsureLoadOsfDLL 

Spremlja neuspešna nalaganja dogodka Osf.DLL. Zazna neuspešno nalaganje DLL-ja, ki onemogoča zagon funkcije.

Zbrana so ta polja:

  - Nobeno

#### <a name="officeextensibilityuxfensureloadosfuidll"></a>Office.Extensibility.UX.FEnsureLoadOsfUIDLL 

Spremlja neuspešna nalaganja dogodka OsfUI.DLL. Zazna neuspešno nalaganje DLL-ja, ki onemogoča zagon funkcije.

Zbrana so ta polja:

  - Nobeno

#### <a name="officeextensibilityuxfensureosfshareddllload"></a>Office.Extensibility.UX.FEnsureOsfSharedDLLLoad 

Spremlja neuspešna nalaganja dogodka OsfShared.DLL. Zazna neuspešno nalaganje DLL-ja, ki onemogoča zagon funkcije.

Zbrana so ta polja:

  - Nobeno

#### <a name="officeextensibilityvbatelemetrycomobjectinstantiated"></a>Office.Extensibility.VBATelemetryComObjectInstantiated

Zbira podatke o pozivih avtomatizacijskega strežnika ali odjemalca v rešitvah VBA. Uporabljamo ga za lažje razumevanje interakcije med VBA-jem in predmeti COM.

Zbrana so ta polja:

  - **ComObjectInstantiatedCount** – Število primerkov predmeta COM.

  - **HashComObjectInstantiatedClsid** – Zgoščena vrednost identifikatorja CLSID za predmet COM.

  - **HashProjectName** – Zgoščena vrednost imena projekta VBA.

  - **TagId** – Enolična oznaka.

#### <a name="officeextensibilityvbatelemetrydeclare"></a>Office.Extensibility.VBATelemetryDeclare 

Zbira podatke o pozivih API-ja za Win32 v rešitvah VBA. Uporabljamo ga za lažje razumevanje interakcije med VBA-jem in uporabo ter kot podporo za raziskovanje varnosti.

Zbrana so ta polja:

  - **DeclareCount** – Število deklaracij.

  - **HashDeclare** – Zgoščena vrednost imena DLL-ja.

  - **HashEntryPoint** – Zgoščena vrednost imena API-ja.

  - **HashProjectName** – Zgoščena vrednost imena projekta VBA.

  - **IsPtrSafe** – Ali je izjava o deklaraciji združljiva z drugo arhitekturo.

  - **TagId** – Enolična oznaka.

#### <a name="officeoutlookdesktopadd-insadd-inloaded"></a>Office.Outlook.Desktop.Add-ins.Add-inLoaded

Zbira uspešna in neuspešna nalaganja dodatka v Outlooku. Te podatke aktivno spremljamo za zagotavljanje ustreznega delovanja Outlooka s strankinimi dodatki. S temi podatki zaznamo težave in jih raziščemo.

Zbrana so naslednja polja:

  - **Standard HVA Activity** brez koristne vsebine po meri.

#### <a name="officeoutlookmacaddinapiusage"></a>Office.Outlook.Mac.AddinAPIUsage

Zbira uspehe in neuspehe izvedb dodatkov v Outlooku. Te podatke aktivno spremljamo za zagotavljanje ustreznega delovanja Outlooka z dodatki. S temi podatki zaznamo težave in jih raziščemo.

Zbrana so naslednja polja:

- **AccountType** – vrsta računa, ki je povezan z dodatkom. 

- **Cookie** – piškotek, ki ga dodatek uporablja.

- **DispId** – identifikator razpošiljanja. 

- **EndTime** – čas zaključka dodatka. 

- **ExecutionTime** – čas, ki je potekel med izvajanjem dodatka. 

- **Result** – rezultat uporabe dodatka v Outlooku. 

- **StartTime** – čas začetka izvedbe dodatka.


#### <a name="officeoutlookmacaddineventapisusage"></a>Office.Outlook.Mac.AddinEventAPIsUsage

Zbira uspehe ali neuspehe izvedbe dodatka v Outlooku. Te podatke aktivno spremljamo za zagotavljanje pravilnega delovanja Outlooka z dodatki. S temi podatki zaznamo težave in jih raziščemo.

Zbrana so naslednja polja:

- **AddinType** – vrsta dodatka. 

- **EventAction** – dejanje, ki ga dodatek izvede. 

- **EventDispid** – identifikator razpošiljanja.

- **EventResult** – rezultat dejanja, ki ga dodatek izvede. 

#### <a name="officeoutlookmacaddininstallationfrominclientstore"></a>Office.Outlook.Mac.AddInInstallationFromInClientStore

Zbira uspehe ali neuspehe namestitve dodatka v Outlooku. Te podatke aktivno spremljamo za zagotavljanje pravilnega delovanja Outlooka z dodatki. S temi podatki zaznamo težave in jih raziščemo.

Zbrana so naslednja polja:

- **AccountType** – vrsta računa, povezanega z dodatkom. 

- **FailureReason** – razlog za neuspeh namestitve dodatka. 

- **MarketplaceAssetId** – identifikator dodatka iz trgovine. 

- **Stanje** – stanje namestitve dodatka.


#### <a name="officeprogrammabilityadd-insinternalsetconnectenterprise"></a>Office.Programmability.Add-ins.InternalSetConnectEnterprise

Dogodek, ki je ustvarjen pri nalaganju dodatka COM v napravi s paketom Enterprise. 

Zbrana so naslednja polja:

  - **Rezultat dejavnosti** – stanje uspešnosti povezave.

  - **Add-inconnectFlag** – vedenje trenutnega nalaganja.

  - **Add-inId** – ID razreda dodatka.

  - **Add-inTimeDateStamp** – časovni žig dodatka iz metapodatkov DLL.

  - **IsBootInProgress** – ali je Officeov program v postopku zagona.

#### <a name="officevisiovisioaddonload"></a>Office.Visio.Visio.AddonLoad

Izračuna napake, če rešitve ni mogoče naložiti. Nujno za odpravljanje napak z nalaganjem dodatkov v Visiu.

Zbrana so ta polja:

  - **Data\_Load1Error:integer** – Vrednost napake med nalaganjem dodatka za Visio.

#### <a name="officevisiovisioaddonusage"></a>Office.Visio.Visio.AddonUsage

Zbira napake v primeru napake funkcij rešitve. Nujno za odpravljanje napak z dodatki v dodatkih.

Zbrana so ta polja:

  - **Data\_DocumentSessionLogID:string** – Identifikator seje dokumenta.

  - **Data\_IsEnabled**:**bool** – Vrednost »true«, če je rešitev omogočena.

  - **Data\_TemplateID:string** – GUID predloge, kamor je bila naložena rešitev. Označeno z 0 za rešitev po meri.

  - **Data\_AddOnID**:**string** – GUID za določanje naloženega dodatka.

  - **Data\_Error**:**integer** – ID napake.

### <a name="security-subtype"></a>*Podtip varnosti*

Stanje napak dokumentov, funkcij in dodatkov, ki lahko ogrozijo varnost in pripravljenost izdelka za posodobitve.

#### <a name="officesecurityactivationfilterclsidactivated"></a>Office.Security.ActivationFilter.CLSIDActivated

Spremlja, kdaj je določeni identifikator CLSID (Flash, Silverlight itd.) aktiviran v Officeu. Z njim spremljamo vpliv blokiranja kontrolnikov za Flash, Silverlight in Shockwave na končne uporabnike.

Zbrana so ta polja:

  - **ActivationType** – Vrsta aktiviranja kontrolnika.

  - **Blocked** – Ali je kontrolnik blokiral Office.

  - **CLSID** – Identifikator razreda kontrolnika.

  - **Count** – Število aktiviranj kontrolnika.

#### <a name="officesecurityactivationfilterfailedtoregister"></a>Office.Security.ActivationFilter.FailedToRegister

Spremlja stanje napak varnostnih ukrepov za zmanjševanje tveganja, ki blokirajo aktiviranje nevarnih kontrolnikov v Officeu.

Z njim diagnosticiramo stanje napak varnostnih ukrepov za zmanjševanje tveganja, ki bi lahko vplivale na varnost končnih uporabnikov.

Zbrana so ta polja:

  - Nobeno

#### <a name="officesecuritycomsecurityfileextensionlistfromservice"></a>Office.Security.ComSecurity.FileExtensionListFromService

Spremlja, ali je storitev konfiguriranja prebrala pripone za blokiranje pakiranja oz. je bil uporabljen privzeti seznam odjemalca. Z njim zagotovite učinkovitost varnostnih ukrepov za zmanjševanje tveganja, ki ščitijo končne uporabnike Officea.

Zbrana so ta polja:

  - **RetrievedFromServiceStatus** – Ali je bilo mogoče pridobiti seznam datotečnih pripon za blokiranje oz. kakšen je bil razlog za napako, če pripon ni bilo mogoče pridobiti.

#### <a name="officesecuritycomsecurityload"></a>Office.Security.ComSecurity.Load

Spremlja, kdaj je predmet OLE naložen v dokument. Z njim zagotovite učinkovitost varnostnih ukrepov za zmanjševanje tveganja, ki ščitijo končne uporabnike Officea.

Zbrana so ta polja:

  - **Clsid** – Identifikator razreda kontrolnika OLE.

  - **Count** – Število nalaganj kontrolnika OLE.

  - **DocUrlHash** – Enolična zgoščena vrednost dokumenta. (Opomba – to polje ne vključuje dejanskih podrobnosti o dokumentu. Je zgolj enolična predstavitev dokumenta.)

  - **IsCategorized** – Ali je kontrolnik OLE razvrščen za nalaganje v Officeu.

  - **IsInsertable** – Ali je bil kontrolnik OLE vstavljen ali ne.

#### <a name="officesecuritycomsecurityobjdetected"></a>Office.Security.ComSecurity.ObjDetected

Spremlja, kdaj je predmet OLE zaznan v dokumentu. Z njim zagotovite učinkovitost varnostnih ukrepov za zmanjševanje tveganja, ki ščitijo končne uporabnike Officea.

Zbrana so ta polja:

  - **Clsid** – Identifikator razreda kontrolnika OLE.

  - **Count** – Število zaznavanj kontrolnika OLE.

  - **DocUrlHash** – Enolična zgoščena vrednost dokumenta. (Opomba – to polje ne vključuje dejanskih podrobnosti o dokumentu. Je zgolj enolična predstavitev dokumenta.)

  - **IsCategorized** – Ali je kontrolnik OLE razvrščen za nalaganje v Officeu.

  - **IsInsertable** – Ali je bil kontrolnik OLE vstavljen ali ne.

#### <a name="officesecuritycomsecuritypackageractivation"></a>Office.Security.ComSecurity.PackagerActivation

Spremlja rezultat varnostnih ukrepov za zmanjševanje tveganja, ki blokirajo nevarne pripone, vdelane v Officeove dokumente. Z njim zagotovite učinkovitost varnostnih ukrepov za zmanjševanje tveganja, ki ščitijo končne uporabnike Officea.

Zbrana so ta polja:

  - **FromInternet** – Ali je bil dokument na voljo v internetu.

  - **PackagerSetting** – Vrsta nastavitev trenutnega pakiranja.

  - **TrustedDocument** – Ali je dokument zaupanja vreden.

#### <a name="officesecuritycomsecuritypackageractivationerrors"></a>Office.Security.ComSecurity.PackagerActivationErrors

Stanje napak varnostnih ukrepov za zmanjševanje tveganja, ki blokirajo nevarne pripone, vdelane v Officeove dokumente. Z njim zagotovite učinkovitost varnostnih ukrepov za zmanjševanje tveganja, ki ščitijo končne uporabnike Officea.

Zbrana so ta polja:

  - **Error** – Koda napake.

  - **Extension** – Vrsta datotečne pripone.

  - **FromInternet** – Ali je bil dokument na voljo v internetu.

  - **LinkedDocument** – Ali je dokument povezan ali ne.

  - **PackagerSetting** – Vrsta nastavitev trenutnega pakiranja.

  - **TrustedDocument** – Ali je dokument zaupanja vreden.


#### <a name="officesecuritymacrointernetvbablockenabled"></a>Office.Security.Macro.InternetVBABlockEnabled

Spremlja, ali je nastavitev za blokiranje makra v internetu omogočena za odjemalca. Z njim lahko ocenite varnostne ukrepe za zmanjševanje tveganja za zagotavljanje zaščite pred zlonamernimi makri.

Zbrana so ta polja:

  - Nobeno

#### <a name="officesecuritymacropolicydigsigtrustedpublishers"></a>Office.Security.Macro.PolicyDigSigTrustedPublishers

Spremlja, ali je bilo preverjeno, da je makro od zaupanja vrednega izdajatelja. Z njim zagotovite učinkovitost varnostnih ukrepov za zmanjševanje tveganja, ki ščitijo končne uporabnike Officea.

Zbrana so ta polja:

  - **Policy** – Ali je pravilnik nastavljen, ni nastavljen oz. ni na voljo.

#### <a name="officesecuritymacroprompted"></a>Office.Security.Macro.Prompted

Spremlja, kdaj je uporabnik pozvan k omogočanju makrov VBA. Z njim ocenimo razširjenost makrov VBA in zagotovimo nadaljnje varnostne ukrepe za zmanjševanje tveganja, ki preprečujejo izvajanje makrov v primeru varnostnih dogodkov.

Zbrana so ta polja:

  - **PromptType** – Vrsta prikazanega poziva.

  - **VBAMacroAntiVirusHash** – Protivirusna zgoščena vrednost makra.

  - **VBAMacroAntiVirusHRESULT** – Rezultati protivirusnega ocenjevanja.

#### <a name="officesecuritymacrovbasecureruntimesessionenablestate"></a>Office.Security.Macro.VBASecureRuntimeSessionEnableState

Spremlja preverjanje izvajalnika AMSI ob izvajanju makra. Spremlja učinkovitost preverjanja izvajalnika AMSI za izvajanje makra in prepozna napake, ki bi lahko vplivale na varnost končnih uporabnikov.

Zbrana so ta polja:

  - **IsRegistry** – Ali je skrbnik nastavil preglasitev v registru.

  - **State** – Stanje varnega izvajalnika.

#### <a name="officesecuritymacroxl4prompted"></a>Office.Security.Macro.XL4Prompted

Spremlja, kdaj je uporabnik pozvan k omogočanju makrov XL4. Z njim ocenimo razširjenost makrov XL4 v Excelu za zagotavljanje nadaljnjih varnostnih ukrepov za zmanjševanje tveganja, ki privzeto blokirajo XL4 kot odziv na varnostne dogodke zlorabe makrov XL4.

Zbrana so ta polja:

  - **PromptType** – Vrsta prikazanega poziva.


#### <a name="officesecurityocxufiprompt"></a>Office.Security.OCX.UFIPrompt

Spremlja, kdaj je varnostni poziv prikazan uporabniku ob nalaganju kontrolnika ActiveX, ki je označen kot nevaren za inicializacijo. Z njim ocenimo razširjenost kontrolnikov UFI ActiveX v Officeovih dokumentih za zagotavljanje ukrepov za zmanjševanje tveganja (npr. kontrolniki »killbit«) kot odziv na varnostne dogodke.

Zbrana so ta polja:

  - **IsFromInternet** – Ali je bil dokument odprt v internetu.

  - **IsSecureReaderMode** – Ali je bil dokument odprt v varnem bralniku.

  - **OcxTrustCenterSettings** – Kakšna je trenutna nastavitev kontrolnika ActiveX.


#### <a name="officesecuritysecurereaderhostopeninosr"></a>Office.Security.SecureReaderHost.OpenInOSR

Spremlja dokončanje odprtega zaščitenega pogleda. Z njim diagnosticiramo stanja morebitnih napak pri odpiranju datotek v zaščitenem pogledu, ki vplivajo na varnost in storilnost strank.

Zbrana so ta polja:

  - Nobeno

## <a name="product-and-service-usage-data-events"></a>Dogodki podatkov uporabe izdelka in storitve

V nadaljevanju tega članka so navedeni podatkovni podtipi v tej kategoriji:

- [Uspešnost izvajanja funkcije aplikacije](#application-feature-success-subtype)
- [Stanje in zagon aplikacije](#application-status-and-boot-subtype)
- [Konfiguracija za dostopnost sistema Office](#office-accessibility-configuration-subtype)
- [Zasebnost](#privacy-subtype)


### <a name="application-feature-success-subtype"></a>*Podtip uspešnosti izvajanja funkcije aplikacije*

Uspešnost delovanja aplikacije. Omejeno na odpiranje in zapiranje aplikacij in dokumentov, urejanje datoteke ter skupno rabo datotek (sodelovanje).

#### <a name="ipccreaterepublishinglicense"></a>IpcCreateRepublishingLicense

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij. Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride v zadnji fazi postopka, ko se izvede priklic API IpcCreateRepublishingLicense.

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se program izvaja v produkcijskem okolju ali v okolju razvijalcev

- **AppInfo.Name** – ime aplikacije

- **AppInfo.Version** – različica aplikacije

- **iKey** – ID strežnika za storitev pisanja dnevnika

- **RMS.Duration** – Skupen čas za izvedbo API priklica

- **RMS.DurationWithoutExternalOps** – skupni čas minus zunanje operacije, kot je zakasnitev omrežja.

- **RMS.ErrorCode** – koda napake je vrnjena, če katera koli izvira iz priklica API

- **RMS.HttpCall** – označite, ali je prišlo do operacije HTTP

- **RMS.Rezultat** – uspeh ali neuspeh priklica API

- **RMS.ScenarioId** – ID scenarija, ki ga določa API

- **RMS.SDKVersion** – različica odjemalca storitve za upravljanje pravic

- **RMS.StatusCode** – Koda stanja vrnjenega rezultata

#### <a name="ipcgetlicenseproperty"></a>IpcGetLicenseProperty

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij. Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede priklic API IpcCreateRepublishingLicense.

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se program izvaja v produkcijskem okolju ali v okolju razvijalcev

- **AppInfo.Name** – ime aplikacije.

- **AppInfo.Version** – različica aplikacije

- **iKey** – ID strežnika za storitev pisanja dnevnika

- **RMS.Duration** – Skupen čas za izvedbo API priklica

- **RMS.DurationWithoutExternalOps** – skupni čas minus zunanje operacije, kot je zakasnitev omrežja.

- **RMS.ErrorCode** – koda napake je vrnjena, če katera koli izvira iz priklica API

- **RMS.HttpCall** – označite, ali je prišlo do operacije HTTP

- **RMS.LicensePropertyType** – vrsta lastnosti licence

- **RMS.Rezultat** – uspeh ali neuspeh priklica API

- **RMS.ScenarioId** – ID scenarija, ki ga določa API

- **RMS.SDKVersion** – različica odjemalca storitve za upravljanje pravic

- **RMS.StatusCode** – Koda stanja vrnjenega rezultata

#### <a name="ipcgetserializedlicenseproperty"></a>IpcGetSerializedLicenseProperty

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij. Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede priklic API IpcCreateRepublishingLicense.

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se program izvaja v produkcijskem okolju ali v okolju razvijalcev

- **AppInfo.Name** – ime aplikacije.

- **AppInfo.Version** – različica aplikacije

- **iKey** – ID strežnika za storitev pisanja dnevnika

- **RMS.Duration** – Skupen čas za izvedbo API priklica

- **RMS.DurationWithoutExternalOps** – skupni čas minus zunanje operacije, kot je zakasnitev omrežja.

- **RMS.ErrorCode** – koda napake je vrnjena, če katera koli izvira iz priklica API

- **RMS.HttpCall** – označite, ali je prišlo do operacije HTTP

- **RMS.LicensePropertyType** – vrsta lastnosti licence

- **RMS.Rezultat** – uspeh ali neuspeh priklica API

- **RMS.ScenarioId** – ID scenarija, ki ga določa API

- **RMS.SDKVersion** – različica odjemalca storitve za upravljanje pravic

- **RMS.StatusCode** – Koda stanja vrnjenega rezultata

#### <a name="ipcgettemplateissuerlist"></a>IpcGetTemplateIssuerList

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij. Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede priklic API IpcGetTemplateIssuerList.

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se program izvaja v produkcijskem okolju ali v okolju razvijalcev

- **AppInfo.Name** – ime aplikacije.

- **AppInfo.Version** – različica aplikacije

- **iKey** – ID strežnika za storitev pisanja dnevnika

- **RMS.AuthCallbackProvided** – označite, če zagotavlja preverjanje pristnosti s povratnim klicem kot vhod priklica API ali ne

- **RMS.ConnectionInfo.ExtranetUrl** – URL ekstraneta podatkov povezave

- **RMS.ConnectionInfo.IntranetUrl**– URL intraneta podatkov povezave

- **RMS.ConnectionMode** – način povezave med odjemalcem in strežnikom storitev za upravljanje pravic: z vzpostavljeno povezavo ali brez povezave

- **RMS.Duration** – Skupen čas za izvedbo API priklica

- **RMS.DurationWithoutExternalOps** – skupni čas minus zunanje operacije, kot je zakasnitev omrežja.

- **RMS.ErrorCode** – koda napake je vrnjena, če katera koli izvira iz priklica API

- **RMS.GuestTenant** – ID gosta najemnika za uporabnika

- **RMS.HomeTenant** – ID domačega najemnika za uporabnika

- **RMS.HttpCall** – označite, ali je prišlo do operacije HTTP

- **RMS.Identity.ExtranetUrl** – URL ekstraneta strežnika za upravljanje pravic za uporabnika, ki je bil zbran pri pridobivanju novega potrdila o računu pravic iz strežnika
 
- **RMS.Identity.ExtranetUrl** – URL intraneta strežnika za upravljanje pravic za uporabnika, ki je bil zbran pri pridobivanju novega potrdila o računu pravic iz strežnika

- **RMS.Identity.Status** – ko prvič dobite potrdilo o računu pravic iz strežnika ali obnovite potrdilo o računu pravic 

- **RMS.Identity.Type** – vrsta uporabniškega računa, kot je račun za Windows ali račun Live

- **RMS.Identity.UserProvided** – določite, ali je e-poštni naslov naveden ali ne, medtem ko pridobivate novo potrdilo o računu pravic od strežnika

- **RMS.IssuerId** – ID strežnika za upravljanje pravic, ki izda potrdilo o računu pravic 

- **RMS.LicenseFormat** – oblika licence: Xrml ali Json

- **RMS.RACType** – vrsta potrdila o računu pravic

- **RMS.Rezultat** – uspeh ali neuspeh priklica API

- **RMS.ScenarioId** – ID scenarija, ki ga določa API

- **RMS.SDKVersion** – različica odjemalca storitve za upravljanje pravic

- **RMS.ServerType** – vrsta strežnika za upravljanje pravic do storitev

- **RMS.StatusCode** – Koda stanja vrnjenega rezultata

- **UserInfo.UserObjectId** – ID predmeta uporabnika

#### <a name="ipcgettemplatelist"></a>IpcGetTemplateList

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij. Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede priklic API IpcGetTemplateList.

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se program izvaja v produkcijskem okolju ali v okolju razvijalcev

- **AppInfo.Name** – ime aplikacije.

- **AppInfo.Version** – različica aplikacije

- **iKey** – ID strežnika za storitev pisanja dnevnika

- **RMS.AuthCallbackProvided** – označite, če zagotavlja preverjanje pristnosti s povratnim klicem kot vhod priklica API ali ne

- **RMS.ConnectionInfo.ExtranetUrl** – URL ekstraneta podatkov povezave

- **RMS.ConnectionInfo.IntranetUrl**– URL intraneta podatkov povezave

- **RMS.ConnectionMode** – način povezave med odjemalcem in strežnikom storitev za upravljanje pravic: z vzpostavljeno povezavo ali brez povezave

- **RMS.Duration** – Skupen čas za izvedbo API priklica

- **RMS.DurationWithoutExternalOps** – skupni čas minus zunanje operacije, kot je zakasnitev omrežja.

- **RMS.ErrorCode** – koda napake je vrnjena, če katera koli izvira iz priklica API

- **RMS.GuestTenant** – ID gosta najemnika za uporabnika

- **RMS.HomeTenant** – ID domačega najemnika za uporabnika

- **RMS.HttpCall** – označite, ali je prišlo do operacije http

- **RMS.Identity.ExtranetUrl** – URL ekstraneta strežnika za upravljanje pravic za uporabnika, ki je bil zbran pri pridobivanju novega potrdila o računu pravic iz strežnika
 
- **RMS.Identity.ExtranetUrl** – URL intraneta strežnika za upravljanje pravic za uporabnika, ki je bil zbran pri pridobivanju novega potrdila o računu pravic iz strežnika

- **RMS.Identity.Status** – ko prvič dobite potrdilo o računu pravic iz strežnika ali obnovite potrdilo o računu pravic 

- **RMS.Identity.Type** – vrsta uporabniškega računa, kot je račun za Windows ali račun Live

- **RMS.Identity.UserProvided** – določite, ali je e-poštni naslov naveden ali ne, medtem ko pridobivate novo potrdilo o računu pravic od strežnika

- **RMS.IssuerId** – ID strežnika za upravljanje pravic, ki izda potrdilo o računu pravic 

- **RMS.LicenseFormat** – oblika licence: Xrml ali Json

- **RMS.RACType** – vrsta potrdila o računu pravic

- **RMS.Rezultat** – uspeh ali neuspeh priklica API

- **RMS.ScenarioId** – ID scenarija, ki ga določa API

- **RMS.SDKVersion** – različica odjemalca storitve za upravljanje pravic

- **RMS.ServerType** – vrsta strežnika za upravljanje pravic do storitev

- **RMS.StatusCode** – Koda stanja vrnjenega rezultata

- **RMS.TemplatesCount** – število predlog

- **UserInfo.UserObjectId** – ID predmeta uporabnika

#### <a name="ipcpcreatelicensefromscratch"></a>IpcpCreateLicenseFromScratch

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij. Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride v zadnji fazi postopka, ko se izvede priklic API IpcCreateLicenseFromScratch.

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se program izvaja v produkcijskem okolju ali v okolju razvijalcev

- **AppInfo.Name** – ime aplikacije.

- **AppInfo.Version** – različica aplikacije

- **iKey** – ID strežnika za storitev pisanja dnevnika

- **RMS.Duration** – Skupen čas za izvedbo API priklica

- **RMS.DurationWithoutExternalOps** – skupni čas minus zunanje operacije, kot je zakasnitev omrežja.

- **RMS.ErrorCode** – koda napake je vrnjena, če katera koli izvira iz priklica API

- **RMS.GuestTenant** – ID gosta najemnika za uporabnika

- **RMS.HomeTenant** – ID domačega najemnika za uporabnika

- **RMS.HttpCall** – označite, ali je prišlo do operacije HTTP

- **RMS.Identity.ExtranetUrl** – URL ekstraneta strežnika za upravljanje pravic za uporabnika, ki je bil zbran pri pridobivanju novega potrdila o računu pravic iz strežnika

- **RMS.Identity.ExtranetUrl** – URL intraneta strežnika za upravljanje pravic za uporabnika, ki je bil zbran pri pridobivanju novega potrdila o računu pravic iz strežnika

- **RMS.Identity.UserProvided** – določite, ali je e-poštni naslov naveden ali ne, medtem ko pridobivate novo potrdilo o računu pravic od strežnika

- **RMS.IssuerId** – ID strežnika za upravljanje pravic, ki izda potrdilo o računu pravic 

- **RMS.LicenseFormat** – oblika licence: Xrml ali Json

- **RMS.RACType** – vrsta potrdila o računu pravic

- **RMS.Rezultat** – uspeh ali neuspeh priklica API

- **RMS.ScenarioId** – ID scenarija, ki ga določa API

- **RMS.SDKVersion** – različica odjemalca storitve za upravljanje pravic

- **RMS.ServerType** – vrsta strežnika za upravljanje pravic do storitev

- **RMS.StatusCode** – Koda stanja vrnjenega rezultata

- **RMS.TokenProvided** – označuje, ali je žeton ponujen kot vhod klica API ali ne 

- **RMS.TokenProvided** – označuje, ali je žeton ponujen kot vhod klica API ali ne 

- **UserInfo.UserObjectId** – ID predmeta uporabnika 

#### <a name="ipcpcreatelicensefromtemplate"></a>IpcpCreateLicenseFromTemplate

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij. Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride v zadnji fazi postopka, ko se izvede priklic API IpcCreateLicenseFromTemplate. 

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se program izvaja v produkcijskem okolju ali v okolju razvijalcev

- **AppInfo.Name** – ime aplikacije.

- **AppInfo.Version** – različica aplikacije

- **iKey** – ID strežnika za storitev pisanja dnevnika

- **RMS.AuthCallbackProvided** – označite, če zagotavlja preverjanje pristnosti s povratnim klicem kot vhod priklica API ali ne

- **RMS.ConnectionMode** – način povezave med odjemalcem in strežnikom storitev za upravljanje pravic: z vzpostavljeno povezavo ali brez povezave

- **RMS.Duration** – Skupen čas za izvedbo API priklica

- **RMS.DurationWithoutExternalOps** – skupni čas minus zunanje operacije, kot je zakasnitev omrežja.

- **RMS.ErrorCode** – koda napake je vrnjena, če katera koli izvira iz priklica API

- **RMS.HttpCall** – označite, ali je prišlo do operacije http

- **RMS.Rezultat** – uspeh ali neuspeh priklica API

- **RMS.ScenarioId** – ID scenarija, ki ga določa API

- **RMS.SDKVersion** – različica odjemalca storitve za upravljanje pravic

- **RMS.StatusCode** – Koda stanja vrnjenega rezultata

- **RMS.TokenProvided** – označuje, ali je žeton ponujen kot vhod klica API ali ne 

- **RMS.TokenProvided** – označuje, ali je žeton ponujen kot vhod klica API ali ne 

#### <a name="ipcpgettemplatelistforuser"></a>IpcpGetTemplateListForUser

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij. Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede priklic API IpcGetTemplateListForUser. 

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se program izvaja v produkcijskem okolju ali v okolju razvijalcev

- **AppInfo.Name** – ime aplikacije.

- **AppInfo.Version** – različica aplikacije

- **iKey** – ID strežnika za storitev pisanja dnevnika

- **RMS.ApplicationScenarioId** – ID scenarija, ki ga je posredovala aplikacija

- **RMS.AuthCallbackProvided** – označite, če zagotavlja preverjanje pristnosti s povratnim klicem kot vhod priklica API ali ne

- **RMS.ConnectionInfo.ExtranetUrl** – URL ekstraneta podatkov povezave

- **RMS.ConnectionInfo.IntranetUrl**– URL intraneta podatkov povezave

- **RMS.ConnectionMode** – način povezave med odjemalcem in strežnikom storitev za upravljanje pravic: z vzpostavljeno povezavo ali brez povezave

- **RMS.Duration** – Skupen čas za izvedbo API priklica

- **RMS.DurationWithoutExternalOps** – skupni čas minus zunanje operacije, kot je zakasnitev omrežja.

- **RMS.ErrorCode** – koda napake je vrnjena, če katera koli izvira iz priklica API

- **RMS.GuestTenant** – ID gosta najemnika za uporabnika

- **RMS.HomeTenant** – ID domačega najemnika za uporabnika

- **RMS.HttpCall** – označite, ali je prišlo do operacije HTTP

- **RMS.Identity.ExtranetUrl** – URL ekstraneta strežnika za upravljanje pravic za uporabnika, ki je bil zbran pri pridobivanju novega potrdila o računu pravic iz strežnika

- **RMS.Identity.ExtranetUrl** – URL intraneta strežnika za upravljanje pravic za uporabnika, ki je bil zbran pri pridobivanju novega potrdila o računu pravic iz strežnika

- **RMS.Identity.Status** – ko prvič dobite potrdilo o računu pravic iz strežnika ali obnovite potrdilo o računu pravic 

- **RMS.Identity.Type** – vrsta uporabniškega računa, kot je račun za Windows ali račun Live

- **RMS.Identity.UserProvided** – določite, ali je e-poštni naslov naveden ali ne, medtem ko pridobivate novo potrdilo o računu pravic od strežnika

- **RMS.IssuerId** – ID strežnika za upravljanje pravic, ki izda potrdilo o računu pravic 

- **RMS.LicenseFormat** – oblika licence: Xrml ali Json

- **RMS.RACType** – vrsta potrdila o računu pravic

- **RMS.Rezultat** – uspeh ali neuspeh priklica API

- **RMS.ScenarioId** – ID scenarija, ki ga določa API

- **RMS.SDKVersion** – različica odjemalca storitve za upravljanje pravic

- **RMS.ServerType** – vrsta strežnika za upravljanje pravic do storitev

- **RMS.StatusCode** – Koda stanja vrnjenega rezultata

- **RMS.TemplatesCount** – število predlog

- **RMS.TokenProvided** – označuje, ali je žeton ponujen kot vhod klica API ali ne 
    
- **RMS.TokenProvided** – označuje, ali je žeton ponujen kot vhod klica API ali ne 

- **UserInfo.UserObjectId** – ID predmeta uporabnika 

#### <a name="ipcpserializelicense"></a>IpcpSerializeLicense

Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride v zadnji fazi postopka, ko se izvede priklic API IpcpSerializeLicense.

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se program izvaja v produkcijskem okolju ali v okolju razvijalcev

- **AppInfo.Name** – ime aplikacije.

- **AppInfo.Version** – različica aplikacije

- **iKey** – ID strežnika za storitev pisanja dnevnika

- **RMS.ApplicationScenarioId** – ID scenarija, ki ga je posredovala aplikacija

- **RMS.AuthCallbackProvided** – označite, če zagotavlja preverjanje pristnosti s povratnim klicem kot vhod priklica API ali ne

- **RMS.ConnectionMode** – način povezave med odjemalcem in strežnikom storitev za upravljanje pravic: z vzpostavljeno povezavo ali brez povezave

- **RMS.ContentId** – ID vsebine dokumenta

- **RMS.Duration** – Skupen čas za izvedbo API priklica

- **RMS.DurationWithoutExternalOps** – skupni čas minus zunanje operacije, kot je zakasnitev omrežja.

- **RMS.ErrorCode** – koda napake je vrnjena, če katera koli izvira iz priklica API

- **RMS.GuestTenant** – ID gosta najemnika za uporabnika

- **RMS.HomeTenant** – ID domačega najemnika za uporabnika

- **RMS.HttpCall** – označite, ali je prišlo do operacije http

- **RMS.Identity.ExtranetUrl** – URL ekstraneta strežnika za upravljanje pravic za uporabnika, ki je bil zbran pri pridobivanju novega potrdila o računu pravic iz strežnika

- **RMS.Identity.ExtranetUrl** – URL intraneta strežnika za upravljanje pravic za uporabnika, ki je bil zbran pri pridobivanju novega potrdila o računu pravic iz strežnika

- **RMS.Identity.Status** – ko prvič dobite potrdilo o računu pravic iz strežnika ali obnovite potrdilo o računu pravic 

- **RMS.Identity.Type** – vrsta uporabniškega računa, kot je račun za Windows ali račun Live

- **RMS.Identity.UserProvided** – določite, ali je e-poštni naslov naveden ali ne, medtem ko pridobivate novo potrdilo o računu pravic od strežnika

- **RMS.IssuerId** – ID strežnika za upravljanje pravic, ki izda potrdilo o računu pravic 

- **RMS.KeyHandle** – pomnilniški naslov kode za dostop

- **RMS.LicenseFormat** – oblika licence: Xrml ali Json

- **RMS.RACType** – vrsta potrdila o računu pravic

- **RMS.Rezultat** – uspeh ali neuspeh priklica API

- **RMS.ScenarioId** – ID scenarija, ki ga določa API

- **RMS.SDKVersion** – različica odjemalca storitve za upravljanje pravic

- **RMS.ServerType** – vrsta strežnika za upravljanje pravic do storitev

- **RMS.StatusCode** – Koda stanja vrnjenega rezultata

- **RMS.TokenProvided** – označuje, ali je žeton ponujen kot vhod klica API ali ne 

- **RMS.TokenProvided** – označuje, ali je žeton ponujen kot vhod klica API ali ne 

- **UserInfo.UserObjectId** – ID predmeta uporabnika 

#### <a name="ipcsetlicenseproperty"></a>IpcSetLicenseProperty

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij. Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede priklic API  IpcSetLicenseProperty. 

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se program izvaja v produkcijskem okolju ali v okolju razvijalcev

- **AppInfo.Name** – ime aplikacije.

- **AppInfo.Version** – različica aplikacije

- **iKey** – ID strežnika za storitev pisanja dnevnika

- **RMS.Duration** – Skupen čas za izvedbo API priklica

- **RMS.DurationWithoutExternalOps** – skupni čas minus zunanje operacije, kot je zakasnitev omrežja.

- **RMS.ErrorCode** – koda napake je vrnjena, če katera koli izvira iz priklica API 

- **RMS.HttpCall** – označite, ali je prišlo do operacije http

- **RMS.LicensePropertyType** – vrsta lastnosti licence

- **RMS.Rezultat** – uspeh ali neuspeh priklica API

- **RMS.ScenarioId** – ID scenarija, ki ga določa API

- **RMS.SDKVersion** – različica odjemalca storitve za upravljanje pravic

- **RMS.StatusCode** – ID scenarija, ki ga določa API


#### <a name="officeappcompatappcompatagentupload"></a>Office.AppCompat.AppCompat.AgentUpload

Ustvarjeno je ob zagonu odjemalca, če je končni uporabnik omogočil nadzorno ploščo za telemetrijo sistema Office.  Zbira informacije o tem, kdaj je posrednik za telemetrijo sistema Office prenesel podatke v mapo v skupni rabi. Primarna uporaba tega dogodka je spremljanje ustreznosti stanja posrednika za telemetrijo sistema Office, sekundarna uporaba dogodka pa je ocena uporabe nadzorne plošče za telemetrijo sistema Office.

Zbrana so naslednja polja:

- **UploadTime** – časovni žig zadnjega uspešnega prenosa, ki ga je izvedel posrednik za telemetrijo.


#### <a name="officeappcompatappcompatagentscanandupload"></a>Office.AppCompat.AppCompat.AgentScanAndUpload

Podatki so zbrani le, če je uporabnik omogočil nadzorno ploščo za telemetrijo sistema Office. Zbira informacije o tem, kdaj se izvaja posrednik za telemetrijo sistema Office.  Ti podatki so zbrani le, če je nadzorna plošča za telemetrijo sistema Office omogočena in uporabljena za določanje ustreznosti stanja posrednika za telemetrijo sistema Office.

Zbrana so ta polja:

  - **Data.AgentExit** – Časovni žig, ko se je posrednik za telemetrijo uspešno zaprl.

  - **Data.AgentScan** – Časovni žig, ko je posrednik za telemetrijo uspešno dokončal pregled.

  - **Data.AgentUpload** – Časovni žig, ko je posrednik za telemetrijo uspešno dokončal nalaganje.

#### <a name="officeappcompatappcompattelemetrydashboardresiliencycrashlog"></a>Office.AppCompat.AppCompat.TelemetryDashboardResiliencyCrashLog

Ti podatki so zbrani le, če je končni uporabnik (najverjetneje skrbnik) omogočil nadzorno ploščo za telemetrijo sistema Office. Zbira pojavitve dodatkov za Office in zrušitve dokumentov. Ti podatki so zbrani le, če je končni uporabnik omogočil nadzorno ploščo za telemetrijo sistema Office. Z njimi določimo morebitno povečano pojavitev dodatkov ali zrušitev dokumentov.

Zbrana so ta polja:

  - **Data.CollectionTime** – Časovni žig, kdaj je bil zabeležen dogodek zrušitve.

#### <a name="office_apple_cisauthticketwithidentity"></a>Office_Apple_CISAuthTicketWithIdentity

Ta dogodek se zbira za Officeove programe, ki se izvajajo na platformah Apple. Dogodek se uporablja za zajemanje napak pri ustvarjanju žetonov za preverjanje pristnosti med InAppPurchase v računalniku Mac (dogodek zabeleži kodo napake, ki jo je prejel).  Ta dogodek se uporablja za odkrivanje in pomoč pri odpravljanju napak pri ustvarjanju žetonov za preverjanje pristnosti

Zbrana so naslednja polja:

- **Data_EmptyAuthToken** – zbrali smo niz, ki predstavlja, kje v neprekinjenem poteku licence je prišlo do napake.

- **Data_TicketAuthError** – koda napake, ki označuje vzrok napake

- **Data_ValidIdentity** – če ima odjemalec veljavno identiteto



#### <a name="officeconnectdeviceactivitystart"></a>Office.ConnectDevice.Activity.Start

Dogodek nam omogoča prepoznavanje uspešne povezave z napravo ali aplikacijo.  Uporabljamo ga za zagotavljanje ustreznosti delovanja funkcij in nadzor. Ta dogodek ustvari Microsoftovo orodje za pretakanje podatkov za dodatek za Excel.

Zbrana so ta polja:

- **Datasource_Type** – Informacije o serijski napravi ali storitvi aplikacije.

- **DataSource_Name** – Ime povezanega vira podatkov.

- **Activity_Name** – Ime dejavnosti »ConnectDevice«.

- **Activity_CV** – ID za povezovanje dogodkov v seji povezave.

- **Activity_StartStopType** – Začetek.

- **Activity_DateTimeTicks** – Datum in čas dejavnosti.
 
#### <a name="officeconnectdeviceactivitystop"></a>Office.ConnectDevice.Activity.Stop

Dogodek nam omogoča prepoznavanje uspešne povezave z napravo ali aplikacijo. Uporabljamo ga za zagotavljanje ustreznosti stanja in spremljanje. Ta dogodek ustvari Microsoftovo orodje za pretakanje podatkov za dodatek za Excel.

Zbrana so ta polja:

- **Datasource_Type** – Informacije o serijski napravi ali storitvi aplikacije.

- **DataSource_Name** – Ime povezanega vira podatkov.

- **Activity_Name** – Ime dejavnosti »ConnectDevice«.

- **Activity_CV** – ID za povezovanje dogodkov v seji povezave.

- **Activity_StartStopType** – Konec.

- **Activity_DateTimeTicks** – Datum in čas dejavnosti.

#### <a name="officeextensibilitycatalogexchangeprocessentitlement"></a>Office.Extensibility.Catalog.ExchangeProcessEntitlement

Podatki o obdelavi posameznih upravičenosti za najemnika in skrbnika storitve Office 365, ki jima je dodeljen dodatek.

Uporabljamo ga za grafikone (zahteva ga upravljanje skupin) za določanje uspešnosti strank in analiziranje težav strank.

Zbrana so ta polja:

  - **AppVersion** – Različica gostiteljske aplikacije dodatka.

  - **SolutionId** – GUID, ki predstavlja enolični dodatek.

  - **TelemetryId** – GUID, ki predstavlja enoličnega uporabnika.

#### <a name="officeextensibilitycatalogexchangeprocessmanifest"></a>Office.Extensibility.Catalog.ExchangeProcessManifest

Podatki o obdelavi posameznega manifesta za dodatek najemnika storitve Office 365, ki ga dodeli skrbnik. Uporablja se pri analizi težav stranke in ustvarjanju grafikonov strankinega uspeha.
 
Zbrana so naslednja polja:

- **AppVersion** – različica aplikacije.

- **IsAllReturnedManifestsParsed** – logična vrednost, ki označuje, da smo razčlenili vse vrnjene manifeste.

- **IsAppCommand** – logična vrednost, ki označuje, da je to ukaz aplikacije. 

- **ReturnedManifestsParsed** – število razčlenjenih manifestov.

- **SolutionId** – ID rešitve

- **TelemetryId** – ID telemetrije, ki temelji na vpisani identiteti

#### <a name="officeextensibilityodpappcommandsribbonclick"></a>Office.Extensibility.ODPAppCommandsRibbonClick

Zbira podatke o tem, ali je bilo klikanje kontrolnika dodatka po meri uspešno ali ne. Uporablja se za zaznavanje težav pri interakciji uporabnikov s kontrolniki dodatkov.
 
Zbrana so naslednja polja:

- **CommandActionType** – vrsta ukaza dodatka.

- **CommandLabel** – oznaka kliknjenega ukaza.

- **SolutionId** – ID rešitve

#### <a name="officefileiocsiccachedfilecsiloadfilebasic"></a>Office.FileIO.CSI.CCachedFileCsiLoadFileBasic

S tem dogodkom lahko prepoznamo, ali je bila datoteka uspešno odprta v plasti FIO. Uporabljamo ga za zagotavljanje ustreznosti delovanja funkcij in nadzor.

Zbrana so ta polja:

  - **Activity.Group** – Oznaka, ki omogoča združevanje nabora dogodkov nadzora za upravljanje uspešnega delovanja.

  - **Activity.IsHVA** – Zastavica, ki označuje, da je dogodek ključen za zagotavljanje uspešnega delovanja za uporabnika.

  - **Data.AsyncOpen** – Zastavica, ki označuje odpiranje vsebine, prejete potem, ko je bilo glavno telo dokumenta že odprto.

  - **Data.CacheFileId** – Povezava do telemetrije predpomnilnika Officeovih dokumentov za omogočanje analize posledic težav s predpomnilnikom na uporabniško izkušnjo.

  - **Data.CoauthStatus** – Poroča o stanju sodelovanja v dokumentu ob odpiranju.

  - **Data.CountOfMultiRoundTripsDownload** – Število vrnitev v strežnik, ki se uporablja za odpravljanje težav z učinkovitostjo delovanja in omrežjem.

  - **Data.CountOfMultiRoundTripsUpload** – Število vrnitev v strežnik, ki se uporablja za odpravljanje težav z učinkovitostjo delovanja in omrežjem.

  - **Data.DialogId** – To polje je nastavljeno, če je bilo pogovorno okno za UI prikazano med odpiranjem, in označuje, da je uporabnik prejel opozorilno sporočilo.

  - **Data.DidFallbackToDAV** – To polje je nastavljeno, če je bil dokument odprt s starejšim protokolom za prenos datotek.

  - **Data.Doc.AccessMode** – Dokument je samo za branje/ga je mogoče urejati.

  - **Data.Doc.AssistedReadingReasons** – To polje je nastavljeno, če je za dokument izbrana elektronska zaščita podatkov.

  - **Data.Doc.AsyncOpenKind – ** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

  - **Data.Doc.ChunkingType** – Enote, uporabljene za postopno odpiranje dokumenta.

  - **Data.Doc.EdpState** – Nastavitev elektronske zaščite podatkov dokumenta.

  - **Data.Doc.Ext** – Pripona dokumenta (docx/xlsb/pptx itd.).

  - **Data.Doc.Extension** – Zastarelo.

  - **Data.Doc.FileFormat** – Različica protokola za obliko zapisa dokumenta.

  - **Data.Doc.Fqdn** – Ime domene za OneDrive ali SharePoint Online.

  - **Data.Doc.FqdnHash** – Enostranska zgoščena vrednost imena domene, ki omogoča identifikacijo stranke.

  - **Data.Doc.IdentityTelemetryId** – Enostranska zgoščena vrednost identitete uporabnika, uporabljena za odpiranje.

  - **Data.Doc.IdentityUniqueId** – Zastarelo.

  - **Data.Doc.InitializationScenario** – Zabeleži način odpiranja dokumenta.

  - **Data.Doc.IOFlags** – Poroča o predpomnjenih zastavicah, uporabljenih za nastavitev možnosti zahtev.

  - **Data.Doc.IrmRights** – Dejanja, ki jih je dovolil pravilnik za elektronsko zaščito podatkov, ki velja za dokument/uporabnika.

  - **Data.Doc.IsCloudCollabEnabled** – Zastavica, ki označuje, da storitev podpira sodelovanje v oblaku.

  - **Data.Doc.IsIncrementalOpen** – Zastavica, ki označuje postopno odpiranje dokumenta.

  - **Data.Doc.IsOcsSupported** – Zastavica, ki označuje, da storitev sodelovanja podpira dokument.

  - **Data.Doc.IsOpeningOfflineCopy** – Zastavica, ki označuje, da je bila odprta kopija dokumenta brez povezave.

  - **Data.Doc.IsSyncBacked** – Zastavica, ki označuje, da v računalniku obstaja samodejno sinhronizirana kopija dokumenta.

  - **Data.Doc.Location** – Označuje, v kateri storitvi je na voljo dokument (OneDrive, File Server, SharePoint itd.).

  - **Data.Doc.LocationDetails** – Označuje, v kateri znani mapi je na voljo lokalno shranjen dokument.

  - **Data.Doc.NumberCoAuthors** – Število uporabnikov v seji urejanja s sodelovanjem.

  - **Data.Doc.PasswordFlags** – Označuje nastavljeno zastavico za branje ali branje/pisanje gesla.

  - **Data.Doc.ReadOnlyReasons** – Razlogi, zakaj je bil dokument odprt v načinu »Samo za branje«.

  - **Data.Doc.ResourceIdHash** – Anonimni identifikator dokumenta za diagnosticiranje težav.

  - **Data.Doc.ServerDocId** – Nespremenljivi anonimni identifikator dokumenta za diagnosticiranje težav.

  - **Data.Doc.ServerProtocol** – Različica protokola za komunikacijo s storitvijo.

  - **Data.Doc.ServerType** – Vrsta strežnika, ki zagotavlja storitev (SharePoint, OneDrive, WOPI itd.).

  - **Data.Doc.ServerVersion** – Različica strežnika, ki zagotavlja storitev.

  - **Data.Doc.SessionId** – Prepozna določeno sejo za urejanje dokumenta v celotni seji.

  - **Data.Doc.SharePointServiceContext** – Diagnostične informacije SharePoint Onlineovih zahtev.

  - **Data.Doc.SizeInBytes** – Indikator velikosti dokumenta.

  - **Data.Doc.SpecialChars** – Indikator posebnih znakov v URL-ju ali poti dokumenta.

  - **Data.Doc.StorageProviderId** – Zastarelo.

  - **Data.Doc.StreamAvailability** – Indikator, ali je tok dokumenta na voljo/onemogočen.

  - **Data.Doc.SyncBackedType** – Indikator vrste dokumenta (lokalno ali storitev).

  - **Data.Doc.UrlHash** – Enostranska zgoščena vrednost za ustvarjanje naivnega identifikatorja dokumenta.

  - **Data.Doc.UsedWrsDataOnOpen** – Diagnostični indikator postopnega odpiranja dokumenta.

  - **Data.Doc.WopiServiceId** – Vsebuje enolični identifikator za ponudnika storitve WOPI.

  - **Data.DocumentLoadEndpoint** – Zastarel/odvečen dvojnik (»Data.Doc.Location« in »Data.Doc.IsSyncbacked«).

  - **Data.DocumentSizeInBytes** – Zastarelo/odvečeno polje, ki ga je nadomestilo polje »Data.Doc. SizeInBytes«.

  - **Data.DocumentSizeOnDisk** – Zastarelo.

  - **Data.DoesBaseHaveContentOnOpen** – Diagnostika sledenja spremembam za zagotavljanje najnovejše različice datoteke v skupni rabi.

  - **Data.DoesWorkingBranchHaveExcludedDataOnOpen** – Diagnostika sledenja spremembam za zagotavljanje najnovejše različice datoteke v skupni rabi.

  - **Data.DownloadFragmentSize** – Velikost poslanih podatkov v podzahtevi za diagnosticiranje omrežnih težav.

  - **Data.DsmcStartedTooEarly** – Označuje napako z začetkom seje urejanja s sodelovanjem.

  - **Data.EditorsCount** – Število drugih sodelavcev, ki urejajo dokument.

  - **Data.ExcludedDataThresholdInBytes** – Velikost datoteke, zahtevana za uporabo asinhronega odpiranja.

  - **Data.FileIOResult.Code** – Predpomnilnik vrnjene kode zadnjega odpiranja plasti protokola.

  - **Data.FileIOResult.Success** – Predpomnilnik indikatorja uspešnega zadnjega odpiranja plasti protokola.

  - **Data.FileIOResult.Tag** – Predpomnilnik oznake napake zadnjega odpiranja plasti protokola.

  - **Data.FileIOResult.Type** – Predpomnilnik vrste napake zadnjega odpiranja plasti protokola.

  - **Data.FqdnHash** – Zastarelo; zamenjalo ga je polje »Data\_Doc\_FqdnHash«.

  - **Data.FullIError** – Predpomnilnik kod napak vseh odpiranj plasti protokola.

  - **Data.FullyQualifiedDomainName** – Zastarelo; zamenjalo ga je polje »Data\_Doc\_Fqdn«.

  - **Data.Input.FileOpenState** – Stanje, ki ga zahteva aplikacija (branje/branje in pisanje itd.)

  - **Data.Input.OpenAsync** – Asinhrono odpiranje, ki ga zahteva aplikacija.

  - **Data.Input.OpenOfflineCopy** – Odpiranje kopije brez povezave, ki ga zahteva aplikacija.

  - **Data.IOFlags** – Zastarelo.

  - **Data.IsBaseBranchEmptyOnOpen** – Diagnostika sledenja spremembam za zagotavljanje najnovejše različice datoteke v skupni rabi.

  - **Data.IsCachedHistoricalVersion** – Predpomnilnik vsebuje starejšo različico dokumenta.

  - **Data.IsDocEnterpriseProtected** – Dokument je bil zaščiten s šifriranjem (elektronska zaščita dokumentov/EDP).

  - **Data.IsDocInODC** – Dokument je bil odprt v preteklosti in je že v predpomnilniku.

  - **Data.IsMapUnMapCase** – Del stanja predpomnjene datoteke.

  - **Data.IsMapUnMapCase.End** – Del stanja predpomnjene datoteke.

  - **Data.IsOfficeHydrationInProgress** – Dokument je shranjen v prostoru za shranjevanje brez povezave v sistemu Windows.

  - **Data.isOfficeHydrationRequired** – Dokument je trenutno v prostoru za shranjevanje brez povezave.

  - **Data.isOpenFromCollab** – Najnovejša kopija dokumenta je bila pridobljena iz storitve za sodelovanje v skupni rabi.

  - **Data.isPendingNameExist** – Poteka preimenovanje dokumenta.

  - **Data.IsStubFile** – Dokument še ni bil shranjen v storitev v oblaku.

  - **Data.IsSyncBackedStateDifferentThanOnLastOpen** – Stanje dokumenta je bilo spremenjeno; spremembe so bile morda izvedene, ko dokument ni bil odprt.

  - **Data.isTaskCanceledAfterOpenComplete** – Zastarelo.

  - **Data.IsWorkingBranchAvailableOnOpen** – Diagnostika sledenja spremembam za zagotavljanje najnovejše različice datoteke v skupni rabi.

  - **Data.LicenseStatus** – stanje licence izdelka za diagnostiko, uporabljenega za preverjanje, ali so ustrezne funkcije izdelka omogočene za vrsto licence uporabnika. 

  - **Data.LicenseType** – Označuje stanje licence (brezplačno/plačljivo/preskusna različica itd.).

  - **Data.Location** – Označuje vrsto/lokacijo predstavnosti shrambe (USB, oblak itd.).

  - **Data.LockRequestDocMode** – Označuje, ali je dokument na voljo drugim osebam.

  - **Data.MyDeferredValue** – Zastarelo.

  - **Data.Network.BytesReceived** – Zastarelo.

  - **Data.Network.BytesSent** – Zastarelo.

  - **Data.Network.ConnectionsCreated** – Zastarelo.

  - **Data.Network.ConnectionsEnded** – Zastarelo.

  - **Data.OcsDisableReasons** – Razlog, zakaj ni na voljo storitev sodelovanja v skupni rabi za dokument.

  - **Data.OcsHostOnOpen** – Zastavica, ki označuje, da bo kontrolnik med odpiranjem preklopljen v storitev sodelovanja v skupni rabi.

  - **Data.OpeningOfflineCopy** – Zastavica, ki označuje, da bo odprta lokalna kopija dokumenta.

  - **Data.Partition** – Zastarelo.

  - **Data.RequestTime** – Zastarelo.

  - **Data.ResourceIdHash** – Zastarelo.

  - **Data.ResumedIncrementalOpen** – Zastarelo.

  - **Data.RTCEnabled** – Začetek izvajanja protokola za hitro distribucijo sprememb.

  - **Data.SaveOnOpen** – Neshranjene spremembe v lokalnem dokumentu so bile shranjene v storitev med odpiranjem.

  - **Data.ServerProtocol** – Zastarelo; zamenjalo ga je polje »Data\_Doc\_ServerProtocol«.

  - **Data.ServerType** – Zastarelo; zamenjalo ga je polje »Data\_Doc\_ServerType«.

  - **Data.ServerVersion** – Zastarelo; zamenjalo ga je polje »Data\_Doc\_ServerVersion«.

  - **Data.ServiceId** – Zastarelo; zamenjalo ga je polje »Data\_Doc\_WopiServiceId«.

  - **Data.SessionId** – Zastarelo.

  - **Data.ShouldSwitchToServerOnly** – Lokalne kopije dokumenta ni mogoče uporabljati, uporabljena mora biti različica strežnika.

  - **Data.SpecialChars** – Zastarelo.

  - **Data.StopwatchDuration** – Zastarelo.

  - **Data.SyncBackedFileTelemetrySessionId** – Zastarelo.

  - **Data.SyncElapsedTime** – Zastarelo.

  - **Data.SyncRequestId** – Zastarelo.

  - **Data.TestProperty** – Zastarelo.

  - **Data.TransitionToHostOnOpen** – Zastavica, ki označuje, da bo seja povezana s storitvijo, ki gosti dokument.

  - **Data.TransitionToHostOnOpenResult** – Stanje prehoda v gostiteljsko storitev.

  - **Data.UseCachedNetworkConnection** – Zastavica, ki označuje, ali je bila povezava znova uporabljena oz. ustvarjena nova povezava.

  - **Data.UseClientIdAsSchemaLockId** – Zastavica za nadzor načina zaklepanja dokumentov v storitvi.

  - **Data.WopiServiceId** – Zastarelo; zamenjalo ga je polje »Data\_Doc\_WopiServiceId«.

#### <a name="officefileiocsiccachedfilecsisavefilebasic"></a>Office.FileIO.CSI.CCachedFileCsiSaveFileBasic

S tem dogodkom lahko prepoznamo, ali je bila datoteka uspešno shranjena v plasti FIO. Uporabljamo ga za zagotavljanje ustreznosti delovanja funkcij in nadzor.

Zbrana so ta polja:

  - **Activity.Group** – Oznaka, ki omogoča združevanje nabora dogodkov nadzora za upravljanje uspešnega delovanja.

  - **Activity.IsHVA** – Zastavica, ki označuje, da je dogodek ključen za zagotavljanje uspešnega delovanja za uporabnika.

  - **Data.AsyncOpen** – Zastavica, ki označuje, da je bil odprt dokument z vsebino, prejeto potem, ko je bilo glavno telo dokumenta že odprto.

  - **Data.BaseDownloadTriggered** – Diagnostika sledenja spremembam, vključno s podatki, da je bila zahtevana osnovna različica dokumenta.

  - **Data.BlockAutoUploadReasons** – Kode vzroka za blokirano stanje nalaganja (npr. samodejno shranjevanje je vklopljeno, dokument je v stanju prehoda).

  - **Data.BlockUploadDueToFailedSaveAsOverExisting** – Nalaganje je blokirano, saj bi bil vnovičen poskus neuspešen.

  - **Data.CacheFileId** – Povezava do telemetrije predpomnilnika Officeovih dokumentov za omogočanje analize posledic težav s predpomnilnikom na uporabniško izkušnjo.

  - **Data.ChartType** – Zastarelo.

  - **Data.CoauthStatus** – Poroča o stanju sodelovanja v dokumentu ob shranjevanju.

  - **Data.CoauthUpdatesContext** – Poroča o kontekstu (spajanje/postopno odpiranje).

  - **Data.CountOfMultiRoundTripsDownload** – Število vrnitev v strežnik, ki se uporablja za odpravljanje težav z učinkovitostjo delovanja in omrežjem.

  - **Data.CountOfMultiRoundTripsUpload** – Število vrnitev v strežnik, ki se uporablja za odpravljanje težav z učinkovitostjo delovanja in omrežjem.

  - **Data.DialogChoice** – Zabeleži izbrane možnosti v katerih koli pogovornih oknih napak.

  - **Data.DialogId** – Zabeleži ID pogovornega okna katerih koli pogovornih oknih napak, prikazanih med shranjevanjem.

  - **Data.Dmc.IsOcsSupported** – Zastarelo.

  - **Data.Doc.AccessMode** – Dokument je samo za branje.

  - **Data.Doc.AssistedReadingReasons** – To polje je nastavljeno, če je za dokument izbrana elektronska zaščita podatkov.

  - **Data.Doc.AsyncOpenKind – ** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

  - **Data.Doc.ChunkingType** – Enote, uporabljene za postopno odpiranje dokumenta.

  - **Data.Doc.EdpState** – Nastavitev elektronske zaščite podatkov dokumenta.

  - **Data.Doc.Ext** – Pripona dokumenta (docx/xlsm/pptx itd.).

  - **Data.Doc.Extension** – Zastarelo.

  - **Data.Doc.FileFormat** – Različica protokola za obliko zapisa dokumenta.

  - **Data.Doc.Fqdn** – Ime domene za OneDrive ali SharePoint Online.

  - **Data.Doc.FqdnHash** – Enostranska zgoščena vrednost imena domene, ki omogoča identifikacijo stranke.

  - **Data.Doc.FqdnHasi** – Zastarelo.

  - **Data.Doc.IdentityTelemetryId** – Enostranska zgoščena vrednost identitete uporabnika, uporabljena za shranjevanje.

  - **Data.Doc.IdentityUniqueId** – Zastarelo.

  - **Data.Doc.IKFlags** – Zastarelo.

  - **Data.Doc.InitializationScenario** – Zabeleži način odpiranja dokumenta.

  - **Data.Doc.IOFlags** – Poroča o predpomnjenih zastavicah, uporabljenih za nastavitev možnosti zahtev.

  - **Data.Doc.IrmRights** – Dejanja, ki jih je dovolil pravilnik za elektronsko zaščito podatkov, ki velja za dokument/uporabnika.

  - **Data.Doc.IsCloudCollabEnabled** – Zastavica, ki označuje, da aplikacija podpira sodelovanje v oblaku.

  - **Data.Doc.IsIncrementalOpen** – Zastavica, ki označuje postopno odpiranje dokumenta.

  - **Data.Doc.IsOcsSupported** – Zastavica, ki označuje, da dokument podpira sodelovanje v oblaku.

  - **Data.Doc.IsOpeningOfflineCopy** – Zastavica, ki označuje, da je bila odprta kopija dokumenta brez povezave.

  - **Data.Doc.IsSyncBacked** – Zastavica, ki označuje, da v računalniku obstaja samodejno sinhronizirana kopija dokumenta.

  - **Data.Doc.Location** – Označuje, v kateri storitvi je na voljo dokument (OneDrive, File Server, SharePoint itd.).

  - **Data.Doc.LocationDetails** – Označuje, v kateri znani mapi je na voljo lokalno shranjen dokument.

  - **Data.Doc.NumberCoAuthors** – Število uporabnikov v seji urejanja s sodelovanjem.

  - **Data.Doc.PasswordFlags** – Označuje nastavljeno zastavico za branje ali branje/pisanje gesla.

  - **Data.Doc.ReadOnlyReasons** – Razlogi, zakaj je bil dokument odprt v načinu »Samo za branje«.

  - **Data.Doc.ResourceIdHash** – Anonimni identifikator dokumenta za diagnosticiranje težav.

  - **Data.Doc.ServerDocId** – Nespremenljivi anonimni identifikator dokumenta za diagnosticiranje težav.

  - **Data.Doc.ServerProtocol** – Različica protokola za komunikacijo s storitvijo.

  - **Data.Doc.ServerType** – Vrsta strežnika, ki zagotavlja storitev (SharePoint, OneDrive, WOPI itd.).

  - **Data.Doc.ServerVersion** – Različica strežnika, ki zagotavlja storitev.

  - **Data.Doc.SessionId** – Prepozna določeno sejo za urejanje dokumenta v celotni seji.

  - **Data.Doc.SharePointServiceContext** – Diagnostične informacije SharePoint Onlineovih zahtev.

  - **Data.Doc.SizeInBytes** – Indikator velikosti dokumenta.

  - **Data.Doc.SpecialChars** – Indikator posebnih znakov v URL-ju ali poti dokumenta.

  - **Data.Doc.StorageProviderId** – Zastarelo.

  - **Data.Doc.StreamAvailability** – Indikator, ali je tok dokumenta na voljo/onemogočen.

  - **Data.Doc.SussionId** – Zastarelo.

  - **Data.Doc.SyncBackedType** – Indikator vrste dokumenta (lokalno ali storitev).

  - **Data.Doc.UrlHash** – Enostranska zgoščena vrednost za ustvarjanje naivnega identifikatorja dokumenta.

  - **Data.Doc.UsedWrsDataOnOpen** – Diagnostični indikator postopnega odpiranja dokumenta.

  - **Data.Doc.WopiServiceId** – Vsebuje enolični identifikator za ponudnika storitve WOPI.

  - **Data.DocnReadOnlyReasons** – Zastarelo.

  - **Data.DocumentSaveEndpoint** – Zastarelo; zamenjalo ga je polje »Data\_Doc\_Location«.

  - **Data.DocumentSaveType** – Vrsta shranjevanja (»Navadno«, »Ustvari«, »Shrani kot«).

  - **Data.DocumentSizeOnDisk** – Zastarelo; zamenjalo ga je polje »Data\_Doc\_SizeInBytes«.

  - **Data.DoesBaseHaveContentOnOpen** – Diagnostika sledenja spremembam za zagotavljanje najnovejše različice datoteke v skupni rabi.

  - **Data.DoesWorkingBranchHaveExcludedDataOnOpen** – Diagnostika sledenja spremembam za zagotavljanje najnovejše različice datoteke v skupni rabi.

  - **Data.DstDoc.AccessMode** – Nov dokument je samo za branje/ga je mogoče urejati.

  - **Data.DstDoc.EdpState** – Nastavitev elektronske zaščite podatkov novega dokumenta.

  - **Data.DstDoc.Extension** – Pripona novega dokumenta (docx/xlsm/pptx itd.).

  - **Data.DstDoc.FileFormat** – Protokol za obliko zapisa novega dokumenta.

  - **Data.DstDoc.Fqdn** – Ime domene za OneDrive ali SharePoint Online.

  - **Data.DstDoc.FqdnHash** – Enostranska zgoščena vrednost imena domene novega dokumenta, ki omogoča identifikacijo stranke.

  - **Data.DstDoc.IdentityUniqueId** – Zastarelo.

  - **Data.DstDoc.IOFlags** – Zastavice predpomnjenih možnosti novega dokumenta, uporabljene za odpiranje.

  - **Data.DstDoc.IsOpeningOfflineCopy** – Zastavica, ki označuje, da je bila odprta kopija novega dokumenta brez povezave.

  - **Data.DstDoc.IsSyncBacked** – Zastavica, ki označuje, da v računalniku obstaja samodejno sinhronizirana kopija dokumenta.

  - **Data.DstDoc.Location** – Označuje vrsto storitve, v kateri je na voljo nov dokument (OneDrive, File Server, SharePoint itd.).

  - **Data.DstDoc.NumberCoAuthors** – Število uporabnikov v seji urejanja s sodelovanjem v novem dokumentu.

  - **Data.DstDoc.ReadOnlyReasons** – Razlogi, zakaj je bil nov dokument odprt v načinu »Samo za branje«.

  - **Data.DstDoc.ResourceIdHash** – Anonimni identifikator dokumenta za diagnosticiranje težav novega dokumenta.

  - **Data.DstDoc.ResourceIdHash** – Anonimni identifikator dokumenta za diagnosticiranje težav novega dokumenta.

  - **Data.DstDoc.ServerProtocol** – Različica protokola za komunikacijo s storitvijo pri ustvarjanju novega dokumenta.

  - **Data.DstDoc.ServerType** – Vrsta strežnika, ki zagotavlja storitev (SharePoint, OneDrive, WOPI itd.) za novi dokument.

  - **Data.DstDoc.ServerVersion** – Različica strežnika, ki zagotavlja storitev za novi dokument.

  - **Data.DstDoc.SessionId** – Prepozna določeno sejo urejanja dokumenta v celotni seji za novi dokument.

  - **Data.DstDoc.SharePointServiceContext** – Diagnostične informacije SharePoint Onlineovih zahtev za novi dokument.

  - **Data.DstDoc.SizeInBytes** – Indikator velikosti novega dokumenta.

  - **Data.DstDoc.UrlHash** – Enostranska zgoščena vrednost za ustvarjanje naivnega identifikatorja dokumenta za novi dokument.

  - **Data.EditorsCount** – Število drugih sodelavcev, ki urejajo dokument.

  - **Data.FullIError** – Predpomnilnik vseh kod napak plasti protokola.

  - **Data.HasFilteredCategories** – Zastarelo.

  - **Data.HasFilteredCategoryNames** – Zastarelo.

  - **Data.HasFilteredSeries** – Zastarelo.

  - **Data.HasFilteredSeriesNames** – Zastarelo.

  - **Data.HasPendingSaveAs** Označuje izvajanje zahteve »Shrani kot/Shrani kopijo«.

  - **Data.Input.FileOpenState** – Stanje, ki ga zahteva aplikacija (branje/branje in pisanje itd.).

  - **Data.Input.FileSaveState** Stanje, ki ga zahteva aplikacija (»Shrani ob odpiranju«, »Shrani kot« itd.).

  - **Data.Input.NetworkCost** – Označuje strošek/vrsto omrežja (omejen prenos podatkov, omejeno nad zgornjo mejo itd.).

  - **Data.Input.OpenAsync** – Zastavica, ki označuje, da je aplikacija zahtevala asinhrono odpiranje.

  - **Data.Input.OpenAsync** – Zastavica, ki označuje, da je aplikacija zahtevala odpiranje brez povezave.

  - **Data.IsCachedHistoricalVersion** – Označuje, da to ni najnovejša različica predpomnjene datoteke.

  - **Data.IsHtml** – Označuje lepljenje besedila z obliko zapisa HTML.

  - **Data.IsLegacyCode** – Označuje lepljenje besedila z obliko zapisa podedovane kode.

  - **Data.IsLocalOnlyFile** – Označuje, da je bila datoteka odprta samo v lokalni shrambi.

  - **Data.IsLocalOrSyncBackedFile** – Označuje, da je bila datoteka odprta lokalno in preslikana v storitev.

  - **Data.IsMapUnMapCase** – Del stanja predpomnjene datoteke.

  - **Data.isOpenFromCollab** – Označuje, da je bila datoteka odprta v storitvi sodelovanja v skupni rabi.

  - **Data.IsStubFile** – Za dokument še bi bila omogočena skupna raba v storitvi v oblaku.

  - **Data.IsSyncBackedFile** – Dokument je v mapi, ki je posodobljena s samodejno sinhronizacijo.

  - **Data.IsSyncBackedStateDifferentThanOnLastOpen** – Stanje dokumenta je bilo spremenjeno; spremembe so bile morda izvedene, ko dokument ni bil odprt.

  - **Data.IsWorkingBranchAvailableOnOpen** – Diagnostika sledenja spremembam za zagotavljanje najnovejše različice datoteke v skupni rabi.

  - **Data.Location** – Označuje vrsto/lokacijo predstavnosti shrambe (USB, oblak itd.).

  - **Data.LockRequestDocMode** – Označuje, ali je dokument na voljo drugim osebam.

  - **Data.MruRequestResult** – Zastarelo.

  - **Data.NewDataNotAvailableReason** – Zastarelo.

  - **Data.OcsDisableReasons** – Ni uporabljeno za shranjevanje.

  - **Data.OcsHostOnOpen** – Ni uporabljeno za shranjevanje.

  - **Data.Output.FileSaveState** – Stanje ob dokončanju shranjevanja.

  - **Data.PivotChart** – Zastarelo.

  - **Data.resolveConflictState** – Kode vzroka za zahtevo za razrešitev sporov spajanja.

  - **Data.RTCEnabled** – Začetek izvajanja protokola za hitro distribucijo sprememb.

  - **Data.SaveAsToCurrent** – Označuje, da bo aktivni dokument prepisal shranjeno datoteko.

  - **Data.ServiceId** – Zastarelo; zamenjalo ga je polje »Data\_Doc\_WopiServiceId«.

  - **Data.SessionId** – Zastarelo.

  - **Data.SizeInBytes** – Zastarelo; zamenjalo ga je polje »Data\_Doc\_SizeInBytes«.

  - **Data.StopwatchDuration** – Zastarelo.

  - **Data.SyncBackedFileRequiresOnlineTransition** – Zastavica, ki označuje, da je spletni prehod začasno blokiral dejanje shranjevanja.

  - **Data.SyncBackedFileSaveOnOpen** – Zastavica, ki označuje, da spremembe, izvedene s samodejno sinhronizacijo, zahtevajo način shranjevanja ob odpiranju.

  - **Data.TelemetryId** – Zastarelo.

  - **Data.TriggerSaveAfterBaseDownload** – Diagnostika sledenja spremembam za zagotavljanje najnovejše različice datoteke v skupni rabi.

  - **Data.UploadBlockedDueToCoherencyFailure** – Shranjevanje v storitev je blokiralo uporabnikovo čakajoče reševanje sprememb v sporu.

  - **Data.UploadBlockedDueToFailedSaveAsOverExisting** – Shranjevanje v storitev je bila blokirana zaradi neuspešnega poskusa prepisovanja obstoječe datoteke.

  - **Data.UploadPreemptedForCoherency** – Shranjevanje v storitev je bilo prekinjeno zaradi večjega števila sprememb s strani uporabnika.

  - **Data.UploadPreemptedForSaveAsOverExistingFailure** – Shranjevanje v storitev je bilo prekinjeno zaradi predhodno neuspešno izvedene možnosti » SaveAsOverExisting«.

  - **Data.UploadScheduled** – Datoteko je pripravljena na asinhrono nalaganje v storitev.

  - **Data.UseClientIdAsSchemaLockId** – Zastavica za nadzor načina zaklepanja dokumentov v storitvi.

  - **Data.WorkingCopySaved** – Diagnostika sledenja spremembam za zagotavljanje najnovejše različice datoteke v skupni rabi.

  - **Data.ZrtSaveAsforSyncBackedBusinessEnabled** – Zastavica, ki označuje, da je hitro shranjevanje omogočeno za SharePoint Online.

  - **Data.ZrtSaveAsforSyncBackedConsumerEnabled** – Zastavica, ki označuje, da je hitro shranjevanje omogočeno za porabnika storitve OneDrive.

  - **Data.ZrtSaveAsforSyncBackedCTBusinessEnabled** – Zastavica, ki označuje, da je hitro shranjevanje vrst vsebine omogočeno za SharePoint Online.

  - **Data.ZrtSaveAsforSyncBackedCTConsumerEnabled** – Zastavica, ki označuje, da je hitro shranjevanje vrst vsebine omogočeno za porabnika storitve OneDrive.

  - **Data.ZrtSaveAsforSyncBackedBusinessMetaDataEnabled** – Zastavica, ki označuje, da je hitro shranjevanje metapodatkov datoteke omogočeno za SharePoint Online.

  - **Data.ZrtSaveAsforSyncBackedMetaDataConsumerEnabled** – Zastavica, ki označuje, da je hitro shranjevanje metapodatkov datoteke omogočeno za porabnika storitve OneDrive.

#### <a name="officefindtimeappfailedtostart"></a>Office.FindTime.AppFailedToStart

Podatki so zbrani, če aplikacije ni mogoče zagnati zaradi nepričakovane napake med zagonom. S tem dogodkom spremljamo izjeme in zrušitve. Omogoča lažje spremljanje ustreznosti stanja aplikacije in odpravljanje težav.

Zbrana so ta polja:
- **DateTime** – Časovni žig o času, ko je bil dogodek zabeležen.

- **EventName** – Ime zabeleženega dogodka.

#### <a name="officelivepersonacarduseractionsopenedpersonacard"></a>Office.LivePersonaCard.UserActions.OpenedPersonaCard

Prijavljen, ko uporabnik odpre Kartico osebe. Uporablja se za opazovanje kritičnih anomalij v stopnjah napake pri uvajanju kartice osebe Live Persona Card.

Zbrana so naslednja polja:

- **Data.appContextId** – naključno ustvarjen ID, ki se uporablja za prepoznavanje različnih računov v istem programu

- **Data.AppInfo.Name** – ime storitve v uporabi (kartica profila)

- **Data.cardCorrelationId** – globalni enolični identifikator za kartico osebe

- **Data.cardPersonaCorrelationId** – globalni enolični identifikator za določeno osebo, ki je prikazan na kartici

- **Data.clientCorrelationId** – globalni enolični identifikator za sejo aplikacije

- **Data.clientType** – vrsto naprave, v kateri se izvaja aplikacija.

- **Data.eventId** – identifikator imena dogodka, npr. »LivePersonaCardRenderedAction«

- **Data.exportName**– človeško berljivo ime dogodka dejanja uporabnika, npr. »OpenedPersonaCard«

- **Data.exportType** – Kategorija dogodka za izvoz zahteve uredbe GDPR

- **Data.feature** – uporablja se za združevanje različnih dogodkov z enakimi lastnostmi (kartica profila)

- **Data.hostAppRing** – krog, s katerim je bila aplikacija distribuirana

- **Data.OTelJS.Version**– različica programa OTel Logger

- **Data.region** – geografsko območje zaledne storitve Kartica profila stika, s katerim je povezan uporabnik

- **Data.tenantAadObjectId** – najemnik, na katerega je vezana naročnina uporabnika. Omogoča, da razvrstimo težave in določimo, ali je težava razširjena ali omejena na določen nabor uporabnikov oz. določenega najemnika

- **Data.type** – vrsta zabeleženega dogodka, npr. Sledenje, Napaka, Dogodek

- **Data.userAadObjectId** – globalni enolični identifikator uporabnika za Microsoftov račun za podjetja (dvojnik Data.UserInfo.Id)

- **Data.UserInfo.Id** – globalni enolični identifikator uporabnika za Microsoftov račun za podjetja 

- **Data.UserInfo.Id** – globalni enolični identifikator uporabnika za Microsoftov potrošniški račun

- **Data.UserInfo.OMSTenantId** – najemnik, s katerim je povezana uporabnikova naročnina. Omogoča, da razvrstimo težave in določimo, ali je težava razširjena ali omejena na določen nabor uporabnikov oz. določenega najemnika

- **Data.userPuid** – globalni enolični identifikator uporabnika za Microsoftov potrošniški račun (dvojnik Data.UserInfo.Msald)

- **Data.version** – različica storitve (kartica profila)

- **Data.viewType** – določa vrsto prikazane kartice profila

- **NetworkCost** – Označuje strošek/vrsto omrežja (omejen prenos podatkov, omejeno nad zgornjo mejo itd.)

- **NetworkCountry** – koda države pošiljatelja, ki temelji na neočiščenem naslovu IP odjemalca.

- **Data.properties** – dodatni metapodatki, ki so zbrani za vsak dogodek, kot je prikazano v tem primeru.

    - **bandwidthEstimateMbps** – učinkovita ocena pasovne širine v Mb/s

    - **cardCorrelationId** – Dvojnik Data.appContextId zgoraj 

    - **cardPersonaCorrelationId**  – Dvojnik Data.cardCorrelationId zgoraj

    - **consumerCorrelationId**  – Dvojnik Data.clientCorrelationId zgoraj 

    - **externalAppSessionCorrelationId**  – globalni enolični identifikator za aplikacijo za prepoznavanje vseh kartic osebe, odprtih v istem podsrečanju

    - **immersiveProfileCorrelationId** – globalni enolični identifikator za razširjeno sejo pogleda profila

    - **networkEffectiveType** – učinkovita vrsta omrežne povezave, npr. »slow-2g online«, ki določi, ali je uporabnik povezan z internetom v času, ko prikazuje kartico osebe

    - **networkType** – vrsta omrežne povezljivosti naprave, ki je v uporabi

    - **personaCorrelationId** – globalni enolični identifikator enolične osebe v seji

    - **roundTripEstimateMs** – ocenjeno učinkovita povratna povezava trenutne povezave v milisekundah

    - **wasOpenedAsCompactCard** – uporablja se za identifikacijo, ali je bila kartica prvotno odprta kot strnjeni pogled


#### <a name="officemanageabilityclient-fetchpolicyprechecks"></a>Office.Manageability.Client Fetch.PolicyPreChecks

Nujna telemetrija za spremljanje neuspešnega\\uspešnega preverjanja veljavnosti vnaprejšnjega preverjanja pridobivanja pravilnika v oblaku. »ExitReason« vsebuje zemljevid popisovalnika vnaprej preverjenega stanja, ki ni bilo uspešno.

Zbrana so ta polja:

  - **Data.ExitReason** – Vrednost popisovalnika z navedbo razloga za izhod, če je bilo vnaprejšnje preverjanje neuspešno.

  - **Data.Log** – Sporočilo dnevnika po meri, ki označuje, ali je bilo vnaprejšnje preverjanje uspešno oz. neuspešno izvedeno.

#### <a name="officemanageabilityclientfetchandapplypolicy"></a>Office.Manageability.Client.Fetch.AndApplyPolicy

Nujna telemetrija za spremljanje neuspešne\\uspešne inicializacije pridobivanja pravilnika v oblaku v aplikaciji. »Exit Reason« vsebuje zemljevid popisovalnika razloga za napako.

Zbrana so ta polja:

  - **Data.ExitReason** – Vrednost popisovalnika z navedbo razloga za izhod, če je bilo vnaprejšnje preverjanje neuspešno.

  - **Data.Log** – Sporočilo dnevnika po meri, ki označuje, ali je bilo vnaprejšnje preverjanje uspešno oz. neuspešno izvedeno.


#### <a name="officeonenotenavigationcreatepage"></a>Office.OneNote.Navigation.CreatePage

Kritični signal, uporabljen za spremljanje možnosti uporabnikov OneNota za ustvarjanje strani v OneNotu.  Telemetrija, uporabljena za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in ustreznosti stanja storitve. Če uporabniki ne morejo ustvariti strani, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so naslednja polja:

- **IsAtSectionEnd** – označuje, ali je na koncu odseka ustvarjena nova stran ali ne.

- **IsBlank** – označuje, ali je nova stran prazna ali pa je ustvarjena na podlagi predloge.

- **IsRecentsView** – označuje, ali je stran ustvarjena na podlagi nedavnih elementov ali ne.

- **NavView** – označuje, ali je stran ustvarjena na podlagi pogleda krmarjenja ali ne.

- **NoteType** – označuje vrsto strani (hitra beležka, seznam ali fotografija).

- **QuickNoteType** – označuje vrsto strani (hitra beležka, seznam ali fotografija).

- **RailState** – označuje stanje sledi krmarjenja OneNota pri ustvarjanju strani.

- **Trigger** – označuje vhodno točko, na kateri se začne dejanje ustvarjanja strani.

- **TriggerInfo** – označuje dodatne informacije, povezane s sprožilcem.


#### <a name="officeonenotenavigationcreatesection"></a>Office.OneNote.Navigation.CreateSection

Kritični signal, ki se uporablja za spremljanje možnosti uporabnikov OneNota za ustvarjanje odsekov v OneNotu.  Telemetrija, uporabljena za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in ustreznosti stanja storitve. Če uporabniki ne morejo ustvariti strani, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so naslednja polja

- **NotebookID** – enolični identifikator zvezka.

- **SectionID** – enolični identifikator ustvarjenega odseka.

- **Sprožilec** – označuje vstopno točko, na kateri se začne dejanje ustvarjanja odseka.

- **TriggerInfo** – označuje dodatne informacije, povezane s sprožilcem.


#### <a name="officeonenotenavigationnavigate"></a>Office.OneNote.Navigation.Navigate

Kritični signal, ki se uporablja za spremljanje možnosti uporabnikov OneNota za krmarjenje med stranmi v OneNotu.  Telemetrija, uporabljena za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in ustreznosti stanja storitve. Če uporabniki ne morejo krmariti, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so naslednja polja:

- **FromNotebook** – enolični identifikator zvezka.

- **FromPage** – enolični identifikator strani.

- **FromSection** – enolični identifikator odseka.

- **FromSectionGroup** – enolični identifikator skupine odsekov.

- **IsCurrentUserEduStudent** – označuje, ali ima trenutni uporabnik vlogo študenta v izobraževalnem zvezku ali ne.

- **IsEduNotebook** – označuje, ali je trenutna stran izobraževalni zvezek ali ne.

- **IsEduNotebookReadOnlyPage** – označuje, ali je trenutna stran na voljo »samo za branje« v izobraževalnem zvezku ali ne.

- **ToNotebook** – enolični identifikator zvezka.

- **ToPage** – enolični identifikator strani.

- **ToSection** – enolični identifikator odseka.

- **ToSectionGroup** – enolični identifikator skupine odsekov.


#### <a name="officeonenotenotebookmanagementcreatenotebook"></a>Office.OneNote.NotebookManagement.CreateNotebook

Kritični signal, ki se uporablja za spremljanje možnosti uporabnikov OneNota za ustvarjanje zvezkov v OneNotu.  Telemetrija, uporabljena za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in ustreznosti stanja storitve. Če uporabniki ne morejo ustvariti zvezkov, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so naslednja polja:
    
- **NotebookID** – enolični identifikator zvezka.


#### <a name="officeonenotenotebookmanagementopennotebook"></a>Office.OneNote.NotebookManagement.OpenNotebook

Kritični signal, ki se uporablja za spremljanje možnosti uporabnikov OneNota za odpiranje zvezkov v OneNotu.  Telemetrija, uporabljena za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in ustreznosti stanja storitve. Če uporabniki ne morejo odpreti zvezkov, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so naslednja polja:

-  **NotebookID** – enolični identifikator zvezka.

    
#### <a name="officeonenotesearchsearch"></a>Office.OneNote.Search.Search

ID kritičnega signala, uporabljan za spremljanje možnosti OneNotovih uporabnikov za iskanje informacij na več tisoč straneh in v več tisoč zvezkih.   Telemetrija, uporabljena za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in ustreznosti stanja storitve. Če uporabniki ne morejo najti informacij v zvezkih, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so naslednja polja:

- **PageSearchResultCount** – označuje število rezultatov iskanja, ki so najdeni v načinu iskanja strani.

-  **PageTimeToFirstResultInMs** – označuje količino časa, ki jo OneNote porabi za iskanje prvega ujemanja v načinu iskanja strani.
    
-  **PageTimeToLastResultInMs** – označuje količino časa, ki jo OneNote porabi za iskanje zadnjega ujemanja v načinu iskanja strani.

-  **PageTimeToMedianResultInMs** – označuje mediano časa, ki ga OneNote porabi za iskanje vseh ujemanj v načinu iskanja strani.

-  **SearchResultCount** – označuje število najdenih rezultatov iskanja.

-  **TagSearchResultCount** – označuje število rezultatov iskanja, najdenih v načinu iskanja oznak.

-  **TagTimeToFirstResultInMs** – označuje količino časa, ki jo OneNote porabi za iskanje prvega ujemanja v načinu iskanja oznak.

-  **TagTimeToLastResultInMs** – označuje količino časa, ki jo OneNote porabi za iskanje zadnjega ujemanja v načinu iskanja oznak.

-  **TagTimeToMedianResultInMs** – označuje mediano časa, ki ga OneNote porabi za iskanje vseh ujemanj v načinu iskanja oznak.

-  **TimeToFirstResultInMs** – označuje količino časa, ki jo OneNote porabi za iskanje prvega ujemanja.

-  **TimeToLastResultInMs** – označuje količino časa, ki jo OneNote porabi za iskanje zadnjega ujemanja.

-  **TimeToMedianResultInMs** – označuje mediano časa, ki ga OneNote porabi za iskanje vseh ujemanj.


#### <a name="officeonenotestickynotesnotecreated"></a>Office.OneNote.StickyNotes.NoteCreated

To je kritični signal, ki se uporablja za nadzor zmogljivosti Lepljivih zapiskov za ustvarjanje zapiskov v aplikaciji.  Telemetrija se uporablja za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in stanja storitve. Če uporabniki ne morejo ustvariti zapiska, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so naslednja polja:

- **NoteLocalId** – razpoznavni enolični identifikator, ki je dodeljen zapisku v času, ko uporabnik ustvari zapiski v programu.

- **IsExportable** – zastavica, ki označuje, ali je bil dogodek rezultat dejanja uporabnika ali ne. Mora biti nastavljen na vrednost true, ker je NoteCreated dejanje, ki ga je sprožil uporabnik.

- **StickyNotes – SDKVersion** – številka različice, ki označuje različico Lepljivih zapiskov, ki jo uporablja uporabnik. Omogoča, da določimo, v katerih različicah izdelka je prišlo do težave ter te težave razvrstimo po pomembnosti.


#### <a name="officeonenotestickynotesnoteviewed"></a>Office.OneNote.StickyNotes.NoteViewed

To je kritični signal, ki se uporablja za nadzor zmogljivosti Lepljivih zapiskov za ustvarjanje zapiskov v aplikaciji.  Telemetrija se uporablja za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in stanja storitve. Če uporabniki ne morejo ustvariti zapiska, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so naslednja polja:

- **HasImages** – zastavica, ki označuje, so v ogledanem zapisku shranjene slike.

- **IsExportable** – zastavica, ki označuje, ali je bil dogodek rezultat dejanja uporabnika ali ne. Mora biti nastavljen na vrednost true, ker je NoteViewed dejanje, ki ga je sprožil uporabnik.

- **NoteLocalId** – razpoznavni enolični identifikator, ki je dodeljen zapisku v času, ko uporabnik ustvari zapisek v programu.

- **StickyNotes – SDKVersion** – številka različice, ki označuje različico Lepljivih zapiskov, ki jo uporablja uporabnik. Omogoča, da določimo, v katerih različicah izdelka je prišlo do težave ter te težave razvrstimo po pomembnosti.


#### <a name="officeonenotestoragenotebooksyncresult"></a>Office.OneNote.Storage.NotebookSyncResult
 
Ta dogodek zabeleži rezultat sinhronizacije zvezka. Uporablja se za prikaz števila enoličnih ciljev sinhronizacije pri izračunavanju rezultata sinhronizacije za OneNote.
 
Zbrana so naslednja polja

- **CachedError_Code** – oštevilčena ali alfanumerična koda, ki se uporablja za določanje narave predpomnjene napake, in/ali razloga, zakaj se je pojavila.
    
- **CachedError_Description** – opis predpomnjene napake.

- **CachedError_Tag** – označuje, kje v kodi je shranjena predpomnjena napaka.

- **CachedError_Type** – vrsta predpomnjene napake, na primer »Win32Error« itd.

- **ExecutionTime** – čas v milisekundah, porabljen za podvojitev zvezka.

- **Gosid** – globalni ID prostora za predmete.

- **IdentityType** – vrsta identitete, npr. Windows Live, ID organizacije itd.

- **InitialReplicationInSession** – označuje, ali je ta podvojitev prva podvojitev zvezka po odprtju ali ne.

- **IsBackgroundSync** – označuje, ali je to sinhroniziranje ozadja ali ne.

- **IsCachedErrorSuppressed** – označuje, ali je predpomnjena napaka onemogočena ali ne.

- **IsCachedErrorUnexpected** – označuje, ali je predpomnjena napaka nepričakovana ali ne.

- **IsNotebookErrorSuppressed** – označuje, ali je napaka sinhronizacije na ravni zvezka onemogočena ali ne.

- **IsNotebookErrorUnexpected** – označuje, ali je napaka sinhronizacije na ravni zvezka nepričakovana ali ne.

- **IsSectionErrorSuppressed** – označuje, ali je napaka sinhronizacije odseka onemogočena ali ne.

- **IsSectionErrorUnexpected** – označuje, ali je napaka sinhronizacije odseka nepričakovana ali ne.

- **IsUsingRealtimeSync** – označuje, ali je sinhronizacija zvezka z moderno vsebino strani izvedena ali ne.

- **LastAttemptedSync** – časovni žig, ko je bil nazadnje izveden poskus sinhronizacije zvezka.

- **LastBackgroundSync** – časovni žig, ko je bil izveden zadnji poskus sinhronizacije v ozadju.

- **LastNotebookViewedDate** – datum, ko je bil zvezek nazadnje gledan.

- **LastSuccessfulSync** – časovni žig, ko je bil zvezek uspešno predhodno sinhroniziran.

- **NeedToRestartBecauseOfInconsistencies** – označuje, ali je potreben ponovni zagon sinhronizacije zaradi nedoslednosti ali ne.

- **NotebookErrorCode** – koda napake sinhronizacije na ravni zvezka, ki je shranjena v prostoru zvezka »Graph«.

- **NotebookId** – ID zvezka.

- **NotebookType** – vrsta zvezka.

- **ReplicatingAgainBecauseOfInconsistencies** – označuje, ali se ponovni zagon sinhronizacije izvede zaradi nedoslednosti ali ne.

- **SectionError_Code** – oštevilčena ali alfanumerična koda, ki se uporablja za določanje narave napake sinhronizacije odseka in/ali razloga, zakaj se je pojavila.

- **SectionError_Description** – opis napake sinhronizacije odseka.

- **SectionError_Tag** – določite mesto v kodi, kjer je vrnjena napaka sinhronizacije odseka.

- **SectionError_Type** – vrsta napake sinhronizacije odseka, npr. »Win32Error« itd.

- **Success** – označuje, ali je sinhronizacija zvezka uspešna ali ne.

- **SyncDestinationType** – vrsta cilja sinhronizacije, tj. OneDrive ali SharePoint Online.

- **SyncId** – številka, ki je enolična za vsako sinhronizacijo zvezka.

- **SyncWasFirstInSession** – označuje, ali je ta sinhronizacija prva sinhronizacija v trenutni seji.

- **SyncWasUserInitiated** – označuje, ali je to sinhronizacijo inicializiral uporabnik ali ne.

- **TenantId** – ID najemnika za SharePoint.

- **TimeSinceLastAttemptedSync** – čas od zadnjega poskusa sinhronizacije zvezka.

- **TimeSinceLastSuccessfulSync** – čas od zadnje uspešne sinhronizacije zvezka.


#### <a name="officeonenotesystemapplifecycleapplaunch"></a>Office.OneNote.System.AppLifeCycle.AppLaunch

Kritični signal, ki se uporablja, da uporabnikom storitve OneNote zagotovi uspešen zagon aplikacije. Telemetrija se uporablja za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in ustreznosti stanja storitve. Če uporabniki ne morejo zagnati aplikacije v našem oknu učinkovitosti delovanja, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so naslednja polja:     Brez

#### <a name="officeoutlookdesktopaccountconfigurationcreateaccountresult"></a>Office.Outlook.Desktop.AccountConfiguration.CreateAccountResult

Rezultati dodajanja računa v nov profil v Outlooku iz pogleda »Office Backstage« ali pogovornega okna z nastavitvami računa. Podatke aktivno spremljamo, da zaznamo morebitne konice napak. Z analiziranjem teh podatkov odkrijemo tudi področja, ki jih moramo izboljšati. Z vsako izdajo se trudimo izboljšati to raven uspešnosti.

Zbrana so ta polja:

  - **AccountCreationResult** – Rezultati (uspešno, neuspešno, preklic itd.) dodajanja računa v Outlook.

  - **AccountCreationTime** – Čas trajanja ustvarjanja računa.

  - **AccountInfoSource** – Vir nastavitev računa (npr. samodejno odkrivanje, GuessSmart, samodejno zaznavanje itd.).

  - **AccountType** – Vrsta konfiguriranega računa.

  - **HashedEmailAddress** – Zgoščeni e-poštni naslov.

  - **ShowPasswordPageFlightEnabled** – Indikator, ali je omogočena pilotna različica za »ShowPopImapPasswordPage«.

#### <a name="officeoutlookdesktopaccountconfigurationrepairaccountresult"></a>Office.Outlook.Desktop.AccountConfiguration.RepairAccountResult

Rezultati popravila računa ali spreminjanja dodatnih nastavitev računa. Podatke aktivno spremljamo, da zaznamo morebitne konice napak. Z analiziranjem teh podatkov odkrijemo tudi področja, ki jih moramo izboljšati. Ker so to nove (refaktorirane) izkušnje, stremimo k popolni učinkovitosti delovanja.

Zbrana so ta polja:

  - **AccountInfoSource** – Vir informacij o računu, s katerim izvajamo popravila.

  - **AccountType** – Vrsta računa, ki smo ga poskušali popraviti.

  - **HashedEmailAddress** – Zgoščeni e-poštni naslov.

  - **ManualRepairRequested** – Indikator, ali je bilo zahtevano ročno popravilo.

  - **Result** – Rezultat poskusa popravila računa. Na primer: »Success« ali »Fail\_SaveChangesToAccount«.

#### <a name="officeoutlookdesktopaccountconfigurationupdatepasswordresult"></a>Office.Outlook.Desktop.AccountConfiguration.UpdatePasswordResult

Rezultat posodobitve gesla računa v spustnem meniju »Nastavitve računa«. Podatke aktivno spremljamo, da zaznamo morebitne konice napak. Z analiziranjem teh podatkov odkrijemo tudi področja, ki jih moramo izboljšati. Ker so to nove (refaktorirane) izkušnje, stremimo k popolni učinkovitosti delovanja.

Zbrana so ta polja:

  - **AccountType** – Vrsta računa, za katerega smo poskušali posodobiti geslo.

  - **HashedEmailAddress** – Zgoščeni e-poštni naslov.

  - **Result** – Rezultat poskusa posodobitve gesla. Na primer: »Success« ali »Fail\_AllowLessSecureAppsDisabled«.


#### <a name="officeoutlookdesktopstorescreatenewstore"></a>Office.Outlook.Desktop.Stores.CreateNewStore

Zbira rezultate ustvarjanja nove shrambe (z vrsto in različico) ter rezultate kod. Z aktivnim spremljanjem tega dogodka nadziramo ustreznost uporabnikove zmogljivosti sinhroniziranja in lokalnega shranjevanja pošte, arhiviranja e-poštnih sporočil (v PST-ju) ali uporabe Skupin.

Zbrana so ta polja:

  - **Standard HVA Activity** s koristno vsebino po meri.

  - **StoreType** – Vrsta ustvarjene shrambe (OST/PST/NST).

  - **StoreVersion** – Različica ustvarjene shrambe (majhna/velika/Tardis).

#### <a name="officeoutlookmacaccountaddworkflow"></a>Office.Outlook.Mac.AccountAddWorkflow

Rezultat dodajanja računa v Outlook. Podatke spremljamo, da zagotovimo, da ne pride do morebitnih konic napak. Z analiziranjem teh podatkov odkrijemo tudi področja, ki jih moramo izboljšati. Z vsako izdajo se trudimo izboljšati to raven uspešnosti. 

Zbrana so naslednja polja:

- **AccountConfigMethod** – način konfiguracije računa.

- **AccountType** – vrsta konfiguriranega računa.

- **AccountWorkflowSession** – seja, v kateri je izveden poskus poteka dela računa.

- **SessionDuration** – trajanje seje. 

- **ThreadId** – identifikator niti.


#### <a name="officeoutlookmacaccountonboardingflow"></a>Office.Outlook.Mac.AccountOnboardingFlow

Rezultat dodajanja računa v Outlook z uporabo nove izkušnje konfiguracije računa. Podatke spremljamo, da zagotovimo, da ne pride do morebitnih konic napak. Z analiziranjem teh podatkov odkrijemo tudi področja, ki jih moramo izboljšati. Z vsako izdajo se trudimo izboljšati to raven uspešnosti. 

Zbrana so naslednja polja:

- **AccountConfigAutoSignIn** – samodejna konfiguracija računa, ki jo nastavi skrbnik.

- **AccountConfigDomain** – domena, določena med konfiguracijo računa. 

- **AccountConfigEntryPoint** – vstopna točka, na kateri je uporabnik vnesel konfiguracijo računa. 

- **AccountConfigErrorCode** – koda napake, do katere pride med konfiguracijo računa. 

- **AccountConfigErrorCode** – napaka, do katere pride med konfiguracijo računa.

- **AccountConfigMethod** – način konfiguracije računa

- **AccountConfigPhase** – trenutni korak poteka dela konfiguracije računa.

- **AccountConfigPhaseFrom** – začetni korak poteka dela konfiguracije računa. 

- **AccountConfigPhase** – zadnji korak poteka dela konfiguracije računa. 

- **AccountType** – vrsta računa, ki je konfiguriran.

- **AccountWorkflowSession** – seja, v kateri je izveden poskus poteka dela računa.

- **SessionDuration** – trajanje seje.


#### <a name="officeoutlookmacdeleteaccountusage"></a>Office.Outlook.Mac.DeleteAccountUsage

Rezultat brisanja računa v Outlooku. Podatke spremljamo, da zagotovimo, da ne pride do morebitnih konic napak. Z analiziranjem teh podatkov odkrijemo tudi področja, ki jih moramo izboljšati. Z vsako izdajo se trudimo izboljšati to raven uspešnosti. 

Zbrana so naslednja polja:

- **AccountType** – vrsta računa, ki je konfiguriran.

- **AccountID** – identifikator računa.

- **DeprovisionAccount** – označuje, ali je račun odstranjen iz strežnika.

- **IsFastDelete** – označuje, ali je račun izbrisan v niti ozadja.

#### <a name="officepowerpointdocoperationclose"></a>Office.PowerPoint.DocOperation.Close

Podatki so zbrani ob zapiranju PowerPointovih predstavitev. Ta dogodek vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav pri postopku zapiranja, ki vključuje shranjevanje in sinhroniziranje uporabnikovih podatkov. Microsoft uporablja te podatke za zagotavljanje ustreznega delovanje postopka zapiranja in uspešnega shranjevanja uporabnikove vsebine.

Zbrana so ta polja:

  - **Data\_AddDocTelemetryResult:long** – Ali ima ta dolgi vnos vso zahtevano telemetrijo dokumenta (polja »Data\_Doc\_\*«)? Če je nima, zakaj?

  - **Data\_AutoSaveDisabledReasons:string** – Nabor vnaprej določenih vrednosti, zakaj je bilo samodejno shranjevanje onemogočeno v tem dokumentu. (Napaka spajanja, napaka shranjevanja, pravilnik skupine itd.).

  - **Data\_CloseReason:long** – Kako je bil izveden postopek zapiranja? Ali ste zaprli dokument? Ali ste zaprli aplikacijo?

  - **Data\_CppUncaughtExceptionCount:long** – Število neobravnavanih izjem.

  - **Data\_DetachedDuration:long** – Čas odpete dejavnosti/neizvajanja dejavnosti.

  - **Data\_Doc\_AccessMode:long** – Način odpiranja dokumenta (samo za branje/branje in pisanje).

  - **Data\_Doc\_AssistedReadingReasons:long** – Nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

  - **Data_Doc_AsyncOpenKind:long – ** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

  - **Data\_Doc\_ChunkingType:long** – Način shranjevanja dokumenta v SharePointu.

  - **Data\_Doc\_EdpState:long** – Stanje zaščite podatkov podjetja za dokument.

  - **Data\_Doc\_Ext:string** – Pripona dokumenta.

  - **Data\_Doc\_Extenstion:string** – Pripona dokumenta.

  - **Data\_Doc\_FileFormat:long** – Nabor vnaprej določenih vrednosti za obliko zapisa datoteke (bolj podrobno kot za pripono).

  - **Data\_Doc\_Fqdn:string** – Mesto, kjer je dokument shranjen (SharePoint.com, live.net); na voljo samo za domene v storitvi Office 365.

  - **Data\_Doc\_FqdnHash:string** – Zgoščena vrednost mesta shrambe dokumenta.

  - **Data\_Doc\_IdentityTelemetryId:string** – Enolični GUID uporabnika.

  - **Data\_Doc\_IdentityUniqueId:string** – Enolični identifikator identitete, ki je bila uporabljena za dokumente v skupni rabi.

  - **Data\_Doc\_IOFlags:long** – Bitna maska za različne zastavice danega dokumenta, povezane z V/I.

  - **Data\_Doc\_IrmRights:long** – Nabor vnaprej določenih vrednosti za vrsto upravljanja pravic do informacij, ki velja za ta dokument (»Forward«, »Reply«, »SecureReader«, »Edit« itd.).

  - **Data\_Doc\_IsCloudCollabEnabled:bool** – Ima vrednost »true«, če je bila že prejeta glava HTTP »IsCloudCollabEnabled«, ki njo je poslala zahteva OPTIONS.

  - **Data\_Doc\_IsIncrementalOpen:bool** – Ali je bil dokument odprt postopoma (nova funkcija, ki odpre dokument tako, da ne prenese celoten dokument).

  - **Data\_Doc\_IsOcsSupported:bool** – Ali dokument podpira soavtorstvo z novo storitvijo OCS.

  - **Data\_Doc\_IsOpeningOfflineCopy:bool** – Preverja, ali je bil dokument odprt v lokalnem predpomnilniku.

  - **Data\_Doc\_IsSyncBacked:bool** – Preverja, ali je bil dokument odprt v mapi, za katero je uporabljena aplikacija za povratno sinhronizacijo v storitvi OneDrive.

  - **Data\_Doc\_Location:long** – Nabor vnaprej določenih vrednosti za mesto shranjevanja dokumenta (lokalno, SharePoint, WOPI, omrežje itd.).

  - **Data\_Doc\_LocationDetails:long** – Nabor vnaprej določenih vrednosti podrobnejše lokacije (mapa »Začasno«, mapa »Prenosi«, dokumenti storitve OneDrive, slike storitve OneDrive itd.).

  - **Data\_Doc\_NumberCoAuthors:long** –Število soavtorjev, ko je bil dokument odprt.

  - **Data\_Doc\_PasswordFlags:long** – Nabor vnaprej določenih vrednosti za način šifriranja dokumenta z geslom (brez, geslo za branje, geslo za urejanje).

  - **Data\_Doc\_ReadOnlyReasons:long** – Nabor vnaprej določenih vrednosti, zakaj je bil ta dokument označen samo za branje (zaklenjeno v strežniku, dokončni dokument, zaščiteno z geslom za urejanje itd.).

  - **Data\_Doc\_ResourceIdHash:string** – Zgoščena vrednost identifikatorja vira za dokumente, shranjene v oblaku.

  - **Data_Doc_RtcType – **  označuje, kako je bil kanal v realnem času (RTC) nastavljen za trenutno datoteko (onemogočeno, nepodprto, na zahtevo, vedno vklopljeno itn.).

  - **Data\_Doc\_ServerDocId:string –** nespremenljivi identifikator za dokumente, shranjene v oblaku

  - **Data\_Doc\_ServerProtocol:long** – Nabor vnaprej določenih vrednosti, ki jih protokol uporablja za komunikacijo s strežnikom (Http, Cobalt, WOPI itd.).

  - **Data\_Doc\_ServerType:long** – Nabor vnaprej določenih vrednosti za vrsto strežnika (SharePoint, DropBox, WOPI).

  - **Data\_Doc\_ServerVersion:long** – Preverja, ali strežnik temelji na sistemu Office14, Office15 ali Office 16.

  - **Data\_Doc\_SessionId:long** – Ustvarjeni GUID, ki prepozna primerek dokumenta v seji istega procesa.

  - **Data\_Doc\_SharePointServiceContext:string** – Neprosojen niz, običajno »GridManagerID.FarmID«. Uporabni podatki za korelacijo odjemalskega in strežniškega dnevnika.

  - **Data\_Doc\_SizeInBytes:long** – Velikost dokumenta v bajtih.

  - **Data\_Doc\_SpecialChars:long** – Bitna maska, ki označuje posebne znake v URL-ju ali poti dokumenta.

  - **Data\_Doc\_StorageProviderId:string** – Niz, ki prepozna ponudnika za shranjevanje dokumentov, npr. »DropBox«.

  - **Data\_Doc\_StreamAvailability:long** – Nabor vnaprej določenih vrednosti za stanje dokumenta Stream (na voljo, stalno onemogočeno, ni na voljo).

  - **Data\_Doc\_UrlHash:string** – Zgoščena vrednost polnega URL-ja za dokumente, shranjene v oblaku.

  - **Data\_Doc\_UsedWrsDataOnOpen:bool** – Ima vrednost »true«, če je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS na strani gostitelja.

  - **Data\_Doc\_WopiServiceId:string** – Identifikator storitve WOPI, npr. »Dropbox«.

  - **Data\_DocHasStorage:bool** – Ali ima ta dokument lokalno shrambo?

  - **Data\_fLifeguarded:bool** – Ali je bil dokument kdaj zavarovan (funkcija za samodejno odpravljanje težav z dokumenti brez pozivanja uporabnika)?

  - **Data\_IsDocAutoSaveable:bool** – Ali je predstavitev mogoče samodejno shraniti?

  - **Data\_IsDocDirty:bool** – Ali predstavitev vključuje spremembe, ki še niso shranjene?

  - **Data\_IsNewDoc:bool** – Ali je dokument nov oz. obstoječ?

  - **Data\_IsRecoveredDoc:bool** – Ali je bil dokument obnovljen? (Če se je prejšnja seja zrušila, je podokno za obnovitev dokumenta prikazano v naslednji seji).

  - **Data\_NewDocDiscarded:bool** – Ali je bila nova predstavitev zavržena brez shranjevanja?

  - **Data\_OCSClosingDlgCanceled:bool** – Če je v strežniku OCS čakajoče nalaganje in uporabnik zapre dokument, je uporabniku prikazano pogovorno okno s sporočilom, naj počaka. Katero možnost naj uporabnik izbere?

  - **Data\_OCSClosingDlgExpired:bool** – Ali je pogovorno okno samodejno poteklo (po 1 minuti)?

  - **Data\_OCSClosingStatus:long** – Kakšno je končno stanje strežnika OCS (»In CSI«, »Closable«, »In OCS Transition«, »In CSI transition« itd.).

  - **Data\_OCSClosingWaitDurationMS:long** – Koliko časa je moral uporabnik čakati, da se je strežnik OCS naložil.

  - **Data\_OCSHandleTransitionResult:long** – Vnaprej določen nabor vrednosti rezultatov prehoda, izvedenega med zapiranjem (poskus je bil že izveden, nadaljuj zapiranje itd.).

  - **Data\_ServerDocId:string** – GUID za enolično identifikacijo dokumenta.

  - **Data\_StopwatchDuration:long** – Skupni čas dejavnosti.

  - **Data\_UserContinuedZRTClose:bool** – Ali je uporabnik izbral možnost »Nadaljuj« zapiranje, ko je bilo ob zapiranju dokumenta prikazano pogovorno okno?

#### <a name="officepowerpointdocoperationnewdocument"></a>Office.PowerPoint.DocOperation.NewDocument

Dogodek je zbran, ko PowerPoint ustvari novo predstavitev. Vključuje metrike uspešnosti, neuspešnosti in učinkovitosti delovanja.

Te informacije uporabljamo za zagotavljanje uspešnega ustvarjanja datotek brez kakršnega koli zmanjšanja učinkovitosti delovanja.

Zbrana so ta polja:

  - **NewDocumentType** – Ali je nov dokument ustvarjen iz predloge oz. povsem na novo?

  - **FLifeguarded** – Ali je življenjski cikel dokumenta zaščiten (funkcija, ki obnovi stanje poškodovanega dokumenta brez pozivanja uporabnika)?

#### <a name="officepowerpointdocoperationopencompleteprotocol"></a>Office.PowerPoint.DocOperation.OpenCompleteProtocol

Podatki so zbrani ob odpiranju PowerPointovih predstavitev. Ta dogodek vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride v zadnji fazi postopka odpiranja.

Microsoft uporablja te podatke za zagotavljanje ustreznega delovanja funkcije in učinkovitega postopka odpiranja predstavitev.

Zbrana so ta polja:

  - **Data\_AntiVirusScanMethod:long** – Nabor vnaprej določenih vrednosti za vrsto protivirusnega pregleda (IOAV, AMSI, None itd.).

  - **Data\_AntiVirusScanStatus:long** – Nabor vnaprej določenih vrednosti za protivirusni pregled, ki se izvede za vsak odprti dokument (NoThreatsDetected, Failed, MalwareDetected itd.).

  - **Data\_CloseAndReopen:bool** – Ali je bil ta dokument zaprt in nato znova odprt?

  - **Data\_DetachedDuration:long** – Čas odpete dejavnosti/neizvajanja dejavnosti.

  - **Data\_Doc\_AccessMode:long** – Način odpiranja dokumenta (samo za branje/branje in pisanje).

  - **Data\_Doc\_AssistedReadingReasons:long** – Nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

  - **Data_Doc_AsyncOpenKind:long – ** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

  - **Data\_Doc\_ChunkingType:long** – Način shranjevanja dokumenta v SharePointu.

  - **Data\_Doc\_EdpState:long** – Stanje zaščite podatkov podjetja za dokument.

  - **Data\_Doc\_Ext:string** – Pripona dokumenta.

  - **Data\_Doc\_Extenstion:string** – Pripona dokumenta.

  - **Data\_Doc\_FileFormat:long** – Nabor vnaprej določenih vrednosti za obliko zapisa datoteke (bolj podrobno kot za pripono).

  - **Data\_Doc\_Fqdn:string** – Mesto, kjer je dokument shranjen (SharePoint.com, live.net); na voljo samo za domene v storitvi Office 365.

  - **Data\_Doc\_FqdnHash:string** – Zgoščena vrednost mesta shrambe dokumenta.

  - **Data\_Doc\_IdentityTelemetryId:string** – Enolični GUID uporabnika.

  - **Data\_Doc\_IdentityUniqueId:string** – Enolični identifikator identitete, ki je bila uporabljena za dokumente v skupni rabi.

  - **Data\_Doc\_IOFlags:long** – Bitna maska za različne zastavice danega dokumenta, povezane z V/I.

  - **Data\_Doc\_IrmRights:long** – Nabor vnaprej določenih vrednosti za vrsto upravljanja pravic do informacij, ki velja za ta dokument (»Forward«, »Reply«, »SecureReader«, »Edit« itd.).

  - **Data\_Doc\_IsCloudCollabEnabled:bool** – Ima vrednost »true«, če je bila že prejeta glava HTTP »IsCloudCollabEnabled«, ki njo je poslala zahteva OPTIONS.

  - **Data\_Doc\_IsIncrementalOpen:bool** – Ali je bil dokument odprt postopoma (nova funkcija, ki odpre dokument tako, da ne prenese celoten dokument).

  - **Data\_Doc\_IsOcsSupported:bool** – Ali dokument podpira soavtorstvo z novo storitvijo OCS.

  - **Data\_Doc\_IsOpeningOfflineCopy:bool** – Ali je bil dokument odprt iz lokalnega predpomnilnika?

  - **Data\_Doc\_IsSyncBacked:bool** –Ali je bil dokument odprt iz mape, za katero se uporablja aplikacija za povratno sinhronizacijo v storitvi OneDrive.

  - **Data\_Doc\_Location:long** – Nabor vnaprej določenih vrednosti za mesto shranjevanja dokumenta (lokalno, SharePoint, WOPI, omrežje itd.).

  - **Data\_Doc\_LocationDetails:long** – Nabor vnaprej določenih vrednosti podrobnejše lokacije (mapa »Začasno«, mapa »Prenosi«, dokumenti storitve OneDrive, slike storitve OneDrive itd.).

  - **Data\_Doc\_NumberCoAuthors:long** –Število soavtorjev, ko je bil dokument odprt.

  - **Data\_Doc\_PasswordFlags:long** – Nabor vnaprej določenih vrednosti za način šifriranja dokumenta z geslom (brez, geslo za branje, geslo za urejanje).

  - **Data\_Doc\_ReadOnlyReasons:long** – Nabor vnaprej določenih vrednosti, zakaj je bil ta dokument označen samo za branje (zaklenjeno v strežniku, dokončni dokument, zaščiteno z geslom za urejanje itd.).

  - **Data\_Doc\_ResourceIdHash:string** – Zgoščena vrednost identifikatorja vira za dokumente, shranjene v oblaku.

  - **Data_Doc_RtcType – **  označuje, kako je bil kanal v realnem času (RTC) nastavljen za trenutno datoteko (onemogočeno, nepodprto, na zahtevo, vedno vklopljeno itn.).

  - **Data\_Doc\_ServerDocId:string –** nespremenljivi identifikator za dokumente, shranjene v oblaku

  - **Data\_Doc\_ServerProtocol:long** – Nabor vnaprej določenih vrednosti, ki jih protokol uporablja za komunikacijo s strežnikom (Http, Cobalt, WOPI itd.).

  - **Data\_Doc\_ServerType:long** – Nabor vnaprej določenih vrednosti za vrsto strežnika (SharePoint, DropBox, WOPI).

  - **Data\_Doc\_ServerVersion:long** – Preverja, ali strežnik temelji na sistemu Office14, Office15 ali Office 16.

  - **Data\_Doc\_SessionId:long** – Ustvarjeni GUID, ki prepozna primerek dokumenta v seji istega procesa.

  - **Data\_Doc\_SharePointServiceContext:string** – Neprosojen niz, običajno »GridManagerID.FarmID«. Uporabni dogodki za korelacijo odjemalskih in strežniških dnevnikov.

  - **Data\_Doc\_SizeInBytes:long** – Velikost dokumenta v bajtih.

  - **Data\_Doc\_SpecialChars:long** – Bitna maska, ki označuje posebne znake v URL-ju ali poti dokumenta.

  - **Data\_Doc\_StorageProviderId:string** – Niz, ki prepozna ponudnika za shranjevanje dokumentov, npr. »DropBox«.

  - **Data\_Doc\_StreamAvailability:long** – Nabor vnaprej določenih vrednosti za stanje dokumenta Stream (na voljo, stalno onemogočeno, ni na voljo).

  - **Data\_Doc\_UrlHash:string** – Zgoščena vrednost polnega URL-ja za dokumente, shranjene v oblaku.

  - **Data\_Doc\_UsedWrsDataOnOpen:bool** – Ima vrednost »true«, če je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS na strani gostitelja.

  - **Data\_Doc\_WopiServiceId:string** – Identifikator storitve WOPI, npr. »Dropbox«.

  - **Data\_ExecutionCount:long** – Kolikokrat je bil izveden protokol IncOpen pred izvedbo tega (OpenComplete) protokola.

  - **Data\_FailureComponent:long** – Nabor vnaprej določenih vrednosti komponent, zaradi katerih tega protokola ni bilo mogoče izvesti. (Spor, CSI, Internal itd.).

  - **Data\_FailureReason:long** – Nabor vnaprej določenih vrednosti vzrokov napake (FileIsCorrupt, BlockedByAntivirus itd.).

  - **Data_FullDownloadRoundTripCount:long** – število izvedenih povratnih poti do strežnika za prenos celotnega dokumenta.
  
  - **Data_IsProtocolRunInIncOpenMode:bool** – ali je bil protokol zagnan za postopni prenos – to je vrsta prenosa, pri katerem so deli dokumenta preneseni po tem, ko so bili prikazani uporabniku.

  - **Data\_MethodId:long** – Katera vrstica kode je bila zadnja izvedena v postopku.

  - **Data\_StopwatchDuration:long** – Skupni čas dejavnosti.

  - **Data\_TimeToEdit:long** Čas, potreben, da je dokument mogoče urejati.

  - **Data\_TimeToView:long** – Trajanje upodabljanja prvega diapozitiva dokumenta.

  - **Data\_UnhandledException:bool** – Ali so na voljo katere koli neobravnavane izvorne izjeme?

#### <a name="officepowerpointdocoperationsave"></a>Office.PowerPoint.DocOperation.Save

Podatki so zbrani, kadar koli PowerPoint izvede postopek shranjevanja s potjo sodobne kode. Dogodek vsebuje vrsto rezultata uspešne oz. neuspešne metrike učinkovitosti shranjevanja in pomembne metapodatke dokumenta.  Napake pri shranjevanju lahko privedejo do izgube podatkov. Microsoft uporablja te podatke za zagotavljanje ustreznega delovanje funkcije in uspešnega shranjevanja uporabnikove vsebine.

Zbrana so ta polja:

  - **Data\_AddDocTelemetryResult:long** – Ali ima ta dolgi vnos vso zahtevano telemetrijo dokumenta (polja »Data\_Doc\_\*«)? Če je nima, zakaj?

  - **Data\_BeforeSaveEvent:long** – Trajanje pridobivanja dokumenta pred dogodkom shranjevanja.

  - **Data\_CheckDownRevSaveTimeMS:long** – Trajanje preverjanja revizije.

  - **Data\_CheckMacroSaveTimeMS:long** – Trajanje shranjevanja makrov.

  - **Data\_ClearAutoSaveTimeMS:long** – Trajanje čiščenja zastavice za samodejno shranjevanje.

  - **Data\_ClearDirtyFlagTimeMS:long** – Trajanje čiščenja zastavice nečistega dokumenta.

  - **Data\_CloneDocumentTimeMS:long** – Trajanje kloniranja dokumenta pred začetkom postopka shranjevanja.

  - **Data\_CommitTransactionTimeMS:long** – Trajanje potrjevanja transakcije shranjevanja.

  - **Data\_CppUncaughtExceptionCount:long** – Nezaznane izvorne izjeme med izvajanjem dejavnosti.

  - **Data\_DetachedDuration:long** – Čas odpete dejavnosti/neizvajanja dejavnosti.

  - **Data\_Doc\_AccessMode:long** – Način odpiranja dokumenta (samo za branje/branje in pisanje).

  - **Data\_Doc\_AssistedReadingReasons:long** – Nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

  - **Data_Doc_AsyncOpenKind:long – ** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

  - **Data\_Doc\_ChunkingType:long** – Način shranjevanja dokumenta v SharePointu.

  - **Data\_Doc\_EdpState:long** – Stanje zaščite podatkov podjetja za dokument.

  - **Data\_Doc\_Ext:string** – Pripona dokumenta.

  - **Data\_Doc\_Extenstion:string** – Pripona dokumenta.

  - **Data\_Doc\_FileFormat:long** – Nabor vnaprej določenih vrednosti za obliko zapisa datoteke (bolj podrobno kot za pripono).

  - **Data\_Doc\_Fqdn:string** – Mesto, kjer je dokument shranjen (SharePoint.com, live.net); na voljo samo za domene v storitvi Office 365.

  - **Data\_Doc\_FqdnHash:string** – Zgoščena vrednost mesta shrambe dokumenta.

  - **Data\_Doc\_IdentityTelemetryId:string** – Enolični GUID uporabnika.

  - **Data\_Doc\_IdentityUniqueId:string** – Enolični identifikator identitete, ki je bila uporabljena za dokumente v skupni rabi.

  - **Data\_Doc\_IOFlags:long** – Bitna maska za različne zastavice danega dokumenta, povezane z V/I.

  - **Data\_Doc\_IrmRights:long** – Nabor vnaprej določenih vrednosti za vrsto upravljanja pravic do informacij, ki velja za ta dokument (»Forward«, »Reply«, »SecureReader«, »Edit« itd.).

  - **Data\_Doc\_IsCloudCollabEnabled:bool** – Ima vrednost »true«, če je bila že prejeta glava HTTP »IsCloudCollabEnabled«, ki njo je poslala zahteva OPTIONS.

  - **Data\_Doc\_IsIncrementalOpen:bool** – Ali je bil dokument odprt postopoma (nova funkcija, ki odpre dokument tako, da ne prenese celoten dokument).

  - **Data\_Doc\_IsOcsSupported:bool** – Ali dokument podpira soavtorstvo z novo storitvijo OCS.

  - **Data\_Doc\_IsOpeningOfflineCopy:bool** – Preverja, ali je bil dokument odprt v lokalnem predpomnilniku.

  - **Data\_Doc\_IsSyncBacked:bool** –Ali je bil dokument odprt iz mape, za katero se uporablja aplikacija za povratno sinhronizacijo v storitvi OneDrive.

  - **Data\_Doc\_Location:long** – Nabor vnaprej določenih vrednosti za mesto shranjevanja dokumenta (lokalno, SharePoint, WOPI, omrežje itd.).

  - **Data\_Doc\_LocationDetails:long** – Nabor vnaprej določenih vrednosti podrobnejše lokacije (mapa »Začasno«, mapa »Prenosi«, dokumenti storitve OneDrive, slike storitve OneDrive itd.).

  - **Data\_Doc\_NumberCoAuthors:long** –Število soavtorjev, ko je bil dokument odprt.

  - **Data\_Doc\_PasswordFlags:long** – Nabor vnaprej določenih vrednosti za način šifriranja dokumenta z geslom (brez, geslo za branje, geslo za urejanje).

  - **Data\_Doc\_ReadOnlyReasons:long** – Nabor vnaprej določenih vrednosti, zakaj je bil ta dokument označen samo za branje (zaklenjeno v strežniku, dokončni dokument, zaščiteno z geslom za urejanje itd.).

  - **Data\_Doc\_ResourceIdHash:string** – Zgoščena vrednost identifikatorja vira za dokumente, shranjene v oblaku.

  - **Data_Doc_RtcType – **  označuje, kako je bil kanal v realnem času (RTC) nastavljen za trenutno datoteko (onemogočeno, nepodprto, na zahtevo, vedno vklopljeno itn.).

  - **Data\_Doc\_ServerDocId:string –** nespremenljivi identifikator za dokumente, shranjene v oblaku

  - **Data\_Doc\_ServerProtocol:long** – Nabor vnaprej določenih vrednosti, ki jih protokol uporablja za komunikacijo s strežnikom (Http, Cobalt, WOPI itd.).

  - **Data\_Doc\_ServerType:long** – Nabor vnaprej določenih vrednosti za vrsto strežnika (SharePoint, DropBox, WOPI).

  - **Data\_Doc\_ServerVersion:long** – Preverja, ali strežnik temelji na sistemu Office14, Office15 ali Office 16.

  - **Data\_Doc\_SessionId:long** – Ustvarjeni GUID, ki prepozna primerek dokumenta v seji istega procesa.

  - **Data\_Doc\_SharePointServiceContext:string** – Neprosojen niz, običajno »GridManagerID.FarmID«. Uporabni dogodki za korelacijo odjemalskih in strežniških dnevnikov.

  - **Data\_Doc\_SizeInBytes:long** – Velikost dokumenta v bajtih.

  - **Data\_Doc\_SpecialChars:long** – Bitna maska, ki označuje posebne znake v URL-ju ali poti dokumenta.

  - **Data\_Doc\_StorageProviderId:string** – Niz, ki prepozna ponudnika za shranjevanje dokumentov, npr. »DropBox«.

  - **Data\_Doc\_StreamAvailability:long** – Nabor vnaprej določenih vrednosti za stanje dokumenta Stream (na voljo, stalno onemogočeno, ni na voljo).

  - **Data\_Doc\_UrlHash:string** – Zgoščena vrednost polnega URL-ja za dokumente, shranjene v oblaku.

  - **Data\_Doc\_UsedWrsDataOnOpen:bool** – Ima vrednost »true«, če je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS na strani gostitelja.

  - **Data\_Doc\_WopiServiceId:string** – Identifikator storitve WOPI, npr. »Dropbox«.

  - **Data\_DurationUAEOnSaveStartedMs:long** – Trajanje zapiranja neznane aplikacije med shranjevanjem.

  - **Data\_EnsureSaveTransactionTimeMS:long** – Trajanje preverjanja ustvarjanja transakcije shranjevanja, če ta še ni na voljo.

  - **Data\_FailureComponent:long** – Nabor vnaprej določenih vrednosti komponent, zaradi katerih tega protokola ni bilo mogoče izvesti. (Spor, CSI, Internal itd.).

  - **Data\_FailureReason:long** – Nabor vnaprej določenih vrednosti vzrokov napake (FileIsCorrupt, BlockedByAntivirus itd.).

  - **Data\_fLifeguarded:bool** – Ali je bil dokument kdaj zavarovan (funkcija za samodejno odpravljanje težav z dokumenti brez pozivanja uporabnika)?

  - **Data\_HandleEnsureContentType:long** – Trajanje preverjanja ustreznosti vseh vrst vsebine.

  - **Data\_HandleEnsureContentTypeTimeMS:long** – Trajanje preverjanja ustreznosti vseh vrst vsebine.

  - **Data\_HasEmbeddedFont:bool** – Ali ta dokument vsebuje vdelane pisave?

  - **Data\_InitializeSaveTimeMS:long** – Trajanje inicializiranja vsebine dokumenta za začetek shranjevanja.

  - **Data\_InOCSTransition:bool** – Ali se to shranjevanje izvaja za prehod v strežnik OCS?

  - **Data\_IsSavingWithEmbeddedFont:bool** – Ali ta dokument vsebuje vdelane pisave?

  - **Data\_MethodId:long** – Katera vrstica kode je bila zadnja izvedena v postopku.

  - **Data\_PerformEmbedFontsTimeMS:long** – Trajanje serializacije vdelanih pisav.

  - **Data\_PerformModernSaveTimeMS:long** – Trajanje izvajanje sodobnega shranjevanja (nova koda).

  - **Data\_PerformPostSaveTimeMS:long** – Trajanje izvajanja funkcij po shranjevanju (obvestila, razveljavitev vnosov).

  - **Data\_PrepareForSaveTimeMS:long** – Trajanje zagona shranjevanja.

  - **Data\_RaiseDocumentBeforeSaveEventTimeMS:long** – Trajanje pridobivanja dogodka »BeforeSave«.

  - **Data\_ReflectDocumentChangeTimeMS:long** – Trajanje zrcaljenja shranjenih sprememb v UI (vnovična dopolnitev sličic itd.).

  - **Data\_ReportStartTimeMS:long** – Trajanje dokončanja inicializiranja telemetrije za shranjevanje.

  - **Data\_ReportSuccessTimeMS:long** – Trajanje dokončanja poročanja o uspešnem shranjevanju.

  - **Data\_ResetDirtyFlagOnErrorTimeMS:long** – Trajanje ponastavitve zastavice napake za nečisti dokument.

  - **Data\_SaveReason:long** – Nabor vnaprej določenih vrednosti, zakaj je bilo izvedeno to shranjevanje. (AutoSave, ToOCSTransitionSave, ToCSITransitionSave itd.).

  - **Data\_SaveType:long** – Nabor vnaprej določenih vrednosti vrste shranjevanja (SaveAs, Publish, Manual, OMSave itd.).

  - **Data\_SavingWithFont:bool** – Ali shranjujemo dokument z novimi vdelanimi pisavami?

  - **Data\_ScrubClonedDocumentTimeMS:long** – Trajanje odstranjevanja osebnih podatkov v klonirani kopiji dokumenta.

  - **Data\_StopwatchDuration:long** – Skupni čas dejavnosti.

  - **Data\_TransactionType:long** – Ali gre za transakcijo shranjevanja »Save« oz. »MergeAndSave«?

#### <a name="officepowerpointdocoperationsaveas"></a>Office.PowerPoint.DocOperation.SaveAs

Podatki so zbrani, kadar koli PowerPoint izvede postopek »Shrani kot«. Dogodek vsebuje vrsto rezultata uspešne oz. neuspešne metrike učinkovitosti shranjevanja in pomembne metapodatke dokumenta. Napake pri shranjevanju lahko privedejo do izgube podatkov.  Microsoft uporablja te podatke za zagotavljanje ustreznega delovanje funkcije in uspešnega shranjevanja uporabnikove vsebine.

Zbrana so sledeča polja:

- **Data_AddDocTelemetryResult:long** – označuje, ali ima ta dolgi vnos vso zahtevano telemetrijo dokumenta (polja »Data_Doc_*«)? Če je nima, zakaj?

- **Data_CppUncaughtExceptionCount:long** – nezaznane izvirne izjeme med izvedbo dejavnosti.

- **Data_DetachedDuration:long** – čas, v katerem je bila dejavnost ločena/ni bila izvajana.

- **Data_DstDoc_AccessMode:long** – način odpiranja tega dokumenta (samo za branje | branje in pisanje).

- **Data_DstDoc_AssistedReadingReasons:long** – nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

- **Data_DstDoc_AsyncOpenKind:long – ** označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

- **Data_DstDoc_ChunkingType:long** – način shranjevanja dokumenta v SharePointu

- **Data_DstDoc_EdpState:long** – stanje zaščite podatkov podjetja za dokument.

- **Data_DstDoc_Ext:string** – pripona dokumenta.

- **Data_DstDoc_Extension:string** – pripona dokumenta.

- **Data_DstDoc_FileFormat:long** – nabor vnaprej določenih vrednosti za obliko zapisa datoteke (bolj podrobno kot za pripono).

- **Data_DstDoc_Fqdn:string** – mesto, kjer je dokument shranjen (SharePoint.com, live.net); na voljo samo za domene v storitvi Office 365.
    
- **Data_DstDoc_FqdnHash:string** – zgoščena vrednost mesta shrambe dokumenta.

- **Data_DstDoc_IdentityTelemetryId:string** – enolični GUID uporabnika.

- **Data_DstDoc_IdentityUniqueId:string** – enolični identifikator identitete, ki je bila uporabljena za dejanje dokumentov v skupni rabi.

- **Data_DstDoc_IOFlags:long** – bitna maska za različne zastavice danega dokumenta, povezane z VI.

- **Data_DstDoc_IrmRights:long** – nabor vnaprej določenih vrednosti za vrsto upravljanja pravic do informacij, ki velja za ta dokument (»Posredovanje«, »Odgovarjanje«, »SecureReader«, »Urejanje« itd.).
    
- **Data_DstDoc_IsCloudCollabEnabled:bool** – ima vrednost »true«, če je bila že prejeta glava HTTP »IsCloudCollabEnabled«, ki jo je poslala zahteva OPTIONS.

- **Data_DstDoc_IsIncrementalOpen:bool** – označuje, ali je bil dokument odprt postopoma (nova funkcija, ki odpre dokument, ne da bi bilo treba prenesti celoten dokument).

- **Data_DstDoc_IsOcsSupported:bool** – označuje, ali dokument podpira soavtorstvo z novo storitvijo OCS.

- **Data_DstDoc_IsOpeningOfflineCopy:bool** – preverja, ali je bil dokument odprt v lokalnem predpomnilniku.

- **Data_DstDoc_IsSyncBacked:bool** –označuje, ali je bil dokument odprt v mapi, za katero se uporablja aplikacija za povratno sinhronizacijo v storitvi OneDrive.
    
- **Data_DstDoc_Location:long** – nabor vnaprej določenih vrednosti za mesto shrambe dokumenta (lokalno, SharePoint, WOPI, omrežje itd.).

- **Data_DstDoc_LocationDetails:long** – nabor vnaprej določenih vrednosti podrobnejše lokacije (mapa »Začasno«, mapa »Prenosi«, dokumenti storitve OneDrive, slike storitve OneDrive itd.).

- **Data_DstDoc_NumberCoAuthors:long** –število soavtorjev v trenutku, ko je bil dokument odprt.

- **Data_DstDoc_PasswordFlags:long** – nabor vnaprej določenih vrednosti za način šifriranja dokumenta z geslom (brez, geslo za branje, geslo za urejanje).

- **Data_DstDoc_ReadOnlyReasons:long** – nabor vnaprej določenih vrednosti, zakaj je bil ta dokument označen samo za branje (zaklenjeno v strežniku, končni dokument, zaščiteno z geslom za urejanje itd.).

- **Data_DstDoc_ResourceIdHash:string** – zgoščena vrednost identifikatorja vira za dokumente, shranjene v oblaku.

- **Data_DstDoc_ServerDocId:string** – nespremenljivi identifikator za dokumente, shranjene v oblaku.

- **Data_DstDoc_ServerProtocol:long** – nabor vnaprej določenih vrednosti, ki jih protokol uporablja za komunikacijo s strežnikom (Http, Cobalt, WOPI itd.).

- **Data_DstDoc_ServerType:long** – nabor vnaprej določenih vrednosti za vrsto strežnika (SharePoint, DropBox, WOPI).

- **Data_DstDoc_ServerVersion:long** – preverja, ali strežnik temelji na sistemu Office 14, Office 15 ali Office 16.

- **Data_DstDoc_SessionId:long** – ustvarjeni GUID, ki prepozna primerek dokumenta v isti seji procesa.

- **Data_DstDoc_SharePointServiceContext:string** – neprosojen niz, običajno »GridManagerID.FarmID«. Uporabni dogodki za korelacijo odjemalskih in strežniških dnevnikov.

- **Data_DstDoc_SizeInBytes:long** – velikost dokumenta v bajtih.

- **Data_DstDoc_SpecialChars:long** – bitna maska, ki označuje posebne znake v URL-ju ali poti dokumenta.

- **Data_DstDoc_StorageProviderId:string** – niz, ki prepozna ponudnika shrambe dokumentov, npr. »DropBox«.

- **Data_DstDoc_StorageProviderId:string** – nabor vnaprej določenih vrednosti za stanje toka dokumentov (na voljo, stalno onemogočeno, ni na voljo).

- **Data_DstDoc_UrlHash:string** – zgoščena vrednost polnega URL-ja za dokumente, shranjene v oblaku.

- **Data_DstDoc_UsedWrsDataOnOpen:bool** – ima vrednost »true«, če je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS v gostitelju.

- **Data_DstDoc_WopiServiceId:string** – identifikator storitve WOPI, npr. Dropbox.

- **Data_FileType:long** – nabor vnaprej določenih vrednosti notranje vrste datoteke.

- **Data_fLifeguarded:bool** – označuje, ali je bil dokument kdaj zavarovan (funkcija za samodejno odpravljanje težav z dokumenti brez pozivanja uporabnika)?

- **Data_FWebCreated:bool** – označuje, ali ta dokument vsebuje zastavico »WebCreator«?

- **Data_SaveReason:long** – nabor vnaprej določenih vrednosti, zakaj je bilo izvedeno to shranjevanje. (AutoSave, ToOCSTransitionSave, ToCSITransitionSave itd.).

- **Data_SaveType:long** – nabor vnaprej določenih vrednosti vrste shranjevanja (»SaveAs«, »Publish«, »Manual«, OMSave itd.). 

- **Data_SrcDoc_AccessMode:long** – način odpiranja tega dokumenta (samo za branje | branje in pisanje).

- **Data_SrcDoc_AssistedReadingReasons:long** – nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

- **Data_SrcDoc_AsyncOpenKind:long – ** označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

- **Data_SrcDoc_ChunkingType:long** – način shranjevanja dokumenta v SharePointu 

- **Data_SrcDoc_EdpState:long** – stanje zaščite podatkov podjetja za dokument.

- **Data_SrcDoc_Ext:string** – pripona dokumenta.

- **Data_SrcDoc_Extension:string** – pripona dokumenta.

- **Data_SrcDoc_FileFormat:long** – nabor vnaprej določenih vrednosti za obliko zapisa datoteke (bolj podrobno kot za pripono).

- **Data_SrcDoc_Fqdn:string** – mesto, kjer je dokument shranjen (SharePoint.com, live.net); na voljo samo za domene v storitvi Office 365.

- **Data_SrcDoc_FqdnHash:string** – zgoščena vrednost mesta shrambe dokumenta.

- **Data_SrcDoc_IdentityTelemetryId:string** – enolični GUID uporabnika.

- **Data_SrcDoc_IdentityUniqueId:string** – enolični identifikator identitete, ki je bila uporabljena za dejanje dokumentov v skupni rabi.

- **Data_SrcDoc_IOFlags:long** – bitna maska za različne zastavice danega dokumenta, povezane z VI.

- **Data_SrcDoc_IrmRights:long** – nabor vnaprej določenih vrednosti za vrsto upravljanja pravic do informacij, ki velja za ta dokument (»Forward«, »Reply«, »SecureReader«, »Edit« itd.).

- **Data_SrcDoc_IsCloudCollabEnabled:bool** – ima vrednost »true«, če je bila že prejeta glava HTTP »IsCloudCollabEnabled«, ki jo je poslala zahteva OPTIONS.

- **Data_SrcDoc_IsIncrementalOpen:bool** – označuje, ali je bil dokument odprt postopoma (nova funkcija, ki odpre dokument, ne da bi bilo treba prenesti celoten dokument).

- **Data_SrcDoc_IsOcsSupported:bool** – označuje, ali dokument podpira soavtorstvo z novo storitvijo OCS.

- **Data_SrcDoc_IsOpeningOfflineCopy:bool** – preverja, ali je dokument odprt v lokalnem predpomnilniku.

- **Data_SrcDoc_IsSyncBacked:bool** –označuje, ali je bil dokument odprt v mapi, za katero se uporablja aplikacija za povratno sinhronizacijo v storitvi OneDrive.

- **Data_SrcDoc_Location:long** – nabor vnaprej določenih vrednosti za mesto shranjevanja dokumenta (lokalno, SharePoint, WOPI, omrežje itd.).

- **Data_SrcDoc_LocationDetails:long** – nabor vnaprej določenih vrednosti podrobnejše lokacije (mapa »Začasno«, mapa »Prenosi«, dokumenti storitve One Drive, slike storitve One Drive itd.).

- **Data_SrcDoc_NumberCoAuthors:long** –število soavtorjev v trenutku, ko je bil dokument odprt.

- **Data_SrcDoc_PasswordFlags:long** – nabor vnaprej določenih vrednosti za način šifriranja dokumenta z geslom (brez, geslo za branje, geslo za urejanje).

- **Data_SrcDoc_ReadOnlyReasons:long** – nabor vnaprej določenih vrednosti, zakaj je bil ta dokument označen samo za branje (zaklenjeno v strežniku, končni dokument, zaščiteno z geslom za urejanje itd.).

- **Data_SrcDoc_ResourceIdHash:string** – zgoščena vrednost identifikatorja vira za dokumente, shranjene v oblaku.

- **Data_SrcDoc_ServerDocId:string** – nespremenljivi identifikator za dokumente, shranjene v oblaku.

- **Data_SrcDoc_ServerProtocol:long** – nabor vnaprej določenih vrednosti, ki jih protokol uporablja za komunikacijo s strežnikom (Http, Cobalt, WOPI itd.).

- **Data_SrcDoc_ServerType:long** – nabor vnaprej določenih vrednosti za vrsto strežnika (SharePoint, DropBox, WOPI).

- **Data_SrcDoc_ServerVersion:long** – preverja, ali strežnik temelji na sistemu Office 14, Office 15 ali Office 16. »DataSrcDocSessionId:long« – ustvarjeni GUID, ki prepozna primerek dokumenta v isti seji procesa

- **Data_SrcDoc_SharePointServiceContext:string** – neprosojen niz, običajno »GridManagerID.FarmID«. Uporabni dogodki za korelacijo odjemalskih in strežniških dnevnikov.

- **Data_SrcDoc_SizeInBytes:long** – velikost dokumenta v bajtih.

- **Data_SrcDoc_SpecialChars:long** – bitna maska, ki označuje posebne znake v URL-ju ali poti dokumenta.

- **Data_SrcDoc_StorageProviderId:string** – niz, ki prepozna ponudnika shrambe dokumentov, npr. »DropBox«.

- **Data_SrcDoc_StreamAvailability:long** – nabor vnaprej določenih vrednosti za stanje toka dokumentov (na voljo, stalno onemogočeno, ni na voljo).

- **Data_SrcDoc_UrlHash:string** – zgoščena vrednost polnega URL-ja za dokumente, shranjene v oblaku.

- **Data_SrcDoc_UsedWrsDataOnOpen:bool** – ima vrednost »true«, če je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS v gostitelju.

- **Data_SrcDoc_WopiServiceId:string** – identifikator storitve WOPI, npr. »Dropbox«.

- **Data_StopwatchDuration:long** – skupni čas dejavnosti.

- **Data_TypeOfSaveDialog:long** – vnaprej opredeljen nabor vrednosti pogovornega okna (RUN_SAVEAS_DLG,RUN_SAVEMEDIA_DLG, RUN_SAVEAS_VIDEO_DLG itd.)

- **DstDoc** – nova lokacija dokumenta. 

- **SrcDoc** – izvirna lokacija dokumenta.


#### <a name="officepowerpointdocoperationsavelegacy"></a>Office.PowerPoint.DocOperation.SaveLegacy

Podatki so zbrani, kadar koli PowerPoint izvede postopek shranjevanja s potjo podedovane kode. Dogodek vsebuje vrsto rezultata uspešne oz. neuspešne metrike učinkovitosti shranjevanja in pomembne metapodatke dokumenta.  Napake pri shranjevanju lahko privedejo do izgube podatkov.  Microsoft uporablja te podatke za zagotavljanje ustreznega delovanje funkcije in uspešnega shranjevanja uporabnikove vsebine.

Zbrana so sledeča polja:

- **Data_AddDocTelemetryResult:long** – označuje, ali ima ta dolgi vnos vso zahtevano telemetrijo dokumenta (polja »Data_Doc_*«)? Če je nima, zakaj?

- **Data_CppUncaughtExceptionCount:long** – nezaznane izvirne izjeme med izvedbo dejavnosti.

- **Data_DetachedDuration:long** – čas, v katerem je bila dejavnost ločena/ni bila izvajana.

- **Data_Doc_AccessMode:long** – način odpiranja dokumenta (samo za branje | branje in pisanje)

- **Data_Doc_AssistedReadingReasons:long** – nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

- **Data_Doc_AsyncOpenKind:long – ** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

- **Data_Doc_ChunkingType:long** – način shranjevanja dokumenta v SharePointu.

- **Data_Doc_EdpState:long** – stanje zaščite podatkov podjetja za dokument.

- **Data_Doc_Ext:string** – pripona dokumenta.

- **Data_Doc_Extension:string** – pripona dokumenta.

- **Data_Doc_FileFormat:long** – nabor vnaprej določenih vrednosti za obliko zapisa datoteke (bolj podrobno kot za pripono).

- **Data_Doc_Fqdn:string** – mesto, kjer je dokument shranjen (SharePoint.com, live.net); na voljo samo za domene v storitvi Office 365.

- **Data_Doc_FqdnHash:string** – zgoščena vrednost mesta shrambe dokumenta.

- **Data_Doc_IdentityTelemetryId:string** – enolični GUID uporabnika.

- **Data_Doc_IdentityUniqueId:string** – enolični identifikator identitete, ki je bila uporabljena za dejanje dokumentov v skupni rabi.

- **Data_Doc_IOFlags:long** – bitna maska za različne zastavice danega dokumenta, povezane z VI.

- **Data_Doc_IrmRights:long** – nabor vnaprej določenih vrednosti za vrsto upravljanja pravic do informacij, ki velja za ta dokument (»Posredovanje«, »Odgovarjanje«, »SecureReader«, »Urejanje« itd.).

- **Data_Doc_IsCloudCollabEnabled:bool** – ima vrednost »true«, če je bila že prejeta glava HTTP »IsCloudCollabEnabled«, ki jo je poslala zahteva OPTIONS.

- **Data_Doc_IsIncrementalOpen:bool** – označuje, ali je bil dokument odprt postopoma (nova funkcija, ki odpre dokument, ne da bi bilo treba prenesti celoten dokument).

- **Data_Doc_IsOcsSupported:bool** – označuje, ali dokument podpira soavtorstvo z novo storitvijo OCS.

- **Data_Doc_IsOpeningOfflineCopy:bool** – preverja, ali je bil dokument odprt v lokalnem predpomnilniku.

- **Data_Doc_IsSyncBacked:bool** –označuje, ali je bil dokument odprt v mapi, za katero se uporablja aplikacija za povratno sinhronizacijo v storitvi OneDrive.

- **Data_Doc_Location:long** – nabor vnaprej določenih vrednosti za mesto shrambe dokumenta (lokalno, SharePoint, WOPI, omrežje itd.).

- **Data_Doc_LocationDetails:long** – nabor vnaprej določenih vrednosti podrobnejše lokacije (mapa »Začasno«, mapa »Prenosi«, dokumenti storitve OneDrive, slike storitve OneDrive itd.).

- **Data_Doc_NumberCoAuthors:long** –število soavtorjev v trenutku, ko je bil dokument odprt.

- **Data_Doc_PasswordFlags:long** – nabor vnaprej določenih vrednosti za način šifriranja dokumenta z geslom (brez, geslo za branje, geslo za urejanje).

- **Data_Doc_ReadOnlyReasons:long** – nabor vnaprej določenih vrednosti, zakaj je bil ta dokument označen samo za branje (zaklenjeno v strežniku, končni dokument, zaščiteno z geslom za urejanje itd.).

- **Data_Doc_ResourceIdHash:string** – zgoščena vrednost identifikatorja vira za dokumente, shranjene v oblaku.

- **Data_Doc_RtcType** – označuje, kako je bil kanal v realnem času (RTC) nastavljen za trenutno datoteko (onemogočeno, nepodprto, na zahtevo, vedno vklopljeno itn.).

- **Data_Doc_ServerDocId:string** – nespremenljivi identifikator za dokumente, shranjene v oblaku.

- **Data_Doc_ServerProtocol:long** – nabor vnaprej določenih vrednosti, ki jih protokol uporablja za komunikacijo s strežnikom (Http, Cobalt, WOPI itd.).

- **Data_Doc_ServerType:long** – nabor vnaprej določenih vrednosti za vrsto strežnika (SharePoint, DropBox, WOPI). 

- **Data_Doc_ServerVersion:long** – preverja, ali strežnik temelji na sistemu Office 14, Office 15 ali Office 16.

- **Data_Doc_SessionId:long** – ustvarjeni GUID, ki prepozna primerek dokumenta v isti seji procesa.

- **Data_Doc_SharePointServiceContext:string** – neprosojen niz, običajno »GridManagerID.FarmID«. Uporabni dogodki za korelacijo odjemalskih in strežniških dnevnikov.

- **Data_Doc_SizeInBytes:long** – velikost dokumenta v bajtih.

- **Data_Doc_SpecialChars:long** – bitna maska, ki označuje posebne znake v URL-ju ali poti dokumenta.

- **Data_Doc_StorageProviderId:string** – niz, ki prepozna ponudnika shrambe dokumentov, npr. »DropBox«.

- **Data_Doc_StreamAvailability:long** – nabor vnaprej določenih vrednosti za stanje toka dokumentov (na voljo, stalno onemogočeno, ni na voljo).

- **Data_Doc_UrlHash:string** – zgoščena vrednost polnega URL-ja za dokumente, shranjene v oblaku.

- **Data_Doc_UsedWrsDataOnOpen:bool** – ima vrednost »true«, če je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS v gostitelju.

- **Data_Doc_WopiServiceId:string** – identifikator storitve WOPI, npr. Dropbox.

- **Data_DstDoc_AccessMode:long** – način odpiranja tega dokumenta (samo za branje | branje in pisanje).

- **Data_DstDoc_AssistedReadingReasons:long** – nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

- **Data_DstDoc_AsyncOpenKind:long – ** označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

- **Data_DstDoc_ChunkingType:long** – način shranjevanja dokumenta v SharePointu

- **Data_DstDoc_EdpState:long** – stanje zaščite podatkov podjetja za dokument.

- **Data_DstDoc_Ext:string** – pripona dokumenta.

- **Data_DstDoc_Extension:string** – pripona dokumenta.

- **Data_DstDoc_FileFormat:long** – nabor vnaprej določenih vrednosti za obliko zapisa datoteke (bolj podrobno kot za pripono).

- **Data_DstDoc_Fqdn:string** – mesto, kjer je dokument shranjen (SharePoint.com, live.net); na voljo samo za domene v storitvi Office 365.
    
- **Data_DstDoc_FqdnHash:string** – zgoščena vrednost mesta shrambe dokumenta.

- **Data_DstDoc_IdentityTelemetryId:string** – enolični GUID uporabnika.

- **Data_DstDoc_IdentityUniqueId:string** – enolični identifikator identitete, ki je bila uporabljena za dejanje dokumentov v skupni rabi.

- **Data_DstDoc_IOFlags:long** – bitna maska za različne zastavice danega dokumenta, povezane z VI.

- **Data_DstDoc_IrmRights:long** – nabor vnaprej določenih vrednosti za vrsto upravljanja pravic do informacij, ki velja za ta dokument (»Posredovanje«, »Odgovarjanje«, »SecureReader«, »Urejanje« itd.).

- **Data_DstDoc_IsCloudCollabEnabled:bool** – ima vrednost »true«, če je bila že prejeta glava HTTP »IsCloudCollabEnabled«, ki jo je poslala zahteva OPTIONS.

- **Data_DstDoc_IsIncrementalOpen:bool** – označuje, ali je bil dokument odprt postopoma (nova funkcija, ki odpre dokument, ne da bi bilo treba prenesti celoten dokument).

- **Data_DstDoc_IsOcsSupported:bool** – označuje, ali dokument podpira soavtorstvo z novo storitvijo OCS.

- **Data_DstDoc_IsOpeningOfflineCopy:bool** – preverja, ali je bil dokument odprt v lokalnem predpomnilniku.

- **Data_DstDoc_IsSyncBacked:bool** –označuje, ali je bil dokument odprt v mapi, za katero se uporablja aplikacija za povratno sinhronizacijo v storitvi OneDrive.

- **Data_DstDoc_Location:long** – nabor vnaprej določenih vrednosti za mesto shrambe dokumenta (lokalno, SharePoint, WOPI, omrežje itd.).

- **Data_DstDoc_LocationDetails:long** – nabor vnaprej določenih vrednosti podrobnejše lokacije (mapa »Začasno«, mapa »Prenosi«, dokumenti storitve OneDrive, slike storitve OneDrive itd.).

- **Data_DstDoc_NumberCoAuthors:long** –število soavtorjev v trenutku, ko je bil dokument odprt.

- **Data_DstDoc_PasswordFlags:long** – nabor vnaprej določenih vrednosti za način šifriranja dokumenta z geslom (brez, geslo za branje, geslo za urejanje).

- **Data_DstDoc_ReadOnlyReasons:long** – nabor vnaprej določenih vrednosti, zakaj je bil ta dokument označen samo za branje (zaklenjeno v strežniku, končni dokument, zaščiteno z geslom za urejanje itd.)

- **Data_DstDoc_ResourceIdHash:string** – zgoščena vrednost identifikatorja vira za dokumente, shranjene v oblaku.

- **Data_DstDoc_ServerDocId:string** – nespremenljivi identifikator za dokumente, shranjene v oblaku.

- **Data_DstDoc_ServerProtocol:long** – nabor vnaprej določenih vrednosti, ki jih protokol uporablja za komunikacijo s strežnikom (Http, Cobalt, WOPI itd.).

- **Data_DstDoc_ServerType:long** – nabor vnaprej določenih vrednosti za vrsto strežnika (SharePoint, DropBox, WOPI).

- **Data_DstDoc_ServerVersion:long** – preverja, ali strežnik temelji na sistemu Office 14, Office 15 ali Office 16.

- **Data_DstDoc_SessionId:long** – ustvarjeni GUID, ki prepozna primerek dokumenta v isti seji procesa.

- **Data_DstDoc_SharePointServiceContext:string** – neprosojen niz, običajno »GridManagerID.FarmID«. Uporabni dogodki za korelacijo odjemalskih in strežniških dnevnikov.

- **Data_DstDoc_SizeInBytes:long** – velikost dokumenta v bajtih.

- **Data_DstDoc_SpecialChars:long** – bitna maska, ki označuje posebne znake v URL-ju ali poti dokumenta.

- **Data_DstDoc_StorageProviderId:string** – niz, ki prepozna ponudnika shrambe dokumentov, npr. »DropBox«.

- **Data_DstDoc_StorageProviderId:string** – nabor vnaprej določenih vrednosti za stanje toka dokumentov (na voljo, stalno onemogočeno, ni na voljo).

- **Data_DstDoc_UrlHash:string** – zgoščena vrednost polnega URL-ja za dokumente, shranjene v oblaku.

- **Data_DstDoc_UsedWrsDataOnOpen:bool** – ima vrednost »true«, če je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS v gostitelju.

- **Data_DstDoc_WopiServiceId:string** – identifikator storitve WOPI, npr. Dropbox.

- **Data_FileType:long** – nabor vnaprej določenih vrednosti notranje vrste datoteke.

- **Data_fLifeguarded:bool** – označuje, ali je bil dokument kdaj zavarovan (funkcija za samodejno odpravljanje težav z dokumenti brez pozivanja uporabnika)?

- **Data_SaveReason:long** – nabor vnaprej določenih vrednosti, zakaj je bilo izvedeno to shranjevanje. (AutoSave, ToOCSTransitionSave, ToCSITransitionSave itd.)

- **Data_SaveType:long** – nabor vnaprej določenih vrednosti vrste shranjevanja (»SaveAs«, »Publish«, »Manual«, OMSave itd.)

- **Data_SrcDoc_AccessMode:long** – način odpiranja tega dokumenta (samo za branje | branje in pisanje).

- **Data_SrcDoc_AssistedReadingReasons:long** – nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

- **Data_SrcDoc_AsyncOpenKind:long – ** označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

- **Data_SrcDoc_ChunkingType:long** – način shranjevanja dokumenta v SharePointu

- **Data_SrcDoc_EdpState:long** – stanje zaščite podatkov podjetja za dokument.

- **Data_SrcDoc_Ext:string** – pripona dokumenta.

- **Data_SrcDoc_Extension:string** – pripona dokumenta.

- **Data_SrcDoc_FileFormat:long** – nabor vnaprej določenih vrednosti za obliko zapisa datoteke (bolj podrobno kot za pripono).

- **Data_SrcDoc_Fqdn:string** – mesto, kjer je dokument shranjen (SharePoint.com, live.net); na voljo samo za domene v storitvi Office 365.

- **Data_SrcDoc_FqdnHash:string** – zgoščena vrednost mesta shrambe dokumenta. 

- **Data_SrcDoc_IdentityTelemetryId:string** – enolični GUID uporabnika.

- **Data_SrcDoc_IdentityUniqueId:string** – enolični identifikator identitete, ki je bila uporabljena za dejanje dokumentov v skupni rabi.

- **Data_SrcDoc_IOFlags:long** – bitna maska za različne zastavice danega dokumenta, povezane z VI.

- **Data_SrcDoc_IrmRights:long** – nabor vnaprej določenih vrednosti za vrsto upravljanja pravic do informacij, ki velja za ta dokument (»Forward«, »Reply«, »SecureReader«, »Edit« itd.).
    
- **Data_SrcDoc_IsCloudCollabEnabled:bool** – ima vrednost »true«, če je bila že prejeta glava HTTP »IsCloudCollabEnabled«, ki jo je poslala zahteva OPTIONS.

- **Data_SrcDoc_IsIncrementalOpen:bool** – označuje, ali je bil dokument odprt postopoma (nova funkcija, ki odpre dokument, ne da bi bilo treba prenesti celoten dokument).

- **Data_SrcDoc_IsOcsSupported:bool** – označuje, ali dokument podpira soavtorstvo z novo storitvijo OCS.

- **Data_SrcDoc_IsOpeningOfflineCopy:bool** – preverja, ali je dokument odprt v lokalnem predpomnilniku.

- **Data_SrcDoc_IsSyncBacked:bool** –označuje, ali je bil dokument odprt v mapi, za katero se uporablja aplikacija za povratno sinhronizacijo v storitvi OneDrive.

- **Data_SrcDoc_Location:long** – nabor vnaprej določenih vrednosti za mesto shranjevanja dokumenta (lokalno, SharePoint, WOPI, omrežje itd.).

- **Data_SrcDoc_LocationDetails:long** – nabor vnaprej določenih vrednosti podrobnejše lokacije (mapa »Začasno«, mapa »Prenosi«, dokumenti storitve One Drive, slike storitve One Drive itd.)

- **Data_SrcDoc_NumberCoAuthors:long** –število soavtorjev v trenutku, ko je bil dokument odprt.

- **Data_SrcDoc_PasswordFlags:long** – nabor vnaprej določenih vrednosti za način šifriranja dokumenta z geslom (brez, geslo za branje, geslo za urejanje).

- **Data_SrcDoc_ReadOnlyReasons:long** – nabor vnaprej določenih vrednosti, zakaj je bil ta dokument označen samo za branje (zaklenjeno v strežniku, končni dokument, zaščiteno z geslom za urejanje itd.).

- **Data_SrcDoc_ResourceIdHash:string** – zgoščena vrednost identifikatorja vira za dokumente, shranjene v oblaku.

- **Data_SrcDoc_ServerDocId:string** – nespremenljivi identifikator za dokumente, shranjene v oblaku.

- **Data_SrcDoc_ServerProtocol:long** – nabor vnaprej določenih vrednosti, ki jih protokol uporablja za komunikacijo s strežnikom (Http, Cobalt, WOPI itd.).

- **Data_SrcDoc_ServerType:long** – nabor vnaprej določenih vrednosti za vrsto strežnika (SharePoint, DropBox, WOPI).

- **Data_SrcDoc_ServerVersion:long** – preverja, ali strežnik temelji na sistemu Office 14, Office 15 ali Office 16.

- **Data_SrcDoc_SessionId:long** – ustvarjeni GUID, ki prepozna primerek dokumenta v isti seji procesa.

- **Data_SrcDoc_SharePointServiceContext:string** – neprosojen niz, običajno »GridManagerID.FarmID«. Uporabni dogodki za korelacijo odjemalskih in strežniških dnevnikov.

- **Data_SrcDoc_SizeInBytes:long** – velikost dokumenta v bajtih.

- **Data_SrcDoc_SpecialChars:long** – bitna maska, ki označuje posebne znake v URL-ju ali poti dokumenta.

- **Data_SrcDoc_StorageProviderId:string** – niz, ki prepozna ponudnika shrambe dokumentov, npr. »DropBox«.

- **Data_SrcDoc_StreamAvailability:long** – nabor vnaprej določenih vrednosti za stanje toka dokumentov (na voljo, stalno onemogočeno, ni na voljo).

- **Data_SrcDoc_UrlHash:string** – zgoščena vrednost polnega URL-ja za dokumente, shranjene v oblaku.

- **Data_SrcDoc_UsedWrsDataOnOpen:bool** – ima vrednost »true«, če je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS v gostitelju.

- **Data_SrcDoc_WopiServiceId:string** – identifikator storitve WOPI, npr. »Dropbox«.

- **Data_StopwatchDuration:long** – skupni čas dejavnosti.

- **Data_TypeOfSaveDialog:long** – vnaprej opredeljen nabor vrednosti pogovornega okna (RUN_SAVEAS_DLG, RUN_SAVEMEDIA_DLG, RUN_SAVEAS_VIDEO_DLG itd.)

- **Doc** – trenutni dokument za shranjevanje.

- **DstDoc** – novo mesto dokumenta (v primeru možnosti »Shrani kot«).

- **SrcDoc** – izvirno mesto dokumenta (v primeru možnosti »Shrani kot«).

#### <a name="officepowerpointpptmacshellprintinfo"></a>Office.PowerPoint.PPT.Mac.Shell.PrintInfo

Ti podatki so zbrani vsakič, ko je dokončan postopek izvoza v obliki datoteke PDF, in vsebujejo informacije o uspešnosti postopka. Te informacije so nujne za prepoznavanje uspešnosti postopkov izvoza v obliki datoteke PDF za našo aplikacijo.

Zbrana so naslednja polja:

- **Data_ExportAsPDFSucceed** – logična vrednost, ki označuje, ali je bil izvoz v obliki datoteke PDF uspešen.


#### <a name="officepowerpointpptsharedslideshowfailure"></a>Office.PowerPoint.PPT.Shared.SlideShow.Failure

Zbiranje neuspehov med diaprojekcijo kot ključna funkcija za PowerPoint. Microsoft zbira te podatke v primeru napak med diaprojekcijo za izboljšanje uporabniške izkušnje diaprojekcije. Microsoft uporablja te podatke za pridobivanje diagnostičnih informacij o tem, kje je prišlo do napake med izvajanjem uporabnikove diaprojekcije.

Zbrana so naslednja polja:

- **CountOArtErrors** – Skupno število napak OArt.

- **CountOtherErrors** – Skupno število drugih napak.

- **CountPPTErrors** – Skupno število napak PPT.

- **CountSlideShowErrors** – Skupno število napak diaprojekcije.

- **FirstOArtError** – Prva napaka v komponenti OArt.

- **FirstOtherError** – Prva napaka v drugih območjih.

- **FirstPPTError** – Prva napaka v datoteki PPT.

- **FirstSlideShowError** – Prva napaka v diaprojekciji.

    
#### <a name="officepowerpointrunprintoperation"></a>Office.PowerPoint.RunPrintOperation

Ti podatki so zbrani vsakič, ko je dokončana operacija tiskanja datoteke PDF, in vsebujejo informacije o vrsti postavitve, uporabi številk diapozitivov in uspešnosti operacije. Te informacije so kritične za identifikacijo uspešnosti operacij tiskanja datoteke PDF za našo aplikacijo.

Zbrana so naslednja polja:

- **Data_PrintWithSlideNumbers** – logična vrednost, ki označuje, ali uporabnik pri tiskanju uporablja številke diapozitivov.

- **Data_SavePrintLayoutType** – vrsta postavitve tiskanja na začetku operacije tiskanja ali izvažanja.

- **Data_Success** – logična vrednost, ki označuje, ali je bilo tiskanje uspešno.


#### <a name="officeprojectprojectfilesave"></a>Office.Project.ProjectFileSave

Project shrani datoteko. Ta dogodek označuje Projectovo shranjevanje. Microsoft lahko z njim oceni uspešnost Projectovega shranjevanja datoteke, kar je pomembno za preprečevanje izgube podatkov v dokumentu.

Zbrana so ta polja:

  - **Data\_TriggerTime** – Čas shranjevanja.

  - **Data\_FileType** – Vrsta datoteke, izbrana za shranjevanje projekta.
 
#### <a name="officesessionactivitystart"></a>Office.Session.Activity.Start

S tem dogodkom lahko prepoznamo, kdaj se je začela seja orodja za pretakanje podatkov.  Uporabljamo ga za zagotavljanje ustreznosti delovanja funkcij in nadzor. Ta dogodek ustvari Microsoftovo orodje za pretakanje podatkov za dodatek za Excel.

Zbrana so ta polja:

- **Activity_Name** – Ime dejavnosti »Session«.

- **Activity_CV** – ID za povezovanje dogodkov v seji povezave.

- **Activity_StartStopType** – Začetek.

- **Activity_DateTimeTicks** – Datum in čas dejavnosti.

#### <a name="officesessionactivitystop"></a>Office.Session.Activity.Stop

S tem dogodkom lahko prepoznamo, kdaj se je končala seja orodja za pretakanje podatkov. Uporabljamo ga za zagotavljanje ustreznosti delovanja funkcij in nadzor. Ta dogodek ustvari Microsoftovo orodje za pretakanje podatkov za dodatek za Excel.

Zbrana so ta polja:

- **Activity_Name** – Ime dejavnosti »Session«.

- **Activity_CV** – ID za povezovanje dogodkov v seji povezave.

- **Activity_StartStopType** – Konec.

- **Activity_DateTimeTicks** – Datum in čas dejavnosti.

#### <a name="officestreamdeviceactivitystart"></a>Office.StreamDevice.Activity.Start

S tem dogodkom lahko prepoznamo, ali je bil začetek pretakanja vira podatkov uspešen.   Uporabljamo ga za zagotavljanje ustreznosti delovanja funkcij in nadzor. Ta dogodek ustvari Microsoftovo orodje za pretakanje podatkov za dodatek za Excel.

Zbrana so ta polja:

- **Datasource_Type** – Informacije o serijski napravi ali storitvi aplikacije.

- **DataSource_Name** – Ime povezanega vira podatkov.

- **Activity_Name** – Ime dejavnosti »StreamDeviceData« ali »StreamFileData«.

- **Activity_CV** – ID za povezovanje dogodkov v seji povezave.

- **Activity_StartStopType** – Začetek.

- **Activity_DateTimeTicks** – Datum in čas dejavnosti.

#### <a name="officestreamdeviceactivitystop"></a>Office.StreamDevice.Activity.Stop

S tem dogodkom lahko prepoznamo, ali je bil konec pretakanja vira podatkov uspešen.   Uporabljamo ga za zagotavljanje ustreznosti delovanja funkcij in nadzor. Ta dogodek ustvari Microsoftovo orodje za pretakanje podatkov za dodatek za Excel.

Zbrana so ta polja:

- **Datasource_Type** – Informacije o serijski napravi ali storitvi aplikacije.

- **DataSource_Name** – Ime povezanega vira podatkov.

- **Activity_Name** – Ime dejavnosti »StreamDeviceData« ali »StreamFileData«.

- **Activity_CV** – ID za povezovanje dogodkov v seji povezave.

- **Activity_StartStopType** – Konec.

- **Activity_DateTimeTicks** – Datum in čas dejavnosti.

#### <a name="officetargetedmessagingabexperimentmessagetrigger"></a>Office.TargetedMessaging.ABExperimentMessageTrigger

Spremlja število uporabnikov, ki prejemajo sporočila storitev BizBar in Dynamic Canvas storitve TMS (TargetedMessagingService). Ti podatki so ključni za razumevanje vrste in območij sporočil, ki jih prejemajo uporabniki. Z njimi lahko zagotovimo, da uporabniki prejmejo vsa sporočila, nujna za nadaljnjo uporabo izdelka. Te podatke potrebujemo tudi za natančno ocenjevanje naših poskusov in akcij v storitvi TMS.

Zbrana so ta polja:

  - **Data\_Surface** – Ime območja, kamor je storitev poslala sporočilo.

  - **Data\_Flight** – Identifikator pilotne različice ECS/CT, uporabljene za pošiljanje tega sporočila.

  - **Data\_CampaignId** – Identifikator akcije, kateri pripada to sporočilo.

  - **Data\_MessageId** – Identifikator sporočila, ki ga je poslala ta storitev.

  - **Data\_TransactionId** – Identifikator transakcije s storitvijo.

  - **Data\_TriggerPoint** – Korak, v katerem je bil zabeležen ta dogodek (v prejete ali prikazanem sporočilu).

#### <a name="officetextfontpickerfontselectedwin32"></a>Office.Text.FontPickerFontSelected.Win32

Ta dogodek označuje, ali je bila prenesena pisava pravilno upodobljena. S temi podatki prepoznamo uspešen oz. neuspešen prenos pisave.

Zbrana so ta polja:

  - **Font name (Data\_Font)** – Ime pisave, izbrane v izbirniku pisav.

  - **User click (Data\_FClick)** – Ali je uporabnik izbral element z miško.

#### <a name="officetextresourceclientrequestresourceinternal"></a>Office.Text.ResourceClient.RequestResourceInternal

Ta dogodek označuje, ali je bila pisava pravilno prenesena. S temi podatki prepoznamo uspešno oz. neuspešno upodabljanje prenesene pisave.

Zbrana so ta polja:

  - **Data\_FontToken** – Ime shranjene datoteke sredstev.

  - **Data\_HTTPResult** – Rezultat zahteve HTTP.

  - **Data\_HTTPStatusCode** – Koda HTTP, ki jo vrne zahteva HTTP.

  - **Data\_isInternetOn** – Ali je bila med pridobivanjem sredstev vzpostavljena povezava.

  - **Data\_RequestUrl** – URL sredstev CDN, ki jih želimo pridobiti.



#### <a name="officetranslatordocumenttranslated"></a>Office.Translator.DocumentTranslated

Zbira podatke o uspešnem oz. neuspešnem prevajanju celotnega dokumenta, ki ga je uporabnik zagnal z orodjem Translator SDX. Ti podatki so ključni za ocenjevanje ustreznosti stanja funkcije prevajanja in odzivanje na morebitne izpade delovanja. S tem dogodkom spremljamo scenarij »Prevajanje dokumenta« v Wordu.

Zbrana so sledeča polja:

- **Data.actionSource** – kako je bil sprožen izbor prevajanja.

- **Data.bodyBackgroundColor** – barva ozadja vsebnika Officeove teme.

- **Data.bodyForegroundColor** – barva ospredja vsebnika Officeove teme.

- **Data.browserLang** – trenutni jezik prikaza brskalnika.

- **Data.browserOnline** – zastarelo.

- **Data.browserPlatform** – platforma brskalnika.

- **Data.browserUserAgent** – uporabnikov posrednik v brskalniku.

- **Data.colorDepth** – barvna globina sistema.

- **Data.contentLanguage** – zaznani jezik vsebine, ki jo je treba prevesti.

- **Data.controlBackgroundColor** – barva ozadja kontrolnika Officeove teme.

- **Data.controlForegroundColor** – barva ospredja kontrolnika Officeove teme.

- **Data.correlationId** – enolični identifikator zahteve, poslane v storitev.

- **Data.crossSessionId** – enolični identifikator uporabnika.

- **Data.crossSessionStartTime** – časovni žig UTC, ko se je seja prevajanja začela.

- **Data.currentTime** – časovni žig UTC, ko je bilo poslano to sporočilo telemetrije.

- **Data.displayLanguage** – jezik prikaza sistema Office.

- **Data.documentSourceLang** – jezik vsebine dokumenta.

- **Data.documentTargetLang** – jezik, v katerega bo preveden dokument.

- **Data.environment** – okolje storitve, kamor je poslana zahteva.

- **Data.errorMessage** – sporočilo o napaki, ki ga je poslala storitev.

- **Data.eventActionType** – vrsta dogodka telemetrije.

- **Data.eventTagId"** – enolični identifikator vrstice kode, ki je ustvarila to sporočilo telemetrije.

- **Data.flights** – omogočene pilotne različice.

- **Data.fileSize** – velikost Wordove datoteke, ki jo je treba prevesti.

- **Data.fileSource** – mesto, kjer gostuje Wordova datoteka (ni v spletu, v spletu).

- **Data.fileType** – pripona Wordove datoteke.

- **Data.innerHeight** – višina vsebnika stranskega podokna.

- **Data.innerWidth** – širina vsebnika stranskega podokna.

- **Data.lookupSourceLang** – ni uporabljeno za prevajanje dokumenta.

- **Data.lookupTargetLang** – ni uporabljeno za prevajanje dokumenta.

- **Data.officeHost** – Officeova aplikacija, ki gosti stransko podokno.

- **Data.officeLocale** – uporabniški jezik sistema Office.

- **Data.officeMachineId** – enolični identifikator naprave.

- **Data.officePlatform** – platforma naprave.

- **Data.officeSessionId** – identifikator seje za Office.

- **Data.officeUserId** – uporabniški enolični identifikator za Office.

- **Data.officeVersion** – različica Officea.

- **Data.pageXOffset** – položaj vodoravnega drsnika stranskega podokna na levi strani podokna.

- **Data.pageYOffset** – položaj navpičnega drsnika stranskega podokna v zgornjem delu podokna.

- **Data.pixelDepth** – ločljivost barve zaslona.

- **Data.responseCode** – koda odziva storitve na zahtevo.

- **Data.responseTime** – pretečeni čas odziva na zahtevo. 

- **Data.resultType** – rezultat zahteve.

- **Data.screenHeight** – višina zaslona v slikovnih pikah.

- **Data.screenLeft** – vodoravna koordinata okna glede na zaslon.

- **Data.screenTop** – navpična koordinata okna glede na zaslon.

- **Data.screenWidth** – širina zaslona v slikovnih pikah.

- **Data.selectedTab** – vrsta izbranega zavihka (»Izbor« ali »Dokument«).

- **Data.serverUrl** – URL storitve prevajanja.

- **Data.sessionId** – identifikator seje stranskega podokna.

- **Data.sessionStartTime** – časovni žig UTC, ko se je seja prevajanja začela.

- **Data.sourceTextHash** – zgoščena vrednost besedila, ki ga je treba prevesti.

- **Data.sourceTextLength** dolžina besedila, ki ga je treba prevesti.

- **Data.sourceTextWords** – število besed v besedilu, ki ga je treba prevesti.

- **Data.warningMessage** – opozorilno sporočilo, ki ga pošlje storitev.


#### <a name="officetranslatortexttranslated"></a>Office.Translator.TextTranslated

Zbira podatke o uspešnem oz. neuspešnem prevajanju izbora, ki ga zažene dejanje uporabnika v orodju Translator SDX. Ti podatki so ključni za ocenjevanje ustreznosti stanja funkcije prevajanja in odzivanje na morebitne izpade delovanja. S tem dogodkom spremljamo scenarij »Prevajanje izbora« v Excelu, PowerPointu in Wordu.

Zbrana so sledeča polja:

- **Data.actionSource** – kako je bil sprožen izbor prevajanja.

- **Data.bodyBackgroundColor** – barva ozadja vsebnika Officeove teme.

- **Data.bodyForegroundColor** – barva ospredja vsebnika Officeove teme.

- **Data.browserLang** – trenutni jezik prikaza brskalnika.

- **Data.browserOnline** – zastarelo.

- **Data.browserPlatform** – platforma brskalnika.

- **Data.browserUserAgent** – uporabnikov posrednik v brskalniku.

- **Data.colorDepth** – barvna globina sistema.

- **Data.contentLanguage** – zaznani jezik vsebine, ki jo je treba prevesti.

- **Data.controlBackgroundColor** – barva ozadja kontrolnika Officeove teme.

- **Data.controlForegroundColor** – barva ospredja kontrolnika Officeove teme.

- **Data.correlationId** – enolični identifikator zahteve, poslane v storitev.

- **Data.crossSessionId** – enolični identifikator uporabnika.

- **Data.crossSessionStartTime** – časovni žig UTC, ko se je seja prevajanja začela.

- **Data.currentTime** – časovni žig UTC, ko je bilo poslano to sporočilo telemetrije.

- **Data.displayLanguage** – jezik prikaza sistema Office.

- **Data.documentSourceLang** – ni uporabljeno za izbor.

- **Data.documentTargetLang** – ni uporabljeno za izbor prevajanja.

- **Data.environment** – okolje storitve, kamor je poslana zahteva.

- **Data.errorMessage** – sporočilo o napaki, ki ga je poslala storitev.

- **Data.eventActionType** – vrsta dogodka telemetrije.

- **Data.eventTagId"** – enolični identifikator vrstice kode, ki je ustvarila to sporočilo telemetrije

- **Data.flights** – omogočene pilotne različice.

- **Data.innerHeight** – višina vsebnika stranskega podokna

- **Data.innerWidth** – širina vsebnika stranskega podokna

- **Data.lookupSourceLang** – jezik trenutno izbranega besedila.

- **Data.lookupTargetLang** – jezik, v katerega bo prevedeno trenutno izbrano besedilo.

- **Data.officeHost** – Officeova aplikacija, ki gosti stransko podokno.

- **Data.officeLocale** – uporabniški jezik sistema Office.

- **Data.officeMachineId** – enolični identifikator naprave.

- **Data.officePlatform** – platforma naprave.

- **Data.officeSessionId** – identifikator seje za Office.

- **Data.officeUserId** – uporabniški enolični identifikator za Office.

- **Data.officeVersion** – različica Officea.

- **Data.pageXOffset** – položaj vodoravnega drsnika stranskega podokna na levi strani podokna.

- **Data.pageYOffset** – položaj navpičnega drsnika stranskega podokna v zgornjem delu podokna.

- **Data.pixelDepth** – ločljivost barve zaslona.

- **Data.responseCode** – koda odziva storitve na zahtevo.

- **Data.responseTime** – pretečeni čas odziva na zahtevo.

- **Data.resultType** – rezultat zahteve.

- **Data.screenHeight** – višina zaslona v slikovnih pikah.

- **Data.screenLeft** – vodoravna koordinata okna glede na zaslon.

- **Data.screenTop** – navpična koordinata okna glede na zaslon.

- **Data.screenWidth** – širina zaslona v slikovnih pikah.

- **Data.selectedTab** – vrsta izbranega zavihka (»Izbor« ali »Dokument«).

- **Data.serverUrl** – URL storitve prevajanja.

- **Data.sessionId** – identifikator seje stranskega podokna.

- **Data.sessionStartTime** – časovni žig UTC, ko se je seja prevajanja začela.

- **Data.sourceTextHash** – zgoščena vrednost besedila, ki ga je treba prevesti.

- **Data.sourceTextLength** dolžina besedila, ki ga je treba prevesti.

- **Data.sourceTextWords** – število besed v besedilu, ki ga je treba prevesti.

- **Data.warningMessage** – opozorilno sporočilo, ki ga pošlje storitev.


#### <a name="officevisiosharedfeatureexperimentation"></a>Office.Visio.Shared.FeatureExperimentation

Sledi premike funkcij za uporabnike. S tem dogodkom lahko določimo uspešnost ali neuspešnost premikov funkcij.

Zbrana so sledeča polja:

  - **Data\_Enable:bool** – vrednost true ponazarja, da je funkcija omogočena za trenutnega uporabnika

  - **Data\_Feature:string** – ime funkcije

  - **Data\_Flighted:bool** – vrednost true ponazarja, da je funkcija omogočena

  - **Data\_Licensed:bool** – vrednost true ponazarja, da sistem preverja licenco za to funkcijo

  - **Data\_Subscriber:bool** – vrednost true ponazarja, da ima uporabnik licenco za naročnino

#### <a name="officevisiosharedrefreshsmartdiagram"></a>Office.Visio.Shared.RefreshSmartDiagram

Zajame vrednosti osveževanje diagrama, če je datoteka ustvarjena z vmesnikom DV. Na ta način lažje odpravljamo napake in težave pri osveževanju podatkov v diagramu DV.

Zbrana so sledeča polja:

  - **Data\_ConnectorsBasedOnSequence:bool** – ima vrednost true, če je bil osveženi diagram prvotno ustvarjen s povezovalnikom na osnovi zaporedja

  - **Data\_DialogError**:**string** – napaka med osveževanjem pametnega diagrama

  - **Data\_FileError:string** – niz napake, če povezana Excelova datoteka ni veljavna

  - **Data\_OverwriteSelected**:**bool** – ima vrednost true, če je uporabnik med osveževanjem izbral možnost za prepisovanje diagrama

  - **Data\_WarningShown**:**bool** – ima vrednost true, če je uporabnik med postopkom osveževanja podatkov prejel opozorilo

#### <a name="officevisiosharedwritebacktoexcel"></a>Office.Visio.Shared.WritebackToExcel

Zajame vrednosti napak pri pisanju nazaj v Excelu, če je datoteka ustvarjena z vmesnikom DV. Na ta način lažje odpravljamo napake in težave pri pisanju podatkov nazaj v Excel v diagramu DV.

Zbrana so sledeča polja:

  - **Data\_ConnectorsBasedOnSequence:bool** – vrednost true pomeni, da so povezovalniki ustvarjeni glede na nastavitve zaporedja

  - **Data\_DataSourceType:string** – to polje ponazarja, ali je bil diagram ustvarjen iz možnosti »Tabela« oz. »ObsegPoMeri«

  - **Data\_DialogError:string** – vrsta napake po meri med ustvarjanjem pametnega diagrama v Excelu

  - **Data\_NoOfShapesAdded:int** – število oblik, ki so bile dodane med postopkom pisanja nazaj v Excelove funkcije

  - **Data\_NoOfShapesDeleted:int** – število oblik, ki so bile izbrisane med postopkom pisanja nazaj v Excelove funkcije

  - **Data\_OverwriteSelected:bool** – ima vrednost true, če je uporabnik izbral možnost prepisovanja podatkov

  - **Data\_SourceDataModified:bool** – vrednost true ponazarja, da so bili izvorni podatki spremenjeni

  - **Data\_WarningShown:bool** – vrednost true ponazarja, da je uporabnik prejel opozorilo o posodobitvi podatkov

  - **Data\_WarningShownBecauseOfPresenceOfFormula:bool** – vrednost true ponazarja, da je uporabnik prejel opozorilo zaradi formule v Excelu

  - **Data\_WarningShownToAddNextStepID:bool** – vrednost true ponazarja, da je uporabnik prejel opozorilo, saj v Excelu ni prisoten identifikator naslednjega koraka

  - **Data\_WarningShownToConvertToTable:bool** – vrednost true ponazarja, da je uporabnik prejel opozorilo, naj Excelove podatke pretvori v obliko zapisa za tabele


#### <a name="officewordexperimentationdocumentstatsoncloseandsuspend"></a>Office.Word.Experimentation.DocumentStatsOnCloseAndSuspend

Ta dogodke zabeleži statistiko posameznih dokumentov, ko je Office Word zaprt ali začasno prekinjen.  S tem dogodkom prepoznamo morebitno soodvisnost elementov urejanja dokumentov, velikosti dokumentov in drugega z napakami, ki se pojavijo pri shranjevanju in skupni rabi dokumentov ter sodelovanju pri urejanju dokumentov v spletu.

Zbrana so naslednja polja:

- **Data_BkmkRefCount** – število sklicev zaznamkov v dokumentu.

- **Data_CharacterCount** – število znakov v dokumentu.

- **Data_CharactersWithSpaceCount** – število znakov in presledkov v dokumentu.

- **Data_ChartCount** – število grafikonov v dokumentu.

- **Data_CitationCount** – število citatov v dokumentu.

- **Data_DocumentLocation** – označuje, v kateri storitvi je na voljo dokument (OneDrive, File Server, SharePoint itd.).

- **Data_ETW_TrackbackTag** – določa mesto v kodi, kjer je bil ta dogodek sprožen (zapiranje ali začasna prekinitev).

- **Data_EndnoteDocCount** – število končnih opomb v dokumentu.

- **Data_FootnoteDocCount** – število sprotnih opomb v dokumentu.

- **Data_HasBibliography** – označuje, ali dokument vsebuje bibliografijo.

- **Data_HasHeader** – označuje, ali dokument vsebuje glavo.

- **Data_IsImeUsed** – označuje, ali je bil v dokumentu uporabljen urejevalnik vnosne metode.

- **Data_IsPageCountInProgress** – označuje, ali se v dokumentu trenutno izvaja štetje strani.
    
- **Data_IsTouchUsed** – označuje, ali je bil v dokumentu uporabljen vnos na dotik.

- **Data_IsTrackChangesOn** – označuje, ali je bil za dokument vklopljen način sledenja spremembam.

- **Data_LineCount** – število vrstic v dokumentu.

- **Data_MainPdod** – identifikator dokumenta v postopku programa Office Word.

- **Data_PageCount** – število strani v dokumentu.

- **Data_PageNumberFieldCount** – število polj za številko strani v dokumentu.

- **Data_ParagraphCount** – število odstavkov v dokumentu.

- **Data_PicCount** – število slik v dokumentu.

- **Data_RsidCount** – število identifikatorjev shranjenih revizij v dokumentu.

- **Data_TocCount** – število kazal vsebine v dokumentu.

- **Data_UrlHash** – enostranska zgoščena vrednost za ustvarjanje naivnega identifikatorja dokumenta.

- **Data_UserActionID** – to podatkovno polje ni uporabljeno (vrednost je vedno 0).

- **Data_UserActionName** – vedno »DocumentStatsOnCloseAndSuspend«

- **Data_UserInteractionTimeMsec** – število milisekund aktivne interakcije uporabnika z dokumentom.
    
- **Data_WordCount** – število besed v dokumentu.

#### <a name="officewordfilenewcreatenewfile"></a>Office.Word.FileNew.CreateNewFile

Ta dogodek označuje, da je bil ustvarjen nov dokument v Office Wordu, in spremlja, ali je bil postopek uspešen oz. neuspešen. S tem dogodkom spremljamo ustreznost ustvarjanja novega dokumenta. Ta dogodek uporabljamo tudi za ocenjevanje števila mesečnih aktivnih uporabnikov/naprav in za metriko zanesljivosti v oblaku.

Zbrana so ta polja:

  - **Data\_DirtyState** – Ali je bil dokument ustvarjen v nečistem stanju (s spremembami, ki jih je treba shraniti).

  - **Data\_ErrorID** – Identifikator napake v primeru napake postopka.

  - **Data\_MainPdod** – Identifikator dokumenta med sejo tega postopka.

  - **Data\_UsesCustomTemplate** – Označuje, ali je bil dokument ustvarjen s predlogo po meri.

#### <a name="officewordfileopenuserinitiatedopen"></a>Office.Word.FileOpen.UserInitiatedOpen 

V tem dogodku je navedeno, da je Office Word odprl dokument z zagonom uporabnika namesto na programski način Office Word.  Poleg tega vsebuje kritične podatke o učinkovitosti odpiranja datotek in z vidika uporabnika predstavlja dogodek za zagon aplikacije.  Dogodek nadzira, ali funkcija za odpiranje datoteke deluje pravilno. Prav tako se uporablja za izračunane mesečne aktivne uporabnike/naprave in za metriko zanesljivosti v oblaku. 
 
Zbrana so sledeča polja:

- **Data_AddDocTelemRes** – poroča, ali lahko pravilno dopolnimo druge vrednosti dogodka, povezane s telemetrijo dokumenta. Uporablja se za diagnostiko kakovosti podatkov. 

- **Data_BytesAsynchronous** – število bajtov (stisnjenih), brez katerega je morda mogoče odpreti datoteko, če ga pridobimo, preden uporabnik začne urejati dokument oz. se ga morda odloči shraniti. 

- **Data_BytesAsynchronousWithWork** – število bajtov (stisnjenih), brez katerega morda lahko odpremo datoteko, vendar bi zato morali občutno spremeniti kodo. 

- **Data_BytesSynchronous** – število bajtov (stisnjenih), ki ga moramo pridobiti, preden lahko odpremo datoteko. 

- **Data_BytesUnknown** – število bajtov v delih dokumenta, za katerega menimo, da ga ne bomo našli. 

- **Data.Doc.AccessMode** – dokument je samo za branje/ga je mogoče urejati. 

- **Data_Doc_AssistedReadingReasons** – nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja. 

- **Data_Doc_ChunkingType** – enote, uporabljene za postopno odpiranje dokumenta. 

- **Data_Doc_EdpState** – nastavitev elektronske zaščite podatkov dokumenta. 

- **Data_Doc_Ext** – pripona dokumenta (docx/xlsb/pptx itd.). 

- **Data_Doc_FileFormat** – različica protokola za obliko zapisa datoteke. 

- **Data_Doc_Fqdn** – ime domene za OneDrive ali SharePoint Online. 

- **Data_Doc_FqdnHash** – enostranska zgoščena vrednost imena domene, ki omogoča identifikacijo stranke. 

- **Data_Doc_IdentityTelemetryId** – enostranska zgoščena vrednost identitete uporabnika, uporabljena za odpiranje. 

- **Data_Doc_InitializationScenario** – zabeleži način odpiranja dokumenta. 

- **Data_Doc_IOFlags** – poroča o predpomnjenih zastavicah, uporabljenih za nastavitev možnosti zahtev za odpiranje. 

- **Data_Doc_IrmRights** – dejanja, ki jih je dovolil pravilnik za elektronsko zaščito podatkov, ki velja za dokument/uporabnika. 

- **Data_Doc_IsIncrementalOpen** – zastavica, ki označuje postopno odpiranje dokumenta. 

- **Data_Doc_IsOcsSupported** – zastavica, ki označuje, da je storitev sodelovanja podprta v dokumentu. 

- **Data_Doc_IsOpeningOfflineCopy** – zastavica, ki označuje, da je bila odprta kopija dokumenta brez povezave. 

- **Data_Doc_IsSyncBacked** – zastavica, ki označuje, da v računalniku obstaja samodejno sinhronizirana kopija dokumenta. 

- **Data_Doc_Location** – označuje, v kateri storitvi je dokument na voljo (OneDrive, File Server, SharePoint) 

- **Data_Doc_LocationDetails** – označuje, v kateri znani mapi je na voljo lokalno shranjen dokument 

- **Data_Doc_NumberCoAuthors** – število souporabnikov v seji urejanja s sodelovanjem. 

- **Data_Doc_PasswordFlags** – označuje nastavljene zastavice za branje ali branje/pisanje gesla. 

- **Data_Doc_ReadOnlyReasons** – razlogi, zakaj je bil dokument odprt v načinu »samo za branje«. 

- **Data_Doc_ResourceIdHash** – anonimni identifikator dokumenta za diagnosticiranje težav 

- **Data_Doc_ServerDocId** – nespremenljivi anonimni identifikator dokumenta za diagnosticiranje težav 

- **Data_Doc_ServerProtocol** – različica protokola za komunikacijo s storitvijo 

- **Data_Doc_ServerType** – vrsta strežnika, ki zagotavlja storitev (SharePoint, OneDrive, WOPI itd.). 

- **Data_Doc_ServerVersion** – različica strežnika, ki zagotavlja storitev 

- **Data_Doc_SessionId** – različica strežnika, ki zagotavlja storitev 

- **Data_Doc_SharePointServiceContext** – diagnostične informacije zahtev storitve SharePoint Online. 

- **Data_Doc_SizeInBytes** – indikator velikosti dokumenta. 

- **Data_Doc_SpecialChars** – indikator posebnih znakov v URL-ju ali poti dokumenta. 

- **Data_Doc_StreamAvailability** – indikator, ali je tok dokumenta na voljo/onemogočen. 

- **Data_Doc_SyncBackedType** – indikator vrste dokumenta (lokalno ali storitev). 

- **Data_Doc_UrlHash** – enostranska zgoščena vrednost za ustvarjanje naivnega identifikatorja dokumenta. 

- **Data_Doc_WopiServiceId** – vsebuje enolični identifikator za ponudnika storitve WOPI. 

- **Data_EditorDisablingRename** – identifikator prvega urejevalnika, ki je onemogočil preimenovanje 

- **Data_EditorsCount** – število urednikov v dokumentov 

- **Data_ForceReadWriteReason** – vrednost celega števila, ki predstavlja vzrok za vsiljeni način za branje/pisanje pri datoteki. 

- **Data_FSucceededAfterRecoverableFailure** – označuje, da je bilo odpiranje uspešno po odpravi napake med odpiranjem dokumenta. 

- **Data_LastLoggedTag** – enolična oznaka za mesto klica kode, ki se uporablja za prepoznavanje, ko poskušamo izvesti neuspešno odpiranje dvakrat zapored (uporablja se za diagnostiko kakovosti podatkov). 

- **Data_LinkStyles** – označuje, ali povezujemo sloge predlog. 

- **Data_MainPdod** – identifikator dokumenta v postopku programa Microsoft Office Word. 

- **Data_Measurements** – šifriran niz z razčlenitvijo časa različnih časov odpiranja. Uporablja se za diagnosticiranje uspešnost pri odpiranju 

- **Data_MoveDisabledReason** – napaka, ki onemogoča premik dokumenta. 

- **Data_MoveFlightEnabled** – označuje, ali je omogočena pilotna različica za funkcijo premikanja. 

- **Data_OpenInitiateKind** – vrsta scenarija, v katerem so uporabniki zagnali to operacijo za odpiranje dokumenta. 

- **Data_PartsUnknown** – število delov dokumenta, za katere nismo uspeli pridobiti podatkov 

- **Data_RecoverableFailureInitiationLocationTag** – enolična oznaka za mesto klica kode, ki se uporablja za prepoznavanje mesta v kodi, kjer poskušamo odpraviti napako pred odpiranjem datoteke. 

- **Data_RenameDisabledReason** – napaka, ki povzroča, da je funkcija preimenovanja za ta dokument onemogočena. 

- **Data_RenameFlightEnabled** – označuje, ali je omogočena pilotna različica za funkcijo preimenovanja. 

- **Data_SecondaryTag** – enolična oznaka za mesto klica kode, ki se uporablja za dodajanje dodatnih podatkov o neuspehih pri odpiranju. 

- **Data_TemplateFormat** – oblika zapisa datoteke za predlogo, na kateri temelji dokument. 

- **Data_UsesNormal** – označuje, ali odprti dokument temelji na navadni predlogi. 

- **Data_VerboseMeasurements** – šifriran niz z razčlenitvijo časa različnih časov odpiranja.  Uporablja se za merjenje učinkovitosti delovanja, ki je omogočena le za interne obroče. 



#### <a name="officewordfilesaveactcmdgosubsaveas"></a>Office.Word.FileSave.ActCmdGosubSaveAs

Ta dogodek označuje, da uporabnik shranjuje spremembe v nov dokument. Dogodek nadzira ustreznost delovanja shranjevanja v nov dokument. Ta dogodek uporabljamo tudi za ocenjevanje števila mesečnih aktivnih uporabnikov/naprav in za metriko zanesljivosti v oblaku.

Zbrana so sledeča polja:

- **Data_AddDocTelemRes** – poroča, ali lahko pravilno dopolnimo druge vrednosti dogodka, povezane s telemetrijo dokumenta. Uporablja se za diagnostiko kakovosti podatkov.

- **Data_DetachedDuration** – koliko časa je bila dejavnost ločena od niti.

- **Data.Doc.AccessMode** – dokument je samo za branje/ga je mogoče urejati.

- **Data_Doc_AssistedReadingReasons** – nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

- **Data_Doc_AsyncOpenKind – ** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

- **Data_Doc_ChunkingType** – enote, uporabljene za postopno odpiranje dokumenta.

- **Data_Doc_EdpState** – nastavitev elektronske zaščite podatkov dokumenta.

- **Data_Doc_Ext** – pripona dokumenta (docx/xlsb/pptx itd.).

- **Data_Doc_FileFormat** – različica protokola za obliko zapisa datoteke.

- **Data_Doc_Fqdn** – ime domene za OneDrive ali SharePoint Online.

- **Data_Doc_FqdnHash** – enostranska zgoščena vrednost imena domene, ki omogoča identifikacijo stranke.

- **Data_Doc_IdentityTelemetryId** – enostranska zgoščena vrednost identitete uporabnika, uporabljena za odpiranje.

- **Data_Doc_InitializationScenario** – zabeleži način odpiranja dokumenta.

- **Data_Doc_IOFlags** – poroča o predpomnjenih zastavicah, uporabljenih za nastavitev možnosti zahtev za odpiranje.

- **Data_Doc_IrmRights** – dejanja, ki jih je dovolil pravilnik za elektronsko zaščito podatkov, ki velja za dokument/uporabnika.
    
- **Data_Doc_IsIncrementalOpen** – zastavica, ki označuje postopno odpiranje dokumenta.

- **Data_Doc_IsOcsSupported** – zastavica, ki označuje, da je storitev sodelovanja podprta v dokumentu.
    
- **Data_Doc_IsOpeningOfflineCopy** – zastavica, ki označuje, da je bila odprta kopija dokumenta brez povezave.

- **Data_Doc_IsSyncBacked** – zastavica, ki označuje, da v računalniku obstaja samodejno sinhronizirana kopija dokumenta.

- **Data_Doc_Location** – označuje, v kateri storitvi je dokument na voljo (OneDrive, File Server, SharePoint itd.).

- **Data_Doc_LocationDetails** – označuje, v kateri znani mapi je na voljo lokalno shranjen dokument.

- **Data_Doc_NumberCoAuthors** – število souporabnikov v seji urejanja s sodelovanjem.

- **Data_Doc_PasswordFlags** – označuje nastavljene zastavice za branje ali branje/pisanje gesla.

- **Data_Doc_ReadOnlyReasons** – razlogi, zakaj je bil dokument odprt v načinu »samo za branje«.

- **Data_Doc_ResourceIdHash** – anonimni identifikator dokumenta za diagnosticiranje težav.

- **Data_Doc_RtcType** – označuje, kako je bil kanal v realnem času (RTC) nastavljen za trenutno datoteko (onemogočeno, nepodprto, na zahtevo, vedno vklopljeno itn.).

- **Data_Doc_ServerDocId** – nespremenljivi anonimni identifikator dokumenta za diagnosticiranje težav.

- **Data_Doc_ServerProtocol** – različica protokola za komunikacijo s storitvijo.

- **Data_Doc_ServerType** – vrsta strežnika, ki zagotavlja storitev (SharePoint, OneDrive, WOPI itd.).

- **Data_Doc_ServerVersion** – različica strežnika, ki zagotavlja storitev.

- **Data_Doc_SessionId** – prepozna specifično sejo za urejanje dokumenta v celotni seji.

- **Data_Doc_SharePointServiceContext** – diagnostične informacije zahtev storitve SharePoint Online.

- **Data_Doc_SizeInBytes** – indikator velikosti dokumenta.

- **Data_Doc_SpecialChars** – indikator posebnih znakov v URL-ju ali poti dokumenta.

- **Data_Doc_StreamAvailability** – indikator, ali je tok dokumenta na voljo/onemogočen.

- **Data_Doc_SyncBackedType** – indikator vrste dokumenta (lokalno ali storitev).

- **Data_Doc_UrlHash** – enostranska zgoščena vrednost za ustvarjanje naivnega identifikatorja dokumenta.

- **Data_EditorDisablingRename** – identifikator prvega urejevalnika, ki je onemogočil preimenovanje.

- **Data_EditorsCount** – število urednikov v dokumentov

- **Data_LastLoggedTag** – enolična oznaka za mesto klica kode, ki se uporablja za prepoznavanje, ko poskušamo dvakrat zapored neuspešno izvesti shranjevanje (se uporablja za diagnostiko kakovosti podatkov)

- **Data_MoveDisabledReason** – napaka, ki onemogoča premik dokumenta.

- **Data_MoveFlightEnabled** – označuje, ali je omogočena pilotna različica za funkcijo premikanja.

- **Data_RenameDisabledReason** – napaka, zaradi katere je funkcija preimenovanja za dokument onemogočena.

- **Data_RenameFlightEnabled** – označuje, ali je omogočena pilotna različica za funkcijo preimenovanja.

    
#### <a name="officewordfilesaveactfconfirmsavedoccoreautorecoverysave"></a>Office.Word.FileSave.ActFConfirmSaveDocCoreAutoRecoverySave

Ta dogodek označuje, da je Office Word shranil samodejno obnovljen dokument, ki še ni bil shranjen. S tem dogodkom Microsoft zazna napake v funkciji samodejne obnovitve, ki so pomembne zagotavljanje varnosti podatkov v dokumentih.  Dogodek nadzira ustreznost delovanja funkcije shranjevanja samodejno obnovljenih dokumentov.  Ta dogodek uporabljamo tudi za ocenjevanje števila mesečnih aktivnih uporabnikov/naprav in za metriko zanesljivosti v oblaku.

Zbrana so sledeča polja:

- **Data_DetachedDuration** – koliko časa je bila dejavnost ločena od niti.

- **Data.Doc.AccessMode** – dokument je samo za branje/ga je mogoče urejati.

- **Data_Doc_AssistedReadingReasons** – nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

- **Data_Doc_AsyncOpenKind – ** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.
    
- **Data_Doc_ChunkingType** – enote, uporabljene za postopno odpiranje dokumenta.

- **Data_Doc_EdpState** – nastavitev elektronske zaščite podatkov dokumenta.

- **Data_Doc_Ext** – pripona dokumenta (docx/xlsb/pptx itd.).

- **Data_Doc_FileFormat** – različica protokola za obliko zapisa datoteke.

- **Data_Doc_Fqdn** – ime domene za OneDrive ali SharePoint Online.

- **Data_Doc_FqdnHash** – enostranska zgoščena vrednost imena domene, ki omogoča identifikacijo stranke.

- **Data_Doc_IdentityTelemetryId** – enostranska zgoščena vrednost identitete uporabnika, uporabljena za odpiranje.

- **Data_Doc_InitializationScenario** – zabeleži način odpiranja dokumenta.

- **Data_Doc_IOFlags** – poroča o predpomnjenih zastavicah, uporabljenih za nastavitev možnosti zahtev za odpiranje.

- **Data_Doc_IrmRights** – dejanja, ki jih je dovolil pravilnik za elektronsko zaščito podatkov, ki velja za dokument/uporabnika.

- **Data_Doc_IsIncrementalOpen** – zastavica, ki označuje postopno odpiranje dokumenta.

- **Data_Doc_IsOcsSupported** – zastavica, ki označuje, da je storitev sodelovanja podprta v dokumentu.
    
- **Data_Doc_IsOpeningOfflineCopy** – zastavica, ki označuje, da je bila odprta kopija dokumenta brez povezave.

- **Data_Doc_IsSyncBacked** – zastavica, ki označuje, da v računalniku obstaja samodejno sinhronizirana kopija dokumenta.

- **Data_Doc_Location** – označuje, v kateri storitvi je dokument na voljo (OneDrive, File Server, SharePoint itd.).

- **Data_Doc_LocationDetails** – označuje, v kateri znani mapi je na voljo lokalno shranjen dokument.

- **Data_Doc_NumberCoAuthors** – število souporabnikov v seji urejanja s sodelovanjem.

- **Data_Doc_PasswordFlags** – označuje nastavljene zastavice za branje ali branje/pisanje gesla.

- **Data_Doc_ReadOnlyReasons** – razlogi, zakaj je bil dokument odprt v načinu »samo za branje«.

- **Data_Doc_ResourceIdHash** – anonimni identifikator dokumenta za diagnosticiranje težav.

- **Data_Doc_RtcType** – označuje, kako je bil kanal v realnem času (RTC) nastavljen za trenutno datoteko (onemogočeno, nepodprto, na zahtevo, vedno vklopljeno itn.).

- **Data_Doc_ServerDocId** – nespremenljivi anonimni identifikator dokumenta za diagnosticiranje težav.

- **Data_Doc_ServerProtocol** – različica protokola za komunikacijo s storitvijo

- **Data_Doc_ServerType** – vrsta strežnika, ki zagotavlja storitev (SharePoint, OneDrive, WOPI itd.).

- **Data_Doc_ServerVersion** – različica strežnika, ki zagotavlja storitev

- **Data_Doc_SessionId** – prepozna specifično sejo za urejanje dokumenta v celotni seji.

- **Data_Doc_SharePointServiceContext** – diagnostične informacije zahtev storitve SharePoint Online.

- **Data_Doc_SizeInBytes** – indikator velikosti dokumenta.

- **Data_Doc_SpecialChars** – indikator posebnih znakov v URL-ju ali poti dokumenta.

- **Data_Doc_StreamAvailability** – indikator, ali je tok dokumenta na voljo/onemogočen.

- **Data_Doc_SyncBackedType** – indikator vrste dokumenta (lokalno ali storitev).

- **Data_Doc_UrlHash** – enostranska zgoščena vrednost za ustvarjanje naivnega identifikatorja dokumenta.

- **Data_Doc_WopiServiceId** – vsebuje enolični identifikator za ponudnika storitve WOPI.

- **Data_FailureClass** – celo število, ki predstavlja razred napake pri neuspešnih prehodih Officeovih storitev za sodelovanje (OCS).
    
- **Data_MainPdod** – identifikator dokumenta v postopku programa Office Word.

- **Data_MoveFlightEnabled** – označuje, ali je omogočena pilotna različica za funkcijo premikanja.

- **Data_OCSSyncbackSaveStarted** – zastavica, ki označuje, da je ta postopek shranjevanja povezan s funkcijo shranjevanja s povratno sinhronizacijo.

- **Data_RenameDisabledReason** – napaka, ki povzroča, da je funkcija preimenovanja za ta dokument onemogočena.

- **Data_RenameFlightEnabled** – označuje, ali je omogočena pilotna različica za funkcijo preimenovanja.

- **Data_SaveInitiateKind** – celo število, ki označuje način inicializacije shranjevanja.

- **Data_SrcDocIsUnnamedOrNew** – označuje, ali je dokument, ki ga želite shraniti, nov dokument.


#### <a name="officewordfilesaveactfconfirmsavedoccorequerysave"></a>Office.Word.FileSave.ActFConfirmSaveDocCoreQuerySave

Ta dogodek označuje, da Office Word pozove uporabnika k shranjevanju sprememb, ko ta poskuša zapreti dokument. Z njim Microsoft nadzira ustreznost delovanja funkcije shranjevanja dokumenta ob zapiranju ter tako prepreči morebitno izgubo podatkov v dokumentih. Dogodek nadzira, ali način shranjevanja ob zapiranju ustrezno deluje. Ta dogodek uporabljamo tudi za ocenjevanje števila mesečnih aktivnih uporabnikov/naprav in za metriko zanesljivosti v oblaku.

Zbrana so sledeča polja:

- **Data_AddDocTelemRes** – poroča, ali lahko pravilno dopolnimo druge vrednosti dogodka, povezane s telemetrijo dokumenta. Uporablja se za diagnostiko kakovosti podatkov.

- **Data_DetachedDuration** – koliko časa je bila dejavnost ločena od niti.

- **Data.Doc.AccessMode** – dokument je samo za branje/ga je mogoče urejati.

- **Data_Doc_AssistedReadingReasons** – nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

- **Data_Doc_AsyncOpenKind – ** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

- **Data_Doc_ChunkingType** – enote, uporabljene za postopno odpiranje dokumenta.

- **Data_Doc_EdpState** – nastavitev elektronske zaščite podatkov dokumenta.

- **Data_Doc_Ext** – pripona dokumenta (docx/xlsb/pptx itd.).

- **Data_Doc_FileFormat** – različica protokola za obliko zapisa datoteke.

- **Data_Doc_Fqdn** – ime domene za OneDrive ali SharePoint Online.

- **Data_Doc_FqdnHash** – enostranska zgoščena vrednost imena domene, ki omogoča identifikacijo stranke.

- **Data_Doc_IdentityTelemetryId** – enostranska zgoščena vrednost identitete uporabnika, uporabljena za odpiranje.

- **Data_Doc_InitializationScenario** – zabeleži način odpiranja dokumenta.

- **Data_Doc_IOFlags** – poroča o predpomnjenih zastavicah, uporabljenih za nastavitev možnosti zahtev za odpiranje.

- **Data_Doc_IrmRights** – dejanja, ki jih je dovolil pravilnik za elektronsko zaščito podatkov, ki velja za dokument/uporabnika.

- **Data_Doc_IsIncrementalOpen** – zastavica, ki označuje postopno odpiranje dokumenta.

- **Data_Doc_IsOcsSupported** – zastavica, ki označuje, da je storitev sodelovanja podprta v dokumentu.
    
- **Data_Doc_IsOpeningOfflineCopy** – zastavica, ki označuje, da je bila odprta kopija dokumenta brez povezave.

- **Data_Doc_IsSyncBacked** – zastavica, ki označuje, da v računalniku obstaja samodejno sinhronizirana kopija dokumenta.

- **Data_Doc_Location** – označuje, v kateri storitvi je dokument na voljo (OneDrive, File Server, SharePoint itd.).

- **Data_Doc_LocationDetails** – označuje, v kateri znani mapi je na voljo lokalno shranjen dokument.

- **Data_Doc_NumberCoAuthors** – število souporabnikov v seji urejanja s sodelovanjem.

- **Data_Doc_PasswordFlags** – označuje nastavljene zastavice za branje ali branje/pisanje gesla.

- **Data_Doc_ReadOnlyReasons** – razlogi, zakaj je bil dokument odprt v načinu »samo za branje«.

- **Data_Doc_ResourceIdHash** – anonimni identifikator dokumenta za diagnosticiranje težav.

- **Data_Doc_RtcType** – označuje, kako je bil kanal v realnem času (RTC) nastavljen za trenutno datoteko (onemogočeno, nepodprto, na zahtevo, vedno vklopljeno itn.).

- **Data_Doc_ServerDocId** – nespremenljivi anonimni identifikator dokumenta za diagnosticiranje težav.

- **Data_Doc_ServerProtocol** – različica protokola za komunikacijo s storitvijo

- **Data_Doc_ServerType** – vrsta strežnika, ki zagotavlja storitev (SharePoint, OneDrive, WOPI itd.).

- **Data_Doc_ServerVersion** – različica strežnika, ki zagotavlja storitev

- **Data_Doc_SessionId** – prepozna specifično sejo za urejanje dokumenta v celotni seji.

- **Data_Doc_SharePointServiceContext** – diagnostične informacije zahtev storitve SharePoint Online.

- **Data_Doc_SizeInBytes** – indikator velikosti dokumenta.

- **Data_Doc_SpecialChars** – indikator posebnih znakov v URL-ju ali poti dokumenta.

- **Data_Doc_StreamAvailability** – indikator, ali je tok dokumenta na voljo/onemogočen.

- **Data_Doc_SyncBackedType** – indikator vrste dokumenta (lokalno ali storitev).

- **Data_Doc_UrlHash** – enostranska zgoščena vrednost za ustvarjanje naivnega identifikatorja dokumenta.

- **Data_Doc_WopiServiceId** – vsebuje enolični identifikator za ponudnika storitve WOPI.

- **Data_DstDoc_AccessMode** – ciljni dokument je samo za branje ali omogoča urejanje.

- **Data_DstDoc_EdpState** – nastavitev elektronske zaščite podatkov za ciljni dokument.

- **Data_DstDoc_Ext** – pripona dokumenta (docx/xlsb/pptx, itd.) za ciljni dokument.

- **Data_DstDoc_FileFormat** – različica protokola za obliko zapisa datoteke za ciljni dokument.

- **Data_DstDoc_Location** – označuje, katera storitev zagotavlja mesto shranjevanja za ciljni dokument (OneDrive, datotečni strežnik, SharePoint itd.)

- **Data_DstDoc_LocationDetails** – označuje, v kateri lokalno znani mapi je shranjen ciljni dokument.

- **Data_DstDoc_SessionId** – prepozna določeno sejo za urejanje dokumenta v celotni seji.

- **Data_DstDoc_UrlHash** – enostranska zgoščena vrednost, s katero je mogoče ustvariti naivni identifikator dokumenta za ciljni dokument.

- **Data_FailureClass** – celo število, ki predstavlja razred napake za napake pri prehodih OCS.

- **Data_LocationPickerSaveStatus** – vrednost celega števila, ki ponazarja dejanje, ki je aktiviralo shranjevanje v pogovornem oknu za shranjevanje ob izhodu.

- **Data_MainPdod** – identifikator dokumenta v postopku programa Office Word.

- **Data_MoveFlightEnabled** – označuje, ali je omogočena pilotna različica za funkcijo premikanja.

- **Data_OCSSyncbackSaveStarted** – zastavica, ki označuje, da je ta postopek shranjevanja povezan s funkcijo shranjevanja s povratno sinhronizacijo. 

- **Data_RenameDisabledReason** – napaka, ki povzroča, da je funkcija preimenovanja za ta dokument onemogočena.

- **Data_RenameFlightEnabled** – označuje, ali je omogočena pilotna različica za funkcijo preimenovanja.

- **Data_SaveInitiateKind** – celo število, ki označuje način inicializacije shranjevanja.

- **Data_SrcDocIsUnnamedOrNew** – označuje, ali je dokument, ki ga želite shraniti, nov dokument.


#### <a name="officewordfilesavesaveassavefile"></a>Office.Word.FileSave.SaveAsSaveFile

Ta dogodek ponazarja, da Microsoft Office Word shranjuje dokument v nov dokument. Microsoftu omogoča, da pri funkciji »Shrani kot« zazna napake, ki so pomembne za preprečevanje izgube podatkov v dokumentih. Dogodek nadzira, ali funkcija »Shrani kot« deluje običajno. Prav tako se uporablja za izračunane mesečne aktivne uporabnike/naprave in za metriko zanesljivosti v oblaku.

Zbrana so sledeča polja:

- **Data_AddDocTelemRes** – poroča, ali lahko pravilno dopolnimo druge vrednosti dogodka, povezane s telemetrijo dokumenta. Uporablja se za diagnostiko kakovosti podatkov.

- **Data_AddDocTelemResDst** – poroča, ali lahko pravilno dopolnimo druge vrednosti dogodka za ciljni dokument, povezane s telemetrijo dokumenta. Uporablja se za diagnostiko kakovosti podatkov.

- **Data_AddDocTelemResSrc** – poroča, ali lahko pravilno dopolnimo druge vrednosti dogodka za izvorni dokument, povezane s telemetrijo dokumenta. Uporablja se za diagnostiko kakovosti podatkov.

- **Data_DetachedDuration** – koliko časa je bila dejavnost ločena od niti.

- **Data.Doc.AccessMode** – dokument je samo za branje/ga je mogoče urejati.

- **Data_Doc_AssistedReadingReasons** – nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

- **Data_Doc_AsyncOpenKind – ** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

- **Data_Doc_ChunkingType** – enote, uporabljene za postopno odpiranje dokumenta.

- **Data_Doc_EdpState** – nastavitev elektronske zaščite podatkov dokumenta.

- **Data_Doc_Ext** – pripona dokumenta (docx/xlsb/pptx itd.).

- **Data_Doc_FileFormat** – različica protokola za obliko zapisa datoteke.

- **Data_Doc_Fqdn** – ime domene za OneDrive ali SharePoint Online.

- **Data_Doc_FqdnHash** – enostranska zgoščena vrednost imena domene, ki omogoča identifikacijo stranke.

- **Data_Doc_IdentityTelemetryId** – enostranska zgoščena vrednost identitete uporabnika, uporabljena za odpiranje.

- **Data_Doc_IOFlags** – poroča o predpomnjenih zastavicah, uporabljenih za nastavitev možnosti zahtev za odpiranje.

- **Data_Doc_IrmRights** – dejanja, ki jih je dovolil pravilnik za elektronsko zaščito podatkov, ki velja za dokument/uporabnika.

- **Data_Doc_IsIncrementalOpen** – zastavica, ki označuje postopno odpiranje dokumenta.

- **Data_Doc_IsOcsSupported** – zastavica, ki označuje, da je storitev sodelovanja podprta v dokumentu.

- **Data_Doc_IsOpeningOfflineCopy** – zastavica, ki označuje, da je bila odprta kopija dokumenta brez povezave.

- **Data_Doc_IsSyncBacked** – zastavica, ki označuje, da v računalniku obstaja samodejno sinhronizirana kopija dokumenta.

- **Data_Doc_Location** – označuje, v kateri storitvi je dokument na voljo (OneDrive, File Server, SharePoint itd.).

- **Data_Doc_LocationDetails** – označuje, v kateri znani mapi je na voljo lokalno shranjen dokument.

- **Data_Doc_NumberCoAuthors** – število souporabnikov v seji urejanja s sodelovanjem.

- **Data_Doc_ReadOnlyReasons** – razlogi, zakaj je bil dokument odprt v načinu »samo za branje«.

- **Data_Doc_ResourceIdHash** – anonimni identifikator dokumenta za diagnosticiranje težav.

- **Data_Doc_RtcType** – označuje, kako je bil kanal v realnem času (RTC) nastavljen za trenutno datoteko (onemogočeno, nepodprto, na zahtevo, vedno vklopljeno itn.).

- **Data_Doc_ServerDocId** – nespremenljivi anonimni identifikator dokumenta za diagnosticiranje težav.

- **Data_Doc_ServerProtocol** – različica protokola za komunikacijo s storitvijo

- **Data_Doc_ServerType** – vrsta strežnika, ki zagotavlja storitev (SharePoint, OneDrive, WOPI itd.).

- **Data_Doc_ServerVersion** – različica strežnika, ki zagotavlja storitev

- **Data_Doc_SessionId** – prepozna specifično sejo za urejanje dokumenta v celotni seji.

- **Data_Doc_SharePointServiceContext** – diagnostične informacije zahtev storitve SharePoint Online.

- **Data_Doc_SizeInBytes** – indikator velikosti dokumenta.

- **Data_Doc_SpecialChars** – indikator posebnih znakov v URL-ju ali poti dokumenta.

- **Data_Doc_StreamAvailability** – indikator, ali je tok dokumenta na voljo/onemogočen.

- **Data_Doc_UrlHash** – enostranska zgoščena vrednost za ustvarjanje naivnega identifikatorja dokumenta.

- **Data_DstDoc_AccessMode** – ciljni dokument je samo za branje ali omogoča urejanje.

- **Data_DstDoc_AssistedReadingReasons** – nabor vnaprej določenih vrednosti, zakaj je bil ciljni dokument odprt v načinu vodenega branja.

- **Data_DstDoc_AsyncOpenKind – ** označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.
    
- **Data_DstDoc_ChunkingType** – enote, uporabljene za postopno odpiranje dokumenta.

- **Data_DstDoc_EdpState** – nastavitev elektronske zaščite podatkov za ciljni dokument

- **Data_DstDoc_Ext** – pripona dokumenta (docx/xlsb/pptx itd.).

- **Data_DstDoc_FileFormat** – različica protokola za obliko zapisa dokumenta.

- **Data_DstDoc_Fqdn** – ime domene v storitvi OneDrive ali SharePoint Online za ciljni dokument.

- **Data_DstDoc_FqdnHash** – enostranska zgoščena vrednost imena domene za ciljni dokument, ki ga stranka lahko prepozna.

- **Data_DstDoc_IdentityTelemetryId** – enostranska zgoščena vrednost identitete uporabnika, uporabljena za odpiranje.

- **Data_DstDoc_InitializationScenario** – zabeleži način, uporabljen za odpiranje ciljnega dokumenta.

- **Data_DstDoc_IOFlags** – poroča o predpomnjenih zastavicah za nastavitev možnosti odprtih zahtev za ciljni dokument.
    
- **Data_DstDoc_IrmRights** – dejanja, ki jih je dovolil pravilnik za elektronsko zaščito podatkov, ki velja za ciljni dokument/ciljnega uporabnika.

- **Data_DstDoc_IsIncrementalOpen** – zastavica, ki označuje postopno odpiranje dokumenta.

- **Data_DstDoc_IsOcsSupported** – zastavica, ki označuje, da je storitev sodelovanja podprta v dokumentu.

- **Data_DstDoc_IsOpeningOfflineCopy** – zastavica, ki označuje, da je bila odprta kopija dokumenta brez povezave.

- **Data_DstDoc_IsSyncBacked** – zastavica, ki označuje, da v računalniku obstaja samodejno sinhronizirana kopija dokumenta.

- **Data_DstDoc_Location** – označuje, katera storitev zagotavlja mesto shranjevanja za ciljni dokument (OneDrive, datotečni strežnik, SharePoint itd.).

- **Data_DstDoc_LocationDetails** – označuje, v kateri znani mapi je na voljo lokalno shranjen dokument.

- **Data_DstDoc_NumberCoAuthors** – število souporabnikov v seji urejanja s sodelovanjem.

- **Data_DstDoc_PasswordFlags** – označuje nastavljeno zastavico za branje ali branje/pisanje gesla za ciljni dokument.

- **Data_DstDoc_ReadOnlyReasons** – razlogi, zakaj je bil ciljni dokument odprt v načinu »samo za branje«. 

- **Data_DstDoc_ResourceIdHash** – anonimni identifikator dokumenta za diagnosticiranje težav.

- **Data_DstDoc_ServerDocId** – nespremenljivi anonimni identifikator dokumenta za diagnosticiranje težav.

- **Data_DstDoc_ServerProtocol** – različica protokola za komunikacijo s storitvijo.

- **Data_DstDoc_ServerType** – vrsta strežnika, ki zagotavlja storitev (SharePoint, OneDrive, WOPI itd.).
    
- **Data_DstDoc_ServerVersion** – različica strežnika, ki zagotavlja storitev.

- **Data_DstDoc_SessionId** – prepozna določeno sejo za urejanje dokumenta v celotni seji.

- **Data_DstDoc_SharePointServiceContext** – diagnostične informacije zahtev storitve SharePoint Online.

- **Data_DstDoc_SizeInBytes** – indikator velikosti dokumenta.

- **Data_DstDoc_SpecialChars** – indikator posebnih znakov v URL-ju ali poti dokumenta.

- **Data_DstDoc_StreamAvailability** – indikator, ali je tok dokumenta na voljo/onemogočen.

- **Data_DstDoc_SyncBackedType** – indikator vrste dokumenta (lokalno ali storitev).

- **Data_DstDoc_UrlHash** – enostranska zgoščena vrednost, s katero je mogoče ustvariti naivni identifikator dokumenta za ciljni dokument.
    
- **Data_DstDoc_WopiServiceId** – vsebuje enolični identifikator za ponudnika storitve WOPI.

- **Data_FailureClass** – celo število, ki predstavlja razred napake za napake pri prehodih OCS.

- **Data_LocationPickerPropagateToSaveTime,spLapsedMsec** – izmeri čas v milisekundah, ki mora poteči, da se aktivira shranjevanje po pridobivanju rezultata iz izbirnika mesta.

- **Data_LocationPickerSaveStatus** – stanje, ki ga je vrnil izbirnik mesta.

- **Data_MainPdod** – identifikator dokumenta v postopku programa Microsoft Office Word.

- **Data_MoveDisabledReason** – napaka, ki onemogoča premik dokumenta.

- **Data_MoveFlightEnabled** – označuje, ali je omogočena pilotna različica za funkcijo premikanja.

- **Data_RenameDisabledReason** – napaka, ki povzroča, da je funkcija preimenovanja za ta dokument onemogočena.

- **Data_RenameFlightEnabled** – označuje, ali je omogočena pilotna različica za funkcijo preimenovanja.

- **Data_SaveInitiateKind** – celo število, ki označuje način inicializacije shranjevanja.

- **Data_SrcDoc_AccessMode** – izvirni dokument je samo za branje ali omogoča urejanje.

- **Data_SrcDoc_AssistedReadingReasons** – nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

- **Data_SrcDoc_AsyncOpenKind – ** označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

- **Data_SrcDoc_ChunkingType** – enote, uporabljene za postopno odpiranje dokumenta.

- **Data_SrcDoc_EdpState** – nastavitev elektronske zaščite podatkov izvornega dokumenta.

- **Data_SrcDoc_Ext** – pripona dokumenta za izvorni dokument (docx/xlsb/pptx itd.).

- **Data_SrcDoc_FileFormat** – različica protokola za obliko zapisa datoteke za izvorni dokument.

- **Data_SrcDoc_Fqdn** – ime domene v storitvi OneDrive ali SharePoint Online za izvorni dokument.

- **Data_SrcDoc_FqdnHash** – enostranska zgoščena vrednost imena domene za izvorni dokument, ki ga stranka lahko prepozna.

- **Data_SrcDoc_IdentityTelemetryId** – enostranska zgoščena vrednost identitete uporabnika, uporabljena za odpiranje.

- **Data_SrcDoc_InitializationScenario** – zabeleži način odpiranja dokumenta.

- **Data_SrcDoc_IOFlags** – poroča o predpomnjenih zastavicah, uporabljenih za nastavitev možnosti odprtih zahtev.

- **Data_SrcDoc_IrmRights** – dejanja, ki jih je dovolil pravilnik za elektronsko zaščito podatkov, ki velja za dokument/uporabnika

- **Data_SrcDoc_IsIncrementalOpen** – zastavica, ki označuje postopno odpiranje dokumenta.

- **Data_SrcDoc_IsOcsSupported** – zastavica, ki označuje, da je storitev sodelovanja podprta v dokumentu.

- **Data_SrcDoc_IsOpeningOfflineCopy** – zastavica, ki označuje, da je bila odprta kopija dokumenta brez povezave.

- **Data_SrcDoc_IsSyncBacked** – zastavica, ki označuje, da v računalniku obstaja samodejno sinhronizirana kopija dokumenta.
    
- **Data_SrcDoc_Location** – označuje, katera storitev je zagotovila izvorni dokument (OneDrive, datotečni strežnik, SharePoint itd.)

- **Data_SrcDoc_LocationDetails** – označuje, v kateri znani mapi je na voljo lokalno shranjen dokument.

- **Data_SrcDoc_NumberCoAuthors** – število souporabnikov v seji urejanja s sodelovanjem.

- **Data_SrcDoc_PasswordFlags** – označuje nastavljene zastavice za branje ali branje/pisanje gesla.

- **Data_SrcDoc_ReadOnlyReasons** – razlogi, zakaj je bil dokument odprt v načinu »samo za branje«.

- **Data_SrcDoc_ResourceIdHash** – anonimni identifikator dokumenta za diagnosticiranje težav.

- **Data_SrcDoc_ServerDocId** – nespremenljivi anonimni identifikator dokumenta za diagnosticiranje težav.

- **Data_SrcDoc_ServerProtocol**– različica protokola za komunikacijo s storitvijo.

- **Data_SrcDoc_ServerType** – vrsta strežnika, ki zagotavlja storitev (SharePoint, OneDrive, WOPI itd.).

- **Data_SrcDoc_ServerVersion** – različica strežnika, ki zagotavlja storitev.

- **Data_SrcDoc_SessionId** – prepozna specifično sejo za urejanje dokumenta v celotni seji.

- **Data_SrcDoc_SharePointServiceContext** – diagnostične informacije zahtev storitve SharePoint Online.

- **Data_SrcDoc_SizeInBytes** – indikator velikosti dokumenta.

- **Data_SrcDoc_SpecialChars** – indikator posebnih znakov v URL-ju ali poti dokumenta.

- **Data_SrcDoc_StreamAvailability** – indikator, ali je tok dokumenta na voljo/onemogočen.

- **Data_SrcDoc_SyncBackedType** – indikator vrste dokumenta (lokalno ali storitev).

- **Data_SrcDoc_UrlHash** – enostranska zgoščena vrednost za ustvarjanje naivnega identifikatorja dokumenta.

- **Data_SrcDoc_WopiServiceId** – vsebuje enolični identifikator za ponudnika storitve WOPI.

- **Data_SrcDocIsUnnamedOrNew** – označuje, ali je dokument, ki ga želite shraniti, nov dokument.


#### <a name="officewordworddocumentdirtyflagchanged"></a>Office.Word.Word.DocumentDirtyFlagChanged

Ta dogodek ponazarja, da Microsoft Office Word ureja dokument, zaradi česar se je spremenilo notranje stanje dokumenta v »spremenjeno«. Microsoftu omogoča, da ovrednoti stanje funkcij urejenega dokumenta. Dogodek predstavlja interval obveščanja o urejanjih uporabnika. Prav tako se uporablja za izračunane mesečne aktivne uporabnike/naprave.

Zbrana so sledeča polja:

  - **Data\_CollectionTime –** časovni žig dogodka

  - **Data\_DocumentLocation –** vrsta za mesto dokumenta

  - **Data\_DocumentLocationDetails –** podvrsta za mesto dokumenta

  - **Data\_FAlwaysSaveEnabled –** ponazarja, ali je omogočena funkcija »Vedno shrani«

  - **Data\_FirstEditTime –** časovni žig prvega urejanja

  - **Data\_NumberCoAuthors –** število soavtorjev, ki med sejo urejajo dokument

  - **Data\_NumberOfTimesDocumentDirtied –** število urejanj dokumenta

  - **Data\_Pdod –** identifikator dokumenta v postopku programa Microsoft Office Word

  - **Data\_UrlHash –** razpršitev poti dokumenta

  - **Data\_ViewKind –** vrsta Wordovega pogleda


#### <a name="parselicenseop"></a>ParseLicenseOp

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij.  Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede operacija razčlenjevanja dovoljenj. 

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se program izvaja v produkcijskem okolju ali v okolju razvijalcev

- **AppInfo.Name** – ime aplikacije

- **AppInfo.Version** – različica aplikacije

- **iKey** – ID strežnika Logger 

- **RMS.ApplicationScenarioId** – ID scenarija, ki ga je posredovala aplikacija

- **RMS.Duration** – Skupen čas za izvedbo operacije

- **RMS.DurationWithoutExternalOps** – skupni čas minus zunanje operacije, kot je zakasnitev omrežja.

- **RMS.ErrorCode** – koda napake je vrnjena, če izvira iz operacije

- **RMS.HttpCall** – označite, ali je prišlo do operacije HTTP

- **RMS.LicenseFormat** – oblika licence: Xrml ali Json

- **RMS.Result** – uspeh ali neuspeh operacije

- **RMS.ScenarioId** – ID scenarija, ki ga je določil odjemalec storitve za upravljanje pravic

- **RMS.SDKVersion** – različica odjemalca storitve za upravljanje pravic

- **RMS.ServerType** – vrsta strežnika za upravljanje pravic do storitev 

- **RMS.StatusCode** – koda stanja rezultata operacije

- **RMS.VerifyCertChainDuration** – čas trajanja za preverjanje verige certifikata

- **RMS.VerifySignatureDuration** – čas trajanja za preverjanje podpisa

#### <a name="storeop"></a>StoreOp

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij.  Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede operacija shranjevanja dovoljenj storitev za upravljanje pravic. 

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se program izvaja v produkcijskem okolju ali v okolju razvijalcev

- **AppInfo.Name** – ime aplikacije.

- **AppInfo.Version** – različica aplikacije

- **iKey** – ID strežnika za storitev pisanja dnevnika

- **RMS.ApplicationScenarioId** – ID scenarija, ki ga je posredovala aplikacija

- **RMS.ContentId** – ID vsebine v končni uporabniški licenci

- **RMS.Duration** – Skupen čas za izvedbo API priklica

- **RMS.DurationWithoutExternalOps** – skupni čas minus zunanje operacije, kot je zakasnitev omrežja.

- **RMS.ErrorCode** – koda napake je vrnjena, če izvira iz operacije

- **RMS.HttpCall** – označite, ali je prišlo do operacije HTTP

- **RMS.LicenseFormat** – oblika licence: Xrml ali Json

- **RMS.OperationName** – ime operacije

- **RMS.Result** – uspeh ali neuspeh operacije

- **RMS.ScenarioId** – ID scenarija, ki ga je določil odjemalec storitve za upravljanje pravic

- **RMS.SDKVersion** – različica odjemalca storitve za upravljanje pravic

- **RMS.ServerType** – vrsta strežnika za upravljanje pravic do storitev 

- **RMS.StatusCode** – koda stanja rezultata operacije

- **RMS.Url** – URL strežnika za upravljanje pravic do storitev


### <a name="application-status-and-boot-subtype"></a>*Stanje aplikacije in podvrsta zagona*

Določanje, ali je prišlo do specifičnih dogodkov funkcije, kot sta zagon ali zaustavitev, in funkcije, ki se izvaja.

#### <a name="dnslookupop"></a>DnsLookupOp

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij.  Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede operacija iskanja informacij o strežniku DNS. 

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se program izvaja v produkcijskem okolju ali v okolju razvijalcev

- **AppInfo.Name** – ime aplikacije.

- **AppInfo.Version** – različica aplikacije

- **iKey** – ID strežnika za storitev pisanja dnevnika

- **RMS.ApplicationScenarioId** – ID scenarija, ki ga je posredovala aplikacija

- **RMS.Duration** – Skupen čas za izvedbo operacije

- **RMS.DurationWithoutExternalOps** – skupni čas minus zunanje operacije, kot je zakasnitev omrežja.

- **RMS.ErrorCode** – koda napake je vrnjena, če izvira iz operacije

- **RMS.HttpCall** – označite, ali je prišlo do operacije http

- **RMS.LicenseFormat** – oblika licence: Xrml ali Json

- **RMS.NoOfDomainsSearched** – število iskanih domen  

- **RMS.NoOfDomainsSkipped** – število preskočenih domen 

- **RMS.Result** – uspeh ali neuspeh operacije

- **RMS.ScenarioId** – ID scenarija, ki ga je določil odjemalec storitve za upravljanje pravic

- **RMS.SDKVersion** – različica odjemalca storitve za upravljanje pravic

- **RMS.ServerType** – vrsta strežnika za upravljanje pravic do storitev 

- **RMS.StatusCode** – koda stanja rezultata operacije

#### <a name="getuserop"></a>GetUserOp

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij.  Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede operacija pridobivanja uporabniških dovoljenj. 

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se program izvaja v produkcijskem okolju ali v okolju razvijalcev

- **AppInfo.Name** – ime aplikacije

- **AppInfo.Version** – različica aplikacije

- **iKey** – ID strežnika za storitev pisanja dnevnika

- **RMS.ApplicationScenarioId** – ID scenarija, ki ga je posredovala aplikacija

- **RMS.ContentId** – ID vsebine

- **RMS.Duration** – Skupen čas za izvedbo operacije

- **RMS.DurationWithoutExternalOps** – skupni čas minus zunanje operacije, kot je zakasnitev omrežja.

- **RMS.ErrorCode** – koda napake vrnjena iz operacije

- **RMS.HttpCall** – označite, ali je prišlo do operacije HTTP

- **RMS.LicenseFormat** – oblika licence: Xrml ali Json

- **RMS.Result** – uspeh ali neuspeh operacije

- **RMS.ScenarioId** – ID scenarija, ki ga je določil odjemalec storitve za upravljanje pravic

- **RMS.SDKVersion** – različica odjemalca storitve za upravljanje pravic

- **RMS.ServerType** – vrsta strežnika za upravljanje pravic do storitev 

- **RMS.StatusCode** – koda stanja rezultata operacije

- **RMS.Type** – vrsta uporabniških informacij

#### <a name="httpop"></a>HttpOp

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij.  Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede operacija za http zahtevo.

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se program izvaja v produkcijskem okolju ali v okolju razvijalcev
    
- **AppInfo.Name** – ime aplikacije

- **AppInfo.Version** – različica aplikacije

- **iKey** – ID strežnika za storitev pisanja dnevnika

- **RMS.ApplicationScenarioId** – ID scenarija, ki ga je posredovala aplikacija

- **RMS.CallBackStatus** – stanje rezultata povratnega klica za preverjanje pristnosti

- **RMS.CallbackTime** – čas, porabljen za povratni klic za preverjanje pristnosti 

- **RMS.CorrelationId** – ID korelacije zahteve http

- **RMS.DataSize** – velikost podatkov zahteve HTTP

- **RMS.Duration** – Skupen čas za izvedbo operacije

- **RMS.DurationWithoutExternalOps** – skupni čas minus zunanje operacije, kot je zakasnitev omrežja.

- **RMS.ErrorCode** – koda napake je vrnjena, če izvira iz operacije

- **RMS.HttpCall** – označite, ali je prišlo do ugnezdene operacije http 

- **RMS.LicenseFormat** – oblika licence: Xrml ali Json

- **RMS.OperationName** – ime operacije

- **RMS.Result** – uspeh ali neuspeh operacije

- **RMS.ScenarioId** – ID scenarija, ki ga je določil odjemalec storitve za upravljanje pravic

- **RMS.SDKVersion** – različica odjemalca storitve za upravljanje pravic

- **RMS.ServerType** – vrsta strežnika za upravljanje pravic do storitev 

- **RMS.StatusCode** – koda stanja rezultata operacije

- **RMS.Url** – URL strežnika za upravljanje pravic do storitev

- **RMS.WinhttpCallbackStatus** – stanje rezultata povratnega klica winhttp

#### <a name="ipccreateoauth2token"></a>IpcCreateOauth2Token

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij. Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede priklic API IpcCreateOauth2Token API.

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se program izvaja v produkcijskem okolju ali v okolju razvijalcev
    
- **AppInfo.Name** – ime aplikacije.

- **AppInfo.Version** – različica aplikacije

- **iKey** – ID strežnika za storitev pisanja dnevnika

- **RMS.Duration** – Skupen čas za izvedbo API priklica

- **RMS.DurationWithoutExternalOps** – skupni čas minus zunanje operacije, kot je zakasnitev omrežja.

- **RMS.ErrorCode** – koda napake je vrnjena, če katera koli izvira iz priklica API

- **RMS.HttpCall** – označite, ali je prišlo do operacije HTTP

- **RMS.Rezultat** – uspeh ali neuspeh priklica API

- **RMS.ScenarioId** – ID scenarija, ki ga določa API

- **RMS.SDKVersion** – različica odjemalca storitve za upravljanje pravic

- **RMS.StatusCode** – Koda stanja vrnjenega rezultata

#### <a name="officeextensibilityofficejsappactivated"></a>Office.Extensibility.OfficeJS.Appactivated

Zapiše informacije o nepričakovanih zaustavitvah v Officeu. Tako lahko prepoznamo zrušitve ali neodzivanja izdelka in ustrezno ukrepamo.

Zbrana so sledeča polja:

  - **Data\_AirspaceInitTime:integer –** čas, zahtevan za inicializacijo Officeove komponente Airspace

  - **Data\_AllShapes:integer –** število oblik v dokumentu

  - **Data\_APIInitTime:integer –** čas, zahtevan za inicializacijo modula Visio API

  - **Data\_AppSizeHeight –** višina okna za dodatek**-**

  - **Data\_AppSizeWidth –** širina okna za dodatek**-**

  - **Data\_AppURL –** URL prijave; zapiše polni URL za dodatke iz trgovine in domeno URL-ja za dogodke, ki jih niste pridobili iz trgovine

  - **Data_Doc_AsyncOpenKind:long – ** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

  - **Data\_AuthorsCount:integer –** število avtorjev, ki so uredili dokument v tej seji

  - **Data\_BackgroundPages:integer –** število strani v ozadju diagrama

  - **Data\_BootTime:integer –** čas, zahtevan za zagon Visia

  - **Data\_Browser –** niz brskalnika, ki vsebuje informacije o vrsti in različici brskalnika

  - **Data\_ChildWindowMixedModeTime:integer –** čas, zahtevan za omogočanje mešanega načina v Visiu (podrejeno okno ima lahko različno vrednost DpiAwareness kot nadrejeno okno)

  - **Data\_CommentsCount:integer –** število komentarjev v dokumentu

  - **Data\_ConnectionCount:integer –** število podatkovnih povezav v diagramu

  - **Data\_ContentMgrInitTim:integer –** čas, zahtevan za inicializacijo upravitelja vsebine

  - **Data\_CreateMainFrameTime:integer –** čas, zahtevan za ustvarjanje glavnega okvirja

  - **Data\_CreatePaletteTime:integer –** čas, zahtevan za ustvarjanje globalne palete z barvami

  - **Data\_DispFormatCount:integer –** število podatkovnih grafik v diagramu

  - **Data\_Doc\_Ext:string –** pripona dokumenta

  - **Data\_Doc\_Fqdn:string –** mesto, kjer je dokument shranjen (SharePoint.com, live.net); na voljo samo za domene v storitvi Office 365

  - **Data\_Doc\_FqdnHash:string –** razpršitev mesta shrambe dokumenta

  - **Data\_Doc\_IsIncrementalOpen:bool-**: ali je bil dokument odprt postopoma (nova funkcija, ki dokument odpre, brez da prenese celoten dokument)

  - **Data\_Doc\_IsOpeningOfflineCopy:bool –** ali je bil dokument odprt iz lokalnega predpomnilnika?

  - **Data\_Doc\_IsSyncBacked:bool –** ima vrednost true, če gre za dokument strežnika, ki je na voljo lokalno in je sinhroniziran s strežnikom (npr. prek storitve OneDrive ali odjemalskih aplikacij ODB)

  - **Data\_Doc\_Location:long-**: nabor vnaprej določenih vrednosti za mesto shranjevanja dokumenta (lokalno, SharePoint, WOPI, omrežje itd.)

  - **Data\_Doc\_LocationDetails:long –** nabor vnaprej določenih vrednosti podrobnejše lokacije (mapa »Začasno«, mapa »Prenosi«, dokumenti storitve One Drive, slike storitve One Drive)

  - **Data\_Doc\_ResourceIdHash:string –** razpršitev identifikatorja vira za dokumente, shranjene v oblaku

  - **Data_Doc_RtcType – **  označuje, kako je bil kanal v realnem času (RTC) nastavljen za trenutno datoteko (onemogočeno, nepodprto, na zahtevo, vedno vklopljeno itn.).

  - **Data\_Doc\_ServerDocId:string –** nespremenljivi identifikator za dokumente, shranjene v oblaku

  - **Data\_Doc\_SessionId:long –** ustvarjeni GUID, ki prepozna primerek dokumenta v seji istega procesa

  - **Data\_Doc\_SizeInBytes:long –** velikost dokumenta v bajtih

  - **Data\_Doc\_SpecialChars:long –** dolga bitna maska, ki ponazarja posebne znake v URL-ju ali poti dokumenta

  - **Data\_Doc\_SyncBackedType –** indikator vrste dokumenta (lokalno ali storitev) 

  - **Data\_Doc\_UrlHash:string –** razpršitev polnega URL-ja za dokumente, shranjene v oblaku

  - **Data\_DpiAwarenessTime:integer –** čas, zahtevan za omogočanje zaznavanja ločljivosti (dpi) na monitor

  - **Data\_DurationToCompleteInMilliseconds:double –** čas, zahtevan za dokončanje shranjevanja, v milisekundah

  - **Data\_ErrorCode:int -**: 0 za uspešno, celo število za neuspešno shranjevanje

  - **Data\_FailureReason:integer –** razlog za neuspešno asinhrono shranjevanje

  - **Data\_FileExtension –** pripona datoteka odprtega diagrama

  - **Data\_FileHasDGMaster:bool –** ima vrednost true, če datoteka vsebuje podatkovno grafiko

  - **Data\_FileHasImportedData:bool –** ima vrednost true, če datoteka vsebuje uvožene podatke

  - **Data\_FileHasShapesLinked:bool –** ima vrednost true, če datoteka vsebuje oblike, povezane s podatki

  - **Data\_FileIOBytesRead:int –** skupno število bajtov, prebranih med shranjevanjem

  - **Data\_FileIOBytesReadSquared:int –** kvadratna vrednost za Data\_FileIOBytesRead

  - **Data\_FileIOBytesWritten:int –** skupno število bajtov, zapisanih med shranjevanjem

  - **Data\_FileIOBytesWrittenSquared:int –** kvadratna vrednost za Data\_FileIOBytesWritten

  - **Data\_FilePathHash:binary** – dvojiška vrednost razpršitve za pot datoteke

  - **Data\_FilePathHash: binary** – GUID za pot datoteke

  - **Data\_FileSize –** velikost dokumenta v bajtih

  - **Data\_ForegroundPages:integer –** število strani v ospredju diagrama

  - **Data\_ForegroundShapes:integer –** celo število za oblike na straneh v ospredju

  - **Data\_GdiInitTime:integer –** čas, zahtevan za inicializacijo modula GDI

  - **Data\_HasCoauthUserEdit:bool –** ima vrednost true, če je bil dokument urejen v seji soavtorstva

  - **Data\_HasCustomPages:bool –** ima vrednost true, če dokument vsebuje strani po meri

  - **Data\_HasCustPatterns:bool –** ima vrednost true, če datoteka vsebuje vzorce po meri

  - **Data\_HasDynConn:bool –** ima vrednost true, če dokument vsebuje dinamično povezavo

  - **Data\_HasScaledPages:bool –** ima vrednost true, če dokument vsebuje strani s spremenjenimi stranmi

  - **Data\_HasUserWaitTime:bool –** ima vrednost true, če se med shranjevanjem prikaže pogovorno okno datoteke

  - **Data\_InitAddinsTime:integer –** čas, zahtevan za inicializacijo in nalaganje dodatka COM

  - **Data\_InitBrandTime:integer –** čas, zahtevan za inicializacijo pozdravnega zaslona in zaščitenih Officeovih komponent

  - **Data\_InitGimmeTime:integer –** čas, zahtevan za inicializacijo Officeove komponente

  - **Data\_InitLicensingTime:integer –** čas, zahtevan za inicializacijo za licenciranje Officeove komponente

  - **Data\_InitMsoUtilsTime:integer –** čas, zahtevan za inicializacijo Officeove komponente MSOUTILS

  - **Data\_InitPerfTime:integer –** čas, zahtevan za inicializacijo Officeove komponente za učinkovitost delovanja

  - **Data\_InitTCOTime:integer –** čas, zahteva za inicializacijo upravitelja za Officeove komponente

  - **Data\_InitTrustCenterTime:integer –** čas, zahtevan za inicializacijo središča za zaupanje Officeove komponente

  - **Data\_InitVSSubSystemsTime:integer –** čas, zahteva za inicializacijo Visiovih komponent

  - **Data\_InternalFile:bool –** ima vrednost true, če gre za notranjo datoteko, denimo šablono

  - **Data\_IsAsyncSave:bool –** ima vrednost true, če je bilo zaznano asinhrono shranjevanje

  - **Data\_IsAutoRecoveredFile:bool –** ima vrednost true, če je bila datoteka samodejno obnovljena

  - **Data\_IsEmbedded:bool –** ima vrednost true, če je bila Visiova datoteka vgrajena v drugo aplikacijo

  - **Data\_IsInfinitePageDisabledForAllPages:bool –** ima vrednost true, če je funkcija neskončne strani onemogočena za vse strani dokumenta

  - **Data\_IsIRMProtected:bool –** ima vrednost true, če ima datoteka zaščito za upravljanje pravic do informacij

  - **Data\_IsLocal:bool –** ima vrednost true, če je datoteka lokalna

  - **Data\_IsRecoverySave:bool –** ima vrednost true, če je postopek shranjevanja sprožila obnovitev

  - **Data\_IsShapeSearchPaneHiddenState:bool –** ima vrednost true, če je bilo za dokument skrito podokno za iskanje oblik

  - **Data\_IsSmartDiagramPresentInActivePageOfFile:bool –** vrednost boolean, ima vrednost true, če aktivna stran datoteke vsebuje pametni diagram s ponazoritvijo podatkov

  - **Data\_IsSmartDiagramPresentInFile:bool –** vrednost boolean, ima vrednost true, če datoteka vsebuje pametni diagram s ponazoritvijo podatkov

  - **Data\_IsUNC:bool –** ima vrednost true, če pot dokumenta ustreza univerzalna pravila poimenovanja

  - **Data\_LandscapePgCount:integer –** število strani, ki imajo v diagramu ležečo usmerjenost

  - **Data\_Layers:integer –** število plasti v diagramu

  - **Data\_LoadProfileTime:integer –** čas, zahtevan za nalaganje Officeovega orodja za spremljanje delovanja

  - **Data\_LoadRichEditTim:integer –** čas, zahtevan za nalaganje komponente z obogatenimi vnosi

  - **Data\_LoadVisIntlTime:integer –** čas, zahtevan za nalaganje Visiove mednarodne knjižnice DLL

  - **Data\_Location:integer –** mesto za odpiranje datoteke; 0 lokalno, 1 omrežje, 2 SharePoint, 3 splet

  - **Data\_MasterCount:integer –** število nadrejenih elementov v diagramu

  - **Data\_MaxCoauthUsers:integer –** največje dovoljeno število uporabnikov, ki sourejajo v seji Filesystem, Registry, First Party, SDX

  - **Data\_MaxTilesAutoSizeOn:integer –** največje dovoljeno število naslovov strani, za katero je omogočeno samodejno spreminjanje velikosti

  - **Data\_MsoBeginBootTime:integer –** čas zagona za MSZN

  - **Data\_MsoDllLoadTime:integer –** čas, zahtevan za nalaganje knjižnice DLL MSZN

  - **Data\_MsoEndBootTime:integer –** čas, zahtevan za končanje zagona MSZN

  - **Data\_MsoInitCoreTime:integer –** čas, zahtevan za inicializacijo Officeove komponente MSZN

  - **Data\_MsoInitUITime:integer –** čas, zahtevan za inicializacijo Officeove komponente uporabniškega vmesnika

  - **Data\_MsoMigrateTime:integer –** čas, zahtevan za selitev uporabniških nastavitev pri prvem zagonu, če je uporabnik nadgradil iz prejšnje različice

  - **Data\_NetworkIOBytesRead:int –** skupno število bajtov omrežja, prebranih med shranjevanjem

  - **Data\_NetworkIOBytesReadSquared:int –** kvadratna vrednost za Network\_FileIOBytesRead

  - **Data\_NetworkIOBytesWritten:int –** skupno število bajtov omrežja, zapisanih med shranjevanjem

  - **Data\_NetworkIOBytesWrittenSquared:int –** kvadratna vrednost za NetworkOBytesWritten

  - **Data\_OartStartupTime:integer –** čas, zahtevan za inicializacijo Officeove komponente OART

  - **Data\_OleInitTime:integer –** čas, zahtevan za inicializacijo Officeove komponente OLE

  - **Data\_OpenDurationTimeInMs:integer –** čas, zahtevan za odpiranje datoteke v milisekundah

  - **Data\_OriginatedFromTemplateID:integer –** identifikator predloge, iz katere je bil ustvarjen diagram. Ima vrednost NULL za predloge tretjih oseb

  - **Data\_Pages:integer –** število strani v dokumentu

  - **Data\_PositionToolbarsTime:integer –** čas, zahtevan za postavitev orodnih vrstic

  - **Data\_ReadOnly:bool –** ima vrednost true, če je datoteka v načinu samo za branje

  - **Data\_RecordSetCount:integer –** število zapisov, nastavljenih v diagramu

  - **Data\_RecoveryTime:integer –** čas, zahtevan za odpiranje obnovitvenih datotek

  - **Data\_ReviewerPages:integer –** število strani pregledovalnika v diagramu

  - **Data\_RibbonTime:integer –** čas, zahtevan za prikaz vrstice stanja

  - **Data\_RoamingSettingsStartupTime:integer –** čas, zahtevan za ustvarjanje in nalaganje vseh trenutno preseljenih nastavitev za Visio

  - **Data\_SchemeMgrStartupTime:integer –** čas, zahtevan za inicializacijo upravitelja shem

  - **Data\_SDX\_AssetId –** na voljo SAMO za dodatke iz trgovine. OMEX dodatku podeli ID sredstva, ko se naloži v trgovino

  - **Data\_SDX\_BrowserToken –** identifikator v predpomnilniku brskalnika

  - **Data\_SDX\_HostJsVersion –** predstavlja platformo, specifično za različico datoteke Office.js (npr. outlook web16.01.js). Vsebuje programski vmesnik za dodatke

  - **Data\_SDX\_Id –** GUID dodatka, ki ga enolično identificira

  - **Data\_SDX\_InstanceId –** predstavlja par dokumenta dodatka

  - **Data\_SDX\_MarketplaceType –** ponazarja vir, iz katerega je bil nameščen dodatek

  - **Data\_SDX\_OfficeJsVersion –** predstavlja različico datoteke Office.js, ki poskrbi za preusmeritev na različico, odvisno od platforme

  - **Data\_SDX\_Version –** različica dodatka

  - **Data\_ShellCmdLineTime:integer –** čas, zahtevan za razčlenitev in izvedbo ukazov lupine v ukazni vrstici

  - **Data\_Size:long** – velikost datoteke v bajtih

  - **Data\_StartEndTransactionTime:integer –** čas, zahtevan za inicializacijo Visiovih komponent

  - **Data\_STNInitTime:integer –** čas, zahtevan za inicializacijo konfiguracijo okna šablone

  - **Data\_Tag:string –** enolični identifikator za prepoznavanje dogodka »Shrani kot«

  - **Data\_ThemeCount:integer –** število tem v diagramu

  - **Data\_TimeStamp –** časovni žig, ko je bil dokument zaprt

  - **Data\_UIInitTime:integer –** čas, zahtevan za inicializacijo uporabniškega vmesnika

  - **Data\_WasSuccessful:bool –** ima vrednost true, če je bilo shranjevanje uspešno

  - **Data\_WinLaunchTime:integer –** čas, zahtevan za zagon podokna za zagon Visia itd.

  - **Office.Visio.FileCharacteristicsVisio –** zajame lastnosti datoteke pri zagonu za Visio C2R in Dev16. S tem dogodkom lahko razvrstimo napake o lastnostih dokumentov in jih odpravimo. To nam prav tako omogoča, da na strankino zadovoljstvo hitreje določimo glavni vzrok in hitreje odpravimo težavo.

  - **Office.Visio.Shared.BootStats –** ta dogodek zbira čas zagona za aplikacijo Visio Win32. Zbira različna polja za zagon različnih komponent, kot so čas za nalaganje traku, čas za inicializacijo aplikacije. Ta dogodek se uporablja za merjenje učinkovitosti zagona za Visio.

  - **Office.Visio.Shared.FileOpen –** ta dogodek zbira statistiko za odpiranje datotek za Visio. Uporablja se za nadzor stopenj uspešnosti in neuspešnosti pri odpiranju datotek, ki jih preslika z nekaterimi lastnostmi, denimo velikostjo datoteke. Lastnosti datoteke nam omogočajo, da hitreje odkrijemo napako in poiščemo glavni vzrok.

  - **Office.Visio.Shared.Filesave –** ta dogodek zbira statistiko za shranjevanje datotek za Visio. Uporablja se za nadzor stopenj uspešnosti in neuspešnosti pri shranjevanju datotek, ki jih preslika z nekaterimi lastnostmi, denimo velikostjo datoteke in mestom shranjevanja, npr. v oblak/lokalno. Lastnosti datoteke nam omogočajo, da hitreje odkrijemo napako in poiščemo glavni vzrok.

  - **Office.Visio.Shared.FilesaveAs –** ta dogodek zbira statistiko za funkcijo »Shrani datoteko kot« za Visio. Uporablja se za nadzor stopenj uspešnosti in neuspešnosti pri shranjevanju datotek, ki jih preslika z nekaterimi lastnostmi, denimo velikostjo datoteke in mestom shranjevanja, npr. v oblak/lokalno. Lastnosti datoteke nam omogočajo, da hitreje odkrijemo napako in poiščemo glavni vzrok.

  - **Office.Visio.Shared.PostSave –** da dogodek zajame vzrok napake pri shranjevanju datoteke.

  - **Office.Visio.VisioFileSaveAs –** ta dogodek zbira statistiko za funkcijo »Shrani datoteko kot« za Visio Dev16. Uporablja se za nadzor stopenj uspešnosti in neuspešnosti pri funkciji »Shrani datoteko kot«, ki jih preslika z nekaterimi lastnostmi, denimo velikostjo datoteke in mestom shranjevanja, npr. v oblak/lokalno. Lastnosti datoteke nam omogočajo, da hitreje odkrijemo napako in poiščemo glavni vzrok.

  - **Office.Visio.VisioFileSaveAsync –** ta dogodek zbira statistiko za funkcijo asinhronega shranjevanja za Visio Dev16. Uporablja se za nadzor stopenj uspešnosti in neuspešnosti pri funkciji asinhronega shranjevanja, ki jih preslika z nekaterimi lastnostmi, denimo velikostjo datoteke in mestom shranjevanja, npr. v oblak/lokalno. Lastnosti datoteke nam omogočajo, da hitreje odkrijemo napako in poiščemo glavni vzrok.

  - **Office.Visio.VisioFileSaveSync –** ta dogodek zbira statistiko za funkcijo sinhronega shranjevanja za Visio Dev16. Uporablja se za nadzor stopenj uspešnosti in neuspešnosti pri funkciji sinhronega shranjevanja, ki jih preslika z nekaterimi lastnostmi, denimo velikostjo datoteke in mestom shranjevanja, npr. v oblak/lokalno. Lastnosti datoteke nam omogočajo, da hitreje odkrijemo napako in poiščemo glavni vzrok. Ta dogodek nam omogoča, da nadziramo vzroke za napake pri shranjevanju datoteke.

#### <a name="officeextensibilitysandboxodpactivationhanging"></a>Office.Extensibility.Sandbox.ODPActivationHanging

Zbira podatke, ko zagon Officeovega dodatka traja nepričakovano dolgo (> 5 s). Uporablja se za zaznavanje in odpravljanje težav pri zagonih Officeovih dodatkov.
 
Zbrana so naslednja polja:

- **AppId** – ID aplikacije

- **AppInfo** – podatki glede vrste dodatka (podokno opravil ali UILess ali znotraj vsebine itd.) in vrste ponudnika (Omen, SharePoint, datotečni sistem itd.)

- **AppInstanceId** – ID primerka aplikacije 

- **AssetId** – ID sredstva aplikacije.

- **NumberOfAddinsActivated** – števec aktiviranih dodatkov.

- **RemoterType** – določa vrsto remoterja (zaupanja vreden, ni vreden zaupanja, Win32webView, zaupanja vreden UDF itd.), ki se uporablja za aktiviranje dodatka.

- **StoreType** – izvor aplikacije.

- **TimeForAuth** – čas, porabljen za preverjanje pristnosti. 

- **TimeForSandbox** – čas, porabljen za peskovnik.

- **TimeForServerCall** – čas, porabljen za klic strežnika. 

- **TotalTime** – skupni porabljeni čas


#### <a name="officeoutlookdesktopexchangepuidandtenantcorrelation"></a>Office.Outlook.Desktop.ExchangePuidAndTenantCorrelation

Zbere uporabniški PUID in identifikator najemnika enkrat na sejo. Korelaciji za PUID in najemnika sta zahtevani za razumevanje in diagnosticiranje Outlookovih težav za najemnika.

Zbrana so sledeča polja:

  - **CollectionTime** – časovni žig dogodka

  - **ConnId** – identifikator povezave: identifikator za razčlenjevanje povezave za identifikator najemnika PUID in OMS

  - **OMSTenantId** – enolični identifikator najemnika, ki ga ustvari Microsoft

  - **PUID** – Exchengeev PUID za enolično prepoznavanje uporabnikov


#### <a name="officeoutlookmacmacolkactivationstate"></a>Office.Outlook.Mac.MacOLKActivationState

Zbere podatke o načinu aktiviranja Outlooka, na primer z naročnino ali s količinskim licenciranjem. Podatke spremljamo, da zagotovimo, da ne pride do morebitnih konic napak. Z analiziranjem teh podatkov odkrijemo tudi področja, ki jih moramo izboljšati. 

Zbrana so naslednja polja:

- **SetupUIActivationMethod** – način aktiviranja Outlooka, na primer naročnina ali količinsko licenciranje.

#### <a name="officepowerpointdocoperationopen"></a>Office.PowerPoint.DocOperation.Open 

Ta dogodek je zbran vsakokrat, ko PowerPoint odpre datoteko. Vsebuje informacije o uspehu, podrobnosti o napaki, metriko učinkovitosti delovanja in osnovne podrobnosti o datoteki, vključno z vrsto oblike zapisa datoteke ter metapodatki dokumenta. Te informacije so zahtevane, da PowerPoint lahko uspešno odpira datoteke in pri tem ne izgublja na učinkovitosti delovanja. Z njimi lahko diagnosticiramo težave, ki jih odkrijemo.

Zbrana so sledeča polja:

  - **Data\_AddDocTelemetryResult –** ali ima ta vnos dnevnika vso zahtevano telemetrijo dokumenta (polja Data\_Doc\_\*)

  - **Data\_AddDocumentToMruList –** trajanje izvedbe za način AddDocumentToMruList

  - **Data\_AlreadyOpened –** ali je bil ta dokument že odprt (v kontekstu iste seje procesa)

  - **Data\_AntiVirusScanMethod –** nabor vnaprej določenih vrednosti za protivirusni pregled (IOAV, AMSI, None itd.)

  - **Data\_AntiVirusScanStatus –** nabor vnaprej določenih vrednosti za protivirusni pregled, ki se izvede za vsak odprti dokument (NoThreatsDetected, Failed, MalwareDetected itd.)

  - **Data\_AsyncOpenKind –** nabor vnaprej določenih vrednosti za asinhrone možnosti (Collab, ServerOnly, SyncBacked, NotAsync)

  - **Data\_CancelBackgroundDownloadHr –** ali je prišlo do prekinitve med prenosom dokumenta? Če je odgovor pritrdilen, kakšen je bil rezultat prekinitve?

  - **Data\_CheckForAssistedReadingReasons –** trajanje izvedbe za način CheckForAssistedReadingReasons v milisekundah

  - **Data\_CheckForDisabledDocument –** trajanje izvedbe za način CheckForDisabledDocument v milisekundah

  - **Data\_CheckForExistingDocument –** trajanje izvedbe za način CheckForExistingDocument v milisekundah

  - **Data\_CheckIncOpenResult –** trajanje izvedbe za način CheckIncOpenResult v milisekundah

  - **Data\_CheckLambdaResult –** trajanje izvedbe za način CheckLambdaResult v milisekundah

  - **Data\_CheckPackageForRequiredParts –** trajanje izvedbe za način CheckPackageForRequiredParts v milisekundah

  - **Data\_CheckPackageForSpecialCases –** trajanje izvedbe za način CheckPackageForSpecialCases v milisekundah

  - **Data\_CheckRequiredPartsLoaded –** trajanje izvedbe za način CheckRequiredPartsLoaded v milisekundah

  - **Data\_CheckWebSharingViolationForIncOpen –** trajanje izvedbe za način CheckWebSharingViolationForIncOpen v milisekundah
   
  - **Data_CloseAndReopenWithoutDiscard –** ali je bil dokument zaprt in ponovno odprt med postopkom odpiranja brez zavrženja.

  - **Data\_ContentTransaction –** nabor vnaprej določenih vrednosti, ko je mogoče ustvariti transakcijo (AllowedOnLoadDocument, AllowedOnOpenComplete itd.)

  - **Data_CorrelationId –** GUID, ki je bil v PowerPoint posredovan z rutino ProtocolHandler za korelacijo telemetrije. ProtocolHandler je ločen proces, ki obravnava Officeove povezave za OS.

  - **Data\_CppUncaughtExceptionCount:long –** nezaznane izvirne izjeme med dejavnostjo

  - **Data\_CreateDocumentTimeMS –** trajanje izvedbe za način CreateDocumentTimeMS v milisekundah

  - **Data\_CreateDocumentToken –** trajanje izvedbe za način CreateDocumentToken v milisekundah

  - **Data\_CreateDocumentToW –** trajanje izvedbe za način CreateDocumentToW v milisekundah

  - **Data\_CreateDocWindow –** trajanje izvedbe za način CreateDocWindow v milisekundah

  - **Data\_CreateLocalTempFile –** trajanje izvedbe za način CreateLocalTempFile v milisekundah

  - **Data\_DetachedDuration:long –** čas odpete dejavnosti/neizvajanja dejavnosti

  - **Data\_DetermineFileType –** trajanje izvajanja za način DetermineFileType v milisekundah

  - **Data\_Doc\_AccessMode:long –** način odpiranja dokumenta (samo za branje/branje in pisanje)

  - **Data\_Doc\_AssistedReadingReasons:long –** nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja

  - **Data_Doc_AsyncOpenKind:long – ** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

  - **Data\_Doc\_ChunkingType:long –** način shranjevanja dokumenta v SharePointu

  - **Data\_Doc\_EdpState:long –** stanje zaščite dokumentov podjetja za dokument

  - **Data\_Doc\_Ext:string –** pripona dokumenta

  - **Data\_Doc\_Extenstion:string –** pripona dokumenta

  - **Data\_Doc\_FileFormat:long –** nabor vnaprej nastavljenih vrednosti za obliko zapisa datoteke (bolj podrobno kot za pripono)

  - **Data\_Doc\_Fqdn:string –** mesto, kjer je dokument shranjen (SharePoint.com, live.net); na voljo samo za domene v storitvi Office 365

  - **Data\_Doc\_FqdnHash:string –** razpršitev mesta shrambe dokumenta

  - **Data\_Doc\_IdentityTelemetryId:string –** enolični GUID uporabnika

  - **Data\_Doc\_IdentityUniqueId:string –** enolični identifikator identitete, ki je bila uporabljena za dokumente v skupni rabi

  - **Data\_Doc\_IOFlags:long** – Bitna maska za različne zastavice danega dokumenta, povezane z V/I.

  - **Data\_Doc\_IrmRights:long** – Nabor vnaprej določenih vrednosti za vrsto upravljanja pravic do informacij, ki velja za ta dokument (»Forward«, »Reply«, »SecureReader«, »Edit« itd.).

  - **Data\_Doc\_IsCloudCollabEnabled:bool –** ima vrednost true, če je bila glava HTTP »IsCloudCollabEnabled« že prejeta od zahteve OPTIONS

  - **Data\_Doc\_IsIncrementalOpen:bool –** ali je bil dokument odprt postopoma (nova funkcija, ki dokument odpre, brez da prenese celoten dokument)

  - **Data\_Doc\_IsOcsSupported:bool –** ali dokument podpira soavtorstvo z novo storitvijo OCS

  - **Data\_Doc\_IsOpeningOfflineCopy:bool –** ali je bil dokument odprt iz lokalnega predpomnilnika?

  - **Data\_Doc\_IsSyncBacked:bool –** ali je bil dokument odprt iz mape, za katero se uporablja aplikacija za povratno sinhronizacijo v storitvi OneDrive

  - **Data\_Doc\_Location:long-**: nabor vnaprej določenih vrednosti za mesto shranjevanja dokumenta (lokalno, SharePoint, WOPI, omrežje itd.)

  - **Data\_Doc\_LocationDetails:long –** nabor vnaprej določenih vrednosti podrobnejše lokacije (mapa »Začasno«, mapa »Prenosi«, dokumenti storitve One Drive, slike storitve One Drive itd.)

  - **Data\_Doc\_NumberCoAuthors:long –** število soavtorjev, ko je bil dokument odprt

  - **Data\_Doc\_PasswordFlags:long –** nabor vnaprej določenih vrednosti za način šifriranja dokumenta z geslom (brez, geslo za branje, geslo za urejanje)

  - **Data\_Doc\_ReadOnlyReasons:long –** nabor vnaprej določenih vrednosti, zakaj je bil ta dokument označen samo za branje (zaklenjeno v strežniku, dokončni dokument, zaščiteno z geslom za urejanje itd.)

  - **Data\_Doc\_ResourceIdHash:string –** razpršitev identifikatorja vira za dokumente, shranjene v oblaku

  - **Data_Doc_RtcType – **  označuje, kako je bil kanal v realnem času (RTC) nastavljen za trenutno datoteko (onemogočeno, nepodprto, na zahtevo, vedno vklopljeno itn.).

  - **Data\_Doc\_ServerDocId:string –** nespremenljivi identifikator za dokumente, shranjene v oblaku

  - **Data\_Doc\_ServerProtocol:long –** nabor vnaprej določenih vrednosti, ki jih protokol uporablja za komunikacijo s strežnikom (Http, Cobalt, WOPI itd.)

  - **Data\_Doc\_ServerType:long –** nabor vnaprej določenih vrednosti za vrsto strežnika (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long –** ali ta strežnik temelji na sistemu Office 14, Office 15, Office 16?

  - **Data\_Doc\_SessionId:long –** ustvarjeni GUID, ki prepozna primerek dokumenta v seji istega procesa

  - **Data\_Doc\_SharePointServiceContext:string –** neprosojen niz, običajno GridManagerID.FarmID. Uporabni dogodki za korelacijo odjemalskih in strežniških dnevnikov

  - **Data\_Doc\_SizeInBytes:long –** velikost dokumenta v bajtih

  - **Data\_Doc\_SpecialChars:long –** bitna maska, ki ponazarja posebne znake v URL-ju ali poti dokumenta

  - **Data\_Doc\_StorageProviderId:string –** niz, ki prepozna ponudnika za shranjevanje dokumentov, na primer DropBox

  - **Data\_Doc\_StreamAvailability:long –** nabor vnaprej določenih vrednosti za stanje dokumenta Stream (na voljo, stalno onemogočeno, ni na voljo)

  - **Data\_Doc\_UrlHash:string –** razpršitev polnega URL-ja za dokumente, shranjene v oblaku

  - **Data\_Doc\_UsedWrsDataOnOpen:bool –** ima vrednost true, če je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS na strani gostitelja

  - **Data\_Doc\_WopiServiceId:string –** identifikator storitve WOPI, na primer Dropbox

  - **Data\_DownloadExcludedData –** trajanje izvajanja za način DownloadExcludedData v milisekundah

  - **Data\_DownloadExcludedDataTelemetry –** nabor vnaprej določenih vrednosti za stanje sinhronega čakanja na prenos (SynchronousLogicHit, UserCancelled RunModalTaskUnexpectedHResult itd.)

  - **Data\_DownloadFileInBGThread –** trajanje izvedbe za način DownloadFileInBGThread v milisekundah

  - **Data\_DownloadFragmentSize –** velikost dela (del datoteke, ki ga je mogoče prenesti), običajno 3,5 MB

  - **Data\_ExcludedEmbeddedItems –** število stisnjenih delov, ki so bili izključeni pri prvem upodabljanju

  - **Data\_ExcludedEmbeddedItems –** skupna velikost stisnjenih delov, ki so bili izključeni pri prvem upodabljanju

  - **Data\_ExcludedRequiredItems –** število stisnjenih delov, ki so bili izključeni pri prvem upodabljanju, vendar so zahtevani

  - **Data\_ExcludedRequiredItemsSize –** skupna velikost stisnjenih delov, ki so bili izključeni pri prvem upodabljanju, vendar so zahtevani

  - **Data\_ExecutionCount –** število izvedenih protokolov IncOpen

  - **Data\_FailureComponent:long –** nabor vnaprej določenih vrednosti komponent, zaradi katerih tega protokola ni bilo mogoče izvesti (Spor, CSI, Internal itd.)

  - **Data\_FailureReason:long –** nabor vnaprej določenih vrednosti za vzroke okvare (FileIsCorrupt, BlockedByAntivirus itd.)

  - **Data\_FCreateNew –** ali je to nov prazen dokument

  - **Data\_FCreateNewFromTemplate –** ali je to nov dokument iz predlog

  - **Data_FErrorAfterDocWinCreation:boolean** – Ali je prišlo do morebitne napake ali izjeme po tem, ko je bilo ustvarjeno okno dokumenta.

  - **Data\_FileUrlLocation –** nabor vnaprej določenih vrednosti za mesto shranjevanja dokumentov (NetworkShare, LocalDrive, ServerOther itd.)

  - **Data\_FirstSlideCompressedSize –** stisnjena velikost prvega stisnjenega dela diapozitivov (običajno Slide1.xml)

  - **Data\_FIsDownloadFileInBgThreadEnabled –** ali je omogočen prenos v niti v ozadju?

  - **Data\_fLifeguarded:bool –** ali je bil dokument kdaj zavarovan (funkcija za samodejno odpravljanje težav z dokumenti brez pozivanja uporabnika)?

  - **Data\_ForceReopenOnIncOpenMergeFailure –** zastavica, ki predstavlja, ali smo morali dokument znova odpreti zaradi napake pri spajanju pri postopnem odpiranju

  - **Data\_ForegroundThreadPass0TimeMS –** skupni čas, porabljen za nit v ospredju pri prvem posredovanju (velja samo za računalnike Mac)

  - **Data\_ForegroundThreadPass1TimeMS –** skupni čas, porabljen za nit v ospredju pri drugem posredovanju (velja samo za računalnike Mac)

  - **Data\_FWebCreatorDoc –** ali je bil dokument ustvarjen iz predloge oziroma z orodjem za hiter začetek

  - **Data\_HasDocToken –** ali ima ta dokument žeton za dokument CSI (notranja koda)

  - **Data\_HasDocument –** ali ta dokument vsebuje dokument CSI (notranja koda)

  - **Data\_InclusiveMeasurements –** ali trajanja izvedb za načine vključujejo trajanje klicev za podrejene načine

  - **Data\_IncompleteDocReasons –** nabor vnaprej določenih vrednosti, zakaj odpiranje ni bili dokončano v celoti (Unknown, DiscardFailure itd.)

  - **Data\_IncOpenDisabledReasons –** nabor vnaprej določenih vrednosti za razloge, zakaj je onemogočena funkcija postopnega odpiranja

  - **Data\_IncOpenFailureHr –** rezultat, zakaj funkcije postopnega odpiranja ni bilo mogoče izvesti

  - **Data\_IncOpenFailureTag –** oznaka (kazalec na mesto v kodu), kjer je prišlo do napake pri postopnem odpiranju

  - **Data\_IncOpenFallbackReason –** zakaj funkcija postopnega odpiranja ni bila izvedena

  - **Data\_IncOpenRequiredTypes –** nabor vnaprej določenih vrednosti za vrste vsebine, zahtevane za prvo upodabljanje (RequiredXmlZipItem, RequiredNotesMaster itd.)

  - **Data\_IncOpenStatus –** nabor vnaprej določenih vrednosti za stanje postopnega odpiranja (Attempted, FoundExcludedItems, DocIncOpenInfoCreated itd.)

  - **Data\_InitFileContents –** trajanje izvedbe za način InitFileContents v milisekundah

  - **Data\_InitialExcludedItems –** število stisnjenih delov, ki so bili izključeni na začetku

  - **Data\_InitialExcludedItemsSize –** skupna velikost stisnjenih delov, ki so bili izključeni na začetku

  - **Data\_InitializationTimeMS –** čas, zahtevan za inicializacijo (samo za računalnike Mac)

  - **Data\_InitialRoundtripCount –** število odzivov strežnika, zahtevanih za izvedbo začetnega arhiva zip

  - **Data\_InitLoadProcess –** trajanje izvedbe za način InitLoadProcess v milisekundah

  - **Data\_InitPackage –** trajanje izvedbe za način InitPackage v milisekundah

  - **Data\_InitSecureReaderReasons –** trajanje izvedbe za način  InitSecureReaderReasons v milisekundah

  - **Data\_IsIncOpenInProgressWhileOpen –** če želite isti dokument odpreti večkrat, ali je poleg protokola za odpiranje aktivirano tudi postopno odpiranje?

  - **Data\_IsMultiOpen –** ali podpiramo večkratno odpiranje?

  - **Data\_IsOCS –** ali je bil dokument v načinu OCS v njegovem zadnjem znanem stanju

  - **Data\_IsODPFile –** ali je dokument v stanju »Odpri obliko zapisa datoteke«, ki ga uporablja OpenOffice.org 

  - **Data\_IsPPTMetroFile –** ali je dokument ustvarjen v obliki zapisa datoteke pptx

  - **Data\_LoadDocument –** trajanje izvedbe za način LoadDocument v milisekundah

  - **Data\_MeasurementBreakdown –** razčlenitev šifrirane meritve (podrobnosti učinkovitosti načina v skrajšani obliki)

  - **Data\_Measurements –** šifrirane meritve

  - **Data\_MethodId –** zadnji izvedeni način

  - **Data\_NotRequiredExcludedItems –** skupno število PowerPointovih paketnih elementov, ki niso zahtevani za prvo upodabljanje in so bili izključeni

  - **Data\_NotRequiredExcludedItemsSize –** skupna velikost PowerPointovih paketnih elementov, ki niso zahtevani za prvo upodabljanje in so bili izključeni

  - **Data\_NotRequiredExcludedParts –** skupno število stisnjenih delov, ki niso zahtevani za prvo upodabljanje in so bili izključeni

  - **Data\_NotRequiredExcludedPartsSize –** skupno število stisnjenih delov, ki niso zahtevani za prvo upodabljanje in so bili izključeni

  - **Data\_OpenCompleteFailureHR –** razlog, zakaj protokola OpenComplete ni bilo mogoče dokončati

  - **Data\_OpenCompleteFailureTag –** oznaka (kazalec na mesto v kodi) mesta, kjer je prišlo do napake pri protokolu OpenComplete

  - **Data\_OpenLifeguardOption –** nabor vnaprej določenih vrednosti za izbire načinov zaščite (None, TryAgain, OpenInWebApp itd.)

  - **Data\_OpenReason –** nabor vnaprej določenih vrednosti za način odpiranja dokumenta (FilePicker, OpenFromMru, FileDrop itd.)

  - **Data\_OSRPolicy –** pravilnik SecureReader

  - **Data\_OSRReason –** razlogi, zakaj je bil ta dokument v programu Secure Reader

  - **Data\_OtherContentTypesWithRequiredParts –** nestandardne vrste vsebine, ki so bile izključene, vendar so zahtevane za prvo upodabljanje

  - **Data\_PrepCacheAsync –** zastavica za OcsiOpenPerfPrepCacheAsync

  - **Data\_PreviousDiscardFailed –** ponazarja, da prejšnji poskus odpiranja/zapiranja dokumenta ni pravilno sprostil vsega pomnilnika

  - **Data\_PreviousFailureHr –** v primeru vnovičnega odpiranja istega dokumenta ponazarja zadnji neuspešen rezultat

  - **Data\_PreviousFailureTag –** v primeru vnovičnega odpiranja istega dokumenta ponazarja zadnjo neuspešno oznako (kazalec na mesto v kodi)

  - **Data\_RemoteDocToken –** ali je omogočeno oddaljeno odpiranje (funkcija prototipa, ki omogoča odpiranja datoteke iz storitve in ne iz gostitelja)?

  - **Data\_Repair –** ali je aktiviran način za popravilo dokumenta (na voljo samo za poškodovane dokumente, ki jih je mogoče popraviti)

  - **Data\_RequestPauseStats –** število primerov, ko je koda zahtevala premor beleženja učinkovitosti delovanja

  - **Data\_RequiredPartsComressedSize –** skupna velikost zahtevanih PowerPointovih delov, zahtevanih za prvo upodabljanje

  - **Data\_RequiredPartsDownload –** skupna velikost zahtevanih PowerPointovih delov, ki so bili preneseni

  - **Data\_RequiredPartsRoundtripCount –** skupno število odhodov in vrnitev (klicev gostitelja), potrebnih za pridobitev vseh PowerPointovih delov, zahtevanih za prvo upodabljanje

  - **Data\_RequiredZipItemsDownload –** skupna velikost stisnjenih elementov, zahtevanih za prvo upodabljanje

  - **Data\_RequiredZipItemsRoundtripCount –** skupno število odhodov in vrnitev (klicev gostitelja), potrebnih za pridobitev vseh stisnjenih delov, zahtevanih za prvo upodabljanje

  - **Data\_RoundtripsAfterMissingRequiredParts –** skupno število odhodov in vrnitev (klicev gostitelja), ki so zahtevani, po tem, ko smo odkrili manjkajoče zahtevane PowerPointove dele

  - **Data\_RoundtripsAfterMissingRequiredZipItems –** skupno število odhodov in vrnitev (klicev gostitelja), ki so zahtevani, po tem, ko smo odkrili manjkajoče zahtevane stisnjene elemente

  - **Data\_RoundtripsAfterRequiredPackage –** skupno število zahtevanih odhodov in vrnitev (klicev gostitelja), po tem, ko smo ustvarili paket

  - **Data\_RoundtripsAfterRequiredParts –** skupno število zahtevanih odhodov in vrnitev (klicev gostitelja), po tem, ko smo prenesli vse zahtevane dele

  - **Data\_SetDocCoAuthAutoSaveable –** trajanje izvedbe za način SetDocCoAuthAutoSaveable v milisekundah

  - **Data\_SniffedFileType –** domneva predlagane vrste dokumenta poškodovanega dokumenta

  - **Data\_StartTime –** števec učinkovitosti delovanja pri odpiranju

  - **Data\_StopwatchDuration:long –** skupni čas dejavnosti

  - **Data\_SyncSlides –** trajanje izvedbe za način SyncSlides v milisekundah

  - **Data\_TimerStartReason –** nabor vnaprej določenih vrednosti za način zagona časovnika (CatchMissedSyncStateNotification, WaitingForFirstDownload itd.)

  - **Data\_TimeSplitMeasurements –** razčlenitev šifrirane meritve (podrobnosti učinkovitosti načina v skrajšani obliki)

  - **Data\_TimeToInitialPackage –** čas, zahtevan za ustvarjanje prvega paketa

  - **Data\_TimeToRequiredPackage –** čas, zahtevan za ustvarjanje zahtevanega paketa

  - **Data\_TimeToRequiredParts –** čas, zahtevan za ustvarjanje paketa z vsemi zahtevanimi deli

  - **Data\_TotalRequiredParts –** skupno število PowerPointovih delov, zahtevanih za prvo upodabljanje

  - **Data\_UnknownRequiredParts –** skupno število nestandardnih delov, zahtevanih za prvo upodabljanje

  - **Data\_UnpackLinkWatsonId –** identifikator Watson za napako pri odpiranju dokumenta prek URL-ja za OneDrive v skupni rabi

  - **Data\_UnpackResultHint –** nabor vnaprej določenih vrednosti za raztezanje rezultatov URL-ja v skupni rabi (NavigateToWebWithoutError, UrlUnsupported, AttemptOpen itd.)

  - **Data\_UnpackUrl –** trajanje izvedbe za način UnpackUrl v milisekundah

  - **Data\_UpdateAppstateTimeMS –** trajanje izvedbe za način UpdateAppstate v milisekundah

  - **Data\_UpdateCoauthoringState –** trajanje izvedbe za način UpdateCoauthoringState v milisekundah

  - **Data\_UpdateReadOnlyState –** trajanje izvedbe za način UpdateReadOnlyState v milisekundah

  - **Data\_WACCorrelationId –** pridobi korelacijo a dnevnike WebApp, če je bila datoteka odprta v brskalniku

  - **Data\_WasCachedOnInitialize –** ali je bil dokument predpomnjen med inicializacijo

  - **Data\_WBDirtyBeforeDiscard –** ali se je delovna veja spremenila pred vnovičnim odpiranjem dokumenta

  - **Data\_ZRTOpenDisabledReasons –** zakaj ni bilo mogoče odpreti dokumenta iz predpomnilnika (nič odhodov in vrnitev)

#### <a name="officepowerpointpptdesktopbootime"></a>Office.PowerPoint.PPT.Desktop.Bootime

Dogodek za zbiranje načina zagona za PowrPoint. Vključuje podatke o zagonu PowerPointa v zaščitnem načinu, o načinu branja s pomočjo, makru, tiskanju, novem in praznem dokumentu, obnovitvi dokumenta, avtomatizaciji in podatke o tem, ali uporablja tehnologijo zagona s klikom. Prav tako zbira čas, zahtevan za zagon PowerPointa. Ti podatki so ključnega pomena za zagotovitev pravilnega zagona PowerPointa iz različnih načinov. Microsoft te podatke uporablja za zbiranje časa o dolgem zagonu pri odpiranju PowerPointa iz različnih načinov.

Zbrana so sledeča polja:

  - **AssistedReading –** v načinu branja s pomočjo

  - **Automation –** iz avtomatiziranega načina

  - **Benchmark –** zagon preizkusa zmogljivosti

  - **Blank –** prazen dokument

  - **BootTime –** čas, zahtevan za zagon seje

  - **Embedding –** vgrajeni dokument

  - **IsC2R –** ali omogoča tehnologijo zagona s klikom

  - **IsNew –** nov dokument

  - **IsOpen –** je odprt

  - **Macro1 –** zaženi makro

  - **Macro2 –** zaženi makro

  - **NonStandardSpaceInCmdLine** – v ukazni vrstici je preveč presledkov

  - **Print –** natisni dokument

  - **PrintDialog –** natisni dokument s pogovornim oknom

  - **PrintPrinter –** natisni dokument s tiskalnikom

  - **ProtectedView –** v zaščitenem pogledu

  - **Regserver –** registriraj PowerPoint kot strežnik COM

  - **Restore –** obnovi dokument

  - **Show –** pokaži dokument

  - **Time –** čas seje

  - **UnprotectedView –** v nezaščitenem načinu

#### <a name="officepowerpointppthasuserediteddocument"></a>Office.PowerPoint.PPT.HasUserEditedDocument

Ti podatki so zbrani, ko uporabnik začne urejati dokument. Microsoft uporabi te podatke za izračun aktivnih uporabnikov, ki so urejali PowerPointov dokument.

Zbrana so sledeča polja:

  - **CorrelationId** – identifikator za korelacijo dokumenta

#### <a name="officeprojectbootandopenproject"></a>Office.Project.BootAndOpenProject

Project zaženete tako, da odprete datoteko. Ta dogodek ponazarja, da je uporabnik odprl Office Project s povezano datoteko. Vključuje kritične podatke o uspešnosti, s katerimi je mogoče zagotoviti, da Project lahko zažene datoteko in jo naloži.

Zbrana so sledeča polja:

  - **Data\_AlertTime –** čas, ko je bilo aktivno pogovorno okno zagona

  - **Data\_BootTime –** čas, zahtevan za zagon Projecta

  - **Data\_CacheFileSize –** velikost datoteke, če je bila datoteka predpomnjena

  - **Data\_EntDocType –** vrsta odprte datoteke

  - **Data\_IsInCache –** ali je bila datoteka odprta oziroma predpomnjena

  - **Data\_LoadSRAs –** ali uporabnik želi naložiti SRA-je

  - **Data\_Outcome –** skupni čas, zahtevan za zagon in odpiranje datoteke

  - **Data\_OpenFromDocLib –** ali je bila Projectova datoteka odprta iz knjižnice dokumentov

  - **Data\_ProjectServerVersion –** različica in gradnja, v kateri se trenutno izvaja Project

#### <a name="officeprojectbootproject"></a>Office.Project.BootProject

Za zagon Projecta vam ni treba odpreti datoteke. Ta dogodek ponazarja, da je uporabnik odprl Office Project brez povezane datoteke. Vključuje kritične podatke o uspešnosti, s katerimi je mogoče zagotoviti, da Project lahko zaženete.

Zbrana so sledeča polja:

  - **Data\_BootTime –** čas, zahtevan za zagon Projecta

  - **Data\_FileLoaded –** ima vrednost false, če ste datoteko odprli iz zunanjega oz. novega praznega projekta

  - **Data\_IsEntOfflineWithProfile out-space ** ali je uporabnikom bila dodeljena profesionalna inventarna številka in nimajo vzpostavljene povezave s strežnikom

  - **Data\_IsEntOnline –** ali je Projectova seja povezana s Projectovim strežnikom s funkcijami podjetja

  - **Data\_IsLocalOnline –** ali je Projectova seja povezana s Projectovim strežnikom s funkcijami podjetja

  - **Data\_ProjectServerVersion –** različica in gradnja, v kateri se trenutno izvaja Project


#### <a name="officeprojectopenproject"></a>Office.Project.OpenProject

Project odpre datoteko. Ta dogodek ponazarja, da je uporabnik neposredno odprl Projectovo datoteko. Vključuje kritične podatke o uspešnosti pri odpiranju datotek v Projectu.

Zbrana so sledeča polja:

  - **Data\_AgileMode –** določa, ali je odprti projekt stopničast oziroma prilagodljiv

  - **Data\_AlertTime –** čas, ko je bilo aktivno pogovorno okno zagona

  - **Data\_CacheFileSize –** velikost datoteke, če je bila datoteka predpomnjena

  - **Data\_EntDocType –** vrsta odprte datoteke

  - **Data\_IsInCache –** ali je bila datoteka odprta oziroma predpomnjena

  - **Data\_LoadSRAs –** ali uporabnik želi naložiti SRA-je

  - **Data\_OpenFromDocLib –** ali je bila Projectova datoteka odprta iz knjižnice dokumentov

  - **Data\_Outcome –** skupni čas, zahtevan za zagon in odpiranje datoteke

  - **Data\_Outcome –** skupni čas, zahtevan za zagon in odpiranje datoteke

  - **Data\_ProjectServerVersion –** različica in gradnja, v kateri se trenutno izvaja Project

#### <a name="officesessionidproviderofficeprocesssessionstart"></a>Office.SessionIdProvider.OfficeProcessSessionStart

Velja za vse vrste Officeovih aplikacij v okolju sistema Windows: win32 and UWP

Zbrana so sledeča polja:

- **OfficeProcessSessionStart** pošlje osnovne informacije ob zagonu nove Officeove seje. Ta dogodek se uporablja za štetje števila enoličnih sej, zaznanih v dani napravi. Ta dogodek se uporablja kot signal obveščanja o izvajanju aplikacije, s katerim se zagotovi, ali se aplikacija izvaja v napravi. Poleg tega se uporablja tudi kot kritičen signal za splošno zanesljivost aplikacije.

- **AppSessionGuid** – identifikator določene seje aplikacije, ki se je začela z ustvarjanjem procesa in traja vse do konca procesa. Dogodek je oblikovan kot standardni 128-bitni GUID, sestavljen iz 4 delov. Ti štirje deli v vrstnem redu so (1) 32-bitni ID procesa (2) 16-bitni ID seje (3) 16-bitni ID zagona (4) čas ustvarjanja 64-bitnega procesa v UTC 100ns

- **processSessionId** – naključno ustvarjeni GUID za prepoznavanje seje aplikacije

- **UTCReplace_AppSessionGuid** – logična vrednost konstante. Vedno ima vrednost true.

#### <a name="officetelemetryengineisprelaunch"></a>Office.TelemetryEngine.IsPreLaunch

Velja za Officeove aplikacije UWP.  Ta dogodek se sproži, ko se Officeova aplikacija zažene prvič po nadgradnji/namestitvi iz trgovine. Je del osnovnih diagnostičnih podatkov, ki se uporabljajo za sledenje, ali je seja zagonska.

Zbrana so sledeča polja:

- **appVersionBuild** – številka različice za gradnjo aplikacije

- **appVersionMajor** – Številka glavne različice aplikacije.

- **appVersionMinor** – manjša številka različice za aplikacijo

- **appVersionRev** – številka različice za revizijo aplikacije

- **SessionId** – naključno ustvarjeni GUID za prepoznavanje seje aplikacije

#### <a name="officetelemetryenginesessionhandoff"></a>Office.TelemetryEngine.SessionHandOff

Velja za Officeove aplikacije Win32.  S tem dogodkom lahko ugotovimo, ali je bila ustvarjena nova seja za obravnavno dohodka za odpiranje datoteke, ki ga je sprožil uporabnik. Predstavlja kritične diagnostične informacije, ki se uporabljajo za izpeljavo signala zanesljivosti, in zagotavlja, da aplikacija deluje po pričakovanjih.

Zbrana so sledeča polja:

- **appVersionBuild** – številka različice za gradnjo aplikacije

- **appVersionMajor** – Številka glavne različice aplikacije.

- **appVersionMinor** – manjša številka različice za aplikacijo

- **appVersionRev** – številka različice za revizijo aplikacije

- **childSessionId** – naključno ustvarjeni GUID za prepoznavanje seje aplikacije

- **parentSessionId** – naključno ustvarjeni GUID za prepoznavanje seje aplikacije


#### <a name="officewordfileopenopencmdfilemrupriv"></a>Office.Word.FileOpen.OpenCmdFileMruPriv

Ta dogodek ponazarja, da je Microsoft Office Word odprl dokument s seznama nedavno uporabljenih elementov. Poleg tega vsebuje kritične podatke o učinkovitosti odpiranja datotek in z vidika uporabnika predstavlja dogodek za zagon aplikacije. Dogodek nadzira, ali funkcija »Odpri datoteko s seznama nazadnje uporabljenih datotek« deluje v skladu s pričakovanji. Prav tako se uporablja za izračunane mesečne aktivne uporabnike/naprave in za metriko zanesljivosti v oblaku.

Zbrana so sledeča polja:

- **Data_AddDocTelemRes** – poroča, ali lahko pravilno dopolnimo druge vrednosti dogodka, povezane s telemetrijo dokumenta. Uporablja se za diagnostiko kakovosti podatkov.

- **Data_BytesAsynchronous** – število bajtov (stisnjenih), brez katerega je morda mogoče odpreti datoteko, če ga pridobimo, preden uporabnik začne urejati dokument oz. se ga morda odloči shraniti.

- **Data_BytesAsynchronousWithWork** – število bajtov (stisnjenih), brez katerega morda lahko odpremo datoteko, vendar bi zato morali občutno spremeniti kodo.

- **Data_BytesSynchronous** – število bajtov (stisnjenih), ki ga moramo pridobiti, preden lahko odpremo datoteko.

- **Data_BytesUnknown** – število bajtov v delih dokumenta, za katerega menimo, da ga ne bomo našli. 

- **Data_DetachedDuration** – koliko časa je bila dejavnost ločena od niti.

- **Data_Doc_AccessMode** – dokument je samo za branje/ga je mogoče urejati.

- **Data_Doc_AssistedReadingReasons** – nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

- **Data_Doc_AsyncOpenKind – ** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

- **Data_Doc_ChunkingType** – enote, uporabljene za postopno odpiranje dokumenta.

- **Data_Doc_EdpState** – nastavitev elektronske zaščite podatkov dokumenta.

- **Data_Doc_Ext** – pripona dokumenta (docx/xlsb/pptx itd.).

- **Data_Doc_FileFormat** – različica protokola za obliko zapisa datoteke.

- **Data_Doc_Fqdn** – ime domene za OneDrive ali SharePoint Online.

- **Data_Doc_FqdnHash** – enostranska zgoščena vrednost imena domene, ki omogoča identifikacijo stranke.

- **Data_Doc_IdentityTelemetryId** – enostranska zgoščena vrednost identitete uporabnika, uporabljena za odpiranje.

- **Data_Doc_InitializationScenario** – zabeleži način odpiranja dokumenta.

- **Data_Doc_IOFlags** – poroča o predpomnjenih zastavicah, uporabljenih za nastavitev možnosti zahtev za odpiranje.

- **Data_Doc_IrmRights** – dejanja, ki jih je dovolil pravilnik za elektronsko zaščito podatkov, ki velja za dokument/uporabnika.

- **Data_Doc_IsIncrementalOpen** – zastavica, ki označuje postopno odpiranje dokumenta.

- **Data_Doc_IsOcsSupported** – zastavica, ki označuje, da je storitev sodelovanja podprta v dokumentu.

- **Data_Doc_IsOpeningOfflineCopy** – zastavica, ki označuje, da je bila odprta kopija dokumenta brez povezave.

- **Data_Doc_IsSyncBacked** – zastavica, ki označuje, da v računalniku obstaja samodejno sinhronizirana kopija dokumenta

- **Data_Doc_Location** – označuje, v kateri storitvi je dokument na voljo (OneDrive, File Server, SharePoint itd.).

- **Data_Doc_LocationDetails** – označuje, v kateri znani mapi je na voljo lokalno shranjen dokument.

- **Data_Doc_NumberCoAuthors** – število souporabnikov v seji urejanja s sodelovanjem.

- **Data_Doc_PasswordFlags** – označuje nastavljene zastavice za branje ali branje/pisanje gesla.

- **Data_Doc_ReadOnlyReasons** – razlogi, zakaj je bil dokument odprt v načinu »samo za branje«.

- **Data_Doc_ResourceIdHash** – anonimni identifikator dokumenta za diagnosticiranje težav

- **Data_Doc_RtcType** – označuje, kako je bil kanal v realnem času (RTC) nastavljen za trenutno datoteko (onemogočeno, nepodprto, na zahtevo, vedno vklopljeno itn.).

- **Data_Doc_ServerDocId** – nespremenljivi anonimni identifikator dokumenta za diagnosticiranje težav 

- **Data_Doc_ServerProtocol** – različica protokola za komunikacijo s storitvijo

- **Data_Doc_ServerType** – vrsta strežnika, ki zagotavlja storitev (SharePoint, OneDrive, WOPI itd.).

- **Data_Doc_ServerVersion** – različica strežnika, ki zagotavlja storitev

- **Data_Doc_SessionId** – prepozna specifično sejo za urejanje dokumenta v celotni seji.

- **Data_Doc_SharePointServiceContext** – diagnostične informacije zahtev storitve SharePoint Online.

- **Data_Doc_SizeInBytes** – indikator velikosti dokumenta.

- **Data_Doc_SpecialChars** – indikator posebnih znakov v URL-ju dokumenta. 

- **Data_Doc_SyncBackedType** – indikator vrste dokumenta (lokalno ali storitev).

- **Data_Doc_UrlHash** – enostranska zgoščena vrednost za ustvarjanje naivnega identifikatorja dokumenta.

- **Data_Doc_WopiServiceId** – vsebuje enolični identifikator za ponudnika storitve WOPI.

- **Data_EditorDisablingRename** – identifikator prvega urejevalnika, ki je onemogočil preimenovanje

- **Data_EditorsCount** – število urednikov v dokumentov

- **Data_ForceReadWriteReason** – vrednost celega števila, ki predstavlja vzrok za vsiljeni način za branje/pisanje pri datoteki.

- **Data_FSucceededAfterRecoverableFailure** – označuje, da je bilo odpiranje uspešno po odpravi napake med odpiranjem dokumenta.

- **Data_LastLoggedTag** – enolična oznaka za mesto klica kode, ki se uporablja za prepoznavanje, ko poskušamo izvesti neuspešno odpiranje dvakrat zapored (uporablja se za diagnostiko kakovosti podatkov).

- **Data_LinkStyles** – označuje, ali povezujemo sloge predlog.

- **Data_MainPdod** – identifikator dokumenta v postopku programa Microsoft Office Word.

- **Data_Measurements** – šifriran niz z razčlenitvijo časa različnih časov odpiranja. Se uporablja za merjenje učinkovitosti delovanja.

- **Data_MoveDisabledReason** – napaka, ki onemogoča premik dokumenta.

- **Data_MoveFlightEnabled** – označuje, ali je omogočena pilotna različica za funkcijo premikanja.

- **Data_PartsUnknown** – število delov dokumenta, za katere nismo uspeli pridobiti podatkov.

- **Data_RecoverableFailureInitiationLocationTag** – enolična oznaka za mesto klica kode, ki se uporablja za prepoznavanje mesta v kodi, kjer poskušamo odpraviti napako pred odpiranjem datoteke.

- **Data_RenameDisabledReason** – napaka, ki povzroča, da je funkcija preimenovanja za ta dokument onemogočena.

- **Data_RenameFlightEnabled** – označuje, ali je omogočena pilotna različica za funkcijo preimenovanja.

- **Data_SecondaryTag** – enolična oznaka za mesto klica kode, ki se uporablja za dodajanje dodatnih podatkov o neuspehih pri odpiranju. 

- **Data_TemplateFormat** – oblika zapisa datoteke za predlogo, na kateri temelji dokument.

- **Data_UsesNormal** – označuje, ali odprti dokument temelji na navadni predlogi.

- **PathData_Doc_StreamAvailability** – indikator, ali je tok dokumenta na voljo/onemogočen.


#### <a name="officewordfileopenopenffileopenxstzcore"></a>Office.Word.FileOpen.OpenFFileOpenXstzCore

Ta dogodek ponazarja, da Microsoft Office Word odpira dokument, ki ga je uporabnik dvokliknil. Poleg tega vsebuje kritične podatke o učinkovitosti odpiranja datotek in z vidika uporabnika predstavlja dogodek za zagon aplikacije. Dogodek nadzira, ali funkcija »Odpri datoteko z dvoklikom« deluje v skladu s pričakovanji. Prav tako se uporablja za izračunane mesečne aktivne uporabnike/naprave in za metriko zanesljivosti v oblaku.

Zbrana so sledeča polja:

- **Data_AddDocTelemRes** – poroča, ali lahko pravilno dopolnimo druge vrednosti dogodka, povezane s telemetrijo dokumenta. Uporablja se za diagnostiko kakovosti podatkov
    
- **Data_BytesAsynchronous** – število bajtov (stisnjenih), brez katerega je morda mogoče odpreti datoteko, če ga pridobimo, preden uporabnik začne urejati dokument oz. se ga morda odloči shraniti.
    
- **Data_BytesAsynchronousWithWork** – število bajtov (stisnjenih), brez katerega morda lahko odpremo datoteko, vendar bi zato morali občutno spremeniti kodo.

- **Data_BytesSynchronous** – število bajtov (stisnjenih), ki ga moramo pridobiti, preden lahko odpremo datoteko.
    
- **Data_BytesUnknown** – število bajtov v delih dokumenta, za katerega menimo, da ga ne bomo našli.

- **Data_DetachedDuration** – koliko časa je bila dejavnost ločena od niti.

- **Data_Doc_AccessMode** – dokument je samo za branje/ga je mogoče urejati.

- **Data_Doc_AssistedReadingReasons** – nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

- **Data_Doc_AsyncOpenKind – ** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

- **Data_Doc_ChunkingType** – enote, uporabljene za postopno odpiranje dokumenta.

- **Data_Doc_EdpState** – nastavitev elektronske zaščite podatkov dokumenta.

- **Data_Doc_Ext** – pripona dokumenta (docx/xlsb/pptx itd.).

- **Data_Doc_FileFormat** – različica protokola za obliko zapisa datoteke.

- **Data_Doc_Fqdn** – ime domene za OneDrive ali SharePoint Online.

- **Data_Doc_FqdnHash** – enostranska zgoščena vrednost imena domene, ki omogoča identifikacijo stranke.

- **Data_Doc_IOFlags** – poroča o predpomnjenih zastavicah, uporabljenih za nastavitev možnosti zahtev za odpiranje.

- **Data_Doc_IdentityTelemetryId** – enostranska zgoščena vrednost identitete uporabnika, uporabljena za odpiranje.

- **Data_Doc_InitializationScenario** – zabeleži način odpiranja dokumenta.

- **Data_Doc_IrmRights** – dejanja, ki jih je dovolil pravilnik za elektronsko zaščito podatkov, ki velja za dokument/uporabnika.

- **Data_Doc_IsIncrementalOpen** – zastavica, ki označuje postopno odpiranje dokumenta.

- **Data_Doc_IsOcsSupported** – zastavica, ki označuje, da je storitev sodelovanja podprta v dokumentu.
    
- **Data_Doc_IsOpeningOfflineCopy** – zastavica, ki označuje, da je bila odprta kopija dokumenta brez povezave.

- **Data_Doc_IsSyncBacked** – zastavica, ki označuje, da v računalniku obstaja samodejno sinhronizirana kopija dokumenta.

- **Data_Doc_Location** – označuje, v kateri storitvi je dokument na voljo (OneDrive, File Server, SharePoint itd.).
    
- **Data_Doc_LocationDetails** – označuje, v kateri znani mapi je na voljo lokalno shranjen dokument.

- **Data_Doc_NumberCoAuthors** – število souporabnikov v seji urejanja s sodelovanjem.

- **Data_Doc_PasswordFlags** – označuje nastavljene zastavice za branje ali branje/pisanje gesla.

- **Data_Doc_ReadOnlyReasons** – razlogi, zakaj je bil dokument odprt v načinu »samo za branje«.

- **Data_Doc_ResourceIdHash** – anonimni identifikator dokumenta za diagnosticiranje težav

- **Data_Doc_RtcType** – označuje, kako je bil kanal v realnem času (RTC) nastavljen za trenutno datoteko (onemogočeno, nepodprto, na zahtevo, vedno vklopljeno itn.).

- **Data_Doc_ServerDocId** – nespremenljivi anonimni identifikator dokumenta za diagnosticiranje težav

- **Data_Doc_ServerProtocol** – različica protokola za komunikacijo s storitvijo

- **Data_Doc_ServerType** – vrsta strežnika, ki zagotavlja storitev (SharePoint, OneDrive, WOPI itd.).
    
- **Data_Doc_ServerVersion** – različica strežnika, ki zagotavlja storitev 

- **Data_Doc_SessionId** – prepozna specifično sejo za urejanje dokumenta v celotni seji.

- **Data_Doc_SharePointServiceContext** – diagnostične informacije zahtev storitve SharePoint Online.

- **Data_Doc_SizeInBytes** – indikator velikosti dokumenta.

- **Data_Doc_SpecialChars** – indikator posebnih znakov v URL-ju ali poti dokumenta.

- **Data_Doc_StreamAvailability** – indikator, ali je tok dokumenta na voljo/onemogočen.

- **Data_Doc_SyncBackedType** – indikator vrste dokumenta (lokalno ali storitev).

- **Data_Doc_UrlHash** – enostranska zgoščena vrednost za ustvarjanje naivnega identifikatorja dokumenta.

- **Data_Doc_WopiServiceId** – vsebuje enolični identifikator za ponudnika storitve WOPI.

- **Data_EditorDisablingRename** – identifikator prvega urejevalnika, ki je onemogočil preimenovanje

- **Data_EditorsCount** – število urednikov v dokumentov

- **Data_FSucceededAfterRecoverableFailure** – označuje, da je bilo odpiranje uspešno po odpravi napake med odpiranjem dokumenta.

- **Data_ForceReadWriteReason** – vrednost celega števila, ki predstavlja vzrok za vsiljeni način za branje/pisanje pri datoteki.
    
- **Data_LastLoggedTag** – enolična oznaka za mesto klica kode, ki se uporablja za prepoznavanje, ko poskušamo izvesti neuspešno odpiranje dvakrat zapored (uporablja se za diagnostiko kakovosti podatkov).

- **Data_LinkStyles** – označuje, ali povezujemo sloge predlog.

- **Data_MainPdod** – identifikator dokumenta v postopku programa Microsoft Office Word.

- **Data_Measurements** – šifriran niz z razčlenitvijo časa različnih časov odpiranja. Se uporablja za merjenje učinkovitosti delovanja.
    
- **Data_MoveDisabledReason** – napaka, ki onemogoča premik dokumenta.

- **Data_MoveFlightEnabled** – označuje, ali je omogočena pilotna različica za funkcijo premikanja.

- **Data_PartsUnknown** – število delov dokumenta, za katere nismo uspeli pridobiti podatkov.

- **Data_RecoverableFailureInitiationLocationTag** – enolična oznaka za mesto klica kode, ki se uporablja za prepoznavanje mesta v kodi, kjer poskušamo odpraviti napako pred odpiranjem datoteke.

- **Data_RenameDisabledReason** – napaka, ki povzroča, da je funkcija preimenovanja za ta dokument onemogočena.

- **Data_RenameFlightEnabled** – označuje, ali je omogočena pilotna različica za funkcijo preimenovanja.

- **Data_SecondaryTag** – enolična oznaka za mesto klica kode, ki se uporablja za dodajanje dodatnih podatkov o neuspehih pri odpiranju.

- **Data_TemplateFormat** – oblika zapisa datoteke za predlogo, na kateri temelji dokument.

- **Data_UsesNormal** – označuje, ali odprti dokument temelji na navadni predlogi.


#### <a name="officewordfileopenopenifrinitargs"></a>Office.Word.FileOpen.OpenIfrInitArgs

Ta dogodek ponazarja, da Microsoft Office Word odpira dokument s pomočjo aktivacije modula COM ali ukazne vrstice. Prav tako vsebuje kritične podatke o učinkovitosti odpiranja datotek in z vidika uporabnika predstavlja dogodek za zagon aplikacije. Dogodek nadzira, ali funkcija »Odpri datoteko iz ukazne vrstice« deluje običajno. Prav tako se uporablja za izračunane mesečne aktivne uporabnike/naprave in za metriko zanesljivosti v oblaku.

Zbrana so sledeča polja:

  - **Data\_AddDocTelemRes** – Poroča, ali lahko pravilno dopolnimo druge vrednosti dogodka, povezane s telemetrijo dokumenta. Uporablja se za diagnostiko kakovosti podatkov

  - **Data\_BytesAsynchronous –** število bajtov (stisnjenih), za katerega menimo, da lahko odpremo datoteko brez tega števila, če jih pridobimo, preden uporabnik želi začeti urejati dokument oz. ga morda shraniti

  - **Data\_BytesAsynchronousWithWork –** število bajtov (stisnjenih), pri katerem morda še lahko odpremo datoteko brez tega števila, vendar bi zato morali občutno spremeniti kodo

  - **Data\_BytesSynchronous –** število bajtov (stisnjenih), ki ga moramo pridobiti, preden lahko odpremo datoteko

  - **Data\_BytesUnknown –** število bajtov v delih dokumenta, za katerega menimo, da ga ne bomo našli

  - **Data\_Doc\_AccessMode –** dokument je samo za branje ali omogoča urejanje

  - **Data\_Doc\_AssistedReadingReasons** – Nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

  - **Data_Doc_AsyncOpenKind – ** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

  - **Data\_Doc\_ChunkingType** – Enote, ki se uporabljajo za postopno odpiranje dokumenta.

  - **Data\_Doc\_EdpState –** nastavitev elektronske zaščite podatkov dokumenta

  - **Data\_Doc\_Ext –** pripona dokumenta (docx/xlsb/pptx itd.)

  - **Data\_Doc\_FileFormat –** različica protokola za obliko zapisa dokumenta

  - **Data\_Doc\_Fqdn** – Ime domene za OneDrive ali SharePoint Online.

  - **Data\_Doc\_FqdnHash** – Enostranska zgoščena vrednost imena domene, ki omogoča identifikacijo stranke.

  - **Data\_Doc\_IOFlags –** poroča predpomnjenje zastavice za nastavitev možnosti odprtih zahtev

  - **Data\_Doc\_IdentityTelemetryId –** enosmerna razpršitev identitete uporabnika, ki je bila uporabljena za odpiranje

  - **Data\_Doc\_InitializationScenario –** zapiše način, uporabljen za odpiranje dokumenta

  - **Data\_Doc\_IrmRights** – Dejanja, ki jih je dovolil pravilnik za elektronsko zaščito dokumentov, ki velja za dokument/uporabnika.

  - **Data\_Doc\_IsIncrementalOpen** – Zastavica, ki označuje postopno odpiranje dokumenta.

  - **Data\_Doc\_IsOcsSupported** – Zastavica, ki označuje, da storitev sodelovanja podpira dokument.

  - **Data\_Doc\_IsOpeningOfflineCopy** – Zastavica, ki označuje, da je bila odprta kopija dokumenta brez povezave.

  - **Data\_Doc\_IsSyncBacked –** zastavica ponazarja, da v računalniku obstaja samodejno sinhronizirana kopija dokumenta

  - **Data\_Doc\_Location –** ponazarja storitev, ki je zagotovila dokument (OneDrive, strežnik datotek, SharePoint)

  - **Data\_Doc\_LocationDetails –** ponazarja, katera znana mapa je zagotovila lokalno shranjen dokument

  - **Data\_Doc\_NumberCoAuthors** – Število uporabnikov v skupni seji urejanja s sodelovanjem.

  - **Data\_Doc\_PasswordFlags** – Označuje nastavljeno zastavico za branje ali branje/pisanje gesla.

  - **Data\_Doc\_ReadOnlyReasons –** razlogi, zakaj je bil dokument odprt v načinu »Samo za branje«

  - **Data\_Doc\_ResourceIdHash –** anonimni identifikator dokumenta za diagnosticiranje težav

  - **Data_Doc_RtcType – **  označuje, kako je bil kanal v realnem času (RTC) nastavljen za trenutno datoteko (onemogočeno, nepodprto, na zahtevo, vedno vklopljeno itn.).

  - **Data\_Doc\_ServerDocId –** nespremenljivi anonimni identifikator dokumenta za diagnosticiranje težav

  - **Data\_Doc\_ServerProtocol –** različica protokola za komunikacijo s storitvijo

  - **Data\_Doc\_ServerType** – Vrsta strežnika, ki zagotavlja storitev (SharePoint, OneDrive, WOPI itd.).

  - **Data\_Doc\_ServerVersion –** različica strežnika, ki zagotavlja storitev

  - **Data\_Doc\_SessionId –** različica strežnika, ki zagotavlja storitev

  - **Data\_Doc\_SharePointServiceContext –** diagnostične informacije iz zahtev storitve SharePoint Online

  - **Data\_Doc\_SizeInBytes** – Indikator velikosti dokumenta.

  - **Data\_Doc\_SpecialChars** – Indikator posebnih znakov v URL-ju ali poti dokumenta.

  - **Data\_Doc\_StreamAvailability** – Indikator, ali je tok dokumenta na voljo/onemogočen.

  - **Data\_Doc\_SyncBackedType** – Indikator vrste dokumenta (lokalno ali storitev).

  - **Data\_Doc\_UrlHash** – Enostranska zgoščena vrednost za ustvarjanje naivnega identifikatorja dokumenta.

  - **Data\_Doc\_WopiServiceId –** vsebuje enolični identifikator za ponudnika storitve WOPI

  - **Data\_EditorDisablingRename –** identifikator prvega urednika, ki je onemogočil preimenovanje

  - **Data\_EditorsCount –** število urednikov v dokumentov

  - **Data\_FSucceededAfterRecoverableFailure –**  označuje, da je bilo odpiranje uspešno po odpravi napake med odpiranjem dokumenta

  - **Data\_ForceReadWriteReason –** vrednost celega števila, ki predstavlja vzrok za vsiljeni način za branje/pisanje

  - **Data\_LastLoggedTag –** enolična oznaka za mesto klica kode, ki se uporablja za prepoznavanje, ko poskušamo izvesti neuspešno odpiranje dvakrat zapored (se uporablja za diagnostiko kakovosti podatkov)

  - **Data\_LinkStyles –** označuje, ali povezujemo sloge predlog

  - **Data\_MainPdod –** identifikator dokumenta v postopku programa Microsoft Office Word

  - **Data\_Measurements –** šifriran niz z razčlenitvijo časa različnih časov odpiranja. Uporablja se za diagnosticiranje uspešnost pri odpiranju

  - **Data\_MoveDisabledReason –** napaka, ki onemogoča premik dokumenta

  - **Data\_MoveFlightEnabled –** ali je omogočen let za funkcijo premikanja

  - **Data\_PartsUnknown –** število delov dokumenta, za katere nismo uspeli pridobiti podatkov

  - **Data\_RecoverableFailureInitiationLocationTag –** enolična oznaka za mesto klica kode, ki se uporablja za prepoznavanje mesta v kodi, kjer smo poskušali odpraviti napako pred odpiranjem datoteke

  - **Data\_RenameDisabledReason –** napaka, ki povzroča, da je funkcija preimenovanja za ta dokument onemogočena

  - **Data\_RenameFlightEnabled –** ali je omogočen let za funkcijo preimenovanja

  - **Data\_SecondaryTag –** enolična oznaka za mesto klica kode, ki se uporablja za dodajanje dodatnih podatkov o neuspehih za odpiranje

  - **Data\_TemplateFormat –** oblika zapisa datoteke za predlogo, na kateri temelji dokument

  - **Data\_UsesNormal –** ponazarja, ali je osnova odprtega dokumenta predstavlja običajna predloga


#### <a name="officewordfileopenopenloadfile"></a>Office.Word.FileOpen.OpenLoadFile

Ta dogodek ponazarja, da Microsoft Office Word odpira dokument s pomočjo pogovornega okna za odpiranje Poleg tega vsebuje kritične podatke o učinkovitosti odpiranja datotek in z vidika uporabnika predstavlja dogodek za zagon aplikacije. Dogodek nadzira, ali funkcija »Odpri datoteko v pogovornem oknu za odpiranje datotek« deluje v skladu s pričakovanji. Prav tako se uporablja za izračunane mesečne aktivne uporabnike/naprave in za metriko zanesljivosti v oblaku.

Zbrana so sledeča polja:

- **Data_AddDocTelemRes** – poroča, ali lahko pravilno dopolnimo druge vrednosti dogodka, povezane s telemetrijo dokumenta. Uporablja se za diagnostiko kakovosti podatkov.

- **Data_BytesAsynchronous** – število bajtov (stisnjenih), brez katerega je morda mogoče odpreti datoteko, če ga pridobimo, preden uporabnik začne urejati dokument oz. se ga morda odloči shraniti.

- **Data_BytesAsynchronousWithWork** – število bajtov (stisnjenih), brez katerega morda lahko odpremo datoteko, vendar bi zato morali občutno spremeniti kodo.
    
- **Data_BytesSynchronous** – število bajtov (stisnjenih), ki ga moramo pridobiti, preden lahko odpremo datoteko.

- **Data_BytesUnknown** – število bajtov v delih dokumenta, za katerega menimo, da ga ne bomo našli.

- **Data_DetachedDuration** – koliko časa je bila dejavnost ločena od niti.

- **Data.Doc.AccessMode** – dokument je samo za branje/ga je mogoče urejati.

- **Data_Doc_AssistedReadingReasons** – nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

- **Data_Doc_AsyncOpenKind – ** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

- **Data_Doc_ChunkingType** – enote, uporabljene za postopno odpiranje dokumenta.

- **Data_Doc_EdpState** – nastavitev elektronske zaščite podatkov dokumenta.

- **Data_Doc_Ext** – pripona dokumenta (docx/xlsb/pptx itd.).

- **Data_Doc_FileFormat** – različica protokola za obliko zapisa datoteke.

- **Data_Doc_Fqdn** – ime domene za OneDrive ali SharePoint Online.

- **Data_Doc_FqdnHash** – enostranska zgoščena vrednost imena domene, ki omogoča identifikacijo stranke.

- **Data_Doc_IdentityTelemetryId** – enostranska zgoščena vrednost identitete uporabnika, uporabljena za odpiranje.

- **Data_Doc_InitializationScenario** – zabeleži način odpiranja dokumenta.

- **Data_Doc_IOFlags** – poroča o predpomnjenih zastavicah, uporabljenih za nastavitev možnosti zahtev za odpiranje.

- **Data_Doc_IrmRights** – dejanja, ki jih je dovolil pravilnik za elektronsko zaščito podatkov, ki velja za dokument/uporabnika.
    
- **Data_Doc_IsIncrementalOpen** – zastavica, ki označuje postopno odpiranje dokumenta.

- **Data_Doc_IsOcsSupported** – zastavica, ki označuje, da je storitev sodelovanja podprta v dokumentu.

- **Data_Doc_IsOpeningOfflineCopy** – zastavica, ki označuje, da je bila odprta kopija dokumenta brez povezave.

- **Data_Doc_IsSyncBacked** – zastavica, ki označuje, da v računalniku obstaja samodejno sinhronizirana kopija dokumenta.

- **Data_Doc_Location** – označuje, v kateri storitvi je dokument na voljo (OneDrive, File Server, SharePoint itd.).

- **Data_Doc_LocationDetails** – označuje, v kateri znani mapi je na voljo lokalno shranjen dokument.

- **Data_Doc_NumberCoAuthors** – število souporabnikov v seji urejanja s sodelovanjem.

- **Data_Doc_PasswordFlags** – označuje nastavljene zastavice za branje ali branje/pisanje gesla.

- **Data_Doc_ReadOnlyReasons** – razlogi, zakaj je bil dokument odprt v načinu »samo za branje«.

- **Data_Doc_ResourceIdHash** – anonimni identifikator dokumenta za diagnosticiranje težav

- **Data_Doc_RtcType** – označuje, kako je bil kanal v realnem času (RTC) nastavljen za trenutno datoteko (onemogočeno, nepodprto, na zahtevo, vedno vklopljeno itn.).

- **Data_Doc_ServerDocId** – nespremenljivi anonimni identifikator dokumenta za diagnosticiranje težav 

- **Data_Doc_ServerProtocol** – različica protokola za komunikacijo s storitvijo

- **Data_Doc_ServerType** – vrsta strežnika, ki zagotavlja storitev (SharePoint, OneDrive, WOPI itd.).

- **Data_Doc_ServerVersion** – različica strežnika, ki zagotavlja storitev

- **Data_Doc_SessionId** – prepozna specifično sejo za urejanje dokumenta v celotni seji.

- **Data_Doc_SharePointServiceContext** – diagnostične informacije zahtev storitve SharePoint Online.

- **Data_Doc_SizeInBytes** – indikator velikosti dokumenta.

- **Data_Doc_SpecialChars** – indikator posebnih znakov v URL-ju ali poti dokumenta.

- **Data_Doc_StreamAvailability** – indikator, ali je tok dokumenta na voljo/onemogočen.

- **Data_Doc_SyncBackedType** – indikator vrste dokumenta (lokalno ali storitev).

- **Data_Doc_UrlHash** – enostranska zgoščena vrednost za ustvarjanje naivnega identifikatorja dokumenta.

- **Data_EditorDisablingRename** – identifikator prvega urejevalnika, ki je onemogočil preimenovanje

- **Data_EditorsCount** – število urednikov v dokumentov

- **Data_ForceReadWriteReason** – vrednost celega števila, ki predstavlja vzrok za vsiljeni način za branje/pisanje pri datoteki.
    
- **Data_FSucceededAfterRecoverableFailure** – označuje, da je bilo odpiranje uspešno po odpravi napake med odpiranjem dokumenta.

- **Data_LastLoggedTag** – enolična oznaka za mesto klica kode, ki se uporablja za prepoznavanje, ko poskušamo dvakrat zapored neuspešno izvesti shranjevanje (se uporablja za diagnostiko kakovosti podatkov)

- **Data_LinkStyles** – označuje, ali povezujemo sloge predlog.

- **Data_MainPdod** – identifikator dokumenta v postopku programa Microsoft Office Word.

- **Data_Measurements** – šifriran niz z razčlenitvijo časa različnih časov odpiranja. Se uporablja za merjenje učinkovitosti delovanja.

- **Data_MoveDisabledReason** – napaka, ki onemogoča premik dokumenta.

- **Data_MoveFlightEnabled** – označuje, ali je omogočena pilotna različica za funkcijo premikanja.

- **Data_PartsUnknown** – število delov dokumenta, za katere nismo uspeli pridobiti podatkov.

- **Data_RecoverableFailureInitiationLocationTag** – enolična oznaka za mesto klica kode, ki se uporablja za prepoznavanje mesta v kodi, kjer poskušamo odpraviti napako pred odpiranjem datoteke.

- **Data_RenameDisabledReason** – napaka, ki povzroča, da je funkcija preimenovanja za ta dokument onemogočena.

- **Data_RenameFlightEnabled** – označuje, ali je omogočena pilotna različica za funkcijo preimenovanja.

- **Data_SecondaryTag** – enolična oznaka za mesto klica kode, ki se uporablja za dodajanje dodatnih podatkov o neuspehih pri odpiranju.

- **Data_TemplateFormat** – oblika zapisa datoteke za predlogo, na kateri temelji dokument

- **Data_UsesNormal** – označuje, ali odprti dokument temelji na navadni predlogi.


#### <a name="renewuserop"></a>RenewUserOp

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij.  Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede operacija obnovitve uporabniških dovoljenj. 

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se program izvaja v produkcijskem okolju ali v okolju razvijalcev

- **AppInfo.Name** – ime aplikacije.

- **AppInfo.Version** – različica aplikacije

- **iKey** – ID strežnika Logger 

- **RMS.ApplicationScenarioId** – ID scenarija, ki ga je posredovala aplikacija

- **RMS.Duration** – Skupen čas za izvedbo operacije

- **RMS.DurationWithoutExternalOps** – skupni čas minus zunanje operacije, kot je zakasnitev omrežja.

- **RMS.ErrorCode** – koda napake je vrnjena, če izvira iz operacije

- **RMS.HttpCall** – označite, ali je prišlo do operacije HTTP

- **RMS.LicenseFormat** – oblika licence: Xrml ali Json

- **RMS.Result** – uspeh ali neuspeh operacije

- **RMS.ScenarioId** – ID scenarija, ki ga je določil odjemalec storitve za upravljanje pravic

- **RMS.SDKVersion** – različica odjemalca storitve za upravljanje pravic

- **RMS.ServerType** – vrsta strežnika za upravljanje pravic do storitev 

- **RMS.StatusCode** – koda stanja rezultata operacije

- **RMS.Type** – vrsta uporabniških informacij

#### <a name="servicediscoveryop"></a>ServiceDiscoveryOp

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij.  Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede operacija odkrivanja. 

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se program izvaja v produkcijskem okolju ali v okolju razvijalcev

- **AppInfo.Name** – ime aplikacije.

- **AppInfo.Version** – različica aplikacije

- **iKey** – ID strežnika za storitev pisanja dnevnika

- **RMS.ApplicationScenarioId** – ID scenarija, ki ga je posredovala aplikacija

- **RMS.Duration** – Skupen čas za izvedbo operacije

- **RMS.DurationWithoutExternalOps** – skupni čas minus zunanje operacije, kot je zakasnitev omrežja.

- **RMS.ErrorCode** – koda napake je vrnjena, če izvira iz operacije

- **RMS.HttpCall** – označite, ali je prišlo do operacije HTTP

- **RMS.LicenseFormat** – oblika licence: Xrml ali Json

- **RMS.OperationName** – ime operacije

- **RMS.Result** – uspeh ali neuspeh operacije

- **RMS.ScenarioId** – ID scenarija, ki ga je določil odjemalec storitve za upravljanje pravic

- **RMS.SDKVersion** – različica odjemalca storitve za upravljanje pravic

- **RMS.ServerType** – vrsta strežnika za upravljanje pravic do storitev 

- **RMS.StatusCode** – koda stanja rezultata operacije


### <a name="office-accessibility-configuration-subtype"></a>*Podvrsta konfiguracije za dostopnost v Officeu*

Officeove funkcije dostopnosti

#### <a name="officeaccessibilityaccessibilitytoolsessionpresencewin32"></a>Office.Accessibility.AccessibilityToolSessionPresenceWin32

Omogoča nam, da odkrijemo uporabnikovo orodje za pomoč uporabnikom s posebnimi potrebami in njegovo ime. S pomočjo tega dogodka vidimo, ali ima Officeov uporabnik težave z določenim orodjem za pomoč uporabnikov s posebnimi potrebami.

Zbrana so sledeča polja:

  - **Data\_Data\_Jaws –** ponazarja, ali se je med sejo uporabljal bralnik Jaws**Data\_Data\_Magic –** ponazarja, ali se je med sejo uporabljalo orodje Magic

  - **Data\_Data\_Magnify –** ponazarja, ali se je med sejo uporabljajo orodje povečave

  - **Data\_Data\_Narrator –** ponazarja, ali se je med sejo uporabljal pripovedovalec

  - **Data\_Data\_NVDA –** ponazarja, ali se je med sejo uporabljajo orodje NVDA

  - **Data\_Data\_SA –** ponazarja, ali se je med sejo uporabljajo orodje SA

  - **Data\_Data\_Supernova –** ponazarja, ali se je med sejo uporabljajo orodje Supernova

  - **Data\_Data\_SuperNovaessSuite –** ponazarja, ali se je med sejo uporabljajo orodje SuperNovaAccessSuite

  - **Data\_Data\_WinEyes –** ponazarja, ali se je med sejo uporabljajo orodje WinEyes

  - **Data\_Data\_ZoomText –** ponazarja, ali se je med sejo uporabljajo orodje ZoomText

#### <a name="officewordaccessibilitylearningtoolsreadaloudplayreadaloud"></a>Office.Word.Accessibility.LearningTools.ReadAloud.PlayReadAloud

Ta dogodek ponazarja, da Microsoft Office Word naglas bere besedilo dokumenta. Dogodek predstavlja signal obveščanja o izvajanju funkcije dostopnosti, ki Microsoftu omogoča, da ovrednoti stanje storitve branja besedila naglas.

Zbrana so sledeča polja:

  - **Data\_CharacterCount –** število znakov v dokumentu

  - **Data\_CharactersWithSpaceCount –** število znakov s presledki v dokumentu

  - **Data\_IsPageCountInProgress –** ali se izvaja štetje strani

  - **Data\_LineCount –** število vrstic v dokumentu

  - **Data\_PageCount –** število strani v dokumentu

  - **Data\_ParagraphCount –** število odstavkov v dokumentu

  - **Data\_Play –** ali Word prvič bere dokument naglas

  - **Data\_ViewKind –** vrsta pogleda v dokumentu

  - **Data\_WordCount –** število besed v dokumentu

#### <a name="officewordaccessibilitylearningtoolsreadaloudstopreadaloud"></a>Office.Word.Accessibility.LearningTools.ReadAloud.StopReadAloud

Ta dogodek ponazarja, da je Microsoft Office Word prenehal naglas brati besedilo dokumenta. Microsoft uporabi ta dogodek za ovrednotenje stanja funkcije branja besedila naglas tako, da izmeri trajanje izvajanja.

Zbrana so sledeča polja:

  - Brez

### <a name="privacy-subtype"></a>*Podvrsta zasebnosti*

Nastavitve zasebnosti za Office 

#### <a name="officeintelligentserviceprivacyconsentprivacyevent"></a>Office.IntelligentService.PrivacyConsent.PrivacyEvent

Ta dogodek predstavlja dejanje uporabnika ali sistema, ki je del uporabniške izkušnje z zasebnostjo za Office. Aktivira se v pogovornih oknih zasebnosti ob prvem zagonu, pogovornem oknu zasebnosti računa in obvestilih o zasebnosti. Dogodek se uporablja za naslednje: razumevanje soglasja uporabnikov za nastavitve zasebnosti za Office, uporabnikovo spreminjanje nastavitev zasebnosti za Office in za posodabljanje nastavitev zasebnosti za Office v uporabniških sejah.

Zbrana so sledeča polja:

  - **Data_ActionId –** dejanje uporabnika v pogovornem oknu zasebnosti

  - **Data_ControllerConnectedServicesState –** nastavitev pravilnika uporabnika za dodatne izbirne povezane izkušnje

  - **Data_DownloadedContentServiceGroupState –** nastavitev uporabnika za preneseno vsebino 
 
  - **Data_ForwardLinkId –** povezava do dokumentacije o zasebnosti za scenarij uporabnika

  - **Data_HRESULT –** zapisovanje napak med interakcijo v pogovornem oknu zasebnosti

  - **Data_IsEnterpriseUser –** kategorija licenc uporabnikov

  - **Data_OfficeServiceConnectionState –** nastavitev uporabnika za povezane storitve

  - **Data_RecordRegistry –** zapis, ki prikazuje pogovorno okno zasebnosti podjetja

  - **Data_Scenario –** prvi scenarij, izveden glede na licenco uporabnika in kategorijo

  - **Data_SeenInsidersDialog –** zapis, ki prikazuje pogovorno okno zasebnosti za člane programa Insider

  - **Data_SendTelemetryOption –** nastavitev uporabnika za telemetrijo

  - **Data_SendTelemetryOptionPolicy –** nastavitev pravilnika uporabnika za telemetrijo

  - **Data_UserCategory –** vrsta uporabniškega računa  

  - **Data_UserCCSDisabled –** preglasitev uporabnika za dodatne izbirne povezane izkušnje

   - **Data_UserContentServiceGroupState –** nastavitev uporabnika za analizo vsebine

  - **Data_WillShowDialogs –** zapis uporabnika, zahtevan pri pogovornih oknih zasebnosti ob prvem zagonu



## <a name="product-and-service-performance-data-events"></a>Dogodki podatkov o učinkovitosti delovanja izdelkov in storitev

V nadaljevanju tega članka so navedene podvrste podatkov v tej kategoriji:
- [Nepričakovan izhod iz aplikacije (zrušitev)](#unexpected-application-exit-crash-subtype)
- [Učinkovitost delovanja funkcije aplikacije](#application-feature-performance-subtype)
- [Napaka pri dejavnosti aplikacije](#application-activity-error-subtype)

### <a name="unexpected-application-exit-crash-subtype"></a>*Podvrsta nepričakovanega izhoda iz aplikacije (zrušitev)*

Aplikacija se nepričakovano zapre in stanje te aplikacije, ko pride do tega.

#### <a name="officeappdomainunhandledexceptionhandlerfailed"></a>Office.AppDomain.UnhandledExceptionHandlerFailed

Zbira informacije za morebitne neobravnavane izjeme z orodjem za pretakanje podatkov. Ti podatki se uporabljajo za nadzor stanja aplikacije. Ta dogodek ustvari Microsoftovo orodje za pretakanje podatkov za Excelov dodatek.

Zbrana so sledeča polja:

- **Exception** – nabor klicev za izjemo

- **Event Name** – kategorija dogodka in oznaka dogodka predstavljata ime dogodka

#### <a name="officeapplesystemhealthappexitmacandios"></a>Office.Apple.SystemHealthAppExitMacAndiOS

Dogodek ob zagonu, ki zajame nemotena in motena zapiranja aplikacije za nadaljnjo preiskavo.

Zbrana so naslednja polja:

- **AffectedProcessResidentMemoryOnCrash** – pomnilnik, v katerem je shranjena zrušena aplikacija.

- **AffectedProcessSessionID** – »SessionID« postopka pri prejšnjem zapiranju.

- **AffectedProcessUnsymbolicatedChecksum** – uporablja se z zgoščeno vrednostjo sklada za simbolizacijo.

- **AffectedProcessVirtualMemoryOnCrash** – navidezni pomnilnik zrušene aplikacije.

- **AffectedSessionBuildNumber** – različica aplikacije

- **AffectedSessionDuration** – trajanje seje v sekundah pred zrušitvijo.

- **AffectedSessionIDSMatch** – logična vrednost za preverjanje, ali je ID seje poročanja enak kot tisti, ki ga sprejme MERP.

- **AffectedSessionLongBuildNumber** –dolga številka graditve.

- **AffectedSessionMERPSessionID** – ID seje za MERP.

- **AffectedSessionOSLocale** – območne nastavitve operacijskega sistema.

- **AffectedSessionOSVersion** – različica operacijskega sistema.

- **AffectedSessionStackHash** – zgoščena vrednost sledi sklada zrušene aplikacije.

- **AffectedSessionStartTime** – »DateTime« začetka seje.

- **AffectedSessionUAEType** – oštevilčenje, ki zagotavlja informacije o tem, do kakšne vrste zrušitve je prišlo.

- **AffectedSessionVersion** – različica aplikacije.

- **DeviceModel** – model strojne opreme.

- **ExitWasGraceful** – ali je bilo prejšnje zapiranje aplikacije nemoteno?

#### <a name="officeextensibilitycomaddinunhandledexception"></a>Office.Extensibility.COMAddinUnhandledException

Dogodek, ustvarjen ob zrušitvah dodatka COM v potrošniški različici Officeovih aplikacij. 

Uporaba: uporablja se za izračun globalnega »sprejetja« Office 365 ProPlus (ni omejeno na podjetje) za dodatek, objavljen na spletnem mestu readyforwindows.com, in druga orodja, kot je komplet orodij Readiness. S tem lahko poslovne stranke preverijo, če so dodatki, ki so bili uvedeni v njihovih podjetjih, združljivi z najnovejšimi različicami sistema Office 365 ProPlus, in ustrezno načrtujejo njihove nadgradnje. 

Zbrana so sledeča polja:

- **ScopeId** – obseg trenutne niti

- **Method** – Officeov način, kjer je prišlo do izjeme

- **Interface** – Officeov vmesnik, kjer je prišlo do izjeme

- **AddinId** – ID razreda za dodatek

- **AddinProgId** – zastarelo.

- **AddinFriendlyName** – zastarelo.

- **AddinTimeDateStamp** – časovni žig dodatka iz metapodatkov DLL.

- **AddinVersion** – zastarelo.

- **AddinFileName** – zastarelo.

- **VSTOAddIn** – ali je dodatek vrste VSTO

- **AddinConnectFlag** – vedenje trenutnega nalaganja

- **LoadAttempts** – število poskusov za nalaganje izdelka

#### <a name="officeextensibilitycomaddinunhandledexceptionenterprise"></a>Office.Extensibility.COMAddinUnhandledExceptionEnterprise

Dogodek, ustvarjen ob zrušitvah dodatka COM v poslovni različici Officeovih aplikacij.

Uporaba: uporablja se za izračun globalnega »sprejetja« Office 365 ProPlus (ni omejeno na podjetje) za dodatek, objavljen na spletnem mestu readyforwindows.com, in druga orodja, kot je komplet orodij Readiness. S tem lahko poslovne stranke preverijo, če so dodatki, ki so bili uvedeni v njihovih podjetjih, združljivi z najnovejšimi različicami sistema Office 365 ProPlus, in ustrezno načrtujejo njihove nadgradnje. 

- **ScopeId** – obseg trenutne niti

- **Method** – Officeov način, kjer je prišlo do izjeme

- **Interface** – Officeov vmesnik, kjer je prišlo do izjeme

- **AddinId** – ID razreda za dodatek

- **AddinProgId** – zastarelo.

- **AddinFriendlyName** – zastarelo.

- **AddinTimeDateStamp** – časovni žig dodatka iz metapodatkov DLL.

- **AddinVersion** – zastarelo.

- **AddinFileName** – zastarelo.

- **VSTOAddIn** – ali je dodatek vrste VSTO

- **AddinConnectFlag** – vedenje trenutnega nalaganja

- **LoadAttempts** – število poskusov za nalaganje izdelka

#### <a name="officeextensibilitysandboxodpactivationheartbeat"></a>Office.Extensibility.Sandbox.ODPActivationHeartbeat

Dodatki za Office se zaženejo v peskovniku. Ta dogodek zbira informacije o signalih obveščanja o izvajanju programa ob aktiviranjih. Ko pride do zrušitve dodatka, ta dogodek zbira podatke o tem, zakaj je prišlo do zrušitve v primeru, ki je povezan z našim peskovnikom. Uporablja se za preiskovanje, ko stranke stopnjujejo težave.
 
Zbrana so naslednja polja:

- **AppId** – ID aplikacije

- **AppInfo** – podatki glede vrste dodatka (podokno opravil ali UILess ali znotraj vsebine itd.) in vrste ponudnika (Omen, SharePoint, datotečni sistem itd.).

- **AppInstanceId** – ID primerka aplikacije 

- **AssetId** – ID sredstva aplikacije

- **ErrorCode** – skupni porabljeni čas. 

- **NumberOfAddinsActivated** – števec aktiviranih dodatkov

- **RemoterType** – določa vrsto remoterja (zaupanja vreden, ni vreden zaupanja, Win32webView, zaupanja vreden UDF itd.), ki se uporablja za aktiviranje dodatka

- **StoreType** – izvor aplikacije

#### <a name="officeextensibilityvbatelemetrybreak"></a>Office.Extensibility.VbaTelemetryBreak

Dogodek, ki se ustvari, ko datoteka z omogočenimi makri naleti na napako pri prevajanju ali izvajanju.

Namizna analitika: uporablja se kot števec pri izračunu stanja poslovnih funkcij za vrste makrov (npr. Wordovi makri, Excelovi makri itd.), ki se uporabljajo za določitev, ali je med pilotnim projektom dodatek »pripravljen na nadgradnjo« v proizvodnem ciklu.

Zbrana so sledeča polja:

- **TagId** – ID oznake za telemetrijo

- **BreakReason** – razlog za prekinitev (napaka pri izvajanju, prevajanju ali druga napaka.)

- **SolutionType** – vrsta rešitve (dokument, predloga, dodatek aplikacije, dodatek COM)

- **Data.ErrorCode** – koda napake, ki jo je zaznal mehanizem VBA


#### <a name="officefindtimeappfailedtostart"></a>Office.FindTime.AppFailedToStart

Podatki so zbrani, če aplikacije ni mogoče zagnati zaradi nepričakovane napake med zagonom. S tem dogodkom spremljamo izjeme in zrušitve.  Omogoča lažje spremljanje ustreznosti stanja aplikacije in odpravljanje napak.

Zbrana so naslednja polja: 

- **DateTime** – časovni žig trenutka, ko je bil dogodek zabeležen.

- **EventName** – ime zabeleženega dogodka.

#### <a name="officeoutlookdesktophangbucketmetrics"></a>Office.Outlook.Desktop.HangBucketMetrics

Zbira informacije o neodzivnosti v Outlooku – enolični identifikator za posamezne dogodke neodzivnosti, pretečeni čas in informacije o naboru klicev. Podatki se uporabljajo za zaznavanje in prepoznavanje zrušitev informacij, zahtevanih za odpravljanje napak v bodočih posodobitvah.

Zbrana so sledeča polja:

  - **BucketId** – razpršitev nabora klicev

  - **ElapsedTotal** – skupni čas, porabljen za klic

  - **ElapsedHanging** – čas neodzivnosti klica

#### <a name="officeoutlookdesktophangreportingscopeperfmetrics"></a>Office.Outlook.Desktop.HangReportingScopePerfMetrics

Zbira podatke o času, zahtevane za ključne scenarije v Outlooku – switchfolder switchmodule, sendmailoutbox, openitemclassic, sendmailtransport. Ti podatki so aktivno nadzorovani proti nenavadnim težavam z učinkovitostjo delovanja. Uporabljajo se za zaznavanje in diagnosticiranje težav z učinkovitostjo delovanja ter izboljšanje učinkovitosti delovanja v bodočih posodobitvah.

Zbrana so sledeča polja:

  - **ElapsedTotal** – skupni čas, porabljen za ta klic

  - **ScopeId** – ime funkcije, ki vsebuje deklaracijo ali ime po meri, podeljen prek definicije obsega

#### <a name="officeoutlookdesktopwatsonbuckets"></a>Office.Outlook.Desktop.WatsonBuckets

To pravilo zbira informacije o zrušitvi iz dnevnikov dogodkov, ko se je zrušil Outlook v prejšnji seji.

Ti podatki so aktivno nadzorovani proti nenavadnim neodzivnostim. Uporabljajo se za zaznavanje in prepoznavanje neodzivnosti, zahtevanih za odpravljanje napak v bodočih posodobitvah.

Zbrana so sledeča polja:

  - **BucketId** – razpršitev nabora klicev

  - **ElapsedTotal** – skupni čas, porabljen za klic

  - **ElapsedHanging** – čas neodzivnosti klica

#### <a name="officepowerpointsession"></a>Office.PowerPoint.Session

Zbiranje uporab funkcije v posameznih PowerPointovih sejah. Ti podatki se uporabljajo za izračun razmerja neprimernih izhodov iz PowerPointa med uporabo funkcije. Razmerje neprimernih izhodov iz PowerPointa predstavlja poglavitni signal za zagotovitev, da PowerPoint ne deluje po pričakovanjih.

Zbrana so sledeča polja:

  - **Flag** – zastavice sej

  - **Usage** – uporabe funkcij

#### <a name="officepowerpointuaedialog"></a>Office.PowerPoint.UAE.Dialog

Ti podatki so zbrani vsakič, ko se PowerPoint neprimerno zapre, ko je prikazano pogovorno okno na vrhu glavnega okna v PowerPointu. Te informacije so ključnega pomena za zaznavanje neprimernih izhodov iz PowerPointa, ki jih povzroči aktivno pogovorno okno, ki blokira glavno okno v PowerPointu. Microsoft s temi podatki diagnosticira težave in tako zagotovi pravilno delovanje PowerPointa.

Zbrana so sledeča polja:

  - **DlgCnt** – skupno število odprtih pogovornih oken ob zrušitvi seje

  - **DlgId** – identifikator odprtega pogovornega okna

  - **IdType** – vrsta identifikatorja odprtega pogovornega okna

  - **InitTime** – čas inicializacije zrušene seje

  - **SessionId** – identifikator zrušene seje

  - **TopId** – identifikator zgornjega pogovornega okna

  - **Version** – različica zrušene seje

#### <a name="officepowerpointuaedocument"></a>Office.PowerPoint.UAE.Document

Dogodek, ki zbira podatke o funkciji, ki je bila uporabljena v dokumentu, ko je prišlo do nenavadnega izhoda iz PowerPointa. Te funkcije vključujejo diaprojekcijo, odpiranje, shranjevanje, urejanje in soavtorstvo dokumenta ter zaustavitev. Te informacije so ključnega pomena za zaznavanje nenavadnih izhodov iz PowerPointa med uporabo funkcije. Microsoft s temi podatki diagnosticira težave in tako zagotovi pravilno delovanje PowerPointa.

Zbrana so sledeča polja:

  - **CoauthFlag** – zastavice za uporabo soavtorstva

  - **CommandFlag** – zastavice za spreminjanje dokumenta

  - **FileIOFlag** – zastavice za uporabo V-/I-datoteke

  - **InitTime** – čas inicializacije zrušene seje

  - **Location** – mesto dokumenta

  - **ServerDocId** – identifikator dokumenta v strežniku

  - **SessionId** – identifikator zrušene seje

  - **UrlHash** – razpršitev IURL-ja dokumenta

  - **Usage** – uporabe funkcij

  - **Version** – različica zrušene seje

#### <a name="officepowerpointuaeopen"></a>Office.PowerPoint.UAE.Open

Zbiranje podatkov vsakič, ko se PowerPoint neprimerno zapre med odpiranje dokumenta. Te informacije so ključnega pomena za zaznavanje nenavadnih izhodov iz PowerPointa med odpiranjem dokumenta. Microsoft s temi podatki diagnosticira težave in tako zagotovi pravilno delovanje PowerPointa.

Zbrana so sledeča polja:

  - **FileUrlLocation** – mesto za URL dokumenta

  - **Flag** – odprte zastavice

  - **InitTime** – čas inicializacije zrušene seje

  - **Location** – mesto dokumenta

  - **OpenReason** – razlog za odpiranje

  - **ServerDocId** – identifikator dokumenta v strežniku

  - **SessionId** – identifikator zrušene seje

  - **UrlHash** – razpršitev IURL-ja dokumenta

  - **Version** – različica zrušene seje

#### <a name="officepowerpointuaesession"></a>Office.PowerPoint.UAE.Session

Zbiranje podatkov o funkciji, ki je bila uporabljena, ko se je PowerPointova seja nenavadno končala.  Te informacije so ključnega pomena za zaznavanje nenavadnih izhodov iz PowerPointa. Microsoft s temi podatki diagnosticira težave in tako zagotovi pravilno delovanje PowerPointa.

Zbrana so sledeča polja:

  - **Flag** – zastavice sej

  - **InitTime** – čas inicializacije zrušene seje

  - **PreviousSessionId** – identifikator zrušene seje

  - **Usage** – uporabe funkcij

  - **Version** – različica zrušene seje

#### <a name="officepowerpointuaeshutdown"></a>Office.PowerPoint.UAE.Shutdown

Zbiranje podatkov o nenavadnih izhodih iz PowerPointa med zaustavitvijo. Te informacije so ključnega pomena za zaznavanje nenavadnih izhodov iz PowerPointa med zaustavitvijo. Microsoft s temi podatki diagnosticira težave in tako zagotovi pravilno delovanje PowerPointa.

Zbrana so sledeča polja:

  - **InitTime** – čas inicializacije zrušene seje

  - **SessionId** – identifikator zrušene seje

  - **Stage** – stopnja zaustavitve

  - **Version** – različica zrušene seje

#### <a name="officepowerpointuaeslideshow"></a>Office.PowerPoint.UAE.SlideShow

Zbiranje podatkov o nenavadnih izhodih iz PowerPointa med zaustavitvijo. Te informacije so ključnega pomena za zaznavanje nenavadnih izhodov iz PowerPointa med zaustavitvijo. Microsoft s temi podatki diagnosticira težave in tako zagotovi pravilno delovanje PowerPointa.

Zbrana so sledeča polja:

  - **InitTime** – čas inicializacije zrušene seje

  - **Mode** – način diaprojekcije

  - **SessionId** – identifikator zrušene seje

  - **State** – stanje diaprojekcije

  - **Version** – različica zrušene seje

#### <a name="officeprogrammabilitytelemetryaddincrash"></a>Office.Programmability.Telemetry.AddInCrash

Dogodek, ki se ustvari pri nalaganju dodatka COM. Te informacije so ključnega pomena za določanje, ali je dodatek povzročil zrušitev Officeove aplikacije. Uporablja se za ocenjevanje globalne združljivosti izdelkov v Officeovih aplikacijah.

Zbrana so sledeča polja:

  - **CLSID** – identifikator za razred dodatka

  - **ConnectFlag** – trenutno vedenje pri nalaganju dodatka

  - **FileName** – ime datoteke za dodatek brez poti datoteke

  - **FriendlyName** – prijazno ime dodatka

  - **Interface** – Officeov vmesnik, kjer je prišlo do izjeme

  - **LoadAttempts** – število poskusov za nalaganje izdelka

  - **Method** – Officeov način, kjer je prišlo do izjeme

  - **OfficeApplication** – Officeova aplikacija, v kateri je bila zaznana izjema

  - **OfficeVersion** – različice sistema Office

  - **ProgID** – identifikator programa za dodatek

#### <a name="officeprogrammabilitytelemetrymacrofileopened"></a>Office.Programmability.Telemetry.MacroFileOpened 

Sproženo ob odpiranju makra (VBA), ki vsebuje datoteko v napravi, katere uporabo je IT skrbnik omogočil v Officeovih aplikacijah kot storitev (OAAS), in kjer je bil aktiviran Office 365 ProPlus z licenco podjetja. Dogodek se uporablja za razumevanje stanja dokumentov, ki vsebujejo makro (VBA) v najemniku in se primerja z Office.Programmability.Telemetry.VbaTelemetryBreak, ki sledi napakam v datotekah, ki vsebujejo VBA. 

Nobena polja niso izbrana.

#### <a name="officesystemsystemhealthungracefulappexitmacandios"></a>Office.System.SystemHealthUngracefulAppExitMacAndiOS

Dogodek ob zagonu, ki zajame motena zapiranja aplikacije za nadaljnjo preiskavo.

Zbrana so naslednja polja:

- **AffectedProcessAppBuild** – številka graditve.

- **AffectedProcessAppBuildRevision** – številka pregleda graditve.

- **AffectedProcessAppMajorVer** – številka glavne različice aplikacije.

- **AffectedProcessAppMinorVer** – številka podrazličice aplikacije.

- **AffectedProcessAppName** – ime aplikacije.

- **AffectedProcessResidentMemoryOnCrash** – pomnilnik, v katerem je shranjena zrušena aplikacija.

- **AffectedProcessUnsymbolicatedChecksum** – uporablja se z zgoščeno vrednostjo sklada za simbolizacijo.

- **AffectedProcessVirtualMemoryOnCrash** – navidezni pomnilnik zrušene aplikacije.

- **AffectedSessionDuration** – trajanje seje v sekundah pred zrušitvijo.

- **AffectedSessionLongBuildNumber** –dolga številka graditve.

- **CrashedProcessSessionID** – »SessionID« postopka pri zrušitvi aplikacije.

- **DetectionTime** – »DateTime« zrušitve aplikacije.
    
- **DeviceModel** – model strojne opreme.

- **MERPSessionID** – ID seje MERP.

- **ReportingOsLocaleTag** – območne nastavitve operacijskega sistema.

- **ReportingOSVerStr** – različica operacijskega sistema.

- **SessionBuildNumber** – različica zrušene aplikacije.

- **SessionIDSMatch** – logična vrednost za preverjanje, ali je ID seje poročanja enak kot tisti, ki ga sprejme Merp.

- **SessionVersion** – različica zrušene aplikacije – **StackHash** – zgoščena vrednost sledi sklada zrušene aplikacije.

- **UAEType** – oštevilčenje, ki zagotavlja informacije o tem, do kakšne vrste zrušitve je prišlo.

#### <a name="officethisaddinstartupfailed"></a>Office.ThisAddIn.StartupFailed

Zbira informacije o izjemi, ki se je pojavila med zagonom orodja za pretakanje podatkov. Ti podatki se uporabljajo za nadzor stanja aplikacije. Ta dogodek ustvari Microsoftovo orodje za pretakanje podatkov za Excelov dodatek.

Zbrana so sledeča polja:

- **Exception** – nabor klicev za izjemo

- **Event Name** – kategorija dogodka in oznaka dogodka predstavljata ime dogodka


### <a name="application-feature-performance-subtype"></a>*Podvrsta za učinkovitost delovanja funkcije aplikacije*

Slab odzivni čas ali slaba učinkovitost za scenarije, kot sta zagon aplikacije ali odpiranje datoteke.

#### <a name="ipcpbootstrapuser"></a>IpcpBootstrapUser

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij. Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede priklic API IpcpBootstrapUser.

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se program izvaja v produkcijskem okolju ali v okolju razvijalcev

- **AppInfo.Name** – ime aplikacije.

- **AppInfo.Version** – različica aplikacije

- **iKey** – ID strežnika za storitev pisanja dnevnika

- **RMS.ApplicationScenarioId** – ID scenarija, ki ga je posredovala aplikacija

- **RMS.AuthCallbackProvided** – označite, če zagotavlja preverjanje pristnosti s povratnim klicem kot vhod priklica API ali ne

- **RMS.ConnectionInfo.ExtranetUrl** – URL ekstraneta v  podatkih o povezavi

- **RMS.ConnectionInfo.IntranetUrl**– URL intraneta v podatkih o povezavi

- **RMS.ConnectionMode** – način povezave med odjemalcem in strežnikom storitev za upravljanje pravic: z vzpostavljeno povezavo ali brez povezave

- **RMS.Duration** – Skupen čas za izvedbo API priklica

- **RMS.DurationWithoutExternalOps** – skupni čas minus zunanje operacije, kot je zakasnitev omrežja.

- **RMS.ErrorCode** – koda napake je vrnjena, če katera koli izvira iz priklica API

- **RMS.GuestTenant** – ID gosta najemnika za uporabnika

- **RMS.HomeTenant** – ID domačega najemnika za uporabnika

- **RMS.HttpCall** – označite, ali je prišlo do operacije HTTP

- **RMS.Identity.ExtranetUrl** – URL ekstraneta strežnika za upravljanje pravic za uporabnika, ki je bil zbran pri pridobivanju novega potrdila o računu pravic iz strežnika

- **RMS.Identity.ExtranetUrl** – URL intraneta strežnika za upravljanje pravic za uporabnika, ki je bil zbran pri pridobivanju novega potrdila o računu pravic iz strežnika

- **RMS.Identity.Status** – ko prvič dobite potrdilo o računu pravic iz strežnika ali obnovite potrdilo o računu pravic 

- **RMS.Identity.Type** – vrsta uporabniškega računa, kot je račun za Windows ali račun Live

- **RMS.Identity.UserProvided** – določite, ali je e-poštni naslov naveden ali ne, medtem ko pridobivate novo potrdilo o računu pravic od strežnika

- **RMS.IssuerId** – ID strežnika za upravljanje pravic, ki izda potrdilo o računu pravic  

- **RMS.LicenseFormat** – oblika licence: Xrml ali Json

- **RMS.RACType** – vrsta potrdila o računu pravic

- **RMS.Rezultat** – uspeh ali neuspeh priklica API

- **RMS.ScenarioId** – ID scenarija, ki ga določa API

- **RMS.SDKVersion** – različica odjemalca storitve za upravljanje pravic

- **RMS.ServerType** – vrsta strežnika za upravljanje pravic do storitev 

- **RMS.StatusCode** – Koda stanja vrnjenega rezultata

- **RMS.TemplatesCount** – število predlog

- **RMS.TokenProvided** – označuje, ali je žeton ponujen kot vhod klica API ali ne 

- **RMS.TokenProvided** – označuje, ali je žeton ponujen kot vhod klica API ali ne 

- **UserInfo.UserObjectId** – ID predmeta uporabnika
#### <a name="officeextensibilityrichapimethodinvocation"></a>Office.Extensibility.RichApiMethodInvocation

Ko stranka uporablja Officeov dodatek in izvaja klice obogatenega API-ja za zagotavljanje storitve, bo sprožen ta dogodek. Uporablja se za merjenje zanesljivosti, učinkovitosti delovanja in uporabe storitve za priklic načina obogatenega API-ja.
 
Zbrana so naslednja polja:

- **Api** – polno ime API-ja

- **DispFlag** – bitna zastavica, ki opisuje vrsto metode (npr.: 0x1 = METHOD, 0x2 = PROPERTYGET, 0x4 = PROPERTYPUT, 0x8 = PROPERTYPUTREF)

- **Despid** – ID razpošiljanja za metodo, ki je klicana.

- **HResult** – »HResult« za klic metode.

- **Latency** – zakasnitev klica v mikrosekundah.

- **ReqId** – GUID za paketno zahtevo, ki ji ta metoda pripada.

- **TypeId** – GUID za vmesnik, v katerem je ta metoda klicana.


#### <a name="officemanageabilityserviceapplypolicy"></a>Office.Manageability.Service.ApplyPolicy

Kritična telemetrija za sledenje neuspeha\\uspeha pri uporabi nastavitev pravilnika v oblaku v registru. Iz elementa LastError je razvidno, zakaj in kje je prišlo do napake pri uveljavljanju pravilnika v registru.

Zbrana so sledeča polja:

  - **Data.ApplyLogMsg** – sporočilo izjeme, če je bil uveljavljen pravilnik while

  - **Data.Cid** – dinamično ustvarjeni identifikator korelacije, poslan storitvi, ko je bil opravljen klic storitve za pridobivanje pravilnika v oblaku. Uporablja se za medsebojno odvisnost pri uporabi pravilnikov v oblaku

  - **Data.Last Error** – ena od petih vrednosti niza (popisovalnik) za beleženje, katera stopnja pravilnika je bila izvedena, ko je prišlo do izjeme

#### <a name="officeoutlookdesktopbootperfmetrics"></a>Office.Outlook.Desktop.BootPerfMetrics

Zbira čas, zahtevan za zagon Outlooka. Čas zagona Outlooka je aktivno nadzorovan za zaznavanje in diagnosticiranje regresij. Prav tako se uporablja za diagnosticiranje stopnjevanj stranke in za izboljšanje učinkovitosti delovanja zagona v bodoče.

Zbrana so sledeča polja:

  - **AddinElapsedTotal** – skupni čas, porabljen za nalaganje dodatkov

  - **CredPromptCount** – število prikazanih pozivov za vnos poverilnic

  - **ElapsedTotal** – skupni čas, porabljen za zagon

  - **IsLoggingEnabled** – ali je omogočeno pisanje dnevnika

  - **ShowChooseProfileDlg** – ali je bilo prikazano pogovorno okno za izbiranje profila

  - **ShowFirstRunDlg** – ali je bil Outlook prvič zagnan

  - **ShowIMAPSrchfldWarningDlg** – opozorila v primeru računa IMAP z elementi ANSI PST

  - **ShowNeedSupportDlg** – neuspešen zagon je aktiviral pogovorno okno podpore

  - **ShowSafeModeDlg** – ali je bila seja odprta v varnem načinu

  - **ShowScanPstDlg** – pregled za popravilo trgovine je prikazal sporočilo o napaki


#### <a name="officeoutlookmacbootperf"></a>Office.Outlook.Mac.BootPerf

Zbira čas, zahtevan za zagon Outlooka. Čas zagona Outlooka je aktivno nadzorovan za zaznavanje in diagnosticiranje regresij. Prav tako se uporablja za diagnosticiranje stopnjevanj stranke in za izboljšanje učinkovitosti delovanja zagona v bodoče.

Zbrana so naslednja polja:

- **MacOLKBootPerfDuration** – skupni čas, porabljen za zagon.

- **MacOLKBootPerfID** – identifikator časa, ki je porabljen za zagon.


#### <a name="officeoutlookmacperformanceunresponsive"></a>Office.Outlook.Mac.PerformanceUnresponsive

Uporablja se za identifikacijo težav v Outlooku, ki vplivajo na uporabnike in se lahko izrazijo kot poslabšano delovanje. 

Zbrana so naslednja polja:

- **Duration** – čas, potekel od poslabšanega delovanja.

- **EventType** – vrsta dogodka, pri katerem prihaja do izkušnje poslabšane učinkovitosti delovanja.


#### <a name="officeperformanceboot"></a>Office.Performance.Boot

Zbrano, ko je zagnana Officeova aplikacija. Vključuje podatke o tem, kdaj je bil zagnan inicializiran z odpiranjem datoteke ali z zagonom prek začetnega menija, ali je bil to prvi zagon aplikacije, koliko pomnilnika porablja aplikacija in ali je bil uporabniku prikazan UV, ki je oviral pogled. Uporabljeno za merjenje hitrosti zagona Officeovih aplikacij in koliko pomnilnika porabijo, ko se zaženejo. Na ta način je zagotovljena sprejemljiva uporabniška izkušnja.

Zbrana so ta polja:

  - **ActivationKind** – ali je bila aplikacija zagnana z zagonom v začetnem meniju, z odpiranjem datoteke ali avtomatizacijo OLE.
  
  - **BootToStart** – ali se je uporabnik odločil za prikaz začetnega zaslona, ko se ta aplikacija zažene.

  - **Data_DocumentLocation** – pri odpiranju dokumenta označuje, v kateri storitvi je na voljo dokument (OneDrive, File Server, SharePoint itd.).

  - **FirstBoot** – ali je bil to prvi zagon aplikacije.

  - **InitializationDuration** – koliko časa v mikrosekundah je preteklo za prvo inicializacijo Officeovega postopka.

  - **InterruptionMessageId** – ID pogovornega okna, če je zagon prekinilo pogovorno okno, ki je uporabnika pozivalo k vnosu podatkov.

  - **TotalWorkingSetMB** – količina pomnilnika v megabajtih v delovnem naboru postopka.

  - **VirtualSetMB** – količina pomnilnika v megabajtih v navideznem naboru postopka. (Samo MacOS/iOS)

  - **WorkingSetPeakMB** – največja količina pomnilnika v megabajtih, ki je bila doslej v delovnem naboru postopka.

#### <a name="officeuxofficeinsidercanshowofficeinsiderslab"></a>Office.UX.OfficeInsider.CanShowOfficeInsiderSlab

Sledenje dejavnosti. Ali je mogoče pomnilniški blok storitve Office Insider prikazati uporabniku na zavihku »Račun« v uporabniškem vmesniku »Office Backstage«.

Zbrana so ta polja:

  - **Data_CanShow** – označuje, ali je mogoče pomnilniški blok storitve Office Insider prikazati uporabniku na zavihku »Račun« v uporabniškem vmesniku »Office Backstage«.
  
  - **Data_Event** – neuporabljeno

  - **Data_EventInfo** – neuporabljeno

  - **Data_Reason** – neuporabljeno.
 

#### <a name="officeuxofficeinsiderregistercurrentinsider"></a>Office.UX.OfficeInsider.RegisterCurrentInsider

Kritični signal za spremljanje zmožnosti ali nezmožnosti registracije uporabnikov, ki niso bili registrirani kot uporabniki programa Office Insider, z uporabo gradenj programa Office Insider. Glavni scenarij za to so trenutni uporabniki programa Office Insider, ki so se pridružili programu Office Insider, preden je bila dodana registracija programa Office Insider.

Zbrana so naslednja polja:

- **Data_RegisterInsider** – stanje registracije programa Office Insider.

- **Data_RegisterInsiderHr** – koda rezultata za registracijo v programu Office Insider.

- **Data_RegistrationStateCurrent** – trenutno stanje registracije.

- **Data_RegistrationStateDesired** – zahtevano stanje registracije.


#### <a name="officeuxofficeinsidershowofficeinsiderdlg"></a>Office.UX.OfficeInsider.ShowOfficeInsiderDlg

Uporabniška interakcija sledenja kritičnega signala s pogovornim oknom »Pridružite se programu Office Insider«. Uporablja se za prepoznavanje kakršnih koli težav pri izvajanju sprememb, ki jih sproži uporabnik, kot sta pridružitev programu Office Insider ali zapuščanje tega programa in spreminjanje ravni programa Office Insider.

Zbrana so naslednja polja:

- **Data_AcceptedContactMeNew** – označuje, ali je uporabnik sprejel možnost vzpostavitve stika s strani družbe Microsoft, ko se je pridružil programu Office Insider.

- **Data_InsiderLevel** – raven programa Insider pri odpiranju pogovornega okna »Pridružite se programu Office Insider«.

- **Data_InsiderLevelNew** – raven programa Insider pri zapiranju pogovornega okna »Pridružite se programu Office Insider«.

- **Data_IsInternalUser** – označuje, ali se aplikacija izvaja s poverilnicami Microsoftovega poslovnega računa.

- **Data_IsInternalUserInit** – označuje, ali lahko koda določi, ali se aplikacija izvaja s poverilnicami Microsoftovega poslovnega računa.

- **Data_OpenNewsletterWebpage** – označuje, ali je bila povezava do naročnine na glasilo »Office Insider« sprožena pod pogojem, da se je uporabnik pridružil programu »Office Insider«, da je omogočena funkcija »Naročnina na glasilo« in da uporabnik ni preklical odpiranja spletne strani z naročnino na glasilo »Office Insider«.
    
- **Data_RegisterInsider** – stanje registracije programa Office Insider.

- **Data_RegisterInsiderHr** – koda rezultata za registracijo v programu Office Insider.

- **Data_RegistrationStateCurrent** – trenutno stanje registracije.

- **Data_RegistrationStateDesired** – zahtevano stanje registracije.




#### <a name="officevisiosharedvisiofilerender"></a>Office.Visio.Shared.VisioFileRender

Ta dogodek zajame čas, zahtevan za upodobitev datoteke. S pomočjo tega dogodka lahko poskrbimo za učinkovito upodabljanje datoteke.

Zbrana so sledeča polja:

  - **Data\_AvgTime: integer** – povprečen čas, zahtevan za upodobitev Visiove risbe v seji

  - **Data\_CompositeSurfEnabled: bool** – ima vrednost true, če je omogočen kompozitni način za upodabljanje

  - **Data\_Count: integer** – število upodobitev slike v seji v Visiu

  - **Data\_FirstRenderTime: long** – trajanje za upodobitev datoteke ob prvem zagonu v milisekundah

  - **Data\_MaxTime: integer** – najdaljši čas, zahtevan za upodobitev Visiove slike v seji

#### <a name="officevisiovisiofileopenreliability"></a>Office.Visio.VisioFileOpenReliability

Ta dogodek zbira podatke o učinkovitosti odpiranja datotek za Visio Dev16. Ta dogodek se uporablja za nadzor učinkovitosti delovanja za odpiranje datoteke, ki jo poveže z lastnostmi datoteke, kot je velikost datoteke, za Visio Dev16. Lastnosti datoteke nam omogočajo, da hitreje odkrijemo napako in poiščemo glavni vzrok.

Zbrana so sledeča polja:

  - **Data\_CorrelationId: string –** identifikator korelacije dokumenta

  - **Data\_DocIsEnterpriseProtected: bool –** ima vrednost true, če je dokument zaščiten z zaščito informacij sistema Windows

  - **Data\_DocumentId: string -** GUID za pot datoteke

  - **Data\_DurationToCompleteInMilliseconds:double –** čas, zahtevan za dokončanje shranjevanja, v milisekundah

  - **Data\_DurationToCompleteInMillisecondsSquared: double –** kvadratna vrednost za DurationToCompleteInMilliseconds

  - **Data\_ErrorCode: integer –** koda notranje napake za neuspešno odpiranje datoteke

  - **Data\_Extension\_Docs: string –** pripona datoteke za odprti diagram

  - **Data\_FileIOBytesRead:int –** skupno število bajtov, prebranih med shranjevanjem

  - **Data\_FileIOBytesReadSquared:int –** kvadratna vrednost za Data\_FileIOBytesRead

  - **Data\_FileIOBytesWritten:int –** skupno število bajtov, zapisanih med shranjevanjem

  - **Data\_FileIOBytesWrittenSquared:int –** kvadratna vrednost za Data\_FileIOBytesWritten

  - **Data\_FileName: binary –** binarna razpršenost za ime datoteke

  - **Data\_FileOpenDownloadDurationInMs: long –** čas, zahtevan za prenos datoteke v milisekundah

  - **Data\_FileOpenEndDurationInMs: long: –** čas, zahtevan za odpiranje datoteke v milisekundah

  - **Data\_FileOpenTimeStamp: time: –** časovni žig za začetek odpiranja datoteke

  - **Data\_FilePathHash: binary** – GUID za pot datoteke

  - **Data\_FileSize: long –** velikost dokumenta v bajtih

  - **Data\_FileType: string –** pripona datoteke za odprti diagram

  - **Data\_IsInternalFile: bool –** ima vrednost true, če gre za notranjo datoteko denimo šablono

  - **Data\_IsIRM: bool –** ima vrednost true, če ima datoteka zaščito za upravljanje pravic do informacij

  - **Data\_IsReadOnly: bool –** ima vrednost true, če je datoteka v načinu samo za branje

  - **Data\_IsSuccess: bool –** ima vrednost true, če je bilo odpiranje datoteke uspešno

  - **Data\_Location: string –** mesto datoteke, kot je lokalno, SharePoint, OneDrive, WopiConsumer, WopiBusiness, GenericThirdPartyConsumer

  - **Data\_NetworkIOBytesRead:int –** skupno število bajtov omrežja, prebranih med shranjevanjem

  - **Data\_NetworkIOBytesReadSquared:int –** kvadratna vrednost za Network\_FileIOBytesRead

  - **Data\_NetworkIOBytesWritten:int –** skupno število bajtov omrežja, zapisanih med shranjevanjem

  - **Data\_NetworkIOBytesWrittenSquared:int –** kvadratna vrednost za NetworkOBytesWritten

  - **Data\_OpenLocation: integer –** mesto za odpiranje datoteke; 0 lokalno, 1 omrežje, 2 SharePoint, 3 splet

  - **Data\_Size\_Docs: integer –** velikost dokumenta v bajtih

  - **Data\_Tag:string –** enolični identifikator za prepoznavanje dogodka »Shrani kot«

  - **Data\_WasSuccessful: bool –** ima vrednost true, če je bilo shranjevanje uspešno

### <a name="application-activity-error-subtype"></a>*Podvrsta napake pri dejavnosti aplikacije*

Napake v delovanju funkcije ali uporabniške izkušnje.

#### <a name="officeairspacebackendwin32graphicsdriversofthang"></a>Office.AirSpace.Backend.Win32.GraphicsDriverSoftHang 

Microsoftu pomaga razlikovati dolgotrajne neodzivnosti gonilnika grafične kartice od kratkotrajnih. Na ta način je lažje določiti, pri katerih gonilnikih grafične kartice se je pojavila napaka. Gonilnik grafične kartice uporabnika je povzročil neodzivnost Officea, vpliv neodzivnosti pa še ni določen.

Zbrana so sledeča polja:

  - **Data\_InDeviceCall** – poklicani način grafične kartice, ki je povzročil neodzivnost

  - **Data\_Timeout** – čas neodzivnosti

#### <a name="officeextensibilitysandboxodperrornotification"></a>Office.Extensibility.Sandbox.ODPErrorNotification

Sledi različnim obvestilom o napakah, ki prispejo iz peskovnika. Uporablja se za zaznavanje scenarijev napak v peskovniku in na podlagi tega za odpravljanje napak, da bi prišlo do izboljšanja storilnosti uporabnika.
 
Zbrana so naslednja polja:

- **AppId** – ID aplikacije.

- **AppUrl** – pomaknjen URL aplikacije. 

- **Result** – koda napake rezultata.


#### <a name="officegraphicsarcexceptions"></a>Office.Graphics.ARCExceptions 

Ti podatki poročanja o izjemi so pomembni za ocenjevanje splošnega stanja grafike in za prepoznavanje delov v kodi, kjer pogosto prihaja do napak. Tako lahko določimo vrstni red raziskovanja. Ti podatki poročanja o izjemi so pomembni za ocenjevanje splošnega stanja grafike in za prepoznavanje delov v kodi, kjer pogosto prihaja do napak. Inženir lahko tako določi, katere napake pri upodabljanju vplivajo na večino uporabnikov, kar nam omogoča, da najprej odpravimo težave, katere v največji meri vplivajo na uporabnike.

Zbrana so sledeča polja:

  - **Data\_HResult** – koda napake, ki jo je vrnila okvara

  - **Data\_TagCount** – število zaznanih okvar

  - **Data\_TagID** – identifikator zaznane okvare

#### <a name="officeoutlookdesktopcalendaracceptcalsharenavigatetosharedfolder_error"></a>Office.Outlook.Desktop.Calendar.AcceptCalShareNavigateToSharedFolder\_Error

Zbira informacije o zaznanih okvarah med prikazom koledarja v skupni rabi. Ti podatki se uporabljajo za nadzor stanja programskega vmesnika za skupno rabo koledarja in Outlookove interakcije s koledarji v skupni rabi.

Zbrana so sledeča polja:

  - **FailedCaseHResult** – koda napake, ki jo je vrnila okvara

#### <a name="officeoutlookdesktopedpedpopenstorefailure"></a>Office.Outlook.Desktop.EDP.EDPOpenStoreFailure

Uspešno ali neuspešno odpiranje nabiralnika z omogočeno zaščito podatkov podjetja zaradi klica programskega vmesnika sistema Windows za pridobivanje ključa za dešifriranje trgovine. Te podatke uporabimo za diagnosticiranje ene od najpogostejših težava zaščite podatkov podjetja, ki lahko prepreči zagon Outlooka. Glavni vzrok napake je Outlookova interakcija s programski vmesniki sistema Windows, ki se uporabljajo za dešifriranje ključa trgovine.

Zbrana so sledeča polja:

  - **HVA Activity** **-** s podatkovni polji po meri

  - **IsFlightOn** – ponazarja, ali je omogočena selitev EDPDecryption

#### <a name="officeoutlookdesktopndbcorruptionresult"></a>Office.Outlook.Desktop.NdbCorruptionResult

Dogodka Office.Outlook.Desktop.NdbCorruptionResult in Office.Outlook.Desktop.NDBCorruptStore.Warning sta zbrana, ko odkrijemo poškodbe v datotekah PST/OST uporabnika. Ko zaznamo poškodbe, Microsoft zbere obliko zapisa zbirke podatkov, mesto zaznavanja in majhen del konteksta o nepravilnosti. Poškodovane datoteke OST/PST uporabnikom preprečujejo dostop do svojih e-poštnih sporočil. Te podatke aktivno spremljamo, ali se v njih pojavi nenavadna dejavnost. Želimo raziskovati in diagnosticirati težave in omejiti izgubo podatkov uporabnikov.

Zbrana so sledeča polja:

  - **0 –** ime procesa, ki je sporočil poškodbo

  - **1 –** logična vrednost, ki označuje, ali je uporabnik izbral novo datoteko

  - **2 –** število drugih procesov, ki imajo odprte zbirke podatkov

#### <a name="officeoutlookdesktopndbcorruptstorewarning"></a>Office.Outlook.Desktop.NDBCorruptStore.Warning

Dogodka Office.Outlook.Desktop.NdbCorruptionResult in Office.Outlook.Desktop.NDBCorruptStore.Warning sta zbrana, ko odkrijemo poškodbe v datotekah PST/OST uporabnika. Ko zaznamo poškodbe, Microsoft zbere obliko zapisa zbirke podatkov, mesto zaznavanja in majhen del konteksta o nepravilnosti. Poškodovane datoteke OST/PST uporabnikom preprečujejo dostop do svojih e-poštnih sporočil. Te podatke aktivno spremljamo, ali se v njih pojavi nenavadna dejavnost. Želimo raziskovati in diagnosticirati težave in omejiti izgubo podatkov uporabnikov.

Zbrana so sledeča polja:

  - **CollectionTime** – čas zbiranja

  - **Context** – kontekst poškodovane trgovine, v kateri je bila zaznana poškodba

  - **CreatedWithVersion** – (izbirno) polje z različico trgovine

  - **Details** – podrobnosti zrušitve

  - **NdbType** – vrsta trgovine; vrednosti so lahko 0 = NdbUndefined, 1 = NdbSmall, 2 = NdbLarge, 3 = NdbTardis

  - **ProcessName** – ime procesa, ki je povzročil poškodbo trgovine

  - **PstVersion** – različica knjižnice MSPST32. DLL

  - **Version** – različica oblike zapisa datoteke za trgovino

#### <a name="officeoutlookdesktopoutlookcalendarusageerrmeetrcptforwardactionsruleo16"></a>Office.Outlook.Desktop.OutlookCalendarUsageErr.MeetRcpt.ForwardActions.Rule.O16

V pogledih pošte, koledarja in inspektorja v Outlooku zbere podatke o uspešnih in neuspešnih dejanjih posredovanja, posredovanja kot priloge in posredovanja kot dejanje za iCalendar za enkraten ter ponavljajoči se odziv in odziv izjemnega sestanka. V stopnji neuspeha za posredovanje, posredovanje kot prilogo in posredovanje kot dejanje iCalendar aktivno iščemo anomalije. Nenavadna statistika ponazarja neuspeh Outlooka, da izvede osnovno dejanje koledarja. Ti podatki se prav tako uporabljajo za diagnosticiranje drugih zaznanih težav, povezanih s koledarjem.

Zbrana so sledeča polja:

  - **CountExceptionForward** – število posredovanih izjem srečanj.

  - **CountExceptionForwardAsiCal** – število posredovanih izjem srečanj kot dejanje iCal.

  - **CountExceptionForwardInSplit** – število posredovanih izjem srečanj iz menija za razdeljevanje na traku.

  - **CountExceptionForwardWithAttach** – število posredovanih izjem srečanj kot priloga.

  - **CountRecurringForward** – število posredovanih ponavljajočih se srečanj.

  - **CountRecurringForwardAsiCal** – število posredovanih ponavljajočih se srečanj kot dejanje iCal.

  - **CountRecurringForwardInSplit** – število posredovanih ponavljajočih se srečanj iz menja za razdeljevanje na traku.

  - **CountRecurringForwardWithAttach** – število posredovanih ponavljajočih se srečanj kot priloga.

  - **CountSingleForward** – število posredovanih enkratnih srečanj.

  - **CountSingleForwardAsiCal** – število posredovanih enkratnih srečanj kot dejanje iCal.

  - **CountSingleForwardInSplit** – število posredovanih enkratnih srečanj iz menija za razdeljevanje na traku.

  - **CountSingleForwardWithAttach** – število posredovanih enkratnih srečanj kot priloga.

  - **HResult** – »ErrorCode«.

  - **OlkViewName** – označuje pogled pošte, koledarja ali nadzornika.

#### <a name="officeoutlookdesktopoutlookcalendarusageerrmeetrcptreplyactionsruleo16"></a>Office.Outlook.Desktop.OutlookCalendarUsageErr.MeetRcpt.ReplyActions.Rule.O16

V pogledih pošte, koledarja in inšpektorja v Outlooku zbere podatke o uspešnih in neuspešnih dejanjih »Odgovori«, »Odgovori vsem«, »Odgovori z neposrednim sporočilom« in »Odgovori vsem z neposrednim sporočilom« za enkraten ter ponavljajoči se odziv in odziv izjemnega sestanka. V stopnji neuspeha za dejanja »Odgovori«, »Odgovori vsem«, »Odgovori z neposrednim sporočilom« in »Odgovori vsem z neposrednim sporočilom« aktivno iščemo anomalije. Nenavadna statistika ponazarja neuspeh Outlooka, da izvede osnovno dejanje koledarja. Ti podatki se prav tako uporabljajo za diagnosticiranje drugih zaznanih težav, povezanih s koledarjem.

Zbrana so naslednja polja:

  - **CountExceptionReply** – število dejanj »Odgovori« za srečanja pri izjemah.

  - **CountExceptionReplyAll** – število dejanj »Odgovori vsem« za srečanja pri izjemah.

  - **CountExceptionReplyAllWithIM** – število dejanj »Odgovori vsem z neposrednim sporočilom« za srečanja pri izjemah.

  - **CountExceptionReplyWithIM** – število dejanj »Odgovori z neposrednim sporočilom« za srečanja pri izjemah.

  - **CountRecurringReply** – število dejanj »Odgovori« v ponavljajočih se srečanjih.

  - **CountRecurringReplyAll** – število dejanj »Odgovori vsem« v ponavljajočih se srečanjih.

  - **CountRecurringReplyAllWithIM** – število dejanj »Odgovori vsem z neposrednim sporočilom« v ponavljajočih se srečanjih.

  - **CountRecurringReplyWithIM** – število dejanj »Odgovori z neposrednim sporočilom« v ponavljajočih se srečanjih.

  - **CountSingleReply** – število dejanj »Odgovori« v enkratnih srečanjih.

  - **CountSingleReplyAll** – število dejanj »Odgovori vsem« v enkratnih srečanjih.

  - **CountSingleReplyAllWithIM** – število dejanj »Odgovori vsem z neposrednim sporočilom« v enkratnih srečanjih.

  - **CountSingleReplyWithIM** – število dejanj »Odgovori z neposrednim sporočilom« v enkratnih srečanjih.

  - **HResult** – »ErrorCode«.

  - **OlkViewName** – označuje pogled pošte, koledarja ali nadzornika.

#### <a name="officeoutlookdesktopoutlookprivsdlgsingleuserloadfail"></a>Office.Outlook.Desktop.OutlookPrivsDlgSingleUser.LoadFail

To pravilo zbere napake pri skupni rabi koledarja, nastale pri dodajanju novega uporabnika (vrste EX ali SMTP) iz adresarja. Ti podatki se uporabljajo za diagnosticiranje in odpravljanje težav v pogovornem oknu za skupno rabo koledarja.

Zbrana so sledeča polja:

  - **CountAccountWizardEnd** – kolikokrat se je podedovano pogovorno okno čarovnika zaprlo

  - **CountCreatePIMAccount** – kolikokrat je uporabnik ustvaril profil PIM

#### <a name="officeoutlookmacmacolkasserts"></a>Office.Outlook.Mac.MacOLKAsserts

Uporablja se za identifikacijo težav v Outlooku, ki vplivajo na uporabnike in se lahko izrazijo kot zrušitve ali poslabšanje učinkovitosti delovanja funkcionalnosti. 

Zbrana so naslednja polja:

- **Category** – vrsta potrditve.

- **CollectionTime** – čas zbiranja potrditve.


#### <a name="officeoutlookmacmacolkerrors"></a>Office.Outlook.Mac.MacOLKErrors

Uporablja se za identifikacijo težav v Outlooku, ki vplivajo na uporabnike in se lahko izrazijo kot zrušitve ali poslabšanje učinkovitosti delovanja funkcionalnosti. 

Zbrana so naslednja polja:

- **Category** – vrsta napake.

- **CollectionTime** – čas zbiranja napake.

- **ThreadId** – identifikator niti.


#### <a name="officesystemsystemhealthasserts"></a>Office.System.SystemHealthAsserts

Napake, ki jih prepozna ta dogodek, nam omogočajo bolje razumeti, kdaj se je poslabšala uporabniška izkušnja. Številne potrditve ShipAsserts povzročajo zrušitve in te informacije nam omogočajo, da jih odpravimo. Zbira potrditve ShipAsserts izdelka, ki nam pomagajo prepoznati napake.

Zbrana so naslednja polja:

 - **Count** – število poročanih posameznih potrditev.

  - **EndTime** – čas poročanja za zadnjo potrditev

  - **ErrorGroup** – identifikator razdeljevanja za posamezno potrditev

  - **FirstTimeStamp** – prvič, ko je prišlo do potrditve

  - **Trackback** – enolični identifikator za določeno potrditev

#### <a name="officesystemsystemhealtherrorsetwshim"></a>Office.System.SystemHealthErrorsEtwShim

Ta dogodek se uporablja za prepoznavanje težav, ki vplivajo na uporabnika, v aktivni aplikaciji, zaradi katerih lahko pride do zrušitev ali zmanjšanje funkcionalnosti. Zabeleži napake, ki se pojavijo med izvajanjem procesov.

Zbrana so sledeča polja:

  - **EndTime** – čas poročanja za zadnjo napako

  - **Trackback** – enolični identifikator za določeno napako

  - **ErrorGroup** – identifikator razdeljevanja za posamezno napako

  - **Count** – število posameznih napak

  - **FirstTimeStamp** – prvič, ko je prišlo do napake

#### <a name="officesystemsystemhealtherrorsulsandasserts"></a>Office.System.SystemHealthErrorsUlsAndAsserts

Ta dogodek se uporablja za prepoznavanje težav, ki vplivajo na uporabnika, v aktivni aplikaciji, zaradi katerih lahko pride do zrušitev ali zmanjšanje funkcionalnosti. Zabeleži napake, ki se pojavijo med izvajanjem procesov.

Zbrana so sledeča polja:

  - **EndTime** – čas poročanja za zadnjo napako

  - **Trackback** – enolični identifikator za določeno napako

  - **ErrorGroup** – identifikator razdeljevanja za posamezno napako

  - **Count** – število posameznih napak

  - **FirstTimeStamp** – prvič, ko je prišlo do napake

#### <a name="officesystemsystemhealtherrorsulsworkaround"></a>Office.System.SystemHealthErrorsUlsWorkaround

Ta dogodek se uporablja za prepoznavanje težav, ki vplivajo na uporabnika, v aktivni aplikaciji, zaradi katerih lahko pride do zrušitev ali zmanjšanje funkcionalnosti. Zabeleži napake, ki se pojavijo med izvajanjem procesov.

Zbrana so sledeča polja:

  - **EndTime** – čas poročanja za zadnjo napako

  - **Trackback** – enolični identifikator za določeno napako

  - **ErrorGroup** – identifikator razdeljevanja za posamezno napako

  - **Count** – število posameznih napak

#### <a name="officesystemsystemhealtherrorswithouttag"></a>Office.System.SystemHealthErrorsWithoutTag

Ta dogodek se uporablja za prepoznavanje težav, ki vplivajo na uporabnika, v aktivni aplikaciji, zaradi katerih lahko pride do zrušitev ali zmanjšanje funkcionalnosti. Zabeleži napake, ki se pojavijo med izvajanjem procesov.

Zbrana so sledeča polja:

Count – število posameznih napak

  - **EndTime** – čas poročanja za zadnjo napako

  - **ErrorCode** – identifikator napake

  - **ErrorGroup** – identifikator razdeljevanja za posamezno napako

  - **ErrorId** – identifikator napake

  - **FirstTimeStamp** – prvič, ko je prišlo do napake

  - **Trackback** – enolični identifikator za določeno napako

#### <a name="officesystemsystemhealtherrorswithtag"></a>Office.System.SystemHealthErrorsWithTag

Ta dogodek se uporablja za prepoznavanje težav, ki vplivajo na uporabnika, v aktivni aplikaciji, zaradi katerih lahko pride do zrušitev ali zmanjšanje funkcionalnosti. Zabeleži napake, ki se pojavijo med izvajanjem procesov.

Zbrana so sledeča polja:

  - **Count** – število posameznih napak

  - **EndTime** – čas poročanja za zadnjo napako

  - **ErrorCode** – identifikator napake

  - **ErrorGroup** – identifikator razdeljevanja za posamezno napako

  - **ErrorId** – identifikator napake

  - **FirstTimeStamp** – prvič, ko je prišlo do napake

  - **Trackback** – enolični identifikator za določeno napako

#### <a name="renewidentityfailure"></a>RenewIdentityFailure

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij. Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko obnovitev uporabniških dovoljenj ne uspe.

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se program izvaja v produkcijskem okolju ali v okolju razvijalcev

- **AppInfo.Name** – ime aplikacije.

- **AppInfo.Version** – različica aplikacije

- **Failure.Category** – Kategorija napake »UnhandledError«

- **Failure.Detail** – podrobnejše informacije o napaki

- **Failure.Id** – ID napake

- **Failure.Signature** – podpis napake, ki je enaka kot ime dogodka

- **iKey** – ID strežnika za storitev pisanja dnevnika

- **RMS. HRESULT** – rezultat obnovitve potrdila uporabnika

- **RMS.ScenarioId** – ID scenarija, ki ga je določil odjemalec storitve za upravljanje pravic

- **RMS.SDKVersion** – različica odjemalca storitve za upravljanje pravic


## <a name="device-connectivity-and-configuration-data-events"></a>Podatkovni dogodki povezljivosti in konfiguracije naprave

V nadaljevanju tega članka so navedene podvrste podatkov v tej kategoriji:

- [Povezljivost in konfiguracija naprave](#device-connectivity-and-configuration-subtype)


### <a name="device-connectivity-and-configuration-subtype"></a>*Podvrsta povezljivosti in konfiguracije naprave*

Stanje omrežne povezave in nastavitve naprave, kot je pomnilnik.

#### <a name="officeairspaceairspacelocalblocklistdriverupdated"></a>Office.AirSpace.AirSpaceLocalBlocklistDriverUpdated

Uporabnik je posodobil gonilnik grafične kartice, ki je povzročal zrušitve Officea in se posledični ni več uporabljal za upodabljanje. Obvešča Microsoft, da so uporabniki, ki so nekoč bili v neoptimalnem stanju upodabljanja, ponovno v priporočenem stanju upodabljanja.

Zbrana so sledeča polja:

  - **Data\_BlockedDriverVersion** – različica gonilnika na seznamu prepovedanih

  - **Data\_DeviceId** – identifikator grafične kartice na seznamu prepovedanih

  - **Data\_UpdatedDriverVersion** – različica posodobljenega gonilnika

#### <a name="officeairspaceairspacelocalblocklistinfo"></a>Office.AirSpace.AirSpaceLocalBlocklistInfo

Podrobnosti o gonilniku grafične kartice uporabnika, ki je povzročil več nedavnih zrušitev Officeovih aplikacij. Office ne bo uporabljal te grafične kartice v tej Officeovi seji (namesto tega se uporabi programska oprema za upodabljanje), dokler ne posodobite gonilnika. Obvesti Microsoft o gonilnikih grafične kartice, ki povzročajo težave v Officeu. Na ta način je mogoče prepoznati trende in analizirati učinek, ki ga imajo takšni gonilniki na uporabnika. Microsoft tako izve, koliko uporabnikov ni v optimalnem stanju.

Zbrana so sledeča polja:

  - **Data\_AllAppsBlocked** – ali so prepovedane vse Officeove aplikacije

  - **Data\_BlockedDeviceId** – identifikator grafične kartice na seznamu prepovedanih

  - **Data\_BlockedDriverVersion** – različica gonilnika na seznamu prepovedanih

  - **Data\_CrashHistory** – niz, ki predstavlja zgodovino gonilnika grafične kartice, ki je povzročil zrušitve za analizo

  - **Data\_SecsBetweenCrashes** – kako pogosto prihaja do zrušitev grafične kartice

#### <a name="officeairspaceairspacewincompisenabled"></a>Office.AirSpace.AirSpaceWinCompIsEnabled

Ali se za sestavo sistema Windows uporablja najnovejša Officeova platforma za upodabljanje na nizki ravni.

Najnovejša Officeova platforma za upodabljanje na nizki ravni se razvija in se postopno izdaja uporabnikom, tako da Microsoft lahko oceni, koliko uporabnikov uporablja določeno različico, in tako zagotovi nemoteno delovanje platforme.

Zbrana so sledeča polja:

  - **Data\_WinCompEnabled** – ali se uporablja zaledje na osnovi sestave sistema Windows

#### <a name="officeairspacebackendwin32graphicsdriverhangdetectorblocklistapp"></a>Office.AirSpace.Backend.Win32.GraphicsDriverHangDetectorBlocklistApp

Za grafično kartico uporabnika je bilo zaznano, da povzroča dolgotrajno neodzivnost in neodzivnost, ki je ni mogoče odpraviti. Office ne bo uporabljal te grafične kartice v tej Officeovi seji (namesto tega se uporabi programska oprema za upodabljanje), dokler ne posodobite gonilnika. Obvesti Microsoft o gonilnikih grafične kartice, ki povzročajo težave v Officeu. Na ta način je mogoče prepoznati trende in analizirati učinek, ki ga imajo takšni gonilniki na uporabnika. Prav tako omogoča podatke o tem, koliko uporabnikov ni v optimalnem stanju.

Zbrana so sledeča polja:

  - **Data\_AppName** – katera aplikacija je naletela na neodzivnost gonilnika grafične kartice

#### <a name="officeairspacebackendwin32graphicsdriverhangdetectorregistrywrite"></a>Office.AirSpace.Backend.Win32.GraphicsDriverHangDetectorRegistryWrite

Office je prepoznal, da je gonilnik grafične kartice uporabnika povzročil neodzivno stanje, ki ga je treba analizirati pri naslednjem zagonu Officeove aplikacije. Se uporablja za odločitev, ali bi uporaba drugega gonilnika grafične kartice ali vmesnika zagotovila boljšo uporabniško izkušnjo. Če se pojavijo vzorci, Microsoft lahko poskrbi za prilagoditve, s katerimi zagotovi čim bolj neovirano delovanje Officea.

Zbrana so sledeča polja:

  - **Data\_HangDetected** – ali je bila zaznana zrušitev

  - **Data\_InDeviceCall** – kateri klic za upodabljanje grafične kartice je bil aktiviran za Office, ko je bila zaznana neodzivnost

  - **Data\_Timeout** – čas neodzivnosti, če je bila ta odpravljena

  - **Data\_UnrecoverableCommand** – ali je neodzivnost v tem ukazu za upodabljanje grafične kartice mogoče obnoviti

#### <a name="officeairspacebackendwin32localblocklistactivity"></a>Office.AirSpace.Backend.Win32.LocalBlocklistActivity

Podrobnosti o gonilniku grafične kartice uporabnika, ki je povzročil več nedavnih zrušitev Officeovih aplikacij. Office ne bo uporabljal te grafične kartice v tej Officeovi seji (namesto tega se uporabi programska oprema za upodabljanje), dokler ne posodobite gonilnika. Obvesti Microsoft o gonilnikih grafične kartice, ki povzročajo težave v Officeu. Na ta način je mogoče prepoznati trende in analizirati učinek, ki ga imajo takšni gonilniki na uporabnika. Microsoft tako izve, koliko uporabnikov ni v optimalnem stanju.

Zbrana so sledeča polja:

  - **Data.AllAppsBlocked** – ali so blokirane vse Officeove aplikacije

  - **Data.BlockedDeviceId** – identifikator blokirane grafične kartice

  - **Data.BlockedDriverVersion** – različica gonilnika na seznamu blokiranih

  - **Data.CrashHistory System.String** – niz, ki predstavlja zgodovino gonilnika grafične kartice, ki je povzročil zrušitve za analizo

  - **Data.SecsBetweenCrashes** – kako pogosto prihaja do zrušitev grafične kartice

#### <a name="officeairspacebackendwin32localblocklistdriverupdatedactivity"></a>Office.AirSpace.Backend.Win32.LocalBlocklistDriverUpdatedActivity

Uporabnik je posodobil gonilnik grafične kartice, ki je povzročal zrušitve Officea in se posledični ni več uporabljal za upodabljanje. Obvešča Microsoft, da so uporabniki, ki so nekoč bili v neoptimalnem stanju upodabljanja, ponovno v priporočenem stanju upodabljanja.

Zbrana so sledeča polja:

  - **Data\_BlockedDeviceId** – identifikator grafične kartice na seznamu prepovedanih

  - **Data\_BlockedDriverVersion** – različica gonilnika na seznamu prepovedanih

  - **Data\_UpdatedDriverVersion** – različica posodobljenega gonilnika

#### <a name="officegraphicsspritememcorrupt"></a>Office.Graphics.SpriteMemCorrupt

Prijavi vse napake, zaznane pri telemetriji za določanje pomnilnika za slike. Ta dogodek je pomemben za ocenjevanje stanja telemetrije porabe grafičnega pomnilnika. Ti podatki so zahtevani za preverjanje, ali je naša telemetrija pomnilnika SpriteMem pravilna.

Zbrana so sledeča polja:

  - **Data\_CurrentSpriteMem** – skupna količina pomnilnika, ki je aktivno dodeljen za prikaz slik na zaslonu

  - **Data\_Function** – ime funkcije, ki poskuša sprostiti pomnilnik za slike

  - **Data\_SpriteMemToRemove** – količina pomnilnika, ki bo odstranjena iz dodelitve za slike.

#### <a name="officepowerpointpptsharednointernetconnectivity"></a>Office.PowerPoint.PPT.Shared.NoInternetConnectivity

Ti podatki so zbrani, kadar PowerPoint zazna, da ni internetne povezave. Microsoft uporablja te podatke za pridobivanje diagnostičnih informacij o internetni povezavi uporabnika, da lahko bolje razume učinek, kako to vpliva na povezljivost z Officeovimi storitvami.

Zbrana so sledeča polja:

- **Data\_IsNexusDetected:bool** – prikaže, ali je stanje internetne povezave na voljo med klicanjem storitve Nexus (true) ali pri klicanju programskega vmesnika za splošno spletno storitev (false)
