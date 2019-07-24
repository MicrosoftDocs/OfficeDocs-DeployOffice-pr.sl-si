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
ms.openlocfilehash: 14b2426d021e5c559cabd3c969f80df9131cc9b9
ms.sourcegitcommit: 22ae0005d3106ff02949fb613b82e0245abfa49f
ms.translationtype: HT
ms.contentlocale: sl-SI
ms.lasthandoff: 07/22/2019
ms.locfileid: "35817986"
---
# <a name="essential-services-for-office"></a>Osnovne storitve za Office

> [!IMPORTANT]
> Informacije v tem članku veljajo za različico 1904 ali novejšo različico sledeče Officeove odjemalske programske opreme, ki je nameščena v računalniku s sistemom Windows:
> - Office 365 ProPlus in Office 365 Business
> - Office 365 Personal, Office 365 Home ali druge različice Officea, ki so del naročnine na Office 365.
> - Project in Visio, ki sta vključena v nekatere naročniške pakete, kot sta paketa Project Online Professional ali Visio Online 2.


Office sestavljajo aplikacije odjemalske programske opreme in povezane izkušnje, zasnovne tako, da vam omogočajo bolj učinkovito ustvarjanje, komuniciranje in sodelovanje. Upravljate lahko številne povezane izkušnje, ki so na voljo za vas ali vaše uporabnike, če ste skrbnik v organizaciji, obstaja pa tudi nabor osnovnih storitev, ko določajo način delovanja Officea in jih tako ni mogoče onemogočiti. Na primer storitev licenciranja, s katero potrdite, da imate ustrezno licenco za uporabo Officea. Zahtevani podatki o teh storitvah so zbrani in poslani Microsoftu, ne glede na to, ali imate konfigurirane druge nastavitve pravilnika, povezane z varnostjo. Te podatke si lahko ogledate s pregledovalnikom diagnostičnih podatkov.

Če želite več informacij, preberite članke:

- [Zahtevani podatki storitev za Office](required-service-data.md)
- [Uporaba pregledovalnika diagnostičnih podatkov z Officeom](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)
- [Povezane izkušnje v Officeu](connected-experiences.md)

Če ste skrbnik v svoji organizaciji, vas bo morda zanimalo to:

- [Pregled kontrolnikov zasebnosti za Office 365 ProPlus](overview-privacy-controls.md)
- [Uporaba nastavitev pravilnika za upravljanje kontrolnikov zasebnosti za Office365 ProPlus](manage-privacy-controls.md)

## <a name="list-of-essential-services-for-office"></a>Seznam osnovnih storitev za Office 

V tej tabeli si lahko ogledate seznam osnovnih storitev za Office in opis posameznih storitev.

