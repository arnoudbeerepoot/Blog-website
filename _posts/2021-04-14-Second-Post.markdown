---
layout: post
title:  "Een gebruikte auto van welk merk kun je het beste kiezen?"
date:   2018-09-14 18:58:15 +0100
categories: jekyll
---
## Analyse van het aantal auto’s per merk per leeftijd

Op het moment dat je een gebruikte auto wilt kopen, vraag je vaak advies bij vrienden of familie. Vaak krijg je dan een uiteenlopend advies, zoals dit merk moet je zeker niet kopen,
want deze auto’s zijn niet betrouwbaar of hebben veel onderhoud nodig, roesten en noem maar op. Ook krijg je dan advies wat je wel moet kopen. Maar is dit advies nu wel juist en is het objectief?

De vraag die ik mezelf daarom stelde was: Als ik een auto van 10 jaar oud wil kopen, is het dan mogelijk om op basis van data-analyse van het huidige wagenpark in Nederland mogelijk
om te bepalen welk merk je het beste kunt kopen?

# Gegevens verzamelen

Ik heb ervoor gekozen om de analyse uit te voeren op de dataset van het huidige wagenpark in Nederland. Deze dataset is beschikbaar als open dataset via deze [link](https://opendata.rdw.nl/Voertuigen/Open-Data-RDW-Gekentekende_voertuigen/m9d7-ebf2)

De eerste stap in de analyse is het maken van de juiste selectie van data uit de dataset, aangezien er heel veel merken bestaan. Zonder een selectie is het lastig om een overzichtelijke analyse te maken.

De selectie die gekozen is allereerst Personenauto en daarnaast worden alleen merken meegenomen waarvan er minimaal 10.000 in Nederland rondrijden. Dan blijven de 36 grootste merken over.

Voor de analyse zijn ook verkoopgegevens nodig. De verkochte aantallen per merk per jaar zijn [hier](https://www.autoweek.nl/verkoopcijfers/) te vinden.

# Analyse

De volgende stap is het starten van de analyse. Het uitgangspunt daarbij is mensen langer doorrijden in auto’s die weinig onderhoud nodig hebben, dus auto’s die het altijd doen en waar de mensen tevreden over zijn.
Doordat mensen hier langer in doorrijden is het gevolg dat ze later gesloopt of geexporteerd worden. De gemiddelde leeftijd van deze auto’s zal dus hoger zijn.

In eerste instantie is de analyse daarom gestart met het bepalen van de gemiddelde leeftijd per merk en aan de hand daarvan het beste merk bepalen. Na het berekenen van de gemiddelde leeftijd is gebleken dat het moeilijk is om daar conclusies aan te verbinden. Daarom is daarna een nieuwe analyse methode geprobeerd.

De nieuwe methode die gebruikt is, is hoeveel van de origineel in Nederland verkochte auto’s rijden er nu nog rond in Nederland. Om de vergelijking tussen merken mogelijk te maken, is er voor gekozen om alles terug te rekenen naar 10.000 origineel in Nederland verkochte auto’s. Dit resulteert in het berekenen van het aantal auto’s per merk en per jaar dat nu nog in Nederland geregistreerd is per 10.000 nieuw verkochte auto’s per merk per jaar.

# Resultaat

Het resultaat wordt getoond in een aantal [grafieken](https://infogram.com/aantal-autos-per-merk-en-leeftijd-in-nederland-1hnq411n75kk43z?live). Er is een totaal grafiek met alle merken en daarnaast is er voor een duidelijker beeld een aantal grafieken met een subselectie gemaakt op basis van de herkomst van de verschillende merken. Dit resulteert in een grafiek voor de Japanse, Duitse, Franse en Italiaanse merken. In elke grafiek wordt ook het gemiddelde aantal van het totaal getoond. Op deze manier kan bekeken worden per merk per jaar of deze het beter of minder goed doet dan het gemiddelde.

<script id="infogram_0_b2505b1e-fb50-4dbc-a66c-c84b50e9cb86" title="Aantal auto&amp;amp;#39;s per merk en leeftijd in Nederland" src="https://e.infogram.com/js/dist/embed.js?7dY" type="text/javascript"></script><div style="padding:8px 0;font-family:Arial!important;font-size:13px!important;line-height:15px!important;text-align:center;border-top:1px solid #dadada;margin:0 30px"><a href="https://infogram.com/b2505b1e-fb50-4dbc-a66c-c84b50e9cb86" style="color:#989898!important;text-decoration:none!important;" target="_blank">Aantal auto's per merk en leeftijd in Nederland</a><br><a href="https://infogram.com" style="color:#989898!important;text-decoration:none!important;" target="_blank" rel="nofollow">Infogram</a></div>


In het algemeen is in de grafieken te zien dat het aantal auto’s na het tiende levensjaar snel afneemt. Dit loopt door totdat de auto’s ongeveer 20-25 jaar oud zijn. Dan zijn alleen de oldtimers nog over. Daarnaast is het ook opmerkelijk dat het gemiddelde van het jaar 2007 een dip toont. Deze dip is ook te zien bij populaire merken zoals Volkswagen en Audi. Deze dip is te verklaren door het aantal auto’s dat geëxporteerd wordt uit Nederland. Bepaalde jaren zijn populairder voor de export dan andere. Hier moet wel rekening mee gehouden worden in deze analyse.

Uit de Japanse grafiek is te zien dat de merken Suzuki, Daihatsu en Toyota het in de jaren tot 1994 beter doen dan het gemiddelde.

In de Duitse grafiek is te zien dat in de jaren voor 2000 Porsche verreweg de hoogste aantallen heeft van alle merken. Dit is te verklaren doordat dit een echte verzamelauto is, die jarenlang bewaard wordt en waarvan er weinig gesloopt worden.

In de Franse grafiek is te zien dat deze het gemiddelde volgen. In de Italiaanse grafiek is te zien dat deze voor een groot deel onder het gemiddelde liggen.

# Conclusie

Het is moeilijk om te bepalen welk merk nu het beste is. Wel is het mogelijk om per jaar te bekijken van welk merk nog de meeste auto’s in Nederland op de weg zijn. Op de vraag uit het begin van deze blog, welk merk van 15 jaar oud is de beste, is het antwoord volgens deze analyse dus: Suzuki. Misschien wel onverwacht, maar dat is ook de reden voor het uitvoeren van deze analyse. Laat de data spreken in plaats van de goedbedoelde adviezen van vrienden en familie.

