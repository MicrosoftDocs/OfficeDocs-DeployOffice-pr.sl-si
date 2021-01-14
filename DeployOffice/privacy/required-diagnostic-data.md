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
ms.openlocfilehash: b7993abbca401d65cc99ed9fdd7960bae03e89a3
ms.sourcegitcommit: c891622923aecf9afd3ba61e008501cb0c374b73
ms.translationtype: HT
ms.contentlocale: sl-SI
ms.lasthandoff: 01/13/2021
ms.locfileid: "49841732"
---
# <a name="required-diagnostic-data-for-office"></a>Obvezni diagnostični podatki za Office

> [!NOTE]
> Če si želite ogledati seznam Officeovih izdelkov, ki so zajeti v teh informacijah o zasebnosti, glejte [Kontrolnike zasebnosti, ki so na voljo za Officeove izdelke](products-versions-privacy-controls.md).

Diagnostični podatki so uporabljeni za zaščito, posodobitev ter zaznavanje in odpravljanje težav v Officeu, poleg tega pa tudi za izboljšanje izdelka. Ti podatki ne vključujejo uporabniškega imena ali e-poštnega naslova, vsebine datotek uporabnika ali informacij o aplikacijah, ki niso del Officea.

Ti diagnostični podatki so zbrani in poslani Microsoftu. V njih so podatki o odjemalski programski opremi za Office v napravi uporabnika. Nekateri diagnostični podatki so obvezni, medtem ko so drugi izbirni. S kontrolniki zasebnosti lahko izbirate, ali nam boste poslali zahtevane ali izbirne diagnostične podatke, kot so na primer nastavitve pravilnikov za organizacijo. S Pregledovalnikom diagnostičnih podatkov lahko vidite, kateri diagnostični podatki so nam poslani.

***Obvezni diagnostični podatki** _ vključujejo najmanjšo nujno količino podatkov, potrebnih za zagotavljanje varnosti, posodobitev in pričakovanega delovanja Officea v napravi, v kateri je sistem nameščen.

Z obveznimi diagnostičnimi podatki prepoznate težave z Officeom, ki so morda povezane z napravo ali konfiguracijo programske opreme. Z njimi lahko na primer prepoznate pogoste zrušitve novo uvedenih Officeovih funkcij v določeni različici operacijskega sistema oz. onemogočene Officeove funkcije. Z obveznimi diagnostičnimi podatki lahko hitreje zaznamo, diagnosticiramo in odpravimo te težave ter tako zmanjšamo njihov vpliv na uporabnike ali organizacije.

Več informacij o diagnostičnih podatkih najdete v teh člankih:

- [Izbirni diagnostični podatki za Office](optional-diagnostic-data.md)
- [Uporaba pregledovalnika diagnostičnih podatkov z Officeom](https://support.microsoft.com/office/cf761ce9-d805-4c60-a339-4e07f3182855)

Če ste skrbnik za svojo organizacijo, vas bo morda zanimal tudi za te članke:

- [Pregled kontrolnikov za zasebnost za Microsoft 365 aplikacije za podjetja](overview-privacy-controls.md)
- [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Microsoft 365 aplikacije za podjetja](manage-privacy-controls.md)
- [Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office za Mac](mac-privacy-preferences.md)
- [Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom iOS](ios-privacy-preferences.md)
- [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom Android](android-privacy-controls.md)

## <a name="categories-data-subtypes-events-and-data-fields-for-required-diagnostic-data"></a>Kategorije, podatkovni podtipi, dogodki in podatkovna polja za obvezne diagnostične podatke

Obvezni diagnostični podatki so organizirani v kategorije in podatkovne podtipe. Posamezni podatkovni tipi so razvrščeni v dogodke, ki vključujejo določena podatkovna polja.

V spodnji tabeli je na voljo seznam kategorij za obvezne diagnostične podatke. Navedeni so podatkovni podtipi znotraj posameznih kategorij ter opisi fokusa posameznih podatkovnih podtipov. Navedene so tudi povezave do posameznih razdelkov podatkovnih podtipov, kjer so na voljo te informacije:

- Seznam dogodkov v določenem podatkovnem podtipu
- Opis posameznih dogodkov
- Seznam podatkovnih polj v posameznih dogodkih
- Opis posameznih podatkovnih polj

| _ *Kategorija**       | **Podatkovni podtip**| **Opis**    |
| ---------- | ------------- | ---- |
| **Nastavitev programske opreme in inventar** | [Nastavitev Officea in inventar](#office-setup-and-inventory-subtype)   | Nameščeni izdelek, različica in stanje namestitve.  |
| | [Konfiguracija dodatka za Office](#office-add-in-configuration-subtype)  | Dodatki programske opreme in nastavitve.     |
| | [Varnost](#security-subtype)  | Stanje napak dokumentov, funkcij in dodatkov, ki lahko ogrozijo varnost in pripravljenost izdelka za posodobitve.  |
| **Uporaba izdelka in storitev**    | [Uspešnost izvajanja funkcije aplikacije](#application-feature-success-subtype)   | Uspešnost delovanja aplikacije. Omejeno na odpiranje in zapiranje aplikacij in dokumentov, urejanje datoteke ter skupno rabo datotek (sodelovanje). |
| | [Stanje in zagon aplikacije](#application-status-and-boot-subtype)    | Prepoznavanje, ali so bili izvedeni določeni dogodki funkcij, kot je zagon ali ustavitev, oz. če se funkcije izvajajo.   |
| | [Konfiguracija za dostopnost sistema Office](#office-accessibility-configuration-subtype)  | Officeove funkcije dostopnosti       |
| | [Zasebnost](#privacy-subtype)| Nastavitve zasebnosti za Office|
| **Učinkovitost delovanja izdelka in storitve**       | [Nepričakovano zapiranje aplikacije (zrušitev)](#unexpected-application-exit-crash-subtype)  | Nepričakovana zapiranja aplikacije in stanje aplikacije, ko pride do tega.    |
|  | [Učinkovitost delovanja funkcije aplikacije](#application-feature-performance-subtype)  | Slab odzivni čas ali slaba učinkovitost delovanja za scenarije, kot sta zagon aplikacije oz. odpiranje datoteke. |
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

  - **ControllerConnectedServicesSourceLocation** – Označuje, kako je uporabnik izbral uporabo izbirnih povezanih izkušenj.

  - **ControllerConnectedServicesState** – Označuje, ali ima uporabnik dostop do izbirnih povezanih izkušenj.

  - **ControllerConnectedServicesStateConsentTime** – Označuje, kdaj je uporabnik izbral stanje izbirnih povezanih izkušenj. Datum bo prikazan kot človeško berljiv datum ali kot strojno kodiran datum, ki je videti kot veliko število.

  - **DiagnosticConsentConsentTime** – Označuje, kdaj je uporabnik soglašal z uporabo diagnostičnih podatkov. Datum bo prikazan kot človeško berljiv datum ali kot strojno kodiran datum, ki je videti kot veliko število.

  - **DiagnosticConsentLevel** – Označuje raven soglasja za uporabo diagnostičnih podatkov, ki ga je podelil uporabnik.

  - **DiagnosticConsentLevelSourceLocation** – Označuje, kako je uporabnik soglašal z uporabo diagnostičnih podatkov.

  - **DownloadContentSourceLocation** – Označuje, kako je uporabnik omogočil oz. onemogočil povezane izkušnje, ki prenašajo spletno vsebino.

  - **DownloadContentState** – Označuje, ali je uporabnik omogočil oz. onemogočil povezane izkušnje, ki prenašajo spletno vsebino.

  - **DownloadContentStateConsentTime** – Označuje, kdaj je uporabnik omogočil oz. onemogočil povezane izkušnje, ki prenašajo spletno vsebino. Datum bo prikazan kot človeško berljiv datum ali kot strojno kodiran datum, ki je videti kot veliko število.

  - **ServiceConnectionState** – Označuje, ali je uporabnik izbral, da želi oz. ne želi uporabljati vse povezane izkušnje.

  - **ServiceConnectionStateConsentTime** – Označuje, kdaj je uporabnik izbral, ali želi uporabljati vse povezane izkušnje. Datum bo prikazan kot človeško berljiv datum ali kot strojno kodiran datum, ki je videti kot veliko število.

  - **ServiceConnectionStateSourceLocation** – Označuje, kako je uporabnik izbral možnost uporabe vseh povezanih izkušenj.

  - **UserCategoryValue** – Določa vrsto uporabnika, ki je podelil soglasje. MSAUser, AADUser ali LocalDeviceUser.

  - **UserContentDependentSourceLocation** – Označuje, kako je uporabnik omogočil oz. onemogočil povezane izkušnje, ki analizirajo vsebino.

  - **UserContentDependentState** – Označuje, ali je uporabnik omogočil oz. onemogočil povezane izkušnje, ki analizirajo vsebino.

  - **UserContentDependentStateConsentTime** – Označuje, kdaj je uporabnik omogočil oz. onemogočil povezane izkušnje, ki analizirajo vsebino. Datum bo prikazan kot človeško berljiv datum ali kot strojno kodiran datum, ki je videti kot veliko število.

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

  - **HostAppName** – prepozna ime gostiteljske aplikacije, ki zažene podaplikacijo. Aplikacije, kot je Office Mobile (Android), lahko zaženejo Wordove, Excelove in PowerPointove podaplikacije. Takšne podaplikacije gostujejo v aplikaciji OfficeMobile

  - **HostSessionId** – enolično določa sejo gostiteljske aplikacije za podaplikacijo

  - **Id** – Enolično identificira določeno podatkovno sejo. Omogoča, da določimo vpliv težav tako, da ocenimo število prizadetih sej in prepoznamo morebitne skupne značilnosti teh sej.

  - **ImpressionId** – Določa nabor pilotnih različic, ki se izvajajo v določeni seji. Omogoča, da ugotovimo, katere pilotne različice se izvajajo v seji ter tako določimo, ali je pilotna različica izvor uporabnikovih težav.

  - **MeasuresEnabled** – Zastavica, ki označuje, ali so podatki trenutne seje vzorčni. Omogoča, da določimo, kako statistično oceniti podatke, zbrane v določeni seji.

  - **SamplingClientIdValue** – ID odjemalca, s katerim določimo, ali je del vzorčenja. Omogoča, da določimo, zakaj so bile posamezne seje vključene oz. izključene iz vzorčenja.
  
 - **SubAppName** – Za aplikacijo Office Mobile to polje označuje temeljno aplikacijo, uporabljeno za odpiranje dokumenta. Če na primer odprete Wordov dokument v aplikaciji Office, je v tem polju prikazana vrednost »Word«.

 - **VirtualizationType** – vrsta ponazoritve, če se ta izvaja v Officeu. Na voljo so te vrednosti: 
    - 0 = Brez
    - 1 = Navidezno namizje sistema Windows
    - 2 = Windows Defender Application Guard
    - 3 = Windows Core OS

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

  - **Duration** – Trajanje izvajanja dejavnosti. Nam omogoča, da prepoznamo težave z učinkovitostjo delovanja, ki negativno vplivajo na uporabniško izkušnjo.

  - **Result.Code** – Koda, ki jo določa aplikacija, za prepoznavanje določenih rezultatov. Omogoča, da določimo podrobnosti napake, kot je koda napake, s katero lahko razvrstimo težave in jih odpravimo.

  - **Result.Tag** – Oznaka za celo število, ki določa lokacijo v kodi, kjer je bil ustvarjen rezultat. Omogoča, da natančno določimo lokacijo v kodi, kjer je bil ustvarjen rezultat, ter tako razvrstimo napake.

  - **Result.Type** – Vrsta kode rezultata. Določa vrsto poslane kode rezultata, tako da lahko ustrezno obravnavamo vrednost.

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

  - **SusClientId** – ID za storitev Windows Update za napravo, v kateri se izvaja Office.

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

  - **Level** – Označuje vrsto dogodka.

  - **Name** – Ime dogodka. Omogoča nam, da določimo dogodek, ki ga je poslal odjemalec.

  - **Rule** – Identifikator pravila, ki je ustvarilo podatke (če je te ustvarilo pravilo). Omogoča določitev vira dela podatkov, tako da lahko preverimo veljavnost parametrov dogodkov in jih upravljamo.

  - **RuleId** – Identifikator pravila, ki je ustvarilo podatke (če je te ustvarilo pravilo). Omogoča določitev vira dela podatkov, tako da lahko preverimo veljavnost parametrov dogodkov in jih upravljamo.

  - **RuleInterfaces** – Vsi vmesniki, ki jih uveljavi določeno pravilo. Omogoča, da razvrstimo in uvozimo podatke glede na njihovo strukturo ter tako poenostavimo obdelavo podatkov.

  - **RuleVersion** – Identifikator pravila, ki je ustvarilo podatke (če je te ustvarilo pravilo). Omogoča določitev vira dela podatkov, tako da lahko preverimo veljavnost parametrov dogodkov in jih upravljamo.

  - **SampleRate** – navedbo, Kolikšen odstotek uporabnikov pošilja ta del podatkov. Na ta način lahko izvedemo statistične analize podatkov in za zelo pogosta podatkovna mesta ne zahtevajo, da jih pošljejo vsi uporabniki.

  - **SchemaVersion** – Različica sheme, ki je uporabljena za ustvarjanje diagnostičnih podatkov. Zahtevano za upravljanje podatkov, poslanih iz odjemalca. Omogoča, da lahko sčasoma spremenimo vrsto podatkov, ki jih pošilja odjemalec.

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

  - **SamplingClientIdValue** – Vrednost ključa, s katerim je določeno vzorčenje. Omogoča, da lahko prepoznamo razlog za vzorčenje oz. izključitev iz vzorčenja za določeno sejo.

  - **SamplingDeviceIdValue** – Vrednost ključa, s katerim je določeno vzorčenje. Omogoča, da lahko prepoznamo razlog za vzorčenje oz. izključitev iz vzorčenja za določeno sejo.

  - **SamplingKey** – Ključ, uporabljen za določanje, ali je seja vzorčna ali ne. Omogoča prikaz podatkov, ki določajo, ali je seja vzorčna ali ne.

  - **SamplingMethod** – Način, uporabljen za določanje pravilnika vzorčenja. Omogoča razumevanje vrste podatkov, ki jih ustvarja seja.

  - **SamplingSessionKValue** – Dodatni metapodatki vzorčenja. Omogoča ocenjevanje statističnega pomena prejetih podatkov.

  - **SamplingSessionNValue** – Dodatni metapodatki vzorčenja. Omogoča ocenjevanje statističnega pomena prejetih podatkov.

  - **Sequence** – Enolični številski identifikator seje. Omogoča naročanje sej za analizo težav.

  - **Start** – Čas zagona seje postopka. Omogoča določitev časa začetka izvajanja seje.

  - **TelemetryPermissionLevel** – Vrednost, ki določa, katero raven diagnostičnih podatkov je izbral uporabnik. Omogoča razumevanje ravni diagnostičnih podatkov, ki jih bo ustvarila seja.

  - **TimeZoneBiasInMinutes** – Razlika med UTC-jem in lokalnim časom v minutah. Omogoča normaliziranje časov UTC v lokalne čase.

## <a name="data-fields-that-are-common-for-onenote-events"></a>Podatkovna polja, ki so skupna za dogodke storitve OneNote

Naslednja podatkovna polja so skupna za vse dogodke storitve OneNote za Mac, iOS in Android.

> [!NOTE]
> Kadar uporabljate pregledovalnik diagnostičnih podatkov, je prikazano ime »Dejavnost«, »ReportData« ali »Nepričakovano« za dogodke storitve OneNote za Mac, iOS in Android. Če želite najti dejansko ime dogodka, izberite dogodek in si nato oglejte polje »EventName«.

- **Activity_ActivityType** – označuje vrsto tega dogodka dejavnosti. Dejavnost je lahko normalna dejavnost ali dejavnost z visoko vrednostjo.

- **Activity_AggMode** – sporoči sistemu, kako naj združi rezultate dejavnosti. Omogoča, da zmanjšamo količino prenesenih informacij iz uporabnikovega računalnika tako, da združimo rezultate dejavnosti v en dogodek, ki ga redno pošiljamo.

- **Activity_Count** – število izvajanj določene dejavnosti, če pridobljeno število označuje združeni dogodek. Omogoča, da določimo, kolikokrat je bila dejavnost uspešno oz. neuspešno izvedena glede na način združevanja dejavnosti.

- **Activity_CV** – vrednost, ki določa odnos med dejavnostmi in poddejavnostmi. Omogoča, da lahko znova ustvarimo odnos med ugnezdenimi dejavnostmi.

- **Activity_DetachedDurationInMicroseconds** – čas, ko je dejavnost nedejavna in ne izvaja nobenega dejanskega dela, vendar se čas še vedno sešteva za pridobitev skupnega časa dejavnosti.

- **Activity_DurationInMicroseconds** – trajanje izvajanja dejavnosti. Nam omogoča, da prepoznamo težave z učinkovitostjo delovanja, ki negativno vplivajo na uporabniško izkušnjo.

- **Activity_Expiration** – datum v številski obliki označuje, kdaj bo prišlo do ustavitve pošiljanja tega dogodka iz odjemalcev.

- **Activity_FailCount** – število, ki pokaže, kolikokrat je bila ta dejavnost neuspešna

- **Activity_Name** – kratko ime dogodka. Omogoča nam, da določimo dogodek, ki ga je poslal odjemalec.

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

- **UserInfo.OMSTenantId** – najemnik, s katerim je povezana uporabnikova naročnina. Omogoča, da razvrstimo težave in določimo, ali je težava razširjena ali omejena na določen nabor uporabnikov oz. določenega najemnika.

- **UserInfo_OtherId** – seznam psevdonimnih identifikatorjev, ki niso primarni in predstavljajo uporabniške račune.

- **UserInfo_OtherIdType** – seznam vrst računov, ki niso primarni.

## <a name="data-fields-that-are-common-for-outlook-mobile-events"></a>Podatkovna polja, ki so skupna za dogodke aplikacije Outlook Mobile

Outlook Mobile zbira pogosta polja za vsak naš dogodek, tako da lahko zagotovimo, da je aplikacija posodobljena, varna in deluje po pričakovanjih. 

Naslednja podatkovna polja so skupna za vse dogodke storitve Outlook za iOS in Android.

- **aad_tenant_id** – ID najemnika stranke, če je na voljo

- **account_cid** – identifikator s psevdonimom, ki označuje trenutnega uporabnika

- **account_domain** – ime domene računa

- **account_puid** – globalni enolični identifikator uporabnika za Microsoftov potrošniški račun

- **account_type** – sledi tipu računa, kot so Office 365, Google Cloud Cache, Outlook.com itd.

- **action** – ime dejanja dogodka (kot je arhiviraj, izbriši itd.), da lahko zaznamo težavo z določenimi izvedenimi dejanji

- **ad_id** – enolični identifikator za oglaševanje

- **app_version** – trenutna različica aplikacije, ki je nameščena, da bomo lahko zaznali težave, ki vplivajo na določeno različico aplikacije

- **AppInfo. ETag** – enolični identifikator za upravljanje izdaj naših funkcij, da bomo lahko zaznali težave, ki vplivajo na izdane funkcije

- **AppInfo.Language** – trenutna jezikovna nastavitev naprave, da bomo lahko zaznali težave, ki vplivajo na določene jezike

- **AppInfo.Version** – trenutna različica aplikacije, ki je nameščena, da bomo lahko zaznali težave, ki vplivajo na določene različice aplikacije

- **CI** – enolična oznaka naprave z značilnim psevdonimom

- **cid_type** – označuje, katero vrsto računa imate, na primer trgovski račun ali račun Outlook.com.

- **cloud** – kje v napravi se nahaja nabiralnik računa za zaznavanje težav določenega nabiralnika v oblaku, kot sta Office 365 ali GCC.

- **customer_type** – označuje vrsto stranke (potrošnik, komercialna stranka, tretja oseba itd.), da bomo lahko zaznali težave, ki vplivajo na določene vrste strank

- **device_category** – označuje vrsto naprave (telefon, tablični računalnik itd.), da bomo lahko zaznali težave določene vrste naprav

- **DeviceInfo.Id** – enoličen identifikator naprave, da bomo lahko zaznali težave določene naprave

- **DeviceInfo.Make** – znamka naprave (na primer Apple, Samsung, itd.), da bomo lahko zaznali težave določene znamke

- **DeviceInfo.Model** – model naprave (na primer iPhone 6s), da bomo lahko zaznali težave določenega modela

- **DeviceInfo.NetworkType** – trenutno omrežje naprave v uporabi (Wi-Fi, mobilno omrežje itd.), da bomo lahko zaznali težave določenega omrežja naprave

- **DeviceInfo.OsBuild** – trenutna gradnja operacijskega sistema naprave, da bomo lahko zaznali težave, ki vplivajo na določene gradnje operacijskega sistema

- **DeviceInfo.OsName** – ime operacijskega sistema (na primer iOS), da bomo lahko zaznali težave, ki vplivajo na določene platforme

- **DeviceInfo.OsVersion** – trenutna različica operacijskega sistema naprave, da bomo lahko zaznali težave, ki vplivajo na določene različice operacijskega sistema

- **DeviceInfo.SDKUid** – enolični identifikator naprave (podobno kot DeviceInfo.Id)

- **EventInfo.InitId** – ID, ki se uporablja za razvrščanje dogodkov prek našega prodajnega lijaka za telemetrijo, da bomo lahko zaznali korenski vzrok težave prodajnega lijaka

- **EventInfo.SdkVersion** – različica kompleta za razvoj programske opreme, ki jo uporabljamo za pošiljanje telemetrije, da bomo lahko zaznali korenski vzrok težave prodajnega lijaka

- **EventInfo.Sequence** – zaporedje za razvrščanje dogodkov prek našega prodajnega lijaka za telemetrijo, da bomo lahko zaznali korenski vzrok težave prodajnega lijaka

- **EventInfo.Source** – nam pove, kateri del kode je poslal dogodek, da bomo lahko zaznali korenski vzrok težave

- **EventInfo.Time** – ura in datum, ko je bil dogodek posredovan z naprave, da bodo lahko naši sistemi uspešno upravljali z dohodnimi dogodki

- **eventpriority** – prioriteta telemetričnega dogodka glede na druge dogodke, da bodo lahko naši sistemi uspešno upravljali z dohodnimi dogodki

- **first_launch_date** – prvi zagon aplikacije, da bomo lahko razumeli, kdaj se je težava začela

- **hashed_email** – identifikator s psevdonimom, ki označuje e-poštni naslov trenutnega uporabnika

- **is_first_session** – sledi temu, če je to prva seja aplikacije za namene iskanja in odpravljanja napak

- **origin** – izvor dejanja. Sporočilo, označeno kot prebrano, lahko na primer izvira iz seznama sporočil ali novega e-poštnega obvestila, kar nam pomaga zaznati težave glede na izvor dejanja

- **PipelineInfo.AccountId** – identifikator s psevdonimom, ki označuje trenutnega uporabnika

- **PipelineInfo.ClientCountry** – trenutna država naprave za zaznavanje težav ali izpadov v določeni državi ali regiji

- **PipelineInfo.ClientIp** – naslov IP, ki je povezan z napravo za iskanje in odpravljanje napak s povezavo

- **PipelineInfo.IngestionTime** – časovni žig, kdaj smo prejeli telemetrijo za ta dogodek

- **Session.Id** – enolični identifikator za sejo aplikacije, da bomo lahko prepoznali težave določene seje

- **Session.ImpressionId** – enolični identifikator za upravljanje izdaj naših funkcij, da lahko zagotovimo uspešno izdajo funkcij za vse uporabnike in naprave

- **ui_mode** – ali uporabnik uporablja svetli ali temni način, da lahko razvrščamo napake uporabniške izkušnje

- **UserInfo.Language** – jezik uporabnika za iskanje in odpravljanje napak pri prevajanju besedil

- **UserInfo.TimeZone** – časovni pas uporabnika za iskanje in odpravljanje napak koledarja


Poleg tega so naslednja polja skupna za vse dogodke storitve Outlook za iOS.

- **DeviceInfo.NetworkProvider** – ponudnik omrežja naprave (na primer Verizon)

- **gcc_restrictions_enabled** – nam pove, če so bile v aplikaciji uporabljene omejitve GCC, tako da lahko zagotovimo, da naše stranke GCC varno uporabljajo našo aplikacijo
 
- **multi_window_mode** – pove nam, ali je uporabnik v napravi iPad z več okni, ki nam pomaga pri zaznavi težav, povezanih z uporabo več oken.

- **office_session_id** – enolični ID, ki sledi seji za povezane Officeove storitve, da lahko zaznamo težave določene integracije Officeovih storitev v Outlooku, kot je Word

- **state** – če je bila aplikacija aktivna, ko je bil dogodek poslan, da bomo lahko zaznali težave določenih stanj aktivnih ali neaktivnih aplikacij


Poleg tega so naslednja polja skupna za vse dogodke storitve Outlook za Android.

- **aad_id** – identifikator imenika Azure Active Directory

- **DeviceInfo.NetworkCost** – označuje trenutni strošek omrežja naprave, ki prikazuje stanje Wi-Fi/mobilnega omrežja/gostovanja, za lažje prepoznavanje težav določenega omrežja naprave

- **is_app_in_duo_split_view_mode** – to nas bo obvestilo, da je bila aplikacija v načinu razdeljenega zaslona Duo.  Ta lastnost je nastavljena samo za naprave Duo (samo Android).

- **is_dex_mode_enabled** – če je omogočen način Samsung DeX, da bomo lahko zaznali težave določenega načina DeX pri napravah Samsung

- **is_sliding_drawer_enabled** – če je omogočen vmesnik s premikajočimi se predali, da bomo lahko zaznali težave, ki jih povzroča naš vmesnik s premikajočimi se predali

- **orientation** – fizična usmerjenost zaslona (pokončno/ležeče), da bomo lahko zaznali težave določene usmerjenosti zaslona

- **os_arch** – arhitektura operacijskega sistema za napravo, da bomo lahko zaznali težave določenih operacijskih sistemov naprave

- **process_bitness** – bitnost procesa (32- ali 64-bitni) za aplikacijo, da bomo lahko zaznali težave določene bitnosti naprave

- **webview_kernel_version**: Različica spletnega ogleda Chromium jedra v napravi, ki nam pomaga odkriti težave z združljivostjo, povezane z različico spletnega pogleda.

- **webview_package_name**: Ime paketa spletnega ogleda v napravi, ki nam pomaga odkriti težave z združljivostjo, povezano z različico spletnega pogleda.

- **webview_package_version**: Različica paketa spletnega ogleda v napravi, ki nam pomaga odkriti težave z združljivostjo, povezane z različico spletnega pogleda.


## <a name="software-setup-and-inventory-data-events"></a>Dogodki podatkov inventarja in nastavitve programske opreme

V nadaljevanju tega članka so navedeni podatkovni podtipi v tej kategoriji:
- [Nastavitev Officea in inventar](#office-setup-and-inventory-subtype)
- [Konfiguracija dodatka za Office](#office-add-in-configuration-subtype)
- [Varnost](#security-subtype)  

### <a name="office-setup-and-inventory-subtype"></a>*Podtip nastavitve Officea in inventarja*

Nameščeni izdelek, različica in stanje namestitve.

#### <a name="addssoaccount"></a>add.sso.account

Tako boste Microsoft opozorili na uspeh ali neuspeh uporabnika, ki je dodal račun prek enotne prijave (SSO).

Zbrana so naslednja polja: 

- **account_type** – vrsto računa, ki ste ga dodali s storitvijo SSO.

- **action_origin** – od koder je bil ustvarjen ta dogodek. (Na primer vrednosti: sso_drawer, sso_add_account, sso_add_account_prompt, sso_settings, sso_oobe).

- **ponudnik** – identifikator paketa software Provider za enotno prijavo.

- **Zvezna država** – trenutno stanje računa (na primer vrednost: ni USPEla, ČAKAJOČa, dodana itd.)


#### <a name="installreferral"></a>install.referral

Ta dogodek je sprožen ob začetni namestitvi aplikacije in zabeleži element, ki je posredoval uporabnika (če je na voljo).

Zbrana so ta polja:

- **install_referrer** – Izdelek ali izkušnja, ki je posredovala uporabnika

 
#### <a name="officeclicktorunupdatestatus"></a>Office.ClickToRun.UpdateStatus

Velja za vse aplikacije za Win32. Omogoča razumevanje stanja postopka Officeove posodobitve (uspešno ali neuspešno s podrobnostmi o napaki)

Zbrana so naslednja polja:

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

- **AppSessionGuid** – Identifikator določene seje aplikacije, ki se je začela z ustvarjanjem procesa in traja vse do konca procesa. Dogodek je oblikovan kot standardni 128-bitni GUID, sestavljen iz štirih delov. Ti štirje deli v vrstnem redu so (1) 32-bitni ID procesa (2) 16-bitni ID seje (3) 16-bitni ID zagona (4) čas ustvarjanja 64-bitnega procesa v UTC 100 ns

- **appVersionBuild** – številka različice za gradnjo aplikacije

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

#### <a name="officeonenoteandroidapponenotelaunchednonactivated"></a>Office.OneNote.Android.App.OneNoteLaunchedNonActivated

*[Ta dogodek je bil prej imenovan OneNote.App.OneNoteLaunchedNonActivated.]*

Zabeleži informacije o stanju aktivacije aplikacije.  Podatke nadzorujemo, saj želimo prepoznati pogoste težave pri aktivaciji. Z analiziranjem teh podatkov odkrijemo tudi področja, ki jih moramo izboljšati.

Zbrana so naslednja polja: 

- **INSTALL_LOCATION** – Označuje, ali je aplikacija vnaprej nameščena ali prenesena iz trgovine.

#### <a name="officeonenoteandroidresetstatus"></a>Office.OneNote.Android.ResetStatus

*[Ta dogodek je bil prej imenovan OneNote.ResetStatus.]*

Signal, ki se uporablja za beleženje težav, na katere uporabnik lahko naleti, ko poskuša ponastaviti aplikacijo.  S to telemetrijo nadziramo, zaznavamo in odpravljamo morebitne težave pri ponastavitvi. 

Zbrana so naslednja polja: 

- **Accounts** – Označuje vrste, če je bil vpis v aplikacijo izveden z računi.

- **Generic String Type** – Vrne rezultat, če gre za celotno ponastavitev za notes_light_data.

- **LaunchPoint** – Mesto, s katerega je bila inicializirana ponastavitev. Morebitne vrednosti: gumb za izpis, napaka pri izpisu, sprožena storitev Intune.

- **Pass** – Označuje, ali je bila ponastavitev uspešna.

#### <a name="officeonenoteandroidsigninsignincompleted"></a>Office.OneNote.Android.SignIn.SignInCompleted

*[Ta dogodek je bil prej imenovan OneNote.SignIn.SignInCompleted.]*

Kritični signal, ki določa uspešnost vpisa. Telemetrija se uporablja za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in stanja storitve.

Zbrana so naslednja polja: 

- **CompletionState** – Končno stanje vpisa – uspešno ali neuspešno. In primeri napak.

- **EntryPoint** – Označuje mesto, s katerega je bil inicializiran vpis.

- **Hresult** – Koda napake.

- **Provider Package ID** – V primero samodejnega vpisa.

- **Result** – Uspelo, ni uspelo, neznano, preklicano.

- **ServerType** – vrne vrsto strežnika, ki ponuja storitev. 

- **SignInMode** – Vpis ali prijava oz. pospešeni samodejni vpis ali prijava.

#### <a name="officeonenoteandroidsigninsigninstarted"></a>Office.OneNote.Android.SignIn.SignInStarted

*[Ta dogodek je bil prej imenovan OneNote.SignIn.SignInStarted.]*

Signal, ki se uporablja za ponazoritev morebitnih težav, nastalih pri uporabi vrstice s sporočili.  S to telemetrijo nadziramo, zaznavamo in odpravljamo morebitne težave pri interakciji vrstice s sporočili

Zbrana so naslednja polja: 

- **EntryPoint** – Označuje mesto, s katerega je bil inicializiran vpis.

- **Result** – Rezultat poteka vpisa.

- **ServerType** – Vrne vrsto strežnika, ki ponuja storitev. 

- **SignInMode** – Vpis ali prijava oz. pospešeni samodejni vpis ali prijava.


#### <a name="officeonenotefirstrunfirstrun"></a>Office.OneNote.FirstRun.FirstRun

Kritični signal, ki se uporablja, da lahko novi uporabniki prvič uspešno zaženejo in začnejo uporabljati OneNote.  Telemetrija se uporablja za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in stanja storitve. Če uporabniki prvič ne morejo zagnati aplikacije, bo to sprožilo dogodek z visoko stopnjo resnosti.

- **AfterOneDriveFrozenAccountError** – označuje napako OneDrive, ko je račun zamrznjen.

- **Poskus** – kolikokrat je treba izvesti uporabniško izkušnjo prvega zagona.

- **IsDefaultNotebookCreated** – označuje, ali je OneNote ustvaril uporabniški privzeti zvezek ali ne.

- **IsDelayedSignIn** – označuje, ali je prvi zagon v zakasnitvi pri vpisu, kjer se uporabniku ni treba vpisati.

- **IsMSA** – označuje, ali je račun Microsoftov račun ali ne.

#### <a name="officeonenotefirstrunfirstrunformsa"></a>Office.OneNote.FirstRun.FirstRunForMSA

Kritični signal, ki se uporablja, da lahko novi uporabniki (Microsoftov račun) prvič uspešno zaženejo in začnejo uporabljati OneNote.

Telemetrija, uporabljena za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in ustreznosti stanja storitve. Če uporabniki prvič ne morejo zagnati aplikacije, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so sledeča polja:

- **Poskus** – kolikokrat je treba izvesti uporabniško izkušnjo prvega zagona.

- **Napaka** – A predmet napake OneNote označuje napako med prvim zagonom, če pride do nje.

- **FAllowAddingGuide** – označuje, ali bo OneNote omogočil ustvarjanje zvezka za vodenje ali ne.

- **FrozenOneDriveAccount** – označuje, ali je račun OneDrive zamrznjen ali ne.

- **IsDefaultNotebookCreated** – označuje, ali je OneNote ustvaril uporabniški privzeti zvezek ali ne.

- **NoInternetConnection** – označuje, ali naprava nima nameščene internetne povezave.

- **ProvisioningFailure** – predmet napake v OneNote, ki označuje napako pri omogočanju uporabe, če pride do nje.

- **ProvisioningFinishedTime** – označuje končni čas, ko OneNote dokonča omogočanje uporabe zvezka med izkušnjo prvega zagona.

- **ProvisioningStartedTime** – označuje začetni čas, ko OneNote začne omogočati uporabo zvezka med izkušnjo prvega zagona.

- **ShowSuggestedNotebooks** – označuje, ali OneNote prikaže funkcijo predlaganega zvezka ali ne.

#### <a name="officeonenotefirstrunfirstrunfororgid"></a>Office.OneNote.FirstRun.FirstRunForOrgId

Kritični signal, ki se uporablja, da lahko novi poslovni uporabniki(AAD/OrgID) prvič uspešno zaženejo in začnejo uporabljati OneNote.  Telemetrija, uporabljena za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in ustreznosti stanja storitve. Če uporabniki prvič ne morejo zagnati aplikacije, bo to sprožilo dogodek z visoko stopnjo resnosti.

- **Poskus** – kolikokrat je treba izvesti uporabniško izkušnjo prvega zagona.

- **Napaka** – A predmet napake OneNote označuje napako med prvim zagonom, če pride do nje.

- **FAllowAddingGuide** – označuje, ali bo OneNote omogočil ustvarjanje zvezka za vodenje ali ne.

- **IsDefaultNotebookCreated** – označuje, ali je OneNote ustvaril uporabniški privzeti zvezek ali ne.

- **ProvisioningFailure** – A predmet napake v OneNote, ki označuje napako pri omogočanju uporabe, če pride do nje.

- **ProvisioningFinishedTime** – označuje končni čas, ko OneNote dokonča omogočanje uporabe zvezka med izkušnjo prvega zagona.

- **ProvisioningStartedTime** – označuje začetni čas, ko OneNote začne omogočati uporabo zvezka med izkušnjo prvega zagona.

#### <a name="officeonenotefirstrunmrureadernotebookentries"></a>Office.OneNote.FirstRun.MruReaderNoteBookEntries 

Signal, ki se uporablja za beleženje težav, na katere lahko naletite med nalaganjem zvezkov pri prvem zagonu.  S to telemetrijo nadziramo, zaznavamo in odpravljamo morebitne težave pri prvem zagonu.

Zbrana so naslednja polja: 

- **OnPremNBCount** – Število zvezkov v strežniku na mestu uporabe.

- **TotalNBCount** – Skupno število zvezkov, povezanih z uporabniškim računom.

#### <a name="officetargetedmessagingensurecached"></a>Office.TargetedMessaging.EnsureCached 

Spremlja prenos paketa za Dynamic Canvas. Obravnavamo ga kot konfiguracijo programske opreme, ker mora biti paket uspešno prenesen, da odjemalec lahko uporablja ustrezno izkušnjo. Še posebej je pomemben pri naročninah za potrošnike, kjer prek platna komuniciramo z uporabnikom, ki mu je potekla licenca. S tem dogodkom spremljamo metapodatke paketa dinamične vsebine, prenesene z izdelkom in shranjene v predpomnilnik, ter rezultate izvedenih postopkov za paket: napake pri prenosu, napake pri razpakiranju, napake pri preverjanju doslednosti, zadetki v predpomnilniku, uporabe paketa, viri prenosov.

Zbrana so sledeča polja:

  - **Data\_CacheFolderNotCreated** – Logična zastavica, ki označuje, ali je bila mapa predpomnilnika uspešno ustvarjena.

  - **Data\_CdnPath – Izvorni naslov paketa.**

  - **Data\_EnsureCached** – Logična zastavica, ki označuje, ali je bil paket vsebine shranjen v predpomnilnik.

  - **Data\_ExistsAlready** – Logična zastavica, ki označuje, da je bil paket že prenesen v preteklosti in da je bil zaznan vnovični poskus prenosa.

  - **Data\_GetFileStreamFailed** – Izvorni paket ni na voljo v izvorni datoteki.

  - **Data\_GetFileStreamFailedToCreateLocalFolder** – Težave z lokalnim diskom, zaradi katerih prihaja do napak pri ustvarjanju imenika.

  - **Data\_GetFileStreamFromPackageFailed** – Zastavica, ki označuje, da je bil paket prenesen, vendar ga odjemalec ne more brati.

  - **Data\_GetFileStreamFromPackageSuccess** – Uspešni poskusi branja paketa.

  - **Data\_GetFileStreamSuccess** – ni zaznanih težav z diskom ali konfiguracijo, ki bi preprečevale branje toka datoteke

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

- **SolutionId** – ID rešitve

- **StoreType** – označuje izvor aplikacije.


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

Podatki o uspešnem oz. neuspešnem pridobivanju posodobljenih podatkov o dodatkih, ki so bili dodeljeni najemniku storitve Office 365. Z njim ustvarjamo metrike ustreznosti stanja, grafikone in analize težav uporabnikov. »ExchangeGetLastUpdate« se vedno začne izvajati ob zagonu kot del kode gostitelja in določa, ali so bile dodelitve dodatkov spremenjene za uporabnika.  Če je tako, potem Weldgen. Datoteka DLL bo naložena, tako da lahko pokličemo ExchangeGetEntitlements, da dobimo določene dodelitve (in ExchangeGetManifests bodo pozvani, da pridobijo nove manifeste, ki so potrebni).   Na zahtevo lahko prikličemo tudi »ExchangeGetEntitlements« (in »ExchangeGetManifests«), ko je zagnana gostiteljska aplikacija.   Veliki DLL se ne naloži, če ga ne potrebujemo.   Brez tega dogodka v polju »Required« ni mogoče prepoznati, da uporabniki niso uspešno pridobili njim dodeljenih dodatkov, če je bil prvi klic storitve neuspešen.   To je tudi glavni pokazatelj morebitnih težav s preverjanjem pristnosti med povezovanjem s storitvijo.

Zbrana so sledeča polja:

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

  - **MsoHttpResult –** je vrnjena vrednost enumeriranega vmesnika http API

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

  - **ManifestsReturned** – število manifestov, vrnjenih iz strežnika

  - **ManifestsToRetrieve** – število manifestov, ki jih je treba dobiti iz strežnika

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


#### <a name="officeprogrammabilityaddinsinternalsetconnectenterprise"></a>Office.Programmability.Add-ins.InternalSetConnectEnterprise

Dogodek, ki je ustvarjen pri nalaganju dodatka COM v napravi s paketom Enterprise. Uporablja se za določanje težav pri uvedbah, učinkovitosti delovanja in zanesljivosti z Officeovimi dodatki. 

Zbrana so naslednja polja:

  - **Acitivity Result** – stanje uspešne povezave *[To polje je bilo odstranjeno iz tekočih različic Officea, vendar se lahko še vedno prikaže v starejših različicah.]*

  - **AddinConnectFlag** – predstavlja vedenje nalaganja 

  - **AddinDescriptionV2** – opis dodatka

  - **AddinFileNameV2** – ime datoteke dodatka, brez poti datoteke

  - **AddinFriendlyNameV2** – prijazno ime dodatka

  - **Add-inId** – ID razreda dodatka *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar se bo morda še vedo pojavljalo v starejših graditvah.]*

  - **AddinIdV2** – ID razreda dodatka

  - **AddinProgIdV2** – ID programa dodatka

 - **AddinProviderV2** – ponudnik dodatka

  - **Add-inTimeDateStamp** – časovni žig dodatka iz metapodatkov DLL *[To polje je bilo odstranjeno iz tekočih različic Officea, vendar se lahko še vedno prikaže v starejših različicah.]*

  - **AddinTimeDateStampV2** – časovni žig dodatka iz metapodatkov DLL.

  - **AddinVersionV2** – različica dodatka

  - **IsBootInProgress** – ali je Officeov program v postopku zagona.
 
  - **LoadDuration** – čas, potreben za nalaganje dodatka
  
  - **LoadResult** – stanje uspeha nalaganja


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

  - **Data\_Error**:**integer** – ID napake

### <a name="security-subtype"></a>*Podtip varnosti*

Stanje napak dokumentov, funkcij in dodatkov, ki lahko ogrozijo varnost in pripravljenost izdelka za posodobitve.

#### <a name="officeappguardcreatecontainer"></a>Office.AppGuard.CreateContainer

Zbrali smo šifre napak in ali je bil vsebnik že prisoten ali ne. Prav tako zbiramo šifre napak za dogodek ponastavitve, če ne bi bilo mogoče ustvariti vsebnika v prvem poskusu. Uporabljeni bodo podatki, ki označujejo odstotek sej, ki jih uspešno ustvarjamo za začetek uporabe Officeovih aplikacijskih stražarjev. Podatki bodo Microsoftu omogočili, da prepoznajo in naslovijo šifre napak iz ustvarjanja kontejnerja.

Zbrana so naslednja polja:

- **ErrorCode1** – vrsta kode napake pri nastavitvi vsebnika.  

- **ErrorCode2** – koda napake od izvršitve ustvarjanja. 

- **ErrorCode3** – dodatna koda napake. 

- **ID** – Enolični identifikator (GUID) za ustvarjanje vsebnika.

- **ResetError** – koda napake, s katero poskuša ponastaviti posodo po spodletelem poskusu.

- **ResetErrorCode1** – vrsta napake pri nastavitvi vsebnika po ukazu »Ponastavi«. 

- **ResetErrorCode2** – koda napake od izvršitve ustvarjanja.

- **ResetErrorCode3** – dodatna koda napake po ponastavitvi ukaza.

- **ResetErrorType** – vrsta napake med ponastavitvijo: ustvarjanje, Priprava datoteke ali zagon.

- **WarmBoot** – ugotovi, ali je bil vsebnik že ustvarjen ali ne.

#### <a name="officeappguardlaunchfile"></a>Office.AppGuard.LaunchFile

V tem primeru se prikaže rezultat izvršitve datoteke programa Guard. Določili bomo lahko odstotek sej, pri katerih je bila uspešno zagnana Wordova, Excelova ali PowerPointa datoteka in kode napak za neuspele poizkuse.

Zbrana so sledeča polja:

- **AppId** – identificira, katera aplikacija je v postopku zagona.

- **DetachedDuration** – identificira skupni las, ki ga je porabila združena dejavnost. 

- **ErrorCode1** – vrsta kode napake pri nastavitvi vsebnika.  

- **ErrorCode2** – koda napake od izvršitve ustvarjanja. 

- **ErrorCode3** – dodatna koda napake. 

- **FileId** – enolični identifikator (GUID), ki ga je vrnil Windows API po zagonu datoteke.

- **Id** – enolični identifikator (GUID) za zagon in ustvarjanje datoteke. Ta ID je uporabljen za določanje korelacije dogodkov iz Officea in sistema Windows.

- **ResetError** – koda napake, s katero poskuša ponastaviti posodo po spodletelem poskusu.

- **ResetErrorCode1** – vrsta napake pri nastavitvi vsebnika po ukazu »Ponastavi«. 

- **ResetErrorCode2** – koda napake od izvršitve ustvarjanja.

- **ResetErrorCode3** – dodatna koda napake po ponastavitvi ukaza.  

- **ResetErrorType** – vrsta napake: ustvarjanje, PrepFile ali Launch.



#### <a name="officesecurityactivationfilterclsidactivated"></a>Office.Security.ActivationFilter.CLSIDActivated

Spremlja, kdaj je določeni identifikator CLSID (Flash, Silverlight itd.) aktiviran v Officeu. S tem dogodkom spremljamo vpliv blokiranja kontrolnikov za Flash, Silverlight in Shockwave na končne uporabnike.

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

Spremlja, kdaj je varnostni poziv prikazan uporabniku ob nalaganju kontrolnika ActiveX, ki je označen kot nevaren za inicializacijo. Z njim ocenimo razširjenost kontrolnikov UFI ActiveX v Officeovih dokumentih za zagotavljanje ukrepov za zmanjševanje tveganja (na primer kontrolniki »killbit«) kot odziv na varnostne dogodke.

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

#### <a name="accountaction"></a>account.action

S tem dogodkom zagotovimo, da konfiguracija računa deluje uspešno, in ga uporabljamo za spremljanje stanja pri ustvarjanju računa, zmožnost dodajanja novih e-poštnih računov in za spremljanje ponastavitev računov 

Zbrana so sledeča polja: 

- **account_calendar_count** – število koledarjev v računu
 
- **action** – vrsta izvedenega dejanja, na primer create_account, delete_account.
 
- **duration_seconds** – trajanje dejanja
 
- **entry_point** – vstopna točka dejanja, način, kako je uporabnik zagnal dejanje
 
- **has_hx** – ali je v napravi nastavljen račun, ki uporablja našo novo storitev za sinhronizacijo pošte; ni nujno, da gre za račun, v katerem je bilo dejanje izvedeno
 
- **is_hx** – je račun, ki uporablja našo novo storitev za sinhronizacijo pošte
 
- **is_shared_mailbox** – ali dejanje pripada nabiralniku v skupni rabi
 
- **number_of_accounts** – skupno število računov, v katerih je bilo izvedeno dejanje
 
- **result** – rezultat dejanja, na primer »uspelo« ali »ni uspelo«.
   
- **server_type** – vrsta strežnika za račun, podobno polju account_type
 
- **shared_type** – vrsta računa v skupni rabi (če je omogočena skupna raba računa)
 
- **scope** – obseg dejanja; za brisanje računa, this_device ali all_devices
 
- **total_calendar_accounts** – število računov koledarja v aplikaciji, ko je bilo izvedeno dejanje
 
- **total_email_accounts** – število e-poštnih računov v aplikaciji, ko je bilo izvedeno dejanje
 
- **total_file_accounts** – število računov datotek v aplikaciji, ko je bilo izvedeno dejanje

#### <a name="accountlifecycle"></a>account.lifecycle

Ta dogodek je zbiramo zato, da konfiguracija računa deluje uspešno, in ga uporabljamo za spremljanje stanja pri ustvarjanju računa, zmožnost dodajanja novih e-poštnih računov in za spremljanje ponastavitev računov

Zbrana so sledeča polja: 

- **account_creation_source** – izbirna lastnost, uporabljena za iskanje in diagnosticiranje morebitnih težav, do katerih pride med ustvarjanjem računa, ko je dodana vrsta dejanja.  Ima lahko vrednosti, kot so enotna prijava (SSO), create_new_account, manual, itd.

- **action** – vrsta dejanja, izvedena v računu, kot je na primer dodajanje, odstranjevanje ali ponastavljanje

#### <a name="addnewaccountstep"></a>add.new.account.step

S tem dejanjem lahko zaznamo, v kolikšni meri je uporabnik dokončal postopek ustvarjanja novega obrazca računa.  Označuje, kdaj se je uporabnik premaknil na naslednji korak oz. ali je postopek opustil.  S temi informacijami lahko zaznamo, ali kateri od korakov ne deluje, in poskrbimo, da bo postopek ustvarjanja uporabniškega računa uspešen. 

Zbrano je sledeče polje: 

- **OTAddAccountCurrentStep** – ima lahko te vrednosti: profile_form, redirect_mobile_check, mobile_check_success

#### <a name="apperror"></a>app.error

Spremlja kritične napake aplikacije, da lahko preprečimo težave, ki bi lahko povzročile zrušitev vaše aplikacije ali vam preprečevala branje e-pošte.

Zbrana so sledeča polja: 

- **clientName** – ime odjemalca za datoteko v oblaku, v kateri se je pojavila napaka (če je na voljo).

- **cloudfile_error_type** – vrsta napake, ki se je pojavila v datoteki v oblaku (če je na voljo).

- **cloudfile_response_name** – ime odziva za napako, ki se je pojavila v datoteki v oblaku (če je na voljo).

- **component_name** – ime komponente aplikacije, v kateri se je pojavila napaka, na primer pošta ali koledar.

- **debug_info** – informacije o napaki, ki se je pojavila v datoteki v oblaku, s katerimi lahko ugotovimo vzrok napake.

- **error_origin_identifier** – izvor napake, ki se je pojavila v osnutku (če je na voljo).

- **error_type** – vrsta napake, ki se je pojavila. Nekateri primeri vključujejo napake pri shranjevanju osnutka, pošiljanju osnutka in napake datoteke v oblaku.

- **exdate** – datum razširjenega pravila (velja le za napake pri ponavljajočih se sestankih) *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar se lahko še vedno prikaže v starejših graditvah.]*

- **exrule** – vrednost razširjenega pravila (velja le za napake pri ponavljajočih se sestankih) *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar se lahko še vedno prikaže v starejših graditvah.]*

- **has_attachments** – prikaže, ali ima osnutek, v katerem se je pojavila napaka, priloge (če so na voljo).

- **is_IRM_protected** – prikaže, ali je osnutek, v katerem se je pojavila napaka, zaščiten z upravljanjem pravic do informacij (če so na voljo).

- **is_legitimate** – prikaže, ali je izvor napake v kodi. Napake pri programiranju se obravnavajo kot nelegitimne.

- **is_local** – prikaže, ali je osnutek, v katerem se je pojavila napaka, sinhroniziran s strežnikom (če je na voljo).

- **is_recoverable** – prikaže, ali je napako mogoče obnoviti oz. gre za kritično napako.

- **rdate** – datum pravila ponovitve (velja le za napake pri ponavljajočih se sestankih) *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar se lahko še vedno prikaže v starejših graditvah.]*

- **rrule** – samo pravilo ponovitve (velja le za napake pri ponavljajočih se sestankih) *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar se lahko še vedno prikaže v starejših graditvah.]*

- **rrule_error_message** – sporočilo o napaki pri razčlenjevanju pravila ponovitve (velja le za napake pri ponavljajočih se sestankih) *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar se lahko še vedno prikaže v starejših graditvah.]*

- **rrule_error_type** – vrsta napake pri razčlenjevanju pravila ponovitve (velja le za napake pri ponavljajočih se sestankih) *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar se lahko še vedno prikaže v starejših graditvah.]*

- **status_code** – koda stanja za napako, ki se je pojavila. Pomaga nam razumeti vzrok napake.

Vsi znaki so lahko tudi morebitne lastnosti. Tako bolje razumemo znake v telesu in osnutku sporočila, v katerem se je napaka pojavila. Na primer, »a«, »b« in »c« so morebitne lastnosti.

#### <a name="applaunchreport"></a>app.launch.report

S tem dogodkom lahko zaznavamo težave in jih odpravljamo, ko Outlook začne delovati počasneje ali neobičajno, kar uporabnikom otežuje uporabo aplikacije. Dogodek vključuje informacije o posebnih omogočenih lastnosti in o tem, kako dolgi so posamezni deli zagona.

Zbrana so sledeča polja: 

- **is_agenda_widget_active** – prikaže, ali je gradnik dnevnega reda aktiven.

- **is_alert_available** – prikaže, ali je bila aplikacija konfigurirana za omogočanje opozoril in obvestil.

- **is_background_refresh_available** – prikaže, ali je bila aplikacija konfigurirana za osveževanje v ozadju.

- **is_badge_available** – prikaže, ali je bila aplikacija konfigurirana za omogočanje značk in obvestil.

- **is_intune_managed** – prikaže, ali aplikacijo upravlja Intune.

- **is_registered_for_remote_notifications** – prikaže, ali je bila aplikacija registrirana za oddaljena obvestila.

- **is_sound_available** – prikaže, ali je bila aplikacija registrirana za omogočanje zvokov obvestil.

- **is_watch_app_installed** – prikaže, ali je v Outlooku nameščena aplikacija ure.

- **is_watch_paired** – prikaže, ali je Outlookova aplikacija ure seznanjena z glavno Outlookovo aplikacijo.

- **launch_to_db_ready_ms** – prikaže čas, ki ga je Outlook porabil od zagona do stanja pripravljenosti zbirke uporabe.

- **num_calendar_accounts** – prikaže število računov koledarjev v aplikaciji.

- **num_cloud_file_accounts** – prikaže število računov shramb v aplikaciji.

- **num_hx_calendar_accounts** – prikaže število računov koledarjev v aplikaciji, povezanih z našo novo storitvijo za sinhronizacijo pošte.

- **num_hx_mail_accounts** – prikaže število poštnih računov v aplikaciji, povezanih z našo novo storitvijo za sinhronizacijo pošte.

- **num_mail_accounts** – prikaže število poštnih računov v aplikaciji.

#### <a name="calendaraction"></a>calendar.action

Se uporablja za nadzor morebitnih negativnih učinkov na vašo zmožnost izvajanja ključnih dejanj koledarja, kot sta ustvarjanje ali urejanje dogodkov.  Dogodek lahko prav tako vključuje niz z imeni lastnosti in informacije o tem, ali so se spremenile. Imena vključenih lastnosti, kot so »title_changed«, »online_meeting_changed« in »description_changed«, nam pomagajo pri razumevanju, ali je prišlo do težav pri urejanju določenih lastnosti.

Zbrana so sledeča polja: 

- **account_sfb_enabled** – s tem dogodkom zagotovimo, ali je Skype za podjetja pravilno nastavljen. 

- **action** – vrsta dejanja, ki je bila izvedena v koledarju. Vključuje denimo opravila, kot so odpiranje, urejanje, dodajanje bližnjic, dremež itd. Pomaga nam zagotoviti, da koledar deluje po pričakovanjih in da vse funkcije delujejo pravilno. 

- **action_result** – rezultat dejanja, izveden v komponentah koledarja. Vključuje lahko vrednosti, kot so »uspešno«, »neuspešno«, »neznano« in »časovna omejitev«. Se uporablja za spremljanje stopnje uspešnosti za dejanja in določevanje, ali se je pri dejanjih koledarja pojavila razširjena težava. 

- **attendee_busy_status** – prosto/zasedeno stanje udeleženca, s katerim je povezano dejanje. Ta vrednost je lahko »prost«, »zaseden« ali »pogojno sprejeto«. S tem dogodkom lažje razumemo, ali je prišlo do težave z dejanji, ki so povezana z določenim zasedenem stanjem. 

- **availability** – vrednost razpoložljivosti, če se je stanje »prost/zaseden« spremenilo med srečanjem. S tem dogodkom lažje razumemo, ali je prišlo do težav z določeno vrednostjo razpoložljivosti. 

- **calendar_onlinemeeting_default_provider** – vsebuje privzetega ponudnika spletnega srečanja za uporabo pri ustvarjanju strežniškega spletnega srečanja. Vključuje vrste za Skype, Skype za podjetja, Hangout in Teams za podjetja. Ta dogodek uporabljamo pri diagnosticiranju težavi pri ustvarjanju spletnih srečanj določenih ponudnikov. 

- **calendar_onlinemeeting_enabled** – ima vrednost »true«, če koledar podpira ustvarjanje strežniškega spletnega srečanja glede na privzetega ponudnika spletnega srečanja. Pomaga nam razumeti, ali je prišlo do morebitnih težav v koledarjih z omogočenimi spletnimi srečanji. 

- **calendar_type** – vrsta koledarja, v katerem je dogodek, po tem, ko je uporabnik uredil srečanje. Morebitne vrednosti so »primarno«, »sekundarno«, »v skupni rabi« in »skupina«. S tem dogodkom lažje razumemo, ali je prišlo do težav z določeno vrsto koledarja. 

- **delete_action_origin** – izvor izvedenega dejanja izbrisa. Vključuje vrednosti, kot so orodna vrstica za krmarjenje in orodna vrstica v obliki kapsule.  Pomaga nam razumeti, ali je prišlo do morebitnih težav pri brisanju srečanja iz določenega mesta. 

- **distribution_list_count** – število udeležencev, navedenih na seznamih prejemnikov. S pomočjo tega dogodka lahko spremljamo, ali je prišlo do težav z udeleženci, navedenimi na seznamih prejemnikov. 

- **guest_count** – število gostov v srečanju.  S pomočjo tega dogodka lahko zagotovimo, da so bili gostje dodani pravilno. 

- **is_all_day** – se uporablja skupaj z dogodkom »meeting_duration« za določanje, ali gre za celodnevno srečanje. S pomočjo tega dogodka lahko ugotovimo, ali je prišlo do morebitnih težav pri dejanjih, izvedenih v celodnevnih srečanjih. 

- **is_location_permission_granted** – Ali je uporabnik aplikaciji odobril sistemsko lokacijsko dovoljenje. Če je lokacijsko dovoljenje podeljeno, lahko aplikacija v uporabniškem vmesniku prikaže dodatne informacije o koristnosti. Vedeti, ali je dovoljenje za lokacijo odobreno, nam bo omogočilo vedeti, kako pogosto se uporabnikom prikažejo dodatne informacije o uporabnosti.

- **is_organizer** – pomaga nam razumeti, ali je srečanja mogoče urejati in ali jih je organizator ustvaril pravilno. 

- **is_recurring** – pomaga nam razumeti, ali je prišlo do težave, ki vpliva na ponavljajoča se srečanja. 

- **launch_point** – začetna točka dejanja. Lahko vsebuje vrednosti, kot so glava gradnika, noga gradnika, celodnevni gradnik in bližnjica koledarja. S pomočjo tega dogodka lahko razumemo kontekst, v katerem je bilo zagnano dejanje. 

- **location_count** – število lokacij, določenih pri ustvarjanju in urejanju dogodka. S pomočjo tega dogodka lahko razumemo, ali je prišlo do težav pri ustvarjanji ali urejanju dogodkov z določenim številom mest. 

- **location_selection_source_type** – vrsta vira za izbiro lokacije. Lahko vsebuje vrednosti, kot so predlog lokacije, po meri in obstoječe. Pomaga nam diagnosticirati morebitne težave pri izbiri lokacije iz določenega vira. 

- **location_session_id** – ID seje za izbiro lokacije srečanja. Pomaga nam diagnosticirati morebitne težave pri izbiri lokacije srečanja. 

- **location_type** – vrsta izbrane lokacije.  Vsebuje vrste, kot so lokacija po meri, konferenčna soba in Bing. S pomočjo tega dogodka lahko razumemo težave pri dodajanju določenih vrst lokacij srečanju. 

- **meeting_duration** – trajanje srečanja.  S pomočjo tega dogodka lahko za srečanja nastavimo pravilne čase. 

- **meeting_insights_type** – vrsta vpogledov srečanja v podrobnosti dogodka.  Vključuje datoteko in sporočilo. S pomočjo tega dogodka lahko določimo število prikaznih vpogledov srečanja. 

- **meeting_type** – vrsta spletnega srečanja, povezanega z dejanjem.  Vključuje vrste za Skype, Skype za podjetja, Hangout in Teams za podjetja. S pomočjo tega dogodka lahko določimo, ali so spletna srečanja pravilno nastavljena. 

- **origin** – izvor dejanja koledarja. Vključuje vrste, kot so dnevni red, koledar, gradnik za dnevni red itd. S pomočjo tega dogodka lahko zagotovimo pravilno komunikacijo med komponentami koledarja. 

- **recurrence_scope** – vrsta ponovitve srečanja (enkratna ponovitev ali niz).  S pomočjo tega dogodka lahko ugotovimo, ali je prišlo do morebitnih težav pri urejanju različnih vrst ponovitev. 

- **reminder_time** – čas opomnika za srečanje (če se je spremenil).  S tem dogodkom zagotovimo, da se je čas opomnika za srečanje pravilno shranil. 

- **reminders_count** – število opomnikov za dogodek, če so se opomniki spremenili. S tem dogodkom lahko diagnosticiramo težave z več opomniki dogodka. 

- **sensitivity** – občutljivost srečanja. Vključuje vrste, kot so »običajno«, »osebno«, »zasebno« in »zaupno«. S pomočjo tega dogodka lahko ugotovimo, ali je občutljivost srečanja nastavljena pravilno. 

- **session_duration** – trajanje seje v milisekundah. S pomočjo tega dogodka lahko ugotovimo, ali je prišlo do napak, ki povečujejo trajanje, zahtevano za izvedbo dejanja koledarja. 

- **shared_calendar_result** – rezultat dejanja, izvedenega v koledarju v skupni rabi. Razpoložljive možnosti so: »v redu«, »brez dovoljenja«, »neznano«, »lastnik na mestu uporabe« in »lastnik je skupina«. S pomočjo tega dogodka lahko ocenimo zanesljivost dejanj, izvedenih v koledarjih v skupni rabi. 

- **time_picker_origin** – izvor izbirnika časa za dejanje shranjevanja. Vključuje vrednosti, kot so »več možnosti« in »manj možnosti«. S pomočjo tega dogodka lahko ugotovimo, kako je uporabnik shranil srečanje, in se prepričamo, da ta funkcija deluje pravilno. 

- **title** – samodejni naslov, predlagan iz vrednosti, določene v aplikaciji. Vključuje vrednosti, kot so »Klic«, »Kosilo« in »Skype«. S pomočjo tega dogodka lahko ugotovimo, ali je samodejni predlog nastavljen pravilno. 

- **txp** – vrsta rezervacije dogodka (če je na voljo). Vključuje vrste, kot so rezervacija dogodka, rezervacija leta, rezervacija najema avtomobila itd. S pomočjo tega dogodka lahko ugotovimo, ali kartice za rezervacijo delujejo pravilno. 

- **upcoming_event_count** – število prihajajočih dogodkov, prikazanih v pogledu prihajajočih dogodkov. S pomočjo tega dogodka ugotovimo, ali je prišlo do težav s pogledom prihajajočih dogodkov. 

- **upcoming_event_seconds_until_event** – število sekund, do začetka naslednjega dogodka. S pomočjo tega dogodka ugotovimo običajne dogodke, ki so prikazani v pogledu prihajajočih dogodkov. 

- **value** – podrobnosti dejanja, kot so trajanje zakasnitve alarma ali kategorija »Ponavljaj do«. S pomočjo tega dogodka lahko razumemo kontekst, v katerem je bilo izvedeno dejanje. 

#### <a name="combinedsearchuse"></a>combined.search.use

Se uporablja za nadzor morebitnega negativnega učinka na vašo zmožnost izvajanja ključnega iskanja, kot so iskanje pošte, stikov ali dogodkov.

Naslednja polja so zbrana v operacijskih sistemih iOS in Android: 

- **account_switcher_action_type** – ta vrsta dejanja spremlja, ali je uporabnik uporabil preklopnik med računi v načinu preprostega odkrivanja ali je preklopil na drug račun.

- **action_type** – vrsta dejanja, ki je bila izvedena v funkciji iskanja. Določa, ali je bila zagnana funkcija iskanja, se ponavlja oziroma je bila končana ter prepozna, katera dejanja so bila izvedena med iskanjem, na primer ali je bil uporabljen mikrofon. Ta dogodek nam omogoča, da zagotavljamo natančna in pomenljiva iskanja. 

- **conversation_id** – enolični ID za posamezno sejo iskanja (na primer vsakič, ko uporabnik vnese element v iskalno polje)

- **entrance_type** – določa način, kako je uporabnik zagnal poizvedbo iskanja na zavihku za iskanje, iz ničelne poizvedbe, naslova iskanja ali rezultata iskanja. 

- **has_contact_results** – ali so rezultati stika prikazani v poizvedbi iskanja.

- **include_deleted** – ali so v rezultatih iskanja prikazane izbrisane možnosti. 

- **is_ics_external_data** – Zajame, če je dodan dogodek interni (tj. dodan v Outlooku v koledar Outlook) ali zunanji (tj. dodan iz druge e-poštne aplikacije, kot je Gmail za koledar Outlook).

- **is_network_fully_connected** – To je namig za razlog za iskanje brez povezave. Če je omrežje povezano in iskanje poteka brez povezave, je verjetno razlog časovna prekinitev strežnika

- **is_offline_search** – ali je seja iskanja iskanje brez povezave na podlagi rezultatov iskanja, ki jih je vrnil hx

- **re_enter_search_tab** – logična vrednost, ki ponazarja, ali je uporabnik pred izbiro rezultata preklopil na drug zavihek.

- **result_selected_type** – kakšno vrsto prikazanih podatkov uporablja uporabnik. Na primer, ali so prikazani vsi stiki, pogovori, dogodki itd. 

- **search_conversation_result_data** – vsebuje podatke o pogovoru, izbranem med rezultati iskanja, vključno z vrsto računa (hx, ac itd.), ali je sporočilo shranjeno v storitvi v oblaku in ali je zamik strani prikazan na isti strani kot prvo sporočilo. 

- **search_origin** – vir iskanja, na primer glasovni pomočnik, Cortana, vnos s tipkovnico itd. 

- **search_scope** – niz, ki prikazuje vrsto računa, izbrano za iskanje (npr. Exchange, Gmail itd.), ali če je bila izbrana možnost iskanja v vseh računih. 

- **search_suggestion_type** – prikazuje element za predlogom za iskanje, na primer, ali gre za popravek črkovanja? Ali temelji na zgodovini? Funkcija samodokončanja?

- **search_request_reason** – prikazuje vzrok, zakaj je bila iz aplikacije poslana zahteva za iskanje, in ponazarja komponento oz. dejanje uporabnika, priklicano s funkcijo iskanja.

- **search_result_filter_type** – prikazuje vrsto filtra, ki je bila uporabljena za funkcijo iskanja, ter prikazuje vso vsebino ali samo priloge.

Naslednja polja so zbrana v iOS aplikacijah Outlook Mobile: 

- **action** – vrsta dejanja, ki je bila izvedena v funkciji iskanja. Določa, ali je bila zagnana funkcija iskanja, se ponavlja oziroma je bila končana ter prepozna, katera dejanja so bila izvedena med iskanjem, na primer ali je bil uporabljen mikrofon. Ta dogodek nam omogoča, da zagotavljamo natančna in pomenljiva iskanja.

- **answer_result_selected_count** – število uspešnih iskanj; na primer, ali je uporabnik našel iskano osebo? Ali je bilo ustvarjeno e-poštno sporočilo? Ali je bilo sporočilo dodane med zaznamke? 

- **contact_result_in_full_list_selected_count** – število, ko je uporabnik v pogledu polnega seznama izbral možnost »Prikaži vse stike« med sejo kombiniranega iskanja.

- **contact_result_selected_count** – število izbranih rezultatov stikov med sejo kombiniranega iskanja.

- **conversation_result_selected_count** – število izbranih pogovorov med sejo kombiniranega iskanja.

- **mail_paging_gesture_count** – spremlja število izvedenih potez ostranjevanja iskanja pošte v seji združenega iskanja 

- **mail_requests_count** – sledi, koliko zahtev za iskanje po pošti je bilo poslanih v kombinirani iskalni seji

- **people_filter_selected_contacts_count** – sledi, koliko stikov je bilo izbranih v filtru ljudi

- **search_session_ended_type** – prikazuje mesto, kjer se je iskanje zaključilo, ker je bila poizvedba preklicana ali posodobljena.

- **search_suggestion_type** – prikazuje element za predlogom za iskanje, na primer, ali gre za popravek črkovanja? Ali temelji na zgodovini? Funkcija samodokončanja?

- **see_all_contacts_selected_count** – kolikokrat je bila med sejo kombiniranega iskanja izbrana možnost »Prikaži vse stike«.

- **subtab_type** – spremlja, kje uporabnik izbere rezultat s katerega zavihka z rezultati

- **top_mail_result_selected_count** – kolikokrat je uporabnik izbral prikazane najpomembnejše rezultate.

- **ui_reload_result_count** – posname čas vnovičnega nalaganja uporabniškega vmesnika zaradi posodobitve nabora rezultatov (med ustrezno poizvedbo)

- **ui_reload_result_time** – posname celoten čas, porabljen za vnovično nalaganje uporabniškega vmesnika zaradi posodobitve nabora rezultatov (med ustrezno poizvedbo)

- **ui_reload_status_count** – posname čas vnovičnega nalaganja uporabniškega vmesnika zaradi posodobitve stanja (med ustrezno poizvedbo)

- **ui_reload_status_time** – posname celoten čas, porabljen za vnovično nalaganje uporabniškega vmesnika zaradi posodobitve stanja (med ustrezno poizvedbo)

#### <a name="composemailaccessory"></a>compose.mail.accessory

S tem dogodkom lahko zaznamo in odpravimo težave z dejanji ključnih komponent, da ne boste naleteli na težave pri prilaganju datoteke, zajemu fotografije kot priloge ali pošiljanju svoje razpoložljivosti.

Zbrana so sledeča polja: 

- **action** – ponazarja dejanje, ki se je poskušalo izvesti med zapisom dejanja. Nekateri primeri vključujejo prilaganje datoteke in prikaz več možnosti.

- **icon_name** – ponazarja ime ikone, ki je prikazana med zapisom dejanja.
 
- **origin** – sporoča izvor dejanja. Možni vrednosti sta quick_reply in full_screen.

- **toolbar_type** – sporoča vrsto orodne vrstice, predstavljene na strani za sestavljanje. Možni vrednosti sta compose_actions in formatting.


#### <a name="conversationviewaction"></a>conversation.view.action

Se uporablja za nadzor morebitnega negativnega učinka na vašo zmožnost ogledovanja e-poštnih sporočil in odgovarjanja nanje.

Zbrana so sledeča polja:

- **contains_mention** – ponazarja, ali je bila v pogovoru uporabljena oznaka @, s katero si pomagamo pri odkrivanju težav pri e-poštnih objavah.

- **conversation_type** – ponazarja vrsto upodobljenega e-poštnega sporočila, na primer pogled enega sporočila ali pogled več sporočil. S pomočjo tega dogodka lahko zaznavamo težave, povezane z določeno vrsto sporočila v našem pogledu e-poštnega pogovora.

- **hx_error_type** – sporoči, katera napaka je prepovedala storitvi dokončanje odstranitve, posodobitve ali dodajanja odziva za sporočilo.

- **hx_string_tag** – sporoči oznako napake v bazi kod storitve

- **reaction_origin** – pove nam, od kod je uporabnik reagiral 

- **reaction_type** – sporoči nam vrsto reakcije uporabnika

- **suggested_reply_char_count** – število znakov v predlaganem odgovoru (če je na voljo), s katerim lažje zaznamo odstopanja in težave, povezane z našimi predlogi.

- **suggested_reply_click_pos** – položaj upodobitve predlaganega odgovora (če je na voljo), s katerim lažje zaznamo težave z določenim predlogom.

- **suggested_reply_type** – označuje vrsto predlaganega odgovora za to dejanje. Možne vrednosti so text, send_avail in create_meeting.

- **use_default_quick_reply_mode** – prikazuje, ali je bil uporabljen privzeti način hitrega odgovora, s katerim lažje zaznamo težave, povezane z izkušnjo hitrih odgovorov v e-pošti.

#### <a name="draftaction"></a>draft.action

Se uporablja za nadzor morebitnega negativnega učinka na vašo zmožnost ustvarjanja in shranjevanja osnutkov e-pošte.

Zbrana so sledeča polja: 

- **action** – vrsta dejanja, na primer »shrani« ali »zavrzi«.
 
- **draft_message_id** – ID sporočila osnutka.

- **is_groups** – ali je bil osnutek poslan skupinski mapi ali iz nje.
 
- **origin** – vir osnutka, na primer »podrobnosti sporočila«, »sestavi«.

- **smart_compose_model_version** – spremlja, katero različico modela Smart sestavite uporabljamo

- **suggestions_requested** – označuje, koliko predlogov za pametno sestaviti je bilo zahtevano

- **suggestions_results** – rezultat pametnega sestavljanja predloga, ki je bil sprejet oz. zavrnjen

- **suggestions_returned** – označuje, koliko pametnih predlogov za sestavljanje je vrnjenih iz strežnika

- **suggestions_shown** – označuje, koliko pametnih predlogov za sestavljanje je prikazano uporabniku
 
- **thread_id** – ID za nit pogovora, s katerim je povezan osnutek

#### <a name="draganddrop"></a>drag.and.drop

V tem primeru lahko zaznamo, ali je bilo dejanje »povleci in spusti« uspešno ali ne.  Z njim poskrbimo, da izkušnja vlečenja in spuščanja pravilno deluje v vseh aplikacijah, tako kot dogodek vlečenja v Outlook kot tudi dogodek vlečenja, s katerim uporabnik vsebino odvleče iz Outlooka.  S temi podatki lahko poskrbimo, da celotna izkušnja v drugih aplikacijah deluje v skladu s pričakovanji.

Zbrana so sledeča polja: 

- **action** – dejanje bo bodisi vlečenje bodisi spuščanje

- **location** – v primeru dejanja vleka bomo s tem izvedeli, s katerega mesta je uporabnik začel vlečenje.  V primeru odložitve bomo izvedeli, kje je uporabnik odložil datoteko, ki jo je vlekel. 

- **vir** – če gre za dejanje spuščanja, nam to sporočite, na kateri lokaciji je uporabnik zagnal funkcijo» povleci «. Tako boste lažje odkrivali težave z določenim virom, kot je OneDrive ali datoteke, na določeno mesto za spuščanje, kot je na primer nova e-poštna sporočila.

#### <a name="drawerevent"></a>drawer.event

Se uporablja za nadzor morebitnega negativnega učinka na vašo zmožnost dostopanja do map v nabiralniku.

Zbrana so sledeča polja:

- **add_calendar_option** – ponazarja vrsto koledarja, ki je bil dodan iz predala, tj. koledar zanimivosti, koledar pošte, koledar v skupni rabi, s katerim lahko lažje zaznamo težave, povezane z določenimi vrstami koledarjev.

- **calendar_accounts_count** – ponazarja število računov koledarja, s katerim lahko zaznamo težave, povezane s številom računov, katerih lastnih ste.

- **calendar_apps_count** – ponazarja število aplikacij koledarja, nameščenih v napravi uporabnika, s katerim lahko zaznavamo težave, povezane z aplikacijami koledarja.

- **drawer_type** – ponazarja vrsto predala: koledar, pošta ali ničelna poizvedba za zaznavanje težav, povezanih z vrsto predala.

- **from_favorites** – ponazarja, ali je bilo dejanje izvedeno iz priljubljenih, in nam pomaga zaznati težave, povezane s priljubljenimi.

- **group_calendar_count** – ponazarja število koledarjev za račun, s katerim lahko zaznamo težave, povezane s koledarji skupine

- **inbox_unread_count** – ponazarja število neprebranih sporočil v nabiralniku, s katerim lahko zaznamo težave pri prikazu števila neprebranih sporočil v mapi »Prejeto«.

- **interesting_calendar_accounts_count** – ponazarja število računov, ki so primerni za zanimive koledarje v napravi, s katerim lahko zaznamo težave, povezane z zanimivimi koledarji

- **is_group_calendar** – ponazarja, ali gre za koledar skupine, in nam pomaga zaznati težave, povezane s koledarji skupine

- **mail_folder_type** – ponazarja vrsto mape za pošto, tj. »Prejeto«, »Osnutki« itd., in nam pomaga zaznati težave, povezane z vrstami map.

- **mail_accounts_count** – ponazarja število računov pošte, s katerim lahko zaznamo težave, povezane računi pošte.

- **selected_group_calendar_count** – ponazarja število koledarjev skupine, ki so izbrani in aktivni v uporabniškem vmesniku

- **visibility_toggle** – ponazarja, ali je uporabnik vklopil/izklopil dani koledar, in nam pomaga zaznati težave, povezne s prikazovanjem oz. skrivanjem koledarjev.

#### <a name="ipccreaterepublishinglicense"></a>IpcCreateRepublishingLicense

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij. Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride v zadnji fazi postopka, ko se izvede priklic API IpcCreateRepublishingLicense.

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se aplikacija izvaja v produkcijskem okolju ali v okolju razvijalcev

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

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se aplikacija izvaja v produkcijskem okolju ali v okolju razvijalcev

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

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se aplikacija izvaja v produkcijskem okolju ali v okolju razvijalcev

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

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se aplikacija izvaja v produkcijskem okolju ali v okolju razvijalcev

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

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se aplikacija izvaja v produkcijskem okolju ali v okolju razvijalcev

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

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se aplikacija izvaja v produkcijskem okolju ali v okolju razvijalcev

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

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se aplikacija izvaja v produkcijskem okolju ali v okolju razvijalcev

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

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se aplikacija izvaja v produkcijskem okolju ali v okolju razvijalcev

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

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se aplikacija izvaja v produkcijskem okolju ali v okolju razvijalcev

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

- **RMS.PL.KeyType** – vrednost »enojno« ali »dvojno«. Označuje, ali je bil PL zaščiten z zaščito z enojnim ali dvojnim ključem.

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

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se aplikacija izvaja v produkcijskem okolju ali v okolju razvijalcev

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


#### <a name="linkclickedaction"></a>link.clicked.action

Dogodek se uporablja za spremljanje uspeha uporabnikov pri ogledu URL-ja v pogledu »Edge Web View« in izpolnjevanju standardnih spletnih scenarijev v tem spletnem pogledu, ne da bi se s tem soočile napake

Zbrana so naslednja polja:

- **account_type** – če je bil pogled» Edge Web View «zagnan z e-poštnega sporočila ali dogodkom v Outlooku, vnesite račun, od koder je prišel URL.

- **dejanje** – dejanje, ki ga opravi uporabnik znotraj Outlooka od trenutka, ko tapnete URL, da ko zapusti ta potek (odprla povezavo v pogledu» rob «, se stran ni naložila v spletnem pogledu, izvedla iskanje v spletnem pogledu, zaprla spletni pogled Edge, da bi odprla povezavo v spletnem brskalniku...)

- **trajanje** – trajanje uporabniške seje

- **launch_type** – če se je zagnal pogled »Edge Web View«, je bil iz Outlooka, iz gradnika ali iz komponente OS

- **poreklo** – če je uporabnik izvajal dejanje v pogledu »Edge Web View«, je izvor tega dejanja

- **Napotitelj** – mesto URL-ja, na katerega uporabnik prisluškuje (e-pošta, dogodek v koledarju, kartica TXP itd.)

- **search_scope** – če je uporabnik izvajal iskanje v pogledu »Edge Web View«, obseg iskanja (vse, slike, videoposnetki itd.)

- **search_subtype** – če je uporabnik izvajal iskanje v pogledu »Edge Web View«, je bilo začetno iskanje ali rafinirano iskanje.

- **session_summary_page_loaded_count** – število strani, ki jih uporabnik naloži med sejo v pogledu »Edge Web View«

- **session_summary_search_count** – število iskanj Bing, ki jih je opravil uporabnik med sejo v pogledu »Edge Web View«

- **session_summary_session_id** – identifikator za trenutno sejo uporabnika v pogledu »Edge Web View«

- **txp** – če je bil pogled» Edge Web View «zagnan iz TXP kartice, vrste dogodkov za to kartico (jedilnica, Flight itd.)

- **txp** – če je bil pogled »Edge Web View« zagnan iz TXP kartice, vrste dogodkov za to kartico (jedilnica, Flight itd.)


#### <a name="mailaction"></a>mail.action

Uporablja se za nadzor morebitnega negativnega učinka na vašo zmožnost izvajanja kritičnih dejanj pošte (npr. izvajanje na pošte v nitnem načinu, zagotavljanje delovanje triažnih dejanj za pošto) in zagotavljanje, da naša poštna aplikacija ustrezno deluje.

Zbrana so sledeča polja:

- **account** – račun, ki je izvedel dejanje *[To polje je bilo odstranjeno iz trenutnih različic Officea, vendar se lahko še vedno prikaže v starejših graditvah.]*

- **action** – spremlja vrsto izvedenega dejanja, tj. »arhiviranje«, »brisanje«, »označevanje kot prebrano« itd. 

- **attachment_content_type** – vrsta vsebine prenesene priloge. 

- **attachment_content_type_with_count** – spremlja število prilog v e-pošti.

- **attachment_download_result** – rezultat (tj. usešno/neuspešno) za dejanje prenosa priloge

- **attachment_download_time** – čas dejanja prenosa priloge.

- **attachment_extn** – datotečna pripona prenesene priloge *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar je lahko še vedno prikazano v starejših graditvah.]*

- **attachment_id** – identifikator sistema za preneseno prilogo. 

- **attachment_size** – velikost prenesene priloge.

- **domain** – domena dokumenta, ki ga želite odpreti.

- **duration** – spremlja, kako dolgo je trajalo dejanje kot niz v človeku berljivi obliki v angleščini (na primer 1 s, 4 ure).

- **error** – sporočilo o napaki, povezani z dejanjem. 

- **event_mode** – vrsta izbranega načina dogodka, skupine ali drugo. 

- **Extension** – štirje znaki datotečne pripone povezave ali priloge, povezane s tem dejanjem *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar je lahko še vedno prikazano v starejših graditvah.]*

- **internet_message_id** – ID sporočila za sledenje.

- **is_group_escalation** – ponazarja, ali je bilo sporočilo, za katero se je dejanje izvedlo, poslano v nabiralnik uporabnika zaradi stopnjevanja (naročnina na skupino).

- **is_rule** – ponazarja, ali je izvedeno dejanje pošte ponastavilo klasifikacijo v fokusu/drugo klasifikacijo.

- **is_threaded_mode** – ponazarja, ali je bilo sporočilo v nitnem načinu, tj. načinu združevanja sporočil

- **is_unread** – ponazarja, ali je sporočilo, za katero se je izvedlo dejanje, neprebrano.

- **left_swipe_setting** – ponazarja dejanje, ki ga izvedete z levim podrsljajem.

- **message_id** – ID sporočila strežnika, ciljan za dejanje, ali seznam, ločen z vejicami, če je bilo izvedenih več dejanj.

- **message_type** – ponazarja vrsto sporočila, za katero je bilo izvedeno dejanje – skupina ali drugo.

- **number_selected** – število elementov, ki jih je izbral uporabnik na seznamu sporočil in je ukrepal v več načinih izbora.

- **origin** – vir dejanja, tj. podrsanje po celici, ničelna poizvedba, globoka povezava, e-poštni pogled, e-poštni seznam itd.

- **origin_view** – izvorni pogled dejanja, na primer pogovor, sporočilo itd.

- **reported_to_msft** – ko je bila e-pošta posredovana v mapo z neželeno vsebino (neželena pošta) ali v koš (lažno predstavljanje), lahko uporabnik izbere, ali želi dejanje prijaviti Microsoftu.

- **retry** – ali je prišlo do vnovične izvedbe dejanja.

- **right_swipe_setting** – ponazarja dejanje, ki ga izvedete z desnim podrsljajem. 

- **shortcut** – ponazarja, ali je bila uporabljena bližnjica in katera bližnjica je bila uporabljena za načrtovanje sporočila, tj. pozneje, jutri, izberite čas itd.

- **size** – velikost povezave ali priloge, povezane s tem dejanjem

- **source_folder** – spremlja vrsto izvorne mape, ko dejanje ponazarja na premik iz ene v drugo mapo, tj. v mapo »Prejeto«, koš itd. 

- **source_inbox** – ponazarja, v kateri nabiralnik bo poslana pošta (to je s fokusom, drugo itd.) – stanje dejanja, to je »uspešno« ali mesto neuspeha

- **state** – stanje dejanja, na primer uspeh ali mesto napake

- **target_folder** – ponazarja vrsto ciljne mape pri premikanju e-poštnih sporočil iz ene mape v drugo

- **thread_id** – ID niza za pogovor, ciljan za dejanje, ali seznam, ločen z vejicami, če je bilo izvedenih več dejanj

- **time_taken_to_fetch_access_token** – čas, zahtevan za pridobivanje sistemskega žetona za dostop in uporabo za odpiranje povezave.

- **time_taken_to_fetch_drive_item** – čas, zahtevan za pridobivanje vira OneDrive ob kliku nanj.

- **time_taken_to_fetch_embed_viewer_resource** – čas, zahtevan za inicializacijo vdelanega pregledovalnika pri odpiranju povezav.

- **time_taken_to_load_embed_viewer** – čas, zahtevan za inicializacijo vdelanega pregledovalnika pri odpiranju povezav.

- **time_taken_to_load_link** – čas, zahtevan za dokončanje nalaganja povezave.

- **time_taken_to_tap_attachment** – čas med odpiranjem sporočila in klikom na Priloge

- **time_taken_to_tap_link** – čas, ki ga je uporabnik porabil za ogled sporočila in klik povezave.

- **txp** – ponazarja, ali je na voljo vrsta txp za element, povezan s pošto, za katero je bilo izvedeno dejanje, denimo rezervacija dogodka, rezervacija leta itd. 

- **type** – vrsta dokumenta, ki je bila odprta prek povezave.

#### <a name="mailcompose"></a>mail.compose

Uporablja se za nadzor morebitnega negativnega učinka na vašo zmožnost sestavljanja e-poštnega sporočila in odgovarjanja nanj, npr. težave pri možnosti »Odgovori vsem«, oblikovanje ali pošiljanje e-poštnega sporočila.

Zbrana so sledeča polja: 

- **draft_message_id** – ID osnutka za pogovor, ki ga želite ustvariti kot osnutek, s katerim lahko zaznamo težave, povezane z osnutki e-poštnih sporočil

- **message_id** – ID sporočila za pogovor, na katerega ste odgovorili ali vam je bil posredovan, s katerim lahko zaznamo težave, povezane z določenim sporočilom

- **origin** – prikazuje vir sporočila, na primer možnost »Odgovori vsem«, »Sestavi novo sporočilo« ali »Hitri odgovor«. Pomaga nam pri zaznavanju težav, povezanih z določeno vrsto vira odgovora.

- **is_group_escalation** – ponazarja, ali je sporočilo stopnjevano sporočilo skupine, ki nam pomaga pri zaznavanju težav pri sestavljanju, povezanih s skupinami.

- **is_link** – ponazarja, ali je bil novi osnutek ustvarjen iz povezave. Pomaga nam pri zaznavanju težav, povezanih z osnutki, ustvarjenimi iz povezav.

- **is_force_touch** – ponazarja, ali je bil novi osnutek ustvarjen iz dejanja na dotik na silo. Pomaga nam pri zaznavanju težav, povezanih z osnutki, ustvarjenimi s tem določenim dejanjem.

- **is_groups** – ponazarja, ali je bil ta dogodek zagnan iz prostora skupine, in nam pomaga pri zaznavanju težav pri sestavljanju, povezanih s skupinami.

- **source_inbox** – ponazarja izvorni nabiralnik, na primer ali je bil v fokusu ali je šlo za drug nabiralnik.

- **thread_id** – ID niti za pogovor, na katerega ste odgovorili ali vam je bil posredovan in nam pomaga zaznati težave, povezane z določeno nitjo

#### <a name="meetingcalltoaction"></a>meeting.call.to.action

Se uporablja za nadzor morebitnih negativnih učinkov na vašo zmožnost izvajanja ključnih dejanj srečanja, kot so ustvarjanje in urejanje srečanj in odgovarjanje nanje.

Zbrana so sledeča polja:

- **event_mode** – ponazarja, ali gre za dogodek skupine, in nam pomaga pri zaznavanju težav z dogodki skupine.

- **meeting_id** – ID srečanja, s pomočjo katerega lahko spremljamo težave za čas trajanja srečanja in zaznamo težave z določenimi srečanji.

- **meeting_provider** – ponazarja ponudnika spletnega srečanja, na primer Teams, Skype za podjetja, in nam pomaga pri zaznavanju težav z določenimi ponudniki spletnih srečanj

- **notify_type** – ponazarja vrsto odgovora za druge vrste računov in nam pomaga pri zaznavanju težav z različnimi vrstami računov

- **recurrence** – ponazarja pogostost srečanja, denimo enkratno srečanje ali niz srečanj, in nam pomaga pri zaznavanju težav pri nizih ponavljajočih se srečanj

- **response** – ponazarja vrsto odziva, kot je sprejem ali zavrnitev, v določenih vrstah računa in nam pomaga pri zaznavanju težav pri odzivanju na dogodke.

- **response_message_length** – ponazarja dolžino sporočila in nam pomaga pri zaznavanju težav pri odzivih na srečanja.

- **review_time_proposal_action_type** – ponazarja predlog novega časa v odzivu uporabnika in nam pomaga pri zaznavanju težav s predlaganjem novega časa.

- **send_response** – ponazarja, ali je bil odziv poslan, in nam pomaga pri zaznavanju težav pri pošiljanju odzivov na povabilo na srečanje.

- **txp** – ponazarja vrsto, iz katere je bilo srečanje ustvarjeno, od rezervacij leta do dostavo, in nam pomaga pri zaznavanju težav s to vrsto srečanja.

- **with_message_enabled** – ponazarja, ali se uporabnik lahko odzove s sporočilom, in nam pomaga pri zaznavanju težav z odzivi na povabila na srečanja

#### <a name="officeandroiddocsuifileoperationsopendocumentmeasurements"></a>Office.Android.DocsUI.FileOperations.OpenDocumentMeasurements

Ta dogodek se zbira za Officeove aplikacije, ki se izvajajo v platformi Android, in zabeleži dogodek odpiranja datoteke. Ta dogodek zagotavlja varnost pri odpiranju datoteke, posodobitve in učinkovito delovanje. Cilj zbiranja teh podatkov je nenehno izboljševanje učinkovitosti pri odpiranju datoteke. 

Zbrana so sledeča polja:

- **Data_AppDocsDuration** –čas, zahtevan za podplast med odpiranjem datoteke.

- **Data_AppDuration** – čas, zahtevan za obdelavo aplikacije med odpiranjem datoteke. 

- **Data_AppWarmUpGain** – pridobitev pri času zagona aplikacije, ki smo jo pridobili zaradi vnaprejšnjega zagona dela aplikacije.

- **Data_BootDuration** – čas, zahtevan za zagon aplikacije pri postopku za odpiranje datoteke.

- **Data_ClosePreviouslyOpenedMarkers** – vrednost niza, ki beleži čas med klici funkcij, v obliki zapisa z ID-jem in trajanjem.

- **Data_ClosePreviouslyOpenedMarkers** – v nekaterih scenarijih odpiranja datoteke je postopek zapiranja prej odprtega dokumenta izveden pred odpiranjem trenutnega dokumenta. To časovno obdobje med nekaterimi postopki, ki se izvedejo v tem primeru, je zajeto v vrednosti niza v obliki zapisa \<functionId>\<functionValue>\<functionId>\<functionValue>...

- **Data_Doc_AccessMode** – Oštevilčenje, ki ponazarja način za dostop datoteke, na primer samo za branje, branje in pisanje.

- **Data_Doc_AsyncOpenKind** – Oštevilčenje, ki ponazarja vrsto asinhronega poteka, ki se uporablja za odpiranje datoteke.

- **Data_Doc_ChunkingType** – Oštevilčenje, ki ponazarja vrsto algoritma za razdruževanje datoteke.

- **Data_Doc_EdpState** – Oštevilčenje, ki ponazarja stanje zaščite poslovnih podatkov datoteke.

- **Data_Doc_Ext** – Datotečna pripona datoteke.

- **Data_Doc_Fqdn** – Ime gostitelja strežnika datoteke.

- **Data_Doc_FqdnHash** – globalni enolični identifikator (GUID), ki enolično določa ime gostitelja strežnika.

- **Data_Doc_IdentityTelemetryId** – GUID, ki enolično prepozna identiteto, uporabljeno za odpiranje datoteke. 

- **Data_Doc_InitializationScenario** – Oštevilčenje, ki označuje podrobno vrsto scenarija pri odpiranju datoteke.

- **Data_Doc_IOFlags** – Oštevilčenje, ki označuje V-/I-zastavice postopka za odpiranje datoteke, na primer, ali je bila datoteka predpomnjena.

- **Data_Doc_IsCloudCollabEnabled** – Ali je za datoteko omogočeno sodelovanje v oblaku.

- **Data_Doc_IsIncrementalOpen** – Ali je bila datoteka odprta s funkcijo postopnega odpiranja.

- **Data_Doc_IsOcsSupported** – Ali datoteka podpira Officeovo storitev sodelovanja.

- **Data_Doc_IsOpeningOfflineCopy** – Ali je bila datoteka odprta iz predpomnjene kopije brez povezave.

- **Data_Doc_IsPrefetched** – Ali je bila datoteka vnaprej pridobljena, preden se je zagnal postopek odpiranja.

- **Data_Doc_IsSyncBacked** – Ali je na voljo lokalna različica datoteke, ki je sinhronizirana s strežnikom.

- **Data_Doc_Location** – oštevilčenje, ki označuje mesto datoteke, na primer lokalno ali v oblaku.

- **Data_Doc_ReadOnlyReasons** – oštevilčenje, ki označuje razlog datoteke, ki je samo za branje.

- **Data_Doc_ResourceIdHash** – GUID, ki enolično določa ID vira strežnika datoteke.

- **Data_Doc_RtcType** – Oštevilčenje, ki označuje vrsto kanala v realnem času (RTC), ki ga uporablja datoteka.

- **Data_Doc_ServerDocId** – GUID, ki enolično določa ID dokumenta strežnika.

- **Data_Doc_ServerProtocol** – Oštevilčenje, ki označuje protokol strežnika za datoteko v oblaku.

- **Data_Doc_ServerType** – Oštevilčenje, ki označuje vrsto strežnika za datoteko v oblaku.

- **Data_Doc_ServerVersion** – Oštevilčenje, ki označuje različico strežnika za datoteko v oblaku.

- **Data_Doc_SessionId** – celo število, ki se poveča za 1 za vsak postopek odpiranja datoteke v seji.

- **Data_Doc_SharePointServiceContext** – niz, ki se uporablja za korelacijo odjemalskih in strežniških dnevnikov, po navadi je to neke vrste ID.

- **Data_Doc_SizeInBytes** – Velikost datoteke v bajtih.

- **Data_Doc_SpecialChars** – Oštevilčenje, ki označuje vrsto posebnega znaka, ki ga ima URL datoteke.

- **Data_Doc_UrlHash** – GUID, ki enolično določa URL datoteke.

- **Data_Doc_UsedWrsDataOnOpen** – ali je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS.

- **Data_Doc_WopiServiceId** – niz, ki označuje, iz katere storitve je datoteka WOPI (Web Application Interface Protocol).

- **Data_ErrorId_Code** – koda napake, ki označuje napako v postopku zbiranja podatkov.

- **Data_ErrorId_Tag** – oznaka v kodi za pomoč pri iskanju mesta okvare.

- **Data_FileOpenFlowMarkers** – preden se začne postopek odpiranja datoteke, se mora dokončati postopek vnaprejšnje obdelave. Čas, porabljen za vnaprejšnjo obdelavo, je zajet v vrednosti v obliki zapisa \<functionId>\<functionValue>\<functionId>\<functionValue>...

- **Data_FirstPartyProviderApp** – Če se datoteka, ki je odprta v programih Word, Excel ali PowerPoint ali Office, prikliče iz druge Microsoftove aplikacije, je tukaj zajeto ime te ponudniške storitve.

- **Data_InclusiveMeasurements** – vrednost niza, ki beleži čas, zahtevan za klice funkcij, v obliki zapisa z oznako funkcije ter trajanjem, ki vključuje trajanje klicev podfunkcij. 

- **Data_InitializationReason** – oštevilčenje, ki označuje, način odpiranja datoteke, na primer element uporabniškega vmesnika, odpiranje sprožila aplikacija itd.

- **Data_Measurements** – vrednost niza, ki beleži čas, zahtevan za klice funkcij, v obliki zapisa z oznako funkcije ter trajanjem, ki ne vključuje trajanje klicev podfunkcij.

- **Data_OfficeMobileInitReason** – oštevilčenje, ki označuje vstopno točko pri odpiranju datoteke. 

- **Data_RenderToInSpaceDuration** – trajanje med upodobitvijo in animacijo silhuete/platna.

- **Data_SilhouetteDuration** – Trajanje upodabljanja za odpiranje datoteke.

- **Data_TimeSplitMeasurements** – Vrednost niza, ki beleži čas, zahtevan za klice funkcij, v obliki zapisa z oznako funkcije, časovnim žigom začetka in trajanjem. 

#### <a name="officeandroiddocsuipaywallcontrolpresigninfre"></a>Office.Android.DocsUI.PaywallControl.PreSignInFRE

*[Ta dogodek se je prej imenoval Office.DocsUI.PaywallControl.PreSignInFRE.]*
 
Te je telemetrija kritične uporabe za povečanje prodaje v uporabniški izkušnji prvega zagona za nepodpisane uporabnike. Ta dogodek zajema metriko vpisa ob prvem zagonu. Podatki so uporabljeni za določanje vpogledov predhodnega vpisa in razumevanje uporabnikovega morebitnega nadaljevanja naslednje faze uporabniškega postopka.
 
Zbrana so ta polja: 

- **EventDate** – časovni žig ponovitve dogodka  

- **FunnelPoint** – Popisovalnik, ki označuje mesto uporabnika v tem lijaku preskusa. Popisovalnik sporoči, ali so uporabniku prikazana obravnave in usmerjanja ali ne.

- **SessionID** – globalni enolični identifikator za povezovanje dogodkov po seji


#### <a name="officeandroiddocsuipaywallcontrolskuchoosertoggled"></a>Office.Android.DocsUI.PaywallControl.SkuChooserToggled

Telemetrijo uporabe če si želite ogledati, kolikokrat uporabnik preklaplja med različnimi inventarnimi enotami, preden poskusite kupiti nakup. Uporablja se za razumevanje uporabe izbirnika INVENTARja in optimiziranje možnosti nakupa aplikacije v prihodnjih različicah.

Zbrana so sledeča polja:

- **EventDate** – časovni žig ponovitve dogodka 

- **SessionID** – GUID za povezovanje dogodkov po seji


#### <a name="officeandroiddocsuipaywallcontroluserimageclicked"></a>Office.Android.DocsUI.PaywallControl.UserImageClicked 

*[Ta dogodek se je prej imenoval Office.DocsUI.PaywallControl.UserImageClicked.]*
 
Ta dogodek meri telemetrijo, da določi, ali uporabniki poskušajo dokončati dejanje s klikanjem avatarja uporabnika. Ti podatki so uporabljeni za merjenje števila uporabnikov, ki uporabljajo ikono avatarja za ocenjevanje potrebe po nadaljnji izkušnji ob tapu.
 
Zbrana so ta polja: 

- **EventDate** – časovni žig ponovitve dogodka  

- **SessionID** – globalni enolični identifikator za povezovanje dogodkov po seji 


#### <a name="officeandroidearlytelemetryexpansionfilesavailability"></a>Office.Android.EarlyTelemetry.ExpansionFilesAvailability

Omogočamo razširitvene datoteke kompleta Android Package Kit (APK) za Officeovo mobilno aplikacijo. Razširitvene datoteke APK so dodatne datoteke sredstev, ki jih lahko razvijalci aplikacije Android objavijo skupaj z aplikacijo. Ker želimo vedeti, kako zanesljive so razširitvene datoteke, zabeležimo zastavico, ki pri vsakem zagonu označuje, ali so razširitvene datoteke na voljo ali ne.

Zbrana so sledeča polja:

- **Data_ExpansionFilesAvailable** – logična zastavica, ki označuje, ali so razširitvene datoteke APK na voljo v napravi ob trenutku zagona aplikacije.

#### <a name="officeandroidearlytelemetryexpansionfilesdownloader"></a>Office.Android.EarlyTelemetry.ExpansionFilesDownloader

Omogočamo razširitvene datoteke kompleta Android Package Kit (APK) za Officeovo mobilno aplikacijo. Razširitvene datoteke APK so dodatne datoteke sredstev, ki jih lahko razvijalci aplikacije Android objavijo skupaj z aplikacijo.  Ker želimo vedeti, kako zanesljiv je naš mehanizem za prenos razširitvenih datotek, zabeležimo zastavico, ki označuje, ali smo uspešno prenesli razširitvene datoteke.

Zbrana so sledeča polja: 

- **Data_DownloadSuccess** – logična zastavica, ki označuje, ali je bil prenos razširitvenih datotek APK uspešen, ko poskusimo izvesti prenos med zagonom aplikacije.

#### <a name="officeandroidearlytelemetrynotecreated"></a>Office.Android.EarlyTelemetry.NoteCreated

Kritični signal, ki se uporablja za nadzor zmogljivosti, kjer uporabniki Samolepljivih listkov lahko ustvarjajo zapiske v aplikaciji. Telemetrija se uporablja za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in stanja storitve. Če uporabniki ne morejo ustvariti zapiska, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so sledeča polja:

- **IsExportable** – zastavica, ki označuje, ali je bil dogodek rezultat dejanja uporabnika ali ne. Mora biti nastavljen na vrednost true, ker je NoteCreated dejanje, ki ga je sprožil uporabnik.

- **NoteLocalId** – razlikovalni enolični identifikator, ki je dodeljen zapisku v času, ko uporabnik ustvari zapisek v aplikaciji.

- **StickyNotes – SDKVersion** – številka različice, ki označuje različico Lepljivih zapiskov, ki jo uporablja uporabnik. Omogoča, da določimo, v katerih različicah izdelka je prišlo do težave ter te težave razvrstimo po pomembnosti.


#### <a name="officeandroidearlytelemetrynoteviewed"></a>Office.Android.EarlyTelemetry.NoteViewed 

Kritični signal, ki se uporablja za nadzor zmogljivosti, kjer si uporabniki Samolepljivih listkov lahko ogledujejo zapiske v aplikaciji. Telemetrija se uporablja za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in stanja storitve. Če si uporabniki ne morejo ogledati svojih zapiskov, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so naslednja polja:

- **HasImages** – zastavica, ki označuje, so v ogledanem zapisku shranjene slike.

- **IsExportable** – zastavica, ki označuje, ali je bil dogodek rezultat dejanja uporabnika ali ne. Mora biti nastavljen na vrednost true, ker je NoteViewed dejanje, ki ga je sprožil uporabnik.

- **NoteLocalId** – razpoznavni enolični identifikator, ki je dodeljen zapisku v času, ko uporabnik ustvari zapisek v programu.

- **StickyNotes – SDKVersion** – številka različice, ki označuje različico Lepljivih zapiskov, ki jo uporablja uporabnik. Omogoča, da določimo, v katerih različicah izdelka je prišlo do težave ter te težave razvrstimo po pomembnosti.


#### <a name="officeandroidintuneintunecompliancerequest"></a>Office.Android.Intune.IntuneComplianceRequest

Ta dogodek se zbira za Officeove aplikacije, ki se izvajajo v sistemu Android, vključno z aplikacijami: Office Mobile, Word, Excel, PowerPoint in OneNote. Ta dogodek ponazarja poskus vpisa v račun organizacije, licenciran za Intune, za katerega je skrbnik organizacije pravilnik nastavil tako, da izvršuje pogojni dostop aplikacije. Uporablja se za razumevanje števila končnih uporabnikov, ki poskušajo aplikacije uporabiti v sklopu te konfiguracije pravilnika, in je združen z drugim dogodkom, Office.Android.Intune.IntuneComplianceStatus, za zagotavljanje izvrševanja konfiguriranega pravilnika. 

Podatkovna polja se ne zbirajo.

#### <a name="officeandroidintuneintunecompliancestatus"></a>Office.Android.Intune.IntuneComplianceStatus

Ta dogodek se zbira za Officeove aplikacije, ki se izvajajo v sistemu Android, vključno z aplikacijami: Office Mobile, Word, Excel, PowerPoint in OneNote. Ta dogodek ponazarja poskus vpisa v račun organizacije, licenciran za Intune, za katerega je skrbnik organizacije pravilnik nastavil tako, da izvršuje pogojni dostop aplikacije. Ta dogodek ponazarja stanje skladnosti aplikacije, v katero se je uporabnik vpisal, in se uporablja za preiskovanje okvar. Združen je z drugim dogodkom, Office.Android.Intune.IntuneComplianceRequest, za zagotavljanje izvrševanja konfiguriranega pravilnika.
  
Zbrana so sledeča polja:

- **Data_ComplianceStatus** – označuje stanje skladnosti aplikacije med vpisom s kodo napake pri uspehu ali napaki.
  - -1 – neznana napaka
  -    0 – aplikacija je skladna s pravilniki organizacije
  - 1 – aplikacija ni skladna s pravilniki organizacije
  - 2 – okvare, povezane s storitvijo
  - 3 – okvare, povezane z omrežjem
  - 4 – aplikacija ni uspela pridobiti žetona za preverjanje pristnosti 
  - 5 – odziv storitve še ni bil prejet
  - 6 – aplikacija portala podjetja mora biti nameščena

#### <a name="officeandroidodwxpssotelemetry"></a>Office.Android.ODWXPSSO.Telemetry

S tem dogodkom boste lažje razumeli, s katero drugo Microsoftovo aplikacijo v napravi se je v naši aplikaciji izvedela tiha enotna prijava, s katere točke vnosa itd. Prav tako pomaga pri razumevanju vzroka napake za neuspešno tiho enotno prijavo.  Pridobivamo boljše vpoglede, na primer, iz katere Microsoftove aplikacije v napravi smo pridobili izkušnjo enotne prijave. Ukrepi, kjer enotna prijava ne deluje pravilno.

Zbrana so naslednja polja:

- **AccountType** – Označuje vrsto računa, s katerim je bila izvedena enotna prijava, denimo osebni Microsoftov račun ali službeni račun.

- **EntryPoint** – Označuje vstopno točko v aplikaciji, s katere je bil inicializiran poskus enotne prijave.

- **ErrorCode** – Označuje kodo napake pri poskusu enotne prijave.

- **ErrorDescription** – Označuje sporočilo o napaki poskusa enotne prijave.

- **HResult** – Označuje rezultat kode stanja pri poskusu enotne prijave.

- **ProviderPackageId** – Druga Microsoftova aplikacija v napravi, iz katere se je izvedla enotna prijava.

#### <a name="officeandroidphonenumbersignins"></a>Office.Android.PhoneNumberSignIns

S tem dogodkom poskušamo razumeti, ali se je uporabnik prijavil ali vpisal z računom, povezanim s telefonsko številko, ali z računom, povezanim z e-poštnim naslovom osebnega Microsoftovega računa.  S tem dogodkom določimo število uporabnikov, ki se prijavljajo ali vpisujejo z osebnim Microsoftovim računom, povezanim s telefonsko številko.

Zbrana so naslednja polja:

- **EntryPoint** – Označuje vstopno točko v aplikaciji, s katere je bil inicializiran poskus vpisa.

- **IsEmailMissing** – Ali je v podatkih profila računa naveden e-poštni naslov?

- **IsPhoneNumberMissing** – Ali je v podatkih profila računa navedena telefonska številka?

- **UserDecision** – Označuje izbiro uporabnika, kot je vpis ali prijava oz. poznejši vpis.

#### <a name="officeandroidusersignindecision"></a>Office.Android.UserSignInDecision

S tem dogodkom poskušamo razumeti, na kateri stopnji je prišlo do težave pri vpisu, zakaj vpis ni bil uspešen, koliko uporabnikov se je uspešno vpisalo iz določene vstopne točke v aplikaciji itd.  S tem dogodkom lažje usmerjamo podatke o vpisu, ki so nam v pomoč pri določanju, na kateri stopnji uporabniki naletijo na težave itd.

Zbrana so naslednja polja:

- **AccountType** – Označuje vrsto računa, s katerim je bil izveden poskus vpisa, denimo osebni račun ali službeni račun.

- **AfterLicensingState** – Označuje stanje licence aplikacije po dokončanem vpisu.

- **AllowedEditsWithoutSignIn** – Označuje, koliko prostih urejanj je poteklo, preden je bil izveden vpis.

- **BeforeLicensingState** – Označuje stanje licence aplikacije pred vpisom.

- **CompletionState** – Označuje stopnjo dokončanja vpisa.

- **EntryPoint** – Označuje vstopno točko v aplikaciji, s katere je bil inicializiran poskus vpisa.

- **HRDAutoAcceleratedSignUpAttemptCount** – Označuje število pospešenih vpisov.

- **HRDAutoAcceleratedSignUpQuitCount** – Označuje število preklicanih pospešenih vpisov.

- **HResult** – Označuje rezultat kode stanja za vpis.

- **IsPhoneOnlyAuthFeatureEnabled** – Ali je dovoljen vpis z računom, povezanim s telefonsko številko?

- **LicenseActivationHResult** – Označuje stanje kode za poskus aktivacije licence.

- **LicenseActivationMessageCode** – Označuje kodo sporočila iz storitve licenciranja.

- **NoFreeEditsTreatmentValue** – Ali so prosta urejanja dovoljena?

- **SignUpAttemptCount** – Označuje število poskusov prijave.

- **StartMode** – Označuje način, v katerem je bil zagnan poskus vpisa.

- **UserDecision** – Označuje izbiro uporabnika, kot je vpis ali prijava oz. poznejši vpis.


#### <a name="officeappcompatappcompatagentscanandupload"></a>Office.AppCompat.AppCompat.AgentScanAndUpload

Podatki so zbrani le, če je uporabnik omogočil nadzorno ploščo za telemetrijo sistema Office. Zbira informacije o tem, kdaj se izvaja posrednik za telemetrijo sistema Office.    Ti podatki so zbrani le, če je nadzorna plošča za telemetrijo sistema Office omogočena in uporabljena za določanje ustreznosti stanja posrednika za telemetrijo sistema Office.

Zbrana so ta polja:

  - **Data.AgentExit** – Časovni žig, ko se je posrednik za telemetrijo uspešno zaprl.

  - **Data.AgentScan** – Časovni žig, ko je posrednik za telemetrijo uspešno dokončal pregled.

  - **Data.AgentUpload** – Časovni žig, ko je posrednik za telemetrijo uspešno dokončal nalaganje.

#### <a name="officeappcompatappcompatagentupload"></a>Office.AppCompat.AppCompat.AgentUpload

Ustvarjeno je ob zagonu odjemalca, če je končni uporabnik omogočil nadzorno ploščo za telemetrijo sistema Office.  Zbira informacije o tem, kdaj je posrednik za telemetrijo sistema Office prenesel podatke v mapo v skupni rabi. Primarna uporaba tega dogodka je spremljanje ustreznosti stanja posrednika za telemetrijo sistema Office, sekundarna uporaba dogodka pa je ocena uporabe nadzorne plošče za telemetrijo sistema Office.

Zbrana so naslednja polja:

- **UploadTime** – časovni žig zadnjega uspešnega prenosa, ki ga je izvedel posrednik za telemetrijo.


#### <a name="officeappcompatappcompattelemetrydashboardresiliencycrashlog"></a>Office.AppCompat.AppCompat.TelemetryDashboardResiliencyCrashLog

Ti podatki so zbrani le, če je končni uporabnik (najverjetneje skrbnik) omogočil nadzorno ploščo za telemetrijo sistema Office. Zbira pojavitve dodatkov za Office in zrušitve dokumentov.  Ti podatki so zbrani le, če je končni uporabnik omogočil nadzorno ploščo za telemetrijo sistema Office. Z njimi določimo morebitno povečano pojavitev dodatkov ali zrušitev dokumentov.

Zbrana so ta polja:

  - **Data.CollectionTime** – Časovni žig, kdaj je bil zabeležen dogodek zrušitve.

#### <a name="officeappdocsappdocsdocumentoperation"></a>Office.AppDocs.AppDocs.DocumentOperation

Ta dogodek je zbran za Officeove aplikacije, ki se izvajajo v platformah Android, iOS, Universal ali Windows. Dogodek zabeleži, ko se izvede datotečna operacija (ustvari/odpre/shrani/izvozi/itd.), uporablja pa se za razumevanje in določanje prednosti uporabniških izkušenj glede na informacije o datotečnih operacijah.

Zbrana so sledeča polja:

- **Data_AppIdForReportEndBeforeAppKnown** – ID aplikacije, ko ni znan preden je bil za postopek priklican konec poročila.

- **Data_CanContinueFromOnBeforeOperationBegins** – Stanje CanContinue, preden je priklican program za obravnavo začetka.

- **Data_DetachedDuration** – Trajanje, zahtevano za odpenjanje postopka dogodka. 

- **Data_Doc_AccessMode** – oštevilčenje, ki ponazarja način za dostop datoteke, na primer samo za branje, branje in pisanje.

- **Data_Doc_AsyncOpenKind** – Oštevilčenje, ki ponazarja vrsto asinhronega poteka, ki se uporablja za odpiranje datoteke.

- **Data_Doc_ChunkingType** – Oštevilčenje, ki ponazarja vrsto algoritma za razdruževanje datoteke.

- **Data_Doc_EdpState** – Oštevilčenje, ki ponazarja stanje zaščite poslovnih podatkov datoteke.

- **Data_Doc_Ext** – prvi štirje znaki datotečne pripone.

- **Data_Doc_Fqdn** – Ime gostitelja strežnika datoteke.

- **Data_Doc_FqdnHash** – GUID, ki enolično določa ime gostitelja strežnika.

- **Data_Doc_IdentityTelemetryId** – enostranska zgoščena vrednost identitete uporabnika, uporabljena za odpiranje.

- **Data_Doc_InitializationScenario** – Oštevilčenje, ki označuje podrobno vrsto scenarija pri odpiranju datoteke.

- **Data_Doc_IOFlags** – oštevilčenje, ki označuje V-/I-zastavice postopka za odpiranje datoteke, na primer, ali je bila datoteka predpomnjena.

- **Data_Doc_IsCloudCollabEnabled** – Ali je za datoteko omogočeno sodelovanje v oblaku.

- **Data_Doc_IsIncrementalOpen** – Ali je bila datoteka odprta s funkcijo postopnega odpiranja.

- **Data_Doc_IsOcsSupported** – Ali datoteka podpira Officeovo storitev sodelovanja.

- **Data_Doc_IsOpeningOfflineCopy** – Ali je bila datoteka odprta iz predpomnjene kopije brez povezave.

- **Data_Doc_IsPrefetched** – Ali je bila datoteka vnaprej pridobljena, preden se je zagnal postopek odpiranja.

- **Data_Doc_IsSyncBacked** – Ali je na voljo lokalna različica datoteke, ki je sinhronizirana s strežnikom.

- **Data_Doc_Location** – oštevilčenje, ki označuje mesto datoteke, npr. lokalno ali v oblaku.

- **Data_Doc_ReadOnlyReasons** – oštevilčenje, ki označuje razlog datoteke, ki je samo za branje.

- **Data_Doc_ResourceIdHash** – GUID, ki enolično določa ID vira strežnika datoteke.

- **Data_Doc_RtcType** – Oštevilčenje, ki označuje vrsto kanala v realnem času (RTC), ki ga uporablja datoteka.

- **Data_Doc_ServerDocId** – GUID, ki enolično določa ID dokumenta strežnika.

- **Data_Doc_ServerProtocol** – Oštevilčenje, ki označuje protokol strežnika za datoteko v oblaku.

- **Data_Doc_ServerType** – Oštevilčenje, ki označuje vrsto strežnika za datoteko v oblaku.

- **Data_Doc_ServerVersion** – Oštevilčenje, ki označuje različico strežnika za datoteko v oblaku.

- **Data_Doc_SessionId** – celo število, ki se poveča za 1 za vsak postopek odpiranja datoteke v seji.

- **Data_Doc_SharePointServiceContext** – Niz, ki se uporablja za korelacijo odjemalskih in strežniških dnevnikov, po navadi je to neke vrste ID.

- **Data_Doc_SizeInBytes** – Velikost datoteke v bajtih.

- **Data_Doc_SpecialChars** – Oštevilčenje, ki označuje vrsto posebnega znaka, ki ga ima URL datoteke.

- **Data_Doc_UrlHash** – GUID, ki enolično določa URL datoteke.

- **Data_Doc_UsedWrsDataOnOpen** – Ali je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS.

- **Data_Doc_WopiServiceId** – Niz, ki označuje, iz katere storitve je datoteka WOPI (Web Application Interface Protocol).

- **Data_DocumentInputCurrency** – Vrsta vnosa dokumenta, ki ga uporablja postopek.

- **Data_DocumentOperation_AppId** – Vrednost oštevilčenja, ki predstavlja ID aplikacije.

- **Data_DocumentOperation_EndEventId** – Oznaka, ki predstavlja mesto, kjer se je postopek končal.

- **Data_DocumentOperation_EndReason** – Vrednost oštevilčenja, ki predstavlja razlog konca.

- **Data_DocumentOperation_IsReinitialized** – Znova inicializira dokument, ki je že odprt.

- **Data_DocumentOperation_isTargetECBeginEC** – Kontekst ciljne izvedbe je enak kontekstu odpiranja.

- **Data_DocumentOperation_ParamsFlags** – Oznake oštevilčenja, uporabljene za začetek postopka.

- **Data_DocumentOperation_TelemetryReason** – Oštevilčenje, ki predstavlja vhodno točko za dogodek odpiranja. Na primer odpiranje iz MRU ali brskanje, aktivacija datoteke itd.

- **Data_FileIOInclusiveMeasurements** – Vrednost niza, ki beleži čas, zahtevan za klice funkcij, v obliki zapisa z oznako funkcije ter trajanjem, ki vključuje trajanje klicev podfunkcij.

- **Data_FileIOMeasurements** – Vrednost niza, ki beleži čas, zahtevan za klice funkcij, v obliki zapisa z oznako funkcije ter trajanjem, ki ne vključuje trajanje klicev podfunkcij.

- **Data_InitializationReason** – Predstavitev oštevilčenja, ki določenega razloga za operacijo. Npr. – Odprite z URL-jem ali lokalno potjo do datoteke, ustvarite z izbiralnikom datotek, kopirajte pot do datoteke, izvozite v URL ipd.

- **Data_IsDisambiguateCsiNetworkConnectivityErrorEnabled**.

- **Data_IsNameMissingInUrl** – Označuje, če ime ni bilo razčlenjeno iz URL-ja.

- **Data_IsPathMissingForLocalFile** – Označuje, če je to lokalna datoteka brez poti.

- **Data_IsUnpackedLinkSupportedForOpen** – Označuje, ali je povezava, ki je ni mogoče razpakirati, podprta za odpiranje.

- **Data_LinksOpenRightScenario** – Vrednost oštevilčenja za scenarij pravilnega odpiranja povezav.

- **Data_OpEndEventId** – Oznaka, ki predstavlja, kjer se je postopek končal.

- **Data_OperationType** – Oštevilčenje, ki predstavlja splošno vrsto operacije. Npr. ustvarjanje, odpiranje, kopiranje, shranjevanje itd.

- **Data_RelatedPrevOpTelemetryReason** – Postopek, povezan s prejšnjim postopkom.

- **Data_StopwatchDuration** – Skupno trajanje dogodka.

- **Data_UnpackLinkHint** – Oštevilčenje, ki predstavlja potencialno dejanje uporabnika s povezavo za razpakiranje.

- **Data_UnpackLinkPromptResult** – Oštevilčenje, ki predstavlja odgovor na poziv za povezavo za razpakiranje.

#### <a name="officeappleactivateperpetual"></a>Office.Apple.ActivatePerpetual

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za nadzorovanje ustreznosti stanja stalnega postopka aktiviranja ter preiskovanje vzrokov napak na osnovi pregleda vrednosti FailedAt.

Zbrana so naslednja polja:

- **Data_FailedAt** – zbiramo podatke o nizu, ki predstavlja, kje v postopku aktiviranja stalne licence je prišlo do napake.

#### <a name="officeappleactivatesubscription"></a>Office.Apple.ActivateSubscription

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Zbiramo informacije, povezane s selitvijo s sklada podedovane kode za licenciranje na sklad kode za licenciranje vNext. To se uporablja za nadzorovanje ustreznosti stanja postopka aktiviranja naročnine ter sledenje temu, ali gre za selitev na licenciranje vNext in ali je bila uporabljena primarna identiteta.

Zbrana so naslednja polja:

- **Data_ActivatingPrimaryIdentity** – vrednost true/false, ki označuje, ali je bila uporabljena primarna identiteta. 

- **Data_NULSubscriptionLicensed** – vrednost true/false, ki označuje stanje naročnine

#### <a name="officeapplecisauthticketwithidentity"></a>Office.Apple.CISAuthTicketWithIdentity

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek se uporablja za zajemanje napak pri ustvarjanju žetonov za preverjanje pristnosti med InAppPurchase v računalniku Mac (dogodek zabeleži kodo napake, ki jo je prejel).  Ta dogodek se uporablja za odkrivanje in pomoč pri odpravljanju napak pri ustvarjanju žetonov za preverjanje pristnosti

Zbrana so naslednja polja:

- **Data_EmptyAuthToken** – zbrali smo niz, ki predstavlja, kje v neprekinjenem poteku licence je prišlo do napake.

- **Data_TicketAuthError** – koda napake, ki označuje vzrok napake

- **Data_ValidIdentity** – če ima odjemalec veljavno identiteto

#### <a name="officeappleinappassociationactivity"></a>Office.Apple.InAppAssociationActivity

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Zbiramo informacije, povezane s povezavo izdelka po nakupu znotraj aplikacije. Zabeležimo, katero inventarno številko naročnine povezujemo.  To se uporablja za nadzorovanje ustreznosti stanja povezav izdelkov pri nakupu znotraj aplikacije.

Zbrana so naslednja polja:

- **Data_ProductID** – inventarna številka naročnine, s katero poskušamo povezati izdelek.

#### <a name="officeappleinapppurchaseactivity"></a>Office.Apple.InAppPurchaseActivity

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. 

Zbiramo informacije, povezane z nakupi izdelkov v trgovini AppStore. Sledimo rezultatu nakupa (neuspeh, uspeh, težava z vplačilom ipd.), vrsto zahteve za nakup (obnovitev, nakup) in nakup INVENTARne številke (Microsoft 365 Family itd.).  Te podatke uporabljamo za nadzorovanje ustreznosti stanja postopkov nakupa znotraj aplikacije.

Zbrana so naslednja polja:

- **Data_ Data_PurchaseResult** – rezultat postopka nakupa

- **Data_ProductID** – izdelek, ki je predmet nakupa

- **Data_PurchaseRequestType** – vrsta zahteve za nakup

#### <a name="officeappleintune"></a>Office.Apple.InTune

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Zbiramo informacije o tem, ali je trenutna seja upravljana s storitvijo Intune. Ta dogodek se uporablja za določevanje/filtriranje sej, upravljanih s storitvijo Intune, in nam omogoča, da raziščemo morebitne težave, povezane z Officeom, ki se izvaja kot aplikacija, upravljana s storitvijo Intune.

Zbrana so naslednja polja:

- **Data_EventID** – zbiramo podatke o nizu, ki predstavlja kodo, ki označuje, ali je seja upravljana s storitvijo Intune.

#### <a name="officeapplelicensingmaclicensingstate"></a>Office.Apple.Licensing.Mac.LicensingState

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek zajame trenutno stanje licence za sejo v računalniku (ID licence OLS, inventarna številka, ki se uporablja, dovoljeno obdobje ali njegova odsotnost, način zmanjšane funkcionalnosti ipd.). Zbrane podatke uporabljamo za odkrivanje napak in preiskovanje vzrokov napak. 

Zbrana so naslednja polja:

- **Data_DidRunPreview** – niz, ki označuje, ali se ta seja izvaja v predogledu

- **Data_LicensingACID** – niz, ki predstavlja notranji identifikator sistema licenciranja

- **Data_LicensingType** – niz, ki predstavlja vrsto licence

- **Data_OLSLicenseId** – niz, ki predstavlja identifikator licence

- **Data_State** – niz, ki predstavlja trenutno stanje licence

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

#### <a name="officedocsappdocsoperationopenfrommrubypath"></a>Office.Docs.AppDocs.OperationOpenFromMruByPath

Ta dogodek je zbran za Officeove aplikacije, ki se izvajajo v platformah Android, iOS, Universal ali Windows. Ta dogodek zabeleži, ko je postopek odpiranja datoteke izveden s poti, navedene na seznamu nedavno uporabljenih, in je uporabljen za razumevanje in določanje prioritete napak uporabniške izkušnje na podlagi podatkov o postopku odpiranja datoteke.

Zbrana so sledeča polja:

- **Data_AppIdForReportEndBeforeAppKnown** – ID aplikacije, ko ni znan preden je bil za postopek priklican konec poročila.

- **Data_CanContinueFromOnBeforeOperationBegins** – Stanje CanContinue, preden je priklican program za obravnavo začetka.

- **Data_DetachedDuration** – Trajanje, zahtevano za odpenjanje postopka dogodka. 

- **Data_Doc_AccessMode** – oštevilčenje, ki ponazarja način za dostop datoteke, na primer samo za branje, branje in pisanje.

- **Data_Doc_AsyncOpenKind** – Oštevilčenje, ki ponazarja vrsto asinhronega poteka, ki se uporablja za odpiranje datoteke.

- **Data_Doc_ChunkingType** – Oštevilčenje, ki ponazarja vrsto algoritma za razdruževanje datoteke.

- **Data_Doc_EdpState** – Oštevilčenje, ki ponazarja stanje zaščite poslovnih podatkov datoteke.

- **Data_Doc_Ext** – Prvi 4 znaki razširitve datoteke.

- **Data_Doc_Fqdn** – Ime gostitelja strežnika datoteke.

- **Data_Doc_FqdnHash** – GUID, ki enolično določa ime gostitelja strežnika.

- **Data_Doc_IdentityTelemetryId** – enostranska zgoščena vrednost identitete uporabnika, uporabljena za odpiranje.

- **Data_Doc_InitializationScenario** – Oštevilčenje, ki označuje podrobno vrsto scenarija pri odpiranju datoteke.

- **Data_Doc_IOFlags** – oštevilčenje, ki označuje V-/I-zastavice postopka za odpiranje datoteke, na primer, ali je bila datoteka predpomnjena.

- **Data_Doc_IsCloudCollabEnabled** – Ali je za datoteko omogočeno sodelovanje v oblaku.

- **Data_Doc_IsIncrementalOpen** – Ali je bila datoteka odprta s funkcijo postopnega odpiranja.

- **Data_Doc_IsOcsSupported** – Ali datoteka podpira Officeovo storitev sodelovanja.

- **Data_Doc_IsOpeningOfflineCopy** – Ali je bila datoteka odprta iz predpomnjene kopije brez povezave.

- **Data_Doc_IsPrefetched** – Ali je bila datoteka vnaprej pridobljena, preden se je zagnal postopek odpiranja.

- **Data_Doc_IsSyncBacked** – Ali je na voljo lokalna različica datoteke, ki je sinhronizirana s strežnikom.

- **Data_Doc_Location** – oštevilčenje, ki označuje mesto datoteke, npr. lokalno ali v oblaku.

- **Data_Doc_ReadOnlyReasons** – oštevilčenje, ki označuje razlog datoteke, ki je samo za branje.

- **Data_Doc_ResourceIdHash** – GUID, ki enolično določa ID vira strežnika datoteke.

- **Data_Doc_RtcType** – Oštevilčenje, ki označuje vrsto kanala v realnem času (RTC), ki ga uporablja datoteka.

- **Data_Doc_ServerDocId** – GUID, ki enolično določa ID dokumenta strežnika.

- **Data_Doc_ServerProtocol** – Oštevilčenje, ki označuje protokol strežnika za datoteko v oblaku.

- **Data_Doc_ServerType** – Oštevilčenje, ki označuje vrsto strežnika za datoteko v oblaku.

- **Data_Doc_ServerVersion** – Oštevilčenje, ki označuje različico strežnika za datoteko v oblaku.

- **Data_Doc_SessionId** – celo število, ki se poveča za 1 za vsak postopek odpiranja datoteke v seji.

- **Data_Doc_SharePointServiceContext** – Niz, ki se uporablja za korelacijo odjemalskih in strežniških dnevnikov, po navadi je to neke vrste ID.

- **Data_Doc_SizeInBytes** – Velikost datoteke v bajtih.

- **Data_Doc_SpecialChars** – Oštevilčenje, ki označuje vrsto posebnega znaka, ki ga ima URL datoteke.

- **Data_Doc_UrlHash** – GUID, ki enolično določa URL datoteke.

- **Data_Doc_UsedWrsDataOnOpen** – Ali je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS.

- **Data_Doc_WopiServiceId** – Niz, ki označuje, iz katere storitve je datoteka WOPI (Web Application Interface Protocol).

- **Data_DocumentInputCurrency** – Vrsta vnosa dokumenta, ki ga uporablja postopek.

- **Data_DocumentOperation_AppId** – Vrednost oštevilčenja, ki predstavlja ID aplikacije.

- **Data_DocumentOperation_EndEventId** – Oznaka, ki predstavlja mesto, kjer se je postopek končal.

- **Data_DocumentOperation_EndReason** – Vrednost oštevilčenja, ki predstavlja razlog konca.

- **Data_DocumentOperation_IsReinitialized** – Znova inicializira dokument, ki je že odprt.

- **Data_DocumentOperation_ParamsFlags** – Oznake oštevilčenja, uporabljene za začetek postopka.

- **Data_DocumentOperation_TelemetryReason** – Oštevilčenje, ki predstavlja vhodno točko za dogodek odpiranja. Na primer odpiranje iz MRU ali brskanje, aktivacija datoteke itd.

- **Data_DocumentOperation_isTargetECBeginEC** – Kontekst ciljne izvedbe je enak kontekstu odpiranja.

- **Data_FileIOInclusiveMeasurements** – Vrednost niza, ki beleži čas, zahtevan za klice funkcij, v obliki zapisa z oznako funkcije ter trajanjem, ki vključuje trajanje klicev podfunkcij.

- **Data_FileIOMeasurements** – Vrednost niza, ki beleži čas, zahtevan za klice funkcij, v obliki zapisa z oznako funkcije ter trajanjem, ki ne vključuje trajanje klicev podfunkcij.

- **Data_IsNameMissingInUrl** – Označuje, če ime ni bilo razčlenjeno iz URL-ja.

- **Data_IsPathMissingForLocalFile** – Označuje, če je to lokalna datoteka brez poti.

- **Data_IsUnpackedLinkSupportedForOpen** – Označuje, ali je povezava, ki je ni mogoče razpakirati, podprta za odpiranje.

- **Data_LinksOpenRightScenario** – Vrednost oštevilčenja za scenarij pravilnega odpiranja povezav.

- **Data_OpEndEventId** – Oznaka, ki predstavlja, kjer se je postopek končal.

- **Data_RelatedPrevOpTelemetryReason** – Postopek, povezan s prejšnjim postopkom.

- **Data_StopwatchDuration** – Skupno trajanje dogodka.

- **Data_UnpackLinkHint** – Oštevilčenje, ki predstavlja potencialno dejanje uporabnika s povezavo za razpakiranje.

- **Data_UnpackLinkPromptResult** – Oštevilčenje, ki predstavlja odgovor na poziv za povezavo za razpakiranje.

#### <a name="officedocsappdocsoperationopenfrommrubyurl"></a>Office.Docs.AppDocs.OperationOpenFromMruByUrl

Ta dogodek je zbran za Officeove aplikacije, ki se izvajajo v platformah Android, iOS, Universal ali Windows. Ta dogodek zabeleži, ko je postopek odpiranja datoteke izveden z URL-ja, navedenega na seznamu nedavno uporabljenih, in je uporabljen za razumevanje in določanje prioritete uporabniške izkušnje na podlagi podatkov o postopku odpiranja datoteke. 

Zbrana so sledeča polja:

- **Data_AppIdForReportEndBeforeAppKnown** – ID aplikacije, ko ni znan preden je bil za postopek priklican konec poročila.

- **Data_CanContinueFromOnBeforeOperationBegins** – Stanje CanContinue, preden je priklican program za obravnavo začetka.

- **Data_DetachedDuration** – Trajanje, zahtevano za odpenjanje postopka dogodka. 

- **Data_Doc_AccessMode** – oštevilčenje, ki ponazarja način za dostop datoteke, na primer samo za branje, branje in pisanje.

- **Data_Doc_AsyncOpenKind** – Oštevilčenje, ki ponazarja vrsto asinhronega poteka, ki se uporablja za odpiranje datoteke.

- **Data_Doc_ChunkingType** – Oštevilčenje, ki ponazarja vrsto algoritma za razdruževanje datoteke.

- **Data_Doc_EdpState** – Oštevilčenje, ki ponazarja stanje zaščite poslovnih podatkov datoteke.

- **Data_Doc_Ext** – Prvi 4 znaki razširitve datoteke.

- **Data_Doc_Fqdn** – Ime gostitelja strežnika datoteke.

- **Data_Doc_FqdnHash** – GUID, ki enolično določa ime gostitelja strežnika.

- **Data_Doc_IdentityTelemetryId** – enostranska zgoščena vrednost identitete uporabnika, uporabljena za odpiranje.

- **Data_Doc_InitializationScenario** – Oštevilčenje, ki označuje podrobno vrsto scenarija pri odpiranju datoteke.

- **Data_Doc_IOFlags** – oštevilčenje, ki označuje V-/I-zastavice postopka za odpiranje datoteke, na primer, ali je bila datoteka predpomnjena.

- **Data_Doc_IsCloudCollabEnabled** – Ali je za datoteko omogočeno sodelovanje v oblaku.

- **Data_Doc_IsIncrementalOpen** – Ali je bila datoteka odprta s funkcijo postopnega odpiranja.

- **Data_Doc_IsOcsSupported** – Ali datoteka podpira Officeovo storitev sodelovanja.

- **Data_Doc_IsOpeningOfflineCopy** – Ali je bila datoteka odprta iz predpomnjene kopije brez povezave.

- **Data_Doc_IsPrefetched** – Ali je bila datoteka vnaprej pridobljena, preden se je zagnal postopek odpiranja.

- **Data_Doc_IsSyncBacked** – Ali je na voljo lokalna različica datoteke, ki je sinhronizirana s strežnikom.

- **Data_Doc_Location** – oštevilčenje, ki označuje mesto datoteke, npr. lokalno ali v oblaku.

- **Data_Doc_ReadOnlyReasons** – oštevilčenje, ki označuje razlog datoteke, ki je samo za branje.

- **Data_Doc_ResourceIdHash** – GUID, ki enolično določa ID vira strežnika datoteke.

- **Data_Doc_RtcType** – Oštevilčenje, ki označuje vrsto kanala v realnem času (RTC), ki ga uporablja datoteka.

- **Data_Doc_ServerDocId** – GUID, ki enolično določa ID dokumenta strežnika.

- **Data_Doc_ServerProtocol** – Oštevilčenje, ki označuje protokol strežnika za datoteko v oblaku.

- **Data_Doc_ServerType** – Oštevilčenje, ki označuje vrsto strežnika za datoteko v oblaku.

- **Data_Doc_ServerVersion** – Oštevilčenje, ki označuje različico strežnika za datoteko v oblaku.

- **Data_Doc_SessionId** – celo število, ki se poveča za 1 za vsak postopek odpiranja datoteke v seji.

- **Data_Doc_SharePointServiceContext** – Niz, ki se uporablja za korelacijo odjemalskih in strežniških dnevnikov, po navadi je to neke vrste ID.

- **Data_Doc_SizeInBytes** – Velikost datoteke v bajtih.

- **Data_Doc_SpecialChars** – Oštevilčenje, ki označuje vrsto posebnega znaka, ki ga ima URL datoteke.

- **Data_Doc_UrlHash** – GUID, ki enolično določa URL datoteke.

- **Data_Doc_UsedWrsDataOnOpen** – Ali je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS.

- **Data_Doc_WopiServiceId** – Niz, ki označuje, iz katere storitve je datoteka WOPI (Web Application Interface Protocol).

- **Data_DocumentInputCurrency** – Vrsta vnosa dokumenta, ki ga uporablja postopek.

- **Data_DocumentOperation_AppId** – Vrednost oštevilčenja, ki predstavlja ID aplikacije.

- **Data_DocumentOperation_EndEventId** – Oznaka, ki predstavlja mesto, kjer se je postopek končal.

- **Data_DocumentOperation_EndReason** – Vrednost oštevilčenja, ki predstavlja razlog konca.

- **Data_DocumentOperation_IsReinitialized** – Znova inicializira dokument, ki je že odprt.

- **Data_DocumentOperation_ParamsFlags** – Oznake oštevilčenja, uporabljene za začetek postopka.

- **Data_DocumentOperation_TelemetryReason** – Oštevilčenje, ki predstavlja vhodno točko za dogodek odpiranja. Na primer odpiranje iz MRU ali brskanje, aktivacija datoteke itd.

- **Data_DocumentOperation_isTargetECBeginEC** – Kontekst ciljne izvedbe je enak kontekstu odpiranja.

- **Data_FileIOInclusiveMeasurements** – Vrednost niza, ki beleži čas, zahtevan za klice funkcij, v obliki zapisa z oznako funkcije ter trajanjem, ki vključuje trajanje klicev podfunkcij.

- **Data_FileIOMeasurements** – Vrednost niza, ki beleži čas, zahtevan za klice funkcij, v obliki zapisa z oznako funkcije ter trajanjem, ki ne vključuje trajanje klicev podfunkcij.

- **Data_IsNameMissingInUrl** – Označuje, če ime ni bilo razčlenjeno iz URL-ja.

- **Data_IsPathMissingForLocalFile** – Označuje, če je to lokalna datoteka brez poti.

- **Data_IsUnpackedLinkSupportedForOpen** – Označuje, ali je povezava, ki je ni mogoče razpakirati, podprta za odpiranje.

- **Data_LinksOpenRightScenario** – Vrednost oštevilčenja za scenarij pravilnega odpiranja povezav.

- **Data_OpEndEventId** – Oznaka, ki predstavlja, kjer se je postopek končal.

- **Data_RelatedPrevOpTelemetryReason** – Postopek, povezan s prejšnjim postopkom.

- **Data_StopwatchDuration** – Skupno trajanje dogodka.

- **Data_UnpackLinkHint** – Oštevilčenje, ki predstavlja potencialno dejanje uporabnika s povezavo za razpakiranje.

- **Data_UnpackLinkPromptResult** – Oštevilčenje, ki predstavlja odgovor na poziv za povezavo za razpakiranje.


#### <a name="officedocsappdocsoperationopenfrompath"></a>Office.Docs.AppDocs.OperationOpenFromPath

Ta dogodek je zbran za Officeove aplikacije, ki se izvajajo v platformah Android, iOS, Universal ali Windows. Dogodek zabeleži odpiranje datoteke s poti, uporablja pa se za razumevanje in določanje prednosti uporabniških izkušenj glede na informacije o odpiranju datoteke.

Zbrana so sledeča polja:

- **Data_AppIdForReportEndBeforeAppKnown** – ID aplikacije, ko ni znan preden je bil za postopek priklican konec poročila.

- **Data_CanContinueFromOnBeforeOperationBegins** – Stanje CanContinue, preden je priklican program za obravnavo začetka.

- **Data_DetachedDuration** – Trajanje, zahtevano za odpenjanje postopka dogodka. 

- **Data_Doc_AccessMode** – oštevilčenje, ki ponazarja način za dostop datoteke, na primer samo za branje, branje in pisanje.

- **Data_Doc_AsyncOpenKind** – Oštevilčenje, ki ponazarja vrsto asinhronega poteka, ki se uporablja za odpiranje datoteke.

- **Data_Doc_ChunkingType** – Oštevilčenje, ki ponazarja vrsto algoritma za razdruževanje datoteke.

- **Data_Doc_EdpState** – Oštevilčenje, ki ponazarja stanje zaščite poslovnih podatkov datoteke.

- **Data_Doc_Ext** – Prvi 4 znaki razširitve datoteke.

- **Data_Doc_Fqdn** – Ime gostitelja strežnika datoteke.

- **Data_Doc_FqdnHash** – GUID, ki enolično določa ime gostitelja strežnika.

- **Data_Doc_IdentityTelemetryId** – enostranska zgoščena vrednost identitete uporabnika, uporabljena za odpiranje.

- **Data_Doc_InitializationScenario** – Oštevilčenje, ki označuje podrobno vrsto scenarija pri odpiranju datoteke.

- **Data_Doc_IOFlags** – oštevilčenje, ki označuje V-/I-zastavice postopka za odpiranje datoteke, na primer, ali je bila datoteka predpomnjena.

- **Data_Doc_IsCloudCollabEnabled** – Ali je za datoteko omogočeno sodelovanje v oblaku.

- **Data_Doc_IsIncrementalOpen** – Ali je bila datoteka odprta s funkcijo postopnega odpiranja.

- **Data_Doc_IsOcsSupported** – Ali datoteka podpira Officeovo storitev sodelovanja.

- **Data_Doc_IsOpeningOfflineCopy** – Ali je bila datoteka odprta iz predpomnjene kopije brez povezave.

- **Data_Doc_IsPrefetched** – Ali je bila datoteka vnaprej pridobljena, preden se je zagnal postopek odpiranja.

- **Data_Doc_IsSyncBacked** – Ali je na voljo lokalna različica datoteke, ki je sinhronizirana s strežnikom.

- **Data_Doc_Location** – oštevilčenje, ki označuje mesto datoteke, npr. lokalno ali v oblaku.

- **Data_Doc_ReadOnlyReasons** – oštevilčenje, ki označuje razlog datoteke, ki je samo za branje.

- **Data_Doc_ResourceIdHash** – GUID, ki enolično določa ID vira strežnika datoteke.

- **Data_Doc_RtcType** – Oštevilčenje, ki označuje vrsto kanala v realnem času (RTC), ki ga uporablja datoteka.

- **Data_Doc_ServerDocId** – GUID, ki enolično določa ID dokumenta strežnika.

- **Data_Doc_ServerProtocol** – Oštevilčenje, ki označuje protokol strežnika za datoteko v oblaku.

- **Data_Doc_ServerType** – Oštevilčenje, ki označuje vrsto strežnika za datoteko v oblaku.

- **Data_Doc_ServerVersion** – Oštevilčenje, ki označuje različico strežnika za datoteko v oblaku.

- **Data_Doc_SessionId** – celo število, ki se poveča za 1 za vsak postopek odpiranja datoteke v seji.

- **Data_Doc_SharePointServiceContext** – Niz, ki se uporablja za korelacijo odjemalskih in strežniških dnevnikov, po navadi je to neke vrste ID.

- **Data_Doc_SizeInBytes** – Velikost datoteke v bajtih.

- **Data_Doc_SpecialChars** – Oštevilčenje, ki označuje vrsto posebnega znaka, ki ga ima URL datoteke.

- **Data_Doc_UrlHash** – GUID, ki enolično določa URL datoteke.

- **Data_Doc_UsedWrsDataOnOpen** – Ali je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS.

- **Data_Doc_WopiServiceId** – Niz, ki označuje, iz katere storitve je datoteka WOPI (Web Application Interface Protocol).

- **Data_DocumentInputCurrency** – Vrsta vnosa dokumenta, ki ga uporablja postopek.

- **Data_DocumentOperation_AppId** – Vrednost oštevilčenja, ki predstavlja ID aplikacije.

- **Data_DocumentOperation_EndEventId** – Oznaka, ki predstavlja mesto, kjer se je postopek končal.

- **Data_DocumentOperation_EndReason** – Vrednost oštevilčenja, ki predstavlja razlog konca.

- **Data_DocumentOperation_IsReinitialized** – Znova inicializira dokument, ki je že odprt.

- **Data_DocumentOperation_ParamsFlags** – Oznake oštevilčenja, uporabljene za začetek postopka.

- **Data_DocumentOperation_TelemetryReason** – Oštevilčenje, ki predstavlja vhodno točko za dogodek odpiranja. Na primer odpiranje iz MRU ali brskanje, aktivacija datoteke itd.

- **Data_DocumentOperation_isTargetECBeginEC** – Kontekst ciljne izvedbe je enak kontekstu odpiranja.

- **Data_FileIOInclusiveMeasurements** – Vrednost niza, ki beleži čas, zahtevan za klice funkcij, v obliki zapisa z oznako funkcije ter trajanjem, ki vključuje trajanje klicev podfunkcij.

- **Data_FileIOMeasurements** – Vrednost niza, ki beleži čas, zahtevan za klice funkcij, v obliki zapisa z oznako funkcije ter trajanjem, ki ne vključuje trajanje klicev podfunkcij.

- **Data_IsNameMissingInUrl** – Označuje, če ime ni bilo razčlenjeno iz URL-ja.

- **Data_IsPathMissingForLocalFile** – Označuje, če je to lokalna datoteka brez poti.

- **Data_IsUnpackedLinkSupportedForOpen** – Označuje, ali je povezava, ki je ni mogoče razpakirati, podprta za odpiranje.

- **Data_LinksOpenRightScenario** – Vrednost oštevilčenja za scenarij pravilnega odpiranja povezav.

- **Data_OpEndEventId** – Oznaka, ki predstavlja, kjer se je postopek končal.

- **Data_RelatedPrevOpTelemetryReason** – Postopek, povezan s prejšnjim postopkom.

- **Data_StopwatchDuration** – Skupno trajanje dogodka.

- **Data_UnpackLinkHint** – Oštevilčenje, ki predstavlja potencialno dejanje uporabnika s povezavo za razpakiranje.

- **Data_UnpackLinkPromptResult** – Oštevilčenje, ki predstavlja odgovor na poziv za povezavo za razpakiranje.

#### <a name="officedocsappdocsoperationopenfromprotocolhandler"></a>Office.Docs.AppDocs.OperationOpenFromProtocolHandler

Ta dogodek je zbran za Officeove aplikacije, ki se izvajajo v platformah Android, iOS, Universal ali Windows. Dogodek zabeleži postopek odpiranja datoteke v drugi aplikaciji, ki uporablja vmesnik programa za obravnavo protokola, uporabljen pa je za razumevanje in določanje prioritete uporabniških izkušenj na podlagi informacij o odpiranju datoteke.

Zbrana so sledeča polja:

- **Data_AppIdForReportEndBeforeAppKnown** – ID aplikacije, ko ni znan preden je bil za postopek priklican konec poročila.

- **Data_CanContinueFromOnBeforeOperationBegins** – Stanje CanContinue, preden je priklican program za obravnavo začetka.

- **Data_DetachedDuration** – Trajanje, zahtevano za odpenjanje postopka dogodka. 

- **Data_Doc_AccessMode** – oštevilčenje, ki ponazarja način za dostop datoteke, na primer samo za branje, branje in pisanje.

- **Data_Doc_AsyncOpenKind** – Oštevilčenje, ki ponazarja vrsto asinhronega poteka, ki se uporablja za odpiranje datoteke.

- **Data_Doc_ChunkingType** – Oštevilčenje, ki ponazarja vrsto algoritma za razdruževanje datoteke.

- **Data_Doc_EdpState** – Oštevilčenje, ki ponazarja stanje zaščite poslovnih podatkov datoteke.

- **Data_Doc_Ext** – Prvi 4 znaki razširitve datoteke.

- **Data_Doc_Fqdn** – Ime gostitelja strežnika datoteke.

- **Data_Doc_FqdnHash** – GUID, ki enolično določa ime gostitelja strežnika.

- **Data_Doc_IdentityTelemetryId** – enostranska zgoščena vrednost identitete uporabnika, uporabljena za odpiranje.

- **Data_Doc_InitializationScenario** – Oštevilčenje, ki označuje podrobno vrsto scenarija pri odpiranju datoteke.

- **Data_Doc_IOFlags** – oštevilčenje, ki označuje V-/I-zastavice postopka za odpiranje datoteke, na primer, ali je bila datoteka predpomnjena.

- **Data_Doc_IsCloudCollabEnabled** – Ali je za datoteko omogočeno sodelovanje v oblaku.

- **Data_Doc_IsIncrementalOpen** – Ali je bila datoteka odprta s funkcijo postopnega odpiranja.

- **Data_Doc_IsOcsSupported** – Ali datoteka podpira Officeovo storitev sodelovanja.

- **Data_Doc_IsOpeningOfflineCopy** – Ali je bila datoteka odprta iz predpomnjene kopije brez povezave.

- **Data_Doc_IsPrefetched** – Ali je bila datoteka vnaprej pridobljena, preden se je zagnal postopek odpiranja.

- **Data_Doc_IsSyncBacked** – Ali je na voljo lokalna različica datoteke, ki je sinhronizirana s strežnikom.

- **Data_Doc_Location** – oštevilčenje, ki označuje mesto datoteke, npr. lokalno ali v oblaku.

- **Data_Doc_ReadOnlyReasons** – oštevilčenje, ki označuje razlog datoteke, ki je samo za branje.

- **Data_Doc_ResourceIdHash** – GUID, ki enolično določa ID vira strežnika datoteke.

- **Data_Doc_RtcType** – Oštevilčenje, ki označuje vrsto kanala v realnem času (RTC), ki ga uporablja datoteka.

- **Data_Doc_ServerDocId** – GUID, ki enolično določa ID dokumenta strežnika.

- **Data_Doc_ServerProtocol** – Oštevilčenje, ki označuje protokol strežnika za datoteko v oblaku.

- **Data_Doc_ServerType** – Oštevilčenje, ki označuje vrsto strežnika za datoteko v oblaku.

- **Data_Doc_ServerVersion** – Oštevilčenje, ki označuje različico strežnika za datoteko v oblaku.

- **Data_Doc_SessionId** – celo število, ki se poveča za 1 za vsak postopek odpiranja datoteke v seji.

- **Data_Doc_SharePointServiceContext** – Niz, ki se uporablja za korelacijo odjemalskih in strežniških dnevnikov, po navadi je to neke vrste ID.

- **Data_Doc_SizeInBytes** – Velikost datoteke v bajtih.

- **Data_Doc_SpecialChars** – Oštevilčenje, ki označuje vrsto posebnega znaka, ki ga ima URL datoteke.

- **Data_Doc_UrlHash** – GUID, ki enolično določa URL datoteke.

- **Data_Doc_UsedWrsDataOnOpen** – Ali je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS.

- **Data_Doc_WopiServiceId** – Niz, ki označuje, iz katere storitve je datoteka WOPI (Web Application Interface Protocol).

- **Data_DocumentInputCurrency** – Vrsta vnosa dokumenta, ki ga uporablja postopek.

- **Data_DocumentOperation_AppId** – Vrednost oštevilčenja, ki predstavlja ID aplikacije.

- **Data_DocumentOperation_EndEventId** – Oznaka, ki predstavlja mesto, kjer se je postopek končal.

- **Data_DocumentOperation_EndReason** – Vrednost oštevilčenja, ki predstavlja razlog konca.

- **Data_DocumentOperation_IsReinitialized** – Znova inicializira dokument, ki je že odprt.

- **Data_DocumentOperation_ParamsFlags** – Oznake oštevilčenja, uporabljene za začetek postopka.

- **Data_DocumentOperation_TelemetryReason** – Oštevilčenje, ki predstavlja vhodno točko za dogodek odpiranja. Na primer odpiranje iz MRU ali brskanje, aktivacija datoteke itd.

- **Data_DocumentOperation_isTargetECBeginEC** – Kontekst ciljne izvedbe je enak kontekstu odpiranja.

- **Data_FileIOInclusiveMeasurements** – Vrednost niza, ki beleži čas, zahtevan za klice funkcij, v obliki zapisa z oznako funkcije ter trajanjem, ki vključuje trajanje klicev podfunkcij.

- **Data_FileIOMeasurements** – Vrednost niza, ki beleži čas, zahtevan za klice funkcij, v obliki zapisa z oznako funkcije ter trajanjem, ki ne vključuje trajanje klicev podfunkcij.

- **Data_IsNameMissingInUrl** – Označuje, če ime ni bilo razčlenjeno iz URL-ja.

- **Data_IsPathMissingForLocalFile** – Označuje, če je to lokalna datoteka brez poti.

- **Data_IsUnpackedLinkSupportedForOpen** – Označuje, ali je povezava, ki je ni mogoče razpakirati, podprta za odpiranje.

- **Data_LinksOpenRightScenario** – Vrednost oštevilčenja za scenarij pravilnega odpiranja povezav.

- **Data_OpEndEventId** – Oznaka, ki predstavlja, kjer se je postopek končal.

- **Data_RelatedPrevOpTelemetryReason** – Postopek, povezan s prejšnjim postopkom.

- **Data_StopwatchDuration** – Skupno trajanje dogodka.

- **Data_UnpackLinkHint** – Oštevilčenje, ki predstavlja potencialno dejanje uporabnika s povezavo za razpakiranje.

- **Data_UnpackLinkPromptResult** – Oštevilčenje, ki predstavlja odgovor na poziv za povezavo za razpakiranje.

#### <a name="officedocsappdocsoperationopenfromshell"></a>Office.Docs.AppDocs.OperationOpenFromShell

Ta dogodek je zbran za Officeove aplikacije, ki se izvajajo v platformah Android, iOS, Universal ali Windows. Dogodek zabeleži odpiranje datoteke iz lupine, uporablja pa se za razumevanje in določanje prednosti uporabniških izkušenj glede na informacije o odpiranju datoteke.

Zbrana so sledeča polja:

- **Data_AppIdForReportEndBeforeAppKnown** – ID aplikacije, ko ni znan preden je bil za postopek priklican konec poročila.

- **Data_CanContinueFromOnBeforeOperationBegins** – Stanje CanContinue, preden je priklican program za obravnavo začetka.

- **Data_DetachedDuration** – Trajanje, zahtevano za odpenjanje postopka dogodka. 

- **Data_Doc_AccessMode** – oštevilčenje, ki ponazarja način za dostop datoteke, na primer samo za branje, branje in pisanje.

- **Data_Doc_AsyncOpenKind** – Oštevilčenje, ki ponazarja vrsto asinhronega poteka, ki se uporablja za odpiranje datoteke.

- **Data_Doc_ChunkingType** – Oštevilčenje, ki ponazarja vrsto algoritma za razdruževanje datoteke.

- **Data_Doc_EdpState** – Oštevilčenje, ki ponazarja stanje zaščite poslovnih podatkov datoteke.

- **Data_Doc_Ext** – Prvi 4 znaki razširitve datoteke.

- **Data_Doc_Fqdn** – Ime gostitelja strežnika datoteke.

- **Data_Doc_FqdnHash** – GUID, ki enolično določa ime gostitelja strežnika.

- **Data_Doc_IdentityTelemetryId** – enostranska zgoščena vrednost identitete uporabnika, uporabljena za odpiranje.

- **Data_Doc_InitializationScenario** – Oštevilčenje, ki označuje podrobno vrsto scenarija pri odpiranju datoteke.

- **Data_Doc_IOFlags** – oštevilčenje, ki označuje V-/I-zastavice postopka za odpiranje datoteke, na primer, ali je bila datoteka predpomnjena.

- **Data_Doc_IsCloudCollabEnabled** – Ali je za datoteko omogočeno sodelovanje v oblaku.

- **Data_Doc_IsIncrementalOpen** – Ali je bila datoteka odprta s funkcijo postopnega odpiranja.

- **Data_Doc_IsOcsSupported** – Ali datoteka podpira Officeovo storitev sodelovanja.

- **Data_Doc_IsOpeningOfflineCopy** – Ali je bila datoteka odprta iz predpomnjene kopije brez povezave.

- **Data_Doc_IsPrefetched** – Ali je bila datoteka vnaprej pridobljena, preden se je zagnal postopek odpiranja.

- **Data_Doc_IsSyncBacked** – Ali je na voljo lokalna različica datoteke, ki je sinhronizirana s strežnikom.

- **Data_Doc_Location** – oštevilčenje, ki označuje mesto datoteke, npr. lokalno ali v oblaku.

- **Data_Doc_ReadOnlyReasons** – oštevilčenje, ki označuje razlog datoteke, ki je samo za branje.

- **Data_Doc_ResourceIdHash** – GUID, ki enolično določa ID vira strežnika datoteke.

- **Data_Doc_RtcType** – Oštevilčenje, ki označuje vrsto kanala v realnem času (RTC), ki ga uporablja datoteka.

- **Data_Doc_ServerDocId** – GUID, ki enolično določa ID dokumenta strežnika.

- **Data_Doc_ServerProtocol** – Oštevilčenje, ki označuje protokol strežnika za datoteko v oblaku.

- **Data_Doc_ServerType** – Oštevilčenje, ki označuje vrsto strežnika za datoteko v oblaku.

- **Data_Doc_ServerVersion** – Oštevilčenje, ki označuje različico strežnika za datoteko v oblaku.

- **Data_Doc_SessionId** – celo število, ki se poveča za 1 za vsak postopek odpiranja datoteke v seji.

- **Data_Doc_SharePointServiceContext** – Niz, ki se uporablja za korelacijo odjemalskih in strežniških dnevnikov, po navadi je to neke vrste ID.

- **Data_Doc_SizeInBytes** – Velikost datoteke v bajtih.

- **Data_Doc_SpecialChars** – Oštevilčenje, ki označuje vrsto posebnega znaka, ki ga ima URL datoteke.

- **Data_Doc_UrlHash** – GUID, ki enolično določa URL datoteke.

- **Data_Doc_UsedWrsDataOnOpen** – Ali je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS.

- **Data_Doc_WopiServiceId** – Niz, ki označuje, iz katere storitve je datoteka WOPI (Web Application Interface Protocol).

- **Data_DocumentInputCurrency** – Vrsta vnosa dokumenta, ki ga uporablja postopek.

- **Data_DocumentOperation_AppId** – Vrednost oštevilčenja, ki predstavlja ID aplikacije.

- **Data_DocumentOperation_EndEventId** – Oznaka, ki predstavlja mesto, kjer se je postopek končal.

- **Data_DocumentOperation_EndReason** – Vrednost oštevilčenja, ki predstavlja razlog konca.

- **Data_DocumentOperation_IsReinitialized** – Znova inicializira dokument, ki je že odprt.

- **Data_DocumentOperation_ParamsFlags** – Oznake oštevilčenja, uporabljene za začetek postopka.

- **Data_DocumentOperation_TelemetryReason** – Oštevilčenje, ki predstavlja vhodno točko za dogodek odpiranja. Na primer odpiranje iz MRU ali brskanje, aktivacija datoteke itd.

- **Data_DocumentOperation_isTargetECBeginEC** – Kontekst ciljne izvedbe je enak kontekstu odpiranja.

- **Data_FileIOInclusiveMeasurements** – Vrednost niza, ki beleži čas, zahtevan za klice funkcij, v obliki zapisa z oznako funkcije ter trajanjem, ki vključuje trajanje klicev podfunkcij.

- **Data_FileIOMeasurements** – Vrednost niza, ki beleži čas, zahtevan za klice funkcij, v obliki zapisa z oznako funkcije ter trajanjem, ki ne vključuje trajanje klicev podfunkcij.

- **Data_IsNameMissingInUrl** – Označuje, če ime ni bilo razčlenjeno iz URL-ja.

- **Data_IsPathMissingForLocalFile** – Označuje, če je to lokalna datoteka brez poti.

- **Data_IsUnpackedLinkSupportedForOpen** – Označuje, ali je povezava, ki je ni mogoče razpakirati, podprta za odpiranje.

- **Data_LinksOpenRightScenario** – Vrednost oštevilčenja za scenarij pravilnega odpiranja povezav.

- **Data_OpEndEventId** – Oznaka, ki predstavlja, kjer se je postopek končal.

- **Data_RelatedPrevOpTelemetryReason** – Postopek, povezan s prejšnjim postopkom.

- **Data_StopwatchDuration** – Skupno trajanje dogodka.

- **Data_UnpackLinkHint** – Oštevilčenje, ki predstavlja potencialno dejanje uporabnika s povezavo za razpakiranje.

- **Data_UnpackLinkPromptResult** – Oštevilčenje, ki predstavlja odgovor na poziv za povezavo za razpakiranje.


#### <a name="officedocsappdocsoperationopenfromurl"></a>Office.Docs.AppDocs.OperationOpenFromUrl

Ta dogodek je zbran za Officeove aplikacije, ki se izvajajo v platformah Android, iOS, Universal ali Windows. Dogodek zabeleži odpiranje datoteke z URL-ja, uporablja pa se za razumevanje in določanje prednosti uporabniških izkušenj glede na informacije o odpiranju datoteke.

Zbrana so sledeča polja:

- **Data_AppIdForReportEndBeforeAppKnown** – ID aplikacije, ko ni znan preden je bil za postopek priklican konec poročila.

- **Data_CanContinueFromOnBeforeOperationBegins** – Stanje CanContinue, preden je priklican program za obravnavo začetka.

- **Data_DetachedDuration** – Trajanje, zahtevano za odpenjanje postopka dogodka. 

- **Data_Doc_AccessMode** – oštevilčenje, ki ponazarja način za dostop datoteke, na primer samo za branje, branje in pisanje.

- **Data_Doc_AsyncOpenKind** – Oštevilčenje, ki ponazarja vrsto asinhronega poteka, ki se uporablja za odpiranje datoteke.

- **Data_Doc_ChunkingType** – Oštevilčenje, ki ponazarja vrsto algoritma za razdruževanje datoteke.

- **Data_Doc_EdpState** – Oštevilčenje, ki ponazarja stanje zaščite poslovnih podatkov datoteke.

- **Data_Doc_Ext** – Prvi 4 znaki razširitve datoteke.

- **Data_Doc_Fqdn** – Ime gostitelja strežnika datoteke.

- **Data_Doc_FqdnHash** – GUID, ki enolično določa ime gostitelja strežnika.

- **Data_Doc_IdentityTelemetryId** – enostranska zgoščena vrednost identitete uporabnika, uporabljena za odpiranje.

- **Data_Doc_InitializationScenario** – Oštevilčenje, ki označuje podrobno vrsto scenarija pri odpiranju datoteke.

- **Data_Doc_IOFlags** – oštevilčenje, ki označuje V-/I-zastavice postopka za odpiranje datoteke, na primer, ali je bila datoteka predpomnjena.

- **Data_Doc_IsCloudCollabEnabled** – Ali je za datoteko omogočeno sodelovanje v oblaku.

- **Data_Doc_IsIncrementalOpen** – Ali je bila datoteka odprta s funkcijo postopnega odpiranja.

- **Data_Doc_IsOcsSupported** – Ali datoteka podpira Officeovo storitev sodelovanja.

- **Data_Doc_IsOpeningOfflineCopy** – Ali je bila datoteka odprta iz predpomnjene kopije brez povezave.

- **Data_Doc_IsPrefetched** – Ali je bila datoteka vnaprej pridobljena, preden se je zagnal postopek odpiranja.

- **Data_Doc_IsSyncBacked** – Ali je na voljo lokalna različica datoteke, ki je sinhronizirana s strežnikom.

- **Data_Doc_Location** – oštevilčenje, ki označuje mesto datoteke, npr. lokalno ali v oblaku.

- **Data_Doc_ReadOnlyReasons** – oštevilčenje, ki označuje razlog datoteke, ki je samo za branje.

- **Data_Doc_ResourceIdHash** – GUID, ki enolično določa ID vira strežnika datoteke.

- **Data_Doc_RtcType** – Oštevilčenje, ki označuje vrsto kanala v realnem času (RTC), ki ga uporablja datoteka.

- **Data_Doc_ServerDocId** – GUID, ki enolično določa ID dokumenta strežnika.

- **Data_Doc_ServerProtocol** – Oštevilčenje, ki označuje protokol strežnika za datoteko v oblaku.

- **Data_Doc_ServerType** – Oštevilčenje, ki označuje vrsto strežnika za datoteko v oblaku.

- **Data_Doc_ServerVersion** – Oštevilčenje, ki označuje različico strežnika za datoteko v oblaku.

- **Data_Doc_SessionId** – celo število, ki se poveča za 1 za vsak postopek odpiranja datoteke v seji.

- **Data_Doc_SharePointServiceContext** – Niz, ki se uporablja za korelacijo odjemalskih in strežniških dnevnikov, po navadi je to neke vrste ID.

- **Data_Doc_SizeInBytes** – Velikost datoteke v bajtih.

- **Data_Doc_SpecialChars** – Oštevilčenje, ki označuje vrsto posebnega znaka, ki ga ima URL datoteke.

- **Data_Doc_UrlHash** – GUID, ki enolično določa URL datoteke.

- **Data_Doc_UsedWrsDataOnOpen** – Ali je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS.

- **Data_Doc_WopiServiceId** – Niz, ki označuje, iz katere storitve je datoteka WOPI (Web Application Interface Protocol).

- **Data_DocumentInputCurrency** – Vrsta vnosa dokumenta, ki ga uporablja postopek.

- **Data_DocumentOperation_AppId** – Vrednost oštevilčenja, ki predstavlja ID aplikacije.

- **Data_DocumentOperation_EndEventId** – Oznaka, ki predstavlja mesto, kjer se je postopek končal.

- **Data_DocumentOperation_EndReason** – Vrednost oštevilčenja, ki predstavlja razlog konca.

- **Data_DocumentOperation_IsReinitialized** – Znova inicializira dokument, ki je že odprt.

- **Data_DocumentOperation_ParamsFlags** – Oznake oštevilčenja, uporabljene za začetek postopka.

- **Data_DocumentOperation_TelemetryReason** – Oštevilčenje, ki predstavlja vhodno točko za dogodek odpiranja. Na primer odpiranje iz MRU ali brskanje, aktivacija datoteke itd.

- **Data_DocumentOperation_isTargetECBeginEC** – Kontekst ciljne izvedbe je enak kontekstu odpiranja.

- **Data_FileIOInclusiveMeasurements** – Vrednost niza, ki beleži čas, zahtevan za klice funkcij, v obliki zapisa z oznako funkcije ter trajanjem, ki vključuje trajanje klicev podfunkcij.

- **Data_FileIOMeasurements** – Vrednost niza, ki beleži čas, zahtevan za klice funkcij, v obliki zapisa z oznako funkcije ter trajanjem, ki ne vključuje trajanje klicev podfunkcij.

- **Data_IsNameMissingInUrl** – Označuje, če ime ni bilo razčlenjeno iz URL-ja.

- **Data_IsPathMissingForLocalFile** – Označuje, če je to lokalna datoteka brez poti.

- **Data_IsUnpackedLinkSupportedForOpen** – Označuje, ali je povezava, ki je ni mogoče razpakirati, podprta za odpiranje.

- **Data_LinksOpenRightScenario** – Vrednost oštevilčenja za scenarij pravilnega odpiranja povezav.

- **Data_OpEndEventId** – Oznaka, ki predstavlja, kjer se je postopek končal.

- **Data_RelatedPrevOpTelemetryReason** – Postopek, povezan s prejšnjim postopkom.

- **Data_StopwatchDuration** – Skupno trajanje dogodka.

- **Data_UnpackLinkHint** – Oštevilčenje, ki predstavlja potencialno dejanje uporabnika s povezavo za razpakiranje.

- **Data_UnpackLinkPromptResult** – Oštevilčenje, ki predstavlja odgovor na poziv za povezavo za razpakiranje.



#### <a name="officedocsappledocsuxiossaveasthroughfilemenu"></a>Office.Docs.Apple.DocsUXiOSSaveAsThroughFileMenu 

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek zabeleži, ko se izvede operacija »Shrani kot«, uporablja pa za razumevanje in določanje prednosti uporabniških izkušenj na podlagi informacij o datotečnih operacijah, kot so kategorije mest.  Operacija »Shrani kot« se izvede vsakič, ko uporabnik ustvari novo datoteko in jo shrani prvič ali ko shrani kopijo obstoječe datoteke na novo mesto.

Zbrana so sledeča polja:

- **Data_OriginServiceType** – abstraktna kategorizacija izvirnega mesta datoteke, na primer »SharePoint«, »OneDrive«, »Lokalno«, »WOPI« itn., ne pa dejansko mesto datoteke.

- **Data_ServiceType** – abstraktna kategorizacija novega mesta datoteke po dokončanem shranjevanju, na primer »SharePoint« , »OneDrive«, »Lokalno«, »WOPI« itn., ne pa dejansko mesto datoteke.

#### <a name="officedocsappledocsuxmacatmentioninsertedatmention"></a>Office.Docs.Apple.DocsUXMacAtMentionInsertedAtMention 

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Ta dogodek zabeleži, ko uporabnik »@« omeni drugega uporabnika, uporablja pa se za razumevanje in določanje prednosti uporabniških izkušenj na podlagi tega, kako uporabniki sodelujejo z drugimi uporabniki.

Zbrana so sledeča polja:

- **Data_CharactersTyped** – številska vrednost, ki označuje skupno število znakov vnesenega besedila »@« omembe.

#### <a name="officedocsappledocsuxmacodspsharingwebviewsharingcompleted"></a>Office.Docs.Apple.DocsUXMacODSPSharingWebViewSharingCompleted 

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Ta dogodek zabeleži, ko uporabnik da dokument v oblaku v skupno rabo z uporabo izkušnje dajanja v skupno rabo OneDrive, uporablja pa se za boljše razumevanje in določanje prednosti uporabniških izkušenj na podlagi skupne rabe dokumentov.

Zbrana so sledeča polja:

- **Data_ShareType** – vprogramiran niz, ki označuje, katera vrsta operacije za skupno rabo je bila dokončana, kar med drugim vključuje tudi »Kopiranje povezave«, »Več aplikacij« in »Teams«.

- **Data_ShareWebViewMode** – vprogramiran niz, ki označuje, kakšen način skupne rabe je bil aktiven, ko je bilo dokončano dajanje v skupno rabo, kar med drugim vključuje tudi »ManageAccess«, »AtMentions« in »Skupna raba«.

#### <a name="officedocsuicollaborationcoauthorgalleryrowtapped"></a>Office.DocsUI.Collaboration.CoauthorGalleryRowTapped 

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Ta dogodek zabeleži, ko si uporabnik ogleda seznam trenutnih soavtorjev.  Te podatke uporabljamo za boljše razumevanje in določanje prednosti uporabniških izkušenj, povezanih s sočasnim soavtorstvom dokumenta.

Zbrana so naslednja polja:

- **Data_CoauthorCount** – številska vrednost, ki predstavlja skupno število oseb, ki trenutno urejajo isti dokument kot uporabnik.

#### <a name="officedocsuicollaborationcollabcornerpeoplegallerycoauthorsupdated"></a>Office.DocsUI.Collaboration.CollabCornerPeopleGalleryCoauthorsUpdated 

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek zabeleži, ko se spremeni število aktivnih soavtorjev v dokumentu v oblaku.  Te podatke uporabljamo za boljše razumevanje in določanje prednosti uporabniških izkušenj, povezanih s sočasnim soavtorstvom dokumenta.

Zbrana so naslednja polja:

- **Data_CoauthorsJoined** – število soavtorjev, ki so se pridružili dokumentu.

- **Data_CoauthorsJoined** – število soavtorjev, ki so zapustili dokument.

- **Data_NewCoauthorCount** – novo število aktivnih soavtorjev v dokumentu. 

- **Data_OldCoauthorCount** – prejšnje število aktivnih soavtorjev pred posodobitvijo.

- **Data_ ServiceType** – abstraktna kategorizacija mesta datoteke, na primer »SharePoint«, »OneDrive«, »Lokalno«, »WOPI« itn., ne pa dejansko mesto datoteke.

#### <a name="officedocsuidocstagedocstagecreatenewfromtemplate"></a>Office.DocsUI.DocStage.DocStageCreateNewFromTemplate 

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek zabeleži, ko je ustvarjena nova datoteka na osnovi izkušnje »Novo iz predloge«, uporablja pa se za boljše razumevanje in določanje prednosti uporabniških izkušenj na podlagi informacij o ustvarjanju dokumenta.

Zbrana so sledeča polja:

- **Data_InHomeTab** – logična vrednost, ki označuje, ali je bila nova datoteka v predlogi ustvarjena na zavihku »Osnovno« v novi izkušnji datoteke.

- **Data_InSearch** – logična vrednost, ki označuje, ali je bila datoteka ustvarjena, ko je uporabnik iskal predlogo.

- **Data_IsHomeTabEnabled** – logična vrednost, ki označuje, ali je zavihek »Osnovno« trenutno na voljo uporabniku.

- **Data_IsRecommendedEnabled** – logična vrednost, ki označuje, ali je izkušnja »Priporočeno« trenutno na voljo uporabniku.

- **Data_TemplateIndex** – številski indeks datoteke predloge, kot je vizualno prikazan uporabniku.

- **Data_TemplateType** – klasifikacija za boljše razlikovanje vrste predloge, kar med drugim vključuje tudi predloge »V spletu«, predloge »Spletno iskanje« in predloge »Lokalno«.

#### <a name="officedocsuidocstagerecommendedopen"></a>Office.DocsUI.DocStage.RecommendedOpen

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek zabeleži, ko se operacija odpiranja datoteke izvede iz razdelka za priporočene datoteke v galeriji dokumentov, uporablja pa za razumevanje in določanje prednosti uporabniških izkušenj na podlagi informacij o operaciji odpiranja datoteke.

Zbrana so naslednja polja:

- **Data_Success** – logična vrednost, ki označuje, ali je bila operacija uspešna.

#### <a name="officedocsuifileoperationsdocsuifileopenmacrequired"></a>Office.DocsUI.FileOperations.DocsUIFileOpenMacRequired

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek zabeleži, ko se izvede operacija za odpiranje datoteke, uporablja pa za razumevanje in določanje prednosti uporabniških izkušenj na podlagi informacij o operaciji odpiranja datoteke, kot so kategorije mest »ServiceType« in prvi štirje znaki pripone.

Zbrana so sledeča polja:

- **Data_Ext** – pripona datoteke, omejena na največ prve štiri znake pripone.

- **Data_ServiceType** – abstraktna kategorizacija mesta datoteke, na primer »SharePoint«, »OneDrive«, »Lokalno«, »WOPI« itn.

#### <a name="officedocsuifileoperationsopendocumentmeasurements"></a>Office.DocsUI.FileOperations.OpenDocumentMeasurements

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformi iOS. Dogodek se zabeleži ob odpiranju datoteke, uporablja pa za razumevanje in določanje prednosti uporabniških izkušenj glede na informacije o odpiranju datoteke, zlasti informacije o učinkovitosti.

Zbrana so naslednja polja:

- **Data_AppDuration** – Čas, zahtevan za obdelavo aplikacije med odpiranjem datoteke.

- **Data_BootDuration** – Čas, zahtevan za zagon postopka za odpiranje datoteke.

- **Data_ClickOrigin** – Niz, ki označuje, izvirno mesto povezave, ko je uporabnik kliknil povezavo v Outlooku v sistemu iOS za odpiranje datoteke v Officeovi aplikaciji.

- **Data_ClickTime** – čas Unixa, ko je uporabnik kliknil povezavo v Outlooku v sistemu iOS za odpiranje datoteke v Officeovi aplikaciji.

- **Data_ClosePreviouslyOpenedMarkers** – vrednost niza, ki beleži čas med klici funkcij, v obliki zapisa z ID-jem in trajanjem.

- **Data_DetachedDuration** – trajanje, zahtevano za odpenjanje postopka dogodka. 

- **Data_Doc_AccessMode** – Oštevilčenje, ki ponazarja način za dostop datoteke, na primer samo za branje, branje in pisanje.

- **Data_Doc_AsyncOpenKind** – Oštevilčenje, ki ponazarja vrsto asinhronega poteka, ki se uporablja za odpiranje datoteke.

- **Data_Doc_ChunkingType** – Oštevilčenje, ki ponazarja vrsto algoritma za razdruževanje datoteke.

- **Data_Doc_EdpState** – Oštevilčenje, ki ponazarja stanje zaščite poslovnih podatkov datoteke.

- **Data_Doc_Ext** – Datotečna pripona datoteke.

- **Data_Doc_Fqdn** – Ime gostitelja strežnika datoteke.

- **Data_Doc_FqdnHash** – GUID, ki enolično določa ime gostitelja strežnika.

- **Data_Doc_IdentityTelemetryId** – GUID, ki enolično prepozna identiteto, uporabljeno za odpiranje datoteke.

- **Data_Doc_InitializationScenario** – Oštevilčenje, ki označuje podrobno vrsto scenarija pri odpiranju datoteke.

- **Data_Doc_IOFlags** – oštevilčenje, ki označuje V-/I-zastavice postopka za odpiranje datoteke, na primer, ali je bila datoteka predpomnjena.

- **Data_Doc_IsCloudCollabEnabled** – Ali je za datoteko omogočeno sodelovanje v oblaku.

- **Data_Doc_IsIncrementalOpen** – Ali je bila datoteka odprta s funkcijo postopnega odpiranja.

- **Data_Doc_IsOcsSupported** – Ali datoteka podpira Officeovo storitev sodelovanja.

- **Data_Doc_IsOpeningOfflineCopy** – Ali je bila datoteka odprta iz predpomnjene kopije brez povezave.

- **Data_Doc_IsPrefetched** – Ali je bila datoteka vnaprej pridobljena, preden se je zagnal postopek odpiranja.

- **Data_Doc_IsSyncBacked** – Ali je na voljo lokalna različica datoteke, ki je sinhronizirana s strežnikom.

- **Data_Doc_Location** – oštevilčenje, ki označuje mesto datoteke, na primer lokalno ali v oblaku.

- **Data_Doc_ReadOnlyReasons** – oštevilčenje, ki označuje razlog datoteke, ki je samo za branje.

- **Data_Doc_ResourceIdHash** – GUID, ki enolično določa ID vira strežnika datoteke.

- **Data_Doc_RtcType** – Oštevilčenje, ki označuje vrsto kanala v realnem času (RTC), ki ga uporablja datoteka.

- **Data_Doc_ServerDocId** – GUID, ki enolično določa ID dokumenta strežnika.

- **Data_Doc_ServerProtocol** – Oštevilčenje, ki označuje protokol strežnika za datoteko v oblaku.

- **Data_Doc_ServerType** – Oštevilčenje, ki označuje vrsto strežnika za datoteko v oblaku.

- **Data_Doc_ServerVersion** – Oštevilčenje, ki označuje različico strežnika za datoteko v oblaku.

- **Data_Doc_SessionId** – celo število, ki se poveča za 1 za vsak postopek odpiranja datoteke v seji.

- **Data_Doc_SharePointServiceContext** – Niz, ki se uporablja za korelacijo odjemalskih in strežniških dnevnikov, po navadi je to neke vrste ID.

- **Data_Doc_SizeInBytes** – Velikost datoteke v bajtih.

- **Data_Doc_SpecialChars** – Oštevilčenje, ki označuje vrsto posebnega znaka, ki ga ima URL datoteke.

- **Data_Doc_UrlHash** – GUID, ki enolično določa URL datoteke.

- **Data_Doc_UsedWrsDataOnOpen** – Ali je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS.

- **Data_Doc_WopiServiceId** – Niz, ki označuje, iz katere storitve je datoteka WOPI (Web Application Interface Protocol).

- **Data_HWModel** – vrednost niza, ki beleži model naprave iPad ali iPhone.

- **Data_InclusiveMeasurements** – Vrednost niza, ki beleži čas, zahtevan za klice funkcij, v obliki zapisa z oznako funkcije ter trajanjem, ki vključuje trajanje klicev podfunkcij.

- **Data_InitializationReason** – oštevilčenje, ki označuje način odpiranja datoteke, na primer iz katerega elementa uporabniškega vmesnika oz. odpiranje sprožila aplikacija.

- **Data_IsDocumentAlreadyOpen** – ne glede na to, ali je datoteka že odprta.

- **Data_IsInterrupted** – ne glede na to, ali je bila odpiranje datoteke prekinjena z odpiranjem programa v ozadje.

- **Data_Measurements** – Vrednost niza, ki beleži čas, zahtevan za klice funkcij, v obliki zapisa z oznako funkcije ter trajanjem, ki ne vključuje trajanje klicev podfunkcij.

- **Data_OpenInPlace** – Ali je treba datoteko kopirati v vsebnik z varnostnimi omejitvami v Officeu, preden jo uporabnik lahko odpre.

- **Data_OpenStartTime** – Čas Unixa, ko je bil zagnan postopek odpiranja datoteke.

- **Data_SilhouetteDuration** – Trajanje upodabljanja za odpiranje datoteke.

- **Data_SourceApplication** – Niz, ki označuje ID snopa izvorne aplikacije, ko je postopek odpiranja datoteke sprožila aplikacija.

- **Data_StopwatchDuration** – Trajanje od začetka do konca dogodka.

- **Data_TimeSplitMeasurements** – Vrednost niza, ki beleži čas, zahtevan za klice funkcij, v obliki zapisa z oznako funkcije, časovnim žigom začetka in trajanjem.

#### <a name="officedocsuifileoperationsopenfilewithreason"></a>Office.DocsUI.FileOperations.OpenFileWithReason 

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek zabeleži, ko se izvede operacija odpiranja datoteke, uporablja pa za razumevanje in določanje prednosti uporabniških izkušenj na podlagi informacij o operaciji odpiranja datoteke, kot so kategorije mest »ServiceType« in mesto v aplikaciji, s katerega je uporabnik zahteval odpiranje datoteke.

Zbrana so sledeča polja:

- **Data_IsCandidateDropboxFile** – to je logična vrednost, ki je zabeležena, če na podlagi pregleda poti datoteke menimo, da je morda iz mape, ki jo sinhronizira Drop Box.

- **Data_IsSignedIn** – označuje, ali je uporabnik pri shranjevanju datoteke vpisan.

- **Data_OpenReason** – razlog za odpiranje je številska vrednost, ki označuje mesto v aplikaciji, s katerega je uporabnik odprl datoteko.

- **Data_ServiceType** – abstraktna številska kategorizacija mesta datoteke, na primer »SharePoint«, »OneDrive«, »Lokalno«, »WOPI« itn., ne pa dejansko mesto datoteke.

#### <a name="officedocsuifileoperationssavetourl"></a>Office.DocsUI.FileOperations.SaveToURL

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek zabeleži, ko se izvede operacija »Shrani kot«, uporablja pa za razumevanje in določanje prednosti uporabniških izkušenj na podlagi informacij o operaciji za datoteko, kot so kategorije mest in prvi štirje znaki pripone.  Operacija »Shrani kot« se izvede vsakič, ko uporabnik ustvari novo datoteko in jo shrani prvič ali ko shrani kopijo obstoječe datoteke na novo mesto.

Zbrana so sledeča polja:

- **Data_FileExtension** – prvi štirje znaki pripone nove datoteke.

- **Data_IsNewFileCreation** – označuje, ali je operacija shranjevanja izvedena za novo datoteko ali kopijo obstoječe datoteke.

- **Data_IsSignedIn** – označuje, ali je uporabnik pri shranjevanju datoteke vpisan.

- **Data_SaveErrorCode** – številska vrednost, ki je nastavljena, če pride do napake, in pomaga prepoznati vrsto napake.

- **Data_SaveErrorDomain** – navaja domeno za SaveErrorCode, kot to določa Apple SaveErrorDomains »so poljubni nizi, ki se uporabljajo za razlikovanje skupin kod«.

- **Data_SaveLocation** – abstraktna kategorizacija mesta datoteke, na primer »SharePoint«, »OneDrive«, »Lokalno«, »WOPI« itn., ne pa dejansko mesto datoteke.

- **Data_SaveOperationType** – številska vrednost, ki jo določa skupina vrednosti NSSaveOperationType družbe Apple.


#### <a name="officedocsuisharinguicloudupsellshown"></a>Office.DocsUI.SharingUI.CloudUpsellShown 

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Ta dogodek zabeleži, ko uporabnik izvede postopek za shranjevanje dokumentov v oblak v okviru prodaje dodatnih izdelkov.  Ti podatki so uporabljeni za boljše razumevanje in določanje prednosti uporabniških izkušenj, povezanih s premikanjem dokumentov na mesta v oblaku.

Zbrana so naslednja polja:

- **Data_FileStyle** – številska vrednost, ki označuje, v kakšnem primeru je bila prikazana izkušnja v okviru prodaje dodatnih izdelkov, npr. na preklopnem stikalu za samodejno shranjevanje ali gumbu »Skupna raba«.

- **Data_FileType** – prvi štirje znaki pripone trenutne datoteke.

- **Data_InDocStage** – logična vrednost, ki označuje, ali je izkušnja v okviru prodaje dodatnih izdelkov prikazana v galeriji dokumentov ali v oknu dokumenta.

- **Data_IsDocumentOpened** – logična vrednost, ki označuje, ali je odprt tudi trenutni dokument, za katerega je prikazana izkušnja v okviru prodaje dodatnih izdelkov.

- **Data_IsDraft** – logična vrednost, ki označuje, ali je bila trenutna datoteka že kdaj shranjena.

- **Data_IsSheetModal** – logična vrednost, ki označuje, ali je bila izkušnja v okviru prodaje dodatnih izdelkov predstavljena modalno.

#### <a name="officedocsuisharinguicloudupsellupload"></a>Office.DocsUI.SharingUI.CloudUpsellUpload 

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Ta dogodek zabeleži, ko uporabnik prenese novo ali lokalno datoteko v oblak in rezultat te operacije.  Ti podatki so uporabljeni za boljše razumevanje in določanje prednosti uporabniških izkušenj, povezanih s premikanjem dokumentov na mesta v oblaku.

Zbrana so naslednja polja:

- **Data_FileStyle** – številska vrednost, ki označuje, v kakšnem primeru je bila prikazana izkušnja v okviru prodaje dodatnih izdelkov, npr. na preklopnem stikalu za samodejno shranjevanje ali gumbu »Skupna raba«.

- **Data_FileType** – prvi štirje znaki pripone trenutne datoteke.

- **Data_InDocStage** – logična vrednost, ki označuje, ali je izkušnja v okviru prodaje dodatnih izdelkov prikazana v galeriji dokumentov ali v oknu dokumenta.

- **Data_IsDefaultServiceLocation** – logična vrednost, ki označuje, ali gre pri izbranem mestu za prenos dokumenta za privzeto mesto.

- **Data_IsDocumentOpened** – logična vrednost, ki označuje, ali je odprt tudi trenutni dokument, za katerega je prikazana izkušnja v okviru prodaje dodatnih izdelkov.

- **Data_IsDraft** – logična vrednost, ki označuje, ali je bila trenutna datoteka že kdaj shranjena.

- **Data_IsSheetModal** – logična vrednost, ki označuje, ali je bila izkušnja v okviru prodaje dodatnih izdelkov predstavljena modalno.

- **Data_LocationServiceType** – abstraktna kategorizacija mesta datoteke, na primer »SharePoint«, »OneDrive«, »Lokalno«, »WOPI« itn., ne pa dejansko mesto datoteke.

- **Data_UploadAction** – vprogramiran niz, ki označuje, ali je pri prenosu v strežnik šlo za operacijo premikanja ali kopiranja.

- **Data_UploadResult** – vprogramiran niz, ki označuje rezultat poskusa prenosa v strežnik, kar med drugim vključuje tudi »Success«, »UserCancelledUpload« in »PreAuthFailed«.

#### <a name="officedocsuisharinguicopylinkoperation"></a>Office.DocsUI.SharingUI.CopyLinkOperation

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Ta dogodek zabeleži, ko uporabnik da dokument v skupno rabo v oblak z ustvarjanjem povezave do dokumenta v oblaku, uporablja pa se za boljše razumevanje in določanje prednosti uporabniških izkušenj na podlagi skupne rabe dokumentov.

Zbrana so sledeča polja:

- **Data_ ServiceType** – abstraktna kategorizacija mesta datoteke, na primer »SharePoint«, »OneDrive«, »Lokalno«, »WOPI« itn., ne pa dejansko mesto datoteke.

- **Data_LinkType** – vprogramiran niz, ki opisuje vrsto izvedene operacije povabila, npr. »ViewOnly« in »ViewAndEdit«.

- **Data_ShareScenario** – vprogramiran niz z opisom mesta v uporabniškem vmesniku aplikacije, s katerega je bila datoteka dana v skupno rabo, kar med drugim vključuje tudi »FileMenu«, »OpenTabShareActionMenu« in »RecentTabShareActionMenu«.

#### <a name="officedocsuisharinguidocsuionedriveshare"></a>Office.DocsUI.SharingUI.DocsUIOneDriveShare 

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Ta dogodek zabeleži, ko uporabnik da dokument v oblaku v skupno rabo z uporabo izkušnje dajanja v skupno rabo OneDrive, uporablja pa se za boljše razumevanje in določanje prednosti uporabniških izkušenj na podlagi skupne rabe dokumentov.

Zbrana so naslednja polja:

- **Data_ODSPShareWebviewShareError** – številska vrednost, ki v primeru pojava napake pri izkušnji skupne rabe omogoča lažje prepoznavanje vzroka napake.

- **Data_ODSPShareWebviewShareGrantAccessResult** – logična vrednost, ki v primeru vrednosti »true« označuje, da je bila operacija poenostavljenega dajanja v skupno rabo uspešno dokončana.

- **Data_ODSPShareWebviewShareSuccessType** – številska vrednost, ki se v primeru uspešno dokončane operacije dajanja v skupno rabo uporablja za ugotavljanje vrste dokončane operacije dajanja v skupno rabo.

- **Data_WebViewInfoResult** – številska vrednost, ki omogoča lažje prepoznavanje vzroka napake, če se uporabniški vmesnik ne naloži. 

- **Data_WebViewLoadTimeInMs** – številska vrednost, ki zabeleži čas, ki je bil potreben za nalaganje spletnega uporabniškega vmesnika.

#### <a name="officedocsuisharinguiinvitepeople"></a>Office.DocsUI.SharingUI.InvitePeople 

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Ta dogodek zabeleži, ko uporabnik povabi osebe v dokument v oblaku, uporablja pa se za boljše razumevanje in določanje prednosti uporabniških izkušenj na podlagi skupne rabe dokumentov.

Zbrana so sledeča polja:

- **Data_ ServiceType** – abstraktna kategorizacija mesta datoteke, na primer »SharePoint«, »OneDrive«, »Lokalno«, »WOPI« itn., ne pa dejansko mesto datoteke.

- **Data_InviteeCount** – skupno število stikov, povabljenih v dokument v okviru enega dejanja povabila.

- **Data_LinkType** – vprogramiran niz, ki opisuje vrsto izvedene operacije povabila, npr. »ViewOnly« in »ViewAndEdit«.

- **Data_MessageLength** – številsko štetje skupnega števila znakov, poslanih v sporočilu s povabilom.

- **Data_ShareScenario** – vprogramiran niz z opisom mesta v uporabniškem vmesniku aplikacije, s katerega je bila datoteka dana v skupno rabo, kar med drugim vključuje tudi »FileMenu«, »OpenTabShareActionMenu« in »RecentTabShareActionMenu«.

#### <a name="officedocsuisharinguisendacopyoperation"></a>Office.DocsUI.SharingUI.SendACopyOperation

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek zabeleži, ko uporabnik pošlje kopijo dokumenta, uporablja pa se za boljše razumevanje in določanje prednosti uporabniških izkušenj na podlagi skupne rabe dokumentov.

Zbrana so naslednja polja:

- **Data_IsHomeTabEnabled** – logična vrednost, ki označuje, ali je zavihek »Osnovno« trenutno na voljo uporabniku.

- **Data_IsRecommendedEnabled** – logična vrednost, ki označuje, ali je izkušnja »Priporočeno« trenutno na voljo uporabniku.

- **Data_OperationType** – številska vrednost, ki označuje, katera vrsta operacije pošiljanja kopije se izvaja, npr. pošiljanje kopije v e-poštnem sporočilu ali pošiljanje kopije z nadzorom skupne rabe v storitvi družbe Apple.

- **Data_ ServiceType** – abstraktna kategorizacija mesta datoteke, na primer »SharePoint«, »OneDrive«, »Lokalno«, »WOPI« itn., ne pa dejansko mesto datoteke.

- **Data_ShareFileType** – vprogramiran niz z opisom vrste predmeta, ki se daje v skupno rabo, kar med drugim vključuje tudi »Dokument«, »PDF« in »Slika«.

- **Data_ShareScenario** – vprogramiran niz z opisom mesta v uporabniškem vmesniku aplikacije, s katerega je bila datoteka dana v skupno rabo, kar med drugim vključuje tudi »FileMenu«, »OpenTabShareActionMenu« in »RecentTabShareActionMenu«.

- **Data_SharingService** – logična vrednost, ki označuje, ali je bila datoteka ustvarjena, ko je uporabnik iskal predlogo.

#### <a name="officedocsuisharinguiupsellshare"></a>Office.DocsUI.SharingUI.UpsellShare 

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Ta dogodek zabeleži, ko uporabnik pri poskusu dajanja dokumenta v skupno rabo izvede postopek za shranjevanje dokumentov v oblak v okviru prodaje dodatnih izdelkov.  Te podatke uporabljamo za boljše razumevanje in določanje prednosti uporabniških izkušenj, povezanih s premikanjem dokumentov na mesta v oblaku.

Zbrana so naslednja polja:

- **Data_FileOperationResult** – številska vrednost, ki označuje, ali je bila operacija uspešna.

- **Data_HostedFromDocStage** – logična vrednost, ki označuje, ali uporabnik izvede postopek za shranjevanje dokumentov v oblak v okviru prodaje dodatnih izdelkov iz izkušnje DocStage ali iz odprtega dokumenta.

- **Data_isLocalCopyOn** – logična vrednost, ki označuje, ali uporabnik obdrži lokalno kopijo dokumenta, ki je predmet prenosa na mesto v oblaku, ali obstoječi dokument premakne na mesto v oblaku.

- **Data_NewFileType** – abstraktna kategorizacija novega mesta datoteke, na primer »SharePoint«, »OneDrive«, »Lokalno«, »WOPI« itn., ne pa dejansko mesto datoteke.

- **Data_OriginalFileType** – abstraktna kategorizacija mesta datoteke, na primer »SharePoint«, »OneDrive«, »Lokalno«, »WOPI« itn., ne pa dejansko mesto datoteke.

- **Data_UploadButtonPressed** – logična vrednost, ki označuje, ali uporabnik trenutni dokument prenese na mesto v oblaku.

- **Data_UploadError** – številska vrednost, ki označuje vrsto napake, do katere pride, če operacija prenosa datoteke v strežnik ne uspe.

- **Data_UpsellAppearsFromDelegate** – logična vrednost, ki označuje, ali je bil pogled prikazan v meniju »Skupna raba«.

#### <a name="officeextensibilitycatalogexchangeprocessentitlement"></a>Office.Extensibility.Catalog.ExchangeProcessEntitlement

Podatki o obdelavi posameznih upravičenosti za najemnika in skrbnika storitve Office 365, ki jima je dodeljen dodatek.

Uporabljamo ga za grafikone (zahteva ga upravljanje skupin) za določanje uspešnosti strank in analiziranje težav strank.

Zbrana so naslednja polja:

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

#### <a name="officefeedeventsinitializing"></a>Office.Feed.Events.Initializing

Ta dogodek se zbere ob inicializaciji vira. Ta dogodek se uporablja za označevanje zagona vira in za diagnosticiranje težav z zanesljivostjo pri zagonu vira.

- **AppInfo.Language** – jezik aplikacije v obliki zapisa jezikovne oznake IETF.

- **AppInfo.Name** – ime uporabljene komponente (vir za Office).

- **AppInfo.Version** – različica aplikacije.

- **clientCorrelationId** – globalni enolični identifikator za sejo aplikacije.

- **clientType** – aplikacija, v kateri se izvaja komponenta.

- **DeviceInfo.Make** – proizvajalec naprave ali ime proizvajalca strojne opreme naprave.

- **DeviceInfo.NetworkProvider** – omrežje ali mobilni operater, kot je »AT&T«.

- **DeviceInfo.NetworkType** – vrsta povezljivosti z omrežjem za uporabljeno napravo, na primer »žična«, »Wi-Fi« ali »WWAN« (podatki/mobilno).

- **DeviceInfo.OsName** – ime operacijskega sistema naprave.

- **DeviceInfo_SDKUid** – enolično prepozna napravo iz vidika telemetrije kompleta za razvoj programske opreme

- **eventId** – identifikator za ime dogodka. 

- **EventInfo.SdkVersion** – različica telemetrije kompleta za razvoj programske opreme, s katero je odjemalec ustvaril dogodek.

- **eventpriority** – številska vrednost prioritete za pošiljanje dogodka.

- **feature** – uporablja se za združevanje različnih dogodkov z enakimi lastnostmi.

- **hostAppRing** – število uporabnikov, katerim je bila posredovana aplikacija.

- **properties** – vsebuje dodatne lastnosti metapodatkov, ki so zbrani za vsak dogodek.
        
    - **ClientTimeStamp** – časovni žig, ko je odjemalec zabeležil dogodek.

- **publicEventName** – javno ime dogodka.  

- **region** – geografsko območje storitve vira, s katerim je povezan uporabnik. 

- **tenantAadObjectId** – globalni enolični identifikator uporabnika za poslovnega najemnika.

- **type** – vrsta zabeleženega dogodka, npr. »Sledenje«, »Napaka«, »Dogodek« ali »QoS«.

- **userAadObjectId** – globalni enolični identifikator uporabnika za Microsoftov račun za podjetja.

- **UserInfo.Id** – globalni enolični identifikator uporabnika za Microsoftov račun za podjetja.

- **UserInfo.IdType** – določa vrsto ID-ja uporabnika. 

- **UserInfo.Language** – jezik uporabnika v obliki zapisa jezikovne oznake IETF.

- **UserInfo.Id** – globalni enolični identifikator uporabnika za Microsoftov potrošniški račun.

- **UserInfo.OMSTenantId** – najemnik, s katerim je povezana uporabnikova naročnina. Omogoča, da razvrstimo težave in določimo, ali je težava razširjena ali omejena na določen nabor uporabnikov oz. določenega najemnika.

- **UserInfo.TimeZone** – uporabnikov časovni pas glede na UTC.

- **UserPuid** – globalni enolični identifikator uporabnika za Microsoftov potrošniški račun.

- **version** – različica odjemalca vira.

#### <a name="officefeedeventsofficefeeddidappear"></a>Office.Feed.Events.OfficeFeedDidAppear

Ta dogodek se zbere ob prikazu vira uporabniku. S tem dogodkom se preveri, ali je bil korak inicializacije vira zaključen in diagnosticira težave z zanesljivostjo pri zagonu vira.

- **AppInfo.Language** – jezik aplikacije v obliki zapisa jezikovne oznake IETF.

- **AppInfo.Name** – ime uporabljene komponente (vir za Office).

- **AppInfo.Version** – različica aplikacije.

- **bridgeWaitingTime** – metrika za diagnosticiranje učinkovitosti delovanja pri upodabljanju vira.

- **clientCorrelationId** – globalni enolični identifikator za sejo aplikacije.

- **clientScenario**-scenarija za različne variante vira.

- **ClientTimeStamp** – časovni žig, ko je odjemalec zabeležil dogodek.

- **clientType** – aplikacija, v kateri se izvaja komponenta.

- **DeviceInfo.Make** – proizvajalec naprave ali ime proizvajalca strojne opreme naprave.

- **DeviceInfo.NetworkProvider** – omrežje ali mobilni operater, kot je »AT&T«.

- **DeviceInfo.NetworkType** – vrsta povezljivosti z omrežjem za uporabljeno napravo, na primer »žična«, »Wi-Fi« ali »WWAN« (podatki/mobilno).

- **DeviceInfo.OsName** – ime operacijskega sistema naprave.

- **DeviceInfo_SDKUid** – enolično prepozna napravo iz vidika telemetrije kompleta za razvoj programske opreme

- **eventId** – identifikator za ime dogodka.

- **EventInfo.SdkVersion** – različica telemetrije kompleta za razvoj programske opreme, s katero je odjemalec ustvaril dogodek.

- **eventpriority** – številska vrednost prioritete za pošiljanje dogodka.

- **feature** – uporablja se za združevanje različnih dogodkov z enakimi lastnostmi.

- **hostAppRing** – število uporabnikov, katerim je bila posredovana aplikacija.

- **properties** – vsebuje dodatne lastnosti metapodatkov, ki so zbrani za vsak dogodek. *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar se bo morda še vedo pojavljalo v starejših graditvah.]*

- **publicEventName** – javno ime dogodka.  

- **region** – geografsko območje storitve vira, s katerim je povezan uporabnik. 

- **renderTime** – metrika za diagnosticiranje učinkovitosti delovanja pri upodabljanju vira.

- **tenantAadObjectId** – globalni enolični identifikator uporabnika za poslovnega najemnika.

- **type** – vrsta zabeleženega dogodka, npr. »Sledenje«, »Napaka«, »Dogodek« ali »QoS«.

- **userAadObjectId** – globalni enolični identifikator uporabnika za Microsoftov račun za podjetja.

- **UserInfo.Id** – globalni enolični identifikator uporabnika za Microsoftov račun za podjetja.

- **UserInfo.IdType** – določa vrsto ID-ja uporabnika. 

- **UserInfo.Language** – jezik uporabnika v obliki zapisa jezikovne oznake IETF.

- **UserInfo.Id** – globalni enolični identifikator uporabnika za Microsoftov potrošniški račun.

- **UserInfo.OMSTenantId** – najemnik, s katerim je povezana uporabnikova naročnina. Omogoča, da razvrstimo težave in določimo, ali je težava razširjena ali omejena na določen nabor uporabnikov oz. določenega najemnika.

- **UserInfo.TimeZone** – uporabnikov časovni pas glede na UTC.

- **UserPuid** – globalni enolični identifikator uporabnika za Microsoftov potrošniški račun.

- **version** – različica odjemalca vira.


#### <a name="officefeedbacksurveyfloodgateclientsurveytracked"></a>Office.Feedback.Survey.FloodgateClient.SurveyTracked

Sledi, ko naprava, ki je upravičena do ankete, zažene aplikacijo. Uporablja se za oceno stanja postopka izbora uporabnikov ankete in zagotavljanje, da je signal, ki se uporablja za analizo težav z odjemalcem in zdravje, deluje pravilno.

Zbrana so naslednja polja:

- **ExpirationTimeUTC** – datum/čas, ko bo Anketa potekla

- **SurveyName** – prikazano je ime ankete

- **SurveyId** – edinstven primerek kampanje

- **UniqueId** – ID za identifikacijo posameznega dela telemetrije

#### <a name="officefeedbacksurveyfloodgateclienttriggermet"></a>Office.Feedback.Survey.FloodgateClient.TriggerMet

Sledi, ko naprava izpolnjuje pogoje za prikaz ankete. Uporablja se za oceno stanja postopka sprožanja ankete in zagotavljanje, da signal, ki se uporablja za analizo težav strank in zdravje, deluje pravilno.

Zbrana so naslednja polja:

- **ExpirationTimeUTC** – datum/čas, ko bo Anketa potekla

- **SurveyName** – prikazano je ime ankete

- **SurveyId** – edinstven primerek kampanje

- **UniqueId** – ID za identifikacijo posameznega dela telemetrije

#### <a name="officefeedbacksurveyfloodgateclientuserselected"></a>Office.Feedback.Survey.FloodgateClient.UserSelected

Sledi, ko je naprava izbrana za anketo. Uporablja se za oceno stanja postopka izbora uporabnikov ankete in zagotavljanje, da je signal, ki se uporablja za analizo težav z odjemalcem in zdravje, deluje pravilno.

Zbrana so naslednja polja:

- **ExpirationTimeUTC** – datum/čas, ko bo Anketa potekla

- **SurveyName** – prikazano je ime ankete

- **SurveyId** – edinstven primerek kampanje

- **UniqueId** – ID za identifikacijo posameznega dela telemetrije

#### <a name="officefeedbacksurveyuiandroid"></a>Office.Feedback.Survey.UI.Android

V napravi s sistemom Android sledi, ko se uporabnik v napravi sporazumeva z uporabniškim pozivnikom» Anketa «in uporabniškega vmesnika za anketo. Uporablja se za oceno stanja postopka sprožanja ankete in zagotavljanje, da signal, ki se uporablja za analizo težav strank in zdravje, deluje pravilno.

Zbrana so naslednja polja:

- **ExpirationTimeUTC** – datum/čas, ko bo Anketa potekla

- **SurveyName** – prikazano je ime ankete

- **SurveyId** – edinstven primerek kampanje

- **UniqueId** – ID za identifikacijo posameznega dela telemetrije

#### <a name="officefeedbacksurveyuiios"></a>Office.Feedback.Survey.UI.IOS

V napravi s sistemom Android sledi, ko se uporabnik v napravi sporazumeva z uporabniškim pozivnikom» Anketa «in uporabniškega vmesnika za anketo. Uporablja se za oceno stanja postopka sprožanja ankete in zagotavljanje, da signal, ki se uporablja za analizo težav strank in zdravje, deluje pravilno.

Zbrana so naslednja polja:

- **ExpirationTimeUTC** – datum/čas, ko bo Anketa potekla

- **SurveyName** – prikazano je ime ankete

- **SurveyId** – edinstven primerek kampanje

- **UniqueId** – ID za identifikacijo posameznega dela telemetrije

#### <a name="officefeedbacksurveyuimac"></a>Office.Feedback.Survey.UI.Mac

V napravi s sistemom Android sledi, ko se uporabnik v napravi sporazumeva z uporabniškim pozivnikom» Anketa «in uporabniškega vmesnika za anketo. Uporablja se za oceno stanja postopka sprožanja ankete in zagotavljanje, da signal, ki se uporablja za analizo težav strank in zdravje, deluje pravilno.

Zbrana so naslednja polja:

- **ExpirationTimeUTC** – datum/čas, ko bo Anketa potekla

- **SurveyName** – prikazano je ime ankete

- **SurveyId** – edinstven primerek kampanje

- **UniqueId** – ID za identifikacijo posameznega dela telemetrije

#### <a name="officefeedbacksurveyuiwin32"></a>Office.Feedback.Survey.UI.Win32

V napravi s sistemom Win32 sledi, ko se uporabnik v napravi sporazumeva s pozivnikom »Anketa« in z uporabniškim vmesnikom »Anketa«. Uporablja se za oceno stanja postopka sprožanja ankete in zagotavljanje, da signal, ki se uporablja za analizo težav strank in zdravje, deluje pravilno.

Zbrana so naslednja polja:

- **ExpirationTimeUTC** – datum/čas, ko bo Anketa potekla

- **SurveyName** – prikazano je ime ankete

- **SurveyId** – edinstven primerek kampanje

- **UniqueId** – ID za identifikacijo posameznega dela telemetrije

#### <a name="officefeedbacksurveyuiwin32toast"></a>Office.Feedback.Survey.UI.Win32.Toast

Sledi, ko je prikazan pozivnik ankete. Uporablja se za oceno stanja popravka postopka ankete ter za zagotavljanje, da signal, ki se uporablja za analizo težav in zdravje strank, deluje pravilno.

Zbrana so naslednja polja:

- **ExpirationTimeUTC** – datum/čas, ko bo Anketa potekla

- **SurveyName** – prikazano je ime ankete

- **SurveyId** – edinstven primerek kampanje

- **UniqueId** – ID za identifikacijo posameznega dela telemetrije

#### <a name="officefileiocsiccachedfilecsiloadfilebasic"></a>Office.FileIO.CSI.CCachedFileCsiLoadFileBasic

S tem dogodkom lahko prepoznamo, ali je bila datoteka uspešno odprta v plasti FIO. Uporabljamo ga za zagotavljanje ustreznosti delovanja funkcij in nadzor.

Zbrana so ta polja:

  - **Activity.Group** – Oznaka, ki omogoča združevanje nabora dogodkov nadzora za upravljanje uspešnega delovanja.

  - **Activity.IsHVA** – Zastavica, ki označuje, da je dogodek ključen za zagotavljanje uspešnega delovanja za uporabnika.

  - **Data.AsyncOpen** – Zastavica, ki označuje odpiranje vsebine, prejete potem, ko je bilo glavno telo dokumenta že odprto.

  - **Data.CacheFileId** – Povezava do telemetrije predpomnilnika Officeovih dokumentov za omogočanje analize posledic težav s predpomnilnikom na uporabniško izkušnjo.
 
  - **Data. CFREnabled** – označuje, da je za sejo omogočena možnost CacheFileRuntime.

  - **Data. CFRFailure** – označuje, da je CacheFileRuntime naletel na napako.
  
  - **Data.CoauthStatus** – Poroča o stanju sodelovanja v dokumentu ob odpiranju.

  - **Data.CountOfMultiRoundTripsDownload** – Število vrnitev v strežnik, ki se uporablja za odpravljanje težav z učinkovitostjo delovanja in omrežjem.

  - **Data.CountOfMultiRoundTripsUpload** – Število vrnitev v strežnik, ki se uporablja za odpravljanje težav z učinkovitostjo delovanja in omrežjem.

  - **Data.DialogId** – To polje je nastavljeno, če je bilo pogovorno okno za UI prikazano med odpiranjem, in označuje, da je uporabnik prejel opozorilno sporočilo.

  - **Data.DidFallbackToDAV** – To polje je nastavljeno, če je bil dokument odprt s starejšim protokolom za prenos datotek.

  - **Data.Doc.AccessMode** – Dokument je samo za branje/ga je mogoče urejati.

  - **Data.Doc.AssistedReadingReasons** – To polje je nastavljeno, če je za dokument izbrana elektronska zaščita podatkov.

  - **Data.Doc.AsyncOpenKind –** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

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

  - **Data. VersionType** – označuje, za katero vrsto različice gre pri trenutni operaciji odpiranja.

  - **Data.WopiServiceId** – Zastarelo; zamenjalo ga je polje »Data\_Doc\_WopiServiceId«.

#### <a name="officefileiocsiccachedfilecsisavefilebasic"></a>Office.FileIO.CSI.CCachedFileCsiSaveFileBasic

S tem dogodkom lahko prepoznamo, ali je bila datoteka uspešno shranjena v plasti FIO. Uporabljamo ga za zagotavljanje ustreznosti delovanja funkcij in nadzor.

Zbrana so ta polja:

  - **Activity.Group** – Oznaka, ki omogoča združevanje nabora dogodkov nadzora za upravljanje uspešnega delovanja.

  - **Activity.IsHVA** – Zastavica, ki označuje, da je dogodek ključen za zagotavljanje uspešnega delovanja za uporabnika.

  - **Data.AsyncOpen** – Zastavica, ki označuje, da je bil odprt dokument z vsebino, prejeto potem, ko je bilo glavno telo dokumenta že odprto.

  - **Data.BaseDownloadTriggered** – Diagnostika sledenja spremembam, vključno s podatki, da je bila zahtevana osnovna različica dokumenta.

  - **Data.BlockAutoUploadReasons** – kode vzroka za blokirano stanje nalaganja (na primer samodejno shranjevanje je vklopljeno, dokument je v stanju prehoda)

  - **Data.BlockUploadDueToFailedSaveAsOverExisting** – Nalaganje je blokirano, saj bi bil vnovičen poskus neuspešen.

  - **Data.CacheFileId** – Povezava do telemetrije predpomnilnika Officeovih dokumentov za omogočanje analize posledic težav s predpomnilnikom na uporabniško izkušnjo.

  - **Data.ChartType** – Zastarelo.

  - **Data.CoauthStatus** – Poroča o stanju sodelovanja v dokumentu ob shranjevanju.

  - **Data.CoauthUpdatesContext** – Poroča o kontekstu (spajanje/postopno odpiranje).

  - **Data.CountOfMultiRoundTripsDownload** – Število vrnitev v strežnik, ki se uporablja za odpravljanje težav z učinkovitostjo delovanja in omrežjem.

  - **Data.CountOfMultiRoundTripsUpload** – Število vrnitev v strežnik, ki se uporablja za odpravljanje težav z učinkovitostjo delovanja in omrežjem.
  
  - **Data. CFREnabled** – označuje, da je za sejo omogočena možnost CacheFileRuntime.

  - **Data. CFRFailure** – označuje, da je CacheFileRuntime naletel na napako.

  - **Data.DialogChoice** – Zabeleži izbrane možnosti v katerih koli pogovornih oknih napak.

  - **Data.DialogId** – Zabeleži ID pogovornega okna katerih koli pogovornih oknih napak, prikazanih med shranjevanjem.

  - **Data.Dmc.IsOcsSupported** – Zastarelo.

  - **Data.Doc.AccessMode** – Dokument je samo za branje.

  - **Data.Doc.AssistedReadingReasons** – To polje je nastavljeno, če je za dokument izbrana elektronska zaščita podatkov.

  - **Data.Doc.AsyncOpenKind –** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

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

#### <a name="officefirstrunappleactivationresult"></a>Office.FirstRun.Apple.ActivationResult

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za nadzorovanje ustreznosti stanja postopka aktiviranja aplikacije. Te podatke zbiramo, da bi ugotovili rezultat aktiviranja naročnine na Office 365 skupaj s postopkom, ki se uporablja za aktiviranje (uporabniška izkušnja prvega zagona, postopek znotraj aplikacije, nakup itd.).

Zbrana so naslednja polja:

- **Data_ActivationStatusCollectionTime** – časovni žig

- **Data_ActivationStatusError** – koda napake pri aktivaciji.

- **Data_ActivationStatusFlowType** – številska vrednost, ki označuje vrsto postopka aktiviranja

#### <a name="officefirstrunappleactivationstatus"></a>Office.FirstRun.Apple.ActivationStatus

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za ugotavljanje rezultata aktiviranja naročnine na Office 365 skupaj s postopkom, ki se uporablja za aktiviranje (FRE, postopek znotraj aplikacije, nakup itd.). Zbiramo podatke, ki vsebujejo vrsto aktiviranja, vrsto postopka (FRE/DocStage/nakup) in ID storitve licenciranja za Office.

Zbrana so naslednja polja:

- **Data_ActivationTypeCollectionTime** – časovni žig

- **Data_ActivationTypeFlowType** – številska vrednost, ki označuje vrsto postopka aktiviranja

- **Data_ActivationTypeOLSLicense** – identifikator licence

- **Data_ActivationTypeStatus** – koda stanja aktiviranja.

#### <a name="officefirstrunapplefirstruncomplete"></a>Office.FirstRun.Apple.FirstRunComplete

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Ta dogodek nam pove, ali uporabnik uporablja brezplačno storitev z omejitvami, kakšna vrsta postopka se izvaja (FRE/DocStage/nakup) in za kakšno vrsto identitete gre (MSA/OrgID). Ta dogodek uporabljamo za ugotavljanje morebitnega dokončanja uporabniške izkušnje prvega zagona (FRE) in vrste identitete, ki je uporabljena za vpis (MSA/OrgID).

Zbrana so naslednja polja:

- **Data_FirstRunCompletedCollectionTime** – časovni žig, ki zabeleži čas, ko je bil postopek dokončan

- **Data_FirstRunCompletedFlowType** – koda, ki označuje vrsto uporabniškega postopka, ki je bil dokončan 

- **Data_FirstRunCompletedFreemiumStatus** – koda, ki predstavlja stanje dokončanja uporabniškega postopka pri uporabi brezplačne storitve z omejitvami

- **Data_FirstRunCompletedIdentityType** – vrsta identitete uporabnika, ki je dokončal postopek

#### <a name="officefirstrunapplefirstrunstart"></a>Office.FirstRun.Apple.FirstRunStart

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Ta dogodek nam pove, ali je uporabnik zagnal uporabniško izkušnjo prvega zagona in kakšna je vrsta postopka, ki se izvaja (FRE/DocStage/nakup). Ta dogodek uporabljamo, da bi ugotovili, ali je bila uporabniška izkušnja prvega zagona (FRE) uspešno zagnana.

Zbrana so naslednja polja:

- **Data_FirstRunStartedCollectionTime** – časovni žig, ki zabeleži čas, ko je bil postopek dokončan

- **Data_FirstRunStartedFlowType** – koda, ki označuje vrsto uporabniškega postopka, ki je bil dokončan 

#### <a name="officefirstrunapplefirstrunstartedandcompleted"></a>Office.FirstRun.Apple.FirstRunStartedAndCompleted

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Ta dogodek nam pove, ali uporabnik uporablja brezplačno storitev z omejitvami, kakšna vrsta postopka se izvaja (FRE/DocStage/nakup) in za kakšno vrsto identitete gre (MSA/OrgID). Ta dogodek uporabljamo, da ugotovimo ustreznost stanja in učinkovitost postopka uporabniške izkušnje prvega zagona (FRE).

Zbrana so naslednja polja:

- **Data_FirstRunCompletedCollectionTime** – časovni žig, ki zabeleži čas, ko je bil postopek dokončan

- **Data_FirstRunCompletedFlowType** – koda, ki označuje vrsto uporabniškega postopka, ki je bil dokončan  

- **Data_FirstRunCompletedFreemiumStatus** – koda, ki predstavlja stanje dokončanja uporabniškega postopka pri uporabi brezplačne storitve z omejitvami

- **Data_FirstRunCompletedIdentityType** – vrsta identitete uporabnika, ki je dokončal postopek

- **Data_FirstRunStartedCollectionTime** – časovni žig, ki zabeleži čas, ko je bil postopek zagnan

- **Data_FirstRunStartedFlowType** – koda, ki označuje vrsto uporabniškega postopka, ki je bil zagnan

#### <a name="officefirstrunappleinapppurchaseactivationfail"></a>Office.FirstRun.Apple.InAppPurchaseActivationFail

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za nadzorovanje ustreznosti stanja postopka aktiviranja aplikacije. Te podatke zbiramo, da bi ugotovili rezultat aktiviranja nakupa znotraj aplikacije skupaj s postopkom, ki se uporablja za aktiviranje (uporabniška izkušnja prvega zagona, postopek znotraj aplikacije, nakup ipd.). 

Zbrana so naslednja polja:

- **Data_ActivationFailCollectionTime** – časovni žig, ki zabeleži čas, ko je prišlo do napake pri aktivaciji 

- **Data_ActivationFailFlowType** – koda, ki označuje vrsto uporabniškega postopka, ki je bil uporabljen

- **Data_AssoicatedSuccessfullyCollectionTime** – časovni žig, ki zabeleži čas, ko je prišlo do povezave 

- **Data_AssoicatedSuccessfullyFlowType** – koda, ki označuje vrsto uporabniškega postopka, ki je bil uporabljen

#### <a name="officefirstrunappleinapppurchaseactivationsuccess"></a>Office.FirstRun.Apple.InAppPurchaseActivationSuccess

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za nadzorovanje ustreznosti stanja postopka aktiviranja aplikacije. Te podatke zbiramo, da bi ugotovili rezultat aktiviranja nakupa znotraj aplikacije skupaj s postopkom, ki se uporablja za aktiviranje (uporabniška izkušnja prvega zagona, postopek znotraj aplikacije, nakup ipd.). 

Zbrana so naslednja polja:

- **Data_ActivatedSuccessfullyCollectionTime** – časovni žig, ki zabeleži čas, ko je prišlo do aktiviranja 

- **Data_ActivatedSuccessfullyFlowType** – koda, ki označuje vrsto uporabniškega postopka, ki je bil uporabljen

- **Data_AssoicatedSuccessfullyCollectionTime** – časovni žig, ki zabeleži čas, ko je prišlo do povezave 

- **Data_AssoicatedSuccessfullyFlowType** – koda, ki označuje vrsto uporabniškega postopka, ki je bil uporabljen

#### <a name="officefirstrunappleinapppurchaseassociationfailed"></a>Office.FirstRun.Apple.InAppPurchaseAssociationFailed

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za nadzorovanje ustreznosti stanja postopka aktiviranja aplikacije. Te podatke zbiramo, da bi ugotovili rezultat aktiviranja nakupa znotraj aplikacije skupaj s postopkom, ki se uporablja za aktiviranje (uporabniška izkušnja prvega zagona, postopek znotraj aplikacije, nakup ipd.). 

Zbrana so naslednja polja:

- **Data_AppChargedSuccessfullyCollectionTime** – časovni žig, ki zabeleži čas, ko je bila izvedena bremenitev za nakup

- **Data_AppChargedSuccessfullyFlowType** – koda, ki označuje vrsto uporabniškega postopka, ki je bil uporabljen

- **Data_AssoicationFailedCollectionTime** – časovni žig, ki zabeleži čas, ko je prišlo do neuspešne povezave aplikacije

- **Data_AssoicationFailedFlowType** – koda, ki označuje vrsto uporabniškega postopka, ki je bil uporabljen

- **Data_AssoicationFailedResult** – koda, ki označuje vrsto zaznane napake

#### <a name="officefirstrunappleinapppurchaseassociationsuccess"></a>Office.FirstRun.Apple.InAppPurchaseAssociationSuccess

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za nadzorovanje ustreznosti stanja postopka aktiviranja aplikacije. Te podatke zbiramo, da bi ugotovili rezultat aktiviranja nakupa znotraj aplikacije skupaj s postopkom, ki se uporablja za aktiviranje (uporabniška izkušnja prvega zagona, postopek znotraj aplikacije, nakup ipd.). 

Zbrana so naslednja polja:

- **Data_AppChargedSuccessfullyCollectionTime** – časovni žig, ki zabeleži čas, ko je bila izvedena bremenitev za nakup

- **Data_AppChargedSuccessfullyFlowType** – koda, ki označuje vrsto uporabniškega postopka, ki je bil uporabljen

- **Data_AssoicatedSuccessfullyCollectionTime** – časovni žig, ki zabeleži čas, ko je prišlo do neuspešne povezave aplikacije

- **Data_AssoicatedSuccessfullyFlowType** – koda, ki označuje vrsto uporabniškega postopka, ki je bil uporabljen

#### <a name="officefirstrunappleinapppurchasefailures"></a>Office.FirstRun.Apple.InAppPurchaseFailures

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za nadzorovanje ustreznosti stanja postopka aktiviranja aplikacije. Zbiramo podatke o rezultatu postopka nakupa znotraj aplikacije.

Zbrana so naslednja polja:

- **Data_AppStoreFailureFlowType** – koda, ki označuje vrsto uporabniškega postopka, ki je bil uporabljen

- **Data_AppStoreFailureResult** – pomeni, da je bila zaznana napaka

- **Data_CancelRequestFlowType** – koda, ki označuje vrsto uporabniškega postopka, ki je bil uporabljen

- **Data_EventId** – koda, ki označuje vrsto zaznane napake

#### <a name="officefirstrunappleinapppurchasesattempted"></a>Office.FirstRun.Apple.InAppPurchasesAttempted

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za nadzorovanje ustreznosti stanja postopka nakupa znotraj aplikacije. Te podatke zbiramo, da bi sledili poskusom nakupov znotraj aplikacije in vrsti inventarne številke, ki je predmet nakupa (mesečna naročnina/letna naročnina/Home/Personal).

Zbrana so naslednja polja:

- **Data_EventId** – koda, ki označuje vrsto zaznanega rezultata

- **Data_PurchasedClickedOfferType** – vrsta inventarne številke, ki je predmet poskusa nakupa

- **Data_PurchaseSuccessfulFlowType** – koda, ki označuje vrsto uporabniškega postopka, ki je bil uporabljen

#### <a name="officefirstrunappleinapprestoreattempted"></a>Office.FirstRun.Apple.InAppRestoreAttempted

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za nadzorovanje ustreznosti stanja postopka nakupa znotraj aplikacije. Te podatke zbiramo, da bi sledili poskusom obnovitve znotraj aplikacije

Zbrana so naslednja polja:

- **Data_EventId** – koda, ki označuje vrsto rezultata poskusa

- **Data_RestoreAttemptFlowType** – koda, ki označuje vrsto uporabniškega postopka, ki je bil uporabljen

#### <a name="officefirstrunappleinapprestoreattemptfailed"></a>Office.FirstRun.Apple.InAppRestoreAttemptFailed

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za nadzorovanje ustreznosti stanja postopka nakupa znotraj aplikacije. Te podatke zbiramo, da bi sledili poskusom obnovitev znotraj aplikacije ter njihovim povezanim postopkom in napakam.

Zbrana so naslednja polja:

- **Data_RestoreButtonFlowType** – koda, ki označuje vrsto uporabniškega postopka, ki je bil uporabljen

- **Data_RestoredFailedPaymentCancelledFlowType** – koda, ki označuje vrsto postopka preklica plačila, ki je bil uporabljen

- **Data_RestoredFailedUnKnownFlowType** – označuje, ali je bil poskus neuspešen zaradi uporabe nepričakovanega uporabniškega postopka

- **Data_RestoredFailedUnKnownResult** – označuje, ali je bil poskus neuspešen zaradi neznanih razlogov

#### <a name="officefirstrunapplemacfirstruncompleted"></a>Office.FirstRun.Apple.MacFirstRunCompleted

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Ta dogodek nam pove, da je uporabnik izvedel uporabniško izkušnjo prvega zagona. Ta dogodek uporabljamo, da bi ugotovili, ali je bil postopek uporabniške izkušnje prvega zagona (FRE) uspešno dokončan.

Zbrana so naslednja polja:

- **Data_FirstRunCollectionTime** – časovni žig, ki zabeleži čas, ko je bil postopek dokončan.

#### <a name="officefirstrunapplemacwxpfirstrunstarted"></a>Office.FirstRun.Apple.MacWXPFirstRunStarted

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Ta dogodek nam pove, da je uporabnik odprl uporabniško izkušnjo prvega zagona. Ta dogodek uporabljamo, da bi ugotovili, ali je bil postopek za uporabniško izkušnjo prvega zagona (FRE) uspešno zagnan.

Zbrana so naslednja polja:

- **Data_FirstRunPanelName** – ime podokna, iz katerega je bila zagnana uporabniška izkušnja

#### <a name="officelenslenssdkcloudconnectorlaunch"></a>Office.Lens.LensSdk.CloudConnectorLaunch

Ta dogodek se zbere, ko uporabnik obreže sliko in tapne gumb »Potrdi« pri končni izbiri slike, ki se bo uporabila za optično prepoznavanje znakov.     
Gre za zapis, ki ga zahteva uporabnik, za storitev, saj v storitvi ni voljo opravilo preslikave od uporabnika v storitev. Polje UserId je zahtevano za izpolnjevanje zahtev Splošne uredbe o varstvu podatkov, saj storitev ni neposredno izpostavljena uporabnikom, temveč prek odjemalcev, in za določanje skupnega števila oseb, ki uporablja storitev. Storitvi pomaga spremljati število uporabnikov, ki uporabljajo izdelek, in prepoznavati spremembe trendov, poiskati pomoč in odpraviti težave z izdelkom.

Zbrana so naslednja polja:

- **CallType** – niz za prepoznavanje, ali je bil klic API sinhron oz. nesinhron.

- **CloudConnectorRequestId** – niz, ki se uporablja za prepoznavanje zahteve storitve, ki je bila izvedena za namen pretvorbe slik prek storitve. 

- **CloudConnectorTarget** – niz, ki potrjuje, katero vrsto pretvorbe bo izvedla storitev na slikah, na primer pretvorba v PDF, Docx, besedilo itd.

- **CustomerId** – niz, ki se uporablja za prepoznavanje uporabnika, ki je lastnik obdelanih slik.

- **CustomerType** – niz, ki se uporablja za prepoznavanje uporabnika kot uporabnika podjetja ali posameznega uporabnika. To razlikovanje vpliva na število slik (kvota), ki jih odjemalec lahko pretvori hkrati. 

- **RelationId** – niz, ki določa povezavo med aplikacijo Lens in storitvijo, ki se uporablja za obdelavo datotek.


#### <a name="officelenslenssdkcloudconnectoruploaderror"></a>Office.Lens.LensSdk.CloudConnectorUploadError

Ko v oknu »Slika v tabelo« uporabnik tapne »Daj v skupno rabo«, »Kopiraj« ali »Odpri«, so popravki v tabeli, ki jih je opravil uporabnik, dani v skupno rabo s storitvijo za namene izboljšanja optičnega prepoznavanja znakov. Ta dogodek se zbere pri odzivu na napako te storitve in vsebuje pomembne identifikatorje za odpravljanje različnih težav v storitvi. 

Zbrana so naslednja polja:

- **CloudConnectorRequestId** – identifikator niza za povezovanje posla storitve trenutne zahteve storitve, za katero so bili v skupno rabo dani podatki o izboljšavah.

- **CorrelationId** – niz, ki vsebuje identifikatorja trenutnega primerka za posel storitve.

- **Reason** – niz, ki vsebuje kodo napake in opis napake.

- **TargetType** – niz, ki prepozna končno točko v storitvi.

- **TaskType** – niz, ki prepozna namen klica storitve.


#### <a name="officelenslenssdkcloudconnectoruploadsuccess"></a>Office.Lens.LensSdk.CloudConnectorUploadSuccess

Ko v oknu »Slika v tabelo« uporabnik tapne »Daj v skupno rabo«, »Kopiraj« ali »Odpri«, so popravki v tabeli, ki jih je opravil uporabnik, dani v skupno rabo s storitvijo za namene izboljšanja optičnega prepoznavanja znakov. Ta dogodek se zbere pri uspešnem odzivu te storitve in vsebuje pomembne identifikatorje za odpravljanje težav v procesu. Prav tako pomaga analizirati uporabo lijaka za izboljšanje storitve.

Zbrana so naslednja polja:

- **CloudConnectorRequestId** – identifikator niza za povezovanje posla storitve trenutne zahteve storitve, za katero so bili v skupno rabo dani podatki o izboljšavah.

- **CorrelationId** – niz, ki vsebuje identifikatorja trenutnega primerka za posel storitve.

- **TargetType** – niz, ki prepozna končno točko v storitvi.

- **TaskType** – niz, ki prepozna namen klica storitve.


#### <a name="officelenslenssdkpermission"></a>Office.Lens.LensSdk.Permission

Dovoljenja so občutljiva funkcija, saj brez jih uporabnik ne more preizkusiti funkcij aplikacije Lens. Dovoljenja spremljamo z namenom razumevanja uporabniških navad pri omogočanju/preklicu dovoljenj. Te dogodke zberemo, ko uporabnik prikaže poljubno pogovorno okno dovoljenja v naši aplikaciji. Izboljšave funkcij za pomoč uporabnikom pri razumevanju, zakaj so dovoljenja tako pomembna, prepoznamo glede na trende uporabnikov pri sprejemanju in zavračanju dovoljenj.

Zbrana so naslednja polja:

- **Data_action** – vsebuje vrednosti, kot so »CameraPermissionAllowed» (ali Denied), »StoragePermissionGranted« (ali Denied), s katerimi ugotovimo, ali je uporabnik sprejel oz. zavrnil dovoljenja za shrambo in kamero.

- **Data_Action** – to polje nam je v pomoč pri razumevanju, katera vrsta dovoljenja je bila zahtevana od uporabnika, npr. kamera ali shramba

- **Data_status** – vsebuje vrednosti, kot so »Allowed«, »Denied« in »DeniedForever«, s katerimi ugotovimo, ali je uporabnik sprejel oz. zavrnil dovoljenja za shrambo in kamero.


#### <a name="officelenslenssdksavemedia"></a>Office.Lens.LensSdk.SaveMedia

Ta dogodek je pozvan, ko uporabnik klikne gumb »Dokončaj« in shrani slike v sistem Android ter iOS. Beleži uporabnike, ki so shranili slike v naši aplikaciji, ter tako izberi raven uporabnikove aktivnosti.

Zbrana so sledeča polja (velja samo za naprave s sistemom Android):

- **Data_FileSizeAfterCleanUp** – velikost datoteke, potem ko jo je počistila aplikacija, za razumevanje, kolikšna stopnja stiskanja je bila dosežena po čiščenju.

- **Data_FileSizeAfterSave** – velikost datoteke, potem ko jo shranil uporabnik, za razumevanje, kolikšna stopnja stiskanja je bila dosežena po shranjevanju.

- **Data_FileSizeBeforeCleanUp** – velikost datoteke, preden jo je počistila aplikacija, za razumevanje zajete velikosti datoteke

- **Data_Filter** – filter, uporabljen na sliki.

- **Data_ImageHeightAfterCleanUp** – višina slike, potem ko jo je počistila aplikacija.

- **Data_ImageHeightBeforeCleanUp** – višina slike, preden jo je počistila aplikacija.

- **Data_ImageWidthAfterCleanUp** – širina slike, potem ko jo je počistila aplikacija.

- **Data_ImageWidthBeforeCleanUp** – širina slike, preden jo je počistila aplikacija.

- **Data_MediaId** – identifikator za slike za pomoč pri sledenju uspešne operacije.

- **Data_ProcessMode** – aktiviran način uporabnika pri shranjevanju slike.

- **Data_Source** – določa vir slike, na primer zajem s kamero, uvoz iz galerije itd. 

Zbrana so sledeča polja (velja samo za naprave s sistemom iOS):

- **Data_filter** – filter, uporabljen na sliki. 

- **Data_imageDPI** – zmanjšanje kakovosti slike pri shranjevanju slikovne datoteke

- **Data_imageSize** – velikost slike, potem ko jo je uporabnik shranil

- **Data_mediaId** – identifikator za slike za pomoč pri sledenju uspešne operacije.

- **Data_mode** – aktiviran način uporabnika pri shranjevanju slike.

- **Data_sizeinPixel** – velikost slike v slikovnih pikah

- **Data_source** – določa vir slike, na primer zajem s kamero, uvoz iz galerije itd. 


#### <a name="officelenslenssdkserviceidmapping"></a>Office.Lens.LensSdk.ServiceIDMapping

Ta dogodek se zbere pri uspešnem prenosu slike v storitev. Ponazarja, da bo storitev izvedla en ali več poslov za obdelavo slike, in vsebuje ustrezne ID-je za pomoč pri odpravljanju težav pri procesu. Prav tako pomaga analizirati uporabo različnih funkcij storitve.

Zbrana so naslednja polja:

- **CloudConnectorRequestId** – niz, ki se uporablja za prepoznavanje zahteve storitve, ki je bila izvedena za namen pretvorbe slik prek storitve.

- **I2DserviceProcessID** – niz, ki opredeli posel storitev, ki izvaja določeno podzahtevo 


#### <a name="officeiospaywallpaywallpresented"></a>Office.iOS.Paywall.Paywall.Presented

Ta telemetrijo kritične uporabe je zbrana, ko je uporabniku prikazan nadzor paywall, ki se uporablja za razumevanje nakupne izkušnje v aplikaciji za uporabnika in optimiziranje enakega stanja za prihodnje različice.

Zbrana so sledeča polja:

- **Točka vnosa** -string – gumb/tok, iz katerega je bil prikazan paywall. Npr. gumb »premija za nadgradnjo« ali »prvi zagonski tok«.

- **isFRE** -logična vrednost – ali prikazujemo prvo izkušnjo z zagonom ali navadni uporabniški vmesnik?

#### <a name="officeiospaywallpaywallstats"></a>Office.iOS.Paywall.Paywall.Stats

Ta metapodatki na osnovi seje se zberejo, ko je uporabnik uporabniškega vmesnika za paywall prikazan uporabniku, trajanju interakcije in o tem, ali je bil nakup izveden in je uspel ali ni uspel.  Podatki so uporabljeni za razumevanje uporabe in stanja celotne izkušnje plačevanja in odpravljanja napak, optimiziranje in odpravljanje težav z nakupno izkušnjo v aplikaciji v prihodnjih različicah.

Zbrana so sledeča polja:

- **entryPoint** – niz – gumb/potek za prikaz plačilnega sistema Npr. gumb »premijska nadgradnja« ali »prvi zagonski tok«.

- **isFRE** -logična vrednost – ali prikazujemo prvo izkušnjo z zagonom ali navadni uporabniški vmesnik?

- **stanje** nizov – izstop stanja paywall. Kot» zagnano «,» paymentDone «,» provisionFailed «

- **userDuration** – dvojno trajanje v milisekundah, ki jih je uporabnik porabil za paywall

#### <a name="officeiospaywallskuchoosermorebenefitsstats"></a>Office.iOS.Paywall.SKUChooser.MoreBenefits.Stats

V tem primeru so zbrane funkcije in aplikacije, ki jih uporabnik razširi iz» Oglejte si več prednosti «, in trajanje porabljenega časa.  Podatki so uporabljeni za razumevanje funkcije» Oglejte si vse prednosti «in še naprej Optimizirajte izkušnjo v prihodnjih različicah.

Zbrana so sledeča polja:

- **appsExpanded** -niz, ločen z vejico, seznam storitev/aplikacij, za katere je bila razširjena ugodnost.

- **ID shrambe, ki je na voljo v** nizu, za katerega uporabnik prikazuje več prednosti, ki jih ponuja

- **userDuration** – dvojno trajanje v milisekundah, ki jih je uporabnik porabil za zaslon z ugodnostmi.

#### <a name="officeiospaywallskuchooserstats"></a>Office.iOS.Paywall.SKUChooser.Stats

Ta telemetrijo uporabe je zbrana, da si ogledate, kako je uporabnik vstopil v izbirnik INVENTARne številke, koliko časa porabi uporabnik na zaslonu izbirnika INVENTARne številke in zakaj so izstopili izbirnika INVENTARne številke.  Podatki so uporabljeni za razumevanje uporabe izbirnika INVENTARja in optimiziranje nakupa izkušenj v aplikacijah v prihodnjih različicah.

Zbrana so sledeča polja:

- **entryPoint** – niz – gumb/potek za prikaz plačilnega sistema Npr. gumb »premijska nadgradnja« ali »prvi zagonski tok«.

- **exitReason** -string – izstop zaradi izbirnika INVENTARne številke. Kot» BuyButton «,» CloseButton

- **isFRE** -logična vrednost – ali prikazujemo prvo izkušnjo z zagonom ali navadni uporabniški vmesnik?

- **userDuration** – dvojno trajanje v milisekundah, ki jih je uporabnik porabil za izbirnik INVENTARne številke


#### <a name="officelivepersonacardconfigurationsetaction"></a>Office.LivePersonaCard.ConfigurationSetAction

Dejavnosti beležimo, ko uporabnik zažene aplikacijo za nalaganje kartice osebe in želi odpreti kartico osebe v živo.  S temi podatki določimo, ali je bila kartica naložena pravilno. 

Zbrana so sledeča polja: 

- **Data.accountType** – Ali uporabnik pripada organizaciji oziroma je domač uporabnik

- **Data.appContextId** – Naključno ustvarjen ID, ki se uporablja za prepoznavanje različnih računov v isti aplikaciji

- **Data.AppInfo.Name** – ime uporabljene storitve (kartica profila)

- **Data.AppInfo_Id** – ime gostiteljske aplikacije

- **Data.AppInfo_Version** – različica gostiteljske aplikacije

- **Data.cardCorrelationId** – globalni enolični identifikator za kartico osebe

- **Data.cardPersonaCorrelationId** – globalni enolični identifikator za določeno osebo, ki je prikazan na kartici

- **Data.clientCorrelationId** – globalni enolični identifikator za sejo aplikacije

- **Data.clientType** – Vrsta naprave, v kateri se izvaja aplikacija

- **Data.contextType** – Iz katere aplikacije je bila kartica zagnana

- **Data.ecsConfigIds** – Identifikatorji različic za funkcije, omogočene na kartici

- **Data.ecsTagId** – ID oznake za funkcije

- **Data.eventId** – identifikator imena dogodka, na primer »LivePersonaCardRenderedAction«

- **Data.eventpriority** – številska vrednost prioritete za pošiljanje dogodka.

- **Data.feature** – Uporablja se za združevanje različnih dogodkov z enakimi lastnostmi (kartica profila)

- **Data.flights** – Funkcije, omogočene na kartici

- **Data.fromCache** – Ali so bili podatki pridobljeni iz pomnilnika

- **Data.hasFinePointer** – Ali ima naprava vgrajeno podporo za kazalca miške

- **Data.hasHoverEvents** – Ali ima naprava vgrajeno podporo za premikanje kazalca miške nad elemente

- **Data.immersiveProfileCorrelationId** – Globalni enolični identifikator za sejo razširjenega pogleda profila

- **Data.offlineResolved** – Ali so bili podatki pridobljeni brez povezave

- **Data.OTelJS.Version**– Različica programa OTel Logger

- **Data.personaCorrelationId** – Globalni enolični identifikator enolične osebe v seji

- **Data.properties** – Dodatni metapodatki, ki so zbrani za vsak dogodek, kot je prikazano v tem primeru: *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar se bo morda še vedo pojavljalo v starejših graditvah.]*

  - **cardCorrelationId** – Dvojnik Data.appContextId zgoraj
  - **cardPersonaCorrelationId**  – Dvojnik Data.cardCorrelationId zgoraj
  - **ClientTimeStamp** – čas v aplikaciji, ko je bil dogodek zabeležen
  - **consumerCorrelationId**  – Dvojnik Data.clientCorrelationId zgoraj

  - **externalAppSessionCorrelationId** – Globalni enolični identifikator za aplikacijo za prepoznavanje vseh kartic osebe, odprtih v istem podsrečanju

- **Data.region** – Geografsko območje zaledne storitve Kartica profila stika, s katerim je povezan uporabnik

- **Data.tenantAadObjectId** – najemnik, na katerega je vezana naročnina uporabnika. Omogoča, da razvrstimo težave in določimo, ali je težava razširjena ali omejena na določen nabor uporabnikov oz. določenega najemnika

- **Data.type** – vrsta zabeleženega dogodka, npr. Sledenje, Napaka, Dogodek

- **Data.userAadObjectId** – globalni enolični identifikator uporabnika za Microsoftov račun za podjetja (dvojnik Data.UserInfo.Id)

- **Data.UserInfo.Id** – globalni enolični identifikator uporabnika za Microsoftov račun za podjetja

- **Data.UserInfo.Id** – globalni enolični identifikator uporabnika za Microsoftov potrošniški račun

- **Data.UserInfo.OMSTenantId** – najemnik, s katerim je povezana uporabnikova naročnina. Omogoča, da razvrstimo težave in določimo, ali je težava razširjena ali omejena na določen nabor uporabnikov oz. določenega najemnika

- **Data.userPuid** – globalni enolični identifikator uporabnika za Microsoftov potrošniški račun (dvojnik za »Data.UserInfo.Msald«)

- **Data.version** – različica storitve (kartica profila)

- **Data.workloadCulture** – nabor podatkov o kulturi v gostiteljski aplikaciji

- **DeviceInfo_Id** – globalni enolični identifikator naprave za napravo

- **DeviceInfo_Make** – blagovna znamka operacijskega sistema

- **DeviceInfo_Model** – model naprave

- **DeviceInfo_OsName** – ime operacijskega sistema naprave

- **DeviceInfo_OsVersion** – različica operacijskega sistema

- **DeviceInfo_SDKUid** – Enolično prepozna napravo iz vidika telemetrije kompleta za razvoj programske opreme

#### <a name="officelivepersonacarduseractionsclosedexpandedpersonacard"></a>Office. LivePersonaCard. UserActions. ClosedExpandedPersonaCard

Prijavljeno, ko uporabnik zapre razširjeno kartico persona. Uporablja se za opazovanje kritičnih anomalij v stopnjah napake pri zaprtju kartice » Live persona«.

Zbrana so naslednja polja:

- **AppInfo_Id** – ime gostiteljske aplikacije

- **AppInfo_Version** – različica gostiteljske aplikacije

- **Data.appContextId** – Naključno ustvarjen ID, ki se uporablja za prepoznavanje različnih računov v isti aplikaciji

- **Data.AppInfo.Name** – ime storitve v uporabi (kartica profila)

- **Data.cardCorrelationId** – globalni enolični identifikator za kartico osebe

- **Data.cardPersonaCorrelationId** – globalni enolični identifikator za določeno osebo, ki je prikazan na kartici

- **Data.clientCorrelationId** – globalni enolični identifikator za sejo aplikacije

- **Data. clientType** – vrsta naprave, v kateri se izvaja aplikacija, na primer »Outlook_Win32«

- **Data.eventId** – identifikator imena dogodka, na primer »LivePersonaCardRenderedAction«

- **Data. exportName** – ime dogodka uporabnika v berljivi obliki zapisa, na primer. »ClosedExpandedPersonaCard«

- **Data.exportType** – Kategorija dogodka za izvoz zahteve uredbe GDPR

- **Data.externalAppSessionCorrelationId** – Globalni enolični identifikator za aplikacijo za prepoznavanje vseh kartic osebe, odprtih v istem podsrečanju

- **Data.feature** – Uporablja se za združevanje različnih dogodkov z enakimi lastnostmi (kartica profila)

- **Data.immersiveProfileCorrelationId** – Globalni enolični identifikator za sejo razširjenega pogleda profila

- **Data.OTelJS.Version**– Različica programa OTel Logger

- **Data.personaCorrelationId** – Globalni enolični identifikator enolične osebe v seji

- **Data.properties** – Dodatni metapodatki, ki so zbrani za vsak dogodek, kot je prikazano v tem primeru: *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar se bo morda še vedo pojavljalo v starejših graditvah.]*

   - **cardCorrelationId** – Dvojnik Data.appContextId zgoraj 
   - **cardPersonaCorrelationId**  – Dvojnik Data.cardCorrelationId zgoraj
   - **ClientTimeStamp** časa, da se je dogodek zgodil v času časa, ko je bil čas za UNIX
   - **consumerCorrelationId**  – Dvojnik Data.clientCorrelationId zgoraj 

- **Data.region** – Geografsko območje zaledne storitve Kartica profila stika, s katerim je povezan uporabnik

- **Data.tenantAadObjectId** – najemnik, na katerega je vezana naročnina uporabnika. Omogoča, da razvrstimo težave in določimo, ali je težava razširjena ali omejena na določen nabor uporabnikov oz. določenega najemnika

- **Data.type** – vrsta zabeleženega dogodka, npr. Sledenje, Napaka, Dogodek

- **Data.userAadObjectId** – globalni enolični identifikator uporabnika za Microsoftov račun za podjetja (dvojnik Data.UserInfo.Id)

- **Data.UserInfo.Id** – globalni enolični identifikator uporabnika za Microsoftov račun za podjetja 

- **Data.UserInfo.Id** – globalni enolični identifikator uporabnika za Microsoftov potrošniški račun

- **Data.UserInfo.OMSTenantId** – najemnik, s katerim je povezana uporabnikova naročnina. Omogoča, da razvrstimo težave in določimo, ali je težava razširjena ali omejena na določen nabor uporabnikov oz. določenega najemnika.

- **Data.userPuid** – globalni enolični identifikator uporabnika za Microsoftov potrošniški račun (dvojnik Data.UserInfo.Msald)

- **Data.version** – različica storitve (kartica profila)

- **DeviceInfo_Id** – globalni enolični identifikator naprave za napravo

- **DeviceInfo_Make** – blagovna znamka operacijskega sistema

- **DeviceInfo_Model** – model naprave

- **DeviceInfo. NetworkCost** – Označuje strošek omrežja/vrsto (merjeno, merjeno nad zgornjo mejo ipd.)

- **DeviceInfo_OsName** – ime operacijskega sistema naprave

- **DeviceInfo_OsVersion** – različica operacijskega sistema

- **PipelineInfo.ClientCountry** – koda države pošiljatelja, ki temelji na naslovu IP, ki ga je razrešila stranka


#### <a name="officelivepersonacarduseractionsclosedpersonacard"></a>Office.LivePersonaCard.UserActions.ClosedPersonaCard

Prijavljen, ko uporabnik zapre kartico osebe.  S temi podatki določimo, ali je bila kartica pravilno zaprta. 

Zbrana so sledeča polja: 

- **BatchId** – globalni enolični identifikator, če je bil izveden nabor zahtev

- **Data.appContextId** – Naključno ustvarjen ID, ki se uporablja za prepoznavanje različnih računov v isti aplikaciji

- **Data.AppInfo.Name** – ime uporabljene storitve (kartica profila)

- **Data.AppInfo_Id** – ime gostiteljske aplikacije

- **Data.AppInfo_Version** – različica gostiteljske aplikacije

- **Data.cardCorrelationId** – globalni enolični identifikator za kartico osebe

- **Data.cardPersonaCorrelationId** – globalni enolični identifikator za določeno osebo, ki je prikazan na kartici

- **Data.clientCorrelationId** – globalni enolični identifikator za sejo aplikacije

- **Data.clientType** – Vrsta naprave, v kateri se izvaja aplikacija

- **Data.eventId** – identifikator imena dogodka, na primer »LivePersonaCardRenderedAction«

- **Data.externalAppSessionCorrelationId** – Globalni enolični identifikator za aplikacijo za prepoznavanje vseh kartic osebe, odprtih v istem podsrečanju.

- **Data.feature** – Uporablja se za združevanje različnih dogodkov z enakimi lastnostmi (kartica profila)

- **Data.immersiveProfileCorrelationId** – Globalni enolični identifikator za sejo razširjenega pogleda profila

- **Data.OTelJS.Version**– Različica programa OTel Logger

- **Data.personaCorrelationId** – Globalni enolični identifikator enolične osebe v seji

- **Data.properties** – Dodatni metapodatki, ki so zbrani za vsak dogodek, kot je prikazano v tem primeru: *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar se bo morda še vedo pojavljalo v starejših graditvah.]*

  - **ClientTimeStamp** – Čas v aplikaciji, ko je bil dogodek zabeležen
  - **cardCorrelationId** – Dvojnik Data.appContextId zgoraj
  - **cardPersonaCorrelationId**  – Dvojnik Data.cardCorrelationId zgoraj
  - **consumerCorrelationId**  – Dvojnik Data.clientCorrelationId zgoraj

- **Data.region** – Geografsko območje zaledne storitve Kartica profila stika, s katerim je povezan uporabnik

- **Data.tenantAadObjectId** – najemnik, na katerega je vezana naročnina uporabnika. Omogoča, da razvrstimo težave in določimo, ali je težava razširjena ali omejena na določen nabor uporabnikov oz. določenega najemnika

- **Data.type** – vrsta zabeleženega dogodka, npr. Sledenje, Napaka, Dogodek

- **Data.userAadObjectId** – globalni enolični identifikator uporabnika za Microsoftov račun za podjetja (dvojnik Data.UserInfo.Id)

- **Data.UserInfo.Id** – globalni enolični identifikator uporabnika za Microsoftov račun za podjetja

- **Data.UserInfo.Id** – globalni enolični identifikator uporabnika za Microsoftov potrošniški račun

- **Data.UserInfo.OMSTenantId** – najemnik, s katerim je povezana uporabnikova naročnina. Omogoča, da razvrstimo težave in določimo, ali je težava razširjena ali omejena na določen nabor uporabnikov oz. določenega najemnika

- **Data.userPuid** – globalni enolični identifikator uporabnika za Microsoftov potrošniški račun (dvojnik Data.UserInfo.Msald)

- **Data.version** – različica storitve (kartica profila)

- **Data_hostAppRing** – prstan za uvedbo kartice osebe

- **Event_ReceivedTime** – Čas, ko je bil zabeležen dogodek v storitvi

#### <a name="officelivepersonacarduseractionsopenedexpandedpersonacard"></a>Office.LivePersonaCard.UserActions.OpenedExpandedPersonaCard

Aktivnosti se beležijo, ko uporabnik odpre razširjeno kartico osebe. Uporablja se za opazovanje kritičnih anomalij v stopnjah napake pri uvajanju kartice osebe Live Persona Card.

Zbrana so sledeča polja:

- **AppInfo_Id** – ime gostiteljske aplikacije

- **AppInfo_Version** – različica gostiteljske aplikacije

- **Data.appContextId** – Naključno ustvarjen ID, ki se uporablja za prepoznavanje različnih računov v isti aplikaciji

- **Data.AppInfo.Name** – ime storitve v uporabi (kartica profila)

- **Data.cardCorrelationId** – globalni enolični identifikator za kartico osebe

- **Data.cardPersonaCorrelationId** – globalni enolični identifikator za določeno osebo, ki je prikazan na kartici

- **Data.clientCorrelationId** – Globalni enolični identifikator za sejo aplikacije

- **Data.clientScenario** – se uporablja za prepoznavanje funkcije v aplikaciji, v kateri je bila odprta kartica osebe

- **Data.clientType** – Vrsta naprave, v kateri se izvaja aplikacija

- **Data.eventId** – identifikator imena dogodka, na primer »LivePersonaCardRenderedAction«

- **Data.externalAppSessionCorrelationId** – globalni enolični identifikator za aplikacijo za prepoznavanje vseh kartic osebe, odprtih v istem podsrečanju.

- **Data.exportName** – človeško berljivo ime dogodka dejanja uporabnika, npr. »OpenedPersonaCard«

- **Data.exportType** – Kategorija dogodka za izvoz zahteve uredbe GDPR

- **Data.feature** – Uporablja se za združevanje različnih dogodkov z enakimi lastnostmi (kartica profila)

- **Data.hasPersonalInsightRing** – Vpogledi v Office ali LinkedIn so lahko na voljo za uporabnika

- **Data.hostAppRing** – Krog, s katerim je bila aplikacija distribuirana

- **Data.immersiveProfileCorrelationId** – Globalni enolični identifikator za sejo razširjenega pogleda profila

- **Data.OTelJS.Version**– Različica programa OTel Logger

- **Data.personaCorrelationId** – Globalni enolični identifikator enolične osebe v seji

- **Data.properties** – Dodatni metapodatki, ki so zbrani za vsak dogodek, kot je prikazano v tem primeru: *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar se bo morda še vedo pojavljalo v starejših graditvah.]*

  - **cardCorrelationId** – Dvojnik Data.appContextId zgoraj 
  - **cardPersonaCorrelationId**  – Dvojnik Data.cardCorrelationId zgoraj
  - **consumerCorrelationId**  – Dvojnik Data.clientCorrelationId zgoraj 

- **Data.region** – Geografsko območje zaledne storitve Kartica profila stika, s katerim je povezan uporabnik

- **Data.section** – Aktivni razdelek razširjene kartice

- **Data.tenantAadObjectId** – Najemnik, na katerega je vezana naročnina uporabnika. Omogoča, da razvrstimo težave in določimo, ali je težava razširjena ali omejena na določen nabor uporabnikov oz. določenega najemnika

- **Data.type** – vrsta zabeleženega dogodka, npr. Sledenje, Napaka, Dogodek

- **Data.userAadObjectId** – globalni enolični identifikator uporabnika za Microsoftov račun za podjetja (dvojnik Data.UserInfo.Id)

- **Data.UserInfo.Id** – globalni enolični identifikator uporabnika za Microsoftov račun za podjetja 

- **Data.UserInfo.Id** – globalni enolični identifikator uporabnika za Microsoftov potrošniški račun

- **Data.UserInfo.OMSTenantId** – najemnik, s katerim je povezana uporabnikova naročnina. Omogoča, da razvrstimo težave in določimo, ali je težava razširjena ali omejena na določen nabor uporabnikov oz. določenega najemnika

- **Data.userPuid** – globalni enolični identifikator uporabnika za Microsoftov potrošniški račun (dvojnik Data.UserInfo.Msald)

- **Data.version** – različica storitve (kartica profila)

- **DeviceInfo_Id** – globalni enolični identifikator naprave za napravo

- **DeviceInfo_Make** – blagovna znamka operacijskega sistema

- **DeviceInfo_Model** – model naprave

- **DeviceInfo_OsName** – ime operacijskega sistema naprave

- **DeviceInfo_OsVersion** – različica operacijskega sistema

- **DeviceInfo_SDKUid** – enolično prepozna napravo iz vidika telemetrije kompleta za razvoj programske opreme

- **NetworkCost** – Označuje strošek/vrsto omrežja (omejen prenos podatkov, omejeno nad zgornjo mejo itd.)

- **NetworkCountry** – koda države pošiljatelja, ki temelji na neočiščenem naslovu IP odjemalca


#### <a name="officelivepersonacarduseractionsopenedpersonacard"></a>Office.LivePersonaCard.UserActions.OpenedPersonaCard

Prijavljen, ko uporabnik odpre Kartico osebe. Uporablja se za opazovanje kritičnih anomalij v stopnjah napake pri uvajanju kartice osebe Live Persona Card.

Zbrana so sledeča polja:

- **Data.appContextId** – naključno ustvarjen ID, ki se uporablja za prepoznavanje različnih računov v isti aplikaciji

- **Data.AppInfo.Name** – Ime storitve v uporabi (kartica profila)

- **Data.bandwidthEstimateMbps** – Učinkovita ocena pasovne širine v Mb/s

- **Data.cardCorrelationId** – Globalni enolični identifikator za kartico osebe

- **Data.cardPersonaCorrelationId** – globalni enolični identifikator za določeno osebo, ki je prikazan na kartici

- **Data.clientCorrelationId** – globalni enolični identifikator za sejo aplikacije

- **Data.clientType** – vrsto naprave, v kateri se izvaja aplikacija.

- **Data.eventId** – identifikator imena dogodka, na primer »LivePersonaCardRenderedAction«

- **Data.exportName** – človeško berljivo ime dogodka dejanja uporabnika, npr. »OpenedPersonaCard«

- **Data.exportType** – Kategorija dogodka za izvoz zahteve uredbe GDPR

- **Data.externalAppSessionCorrelationId** – Globalni enolični identifikator za aplikacijo za prepoznavanje vseh kartic osebe, odprtih v istem podsrečanju

- **Data.feature** – Uporablja se za združevanje različnih dogodkov z enakimi lastnostmi (kartica profila)

- **Data.hasPersonalInsightRing** – Vpogledi v Office ali LinkedIn so lahko na voljo za uporabnika

- **Data.hostAppRing** – Krog, s katerim je bila aplikacija distribuirana

- **Data.immersiveProfileCorrelationId** – Globalni enolični identifikator za sejo razširjenega pogleda profila

- **Data.OTelJS.Version**– Različica programa OTel Logger

- **Data.personaCorrelationId** – Globalni enolični identifikator enolične osebe v seji

- **Data.properties** – Dodatni metapodatki, ki so zbrani za vsak dogodek, kot je prikazano v tem primeru. *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar se bo morda še vedo pojavljalo v starejših graditvah.]*

    - **cardCorrelationId** – Dvojnik Data.appContextId zgoraj 
    - **cardPersonaCorrelationId**  – Dvojnik Data.cardCorrelationId zgoraj
    - **consumerCorrelationId**  – Dvojnik Data.clientCorrelationId zgoraj 
    - **networkEffectiveType** – učinkovita vrsta omrežne povezave, na primer »slow-2g online«, ki določi, ali je uporabnik povezan z internetom v času, ko prikazuje kartico osebe
    - **networkType** – Vrsta omrežne povezljivosti naprave, ki je v uporabi
    - **roundTripEstimateMs** – Ocenjena učinkovita povratna povezava trenutne povezave v milisekundah

- **Data.region** – geografsko območje zaledne storitve Kartica profila stika, s katerim je povezan uporabnik

- **Data.tenantAadObjectId** – najemnik, na katerega je vezana naročnina uporabnika. Omogoča, da razvrstimo težave in določimo, ali je težava razširjena ali omejena na določen nabor uporabnikov oz. določenega najemnika

- **Data.type** – vrsta zabeleženega dogodka, npr. Sledenje, Napaka, Dogodek

- **Data.userAadObjectId** – globalni enolični identifikator uporabnika za Microsoftov račun za podjetja (dvojnik Data.UserInfo.Id)

- **Data.UserInfo.Id** – globalni enolični identifikator uporabnika za Microsoftov račun za podjetja 

- **Data.UserInfo.Id** – globalni enolični identifikator uporabnika za Microsoftov potrošniški račun

- **Data.UserInfo.OMSTenantId** – najemnik, s katerim je povezana uporabnikova naročnina. Omogoča, da razvrstimo težave in določimo, ali je težava razširjena ali omejena na določen nabor uporabnikov oz. določenega najemnika

- **Data.userPuid** – globalni enolični identifikator uporabnika za Microsoftov potrošniški račun (dvojnik Data.UserInfo.Msald)

- **Data.version** – različica storitve (kartica profila)

- **Data.viewType** – Določa vrsto prikazane kartice profila

- **Data.wasOpenedAsCompactCard** – Uporablja se za identifikacijo, ali je bila kartica prvotno odprta kot strnjeni pogled

- **NetworkCost** – Označuje strošek/vrsto omrežja (omejen prenos podatkov, omejeno nad zgornjo mejo itd.)

- **NetworkCountry** – koda države pošiljatelja, ki temelji na neočiščenem naslovu IP odjemalca.

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

#### <a name="officeofficemobilepdfviewerpdffileopenmeasurements"></a>Office.OfficeMobile.PdfViewer.PdfFileOpenMeasurements

Ta dogodek je izbran za aplikacijo Office; posname izvajanje postopka odpiranja datoteke. Zbrali smo te podatke, da bi zagotovili dobro učinkovitost delovanja za vse datoteke, ki se odpre v aplikaciji. 

Zbrana so naslednja polja:

- **Data_Doc_ActivationFQDN** – ime domene aplikacije ponudnika za scenarij aktivacije datoteke (prijavljene so le informacije o aplikaciji prve stranke).

- **Data_Doc_CreateTelemetryReason** – vzrok telemetrije za ustvarjanje dokumenta PDF (na primer: ustvari iz pregleda z ukazi »slika v PDF«, »dokument v PDF« itd.)

- **Data_Doc_DownloadDurationms** čas za prenos datoteke v oblaku PDF.

- **Data_Doc_DownloadEndTime** – časovni žig za konec prenosa datoteke v oblaku.

- **Data_Doc_DownloadStartTime** – časovni žig za začetek prenosa datoteke v oblaku.

- **Data_Doc_FileOpSessionID** – enolični ID seje dokumenta.

- **Data_Doc_Location** – lokacija datoteke (lokalni disk, ODSP, iCloud, aplikacije tretjih oseb, wopi)

- **Data_Doc_OpenCompletionTime** – časovni žig za konec odprtega delovanja datoteke PDF.

- **Data_Doc_OpenDurationms** čas za odpiranje datoteke PDF v milisekundah.

- **Data_Doc_OpenStartTime** – časovni žig za začetek odprtega delovanja datoteke PDF.

- **Data_Doc_TelemetryReason** – telemetrija vzroka za odprt dogodek (na primer: odpiranje iz MRU ali brskanje, aktivacija datoteke, aktivacija protokolov itd.).

- **Doc_RenderDurationms** časa, da postane datoteka PDF


#### <a name="officeofficemobilepdfviewerpdffileoperations-on-android"></a>Office.OfficeMobile.PdfViewer.PdfFileOperations (v sistemu Android)

Dogodek je zbran za Officeovo aplikacijo za Android. Zabeleži, ko pride do dogodka odpiranja, zapiranja ali shranjevanja dokumenta .pdf, uporablja pa za razumevanje in določanje prednosti uporabniških izkušenj na podlagi informacij o delu z datotekami .pdf. S tem dogodkom poskrbimo, da postopki odpiranja, zapiranja in shranjevanja dokumentov .pdf delujejo v skladu s pričakovanji, hkrati pa lahko izboljšujemo učinkovitost dela z datotekami .pdf.

Zbrana so sledeča polja:

- **Data_Doc_FileOpSessionID** – enolični ID za sejo dokumenta

- **Data_ErrorCode** – napaka, do katere pride zaradi neuspelih postopkov odpiranja datotek/neuspelih prenosov/preklica prenosov

- **Data_ErrorMessage** – relevantna koda sporočilo-napaka

- **Data_FailureReason** – če pride do napake pri odpiranju, to oštevilčenje določa vzrok za napako.

- **Data_FileGUID** – globalni identifikator za datoteko, ki je ustvarjena slučajno

- **Data_FileLocation**– lokacija datoteke, na primer: lokalno, ODSP, iCloud, itd.

- **Data_FileOpenEntryPoint** – vhodna točka za odpiranje datoteke

- **Data_FileSize** – velikost datoteke, v kateri se izvaja postopek

- **Data_NetworkRequestErrorResponse** – odziv z napako omrežja, ki ustreza kodi napake.

- **Data_NetworkRequestStage** – prikaz napake v primeru prenosa datotek pdf v oblak.

- **Data_OpenMode** – v katerem načinu je bil odprt dokument PDF, na primer: 0: način pogleda, 2: način podpisa

- **Data_PageCount** – število strani v datoteki PDF

- **Data_PasswordProtected** – označevalnik, ki označuje, ali je datoteka zaščitena z geslom ali ne.

- **Data_ProviderApp** – trenutni ponudnik aplikacije le v primeru aktivacije datoteke 

- **Data_ReadOnly** – označevalnik, ki označuje, ali je datoteka samo za branje ali ne.

- **Data_Result** – stanje postopka, ki se izvaja, na primer: true:success, false:failure

- **Data_Type** – vrsta postopka, uporabljenega za datoteko (odpri, zapri ali shrani) 

#### <a name="officeofficemobilepdfviewerpdffileoperations-on-ios"></a>Office.OfficeMobile.PdfViewer.PdfFileOperations (v sistemu iOS)

Dogodek se zbira za aplikacijo Office za iOS. Zabeleži, ko pride do dogodka odpiranja, zapiranja ali shranjevanja dokumenta .pdf, uporablja pa za razumevanje in določanje prednosti uporabniških izkušenj na podlagi informacij o delu z datotekami .pdf. S tem dogodkom poskrbimo, da postopki odpiranja, zapiranja in shranjevanja dokumentov .pdf delujejo v skladu s pričakovanji, hkrati pa lahko izboljšujemo učinkovitost dela z datotekami .pdf. 

- **Data_Doc_FileOpSessionID** – enolični ID za sejo dokumenta 

- **Data_ErrorCode** – napaka, do katere pride zaradi neuspelih postopkov odpiranja datotek/neuspelih prenosov/preklica prenosov 

- **Data_ErrorMessage** – relevantna koda sporočilo-napaka 

- **Data_FailureReason** – če pride do napake pri odpiranju, to oštevilčenje določa vzrok za napako. 

- **Data_FileGUID** – globalni identifikator za datoteko, ki je ustvarjena slučajno

- **Data_FileLocation**– lokacija datoteke (lokalno, ODSP, iCloud, itd.) 

- **Data_FileOpenEntryPoint** – vhodna točka za odpiranje datoteke 

- **Data_FileSize** – velikost datoteke, v kateri se izvaja postopek 

- **Data_OpenMode** – v katerem načinu je bil odprt dokument PDF (0: način pogleda, 2: način podpisa) 

- **Data_PageCount** – število strani v datoteki PDF

- **Data_PasswordProtected** – označevalnik, ki označuje, ali je datoteka zaščitena z geslom ali ne. 

- **Data_ProviderApp** – trenutni ponudnik aplikacije le v primeru aktivacije datoteke 

- **Data_ReadOnly** – označevalnik, ki označuje, ali je datoteka samo za branje ali ne.

- **Data_Result** – stanje postopka, ki se izvaja (true:success, false:failure) 

- **Data_Type** – vrsta postopka, uporabljenega za datoteko (odpri, zapri ali shrani)


#### <a name="officeonenoteandroidappnavigationnavigationuistatechanged"></a>Office.OneNote.Android.App.Navigation.NavigationUIStateChanged

*[Ta dogodek je bil prej imenovan OneNote.App.Navigation.NavigationUIStateChanged.]*

Ta dogodek zbira kritični signal, ki uporabnikom storitve OneNote zagotovi uspešno krmarjenje po aplikaciji.  Telemetrija se uporablja za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in ustreznosti stanja storitve. 

Zbrana so sledeča polja: 

- **IS_SPANNED** – označuje, ali je aplikacija v razpetem načinu. To je posebej zabeleženo za zložljive naprave.

- **NEW_STATE** – označuje stanje aplikacije tik po krmarjenju

- **OLD_STATE** – označuje stanje aplikacije tik pred krmarjenjem

#### <a name="officeonenoteandroidcanvaspageopened"></a>Office.OneNote.Android.Canvas.PageOpened

*[Ta dogodek je bil prej imenovan OneNote.Canvas.PageOpened.]*

Signal za beleženje časa odpiranja strani.  S to telemetrijo nadziramo, zaznavamo in odpravljamo morebitne težave pri odpiranju strani v OneNotu.

Zbrana so naslednja polja: 

- **JOT_ID** – Predmet odprte strani.

- **TIME_TAKEN_IN_MS** – Čas, zahtevan za odpiranje strani.

#### <a name="officeonenoteandroidcapturenewnotenewnotetaken"></a>Office.OneNote.Android.Capture.NewNote.NewNoteTaken

*[Ta dogodek je bil prej imenovan OneNote.Capture.NewNote.NewNoteTaken.]*

Ta signal se uporablja za pravilno nastavitev in uporabo zvezkov, po tem, ko se je uporabnik vpisal v aplikacijo OneNote za sistem Android, ter zagotovitev uspešnega ustvarjanja novega zapiska.  Uporablja se za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in stanja storitve.

Zbrana so sledeča polja:

- Nobeno

#### <a name="officeonenoteandroidlenssdkofficelenslaunched"></a>Office.OneNote.Android.LensSDK.OfficeLensLaunched

*[Ta dogodek je bil prej imenovan OneNote.LensSDK.OfficeLensLaunched.]*

Ta dogodek zbere kritični signal, ki omogoča pravilen zagon aplikacije OfficeLens.  Telemetrija se uporablja za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in ustreznosti stanja storitve. 

Zbrana so sledeča polja: 

- **CAPTURE_MODE** – označuje, v katerem načinu je bila zagnana aplikacija OfficeLens.  Načini so lahko privzeto, urejanje, hitro vstavljanje ali uvoz videoposnetka.

- **ERROR_CODE** – označuje kodo napake zagona, če je prišlo do napake med zagonom.

- **IMAGE_COUNT** – označuje število posnetih slik

- **LAUNCH_REASON** – označuje tok, v katerem je bila zagnana aplikacija OfficeLens. Zagnana je lahko prek zaklenjenega zaslona, kamere, možnosti galerije v samolepljivih listkih, prek platna v aplikaciji OneNote itd.

#### <a name="officeonenoteandroidmessagebarmessagebarclicked"></a>Office.OneNote.Android.MessageBar.MessageBarClicked

*[Ta dogodek je bil prej imenovan OneNote.MessageBar.MessageBarClicked.]*

Signal, ki se uporablja za ponazoritev morebitnih težav, nastalih pri uporabi vrstice s sporočili.  S to telemetrijo nadziramo, zaznavamo in odpravljamo morebitne težave pri interakciji vrstice s sporočili

Zbrana so naslednja polja: 

- **Message_Bar_Type** – Se prikaže, če uporabnik uporablja staro ali novo vrstico s sporočili.

- **Message_Type** – Vrne ID sporočila o napaki.

#### <a name="officeonenoteandroidstickynotesnotecreated"></a>Office.OneNote.Android.StickyNotes.NoteCreated
 
Kritični signal, ki se uporablja za nadzor zmogljivosti, kjer uporabniki Samolepljivih listkov lahko ustvarjajo zapiske v aplikaciji.   Telemetrija se uporablja za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in stanja storitve. Če uporabniki ne morejo ustvariti zapiska, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so sledeča polja:

- **IsExportable** – zastavica, ki označuje, ali je bil dogodek rezultat dejanja uporabnika ali ne. Mora biti nastavljen na vrednost true, ker je NoteCreated dejanje, ki ga je sprožil uporabnik.

- **NoteLocalId** – razlikovalni enolični identifikator, ki je dodeljen zapisku v času, ko uporabnik ustvari zapisek v aplikaciji.

- **StickyNotes – SDKVersion** – številka različice, ki označuje različico Lepljivih zapiskov, ki jo uporablja uporabnik. Omogoča, da določimo, v katerih različicah izdelka je prišlo do težave ter te težave razvrstimo po pomembnosti.


#### <a name="officeonenoteandroidstickynotesnoteviewed"></a>Office.OneNote.Android.StickyNotes.NoteViewed

Kritični signal, ki se uporablja za nadzor zmogljivosti, kjer si uporabniki Samolepljivih listkov lahko ogledujejo zapiske v aplikaciji.  Telemetrija se uporablja za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in stanja storitve. Če si uporabniki ne morejo ogledati svojih zapiskov, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so sledeča polja:

- **HasImages** – zastavica, ki označuje, so v ogledanem zapisku shranjene slike.

- **IsExportable** – zastavica, ki označuje, ali je bil dogodek rezultat dejanja uporabnika ali ne. Mora biti nastavljen na vrednost true, ker je NoteViewed dejanje, ki ga je sprožil uporabnik.

- **NoteLocalId** – razpoznavni enolični identifikator, ki je dodeljen zapisku v času, ko uporabnik ustvari zapisek v programu.

- **StickyNotes – SDKVersion** – številka različice, ki označuje različico Lepljivih zapiskov, ki jo uporablja uporabnik. Omogoča, da določimo, v katerih različicah izdelka je prišlo do težave ter te težave razvrstimo po pomembnosti.


#### <a name="officeonenotecanvasinkinkstrokelogger"></a>Office.OneNote.Canvas.Ink.InkStrokeLogger 

S tem dogodkom zaznavamo in diagnosticiramo napako, na katero uporabnik pogosto naleti pri uporabi funkcije rokopisa.  Uporabili ga bomo pri določanju najprimernejšega načina reševanja te napake. 

Zbrana so naslednja polja:

- **CurrentCanvasZoomFactor** – Trenutni dejavnik povečave platna.

- **CurrentNotebook** – Identifikator trenutno aktivnega zvezka.

- **CurrentPage** – Identifikator trenutno aktivne strani.

- **CurrentSection** – Identifikator trenutno aktivnega odseka.

- **DefaultCanvasZoomFactor** – Privzeti dejavnik povečave platna.

- **InkStrokeCount** – Skupno število potez rokopisa od zadnjega dnevnika.

- **InkStrokeWithLayerInkEffect** – Število potez rokopisa z učinkom črnila na plasteh od zadnjega dnevnika.

- **InkStrokeWithoutPressureCount** – Število potez rokopisa brez pritiska od zadnjega dnevnika.

- **InkStrokeWithPencilInkEffect** – Število potez rokopisa z učinkom črnila svinčnika od zadnjega dnevnika.

- **InkStrokeWithTilt** – Število potez rokopisa z nagibom od zadnjega dnevnika.

#### <a name="officeonenotenavigationcreatepage"></a>Office.OneNote.Navigation.CreatePage

Kritični signal, uporabljen za spremljanje možnosti uporabnikov OneNota za ustvarjanje strani v OneNotu.  Telemetrija, uporabljena za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in ustreznosti stanja storitve. Če uporabniki ne morejo ustvariti strani, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so sledeča polja:

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

Zbrana so sledeča polja

- **NotebookID** – enolični identifikator zvezka.

- **SectionID** – enolični identifikator ustvarjenega odseka.

- **Sprožilec** – označuje vstopno točko, na kateri se začne dejanje ustvarjanja odseka.

- **TriggerInfo** – označuje dodatne informacije, povezane s sprožilcem.


#### <a name="officeonenotenavigationnavigate"></a>Office.OneNote.Navigation.Navigate

Kritični signal, ki se uporablja za spremljanje možnosti uporabnikov OneNota za krmarjenje med stranmi v OneNotu.  Telemetrija, uporabljena za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in ustreznosti stanja storitve. Če uporabniki ne morejo krmariti, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so sledeča polja:

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

Zbrana so sledeča polja:
    
- **NotebookID** – enolični identifikator zvezka.


#### <a name="officeonenotenotebookmanagementopennotebook"></a>Office.OneNote.NotebookManagement.OpenNotebook

Kritični signal, ki se uporablja za spremljanje možnosti uporabnikov OneNota za odpiranje zvezkov v OneNotu.  Telemetrija, uporabljena za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in ustreznosti stanja storitve. Če uporabniki ne morejo odpreti zvezkov, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so sledeča polja:

-  **NotebookID** – enolični identifikator zvezka.

    
#### <a name="officeonenotesearchsearch"></a>Office.OneNote.Search.Search

ID kritičnega signala, uporabljan za spremljanje možnosti OneNotovih uporabnikov za iskanje informacij na več tisoč straneh in v več tisoč zvezkih.   Telemetrija, uporabljena za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in ustreznosti stanja storitve. Če uporabniki ne morejo najti informacij v zvezkih, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so sledeča polja:

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

### <a name="officeonenotesigscriticalerrorencountered"></a>Office.OneNote.SIGS.CriticalErrorEncountered

Ta dogodek zajame kritični signal, ki se uporablja za nadzor ustreznosti stanja storitve Signal Ingestion Service (SIGS), tako, da izvede prijavo vsakič, ko je zaznana kritična napaka. Kritične napake lahko blokirajo celotno storitev SIGS, zato s tem dogodkom lažje preprečimo morebitne takšne napake takoj, ko jih uporabniki zaznajo. 

V nasprotnem primeru bi nam uporabniki morali poročati o težavah, ki jih zaznajo. Če ne bi bilo na voljo takšne telemetrije, bi bil povprečni čas prejema takšnih napak precej daljši.

Zbrana so naslednja polja: 

- **ErrorCode** – Koda napake, ki jo je zaznal uporabnik.


#### <a name="officeonenotestickynotesnotecreated-on-ios-onenotestickynotesnotecreated-on-android"></a>Office.OneNote.StickyNotes.NoteCreated (na iOS), OneNote.StickyNotes.NoteCreated (na Android)

To je kritični signal, ki se uporablja za nadzor zmogljivosti Lepljivih zapiskov za ustvarjanje zapiskov v aplikaciji.  Telemetrija se uporablja za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in stanja storitve. Če uporabniki ne morejo ustvariti zapiska, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so sledeča polja:

- **NoteLocalId** – razpoznavni enolični identifikator, ki je dodeljen zapisku v času, ko uporabnik ustvari zapiski v programu.

- **IsExportable** – zastavica, ki označuje, ali je bil dogodek rezultat dejanja uporabnika ali ne. Mora biti nastavljen na vrednost true, ker je NoteCreated dejanje, ki ga je sprožil uporabnik.

- **StickyNotes – SDKVersion** – številka različice, ki označuje različico Lepljivih zapiskov, ki jo uporablja uporabnik. Omogoča, da določimo, v katerih različicah izdelka je prišlo do težave ter te težave razvrstimo po pomembnosti.


#### <a name="officeonenotestickynotesnoteviewed-on-ios-onenotestickynotesnoteviewed-on-android"></a>Office.OneNote.StickyNotes.NoteViewed (na iOS), OneNote.StickyNotes.NoteViewed (na Android)

To je kritični signal, ki se uporablja za nadzor zmogljivosti Lepljivih zapiskov za ustvarjanje zapiskov v aplikaciji.  Telemetrija se uporablja za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in stanja storitve. Če uporabniki ne morejo ustvariti zapiska, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so sledeča polja:

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

- **SectionError_Type** – vrsta napake sinhronizacije odseka, na primer »Win32Error« itd.

- **Success** – označuje, ali je sinhronizacija zvezka uspešna ali ne

- **SyncDestinationType** – vrsta cilja sinhronizacije, denimo OneDrive ali SharePoint Online

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

  - **AccountInfoSource** – vir nastavitev računa (na primer samodejno odkrivanje, GuessSmart, samodejno zaznavanje itd.).

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

Zbira rezultate ustvarjanja nove shrambe (z vrsto in različico) ter kodo rezultatov. Z aktivnim spremljanjem tega dogodka nadziramo ustreznost uporabnikove zmogljivosti sinhroniziranja in lokalnega shranjevanja pošte, arhiviranja e-poštnih sporočil (v PST-ju) ali uporabe Skupin.

Zbrana so sledeča polja:

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

  - **Data_Doc_AsyncOpenKind:long –** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

  - **Data\_Doc\_ChunkingType:long** – Način shranjevanja dokumenta v SharePointu.

  - **Data\_Doc\_EdpState:long** – Stanje zaščite podatkov podjetja za dokument.

  - **Data\_Doc\_Ext:string** – Pripona dokumenta.

  - **Data\_Doc\_Extenstion:string** – Pripona dokumenta.

  - **Data\_Doc\_FileFormat:long** – Nabor vnaprej določenih vrednosti za obliko zapisa datoteke (bolj podrobno kot za pripono).

  - **Data\_Doc\_Fqdn:string** – Mesto, kjer je dokument shranjen (SharePoint.com, live.net); na voljo samo za domene v storitvi Office 365.

  - **Data\_Doc\_FqdnHash:string** – Zgoščena vrednost mesta shrambe dokumenta.

  - **Data\_Doc\_IdentityTelemetryId:string** – Enolični GUID uporabnika.

  - **Data\_Doc\_IdentityUniqueId:string –** enolični identifikator identitete, ki je bila uporabljena za dokumente v skupni rabi

  - **Data\_Doc\_IOFlags:long** – Bitna maska za različne zastavice danega dokumenta, povezane z VI.

  - **Data\_Doc\_IrmRights:long** – Nabor vnaprej določenih vrednosti za vrsto upravljanja pravic do informacij, ki velja za ta dokument (»Forward«, »Reply«, »SecureReader«, »Edit« itd.).

  - **Data\_Doc\_IsCloudCollabEnabled:bool** – Ima vrednost »true«, če je bila že prejeta glava HTTP »IsCloudCollabEnabled«, ki njo je poslala zahteva OPTIONS.

  - **Data\_Doc\_IsIncrementalOpen:bool** – Ali je bil dokument odprt postopoma (nova funkcija, ki odpre dokument tako, da ne prenese celoten dokument).

  - **Data\_Doc\_IsOcsSupported:bool** – ali dokument podpira soavtorstvo z novo storitvijo OCS

  - **Data\_Doc\_IsOpeningOfflineCopy:bool** – Preverja, ali je bil dokument odprt v lokalnem predpomnilniku.

  - **Data\_Doc\_IsSyncBacked:bool** – Preverja, ali je bil dokument odprt v mapi, za katero je uporabljena aplikacija za povratno sinhronizacijo v storitvi OneDrive.

  - **Data\_Doc\_Location:long** – Nabor vnaprej določenih vrednosti za mesto shranjevanja dokumenta (lokalno, SharePoint, WOPI, omrežje itd.).

  - **Data\_Doc\_LocationDetails:long** – Nabor vnaprej določenih vrednosti podrobnejše lokacije (mapa »Začasno«, mapa »Prenosi«, dokumenti storitve OneDrive, slike storitve OneDrive itd.).

  - **Data\_Doc\_NumberCoAuthors:long** –število soavtorjev, ko je bil dokument odprt

  - **Data\_Doc\_PasswordFlags:long** – Nabor vnaprej določenih vrednosti za način šifriranja dokumenta z geslom (brez, geslo za branje, geslo za urejanje).

  - **Data\_Doc\_ReadOnlyReasons:long** – Nabor vnaprej določenih vrednosti, zakaj je bil ta dokument označen samo za branje (zaklenjeno v strežniku, dokončni dokument, zaščiteno z geslom za urejanje itd.).

  - **Data\_Doc\_ResourceIdHash:string** – Zgoščena vrednost identifikatorja vira za dokumente, shranjene v oblaku.

  - **Data_Doc_RtcType** – označuje, kako je bil kanal v realnem času (RTC) nastavljen za trenutno datoteko (onemogočeno, nepodprto, na zahtevo, vedno vklopljeno itn.).

  - **Data\_Doc\_ServerDocId:string –** nespremenljivi identifikator za dokumente, shranjene v oblaku

  - **Data\_Doc\_ServerProtocol:long** – Nabor vnaprej določenih vrednosti, ki jih protokol uporablja za komunikacijo s strežnikom (Http, Cobalt, WOPI itd.).

  - **Data\_Doc\_ServerType:long –** nabor vnaprej določenih vrednosti za vrsto strežnika (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long** – preverja, ali strežnik temelji na sistemu Office14, Office15 ali Office 16

  - **Data\_Doc\_SessionId:long –** ustvarjeni GUID, ki prepozna primerek dokumenta v seji istega procesa

  - **Data\_Doc\_SharePointServiceContext:string** – Neprosojen niz, običajno »GridManagerID.FarmID«. Uporabni podatki za korelacijo odjemalskega in strežniškega dnevnika.

  - **Data\_Doc\_SizeInBytes:long** – Velikost dokumenta v bajtih.

  - **Data\_Doc\_SpecialChars:long** – Bitna maska, ki označuje posebne znake v URL-ju ali poti dokumenta.

  - **Data\_Doc\_StorageProviderId:string** – Niz, ki prepozna ponudnika za shranjevanje dokumentov, npr. »DropBox«.

  - **Data\_Doc\_StreamAvailability:long** – Nabor vnaprej določenih vrednosti za stanje dokumenta Stream (na voljo, stalno onemogočeno, ni na voljo).

  - **Data\_Doc\_UrlHash:string** – Zgoščena vrednost polnega URL-ja za dokumente, shranjene v oblaku.

  - **Data\_Doc\_UsedWrsDataOnOpen:bool** – Ima vrednost »true«, če je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS na strani gostitelja.

  - **Data\_Doc\_WopiServiceId:string** – Identifikator storitve WOPI, na primer »Dropbox«

  - **Data\_DocHasStorage:bool** – Ali ima ta dokument lokalno shrambo?

  - **Data\_fLifeguarded:bool –** ali je bil dokument kdaj zavarovan (funkcija za samodejno odpravljanje težav z dokumenti brez pozivanja uporabnika)?

  - **Data\_IsDocAutoSaveable:bool -** Is presentation auto saveable?

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

  - **Data\_StopwatchDuration:long –** skupni čas dejavnosti

  - **Data\_UserContinuedZRTClose:bool** – Ali je uporabnik izbral možnost »Nadaljuj« zapiranje, ko je bilo ob zapiranju dokumenta prikazano pogovorno okno?

#### <a name="officepowerpointdocoperationnewdocument"></a>Office.PowerPoint.DocOperation.NewDocument

Dogodek je zbran, ko PowerPoint ustvari novo predstavitev.  Vključuje metrike uspešnosti, neuspešnosti in učinkovitosti delovanja.

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

  - **Data_Doc_AsyncOpenKind:long –** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

  - **Data\_Doc\_ChunkingType:long** – Način shranjevanja dokumenta v SharePointu.

  - **Data\_Doc\_EdpState:long** – Stanje zaščite podatkov podjetja za dokument.

  - **Data\_Doc\_Ext:string** – Pripona dokumenta.

  - **Data\_Doc\_Extenstion:string** – Pripona dokumenta.

  - **Data\_Doc\_FileFormat:long** – Nabor vnaprej določenih vrednosti za obliko zapisa datoteke (bolj podrobno kot za pripono).

  - **Data\_Doc\_Fqdn:string** – Mesto, kjer je dokument shranjen (SharePoint.com, live.net); na voljo samo za domene v storitvi Office 365.

  - **Data\_Doc\_FqdnHash:string** – Zgoščena vrednost mesta shrambe dokumenta.

  - **Data\_Doc\_IdentityTelemetryId:string** – Enolični GUID uporabnika.

  - **Data\_Doc\_IdentityUniqueId:string –** enolični identifikator identitete, ki je bila uporabljena za dokumente v skupni rabi

  - **Data\_Doc\_IOFlags:long** – Bitna maska za različne zastavice danega dokumenta, povezane z VI.

  - **Data\_Doc\_IrmRights:long** – Nabor vnaprej določenih vrednosti za vrsto upravljanja pravic do informacij, ki velja za ta dokument (»Forward«, »Reply«, »SecureReader«, »Edit« itd.).

  - **Data\_Doc\_IsCloudCollabEnabled:bool** – Ima vrednost »true«, če je bila že prejeta glava HTTP »IsCloudCollabEnabled«, ki njo je poslala zahteva OPTIONS.

  - **Data\_Doc\_IsIncrementalOpen:bool** – Ali je bil dokument odprt postopoma (nova funkcija, ki odpre dokument tako, da ne prenese celoten dokument).

  - **Data\_Doc\_IsOcsSupported:bool** – ali dokument podpira soavtorstvo z novo storitvijo OCS

  - **Data\_Doc\_IsOpeningOfflineCopy:bool** – Ali je bil dokument odprt iz lokalnega predpomnilnika?

  - **Data\_Doc\_IsSyncBacked:bool** –Ali je bil dokument odprt iz mape, za katero se uporablja aplikacija za povratno sinhronizacijo v storitvi OneDrive.

  - **Data\_Doc\_Location:long** – Nabor vnaprej določenih vrednosti za mesto shranjevanja dokumenta (lokalno, SharePoint, WOPI, omrežje itd.).

  - **Data\_Doc\_LocationDetails:long** – Nabor vnaprej določenih vrednosti podrobnejše lokacije (mapa »Začasno«, mapa »Prenosi«, dokumenti storitve OneDrive, slike storitve OneDrive itd.).

  - **Data\_Doc\_NumberCoAuthors:long** –število soavtorjev, ko je bil dokument odprt

  - **Data\_Doc\_PasswordFlags:long** – Nabor vnaprej določenih vrednosti za način šifriranja dokumenta z geslom (brez, geslo za branje, geslo za urejanje).

  - **Data\_Doc\_ReadOnlyReasons:long** – Nabor vnaprej določenih vrednosti, zakaj je bil ta dokument označen samo za branje (zaklenjeno v strežniku, dokončni dokument, zaščiteno z geslom za urejanje itd.).

  - **Data\_Doc\_ResourceIdHash:string** – Zgoščena vrednost identifikatorja vira za dokumente, shranjene v oblaku.

  - **Data_Doc_RtcType** – označuje, kako je bil kanal v realnem času (RTC) nastavljen za trenutno datoteko (onemogočeno, nepodprto, na zahtevo, vedno vklopljeno itn.).

  - **Data\_Doc\_ServerDocId:string –** nespremenljivi identifikator za dokumente, shranjene v oblaku

  - **Data\_Doc\_ServerProtocol:long** – Nabor vnaprej določenih vrednosti, ki jih protokol uporablja za komunikacijo s strežnikom (Http, Cobalt, WOPI itd.).

  - **Data\_Doc\_ServerType:long –** nabor vnaprej določenih vrednosti za vrsto strežnika (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long** – preverja, ali strežnik temelji na sistemu Office14, Office15 ali Office 16

  - **Data\_Doc\_SessionId:long –** ustvarjeni GUID, ki prepozna primerek dokumenta v seji istega procesa

  - **Data\_Doc\_SharePointServiceContext:string** – Neprosojen niz, običajno »GridManagerID.FarmID«. Uporabni dogodki za korelacijo odjemalskih in strežniških dnevnikov.

  - **Data\_Doc\_SizeInBytes:long** – Velikost dokumenta v bajtih.

  - **Data\_Doc\_SpecialChars:long** – Bitna maska, ki označuje posebne znake v URL-ju ali poti dokumenta.

  - **Data\_Doc\_StorageProviderId:string** – Niz, ki prepozna ponudnika za shranjevanje dokumentov, npr. »DropBox«.

  - **Data\_Doc\_StreamAvailability:long** – Nabor vnaprej določenih vrednosti za stanje dokumenta Stream (na voljo, stalno onemogočeno, ni na voljo).

  - **Data\_Doc\_UrlHash:string** – Zgoščena vrednost polnega URL-ja za dokumente, shranjene v oblaku.

  - **Data\_Doc\_UsedWrsDataOnOpen:bool** – Ima vrednost »true«, če je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS na strani gostitelja.

  - **Data\_Doc\_WopiServiceId:string** – Identifikator storitve WOPI, na primer »Dropbox«

  - **Data\_ExecutionCount:long** – Kolikokrat je bil izveden protokol IncOpen pred izvedbo tega (OpenComplete) protokola.

  - **Data\_FailureComponent:long** – Nabor vnaprej določenih vrednosti komponent, zaradi katerih tega protokola ni bilo mogoče izvesti. (Spor, CSI, Internal itd.)

  - **Data\_FailureReason:long –** nabor vnaprej določenih vrednosti za vzroke okvare (FileIsCorrupt, BlockedByAntivirus itd.)

  - **Data_FullDownloadRoundTripCount:long** – število izvedenih povratnih poti do strežnika za prenos celotnega dokumenta.
  
  - **Data_IsProtocolRunInIncOpenMode:bool** – ali je bil protokol zagnan za postopni prenos – to je vrsta prenosa, pri katerem so deli dokumenta preneseni po tem, ko so bili prikazani uporabniku.

  - **Data\_MethodId:long** – Katera vrstica kode je bila zadnja izvedena v postopku.

  - **Data\_StopwatchDuration:long –** skupni čas dejavnosti

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

  - **Data_Doc_AsyncOpenKind:long –** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

  - **Data\_Doc\_ChunkingType:long** – Način shranjevanja dokumenta v SharePointu.

  - **Data\_Doc\_EdpState:long** – Stanje zaščite podatkov podjetja za dokument.

  - **Data\_Doc\_Ext:string** – Pripona dokumenta.

  - **Data\_Doc\_Extenstion:string** – Pripona dokumenta.

  - **Data\_Doc\_FileFormat:long** – Nabor vnaprej določenih vrednosti za obliko zapisa datoteke (bolj podrobno kot za pripono).

  - **Data\_Doc\_Fqdn:string** – Mesto, kjer je dokument shranjen (SharePoint.com, live.net); na voljo samo za domene v storitvi Office 365.

  - **Data\_Doc\_FqdnHash:string** – Zgoščena vrednost mesta shrambe dokumenta.

  - **Data\_Doc\_IdentityTelemetryId:string** – Enolični GUID uporabnika.

  - **Data\_Doc\_IdentityUniqueId:string –** enolični identifikator identitete, ki je bila uporabljena za dokumente v skupni rabi

  - **Data\_Doc\_IOFlags:long** – Bitna maska za različne zastavice danega dokumenta, povezane z VI.

  - **Data\_Doc\_IrmRights:long** – Nabor vnaprej določenih vrednosti za vrsto upravljanja pravic do informacij, ki velja za ta dokument (»Forward«, »Reply«, »SecureReader«, »Edit« itd.).

  - **Data\_Doc\_IsCloudCollabEnabled:bool** – Ima vrednost »true«, če je bila že prejeta glava HTTP »IsCloudCollabEnabled«, ki njo je poslala zahteva OPTIONS.

  - **Data\_Doc\_IsIncrementalOpen:bool** – Ali je bil dokument odprt postopoma (nova funkcija, ki odpre dokument tako, da ne prenese celoten dokument).

  - **Data\_Doc\_IsOcsSupported:bool** – ali dokument podpira soavtorstvo z novo storitvijo OCS

  - **Data\_Doc\_IsOpeningOfflineCopy:bool** – Preverja, ali je bil dokument odprt v lokalnem predpomnilniku.

  - **Data\_Doc\_IsSyncBacked:bool** –Ali je bil dokument odprt iz mape, za katero se uporablja aplikacija za povratno sinhronizacijo v storitvi OneDrive.

  - **Data\_Doc\_Location:long** – Nabor vnaprej določenih vrednosti za mesto shranjevanja dokumenta (lokalno, SharePoint, WOPI, omrežje itd.).

  - **Data\_Doc\_LocationDetails:long** – Nabor vnaprej določenih vrednosti podrobnejše lokacije (mapa »Začasno«, mapa »Prenosi«, dokumenti storitve OneDrive, slike storitve OneDrive itd.).

  - **Data\_Doc\_NumberCoAuthors:long** –število soavtorjev, ko je bil dokument odprt

  - **Data\_Doc\_PasswordFlags:long** – Nabor vnaprej določenih vrednosti za način šifriranja dokumenta z geslom (brez, geslo za branje, geslo za urejanje).

  - **Data\_Doc\_ReadOnlyReasons:long** – Nabor vnaprej določenih vrednosti, zakaj je bil ta dokument označen samo za branje (zaklenjeno v strežniku, dokončni dokument, zaščiteno z geslom za urejanje itd.).

  - **Data\_Doc\_ResourceIdHash:string** – Zgoščena vrednost identifikatorja vira za dokumente, shranjene v oblaku.

  - **Data_Doc_RtcType** – označuje, kako je bil kanal v realnem času (RTC) nastavljen za trenutno datoteko (onemogočeno, nepodprto, na zahtevo, vedno vklopljeno itn.).

  - **Data\_Doc\_ServerDocId:string –** nespremenljivi identifikator za dokumente, shranjene v oblaku

  - **Data\_Doc\_ServerProtocol:long** – Nabor vnaprej določenih vrednosti, ki jih protokol uporablja za komunikacijo s strežnikom (Http, Cobalt, WOPI itd.).

  - **Data\_Doc\_ServerType:long –** nabor vnaprej določenih vrednosti za vrsto strežnika (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long** – preverja, ali strežnik temelji na sistemu Office14, Office15 ali Office 16

  - **Data\_Doc\_SessionId:long –** ustvarjeni GUID, ki prepozna primerek dokumenta v seji istega procesa

  - **Data\_Doc\_SharePointServiceContext:string** – Neprosojen niz, običajno »GridManagerID.FarmID«. Uporabni dogodki za korelacijo odjemalskih in strežniških dnevnikov.

  - **Data\_Doc\_SizeInBytes:long** – Velikost dokumenta v bajtih.

  - **Data\_Doc\_SpecialChars:long** – Bitna maska, ki označuje posebne znake v URL-ju ali poti dokumenta.

  - **Data\_Doc\_StorageProviderId:string** – Niz, ki prepozna ponudnika za shranjevanje dokumentov, npr. »DropBox«.

  - **Data\_Doc\_StreamAvailability:long** – Nabor vnaprej določenih vrednosti za stanje dokumenta Stream (na voljo, stalno onemogočeno, ni na voljo).

  - **Data\_Doc\_UrlHash:string** – Zgoščena vrednost polnega URL-ja za dokumente, shranjene v oblaku.

  - **Data\_Doc\_UsedWrsDataOnOpen:bool** – Ima vrednost »true«, če je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS na strani gostitelja.

  - **Data\_Doc\_WopiServiceId:string** – identifikator storitve WOPI, na primer »Dropbox«

  - **Data\_DurationUAEOnSaveStartedMs:long** – Trajanje zapiranja neznane aplikacije med shranjevanjem.

  - **Data\_EnsureSaveTransactionTimeMS:long** – Trajanje preverjanja ustvarjanja transakcije shranjevanja, če ta še ni na voljo.

  - **Data\_FailureComponent:long** – Nabor vnaprej določenih vrednosti komponent, zaradi katerih tega protokola ni bilo mogoče izvesti. (Spor, CSI, Internal itd.)

  - **Data\_FailureReason:long –** nabor vnaprej določenih vrednosti za vzroke okvare (FileIsCorrupt, BlockedByAntivirus itd.)

  - **Data\_fLifeguarded:bool –** ali je bil dokument kdaj zavarovan (funkcija za samodejno odpravljanje težav z dokumenti brez pozivanja uporabnika)?

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

- **Data_DstDoc_AsyncOpenKind:long –** označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

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

- **Data_DstDoc_NumberCoAuthors:long** – število soavtorjev v trenutku, ko je bil dokument odprt

- **Data_DstDoc_PasswordFlags:long** – nabor vnaprej določenih vrednosti za način šifriranja dokumenta z geslom (brez, geslo za branje, geslo za urejanje).

- **Data_DstDoc_ReadOnlyReasons:long** – nabor vnaprej določenih vrednosti, zakaj je bil ta dokument označen samo za branje (zaklenjeno v strežniku, končni dokument, zaščiteno z geslom za urejanje itd.).

- **Data_DstDoc_ResourceIdHash:string** – zgoščena vrednost identifikatorja vira za dokumente, shranjene v oblaku.

- **Data_DstDoc_ServerDocId:string** – nespremenljivi identifikator za dokumente, shranjene v oblaku.

- **Data_DstDoc_ServerProtocol:long** – nabor vnaprej določenih vrednosti, ki jih protokol uporablja za komunikacijo s strežnikom (Http, Cobalt, WOPI itd.).

- **Data_DstDoc_ServerType:long** – nabor vnaprej določenih vrednosti za vrsto strežnika (SharePoint, DropBox, WOPI).

- **Data_DstDoc_ServerVersion:long** – preverja, ali strežnik temelji na sistemu Office 14, Office 15 ali Office 16

- **Data_DstDoc_SessionId:long** – ustvarjeni GUID, ki prepozna primerek dokumenta v isti seji procesa.

- **Data_DstDoc_SharePointServiceContext:string** – neprosojen niz, običajno »GridManagerID.FarmID«. Uporabni dogodki za korelacijo odjemalskih in strežniških dnevnikov.

- **Data_DstDoc_SizeInBytes:long** – velikost dokumenta v bajtih.

- **Data_DstDoc_SpecialChars:long** – bitna maska, ki označuje posebne znake v URL-ju ali poti dokumenta.

- **Data_DstDoc_StorageProviderId:string** – niz, ki prepozna ponudnika shrambe dokumentov, npr. »DropBox«.

- **Data_DstDoc_StorageProviderId:string** – nabor vnaprej določenih vrednosti za stanje toka dokumentov (na voljo, stalno onemogočeno, ni na voljo).

- **Data_DstDoc_UrlHash:string** – zgoščena vrednost polnega URL-ja za dokumente, shranjene v oblaku.

- **Data_DstDoc_UsedWrsDataOnOpen:bool** – ima vrednost »true«, če je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS v gostitelju.

- **Data_DstDoc_WopiServiceId:string** – identifikator storitve WOPI, na primer »Dropbox«

- **Data_FileType:long** – nabor vnaprej določenih vrednosti notranje vrste datoteke.

- **Data_fLifeguarded:bool** – označuje, ali je bil dokument kdaj zavarovan (funkcija za samodejno odpravljanje težav z dokumenti brez pozivanja uporabnika)?

- **Data_FWebCreated:bool** – označuje, ali ta dokument vsebuje zastavico »WebCreator«?

- **Data_SaveReason:long** – nabor vnaprej določenih vrednosti, zakaj je bilo izvedeno to shranjevanje. (AutoSave, ToOCSTransitionSave, ToCSITransitionSave itd.).

- **Data_SaveType:long** – nabor vnaprej določenih vrednosti vrste shranjevanja (»SaveAs«, »Publish«, »Manual«, OMSave itd.). 

- **Data_SrcDoc_AccessMode:long** – način odpiranja tega dokumenta (samo za branje | branje in pisanje).

- **Data_SrcDoc_AssistedReadingReasons:long** – nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

- **Data_SrcDoc_AsyncOpenKind:long –** označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

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

- **Data_SrcDoc_IsOcsSupported:bool** – označuje, ali dokument podpira soavtorstvo z novo storitvijo OCS

- **Data_SrcDoc_IsOpeningOfflineCopy:bool** – preverja, ali je dokument odprt v lokalnem predpomnilniku.

- **Data_SrcDoc_IsSyncBacked:bool** –označuje, ali je bil dokument odprt v mapi, za katero se uporablja aplikacija za povratno sinhronizacijo v storitvi OneDrive.

- **Data_SrcDoc_Location:long** – nabor vnaprej določenih vrednosti za mesto shranjevanja dokumenta (lokalno, SharePoint, WOPI, omrežje itd.).

- **Data_SrcDoc_LocationDetails:long** – nabor vnaprej določenih vrednosti podrobnejše lokacije (mapa »Začasno«, mapa »Prenosi«, dokumenti storitve One Drive, slike storitve One Drive itd.).

- **Data_SrcDoc_NumberCoAuthors:long** – število soavtorjev v trenutku, ko je bil dokument odprt

- **Data_SrcDoc_PasswordFlags:long** – nabor vnaprej določenih vrednosti za način šifriranja dokumenta z geslom (brez, geslo za branje, geslo za urejanje).

- **Data_SrcDoc_ReadOnlyReasons:long** – nabor vnaprej določenih vrednosti, zakaj je bil ta dokument označen samo za branje (zaklenjeno v strežniku, končni dokument, zaščiteno z geslom za urejanje itd.).

- **Data_SrcDoc_ResourceIdHash:string** – zgoščena vrednost identifikatorja vira za dokumente, shranjene v oblaku.

- **Data_SrcDoc_ServerDocId:string** – nespremenljivi identifikator za dokumente, shranjene v oblaku.

- **Data_SrcDoc_ServerProtocol:long** – nabor vnaprej določenih vrednosti, ki jih protokol uporablja za komunikacijo s strežnikom (Http, Cobalt, WOPI itd.).

- **Data_SrcDoc_ServerType:long** – nabor vnaprej določenih vrednosti za vrsto strežnika (SharePoint, DropBox, WOPI).

- **Data_SrcDoc_ServerVersion:long** – preverja, ali strežnik temelji na sistemu Office 14, Office 15 ali Office 16

- **Data_SrcDoc_SessionId:long** – ustvarjeni GUID, ki prepozna primerek dokumenta v isti seji procesa.

- **Data_SrcDoc_SharePointServiceContext:string** – neprosojen niz, običajno »GridManagerID.FarmID«. Uporabni dogodki za korelacijo odjemalskih in strežniških dnevnikov.

- **Data_SrcDoc_SizeInBytes:long** – velikost dokumenta v bajtih.

- **Data_SrcDoc_SpecialChars:long** – bitna maska, ki označuje posebne znake v URL-ju ali poti dokumenta.

- **Data_SrcDoc_StorageProviderId:string** – niz, ki prepozna ponudnika shrambe dokumentov, npr. »DropBox«.

- **Data_SrcDoc_StreamAvailability:long** – nabor vnaprej določenih vrednosti za stanje toka dokumentov (na voljo, stalno onemogočeno, ni na voljo).

- **Data_SrcDoc_UrlHash:string** – zgoščena vrednost polnega URL-ja za dokumente, shranjene v oblaku.

- **Data_SrcDoc_UsedWrsDataOnOpen:bool** – ima vrednost »true«, če je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS v gostitelju.

- **Data_SrcDoc_WopiServiceId:string** – identifikator storitve WOPI, npr. »Dropbox«

- **Data_StopwatchDuration:long** – skupni čas dejavnosti.

- **Data_TypeOfSaveDialog:long** – Vnaprej opredeljen nabor vrednosti pogovornega okna (RUN_SAVEAS_DLG,RUN_SAVEMEDIA_DLG, RUN_SAVEAS_VIDEO_DLG itd.)

- **Data_WaitForSaveOrMergeSuccess:bool** – Postopek SaveAs je uspel med čakanjem na shranjevanje ali združevanje v ozadju.
 
- **Data_WaitForSaveOrMergeTimeout:long** – časovna omejitev postopka SaveAs je potekla med čakanjem na shranjevanje ali združevanje v ozadju.

- **DstDoc** – Nova lokacija dokumenta. 

- **SrcDoc** – izvirna lokacija dokumenta.


#### <a name="officepowerpointdocoperationsavelegacy"></a>Office.PowerPoint.DocOperation.SaveLegacy

Podatki so zbrani, kadar koli PowerPoint izvede postopek shranjevanja s potjo podedovane kode. Dogodek vsebuje vrsto rezultata uspešne oz. neuspešne metrike učinkovitosti shranjevanja in pomembne metapodatke dokumenta.  Napake pri shranjevanju lahko privedejo do izgube podatkov.  Microsoft uporablja te podatke za zagotavljanje ustreznega delovanje funkcije in uspešnega shranjevanja uporabnikove vsebine.

Zbrana so sledeča polja:

- **Data_AddDocTelemetryResult:long** – označuje, ali ima ta dolgi vnos vso zahtevano telemetrijo dokumenta (polja »Data_Doc_*«)? Če je nima, zakaj?

- **Data_CppUncaughtExceptionCount:long** – nezaznane izvirne izjeme med izvedbo dejavnosti.

- **Data_DetachedDuration:long** – čas, v katerem je bila dejavnost ločena/ni bila izvajana.

- **Data_Doc_AccessMode:long** – način odpiranja dokumenta (samo za branje | branje in pisanje)

- **Data_Doc_AssistedReadingReasons:long** – nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

- **Data_Doc_AsyncOpenKind:long –** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

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

- **Data_Doc_IsOcsSupported:bool** – označuje, ali dokument podpira soavtorstvo z novo storitvijo OCS

- **Data_Doc_IsOpeningOfflineCopy:bool** – preverja, ali je bil dokument odprt v lokalnem predpomnilniku.

- **Data_Doc_IsSyncBacked:bool** –označuje, ali je bil dokument odprt v mapi, za katero se uporablja aplikacija za povratno sinhronizacijo v storitvi OneDrive.

- **Data_Doc_Location:long** – nabor vnaprej določenih vrednosti za mesto shrambe dokumenta (lokalno, SharePoint, WOPI, omrežje itd.).

- **Data_Doc_LocationDetails:long** – nabor vnaprej določenih vrednosti podrobnejše lokacije (mapa »Začasno«, mapa »Prenosi«, dokumenti storitve OneDrive, slike storitve OneDrive itd.).

- **Data_Doc_NumberCoAuthors:long** – število soavtorjev v trenutku, ko je bil dokument odprt

- **Data_Doc_PasswordFlags:long** – nabor vnaprej določenih vrednosti za način šifriranja dokumenta z geslom (brez, geslo za branje, geslo za urejanje).

- **Data_Doc_ReadOnlyReasons:long** – nabor vnaprej določenih vrednosti, zakaj je bil ta dokument označen samo za branje (zaklenjeno v strežniku, končni dokument, zaščiteno z geslom za urejanje itd.).

- **Data_Doc_ResourceIdHash:string** – zgoščena vrednost identifikatorja vira za dokumente, shranjene v oblaku.

- **Data_Doc_RtcType** – označuje, kako je bil kanal v realnem času (RTC) nastavljen za trenutno datoteko (onemogočeno, nepodprto, na zahtevo, vedno vklopljeno itn.).

- **Data_Doc_ServerDocId:string** – nespremenljivi identifikator za dokumente, shranjene v oblaku.

- **Data_Doc_ServerProtocol:long** – nabor vnaprej določenih vrednosti, ki jih protokol uporablja za komunikacijo s strežnikom (Http, Cobalt, WOPI itd.).

- **Data_Doc_ServerType:long** – nabor vnaprej določenih vrednosti za vrsto strežnika (SharePoint, DropBox, WOPI). 

- **Data_Doc_ServerVersion:long** – preverja, ali strežnik temelji na sistemu Office 14, Office 15 ali Office 16

- **Data_Doc_SessionId:long** – ustvarjeni GUID, ki prepozna primerek dokumenta v isti seji procesa.

- **Data_Doc_SharePointServiceContext:string** – neprosojen niz, običajno »GridManagerID.FarmID«. Uporabni dogodki za korelacijo odjemalskih in strežniških dnevnikov.

- **Data_Doc_SizeInBytes:long** – velikost dokumenta v bajtih.

- **Data_Doc_SpecialChars:long** – bitna maska, ki označuje posebne znake v URL-ju ali poti dokumenta.

- **Data_Doc_StorageProviderId:string** – niz, ki prepozna ponudnika shrambe dokumentov, npr. »DropBox«.

- **Data_Doc_StreamAvailability:long** – nabor vnaprej določenih vrednosti za stanje toka dokumentov (na voljo, stalno onemogočeno, ni na voljo).

- **Data_Doc_UrlHash:string** – zgoščena vrednost polnega URL-ja za dokumente, shranjene v oblaku.

- **Data_Doc_UsedWrsDataOnOpen:bool** – ima vrednost »true«, če je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS v gostitelju.

- **Data_Doc_WopiServiceId:string** – identifikator storitve WOPI, npr. »Dropbox«

- **Data_DstDoc_AccessMode:long** – način odpiranja tega dokumenta (samo za branje | branje in pisanje).

- **Data_DstDoc_AssistedReadingReasons:long** – nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

- **Data_DstDoc_AsyncOpenKind:long –** označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

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

- **Data_DstDoc_NumberCoAuthors:long** – število soavtorjev v trenutku, ko je bil dokument odprt

- **Data_DstDoc_PasswordFlags:long** – nabor vnaprej določenih vrednosti za način šifriranja dokumenta z geslom (brez, geslo za branje, geslo za urejanje).

- **Data_DstDoc_ReadOnlyReasons:long** – nabor vnaprej določenih vrednosti, zakaj je bil ta dokument označen samo za branje (zaklenjeno v strežniku, končni dokument, zaščiteno z geslom za urejanje itd.)

- **Data_DstDoc_ResourceIdHash:string** – zgoščena vrednost identifikatorja vira za dokumente, shranjene v oblaku.

- **Data_DstDoc_ServerDocId:string** – nespremenljivi identifikator za dokumente, shranjene v oblaku.

- **Data_DstDoc_ServerProtocol:long** – nabor vnaprej določenih vrednosti, ki jih protokol uporablja za komunikacijo s strežnikom (Http, Cobalt, WOPI itd.).

- **Data_DstDoc_ServerType:long** – nabor vnaprej določenih vrednosti za vrsto strežnika (SharePoint, DropBox, WOPI).

- **Data_DstDoc_ServerVersion:long** – preverja, ali strežnik temelji na sistemu Office 14, Office 15 ali Office 16

- **Data_DstDoc_SessionId:long** – ustvarjeni GUID, ki prepozna primerek dokumenta v isti seji procesa.

- **Data_DstDoc_SharePointServiceContext:string** – neprosojen niz, običajno »GridManagerID.FarmID«. Uporabni dogodki za korelacijo odjemalskih in strežniških dnevnikov.

- **Data_DstDoc_SizeInBytes:long** – velikost dokumenta v bajtih.

- **Data_DstDoc_SpecialChars:long** – bitna maska, ki označuje posebne znake v URL-ju ali poti dokumenta.

- **Data_DstDoc_StorageProviderId:string** – niz, ki prepozna ponudnika shrambe dokumentov, npr. »DropBox«.

- **Data_DstDoc_StorageProviderId:string** – nabor vnaprej določenih vrednosti za stanje toka dokumentov (na voljo, stalno onemogočeno, ni na voljo).

- **Data_DstDoc_UrlHash:string** – zgoščena vrednost polnega URL-ja za dokumente, shranjene v oblaku.

- **Data_DstDoc_UsedWrsDataOnOpen:bool** – ima vrednost »true«, če je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS v gostitelju.

- **Data_DstDoc_WopiServiceId:string** – identifikator storitve WOPI, na primer »Dropbox«

- **Data_FileType:long** – nabor vnaprej določenih vrednosti notranje vrste datoteke.

- **Data_fLifeguarded:bool** – označuje, ali je bil dokument kdaj zavarovan (funkcija za samodejno odpravljanje težav z dokumenti brez pozivanja uporabnika)?

- **Data_SaveReason:long** – nabor vnaprej določenih vrednosti, zakaj je bilo izvedeno to shranjevanje. (AutoSave, ToOCSTransitionSave, ToCSITransitionSave itd.)

- **Data_SaveType:long** – nabor vnaprej določenih vrednosti vrste shranjevanja (»SaveAs«, »Publish«, »Manual«, OMSave itd.)

- **Data_SrcDoc_AccessMode:long** – način odpiranja tega dokumenta (samo za branje | branje in pisanje).

- **Data_SrcDoc_AssistedReadingReasons:long** – nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

- **Data_SrcDoc_AsyncOpenKind:long –** označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

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

- **Data_SrcDoc_IsOcsSupported:bool** – označuje, ali dokument podpira soavtorstvo z novo storitvijo OCS

- **Data_SrcDoc_IsOpeningOfflineCopy:bool** – preverja, ali je dokument odprt v lokalnem predpomnilniku.

- **Data_SrcDoc_IsSyncBacked:bool** –označuje, ali je bil dokument odprt v mapi, za katero se uporablja aplikacija za povratno sinhronizacijo v storitvi OneDrive.

- **Data_SrcDoc_Location:long** – nabor vnaprej določenih vrednosti za mesto shranjevanja dokumenta (lokalno, SharePoint, WOPI, omrežje itd.).

- **Data_SrcDoc_LocationDetails:long** – nabor vnaprej določenih vrednosti podrobnejše lokacije (mapa »Začasno«, mapa »Prenosi«, dokumenti storitve One Drive, slike storitve One Drive itd.)

- **Data_SrcDoc_NumberCoAuthors:long** – število soavtorjev v trenutku, ko je bil dokument odprt

- **Data_SrcDoc_PasswordFlags:long** – nabor vnaprej določenih vrednosti za način šifriranja dokumenta z geslom (brez, geslo za branje, geslo za urejanje).

- **Data_SrcDoc_ReadOnlyReasons:long** – nabor vnaprej določenih vrednosti, zakaj je bil ta dokument označen samo za branje (zaklenjeno v strežniku, končni dokument, zaščiteno z geslom za urejanje itd.).

- **Data_SrcDoc_ResourceIdHash:string** – zgoščena vrednost identifikatorja vira za dokumente, shranjene v oblaku.

- **Data_SrcDoc_ServerDocId:string** – nespremenljivi identifikator za dokumente, shranjene v oblaku.

- **Data_SrcDoc_ServerProtocol:long** – nabor vnaprej določenih vrednosti, ki jih protokol uporablja za komunikacijo s strežnikom (Http, Cobalt, WOPI itd.).

- **Data_SrcDoc_ServerType:long** – nabor vnaprej določenih vrednosti za vrsto strežnika (SharePoint, DropBox, WOPI).

- **Data_SrcDoc_ServerVersion:long** – preverja, ali strežnik temelji na sistemu Office 14, Office 15 ali Office 16

- **Data_SrcDoc_SessionId:long** – ustvarjeni GUID, ki prepozna primerek dokumenta v isti seji procesa.

- **Data_SrcDoc_SharePointServiceContext:string** – neprosojen niz, običajno »GridManagerID.FarmID«. Uporabni dogodki za korelacijo odjemalskih in strežniških dnevnikov.

- **Data_SrcDoc_SizeInBytes:long** – velikost dokumenta v bajtih.

- **Data_SrcDoc_SpecialChars:long** – bitna maska, ki označuje posebne znake v URL-ju ali poti dokumenta.

- **Data_SrcDoc_StorageProviderId:string** – niz, ki prepozna ponudnika shrambe dokumentov, npr. »DropBox«.

- **Data_SrcDoc_StreamAvailability:long** – nabor vnaprej določenih vrednosti za stanje toka dokumentov (na voljo, stalno onemogočeno, ni na voljo).

- **Data_SrcDoc_UrlHash:string** – zgoščena vrednost polnega URL-ja za dokumente, shranjene v oblaku.

- **Data_SrcDoc_UsedWrsDataOnOpen:bool** – ima vrednost »true«, če je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS v gostitelju.

- **Data_SrcDoc_WopiServiceId:string** – identifikator storitve WOPI, npr. »Dropbox«

- **Data_StopwatchDuration:long** – skupni čas dejavnosti.

- **Data_TypeOfSaveDialog:long** – vnaprej opredeljen nabor vrednosti pogovornega okna (RUN_SAVEAS_DLG, RUN_SAVEMEDIA_DLG, RUN_SAVEAS_VIDEO_DLG itd.)

- **Doc** – trenutni dokument za shranjevanje.

- **DstDoc** – novo mesto dokumenta (v primeru možnosti »Shrani kot«).

- **SrcDoc** – izvirno mesto dokumenta (v primeru možnosti »Shrani kot«).


#### <a name="officepowerpointpptiosrehearseview"></a>Office.PowerPoint.PPT.IOS.RehearseView 

Ta dogodek označuje, da je uporabnik ustavil sejo vaje. Ti podatki so uporabljeni v kombinaciji s parametrom Office.PowerPoint.IOS.Android.RehearseView.StartSession kot prvi indikator morebitnih zrušitev ali napak, ki jih zazna uporabnik.  
 
Zbrana so sledeča polja:

- **ConnectionCreationTime** časa, ki je bil ustvarjen za ustvarjanje povezav storitve.

- **CountDownAlertTime** – Čas prikaza opozorila z odštevanjem.

- **CountdownInitTime** – Čad med dokončanjem nalaganja diaprojekcije in začetkom odštevanja.

- **CritiqueSummary** – Povzetek vseh pripomb, ki so bile prikazane uporabniku.

- **ExitEventCode** – Koda za prepoznavanje vrste scenarija, kjer je uporabnik zaprl sejo vaje v okviru scenarija napake ali uspešnega izhoda.

- **FRETime** – Čas med začetkom prikaza zaslona FRE in njegovim zapiranjem s strani uporabnika.

- **MicrophonePermissionTime** – Čas prikaza opozorila o dovoljenju za mikrofon, dokler uporabnik ni izbral ene od možnosti.

- **PauseRehearsingCount** – Število klikov uporabnika z namenom začasne ustavitve vaje.

- **RehearsalInitTime** – Čas, potreben za inicializiranje vaje.

- **ResumeRehearsingCount** – Število klikov uporabnika z namenom nadaljevanja vaje.

- **Sessionid** – ID govorne seje z vhodnih vrat.  Ta parameter je uporabljen za odpravljanje napak v dnevnikih storitev.

- **SlideshowViewLoadTime** – Čas, potreben za nalaganje diaprojekcije.


#### <a name="officepowerpointpptiosrehearseviewrehearsalsummarypage"></a>Office.PowerPoint.PPT.IOS.RehearseView.RehearsalSummaryPage

Dogodek je sprožen, ko je dokončano nalaganje strani s povzetkom. S tem dogodkom določimo učinkovitost delovanja strani s povzetkom. Sporoči trajanje nalaganja strani storitve s povzetkom vaje v odjemalca. Če želite, da je funkcija izvedena, morate obdržati funkcijo.  

Zbrana so sledeča polja: 

- **PayloadCreationTime** – Čas v milisekundah, potreben za ustvarjanje koristne vsebine.  

- **PostUrlCallTime** – Čas v milisekundah, potreben za objavljanje klica URL. 

- **RehearseSessionId** – ID govorne seje z vhodnih vrat. Ta parameter je uporabljen za odpravljanje napak v dnevnikih storitev.  

- **SummaryPageErrorReceived** – logična vrednost, ki označuje, ali je bila stran s povzetkom prejeta oziroma ali je prišlo do napake.

- **SummaryPageHtmlLoadTime** – Čas v milisekundah, potreben za nalaganje summarypageHtml. 

- **SummaryPageLoadStartTime** – Čas v milisekundah, potreben za prejemanje prvega odziva strežnika. 

- **SummaryPageLoadTime** – Čas, potreben za nalaganje strani s povzetkom. To vključuje čas ustvarjanja koristne vsebine. 

- **ThumbnailsCount** – Skupno število sličic, ki bodo sel strani s povzetkom. 


#### <a name="officepowerpointpptiosrehearseviewstartsession"></a>Office.PowerPoint.PPT.IOS.RehearseView.StartSession 
 
Ta dogodek je sprožen, ko uporabnik klikne možnost »Začni sejo«. S tem dogodkom lažje določimo število uporabnikov, ki uporabljajo funkcijo inštrukcij za predstavitelja v sistemu iOS. Skupaj s parametrom Office.PowerPoint.PPT.iOS.RehearseView sporoči število uporabnikov, ki so uspešno dokončali sejo vaje, in število uporabnikov, ki j niso uspešno dokončali. To je naš prvi pokazatelj zrušitve ali napak v funkciji.

Zbrana so naslednja polja:

- Nobeno

#### <a name="officepowerpointpptmacshellprintinfo"></a>Office.PowerPoint.PPT.Mac.Shell.PrintInfo

Ti podatki so zbrani vsakič, ko je dokončan postopek izvoza v obliki datoteke PDF, in vsebujejo informacije o uspešnosti postopka. Te informacije so nujne za prepoznavanje uspešnosti postopkov izvoza v obliki datoteke PDF za našo aplikacijo.

Zbrana so naslednja polja:

- **Data_ExportAsPDFSucceed** – logična vrednost, ki označuje, ali je bil izvoz v obliki datoteke PDF uspešen.

#### <a name="officepowerpointpptsharedrehearseviewrehearseclicked"></a>Office.PowerPoint.PPT.Shared.RehearseView.RehearseClicked

Ta dogodek je zajet ob kliku parametra RehearseWithCoach.  Ta dogodek je uporabljen za analiziranje lijaka »videl-poskusil-obdržal« funkcije. S tem dogodkom ter s preskušenim in ohranjenim dogodkom lažje določimo, ali uporabniki ne bodo več uporabljali lijaka. Tako lažje ohranjamo ustrezno stanje funkcije.

Zbrana so sledeča polja:

- Nobeno


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

Zbrana so sledeča polja:

- **Activity_Name** – Ime dejavnosti »Session«.

- **Activity_CV** – ID za povezovanje dogodkov v seji povezave.

- **Activity_StartStopType** – Začetek.

- **Activity_DateTimeTicks** – Datum in čas dejavnosti.

#### <a name="officesessionactivitystop"></a>Office.Session.Activity.Stop

S tem dogodkom lahko prepoznamo, kdaj se je končala seja orodja za pretakanje podatkov. Uporabljamo ga za zagotavljanje ustreznosti delovanja funkcij in nadzor. Ta dogodek ustvari Microsoftovo orodje za pretakanje podatkov za dodatek za Excel.

Zbrana so sledeča polja:

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


#### <a name="officeuxacccheckeracccheckerfinalviolationcountperrule"></a>Office.UX.AccChecker.AccCheckerFinalViolationCountPerRule

Ta dogodek je sprožen, ko so za trenutno odprt dokument prijavljene težave z dostopnostjo. Ta dogodek predstavlja kršitve dostopnosti (napake, opozorila in namige), ki obstajajo za posamezno pravilo, za odprt dokument na začetku in koncu seje.  Ta dogodek je uporabljen za beleženje števila kršitev dostopnosti (napake, opozorila in namigi) za posamezno opravilo za odprt dokument na začetku in koncu seje.

S podrobnostmi o številu kršitev za posamezno pravilo lahko družba Microsoft identificira, katere težave z dostopnostjo so najpogostejše v Officeovih dokumentih. To je v veliko pomoč pri odpravljanju težav, hkrati pa spodbuja ustvarjanje vključujočega okolja na delovnem mestu in v učilnici za ljudi s posebnimi potrebami.

Zbrana so ta polja:

- **Data_FinalCount_RuleID_0** – število kršitev ID-ja pravila = n, ki ostanejo, ko se je v seji izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_1** – število kršitev ID-ja pravila = n, ki ostanejo, ko se je v seji izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_2** – število kršitev ID-ja pravila = n, ki ostanejo, ko se je v seji izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_3** – število kršitev ID-ja pravila = n, ki ostanejo, ko se je v seji izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_4** – število kršitev ID-ja pravila = n, ki ostanejo, ko se je v seji izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_5** – število kršitev ID-ja pravila = n, ki ostanejo, ko se je v seji izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_6** – število kršitev ID-ja pravila = n, ki ostanejo, ko se je v seji izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_7** – število kršitev ID-ja pravila = n, ki ostanejo, ko se je v seji izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_8** – število kršitev ID-ja pravila = n, ki ostanejo, ko se je v seji izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_9** – število kršitev ID-ja pravila = n, ki ostanejo, ko se je v seji izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_10** – število kršitev ID-ja pravila = n, ki ostanejo, ko se je v seji izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_11** – število kršitev ID-ja pravila = n, ki ostanejo, ko se je v seji izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_12** – število kršitev ID-ja pravila = n, ki ostanejo, ko se je v seji izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_13** – število kršitev ID-ja pravila = n, ki ostanejo, ko se je v seji izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_14** – število kršitev ID-ja pravila = n, ki ostanejo, ko se je v seji izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_15** – število kršitev ID-ja pravila = n, ki ostanejo, ko se je v seji izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_16** – število kršitev ID-ja pravila = n, ki ostanejo, ko se je v seji izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_17** – število kršitev ID-ja pravila = n, ki ostanejo, ko se je v seji izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_0** – število najdenih kršitev ID-ja pravila = n, ko se je v seji prvič izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_1** – število najdenih kršitev ID-ja pravila = n, ko se je v seji prvič izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_2** – število najdenih kršitev ID-ja pravila = n, ko se je v seji prvič izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_3** – število najdenih kršitev ID-ja pravila = n, ko se je v seji prvič izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_4** – število najdenih kršitev ID-ja pravila = n, ko se je v seji prvič izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_5** – število najdenih kršitev ID-ja pravila = n, ko se je v seji prvič izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_6** – število najdenih kršitev ID-ja pravila = n, ko se je v seji prvič izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_7** – število najdenih kršitev ID-ja pravila = n, ko se je v seji prvič izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_8** – število najdenih kršitev ID-ja pravila = n, ko se je v seji prvič izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_9** – število najdenih kršitev ID-ja pravila = n, ko se je v seji prvič izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_10** – število najdenih kršitev ID-ja pravila = n, ko se je v seji prvič izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_11** – število najdenih kršitev ID-ja pravila = n, ko se je v seji prvič izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_12** – število najdenih kršitev ID-ja pravila = n, ko se je v seji prvič izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_13** – število najdenih kršitev ID-ja pravila = n, ko se je v seji prvič izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_14** – število najdenih kršitev ID-ja pravila = n, ko se je v seji prvič izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_15** – število najdenih kršitev ID-ja pravila = n, ko se je v seji prvič izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_16** – število najdenih kršitev ID-ja pravila = n, ko se je v seji prvič izvajal preverjevalnik »acc«.

- **Data_FinalCount_RuleID_17** – število najdenih kršitev ID-ja pravila = n, ko se je v seji prvič izvajal preverjevalnik »acc«.

- **FinalDocID** – končni parameter DocumentID pregledanega dokumenta

- **FinalDocUrlHash** – končni parameter DocumentURLHash pregledanega dokumenta
    
- **InitialDocID** – prvotni parameter DocumentID pregledanega dokumenta

- **InitialDocUrlHash** – prvotni parameter Initial DocumentURLHash pregledanega dokumenta

- **PaneOpened** – logična vrednost, ki spremlja, ali je bilo podokno AccChecker odprto

- **ServerDocID** – DocumentID strežnika za dokument, ki ga je pregledal preverjevalnik dostopnosti


#### <a name="officeuxacccheckeracccheckerviolationinformation"></a>Office.UX.AccChecker.AccCheckerViolationInformation

Ta dogodek je sprožen, ko so za trenutno odprt dokument prijavljene težave z dostopnostjo. Predstavlja združeno število kršitev (napake, opozorila in namigi) za odprt dokument na začetku in koncu seje. Ta dogodek je uporabljen za beleženje združenega števila kršitev dostopnosti (napake, opozorila in namigi) za odprt dokument na začetku in koncu seje. S podatki o uporabi preverjevalnika dostopnosti lahko družba Microsoft izboljša izkušnjo aplikacij tako, da so bolj vključujoče za ljudi s posebnimi potrebami v scenarijih uporabe Officea za delovno mesto in učilnico.

Zbrana so ta polja:
    
- **FinalDocID** – končni parameter DocumentID pregledanega dokumenta

- **FinalDocUrlHash** – končni parameter DocumentURLHash pregledanega dokumenta

- **FinalErrorCount** – končno število napak, ki jih je preverjevalnik dostopnosti javil za dokument

- **FinalIntelligentServiceCount** – končno število težav s pametnimi storitvami, ki jih je preverjevalnik dostopnosti javil za dokument

- **FinalTipCount** – končno število namigov, ki jih je preverjevalnik dostopnosti javil za dokument

- **FinalViolationCount** – končno število kršitev, ki jih je preverjevalnik dostopnosti javil za dokument

- **FinalWarningCount** – končno število opozoril, ki jih je preverjevalnik dostopnosti javil v dokumentu

- **InitialDocID** – prvotni parameter DocumentID pregledanega dokumenta

- **InitialDocUrlHash** – prvotni parameter Initial DocumentURLHash pregledanega dokumenta

- **InitialErrorCount** – število vseh kršitev vrste »Napaka«, ki so bile najdene, ko se je preverjevalnik »acc« prvič izvajal v seji.

- **InitialIntelligentServicesCount** – število vseh kršitev vrste »Pametna storitev«, ki so bile najdene, ko se je preverjevalnik »acc« prvič izvajal v seji.

- **InitialTipCount** – število vseh kršitev vrste »Namig«, ki so bile najdene, ko se je preverjevalnik »acc« prvič izvajal v seji.

- **InitialUrlHash** – število vseh kršitev vrste »Napaka«, ki so bile najdene, ko se je preverjevalnik »acc« prvič izvajal v seji.

- **InitialViolationCount** – število vseh kršitev, ki so bile najdene, ko se je preverjevalnik »acc« prvič izvajal v seji.

- **InitialWarningCount** – število vseh kršitev vrste »Opozorilo«, ki so bile najdene, ko se je preverjevalnik »acc« prvič izvajal v seji.

- **PaneOpened** – logična vrednost, ki spremlja, ali je bilo podokno »Preverjevalnik dostopnosti« odprto

- **ServerDocID** – DocumentID strežnika za dokument, ki ga je pregledal preverjevalnik dostopnosti


#### <a name="officeuxacccheckerbackgroundacccheckerenabledstate"></a>Office.UX.AccChecker.BackgroundAccCheckerEnabledState

Ta dogodek se sproži, ko uporabnik ali skrbnik IT za uporabnika Officea omogoči preverjevalnik »Dostopnost ozadja«. S tem dogodkom so pridobljene informacije o primerkih, ko je preverjevalnik »Dostopnost ozadja« omogočen za uporabnike Officea. Družba Microsoft lahko z omogočenim stanjem preverjalnika »Dostopnost ozadja« razume, ali je mogoče dokumente samodejno pregledati v ozadju. Tako lahko ustvarimo bolj vključujoče okolje na delovnem mestu in v učilnici za ljudi s posebnimi potrebami.

Zbrana so ta polja:

- **BackgroundAccCheckerEnabled** – logična vrednost za spremljanje stanja »Omogočeno/onemogočeno« preverjevalnika »Dostopnost ozadja«


#### <a name="officeuxacccheckerbackgroundscanningcheckboxclicked"></a>Office.UX.AccChecker.BackgroundScanningCheckboxClicked

Ta dogodek se sproži, ko uporabnik v podoknu opravil »Preverjevalnik dostopnosti« omogoči preverjevalnik »Dostopnost ozadja«.  S tem dogodkom so pridobljene informacije o primerkih, ko je preverjevalnik »Dostopnost ozadja« omogočen za Officeove dokumente. Družba Microsoft lahko z omogočenim stanjem preverjalnika »Dostopnost ozadja« razume, ali je mogoče dokumente samodejno pregledati v ozadju. Tako lahko ustvarimo bolj vključujoče okolje na delovnem mestu in v učilnici za ljudi s posebnimi potrebami.

Zbrana so ta polja:
    
- **FinalBackgroundScanningState** – prvotno stanje potrditvenega polja, ki omogoča pregledovanje ozadja

- **InitialBackgroundScanningState** – prvotno stanje potrditvenega polja, ki omogoča pregledovanje ozadja


#### <a name="officeuxacccheckerdisabledresults"></a>Office.UX.AccChecker.DisabledResults

Ta dogodek je sprožen, ko je za odprt dokument onemogočen preverjevalnik dostopnosti. Ta dogodek je uporabljen za pridobivanje podatkov o tem, ali je Officeov preverjevalnik dostopnosti onemogočen zaradi podedovanega ali nepodprtega Officeovega dokumenta. Z onemogočenim stanjem preverjevalnika dostopnosti lahko družba Microsoft razume, kako pogosto ni mogoče pregledati dokumenta, hkrati pa uporabnikom omogoča pregledovanje tovrstnih dokumentov s pretvorbo v sodobnejšo obliko zapisa. Tako lahko ustvarimo bolj vključujoče okolje na delovnem mestu in v učilnici za ljudi s posebnimi potrebami.

Zbrana so ta polja:
    
- **Data_Disabled_ID** – ID napake »Onemogočeno«

- **Data_Disabled_Reason** – razlog za onemogočanje preverjevalnika dostopnosti

- **Data_IsUpConvertEnabled** – spremlja, ali je pretvorba v višjo ločljivost na voljo za dokument


#### <a name="officeuxacccheckershowtaskpane"></a>Office.UX.AccChecker.ShowTaskPane

Ta dogodek se sproži, ko je za trenutno odprt dokument zagnano podokno opravil »Preverjevalnik dostopnosti«.  Ta dogodek je uporabljen za razumevanje uporabe Officeovega preverjevalnika dostopnosti. Preverjevalnik dostopnosti je uporabljen za identifikacijo in odpravljanje težav z dostopnostjo v Officeovih dokumentih. S podatki o uporabi preverjevalnika dostopnosti lahko družba Microsoft izboljša izkušnjo aplikacij tako, da so bolj vključujoče za ljudi s posebnimi potrebami v scenarijih uporabe Officea za delovno mesto in učilnico.

Zbrana so ta polja:

- **BackgroundScanCheckboxEnabled** – spremlja, ali je omogočen preverjevalnik dostopnosti ozadja
    
- **Column** – namen

- **DocUrlHash** – enolično razpršen ID dokumenta, ki je bil pregledan

- **HasAccessibilityViolations** – spremlja, ali so bile v dokumentu morebitne kršitve dostopnosti v trenutku, ko je bilo podokno odprto

- **IsPaneDisabled** – spremlja, ali je podokno »Preverjevalnik dostopnosti« odprto v onemogočenem stanju (podedovano ali nepodprt dokument)

- **PaneOpenedBefore** – spremlja, ali je bilo podokno »Preverjevalnik dostopnosti« prej odprto

- **WAC_ServerDocId** – ID dokumenta v strežniku za dokument, ki je bil pregledan


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

- **Data_PartsUnknown** – število delov dokumenta, za katere nismo uspeli pridobiti podatkov. 

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

- **Data_Doc_AsyncOpenKind –** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

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

    

#### <a name="officewordfilesaveactfconfirmsavedoccorequerysave"></a>Office.Word.FileSave.ActFConfirmSaveDocCoreQuerySave

Ta dogodek označuje, da Office Word pozove uporabnika k shranjevanju sprememb, ko ta poskuša zapreti dokument. Z njim Microsoft nadzira ustreznost delovanja funkcije shranjevanja dokumenta ob zapiranju ter tako prepreči morebitno izgubo podatkov v dokumentih. Dogodek nadzira, ali način shranjevanja ob zapiranju ustrezno deluje. Ta dogodek uporabljamo tudi za ocenjevanje števila mesečnih aktivnih uporabnikov/naprav in za metriko zanesljivosti v oblaku.

Zbrana so sledeča polja:

- **Data_AddDocTelemRes** – poroča, ali lahko pravilno dopolnimo druge vrednosti dogodka, povezane s telemetrijo dokumenta. Uporablja se za diagnostiko kakovosti podatkov.

- **Data_DetachedDuration** – koliko časa je bila dejavnost ločena od niti.

- **Data.Doc.AccessMode** – dokument je samo za branje/ga je mogoče urejati.

- **Data_Doc_AssistedReadingReasons** – nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

- **Data_Doc_AsyncOpenKind –** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

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

- **Data_Doc_AsyncOpenKind –** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

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

- **Data_DstDoc_AsyncOpenKind –** označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.
    
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

- **Data_SrcDoc_AsyncOpenKind –** označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

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



#### <a name="onenoteappnavigationratingreminderdialogshown"></a>OneNote.App.Navigation.RatingReminderDialogShown

Kritični signal, ki se uporablja za merjenje učinkovitosti sprožitvene logike za oceno opomina. To pogovorno okno se prikaže, ko uporabnik izpolnjuje vse pogoje, če si želite ogledati opomin za oceno (ne. aktivne dni, je ocenjeno prej ali ne, itd.). S tem zagotovite, da je argument» sprožitvena logika «za bonitetni opomin. Če bodo uporabniki videli to pogovorno okno, nam bodo posredovali načine za sprejemanje povratnih informacij strank ob pravem času in izboljšali stanje aplikacije.

Zbrana so naslednja polja:

- Nobeno

#### <a name="parselicenseop"></a>ParseLicenseOp

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij.  Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede operacija razčlenjevanja dovoljenj. 

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se aplikacija izvaja v produkcijskem okolju ali v okolju razvijalcev

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

#### <a name="readconversation"></a>read.conversation

Uporablja se za nadzor morebitnih negativnih učinkov na stanje in učinkovitost upodabljanja e-poštnega sporočila.

Zbrana so sledeča polja: 

- **above_40fps** – število okvirjev, upodobljenih nad 40 slik/s
 
- **above_50fps** – število okvirjev, upodobljenih nad 50 slik/s
 
- **above_55fps** – število okvirjev, upodobljenih nad 55 slik/s

- **adal_id** – ID za preverjanje pristnosti imenika Active Directory računa, enolični identifikator v Microsoftovem sistemu za preverjanje pristnosti 

- **component_name** – ime komponente/pogleda, ki je aktiven med filtriranjem

- **event_mode** – mesto v aplikaciji, kjer je uporabnik začel pogovor (skupina ali drugo).

- **internet_message_id** – ID sledenja za zadnje sporočilo v pogovoru.
      
- **orientation** – usmerjenost zaslona ob dogodku (pokončna ali ležeča).

- **recent_message_id** – ID zadnjega sporočila v pogovoru.

- **suggested_reply_state** – Stanje predlaganih odgovorov za ta pogovor (ni na voljo, na voljo, prikazano, uporabljeno ali zavrženo).

- **suggested_reply_types** – Označuje vrsto in število predlaganih odgovorov, prikazanih/uporabljenih za ta pogovor. To je slovar. Na primer {text: 2, send_avail: 1}.
  
- **total_count** – skupno število okvirjev, ki jih prikaže komponenta.
 
- **view_duration** – čas, ko si je uporabnik ogledoval komponento.

#### <a name="saveattempt"></a>save.attempt

Omogoča, da določimo vpliv težav, ki jih povzročijo uporabniki pri poskusih shranjevanja datoteke, tako, da ocenimo število prizadetih sej in prepoznamo morebitne skupne značilnosti teh sej.

Zbrana so sledeča polja: 

- **file_type** – vrsta datoteke, ki jo je uporabnik poskusil shraniti (na primer. doc).

- **origin** – izvor poskusa shranjevanja datoteke (npr. iz e-pošte), s katerim lahko zaznamo težave, povezane s shranjevanjem datoteke iz določenega mesta v aplikaciji.

- **token_type** – vrsta žetona, uporabljenega za preverjanje pristnosti računa za shranjevanje datoteke, s katero zaznavamo težave pri preverjanju pristnosti, povezane s shranjevanjem datoteke.

#### <a name="searchsubtabselected"></a>search.subtab.selected

Dogodek zbira točke izvora, zakaj je bil izbran podzavihek »sub_tab« iskanja. Podzavihki so na voljo v vrstici za iskanje primarne aplikacije za filtriranje podatkov. S tem dogodkom lahko spremljamo tablete vrste entitete (vse, pošta, stiki in koledar), ki jih uporabniki uporabljajo, ko izvajajo svoja iskanj. Tako lahko poskrbimo, da mehanizmi filtrov iskanja delujejo pravilno.

Zbrana so sledeča polja:

- **properties_general** – splošne lastnosti, ki jih zbira dogodek »all Aria«

- **selected_reason** – Vzrok za izbor tabletke vrste, ki je lahko ena teh treh vrednosti (glif, ki je ikona): tap_on_header, tap_on_see_all, enter_search_mode, mail_glyph, calendar_glyph.

- **subtab_type** – Izbrana tabletka vrste, ki je lahko ena od teh štirih vrednosti: vse, pošta, stik, dogodek.

#### <a name="sendmessage"></a>send.message

Uporablja se za nadzor morebitnih negativnih učinkov na učinkovitost in stanje pošiljanja e-poštnih sporočil.

Zbrana so sledeča polja:
  
- **account** – spremlja račun, v katerem se je izvedlo dejanje

- **compose_duration** –spremlja skupni čas, ki ga je uporabnik porabil za sestavljanje sporočila, vključno s sejo z več osnutki.

- **draft_message_id** – spremlja ID sporočila za sestavljanje poslanega sporočila.

- **event_mode** – spremlja način dogodka, če je na voljo za sporočilo (»skupine« ali »drugo«)

- **has_attachment** – označuje, ali sporočilo vsebuje priponke.

- **has_mip_label** – označuje, ali je sporočilo označeno z oznako MIP.

- **is_group_escalation** – ali gre za stopnjevano sporočilo skupine. »Stopnjevano sporočilo« je sporočilo, poslano v nabiralnik uporabnika zaradi stopnjevanja (naročnina na skupino).

- **is_groups** – spremlja, ali je poslano sporočilo vrste »sporočilo skupine«.

- **key_stroke_count** – spremlja število pritiskov tipk za sporočilo, ki ga želite poslati.

- **message_id** – spremlja ID sporočila, na katerega želite odgovoriti ali ga posredovati.

- **origin** – ponazarja mesto začetka ustvarjanja sporočila, denimo novo, odgovor, hitri odgovor itd.

- **send_draft_origin** – ponazarja mesto začetka pošiljanja, denimo ustvari ali hitri odgovor

- **smart_compose_model_version** – spremlja, katero različico modela Smart sestavite uporabljamo

- **source_inbox** – ponazarja vrsto izvirnega nabiralnika za referenčno sporočilo. 

- **suggested_reply_state** – zajem stanja predlaganega odgovora za to poslano sporočilo, denimo ni na voljo, na voljo, prikazano, uporabljeno, zavrženo

- **suggested_reply_types** – Označuje vrsto in število predlaganih odgovorov, prikazanih/uporabljenih za to poslano e-poštno sporočilo. To je slovar. Na primer {text: 2,  send_avail: 1}.

- **suggestions_requested** – Označuje, koliko predlogov za pametno sestaviti je bilo zahtevano

- **suggestions_results** – Smart sestavite rezultate, tj. sprejeto, zavrnjeno

- **suggestions_returned** – označuje, koliko pametnih predlogov za sestavljanje je vrnjenih iz strežnika

- **suggestions_shown** – označuje, koliko pametnih predlogov za sestavljanje je prikazano uporabniku

- **thread_id** – ponazarja ID niti za pogovor, ki ga želite posredovati ali odgovoriti nanj.

#### <a name="session"></a>session

Omogoča nam zaznavanje in odpravljanje primerov, kjer uporabljamo prevelik odstotek baterije vaše naprave, ter nam pomaga prepoznati morebiten vzrok.

Zbrana so sledeča polja: 

- **battery_level** – ponazarja raven baterije v naravi, s katero lahko zaznamo, kdaj naša aplikacija negativno vpliva na stanje baterije vaše naprave.

- **has_hx** – dogodek, ki ponazarja, da račun uporablja našo novo storitev sinhronizacije, s katerim je mogoče zaznati težave, ki jih povzroči naša storitev sinhronizacije.

- **Session.Duration** – dolžina seje v sekundah

- **Session.DurationBucket** – časovni okvir trajanja *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar je lahko še vedno prikazano v starejših graditvah.]*

- **Session.FirstLaunchTime** – prvi zabeleženi čas zagona aplikacije *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar je lahko še vedno prikazano v starejših graditvah.]*

- **Session.State** – indikator začetka ali konca seje

#### <a name="settingsaction"></a>settings.action

Ta dogodek zbere informacije o konfiguraciji v nastavitvah. Podatki nam omogočajo, da zaznamo primere, kjer je možno negativno vplivanje na sposobnost uporabnikov, Konfigurirajte nastavitve aplikacije, na primer nastavitve obvestil, primarni poštni račun in konfiguracijo e-poštnega podpisa.

Zbrana so sledeča polja: 

- **account_order_changed** – preveri, ali ste spremenili vrstni red računov, in zagotovi, da ta konfiguracija deluje pravilno. 

- **action** – morebitna dejanja, izvedena v nastavitvah, kot je brisanje računa, ki so nam v pomoč pri zaznavanju težav in zagotavljanju, da ni negativnega učinka.

- **auth_type** – vrsta preverjanja pristnosti, ki ga uporablja račun, za razumevanje uporabljene plasti sinhronizacije v zaledju pri diagnosticiranju težav. 

- **changed_folder** – ponazarja, ali je bila spremenjena mapa, in nam pomaga diagnosticirati težave. 

- **delete_scope** – ali je bil med brisanjem računa račun izbrisan iz te naprave ali iz vseh naprav v Outlooku.  

- **enabled_state** – ali so pravilno konfigurirane nastavitve za samodejne odgovore, shranjevanje stikov in blokiranje zunanjih slik.  

- **notification_action** – če želite preveriti, ali ste konfigurirali kakšno dejanje obvestila za Triaging e-poštna sporočila, ki nam bodo v pomoč pri zagotavljanju, da ta nastavitev deluje uspešno 

- **notification_action_number** – če želite preveriti, ali so dejanja obvestila (dejanje ena ali dejanje dve) pravilno konfigurirana

- **server_type** – podobno kot dogodek auth_type, nam pove, katero vrsto računa imate, in nam pomaga pri boljšem diagnosticiranju težav.  Primeri: Office365, Gmail, Outlook

- **setting_properties** – sledi lastnosti glede na to, kaj je opisano spodaj: 
   - **alternate_app_icon_setting** – izbrana ikona nadomestnega programa (svetlo, temno)
   - **auth_type** – ponazarja vrsto preverjanja pristnosti v zaledju, s katero zaznamo, ali je prišlo do težave z določeno vrsto računa.
   - **badge_count_state** – ponazarja vrsto štetja značk, ki jo je zahteval uporabnik, denimo brez značk, samo nabiralnik v fokusu itd. 
   - **changed_folder** – določa, ali je bilo to dejanje arhivirano, načrtovano oz. je bilo izvedeno drugo dejanje.
   - **delete_scope** – spremlja, ali je bilo to dejanje povezano z brisanjem samo v tej napravi ali v vseh napravah (če je to ustrezno). 
  - **enabled_state** – ali je omogočeno stanje, povezano z dejanjem.
  - **in_app_language** – izbrani jezik v aplikaciji, vrsta niza (privzeto, en-US, FA, ru ipd.)
  - **notification_action_setting** – označuje podrobnosti o nastavitvah dejanja obvestila, ki so povezane s tem dejanjem, če je to mogoče.
    - **notification_action** – označuje, kaj je uporabnik poskušal narediti (dodati zastavico, izbrisati arhivirati). Ta dogodek nam omogoča, da določimo dejanje sporočila, ki ga je uporabnik želel izvesti v obvestilu, in če je dejanje morda spodletelo. 
    - **notification_action_number** – označuje, katera številka dejanja (dve od treh dejanj sta prilagodljivi), je bila dodeljena dejanje obvestila, denimo prvi dejanje, drugo dejanje. To nam omogoča, da ugotovite, ali je prišlo do težave z določenim dejanjem.
   - **notification_state** – ponazarja vrsto štetja značk, ki jo je zahteval uporabnik, na primer brez značk, samo nabiralnik v fokusu itd.
   - **server_type** – ponazarja vrsto strežnika v zaledju, s katero zaznamo, ali je prišlo do težave z določeno vrsto strežnika.
   - **source** – ponazarja vir obvestil nastavitev, če je to ustrezno, ali za nastavitev »Ne motite«.
   - **swipe_setting** – ponazarja podrobnosti nastavitev podrsljajev, povezane s tem dejanjem (če so na voljo).
     - **swipe_action** – ponazarja dejanje, ki ga je poskušal izvesti uporabnik, na primer dodajanje zastavice, brisanje, arhiviranje. Omogoča nam, da ugotovimo, katero dejanje je uporabnik želel izvesti in ali je bilo to opravilo uspešno. 
     - **swipe_direction** – ponazarja nastavljeno smer za poteze podrsljajev, na primer od leve proti desni ali od desne proti levi. S tem dogodkom lahko ugotovimo, ali je prišlo do težave z določeno smerjo podrsljaja.
   - **temperature_unit_setting** – izbrana enota temperature, ki bo jena za vreme 
   - **theme_color_setting** – barva aplikacije po meri, ki jo je izbral uporabnik 
   - **ui_mode_setting**– izbrani način uporabniškega vmesnika (temni, svetli, privzeti način, način nizke napolnjenosti baterije itd.).
   - **signature_setting** – ponazarja, ali je bila nastavitev uporabljena za vse račune ali samo za posamezni račun.

- **state_changed_to** – preveri, ali je nastavitev za vklop/izklop nabiralnika v fokusu pravilno nastavljena. 

- **swipe_action** – preveri, ali imate za triažo e-poštnih sporočil nastavljena dejanja podrsavanja. S tem dogodkom preverimo, ali ta nastavitev deluje pravilno. 

- **swipe_direction** – preveri, ali sta smeri podrsljajev (v levo ali desno) nastavljeni pravilno.


#### <a name="sidebaraction"></a>sidebar.action

Omogoča nam, da odkrijemo primere morebitnega negativnega učinka na vašo zmožnost konfiguracije nastavitev aplikacije, na primer nastavitve obvestil, vaš primarni e-poštni račun in konfiguriranje vašega e-poštnega podpisa.

Podatkovna polja, ki so pogosta za Outlook Mobile za ta dogodek v napravah s sistemom iOS in Android:

- **Račun** – sledi računu in podatkom, povezanim z dogodkom, vrednosti, ki so sledene v teh podatkih, so v skupnem gradivu om Field *[to polje je bilo odstranjeno iz tekočih različic Officea, vendar se lahko še vedno prikaže v starejših različicah.]*

- **action** – spremlja vrsto izvedenega dejanja stranske vrstice, na primer zavrženo, izbran gumb pomoči, stranska vrstica pošte itd. 

- **from_favorites** – spremlja, ali je bilo dejanje izvedeno iz priljubljenega elementa. 

- **mail_folder_type** – vrsta izbrane mape med dejanjem stranske vrstice (če je bilo to izvedeno).

- **sidebar_type** – spremlja vrsto stranske vrstice, povezane s tem dogodkom, na primer pošta ali koledar. S tem dogodkom lahko zagotovimo pravilno delovanje nastavitve priljubljenih.

Zbrana so naslednja polja: 

- **account_type** – ponazarja vrsto računa za preverjanje pristnosti, na primer Gmail, Outlook itd. 

- **account_has_groups** – s tem dogodkom preverimo, ali so v računu skupine in ali so nastavljeno pravilno.

- **calendar_accounts_count** – ponazarja število računov koledarja. S tem dogodkom preverimo, ali so vaši računi koledarja nastavljeni pravilno. 

- **calendar_apps_count** – ponazarja število aplikacij koledarja. S tem dogodkom preverimo, ali so vaše aplikacije koledarja nastavljene pravilno. 

- **calendar_type** – ponazarja vrsto koledarja (primarni koledar, koledar skupine itd.). 

- **has_favorite_folders** – s tem preverimo, ali so priljubljene mape pravilno nastavljene. 

- **has_favorite_people** – s tem preverimo, ali so priljubljene osebe/priljubljeni stiki pravilno nastavljeni. 

- **has_group_calendar** – s tem preverimo, ali imate koledarje skupine in ali so ti pravilno nastavljeni. 

- **has_group_calendar_account** – s tem preverimo, ali imate koledarje skupine in ali so ti pravilno nastavljeni. 

- **has_group_toggled** – s tem preverimo, ali ste preklopili na koledarje skupine in ali je ta nastavitev pravilno nastavljena. 

- **interesting_calendars_accounts_count** – ponazarja število zanimivih računov koledarja. S tem dogodkom preverimo, ali so vaši računi zanimivih koledarjev nastavljeni pravilno. 

- **mail_accounts_count** – skupno število e-poštnih računov v stranski vrstici. S tem preverimo, ali je ta nastavitev nastavljena pravilno. 

- **mail_folder_type** – vrsta mape, ki jo je izbral uporabnik. S tem preverimo, ali je ta nastavitev nastavljena pravilno. Vključuje lahko mape z izbrisanimi elementi, neželeno pošto ali poslanimi elementi. 

- **mail_inbox_unread_count** – s tem zagotovimo, ali je število neprebranih sporočil prikazano in nastavljeno pravilno. 

- **mail_subfolder_depth** – s tem zagotovimo, da lahko uspešno prikažemo konfiguracije podmape za pošto uporabnika.

#### <a name="storeop"></a>StoreOp

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij.  Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede operacija shranjevanja dovoljenj storitev za upravljanje pravic. 

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se aplikacija izvaja v produkcijskem okolju ali v okolju razvijalcev

- **AppInfo.Name** – ime aplikacije.

- **AppInfo.Version** – različica aplikacije

- **iKey** – ID strežnika za storitev pisanja dnevnika

- **RMS.ApplicationScenarioId** – ID scenarija, ki ga je posredovala aplikacija

- **RMS.ContentId** – ID vsebine v licenci končnega uporabnika

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

#### <a name="watchappv2"></a>watchAppV2

S tem dogodkom lahko zaznamo in odpravimo morebitne zmogljivostne težave v vaši napravi Apple Watch, kot so prejemanje obvestil ali odgovarjanje na e-poštna sporočila.

Zbrana so sledeča polja: 

- **app_action** – ponazarja vrste dejanj, ki jih je uporabnik izvedel v napravi Apple Watch, npr. »archive_message«. S tem dogodkom lahko zaznamo težave, povezane z določenim dejanjem, kot je neuspešno arhiviranje sporočil v napravi Apple Watch.

- **is_watch_app_installed** – ponazarja, ali je uporabnik v napravo namestil aplikacijo Apple Watch.

- **is_complication_enabled** – ponazarja, ali je uporabnik na zaslon naprave Apple Watch dodal Outlook. S tem dogodkom lahko zaznamo težave, povezane z zasloni naprave Apple Watch.

- **watch_os** – ponazarja nameščeno različico operacijskega sistema za napravo Apple Watch. S tem dogodkom lahko zaznamo težave, povezane z določenimi različicami operacijskega sistema za napravo Apple Watch.


### <a name="application-status-and-boot-subtype"></a>*Stanje aplikacije in podvrsta zagona*

Določanje, ali je prišlo do specifičnih dogodkov funkcije, kot sta zagon ali zaustavitev, in funkcije, ki se izvaja.

#### <a name="appstartup"></a>app.startup

S tem dogodkom lahko zaznavamo težave in jih odpravljamo, ko Outlook začne delovati počasneje ali neobičajno, kar uporabnikom otežuje uporabo aplikacije.  Dogodek vključuje informacije o posebnih omogočenih lastnosti in o tem, kako dolgi so posamezni deli zagona.

Zbrana so sledeča polja: 

- **attach_base_context_millis** – čas med zagonom osnovnega konteksta in funkcije onCreate().

- **device_ram_in_mb** – RAM, ki je na voljo v napravi.

- **has_company_portal** – ponazarja, ali je nameščena aplikacija portala podjetja.

- **hx_okhttp_mode** – ali komponenta nove storitve za sinhronizacijo e-pošte uporablja način OKHttp za pošiljanje in prejemanje omrežnih zahtev, ki temeljijo na protokolu HTTP.

- **initial_activity_name** – dejavnost sistema Android, ki je zagnala aplikacijo

- **manufacturer** – proizvajalec naprave.

- **model** – model naprave.

- **on_create_millis** – čas, zahtevan za funkcijo onCreate().

- **on_resume_millis** – čas, zahtevan za funkcijo onResume().

- **time_until_attach** – čas med nalaganjem razreda in zagonom osnovnega konteksta.

- **total_millis** – skupni čas od začetka nalaganja razreda do dokončanja nadaljevanja dejavnosti v sistemu Android.

#### <a name="boottime"></a>boot.time 

S tem dogodkom lahko zaznamo, kdaj se pojavijo kritične napake aplikacije, ki lahko povzročijo zrušitev aplikacije ali resne težave, kot so prazne vrstice v vašem nabiralniku. Ta dogodek zbira informacije, s katerimi lahko kategoriziramo in razvrščamo težave pri dodeljevanju prioritet za učinke težav na uporabnike.

Zbrana so sledeča polja:

- **black_list_reason** – prikaže, ali je na voljo razlog, da prezremo te podatke. Nekateri primeri vključujejo zagon zaradi oddaljenega obvestila in zagon zaradi pridobivanja v ozadju.

- **step_premain** – Sporoča, koliko časa je Outlook potreboval od trenutka, ko je uporabnik tapnil ikono do »glavnega« koraka step0_main, določenega v tem dokumentu.

- **step0_main** – Prikaže čas, zahtevan, da je Outlook prešel na korak »main«, ki ga je določila družba Apple.

- **step1_appWillFinishLaunching** – prikaže čas, zahtevan, da je Outlook iz koraka »main« prešel na korak »appWillFinishLaunching«, ki ga je določila družba Apple.

- **step2_appDidFinishLaunching** – prikaže čas, zahtevan, da je Outlook iz koraka »appWillFinishLaunching« prešel na korak »appDidFinishLaunching«, ki ga je določila družba Apple.

- **step3_engineStarted** – prikaže čas, zahtevan, da je Outlook iz koraka »appDidFinishLaunching« prešel na zagon mehanizma aplikacije, ki obravnava shranjevanje in sinhronizacijo podatkov.

- **step4_runLoopFirstIdle** – prikaže čas, zahtevan, da je Outlook iz koraka» engineStarted « prešel na stanje, v katerem dodatno delo ni več potrebno.

- **total_time** – prikaže skupni čas, ki ga je Outlook potreboval za dokončanje zagona.

#### <a name="dnslookupop"></a>DnsLookupOp

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij.  Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede operacija iskanja informacij o strežniku DNS. 

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se aplikacija izvaja v produkcijskem okolju ali v okolju razvijalcev

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

#### <a name="firstvisible"></a>first.visible

Ta dogodek nam sporoča, ko uporabnik prvič interno zažene aplikacijo. Ta dogodek potrebujemo zato, da lahko poskrbimo uspešno delovanje aplikacije v graditvah proizvajalca strojne opreme (OEM).

Zbrana so sledeča polja:

- **is_oem** – sledenje polja, ki označuje, ali se aplikacija izvaja v različici OEM

- **is_system_install** – polje, ki spremlja prisotnost vnaprej nameščene datoteke lastnosti, ki bi morala označevati, da je ta graditev OEM 

- **manufacturer** – proizvajalec naprave

- **model** – model naprave

- **systemFlagSet** – vrednost zastavice sistema Android (ApplicationInfo.FLAG_SYSTEM), ki označuje, ali je bila aplikacija nameščena kot del slike sistema naprave

#### <a name="getuserop"></a>GetUserOp

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij.  Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede operacija pridobivanja uporabniških dovoljenj. 

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se aplikacija izvaja v produkcijskem okolju ali v okolju razvijalcev

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

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se aplikacija izvaja v produkcijskem okolju ali v okolju razvijalcev
    
- **AppInfo.Name** – ime aplikacije

- **AppInfo.Version** – različica aplikacije

- **iKey** – ID strežnika za storitev pisanja dnevnika

- **RMS.ApplicationScenarioId** – ID scenarija, ki ga je posredovala aplikacija

- **RMS.CallBackStatus** – stanje rezultata povratnega klica za preverjanje pristnosti

- **RMS.CallbackTime** – čas, porabljen za povratni klic za preverjanje pristnosti 

- **RMS.CorrelationId** – ID korelacije za zahtevo HTTP

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

#### <a name="initialized"></a>Initialized

Omogoča nam analizo stanja vmesnika, s katerim lahko mobilne aplikacije iz Officeovih storitev pridobivajo nastavitve uporabnikov in zasebnosti ter diagnosticirajo težave z nastavitvijo povezljivosti in zasebnosti.

Zbrana so sledeča polja:

- **roamingSettingType** – prepozna mesto, s katerega smo poskušali prebrati nastavitve.

#### <a name="ipccreateoauth2token"></a>IpcCreateOauth2Token

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij. Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede priklic API IpcCreateOauth2Token API.

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se aplikacija izvaja v produkcijskem okolju ali v okolju razvijalcev
    
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


#### <a name="officeandroidaccountstorageinfo"></a>Office.Android.AccountStorageInfo

V tem primeru določite število računov MSA in ADAL v nastavitvah registra in v skupni rabi. Omogoča analizo neskladij med trgovinami s podatki in nam pomaga stabilizirati učinkovitost delovanja aplikacije.

Zbrana so naslednja polja:

- **RegistryADALCount**– označuje število ADAL računov v registru.

- **RegistryLiveIdCount**– označuje število računov MSA v registru.

- **SharedPrefADALCount**– označuje število ADAL računov v možnostih v skupni rabi.

- **SharedPrefLiveIdCount**– označuje število računov MSA v možnostih v skupni rabi.


#### <a name="officeandroidandroidoffice16bootlatency"></a>Office.Android.AndroidOffice16BootLatency

Ključnega pomena za zajem meritev učinkovitosti delovanja aplikacije glede na odzivni čas aplikacije od zagona.  Microsoft s tem dogodkom zbira čas, zahtevan za odzivnost aplikacije, in za zaznavanje scenarijev, ki lahko vplivajo na čas zagona v aplikacijah Word, Excel ali PowerPoint..

Zbrana so naslednja polja:

- **AppLaunchResponsiveTimeInMilliSec** – Čas odzivnosti pri zagonu aplikacije.

- **AppSuspendedDuringBoot** – Logična vrednost, ki označuje, ali je bila aplikacija prekinjena med zagonom.

- **CollectionTime** – Čas dogodka.

- **FileActivationAttempted** – Logična vrednost, ki označuje, ali je prišlo do poskusa aktivacije datoteke.

- **FirstIdleOnAppThreadTimeInMilliSec** – Čas nedejavnosti za nit aplikacije.

- **IsThisFirstLaunch** – Logična vrednost, ki označuje, ali je to zagon aplikacije.

- **UserDialogInterruptionDuringBoot** – Logična vrednost, ki označuje, ali je med zagonom prišlo do blokiranja uporabniškega vmesnika.

#### <a name="officeextensibilityofficejsappactivated"></a>Office.Extensibility.OfficeJS.Appactivated

Zapiše informacije o nepričakovanih zaustavitvah v Officeu. Tako lahko prepoznamo zrušitve ali neodzivanja izdelka in ustrezno ukrepamo.

Zbrana so naslednja polja:

  - **Data\_AirspaceInitTime:integer –** Čas, zahtevan za inicializacijo Officeove komponente Airspace.

  - **Data\_AllShapes:integer –** število oblik v dokumentu

  - **Data\_APIInitTime:integer –** čas, zahtevan za inicializacijo modula Visio API

  - **Data\_AppSizeHeight –** višina okna za dodatek **-**

  - **Data\_AppSizeWidth –** širina okna za dodatek **-**

  - **Data\_AppURL –** URL dodatka; zapiše polni URL za dodatke iz trgovine in domeno URL-ja za dogodke, ki jih niste pridobili iz trgovine

  - **Data_Doc_AsyncOpenKind:long –** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

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

  - **Data\_Doc\_IsSyncBacked:bool –** ima vrednost »true«, če gre za dokument strežnika, ki je na voljo lokalno in je sinhroniziran s strežnikom (npr. prek storitve OneDrive ali odjemalskih aplikacij ODB)

  - **Data\_Doc\_Location:long-**: nabor vnaprej določenih vrednosti za mesto shranjevanja dokumenta (lokalno, SharePoint, WOPI, omrežje itd.)

  - **Data\_Doc\_LocationDetails:long –** nabor vnaprej določenih vrednosti podrobnejše lokacije (mapa »Začasno«, mapa »Prenosi«, dokumenti storitve One Drive, slike storitve One Drive)

  - **Data\_Doc\_ResourceIdHash:string –** razpršitev identifikatorja vira za dokumente, shranjene v oblaku

  - **Data_Doc_RtcType –**  označuje, kako je bil kanal v realnem času (RTC) nastavljen za trenutno datoteko (onemogočeno, nepodprto, na zahtevo, vedno vklopljeno itn.).

  - **Data\_Doc\_ServerDocId:string –** nespremenljivi identifikator za dokumente, shranjene v oblaku

  - **Data\_Doc\_SessionId:long –** ustvarjeni GUID, ki prepozna primerek dokumenta v seji istega procesa

  - **Data\_Doc\_SizeInBytes:long –** velikost dokumenta v bajtih

  - **Data\_Doc\_SpecialChars:long –** dolga bitna maska, ki ponazarja posebne znake v URL-ju ali poti dokumenta

  - **Data\_Doc\_SyncBackedType** – Indikator vrste dokumenta (lokalno ali storitev). 

  - **Data\_Doc\_UrlHash:string –** razpršitev polnega URL-ja za dokumente, shranjene v oblaku

  - **Data\_DpiAwarenessTime:integer –** čas, zahtevan za omogočanje zaznavanja ločljivosti (DPI) na monitor

  - **Data\_DurationToCompleteInMilliseconds:double –** čas, zahtevan za dokončanje shranjevanja, v milisekundah

  - **Data\_ErrorCode:int –**: 0 za uspešno, celo število za neuspešno shranjevanje

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

  - **Data\_HasCoauthUserEdit:bool –** ima vrednost »true«, če je bil dokument urejen v seji soavtorstva

  - **Data\_HasCustomPages:bool –** ima vrednost true, če dokument vsebuje strani po meri

  - **Data\_HasCustPatterns:bool –** ima vrednost true, če datoteka vsebuje vzorce po meri

  - **Data\_HasDynConn:bool –** ima vrednost true, če dokument vsebuje dinamično povezavo

  - **Data\_HasScaledPages:bool –** ima vrednost true, če dokument vsebuje strani s spremenjenimi stranmi

  - **Data\_HasUserWaitTime:bool –** ima vrednost true, če se med shranjevanjem prikaže pogovorno okno datoteke

  - **Data\_InitAddinsTime:integer –** čas, zahtevan za inicializacijo in nalaganje dodatka COM

  - **Data\_InitBrandTime:integer –** Čas, zahtevan za inicializacijo pozdravnega zaslona in zaščitenih Officeovih komponent.

  - **Data\_InitGimmeTime:integer –** Čas, zahtevan za inicializacijo Officeove komponente.

  - **Data\_InitLicensingTime:integer –** Čas, zahtevan za inicializacijo za licenciranje Officeove komponente.

  - **Data\_InitMsoUtilsTime:integer –** Čas, zahtevan za inicializacijo Officeove komponente MSOUTILS.

  - **Data\_InitPerfTime:integer –** Čas, zahtevan za inicializacijo Officeove komponente za učinkovitost delovanja.

  - **Data\_InitTCOTime:integer –** Čas, zahteva za inicializacijo upravitelja za Officeove komponente.

  - **Data\_InitTrustCenterTime:integer –** Čas, zahtevan za inicializacijo središča za zaupanje Officeove komponente.

  - **Data\_InitVSSubSystemsTime:integer –** čas, zahteva za inicializacijo Visiovih komponent

  - **Data\_InternalFile:bool –** ima vrednost true, če gre za notranjo datoteko, na primer šablona

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

  - **Data\_LoadProfileTime:integer –** Čas, zahtevan za nalaganje Officeovega orodja za spremljanje delovanja.

  - **Data\_LoadRichEditTim:integer –** čas, zahtevan za nalaganje komponente z obogatenimi vnosi

  - **Data\_LoadVisIntlTime:integer –** čas, zahtevan za nalaganje Visiove mednarodne knjižnice DLL

  - **Data\_Location:integer –** mesto za odpiranje datoteke; 0 lokalno, 1 omrežje, 2 SharePoint, 3 splet

  - **Data\_MasterCount:integer –** število nadrejenih elementov v diagramu

  - **Data\_MaxCoauthUsers:integer –** največje dovoljeno število uporabnikov, ki sourejajo v seji Filesystem, Registry, First Party, SDX

  - **Data\_MaxTilesAutoSizeOn:integer –** največje dovoljeno število naslovov strani, za katero je omogočeno samodejno spreminjanje velikosti

  - **Data\_MsoBeginBootTime:integer –** čas zagona za MSZN

  - **Data\_MsoDllLoadTime:integer –** čas, zahtevan za nalaganje knjižnice DLL MSZN

  - **Data\_MsoEndBootTime:integer –** čas, zahtevan za končanje zagona MSZN

  - **Data\_MsoInitCoreTime:integer –** Čas, zahtevan za inicializacijo Officeove komponente MSZN.

  - **Data\_MsoInitUITime:integer –** Čas, zahtevan za inicializacijo Officeove komponente uporabniškega vmesnika.

  - **Data\_MsoMigrateTime:integer –** čas, zahtevan za selitev uporabniških nastavitev pri prvem zagonu, če je uporabnik nadgradil iz prejšnje različice

  - **Data\_NetworkIOBytesRead:int –** skupno število bajtov omrežja, prebranih med shranjevanjem

  - **Data\_NetworkIOBytesReadSquared:int –** kvadratna vrednost za Network\_FileIOBytesRead

  - **Data\_NetworkIOBytesWritten:int –** skupno število bajtov omrežja, zapisanih med shranjevanjem

  - **Data\_NetworkIOBytesWrittenSquared:int –** kvadratna vrednost za NetworkOBytesWritten

  - **Data\_OartStartupTime:integer –** Čas, zahtevan za inicializacijo Officeove komponente OART.

  - **Data\_OleInitTime:integer –** Čas, zahtevan za inicializacijo Officeove komponente OLE.

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

  - **Data\_SDX\_HostJsVersion –** predstavlja platformo, specifično za različico datoteke Office.js (na primer outlook web16.01.js). Vsebuje programski vmesnik za dodatke.

  - **Data\_SDX\_Id –** GUID dodatka, ki ga enolično identificira

  - **Data\_SDX\_InstanceId –** predstavlja par dokumenta dodatka

  - **Data\_SDX\_MarketplaceType –** ponazarja vir, iz katerega je bil nameščen dodatek

  - **Data\_SDX\_OfficeJsVersion –** predstavlja različico datoteke Office.js, ki poskrbi za preusmeritev na različico, odvisno od platforme.

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

  
#### <a name="officeextensibilitysandboxodpactivationhanging"></a>Office.Extensibility.Sandbox.ODPActivationHanging

Zbira podatke, ko zagon Officeovega dodatka traja nepričakovano dolgo (> 5 s). Uporablja se za zaznavanje in odpravljanje težav pri zagonih Officeovih dodatkov.
 
Zbrana so naslednja polja:

- **AppId** – ID aplikacije

- **AppInfo** – podatki glede vrste dodatka (podokno opravil ali UILess ali znotraj vsebine itd.) in vrste ponudnika (Omen, SharePoint, datotečni sistem itd.)

- **AppInstanceId** – ID primerka aplikacije 

- **AssetId** – ID sredstva aplikacije.

- **IsPreload** – označuje, ali je dodatek vnaprej naložen v ozadju, da izboljšate učinkovitost delovanja.

- **NumberOfAddinsActivated** – števec aktiviranih dodatkov.

- **RemoterType** – določa vrsto remoterja (zaupanja vreden, ni vreden zaupanja, Win32webView, zaupanja vreden UDF itd.), ki se uporablja za aktiviranje dodatka.

- **StoreType** – izvor aplikacije.

- **TimeForAuth** – čas, porabljen za preverjanje pristnosti. 

- **TimeForSandbox** – čas, porabljen za peskovnik.

- **TimeForServerCall** – čas, porabljen za klic strežnika. 

- **TotalTime** – skupni porabljeni čas

- **UsesSharedRuntime** – Označuje, ali aplikacija uporablja sharedRuntime ali ne.

#### <a name="officelenslenssdklaunchlens"></a>Office.Lens.LensSdk.LaunchLens

Ko uporabnik zažene aplikacijo Lens ali uvozi slike v poljubno aplikacijo, se zažene komplet za razvoj programske opreme Lens in zbere ta dogodek. S podatki o zagonu lahko določimo število uporabnikov/naprav, ki so zagnali aplikacijo, in podrobneje razumemo uporabo funkcij. S tem dogodkom spremljamo število uporabnikov, ki uporablja izdelek, ter prepoznavamo spremembe trendov, iščemo pomoč ter odpravljamo težave z izdelkom.

Zbrana so naslednja polja:

- **Data_isResumeSession** – ali je bila aplikacija zagnana po prekinitvi oz. se je uporabnik odločil za svež zagon. (Polje z logično vrednostjo) 

- **Data_launchPerf** – celo število, ki ponazarja čas, zahtevan za zagon aplikacije (v napravah s sistemom Android)

- **Data_LaunchWorkFlowItem** – polje, ki ponazarja, ali je bila aplikacija zagnana z zaslona kamere oz. z zaslona za urejanje. 

- **Data_mediaCompressionFactor** – faktor, s katerim aplikacija stisne slike.

- **Data_RecoveryMode** – polje z logično vrednostjo, ki ponazarja, ali je bila seja obnovljena po zaustavitvi aplikacije (v napravah s sistemom Android)

- **IsDexModeEnabled** – polje z logično vrednostjo, ki ponazarja, ali naprava podpira funkcije Samsung Dex.

- **IsEmbeddedLaunch** – polje z logično vrednostjo, ki ponazarja, ali je uporabnik zagnal kontrolnik v načinu »slika v sliki«.

- **IsInterimCropEnabled** – polje z logično vrednostjo, ki ponazarja, ali je uporabnik slike obrezal ročno.

- **IsMultiWindowEnabled** – polje z logično vrednostjo, ki ponazarja, ali je aplikacijo mogoče zagnati v načinu razdeljenega zaslona.

- **LaunchPerf** – celo število, ki ponazarja čas, zahtevan za zagon aplikacije (v napravah s sistemom iOS)

- **RecoveryMode** – polje z logično vrednostjo, ki ponazarja, ali je bila seja obnovljena po zaustavitvi aplikacije (v napravah s sistemom iOS)

- **SDKMode** – način, v katerem so bile zajete slike.


#### <a name="officeofficemobileappactivationlaunch"></a>Office.OfficeMobile.AppActivation.Launch

Ta dogodek prepozna prvo aktiviranje in naslednja aktiviranja v zunanjih sprožilcih, ki aktivirajo aplikacijo. Aktiviranje aplikacije naloži določene odvisnosti, zaradi katerih aplikacija nemoteno deluje, ta dogodek pa zabeleži, če so bile ustrezno naložene. Zabeležen je tudi vir aktiviranja in namen aplikacije, ki je odgovoren za aktiviranje aplikacije.

Zbrana so naslednja polja:

- **ActionName** – Preslikava celoštevilske vrednosti v ime dejanja/funkcije, ki je priklicana iz točke aktiviranja.
 
- **ActivationType** – Preslikava celoštevilske vrednosti v vir aktiviranja.
  
- **IsActionTriggered** – Logična vrednost, ki določa, ali je bilo dejanje sproženo po uspešnem aktiviranju aplikacije.

- **IsFirstRun** – Logična vrednost, ki določa, ali gre za prvo izvajanje aplikacije oziroma nadaljnja izvajanja.
 

#### <a name="officeofficemobilefrefirstrunsetup"></a>Office.OfficeMobile.FRE.FirstRunSetup

Ta dogodek signala obveščanja o izvajanju programa bo izzval prvi zagon aplikacije po namestitvi. Pomagal bo identificirati namestitve in samodejne nadgradnje iz starejših različic aplikacije, z njim pa bomo lahko identificirali napake v samodejnih nadgradnjah, vključno z nalaganjem knjižnice in napakami prenosov razširitve/jezikovnega paketa.

Zbrana so sledeča polja:

- **IsFlightAssigned** – Logična vrednost, ki določa, ali je bil uporabnik del kakršne koli vnaprej dodeljene preskusne skupine, ki lahko sproži izpostavljenost določenim izkušnjam.

- **IsFRELoadSuccessful** – Celo število, ki omenja stanje rezultata.

#### <a name="officeonenoteandroidappappbootcomplete-officeandroidearlytelemetryappbootcomplete"></a>Office.OneNote.Android.App.AppBootComplete, Office.Android.EarlyTelemetry.AppBootComplete

*[Ta dogodek je bil prej imenovan OneNote.App.AppBootComplete.]*

Kritični signal, ki se uporablja, da lahko novi uporabniki (Microsoftov račun) prvič uspešno zaženejo in začnejo uporabljati OneNote.  Uporablja se za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in stanja storitve.  Če uporabniki prvič ne morejo zagnati aplikacije, bo to sprožilo dogodek z visoko stopnjo resnosti.

Zbrana so sledeča polja: 

- **ACTIVITY_BOOT_TIME_IN_MS** – Čas, zahtevan, za ustvarjanje dejavnosti.

- **ACTIVITY_NAME** – Ime dejavnosti, odprte pri zagonu. 

- **ANY_DIALOG_SHOWN** – Označuje, ali se med zagonom prikaže pogovorno okno.

- **APP_SUSPEND_DURING_EVENT** – označuje, ali je bil zagon izvedeno prej

- **APP_THREAD_CREATION_WAIT_TIME_TIME_FOR_APP_THREAD_CREATION** – Čas, zahtevan za ustvarjanje niti aplikacije.

- **AVAILABLE_MEMORY_IN_MB** – Skupni pomnilnik, ki je na voljo v napravi. 

- **AVG_SNAPSHOT_POPULATION_TIME** – Pov. čas, zahtevan za pridobivanje struktur zvezka med uporabo aplikacije.

- **BOOT_END_AT_VIEW** – Podkategorija imena dejavnosti (ime pogleda).

- **BOOT_SNAPSHOTS** – Podrobnosti o pridobljenih strukturah zvezka za računa, uporabljene v aplikaciji.

- **COREAPP_STARTUP_ACCOUNT_SETUP_STARTUP_ACCOUNT_SETUP** – Čas, zahtevan za preverjanje in zagon izkušnje enotne prijave.

- **CRASH_INTERACTION_DURING_BOOT > 0** – Če želite označiti, ali je med zadnjo sejo prišlo do zrušitve aplikacije.

- **DALVIK_HEAP_LIMIT_IN_MB** – Zastarelo.

- **DELAY_LOAD_STICKY_NOTES** – Označuje, ali imajo samolepljivi listki zakasnitev.

- **FISHBOWL_SHOWN_DURING_EVENT** – Označuje primerke z nesinhronizirano vsebino.

- **HAS_LOGCAT_LOGGING_IMPACT_ON_BOOT** – Označuje, ali dnevniki vplivajo na čas zagona.

- **INIT_SNAPSHOT_DURATION** – Čas, zahtevan za pridobivanje strukture zvezka za uporabniške račune.

- **IS_COLD_BOOT** – Označuje, ali naj se aplikacija zažene, če se ta ni izvajala v ozadju.

- **IS_FIRST_LAUNCH** – Označuje, ali gre za prvi zagon aplikacije v napravi.

- **IS_FOLDABLE_TYPE** – označuje, ali je naprava zložljiva naprava

- **IS_PHONE** – Označuje, ali je naprava telefon ali tablični računalnik.

- **IS_RECENT_PAGES_AVAILABLE_ON_FRAGMENT_CREATION** – Označuje, ali je uporabniški vmesnik pripravljen in čaka, da postane vsebina na voljo. 

- **IS_REHYDRATE_LAUNCH** – Označuje, ali je sistem zaustavil aplikacijo.

- **IS_UPGRADE** – Označuje, ali se je aplikacija zagnala po nadgradnji.

- **JOT_MAIN_APP_CREATE_TIME_MAIN_APP_CREATE_TIME** – Čas, zahtevan za ustvarjanje komponente JOT (komponenta kode v skupni rabi). 

- **JOT_MAIN_APP_INIT_TIME_MAIN_APP_INIT_TIME** – Čas, zahtevan za inicializacijo komponente JOT.

- **LAUNCH_POINT** – Označuje, ali je bila aplikacija zagnana s pripomočkom, ikono aplikacije, prek hiperpovezave ali OMOGOČENE skupne rabe itd.

- **MSO_ACTIVATION_TIME_ACTIVATION_TIME** – Čas, zahtevan za inicializacijo MSO-ja.

- **NATIVE_LIBRARIES_LOAD_TIME** – Čas, zahtevan za nalaganje knjižnic.

- **NAVIGATION_CREATE_TO_NAVIGATION_RESUME_CREATE_TO_NAVIGATION_RESUME** – Čas, zahtevan za dokončanje krmarjenja.

- **NAVIGATION_RESUME_TO_BOOT_END_RESUME_TO_BOOT_END** – Čas, zahteva za merjenje zakasnitve pri nalaganju strani po zagonu.

- **NAVIGATION_SET_CONTENT_VIEW_TIME_SET_CONTENT_VIEW_TIME** – Čas, zahtevan za dodajanje vsebine.

- **NUMBER_Of_RUNNING_PROCESSES** – Označuje število aktivnih procesov, ki se izvajajo.

- **NUMBER_OF_SNAPSHOTS** – Število pridobljenih struktur zvezkov med zagonom.

- **OFFICEASSETMANAGER_INITIALIZATION_TIME** – Čas, zahtevan za razširitev in zagon upravitelja sredstev.

- **PROCESS_BOOT_TIME_IN_MS** – Čas, zahtevan, za ustvarjanje procesa.

- **ROOT_ACTIVITY_CREATE_ACTIVITY_CREATE** – Čas, zahtevan za prehod iz korenske plasti. 

- **ROOT_ACTIVITY_DISK_CHECK_ACTIVITY_DISK_CHECK** – Zastarelo.

- **ROOT_ACTIVITY_LAUNCH_NEXTACTIVITY_ACTIVITY_LAUNCH_NEXTACTIVITY** – Zastarelo.

- **ROOT_ACTIVITY_PROCESS_INTENT_ACTIVITY_PROCESS_INTENT** – Zastarelo. 

- **RooT_ACTIVITY_SESSION_ACTIVITY_SESSION** – Čas, zahtevan za prehod iz korenske plasti. 

- **ROOT_TO_NAVIGATION_TRANSITION_TO_NAVIGATION_TRANSITION** – Čas, zahtevan za obravnavo krmarjenja iz korena.

- **SNAPSHOT_PUBLISH_TO_RENDERING_END_PUBLISH_TO_RENDERING_END** – Čas, zahtevan za dokončanje upodabljanja vsebine.

- **SPLASH_ACTIVITY_SESSION_ACTIVITY_SESSION**, – Čas, zahteva za prikaz pozdravnega zaslona.

- **SPLASH_TO_ROOT_TRANSITION_TO_ROOT_TRANSITION** – Čas, zahtevan za prehod iz korenske plasti. 

- **TIME_BETWEEN_PROCESS_BOOT_AND_ACTIVITY_BEGIN_IN_MS** – Čas med procesom in ustvarjanjem dejavnosti. 

- **TIME_TAKEN_IN_MS** – Čas, zahtevan za dokončanje zagona.
 
- **TOTAL_MEMORY_IN_MB** – Skupni pomnilnik naprave.
 
- **USER_INTERACTED_DURING_EVENT** – Označuje, ali je prišlo do uporabnikove interakcije med zagonom.

#### <a name="officeonenoteandroidapponenoteappforeground-officeandroidearlytelemetryonenoteappforeground"></a>Office.OneNote.Android.App.OneNoteAppForeground, Office.Android.EarlyTelemetry.OneNoteAppForeground

*[Ta dogodek je bil prej imenovan OneNote.App.OneNoteAppForeground.]*

S tem signalom določimo, da se aplikacija OneNote izvaja v ospredju.  Telemetrija se uporablja za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in ustreznosti stanja storitve. 

Zbrana so sledeča polja: 

- Nobeno

#### <a name="officeonenoteandroidapplaunch-officeandroidearlytelemetryapplaunch"></a>Office.OneNote.Android.AppLaunch, Office.Android.EarlyTelemetry.AppLaunch

*[Ta dogodek je bil prej imenovan OneNote.AppLaunch.]*

Kritični signal, ki se uporablja, da uporabnikom storitve OneNote zagotovi uspešen zagon aplikacije.  Telemetrija se uporablja za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in ustreznosti stanja storitve. 

Zbrana so sledeča polja: 

- **ANDROID_SDK_VERSION** – zajame različico Android SDK

- **FirstLaunchTime** – Beleži čas prvega zagona aplikacije.

- **InstallLocation** – Označuje, ali je aplikacija vnaprej nameščena ali prenesena iz trgovine.

- **is_boot_completed_ever** – Označuje, ali je bila aplikacija že kdaj uspešno zagnana v tej napravi.

- **IS_DARK_MODE_ENABLED** – logična vrednost, ki označuje, ali je aplikacija v temnem načinu ali ne

- **NewOneNoteUser** – Prepoznajte, ali je uporabnik obenem nov uporabnik.

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

  - **Data\_AlreadyOpened –** ali je bil ta dokument že odprt (v okviru iste seje procesa)

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

  - **Data_CorrelationId –** GUID, ki je bil v PowerPoint posredovan z rutino ProtocolHandler za korelacijo telemetrije. ProtocolHandler je ločen proces, ki obravnava Officeove povezave za operacijski sistem.

  - **Data\_CppUncaughtExceptionCount:long** – Nezaznane izvorne izjeme med izvajanjem dejavnosti.

  - **Data\_CreateDocumentTimeMS –** trajanje izvedbe za način CreateDocumentTimeMS v milisekundah

  - **Data\_CreateDocumentToken –** trajanje izvedbe za način CreateDocumentToken v milisekundah

  - **Data\_CreateDocumentToW –** trajanje izvedbe za način CreateDocumentToW v milisekundah

  - **Data\_CreateDocWindow –** trajanje izvedbe za način CreateDocWindow v milisekundah

  - **Data\_CreateLocalTempFile –** trajanje izvedbe za način CreateLocalTempFile v milisekundah

  - **Data\_DetachedDuration:long –** čas odpete dejavnosti/neizvajanja dejavnosti

  - **Data\_DetermineFileType –** trajanje izvajanja za način DetermineFileType v milisekundah

  - **Data\_Doc\_AccessMode:long** – Način odpiranja dokumenta (samo za branje/branje in pisanje).

  - **Data\_Doc\_AssistedReadingReasons:long** – Nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

  - **Data_Doc_AsyncOpenKind:long –** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

  - **Data\_Doc\_ChunkingType:long** – Način shranjevanja dokumenta v SharePointu.

  - **Data\_Doc\_EdpState:long** – Stanje zaščite podatkov podjetja za dokument.

  - **Data\_Doc\_Ext:string** – Pripona dokumenta.

  - **Data\_Doc\_Extenstion:string** – Pripona dokumenta.

  - **Data\_Doc\_FileFormat:long** – Nabor vnaprej določenih vrednosti za obliko zapisa datoteke (bolj podrobno kot za pripono).

  - **Data\_Doc\_Fqdn:string** – Mesto, kjer je dokument shranjen (SharePoint.com, live.net); na voljo samo za domene v storitvi Office 365.

  - **Data\_Doc\_FqdnHash:string –** razpršitev mesta shrambe dokumenta

  - **Data\_Doc\_IdentityTelemetryId:string** – Enolični GUID uporabnika.

  - **Data\_Doc\_IdentityUniqueId:string –** enolični identifikator identitete, ki je bila uporabljena za dokumente v skupni rabi

  - **Data\_Doc\_IOFlags:long** – Bitna maska za različne zastavice danega dokumenta, povezane z VI.

  - **Data\_Doc\_IrmRights:long** – Nabor vnaprej določenih vrednosti za vrsto upravljanja pravic do informacij, ki velja za ta dokument (»Forward«, »Reply«, »SecureReader«, »Edit« itd.).

  - **Data\_Doc\_IsCloudCollabEnabled:bool –** ima vrednost true, če je bila glava HTTP »IsCloudCollabEnabled« že prejeta od zahteve OPTIONS

  - **Data\_Doc\_IsIncrementalOpen:bool** – Ali je bil dokument odprt postopoma (nova funkcija, ki odpre dokument tako, da ne prenese celoten dokument).

  - **Data\_Doc\_IsOcsSupported:bool** – ali dokument podpira soavtorstvo z novo storitvijo OCS

  - **Data\_Doc\_IsOpeningOfflineCopy:bool** – Ali je bil dokument odprt iz lokalnega predpomnilnika?

  - **Data\_Doc\_IsSyncBacked:bool** –Ali je bil dokument odprt iz mape, za katero se uporablja aplikacija za povratno sinhronizacijo v storitvi OneDrive.

  - **Data\_Doc\_Location:long** – Nabor vnaprej določenih vrednosti za mesto shranjevanja dokumenta (lokalno, SharePoint, WOPI, omrežje itd.).

  - **Data\_Doc\_LocationDetails:long** – Nabor vnaprej določenih vrednosti podrobnejše lokacije (mapa »Začasno«, mapa »Prenosi«, dokumenti storitve OneDrive, slike storitve OneDrive itd.).

  - **Data\_Doc\_NumberCoAuthors:long** –število soavtorjev, ko je bil dokument odprt

  - **Data\_Doc\_PasswordFlags:long** – Nabor vnaprej določenih vrednosti za način šifriranja dokumenta z geslom (brez, geslo za branje, geslo za urejanje).

  - **Data\_Doc\_ReadOnlyReasons:long** – Nabor vnaprej določenih vrednosti, zakaj je bil ta dokument označen samo za branje (zaklenjeno v strežniku, dokončni dokument, zaščiteno z geslom za urejanje itd.).

  - **Data\_Doc\_ResourceIdHash:string** – Zgoščena vrednost identifikatorja vira za dokumente, shranjene v oblaku.

  - **Data_Doc_RtcType** – označuje, kako je bil kanal v realnem času (RTC) nastavljen za trenutno datoteko (onemogočeno, nepodprto, na zahtevo, vedno vklopljeno itn.).

  - **Data\_Doc\_ServerDocId:string –** nespremenljivi identifikator za dokumente, shranjene v oblaku

  - **Data\_Doc\_ServerProtocol:long** – Nabor vnaprej določenih vrednosti, ki jih protokol uporablja za komunikacijo s strežnikom (Http, Cobalt, WOPI itd.).
 
  - **Data\_Doc\_ServerType:long –** nabor vnaprej določenih vrednosti za vrsto strežnika (SharePoint, DropBox, WOPI)

  - **Data\_Doc\_ServerVersion:long –** ali ta strežnik temelji na sistemu Office 14, Office 15, Office 16?

  - **Data\_Doc\_SessionId:long –** ustvarjeni GUID, ki prepozna primerek dokumenta v seji istega procesa

  - **Data\_Doc\_SharePointServiceContext:string** – Neprosojen niz, običajno »GridManagerID.FarmID«. Uporabni dogodki za korelacijo odjemalskih in strežniških dnevnikov.

  - **Data\_Doc\_SizeInBytes:long** – Velikost dokumenta v bajtih.

  - **Data\_Doc\_SpecialChars:long** – Bitna maska, ki označuje posebne znake v URL-ju ali poti dokumenta.

  - **Data\_Doc\_StorageProviderId:string** – Niz, ki prepozna ponudnika za shranjevanje dokumentov, npr. »DropBox«.

  - **Data\_Doc\_StreamAvailability:long** – Nabor vnaprej določenih vrednosti za stanje dokumenta Stream (na voljo, stalno onemogočeno, ni na voljo).

  - **Data\_Doc\_UrlHash:string –** razpršitev polnega URL-ja za dokumente, shranjene v oblaku

  - **Data\_Doc\_UsedWrsDataOnOpen:bool –** ima vrednost true, če je bila datoteka odprta postopoma z vnaprej predpomnjenimi podatki WRS na strani gostitelja

  - **Data\_Doc\_WopiServiceId:string** – identifikator storitve WOPI, na primer »Dropbox«

  - **Data\_DownloadExcludedData –** trajanje izvajanja za način DownloadExcludedData v milisekundah

  - **Data\_DownloadExcludedDataTelemetry –** nabor vnaprej določenih vrednosti za stanje sinhronega čakanja na prenos (SynchronousLogicHit, UserCancelled RunModalTaskUnexpectedHResult itd.)

  - **Data\_DownloadFileInBGThread –** trajanje izvedbe za način DownloadFileInBGThread v milisekundah

  - **Data\_DownloadFragmentSize –** velikost dela (del datoteke, ki ga je mogoče prenesti), običajno 3,5 MB

  - **Data\_ExcludedEmbeddedItems –** število stisnjenih delov, ki so bili izključeni pri prvem upodabljanju

  - **Data\_ExcludedEmbeddedItems –** skupna velikost stisnjenih delov, ki so bili izključeni pri prvem upodabljanju

  - **Data\_ExcludedRequiredItems –** število stisnjenih delov, ki so bili izključeni pri prvem upodabljanju, vendar so zahtevani

  - **Data\_ExcludedRequiredItemsSize –** skupna velikost stisnjenih delov, ki so bili izključeni pri prvem upodabljanju, vendar so zahtevani

  - **Data\_ExecutionCount –** število izvedenih protokolov IncOpen

  - **Data\_FailureComponent:long** – Nabor vnaprej določenih vrednosti komponent, zaradi katerih tega protokola ni bilo mogoče izvesti. (Spor, CSI, Internal itd.)

  - **Data\_FailureReason:long –** nabor vnaprej določenih vrednosti za vzroke okvare (FileIsCorrupt, BlockedByAntivirus itd.)

  - **Data\_FCreateNew –** ali je to nov prazen dokument

  - **Data\_FCreateNewFromTemplate –** ali je to nov dokument iz predlog

  - **Data_FErrorAfterDocWinCreation:boolean** – Ali je prišlo do morebitne napake ali izjeme po tem, ko je bilo ustvarjeno okno dokumenta.

  - **Data\_FileUrlLocation –** nabor vnaprej določenih vrednosti za mesto shranjevanja dokumentov (NetworkShare, LocalDrive, ServerOther itd.)

  - **Data\_FirstSlideCompressedSize –** stisnjena velikost prvega stisnjenega dela diapozitivov (običajno Slide1.xml)

  - **Data_FIsAutoBackupFile –** je datoteka Samodejna varnostna kopija?

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

  - **Data\_IsIncOpenInProgressWhileOpen –** v primeru večkratnega odpiranja istega dokumenta sporoči, ali je poleg protokola za odpiranje aktivirano tudi postopno odpiranje

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

  - **Data_OngoingBlockingOpenCount –** to je število blokiranj odprtih protokolov, ki se trenutno izvaja.
  
  - **Data_OngoingOpenCount –** to je število odprtih protokolov, ki se trenutno izvaja.

  - **Data\_OpenCompleteFailureHR –** razlog, zakaj protokola OpenComplete ni bilo mogoče dokončati

  - **Data\_OpenCompleteFailureTag –** oznaka (kazalec na mesto v kodi) mesta, kjer je prišlo do napake pri protokolu OpenComplete

  - **Data\_OpenLifeguardOption –** nabor vnaprej določenih vrednosti za izbire načinov zaščite (None, TryAgain, OpenInWebApp itd.)

  - **Data\_OpenReason –** nabor vnaprej določenih vrednosti za način odpiranja dokumenta (FilePicker, OpenFromMru, FileDrop itd.)

  - **Data\_OSRPolicy –** pravilnik SecureReader

  - **Data\_OSRReason –** razlogi, zakaj je bil ta dokument v programu Secure Reader

  - **Data\_OtherContentTypesWithRequiredParts –** nestandardne vrste vsebine, ki so bile izključene, vendar so zahtevane za prvo upodabljanje

  - **Data\_PrepCacheAsync –** zastavica za OcsiOpenPerfPrepCacheAsync

  - **Data\_PreviousDiscardFailed –** ponazarja, da prejšnji poskus odpiranja/zapiranja dokumenta ni pravilno sprostil vsega pomnilnika

  - **Data\_PreviousFailureHr –** v primeru vnovičnega odpiranja istega dokumenta označuje zadnji neuspešen rezultat

  - **Data\_PreviousFailureTag –** v primeru vnovičnega odpiranja istega dokumenta navaja zadnjo neuspešno oznako (kazalec na mesto v kodi)

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

  - **Data\_IsEntOfflineWithProfile out-space** ali je uporabnikom bila dodeljena profesionalna inventarna številka in nimajo vzpostavljene povezave s strežnikom

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

- **AppSessionGuid** – identifikator določene seje aplikacije, ki se je začela z ustvarjanjem procesa in traja vse do konca procesa. Dogodek je oblikovan kot standardni 128-bitni GUID, sestavljen iz štirih delov. Ti štirje deli v vrstnem redu so (1) 32-bitni ID procesa (2) 16-bitni ID seje (3) 16-bitni ID zagona (4) čas ustvarjanja 64-bitnega procesa v UTC 100 ns

- **processSessionId** – naključno ustvarjeni GUID za prepoznavanje seje aplikacije

- **UTCReplace_AppSessionGuid** – logična vrednost konstante. Vedno ima vrednost true.

#### <a name="officesystemsessionhandoff"></a>Office.System.SessionHandoff

Označuje, da gre pri trenutni Officeovi seji za sejo prenosa. To pomeni, da je obravnava uporabnikove zahteve za odpiranje dokumenta prenesena na primerek iste aplikacije, ki se že izvaja.

Zbrana so naslednja polja.

- **ParentSessionId** – ID seje, ki bo prevzela obravnavo uporabnikove zahteve.

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

#### <a name="officevisiovisioiosappboottime"></a>Office.Visio.VisioIosAppBootTime

Ta dogodek se sproži vsakič, ko se zažene aplikacija Visio iOS. Zelo pomembno je, da razumemo učinkovitost delovanja zagona aplikacije Visio iOS. Dogodek uporabljamo za odpravljanje slabe učinkovitosti delovanja. 

Zbrana so naslednja polja:

- **Data_AppBootTime** – trajanja zagona aplikacije v milisekundah.

#### <a name="officevisiovisioiosappresumetime"></a>Office.Visio.VisioIosAppResumeTime 

Ta dogodek se sproži vsakič, ko se nadaljuje izvajanje aplikacije Visio iOS v fokusu. Zelo pomembno je, da merimo učinkovitost ponovnega izvajanje aplikacije in da odpravimo težave z učinkovitostjo delovanja aplikacije Visio iOS.

Zbrana so naslednja polja:

- **Data_AppResumeTime** – trajanje za nadaljevanje izvajanja aplikacije v milisekundah.

#### <a name="officewordfileopenopencmdfilemrupriv"></a>Office.Word.FileOpen.OpenCmdFileMruPriv

Ta dogodek ponazarja, da je Microsoft Office Word odprl dokument s seznama nedavno uporabljenih elementov. Poleg tega vsebuje kritične podatke o učinkovitosti odpiranja datotek in z vidika uporabnika predstavlja dogodek za zagon aplikacije. Dogodek nadzira, ali funkcija »Odpri datoteko s seznama nazadnje uporabljenih datotek« deluje v skladu s pričakovanji. Prav tako se uporablja za izračunane mesečne aktivne uporabnike/naprave in za metriko zanesljivosti v oblaku.

Zbrana so sledeča polja:

- **Data_AddDocTelemRes** – poroča, ali lahko pravilno dopolnimo druge vrednosti dogodka, povezane s telemetrijo dokumenta. Uporablja se za diagnostiko kakovosti podatkov.

- **Data_BytesAsynchronous** – število bajtov (stisnjenih), brez katerega je morda mogoče odpreti datoteko, če ga pridobimo, preden uporabnik začne urejati dokument oz. se ga morda odloči shraniti.

- **Data_BytesAsynchronousWithWork** – število bajtov (stisnjenih), brez katerega morda lahko odpremo datoteko, vendar bi zato morali občutno spremeniti kodo.

- **Data_BytesSynchronous** – število bajtov (stisnjenih), ki ga moramo pridobiti, preden lahko odpremo datoteko.

- **Data_BytesUnknown** – število bajtov v delih dokumenta, za katerega menimo, da ga ne bomo našli. 

- **Data_DetachedDuration** – koliko časa je bila dejavnost ločena od niti.

- **Data.Doc.AccessMode** – dokument je samo za branje/ga je mogoče urejati.

- **Data_Doc_AssistedReadingReasons** – nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

- **Data_Doc_AsyncOpenKind –** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

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

- **Data.Doc.AccessMode** – dokument je samo za branje/ga je mogoče urejati.

- **Data_Doc_AssistedReadingReasons** – nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

- **Data_Doc_AsyncOpenKind –** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

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

  - **Data\_AddDocTelemRes** – Poroča, ali lahko pravilno dopolnimo druge vrednosti dogodka, povezane s telemetrijo dokumenta. Uporablja se za diagnostiko kakovosti podatkov.

  - **Data\_BytesAsynchronous –** število bajtov (stisnjenih), za katerega menimo, da lahko odpremo datoteko brez tega števila, če jih pridobimo, preden uporabnik želi začeti urejati dokument oz. ga morda shraniti

  - **Data\_BytesAsynchronousWithWork –** število bajtov (stisnjenih), pri katerem morda še lahko odpremo datoteko brez tega števila, vendar bi zato morali občutno spremeniti kodo

  - **Data\_BytesSynchronous –** število bajtov (stisnjenih), ki ga moramo pridobiti, preden lahko odpremo datoteko

  - **Data\_BytesUnknown –** število bajtov v delih dokumenta, za katerega menimo, da ga ne bomo našli

  - **Data\_Doc\_AccessMode –** dokument je samo za branje ali omogoča urejanje

  - **Data\_Doc\_AssistedReadingReasons** – Nabor vnaprej določenih vrednosti, zakaj je bil dokument odprt v načinu vodenega branja.

  - **Data_Doc_AsyncOpenKind –** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

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

  - **Data_Doc_RtcType** – označuje, kako je bil kanal v realnem času (RTC) nastavljen za trenutno datoteko (onemogočeno, nepodprto, na zahtevo, vedno vklopljeno itn.).

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

- **Data_Doc_AsyncOpenKind –** Označuje, ali se je odprla predpomnjena različica dokumenta v oblaku in katera logika asinhronega osveževanja je bila uporabljena.

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

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se aplikacija izvaja v produkcijskem okolju ali v okolju razvijalcev

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

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se aplikacija izvaja v produkcijskem okolju ali v okolju razvijalcev

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

  - **Data\_Data\_Jaws –** ponazarja, ali se je med sejo uporabljal bralnik Jaws **Data\_Data\_Magic –** ponazarja, ali se je med sejo uporabljalo orodje Magic

  - **Data\_Data\_Magnify –** ponazarja, ali se je med sejo uporabljajo orodje povečave

  - **Data\_Data\_Narrator –** ponazarja, ali se je med sejo uporabljal pripovedovalec

  - **Data\_Data\_NVDA –** ponazarja, ali se je med sejo uporabljajo orodje NVDA

  - **Data\_Data\_SA –** ponazarja, ali se je med sejo uporabljajo orodje SA

  - **Data\_Data\_Supernova –** ponazarja, ali se je med sejo uporabljajo orodje Supernova

  - **Data\_Data\_SuperNovaessSuite –** ponazarja, ali se je med sejo uporabljajo orodje SuperNovaAccessSuite

  - **Data\_Data\_WinEyes –** ponazarja, ali se je med sejo uporabljajo orodje WinEyes

  - **Data\_Data\_ZoomText –** ponazarja, ali se je med sejo uporabljajo orodje ZoomText

#### <a name="officeappledarkmode"></a>Office.Apple.DarkMode

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek nam pove, ali je uporabnik zagnal sistem v načinu DarkMode in ali je uporabnik prepisal nastavitev sistema DarkMode v Officeu.  Ta dogodek nam pomaga zagotoviti dostopnost in prednostno obravnavo optimizacije uporabniške izkušnje.

Zbrana so naslednja polja:

- **Data_DarkModeIsEnabled** – označuje, ali je v sistemu omogočen način DarkMode.

- **Data_RequiresAquaSystemAppearanceEnabled** – označuje, ali je v Officeu prepisan način DarkMode.

#### <a name="officeapplehardwarekeyboardinuseapple"></a>Office.Apple.HardwareKeyboardInUse.Apple

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek nam pove, da ima uporabnik na svojo prenosno napravo priključeno tipkovnico. Dogodek nam pomaga pri izboljšanju dostopnosti in optimizaciji uporabniške izkušnje.

Zbrana so naslednja polja:

- **Data_CollectionTime** – časovni žig, ki označuje čas zbiranja dogodka.

#### <a name="officeapplembuinstrumentdeviceaccessibilitysettings"></a>Office.Apple.MbuInstrument.DeviceAccessibilitySettings

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek zbira podatke o stanju različnih možnosti dostopnosti, ki so na voljo med sejo. Ta dogodek nam pomaga zagotoviti dostopnost in prednostno obravnavo optimizacije uporabniške izkušnje.

Zbrana so naslednja polja:

- **Data_AccessibilityContentSize** – zastavica, ki označuje, ali je ta nastavitev omogočena

- **Data_AssistiveTouchRunning** – zastavica, ki označuje, ali je ta nastavitev omogočena

- **Data_BoldTextEnabled** – zastavica, ki označuje, ali je ta nastavitev omogočena

- **Data_CollectionTime** – zastavica, ki označuje, ali je ta nastavitev omogočena

- **Data_DarkerSystemColorsEnabled** – zastavica, ki označuje, ali je ta nastavitev omogočena

- **Data_DifferentiateWithoutColor** – zastavica, ki označuje, ali je ta nastavitev omogočena

- **Data_GrayscaleEnabled** – zastavica, ki označuje, ali je ta nastavitev omogočena

- **Data_GuidedAccessEnabled** – zastavica, ki označuje, ali je ta nastavitev omogočena

- **Data_IncreaseContrast** – zastavica, ki označuje, ali je ta nastavitev omogočena

- **Data_InvertColorsEnabled** – zastavica, ki označuje, ali je ta nastavitev omogočena

- **Data_PreferredContentSizeCategory** – zastavica, ki označuje, ali je ta nastavitev omogočena

- **Data_ReduceMotionEnabled** – zastavica, ki označuje, ali je ta nastavitev omogočena

- **Data_ReduceTransparency** – zastavica, ki označuje, ali je ta nastavitev omogočena

- **Data_ReduceTransparencyEnabled** – zastavica, ki označuje, ali je ta nastavitev omogočena

- **Data_ShakeToUndeEnabled** – zastavica, ki označuje, ali je ta nastavitev omogočena. (Opuščeno – uporabljeno le pri starih graditvah.)

- **Data_ShakeToUndoEnabled** – zastavica, ki označuje, ali je ta nastavitev omogočena.

- **Data_SpeakScreenEnabled** – zastavica, ki označuje, ali je ta nastavitev omogočena

- **Data_SpeakSelectionEnabled** – zastavica, ki označuje, ali je ta nastavitev omogočena

- **Data_SwitchControlRunning** – zastavica, ki označuje, ali je ta nastavitev omogočena

- **Data_UAZoomEnabled** – zastavica, ki označuje, ali je ta nastavitev omogočena

- **Data_VoiceOverRunning** – zastavica, ki označuje, ali je ta nastavitev omogočena

#### <a name="officewordaccessibilitylearningtoolsreadaloudplayreadaloud"></a>Office.Word.Accessibility.LearningTools.ReadAloud.PlayReadAloud

Ta dogodek ponazarja, da Microsoft Office Word naglas bere besedilo dokumenta. Dogodek predstavlja signal obveščanja o izvajanju funkcije dostopnosti, ki Microsoftu omogoča, da ovrednoti stanje storitve branja besedila naglas.

Zbrana so sledeča polja:

  - **Data\_ParagraphCount –** število odstavkov v dokumentu

  - **Data\_Play –** ali Word prvič bere dokument naglas

  - **Data\_ViewKind –** vrsta pogleda v dokumentu

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

#### <a name="appstartupreason"></a>app.startup.reason

S tem dogodkom lahko zaznamo in odpravljamo težave, zaradi katerih se je Outlook zrušil med zagonom.  Ta dogodek vključuje informacije o zrušitvi, tako da lahko težavo hitro odpravimo.

Zbrana so sledeča polja: 

- **app_background_time** – čas, ko je bila aplikacija v ozadju med zadnjo sejo.

- **startup_reason_type** – prikaže razlog za zagon aplikacije, npr. zaradi prisilne zaustavitve ali drugega razloga. 

- **watch_status_info** – spremlja naslednje informacije (če so na voljo). 

  - **is_watch_app_installed** – ugotovi, ali je uporabnik namestil aplikacijo Watch.

  - **is_watch_paired** – ugotovi, ali je naprava iOS seznanjena z uro.

  - **is_watch_supported_and_active** – prikaže, ali je ura podprta in aktivna med sejo.

Ta polja so zbrana samo za aplikacijo Outlook Mobile za iOS:

- **clean_exit_reason** – niz besed, ki ponazarjajo, ali je bil na voljo razlog za ustavitev aplikacije.

- **is_agenda_user** – prikaže, ali je uporabnik pred kratkim odprl dnevni red, kar pomeni, da med zagonom zapisujemo podatke na disk

- **is_watch_supported_and_active** – prikaže, ali je ura podprta in aktivna med sejo.


#### <a name="applicationcrash"></a>application.crash

Se uporablja za nadzor kritičnih zrušitev aplikacije. S tem dogodkom zbiramo informacije o razlogih za zrušitev aplikacije in o tem, kako preprečiti zrušitev.

Zbrana so sledeča polja: 

- **android.hardware.** – vrednosti za konfiguracijo strojne opreme, ki jih posreduje okolje Android (na primer android.hardware.bluetooth)

- **android.software.** – vrednosti za konfiguracijo programske opreme, ki jih posreduje okolje Android (na primer android.software.device_admin)

- **android_version** – ime različice naprave Android, kot ga navaja android.os.Build.VERSION#RELEASE.

- **application_package_name** – ime paketa aplikacije, kot ga navaja android.content.Context#getPackageName().

- **application_stack_trace** – sled sklada zrušitve.

- **application_version_code** – koda različice aplikacije, ki jo določa aplikacija Outlook.

- **application_version_name** – ime različice aplikacije, ki jo določa aplikacija Outlook. 

- **com.** (Na primer com.google.android.feature.FASTPASS_BUILD, com.amazon.feature.PRELOAD, com.samsung.android.bio.face). Konfiguracijske vrednosti proizvajalca, ki jih zagotavlja platforma Android.

- **crash_report_sdk**-SDK za pošiljanje dnevnikov zrušitve. Hokejski ali AppCenter

- **crash_type** – crash_type bo vsebovala Javo kot vrste, ki niso usodne.

     - Java – IF je bila zabeležena na plast aplikacije.

     - izvorno – če je bila zrušitev zabeležena na izvorni ravni v aplikaciji. 

     - ne-usodne zrušitve so zapisana, da odpravijo katerokoli značilnost. Aplikacija ne bo trčila, vendar bo naložila dnevnike neusodne zrušitve za pomoč pri odpravljanju težav s funkcijo.

- **device_brand** – blagovna znamka naprave (proizvajalec ali operater), kot jo navaja android.os.Build#BRAND.

- **device_ID** – enolični ID naprave (IMEI).

- **device_manufacturer** – proizvajalec naprave, kot ga navaja android.os.Build#MANUFACTURER.

- **device_model** – model naprave, kot ga navaja android.os.Build#MODEL.

- **device_name** – ime naprave, kot ga navaja android.os.Build#DEVICE.

- **device_total_memory** – ocena skupne velikosti pomnilnika naprave glede na statistične podatke datotečnega sistema.

- **glEsVersion** – ključ različice za vdelane sisteme OpenGL.


#### <a name="crashevent"></a>crash.event

Omogoča, da zaznamo in odpravimo primere, pri katerih je prišlo do kritičnih zrušitev aplikacije. S tem dogodkom zbiramo informacije o razlogih za zrušitev aplikacije in o tem, kako preprečiti zrušitev.

Zbrana so sledeča polja: 

- **crashTime** – datum in čas zrušitve, ki sta nam v pomoč pri preiskavi.

- **crash_time_from_start** – Čas, ki je pretekel od zagona aplikacije do zrušitve, za namene podpore pri raziskavi.

- **exceptionName** – Ime izjeme, ki je sprožila zrušitev, za namene podpore pri raziskavi.

- **exception_reason** – Razlog izjeme, ki je sprožila zrušitev, za namene podpore pri raziskavi.

- **hasHx** – dogodek, ki ponazarja, da račun uporablja našo novo storitev sinhronizacije, s katerim je mogoče zaznati težave, ki jih povzroči naša storitev sinhronizacije.

- **incidentIdentifier** – Enolični ID za poročilo o zrušitvi, da bomo lahko našli ustrezno težavo.

- **isAppKill** – Pomaga nam ugotoviti, ali je bila aplikacija prisilno zaustavljena ali zaprta v napravi.

- **is_crashloop** – Pomaga nam razumeti, ali gre pri zrušitvi morda za zanko zrušitve.

- **reportKey** – Enoličen ID za namestitev aplikacije iz naprave za namene preiskave.

- **signal** – signal, ki je povzročil zrušitev, in vsebuje podrobnosti za preiskavo te zrušitve.


#### <a name="error"></a>Napaka

Pomaga nam razumeti težave, do katerih lahko pride, ko mobilne aplikacije poskušajo pridobiti nastavitve zasebnosti iz strežnika.

Zbrana so sledeča polja:

- **correlationId** – enoličen identifikator za storitev povezave, ki je javila napako. Omogoča nam, da diagnosticiramo morebiten vzrok napake.

- **errorCode** – prepozna ustrezno kodo napake, prejeto iz storitve, ki jo lahko uporabimo za diagnosticiranje težave.

- **exceptionType** – vrsta napake, na katero je naletela knjižnica med pridobivanjem nastavitve.

- **message** – prepozna sporočilo napake, prejeto od storitve.

- **roamingSettingType** – prepozna mesto, s katerega smo poskušali prebrati nastavitve.

- **settingId** – nastavitev, ki jo je sitem poskušal pridobiti.

#### <a name="officeappdomainunhandledexceptionhandlerfailed"></a>Office.AppDomain.UnhandledExceptionHandlerFailed

Zbira informacije za morebitne neobravnavane izjeme z orodjem za pretakanje podatkov. Ti podatki se uporabljajo za nadzor stanja aplikacije. Ta dogodek ustvari Microsoftovo orodje za pretakanje podatkov za Excelov dodatek.

Zbrana so sledeča polja:

- **Exception** – nabor klicev za izjemo

- **Event Name** – Kategorija dogodka in oznaka dogodka predstavljata ime dogodka

#### <a name="officeappleidentitydomainname"></a>Office.Apple.IdentityDomainName

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za nadzorovanje ustreznosti stanja sistema in preiskovanje vzrokov napak nekaterih uporabnikov domene. Zbiramo podatke o domeni, ki jo uporabljajo naši uporabniki pri preverjanju pristnosti.  Ti podatki nam pomagajo prepoznati in odpraviti težave, ki se morda na širši ravni ne zdijo preveč vplivne, za določeno domeno uporabnikov pa se izkažejo za zelo vplivne.

Zbrana so naslednja polja:

- **Data_Domain** – domena, ki se uporablja za preverjanje pristnosti

- **Data_IdentityProvider** – ime ponudnika identitete za preverjanje pristnosti. (npr. LiveId ali ADAL)

- **Data_IdentityProviderEnum** – koda ponudnika identitete za preverjanje pristnosti. (Število)

#### <a name="officeapplesystemhealthappexitmacandios"></a>Office.Apple.SystemHealthAppExitMacAndiOS

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za nadzorovanje ustreznosti stanja Officeovih aplikacij in preiskovanje vzrokov napak. Zbiramo podatke o posameznem izhodu iz aplikacije, da bi ugotovili, ali se je aplikacija zaprla brez napak.

Zbrana so naslednja polja:

- **Data_AffectedProcessSessionID** – identifikator seje, pri kateri je prišlo do izhoda iz aplikacije.

- **Data_AffectedSessionBuildNumber** – podrazličica aplikacije, pri kateri je bil zaznan izhod iz aplikacije.

- **Data_AffectedSessionDuration** – dolžina seje od začetka do izhoda

- **Data_AffectedSessionIDSMatch** – kazalnik ustreznosti stanja telemetrije.

- **Data_AffectedSessionMERPSessionID** – kazalnik ustreznosti stanja telemetrije.

- **Data_AffectedSessionOSLocale** – območne nastavitve operacijskega sistema, v katerem je bil zaznan izhod iz aplikacije.

- **Data_AffectedSessionOSVersion** – različica operacijskega sistema, v katerem je bil zaznan izhod iz aplikacije.

- **Data_AffectedSessionResidentMemoryOnCrash** – prostor v stalnem pomnilniku, ki je bil zaseden, ko je prišlo do izhoda iz aplikacije

- **Data_AffectedSessionStackHash** – identifikator, ki označuje določeno napako, do katere je prišlo.

- **Data_AffectedSessionStartTime** – čas, ko se je začela seja.

- **Data_AffectedSessionUAEType** – vrsta zaznanega izhoda iz aplikacije (če gre za izhod z napako, ta koda označuje vrsto zaznane napake)

- **Data_AffectedSessionVersionr** – glavna različica aplikacije, pri kateri je bil zaznan izhod iz aplikacije.

- **Data_AffectedSessionVirtualMemoryOnCrash** – prostor v navideznem pomnilniku, ki je bil zaseden, ko je prišlo do izhoda iz aplikacije.

- **Data_ExitWasGraceful** – označuje, ali je šlo za izhod iz aplikacije brez napak ali z napakami.

#### <a name="officeextensibilitycomaddinunhandledexception"></a>Office.Extensibility.COMAddinUnhandledException

Dogodek, ustvarjen ob zrušitvah dodatka COM v potrošniški različici Officeovih aplikacij. 

S tem dogodkom je mogoče izračunati globalne aplikacije, ki niso značilne za okolje Microsoft 365, za »uvedbo« v podjetjih za dodatek, ki ga nato uporabljajo orodja, kot je orodje za pripravljenost. S tem strankam podjetja dovolite, da preverijo, ali so dodatki, ki so uvedeni v svojih organizacijah, združljivi z najnovejšimi različicami aplikacij Microsoft 365 za podjetja in da bodo ustrezno načrtovali njihove nadgradnje. 

Zbrana so naslednja polja:

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

S tem dogodkom je mogoče izračunati globalne aplikacije, ki niso značilne za okolje Microsoft 365, za »uvedbo« v podjetjih za dodatek, ki ga nato uporabljajo orodja, kot je orodje za pripravljenost. S tem strankam podjetja dovolite, da preverijo, ali so dodatki, ki so uvedeni v svojih organizacijah, združljivi z najnovejšimi različicami aplikacij Microsoft 365 za podjetja in da bodo ustrezno načrtovali njihove nadgradnje. 

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

- **IsAugmentationScenario** – označuje, ali je razširitvena zanka odgovorna za inicializacijo nadzora Officeovih rešitev

- **IsDebug** – označuje sejo za odpravljanje napak

- **IsPreload** – Označuje, ali je dodatek vnaprej naložen v ozadju za izboljšanje učinkovitosti delovanja.

- **IsWdagContainer** – Označuje, ali se je začel postopek aktivacije dodatka v vsebniku tehnologije Windows Defender Application Guard.

- **NumberOfAddinsActivated** – Števec aktiviranih dodatkov

- **RemoterType** – določa vrsto remoterja (zaupanja vreden, ni vreden zaupanja, Win32webView, zaupanja vreden UDF itd.), ki se uporablja za aktiviranje dodatka

- **StoreType** – izvor aplikacije

- **Oznaka**– določa, kje točno je prišlo do napake kode, in sicer z enolično oznako, ki je povezana s kodo.

- **UsesSharedRuntime** – označuje, ali aplikacija uporablja sharedRuntime.


#### <a name="officeextensibilityvbatelemetrybreak"></a>Office.Extensibility.VbaTelemetryBreak

Dogodek, ki se ustvari, ko datoteka z omogočenimi makri naleti na napako pri prevajanju ali izvajanju.

Namizna analitika: uporablja se kot števec pri izračunu stanja poslovnih funkcij za vrste makrov (na primer Wordovi makri, Excelovi makri itd.), ki se uporabljajo za določitev, ali je med pilotnim projektom dodatek »pripravljen na nadgradnjo« v proizvodnem ciklu.

Zbrana so naslednja polja:

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

Zbiranje uporab funkcije v posameznih PowerPointovih sejah.  Ti podatki se uporabljajo za izračun razmerja neprimernih izhodov iz PowerPointa med uporabo funkcije. Razmerje neprimernih izhodov iz PowerPointa predstavlja poglavitni signal za zagotovitev, da PowerPoint ne deluje po pričakovanjih.

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


#### <a name="officeprogrammabilityaddinscomaddincrash"></a>Office.Programmability.Addins.COMAddInCrash 

Dogodek, ki se ustvari ob zrušitvi dodatka COM. Uporablja se za določanje težav pri uvedbah in zanesljivosti z Officeovimi dodatki. 

Zbrana so naslednja polja:

- **AddinConnectFlag** – predstavlja vedenje nalaganja  

- **AddinDescriptionV2** – opis dodatka 

- **AddinFileNameV2** – ime datoteke DLL dodatka. Ne vključuje lokacije datoteke.

- **AddinFriendlyNameV2** – prijazno ime dodatka

- **AddinIdV2** – ID razreda dodatka (CLSID)

- **AddinProgIdV2** – ID programa dodatka 

- **AddinProviderV2** – ponudnik dodatka 

- **AddinTimeDateStampV2** – časovni žig prevajalnika

- **AddinVersionV2** – različica dodatka 

- **Interface** – vmesnik COM dodatka, ki je povzročil zrušitev 

- **LoadAttempts** – ponazarja število poskusov nalaganj pred zrušitvijo 

- **Method** – metoda COM dodatka, ki je povzročila zrušitev 


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

Sproženo ob odpiranju makra (VBA), ki vsebuje datoteko v napravi, ki je bila na voljo za Officeove aplikacije kot storitev (OAAS), ki jo je opravil skrbnik IT in kjer je bil aktiviran Microsoft 365 apps za podjetja z licenco za podjetja. Dogodek se uporablja za razumevanje stanja dokumentov, ki vsebujejo makro (VBA) v najemniku in se primerja z Office.Programmability.Telemetry.VbaTelemetryBreak, ki sledi napakam v datotekah, ki vsebujejo VBA. 

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

- **Event Name** – Kategorija dogodka in oznaka dogodka predstavljata ime dogodka

#### <a name="onenotesafebootresetcrashcounteronappsuspend-officeonenoteandroidsafebootresetcrashcounteronappsuspend-officeandroidearlytelemetrysafebootresetcrashcounteronappsuspend"></a>OneNote.SafeBootResetCrashCounterOnAppSuspend, Office.OneNote.Android.SafeBootResetCrashCounterOnAppSuspend, Office.Android.EarlyTelemetry.SafeBootResetCrashCounterOnAppSuspend

Kritični signal je poslan, ko ponastavljamo števec zrušitev za zaustavitev aplikacije, preden je prikazano pogovorno okno za varen zagon. Ta oznaka je zahtevana za spremljanje in diagnosticiranje ustreznosti stanja aplikacije. Pogovorno okno za varen zagon se prikaže takrat, ko se aplikacija večkrat zaporedoma zruši. Uporabnik ima tako možnost, da ponastavi aplikacijo. S to oznako bomo lahko ugotovili, ali pogovorno okno za varen zagon ni bilo prikazano uporabniku, čeprav so bili izpolnjeni pogoji za sproženje. 

Zbrana so sledeča polja:

- Nobeno


#### <a name="telemetryerror"></a>telemetry.error

S tem dogodkom lahko diagnosticiramo in odpravimo težave, ki preprečujejo ustvarjanje ali pošiljanje zahtevnih diagnostičnih podatkov. S temi dogodki ugotovimo, ali imamo na voljo vse kritične podatke, zahtevane za prepoznavanje varnostnih težav ali večjih težav z delovanjem vaše aplikacije.

Zbrana so sledeča polja: 

- **timer_name** – prikaže mesto napake telemetrije, npr. v komponenti nabiralnika ali koledarju. S tem dogodkom lahko zaznamo in odpravimo napake telemetrije, ki se pojavijo v določenem delu aplikacije.

- **type** – prikaže vrsto napake časovnika, s katero lahko ugotovimo, kdaj se v aplikaciji pojavljajo težave pri pošiljanju diagnostičnih podatkov telemetrije.


#### <a name="watchdoganr"></a>watchdog.anr

Ti dogodki so zahtevani za nadzor napak učinkovitosti delovanja aplikacije, da preprečimo primere, ko se aplikacija preneha odzivati, vaš zaslon pa postane neodziven v aplikaciji (neodzivnost aplikacije, angleško ANR).

Zbrana so sledeča polja: 

- **callstack** – seznam klicev kode s primeri neodzivne aplikacije.
 
- **caused_restart** – ali je bil zaradi neodzivnosti zahtevan vnovičen zagon aplikacije.
 
- **duration** – čas, ko je bila naprava neodzivna.
 
- **id** – enoličen identifikator za neodzivnost aplikacije.
 
- **interval** – konfigurirani prag za aktviranje neodzivnosti aplikacije.
 
- **is_application_object_initialized** – ali je do neodzivnosti aplikacije prišlo po tem, ko je bila aplikacija v celoti inicializirana ali pred tem.
 
- **last_known_is_in_foreground** – ali je bila aplikacija nedavno uporabljena v osprednji oz. ozadju.


### <a name="application-feature-performance-subtype"></a>*Podvrsta za učinkovitost delovanja funkcije aplikacije*

Slab odzivni čas ali slaba učinkovitost za scenarije, kot sta zagon aplikacije ali odpiranje datoteke.

#### <a name="androidframemetrics"></a>android.frame.metrics

Omogoča nam, da zaznamo in odpravimo primere, kjer komponente naše aplikacije za sistem Android povzročajo težavi z učinkovitostjo delovanja, npr. ali pomikanje po mapi »Prejeto« ne poteka neovirano.

Zbrana so sledeča polja: 

- **animation_duration** – trajanje upodobitve animacije v milisekundah.

- **command_issue_duration** – trajanje ukazov v okolju v milisekundah. 

- **draw_duration** – trajanje upodobitve uporabniškega vmesnika v milisekundah. 

- **input_handling_duration** – trajanje obdelave vnosa v milisekundah. 

- **layout_measure_duration** – trajanje meritve postavitve v milisekundah.

- **origin** – komponenta aplikacije, ki bo izmerjena, na primer koledar ali pošta.

- **sync_duration** – čas, zahtevan za sinhronizacijo okvirja, v milisekundah.

- **swap_buffers_duration** – čas, zahtevan za zamenjavo medpomnilkov, v milisekundah.

- **total_duration** – skupni čas trajanja upodabljanja okvirja v milisekundah.

- **unknown_delay** – zakasnitev zaradi neznanih virov, vzrok katerih ni v izrecno spremljanih trajanjih.

#### <a name="calcomponent"></a>cal.component

S tem dogodkom lahko zaznamo in odpravimo težave, ki povzročajo občutno slabšo učinkovitost delovanja na naše komponente uporabniškega vmesnika koledarja, zaradi katerih lahko pride do težav med pomikanjem.

Zbrana so sledeča polja: 

- **above_40fps** – število okvirjev, upodobljenih nad 40 slik/s

- **above_40fps** – število okvirjev, upodobljenih nad 40 slik/s

- **above_50fps** – število okvirjev, upodobljenih nad 50 slik/s

- **above_50fps** – število okvirjev, upodobljenih nad 50 slik/s

- **above_55fps** – število okvirjev, upodobljenih nad 55 slik/s

- **above_55fps** – število okvirjev, upodobljenih nad 55 slik/s

- **account_counter** – spremlja število računov, povezanih s posameznimi vrstami koledarja, na primer 2 za Gmailov koledar, in ali ta račun uporablja našo novo storitev sinhronizacije.

- **app_instance** – v Outlooku sta na voljo dve vstopni točki za Duo, ena za koledar, druga za pošto, obe pa ju lahko uvedete drug ob drugem v okolju z več primerki. S tem nam sporočite, na primer, kako bo ta poklic za poročanje, ali pošta ali koledar.

- **component_name** – prikaže ime komponente koledarja, kot je pogled dnevnega reda ali dnevni pogled, da lahko zaznamo težave pri učinkovitosti delovanja, ki vplivajo na določeno komponento v koledarju.

- **display_frame_data** – spremlja čas, porabljen za prikaz 60 okvirjev, da lahko ugotovi, ali se pojavljajo težave z učinkovitostjo delovanja. 

- **orientation** – prikaže način usmerjenosti naprave (pokončno ali ležeče) in nam pomaga zaznati težave z učinkovitostjo delovanja, ki vplivajo na določeno usmerjenost naprave.

- **taskId** – TaskId nam bo dal trenutni primerek taskId. To bo zahtevano v okolju z več primerki, če želi uporabnik zagnati enake primerke (koledar, koledar ali pošta, pošta) drug ob drugem

- **view_duration** – prikaže čas, zahtevan za upodobitev različnih komponent uporabniškega vmesnika koledarja, in nam pomaga zaznati težave z učinkovitostjo delovanja, ki vplivajo na vašo izkušnjo uporabe koledarja.

#### <a name="contactaction"></a>contact.action

Ta dogodek se sproža z različnimi dejanji v zvezi z ogledom, posodabljanjem in brisanjem stikov ter ogledom seznama stikov. Uporablja se, da ugotovite, ali so na voljo regresivne učinkovitosti delovanja s stiki.

Zbrana so sledeča polja: 

- **accounts_with_filters** – število računov s filtri, ki so bili uporabljeni na seznamu stikov

- **dejanje** – dejanje, ki je bilo izvedeno, na primer ogled stika
 
- **duration_initial_view_load** – trajanje z odpiranjem pogleda na prvotno nalaganje seznama stikov

- **duration_show_contacts** – trajanje, da odprete pogled tako, da prikazuje stike na seznamu stikov.
 
- **total_contacts** – število stikov brez filtrov, ki je uporabljeno
 
- **total_filtered_contacts** – število stikov z uporabljenimi filtri

#### <a name="conversationloadtime"></a>conversation.load.time

S tem dogodkom lahko zaznamo in odpravimo težave, ki povzročajo občutno slabšo učinkovitost delovanja pri nalaganju pogovorov prek e-pošte, in tako zagotovimo, da se vaše e-poštna sporočila nalagajo po pričakovanjih.

Zbrana so naslednja polja: 

- **time** – čas, zahtevan za nalaganje pogovora prek e-pošte v celoti.

#### <a name="conversationreloaded"></a>conversation.reloaded

Ta dogodek omogoča zaznavanje pogostosti ponovnega nalaganja pogovora glede na obvestila o storitvi. Spremljati je treba, ali so obvestila o posodobitvah preobsežna in jih je treba obrezati, ker negativno vplivajo na uporabnost.

Zbrana so ta polja: 

- **average** – količina vnovičnih nalaganj glede na velikost 

- **client-request-ID** – identifikator zahteve odjemalca za zahtevo, ki je povzročila napako

- **date** – časovni žig zahteve, ki je povzročila napako

- **duration** – koliko časa je bil pogovor odprt 


#### <a name="coredatamigration"></a>core.data.migration

S tem dogodkom lahko zaznamo in odpravimo primere napak pri posodabljanju podatkov e-pošte v vaši napravi na novejšo različico.

Zbrana so sledeča polja:

- **db_size_megabytes** – spremlja velikost osnovne zbirke podatkov, zaokroženo na najbližjih 25 MB in z najvišjo zmogljivostjo 500 MB.

- **db_wal_size_megabytes** – spremlja velikost osnovne zbirke podatkov, ko je datoteka glavne shrambe nespremenjeno zaokrožena na najbližji 1 MB in z najvišjo zmogljivostjo 10 MB.

- **free_space_megabytes** – spremlja nezaseden prostor v vedrih 10, 100, 1000, 10.000 in nato 100.000. 

- **migration_duration_seconds** – spremlja trajanje selitve, zaokroženo na enega od teh časovnih okvirjev: 0, 10, 20, 30, 40, 50, 60, 70, 80, 90, 100, 110, 120, 130, 140, 150, 160, 170, 180 (kar je več od 180, ostane 180).

#### <a name="coredataperformance"></a>core.data.performance

S tem dogodkom lahko zaznamo in odpravimo primere, kjer težave e-pošte, ki jih shranjujemo v vašo napravo, povzročajo težave pri učinkovitosti delovanja.

Zbrana so sledeča polja:

- **Caller** – spremlja ime entitete, ki pokliče operacijo shranjevanja.

- **db_size_megabytes** – spremlja velikost osnovne zbirke podatkov, zaokroženo na najbližjih 25 MB in z najvišjo zmogljivostjo 500 MB.

- **duration** – čas, zahtevan za dokončanje operacije.

- **entity** – spremlja ime entitete, ki pokliče operacijo pridobivanja.

- **operation** – nespremenjena vrednost operacije shranjevanja, pridobivanja ali »branje/pisanje vrste je blokirano«.

#### <a name="inboxcomponent"></a>inbox.component

Ta dogodek zbere dve vrsti podatkov o uporabniku: stanje naročnine na Microsoft 365 in prikaz oglasov uporabniku. S tem dogodkom lahko zaznamo in odpravimo težave, ki povzročajo občutno slabšo učinkovitost delovanja komponent uporabniškega vmesnika za nabiralnik. Zaradi teh težav e-poštna sporočila, avatar, stanje prebranih/neprebranih sporočil morda ne bodo naloženi ali prikazani pravilno.

Zbrana so naslednja polja: 

- **above_40fps** – število okvirjev, upodobljenih nad 40 slik/s

- **above_40fps** – število okvirjev, upodobljenih nad 40 slik/s

- **above_50fps** – število okvirjev, upodobljenih nad 50 slik/s

- **above_50fps** – število okvirjev, upodobljenih nad 50 slik/s

- **above_55fps** – število okvirjev, upodobljenih nad 55 slik/s

- **above_55fps** – število okvirjev, upodobljenih nad 55 slik/s

- **account_counter** – števec posameznih vrst računov v napravi, na primer račun za Office 365 = 1 račun, račun za Outlook.com = 1 račun.

- **ad_not_shown_reason** – razlog, zakaj oglasi niso prikazani.

- **ad_shown** – prikaže, ali je bil oglas prikazan (če so oglasi omogočeni).

- **ad_shown_for_premium** – nepričakovan prikaz oglasa uporabnikom različice Premium

- **age** – staroste osebe (uporablja se za zagotavljanje skladnosti s predpisi glede staroste omejitve za oglase) *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar je lahko še vedno prikazano v starejših graditvah.]*

- **app_instance** – v Outlooku sta na voljo dve vstopni točki za Duo, ena za koledar, druga za pošto, obe pa ju lahko uvedete drug ob drugem v okolju z več primerki. S tem nam sporočite, na primer, kako bo ta poklic za poročanje, ali pošta ali koledar.

- **component_name** – ime komponente/pogleda, ki je aktiven med filtriranjem

- **has_hx** – prikaže, ali je v napravi vsaj en račun Hx (naša nova storitev za sinhronizacijo e-pošte).

- **has_subscription** – prikaže, ali je naprava naročena na oglase.

- **is_all_accounts_inbox** – prikaže, ali je trenutni nabiralnik mapa »z vsemi računi«.

- **is_current_account** – prikaže, ali je za račun za oglase izbran trenutno aktivni račun.

- **load_error_code** – koda napake pri nalaganju oglasov.

- **network_error_code** – koda omrežne napake pri zahtevanju oglasov.

- **orientation** – usmerjenost zaslona ob dogodku (pokončna ali ležeča).

- **provider** – ponudnik (Xandr ali Facebook) trenutno prikazanega oglasa

- **sub_error_type** – vrsta napake s podrobnostmi

- **taskId** – TaskId nam bo dal trenutni primerek taskId. To bo zahtevano v okolju z več primerki, če želi uporabnik zagnati enake primerke (koledar, koledar ali pošta, pošta) drug ob drugem

- **total_count** – skupno število okvirjev, ki jih prikaže komponenta.

- **view_duration** – čas, ko si je uporabnik ogledoval komponento.

#### <a name="initialpagelanding"></a>Initial.page.landing 
 
Ta dogodek nam pomaga slediti vrsti izkušnje, ki je prikazana uporabnikom, ko se znajdejo na strani aplikacije.  Te podatke uporabljamo za ugotavljanje prometa uporabnikov, ki se steka v okviru posamezne izkušnje v aplikaciji, in za lažje usklajevanje rezultatov eksperimentiranja.
 
Zbrana so naslednja polja: 

- **Stran** – to se uporablja se za sledenje vrsti izkušnje, ki je uporabniku najprej prikazana, ko se znajde na naši strani. Možne vrednosti so »Preskusna različica«, »Preskoči«, »V paketu«, »Naročnina« itn.

- **storeExperience** – to se uporablja za ugotavljanje, ali je bil uporabnik upravičen do ogleda izkušnje SDK za Store.

- **stringVariant** – to se uporablja za ugotavljanje vrste nizov, ki so prikazani uporabnikom, ko se znajdejo na naši strani. Na vsaki strani, npr. »Preskusna različica«, je uporabnik upravičen do ogleda različnih nizov, in sicer glede na to, ali ima nameščen podedovan Office ali če je že kdaj prej aktiviral Office. Možni elementi naštevanja za to lastnost so »LegacyUpsell«, »OfficeOpened«, »Privzeto «, »YesIntent«, »NoIntent« itd.

- **windowsBuildType** – to se uporablja za sledenje vrsti graditve WindowsBuildType, ki jo uporabnik uporablja. Na primer »RS4«,»RS5«,»RS19H1«,»Vibranium« ipd. Ker so izkušnje običajno namenjene različnim vrstam graditve WindowsBuildTypes, je ta lastnost ključnega pomena pri razlikovanju med uvedbami. 

#### <a name="ipcpbootstrapuser"></a>IpcpBootstrapUser

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij ali uporabiti zaščito za upravljanje pravic do informacij. Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede priklic API IpcpBootstrapUser.

Zbrana so naslednja polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se aplikacija izvaja v produkcijskem okolju ali v okolju razvijalcev

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

#### <a name="ipcpgetkey"></a>IpcpGetKey

Zbira, ko uporabnik poskuša odpreti dokument, zaščiten z upravljanjem pravic do informacij (IRM) ali uporabiti zaščito za upravljanje pravic do informacij. Vsebuje informacije, potrebne za ustrezno raziskovanje in diagnosticiranje težav, do katerih pride, ko se izvede priklic API IpcpGetKey.

Zbrana so sledeča polja:

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se aplikacija izvaja v produkcijskem okolju ali v okolju razvijalcev

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

- **RMS.EulId** – ID licence končnega uporabnika

- **RMS.EulProvided** – označuje, ali je licenca končnega uporabnika podana kot vnos klica API ali ne

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

- **RMS.PL.ExtranetUrl** – ekstranetni URL v licenci za objavljanje

- **RMS.PL.IntranetUrl** – intranetni URL v licenci za objavljanje

- **RMS.PL.KeyType** – vrednosti »enojno« ali »dvojno«. Označuje, ali je bil PL zaščiten z zaščito z enojnim ali dvojnim ključem.

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

#### <a name="jsonparseerror"></a>json.parse.error 
 
Ta dogodek pomeni, da je razčlenjevalnik JSON vrnil napako.  Omogoča nam, da odpravimo napake v nizu bralnega registra, ki je bil poslan razčlenjevalniku JSON, in uporabnikom zagotovimo nemoteno izkušnjo.
 
Zbrana so naslednja polja: 

- **Napaka** – to vključuje sporočilo o napaki, ki ga vrne predmet napake.

#### <a name="mailfiltercomponent"></a>mail.filter.component

S tem dogodkom lahko zaznamo in odpravimo težave, ki povzročajo občutno slabšo učinkovitost pri filtriranju e-pošte. Zaradi teh težav filtri morda ne bodo naloženi ali prikazani pravilno.

Zbrana so naslednja polja: 

- **above_40fps** – število okvirjev, upodobljenih nad 40 slik/s

- **above_40fps** – število okvirjev, upodobljenih nad 40 slik/s
 
- **above_50fps** – število okvirjev, upodobljenih nad 50 slik/s

- **above_50fps** – število okvirjev, upodobljenih nad 50 slik/s
 
- **above_55fps** – število okvirjev, upodobljenih nad 55 slik/s

- **above_55fps** – število okvirjev, upodobljenih nad 55 slik/s
 
- **account_counter** – števec posameznih vrst računov v napravi, na primer račun za Office 365 = 1 račun, račun za Outlook.com = 1 račun.
 
- **ad_not_shown_reason** – razlog, zakaj oglasi niso prikazani.
 
- **ad_shown** – prikaže, ali je bil oglas prikazan (če so oglasi omogočeni).
 
- **age** – starost osebe (se uporablja za potrditev skladnost glede omejitev let v oglasih).

- **app_instance** – v Outlooku sta na voljo dve vstopni točki za Duo, ena za koledar, druga za pošto, obe pa ju lahko uvedete drug ob drugem v okolju z več primerki. S tem nam sporočite, na primer, kako bo ta poklic za poročanje, ali pošta ali koledar.
 
- **component_name** – ime komponente/pogleda, ki je aktiven med filtriranjem
 
- **folder_type** – vrsta filtrirane mape (na primer nabiralnik, smeti, nesistemska mapa)
 
- **has_hx** – prikaže, ali je v napravi vsaj en račun Hx (nova storitev za sinhronizacijo e-pošte).
 
- **has_subscription** – prikaže, ali je naprava naročena na oglase.
 
- **is_all_accounts_inbox** – prikaže, ali je trenutni nabiralnik mapa »z vsemi računi«.
 
- **is_current_account** – prikaže, ali je za račun za oglase izbran trenutno aktivni račun.
 
- **load_error_code** – koda napake pri nalaganju oglasov.
 
- **network_error_code** – koda omrežne napake pri zahtevanju oglasov.
 
- **orientation** – usmerjenost zaslona ob dogodku (pokončna ali ležeča).
 
- **sub_error_type** – vrsta napake s podrobnostmi

- **taskId** – TaskId nam bo dal trenutni primerek taskId. To bo zahtevano v okolju z več primerki, če želi uporabnik zagnati enake primerke (koledar, koledar ali pošta, pošta) drug ob drugem
 
- **total_count** – skupno število okvirjev, ki jih prikaže komponenta.
 
- **view_duration** – čas, ko si je uporabnik ogledoval komponento.

#### <a name="messagerenderingintercepted"></a>message.rendering.intercepted

S tem dogodkom lahko spremljate, kako pogosto uporabniki prestrežejo postopke uporabljanja, preden so ti dokončani. Ta dogodek je uporabljen za zaznavanje težav z učinkovitostjo delovanja.

Zbrana so ta polja: 

- **is_cache** – ali je telo sporočila naloženo iz predpomnilnika

- **is_on_screen** – ali je postopek upodabljanja prikazan uporabnikom (običajno upodabljanje)

- **is_rendering_complete** – ali je postopek upodabljanja dokončan 

- **is_trimmed_body** – ali je telo sporočila obrezano 

- **rendering_method** – način upodabljanja sporočila

- **rendering_time** – trajanje upodabljanja sporočila, dokler uporabnik ne zapre strani

#### <a name="messagerenderingperformance"></a>message.rendering.performance

S tem dogodkom lahko spremljate učinkovitost delovanja postopka upodabljanja sporočila za namene analiziranja učinkovitosti različnih postopkov upodabljanja ter zaznavanja težav z delovanjem. 

Zbrana so ta polja: 

- **bundle_prepare_time** – čas, potreben za pripravo paketa za upodabljanje

- **full_rendering_time** – čas celotnega izvajanja postopka upodabljanja

- **is_cache** – ali je telo sporočila naloženo iz predpomnilnika

- **is_on_screen** – ali je postopek upodabljanja prikazan uporabnikom (običajno upodabljanje)

- **is_trimmed_body** – ali je telo sporočila obrezano 

- **load_message_time** – čas, potreben za nalaganje sporočila iz zalednega dela (je lahko 0, če je sporočilo na voljo v predpomnilniku)

- **native_preprocess_time** – čas, potreben za obdelavo telesa sporočila na izvornem mestu 

- **prepare_body_time** – čas, potreben za pripravo telesa sporočila (vključno z nalaganjem in obdelavo sporočila)

- **rendering_method** – način upodabljanja sporočila

- **rendering_time** – čas, potreben za upodabljanje sporočila glede na paket  

- **wait_time** – čas, potreben za ustvarjanje URL-ja sporočila


#### <a name="officeandroidandroidofficelaunchtolandingpagelatency"></a>Office.Android.AndroidOfficeLaunchToLandingPageLatency

Ključnega pomena za zajem meritev učinkovitosti delovanja aplikacije glede na odzivni čas aplikacije od zagona.  Microsoft s tem dogodkom zbira čas, zahtevan za odzivnost aplikacije, in za zaznavanje scenarijev, ki lahko vplivajo na čas zagona v aplikacijah Word, Excel ali PowerPoint..

Zbrana so naslednja polja:
 
- **AnyCrashInteractionDuringBoot** – Logična vrednost za morebitno zrušitev med zagonom.

- **AppActivationTimeInMs** – Čas zrušitve aplikacije.

- **AppSuspendedDuringBoot** – Logična vrednost za začasno prekinitev aplikacije med zagonom.

- **AvailableMemoryInMB, ki je na voljo** – Pomnilnik, ki je na voljo.

- **CollectionTime** – Čas dogodka.

- **DalvikHeapLimitInMB** – Informacije kopice.

- **DocumentRecoveryInvoked** – Logična vrednost, ki označuje, ali je bil dokument obnovljen.

- **ExtractionDone** – Čas ekstrahiranja izvorne knjižnice.

- **FastBootGainTimeInMs** – Čas, zahtevan za dokončanje hitrega zagona.

- **FileActivationAttempted** – Logična vrednost, ki označuje, ali je bila aplikacija zagnana zaradi aktivacije datoteke.

- **HasLogcatLoggingImpactOnBoot** – Logična vrednost, ki označuje, ali Logcat vpliva na čas zagona.

- **IsThisFirstLaunch** – Logična vrednost, ki označuje, ali je to prvi zagon aplikacije.

- **LatencyTimeInMilliSec** – Zakasnitev v milisekundah.

- **LibrarySharingTimeInMs** – Čas, zahtevan za skupno rabo knjižnic.

- **LoadMinLibsTimeInMs** – Čas nalaganja za najmanjši nabor knjižnic.

- **MruListingTimeInMs**– Čas, zahtevan za nalaganje MRU-ja.

- **NativeLibrariesLoadTime** – Čas, zahtevan za nalaganje knjižnic CPP.

- **NumberOfRunningProcesses** – Število procesov, ki se izvajajo.

- **NumberOfRunningProcesses** – Število procesov, ki se izvajajo.

- **NumberOfRunningServices** – Število storitev, ki se izvajajo.

- **OfficeActivityTimeInMs** – Čas, zahtevan za zagon Officeove dejavnosti.

- **PostAppInitTimeInMs** – Čas faze aplikacije.

- **PreAppInitializationTime** – Čas za zagon faze aplikacije.

- **PreAppInitTimeInMs** – Čas faze aplikacije.

- **TotalMemoryInMB** – Skupni pomnilnik.

- **UIRaaSDownloadLanguagePackageBoot** – Informacije, povezane s prenosom jezikovnega paketa.

- **UserDialogInterruptionDuringBoot** – Logična vrednost za blokiranje pogovornih oken med zagonom.


#### <a name="officeappleappleappbootmac"></a>Office.Apple.Apple.AppBoot.Mac

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za zbiranje podatkov o času, potrebnem za zagon aplikacije, in nekaterih podatkov o vrsti izvedenega zagona. Ta dogodek nam pomaga pri nadziranju učinkovitost delovanja in zagotavljanju izboljšav učinkovitosti delovanja.

Zbrana so naslednja polja:

- **Data_ Data_EvtBootTimerDocStageReady** – čas, ki je pretekel, dokler ni bila dosežena določena točka v kodi.

- **Data_DocumentRecoveryInvoked** – označuje, ali je bila med zagonom priklicana obnovitev dokumenta.

- **Data_EvtBootTimerBootIdle** – čas, ki je pretekel, dokler ni bila dosežena določena točka v kodi.

- **Data_EvtBootTimerFinishLaunchEnd** – čas, ki je pretekel, dokler ni bila dosežena določena točka v kodi.

- **Data_EvtBootTimerLaunchDidFinish** – čas, ki je pretekel, dokler ni bila dosežena določena točka v kodi.

- **Data_EvtBootTimerLaunchStart** – čas, ki je pretekel, dokler ni bila dosežena določena točka v kodi.

- **Data_EvtBootTimerMainStart** – čas, ki je pretekel, dokler ni bila dosežena določena točka v kodi.

- **Data_EvtBootTimerStaticInit** – čas, ki je pretekel, dokler ni bila dosežena določena točka v kodi.

- **Data_EvtDockStageReady** – čas, ki je pretekel, dokler ni bila dosežena določena točka v kodi.

- **Data_IsFileOpenAttempted** – označuje, ali je bil med zagonom izveden poskus odpiranja datoteke.

- **Data_IsFirstRunAttempted** – označuje, ali je bila pri zagonu aplikacije izvedena uporabniška izkušnja prvega zagona.

- **Data_SentToBackground** – označuje, ali je bila med zagonom aplikacija poslana v ozadje.

#### <a name="officeapplediskruleresultserializererroronstreamop"></a>Office.Apple.DiskRuleResultSerializerErrorOnStreamOp

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za nadziranje ustreznosti stanja infrastrukture telemetrije. Ta dogodek pomeni, da je prišlo do napake.

Zbrana so sledeča polja:

- **Data_ActualBytesModified** – število spremenjenih bajtov.

- **Data_BytesRequested** – število bajtov za obdelavo.

- **Data_IsWriteOp** – označuje, ali bo kmalu izvedena operacija pisanja.

#### <a name="officeapplemacbootresourceusage"></a>Office.Apple.MacBootResourceUsage

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za zbiranje podatkov o več kazalnikih v povezavi z viri, ki so v uporabi med zagonom z Officeovimi aplikacijami. Ta dogodek nam pomaga pri nadziranju učinkovitost delovanja in zagotavljanju izboljšav učinkovitosti delovanja.

Zbrana so naslednja polja:

- **Data_BlockInputOperations** – število operacij blokiranja vhoda

- **Data_BlockOutputOperations** – število operacij blokiranja izhoda

- **Data_InvoluntaryContextSwitches** – število nenamernih skokov v drug odsek

- **Data_MainThreadCPUTime** – merjenje pretečenega časa

- **Data_MaxResidentSize** – merjenje velikosti pomnilnika

- **Data_MessagesReceived** – število prejetih sporočil

- **Data_MessagesSent** – število poslanih sporočil

- **Data_PageFaults** – število vnovičnih prevzemov strani

- **Data_PageReclaims** – število vnovičnih prevzemov strani

- **Data_ProcessCPUTime** – merjenje pretečenega časa

- **Data_SharedTextMemorySize** – merjenje velikosti pomnilnika

- **Data_SignalsReceived** – število prejetih signalov

- **Data_Swaps** – število zamenjav podatkov

- **Data_SystemCPUTime** – merjenje pretečenega časa

- **Data_SystemUpTime** – merjenje pretečenega časa

- **Data_UnsharedDataSize** – merjenje velikosti podatkov

- **Data_UnsharedStackSize** – merjenje velikosti sklada

- **Data_UserCPUTime** – merjenje pretečenega časa

- **Data_VoluntaryContextSwitchesNvcsw** – število namernih skokov v drug odsek

#### <a name="officeapplemauvalidation"></a>Office.Apple.MAU.Validation

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za nadziranje ustreznosti stanja komponente Microsoft Autoupdate, ki se uporablja za pošiljanje in nameščanje posodobitev aplikacij. Zbrane podatke uporabljamo za odkrivanje napak in preiskovanje vzrokov napak.

Zbrana so sledeča polja:

- **Data_EventID** – zbiramo niz, ki predstavlja kodo napake

- **Data_Message** – zbiramo niz, ki vsebuje opis napake

#### <a name="officeapplembuinstrumenthangdetectionspincontrol"></a>Office.Apple.MbuInstrument.Hang.Detection.Spin.Control

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek se zabeleži vsakič, ko je videti, da se je aplikacija prenehala odzivati. Ta dogodek nam pomaga pri nadziranju učinkovitost delovanja in zagotavljanju izboljšav učinkovitosti delovanja.

Zbrana so naslednja polja:

- **Data_CountSpinControlStart** – oznaka, ki označuje neodzivnost aplikacije (ali počasno odzivanje)

#### <a name="officeapplembuinstrumentvmondocumentclose"></a>Office.Apple.MbuInstrument.VMOnDocumentClose

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za zbiranje posnetka stanja pomnilnika pri zapiranju dokumenta. Ta dogodek nam pomaga pri nadziranju učinkovitost delovanja in zagotavljanju izboljšav učinkovitosti delovanja.

Zbrana so naslednja polja:

- **Data_CollectionTime** – časovni žig trenutka, ko so bili zbrani podatki

- **Data_ResidentMemory** – zaznana vrednost stalnega pomnilnika

- **Data_VirtualMemory** – zaznana vrednost navideznega pomnilnika

#### <a name="officeapplembuinstrumentvmonshutdown"></a>Office.Apple.MbuInstrument.VMOnShutdown

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za zbiranje posnetka stanja pomnilnika pri zaustavitvi aplikacije. Ta dogodek nam pomaga pri nadziranju učinkovitost delovanja in zagotavljanju izboljšav učinkovitosti delovanja.

Zbrana so naslednja polja:

- **Data_CollectionTime** – časovni žig trenutka, ko so bili zbrani podatki

- **Data_ResidentMemory** – zaznana vrednost stalnega pomnilnika

- **Data_VirtualMemory** – zaznana vrednost navideznega pomnilnika

#### <a name="officeapplembuinstrumentvmonstart"></a>Office.Apple.MbuInstrument.VMOnStart

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za zbiranje posnetka stanja pomnilnika pri zagonu aplikacije. Ta dogodek nam pomaga pri nadziranju učinkovitost delovanja in zagotavljanju izboljšav učinkovitosti delovanja.

Zbrana so naslednja polja:

- **Data_CollectionTime** – časovni žig trenutka, ko so bili zbrani podatki

- **Data_ResidentMemory** – zaznana vrednost stalnega pomnilnika

- **Data_VirtualMemory** – zaznana vrednost navideznega pomnilnika

#### <a name="officeapplemsoappdelegatebootperf"></a>Office.Apple.MsoAppDelegate.BootPerf

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za zbiranje podatkov o času in prostoru v pomnilniku, porabljenima med zagonom z Officeovimi aplikacijami ter nekaj podatkov o vrsti izvedenega zagona. Ta dogodek nam pomaga pri nadziranju učinkovitost delovanja in zagotavljanju izboljšav učinkovitosti delovanja.

Zbrana so naslednja polja:

- **Data_AppLaunchDurationMicroSec** – trajanje postopka zagona

- **Data_AppLaunchFinishSystemTime** – časovni žig pri določeni oznaki kode zagona

- **Data_AppLaunchStartSystemTime** – časovni žig pri določeni oznaki kode zagona

- **Data_ResidentMemory** – posnetek stalnega pomnilnika, ki je na voljo med zagonom

- **Data_VirtualMemory** – posnetek navideznega pomnilnika, ki je na voljo med zagonom

#### <a name="officeappleungracefulappexithangsinprevioussession"></a>Office.Apple.UngracefulAppExitHangsInPreviousSession

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za nadzorovanje ustreznosti stanja Officeovih aplikacij in preiskovanje vzrokov napak. Zbiramo podatke o tem, kolikokrat je bila aplikacija neodzivna, preden je prišlo do izhoda iz aplikacije z napakami.

Zbrana so naslednja polja:

- **Data_HangsDetected** – označuje, kolikokrat je bila aplikacija neodzivna, preden je bil zaznan izhod iz aplikacije z napakami.

- **Data_LastSessionId** – identifikator seje, pri kateri je bil zaznan izhod iz aplikacije z napakami.

- **Data_SessionBuildNumber** – podrazličica aplikacije, pri kateri je bil zaznan izhod iz aplikacije z napakami.

- **Data_SessionVersion** – glavna različica aplikacije, pri kateri je bil zaznan izhod iz aplikacije z napakami.

#### <a name="officeapplewhatsnewerrorandwarning"></a>Office.Apple.WhatsNewErrorAndWarning

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za nadziranje ustreznosti stanja funkcije »Novosti«. Ta dogodek pomeni, da je med razčlenjevanjem vsebine »Novosti« prišlo do napake/opozorila, kar kaže na morebitne težave z avtorstvom vsebine.

Zbrana so naslednja polja:

- **Data_ContentKey** – kazalec na del vsebine, ki je verjetno povzročil napako.

- **Data_ErrorCode** – zaznana koda napake (če je na voljo)

- **Data_ErrorDescription** – opis napake (če je na voljo)

- **Data_EventID** – zbiramo niz, ki predstavlja vrsto zaznane napake.

- **Data_IncludesHTMLTag** – označuje, ali vsebina vključuje obogateni html

- **Data_IncludesItemsTag** – označuje, ali vsebina vključuje hierarhijo elementov

- **Data_LengthOfRawData** – velikost vsebine

- **Data_RequestURL** – spletni naslov, s katerega je bila vsebina prenesena

- **Data_ServerLanguageTag** – jezik, v katerem je bila vsebina.

- **Data_StatusCode** – stanje napake (če je na voljo)

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

#### <a name="officeiospaywallfailedscreenretrybuttontap"></a>Office.iOS.Paywall.FailedScreen.RetryButtonTap

Ta telemetrijo uporabe je zbrana tako, da se ugotovi, kdaj nakup/omogočanje uporabe/aktivacija ni uspela, uporabnik pa je potrkal gumb »poskusi znova«.  Uporablja se za odpravljanje težav z nakupi scenarijev, ki vodijo do ponovne uporabe in izboljšanje zanesljivosti procesov.

Zbrana so sledeča polja:

- **failureReason** – niz, ki označuje, kaj je bila napaka uporabnika. Kot »provisioningFailed«, »purchaseFailed«, »activationFailed«.

- **ID izdelka, ki je naveden v** -string – shramba aplikacije za izdelek, za katerega uporabnik znova ne poskuša izvesti zahteve


#### <a name="officemanageabilityserviceapplypolicy"></a>Office.Manageability.Service.ApplyPolicy

Kritična telemetrija za sledenje neuspeha\\uspeha pri uporabi nastavitev pravilnika v oblaku v registru. Iz elementa LastError je razvidno, zakaj in kje je prišlo do napake pri uveljavljanju pravilnika v registru.

Zbrana so sledeča polja:

  - **Data.ApplyLogMsg** – sporočilo izjeme, če je bil uveljavljen pravilnik while

  - **Data.Cid** – dinamično ustvarjeni identifikator korelacije, poslan storitvi, ko je bil opravljen klic storitve za pridobivanje pravilnika v oblaku. Uporablja se za medsebojno odvisnost pri uporabi pravilnikov v oblaku

  - **Data.Last Error** – ena od petih vrednosti niza (popisovalnik) za beleženje, katera stopnja pravilnika je bila izvedena, ko je prišlo do izjeme

#### <a name="officeonenoteandroidsyncprovisioningcompleted"></a>Office.OneNote.Android.Sync.ProvisioningCompleted

*[Ta dogodek je bil prej imenovan OneNote.Sync.ProvisioningCompleted.]*

Kritični signal se uporablja za pravilno nastavitev in uporabo zvezkov, po tem, ko se je uporabnik vpisal v aplikacijo OneNote za sistem Android, za omogočanje dostopa do zvezkov. Uporablja se za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in stanja storitve.

Zbrana so sledeča polja: 

- **AppSuspendedDuringEvent** – vrne logično vrednost, ki označuje, ali je bila aplikacija prekinjena med omogočanjem uporabe.

- **NetworkConnection** – vrsta omrežne povezave za uporabljeno napravo.

- **NetworkDataExchange** – zabeleži število bajtov, izmenjanih med omogočanjem uporabe.

- **ServerType** – vrne vrsto strežnika, ki ponuja storitev.

- **TimeTakenInMilliSeconds** – vrne čas, zahtevan za dokončanje omogočanja uporabe, v milisekundah.

#### <a name="officeonenoteandroidsyncprovisioningerror"></a>Office.OneNote.Android.Sync.ProvisioningError

Kritični signal se uporablja za pravilno nastavitev in uporabo zvezkov, po tem, ko se je uporabnik vpisal v aplikacijo OneNote za sistem Android, za omogočanje dostopa do zvezkov. Uporablja se za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in stanja storitve.

Zbrana so naslednja polja:

- **AppSuspendedDuringEvent**: vrne logično vrednost, ki označuje, ali je bila aplikacija prekinjena med omogočanje uporabe

- **ErrorCode** – vrne kodo napake, ki je odgovorna za neuspela omogočanje uporabe 

- **NetworkConnection**: vrsta omrežne povezljivosti naprave, ki je v uporabi

- **NetworkDataExchange** – zabeleži število bajtov, izmenjanih med omogočanjem uporabe.

- **ServerType**: vrne vrsto strežnika, ki ponuja storitev.

- **TimeTakenInMilliSeconds**: vrne čas, ki ga je treba izvesti za dokončanje uporabe v milisekundah


#### <a name="officeonenoteandroidsyncprovisioningstarted"></a>Office.OneNote.Android.Sync.ProvisioningStarted

*[Ta dogodek je bil prej imenovan OneNote.Sync.ProvisioningStarted.]*

Kritični signal se uporablja za pravilno nastavitev in uporabo zvezkov, po tem, ko se je uporabnik vpisal v aplikacijo OneNote za sistem Android, za omogočanje dostopa do zvezkov.  Uporablja se za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in stanja storitve.

Zbrana so sledeča polja: 

- **NetworkConnection** – vrsta omrežne povezave za uporabljeno napravo.

- **ServerType** – vrne vrsto strežnika, ki ponuja storitev.

#### <a name="officeonenotesystembootdialogssafebootdialogpending"></a>Office.OneNote.System.BootDialogs.SafeBootDialogPending 

Kritični signal, ki se uporablja za spremljanje, ko se odločimo, da bo uporabnik v pogovornem oknu »Safe boot« v naslednjem zagonu, ker se večkrat zrušimo v zagonu. Uporablja se za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in stanja storitve. Če bodo uporabniki videli pogovorno okno varnega zagona, je prišlo do kritične napake pri zagonu in v teh napravah je na voljo več informacij o tem, koliko uporabnikov se sooča s to težavo in koliko uporabnikov je znova zagnalo aplikacijo, da je v resnici prikazano pogovorno okno varni zagon proti število ne vrne.

Zbrana so sledeča polja:

 - Nobeno

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

- **MacOLKBootPerfDuration** – Skupni čas, porabljen za zagon.

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

- **ColdBoot** – ne glede na to, ali se Officeov program prvič zažene, ko je bil vnovični zagon sistema ali binarna aplikacija naložena z diska.

- **DeviceModel** – model naprave.

- **Data_DocumentLocation** – pri odpiranju dokumenta označuje, v kateri storitvi je na voljo dokument (OneDrive, File Server, SharePoint itd.).

- **DurationUntilMso20Initialization** – trajanje, ki je bilo uporabljeno v mikrosekundah med inicializacijo Officeovega postopka, in mso20win32client. dll je bil naložen.

- **Embedding** – Ali je bila aplikacija odprta za vdelovanje OLE.

- **FirstBoot** – ali je bil to prvi zagon aplikacije.

- **InitializationDuration** – koliko časa v mikrosekundah je preteklo za prvo inicializacijo Officeovega postopka.

- **InterruptionMessageId** – ID pogovornega okna, če je zagon prekinilo pogovorno okno, ki je uporabnika pozivalo k vnosu podatkov.

- **LegacyDuration** – Trajanje izvajanja dejavnosti, izmerjeno z drugimi začetnimi in končnimi točkami, kot so na voljo za »Activity.Duration«.

- **OpenAsNew** – Ali je bila aplikacija zagnana z odpiranjem obstoječega dokumenta kot predloge za novega.

- **TotalWorkingSetMB** – količina pomnilnika v megabajtih v delovnem naboru postopka.

- **VirtualSetMB** – količina pomnilnika v megabajtih v navideznem naboru postopka. (samo za MacOS/iOS)

- **WorkingSetPeakMB** – največja količina pomnilnika v megabajtih, ki je bila doslej v delovnem naboru postopka.


#### <a name="officepowerpointpptandroidrehearseview"></a>Office.PowerPoint.PPT.Android.RehearseView

Ta dogodek označuje, da je uporabnik ustavil sejo vaje. V kombinaciji s sistemom Office. PowerPoint. PPT. Android. RehearseView. StartSession bo to prvi pokazatelj morebitnih zrušitev ali napak, ki jih uporabnik srečuje.

Zbrana so sledeča polja:

- **ConnectionCreationTime** časa, ki je bil ustvarjen za ustvarjanje povezav storitve.

- **CountDownAlertTime** – čas, za katerega je bila prikazana odštevna opozorila.

- **CountdownInitTime –** času med dokončano obremenitvijo diaprojekcije in odštevanjem.

- **CritiqueSummary** – Povzetek vseh kritik, ki so jih uporabniki videli s svojimi računi.

- **ExitEventCode** – koda za prepoznavanje scenarija, v katerem je uporabnik zapustil sejo vaje, je bil scenarij z napako ali je sejo uspešno zapustil. 

- **FRETime** -čas med delom v oknu FRE se je začel prikazovati, dokler ga uporabnik ne zavrne. 

- **MicrophonePermissionTime** -čas, za katerega je bil prikazan opozorilni klic z mikrofonom, dokler uporabnik ne izbere ene od možnosti.

- **PauseRehearsingCount** – število uporabnikov, ki so večkrat kliknili »pavza« vaje.

- **RehearsalInitTime** –Čas, potreben za inicializacijo vaje.

- **ResumeRehearsingCount** – število uporabnikov, ki ste jih kliknili z navodili za vnovično uporabo.

- **Sessionid** – ID govorne seje z vhodnih vrat. Ta parameter se uporablja za odpravljanje napak v dnevnikih storitev.

- **SlideshowViewLoadTime** – Čas, potreben za nalaganje diaprojekcije.


#### <a name="officepowerpointpptandroidrehearseviewrehearsalsummarypage"></a>Office.PowerPoint.PPT.Android.RehearseView.RehearsalSummaryPage 

Dogodek, sprožen ob nalaganju strani s povzetkom. Ta dogodek nam pomaga pri zajemu strani s povzetkom. Pove, koliko časa traja, da se stran s povzetkom vaj naloži na odjemalca. Če želite, da je funkcija izvedena, morate obdržati funkcijo. 

Zbrana so sledeča polja:

- **PayloadCreationTime** – Čas v milisekundah, potreben za ustvarjanje koristne vsebine. 

- **PostUrlCallTime** – Čas v milisekundah, potreben za objavljanje klica Url. 

- **RehearseSessionId** – ID govorne seje z vhodnih vrat. Ta parameter se uporablja za odpravljanje napak v dnevnikih storitev.

- **RequestPayloadSize** – Velikost koristne vsebine zahteve. 

- **ResourcesLoadTime** – Čas v milisekundah, potreben za nalaganje virov (js, css). 

- **SummaryPageErrorReceived** – logična vrednost, ki označuje, ali je bila stran s povzetkom prejeta oziroma ali je prišlo do napake.

- **SummaryPageHtmlLoadTime** – Čas v milisekundah, potreben za nalaganje summarypageHtml. 

- **SummaryPageLoadStartTime** – Čas v milisekundah, potreben za prejemanje prvega odziva strežnika. 

- **SummaryPageLoadTime** – Čas (v ms), potreben za nalaganje strani s povzetkom. To vključuje čas ustvarjanja koristne vsebine 

- **ThumbnailsCount** – Skupno število sličic, ki bodo del strani s povzetkom. 

#### <a name="officepowerpointpptandroidrehearseviewstartsession"></a>Office.PowerPoint.PPT.Android.RehearseView.StartSession

Dogodek se sproži, ko uporabnik klikne začetno sejo. Ta dogodek nam pomaga pri zajemu števila uporabnikov, ki uporabljajo funkcijo trenerja predstavitelja v napravi s sistemom Android. Ko ste v kombinaciji z Officeom. PowerPoint. PPT. Android. RehearseView, nam bo pokazal, koliko uporabnikov je uspešno dokončala vajo in koliko jih ni bilo mogoče. To je naš prvi pokazatelj zrušitve ali napak v funkciji.
 
Zbrana so naslednja polja:

 - Nobeno


#### <a name="officepowerpointpptsharedrehearseviewerrors"></a>Office.PowerPoint.PPT.Shared.RehearseView.Errors

*[Ta dogodek je bil prej imenovan Office.PowerPoint.PPT.Android.RehearseView.Errors]*

Dogodek se sproži, ko pride do napake. S tem dogodkom pridobite napake, ki so bile prikazane uporabniku, ter zagotovite učinkovito delovanje inštrukcij za predstavitelja v prenosni napravi.

Zbrana so ta polja:

- **Session ID** – ID seje vaje

- **RehearsalEventCode** – koda napake vaje


#### <a name="officepowerpointrehearsalsessionmetrics"></a>Office.PowerPoint.Rehearsal.SessionMetrics 

Dogodek, ki je sprožen, ko je seja govora ustavljena za inštrukcije za predstavitelja. S tem dogodkom lahko zajamemo nekatere metrične podatke za sejo vaje v inštrukcijah za predstavitelja. Uporabili ga bomo za vzdrževanje visoke kakovosti te funkcije.

Zbrana so sledeča polja:

- **ActualRehearseBootTimeInMs** – Dejanski čas, potreben za ustvarjanje povezav.

- **AdaptationTextSize** – Velikost besedila, ki je poslano v storitev.

- **AuthDurationInMs** – To je čas v milisekundah, potreben za preverjanje pristnosti (osvežite žeton za preverjanje pristnosti).

- **AuthError** – To opisuje napako preverjanja pristnosti, do katere je prišlo (če je prišlo do nje).

- **AvgFragmentLatencyInMs** – To je povprečen čas, ki ga sporočila govora potrebujejo za povratno pot v omrežju.

- **ConnectDurationInMs** – To je čas v milisekundah, ki ga seja potrebuje za dokončanje povezave. 

- **FirstAudioDelayInMs** – To je čas v milisekundah, potreben za prejem prve zvočne datoteke.

- **FRetriedOnOpenConnection** – logična vrednost, ki označuje, ali je bil ponovni poskus izveden za odprto povezavo ali ne.

- **InitMediaCaptureLayerDurationInMs** – to je čas, ki ste ga odstranili v milisekundah, da inicializirate plast »Media/Audio Capture«.

- **LocallyDroppedMessageCount** – To je skupno število sporočil, opuščenih lokalno.

- **NumReconnectAttemptsDuringSession** – To označuje število poskusov ponovnega povezovanja s storitvijo govora.

- **NumTriesDuringEachReconnectAttempt** – To je polje, ki označuje število poskusov, izvedenih med posameznim poskusom ponovnega povezovanja.

- **OpenFrontDoorConnectionDurationInMs** – To je čas v milisekundah, potreben za odpiranje povezave do storitve FrontDoor.

- **SendAdaptationTextDurationInMs** – To je čas v milisekundah, ki je bil potreben za pošiljanje besedila adaptacije v storitev.

- **ServiceDroppedMessageCount** – To je skupno število sporočil, ki jih je opustila storitev.

- **SessionDurationInMs** – Trajanje celotne seje od trenutka, ko je uporabnik kliknil možnost začetka, do trenutka, ko je kliknil možnost ustavitve.

- **Sessionid** – ID govorne seje z vhodnih vrat. Ta parameter se uporablja za odpravljanje napak v dnevnikih storitev.

- **SpeechClientResultEventsWithTimestamps** – to je polje s kodami napak, prejetih skupaj s časovnimi žigi, ki so lahko v pomoč pri odpravljanju napak.

- **SpeechHResultsWithTimestamps** – to je polje s kodami napak, prejetih skupaj s časovnimi žigi, ki so lahko v pomoč pri odpravljanju napak.

- **StartSpeechCaptureDurationInMs** – to je čas v milisekundah, potreben za začetek zajema govora.

- **StartSpeechServiceDurationInMs** – to je polje časa, potrebnega za začetek seje govora pri vsakem ponovnem povezovanju, vključno s trajanjem prvega zagona seje govora. 

- **TotalMessageCount** – To je skupno število zvočnih sporočil, poslanih v storitev.

- **WebSocketConnectDurationInMs** – To je čas v milisekundah, potreben za dokončanje povezave s spletno vtičnico.


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

Ta dogodek zbira podatke o učinkovitosti odpiranja datotek za Visio Dev16. Ta dogodek se uporablja za nadzor učinkovitosti delovanja za odpiranje datoteke, ki jo poveže z lastnostmi datoteke, kot je velikost datoteke, za Visio Dev16. Lastnosti datoteke omogočajo hitrejše odkrivanje napak in korenskih vzrokov zanje.

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

  - **Data\_IsInternalFile: bool –** ima vrednost true, če gre za notranjo datoteko na primer šablona

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


#### <a name="onenoteappsafebootdialogactiontaken-officeonenoteandroidsafebootdialogactiontaken-officeandroidearlytelemetrysafebootdialogactiontaken"></a>OneNote.App.SafeBootDialogActionTaken, Office.OneNote.Android.SafeBootDialogActionTaken, Office.Android.EarlyTelemetry.SafeBootDialogActionTaken

Kritični signal, ki se uporablja za spremljanje odzivanja uporabnikov, ko se prikaže pogovorno okno varnega zagona. Pogovorno okno »Safe boot« je prikazano, ko ni bilo mogoče večkrat zagnati. Uporabnik, ki je na varnem zagonu, se uporablja kot dovoljenje za počistitev podatkov programa za uspešno uvedbo. Uporablja se za zagotavljanje zaznavanja kritične regresije za aplikacijo OneNote in stanja storitve. Uporabnik si ogleda, ko naleti na kritično napako z zagonskim zrušitvijo. S temi informacijami boste sledili odpravljanju vzrokov zrušitve in ali je uporabnik uspešno zagnal aplikacijo ali ne.

Zbrana so ta polja: 

- **DIALOG_ACTION** – kateri gumb »pogovornega okna« je uporabnik kliknil – gumb » pozitivna« ali »negativni gumb«


#### <a name="perfevent"></a>perf.event

Uporablja se za nadzor negativnega učinka pri nalaganju različnih komponent aplikacije, na primer za zagotovitev, da se pri prvem zagonu aplikacije vaš indeks čim prej naloži.

Zbrana so sledeča polja: 

- **app_start_show_message_list** – pojavila se je težava pri učinkovitosti delovanja med zagonom aplikacije, zaradi katere se je seznam sporočil v mapi »Prejeto« nalagal dolgo časa.

- **average** – zbere število izvedenih ponovnih nalaganj pogovora glede na število sporočil v določenem pogovoru.  

- **event_type** – prikaže vrsto dogodka učinkovitosti delovanja, zaradi katerega se je pojavila težava pri učinkovitosti delovanja. S tem dogodkom lahko zaznamo težave, povezane z določeno vrsto.   

- **extra_params** – razvijalec lahko doda dodatne parametre, s pomočjo katerih izvemo več podrobnosti o tem, kaj je lahko vzrok za težavo pri učinkovitosti delovanja, na primer začetek/konec tega dejanja itd. 

-   **has_work_profile** – ponazarja, ali se aplikacija izvaja v delovnem načinu za Android oz. podobni konfiguraciji, ter se uporablja za povezavo analize o učinkovitosti delovanja s temi sistemi.

- **profiling_summary** – ponuja informacije o skupini opravil, številu opravil in povprečnem času za te skupine, s katerimi lahko lažje razumete morebitna regresija na določenih območjih pri nalaganju aplikacije

- **runtime_performance_monitoring_data** – zagotavlja podatke o učinkovitosti delovanja (čas nalaganja, število zapisov) pri nalaganju podatkov v različnih delih aplikacije.
  - **average_cost_time_ns** – Povprečni čas stroškov v nanosekundah.
  - **cost_type** – Označuje, ali je ta dogodek namenjen merjenju izvajanja plasti shrambe ali skupnega trajanja.
  - **hx_object_type** – Zagotavlja podrobnosti o vrsti predmeta programiranja merjenja.
  - **is_main_thread** – Označuje, ali ta dogodek meri le čas izvajanja glavne niti.
  - **record_count** – Število zapisov, ki jih vrne temeljna plast shrambe.
  - **scope_name** – zagotavlja ime strani/komponent uporabniškega vmesnika, ki jim pripada ta dogodek.
  - **total_cost_time_ns** – Skupni čas izvajanja v nanosekundah. 

- **total_time_elapsed** – čas trajanja dogodka učinkovitosti delovanja, s katerim ugotovimo resnost težave pri učinkovitosti delovanja.

#### <a name="performancerecord"></a>performance.record

Ta dogodek zbira metriko učinkovitosti delovanja aplikacije. To nam omogoča, da zaznamo in odpravimo primere, kjer je poraba pomnilnika in CPE-ja izjemno visoka ali je prišlo do drugih težav z učinkovitostjo delovanja, kar lahko povzroči upočasnitev delovanja vaše naprave.

Zbrana so naslednja polja: 

- **app_exit_metric** – Prikaže metriko o številu različnih vrst zapiranj aplikacij v ospredju in ozadju, kar nam služi za lažje razumevanje nepričakovanih zapiranja aplikacij.

- **average_suspended_memory** – Prikaže povprečno količino pomnilnika, ki ga porabi aplikacija, ko je začasno prekinjena, kar nam služi za primerjavo ter lažje razumevanje negativnega vpliva.

- **category** – prikaže, ali se aplikacija trenutno izvaja v ospredju ali ozadju. Možni vrednosti sta »ospredje« in »ozadje«.

- **cpu_usage** – prikaže, koliko CPE-ja porabi aplikacija. S pomočjo tega dogodka lahko ugotovimo morebiten negativni učinek.

- **cumulative_CPU_time** – Prikaže, koliko časa CPE je porabila aplikacija, kar nam služi za primerjavo ter lažje razumevanje negativnega vpliva.

- **cumulative_GPU_time** – Prikaže, koliko časa GPE je porabila aplikacija, kar nam služi za primerjavo ter lažje razumevanje vpliva na skrajšan časa delovanja baterije.

- **is_watch_app_installed** – prikaže, ali uporabnik trenutno uporablja napravo Apple Watch in ali je ta nameščena. S tem dogodkom ugotovimo negativni učinek zaradi naprave Watch.

- **is_watch_paired** – prikaže, ali uporabnik trenutno uporablja napravo Apple Watch in ali je ta seznanjena z uporabnikovo napravo. S tem dogodkom ugotovimo negativni učinek zaradi naprave Watch.

- **is_watch_supported_and_active** – prikaže, ali uporabnik trenutno uporablja napravo Apple Watch in ali je ta aktivna. S tem dogodkom ugotovimo negativni učinek zaradi naprave Watch.

- **memoAry_used_percentage** – prikaže odstotek pomnilnika, ki ga aplikacija porabi. S pomočjo tega dogodka lahko ugotovimo morebiten negativni učinek.

- **memory_used** – prikaže, koliko pomnilnika porabi aplikacija. S pomočjo tega dogodka lahko ugotovimo morebiten negativni učinek.

- **peak_memory_usage** – Prikaže največjo količino pomnilnika, ki ga porabi aplikacija, kar nam služi za primerjavo ter lažje razumevanje negativnega vpliva.

- **scroll_hitch_time_ratio** – Prikaže razmerje časa, porabljenega za težave med pomikanjem po uporabniškem vmesniku, kar nam služi za lažje razumevanje negativnega vpliva na delovanje uporabniškega vmesnika.


### <a name="application-activity-error-subtype"></a>*Podvrsta napake pri dejavnosti aplikacije*

Napake v delovanju funkcije ali uporabniške izkušnje.

#### <a name="assertion"></a>assertion

S tem dogodkom lahko zaznamo, kdaj se pojavijo kritične napake aplikacije, ki lahko povzročijo zrušitev aplikacije ali resne težave, kot so prazne vrstice v vašem nabiralniku.

Zbrana so sledeča polja:

- **count** – skupno število elementov, povezanih z napako; na primer število koledarjev z napakami.

- **has_hx** – dogodek, ki ponazarja, da račun uporablja našo novo storitev sinhronizacije, s katerim je mogoče zaznati težave, ki jih povzroči naša storitev sinhronizacije.

- **host_name** – ime gostitelja storitve, ki je bil vključen v napako. Ta dogodek nam pomaga odkriti težave, povezane z določenim gostiteljem.

- **host_type** – vrsta gostitelja, ki je bil vključen v napako. Ta dogodek nam pomaga odkriti težave, povezane z določeno vrsto gostitelja.

- **message** – sporočilo po meri za izjavo, uporabljeno za diagnosticiranje težave. 

- **origin** – izvor napake v kodi za zaznavanje težav, povezanih z določenim delom kode.

- **stacktrace** – sled sklada, kjer se je pojavila izjava, za zaznavanje težav, povezanih z določenim delom kode.

- **type** – vrsta zaznane napake v izjavi, na primer null_folder_name, compose_selected_null_account, za pomoč pri zaznavanju težav, povezanih z določenim delom kode

#### <a name="editcontacterror"></a>edit.contact.error

Omogoča nam, da zaznamo in odpravimo primere, v katerih je prišlo do napak pri ogledu oziroma urejanju stikov v naši aplikaciji.

Zbrana so sledeča polja: 

- **errorType** – vrsta zaznane napake za pomoč pri diagnosticiranju težave.

- **field** – polje stika, ki ga je uporabnik želel urediti, za pomoč pri diagnosticiranju te težave.

- **version** – različica za storitev kartice stika, ki jo uporabljamo za pomoč pri diagnosticiranju težave.

#### <a name="errorreport"></a>error.report

S tem dogodkom lahko zaznamo kritične napake aplikacije in tako preprečimo težave, ki bi lahko povzročile zrušitev vaše aplikacije ali vam preprečevala branje e-pošte. 

Zbrana so sledeča polja: 

- **client-request-id** – identifikator zahteve odjemalca za zahtevo, ki je povzročila napako
 
- **date** – časovni žig zahteve, ki je povzročila napako

- **error** – vrsta napake, na primer get_mailbox_location_failed
 
- **error_body** – telo sporočila o napaki.
 
- **is_x_mailbox_anchor_set** – ali je bila v zahtevi uporabljena lastnost X-AnchorMailbox.
 
- **reason** – vzrok napake, na primer sporočilo o napaki
 
- **request-id** – identifikator zahteve strežnika za zahtevo, ki je povzročila napako
 
- **source** – vir napake v infrastrukturi OM, običajno »BE« ali »FE«.


#### <a name="officeairspacebackendwin32graphicsdriversofthang"></a>Office.AirSpace.Backend.Win32.GraphicsDriverSoftHang 

Microsoftu pomaga razlikovati dolgotrajne neodzivnosti gonilnika grafične kartice od kratkotrajnih. Na ta način je lažje določiti, pri katerih gonilnikih grafične kartice se je pojavila napaka. Gonilnik grafične kartice uporabnika je povzročil neodzivnost Officea, vpliv neodzivnosti pa še ni določen.

Zbrana so sledeča polja:

  - **Data\_InDeviceCall** – poklicani način grafične kartice, ki je povzročil neodzivnost

  - **Data\_Timeout** – čas neodzivnosti

  #### <a name="officeandroidadalsigninuiprompts"></a>Office.Android.ADALSignInUIPrompts

Ta dogodek ponazarja, da je bil uporabniku prikazan poziv za vpis v šolski ali službeni račun.  Ta dogodek omogoča lažje razumevanje stanja vpisa naših aplikacij in izvedbo ustreznih dejanj, ko zaznamo nepričakovane pozive za vpis. 

Zbrana so sledeča polja:

- **LastLoginDelta** – Delta čas zadnje uspešne prijave.

- **PreviousIdentityCredProviderState** – Označuje stanje računa.

- **PreviousIdentityState** – Označuje stanje računa, kot je potekla seja. 

- **SignInResultCode** – Označuje kodo rezultata za končanje poziva za vpis.

- **UseCache** – Označuje, ali smo uporabnika pozvali k ponovnemu vpisu gesla.

- **UserType** – Označuje, ali gre za obstoječi ali nov račun.

#### <a name="officeandroidandroidappdocsfileoperationends"></a>Office.Android.AndroidAppDocsFileOperationEnds

Telemetrični podatki kritičnih dokumentov samo za Android (AppDocs) za končanje operacij Datoteka > Novo/Odpri/Shrani kot. S tem dogodkom zabeležite kode napak za vse neuspešne operacije AppDocs.  Microsoft s tem dogodkom prepozna napake v različnih postopkih datoteke in plast, kjer je prišlo do napake v Wordu, Excelu ali PowerPointu.

Zbrana so naslednja polja:

- **AccessMode** – Vrednost oštevilčenja za način dostopa do datoteke. Vrednosti – None, ReadOnly, ReadOnlyUpgradable, ReadWrite

- **BlockingUIShown** – Logična vrednost, ki označuje, ali je bil v toku prikazan blokiran uporabniški vmesnik.

- **ContentUriAuthority** – overitelj URL-ja vsebina iz SAF.

- **Correlation** – GUID za ID korelacije, povezanega s postopkom.

- **DocId** – ID dokumenta, ki ga je ustvaril AppDocs.

- **DocInstanceId** – ID primerka dokumenta, ki ga je ustvaril AppDocs, glede na obseg primerka operacije v dokumentu.

- **DocIsEnterpriseProtected** – Logična vrednost, ki označuje, ali je dokument zaščiten.

- **DocUserId** – ID uporabnika iz plasti MS auth.

- **DocUserIdProvider** – Oštevilčenje, ki predstavlja ponudnika ID-ja uporabnika, 0 = neznano, 1 = LiveId, 2 = OrgId, 3 = SSPI, 4 = ADAL.

- **DurationInMs** – Čas v milisekundah, da se operacija datoteke konča.

- **EndReason** – Vrednost oštevilčenja za vzrok končanja.  Vrednosti – None, Success, Failure, Cancel

- **ErrorCode** – Koda napake za delovanje datoteke.

- **Extension** – Razširitev datoteke, ki jo želite odpreti.

- **FileSourceLocation** – Vrednost oštevilčenja za mesto datoteke. Morebitne vrednosti: None, Local, UncOrMappedNetworkDrive, SkyDrive, App, SharePoint, UnknownServer

- **FILETIME** – Čas dogodka.

- **FirstBCSClientError_Info** – Informacije o kodi napake, povezani s pretvorbami datotek.

- **HttpStatusCode** – Koda odziva http za zahtevo spletne storitve.

- **InitalizationReason** – Vstopna točka za odpiranje datoteke.

- **K2FileIOHresult** – Koda Hresult za končanje odpiranja datoteke.

- **LastBCSClientError_TagId** – Zadnja napaka v odjemalcu BCS (binarna storitev pretvorbe).

- **OfficeWebServiceApiStatusFlag** – Zastavica stanja za zahtevo spletne storitve.

- **OpEndEventId** – Oznaka, ki predstavlja, kje se je operacija dejansko končala.

- **OpFlags** – Zastavice parametrov za operacijo dokumenta, ki jih uporablja plast AppDocs.

- **OpSeqNum** – Število, ki predstavlja zaporedje klicev v zvezi z delovanjem datoteke v plasti AppDocs.

- **OpType** – Oštevilčenje vrste operacije. Vrednosti: »None«, »CreateDocument«, »OpenDocument«, »CopyDocument«, »CloseDocument«, »SaveDocument«, »OpenVersion«, »CloseVersion«.

- **PreFetchState** – Oštevilčenje za vnaprejšnje stanje predlog za ustvarjanje novih datotek.

- **ProviderApp** – Ime paketa aplikacije, v kateri se je odprla datoteka.

- **ScopeInstanceId** – ID primerka obsega, ki se uporablja za združevanje konteksta podatkov z dejavnostmi.

- **Size** – Velikost datoteke.

- **State** – Vrednost oštevilčenja za stanje datoteke. Vrednosti: None, Creating, Created, CreateFailed, Opening, Opened, OpenFailed, Copying, Copied, CopyFailed, Closing, Closed, CloseFail.

- **TemplateName** – ime dvojiške predloge dokumenta iz storitve predloge, npr. TF10002009.dotx

- **UriScheme** – Shema URL-ja.

#### <a name="officeandroidandroidautherror"></a>Office.Android.AndroidAuthError

Ta dogodek ponazarja ključne napake pri preverjanju pristnosti med tiho osvežitvijo žetona, nalaganjem vpisne strani iz storitve itd.  Ta dogodek omogoča lažje razumevanje stanja vpisa naših aplikacij, poskusov vpisov in izvedbo ustreznih dejanj, ko zaznamo nepričakovane pozive za vpis. 

Zbrana so naslednja polja:

- **ADALErrorCode** – Označuje kodo napake, pri čemer je prikazan poziv za vpis ali poskus tihega pridobivanja žetona za službeni račun.

- **ADALRawErrorCode** – Označuje neobdelano kodo napake, pri čemer je prikazan poziv za vpis ali poskus tihega pridobivanja žetona za službeni račun.

- **ErrorGroup** – Označuje vrsto računa, kot je osebni ali službeni račun oziroma službeni račun na mestu uporabe.

- **IDCRLErrorCode** – Označuje kodo napake, pri čemer je prikazan poziv za vpis v osebni račun.

- **IDCRLRawErrorCode** – Označuje neobdelano kodo napake, pri čemer je prikazan poziv za vpis v osebni račun.

- **LiveOAuthErrorCode** – Označuje kodo napake med poskusom tihega osveževanja žetona za osebni račun.

- **LiveOAuthRawErrorCode** – Označuje neobdelano kodo napake med poskusom tihega osveževanja žetona za osebni račun.

- **NTLMErrorCode** – Označuje kodo napake, pri čemer je prikazan poziv za vpis v službeni račun na mestu uporabe.

#### <a name="officeandroidandroidfileasyncsavestatus"></a>Office.Android.AndroidFileAsyncSaveStatus

Vključuje podatke o stanju asinhronega shranjevanja datoteke in različne kode napak iz različnih komponent.  Microsoft s temi podatki analizira, ali prihaja do izgube podatkov uporabnikov v aplikaciji med shranjevanjem datotek v aplikacijah Word, Excel ali PowerPoint.

Zbrana so naslednja polja:

- **FileExtension** – Datotečna pripona.

- **FileIOSaveHResult** – HResult za operacijo shranjevanja datotek.

- **FileIOSaveIsCopy** – Logična vrednost, ki označuje, ali je bo v operaciji shranjena kopija.

- **FileSize** – Velikost datoteke.

- **FileSourceLocation** – Vrednost oštevilčenja za mesto vira datoteke. Vrednosti: None, Local, UncOrMappedNetworkDrive, SkyDrive, App, SharePoint, UnknownServer

#### <a name="officeandroidandroidfileopenreliability"></a>Office.Android.AndroidFileOpenReliability

Vključuje podatke o stanju odpiranja datoteke ter različne kode napak za prepoznavanje pričakovanih in nepričakovanih napak pri odpiranju datotek ter ugotavljanje, kateri del kode sporoča napake.  Microsoft s temi podatki analizira vzroke za napake pri odpiranju datotek in izračuna kritične podatke meritev, kot je stopnja uspešnosti za odpiranje datoteke v aplikacijah Word, Excel ali PowerPoint.

Zbrana so naslednja polja:

- **AccessMode** – Oštevilčenje za način dostopa.

- **AppDocsFileOpenErrorCode** – Koda napake AppDocs za napake pri odpiranju datoteke.

- **ContentUriAuthority** – Overitelj URL-ja vsebine iz SAF.

- **DownloadCsiError** – Sporočilo o napaki iz CSI-ja.

- **FileExtension** – Datotečna pripona.

- **FileOpenEndErrorCode** – Koda napake za napako pri odpiranju datoteke.

- **FileOpenStatus** – Oštevilčenje stanja pri odpiranju datoteke.

- **FileSize** – Velikost datoteke.

- **FileSourceLocation** – Oštevilčenje mesta datoteke.

- **FirstBCSClientError_Info** – Zadnja napaka v odjemalcu BCS (binarna storitev pretvorbe).

- **IfWordFileOpencanceled** – Ali je uporabnik v Wordu preklical odpiranje datoteke.

- **InitializationReason** – Oštevilčenje za vnosno točko odpiranja datoteke.

- **IsAutoSaveDisabled** – Ali je samodejno shranjevanje onemogočeno med odpiranjem datoteke.

- **IsFileEmpty** – Logična vrednost, ki označuje, ali je datoteka prazna.

- **K2FileIOHresult** – Hresult za končanje opravila datoteke.

- **OpenCsiError** – Sporočilo o napaki pri odpiranju datoteke v plasti CSI.

- **OpEndEventId** – Oznaka mesta, kjer se je operacija dejansko končala.

- **PPTHresult** – Hresult v PPT-ju.

- **PPTIsExpectedError**– Razvrstitev napake PPT za pričakovano/nepričakovano napako pri odpiranju datoteke. 

- **PPTTag** – Oznaka napake v PPT-ju.

- **ProviderApp** – Ime paketa aplikacije, v kateri se je odprla datoteka.

- **ProviderFileSize** – Velikost zajete datoteke med odpiranjem datoteke prek aktivacije datoteke.

- **State** – Oštevilčenje stanja pri odpiranju datoteke.

- **UriScheme** – Shema URL-ja.

- **WordErrortag** – Oznaka napake v Wordu.

- **WordFileCorruptionReason** – Vzrok za poškodbo datoteke, zaradi katere Wordove datoteke ni bilo mogoče odpreti.

- **WordFileOpenErrorCode** – Koda napake za odpiranje določenih Wordovih datotek.

- **WordFileTypeFromDod** – Vrsta datoteke, ki jo določi Word, glede na dejansko obliko zapisa datoteke.

- **WordFileTypeFromExtension** – Vrsta datoteke, ki jo določi Word, glede na datotečno pripono.

#### <a name="officeandroidandroidfilesavestatus"></a>Office.Android.AndroidFileSaveStatus

Kritično za zajem podatkov o stanju asinhronega shranjevanja datoteke in različne kode napak iz različnih komponent.  Microsoft s temi podatki analizira, ali prihaja do izgube podatkov uporabnikov v aplikaciji med shranjevanjem datotek v aplikacijah Word, Excel ali PowerPoint.

Zbrana so naslednja polja:

- **AccessMode** – Vrednosti** None, ReadOnly, ReadOnlyUpgradable, ReadWrite.

- **AppDocsEndReason** – Oštevilčenje za vzroka za končanje Appdoc pri shranjevanju datoteke.  Vrednosti: None, Success, Failure, Cancel.

- **AppDocsErrorCode** – Končna koda napake za napako pri shranjevanju datoteke.

- **AppDocsTriggeringSaveDetails** – Polje, v katerem je navedeno, ali AppDocs aktivira ukaz za shranjevanje.

- **DocInstanceId** – ID primerka dokumenta, ki ga je ustvaril AppDocs, glede na obseg primerka operacije v dokumentu.

- **ExcelFileSaveResult** – Posebni HResult za Excel.

- **FileExtension** – Razširitev datoteke.

- **FileIOSaveErrorCode** – Koda napake v FileIO.

- **FileIOSaveHResult** – Hresult v FileIO.

- **FileIOSaveIsCopy** – Logična vrednost, ki označuje, ali gre za kopiranje.

- **FileSize** – Velikost datoteke.

- **FileSourceLocation** – Oštevilčenje mesta datoteke.  Vrednosti: None, Local, UncOrMappedNetworkDrive, SkyDrive, App, SharePoint, UnknownServer

- **OpFlags** – Zastavice oštevilčenja za shranjevanje.

- **PPTFileSaveFailHresult** – Hresult PPT za napako pri shranjevanju.

- **PPTFileSaveFailTag** – Oznaka PPT za napako pri shranjevanju.

- **Stare** – Oštevilčenje stanja pri odpiranju datoteke. 

- **Vrednosti** – None, Creating, Created, CreateFailed, Opening, Opened, OpenFailed, Copying, Copied, CopyFailed, Closing, Closed, CloseFail.

- **WordFileCopyErrorTrackbackTag** – Oznaka trackback za napako stanja CopyDocument v Wordu.

- **WordFileSaveCancelReason** – Oznaka trackback za preklice v Wordu.

- **WordFileSaveEid** – koda napake, značilna za Word.

- **WordFileSaveErrorTrackbackTag** – Oznaka trackback za napake pri shranjevanju.

- **WordFileSaveOpResult** – Oštevilčenje za stanje rezultata 0, če je bila operacija uspešna, 1, če ni uspela in 2, če je bila preklicana.

- **WordFileSaveSuccess** – Oštevilčenje za podrobnosti, značilne za Word za uspeh pri shranjevanju datoteke.

#### <a name="officeandroidandroidofficeactivationlatency"></a>Office.Android.AndroidOfficeActivationLatency

Kritični podatki za zbiranje celovitega časa, zahtevanega za odpiranje datoteke, za vsa odpiranja datotek v sistemu Windows ter Excelovih in PowerPointovih aplikacijah.  Ta dogodek Microsoft uporablja za določanje metrike za učinkovitost pri odpiranju datoteke naših aplikacij.

Zbrana so naslednja polja:

- **AppBootingOccured** – Logična vrednost za preverjanje, ali je zagon aplikacije končan.

- **ApplicationBootTime**– Čas, zahtevan za določeno stopnjo zagona aplikacije.

- **AppSuspendedDuringBoot** – Logična vrednost za preverjanje, ali je bila aplikacija prekinjena med zagonom.

- **BlockingUIShownDuringFileOpen** – Logična vrednost, ki označuje, ali je med odpiranjem datoteke prišlo do blokiranja pogovornih oken.

- **CachedInfoAvailable** – Logična vrednost za iskanje predpomnjenih informacij, značilnih za odpiranje datoteke.

- **DocumentRecoveryInvoked** – Logična vrednost, ki označuje, ali je na voljo dokument, ki čaka na obnovitev.

- **EndToEndActivationTime** – Čas, zahtevan za upodobitev datoteke za datoteke, zagnane zunaj aplikacije.

- **EndToEndFileOpenTime** – Čas, zahtevan za upodobitev datoteke za datoteke, zagnane v aplikaciji.

- **FileOpenPhaseDurationInMs** – Čas za odpiranje datoteke, ki ga porabi določena faza.

- **FileSourceLocation** – Vrednost oštevilčenja za mesto datoteke, kot so: None, Local, UncOrMappedNetworkDrive, SkyDrive, App, SharePoint, UnknownServer.

- **InitalizationReason** – Vstopna točka za odpiranje datoteke.

- **InitialBootPhaseTime**– Čas, zahtevan za določeno stopnjo zagona aplikacije.

- **IsThisFirstLaunch** – Logična vrednost, ki označuje, ali je to prvi zagon aplikacije.

- **MinimumLibraryLoadPhaseTime** – Čas, zahtevan za določeno stopnjo zagona aplikacije.

- **MinimumLibraryLoadPhaseTime** – Čas, zahtevan za določeno stopnjo zagona aplikacije.

- **MinimumLibraryLoadPhaseTime** – Čas, zahtevan za določeno stopnjo zagona aplikacije.

- **PostAppInitTimeInMs** – Čas, zahtevan za določeno stopnjo zagona aplikacije.

- **PPTRenderPhase** – Čas, povezan z določeno stopnjo pri upodabljanju PPT.

- **PreAppInitTimeInMs**– Čas, zahtevan za določeno stopnjo zagona aplikacije.

- **ProviderApp** – Ime paketa aplikacije, v kateri se je odprla datoteka.

- **TelemetryReason** – Podobno kot InitialisationReason, vendar bolj podrobna vrednost oštevilčenja glede na vstopno točko za odpiranje datoteke.

- **UserDialogInterruptionDuringBoot** – Logična vrednost, ki označuje, ali je med zagonom prišlo do blokiranja pogovornih oken.

- **XLRenderPhase** – Čas, povezan z določeno stopnjo pri upodabljanju za Excel.

#### <a name="officeandroidappdocsfileoperationends"></a>Office.Android.AppDocsFileOperationEnds

Telemetrični podatki kritičnih dokumentov samo za Android (AppDocs) za končanje operacij Datoteka > Novo/Odpri/Shrani kot. S tem dogodkom zabeležite kode napak za vse neuspešne operacije AppDocs.  Microsoft s tem dogodkom prepozna napake v različnih postopkih datoteke in plast, kjer je prišlo do napake v Wordu, Excelu ali PowerPointu.

Zbrana so naslednja polja:

- **AccessMode** – Vrednost oštevilčenja za način dostopa do datoteke.  Vrednosti: None, ReadOnly, ReadOnlyUpgradable, ReadWrite

- **BlockingUIShown** – Logična vrednost, ki označuje, ali je bil v toku prikazan blokiran uporabniški vmesnik.

- **ContentUriAuthority** – overitelj URL-ja vsebina iz SAF.

- **Correlation** – GUID za ID korelacije, povezanega s postopkom.

- **DocId** – ID dokumenta, ki ga je ustvaril AppDocs.

- **DocInstanceId** – ID primerka dokumenta, ki ga je ustvaril AppDocs, glede na obseg primerka operacije v dokumentu.

- **DocIsEnterpriseProtected** – Logična vrednost, ki označuje, ali je dokument zaščiten.

- **DocUserId** – ID uporabnika iz plasti MS auth.

- **DocUserIdProvider** – Oštevilčenje, ki predstavlja ponudnika ID-ja uporabnika, 0 = neznano, 1 = LiveId, 2 = OrgId, 3 = SSPI, 4 = ADAL.

- **DurationInMs** – Čas v milisekundah, da se operacija datoteke konča.

- **EndReason** – Vrednost oštevilčenja za vzrok končanja.  Vrednosti: None, Success, Failure, Cancel.

- **ErrorCode** – Koda napake za delovanje datoteke.

- **Pripona** – Prvi štirje znaki razširitve datoteke, ki jo želite odpreti.

- **FileSourceLocation** – Vrednost oštevilčenja za mesto datoteke. Morebitne vrednosti: None, Local, UncOrMappedNetworkDrive, SkyDrive, App, SharePoint, UnknownServer

- **FILETIME** – Čas dogodka.

- **FirstBCSClientError_Info** – Informacije o kodi napake, povezani s pretvorbami datotek.

- **HttpStatusCode** – Koda odziva HTTP za zahtevo spletne storitve.

- **InitalizationReason** – Vstopna točka za odpiranje datoteke.

- **K2FileIOHresult** – Koda Hresult za končanje odpiranja datoteke.

- **LastBCSClientError_TagId** – Zadnja napaka v odjemalcu BCS (binarna storitev pretvorbe).

- **OfficeWebServiceApiStatusFlag** – Zastavica stanja za zahtevo spletne storitve.

- **OpEndEventId** – Oznaka, ki predstavlja, kje se je operacija dejansko končala.

- **OpFlags** – Zastavice parametrov za operacijo dokumenta, ki jih uporablja plast AppDocs.

- **OpSeqNum** – Število, ki predstavlja zaporedje klicev v zvezi z delovanjem datoteke v plasti AppDocs.

- **OpType** – Oštevilčenje vrste operacije. Vrednosti: »None«, »CreateDocument«, »OpenDocument«, »CopyDocument«, »CloseDocument«, »SaveDocument«, »OpenVersion«, »CloseVersion«.

- **PreFetchState** – Oštevilčenje za vnaprejšnje stanje predlog za ustvarjanje novih datotek.

- **ProviderApp** – Ime paketa aplikacije, v kateri se je odprla datoteka.

- **ScopeInstanceId** – ID primerka obsega, ki se uporablja za združevanje konteksta podatkov z dejavnostmi.

- **Size** – Velikost datoteke.

- **State** – Vrednost oštevilčenja za stanje datoteke. Vrednosti: None, Creating, Created, CreateFailed, Opening, Opened, OpenFailed, Copying, Copied, CopyFailed, Closing, Closed, CloseFail.

- **TemplateName** – ime dvojiške predloge dokumenta iz storitve predloge, npr. TF10002009.dotx

- **UriScheme** – Shema URL-ja.

#### <a name="officeandroidauthaceerrors"></a>Office.Android.AuthACEErrors

Ta dogodek uporablja Microsoftov račun (MSA) za določanje uporabnika, ki se želi vpisati v aplikacijo, in vrste telemetrije, ki je v tistem trenutku sprožena v razpravi kot del neuspešnega poskusa.  

Ta dogodek vam pomaga pri analizi napake pri vpisu v storitvi MSA, ki pomaga pri razumevanju razlogov za neuspešen potek dela v storitvi MSA.

Zbrana so sledeča polja:

- **ExceptionsName** – označuje izjemne razrede glede na oznake izjem, ki se pojavijo med potekom vpisov v Microsoftov račun.

- **ExceptionsTag** – označuje, katere izjeme za prilive v uniji so prisotne v storitvi v storitvi v storitvi MSA-vpis.

- **IDCRLACEErrorCode** – daje kodo napake, ki se pojavi med vpisom v storitvi MSA. Različne kode napake, navedene na naslovu%SRCROOT%\identity\coreapi\public\IdentityData.h

- **IDCRLAuthenticationStatusErrorCode** – označuje koda napake za neveljavno stanje rezultata preverjanja pristnosti, ki prihaja iz Microsoftovega računa (MSA).

- **IDCRLUserInteractionMissingError** – označuje, ali se je v Microsoftov račun (MSA), na katerega se je priklicala showUI zastavica, priklicana z zastavico, ki je napačno.


#### <a name="officeandroidbcserrors"></a>Office.Android.BCS.Errors

Telemetrija napak dvojiških pretvorb za ukaza »Natisni« in »Shrani kot PDF«.  Microsoft s tem dogodkom prepoznava točke napak med pretvorbami BCS v aplikacijah Word, Excel ali PowerPoint.

Zbrana so naslednja polja:

- **DocumentFileSize** – Velikost datoteke.

- **FileExtension** – Prvi štirje znaki razširitve datoteke.

- **IsFileDirty** – Logična vrednost, ki označuje, ali je v datoteki prišlo do neshranjenih sprememb.

- **Location** – Oštevilčenje mesta datoteke.  Vrednosti: OneDrive, SharePoint, Dropbox, Others.

- **PDFConversionError** – Oznaka, pri kateri se pojavi napaka pri pretvorbi datoteke PDF.

- **PdfConversionErrorCode** – Koda napake pri pretvorbi PDF.

- **PdfConversionHRStatus** – Koda stanja pretvorbe PDF.

- **PdfConversionResult** – Oštevilčenje rezultata pretvorbe datoteke PDF.  Vrednosti: »uspeh«, »ni uspelo« in »preklicano«

- **PdfFileSize** – Velikost datoteke PDF.

#### <a name="officeandroidclientsideiap"></a>Office.Android.ClientSideIAP

Telemetrija kritične napake za napake zbirke podatkov med brskanjem datotek in dodajanje mest.  Microsoft s tem dogodkom prepozna težave s poškodbami zbirk podatkov v aplikacijah, ki uporabniku morda preprečujejo dodajanje ali brskanje mest v aplikaciji za aplikacije Word, Excel ali PowerPoint.

Zbrana so naslednja polja:

- **ClientTransactionId** – GUID je posredovan na DSC za določeno zahtevo za prevzem.

- **CollectionTime** – Čas zaključka nakupa naročnine.

- **CountryCode** – koda države odjemalca, ki je posredovana na DSC za zahtevo prevzema odjemalca

- **GoPremiumEntryPoint** – vstopna točka za sprožitev nakupa 

- **IsActivateExistingSubscription** – logična vrednost, ki označuje, ali je prišlo do aktiviranja obstoječe naročnine

- **IsErrorRetriable** – Logična vrednost, ki označuje, ali je prevzem mogoče ponoviti.

- **IsPreviousPurchase** – Logična vrednost, ki označuje, ali je prišlo do aktivacije ob prejšnjem nakupu naročnine.

- **IsProvisioningTriggeredByRetry** – Logična vrednost, ki označuje, ali je prišlo do vnovičnega poskusa.

- **LanguageCode** – koda jezika odjemalca, ki je posredovana na DSC za zahtevo prevzema odjemalca

- **ProductIdentifier** – ime inventarne številke, ki jo odjemalec želi kupiti

- **ProvisioningHttpStatusCode** – Omogočanje kode stanja http.

- **ProvisioningStatusCode** – Omogočanje kode stanja.

- **PurchaseOrderId** – Identifikator naročila za nakup v trgovini Google/Samsung.

- **RedemptionTaskHR** – HResult za opravilo prevzema naročnine.

- **SubscriptionProvisioningSucceeded** – Logična vrednost uspešnega rezultata za omogočanje uporabe naročnine.

- **SubscriptionPurchaseHR** – Hresult za opravilo nakupa naročnine.

- **SubscriptionType** – Oštevilčenje za vrsto naročnine ali inventarne številke.

- **TCID** – Klik ikone sproži potek naročnine.

#### <a name="officeandroiddbfailurecause"></a>Office.Android.DBFailureCause

Telemetrija kritične napake za napake zbirke podatkov med brskanjem datotek in dodajanje mest.  Microsoft s tem dogodkom prepozna težave s poškodbami zbirk podatkov v aplikacijah, ki uporabniku morda preprečujejo dodajanje ali brskanje mest v aplikaciji za aplikacije Word, Excel ali PowerPoint.

Zbrana so naslednja polja:

- **ErrorAt** – Vrednost oznake: Informacije o mestu, kjer je prišlo do napake.

- **ExceptionErrorMessage** – obširno sporočilo o napaki.

#### <a name="officeandroidearlytelemetryexpansionfileserrors"></a>Office.Android.EarlyTelemetry.ExpansionFilesErrors

Razširitvene datoteke kompleta Android Package Kit (APK) za Officeovo mobilno aplikacijo so dodatne datoteke sredstev, ki jih lahko razvijalci aplikacije Android objavijo skupaj z aplikacijo. Ker želimo poskrbeti, da bo naš mehanizem za prenos razširitvenih datotek bolj zanesljiv, v dnevnik zapisujemo vzrok napak, do katerih pride bodisi med prenosom razširitvenih datotek bodisi med branjem prenesenih razširitvenih datotek.

Zbrana so sledeča polja:

- **Data_ClassName** – besedilo, ki predstavlja ime datoteke izvorne kode, kjer je prišlo do napake.

- **Data_ErrorMessage** – besedilo, ki predstavlja postopek, ki ni uspel.

- **Data_ExceptionMessage** – izbirno polje z besedilom, ki predstavlja vzrok izjeme.

- **Data_ExceptionType** – izbirno polje z besedilom, ki predstavlja ime izjeme, ki jo poda izvorna koda.

- **Data_MethodName** – Besedilo, ki predstavlja ime načina v izvorni kodi, kjer je prišlo do napake.

#### <a name="officeandroidearlytelemetryextractionerror"></a>Office.Android.EarlyTelemetry.ExtractionError

Če želite zmanjšati velikost programov sistema Office Android, uporabite stiskanje za vire v končnem paketu. Ko zaženete čas, najprej izvlečemo te vire, preden jih uporabimo. Med izvajanjem izvlečkov je včasih prišlo do nepričakovanih napak, kar povzroča zrušitve programa. 

S tem dogodkom pridobivamo nekatere diagnostične informacije, ki so povezane z ekstrakcijo, na primer ime vira, ki je bil pridobljen, pot, na kateri je izvlečena itd. Ti podatki so zbrani le, kadar pride do napak pri pridobivanju.

Te podatke uporabljamo, da bi razumeli vzrok za težave z ekstrakcijo in izboljšali uporabniško izkušnjo naših aplikacij.

Zbrana so sledeča polja:

- **Data_ArchiveName** – ime vira, ki ga pridobivate.

- **Data_ArchivePath** – pot, kjer je vir začasno predpomnjen.

- **Data_ArchiveSizeKB** – velikost vira, ki ga pridobivate.
 
- **Data_ClassName** – ime datoteke v izvorni kodi, pri kateri je prišlo do napake.

- **Data_ErrorDetail** – besedilo, ki opisuje več podrobnosti o vzroku napake, kot je koda napake ipd.

- **Data_ErrorMessage** – besedilo z opisom vrste napake, ki je bila med ekstrakcijo naletela.

- **Data_ExtractionDestinationPath** – pot, kjer naj bo vir shranjen po ekstrakciji.

- **Data_FreeDiskSpaceMB** – količina prostega prostora na disku, ki je na voljo v napravi, merjeni v Mega bajtih. 

- **Data_ItemToExtract** – ime vira, ki ga pridobivate.

- **Data_MethodName** – ime metode v izvorni kodi, pri kateri je prišlo do napake.


#### <a name="officeandroidearlytelemetryregistryerrors"></a>Office.Android.EarlyTelemetry.RegistryErrors

Ta dogodek zajame morebitne napake, do katerih je prišlo med dostopom do registra sistema Android. S podatki tega dogodka lahko razumemo napake uporabnika in ustvarimo bolj trpežno funkcijo registra.

Zbrana so sledeča polja:

- **App** – Postopek aplikacije, ki pošilja dogodek.

- **AppVersionLong** – Različica aplikacije.

- **Data_StackTrace** – Sled sklada napake.

#### <a name="officeandroidearlytelemetrysharedlibraryloadersearchandloadlibraryerror"></a>Office.Android.EarlyTelemetry.SharedLibraryLoadersearchAndloadLibraryError 

Ta dogodek beležimo v primeru napak pri nalaganju knjižnic v skupni rabi. Do napak pri nalaganju knjižnic lahko pride zaradi dveh vzrokov 1) nameščeni APK ni združljiv z napravo. 2) Knjižnica, ki jo skušamo naložiti, je morda poškodovana, zaradi napak pri ekstrahiranju, nastalih zaradi premalo prostora na disku ali premalo pomnilnika.

Zbrana so sledeča polja:

- **Data_ExceptionMessage** – Sporočilo izjeme, ki ga aktivira Android API Szstem.loadlibrary.

- **Data_FreeSpaceInMB** – Prostor, ki je na voljo v napravi.

- **Data_nickName** – ime knjižnice, ki je ni bilo mogoče naložiti

#### <a name="officeandroidintuneintunejavacopyfailedattempts"></a>Office.Android.Intune.IntuneJavaCopyFailedAttempts

Telemetrija kritične napake za spremljanje napak za posamezne vmesnike API Intune; ta telemetrija se zapisuje v dnevnike v primeru napak pri shranjevanju lokalne kopije dokumentov v oblaku, zaščitenih s storitvijo Intune.  Microsoft s temi podatki prepoznava napake med in po vpisu v storitev Intune v aplikaciji in po vpisu v aplikacijo s službenim računom.

Zbrana so naslednja polja:

- **Data_FileCreationFailedErrorCode** – Koda napake, povezana s tokom.

#### <a name="officeandroidintuneintunejavaexceptionadaltokenformam"></a>Office.Android.Intune.IntuneJavaExceptionADALTokenForMAM

Telemetrija kritične napake za spremljanje napak za posamezne vmesnike API Intune; ta telemetrija se zapisuje v dnevnike v primeru napak pri pridobivanju žetona ADAL za vire Intune.  Microsoft s temi podatki prepoznava napake med vpisom v storitev Intune v aplikaciji in po vpisu v aplikacijo s službenim računom.

Zbrana so naslednja polja:

- **Data_ErrorCode** – Koda napake, povezana s tokom.

#### <a name="officeandroidintuneintunejavaexceptionapppolicy"></a>Office.Android.Intune.IntuneJavaExceptionAppPolicy

Telemetrija kritične napake za spremljanje napak za posamezne vmesnike API Intune; ta telemetrija se zapisuje v dnevnike v primeru napak pri klicanju vmesnika API za Intune, povezanega s pridobivanjem pravilnikov za identiteto trenutnega procesa.  Microsoft s temi podatki prepoznava napake med in po vpisu v storitev Intune v aplikaciji in po vpisu v aplikacijo s službenim računom.

Zbrana so naslednja polja:
 
- Nobeno

#### <a name="officeandroidintuneintunejavaexceptionapppolicyforcontext"></a>Office.Android.Intune.IntuneJavaExceptionAppPolicyForContext

Telemetrija kritične napake za spremljanje napak za posamezne vmesnike API Intune; ta telemetrija se zapisuje v dnevnike v primeru napak pri klicanju vmesnika API za Intune, povezanega s pridobivanjem pravilnikov za identiteto trenutne dejavnosti.  Microsoft s temi podatki prepoznava napake med in po vpisu v storitev Intune v aplikaciji in po vpisu v aplikacijo s službenim računom.

Zbrana so naslednja polja:
 
- Nobeno

#### <a name="officeandroidintuneintunejavaexceptionauthenticationcallback"></a>Office.Android.Intune.IntuneJavaExceptionAuthenticationCallback

Telemetrija kritične napake za spremljanje napak za posamezne vmesnike API Intune; ta telemetrija se zapisuje v dnevnike v primeru napak pri klicanju vmesnika API za Intune, povezanega z registracijo za povratne klice preverjanja pristnosti za upravljane račune.  Microsoft s temi podatki prepoznava napake med in po vpisu v storitev Intune v aplikaciji in po vpisu v aplikacijo s službenim računom.

Zbrana so naslednja polja:

- Nobeno

#### <a name="officeandroidintuneintunejavaexceptiongetaccountstatesync"></a>Office.Android.Intune.IntuneJavaExceptionGetAccountStateSync

Telemetrija kritične napake za spremljanje napak za posamezne vmesnike API Intune; ta telemetrija se zapisuje v dnevnike v primeru napak pri klicanju vmesnika API za Intune, povezanega z upravljanim računom.  Microsoft s temi podatki prepoznava napake med in po vpisu v storitev Intune v aplikaciji in po vpisu v aplikacijo s službenim računom.

Zbrana so naslednja polja:
 
- Nobeno

#### <a name="officeandroidintuneintunejavaexceptiongetissavetolocationallowed"></a>Office.Android.Intune.IntuneJavaExceptionGetIsSaveToLocationAllowed

Telemetrija kritične napake za spremljanje napak za posamezne vmesnike API Intune; ta telemetrija se zapisuje v dnevnike v primeru napak pri pridobivanju pravilnika, povezanega z lokalnim shranjevanjem.  Microsoft s temi podatki prepoznava napake med in po vpisu v storitev Intune v aplikaciji in po vpisu v aplikacijo s službenim računom.

Zbrana so naslednja polja:

- Nobeno

#### <a name="officeandroidintuneintunejavaexceptiongetpolicyforidentity"></a>Office.Android.Intune.IntuneJavaExceptionGetPolicyForIdentity

Telemetrija kritične napake za spremljanje napak za posamezne vmesnike API Intune; ta telemetrija se zapisuje v dnevnike v primeru napak pri klicanju vmesnika API za Intune, povezanega s pridobivanjem pravilnikov za identiteto.  Microsoft s temi podatki prepoznava napake med in po vpisu v storitev Intune v aplikaciji in po vpisu v aplikacijo s službenim računom.

Zbrana so naslednja polja:

- Nobeno

#### <a name="officeandroidintuneintunejavaexceptiongetprotectioninfofromdescriptor"></a>Office.Android.Intune.IntuneJavaExceptionGetProtectionInfoFromDescriptor

Telemetrija kritične napake za spremljanje napak za posamezne vmesnike API Intune; ta telemetrija se zapisuje v dnevnike v primeru napak pri klicanju vmesnika API za Intune, povezanega s podatki o zaščiti.  Microsoft s temi podatki prepoznava napake med in po vpisu v storitev Intune v aplikaciji in po vpisu v aplikacijo s službenim računom.

Zbrana so naslednja polja:
  
- Nobeno

#### <a name="officeandroidintuneintunejavaexceptiongetprotectioninfofrompath"></a>Office.Android.Intune.IntuneJavaExceptionGetProtectionInfoFromPath

Telemetrija kritične napake za spremljanje napak za posamezne vmesnike API Intune; ta telemetrija se zapisuje v dnevnike v primeru napak pri klicanju vmesnika API za Intune, povezanega s podatki o zaščiti.  Microsoft s temi podatki prepoznava napake med in po vpisu v storitev Intune v aplikaciji in po vpisu v aplikacijo s službenim računom.

Zbrana so naslednja polja:

- Nobeno

#### <a name="officeandroidintuneintunejavaexceptiongetuipolicyidentity"></a>Office.Android.Intune.IntuneJavaExceptionGetUIPolicyIdentity

Telemetrija kritične napake za spremljanje napak za posamezne vmesnike API Intune; ta telemetrija se zapisuje v dnevnike v primeru napak pri klicanju vmesnika API za Intune, povezanega s pridobivanjem pravilnikov uporabniškega vmesnika za upravljan račun.  Microsoft s temi podatki prepoznava napake med in po vpisu v storitev Intune v aplikaciji in po vpisu v aplikacijo s službenim računom.

Zbrana so naslednja polja:

- Nobeno

#### <a name="officeandroidintuneintunejavaexceptionisidentitymanaged"></a>Office.Android.Intune.IntuneJavaExceptionIsIdentityManaged

Telemetrija kritične napake za spremljanje napak za posamezne vmesnike API Intune; ta telemetrija se zapisuje v dnevnike v primeru napak pri klicanju vmesnika API za Intune, povezanega z določevanjem, ali gre za upravljan račun.  Microsoft s temi podatki prepoznava napake med in po vpisu v storitev Intune v aplikaciji in po vpisu v aplikacijo s službenim računom.

Zbrana so naslednja polja:

- Nobeno

#### <a name="officeandroidintuneintunejavaexceptionnullenrollmentmanager"></a>Office.Android.Intune.IntuneJavaExceptionNullEnrollmentManager

Telemetrija kritične napake za spremljanje napak za posamezne vmesnike API Intune; ta telemetrija se zapisuje v dnevnike v primeru napak pri klicanju vmesnika API za Intune, povezanega z registracijo komponent za povratni klic.  Microsoft s temi podatki prepoznava napake med in po vpisu v storitev Intune v aplikaciji in po vpisu v aplikacijo s službenim računom.

Zbrana so naslednja polja:

- Nobeno

#### <a name="officeandroidintuneintunejavaexceptionprotect"></a>Office.Android.Intune.IntuneJavaExceptionProtect

Telemetrija kritične napake za spremljanje napak za posamezne vmesnike API Intune; ta telemetrija se zapisuje v dnevnike v primeru napak pri klicanju vmesnika API za Intune, povezanega z zaščito upravljanega računa.  Microsoft s temi podatki prepoznava napake med in po vpisu v storitev Intune v aplikaciji in po vpisu v aplikacijo s službenim računom.

Zbrana so naslednja polja:

- Nobeno

#### <a name="officeandroidintuneintunejavaexceptionprotectfromdescriptorifrequired"></a>Office.Android.Intune.IntuneJavaExceptionProtectFromDescriptorIfRequired

Telemetrija kritične napake za spremljanje napak za posamezne vmesnike API Intune; ta telemetrija se zapisuje v dnevnike v primeru napak pri klicanju vmesnika API za Intune, povezanega z zaščito upravljanega računa.  Microsoft s temi podatki prepoznava napake med in po vpisu v storitev Intune v aplikaciji in po vpisu v aplikacijo s službenim računom.

Zbrana so naslednja polja:

- Nobeno

#### <a name="officeandroidintuneintunejavaexceptionregisteraccountsync"></a>Office.Android.Intune.IntuneJavaExceptionRegisterAccountSync

Telemetrija kritične napake za spremljanje napak za posamezne vmesnike API Intune; ta telemetrija se zapisuje v dnevnike v primeru napak pri klicanju vmesnika API za Intune, povezanega z registracijo računa za upravljanje v storitvi Intune.  Microsoft s temi podatki prepoznava napake med in po vpisu v storitev Intune v aplikaciji in po vpisu v aplikacijo s službenim računom.

Zbrana so naslednja polja:

- Nobeno

#### <a name="officeandroidintuneintunejavaexceptionsetuipolicyidentitysync"></a>Office.Android.Intune.IntuneJavaExceptionSetUIPolicyIdentitySync

Telemetrija kritične napake za spremljanje napak za posamezne vmesnike API Intune; ta telemetrija se zapisuje v dnevnike v primeru napak pri klicanju vmesnika API za Intune, povezanega z nastavljanjem pravilnikov uporabniškega vmesnika za upravljan račun.  Microsoft s temi podatki prepoznava napake med in po vpisu v storitev Intune v aplikaciji in po vpisu v aplikacijo s službenim računom.

Zbrana so naslednja polja:

- Nobeno

#### <a name="officeandroidintuneintunejavaexceptionunregisteraccountsync"></a>Office.Android.Intune.IntuneJavaExceptionUnregisterAccountSync

Telemetrija kritične napake za spremljanje napak za posamezne vmesnike API Intune; ta telemetrija se zapisuje v dnevnike v primeru napak pri klicanju vmesnika API za Intune, povezanega s scenariji oddaljenega brisanja za upravljanje v storitvi Intune.  Microsoft s temi podatki prepoznava napake med in po vpisu v storitev Intune v aplikaciji in po vpisu v aplikacijo s službenim računom.

Zbrana so naslednja polja:

- Nobeno

#### <a name="officeandroidintuneintunejavaexceptionupdatetoken"></a>Office.Android.Intune.IntuneJavaExceptionUpdateToken

Telemetrija kritične napake za spremljanje napak za posamezne vmesnike API Intune; ta telemetrija se zapisuje v dnevnike v primeru napak pri klicanju vmesnika API za Intune, povezanega z žetonom za preverjanje pristnosti posodobitve za upravljan račun.  Microsoft s temi podatki prepoznava napake med in po vpisu v storitev Intune v aplikaciji in po vpisu v aplikacijo s službenim računom.

Zbrana so naslednja polja:

- Nobeno

#### <a name="officeandroidlicenseactivationfailure"></a>Office.Android.LicenseActivationFailure

Telemetrija kritične napake za spremljanje napak pri aktivaciji licenc za račune Office 365 v aplikacijah Word, Excel ali PowerPoint.  Microsoft s tem dogodkom analizira napake pri aktivaciji kupljenih licenc za Office 365.

Zbrana so naslednja polja:

- **EntryPoint** – Oštevilčenje vstopne točke za sprožitev poteka aktivacije licenc.

- **HResult** – Koda napake pri okvari.

- **IsGallatin** – Logična vrednost za preverjanje, ali gre za račun Gallatin.

- **MessageCode** – Oštevilčenje, ki označuje mesto napake pri aktivaciji.

- **PreviousEntryPoint** – Oštevilčenje vstopne točke za sprožitev poteka aktivacije licenc.

- **StateAfterActivation** – Oštevilčenje, ki označuje stanje licenciranja aplikacije po koncu aktivacije.

- **StateBeforeActivation** – Oštevilčenje, ki označuje stanje licenciranja aplikacije pred začetkom aktivacije.

- **UserAccountType** – Oštevilčenje, ki označuje, ali gre za osebni račun ali račun podjetja.

#### <a name="officeandroidmsasigninuiprompts"></a>Office.Android.MSASignInUIPrompts

Ta dogodek ponazarja, da je bil uporabniku prikazan poziv za vpis v osebni račun.  Ta dogodek omogoča lažje razumevanje stanja vpisa naših aplikacij in izvedbo ustreznih dejanj, ko zaznamo nepričakovane pozive za vpis. 

Zbrana so naslednja polja:

- **ExternalCacheRefreshError** – Koda napake pri poskusu osveževanja žetona pred prikazom poziva za vpis.

- **LastLoginDelta** – Delta čas zadnje uspešne prijave.

- **MSAserverUAID** – ID korelacije s podatki za telemetrijo storitve

- **PreviousIdentityState** – Označuje stanje računa, kot je potekla seja. 

- **SignInResultCode** – Označuje kodo rezultata za končanje poziva za vpis.

- **UseCache** – Označuje, ali smo uporabnika pozvali k ponovnemu vpisu gesla.

- **UserType** – Označuje, ali gre za obstoječi ali nov račun.

- **WasIdentitySignedOut** – Označuje, ali je bil račun v izpisanem stanju.


#### <a name="officeapplelicensingmacdractivationfailures"></a>Office.Apple.Licensing.Mac.DRActivationFailures

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek uporabljamo za beleženje napak pri aktivaciji storitve Digital River (dnevnik zabeleži ključ in izdelek, ki je bil uporabljen za aktivacijo, ter prejeto kodo napake).  Ta dogodek uporabljamo za odkrivanje napak pri aktivaciji in pomoč pri njihovem odpravljanju (težave s storitvijo Digital River).

Zbrana so naslednja polja:

- **Data_DigitalRiverID** – ID izdelka Digital River, ki se preslika v Officeov izdelek SKY

- **Data_Error** – niz, ki predstavlja kodo napake pri aktivaciji.

- **Data_ProductKey** – ključ izdelka, pri katerem je bil izveden poskus aktivacije.

- **Data_ProductKeyHash** – kodiran ključ izdelka, ki je v postopku aktiviranja

#### <a name="officeapplelicensingmacgetmachinestatuserrors"></a>Office.Apple.Licensing.Mac.GetMachineStatusErrors

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Dogodek zbira podatke o kodi napake, ki je vrnjena med občasnim preverjanjem veljavnosti naročniške licence. Koda napake lahko označuje, da strežnik ni na voljo, pa tudi potek licence, omejitev števila računalnikov, neveljaven ID strojne opreme ipd. Ta dogodek uporabljamo za nadzorovanje ustreznosti stanja storitve licenciranja za Office, pa tudi za preiskovanje težav, povezanih z upravljanjem naročnine v računalniku.

Zbrana so naslednja polja:

- **Data_Error** – zbiramo podatke o nizu, ki predstavlja kodo napake.

#### <a name="officeextensibilitysandboxodperrornotification"></a>Office.Extensibility.Sandbox.ODPErrorNotification

Sledi različnim obvestilom o napakah, ki prispejo iz peskovnika. Uporablja se za zaznavanje scenarijev napak v peskovniku in na podlagi tega za odpravljanje napak, da bi prišlo do izboljšanja storilnosti uporabnika.
 
Zbrana so naslednja polja:

- **AppId** – ID aplikacije

- **AppUrl** – pomaknjen URL aplikacije. 

- **Result** – koda napake rezultata.

#### <a name="officefirstrunapplemaconiolkfirstrunstarted"></a>Office.FirstRun.Apple.MacONIOLKFirstRunStarted

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Ta dogodek nam pove, da je uporabnik odprl uporabniško izkušnjo prvega zagona. Ta dogodek uporabljamo, da bi ugotovili, ali je bil postopek za uporabniško izkušnjo prvega zagona (FRE) uspešno zagnan.

Zbrana so naslednja polja:

- **Data_FirstRunCollectionTime** – časovni žig, ki zabeleži čas, ko je bil postopek zagnan.

#### <a name="officegraphicsarcexceptions"></a>Office.Graphics.ARCExceptions 

Ti podatki poročanja o izjemi so pomembni za ocenjevanje splošnega stanja grafike in za prepoznavanje delov v kodi, kjer pogosto prihaja do napak. Tako lahko določimo vrstni red raziskovanja. Ti podatki poročanja o izjemi so pomembni za ocenjevanje splošnega stanja grafike in za prepoznavanje delov v kodi, kjer pogosto prihaja do napak. Inženir lahko tako določi, katere napake pri upodabljanju vplivajo na večino uporabnikov, kar nam omogoča, da najprej odpravimo težave, katere v največji meri vplivajo na uporabnike.

Zbrana so sledeča polja:

  - **Data\_HResult** – koda napake, ki jo je vrnila okvara

  - **Data\_TagCount** – število zaznanih okvar

  - **Data\_TagID** – identifikator zaznane okvare

#### <a name="officeoutlookdesktopcalendaracceptcalsharenavigatetosharedfoldererror"></a>Office.Outlook.Desktop.Calendar.AcceptCalShareNavigateToSharedFolder.Error

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

- **AppInfo.ClientHierarchy** – hierarhija odjemalcev, ki označuje, da se aplikacija izvaja v produkcijskem okolju ali v okolju razvijalcev

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

#### <a name="saveerror"></a>save.error

Omogoča nam, da zaznamo in odpravimo primere, ko je prišlo do napake med poskusom shranjevanja datoteke.  Ta dogodek spremlja napake, nastale zaradi neuspešnega shranjevanja datoteke, vključno z opisnim sporočilom o napaki. Dogodek nam je v pomoč pri odpravljanju težave.

Zbrana so sledeča polja: 

- **error** – vrsta nastale napake za pomoč pri zaznavanju in odpravljanju težav, povezanih z določeno vrsto napake.

- **file_type** – vrsta datoteke, ki jo je uporabnik poskusil shraniti (na primer. doc).

- **origin** – izvor poskusa shranjevanja datoteke (npr. iz e-pošte), s katerim lahko zaznamo težave, povezane s shranjevanjem datoteke iz določenega mesta v aplikaciji.

- **token_type** – vrsta žetona, uporabljenega za preverjanje pristnosti računa za shranjevanje datoteke, s katero zaznavamo težave pri preverjanju pristnosti, povezane s shranjevanjem datoteke.

#### <a name="wkwebviewerror"></a>wkwebview.error

S tem dogodkom lahko zaznamo, do kdaj je prišlo do napak spletnega pogleda med sestavljanjem ali branjem e-pošte, tako da lahko preprečimo težave, zaradi katerih z vašo aplikacijo ne bi bilo mogoče sestaviti ali prebrati e-pošte. 

Zbrana so ta polja: 

- **description** – opis napake

- **error_code** – koda napake za napako WKError

- **function_name** – ime funkcije JavaScript v primeru napake

- **js_exception_column_number** – številka stolpca, ko pride do izjeme JavaScript 

- **js_exception_line_number** – številka vrstice, ko pride do izjeme JavaScript

- **js_exception_message** – sporočilo izjeme, ko pride do izjeme JavaScript

- **js_exception_source_url** – URL vira, kjer je prišlo do izjeme JavaScript  

- **scenario** – kje je prišlo do napake. To je oštevilčenje. Možne so vrednosti »old_renderer«, »react_renderer« in »composing«.

#### <a name="wkwebviewterminate"></a>wkwebview.terminate

S tem dogodkom lahko zaznate, kdaj sistem konča spletni pogled. S temi podatki lahko nadzorujete, kateri uporabnik je zaznal napako pri sestavljanju ali branju e-poštnega sporočila. 

Zbrana so ta polja: 

- **is_foreground** – ali je bila aplikacija v ospredju, ko je prišlo do tega dogodka.

- **Scenario** – kje je prišlo do napake med izvajanjem upodabljanja ali sestavljanja.


## <a name="device-connectivity-and-configuration-data-events"></a>Podatkovni dogodki povezljivosti in konfiguracije naprave

V nadaljevanju tega članka so navedene podvrste podatkov v tej kategoriji:

- [Povezljivost in konfiguracija naprave](#device-connectivity-and-configuration-subtype)


### <a name="device-connectivity-and-configuration-subtype"></a>*Podvrsta povezljivosti in konfiguracije naprave*

Stanje omrežne povezave in nastavitve naprave, kot je pomnilnik.

#### <a name="applicationdidreceivememorywarning"></a>application.did.receive.memory.warning

Ta dogodek je poslan, ko nam na družba Apple sporoči, da v aplikaciji ni na voljo dovolj pomnilnika. Iz dogodka je razvidno, da smo v vaši napravi uvedli težavo upravljanja pomnilnika.

Zbrana so sledeča polja: 

- **current_memory_used** – prikaže, koliko pomnilnika je porabila aplikacija na točki, kjer je sistem zaznal, da je aplikaciji zmanjkalo pomnilnika.

- **current_memory_used_percentage** – prikaže odstotek pomnilnika, ki ga porabi aplikacija, od skupno razpoložljivega pomnilnika na točki, kjer je sistem zaznal, da je aplikaciji zmanjkalo pomnilnika.

- **currentVC** – prikaže trenutni pogled, ko je aplikaciji zmanjkalo pomnilnika.

- **has_hx** – dogodek, ki ponazarja, da račun uporablja našo novo storitev sinhronizacije, s katerim je mogoče zaznati težave, ki jih povzroči naša storitev sinhronizacije.

- **is_watch_app_installed** – prikaže, ali uporabnik trenutno uporablja napravo Apple Watch in ali je ta nameščena. S tem dogodkom ugotovimo negativni učinek zaradi naprave Watch.

- **is_watch_paired** – prikaže, ali uporabnik trenutno uporablja napravo Apple Watch in ali je ta seznanjena z uporabnikovo napravo. S tem dogodkom ugotovimo negativni učinek zaradi naprave Watch.

- **is_watch_supported_and_active** – prikaže, ali uporabnik trenutno uporablja napravo Apple Watch in ali je ta aktivna. S tem dogodkom ugotovimo negativni učinek zaradi naprave Watch.

- **rn_initialized** – prikaže, ali je bil zagnan React Native, ko je aplikaciji zmanjkalo pomnilnika.

- **running_time** – prikaže čas izvajanja aplikacije, ko je aplikaciji zmanjkalo pomnilnika.

#### <a name="conversationmemoryleak"></a>conversation.memory.leak

Omogoča nam, da zaznamo primere, kjer moramo zaradi pogleda pogovora prek e-pošte porabiti več pomnilnika kot običajno.

Zbrana so sledeča polja:

- Zbrana niso nobena polja ali dodani podatki. Zbirajo se samo dnevniki, če je bilo zaznano puščanje pomnilnika, povezano z nitjo pogovora.

#### <a name="coredatacorruption"></a>core.data.corruption

Omogoča nam, da zaznamo primere, ko vam ne moremo prikazati e-poštnih sporočil ali koledarja, ker je mesto, kjer hranimo vašo e-pošto v napravi, poškodovano.

Zbrana so sledeča polja:

- **errorSource** – prikaže, ali je do napake prišlo zaradi shranjevanja ali ustvarjanja.

- **sqlError** – številska koda napake, navedena na https://www.sqlite.org/c3ref/c_abort.html.

#### <a name="coredatacorruptionuserreset"></a>core.data.corruption.user.reset

Omogoča nam, da zaznamo primere, ko ste v aplikaciji izbrisali ali ponastavili svoj račun. Do težave je prišlo zaradi poškodovanih podatkov e-pošte, ki jih hranimo v vaši napravi.

Zbrana so sledeča polja:

- **errorSource** – prikaže vir napake (med shranjevanjem ali ustvarjanjem).

#### <a name="coredatadiagnostics"></a>core.data.diagnostics 

Omogoča nam, da zaznamo in odpravimo primere, kjer e-poštna shramba porablja preveč prostora za shranjevanje v napravi.

Zbrana so sledeča polja:

- **db_size_megabytes** – spremlja velikost osnovne zbirke podatkov, zaokroženo na najbližjih 25 MB in z najvišjo zmogljivostjo 500 MB.

#### <a name="generalpropertieslog"></a>general.properties.log

Ta dogodek zbira informacije, s katerimi lahko razvrstimo in kategoriziramo težave v Outlookovi aplikaciji, ki so povezane z nastavitvami dostopnosti in naprave.  Ta kategorizacija je zahtevana za določanje prioritet, kako težave vplivajo na stranke.

Zbrana so sledeča polja (velja samo za naprave s sistemom iOS):

- **bold_text** – prikaže, ali je v napravi vklopljena nastavitev krepkega besedila. S tem dogodkom lahko zaznamo težave, povezane s krepkim besedilom.

- **closed_captioning** – prikaže, ali je uporabnik v svoji napravi omogočil podnapise. S tem dogodkom lahko zaznamo težave, povezane s podnapisi.

- **darker_system_colors** – prikaže, ali je uporabnik v svoji napravi omogočil temnejše barve sistema. S tem dogodkom lahko zaznamo težave, povezane s to nastavitvijo.

- **gray_scale** – prikaže, ali je uporabnik v svoji napravi vklopil možnost sivine. S tem dogodkom lahko zaznamo težave, povezane s to nastavitvijo.

- **guided_access** – prikaže, ali je uporabnik v svoji napravi vklopil možnost vodenega dostopa. S tem dogodkom lahko zaznamo težave, povezane s to nastavitvijo.

- **invert_colors** – prikaže, ali je uporabnik v svoji napravi omogočil barvne negativne. S tem dogodkom lahko zaznamo težave, povezane s to nastavitvijo.

- **mono_audio** – prikaže, ali je uporabnik v svoji napravi omogočil mono zvok. S tem dogodkom lahko zaznamo težave, povezane s to nastavitvijo.

- **reduce_motion** – prikaže, ali je uporabnik v svoji napravi vklopil nastavitev zmanjšanja animacij. S tem dogodkom lahko zaznamo težave, povezane s to nastavitvijo.

- **reduce_transparency** – prikaže, ali je uporabnik v svoji napravi vklopil nastavitev za zmanjšanje prosojnosti. S tem dogodkom lahko zaznamo težave, povezane s to nastavitvijo.

- **speak_screen** – prikaže, ali je uporabnik v svoji napravi omogočil mono zvok. S tem dogodkom lahko zaznamo težave, povezane s to nastavitvijo.

- **speak_selection** – prikaže, ali je uporabnik v svoji napravi vklopil nastavitev izbire z govorom. S tem dogodkom lahko zaznamo težave, povezane s to nastavitvijo.

- **switch_control** – prikaže, ali je uporabnik v svoji napravi vklopil nastavitev preklopa nadzora. S tem dogodkom lahko zaznamo težave, povezane s to nastavitvijo.

- **voice_over** – prikaže, ali je uporabnik v svoji napravi vklopil nastavitev glasovnega nasnemavanja. S tem dogodkom lahko zaznamo težave, povezane s to nastavitvijo.

Zbrana so sledeča polja (velja samo za naprave s sistemom Android):

- **braille** – prikaže, ali je uporabnik v svoji napravi omogočil barvne negativne. S tem dogodkom lahko zaznamo težave, povezane s to nastavitvijo.

- **caption** – prikaže, ali je uporabnik v svoji napravi omogočil podnapise. S tem dogodkom lahko zaznamo težave, povezane s podnapisi.

- **color_inversion** – prikaže, ali je uporabnik v svoji napravi omogočil barvne negativne. S tem dogodkom lahko zaznamo težave, povezane s to nastavitvijo.

- **high_contrast** – prikaže, ali je uporabnik v svoji napravi vklopil nastavitev visokega kontrasta. S tem dogodkom lahko zaznamo težave, povezane s to nastavitvijo.

- **large_text** – prikaže, ali je v napravi vklopljena nastavitev večjega besedila. S tem dogodkom lahko zaznamo težave, povezane s to nastavitvijo.

- **oem_preinstall** – prikaže, ali je naša aplikacija vnaprej nameščena v napravo (to velja samo za naprave Samsung).

- **supported_abis** – prikaže, katere vrste binarnih vmesnikov aplikacije podpira okolje naprave. S tem dogodkom lahko zaznamo težave, povezane s to nastavitvijo.

- **switch_access** – prikaže, ali je uporabnik v svoji napravi vklopil nastavitev zamenjave nadzora. S tem dogodkom lahko zaznamo težave, povezane s to nastavitvijo.

- **talkback** – prikaže, ali je uporabnik v svoji napravi vklopil nastavitev povratnega govora. S tem dogodkom lahko zaznamo težave, povezane s to nastavitvijo.

- **theme_color** – barva teme po meri (izbere uporabnik), ki jo trenutno uporablja aplikacija

- **webview_kernel_version**: Različica spletnega ogleda Chromium jedra v napravi, ki nam pomaga odkriti težave z združljivostjo, povezane z različico spletnega pogleda.

- **webview_package_name**: Ime paketa spletnega ogleda v napravi, ki nam pomaga odkriti težave z združljivostjo, povezano z različico spletnega pogleda.

- **webview_package_version**: Različica paketa spletnega ogleda v napravi, ki nam pomaga odkriti težave z združljivostjo, povezane z različico spletnega pogleda.

#### <a name="lowstoragewarning"></a>low.storage.warning

Uporablja se za nadzor, če naša aplikacija nenadoma zavzame večino prostora za shranjevanje v napravi zaradi visoke porabe pomnilnika, ko v napravi primanjkuje prostora.

Zbrana so sledeča polja: 

- **free_bytes** – količina prostega prostora za shranjevanje, ki je na voljo v napravi.

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

#### <a name="officeserviceabilitymanagerofficesvcmgrprofile"></a>Office.ServiceabilityManager.OfficeSvcMgrProfile

Ta dogodek je sprožen ob zagonu upravitelja za storitve v Officeu in ima ključno vlogo pri zagotavljanju natančnih vpogledov, povezanih s stanjem uvedbe in aplikacije ter zrušitvami zaradi dodatkov pri najemniku stranke ter nam omogoča, da ustvarjamo vpoglede za skrbnika za IT, ki bo lahko uvajal posodobitve za službene računalnike.  

Zbrana so sledeča polja:

- **DeviceIdJoinToken** – uporablja se za združitev podatkov telemetrije iz stanja storitve in uvedbe z drugimi funkcionalnimi podatki, zbranimi prek prodajnega lijaka storitev.

- **TenantAssociationKeyStamped** – Zastavica logične vrednosti, ki se uporablja za določanje števila upravljanih naprav v Officeovim ekosistemu.
