---
Title: Analyser
Description: Rapport om laddningstid
---

Laddanalys
==========================

Denna uppgift syftar till att dokumentera och analysera olika webbplatsers laddningstid. I syftet ingår även att argumentera gällande eventuella förbättringar avseende laddningstid och användbarhet.

&nbsp;

Urval
-----------------------

Jag valde att undersöka olika nyhetssidor för att se hur olika hemsidor inom samma kategori fungerar.

Följande hemsidor valdes ut för undersökningen:
* https://www.dn.se/
* https://www.svt.se/
* https://www.expressen.se/

&nbsp;

Metod
-----------------------

De mer mått som användes var DevTools/Inspektera för varje webbplats för att på så sätt få fram information om laddningstiden, sidans storlek och antal resurser.
Google Pagespeed användes för att få ytterligare information om olika typer av laddningstid.  

&nbsp;

Resultat
-----------------------

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRmEgdI__LK8zu1lS3hlJ38MfzI_jxE7KoQgaLzt6lZw1llalojam5CUtlkPHV2PhsW-6BEhaL1p_q4/pubhtml?widget=true&amp;headers=false" title="Resultat"></iframe>

### DN

![DN](%assets_url%/img/DN_2022_11_27.png)

DN skulle bland annat kunna förbättra sin tillgänglighet på datorn genom att se till att alla bilder har alt-attribut, se över länknamn samt kontrast mellan bakgrundsfärg och förgrundsfärg.

&nbsp;

### SVT

![SVT](%assets_url%/img/SVT_2022_11_27.png)

SVT skulle kunna förbättra sin mobila prestanda genom att uppdatera sin JavaScript, minifiera/reducera (minify) sin CSS och JavaScript och ta bort kod som inte används.

&nbsp;

### Expressen

![Expressen](%assets_url%/img/Expressen_2022_11_27.png)

Expressen skulle kunna förbättra sin mobila prestanda genom att uppdatera sin JavaScript, minifiera/reducera (minify) och sin JavaScript-kod.

&nbsp;


Analys
-----------------------

Överlag verkar sidorna få sämre resultat när det gäller deras mobilversioner avseende prestanda. DN och Expressen skulle även kunna arbeta lite grann på att öka sin tillgänglighet på deras datorbaserade webbplatser. Generellt får dock alla sidor ändå bra resultat.
Bedömer även att alla webbplatser laddar snabbt, runt en sekund. Tycker att om det tar mer än 2-3 sekunder så hinner man som användare reagera på att vissa delar dyker upp snabbare än andra.

&nbsp;

Referenser
-----------------------



Övrigt
-----------------------

Denna analys och rapport genomfördes enskilt utav mig.
