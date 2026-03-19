---
modul: M5
titol: "Accessibilitat digital"
tipus: eina
descripcio: "Estàndards i recursos per a materials digitals accessibles: WCAG, subtítols, lectors de pantalla"
review_status: esborrany
generat_at: 2026-03-17T21:58:23
---
# 1. CONTINGUT ESPECÍFIC DEL DOCUMENT

## Descripció i propòsit
L'accessibilitat digital és la pràctica de dissenyar i crear materials i entorns digitals que puguin ser percebuts, entesos, navegats i utilitzats per totes les persones, independentment de les seves capacitats o discapacitats. El seu propòsit principal és eliminar les barreres digitals per garantir la inclusió de tot l'alumnat, especialment aquell amb diversitat funcional sensorial (visual, auditiva), motriu o cognitiva. Aquesta eina proporciona una guia pràctica per assegurar que els recursos digitals que utilitzem a l'aula compleixin amb els estàndards d'accessibilitat, facilitant així l'aplicació dels principis del Disseny Universal per a l'Aprenentatge (DUA) des del disseny.

## Freqüència i moment d'ús
Aquesta eina s'ha d'utilitzar de manera **proactiva i contínua** en totes les fases del cicle de vida d'un material digital:
*   **Disseny inicial**: Quan es conceptualitza un nou material o activitat digital.
*   **Creació i producció**: Mentre s'està elaborant el contingut (text, imatges, vídeos, presentacions, etc.).
*   **Revisió i adaptació**: Abans de publicar o compartir un material existent amb l'alumnat.
*   **Avaluació**: Per verificar l'accessibilitat dels materials ja en ús.

No és una eina per a un ús puntual, sinó una mentalitat a integrar en la pràctica diària de creació de recursos.

## Components i estructura
Aquesta eina es basa en els estàndards de les Pautes d'Accessibilitat al Contingut Web (WCAG), que són un referent internacional. Els components clau es resumeixen en quatre principis fonamentals (PERCEBIBLE, OPERABLE, COMPRENSIBLE, ROBUST) i es desglossen en elements concrets a revisar:

1.  **Perceptible**: La informació i els components de la interfície d'usuari han de ser presentables als usuaris de manera que puguin percebre'ls.
    *   **Text alternatiu (Alt text)**: Per a imatges, gràfics, taules.
    *   **Subtítols i transcripcions**: Per a vídeos i àudios.
    *   **Contrast de color**: Suficient entre text i fons.
    *   **Presentació adaptable**: Contingut que es pot presentar de diferents maneres sense perdre informació o estructura.

2.  **Operable**: Els components de la interfície d'usuari i la navegació han de ser operables.
    *   **Navegació per teclat**: Totes les funcionalitats accessibles sense ratolí.
    *   **Temps suficient**: Per llegir i utilitzar el contingut.
    *   **Evitar parpellejos**: Que puguin provocar convulsions.

3.  **Comprensible**: La informació i el funcionament de la interfície d'usuari han de ser comprensibles.
    *   **Textos clars i senzills**: Llenguatge fàcil d'entendre.
    *   **Estructura lògica**: Títols, subtítols, llistes.
    *   **Instruccions clares**: Per a la interacció.
    *   **Ajuda a la introducció de dades**: Identificació d'errors i suggeriments de correcció.

4.  **Robust**: El contingut ha de ser prou robust perquè pugui ser interpretat per una àmplia varietat d'agents d'usuari, incloses les tecnologies d'assistència.
    *   **Codi vàlid**: Utilitzar estàndards web i etiquetatge semàntic.
    *   **Compatibilitat**: Amb lectors de pantalla i altres eines d'assistència.

## Guia d'ús pas a pas

1.  **Identifica el material digital**: Decideix quin recurs vols fer accessible (presentació, document de text, vídeo, web, etc.).
2.  **Revisa el principi "Perceptible"**:
    *   **Imatges i gràfics**: Afegeix text alternatiu descriptiu. Si la imatge és purament decorativa, marca-la com a tal (alt="").
    *   **Vídeos i àudios**: Inclou subtítols (preferiblement tancats, que es poden activar/desactivar) i una transcripció completa.
    *   **Colors**: Utilitza eines de contrast per assegurar que la combinació de colors de text i fons tingui un contrast mínim de 4.5:1 (WCAG AA).
    *   **Estructura visual**: Assegura que la informació no depengui només del color per transmetre significat.
