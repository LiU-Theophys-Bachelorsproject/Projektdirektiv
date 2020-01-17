# Projektdirektiv

Visualisering av elektronstruktur

## Personer
* Beställare: Rickard Armiento
* Handledare: Joel Davidsson
* Expert: Peter Steneteg

## Bakgrund
Elektronstrukturberäkningar är ett viktigt verktyg inom teoretisk fysik
för att förstå hur materials och molekylers egenskaper kan härledas från
kvantmekaniska effekter. För att förstå dessa egenskaper är det viktigt att
kunna analysera data från sina beräkningar, något som i vissa fall förenklas
genom visualisering och ofta helt och hållet kräver att man kan visualisera
sin data. Inviwo är ett kraftfullt forskningsverktyg som utvecklas av
Visualiseringscenter i Norrköping. Inviwo gör det möjligt att styra
visualisering med programmering och att konstruera användargränssnitt
för interaktiv visualisering.

## Projektidé
Projektet går ut på att skapa ett verktyg för att visualisera viktiga egenskaper
från elektronstrukturberäkningar. Verktyget ska bestå av APIer för att programmatiskt
utföra visualisering samt eventuellt ett grafiskt användargränssnittför dessa APIer.

Mjukvara ifrån tidigare projektomgång finns tillgänglig för projektgruppen och får
användas för att underlätta uppfyllandet av kraven.

## Syfte
Projektet syftar till att utveckla kreativiteten samt att ge färdigheter i
fysikaliskt tänkande och analys av teoretiska resultat. Projektet bedrivs
så realistiskt som möjligt för att vara en träning inför det kommande yrkeslivet.
Resultatet av projektarbetet ska hålla hög vetenskaplig och teknisk kvalité och
baseras på moderna kunskaper, dokumenteras i form av projekt-och tidsplan,
krav-och designspecification samt i en teknisk/vetenskaplig rapport,
presenteras muntligt, demonstreras och följas upp i en efterstudie.

## Mål
Att i visualiseringsverktyget Inviwo utveckla ett system för visualisering
av resultatet av elektronstrukturberäkningar. Att demonstrera systemets
funktionalitet genom att använda det till att illustrera några befintliga
beräkningsresultat.

## Krav på systemet
- Systemet ska implementeras i Inviwo.
- Källkoden i systemet, användarmanualen och den tekniska dokumentationen bör licensieras med BSD 2-clause "simplified" licence.
- 'Processorer' för Inviwo (och ev. annan kod som integreras direkt i Inviwo) ska utveklas under Inviwos utvecklaravtal och om möjligt tillhandahållas utvecklarna av Inviwo i form av git pull-requests i samband med projektets avslutande.
- Systemet ska fungera mot den senaste versions-märkta releasen av Inviwo som finns när projektet börjas, eller någon senare version.
- Utveckling ska ske på så sätt att utvecklingshistoriken bevaras med hjälp av källkodshantering.
- Testning ska ske via implementerade enhetstester av tillagd funktionalitet.
- Tillhandahållna python-moduler ska vara användarvänliga och möjliggöra visualisering med kommandon på hög nivå.
- Systemet bör effektivt kunna hantera stora filer och arbeta med vissa visuliseringar ifrån dataset som är större än vad som rymms i datorns internminne.
- Systemet bör översätta input-filer i textformat till det binära filformatet HDF5.
- Systemet bör tillhandahålla ett grafiskt gränssnitt (GUI) för vanligt förekommande visualiseringsuppgifter.
- Installation och uppstart av systemet bör vara enkel för användaren.
- Systemet bör utnyttja befintlig kod för hantering av inläsning av datafiler och hantering av bl.a. kristallstrukturer.
- Ska kunna läsa in resultat skapade med beräkningsprogrammet VASP.
- Bör kunna läsa inresultat från något annat beräkningsprogram, t.ex. Elk.
- Systemet ska kunna läsa indata direkt ifrån utdatafiler ifrån beräkningsprogram och visualisera detta.
- Ska visualisera kristallstruktur som atompositioner i enhetscellen.
- Systemet ska kunna visualisera den elektrontäthet som resulterat ifrån en beräkning.
- Visualiseringen ska utnyttja Inviwos funktionalitet för volymsrendrering för partiell transparens.
- Visualiseringen ska tillåta interaktion i form av rotering, skalning, etc.
- Användaren ska kunna reglera en brytpunkt för vilken full transparens inträder för att kunna tydliggöra strukturer bättre.
- Ska visualisera projicerad tillståndstäthet härrörande till varje separat atom i en kristalls enhets-cell.
- Tillåta att visualisering tillhörande atomer bara visas på vissa atomer, som kan väljas dynamiskt med
  t.ex. musklick.
- Ska implementera eller avsevärt utöka redan befintlig implementation av visualisering av minst två av följande egenskaper:
  - Rita ut bindningslinjer och polyhedra för att förtydliga bindningar mellan atomer.
  - Animerade atompositioner (molekyldynamik), även med visning av laddningstäthet som ett animerat 3D-fält.
  - Elastiska konstanter.
  - Fermi-ytor.
  - ELF.
  - Krafter på atomer.
  - Bandstruktur.
  - Total och partiell DOS, (även t.ex. i ansluning till atomerna i 3d-vyn.)
  - Parkorrelationsfunktionen.
  - Illustration av partiell elektrondensitet.

  (Som att avsevärt utöka en befintlig visualisering av egenskaper räknas att betydligt förbättra avgörandet av initiala
  visualiseringsparamatrar för att ge en betydligt mer meningsfull startpunkt.)
 - I en naturvetenskaplig rapport demonstrera några av de aktuella visualiseringarna och diskutera fysikaliska insikter som kan erhållas utifrån dem.

## Slutgodkännande

För systemets godkännande krävs en interaktiv demonstration av systemets färdigheter som utförs
i samband med leverans.

## Leveranser
Se kursens Lisamsida.

## Övriga krav
Projektet ska bedrivas enligt LIPS-modellen och samtliga dokument ska utgå från LIPS-mallar.
I förefasen ingår att projektgruppen ska ta fram en kravspecifikation, en systemskiss och
en projektplan med tidplan. Samtliga dessa dokument ska godkännas av beställaren. Efter
godkänd projektplan (BP2) får projektet ta maximalt 1500 arbetstimmar att slutföra.
Projektgruppen ska utföra kontinuerlig tidsredovisning som skickas till beställaren en
gång per vecka. Vid begäran ska gruppen även skicka in en statusrapport. Vid slutleveransen
ska det finnas ett fungerande interaktivt visualiseringssystem, teknisk dokumentation med
användaranvisning, en teknisk/naturvetenskaplig rapport samt slutrapport. Projektets delleveranser
och slutleverans ska senast ske vid de datum som finns specificerade på kursens Lisamsida. Även
formen för slutleveransen beskrivs på denna sida. Dokumentationen sparas på kursens Lisamsida.
