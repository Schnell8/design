---
Title: load
Description: This is my load page.
Template: analysis
---

Analys av webbplatser
=======================
Uppgiften handlar om att analysera olika webbplatsers laddningstid och se vilka områden som kan förbättras för att sänka laddningstiden.

Urval
-----------------------
Jag har valt att undersöka två giganter ute på internet, Zara och H&M, men också en mindre webbplats som tillhör företaget Öbergs Modehus som är en lokal klädeskedja från min hemstad Ystad. Det är tre företag inom samma bransch varav två är stora konkurrenter. Extra intressant är att se deras värden i jämförelse men också att se hur ett litet företag står upp mot dessa giganter.

Metod
-----------------------
På "Pagespeed Insight" har jag hämtat många olika typer av värde, samt kunnat se vilka förbättringsmöjligheter weddsidan har. I devtools flik network har jag kommit åt nyttig data för att se antalet resurser, storleken på webbsidan och laddningstiden.

Resultat
-----------------------
<img src="%base_url%/image/zara.png" alt="zara">
<a href="https://www.zara.com/se">https://www.zara.com/se</a>

<table style="border: solid 1px #000;">
    <tbody>
        <tr>
            <td>Betyg 1-100 (mobile)</td>
            <td>Betyg 1-100 (desktop)</td>
            <td>Laddningstid i s</td>
            <td>Antal resurser</td>
            <td>Storlek på sidan i MB</td>
        </tr>
        <tr>
            <td>22</td>
            <td>43</td>
            <td>1.71</td>
            <td>109</td>
            <td>2.6</td>
        </tr>
    </tbody>
</table>

Kommentar: Här bör man se över sin JavaScript, oavsett enhet. Just nu finns Javascript som man istället kan vänta med att läsa in till det faktiskt behövs. Även bilder som finns utanför skärmen kan man vänta med att läsa in tills viktigare saker kommit på plats. Man bör också optimera bildformatet på bilderna som skickas med. Detta skulle resultera i snabbare nedladdningstid som i sin tur ger minskad dataförbrukning.

<img src="%base_url%/image/hm.png" alt="hm">
<a href="https://www2.hm.com/sv_se/index.html">https://www2.hm.com/sv_se/index.html</a>

<table style="border: solid 1px #000;">
    <tbody>
        <tr>
            <td>Betyg 1-100 (mobile)</td>
            <td>Betyg 1-100 (desktop)</td>
            <td>Laddningstid i s</td>
            <td>Antal resurser</td>
            <td>Storlek på sidan i MB</td>
        </tr>
        <tr>
            <td>11</td>
            <td>40</td>
            <td>2.41</td>
            <td>285</td>
            <td>6.0</td>
        </tr>
    </tbody>
</table>

Kommentar: Precis som Zara behöver H&M se över sina bilder. Att skicka bilder med rätt storlek och bildformat skulle spara mycket tid. Webbsidan skulle också må bättre av att vänta med inläsningen av bilder som ligger utanför skärmen tills att de viktiga resurserna är inlästa.

<img src="%base_url%/image/obergs.png" alt="obergs">
<a href="https://obergsmodehus.se/">https://obergsmodehus.se/</a>

<table style="border: solid 1px #000;">
    <tbody>
        <tr>
            <td>Betyg 1-100 (mobile)</td>
            <td>Betyg 1-100 (desktop)</td>
            <td>Laddningstid i s</td>
            <td>Antal resurser</td>
            <td>Storlek på sidan i MB</td>
        </tr>
        <tr>
            <td>66</td>
            <td>91</td>
            <td>0.425</td>
            <td>45</td>
            <td>2.6</td>
        </tr>
    </tbody>
</table>

Kommentar: Likt de två övriga webbsidorna är bilderna boven i dramat åter igen. Bilderna skulle behöva skickas i ett annorlunda bildformat med rätt storlek för att speeda upp laddningstiden.

Analys
-----------------------
Utifrån resultatet kan vi enkelt konstatera att mindre antal resurser ger en mindre storlek på webbsidan vilket ger en snabbare laddningstid. De vanligaste förbättringsåtgärderna för utvalda webbsidor är:

-Skicka bilder i modernare bildformat

-Skjut upp inläsningen av bilder som inte visas på skärmen

-Använd bilder med rätt storlek

-Reducera JavaScript som inte används

Ett tydligt mönster av att bilder har stor inverkan på webbsidan.

<iframe class="iframe-load" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSbK_gIgxe7DJSWVY6ucelw3IFszgTFviZcA_rBKaBFt6ar7dNNJY2SfNHkiDfUjtooMwGNjs8DkJZu/pubhtml?widget=true&amp;headers=false" title="Excel data"></iframe>

Som tabellen visar har Öbergs Modevaruhus fått bäst betyg och visar även upp snabbast laddningstid. Detta betyder nödvändigtvis inte att det är den bäst utförda webbplatsen. De andra webbplatserna är betydligt större och använder sig av många fler resurser som gör att mer data behöver hanteras. Betyget är avsevärt mycket bättre och i mina ögon kan jag i slutändan inget annat än se Öbergs Modevaruhus som vinnare.

Mitt gränsvärde
-----------------------
Givetvis vill man att allt ska gå på nolltid men riktigt så är inte verkligheten, saker tar tid. Allt under 2 sekunder ser jag som accepterbart, tar det längre tid än så uppfattar jag sidan som trög och min upplevelse försämras. 
Då finns risken att jag inte stannar kvar på sidan och jag lär då inte heller återvända. Av webbplatserna jag valt ut klarar sig två bra medans H&M ligger över. Jag upplever att det tar betydligt längre tid att ta sig fram på webbplatsen i jämförelse med de andra två. Fast att det bara rör sig om 1-2 sekunder blir det en markant skillnad för mig som användare.

Övrigt
-----------------------
Christopher Schnell