---
Title: Kmom11
Description: Part 1
Template: analys
---

Laddningstider.
=======================

Organisationen Valfrihet har bett mig analysera webbplatsen för konstnären Kim inom ramarna av bilder och mäta laddningshastigheten och hur man potentiellt skulle kunna förbättra den.

Urval
-----------------------

Denna analys har organisationen Valfrihet bett mig att göra och de valde vilken hemsida jag skulle analysera. Länken till hemsidan finns under referenser.

Metod
-----------------------

Jag använde mig av Googles pagespeed insight för att mäta laddningstiden, där sidan får ett betyg ifrån 0 - 100, jag använde även mig av devtools i google chrome för att mäta laddningstid, storlek på sidan och antal resurser som laddas. Svaren där fick man i MB och i sekunder/minuter.
Länken till google insights finns under referenser.

Resultat
-----------------------

Resultaten för laddningshastighet finns i ett google sheets ark, länken till detta finns under rubriken referenser.

## Kims hemsida
<img src="../assets/img/kims_hemsida_screenshot.png" width="1000" height="500" alt="Bild av Kims hemsida" />

Hemsidan åt artisten Kim presterar enligt google PageSpeed Insights bra. Medelvärdet för desktop när jag har kört hemsidan fem stycken gånger blev 94 av 100. Resultatet av lika många försök på mobile blev 90 av 100.  

Generella intrycket av sidan är att den laddar in väldigt fort både på desktop och mobile. Sidan är relativt stilren och ganska minimalistisk och har ett lagom antal element. Det verkar som att sidan fungerar väldigt bra på desktop och har inte många element som kan göra så att sidan fungerar exponentiellt mycket bättre. Det verkar som det största problemet sidan har på desktop det största problemet med Largest Contentful Paint (LCP). Vilket är hur lång tid det tar att ladda den största bilder eller text-blocket som finns på hemsidan. I detta fall är det nog den stora bilden på Kim som är det första man ser som bidrar till detta. På mobile får sidan ett lite sämre resultat än vad det gör för desktop. Largest Contentful Paint verkar även här vara en del av problemet. Men även Cumulative Layout Shift (CLS), vilket står för att sidan förändras när man väl är inne på sidan. T.ex. när man läser en text och helt plötsligt är någon annanstans på sidan.  

För att lösa dessa problem kan man med CLS bestämma vilken storlek bilden ska ha innan sidan börjar ladda in bilden. Alltså I HTML eller CSS.
För att lösa problem med LCP kan man göra bilderna mindre för att optimera hemsidan och göra så att den går att ladda fortare.


Analys
-----------------------
När man analyserar sidor för hastigheten kan det vara lite förvirrande och missvisande att bara kolla på siffrorna. Visst om sida har låga siffror kan det betyda att sidan fungerar dåligt. Men några av de sidorna jag har analyserat i mina studier har haft dåliga betyg men det är inget som man märker av som besökare av sidan. Denna sida tycker jag fungerar bra och det är inte direkt några problem som man kan se som besökare. Den skulle kunna ladda lite snabbare när man först besöker den men det är absolut inget man irriterar sig över och det tar cirka 1.5 sekund för sidan att kunna ladda. Så länge det känns bra brukar det inte oftast vara några problem.  

Jag nämner det för att vissa sidor behöver ladda in mer än andra sidor och kommer då troligtvis då få mindre betyg, samma sak gäller om man väljer att lägga till vissa element på en sida. Det viktigaste är att det inte är några problem för besökaren när den går in på hemsidan. T.ex. om man skalade ner den stora bilden på Kims hemsida skulle den nog ladda snabbare men den bilden ger också besökaren en gott intryck om sidans budskap. Om den var mindre kanske inte budskapet skulle bli lika tydligt. Det är en balansgång med att lägga till flera element på en hemsida så att den fungerar snabbt och bra ifrån ett teknisk perspektiv men även så att den är snyggt designat ifrån ett designperspektiv.  
Men om man har ett sådant problem kan det istället handla om problemlösning vad kan man göra så att sidan laddar snabbare och har en design som passar med syftet med hemsidan. T.ex. istället för att ha en stor bild kanske mindre bilder som bildar en större helhet. Men som sagt fungerar hemsidan bra och det är inte riktigt något man stör sig på när det gäller laddningstid.  

Den officiella laddningstiden för sidor kommer variera för vilket syfte sidan har. Är sidan en portfolio sida som denna kommer det nog gå väldigt snabbt att ladda eftersom det inte är lika många element som behöver laddas in. Men om det är en streaming sida kommer den officiella laddningstiden troligtvis vara längre. Det viktigaste är hur det känns för besökaren. Har sidan en lång officiell laddningstid och är trög att komma in på är det ett problem. Men om sidan har en lång officiell laddningstid men det går fort att komma in på sidan och det går smidigt borde det inte vara något problem alls. Kims hemsida laddas snabbt och passar en bra standard.

Referenser
-----------------------

http://www.student.bth.se/~magv20/dbwebb-kurser/design/me/kmom10/  
https://docs.google.com/spreadsheets/d/1OwKg4zLNvx1ewSoZfGayyyLSehatzHiG1jND3M1KWUg/edit?usp=sharing  
https://developers.google.com/speed/pagespeed/insights/  

Övrigt
-----------------------

Jag har gjort denna rapport själv!
