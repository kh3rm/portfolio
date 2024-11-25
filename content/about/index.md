---
Title: About
Description: A page outlining the technologies that we're working with
# hidden: true
---

## About

Sidans grundstruktur är uppbyggd med ett smidigt, minimalistiskt PHP-ramverk som heter Pico, som tar hjälp av twig, en template engine, mycket lik det mycket populära och använda EJS i sin sammansättning och sin syntax, för att enkelt och cleant kunna rendera vyerna.

För att mer initierat kunna arbeta med stylingen och CSS-strukturen, så är vi understödda utav SASS, som ger oss möjligheten att jobba på ett mer modulärt, välstrukturerat och sofistikerat sätt med våran stylingkod, för att sedan kunna kompilera ihop dessa beståndsdelar till en enda sammanhållen css-stylesheet igen med ett enkelt "npm run style"-kommando. Fiffigt!

Den stylingkoden ser vi också till att kvalitetskontrollera lokalt själva, oberoende av de vanliga dbwebb-kontrollverktygen, med hjälp utav lint, för att säkerställa att vi är skötsamma och att vi anammar gängse god kodpraxis.

Vi inkorporerar även Font Awesomes standardbibliotek, och gör det genom att importera det i scss-koden, vilket ger oss tillgång till dess utbud av gratis stock-ikoner (och mycket annat), som smidigt kan sättas ut med hjälp utav klassnamn.

De fonter som jag personligen valt att använda mig av, Nunito Sans och Lora, hämtar jag hem från Google Fonts, där läsbarhet och tydlighet har varit mina ledstjärnor i min typografiska avvägning.

Vi använder oss av markdown för att på ett avskalat - och för en från programmeringsvärlden utomstående mer lättförståeligt och intuitivt sätt - formatera våra texter, så att de mer efterliknar det man skulle kunna mötas av i en vanlig ordhanterare.

HTML är ju, per definition i webbsammanhang, alltid med där i bakgrunden som en stamfader, övervakandes allt intressant ynglingarna hittar på. Och även om vi inte aktivt skriver mycket ren HTML-kod, så är det ju naturligtvis fortsatt det formatet som den slutgiltiga källkoden intar när det vankas faktisk sidorendering på klientsidan.
