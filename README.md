# Oppgaveark-2-DB1100
DB1100, oppgaver til forelesning 02

Oppgave 1 - begreper & terminologi
Forklar følgende terminologi og databasebegreper med gruppen din:
 DBMS
 SQL
 Relasjon
 Tuple
 Attributt
 Kardinalitet
 Grad
 Domene
NB: Gjør det skriftlig i word (e.l.) og send til kontaktveilederen deres når dere er ferdige (kun en
epost per gruppe). Dette er pensum, og kan komme på en prøve!


Oppgave 2 - SELECT queries
Benytt MySQL eksempeldatabasen ("schema") som heter world. (Samme som forrige uke.)
Skriv SQL spørringer som utfører følgende:
1. Lager en rangert liste over land etter antall mennesker per kvadratkilometer. (Tips: Se etter
tabell som inneholder befolkning og km2
for å komme igang. Bruk matematiske operatorer i
spørringen.)
2. Summerer hva totalt folketall per verdensdel (altså for alle verdensdeler) er, sortert på
folketall (synkende rekkefølge).
3. Dobbeltsjekk svaret fra oppgaven over ved å manuelt summere alle folketallene fra svaret,
og så sammenlikne de med en ny spørring som henter ut summen av verdens befolkning.
4. List ut landkode, navn og uavhengighetsår, sortert på år og deretter navn, for alle land som
har oppgitt et uavhengighetsår. (Tips: Noe med NULL.)
5. Hent ut alle land som har 'W' som mellomste bokstav i landkoden sin.
6. Hent ut alle data for landene som begynner på 'N', 'O' eller 'P'. Sorter de alfabetisk på navn.
7. Hent ut alle språkdata for landene som har et offisielt språk som snakkes av 99% eller mer av
befolkningen i landet. Sorter etter synkende prosentverdi, deretter alfabetisk på språk.
8. Hent ut landkode, navn og kontinent for alle land i Amerika (både Nord-Amerika og SørAmerika).
Sorter alfabetisk på landkode.
9. Hent ut antall land per kontinent for alle kontinentene.
10. Hent ut kontinent og antall land i dette kontinentet, for de kontinentene som har 30 eller fler
land. Sorter på antall land i synkende rekkefølge.
Tips: Ved siden av å spørre gruppen din og veilederne, se på
http://www.w3schools.com/sql/default.asp på egenhånd. Etter at du har gjort deg kjent med
denne websiden, vil du være i stand til å finne svar på mange av dine SQL spm. her! :-)


Oppgave 3
Jeg kan ikke finne noen fremmednøkler i tabellene city, country og countrylanguage i
databasen world. Hvilke kolonner kunne vi benyttet som fremmednøkler for å knytte tabellene
sammen?


Oppgave 4
Bruk World-databasen og tenk over hvilke data det kan være interessant å trekke ut fra
datagrunnlaget. Prøv deg fram og lag noen spørringer som gir deg disse dataene. Spørringene skal
kun benytte SQL som vi har gjennomgått til nå (SELECT, FROM, WHERE, ORDER BY, AS,
COUNT, SUM, AVG, MIN, MAX, GROUP BY, HAVING, DISTINCT, LIKE, IN,
BETWEEN,<WILDCARDS>, <operatorer>) og vi henter bare fra én tabell. Når du har lykkes
med å lage en spørring som gir forventet svar, legg inn oppgaven i forumet til kurset. Oppaven skal
beskrive dataene som skal hentes. Merk oppgaven med vanskelighetsgrad «lett», «middels» eller
«vanskelig» og si noe om forventet resultat av spørringen. Hvis du ikke finner tråden som skal romme
ukas studentoppgaver, opprett den og gi den et passende navn.
Når du har laget noen oppgaver og lagt dem inn i forumet, løs oppgaver i forumet med den
vanskelighetsgraden som passer deg. Løs gjerne oppgaver fra forrige uke også...
Ta gjerne en titt på spørsmålene i forumet fra forrige uke.
