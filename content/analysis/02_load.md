---
Title: Laddningstid och användbarhet
Template: analysis
---

Laddningstid och användbarhet
=======================

<!-- Skriv en eller två rader om vad uppgiften handlar om. -->

Urval
-----------------------

<!-- Berätta vilka webbplatser du valt att undersöka och varför eller hur du gick tillväga när du gjorde ditt urval. -->
<!--
https://www.tesla.com/sv_se
https://www.reddit.com/
https://sv.wikipedia.org/wiki/Varbergs_f%C3%A4stning
-->
Jag har valt att undersöka:

 - Tesla
 - Reddit
 - Wikipedia: Varbergs Fästning

Mitt urval består av 3 olika sidor vars huvudsakliga skillnader är antalet bilder som används på hemsidan. 
Den specifika wikipedia sidan kanske sticker ut som ett lite udda val men motiveringen bakom valet är att folk sällan är inne på wikipedias startsida och istället är inne och läser på specifika artiklar.

Metod
-----------------------

<!-- Berätta kort om din "metod", hur du gör för att utföra undersökningen. Berätta om du använder något speciellt verktyg. -->
För att mäta laddningstiden på dem olika sidorna så använder jag mig utav "Network"-fliken i dev-tools samt PageSpeed Insight.

Resultat
-----------------------

<!-- Dokumentera dina resultat från din studie. Berätta vad du kom fram till, vilka resultat du hittade och observerade. -->
### [<i class="fas fa-external-link-alt"></i> Tesla:](https://www.tesla.com/sv_se)

<div class="site-result">
    <img src="%base_url%/content/analysis/img/tesla.png" alt="Aftobladet" class="analysis-img">
    <div>
        <table style="border-spacing: 4px; border-collapse: collapse" class="load-table">
            <tr>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">PageSpeed: Desktop</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">PageSpeed: Mobil</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">Laddningstid</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">Resurser</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">Total storlek</td>
            </tr>
            <tr>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">58,00</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">13,67</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">1,02 s</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">29 st</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">8,00 MB</td>
            </tr>
        </table>
        <p>Här finns ytters få saker man skulle kunna förbättra på sidan. Något man skulle kunna göra är att minska antalet resurser som behöver hämtas och i samband med detta minska den totala storleken på hemsidan.</p>
    </div>
</div>

### [<i class="fas fa-external-link-alt"></i> Reddit:](https://www.reddit.com/)

<div class="site-result">
    <img src="%base_url%/content/analysis/img/reddit.png" alt="Aftobladet" class="analysis-img">
    <div>
        <table style="border-spacing: 4px; border-collapse: collapse" class="load-table">
            <tr>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">PageSpeed: Desktop</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">PageSpeed: Mobil</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">Laddningstid</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">Resurser</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">Total storlek</td>
            </tr>
            <tr>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">40,00</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">21,00</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">3,40 s</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">190 st</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">16,20 MB</td>
            </tr>
        </table>
        <p>Här behövs en stor minskning av antalet resurser och eftersom många av dem resurser som hämtas är bilder så skulle någon form komprimering också behövas för att få ner filstorleken.</p>
    </div>
</div>

### [<i class="fas fa-external-link-alt"></i> Wikipedia: Varbergs Fästning:](https://sv.wikipedia.org/wiki/Varbergs_f%C3%A4stning)

<div class="site-result">
    <img src="%base_url%/content/analysis/img/wikipedia.png" alt="Aftobladet" class="analysis-img">
    <div>
        <table style="border-spacing: 4px; border-collapse: collapse" class="load-table">
            <tr>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">PageSpeed: Desktop</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">PageSpeed: Mobil</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">Laddningstid</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">Resurser</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">Total storlek</td>
            </tr>
            <tr>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">99,00</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">81,67</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">282 ms</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">30,00 st</td>
                <td style="height: 30px; width: 100px; border: 1px solid grey;">871 KB</td>
            </tr>
        </table>
        <p>Wikipedia är näst intill perfekt, väldigt kort laddningstid och liten filstorlek. Om något skulle behöva förbättras så skulle man kanske kunna minska antalet resurser som hämtas.</p>
    </div>
</div>

Analys
-----------------------

<!-- Diskutera och analysera de resultaten du fann. -->
För att sammanfatta så finns det som fröväntat en tydlig korrelation mellan storleken på filerna och laddningstid. Dem vanligaste åtgärderna för detta är att minska antalet filer som begärs och på så sätt bli av med onödiga resurser och att optimera koden i dem filerna som är nödvändiga för att minska dess storlek.

Utifrån mitt urval och resultat skulle jag säga att Wikipedia är vinnaren, dem använder ett generellt "sans-serif"-typsnitt vilket gör att datorn väljer det lättast tillgängliga typsnittet vilket i sin tur minskar laddningstiden. Dem använder sig också av bilder endast när dem har ett tydligt syfte och när bilder visas så är dem anpassade för att vara så "storlekssnåla" som möjligt.

Jag skulle dra min persnoliga gräns för snabb laddningstid vid ca 2s vilket jag tror är längre än dem flesta andra, allt efter detta upplever jag som segt. Tesla och Wikipedia klarar denna gränsen med bra respektive väldigt bra marginal. Reddit känns segt vilket sedan gör att jag lätt tappar intresse för sidan om jag inte direkt ser något som fångar min uppmärksamhet.

Referenser
-----------------------

<!-- Ange de eventuella referenser du använder dig av, om några. -->
<a href="https://docs.google.com/spreadsheets/d/1Sc83FUq91LZp9j7-ZBEy0X8adsyL1TzI50mpyAPC28A/edit?usp=sharing"><i class="fas fa-external-link-alt"></i> Rådata</a>

Övrigt
-----------------------

<!-- Skriv ditt eget namn samt vilka gruppmedlemmar som deltog i att författa rapporten. -->
Skriven utav Hannes Öhman