3.  **Revisa el principi "Operable"**:
    *   **Navegació**: Prova de navegar pel material només amb el teclat (tecles Tab, Enter, fletxes). Tots els elements interactius (enllaços, botons) han de ser accessibles.
    *   **Temps**: Si hi ha elements amb temps limitat, ofereix opcions per pausar, aturar o estendre el temps.
4.  **Revisa el principi "Comprensible"**:
    *   **Llenguatge**: Utilitza un llenguatge clar, concís i apropiat per a l'edat i nivell de l'alumnat. Evita argot innecessari.
    *   **Estructura**: Aplica títols (H1, H2, H3), llistes (ordenades/desordenades) i paràgrafs curts per facilitar la lectura i la comprensió.
    *   **Instruccions**: Formula les instruccions de manera clara i seqüencial.
5.  **Revisa el principi "Robust"**:
    *   **Format**: Preferiblement, utilitza formats oberts i estàndard (HTML, PDF etiquetat, ePub).
    *   **Eines d'autor**: Moltes aplicacions (Word, PowerPoint, Google Docs) tenen verificadors d'accessibilitat integrats. Utilitza'ls.
    *   **Prova amb lectors de pantalla**: Si és possible, fes una prova bàsica amb un lector de pantalla (NVDA, JAWS, VoiceOver) per veure com es llegeix el teu material.

## Exemples completats

### Exemple 1: Presentació de diapositives (PowerPoint/Google Slides)

**Material original (no accessible):**
Una presentació amb moltes imatges sense descripció, text amb colors de baix contrast, i sense títols de diapositiva clars.

**Adaptació accessible (pas a pas):**
1.  **Títols de diapositiva**: Assegura que cada diapositiva tingui un títol únic i significatiu utilitzant els "layouts" de diapositiva predefinits.
2.  **Text alternatiu per imatges**:
    *   Imatge: Gràfic de barres amb el creixement de la població escolar.
    *   Alt text: "Gràfic de barres que mostra l'augment de la població escolar a Catalunya entre 2010 i 2020, passant de 1.2M a 1.5M d'alumnes."
    *   Imatge: Logotip de l'escola.
    *   Alt text: "Logotip de l'escola [Nom de l'escola]."
3.  **Contrast de color**: Revisa els colors del text i fons. Si un títol vermell sobre fons gris té un contrast baix, canvia el vermell per un to més fosc o el fons per un més clar.
4.  **Estructura del text**: Utilitza els estils de títol i subtítol integrats en el programa, no només canvis de mida de font. Utilitza llistes amb vinyetes per a punts clau.
5.  **Enllaços**: Assegura que els enllaços tinguin un text descriptiu, no només "clica aquí". Exemple: "Consulta la normativa de DUA (enllaç a la normativa)" en lloc de "Clica aquí".

### Exemple 2: Vídeo educatiu (YouTube/Drive)

**Material original (no accessible):**
Un vídeo explicatiu de 5 minuts sobre la fotosíntesi, sense subtítols ni transcripció.

**Adaptació accessible (pas a pas):**
1.  **Subtítols**:
    *   Utilitza la funció de subtítols automàtics de YouTube o Google Drive com a punt de partida.
    *   **Revisa i corregeix manualment** els subtítols generats automàticament per assegurar la precisió, la puntuació i la sincronització.
    *   Assegura que els subtítols incloguin la identificació de qui parla si hi ha diversos interlocutors.
2.  **Transcripció**:
    *   Crea un document de text amb la transcripció completa del diàleg del vídeo.
    *   Afegeix descripcions breus d'elements visuals importants que no s'expliquen verbalment (ex: "[Mostra un diagrama de la cèl·lula vegetal]").
    *   Posa aquest document a disposició de l'alumnat com a recurs addicional.
3.  **Àudio clar**: Assegura que l'àudio del vídeo sigui clar i que la música de fons no interfereixi amb la veu.

## Adaptacions per context

