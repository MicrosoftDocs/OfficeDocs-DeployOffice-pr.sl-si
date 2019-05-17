---
title: Izbirni diagnostični podatki za Office
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Skrbniki za Office dobijo informacije o izbirnih diagnostičnih podatkih v Officeu, vključno z nekaterimi primeri dogodkov.
hideEdit: true
ms.openlocfilehash: 1df576e8f5f1b3ed9fff11651ff4dd2b28d47229
ms.sourcegitcommit: b3fd057154853fc588d0e83b4d632b6e9a051a3c
ms.translationtype: HT
ms.contentlocale: sl-SI
ms.lasthandoff: 04/23/2019
ms.locfileid: "32435875"
---
# <a name="optional-diagnostic-data-for-office"></a>Izbirni diagnostični podatki za Office

> [!IMPORTANT]
> Informacije v tem članku veljajo za različico 1904 ali novejšo različico sledeče Officeove odjemalske programske opreme, ki je nameščena v računalniku s sistemom Windows:
> - Office 365 ProPlus in Office 365 Business
> - Office 365 Personal, Office 365 Home ali druge različice Officea, ki so del naročnine na Office 365.
> - Project in Visio, ki sta vključena v nekatere naročniške pakete, kot sta paketa Project Online Professional ali Visio Online 2.

Diagnostični podatki so uporabljeni za zaščito, posodobitev ter zaznavanje in odpravljanje težav v Officeu, poleg tega pa tudi za izboljšanje izdelka. Ti podatki ne vključujejo uporabniškega imena ali e-poštnega naslova, vsebine datotek uporabnika ali informacij o aplikacijah, ki niso del Officea.

Diagnostični podatki o uporabljeni programski opremi odjemalca za Office v računalnikih z nameščenim sistemom Windows so bili zbrani in poslani Microsoftu. Nekateri diagnostični podatki so obvezni, medtem ko so drugi izbirni. S kontrolniki zasebnosti lahko izbirate, ali nam boste poslali zahtevane ali izbirne diagnostične podatke, kot so na primer nastavitve pravilnikov za organizacijo. S Pregledovalnikom diagnostičnih podatkov lahko vidite, kateri diagnostični podatki so nam poslani.

***Izbirni diagnostični podatki*** – dodatni podatki, ki omogočajo izboljšave izdelkov ter nudijo izčrpne informacije za zaznavanje, diagnosticiranje in odpravljanje težav.

Če se odločite, da nam boste poslali izbirne diagnostične podatke, nam boste prav tako poslali še zahtevane diagnostične podatke.

Med izbirne diagnostične podatke sodijo podatki, ki jih zberemo o slikah, ki jih uporabniki vstavijo v Wordove dokumente. Na podlagi pridobljenih podatkov lahko nato ponudimo boljše možnosti za slike. Zbiramo na primer tudi podatke o tem, koliko časa preteče, preden je na zaslonu prikazan PowerPointov diapozitiv. Na podlagi teh podatkov lahko izboljšamo izkušnjo, če deluje počasi.

Če želite izvedeti več informacij o diagnostičnih podatkih, preberite naslednje članke:

