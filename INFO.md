(Work in progress: denna text är ännu bara påbörjad)

# Projektinstruktioner: Visualisering av elektronstruktur

Detta är ett PM som ger lite allmän info om hur vi bedriver projektet *Visualisering av elektronstruktur* 
och ge er svar på några vanliga frågor.

## Projektets form

Vi bedriver detta projekt lite som ett "rollspel". Ni är ett arbetslag på ett mjukvaruföredrag som fått i 
uppdrag att utföra detta projekt. Ni har emellan er olika roller, där en av er är projektledare. *Handledaren*
jobbar på ert företag och ska ses som er närmaste chef. *Beställaren* är den kund på vars uppdrag ni
utför projektet. Ni (och speciellt er projektledare) är alltså ansvariga att boka möten i god tid, föra protokoll
över möten, se till att handledare och beställare får rapporter i tid, osv.

Tanken är att rapporterna i huvudsak skrivs inom ramarna av "rollspelet". D.v.s. vi föredrar om ni hoppar
över att skriva, t.ex., att "Motivationen för arbetet är att vi ska lära oss arbeta i projekt inom kursen TFYA75" 
och istället söker formuleringar för projektets motivation som är i linje med själva projektetuppgiften.

## Etik och upphovsrätt för programkod, text och bilder

På grund av att ni vidareutvecklar ett redan befintligt system brukar det bli en del frågor just kring hur man ska
hantera tidigare års bidrag, de egna tilläggen, och eventuell upphovsrätt till externa bilder (och ibland text) man
använder i rapporter.

### Etiska aspekter

Vid sidan om vad som är "lagligt", vad universitetet kräver, osv. så finns en grundläggande 
etisk princip att alltid ge en väldigt tydlig hänvisning när man använder något som skapats av någon annan.

- Ta *aldrig* bort information om licenser eller upphovsrätt i källfiler ni jobbar med. Lägg till information om 
  era egna bidrag. Om ni är osäkra, fråga er handledare.
  
- Hänvisningar till text, bild och andra verk skapade av andra ska alltid vara explicita. 

  * Använder ni en bild ifrån en annan källa så ska det i bildtexten stå "Reproducerad ifrån Ref. X", det räcker inte med "[5]".
    (Det senare ska snarare tolkas som att man ritat en egen bild baserad på en metod eller data i Ref. 5).
    
  * Om ni använder en beskrivning eller härledning som nära ansluter till existerande text i en bok eller 
    på en webbsida så ska ni formulera om denna med egna ord, men också före denna text skriva ut:
    "Följande härledning följer nära en härledning given av Ref. X" (eller motsvarande).

### Källkod 

Systemet har av tidigare års projektgrupper implementerats i Python och C++ och källfilerna är licensierade med 
en licens som kallas *BSD 2-Clause "Simplified" License*. Ni kan läsa mer om denna licens på bl.a. (Wikipedia)[https://en.wikipedia.org/wiki/BSD_licenses#2-clause_license_(%22Simplified_BSD_License%22_or_%22FreeBSD_License%22)].
När ni arbetar vidare med dessa filer så hamnar era modifikationer under denna licens. 
(Här ska dock påpekas att inom ramarna för kursen kan vi inte tvinga någon att göra sitt arbete
tillgängligt under en given licens. Om någon av deltagarna finner det problematiskt att deras programkod
blir tillgänglig under systemets licens så är det något som måste diskuteras i ett tidigt skede.)

När ni editerar filer så ska ni aldrig ta bort licensinformation, utan, inviduellt, lägga till era namn i slutet 
av listan av namn vid 'Copyright' i toppen av filerna. Ni ska även uppdatera filen LICENSE och lägga till 
alla era namn i projektgruppens i toppen av denna fil.

### Rapporter

Alla rapporter som lämnas in förväntas vara helt era egna arbeten, *förutom* teknisk dokumentation och användarhandlending.
För dessa förväntas ni uppdatera och utvidga de befintliga rapporterna till att omfatta den ökade funktionalitet
ert arbete bidragit med. Tidigare års rapporter finns därför i källkodsrepositoryt licensierade under samma licens
som källkoden.

## Datorresurser

Ni får i samband med projektets början tillgång till en eller två datorer i en av labblokalerna på LiU 
där det är tänkt att ni utför huvuddelen av projektet. Där är dock inget som hindrar att ni installerar
nödvändig programvara på t.ex. egna laptops.

## Naturvetenskaplig undersökning

I tidigare projektgrupper är det en vanlig fråga att 

