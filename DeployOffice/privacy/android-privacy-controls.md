---
title: Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom Android
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
audience: ITPro
ms.topic: article
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Officeovim skrbnikom ponuja informacije o tem, kako upravljati nastavitve zasebnosti za Office v napravah s sistemom Android.
hideEdit: true
ms.openlocfilehash: 38d68df0d3a12e6858568906a60973bad9d76709
ms.sourcegitcommit: f441b1a5f8853c0941b3e23c7781c89abf0be641
ms.translationtype: HT
ms.contentlocale: sl-SI
ms.lasthandoff: 07/09/2020
ms.locfileid: "45087899"
---
# <a name="use-policy-settings-to-manage-privacy-controls-for-office-on-android-devices"></a>Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom Android

Za Office v napravah s sistemom Android so na voljo nastavitve pravilnika, ki omogočajo nadzor nad nastavitvami, ki so povezane z naslednjim:

- ***Diagnostični podatki*** o uporabljeni programski opremi odjemalca za Office, ki jih je sistem zbral in poslal Microsoftu.

- ***Povezane izkušnje***, ki za omogočanje razširjenih Officeovih funkcij uporabljajo storitve v oblaku.

Če želite več informacij o diagnostičnih podatkih in povezanih izkušnjah, preberite članek [Pregled kontrolnikov zasebnosti](overview-privacy-controls.md).

Te nastavitve pravilnika se nanašajo na te aplikacije:
- Različica 16.0.12228.20260 in novejše različice Worda za Android, Excela za Android in PowerPointa za Android.
- Različica 4.1.71 in novejše različice Outlooka za Android.
- Različica 16.0.12228.20004 in novejše različice programa OneNote za Android.
- Različica 5.47 in novejše različice programa OneDrive za Android.

> [!NOTE]
>- Te nastavitve pravilnika velja tudi za različico 16.0.12130.20272 in novejše različice javnega predogleda [Officeove mobilne aplikacije](https://techcommunity.microsoft.com/t5/Office-Apps-Blog/Introducing-Office-Your-new-go-to-mobile-app-for-getting-work/ba-p/977172) za Android.
>- Uporaba javne različice predogleda aplikacije Office Mobile za Android bo zbrala dnevnike za zrušitve, ki lahko v nekaterih primerih vsebujejo vsebino.
>- Če ste zaskrbljeni zaradi zbirke podatkov iz javne predogledne različice Officeove mobilne aplikacije za Android, morate obvestiti uporabnike, da se ne bodo prijavili v aplikacijo s službenim ali šolskim računom.

## <a name="policy-settings-available-for-office-on-android-devices"></a>Nastavitve pravilnika, ki so na voljo za Office v napravah s sistemom Android

V spodnji tabeli so navedene nastavitve pravilnika, ki so na voljo za Office v napravah s sistemom Android, in povezave do dodatnih informacij o vsaki nastavitvi pravilnika.

> [!NOTE]
>- Dodatne informacije, ki so na voljo, so nastavitve pravilnika za Office v napravah, v katerih se izvaja sistem Windows. Vendar pa se iste informacije uporabljajo za Office v napravah s sistemom Android, ker so enake kot nastavitve pravilnika.
>- *Dovoli uporabo povezanih izkušenj v sistemu Office* nastavitev pravilnika, ki je na voljo za Office v napravah, v katerih se izvaja Windows, ne velja za Office v napravah s sistemom Android. 


|Ime nastavitve pravilnika  |Dodatne informacije |
|---------|---------|
|Konfiguracija ravni diagnostičnih podatkov o programski opremi odjemalca, ki jih Office pošlje Microsoftu|[Nastavitev pravilnika za diagnostične podatke](manage-privacy-controls.md#policy-setting-for-diagnostic-data)         |
|Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko analizirate vsebino| [Nastavitev pravilnika za povezane izkušnje z analizo vsebine](manage-privacy-controls.md#policy-setting-for-connected-experiences-that-analyze-your-content)        |
|Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko prenašate spletno vsebino |[Nastavitev pravilnika za povezane izkušnje, ki prenašajo spletno vsebino](manage-privacy-controls.md#policy-setting-for-connected-experiences-that-download-online-content)         |
|Omogočanje uporabe dodatnih povezanih izkušenj v Officeu |[Nastavitev pravilnika za izbirne povezane izkušnje](manage-privacy-controls.md#policy-setting-for-optional-connected-experiences)|



## <a name="use-office-cloud-policy-service-to-apply-policy-settings"></a>Uporaba skrbniških storitev za Office Cloud za uporabo nastavitev pravilnika

Če želite uporabiti katero koli od teh 4 nastavitev pravilnika za Office v napravah s sistemom Android, morate uporabiti storitev pravilnika za Office Cloud. Če želite več informacij o uporabi storitve pravilnika Office Cloud, si oglejte [pregled storitve pravilnika Office Cloud ](../overview-office-cloud-policy-service.md).

> [!NOTE]
> Če ste v preteklosti uporabljali pravilnike za storitev pravilnika Office Cloud za konfiguriranje teh nastavitev pravilnika za Office v napravah, v katerih se izvaja sistem Windows, bodo enake nastavitve veljale za Office v napravah s sistemom Android. Če želite, da se to zgodi, se morate le vpisati v storitev pravilnika Office Cloud in storitev bo samodejno uporabljala nastavitve za Office v napravah s sistemom Android.
