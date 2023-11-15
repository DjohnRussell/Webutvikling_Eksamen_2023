# Webutvikling_Eksamen_2023
 The repository name should distinctly convey that this is the final exam for a web development course, showcasing a portfolio webpage or site. The functional pages include the 
 Front page (index.html), About page (about.html), and Products page (products.html). Additionally, incorporate some innovative elements to enhance the overall experience.
 
 ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------The given task------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Innledning

Som eksamensoppgaven skal dere lage et nettsted. Nettstedet skal bestå av 3 HTML-sider. I denne zip mappen Download denne zip mappen ligger det bilder og video dere kan bruke fritt i oppgaven. Under finner dere skisser for hvordan nettstedet skal se ut, skissene gjelder hovedsakelig dere som sikter etter E-D kravet, for C-A er det demo videoen over hvordan nettstedet ser ut og fungerer som gjelder. Oppgaven er delt inn etter mulig karakteroppnåelse, hvor utnyttelse av mer komplekse teknologier gir bedre karakter. Dere skal levere oppgaven som et GitHub prosjekt, ha god mappestruktur, dobbeltsjekk at kode funker og commit og push til repoet ofte.

Minstekrav (karakter E)
Det er maksimalt mulig å oppnå en karakter E ved gjennomføring av kun minstekrav. Kravene under gjelder uansett hvilket ambisjonsnivå man velger å gå etter.

Nettstedet skal være validert og ha null errors.
Dere har en <div> - kvote på 5, går man over kvoten blir oppgaven satt til en F. Vurder om det er nødvendig med div-er eller ikke, om behovet for <div> taggen blir også vurdert.
Dere skal ha brukt de semantiske taggerne <header>, <nav>, <main>, <section> og <article>.
Alle sidene skal inneholde dummy data som lorum ipsum tekst og placeholder bilder.
Oppgaven dere skal inneholde et dokument hvor dere skriver om hvilket ambisjonsnivå (A-B) dere velger å gå etter, hvilke antagelser eller tolkninger man har gjort og kilder til bruk av bilder og annet. Mangler dokumentet og blir oppgaven satt til en F.
HTML
Du skal lage tre html sider: index.html, about.html og products.html
Sett opp HTML-sidene med fornuftig semantisk struktur basert på skissene.
Alle sidene skal valideres
HTML-koden i menyen og footeren skal være lik på alle sidene
Alle HTML-sidene skal linkes til et og samme CSS ark. Prosjektet skal kun inneholde et stilark, med mindre man også linker til normalize og bruker font awsome. På E-D kravet skal man ikke bruke ikoner.
På «about us» siden skal det legges inn et bilde av et kart, dere kan brukes skolens adresse for både den tekstlige informasjonen og som kartbilde.
På products.html siden skal det være tre seksjoner, en for design, en for branding og en for developement. Disse seksjonene skal holde på en ulik mengde artikkelkort.
Design skal inneholde tre artikkelkort
Branding skal inneholde 4 artikkelkort
Development skal holde på 2 artikkelkort
Hver artikkelkort skal ha et bilde (man kan bruke placeholder bilder) og en overskrift.
Lenking
Alle sidene skal lenkes til hverandre via menyen, alle menypunktene skal være aktive og fungere på alle sidene.
Logoen (både i menyen og i footeren) skal lenkes til index.html som skal være forsiden
Lenking av knapper på forsiden:
“Read more about our services” knappen skal lenkes til about.html
“Read more about us” knappen skal lenkes til about.html
“Contact” I menyen skal lenkes til about.html
Lenking av knapper på About us:
«Get in touch with us» skal lenkes ned til contact us seksjonen og fungere som en snarvei.
Footeren
I footeren skal det være en link til facebook, instagram og linkdin. Disse skal lenkes opp til de sidene.
CSS
Det skal kun være et stilark, med mindre man også bruker normalize eller har font awsome filene.
Du skal skrive CSS for å oppnå resultatet på skissene, i E-D kravet trenger man ikke bruke CSS grid eller Flexbox.
Du skal bruke en websafe font
Alle artikkelkortene på porfoliosiden skal ha en maks bredde på 350px og en min bredde på 200px
Karakter D-krav
I tillegg til kravene og oppgavene nevnt i dette avsnittet, gjelder også minstekrav for karakter D.

Lenking
Lenking av knapper på forsiden:
“Read more about our services” knappen skal lenkes til seksjonen som handler om «services» nederst på forsiden
“Read more about us” knappen skal lenkes til about.html
“Contact” I menyen skal lenkes til seksjonen som holder på en kontaktskjema inne på about.html siden.
Lenking til kategorier på portfolio siden:
Development skal lenkes til seksjonen som holder på kort innenfor development.
Design skal lenkes til seksjonen som holder på kort innenfor design.
Branding skal lenkes til seksjonen som holder på kort innenfor branding.
Karakter C-krav
C-kravene bygger på Minstekrav og karakter D-krav.

For karakter C og høyere forventer vi at studentene selv tar ansvar for refaktorering (bruk av klasser og id-er på en hensiktsmessig måte).

