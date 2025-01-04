---
Title: Loading Times Analysis
Description: An analysis of three websites performance and loading times.
---

<h1 class="about-rubric">Loading Times Analysis</h1>
<br>
I det här andra analysmomentet tar vi oss istället en närmare titt på tre utvalda hemsidors prestanda, med inriktning på svars- och laddningstider.

<h2 class="sub-rubric">Urval</h2>

Jag fortsätter vidare med de tre webbplatserna som tidigare analyserades i färg- och fontdelen, för att med intresse få en bättre inblick i hur de faktiskt beter sig under huven.

För varje sida kommer tre delsidor att testas, både i desktop- och mobilt läge:

- [Rouleur](https://www.rouleur.cc) - brittisk cykelsajt/cykelmagasin.
  - [Home](https://www.rouleur.cc)
  - [Store](https://www.rouleur.cc/collections/all-products)
  - [Travel](https://www.rouleur.cc/pages/rouleur-travel)

- [Chessbase](https://www.chessbase.com) - en sida för schacknyheter, statistik och partianalyser.
  - [Home](https://www.chessbase.com)
  - [Shop](https://shop.chessbase.com/en?ref=RF194-R4XO0JH72X)
  - [Books](https://books.chessbase.com/en)

- [FIDE](https://www.fide.com) - det internationella schackförbundets hemsida.
  - [Home](https://www.fide.com)
  - [Shop](https://shop.fide.com/)
  - [Ratings](https://ratings.fide.com/)

<h2 class="sub-rubric">Metod</h2>

Till min hjälp för att kunna utföra dessa tester har jag [Page Speed Insight](https://pagespeed.web.dev/), ett webbanalytiskt verktyg framtaget av Google, som hjälper till med att diagnosticera och mäta allsköns parametrar och benchmarks som är relevanta för en webbsidas prestanda och svarstider, och som därtill tillhandahåller konstruktiva, konkreta förslag på hur dessa för en given sida skulle kunna förbättras.

Därutöver använder jag min webbläsares developer tools, fortsatt i Firefox, och den nätverks-diagnostik man har att tillgå där, för att insamla ytterligare några relevanta och användbara datapunkter avseende laddningstider och resursanvändning.

För dessa utförs tre separata mätningar, och det genomsnittliga värdet räknas ut och noteras, för att mer rättvist återspegla det faktiska resultatet, och minimera varians och brus.


<iframe title="Loading-Times Google Spreadsheet" class="loading-analysis-sheet las-dark" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSJtyq4KIT1jGBm4l88CNYhBnJupAZx1iHXAJSbDkC9cNmrtugneWJ9vohrrP0oHuwV1n_p6CtMlR44/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>

All denna data har samlats i en google-sheets-tabell som har bäddats in ovan som en händig referens och utgångspunkt, och det är dessa värden som ligger till grund för den resultatanalys som följer nedan.

Bör också tilläggas som ett sista addendum och klargörande att de lokala devtools-testerna är utförda med en stabil men inte vindsnabb uppkoppling (uppmätt till ~22-Mbit/s via [Bredbandskollen](https://www.bredbandskollen.se/) vid testillfället), och en rätt så åldersstigen och överbelamrad dator, och därför är betydligt långsammare än vad de hade varit på och med en piggare och modernare genomsnittlig setup.

Trots detta så bidrar värdena sammantaget och i relation till varandra med ytterligare klargörande fingervisningar om hur sidorna presterar.

Resultatanalysen baseras dock huvudsakligen på de mer standardiserade och objektiva PSI-värdena.


<h2 class="sub-rubric">Resultat och Analys</h2>

<h2 class="analysis-site-rubric">Rouleur.cc</h2>

<img class ="load-screenshot" src= "%assets_url%/img/rouleur-load2.png" alt="Rouleur Screenshot Desktop">
<div class="mobile-load-screenshot-container">
    <img class ="load-screenshot-mobile" src= "%assets_url%/img/rouleur-mobile.png" alt="Rouleur Screenshot Mobile">
</div>

Sidans övergripande performance-betyg landar i ett acceptabelt men beskedligt spann mellan 60-74 för både desktop- och mobil-renderingen, med ett undantag för Travel-sidan i mobilvyn där det kryper ned till 53.

Accessibility-, Best Practices- och SEO-värdena balanserar i regel lite över 90-sträcket, vilket får grönt ljus och får anses vara respektabelt.

Travelsidan, där användaren bland annat bjuds på storskaligt, inbjudande, naturskönt video-material och inbäddade kartor, är extra resurskrävande och långsam att ladda, vilket man får ha visst överseende med.

Det manifesterar sig dock för en mobil användare på ett potentiellt riktigt problematiskt sätt, där FCP, LCP och Speed-index får röd flagg, och framförallt LCP-värdet på 15.6s sticker ut i negativ bemärkelse.

__Förbättringsförslag:__

DOM-trädet generellt kan och bör slimmas ned, och överflödiga JS-script elimineras.

Finns även stora besparingar att göras på bildfronten genom att ladda in bilder i rätt storlek, vilket borde vara en extra angelägen prioritering för en sådan allmänt bildintensiv sida.




<h2 class="analysis-site-rubric">Chessbase.com</h2>


<img class ="load-screenshot" src= "%assets_url%/img/chessbase-load.png" alt="Chessbase Screenshot Desktop">
<div class="mobile-load-screenshot-container">
    <img class ="load-screenshot-mobile" src= "%assets_url%/img/chessbase-mobile.png" alt="Chessbase Screenshot Mobile">
</div>

Siffrorna för Chessbase är desto mer problematiska.

Home-sidan landar i ett värde på 54 för desktop-versionen, och kryper ned till rött territorium för en mobil användare med skrala 43.

Shop klarar sig bara aningen bättre, och desktop-renderingen av Books-sidan är faktiskt den enda som lyckas kravla sig upp till grönt och riktigt stabilt territorium med en notering på 93.

Och även om den dev-tools-inhämtade datan ska tas med en nypa salt, och sidan inte är fullt så långsam som den datan vill ge sken av, så är det iögonfallande höga värden på framförallt DOM-content-loaded överlag, och för Home-sidan i synnerhet.

Detta kan påverka sidupplevelsen väldigt negativt, om en användare tvingas vänta länge innan sidan laddats in till en nivå där den är redo att interageras med på ett åtminstone grundläggande sätt.

Inte att rekommendera, och framförallt inte att rekommendera för en home/index-sida.

Den mobila prestandan är under all kritik, och det handlar i regel om gul och röd flagg, och för bland annat Speed-Index är det idelt rött.

__Förbättringsförslag:__

Finns mycket att jobba med, men att överflödiga JS-script bör ses över är återigen en nyckelsynpunkt.

Även här kan bilderna storleksmässigt arbetas med på ett bättre sätt, vilket skulle ge stora besparingar. Css-kod som inte används skulle också må bra av att slimmas ned.

Det finns därtill ett återkommande problem med layoutförskjutningar, som kan upplevas negativt och distraherande för en användare, som borde ses över.


<h2 class="analysis-site-rubric">FIDE.com</h2>

<img class ="load-screenshot" src= "%assets_url%/img/fide-load.png" alt="Fide Screenshot Desktop">
<div class="mobile-load-screenshot-container">
    <img class ="load-screenshot-mobile" src= "%assets_url%/img/fide-mobile.png" alt="Fide Screenshot Mobile">
</div>


Avslutningsvis tar vi oss en titt på FIDEs webbplats, vilken vid en första anblick tycks vara den rakaste, mest flärdfria, och därför potentiellt den rappaste och mest oproblematiska, av de tre. Skenet bedrar.

Performance-noteringarna är mediokra överlag, och rakt usel för Home-sidan i mobilt läge, med en notering på fattiga 22, och det är faktiskt den enda av alla sidor som direkt underkänns när det kommer till Core Web Vitals.

Best Practices-noteringarna är väl de enda riktigt positiva gröna undantagen, med noteringar på 96+ för alla delsidor, vilket givet sidornas övriga prestationer aningen förvånar. I övrigt är det ingen trevlig läsning.

Mobilrenderingen i synnerhet är rakt bedrövlig, med bl a en 10.2s Speed Index- och 27.9s LCP-notering för indexsidan.

Den laddar i regel in ett mycket stort antal resurser överlag, och mycket data, som jag upplever inte alls står i relation till det relativt modesta innehållet.

__Förbättringsförslag:__

Här finns det definitivt en uppsjö av åtgärder som borde övervägas.

Om vi börjar med fundamenta, och tittar till DOM-trädet, så kan det observeras att det laddas in över 2000 element för t ex home-sidan i mobilrenderingen.

Översvällande DOM-träd [bör undvikas](https://developer.chrome.com/docs/lighthouse/performance/dom-size), och här har vi ett i ordentligt behov av en genomgång, om inte ett omtag helt och hållet.

Finns även här stora besparingar att göras på bildfronten genom att ladda in bilder med rätt storlek och med rätt format.

Även en bättre och effektivare cachestruktur rekommenderas.

Den här listan skulle kunna göras väldigt lång, men själva grundproblematiken och pudelns kärna sammanfattas kanske bäst av Lighthouse själv, och väljer att lyfta in den exakta formuleringen de bjöd på: "Undvik enorm nätverksbelastning".

Kort och koncist. Ett gott råd.



<h2 class="sub-rubric">Övriga reflektioner</h2>

När det kommer till att hitta en röd tråd avseende förbättringsmöjligheterna, så är det gemensamt och återkommande för alla sidor som analyserats här att bättre Javascript-hantering rekommenderas, både när det gäller att avlägsna överflödiga scripts, och att potentiellt kombinera och slimma ned de som fortsatt ska användas.

Även goda vanor när det gäller bilder både avseende storlekshantering och format återkommer som en viktig punkt, speciellt då bilder väldigt ofta tenderar att stå för en väsentlig del av dataåtgången.

En resursmässigt i de flesta fall mindre avgörande, men ändå relevant, förbättring finns också att hitta när det gäller css-hanteringen, där oanvänd css-kod beivras, och ett komprimerat min-css-format föredras.

Skulle rangordna sidorna prestanda- och prestationsmässigt lämpligt nog precis som de är listade, där jag anser att Rouleur.cc klarar sig klart bäst, följt av Chessbase, som är habil men med en del stora brister, och slutligen Fide som klar jumbo, med stundtals riktigt slående svaga resultat.

Hade i ärlighetens namn inte reflekterat över hastigheten eller några större diskrepanser när det gäller laddningstider när jag interagerat med de här sidorna tidigare, men då är jag också van med att ha överseende med lite segare laddningstider och hantering givet min till åren komna dator.

När jag använder mobilen, som är betydligt fräschare och piggare, är jag dock inställd, alternativt bortskämd, på snabbare och rappare rendering.

Efter att ha testbesökt sidorna ytterligare några gånger och aktivt haft det här perspektivet i åtanke, både på min dator och min mobil, kan jag återse och bekräfta många av de mönster man kan utläsa ur tabelldatan, även om jag faktiskt inte tycker att t ex Fide upplevs fullt så seg och lågpresterande i mobilversionen som siffrorna antyder.

Betvilvar dock inte resultaten, som objektivt är vad de är, och tycker att det är bra att det sätts konstruktiv press på webbutvecklare att bidra till en snabbare och effektivare webbmiljö och till bättre utvecklarvanor.

Skulle säga att 1.5-2 sekunder någonting är vad jag intuitivt skulle klassificera som en rimlig, eftersträvnadsvärd laddningstid för en vanlig webbsida.

Om man då använder LCP som den mest relevanta måttstocken, som kanske det närmaste man kan komma en rättvis mätning och estimering av "absolut laddningstid", vilket är öppet för tolkning och nyansering, så är det endast Rouleur i allmänhet, och Chessbase i desktop-läge, som hamnar på rätt sida den 2-sekunders-maxgränsen.

Börjar en sida överskrida det, och därtill sticka iväg över 3 sekunder, så kan den börja upplevas som påtagligt långsam, och en användare har tid att aktivt börja reflektera över att sidan faktiskt laddar, vilket inte är eftersträvansvärt.


<h2 class="sub-rubric">Författare</h2>
Rapport skriven av Herman Karlsson (hekr23).

