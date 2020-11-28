---
Title: Färger och typsnitt
Template: analysis
---

Använding av färger och typsnitt på webbplatser
=======================

<!-- Skriv en eller två rader om vad uppgiften handlar om. -->
Syftet med denna rapport är att undersöka ett urval webbplatser och deras använding av färg och typsnitt. Hur dem påverkar hur användaren läser och vilka känslor dem vill medföra.

Urval
-----------------------

<!-- Berätta vilka webbplatser du valt att undersöka och varför eller hur du gick tillväga när du gjorde ditt urval. -->
<!-- 
https://www.aftonbladet.se/
https://www.svt.se/
https://www.hn.se/ 
-->
Jag har valt att undersöka tre olika nyhetssidor, Aftonbladet, SVT Nyheter och Hallands Nyheter. Att jag valde nyhetssidor är för att färg och typsnitt är väldigt viktigt på denna typen av sidor när det gäller att dra folks ögon till viktiga artiklar och händelser. Motiveringen för just dessa tre specifika sidor var att jag ville ha en nyhetssida som drivs av reklam och betalda prenumerationer i form av Aftonbladet. En annan till storleken likvärdig sida som inte använder reklam, i form av SVT Nyheter och en tredje mindre tidning som är mer fokuserad på lokala nyheter i form av Hallands Nyheter.

Metod
-----------------------

<!-- Berätta kort om din "metod", hur du gör för att utföra undersökningen. Berätta om du använder något speciellt verktyg. -->
Jag kommer öppna varje sida utan att scrolla och analysera första intrycket man får "above-the-fold". Sedan scrollar jag ner en bit för att se om mönstret ändras och vad ögonen dras till.

Resultat
-----------------------

<!-- Dokumentera dina resultat från din studie. Berätta vad du kom fram till, vilka resultat du hittade och observerade. -->
<!--
Aftonbladet:
Bakgrun         VIT     =   #FFFFFF
KÖP PLUS        GUL     =   #FFEB18
Logga           GUL     =   #FFEB00 ~
Nav / Rubriker  RÖD     =   #DD2A30
LOGGA IN        RÖD     =   #DD2A30
Sportartiklar   ROSA    =   #FEEBEE ~
Text            SVART   =   #222222 ~

H1, H2, H3=   Verdana, Arial, Helvetica, sans-serif
p element   =   Arial,Helvetica,Verdana,Geneva,sans-serif
-->
### Aftonbladet:

<div class="site-result">
    <img src="%base_url%/content/analysis/img/aftonbladet_AdBlock.png" alt="Aftobladet" class="analysis-img">
    <h4>Färgschema:</h4>
    <table style="border-spacing: 4px; border-collapse: separate">
        <tr>
            <td style="height: 50px; width: 50px; background-color: #FFFFFF; border: 1px solid grey;">
            <td style="height: 50px; width: 50px; background-color: #FEEBEE; border: 1px solid grey;">
            <td style="height: 50px; width: 50px; background-color: #DD2A30; border: 1px solid grey;">
            <td style="height: 50px; width: 50px; background-color: #FFEB00; border: 1px solid grey;">
            <td style="height: 50px; width: 50px; background-color: #222222; border: 1px solid grey;">
        </tr>
    </table>
    <div>
        <p>Färgschemat som används är huvudsakligen ett monokromt spektrum av vit-rött med gula accentfärger på ett fåtal ställen och svart text.</p><br>
        <h4>Typsnitt:</h4> <br>
        <p>Typsnitten som används på sidan skiljer sig inte mycket infrån varandra, dem är alla sans-serif.</p><br>
        <p><b>h1, h2, h3:</b> Verdana, Arial, Helvetica, sans-serif</p><br>
        <p><b>Brödtext:</b> Arial, Helvetica, Verdana, Geneva, sans-serif</p><br>
        <p>Sidan använder sig av många kontrasterande färger samt signalfärger och tydlig text, vilket jag antar dem strävar efter.</p>
    </div>
</div>



<!--
SVT Nyheter:
Bakgrund            GRÅ     =   #EBEBEB ~
Nav                 VIT     =   #FFFFFF ~
Accent / JUST NU    RÖD     =   #E02E3D ~
Footer 1            GRÅ     =   #404040 ~
Footer 2            GRÅ     =   #333333 ~

Body   =   Publik,Helvetica,Arial,"Nimbus Sans L","Bitstream Vera Sans",sans-serif
-->

### SVT Nyheter:

