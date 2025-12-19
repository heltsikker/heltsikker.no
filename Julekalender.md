---
layout: page
title: Julekalender 2025
---
## Oppgave 3: Misbruk av nettside (SQL)

### Beskrivelse

Santa's Workshop har nylig digitalisert snill og slemme-listene for bedre kommunikasjon mellom Mr.Claus selv og alvene.
Da skal det i teorien være bedre flyt i arbeidet om å lage gavene. Mrs. Claus, som er litt usikker på sikkerheten på siden, er beskymra for barnas sikkerhet. 

Kan noe gå galt? Er det mulig for noen på innsidn å gjøre noe med vonde hensikter?

Hun har spurt deg om å ta en sjekk!

Ingen informasjon som skal brukes til å kontakte barna skal være mulig for alvene å få tak i. Da kan magien bli borte!


Hun sendte deg midlertidig brukernavn og passord og en link for å ta en sjekk:
http://178.18.253.120:8002 <br/>
username: admin <br/>
password: admin <br/>

### OBS!
Vi ber deg om å ikke endre på databasen da dette kan påvirke oppgaven for andre.

### Ledetråd

_Hvor mye henter vi ut fra databasen? Funker det bedre om du finner navn og type på dem?_

Lever flagget i formatet: **HSCTF{flagget}** Til kim@heltsikker.no eller christian@heltsikker.no

## Oppgave 2: Datatyveri fra Nordpolen (Forensics)

### Beskrivelse

Foreleseren stirrer på skjermen. Linjer med kode danser over terminalen, mens pulsen hans øker i takt med blinkingen fra nettverksmonitoren. Noe er galt. Veldig galt.

I et desperat forsøk på å forstå hva som foregår, begynner han å overvåke webtrafikken fra jobb-PC-en. Det han finner, fryser blodet hans: En ukjent enhet har koblet seg til nettverket. IP-adressen peker — urovekkende nok — mot et sted langt mot Nordpolen.

Pakker med data har blitt lastet opp dit, sendt gjennom et nett av DES-krypterte HTTP-forbindelser, med et svakt passord.

Julenissen har stjålet foreleserens data.

Kan du hjelpe foreleseren med å avsløre hva Julenissen stjal … før hele Høytek havner på den slemme listen?

### Ledetråd

*Nissen er ikke så flink med kryptering som han tror. Et svakt passord og en utdatert algoritme kan være hans bane.*


### Filer

[Last ned capture2025.pcapng](/public/capture2025.pcapng)

### Oppgave

Analyser nettverkstrafikken i pcap-filen og finn de krypterte dataene som ble sendt til Nordpolen. Dekrypter innholdet og finn ut hva som ble stjålet.

Lever flagget i formatet: **HSCTF{flagget}** Til kim@heltsikker.no eller christian@heltsikker.no

----------

## Oppgave 1: Den glemte linjen (OSINT/NYBEGYNNER)

### Beskrivelse

En gammel historie har våknet til live i gangene på Høyteknologisenteret.

De eldste studentene (og noen forelesere) hvisker om "testflyvningen i 2010". <br/>
Før Nissen digitaliserte alle systemene, trengte han en fysisk og sikker linje for å rapportere status til verkstedet på Nordpolen. <br/><br/>
Et gammelt Google Street View-bilde fra september 2010 skal visstnok vise denne midlertidige utposten: en liten, rød bygning gjemt i fullt dagslys på parkeringsplassen.<br/>
For å skjule den, brukte Nissen visstnok sin favoritt-taktikk: omvendt psykologi. Han ga den et kodenavn så åpenbart at ingen ville tro det var en hemmelighet. Historien sier at Nissen mente det var for åpenbart til at nysgjerrige studenter ville tenke over det.<br/>
Akkurat det ordet skal fremdeles være synlig på bygningen i 2010-bildet.

### Ledetråd

*Rød som nisselue, liten som et pepperkakehus, men bygget for å binde verdener sammen.*

### Oppgave

Bruk Google Street View (historiske bilder fra september 2010) og finn parkeringsplassen ved UiB Høyteknologisenteret.

Inspiser det "røde lille pepperkakehuset" du finner der. Hvilket ord (kodenavn) står skrevet på den?

Lever flagget i formatet: **HSCTF{ordet}**

![Nissen foran Høyteknologisenteret i Bergen](/public/julekalender/Kalender25-Luke1.png)
