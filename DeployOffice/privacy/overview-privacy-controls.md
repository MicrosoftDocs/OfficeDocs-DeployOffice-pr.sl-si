---
title: Pregled kontrolnikov zasebnosti za Office 365 ProPlus
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: conceptual
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection:
- Ent_O365
- M365-modern-desktop
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Officeovim skrbnikom zagotavlja pregled kontrolnikov zasebnosti za Office 365 ProPlus, vključno z diagnostičnimi podatki in povezanimi izkušnjami.
hideEdit: true
ms.openlocfilehash: 24a3d30d05fb2a1456e10d8a8036f31c25c14db7
ms.sourcegitcommit: 02c4120c0b10bfe378d21d60699ae49aaef97834
ms.translationtype: HT
ms.contentlocale: sl-SI
ms.lasthandoff: 10/15/2019
ms.locfileid: "37510731"
---
# <a name="overview-of-privacy-controls-for-office-365-proplus"></a>Pregled kontrolnikov zasebnosti za Office 365 ProPlus

Microsoft si prizadeva, da vam omogoči informacije in kontrolnike, ki jih potrebujete za sprejemanje odločitev o načinu zbiranja in uporabe vaših podatkov pri uporabi storitve Office 365 ProPlus.

Od različice 1904 storitve Office 365 ProPlus dalje (ki je bila izdana v mesečnem kanalu 29. aprila 2019), boste lahko uporabljali nove, posodobljene in izboljšanje kontrolnike zasebnosti za ta področja:
- ***Diagnostični podatki*** o uporabljeni programski opremi odjemalca za Office v računalnikih z nameščenim sistemom Windows v vaši organizaciji, ki jih je sistem zbral in poslal Microsoftu.
- ***Povezane izkušnje***, ki za omogočanje razširjenih Officeovih funkcij uporabljajo storitve v oblaku.

V sklopu sprememb smo dodali nove in posodobljene elemente uporabniškega vmesnika in nastavitve pravilnika.