*   **Necessitats Educatives Específiques (NEE)**: Per a alumnes amb dislèxia, utilitzar tipografies clares i espaiades. Per a alumnes amb TDAH, fragmentar el contingut en blocs més petits i amb instruccions molt concretes. La IA pot ajudar a simplificar textos o generar exercicis graduats, però cal supervisar que no es perdi el rigor del contingut.
*   **Etapes educatives (Infantil/Primària)**: Simplificar el llenguatge al màxim. Utilitzar més elements visuals amb descripcions senzilles. Els subtítols poden ser una eina per al desenvolupament de la lectoescriptura.
*   **Versió simplificada**: Si el material és molt complex, crea una versió "lectura fàcil" que mantingui la informació essencial amb un vocabulari i estructura més bàsics. La IA pot ser útil per generar esborranys d'aquesta versió simplificada.
*   **Versió digital**: Aprofita les funcionalitats d'accessibilitat integrades en les plataformes (LMS, editors de text, etc.). Moltes plataformes permeten afegir descripcions d'imatges, subtítols i etiquetes semàntiques directament.

## Com interpretar resultats
L'objectiu no és obtenir un "100% accessible" perfecte, sinó millorar contínuament.
*   **Verificació manual**: La millor interpretació prové de revisar el material amb la perspectiva d'una persona amb diversitat funcional.
*   **Feedback de l'alumnat**: Pregunta directament a l'alumnat si troben barreres. El seu feedback és el més valuós.
*   **Eines automàtiques**: Les eines de verificació d'accessibilitat (integrades en programes o extensions de navegador) són un bon punt de partida, però no detecten tots els problemes (ex: un "alt text" pot existir, però ser poc descriptiu).
*   **Impacte en l'aprenentatge**: Observa si l'alumnat amb NEE o diversitat funcional pot accedir i interactuar amb el material de manera autònoma i efectiva. Si no és així, calen més adaptacions.
*   **Principi DUA**: Recorda que l'accessibilitat és un pilar del DUA. Si els materials són accessibles, s'està facilitant múltiples formes de representació, acció i expressió, i implicació, beneficiant a tot l'alumnat.

# 2. CONNEXIONS AMB ALTRES DOCUMENTS DEL CORPUS

| Document relacionat | Relació concreta | Co-activació obligatòria | Co-activació condicional |
|---|---|---|---|
| `inclusio-necessitats` | L'accessibilitat digital és una mesura universal i específica fonamental per a l'atenció a la diversitat i l'aplicació del DUA. Aquest document detalla com la IA pot ajudar a generar materials accessibles. | Sí, sempre que es parli d'inclusió o DUA. | Quan es dissenyen materials per a NEE o diversitat funcional. |
| `competencia-digital-ia` | La creació de contingut digital accessible és una subcompetència de la competència digital general i, per extensió, de la competència digital en IA, especialment en la dimensió de "Diligència" (creació responsable). | No. | Quan es parla de crear contingut digital amb o sense IA, o de la responsabilitat en l'ús de la tecnologia. |
| `friccio-cognitiva` | L'accessibilitat digital assegura que l'alumnat pugui accedir al contingut per iniciar la "fricció productiva". Si el material no és accessible, la fricció cognitiva no es pot ni iniciar. | No. | Quan es dissenyen activitats amb IA i es vol assegurar que el punt de partida sigui equitatiu per a tots. |

# 3. DETECCIÓ (Variables de Context)

**Senyals del docent:**
*   "Com puc assegurar que tots els meus alumnes puguin accedir a aquest material digital?"
*   "He de preparar un vídeo per a la classe, però tinc alumnes amb dificultats auditives."
*   "M'han dit que els meus documents de text no són fàcils de llegir per a alguns alumnes amb dislèxia."
*   "Vull utilitzar una eina digital nova, però em preocupa que no sigui inclusiva."
*   "Com puc fer que la meva presentació sigui més útil per a un alumne amb baixa visió?"

**Senyals de l'alumne:**
*   L'alumne demana que es repeteixi la informació visualment o auditivament.
*   L'alumne té dificultats per interactuar amb un recurs digital (no pot clicar un botó, no entén un formulari).
*   L'alumne expressa frustració per no poder seguir un vídeo o una presentació.

**Senyals de context:**
*   Disseny d'una nova unitat didàctica que inclou molts recursos digitals.
*   Incorporació d'un nou alumne amb NEE o diversitat funcional al grup.
*   Ús de plataformes o eines digitals noves a l'aula.
*   Revisió de materials didàctics existents.

