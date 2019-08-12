---
title: Uporaba prednostnih nastavitev za upravljanje kontrolnikov zasebnosti za Office za Mac
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
description: Officeovim skrbnikom omogoča informacije o načinu uporabe prednostnih nastavitev za upravljanje kontrolnikov zasebnosti za Office za Mac.
hideEdit: true
ms.openlocfilehash: 01bb31f3b6c307ec1dc4762b54fea17185dcf27d
ms.sourcegitcommit: 0fd23324ba1364fa1f8dd1578adf25946adde90f
ms.translationtype: HT
ms.contentlocale: sl-SI
ms.lasthandoff: 08/07/2019
ms.locfileid: "36246324"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-for-mac"></a>Uporaba prednostnih nastavitev za upravljanje kontrolnikov zasebnosti za Office za Mac

V različici 16.28 sistema Office za Mac smo uvedli nove prednostne nastavitve, s katerimi lahko upravljate nastavitve, povezane z naslednjo vsebino:

- ***Diagnostični podatki*** o uporabljeni programski opremi odjemalca za Office, ki jih je sistem zbral in poslal Microsoftu.

- ***Povezane izkušnje***, ki za omogočanje razširjenih Officeovih funkcij uporabljajo storitve v oblaku.

Poleg tega je na voljo nova prednostna nastavitev, povezana s pogovornim oknom **Obvestilo o zahtevanih podatkih** za orodje Microsoft AutoUpdate.

Če želite več informacij o diagnostičnih podatkih in povezanih izkušnjah, preberite članek [Pregled kontrolnikov zasebnosti](overview-privacy-controls.md).

> [!NOTE]
> Če želite več informacij o podobnih nastavitvah za Office v računalnikih s sistemom Windows, preberite članek [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office 365 ProPlus](manage-privacy-controls.md).

## <a name="setting-preferences"></a>Nastavljanje prednostnih nastavitev

Nove prednostne nastavitve so združljive z nastavitvami CFPreferences API in jih lahko nastavite z ukazom `defaults` v programu Terminal oziroma jih lahko uveljavite preko konfiguracijskega profila ali strežnika Upravljanje mobilnih naprav (MDM). Ko so prednostne nastavitve uveljavljene, uporabnik vrednosti ne more več spreminjati, vsi kontrolniki v aplikaciji pa so onemogočeni.

## <a name="preference-setting-for-diagnostic-data"></a>Prednostna nastavitev za diagnostične podatke

Diagnostični podatki se uporabljajo za zaščito, posodobitev, zaznavanje težav in njihovo odpravljanje v Officeu ter za izboljšave izdelka. Če želite več informacij, preberite članek [Diagnostični podatki, poslani Microsoftu iz storitve Office 365 ProPlus](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).

|||
|:-----|:-----|
|**Domena prednostne nastavitve**  | `com.microsoft.office` |
|**Ključ**  | `DiagnosticDataTypePreference`  |
|**Vrsta podatkov**  | Niz |
|**Možne vrednosti**  | `BasicDiagnosticData` *(s tem nastavite raven na možnost »Zahtevana«)* <br/> `FullDiagnosticData` *(s tem nastavite raven na možnost »Izbirna«)* <br/> `ZeroDiagnosticData` *(s tem nastavite raven na možnost »Nobena«)* |
|**Razpoložljivost** |16.28 in novejše različice |

> [!NOTE]
> Če nastavite to prednostno nastavitev, bo veljala tudi za te izdelke:
> - Teams 1.00.217856 za Mac in novejše različice te aplikacije
> - Skype za podjetja za Mac 16.28 in novejše različice te aplikacije

Če te prednostne nastavitve ne nastavite, Microsoft v primeru uporabnikov z naročnino na Office 365, ki so vpisani s službenim ali šolskim računom, oziroma uporabnikov, ki imajo različico sistema Office 2019 za Mac za količinsko licenciranje, prejema izbirne in zahtevane diagnostične podatke. Ti uporabniki ne morejo spremeniti ravni diagnostičnih podatkov, in sicer ne glede na to, kako nastavite to prednostno nastavitev.

V primeru drugih uporabnikov, kot so domači uporabniki z naročnino na Office 365, Microsoft prejema samo zahtevane diagnostične podatke, razen če uporabnik v možnosti **Nastavitve** > **Zasebnost** izbere, da so poslani tudi izbirni diagnostični podatki.

## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a>Prednostna nastavitev za povezane izkušnje, ki analizirajo vašo vsebino

