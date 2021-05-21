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
ms.openlocfilehash: 000fd2c5e13ed51abf3afba6e7a1433c9d4b912f
ms.sourcegitcommit: 9b5f18c543c286c95e546e22fc8edb60ef541030
ms.translationtype: HT
ms.contentlocale: sl-SI
ms.lasthandoff: 05/20/2021
ms.locfileid: "52578352"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a>Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom iOS

> [!NOTE]
> Če si želite ogledati seznam Officeovih izdelkov, ki so zajeti v teh informacijah o zasebnosti, glejte [Kontrolnike zasebnosti, ki so na voljo za Officeove izdelke](products-versions-privacy-controls.md).

Na voljo so nove prednostne nastavitve za Office v napravah s sistemom iOS, s katerimi lahko nadzorujete nastavitve, povezane z naslednjo vsebino:

- ***Diagnostični podatki*** o uporabljeni programski opremi odjemalca za Office, ki jih je sistem zbral in poslal Microsoftu.

- ***Povezane izkušnje***, ki za omogočanje razširjenih Officeovih funkcij uporabljajo storitve v oblaku.

Če želite več informacij o diagnostičnih podatkih in povezanih izkušnjah, preberite članek [Pregled kontrolnikov zasebnosti](overview-privacy-controls.md).

> [!NOTE]
> Če želite več informacij o podobnih nastavitvah za Office v računalnikih s sistemom macOS, preberite članek [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office for Mac](mac-privacy-preferences.md)


## <a name="setting-device-preferences"></a>Nastavljanje nastavitev naprave
Te nove prednostne nastavitve lahko nastavite tudi na ravni naprave s strežnikom Upravljanje mobilnih naprav (MDM), ko je nameščena Officeova aplikacija. Mnogi strežniki MDM skrbnikom za IT omogočajo, da dodajo izbirni konfiguracijski slovar, ko strežnik pošlje `InstallApplication` ukaz MDM v napravo s sistemom iOS. Če želite več informacij, si oglejte dokumentacijo strežnika MDM.

Slovar je predstavljen kot nabor parov ključev/vrednosti v obliki zapisa datoteke XML.

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

Ko ga pošljete napravi, bo konfiguracijski slovar shranjen pod `com.apple.managed.configuration` ključem, kjer bo prebran ob zagonu Officeove aplikacije.

> [!NOTE]
> Uporabite lahko tudi storitev pravilnika za Office Cloud in te nastavitve za 4 pravilnikov:
> - Konfiguracija ravni diagnostičnih podatkov o programski opremi odjemalca, ki jih Office pošlje Microsoftu
> - Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko analizirate vsebino
> - Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko prenašate spletno vsebino
> - Omogočanje uporabe dodatnih povezanih izkušenj v Officeu
>
> Nastavitve zasebnosti za Outlook za iOS in OneDrive za iOS lahko konfigurirate le s storitvijo Office politiko oblaka.
>
> Če želite več informacij o uporabi storitve pravilnika Office Cloud, si oglejte [pregled storitve pravilnika Office Cloud ](../overview-office-cloud-policy-service.md).

## <a name="preference-setting-for-diagnostic-data"></a>Prednostna nastavitev za diagnostične podatke

Diagnostični podatki se uporabljajo za zaščito, posodobitev, zaznavanje težav in njihovo odpravljanje v Officeu ter za izboljšave izdelka. Če želite več informacij, si oglejte [diagnostičnih podatkov, ki so bili poslani iz aplikacij Microsoft 365 za podjetja v Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).

|Kategorija|Podrobnosti|
|:-----|:-----|
|**Ključ**  | `DiagnosticDataTypePreference`  |
|**Vrsta podatkov**  | Niz |
|**Možne vrednosti**  | `BasicDiagnosticData` *(ta vrednost nastavi raven na »Zahtevano«)* <br/> `FullDiagnosticData` *(ta vrednost nastavi raven na »Izbirno«)* <br/> `ZeroDiagnosticData` *(Ta vrednost nastavi raven na »Nič«)* |

Če te prednostne nastavitve ne nastavite, se Microsoftu pošljejo le zahtevani in izbirni diagnostični podatki, če so uporabniki z naročnino na Office 365 (ali Microsoft 365) prijavljeni z delovnim ali šolskim računom. Ti uporabniki ne morejo spremeniti ravni diagnostičnih podatkov, in sicer ne glede na to, kako nastavite to prednostno nastavitev.

> [!NOTE]
> Prejšnji odstavek smo posodobili. Tako smo natančneje pojasnili, da so izbirni diagnostični podatki Microsoftu poslani, tudi če ne izberete te nastavitve.

