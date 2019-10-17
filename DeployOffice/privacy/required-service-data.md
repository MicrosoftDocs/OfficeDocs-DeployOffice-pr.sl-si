---
title: Zahtevani podatki storitev za Office
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
description: Skrbnikom za Office nudijo pregled zahtevanih podatkov storitve, ki so zbrani o povezanih izkušnjah v Officeu.
hideEdit: true
ms.openlocfilehash: eaa659e375d3d5c29d5410ab53db7ae583df6e9d
ms.sourcegitcommit: 02c4120c0b10bfe378d21d60699ae49aaef97834
ms.translationtype: HT
ms.contentlocale: sl-SI
ms.lasthandoff: 10/15/2019
ms.locfileid: "37510641"
---
# <a name="required-service-data-for-office"></a>Zahtevani podatki storitev za Office 

> [!IMPORTANT]
> Informacije v tem članku veljajo za različico 1904 ali novejšo različico sledeče Officeove odjemalske programske opreme, ki je nameščena v računalniku s sistemom Windows:
> - Office 365 ProPlus in Office 365 Business
> - Office 365 Personal, Office 365 Home ali druge različice Officea, ki so del naročnine na Office 365.
> - Project in Visio, ki sta vključena v nekatere naročniške pakete, kot sta paketa Project Online Professional ali Visio Online 2.
>
> Informacije veljajo tudi za različico 16.28 ali novejšo od teh aplikacij sistema Office za Mac: Excel, Outlook, OneNote, PowerPoint in Word.

Office sestavljajo aplikacije odjemalske programske opreme in povezane izkušnje, zasnovne tako, da vam omogočajo bolj učinkovito ustvarjanje, komuniciranje in sodelovanje. Sodelovanje z drugimi na dokumentu, ki je shranjen v storitvi OneDrive za podjetja, ali prevajanje vsebine Wordovega dokumenta v drug jezik sta primera povezanih izkušenj.

Zahtevani podatki storitev so ključni zato, ker lahko z njimi omogočamo povezane izkušnje v oblaku in izboljšamo varnost ter pričakovano delovanje teh izkušenj za stranke. Zahtevani podatki storitev vključujejo tri vrste informacij.

- **Vsebina stranke** predstavlja vsebino, ki jo ustvarite v Officeu, na primer besedilo, ki ste ga vnesli v Wordov dokument in ki je uporabljeno skupaj s povezano izkušnjo.
- **Funkcijski podatki** vključujejo informacije, ki jih zahteva povezana izkušnja za izvedbo opravila, kot so informacije o konfiguraciji aplikacije.
- **Diagnostični podatki storitev** so podatki, zahtevani za zagotavljanje varnosti, posodobitev in pričakovanega delovanja storitve. Ker so ti podatki v glavnem povezani s povezano izkušnjo, tvorijo ločeno raven od zahtevanih oziroma izbirnih diagnostičnih podatkov.

## <a name="example-of-required-service-data-for-a-connected-experience"></a>Primer zahtevanih podatkov storitev za povezane izkušnje

V nadaljevanju si oglejte vzorčni primer uporabe oblikovalnika za PowerPoint – povezano izkušnjo, ki jo lahko uporabite pri ustvarjanju diapozitivov za predstavitev. Tako boste bolje spoznali zahtevane podatke storitev. Oblikovalnik za PowerPoint izboljša vaše diapozitive tako, da samodejno ustvari ideje za načrt ideje, med katerimi lahko izbirate. Oblikovalnik med dodajanjem vsebine na diapozitiv deluje v ozadju in poišče ustrezno vsebino za strokovno oblikovano postavitev.

Zahtevani podatki storitev, poslani Microsoftu, da vam omogoči to povezano izkušnjo, lahko vključujejo:

- *Vsebino stranke*, kot so besedilo in slike, ki ste jih dodali v diapozitive.
- *Funkcijske podatke*, na primer, kateri diapozitiv urejajte in postavitev diapozitiva.
- *Diagnostične podatke storitev*, kot so dogodki, iz katerih je razvidno, ali je bila idejna zasnova pravilno uporabljena v vašem diapozitivu in ali so bili klici storitve izvedeni pravilno.

## <a name="view-and-manage-required-service-data"></a>Ogled in upravljanje zahtevanih podatkov storitve