| **Storitev**  | **Opis**  |
| ------ | ---- |
| [Preverjanje pristnosti](#authentication-events) | Preverjanje pristnosti je storitev, ki je na voljo v različnih platformah, s katero lahko preverite veljavnost identitete uporabnika v Officeu.  S to storitvijo lahko omogočite vpis v Office, aktivirate licenco za Office, dostopate do datotek, shranjenih v oblaku in zagotovite stalne izkušnje v sejah ter napravah, v katerih je nameščen Office.    |
| [Zagon s klikom](#click-to-run-events) | Zagon s klikom je tehnologija namestitev, ki se uporablja za namestitev in posodobitev Officea v sistemu Windows. Preveri, ali so na voljo nove različice Officea, in če je na voljo nova različica, jo prenese ter namesti. Zagon s klikom zazna potrebo, prenese in namesti posodobitve za Office, med drugim tudi varnostne posodobitve.     |
| [Izboljšana konfiguracijska storitev (ECS)](#enhanced-configuration-service-ecs-events) | Storitev ECS Microsoftu omogoča vnovično konfiguracijo namestitev Office, brez potrebe po vnovični uvedbi Office. Uporablja se za nadzor postopnega izdajanja funkcij ali posodobitev. Učinek izdajanja pa lahko nadzorujete z zbranimi diagnostičnimi podatki. Storitev se prav tako uporablja za preprečevanje varnostnih težav in težav z učinkovitostjo delovanja funkcije oziroma posodobitve. Storitev ECS prav tako podpira spremembe konfiguracije, povezane z diagnostičnimi podatki, ki zagotovijo zbiranje ustreznih dogodkov. |
| [Licenciranje](#licensing-events)     | Licenciranje je storitev v oblaku, ki podpira aktivacijo Office za nove namestitve in ohrani licenco v vaših napravah, po tem, ko ste aktivirali Office. Registrira posamezne naprave in aktivira Office, preveri stanje vaše naročnine na Office in upravlja vaše ključe izdelkov.    |
| [Konfiguracija storitev](#services-configuration-events)  | Konfiguracija storitev omogoča posodobitve konfiguracijskih nastavitev za Office za omogočanje oziroma onemogočanje odjemalskih funkcij. Storitev se aktivira vsakič, ko se zažene Officeova aplikacija, in zagotavlja podrobnosti o drugih konfiguracijah ter storitvah v Officeu. Storitve konfiguracije prav tako nadzorujejo, katere storitve so opredeljene kot osnovne storitve.  |
| [Telemetrija](#telemetry-events)  | Storitev telemetrije se uporablja za zbiranje diagnostičnih podatkov iz Officeovih aplikacij. Omogoča zbiranje diagnostičnih podatkov, ki jih ustvarja Office (zahtevanih in izbirnih diagnostičnih podatkov). Storitev je prav tako odgovorna za zbiranje dela diagnostičnih podatkov storitve za zahtevano storitev za Office.  |

## <a name="events-and-data-fields-for-essential-services-for-office"></a>Dogodki in podatkovna polja za osnovne storitve za Office

V naslednjih razdelkih boste naleteli na:

- Seznam dogodkov za posamezne osnovne storitve
- Opis posameznih dogodkov
- Seznam podatkovnih polj v posameznih dogodkih
- Opis posameznih podatkovnih polj

Te dogodke si lahko ogledate s pregledovalnikom diagnostičnih podatkov.



## <a name="authentication-events"></a>Dogodki preverjanja pristnosti

Ti dogodki diagnostičnih podatkov se zberejo, ko Office poskuša pridobiti žeton za preverjanje pristnosti (na tih način ali prek poziva).

### <a name="officeidentityfbapromptwin32"></a>Office.Identity.FbaPromptWin32

Dogodki se zberejo, ko Office uporabniku prikaže poziv za vpis s preverjanjem pristnosti z obrazci.

Poleg tihih pridobitev žetonom se s pozivi za preverjanje pristnosti ugotovi, ali je za uporabnika aktivirano stanje prekinjenega preverjanja pristnosti. Uporabnik se tako nahaja v stanju odjemalca brez povezave, v najslabšem primeru pa prekinjeno preverjanje pristnosti lahko povzroči pridobivanje licence in onemogoči odjemalca v celoti.

Pozivi za vpis s preverjanjem pristnosti z obrazci se uporabljajo za nekatere scenarije preverjanja pristnosti na mestu uporabe, vendar tega običajno ne želimo, ker bi uporabniki morali uporabljati sodobno preverjanje pristnosti zaradi varnostnih ranljivosti, povezanih s preverjanjem pristnosti z obrazci.

**Zbrana so sledeča polja:**

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

  - **Microsoft\_ADAL\_user\_cancel** – trditev true/false, ali je bilo preklicano okno uporabniškega vmesnika

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

  - **Data\_ProductReleaseId** – izdelek, ki ga nameščamo, npr. Office 365 ProPlus

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

  - **Data\_Sku** – inventarna številka, ki je nameščena, npr. Office 365 ProPlus.en-us

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

  - **Data\_ProductReleaseId** – izdelek, ki ga nameščamo, npr. Office 365 ProPlus

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

  - **Data\_ProductsToRemove** – katere Officeove izdelke bomo odstranili 

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

  - **Data\_ProductsToRemove** – katere Officeove izdelke bomo odstranili 

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

  - **Data\_ProductsToRemove** – katere Officeove izdelke bomo odstranili 

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

Podatki o zalogi in nastavitvi Officea, ki se zberejo, ko namestitveni program za Office namešča pisave. Dogodki se uporabljajo za merjenje uspešnosti/neuspešnosti Officeove namestitve.

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

  - **Data\_ProductsToRemove** – katere Officeove izdelke bomo odstranili 

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

  - **Data\_ProductsToRemove** – katere Officeove izdelke bomo odstranili 

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

  - **Data\_ProductsToRemove** – katere Officeove izdelke bomo odstranili 

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

  - **Data\_ProductsToRemove** –  katere Officeove izdelke bomo odstranili 

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

  - **Data\_ProductsToRemove** – katere Officeove izdelke bomo odstranili 

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

  - **Data\_ProductsToRemove** – katere Officeove izdelke bomo odstranili 

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

  - **Data\_15\_UpdateVersion** –  različica, na katero bo posodobljen Office 15 

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

  - **Data\_ProductsToRemove** – katere Officeove izdelke bomo odstranili 

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

  - **Data\_15\_UpdateVersion** –  različica, na katero bo posodobljen Office 15 

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

  - **Data\_ProductsToRemove** –  katere Officeove izdelke bomo odstranili 

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

  - **Data\_ProductsToRemove** – katere Officeove izdelke bomo odstranili 

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

  - **Data\_15\_UpdateVersion** –  različica, na katero bo posodobljen Office 15 

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

  - **Data\_ProductsToRemove** – katere Officeove izdelke bomo odstranili 

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

  - **Data\_ProductsToRemove** – katere Officeove izdelke bomo odstranili 

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

  - **Data\_ProductsToRemove** – katere Officeove izdelke bomo odstranili 

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

  - **Data\_ProductsToRemove** –  katere Officeove izdelke bomo odstranili 

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

  - **Data\_ProductsToRemove** – katere Officeove izdelke bomo odstranili 

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

  - **Data\_ProductsToRemove** – katere Officeove izdelke bomo odstranili 

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

  - **Data\_ProductsToRemove** – katere Officeove izdelke bomo odstranili 

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

  - **Data\_ProductsToRemove** – katere Officeove izdelke bomo odstranili 

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

  - **Data\_ProductsToRemove** –  katere Officeove izdelke bomo odstranili 

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

  - **Data\_15\_UpdateVersion** –  različica, na katero bo posodobljen Office 15 

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

  - **Data\_ProductsToRemove** – katere Officeove izdelke bomo odstranili 

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

  - **Data\_15\_UpdateVersion** –  različica, na katero bo posodobljen Office 15 

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

  - **Data\_ProductsToRemove** – katere Officeove izdelke bomo odstranili 

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


## <a name="enhanced-configuration-service-ecs-events"></a>Dogodki izboljšane konfiguracijske storitve (ECS)

### <a name="officeexperimentationfeaturequerybatched"></a>Office.Experimentation.FeatureQueryBatched

Zbere informacije o vratih funkcije/vratih spremembe, ki jih poizvede izvedena koda.

Zbrana so sledeča polja:

  - **Count** – število poizvedenih vrat funkcije v tem paketnem dogodku

  - **Features** – informacije o poizvedenih vratih

  - **Sequence** – vrstni red, v katerem so bila poizvedena vrata FeatureGate

### <a name="officeexperimentationflightnumberline"></a>Office.Experimentation.FlightNumberLine

Zbere seznam konfiguracij, ki jih odjemalec prejeme od storitve ECS

Zbrana so sledeča polja:

  - **ECSConfigs** – seznam konfiguracij za ECS (vrednosti so med seboj ločene z vejico)

  - **LockType** – vrsta zaklepa FlightManager

  - **TasFlightingVersion** – številka različice

  - **TimeToLock** – čas med začetkom libleta in zaklepom za FlightManager

  - **UnmergedConfigs** – seznam konfiguracij, ki niso spojene


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

Ti podatki so zbrani pri vsaki seji, ki sporoča stanje licenciranja v računalniku in sporoča napake, ki se prikažejo uporabniku, zaradi katerih, ne morejo uporabljati aplikacijo. Ta dogodek ponazarja, ali je stanje računalnika uporabnika primerno. Za ta dogodek smo vzpostavili zaznavanje anomalije, s katerim ugotovimo, ali regresija povzroča nepravilno delovanje uporabnika. Ta dogodek je pomemben tudi pri diagnosticiranju težav uporabnika in za nadziranje zdravja sistema.

Zbrana so sledeča polja:

  - **Acid** – identifikator GUID, ki predstavlja Officeov izdelek, za katerega je uporabnik prejel licenco 

  - **IsSessionLicensing** – ali je izbran način za aktivacijo računalnika v skupni rabi 

  - **LicenseCategory** – kategorija Officeove licence, ki jo uporabnik uporablja 

  - **Licenses** – seznam imen vseh Officeovih licenc, ki so bile zaznane v računalniku 

  - **LicenseStatuses** – stanje vseh Officeovih licenc, ki so bile zaznane v računalniku 

### <a name="officelicensinggetentitlement"></a>Office.Licensing.GetEntitlement 

Te podatke zberemo, ko uporabnik nastavi napravo in pokličemo storitev licenciranja, da zazna, ali je prijavljeni uporabnik upravičen do Officea ali ne. Da dogodek vrne rezultat klica. Dogodek je pomemben pri zaznavanju, ali je uporabnik v dobrem stanju in nima omogočene vse funkcionalnosti; uporabljajo se za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Ta dogodek ne zbere nobenega polja.

### <a name="officelicensingheartbeat"></a>Office.Licensing.Heartbeat 

Za vsako sejo preverimo, ali je minilo 72 ur od zadnje obnovitve licence, in poskušamo podaljšati potek trenutne licence. S pomočjo tega dogodka lahko ugotovimo uspeh/neuspeh klica, s katerim potrdimo, da lahko podaljšamo potek licence in omogočimo funkcionalnost Officea, ki ga je namestil uporabnik. Pri diagnosticiranju težav, povezanih z naročnino, in težav storitev je ta dogodek ključen za uporabnika in pri zaznavanju regresij za že aktitivrane uporabnike naročnine.

Zbrana so sledeča polja:

  - **Mode** – predstavitev orodja za oštevilčenje zbirke za licenciranje Officea, ki se uporablja v tem računalniku

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

  - **Office.Licensing.NextUserLicensingEligible** – ta signal nam sporoča, ali uporabnik izpolnjuje ustrezne pogoje za prehod na novo zbirko licenciranja. To je pomembno pri količinskem vplivu na obstoječe uporabnike, ko uvajamo novo zbirko licenciranja, ter da se prepričamo, da uporabniki ne izgubljajo na funkcionalnosti.

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

### <a name="officelicensingpurchase"></a>Office.Licensing.Purchase 

Preskus, s katerim uporabniku omogočimo samodejno plačevanje za Office neposredno iz aplikacije, ne da bi za to moral zapreti aplikacijo. Ta dogodek ponazarja uspešnost/neuspešnost poskusa skupaj s kodo napake. Dogodki so pomembni pri zaznavanju, ali je uporabnik v dobrem stanju in ima omogočeno vso funkcionalnost, se uporabljajo za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Zbrana so sledeča polja:

  - **StorePurchaseStatus** – predstavlja kodo napake/kodo uspeha za klic nakupa, ki je bil izveden prek Trgovine Windows

### <a name="officelicensingsearchforsessiontoken"></a>Office.Licensing.SearchForSessionToken

Če je uporabnik izbral način za aktivacijo računalnika v skupni rabi, v računalniku poskušamo poiskati žeton seje, ki uporabniku omogoča uporabo aplikacije. Ta dogodek ponazarja scenarij uspešnosti/neuspešnosti licenciranja skupaj s kodo napake. Dogodki so pomembni pri zaznavanju, ali je uporabnik v dobrem stanju in ima omogočeno vso funkcionalnost, se uporabljajo za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Zbrana so sledeča polja:

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

### <a name="officelicensingusegracekey"></a>Office.Licensing.UseGraceKey

Če iz neznanega razloga nismo uspeli licencirati uporabnika, namestimo ključ za dovoljeno obdobje in pošljemo ta signal. Dogodek je pomemben pri zaznavanju, ali je uporabnik v dobrem stanju in nima omogočene vse funkcionalnosti; uporabljajo se za stanje sistema in za diagnostične namene, ko uporabnik prijavi težavo z računalnikom.

Zbrana so sledeča polja:

  - **OpportunisticTokenRenewalAttempted** – označuje, ali smo priložnostno poskušali obnoviti licenco za uporabnika v način za aktivacijo računalnika v skupni rabi

  - **ReArmResult** – označuje rezultat vrnitve v obdobje pred aktiviranjem nameščenega ključa, s katerem je mogoče razširiti trenutno licenco

## <a name="services-configuration-events"></a>Dogodki za konfiguracijo storitev

Konfiguracija storitev ne zbira nepotrebnih dogodkov diagnostičnih podatkov storitve.

## <a name="telemetry-events"></a>Dogodki telemetrije

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

  - **IsDebug** – ali je to gradnja Officea za odpravljanje napak

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

  - **PreviousBuild** – različica Officea, iz katere je bila ta gradnja nadgrajena ali povrnjena na prejšnjo različico.

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

  - **DeviceClass** – identifikator za vrsto naprave, v kateri se izvaja Office

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

<!-- end list -->

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

  - **PreviousBuild** – različica Officea, iz katere je bila ta gradnja nadgrajena ali povrnjena na prejšnjo različico.

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

Dogodek se uporablja za metrike zrušitev.

Zbrana so sledeča polja:

  - **CrashedProcessAppBuild** – identifikator delovne različice za vplivani proces

  - **CrashedAppMajor** – identifikator glavne različice za vplivani proces

  - **CrashedAppMinor** – identifikator manjše različice za vplivani proces

  - **CrashedAppRevision** – identifikator delovne različice za vplivani proces

  - **CrashedConfigIds** – konfiguracija, dodeljena procesu zrušitve

  - **CrashedEcsETag** – identifikator preskusa za proces zrušitve

  - **CrashedImpressionId** – identifikator vtisa za proces zrušitve

  - **CrashedModuleName** – ime modula z napako

  - **CrashedSessionID** – enolični identifikator procesa zrušitve

  - **CrashedSessionInitTime** – čas, ko se je začel vplivani proces

  - **CrashType** – identifikator razdeljevanja za vrsto zrušitve

  - **DetectionTime** – čas, ko je bil zaznan nepričakovani izhod

  - **ExceptionAddress** – mesto v programu, kjer je prišlo do napake

  - **ExceptionCode** – identifikator razdeljevanja za izjemo

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

  - **PreviousBuild** – prejšnja nameščena delovna različica

  - **UAEOSEnvironment** – identifikator okolja za operacijski sistem

  - **VerifyElseCrashTag** – enolični identifikator za mesto zrušitve aplikacije

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

Zbrana so sledeča polja:

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