- [Zahtevani diagnostični podatki za Office](required-diagnostic-data.md)
- [Uporaba pregledovalnika diagnostičnih podatkov z Officeom](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

Če ste skrbnik v svoji organizaciji, vas bo morda zanimalo to:

- [Pregled kontrolnikov zasebnosti za Office 365 ProPlus](overview-privacy-controls.md)
- [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office365 ProPlus](manage-privacy-controls.md)

## <a name="categories-of-optional-diagnostic-data"></a>Kategorije izbirnih diagnostičnih podatkov

Izbirni diagnostični podatki so organizirani v te kategorije:

- Inventar in nastavitev programske opreme
- Uporaba izdelka in storitev
- Učinkovitost delovanja izdelka in storitve
- Povezljivost in konfiguracija naprave

Te kategorije so prikazane v Pregledovalniku diagnostičnih podatkov in so iste kategorije, uporabljene za zahtevane diagnostične podatke.

V teh razdelkih so opis posamezne kategorije in primeri dogodkov za vsako kategorijo.

## <a name="software-setup-and-inventory-events"></a>Dogodki inventarja in nastavitve programske opreme

V to kategorijo sodijo dogodki, ki lahko vključujejo ta področja:

- Nameščeni izdelek, različica in stanje namestitve
- Dodatek programske opreme in nastavitve.
- Dokument, funkcija in pogoji napake dodatka, ki lahko ogrozijo varnost, vključno s pripravljenostjo izdelka na posodobitve.

V tej tabeli so primeri dogodkov v tej kategoriji ter opis teh dogodkov.

| **Ime dogodka**   | **Opis dogodka**  |
| ---- | ---- |
| Office\_Extensibility\_AppCommands\_GetRibbonUpdatesForUserId | Ta dogodek označuje, ali Word uspešno posodobi trak v Wordovem uporabniškem vmesniku, ko uporabnik spremeni svojo identiteto. S tem dogodkom zaznamo napačne nastavitve in druge težave, ki lahko vplivajo na Officeov uporabniški vmesnik. |
| Office.Extensibility.AppCommands.AppCmdInstall   | V tem dogodku so informacije o Officeovem dodatku, ki ga je uporabnik namestil, vključno z ID-jem aplikacije, graditvijo in različico operacijskega sistema, uspehom namestitve ter trajanjem namestitve.  |

## <a name="product-and-service-usage-events"></a>Dogodki uporabe izdelka in storitve

V to kategorijo sodijo dogodki, ki lahko vključujejo ta področja:

- Uspešnost delovanja aplikacije. Omejeno na odpiranje in zapiranje aplikacije in dokumentov, urejanje datoteke ter skupna raba datoteke (sodelovanje).
- Določanje, ali je prišlo do specifičnih dogodkov funkcije, kot sta zagon ali zaustavitev, in funkcije, ki se izvaja.
- Officeove funkcije dostopnosti

V tej tabeli so primeri dogodkov v tej kategoriji ter opis teh dogodkov.

| **Ime dogodka**   | **Opis dogodka**  |
| ------ | ------- |
| Office.Word.Commanding.Highlight  | Ta dogodek označuje, ali je Word izvedel ukaz za označevanje besedila. S tem dogodkom zaznamo napake v ukazu za označevanje besedila.  |
| Office.Translator.AddInLoaded   | Signal obveščanja o izvajanju programa, ki označuje, da je bila funkcija prevajalca uspešno naložena in upodobljena.  |
| Office.Graphics.InsertPictureCommandActivity  | Spremlja uspešnost ali neuspešnost delovanja funkcije »Vstavi sliko«, poleg tega pa poroča podrobnosti o vrstah slik, ki so vstavljene, in iz katerega vira so pridobljene.|
| Office.PowerPoint.PPT.Desktop.SummaryZoomInsertionRule   | Ta element določa, ali so v dokumentu razdelki, ko uporabnik vstavlja zumiranje povzetka, in ali uporabnik izbriše obstoječe razdelke. |
| Office.Security.SecureReaderHost.ProtectedViewValidation | Spremlja, kdaj in zakaj je datoteka odprta v zaščitenem pogledu. Uporabljeno za diagnosticiranje pogojev, zaradi katerih zaščiteni pogled morda ni pravilno sprožen. Na ta način je zagotovljeno pravilno delovanje funkcije. |

## <a name="product-and-service-performance-events"></a>Dogodki delovanja izdelka in storitve

V to kategorijo sodijo dogodki, ki lahko vključujejo ta področja:

- Obstaja nepričakovana aplikacija (se zruši) in stanje te aplikacije, ko pride do tega.
- Slab odzivni čas ali slaba učinkovitost za scenarije, kot sta zagon aplikacije ali odpiranje datoteke.
- Napake v delovanju funkcije ali uporabniške izkušnje.

V tej tabeli so primeri dogodkov v tej kategoriji ter opis teh dogodkov.

| **Ime dogodka**    | **Opis dogodka**   |
| --------------- | -------------- |
| Office\_Word\_Word\_CoreSaveTime100ns     | Ta dogodek zabeleži podatke o učinkovitosti dejanja shranjevanja dokumenta v Wordu. S tem dogodkom zaznamo napake in težave z učinkovitostjo delovanja v dejavnosti shranjevanja dokumenta v Wordu.|
| Office.Identity.SignInForWamAccountAad  | Ta dogodek je poslan, ko je uporabnik vpisan v račun storitve Azure Active Directory s knjižnico Web Account Manager (WAM). Ta dogodek pošlje metapodatke, kot so ime aplikacije, različica aplikacije in koda napake, če dogodek ni uspel. |
| Office.PowerPoint.PPT.Desktop.FileOpen.FirstSlideMasterThumbnailRenderTime | Ta dogodek zbere podatke o času, potrebnem za upodobitev prve sličice matrice v PowerPointu.  |
| Office.Extensibility.Diagnostics   | Ta dogodek nudi splošne diagnostične informacije za Officeove dodatke, kot so poročila o zrušitvi, za odpravljanje napak.|

## <a name="device-connectivity-and-configuration-events"></a>Dogodki povezljivosti in konfiguracije naprave

V to kategorijo sodijo dogodki, ki lahko vključujejo ta področja:

- Stanje omrežne povezave in nastavitve naprave, kot je pomnilnik.

V tej tabeli so primeri dogodkov v tej kategoriji ter opis teh dogodkov.

| **Ime dogodka**                    | **Opis dogodka**                                                                                                                                                     |
| ------ | ----- |
| Office\_Graphics\_ArtViewValidate | Ta dogodek zabeleži preverjanje rezultatov pogleda grafike, ki podpira uporabniški vmesnik grafike. Z dogodkom zberemo podatke o uporabi in napakah pri upodabljanju grafike. |
| Office.Graphics.ARCExceptionScope | Ta dogodek spremlja napake upodabljanja, ki prihajajo iz mehanizma za upodabljanje. |
| Office.Extensibility.ODPLatency   | Ta dogodek nudi informacije o povezavi in hitrosti uporabnikovega omrežja.     |
