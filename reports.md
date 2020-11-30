<p align="center">
  <img src="./resources/logo_ball_black.svg" width="180">
  <br/>
  <a href="https://ecsolutions.se/om-oss/" style="font-size:48px;color:black">EC Solutions</a>
</p>

<br/>
<br/>
<br/>

# Innehållsförteckning <!-- omit in toc -->

+ [Sammanfattning](#sammanfattning)
+ [Inledning](#inledning)
  + [Syfte och Mål](#syfte-och-mål)
  + [Presentationsformat](#presentationsformat)
+ [Frontendutveckling hos EC Utbildning](#frontendutveckling-hos-ec-utbildning)
+ [EC Solutions &mdash; Trust the Experts!](#ec-solutions--trust-the-experts)
+ [Simplr](#simplr)
+ [Veckoindelad Rapportering](#veckoindelad-rapportering)
  + [_Vecka 1_](#vecka-1)
    + [End of Line](#end-of-line)
    + [Docker](#docker)
  + [_Vecka 2_](#vecka-2)
    + [Analys av Datumsträngar](#analys-av-datumsträngar)
    + [Windows Terminal](#windows-terminal)
    + [Windows Subsystem for Linux (WSL)](#windows-subsystem-for-linux-wsl)
  + [_Vecka 3_](#vecka-3)
    + [WYSIWYG - What you see is what you get](#wysiwyg---what-you-see-is-what-you-get)
  + [_Vecka 4_](#vecka-4)
    + [Clean Code with Uncle Bob](#clean-code-with-uncle-bob)
    + [Deep Dive into Git](#deep-dive-into-git)
  + [_Vecka 5_](#vecka-5)
    + [Service Worker](#service-worker)
    + [Web Application Manifest](#web-application-manifest)
  + [_Vecka 6_](#vecka-6)
    + [Laravel](#laravel)
  + [_Vecka 7 och 8_](#vecka-7-och-8)
    + [TLS](#tls)
    + [Floating-point error](#floating-point-error)
  + [_Vecka 9_](#vecka-9)
    + [Subtitle](#subtitle)
  + [_Vecka 10_](#vecka-10)
    + [Subtitle](#subtitle-1)
  + [_Vecka 11_](#vecka-11)
    + [Subtitle](#subtitle-2)
+ [Reflektion och Slutsats](#reflektion-och-slutsats)

<br>
<br>

# Sammanfattning
<br>

- Kommunkation, intern och extern
- Manuell testning av kod
- Lärande tar aldrig slut

<br>
<br>

# Inledning
<br>

## Syfte och Mål 
<br>

Som en del av programmet Frontendutveckling ingår två LIA-perioder (Lärande i Arbete) som innebär praktiktjänstgöring ute hos företag, med syfte att samla arbetslivserfarenhet innan examination. Både för att få insikt i vad yrkesrollen faktiskt innebär efter skolbänken och att få använda de kunskaper som förvärvats genom utbildningen. Mina mål är att fördjupa mig ytterligare i hela webbutvecklingsprocessens generellt och React-biblioteket specifikt.

<br>

## Presentationsformat
<br>

Min rapportering av tiden hos EC Solutions är presenterat veckovis. Varje rapport består av en huvuddel som en omfattande summering av veckan som varit. I slutet av varje veckorapport inkluderas i punktform kortare analyser, reflektioner, diskussioner eller presentationer relevanta till veckan som gått.

Rapporten är skriven i språket [Markdown](https://www.markdownguide.org/getting-started/) som är ett formateringsspråk för textdokument. Till skillnad från textredigeringsprogram som Microsoft Word och Apache Open Office där du ändrar inställningar för formatering genom att klicka på knappar, välja från en rullgardinslista eller kryssa i en checklista, så [används speciella tecken för att definiera formatering](https://www.markdownguide.org/basic-syntax/). Detta är en industristandard för att skriva både dokumentation och rapporter inom, men inte begränsat till, systemutveckling. Formateringen är även populär bland bloggare och författare [eftersom det är plattformsagnostiskt](https://www.markdownguide.org/getting-started/#why-use-markdown), eftersom det i grunden bara är vanlig text.

Två stora fördelar som ofta nämns är just att det går att öppna och redigera Markdown-filer i vilket textredigeringsprogram som helst, eftersom det bara är ren text, till skillnad från exempelvis filer skapade med Microsoft Word (.docx) eller Apache OpenOffice (.odt). Markdown stöds även helt eller delvis i webbapplikationer som exempelvis [Slack](https://www.markdownguide.org/tools/slack/) och [stackoverflow](https://stackoverflow.com/).

<br>
<br>

# Frontendutveckling hos EC Utbildning
<br>

[Kreativitet, glädje och resultat](https://www.ecutbildning.se/om-ec/). Med dessa värdeord som grund strävar EC Utbildning att på bästa sätt förbereda intagna studenter för sina framtida yrkesroller. Genom kontinuerlig utvärdering och revidering av kursplaner och en nära relation till näringslivet kan bolaget försäkra sig om att elever får de kunskaper som efterfrågas i dagsläget. Ett smart drag som oftast leder till kvick anställning efter examen.

När jag lämnade in en sen anmälan under sommaren 2019 förstod jag inte hur lite jag visste om frontendutveckling, eller hur mycket jag skulle komma att få lära mig under det kommande året. Men vad jag visste efter att jag fick mitt positiva antagningsbesked var att jag verkligen ville dedikera min studietid åt att bli duktig på det. Vad som höll min motivation uppe var att jag konstant utmanades av ett högt men ändå hanterbart tempo, ett relevant kursmaterial och våra föreläsare, både kunniga och roliga.

Efter LIA-perioden var över stod mitt mål oförändrat. Jag ville fortfarande bli så duktig jag möjligtvis kunde bli. Den stora skillnaden var att jag hade en klar bild över både hur lite jag visste, och hur mycket jag faktiskt hade lärt mig.

<!-- @TODO nyfikenhet -> intresse -->
<!-- @TODO webbutveckling -> systemutveckling -->

<br>
<br>

# EC Solutions &mdash; Trust the Experts!
<br>

Företaget med kontor i Helsingborg, på första parkett mot Tropical Beach och således havet, tillsammans med människor som utstrålar kompetens och välvilja får en att känna sig varmt välkommen här. Även de dagar då diset ligger tjockt över Öresund och duggregnet piskar ansiktet värms man snabbt av en kopp nybryggt kaffe och en härlig atmosfär. En atmosfär präglad av känslan av att något är på gång, något skapas. Där finns en tydlig yrkesstolthet och passion för kunskapsutbyte.

<br>

> Vi stöder utvecklande företag med experttjänster inom mjuk- och hårdvaruutveckling, projektledning samt åtagande och leverans av helhetsuppdrag. Det självklara valet när ni står inför utmaningar och behöver teknikförstärkning!

<br>

Citatet ovan återfinns på [EC Solutions hemsida](http://www.ecsolutions.se/). Bolaget, som främst bedriver konsultverksamhet och rekrytering, har också ett arbetslag som arbetar inhouse på kontoret i Helsingborg vilket jag har varit en del av under LIA-perioden.

Inhouseavdelningen är mångsysslare som håller på med allt inom webbutveckling, maskininlärning och hårdvaruutveckling samt 3D-utskrift. Det sistnämnda har använts för att exempelvis [donera skyddsskärmar](https://www.linkedin.com/feed/update/urn:li:activity:6654020438877847552/) åt sjukvården.

<br>
<br>

# Simplr
<br>

Företagets affärsidé är att bistå och sköta bland annat frisersalonger där stolar kan bokas av frisörer för att utföra sitt arbete. Detta ger en stor frihet för frisörer som slipper allt ansvar och administration som rör lokaler, betalning och marknadsföring bland annat, i utbyte mot en avgift för varje utförd klippning.

Projektet jag har varit delaktig i under hela perioden är en progressiv webbapplikation åt det nystartade företaget [Simplr, ett systerbolag till Gents](https://simplr.se/about). Vi arbetade tillsammans med Gents utvecklingslag inför lanseringen av applikationens betaversion och de ansvarar för produktionssättningen av de fixar och funktioner vi implementerar. Projektet och majoriteten av kodbasen på plats när jag kom in i projektet togs över efter en polsk firma som inte hade kunnat leverera i tid. Dessvärre var produkten inte bara långt ifrån färdig, utan det som producerats var undermåligt.

Där rådde ingen officiellt etablerad arbetsprocess, utan det som gällde var att på snabbast sätt få ut en MVP-version (_Minimum viable product_) av produkten.

<br>
<br>

# Veckoindelad Rapportering
<br>

## _Vecka 1_
<br>

Veckan innan jag började hade jag fått en generell beskrivning av projektet jag initialt kom att arbeta med: 

> _"... onödigt komplexa abstraktionslager, fylld av buggar och går ut i produktion nästa måndag."_

<br>

_"Kul,"_ tänkte jag direkt.

Måndagen började med att jag, guidad av min handledare, skulle sätta upp utvecklingsmiljön på min dator så att jag kunde tilldelas *tasks* från kanban-brädan på Trello. Eftersom att jag var den enda i arbetslaget som använde operativsystemet Windows fanns där en hel del saker som inte fungerade med konfigurationen av utvecklingsmiljön. Tillsammans med en senior kollega betades fel efter fel av fram tills att vi fått igång både backend och klient. Som bonus kunde vi dessutom dela med till produktägaren och projektledaren vad för slags ändringar av konfigurationen som krävdes. Skulle där i framtiden komma in fler utvecklare med Windows skulle de i så fall inte stöta på samma problem.

Resten av dagen spenderade jag på att sätta mig in i projektets arkitektur eftersom kodens abstraktionsgrad var väldigt hög, vilket var en av orsakerna till dess komplexitet. Exempelvis var komponenternas namngivelser otydliga samtidigt som koden var extremt uppdelad utan att vara generaliserad. Så för att göra något väldigt enkelt var man tvungen att ändra lite kod i väldigt många filer.

På tisdagen började ta på mig uppgifter från kanban-brädet, och därefter rullade veckan på rätt så bra för min del och bestod mestadels av att skriva enkla algoritmer, fixa buggar och att förbättra användareupplevelsen med hjälp av att implementera ny gränssnittsdesign.

_Frihet under ansvar_; ett talesätt jag kom att tänka på mot slutet på första veckan, vilket kommer att prägla resten av LIA-perioden.

Efter en slitsam vecka med långa dagar så var produkten på fredagen stabil nog att en demo kunde visas upp för slutkunder på måndagen.

<br>
<br>

### End of Line

Med _end of line_ syftar man som namnet tyder på en radändelse. Det är viktigt att känna till detta eftersom radändelser fungerar olika på olika system, och kan skapa stora och svårfunna problem exempelvis när ett operativsystem med UNIX-kärna ska köra en shell-fil skriven i ett operativsystem med DOS-kärna.

<br>
  
### Docker

<!-- @ TODO -->

<br> 
<br>

## _Vecka 2_
<br>

Den andra veckan började som den första slutade. Jag fortsatte med att hjälpa till och avverka uppgifter som låg i prio-listan på Trello, samtidigt som jag vidareutvecklade föregående funktionalitet jag lagt till så fort feedback kom tillbaka på dem. Något som jag tyckte var mycket nyttigt och ofta snabbt kunde lösa.

Mot veckans slut hade jag tröttnat rejält på att min dator var så oerhört långsam. Under hela tiden fram tills nu så låg datorns minneskonsumption på 95~99% medan jag arbetade på projektet, och listade då ut att det var Docker-Engine som var boven i dramat. Jag lade temporärt arbetet åt sidan för att kunna felsöka problemet, så att jag senare kan arbeta mer effektivt. Windows Subsystem for Linux studerades noggrant, systemet som möjliggör så att Docker kan köras på Windows, och kom fram till att lösningen på problemet var tvådelat: installera Ubuntu som är ett operativsystem för Linux och strypa de resurser som Docker har tillgång till.

Genom Ubuntu ökades effektiviteten på Docker-Engine vilket gjorde att jag kunde begränsa minnet och antalet processorkärnor som motorn kunde använda sig av _**utan**_ att tappa prestanda på utvecklingsservern, och efter det var min effektivitet inte begränsad av datorns kapacitet längre. Vilket kommer spara mig många timmar och frustration under resten av LIA-perioden.  

<br>

### Analys av Datumsträngar

`Date.parse()`-metoden som körs när du kallar på deklarerar ett ny instans av `Date`-klassen med ett strängargument, har [ett väldigt inkonsekvent beteende](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/parse) och fungerar exempelvis annorlunda i Safari jämfört med andra webbläsare. Därför bör alltid `Date`-konstruktorn kallas med nummer-argument för att vara säker på samma resultat oberoende av webbläsare. Fördelen med att göra detta är att webbläsarspecifik felhantering kan utelämnas.

<br>

_Exempel på användning_

```javascript
new Date("1988-12-20") // Osäker instatiering
new Date(1988, 12, 20) // Säker instatiering
```
 
<br>

### Windows Terminal

En fantastisk terminal för Windows med anpassningsbara teman, flikar och enkel konfiguration. Gör det betydligt enklare och roligare att arbeta med verktyg som docker, live servrar och versionshanteringssystem simultant.

<br>

### Windows Subsystem for Linux (WSL)

WSL är ett kompabilitetslager för att kunna exekvera binära Linux-program. Byggt på Hyper-V som är skapat av Microsoft för att kunna skapa virtuella miljöer. Något som bör göras för varje projekt med mer än en tänkt utvecklare. För att konfigurera sin dators resurser som WSL får lov att tillgå så skapar man en `.wslconfig` i sin användarmapp. Begränsas inte dessa resurser kommer den virtuella miljön helt enkelt ta så mycket som finns tillgängligt och reservera detta om det skulle behövas. Något som absolut är fördelaktigt för en server, men inte för en lokal miljö på samma moderkort som utvecklingsarbete sker.

<br>

_Exempel på en enkel .wslconfig-fil_

```
[wsl<versionsnummer>]
memory=<nummer>GB
processors=<nummer>
swap=<nummer>GB
```

<br>
<br>

## _Vecka 3_
<br>

Veckan börjar med en _release lunch_ hos kunden vilket var väldigt trevligt. Särskilt roligt var det att få sätta ansikten på alla involverade i projektet som vi har bollat idéer och problemlöst tillsammans med på distans fram tills nu. En ren social tillställning där vi fick lära känna varandra närmre och diskussion kring jobb aktivt undveks.

Väl tillbaka på kontoret tar en senior kollega upp vissa problem med den nuvarande arbetsprocessen som till stora delar rör Git, men också implementering av saker som översättningar och dynamiskt skapade sidor. Vi bestämmer oss för att ta upp en del åsikter med kunden, för att se hur de prioriterar. Senare i veckan bestäms ett nytt flöde för Git som vi internt inte håller med om är nödvändigt och anser bara bidrar till en mer svårhanterligt flöde, men som vi rättar oss efter. Personligen hade jag ingen åsikt på grund av min bristande erfarenhet gällande Git och de olika arbetsmetodiker kopplade till det, men glädes ändå för den nyligen fastställda processen eftersom det innebar att jag skulle få möjlighet att lära mig ännu mer om Git.

Det nya arbetsflödet innebar att varje utvecklingslag som kommer att jobba mot samma projekt klonar koden som ligger i produktionsstadiet huvudgren till en egen kodförvaring, hädanefter _repo_ (förkortat från _repository_ som betyder _förvaring_). Efter det klonar var utvecklare själv ned lokalt huvudgrenen för sitt lags repo, och grenar utifrån den när en ny uppgift ska tas an och namnger grenen med typ av uppgift och namnges koncist. Arbetar man exempelvis med att fixa en bug som ska lösa ett problem som uppstår i en betalningsfunktion så kan den heta `fix/payment-handler`. Namnet på grenen är bara viktigt tills det att den förenas med huvudgrenen; när uppgiften anses vara slutförd tas den bort efter förening.

<br>

_Exempel på det nya flödets livscykel för en uppgift och utgår från ens lokala huvudgren_
```shell
git checkout -b <namn>

// Utför uppgift

git add <sökväg>
git commit -m "<beskrivning>"

// Ifall pre-commit hooken hittar problem så ska de lösas här och följs sen av de kommenterade kommandona nedan
// git add <sökväg>
// git commit --amend --no-edit

git fetch upstream --all
git rebase upstream/master

// Lös eventuella krockar med kod i produktionsbasen
// git add <sökväg>
// git rebase --continue

git push origin <namn>

// Skapa en föreningsbegäran och delge projektansvarig

git checkout <huvudgren>
```

<br>

Flödet motiverades i slutändan av viljan att ha en helt linjär historik över commits i produktionsträdet, något som används flitigt inom _Open Source_-communityn. Ytterligare ett skäl till att jag blev exalterad över just denna metodiken valdes då jag under ett tag nu varit intresserad av att bidra till diverse projekt.

<br>

### WYSIWYG - What you see is what you get

En fras som kanske inte alltid kopplas samman med systemutveckling. I detta fall handlar det om ett textredigeringsverktyg i ett innehållshanteringssystem (_CMS: Content Management System_), som låter en användare redigera text likt Microsoft Word, Apache OpenOffice eller Libre Office. All formatering, som typsnitt, teckenstorlek och stil, konverteras direkt till HTML och CSS och lagras i en databas för att sedan hämtas som innehåll till en av sidorna i en webbapplikation till exempel.

<br>
<br>

## _Vecka 4_ 
<br>

Under denna veckan var jag rätt så sjuk tre av dagarna, men eftersom alla jobbar hemifrån gick det ändå bra och jag fick gjort mycket under omständigheterna. Tech Lead sade åt mig att vila om det började kännas för tungt, vilket det ibland gjorde med en rejäl snuva och tung huvudvärk. Dessa stunder lyssnade jag på podcasts eller såg på föreläsningar som hade med programmering att göra, varav två som jag starkt rekommenderat till resten av mina kurskamrater.

Jag spenderade även mycket tid med att övergå till en ny utvecklingsmiljö (_IDE: Integrated Development Environment_), [PhpStorm](https://www.jetbrains.com/phpstorm/), som _out-of-the-box_ är mer lämpat för programmering i språket _PHP_ jämfört med Visual Studio Code vilket jag är van vid. PHP var en sak jag uttryckt intresse av att få sätta mig in i när det ansågs finnas tid till det, eftersom ett populärt ramverk som ofta används är skrivet i just detta. 

Att byta till en annan miljö var lite jobbigt eftersom att jag initialt var mycket långsammare och allt var nytt, exempelvis snabbkommandon, gränssnitt och i detta fall även det faktum att jag skulle bli bekväm i en helt ny syntax. I efterhand vet jag inte om bytet var nödvändigt eftersom all funktionalitet finns i Visual Studio Code så länge det konfigurerats korrekt. Samtidigt så skadar det absolut inte med erfarenhet av olika plattformar och det kändes vettigt att konformera sig till PhpStorm när det är en gedigen IDE som dessutom kostar rätt mycket.

<br>

### Clean Code with Uncle Bob

Robert C. Martin, ofta känd som _Uncle Bob_, är en väldigt känd mjukvaruutvecklare och författare. Som en av agil projektmetodiks högst ljudande språkrör, föreläser han i dag om ett gemensamt åtagande gällande att etablera en principiell standard för både etik och moral. Något han menar bör anammas av alla som kallar sig för professionell utvecklare. I flera av sina böcker och [denna samling av föreläsningar](https://www.youtube.com/watch?v=7EmboKQH8lM&t) förklarar han att eftersom denna yrkesroll fortfarande är relativt ung, har vi i detta ämbete inte än blivit direkt relegerade av lagar, vare sig internationella eller nationella. Men att detta kommer ske inom en snar framtid, och det är då bättre om vi själva kommit till ett konsensus gällande den regeluppsättning vi vill förhålla oss till. För att uppnå detta så definierar han alltså flera olika principer som en utvecklare bör förhålla sig till, och kallar denna sammanställning för _ren kod_.

<br>

### Deep Dive into Git

NDC Conferences är en organisation som fokuserar på att erbjuda föreläsningar med högkvalitativt innehåll relaterat för utvecklare inom alla olika system. Just i Oslo, 2017, höll Edward Thompson [en omtalad sådan](https://www.youtube.com/watch?v=fBP18-taaNw) som ofta rekommenderas för att som ny till Git och versionshanteringssystem få en djupare inblick i vad som faktiskt händer när man skriver Git-kommandon.

<br>
<br>

## _Vecka 5_
<br>

Under helgen uppdagades ett stort problem som visade att en del av ändringarna som produktionssatts inte hade nått våra slutanvändare. Till skillnad från andra veckor som varit helt fria från formella möten, satte vi oss ned tillsammans i ett försök att specifiera problemet. Applikationen både såg ut och fungerade som väntat när vi granskade projektet. Inte bara lokalt utan även i produktion. Senare under dagen visade det sig att endast en del kunder var påverkade, och vi kunde snabbt deducera att det antagligen rörde sig om cachning. Eftersom det är en PWA vi arbetar med så [cachas sidostruktur, stilark och svarsdata](https://developer.mozilla.org/en-US/docs/Web/API/Cache) från HTTP-anrop av en [servicearbetare](https://developer.mozilla.org/en-US/docs/Web/API/ServiceWorker). En snabb granskning av servicearbetarens konfiguration gav oss svaret; cachningens livstid var satt till en alldeles för lång period. Justeringar gjordes och drabbade kunder uppmanades att installera om applikationen ifall den fortfarande inte fungerade.

Vad som annars låg framför mig denna veckan var ett omarbete av applikationens sökvägar och vyer. Fram tills denna tidpunkt har mycket data skickats mellan sidor via `<Link>`-komponententer som ett tillståndsattribut på `to`-objektet. Detta medför endast krav på extra felhantering och omöjliggör direktlänkar till vyer som beror på sådan data utan att blanda in `localStorage`-API:et. Omarbetet som var rätt så omfattande innebar alltså att datan skulle deriveras utifrån webbadressen.

Genom att introducera parametrar såsom identifikationsnummer och söksträngar med väsentliga nyckelvärden i webbadresser kan dessa sen användas för att hämta korrekt data från vår backends REST-server; en vanlig metod för att rendera sidor inte minst i React-biblioteket, som valts bort av utvecklarna som inlett projektet.

<br>

### Service Worker

En simpel förklaring om hur tekniken fungerar är att den agerar som en mellanhand mellan webbapplikationer och nätverk (oftast internet). Genom att fånga all utgående och inkommande kommunikation och spara denna i närminnet kan det blixtsnabbt hämtas vid ett senare tillfälle. På så sätt möjliggörs offline-läge för appen, så att även om datan inte är helt uppdaterad och du inte kan ladda ned ny data så kan fortfarande alla besökta sidor återskapas från cache-minnet.

Ett bra sätt att förstå tekniken på är att läsa [en introduktion till konceptet](https://developers.google.com/web/fundamentals/primers/service-workers) och sedan fortsätta med [dokumentationen på MDN](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API) som har flera bra exempel.

<br>

### Web Application Manifest

För att en PWA ska vara installerbar krävs en fil som i breda drag beskriver applikationen. Där finns olika filformat denna konfiguration kan skrivas i, där det är vanligast att i ett projekts rotmapp skapa en `manifest.json`-fil. Anmärkningsvärt så skriver W3C att [den officiella filändelsen är `.webmanifest`](https://www.w3.org/TR/appmanifest/#using-a-link-element-to-link-to-a-manifest), vilket är betydligt ovanligare. [En intressant diskussionstråd på GitHub](https://github.com/w3c/manifest/issues/689#issuecomment-396822052) tar upp vissa punkter kring skillnaderna mellan de två.

<br>
<br>

## _Vecka 6_
<br>

Hittills hade mitt deltagande i projektet helt och hållet varit inriktat mot frontend. Men på eget bevåg hade jag även orienterat mig runt en hel del i backend, närmre bestämt själva REST API:et. Vid detta laget kunde jag det så pass bra att jag vågade be om att få prova göra uppgifter relaterade till den delen av projektet. Något de valde att blidka mig angående.

Så jag skred till arbete, vilket innebar ändringar av kunds fakturor. Både layout och presenterad data skulle justeras enligt de nya önskemålen. Ett arbete som omfattade Blade-mallar för layout och controllers, services och resources för logik och modellering. Enligt mig, så pendlar man väldigt ofta mellan två olika känslor under tiden man programmerar. Ena stunden kan det kännas bekvämt och tryggt för att allt känns igen, andra stunden har något gått fel och känslan har hastigt bytts mot förvirran. Denna förvirran blir lätt mycket större framför en ovan syntax, såsom PHP, språket vår backend är skrivet i, var för mig.

Efter en del orientering hade jag funnit var och vad jag behövde för att genomföra de justeringar som efterfrågades. 

<br>

### Laravel

Ramverket består av många delar som tillsammans bildar en komplett verktygslåda för att bygga webbapplikationer. I stark kontrast mot exempelvis [Express](http://expressjs.com/), så kräver Laravel att man tar efter de principer och den metodik som främjas. Går man ifrån det utstakade arbetssättet så blir det väldigt rörigt, något jag fick uppleva i detta projektet. Däremot har jag också fått ta del av hur modulärt och underhållbart det kan vara.

<br>
<br>

## _Vecka 7 och 8_
<br>

Efter mycket bollande mellan kunden, UX/UI-designer, och vår egen Tech Lead, kom ett slutgiltig prototyp av appens nya kartvy. Precis som allt annat i kodbasen var även denna vy med sammanhörande komponenter skrivna på ett omodernt, otydligt och ineffektivt sätt. Exempelvis gjordes det onödigt många anrop vid instantiering eftersom att vyn renderades utan att vänta in populering av grundläggande data, och presentationen av tillgängliga bokningstider var inte byggt på ett sätt som gjorde användandet intuitivt. Där fanns alltså skäl till att göra om allt, och med tanke på renoveringens omfattning så kunde vi nu börja avvika från den arkitektur som präglade projektet.

<br/>
<br/>

<p align="center">
  <img src="./resources/map-view-prototypes.png" width="80%"><br/>
  <em style="font-size:12px">Prototyper för kartvyns olika tillstånd.</em>
<p>

<br/>
<br/>



<br>

### TLS
localhost = secure context / SSL => TLS https://developer.mozilla.org/en-US/docs/Web/Security/Secure_Contexts

### Floating-point error
https://docs.oracle.com/cd/E19957-01/806-3568/ncg_goldberg.html

<br>
<br>

## _Vecka 9_
<br>

Content

<br>

### Subtitle

<br>
<br>

## _Vecka 10_
<br>

Content

<br>

### Subtitle

<br>
<br>

## _Vecka 11_
<br>

Content

<br>

### Subtitle

<br>
<br>

# Reflektion och Slutsats