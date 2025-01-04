---
Title: About
Description: A page outlining the technologies that we're working with
# hidden: true
---

<h1 class="about-rubric">About</h1>


Sidans grundstruktur är uppbyggd med ett smidigt, minimalistiskt PHP-ramverk som heter Pico, som tar hjälp av Twig, en template engine, mycket likt det mycket populära och använda EJS i sin sammansättning och sin syntax, för att enkelt och cleant kunna rendera vyerna.

För att mer initierat kunna arbeta med stylingen och CSS-strukturen, så är vi understödda av SASS, som ger oss möjligheten att jobba på ett mer modulärt, välstrukturerat och sofistikerat sätt med våran stylingkod, för att sedan kunna kompilera ihop dessa beståndsdelar till ett enda sammanhållet css-stylesheet igen med ett enkelt "npm run style"-kommando. Fiffigt!

Den stylingkoden ser vi också till att kvalitetskontrollera lokalt själva, oberoende av de vanliga dbwebb-kontrollverktygen, med hjälp utav stylelint, för att säkerställa att vi är skötsamma och att vi anammar gängse god kodpraxis.

Vi inkorporerar även Font Awesomes standardbibliotek, genom att importera det i scss-koden, vilket ger oss tillgång till dess utbud av gratis stock-ikoner (och mycket annat), som smidigt kan implementeras med hjälp av ikonernas klassnamn.

Sidan använder sig av två minimalistiska, monokroma färgscheman, ett ljust och ett mörkt:

<div class="color-scheme-div">
<table>
    <h2 class="about-color-scheme-h3">Light mode:</h2>
    <tr>
        <td style="background-color: #f1f0ff">
            <span class="light-span">#f1f0ff</span>
        </td>
        <td style="background-color: #f0f8ff">
            <span class="light-span">#f0f8ff</span>
        </td>
        <td style="background-color: #93B6D5">
            <span class="light-span">#93B6D5</span>
        </td>
    </tr>
</table>
</div>

<div class="color-scheme-div">
<table>
    <h2 class="about-color-scheme-h3">Dark mode:</h2>
    <tr>
        <td style="background-color: #746878">
            <span class="dark-span">#746878</span>
        </td>
        <td style="background-color: #4F4F7D">
            <span class="dark-span">#4F4F7D</span>
        </td>
        <td style="background-color: #414152">
            <span class="dark-span">#414152</span>
        </td>
    </tr>
    <tr>
        <td style="background-color: #171724">
            <span class="dark-span">#171724</span>
        </td>
        <td style="background-color: #1f1c20">
            <span class="dark-span">#1f1c20</span>
        </td>
        <td style="background-color: #0b0b14">
            <span class="dark-span">#0b0b14</span>
        </td>
    </tr>
</table>
</div>

De fonter som jag personligen har valt att använda mig av, [Nunito Sans](https://fonts.google.com/specimen/Nunito+Sans) och [Lora](https://fonts.google.com/specimen/Lora), hämtar jag hem från Google Fonts, där läsbarhet och tydlighet har varit ledstjärnorna i min typografiska avvägning.

Vi använder oss av Markdown för att på ett avskalat - och för en från programmeringsvärlden utomstående mer lättförståeligt och intuitivt - sätt formatera våra texter, så att de mer efterliknar det man skulle kunna mötas av i en vanlig ordhanterare.

HTML är ju, per definition i webbsammanhang, alltid med där i bakgrunden som en stamfader, övervakandes allt intressant som ynglingarna hittar på.

...och även om vi nu inte aktivt skriver mycket ren HTML-kod, så är det ju naturligtvis fortsatt det formatet som den slutgiltiga källkoden intar när det vankas faktisk sidorendering på klientsidan.
