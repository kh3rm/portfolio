---
Title: Colors and Fonts Analysis
Description: An analysis of three websites choice of colors and fonts.
---

<h1 class="about-rubric">Colors and Fonts Analysis</h1>
<br>
I den här, den första av de analysuppgifter som kommer att genomföras under de sista kursmomenten, ska vi ta oss en närmare titt på tre utvalda webbplatser, och mer specifikt deras val av färger och typsnitt.

Syftet är tveeggat: som en övning i att läsa av och strukturellt kartlägga hemsidors färg- och typsnittsval, understödda av ändamålsenliga verktyg och tekniker, och att med den konkreta grunden på plats analysera och reflektera över:

Hur bra tycker vi att de har lyckats med deras val?

Upplevs sidorna som färgmässigt väl sammansatta och harmoniska?

Bidrar de typografiska avvägningarna de har gjort till ett textmässigt resultat som är stilfullt, läsvänligt och tydligt att interagera med?

Finns det förbättringspotential?

<h2 class="sub-rubric">Urval</h2>

De tre webbplatser som jag har valt att ta mig en närmare titt på är:

- [Rouleur](http://www.rouleur.cc) - brittisk cykelsajt/cykelmagasin.
- [Chessbase](http://www.chessbase.com) - en sida för schacknyheter, statistik och partianalyser.
- [FIDE](http://www.fide.com) - det internationella schackförbundets hemsida.

Den första som ett exempel på en modern, stilmedveten sida, som jag vid en första anblick upplever har lyckats väldigt bra när det gäller dessa balansgångar.

De senare för att inkludera två sidor som kretsar kring samma huvudämne: schack i det här fallet, men med olika profiler, teman och roller, för att se hur det i sin tur kan komma att påverka de val de gör, och kanske även hur mycket kreativ frihet de tillåter sig.

<h2 class="sub-rubric">Metod</h2>

Den här typen av stickprov gör man kanske mest direkt och naturligt med en webbläsares developer-tools, där de relevanta elementen kan inspekteras.

Jag väljer att använda mig av Firefox, och för att på ett mer laserfokuserat sätt kunna identifiera färgerna, tar jag hjälp av ColorZilla, en tacksam Firefox-extension.

Typsnitten, som också de visserligen kan identifieras med endast devtools, kartläggs här på ett smidigare sätt med hjälp av WhatFont, ytterligare ett behjälpligt Firefox-tillägg.

Respektive sidoanalys kompletteras med skärmbilder, och färgschemat representeras i en färgpalett.

För att skala ned skärmbilderna till en mer lämplig storlek, har jag använt mig av https://picresize.com.


<h2 class="sub-rubric">Resultat och Analys</h2>

<h2 class="analysis-site-rubric">Rouleur.cc</h2>

<img class ="analysis-screenshot" src= "%assets_url%/img/rouleur-screenshot.png" alt="Rouleur-screenshot-1">

<div class="color-scheme-div alt-color-scheme">
<table>
    <h3 class="about-color-scheme-h3">Färgschema:</h3>
    <tr>
        <td style="background-color: #FFFFFF">
            <span class="light-span"></span>
        </td>
        <td style="background-color: #FFFEFF">
            <span class="light-span"></span>
        </td>
        <td style="background-color: #F4F4F4">
            <span class="light-span"></span>
        </td>
        <td style="background-color: #E5E5E5">
            <span class="light-span"></span>
        </td>
        <td style="background-color: #E74444">
            <span class="dark-span"></span>
        </td>
        <td style="background-color: #831D2D">
            <span class="dark-span"></span>
        </td>
        <td style="background-color: #1D1D1D">
            <span class="dark-span"></span>
        </td>
        <td style="background-color: #000000">
            <span class="dark-span"></span>
        </td>
    </tr>
</table>
</div>

Färgpaletten ser vid en första anblick ut att vittna om en ganska, grå, trist och torftig hemsida, vilket inte på något sätt är fallet.

Rouleur.cc lyckas ro i land det här minimalistiska, spartanska, neutrala, akromatiska (svart-vit-gråa) färgschemat, med ett litet rött accentuerande undantag för subscription-knappen, som är nätt och diskret, med en matt röd färg, genom att istället ge väldigt generöst med plats åt vad som i regel är högkvalitativa, stilrena, färggranna, ofta natursköna bilder som hör cykelsporten till.

<img class ="analysis-screenshot" src= "%assets_url%/img/rouleur-screenshot4.png" alt="Rouleur-screenshot-4">

Därutöver har de ytterligare ett litet kulört undantagsfall, vinrött i det här fallet, som de använder i det enda reklambanner-liknande inslaget på sidan, som i själva verket inte är en regelrätt sådan, utan istället frontar deras egna magasin, varför jag anser att den är värd att inkludera i den här elementfärgsanalysen, och även den länkar tillbaka till subscribe-sidan.

Till den hör en mycket väl sammansatt image-comparison-slider på samma tema. Inkluderar båda nedan. Stiligt så det förslår.

<img class ="analysis-screenshot" src= "%assets_url%/img/rouleur-screenshot2.png" alt="Rouleur-screenshot-2">

<img class ="analysis-screenshot" src= "%assets_url%/img/rouleur-screenshot3.png" alt="Rouleur-screenshot-3">


Typsnittsmässigt så växlar de mellan två utvalda fonter:

[Georgia Pro](https://www.iu.edu/brand/design/typography/georgia-pro.html) - ett serif-typsnitt - för logon, bildrubrikerna, länkarna, och även brödtexten.

[Harmonia Sans](https://www.dafontfree.co/harmonia-sans-font/) - ett sans serif-typsnitt - har istället används för knapparna, navbar-texten, h1-rubrikerna och underrubrikerna.

Generellt sett så är det ju rekommenderat att man väljer ett modernare, tydligare sans-serif-typsnitt för brödtexten, för att främja bättre läsbarhet, men här har de valt att frångå den principen.

Georgia Pro är ett serif-typsnitt som är framtaget för att nominellt även kunna lämpa sig för brödtext i en sådan här implementation, och den gör väl enligt min bedömning åtminstone ett okej jobb.

Men givet att sidan ändå är ganska textintensiv på sina håll, och innehåller många längre artiklar och essäer, så går det att argumentera för att de ändå kanske skulle valt en än ögon- och läsvänligare variant.

Till logon, bildrubrikerna etc. finner jag dock att Georgia Pro lämpar sig alldeles utmärkt, och det bestående intrycket från sidan är mycket gott.


<h2 class="analysis-site-rubric">Chessbase.com</h2>


<img class ="analysis-screenshot" src= "%assets_url%/img/chessbase-screenshot.png" alt="Chessbase-screenshot-1">
<img class ="analysis-screenshot" src= "%assets_url%/img/chessbase-screenshot2.png" alt="Chessbase-screenshot-2">

<div class="color-scheme-div alt-color-scheme">
    <h3 class="about-color-scheme-h3">Färgschema:</h3>
    <table>
        <tr>
            <td style="background-color: #E3B97D"><span class="light-span"></span></td>
            <td style="background-color: #C47A58"><span class="dark-span"></span></td>
            <td style="background-color: #E2B400"><span class="light-span"></span></td>
            <td style="background-color: #D47E01"><span class="light-span"></span></td>
            <td style="background-color: #AA5E00"><span class="dark-span"></span></td>
            <td style="background-color: #854B1D"><span class="dark-span"></span></td>
            <td style="background-color: #48220E"><span class="dark-span"></span></td>
            <td style="background-color: #401E0C"><span class="dark-span"></span></td>
        </tr>
        <tr>
            <td style="background-color: #59AFD4"><span class="light-span"></span></td>
            <td style="background-color: #598DCA"><span class="light-span"></span></td>
            <td style="background-color: #3A589B"><span class="dark-span"></span></td>
        </tr>
        <tr>
            <td style="background-color: #00AA00"><span class="dark-span"></span></td>
            <td style="background-color: #3E654A"><span class="dark-span"></span></td>
        </tr>
        <tr>
            <td style="background-color: #992F53"><span class="dark-span"></span></td>
            <td style="background-color: #BB102B"><span class="dark-span"></span></td>
            <td style="background-color: #D8011E"><span class="dark-span"></span></td>
            <td style="background-color: #B70D20"><span class="dark-span"></span></td>
            <td style="background-color: #6B1A5D"><span class="dark-span"></span></td>
            <td style="background-color: #5A194E"><span class="dark-span"></span></td>
        </tr>
        <tr>
            <td style="background-color: #F2E1CC"><span class="light-span"></span></td>
            <td style="background-color: #909AA6"><span class="light-span"></span></td>
            <td style="background-color: #8E989A"><span class="light-span"></span></td>
            <td style="background-color: #6E7D8C"><span class="light-span"></span></td>
            <td style="background-color: #5D6668"><span class="light-span"></span></td>
            <td style="background-color: #3D485C"><span class="dark-span"></span></td>
            <td style="background-color: #3F4A5E"><span class="dark-span"></span></td>
            <td style="background-color: #0F1516"><span class="dark-span"></span></td>
            <td style="background-color: #000000"><span class="dark-span"></span></td>
        </tr>
    </table>
</div>

Chessbase är desto frikostigare på färgfronten, dessutom med återkommande gradient-effekter på många av elementen, vilka jag har försökt fånga upp på ett representativt sätt.

Det går nog inte att strikt kategorisera det som varandes något renodlat färgschema, utan får väl klassas som någon slags hybrid mellan en komplementär och analog sammansättning med triadiska inslag.

Det huvudsakliga dominerande brun-blå-röda huvudtemat harmoniserar bra, och de övriga färgerna, även om de är ganska många, har en nedtonad, lugn, dämpad profil.

De neutrala vit-beige-grå-svarta huvudstråken bidrar till att sidan känns sammansatt, stabil och seriös, vilket lämpar sig för en schacksida, även med den i övrigt lite spretigare och friare kromatiska profilen.

Hade de börjat rucka på den, och börjat experimentera med fler färger till den grundstrukturen, hade det funnits en risk för att det barkat iväg på ett sätt som potentiellt kunnat upplevas som distraherande.

Själva schackbrädet som används för partianalyser, som är väldigt centralt för en sida av denna art, och där en genomsnittsbesökare kommer spendera mycket av sin tid, passar in väl med det huvudsakliga färgschemat.

Eller, det är nog egentligen att börja i fel ände: det beige-brun-rutade brädet, kanske det mest populära globalt bortsett från det klassiska svart-vita, är nog i själva verket det som delvis inspirerat till färgvalen i layouten, kan man åtminstone starkt misstänka.

<img class ="analysis-screenshot" src= "%assets_url%/img/chessbase-screenshot3.png" alt="Chessbase-screenshot-3">

De använder sig av:

[Montserrat](https://fonts.google.com/specimen/Montserrat) - ett sans-serif-typsnitt - för länkarna i huvudbannern, andra länkar på sina håll, knapparna, och även vissa sidobanners.

[Merriweather](https://fonts.google.com/specimen/Merriweather) - ett serif-typsnitt - för brödtexten, h1-rubriker, ingresser, underrubriker, och även vissa andra länkar.

[Fjalla One](https://fonts.google.com/specimen/Fjalla+One) - ett sans-serif-typsnitt- med en betydligt modernare känsla, letar sig in i en och annan sidobanner.

[Roboto Condensed](https://fonts.google.com/specimen/Roboto+Condensed) - ett sans-serif-typsnitt - som gör ett bra jobb med att på liten yta och i liten storlek bjuda på tydlig draganalys i det lilla fönster-elementet i anslutning till schackbrädet.


<img class ="analysis-screenshot" src= "%assets_url%/img/chessbase-screenshot4.png" alt="Chessbase-screenshot-4">

Även här går det att ifrågasätta att de valt att använda ett serif-typsnitt i Merriweather för att axla rollen som bärare av brödtexten.

Delvis pga att den till sin natur inte är särskilt lättläst och luftig, och tycker även att den här i sin allmäna implementation bidrar till en lite förlegad och utdaterad känsla till sidan överlag, som skär sig lite med det helhetsintryck som annars hade landad i någonting verkligt gediget, modernt och balanserat.

Inte för att för den sakens skull antyda att "modernt" per definition och per automatik är bra, men om man då väljer att ge så mycket utrymme till ett (i mitt tycke tämligen mediokert och trist) serif-typsnitt av det här slaget, och om man med det söker få till en mer klassisk och traditionell känsla, så bör det kanske isf också återspegla sig i sidans övriga layout, och eventuellt också kompenseras för med ytterligare letter spacing eller andra lämpliga åtgärder för att nå upp till en god nivå av läsbarhet.

När Montserrat, eller Fjalla One, som inte nödvändigtvis är några personliga favoriter hos en typografisk novis som mig, istället appliceras, så upplever jag att de ger ett lyft direkt.

Även med ovan nämnda synpunkter i beaktning, så är det samlade intrycket från sidan ändå fortsatt gott och seriöst, men med utrymme för förbättring.

<h2 class="analysis-site-rubric">FIDE.com</h2>

<img class ="analysis-screenshot" src= "%assets_url%/img/fide-screenshot.png" alt="fide-screenshot1">

<div class="color-scheme-div alt-color-scheme">
    <h3 class="about-color-scheme-h3">Färgschema:</h3>
    <table>
        <tr>
            <td style="background-color: #FFFFFF"><span class="light-span"></span></td>
            <td style="background-color: #F5F4F9"><span class="light-span"></span></td>
            <td style="background-color: #E9E9F1"><span class="light-span"></span></td>
            <td style="background-color: #AEB9CD"><span class="light-span"></span></td>
            <td style="background-color: #C6CEE5"><span class="light-span"></span></td>
            <td style="background-color: #979797"><span class="dark-span"></span></td>
            <td style="background-color: #232221"><span class="dark-span"></span></td>
            <td style="background-color: #000000"><span class="dark-span"></span></td>
        </tr>
        <tr>
            <td style="background-color: #B5DAFB"><span class="light-span"></span></td>
            <td style="background-color: #48ACFF"><span class="light-span"></span></td>
            <td style="background-color: #4C67AC"><span class="dark-span"></span></td>
            <td style="background-color: #50618D"><span class="dark-span"></span></td>
            <td style="background-color: #334166"><span class="dark-span"></span></td>
            <td style="background-color: #3C4963"><span class="dark-span"></span></td>
        </tr>
        <tr>
            <td style="background-color: #F6A0A3"><span class="light-span"></span></td>
            <td style="background-color: #E76766"><span class="light-span"></span></td>
            <td style="background-color: #DA2A2A"><span class="light-span"></span></td>
            <td style="background-color: #EB1F26"><span class="light-span"></span></td>
            <td style="background-color: #FF003D"><span class="light-span"></span></td>
            <td style="background-color: #FF0000"><span class="light-span"></span></td>
        </tr>
    </table>
</div>

Slutligen tar vi oss en titt på FIDEs hemsida. Där har vi att göra med ett betydligt mer sparsmakat färgschema igen.

De har valt att använda sig av ett blått analogt huvudtema, med kompletterande röda accentfärger, balanserade mot en neutral vit-grå-svart grund.

Det är återhållsamt, nyktert, inte jättespännande, men i mitt tycke stilrent och snyggt.

Även när det gäller typsnitten är det verkligen inga utsvävningar, utan de håller sig till säkra kort.

Och med undantag för [Bitstream Vera Serif](https://www.dafont.com/bitstream-vera-seri.font) - ett serif-typsnitt- som används till titeln i headern, så är det [Roboto](https://fonts.google.com/specimen/Roboto) - ett av de mest populära och använda sans-serif-typsnitten - som gäller för hela slanten, för allt övrigt innehåll på huvudsidan.

<img class ="analysis-screenshot" src= "%assets_url%/img/fide-screenshot2.png" alt="fide-screenshot2">
<img class ="analysis-screenshot" src= "%assets_url%/img/fide-screenshot3.png" alt="fide-screenshot3">


Igen, varken vågat eller nyskapande, men det fungerar och levererar ett förutsägbart, habilt, tydligt, läsvänligt resultat.

Jag kvalificerade det tidigare kategoriska konstaterandet med att det gällde huvudsidan, för när FIDE i år (2024) fyllde 100 år, så etablerade de en liten jubileumssida som länkas till från navbaren, där de faktiskt har spänt bågen åtminstone lite till när det gäller typsnittsvalen:

<img class ="analysis-screenshot" src= "%assets_url%/img/fide-screenshot4.png" alt="fide-screenshot4">
<img class ="analysis-screenshot" src= "%assets_url%/img/fide-screenshot5.png" alt="fide-screenshot5">


...där är det istället [Segoe UI](https://online-fonts.com/fonts/segoe-ui) - ett sans-serif-typsnitt- som används till titeln i headern, och [Red Hat Display](https://fonts.google.com/specimen/Red+Hat+Display) - ytterligare ett sans-serif-typsnitt - till resten av elementen.

Stilrent och enkelt även här, men med kanske aningen mer flärd.

Sammanfattningsvis tycker jag att färgvalen och typsnittsvalen bidrar till ett professionellt, propert och formellt intryck, vilket är i linje med vad man kan förvänta sig av en förbundssida.


<h2 class="sub-rubric">Referenser</h2>
[Readability in UX/UI Design](https://www.interaction-design.org/literature/topics/readability-in-ux-design)

The Principles of Beautiful Web Design, 4th edition, Chapter 2 - Color

<h2 class="sub-rubric">Författare</h2>
Rapport skriven av Herman Karlsson (hekr23).