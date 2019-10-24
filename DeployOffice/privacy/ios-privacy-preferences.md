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
# <a name="use-preferences-to-manage-privacy-controls-for-office-on-ios-devices"></a><span data-ttu-id="54b34-103">Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom iOS</span><span class="sxs-lookup"><span data-stu-id="54b34-103">Use preferences to manage privacy controls for Office on iOS devices</span></span>

<span data-ttu-id="54b34-104">Na voljo so nove prednostne nastavitve za Office v napravah s sistemom iOS, s katerimi lahko nadzorujete nastavitve, povezane z naslednjo vsebino:</span><span class="sxs-lookup"><span data-stu-id="54b34-104">There are new preference settings for Office on iOS devices that allow you to control settings related to the following:</span></span>

- <span data-ttu-id="54b34-105">***Diagnostični podatki*** o uporabljeni programski opremi odjemalca za Office, ki jih je sistem zbral in poslal Microsoftu.</span><span class="sxs-lookup"><span data-stu-id="54b34-105">***Diagnostic data*** that is collected and sent to Microsoft about Office client software being used.</span></span>

- <span data-ttu-id="54b34-106">***Povezane izkušnje***, ki za omogočanje razširjenih Officeovih funkcij uporabljajo storitve v oblaku.</span><span class="sxs-lookup"><span data-stu-id="54b34-106">***Connected experiences*** that use cloud-based functionality to provide enhanced Office features to you and your users.</span></span>

<span data-ttu-id="54b34-107">Če želite več informacij o diagnostičnih podatkih in povezanih izkušnjah, preberite članek [Pregled kontrolnikov zasebnosti](overview-privacy-controls.md).</span><span class="sxs-lookup"><span data-stu-id="54b34-107">For more information about diagnostic data and connected experiences, see [Overview of privacy controls](overview-privacy-controls.md).</span></span>

<span data-ttu-id="54b34-108">Te prednostne nastavitve se nanašajo na naslednje aplikacije:</span><span class="sxs-lookup"><span data-stu-id="54b34-108">These preference settings apply to the following applications:</span></span>
- <span data-ttu-id="54b34-109">Različica 2.30 in poznejše različice programov Word za iOS, Excel za iOS in PowerPoint za iOS.</span><span class="sxs-lookup"><span data-stu-id="54b34-109">Version 2.30 and later of Word for iOS, Excel for iOS, and PowerPoint for iOS.</span></span>
- <span data-ttu-id="54b34-110">Različica 16.30 in novejša različica programa OneNote za iOS.</span><span class="sxs-lookup"><span data-stu-id="54b34-110">Version 16.30 and later of OneNote for iOS.</span></span>
- <span data-ttu-id="54b34-111">Različica 1.17 in novejša različica programa Visio Viewer za iOS.</span><span class="sxs-lookup"><span data-stu-id="54b34-111">Version 1.17 and later of Visio Viewer for iOS.</span></span>

> [!NOTE]
> <span data-ttu-id="54b34-112">Če želite več informacij o podobnih nastavitvah za Office v računalnikih s sistemom macOS, preberite članek [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office for Mac](mac-privacy-preferences.md)</span><span class="sxs-lookup"><span data-stu-id="54b34-112">For information about similar settings for Office on computers running Windows, see [Use policy settings to manage privacy controls for Office 365 ProPlus](mac-privacy-preferences.md).</span></span>