Diagnostične podatke storitve si lahko ogledate s Pregledovalnikom diagnostičnih podatkov. Če želite več informacij, glejte [Primeri dogodkov za diagnostične podatke storitve](#examples-of-events-for-service-diagnostic-data).

Izbirate lahko, katere vrste povezanih izkušenj želite uporabljati v Officeu. Od tega je nato odvisno, kateri zahtevani podatki storitve so poslani nam. Na primer Oblikovalnik za PowerPoint je ena od povezanih izkušenj, ki analizira vašo vsebino. Če izklopite povezane izkušnje, ki analizirajo vsebino, ne prejmemo nobenih zahtevanih podatkov storitve o Oblikovalniku za PowerPoint, ker Oblikovalnik za PowerPoint ni na voljo za uporabo.

Zahtevani podatki storitve so zbrani in poslani Microsoftu tudi za ključne Officeove storitve, kot je storitev licenciranja, ki potrjuje, da imate ustrezne licence za uporabo Officea. Ti podatki za ključne storitve so poslani, ne glede na druge nastavitve, povezane z varnostjo, ki ste jih morda konfigurirali.

Če želite več informacij, glejte članke:

- [Povezane izkušnje v Officeu](connected-experiences.md)
- [Osnovne storitve za Office](essential-services.md)
- [Uporaba pregledovalnika diagnostičnih podatkov z Officeom](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

Če ste skrbnik v svoji organizaciji, vas bo morda zanimalo to:

- [Pregled kontrolnikov zasebnosti za Office 365 ProPlus](overview-privacy-controls.md)
- [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office365 ProPlus](manage-privacy-controls.md)
- [Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office za Mac](mac-privacy-preferences.md)
- [Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom iOS](ios-privacy-preferences.md)

## <a name="examples-of-events-for-service-diagnostic-data"></a>Primeri dogodkov za diagnostične podatke storitve

Diagnostični podatki storitve so prikazani v Pregledovalniku diagnostičnih podatkov in so organizirani v iste kategorije, ki jih uporabljajo zahtevani in izbirni diagnostični podatki. Na primer *podatki o uporabi izdelka in storitve* ali *podatki o učinkovitosti delovanja izdelka in storitve.*

Dogodki za diagnostične podatke storitve nudijo zahtevane informacije o tem, ali povezana izkušnja deluje tako, kot pričakuje stranka. Na primer podatki o tem, ali je bila storitev, ki jo uporablja povezana izkušnja, uspešno zagnana in ali je bila na voljo, ko je bilo to potrebno, ali je prišlo do napak ali drugih nepričakovanih težav (zrušitve) med interakcijo s storitvijo in kakšna je odzivnost ali učinkovitost delovanja storitve.

V tej tabeli so nekateri primeri dogodkov za diagnostične podatke storitve.

| **Ime**      | **Opis**    |
| ---------- | --------------------- |
| Office.Excel.Coauth.SaveXrr     | Dogodek, sprožen v Excelu ob uporabi storitve za sodelovanje, ki sporoča podrobnosti o posameznih revizijah, zapisanih v dnevnik revizije. To omogoča nadzor zakasnitev in označuje napake v Excelu, ki so povezane s sodelovanjem  |
| Office.Excel.Coauth.CloseWorkbook  | Dogodek, sprožen v Excelu ob uporabi storitve za sodelovanje, ki sporoča, kdaj je delovni zvezek zaprt. To je potrebno za določanje morebitnih napak pri vnovičnem nalaganju in samodejnem osveževanju. Omogoča merjenje uspeha za dejavnosti storitve sodelovanja.   |
| Office.Security.OCX.NonTrustedEncounter    | Dogodek, sprožen v Officeovih aplikacijah (vključno z Wordom, Excelom, Outlookom, PowerPointom in Visiom), ko uporabnik s kontrolnikom ActiveX odpre dokument, ki ni vreden zaupanja. Uporabljen je za splošno oceno kontrolnikov ActiveX, vdelanih v Officeovih dokumentih, in za omogočanje varnostnih selitev kot odgovor na varnostne dogodke.  |
| Office.Security.UrlReputation.GetUrlReputation | Dogodek, sprožen v Officeovih aplikacijah (vključno z Wordom, Excelom, PowerPointom, Visiom in Publisherjem), ki spremlja uspešnost ali neuspešnost klicev Varnih povezav. Dogodek je uporabljen za preverjanje, ali storitev Varne povezave pravilno deluje, poleg tega pa tudi za diagnozo morebitnih težav.  |
| Office.Voice.VoiceManager.StreamingAudio   | Dogodek, sprožen v Officeovih aplikacijah (vključno z Wordom, Outlookom in PowerPointom), ki nudi informacije o stanju pretakanja zvoka v storitev govora. Vsebuje informacije o velikosti pretočenega zvoka in morebitne napake, do katerih morda pride. Te informacije so uporabljene za nadzorovanje stanja storitve in za diagnosticiranje morebitnih težav, ki jih prijavijo stranke. |
