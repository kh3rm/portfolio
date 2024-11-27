---
Title: About
Description: A page outlining the technologies that we're working with
# hidden: true
---

## About

Sidans grundstruktur är uppbyggd med ett smidigt, minimalistiskt PHP-ramverk som heter Pico, som tar hjälp av Twig, en template engine, mycket likt det mycket populära och använda EJS i sin sammansättning och sin syntax, för att enkelt och cleant kunna rendera vyerna.

För att mer initierat kunna arbeta med stylingen och CSS-strukturen, så är vi understödda av SASS, som ger oss möjligheten att jobba på ett mer modulärt, välstrukturerat och sofistikerat sätt med våran stylingkod, för att sedan kunna kompilera ihop dessa beståndsdelar till ett enda sammanhållet css-stylesheet igen med ett enkelt "npm run style"-kommando. Fiffigt!

Den stylingkoden ser vi också till att kvalitetskontrollera lokalt själva, oberoende av de vanliga dbwebb-kontrollverktygen, med hjälp utav stylelint, för att säkerställa att vi är skötsamma och att vi anammar gängse god kodpraxis.

Vi inkorporerar även Font Awesomes standardbibliotek, genom att importera det i scss-koden, vilket ger oss tillgång till dess utbud av gratis stock-ikoner (och mycket annat), som smidigt kan implementeras med hjälp av ikonernas klassnamn.

De fonter som jag personligen har valt att använda mig av, Nunito Sans och Lora, hämtar jag hem från Google Fonts, där läsbarhet och tydlighet har varit ledstjärnorna i min typografiska avvägning.

Vi använder oss av Markdown för att på ett avskalat - och för en från programmeringsvärlden utomstående mer lättförståeligt och intuitivt - sätt formatera våra texter, så att de mer efterliknar det man skulle kunna mötas av i en vanlig ordhanterare.

HTML är ju, per definition i webbsammanhang, alltid med där i bakgrunden som en stamfader, övervakandes allt intressant som ynglingarna hittar på.

...och även om vi nu inte aktivt skriver mycket ren HTML-kod, så är det ju naturligtvis fortsatt det formatet som den slutgiltiga källkoden intar när det vankas faktisk sidorendering på klientsidan.