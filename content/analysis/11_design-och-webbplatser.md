---
Title: Design och Webbplatser
Template: analysis
---

Design och Webbplatser
=======================
<!-- Skriv en eller två rader om vad uppgiften handlar om. -->
Syftet med denna rapport är att analysera mitt examinationsprojekt för kursen design utifrån en bild och laddningstids-synpunkt.

Urval
-----------------------
<!-- Berätta vilka webbplatser du valt att undersöka och varför eller hur du gick tillväga när du gjorde ditt urval. -->
- [<i class="fas fa-external-link-alt"></i> Mitt examinationsprojekt](http://www.student.bth.se/~haoh20/dbwebb-kurser/design/me/kmom10/)

Metod
-----------------------
<!-- Berätta kort om din "metod", hur du gör för att utföra undersökningen. Berätta om du använder något speciellt verktyg. -->
Min metod för denna analys kommer vara att mäta laddningstiden för min sida på studentservern 3 gånger med rensad cache och dra ett medelvärde av dessa. Jag kommer även mäta filstorleken, upplösningen och storleken på img-elementet för några av bilderna för att se om några förbättringar kan göras. Jag kommer även använda mig utav Lighthouse i DevTools för ytterligare mätningar. Beräkningarna görs för både desktop och mobila enheter.

Resultat
-----------------------
<!-- Dokumentera dina resultat från din studie. Berätta vad du kom fram till, vilka resultat du hittade och observerade. -->
### Desktop: ----------------------------------------------

### Laddningstid
<table style="border-spacing: 4px; border-collapse: collapse" class="load-table">
    <tr>
        <th>Hem</th><th>Om</th><th>Projekt</th>
    </tr>
    <tr>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">453 ms</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">567 ms</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">679 ms</td>
    </tr>
    <tr>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">336 ms</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">629 ms</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">349 ms</td>
    </tr>
    <tr>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">397 ms</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">550 ms</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">467 ms</td>
    </tr>
    <tr>
        <td style="height: 30px; width: 100px; border: 1px solid grey;"><b>Medel: 395,3 ms</b></td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;"><b>Medel: 582 ms</b></td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;"><b>Medel: 498,3 ms</b></td>
    </tr>
</table>

### Bilder
<table style="border-spacing: 4px; border-collapse: collapse" class="load-table">
    <tr>
        <th></th><th>Heroimage</th><th>Logga (Topp)</th><th>Logga (Botten)</th><th>Headshot</th>
    </tr>
    <tr>
        <td style="height: 30px; width: 100px; border: 1px solid grey;"><b>Filstorlek:</b></td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">165 kB</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">31,7 kB</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">31,7 kB</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">1,9 MB</td>
    </tr>
    <tr>
        <td style="height: 30px; width: 100px; border: 1px solid grey;"><b>Bildupplösning:</b></td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">2000 x 1333</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">300 x 333</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">300 x 333</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">1000 x 994</td>
    </tr>
    <tr>
        <td style="height: 30px; width: 100px; border: 1px solid grey;"><b>Img-storlek:</b></td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">1903 x 374,8</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">168,66 x 187,2</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">63,42 x 70,39</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">319,69 x 317,766</td>
    </tr>
</table>

### Lighthouse Performance
<p>
    <b>Hem:</b> 98
    <b>Om:</b> 99
    <b>Projekt:</b> 99
</p>

### Mobil: ------------------------------------------------

### Laddningstid
<table style="border-spacing: 4px; border-collapse: collapse" class="load-table">
    <tr>
        <th>Hem</th><th>Om</th><th>Projekt</th>
    </tr>
    <tr>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">357 ms</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">552 ms</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">385 ms</td>
    </tr>
    <tr>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">439 ms</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">605 ms</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">1,77 s</td>
    </tr>
    <tr>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">391 ms</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">559 ms</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">336 ms</td>
    </tr>
    <tr>
        <td style="height: 30px; width: 100px; border: 1px solid grey;"><b>Medel: 395,7 ms</b></td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;"><b>Medel: 572 ms</b></td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;"><b>Medel: 830,3 ms</b></td>
    </tr>
</table>

### Bilder
<table style="border-spacing: 4px; border-collapse: collapse" class="load-table">
    <tr>
        <th></th><th>Heroimage</th><th>Logga (Topp)</th><th>Logga (Botten)</th><th>Headshot</th>
    </tr>
    <tr>
        <td style="height: 30px; width: 100px; border: 1px solid grey;"><b>Filstorlek:</b></td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">165 kB</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">6,5 kB</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">6,5 kB</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">1,9 MB</td>
    </tr>
    <tr>
        <td style="height: 30px; width: 100px; border: 1px solid grey;"><b>Bildupplösning:</b></td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">2000 x 1333</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">100 x 111</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">100 x 111</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">1000 x 994</td>
    </tr>
    <tr>
        <td style="height: 30px; width: 100px; border: 1px solid grey;"><b>Img-storlek:</b></td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">414 x 220,8</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">73,59 x 81,69</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">69 x 76,58</td>
        <td style="height: 30px; width: 100px; border: 1px solid grey;">260,83 x 259,25</td>
    </tr>
</table>

### Lighthouse Performance
<p>
    <b>Hem:</b> 81
    <b>Om:</b> 80
    <b>Projekt:</b> 91
</p>

Analys
-----------------------
<!-- Diskutera och analysera de resultaten du fann. -->
Laddningstiderna mellan dem olika platformarna är näst intill identiska, bortsett från en dålig laddningstid med 1,8s på mobil. För att förbättra denna sidan finns det ett antal åtgärder som skulle kunna göras, den främsta är att korrekt skala bilderna för storleken av dess element. Som det ser ut nu så är två av bilderna, nämligen herobilden och headshotbilden, väldigt dåligt optimerade för storleken av det element dem ligger i. Herobilden behåller sin ursprungliga storlek av 2000px hela vägen ner till mobil-storlek där storleken på elementet är 400px och lika så med headshotet som håller 1000px hela vägen ner till där den skulle varit 260px. Dem resterande bilderna, som alla ligger på projekt-sidan är väl anpassade till elementets-storlek, detta tack vare användningen av picture-element och cimage-funktioner för att responsivt anpassa storleken på bilden beroende på vilken bredd enheten har. 

Referenser
-----------------------
<!-- Ange de eventuella referenser du använder dig av, om några. -->
<p>-</p>

Övrigt
-----------------------
<!-- Skriv ditt eget namn samt vilka gruppmedlemmar som deltog i att författa rapporten. -->
Skriven utav Hannes Öhman