V primeru drugih uporabnikov, kot so domači uporabniki z naročnino na Office 365 (ali Microsoft 365), Microsoft prejema samo zahtevane diagnostične podatke, razen če uporabnik v možnosti **Nastavitve** > **Zasebnost** izbere, da so poslani tudi izbirni diagnostični podatki.


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a>Prednostna nastavitev za povezane izkušnje, ki analizirajo vašo vsebino

Povezane Izkušnje, ki analizirajo vašo vsebino so izkušnje, ki na podlagi Officeove vsebine nudijo priporočila za načrte, predloge za urejanje, vpoglede v podatke in podobne funkcije. Na primer »Ideje za oblikovanje« v PowerPointu. Če si želite ogledati seznam povezanih izkušenj, glejte [Povezane izkušnje v Officeu](connected-experiences.md).

|Kategorija|Podrobnosti|
|:-----|:-----|
|**Ključ**  | `OfficeExperiencesAnalyzingContentPreference`  |
|**Vrsta podatkov**  | Logični |
|**Možne vrednosti**  | `TRUE` *(omogočeno)* <br/> `FALSE` *(onemogočeno)*|


Če te prednostne nastavitve ne nastavite, so povezane izkušnje, ki analizirajo vsebino, na voljo za uporabnike.

Če ima uporabnik naročnino na Office 365 (ali Microsoft 365) in je vpisan s službenim ali šolskim računom, ne more izklopiti povezanih izkušenj, ki analizirajo vsebino.

Drugi uporabniki, kot so domači uporabniki z naročnino na Office 365 (ali Microsoft 365), lahko v možnosti **Nastavitve** > **Nastavitve zasebnosti** izklopijo povezane izkušnje, ki analizirajo vsebino.

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a>Prednostna nastavitev za povezane izkušnje, s katerimi prenesete spletno vsebino

Povezane izkušnje, s katerimi prenesete spletno vsebino, so izkušnje, ki vam omogočajo, da poiščete in prenesete spletno vsebino, vključno s predlogami, slikami, videoposnetki in referenčnim gradivom, s katero izpopolnite svoje dokumente. Na primer, Officeove predloge ali vstavljanje spletne ikone. Če si želite ogledati seznam povezanih izkušenj, glejte [Povezane izkušnje v Officeu](connected-experiences.md).

|Kategorija|Podrobnosti|
|:-----|:-----|
|**Ključ**  | `OfficeExperiencesDownloadingContentPreference`  |
|**Vrsta podatkov**  | Logični |
|**Možne vrednosti**  | `TRUE` *(omogočeno)* <br/> `FALSE` *(onemogočeno)*|


Če te prednostne nastavitve ne nastavite, so povezane izkušnje, s katerimi prenesete spletno vsebino, na voljo uporabnikom.

Če ima uporabnik naročnino na Office 365 (ali Microsoft 365) in je vpisan s službenim ali šolskim računom, ne more izklopiti povezanih izkušenj, ki prenašajo spletno vsebino.

Drugi uporabniki, kot so domači uporabniki z naročnino na Office 365 (ali Microsoft 365), lahko v možnosti **Nastavitve** > **Nastavitve zasebnosti** izklopijo povezane izkušnje, ki prenašajo spletno vsebino.

## <a name="preference-setting-for-optional-connected-experiences"></a>Prednostna nastavitev za izbirne povezane izkušnje

Poleg povezanih izkušenj, omenjenih v tem članku, lahko izbirate še med dodatnimi izbirnimi povezanimi izkušnjami, s katerimi lahko vaši uporabniki dostopajo do svojih računov organizacije, imenovanih tudi službeni ali šolski računi. Na primer, dodatki za Office, ki so preneseni prek Trgovine Office v napravo. Če si želite ogledati več primerov, preberite [Pregled izbirnih povezanih izkušenj v Officeu](optional-connected-experiences.md).

|Kategorija|Podrobnosti|
|:-----|:-----|
|**Ključ**  | `OptionalConnectedExperiencesPreference`  |
|**Vrsta podatkov**  | Logični |
|**Možne vrednosti**  | `TRUE` *(omogočeno)* <br/> `FALSE` *(onemogočeno)*|


Če te prednostne nastavitve ne nastavite, so izbirne povezane izkušnje na voljo uporabnikom z naročnino na Office 365 (ali Microsoft 365), ki so vpisani s službenim ali šolskim računom. Če te prednostne nastavitve ne nastavite na NAPAČNO, lahko ti uporabniki v možnosti **Nastavitve** > **Nastavitve zasebnosti** izklopijo izbirne povezane izkušnje.

Če želite drugim uporabnikom, kot so domači uporabniki z naročnino na Office 365 (ali Microsoft 365), ne morete izklopiti izbirnih povezanih izkušenj.