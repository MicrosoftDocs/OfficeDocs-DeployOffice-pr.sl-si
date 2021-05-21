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
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="b4a65-103">Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom iOS</span><span class="sxs-lookup"><span data-stu-id="b4a65-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

> [!NOTE]
> <span data-ttu-id="b4a65-104">Če si želite ogledati seznam Officeovih izdelkov, ki so zajeti v teh informacijah o zasebnosti, glejte [Kontrolnike zasebnosti, ki so na voljo za Officeove izdelke](products-versions-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="b4a65-104">For a list of Office products covered by this privacy information, see [Privacy controls available for Office products](products-versions-privacy-controls.md).</span></span>

<span data-ttu-id="b4a65-105">Na voljo so nove prednostne nastavitve za Office v napravah s sistemom iOS, s katerimi lahko nadzorujete nastavitve, povezane z naslednjo vsebino:</span><span class="sxs-lookup"><span data-stu-id="b4a65-105">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="b4a65-106">***Diagnostični podatki*** o uporabljeni programski opremi odjemalca za Office, ki jih je sistem zbral in poslal Microsoftu.</span><span class="sxs-lookup"><span data-stu-id="b4a65-106">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="b4a65-107">***Povezane izkušnje***, ki za omogočanje razširjenih Officeovih funkcij uporabljajo storitve v oblaku.</span><span class="sxs-lookup"><span data-stu-id="b4a65-107">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="b4a65-108">Če želite več informacij o diagnostičnih podatkih in povezanih izkušnjah, preberite članek [Pregled kontrolnikov zasebnosti](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="b4a65-108">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

> [!NOTE]
> <span data-ttu-id="b4a65-109">Če želite več informacij o podobnih nastavitvah za Office v računalnikih s sistemom macOS, preberite članek [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office for Mac](mac-privacy-preferences.md)</span><span class="sxs-lookup"><span data-stu-id="b4a65-109">For information about similar settings for Office on computers running macOS, see [Use preferences to manage privacy controls for Office for Mac](mac-privacy-preferences.md)</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="b4a65-110">Nastavljanje nastavitev naprave</span><span class="sxs-lookup"><span data-stu-id="b4a65-110">Setting device preferences</span></span>
<span data-ttu-id="b4a65-111">Te nove prednostne nastavitve lahko nastavite tudi na ravni naprave s strežnikom Upravljanje mobilnih naprav (MDM), ko je nameščena Officeova aplikacija.</span><span class="sxs-lookup"><span data-stu-id="b4a65-111">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="b4a65-112">Mnogi strežniki MDM skrbnikom za IT omogočajo, da dodajo izbirni konfiguracijski slovar, ko strežnik pošlje `InstallApplication` ukaz MDM v napravo s sistemom iOS.</span><span class="sxs-lookup"><span data-stu-id="b4a65-112">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="b4a65-113">Če želite več informacij, si oglejte dokumentacijo strežnika MDM.</span><span class="sxs-lookup"><span data-stu-id="b4a65-113">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="b4a65-p102">Slovar je predstavljen kot nabor parov ključev/vrednosti v obliki zapisa datoteke XML.</span><span class="sxs-lookup"><span data-stu-id="b4a65-p102">The dictionary is represented as a set of key/value pairs in XML format. For example:</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="b4a65-116">Ko ga pošljete napravi, bo konfiguracijski slovar shranjen pod `com.apple.managed.configuration` ključem, kjer bo prebran ob zagonu Officeove aplikacije.</span><span class="sxs-lookup"><span data-stu-id="b4a65-116">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

> [!NOTE]
> <span data-ttu-id="b4a65-117">Uporabite lahko tudi storitev pravilnika za Office Cloud in te nastavitve za 4 pravilnikov:</span><span class="sxs-lookup"><span data-stu-id="b4a65-117">You can also use the Office cloud policy service and these 4 policy settings:</span></span>
> - <span data-ttu-id="b4a65-118">Konfiguracija ravni diagnostičnih podatkov o programski opremi odjemalca, ki jih Office pošlje Microsoftu</span><span class="sxs-lookup"><span data-stu-id="b4a65-118">Configure the level of client software diagnostic data sent by Office to Microsoft</span></span>
> - <span data-ttu-id="b4a65-119">Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko analizirate vsebino</span><span class="sxs-lookup"><span data-stu-id="b4a65-119">Allow the use of connected experiences in Office that analyze content</span></span>
> - <span data-ttu-id="b4a65-120">Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko prenašate spletno vsebino</span><span class="sxs-lookup"><span data-stu-id="b4a65-120">Allow the use of connected experiences in Office that download online content</span></span>
> - <span data-ttu-id="b4a65-121">Omogočanje uporabe dodatnih povezanih izkušenj v Officeu</span><span class="sxs-lookup"><span data-stu-id="b4a65-121">Allow the use of additional optional connected experiences in Office</span></span>
>
> <span data-ttu-id="b4a65-122">Nastavitve zasebnosti za Outlook za iOS in OneDrive za iOS lahko konfigurirate le s storitvijo Office politiko oblaka.</span><span class="sxs-lookup"><span data-stu-id="b4a65-122">Privacy settings for Outlook for iOS and OneDrive for iOS can only be configured by using the Office cloud policy service.</span></span>
>
> <span data-ttu-id="b4a65-123">Če želite več informacij o uporabi storitve pravilnika Office Cloud, si oglejte [pregled storitve pravilnika Office Cloud ](../overview-office-cloud-policy-service.md).</span><span class="sxs-lookup"><span data-stu-id="b4a65-123">For more information on using the Office cloud policy service, see [Overview of the Office cloud policy service](../overview-office-cloud-policy-service.md).</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="b4a65-124">Prednostna nastavitev za diagnostične podatke</span><span class="sxs-lookup"><span data-stu-id="b4a65-124">Preference setting for diagnostic data</span></span>

<span data-ttu-id="b4a65-125">Diagnostični podatki se uporabljajo za zaščito, posodobitev, zaznavanje težav in njihovo odpravljanje v Officeu ter za izboljšave izdelka.</span><span class="sxs-lookup"><span data-stu-id="b4a65-125">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="b4a65-126">Če želite več informacij, si oglejte [diagnostičnih podatkov, ki so bili poslani iz aplikacij Microsoft 365 za podjetja v Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="b4a65-126">For more information, see [Diagnostic data sent from Microsoft 365 Apps for enterprise to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span></span>

|<span data-ttu-id="b4a65-127">Kategorija</span><span class="sxs-lookup"><span data-stu-id="b4a65-127">Category</span></span>|<span data-ttu-id="b4a65-128">Podrobnosti</span><span class="sxs-lookup"><span data-stu-id="b4a65-128">Details</span></span>|
|:-----|:-----|
|<span data-ttu-id="b4a65-129">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="b4a65-129">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="b4a65-130">**Vrsta podatkov**</span><span class="sxs-lookup"><span data-stu-id="b4a65-130">**Data Type**</span></span>  | <span data-ttu-id="b4a65-131">Niz</span><span class="sxs-lookup"><span data-stu-id="b4a65-131">String</span></span> |
|<span data-ttu-id="b4a65-132">**Možne vrednosti**</span><span class="sxs-lookup"><span data-stu-id="b4a65-132">**Possible values**</span></span>  | <span data-ttu-id="b4a65-133">`BasicDiagnosticData` *(ta vrednost nastavi raven na »Zahtevano«)*</span><span class="sxs-lookup"><span data-stu-id="b4a65-133">`BasicDiagnosticData` *(this value sets the level to Required)*</span></span> <br/> <span data-ttu-id="b4a65-134">`FullDiagnosticData` *(ta vrednost nastavi raven na »Izbirno«)*</span><span class="sxs-lookup"><span data-stu-id="b4a65-134">`FullDiagnosticData` *(this value sets the level to Optional)*</span></span> <br/> <span data-ttu-id="b4a65-135">`ZeroDiagnosticData` *(Ta vrednost nastavi raven na »Nič«)*</span><span class="sxs-lookup"><span data-stu-id="b4a65-135">`ZeroDiagnosticData` *(this value sets the level to Neither)*</span></span> |

<span data-ttu-id="b4a65-136">Če te prednostne nastavitve ne nastavite, se Microsoftu pošljejo le zahtevani in izbirni diagnostični podatki, če so uporabniki z naročnino na Office 365 (ali Microsoft 365) prijavljeni z delovnim ali šolskim računom.</span><span class="sxs-lookup"><span data-stu-id="b4a65-136">If you don't set this preference, both required and optional diagnostic data are sent to Microsoft if users with an Office 365 (or Microsoft 365) subscription are signed in with a work or school account.</span></span> <span data-ttu-id="b4a65-137">Ti uporabniki ne morejo spremeniti ravni diagnostičnih podatkov, in sicer ne glede na to, kako nastavite to prednostno nastavitev.</span><span class="sxs-lookup"><span data-stu-id="b4a65-137">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

> [!NOTE]
> <span data-ttu-id="b4a65-138">Prejšnji odstavek smo posodobili. Tako smo natančneje pojasnili, da so izbirni diagnostični podatki Microsoftu poslani, tudi če ne izberete te nastavitve.</span><span class="sxs-lookup"><span data-stu-id="b4a65-138">We've updated the previous paragraph to clarify that optional diagnostic data is also sent to Microsoft if you don't set this preference.</span></span>

<span data-ttu-id="b4a65-139">V primeru drugih uporabnikov, kot so domači uporabniki z naročnino na Office 365 (ali Microsoft 365), Microsoft prejema samo zahtevane diagnostične podatke, razen če uporabnik v možnosti **Nastavitve** > **Zasebnost** izbere, da so poslani tudi izbirni diagnostični podatki.</span><span class="sxs-lookup"><span data-stu-id="b4a65-139">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Settings** > **Privacy Settings**.</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="b4a65-140">Prednostna nastavitev za povezane izkušnje, ki analizirajo vašo vsebino</span><span class="sxs-lookup"><span data-stu-id="b4a65-140">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="b4a65-141">Povezane Izkušnje, ki analizirajo vašo vsebino so izkušnje, ki na podlagi Officeove vsebine nudijo priporočila za načrte, predloge za urejanje, vpoglede v podatke in podobne funkcije.</span><span class="sxs-lookup"><span data-stu-id="b4a65-141">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="b4a65-142">Na primer »Ideje za oblikovanje« v PowerPointu.</span><span class="sxs-lookup"><span data-stu-id="b4a65-142">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="b4a65-143">Če si želite ogledati seznam povezanih izkušenj, glejte [Povezane izkušnje v Officeu](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="b4a65-143">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|<span data-ttu-id="b4a65-144">Kategorija</span><span class="sxs-lookup"><span data-stu-id="b4a65-144">Category</span></span>|<span data-ttu-id="b4a65-145">Podrobnosti</span><span class="sxs-lookup"><span data-stu-id="b4a65-145">Details</span></span>|
|:-----|:-----|
|<span data-ttu-id="b4a65-146">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="b4a65-146">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="b4a65-147">**Vrsta podatkov**</span><span class="sxs-lookup"><span data-stu-id="b4a65-147">**Data Type**</span></span>  | <span data-ttu-id="b4a65-148">Logični</span><span class="sxs-lookup"><span data-stu-id="b4a65-148">Boolean</span></span> |
|<span data-ttu-id="b4a65-149">**Možne vrednosti**</span><span class="sxs-lookup"><span data-stu-id="b4a65-149">**Possible values**</span></span>  | <span data-ttu-id="b4a65-150">`TRUE` *(omogočeno)*</span><span class="sxs-lookup"><span data-stu-id="b4a65-150">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="b4a65-151">`FALSE` *(onemogočeno)*</span><span class="sxs-lookup"><span data-stu-id="b4a65-151">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="b4a65-152">Če te prednostne nastavitve ne nastavite, so povezane izkušnje, ki analizirajo vsebino, na voljo za uporabnike.</span><span class="sxs-lookup"><span data-stu-id="b4a65-152">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="b4a65-153">Če ima uporabnik naročnino na Office 365 (ali Microsoft 365) in je vpisan s službenim ali šolskim računom, ne more izklopiti povezanih izkušenj, ki analizirajo vsebino.</span><span class="sxs-lookup"><span data-stu-id="b4a65-153">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="b4a65-154">Drugi uporabniki, kot so domači uporabniki z naročnino na Office 365 (ali Microsoft 365), lahko v možnosti **Nastavitve** > **Nastavitve zasebnosti** izklopijo povezane izkušnje, ki analizirajo vsebino.</span><span class="sxs-lookup"><span data-stu-id="b4a65-154">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that analyze content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="b4a65-155">Prednostna nastavitev za povezane izkušnje, s katerimi prenesete spletno vsebino</span><span class="sxs-lookup"><span data-stu-id="b4a65-155">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="b4a65-156">Povezane izkušnje, s katerimi prenesete spletno vsebino, so izkušnje, ki vam omogočajo, da poiščete in prenesete spletno vsebino, vključno s predlogami, slikami, videoposnetki in referenčnim gradivom, s katero izpopolnite svoje dokumente.</span><span class="sxs-lookup"><span data-stu-id="b4a65-156">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="b4a65-157">Na primer, Officeove predloge ali vstavljanje spletne ikone.</span><span class="sxs-lookup"><span data-stu-id="b4a65-157">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="b4a65-158">Če si želite ogledati seznam povezanih izkušenj, glejte [Povezane izkušnje v Officeu](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="b4a65-158">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|<span data-ttu-id="b4a65-159">Kategorija</span><span class="sxs-lookup"><span data-stu-id="b4a65-159">Category</span></span>|<span data-ttu-id="b4a65-160">Podrobnosti</span><span class="sxs-lookup"><span data-stu-id="b4a65-160">Details</span></span>|
|:-----|:-----|
|<span data-ttu-id="b4a65-161">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="b4a65-161">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="b4a65-162">**Vrsta podatkov**</span><span class="sxs-lookup"><span data-stu-id="b4a65-162">**Data Type**</span></span>  | <span data-ttu-id="b4a65-163">Logični</span><span class="sxs-lookup"><span data-stu-id="b4a65-163">Boolean</span></span> |
|<span data-ttu-id="b4a65-164">**Možne vrednosti**</span><span class="sxs-lookup"><span data-stu-id="b4a65-164">**Possible values**</span></span>  | <span data-ttu-id="b4a65-165">`TRUE` *(omogočeno)*</span><span class="sxs-lookup"><span data-stu-id="b4a65-165">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="b4a65-166">`FALSE` *(onemogočeno)*</span><span class="sxs-lookup"><span data-stu-id="b4a65-166">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="b4a65-167">Če te prednostne nastavitve ne nastavite, so povezane izkušnje, s katerimi prenesete spletno vsebino, na voljo uporabnikom.</span><span class="sxs-lookup"><span data-stu-id="b4a65-167">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="b4a65-168">Če ima uporabnik naročnino na Office 365 (ali Microsoft 365) in je vpisan s službenim ali šolskim računom, ne more izklopiti povezanih izkušenj, ki prenašajo spletno vsebino.</span><span class="sxs-lookup"><span data-stu-id="b4a65-168">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="b4a65-169">Drugi uporabniki, kot so domači uporabniki z naročnino na Office 365 (ali Microsoft 365), lahko v možnosti **Nastavitve** > **Nastavitve zasebnosti** izklopijo povezane izkušnje, ki prenašajo spletno vsebino.</span><span class="sxs-lookup"><span data-stu-id="b4a65-169">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that download online content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="b4a65-170">Prednostna nastavitev za izbirne povezane izkušnje</span><span class="sxs-lookup"><span data-stu-id="b4a65-170">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="b4a65-171">Poleg povezanih izkušenj, omenjenih v tem članku, lahko izbirate še med dodatnimi izbirnimi povezanimi izkušnjami, s katerimi lahko vaši uporabniki dostopajo do svojih računov organizacije, imenovanih tudi službeni ali šolski računi.</span><span class="sxs-lookup"><span data-stu-id="b4a65-171">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="b4a65-172">Na primer, dodatki za Office, ki so preneseni prek Trgovine Office v napravo.</span><span class="sxs-lookup"><span data-stu-id="b4a65-172">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="b4a65-173">Če si želite ogledati več primerov, preberite [Pregled izbirnih povezanih izkušenj v Officeu](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="b4a65-173">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|<span data-ttu-id="b4a65-174">Kategorija</span><span class="sxs-lookup"><span data-stu-id="b4a65-174">Category</span></span>|<span data-ttu-id="b4a65-175">Podrobnosti</span><span class="sxs-lookup"><span data-stu-id="b4a65-175">Details</span></span>|
|:-----|:-----|
|<span data-ttu-id="b4a65-176">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="b4a65-176">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="b4a65-177">**Vrsta podatkov**</span><span class="sxs-lookup"><span data-stu-id="b4a65-177">**Data Type**</span></span>  | <span data-ttu-id="b4a65-178">Logični</span><span class="sxs-lookup"><span data-stu-id="b4a65-178">Boolean</span></span> |
|<span data-ttu-id="b4a65-179">**Možne vrednosti**</span><span class="sxs-lookup"><span data-stu-id="b4a65-179">**Possible values**</span></span>  | <span data-ttu-id="b4a65-180">`TRUE` *(omogočeno)*</span><span class="sxs-lookup"><span data-stu-id="b4a65-180">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="b4a65-181">`FALSE` *(onemogočeno)*</span><span class="sxs-lookup"><span data-stu-id="b4a65-181">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="b4a65-182">Če te prednostne nastavitve ne nastavite, so izbirne povezane izkušnje na voljo uporabnikom z naročnino na Office 365 (ali Microsoft 365), ki so vpisani s službenim ali šolskim računom.</span><span class="sxs-lookup"><span data-stu-id="b4a65-182">If you don't set this preference, optional connected experiences are available to users with an Office 365 (or Microsoft 365) subscription that are signed in with a work or school account.</span></span> <span data-ttu-id="b4a65-183">Če te prednostne nastavitve ne nastavite na NAPAČNO, lahko ti uporabniki v možnosti **Nastavitve** > **Nastavitve zasebnosti** izklopijo izbirne povezane izkušnje.</span><span class="sxs-lookup"><span data-stu-id="b4a65-183">Unless you have set this preference to FALSE, these users can choose to turn off optional connected experiences by going to **Settings** > **Privacy Settings**.</span></span>

<span data-ttu-id="b4a65-184">Če želite drugim uporabnikom, kot so domači uporabniki z naročnino na Office 365 (ali Microsoft 365), ne morete izklopiti izbirnih povezanih izkušenj.</span><span class="sxs-lookup"><span data-stu-id="b4a65-184">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, there isn't an option to turn off optional connected experiences.</span></span>