**Anti-senyals (quan NO activar malgrat les aparences):**
*   Quan la pregunta del docent es refereix exclusivament a la dificultat tècnica d'ús d'una eina digital, sense implicar barreres d'accés per a la diversitat funcional.
*   Quan la preocupació principal és la gestió de llicències o la seguretat informàtica, i no l'accés al contingut.
*   Quan es demana una solució per a un problema de rendiment acadèmic general que no està directament relacionat amb l'accessibilitat del material.

# 4. HEURÍSTIQUES I RAONAMENT PER A L'AGENT

## H1 Heurística — DOCENT

**Quan aplica:** Quan el docent està dissenyant una nova activitat o material digital des de zero, o quan vol revisar la inclusió dels seus recursos. *

**Fonament:** L'accessibilitat no és una "addició" sinó un pilar del Disseny Universal per a l'Aprenentatge (DUA). Pensar en l'accessibilitat des del principi estalvia temps i esforços, i garanteix que el material sigui inherentment més inclusiu. A més, evita la "fricció cognitiva" innecessària causada per barreres d'accés, permetent que l'alumne es concentri en l'aprenentatge real. *

**Exemple:** Un docent vol crear una presentació interactiva per introduir un tema nou. En lloc de fer la presentació i després pensar en com adaptar-la, l'agent suggeriria al docent que, des del primer esborrany, utilitzi plantilles amb títols de diapositiva estructurats, s'asseguri que les imatges que inclogui tinguin espai per a text alternatiu, i que els colors de fons i text tinguin un bon contrast. Això no només beneficiarà a alumnes amb baixa visió o dislèxia, sinó que també millorarà l'estructura i la claredat per a tot l'alumnat, fent la presentació més robusta i comprensible per a tots, tal com promou el DUA.

---

## H2 Heurística — DOCENT

**Quan aplica:** Quan el docent crea o selecciona contingut informatiu (text, vídeo, àudio). *

**Fonament:** Per complir amb el principi DUA de "múltiples formes de representació", oferir la informació en almenys tres formats diferents (visual, auditiu, textual) maximitza les possibilitats que tot l'alumnat pugui accedir-hi segons les seves preferències o necessitats. Això inclou subtítols per a vídeos, transcripcions per a àudios i text alternatiu per a imatges. *

**Exemple:** Un docent vol compartir un vídeo explicatiu sobre un concepte complex. L'agent raonaria que, per fer-lo accessible, no n'hi ha prou amb el vídeo en si. Caldria assegurar que el vídeo tingui subtítols precisos (format textual per a l'àudio), i idealment, una transcripció completa que també descrigui elements visuals rellevants (un altre format textual). A més, si el vídeo conté gràfics, aquests haurien de tenir descripcions verbals o text alternatiu. Aquesta aproximació beneficia no només a alumnes amb dificultats auditives, sinó també a aquells que prefereixen llegir, que es troben en un entorn sorollós, o que volen repassar el contingut de manera ràpida.

---

## H3 Heurística — DOCENT

**Quan aplica:** Quan el docent vol verificar la usabilitat i accessibilitat d'un material digital interactiu o d'una plataforma. *

**Fonament:** Simular l'experiència d'un usuari amb una discapacitat sensorial o motriu ajuda a identificar barreres que d'altra manera passarien desapercebudes. La navegació per teclat és un requisit WCAG fonamental per a moltes tecnologies d'assistència. *

**Exemple:** Un docent ha dissenyat un qüestionari en línia amb imatges interactives. L'agent suggeriria al docent que intenti completar el qüestionari utilitzant només el teclat (tecla Tab per moure's, Enter per seleccionar) i, si és possible, amb un lector de pantalla bàsic activat. Si el docent no pot navegar per totes les preguntes, seleccionar respostes o enviar el formulari sense el ratolí, o si el lector de pantalla no llegeix correctament les preguntes o les opcions, significa que hi ha barreres d'operabilitat o de percepció que cal corregir. Això garanteix que alumnes amb dificultats motrius o visuals puguin participar plenament. *

---

## H6 Heurística — ALUMNE

**Quan aplica:** Quan el docent considera utilitzar eines d'IA per generar o adaptar materials digitals amb finalitats d'accessibilitat. *

**Fonament:** La IA pot ser una eina potent per a l'accessibilitat (generar subtítols, simplificar textos, descriure imatges), però no substitueix la supervisió humana. Les "al·lucinacions" o biaixos de la IA poden generar contingut incorrecte o poc precís, que podria crear noves barreres o "fricció cognitiva" innecessària si no es revisa. *

