---
title: Izbirni diagnostični podatki za Office
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
description: Skrbniki za Office dobijo informacije o izbirnih diagnostičnih podatkih v Officeu, vključno z nekaterimi primeri dogodkov.
hideEdit: true
ms.openlocfilehash: 0190c29a017b35d945e6a1d540e1560dfab47a4c
ms.sourcegitcommit: 3890a23390edd0b5fdb2cf33613ec0778566cf97
ms.translationtype: HT
ms.contentlocale: sl-SI
ms.lasthandoff: 05/01/2020
ms.locfileid: "43993162"
---
# <a name="optional-diagnostic-data-for-office"></a>Izbirni diagnostični podatki za Office

> [!IMPORTANT]
> Informacije v tem članku veljajo za različico 1904 ali novejšo različico sledeče Officeove odjemalske programske opreme, ki je nameščena v računalniku s sistemom Windows:
> - Microsoft 365 aplikacije za velika podjetja (prej imenovan Office 365 ProPlus)
> - Microsoft 365 aplikacije za podjetja (prej imenovan Office 365 Business)
> - Microsoft 365 Personal, Microsoft 365 Family ali druge Officeove različice, ki so del naročnine na Microsoft 365.
> - Project in Visiove namizne aplikacije, ki so priložene nekaterim naročniškim paketom, kot je Project plan 5 ali Visio (paket 2).
>
> Informacije veljajo tudi za različico 16.28 ali novejšo od teh aplikacij sistema Office za Mac: Excel, Outlook, OneNote, PowerPoint in Word.

Diagnostični podatki so uporabljeni za zaščito, posodobitev ter zaznavanje in odpravljanje težav v Officeu, poleg tega pa tudi za izboljšanje izdelka. Ti podatki ne vključujejo uporabniškega imena ali e-poštnega naslova, vsebine datotek uporabnika ali informacij o aplikacijah, ki niso del Officea.

Diagnostični podatki o uporabljeni programski opremi odjemalca za Office v računalnikih z nameščenim sistemom Windows so bili zbrani in poslani Microsoftu. Nekateri diagnostični podatki so obvezni, medtem ko so drugi izbirni. S kontrolniki zasebnosti lahko izbirate, ali nam boste poslali zahtevane ali izbirne diagnostične podatke, kot so na primer nastavitve pravilnikov za organizacijo. S Pregledovalnikom diagnostičnih podatkov lahko vidite, kateri diagnostični podatki so nam poslani.

***Izbirni diagnostični podatki*** – dodatni podatki, ki omogočajo izboljšave izdelkov ter nudijo izčrpne informacije za zaznavanje, diagnosticiranje in odpravljanje težav.

Če se odločite, da nam boste poslali izbirne diagnostične podatke, nam boste prav tako poslali še zahtevane diagnostične podatke.

Med izbirne diagnostične podatke sodijo podatki, ki jih zberemo o oblikah, ki jih uporabniki vstavijo v Wordove dokumente. Na podlagi pridobljenih podatkov lahko nato ponudimo boljše možnosti. Zbiramo na primer tudi podatke o tem, koliko časa preteče, preden je na zaslonu prikazan PowerPointov diapozitiv. Na podlagi teh podatkov lahko izboljšamo izkušnjo, če deluje počasi.

Če želite izvedeti več informacij o diagnostičnih podatkih, preberite te članke:

- [Zahtevani diagnostični podatki za Office](required-diagnostic-data.md)
- [Uporaba pregledovalnika diagnostičnih podatkov z Officeom](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

Če ste skrbnik v svoji organizaciji, vas bo morda zanimalo to:

- [Pregled kontrolnikov za zasebnost za Microsoft 365 aplikacije za podjetja](overview-privacy-controls.md)
- [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Microsoft 365 aplikacije za podjetja](manage-privacy-controls.md)
- [Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office za Mac](mac-privacy-preferences.md)
- [Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom iOS](ios-privacy-preferences.md)
- [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom Android](android-privacy-controls.md)

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
| Office.Extensibility.AppCommands.GetRibbonUpdatesForUserId | Ta dogodek označuje, ali Word uspešno posodobi trak v Wordovem uporabniškem vmesniku, ko uporabnik spremeni svojo identiteto. S tem dogodkom zaznamo napačne nastavitve in druge težave, ki lahko vplivajo na Officeov uporabniški vmesnik. |
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
| Office.Graphics.GVizInsertShape |Spremlja uporabo funkcije »Vstavi obliko« v Wordu, poleg tega pa poroča podrobnosti o vrstah oblik, ki so vstavljene, in iz katerega vira so pridobljene.| 
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
| Office.Word.Word.CoreSaveTime100ns     | Ta dogodek zabeleži podatke o učinkovitosti dejanja shranjevanja dokumenta v Wordu. S tem dogodkom zaznamo napake in težave z učinkovitostjo delovanja v dejavnosti shranjevanja dokumenta v Wordu.|
| Office.Identity.SignInForWamAccountAad  | Ta dogodek je poslan, ko je uporabnik vpisan v račun storitve Azure Active Directory s knjižnico Web Account Manager (WAM). Ta dogodek pošlje metapodatke, kot so ime aplikacije, različica aplikacije in koda napake, če dogodek ni uspel. |
| Office.PowerPoint.PPT.Desktop.FileOpen.FirstSlideMasterThumbnailRenderTime | Ta dogodek zbere podatke o času, potrebnem za upodobitev prve sličice matrice v PowerPointu.  |
| Office.Extensibility.Diagnostics   | Ta dogodek nudi splošne diagnostične informacije za Officeove dodatke, kot so poročila o zrušitvi, za odpravljanje napak.|

## <a name="device-connectivity-and-configuration-events"></a>Dogodki povezljivosti in konfiguracije naprave

V to kategorijo sodijo dogodki, ki lahko vključujejo ta področja:

- Stanje omrežne povezave in nastavitve naprave, kot je pomnilnik.

V tej tabeli so primeri dogodkov v tej kategoriji ter opis teh dogodkov.

| **Ime dogodka**                    | **Opis dogodka**                                                                                                                                                     |
| ------ | ----- |
| Office.Graphics.ArtViewValidate | Ta dogodek zabeleži preverjanje rezultatov pogleda grafike, ki podpira uporabniški vmesnik grafike. Z dogodkom zberemo podatke o uporabi in napakah pri upodabljanju grafike. |
| Office.Graphics.ARCExceptionScope | Ta dogodek spremlja napake upodabljanja, ki prihajajo iz mehanizma za upodabljanje. |
| Office.Extensibility.ODPLatency   | Ta dogodek nudi informacije o povezavi in hitrosti uporabnikovega omrežja.     |