## <a name="setting-device-preferences"></a><span data-ttu-id="54b34-113">Nastavljanje nastavitev naprave</span><span class="sxs-lookup"><span data-stu-id="54b34-113">Setting device preferences</span></span>
<span data-ttu-id="54b34-114">Te nove prednostne nastavitve lahko nastavite tudi na ravni naprave s strežnikom Upravljanje mobilnih naprav (MDM), ko je nameščena Officeova aplikacija.</span><span class="sxs-lookup"><span data-stu-id="54b34-114">These new preference settings can also be set at the device level by a Mobile Device Management (MDM) server when the Office application is installed.</span></span> <span data-ttu-id="54b34-115">Mnogi strežniki MDM skrbnikom za IT omogočajo, da dodajo izbirni konfiguracijski slovar, ko strežnik pošlje `InstallApplication` ukaz MDM v napravo s sistemom iOS.</span><span class="sxs-lookup"><span data-stu-id="54b34-115">Many MDM servers allow IT administrators to add an optional configuration dictionary when the server sends the `InstallApplication` MDM command to an iOS device.</span></span> <span data-ttu-id="54b34-116">Če želite več informacij, si oglejte dokumentacijo strežnika MDM.</span><span class="sxs-lookup"><span data-stu-id="54b34-116">Refer to your MDM server documentation for more details.</span></span>

<span data-ttu-id="54b34-117">Slovar je predstavljen kot nabor parov ključev/vrednosti v obliki zapisa datoteke XML.</span><span class="sxs-lookup"><span data-stu-id="54b34-117">The dictionary is represented as a set of key/value pairs in XML format.</span></span> <span data-ttu-id="54b34-118">Na primer:</span><span class="sxs-lookup"><span data-stu-id="54b34-118">For example, DuplicateDomain-GUIDcontoso.com.</span></span>

```xml
<dict>
    <key>DiagnosticDataTypePreference</key>
    <string>BasicDiagnosticData</string>
</dict>
```

<span data-ttu-id="54b34-119">Ko ga pošljete napravi, bo konfiguracijski slovar shranjen pod `com.apple.managed.configuration` ključem, kjer bo prebran ob zagonu Officeove aplikacije.</span><span class="sxs-lookup"><span data-stu-id="54b34-119">Once sent to the device, the configuration dictionary will reside under the `com.apple.managed.configuration` key, where it will be read when the Office application is launched.</span></span>

## <a name="preference-setting-for-diagnostic-data"></a><span data-ttu-id="54b34-120">Prednostna nastavitev za diagnostične podatke</span><span class="sxs-lookup"><span data-stu-id="54b34-120">Preference setting for diagnostic data</span></span>

