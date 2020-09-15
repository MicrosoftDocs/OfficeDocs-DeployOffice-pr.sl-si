---
title: Osnovne storitve za Office
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
description: Officeovim skrbnikom zagotavlja informacije o osnovnih storitvah v Officeu, kot so zagon s klikom in licenciranje, ter prikaže seznam dogodkov in polja s podatki za te osnovne storitve.
hideEdit: true
ms.openlocfilehash: 8b4c473736bfe19edffde227be009dd2555852df
ms.sourcegitcommit: 73158b40bdc2d83bdadedeafe0fd152b449d2a44
ms.translationtype: HT
ms.contentlocale: sl-SI
ms.lasthandoff: 09/11/2020
ms.locfileid: "47440505"
---
# <a name="essential-services-for-office"></a>Osnovne storitve za Office

> [!NOTE]
> Če si želite ogledati seznam Officeovih izdelkov, ki so zajeti v teh informacijah o zasebnosti, glejte [Kontrolnike zasebnosti, ki so na voljo za Officeove izdelke](products-versions-privacy-controls.md).

Office sestavljajo aplikacije odjemalske programske opreme in povezane izkušnje, zasnovne tako, da vam omogočajo bolj učinkovito ustvarjanje, komuniciranje in sodelovanje. Upravljate lahko številne povezane izkušnje, ki so na voljo za vas ali vaše uporabnike, če ste skrbnik v organizaciji, obstaja pa tudi nabor osnovnih storitev, ko določajo način delovanja Officea in jih tako ni mogoče onemogočiti. Na primer storitev licenciranja, s katero potrdite, da imate ustrezno licenco za uporabo Officea. Zahtevani podatki o teh storitvah so zbrani in poslani Microsoftu, ne glede na to, ali imate konfigurirane druge nastavitve pravilnika, povezane z varnostjo.

Če želite več informacij, preberite članke:

- [Zahtevani podatki storitev za Office](required-service-data.md)
- [Povezane izkušnje v Officeu](connected-experiences.md)

Če ste skrbnik v svoji organizaciji, vas bo morda zanimalo to:

- [Pregled kontrolnikov za zasebnost za Microsoft 365 aplikacije za podjetja](overview-privacy-controls.md)
- [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Microsoft 365 aplikacije za podjetja](manage-privacy-controls.md)
- [Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office za Mac](mac-privacy-preferences.md)
- [Uporaba nastavitev za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom iOS](ios-privacy-preferences.md)
- [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office v napravah s sistemom Android](android-privacy-controls.md)
- [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za aplikacije Office v spletu.](office-web-privacy-controls.md)

## <a name="list-of-essential-services-for-office"></a>Seznam osnovnih storitev za Office 

V tej tabeli si lahko ogledate seznam osnovnih storitev za Office in opis posameznih storitev.

| **Storitev**  | **Opis**  |
| ------ | ---- |
| [Preverjanje pristnosti](#authentication-events) | Preverjanje pristnosti je storitev, ki je na voljo v različnih platformah, s katero lahko preverite veljavnost identitete uporabnika v Officeu.  S to storitvijo lahko omogočite vpis v Office, aktivirate licenco za Office, dostopate do datotek, shranjenih v oblaku in zagotovite stalne izkušnje v sejah ter napravah, v katerih je nameščen Office.    |
| [Zagon s klikom](#click-to-run-events) | Zagon s klikom je tehnologija namestitev, ki se uporablja za namestitev in posodobitev Officea v sistemu Windows. Preveri, ali so na voljo nove različice Officea, in če je na voljo nova različica, jo prenese ter namesti. Zagon s klikom zazna potrebo, prenese in namesti posodobitve za Office, med drugim tudi varnostne posodobitve.     |
| [Izboljšana konfiguracijska storitev (ECS)](#enhanced-configuration-service-ecs-events) | Storitev ECS Microsoftu omogoča vnovično konfiguracijo namestitev Office, brez potrebe po vnovični uvedbi Office. Uporablja se za nadzor postopnega izdajanja funkcij ali posodobitev. Učinek izdajanja pa lahko nadzorujete z zbranimi diagnostičnimi podatki. Storitev se prav tako uporablja za preprečevanje varnostnih težav in težav z učinkovitostjo delovanja funkcije oziroma posodobitve. Storitev ECS prav tako podpira spremembe konfiguracije, povezane z diagnostičnimi podatki, ki zagotovijo zbiranje ustreznih dogodkov. |
| [Licenciranje](#licensing-events)     | Licenciranje je storitev v oblaku, ki podpira aktivacijo Office za nove namestitve in ohrani licenco v vaših napravah, po tem, ko ste aktivirali Office. Registrira posamezne naprave in aktivira Office, preveri stanje vaše naročnine na Office in upravlja vaše ključe izdelkov.    |
|[Microsoft AutoUpdate (MAU)](#microsoft-autoupdate-mau-events)|Microsoft AutoUpdate (MAU) je tehnologija, ki se uporablja za posodobitev Microsoftovih aplikacij, ustvarjenih za macOS, kot je Office. MAU bo zaznal potrebo po storitvi, izvedla prenos in namestitev posodobitev programov, vključno z varnostnimi posodobitvami.|
|[Sinhronizacija programa OneNote](#onenote-sync-events)|OneNote za Mac podpira le zvezke, ki so shranjeni v internetu v OneDrive ali SharePoint Online. OneNote za Mac nenehno sinhronizira vse zapiske uporabnikov z OneDrive ali storitvijo SharePoint online. Tako lahko uporabniki odprejo, si ogledajo in urejajo svoje zvezke v vseh svojih napravah, tako da so njihovi zvezki vedno posodobljeni.
 [Konfiguracija storitev](#services-configuration-events)  | Konfiguracija storitev omogoča posodobitve konfiguracijskih nastavitev za Office za omogočanje oziroma onemogočanje odjemalskih funkcij. Storitev se aktivira vsakič, ko se zažene Officeova aplikacija, in zagotavlja podrobnosti o drugih konfiguracijah ter storitvah v Officeu. Storitve konfiguracije prav tako nadzorujejo, katere storitve so opredeljene kot osnovne storitve.  |
| [Telemetrija](#telemetry-events)  | Storitev telemetrije se uporablja za zbiranje diagnostičnih podatkov iz Officeovih aplikacij. Omogoča zbiranje diagnostičnih podatkov, ki jih ustvarja Office (zahtevanih in izbirnih diagnostičnih podatkov). Storitev je prav tako odgovorna za zbiranje dela zahtevanih diagnostičnih podatkov za Office.  |

## <a name="events-and-data-fields-for-essential-services-for-office"></a>Dogodki in podatkovna polja za osnovne storitve za Office

V naslednjih razdelkih boste naleteli na:

- Seznam dogodkov za posamezne osnovne storitve
- Opis posameznih dogodkov
- Seznam podatkovnih polj v posameznih dogodkih
- Opis posameznih podatkovnih polj


## <a name="authentication-events"></a>Dogodki preverjanja pristnosti

Ti dogodki diagnostičnih podatkov se zberejo, ko Office poskuša pridobiti žeton za preverjanje pristnosti (na tih način ali prek poziva).

### <a name="officeandroidmsaguesttoaad"></a>Office.Android.MSAGuestToAAD

S tem dogodkom lažje razumemo, kako številni uporabniki med dostopanjem do službenega vira, dobivajo pozive za vnos gesla osebnega računa, saj njihov osebni račun lahko predstavlja veljaven gostujoči račun za najemnika službenih računov.

S temi podatki lažje razumemo, kako se morajo številni uporabniki prebiti prek mukotrpnih pozivov za vpis za dodelitev prioritet pri pridobivanju žetona za AAD glede na Microsoftovo izjavo za račun SAML (Security Assertion Markup Language).

Zbrana so sledeča polja:

- **Tag** – ponazarja, da je bil uporabniku med dostopanjem do službenega vira prikazan poziv za vpis v osebni račun.


### <a name="officeidentityfbapromptwin32"></a>Office.Identity.FbaPromptWin32

Dogodki se zberejo, ko Office uporabniku prikaže poziv za vpis s preverjanjem pristnosti z obrazci.

Poleg tihih pridobitev žetonom se s pozivi za preverjanje pristnosti ugotovi, ali je za uporabnika aktivirano stanje prekinjenega preverjanja pristnosti. Uporabnik se tako nahaja v stanju odjemalca brez povezave, v najslabšem primeru pa prekinjeno preverjanje pristnosti lahko povzroči pridobivanje licence in onemogoči odjemalca v celoti.

Pozivi za vpis s preverjanjem pristnosti z obrazci se uporabljajo za nekatere scenarije preverjanja pristnosti na mestu uporabe, vendar tega običajno ne želimo, ker bi uporabniki morali uporabljati sodobno preverjanje pristnosti zaradi varnostnih ranljivosti, povezanih s preverjanjem pristnosti z obrazci.

Zbrana so sledeča polja:

  - **AuthScheme** – uporabljena shema za preverjanje pristnosti

  - **DocumentUrlHash** – zahteva za šifrirani URL

  - **EndTag** – oznaka, pri kateri se zaključi obrazec za preverjanje pristnosti

  - **Flags** – zastarelo

  - **FlowTag** – oznaka, pri kateri se začne obrazec za preverjanje pristnosti

  - **LastError** – vrnjena koda napake

  - **PromptEndTime** – čas, ko se je poziv končal

  - **PromptStartTime** – čas, ko se je poziv začel

  - **Result** – ali je bilo preverjanje pristnosti uspešno

  - **SessionEndTime** – čas, ko se konča seja dogodka

  - **Timeout** – čas, ko je potekla časovna omejitev poziva

### <a name="officeidentitysignoutevent"></a>Office.Identity.SignOutEvent

Dogodki se zberejo, ko se uporabnik izpiše iz Officea.

Če veste, da se je uporabnik izpisal, lahko pričakovano razvrstite druge dogodke, na primer pozive, da bodo ti dogodki lahko pravilno izračunani v metriki zanesljivosti/pripravljenosti na odpremo. Prav tako se lahko izognete opozorilom oziroma razveljavljanju gradenj ob lažni predpostavki, da je uporabnik deležen nepričakovanih pozivov za vpis.

Zbrana so sledeča polja:

  - **FlowEndTime** – čas, ko se konča izpis

  - **FlowStartTime** – čas, ko se začne izpis

  - **IdentityErrorState** – stanje napake identitete pri izpisu

  - **IdentityHashedUniqueId** – šifrirani ID identitete pri izpisu

  - **IdentityProviderType** – ponudnik identitete za identiteto, za katero poteka izpis

  - **IdentityUniqueID** – ID identitete, za katero poteka izpis

  - **SessionEndTime** – čas, ko se konča seja dogodka

  - **SignOutUserAction** – ponazarja, da je uporabnik začel postopek izpisa

### <a name="officeidentitysspipromptwin32"></a>Office.Identity.SspiPromptWin32

Dogodki se zberejo, ko Office uporabniku prikaže poziv za vpis prek vmesnika SSPI v sistemu Windows. Poleg tihih pridobitev žetonov se s pozivi za preverjanje pristnosti ugotovi, ali je za uporabnika aktivirano stanje prekinjenega preverjanja pristnosti. Rezultat tega je stanje odjemalca brez povezave. Prekinjeno preverjanje pristnosti lahko prepreči pridobitev licence in onemogoči odjemalca v celoti.

Pozivi vmesnika SSPI v sistemu Windows se uporabljajo za preverjanje pristnosti z Exchangeom (za sinhronizacijo pošte), ko vir za Exchange uporabnika ni bil nastavljen za večkratno preverjanje pristnosti.

Ti dogodki se skupaj z dogodki imenskega prostora Office.MATS uporabljajo za te namene:

1\) Ugotovite, ali odjemalci lahko uspešno pridobijo žeton za preverjanje pristnosti oziroma je za njih aktivirano stanje prekinjenega preverjanja pristnosti.

2\) Ovrednotite, ali je prišlo do sprememb v odjemalcu, oziroma je v storitvah prišlo do kritičnih regresij glede izkušnje in zanesljivosti pri preverjanju pristnosti uporabnika.

3\) Ko se pojavijo napake, ti signali iz odgovorne komponente (koda odjemalca za Office, knjižnice za preverjanje pristnosti ali storitve avtoritete) oddajo pomembne kode napak, ki se jih lahko uporabi za triažo, diagnosticiranje ali odpravljanje napak.

4\) Ti signali ponazarjajo različne pripravljenosti na odpremo in nadzirajo stanja, zaradi katerih se aktivirajo opozorila. Na ta način naši inženirji lahko hitro ukrepajo in skrajšajo čas za odpravljanje kritičnih težav blokiranja uporabnikov.

Zbrana so sledeča polja:

  - **AllowSavedCreds** – ali se ohranijo nove poverilnice

  - **AuthScheme** – uporabljena shema za preverjanje pristnosti

  - **CredsSaved** – ali se shranijo nove poverilnice

  - **DocumentUrlHash** – zahteva za šifrirani URL

  - **EndTag** – oznaka, pri kateri se konča poziv

  - **NewIdentity**\_ErrorState – ali je nova identiteta veljavna

  - **NewIdentity\_HashedUniqueId** – šifrirani ID nove identitete, ko je poziv končan

  - **NewIdentity\_ProviderType** – novi ponudnik identitete, ko je poziv končan

  - **NewIdentity\_UniqueID** – ID nove identitete, ko je poziv končan

  - **OutStatus** – ali je rezultat poziva veljaven

  - **PromptEndTime** – čas, ko se je poziv končal

  - **PromptFailedTag** – oznaka, ki ponazarja napako vmesnika SSPI

  - **PromptFlow** – oznaka, ki je priklicala poziv vmesnika SSPI

  - **PromptStartTime** – čas, ko se je poziv začel

  - **Proxy** – ali se uporablja strežnik proxy

  - **ServerHash** – šifrirani naslov strežnika

  - **SessionEndTime** – čas, ko se konča seja dogodka

  - **Timeout** – čas, ko je potekla časovna omejitev poziva

  - **UiMessage** – sporočilo uporabniškega vmesnika v pozivu

  - **UserNameHash** – šifrirano uporabniško ime

### <a name="officeidentitywin32prompt"></a>Office.Identity.Win32Prompt

Dogodki se zberejo, ko Office uporabniku prikaže poziv za vpis z večkratnim preverjanjem pristnosti. Poleg tihih pridobitev žetonov se s pozivi za preverjanje pristnosti ugotovi, ali je za uporabnika aktivirano stanje prekinjenega preverjanja pristnosti. Rezultat tega je stanje odjemalca brez povezave. Prekinjeno preverjanje pristnosti lahko prepreči pridobitev licence in onemogoči odjemalca v celoti.

Ti dogodki se skupaj z dogodki imenskega prostora Office.MATS uporabljajo za te namene:

1\) Ugotovite, ali odjemalci lahko uspešno pridobijo žeton za preverjanje pristnosti oziroma je za njih aktivirano stanje prekinjenega preverjanja pristnosti.

2\) Ovrednotite, ali je prišlo do sprememb v odjemalcu, oziroma je v storitvah prišlo do kritičnih regresij glede izkušnje in zanesljivosti pri preverjanju pristnosti uporabnika.

3\) Ko se pojavijo napake, ti signali iz odgovorne komponente (koda odjemalca za Office, knjižnice za preverjanje pristnosti ali storitve avtoritete) oddajo pomembne kode napak, ki se jih lahko uporabi za triažo, diagnosticiranje ali odpravljanje napak.

4\) Ti signali ponazarjajo različne pripravljenosti na odpremo in nadzirajo stanja, zaradi katerih se aktivirajo opozorila. Na ta način naši inženirji lahko hitro ukrepajo in skrajšajo čas za odpravljanje kritičnih težav blokiranja uporabnikov.

Zbrana so sledeča polja:

  - **AdalWAMUsed** – oznaka, ki ponazarja rezultat, ali je bil uporabljen ADAL-atop-WAM

  - **CallTag** – oznaka, ki ponazarja klicatelja za vpis v uporabniški vmesnik

  - **Context** – kontekst vpisa za poziv

  - **EndTagIdentityProviderRequested** – oznaka za zahtevo ponudnika identitete

  - **HrdShownTag** – oznaka, pri kateri je prikazano pogovorno okno za vpis v HRD

  - **IdentityProviderResulted** – zahtevana vrsta ponudnika identitete

  - **IdPFlowTag** – oznaka, ki ponazarja rezultat zahteve identitete

  - **LastLoginDelta** – delta časa iz zadnje uspešne prijave

  - **NewIdentity\_** ErrorState – ali je identiteta veljavna po pozivu

  - **NewIdentity\_ProviderType** – vrsta ponudnika identitete po pozivu

  - **NewIdentity\_UniqueID** – vrnjeni ID nove identitete po pozivu

  - **PromptCorrelation** – ID korelacije poziva za diagnostiko

  - **PromptEndTime** – čas, ko se je poziv končal

  - **PromptStartTime** – čas, ko se je poziv začel

  - **SessionEndTime** – čas, ko se konča seja dogodka

  - **ShowUIResult** – koda rezultata, ki jo je vrnil poziv

  - **StartTag** – oznaka, pri kateri se je začel poziv Win32

  - **Timeout** – čas, ko je potekla časovna omejitev poziva

  - **WasIdentitySignedOut** – ali je uporabnik izpisan

### <a name="officematsactionofficewin32-officematsactionofficewinrt"></a>Office.MATS.actionofficewin32, Office.MATS.actionofficewinrt

Ta opis velja za dogodke Win32 in WinRT (ime je odvisno od platforme).

Microsoftov telemetrični sistem za preverjanje pristnosti (MATS) se zbere, ko Office poskuša pridobiti žeton za preverjanje pristnosti (na tih način ali prek poziva). Če pridobitev ni uspešna, so vključeni tudi podatki o napakah. S temi dogodki se naši uporabniki lahko izognejo stanju prekinjenega preverjanja pristnosti tako, da:

1\) Ugotovijo, ali odjemalci lahko uspešno pridobijo žeton za preverjanje pristnosti oziroma je za njih aktivirano stanje prekinjenega preverjanja pristnosti.

2\) Ovrednotijo, kdaj je prišlo do sprememb v odjemalcu ali storitvah, ali je prišlo do kritičnih regresij glede izkušnje in zanesljivosti pri preverjanju pristnosti uporabnika.

3\) Ko se pojavijo napake, ti signali iz odgovorne komponente (koda odjemalca za Office, knjižnice za preverjanje pristnosti ali storitve avtoritete) oddajo pomembne kode napak, ki se jih lahko uporabi za triažo, diagnosticiranje ali odpravljanje napak.

4\) Ti signali ponazarjajo različne pripravljenosti na odpremo in nadzirajo stanja, zaradi katerih se aktivirajo opozorila. Na ta način naši inženirji lahko hitro ukrepajo in skrajšajo čas za odpravljanje kritičnih težav.

Zbrana so sledeča polja:

  - **Actiontype** – katera vrsta knjižnice za preverjanje pristnosti se uporabi

  - **Appaudience** – ali je aplikacija namenjena za notranjo oziroma zunanjo uporabo

  - **Appforcedprompt** – ali aplikacija preglasi predpomnilnik in vsili prikaz poziva

  - **Appname** – ima aplikacije, ki izvaja preverjanje pristnosti

  - **Appver** – različica aplikacije, ki izvaja preverjanje pristnosti

  - **Askedforcreds** – ali ja aplikacija uporabnika pozvala za vnos poverilnic za to dejanje

  - **Authoutcome** – ali je bil poskus preverjanja pristnosti uspešen, ni bil uspešen oziroma je bil preklican

  - **Blockingprompt** – ali je aplikacija prikazala poziv, ki zahteva posredovanje uporabnika

  - **Correlationid** – GUID, ki se uporablja za združevanje s podatki storitev

  - **Count** – število dogodkov v primerih združevanja

  - **Data\_accounttype** – potrošniški račun ali račun organizacije

  - **Devicenetworkstate** – ali je bil uporabnik dosegljiv

  - **Deviceprofiletelemetryid** – anonimni ID naprave, ki se uporablja za merjenje izkušnje naprave

  - **Duration** – čas trajanja preverjanja pristnosti

  - **Endtime** – ali se je dogodek preverjanja pristnosti končal

  - **Error** – koda napake, če preverjanje pristnosti ni bilo uspešno

  - **ErrorDescription** – kratek opis napake

  - **Errorsource** – ali je do napake prišlo v storitvi, knjižnici za preverjanje pristnosti oziroma aplikaciji

  - **Identityservice** – ali je bil priklican Microsoftov račun storitve (MSA) oziroma storitev Azure Active Directory (AAD) 

  - **Interactiveauthcontainer** – katere vrste poziv je bil prikazan

  - **Issilent** – ali je bil prikazan poziv

  - **Microsoft**\_**ADAL**\_**adal**\_**version** – različica knjižnice Azure Active Directory Authentication Library (ADAL)

  - **Microsoft\_ADAL\_api\_error\_code** – koda napake, ki jo je ustvarila knjižnica za preverjanje pristnosti za ta poskus preverjanja pristnosti

  - **Microsoft\_ADAL\_api\_id** – API, ki je bil priklican za ta poskus preverjanja pristnosti

  - **Microsoft\_ADAL\_authority** – URL overovitelja za Azure Active Directory, ki je odgovoren za preverjanje pristnosti uporabnika

  - **Microsoft\_ADAL\_authority\_type** – potrošnik/pogodba za storitve Microsoft (MSA) v primerjavi z organizacijskim/Azure Active Directory (AAD); trenutno vedno AAD

  - **Microsoft\_ADAL\_authority\_validation\_status** – ponazarja, ali je bilo preverjanje pristnosti v storitvi dokončano

  - **Microsoft\_ADAL\_broker\_app** – ponazarja, ali je ADAL pri preverjanju pristnosti uporabil posrednika

  - **Microsoft\_ADAL\_broker\_app\_used** – ponazarja ime posrednika (npr. upravljanje računov v sistemu Windows)

  - **Microsoft\_ADAL\_broker\_version** – ponazarja različico morebitnega posrednika

  - **Microsoft\_ADAL\_cache\_event\_count** – število dogodkov predpomnilnik, ki jih je ADAL izvedel med pridobivanjem žetona

  - **Microsoft\_ADAL\_cache\_event\_count\_max** – če se združi ta signal, ponazarja največje dovoljeno število dogodkov predpomnilnika za katere koli združene dogodke

  - **Microsoft\_ADAL\_cache\_event\_count\_min** – če se združi ta signal, ponazarja najmanjše dovoljeno število dogodkov predpomnilnika za katere koli združene dogodke

  - **Microsoft\_ADAL\_cache\_event\_count\_sum** – če se združi ta signal, ponazarja vsoto dogodkov predpomnilnika za vse združene dogodke

  - **Microsoft\_ADAL\_cache\_read\_count** – kolikokrat je API prebral iz predpomnilnika diska. Na voljo, če je bilo zaznano vsaj eno branje

  - **Microsoft\_ADAL\_cache\_read\_error\_count** – kolikokrat ni uspelo branje iz predpomnilnika diska. Na voljo, če je bil zaznan vsaj en neuspešen poskus

  - **Microsoft\_ADAL\_cache\_read\_last\_error** – koda napake ADAL. Na voljo, če je bilo zaznano vsaj eno neuspešno branje

  - **Microsoft\_ADAL\_cache\_read\_last\_system\_error** – koda napake sistema. Na voljo, če je bilo zaznano vsaj eno neuspešno branje

  - **Microsoft\_ADAL\_cache\_write\_count** – kolikokrat je API zapisal v predpomnilnik diska. Na voljo, če je bilo zaznano vsaj eno pisanje

  - **Microsoft\_ADAL\_cache\_write\_error\_count** – kolikokrat ni uspelo pisanje v predpomnilnik diska. Na voljo, če je bil zaznan vsaj en neuspešen poskus

  - **Microsoft\_ADAL\_cache\_write\_last\_error** – koda napake ADAL. Na voljo, če je bila zaznana vsaj ena napaka pisanja

  - **Microsoft\_ADAL\_cache\_write\_last\_system\_error** – koda napake sistema. Na voljo, če je bila zaznana vsaj ena napaka pisanja

  - **Microsoft\_ADAL\_client\_id** – zgoščeni ID aplikacije AAD

  - **Microsoft\_ADAL\_extended\_expires\_on\_setting** – trditev true/false, ki ponazarja, ali je žeton presegel svojo življenjsko dobo

  - **Microsoft\_ADAL\_http\_event\_coun**t – število klicev HTTP, ki jih izvede ADAL

  - **Microsoft\_ADAL\_http\_event\_count\_max** – če je združen ta signal, ponazarja največje dovoljeno število klicev HTTP, ki jih izvede ADAL za kateri koli združeni dogodek.

  - **Microsoft\_ADAL\_http\_event\_count\_min** – če je združen ta signal, ponazarja najmanjše dovoljeno število klicev HTTP, ki jih izvede ADAL za kateri koli združeni dogodek.

  - **Microsoft\_ADAL\_http\_event\_count\_sum** – če je združen ta signal, ponazarja vsoto klicev HTTP, ki jih izvede ADAL za vse združene dogodke.

  - **Microsoft\_ADAL\_is\_silent\_ui** – trditev true/false, ki ponazarja, ali je ADAL prikazal poziv uporabniškega vmesnika

  - **Microsoft\_ADAL\_is\_successful** – trditev true/false, ki ponazarja, ali je bil API ADAL uspešen

  - **Microsoft\_ADAL\_logging\_pii\_enabled** – trditev true/false, ki ponazarja, ali je omogočen celoten način pisanja dnevnika ADAL. Ti podatke so zapisani v dnevnik samo lokalno in niso posredovani telemetriji

  - **Microsoft\_ADAL\_oauth\_error\_code** – koda napake za protokol OAuth, ki jo vrne storitev

  - **Microsoft\_ADAL\_prompt\_behavior** – parameter HTTP za prijavo, ki je bil posredovan storitvi za določanje, ali je mogoče prikazati uporabniški vmesnik (oziroma storitvi ni bil posredovan noben parameter HTTP)

  - **Microsoft\_ADAL\_request\_id** – transakcijski GUID za zahtevo, ki jo ADAL posreduje storitvi

  - **Microsoft\_ADAL\_response\_code** – koda odziva HTTP iz storitve

  - **Microsoft\_ADAL\_response\_time** – kako dolgo je trajalo, da se je storitev vrnila v ADAL

  - **Microsoft\_ADAL\_response\_time\_max** – če je združen ta signal, ponazarja najdaljši čas, ki ga je ADAL porabil za vrnitev od vmesnika API za kateri koli združeni dogodek

  - **Microsoft\_ADAL\_response\_time\_min** – če je združen ta signal, ponazarja najkrajši čas, ki ga je storitev porabila za odziv na ADAL za kateri koli združeni dogodek.

  - **Microsoft\_ADAL\_response\_time\_sum** – če je združen ta signal, ponazarja vsoto časa, ki ga je ADAL porabil za vrnitev od vmesnika API za vse združene dogodke

  - **Microsoft\_ADAL\_rt\_age** – starost žetona za osveževanje

  - **Microsoft\_ADAL\_server\_error\_code** – koda napake, ki jo je vrnil strežnik

  - **Microsoft\_ADAL\_server\_sub\_error\_code** – koda podnapake, ki jo je strežnik vrnil kot pojasnilo, zakaj zahteve ni bilo mogoče dokončati

  - **Microsoft\_ADAL\_spe\_ring** – trditev true/false, ki ponazarja, ali je uporabnik uporabil notranji obroč za Secure Production Enterprise (samo za Microsoftove zaposlene)

  - **Microsoft\_ADAL\_start\_time** – čas, ko je bil izveden klic za ADAL API

  - **Microsoft\_ADAL\_stop\_time** – čas, ko je bil vrnjen klic za ADAL API

  - **Microsoft\_ADAL\_telemetry\_pii\_enabled** – trditev true/false, ki ponazarja, ali je omogočen način polne telemetrije za ADAL. Ime je napačno ime, saj se ne oddaja noben PII/EUII

  - **Microsoft\_ADAL\_tenant\_id** – GUID, ki identificira najemnika, kateremu pripada preverjeni uporabnik

  - **Microsoft\_ADAL\_token\_acquisition\_from\_context** – opisuje vedenje ADAL glede na žetone v kontekstu preverjanja pristnosti

  - **Microsoft\_ADAL\_token\_type** – žeton za osveževanje (RT) ali žeton za osveževanje z več viri (MRRT)

  - **Microsoft\_ADAL\_ui\_event\_count** – število pozivov, prikazanih uporabniku. Morda so tihi

  - **Microsoft\_ADAL\_user\_cancel** – trditev true/false, ali je bilo preklicano okno uporabniškega vmesnika.

  - **Microsoft\_ADAL\_x\_ms\_request\_id** – dodatni ID zahteve v glavi HTTP, ki ga ADAL posreduje storitvi

  - **Platform** – Win32/WinRT/Android/iOS/Mac

  - **Scenarioid** – GUID. Enemu scenariju lahko pripada več dogodkov. Scenarij lahko na primer doda nov račun, vendar lahko v tem scenariju pride do več pozivov. Ta ID omogoča korelacijo

  - **Sessionid** – GUID za prepoznavanje seje zagona

  - **Skdver** – različica odjemalskega kompleta za razvoj programske opreme MATS, uporabljena za ustvarjanje teh podatkov

  - **Začetni čas** – času, ko je bil poklican API MATS za začetek\*dejanja

  - **Tenantid** – GUID, ki identificira najemnika, kateremu pripada preverjeni uporabnik (v primerih, ki niso ADAL).

  - **Uploadid** – enolični GUID za ta dogodek, uporablja se za onemogočanje dvojnikov

  - **Wamapi** – identificira, kateri API WAM se pokliče

  - **Wamtelemetrybatch** – se trenutno ne uporablja. V prihodnosti komponenti WAM omogoča odpremo dodatnih informacij glede dogodka za preverjanje pristnosti

### <a name="onenotesigninssoexternalappsaccountfound"></a>OneNote.SignIn.SSOExternalAppsAccountFound
 
Ta dogodek se zabeleži, ko je račun z veljavnim žetonom za osveževanje najden med seznamom računov, ki jih je predložil TokenSharingManager.  Ta primer je specifičen za enotno prijavo (SSO).
 
Zbrana so sledeča polja:
 
- **AccountType** – prijavi vrsto računa

- **ProviderPackageID** – prijavi ID paketa za program, ki je priskrbel ta račun

### <a name="onenotesigninssoexternalappsinvalidaccount"></a>OneNote.SignIn.SSOExternalAppsInvalidAccount

Ta dogodek se zabeleži, ko je prišlo do napake pri poskusu pridobivanja žetona za osveževanje za račun na seznamu računov, ki ga je predložil TokenSharingManager. Ta primer je specifičen za enotno prijavo (SSO).
 
Zbrana so sledeča polja:
 
- **RawError** – prijavi neobdelano napako, ki je bila pridobljena, ko poskuša dobiti žeton za osveževanje z danim računom.

### <a name="onenotestickynotesfetchtokencompleted"></a>OneNote.StickyNotes.FetchTokenCompleted
 
Ta dogodek se zabeleži po preverjanju pristnosti, ko je prenašanje žetona za osveževanje dokončano.
 
Zbrana so sledeča polja:
 
- **ErrorMessage** – če ni bilo mogoče pridobivati žetona, se bo to sporočilo o napaki v dnevniku 

- **Rezultat** – dnevnike rezultata pridobivanja žetona

- **StickyNoteAccountType** – Vrsta računa, za katerega je program poskusil pridobiti žeton za osveževanje


## <a name="click-to-run-events"></a>Dogodki zagona s klikom

### <a name="officeclicktorunbootstrapper"></a>Office.ClickToRun.Bootstrapper 

Podatki o zalogi in nastavitvi Officea se zberejo, ko uporabnik zažene datoteko Office setup.exe, da spremeni nameščene Officeove izdelke. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti celotne namestitve Officea, ki jo je sprožil uporabnik, vključno z vnaprej zahtevanimi pregledi.

Zbrana so sledeča polja:

  - **Data\_BootStrapperStateFailure\_ErrorCode** – koda napake

  - **Data\_BootStrapperStateFailure\_ErrorSource** – funkcija, ki je ni bilo mogoče zagnati

  - **Data\_BootStrapperStateFailure\_FailingState** – del, ki ga ni bilo mogoče izvesti v orodju boostrapperbootstrapper

  - **Data\_BootStrapperStateFailure\_OExceptionType** – vrsta izjeme, ki je ni bilo mogoče izvesti

  - **Data\_Culture** – lokalne nastavitve, uporabljene za zagon datoteke exe, npr. en-us

  - **Data\_HashedOLSToken** – zgoščena vrednost sha-256 za žeton, prejeta od storitve OLS

  - **Data\_Platform** – namestitev x64 ali x86

  - **Data\_PrereqFailure\_Type** – zahtevana okvara, na katero smo naleteli, npr. operacijski sistem ni podprt

  - **Data\_ProductReleaseId** – izdelek, ki ga nameščamo, npr. Aplikacije ogrodja Microsoft 365 za podjetja

### <a name="officeclicktoruncorruptioncheck"></a>Office.ClickToRun.CorruptionCheck

Podatki o zalogi in nastavitvi Officea se zberejo, ko odjemalec zagona s klikom zažene poškodovano preverjanje, s katerim zagotovi, da so Officeove dvojiške vrednosti pravilne. Dogodki se uporabljajo za merjenje poškodb Officeovih dvojiških vrednosti in določanje, katere dvojiške vrednosti so poškodovane.

Zbrana so sledeča polja:

  - **Data\_Active –** trenutni manifest toka, ki ga preverjamo na disku

  - **Podatki\_ActivePackages –** katere pakete vsebuje manifest

  - **Data\_ActiveVersion –** različica manifesta

  - **Data\_AddFileCount –** števil datotek, ki jih bomo dodali

  - **Data\_AddFileFiles –** vzorec datotek, ki jih bomo dodali

  - **Data\_CompressionLevel –** način stiskanja datotek

  - **Data\_CorruptionCheckLevel –** kako globoko preverjamo poškodbe (stopnje)

  - **Data\_CorruptSizeCount –** koliko datotek ima nepravilno velikost

  - **Data\_CorruptSizeFiles –** vzorec datotek z nepravilno velikostjo

  - **Data\_CorruptVersionCount –** število datotek z nepravilno različico

  - **Data\_CorruptVersionFiles –** vzorec datotek z nepravilnimi različicami

  - **Data\_FileBadDigestCount –** število datotek, ki jih ni bilo mogoče odpreti

  - **Data\_FileBadDigestFiles –** vzorec datotek, ki jih ni bilo mogoče odpreti

  - **Data\_FileNotSignedCount –** število nepodpisanih datotek

  - **Data\_FileNotSignedFiles –** vzorec nepodpisanih datotek

  - **Data\_FileNotTrustedCount –** število datotek, ki jim ni mogoče zaupati

  - **Data\_FileNotTrustedFiles –** vzorec datotek, ki jim ni mogoče zaupati

  - **Data\_IncompleteFileCount –** število nepopolnih datotek

  - **Data\_IncompleteFileFiles –** vzorec nepopolnih datotek

  - **Data\_KeepFileCount –** število ohranjenih datotek

  - **Data\_KeepFileFiles –** vzorec ohranjenih datotek

  - **Data\_KeepIncompleteFileCount –** število datotek, ki smo jih ohranili, kljub temu, da so nepopolne

  - **Data\_KeepIncompleteFileFiles –** vzorec nepopolnih datotek, ki smo jih ohranili

  - **Data\_MismatchSizeCount –** število datotek, katerih velikost ne ustreza našemu manifestu

  - **Data\_MismatchSizeFiles –** vzorec datotek z neustrezno velikostjo

  - **Data\_MismatchVersionCount –** število datotek z različico, ki se razlikuje od našega manifesta

  - **Data\_MismatchVersionFiles –** vzorec datotek z različnimi različicami

  - **Data\_MissingFileCount –** število manjkajočih datotek

  - **Data\_MissingFileFiles –** vzorec manjkajočih datotek

  - **Data\_NotToBeStreamedFileCount –** število datotek, ki jih ne predvajamo pretočno

  - **Data\_RemoveFileCount –** število datotek, ki jih bomo odstranili

  - **Data\_RemoveFileFiles –** vzorec datotek, ki jih bomo odstranili

  - **Data\_StreamUnitsMismatchCount –** število datotek z enotami, ki se ne ujemajo z našim manifestom

  - **Data\_StreamUnitsMismatchFiles –** vzorec datotek s tokom enot, ki se ne ujemajo

  - **Data\_TimeElapsed –** kako dolgo smo iskali nepravilnosti

  - **Data\_UpdateFileCount –** število datotek, ki jih bomo posodobili

  - **Data\_UpdateFileFiles –** vzorec datotek, ki ji bomo dodali

  - **Data\_Working –** novi manifest, ki ga preverjamo

  - **Data\_WorkingVersion –** različica novega manifesta

### <a name="officeclicktorunmachinemetadata"></a>Office.ClickToRun.MachineMetadata

Podatki o zalogi in nastavitvi Officea, ki omogočajo zahtevane metapodatke za nastavitev in zalogo ter se uporabljajo za določanje natančne zbirke namestitve.

Zbrana so sledeča polja:

  - **Data\_C2RClientVer** – različica datoteke OfficeClickToRun.exe v računalniku

  - **Data\_OfficeBitness** – bitni način, v katerem je nameščen Office, x86 ali x64

  - **Data\_OfficeVersion** – različica nameščenega Officea

  - **Data\_Sku** – inventarna enota, ki je nameščena, tj. Aplikacije ogrodja Microsoft 365 za podjetja

  - **Data\_SqmMachineID** – enolični ID računalnika, ki ga uporablja Windows SQM Data\_SusClientID – identifikator za posodobitev Officea

### <a name="officeclicktorunodt"></a>Office.ClickToRun.ODT

Podatki o zalogi in nastavitvi Officea, ki se zberejo, ko skrbnik za IT zažene datoteko setup.exe s tehnologijo zagona s klikom za orodje za uvedbo sistema Office, da spremeni Officeove izdelke, ki jih je namestil uporabnik. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti celotne namestitve Officea, ki jo je sprožil skrbnik za IT, vključno z vnaprej zahtevanimi pregledi.

Zbrana so sledeča polja:

  - **Data\_BootStrapperStateFailure\_ErrorCode** – koda napake

  - **Data\_BootStrapperStateFailure\_ErrorSource** – funkcija, ki je ni bilo mogoče zagnati

  - **Data\_BootStrapperStateFailure\_FailingState** – del, ki ga ni bilo mogoče izvesti v orodju boostrapper

  - **Data\_BootStrapperStateFailure\_OExceptionType** – vrsta izjeme, ki je ni bilo mogoče izvesti

  - **Data\_ConfigurationHost** – gostitelj, ki je posredoval datoteko configuration.xml

  - **Data\_ConfigurationId** – ID, ki ga pridobimo iz datoteke configuration.xml

  - **Data\_ConfigurationSource** – vir, ki je posredoval datoteko configuration.xml

  - **Data\_Culture** – lokalne nastavitve, uporabljene za zagon datoteke exe, npr. en-us

  - **Data\_HashedOLSToken** – zgoščena vrednost sha-256 za žeton, prejeta od storitve OLS

  - **Data\_MigrateArchRequest** – če uporabnika selimo iz načina x86 v x64 ali obratno

  - **Data\_MigrateArchRequestValid** – če menimo, da je zahteva za selitev veljavna

  - **Data\_Platform** – namestitev x64 ali x86

  - **Data\_PlatformMigratedFrom** – začetna platforma, npr. x86

  - **Data\_PlatformMigratedTo** – končna platforma, npr x64

  - **Data\_PrereqFailure\_Type** – zahtevana okvara, do katere je prišlo

  - **Data\_ProductReleaseId** – izdelek, ki ga nameščamo, npr. Aplikacije ogrodja Microsoft 365 za podjetja

### <a name="officeclicktorunrepomanlogger"></a>Office.ClickToRun.RepomanLogger

Poroča o stanju novega posodobitvenega cevovoda »Zagon s klikom« (»Repoman«), če pa se uspešno prenese, uveljavi posodobitve za Office.

Zbrana so sledeča polja:

  - **ApplySucceeded** – ima vrednost true, če je cevovod uspešno uveljavil posodobitev, v nasprotnem primeru pa vrednost false.
  
  - **DownloadSucceeded** – ima vrednost true, če je cevovod uspešno prenesel posodobitev, v nasprotnem primeru pa vrednost false.

  - **ErrorCode** – koda zadnje napake, ki se je pojavila v cevovodu »Zagon s klikom« Repoman.

  - **ErrorCode** – dodatne podrobnosti zadnje napake, ki se je pojavila v cevovodu »Zagon s klikom« Repoman.
 
  - **ErrorMessage** – sporočilo zadnje napake, ki se je pojavila v cevovodu »Zagon s klikom« Repoman.

  - **OpenStreamSessionSucceeded** – ima vrednost true, če cevovod uspešno ustvari sejo za pretakanje Officeove posodobitve, v nasprotnem primeru pa vrednost false.

  - **RepomanErrorMessage** – iz datoteke repoman.dll je bilo prejeto sporočilo o napaki.
 

### <a name="officeclicktorunscenarioinstalltaskconfigure"></a>Office.ClickToRun.Scenario.InstallTaskConfigure

Podatki o zalogi in nastavitvi Officea, ki se zberejo, ko namestitveni program za Office zažene na novo prenesene datoteke. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeove namestitve.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion** – različica, na katero bo posodobljen Office 15 

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake 

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove**– katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti 

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** – enolični ID računalnika, ki ga uporablja Windows SQM 

  - **Data\_SusClientID** – identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktorunscenarioinstalltaskconfigurelight"></a>Office.ClickToRun.Scenario.InstallTaskConfigurelight

Podatki o zalogi in nastavitvi Officea, ki se zberejo, ko se namestitveni program za Office odloča, katere datoteke je treba prenesti. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeove namestitve.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion** – različica, na katero bo posodobljen Office 15 

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake 

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove**– katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti 

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** – enolični ID računalnika, ki ga uporablja Windows SQM 

  - **Data\_SusClientID** – identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktorunscenarioinstalltaskfinalintegrate"></a>Office.ClickToRun.Scenario.InstallTaskFinalintegrate

Podatki o zalogi in nastavitvi Officea, ki se zberejo, ko namestitveni program za Office namešča nove licence in nastavitve registra. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeove namestitve.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion** – različica, na katero bo posodobljen Office 15

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove**– katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti 

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** – enolični ID računalnika, ki ga uporablja Windows SQM 

  - **Data\_SusClientID** – identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktorunscenarioinstalltaskfonts"></a>Office.ClickToRun.Scenario.InstallTaskFonts

Podatki o zalogi in nastavitvi Officea, ki se zberejo, ko namestitveni program za Office namešča pisave. Uporabljajo se za merjenje uspešnosti/neuspešnosti namestitev Officea.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion** – različica, na katero bo posodobljen Office 15 

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake 

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove**– katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** – enolični ID računalnika, ki ga uporablja Windows SQM 

  - **Data\_SusClientID** – identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktorunscenarioinstalltaskinitupdates"></a>Office.ClickToRun.Scenario.InstallTaskInitupdates

Podatki o zalogi in nastavitvi Officea, ki se zberejo, ko namestitveni program za Office ustvarja nastavitve za pravilno delovanje posodobitev. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeove namestitve.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion** – različica, na katero bo posodobljen Office 15 

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake 

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove**– katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** – enolični ID računalnika, ki ga uporablja Windows SQM 

  - **Data\_SusClientID** – identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktorunscenarioinstalltaskintegrateinstall"></a>Office.ClickToRun.Scenario.InstallTaskIntegrateinstall

Podatki o zalogi in nastavitvi Officea, ki se zberejo, ko namestitveni program za Office ustvarja vnose v register za Officeove aplikacije. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeove namestitve.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion** – različica, na katero bo posodobljen Office 15

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake 

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove**– katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti 

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** – enolični ID računalnika, ki ga uporablja Windows SQM

  - **Data\_SusClientID** – identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktorunscenarioinstalltasklastrun"></a>Office.ClickToRun.Scenario.InstallTaskLastrun

Podatki o zalogi in nastavitvi Officea, ki se zberejo, ko namestitveni program za Office dokončuje namestitev, pripenja bližnjice in ustvarja dokončne nastavitve registra. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeove namestitve.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion** – različica, na katero bo posodobljen Office 15

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake 

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove**–  katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** – enolični ID računalnika, ki ga uporablja Windows SQM

  - **Data\_SusClientID** – identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktorunscenarioinstalltaskmigrate"></a>Office.ClickToRun.Scenario.InstallTaskMigrate

Podatki o zalogi in nastavitvi Officea, ki se zberejo, ko namestitveni program za Office seli nastavitve iz starejših različic Officea. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeove namestitve.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion** – različica, na katero bo posodobljen Office 15

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove**– katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** – enolični ID računalnika, ki ga uporablja Windows SQM

  - **Data\_SusClientID** –  identifikator za posodobitev Officea v računalniku

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktorunscenarioinstalltaskpublishrsod"></a>Office.ClickToRun.Scenario.InstallTaskPublishrsod

Podatki o zalogi in nastavitvi Officea, ki se zberejo, ko namestitveni program za Office objavlja navidezni register za navidezno plast AppV. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeove namestitve.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion** – različica, na katero bo posodobljen Office 15

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove**– katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr. namestitev 

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** – enolični ID računalnika, ki ga uporablja Windows SQM

  - **Data\_SusClientID** – identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktorunscenarioinstalltaskremoveinstallation"></a>Office.ClickToRun.Scenario.InstallTaskRemoveinstallation

Podatki o zalogi in nastavitvi Officea, ki se zberejo, ko namestitveni program za Office odstranjuje komponente Officea iz naprave. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeove namestitve.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion –**  različica, na katero bo posodobljen Office 15 

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake 

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove**– katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti 

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** – enolični ID računalnika, ki ga uporablja Windows SQM

  - **Data\_SusClientID** – identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktorunscenarioinstalltaskstream"></a>Office.ClickToRun.Scenario.InstallTaskStream

Podatki o zalogi in nastavitvi Officea, ki se zberejo, ko namestitveni program za Office prenaša nove datoteke za Office. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeove namestitve.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion –**  različica, na katero bo posodobljen Office 15 

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake 

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove –** katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti 

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** –  enolični ID računalnika, ki ga uporablja Windows SQM 

  - **Data\_SusClientID** –  identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktorunscenarioinstalltaskuninstallcentennial"></a>Office.ClickToRun.Scenario.InstallTaskUninstallcentennial

Podatki o zalogi in nastavitvi Officea, ki se zberejo, ko namestitveni program za Office odstranjuje prejšnjo različico Officea iz Trgovine. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeove namestitve.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion** – različica, na katero bo posodobljen Office 15 

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake 

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove**– katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti 

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** –  enolični ID računalnika, ki ga uporablja Windows SQM

  - **Data\_SusClientID** – identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktorunscenariorepairtaskfinalintegrate"></a>Office.ClickToRun.Scenario.RepairTaskFinalintegrate

Podatki o zalogi in nastavitvi Officea, ki se zberejo, ko odjemalec za popravilo Officea znova objavi datoteke .msi in Officeove razširitve. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeovega popravila.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion –**  različica, na katero bo posodobljen Office 15 

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake 

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove**– katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti 

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** –  enolični ID računalnika, ki ga uporablja Windows SQM 

  - **Data\_SusClientID** – identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktorunscenariorepairtaskfullrepair"></a>Office.ClickToRun.Scenario.RepairTaskFullrepair

Podatki o zalogi in nastavitvi Officea, ki se zberejo, ko odjemalec za popravila v Officeu prenese najnovejšo različico odjemalca s tehnologijo zagona s klikom, da pripravi računalnik na odstranitev in vnovično namestitev. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeovega popravila.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion** – različica, na katero bo posodobljen Office 15 

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake 

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove**– katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti 

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** –  enolični ID računalnika, ki ga uporablja Windows SQM 

  - **Data\_SusClientID** – identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktorunscenariorepairtaskintegraterepair"></a>Office.ClickToRun.Scenario.RepairTaskIntegraterepair

Podatki o zalogi in nastavitvi Officea, ki se zberejo, ko odjemalec za popravila v Officeu poskuša popraviti nekatere znane vnose v registru z napakami. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeovega popravila.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion** – različica, na katero bo posodobljen Office 15 

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake 

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove**– katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti 

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** –  enolični ID računalnika, ki ga uporablja Windows SQM 

  - **Data\_SusClientID** – identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktorunscenariorepairtaskremoveinstallation"></a>Office.ClickToRun.Scenario.RepairTaskRemoveinstallation

Podatki o zalogi in nastavitvi Officea, ki se zberejo, ko odjemalec za popravila v Officeu iz naprave odstrani Office, da pripravi napravo na vnovično namestitev pri popravilu. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeovega popravila.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion** – različica, na katero bo posodobljen Office 15 

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake 

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove**–  katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti 

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** –  enolični ID računalnika, ki ga uporablja Windows SQM 

  - **Data\_SusClientID** – identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktorunscenarioupdatetaskintegrateupdate"></a>Office.ClickToRun.Scenario.UpdateTaskIntegrateupdate 

Podatki o zalogi in nastavitvi Officea se zberejo, ko odjemalec s tehnologijo zagona s klikom po potrebi posodobi licence. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeove posodobitve.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion** – različica, na katero bo posodobljen Office 15 

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake 

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove**– katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti 

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** –  enolični ID računalnika, ki ga uporablja Windows SQM 

  - **Data\_SusClientID** – identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktorunscenarioupdatetaskpublishrsod"></a>Office.ClickToRun.Scenario.UpdateTaskPublishrsod

Podatki o zalogi in nastavitvi Officea se zberejo, ko odjemalec s tehnologijo zagona s klikom posodobi nastavitve registra za nove binarne vrednosti. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeove posodobitve.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion** – različica, na katero bo posodobljen Office 15 

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake 

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove**– katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti 

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** –  enolični ID računalnika, ki ga uporablja Windows SQM 

  - **Data\_SusClientID** – identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktorunscenarioupdatetaskupdateapply"></a>Office.ClickToRun.Scenario.UpdateTaskUpdateapply

Podatki o zalogi in nastavitvi Officea se zberejo, ko odjemalec s tehnologijo zagona s klikom po potrebi zaustavi aplikacije, ki se izvajajo, in namesti nove datoteke, ki so bile prenesene. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeove posodobitve.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion** – različica, na katero bo posodobljen Office 15 

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_AvailableVersion to** – katera različica Officea je na voljo za posodobitev

  - **Data\_CompletedWithoutActionInfo** – zakaj nismo dokončali scenarija, npr. aplikacije so bile odprte

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_CorruptionChecksOnly** – ali iščemo samo poškodbe brez posodobitev

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_HardlinkingException** – izjema, na katero smo naleteli med ustvarjanjem povezav

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Podatki\_PackageOperationSuccessful** – vrednost »True«, če smo uspešno dokončali opravilo v Officeovem paketu

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove**– katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti 

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** –  enolični ID računalnika, ki ga uporablja Windows SQM

  - **Data\_SusClientID** –  identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

  - **Data\_WorkstationLockState** – vrednost »True«, če menimo, da je računalnik zaklenjen

### <a name="officeclicktorunscenarioupdatetaskupdateclientdownload"></a>Office.ClickToRun.Scenario.UpdateTaskUpdateclientdownload

Podatki o zalogi in nastavitvi Officea se zberejo, ko odjemalec s tehnologijo zagona s klikom prenese novo različico. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeove posodobitve.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion** – različica, na katero bo posodobljen Office 15 

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake 

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove**– katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti 

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** – enolični ID računalnika, ki ga uporablja Windows SQM

  - **Data\_SusClientID** – identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktorunscenarioupdatetaskupdatedetection"></a>Office.ClickToRun.Scenario.UpdateTaskUpdatedetection

Podatki o zalogi in nastavitvi Officea se zberejo, ko odjemalec s tehnologijo zagona s klikom preveri, ali je na voljo nova posodobitev. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeove posodobitve.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion** – različica, na katero bo posodobljen Office 15 

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_AvailableVersion** – katera različica Officea je na voljo za posodobitev

  - **Data\_ComAction** – število, ki predstavlja dejanje com, ki ga izvajamo

  - **Data\_CompletedWithoutActionInfo** – zakaj nismo dokončali scenarija, npr. aplikacije so bile odprte

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Data\_PackageUpdateAvailable** – vrednost »True«, če je na voljo nova različica Officea

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove –** katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** –  enolični ID računalnika, ki ga uporablja Windows SQM 

  - **Data\_SusClientID** –  identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktorunscenarioupdatetaskupdatedownload"></a>Office.ClickToRun.Scenario.UpdateTaskUpdatedownload

Podatki o zalogi in nastavitvi Officea se zberejo, ko odjemalec s tehnologijo zagona s klikom prenaša novo posodobitev. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeove posodobitve.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion –**  različica, na katero bo posodobljen Office 15 

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_AvailableVersion** – katera različica Officea je na voljo za posodobitev

  - **Data\_CompletedWithoutActionInfo** – zakaj nismo dokončali scenarija, npr. aplikacije so bile odprte

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_CorruptionChecksOnly** – ali iščemo samo poškodbe brez posodobitev

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_FoundCorruptFiles** – vrednost »True«, če smo odkrili poškodovane datoteke

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Podatki\_PackageOperationSuccessful** – vrednost »True«, če smo uspešno dokončali opravilo v Officeovem paketu

  - **Data\_PipelineExitCode** – koda izhoda, ki smo jo prejeli od cevovoda

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove**– katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti 

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** – enolični ID računalnika, ki ga uporablja Windows SQM 

  - **Data\_SusClientID** – identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktorunscenarioupdatetaskupdatefinalize"></a>Office.ClickToRun.Scenario.UpdateTaskUpdatefinalize

Podatki o zalogi in nastavitvi Officea, ki se zberejo, ko odjemalec s tehnologijo zagona s klikom počisti posodobitev in obnovi aplikacije, ki so bile prej odprte. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeove posodobitve.

Zbrana so sledeča polja:

  - **Data\_15\_SourceType** – mesto vira za Office 15, npr. CDN ali lokalno 

  - **Data\_15\_UpdatesEnabled** – ali so omogočene posodobitve za Office 15 

  - **Data\_15\_UpdateVersion –**  različica, na katero bo posodobljen Office 15 

  - **Data\_15\_Version** – različica za Office 15 

  - **Data\_16\_SourceType** – mesto vira za Office 16, npr. CDN ali lokalno 

  - **Data\_16\_UpdatesEnabled** – ali so omogočene posodobitve za Office 16 

  - **Data\_16\_UpdateVersion** – različica, na katero bo posodobljen Office 16 

  - **Data\_16\_Version** – različica za Office 16 

  - **Data\_AddingFixedProducts** – izdelki, ki jih bomo dodali 

  - **Data\_AddingProducts** – katere izdelke naj dodamo 

  - **Data\_CompletionState** – ali smo dokončali opravilo

  - **Data\_ErrorCode** – koda napake, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_ErrorDetails** – dodatne podrobnosti napake 

  - **Data\_ErrorMessage** – sporočilo napake 

  - **Data\_ErrorSource** – mesto napake 

  - **Data\_ExceptionType** – izjema, zaradi katere ni bilo mogoče dokončati opravila 

  - **Data\_IsErrorCodeIgnorable** – ali je kodo napake, zaradi katere ni bilo mogoče dokončati opravila, mogoče prezreti 

  - **Data\_IsErrorCodeIgnorableForScenarioHealth** – ali menimo, da je kodo napake mogoče prezreti 

  - **Data\_NewestPackageVersion** – najnovejša različica Officea v računalniku 

  - **Data\_OldestPackageVersion** – najstarejša različica Officea v računalniku 

  - **Data\_ProductsToAdd** – katere Officeove izdelke bomo dodali 

  - **Data\_ProductsToRemove**– katere Officeove izdelke bomo odstranili 

  - **Data\_RemovingFixedProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_RemovingProducts** – izdelki, ki jih bomo odstranili 

  - **Data\_ScenarioInstanceID** – enolični GUID za scenarij, ki se izvaja 

  - **Data\_ScenarioName** – kateri scenarij se izvaja, npr namesti 

  - **Data\_ScenarioSubType** – katero vrsto scenarija izvajamo, npr. odstrani, znova namesti 

  - **Data\_SourceType** – mesto vira, npr. CDN 

  - **Data\_SqmMachineID** –  enolični ID računalnika, ki ga uporablja Windows SQM 

  - **Data\_SusClientID** –  identifikator za posodobitev Officea v računalniku 

  - **Data\_TaskState** – v katerem stanju je opravilo, npr. izvajanje ali preklic 

  - **Data\_TotalClientCabSize** – velikost kabine odjemalca 

  - **Data\_TriggeringUI** – kaj je sprožilo uporabniški vmesnik 

  - **Data\_UpdatesEnabled** – ali so omogočene posodobitve za Office 

  - **Data\_Version** – različica Officea 

### <a name="officeclicktoruntransport"></a>Office.ClickToRun.Transport

Poročila v datoteki Prenesite dejanja, da ugotovite uspešnost operacije, vrsto prenosa izvedenih in diagnostičnih informacij.


- **BytesFromGroupPeers –** bajti iz skupinskega sovrstnika, le za prenose z uporabo optimizacije dostave

- **BytesFromHttp –** bajti od http, le za prenose z uporabo optimizacije dostave

- **BytesFromInternetPeers –** bajti iz skupinskega sovrstnika, le za prenose z uporabo optimizacije dostave 

- **BytesFromLanPeers –** bajti iz Lan vrstnikov, le za prenose z uporabo optimizacije dostave 

- **cancelledJobs –** število preklicanih zahtev v seji

- **Povezano –** ne glede na to, ali je povezano z virom

- **ErrorCode –** koda zadnje napake

- **ErrorDetails –** podrobnosti o zadnji napaki

- **»ErrorMessage«–** sporočilo o zadnji napaki 

- **ErrorSource –** vir zadnje napake npr. povezava, LoadFile ali LoadRange

- **FailedJob –** število spodletelih zahtev v seji

- **Velikost datoteke -**   velikosti vira

- **SourcePathNoFilePath –** izvorna pot vira le vir http je Javljena, lokalna pot datoteke ali pot UNC je filtrirana

- **SucceededJobs –** število uspešnih zahtev v seji

- **TotalJobs –** skupno število zahtev v seji

- **TotalRequestedBytes –** skupni zahtevani bajti v seji

- **TotalTransferTime –** skupen čas prenosa v seji

- **TransferredBytes –** vsota prenesenih bajtov v seji

- **TransportType –** vrsta prevoza (na primer v pomnilniku optimizacija, http, ozadje inteligentna storitev prenosa)



### <a name="officeclicktoruntransportexperimentaltransportpipelinecreatetransport"></a>Office.ClickToRun.Transport.ExperimentalTransport.PipelineCreateTransport

Podatki o zalogi in nastavitvi Officea se zberejo, ko odjemalec s tehnologijo zagona s klikom ustvarja tok za prenos Officeovih datotek. Dogodki se uporabljajo za določanja stanja različnih tehnologij prenosa (npr. HTTP, BITS, SO), kar je kritičnega pomena za pravilno prenašanje Officea za namestitev in posodobitve.

Zbrana so sledeča polja:

  - **Data\_IsForeGroundStreaming** – ali pretočno predvajamo v ospredje oziroma ozadje

  - **Data\_IsInstallMode** – ima vrednost 1, če nameščamo in prenašamo datoteke, oziroma vrednost 0, če jih ne

  - **Data\_SourceProtocol** – ali prenašamo iz podatkovnega omrežja vsebine, CDN-ja, računalnika, ki predstavlja mesto namestitve, lokalno ali iz vira v lokalnem območnem omrežju

  - **Data\_Status** – uspeh ali neuspeh 

### <a name="officeclicktorunupdatestatus"></a>Office.ClickToRun.UpdateStatus

Podatki o zalogi in nastavitvi Officea se zberejo, ko odjemalec s tehnologijo zagona s klikom končuje stanje posodobitve

Zbrana so sledeča polja:

  - **Data\_build** – trenutno nameščena Officeova različica

  - **Data\_channel** – kanal, v katerega je prijavljen uporabnik

  - **Data\_errorCode** – koda celega števila, ki določa vrsto morebitne nastale napake

  - **Data\_errorMessage** – niz z opisom morebitne nastale napake

  - **Data\_status** – kratko stanje o poteku med posodobitvijo, npr. »Uspelo« ali »Ni uspelo«

  - **Data\_targetBuild** – različica Officea, na katero želimo posodobiti


### <a name="officeclicktorununiversalbootstrapperapplication"></a>Office.ClickToRun.UniversalBootstrapper.Application

Poroča o rezultatu poskusa pokončne namestitve

 - **ErrorCode –** celoštevilska vrednost, povezana z neobravnavano izjemo

 - **ErrorDetails –** niz, v katerem je opisana lokacija, kjer je prišlo do neobravnavane izjeme (funkcija, datoteka, številka vrstice, dodatni parametri, ki jih je nastavil gumb »thrower«)

 - **ErrorMessage –** niz, ki je definiran na mestu, kjer je bila zavrnjena neobravnavana izjema, z opisom narave napake

 - **ErrorType –** niz z opisom kategorije neobravnavane izjeme

 - **ExitCode –** celo število, ki je povezano z rezultatom zagona Bootstrapper, pri čemer je razvidno, da je uspeh v primerjavi s posebnimi vrstami spodletelih.

### <a name="officeclicktorununiversalbootstrappercalculateparameters"></a>Office.ClickToRun.UniversalBootstrapper.CalculateParameters

Poročila o dejanjih, ki jih je zaradi vnosa, zbranega z CollectParameters

- **BitField –** celoštevilska vrednost argumenta BitField, ki nam pove, ali je zahtevana izrecna namestitev/posodobitev kanala. Na primer kanal beta, Trenutni kanal (predogled), trenutni kanal, Mesečni kanal za podjetja, Polletni kanal za podjetja (predogled) ali Polletni kanal za podjetja.

- **ChannelID –** celo število, ki predstavlja vrednost enum izbranega kanala za posodobitev/namestitev. Na primer kanal beta, Trenutni kanal (predogled), trenutni kanal, Mesečni kanal za podjetja, Polletni kanal za podjetja (predogled), Polletni kanal za podjetja ali Neveljaven.

- **CMDMode –** prijazen niz, ki ustreza celotnemu načinu zamenjave načina, je bil zaznan v argumentih cmd, ki so bili preneseni v exe.

- **C2RClientUICulture –** kultura C2R odjemalca za namestitev

- **ErrorCode –** celoštevilska vrednost, povezana z neobravnavano izjemo

- **ErrorDetails –** niz, v katerem je opisana lokacija, kjer je prišlo do neobravnavane izjeme (funkcija, datoteka, številka vrstice, dodatni parametri, ki jih je nastavil gumb »thrower«)

- **ErrorMessage –** niz, ki je definiran na mestu, kjer je bila zavrnjena neobravnavana izjema, z opisom narave napake

- **ErrorType –** niz z opisom kategorije neobravnavane izjeme

- **ExcludedApps –** niz, na katerem so na voljo imena posameznih Officeovih aplikacij, ki jih želite izključiti iz nameščenih Officeovih zbirk

- **InstalledCabVersion –** različica» 16.0. xxxxx. llll «, ki jo je že namestil odjemalec za Office C2R.

- **InstalledProductVersion –** različica programa za Office C2R, ki je že nameščena v različici» 16.0. xxxxx. llll «

- **IsC2RServiceRunning –** znakovni niz tipa Boolean, ki označuje, ali je v napravi nameščeno lokalno strojno storitev C2R odjemalca.

- **IsElevatedFlagSet –** znakovni niz tipa Boolean, ki označuje, ali je Bootstrapper že poskusil pridobiti skrbniško zvišanje

- **IsFireFlyInstalled –** znakovni niz tipa Boolean, ki označuje, ali je trenutno nameščen odjemalec sistema Office 2013 RTM C2R

- **IsFireflyServiceRunning –** znakovni niz tipa Boolean, ki označuje, ali je storitev lokalnega računalnika odjemalca 2013 RTM C2R in deluje v napravi

- **IsOfficeInstalled –** znakovni niz tipa Boolean, ki označuje, ali je že nameščen sodobni Officeov odjemalec.

- **OfficeCultures –** seznam Office kultur, ki jih je treba namestiti

- **OfficeSourceType –** prijazna vrvica, povezana z vrednostjo enum za vir namestitve (CDN, http, UNC, CMBITS, DVD, Local)

- **Poreklo –** vrednost niza, ki nam sporoča, kateri od podprtih izvorov (Puerto Rico [PR], Singapur [SG], Dublin [DB]) bi bilo treba uporabiti za začetno pretočni prenos

- **PlatformFromLink –** niz, ki označuje zahtevano x86 | x64 | privzeta bitnostjo sistema Office, ki ga zahteva storitev C2R setup

- **PlatformOfExistingInstallation –** niz, ki označuje, ali je bil x86 vs. x64 Office že nameščen v napravi

- **PlatformToInstall –** niz, ki označuje končno odločitev o tem, ali je treba namestiti x86 vs. x64 Office. Možnosti so: Autorun, Configure, Consumer, download, Help, pakirnice

- **PRID –** vrednost niza, ki predstavlja zahtevani ID izdaje izdelka v scenariju namestitve potrošnika (na primer »O365ProPlusRetail«)

- **PridsToMigrateFromCentennial–** niz Officeovih izdelkov, ki jih želite preseliti iz Store, ki jih želite zagnati s tehnologijo »zagon s klikom«

- **ProductsToAdd –** sestavljen niz, ki naroča C2R odjemalcu, na katerem je treba namestiti kombinacije izdelka/kulture.

- **ProductsToMigrateFromO15C2R –** niz Officeovih izdelkov in kultur za selitev iz namestitve sistema Office 2013 s tehnologijo »zagon s klikom«

- **ProductsToRemove –** sestavljen niz, ki naroča C2R odjemalcu, na katerem so kombinacije izdelkov/kulture, ki jih je treba odstraniti

- **SharedComputerLicensing –** znakovni niz tipa Boolean, ki označuje, ali je skrbnik za IT zahteval nastavitev, ki omogoča funkcijo »SharedComputerLicensing«

- **ShouldActivate –** znakovni niz tipa Boolean, ki označuje, ali je skrbnik za IT zahteval samodejno aktivacijo licenc, ki je bil izveden v konfiguraciji. XML

- **ShouldUninstallCentennial –** znakovni niz tipa Boolean, ki označuje, ali naj bodo Officeove izdelke iz Store odstranjene

- **VersionToInstall –** vrednost niza Officea »16.0. xxxxx. llll«, ki je nameščena
 

### <a name="officeclicktorununiversalbootstrappercollectembeddedsignature"></a>Office.ClickToRun.UniversalBootstrapper.CollectEmbeddedSignature

Poročila o dejanjih, ki preberejo označeno vnašanje iz vdelanega podpisa exe.  To je nedokazano pojmovanje prejšnjega ponovitve namestitve. exe ni bilo mogoče izvesti in je odvisno od tega, na kaj se zanašamo, da bi v postopku setup. exe prenašali možnosti uporabnikov izdelek/jezik/bitnostjo.
 
- **ErrorCode –** celoštevilska vrednost, povezana z neobravnavano izjemo

- **ErrorDetails –** niz, v katerem je opisana lokacija, kjer je prišlo do neobravnavane izjeme (funkcija, datoteka, številka vrstice, dodatni parametri, ki jih je nastavil gumb »thrower«)

- **ErrorMessage –** niz, ki je definiran na mestu, kjer je bila zavrnjena neobravnavana izjema, z opisom narave napake

- **ErrorType –** niz z opisom kategorije neobravnavane izjeme

### <a name="officeclicktorununiversalbootstrappercollectparameters"></a>Office.ClickToRun.UniversalBootstrapper.CollectParameters

Sporoči parametre, ki se uporabljajo za namestitev Officea

- **BitField –** celoštevilska vrednost argumenta BitField, ki nam pove, ali je zahtevana izrecna namestitev/posodobitev kanala. Na primer kanal beta, Trenutni kanal (predogled), trenutni kanal, Mesečni kanal za podjetja, Polletni kanal za podjetja (predogled) ali Polletni kanal za podjetja.

- **ChannelID –** celo število, ki predstavlja vrednost enum izbranega kanala za posodobitev/namestitev. Na primer kanal beta, Trenutni kanal (predogled), trenutni kanal, Mesečni kanal za podjetja, Polletni kanal za podjetja (predogled), Polletni kanal za podjetja ali Neveljaven.

- **CMDMode –** prijazen niz, ki ustreza celotnemu načinu zamenjave načina je bil zaznan v argumentih cmd, ki so bili preneseni v exe. Možnosti so: Autorun, Configure, Consumer, download, Help, pakirnice

- **C2RClientUICulture –** kultura C2R odjemalca za namestitev

- **ErrorCode –** celoštevilska vrednost, povezana z neobravnavano izjemo

- **ErrorDetails –** niz, v katerem je opisana lokacija, kjer je prišlo do neobravnavane izjeme (funkcija, datoteka, številka vrstice, dodatni parametri, ki jih je nastavil gumb »thrower«)

- **ErrorMessage –** niz, ki je definiran na mestu, kjer je bila zavrnjena neobravnavana izjema, z opisom narave napake

- **ErrorType –** niz z opisom kategorije neobravnavane izjeme

- **ExcludedApps –** niz, na katerem so na voljo imena posameznih Officeovih aplikacij, ki jih želite izključiti iz nameščenih Officeovih zbirk

- **InstalledCabVersion –** različica» 16.0. xxxxx. llll «, ki jo je že namestil odjemalec za Office C2R.

- **InstalledProductVersion –** različica programa za Office C2R, ki je že nameščena v različici» 16.0. xxxxx. llll «

- **IsC2RServiceRunning –** znakovni niz tipa Boolean, ki označuje, ali je v napravi nameščeno lokalno strojno storitev C2R odjemalca.

- **IsElevatedFlagSet –** znakovni niz tipa Boolean, ki označuje, ali je Bootstrapper že poskusil pridobiti skrbniško zvišanje

- **IsFireFlyInstalled –** znakovni niz tipa Boolean, ki označuje, ali je trenutno nameščen odjemalec sistema Office 2013 RTM C2R

- **IsFireflyServiceRunning –** znakovni niz tipa Boolean, ki označuje, ali je storitev lokalnega računalnika odjemalca 2013 RTM C2R in deluje v napravi

- **IsOfficeInstalled –** znakovni niz tipa Boolean, ki označuje, ali je že nameščen sodobni Officeov odjemalec.

- **OfficeCultures –** seznam Office kultur, ki jih je treba namestiti

- **OfficeSourceType –** prijazna vrvica, povezana z vrednostjo enum za vir namestitve (CDN, http, UNC, CMBITS, DVD, Local)

- **Poreklo –** vrednost niza, ki nam sporoča, kateri od podprtih izvorov (Puerto Rico [PR], Singapur [SG], Dublin [DB]) bi bilo treba uporabiti za začetno pretočni prenos

- **PlatformFromLink –** niz, ki označuje zahtevano x86 | x64 | privzeta bitnostjo sistema Office, ki ga zahteva storitev C2R setup

- **PlatformOfExistingInstallation –** niz, ki označuje, ali je bil x86 vs. x64 Office že nameščen v napravi

- **PlatformToInstall –** niz, ki označuje končno odločitev o tem, ali je treba namestiti x86 vs. x64 Office.

- **PRID –** vrednost niza, ki predstavlja zahtevani ID izdaje izdelka v scenariju namestitve potrošnika (na primer »O365ProPlusRetail«)

- **PridsToMigrateFromCentennial–** niz Officeovih izdelkov, ki jih želite preseliti iz Store, ki jih želite zagnati s tehnologijo »zagon s klikom«

- **ProductsToAdd –** sestavljen niz, ki naroča C2R odjemalcu, na katerem je treba namestiti kombinacije izdelka/kulture.

- **ProductsToMigrateFromO15C2R –** niz Officeovih izdelkov in kultur za selitev iz namestitve sistema Office 2013 s tehnologijo »zagon s klikom«

- **ProductsToRemove –** sestavljen niz, ki naroča C2R odjemalcu, na katerem so kombinacije izdelkov/kulture, ki jih je treba odstraniti

- **SharedComputerLicensing –** znakovni niz tipa Boolean, ki označuje, ali je skrbnik za IT zahteval nastavitev, ki omogoča funkcijo »SharedComputerLicensing«

- **ShouldActivate –** znakovni niz tipa Boolean, ki označuje, ali je skrbnik za IT zahteval samodejno aktivacijo licenc, ki je bil izveden v konfiguraciji. XML

- **ShouldUninstallCentennial –** znakovni niz tipa Boolean, ki označuje, ali naj bodo Officeove izdelke iz Store odstranjene

- **VersionToInstall –** vrednost niza Officea »16.0. xxxxx. llll«, ki je nameščena

### <a name="officeclicktorununiversalbootstrapperexecute"></a>Office.ClickToRun.UniversalBootstrapper.Execute

Poročila o izvedenih sprejetih dejanjih, kot je določeno z obrazloženimi podatki iz »CalculateParameters«

- **AvailableClientVersionText –** vrednost niza odjemalca C2R» 16.0. xxxxx. llll «, ki je na voljo v XML deskriptorju različice, ki se uporablja za določanje, ali je treba posodobiti trenutno nameščenega odjemalca C2R

- **CleanFireflyAction –** »TRUE«, če je načrtovano opravilo »CleanFireflyAction«, ki se izvaja med to namestitvijo

- **CleanO15Action –** »TRUE«, če je načrtovano opravilo »CleanO15Action«, ki se izvaja med to namestitvijo

- **CMDMode –** prijazen niz, ki ustreza celotnemu načinu zamenjave načina je bil zaznan v argumentih cmd, ki so bili preneseni v exe. Možnosti so: Autorun, Configure, Consumer, download, Help, pakirnice

- **DeliveryMechanism –** GUID »FFNRoot«, ki je bil pridobljen iz XML deskriptorja različic (ki ga je ožigosal RDX), v katerem je navedeno, za katero publiko/kanal je prišel vir gradnje

- **DownloadC2RClientAction –** »TRUE«, če je načrtovano opravilo »DownloadC2RClientAction«, ki se izvaja med to namestitvijo

- **ErrorCode –** celoštevilska vrednost, povezana z neobravnavano izjemo

- **ErrorDetails –** niz, v katerem je opisana lokacija, kjer je prišlo do neobravnavane izjeme (funkcija, datoteka, številka vrstice, dodatni parametri, ki jih je nastavil gumb »thrower«)

- **ErrorMessage –** niz, ki je definiran na mestu, kjer je bila zavrnjena neobravnavana izjema, z opisom narave napake

- **ErrorType –** niz z opisom kategorije neobravnavane izjeme

- **ExitCode –** celo število, ki je povezano z rezultatom zagona izvršitvene faze Bootstrapper, pri čemer je navedeno, da je uspeh v primerjavi s posebnimi vrstami spodletelih.

- **LaunchAction –** » TRUE «, če je načrtovano opravilo» LaunchAction «, ki se izvaja med to namestitvijo

- **LaunchUpdateAction –** »TRUE«, če je načrtovano opravilo »LaunchUpdateAction«, ki se izvaja med to namestitvijo

- **PreReqResult –** celo število enum vrednosti rezultata, ko so bile izvedene predzahtevi kontrole (pass/neuspel/ponovni zagon)

- **UnexpectedAction –** »TRUE«, če je v tej namestitvi načrtovano opravilo »UnexpectedAction« (primer napake)

- **VersionToInstall –** vrednost niza Officea »16.0. xxxxx. llll«, ki je nameščena

### <a name="officeserviceabilitymanagerinventoryaddonheartbeat"></a>Office.ServiceabilityManager.InventoryAddon.Heartbeat

*[Ta dogodek je bil odstranjen iz trenutnih graditev Officea, vendar se bo morda še vedo pojavljal v starejših graditvah.]*

Ta dogodek uporabljamo za pridobivanje standardnih metapodatkov pri vsakem zagonu dodatka zaloge, ki je del upravitelja dosegljivosti storitve za Office, in se uporablja za Officeove informacije o zalogi v teh računalnikih, ki jih je izbral skrbnik za IT. Metapodatki, ki so tukaj zanimivi, je ID seje, ki se uporablja za povezovanje z drugimi podatki, shranjenimi v najemniški storitvi v oblaku.

Ta dogodek ne vsebuje dodatnih polj, kajti pomembni so zgolj metapodatki.

### <a name="officeserviceabilitymanagerinventoryaddonresults"></a>Office.ServiceabilityManager.InventoryAddon.Results

Ta dogodek se zabeleži, ko se pokličete v WebService, ki je bil ustvarjen z dodatkom upravitelja za uporabnost s tehnologijo »zagon s klikom«, ne glede na to, ali je uspešen ali ne. To je pravzaprav zadnji postopek v Dodatku za spremljanje stanja celotnega postopka.

Zbrana so naslednja polja:

- **ActionDetail** – dodatne podrobnosti o tem, kdaj pride do napake.
   - Če je zahteve HTTP uspešna, bo ActionDetail 0.
   - Če polje z rezultati ni v redu (tj. ne 0), kar pomeni, da zahteva ni poslana, bo v tem polju zapisana Notranja koda napake, ki je enaka kot polje z rezultatom.
   - Če je polje rezultat v redu (tj. 0), kar pomeni, da je koda odziva HTTP > = 300, se bo prijavila koda za odziv HTTP (na primer 404).

- **Rezultat** – številske zastavice kode napake, ki jih vrne Office WebService Call API-ji. – na primer 3 pomeni, da je prišlo do težave z inicializacijo glav HTTP.

- **Vnesite** – dodatne informacije vrste. V primeru inventarja te informacije določa vrsto poslanega tovora – na primer polno ali samo Delta sprememb. 

-  **WebCallSource** – vrednost enumeracije (ki je navedena kot celo število), ki označuje dodatek upravitelja za uporabnost, ki je bil vir klica:
   - Zaloga: 0
   - Konfiguracija inventarja: 1
   - Pravilnik o inventarju: 2
   - Stanje omrežnega inventarja: 3
   - Upravitelj uporabnosti: 4
   - Upravljanje: 5

### <a name="officeserviceabilitymanagerwebservicefailure"></a>Office.ServiceabilityManager.WebserviceFailure

Kadar koli klic spletne storitve v okviru dodatkov Office Serviceability Manager ne uspe, je ta izjava zabeležena v dnevnik. Do napak lahko pride zaradi notranjih napak ali nezmožnosti vzpostavitve povezave s spletno storitvijo.

Zbrana so sledeča polja:

- **Dodatek** – dodatek upravitelja s tehnologijo »zagon s klikom«, iz katerega je bil ustvarjen klic za WebService. To lahko vsebuje vrednosti, kot so inventar, obvladljivost itd. kodirano kot številska vrednost.

- **ID korelacije** – naključno ustvarjen GUID, ki je specifičen za trenutni primerek, ki je poslan v WebService za korelacijo klicev med odjemalcem in strežnikom.

- **ErrorInfo** – števila podatkov kode napake, ki jih vrne Office WebService Call API.

- **ErrorMessage** – sporočilo, ki nudi dodatne vpoglede v napako. Vsaka vrsta napake je preslikana v kodiran niz, nekatere vrste napak pa so lahko preslikane v več nizov, odvisno od vrste napake.

- **Funkcija** – funkcija v kodi, iz katere je prišlo do trenutnega klica.

- **Stanje** – koda stanja HTTP, ki jo vrne klic v WebService, na primer 404, 500 itd.


## <a name="enhanced-configuration-service-ecs-events"></a>Dogodki izboljšane konfiguracijske storitve (ECS)

### <a name="officeexperimentationfeaturequerybatched"></a>Office.Experimentation.FeatureQueryBatched

Zbere informacije o vratih funkcije/vratih spremembe, ki jih poizvede izvedena koda.

Zbrana so sledeča polja:

  - **Count** – število poizvedenih vrat funkcije v tem paketnem dogodku

  - **Features** – informacije o poizvedenih vratih

  - **Sequence** – vrstni red, v katerem so bila poizvedena vrata FeatureGate

### <a name="officeexperimentationflightnumberline"></a>Office.Experimentation.FlightNumberLine

Zbere seznam konfiguracij, ki jih odjemalec prejeme od storitve ECS

Zbrana so naslednja polja:

  - **ECSConfigs** – seznam konfiguracij za ECS (vrednosti so med seboj ločene z vejico)

  - **LockType** – vrsta zaklepa FlightManager

  - **TasFlightingVersion** – številka različice

  - **TimeToLock** – čas med začetkom libleta in zaklepom za FlightManager

  - **UnmergedConfigs** – seznam konfiguracij, ki niso spojene

### <a name="officeexperimentationtriggeranalysis"></a>Office.Experimentation.TriggerAnalysis

Ta dogodek omogoča analizo obsega uporabe izdelkov in metrike učinkovitosti delovanja (npr. zrušitve, neodzivnost ipd.) za podnabor porabnikov ali naprav, ki so upravičeni do uporabe zadevne funkcije, s tem pa pomaga zagotoviti, da izdelek deluje pravilno.

Zbrana so naslednja polja:

  - **FeatureGate** – določa nabor funkcij, za katere se uporablja sprožitvena analiza.

### <a name="onenoteflightdefault"></a>OneNote.FlightDefault
 
Ta dogodek se zabeleži, ko OneNote pozove strežnik ECS za vrednosti letenja.  To se uporablja za omogočanje eksperimentalnih funkcij tistim uporabnikom, ki so se odločili za prejem takšnih letov.
 
Zbrana so sledeča polja:
 
- **ConfigParam** – nastavitev, za katero je bila dostopna vrednost

## <a name="licensing-events"></a>Licenciranje dogodkov

### <a name="officelicensingaccepteulaforcurrentlicense"></a>Office.Licensing.AcceptEulaForCurrentLicense 

Ti dogodki so zbrani, ko uporabnik prejme licenco in sprejme licenčne pogoje za Microsoftovo programsko opremo za trenutno licenco.

Dogodki se uporabljajo za zaznavanje, ali je uporabnik v dobrem stanju, za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Zbrana so sledeča polja:

  - **ACID** – identifikator GUID, ki predstavlja Officeov izdelek, za katerega je uporabnik prejel licenco

  - **DwEulaId** – številski identifikator za vrsto licenčnih pogojev za Microsoftovo programsko opremo, ki jo je sprejel uporabnik

### <a name="officelicensingactivation"></a>Office.Licensing.Activation 

Naknadna nastavitev licence v stroju, kjer licenco poskušamo aktivirati s klicem storitve AVS. Sporoča rezultat aktivacijskega klica.

Dogodki so pomembni pri zaznavanju, koliko uporabnikov ima težave pri aktivaciji. Poskrbeli smo za zaznavanje anomalije, s katero zaznamo morebitno regresijo. To je izjemno pomembno, saj imamo zunanje odvisnosti v storitvi AVS, ta signal pa ponazarja, ali naši zunanji partnerji delujejo ustrezno. Te dogodke prav tako uporabljamo za diagnostične namene in preverjanje stanja sistema, ko uporabnik posreduje težavo z računalnikom.

Zbrana so sledeča polja:

  - **Acid** – identifikator GUID, ki predstavlja Officeov izdelek, za katerega je uporabnik prejel licenco

  - **ReferralData** – identifikator za OEM, ki se namesti v Office v računalniku

### <a name="officelicensingactivationwizard"></a>Office.Licensing.ActivationWizard 

Če iz neznanega razloga nismo uspeli samodejno aktivirati licence, uporabniku prikažemo čarovnika za aktivacijo. Ti dogodki nam posredujejo informacije, da je bil čarovnih prikazan uporabniku. Dogodki so pomembni pri zaznavanju, ali je uporabnik v dobrem stanju in ima omogočeno vso funkcionalnost, se uporabljajo za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Ta dogodek ne zbere nobenega polja.

### <a name="officelicensingenforcesigninqualified"></a>Office.Licensing.EnforceSignInQualified 

To je signal, ki nam pove, ali je bil poskus, ki smo ga izvedli za vsilitev vpisa uporabnika v sklopu licenciranja, uspešen. To je ključnega pomena pri zaznavanju uspeha ali neuspeha poskusa, ki uporabnike prisili, da se prijavijo, kar predstavlja obvezen korak pri sodobnem licenciranju. Če se uporabniki ne uspejo vpisati, ne bodo mogli več uporabljati aplikacije.

Zbrana so sledeča polja:

  - **Qualified** – prepozna, ali je uporabnik kvalificiran za vsiljeni vpis

### <a name="officelicensingexpirationdialogshown"></a>Office.Licensing.ExpirationDialogShown

Ti podatki so zbrani, ko se pojavi pogovorno okno poteka, v katerem uporabnik izve, da je potekla njegova licenca. Dogodki so pomembni pri zaznavanju, ali je uporabnik v dobrem stanju in ima omogočeno vso funkcionalnost, se uporabljajo za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Zbrana so sledeča polja:

  - **LicNotificationState** – orodje za oštevilčenje, s katerim ugotovimo, katera vrsta obvestila je bila prikazana uporabniku

### <a name="officelicensingfullvalidation"></a>Office.Licensing.FullValidation 

Ti podatki so zbrani pri vsaki seji, ki sporoča stanje licenciranja v računalniku in sporoča napake, ki se prikažejo uporabniku, zaradi katerih, ne morejo uporabljati aplikacijo. Ta dogodek ponazarja, ali je stanje računalnika uporabnika primerno. Za ta dogodek smo vzpostavili zaznavanje anomalije, s katerim ugotovimo, ali regresija ali mehanizem aktivacije povzroča nepravilno delovanje uporabnika. Ta dogodek je pomemben tudi pri diagnosticiranju težav uporabnika in za nadziranje zdravja sistema.

Zbrana so naslednja polja:

  - **Acid** – identifikator GUID, ki predstavlja Officeov izdelek, za katerega je uporabnik prejel licenco 
  
  - **ActivationAttributes** – vrsta mehanizma aktivacije, ki ga uporablja uporabnik.

  - **IsSessionLicensing** – ali je izbran način za aktivacijo računalnika v skupni rabi 

  - **LicenseCategory** – kategorija Officeove licence, ki jo uporabnik uporablja 

  - **Licenses** – seznam imen vseh Officeovih licenc, ki so bile zaznane v računalniku 

  - **LicenseStatuses** – stanje vseh Officeovih licenc, ki so bile zaznane v računalniku 

### <a name="officelicensinggetentitlement"></a>Office.Licensing.GetEntitlement 

Te podatke zberemo, ko uporabnik nastavi napravo in pokličemo storitev licenciranja, da zazna, ali je prijavljeni uporabnik upravičen do Officea ali ne. Da dogodek vrne rezultat klica. Dogodek je pomemben pri zaznavanju, ali je uporabnik v dobrem stanju in nima omogočene vse funkcionalnosti; uporabljajo se za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Zbrana so sledeča polja:

- **EntitlementCount** – število upravičenosti, ki jih je uporabnik


### <a name="officelicensingheartbeat"></a>Office.Licensing.Heartbeat 

Za vsako sejo preverimo, ali je minilo 72 ur od zadnje obnovitve licence, in poskušamo podaljšati potek trenutne licence. S pomočjo tega dogodka lahko ugotovimo, ali je bil klic uspešen ali neuspešen, da lahko podaljšamo potek licence in omogočimo funkcionalnost Officea, ki ga je namestil uporabnik. Pri diagnosticiranju težav, povezanih z naročnino, in težav storitev je ta dogodek ključen za uporabnika in pri zaznavanju regresij za že aktitivrane uporabnike naročnine.

Zbrana so sledeča polja:

  - **Mode** – predstavitev orodja za oštevilčenje zbirke za licenciranje Officea, ki se uporablja v tem računalniku

### <a name="officelicensinginclientpinredemptioncallpinredemptionapi"></a>Office.Licensing.InClientPinRedemption.CallPinRedemptionAPI

V tej telemetriji so prikazani rezultati klicne storitve za prevzem PIN-a.

Zbrana so sledeča polja:

- **ClientTransactionId** – Enolični identifikator za klic storitve.

- **ErrorCategory** – vsaka vrsta napake lahko pade v kategorijo »bolj splošna«, na primer »vnovičen poskus«.

- **ErrorType** – vzrok neuspeha, na primer »AlreadyRedeemedByOther«.

- **InAFOFlow** – znakovni niz tipa Boolean, ki označuje, ali smo v toku AFO redemption.

- **StatusCode** – rezultat klica storitve z eno besedo, na primer »ustvarjeno«.

- **StatusMessage** – podrobnosti o kodi stanja, kot je »uspešno omogočena uporaba«.

- **UsingNulApi** – logična vrednost, ki označuje, ali uporabljamo nov sklad licenciranja.

### <a name="officelicensinginrfm"></a>Office.Licensing.InRFM 

Če se za napravo aktivira način z omejeno funkcionalnostjo, s tem signalom posredujemo, da stanje računalnika ni ustrezno. Dogodek je pomemben pri zaznavanju, ali je uporabnik v dobrem stanju in nima omogočene vse funkcionalnosti; uporabljajo se za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Zbrana so sledeča polja:

  - **ACID** – identifikator GUID, ki predstavlja Officeov izdelek, za katerega je uporabnik prejel licenco

  - **DaysRemaining** – število dni do poteka trenutne Officeove licence

  - **Mode** – predstavitev orodja za oštevilčenje zbirke za licenciranje Officea, ki se uporablja v tem računalniku

  - **ProductName** – ime izdelka, ki ga uporabnik trenutno uporablja

  - **Reason** – koda napake, ki ponazarja vzrok za trenutno stanje licence

### <a name="officelicensinginstallkey"></a>Office.Licensing.InstallKey

Ti podatki so zbrani, ko poskušamo namestiti ključ v napravo za licenciranje računalnika. Dogodek sporoči, ali je bila namestitev uspešna. Če ni bila, prikaže kodo napake. Dogodki so pomembni pri zaznavanju, ali je uporabnik v dobrem stanju in ima omogočeno vso funkcionalnost, se uporabljajo za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Zbrana so sledeča polja:

  - **Prid** – ime skupine izdelkov, za katero se namešča ključ

  - **SkuId** – identifikator GUID, ki predstavlja Officeov izdelek, za katerega se namešča ključ 

### <a name="officelicensinginvokelicensewizard"></a>Office.Licensing.InvokeLicenseWizard

Če zaznamo težave pri aktivacijskem poteku dela, sprožimo čarovnika za licenciranje in posredujemo ta signal. Dogodki so pomembni pri zaznavanju, ali je uporabnik v dobrem stanju in ima omogočeno vso funkcionalnost, se uporabljajo za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Zbrana so sledeča polja:

  - **Acid** – identifikator GUID, ki predstavlja Officeov izdelek, za katerega je uporabnik prejel licenco

  - **LicenseStatus** – stanje Officeove licence, ki jo uporabnik uporablja

  - **MachineKey** – alfanumerični identifikator licenčnega ključa, ki je bil izdan za uporabnika

### <a name="officelicensinglicensingbar"></a>Office.Licensing.LicensingBar

Če ima naprava težave z licenciranjem in uporabniku prikažemo vrstico vodila, pošljemo ta signal, s katerim ponazorimo vrsto vodila, prikazanega uporabniku. Dogodki so pomembni pri zaznavanju, ali je uporabnik v dobrem stanju in ima omogočeno vso funkcionalnost, se uporabljajo za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Zbrana so sledeča polja:

  - **SuppressNotification** – označuje, ali smo onemogočili vrstico vodila za licenciranje

  - **Title** – naslov vrstice vodila za licenciranje, ki je bila prikazana uporabniku

  - **Type** – vrsta vrstice vodila za licenciranje, ki je bila prikazana uporabniku

### <a name="officelicensinglicexitofficeprocess"></a>Office.Licensing.LicExitOfficeProcess 

Ta signal posredujemo, da ponazorimo, da je prišlo do zapiranja ali zrušitve Officea zaradi težave z licenciranjem. Dogodki so pomembni pri zaznavanju, ali je uporabnik v dobrem stanju in ima omogočeno vso funkcionalnost, se uporabljajo za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Zbrana so sledeča polja:

  - **ExitCode** – notranja koda, ki je povzročila zapiranje aplikacije

### <a name="officelicensingloadidentityticket"></a>Office.Licensing.LoadIdentityTicket

Med postopkom licenciranja naprave aplikacija želi naložiti identiteto uporabnika, da preveri, ali je uporabnik upravičen do Officea. Ta dogodek ponazarja uspešnost/neuspešnost licenciranja skupaj s kodo napake. Dogodki so pomembni pri zaznavanju, ali je uporabnik v dobrem stanju in ima omogočeno vso funkcionalnost, se uporabljajo za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Zbrana so sledeča polja:

  - **FederationProvider** – niz, ki identificira ponudnika združevanja za trenutno prijavljenega uporabnika

  - **IdentityProvider** – niz, ki identificira ponudnika identitete za trenutno prijavljenega uporabnika

### <a name="officelicensinglvuxeulaexplicitcrash"></a>Office.Licensing.LVUX.EULAExplicitCrash 

Ti dogodki so zbrani, če uporabniku prikažemo licenčne pogoje za Microsoftovo programsko opremo, uporabnik pa teh pogojev ni sprejel. Aplikacijo smo tako zaprli/zaustavili. Dogodki so pomembni pri zaznavanju, ali je uporabnik v dobrem stanju in ima omogočeno vso funkcionalnost, se uporabljajo za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Zbrana so sledeča polja:

  - **Acid** – identifikator GUID, ki predstavlja Officeov izdelek, za katerega je uporabnik prejel licenco

  - **OptInShown** – ponazarja, ali je bilo izbirno pogovorno okno, ki se prikaže ob prvem zagonu aplikacije, že prikazano

### <a name="officelicensingnextuserlicensingeligible"></a>Office.Licensing.NextUserLicensingEligible 

S tem signalom nam sporočite, ali je uporabnik usposobljen za selitev v nov sklad licenciranja. To je pomembno pri količinskem vplivu na obstoječe uporabnike, ko uvajamo novo zbirko licenciranja, ter da se prepričamo, da uporabniki ne izgubljajo na funkcionalnosti.

Ta dogodek ne zbere nobenega polja.

### <a name="officelicensingnulfetcherfetchmodelfromols"></a>Office.Licensing.Nul.Fetcher.FetchModelFromOls

Če naprava uporablja sodobno zbirko licenciranja, licenčno datoteko poskušamo pridobiti neposredno iz storitve. Ta dogodek sporoča uspešnost ali neuspešnost skupaj s kodo napake storitvenega klica. Dogodki se uporabljajo za zaznavanje, ali je uporabnik v dobrem stanju sodobne zbirke za licenciranje, za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Zbrana so sledeča polja:

  - **MetadataValidationResult** – rezultat preverjanja veljavnosti metapodatkov licence, s katerim se preveri, da metapodatki niso bili spremenjeni

  - **SignatureValidationResult** – rezultat preverjanja veljavnosti podpisa licence, s katerim se preveri, da podpis ni bil spremenjen

### <a name="officelicensingnulvalidationfullvalidation"></a>Office.Licensing.Nul.Validation.FullValidation 

Ti podatki so zbrani ob vsaki seji naprave, ki uporablja sodobno zbirko za licenciranje. Sporočajo stanje licenciranja v računalniku in napake, ki se prikažejo uporabniku, zaradi katerih, ne morejo uporabljati aplikacije. Ta dogodek ponazarja, ali je računalnik, ki ga uporablja uporabnik, v dobrem stanju zbirke za licenciranje. Za ta dogodek smo vzpostavili zaznavanje anomalije, s katerim ugotovimo, ali regresija povzroča nepravilno delovanje uporabnika. Ta dogodek je pomemben tudi pri diagnosticiranju težav uporabnika in za nadziranje zdravja sistema.

Zbrana so sledeča polja:

  - **Acid** – identifikator GUID, ki predstavlja Officeov izdelek, za katerega je uporabnik prejel licenco 

  - **AllAcids** – seznam vseh GUID-jev izdelka, za katere je uporabnik trenutno licenciran 

  - **License** – kategorija Officeove licence, ki jo uporabnik uporablja 

  - **DaysRemaining** – število dni do poteka trenutne Officeove licence 

  - **LIcenseId** – alfanumerični identifikator licence, ki je bil izdan za uporabnika 

  - **LicenseType** – kategorija Officeove licence, ki jo uporabnik uporablja 

### <a name="officelicensingofficeclientlicensingdolicensevalidation"></a>Office.Licensing.OfficeClientLicensing.DoLicenseValidation 

Predstavlja metapodatke za licenciranje, ki se pridobijo iz naprave ob vsakem zagonu, in iz katerih so razvidni identifikator licence, stanje licence, vrsta in druge lastnosti licence. Ti parametri so pomembni pri prepoznavanju nabora funkcij, ki so na voljo za uporabnika. To je zelo pomembno pri prepoznavanju nabora funkcij, ki so na voljo za uporabnika, in ali uporabnik morda ni deležen nekatere funkcionalnosti. Ta dogodek se prav tako uporablja za izračune dnevnih aktivnih uporabnikov/mesečnih aktivnih uporabnikov in za druga poročila, ki jih ustvarjajo različne skupine v Officeu, saj je iz njih razvidna vrsta izdelka, ki ga uporablja uporabnik, ali gre za naročniški izdelek in ali je za uporabnike morda onemogočena določena funkcionalnost.

Zbrana so sledeča polja:

  - **FullValidationMode** – način, ki označuje, da je preverjanje veljavnosti licence v načinu polnega preverjanja 

  - **IsRFM** – označuje, ali je za uporabnika izbran način zmanjšane funkcionalnosti 

  - **IsSCA** – označuje, ali smo izbrali način za aktivacijo računalnika v skupni rabi 

  - **IsSubscription** – označuje, ali uporabnik uporablja naročniško licenco 

  - **IsvNext** – označuje, ali uporabljamo novo sodobno zbirko za licenciranje 

  - **LicenseCategory** – kategorija Officeove licence, ki jo uporabnik uporablja 

  - **LicenseStatus** – stanje Officeove licence, ki jo uporabnik uporablja 

  - **LicenseType** – kategorija Officeove licence, ki jo uporabnik uporablja 

  - **LicensingACID** – identifikator GUID, ki predstavlja Officeov izdelek, za katerega je uporabnik prejel licenco 

  - **OlsLicenseId** – alfanumerični identifikator licence, ki je bil izdan za uporabnika 

  - **SkuIdIsNull** – označuje, ali smo naleteli na težavo, in ne poznamo izdelka, ki ga uporabnik uporablja 

  - **SlapiIsNull** – označuje, ali smo naleteli na težavo pri naseljevanju enega od predmetov licenciranja 

### <a name="officelicensingonlinerepair"></a>Office.Licensing.OnlineRepair 

Ta dogodek se aktivira, če iz neznanega razloga ne uspemo aktivirati uporabnika in mu moramo prikazati pogovorno okno, naj obišče spletno mesto pomoči in poskuša izvesti korake za odpravljanje težav. Dogodki so pomembni pri zaznavanju, ali je uporabnik v dobrem stanju in ima omogočeno vso funkcionalnost, se uporabljajo za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Ta dogodek ne zbere nobenega polja.

### <a name="officelicensingoobetrybuychoice"></a>Office.Licensing.OOBE.TryBuyChoice

Uporabniki z vnaprej nameščenim sistemom Office v novih računalnikih, ki nimajo pravice do Officea, so prikazani v pogovornem oknu, s katerim lahko preskusite, kupite ali vnesete ključ izdelka, da dobi licenco. Ta dogodek zajame dejanje uporabnika v pogovornem oknu. Ta dogodek se uporablja za spremljanje dejanja uporabnika, ki se prikaže v pogovornem oknu, ki je prikazano uporabnikom brez pravic za Office, v katerem je bil Office vnaprej nameščen v računalniku, in pomaga ugotoviti, ali je uporabnik licenciral ali ga ni licenciral z načrtom.

Zbrana so sledeča polja:

- **Nakup** – pove, ali je uporabnik kliknil gumb »kupi« ali ne

- **ForceAutoActivate** – pove, ali želite aktivirati aktiviranje v aplikaciji ali ne

- **GoBackToSignIn** – pove, ali se je uporabnik želel znova vpisati (po možnosti z drugim računom)

- **IsPin** – pove, ali je uporabnik vnesel kodo PIN

- **Productkey** – pove, ali je uporabnik poskusil vnesti ključ izdelka

- **Preskusite** – pove, ali je uporabnik kliknil gumb »poskusi« ali ne

- **UserDismissed** – to pove, ali je uporabnik zavrnil pogovorno okno in je bil torej v načinu »Grace« ali »zmanjšanem načinu«, ker se ni odločil kupiti Office ali dobiti preskusne različice.

### <a name="officelicensingpurchase"></a>Office.Licensing.Purchase 

*[Ta dogodek je bil odstranjen iz trenutnih graditev Officea, vendar se bo morda še vedo pojavljal v starejših graditvah.]*

Preskus, s katerim uporabniku omogočimo samodejno plačevanje za Office neposredno iz aplikacije, ne da bi za to moral zapreti aplikacijo. Ta dogodek ponazarja uspešnost ali neuspešnost poskusa skupaj s kodo napake. Dogodki so pomembni pri zaznavanju, ali je uporabnik v dobrem stanju in ima omogočeno vso funkcionalnost, se uporabljajo za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Zbrana so sledeča polja:

  - **StorePurchaseStatus** – predstavlja kodo napake/kodo uspeha za klic nakupa, ki je bil izveden prek Trgovine Windows

### <a name="officelicensingsearchforsessiontoken"></a>Office.Licensing.SearchForSessionToken

Če je uporabnik izbral način za aktivacijo računalnika v skupni rabi, v računalniku poskušamo poiskati žeton seje, ki uporabniku omogoča uporabo aplikacije. Ta dogodek ponazarja scenarij uspešnosti ali neuspešnosti licenciranja skupaj s kodo napake. Dogodki so pomembni pri zaznavanju, ali je uporabnik v dobrem stanju in ima omogočeno vso funkcionalnost, se uporabljajo za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Zbrana so naslednja polja:

  - **LoadLicenseResult** – predstavlja kodo napake/kodo uspeha, ali smo lahko naložili licence za trenutnega uporabnika

  - **OpportunisticTokenRenewalAttempted** – ponazarja, ali smo poskušali obnoviti žeton za sejo uporabnika

  - **SetAcidResult** – predstavlja kodo napake/kodo uspeha, ali smo identifikator lahko nastavili na pričakovano vrednost

### <a name="officelicensingshownewdeviceactivationdialog"></a>Office.Licensing.ShowNewDeviceActivationDialog

Ob prvem zagonu Officeove aplikacije bomo poskušali prikazati pogovorno okno za vpis z vnaprej izpolnjenimi poverilnicami, ki jih je uporabnik vnesel za prenos Officea. Uporabnik lahko nato nadaljuje vpis s temi poverilnicami, uporabi druge poverilnice ali prezre pogovorno okno. Ta dogodek poroča o dejanju uporabnika ob prikazu tega pogovornega okna. Dogodki se uporabljajo za zaznavanje, ali je uporabnik v dobrem stanju sodobne zbirke za licenciranje, za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Zbrana so sledeča polja:

  - **UserAction** – identifikator za dejanje, ki ga izvede uporabnik, ko se prikaže pogovorno okno.

### <a name="officelicensingskutoskuconversion"></a>Office.Licensing.SkuToSkuConversion

Če moramo v sklopu licenciranja uporabnika spremeniti inventarno številko uporabnika, posredujemo ta signal skupaj s kodo uspeha oziroma neuspeha. Dogodek je pomemben pri zaznavanju, ali je uporabnik v dobrem stanju in nima omogočene vse funkcionalnosti; uporabljajo se za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Zbrana so sledeča polja:

  - **DestinationSku** – ime inventarne številke, v katerega se bo pretvoril trenutno nameščeni izdelek

  - **PendingAcid** – ID izdelka, za katerega je na čakanju pretvorba inventarne številke

  - **SourceSku** – ime izvirne inventarne številke, ki je bila nameščena v računalniku

  - **UninstallProduct** – označuje, ali bo star izdelek odstranjen v sklopu pretvorbe

### <a name="officelicensingtelemetryflowolsresults"></a>Office.Licensing.TelemetryFlow.OLSResults

Če uporabnik ni licenciran, ustvarimo več servisnih klicev, da dobimo uporabnika v licenčno državo in aktiviramo njihov Officeov izdelek.  Ta dogodek se sproži ob pozivu, da storitev Office Licensing preveri, ali ima uporabnik upravičene pravice.  Ta dogodek se bo uporabil za spremljanje stanja licenciranja uporabnikov, ko boste poklicali storitev licenciranja za Office in stanje Officeovega odjemalca, ko boste poskusili dobiti Office aktiviran.

Zbrana so sledeča polja:

- **EntitlementPickerShown** – pove, ali je imela uporabnik več pravic in če je uporabnik moral ročno izbrati od njih, da dobi licenco

- **GetAuthResult** – pove več o tem, da je stranka morda na primer v storitvi, če je na voljo prazna ključa izdelka iz storitve Office Licensing ali če je bila upravičena do drugega izdelka, ki ga je treba pretvoriti v nov izdelek

- **GetEntitlementsCount** – število upravičenosti, ki jih je uporabnik ima

- **GetEntitlementsSucceeded** – pove, ali je klic v storitev Office Licensing API za pridobitev uporabniških pravic uspel ali ne.

- **GetKeySucceeded** – pove, ali je klic v storitev Office Licensing API za pridobitev ključa uspel

- **GetNextUserLicenseResult** – pove, ali je sodobni sklad za licenciranje deloval in če je uporabnik dobil licenco ali ne

- **InstallKeyResult** – pove različne razloge, zakaj je uporabnik morda v slabem stanju, kot je, če aktivacija ni uspela ali če je bila namestitev ključa spodletela

- **NotInitializedBeforeWhileAdding** – to je zgolj informativno in pove, ali je bil dogodek dodan v preslikavo upravitelja telemetrijo, ne da bi ga izrecno registrirali

- **NotInitializedBeforeWhileSending** – to je zgolj informativno sporočilo in pove, ali je bilo poskušeno dogodek poslati, ne da bi ga izrecno prijavili v preslikavi upravitelja telemetrijo pred roko

- **SentOnDestruction** – to je zgolj informativno in pove, ali je bil dogodek dodan v preslikavo upravitelja telemetrijo in ni bil poslan izrecno.

- **Oznaka** – uporablja se za štetje, kjer je bil dogodek poslan iz programa

- **VerifyEntitlementsResult** – pove več o tem, da je uporabnik lahko v storitvi, ko preveri veljavnost upravičenosti, pridobljeno iz storitve Office Licensing

### <a name="officelicensingtelemetryflowsearchforbindingresult"></a>Office.Licensing.TelemetryFlow.SearchForBindingResult

Izvirni izdelovalci opreme prodajajo naprave, ki so vključene v Office (celoletne naročnine ali večne).  Te Officeove izdelke plačate, ko stranka kupi svoj računalnik. Naprave, ki so nastavljene z določenim regkey (OOBEMode: OEMTA), so morda povezane z Officeovo vezavo.  Ko zaženemo Office v teh napravah, izvajamo storitvene preverbe, ali je najdena Officeovo vezava, ki ustreza računalniku.

Ta dejavnost telemetrijo sledi napakam pri uspehu in napaki pri iskanju vezave, tako da lahko zagotovimo, da lahko naprave, ki imajo zavezujočo vezavo, uspešno pridobivajo in da so naše storitve zdrave.  Ta dejavnost ne sledi strojem, ki so na voljo, da ne bi imeli nobenih vezi z njimi, ko jih preverimo z našimi storitvami.

Zbrana so naslednja polja:

- **DexShouldRetry** – znak, da smo pripravili težavo, ki jo je mogoče odpraviti (Internet ali strežniki niso na voljo)

- **GenuineTicketFailure** – nam pove napako HRESULT, ko poskušate dobiti računalnik s sistemom Windows pristno vstopnico/ključ izdelka (WPK).

- **PinValidationFailure** – nam pove, zakaj ni uspelo izvesti postopka preverjanja pristnosti. Morebitne napake so:
    - GeoBlocked
    - InvalidFormat
    - InvalidPin
    - InvalidState
    - InvalidVersion
    - Neznano
    - Uporablja

- **PinValidationResult** – pove nam, kaj je rezultat preverjanja pristnosti kode PIN, ki je ni bilo mogoče razvozlati.

- **Pkpn** – Pkpn obseg, za katerega pripada koda PIN.

- **Uspeh** – pomeni, da smo uspešno pridobivali veljavno Officeovo vezavo (PIN) za napravo.

- **Tag** – pove nam, na kateri stopnji smo nehali iskati vezavo. Možna oznaka:
  - 0x03113809 – med preverjanjem kode PIN napaka ni interneta/storitve.
  - 0x0311380a – napaka pri preverjanju PIN, poslano s poljem »PinValidationFailure«
  - 0x0310410f – uspeh, poslano s poljem »uspeh«
  - 0x0311380d – vnovične napake (težave z internetom, neznane napake)
  - 0x0311380e – napake, ki se ne dajo ponoviti (ponudba za vezavo je potekla)
  - 0x0311380f – druge napake (ki jih ni mogoče licencirati)
  - 0x03104111 – ni uspelo razvozlati Officeovega pina, poslanega z poljem» PinValidationResult «.

- **WpkBindingFailure** – pove napako, da je koda napake pridobila kodo PIN za Office, ki je povezana z WPK računalnika.

### <a name="officelicensingtelemetryflowshowafodialogs"></a>Office.Licensing.TelemetryFlow.ShowAFODialogs

Ko ste uspešno dokončali veljaven Officeov PIN, ki je vezan na računalnik, ki je bil vnaprej povezan s sistemom Office, je uporabnik v pogovornem oknu za vpis ali v pogovorno okno za prevzem.  Ko je koda PIN preplačana, je prikazano pogovorno okno »EULA«.  Kot del naše funkcije modernizacije AFO smo osvežili dve pogovorni okni, da bi posredovali več informacij o Officeovem izdelku, ki je na voljo v računalniku.  Ta telemetrijo je namenjena sledenju, če naša funkcija uspešno zmanjša število uporabnikov, pri čemer prevzame njihov izdelek tako, da spremlja potek in izstopne točke postopka prevzema (ki je bil opuščen).

Zbrana so naslednja polja:

- **ActionActivate** – znak, da je uporabnik kliknil gumb »Aktiviraj«.

- **ActionChangeAccount** – znak, da je uporabnik kliknil hiperpovezavo »uporabi drug račun«.

- **ActionCreateAccount** – znak, da je uporabnik kliknil gumb »Ustvari račun«.

- **ActionSignIn** – signal, ki ga je uporabnik kliknil z gumbom »vpis«.

- **CurrentView** – vrsto pogovornega okna, ki ga je uporabnik zaprl.

- **DialogEULA** – signal, da smo prikazali pogovorno okno »Sprejmi EULA«. 

- **DialogRedemption** – signal, ki smo ga pokazali v pogovornem oknu »AFO ' Redemption«.

- **DialogSignIn** – signal, da smo prikazali pogovorno okno za vpis v AFO '.

- **EmptyRedemptionDefaults** – sporočilo, da ni bilo mogoče pridobivati privzetih informacij o prevzemu.
 
- **GetRedemptionInfo** – znak, da pridobivamo demografske informacije za prevzem PIN.

- **MalformedCountryCode** – znak, da je koda države, ki jo potrebujete za prevzem PIN-a, popačena.

- **OExDetails** – podrobnosti o napaki, ki se prikaže, ko je bil v pogovornem oknu »vpis identitete« opuščen.

- **OExType** – podrobnosti o napaki, ki se prikaže, ko je bil v pogovornem oknu »vpis identitete« opuščen.

- **Tag** – pove nam, s katerim korakom uporabnik zapusti proces prevzema AFO '. Možna oznaka:
    - 0x0311380b – uporabnik je opustil pogovornega okno »prevzem identitete« iz pogovornega okna »redemption«
    - 0x0311380c – ni uspel samodejnega nalaganja identitete po vpisu uporabnika iz pogovornega okna »redemption«
    - 0x03113810 – ni uspel naložiti demografskih informacij kupca (koda države, jezik, valuta, ponudba za preskusno različico in nastavitve marketinga)
    - 0x03113805 – uporabnik je opustil pogovornega okno »prevzem identitete« iz pogovornega okna »redemption«
    - 0x03113806 ni uspel samodejnega nalaganja identitete po vpisu uporabnika iz pogovornega okna »vpis«
    - 0x03113807 ni uspel samodejno naložiti identitete
    - 0x03113811 uporabnik  je zaprl pogovorno okno za vpis/prevzem
    - 0x03113812 uporabnik je zaprl pogovorno okno Sprejmi EULA
    - 0x03113808 uporabnik je sprejel EULA
    - Uporabnik 0x03113811 je zaprl pogovorno okno
    - Uporabnik 0x2370e3a0 je zaprl pogovorno okno
    - 0x2370e3c1 obiščite spletno mesto za prevzem PIN-a
    - 0x2370e3a1 obiščite spletno mesto za prevzem PIN-a
    - Pogovorno okno »0x2370e3c0 zaporedje«, ki ga je povzročil uporabnik, ki je bil na tekočem v pogovornem oknu
    - Uporabnik 0x2370e3a3 je kliknil hiperpovezavo »not Now«, ki preskoči ponudbo za AFO ' za to sejo.
    - Uporabnik 0x2370e3a2 je kliknil »nikoli mi ne kaži več« hiperpovezave, ki onemogoči ponudbo za AFO '


- **UseInAppRedemption** – nam pove, ali imamo uporabniki v aplikaciji za prevzem ali pa jih pošljejo v splet, da bodo lahko izkoristili pogosto kodo PIN (vnaprej izpolnjene).

- **UseModernAFO** – nam pove, ali uporabljate novo ali staro AFO
 izkušnjo.

### <a name="officelicensingtelemetryflowshowtrybuydialogforoobe"></a>Office.Licensing.TelemetryFlow.ShowTryBuyDialogForOOBE

Ko imajo novi računalniki vnaprej nameščeno različico sistema Office in uporabnik nima upravičene osebe, se prikaže pogovorno okno, v katerem je uporabniku na voljo možnost, da preizkusite, kupite ali vnesete ključ izdelka, tako da lahko uporabnik pridobi licenco in ta dogodek sledi, če je prikazano pogovorno okno. Ta dogodek vam bo pomagal pri zavedanju, ali je bil pogovor v pogovornem oknu uporabniku prikazan, če želite preskusiti, kupiti ali vnesti ključ izdelka, zato nam bo pomagal ugotoviti, ali je uporabnik imel možnost pridobiti licenco.

Zbrana so naslednja polja: 

- **ActiveView** – pove ID pogovornega okna, ki je prikazan uporabniku

- **CurrentOOBEMode** – pove način prednamestitve (način OOBE, kot je AFO ', OEM itd.)

- **NotInitializedBeforeWhileAdding** – to je zgolj informativno in pove, ali je bil dogodek dodan v preslikavo upravitelja telemetrijo, ne da bi ga izrecno registrirali

- **SentOnDestruction** – to je zgolj informativno in pove, ali je bil dogodek dodan v preslikavo upravitelja telemetrijo in ni bil poslan izrecno.

- **ShowTryButton** – pove, ali je uporabnik v pogovornem oknu prikazal gumb »poskusi« ali ne

- **Oznaka** – uporablja se za štetje, kjer je bil dogodek poslan iz programa

### <a name="officelicensingtelemetryflowtrialflow"></a>Office.Licensing.TelemetryFlow.TrialFlow

Če uporabnik, ki je bil vnaprej nameščen v računalniku, ne dobi licence, poskuša dobiti preskusno različico, se ta dogodek sproži.  Uporablja se, da si ogledate, s katero potjo bo uporabnik dobil preskusno različico, in če bo prišlo do kakršnih koli napak pri pridobivanju preskusne različice z nakupi v aplikaciji.  Odvisno od dejanja uporabnika in rezultata nakupa aplikacije v storitvi, lahko uporabnik na koncu ne bo licenciral.

Zbrana so sledeča polja:

- **HasConnectivity** – pove, ali ima uporabnik internetno povezljivost, v primeru, da uporabnik morda ne bo rabil licence milosti za pet dni ali pa je morda v načinu zmanjšane funkcionalnosti.

- **InAppTrialPurchase** – pove, ali je polet omogočen za začetek nakupa SDK nakup v trgovini za zajem PI in nakup preskusne različice znotraj programa *[to polje je bilo odstranjeno iz tekočih različic Officea, vendar se lahko še vedno prikaže v starejših različicah.]*

- **IsRS1OrGreater** – pove, ali je različica OS večja od RS1 ali ne, saj bi moral biti nakup v trgovini SDK že uporabljen samo, če je različica OS večja, kot je RS1

- **NotInitializedBeforeWhileAdding** – to je zgolj informativno in pove, ali je bil dogodek dodan v preslikavo upravitelja telemetrijo, ne da bi ga izrecno registrirali

- **OEMSendToWebForTrial** – pove, ali je polet omogočen za pošiljanje uporabnikov v splet, da izkoristi preskusno različico

- **StoreErrorConditions** – pove različne pogoje, v skladu s katerimi je bil nakup SDK shrambe ni uspel *[To polje je bilo odstranjeno iz tekočih različic Officea, vendar se lahko še vedno prikaže v starejših različicah.]*

- **StoreErrorHResult** – pove, da je koda napake vrnjena iz trgovine SDK nakup v trgovini *[to polje je bilo odstranjeno iz tekočih različic Officea, vendar se lahko še vedno prikaže v starejših različicah.]*

- **StorePurchaseStatusResult** – pove, da je rezultat klica SDK za nakup v trgovini in če je uporabnik ustvaril nakup ali ne, s katerim lahko ugotovite, ali mora uporabnik dobiti licenco za uporabo sistema Office *[to polje je bilo odstranjeno iz tekočih različic Officea, vendar se lahko še vedno pojavi v starejših različicah.]*

- **Oznaka** – uporablja se za štetje, kjer je bil dogodek poslan iz programa

- **UserSignedInExplicitly** – pove, ali je uporabnik v tem primeru izrecno vpisan v splet – če je bil uporabljen za preskusno različico *[to polje je bilo odstranjeno iz tekočih različic Officea, vendar je morda še vedno prikazan v starejših različicah.]*

### <a name="officelicensingusegracekey"></a>Office.Licensing.UseGraceKey

Če iz neznanega razloga nismo uspeli licencirati uporabnika, namestimo ključ za dovoljeno obdobje in pošljemo ta signal. Dogodek je pomemben pri zaznavanju, ali je uporabnik v dobrem stanju in nima omogočene vse funkcionalnosti; uporabljajo se za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Zbrana so sledeča polja:

  - **OpportunisticTokenRenewalAttempted** – označuje, ali smo priložnostno poskušali obnoviti licenco za uporabnika v način za aktivacijo računalnika v skupni rabi

  - **ReArmResult** – označuje rezultat vrnitve v obdobje pred aktiviranjem nameščenega ključa, s katerem je mogoče razširiti trenutno licenco

### <a name="onenoteenrollmentresult"></a>OneNote.EnrollmentResult
 
Ta dogodek zabeleži stanje ob vpisu InTune.  Ta primer je specifičen za InTune omogočeni računi.
 
Zbrana so sledeča polja:
 
- **EnrollmentResult** – rezultat vpisa InTune

## <a name="microsoft-autoupdate-mau-events"></a>Dogodki Microsoft AutoUpdate (MAU)

### <a name="additionalappinfo_invalidpreference"></a>additionalappinfo_invalidpreference

Ta dogodek sporoča, da so izbrane napačne nastavitve za prikaz več informacij glede konca storitve za izdelek. Na osnovi teh informacij svetujemo strankam, da izberejo pravilne nastavitve za prikaz dodatnih informacij.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Kanal** – nastavitev za občinstvo

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **Razlog** – podatki o neveljavnem vnosu v nastavitvah

- **SessionId** – identifikator za sejo

### <a name="appdelegate_launch"></a>appdelegate_launch

Ta dogodek pomeni, da je prišlo do poskusa zagona aplikacije. Zabeležimo njegov rezultat (neuspeh ali uspeh). S tem dogodkom ugotovimo primere, v katerih MAU ne bo začela

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek
    
- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – nabor statičnega besedila, ki označuje stanje izstrelitve.

- **PipelineInfo_ClientCountry** – država naprava (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="appdelegate_terminate"></a>appdelegate_terminate

Ta dogodek pomeni, da je prišlo do uporabe ljubkega izhoda. Ta dogodek uporabljamo, da razločimo ljubke izhodne aplikacije iz neusmiljenih.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva
    
- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave
    
- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – statično besedilo, v katerem je navedeno, da je Microsoft autoupdate prekinjen.

- **PipelineInfo_ClientCountry** – država naprava (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="appinstall_connecttoxpc"></a>appinstall_connecttoxpc

Ta dogodek pomeni, da je prišlo do napake pri vzpostavljanju povezave s pomočnikom MAU (komponenta, ki izvede namestitev programa).  V tem primeru se prikaže možna korupcija aplikacije MAU. Naprava ne bo mogla namestiti posodobitev.

Zbrana so sledeča polja:    

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje informacije o napakah pri težavi s povezavo.

- **PipelineInfo_ClientCountry** – država naprava (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="appinstall_logscanned"></a>appinstall_logscanned

Ta dogodek se uporablja za ugotavljanje, ali je bila dnevniška datoteka uspešno obdelana. Ta dogodek uporabljamo za zaznavanje in obdelavo morebitnih težav med namestitvijo aplikacije. 
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost za občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – nastavitev za preverjanje posodobitev

- **Payload** – poroča o napakah, odkritih med namestitvijo aplikacije in/ali pregledom stanja dokončanja 

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **SessionId** – identifikator za sejo

### <a name="appregistry_config"></a>appregistry_config

Ta dogodek poroča o morebitnih napakah med nalaganjem informacij o registraciji aplikacije. Na osnovi tega poročila svetujemo skrbnikom za IT glede pravilne oblike zapisa za nastavitev registracij odjemalske aplikacije.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost za občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – vsebuje informacije o naravi napake, do katere je prišlo pri registraciji aplikacije.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **SessionId** – identifikator za sejo

### <a name="appregistry_info"></a>appregistry_info

V tem primeru se prikaže sporočilo, da se je program zagnal. Ta dogodek uporabljamo za seznam programov, za katere lahko MAU nadzoruje posodobitve, število kopij, ki so na voljo, ter njihovo različico in lokacijo namestitve (privzeto ali drugo).

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje informacije na seznamu identifikatorjev programa, ki se uporablja za registracijo z Microsoftovimi storitvami za samodejno posodabljanje in številom namestitve, ki so registrirane za aplikacijo.

- **PipelineInfo_ClientCountry** – država naprava (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="appregistry_remove"></a>appregistry_remove

Ta dogodek pomeni, da je prišlo do poskusa odstranitve aplikacije s seznama programov, ki jih upravlja MAU. Ta dogodek uporabljamo, da bi preverili, ali so le MAU – izdane aplikacije upravljane prek MAU (ne bi smelo biti tukaj prikazane aplikacije AppStore).

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – ime in identifikator aplikacije, ki jo odstranite, ne glede na to, ali aplikacija še vedno obstaja na registriranem mestu in ali je bil program nameščen iz storitve AppStore.

- **PipelineInfo_ClientCountry** – država naprava (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="catalog_errorsignature"></a>catalog_errorsignature

Ta dogodek pomeni, da je prišlo do napake pri izvajanju preverjanja veljavnosti kode v datoteki s posodobitvijo zavarovanja.  Vsa zavarovanja, ki niso bile podpisane z vpisom kode, je treba upoštevati kot neveljavna.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ime datoteke s katalogom z neveljavnim podpisom. V različnih statičnih besedilih so opisani različni pogoji napake.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="cloningtask_begin"></a>cloningtask_begin

Ta dogodek označuje začetek opravila kloniranja pred posodobitvijo aplikacije. Ta dogodek uporabljamo v povezavi z dogodkom cloningtask_status, da ugotovimo število napak pri kloniranju, da bi ugotovili, ali je treba funkcijo kloniranja zadušiti v drugih kanalih za občinstvo.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator aplikacije.

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost za občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **SessionId** – identifikator za sejo

- **UpdateID** – identifikator za posodobitev.


### <a name="cloningtask_helpertoolconnection"></a>cloningtask_helpertoolconnection

Ta dogodek zabeleži težave z namestitvijo klona (tj. ne bomo se povezali z pomočnikom, da bi uporabili posodobitev, ali pa vzpostavili povezavo, vendar pomočnik ne more uporabiti posodobitve). Če smo zabeležili kartoteko, to pomeni, da ni bilo mogoče namestiti klona in se bo zdaj treba odkupiti posodobitvi na mestu uporabe.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ID za prepoznavanje dejavnosti z eno posodobitvijo in napake strežnika proxy, ki so bile sporočene med postopkom kloniranja.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="cloningtask_status"></a>cloningtask_status

Ta dogodek označuje stanje postopka kloniranja za aplikacijo, ki bo posodobljena. Ta dogodek uporabljamo za določitev stopnje uspešnosti in tudi za vrste napak, zaradi katerih pride do okvar. Ta dogodek se uporablja za ugotavljanje, ali bi morali funkcijo za kloniranje zadušiti v drugih kanalih za občinstvo.

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator aplikacije.

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Error** – niz vsebuje informacije o napaki med opravilom kloniranja.

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **Success** – znakovna predstavitev spremenljivke tipa Boolean.

- **UpdateID** – identifikator za posodobitev.

### <a name="cloningtask_status_finish"></a>cloningtask_status_finish

Ta dogodek poroča o dokončanju opravila »kloniranje«. Ta dogodek je del poročila o posodobitvenem lijaku in se uporablja za določitev stanja posodobitev aplikacije.
 
Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator aplikacije

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **UpdateID** – identifikator posodobitve.


### <a name="configuration_channel"></a>configuration_channel

Ti zapisi dogodkov poskušajo zamenjati kanale (skupina občinstva) v MAU.  To uporabljamo za beleženje poskusov in rezultatov (uspeh ali neuspeh).

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje izbrano ime kanala.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="configuration_metadata"></a>configuration_metadata

Ta dogodek se zabeleži vsakič, ko se MAU inicializira. To je MAU bitje srca vrsta dogodka

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – statično besedilo, ki označuje posamezne metapodatke, je inicializirano ali pa je konfiguracija inicializirana.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo.

### <a name="configuration_systemversion"></a>configuration_systemVersion

Ta dogodek označuje, da poskus pridobivanja različice sistema ni bil uspešen. Vsbuje tudi informacije o informacijah, ki ji je od sistema uspel zbrati Microsoft Auto Update (MAU). Ta dogodek uporabljamo za ugotavljanje, ali bi moral MAU poskrbeti za napake. Ne spreglejte, da se različica sistema uporablja za ugotavljanje, ali je mogoče posodobitev uporabiti za odjemalsko napravo.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – vsebuje informacije o napaki, do katere je prišlo med pridobivanjem niza z različico sistema macOS.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="controller_alertmanager_reinstallresponse"></a>controller_alertmanager_reinstallresponse

Ta dogodek pomeni, da je MAU padel v neuporabljivo/nepopravljivo stanje in ga je treba znova namestiti. V tem primeru je zahtevano sporočilo o nepopravljivi napaki in posredovanju uporabnika.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje enumeriran izbor uporabnika.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="controller_alertmanager_tmpdiskfull"></a>controller_alertmanager_tmpdiskfull

Ta dogodek pomeni, da je bila zaznana pomanjkljiva disketa. Posodobitev ne bo mogoče namestiti zaradi nezadostnega prostora na disku.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – statično besedilo. 

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="controller_alertmanager_tmpdiskfullretry"></a>controller_alertmanager_tmpdiskfullretry

Ta dogodek pomeni, da je bil poskus vnovične namestitve posodobitve zagnan, ko je bil zaznan zadosten prostor na disku. Če ne morete namestiti posodobitev zaradi pomanjkljivega prostora na disku, znova ponovimo namestitev.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – statično besedilo. 

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo
    

### <a name="controller_alertmanager_tmpdiskfullretrycancel"></a>controller_alertmanager_tmpdiskfullretrycancel

Ta dogodek pomeni, da je bila zaznana funkcija preklica za vnovični poskus vnovičnega poizkusa. Ta dogodek uporabljamo, če želite ugotoviti, ali je bil nadomestni mehanizem dovolj za usmerjanje uporabnika skozi postopek posodabljanja, ko je bil zaznan zadosten disk.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)
    
- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev
    
- **Payload** – statično besedilo. 

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="controller_checkwindow_noupdatefoundok"></a>controller_checkwindow_noupdatefoundok

V tem primeru se prikaže potrditveno polje preveri, ali so na voljo posodobitve, ki so bile najdene brez posodobitev, ki jih uporabljamo, če želite zagotoviti, da so posodobitve ponudene pravilno, optimiziranje bremen storitve in določanje, kako pogosti so naši posodobitvi za preverjanje. Optimizirali bomo tudi našo izdajo, ki temelji na pričakovanju uporabnikovih posodobitev.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – statično besedilo. 

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    

### <a name="controller_checkwindow_updatecheck"></a>controller_checkwindow_updatecheck

Ta dogodek pomeni, da je bila izvedena preverjanje posodobitev. Ta dogodek uporabljamo, če želite zagotoviti, da so posodobitve na voljo pravilno, optimizacija storitvenih bremen in določanje, kako pogosta je preverjanje naših posodobitev. Optimizirali bomo tudi našo izdajo, ki temelji na pričakovanju uporabnikovih posodobitev.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave
    
- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – statično besedilo. 

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="controller_checkwindow_updatecheckcancel"></a>controller_checkwindow_updatecheckcancel

Ta dogodek pomeni, da je bil postopek preverjanja posodobitev preklican (preklical ga je uporabnik ali sistem). Ta dogodek uporabljamo, če želite zagotoviti, da so posodobitve na voljo pravilno, optimizacija storitvenih bremen in določanje, kako pogosta je preverjanje naših posodobitev. Optimizirali bomo tudi našo izdajo, ki temelji na pričakovanju uporabnikovih posodobitev.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – statično besedilo. 

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="controller_checkwindow_updatecheckcanceluser"></a>controller_checkwindow_updatecheckcanceluser

Ta dogodek pomeni, da je uporabnik preklical postopek preverjanja za posodobitve.  Ta dogodek uporabljamo, če želite zagotoviti, da so posodobitve na voljo pravilno, optimizacija storitvenih bremen in določanje, kako pogosta je preverjanje naših posodobitev. Optimizirali bomo tudi našo izdajo, ki temelji na pričakovanju uporabnikovih posodobitev.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije
    
- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – statično besedilo. 

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="controller_checkwindow_updatesfound"></a>controller_checkwindow_updatesfound

Ta dogodek pomeni, da je uporabnik preklical postopek preverjanja za posodobitve.  Ta dogodek uporabljamo, če želite zagotoviti, da so posodobitve na voljo pravilno.

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – statično besedilo. 

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="controller_checkwindow_uptodate"></a>controller_checkwindow_uptodate

Ta dogodek pomeni, da postopek preverjanja posodobitev ni bil ustvarjen, ker so programi v napravi posodobljeni.  Ta dogodek uporabljamo, če želite zagotoviti, da so posodobitve na voljo pravilno.

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – statično besedilo. 

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="controller_downloadwindow_applaunchwithpendingupdate"></a>controller_downloadwindow_applaunchwithpendingupdate

Ta dogodek pomeni, da se je zagnala aplikacija, ki je v postopku pridobivanja posodobitev. Ta dogodek uporabljamo, če želite zagotoviti, da so posodobitve na voljo pravilno. Če želite odpreti programe, ne morete začeti posodabljati. Programe je treba zapreti pred posodobitvijo.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – statično besedilo. 

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP
    
- **ID** seje – identifikator za sejo

    
### <a name="controller_downloadwindow_closeapplicationdialog"></a>controller_downloadwindow_closeapplicationdialog

Ta dogodek pomeni, da se je zagnala aplikacija, ki je v postopku pridobivanja posodobitev. Ta dogodek uporabljamo, če želite zagotoviti, da so posodobitve na voljo pravilno. Če želite odpreti programe, ne morete začeti posodabljati. Programe je treba zapreti pred posodobitvijo.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – statično besedilo. 

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="controller_downloadwindow_curtasknull"></a>controller_downloadwindow_curtasknull

Ta dogodek pomeni, da je prišlo do nepričakovane napake med poskusom uporabe posodobitve. Ta dogodek uporabljamo, če želite zagotoviti, da so posodobitve na voljo pravilno.

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – statično besedilo. 

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="controller_downloadwindow_downloadcancel"></a>controller_downloadwindow_downloadcancel

Ta dogodek pomeni, da je uporabnik preklical postopek prenosa.  Ta dogodek uporabljamo, če želite zagotoviti, da so posodobitve na voljo pravilno.

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – statično besedilo. 

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="controller_downloadwindow_downloadfailed"></a>controller_downloadwindow_downloadfailed

Ta dogodek pomeni, da je prišlo do napake pri prenosu posodobitve. Ta dogodek uporabljamo, če želite zagotoviti, da so posodobitve na voljo in pravilno prenesene.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="controller_downloadwindow_downloadfailedok"></a>controller_downloadwindow_downloadfailedok

Ta dogodek pomeni, da je prišlo do napake pri prenosu posodobitve, uporabnik pa je bil obveščen. Ta dogodek uporabljamo, če želite zagotoviti, da so posodobitve na voljo in da so prenesene pravilno ter da je v primeru napake sporočilo vročeno uporabniku.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="controller_downloadwindow_downloadpathmissing"></a>controller_downloadwindow_downloadpathmissing

Ta dogodek pomeni, da je prišlo do napake pri prenosu posodobitve. Ta dogodek uporabljamo, če želite zagotoviti, da so posodobitve na voljo in pravilno prenesene. Ta dogodek pomeni, da manjka URL za prenos.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="controller_downloadwindow_downloadtasknull"></a>controller_downloadwindow_downloadtasknull

Ta dogodek pomeni, da je prišlo do napake pri prenosu posodobitve. Ta dogodek uporabljamo, če želite zagotoviti, da so posodobitve na voljo in pravilno prenesene. V tem primeru je navedeno, da je bila Microsoft autoupdate pozvana, da začasno ustavi ali nadaljuje prenos, vendar ne najde ustreznega upravitelja prenosov.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="controller_downloadwindow_filesignaturenotverified"></a>controller_downloadwindow_filesignaturenotverified

Ta dogodek pomeni, da je prišlo do napake pri prenosu posodobitve. V tem dogodku je navedeno, da družba Microsoft autoupdate ni mogla preveriti, ali je Microsoft storitev objavila to posodobitev. Ta dogodek uporabljamo, če želite zagotoviti, da so posodobitve na voljo in pravilno prenesene. 

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki vsebuje URL za prenos. To je Microsoftova lokacija za prenos, razen če je kanal nastavljen na »po meri«. Za kanal po meri je ta vrednost nastavljena na »lokacija po meri«.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="controller_downloadwindow_installcomplete"></a>controller_downloadwindow_installcomplete

Ta dogodek pomeni, da je bila namestitev vseh posodobitev, ki jih ponuja Microsoft autoupdate, dokončana. Ta dogodek uporabljamo, če želite zagotoviti, da so posodobitve na voljo in pravilno prenesene. 

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.
    
- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="controller_downloadwindow_networkunavailablealert"></a>controller_downloadwindow_networkunavailablealert

Ta dogodek pomeni, da je bila povezljivost z omrežjem izgubljena med prenosom posodobitev.  Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.

Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="controller_downloadwindow_networkunavailablealertok"></a>controller_downloadwindow_networkunavailablealertok

Ta dogodek pomeni, da je bila povezljivost z omrežjem izgubljena med prenosom posodobitev. Prav tako lahko opazite, da je bil uporabnik obveščen o tej napaki. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.

Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="controller_downloadwindow_noconnectionok"></a>controller_downloadwindow_noconnectionok

Ta dogodek pomeni, da je bila povezljivost z omrežjem izgubljena med prenosom posodobitev. Prav tako lahko opazite, da je bil uporabnik obveščen o tej napaki. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.

Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="controller_downloadwindow_repairrequired"></a>controller_downloadwindow_repairrequired

V tem primeru se prikaže sporočilo, da postopek posodabljanja ni uspel. Prav tako je določeno, da je bila posodobitev dokončana, vendar je Microsoft autoupdate našel težavo s posodobljeno aplikacijo in popravilom. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.

Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)
    
- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.
    
- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="controller_downloadwindow_updateaborted"></a>controller_downloadwindow_updateaborted

V tem primeru se prikaže sporočilo, da postopek posodabljanja ni uspel. Prav tako je prikazano, da je posodobitev že napredovala daemon in uporabnik je kliknil »v redu«, da prekinete prenos. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.

Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="controller_downloadwindow_updatefailed"></a>controller_downloadwindow_updatefailed

Ta dogodek pomeni, da je spodletela ena ali več posodobitev trenutnega paketa. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.

Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.
    
- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="controller_downloadwindow_updatesuccessful"></a>controller_downloadwindow_updatesuccessful

Ta dogodek pomeni, da so bile vse posodobitve iz trenutnega paketa uspešne. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.

Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="controller_downloadwindow_userpaused"></a>controller_downloadwindow_userpaused

Ta dogodek pomeni, da so bile vse posodobitve iz trenutnega paketa uspešne. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.

Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="controller_downloadwindow_userresumed"></a>controller_downloadwindow_userresumed

Ta dogodek pomeni, da je bil postopek prenosa posodobitev uspešno vzpostavljen, ko je bil zaustavljen. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.

Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek
    
- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="controller_mainwindow_setautomaticdownloadinstall"></a>controller_mainwindow_setautomaticdownloadinstall

Ta dogodek pomeni, da je bila naprava včlanjena v način samodejnega posodabljanja. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.

Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="controller_mainwindow_setmanualchecking"></a>controller_mainwindow_setmanualchecking

Ta dogodek pomeni, da je bila naprava včlanjena v način ročne posodobitve. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.

Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="controller_templateawindow_cancel"></a>controller_templateawindow_cancel

Ta dogodek pomeni, da se je uporabnik odločil, da prekliče ali prezre določeno opozorilno sporočilo. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.

Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="controller_templateawindow_enroll"></a>controller_templateawindow_enroll

Ta dogodek pomeni, da se je uporabnik odločil upoštevati določeno priporočilo za opozorilo. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.

Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev
    
- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo



### <a name="controller_templateawindow_install"></a>controller_templateawindow_install

Ta dogodek pomeni, da se je uporabnik odločil upoštevati določeno priporočilo, ki je povezano z uvedbo dejanja namestitve programske opreme. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.

Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="controller_updatewindow_begindownloadingapps"></a>controller_updatewindow_begindownloadingapps

Ta dogodek pomeni, da se je zagnala možnost» prenos za posodobitve v oknu posodabljanje. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.

Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje slovar razpoložljivih paketov posodobitev in navedbo, ali je uporabnik izbral namestitev tega vnosa.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="controller_updatewindow_networkretry"></a>controller_updatewindow_networkretry

Ta dogodek pomeni, da je bil vnovičen poskus sprožen na listu posodobitev zaradi napake v omrežju. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.

Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="controller_updatewindow_networkretrycancel"></a>controller_updatewindow_networkretrycancel

Ta dogodek pomeni, da poskusa ni bilo mogoče sprožiti na listu posodobitev zaradi napake omrežja. V tem dogodku je navedeno, da je uporabnik izvoljen za preklic posodobitev, potem ko je opozorilo, da omrežje ne bo na voljo. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="controller_updatewindow_networkunavailable"></a>controller_updatewindow_networkunavailable

Ta dogodek pomeni, da je bila povezljivost z omrežjem nenadoma izgubljena. Ta dogodek pomeni, da Server ni dosegljiv, ko poskuša prenesti paket posodobitev. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="controller_updatewindow_noupdateavailable"></a>controller_updatewindow_noupdateavailable

Ta dogodek pomeni, da je prišlo do iskanja po posodobitvah, ki so privedle do posodobitev, ki niso na voljo. Ta dogodek pomeni, da Microsoft autoupdate ne najde razpoložljivih posodobitev. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="controller_updatewindow_noupdatestoselect"></a>controller_updatewindow_noupdatestoselect

V tem primeru se prikaže sporočilo o napaki, ki je povzročilo prazen seznam posodobitev. V tem primeru je navedeno, da Microsoft autoupdate prikazuje prazen list z posodobitvami. To se ne bi smelo zgoditi. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="controller_updatewindow_updateavailable"></a>Controller_UpdateWindow_UpdateAvailable

Ta dogodek pomeni, da je prišlo do iskanja po posodobitvah, ki so privedle do posodobitev, ki so bile na voljo. To uporabljamo celo za določanje, ali so na voljo posodobitve, ki si jih lahko uporabnik ogleda, ne glede na to, ali so prikazane pravilne posodobitve ali ali je blokiranje posodobitev delovalo po pričakovanjih. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in za pomoč pri odpravljanju napak.
 
Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje slovar razpoložljivih paketov posodobitev in stanje izbora za vsakega uporabnika.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="controller_updatewindow_updateavailablecancel"></a>controller_updatewindow_updateavailablecancel

Ta dogodek pomeni, da je uporabnik preklical, ko smo prikazali posodobitve na seznamu posodobitev lista. To uporabljamo celo zato, da razložimo razloge za to, da ne moremo posodobiti (tj. uporabnik bo preklical). Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="downloadactor_pause"></a>downloadactor_pause

Ta dogodek pomeni, da je uporabnik izdal zahtevo za začasno ustavitev prenosa. To uporabljamo tudi zato, da bi razložili razloge za to, da posodobitve ne bodo dokončane. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="downloadactor_redirect"></a>downloadactor_redirect

V tem dogodku je navedeno, da je agent za prenose opozoril na končno točko, ki bo preusmerila naslov URL-ja za zahtevo prenosa. To funkcijo uporabljamo tudi zato, da razložimo razloge za napake pri prenosu in diagnosticiranje težav z zastopstvom. Prav tako lahko pomaga pri diagnosticiranju razlogov, zakaj so uporabniki opazili, da bodo namestili starejše gradnje. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje preusmerjen URL. To je Microsoftova lokacija za prenos, razen če je kanal nastavljen na »po meri«. Za kanal po meri je ta vrednost nastavljena na »lokacija po meri«.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="downloadactor_resume"></a>downloadactor_resume

Ta dogodek pomeni, da uporabnik izda zahtevo za nadaljevanje začasnega prenosa. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="downloadactor_resumeerror"></a>downloadactor_resumeerror

Ta dogodek pomeni, da uporabnik izda zahtevo za nadaljevanje začasnega prenosa. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki vsebuje URL za prenos. To je Microsoftova lokacija za prenos, razen če je kanal nastavljen na »po meri«. Za kanal po meri je ta vrednost nastavljena na »lokacija po meri«.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="downloadactor_status"></a>downloadactor_status

Ta dnevnik dogodkov, ki jih poskuša pridobiti datoteke zavarovanja, in njihov rezultat (uspeh ali neuspeh). Zanima nas, ali so zavarovane osebe in paketi, ki jih pridobivate. Napačno datoteko, ki jo pridobivate, lahko pomeni težavo z ustvarjanjem/zavarovanjem. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje URL za prenos in kodo napake v primeru napake. To je Microsoftova lokacija za prenos, razen če je kanal nastavljen na »po meri«. Za kanal po meri je ta vrednost nastavljena na »lokacija po meri«.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="downloadmanifest_configuration"></a>downloadmanifest_configuration

Ta dogodek vključuje sporočilo o napaki v zvezi s konfiguracijo storitve Microsoft Auto Update (MAU) – bodisi z izbiro strežnika po meri v nastavitvah bodisi z definicijami končnih točk v pomočniku za posodobitve v nameščenih komponentah storitve MAU. Ta dogodek uporabljamo za svetovanje skrbnikom za IT pri nastavljanju pravilnih končnih točk strežnika z manifestom.
 
Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **Payload** – označi, ali je napaka povezana z namestitvijo strežnika po meri ali z nameščenimi komponentami MAU-ja

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="downloadmanifest_downloadcatalogfail"></a>downloadmanifest_downloadcatalogfail

Ta dogodek je prišlo do napake pri prenosu. Datoteka, ki je ni prenesla, je zabeležena. Zanima nas, ali so zavarovane osebe in paketi, ki jih pridobivate. Če ne želite prenesti manifesta, lahko pokažete na to, da je prišlo do napake pri ustvarjanju nezmožnosti ustvarjanja zavarovanj, napake konfiguracije CDN, napaka konfiguracije odjemalca, omrežna napaka. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje kodo napake prenosa in URL datoteke za prenos. To je Microsoftova lokacija za prenos, razen če je kanal nastavljen na »po meri«. Za kanal po meri je ta vrednost nastavljena na »lokacija po meri«.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="downloadmanifest_downloadcatalogsuccess"></a>downloadmanifest_downloadcatalogsuccess

V tem primeru se prikaže sporočilo, da je bila datoteka uspešno prenesena. Če ne želite prenesti manifesta, lahko pokažete na to, da je prišlo do napake pri ustvarjanju nezmožnosti ustvarjanja zavarovanj, napake konfiguracije CDN, napaka konfiguracije odjemalca, omrežna napaka. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek
    
- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje kodo napake prenosa in URL datoteke za prenos. To je Microsoftova lokacija za prenos, razen če je kanal nastavljen na »po meri«. Za kanal po meri je ta vrednost nastavljena na »lokacija po meri«.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="downloadmanifest_downloadfail"></a>downloadmanifest_downloadfail

Ta dogodek pomeni, da je prišlo do napake pri prenosu. Datoteka manifesta ali paketa, ki ni uspela prenesti, in podrobnosti o napakah, so zabeležene. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje kodo napake prenosa in URL datoteke za prenos. To je Microsoftova lokacija za prenos, razen če je kanal nastavljen na »po meri«. Za kanal po meri je ta vrednost nastavljena na »lokacija po meri«.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="downloadmanifest_downloadfromurl"></a>downloadmanifest_downloadfromurl

Ta dogodek pomeni, da se je zagnal prenos datoteke kataloga. Zabeležimo URL, iz katerega je prenesena datoteka kataloga. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje kodo napake prenosa in URL datoteke za prenos. To je Microsoftova lokacija za prenos, razen če je kanal nastavljen na »po meri«. Za kanal po meri je ta vrednost nastavljena na »lokacija po meri«.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="downloadmanifest_downloading"></a>downloadmanifest_downloading

Ta dogodek pomeni, da se je zagnal prenos datoteke kataloga. Zabeležimo URL, iz katerega je prenesena datoteka kataloga. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje kodo napake prenosa in URL datoteke za prenos. To je Microsoftova lokacija za prenos, razen če je kanal nastavljen na »po meri«. Za kanal po meri je ta vrednost nastavljena na »lokacija po meri«.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="downloadmanifest_downloadsuccess"></a>downloadmanifest_downloadsuccess

V tem primeru se prikaže sporočilo, da je prišlo do nanašanja datoteke XML in paketa. Zabeležimo URL, iz katerega je prenesena datoteka kataloga. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje kodo napake prenosa in URL datoteke za prenos. To je Microsoftova lokacija za prenos, razen če je kanal nastavljen na »po meri«. Za kanal po meri je ta vrednost nastavljena na »lokacija po meri«.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="downloadmanifest_downloadurl"></a>downloadmanifest_downloadurl

V tem primeru se prikaže sporočilo, da je prišlo do zahteve za prenos datoteke. Zabeležimo URL, iz katerega je prenesena datoteka kataloga. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek
    
- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje kodo napake prenosa in URL datoteke za prenos. To je Microsoftova lokacija za prenos, razen če je kanal nastavljen na »po meri«. Za kanal po meri je ta vrednost nastavljena na »lokacija po meri«.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="downloadmanifest_filenameerror"></a>downloadmanifest_filenameerror

Ta dogodek pomeni, da je prišlo do nepričakovane napake. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **SessionId** – identifikator seje.


### <a name="downloadmanifest_invalidhash"></a>downloadmanifest_invalidhash

V tem primeru je spodletela varnostna veljavnost naših datotek. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ime prenesene datoteke z neveljavno razpršilno vrednostjo.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="downloadmanifest_missingdaemon"></a>downloadmanifest_missingdaemon

Ta dogodek pomeni, da je uporabnik poskusil preveriti, ali so na voljo posodobitve, in odkrili smo, da MAU manjka osrednje komponente (Daemon). Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="downloadmanifest_signatureerror"></a>downloadmanifest_signatureerror

Ta dogodek pomeni, da preverjanje podpisa kode ni uspelo za paket. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ime prenesene datoteke z neveljavno razpršilno vrednostjo.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="downloadmanifest_status"></a>downloadmanifest_status

Ta dogodek zabeleži povzeto seštevanje poskusov/napak, ki so jih prizadele med postopkom prenosa za datoteke manifesta in paketa. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje informacije, vključno z URL-jem (Microsoft Address), predpono datoteke, ki jo prenesete, morebitne napake, ki so bile naletele itd.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="downloadmgr_downloadend"></a>downloadmgr_downloadend

Ta dogodek zabeleži oznako, ki označuje, da je proces prenosa končan sam. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje informacije, vključno z URL-jem (Microsoft Address), predpono datoteke, ki jo prenesete, morebitne napake, ki so bile naletele itd.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="downloadmgr_downloadstart"></a>downloadmgr_downloadstart

Ta dogodek zabeleži posodobitev, ki je na voljo za prenos. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ime posodobitve, ki je bila prenesena.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="downloadtask_downloadbegin"></a>downloadtask_downloadbegin

Ta dogodek označi začetek dejavnosti prenosa za posodobitev aplikacije. Ta je del posodobitvenega lijaka in se uporablja za določitev stanja posodobitev aplikacije.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **BundleVersion** – različica aplikacije, ki se posodablja

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **PreviousUpdateID** - Identifier for an application update

- **SessionId** – identifikator za sejo

- **PreviousUpdateID** – identifikator za posodobitev aplikacije

- **UpdatePkg** – ime uporabljenega paketa posodobitve

- **UpdateVersion** – različica aplikacije po posodobitvi


### <a name="downloadtask_downloadfailure"></a>downloadtask_downloadfailure

V tem dnevniku dogodkov je prišlo do napake pri prenosu datoteke paketa. Zabeležimo pot posodobitve in napako. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator aplikacije, v katerem je prišlo do napake pri prenosu.

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Napaka** – med prenosom je bila zaznana napaka.

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ime posodobitve, ki je bila prenesena, in opazite napako. *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar se bo morda še vedo pojavljalo v starejših graditvah.]*

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **UpdateID** – identifikator posodobitve, ki jo nalagate.


### <a name="downloadtask_downloadsuccess"></a>downloadtask_downloadsuccess

Uspešen prenos datoteke paketa. Zabeležimo uporabljeno pot posodabljanja. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator programa.

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje pot posodabljanja za uspešno prenašanje.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **UpdateID** – identifikator posodobitve, ki ste jo naložili.

### <a name="downloadtask_updatertypeerror"></a>downloadtask_updatertypeerror

Ta dogodek poroča o vrsti napake programa za posodabljanje v preneseni datoteki manifesta. Ta dogodek uporabimo za obveščanje lastnika o datoteki manifesta, da je mogoče popraviti napako.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID seje** – identifikator za sejo

- **PreviousUpdateID** – identifikator za posodobitev aplikacije

- **UpdaterType** – vrsta programa za posodabljanje, ki je določen v preneseni datoteki manifesta

- **UpdateURL** – URL posodobitvenega paketa, ki ga je treba uporabiti

### <a name="downloadtask_urlerror"></a>downloadtask_urlerror

Ta dogodek poroča o napaki v URL-ju, določenem v preneseni datoteki manifesta. Ta dogodek uporabimo za obveščanje lastnika o datoteki manifesta, da je mogoče popraviti napako.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **Error** – označuje naravo napake, do katere je prišlo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID seje** – identifikator za sejo

- **PreviousUpdateID** – identifikator za posodobitev aplikacije

- **UpdateURL** – URL posodobitvenega paketa, ki ga je treba uporabiti

### <a name="fba_changelastupdate"></a>fba_changelastupdate

Ta dogodek poroča o tem, kdaj je Microsoft Auto Update (MAU) preveril, ali so na voljo posodobitve. Ta dogodek uporabimo za odpravljanje napak, ko za določeno napravo že dlje časa ni bila na voljo nobena posodobitev.

Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **Payload** – vsebuje datum in čas, ko je MAU preveril, ali so na voljo posodobitve

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fba_checkforupdate"></a>fba_checkforupdate

Ta dogodek pomeni, da se v ozadju preverjajo posodobitve. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fba_checkforupdateskip"></a>fba_checkforupdateskip

Ta dogodek pomeni, da je bil postopek za ozadje preskočen zaradi odprtja MAU. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fba_forceinstallmsgsent"></a>fba_forceinstallmsgsent

Ta dogodek označuje, da je v uporabniškem vmesniku zagnana vsiljena posodobitev na silo. Ta dogodek je del lijaka in se uporablja za določitev stanja funkcije vsiljene posodobitve.

Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="fba_forceupdatecheck"></a>fba_forceupdatecheck

Ta dogodek označuje, da je preverjanje posodobitev vsiljeno. Ta dogodek uporabimo, da ugotovimo število vsiljenih preverjanj posodobitev, ki se zgodijo zunaj običajnega cikla preverjanja posodobitev.

Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="fba_guiappopen"></a>fba_guiappopen

Ta dogodek označuje, da se uporabniški vmesnik zaganja v načinu samodejnega preverjanja, ker je trenutno odprta aplikacija, za katero se uveljavlja posodobitev. Ta dogodek se uporablja za ugotavljanje števila zagonov uporabniškega vmesnika v načinu samodejnega preverjanja za razvoj funkcij v prihodnosti.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** –  čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="fba_installpending"></a>fba_installpending

Ta dogodek označuje, da je Microsoft Auto Update (MAU) poslal obvestilo glede posodobitev, ki čakajo. Ta dogodek se uporablja za določitev števila posodobitev, ki se začnejo z uporabniškimi obvestili, in za izboljšanje uporabniške izkušnje z minimizacijo prekinitev za uporabnika v prihodnjih izdajah.

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** –  čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="fba_launch"></a>fba_launch

Ta dogodek označuje zagon programa Microsoft Update Assistant z metodo zagona. Ta dogodek se uporablja za zgotavljanje, ali se Microsoft Update Assistant zaganja v nepravilnem kontekstu.

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="fba_launchbyagent"></a>fba_launchbyagent

Ta dogodek označuje, da je Microsoft Update Assistant zagnan prek agenta za zagon. Ta dogodek se uporablja za določitev števila zagonov programa Microsoft Update Assistant v uporabniškem vmesniku za razvoj v prihodnje.

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je zgodil dogodek iz dnevnika 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID seje** – identifikator za sejo

### <a name="fba_launchfromprotocol"></a>fba_launchfromprotocol

Ta dogodek označuje, da je Microsoft Update Assistant zagnan prek protokola URL. Ta dogodek se uporablja za določitev števila zagonov programa Microsoft Update Assistant prek protokola URL za razvoj v prihodnje.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – vsebuje informacije o shemi URL in gostitelju URL

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID seje** – identifikator za sejo

### <a name="fba_launchgui"></a>fba_launchgui

Ta dogodek označuje, da Microsoft Update Assistant poskuša zagnati grafični uporabniški vmesnik (GUI). Ta dogodek se uporablja za določitev števila zagonov uporabniškega vmesnika, ki se inicira v programu Microsoft Update Assistant, tza pomoč pri razvoju v prihodnje, vključno z minimizacijo prekinitev za uporabnika zaradi pogostih zagonov uporabniškega vmesnika.

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je zgodil dogodek iz dnevnika 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fba_launchstatus"></a>fba_launchstatus

Ta dogodek se odjavi pri zagonu daemona, medtem ko poskuša zagnati. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Error** – vsebuje OSStatus (koda stanja Apple), ki odseva stanje zagona.

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje OSStatus (koda stanja Apple), ki odseva stanje izstrelitve. *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar se bo morda še vedo pojavljalo v starejših graditvah.]*

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **Success** – znakovni niz tipa Boolean, ki označuje, ali je bil uspešno izveden proces daemona MAU.


### <a name="fba_mausilentupdate"></a>fba_mausilentupdate

Ta dogodek označuje, da Microsoft Update Assistant inicira tihe zagone. Ta dogodek se uporablja za določitev števila posodobitev, ki se uporabijo brez posredovanja uporabnika, da bi pospešili izboljšave uporabniške izkušnje.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo
 
- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je zgodil dogodek iz dnevnika 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="fba_moreinfofromappnotification"></a>fba_moreinfofromappnotification

Ta dogodek sporoča informacijo, da je registrirana aplikacija usmerjena preko programa Microsoft Auto Update (MAU). Na primer, sporočila o koncu storitve so potisnjena z obvestilom programa MAU. Ta dogodek uporabimo za določitev števila naprav, kjer je prikazano to določeno obvestilo, da določite uspešnost razširjanja informacij.

Zbrana so ta polja:

- **AdditionalInfoID** – enolično prepozna potiskanje »Več informacij« skozi program MAU.

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** –  čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **NotificationEvent** – statično besedilo, ki označuje vrsto obvestila, ki se uporablja.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="fba_multipledaemon"></a>fba_multipledaemon

Ta dogodek označuje, da je zaznan drug primerek programa Microsoft Update Assistant in da bo trenutni primerek prekinjen. Ta dogodek bomo uporabili za določitev števila naprav, ki poskušajo zagnati več primerkov programa Update Assistant, in za zasnovo rešitve, če bo potrebno.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je zgodil dogodek iz dnevnika 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="fba_nofifyappclosed"></a>fba_nofifyappclosed

Ta dogodek označuje, da Microsoft Update Assistant pošilja obvestila za čakajoče posodobitve, ker ni odprta nobena registrirana aplikacija in se posodobitve lahko nadaljujejo brez prekinitev za uporabnika. Ta dogodek uporabljamo za določitev števila posodobitev, ki jih je mogoče uporabiti, vendar mora v ta namen ukrepati uporabnik. Ta dogodek se uporablja za pospešitev izboljšanja uporabniške izkušnje.

Zbrana so sledeča polja: 
    
- **Aplikacija** – postopek prijave, ki pošilja dogodek
    
- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku
    
- **AppversionLong** – različica programa
    
- **Channel** – ugodnost občinstva
    
- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)
    
- **DeviceID** – identifikator naprave
    
- **DeviceInfo_Model** – model strojne opreme naprave
    
- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)
    
- **DeviceInfo_OsBuild** – različica operacijskega sistema
    
- **Event_ReceivedTime** – ura prejemanja telemetrijo
    
- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.
    
- **EventInfo_Time** – čas, ko se je zgodil dogodek iz dnevnika 
    
- **HowToCheck** – kako preveriti nastavitev
    
- **Payload** – statično besedilo
    
- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)
    
- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP
    
- **ID** seje – identifikator za sejo

### <a name="fba_nofifyappopen"></a>fba_nofifyappopen

Ta dogodek označuje, da Microsoft Update Assistant pošilja obvestila za čakajoče posodobitve, ker so odprte registrirane aplikacije, za nadaljevanje posodabljanja pa je treba zapreti aplikacije.  Ta dogodek uporabljamo za določitev števila posodobitev, v zvezi s katerimi mora posredovati uporabnik.  Ta dogodek se uporablja za pospešitev izboljšanja uporabniške izkušnje.

Zbrana so sledeča polja:  

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku
    
- **AppversionLong** – različica programa
    
- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je zgodil dogodek iz dnevnika 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID seje** – identifikator za sejo

### <a name="fba_settimerfail"></a>fba_settimerfail  

Ta dogodek označuje poskus nastavitve časovnika za sprožanje prihodnje posodobitve, če ta ni uspela. Ta dogodek je kritičen in ga uporabljamo za ugotavljanje števila neuspešnih poskusov, da poiščemo rešitev, če je potrebno.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je zgodil dogodek iz dnevnika 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – vsebuje informacije o času zadnje posodobitve in koledarju, ki se uporablja

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fba_silentupdateoptin"></a>fba_silentupdateoptin

Ta dogodek pomeni, da se uporabnik odloča v tihih posodobitvah. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="fba_skipforcedupdate"></a>fba_skipforcedupdate

Ta dogodek pomeni, da je preverjanje prisilnega posodabljanja preskočeno zaradi odprtih programov. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fba_startforcedupdate"></a>fba_startforcedupdate

Ta dogodek pomeni, da je prišlo do poskusa uporabe prisilne posodobitve. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fba_terminate"></a>fba_terminate

Ta dogodek pomeni, da se je MAU daemon običajno prekinil. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fba_updatefound"></a>fba_updatefound

Ta dogodek pomeni, da je MAU daemon našel razpoložljive posodobitve, ki so na voljo. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje število razpoložljivih posodobitev, ki so na voljo.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="fba_updatetimer"></a>fba_updatetimer

V tem primeru je navedeno, da je proces Daemona Microsoft autoupdate postal aktiven za preverjanje, ali so na voljo posodobitve, ko ste spali za določeno časovno obdobje. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje podatke o trenutnem času datumov.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fbasilentupdate_allappsclosed"></a>fbasilentupdate_allappsclosed

Ta dnevnik dogodkov, če so bile vse aplikacije zaprte pred namestitvijo. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva
    
- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fbasilentupdate_applaunchafterupdate"></a>fbasilentupdate_applaunchafterupdate

Ta dogodek se prijavi v poskus ponovne uvedbe programa po tihi posodobitvi in načinu posodabljanja (klon ali ne). Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator programa.

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Napaka** – podrobnosti o napaki med zagonom aplikacije po posodobitvi.

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje identifikator, ki se uporablja za spremljanje dejavnosti posodabljanja in ime aplikacije, ki jo je mogoče zagnati. *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar se bo morda še vedo pojavljalo v starejših graditvah.]*
    
- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)
    
- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fbasilentupdate_applaunchwileinstalling"></a>fbasilentupdate_applaunchwileinstalling

Ko namestite posodobitev, se prijavite, ko ste zagnali aplikacijo. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje identifikator, ki se uporablja za spremljanje dejavnosti posodabljanja.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fbasilentupdate_appneedtoclose"></a>fbasilentupdate_appneedtoclose

Ko se začne postopek posodabljanja, se prijavite, da je bila odprta aplikacija za posodobitev. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje identifikator, ki se uporablja za spremljanje dejavnosti posodabljanja, imena ID-ja posodobitev in paketa za pakete uporabe.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fbasilentupdate_appterminationeventreceived"></a>fbasilentupdate_appterminationeventreceived

V tem primeru je navedeno, da je storitev Microsoft Autoupdate prejela dogodek družbe Apple o prekinitvi aplikacije. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator programa.

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Napaka** – podrobnosti o napaki med prekinitvijo programa.

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Koristni tovor** – vsebuje identifikator, ki se uporablja za iskanje ID-ja dejavnosti posodobitve in paketa. To lahko vsebuje tudi niz napake, če Microsoft autoupdate določa, da se aplikacija še vedno izvaja, čeprav je bila prejeta prekinitev dogodka. *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar se bo morda še vedo pojavljalo v starejših graditvah.]*

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **AppID** – identifikator posodobitve programa.


### <a name="fbasilentupdate_clientsession"></a>FBASilentUpdate_ClientSession

Ta dogodek se uporablja za izračun metrike stanja kritičnih posodobitev za Microsoft Auto Update (MAU). Ta dogodek nam omogoča, da označimo, katera posodobitvena seja (za prenos ali za namestitev) se trenutno obdeluje v zaledju.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost za občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – označuje, katera posodobitvena seja (za prenos ali za namestitev) se trenutno obdeluje v zaledju.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **SessionId** – identifikator za sejo


### <a name="fbasilentupdate_codesignfailure"></a>fbasilentupdate_codesignfailure

Ta dogodek zabeleži rezultat preverjanja sooblikovanja, ko uporabite posodobitev. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje rezultat operacije preverjanja sooblikovanja.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **SessionId** – identifikator seje.


### <a name="fbasilentupdate_download"></a>fbasilentupdate_download

Ta dogodek pomeni, da je posodobitev prenesena. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje identifikator, ki se uporablja za spremljanje dejavnosti posodabljanja in ime posodobitve.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fbasilentupdate_downloadfailed"></a>fbasilentupdate_downloadfailed

Ta dogodek pomeni, da je prišlo do napake pri prenosu posodobitve. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator programa.

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Napaka** – podrobnosti o napaki med prenosom posodobitve programa.

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje identifikator, ki se uporablja za spremljanje dejavnosti posodabljanja in ime posodobitve. *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar se bo morda še vedo pojavljalo v starejših graditvah.]*

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **AppID** – identifikator posodobitve programa.

- **UpdateName** – Ime posodobitve aplikacije.


### <a name="fbasilentupdate_downloadinbackground"></a>fbasilentupdate_downloadinbackground

V tem primeru je navedeno, da začenjamo prenos nabora posodobitev v ozadju (zabeležimo število posodobitev, ki so bile sočasno prenesene). Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje število posodobitev, ki je v čakalni vrsti.

    - **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fbasilentupdate_downloadingrepairupdate"></a>fbasilentupdate_downloadingrepairupdate

Ta dogodek pomeni, da smo sprožili poskus prenosa popravila neuspele posodobitve. Zabeležimo različico in posodobitev. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje identifikator, ki se uporablja za spremljanje dejavnosti posodabljanja in ime posodobitve.
    
- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fbasilentupdate_duplicatedownloadattempted"></a>fbasilentupdate_duplicatedownloadattempted

Ta dogodek pomeni, da je prišlo do nepričakovane napake. Naenkrat bi morali le prenesti eno posodobitev za dani program. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fbasilentupdate_installattemptfailed"></a>fbasilentupdate_installattemptfailed

Ta dogodek pomeni, da je poskus namestitve posodobitve (različica) spodletel. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fbasilentupdate_installcomplete"></a>fbasilentupdate_installcomplete

Ta dogodek pomeni, da so vse posodobitve v paketu dokončane z namestitvijo. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fbasilentupdate_installed"></a>fbasilentupdate_installed

V tem primeru je bil uspešno nameščen posamezen posodobitev. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka. Vsebuje identifikator posodobitve.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="fbasilentupdate_installing"></a>fbasilentupdate_installing

V tem primeru je bil uspešno nameščena posamezna posodobitev. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje identifikator, ki se uporablja za spremljanje dejavnosti posodabljanja, imena paketa posodobitev in posodobitev.
    
- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="fbasilentupdate_installstatus"></a>fbasilentupdate_installstatus

Ta dogodek sporoči stanje opravila posodobitve aplikacije. Ta dogodek je del posodobitvenega lijaka za aplikacijo in se uporablja za spremljanje stanja posodobitev aplikacije.

Zbrana so naslednja polja: 

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je zgodil dogodek iz dnevnika 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** –  vsebuje informacije o tem, ali je pogled napredka prikazan

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **Success** –  označuje, ali je bila posodobitev aplikacije uspešna

- **PreviousUpdateID** – identifikator za posodobitev aplikacije

- **UpdateName** – ime posodobitve, kot je prikazano v preneseni datoteki manifesta

- **UpdatePkg** – ime uporabljenega paketa posodobitve

### <a name="fbasilentupdate_notificationerror"></a>fbasilentupdate_notificationerror

Ta dogodek sporoča napako, do katere je prišlo med poskusom pošiljanja uporabniškega obvestila. Ta dogodek se bo uporabil za odpravljanje vzroka za napako in ukrepanje.

Zbrana so sledeča polja:  

- **Aplikacija** – postopek prijave, ki pošilja dogodek
 
- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **ErrType** – označuje naravo napake, do katere je prišlo

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je zgodil dogodek iz dnevnika 

- **HowToCheck** – kako preveriti nastavitev

- **Message** – vsebina obvestila

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **Title** – naslov obvestila

- **Type** – vrsta obvestila

### <a name="fbasilentupdate_notificationremoved"></a>fbasilentupdate_notificationremoved

V tem primeru se prikaže sporočilo, da posodobitev, ki je bila blokirana, ni več blokirana. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ID aplikacije (aplikacija identifikatorja, ki se uporablja za registracijo z Microsoftovo storitvijo za samodejno posodabljanje) za prej blokirano aplikacijo.
    
- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fbasilentupdate_queueinstall"></a>fbasilentupdate_queueinstall

Ta dogodek pomeni, da bo posodobitev v čakalni vrsti za tihi namestitvi. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje identifikator, ki se uporablja za spremljanje dejavnosti posodabljanja in ime posodobitve.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fbasilentupdate_requiredappsclosed"></a>fbasilentupdate_requiredappsclosed

Ko je program, ki ima čakajočo posodobitev, končan, se prijavite. To pomeni čas, ko se lahko postopek dejanske namestitve izvede. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Koristni tovor** – vsebuje identifikator, ki se uporablja za iskanje ID-ja dejavnosti posodobitve in paketa.
    
- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="fbasilentupdate_timerforapptermination"></a>FBASilentUpdate_TimerForAppTermination

Ta dogodek se uporablja za izračun metrike stanja kritičnih posodobitev za Microsoft Auto Update (MAU). Ta dogodek nam omogoča, da sledimo dogodku zapiranja odprte aplikacije in času, ko je bila odprta.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost za občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – označuje, ali je bil za odprto aplikacijo, ko je bila sprožena namestitev posodobitve, nastavljen časovnik. 

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **SessionId** – identifikator za sejo

### <a name="fbasilentupdate_updateavailablenotification"></a>fbasilentupdate_updateavailablenotification

V tem dogodku je navedeno, da je sproženo obvestilo o posodobitvi na voljo. Če želite, da se prikaže sporočilo o posodobitvi, morate zagotoviti, da pride do povratnega toka. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fbasilentupdate_userclicknotification"></a>fbasilentupdate_userclicknotification

V tem dogodku je navedeno, da je uporabnik kliknil vsebino, ki je na voljo v obvestilu o posodobitvi, in Microsoft autoupdate GUI. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fbasilentupdate_userselectinstalllater"></a>fbasilentupdate_userselectinstalllater

Ta dogodek pomeni, da se je uporabnik odločil namestiti pozneje po tem, ko je bila prikazana posodobitev razpoložljivega obvestila. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="fbasilentupdate_userselectinstallnow"></a>fbasilentupdate_userselectinstallnow

Ta dogodek pomeni, da se je uporabnik odločil namestiti pozneje po tem, ko je bila prikazana posodobitev razpoložljivega obvestila. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="gui_dashboardview_appisopendialog_display"></a>gui_dashboardview_appisopendialog_display 

Ta dogodek označuje, da uporabniški vmesnik prikazuje pogovorno okno za zaprtje odprte aplikacije, da bi se nadaljevala posodobitev aplikacije. Ta dogodek se uporablja za ugotavljanje števila posodobitev z zakasnitvijo, da bi zagotovili prihodnje izboljšave, s katerimi bodo prekinitve uporabnika minimizirane.

Zbrana so naslednja polja: 

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je zgodil dogodek iz dnevnika 

- **HowToCheck** – kako preveriti nastavitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID seje** – identifikator za sejo

- **PreviousUpdateID** – identifikator za posodobitev aplikacije

- **UpdateName** – ime posodobitve, kot je prikazano v preneseni datoteki manifesta

### <a name="gui_dashboardview_appisopendialogbutton_clicked"></a>gui_dashboardview_appisopendialogbutton_clicked

Ta dogodek označuje, ali bo posodobitev aplikacije preskočena ali pa se po prikazu odprtega pogovornega okna izvaja drug poskus. Ta dogodek se uporablja za določitev števila posodobitev, ki bodo preskočene in za prihodnje izboljšave, da se kar najbolj zmanjša število prekinitev za uporabnika.

Zbrana so naslednja polja:   

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **ButtonType** – preskoči ali poskusi znova

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave 

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je zgodil dogodek iz dnevnika 

- **HowToCheck** – kako preveriti nastavitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID seje** – identifikator za sejo

- **PreviousUpdateID** – identifikator za posodobitev aplikacije

- **UpdateName** – ime posodobitve, kot je prikazano v preneseni datoteki manifesta

### <a name="gui_dashboardview_updateinprogressdialog_display"></a>gui_dashboardview_updateinprogressdialog_display

Ta dogodek v dnevnik zabeleži, ali je bilo uporabnikom prikazano pogovorno okno, ki označuje, da se posodobitev že izvaja.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost za občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **SessionId** – identifikator za sejo

### <a name="gui_dashboardview_updatemodebutton_clicked"></a>gui_dashboardview_updatemodebutton_clicked

Ta dogodek označuje, da je bil v kontrolniku uporabniškega vmesnika spremenjen način posodobitve. Ta dogodek se uporablja za določitev števila naprav, ki prehajajo z enega načina na drugega in za pomoč pri ugotavljanju, zakaj se stranke zavračajo samodejne posodobitve. 

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek
 
- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je zgodil dogodek iz dnevnika 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – označuje, ali je samodejni prenos izklopljen

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID seje** – identifikator za sejo

### <a name="gui_feedbackwindow_buttonclicked"></a>gui_feedbackwindow_buttonclicked

Ta dogodek sporoča, ali so povratne informacije poslane ali pa preklicane pred pošiljanjem. Ta dogodek se uporablja za pomoč pri ugotavljanju količine povratnih informacij, poslanih za določeno različico izdaje. To je v pomoč pri zgodnji osamitvi morebitnih težav.

Zbrana so naslednja polja: 

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **ButtonType** – označuje, ali so povratne informacije poslane ali preklicane

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema
 
- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="gui_preferenceview_consentsheet_display"></a>gui_preferenceview_consentsheet_display

Ta dogodek označuje, da je prikazan list s soglasjem za navedeni kanal, če je na voljo. Ta dogodek se uporablja za določitev števila naprav, ki se na novo včlanijo v veljavni kanal za občinstvo (Insider Fast/Insider Slow). Ta dogodek uporabljamo tudi, da zagotovimo, da prikaz pogovornega okna s soglasjem deluje in da so za uporabnike prikazani pogoji uporabe.
 
Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **ChannelName** – kanal, za katerega je prikazano pogovorno okno s soglasjem

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je zgodil dogodek iz dnevnika 

- **HowToCheck** – kako preveriti nastavitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="gui_preferenceview_consentsheet_licenseerror"></a>gui_preferenceview_consentsheet_licenseerror

Ta dogodek sporoča napako, do katere je prišlo med poskusom prikaza pogovornega okna s soglasjem. Ta dogodek je kritičen in se uporablja za odpravo morebitnih napak, do katerih pride zaradi zamenjave izdelka, če to velja.

Zbrana so naslednja polja: 

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **ErrorCode** – koda napake, do katere je prišlo

- **ErrorDomain** – domena napake

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je zgodil dogodek iz dnevnika 

- **HowToCheck** – kako preveriti nastavitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="gui_preferenceview_switchchannel"></a>gui_preferenceview_switchchannel

Ta dogodek poroča o prehajanju med kanali, ki jih je izbral uporabnik. Ta dogodek se uporablja za pomoč pri ugotavljanju, zakaj stranke zavrnejo sodelovanje v kanalih za preskuševalce.  

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je zgodil dogodek iz dnevnika 

- **HowToCheck** – kako preveriti nastavitev

- **PickedFrom** – stari kanal

- **PickedFrom** – novi kanal

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="gui_updatemanager_applaunchduringupdate"></a>gui_updatemanager_applaunchduringupdate

Ta dogodek sporoča, da je bila aplikacija zagnana, med tem ko se je posodabljala, in da bo Microsoft AutoUpdate prekinil zagnano aplikacijo. Ne pozabite, da zagon aplikacije, ko se ta posodablja, lahko povzroči poškodbe. S tem dogodkom zagotovimo, da zagnana aplikacija ne vpliva na postopek posodobitve, preden je pripravljen na uporabo.
 
Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator aplikacije, ki je bila zagnana med posodobitvami.

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **Success** – znakovni niz tipa Boolean, ki označuje, ali je bila aplikacija uspešno zaustavljena.

- **UpdateID** – identifikator posodobitve aplikacije.

### <a name="gui_updatemanager_downloadupdateforapp"></a>gui_updatemanager_downloadupdateforapp

Ta dogodek poroča o stanju dokončanja prenosa za posodobitev. S tem dogodkom zagotovimo ustrezno stanje postopka posodobitve in sledenje oz. obdelavo točke z napako.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator aplikacije.

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **IsRepair** – znakovni niz tipa Boolean označuje, ali je določena posodobitev prenos za popravilo.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **isRepair** – označuje, ali je bil prenos namenjen popravilu predhodne neuspešne posodobitve.

- **UpdateID** – identifikator posodobitve.

- **UpdateName** – ime posodobitve.


### <a name="gui_updatemanager_error"></a>gui_updatemanager_error

Ta dogodek je povratno sporočilo o morebitnih napakah, do katerih je prišlo med posodobitvami aplikacije. To lahko označuje napako v zaporedju izvajanja programa Microsoft Auto Update (MAU).  S tem poročilom uporabimo posodobitve za program MAU, da poskrbimo za splošne scenarije z napakami.

Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost za občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – vsebuje informacije o napaki, do katere je prišlo med posodobitvijo aplikacije.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **SessionId** – identifikator za sejo

- **Success** – znakovni niz tipa Boolean, ki označuje, ali je bila aplikacija uspešno zaustavljena.

### <a name="gui_updatemanager_installcleanupforapp"></a>gui_updatemanager_installcleanupforapp

Ta dogodek označuje, da so začasne datoteke, ustvarjene med nameščanjem aplikacije, uspešno počiščene. Ta je del posodobitvenega lijaka, ki se uporabi za določitev ustreznosti stanja posodobitve aplikacije.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator aplikacije.

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppState** – celo število označuje stanje aplikacije po poskusu posodobitve.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost za občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **SessionId** – identifikator za sejo

- **UpdateID** – identifikator posodobitve.


### <a name="gui_updatemanager_installsuccessforapp"></a>gui_updatemanager_installsuccessforapp

Ta dogodek označuje uspešno posodobitev aplikacije. Ta dogodek je del posodobitvenega lijaka, ki se uporabi za določitev ustreznosti stanja posodobitve.
 
Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator aplikacije.

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **Success** – znakovni niz tipa Boolean označuje, ali so bile posodobitve uspešno nameščene.

- **UpdateID** – identifikator posodobitve.

### <a name="gui_updatemanager_installupdateforapp"></a>gui_updatemanager_installupdateforapp

Ta dogodek označuje začetek dejanskega postopka namestitve za posodobitev aplikacije. Ta dogodek je del posodobitvenega lijaka, ki se uporabi določitev ustreznosti stanja posodobitve.
 
Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator aplikacije.

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **UpdateID** – identifikator posodobitve.

### <a name="gui_updatemanager_queueinstallforapp"></a>gui_updatemanager_queueinstallforapp

Ta dogodek označuje začetek dejanskega postopka namestitve za posodobitev aplikacije. Ta dogodek je del posodobitvenega lijaka, ki se uporabi določitev ustreznosti stanja posodobitve.
 
Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator aplikacije.

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **UpdateID** – identifikator posodobitve.

### <a name="gui_updatemanager_relaunchapp"></a>gui_updatemanager_relaunchapp

Ta dogodek zabeleži v dnevnik, ali so bile aplikacije po posodobitvah uspešno znova zagnane.
 
Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator aplikacije.

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **Success** – znakovni niz tipa Boolean, ki označuje, ali je bila aplikacija uspešno zaustavljena.

- **UpdateID** – identifikator posodobitve.

- **UpdateName** – ime posodobitve.

### <a name="installdata_checkrunning"></a>installdata_checkrunning

Ta dogodek zabeleži rezultat pregleda med aplikacijami, ki jih je treba namestiti, in ali bo poskus namestitve izveden glede na odpiranje aplikacije. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="installdata_cleanup"></a>installdata_cleanup

Datoteke paketa morate odstraniti po namestitvi. Ta dogodek zabeleži primere, v katerih jih ne moremo odstraniti. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje preneseno ime datoteke in podrobnosti o napaki.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="installedapp_invalidbundle"></a>installedapp_invalidbundle

V tem dogodku je navedeno, da Microsoft autoupdate ni mogel pridobiti informacij o paketu za registrirano aplikacijo na dani poti. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ime aplikacije.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="installedapp_invalidpreference"></a>installedapp_invalidpreference

Ta dogodek zabeleži primere, v katerih uporabnik preference vsebuje neveljaven vnos programa. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="installedapp_nilbundleid"></a>installedapp_nilbundleid

Ta dogodek zabeleži primere, v katerih ID snopa manjka za aplikacijo. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ime aplikacije.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="installedapp_nilbundlename"></a>installedapp_nilbundlename

Ta dogodek zabeleži primere, v katerih ime snopa manjka za aplikacijo. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ime aplikacije.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="installedapp_sendcoreappleevent"></a>installedapp_sendcoreappleevent

Ta dogodek označuje, da Microsoft Auto Update (MAU) pošilja dogodek Apple v registrirano aplikacijo, da prekine aplikacijo, da bi se lahko nadaljevala čakajoča posodobitev aplikacije. Ta dogodek se trenutno uporablja za pomoč pri prihodnjih izboljšavah, s katerimi bodo kar najbolj zmanjšane prekinitve med posodobitvami aplikacij. 

Zbrana so ta polja:

- **Acknowledged** – označuje, ali je zadevna aplikacija potrdila prejem dogodka

- **App** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija

- **AppleEventClass** – označuje vrsto dogodka, ki se pošilja ali potrjuje

- **AppleEventID** – enočični identifikator dogodka, ki se pošilja/potrjuje

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je zgodil dogodek iz dnevnika 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – vsebuje število ponovnih poskusov

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **Success** – označuje, ali je zadevna aplikacija sporočila uspešno izvedbo postopka

    
### <a name="installstatus_codesign"></a>installstatus_codesign

Ta dogodek zabeleži stanje binarne funkcije za sonačrtovanje OS. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek
    
- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="installstatus_daemon"></a>installstatus_daemon

Ta dogodek zabeleži stanje stanja Microsoftovega daemona autoupdate. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje navedbo, ali komponenta daemon obstaja na pričakovanem mestu in ali je sooblikovana.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="installstatus_helper"></a>installstatus_helper

Ta dogodek zabeleži stanje stanja Microsoftovega orodja za samodejno posodabljanje. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje navedbo, ali komponenta PrivilegedHelperTool obstaja na pričakovanem mestu in ali je sooblikovana.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="installupdatestask_applaunched"></a>installupdatestask_applaunched

V tem dogodku je navedeno, da je Microsoft autoupdate zaznal izdajo programa, ki je blokirana, vendar ni našla ustreznega namestitvenega programa. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ime pobudnika aplikacije.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="installupdatestask_applaunchwithpendingupdate"></a>installupdatestask_applaunchwithpendingupdate

V tem primeru je navedeno, da je Microsoft autoupdate zaznal zagon programa za aplikacijo z čakajočo posodobitvijo. Zagnana aplikacija bo prekinjena. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="installupdatestask_codesignverificationfail"></a>installupdatestask_codesignverificationfail

Ta dogodek pomeni, da preverjanje sooblikovanja ni uspelo za posodobitev programa. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje identifikator, ki se uporablja za spremljanje dejavnosti posodabljanja, imena posodobljenega programa in kode napake.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="installupdatestask_codesignverificationstart"></a>installupdatestask_codesignverificationstart

Ta dogodek pomeni, da se je preverjanje sooblikovanja začelo z posodobitvijo aplikacije. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje identifikator, ki se uporablja za spremljanje dejavnosti posodabljanja in ime posodobljene aplikacije.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="installupdatestask_codesignverificationsuccess"></a>installupdatestask_codesignverificationsuccess

V tem primeru se prikaže sporočilo o napaki pri preverjanju, ali je bila posodobitev programa posodobljena. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje identifikator, ki se uporablja za spremljanje dejavnosti posodabljanja in ime posodobljene aplikacije.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="installupdatestask_failsilentinstall"></a>installupdatestask_failsilentinstall

Ta dnevnik dogodkov ne pride med uporabo tihih posodobitev in ali je bila to klonirana ali navadna namestitev. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 
    
- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje identifikator, ki se uporablja za spremljanje dejavnosti posodabljanja in vrste posodobitve.
    
- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="installupdatestask_multiplerelocatablepackage"></a>installupdatestask_multiplerelocatablepackage

V tem dogodku je navedeno, da je Microsoft autoupdate našel več primerkov vnosa aplikacije za dani paket posodobitev, ki je bil naložen manifestu. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in za pomoč pri odpravljanju napak.
 
Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje identifikator, ki se uporablja za spremljanje dejavnosti posodabljanja in ime posodobitve.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="installupdatestask_removeclone"></a>installupdatestask_removeclone

Ta dogodek pomeni, da je bil odstranjen klon. Odstranitev klona je izpolnjena, če je bil postopek namestitve postopka kloniranja končan ali ko se začne nov proces, v računalniku pa je na voljo starejša klonirana različica. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje identifikator, ki se uporablja za spremljanje dejavnosti posodabljanja, ime posodobitve, ime paketa posodobitev, odstranitev statusa klona/podrobnosti o napaki.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="installupdatestask_retryfail"></a>installupdatestask_retryfail

Ta dogodek pomeni, da so prišlo do napak med postopkom vnovičnega popravka namestitve. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje identifikator, ki se uporablja za spremljanje dejavnosti posodabljanja, ime posodobitve in ali naj bo namestitev izvedena prek namestitve v klonu

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="installupdatestask_retryproxyerror"></a>installupdatestask_retryproxyerror

Ta dogodek zabeleži napake komunikacije znotraj procesa (komunikacija z orodjem za pomoč MAU). Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje identifikator, ki se uporablja za spremljanje dejavnosti posodabljanja, ime posodobitve in podrobnosti o sporočeni napaki strežnika proxy.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="installupdatestask_retryproxyerror"></a>installupdatestask_retryproxyerror

Ta dogodek zabeleži napake komunikacije znotraj procesa (komunikacija z orodjem za pomoč MAU). Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje identifikator, ki se uporablja za spremljanje dejavnosti posodabljanja, ime posodobitve in podrobnosti o sporočeni napaki strežnika proxy.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    

### <a name="installupdatestask_retryresponse"></a>installupdatestask_retryresponse

V tem dnevniku dogodkov, ki jih vnovičen poskus ne deluje. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje identifikator, ki se uporablja za spremljanje dejavnosti posodabljanja, ime posodobitve, različico programa, ime paketa posodobitev in navedbo, ali je bila namestitev v klon vklopljena, ne glede na to, ali je bila namestitev uspešna in katere koli napake, ki so bile sporočene glede napake.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="installupdatestask_retrysuccess"></a>installupdatestask_retrysuccess

Ta dogodek zabeleži uspešno namestitev posodobitve po vnovičnem poskusu. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje identifikator, ki se uporablja za spremljanje dejavnosti posodabljanja, ime posodobitve, različico programa, ime paketa posodobitev in navedbo, ali je bila namestitev v klon vklopljena.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="installupdatestask_setreopengui"></a>installupdatestask_setreopengui

V tem primeru je navedeno, ali je nastavitev možnosti za vnovično odpiranje uporabniškega vmesnika» GUI «uspešna. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo prikazuje uspeh operacije.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="installupdatestask_updatestatus"></a>installupdatestask_updatestatus

Ta dogodek sporoča stanje namestitvenega opravila. Ta dogodek je del poročila o posodobitvenem lijaku in se uporablja za določitev ustreznosti stanja posodobitev aplikacije.

Zbrana so sledeča polja: 

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Error** – označuje vse napake, do katerih je prišlo med postopkom posodobitve, če je izpolnjen

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je zgodil dogodek iz dnevnika 

- **HowToCheck** – kako preveriti nastavitev

- **IOC** – označuje, ali je bila uporabljena funkcija namestitve v klon

- **Payload** – statično besedilo, ki označuje začetek namestitvenega postopka, če je prisoten

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **Success** –  označuje, ali je namestitveni postopek uspešno dokončan

- **PreviousUpdateID** – identifikator za posodobitev aplikacije

- **UpdateName** – ime posodobitve, kot je prikazano v preneseni datoteki manifesta

- **UpdatePkg** – ime uporabljenega paketa posodobitve


### <a name="msupdate_cli_eventhandler"></a>msupdate_cli_eventhandler

Ta dogodek se uporablja za izračun uporabe različnih tipov programskega vmesnika API ukazne vrstice programa Microsoft Auto Update (MAU).

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator aplikacije, ki pošilja programski vmesnik API ukazne vrstice programa MAU.

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – čas, ko je bila prejeta telemetrija

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **EventType** – vrsta dogodka, ki ga pošilja aplikacija v programski vmesnik API ukazne vrstice programa MAU.

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="msupdate_cli_eventhandler_applyupdates_appids"></a>msupdate_cli_eventhandler_applyupdates_appids

V tem dogodku je navedeno, da je bil ukaz CLI (vmesnik odjemalca) izdan tako, da je uporabljal posodobitev. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – vsebuje seznam ID-jev aplikacije, ki jih želite posodobiti.
    
- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="msupdate_cli_eventhandler_config"></a>msupdate_cli_eventhandler_config

V tem primeru je navedeno, da je modul vmesnika ukazne vrstice Microsoft Autoupdate prejel dogodek družbe Apple, ki ga je treba konfigurirati. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="msupdate_cli_eventhandler_updates"></a>msupdate_cli_eventhandler_updates

V tem dogodku je navedeno, da je modul vmesnika ukazne vrstice za samodejno posodabljanje sistema Microsoft prejel dogodek Apple za seznam posodobitev. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="msupdate_monitor_progress_downloaded"></a>msupdate_monitor_progress_downloaded

Ta dogodek pomeni, da so bile posodobitve prenesene. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje sezname posodobitev, ki so bile prenesene

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="msupdate_monitor_progress_failure"></a>msupdate_monitor_progress_failure

Ta dogodek zabeleži seznam posodobitev, ki niso bile uporabljene v čakalni vrsti. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje sezname posodobitev.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="msupdate_monitor_progress_finished"></a>msupdate_monitor_progress_finished

Ta dogodek zabeleži seznam posodobitev, ki so bile dokončane z namestitvijo. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje sezname posodobitev.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="msupdate_monitor_progress_queued"></a>msupdate_monitor_progress_queued

Ta dogodek zabeleži seznam posodobitev v čakalni vrsti. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje sezname posodobitev.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="optinnotificationaction"></a>Optinnotificationaction

Ta dogodek prijavi uporabnikov odgovor v pogovorno okno za vpis v tihe posodobitve. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje statično besedilo, ki predstavlja izbor uporabnika za izbiro samodejnega prenosa in namestitve.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="sauforcedupdate_autodismiss"></a>sauforcedupdate_autodismiss

Ta dogodek označuje, da je bilo prikazano pogovorno okno vsiljene posodobitve opuščeno zaradi nedejavnosti uporabnika. Ta dogodek se uporablja za določitev števila vsiljenih posodobitev, ne da bi uporabniki posredovali kakršen koli vnos v prikazano obvestilo. Ta dogodek se uporablja za izboljšanje uporabniškega vmesnika, da bi kar najbolj zmanjšali prekinitve.

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave
  
- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **SessionId** – identifikator za sejo

### <a name="sauforcedupdate_close"></a>sauforcedupdate_close

Ta dogodek označuje, da bo uporabnik zaprl okno vsiljene posodobitve. Ta dogodek se uporablja za določitev števila vsiljenih posodobitev, ki so odložene zaradi uporabniškega dejanja. Ta dogodek se uporablja za izboljšanje uporabniškega vmesnika, da bi kar najbolj zmanjšali prekinitve. 

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="sauforcedupdate_completeautodismiss"></a>sauforcedupdate_completeautodismiss

Ta dogodek označuje, da se prikazano pogovorno okno vsiljene posodobitve iz funkcije z določenim rokom opušča zaradi nedejavnosti uporabnika. Ta dogodek se uporablja za določitev števila vsiljenih posodobitev, ne da bi uporabniki posredovali kakršen koli vnos v prikazano obvestilo. Ta dogodek se uporablja za izboljšanje uporabniškega vmesnika, da bi kar najbolj zmanjšali prekinitve za funkcijo z določenim rokom.

Zbrana so sledeča polja: 

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="sauforcedupdate_completeclose"></a>sauforcedupdate_completeclose

Ta dogodek označuje uspešno dokončanje vsiljene posodobitve. Ta dogodek se uporablja za pomoč pri določitvi ustreznosti stanja funkcije vsiljene posodobitve. 

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="sauforcedupdate_display"></a>sauforcedupdate_display

Ta dogodek označuje, da je prikazano pogovorno okno vsiljene posodobitve.  Ta dogodek je del poročila o vsiljenem posodobitvenem lijaku in se uporablja za določitev ustreznosti stanja posodobitve aplikacije.

Zbrana so sledeča polja: 

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="sauforcedupdate_displayfinalhour"></a>sauforcedupdate_displayfinalhour

Ta dogodek označuje, da je prikazano pogovorno okno zadnje ure za vsiljeno posodobitev. Ta dogodek je del poročila o vsiljenem posodobitvenem lijaku in ga uporabljamo za določitev ustreznosti stanja vsiljene funkcije posodobitve.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="sauforcedupdate_done"></a>sauforcedupdate_done

Ta dogodek označuje, da je vsiljena posodobitev uspešno dokončana. Ta dogodek je del poročila o vsiljenem posodobitvenem lijaku in se uporablja za določitev ustreznosti stanja vsiljene funkcije posodobitve. 

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="sauforcedupdate_enabled"></a>sauforcedupdate_enabled

Ta dogodek se sproži, ko Microsoft Auto Update (MAU) določi, da je vsiljena posodobitev veljavna.  Ta dogodek se uporablja za določitev ustreznosti stanja funkcije vsiljene posodobitve. 

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Enabled** – označuje, ali je vsiljena posodobitev omogočena

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **InvalidUpdates** – število vsiljenih posodobitev, nastavljenih z nevelčjavnimi različicami posodobitve

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="sauforcedupdate_forcedupdatedismiss"></a>sauforcedupdate_forcedupdatedismiss

Ta dogodek označuje, da je se prikazano pogovorno okno z zadnjo uro vsiljene posodobitve opušča zaradi nedejavnosti uporabnika. Ta dogodek se uporablja za določitev števila vsiljenih posodobitev, ne da bi uporabniki posredovali kakršen koli vnos v prikazano obvestilo. Ta dogodek se uporablja za izboljšanje uporabniškega vmesnika, da bi kar najbolj zmanjšali prekinitve. 

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="sauforcedupdate_forcequitandupdatenow"></a>sauforcedupdate_forcequitandupdatenow

Ta dogodek označuje začetek vsiljene posodobitve, ki jo je iniciral uporabnik. Ta dogodek je del lijaka in se uporablja za določitev ustreznosti stanja funkcije vsiljene posodobitve. 

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo 

### <a name="sauforcedupdate_forceterminate"></a>sauforcedupdate_forceterminate

Ta dogodek označuje začetek vsiljene posodobitve, pri čemer se aplikacijo na silo zaustavi.  Ta dogodek je del lijaka in se uporablja za določitev ustreznosti stanja funkcije vsiljene posodobitve.

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – vsebuje število aplikacij, ki bodo prekinjene

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="sauforcedupdate_quitandupdatenow"></a>sauforcedupdate_quitandupdatenow

Ta dogodek označuje, da se je uporabnik odločil, da bo zaprl aplikacijo in uporabil posodobitev. Ta dogodek je del lijaka in se uporablja za določitev ustreznosti stanja funkcije vsiljene posodobitve. 

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="sauforcedupdate_snooze"></a>sauforcedupdate_snooze

Ta dogodek označuje, da se je uporabnik odločil, da bo odložil vsiljeno posodobitev. Ta dogodek je del lijaka in se uporablja za določitev ustreznosti stanja funkcije vsiljene posodobitve. 

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="sauforcedupdate_terminate"></a>sauforcedupdate_terminate

Ta dogodek označuje začetek vsiljene posodobitve, pri čemer se aplikacijo zaustavlja. Ta dogodek je del lijaka in se uporablja za določitev ustreznosti stanja funkcije vsiljene posodobitve.

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – vsebuje število aplikacij, ki bodo prekinjene

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="sauforcedupdate_updatenow"></a>sauforcedupdate_updatenow

Ta dogodek označuje, da se je uporabnik odločil, da bo aplikacijo posodobil v tem trenutku.  Ta dogodek je del lijaka in se uporablja za določitev ustreznosti stanja funkcije vsiljene posodobitve.

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="sauupdateinfoprovider"></a>sauupdateinfoprovider

Ta dnevnik dogodkov vsakič, ko na podlagi zavarovanja manjka ključ manifesta. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje niz, ki se uporablja za iskanje lokacije ali velikosti posodobitve.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="update_applaunchdetected"></a>update_applaunchdetected

Ta dogodek označuje, da je bila aplikacija zagnana med izvajanjem posodobitve Ta dogodek se uporablja za določitev števila aplikacij, ki so zagnane med posodabljanjem in za izboljšanje uporabniške izkušnje v prihodnjih izdajah.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **Success** – označuje, ali je bila zagnana apliakcija uspešno zaustavljena

- **PreviousUpdateID** – identifikator za posodobitev aplikacije

### <a name="update_appterminationreceived"></a>update_appterminationreceived

Ta dogodek označuje, da je aplikacija z blokirano posodobitvijo zaustavljena in ali lahko Microsoft Auto Update (MAU) nadaljuje s posodobitvijo. Ta dogodek je del lijaka in se uporablja za določitev ustreznosti stanja posodobitev aplikacije.

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Error** – označuje, ali so prisotni drugi primerki aplikacije, ki se še vedno izvaja, kar programu MAU preprečuje nadaljevanje postopka

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo, ki označuje, da MAU nadaljuje s posodobitvijo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID seje** – identifikator za sejo

- **PreviousUpdateID** – identifikator za posodobitev aplikacije

### <a name="update_blockedappclosed"></a>update_blockedappclosed

Ta dogodek označuje, da je Microsoft Auto Update (MAU) zaznal, da je aplikacija z blokirano posodobitvijo zaprta in da lahko nadaljuje s posodobitvijo. Ta dogodek je del lijaka in se uporablja za določitev ustreznosti stanja posodobitev aplikacije. 

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – čas, ko je bila prejeta telemetrija.

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil. 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID seje** – identifikator za sejo

- **PreviousUpdateID** – identifikator za posodobitev aplikacije

### <a name="update_blockedinstallskip"></a>update_blockedinstallskip

Ta dogodek zabeleži v dnevnik napako, do katere je prišlo pri poskusu, da bi se posodobitev aplikacije preskočila. Ta dogodek je kritičen in se uporablja za preiskavo sporočenih napak.  

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – vsebuje informacije o napaki, do katere je prišlo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="update_clientsession"></a>update_clientsession

Ta dogodek je sporočen, ko se spremeni stanje odjemalske naprave, zaradi česar Microsoft Update Assistant začasno ustavi ali nadaljuje postopek posodobitve. Ta dogodek je del lijaka in se uporablja za določitev ustreznosti stanja posodobitev aplikacije. 

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – označuje, ali bo Microsoft Auto Update (MAU) nadaljeval postopek ali ga bo začasno prekinil

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="update_download_begin"></a>update_download_begin 

Ta dogodek označuje začetek postopka posodobitve aplikacije. Ta dogodek je del posodobitvenega lijaka in se uporablja za določitev ustreznosti stanja posodobitev aplikacije. 

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **IsRepair** – označuje, ali je posodobitev povezana s popravilom neuspešne posodobitve

- **Payload** – označuje, ali je poskus posodobite v preteklosti že bil izveden

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **UpdateName** – ime posodobitve, kot je prikazano v preneseni datoteki manifesta

### <a name="update_download_finish"></a>update_download_finish

Ta dogodek označuje dokončanje posodobitvene faze za posodobitev aplikacije. Ta dogodek je del posodobitvenega lijaka in se uporablja za določitev ustreznosti stanja posodobitev aplikacije.  

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **IsRepair** – označuje, ali je posodobitev povezana s popravilom neuspešne posodobitve

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID seje** – identifikator za sejo

- **PreviousUpdateID** – identifikator za posodobitev aplikacije

- **UpdateName** – ime posodobitve, kot je prikazano v preneseni datoteki manifesta

### <a name="update_downloadresume"></a>update_downloadresume

Ta dogodek sporoča napako, do katere je prišlo med poskusom nadaljevanja začasno ustavljenega opravila prenosa. Ta dogodek je kritičen in se uporablja za preiskavo sporočenih napak. 

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Error** – označuje naravo napake, do katere je prišlo

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID seje** – identifikator za sejo

- **PreviousUpdateID** – identifikator za posodobitev aplikacije

### <a name="update_error"></a>update_error

Ta dogodek sporoča napako, do katere je prišlo med poskusom posodobitve registrirane aplikacije.  Ta dogodek je kritičen in se uporablja za preiskavo sporočenih napak. 

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Error** – vsebuje informacije o naravi napake, do katereje prišlo

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – vsebuje informacije o naravi napake, do katereje prišlo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="update_installcleanupforapp"></a>update_installcleanupforapp

Ta dogodek označuje, da se je namestitev posodobitve dokončala in da Microsoft Auto Update (MAU) izvaja postopek čiščenja.  Ta dogodek je del posodobitvenega lijaka in se uporablja za določitev ustreznosti stanja posodobitev aplikacije.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija

- **AppState** – stanje registrirane aplikacije. Lahko označuje napako, čakajoče popravilo itn.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID seje** – identifikator za sejo

- **PreviousUpdateID** – identifikator za posodobitev aplikacije

### <a name="update_installupdateforapp"></a>update_installupdateforapp

Ta dogodek se uporablja za poročanje o začetku postopka namestitve posodobitve. Ta dogodek je del posodobitvenega lijaka in se uporablja za določitev ustreznosti stanja posodobitev aplikacije. 

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Error** – napake, do katerih je prišlo, če so

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID seje** – identifikator za sejo

- **PreviousUpdateID** – identifikator za posodobitev aplikacije

- **UpdateName** – ime posodobitve, kot je prikazano v preneseni datoteki manifesta

### <a name="update_installupdateforapp_success"></a>update_installupdateforapp_success

Ta dogodek sporoča stanje namestitvenega opravila. Ta dogodek je del posodobitvenega lijaka in se uporablja za določitev ustreznosti stanja posodobitev aplikacije. 

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – označuje, ali je pogled napredka prikazan med namestitvenim postopkom

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **Success** – oznaka uspeha, vrnjenega iz namestitvenega opravila

- **PreviousUpdateID** – identifikator za posodobitev aplikacije

### <a name="update_installvariance"></a>Update_InstallVariance

Ta dogodek se uporablja za izračun metrike ustreznosti stanja kritične posodobitve za MAU. Ta dogodek nam omogoča, da določimo metriko uspeha za funkcijo prednostne namestitve in preverimo integriteto funkcije.
 
Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – vsebuje seznam ID-jev aplikacij in pripadajočih prednostnih namestitev v številkah.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="update_multipleappupdates"></a>update_multipleappupdates 

Ta dogodek označuje, da v ozadju poteka posodobitev več aplikacij. Ta dogodek je del posodobitvenega lijaka in se uporablja za določitev ustreznosti stanja posodobitev aplikacije.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave 

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – vsebuje informacije o številu aplikacij, ki se posodabljajo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="update_previousidnil"></a>update_previousidnil

Ta dogodek označuje, da se prenaša paket posodobitev za popravilo, vendar ni na voljo nobenih informacij o predhodnem prenosu. Ta dogodek je kritičen in se uporablja za preiskavo sporočenih napak. 

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Error** – označuje naravo napake, do katere je prišlo

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="update_queueinstallforapp"></a>update_queueinstallforapp 

Ta dogodek označuje, da je preneseni posodobitveni paket vstavljen v vrsto za namestitev.  Ta dogodek je del posodobitvenega lijaka in se uporablja za določitev ustreznosti stanja posodobitev aplikacije.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo, ki označuje, da je treba aplikacijo zapreti, če je prisotna

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID seje** – identifikator za sejo

- **PreviousUpdateID** – identifikator za posodobitev aplikacije

- **UpdateName** – ime posodobitve, kot je prikazano v preneseni datoteki manifesta

### <a name="update_relaunchafterupdate"></a>update_relaunchafterupdate 

Ta dogodek označuje, da je posodobitev aplikacije dokončana in da se znova zaganja. Ta dogodek je del posodobitvenega lijaka in se uporablja za določitev ustreznosti stanja posodobitev aplikacije. 

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Error** – vsebuje informacije o morebitnih napakah, do katerih pride med poskusom vnovičnega zagona aplikacije

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID seje** – identifikator za sejo

- **PreviousUpdateID** – identifikator za posodobitev aplikacije

### <a name="update_timerforapptermination"></a>update_timerforapptermination 

Ta dogodek označuje začetek/konec časovnika za preverjanje stanja aplikacije. Ta dogodek je sporočen v paru in se uporablja za določanje, da so vsi predmeti časovnika odstranjeni, ko se posodobitev aplikacije nadaljuje.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – označuje, ali je bil časovnik dodan ali odstranjen

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="updatecore_appregistration"></a>updatecore_appregistration

Ta dnevnik dogodkov poskuša registrirati aplikacijo in rezultat/razlog. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje identifikator, ki se uporablja za spremljanje dejavnosti posodabljanja, navedba, ali je na voljo ugodnost, označba, ali je to Vnovična registracija, in navedbo, ali je zahtevana registracija.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="updatecore_loadinglaunchagent"></a>updatecore_loadinglaunchagent

Ta dogodek pomeni, da je bil naložen agent za zagon. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="updatecore_runnstaskcommand"></a>updatecore_runnstaskcommand

Ta dogodek sporoči napako med poskusom zagona opravila. Ta dogodek je kritičen in se uporablja za preiskavo sporočenih napak.  

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – vsebuje pot do ukaza, ki se izvaja

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="updatecore_server_connectionfail"></a>updatecore_server_connectionfail

Ta dnevnik dogodkov se je prizadela, ko je dosegel dostop do programa CDN. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje informacije o imenu strežnika, ne glede na to, ali je strežnik veljaven in ali je strežnik dosegljiv.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="updatecore_server_nullurl"></a>updatecore_server_nullurl

Ta dogodek sporoči napako, ki označuje, da določenega strežnika ni bilo mogoče doseči. Ta dogodek se uporablja za določitev stopnje neuspešnih posodobitev zaradi težav z omrežjem. 

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="updatefilterhelper_cannotretrievebuilddate"></a>updatefilterhelper_cannotretrievebuilddate

Posodobitve lahko filtrirate s storitvijo MAU le takrat, ko ponujena posodobitev ni starejša od določenega števila dni. V tem dnevniku ne bi mogli pridobiti datuma iz metapodatkov programa. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ID aplikacije.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="updatefilterhelper_invalidappid"></a>updatefilterhelper_invalidappid

Ta dogodek sporoči napako, ki označuje, da ni bilo mogoče najti nobenih ujemajočih se datotek manifesta z ID-jem aplikacije, pridobljenim iz spletnega odziva. Ta dogodek se uporablja za preiskovanje sporočene napake.

Zbrana so naslednja polja: 

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – vsebuje ID aplikacije v spletnem odzivu

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="updatefilterhelper_invalidappidfromwebservices"></a>updatefilterhelper_invalidappidfromwebservices

Ta dogodek sporoči napako, ki označuje, da ID aplikacije, pridobljen iz spletnega odziva, ni v pričakovani obliki zapisa. Ta dogodek se uporablja za preiskovanje sporočene napake.

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – statično besedilo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="updatefilterhelper_invalidresponsefromupdatefiltering"></a>updatefilterhelper_invalidresponsefromupdatefiltering

Posodobitve lahko filtrirate s storitvijo MAU le takrat, ko ponujena posodobitev ni starejša od določenega števila dni. V tem dnevniku manjkajo datumi iz metapodatkov programa. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 
    
- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ID aplikacije.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="updatefilterhelper_missingbuilddate"></a>updatefilterhelper_missingbuilddate

Posodobitve lahko filtrirate s storitvijo MAU le takrat, ko ponujena posodobitev ni starejša od določenega števila dni. V tem dnevniku manjkajo datumi iz metapodatkov programa. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ID aplikacije.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="updatefilterhelper_updatebypassedoldage"></a>updatefilterhelper_updatebypassedoldage

Posodobitve lahko filtrirate s storitvijo MAU le takrat, ko ponujena posodobitev ni starejša od določenega števila dni. Tukaj se prijavite storitev, ki je obšla zaradi starega datuma posodabljanja. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ID aplikacije.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="updatefinder_check_error"></a>updatefinder_check_error

Ta dogodek sporoči napako, do katere je prišlo med preverjanjem posodobitev. Ta dogodek je kritičen in se uporablja za preiskavo sporočene napake. 

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Code** – koda napake 

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Domain** – domena napake

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

 
### <a name="updatefinder_check_start"></a>updatefinder_check_start

Ta dnevnik dogodkov vsakič, ko začnete preverjanje delovanja posodobitev. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek
    
- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje informacije o posodobitvah, ki so na voljo, registrirane aplikacije in prenesene datoteke v začasnem mestu bodo shranjene v.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="updatefinder_check_status"></a>updatefinder_check_status

S tem dogodkom združite stanje preveri, ali so na primer operacije za preverjanje posodabljanja (lij od iskanja do prenašanja). Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje informacije o posodobitvah, ki so na voljo, registrirane aplikacije in prenesene datoteke v začasnem mestu bodo shranjene v.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="updatefinder_check_updatefound"></a>updatefinder_check_updatefound

Ko se prikaže potrditveno polje preveri, ali so na voljo posodobitve, se prijavite vsakič, ko se prikaže. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="updatefinder_check_updatenotfound"></a>updatefinder_check_updatenotfound

Ko preverite, ali so na voljo posodobitve, se prijavite vsakič, ko preverimo, ali je prišlo do nobenih posodobitev, ki jih ni bilo mogoče najti. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="updatefinder_check_uptodate"></a>updatefinder_check_uptodate

Ko preverimo, ali so na voljo posodobitve, se prijavite vsakič, ko se posodobitve ne ponudijo zaradi vseh programov, ki so že posodobljeni. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="updatefinder_offerupdates_invalidappid"></a>updatefinder_offerupdates_invalidappid

Ta dogodek sporoči napako med poskusom ugotavljanja, ali je posodobitev veljavna. Ta dogodek je kritičen in se uporablja za preiskavo sporočene napake.  

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **CatalogID** – identifikator za katalog, do katerega dostopate

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **IsNullID** – označuje, ali je ID »null«

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="updatefinder_offerupdates_minoscheckfail"></a>updatefinder_offerupdates_minoscheckfail

Ko smo blokirali posodobitev, se prijavite vsakič, ko je prišlo do neizpolnjevanja zahtev za OS. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje najmanjšo zahtevano različico OS, kot je določeno v preneseni datoteki manifesta.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="updatefinder_offerupdates_missingtrigger"></a>updatefinder_offerupdates_missingtrigger

Ta dogodek sporoči napako med poskusom ocene sprožilcev v prenesenem manifestu za posodobitev aplikacije. Ta dogodek je kritičen in se uporablja za preiskavo sporočene napake.  

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **TriggerKey** – ključ sprožilca, najden v manifestu

- **Triggers** – slovar sprožilcev, najdenih v manifestu

### <a name="updatefinder_offerupdates_nullbundleforappid"></a>updatefinder_offerupdates_nullbundleforappid

V tem dogodku je navedeno, da Microsoft autoupdate ni uspel naložiti informacij o paketu za ID aplikacije, ki je naveden v preneseni datoteki manifesta. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ID aplikacije.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="updatefinder_offerupdates_updaterulematched"></a>updatefinder_offerupdates_updaterulematched

Ta dogodek pomeni, da je bila za aplikacijo in osnovni načrt najdena posodobitev. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ID aplikacije in informacije o različici združevanja.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="updatefinder_registeredapps"></a>updatefinder_registeredapps

Prijavimo aplikacije, ki so nameščene/registrirane/pod nadzorom MAU. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ID aplikacije in informacije o različici združevanja.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="updatefinder_suite_invalidsuiteversion"></a>updatefinder_suite_invalidsuiteversion

Ta dogodek sporoči napako v zvezi z različico zbirke med poskusom ugotavljanja, ali je posodobitev veljavna. Ta dogodek je kritičen in se uporablja za preiskavo sporočene napake.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **Suite** – ime zbirke, ki se upošteva

### <a name="updatefinder_suite_keyvaluemissing"></a>updatefinder_suite_keyvaluemissing

Ta dogodek sporoči napako med poskusom dodajanja aplikacije v zbirko. Ta dogodek je kritičen in se uporablja za preiskavo sporočene napake.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo 

- **Suite** – dodati bo treba ime zbirke

    
### <a name="updatefinder_suite_missingcollateral"></a>updatefinder_suite_missingcollateral

Posodobitev zbirke – dnevnik se zabeleži vsakič, ko se posodobitev zbirke ne uporablja zaradi pomanjkanja zavarovanja. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – besedilo, ki označuje vrsto dogodka.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="updatefinder_suite_staleversion"></a>updatefinder_suite_staleversion

Posodobitev zbirke – dnevnik se zabeleži vsakič, ko se posodobitev zbirke ne uporablja zaradi prestaranja različice osnovnega načrta. Zabeležimo različico osnovne vrstice in AppId paketa. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ime zbirke.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="updatefinder_suite_updateapplicable"></a>updatefinder_suite_updateapplicable

Posodobitev zbirke – dnevnik se zabeleži vsakič, ko se posodobitev zbirke uporablja. Zabeležimo različico osnovne vrstice in AppId paketa. Zabeležimo različico osnovne vrstice in AppId paketa. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – vsebuje ime, osnovni načrt in različico posodobitve za zbirko.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="updatefinder_suite_updatenotapplicabledefaultpath"></a>updatefinder_suite_updatenotapplicabledefaultpath

Posodobitev zbirke – prijavite se vsakič, ko posodobitev zbirke ni na voljo, ker niso vse aplikacije zbirke, ki so nameščene pod privzeto potjo. Zabeležimo različico osnovne vrstice in AppId paketa. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – vsebuje ime, osnovni načrt in različico posodobitve za zbirko.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="updatefinder_suite_updatenotapplicableversion"></a>updatefinder_suite_updatenotapplicableversion

Posodobitev zbirke – prijavite se vsakič, ko posodobitev zbirke ni na voljo, ker niso vse aplikacije zbirke, ki so nameščene pod privzeto potjo. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – vsebuje ime, osnovni načrt in različico posodobitve za zbirko.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="updatefinder_suite_updatenotoffered"></a>updatefinder_suite_updatenotoffered

Posodobitev zbirke – dnevnik se zabeleži vsakič, ko posodobitev zbirke ni na voljo zaradi velikosti zbirke, ki je večja od posameznih posodobitev. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ime zbirke.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="updatefinder_suite_updateoffered"></a>updatefinder_suite_updateoffered

Posodobitev zbirke – dnevnik se zabeleži vsakič, ko je na voljo posodobitev zbirke. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Payload** – vsebuje ime, osnovni načrt in različico posodobitve za zbirko.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="updatemanager_checkupdate"></a>updatemanager_checkupdate

Ta dogodek zabeleži število posodobitev, ki jih je odkrila Microsoftova autoupdate, medtem ko preverjate, ali so na voljo posodobitve. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje število razpoložljivih posodobitev, ki so na voljo.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="updatemanager_updatespending"></a>updatemanager_updatespending

Ta dogodek pomeni, da so posodobitve našli in čakajoče namestitve. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje oznako, ali se opravilo izvaja na glavni navoj in število čakajočih posodobitev.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="updatestatus_codesign"></a>UpdateStatus_Codesign

Ta dogodek sporoči stanje iz postopka preverjanja podpisa kode, ki ga Microsoft Update Assistant zažene po namestitvi posodobitev za odjemalske aplikacije. Ta dogodek uporabimo, da zagotovimo pridobivanje veljavnih paketov, s katerimi bodo nameščene aplikacije posodobljene na najnovejšo različico.

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppID** – identifikator za aplikacijo, ki se posodablja

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Error** – vse napake, do katerih je prišlo med postopkom preverjanja podpisa kode

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

- **Success** – označuje, ali je bilo preverjanje podpisa kode uspešno

- **UpdateID** – enolično prepozna uporabljeno posodobitev 

- **UpdateName** – ime posodobitve, ki je opisana v manifestu posodobitve

- **UpdatePkg** – ime uporabljenega paketa posodobitve

### <a name="urlutilities_getmauinfo"></a>urlutilities_getmauinfo

Ta dogodek sporoči napako, do katere je prišlo med dostopanjem do kompleta aplikacij programa Microsoft Auto Update (MAU). Ta dogodek je kritičen in se uporablja za preiskavo sporočene napake.

Zbrana so sledeča polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – vsebuje informacije o napaki, do katere je prišlo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo
   
### <a name="webservices_checkforsilentupdates"></a>webservices_checkforsilentupdates

Ta dogodek pomeni, da so bili najdeni tihi kandidati za posodabljanje. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje število najdenih posodobitev in ID aplikacije.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="webservices_deltaupdater"></a>webservices_deltaupdater

V tem dnevniku so na voljo interakcije med odjemalčevo kodo in funkcijami vrat, ki nadzorujejo, ali mora odjemalec omogočiti posodobitve za Delta. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje odgovor iz spletnih storitev in vrste Updater za uporabo.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="webservices_serviceaction"></a>webservices_serviceaction

Zabeležimo morebitne napake, ki so posledica nepričakovanega odgovora na WebService. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje podrobnosti o dejanjih, ki jih je treba potiskati iz spletnih storitev.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="webservices_serviceaction"></a>webservices_serviceaction

Zabeležimo morebitne napake, ki so posledica nepričakovanega odgovora na WebService. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje podrobnosti o dejanjih, ki jih je treba potiskati iz spletnih storitev.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo


### <a name="webservices_serviceresponse"></a>webservices_serviceresponse

Ta dogodek prijavi zahteve MAU Service, odzivni čas in napake. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ID zahteve, ime aplikacije, čas za odziv in/ali kodo stanja.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

    
### <a name="webservices_silentupdate"></a>webservices_silentupdate

Prijavimo zahteve za preverjanje veljavnosti» Force Update «pravil za uporabo, kar pomeni, da moramo sprejeti uporabnika iz gradnje N za izgradnjo N + 1 zaradi nekaj pomembnejših težav. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ID zahteve, ime aplikacije, čas za odziv in/ali kodo stanja.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="webservices_updatefiltering"></a>webservices_updatefiltering

Ta dogodek označuje filtriranje, ki je bilo izvedeno za seznam veljavnih posodobitev prek spletnih storitev. Ta dogodek uporabljamo, da zagotovimo pravilno delovanje blokiranja aplikacij, če je treba posodobitev blokirati.

Zbrana so naslednja polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku

- **AppversionLong** – različica programa

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – vsebuje informacije o številu blokiranih posodobitev prek spletnih storitev

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="webservices_webcontent"></a>webservices_webcontent

Prijavimo zahteve in odgovore, prejete v storitvi. Ta dogodek uporabljamo za zagotavljanje, da postopek posodabljanja deluje tako, kot je bilo pričakovano, in pomoč pri odpravljanju napak.
 
Zbrana so ta polja:

- **Aplikacija** – postopek prijave, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppVersionLong** – različica aplikacije

- **Channel** – ugodnost občinstva

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave.

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – ura prejemanja telemetrijo

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowTocheck** – ugodnost za preverjanje posodobitev

- **Nosilnost** – vsebuje ID klicatelja za spletne storitve.

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

### <a name="webservices_whatsnew"></a>webservices_whatsnew

Ta dogodek se sproži, ko Microsoft Auto Update (MAU) za ragistrirane aplikacije v spletnih storitvah izvede poizvedbe v funkciji »novosti«. Ta dogodek uporabljamo za določitev ustreznosti stanja funkcije »Novosti«. 

Zbrana so ta polja:

- **App** – postopek aplikacije, ki pošilja dogodek

- **AppInfo_Language** – jezik, v katerem se izvaja aplikacija v razdelku.

- **AppversionLong** – različica programa

- **Kanal** – ugodnost za občinstvo

- **Device_NetworkCountry** – država/regija naprave (ki temelji na naslovu IP)

- **DeviceID** – identifikator naprave

- **DeviceInfo_Model** – model strojne opreme naprave

- **DeviceInfo_NetworkType** – vrsta omrežja (Wi-Fi, žična, neznana)

- **DeviceInfo_OsBuild** – različica operacijskega sistema

- **Event_ReceivedTime** – čas, ko je bila prejeta telemetrija

- **EventInfo_Name** – ime telemetričnega dogodka, ki se zabeleži.

- **EventInfo_Time** – čas, ko se je dogodek v dnevniku zgodil 

- **HowToCheck** – kako preveriti nastavitev

- **Payload** – vsebuje informacije o številu aplikacij, ki se posodabljajo

- **PipelineInfo_ClientCountry** – država naprave (ki temelji na naslovu IP)

- **PipelineInfo_ClientIp** – prve 3 oktete naslova IP

- **ID** seje – identifikator za sejo

## <a name="onenote-sync-events"></a>Dogodki sinhronizacije za OneNote

### <a name="officeonenotestoragenotebooksyncresult"></a>Office.OneNote.Storage.NotebookSyncResult
 
Ta dogodek zabeleži rezultat sinhronizacije zvezka. Uporablja se za prikaz števila enoličnih ciljev sinhronizacije pri izračunavanju rezultata sinhronizacije za OneNote.
 
Zbrana so naslednja polja

- **CachedError_Code** – oštevilčena ali alfanumerična koda, ki se uporablja za določanje narave predpomnjene napake, in/ali razloga, zakaj se je pojavila

- **CachedError_Description** – opis napake v predpomnilniku

- **CachedError_Tag** – določite, kje v kodi je shranjena predpomnjena napaka

- **CachedError_Type** – vrsta predpomnjene napake, na primer Win32Error itd.

- **ExecutionTime** – čas v milisekundah za repliciranje zvezka

- **Gosid** – globalni ID prostora za predmete

- **IdentityType** – vrsta identitete, npr. Windows Live, ID org ipd.

- **InitialReplicationInSession** – ali je to replikacija prva replikacija zvezka po odprtju ali ne

- **IsBackgroundSync** – ali je to sinhroniziranje ozadja ali ne

- **IsCachedErrorSuppressed** – je predpomnjena napaka, ki jo je mogoče zatreti ali ne

- **IsCachedErrorUnexpected** – je predpomnjena napaka, ki je nepričakovana ali ne

- **IsNotebookErrorSuppressed** – je napaka sinhronizacije na ravni zvezka ukinjena ali ne

- **IsNotebookErrorUnexpected** – je napaka sinhronizacije na ravni zvezka nepričakovana ali ne

- **IsSectionErrorSuppressed** – ali je napaka sinhronizacije odseka ukinjena ali ne

- **IsSectionErrorUnexpected** – je napaka sinhronizacije odseka nepričakovana ali ne

- **IsUsingRealtimeSync** – je sinhronizacija zvezka z moderno vsebino strani sinhronizirana ali ne

- **LastAttemptedSync** – časovni žig, ko je bil zvezek poskusil sinhronizirati nazadnje

- **LastBackgroundSync** – časovni žig, ko je bil izveden zadnji sinhronizacijo v ozadju

- **LastNotebookViewedDate** – datum, ko je bil zvezek nazadnje gledan

- **LastSuccessfulSync** – časovni žig, ko je bil zvezek uspešno sinhroniziran

- **NeedToRestartBecauseOfInconsistencies** – ali mora biti sinhronizacija znova zagnana zaradi neskladij ali ne

- **NotebookErrorCode** – koda napake sinhronizacije na ravni zvezek, ki je shranjena v prostoru zvezek Graph

- **NotebookId** – ID zvezka

- **NotebookType** – vrsta zvezka

- **ReplicatingAgainBecauseOfInconsistencies** – ali ponovni zagon sinhronizacije zaradi neskladij ali ne

- **SectionError_Code** – oštevilčena ali alfanumerična koda, ki se uporablja za določanje narave napake sinhronizacije odseka in/ali razloga, zakaj se je pojavila

- **SectionError_Description** – opis napake sinhronizacije odseka

- **SectionError_Tag** – določite mesto, kjer v kodi je sporočilo o napaki sinhronizacije odseka

- **SectionError_Type** – vrsta napake sinhronizacije odseka, npr. Win32Error itd.

- **Uspeh** – ali je sinhronizacija zvezka uspešna ali ne

- **SyncDestinationType** – vrsta ciljne sinhronizacije, tj. OneDrive ali SharePoint online

- **SyncId** – številka, ki je enolična za vsako sinhronizacijo zvezka

- **SyncWasFirstInSession** – ali je sinhronizirana prva sinhronizacija v trenutni seji

- **SyncWasUserInitiated** – ali je ta uporabnik za sinhronizacijo zagnal ali ne

- **TenantId** – ID najemnika za SharePoint

- **TimeSinceLastAttemptedSync** – ura od zadnjega poskusa sinhronizacije zvezka

- **TimeSinceLastSuccessfulSync** – ura odkar je bila nazadnje uspešna sinhronizacija zvezka

### <a name="officeonenotestoragerealtimewebsocketsessioninfo"></a>Office.OneNote.Storage.RealTime.WebSocketSessionInfo
 
Ta dogodek prijavi rezultate sinhronizacije za sinhronizacijo spletne vtičnice za tako vsebino programa OneNote moderne sinhronizacije Uporablja se za prikaz števila enoličnih ciljev sinhronizacije pri izračunavanju rezultata sinhronizacije za OneNote. Uporablja se tudi za sodobno delovanje nadzorne plošče za sinhronizacijo programa OneNote.
 
Zbrana so sledeča polja:
 
- **Vzrok** za CloseReason – bližnjica, npr. neobičajno zapiranje itd.

- **DataIsFreshCount** – število uspešnih zahtev za vlečenje v srečanju

- **ID** seje DeviceSessionId – naprave

- **DownloadCount** – število prenosov v seji »samopostrežna vtičnica«

- **Napaka** – je v osnovi Exception_Type + Exception_Description + Exception_Code + Exception_Tag

- **Exception_Code** – oštevilčena ali alfanumerična koda, ki se uporablja za določanje narave napake, in/ali razloga, zakaj se je pojavila

- **Exception_Description** – opis napake

- **Exception_Tag** – določite, kje v kodi je sporočilo o napaki

- **Exception_Type** – vrsta napake, npr. Win32Error itd.

- **FirstUpdateSize** – dolžina sporočila »prvo posodabljanje«

- **HasError** – ne glede na to, ali je prišlo do napake med sejo 

- **IsEducationNotebook** – je trenutni zvezek za izobraževanje za zvezek ali ne

- **IsHierarchyResource** – je trenutni vir stran ali odsek

- **NotebookId** – ID zvezka za OneNote

- **OperationWithError** – v kateri operaciji je prišlo do napake, na primer na spletnem mestu. Zaprite, v storitvi. Odprite ipd.

- **ResourceId** – stran v OneNotu ali ID vira odseka

- **ID** odseka SectionId – OneNote

- **ID** seje ServerSessionId, ki se uporablja za korelacijo zahteve za OneNote.com

- **SessionDurationInMs** – trajanje seje v milisekundah

- **TenantId** – ID najemnika za SharePoint

- **TimeToFirstUpdateInMs** -čas v milisekundah, ki so bile izvedene za prejem prve posodobitve na strani strežnika, ko je vzpostavljena seja ponudnika

- **UploadAckCount** – število priznanj za prenos v seji v storitvi

- **WebUrl** – podrgnil spletni naslov 

### <a name="officeonenotestoragesectionsyncresult"></a>Office.OneNote.Storage.SectionSyncResult
 
V tem dnevniku je rezultat sinhronizacije odseka. Uporablja se za prikaz števila enoličnih ciljev sinhronizacije pri izračunavanju rezultata sinhronizacije za OneNote. Uporablja se tudi za sodobno delovanje nadzorne plošče za sinhronizacijo programa OneNote.
 
Zbrana so sledeča polja

- **Error_Code** – oštevilčena ali alfanumerična koda, ki se uporablja za določanje narave napake, in/ali razloga, zakaj se je pojavila

- **Error_Description** – opis napake

- **Error_Tag** – določite, kje v kodi je sporočilo o napaki

- **Error_Type** – vrsta napake, npr. Win32Error itd.

- **ErrorLast** – koda napake zadnjega videne napake 

- **ExecutionTime** – čas v milisekundah za repliciranje odseka

- **InitialReplicationInSession** – ali je to replikacija prva replikacija zvezka po odprtju ali ne

- **IsAttachedViaShortcut** – je odsek, ki je pripet prek bližnjice ali ne

- **IsBackgroundSync** – ali je to sinhroniziranje ozadja ali ne

- **IsEncrypted** – ali je odsek šifriran ali ne

- **IsErrorSuppressed** – ali je ta napaka ukinjena ali ne 

- **IsErrorTransient** – ali je ta napaka prehodna ali ne

- **IsErrorUnexpected** – ali je ta napaka nepričakovana ali ne

- **IsUsingRealtimeSync** – je razdelek sinhroniziranje z moderno vsebino strani sinhroniziranje ali ne

- **NotebookId** – ID zvezka

- **NotebookPath** – počistili URL zvezka

- **SectionPath** – obdelani URL odseka »zavarovanje poklicne odgovornosti«

- **SectionReplicatingIsOutbound** – ali je to replikacija odhodna replikacija ali ne

- **SectionReplicatingIsSameIdentity** – ali je to replikacija na podlagi enake identitete datoteke ali ne

- **SectionResourceId** – ID vira razdelka v OneNotu

- **Success** – ali je odsek uspešen ali ne

- **SyncDestinationType** – vrsta ciljne sinhronizacije, tj. OneDrive ali SharePoint online

- **SyncId** – številka, ki je enolična za vsako sinhronizacijo razdelka

- **SyncWasFirstInSession** – ali je sinhronizirana prva sinhronizacija v trenutni seji

- **SyncWasUserInitiated** – ali je ta uporabnik za sinhronizacijo zagnal ali ne

- **TenantId** – ID najemnika za SharePoint

- **ID** razdelka UnmappedGosid pred uporabo GUID-a preslikave


### <a name="officeonenotestoragesyncscore"></a>Office.OneNote.Storage.SyncScore
 
Ta dogodek zabeleži vse negativne faktorje v izkušnji sinhronizacije, ki so vidni za uporabnike. Uporablja se za izračun rezultata sinhronizacije za OneNote, ki je kritična metrika za ovrednotenje izkušenj s sinhronizacijo uporabnikov programa OneNote.
 
Zbrana so sledeča polja

- **AutoShowSyncStatus** – ne glede na to, ali je stanje sinhronizacije samodejno prikazano ali ne

- **Vzrok** – kaj je povzročilo, da so strani programa OneNote premaknjene v napačno postavljene odseke

- **Kontekst** – enum categorizes, ki jih uporabnik poskuša narediti, npr. preimenuje razdelek, znova odpre zvezek itd.

- **Error_Code** – oštevilčena ali alfanumerična koda, ki se uporablja za določanje narave napake, in/ali razloga, zakaj se je pojavila

- **Error_Description** – opis napake

- **Error_Tag** – določite, kje v kodi je sporočilo o napaki

- **Error_Type** – vrsta napake, npr. Win32Error itd.

- **ErrorText** – besedilo napake, ki je prikazano v uporabniškem vmesniku

- **Razlaga** – razloži, katere vrste čakajočih odhodnih sprememb, ki jih je treba premakniti v napačno postavljene odseke

- **fishbowlType** vrsta Fishbowl, npr. stran Fishbowl, oddelek Fishbowl itd.

- **IDS** – celo število identifikator za besedilo, ki je prikazano v uporabniškem vmesniku

- **idsFishbowl** – celo število identifikator za napako »Fishbowl«, ki je prikazana v uporabniškem vmesniku

- **IsUsingRealtimeHierarchySync** – uporablja moderno hierarhično sinhronizacijo ali ne

- **NotebookId** – ID zvezka

- **PageSyncUIState** – niz stanja sinhronizacije strani, na primer UpToDate, Syncing, SaveOffline, SyncError itd. 

- **ServerGosid** – ID vira za novo ustvarjeno stran spora

- **Vir** – v enum je navedeno, kateri dogodek je sprožil UI, tj. ustvaril novo RedX sliko, napako sinhronizacije v uporabniškem vmesniku za sinhronizacijo, prikazano pogovorno okno napake itd.

### <a name="onenoteappprovisioningmovelocalnotebooktoonlinenotebookfailed"></a>OneNote.App.Omogočanje uporabe.MoveLocalNotebookToOnlineNotebookFailed
 
Ta dogodek se zabeleži ob selitvi lokalnega zvezka na pogon.  Ta primer je specifičen za enotno prijavo uporabnika. Ko se uporabnik prijavi, je njihov lokalni zvezek prenesen v OneDrive shrambo storitve. 
 
Zbrana so sledeča polja:
 
- **ErrorMsg** – sporočilo o napaki, ki ustreza napaki.

### <a name="onenotestorageconnectivitychanged"></a>OneNote.Storage.ConnectivityChanged

Dnevnike dogodkov, če ima uporabnik internetno povezljivost ali ne. S tem se lahko poveže druge metrike učinkovitosti delovanja zdravja, tako da prezremo dogodke, do katerih pride, ko uporabnik nima internetne povezljivosti, saj ne pričakujemo, da bo zakasnitev vaše storitve sprejemljiva brez internetne povezljivosti. Na ta način lahko izračunate natančno število sej za naše meritve v različnih rezinah strank (na najemnika, na sektor). Prav tako lahko z njim filtrirate poročila o napakah, saj so na voljo številne napake pri sinhronizaciji, za katere pričakujemo, da bodo prišlo brez povezljivosti z omrežjem, vendar je to naloga.

Če teh podatkov ne prejmemo, ne bomo imeli natančnega nadzora nad delovanjem naših izdelkov ali ugotovili, ali pričakujete, da bo prišlo do napak, ki jih je izkusil uporabnik.

Zbrana so sledeča polja:

- **InternetConnectivityNowAvailable** – če je stanje povezljivosti spremenjeno, tako da je zdaj Internet

### <a name="onenotestoragelegacyinboundlatency"></a>OneNote.Storage.LegacyInboundLatency

Kritični signal, ki se uporablja za spremljanje delovanja dohodnih postopkov sinhronizacije, ki neposredno komunicirajo s SharePointovim paketom, vključno s korelacijo podatkov, ki nam omogočajo nadzor in preiskovanje delovanja prenosa podatkov v našo storitev. Ta signal je namenjen le najslabšem izvajanju prenosa v zadnjih 300 sekundah (število sekund, ki jih je mogoče konfigurirati z Microsoftom, odvisno od zmogljivosti in stanja storitve).

To se uporablja za zagotavljanje stanja storitev tako, da nam omogoči, da si ogledate, kateri najemniki doživljajo nesprejemljivo počasno dohodno podatkov za našo storitev, informacije o podatkih, ki jih prenašajo, ko so doživeli počasno dohodno in kako razširjena je v najemniku, ki je imel težave z zakasnitvijo. Uporablja se tudi za poročanje o stanju storitve in učinkovitosti delovanja v vseh naših strankah, s katerimi lahko izmerite trende v času in opozorite na težave, ki se samodejno uporabljajo za ublažitev strojništva. Če teh podatkov ne bomo imeli, nam prepreči, da bi zagotovili ustrezno učinkovitost prenosa, ko uporabnik sinhronizira spremembe iz SharePointa v svoj računalnik.

Zbrana so sledeča polja: 

- **IsEducationNotebook** – logična vrednost, ki označuje, ali je zvezek izobraževalni zvezek

- **NotebookId** – ID zvezka, v katerem je ta prenos vključen

- **TimeToConfirmSyncedWithServerInMs** – čas v milisekundah, v katerem je bilo izvedeno nalaganje

### <a name="onenotestoragelegacyoutboundlatency"></a>OneNote.Storage.LegacyOutboundLatency

Kritični signal, ki se uporablja za spremljanje delovanja dohodnih postopkov sinhronizacije, ki neposredno komunicirajo s SharePointovim paketom, vključno s korelacijo podatkov, ki nam omogočajo nadzor in preiskovanje delovanja prenosa podatkov v našo storitev. Ta signal je namenjen le najslabšem izvajanju prenosa v zadnjih 300 sekundah (število sekund, ki jih je mogoče konfigurirati z Microsoftom, odvisno od zmogljivosti in stanja storitve).

To se uporablja za zagotavljanje stanja storitev tako, da nam omogoči, da si ogledate, kateri najemniki doživljajo nesprejemljivo počasno dohodno podatkov za našo storitev, informacije o podatkih, ki jih prenašajo, ko so doživeli počasno dohodno in kako razširjena je v najemniku, ki je imel težave z zakasnitvijo. Uporablja se tudi za poročanje o stanju storitve in učinkovitosti delovanja v vseh naših strankah, s katerimi lahko izmerite trende v času in opozorite na težave, ki se samodejno uporabljajo za ublažitev strojništva. Če teh podatkov ne bomo imeli, nam to prepreči, da bi zagotovili ustrezno učinkovitost delovanja, ko bodo uporabniki sinhronizirali spremembe v SharePointu. 

Zbrana so sledeča polja: 

- **IsEducationNotebook** – logična vrednost, ki označuje, ali je zvezek izobraževalni zvezek

- **NotebookId** – ID zvezka, v katerem je ta prenos vključen

- **TimeToConfirmSyncedWithServerInMs** – čas v milisekundah, v katerem je bilo izvedeno nalaganje

### <a name="onenotestoragerealtimefiledataobjectdownload"></a>OneNote.Storage.RealTime.FileDataObjectDownload 

Kritični signal, ki se uporablja za spremljanje učinkovitosti delovanja, ko uporabnik usmeri podatkovna datoteka (tj. vdelana datoteka ali slika), ki je prenesena neposredno iz naše storitve, in ne kot del operacije sinhroniziranja na strani, odseku ali zvezku. Ta signal je namenjen le najslabšem izvajanju prenosa v zadnjih 300 sekundah (število sekund, ki jih je mogoče konfigurirati z Microsoftom, odvisno od zmogljivosti in stanja storitve).

To se uporablja za zagotavljanje stanja storitve in zmogljivosti, tako da si lahko ogledate, kateri najemniki so nesprejemljivo počasna prenos podatkov iz naših storitev, in kako razširjena je v najemniku, ki je težava z zakasnitvijo, ter poroča o našem delu v določenem časovnem obdobju in nam tako omogoči, da merimo trende učinkovitosti delovanja storitve. Če opazite nesprejemljivo zakasnitev za predmet datoteke, bomo te podatke uporabili tudi za to, da bodo lahko sodelovali z drugimi signali iz odjemalca in storitve glede predmeta, ki bodo izboljšali postopek prenosa. Podatke smo razdelili tudi na podlagi razširitve predmeta datoteke, saj imamo različna pričakovanja glede na to, ali je datoteka predstavljena v vrstici z našim platnom (npr. slika) ali pa je datoteka, ki ni v vrstici (kot je besedilni dokument). Če teh podatkov ne prejmemo, nam prepreči nadzor učinkovitosti teh prenosov.

Zbrana so sledeča polja: 

- **FileSizeInBytes** – velikost datoteke, ki jo prenesete v bajtih 

- **IsImage** – logična vrednost, ki določa, ali je datoteka, ki jo prenesete, pripona, ki se ujema z vnaprej določenim seznamom pogostih oblik zapisa slike (.bmp, .emf, gif, .jpe, jpeg, jpg, png), ki je prikazana v vrstici v platnu

- **TimeToDownload** – koliko časa je trajalo, da je FDO uspešno prenesla iz shrambe BLOB v napravo 

### <a name="onenotestoragerealtimewebsocketdownload"></a>OneNote.Storage.RealTime.WebSocketDownload

Kritični signal, ki se uporablja za spremljanje delovanja dohodnih sinhronizacijskih operacij, vključno s korelacijo podatkov, ki nam omogočajo nadzor in preiskovanje delovanja prenosa podatkov iz naših storitev (onenote.com). Ta signal je namenjen le najslabšem izvajanju prenosa v zadnjih 300 sekundah (število sekund, ki jih je mogoče konfigurirati z Microsoftom, odvisno od zmogljivosti in stanja storitve).

To se uporablja za zagotavljanje stanja storitev tako, da nam omogoči, da si ogledate, kateri najemniki doživljajo nesprejemljivo počasno dohodno podatkov za našo storitev, informacije o podatkih, ki jih prenašajo, ko so doživeli počasno dohodno in kako razširjena je v najemniku, ki je imel težave z zakasnitvijo. Uporablja se tudi za poročanje o stanju storitve in učinkovitosti delovanja v vseh naših strankah, s katerimi lahko izmerite trende v času in opozorite na težave, ki se samodejno uporabljajo za ublažitev strojništva. 

Če opazite nesprejemljivo zakasnitev za odsek ali zvezek, bomo te podatke uporabili tudi za to, da bodo lahko sodelovali z drugimi signali v odjemalcu in storitvi v zvezi z istim dokumentom, da bodo prepoznali regresivne zmogljivosti odjemalca, ki nam bodo omogočale Dostavitev bolj zmogljive storitve.

Če teh podatkov ne prejmemo, ne bomo mogli nadzorovati učinkovitosti delovanja tega vidika naših storitev ali pa bo vpliv neželenih sprememb, ki so na voljo, morda zaradi uporabe ali drugih dejavnikov.

Zbrana so sledeča polja:

- **DeviceSessionId** – ID seje naprave

- **IsEducationNotebook** – logična vrednost, ki označuje, ali je zvezek izobraževalni zvezek

- **IsHierarchyResource** – logična vrednost, ki označuje, ali je vir hierarhični vir

- **NotebookId** – ID zvezka, v katerem je ta prenos vključen

- **ResourceId** – ID vira, ki ga nalagamo

- **SectionId** – ID odseka, za katerega je ta prenos vključen

- **ServerSessionId** – ID seje strežnika, ki je ta prenos del programa

- **TimeToConfirmSyncedWithServerInMs** – čas v milisekundah med uporabnikom, ki se premikajo do strani, in sklad replikacije, ki potrjuje, da je stran sinhronizirana s strežnikom.

- **TimeToFirstUpdateInMs** – čas v milisekundah med mehanizmom sinhronizacije, ki se začne z dohodno replikacijo strani, in s tem postopkom replikacije, ki je dosegel sinhronizacijo s stanjem strežnika.

### <a name="onenotestoragerealtimewebsocketupload"></a>OneNote.Storage.RealTime.WebSocketUpload

Kritični signal, ki se uporablja za spremljanje učinkovitosti delovanja odhodne sinhronizacije, vključno s korelacijo podatkov, ki nam omogočajo nadzor in preiskovanje delovanja prenosa podatkov v našo storitev (onenote.com)

To se uporablja za zagotavljanje stanja storitev tako, da nam omogoči, da si ogledate, kateri najemniki doživljajo nesprejemljivo počasno dohodno podatkov za našo storitev, informacije o podatkih, ki jih prenašajo, ko so doživeli počasno dohodno in kako razširjena je v najemniku, ki je imel težave z zakasnitvijo. Uporablja se tudi za poročanje o stanju storitve in učinkovitosti delovanja v vseh naših strankah, s katerimi lahko izmerite trende v času in opozorite na težave, ki se samodejno uporabljajo za ublažitev strojništva. Te podatke bomo uporabili tudi za spremljanje vpliva in učinkovitosti izboljšav, ki jih naredimo našim strankam in storitvam. 

Če opazite nesprejemljivo zakasnitev za odsek ali zvezek, bomo te podatke uporabili tudi za to, da bodo lahko sodelovali z drugimi signali v odjemalcu in storitvi v zvezi z istim dokumentom, da bodo prepoznali regresivne zmogljivosti, ki nam bodo omogočale zagotavljanje bolj zmogljive izkušnje.

Če teh podatkov ne prejmemo, ne bomo mogli nadzorovati učinkovitosti delovanja tega vidika naših storitev ali pa bo vpliv neželenih sprememb, ki so na voljo, morda zaradi uporabe ali drugih dejavnikov.

Zbrana so sledeča polja: 

- **DeviceSessionId** – ID seje naprave

- **IsEducationNotebook** – logična vrednost, ki označuje, ali je zvezek izobraževalni zvezek

- **IsHierarchyResource** – logična vrednost, ki označuje, ali je vir hierarhični vir

- **IsWorstTime** – logična vrednost, ki označuje, ali je čas rednega prenosa, ali najslabšega časa, ki smo ga videli v tem odjemalcu v zadnjih 300 sekundah (število sekund je mogoče konfigurirati z Microsoftom, odvisno od učinkovitosti delovanja in pogoja storitve).

- **NotebookId** – ID zvezka, v katerem je ta prenos vključen

- **RecommendedPutIntervalInMs** – čas, ko je storitev posredovana odjemalcu, kot je priporočeno obdobje »vstavi«

- **ResourceId** – ID vira, ki ga nalagamo

- **SectionId** – ID odseka, za katerega je ta prenos vključen

- **SenderRequestId** – ID pošiljatelja, ki izvaja prenos

- **ServerSessionId** – ID seje strežnika, ki je ta prenos del programa

- **UploadNonSuspendedTimeInMs** – čas v milisekundah, v katerem je bilo izvedeno nalaganje, razen časa, ko je bila aplikacija prekinjena

- **UploadTimeInMs** – čas v milisekundah, v katerem je bilo dejansko izvedeno nalaganje

- **WaitTimeInMs** – čas v milisekundah med zahtevano nalaganje in prenosom, ki se začne

- **WebUrl** – WebUrl prenosa (prijavljeno kot PiiWz)

### <a name="onenotestoragesynchealth"></a>OneNote.Storage.SyncHealth

Kritični signal, s katerim lahko spremljate napake in izjeme, ki so se zgodile znotraj sklada za sinhronizacijo v odjemalcu za OneNote, s katerim lahko nadzorujete in omilimo te nepričakovane pogoje.

To se uporablja za zagotavljanje stanja storitev tako, da si lahko ogledate poročila o napakah odjemalcev, ki so na voljo v realnem času, kar nam omogoča odziv na težave pri sinhronizaciji, ko se pojavijo. Uporablja se tudi za določanje, kako razširjena je težava, in kako huda je navzkrižna referenca z oznako napake z odjemalčevo kodo, da prepoznate izvor napake. Te podatke združimo tudi tako, da dobimo informacije o učinkovitosti delovanja skozi čas ter vpliva in učinkovitosti izboljšav, ki jih naredimo našim strankam in storitvam. Če teh podatkov nimamo, ne bomo mogli proaktivno odgovoriti na pogoje napake v naši sinhronizacijski storitvi, ne da bi se med seboj stopnjevala stranka.

Zbrana so sledeča polja: 

- **Storitev** – storitev sinhronizacije, ki jo je stranka uporabljala, ko je prišlo do napake (podedovana ali sodobna sinhronizacija)

- **Oznaka** – oznaka (prepoznavna vrednost), ki predstavlja napako, ki jo je stranka naletela med postopkom sinhronizacije.

### <a name="onenotesynccreatenotebookfailed"></a>OneNote.Sync.CreateNotebookFailed
 
Ta dogodek se zabeleži, ko ustvarjanje zvezka ne uspe.  
 
Zbrana so sledeča polja:
 
- **NetworkConnection** – prijavi vrsto povezave, ki jo trenutno uporablja naprava, npr. Wi-Fi, brez povezave, 3G 

- **ServerType** – prijavi vrsto strežnika, kjer naj bo ustvarjen zvezek.

### <a name="onenotesyncfirstrunerror"></a>OneNote.Sync.FirstRunError
 
Ta dogodek se zabeleži pri sinhronizaciji hitrih zapiskov za uporabnika med prvo izkušnjo, ki jo izvaja v napravi.  To je specifično za scenarij prvega zagona.
 
Zbrana so sledeča polja:
 
- **NetworkConnection** – prijavi vrsto povezave, ki jo trenutno uporablja naprava, npr. Wi-Fi, brez povezave, 3G

- **ServerType** – prijavi vrsto strežnika, v kateri je ustvarjen zvezek za hitri zapiske.

## <a name="services-configuration-events"></a>Dogodki za konfiguracijo storitev

Konfiguracija storitev ne zbira potrebnih dogodkov podatkov storitve.

## <a name="telemetry-events"></a>Dogodki telemetrije

### <a name="office_firstrun_apple_telemetryoptin"></a>Office_FirstRun_Apple_TelemetryOptIn

Ta dogodek zbiramo za Officeove aplikacije, ki se izvajajo na platformah Apple. Ta dogodek se uporablja za nadzor stanja pretoka telemetrije, ki ste ga dovolili, pri izkušnji prvega zagona. Zbiramo kodo, ki označuje vrsto možnosti zbirke diagnostičnih podatkov, ki jo je izbral uporabnik.

Zbrana so naslednja polja:

 - **Data_EventId** – koda, ki označuje nastavitve za diagnostično zbirko podatkov, ki jo je izbral uporabnik.

### <a name="officesystemgracefulexitgracefulappexitdesktop"></a>Office.System.GracefulExit.GracefulAppExitDesktop

Dogodek sproži elegantna zaustavitev aplikacije v primeru Officeovih odjemalskih aplikacij, kot so med drugim Word, Excel, PowerPoint in Outlook. Z elegantno zaustavitvijo merimo stanje Officeovih odjemalcev. Gre za ključni poslovni signal, ki ga Officeovi inženirji uporabljajo za zagotavljanje stabilnosti izdelka.

Zbrana so naslednja polja:

- **AppBuild** – identifikator delovne različice za vplivani proces.
- **AppMajor** – identifikator glavne različice za vplivani proces.
- **AppMinor** – identifikator manjše različice za vplivani proces.
- **AppRevision** – identifikator delovne različice za vplivani proces.
- **BootCompleted** – ali je Officeov postopek dokončal zagon.
- **DetectionTime** – čas, ko je bil zaznan nepričakovani izhod.
- **EcsETag** – identifikator preskusa za proces.
- **HasEdit** – ali je bilo med Officeovim postopkom v teku urejanje dokumenta.
- **HasOpen** – ali je bil dokument odprt med Officeovim postopkom.
- **InstallMethod** – ali je bila trenutna gradnja Officea nadgrajena iz, povrnjena v prejšnje stanje oziroma sveža namestitev
- **OfficeUILang** – jezik Officeovega postopka.
- **PreviousBuild** – prejšnja nameščena delovna različica.
- **SafeMode** – ali je bil Officeov postopek v varnem načinu.
- **SessionId** – enolični identifikator postopka.
- **SessionInitTime** – čas, ko se je začel vplivani proces.

### <a name="officesystemidentitychanged"></a>Office.System.IdentityChanged

Podatki o identiteti uporabnika, zahtevani za izpolnjevanje zahtev za zahtevo podatkov.

Zbrana so sledeča polja:

  - **IdentityChanged** – ima vedno vrednost »True«. Identiteta se je spremenila

  - **TimerDetectedChange** – ali je spremembo zaznal časovno usklajeni ping

### <a name="officesystemprivacyfallbacktosettingsstore"></a>Office.System.PrivacyFallbackToSettingsStore

Se uporablja za določanje, ali je prišlo do napak pri branju nastavitev zasebnosti uporabnika iz gostujoče shrambe.

Zbrana so sledeča polja:

  - **Oznaka –** oznaka kode, ki ponazarja, katera nastavitev je bila podana nazaj v shrambo nastavitev

### <a name="officesystemsessiondatao365"></a>Office.System.SessionDataO365

Metapodatki, zahtevani za osamitev ponovnega prikaza napake.

Zbrana so sledeča polja:

  - **AppId** – identifikator, na katerega se nanašajo ti podatki Officeove aplikacije

  - **ApplicationArchitecture** – za katero arhitekturo procesorja je zgrajen Office

  - **AppVersionBuild** – delovna različica Officeove aplikacije

  - **AppVersionMajor** – glavna različica Officeove aplikacije

  - **AppVersionMinor** – manjša različica Officeove aplikacije

  - **AppVersionUpdate** – delovna revizija Officeove aplikacije

  - **CollectorVersion** – identifikator različice za način zbiranja odjemalca

  - **DeviceHash** – enosmerno zgoščevanje identifikatorja za operacijski sistem

  - **DeviceName** ime naprave, v kateri je nameščen Office

  - **Domain** – domena, v kateri se izvaja Office

  - **IsCeip** – ali je bila namestitev Officea vključena v ukinjeni program za izboljšanje uporabniške izkušnje

  - **IsDebug** – ali je to graditev Officea za odpravljanje napak

  - **IsImmersive** – ali Officeova aplikacija predstavlja univerzalno ali potopno aplikacijo sistema Windows

  - **IsLaptop** – ali je naprava, v kateri je nameščen Office, prenosni računalnik

  - **IsMicrosoftInternal** – ali je uporabnik sistema Windows, ki izvaja Office, Microsoftov zaposleni

  - **IsO365** – ali je Officeova namestitev del ukinjenega programa za Outlook 365

  - **IsTablet** – ali je naprava, v kateri je nameščen Office, tablični računalnik

  - **IsTerminalServer** – trditev true/false za terminalskega strežniškega odjemalca

  - **MaxMemory** – največja količina pomnilnika RAM, ki je na voljo v napravi z nameščenim Officeom

  - **OsArchitecture** – arhitektura enote CPE operacijskega sistema, za katero je bil zgrajen Office

  - **OsVersionBuild** – delovna različica operacijskega sistema

  - **OsVersionMajor** – glavna različica operacijskega sistema

  - **OsVersionMinor** – manjša različica operacijskega sistema

  - **OsVersionUpdate** – delovna različica operacijskega sistema

  - **ProcessFileName** – izvedljivo ime za aplikacijo, ki se izvaja

  - **ProcessorArchitecture** – v kateri arhitekturi procesorja se izvaja Office

  - **ProcessorFrequency** – hitrost procesorja v napravah, v katerih se izvaja Office (v MHz)

  - **SessionStart** – čas začetka za Officeov proces, ki se izvaja

  - **UserName** – ime računa, v katerem se izvaja Office

### <a name="officesystemsystemhealthcoremetadata"></a>Office.System.SystemHealthCoreMetadata

Metapodatki, zahtevani za osamitev ponovnega prikaza napake.

Zbrana so sledeča polja:

  - **AppBuild** – delovna različica Officeove aplikacije

  - **AppBuildRevision** – delovna revizija Officeove aplikacije

  - **AppMajorVer** – glavna različica Officeove aplikacije

  - **AppMinorVer** – manjša različica Officeove aplikacije

  - **CID** – uporabljeni psevdonim za identiteto uporabnika

  - **CollectibleClassifications** – nabor klasifikacij podatkov, ki ga je mogoče zbrati

  - **CollectionTime** – čas, ko so bili zbrani metapodatki

  - **DeviceManufacturer** – izdelovalec naprave, v kateri se izvaja Office

  - **DeviceModel** – model naprave, v kateri se izvaja Office

  - **FirstRunTime** – čas, ko je bila Officeova aplikacija zagnana prvič

  - **IsClickToRunInstall** – ali je bila Officeova aplikacija zagnana s tehnologijo zagona s klikom

  - **IsDebug** – ali je to gradnja Officea za odpravljanje napak

  - **IsLabMachine** – ali se Office izvaja v Microsoftovem laboratoriju

  - **IsLaptop** – ali je naprava, v kateri je nameščen Office, prenosni računalnik

  - **IsMsftInternal** – ali je uporabnik sistema Windows, ki izvaja Office, Microsoftov zaposleni

  - **IsSubscription** – ali je Officeova aplikacija nameščena v sklopu naročniške licence

  - **IsTablet** – ali je naprava, v kateri je nameščen Office, tablični računalnik

  - **IsTerminalServer** – ali se Office izvaja v terminalskem strežniku

  - **MsoAppId** – identifikator, na katerega se nanašajo ti podatki Officeove aplikacije

  - **OfficeArchitectureText** – za katero arhitekturo procesorja je zgrajen Office

  - **OsBuild** – delovna različica operacijskega sistema

  - **OsBuildRevision** – revizija gradnje operacijskega sistema

  - **OSEnvironment** – identifikator za okolje, v katerem se izvaja Office

  - **OsMajorVer** – glavna različica operacijskega sistema

  - **OsMinorVer** – manjša različica operacijskega sistema

  - **OSVersionString** – različica operacijskega sistema kot niz

  - **ProcessorArchitecture** – v kateri arhitekturi procesorja se izvaja Office

  - **ProcessorCount** – število procesorjev v napravi, v kateri se izvaja Office

  - **ProcSpeedMHz** – hitrost procesorja v napravah, v katerih se izvaja Office (v MHz)

  - **RamMB** – količina pomnilnika RAM, ki je na voljo v napravi, v kateri se izvaja Office

  - **SqmUserId** – naključni identifikator za namestitev Officea

### <a name="officesystemsystemhealthdesktopsessionlifecycleandheartbeat"></a>Office.System.SystemHealthDesktopSessionLifecycleAndHeartbeat

Zagotavlja informacije o metriki stanja sistema.

Zbrana so sledeča polja:

  - **InstallMethod** – ali je bila trenutna gradnja Officea nadgrajena iz, povrnjena v prejšnje stanje oziroma sveža namestitev

  - **OfficeArchitectureText** – arhitektura Officeovega izdelka kot niz (na primer x86, krak).

  - **PreviousBuild** – različica Officea, na katero je bila ta graditev nadgrajena ali s katere je bila povrnjena na prejšnjo različico.

  - **State** – stanje, v katerega se je spremenila seja

  - **Time** – čas, ko se je spremenilo stanje seje

### <a name="officesystemsystemhealthessentialidentitycount"></a>Office.System.SystemHealthEssentialIdentityCount

Zbira število vpisanih identitet uporabnikov.

Zbrana so sledeča polja:

  - **AllIdentityCount** – število vseh identitet

  - **ValidIdentityCount** – število preverjenih identitet

### <a name="officesystemsystemhealthessentialmetadataallidentities"></a>Office.System.SystemHealthEssentialMetadataAllIdentities

Spremlja stanje računov, ki jih je Office prepoznal v tej temi. Dogodek se uporablja za osamitev napake za vrsto prijave računa, če je bila napaka specifična vrsti.

Zbrana so sledeča polja:

  - **CollectionTime** – čas, ko so bili zbrani podatki o identiteti.

  - **IdentityType** – vrsta preverjanja pristnosti ali računa

  - **IdentityUniqueId** – identifikator identitete, ki uporablja psevdonim

  - **IdentityUniqueIdHashed** – enosmerna zgostitev enoličnega ID-ja identitete

### <a name="officesystemsystemhealthmetadataapplicationadditional"></a>Office.System.SystemHealthMetadataApplicationAdditional

Metapodatki, zahtevani za osamitev ponovnega prikaza napake.

Zbrana so sledeča polja:

  - **Alias** – če uporabnik, ki uporablja Office, Microsoftov sodelavec, njegovo podjetje uporablja notranji vzdevek

  - **AppBuild** – delovna različica Officeove aplikacije

  - **AppBuildRevision** – delovna revizija Officeove aplikacije

  - **AppMajorVer** – glavna različica Officeove aplikacije

  - **AppMinorVer** – manjša različica Officeove aplikacije

  - **CID** – uporabljeni psevdonim za identiteto uporabnika

  - **CollectibleClassifications** – nabor klasifikacij podatkov, ki ga je mogoče zbrati

  - **DeviceManufacturer** – izdelovalec naprave, v kateri se izvaja Office

  - **DeviceModel** – model naprave, v kateri se izvaja Office

  - **DeviceProcessorModel** – model procesorja v napravi, v kateri se izvaja Office

  - **DigitizerInfo** – podatki o digitalizatorju, ki je priključen na napravo, v kateri se izvaja Office

  - **DomainName** – ime domene, kateri se je pridružil računalnik, v katerem se izvaja Office (če je domena na voljo)

  - **FirstRunTime** – čas, ko je bila Officeova aplikacija zagnana prvič

  - **HorizontalResolution** – vodoravna ločljivost zaslona

  - **IsDebug** – ali je to gradnja Officea za odpravljanje napak

  - **IsImmersive** – ali Officeova aplikacija predstavlja univerzalno ali potopno aplikacijo sistema Windows

  - **IsJoinedToDomain** – ali se je naprava, v kateri se izvaja Office, pridružila domeni

  - **IsLabMachine** – ali se Office izvaja v Microsoftovem laboratoriju

  - **IsLaptop** – ali je naprava, v kateri je nameščen Office, prenosni računalnik

  - **IsMsftInternal** – ali je uporabnik sistema Windows, ki izvaja Office, Microsoftov zaposleni

  - **IsOEMInstalled** – ali je Officeovo aplikacijo, ki se izvaja, namestil OEM

  - **IsRunAsAdmin** – ali se Officeova aplikacija izvaja v načinu skrbnika

  - **IsSubscription** – ali je Officeova aplikacija nameščena v sklopu naročniške licence

  - **MsoAppId** – identifikator, na katerega se nanašajo ti podatki Officeove aplikacije

  - **NumProcPhysCores** število fizičnih jeder v procesorju

  - **OfficeBuild** – delovna različica Officeovih knjižnic v skupni rabi

  - **OfficeBuildRevision** – različica delovne revizije Officeovih knjižnic v skupni rabi

  - **OfficeMajorVer** – glavna različica Officeovih knjižnic v skupni rabi

  - **OfficeMinorVer** – manjša različica Officeovih knjižnic v skupni rabi

  - **OsBuild** – delovna različica operacijskega sistema

  - **OsBuildRevision** – revizija gradnje operacijskega sistema

  - **OsMajorVer** – glavna različica operacijskega sistema

  - **OsMinorVer** – manjša različica operacijskega sistema

  - **PowerPlatformRole** – identifikator za prednostno vlogo računalnika OEM za napravo, v kateri se izvaja Office

  - **ProcessFileName** – izvedljivo ime za aplikacijo, ki se izvaja

  - **ProcessorCount** – število procesorjev v napravi, v kateri se izvaja Office

  - **RamMB** – količina pomnilnika RAM, ki je na voljo v napravi, v kateri se izvaja Office

  - **SqmUserId** – naključni identifikator za namestitev Officea

  - **StudyId** – identifikator za preučevanje kakovosti metrike za programsko opremo

  - **VerticalResolution** – navpična ločljivost zaslona

  - **WinUserActType** – ali je uporabnik sistema Windows, ki izvaja Office, lokalni skrbnik, zahtevni uporabnik ali običajni uporabnik

### <a name="officesystemsystemhealthmetadataapplicationandlanguage"></a>Office.System.SystemHealthMetadataApplicationAndLanguage

Metapodatki, zahtevani za osamitev ponovnega prikaza napake.

Zbrana so sledeča polja:

  - **AppBuild** – delovna različica Officeove aplikacije

  - **AppBuildRevision** – delovna revizija Officeove aplikacije

  - **AppMajorVer** – glavna različica Officeove aplikacije

  - **AppMinorVer** – manjša različica Officeove aplikacije

  - **AppState** – identifikator stanja Officeove aplikacije

  - **Click2RunPackageVersionBuild** – delovna različica namestitvenega paketa s tehnologijo zagona s klikom

  - **Click2RunPackageVersionMajor** – glavna različica namestitvenega paketa s tehnologijo zagona s klikom

  - **Click2RunPackageVersionMinor** – manjša različica namestitvenega paketa s tehnologijo zagona s klikom

  - **Click2RunPackageVersionRevision** – revizija gradnje namestitvenega paketa s tehnologijo zagona s klikom

  - **DistributionChannel** – distribucijski kanal za Office

  - **InstallType** – identifikator za način namestitve Officea

  - **IsClickToRunInstall** – ali je bila Officeova aplikacija zagnana s tehnologijo zagona s klikom

  - **IsDebug** – ali je to gradnja Officea za odpravljanje napak

  - **IsImmersive** – ali Officeova aplikacija predstavlja univerzalno ali potopno aplikacijo sistema Windows

  - **IsMsftInternal** – ali je uporabnik sistema Windows, ki izvaja Office, Microsoftov zaposleni

  - **IsOEMInstalled** – ali je Officeovo aplikacijo, ki se izvaja, namestil OEM

  - **IsRunAsAdmin** – ali se Officeova aplikacija izvaja v načinu skrbnika

  - **IsSubscription** – ali je Officeova aplikacija nameščena v sklopu naročniške licence

  - **MsoAppId** – identifikator, na katerega se nanašajo ti podatki Officeove aplikacije

  - **OfficeArchitectureText** – za katero arhitekturo procesorja je zgrajen Office

  - **OfficeBuild** – delovna različica Officeovih knjižnic v skupni rabi

  - **OfficeBuildRevision** – različica delovne revizije Officeovih knjižnic v skupni rabi

  - **OfficeMajorVer** – glavna različica Officeovih knjižnic v skupni rabi

  - **OfficeMinorVer** – manjša različica Officeovih knjižnic v skupni rabi

  - **OfficeMuiCount** – število nameščenih Officeovih jezikovnih paketov

  - **OfficeSkuLanguage** – nameščeni jezik SKU

  - **OfficeSkuLanguageTag** – nameščeni jezik SKU

  - **OfficeUiLang** – jezik uporabniškega vmesnika za Officeovo aplikacijo

  - **OfficeUiLangTag** – jezik uporabniškega vmesnika za Officeovo aplikacijo

  - **ProcessFileName** – izvedljivo ime za aplikacijo, ki se izvaja

  - **SqmAppId** – identifikator, na katerega se nanašajo ti podatki Officeove aplikacije

### <a name="officesystemsystemhealthmetadatadelayedlogin"></a>Office.System.SystemHealthMetadataDelayedLogin

Podatki o identiteti uporabnika, zahtevani za izpolnjevanje zahtev za zahtevo podatkov.

Zbrana so sledeča polja:

  - **CID** – uporabljeni psevdonim za identiteto uporabnika

### <a name="officesystemsystemhealthmetadatadevice"></a>Office.System.SystemHealthMetadataDevice

Metapodatki, zahtevani za osamitev ponovnega prikaza napake.

Zbrana so sledeča polja:

  - **CollectionTime** – čas, ko so bili zbrani metapodatki

  - **ComputerSystemProductUuidHash** – enosmerna zgostitev UUID-ja matične plošče

  - **DeviceClass** – identifikator za vrsto naprave, v kateri se izvaja Office.

  - **DeviceMake** – identifikator za vrsto sistema strojne opreme za napravo, v kateri se izvaja Office

  - **DeviceManufacturer** – izdelovalec naprave, v kateri se izvaja Office

  - **DeviceModel** – model naprave, v kateri se izvaja Office

  - **DigitizerInfo** – podatki o digitalizatorju, ki je priključen na napravo, v kateri se izvaja Office

  - **IsLaptop** – ali je naprava, v kateri je nameščen Office, prenosni računalnik

  - **IsTablet** – ali je naprava, v kateri je nameščen Office, tablični računalnik

  - **LicensingACID** – naključni identifikator za namestitev Officea

  - **MachineName** – ime naprave, v kateri se izvaja Office

  - **NumProcPhysCores** število fizičnih jeder v procesorju

  - **NumProcShareSingleCache** – število procesorjev, ki si delijo eno jedro v napravi, v kateri se izvaja Office

  - **NumProcShareSingleCore** – število procesorjev na fizično jedo v napravi, v kateri se izvaja Office

  - **OlsLicenseId** – identifikator storitve za licenciranje za namestitev Officea

  - **Platform** – identifikator za okolje, v katerem se izvaja Office

  - **PowerPlatformRole** – identifikator za prednostno vlogo računalnika OEM za napravo, v kateri se izvaja Office

  - **ProcessorCount** – število procesorjev v napravi, v kateri se izvaja Office

  - **ProcSpeedMHz** – hitrost procesorja v napravi, v kateri se izvaja Office (v MHz)

  - **ProcType** – arhitektura procesorja

  - **ProcTypeText** – vrsta procesorja v napravi, v kateri se izvaja Office

  - **RamMB** – količina pomnilnika RAM, ki je na voljo v napravi, v kateri se izvaja Office

  - **SusClientId** – ID za posodobitev sistema Windows za napravo, v kateri se izvaja Office

  - **SystemFamily** – identifikator za vrsto sistema strojne opreme za napravo, v kateri se izvaja Office

  - **SystemSKU** – identifikator SKU za sistem strojne opreme za napravo, v kateri se izvaja Office

  - **SysVolFreeSpaceMB** – količina prostora, ki je na voljo v sistemu, v megabajtih

  - **SysVolSizeMB** – količina prostora v sistemu v megabajtih

  - **WindowsErrorReportingMachineId** – dodeljeni identifikator računalnika za poročanje o napakah sistema Windows v napravi, v kateri se izvaja Office

  - **WindowsSqmMachineId** – dodeljeni identifikator računalnika s sistemom Windows za napravo, v kateri se izvaja Office

### <a name="officesystemsystemhealthmetadatadeviceconsolidated"></a>Office.System.SystemHealthMetadataDeviceConsolidated

Metapodatki, zahtevani za osamitev ponovnega prikaza napake.

Zbrana so sledeča polja:

  - **BootDiskType** – disk ali polprevodniški pogon

  - **ComputerSystemProductUuidHash** – enosmerna zgostitev UUID-ja matične plošče

  - **DeviceClass** – identifikator za vrsto naprave, v kateri se izvaja Office

  - **DeviceManufacturer** – izdelovalec naprave, v kateri se izvaja Office

  - **DeviceModel** – model naprave, v kateri se izvaja Office

  - **DeviceProcessorModel** – model procesorja v napravi, v kateri se izvaja Office

  - **DigitizerInfo** – podatki o digitalizatorju, ki je priključen na napravo, v kateri se izvaja Office

  - **HasSpectreFix -** ali obdelovalec Office je zagnana v napravi uvedla spekter popravek za to težavo.

  - **IsLaptop** – ali je naprava, v kateri je nameščen Office, prenosni računalnik

  - **IsTablet** – ali je naprava, v kateri je nameščen Office, tablični računalnik

  - **MachineName** – ime naprave, v kateri se izvaja Office

  - **NumProcPhysCores** število fizičnih jeder v procesorju

  - **NumProcShareSingleCache** – število procesorjev, ki si delijo eno jedro v napravi, v kateri se izvaja Office

  - **NumProcShareSingleCore** – število procesorjev na fizično jedo v napravi, v kateri se izvaja Office

  - **Platform** – identifikator za okolje, v katerem se izvaja Office

  - **PowerPlatformRole** – identifikator za prednostno vlogo računalnika OEM za napravo, v kateri se izvaja Office

  - **PowerPlatformRole** – identifikator za prednostno vlogo računalnika OEM za napravo, v kateri se izvaja Office

  - **ProcessorCount** – število procesorjev v napravi, v kateri se izvaja Office

  - **ProcSpeedMHz** – hitrost procesorja v napravi, v kateri se izvaja Office (v MHz)

  - **ProcType** – arhitektura procesorja

  - **ProcTypeText** – vrsta procesorja v napravi, v kateri se izvaja Office

  - **RamMB** – količina pomnilnika RAM, ki je na voljo v napravi, v kateri se izvaja Office

  - **SusClientId** – ID za posodobitev sistema Windows za napravo, v kateri se izvaja Office

  - **SysVolFreeSpaceMB** – količina prostora, ki je na voljo v sistemu, v megabajtih

  - **SysVolSizeMB** – količina prostora v sistemu v megabajtih

  - **SysVolSizeMB** – količina prostora v sistemu v megabajtih

  - **WindowsErrorReportingMachineId** – dodeljeni identifikator računalnika za poročanje o napakah sistema Windows v napravi, v kateri se izvaja Office

  - **WindowsSqmMachineId** – dodeljeni identifikator računalnika s sistemom Windows za napravo, v kateri se izvaja Office

### <a name="officesystemsystemhealthmetadataoperatingsystem"></a>Office.System.SystemHealthMetadataOperatingSystem

Metapodatki, zahtevani za osamitev ponovnega prikaza napake.

Zbrana so sledeča polja:

  - **CollectionTime** – čas, ko je bil ta dogodek dodan v čakalno vrsto za prenos

  - **IsTerminalServer** – trditev true/false za terminalskega strežniškega odjemalca

  - **OsBuild** – delovna različica operacijskega sistema

  - **OsBuildRevision** – revizija gradnje operacijskega sistema

  - **OSEnvironment** – Windows, iOS, Mac, Android itd.

  - **OsMajorVer** – glavna različica operacijskega sistema

  - **OsMinorVer** – manjša različica operacijskega sistema

  - **OSSDKVersionCode** – identifikator različice inventarne številke operacijskega sistema

  - **OsSku** – inventarna številka operacijskega sistema

  - **OsSuite2** – identifikator zbirke operacijskega sistema

  - **OSVersionString** – identifikator različice operacijskega 

  - **ServicePackMajorVer** – glavna različica servisnega paketa za operacijski sistem

  - **ServicePackMinorVer** – manjša različica servisnega paketa za operacijski sistem

### <a name="officesystemsystemhealthmetadataoperatingsystemdevice"></a>Office.System.SystemHealthMetadataOperatingSystemDevice

Metapodatki, zahtevani za osamitev ponovnega prikaza napake.

Zbrana so sledeča polja:

  - **CollectionTime** – čas, ko je bil ta dogodek dodan v čakalno vrsto za prenos

  - **DeviceClass** – identifikator za vrsto naprave, v kateri se izvaja Office

  - **DeviceManufacturer** – izdelovalec naprave, v kateri se izvaja Office

  - **DeviceModel** – model naprave, v kateri se izvaja Office

  - **DigitizerInfo** – podatki o digitalizatorju, ki je priključen na napravo, v kateri se izvaja Office

  - **IsLaptop** – ali je naprava, v kateri je nameščen Office, prenosni računalnik

  - **IsTablet** – ali je naprava, v kateri je nameščen Office, tablični računalnik

  - **IsTerminalServer** – trditev true/false za terminalskega strežniškega odjemalca

  - **MachineName** – ime naprave, v kateri se izvaja Office

  - **NumProcPhysCores** število fizičnih jeder v procesorju

  - **NumProcShareSingleCache** – število procesorjev, ki si delijo eno jedro v napravi, v kateri se izvaja Office

  - **NumProcShareSingleCore** – število procesorjev na fizično jedo v napravi, v kateri se izvaja Office

  - **OsBuild** – delovna različica operacijskega sistema

  - **OsBuildRevision** – revizija gradnje operacijskega sistema

  - **OSEnvironment** – Windows, iOS, Mac, Android itd.

  - **OsMajorVer** – glavna različica operacijskega sistema

  - **OsMinorVer** – manjša različica operacijskega sistema

  - **OSSDKVersionCode** – identifikator različice inventarne številke operacijskega sistema

  - **OsSku** – inventarna številka operacijskega sistema

  - **OsSuite2** – identifikator zbirke operacijskega sistema

  - **OSVersionString** – identifikator različice operacijskega 

  - **Platform** – identifikator za okolje, v katerem se izvaja Office

  - **PowerPlatformRole** – identifikator za prednostno vlogo računalnika OEM za napravo, v kateri se izvaja Office

  - **ProcessorCount** – število procesorjev v napravi, v kateri se izvaja Office

  - **ProcSpeedMHz** – hitrost procesorja v napravi, v kateri se izvaja Office (v MHz)

  - **ProcTypeText** – vrsta procesorja

  - **RamMB** – količina pomnilnika RAM, ki je na voljo v napravi, v kateri se izvaja Office

  - **ServicePackMajorVer** – glavna različica servisnega paketa za operacijski sistem

  - **ServicePackMinorVer** – manjša različica servisnega paketa za operacijski sistem

  - **SysVolFreeSpaceMB** – količina prostora, ki je na voljo v sistemu, v megabajtih

  - **SysVolSizeMB** – količina prostora v sistemu v megabajtih

### <a name="officesystemsystemhealthmetadataos"></a>Office.System.SystemHealthMetadataOS

Metapodatki, zahtevani za osamitev ponovnega prikaza napake.

Zbrana so sledeča polja:

  - **CountryRegion** – nastavitev operacijskega sistema za identifikator države/regije

  - **HorizontalResolution** – vodoravna ločljivost zaslona

  - **IsTerminalServer** – trditev true/false za terminalskega strežniškega odjemalca

  - **KeyboardLanguage** – identifikator jezika za tipkovnico naprave

  - **KeyboardLanguageTag** – identifikator jezika za tipkovnico naprave

  - **OfficeWvd** – določa aktivno stanje navideznega namizja v sistemu Windows

  - **OsBuild** – delovna različica operacijskega sistema

  - **OsBuildRevision** – revizija gradnje operacijskega sistema

  - **OSEnvironment** – Windows, iOS, Mac, Android itd.

  - **OsLocale** – identifikator območnih nastavitev za operacijski sistem

  - **OsLocaleTag** – identifikator območnih nastavitev za operacijski sistem

  - **OsMajorVer** – glavna različica operacijskega sistema

  - **OsMinorVer** – manjša različica operacijskega sistema

  - **OSSDKVersionCode** – identifikator različice inventarne številke operacijskega sistema

  - **OsSku** – identifikator inventarne številke za operacijski sistem

  - **OsSuite2** – identifikator zbirke operacijskega sistema

  - **OsUiLang** – jezik uporabniškega vmesnika za operacijski sistem

  - **OSVersionString** – identifikator različice operacijskega 

  - **ScreenDepth** globina zaslona

  - **ScreenDpi** – število pik na palec za zaslon

  - **ServicePackMajorVer** – glavna različica servisnega paketa za operacijski sistem

  - **ServicePackMinorVer** – manjša različica servisnega paketa za operacijski sistem

  - **SystemLocale** – privzete območne nastavitve za operacijski sistem

  - **SystemLocaleTag** – privzete območne nastavitve za operacijski sistem

  - **TimeZoneBiasInMinutes** – razlika med lokalnim časom in UTC-jem v minutah

  - **VerticalResolution** – navpična ločljivost zaslona

### <a name="officesystemsystemhealthmetadatascreencultureusersqmid"></a>Office.System.SystemHealthMetadataScreenCultureUserSqmId

Metapodatki, zahtevani za osamitev ponovnega prikaza napake.

Zbrana so sledeča polja:

  - **Vzdevek** – Microsoftov zaposleni ali avtomatizirani vzdevek uporabnika

  - **CID** – uporabljeni psevdonim za identiteto uporabnika

  - **CollectibleClassifications** – razvrstitve podatkov, ki jih je mogoče zbirati glede na nastavitve zasebnosti odjemalca

  - **CollectionTime** – čas, ko je bil ta dogodek dodan v čakalno vrsto za prenos

  - **CountryRegion** – nastavitev operacijskega sistema za identifikator države/regije

  - **DomainName** – ime Microsoftove domene

  - **HorizontalResolution** – vodoravna ločljivost zaslona

  - **IntegratedScreenSize** – velikost integriranega zaslona

  - **IsJoinedToDomain** trditev true/false za pridruženost domene odjemalca

  - **IsLabMachine** – je Microsoftov laboratorijski računalnik za preskušanje

  - **IsMsftInternal**  –trditev true/false, ali je računalnik pridružen Microsoftovi poslovni domeni

  - **IsSubscription** – ali je Officeova aplikacija nameščena v sklopu naročniške licence

  - **KeyboardLanguage** – identifikator jezika za tipkovnico naprave

  - **KeyboardLanguageTag** – identifikator jezika za tipkovnico naprave

  - **OsLocale** – identifikator območnih nastavitev za operacijski sistem

  - **OsLocaleTag** – identifikator območnih nastavitev za operacijski sistem

  - **OsUiLang** – jezik uporabniškega vmesnika za operacijski sistem

  - **ScreenDepth** globina zaslona

  - **ScreenDpi** – število pik na palec za zaslon

  - **ScreenXDpi** – število pik na palec za X-os zaslona

  - **ScreenYDpi** – število pik na palec za Y-os zaslona

  - **SqmUserId** – naključni identifikator za namestitev Officea

  - **StudyId** – identifikator za preučevanje kakovosti metrike za programsko opremo

  - **SystemLocale** – privzete območne nastavitve za operacijski sistem

  - **SystemLocaleTag** – privzete območne nastavitve za operacijski sistem

  - **TimeZoneBiasInMinutes** – razlika med lokalnim časom in UTC-jem v minutah

  - **VerticalResolution** – navpična ločljivost zaslona

  - **WinUserActType** – ali je uporabnik sistema Windows, ki izvaja Office, lokalni skrbnik, zahtevni uporabnik ali običajni uporabnik

### <a name="officesystemsystemhealthofficelensidentity"></a>Office.System.SystemHealthOfficeLensIdentity

Podatki o identiteti uporabnika, zahtevani za izpolnjevanje zahtev za zahtevo podatkov.

Zbrana so sledeča polja:

  - **CID** – uporabljeni psevdonim za identiteto uporabnika

### <a name="officesystemsystemhealthrollbacksessionmetadata"></a>Office.System.SystemHealthRollbackSessionMetadata

Metapodatki, zahtevani za osamitev ponovnega prikaza napake.

Zbrana so sledeča polja:

  - **InstallMethod** – nova namestitev, posodobitev ali povrnitev na prejšnjo različico

  - **IsSubscription** – ali je Officeova aplikacija nameščena v sklopu naročniške licence

  - **PreviousBuild** – prejšnja nameščena delovna različica

### <a name="officesystemsystemhealthsessionlifecycleandheartbeat"></a>Office.System.SystemHealthSessionLifecycleAndHeartbeat

Zagotavlja informacije o metriki stanja sistema.

Zbrana so sledeča polja:

  - **InstallMethod** – ali je bila trenutna Officeova namestitev nadgrajena iz, povrnjena v prejšnje stanje oziroma sveža namestitev

  - **InteractionSessionID** – identifikator seje

  - **PreviousBuild** – različica Officea, na katero je bila ta graditev nadgrajena ali s katere je bila povrnjena na prejšnjo različico.

  - **State** – stanje, v katerega se je spremenila seja

  - **Time** – čas, ko se je spremenilo stanje seje

### <a name="officesystemsystemhealthsessionstarttime"></a>Office.System.SystemHealthSessionStartTime

Dogodek se uporablja s podatki o zrušitvi, da lahko razlikuje med zgodnjimi in poznejšimi zrušitvami (npr. za določitev, ali je pred zrušitvijo uporabnik aplikacijo uporabljal nekaj časa).

Zbrana so sledeča polja:

  - **SessionStart** – čas, ko telemetrija začne obdelavo podatkov

### <a name="officesystemsystemhealthungracefulappexitdesktop"></a>Office.System.SystemHealthUngracefulAppExitDesktop

Dogodek se uporablja za metrike zrušitev.

Zbrana so sledeča polja:

  - **AffectedProcessAppBuild** – identifikator delovne različice za vplivani proces

  - **AffectedProcessAppBuild** – delovna revizija identifikatorja za vplivani proces

  - **AffectedProcessAppMinorVer** – identifikator manjše različice za vplivani proces

  - **AffectedProcessAppName** – ime vplivanega procesa

  - **AffectedProcessExeBuildVersion** – številka delovne različice vplivanega procesa

  - **AffectedProcessExeMajorVersion** – številka glavne različice vplivanega procesa

  - **AffectedProcessExeMinorVersion** – številka manjše različice vplivanega procesa

  - **AffectedProcessExeRevisionVersion** – številka revizije delovne različice vplivanega procesa

  - **AffectedProcessIsDebug** – ali je vplivani proces podrejeni element za odpravljanje napak

  - **AffectedProcessIsLabMachine** – ali je vplivani proces v Microsfotovem laboratoriju

  - **AffectedProcessOsEnvironment** – identifikator operacijskega sistema za vplivani proces

  - **AppName** – ime vplivane aplikacije

  - **CrashedAssignedFlights** – leti, povezani s procesom zrušitve

  - **CrashedConfigIds** – konfiguracija, dodeljena procesu zrušitve

  - **CrashedEcsETag** – identifikator preskusa za proces zrušitve

  - **CrashedImpressionId** – identifikator vtisa za proces zrušitve

  - **CrashedProcessSessionID** – enolični identifikator procesa zrušitve

  - **CrashedProcessSessionInitTime** – čas, ko se je začel vplivani proces

  - **CrashType** – identifikator razdeljevanja za vrsto zrušitve

  - **DetectionTime** – čas, ko je bil zaznan nepričakovani izhod

  - **ErrorString** – opis napake

  - **ExceptionAddress** – mesto v programu, kjer je prišlo do napake

  - **ExceptionCode** – identifikator razdeljevanja za izjemo

  - **FaultAppName** – ime aplikacije z napako

  - **InstallMethod** – ali je bila trenutna gradnja Officea nadgrajena iz, povrnjena v prejšnje stanje oziroma sveža namestitev

  - **InstallType** – identifikator za način namestitve Officea

  - **InstallTypeName** – identifikator za način namestitve Officea

  - **IsLabMachine** – ali se Office izvaja v Microsoftovem laboratoriju

  - **IsMsftInternal** – ali je uporabnik sistema Windows, ki izvaja Office, Microsoftov zaposleni

  - **ModuleBaseAddress** – osnovni naslov modula z napako

  - **ModuleBuildVersion** – številka delovne različice za modul z napako

  - **ModuleMajorVersion** – številka glavne različice za modul z napako

  - **ModuleMinorVersion** – številka manjše različice za modul z napako

  - **ModuleName** – ime modula z napako

  - **ModuleOffset** – odmik v bajtih od osnovnega mesta, kjer je prišlo do napake

  - **ModuleRevisionVersion** – številka različice za revizijo gradnje modula z napako

  - **ModuleSize** – velikost modula z napako v bajtih

  - **OSEnvironment** – identifikator za okolje, v katerem se izvaja Office

  - **PreviousBuild** – prejšnja nameščena delovna različica

  - **UAETypeName** – identifikator razdeljevanja za način nenavadnega izhoda iz aplikacije

  - **VerifyElseCrashTag** – enolični identifikator za mesto zrušitve aplikacije

### <a name="officesystemsystemhealthungracefulappexitimmersive"></a>Office.System.SystemHealthUngracefulAppExitImmersive

Dogodek se uporablja za metrike zrušitev.

Zbrana so sledeča polja:

  - **AffectedProcessAppBuild** – identifikator delovne različice za vplivani proces

  - **AffectedProcessAppBuild** – delovna revizija identifikatorja za vplivani proces

  - **AffectedProcessAppMajorVer** – identifikator glavne različice za vplivani proces

  - **AffectedProcessAppMinorVer** – identifikator manjše različice za vplivani proces

  - **AffectedProcessAppName** – ime vplivanega procesa

  - **AffectedProcessExeBuildVersion** – številka delovne različice vplivanega procesa

  - **AffectedProcessExeMajorVersion** – številka glavne različice vplivanega procesa

  - **AffectedProcessExeMinorVersion** – številka manjše različice vplivanega procesa

  - **AffectedProcessExeRevisionVersion** – številka revizije delovne različice vplivanega procesa

  - **AffectedProcessIsDebug** – ali je vplivani proces podrejeni element za odpravljanje napak

  - **AffectedProcessIsLabMachine** – ali je vplivani proces v Microsfotovem laboratoriju

  - **AffectedProcessOsEnvironment** – identifikator operacijskega sistema za vplivani proces

  - **AppName** – ime vplivane aplikacije

  - **CrashedAssignedFlights** – leti, povezani s procesom zrušitve

  - **CrashedConfigIds** – konfiguracija, dodeljena procesu zrušitve

  - **CrashedImpressionId** – identifikator vtisa za proces zrušitve

  - **CrashedInteractionSessionID** – identifikator seje interakcije za vplivani proces

  - **CrashedInteractionSessionTime** – čas za morebitno interakcijo z vplivanim procesom

  - **CrashedProcessSessionID** – enolični identifikator procesa zrušitve

  - **CrashedProcessSessionInitTime** – čas, ko se je začel vplivani proces

  - **DetectionTime** – čas, ko je bil zaznan nepričakovani izhod

  - **IsLabMachine** – ali se Office izvaja v Microsoftovem laboratoriju

  - **IsMsftInternal** – ali je uporabnik sistema Windows, ki izvaja Office, Microsoftov zaposleni

  - **OSEnvironment** – identifikator za okolje, v katerem se izvaja Office

  - **PreviousLifecycleState** – stanje vplivanega procesa, ko je prišlo do zrušitve

  - **UAETypeName** – identifikator razdeljevanja za način nenavadnega izhoda iz aplikacije

### <a name="officesystemsystemhealthungracefulapplicationexitwin32"></a>Office.System.SystemHealthUngracefulApplicationExitWin32

Dogodek sproži neobičajna prekinitev aplikacije (na primer prekinitev izvajanja upravitelja opravil, neodzivnost aplikacije ipd.) v primeru Officeovih odjemalskih aplikacij, kot so med drugim Word, Excel, PowerPoint in Outlook. Metriko motenega zapiranja aplikacij uporabljamo za merjenje stanja Officeovih odjemalskih izdelkov. Gre za ključni poslovni signal, ki ga Officeovi inženirji uporabljajo za zagotavljanje stabilnosti izdelka.

Zbrana so naslednja polja:

  - **AddinExecution –** zastavica, ki sporoča, ali se je dodatek izvajal in se med nenavadnim izhodom iz aplikacije ni končal.

  - **BootCompleted –** zagon Officea je bil ob trenutku zrušitve dokončan.

  - **CrashedProcessAppBuild** – identifikator delovne različice za vplivani proces

  - **CrashedAppMajor** – identifikator glavne različice za vplivani proces

  - **CrashedAppMinor** – identifikator manjše različice za vplivani proces

  - **CrashedAppRevision** – identifikator delovne različice za vplivani proces

  - **CrashedEcsETag** – identifikator preskusa za proces zrušitve.

  - **CrashedModuleName** – ime modula z napako

  - **CrashedSessionID** – enolični identifikator procesa zrušitve

  - **CrashedSessionInitTime** – čas, ko se je začel vplivani proces

  - **CrashTime –** ura, ki označuje, da odjemalec ni bil zaustavljen pravilno

  - **CrashType** – identifikator razdeljevanja za vrsto zrušitve

  - **DetectionTime** – čas, ko je bil zaznan nepričakovani izhod

  - **ExceptionAddress** – mesto v programu, kjer je prišlo do napake

  - **ExceptionCode** – identifikator razdeljevanja za izjemo

  - **HandOff –** ali je uporabnik ustvaril in predal Officeov postopek v novo sejo.

  - **HasEdit –** ali je uporabnik urejal dokument v odjemalcu, ki se je zrušil.

  - **HasOpen –** ali je bil v odjemalcu, ki se je zrušil, odprt dokument.

  - **HexCrashTag** – enolični identifikator za kodo zrušitve.

  - **HexExceptionAddress** – mesto v programu, kjer je prišlo do napake, v šestnajstiški obliki

  - **HexExceptionCode** – identifikator razdeljevanja za izjemo v šestnajstiški obliki

  - **HexModuleBaseAddress** – osnovni naslov modula z napako v šestnajstiški obliki

  - **HexModuleOffset** – odmik v bajtih (v šestnajstiški obliki) od osnovnega mesta, kjer je prišlo do napake

  - **HexModuleSize** – velikost modula z napako v bajtih v šestnajstiški obliki

  - **HexVerifyElseCrashTag** – enolični identifikator za mesto zrušitve aplikacije v šestnajstiški obliki

  - **InstallMethod** – ali je bila trenutna gradnja Officea nadgrajena iz, povrnjena v prejšnje stanje oziroma sveža namestitev

  - **IsLabMachine** – ali se Office izvaja v Microsoftovem laboratoriju

  - **ModuleBaseAddress** – osnovni naslov modula z napako

  - **ModuleOffset** – odmik v bajtih od osnovnega mesta, kjer je prišlo do napake

  - **ModuleSize** – velikost modula z napako v bajtih

  - **OfficeArchitectureText** – arhitektura Officeovega izdelka kot niz (na primer x86, krak).

  - **OfficeUILang –** jezik uporabniškega vmesnika v Officeovi graditvi

  - **PreviousBuild** – prejšnja nameščena delovna različica

  - **SafeMode –** ali je bila seja zagnana v varnem načinu

  - **UAEOSEnvironment** – identifikator okolja za operacijski sistem

  - **UninitLibletId** – enolični identifikator za neuspešne komponente zrušitve.

  - **VerifyElseCrashTag** – enolični identifikator za mesto zrušitve aplikacije *[To polje je bilo odstranjeno iz trenutnih graditev Officea, vendar se bo morda še vedo pojavljalo v starejših graditvah.]*

### <a name="officesystemungracefulapplicationexitdesktopappexit"></a>Office.System.UngracefulApplicationExit.DesktopAppExit

Dogodek se uporablja za metrike zrušitev.

Zbrana so sledeča polja:

  - **AppBuildVersion** – identifikator delovne različice za vplivani proces

  - **AppMajorVersion** – številka glavne različice vplivanega procesa

  - **AppMinorVersion** – identifikator manjše različice za vplivani proces

  - **AppName** – ime vplivane aplikacije

  - **AppRevisionVersion** – identifikator revizije delovne različice za vplivani proces

  - **CrashedAssignedFlights** – leti, povezani s procesom zrušitve

  - **CrashedConfigIds** – konfiguracija, dodeljena procesu zrušitve

  - **CrashedImpressionId** – identifikator vtisa za proces zrušitve

  - **CrashedInteractionSessionId** – identifikator seje interakcije za proces rušitve

  - **CrashedProcessSessionID** – enolični identifikator procesa zrušitve

  - **CrashType** – identifikator razdeljevanja za vrsto zrušitve

  - **ErrorString** – opis napake

  - **ExceptionAddress** – mesto v programu, kjer je prišlo do napake

  - **ExceptionCode** – identifikator razdeljevanja za izjemo

  - **FaultAppName** – ime aplikacije z napako

  - **InstallMethod** – ali je bila trenutna gradnja Officea nadgrajena iz, povrnjena v prejšnje stanje oziroma sveža namestitev

  - **InstallType** – identifikator za način namestitve Officea

  - **IsDebug** – ali je to gradnja Officea za odpravljanje napak

  - **IsHandledCrash** – ali je bil program za obravnavno rušitve pozvan v seji zrušitve

  - **IsLabMachine** – ali se Office izvaja v Microsoftovem laboratoriju

  - **ModuleBaseAddress** – osnovni naslov modula z napako

  - **ModuleName** – ime modula z napako

  - **ModuleOffset** – odmik v bajtih od osnovnega mesta, kjer je prišlo do napake

  - **ModuleSize** – velikost modula z napako v bajtih

  - **OSEnvironment** – identifikator za okolje, v katerem se izvaja Office

  - **PreviousBuild** – prejšnja nameščena delovna različica

  - **PreviousInteractionSessionTime** – čas, ko je bila zagnana seja prejšnje interakcije.

  - **PreviousLifecycleState** – identifikator stanja življenjskega cikla za prejšnjo sejo

  - **PreviousSessionInitTime** – čas, ko je bila zagnana prejšnja seja

  - **StackHash** – identifikator, ki ponazarja mesto v kodi, kjer je prišlo do zrušitve vplivanega procesa

  - **VerifyElseCrashTag** – enolični identifikator za mesto zrušitve aplikacije

### <a name="officesystemuserchangeddiagnosticlevel"></a>Office.System.UserChangedDiagnosticLevel

Informacije, zahtevane za vsilitev izbir pravilnika o zasebnosti uporabnika.

Zbrana so sledeča polja:

  - **DiagnosticLevelChanged**: označuje, da je uporabnik spremenil diagnostično raven

  - **NewDiagnosticLevel**: raven po spremembi uporabnika

  - **OldDiagnosticLevel**: raven, ki jo je uporabnik uporabljal pred spremembo

### <a name="officetelemetryariaeventsinkhandlemsadevicetokenresponse"></a>Office.Telemetry.AriaEventSink.HandleMsaDeviceTokenResponse

Signal prekinitve storitve Microsoftovega računa.

Zbrana so sledeča polja:

  - **RetryCount** – število ponovitev vzpostavljanja povezave s storitvijo MSA

### <a name="officetelemetryariaeventsinkrequestmsadevicetoken"></a>Office.Telemetry.AriaEventSink.RequestMsaDeviceToken

Signal prekinitve storitve Microsoftovega računa.

Zbrana so sledeča polja:

  - **RetryCount** – število ponovitev vzpostavljanja povezave z Microsoftovim računom

### <a name="officetelemetryclientsamplingoverridden"></a>Office.Telemetry.ClientSamplingOverridden

Informacije, zahtevane za pravilne hitrosti ponovitev. Po navadi ta dogodek ne velja za skupino občinstva produkcije.

Zbrana so sledeča polja:

  - **OverriddenMeasureEnabled** – predstavlja odjemalca, nastavljenega za pošiljanje več nevzorčnih dogodkov

  - **OverriddenNumberlinePosition** – položaj novega mesta številske vrstice za vzorčenje

  - **OverriddenReportedSampleRate** – nova poročana hitrost vzorčenja

  - **OverriddenSampleRate** – nova hitrost vzorčenja

  - **PreviousNumberlinePosition** – vzorčni položaj v številski vrstici

  - **PreviousSampleRate** – hitrost vzorčenja, preden je bila preglašena

  - **WasMeasureEnabled** – predstavlja odjemalca, nastavljenega za pošiljanje več nevzorčnih dogodkov

### <a name="officetelemetrycomplianceeventnotinbasicallowlist"></a>Office.Telemetry.Compliance.EventNotInBasicAllowList

Poroča neveljavne uvedbe ali implementacije telemetrije.

Zbrana so sledeča polja:

  - **ShowEvent** – ime dogodka, ki ni naveden na seznamu

### <a name="officetelemetrycompliancemissingdatacategory"></a>Office.Telemetry.Compliance.MissingDataCategory

Poroča neveljavne uvedbe ali implementacije telemetrije.

Zbrana so sledeča polja:

  - **ShowEvent** – ime dogodka brez kategorije

  - **IsFromRule** – ali je bil dogodek aktiviran s pravilom telemetrije

### <a name="officetelemetrycompliancemissingdatacategoryinrule"></a>Office.Telemetry.Compliance.MissingDataCategoryInRule

Poroča neveljavne uvedbe ali implementacije telemetrije.

Zbrana so sledeča polja:

  - **RuleId** – ID pravila, za katerega ni nastavljena kategorija podatkov

  - **RuleVersion** – različica pravila, za katerega ni nastavljena kategorija podatkov

### <a name="officetelemetrydiagnosticdataviewerstatechanged"></a>Office.Telemetry.DiagnosticDataViewerStateChanged

Potrdi, da si potrošniki lahko ogledajo izhodne podatke računalnika s pregledovalnikom diagnostičnih podatkov.

Zbrana so sledeča polja:

  - **DialogCancelled** – ali je bilo pogovorno okno pregledovalnika diagnostičnih podatkov preklicano

  - **NewState** – novo stanje pregledovalnika diagnostičnih podatkov

  - **WasDialogUsed** – ali je bilo pogovorno okno pregledovalnika diagnostičnih podatkov uporabljeno

### <a name="officetelemetrydynamicconfigfetchconfigs"></a>Office.Telemetry.DynamicConfig.FetchConfigs

Podatki, zahtevani za merjenje stanja storitve za konfiguracijo telemetrije.

Zbrana so sledeča polja:

  - **ParsedConfigCount** – število razčlenjenih dinamičnih konfiguracij

  - **ParsedConfigs** – število razčlenjenih dinamičnih konfiguracij

  - **RejectedConfigCount** – število zavrnjenih konfiguracij

  - **RejectedConfigs** – število zavrnjenih konfiguracij

  - **RejectedConfigsList** – seznam zavrnjenih konfiguracij (vrednosti so med seboj ločene z vejico)

### <a name="officetelemetrydynamicconfigparsejsonconfig"></a>Office.Telemetry.DynamicConfig.ParseJsonConfig

Podatki, zahtevani za merjenje stanja storitve za konfiguracijo telemetrije.

Zbrana so sledeča polja:

  - **ErrorMessage** – sporočilo o napaki razčlenjevanja

  - **NodeName** – vozlišče, ki ga ni bilo mogoče razčleniti

### <a name="officetelemetrydynamicconfigpopulatedrequestignored"></a>Office.Telemetry.DynamicConfig.PopulatedRequestIgnored

Ta dogodek se ustvari, ko ne moremo nastaviti cevovoda za konfiguracijo telemetrije.

Ta dogodek ne zbere nobenega polja.

### <a name="officetelemetrydynamicconfigpopulatetreecalledagain"></a>Office.Telemetry.DynamicConfig.PopulateTreeCalledAgain

Podatki, zahtevani za merjenje stanja storitve za konfiguracijo telemetrije.

Ta dogodek ne zbere nobenega polja.

### <a name="officetelemetryeventquarantined"></a>Office.Telemetry.EventQuarantined

S tem dogodkom lahko preverite, ali dogodki NSD delujejo pravilno.

Zbrana so sledeča polja:

  - **EventName** – ime dogodka v karanteni

  - **Reason** – vzrok karantene

### <a name="officetelemetryflusheventbuffer"></a>Office.Telemetry.FlushEventBuffer 

Poroča velikost medpomnilnika za dogodek in lahko ponazori napake telemetrije, povezane z veliko porabo medpomnilnika.

Zbrana so sledeča polja:

  - **EventCount** – število dogodkov v medpomnilniku

  - **FirstPassCount** – število dogodkov, ki so bili posredovani prvič

  - **SecondPassCount** – število dogodkov, ki so bili posredovani drugič

### <a name="officetelemetrygetfilteredpayloadsfromdisk"></a>Office.Telemetry.GetFilteredPayloadsFromDisk

Preveri, ali določeni podedovani deli cevovoda telemetrije delujejo v platformah, ki jih še vedno uporabljajo

Ta dogodek ne zbere nobenega polja.

### <a name="officetelemetryinvaliddatacontractname"></a>Office.Telemetry.InvalidDataContractName

Poroča neveljavne uvedbe ali implementacije telemetrije.

Zbrana so sledeča polja:

  - **DataContractName** – ime pogodbe za podatke telemetrije

  - **EventName** – ime dogodka s pogodbo za neveljavne podatke

  - **IsRuleEvent** – trditev true/false, ali je dogodek uvedlo pravilo telemetrije

### <a name="officetelemetryinvaliddatafieldname"></a>Office.Telemetry.InvalidDataFieldName 

Poroča neveljavne uvedbe ali implementacije telemetrije.

Zbrana so sledeča polja:

  - **DataFieldName** – ime polja s podatki telemetrije

  - **EventName** – ime dogodka z neveljavnim poljem

  - **IsRuleEvent** – trditev true/false, ali je dogodek uvedlo pravilo telemetrije

### <a name="officetelemetryinvalideventcontractname"></a>Office.Telemetry.InvalidEventContractName 

Poroča neveljavne uvedbe ali implementacije telemetrije.

Zbrana so sledeča polja:

  - **EventContractName** – ime pogodbe za neveljavne podatke telemetrije

  - **EventName** – ime dogodka z neveljavnim imenom pogodbe

  - **IsRuleEvent** – trditev true/false, ali je dogodek uvedlo pravilo telemetrije

### <a name="officetelemetryloadxmlrules"></a>Office.Telemetry.LoadXmlRules

Poroča, ali so bila pravila za telemetrijo razčlenjevanja uspešna

Zbrana so sledeča polja:

  - **DetachedDuration** – ločeno trajanje v mikrosekundah

### <a name="officetelemetrymissingfielddetails"></a>Office.Telemetry.MissingFieldDetails

Poročila o manjkajočih informacijah o poljih za diagnosticiranje tiskarskih napak v konfiguraciji telemetrije.

Zbrana so sledeča polja:

  - **ErrorRuleId** – ID pravila telemetrije, ki je zahteval manjkajoče polje

  - **ErrorRuleVersion** – različica pravila telemetrije, ki je zahtevala manjkajoče polje

  - **EtwEventGuid** – GUID ETW zahtevanega polja

  - **EtwEventId** – ID dogodka ETW zahtevanega polja

  - **MissingFieldName** – ime zahtevanega polja

  - **UlsTagId** – oznaka kode za manjkajoče polje

### <a name="officetelemetryprocessidlequeuejob"></a>Office.Telemetry.ProcessIdleQueueJob

Poroča, da se je začela pričakovana obdelava nedejavne telemetrije.

Zbrana so sledeča polja:

  - **DetachedDuration** – ločeno trajanje v mikrosekundah

  - **FailureDiagnostic** – postopek, ki ga ni bilo mogoče izvesti

### <a name="officetelemetryredstoneinboxsampling"></a>Office.Telemetry.RedstoneInboxSampling

Vzorčno stanje za odjemalca, ki je zahtevan za natančno tolmačenje druge metrike.

Zbrana so sledeča polja:

  - **MeasuresEnabled** – ali so meritve omogočene v tej seji?

  - **SamplingClientIdValue** – vzorčna vrednost za tega odjemalca

  - **SamplingKey** – vzorčni ključ za tega odjemalca

  - **SamplingMethod** – vzorčni način za tega odjemalca

### <a name="officetelemetryredstoneinboxsamplingcritical"></a>Office.Telemetry.RedstoneInboxSamplingCritical

Vzorčno stanje za odjemalca je lahko zahtevano za natančno tolmačenje druge metrike.

Zbrana so sledeča polja:

  - **MeasuresEnabled** – ali so meritve omogočene v tej seji?

  - **SamplingClientIdValue** – vzorčna vrednost za tega odjemalca

  - **SamplingKey** – vzorčni ključ za tega odjemalca

  - **SamplingMethod** – vzorčni način za tega odjemalca

### <a name="officetelemetryruleerrorsaggregated"></a>Office.Telemetry.RuleErrorsAggregated

Poročanje o napakah stanja telemetrije. Zahtevano za preverjanje drugih podatkov (vključno z NSD).

Zbrana so sledeča polja:

  - **ErrorCount** – število napake s časovnim oknom združevanja

  - **ErrorInfo** – informativna številka za diagnostično napako

  - **ErrorRuleId** – ID pravila telemetrije, ki je povzročila napako

  - **ErrorRuleVersion** – različica pravila telemetrije, ki je povzročila napako

  - **WarningInfo** – informativna številka diagnostičnega opozorila

<!-- end list -->

  - **QueueFlushCount** – število praznjenj v čakalni vrsti

  - **QueueFlushDueToSizeLimit** – velikost, pri kateri telemetrija izprazni čakalno vrsto

  - **QueueFlushesDueToSize** – število praznjenj čakalne vrste, ki jih je povzročila velikost medpomnilnika

  - **QueueHardLimit** – omejitev zaustavitev telemetrije

  - **QueueLimitHitTime** – čas, ko je bila dosežena omejitev zaustavitev

  - **ResultTime** – čas tega dogodka

### <a name="officetelemetryrulesenginediskthrottled"></a>Office.Telemetry.RulesEngineDiskThrottled

Omejevanje metrike DQ. Zahtevano za zaupanje v druge podatke.

Zbrana so sledeča polja:

  - **DiskWriteLimit** – omejitev velikosti diska za podatke telemetrije

  - **DiskWriteTotal** – skupna velikost za pisanje podatkov telemetrije na disk

  - **SessionDiskWriteTotal** – skupna velikost seje za pisanje podatkov telemetrije na disk

  - **ThrottlingTimestamp** – čas, ko je bila omejena seja

### <a name="officetelemetryrulesenginemediumcostthrottled"></a>Office.Telemetry.RulesEngineMediumCostThrottled

Omejevanje metrike DQ. Zahtevano za zaupanje v druge podatke.

Ta dogodek ne zbere nobenega polja.

### <a name="officetelemetryrulesenginespikethrottled"></a>Office.Telemetry.RulesEngineSpikeThrottled

Omejevanje metrike DQ. Zahtevano za zaupanje v druge podatke.

Zbrana so sledeča polja:

  - **CurrentLimit** – trenutna omejitev konice

  - **Duration** – trajanje konice

  - **Factor** – faktor konice

  - **HighestImpactingRuleBytes** – večina bajtov, ki jih posname pravilo telemetrije

  - **HighestImpactingRuleId** – ID pravila, ki je posnel večino bajtov

  - **HighestImpactingRuleVersion** – različica pravila, ki je posnela večino bajtov

  - **MaxLimit** – največja dovoljena omejitev

  - **ThrottlingTimestamp** – čas, ko je bila omejena telemetrija

### <a name="officetelemetryrulesenginethrottled"></a>Office.Telemetry.RulesEngineThrottled

Omejevanje metrike DQ. Zahtevano za zaupanje v druge podatke.

Zbrana so naslednja polja:

  - **ThrottlingTimestamp** – čas, ko je bila omejena telemetrija

### <a name="officetelemetryrulesengineulsqueuesizebackgroundprocessinglevelreached"></a>Office.Telemetry.RulesEngineUlsQueueSizeBackgroundProcessingLevelReached

Poročila o tem, da je v čakalni vrsti preveliko število dogodkov za obdelavo v času nedejavnosti aplikacije.

Zbrana so sledeča polja:

  - **BackgroundProcessingLevelInBytes** – velikost čakalne vrste za zagon obdelave v ozadju

  - **CurrentQueueSize** – število dogodkov v čakalni vrsti nULS

  - **CurrentQueueSizeInBytes** – velikost čakalne vrste nULS v bajtih

  - **ReachedTimestamp** – čas začetka obdelave v ozadju

### <a name="officetelemetryrulesresultuploadlatencyrule"></a>Office.Telemetry.RulesResultUploadLatencyRule

Povprečna, najnižja in najvišja zakasnitev prenosa za koristno vsebino z rezultati pravila za vsako uro

Zbrana so sledeča polja:

  - **AverageLatency** – povprečna zakasnitev prenosa

  - **CollectionTime** – čas, ko so bili zbrani podatki o prenosu pravila

  - **LatencyGE201LE400** – število prenosov z zakasnitvijo, ki je večja ali enaka 201 ms oziroma manjša ali enaka 400 ms

  - **LatencyGE3001** – število prenosov z zakasnitvijo, ki je večja ali enaka 3001 ms

  - **LatencyGE401LE600** – število prenosov z zakasnitvijo, ki je večja ali enaka 401 ms oziroma manjša ali enaka 600 ms

  - **LatencyGE601LE800** – število prenosov z zakasnitvijo, ki je večja ali enaka 601 ms oziroma manjša ali enaka 800 ms

  - **LatencyLE200** – število prenosov z zakasnitvijo, ki je manjša od 200 ms

  - **MaxLatency** – najvišja zaznana zakasnitev

  - **MinLatency** – najnižja zaznana zakasnitev

### <a name="officetelemetrysamplingpolicy"></a>Office.Telemetry.SamplingPolicy

Vzorčno stanje za odjemalca, ki je zahtevan za natančno tolmačenje druge metrike.

Zbrana so sledeča polja:

  - **MeasuresEnabled** – ali so meritve omogočene v tej seji?

  - **SamplingClientIdValue** – vzorčna vrednost za tega odjemalca

  - **SamplingKey** – vzorčni ključ za tega odjemalca

  - **SamplingMethod** – vzorčni način za tega odjemalca

### <a name="officetelemetrysamplingpolicyeventtrigger"></a>Office.Telemetry.SamplingPolicyEventTrigger

Vzorčno stanje za odjemalca, ki je zahtevan za natančno tolmačenje druge metrike.

Zbrana so sledeča polja:

  - **MeasuresEnabled** – ali so meritve omogočene v tej seji?

  - **SamplingKey** – vzorčni ključ za tega odjemalca

  - **SamplingMethod** – vzorčni način za tega odjemalca

### <a name="officetelemetrysessiontelemetryruleschanged"></a>Office.Telemetry.SessionTelemetryRulesChanged

Poroča, da se je spremenil nabor pravil telemetrije.

Zbrana so sledeča polja:

  - **ChangedRuleId** – ID pravila telemetrije, ki se je spremenil v trenutni posodobitvi

  - **ChangedRuleVersion** – različica pravila telemetrije, ki se je spremenila v trenutni posodobitvi

  - **OperationType** – dodajanje ali odstranjevanje oznake postopka

### <a name="officetelemetrysessiontelemetryrulescount"></a>Office.Telemetry.SessionTelemetryRulesCount

Poroča število naloženih pravil telemetrije.

Zbrana so sledeča polja:

  - **CountOfLoadedRules** – število naloženih pravil telemetrije

  - **HadRuleFileAtBoot** – ali je bila pri zagonu aplikacije zaznana datoteka s pravili telemetrije

### <a name="officetelemetrysessiontelemetryrulesinitialstate"></a>Office.Telemetry.SessionTelemetryRulesInitialState

Poroča, da so bila ob začetki seje naložena pravila telemetrije.

Zbrana so sledeča polja:

  - **HadRuleFileAtBoot** – ali je bila pri zagonu aplikacije zaznana datoteka s pravili telemetrije

  - **LoadedRulesCount** – število naloženih pravil telemetrije

  - **LoadedRulesList** – seznam naloženih pravil telemetrije

### <a name="officetelemetrysystemhealthmetadatanetworkcost"></a>Office.Telemetry.SystemHealthMetadataNetworkCost

Stroški omrežja ponazarjajo našo zmožnost pridobivanja podatkov.

Zbrana so sledeča polja:

  - **NetworkCost** – novi izmerjeni ali neizmerjeni stroški omrežja

  - **OldNetworkCost** – prejšnji izmerjeni ali neizmerjeni stroški omrežja

  - **Tag** – oznaka izvorne kode, ki je zaznala spremembo

### <a name="officetelemetrysystemhealthmetadatanetworkcostchange"></a>Office.Telemetry.SystemHealthMetadataNetworkCostChange

Stroški omrežja ponazarjajo našo zmožnost pridobivanja podatkov.

Zbrana so sledeča polja:

  - **NewNetworkCost** – novi izmerjeni ali neizmerjeni stroški omrežja

  - **OldNetworkCost** – prejšnji izmerjeni ali neizmerjeni stroški omrežja

  - **Tag** – oznaka izvorne kode, ki je zaznala spremembo

### <a name="officetelemetrytelemetryactivityaggregationwindowstatistics"></a>Office.Telemetry.TelemetryActivityAggregationWindowStatistics

Poroča število zbranih skupin dejavnosti in primerkov prenosov v posameznih aktivnostih.

Zbrana so sledeča polja:

  - **GroupCount** – število zbranih dejavnosti, ki pošiljajo podatke

  - **InstancesToSend** – število primerkov zbranih dejavnosti, ki pošiljajo podatke

### <a name="officetelemetrytelemetryulsqueueusage"></a>Office.Telemetry.TelemetryUlsQueueUsage

Poročanje o napakah stanja telemetrije. Zahtevano za preverjanje drugih podatkov (vključno z NSD).

Zbrana so sledeča polja:

  - **AverageEventCount** – povprečno število dogodkov v čakalni vrsti

  - **AverageQueueCB** – povprečna velikost pomnilnika za čakalno vrsto

  - **PeakEventCount** – število dogodkov ob konicah v čakalni vrsti

  - **PeakQueueCB** – velikost pomnilnika ob konicah v čakalni vrsti

  - **QueueDisableRuleLimit** – omejitev, pri kateri se onemogočijo pravila telemetrije

### <a name="officetelemetryulsqueuetopthrottlingtags"></a>Office.Telemetry.UlsQueueTopThrottlingTags

Poroča oznake, ki so najbolj pripomogle k zaustavitvi čakalne vrste ULS.

Zbrana so sledeča polja:

  - **Tag0** – oznaka, ki je porabila večino čakalne vrste

  - **Tag0Percent** – odstotek čakalne vrste, ki jo zasede oznaka tag0

  - **Tag1** – oznaka, ki je porabila 2. največjo količino čakalne vrste

  - **Tag10** – oznaka, ki je porabila 11. največjo količino čakalne vrste

  - **Tag10Percent** – odstotek čakalne vrste, ki jo zasede oznaka tag10

  - **Tag11** – oznaka, ki je porabila 12. največjo količino čakalne vrste

  - **Tag11Percent** – odstotek čakalne vrste, ki jo zasede oznaka tag11

  - **Tag12** – oznaka, ki je porabila 13. največjo količino čakalne vrste

  - **Tag12Percent** – odstotek čakalne vrste, ki jo zasede oznaka tag12

  - **Tag13** – oznaka, ki je porabila 14. največjo količino čakalne vrste

  - **Tag13Percent** – odstotek čakalne vrste, ki jo zasede oznaka tag13

  - **Tag14** – oznaka, ki je porabila 15. največjo količino čakalne vrste

  - **Tag14Percent** – odstotek čakalne vrste, ki jo zasede oznaka tag14

  - **Tag1Percent** – odstotek čakalne vrste, ki jo zasede oznaka tag1

  - **Tag2** – oznaka, ki je porabila 3. največjo količino čakalne vrste

  - **Tag2Percent** – odstotek čakalne vrste, ki jo zasede oznaka tag2

  - **Tag3** – oznaka, ki je porabila 4. največjo količino čakalne vrste

  - **Tag3Percent** – odstotek čakalne vrste, ki jo zasede oznaka tag3

  - **Tag4** – oznaka, ki je porabila 5. največjo količino čakalne vrste

  - **Tag4Percent** – odstotek čakalne vrste, ki jo zasede oznaka tag4

  - **Tag5** – oznaka, ki je porabila 6. največjo količino čakalne vrste

  - **Tag5Percent** – odstotek čakalne vrste, ki jo zasede oznaka tag5

  - **Tag6** – oznaka, ki je porabila 7. največjo količino čakalne vrste

  - **Tag6Percent** – odstotek čakalne vrste, ki jo zasede oznaka tag6

  - **Tag7** – oznaka, ki je porabila 8. največjo količino čakalne vrste

  - **Tag7Percent** – odstotek čakalne vrste, ki jo zasede oznaka tag7

  - **Tag8** – oznaka, ki je porabila 9. največjo količino čakalne vrste

  - **Tag8Percent** – odstotek čakalne vrste, ki jo zasede oznaka tag8

  - **Tag9** – oznaka, ki je porabila 10. največjo količino čakalne vrste

  - **Tag9Percent** – odstotek čakalne vrste, ki jo zasede oznaka tag9

### <a name="officetelemetryvolumetrackingdata"></a>Office.Telemetry.VolumeTrackingData

Metrika za sledenje količine dogodkov za dogodke telemetrije

Zbrana so sledeča polja:

  - **EventThreshold** – največje število primerkov za posamezen dogodek, ki ga lahko pošljete v časovnem oknu

  - **HighestEventCount** – najvišje število primerkov za posamezen dogodek, poslan v tem oknu

  - **HighestEventName** – ime dogodka z najvišjim številom primerkov v tem oknu

  - **TimeWindowInSeconds** – trajanje okna v sekundah

  - **TotalEvents** – skupno število dogodkov, poslanih v oknu

  - **UniqueEvents** – število enoličnih dogodkov, poslanih v oknu

### <a name="officetelemetrywritepayloadstodisk"></a>Office.Telemetry.WritePayloadsToDisk

Preveri, ali določeni podedovani deli cevovoda delujejo v platformah, ki jih še vedno uporabljajo

Zbrana so sledeča polja:

  - **DetachedDuration** – ločeno trajanje v mikrosekundah
