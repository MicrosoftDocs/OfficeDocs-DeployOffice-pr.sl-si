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
ms.openlocfilehash: ac8b3428734649981f20a82be2f0793c857e09ee
ms.sourcegitcommit: 81295dff0f2fa474f0db39fd40560e3a23fff32a
ms.translationtype: HT
ms.contentlocale: sl-SI
ms.lasthandoff: 07/09/2020
ms.locfileid: "45092170"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="455b0-103">Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom iOS</span><span class="sxs-lookup"><span data-stu-id="455b0-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

<span data-ttu-id="455b0-104">Na voljo so nove prednostne nastavitve za Office v napravah s sistemom iOS, s katerimi lahko nadzorujete nastavitve, povezane z naslednjo vsebino:</span><span class="sxs-lookup"><span data-stu-id="455b0-104">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="455b0-105">***Diagnostični podatki*** o uporabljeni programski opremi odjemalca za Office, ki jih je sistem zbral in poslal Microsoftu.</span><span class="sxs-lookup"><span data-stu-id="455b0-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="455b0-106">***Povezane izkušnje***, ki za omogočanje razširjenih Officeovih funkcij uporabljajo storitve v oblaku.</span><span class="sxs-lookup"><span data-stu-id="455b0-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="455b0-107">Če želite več informacij o diagnostičnih podatkih in povezanih izkušnjah, preberite članek [Pregled kontrolnikov zasebnosti](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="455b0-107">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

<span data-ttu-id="455b0-108">Te prednostne nastavitve se nanašajo na naslednje aplikacije:</span><span class="sxs-lookup"><span data-stu-id="455b0-108">These preference settings apply to the following applications:</span></span>
- <span data-ttu-id="455b0-109">Različica 2.30 in poznejše različice programov Word za iOS, Excel za iOS in PowerPoint za iOS.</span><span class="sxs-lookup"><span data-stu-id="455b0-109">Version 2.30 and later of Word for iOS, Excel for iOS, and PowerPoint for iOS.</span></span>
- <span data-ttu-id="455b0-110">Različica 4.30.0 in novejše različice programa Outlook za iOS</span><span class="sxs-lookup"><span data-stu-id="455b0-110">Version 4.30.0 and later of Outlook for iOS</span></span>
- <span data-ttu-id="455b0-111">Različica 16.30 in novejše različice programa OneNote za iOS.</span><span class="sxs-lookup"><span data-stu-id="455b0-111">Version 16.30 and later of OneNote for iOS.</span></span>
- <span data-ttu-id="455b0-112">Različica 11.19.11 in novejše različice programa OneDrive za iOS.</span><span class="sxs-lookup"><span data-stu-id="455b0-112">Version 11.19.11 and later of OneDrive for iOS.</span></span>
- <span data-ttu-id="455b0-113">Različica 1.17 in novejša različica programa Visio Viewer za iOS.</span><span class="sxs-lookup"><span data-stu-id="455b0-113">Version 1.17 and later of Visio Viewer for iOS.</span></span>
- <span data-ttu-id="455b0-114">Različica 2.34 in novejše različice aplikacije Office za iOS.</span><span class="sxs-lookup"><span data-stu-id="455b0-114">Version 2.34 and later of the Office app for iOS.</span></span>

> [!NOTE]
> <span data-ttu-id="455b0-115">Če želite več informacij o podobnih nastavitvah za Office v računalnikih s sistemom macOS, preberite članek [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office for Mac](mac-privacy-preferences.md)</span><span class="sxs-lookup"><span data-stu-id="455b0-115">For information about similar settings for Office on computers running macOS, see [Use preferences to manage privacy controls for Office for Mac](mac-privacy-preferences.md)</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="455b0-116">Nastavljanje nastavitev naprave</span><span class="sxs-lookup"><span data-stu-id="455b0-116">Setting device preferences</span></span>
<span data-ttu-id="455b0-117">Te nove prednostne nastavitve lahko nastavite tudi na ravni naprave s strežnikom Upravljanje mobilnih naprav (MDM), ko je nameščena Officeova aplikacija.</span><span class="sxs-lookup"><span data-stu-id="455b0-117">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="455b0-118">Mnogi strežniki MDM skrbnikom za IT omogočajo, da dodajo izbirni konfiguracijski slovar, ko strežnik pošlje `InstallApplication` ukaz MDM v napravo s sistemom iOS.</span><span class="sxs-lookup"><span data-stu-id="455b0-118">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="455b0-119">Če želite več informacij, si oglejte dokumentacijo strežnika MDM.</span><span class="sxs-lookup"><span data-stu-id="455b0-119">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="455b0-120">Slovar je predstavljen kot nabor parov ključev/vrednosti v obliki zapisa datoteke XML.</span><span class="sxs-lookup"><span data-stu-id="455b0-120">The dictionary is represented as a set of key/value pairs in XML format.</span></span> <span data-ttu-id="455b0-121">Na primer:</span><span class="sxs-lookup"><span data-stu-id="455b0-121">For example:</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="455b0-122">Ko ga pošljete napravi, bo konfiguracijski slovar shranjen pod `com.apple.managed.configuration` ključem, kjer bo prebran ob zagonu Officeove aplikacije.</span><span class="sxs-lookup"><span data-stu-id="455b0-122">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

> [!NOTE]
> <span data-ttu-id="455b0-123">Uporabite lahko tudi storitev pravilnika za Office Cloud in te nastavitve za 4 pravilnikov:</span><span class="sxs-lookup"><span data-stu-id="455b0-123">You can also use the Office cloud policy service and these 4 policy settings:</span></span>
> - <span data-ttu-id="455b0-124">Konfiguracija ravni diagnostičnih podatkov o programski opremi odjemalca, ki jih Office pošlje Microsoftu</span><span class="sxs-lookup"><span data-stu-id="455b0-124">Configure the level of client software diagnostic data sent by Office to Microsoft</span></span>
> - <span data-ttu-id="455b0-125">Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko analizirate vsebino</span><span class="sxs-lookup"><span data-stu-id="455b0-125">Allow the use of connected experiences in Office that analyze content</span></span>
> - <span data-ttu-id="455b0-126">Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko prenašate spletno vsebino</span><span class="sxs-lookup"><span data-stu-id="455b0-126">Allow the use of connected experiences in Office that download online content</span></span>
> - <span data-ttu-id="455b0-127">Omogočanje uporabe dodatnih povezanih izkušenj v Officeu</span><span class="sxs-lookup"><span data-stu-id="455b0-127">Allow the use of additional optional connected experiences in Office</span></span>
>
> <span data-ttu-id="455b0-128">Nastavitve zasebnosti za Outlook za iOS in OneDrive za iOS lahko konfigurirate le s storitvijo Office politiko oblaka.</span><span class="sxs-lookup"><span data-stu-id="455b0-128">Privacy settings for Outlook for iOS and OneDrive for iOS can only be configured by using the Office cloud policy service.</span></span>
>
> <span data-ttu-id="455b0-129">Če želite več informacij o uporabi storitve pravilnika Office Cloud, si oglejte [pregled storitve pravilnika Office Cloud ](../overview-office-cloud-policy-service.md).</span><span class="sxs-lookup"><span data-stu-id="455b0-129">For more information on using the Office cloud policy service, see [Overview of the Office cloud policy service](../overview-office-cloud-policy-service.md).</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="455b0-130">Prednostna nastavitev za diagnostične podatke</span><span class="sxs-lookup"><span data-stu-id="455b0-130">Preference setting for diagnostic data</span></span>

<span data-ttu-id="455b0-131">Diagnostični podatki se uporabljajo za zaščito, posodobitev, zaznavanje težav in njihovo odpravljanje v Officeu ter za izboljšave izdelka.</span><span class="sxs-lookup"><span data-stu-id="455b0-131">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="455b0-132">Če želite več informacij, si oglejte [diagnostičnih podatkov, ki so bili poslani iz aplikacij Microsoft 365 za podjetja v Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="455b0-132">For more information, see [Diagnostic data sent from Microsoft 365 Apps for enterprise to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="455b0-133">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="455b0-133">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="455b0-134">**Vrsta podatkov**</span><span class="sxs-lookup"><span data-stu-id="455b0-134">**Data Type**</span></span>  | <span data-ttu-id="455b0-135">Niz</span><span class="sxs-lookup"><span data-stu-id="455b0-135">String</span></span> |
|<span data-ttu-id="455b0-136">**Možne vrednosti**</span><span class="sxs-lookup"><span data-stu-id="455b0-136">**Possible values**</span></span>  | <span data-ttu-id="455b0-137">`BasicDiagnosticData` *(s tem nastavite raven na možnost »Zahtevana«)*</span><span class="sxs-lookup"><span data-stu-id="455b0-137">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="455b0-138">`FullDiagnosticData` *(s tem nastavite raven na možnost »Izbirna«)*</span><span class="sxs-lookup"><span data-stu-id="455b0-138">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="455b0-139">`ZeroDiagnosticData` *(s tem nastavite raven na možnost »Nobena«)*</span><span class="sxs-lookup"><span data-stu-id="455b0-139">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |

<span data-ttu-id="455b0-140">Če te prednostne nastavitve ne nastavite, se Microsoftu pošljejo le zahtevani diagnostični podatki, če so uporabniki z naročnino na Office 365 (ali Microsoft 365) prijavljeni z delovnim ali šolskim računom.</span><span class="sxs-lookup"><span data-stu-id="455b0-140">If you don't set this preference, only required diagnostic data is sent to Microsoft if users with an Office 365 (or Microsoft 365) subscription are signed in with a work or school account.</span></span> <span data-ttu-id="455b0-141">Ti uporabniki ne morejo spremeniti ravni diagnostičnih podatkov, in sicer ne glede na to, kako nastavite to prednostno nastavitev.</span><span class="sxs-lookup"><span data-stu-id="455b0-141">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="455b0-142">V primeru drugih uporabnikov, kot so domači uporabniki z naročnino na Office 365 (ali Microsoft 365), Microsoft prejema samo zahtevane diagnostične podatke, razen če uporabnik v možnosti **Nastavitve** > **Zasebnost** izbere, da so poslani tudi izbirni diagnostični podatki.</span><span class="sxs-lookup"><span data-stu-id="455b0-142">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Settings** > **Privacy Settings**.</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="455b0-143">Prednostna nastavitev za povezane izkušnje, ki analizirajo vašo vsebino</span><span class="sxs-lookup"><span data-stu-id="455b0-143">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="455b0-144">Povezane Izkušnje, ki analizirajo vašo vsebino so izkušnje, ki na podlagi Officeove vsebine nudijo priporočila za načrte, predloge za urejanje, vpoglede v podatke in podobne funkcije.</span><span class="sxs-lookup"><span data-stu-id="455b0-144">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="455b0-145">Na primer »Ideje za oblikovanje« v PowerPointu.</span><span class="sxs-lookup"><span data-stu-id="455b0-145">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="455b0-146">Če si želite ogledati seznam povezanih izkušenj, glejte [Povezane izkušnje v Officeu](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="455b0-146">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="455b0-147">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="455b0-147">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="455b0-148">**Vrsta podatkov**</span><span class="sxs-lookup"><span data-stu-id="455b0-148">**Data Type**</span></span>  | <span data-ttu-id="455b0-149">Logični</span><span class="sxs-lookup"><span data-stu-id="455b0-149">Boolean</span></span> |
|<span data-ttu-id="455b0-150">**Možne vrednosti**</span><span class="sxs-lookup"><span data-stu-id="455b0-150">**Possible values**</span></span>  | <span data-ttu-id="455b0-151">`TRUE` *(omogočeno)*</span><span class="sxs-lookup"><span data-stu-id="455b0-151">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="455b0-152">`FALSE` *(onemogočeno)*</span><span class="sxs-lookup"><span data-stu-id="455b0-152">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="455b0-153">Če te prednostne nastavitve ne nastavite, so povezane izkušnje, ki analizirajo vsebino, na voljo za uporabnike.</span><span class="sxs-lookup"><span data-stu-id="455b0-153">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="455b0-154">Če ima uporabnik naročnino na Office 365 (ali Microsoft 365) in je vpisan s službenim ali šolskim računom, ne more izklopiti povezanih izkušenj, ki analizirajo vsebino.</span><span class="sxs-lookup"><span data-stu-id="455b0-154">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="455b0-155">Drugi uporabniki, kot so domači uporabniki z naročnino na Office 365 (ali Microsoft 365), lahko v možnosti **Nastavitve** > **Nastavitve zasebnosti** izklopijo povezane izkušnje, ki analizirajo vsebino.</span><span class="sxs-lookup"><span data-stu-id="455b0-155">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that analyze content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="455b0-156">Prednostna nastavitev za povezane izkušnje, s katerimi prenesete spletno vsebino</span><span class="sxs-lookup"><span data-stu-id="455b0-156">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="455b0-157">Povezane izkušnje, s katerimi prenesete spletno vsebino, so izkušnje, ki vam omogočajo, da poiščete in prenesete spletno vsebino, vključno s predlogami, slikami, videoposnetki in referenčnim gradivom, s katero izpopolnite svoje dokumente.</span><span class="sxs-lookup"><span data-stu-id="455b0-157">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="455b0-158">Na primer, Officeove predloge ali vstavljanje spletne ikone.</span><span class="sxs-lookup"><span data-stu-id="455b0-158">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="455b0-159">Če si želite ogledati seznam povezanih izkušenj, glejte [Povezane izkušnje v Officeu](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="455b0-159">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="455b0-160">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="455b0-160">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="455b0-161">**Vrsta podatkov**</span><span class="sxs-lookup"><span data-stu-id="455b0-161">**Data Type**</span></span>  | <span data-ttu-id="455b0-162">Logični</span><span class="sxs-lookup"><span data-stu-id="455b0-162">Boolean</span></span> |
|<span data-ttu-id="455b0-163">**Možne vrednosti**</span><span class="sxs-lookup"><span data-stu-id="455b0-163">**Possible values**</span></span>  | <span data-ttu-id="455b0-164">`TRUE` *(omogočeno)*</span><span class="sxs-lookup"><span data-stu-id="455b0-164">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="455b0-165">`FALSE` *(onemogočeno)*</span><span class="sxs-lookup"><span data-stu-id="455b0-165">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="455b0-166">Če te prednostne nastavitve ne nastavite, so povezane izkušnje, s katerimi prenesete spletno vsebino, na voljo uporabnikom.</span><span class="sxs-lookup"><span data-stu-id="455b0-166">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="455b0-167">Če ima uporabnik naročnino na Office 365 (ali Microsoft 365) in je vpisan s službenim ali šolskim računom, ne more izklopiti povezanih izkušenj, ki prenašajo spletno vsebino.</span><span class="sxs-lookup"><span data-stu-id="455b0-167">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="455b0-168">Drugi uporabniki, kot so domači uporabniki z naročnino na Office 365 (ali Microsoft 365), lahko v možnosti **Nastavitve** > **Nastavitve zasebnosti** izklopijo povezane izkušnje, ki prenašajo spletno vsebino.</span><span class="sxs-lookup"><span data-stu-id="455b0-168">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that download online content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="455b0-169">Prednostna nastavitev za izbirne povezane izkušnje</span><span class="sxs-lookup"><span data-stu-id="455b0-169">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="455b0-170">Poleg povezanih izkušenj, omenjenih v tem članku, lahko izbirate še med dodatnimi izbirnimi povezanimi izkušnjami, s katerimi lahko vaši uporabniki dostopajo do svojih računov organizacije, imenovanih tudi službeni ali šolski računi.</span><span class="sxs-lookup"><span data-stu-id="455b0-170">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="455b0-171">Na primer, dodatki za Office, ki so preneseni prek Trgovine Office v napravo.</span><span class="sxs-lookup"><span data-stu-id="455b0-171">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="455b0-172">Če si želite ogledati več primerov, preberite [Pregled izbirnih povezanih izkušenj v Officeu](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="455b0-172">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="455b0-173">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="455b0-173">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="455b0-174">**Vrsta podatkov**</span><span class="sxs-lookup"><span data-stu-id="455b0-174">**Data Type**</span></span>  | <span data-ttu-id="455b0-175">Logični</span><span class="sxs-lookup"><span data-stu-id="455b0-175">Boolean</span></span> |
|<span data-ttu-id="455b0-176">**Možne vrednosti**</span><span class="sxs-lookup"><span data-stu-id="455b0-176">**Possible values**</span></span>  | <span data-ttu-id="455b0-177">`TRUE` *(omogočeno)*</span><span class="sxs-lookup"><span data-stu-id="455b0-177">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="455b0-178">`FALSE` *(onemogočeno)*</span><span class="sxs-lookup"><span data-stu-id="455b0-178">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="455b0-179">Če te prednostne nastavitve ne nastavite, so izbirne povezane izkušnje na voljo uporabnikom z naročnino na Office 365 (ali Microsoft 365), ki so vpisani s službenim ali šolskim računom.</span><span class="sxs-lookup"><span data-stu-id="455b0-179">If you don't set this preference, optional connected experiences are available to users with an Office 365 (or Microsoft 365) subscription that are signed in with a work or school account.</span></span> <span data-ttu-id="455b0-180">Če te prednostne nastavitve ne nastavite na NAPAČNO, lahko ti uporabniki v možnosti **Nastavitve** > **Nastavitve zasebnosti** izklopijo izbirne povezane izkušnje.</span><span class="sxs-lookup"><span data-stu-id="455b0-180">Unless you have set this preference to FALSE, these users can choose to turn off optional connected experiences by going to **Settings** > **Privacy Settings**.</span></span>

<span data-ttu-id="455b0-181">Če želite drugim uporabnikom, kot so domači uporabniki z naročnino na Office 365 (ali Microsoft 365), ne morete izklopiti izbirnih povezanih izkušenj.</span><span class="sxs-lookup"><span data-stu-id="455b0-181">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, there isn't an option to turn off optional connected experiences.</span></span>