HTML
Ikoner skal bli lagt til der det har blitt brukt på demo videoen.
Facebook, instagram og linkdin skal byttes ut med ikoner fra font-awsome (dissa skal også endres på med css slik at de får fargen hvit og blir litt større). De skal fortsatt være lenket opp til facebook, instagram og linkdin.
På forsiden og about siden skal det legges til ikoner på services. Disse skal også stilsettes slik at de blir større som sett på demo-
Header området på forsiden skal ha et bakgrunnsbilde.
CSS
Sidens struktur og innholds-flyt skal være laget med bruk av CSS grid og flexbox. Dette skal være fornuftig og riktig brukt. Slenger man på display: grid og flexbox ufornuftig og bruker det feil vil dette telle negativt.
Nettstedet skal være responsivt og studenten skal bruke media querries for å gjøre endringer fra mobil til desktop versjon.
Det skal skje endringer med gridet i media querries, hvor det skal være minimum tre kolonner ved desktop og endre seg til en kolonne på mobil.
Menypunktene skal falle under hverandre.
På portfolio siden skal det brukes flexbox for å skape innholds-flyt i de ulike seksjonene. Artikkelkortene skal vokse og minske basert på den tilgjengelige plassen (hint: flex-grow), men de skal ikke blir større enn 692px.
Artikkel-kortene skal falle under hverandre ved nedskalering.
Google fonts skal importeres inn og brukes. Fonten skal selvfølgelig være lesbar.
Siden skal ha en maks bredde på 1600px
Karakter B-krav
B-kravene bygger på C-kravene, Minstekrav og karakter D-krav.

HTML
HTML-kode skal gjøres enda mer tilgjengelig ved å legge til title attributter (der det er fornuftig), tastatur-navigering, aria roller og labels. Vurder innholdet i alt tagger på bilder, hva er innhold og hva er pynt (legg igjen kommentarer på dette i koden).
På about siden skal det legges til et ekte kart (hint: bygg inn kart ved deling i google maps). Kartet skal også gjøres tilgjengelig og ha full bredde som på demo-videoen.
Opengraph metadata og «vanlig» metadata skal legges til på alle sidene, innholdet i metadataen skal være spesifikt for sidene.
CSS
Når man er på en side skal menypunktet for den gjeldene siden markeres med en understrek i gul og fonten skal være bold
Når man hovrer over knapper skal bakgrunnsfargen endres til grå-svart (fargekoder finnes nederst i oppgaven) og tekstfargen skal endres til gull-gul
Når man hovrer over artikkelkortene på portfolio siden skal de bli større og det skal skje gradvis.
Karakter A-krav
HTML
Alle sidene skal ha en form for microdata, vurder innholdet på de ulike sidene og velg fornuftig microdata basert på det.
All microdata skal validere
<div>-kvota øker med tre, du har nå en <div> kvote på totalt åtte <div>-er. Vurder om det er nødvendig med div-er eller ikke, om behovet for <div> taggen blir også vurdert.
På forsiden skal header «bildet» være en video som går på «auto play» og som et «muted», denne skal ha en overlay som skal være delvis gjennomsiktig. Overskriften, teksten og knappen skal ligge over videoen. Hint: position absoulute, realtive, videoen skal ligge inne som et HTML-element.
Nettstedet skal ha et favicon
Det skal finnes en «tilbake til toppen» knapp nederst i høyre hjørne. Den skal være på alle sidene.
 CSS
Når skjermen blir mindre, skal videoen i header området forsvinne og bakgrunnsbildet fra tidligere skal være synlig igjen.
Hover effekter på knapper og andre linker skal kun funke ved desktop og være fraværende ved mobilversjon.
Huskeliste til innlevering
Alle hjelpemidler er tillatt under utviklingen. Sammarbeid er ikke lov og blir ansett som juks.
Gjør GitHub-repositoriet public!
Et kort dokument (repositoriet skal du legge med en pdf fil med navnet "eksamensdokument") som inneholder:
Hvilken vanskelighetsgrad studenten har gått for (minstekrav, D, C, B eller A)
Redegjørelser/forutsetninger dere gjør dersom oppgaveteksten oppleves uklar eller ikke setter klare rammer eller begrensninger
Redegjøre for potensielle utfordringer som ikke rakk/ble klart løst
Kilder til ALL dokumentasjon dere har benyttet under arbeidet med eksamen
... Hvis dette dokumentet mangler fra innlevering blir oppgaven satt til F
Kommenter kode som avviker fra hva som har blitt undervist i kurset, og spesielt der dere har benyttet ekstern hjelp (StackOverflow, YouTube, blogger etc, chatGPT, copilot), inkludert link til kilden.
Dobbeltsjekk at det som ligger på reposiotert er den nyeste koden og at du har pushet opp koden din.
Hvis det skjer endringer på github repoett etter innleveringsfristen blir levering din ikke rettet og du blir registrert som ikke møtt.
Leveranse
Dere skal levere en github link i inspera, dere er selv ansvarlige for å dobbelsjekk innlveringen deres både i inspera og på github. Får dere problemer med å levere må dere kontakte eksamenskontoret. Alle github innleveringer hvor det har blitt gjort endringer etter fristen 29.november 16:00 blir ansett som ikke møtt.

Skisse og demo
Det er laget en skisse for forsiden som er mindre detaljert enn de andre sidene, for dere som går etter E-D ta utgangspunkt i forside skissen når det kommer til mengde detaljer og bruk de andre nettside-skissene som et utgangspunkt for HTML-struktur og layout.

Når det kommer til de høyre karakterene skal nettsiden både se ut og fungere som demonstrert på demo-videoen i tillegg til de andre delene som spesifisert i kravene for karakterene.