Povezane Izkušnje, ki analizirajo vašo vsebino so izkušnje, ki na podlagi Officeove vsebine nudijo priporočila za načrte, predloge za urejanje, vpoglede v podatke in podobne funkcije. Kot na primer Oblikovalnik za PowerPoint ali Raziskovalec v Wordu. Če si želite ogledati seznam povezanih izkušenj, glejte [Povezane izkušnje v Officeu](connected-experiences.md).

|||
|:-----|:-----|
|**Domena prednostne nastavitve**  | `com.microsoft.office` |
|**Ključ**  | `OfficeExperiencesAnalyzingContentPreference`  |
|**Vrsta podatkov**  | Logični |
|**Možne vrednosti**  | `TRUE` *(omogočeno)* <br/> `FALSE` *(onemogočeno)*|
|**Razpoložljivost** |16.28 in novejše različice |

Če te prednostne nastavitve ne nastavite, so povezane izkušnje, ki analizirajo vsebino, na voljo za uporabnike. 

Če ima uporabnik naročnino na Office 365 in je vpisan s službenim ali šolskim računom oz. če ima uporabnik različico sistema Office 2019 za Mac za količinsko licenciranje, ne more izklopiti povezanih izkušenj, ki analizirajo vsebino.

Drugi uporabniki, kot so domači uporabniki z naročnino na Office 365, lahko v možnosti **Nastavitve** > **Zasebnost** izklopijo povezane izkušnje, ki analizirajo vsebino.

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a>Prednostna nastavitev za povezane izkušnje, s katerimi prenesete spletno vsebino

Povezane izkušnje, s katerimi prenesete spletno vsebino, so izkušnje, ki vam omogočajo, da poiščete in prenesete spletno vsebino, vključno s predlogami, slikami, 3D-modeli, videoposnetki in referenčnim gradivom, s katero izpopolnite svoje dokumente. Denimo Officeove predloge ali orodje za hitri začetek za PowerPoint. Če si želite ogledati seznam povezanih izkušenj, glejte [Povezane izkušnje v Officeu](connected-experiences.md).

|||
|:-----|:-----|
|**Domena prednostne nastavitve**  | `com.microsoft.office` |
|**Ključ**  | `OfficeExperiencesDownloadingContentPreference`  |
|**Vrsta podatkov**  | Logični |
|**Možne vrednosti**  | `TRUE` *(omogočeno)* <br/> `FALSE` *(onemogočeno)*|
|**Razpoložljivost** |16.28 in novejše različice |

Če te prednostne nastavitve ne nastavite, so povezane izkušnje, s katerimi prenesete spletno vsebino, na voljo uporabnikom.

Če ima uporabnik naročnino na Office 365 in je vpisan s službenim ali šolskim računom oziroma če ima uporabnik različico sistema Office 2019 za Mac za količinsko licenciranje, ne more izklopiti povezanih izkušenj, s katerimi prenesete spletno vsebino.

Drugi uporabniki, kot so domači uporabniki z naročnino na Office 365, lahko v možnosti **Nastavitve** > **Zasebnost** izklopijo povezane izkušnje, s katerimi prenesete spletno vsebino.

## <a name="preference-setting-for-optional-connected-experiences"></a>Prednostna nastavitev za izbirne povezane izkušnje

Poleg povezanih izkušenj, omenjenih v tem članku, lahko izbirate še med dodatnimi izbirnimi povezanimi izkušnjami, s katerimi lahko vaši uporabniki dostopajo do svojih računov organizacije, imenovanih tudi službeni ali šolski računi. Na primer funkcije LinkedIn pomočnika za življenjepis v Wordu ali vrstica za vreme v Outlooku, ki uporablja storitev Vreme MSN. Če si želite ogledati več primerov, preberite [Pregled izbirnih povezanih izkušenj v Officeu](optional-connected-experiences.md).

|||
|:-----|:-----|
|**Domena prednostne nastavitve**  | `com.microsoft.office` |
|**Ključ**  | `OptionalConnectedExperiencesPreference`  |
|**Vrsta podatkov**  | Logični |
|**Možne vrednosti**  | `TRUE` *(omogočeno)* <br/> `FALSE` *(onemogočeno)*|
|**Razpoložljivost** |16.28 in novejše različice |

Če te prednostne nastavitve ne nastavite, so izbirne povezane izkušnje na voljo uporabnikom z naročnino na Office 365, ki so vpisani s službenim ali šolskim računom, oz. uporabnikom, ki imajo različico sistema Office 2019 za Mac za količinsko licenciranje. Če te prednostne nastavitve ne nastavite na `FALSE`, lahko ti uporabniki v možnosti **Nastavitve** > **Zasebnost** izklopijo izbirne povezane izkušnje.

