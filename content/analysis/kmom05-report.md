---
Title: Kmom05
Description: Part 1
Template: analys
---

Laddningshastighet och bilder
=======================

I denna uppgift ska vi undersöka tre stycken olika hemsidor för att mäta laddningshastigheten och hur man potentiellt skulle kunna förbättra laddningstiden på hemsidorna.

Urval
-----------------------

De sidorna jag har valt att undersöka är Apple, Twitch och Amazon.(Länkar till hemsidorna finns under rubriken referenser) Anledningen till varför jag valde att analysera dessa sidor är för att de är alla väldigt kända företag och kommer dyka upp först om man söker efter dem, dem har en stor budget för att göra en snygg och välfungerade hemsida.
I denna undersökning ska jag ta reda på om dem faktiskt har en snabb laddningshastighet

Metod
-----------------------

Efter att ha valt ut mina hemsidor använde jag mig av Googles pagespeed insights för att mäta laddningstiden, där sidan får ett betyg ifrån 0 - 100, jag använde även mig av devtools i google chrome för att mäta laddningstid, storlek på sidan och antal resurser som laddas. Svaren där fick man i MB och i sekunder/minuter.

Resultat
-----------------------

Resultaten hittar du i google sheets, länken finns under rubriken Referenser.    

Hur webbplatserna kan förbättra sig:

## Apple

Apples sida laddade väldigt fort och det kändes verkligen som det var snabbt och smidigt. Till skillnad ifrån de andra sidorna är apples hemsida mycket mer simpel och stilren och det passar med deras märke. Det problemet som apples sida verkar ha är First Contentful Paint, vilket är det första en person ser när de besöker en hemsida, vilket i detta fall tar lång tid att ladda, efter gjort lite egen forskning är ett sätt att göra så att det laddar fortare är att flytta vissa element ifrån head till andra delar eftersom head delen laddas absolut först och på det sättet går det snabbare för man behöver ladda in mindre saker i början.

## Amazon

Amazons sida tog relativ lång tid att ladda, det är  extremt mycket olika saker som händer på en gång när man laddar sidan och man känner sig nästan lite överrumplad. Dock så vill dem visa att dem har många saker att erbjuda en så jag kan förstå varför dem har valt att göra så. Det som amazon verkar ha problem med mest var Cumulative Layout Shift. Vilket mäter när element på sidan ändra ifrån ingenstans, det kan bero på element som laddas in sent så som en bild eller video som har okända dimensioner.  
Efter att ha gjort lite egen forskning så sätt man kan lösa detta på är att alltid ha med storlekar på sina bilder och filmer så att den tar redan upp så mycket plats även fast själva filmen inte laddar just först.


## Twitch

Twitch sida tog extremt lång tid på sig att ladda. Dock är det väldigt förståeligt, det är en streaming service för spel så för att locka personer att kolla vill dem att man direkt ska klicka på en video som streamas på förstasidan så därför laddas många live-streams in på en gång. Därför tar sidan så lång tid att ladda. Det verkar som twitch största problem är Largest Contentful Paint. Det verkar även som att sidan har mycket Javascript som inte används så det skulle man kunna ta bort och optimizera för att göra så att laddningen går fortare.

Analys
-----------------------

När man pratar om laddningshastigheten på en hemsida tycker jag att man måste prata om vissa andra aspekter också. T.ex. Hur kan vi kombinera märkets identitet med hemsidan?
Kan vi offra laddningshastighet för att göra så att hemsidan mer passar sitt syfte? Vad är bästa sättet att balansera det på?  
Om man kollar på apples hemsida. Den laddar helt på några sekunder, och den har ett rimligt bra poäng enligt google. Men det är också väldigt enkelt för dem att göra en hemsida som laddar fort för dem behöver inte ha så många element för att Apple är kända för att vara simplistiska.   

Amazon fick väldigt bra poäng av google, det tog relativt långt att ladda sidan, runt 40s men det är även många element som ska få plats också vilket även det passar företaget eftersom man vill få folk att konsumera. Hade inte några stora problem alls när det gällde laddningstiden eller hur sidan funkar. Tycker dock att det är för mycket som händer på denna sidan estetiskt sätt. Även fast laddningstiden var lång märkar man inte av det alls när man är inne på sidan.  
Twitch tog cirka 3 minuter att ladda helt och då hade den inte helt laddat färdigt, kan tänka mig att det är pga. att det är massa livestreams så därför skickas alltid information till sidan, dock vid cirka 3 minuter gick det extremt långsamt fram de gångerna jag kollade därför valde jag att säga att det tog cirka 3 minuter.
För att ha så många stora element på sidan tycker jag att det går väldigt smidigt, sidan laddar fort och man märker inga problem så det var väldigt smidigt.   
Något som alla hemsidor kan förbättra är att det står att alla har mycket Javascript som inte används, är inte rikitgt säker på varför det är så och varför inte webbutvecklarna bara skulle ta bort det för att göra så att det går snabbare.

Enligt resultaten skulle jag säga att Apple funkar bäst, sen kommer Amazon och sedan Twitch. Dock har de helt olika syften och det förvånar mig inte alls att apples sida laddas snabbare, är mindre och använder sig av mindre resurser. Amazon kommer därefter med ett väldigt bra betyg ifrån google men har mycket längre laddningstid än apple om man tänker på hur stor sidorna är. Sedan Twitch, som fungerar väldigt bra måste jag säga men det är mycket som sidan och måste göra på en gång, även fast det tar lång tid att ladda är den absolut störst men den fick väldigt dåligt betyg av google.  

Det är svårt att bestämma en bra laddningstid är eftersom att alla hemsidor har olika syften och sidor kommer i olika storlekar. Det som jag tycker är viktigast är hur hemsidan känns, känns det som det går fort även fast laddningstiden är lång skulle jag säga att hemsidan är snabb. Jag tycker att dem hemsidorna jag har diskuterat om i denna rapport alla är snabba eftersom ingen av de känns som om det tar lång tid även Twitch känns väldigt snabb och om man tar Amazon så för besökaren ser det ut som att den laddar lika snabbt som apple men har tekniskt sätt ungefär 8x så mycket laddningstid.

Referenser
-----------------------

https://www.apple.com/ Besöktes 01-12-2020  
https://www.amazon.com/ Besöktes 01-12-2020  
https://www.twitch.tv/ Besöktes 01-12-2020  

Google sheets: https://docs.google.com/spreadsheets/d/1I-kUSKg3og9pKrJKv0w0sGCJWilAqA83N-fvpBgt9k4/edit?usp=sharing Besöktes 01-12-2020

Övrigt
-----------------------

Jag gjorde denna rapport ensam.
