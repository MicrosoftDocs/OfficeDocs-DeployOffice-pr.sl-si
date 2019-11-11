---
title: Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom iOS
ms.author: danbrown
author: pbowden-msft
manager: laurawi
audience: ITPro
ms.topic: article
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
- Ent_Office_Mac
description: Officeovim skrbnikom nudi informacije o načinu upravljanja nastavitev zasebnosti v napravah s sistemom iOS.
hideEdit: true
ms.openlocfilehash: d1a14d2e1bfe45710255467fcbce9ac4af2c9cb7
ms.sourcegitcommit: 903d6bac7d8b7d8003863ac778c0b5bbdfa7a62a
ms.translationtype: HT
ms.contentlocale: sl-SI
ms.lasthandoff: 10/21/2019
ms.locfileid: "37604299"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a>Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom iOS

Na voljo so nove prednostne nastavitve za Office v napravah s sistemom iOS, s katerimi lahko nadzorujete nastavitve, povezane z naslednjo vsebino:

- ***Diagnostični podatki*** o uporabljeni programski opremi odjemalca za Office, ki jih je sistem zbral in poslal Microsoftu.

- ***Povezane izkušnje***, ki za omogočanje razširjenih Officeovih funkcij uporabljajo storitve v oblaku.

Če želite več informacij o diagnostičnih podatkih in povezanih izkušnjah, preberite članek [Pregled kontrolnikov zasebnosti](overview-privacy-controls.md).

Te prednostne nastavitve se nanašajo na naslednje aplikacije:
- Različica 2.30 in poznejše različice programov Word za iOS, Excel za iOS in PowerPoint za iOS.
- Različica 16.30 in novejša različica programa OneNote za iOS.
- Različica 1.17 in novejša različica programa Visio Viewer za iOS.

> [!NOTE]
> Če želite več informacij o podobnih nastavitvah za Office v računalnikih s sistemom macOS, preberite članek [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office for Mac](mac-privacy-preferences.md)


## <a name="setting-device-preferences"></a>Nastavljanje nastavitev naprave
Te nove prednostne nastavitve lahko nastavite tudi na ravni naprave s strežnikom Upravljanje mobilnih naprav (MDM), ko je nameščena Officeova aplikacija. Mnogi strežniki MDM skrbnikom za IT omogočajo, da dodajo izbirni konfiguracijski slovar, ko strežnik pošlje `InstallApplication` ukaz MDM v napravo s sistemom iOS. Če želite več informacij, si oglejte dokumentacijo strežnika MDM.

Slovar je predstavljen kot nabor parov ključev/vrednosti v obliki zapisa datoteke XML. Na primer:

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

Ko ga pošljete napravi, bo konfiguracijski slovar shranjen pod `com.apple.managed.configuration` ključem, kjer bo prebran ob zagonu Officeove aplikacije.

## <a name="preference-setting-for-diagnostic-data"></a>Prednostna nastavitev za diagnostične podatke

Diagnostični podatki se uporabljajo za zaščito, posodobitev, zaznavanje težav in njihovo odpravljanje v Officeu ter za izboljšave izdelka. Če želite več informacij, preberite članek [Diagnostični podatki, poslani Microsoftu iz storitve Office 365 ProPlus](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).

|||
|:-----|:-----|
|**Ključ**  | `DiagnosticDataTypePreference`  |
|**Vrsta podatkov**  | Niz |
|**Možne vrednosti**  | `BasicDiagnosticData` *(s tem nastavite raven na možnost »Zahtevana«)* <br/> `FullDiagnosticData` *(s tem nastavite raven na možnost »Izbirna«)* <br/> `ZeroDiagnosticData` *(s tem nastavite raven na možnost »Nobena«)* |

Če te prednostne nastavitve ne nastavite, se Microsoftu pošljejo le zahtevani diagnostični podatki, če so uporabniki z naročnino na Office 365 prijavljeni z delovnim ali šolskim računom. Ti uporabniki ne morejo spremeniti ravni diagnostičnih podatkov, in sicer ne glede na to, kako nastavite to prednostno nastavitev.

V primeru drugih uporabnikov, kot so domači uporabniki z naročnino na Office 365, Microsoft prejema samo zahtevane diagnostične podatke, razen če uporabnik v možnosti **Nastavitve** > **Zasebnost** izbere, da so poslani tudi izbirni diagnostični podatki.


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a>Prednostna nastavitev za povezane izkušnje, ki analizirajo vašo vsebino