Drugi uporabniki, kot so domači uporabniki z naročnino na Office 365, nimajo možnosti izklopa izbirnih povezanih izkušenj.

## <a name="preference-setting-for-most-connected-experiences"></a>Prednostna nastavitev za najpogostejše povezane izkušnje

S to prednostno nastavitvijo lahko nadzorujete, ali so najpogostejše povezane izkušnje na voljo uporabnikom.

|||
|:-----|:-----|
|**Domena prednostne nastavitve**  | `com.microsoft.office` |
|**Ključ**  | `ConnectedOfficeExperiencesPreference`  |
|**Vrsta podatkov**  | Logični |
|**Možne vrednosti**  | `TRUE` *(omogočeno)* <br/> `FALSE` *(onemogočeno)*|
|**Razpoložljivost** |16.28 in novejše različice |

Če te prednostne nastavitve ne nastavite, so vašim uporabnikom na voljo vse povezane izkušnje, razen če ste nastavili eno od drugih prej omenjenih prednostnih nastavitev za povezane izkušnje, kot je `OfficeExperiencesAnalyzingContentPreference`.

Če to prednostno nastavitev nastavite na primer na `FALSE`, te vrste povezanih izkušenj vašim uporabnikom ne bodo na voljo:
- Izkušnje, s katerimi analizirate vsebino
- Izkušnje, s katerimi prenašate spletno vsebino
- Izbirne povezane izkušnje

Če to prednostno nastavitev nastavite na `FALSE`, boste izklopili tudi večino drugih povezanih izkušenj, kot sta soavtorstvo in spletna shramba datotek. Če si želite ogledati seznam drugih povezanih izkušenj, glejte [Povezane izkušnje v Officeu](connected-experiences.md).

Tudi če to prednostno nastavitev nastavite na `FALSE`, bo še vedno na voljo omejena funkcionalnost Officea, kot je sinhronizacija nabiralnika v Outlooku, in še naprej bodo delovale skupine ter Skype za podjetja. [Osnovne storitve](essential-services.md), kot je storitev licenciranja, s katero potrdite, da imate ustrezno licenco za uporabo Officea, prav tako ostanejo na voljo.

Če ima uporabnik naročnino na Office 365 in je vpisan s službenim ali šolskim računom oziroma če ima uporabnik različico sistema Office 2019 za Mac za količinsko licenciranje, ne more izklopiti najpogostejših povezanih izkušenj.

Drugi uporabniki, kot so domači uporabniki z naročnino na Office 365, lahko v možnosti **Nastavitve** > **Zasebnost** izklopijo najpogostejše povezane izkušnje.

## <a name="preference-setting-for-the-required-data-notice-dialog-for-microsoft-autoupdate"></a>Prednostna nastavitev za pogovorno okno »Obvestilo o zahtevanih podatkih« za orodje Microsoft AutoUpdate

Ob prvem zagonu aplikacije Microsoft AutoUpdate (MAU) 4.12 ali njene poznejše različice je uporabnikom prikazano pogovorno okno **Obvestilo o zahtevanih podatkih**, v katerem so navedene informacije o vrsti podatkov, ki jih MAU pošilja Microsoftu.

Če ne želite, da uporabniki vidijo pogovorno okno**Obvestilo o zahtevanih podatkih** za orodje Microsoft AutoUpdate, lahko nastavite naslednjo prednostno nastavitev. Ne glede na to, katero vrednost nastavite, pogovorno okno vašim uporabnikom ne bo prikazano.

|||
|:-----|:-----|
|**Domena prednostne nastavitve**  | `com.microsoft.autoupdate2` |
|**Ključ**  | `AcknowledgedDataCollectionPolicy`  |
|**Vrsta podatkov**  | Niz |
|**Možne vrednosti**  | `RequiredDataOnly` <br/> `RequiredAndOptionalData`|
|**Razpoložljivost** |4.12 in novejše različice |

Če dovolite, da uporabniki vidijo to pogovorno okno, je v primeru, da uporabnik izbere **V redu**, v pravilnik `AcknowledgedDataCollectionPolicy` zapisana vrednost `RequiredDataOnly`, pogovorno okno pa uporabniku ni več prikazano.


## <a name="related-topics"></a>Sorodne teme

- [Priročnik za konfiguracijski profil (dokumentacija za razvijalce aplikacij za sistem Apple)](https://go.microsoft.com/fwlink/p/?linkid=852998)
- [Uvajanje prednostnih nastavitev za Office za Mac](../mac/deploy-preferences-for-office-for-mac.md)
- [Nastavitve zasebnosti računa](https://support.office.com/article/3e7bc183-bf52-4fd0-8e6b-78978f7f121b#ID0EAADAAA=Mac)
