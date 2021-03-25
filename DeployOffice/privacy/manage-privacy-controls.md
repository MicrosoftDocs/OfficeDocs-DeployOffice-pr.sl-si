---
title: Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Microsoft 365 aplikacije za podjetja
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: article
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection:
- Ent_O365
- M365-modern-desktop
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Officeovim skrbnikom omogoča informacije o načinu upravljanja kontrolnikov zasebnosti v storitvi Aplikacije ogrodja Microsoft 365 za podjetja (prej imenovan Office 365 ProPlus) z uporabo nastavitev pravilnika.
hideEdit: true
ms.openlocfilehash: 636916acf0cb36eecc7ba51318467264bb9ff2d4
ms.sourcegitcommit: 2c4bf05e77415559080766cc7d7f241e9f968108
ms.translationtype: HT
ms.contentlocale: sl-SI
ms.lasthandoff: 03/24/2021
ms.locfileid: "51181222"
---
# <a name="use-policy-settings-to-manage-privacy-controls-for-microsoft-365-apps-for-enterprise"></a>Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Microsoft 365 aplikacije za podjetja

> [!NOTE]
> Če si želite ogledati seznam Officeovih izdelkov, ki so zajeti v teh informacijah o zasebnosti, glejte [Kontrolnike zasebnosti, ki so na voljo za Officeove izdelke](products-versions-privacy-controls.md).

Microsoft si prizadeva, da vam omogoči informacije in kontrolnike, ki jih potrebujete za sprejemanje odločitev o načinu zbiranja in uporabe vaših podatkov pri uporabi storitve Aplikacije ogrodja Microsoft 365 za podjetja (prej imenovan Office 365 ProPlus).

V različici 1904 storitve Aplikacije ogrodja Microsoft 365 za podjetja smo uvedli nove nastavitve zasebnosti, s katerimi lahko upravljate nastavitve, povezane z naslednjo vsebino:

- ***Diagnostični podatki*** o uporabljeni programski opremi odjemalca za Office, ki jih je sistem zbral in poslal Microsoftu

- ***Povezane izkušnje***, ki za omogočanje razširjenih Officeovih funkcij uporabljajo storitve v oblaku.

V nadaljevanju si lahko ogledate pet novih nastavitev zasebnosti:

- Konfiguracija ravni diagnostičnih podatkov o programski opremi odjemalca, ki jih Office pošlje Microsoftu
- Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko analizirate vsebino
- Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko prenašate spletno vsebino
- Omogočanje uporabe dodatnih povezanih izkušenj v Officeu
- Omogočanje uporabe povezanih izkušenj v Officeu