<div class="site-result">
    <img src="%base_url%/content/analysis/img/svt_nyheter.png" alt="SVT Nyheter" class="analysis-img">
    <h4>Färgschema:</h4>
    <table style="border-spacing: 4px; border-collapse: separate">
        <tr>
            <td style="height: 50px; width: 50px; background-color: #FFFFFF; border: 1px solid grey;">
            <td style="height: 50px; width: 50px; background-color: #EBEBEB; border: 1px solid grey;">
            <td style="height: 50px; width: 50px; background-color: #404040; border: 1px solid grey;">
            <td style="height: 50px; width: 50px; background-color: #333333; border: 1px solid grey;">
            <td style="height: 50px; width: 50px; background-color: #E02E3D; border: 1px solid grey;">
        </tr>
    </table>
    <div>
        <p>Monokromt färgschema i form av gråskala med SVT:s signatur röd som accent.</p><br>
        <h4>Typsnitt:</h4> <br>
        <p>Sidan använder sig utav en universal font-family som ligger direkt i bodyn och påverkar allt.</p><br>
        <p><b>Allt:</b> Publik, Helvetica, Arial, "Nimbus Sans L", "Bitstream Vera Sans", sans-serif</p><br>
        <p>Tydliga rubriker med inslag av signalfärger drar ögonen till dem. En väldigt medveten och förväntad design.</p>
    </div>
</div>

<!--
Hallands Nyheter:
Nav                 VIT     =   #FFFFFF ~
Bakgrund            GRÅ     =   #F3F3F3 ~
Logga / Accenter    BLÅ     =   #0A5582 ~
Footer              BLÅ     =   #0A324B
Prenumenera         GRÖN    =   #00c389 ~

H1, H2, H3  =   "Gothia Serif",Serif
brödtext    =   Georgia,'Times New Roman',Times,serif
-->
### Hallands Nyheter:

<div class="site-result">
    <img src="%base_url%/content/analysis/img/hallands_nyheter.png" alt="Hallands Nyheter" class="analysis-img">
    <h4>Färgschema:</h4>
    <table style="border-spacing: 4px; border-collapse: separate">
        <tr>
            <td style="height: 50px; width: 50px; background-color: #FFFFFF; border: 1px solid grey;">
            <td style="height: 50px; width: 50px; background-color: #F3F3F3; border: 1px solid grey;">
            <td style="height: 50px; width: 50px; background-color: #0A5582; border: 1px solid grey;">
            <td style="height: 50px; width: 50px; background-color: #0A324B; border: 1px solid grey;">
            <td style="height: 50px; width: 50px; background-color: #00C389; border: 1px solid grey;">
        </tr>
    </table>
    <div>
        <p>Färgschemat på denna sidan består av två huvudsakliga vita färger för bakgrunder, två blåa för mindre accenter och en lite grönare färg för prenumenerings-knappen.</p><br>
        <h4>Typsnitt:</h4> <br>
        <p>Denna sidan använder sig av välkända serif typsnitt nästan överallt.</p><br>
        <p><b>h1, h2, h3:</b> "Gothia Serif", Serif </p><br>
        <p><b>Brödtext:</b> Georgia, 'Times New Roman', Times, serif</p><br>
        <p>Valet av serif-typsnitt iställer för sans-serif ger en känsla av ålder vilket jag tror är målet. Jag tror dem strävar efter känslan av "en gammal lokaltidning".</p>
    </div>
</div>


Analys
-----------------------

<!-- Diskutera och analysera de resultaten du fann. -->
Vid första intrycket så är likheterna mellan sidorna är onekliga, layouten är näst intill identiska över alla sidorna trots att motiveringen och fokuset bakom sidan är olika. Alla har en större artikel med bild högst upp som förhoppningsvis fångar läsaren direkt och sedan under denna följer mindre artiklar om saker som förmodligen inte är anses som lika intressanta. Aftonbladet och SVT använder sig även flitigt av stor text, oftast färgad röd som signalfärg, högst upp för att locka ögonen till det senaste som precis har hänt. Anledningen till att Hallands Nyheter inte använder sig av detta skulle jag gissa beror på att deras artiklar handlar om små lokala händelser och inte stora nationella / internationella händelser som skulle motivera användningen av signalfärger.

När vi sedan börjar scrolla så ser vi lite olika resultat. På SVT och HN så verkar det som att ett mönster repeteras, en ny större bild dyker upp som sedan följs av ett fåtal mindre artiklar. Detta mönster verkar repeteras för varje ny kategori ("nöje", "coronapandemin", "sport", osv.) tills dess man når sidans footer. Aftonbladet använder sig istället av en "oändlig scroll" där flera artiklar ständigt laddas in när man når botten på sidan.

Vad man kan lära sig utav denna analys är hur våra ögon reagerar på färger och textstorlek och hur dessa nyhetssidor sedan använder sig av denna biologiska programmering för att rikta folks uppmärksamhet till det som händer i världen.


Referenser
-----------------------

<!-- Ange de eventuella referenser du använder dig av, om några. -->
<p>-</p>

Övrigt
-----------------------

<!-- Skriv ditt eget namn samt vilka gruppmedlemmar som deltog i att författa rapporten. -->
Skriven utav Hannes Öhman