Povezane Izkušnje, ki analizirajo vašo vsebino so izkušnje, ki na podlagi Officeove vsebine nudijo priporočila za načrte, predloge za urejanje, vpoglede v podatke in podobne funkcije. Na primer »Ideje za oblikovanje« v PowerPointu. Če si želite ogledati seznam povezanih izkušenj, glejte [Povezane izkušnje v Officeu](connected-experiences.md).

|||
|:-----|:-----|
|**Ključ**  | `OfficeExperiencesAnalyzingContentPreference`  |
|**Vrsta podatkov**  | Logični |
|**Možne vrednosti**  | `TRUE` *(omogočeno)* <br/> `FALSE` *(onemogočeno)*|


Če te prednostne nastavitve ne nastavite, so povezane izkušnje, ki analizirajo vsebino, na voljo za uporabnike.

Če ima uporabnik naročnino na Office 365 in je vpisan s službenim ali šolskim računom, ne more izklopiti povezanih izkušenj, ki analizirajo vsebino.

Drugi uporabniki, kot so domači uporabniki z naročnino na Office 365, lahko v možnosti **Nastavitve** > **Zasebnost** izklopijo povezane izkušnje, ki analizirajo vsebino.

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a>Prednostna nastavitev za povezane izkušnje, s katerimi prenesete spletno vsebino

Povezane izkušnje, s katerimi prenesete spletno vsebino, so izkušnje, ki vam omogočajo, da poiščete in prenesete spletno vsebino, vključno s predlogami, slikami, videoposnetki in referenčnim gradivom, s katero izpopolnite svoje dokumente. Na primer, Officeove predloge ali vstavljanje spletne ikone. Če si želite ogledati seznam povezanih izkušenj, glejte [Povezane izkušnje v Officeu](connected-experiences.md).

|||
|:-----|:-----|
|**Ključ**  | `OfficeExperiencesDownloadingContentPreference`  |
|**Vrsta podatkov**  | Logični |
|**Možne vrednosti**  | `TRUE` *(omogočeno)* <br/> `FALSE` *(onemogočeno)*|


Če te prednostne nastavitve ne nastavite, so povezane izkušnje, s katerimi prenesete spletno vsebino, na voljo uporabnikom.

Če ima uporabnik naročnino na Office 365 in je vpisan s službenim ali šolskim računom, ne more izklopiti povezanih izkušenj, s katerimi prenesejo spletno vsebino.

Drugi uporabniki, kot so domači uporabniki z naročnino na Office 365, lahko v možnosti **Nastavitve** > **Zasebnost** izklopijo povezane izkušnje, s katerimi prenesejo spletno vsebino.

## <a name="preference-setting-for-optional-connected-experiences"></a>Prednostna nastavitev za izbirne povezane izkušnje

Poleg povezanih izkušenj, omenjenih v tem članku, lahko izbirate še med dodatnimi izbirnimi povezanimi izkušnjami, s katerimi lahko vaši uporabniki dostopajo do svojih računov organizacije, imenovanih tudi službeni ali šolski računi. Na primer, dodatki za Office, ki so preneseni prek Trgovine Office v napravo. Če si želite ogledati več primerov, preberite [Pregled izbirnih povezanih izkušenj v Officeu](optional-connected-experiences.md).

|||
|:-----|:-----|
|**Ključ**  | `OptionalConnectedExperiencesPreference`  |
|**Vrsta podatkov**  | Logični |
|**Možne vrednosti**  | `TRUE` *(omogočeno)* <br/> `FALSE` *(onemogočeno)*|


Če te prednostne nastavitve ne nastavite, so izbirne povezane izkušnje na voljo uporabnikom z naročnino na Office 365, ki so vpisani s službenim ali šolskim računom. Če te prednostne nastavitve ne nastavite na NAPAČNO, lahko ti uporabniki v možnosti **Nastavitve** > **Nastavitve zasebnosti** izklopijo izbirne povezane izkušnje.

Drugi uporabniki, kot so domači uporabniki z naročnino na Office 365, ne morejo izklopiti izbirnih povezanih izkušenj.