Te nastavitve pravilnika lahko uvedete s storitvijo pravilnika skupine ali [pravilnika za Office v oblaku](../overview-office-cloud-policy-service.md). Če uporabljate pravilnik skupine, prenesite najnovejše različice datotek za skrbniške predloge (ADMX/ADML) iz [Microsoftovega centra za prenose](https://www.microsoft.com/download/details.aspx?id=49030).

> [!NOTE]
> - Če želite več informacij o upravljanju kontrolnikov zasebnosti za Office for Mac, preberite [Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office for Mac](mac-privacy-preferences.md).
> - Če želite več informacij o podobnih nastavitvah za Office v računalnikih s sistemom iOS, preberite članek [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom iOS](ios-privacy-preferences.md).
> - Če želite več informacij o podobnih nastavitvah za Office v računalnikih s sistemom Android, preberite članek [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom Android](android-privacy-controls.md).
> - Če želite informacije o kontrolnikih zasebnosti za aplikacije Office v spletu, si oglejte [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za aplikacije Office v spletu](office-web-privacy-controls.md).


Če uporabljate orodje za upravljanje pravilnika skupine, vse nastavitve pravilnika najdete v razdelku Konfiguracija uporabnika\\Pravilniki\\Skrbniške predloge\\Microsoft Office 2016\\Zasebnost\\Središče zaupanja.

Te nove nastavitve pravilnika veljajo tudi za namizne različice Project in Visio, ki so priložene nekaterim naročniškim paketom, kot sta Project Plan 5 ali Visio Plan 2. Nanašajo se tudi na Aplikacije ogrodja Microsoft 365 za poslovanje (prej imenovane Office 365 Business).

Nekatere obstoječe nastavitve pravilnika ne bodo več veljale za Aplikacije ogrodja Microsoft 365 za podjetja; prav tako je prišlo do nekaterih sprememb uporabniškega vmesnika za nastavitve pravilnika, na katere bodite pozorni, saj jih bodo morda opazili tudi vaši uporabniki in vas povprašali o njih.

Vse nove nastavitve pravilnika pazljivo preizkusite v omejenem, nadzorovanem okolju, v katerem lahko zagotovite želeni učinek konfiguriranih nastavitev. Nato nastavitve pravilnika uveljavite v svoji organizaciji.

## <a name="policy-setting-for-diagnostic-data"></a>Nastavitev pravilnika za diagnostične podatke

Diagnostični podatki se uporabljajo za zaščito, posodobitev, zaznavanje težav in njihovo odpravljanje v Officeu ter za izboljšave izdelka.

Z nastavitvijo pravilnika *Konfiguracija ravni diagnostičnih podatkov o programski opremi odjemalca, ki jih Office pošlje Microsoftu* lahko določite raven diagnostičnih podatkov, ki so poslani Microsoftu.

Če omogočite to nastavitev pravilnika, izberite, katera raven diagnostičnih podatkov bo poslana Microsoftu. Izbirate lahko med naslednji ravnmi: »Zahtevana«, »Izbirna« ali »Nobena«.

- Če izberete ***Zahtevano***, Microsoft prejme najnižjo stopnjo podatkov, ki še omogoča varnost, posodobitev in pričakovano delovanje Officea v napravi, v kateri je sistem nameščen.

- Če izberete ***Izbirno***, Microsoft prejme dodatne podatke, ki zagotavljajo izboljšave izdelkov in omogočajo razširjene informacije za zaznavanje, diagnosticiranje in odpravljanje težav. Če se odločite, da boste poslali izbirne diagnostične podatke, boste prav tako poslali še zahtevane diagnostične podatke.

- Če izberete ***Nobena***, Microsoft ne prejme nobenih diagnostičnih podatkov o programski opremi odjemalca za napravo, v kateri je nameščen Office. Vendar pa s to možnostjo znatno omejite Microsoftovo zmogljivost zaznavanja, diagnosticiranja in odpravljanja težav, na katere lahko naletijo vaši uporabniki pri uporabi Officea.

Če onemogočite ali ne konfigurirate te nastavitve pravilnika, Microsoft prejme izbirne in zahtevane diagnostične podatke.

Če želite izvedeti več informacij o diagnostičnih podatkih, preberite te članke:

- [Pregled kontrolnikov za zasebnost za Microsoft 365 aplikacije za podjetja](overview-privacy-controls.md)
- [Zahtevani diagnostični podatki za Office](required-diagnostic-data.md)
- [Izbirni diagnostični podatki za Office](optional-diagnostic-data.md)
- [Uporaba pregledovalnika diagnostičnih podatkov z Officeom](https://support.microsoft.com/office/cf761ce9-d805-4c60-a339-4e07f3182855)

## <a name="policy-settings-for-connected-experiences"></a>Nastavitve pravilnika za povezane izkušnje

Aplikacije ogrodja Microsoft 365 za podjetja sestavljajo aplikacije odjemalske programske opreme in povezane izkušnje, zasnovane tako, da vam omogočajo bolj učinkovito ustvarjanje, komuniciranje in sodelovanje. Sodelovanje z drugimi na dokumentu, ki je shranjen v storitvi OneDrive za podjetja, ali prevajanje vsebine Wordovega dokumenta v drug jezik sta primera povezanih izkušenj.

Zavedamo se, da bi morda radi izbirali, katere vrste povezanih izkušenj so na voljo za vaše uporabnike pri delu v Officeovih aplikacijah. Zato smo za vas pripravili štiri nove nastavitve pravilnika:

- Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko analizirate vsebino
- Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko prenašate spletno vsebino
- Omogočanje uporabe dodatnih povezanih izkušenj v Officeu
- Omogočanje uporabe povezanih izkušenj v Officeu

Če ne konfigurirate teh nastavitev pravilnika, so na voljo vse vrste povezanih izkušenj. Tako bodo vaši uporabniki lahko dostopali do vseh funkcij, ki so na voljo v storitvi Aplikacije ogrodja Microsoft 365 za podjetja. Vendar se zavedamo, da morda želite izklopiti nekatere ali vse povezane izkušnje zaradi določenih zahtev vaše organizacije.

Če se odločite, da svojim uporabnikom ne boste omogočili določenih vrst povezanih izkušenj, bo trak ali meni za te povezane izkušnje zatemnjen oziroma bodo uporabniki prejeli sporočilo o napaki, ker so poskušali uporabiti te povezane izkušnje. V tem primeru [zahtevani podatki storitve](required-service-data.md) za te povezane izkušnje ne bodo poslani Microsoftu.

Če so vaši uporabniki vpisani v Office s poverilnicami organizacije, ki jih včasih imenujemo tudi službeni ali šolski račun, ne bodo mogli vklopiti teh povezanih izkušenj, ki so del storitve Aplikacije ogrodja Microsoft 365 za podjetja, oziroma jih izklopiti.

### <a name="policy-setting-for-connected-experiences-that-analyze-your-content"></a>Nastavitev pravilnika za povezane izkušnje, s katerimi lahko analizirate vsebino

To so izkušnje, ki na podlagi Officeove vsebine nudijo priporočila za načrte, predloge za urejanje, vpoglede v podatke in podobne funkcije. Na primer Oblikovalnik za PowerPoint ali Prevajalnik. Če si želite ogledati seznam povezanih izkušenj, glejte [Povezane izkušnje v Officeu](connected-experiences.md).

Z nastavitvijo pravilnika *Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko analizirate vsebino* lahko upravljate, ali so te vrste povezanih izkušenj na voljo za vaše uporabnike. Če ne konfigurirate te nastavitve pravilnika, so te povezane izkušnje na voljo vašim uporabnikom.

Če onemogočite nastavitev pravilnika *Dovoli uporabo povezanih izkušenj v Officeu*, povezane izkušnje, s katerimi lahko analizirate vsebino, ne bodo na voljo vašim uporabnikom.

### <a name="policy-setting-for-connected-experiences-that-download-online-content"></a>Nastavitev pravilnika za povezane izkušnje, s katerimi lahko prenašate spletno vsebino

S temi izkušnjami lahko poiščete in prenesete spletno vsebino, vključno s predlogami, slikami, 3D-modeli, videoposnetki in referenčnim gradivom, s katero izpopolnite svoje dokumente. Denimo Officeove predloge ali orodje za hitri začetek za PowerPoint. Če si želite ogledati seznam povezanih izkušenj, glejte [Povezane izkušnje v Officeu](connected-experiences.md).

Z nastavitvijo pravilnika *Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko prenašate spletno vsebino* lahko upravljate, ali so te vrste povezanih izkušenj na voljo za vaše uporabnike. Če ne konfigurirate te nastavitve pravilnika, so te povezane izkušnje na voljo vašim uporabnikom.

Če onemogočite nastavitev pravilnika *Dovoli uporabo povezanih izkušenj v Officeu*, povezane izkušnje, s katerimi lahko prenašate spletno vsebino, ne bodo na voljo vašim uporabnikom.

### <a name="policy-setting-for-optional-connected-experiences"></a>Nastavitev pravilnika za izbirne povezane izkušnje

Poleg povezanih izkušenj, omenjenih v tem članku, ki so del storitve Aplikacije ogrodja Microsoft 365 za podjetja, lahko izbirate še med dodatnimi izbirnimi povezanimi izkušnjami, s katerimi lahko vaši uporabniki dostopajo do svojih računov organizacije. Na primer funkcije LinkedIn pomočnika za življenjepis v Wordu ali funkcija 3D-zemljevidov v Excelu, ki uporablja Bing. Če si želite ogledati več primerov, preberite [Pregled izbirnih povezanih izkušenj v Officeu](optional-connected-experiences.md).

Te povezane izkušnje so drugačne, saj niso zajete v komercialno pogodbo organizacije z Microsoftom. Izbirne povezane izkušnje, ki jih neposredno ponuja Microsoft uporabnikom in jih ureja [pogodba o Microsoftovih storitvah](https://www.microsoft.com/servicesagreement) in ne [pogoji spletnih storitev](https://www.microsoft.com/licensing/product-licensing/products). V nekaterih primerih vsebino ali funkcionalnost tretjih oseb omogočajo te izbirne povezane izkušnje, za katere lahko veljajo tudi drugi pogoji. Če želite izvedeti več, preberite [Pregled izbirnih povezanih izkušenj v Officeu](optional-connected-experiences.md).

Z nastavitvijo pravilnika *Dovoli uporabo dodatnih povezanih izkušenj v Officeu* lahko upravljate, ali so te vrste povezanih izkušenj na voljo za vaše uporabnike. Če ne konfigurirate te nastavitve pravilnika, so te izbirne povezane izkušnje na voljo vašim uporabnikom.

> [!NOTE]
> Če želite uporabiti nastavitev pravilnika *Dovoli uporabo dodatnih izbirnih povezanih izkušenj  Officeu* za količinsko licencirane različice izdelka Office 2019, Project 2019 ali Visio 2019, morate uporabiti pravilnik skupine. Ne morete uporabiti Storitev pravilnika za Office Cloud. To velja tudi, če je Office 2019, Project 2019 ali Visio 2019 konfiguriran za uporabo kanala za posodobitve PerpetualVL2019.

Tudi če se odločite, da bodo te izbirne povezane izkušnje na voljo vašim uporabnikom, jih lahko ti izklopijo kot skupina tako, da odprejo [pogovorno okno z nastavitvami zasebnosti](https://support.microsoft.com/office/3e7bc183-bf52-4fd0-8e6b-78978f7f121b). Vašim uporabnikom je ta izbira na voljo samo, če so vpisani v Office s svojimi poverilnicami organizacije (včasih jih imenujemo tudi službeni ali šolski račun), ne pa če so vpisani z osebnim e-poštnim naslovom.

Nekatere od teh izbirnih povezanih izkušenj lahko uvrščamo tudi v povezane izkušnje, s katerimi lahko analizirate vsebino ali prenašate spletno vsebino. Vstavljanje spletnih slik je denimo izbirna povezana izkušnja, ki jo omogoča Microsoft Bing, obenem pa je tudi povezana izkušnja, s katero lahko prenašate spletno vsebino. Če torej onemogočite nastavitev pravilnika *Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko prenašate spletno vsebino*, vstavljanje spletnih slik ne bo na voljo vašim uporabnikom. Prav tako ne bo na voljo, tudi če ste omogočili nastavitev pravilnika *Dovoli uporabo dodatnih izbirnih povezanih izkušenj v Officeu*. Če želite več informacij o tem, s katerimi povezanimi izkušnjami je mogoče analizirati vsebino ali prenašati spletno vsebino, preberite [Povezane izkušnje v Officeu](connected-experiences.md).

Obstaja pa izjema, na katero morate biti pozorni. Z nastavitvijo pravilnika *Dovoli uporabo dodatnih izbirnih povezanih izkušenj v Officeu* ni mogoče upravljati izkušenj, ki zahtevajo, da račun za LinkedIn povežete z Microsoftovim službenim ali šolskim računom. Če želite nadzorovati te vrste izkušenj (kot so informacije storitve LinkedIn na [kartici profila](https://support.microsoft.com/office/365-e80f931f-5fc4-4a59-ba6e-c1e35a85b501) v Outlooku), glejte [LinkedIn v Microsoftovih aplikacijah in storitvah](https://support.microsoft.com/office/dc81cc70-4d64-4755-9f1c-b9536e34d381) in [Integracija povezav računa LinkedIn v Azure Active Directory](/azure/active-directory/users-groups-roles/linkedin-integration).

### <a name="policy-setting-for-most-connected-experiences"></a>Nastavitev pravilnika za najpogostejše povezane izkušnje

Z nastavitvijo pravilnika *Dovoli uporabo povezanih izkušenj v Officeu* lahko upravljate, ali bodo za vaše uporabnike na voljo najpogostejše povezane izkušnje v storitvi Aplikacije ogrodja Microsoft 365 za podjetja. Če onemogočite nastavitev pravilnika, te vrste povezanih izkušenj ne bodo na voljo za vaše uporabnike:

- Izkušnje, s katerimi analizirate vsebino
- Izkušnje, s katerimi prenašate spletno vsebino
- Izbirne povezane izkušnje

Če onemogočite to nastavitev pravilnika boste prav tako izklopili večino drugih povezanih izkušenj, kot sta soavtorstvo in spletna shramba datotek. Če si želite ogledati seznam drugih povezanih izkušenj, glejte [Povezane izkušnje v Officeu](connected-experiences.md).

Četudi onemogočite to nastavitev pravilnika, bo še vedno na voljo omejena funkcionalnost Officea, kot je sinhronizacija nabiralnika v Outlooku, in še naprej bodo delovale skupine ter Skype za podjetja. [Osnovne storitve](essential-services.md), kot je storitev licenciranja, s katero potrdite, da imate ustrezno licenco za uporabo Officea, prav tako ostanejo na voljo.

## <a name="existing-policy-settings-that-are-replaced-by-new-policy-settings"></a>Obstoječe nastavitve pravilnika, ki so jih nadomestile nove nastavitve pravilnika

Od različice 1904 naprej obstajata dve nastavitvi pravilnika, ki se ne uporabljata več za Aplikacije ogrodja Microsoft 365 za podjetja. Ogledate si ju lahko v nadaljevanju tega članka:

- **Pošiljanje osebnih podatkov** – to nastavitev lahko najdete v razdelku Konfiguracija uporabnika\\Pravilniki\\Skrbniške predloge\\Microsoft Office 2016\\Zasebnost\\Središče zaupanja.

- **Možnosti spletne vsebine** – to nastavitev lahko najdete v razdelku Konfiguracija uporabnika\\Pravilniki\\Skrbniške predloge\\Microsoft Office 2016\\Orodja | Možnosti | Splošno | Možnosti storitve...\\Spletna vsebina.

Od različice 1904 naprej konfiguriranje teh dveh obstoječih nastavitev pravilnika ne vpliva več na storitev Aplikacije ogrodja Microsoft 365 za podjetja. Nastavitvi ne veljata več, saj so njuno funkcionalnost zamenjale te nove nastavitve pravilnika:

- Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko analizirate vsebino
- Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko prenašate spletno vsebino
- Omogočanje uporabe dodatnih povezanih izkušenj v Officeu
- Omogočanje uporabe povezanih izkušenj v Officeu

Z novimi nastavitvami pravilnika dobite lahko bolj podroben nadzor kot z obstoječima nastavitvama pravilnika. Če ste na primer prej uporabili nastavitev pravilnika *Pošiljanje osebnih podatkov*, sta se izklopila tako orodje za hiter začetek v PowerPointu in pametno iskanje. Toda če sedaj, ko so na voljo nove nastavitve pravilnika, uporabite nastavitev pravilnika *Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko analizirate vsebino*, da izklopite takšno vrsto povezanih izkušenj, se izklopi samo pametno iskanje. Orodje za hiter začetek v PowerPointu je še vedno na voljo za vaše uporabnike.

Nastavitve pravilnika so še vedno prikazane v orodju za upravljanje pravilnika skupine, saj še vedno veljajo za količinsko licencirane različice sistemov Office 2016 in Office 2019, na primer Office Professional Plus 2019.

## <a name="what-about-existing-policy-settings-that-control-connected-experiences"></a>Kaj pa obstoječe nastavitve pravilnika, ki nadzorujejo povezane izkušnje?

Kot se verjetno že izvedeli, so na voljo nekatere obstoječe nastavitve pravilnika, s katerimi lahko upravljate povezne izkušnje. V nadaljevanju si lahko ogledate nekatere primer obstoječih nastavitev pravilnika:

- *Možnosti oblikovalnika za PowerPoint* – to nastavitev lahko najdete v razdelku Konfiguracija uporabnika\\Pravilniki\\Skrbniške predloge\\Microsoft Office 2016\\Orodja | Možnosti | Splošno | Možnosti storitve...\\Oblikovalnik za PowerPoint.

- *Izklop orodja za hiter začetek* – to nastavitev lahko najdete v razdelku Konfiguracija uporabnika\\Pravilniki\\Skrbniške predloge\\Microsoft PowerPoint 2016\\PowerPointove možnosti\\Splošno

- *Dovoli funkcijo pomočnika za življenjepis v storitvi LinkedIn* – to nastavitev lahko najdete v razdelku Konfiguracija uporabnika\\Pravilniki\\Skrbniške predloge\\Microsoft Word 2016\\Wordove možnosti\\Splošno

 Te obstoječe nastavitve pravilnika lahko še vedno uporabite, če želite izklopiti posamezne povezane izkušnje. Vendar ne pozabite, da če uporabite eno od novih nastavitev pravilnika, lahko z novo nastavitvijo pravilnika izklopite povezano izkušnjo, ki ste jo vklopili z drugo nastavitvijo pravilnika. Če na primer omogočite nastavitev pravilnika *Dovoli funkcijo pomočnika za življenjepis v storitvi LinkedIn* in onemogočite nastavitev pravilnika *Dovoli uporabo povezanih izkušenj v Officeu*, pomočnik za življenjepis v storitvi LinkedIn ne bo na voljo za vaše uporabnike.

Na splošno velja, da če z eno nastavitvijo pravilnika vklopite določeno povezano izkušnjo, hkrati pa z drugo nastavitvijo pravilnika izklopite to vrsto povezane izkušnje, bo ta določena povezana izkušnja izklopljena za vaše uporabnike.

## <a name="privacy-related-changes-to-the-office-ui"></a>Spremembe, povezane z zasebnostjo, v uporabniškem vmesniku za Office

Vaši uporabniki bodo morda opazili nekatere spremembe uporabniškega vmesnika v storitvi Aplikacije ogrodja Microsoft 365 za podjetja, povezane z zasebnostjo, in vas povprašali o njih. Te spremembe so neposreden učinek novih kontrolnikov zasebnosti in nastavitev pravilnika, ki so na voljo od različice 1904.

### <a name="dialog-about-optional-connected-experiences"></a>Pogovorno okno o izbirnih povezanih izkušnjah

Če ste svojim uporabnikom omogočili [izbirne povezne izkušnje](optional-connected-experiences.md), se jim bo prikazalo informativno pogovorno okno, ko prvič zaženejo Officeovo aplikacijo po posodobitvi na različico 1904 ali novejšo. To pogovorno okno vaše uporabnike obvešča, da lahko uporabijo te izbirne povezane izkušnje in spremenijo to nastavitev tako, da odprejo meni **Datoteka** > **Račun** > **Zasebnost računa**.

### <a name="privacy-settings-removed-from-the-office-ui"></a>Nastavitve zasebnosti, odstranjene iz uporabniškega vmesnika za Office

Iz menija **Datoteka** > **Možnosti** > **Središče zaupanja** > **Nastavitve središča zaupanja …** smo odstranili naslednje nastavitve > **Možnosti zasebnosti**:

- Officeu dovolite, da ustvarja izboljšave izdelkov na osnovi Officeove vsebine v moji napravi in dostopa do njih ter tako pridobite načrte, informacije, priporočila in storitve.

- Omogočite Officeu vzpostavitev povezave z Microsoftovimi spletnimi storitvami, da zagotovite funkcije, pomembne za vaš način uporabe in nastavitve.

Poleg tega smo v meniju **Datoteka** > **Možnosti** > **Splošno** odstranili izbiro za omogočanje Officeovih pametnih storitev.

Kot skrbnik organizacije imate sedaj z novimi nastavitvami pravilnika, opisanimi v tem članku, nadzor nad enakovrednimi storitvami.

### <a name="privacy-settings-added-to-the-office-ui"></a>Nastavitve zasebnosti, dodane v uporabniški vmesnik za Office

V nadaljevanju si oglejte elemente, ki smo jih dodali v uporabniški vmesnik za Office:

- V meniju **Datoteka** > **Račun** je na voljo nova izbira za **Račun zasebnosti** > **Upravljanje nastavitev**. V razdelku **Upravljanje nastavitev** lahko uporabniki izklopijo izbirne povezne izkušnje, če ste jim omogočili to možnost.

- V meniju **Datoteka** > **Možnosti** > **Središče zaupanja** > **Nastavitve središča zaupanja...** > **Možnosti zasebnosti** je na voljo možnost za omogočanje uporabe orodja [Pregledovalnik diagnostičnih podatkov](https://support.microsoft.com/office/cf761ce9-d805-4c60-a339-4e07f3182855) v napravi.

 
## <a name="control-privacy-settings-by-editing-the-registry"></a>Nadzor nastavitev zasebnosti z urejanjem registra

Nekateri skrbniki spreminjajo nastavitve neposredno v registru, na primer s skriptom. Ne uporabljajo pravilnika skupine ali Officeove storitve pravilnika v oblaku. Te informacije lahko uporabite za konfiguracijo nastavitev zasebnosti neposredno v registru.


|**Nastavitev pravilnika** |**Nastavitev registra**  |**Vrednosti**  |
|---------|---------|---------|---------|
|Konfiguracija ravni diagnostičnih podatkov o programski opremi odjemalca, ki jih Office pošlje Microsoftu  | SendTelemetry |1=zahtevano <br/> 2=izbirno <br/> 3=niti eno niti drugo|
|Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko analizirate vsebino  | UserContentDisabled | 1=omogočeno <br/> 2=onemogočeno|
|Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko prenašate spletno vsebino  | DownloadContentDisabled | 1=omogočeno <br/> 2=onemogočeno|
|Omogočanje uporabe dodatnih povezanih izkušenj v Officeu   | ControllerConnectedServicesEnabled  |1=omogočeno <br/> 2=onemogočeno|
|Omogočanje uporabe povezanih izkušenj v Officeu | DisconnectedState  | 1=omogočeno <br/> 2=onemogočeno|

Če želite ustvariti datoteko .reg za nastavitve zasebnosti, odprite Beležko in kopirajte notri te vrstice. Prilagodite vrednosti svojim potrebam, nato pa shranite datoteko. Poskrbite, da bo imelo ime datoteke pripono .reg

```console
Windows Registry Editor Version 5.00

[HKEY_CURRENT_USER\Software\Policies\Microsoft\office\16.0\common\privacy]
"disconnectedstate"=dword:00000001
"usercontentdisabled"=dword:00000001
"downloadcontentdisabled"=dword:00000001
"controllerconnectedservicesenabled"=dword:00000001

[HKEY_CURRENT_USER\Software\Policies\Microsoft\office\common\clienttelemetry]
"sendtelemetry"=dword:00000002
```

Uporabite lahko to datoteko .reg z ukazom regedit.exe v skriptu in konfigurirate nastavitve zasebnosti za uporabnika.