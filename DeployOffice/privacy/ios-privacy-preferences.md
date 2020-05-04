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
ms.openlocfilehash: 40fc1ec1f5b2abc587e1b5224dc7fe0a5a656f33
ms.sourcegitcommit: 3890a23390edd0b5fdb2cf33613ec0778566cf97
ms.translationtype: HT
ms.contentlocale: sl-SI
ms.lasthandoff: 05/01/2020
ms.locfileid: "43992122"
---
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="c275a-103">Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom iOS</span><span class="sxs-lookup"><span data-stu-id="c275a-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

<span data-ttu-id="c275a-104">Na voljo so nove prednostne nastavitve za Office v napravah s sistemom iOS, s katerimi lahko nadzorujete nastavitve, povezane z naslednjo vsebino:</span><span class="sxs-lookup"><span data-stu-id="c275a-104">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="c275a-105">***Diagnostični podatki*** o uporabljeni programski opremi odjemalca za Office, ki jih je sistem zbral in poslal Microsoftu.</span><span class="sxs-lookup"><span data-stu-id="c275a-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="c275a-106">***Povezane izkušnje***, ki za omogočanje razširjenih Officeovih funkcij uporabljajo storitve v oblaku.</span><span class="sxs-lookup"><span data-stu-id="c275a-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="c275a-107">Če želite več informacij o diagnostičnih podatkih in povezanih izkušnjah, preberite članek [Pregled kontrolnikov zasebnosti](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="c275a-107">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

<span data-ttu-id="c275a-108">Te prednostne nastavitve se nanašajo na naslednje aplikacije:</span><span class="sxs-lookup"><span data-stu-id="c275a-108">These preference settings apply to the following applications:</span></span>
- <span data-ttu-id="c275a-109">Različica 2.30 in poznejše različice programov Word za iOS, Excel za iOS in PowerPoint za iOS.</span><span class="sxs-lookup"><span data-stu-id="c275a-109">Version 2.30 and later of Word for iOS, Excel for iOS, and PowerPoint for iOS.</span></span>
- <span data-ttu-id="c275a-110">Različica 16.30 in novejša različica programa OneNote za iOS.</span><span class="sxs-lookup"><span data-stu-id="c275a-110">Version 16.30 and later of OneNote for iOS.</span></span>
- <span data-ttu-id="c275a-111">Različica 1.17 in novejša različica programa Visio Viewer za iOS.</span><span class="sxs-lookup"><span data-stu-id="c275a-111">Version 1.17 and later of Visio Viewer for iOS.</span></span>

> [!NOTE]
> <span data-ttu-id="c275a-112">Če želite več informacij o podobnih nastavitvah za Office v računalnikih s sistemom macOS, preberite članek [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office for Mac](mac-privacy-preferences.md)</span><span class="sxs-lookup"><span data-stu-id="c275a-112">For information about similar settings for Office on computers running macOS, see [Use preferences to manage privacy controls for Office for Mac](mac-privacy-preferences.md)</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="c275a-113">Nastavljanje nastavitev naprave</span><span class="sxs-lookup"><span data-stu-id="c275a-113">Setting device preferences</span></span>
<span data-ttu-id="c275a-114">Te nove prednostne nastavitve lahko nastavite tudi na ravni naprave s strežnikom Upravljanje mobilnih naprav (MDM), ko je nameščena Officeova aplikacija.</span><span class="sxs-lookup"><span data-stu-id="c275a-114">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="c275a-115">Mnogi strežniki MDM skrbnikom za IT omogočajo, da dodajo izbirni konfiguracijski slovar, ko strežnik pošlje `InstallApplication` ukaz MDM v napravo s sistemom iOS.</span><span class="sxs-lookup"><span data-stu-id="c275a-115">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="c275a-116">Če želite več informacij, si oglejte dokumentacijo strežnika MDM.</span><span class="sxs-lookup"><span data-stu-id="c275a-116">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="c275a-117">Slovar je predstavljen kot nabor parov ključev/vrednosti v obliki zapisa datoteke XML.</span><span class="sxs-lookup"><span data-stu-id="c275a-117">The dictionary is represented as a set of key/value pairs in XML format.</span></span> <span data-ttu-id="c275a-118">Na primer:</span><span class="sxs-lookup"><span data-stu-id="c275a-118">For example:</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="c275a-119">Ko ga pošljete napravi, bo konfiguracijski slovar shranjen pod `com.apple.managed.configuration` ključem, kjer bo prebran ob zagonu Officeove aplikacije.</span><span class="sxs-lookup"><span data-stu-id="c275a-119">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

> [!NOTE]
> <span data-ttu-id="c275a-120">Uporabite lahko tudi storitev pravilnika za Office Cloud in te nastavitve za 4 pravilnikov:</span><span class="sxs-lookup"><span data-stu-id="c275a-120">You can also use the Office cloud policy service and these 4 policy settings:</span></span>
> - <span data-ttu-id="c275a-121">Konfiguracija ravni diagnostičnih podatkov o programski opremi odjemalca, ki jih Office pošlje Microsoftu</span><span class="sxs-lookup"><span data-stu-id="c275a-121">Configure the level of client software diagnostic data sent by Office to Microsoft</span></span>
> - <span data-ttu-id="c275a-122">Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko analizirate vsebino</span><span class="sxs-lookup"><span data-stu-id="c275a-122">Allow the use of connected experiences in Office that analyze content</span></span>
> - <span data-ttu-id="c275a-123">Dovoli uporabo povezanih izkušenj v Officeu, s katerimi lahko prenašate spletno vsebino</span><span class="sxs-lookup"><span data-stu-id="c275a-123">Allow the use of connected experiences in Office that download online content</span></span>
> - <span data-ttu-id="c275a-124">Omogočanje uporabe dodatnih povezanih izkušenj v Officeu</span><span class="sxs-lookup"><span data-stu-id="c275a-124">Allow the use of additional optional connected experiences in Office</span></span>
>
> <span data-ttu-id="c275a-125">Če želite več informacij o uporabi storitve pravilnika Office Cloud, si oglejte [pregled storitve pravilnika Office Cloud ](../overview-office-cloud-policy-service.md).</span><span class="sxs-lookup"><span data-stu-id="c275a-125">For more information on using the Office cloud policy service, see [Overview of the Office cloud policy service](../overview-office-cloud-policy-service.md).</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="c275a-126">Prednostna nastavitev za diagnostične podatke</span><span class="sxs-lookup"><span data-stu-id="c275a-126">Preference setting for diagnostic data</span></span>

<span data-ttu-id="c275a-127">Diagnostični podatki se uporabljajo za zaščito, posodobitev, zaznavanje težav in njihovo odpravljanje v Officeu ter za izboljšave izdelka.</span><span class="sxs-lookup"><span data-stu-id="c275a-127">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="c275a-128">Če želite več informacij, si oglejte [diagnostičnih podatkov, ki so bili poslani iz aplikacij Microsoft 365 za podjetja v Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="c275a-128">For more information, see [Diagnostic data sent from Microsoft 365 Apps for enterprise to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-microsoft-365-apps-for-enterprise-to-microsoft).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c275a-129">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="c275a-129">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="c275a-130">**Vrsta podatkov**</span><span class="sxs-lookup"><span data-stu-id="c275a-130">**Data Type**</span></span>  | <span data-ttu-id="c275a-131">Niz</span><span class="sxs-lookup"><span data-stu-id="c275a-131">String</span></span> |
|<span data-ttu-id="c275a-132">**Možne vrednosti**</span><span class="sxs-lookup"><span data-stu-id="c275a-132">**Possible values**</span></span>  | <span data-ttu-id="c275a-133">`BasicDiagnosticData` *(s tem nastavite raven na možnost »Zahtevana«)*</span><span class="sxs-lookup"><span data-stu-id="c275a-133">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="c275a-134">`FullDiagnosticData` *(s tem nastavite raven na možnost »Izbirna«)*</span><span class="sxs-lookup"><span data-stu-id="c275a-134">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="c275a-135">`ZeroDiagnosticData` *(s tem nastavite raven na možnost »Nobena«)*</span><span class="sxs-lookup"><span data-stu-id="c275a-135">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |

<span data-ttu-id="c275a-136">Če te prednostne nastavitve ne nastavite, se Microsoftu pošljejo le zahtevani diagnostični podatki, če so uporabniki z naročnino na Office 365 (ali Microsoft 365) prijavljeni z delovnim ali šolskim računom.</span><span class="sxs-lookup"><span data-stu-id="c275a-136">If you don't set this preference, only required diagnostic data is sent to Microsoft if users with an Office 365 (or Microsoft 365) subscription are signed in with a work or school account.</span></span> <span data-ttu-id="c275a-137">Ti uporabniki ne morejo spremeniti ravni diagnostičnih podatkov, in sicer ne glede na to, kako nastavite to prednostno nastavitev.</span><span class="sxs-lookup"><span data-stu-id="c275a-137">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="c275a-138">V primeru drugih uporabnikov, kot so domači uporabniki z naročnino na Office 365 (ali Microsoft 365), Microsoft prejema samo zahtevane diagnostične podatke, razen če uporabnik v možnosti **Nastavitve** > **Zasebnost** izbere, da so poslani tudi izbirni diagnostični podatki.</span><span class="sxs-lookup"><span data-stu-id="c275a-138">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Settings** > **Privacy Settings**.</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="c275a-139">Prednostna nastavitev za povezane izkušnje, ki analizirajo vašo vsebino</span><span class="sxs-lookup"><span data-stu-id="c275a-139">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="c275a-140">Povezane Izkušnje, ki analizirajo vašo vsebino so izkušnje, ki na podlagi Officeove vsebine nudijo priporočila za načrte, predloge za urejanje, vpoglede v podatke in podobne funkcije.</span><span class="sxs-lookup"><span data-stu-id="c275a-140">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="c275a-141">Na primer »Ideje za oblikovanje« v PowerPointu.</span><span class="sxs-lookup"><span data-stu-id="c275a-141">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="c275a-142">Če si želite ogledati seznam povezanih izkušenj, glejte [Povezane izkušnje v Officeu](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="c275a-142">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c275a-143">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="c275a-143">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="c275a-144">**Vrsta podatkov**</span><span class="sxs-lookup"><span data-stu-id="c275a-144">**Data Type**</span></span>  | <span data-ttu-id="c275a-145">Logični</span><span class="sxs-lookup"><span data-stu-id="c275a-145">Boolean</span></span> |
|<span data-ttu-id="c275a-146">**Možne vrednosti**</span><span class="sxs-lookup"><span data-stu-id="c275a-146">**Possible values**</span></span>  | <span data-ttu-id="c275a-147">`TRUE` *(omogočeno)*</span><span class="sxs-lookup"><span data-stu-id="c275a-147">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="c275a-148">`FALSE` *(onemogočeno)*</span><span class="sxs-lookup"><span data-stu-id="c275a-148">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="c275a-149">Če te prednostne nastavitve ne nastavite, so povezane izkušnje, ki analizirajo vsebino, na voljo za uporabnike.</span><span class="sxs-lookup"><span data-stu-id="c275a-149">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="c275a-150">Če ima uporabnik naročnino na Office 365 (ali Microsoft 365) in je vpisan s službenim ali šolskim računom, ne more izklopiti povezanih izkušenj, ki analizirajo vsebino.</span><span class="sxs-lookup"><span data-stu-id="c275a-150">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="c275a-151">Drugi uporabniki, kot so domači uporabniki z naročnino na Office 365 (ali Microsoft 365), lahko v možnosti **Nastavitve** > **Nastavitve zasebnosti** izklopijo povezane izkušnje, ki analizirajo vsebino.</span><span class="sxs-lookup"><span data-stu-id="c275a-151">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that analyze content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="c275a-152">Prednostna nastavitev za povezane izkušnje, s katerimi prenesete spletno vsebino</span><span class="sxs-lookup"><span data-stu-id="c275a-152">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="c275a-153">Povezane izkušnje, s katerimi prenesete spletno vsebino, so izkušnje, ki vam omogočajo, da poiščete in prenesete spletno vsebino, vključno s predlogami, slikami, videoposnetki in referenčnim gradivom, s katero izpopolnite svoje dokumente.</span><span class="sxs-lookup"><span data-stu-id="c275a-153">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="c275a-154">Na primer, Officeove predloge ali vstavljanje spletne ikone.</span><span class="sxs-lookup"><span data-stu-id="c275a-154">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="c275a-155">Če si želite ogledati seznam povezanih izkušenj, glejte [Povezane izkušnje v Officeu](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="c275a-155">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c275a-156">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="c275a-156">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="c275a-157">**Vrsta podatkov**</span><span class="sxs-lookup"><span data-stu-id="c275a-157">**Data Type**</span></span>  | <span data-ttu-id="c275a-158">Logični</span><span class="sxs-lookup"><span data-stu-id="c275a-158">Boolean</span></span> |
|<span data-ttu-id="c275a-159">**Možne vrednosti**</span><span class="sxs-lookup"><span data-stu-id="c275a-159">**Possible values**</span></span>  | <span data-ttu-id="c275a-160">`TRUE` *(omogočeno)*</span><span class="sxs-lookup"><span data-stu-id="c275a-160">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="c275a-161">`FALSE` *(onemogočeno)*</span><span class="sxs-lookup"><span data-stu-id="c275a-161">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="c275a-162">Če te prednostne nastavitve ne nastavite, so povezane izkušnje, s katerimi prenesete spletno vsebino, na voljo uporabnikom.</span><span class="sxs-lookup"><span data-stu-id="c275a-162">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="c275a-163">Če ima uporabnik naročnino na Office 365 (ali Microsoft 365) in je vpisan s službenim ali šolskim računom, ne more izklopiti povezanih izkušenj, ki prenašajo spletno vsebino.</span><span class="sxs-lookup"><span data-stu-id="c275a-163">If the user has an Office 365 (or Microsoft 365) subscription and is signed in with a work or school account, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="c275a-164">Drugi uporabniki, kot so domači uporabniki z naročnino na Office 365 (ali Microsoft 365), lahko v možnosti **Nastavitve** > **Nastavitve zasebnosti** izklopijo povezane izkušnje, ki prenašajo spletno vsebino.</span><span class="sxs-lookup"><span data-stu-id="c275a-164">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, the user can choose to turn off connected experiences that download online content by going to **Settings** > **Privacy Settings**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="c275a-165">Prednostna nastavitev za izbirne povezane izkušnje</span><span class="sxs-lookup"><span data-stu-id="c275a-165">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="c275a-166">Poleg povezanih izkušenj, omenjenih v tem članku, lahko izbirate še med dodatnimi izbirnimi povezanimi izkušnjami, s katerimi lahko vaši uporabniki dostopajo do svojih računov organizacije, imenovanih tudi službeni ali šolski računi.</span><span class="sxs-lookup"><span data-stu-id="c275a-166">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="c275a-167">Na primer, dodatki za Office, ki so preneseni prek Trgovine Office v napravo.</span><span class="sxs-lookup"><span data-stu-id="c275a-167">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="c275a-168">Če si želite ogledati več primerov, preberite [Pregled izbirnih povezanih izkušenj v Officeu](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="c275a-168">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c275a-169">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="c275a-169">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="c275a-170">**Vrsta podatkov**</span><span class="sxs-lookup"><span data-stu-id="c275a-170">**Data Type**</span></span>  | <span data-ttu-id="c275a-171">Logični</span><span class="sxs-lookup"><span data-stu-id="c275a-171">Boolean</span></span> |
|<span data-ttu-id="c275a-172">**Možne vrednosti**</span><span class="sxs-lookup"><span data-stu-id="c275a-172">**Possible values**</span></span>  | <span data-ttu-id="c275a-173">`TRUE` *(omogočeno)*</span><span class="sxs-lookup"><span data-stu-id="c275a-173">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="c275a-174">`FALSE` *(onemogočeno)*</span><span class="sxs-lookup"><span data-stu-id="c275a-174">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="c275a-175">Če te prednostne nastavitve ne nastavite, so izbirne povezane izkušnje na voljo uporabnikom z naročnino na Office 365 (ali Microsoft 365), ki so vpisani s službenim ali šolskim računom.</span><span class="sxs-lookup"><span data-stu-id="c275a-175">If you don't set this preference, optional connected experiences are available to users with an Office 365 (or Microsoft 365) subscription that are signed in with a work or school account.</span></span> <span data-ttu-id="c275a-176">Če te prednostne nastavitve ne nastavite na NAPAČNO, lahko ti uporabniki v možnosti **Nastavitve** > **Nastavitve zasebnosti** izklopijo izbirne povezane izkušnje.</span><span class="sxs-lookup"><span data-stu-id="c275a-176">Unless you have set this preference to FALSE, these users can choose to turn off optional connected experiences by going to **Settings** > **Privacy Settings**.</span></span>

<span data-ttu-id="c275a-177">Če želite drugim uporabnikom, kot so domači uporabniki z naročnino na Office 365 (ali Microsoft 365), ne morete izklopiti izbirnih povezanih izkušenj.</span><span class="sxs-lookup"><span data-stu-id="c275a-177">For other users, such as home users with an Office 365 (or Microsoft 365) subscription, there isn't an option to turn off optional connected experiences.</span></span>