Titel på rapporten
=======================

Denna uppgift syftar till att undersöka och analysera prestandan på tre populära svenska webbplatser (Blocket, Hemnet och DN) genom att mäta deras laddningstider och föreslagna optimeringar baserat på data från Google PageSpeed Insights.

Urval
-----------------------

De tre webbplatser som valts för denna studie är Blocket.se, Hemnet.se och DN.se. Blocket är en stor marknadsplats för begagnade varor, Hemnet är en populär plattform för bostadsannonser, och DN är en nyhetswebbplats. Dessa sidor har valts eftersom de besökts ofta och innehåller ett stort antal bilder och annat som måste laddas, vilket gör dem intressanta att analysera ur ett prestandaperspektiv. Genom att studera dessa sidor kan vi få en bättre förståelse för prestanda.

Metod
-----------------------

För att samla in data har jag använt Google PageSpeed Insights för att mäta prestandapoäng, vilket ger en indikation på hur bra sidan är optimerad för användarupplevelse och laddningstid. Jag använde artikeln "Moz om Page Speed" som referens för att tolka resultaten, samt Google PageSpeed Insights för att förstå hur laddningstider påverkar webbplatsens prestanda. Data dokumenterades i en tabell. Jag kommer även att använda DevTools i webbläsaren för att mäta laddningstider och analysera sidans prestanda.

Resultat
-----------------------

I denna studie undersöktes laddningstiderna för tre svenska webbplatser: Blocket, Hemnet och DN. Laddningstiderna mättes med hjälp av Google PageSpeed Insights och WebDevTools för att utvärdera webbplatsens optimering och användarupplevelse. Laddningstiden, eller "Page Load Time", refererar till den tid det tar för en webbsida att fullständigt ladda och bli interaktiv, vilket inkluderar hämtning och rendering av alla resurser såsom bilder, JavaScript, CSS och externa filer.

prestandapoäng - ger en indikation på hur bra sidan är optimerad för användarupplevelse och laddningstid.

Skala på poäng lägre är sämre.
<p class="red"> 0–49 (låg)</p> 
<p class="yellow"> 50–89 (medel) </p>  
<p class="green"> 90–100 (hög)</p> 
<h2>Tabell med poäng och laddningstider</h2>



<table class="loadtime">
    <thead>
        <tr>
            <th>Website</th>
            <th> Mobile score <br>(Google ps)</th>
            <th>Desktop score <br> (Google ps)
            <th> LoadTimes <br> (WebDevTool)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Blocket.se</td>
            <td>42</td>
            <td>49</td>
            <td>9.90 s</td>
        </tr>
        
 <tr>
            <td>hemnet.se</td>
            <td>64</td>
             <td>69</td>
             <td>13.3 s</td>
        </tr>
        <tr>
            <td>dn.se</td>
            <td>92</td>
            <td>88</td>
            <td>20,27 s</td>
        </tr>
    </tbody>
</table>


<div class="borderbottom">
<h2>Blocket</h2>
    <a href="https://blocket.se">
        <img class="pic"src="../image/blocket.png?w=640" alt="snapshot blocket">
        <table class="loadtime">
            <thead>
                <tr>
                    <th>Antal resurser</th>
                    <th>Överfört data</th>
                    <th>Total storlek</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>123</td>
                    <td>2,93 MB </td>
                   <td>9.23 MB</td>
                </tr>
                </tbody>
        </table>
        Blocket.se presterade med de lägsta poängen i både mobil och desktop (42 respektive 49). Detta indikerar en betydande optimeringspotential. En stor orsak till de laddningstiden är javascriptet.
    </a>
</div>


<div class="borderbottom">
    <h2>Hemnet</h2>
    <img class="pic" src="../image/hemnet.png?w=640" alt="snapshot blocket">
    <table class="loadtime">
                <thead>
                    <tr>
                        <th>Antal resurser</th>
                        <th>Överfört data</th>
                        <th>Total storlek</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                    <td>174</td>
                      <td>2,18 MB</td>
                      <td>9.04 MB</td>
                        </tr>
                    </tbody>
            </table>
            Hemnet har relativt bra poäng på pagespeed, men det finns fortfarande utrymme för förbättring för att ytterligare optimera prestandan.
</div>
<img class="pic" src="../image/dn.png?w=640" alt="snapshot blocket">

<div class="borderbottom">
    <h2>DN</h2>
    <img class="pic" src="../image/hemnet.png?w=640" alt="snapshot blocket">
    <table class="loadtime">
                <thead>
                    <tr>
                        <th>Antal resurser</th>
                        <th>Överfört data</th>
                        <th>Total storlek</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                    <td>335</td>
                      <td>5.48 MB </td>
                      <td>2,75 MB</td>
                        </tr>
                    </tbody>
            </table>
          DN har bra poäng på pagespeed, Sidan har mer data att ladda på första sidan. Trorts höga laddningstider så har dom optimerat sidan på ett bra sätt.
</div>
Analys
-----------------------
Blocket presterade lägst med en mobil poäng på 42 och en desktop poäng på 49, vilket indikerar en betydande förbättringspotential. Laddningstiden för sidan var 9,90 sekunder, vilket kan bero på tunga resurser som JavaScript, som inte är tillräckligt optimerade. Detta innebär att det finns stor potential att förbättra användarupplevelsen genom att minska filstorlekar och optimera JavaScript.

Hemnet hade en bättre poäng på både mobil (64) och desktop (69), vilket tyder på en mer optimerad sida. Trots detta, med 174 resurser finns det fortfarande möjlighet att ytterligare förbättra laddningstiden. Här kan man t.ex. optimera javascript.

 DN har optimerat sina resurser på ett bra sätt, även om den höga mängden resurser  bidrar till den längre laddningstiden. Om DN kan minska antalet externa resurser, skulle prestandan kunna förbättras ytterligare och laddningstiden minska.

Så för att sammanfatta: trots en längre laddningstid än de andra sidorna, har DN den bästa optimeringen när det gäller PageSpeed-poäng, vilket innebär att de har arbetat effektivt med prestandaförbättringar.

<h2>Rangordning </h2>
1. DN (Dagens Nyheter)

    Mobilpoäng: 92
    Desktoppoäng: 88
    Laddningstid (WebDevTools): 20,27 s
    
    Trots längre laddningstid och att det är mer att ladda så är den snabbast i förhallande till resurser osv.

2. Hemnet
    Mobilpoäng: 64
    Desktoppoäng: 69
    Laddningstid (WebDevTools): 13,3 s
    
    Hemnet visar en bra balans mellan prestanda och optimering, även om det finns utrymme för förbättringar. Laddningstiden är relativt bra, men den kan optimeras ytterligare, särskilt genom att minska antalet resurser och storleken på dessa.

3. BLocket Mobilpoäng: 42
   Desktoppoäng: 49
   Laddningstid (WebDevTools): 9,90 s


Upplevde 20 sek ok så gränsen är där någonstans för min del.

Blocket hade de lägsta poängen på både mobil och desktop och därmed stor optimeringspotential. Men upplevde den lite långsam. Laddningstiden är rimlig.

DN har en laddningstid på 20,27 sekunder, vilket är långsamt men upplevde att den laddade snabbare än så. (obs) Denna tid är för att ladda hela sidn.

Hemnet ligger på 13,3 sekunder, vilket är acceptabelt.
Blocket har en laddningstid på 9,90 sekunder, vilket är under min gräns och därmed uppfattas som relativt snabb.



Övrigt
-----------------------

Daniel