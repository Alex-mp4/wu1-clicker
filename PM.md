# Clicker | Grodslickaren, wu1  | Post Mortem 

- titel: Grodslickaren
- tagline: Du går ut i katakomberna i hopp om
skatter och guld. Istället finner du endast en
håla fylld med grodor. Hur många slick krävs det för att stiga upp till ett högre tillvaroplan?
- url: alex-mp4.github.io/wu1-clicker/
- git: https://github.com/Alex-mp4/wu1-clicker

## Inledning
Målet med denna uppgift var att få ett färdiggjort clicker spel med fullständig HTML, css och Javascript och anpassa den till ett eget tema. 

## Bakgrund
Uppgiften började med en inledning till arbetsprocessen då vi fick se hemsidan vi sedan skulle jobba med. Vi fick en vecka på oss att komma på det tema vi skulle använda för att anpassa spelet givet till oss. Jag valde "grodslickare" som en liten inside-joke till en grupp där en karaktär slickade på en padda och magiskt (samt slumpmässigt) fick ett sjätte sinne som gav han gudalika krafter. Historien i början av spelet förklarar, in princip, hela storyn bakom händelsen.

Först och framförallt började jag med färgförändringar, bilder och större HTML byten, exempelvist vart specifika delar av spelet skulle ligga. På så sätt kunde jag se alla mina planer genom att lägga alla element som olika lager, typ att knappen skulle vara "under" listan av uppgraderingar eftersom den senare skulle bli "display: flex;"ad för att vara bredvid varandra. Bilden blev snabbt stoppad inom knappen för att visa hela poängen. Texttärgen började som en limegrön, likt färgen på grodan som används till bildt, men jag insåg senare hur jobbigt det var att läsa texten och dessutom vissa kontrast fel. Därför är den istället en mjukare turkos som passar med det bruna (eftersom rent färgteori mässigt passar de ihop).

Därefter anpassade jag mycket att Javascripten. Att slicka på grodor borde inte ge dig fossiler, så istället gjorde jag upgraderingarna till diverse mutationer som absolut skulle hände i verkligheten ifall du började slicka på groder (tro mig, det har hänt mig), till exempel att du plötsligt får kraften att starta om hela universum så att du kan slicka på ännu fler grodor. Som sagt var hela planen relativt humoristisk utöver verklig. Det är ett spel, efter allt. Fler additioner till Javascript handlade om att göra anpassningar som gjorde spelet faktiskt kul att spela. Mycket av min tid var spenderad till play-testing och att hela spel processen skulle vara kul från början till slut. 

Det sista i min plan var att mobilanpassa alla förändringar jag gjort i HTML. Eftersom detta låg på lägst prioritet blev hela den delen inte lika mäktig som datorversionen, men det får man leva med.

## Positiva erfarenheter
Det var väldigt lätt att förändra diverse funktioner och teman inom Javascripten till att fungera som man vill. Att lägga in sina egna idéer bakom spelfunktioner gick relativt bra. Att förändra på HTML gick dessutom väldigt effektivt då det är, in princip, den delan jag förstår som bäst.

## Negativa erfarenheter
Som sagt tidigare hade det varit kul med en bra mobilanpassad sida. Hade det funnits en gnutta mer tid skulle det säkert funka bra också. Dock så gav jag några försök till att faktiskt förändra css:en på mobil men alla mina försök gjorde inte speciellt mycket så jag tog bort den biten. Jag fastnade dessutom lite för länge på att speltesta spelet till perfektion att jag tappade lite tid.

## Sammanfattning
Jag har skapat en hemsida för ett clicker spel baserat på att slicka grodor. Det var nog en av de roligaste uppgifterna hitills på grund av vanan med spel (inte minst clicker spel). Fortfarande behöver jag skaffa lite extra koll på media queries och användingen av dem så att mobilanpassning faktiskt fungerar.