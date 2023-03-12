# Arbeidskrav-1
Velkommen til Olavios arbeidskrav 1.

Frontend repository:
https://github.com/OlavioHstudent/instrumentFE_WF

Backend repository:
https://github.com/OlavioHstudent/instrumentBE

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Hadde satt pris på om dette arbeidskravet kunne vært en presentasjon, så jeg får vist og forklart alt :D
Jeg er stort sett alltid på skolen på dagtid; tlf: 98602835, eller nede i D1-44.

Jeg har fulgt arbeidskravet ved siden av presentasjonene som har blitt lagt ut på Canvas. Enkelte utydeligheter i arbeidskravet vil gjenspeile seg i programmet.

Login:

----BACKEND----
- Velg en port og en IP-addresse for å lytte på disse.

----FRONTEND----
- Koble til en IP og port som blir lyttet på av backend

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Write to file:
Instrument lagres når man trykker "register new".
Sensordata lagres når man stopper kontinuerlig lesing.
Har et sånt oppsett fordi jeg vil bake det mer inn med de andre arbeidskravene, og vet ikke om jeg vil appende med dato og tidsstempling eller lage nye filer hver gang. osv.

Jeg tror jeg har gjort alt som trengs for å tilfredsstille hva jeg tror er arbeidskrav 1.
Designinitiativet mitt var mer tidkrevende enn forventet, så dette er lagt på is inntil videre.

Noen krav til funksjonalitet har vært litt utydelig, og noe av det vil nok gjenspeile seg i programmet. Som for eksempel "writeconf", som per nå fryser hele greia for jeg vet ikke hva det er til.
Det kan sikkert hende at det har en sammenheng med instrumentlista?

Ekstra kommentarer:
- Etter forslag fra Odd, har jeg oppsøkt andre medstudenter og sammenlignet prosjektet mitt med 
dem for å finne ut av hvorfor jeg ikke kan bruke samme "charts" som dem. Alt er identisk; årsak er uvisst.
Pga dette bruker jeg ScottPlot, som ser for jævlig ut.

- Husk å lukke backend fra task manager når du lukker frontend. Om du ser i koden min, 
så skal backend bli synlig igjen og lede til shutdown ved frontend-quit, men det skjer ikke. Samme datatransferlogikk som alle andre steder. Finner fort ut av det

- Håper dere liker programmet mitt, og at det funker på deres maskin, for det funker fjell her. 
Kontakt med dersom dere har execute issues så kan jeg streame til dere over Discord fra maskinen min hjemme.
(har opplevd at andre har hatt issues med VS-prosjektet mitt på sin maskin).