> [!IMPORTANT]
> - Te spremembe veljajo za Access, Excel, OneNote, Outlook, PowerPoint, Publisher in Word.
> - Te spremembe se nanašajo tudi na:
>   - Različico 16.28 ali novejšo naslednjih aplikacij sistema Office za Mac: Excel, Outlook, OneNote, PowerPoint in Word.
>   - Različico 1904 ali novejšo za namizne različice Projecta in Visia, ki sta vključena v nekatere naročniške pakete, kot sta paketa Project Online Professional ali Visio Online Plan 2.
> - Kontrolnike zasebnosti smo vključili v različico 1908 polletnega kanala (ciljno usmerjen), ki je bil izdan 10. septembra 2019. Predvidoma bodo na voljo v polletnem kanalu januarja 2020.
> - Ti kontrolniki za varnost so na voljo za različico 2.30 in poznejše različice iOS za Excel, OneNote, PowerPoint in Word, kot tudi za različico 1.17 in poznejše različice Visio Viewer za iOS.
> - Večino aplikacij Office za splet bodo nov kontrolnik zasebnosti za [izbirne povezane izkušnje](optional-connected-experiences.md) predvidoma začele uporabljati v sredini oktobra 2019. Te aplikacije so: Excel za splet, OneNote za splet, PowerPoint za splet, Visio za splet in Word za splet. Pred tem pa lahko uporabite [Officeovo storitev pravilnika v oblaku](../overview-office-cloud-policy-service.md), da konfigurirate ustrezno [nastavitev pravilnika](manage-privacy-controls.md#policy-setting-for-optional-connected-experiences).
> - Nove in izboljšane kontrolnike zasebnosti bomo razširili dodatnim Officeovim odjemalcem, vključno z aplikacijo Teams in našimi mobilnimi aplikacijami. Več informacij o teh spremembah bomo razkrili v prihajajočih se mesecih. Še naprej bomo pozorno prisluhnili vašim povratnim informacijam in poskrbeli za izboljšave za vse odjemalce in storitve za Office 365.

## <a name="diagnostic-data-sent-from-office-365-proplus-to-microsoft"></a>Diagnostični podatki, poslani Microsoftu iz storitve Office 365 ProPlus

Diagnostični podatki se uporabljajo za zaščito, posodobitev, zaznavanje težav in njihovo odpravljanje v Officeu ter za izboljšave izdelka. Ti podatki ne vključujejo uporabniškega imena ali e-poštnega naslova, vsebine datotek uporabnika ali informacij o aplikacijah, ki niso del Officea.

Diagnostični podatki o uporabljeni programski opremi odjemalca za Office v računalnikih z nameščenim sistemom Windows v vaši organizaciji so bili zbrani in poslani Microsoftu.

Izbirate lahko med tremi ravnmi diagnostičnih podatkov programske opreme odjemalca za Office 365 ProPlus:

- **Zahtevano** – najnižja raven podatkov, ki še omogoča varnost, posodobitev in pričakovano delovanje Officea v napravi, v kateri je sistem nameščen.

- **Izbirno** – dodatni podatki, ki zagotavljajo izboljšave izdelkov in omogočajo razširjene informacije za zaznavanje, diagnosticiranje in odpravljanje težav.

- **Nobena** – zbrani in poslani niso nobeni diagnostični podatki o programski opremi odjemalca za napravo, v kateri je nameščen Office. Vendar pa s to možnostjo znatno omejite našo zmogljivost zaznavanja, diagnosticiranja in odpravljanja težav, na katere lahko naletijo vaši uporabniki pri uporabi Officea.

Zahtevani diagnostični podatki lahko na primer vključujejo informacije o različici Officea, nameščeni v napravi, ali informacije o zrušitvah Officeovih aplikacij, ko poskušate odpreti dokumente. Izbirni diagnostični podatki lahko vključujejo informacije o času, ki je zahtevan za shranjevanje dokumenta, in morda ponazarjajo na težavo, povezano s shranjevanjem v vašo napravo.

Če se odločite, da nam boste poslali izbirne diagnostične podatke, nam boste prav tako poslali še zahtevane diagnostične podatke.

Kot skrbnik organizacije lahko z nastavitvijo pravilnika določite, katero raven diagnostičnih podatkov bomo prejeli. Izbirni diagnostični podatki bodo poslani Microsoftu, razen če ne spremenite nastavitve. Če nam posredujete izbirne diagnostične podatke, bo ekipa Officeovih inženirjev lahko uspešnejša pri zaznavanju, diagnosticiranju in omejitvi težav in bo tako zmanjšala negativne učinke na vašo organizacijo.

Če so vaši uporabniki vpisani v Office s poverilnicami organizacije, ki jih včasih imenujemo tudi službeni ali šolski račun, ne bodo mogli spremeniti ravni diagnostičnih podatkov za svoje naprave.

Ti diagnostični podatki ne vključujejo imen uporabnikov, njihovih e-poštnih naslovov ali vsebine njihovih datotek v Officeu. Nas sitem ustvari enolični ID, ki ga poveže z diagnostičnimi podatki o vaših uporabnikih. Ko prejmemo diagnostične podatke, iz katerih je razvidno, da se je ena naših aplikacij 100-krat nepravilno zaustavila, lahko s tem ID-jem določimo, ali je 100 zrušitev povzročil en uporabnik oziroma je 100 uporabnikov doživelo vsako po eno zrušitev. Enoličnega ID-ja ne bomo uporabili za prepoznavanje določenega uporabnika.

Če si želite ogledati, katere vrste diagnostičnih podatkov so poslane Microsoftu, uporabite brezplačen pregledovalnik diagnostičnih podatkov, ki ga lahko prenesete in namestite iz Trgovine Microsoft.

Če želite več informacij, preberite te članke:

- [Zahtevani diagnostični podatki za Office](required-diagnostic-data.md)
- [Izbirni diagnostični podatki za Office](optional-diagnostic-data.md)
- [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office 365 ProPlus](manage-privacy-controls.md)
- [Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office za Mac](mac-privacy-preferences.md)
- [Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom iOS](ios-privacy-preferences.md)
- [Uporaba pregledovalnika diagnostičnih podatkov z Officeom](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

## <a name="connected-experiences-for-office-365-proplus"></a>Povezane izkušnje za Office 365 ProPlus

Office 365 ProPlus vključuje aplikacije za programsko opremo odjemalca in povezane izkušnje, s katerimi lahko ustvarjate, komunicirate ter sodelujete na učinkovitejši način. Sodelovanje z drugimi na dokumentu, ki je shranjen v storitvi OneDrive za podjetja, ali prevajanje vsebine Wordovega dokumenta v drug jezik sta primera povezanih izkušenj.

Zavedamo se, da bi morda radi izbirali, katere vrste povezanih izkušenj so na voljo za vaše uporabnike pri delu v Officeovih aplikacijah. Kot skrbnik organizacije imate na voljo nastavitve pravilnika, s katerimi lahko določite, ali svojim uporabnikom želite omogočiti te vrste povezanih izkušenj:

- **Izkušnje, s katerimi lahko analizirate vsebino** – izkušnje, ki na podlagi Officeove vsebine nudijo priporočila za načrte, predloge za urejanje, vpoglede v podatke in podobne funkcije. Kot na primer oblikovalnik za PowerPoint ali urejevalnik v Wordu.

- **Izkušnje, s katerimi lahko prenašate spletno vsebino** – izkušnje, ki vam omogočajo, da poiščete in prenesete spletno vsebino, vključno s predlogami, slikami, 3D-modeli, videoposnetki in referenčnim gradivom, s katero izpopolnite svoje dokumente. Denimo Officeove predloge ali orodje za hitri začetek za PowerPoint.

Svojim uporabnikom želite na primer omogočiti povezane izkušnje, s katerimi lahko prenašajo spletno vsebino, ne pa povezanih izkušenj, s katerimi lahko analizirajo vsebino. Če ne konfigurirate teh nastavitev pravilnika, so te povezane izkušnje na voljo vašim uporabnik om.

Na voljo je tudi nastavitev pravilnika, s katero lahko izklopite te povezane izkušnje in obenem tudi druge povezane izkušnje, kot sta soavtorstvo dokumentov in spletna shramba datotek. Tudi če s to nastavitvijo pravilnika izklopite vse te povezane izkušnje, bo določena Officeova funkcionalnost še vedno na voljo, na primer sinhronizacija vašega nabiralnika v Outlooku, uporaba skupin ali Skype za podjetja ter vse osnovne storitve, opisane v nadaljevanju tega članka.

Če se odločite, da svojim uporabnikom ne boste omogočili določenih vrst povezanih izkušenj, bo trak ali meni za te povezane izkušnje zatemnjen oziroma bodo uporabniki prejeli sporočilo o napaki, ker so poskušali uporabiti te povezane izkušnje.

Če so vaši uporabniki vpisani v Office s poverilnicami organizacije, ki jih včasih imenujemo tudi službeni ali šolski račun, ne bodo mogli vklapljati teh povezanih izkušenj oziroma jih izklapljati.

Če želite več informacij, preberite te članke:

- [Povezane izkušnje v Officeu](connected-experiences.md)
- [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office 365 ProPlus](manage-privacy-controls.md)
- [Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office za Mac](mac-privacy-preferences.md)
- [Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom iOS](ios-privacy-preferences.md)

## <a name="optional-connected-experiences-for-office-365-proplus"></a>Izbirne povezane izkušnje za Office 365 ProPlus

Poleg povezanih izkušenj, omenjenih v tem članku, ki so del storitve Office 365 ProPlus, lahko izbirate še med dodatnimi izbirnimi povezanimi izkušnjami, s katerimi lahko vaši uporabniki dostopajo do svojih računov organizacije. Na primer funkcije LinkedIn pomočnika za življenjepis v Wordu ali funkcija 3D-zemljevidov v Excelu, ki uporablja Bing.

To so izbirne povezane izkušnje, ki niso zajete v komercialno pogodbo organizacije z Microsoftom, temveč jih urejajo ločeni pogoji in določila. Izbirne povezane izkušnje, ki jih neposredno ponuja Microsoft uporabnikom in jih ureja [pogodba o Microsoftovih storitvah](https://www.microsoft.com/servicesagreement) in ne [pogoji spletnih storitev](https://www.microsoft.com/licensing/product-licensing/products).

Ker te izbirne povezane izkušnje urejajo ločeni pogoji in določila, jih lahko upravljate ločeno od povezanih izkušenj, opredeljenih v tem članku. Kot skrbnik organizacije lahko z nastavitvijo pravilnika določite, ali so te izbirne povezane izkušnje vašim uporabnikom na voljo kot skupina. Če ne konfigurirate te nastavitve pravilnika, so te izbirne povezane izkušnje na voljo vašim uporabnikom.

Tudi če se odločite, da bodo te izbirne povezane izkušnje na voljo vašim uporabnikom, jih lahko ti izklopijo kot skupino tako, da odprejo [pogovorno okno z nastavitvami zasebnosti](https://support.office.com/article/3e7bc183-bf52-4fd0-8e6b-78978f7f121b). Vašim uporabnikom je ta izbira na voljo samo, če so vpisani v Office s svojimi poverilnicami organizacije (včasih jih imenujemo tudi službeni ali šolski račun), ne pa če so vpisani z osebnim e-poštnim naslovom.

Če želite več informacij, preberite te članke:

- [Pregled izbirnih povezanih izkušenj v Officeu](optional-connected-experiences.md).
- [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office365 ProPlus](manage-privacy-controls.md)
- [Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office za Mac](mac-privacy-preferences.md)
- [Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom iOS](ios-privacy-preferences.md)

## <a name="required-service-data-for-connected-experiences"></a>Zahtevani podatki storitev za povezane izkušnje

Zahtevani podatki storitev so podatki, s katerimi lahko omogočamo povezane izkušnje v oblaku in izboljšamo varnost ter pričakovano delovanje teh izkušenj. Zahtevani podatki storitev vključujejo tri vrste informacij.

- **Vsebina stranke** predstavlja vsebino, ki jo ustvarite v Officeu, na primer besedilo, ki ste ga vnesli v Wordov dokument.
- **Funkcijski podatki** vključujejo informacije, ki jih zahteva povezana izkušnja za izvedbo opravila, kot so informacije o konfiguraciji aplikacije.
- **Diagnostični podatki storitev** so podatki, zahtevani za zagotavljanje varnosti, posodobitev in pričakovanega delovanja storitve. Ker so ti podatki v glavnem povezani s povezano izkušnjo, tvorijo ločeno raven od zahtevanih oziroma izbirnih diagnostičnih podatkov.

V nadaljevanju si oglejte vzorčni primer uporabe oblikovalnika za PowerPoint – povezano izkušnjo, ki jo lahko uporabite pri ustvarjanju diapozitivov za predstavitev. Tako boste bolje spoznali zahtevane podatke storitev. Oblikovalnik za PowerPoint izboljša vaše diapozitive tako, da samodejno ustvari ideje za načrt ideje, med katerimi lahko izbirate. Oblikovalnik med dodajanjem vsebine na diapozitiv deluje v ozadju in poišče ustrezno vsebino za strokovno oblikovano postavitev.

Zahtevani podatki storitev, poslani Microsoftu, da vam omogoči to povezano izkušnjo, lahko vključujejo:

- *Vsebino stranke*, kot so besedilo in slike, ki ste jih dodali v diapozitive.
- *Funkcijske podatke*, na primer, kateri diapozitiv urejajte in postavitev diapozitiva.
- *Diagnostične podatke storitev*, kot so dogodki, iz katerih je razvidno, ali je bila idejna zasnova pravilno uporabljena v vašem diapozitivu in ali so bili klici storitve izvedeni pravilno.

Če se odločite, da uporabnikom ne boste omogočili kategorije povezanih izkušenj, ki vključujejo oblikovalnik za PowerPoint, bo ta funkcija izklopljena, mi pa ne bomo prejeli nobenih zahtevanih podatkov storitev.

Če želite več informacij, preberite [Zahtevani podatki storitev za Office](required-service-data.md).

## <a name="essential-services-for-office-365-proplus"></a>Osnovne storitve Office 365 ProPlus

Obstaja tudi nabor osnovnih storitev za delovanje storitve Office 365 ProPlus, ki jih ni mogoče onemogočiti. Na primer storitev licenciranja, s katero potrdite, da imate ustrezno licenco za uporabo storitve Office 365 ProPlus. Zahtevani podatki o teh storitvah so zbrani in poslani Microsoftu, ne glede na to, ali imate konfigurirane druge nastavitve pravilnika.

Če želite več informacij, preberite [Ključne storitve za Office](essential-services.md).

## <a name="related-topics"></a>Sorodne teme
- [Zasebnost pri Microsoftu](https://privacy.microsoft.com/)
- [Zasebnost v sistemu Windows](https://docs.microsoft.com/windows/privacy/)
