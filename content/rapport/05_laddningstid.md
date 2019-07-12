Laddningstid
=======================

Skriv en eller två rader om vad uppgiften handlar om.

Urval
-----------------------
https://www.boringcompany.com/
https://www.tesla.com/
https://www.spacex.com/


Metod
-----------------------

Berätta kort om din "metod", hur du gör för att utföra undersökningen. Berätta om du använder något speciellt verktyg.

Jag skapar ett google kalkylark och sedan går jag igenom mitt urval och kollar pagespeed och dev tools för att få fram Pagespeed overall rating, Förbättringar och dev tools för 
laddnings tid. 

Jag jobbar igenom dessa med att börja kolla mobil på pagespeed sedan dator.  Detta gör jag tre gånger för att få ett medelvärde. 
Efter går jag och kollar med dev tools och kollar detta tre gånger. Jag lägger märke till vilka resurser som laddas in och hur många. 

Resultat
-----------------------
Excelark 
[spreadsheet mer detaljer osv](https://docs.google.com/spreadsheets/d/1hxxQWuSRnyqxXg1d28r8IeiqjKvStjUKbQ62hNCsiqY/edit?usp=sharing)

### Spacex
[FIGURE src="image/spacex.png?h=500" class="right" caption="Bild på spacex"]

<table style="border-spacing: 4px; border-collapse: separate">
<h3> Mobil </h3>
<tr>
<td>PageSpeed overall rating </td>
<td>Förbättringar </td>
</tr>
<tr>
<td>83</td>

<td>Skicka bilder i modernare bildformat </td>
</tr>

</tr>
<tr>
<td></td>
<td>Använd bilder med rätt storlek</td>
<tr>
<td></td>
<td>Ta bort resurser som blockerar renderingen </td>
</tr>
<tr>
<td></td>
<td>Ta bort oanvänd CSS </td>
</tr>
</table>

<table style="border-spacing: 4px; border-collapse: separate">
<h3> Dator </h3>
<tr>
<td>PageSpeed overall rating </td>
<td>Förbättringar </td>
<td>Dev tools laddbnings tid </td>
<td>Resurser</td>
<td>Storlek</td>
</tr>
<tr>
<td>66</td>
<td>Skicka bilder i modernare bildformat </td>
<td>648 ms </td>
<td>22st </td>
<td>3.76mb </td>
</tr>

</tr>
<tr> 
<td></td>
<td>Koda bilder effektivt </td>
</tr>
<tr>
<td></td>
<td>Använd bilder med rätt storlek</td>
</tr>
<tr>
<td></td>
<td>Ta bort resurser som blockerar renderingen </td>
</tr>
<tr>
<td></td>
<td>Ta bort oanvänd CSS </td>
</tr>
</table>


### Tesla
[FIGURE src="image/tesla.png?h=500" class="right" caption="Bild på Tesla"]

<table style="border-spacing: 4px; border-collapse: separate">
<h3> Mobil </h3>
<tr>
<td>PageSpeed overall rating </td>
<td>Förbättringar </td>
</tr>
<tr>
<td>22</td>
<td>Skicka bilder i modernare bildformat </td>
</tr>

</tr>
<tr> 
<td></td>
<td>Koda bilder effektivt </td>
</tr>
<tr>
<td></td>
<td>Använd bilder med rätt storlek</td>
</tr>
<td></td>
<td>Minifiera JavaScript</td>
</tr>
<tr>
<td></td>
<td>Ta bort resurser som blockerar renderingen </td>
</tr>
<tr>
<td></td>
<td>Ta bort oanvänd CSS </td>
</tr>
</table>

<table style="border-spacing: 4px; border-collapse: separate">
<h3> Dator </h3>
<tr>
<td>PageSpeed overall rating </td>
<td>Förbättringar </td>
<td>Dev tools laddbnings tid </td>
<td>Resurser</td>
<td>Storlek</td>
</tr>
<tr>
<td>98</td>
<td>Skicka bilder i modernare bildformat </td>
<td> 1.45s </td>
<td> 108 </td>
<td> 4.2mb </td>
</tr>

</tr>
<tr> 
<td></td>
<td>Koda bilder effektivt </td>
</tr>
<tr>
<td></td>
<td>Använd bilder med rätt storlek</td>
</tr>
<td></td>
<td>Använd bilder med rätt storlek</td>
</tr>
<tr>
<td></td>
<td>Ta bort resurser som blockerar renderingen </td>
</tr>
<tr>
<td></td>
<td>Ta bort oanvänd CSS </td>
</tr>
</table>




### Boringcompany
[FIGURE src="image/boringcompany.png?h=500" class="right" caption="Bild på Boringcompany"]
<table style="border-spacing: 4px; border-collapse: separate">
<h3> Mobil </h3>
<tr>
<td>PageSpeed overall rating </td>
<td>Förbättringar </td>
</tr>
<tr>
<td>48</td>
<td>Skicka bilder i modernare bildformat </td>
</tr>

</tr>
<tr> 
<td></td>
<td>Skicka bilder i modernare bildformat </td>
</tr>
<tr>
<td></td>
<td>Använd bilder med rätt storlek</td>

<tr>
<td></td>
<td>Ta bort resurser som blockerar renderingen </td>
</tr>
<tr>
<td></td>
<td>Ta bort oanvänd CSS </td>
</tr>
</table>

<table style="border-spacing: 4px; border-collapse: separate">
<h3> Dator </h3>
<tr>
<td>PageSpeed overall rating </td>
<td>Förbättringar </td>
<td>Dev tools laddbnings tid </td>
<td>Resurser</td>
<td>Storlek</td>
</tr>
<tr>
<td>85</td>
<td>Skicka bilder i modernare bildformat </td>
<td> 1.75s </td>
<td> 45st </td>
<td> 4.0mb </td>
</tr>

</tr>
<tr> 
<td></td>
<td>Ta bort resurser som blockerar renderingen </td>
</tr>
</table>


Analys
-----------------------

Det mest typiska som slöar ner dessa sidorna verkar vara bilderna. Det verkar vara att de inte är i modernt format och att de har fel storlek vilket gör att de måste krympa de när 
de väl ha laddat in. 

När det är mobilt verkar det vara mest att de har onödig CSS som inte behövs och dåligt bild format. 

Men tydligen har både datorer och mobiler problem med att ta bort resurser som blockerar rendering. 

Referenser
-----------------------

Ange de eventuella referenser du använder dig av, om några.

Övrigt
-----------------------

Skriven av Sam Pettersson.