**Exemple:** Un docent decideix utilitzar una eina d'IA per generar automàticament els subtítols d'un vídeo educatiu i per simplificar un text complex. L'agent aconsellaria al docent que, tot i que la IA pot accelerar el procés, és absolutament imprescindible revisar i corregir manualment els subtítols generats per assegurar la seva precisió i sincronització, ja que els errors podrien confondre o frustrar l'alumne. De la mateixa manera, el text simplificat per la IA ha de ser revisat per garantir que manté la informació essencial i el rigor acadèmic, i que el llenguatge és realment adequat per al nivell de comprensió desitjat, evitant la "rendició cognitiva" per part de l'alumne que podria acceptar un text simplificat sense escrutini.

---

## H7 Heurística — ALUMNE

**Quan aplica:** Quan l'alumne té dificultats per accedir a un material digital o vol millorar la seva experiència d'aprenentatge. *

**Fonament:** L'alumne ha de ser conscient de les tecnologies d'assistència disponibles (lectors de pantalla, subtítols, configuracions de contrast) i de com utilitzar-les. Això fomenta l'autonomia i la "competència digital" en l'ús d'eines per a l'aprenentatge. *

**Exemple:** Un alumne amb dificultats auditives està mirant un vídeo a classe. L'agent podria recordar-li que la majoria de plataformes de vídeo tenen una opció per activar els subtítols (el botó "CC"). Si els subtítols no estan disponibles o són incorrectes, l'agent podria suggerir-li que ho comuniqui al docent. Això no només l'ajuda a accedir al contingut, sinó que també el capacita per identificar i resoldre barreres d'accessibilitat de manera proactiva, desenvolupant la seva autonomia i la seva "competència digital en IA" si ha d'interactuar amb eines que utilitzen IA per a l'accessibilitat.

---

## H8 Heurística — ALUMNE

**Quan aplica:** Quan l'alumne es troba amb un material digital al qual no pot accedir o que li resulta molt difícil d'utilitzar. *

**Fonament:** L'alumne té dret a accedir a la informació en un format que li sigui comprensible. Demanar un format alternatiu és una forma de defensar el seu dret a la inclusió i a l'aplicació del DUA. *

**Exemple:** Un alumne amb dislèxia rep un document PDF escanejat amb moltes imatges de text, que li resulta gairebé impossible de llegir amb el seu lector de pantalla o amb eines de text a veu. L'agent aconsellaria a l'alumne que demani al docent una versió del document en un format de text editable (Word, Google Docs) o una versió "lectura fàcil" si és possible. Això permetria a l'alumne utilitzar les seves eines d'assistència de manera efectiva, reduint la "fricció cognitiva" innecessària i permetent-li concentrar-se en el contingut en lloc de la lluita per accedir-hi.

---

## H9 Heurística — ALUMNE

**Quan aplica:** Quan l'alumne utilitza eines d'IA per generar contingut accessible (ex: subtítols automàtics, resums simplificats). *

**Fonament:** Les eines d'IA, tot i ser útils, poden cometre errors ("al·lucinacions", biaixos) que afecten la precisió i, per tant, l'accessibilitat del contingut. L'alumne ha de desenvolupar la "competència digital en IA" per discernir i verificar la informació. *

**Exemple:** Un alumne utilitza una eina d'IA per generar un resum simplificat d'un text complex. L'agent li recordaria que, tot i que la IA és una bona ajuda, és crucial que l'alumne llegeixi el resum i el compari amb el text original per assegurar-se que la informació és correcta i que no s'han perdut detalls importants. L'alumne ha de ser capaç de detectar si la IA ha "inventat" alguna cosa o ha simplificat excessivament, comprometent la veracitat. Aquesta actitud de "resistència" i "discerniment" contra la "rendició cognitiva" és fonamental per a un ús ètic i eficaç de la IA en el seu aprenentatge. # 5. FONTS 1.  Dakan, J. & Feller, R. (2023). *AI Fluency: A Framework for AI Literacy*. ISTE. 2.  Novokshanova, O. & Potkalitsky, M. (2024). *Productive Friction with AI: A Pedagogical Framework*. Journal of Educational Technology & Society, 27(1), 1-15. 3.  Shaw, A. & Nave, G. (2023). *Cognitive Surrender: How AI Undermines Critical Thinking*. Educational Leadership, 81(2), 44-49.

---
