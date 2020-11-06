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
ms.openlocfilehash: 7dc10c50baed0306e3e7fc6dd70e0d798a72d0bc
ms.sourcegitcommit: e64b8f2b7f92a3972d8dc83f47d84648fbe17370
ms.translationtype: HT
ms.contentlocale: sl-SI
ms.lasthandoff: 11/06/2020
ms.locfileid: "48931270"
---
# <a name="optional-diagnostic-data-for-office"></a>Izbirni diagnostični podatki za Office

> [!NOTE]
> Če si želite ogledati seznam Officeovih izdelkov, ki so zajeti v teh informacijah o zasebnosti, glejte [Kontrolnike zasebnosti, ki so na voljo za Officeove izdelke](products-versions-privacy-controls.md).

Diagnostični podatki so uporabljeni za zaščito, posodobitev ter zaznavanje in odpravljanje težav v Officeu, poleg tega pa tudi za izboljšanje izdelka. Ti podatki ne vključujejo uporabniškega imena ali e-poštnega naslova, vsebine datotek uporabnika ali informacij o aplikacijah, ki niso del Officea.

Ti diagnostični podatki so zbrani in poslani Microsoftu. V njih so podatki o odjemalski programski opremi za Office v napravi uporabnika. Nekateri diagnostični podatki so obvezni, medtem ko so drugi izbirni. S kontrolniki zasebnosti lahko izbirate, ali nam boste poslali zahtevane ali izbirne diagnostične podatke, kot so na primer nastavitve pravilnikov za organizacijo. S Pregledovalnikom diagnostičnih podatkov lahko vidite, kateri diagnostični podatki so nam poslani.

> [!NOTE]
> Če uporabljate različico sistema Office 2019 ali Office 2016, ki vam ali vašemu skrbniku ne omogoča možnosti izbire pošiljanja izbirnih ali obveznih diagnostičnih podatkov, so poslani le obvezni diagnostični podatki. Če na primer uporabljate Office Professional Plus 2019 ali Office Standard 2016, kjer ni na voljo ta možnost izbire, so poslani le obvezni diagnostični podatki. Office 2013 ne pošilja obveznih ali izbirnih diagnostičnih podatkov. Več informacij o tem, v katerih različicah Officea je na voljo ta možnost izbite preberite v razdelku [Kontrolniki zasebnosti, ki so na voljo za Officeove izdelke](products-versions-privacy-controls.md).

***Izbirni diagnostični podatki** – dodatni podatki, ki omogočajo izboljšave izdelkov ter nudijo izčrpne informacije za zaznavanje, diagnosticiranje in odpravljanje težav.

Če se odločite, da nam boste poslali izbirne diagnostične podatke, nam boste prav tako poslali še zahtevane diagnostične podatke. Prav tako lahko pošljete datoteke diagnostičnega dnevnika za Office, ki vsebujejo informacije, zelo podobne izbirnim diagnostičnim podatkom. Če želite več informacij o teh dnevniških datotekah, si oglejte [Pregled datotek diagnostičnega dnevnika za Office](https://support.microsoft.com/office/fba86aac-70dc-4858-ae1f-ec2034346cdf).

Med izbirne diagnostične podatke sodijo podatki, ki jih zberemo o oblikah, ki jih uporabniki vstavijo v Wordove dokumente. Na podlagi pridobljenih podatkov lahko nato ponudimo boljše možnosti. Zbiramo na primer tudi podatke o tem, koliko časa preteče, preden je na zaslonu prikazan PowerPointov diapozitiv. Na podlagi teh podatkov lahko izboljšamo izkušnjo, če deluje počasi.

Več informacij o diagnostičnih podatkih najdete v teh člankih:

- [Zahtevani diagnostični podatki za Office](required-diagnostic-data.md)
- [Uporaba pregledovalnika diagnostičnih podatkov z Officeom](https://support.microsoft.com/office/cf761ce9-d805-4c60-a339-4e07f3182855)

Če ste skrbnik za svojo organizacijo, vas bo morda zanimal tudi za te članke:

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

| _ *Ime dogodka**   | **Opis dogodka**  |
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
