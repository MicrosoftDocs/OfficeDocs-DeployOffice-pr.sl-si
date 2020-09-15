---
title: Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za aplikacije Office v spletu.
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
description: Officeovim skrbnikom ponuja informacije o tem, kako upravljati nastavitve zasebnosti za aplikacije Office v spletu.
hideEdit: true
ms.openlocfilehash: b5131d5ffc09b28a3b5731a417fcd6d383fb7d01
ms.sourcegitcommit: da41d41b443c8392c96e64a4d2fc674957abddf5
ms.translationtype: HT
ms.contentlocale: sl-SI
ms.lasthandoff: 09/11/2020
ms.locfileid: "47431989"
---
# <a name="use-policy-settings-to-manage-privacy-controls-for-office-for-the-web-applications"></a>Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za aplikacije Office v spletu.

> [!NOTE]
> Če si želite ogledati seznam Officeovih izdelkov, ki so zajeti v teh informacijah o zasebnosti, glejte [Kontrolnike zasebnosti, ki so na voljo za Officeove izdelke](products-versions-privacy-controls.md).

Kot skrbnik za vašo organizacijo lahko nadzorujete, ali imajo vaši uporabniki izbiro za uporabo izbirnih povezanih izkušenj, ko uporabljajo aplikacije Office v spletu, na primer Word v spletu ali PowerPoint v spletu. Ta možnost je na voljo za uporabnike samo, če so vpisani s službenim ali šolskim računom, ko uporabljajo aplikacije Office v spletu. Za nadzor nad tem, ali imajo vaši uporabniki izbiro za uporabo izbirnih povezanih izkušenj, uporabite nastavitev pravilnika *Dovoli uporabo dodatnih povezanih izkušenj v Officeu*.

## <a name="overview-of-optional-connected-experiences"></a>Pregled izbirnih povezanih izkušenj

Izbirne povezane izkušnje so storitve s podporo v oblaku, ki so na voljo vašim uporabnikom, ko uporabljajo sistem Office. Primera izbirnih povezanih izkušenj vključujeta ustvarjanje grafikona z zemljevidom v Excelu ali vstavljanje slike s spleta v Wordov dokument. Obe izkušnji sta odvisni od storitev, ki jih ponuja Microsoft Bing. Uporaba teh storitev s podporo v oblaku je izbirna. 

Izbirne povezane izkušnje niso zajete v komercialno pogodbo organizacije z Microsoftom. Namesto tega izbirne povezane izkušnje Microsoft ponuja neposredno uporabnikom in jih ureja [pogodba o Microsoftovih storitvah](https://www.microsoft.com/servicesagreement). V nekaterih primerih vsebino ali funkcionalnost tretjih oseb omogočajo te izbirne povezane izkušnje, za katere lahko veljajo tudi drugi pogoji.

Nekatere izbirne povezane izkušnje morda niso na voljo v aplikacijah Office v spletu, vendar so na voljo pri uporabi drugih različicah Officea, na primer namizne različice na napravi s sistemom Windows.

Če želite izvedeti več, preberite [Pregled izbirnih povezanih izkušenj v Officeu](optional-connected-experiences.md).

## <a name="configure-the-policy-setting-by-using-the-office-cloud-policy-service"></a>Konfiguracija nastavitve pravilnika s storitvijo pravilnika za Office Cloud

Nastavitev pravilnika *Dovoli uporabo dodatnih povezanih izkušenj v Officeu* lahko uporabite za nadzor nad tem, ali imajo vaši uporabniki izbiro za uporabo izbirnih povezanih izkušenj. Če želite konfigurirati to nastavitev pravilnika za aplikacije Office za splet, uporabite [Storitev pravilnika za Office Cloud](../overview-office-cloud-policy-service.md).  

Če ne konfigurirate te nastavitve pravilnika, bo izbira za uporabo izbirnih povezanih izkušenj na voljo vašim uporabnikom. Če onemogočite to nastavitev pravilnika, uporabniki ne bodo mogli uporabljati nobene od izbirnih povezanih izkušenj.

Za aplikacije Office v spletu nastavitev pravilnika velja, ko vaši uporabniki delajo z Officeovimi dokumenti, ki so shranjeni v Microsoftovo spletno shrambo, na primer OneDrive za podjetja ali SharePoint Online.

Ker uporabljate Storitev pravilnika za Office Cloud, ta nastavitev pravilnika velja tudi, ko vaši uporabniki uporabljajo Office na napravah s sistemom Windows, Mac, iOS ali Android. Te nastavitve pravilnika ne morete konfigurirati le takrat, ko vaši uporabniki uporabljajo aplikacije Office v spletu. Toda ustvarite lahko konfiguracijo pravilnikov, ki vključuje to nastavitev pravilnika, pri čemer lahko ta konfiguracija pravilnika velja le za uporabnike, ki anonimno dostopajo do dokumentov z aplikacijami Office v spletu.

Če se odločite, da bodo uporabniki imeli na voljo izbirne povezane izkušnje, se bo vašim uporabnikom ob prvi uporabi aplikacije Office v spletu prikazalo obvestilo o zasebnosti. To obvestilo vaše uporabnike obvešča, da ste jim dalli možnost uporabe teh izbirnih povezanih izkušenj. Obvestilo prav tako obvesti uporabnike, da so neobvezne povezane izkušnje na voljo v skladu s pogodbo o Microsoftovih storitvah. Ker to obvestilo vsebuje pomembne informacije za vaše uporabnike, to obvestilo mora biti prikazano in ga ni mogoče izklopiti, skriti ali sprejeti v imenu vaših uporabnikov.

## <a name="users-can-choose-to-turn-off-optional-connected-experiences"></a>Uporabniki lahko izberejo možnost izklopa izbirnih povezanih izkušenj

Če se odločite, da boste uporabnikom omogočili neobvezne povezane izkušnje, bodo uporabniki lahko v [nastavitev zasebnosti svojega računa](https://support.microsoft.com/office/3e7bc183-bf52-4fd0-8e6b-78978f7f121b#ID0EAADAAA=Online) izklopili dostop do izbirnih povezanih izkušenj. Ta možnost je na voljo v nastavitvah zasebnosti računa le, če so vaši uporabniki vpisani s službenim ali šolskim računom. Vi kot skrbnik na noben način ne morete preprečiti posameznim uporabnikom v organizaciji, da bi onemogočili dostop do izbirne povezane izkušnje v svojih nastavitvah zasebnosti računa, če ste uporabnikom dodelili možnost izbire za uporabo izbirnih povezanih izkušenj.

## <a name="related-articles"></a>Sorodni članki

- [Pregled kontrolnikov za zasebnost za Microsoft 365 aplikacije za podjetja](overview-privacy-controls.md)
- [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Microsoft 365 aplikacije za podjetja](manage-privacy-controls.md)
- [Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office za Mac](mac-privacy-preferences.md)
- [Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom iOS](ios-privacy-preferences.md)
- [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom Android](android-privacy-controls.md)