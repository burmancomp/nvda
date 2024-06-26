# NVDA NVDA_VERSION Guia d'usuari 

[TOC]

<!-- KC:title: NVDA NVDA_VERSION Ordres Referència ràpida -->



## Introducció {#toc2}

NonVisual Desktop Access (NVDA) és un lector de pantalla de codi obert gratuït per al sistema operatiu Microsoft Windows.
NVDA permet a les persones cegues i amb dificultats de visió accedir als ordinadors que funcionen amb Windows amb el mateix esforç que a una persona amb visió gràcies a un feedback amb veu sintètica i braille.
NVDA ha estat desenvolupat per [{@hreflang=en}NV Access](https://www.nvaccess.org/), amb contribucions de la comunitat.

### Característiques generals {#toc3}

NVDA permet a les persones cegues i amb dificultat de visió accedir i interaccionar amb el sistema operatiu Windows i amb múltiples aplicacions de tercers.

En són aspectes destacables:

* NVDA és compatible amb aplicacions comunes com navegadors web, clients de correu electrònic, programes de xat, i paquets d'ofimàtica
* NVDA incorpora un sintetitzador de veu amb suport per a més de 80 idiomes
* Si el programa dóna informació sobre el format del text, NVDA n'informa i anuncia la família tipogràfica, el cos, l'estil i avisa d'errors ortogràfics
* NVDA avisa automàticament del text que es troba sota el ratolí i opcionalment indica la posició del ratolí per so
* NVDA és compatible amb moltes línies braille, i també accepta entrades en braille d'ordinador per a aquelles línies braille que tenen teclat
* NVDA pot executar-se totalment des d'un llapis USB o altres suports portables, sense requerir instal·lació
* L'instal·lador de NVDA és amb veu i fàcil d'usar
* NVDA s'ha traduït a 47 idiomes
* NVDA és compatible amb els sistemes operatius Windows moderns, tant amb les versions de 32 bits com les de 64 bits
* NVDA funciona a la pantalla d'entrada de Windows i en altres pantalles de seguretat
* NVDA és compatible amb interfícies d'accessibilitat comunes com Microsoft Active Accessibility, Java Access Bridge, IAccessible2 o UI Automation (NVDA només és compatible amb UI Automation a partir de Windows 7)
* NVDA és compatible amb la línia d'ordres Windows i amb aplicacions de consola

### Internacionalització {#toc4}

és important que les persones d'arreu del món, parlin l'idioma que parlin, tinguin accés equitatiu a la tecnologia.
A banda d'oferir-se en anglès, NVDA s'ha traduït a 47 idiomes més, entre ells: afrikaans, albanès, alemany, amhàric, àrab, aragonès, búlgar, català, coreà, croata, danès, eslovac, eslovè, espanyol, espanyol de Colòmbia,  farsi, finès, francès, gallec, georgià, grec, hebreu, hindi, holandès, hongarès, irlandès, islandès, italià, japonès, nepalès, noruec, persa, polonès, portuguès, portuguès de Brasil, punjabi, romanès, rus, serbi, suec, tailandès, tàmil, txec, turc, ucraïnès, vietnamita i xinès tradicional i simplificat.

### Compatibilitat amb sintetitzadors de veu {#toc5}

A banda de facilitar els missatges i la interfície en múltiples idiomes, NVDA permet que l'usuari llegeixi el contingut en qualsevol idioma, sempre i quan tingui un sintetitzador de veu en aquell idioma.

NVDA incorpora [{@hreflang=en}eSpeak](https://espeak.sourceforge.net/), un sintetitzador de veu multilingüe gratuït i de codi obert.

Pots trobar informació sobre altres sintetitzadors de veu compatibles amb NVDA a la secció [Sintetitzadors de veu compatibles](#SupportedSpeechSynths).

### Compatibilitat amb dispositius braille {#toc6}

Per als usuaris que posseeixen un terminal braille, NVDA pot mostrar la seva informació en braille. 
Consulta la secció [Línies braille compatibles](#SupportedBrailleDisplays) per obtenir informació sobre les línies braille compatibles.

NVDA és compatible amb els codis braille de molts idiomes, tant amb les versions compactes com amb les versions no compactes dels codis.

### Llicència i drets d'autor {#toc7}

La propietat intel·lectual de NVDA és dels contribuïdors NVDA_COPYRIGHT_YEARS NVDA.

NVDA té una llicència GNU General Public License (Versió 2).
Tens permís per compartir o canviar aquest programari de qualsevol manera sempre i quan vagi acompanyat de la llicència i facilitis el codi font a qualsevol persona que el vulgui.
Aquest permís afecta tant la còpia original d'aquest programari com les modificacions, i també les obres derivades.
Si en vols saber més, pots [{@hreflang=en}veure la llicència completa.](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html)

## Requisits de sistema {#toc8}

* Sistemes operatius: totes les versions de 32 bits i de 64 bits de Windows XP, Windows Vista, Windows 7, Windows 8 i Windows 10 (inclosos els sistemes operatius de servidor)
 * Per al Windows XP de 32 bits, cal el Service Pack 2 o superior.
 * Per al Windows Server 2003, cal el Service Pack 1 o superior.
 * Per al Windows vista, cal esl Service Pack 2 i l'actualització [KB2763674](https://support.microsoft.com/en-us/kb/2763674).
 * Totes dues s'han d'instal·lar si totes les actualitzacions disponibles s'apliquen a través del Windows Update.
* Memòria RAM: 256 MB o més.
* Velocitat de processador: 1.0 GHz o més.
* Espai de disc de 50 MB aproximadament.

## Descàrrega i instal·lació de NVDA {#toc9}

Si encara no tens una còpia de NVDA, pots descarregar-te-la de [www.nvaccess.org](NVDA_URL).

Ves a la secció de descàrrega i trobaràs un enllaç per descarregar la darrera versió de NVDA.

Si executes el fitxer que t'acabes de descarregar iniciaràs una versió temporal de NVDA.
Llavors el programa et demanarà si vols instal·lar NVDA, crear una versió portable, o simplement continuar amb la versió temporal.

Si tens pensat de fer servir sempre NVDA en aquest ordinador, instal·la NVDA.
Instal·lar NVDA et dóna accés a funcions addicionals com per exemple que el programa s'iniciï automàticament en engegar, la capacitat de llegir l'inici de sessió de Windows i altres pantalles de seguretat de Windows (aquesta funció no està activa en les versions temporals i portables) i poder crear enllaços al programa des de l'escriptori o des del menú d'inici.
La versió instal·lada pot copiar-se en una versió portable en qualsevol moment.

Si vols portar NVDA amb tu en un llapis USB o en algun altre suport informàtic, llavors hauries de triar de crear la versió portable.
La versió portable permet fer una instal·lació completa posteriorment en qualsevol ordinador.
Si el que vols és copiar NVDA en un suport d'emmagatzematge només de lectura, el més aconsellable és que copiïs el fitxer descarregat.
Actualment NVDA no permet executar la versió portable des d'un suport només de lectura.

Una altra opció és fer servir la versió temporal de NVDA (per exemple amb finalitats demostratives), però iniciar NVDA d'aquesta manera cada vegada pot suposar molt de temps.

### Restriccions en les versions portable i temporal {#toc10}

A banda de no poder iniciar-se automàticament durant o després de l'inici de sessió, les versions portables i temporals de NVDA tenen es restriccions següents:

* No poden interaccionar amb aplicacions que s'executen amb privilegis d'administrador, tret que NVDA s'executi també amb permisos d'administrador (no recomanable).
* No poden llegir pantalles de Control de comptes d'usuari (UAC) quan s'intenta iniciar una aplicació amb privilegis d'administrador.
* Windows 8: no són compatibles amb l'entrada des de pantalla tàctil.
* Windows 8: no ofereixen algunes funcions a les aplicacions de Windows Store, com ara el mode de navegació o la verbalització de caràcters escrits.

### Instal·lació de NVDA {#toc11}

Si fas la instal·lació de NVDA des del paquet descarregat, prem el botó Instal·la NVDA.
Si has tancat aquest diàleg o vols fer la instal·lació des d'una versió portable, escull l'opció de menú Instal·la NVDA, a Eines al menú NVDA.

El diàleg d'instal·lació et demanarà que confirmis si vols instal·lar NVDA i t'indicarà si aquesta instal·lació n'actualitza una de prèvia.
En prémer el botó Continua, la instal·lació de NVDA s'iniciarà.
Hi ha altres opcions en aquest diàleg que s'expliquen més avall.
Un cop la instal·lació hagi finalitzat, apareixerà un missatge que indica que tot ha anat bé.
Si prems D'acord en aquest punt la nova versió instal·lada de NVDA s'iniciarà.

#### Inici a l'inici de sessió de Windows {#toc12}

Aquesta opció et permet triar si vols que NVDA s'iniciï automàticament a l'inici de sessió de Windows, abans que introdueixis la contrasenya. 
Això també inclou controls UAC i altres pantalles de seguretat.

#### Crear una drecera d'escriptori (Ctrl+Alt+n) {#toc13}

Aquesta opció et permet triar si vols crear una drecera d'escriptori per iniciar NVDA. 
Si crees la drecera, tindrà associada la combinació de tecles Ctrl+Alt+n que et permetrà iniciar NVDA en qualsevol moment quan premis aquestes tecles.

#### Copiar la configuració de la versió portable al compte d'usuari actual {#toc14}

Aquesta opció et permet triar si NVDA ha de copiar la configuració de NVDA que s'està executant en aquell moment a la configuració de l'usuari actual, per la versió instal·lada de NVDA. 
Aquesta opció no copiarà la configuració a altres usuaris del sistema ni a la configuració de sistema per a l'inici de sessió de Windows ni per a altres pantalles de seguretat.
Aquesta opció només apareix quan es fa la instal·lació a partir d'una versió portable, i no apareix quan es fa la instal·lació des del paquet d'instal·lació.

### Creació d'una versió portable {#toc15}

Si vols crear una versió portable directament des del fitxer d'instal·lació, només has de prémer el botó Crea versió portable.
Si ja has tancat aquest diàleg o estàs executant una versió instal·lada de NVDA, has de triar l'opció de menú Crea versió portable, a Eines al menú NVDA.

El diàleg que apareix et permet escollir la ubicació de la versió portable.
Pots triar d'instal·lar-la en una carpeta del teu disc dur, o en un llapis USB, o en altres suports portables.
També pots triar de copiar la configuració NVDA de l'usuari amb sessió de Windows activa a la versió portable que s'està creant.
Aquesta opció només apareix quan es crea una versió portable a partir d'una versió instal·lada, i no apareix quan es fa la instal·lació des del fitxer d'instal·lació. 
Si prems Continuar, crearàs la versió portable.
Un cop la creació ha finalitzat, apareixerà un missatge que indica que tot ha anat bé.
Si prems D'acord el diàleg desapareixerà.

## Introducció a NVDA {#toc16}
### Iniciar NVDA {#toc17}

Si has instal·lat NVDA amb l'instal·lador, iniciar NVDA és tan senzill com prémer Ctrl+Alt+n, o seleccionar NVDA al menú NVDA a Programes del Menú d'inici.
També pots iniciar el programa si escrius NVDA al diàleg Executa de Windows i prems Retorn.
També pots executar algunes [opcions de línia de comandes](#CommandLineOptions) que et permeten reiniciar NVDA (-r), sortir (-q), desactivar extensions (--disable-addions), i altres.

Per iniciar la versió portable, vés a la carpeta on has descomprimit NVDA, i prem Retorn o fes doble clic a nvda.exe.

Quan NVDA s'inicia, primer sentiràs un conjunt de tons ascendents (per avisar que NVDA s'està carregant).
Si el teu ordinador és molt lent, o executes NVDA des d'un llapis USB o des d'un suport encara més lent, el programa pot trigar una mica a començar.
Si requereix un temps més llarg, NVDA hauria de dir "NVDA s'està carregant. Un moment..."

Si no sents res d'això, o si sents el so d'error de Windows, o un conjunt de tons descendents, significa que NVDA té un error, i caldria informar del problema als desenvolupadors.
Mira com fer-ho al web de NVDA .

Quan NVDA comença per primer cop, el programa et saluda amb un quadre de diàleg que dóna informació bàsica sobre la tecla modificadora de NVDA i el menú NVDA.
(Consulta les seccions següents sobre aquests temes.)
El quadre de diàleg conté també tres caselles de selecció.
La primera casella et permet triar si vols que NVDA utilitzi la tecla Bloqueig de majúscules com a tecla modificadora.
La segona casella et permet triar si vols que NVDA arrenqui automàticament en iniciar Windows i només apareix en les versions instal·lades de NVDA.
La tercera casella permet controlar si aquest diàleg de benvinguda ha d'aparèixer cada cop que NVDA s'inicia.

### Ordres de teclat de NVDA {#toc18}
#### Tecla modificadora de NVDA {#toc19}

La majoria d'ordres de teclat específiques de NVDA es basen en prémer una tecla concreta anomenada tecla modificadora de NVDA i prémer alhora una o més tecles addicionals.
Una excepció remarcable a aquest funcionament són les ordres de revisió de text en la disposició de teclat de sobretaula que usen només el teclat numèric, però existeixen altres ordres que no fan ús de la tecla modificadora.

Es pot configurar NVDA per tal que la tecla modificadora de NVDA sigui la tecla d'inserció del teclat numèric, la tecla d'inserció del teclat estès, o la tecla Bloqueig de majúscules.
De forma predeterminada, tant la tecla d'inserció del teclat numèric, com la tecla d'inserció del teclat estès, funcionen com a tecles modificadores de NVDA.

Si vols que una de les tecles modificadores de NVDA realitzi la seva funció original (per exemple si vols activar el Bloqueig de majúscules mentre la tecla Bloqueig de majúscules funciona com a tecla modificadora de NVDA), pots prémer la tecla ràpidament dos cops.

#### Disposicions de teclat {#toc20}

NVDA s'ofereix actualment amb dos conjunts d'ordres de teclat (anomenats disposicions de teclat): una disposició de teclat per a ordinadors de sobretaula i una disposició de teclat per a ordinadors portàtils.
De forma predeterminada, NVDA està configurat per usar el teclat d'ordinadors de sobretaula, però pots canviar al teclat per a ordinadors portàtils a la Configuració de teclat, que es troba a Preferències al menú NVDA.

La disposició de teclat de sobretaula fa un ús extensiu del teclat numèric (amb el bloqueig del teclat numèric desactivat).
Tot i que molts portàtils no tenen un teclat numèric físic, en alguns portàtils s'emula prement la tecla de funció (FN) i les lletres i números de la dreta del teclat (7 8 9 u i o j k l etc).
Si el teu portàtil no té aquesta funció, o no et permet desactivar el bloqueig numèric, el més recomanable és que canviïs a la disposició de teclat per a portàtils.

### Gestos tàctils de NVDA {#toc21}

Si executes NVDA en un ordinador amb pantalla tàctil, a Windows 8 o una versió posterior, pots controlar NVDA directament des de la pantalla tàctil.
Mentre s'executi NVDA, totes les entrades tàctils aniran directament a NVDA. 
En conseqüència, les accions que normalment es poden fer sense NVDA no funcionaran.

#### Exploració de la pantalla {#toc22}

L'acció més bàsica que pots fer amb la pantalla tàctil és anunciar el control o el text des de qualsevol punt de la pantalla.
Per fer-ho, posa el dit a qualsevol lloc de la pantalla.
Pots mantenir el dit a la pantalla i moure'l amunt i avall per llegir altres controls i text per on passi el dit.

#### Gestos tàctils {#toc23}

Quan més endavant es descriguin les ordres de NVDA, sovint s'indicarà quin gest tàctil s'usa per activar aquella ordre amb la pantalla tàctil.
A continuació pots trobar algunes instruccions sobre com fer els diferents gestos tàctils.

##### Tocs {#toc24}

Toca la pantalla ràpidament amb un o més dits.

Tocar una vegada amb un dit es coneix simplement com a toc.
Tocar amb dos dits alhora és un toc de dos dits, i així successivament.

Si el mateix toc es fa una o més vegades ràpidament, NVDA entendrà l'acció com un gest multitoc.
Tocar dues vegades s'entendrà com un toc doble.
Tocar tres vegades s'entendrà com un toc triple, i així successivament.
Els gestos multitocs evidentment reconeixen quants dits s'han usat, per això és possible indicar gestos com toc triple amb dos dits, toc amb quatre dits, etc. 

##### Moviments ràpids {#toc25}

Arrossega ràpidament el teu dit al llarg de la pantalla.

Existeixen quatre gestos de moviments ràpids segons la direcció en què es fan: moviment ràpid cap a l'esquerra, moviment ràpid cap a la dreta, moviment ràpid cap amunt i moviment ràpid cap avall.

De la mateixa manera que en els tocs, es pot usar més d'un dit per fer el gest de moviment ràpid.
Per això, són possibles gestos com moviments ràpids amb dos dits, moviment ràpid cap a l'esquerra amb quatre dits, etc.

#### Modes tàctils {#toc26}

Com que hi ha més ordres de NVDA que gestos tàctils disponibles, NVDA ofereix diferents modes tàctils, cadascun amb un subconjunt d'ordres, entre els quals pots alternar.
Els dos modes tàctils són el mode textual i el mode objecte. 
Algunes ordres de NVDA llistades en aquest document poden tenir un mode tàctil indicat entre parèntesi després del gest tàctil.
Per exemple, moviment ràpid amunt (mode de text) significa que l'ordre s'executarà si fas el moviment ràpid cap amunt però només en el mode de text.
Si l'ordre no indica cap mode tàctil, funcionarà en ambdós modes.

<!-- KC:beginInclude -->
Per canviar entre modes tàctils, fes un toc amb tres dits.
<!-- KC:endInclude -->

### Mode d'ajuda d'entrada {#toc27}

Al llarg d'aquesta guia d'usuari es mencionen moltes ordres de NVDA: una manera fàcil d'explorar totes les ordres és activar l'ajuda d'entrada.

Per activar l'ajuda d'entrada, prem NVDA+1.
Per desactivar-la, prem de nou NVDA+1.
Mentre l'ajuda d'entrada està activada, realitzar una acció d'entrada (tal com prémer una tecla o fer un gest tàctil) informarà sobre l'acció realitzada i en descriurà la funció (si n'hi ha).
En aquest mode les ordres no s'executaran.

### El menú NVDA {#toc28}

El menú NVDA et permet controlar la configuració del programa, accedir a l'ajuda, desar o restablir la configuració, modificar els diccionaris de síntesi de veu, accedir a eines addicionals i sortir de NVDA.

Per accedir al menú NVDA des de qualsevol lloc a Windows mentre NVDA s'està executant, prem NVDA+n al teclat o fes un toc doble amb dos dits a la pantalla tàctil.
També pots accedir al menú NVDA des del menú de sistema Windows.
Fes clic amb el botó dret a la icona de NVDA de la safata del sistema, o bé accedeix a la safata del sistema prement la tecla del logotip de Windows + B, la fletxa avall a la icona de NVDA i prem la tecla d’aplicacions que es troba a la dreta de la tecla Control a la majoria de teclats.
Quan aparegui el menú, pots usar les tecles de fletxa per navegar pel menú, i la tecla Retorn per activar un element.

### Ordres bàsiques NVDA {#toc29}

<!-- KC:beginInclude -->

| Nom |Tecla en teclat de sobretaula |Tecla en teclat de portàtil |Gest |Descripció|
|---|---|---|---|---|
|Parar veu |Ctrl |Ctrl |Toc amb dos dits |Para la veu instantàniament|
|Pausar veu |Maj |Maj |cap |Para la veu instantàniament. En prémer-la de nou tornarà a parlar a partir del punt on s'ha aturat (si el sintetitzador de veu usat és compatible amb la pausa de veu)|
|Menú NVDA |NVDA+n |NVDA+n |Toc doble amb dos dits |Fa aparèixer el menú NVDA que et permet accedir a les preferències, eines, ajuda etc|
|Commutar Mode de so |NVDA+s |NVDA+s |cap |Canvia el mode de so entre parla, emissió de xiulets i desactivat|
|Commuta el mode d'ajuda d'entrada |NVDA+1 |NVDA+1 |cap |En aquest mode prémer una tecla informarà sobre la tecla premuda i descriurà l'ordre de NVDA que té associada|
|Sortir de NVDA |NVDA+q |NVDA+q |cap |Tanca NVDA|
|Enviar la següent tecla directament |NVDA+f2 |NVDA+f2 |Cap |Indica a NVDA que la següent tecla s'ha d'enviar directament a l'aplicació activa, fins i tot si aquesta tecla s'entendria normalment com a una ordre NVDA|
|Activa i desactiva el mode de suspensió |NVDA+Maj+s |NVDA+Maj+z |cap |El mode de suspensió desactiva totes les ordres de NVDA i la sortida de veu i/o braille per a l'aplicació actual. Aquesta funció és útil a les aplicacions que ja disposen de veu pròpia o de funcions de lector de pantalla. Per desactivar el mode de veu premeu de nou l'ordre|

<!-- KC:endInclude -->

### Informació del sistema {#toc30}

<!-- KC:beginInclude -->

| Nom |tecla |Descripció|
|---|---|---|
|Informa del dia i hora |NVDA+f12 |Prémer una vegada informa de l'hora, prémer dues vegades informa de la data|
|Informar de l'estat de la bateria |NVDA+Maj+b |Informa de l'estat de la bateria, és a dir, si hi ha corrent elèctrica o el percentatge de càrrega actual|
|Informa del text del porta-retalls |NVDA+c |Informa del text del porta-retalls si n'hi ha.|

<!-- KC:endInclude -->

## Navegació amb NVDA {#toc31}

NVDA et permet explorar i navegar pel sistema de diverses maneres, tant en interacció normal com en revisió.

### Objectes {#Objects}

Cada aplicació i també el sistema operatiu consta de diversos objectes.
Un objecte és un element simple com un tros de text, un botó, una casella de selecció, un control lliscant, una llista o un camp de text editable.

### Navegació amb el focus de sistema {#SystemFocus}

El focus de sistema, conegut també simplement com a focus, és l'[objecte](#Objects) que rep les tecles premudes en el teclat. 
Per exemple, si estàs escrivint en un camp de text editable, el camp de text editable té el focus.

La manera més habitual de moure's per Windows amb NVDA consisteix simplement a moure el focus de sistema fent servir les ordres de teclat estàndard de Windows, com ara la tecla de tabulador o Majúscula+tabulador per avançar o retrocedir entre controls, prémer la tecla Alt per anar a la barra de menús i moure's pel menú amb les tecles de fletxa, i usar Alt+Tab per moure's entre les aplicacions en execució.
Mentre fas aquestes accions, NVDA t'informarà sobre l'objecte que rep el focus, i te n'indicarà nom, tipus, valor, estat, descripció, drecera de teclat i et donarà informació de la seva posició.

Hi ha algunes ordres de teclat que són útils per moure's amb el focus de sistema:
<!-- KC:beginInclude -->

| Nom |Tecla en teclat de sobretaula |Tecla en teclat portàtil |Descripció|
|---|---|---|---|
|Informa del focus actual |NVDA+Tab |NVDA+Tab |Anuncia l'objecte o control actual que rep el focus del sistema. Si prems dos cops lletreja el nom|
|Informa del títol |NVDA+t |NVDA+t |Informa del títol de la finestra activa actual. Si prems dos cops l'ordre lletreja el títol. Si prems tres cops l'ordre copiarà el títol al porta-retalls|
|Llegeix la finestra activa |NVDA+b |NVDA+b |Llegeix tots els controls de la finestra activa actualment (útil per a diàlegs)|
|Informa de la barra d'estat |NVDA+FI |NVDA+Maj+FI |Informa de la barra d'estat si NVDA n'ha trobat una. També mou l'objecte de navegació a aquesta ubicació. Si prems dos cops lletreja el nom|

<!-- KC:endInclude -->

### Navegació amb el cursor del sistema {#SystemCaret}

Quan un [objecte](#Objects) que permet la navegació o edició del text rep el [focus](#SystemFocus), pots desplaçar-te pel text fent servir el cursor del sistema, també conegut com a cursor d'edició.

Quan el focus és en un objecte que té el cursor del sistema, pots usar les tecles de fletxa, Re Pàg, Av Pàg, Fi, etc. per desplaçar-te dins el text.
També pots canviar el text si el control permet l'edició.
NVDA t'avisarà del text lletra a lletra, paraula a paraula o línia a línia mentre et mous i també t'anunciarà si selecciones o desselecciones text.

NVDA ofereix les següents ordres de teclat relacionades amb el cursor del sistema:
<!-- KC:beginInclude -->

| Nom |Tecla en teclat de sobretaula |Tecla en teclat portàtil |Descripció|
|---|---|---|---|
|Verbalitza-ho tot |NVDA+fletxa avall |NVDA+a |Comença a llegir des de la posició actual del cursor del sistema, i es mou a mesura que avança|
|Llegeix la línia actual |NVDA+fletxa amunt |NVDA+l |Llegeix la línia en què es troba el cursor del sistema. Si prems dos cops lletreja la línia|
|Llegeix la selecció de text actual |NVDA+Majúscules+fletxa amunt |NVDA+Maj+s |Llegeix qualsevol text seleccionat en aquell moment|
|Frase següent |Alt+fletxa avall |Alt+fletxa avall |Mou el cursor del sistema a la frase següent i l'anuncia. (compatible només amb Microsoft Word i Outlook)|
|Frase anterior |Alt+fletxa amunt |Alt+fletxa amunt |Mou el cursor del sistema a la frase anterior i l'anuncia. (compatible només amb Microsoft Word i Outlook)|

Quan et trobes dins d'una taula, les següents ordres de teclat també estan disponibles:

| Nom |Tecla |Descripció|
|---|---|---|
|Mou a la columna anterior |Ctrl+Alt+fletxa esquerra |Mou el cursor del sistema a la columna anterior (mantenint-se a la mateixa fila)|
|Mou a la columna següent |Ctrl+Alt+fletxa dreta |Mou el cursor del sistema a la columna següent (mantenint-se a la mateixa fila)|
|Mou a la fila anterior |Ctrl+Alt+fletxa amunt |Mou el cursor del sistema a la fila anterior (mantenint-se a la mateixa columna)|
|Mou a la fila següent |Ctrl+Alt+fletxa avall |Mou el cursor del sistema a la fila següent (mantenint-se a la mateixa columna)|

<!-- KC:endInclude -->

### Navegació d'objectes {#toc35}

La major part del temps, treballaràs amb les aplicacions usant ordres que mouen el [focus](#SystemFocus) i el [cursor del sistema](#SystemCaret).
Tot i així, a vegades, pot ser que vulguis explorar l'aplicació actual o el sistema operatiu sense moure el focus o el cursor.
Potser també vols treballar amb [objectes](#Objects) als quals no pots accedir amb el teclat.
En aquests casos, pots usar la navegació d'objectes.

La navegació d'objectes et permet moure't entre els [objectes](#Objects) individuals i obtenir-ne informació.
Quan et desplacis a un objecte, NVDA t'informarà de manera similar a com t'informa del focus de sistema.
Alternativament, per revisar tot el text que apareix a pantalla, pots usar la [revisió de pantalla](#ScreenReview).

En comptes de desplaçar-te endavant i enrere entre cadascun dels objectes del sistema, aquests estan organitzats jeràrquicament.
Això significa que alguns objectes en contenen d'altres i que has de desplaçar-te dins d'ells per accedir als objectes que contenen.
Per exemple, una llista conté elements de llista, i has de desplaçar-te dins la llista per poder accedir als seus elements.
Si t'has desplaçat fins a un element de llista, les ordres següent i anterior et mouran als altres elements de la mateixa llista.
Si et desplaces a l'objecte contenidor dels elements de llista, tornaràs a la llista.
En aquell moment pots desplaçar-te més enllà de la llista si vols accedir a altres objectes.
Igualment, una barra d'eines conté controls, i has de desplaçar-te dins la barra per accedir als controls de la barra d'eines.

L'objecte que estàs revisant en un moment donat s'anomena objecte de navegació.
Un cop has navegat a un objecte, pots revisar-ne el contingut amb les [ordres de revisió de text](#ReviewingText) mentre ets en [mode de revisió d'objectes](#ObjectReview).
Per defecte, l'objecte de navegació es mou amb el focus de sistema, però pots activar o desactivar aquest comportament.

Tingues en compte que, de forma predeterminada, la línia braille segueix el [focus](#SystemFocus) i el [cursor del sistema](#SystemCaret), i no la navegació d'objectes o la revisió de text.
Si prefereixes seguir la navegació d'objectes o la revisió de text, has de [configurar el seguiment de braille](#BrailleTether) al cursor de revisió.

Per a la navegació d'objectes, fes servir les següents ordres:

<!-- KC:beginInclude -->

| Nom |Tecla en teclat de sobretaula |Tecla en teclat de portàtil |Gest |Descripció|
|---|---|---|---|---|
|Informa de l'objecte actual |NVDA+ teclat numèric 5 |NVDA+Maj+o |cap |Informa de l'objecte de navegació actual. Si prems dos cops lletreja la informació, i si prems tres cops copia el nom i valor de l'objecte al porta-retalls|
|Mou a l'objecte contenidor |NVDA+teclat numèric 8 |NVDA+Maj+fletxa amunt |moviment ràpid cap amunt (mode d'objecte) |Et mou a l'objecte que conté l'actual objecte de navegació|
|Mou a l'objecte anterior |NVDA+teclat numèric4 |NVDA+Maj+fletxa esquerra |moviment ràpid cap a l'esquerra (mode d'objecte) |Et mou a l'objecte anterior a l'actual objecte de navegació|
|Mou l'objecte següent |NVDA+teclat numèric 6 |NVDA+Maj+fletxa dreta |moviment ràpid cap a la dreta (mode d'objecte) |Et mou a l'objecte següent a l'actual objecte de navegació|
|Mou al primer objecte contingut |NVDA+teclat numèric 2 |NVDA+Maj+fletxa avall |moviment ràpid cap avall (mode d'objecte) |Et mou al primer objecte inclòs en l'actual objecte de navegació|
|Mou a l'objecte amb focus |NVDA+Menys teclat numèric |NVDA+Retrocés |cap |Et mou a l'objecte que actualment rep el focus del sistema, i desplaça el cursor de revisió a la posició del cursor del sistema, si aquesta es mostra|
|Activa l'objecte de navegació actual |NVDA+Retorn teclat numèric |NVDA+retorn |toc doble |Activa l'actual objecte de navegació (fa la mateixa funció que clicar amb el ratolí o prémer la barra espaiadora quan l'objecte té el focus del sistema)|
|Mou el focus del sistema o el cursor a la posició de revisió actual |NVDA+Maj+Menys teclat numèric |NVDA+Maj+Retrocés |cap |Si es prem un cop mou el focus del sistema a l'actual objecte de navegació, si es prem dos cops mou el cursor del sistema a la posició del cursor de revisió|
|Informa de la posició del cursor de revisió |NVDA+Supr teclat numèric |NVDA+Supr |cap |Informa de la posició del text o objecte on es troba el cursor de revisió. La posició pot indicar-se, per exemple, com a percentatge dins el document, com a distància des del marge de la pàgina, o amb les coordenades exactes de la pantalla. Si es prem dos cops dóna més detalls|

<!-- KC:endInclude -->

Atenció: has de desactivar la tecla Bloqueig del teclat numèric perquè les tecles del teclat numèric funcionin correctament.

### Revisió de text {#ReviewingText}

NVDA et permet llegir el contingut de la [pantalla](#ScreenReview), el [document](#DocumentReview) actual o l'[objecte](#ObjectReview) actual, lletra a lletra, paraula a paraula o línia a línia.
Aquesta funció és especialment útil quan no existeix [cursor del sistema](#SystemCaret) (també a la consola Windows).
Per exemple, pots usar aquesta funció per revisar el text d'un missatge llarg en un diàleg.

Quan mous el cursor de revisió, el cursor del sistema no es desplaça amb ell, per permetre't revisar el text sense perdre la posició d'edició.
En canvi, de forma predeterminada, quan mous el cursor del sistema, el cursor de revisió sí que el segueix.
Això es pot activar o desactivar.

Cal tenir en compte que, de forma predeterminada, la línia braille segueix el [focus](#SystemFocus) i el [cursor del sistema](#SystemCaret), i no la navegació d'objectes o la revisió de text.
Si prefereixes seguir la navegació d'objectes o la revisió de text, has de [configurar el seguiment de braille](#BrailleTether) al cursor de revisió.

Disposes de les següents ordres per revisar el text:
<!-- KC:beginInclude -->

| Nom |Tecla en teclat de sobretaula |Tecla en teclat de portàtil |Gest |Descripció|
|---|---|---|---|---|
|Mou a la línia en revisió superior |Majúscules+teclat numèric 7 |NVDA+Ctrl+Inici |cap |Mou el cursor de revisió a la línia superior del text|
|Mou a la línia en revisió anterior |teclat numèric 7 |NVDA+fletxa amunt |moviment ràpid cap amunt (mode de text) |Mou el cursor de revisió a la línia de text anterior|
|Informa de la línia en revisió actual |teclat numèric 8 |NVDA+Maj+. |cap |Anuncia la línia de text on es troba actualment el cursor de revisió. Si prems dos cops lletreja la línia. Si prems tres cops lletreja la línia amb les descripcions dels caràcters|
|Mou a la línia en revisió següent |teclat numèric 9 |NVDA+fletxa avall |moviment ràpid cap avall (mode de text) |Mou el cursor de revisió a la següent línia de text|
|Mou a la línia de revisió inferior |Majúscules+teclat numèric 9 |NVDA+Ctrl+Fi |cap |Mou el cursor de revisió a la línia de text inferior|
|Mou a la paraula en revisió anterior |teclat numèric 4 |NVDA+Ctrl+fletxa esquerra |moviment ràpid cap a l'esquerra amb dos dits (mode de text) |Mou el cursor de revisió a la paraula anterior del text|
|Informa de la paraula en revisió actual |teclat numèric 5 |NVDA+Ctrl+. |cap |Anuncia la paraula en què es troba actualment el cursor de revisió. Si prems dos cops lletreja la paraula. Si prems tres cops lletreja la paraula amb les descripcions dels caràcters|
|Mou a la següent paraula en revisió |teclat numèric 6 |NVDA+Ctrl+fletxa dreta |moviment ràpid cap a la dreta amb dos dits (mode de text) |Mou el cursor de revisió a la següent paraula en el text|
|Mou al principi de la línia en revisió |Majúscules+teclat numèric 1 |NVDA+Inici |cap |Mou el cursor de revisió al principi de la línia de text actual|
|Mou al caràcter anterior en revisió |teclat numèric 1 |NVDA+fletxa esquerra |moviment ràpid cap a l'esquerra (mode de text) |Mou el cursor de revisió al caràcter anterior a la línia de text actual|
|Informa del caràcter en revisió actual |teclat numèric 2 |NVDA+. |cap |Anuncia el caràcter actual a la línia de text on es troba el cursor de revisió. Si prems dos cops et descriu o posa un exemple d'aquell caràcter. Si prems tres cops t'informa del valor numèric del caràcter en decimal o en hexadecimal|
|Mou al següent caràcter en revisió |teclat numèric 3 |NVDA+fletxa dreta |moviment ràpid cap a la dreta (mode de text) |Mou el cursor de revisió al següent caràcter en la línia de text actual|
|Mou al final de la línia en revisió |Majúscules+teclat numèric 3 |NVDA+Fi |cap |Mou el cursor de revisió al final de la línia de text actual|
|Verbalitza-ho tot en revisió |teclat numèric Més |NVDA+Maj+a |moviment ràpid cap avall amb tres dits (mode de text) |Llegeix des de la posició actual del cursor de revisió, i el desplaça mentre avança|
|Copia des del cursor de revisió |NVDA+f9 |NVDA+f9 |cap |Inicia el copiat de text des de la posició actual del cursor de revisió. La còpia no es farà efectiva fins que indiquis a NVDA a on copiar-ho|
|Copia al cursor de revisió |NVDA+f10 |NVDA+f10 |cap |Copia des de la posició del cursor de revisió marcat com a Copia des del cursor de revisió, a la posició actual del cursor de revisió. Després de prémer aquestes tecles, el text es copiarà al porta-retalls de Windows|
|Informa del format del text |NVDA+f |NVDA+f |cap |Informa del format del text en què es troba actualment el cursor de revisió|

<!-- KC:endInclude -->

Atenció: has de desactivar la tecla Bloqueig del teclat numèric perquè les tecles del teclat numèric funcionin correctament.

Un truc per recordar les ordres bàsiques de revisió de text en la disposició de teclat de sobretaula, és imaginar-les com si estiguessin en una quadrícula de tres per tres, i amb el significat de dalt a baix com a línia, paraula i caràcter i d'esquerra a dreta com a anterior, actual i següent.
La disposició s'exemplifica com es mostra a continuació:

|Línia anterior |Línia actual |Línia següent|
|Paraula anterior |Paraula actual |Paraula següent|
|Caràcter anterior |Caràcter actual |Caràcter següent|

### Modes de revisió {#ReviewModes}

Les [ordres de revisió de text](#ReviewingText) a NVDA permeten revisar el contingut dins l'actual objecte de navegació, document o pantalla, depenent del mode de revisió seleccionat.
Els modes de revisió reemplacen l'antic concepte de NVDA de revisió plana.

Les següents ordres permeten canviar el mode de revisió:
<!-- KC:beginInclude -->

| Nom |Tecla en teclat de sobretaula |Tecla en teclat de portàtil |Gest |Descripció|
|---|---|---|---|---|
|Canvia al següent mode de revisió |NVDA+teclat numèric 7 |NVDA+Re Pàg |moviment ràpid cap amunt amb dos dits |Canvia al següent mode de revisió disponible|
|Canvia a l'anterior mode de revisió |NVDA+teclat numèric 1 |NVDA+Av Pàg |moviment ràpid cap avall amb dos dits |Canvia a l'anterior mode de revisió disponible|

<!-- KC:endInclude -->

#### Revisió d'objectes {#ObjectReview}

Mentre et trobes en mode de revisió d'objectes, només pots revisar el contingut de l'[objecte de navegació](#ObjectNavigation) actual.
Per a altres objectes com camps de text editables o altres controls bàsics de text, generalment el contingut serà el propi text.
Per a altres objectes, el contingut pot ser el nom o el valor.

#### Revisió de documents {#DocumentReview}

Quan l'[objecte de navegació](#ObjectNavigation) es troba dins un document en mode de navegació (per ex. una pàgina web) o altres documents complexos (per ex. un document de Lotus Symphony), es pot canviar al mode de revisió de documents.
El mode de revisió de documents et permet revisar el text de tot el document.

Quan canvies del mode revisió d'objecte al mode de revisió de documents, el cursor de revisió se situa en el document a la posició de l'objecte de navegació.
Quan et desplaces amunt i avall del document amb ordres de revisió, l'objecte de navegació passa automàticament a ser l'objecte que es troba a la posició del cursor de revisió.

Tingues en compte que NVDA canviarà de revisió d'objecte a revisió de documents automàticament quan et desplacis amunt i avall del document en mode de navegació.

#### Revisió de pantalla {#ScreenReview}

El mode de revisió de pantalla et permet revisar el text de la pantalla tal i com apareix visualment a l'aplicació actual. 
Aquest mode és similar a la funció de revisió de pantalla o a la de cursor de ratolí en molts altres lectors de pantalla de Windows.

Quan canvies al mode de revisió de pantalla, el cursor de revisió se situa a la posició de pantalla de l'actual [objecte de navegació](#ObjectNavigation).
Quan et desplaces amunt i avall de la pantalla amb ordres de revisió, l'objecte de navegació passa automàticament a ser l'objecte que es troba a la posició de pantalla del cursor de revisió.

Tingues en compte que en algunes aplicacions més noves, NVDA potser no veu part o la totalitat del text mostrat a pantalla ja que aquest s'ha escrit amb noves tecnologies de dibuix a pantalla, ara mateix incompatibles amb NVDA.

### Navegació amb el ratolí {#toc41}

Quan desplaces el ratolí, NVDA de forma predeterminada informa del text que està just a sota del punter del ratolí així que el ratolí hi passa per sobre. 
En algunes aplicacions compatibles, NVDA llegirà el paràgraf de text circumdant, tot i que alguns controls potser només llegeixen línia a línia.

Pots configurar NVDA per anunciar també el tipus d'[objecte](#Objects) que es troba sota el ratolí quan aquest s'hi desplaça a sobre (per ex. una llista, un botó, etc.).
Aquesta funció pot ser útil per als usuaris totalment cecs, perquè de vegades, amb el text no n'hi ha prou.

NVDA ofereix un mecanisme perquè els usuaris sàpiguen on es troba el ratolí en relació amb les dimensions de la pantalla que consisteix en emetre les coordenades del ratolí en forma de so.
Com més amunt es trobi el ratolí respecte a la pantalla, més aguda serà la nota de l'avís.
Com més a l'esquerra o a la dreta es trobi el ratolí respecte a la pantalla, més a l'esquerra o a la dreta sonarà la nota de l'avís (sempre i quan l'usuari tingui altaveus o auriculars estèreo).

Aquestes característiques extres del ratolí per defecte no estan activades a NVDA.
Si vols gaudir-ne, pots configurar-les des del diàleg [Configuració del ratolí](#MouseSettings), que es troba dins el menú Preferències de NVDA.

Tot i que cal usar un ratolí físic o un ratolí tàctil per navegar amb el ratolí, existeixen unes quantes ordres de teclat relacionades amb el ratolí a NVDA:
<!-- KC:beginInclude -->

| Nom |Tecla en teclat de sobretaula |Tecla en teclat de portàtil |Descripció|
|---|---|---|---|
|Clica amb el botó esquerre del ratolí |Divisió teclat numèric |NVDA+[ |Fa un clic de botó esquerre de ratolí. El típic doble clic es pot aconseguir clicant aquesta combinació de tecles dues vegades ràpidament|
|Bloqueja el botó esquerre del ratolí |Majúscules+Divisió teclat numèric |NVDA+Ctrl+[ |Bloqueja el botó esquerre del ratolí avall. Prem de nou per desbloquejar. Per arrossegar el ratolí, prem aquestes tecles per bloquejar el botó esquerre avall, i llavors mou el ratolí físicament o amb les ordres de moviment de ratolí|
|Clica amb el botó dret de ratolí |Multiplicació teclat numèric |NVDA+] |Fa un clic de botó dret de ratolí.|
|bloqueig del botó dret del ratolí |Majúscules+Multiplicació teclat numèric |NVDA+Ctrl+] |Bloqueja el botó dret del ratolí avall. Prem de nou per desbloquejar. Per arrossegar el ratolí, prem aquestes tecles per bloquejar el botó dret avall, i llavors mou el ratolí físicament o amb les ordres de moviment de ratolí|
|Mou el cursor a l'objecte de navegació actual |NVDA+Divisió teclat numèric |NVDA+Maj+m |Mou el ratolí a la posició de l'objecte de navegació actual, i del cursor de revisió|
|Navega a l'objecte sota el ratolí |NVDA+Multiplicació teclat numèric |NVDA+Maj+n |L'objecte de navegació passa a ser l'objecte ubicat a la posició del ratolí|

<!-- KC:endInclude -->

## Mode de navegació {#toc42}

NVDA navega pels documents complexos només de lectura, com ara pàgines web, amb el mode de navegació.
Així es llegeixen els documents de Mozilla Firefox, Microsoft Internet Explorer, missatges HTML de Microsoft Outlook, Google Chrome, Adobe Reader i Adobe Flash.
El mode de navegació, opcionalment, també està disponible per als documents Microsoft Word.

En mode de navegació, el contingut del document s'ofereix en una representació plana que es pot navegar amb les tecles de cursor com si fos un document de text normal.
Totes les ordres de teclat de NVDA del [cursor del sistema](#SystemCaret) funcionaran en aquest mode; per exemple verbalitza-ho tot, informa del format, ordres de navegació per taules, etc.
Mentre et vas movent, NVDA informa del text i també si aquest és un enllaç, un encapçalament, etc.

Algunes vegades, en aquests documents, et caldrà interaccionar directament amb controls.
Per exemple, et caldrà fer-ho en els camps de text editables, i a les llistes per tal de poder escriure caràcters i usar les tecles de cursor per treballar amb el control.
Per fer-ho cal canviar a mode de focus, on quasi totes les tecles s'envien al control.
Quan et trobes en mode de navegació, NVDA de forma predeterminada canviarà al mode de focus si cliques o et mous amb el tabulador a un control en particular que requereix aquest mode.
Inversament, quan cliques o et mous amb el tabulador a un control que no requereix el mode de focus, NVDA tornarà al mode de navegació.
També pots canviar al mode de focus en els controls que així ho requereixin prement Retorn o la Barra espaiadora.
Si prems tecla d'escapada tornaràs al mode de navegació.
A més, pots forçar el mode de focus manualment, que romandrà actiu fins que decideixis desactivar-lo.

<!-- KC:beginInclude -->

| Nom |Tecla |Descripció|
|---|---|---|
|Canvia de modes entre navegació i focus |NVDA+Barra espaiadora |Canvia entre el mode de focus i el mode de navegació|
|Surt del mode de focus |Tecla d'escapada |Retorna al mode de navegació si el mode de focus s'ha activat automàticament|
|Actualitza el document en navegació |NVDA+f5 |Recarrega el contingut del document actual (útil si sembla que falti part del contingut del document. No disponible a Microsoft Word i a Outlook.)|
|Busca |NVDA+Ctrl+f |Obre un diàleg en el qual pots escriure un text per buscar-lo al document|
|Busca següent |NVDA+f3 |Troba l'ocurrència següent en el document del text que has buscat prèviament|
|Busca anterior |NVDA+Maj+f3 |Troba l'anterior ocurrència en el document del text que has buscat prèviament|
|Obrir descripció llarga |NVDA+d |Obre una nova finestra que conté una descripció llarga de l'element actiu, si és que en té.|

<!-- KC:endInclude -->

### Navegació amb una sola lletra {#toc43}

Quan et trobes en mode de navegació, per facilitar una navegació més ràpida, NVDA ofereix algunes tecles d'una sola lletra per saltar a certs camps del document.
Cal tenir en compte que no totes aquestes ordres actúen en tots els tipus de documents.

<!-- KC:beginInclude -->
Les següents tecles, per sí soles, salten a l'element posterior disponible, i si hi afegeixes la tecla de Majúscules, salten a l'element anterior:

* h: encapçalament
* l: llista
* i: element de llista
* t: taula
* k: enllaç
* n: text sense enllaços
* f: camp de formulari
* u: enllaç no visitat
* v: enllaç visitat
* e: camp editable
* b: botó
* x: casella de selecció
* c: quadre combinat
* r: botó d'opció
* q: cita en bloc
* s: separador
* m: marc
* g: gràfic
* d: marca estructural
* o: objecte incrustat
* 1 to 6: encapçalaments de nivells 1 a 6 respectivament.
 -a: nota (comentari, revisió de l'editor, etc.)

Per moure's a l'inici o al final dels elements contenidors com les llistes o taules:

| Nom |Tecla |Descripció|
|---|---|---|
|Mou al principi del contenidor |Majúscules+coma |Mou al principi del contenidor (llista, taula, etc.) on està posicionat el cursor del sistema|
|Mou més enllà del final del contenidor |coma |Mou més enllà del final del contenidor (llista, taula, etc.) on està posicionat el cursor del sistema|

<!-- KC:endInclude  -->
Algunes aplicacions web com Gmail, Twitter i Facebook usen lletres com a dreceres de teclat. 
Si vols usar-les mentre fas servir les tecles de cursor en el mode de navegació, pots deshabilitar temporalment les tecles de navegació per lletra de NVDA. 
<!-- KC:beginInclude  -->
Per activar i desactivar la navegació per lletra en el document actual, prem NVDA+Maj+espai. 
<!-- KC:endInclude -->

### Llista d'elements {#toc44}

La llista d'elements dóna accés a la llista d'enllaços, la llista d'encapçalaments o la llista de marques estructurals existents en el document. 
Per exemple, en els navegadors web, la llista d'enllaços poden ser enllaços, encapçalaments o regions.
Els botons d’opció et permeten canviar entre aquests tres tipus d’informació.
Al diàleg també hi ha un camp editable que et permet filtrar la llista per ajudar-te a buscar dins la pàgina un element en particular.
Un cop has triat un element, pots usar els botons del diàleg per moure't o activar l'element triat.
<!-- KC:beginInclude -->

| Nom |Tecla |Descripció|
|---|---|---|
|Llista d'elements en mode de navegació |NVDA+f7 |Mostra els diferents tipus d'elements existents en el document actual|

<!-- KC:endInclude -->

### Objectes incrustats {#toc45}

Les pàgines poden incloure contingut enriquit si usen tecnologies com Adobe Flash o Java de Sun, així com aplicacions i diàlegs.
Quan trobes aquest contingut en mode de navegació, NVDA informarà amb els missatges "objecte incrustat", "aplicació" o "diàleg", respectivament.
Pots prémer Retorn en aquests objectes per interaccionar amb ells.
Si l'aplicació és accessible, pots usar el tabulador per moure't amunt i avall i per interaccionar amb ella com en qualsevol aplicació.
NVDA disposa d'una ordre de teclat per tornar a la pàgina original, que conté l'objecte incrustat:
<!-- KC:beginInclude -->

| Nom |Tecla |Descripció|
|---|---|---|
|Mou al document contenidor en mode de navegació |NVDA+Ctrl+Barra espaiadora |Desplaça el focus fora de l'objecte incrustat actual i el mou al document que el conté|

<!-- KC:endInclude  -->

## Lectura de contingut matemàtic {#toc46}

Amb MathPlayer 4 de Design Science, NVDA pot llegir i navegar de forma interactiva el contingut matemàtic compatible.
Això requereix que MathPlayer 4 estigui instal.lat a l'ordinador.
MathPlayer es pot descarregar gratuïtament de: https://www.dessci.com/en/products/mathplayer/

NVDA és compatible amb els següents tipus de contingut matemàtic:

* MathML a Mozilla Firefox i a Microsoft Internet Explorer.
* Design Science MathType a Microsoft Word i PowerPoint. És necessari instal·lar MathType per a que funcioni. Amb la versió de prova és suficient.
* MathML a Adobe reader. Has de tenir en compte que això no és un estàndar oficial encara, i actualment no hi ha cap programari disponible públicament que pugui produir aquest contingut.

Mentre llegeix un document, NVDA verbalitzarà qualsevol contingut matemàtic compatible allà on aquest aparegui. 
Si uses un terminal braille, el contingut també es mostrarà a la línia braille.

### Navegació interactiva {#toc47}

Si treballes principalment amb veu, en molts casos, segurament voldràs examinar l'expressió matemàtica en segments més petits, en comptes de sentir-la tota de cop.

Si estàs en el mode de navegació, pots fer-ho movent el cursor sobre el contingut matemàtic i prement Retorn.

Si no estàs en el mode de navegació:

1. mou el cursor de revisió al contingut matemàtic.
Per defecte, el cursor de revisió segueix el cursor de sistema, per tant pots usar el cursor de sistema per moure't al contingut desitjat.
1. Llavors, activa la següent comanda: 

<!-- KC:beginInclude -->

| Nom |Tecla |Descripció|
|---|---|---|
|Interactúa amb contingut matemàtic |NVDA+Alt+m |Inicia la interacció amb el contingut matemàtic.|

<!-- KC:endInclude  -->

En aquest punt, pots usar les comandes de MathPlayer, com les tecles de fletxa, per explorar l'expressió.
Per exemple, pots moure't al llarg de l'expressió amb les tecles de fletxa esquerra i dreta i ampliar una porció de l'expressió, com una fracció, amb la fletxa avall.
Mira la documentació de MathPlayer per a més informació. 

Quan vulguis tornar al document, simplement prem la tecla Escapada.

## ordres de NVDA específiques d'aplicacions {#toc48}

NVDA disposa d'algunes ordres pròpies addicionals per a algunes aplicacions, per facilitar algunes tasques o per donar accés a funcionalitats que altrament no serien accessibles als usuaris de lectors de pantalla.

### Microsoft Word {#toc49}

NVDA pot anunciar automàticament els encapçalaments de files i columnes apropiades en navegar per les taules del Microsoft Word.
Això requereix, en primer lloc, que l'opció d'informar sobre els encapçalaments de la fila / columna de les taules en el diàleg de formatació de documents estigui activada.
En segon lloc, NVDA necessita conèixer quina fila o columna conté els encapçalaments de la taula.
Desprès de moure't a la primera cel·la en la columna o fila que conté els encapçalaments, utilitza una de les ordres següents:
<!-- KC:beginInclude -->

| Nom |Tecla |Descripció|
|---|---|---|
|Informa del comentari actual |NVDA+Alt+c |Informa del text del comentari que es troba a la posició del cursor del sistema.|
|Estableix com a encapçalament de columna |NVDA+Maj+c |Si prems aquestes tecles un cop, li estàs indicant a NVDA que aquesta és la primera cel·la d’encapçalament de la fila que conté encapçalaments de columna, i així ho hauria d'anunciar automàticament quan et mous entre les columnes sota aquesta fila. Si prems dos cops, deixa de ser l’encapçalament.|
|Estableix com a encapçalament de fila |NVDA+Maj+r |Si prems aquestes tecles un cop, li estàs indicant a NVDA que aquesta és la primera cel·la d’encapçalament de la columna que conté encapçalaments de fila, i així ho hauria d'anunciar automàticament quan et mous entre les files sota aquesta columna. Si prems dos cops, deixa de ser l’encapçalament.|

<!-- KC:endInclude -->

Aquestes configuracions es poden emmagatzemar en els documents com a marcadors, compatibles amb altres lectors de pantalla com ara el Jaws. Això vol dir que altres usuraris del lector de pantalla que obrin aquest llibre més endavant, tindran configurats automàticament els encapçalaments de les files i columnes.

#### Mode de navegació en el Microsoft Word {#toc50}

<!-- KC:beginInclude -->
Per activar i desactivar el mode de navegació al Microsoft Word, prem NVDA+barra espaiadora.
<!-- KC:endInclude -->
Per saber-ne més sobre el mode de navegació i la navegació ràpida, vegeu la [secció mode de navegació](#BrowseMode).

##### La llista d'elements {#toc51}

<!-- KC:beginInclude -->
Mentre estiguis en el mode de navegació en el Microsoft Word, pots accedir a la llista d'elements prement NVDA+f7.
<!-- KC:endInclude -->
La llista d'elements pot llistar encapçalaments, enllaços i anotacions (que inclouen comentaris i seguiment de canvis).

#### Informar dels comentaris {#toc52}

<!-- KC:beginInclude -->
Per informar sobre els comentaris en la posició actual del cursor, prem NVDA+alt+c.
<!-- KC:endInclude -->
Tots els comentaris del document incloent-hi altres seguiment de canvis també poden ser llistats en la llista d'elements del NVDA en seleccionar les anotacions com a tipus.

### Microsoft Excel {#toc53}
#### Lectura automàtica dels encapçalaments de columnes i files {#toc54}

NVDA pot anunciar automàticament els encapçalaments de les files i columnes apropiades al navegar pels fulls de l'Excel.
Això requereix, primer de tot, activar l'opció Informa dels encapçalaments de files / columnes del diàleg Formatació del document del NVDA.
En segon lloc, NVDA necessita conèixer quina fila o columna conté els encapçalaments.
Desprès de moure't a la primera cel·la en la columna o fila que conté els encapçalaments, utilitza una de les ordres següents:
<!-- KC:beginInclude -->

| Nom |Tecla |Descripció|
|---|---|---|
|Estableix com a encapçalament de columna |NVDA+Maj+c |Si prems aquestes tecles un cop, li estàs indicant a NVDA que aquesta és la primera cel·la d’encapçalament de la fila que conté encapçalaments de columna, i així ho hauria d'anunciar automàticament quan et mous entre les columnes sota aquesta fila. Si prems dos cops, deixa de ser l’encapçalament.|
|Estableix com a encapçalament de fila |NVDA+Maj+r |Si prems aquestes tecles un cop, li estàs indicant a NVDA que aquesta és la primera cel·la d’encapçalament de la columna que conté encapçalaments de fila, i així ho hauria d'anunciar automàticament quan et mous entre les files sota aquesta columna. Si prems dos cops, deixa de ser l’encapçalament.|
|Informa del comentari actual |NVDA+Alt+c |Informa del text del comentari de la cel·la actual, si és que n'hi ha.|
|Diàleg de llista d'elements |NVDA+f7 |Obre el Diàleg de llista d'elements i mostra gràfics, cel·les amb comentaris, cel·les amb fòrmules, o fulls.|

<!-- KC:endInclude -->
Aquesta configuració es pot desar al llibre com un nom de rangs definit, i és compatible amb altres lectors de pantalla com ara el Jaws. Això vol dir que altres usuraris del lector de pantalla que obrin aquest llibre més endavant, tindran configurats automàticament els encapçalaments de les files i columnes.

#### La llista d'elements {#toc55}

D'una manera similar al web, NVDA té una llista d'elements per al Microsoft Excel que et permet llistar i accedir a diferents tipus d'informació.
<!-- KC:beginInclude -->
Per accedir a la llista d'elements de l'Excel, prem NVDA+f7.
<!-- KC:endInclude -->
Els tipus d'informació disponibles a la llista d'elements són:

* Gràfic: la llista de tots els gràfics al llibre.
Seleccionant un gràfic i prement la tecla d'inserció o movent-te al botó fa que el gràfic rebi el focus per navegar i llegir amb les tecles de direcció.
* Comentari: la llista de totes les cel·les en el llibre que contenen comentaris.
L'adreça de la cel·la amb els comentaris es mostra per cadascuna de les cel·les.
Prémer la tecla d'inserció o movent-te al botó en un comentari llistat et mourà automàticament a aquesta cel·la. 
* Fórmula: la llista de totes les cel·les en el llibre que contenen una fórmula.
L'adreça de la cel·la amb la seva fórmula es mostra per cadascuna de les cel·les.
Prémer la tecla d'inserció o moure't al botó en una fórmula llistada et mourà directament a aquesta cel·la. 
* Full: la llista de tots els fulls en el llibre. 
Prémer f2 en un full llistat permet reanomenar-lo.
Prémer la tecla d'inserció o moure't al botó en el full llistat et permet moure't a aquest full.

#### Informar dels comentaris {#toc56}

<!-- KC:beginInclude -->
Per informar sobre els comentaris de la cel·la que té el focus, prem NVDA+alt+c.
<!-- KC:endInclude -->
Tots els comentaris del llibre també poden ser llistats a la llista d'elements del NVDA.

#### Lectura de les cel·les protegides {#toc57}

Si un llibre està protegit, no serà possible moure el focus a les cel·les bloquejades per a l'edició.
<!-- KC:beginInclude -->
Per poder moure't a cel·les bloquejades, canvia al mode de navegació prement NVDA+Barra espaiadora, i desprès utilitza les ordres de moviments estàndards de l'Excel com ara les fletxes de direcció, per moure't al voltant de totes les cel·les del full de càlcul actual.
<!-- KC:endInclude -->

### Microsoft PowerPoint {#toc58}

<!-- KC:beginInclude -->

| Nom |Tecla |Descripció|
|---|---|---|
|Notes de l'orador/Presentació |Ctrl+Maj+s |En mode presentació de diapositives, aquesta ordre saltarà entre les notes de l'orador d'una diapositiva i el contingut de la diapositiva. Això afecta només a allò que llegeix NVDA, no al que es mostra en pantalla.|

<!-- KC:endInclude -->

### foobar2000 {#toc59}

<!-- KC:beginInclude -->

| Nom |Tecla |Descripció|
|---|---|---|
|Informa del temps restant |Ctrl+Maj+r |Informa del temps restant de la pista que està sonant actualment, si és que n'hi ha.|

<!-- KC:endInclude -->

Atenció: La drecera de teclat per informar del temps restant només funciona per a la cadena de format estàndard a la línia d'estat de foobar's.

### Miranda IM {#toc60}

<!-- KC:beginInclude -->

| Nom |Tecla |Descripció|
|---|---|---|
|Informa del missatge recent |NVDA+Ctrl+1-4 |Informa d'un dels missatges recents, segons el número premut; per exemple NVDA+control+2 llegeix el segon missatge més recent.|

<!-- KC:endInclude -->

### Poedit {#toc61}

<!-- KC:beginInclude -->

| Nom |Tecla |Descripció|
|---|---|---|
|Informa de la finestra de comentaris |Ctrl+Maj+c |Informa dels comentaris existents a la finestra de comentaris.|
|Informa de notes per als traductors |Ctrl+Maj+a |Informa de totes les notes per als traductors.|

<!-- KC:endInclude -->

### Skype {#toc62}

<!-- KC:beginInclude -->
Mentre converses:

| Nom |Tecla |Descripció|
|---|---|---|
|Revisa el missatge |NVDA+control+1-0 |Mou el cursor de revisió a un missatge recent i n'informa, segons el número indicat; per exemple NVDA+control+2 llegeix el segon missatge més recent.|

<!-- KC:endInclude -->

## Configuració de NVDA {#toc63}
### Preferències {#toc64}

<!-- KC:settingsSection: || Nom | Tecla en teclat de sobretaula | Tecla en teclat de portàtil | Descripció | -->
La majoria d'opcions de NVDA es poden canviar des dels quadres de diàleg que es troben al submenú Preferències del menú NVDA.
A tots els quadres de diàleg de configuració de NVDA, prem el botó D'acord per acceptar els canvis que hagis fet.
Per cancel·lar els canvis, prem el botó Cancel·la o la tecla d'escapada.
Algunes configuracions també es poden canviar amb tecles de drecera, les més rellevants es llisten a continuació. 

Tingues en compte que per defecte, no tots els diàlegs de preferències poden ser accedits amb gestos d'entrada (comandes de teclat, gestos de toc, etc.).
Si vols accedir a diàlegs que encara no tenen dreceres de teclat, usa el [Diàleg de gestos d'entrada](#InputGestures) per assignar-los gestos personalitzats.

#### Configuració general (NVDA+Ctrl+g) {#toc65}

El quadre de diàleg de configuració general es troba al menú de Preferències.
Conté les següents opcions:

##### Idioma {#toc66}

Quadre combinat que et permet escollir l'idioma de la interfície d'usuari de NVDA i els missatges que s'hi mostren.
Hi ha molts idiomes, però l'opció predeterminada és "Valor predeterminat de l'usuari, Windows".
Aquesta opció indica a NVDA que usi l'idioma especificat a Windows.

Tingues en compte que cal reiniciar NVDA quan es canvia l'idioma.
NVDA et preguntarà si vols reiniciar si has canviat l'idioma.
Prem D'acord, i NVDA es reiniciarà.

##### Desa la configuració en sortir {#toc67}

Aquesta opció és una casella de selecció, que quan està activada, indica a NVDA que ha de desar automàticament la configuració en sortir de NVDA.

##### Mostra les opcions de sortida quan surts de NVDA {#toc68}

Aquesta opció és una casella de selecció que et permet triar si vols que aparegui un diàleg cada cop que surtis de NVDA que et preguntarà quina acció vols fer.
Si l'opció està activada quan provis de sortir de NVDA t'apareixerà un diàleg en què se'l preguntarà si vols sortir, reiniciar o reiniciar sense extensions.
Si l'opció està desactivada, NVDA sortirà immediatament.

##### Emet un so en entrar o sortir de NVDA {#toc69}

Aquesta opció és una casella de selecció, que quan està activada, indica a NVDA que emeti un so en començar o en sortir.

##### Nivell de registre {#toc70}

Aquesta opció és un quadre combinat que et permet escollir quanta informació registrarà NVDA mentre s'executa.
En general, els usuaris no haurien de tocar aquesta opció ja que no es registra gaire informació.
De totes maneres, si vols crear un informe d'errors, pot ser una opció útil.

##### Inicia automàticament NVDA després d’iniciar la sessió a Windows {#toc71}

Si aquesta opció està activada, s'iniciarà automàticament NVDA tan aviat com entris a Windows.
Aquesta opció només està disponible a la versió instal·lada de NVDA.

##### Utilitza NVDA a la pantalla d’inici de sessió de Windows (calen privilegis d'administrador) {#toc72}

Si entres a Windows amb usuari i contrasenya, en activar aquesta opció NVDA s'iniciarà automàticament a l'inici de sessió de Windows.
Aquesta opció només està disponible a la versió instal·lada de NVDA.

##### Utilitza la configuració desada a la pantalla d'inici de sessió i a altres pantalles de seguretat {#toc73}

Prement aquest botó es copia la configuració d'usuari desada al directori de configuració de sistema de NVDA, per tal que NVDA la faci servir en executar-se a l'inici de sessió de Windows, Control de comptes d'usuari (UAC) i altres pantalles de seguretat de Windows.
Per assegurar que tota la configuració es transfereix, assegura't primer de desar la teva configuració amb Ctrl+NVDA+c o desa la configuració des del menú NVDA.
Aquesta opció només està disponible a la versió instal·lada de NVDA.

##### Comprova automàticament si hi ha actualitzacions per a NVDA {#toc74}

Si aquesta opció esta activada, NVDA buscarà automàticament versions actualitzades de NVDA i t'informarà si hi ha una actualització disponible. 
També pots buscar actualitzacions manualment, seleccionant Cerca actualitzacions a l'opció Ajuda del menú NVDA.

#### Selecció del sintetitzador (NVDA+Ctrl+s) {#toc75}

El diàleg Sintetitzador, que es troba a "Sintetitzador..." al menú de Preferències, et permet triar el sintetitzador que NVDA usarà per a convertir el text a veu.
Un cop has escollit el sintetitzador, pots prémer D'acord i NVDA carregarà el sintetitzador escollit.
Si es produeix un error en carregar el sintetitzador, NVDA t'ho notificarà amb un missatge, i seguirà usant el sintetitzador anterior.

##### Sintetitzador {#toc76}

Aquesta opció et permet escollir el sintetitzador que vols que NVDA faci servir.

Per obtenir el llistat dels sintetitzadors compatibles amb NVDA, revisa la secció [Sintetitzadors de veu compatibles](#SupportedSpeechSynths).

Un element especial que sempre apareixerà en aquesta llista és "Sense veu", que et permet usar NVDA sense sortida de veu.
Aquesta opció pot ser útil a un usuari que vol usar NVDA únicament amb braille, o potser als desenvolupadors amb visió que només volen usar el Visor de veu.

##### Dispositiu de sortida {#toc77}

Aquesta opció et permet escollir la tarja de so amb la qual parlarà el sintetitzador escollit.

#### Configuració de veu (NVDA+Ctrl+v) {#VoiceSettings}

El diàleg Configuració de veu, que es troba al menú Preferències, conté opcions que et permeten canviar el so de la parla. 
Per conèixer altres vies ràpides de controlar els paràmetres de la veu des de qualsevol punt del programa mentre aquest s'està executant, revisa la secció [Configuració del sintetitzador](#SynthSettingsRing).

El quadre de diàleg Configuració de veu inclou les següents opcions:

##### Veu {#toc79}

La primera opció que trobes en aquest diàleg és un quadre combinat on es llisten totes les veus instal·lades del sintetitzador actual.
Pots usar les tecles de fletxa per escoltar les diferents opcions.
Les fletxes Amunt i Esquerra et desplacen amunt de la llista, mentre que les fletxes Avall i Dreta et desplacen cap avall de la llista.

##### Variant {#toc80}

Si uses el sintetitzador eSpeak que ve incorporat a NVDA, aquesta opció és un quadre combinat que et permet seleccionar amb quin Variant ha de parlar el sintetitzador.
Els variants d'eSpeak són com veus, ja que ofereixen petites diferències en els atributs de la veu de eSpeak.
Alguns variants sonaran com una veu masculina, altres com una veu femenina, i altres fins i tot com una granota.

##### Velocitat {#toc81}

Aquesta opció et permet canviar la velocitat de la veu.
Hi ha un control lliscant que va de 0 a 100, essent 0 la velocitat més lenta, i 100 la més ràpida.

##### To {#toc82}

Aquesta opció et permet canviar el to de la veu.
Hi ha un control lliscant que va de 0 a 100, essent 0 el to més baix, i 100 el més Alt.

##### Volum {#toc83}

Aquesta opció és un control lliscant que va de 0 a 100, essent 0 el volum més baix i 100 el més Alt.

##### Inflexió {#toc84}

Aquesta opció és un control lliscant que et permet triar amb quanta inflexió (pujades i baixades de to) parlarà el sintetitzador. (L'únic sintetitzador que ofereix aquesta opció actualment és eSpeak.)

##### Canvi d'idioma automàtic {#toc85}

Aquesta casella de selecció et permet triar si vols que NVDA canviï  l'idioma de síntesi de veu automàticament, quan el text llegit tingui indicació d'idioma.
Per defecte aquesta opció està activada.
Actualment, eSpeak és l'únic sintetitzador que ofereix el canvi automàtic d'idioma.

##### Canvi de dialecte automàtic {#toc86}

Aquesta casella de selecció et permet triar si vols que NVDA faci canvis de dialecte, en comptes de canvis d'idioma.
Per exemple, si estàs llegint amb una veu d'anglès d'Estats Units però el document indica que un text està escrit en anglès britànic, el sintetitzador canviarà l'accent si aquesta opció està activada.
Per defecte aquesta opció està desactivada.

<!-- KC:setting -->

##### Nivell de puntuació i símbols {#toc87}

Tecla: NVDA+p

Aquesta opció et permet escollir quanta puntuació i quants símbols es verbalitzaran com a paraules.
Per exemple, si està configurat com a tots, tots els símbols es verbalitzaran com a paraules.
Aquesta opció afectarà a tots els sintetitzadors, no només al sintetitzador actiu actualment.

##### Confia en l'idioma de la veu per processar símbols i caràcters {#toc88}

Aquesta opció, activada per defecte, indica a NVDA si l'idioma de la veu és fiable quan es processen símbols i caràcters.
Si trobes que NVDA llegeix la puntuació en l'idioma incorrecte en un sintetitzador o veu en particular, potser desitges desactivar aquesta opció i, per contra, forçar NVDA a usar la seva configuració general d'idioma. 

##### Percentatge de canvi de to a les majúscules {#toc89}

Aquest camp d'edició et permet indicar quant vols que canviï el to de la veu quan pronunciï una majúscula.
Aquest valor és un percentatge, un valor negatiu baixa el to i un valor positiu el puja.
Si no vols canvis de to indica un valor de 0.

##### Digues "Maj" abans de les majúscules {#toc90}

Quan aquesta casella de selecció està seleccionada, indica a NVDA que ha de dir "Maj" abans d'una lletra majúscula si aquesta s'està verbalitzant com a lletra individual, com per exemple en lletrejar.
Normalment, NVDA puja una miqueta el to per a les lletres majúscules, però alguns sintetitzadors no ho poden fer bé, i per això aquesta opció podria ser útil.

##### Emet un xiulet per les majúscules {#toc91}

Si aquesta casella de verificació està seleccionada, NVDA emetrà un petit xiulet cada cop que trobi una lletra majúscula.
Aquesta opció, com l'opció "Digues Maj abans de les majúscules", és útil per a sintetitzadors que no poden canviar el to a les lletres majúscules.

##### Utilitza la funcionalitat de lletrejar si s'admet l'opció {#VoiceSpellingFunctionality}

Algunes paraules estan formades per un únic caràcter, però sonen diferent si el caràcter es pronuncia com a caràcter individual (lletrejant) o com a paraula.
Per exemple, en anglès, "a" és alhora una lletra i una paraula, i es pronuncia diferent en cada cas.
Aquesta opció permet que el sintetitzador diferenciï aquests casos, sempre i quan el sintetitzador ho permeti.
La majoria de sintetitzadors ho permeten.

Aquesta opció generalment estarà activa.
De totes maneres, alguns sintetitzadors de l'API de síntesi de veu de Microsoft, no la implementen correctament i funcionen de manera estranya quan està activada.
Si tens problemes amb la pronúncia de caràcters individuals, prova a desactivar aquesta opció.

#### Configuració del sintetitzador {#SynthSettingsRing}

Si vols canviar ràpidament la configuració de veu sense anar al diàleg Configuració de veu, hi ha algunes ordres de teclat que et permeten moure't entre les configuracions de veu més habituals des de qualsevol punt del programa mentre aquest s'està executant:
<!-- KC:beginInclude -->

| Nom |Tecla en teclat de sobretaula |Tecla en teclat de portàtil |Descripció|
|---|---|---|---|
|Mou a la següent opció de configuració del sintetitzador |NVDA+Ctrl+fletxa dreta |NVDA+Maj+Ctrl+fletxa dreta |Et mou a la següent opció de configuració de veu disponible, tornant a la primera si et trobes a la darrera|
|Mou a l'anterior opció de configuració del sintetitzador |NVDA+Ctrl+fletxa esquerra |NVDA+Maj+Ctrl+fletxa esquerra |Et mou a l'anterior opció de configuració de veu disponible, tornant a la darrera si et trobes a la primera|
|Incrementa el valor de l'opció de configuració del sintetitzador actual |NVDA+Ctrl+fletxa amunt |NVDA+Maj+Ctrl+fletxa amunt |Incrementa el valor de l'opció de configuració en la qual et trobes, per exemple puja la velocitat, escull la següent veu o puja el volum|
|Redueix el valor de l'opció de configuració del sintetitzador actual |NVDA+Ctrl+fletxa avall |NVDA+Maj+Ctrl+fletxa avall |Redueix el valor de l'opció de configuració on et trobes, per exemple baixa la velocitat, escull la veu anterior, o baixa el volum|

<!-- KC:endInclude -->

#### Configuració de braille {#toc94}

El diàleg Configuració de braille es crida des del menú Preferències, a l'opció Configuració de braille.

##### Línia braille {#toc95}

La primera opció que et trobaràs al diàleg Configuració de braille és un quadre combinat que diu "línia braille".
Segons els controladors de línies braille disponibles en el teu sistema, se t'oferiran diverses opcions.
Mou-te per les opcions amb les tecles de fletxa.

L'opció "Sense braille" significa que no usaràs braille.

Per obtenir més informació sobre les línies braille compatibles, consulta la secció [Línies braille compatibles](#SupportedBrailleDisplays).

##### Port {#toc96}

Aquesta opció, si està disponible, et permet escollir quin port o quin tipus de connexió s'usarà per comunicar-se amb la línia braille seleccionada.
L'opció és un quadre combinat que conté les diferents vies de connexió de la teva línia braille.

Per defecte, NVDA fa servir detecció automàtica de port, la qual cosa vol dir que la connexió amb el dispositiu braille s'establirà automàticament amb una cerca dels dispositius USB o Bluetooth connectats al sistema.
Tot i així, per algunes línies braille, és possible que puguis seleccionar explícitament quin port cal usar.
Algunes opcions habituals són "Automàtic" (que indica a NVDA que ha de fer servir el procés automàtic de selecció de port), "USB", "Bluetooth" o altres ports de comunicació sèrie si són compatibles amb la teva línia braille.

Aquesta opció no estarà disponible si la teva línia braille només és compatible amb detecció automàtica de port.

Per conèixer més detalls dels tipus de comunicació compatibles o dels ports disponibles pots consultar la documentació específica de la teva línia braille a la secció [Línies braille compatibles](#SupportedBrailleDisplays).

##### Taula de sortida {#toc97}

La següent opció que es presenta en aquest diàleg és el quadre combinat de codis braille de sortida.
En aquest quadre combinat, hi trobaràs codis braille per a diferents idiomes, normatives i nivells braille.
El codi triat s'usarà per traduir el text a braille i enviar-lo a la teva línia braille.
Pots moure't entre els diferents conjunts de codis braille de la llista amb les tecles de fletxa.

##### Taula d'entrada {#toc98}

Complementària a l'opció prèvia, la següent opció que trobaràs és el quadre combinat de codis braille d'entrada.
El codi triat s'usarà per traduir a text el braille introduït al teclat Perkins del terminal braille.
Actualment NVDA només és compatible amb l'entrada de braille d'ordinador, i per tant només es mostraran conjunts de codis braille de 8 punts.
Pots moure't entre els diferents conjunts de codis braille de la llista amb les tecles de fletxa.

Tingues en compte que aquesta opció només és útil si la teva línia braille té un teclat de tipus Perkins i el controlador de la línia braille admet aquesta funció.
Si NVDA no és compatible amb l'entrada de braille des d'una línia braille que té teclat, això es farà constar a la secció [Línies braille compatibles](#SupportedBrailleDisplays).

##### Expandeix a braille d'ordinador la paraula sota el cursor {#toc99}

Aquesta opció permet que la paraula sota el cursor es mostri en braille d'ordinador no contret.

##### Freqüència de parpelleig del cursor {#toc100}

Aquesta opció és un camp numèric que et permet canviar la freqüència de parpelleig del cursor en mil·lisegons.

##### Temps d'espera del missatge (segons) {#toc101}

Aquesta opció és un camp numèric que et permet controlar quant de temps es mostraran els missatges a la línia braille.
Si especifiques 0 desactives els missatges completament.

<!-- KC:setting -->

##### Seguiment de braille {#BrailleTether}

Tecla: NVDA+Ctrl+t

Aquesta opció et permet escollir si la línia braille seguirà el focus de sistema o bé l'objecte de navegació/cursor de revisió.

##### Llegeix per paràgrafs {#toc103}

Si aquesta opció està activada, el codi braille es mostrarà per paràgrafs en comptes de per línies.
Les ordres de línia anterior i posterior, es mouran també per paràgrafs.
Això significa que no caldrà desplaçar el terminal braille al final de cada línia fins i tot si al terminal braille hi cap més text.
Això permet una lectura més fluida de textos llargs.
Aquesta opció, per defecte, està desactivada. 

##### Evita tallar paraules quan sigui possible {#toc104}

Si aquesta opció està activada, una paraula que és massa llarga per caber al final de la línia braille no es tallarà.
Sinó que, hi haurà alguns espais blancs al final de la línia.
Quan desplacis la línia, podràs llegir la paraula sencera.
Això s'anomena a vegades "ajust de línia"
Tingues en compte que si la paraula és massa llarga per caber a la línia ella sola, la paraula s'haurà de tallar.

Si aquesta opció està desactivada, es mostrarà tantes lletres de la paraula com sigui possible, però la resta es tallarà.
Quan desplacis la línia, podràs llegir la resta de la paraula.

Activar aquesta funció permet una lectura més fluïda, però segurament també et requerirà que desplacis la línia més sovint.

#### Configuració de teclat (NVDA+Ctrl+k) {#toc105}

Aquest quadre de diàleg es troba al menú Preferències, a l'opció "Configuració de teclat...".
Conté les següents opcions:

##### Disposició de teclat {#toc106}

Aquest quadre combinat et permet escollir quina disposició de teclat vols que usi NVDA. Actualment, NVDA ofereix dues disposicions de teclat, sobretaula i portàtil.

##### Utilitza Bloq Maj com a tecla modificadora de NVDA {#toc107}

Si aquesta casella de selecció està activada, s'usarà la tecla Bloqueig de majúscules com a tecla modificadora de NVDA.

##### Utilitza la tecla d'inserció del teclat expandit com a tecla modificadora de NVDA {#toc108}

Si aquesta casella de selecció està activada, es podrà usar la tecla d'inserció del teclat expandit (es troba normalment sobre les tecles de fletxa, prop de les tecles d'Inici i Fi) com a tecla modificadora de NVDA.

##### Utilitza la tecla d'inserció del teclat numèric com a tecla modificadora de NVDA {#toc109}

Si aquesta casella de selecció està activada, es podrà usar la tecla d'inserció del teclat numèric com a tecla modificadora de NVDA.

Si no se selecciona cap tecla com a tecla NVDA no es podrà accedir a algunes ordres de NVDA.
Així doncs, el diàleg Configuració de teclat mostrarà un missatge d'error si no s'ha seleccionat cap tecla en el moment de prémer D'acord.
Un cop obviat el missatge d'error, hauràs de triar com a mínim una tecla per poder prémer D'acord i sortir correctament del diàleg.

<!-- KC:setting -->

##### Verbalitza els caràcters escrits {#toc110}

Tecla: NVDA+2

Quan aquesta opció està activada, NVDA anunciarà tots els caràcters que escriguis amb el teclat.

<!-- KC:setting -->

##### Verbalitza les paraules escrites {#toc111}

Tecla: NVDA+3

Quan aquesta opció està activada, NVDA anunciarà totes les paraules que escriguis en el teclat.

##### Interrupció de la veu per als caràcters escrits {#toc112}

Si aquesta opció està activada, la veu s'interromprà cada cop que escriguis un caràcter. Per defecte, aquesta opció està activada.

##### Interrupció de la veu per a la tecla de retorn {#toc113}

Si aquesta opció està activada, la veu s'interromprà cada cop que premis la tecla Retorn. Per defecte, aquesta opció està activada.

##### Permet la lectura superficial en el perfil Verbalitza-ho tot {#toc114}

Si aquesta opció està activada, algunes ordres de navegació (com Navegació ràpida en mode de navegació o moure's per línies o paràgrafs) no aturaran Verbalitza-ho tot, sinó que faran que Verbalitza-ho tot salti a la nova posició i continuï llegint.

##### Emet un xiulet en escriure lletres minúscules quan el Bloqueig de majúscules està activat {#toc115}

Quan aquesta opció està activada, se sentirà un xiulet d'avís si escrius amb la tecla Majúscules quan el Bloqueig de majúscules està actiu.
En general, quan s'escriuen lletres en majúscules amb el Bloqueig de majúscules activat és perquè no se sap que el Bloqueig de majúscules està actiu.
Així doncs, que NVDA t'avisi pot ser prou útil. 

<!-- KC:setting -->

##### Verbalitza les tecles d'ordre {#toc116}

Tecla: NVDA+4

Quan aquesta opció està activada, NVDA anunciarà totes les tecles escrites en el teclat que no corresponguin a lletres. Això inclou combinacions de tecles com Ctrl i una altra lletra.

##### Gestiona les tecles d'altres aplicacions {#toc117}

Aquesta opció permet a l'usuari controlar si NVDA ha de processar les tecles escrites per altres aplicacions com ara teclats de pantalla o programari de reconeixement de parla. 
Aquesta opció per defecte està activada, però alguns usuaris potser la voldran desactivar, per exemple els usuaris que escriuen vietnamita amb el programari d'escriptura Unikey, ja que provocaria una entrada incorrecta de caràcters.

#### Configuració del ratolí (NVDA+Ctrl+m) {#MouseSettings}

El diàleg Configuració del ratolí es troba al menú Preferències, a l'opció "Configuració del ratolí...".
Conté les següents opcions:

##### Anuncia els canvis en la forma del ratolí {#toc119}

Si aquesta casella de selecció està activada, NVDA anuncia la forma del punter de ratolí cada vegada que canvia.
El punter de ratolí a Windows canvia de forma per donar informació com, per exemple, que quelcom es pot editar, o que quelcom s'està carregant, etc.

<!-- KC:setting -->

##### Habilita el seguiment de ratolí {#toc120}

Tecla: NVDA+m

Quan està activat, NVDA anunciarà el text que es troba sota el punter del ratolí mentre el desplaces amunt i avall de la pantalla. Això et permet trobar coses a la pantalla amb el moviment del ratolí, en comptes de trobar-les a través de la navegació d'objectes.

##### Unitat de resolució de text {#toc121}

Si s'ha configurat NVDA perquè anunciï el text sota el ratolí mentre el mous, aquesta opció et permet escollir quant text es verbalitza cada cop.
Les opcions són una lletra, una paraula, una línia o un paràgraf.

##### Anuncia el rol quan el ratolí entri dins l'objecte {#toc122}

Si aquesta casella de selecció està activada, NVDA anunciarà el rol (tipus) d'objecte quan el ratolí entri en un objecte.

##### Emet les coordenades per àudio quan el ratolí es mou {#toc123}

Activar aquesta casella de selecció fa que NVDA emeti un xiulet quan el ratolí es mou, de tal manera que l'usuari pot deduir on es troba el ratolí respecte a les dimensions de la pantalla.
Com més amunt de la pantalla es trobi el ratolí, més agut sonarà el xiulet.
Com més a l'esquerra o a la dreta de la pantalla es trobi el ratolí, més allunyat a l'esquerra o a la dreta sonarà el so (sempre i quan l'usuari tingui altaveus estèreo o auriculars).

##### La brillantor controla el volum de l'àudio {#toc124}

Si la casella "Emet les coordenades per àudio quan el ratolí es mou" està activada, activar la casella de brillantor significa que el grau de brillantor de la pantalla sota el ratolí marcarà el volum de les coordenades per so.
Aquesta configuració, per defecte, no està activada.

#### Configuració del cursor de revisió {#toc125}

Es troba al menú Preferències a "Cursor de revisió...".
Aquest diàleg conté les següents opcions:

<!-- KC:setting -->

##### Segueix el focus del sistema {#toc126}

Tecla: NVDA+7

Quan aquesta opció està activada, si es canvia el focus, el cursor de revisió se situarà en el mateix objecte que el focus del sistema.

<!-- KC:setting -->

##### Segueix el cursor del sistema {#toc127}

Tecla: NVDA+6

Quan aquesta opció està activada, cada cop que el cursor de sistema es mou, es desplaçarà automàticament el cursor de revisió a la posició del cursor del sistema.

##### Segueix el cursor del ratolí {#toc128}

Quan aquesta opció està activada, el cursor de revisió seguirà els moviments del ratolí.

##### Mode de revisió simple {#toc129}

Quan aquesta opció està activada, NVDA filtrarà la jerarquia dels objectes que es poden navegar per excloure aquells objectes que no són d'interès per a l'usuari,  per exemple, filtrarà els objectes invisibles o els objectes que tenen una funció exclusivament de disposició.

#### Configuració de la presentació d'objectes (NVDA+Ctrl+o) {#toc130}

Es troba al menú Preferències de NVDA a l'opció "Presentació d'objectes...".
Aquest quadre de diàleg conté les opcions següents:

##### Informa dels indicadors de funció {#toc131}

Si aquesta casella de selecció està activada, NVDA anuncia els indicadors de funció que vagin apareixent.
Moltes finestres i controls mostren un breu missatge (o indicador de funció) quan hi passes per sobre amb el punter de ratolí, o a vegades quan hi mous el focus.

##### Informa dels indicadors de funció d'ajuda {#toc132}

Si aquesta casella de selecció està activada, indica a NVDA que ha d'informar dels indicadors de funció d'ajuda que vagin apareixent.
Els indicadors de funció d'ajuda són com els altres indicadors, però solen ser més llargs, i s'associen a esdeveniments del sistema com ara que el cable de xarxa s'ha desconnectat o potser per avisar-te sobre problemes de seguretat de Windows.

##### Informa de les tecles de drecera de l'objecte {#toc133}

Quan aquesta casella de selecció està activada, NVDA en informar de l'objecte o control informarà també de la tecla de drecera que té associada.
Per exemple el menú de fitxers en una barra de menús pot tenir associada la tecla de drecera Alt+f.

##### Informa de la posició de l'objecte {#toc134}

Aquesta opció et permet escollir si vols conèixer la posició d'un objecte (per exemple 1 de 4) quan t'hi desplaces amb el focus o amb la navegació d'objectes.

##### Endevina la informació de posició de l'objecte quan no estigui disponible {#toc135}

Si Informa de la posició de l'objecte està activada, aquesta altra opció permet que NVDA endevini la posició d'un objecte o control en particular quan la seva ubicació no està disponible per cap altra via.

Quan aquesta opció està activada, NVDA informarà de la posició de controls addicionals com ara menús o barres d'eines, però aquesta informació pot ser poc acurada.

##### Informa de les descripcions de l'objecte {#toc136}

Desactiva aquesta casella de selecció si no vols que quan s'informi d'un objecte se'n doni la descripció.

<!-- KC:setting -->

##### Sortida de la barra de progrés {#toc137}

Tecla: NVDA+u

Aquesta opció controla com t'informarà NVDA de les actualitzacions de la barra de progrés.

Té les opcions següents:

* Desactivada: Els canvis a la barra de progrés no es notificaran.
* Verbalitza: Aquesta opció indica a NVDA que ha de verbalitzar la barra de progrés en percentatges. Cada cop que la barra canvia, NVDA dirà el nou valor. 
* Emet un xiulet: Aquesta opció indica a NVDA d'emetre un xiulet cada cop que la barra de progrés canvia. El xiulet augmenta de volum a mesura que la barra de progrés s'acosta al final.
* Verbalitza i emet un xiulet: Aquesta opció indica a NVDA que ha de verbalitzar i xiular cada cop que la barra de progrés s'actualitza.

##### Informa de les barres de progrés en segon pla {#toc138}

Aquesta opció, quan està seleccionada, indica a NVDA que ha de seguir informant sobre una barra de progrés fins i tot si aquesta no és a primer pla. 
Si minimitzes o surts d'una finestra que conté una barra de progrés, NVDA en farà el seguiment, i et permetrà fer altres tasques mentre NVDA segueix la barra de progrés.

<!-- KC:setting -->

##### Informa dels canvis dinàmics del contingut {#toc139}

Tecla: NVDA+5

Commuta l'anunci de nou contingut en alguns objectes concrets com ara terminals o el control d'història en els programes de xat.

#### Configuració de la composició d'entrada {#toc140}

El diàleg Configuració de la composició d'entrada es troba al menú Preferències de NVDA.
Aquest diàleg et permet controlar com NVDA notifica l'entrada de caràcters asiàtics, amb mètodes d'entrada com per exemple IME o Text Service.
Tingues en compte que com que els mètodes d'entrada poden variar substancialment segons les funcions disponibles i segons com ofereixen la informació, segurament caldrà configurar aquestes opcions de forma diferent per a cada mètode d'entrada per gaudir d'una experiència d'escriptura eficient.

##### Informa automàticament de tots els candidats disponibles {#toc141}

Aquesta opció, que està activada per defecte, et permet escollir si cal informar automàticament de tots els candidats visibles quan apareix una llista de candidats o la seva pàgina canvia.
Tenir aquesta opció activada pels mètodes d'entrada pictogràfics com el xinès New ChangJie o el Boshiami és molt útil, ja que pots sentir automàticament tots els símbols i els seus codis i escollir-ne un directament.
De tota manera, per als mètodes d'entrada fonètics com el xinès New Phonetic, potser resulta més útil desactivar aquesta opció, ja que tots els símbols sonaran igual i hauràs d'usar les tecles de fletxa per desplaçar-te un per un pels elements de la llista i obtenir més informació de les descripcions de caràcter de cada candidat.

##### Anuncia el candidat seleccionat {#toc142}

Aquesta opció, que està activada per defecte, et permet escollir si NVDA hauria d'anunciar el candidat seleccionat quan apareix una llista de candidats o quan es canvia la selecció.
Per als mètodes d'entrada en què la selecció es pot canviar amb les tecles de fletxa (com el xinès New Phonetic) això és necessari, però per a alguns mètodes d'entrada potser és més eficient escriure amb aquesta opció desactivada.
Tingues en compte que fins i tot si aquesta opció està desactivada, el cursor de revisió romandrà situat en el candidat escollit, i et permetrà usar la navegació d'objectes o la revisió per llegir manualment aquest o altres candidats.

##### Inclou sempre la descripció curta dels caràcters en anunciar els candidats {#toc143}

Aquesta opció, que està activada per defecte, et permet escollir si NVDA hauria d'oferir una descripció breu de cada caràcter en un candidat, tant si està seleccionat com si es llegeix automàticament quan apareix la llista de candidats.
Tingues en compte que per a algunes llengües com el xinès, l'anunci de descripcions extra de caràcter per al candidat seleccionat no es veu afectat per aquesta opció.
Aquesta opció pot ser útil per als mètodes d'entrada de coreà i japonès.

##### Informa de canvis a la cadena de lectura {#toc144}

Alguns mètodes d'entrada com el xinès New Phonetic i el New ChangJie tenen una cadena de lectura (coneguda a vegades com a cadena de precomposició).
Amb aquesta opció pots escollir si NVDA ha d'anunciar els caràcters nous escrits en aquesta cadena de lectura.
Aquesta opció està activada per defecte.
Tingues en compte que alguns mètodes d'entrada més antics com el xinès ChangJie potser no usen la cadena de lectura per desar els caràcters de precomposició, sinó que fan servir directament la cadena de composició. Revisa la següent opció per configurar la informació de la cadena de composició.

##### Informa de canvis a la cadena de composició {#toc145}

Després que les dades de lectura o precomposició s'han combinat en un símbol pictogràfic vàlid, la majoria de mètodes d'entrada introdueixen aquest símbol en una cadena de composició com a magatzem temporal juntament amb altres símbols combinats, abans d'inserir-los finalment en el document.
Aquesta opció et permet escollir si NVDA ha d'informar de nous símbols a mesura que apareixen a la cadena de composició. 
Aquesta opció està activada per defecte.

#### Configuració del mode de navegació (NVDA+Ctrl+b) {#toc146}

El diàleg Configuració del mode de navegació es pot trobar al menú Preferències de NVDA, a l'opció "Mode de navegació...".

El diàleg inclou les següents opcions:

##### Nombre màxim de caràcters en una línia {#toc147}

Aquest camp estableix la llargada màxima de la línia en mode de navegació (en caràcters).

##### Nombre de línies per pàgina {#toc148}

Aquest camp estableix quantes línies et desplaçaràs prement Re Pàg o Av Pàg mentre et trobes en mode de navegació.

<!-- KC:setting -->

##### Utilitza la disposició de pantalla {#toc149}

Tecla: NVDA+v

Aquesta opció et permet especificar si en mode de navegació els enllaços o altres camps han de situar-se en una línia pròpia, o si s'han de mantenir dins el flux del text tal i com es mostra visualment. Si l'opció està activada, el contingut romandrà tal i com es mostra visualment, però si està desactivada, els camps s'ubicaran a la seva pròpia línia.

##### Verbalitza-ho tot automàticament quan es carrega una pàgina {#toc150}

Aquesta casella de selecció commuta la lectura automàtica d'una pàgina quan es carrega en mode de navegació.
Aquesta opció està activada per defecte.

##### Inclou les taules de disposició {#toc151}

Aquesta opció afecta a la manera en què NVDA tracta les taules purament de disposició.
Quan l'opció està activada, NVDA les tractarà com a taules normals, informant-ne segons la [Configuració de format del document](#DocumentFormattingSettings) i hi podrà anar amb les ordres de navegació ràpida.
Quan l'opció està desactivada, no se n'informarà ni es trobaran amb la navegació ràpida.
De totes maneres, el contingut de les taules sí que es tractarà com a text normal.
Aquesta opció està desactivada per defecte.

##### Configuració de la informació de camps com ara enllaços i encapçalaments {#toc152}

Revisa les opcions del diàleg [Configuració de format del document](#DocumentFormattingSettings) per configurar de quins camps, com enllaços, encapçalaments o taules, s'informa durant la navegació.

##### Mode de focus automàtic per als canvis de focus {#toc153}

Aquesta opció permet cridar el mode de focus quan canvia el focus.
Per exemple, en una pàgina web, si prems Tab i vas a parar a un formulari, si aquesta opció està seleccionada, es cridarà automàticament el mode de focus.

##### Mode de focus automàtic per al moviment del cursor del sistema {#toc154}

Aquesta opció, quan està activada, permet a NVDA d'entrar o abandonar el mode de focus mentre s'usen les tecles de fletxa.
Per exemple, si et desplaces amb la fletxa avall en una pàgina web i vas a parar a un quadre d'edició, NVDA automàticament et posarà en mode de focus. Si amb les fletxes et mous fora del quadre d'edició, NVDA et tornarà al mode de navegació.

##### Indicació audible del mode de focus i de navegació {#toc155}

Si aquesta opció està activada, NVDA emetrà sons especials quan canviï entre el mode de navegació i el mode de focus, en comptes de verbalitzar el canvi.

#### Impedeix que els gestos que no són instruccions arribin al document {#toc156}

Aquesta opció està activada per defecte i et permet triar si els gestos (com premer les tecles) que no estiguin associats a una ordre NVDA i que no es consideren ordres de teclat en general, no arribin al document on actualment tens el focus. 
Com a exemple, si aquesta opció està activada i prems la lletra j, s'impedirà que arribi al document ja que no és una ordre de navegació ràpida ni, segurament, és una ordre de l'aplicació.

#### Configuració del format del document (NVDA+Ctrl+d) {#DocumentFormattingSettings}

Aquest quadre de diàleg es troba al menú Preferències de NVDA, a l'opció "Formatació de documents"

La majoria de caselles de selecció en aquest diàleg serveixen per configurar el tipus de format sobre el qual vols rebre informació a mesura que mous el cursor amunt i avall dels documents.
Per exemple, si selecciones la casella de selecció del nom del tipus de lletra, cada cop que et desplacis a un text amb un tipus de lletra diferent, NVDA anunciarà el nom del tipus de lletra.

Pots configurar si vols que s'informi de:

* Nom del tipus de lletra
* Cos de la lletra
* Atributs de la lletra
* Alineació
* Colors
* Revisions de l'editor
* Èmfasi
* Estil
* Errors ortogràfics
* Números de pàgina
* Número de la línia
* Sagnat de la línia
* Sagnat del paràgraf (per exemple sagnat francès, sagnat de la primera línia)
* Taules
* Capçaleres de fila/columna en una taula
* Coordenades de la cel·la de taula
* Enllaços
* Encapçalaments
* Llistes
* Blocs de cites
* Regions
* Marcs 
* Quan algun objecte és clicable

Per activar aquestes configuracions des de qualsevol punt, si-et-plau assigna'ls gestos amb el [Diàleg de gestos d'entrada](#InputGestures).

##### Anuncia els canvis de format després del cursor {#toc158}

Si està activada, aquesta configuració indica a NVDA que ha de detectar tots els canvis de format en una línia a mesura que la verbalitza, encara que en fer-ho baixi el rendiment de NVDA.

De forma predeterminada, NVDA detectarà el format a la posició del cursor del sistema/cursor de revisió, i en alguns casos pot detectar el format de la resta de la línia, sempre i quan això no baixi el seu rendiment.

Activa aquesta opció si estàs corregint documents en aplicacions com Microsoft Word, en què el format és important.

#### Diccionaris de veu {#toc159}

El menú de diccionaris de veu (que es troba al menú Preferències de NVDA) conté diàlegs que et permeten gestionar com pronunciarà NVDA algunes paraules o frases concretes.
Actualment, existeixen tres tipus de diccionaris de veu.
Són:

* Diccionari per defecte: les regles d'aquest diccionari afecten tota la pronúncia de NVDA
* Diccionari de veus: les regles d'aquest diccionari afecten la pronúncia de la veu del sintetitzador en ús.
* Diccionari temporal: les regles d'aquest diccionari afecten tota la pronúncia de NVDA, però només durant la sessió actual. Aquestes regles són temporals i es perdran si es reinicia NVDA.

Cal que assignis gestos personalitzats amb el [Diàleg de gestos d'entrada](#Inputgestures) si vols obrir aquests diàlegs de diccionaris des de qualsevol punt.

Tots els diàlegs de diccionari contenen una llista de regles que s'usaran per processar la veu.
Aquest diàleg, a més, conté els botons Afegeix, Edita o Elimina.

Per afegir una nova regla al diccionari, prem el botó Afegeix, i omple els camps al quadre de diàleg que t'apareix i prem D'acord.
Veuràs la teva nova regla a la llista de regles.
De totes maneres, per assegurar-te que la teva regla s'ha desat realment, assegura't de prémer D'acord quan surts del diàleg del diccionari un cop has acabat d'afegir/editar regles.

Les regles dels diccionaris de pronúncia de NVDA et permeten canviar una cadena de caràcters per una altra.
Per exemple, si t'interessa que NVDA digui granota cada cop que se suposa que ha de dir ocell.
Al diàleg Afegeix regla, la manera més fàcil de fer-ho és escriure la paraula ocell al camp Patró, i la paraula granota al camp Reemplaça.
Potser també vols escriure una descripció de la regla en el camp Comentari (alguna cosa com: canvia ocell per granota).

Els diccionaris de pronúncia de NVDA permeten fer moltes més coses que simples canvis de paraula.
El diàleg Afegeix regla conté també una casella de selecció per indicar si vols que la regla tingui en compte les majúscules (això vol dir que NVDA tindrà en compte si les lletres són majúscules o minúscules.
De forma predeterminada NVDA no en fa cas).

Finalment, un conjunt de botons d'opció et permet indicar a NVDA si el patró ha de coincidir amb qualsevol text, només amb paraules completes o si s'ha de tractar com a "expressió regular".
Si indiques que el patró ha de coincidir només amb paraules completes vol dir que el text no es reemplaçarà si el patró es dóna en una paraula més llarga; per ex. si un caràcter (no numèric ni guió de subratllat ni espai) ve abans o després immediatament del patró. 
Així, en l'anterior exemple de reemplaçar la paraula "ocell" per la paraula "granota", quan s'indica com a paraula sencera, no farà el canvi a les paraules "ocells" o "ocellaire".

Una expressió regular és un patró que conté uns símbols especials que et permeten, per exemple, identificar un o més caràcters a la vegada, identificar només números, o només lletres, entre d'altres.
En aquesta guia d'usuari no es tracten les expressions regulars, però al web pots trobar molts programes d'aprenentatge que et poden oferir més informació.

#### Pronúncia de la puntuació i dels símbols {#SymbolPronunciation}

Aquest diàleg et permet canviar la manera en què es pronuncien la puntuació i altres símbols, així com el nivell de verbalització dels símbols. 

L'idioma del qual s'està editant la pronunciació del símbols es mostrarà en el títol del diàleg.
Tingues en compte que el diàleg respecta l'opció "Confia en l'idioma de la veu per processar els símbols i els caràcters" del [Diàleg de configuració de veus](#VoiceSettings); és a dir, usa l'idioma de la veu abans que el llenguatge global configurat per NVDA quan aquesta 

Per canviar un símbol, primer l'has de seleccionar a la llista de símbols.

* El camp Reemplaçament et permet canviar el text que es verbalitzarà en comptes del símbol.
* Si uses el camp Nivell, pots ajustar el nivell més baix en el qual el símbol es verbalitzarà.
* The Send actual symbol to synthesizer field specifies when the symbol itself (en contrast amb el seu reemplaçament) hauria de ser enviat al sintetitzador.
Això és útil si el símbol provoca la pausa del sintetitzador o canvia la inflexió de la veu.
Per exemple, una coma provoca la pausa del sintetitzador.
Hi ha tres opcions:
 * mai: mai envia el símbol actual al sintetitzador.
 * sempre: sempre envia el símbol actual al sintetitzador.
 * només per sota del nivell dels símbols: només envia el símbol actual si el nivell de veu del símbol configurat és més baix que el nivell establert per aquest símbol.
 Per exemple, pots utilitzar aquesta opció per a que un símbol tingui el seu reemplaçament verbalitzat als nivells més alts sense pausa, mentre que es continua indicant amb una pausa als nivells més baixos.
 -

Pots afegir nous símbols prement el botó Afegir.
En el diàleg que apareix, entra el símbol i prem el botó D'acord.
Llavors, canvia el reemplaçament i el nivell per al nou símbol tal i com ho faries per altres símbols.

Pots eliminar un símbol que has afegit prèviament, si prems el botó Eliminar.

Quan hagis acabat, prem el botó D'acord per desar els canvis fets o el botó Cancel·la per descartar-los.

+++ Gestos d'entrada +++
En aquest diàleg, pots personalitzar els gestos d'entrada (tecles en el teclat, botons a la línia braille, etc.) usats a les ordres de NVDA.

Només es mostren les ordres que són aplicables immediatament abans que el diàleg s'obri.
Per exemple, si vols personalitzar les ordres relacionades amb el mode de navegació, has d'obrir el diàleg Gestos d'entrada mentre et trobes en mode de navegació.

L'arbre d'aquest diàleg llista totes les ordres NVDA aplicables agrupades per categoria.
Pots filtrar les ordres introduint una o més paraules del nom de l'ordre, dins el Filtre amb la caixa d'edició.
Qualsevol gest associat amb una ordre es llista sota la ordre.

Per afegir un gest d'entrada a una ordre, selecciona l'ordre i prem el botó Afegeix.
Llavors, fes el gest d'entrada que hi vols associar; per exemple, prem una tecla del teclat o un botó de la línia braille.
Sovint, un gest es pot interpretar de diverses maneres.
Per exemple, si prems una tecla del teclat, potser vols que sigui específica de l'actual disposició de teclat (per ex. sobretaula o portàtil) o que sigui vàlida per tots els teclats.
En aquest cas, apareixerà un menú que et permetrà seleccionar l'opció desitjada.

Per dissociar un gest d'una ordre, selecciona el gest i prem el botó Elimina.

Quan hagis acabat de fer canvis, prem el botó D'acord per desar els canvis fets o el botó Cancel·la per descartar-los.

++ Desar i recuperar la configuració ++
De forma predeterminada, NVDA desarà automàticament la teva configuració quan surtis del programa.
De totes maneres, tingues en compte que aquesta opció es pot canviar a les opcions generals del menú Preferències.
Per desar la configuració manualment en qualsevol moment, escull l'opció Desa la configuració del menú NVDA.

Si mai comets un error amb la teva configuració i vols recuperar la configuració desada, escull l'element "Reverteix a la configuració desada" del menú NVDA.
També pots restablir la configuració a la configuració original de fàbrica si selecciones "Reinicialitza la configuració als valors per defecte", que també es troba al menú NVDA.

Les següents ordres de teclat també són útils:
<!-- KC:beginInclude -->

| Nom |Tecla en teclat de sobretaula |Tecla en teclat de portàtil |Descripció|
|---|---|---|---|
|Desa la configuració |NVDA+Ctrl+c |NVDA+Ctrl+c |Desa la teva configuració actual per tal que no es perdi quan surtis de NVDA|
|Refés la configuració |NVDA+Ctrl+r |NVDA+Ctrl+r |Si prems un cop recuperes la darrera configuració desada. Si prems tres cops recuperes la configuració de fàbrica.|

<!-- KC:endInclude -->

### Perfils de configuració {#toc161}

A vegades, et pot interessar disposar de diferents configuracions per situacions diferents.
Per exemple, pots voler tenir activada la informació del sagnat mentre edites, o la informació dels atributs de tipus de lletra mentre fas correccions.
Els perfils de configuració et permeten fer això.

Un perfil de configuració conté només aquelles configuracions que canvien mentre el perfil s'està editant.
La majoria de configuracions es poden canviar en els perfils de configuració excepte les del diàleg Configuració general, que afecten a tot NVDA.

Els perfils de configuració es poden activar manualment.
La seva activació també es pot disparar automàticament per accions com canviar a una aplicació concreta.

#### Gestió bàsica {#toc162}

Per gestionar els perfils de configuració has de seleccionar "Perfils de configuració" al menú NVDA.
També pots fer-ho usant l'ordre de teclat:
<!-- KC:beginInclude -->

* NVDA+Ctrl+p: Mostra el diàleg Perfils de configuració.

<!-- KC:endInclude -->

El primer control en aquest diàleg és la llista de perfils disponibles, d'entre els quals pots triar-ne un.
Quan obres aquest diàleg, apareix seleccionat el perfil amb el qual estàs editant actualment.
Es mostra informació addicional dels perfils actius, que indica si s'han activat manualment o automàticament i/o si s'estan editant.

Per reanomenar o eliminar un perfil, prem els botons Reanomena o Elimina, respectivament.

Prem el botó Tanca per tancar aquest diàleg.

#### Creació d'un perfil {#toc163}

Per crear un perfil, prem el botó Nou.

En el diàleg Nou perfil, pots introduir un nom per al perfil.
També pots seleccionar com usar aquest perfil.
Si només vols usar aquest perfil manualment, selecciona Activació manual, que és l'opció predeterminada.
Altrament, selecciona quina acció desencadenarà l'activació manual del perfil.
Per conveniència, si encara no has entrat un nom per al perfil, quan seleccionis el desencadenador s'omplirà el camp de nom.
Més endavant pots trobar més [informació sobre els desencadenadors](#ConfigProfileTriggers).

Si prems D'acord el perfil es crearà i es tancarà el diàleg Perfils de configuració per tal que el puguis editar.

#### Activació manual {#ConfigProfileManual}

Pots activar manualment un perfil si selecciones un perfil i prems el botó d'Activació manual.
Un cop activat, altres perfils es poden activar per desencadenadors, però les configuracions del perfil activat manualment tindran preferència.
Per exemple, si es dispara un perfil a l'aplicació en ús que té activada la informació d'enllaços, però aquesta informació està desactivada en el perfil activat manualment, no s'informarà dels enllaços.
Tot i així, si has canviat la veu en el perfil activat automàticament però no l'has canviat en el perfil activat manualment, s'usarà la veu del perfil activat automàticament.
Si canvies la configuració, els canvis es desaran en el perfil activat manualment.
Per desactivar un perfil activat manualment, selecciona'l al diàleg Perfils de configuració i prem el botó Desactivació manual.

#### Desencadenadors {#ConfigProfileTriggers}

Si prems el botó Desencadenadors al diàleg Perfils de configuració podràs canviar els perfils que es dispararan automàticament per diversos desencadenadors.

La llista de desencadenadors mostra els desencadenadors disponibles, que són els següents:

* Aplicació en ús: Es dispara quan canvies a l'aplicació en ús.
* Verbalitza-ho tot: Es dispara quan llegeixes amb l'ordre Verbalitza-ho tot.

Per canviar el perfil associat a un desencadenador, selecciona el desencadenador i llavors selecciona el perfil desitjat de la llista de perfils.
Pots seleccionar (configuració normal) si no vols que s'usi cap perfil.

Prem el botó Tanca per tornar al diàleg Perfils de configuració.

#### Edició d'un perfil {#toc166}

Quan has activat manualment un perfil, si canvies la configuració, els canvis es desaran en aquest perfil.
Altrament, els canvis de configuració es desaran en el darrer perfil activat.
Per exemple, si has associat un perfil amb l'aplicació Bloc de notes i obres aquesta aplicació, qualsevol canvi de configuració es desarà en aquest perfil.
Finalment, si no hi ha cap perfil activat manualment o automàtica, qualsevol canvi de configuració es desarà a la configuració normal.

Per editar el perfil associat a Verbalitza-ho tot, has d'[activar manualment](#ConfigProfileManual) aquest perfil.

#### Desactiva temporalment tots els desencadenadors {#toc167}

A vegades, és útil desactivar temporalment tots els desencadenadors.
Per exemple, pots voler editar el perfil activat manualment o la configuració normal, sense que hi interfereixin perfils disparats automàticament.
Pots desactivar-los seleccionant la casella de selecció Desactiva temporalment tots els desencadenadors al diàleg Perfils de configuració.

### Ubicació dels fitxers de configuració {#toc168}

Les versions portables de NVDA desen tota la configuració, els mòduls d'aplicació personalitzats i els controladors personalitzats en una carpeta anomenada userConfig, ubicada dins la carpeta NVDA.

Les versions instal·lades de NVDA desen tota la configuració, els mòduls d'aplicació personalitzats i els controladors personalitzats en una carpeta NVDA especial, ubicada al teu perfil d'usuari de Windows.
Això significa que cada usuari del sistema pot tenir la seva pròpia configuració de NVDA.
Per accedir a la carpeta de configuració de la versió instal·lada de NVDA, al menú Inici, vés a Programes -> NVDA -> explora el directori de configuració de l'usuari.

La configuració de NVDA a l'inici de sessió de Windows o a les pantalles UAC es desa al directori systemConfig del directori d'instal·lació de NVDA.
Normalment, aquesta configuració no s'ha de tocar.
Per canviar la configuració de NVDA de l'inici de sessió de Windows/pantalles UAC, tria la configuració desitjada de NVDA un cop has entrat a Windows, desa la configuració, i llavors prem el botó Utilitza els paràmetres desats a la pantalla d'inici de sessió i a altres pantalles de seguretat al diàleg Configuració general.

## Eines extres {#toc169}
### Visor de registre {#toc170}

El Visor de registre, que es troba a Eines al menú NVDA, et permet veure tot el registre de sortida que s'ha desat des del darrer inici de NVDA.

A banda de llegir-ne el contingut, pots desar una còpia del fitxer de registre, o actualitzar el visor per mostrar la sortida més recent des que has obert el Visor de registre.
Aquestes accions es troben al menú Visor de registre.

### Visor de veu {#toc171}

Per als desenvolupadors amb visió o per a persones que volen fer una demostració de NVDA a una audiència de persones amb visió, existeix una finestra que et permet veure tot el text que NVDA està verbalitzant en un moment donat.

Per activar el Visor de veu, selecciona l'element de menú "Visor de veu" a Eines al menú NVDA.
Desselecciona el menú per desactivar-lo.

Mentre està activat el Visor de veu, aquest s'actualitza constantment per mostrar el text verbalitzat actual.
De totes maneres, si cliques o mous el focus al Visor, NVDA aturarà momentàniament l'actualització del text, per tal de permetre't seleccionar-ne o copiar-ne fàcilment el contingut. 

Per activar el visor de veu des de qualsevol punt, assigna un gest d'entrada amb el [Diàleg de gestos d'entrada](#InputGestures).

### Gestor de complements {#toc172}

El Gestor de complements, al qual s'accedeix seleccionant Gestiona els complements sota Eines en el menú NVDA, et permet instal·lar o desinstal·lar paquets addicionals a NVDA.
Aquests paquets els ofereix la comunitat i contenen codi que pot afegir o canviar funcionalitats de NVDA o fins i tot oferir compatibilitat amb línies braille o sintetitzadors de veu addicionals.

El Gestor de complements conté una llista que mostra els complements instal·lats a la configuració d'usuari activa. 
Per cada complement es mostra el nom del paquet, la versió i l'autor, però es pot veure més informació com la descripció i URL si se selecciona el complement i es prem el botó Sobre el complement.
Si hi ha ajuda disponible per al complement seleccionat, pots accedir-hi prement el botó d'ajuda del complement.

Per navegar i descarregar els complements disponibles a la web, prem el botó Descarrega complements.
Aquest botó obre la [{@hreflang=en}pàgina de complements de NVDA](https://addons.nvda-project.org/).
Si NVDA està instal·lat i executant-se al teu sistema, pots obrir el complement directament des del navegador per iniciar el procés d'instal·lació tal i com es descriu a continuació.
Altrament, desa el paquet del complement i segueix les instruccions de més avall.

Per instal·lar un complement obtingut prèviament, prem el botó Instal·la.
Això et permetrà navegar al paquet del complement (fitxer .nvda-addon) en algun lloc del teu ordinador o en una xarxa.
Un cop prems Obre, el procés d'instal·lació s'iniciarà.

Quan s'instal·la un complement, NVDA en primer lloc et preguntarà si realment el vols instal·lar.
Com que no hi ha restriccions a la funcionalitat dels complements dins NVDA, i en teoria pot incloure accedir a les teves dades personals o fins i tot al sistema sencer si tens una versió instal·lada de NVDA, és molt important que només instal·lis NVDA de fonts de confiança.
Un cop has instal·lat el complement, cal reiniciar NVDA perquè el complement funcioni. 
Mentre no reiniciïs, aquest complement apareixerà amb l'estat "instal·lat" a la llista dels complements.

Per desinstal·lar un complement, selecciona'l de la llista i prem el botó Elimina.
NVDA et preguntarà si realment el vols desinstal·lar.
Com a la instal·lació, has de reiniciar NVDA per desinstal·lar completament el complement.
Mentre no reiniciïs, aquest complement apareixerà amb l'estat "eliminat" a la llista dels complements.

El gestor també té un botó Tanca per tancar el diàleg.
Si has instal·lat o desinstal·lat complements, NVDA et preguntarà primer si vols reiniciar per tal que els canvis tinguin lloc.

Antigament era possible augmentar les funcionalitats de NVDA copiant connectors i controladors individuals a la carpeta de configuració del teu usuari NVDA.
Tot i que aquesta versió de NVDA encara podrà carregar-los, no es mostraran dins del Gestor de complements.
Val més, doncs, eliminar aquests fitxers de la teva configuració i instal·lar el complement apropiat si n'hi ha un de disponible. 

Per accedir al Gestor de complements des de qualsevol punt, assigna-li un gest personalitzat amb el [Diàleg de gestos d'entrada](#InputGestures).

### Consola Python {#toc173}

La consola Python de NVDA, ubicada sota el menú Eines dins el menú NVDA, és una eina de desenvolupament que resulta útil per a la depuració, inspecció general de l'interior de NVDA o inspecció de la jerarquia d'accessibilitat d'una aplicació.
Per a més informació, pots consultar la Guia del desenvolupador disponible a [{@hreflang=en}la secció de desenvolupament de la pàgina web de NVDA](https://community.nvda-project.org/wiki/Development).

### Torna a carregar els connectors {#toc174}

Quan s'activa aquest element, es recarreguen els mòduls d'aplicació i connectors sense reiniciar NVDA, la qual cosa resulta útil per als desenvolupadors.

## Sintetitzadors de veu compatibles {#SupportedSpeechSynths}

Aquesta secció conté informació sobre els sintetitzadors de veu compatibles amb NVDA.
Pots consultar una llista més extensa dels sintetitzadors gratuïts i comercials que pots comprar o descarregar per usar amb NVDA, a la pàgina [{@hreflang=en}https://www.nvda-project.org/wiki/ExtraVoices](https://www.nvda-project.org/wiki/ExtraVoices)

### eSpeak {#toc176}

El sintetitzador [{@hreflang=en}eSpeak](https://espeak.sourceforge.net/) ve incorporat directament a NVDA i no requereix cap controlador o component especial per instal·lar-se.
NVDA s'inicia utilitzant eSpeak de forma predeterminada.
Com que aquest sintetitzador està incorporat a NVDA, és una bona elecció quan s'utilitza NVDA des d'un llapis USB en altres sistemes.

Cadascuna de les veus d'eSpeak parla un idioma diferent.
Hi ha aproximadament 43 idiomes compatibles amb eSpeak.

També hi ha diverses variants que permeten alterar el so de la veu.

### Microsoft Speech API version 4 (SAPI 4) {#toc177}

SAPI 4 és un estàndard antic de Microsoft per a sintetitzadors de veu.
Molts dels sintetitzadors que segueixen aquest estàndard poden adquirir-se o descarregar-se de franc a diverses companyies o a llocs web.
Si l'utilitzes amb NVDA, podràs accedir a totes les veus dels motors SAPI4 disponibles en el teu ordinador anant al [diàleg Configuració de veu](#VoiceSettings) o des de la [Configuració del sintetitzador](#SynthSettingsRing).

Si has instal·lat veus SAPI4 però el sintetitzador no apareix a la llista de sintetitzadors de NVDA, has d'instal·lar els fitxers binaris del temps d'execució de SAPI 4.0, que pots trobar a [{@hreflang=en}https://activex.microsoft.com/activex/controls/sapi/spchapi.exe](https://activex.microsoft.com/activex/controls/sapi/spchapi.exe).

### Microsoft Speech API versió 5 (SAPI 5) {#toc178}

SAPI 5 és un estàndard de Microsoft per a programari de sintetitzadors de veu.
Molts dels sintetitzadors que segueixen aquest estàndard poden adquirir-se o descarregar-se de franc a diverses companyies o a llocs web, però molt probablement el teu sistema ja inclourà com a mínim una veu SAPI 5 preinstal·lada.
Si utilitzes un sintetitzador SAPI 5 amb NVDA, podràs accedir a totes les veus disponibles dels motors SAPI5 disponibles al teu ordinador des del [diàleg Configuració de veu](#VoiceSettings) o des de la [Configuració del sintetitzador](#SynthSettingsRing). 

### Microsoft Speech Platform {#toc179}

Microsoft Speech Platform proporciona veus per a molts idiomes, emprades habitualment per al desenvolupament d'aplicacions de veu per servidor.
Aquestes veus poden usar-se també amb NVDA.

Per poder-les utilitzar, caldrà instal·lar dos components:

* Microsoft Speech Platform - Runtime (Versió 11) , x86: [{@hreflang=en}https://www.microsoft.com/download/en/details.aspx?id=27225](https://www.microsoft.com/download/en/details.aspx?id=27225)
* Microsoft Speech Platform - Runtime Languages (Versió 11): [{@hreflang=en}https://www.microsoft.com/download/en/details.aspx?id=27224](https://www.microsoft.com/download/en/details.aspx?id=27224)
 * Aquesta pàgina conté molts fitxers, tant de reconeixement de veu com de text a veu.
 Tria els fitxers que incloguin les dades TTS per als idiomes/veus que desitgis.
 A tall d'exemple, el fitxer MSSpeech_TTS_en-US_ZiraPro.msi és una veu anglesa d'EUA. veu anglesa.

### Audiologic Tts3 {#toc180}

Es tracta d'un sintetitzador comercial específicament per a l'idioma italià.
Cal tenir-lo instal·lat al teu sistema per poder-lo fer servir amb NVDA.
Per a més informació, pots visitar la web d'Audiologic a [www.audiologic.it](http://www.audiologic.it).

Aquest sintetitzador no permet la [funció de lletrejar](#VoiceSpellingFunctionality).

### Nuance Vocalizer para NVDA {#toc181}

Nuance Vocalizer és un sintetitzador comercial amb una veu d'alta qualitat, desenvolupat per Nuance Communications, Inc. i compilat expressament per a NVDA 
Conté més de 50 veus instal·lables, i inclou més de 30 idiomes.
Tots els components i veus del sintetitzador s'agrupen en paquets de complements, totalment funcionals en versions portables de NVDA.

Pots obtenir més informació sobre Nuance Vocalizer per a NVDA i sobre com comprar-lo, a la seva web [{@hreflang=en}www.vocalizer-nvda.com](https://www.vocalizer-nvda.com/).
Un percentatge de les vendes d'aquest producte es dóna a NV Access, per a finançar el desenvolupament del lector de pantalla NVDA.

## Línies braille compatibles {#SupportedBrailleDisplays}

Aquesta secció conté informació sobre les línies braille compatibles amb NVDA.

### Series Focus/PAC Mate de Freedom Scientific {#toc183}

Totes les línies Focus i PAC Mate de [{@hreflang=en}Freedom Scientific](https://www.freedomscientific.com/) són compatibles amb NVDA si es connecten per USB o Bluetooth.
Cal tenir instal·lats a l'ordinador els controladors dels terminals braille de Freedom Scientific.
Si encara no els tens, pots obtenir-los de [{@hreflang=en}https://www2.freedomscientific.com/downloads/focus-40-blue/focus-40-14-blue-downloads.asp](https://www2.freedomscientific.com/downloads/focus-40-blue/focus-40-14-blue-downloads.asp).
Tot i que aquesta pàgina només parla de la línia braille Focus Blue, els controladors funcionen amb totes les línies Focus i PAC Mate de Freedom Scientific.
Si treballes amb un sistema Windows de 64 bits i ja s'han instal·lat els controladors per a un altre lector de pantalla, segurament hauràs d'instal·lar-los des d'aquest l'enllaç, ja que segurament l'altre lector de pantalla no ha instal·lat els fitxers que NVDA necessita. 

De forma predeterminada, NVDA pot detectar automàticament i connectar-se amb aquestes línies tant per USB com per Bluetooth.
Tot i així, quan configuris la línia, pots seleccionar explícitament els ports "USB" o "Bluetooth" per restringir el tipus de connexió que usaràs.
Això pot ser útil si vols connectar la línia Focus a NVDA per Bluetooth, però vols poder carregar-lo fent servir la càrrega elèctrica per USB del teu ordinador.

A continuació pots trobar les assignacions de tecles per a aquesta línia amb NVDA.
Consulta la documentació de línia per obtenir la descripció d'on es troben aquestes tecles.
<!-- KC:beginInclude -->

| Nom |Tecla|
|---|---|
|Desplaça el terminal braille enrere |sensorSuperior1 (primera cel·la a la pantalla)|
|Desplaça el terminal braille endavant |sensorSuperior20/40/80 (darrera cel·la a la pantalla)|
|Desplaça el terminal braille enrere |barra avançar esquerra|
|Desplaça el terminal braille endavant |barra avançar esquerra|
|Commuta el seguiment de braille a |botó GDFB esquerre+botó GDFB dret|
|Commuta a roda esquerra |prémer roda esquerra|
|Mou enrere fent servir la roda esquerra |roda esquerra amunt|
|Mou endavant fent servir la roda esquerra |roda esquerra avall|
|Commuta a roda dreta |prémer roda dreta|
|Mou enrere fent servir la roda dreta |roda dreta amunt|
|Mou endavant fent servir la roda dreta |roda dreta avall|
|Guia fins a la cel·la braille |sensor|
|Tecla Retrocés |punt7|
|Tecla Retorn |punt8|
|Tecla Majúscules+Tab |BarraEspaiadoraBraille+punt1+punt2|
|Tecla Tab |BarraEspaiadoraBraille+punt4+punt5|
|Tecla Fletxa amunt |BarraEspaiadoraBraille+punt1|
|Tecla Fletxa avall |BarraEspaiadoraBraille+punt4|
|Tecla Ctrl+Fletxa esquerra |BarraEspaiadoraBraille+punt2|
|Tecla Ctrl+Fletxa dreta |BarraEspaiadoraBraille+punt5|
|Tecla Fletxa esquerra |BarraEspaiadoraBraille+punt3|
|Tecla Fletxa dreta |BarraEspaiadoraBraille+punt6|
|Tecla Inici |BarraEspaiadoraBraille+punt1+punt3|
|Tecla Fi |BarraEspaiadoraBraille+punt4+punt6|
|Tecla Ctrl+Inici |BarraEspaiadoraBraille+punt1+punt2+punt3|
|Tecla Ctrl+Fi |BarraEspaiadoraBraille+punt4+punt5+punt6|
|Tecla Alt |BarraEspaiadoraBraille+punt1+punt3+punt4|
|Tecla Alt+Tab |BarraEspaiadoraBraille+punt2+punt3+punt4+punt5|
|Tecla d'escapada |BarraEspaiadoraBraille+punt1+punt5|
|Tecla Windows |BarraEspaiadoraBraille+punt2+punt4+punt5+punt6|
|Tecla Barra espaiadora |BarraEspaiadoraBraille|
|Tecla Windows+d (minimitza totes les aplicacions) |BarraEspaiadoraBraille+punt1+punt2+punt3+punt4+punt5+punt6|
|Informa de la línia actual |BarraEspaiadoraBraille+punt1+punt4|
|Menú NVDA |BarraEspaiadoraBraille+punt1+punt3+punt4+punt5|

Per a models de Focus més nous que contenen tecles de barra balancí (focus 40, focus 80 i focus blue):

| Nom |Tecla|
|---|---|
|Mou el terminal braille a la línia anterior |balancí esquerra amunt, balancí dret amunt|
|Mou el terminal braille a la línia següent |balancí esquerra avall, balancí dret avall|

Només per a Focus 80:

| Nom |Tecla|
|---|---|
|Desplaça el terminal braille enrere |barra frontal esquerra amunt, barra frontal dreta amunt|
|Desplaça el terminal braille endavant |barra frontal esquerra avall, barra frontal dreta avall|

<!-- KC:endInclude -->

### Optelec ALVA BC640/680 {#toc184}

Els models ALVA BC640 i BC680 d'[{@hreflang=en}Optelec](https://www.optelec.com/) són compatibles si estan connectats via USB o Bluetooth.
No necessites tenir instal·lat cap controlador específic per usar aquestes línies braille.
Simplement connecta el terminal i configura NVDA per usar-lo.

Tot i que aquestes línies tenen un teclat braille, elles soles gestionen la traducció de Braille a text.
Per això, no és rellevant la configuració de la taula d'entrada braille a NVDA.

A continuació pots trobar les assignacions de tecles per a aquesta línia amb NVDA.
Consulta la documentació de línia per obtenir la descripció d'on es troben aquestes tecles.
<!-- KC:beginInclude -->

| Nom |Tecla|
|---|---|
|Desplaça el terminal braille enrere |t1|
|Mou el terminal braille a la línia anterior |t2|
|Mou el terminal braille a la línia següent |t4|
|Desplaça el terminal braille endavant |t5|
|Guia fins a la cel·la braille |sensor|
|Majúscules+Tab tecla |espai1|
|Tecla Alt |espai2|
|Tecla d'escapada |espai3|
|Tecla tab |espai4|
|Tecla fletxa amunt |espaiAmunt|
|Tecla fletxa avall |espaiAvall|
|Tecla fletxa esquerra |espaiEsquerra|
|Tecla Fletxa dreta |espaiDreta|
|Tecla Retorn |espaiRetorn|
|Menú NVDA |espai1+espai3|
|Windows+d (minimitza totes les aplicacions) |espai1+espai4|
|Tecla Windows |espai2+espai3|
|Tecla Alt+Tab |espai2+espai4|

<!-- KC:endInclude -->

### Handy Tech Displays {#toc185}

NVDA és compatible amb totes les línies braille de [{@hreflang=de}Handy Tech](https://www.handytech.de/) quan aquestes es connecten via USB o Bluetooth.
Per a línies USB més antigues, caldrà que instal·lis els controladors USB de Handy Tech al teu sistema. 

L'entrada de braille encara no és compatible.

A continuació pots trobar les assignacions de tecles per a aquesta línia amb NVDA.
Consulta la documentació de línia per obtenir la descripció d'on es troben aquestes tecles.
<!-- KC:beginInclude -->

| Nom |Tecla|
|---|---|
|Desplaça el terminal braille enrere |esquerra, amunt|
|Desplaça el terminal braille endavant |dreta, avall|
|Mou el terminal braille a la línia anterior |b4|
|Mou el terminal braille a la línia següent |b5|
|Guia fins a la cel·la braille |sensor|
|Tecla Majúscules+Tab |Tecla d'escapada|
|Tecla Alt |b2+b4+b5|
|Tecla d'escapada |b4+b6|
|Tecla Tab |Retorn|
|Tecla Retorn |Tecla d'escapada+Retorn|
|Tecla Fletxa amunt |Espai esquerre|
|Tecla Fletxa avall |Espai dret|
|Menú NVDA |b2+b4+b5+b6|
|Configuració de Handy Tech |b4+b8|

<!-- KC:endInclude -->

### MDV Lilli {#toc186}

NVDA és compatible amb la línia braille de Lilli, disponible a [{@hreflang=it}MDV](https://www.mdvbologna.it/).
No necessites tenir instal·lat cap controlador específic per usar aquestes línies braille.
Simplement connecta la línia i configura NVDA perquè la usi.

A continuació pots trobar les assignacions de tecles per a aquesta línia amb NVDA.
Consulta la documentació de línia per obtenir la descripció d'on es troben aquestes tecles.
<!-- KC:beginInclude -->

| Nom |Tecla|
|---|---|
|Desplaça el terminal braille enrere |LF|
|Desplaça el terminal braille endavant |RG|
|Mou el terminal braille a la línia anterior |UP|
|Mou el terminal braille a la línia següent |DN|
|Guia fins a la cel·la braille |sensor|
|Tecla Majúscules+Tab |SLF|
|Tecla Tab |SRG|
|Tecla Alt+Tab |SDN|
|Tecla Alt+Maj+Tab |SUP|

<!-- KC:endInclude -->

### Baum/Humanware/APH Braille Displays {#toc187}

NVDA és compatible amb algunes línies [{@hreflang=en}Baum](https://www.baum.de/cms/en/), [{@hreflang=en}HumanWare](https://www.humanware.com/) i [{@hreflang=en}APH](https://www.aph.org/) si es connecten via USB o Bluetooth.
Aquestes inclouen:

* Baum: SuperVario, PocketVario, VarioUltra (només Bluetooth), Pronto! (només Bluetooth)
* HumanWare: Brailliant, BrailleConnect
* APH: Refreshabraille

Algunes altres línies fabricades per Baum potser també funcionen, però no s'han comprovat.

Si les connectes via USB, primer has d'instal·lar els controladors USB del fabricant.
Per a la APH Refreshabraille, cal establir el mode USB com a mode sèrie.

A continuació pots trobar les assignacions de tecles per a aquesta línia amb NVDA.
Consulta la documentació de línia per obtenir la descripció d'on es troben aquestes tecles.
<!-- KC:beginInclude -->

| Nom |Tecla|
|---|---|
|Desplaça el terminal braille enrere |d2|
|Desplaça el terminal braille endavant |d5|
|Mou el terminal braille a la línia anterior |d1|
|Mou el terminal braille a la línia següent |d3|
|Guia fins a la cel·la braille |sensor|

Per a les línies que disposen d'un joystick:

| Nom |Tecla|
|---|---|
|Tecla Fletxa amunt |amunt|
|Tecla Fletxa avall |avall|
|Tecla Fletxa esquerra |esquerra|
|Tecla Fletxa dreta |dreta|
|Tecla Retorn |selecciona|

<!-- KC:endInclude -->

### hedo ProfiLine USB {#toc188}

NVDA és compatible amb la hedo ProfiLine USB de [{@hreflang=de}hedo Reha-Technik](https://www.hedo.de/).
Primer has d'instal·lar els controladors USB del fabricant.

A continuació pots trobar les assignacions de tecles per a aquesta línia amb NVDA.
Consulta la documentació de línia per obtenir la descripció d'on es troben aquestes tecles.
<!-- KC:beginInclude -->

| Nom |Tecla|
|---|---|
|Desplaça el terminal braille enrere |K1|
|Desplaça el terminal braille endavant |K3|
|Mou el terminal braille a la línia anterior |B2|
|Mou el terminal braille a la línia següent |B5|
|Guia fins a la cel·la braille |sensor|
|Commuta el seguiment de braille a |K2|
|Verbalitza-ho tot |B6|

<!-- KC:endInclude -->

### hedo MobilLine USB {#toc189}

NVDA és compatible amb la hedo MobilLine USB de [{@hreflang=de}hedo Reha-Technik](https://www.hedo.de/).
Primer has d'instal·lar els controladors USB del fabricant.

A continuació pots trobar les assignacions de tecles per a aquesta línia amb NVDA.
Consulta la documentació de línia per obtenir la descripció d'on es troben aquestes tecles.
<!-- KC:beginInclude -->

| Nom |Tecla|
|---|---|
|Desplaça el terminal braille enrere |K1|
|Desplaça el terminal braille endavant |K3|
|Mou el terminal braille a la línia anterior |B2|
|Mou el terminal braille a la línia següent |B5|
|Guia fins a la cel·la braille |sensor|
|Commuta el seguiment de braille a |K2|
|Verbalitza-ho tot |B6|

<!-- KC:endInclude -->

### HumanWare Brailliant BI/B Series {#toc190}

NVDA és compatible amb les sèries Brailliant BI i B de línies braille de [{@hreflang=en}HumanWare](https://www.humanware.com/), incloses la BI 32, BI 40 i B 80 quan es connecten via USB o Bluetooth.
Si les connectes via USB, primer has d'instal·lar els controladors USB del fabricant.

A continuació pots trobar les assignacions de tecles per a aquesta línia amb NVDA.
Consulta la documentació de línia per obtenir la descripció d'on es troben aquestes tecles.
<!-- KC:beginInclude -->

| Nom |Tecla|
|---|---|
|Desplaça el terminal braille enrere |esquerra|
|Desplaça el terminal braille endavant |dreta|
|Mou el terminal braille a la línia anterior |amunt|
|Mou el terminal braille a la línia següent |avall|
|Guia fins a la cel·la braille |sensor|
|Commuta el seguiment de braille a |amunt+avall|
|Tecla Fletxa amunt |Espai+punt1|
|Tecla Fletxa avall |Espai+punt4|
|Tecla Fletxa esquerra |Espai+punt3|
|Tecla Fletxa dreta |Espai+punt6|
|Menú NVDA |c1+c3+c4+c5 (ordre n)|
|Tecla Majúscules+Tab |Espai+punt1+punt3|
|Tecla Tab |Espai+punt4+punt6|
|Tecla Alt |Espai+punt1+punt3+punt4 (Espai+m)|
|Tecla d'escapada |Espai+punt1+punt5 (Espai+e)|
|Tecla Retorn |punt8|
|Tecla Windows+d (minimitza totes les aplicacions) |c1+c4+c5 (ordre d)|
|Tecla Windows |Espai+punt3+punt4|
|Tecla Alt+Tab |Espai+punt2+punt3+punt4+punt5 (Espai+t)|
|Verbalitza-ho tot |c1+c2+c3+c4+c5+c6|

<!-- KC:endInclude -->

### HIMS Braille Sense/Braille EDGE Series {#toc191}

NVDA és compatible amb les línies braille Sense i Braille EDGE de [{@hreflang=en}Hims](https://www.hims-inc.com/) si es connecten per USB o Bluetooth. 
Si les connectes per USB, hauràs d'instal·lar els controladors USB de HIMS al teu ordinador.
Els pots descarregar del Centre de Recursos HIMS: [{@hreflang=en}https://www.hims-inc.com/resource-center/](https://www.hims-inc.com/resource-center/)
En aquesta pàgina, selecciona el teu dispositiu i descarrega el controlador de la secció Windows-Eyes.
Tot i que la secció només esmenta Window-Eyes, aquest és un controlador USB general, que també funcionarà amb NVDA.

A continuació pots trobar les assignacions de tecles per a aquestes línies a NVDA.
Consulta la documentació de línia per obtenir la descripció d'on es troben aquestes tecles.
<!-- KC:beginInclude -->

| Nom |Tecla|
|---|---|
|Desplaça el terminal braille enrere |barra de desplaçament esquerra avall|
|Desplaça el terminal braille endavant |barra de desplaçament dreta avall|
|Mou el terminal braille a la línia anterior |barra de desplaçament esquerra amunt|
|Mou el terminal braille a la línia següent |barra de desplaçament dreta amunt|
|Guia fins a la cel·la braille |sensor|
|Majúscules+tecla Tab |punt1+punt2+Espai|
|Tecla Alt |punt1+punt3+punt4+Espai|
|Tecla d'escapada |punt1+punt5+Espai|
|Tecla Tab |punt4+punt5+Espai|
|tecla Retorn |punt8|
|tecla Retrocés |punt7|
|Tecla Fletxa amunt |punt1+Espai|
|Tecla Fletxa avall |punt4+Espai|
|Tecla Bloqueig de majúscules |punt1+punt3+punt6+Espai|
|Tecla Majúscules+Alt+Tab |avançament2+avançament3+avançament1|
|Tecla Alt+Tab |avançament2+avançament3|
|Tecla Fi |punt4+punt6+Espai|
|Tecla Ctrl+Fi |punt4+punt5+punt6+Espai|
|Tecla Inici |punt1+punt3+Espai|
|Tecla Ctrl+Inici |punt1+punt2+punt3+Espai|
|Tecla Fletxa esquerra |punt3+Espai|
|Tecla Ctrl+Maj+Fletxa esquerra |punt2+punt8+Espai+avançament1|
|Tecla Ctrl+Fletxa esquerra |punt2+Espai|
|Tecla Majúscules+Alt+Fletxa esquerra |punt2+punt7+avançament1|
|Tecla Alt+Fletxa esquerra |punt2+punt7|
|Tecla Fletxa dreta |punt6+Espai|
|Tecla Ctrl+Maj+Fletxa dreta |punt5+punt8+Espai+avançament1|
|Tecla Ctrl+Fletxa dreta |punt5+Espai|
|Tecla Majúscules+Alt+Fletxa dreta |punt5+punt7+avançament1|
|Tecla Alt+Fletxa dreta |punt5+punt7|
|Tecla Re Pàg |punt1+punt2+punt6+Espai|
|Tecla Ctrl+Re Pàg |punt1+punt2+punt6+punt8+Espai|
|Tecla Ctrl+Maj+Fletxa amunt |punt2+punt3+punt8+Espai+avançament1|
|Tecla Ctrl+Fletxa amunt |punt2+punt3+Espai|
|Tecla Majúscules+Alt+Fletxa amunt |punt2+punt3+punt7+avançament1|
|Tecla Alt+Fletxa amunt |punt2+punt3+punt7|
|Tecla Majúscules+Fletxa amunt |barra de desplaçament esquerra avall+Espai|
|Tecla Av Pàg |punt3+punt4+punt5+Espai|
|Tecla Ctrl+Av Pàg |punt3+punt4+punt5+punt8+Espai|
|Tecla Ctrl+Maj+Fletxa avall |punt5+punt6+punt8+Espai+avançament1|
|Tecla Ctrl+Fletxa avall |punt5+punt6+Espai|
|Tecla Majúscules+Alt+Fletxa avall |punt5+punt6+punt7+avançament1|
|Tecla Alt+Fletxa avall |punt5+punt6+punt7|
|Tecla Majúscules+Fletxa avall |barra de desplaçament dreta avall+Espai|
|Tecla Supr |punt1+punt3+punt5+Espai|
|Tecla f1 |punt1+punt2+punt5+Espai|
|Tecla f3 |punt1+punt2+punt4+punt8|
|Tecla f4 |punt7+avançament3|
|Tecla Windows+b |punt1+punt2+avançament1|
|Tecla Windows+d |punt1+punt4+punt5+avançament1|

<!-- KC:endInclude -->

### HIMS SyncBraille {#toc192}

NVDA és compatible amb la línia SyncBraille de [{@hreflang=en}HIMS](https://www.hims-inc.com/).
Hauràs d'instal·lar els controladors USB de HIMS al teu ordinador.

A continuació pots trobar les assignacions de tecles per a aquesta línia amb NVDA.
Consulta la documentació de línia per obtenir la descripció d'on es troben aquestes tecles.
<!-- KC:beginInclude -->

| Nom |Tecla|
|---|---|
|Desplaça el terminal braille enrere |barra de desplaçament esquerra avall|
|Desplaça el terminal braille endavant |barra de desplaçament dreta avall|
|Guia fins a la cel·la braille |sensor|

<!-- KC:endInclude -->

### Seika Braille Displays {#toc193}

NVDA és compatible amb la línia braille Seika versió 3, 4 i 5 (40 cel·les) i Seika80 (80 cel·les) de [{@hreflang=en}Nippon Telesoft](https://www.nippontelesoft.com/).
Pots trobar més informació sobre aquestes disposicions a [{@hreflang=en}https://www.seika-braille.com/](https://www.seika-braille.com/).
Primer has d'instal·lar els controladors USB del fabricant.

A continuació pots trobar les assignacions de tecles per a aquesta línia amb NVDA.
Consulta la documentació de línia per obtenir la descripció d'on es troben aquestes tecles.
<!-- KC:beginInclude -->

| Nom |Tecla|
|---|---|
|Desplaça el terminal braille enrere |esquerra|
|Desplaça el terminal braille endavant |dreta|
|Mou el terminal braille a la línia anterior |b3|
|Mou el terminal braille a la línia següent |b4|
|Commuta el seguiment de braille a |b5|
|Verbalitza-ho tot |b6|
|Tecla Tab |b1|
|Tecla Majúscules+Tab |b2|
|Tecla Alt+Tab |b1+b2|
|Menú NVDA |esquerra+dreta|
|Guia fins a la cel·la braille |sensor|

<!-- KC:endInclude -->

### Models més actuals de Papenmeier BRAILLEX {#toc194}

Les següents línies braille són compatibles: 

* BRAILLEX EL 40c, EL 80c, EL 20c, EL 60c (USB)
* BRAILLEX EL 40s, EL 80s, EL 2d80s, EL 70s, EL 66s (USB)
* BRAILLEX Trio (USB i Bluetooth)
* BRAILLEX Live 20, BRAILLEX Live i BRAILLEX Live Plus (USB i bluetooth) 

Si BrxCom està instal·lat, NVDA el farà servir.
BrxCom és una eina que et permet fer servir l'entrada braille de forma independent d'un lector de pantalla.
Papenmeier distribuirà aviat una nova versió de BrxCom que treballa amb NVDA.
L'entrada de braille també és possible amb el dispositiu de Trio, i amb els dispositius BRAILLEX Live.

La majoria de dispositius tenen una Barra d'Accés Ràpid (EAB) que permet operar-les ràpidament i intuitiva.
L'EAB es pot moure en quatre direccions i cada direcció sol tenir dos commutadors.
Les sèries C i Live són les úniques excepcions a aquesta regla.

Les sèries C i altres línies braille tenen dues files de sensors, la superior de les quals es fa servir per donar informació de format.
Si mantens premuda una de les tecles dels sensors superior i prems alhora la EAB en els dispositius de les sèries C emules l'estat del segon commutador.
Les pantalles de les sèries Live tenen només una fila de sensors i la EAB té un commutador per direcció.
El segon commutador es pot emular prement un dels sensors i prement la EAB de la direcció corresponent.
Mantenir premudes les tecles amunt, avall, dreta o esquerra (o EAB) fa que l'acció corresponent es repeteixi.

Generalment, les següents tecles es troben disponibles en aquestes línies braille:

| Nom |Tecla|
|---|---|
|l1 |Tecla frontal esquerra|
|l2 |Tecla següent esquerra|
|r1 |Tecla frontal dreta|
|r2 |Tecla següent dreta|
|amunt |1 pas amunt|
|amunt2 |2 passos amunt|
|esquerra |1 pas esquerra|
|esquerra2 |2 passos esquerra|
|dreta |1 pas dreta|
|dreta2 |2 passos dreta|
|avall |1 pas avall|
|avall2 |2 passos avall|

A continuació pots trobar les ordres assignades a NVDA dins Papenmeier:
<!-- KC:beginInclude -->

| Nom |Tecla|
|---|---|
|Desplaça el terminal braille enrere |esquerra|
|Desplaça el terminal braille endavant |dreta|
|Mou el terminal braille a la línia anterior |amunt|
|Mou el terminal braille a la línia següent |avall|
|Guia fins a la cel·la braille |sensor|
|Informa del caràcter actual en revisió |esquerra1|
|Activa l'objecte de navegació actual |esquerra2|
|Commuta el seguiment de braille a |dreta2|
|Informa del títol |esquerra1+amunt|
|Informa de la Barra d'estat |esquerra2+avall|
|Mou a objecte contenidor |amunt2|
|Mou al primer objecte contingut |avall2|
|Mou a l'objecte anterior |esquerra2|
|Mou a l'objecte següent |dreta2|
|Informa del format de text |fila de sensors superior|

<!-- KC:endInclude -->

El model Trio té quatre tecles addicionals que es troben enfront del teclat braille.
Aquestes són (ordenades d'esquerra a dreta):

* Tecla polze esquerre (lt)
* Espai
* Espai
* Tecla polze dret (rt)

Actualment la tecla del polze dret no és funcional.
Les tecles interiors es mapegen amb l'espai.

<!-- KC:beginInclude -->

| Nom |Tecla|
|---|---|
|Tecla Retrocés |punt 7|
|Tecla Retorn |punt 8|
|Tecla d'escapada |Espai amb punt 7|
|Tecla Fletxa amunt |Espai amb punt 2|
|Tecla Fletxa esquerra |Espai amb punt 1|
|Tecla Fletxa dreta |Espai amb punt 4|
|Tecla Fletxa avall |Espai amb punt 5|
|Tecla Ctrl |polze esquerra+punt2|
|Tecla Alt |polze esquerra+punt3|
|Tecla Ctrl+Tecla d'escapada |Espai amb punt 1 2 3 4 5 6|
|Tecla Tab |Espai amb punt 3 7|

<!-- KC:endInclude  -->

### Models anteriors de Papenmeier Braille BRAILLEX {#toc195}

Les següents línies braille són compatibles: 

* BRAILLEX EL 80, EL 2D-80, EL 40 P
* BRAILLEX Tiny, 2D Screen

Tingues en compte que aquestes línies només es poden connectar per port sèrie.
Per això, has de seleccionar el port al qual està connectada la línia després de seleccionar aquest controlador al diàleg Configuració de braille.

Alguns d'aquests dispositius tenen una Barra de fàcil accés (EAB) que permet interaccionar de forma intuïtiva i ràpida.
L'EAB es pot moure en quatre direccions i cada direcció sol tenir dos interruptors.
Mantenint premudes la tecla amunt, avall, dreta o esquerra (o EAB) fa que l'acció corresponent es repeteixi.
Els dispositius més antics no tenen una EAB,  i cal usar les tecles frontals.

Generalment, les següents tecles estan disponibles en les línies braille:


| Nom |Tecla|
|---|---|
|l1 |Tecla frontal esquerra|
|l2 |Tecla següent esquerra|
|r1 |Tecla frontal dreta|
|r2 |Tecla següent dreta|
|amunt |1 pas amunt|
|amunt2 |2 passos amunt|
|esquerra |1 pas esquerra|
|esquerra2 |2 passos esquerra|
|dreta |1 pas dreta|
|dreta2 |2 passos dreta|
|avall |1 pas avall|
|avall2 |2 passos avall|

A continuació pots trobar les ordres assignades a NVDA dins Papenmeier:

<!-- KC:beginInclude -->
Dispositius amb EAB:

| Nom |Tecla|
|---|---|
|Desplaça el terminal braille enrere |esquerra|
|Desplaça el terminal braille endavant |dreta|
|Mou el terminal braille a la línia anterior |amunt|
|Mou el terminal braille a la línia següent |avall|
|Guia fins a la cel·la braille |sensor|
|Informa del caràcter actual en revisió |esquerra1|
|Activa l'objecte de navegació actual |esquerra2|
|Informa del títol |esquerra1amunt|
|Informa de la barra d'estat |esquerra2avall|
|Mou a objecte contenidor |amunt2|
|Mou al primer objecte contingut |avall2|
|Mou a l'objecte següent |dreta2|
|Mou a l'objecte anterior |esquerra2|
|Informa del format del text |Tira d'enrutament superior|

BRAILLEX Tiny:

| Nom |Tecla|
|---|---|
|Informa del caràcter actual en revisió |esquerra1|
|Activa l'objecte de navegació actual |esquerra2|
|Desplaça el terminal braille enrere |esquerra|
|Desplaça el terminal braille endavant |dreta|
|Mou el terminal braille a la línia anterior |amunt|
|Mou el terminal braille a la línia següent |avall|
|Commuta el seguiment de braille a |dreta2|
|Mou a objecte contenidor |dreta1+amunt||
|Mou al primer objecte contingut |dreta1+avall|
|Mou a l'objecte anterior |dreta1+esquerra|
|Mou a l'objecte següent |dreta1+dreta|
|Informa del format del text |reportf|
|Informa del títol |esquerra1+amunt|
|Informa de la barra d'estat |esquerra2+avall||

BRAILLEX 2D Screen:

| Nom |Tecla|
|---|---|
|Informa del caràcter actual en revisió |esquerra1|
|Activa l'objecte de navegació actual |esquerra2|
|Commuta el seguiment de braille a |dreta2|
|Informa del format del text |reportf|
|Mou el terminal braille a la línia anterior |amunt|
|Desplaça el terminal braille enrere |esquerra|
|Desplaça el terminal braille endavant |dreta|
|Mou el terminal braille a la línia següent |avall|
|Mou a l'objecte següent |esquerra2|
|Mou a l'objecte contenidor |amunt2|
|Mou al primer objecte contingut |avall2|
|Mou a l'objecte anterior |dreta2|

<!-- KC:endInclude -->

### HumanWare BrailleNote {#toc196}

NVDA és compatible amb els anotadors BrailleNote de [{@hreflang=en}Humanware](https://www.humanware.com) quan aquests actuen com a línia braille d'un lector de pantalles.
Els següents models són compatibles:

* BrailleNote Classic (només connexió sèrie)
* BrailleNote PK (connexions sèrie i Bluetooth)
* BrailleNote MPower (connexions sèrie i Bluetooth)
* BrailleNote Apex (connexions USB i Bluetooth)

Si el teu dispositiu permet més d'un tipus de connexió, quan connectis el BrailleNote a NVDA, has d'establir el port com a port per terminal Braille. 
Revisa el manual de BrailleNote per a més detalls.
A NVDA, potser també et cal establir el port al diàleg Configuració de braille.
Si el connectes per USB o Bluetooth, pots establir el port en "Automàtic", "USB" o "Bluetooth", segons les opcions disponibles.
Si el connectes amb un port antic (o un convertidor USB a sèrie) o si no apareix cap de les opcions anteriors, hauràs de triar explícitament el port de comunicacions que vulguis fer servir dins la llista de ports de maquinari.

Abans de connectar l'Apex BrailleNote a través de la seva interfície client USB, hauràs d'instal·lar els controladors d'HumanWare.

A continuació pots trobar les ordres que les BrailleNote assignen a NVDA.
Revisa la documentació de la teva BrailleNote per saber on trobar aquestes tecles.

<!-- KC:beginInclude -->

| Nom |Tecla|
|---|---|
|Desplaça el terminal Braille enrere |enrere|
|Desplaça el terminal braille endavant |avançament|
|Mou el terminal braille a la línia anterior |anterior|
|Mou el terminal braille a la línia següent |següent|
|Guia fins a la cel·la braille |sensor|
|Commuta el seguiment de braille a |anterior+següent|
|Tecla Fletxa amunt |Espai+punt1|
|Tecla Fletxa avall |Espai+punt4|
|Tecla Fletxa esquerra |Espai+punt3|
|Tecla Fletxa dreta |Espai+punt6|
|Tecla Re Pàg |Espai+punt1+punt3|
|Tecla Av Pàg |Espai+punt4+punt6|
|Tecla Inici |Espai+punt1+punt2|
|Tecla Fi |Espai+punt4+punt5|
|Tecla Ctrl+Inici |Espai+punt1+punt2+punt3|
|Tecla Ctrl+Fi |Espai+punt4+punt5+punt6|
|Tecla Espai |Espai|
|Tecla Retorn |Espai+punt8|
|Tecla Retrocés |Espai+punt7|
|Tecla Tab |Espai+punt2+punt3+punt4+punt5 (Espai+t)|
|Tecla Majúscules+Tab |Espai+punt1+punt2+punt5+punt6|
|Tecla Windows |Espai+punt2+punt4+punt5+punt6 (Espai+w)|
|Tecla Alt |Espai+punt1+punt3+punt4 (Espai+m)|
|Commuta ajuda d'entrada |Espai+punt2+punt3+punt6 (Espai+h minúscula)|

<!-- KC:endInclude  -->

### EcoBraille {#toc197}

NVDA és compatible amb les línies EcoBraille segons [ONCE](https://www.once.es)
Els següents models són compatibles:

* EcoBraille 20
* EcoBraille 40
* EcoBraille 80
* EcoBraille Plus

A NVDA, pots configurar el port sèrie en el que està connectada la línia braille al Diàleg de configuració de braille. 

A continuació trobaràs les assignacions de tecles per a les línies EcoBraille.
Mira la [documentació EcoBraille](ftp://ftp.once.es/pub/utt/bibliotecnia/Lineas_Braille/ECO/) en la que es descriu on trobar aquestes tecles.

<!-- KC:beginInclude -->

| Nom |Tecla|
|---|---|
|Desplaça el terminal braille enrere |T2|
|Desplaça el terminal braille endavant |T4||
|Mou el terminal braille a la línia anterior |T1|
|Mou el terminal braille a la línia següent |T5|
|Guia fins a la cel·la braille |sensor|
|Activa l'objecte de navegació actual |T3|
|Canvia al mode de navegació següent |F1|
|Mou a l'objecte contenidor |F2|
|Canvia al mode de navegació anterior |F3|
|Canvia a l'objecte anterior |F4|
|Informa de l'objecte actual |F5|
|Mou al següent objecte |F6|
|Mou a l'objecte amb el focus |F7|
|Mou al primer objecte contingut |F8|
|Mou el focus del sistema o de cursor a la posició actual de revisió |F9|
|Informa de la posició actual del cursor |F0|
|Commuta el seguiment de braille a |A|

<!-- KC:endInclude  -->

### BRLTTY {#toc198}

[{@hreflang=en}BRLTTY](https://mielke.cc/brltty/) és un programa independent que es pot usar per complementar moltes línies braille.
Per a fer-lo servir, cal que instal·lis [{@hreflang=en}BRLTTY for Windows](https://brl.thefreecat.org/brltty/).
Has de descarregar i instal·lar el darrer paquet d'instal·lació, que s'anomenarà, per exemple, brltty-win-4.2-2.exe.
Quan configuris quina línia i port faràs servir, assegura't de fixar-te en les instruccions, especialment si fas servir una línia USB i ja tens els controladors del fabricant instal·lats.

Per a les línies que disposen de teclat braille, BRLTTY gestiona l'entrada braille per sí mateix.
Per això, no és rellevant la configuració de la taula d'entrada Braille a NVDA.

A continuació pots trobar les ordres que les BRLTTY assignen a NVDA.
Revisa la [{@hreflang=en}Documentació dels jocs de tecles BRLTTY](https://mielke.cc/brltty/doc/KeyTables/) per conèixer com es mapegen les ordres BRLTTY amb els controls a les línies braille.
<!-- KC:beginInclude -->

| Nom |ordre BRLTTY|
|---|---|
|Desplaça el terminal braille enrere |fwinlt (vés enrere una finestra)|
|Desplaça el terminal braille endavant |fwinrt (vés endavant una finestra)|
|Mou el terminal braille a la línia anterior |lnup (vés amunt una línia)|
|Mou el terminal braille a la línia següent |lndn (vés avall una línia)|
|Guia fins a la cel·la braille |sensor (porta el cursor al caràcter)|

<!-- KC:endInclude -->

++ Tipus de control Braille i abreviatures d'estat +
Per tal d'encabir tanta informació com sigui possible en un terminal Braille, les següents abreviatures s'han definit per indicar tipus de control i estat.

| Abreviatura |Tipus de control|
|---|---|
|btn |botó|
|cbo |quadre combinat|
|chk |casella de verificació|
|dlg |diàleg|
|edt |camp de text editable|
|gra |gràfic|
|cN |columna número n de la taula, per ex. c1, c2.|
|rN |fila número n de la taula, per exemple r1, r2.|
|hN |encapçalament de nivell, per exemple h1, h2.|
|lnk |enllaç|
|lst |llista|
|vlnk |enllaç visitat|
|mnu |menú|
|mnubar |barra de menú|
|rbtn |botó d'opció|
|tb |taula|
|tv |vista en arbre|
|lv N |l'element de la vista en arbre té el nivell jeràrquic N||
|`-----` |separador|

Els següents indicadors d'estat també s'han definit:

| Abreviatura |Estat de control|
|---|---|
|... |es mostra quan un objecte permet autocompletat|
|( ) |es mostra quan un objecte (per exemple una casella de verificació) no està seleccionat|
|(x) |es mostra quan un objecte (per exemple una casella de verificació) està seleccionat|
|(-) |es mostra quan un objecte (per exemple una casella de verificació) està seleccionat a mitges|
|- |es mostra quan un objecte (per exemple un element en una llista d'arbre) es pot plegar|
|+ |es mostra quan un objecte (per exemple un element en una llista d'arbre) es pot desplegar|
|clk |es mostra quan un objecte es pot clicar|
|ro |es mostra quan un objecte (per exemple un camp de text editable) és de només lectura|
|sel |es mostra quan un objecte està seleccionat|
|submnu |es mostra quan un objecte té una finestra popup (normalment un submenú)|

## Temes avançats {#toc199}
### Opcions de la línia de comandes {#CommandLineOptions}

En iniciar NVDA es poden indicar una o més opcions que n'alteren el funcionament.
Pots indicar tantes opcions com necessitis.
Aquestes opcions poden indicar-se en iniciar NVDA des d'una drecera de teclat (a les propietats de dreceres), des del diàleg d'Executar (Menú d'Inici -> Executar o Windows+r) o des de la consòla de comandes Windows.
Cal indicar les opcions després del nom del fitxer executable NVDA separades per espais.
Per exemple, la drecera de sobretaula que crea NVDA durant la instal.lació té l'opció -r, la qual indica a NVDA que tanqui la còpia en execució abans d'iniciar la nova.
Una altra opció molt útil és --disable-addons (desactiva extensions), que indica a NVDA que aturi totes les extensions actualment en execució. 
Això et permet determinar si és una extensió la que causa un problema i refer-te d'alguns problemes seriosos causats per extensions.

Com a exemple, pots sortir de la còpia en curs de NVDA introduint la següent comanda en el diàleg d'Execució:

nvda -q

Algunes de les opcions de la línia de comandes tenen una versió curta i una llarga, mentre que altres només tenen una versió llarga.
Per aquelles que tenen una versió curta, pots combinar-les com:

|nvda -rm |Aquesta comanda sortirà de la còpia en curs i iniciarà una nova còpia amb els sons d'inici desactivats, etc.|
|nvda -rm --disable-addons |Igual que abans, però amb les extensions desactivades|

Algunes de les opcions de la línia de comandes accepten paràmetres addicionals; per exemple el nivell de detall del registre  de log o el camí a la carpeta de configuració de l'usuari.
Aquests paràmetres s'han de situar després de l'opció, separats de l'opció per un espai si s'usa la versió curta o per un signe igual (=) quan s'usa la versió llarga; per exemple:

|nvda -l 10 |Indica a NVDA d'iniciar-se amb un nivell de registre de log de debug|
|nvda --log-file=c:\nvda.log |Indica a NVDA d'escriure el registre de log a c:\nvda.log|
|nvda --log-level=20 -f c:\nvda.log |Indica a NVDA d'iniciar-se amb un nivell de registre de log de informació i d'escriure el registre a c:\nvda.log|

A continuació es mostren les opcions de la línia de comandes de NVDA:

| Curta |LLarga |Descripció|
|---|---|---|
|-h |--help |mostra l'ajuda de la línia de comandes i surt|
|-q |--quit |Surt de la còpia de NVDA en execució|
|-r |--replace |Surt de la còpia de NVDA en execució i inicia aquesta|
|-k |--check-running |Informa sobre si NVDA s'està executant amb un codi de sortida; 0 si s'està executant, 1 si no s'està executant|
|-f LOGFILENAME |--log-file=LOGFILENAME |El fitxer on els missatges del registre de log s'hauran d'escriure|
|-l LOGLEVEL |--log-level=LOGLEVEL |El nivell més baix dels missatges registrats (debug 10, informació 20, avís 30, error 40, crítics 50), el nivell per defecte és 'avís'|
|-c CONFIGPATH |--config-path=CONFIGPATH |La carpeta en la que la configuració de NVDA es guarda|
|-m |--minimal |Sense so, sense interfície, sense missatge d'inici etc|
|-s |--secure |Mode segur (amb la cònsola Python desactivada)|
|cap |--disable-addons |Les extensions no tindran efecte|
|cap |--no-sr-flag |No canviïs el flag de lectors de pantalla del sistema global|
|cap |--install |Instal·la NVDA (i inicia la còpia nova instal·lada)|
|cap |--install-silent |Instal·la NVDA en silenci (i no inicia la còpia nova instal·lada)|

### Personalització avançada de la pronúncia de símbols {#toc201}

Es pot personalitzar la pronúncia de la puntuació i d'altres símbols més enllà del qual permet el diàleg [Pronúncia de la puntuació i dels símbols](#SymbolPronunciation).
Per exemple, pots especificar si el símbol original s'ha d'enviar al sintetitzador (per ex. per provocar una pausa o canvi en la inflexió) i pots afegir símbols personalitzats.

Per fer-ho, has d'editar el fitxer d'informació sobre la pronúncia de símbols a la carpeta de la teva configuració d'usuari NVDA.
El fitxer s'anomena symbols-xx.dic, i xx és el codi de l'idioma.
El format d'aquest fitxer es documenta a la secció Pronúncia de símbols a la guia de desenvolupadors NVDA, que pots trobar en anglès a la [{@hreflang=en}secció per a desenvolupadors del lloc web de NVDA](https://community.nvda-project.org/wiki/Development).
De totes maneres, els usuaris no poden definir símbols complexos.

## Més informació {#toc202}

Si et cal més informació o assistència en pel que fa a NVDA, visita el lloc web NVDA a NVDA_URL.
Allà, podràs trobar documentació addicional, així com suport tècnic i recursos de la comunitat.
El lloc web ofereix també informació i recursos sobre el desenvolupament de NVDA.