<span data-ttu-id="54b34-121">Diagnostični podatki se uporabljajo za zaščito, posodobitev, zaznavanje težav in njihovo odpravljanje v Officeu ter za izboljšave izdelka.</span><span class="sxs-lookup"><span data-stu-id="54b34-121">Diagnostic data is used to keep Office secure and up-to-date, detect, diagnose and remediate problems, and also make product improvements.</span></span> <span data-ttu-id="54b34-122">Če želite več informacij, preberite članek [Diagnostični podatki, poslani Microsoftu iz storitve Office 365 ProPlus](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).</span><span class="sxs-lookup"><span data-stu-id="54b34-122">For more information, see [Diagnostic data sent from Office 365 ProPlus to Microsoft](overview-privacy-controls.md#diagnostic-data-sent-from-office-365-proplus-to-microsoft).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="54b34-123">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="54b34-123">**Key**</span></span>  | `DiagnosticDataTypePreference`  |
|<span data-ttu-id="54b34-124">**Vrsta podatkov**</span><span class="sxs-lookup"><span data-stu-id="54b34-124">**Data Type**</span></span>  | <span data-ttu-id="54b34-125">Niz</span><span class="sxs-lookup"><span data-stu-id="54b34-125">String</span></span> |
|<span data-ttu-id="54b34-126">**Možne vrednosti**</span><span class="sxs-lookup"><span data-stu-id="54b34-126">**Possible values**</span></span>  | <span data-ttu-id="54b34-127">`BasicDiagnosticData` *(s tem nastavite raven na možnost »Zahtevana«)*</span><span class="sxs-lookup"><span data-stu-id="54b34-127">`BasicDiagnosticData` *(this sets the level to Required)*</span></span> <br/> <span data-ttu-id="54b34-128">`FullDiagnosticData` *(s tem nastavite raven na možnost »Izbirna«)*</span><span class="sxs-lookup"><span data-stu-id="54b34-128">`FullDiagnosticData` *(this sets the level to Optional)*</span></span> <br/> <span data-ttu-id="54b34-129">`ZeroDiagnosticData` *(s tem nastavite raven na možnost »Nobena«)*</span><span class="sxs-lookup"><span data-stu-id="54b34-129">`ZeroDiagnosticData` *(this sets the level to Neither)*</span></span> |

<span data-ttu-id="54b34-130">Če te prednostne nastavitve ne nastavite, se Microsoftu pošljejo le zahtevani diagnostični podatki, če so uporabniki z naročnino na Office 365 prijavljeni z delovnim ali šolskim računom.</span><span class="sxs-lookup"><span data-stu-id="54b34-130">Starting with new installations of Version 16.30, if you don't set this preference, only required diagnostic data is sent to Microsoft if users with an Office 365 subscription are signed in with a work or school account or if users have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="54b34-131">Ti uporabniki ne morejo spremeniti ravni diagnostičnih podatkov, in sicer ne glede na to, kako nastavite to prednostno nastavitev.</span><span class="sxs-lookup"><span data-stu-id="54b34-131">Also, these users can't change the level of diagnostic data regardless of how you set this preference.</span></span>

<span data-ttu-id="54b34-132">V primeru drugih uporabnikov, kot so domači uporabniki z naročnino na Office 365, Microsoft prejema samo zahtevane diagnostične podatke, razen če uporabnik v možnosti **Nastavitve** > **Zasebnost** izbere, da so poslani tudi izbirni diagnostični podatki.</span><span class="sxs-lookup"><span data-stu-id="54b34-132">For other users, such as home users with an Office 365 subscription, only required diagnostic data is sent, unless the user chooses to also send optional diagnostic data by going to **Preferences** > **Privacy**.</span></span>


## <a name="preference-setting-for-connected-experiences-that-analyze-your-content"></a><span data-ttu-id="54b34-133">Prednostna nastavitev za povezane izkušnje, ki analizirajo vašo vsebino</span><span class="sxs-lookup"><span data-stu-id="54b34-133">Preference setting for connected experiences that analyze your content</span></span>

<span data-ttu-id="54b34-134">Povezane Izkušnje, ki analizirajo vašo vsebino so izkušnje, ki na podlagi Officeove vsebine nudijo priporočila za načrte, predloge za urejanje, vpoglede v podatke in podobne funkcije.</span><span class="sxs-lookup"><span data-stu-id="54b34-134">Connected experiences that analyze your content are experiences that use your Office content to provide you with design recommendations, editing suggestions, data insights, and similar features.</span></span> <span data-ttu-id="54b34-135">Na primer »Ideje za oblikovanje« v PowerPointu.</span><span class="sxs-lookup"><span data-stu-id="54b34-135">For example, Design Ideas in PowerPoint.</span></span> <span data-ttu-id="54b34-136">Če si želite ogledati seznam povezanih izkušenj, glejte [Povezane izkušnje v Officeu](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="54b34-136">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="54b34-137">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="54b34-137">**Key**</span></span>  | `OfficeExperiencesAnalyzingContentPreference`  |
|<span data-ttu-id="54b34-138">**Vrsta podatkov**</span><span class="sxs-lookup"><span data-stu-id="54b34-138">**Data Type**</span></span>  | <span data-ttu-id="54b34-139">Logični</span><span class="sxs-lookup"><span data-stu-id="54b34-139">Boolean</span></span> |
|<span data-ttu-id="54b34-140">**Možne vrednosti**</span><span class="sxs-lookup"><span data-stu-id="54b34-140">**Possible values**</span></span>  | <span data-ttu-id="54b34-141">`TRUE` *(omogočeno)*</span><span class="sxs-lookup"><span data-stu-id="54b34-141">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="54b34-142">`FALSE` *(onemogočeno)*</span><span class="sxs-lookup"><span data-stu-id="54b34-142">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="54b34-143">Če te prednostne nastavitve ne nastavite, so povezane izkušnje, ki analizirajo vsebino, na voljo za uporabnike.</span><span class="sxs-lookup"><span data-stu-id="54b34-143">If you don't set this preference, connected experiences that analyze content are available to users.</span></span>

<span data-ttu-id="54b34-144">Če ima uporabnik naročnino na Office 365 in je vpisan s službenim ali šolskim računom, ne more izklopiti povezanih izkušenj, ki analizirajo vsebino.</span><span class="sxs-lookup"><span data-stu-id="54b34-144">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that analyze content.</span></span>

<span data-ttu-id="54b34-145">Drugi uporabniki, kot so domači uporabniki z naročnino na Office 365, lahko v možnosti **Nastavitve** > **Zasebnost** izklopijo povezane izkušnje, ki analizirajo vsebino.</span><span class="sxs-lookup"><span data-stu-id="54b34-145">For other users, such as home users with an Office 365 subscription, the user can choose to turn off connected experiences that analyze content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-connected-experiences-that-download-online-content"></a><span data-ttu-id="54b34-146">Prednostna nastavitev za povezane izkušnje, s katerimi prenesete spletno vsebino</span><span class="sxs-lookup"><span data-stu-id="54b34-146">Preference setting for connected experiences that download online content</span></span>

<span data-ttu-id="54b34-147">Povezane izkušnje, s katerimi prenesete spletno vsebino, so izkušnje, ki vam omogočajo, da poiščete in prenesete spletno vsebino, vključno s predlogami, slikami, videoposnetki in referenčnim gradivom, s katero izpopolnite svoje dokumente.</span><span class="sxs-lookup"><span data-stu-id="54b34-147">Connected experiences that download online content are experiences that allow you to search and download online content including templates, images, 3D models, videos, and reference materials to enhance your documents.</span></span> <span data-ttu-id="54b34-148">Na primer, Officeove predloge ali vstavljanje spletne ikone.</span><span class="sxs-lookup"><span data-stu-id="54b34-148">For example, Office templates or inserting an online icon.</span></span> <span data-ttu-id="54b34-149">Če si želite ogledati seznam povezanih izkušenj, glejte [Povezane izkušnje v Officeu](connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="54b34-149">For a list of these connected experiences, see [Connected experiences in Office](connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="54b34-150">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="54b34-150">**Key**</span></span>  | `OfficeExperiencesDownloadingContentPreference`  |
|<span data-ttu-id="54b34-151">**Vrsta podatkov**</span><span class="sxs-lookup"><span data-stu-id="54b34-151">**Data Type**</span></span>  | <span data-ttu-id="54b34-152">Logični</span><span class="sxs-lookup"><span data-stu-id="54b34-152">Boolean</span></span> |
|<span data-ttu-id="54b34-153">**Možne vrednosti**</span><span class="sxs-lookup"><span data-stu-id="54b34-153">**Possible values**</span></span>  | <span data-ttu-id="54b34-154">`TRUE` *(omogočeno)*</span><span class="sxs-lookup"><span data-stu-id="54b34-154">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="54b34-155">`FALSE` *(onemogočeno)*</span><span class="sxs-lookup"><span data-stu-id="54b34-155">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="54b34-156">Če te prednostne nastavitve ne nastavite, so povezane izkušnje, s katerimi prenesete spletno vsebino, na voljo uporabnikom.</span><span class="sxs-lookup"><span data-stu-id="54b34-156">If you don't set this preference, connected experiences that download online content are available to users.</span></span>

<span data-ttu-id="54b34-157">Če ima uporabnik naročnino na Office 365 in je vpisan s službenim ali šolskim računom, ne more izklopiti povezanih izkušenj, s katerimi prenesejo spletno vsebino.</span><span class="sxs-lookup"><span data-stu-id="54b34-157">If the user has an Office 365 subscription and is signed in with a work or school account or if the user has a volume licensed version of Office 2019 for Mac, then the user can't turn off connected experiences that download online content.</span></span>

<span data-ttu-id="54b34-158">Drugi uporabniki, kot so domači uporabniki z naročnino na Office 365, lahko v možnosti **Nastavitve** > **Zasebnost** izklopijo povezane izkušnje, s katerimi prenesejo spletno vsebino.</span><span class="sxs-lookup"><span data-stu-id="54b34-158">For other users, such as home users with an Office 365 subscription, a user can choose to turn off connected experiences that download online content by going to **Preferences** > **Privacy**.</span></span>

## <a name="preference-setting-for-optional-connected-experiences"></a><span data-ttu-id="54b34-159">Prednostna nastavitev za izbirne povezane izkušnje</span><span class="sxs-lookup"><span data-stu-id="54b34-159">Preference setting for optional connected experiences</span></span>

<span data-ttu-id="54b34-160">Poleg povezanih izkušenj, omenjenih v tem članku, lahko izbirate še med dodatnimi izbirnimi povezanimi izkušnjami, s katerimi lahko vaši uporabniki dostopajo do svojih računov organizacije, imenovanih tudi službeni ali šolski računi.</span><span class="sxs-lookup"><span data-stu-id="54b34-160">In addition to the connected experiences mentioned above, there are some optional connected experiences that you may choose to allow your users to access with their organization account, which is sometimes referred to as a work or school account.</span></span> <span data-ttu-id="54b34-161">Na primer, dodatki za Office, ki so preneseni prek Trgovine Office v napravo.</span><span class="sxs-lookup"><span data-stu-id="54b34-161">For example, Office add-ins that are downloaded through the Office Store to your device.</span></span> <span data-ttu-id="54b34-162">Če si želite ogledati več primerov, preberite [Pregled izbirnih povezanih izkušenj v Officeu](optional-connected-experiences.md).</span><span class="sxs-lookup"><span data-stu-id="54b34-162">For more examples, see [Overview of optional connected experiences in Office](optional-connected-experiences.md).</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="54b34-163">**Ključ**</span><span class="sxs-lookup"><span data-stu-id="54b34-163">**Key**</span></span>  | `OptionalConnectedExperiencesPreference`  |
|<span data-ttu-id="54b34-164">**Vrsta podatkov**</span><span class="sxs-lookup"><span data-stu-id="54b34-164">**Data Type**</span></span>  | <span data-ttu-id="54b34-165">Logični</span><span class="sxs-lookup"><span data-stu-id="54b34-165">Boolean</span></span> |
|<span data-ttu-id="54b34-166">**Možne vrednosti**</span><span class="sxs-lookup"><span data-stu-id="54b34-166">**Possible values**</span></span>  | <span data-ttu-id="54b34-167">`TRUE` *(omogočeno)*</span><span class="sxs-lookup"><span data-stu-id="54b34-167">`TRUE` *(enabled)*</span></span> <br/> <span data-ttu-id="54b34-168">`FALSE` *(onemogočeno)*</span><span class="sxs-lookup"><span data-stu-id="54b34-168">`FALSE` *(disabled)*</span></span>|


<span data-ttu-id="54b34-169">Če te prednostne nastavitve ne nastavite, so izbirne povezane izkušnje na voljo uporabnikom z naročnino na Office 365, ki so vpisani s službenim ali šolskim računom.</span><span class="sxs-lookup"><span data-stu-id="54b34-169">If you don't set this preference, optional connected experiences are available to users with an Office 365 subscription that are signed in with a work or school account or users who have a volume licensed version of Office 2019 for Mac.</span></span> <span data-ttu-id="54b34-170">Če te prednostne nastavitve ne nastavite na NAPAČNO, lahko ti uporabniki v možnosti **Nastavitve** > **Nastavitve zasebnosti** izklopijo izbirne povezane izkušnje.</span><span class="sxs-lookup"><span data-stu-id="54b34-170">Unless you have set this preference to , these users can choose to turn off optional connected experiences by going to Preferences  Privacy.</span></span>

<span data-ttu-id="54b34-171">Drugi uporabniki, kot so domači uporabniki z naročnino na Office 365, ne morejo izklopiti izbirnih povezanih izkušenj.</span><span class="sxs-lookup"><span data-stu-id="54b34-171">For other users, such as home users with an Office 365 subscription, there isn't an option to turn off optional connected experiences.</span></span>