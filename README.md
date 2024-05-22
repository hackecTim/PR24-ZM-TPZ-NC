# VROČA SLOVENIJA
### Projekt pri predmetu Podatkovno Rudarjenje<br>Člani: Žiga Modrić, Tim Žlindra Pristavec, Nejc Černelč

Globalno segrevanje se uveljavlja kot eden najpomembnejših okoljskih izzivov sodobnosti, s takojšnjimi učinki na svetovne temperature in podnebne vzorce. V naši raziskavi bomo raziskali vpliv pojava v Evropi, kjer smo v zadnjih letih priča vse toplejšim poletjem in milejšim zimam, kar predstavlja jasen signal naraščajočih temperatur zaradi globalnega segrevanja.

Naš pristop je osredotočen na specifičen nabor podatkov za Evropo, ki zagotavlja obsežne informacije o temperaturah, merjenih na uro, po posameznih evropskih državah.
Podatke smo pridobili od platforme Renewables.ninja, ki temelji na ponovni analizi MERRA-2 NASA, kar nam omogoča dostop do zanesljivih in natančnih temperaturnih zapisov za vsako državo, upoštevajoč populacijsko povprečje za njena omrežna vozlišča.
Izbrali smo prosto dostopne podatke, ki obsegajo obdobje od leta 1980 do 2020. Temperature so merjene vsako uro, kar pomeni, da so podatki predstavljeni v obliki urnih meritev za posamezno evropsko državo, in vsebujejo 350.641 primerov ter 29 atributov.

V nadaljevanju bomo uporabili te podatke za analizo ključnih dejavnikov, ki prispevajo k globalnemu segrevanju, in poskušali identificirati vzorce, ki bi lahko napovedali prihodnje temperature. Posebno pozornost bomo posvetili Sloveniji, da bi razumeli, kako globalni trendi vplivajo na lokalne razmere, prav tako bomo preverili za sosednje države, da vidimo če je pri njih tudi podobno kot pri Sloveniji.

Analiza bo vključevala primerjavo temperaturnih podatkov iz preteklih let z najnovejšimi merjenji, da bi ugotovili, kako hitro se temperature dvigajo in kateri meseci ali letni časi kažejo največje spremembe. To bo omogočilo boljše razumevanje, kako se podnebne spremembe odražajo v različnih delih Evrope in kako se razlikujejo od globalnih povprečij.

## CILJI IN VPRAŠANJA<br>
   <li>Kdaj se je začela sprememba v ozračju Slovenije?</li>
   <li>Za koliko stopinj se je ozračje spremenilo?</li>
   <li>Kakšne posledice ima to na Slovenijo?</li>
   <li>Za koliko stopinj lahko pričakujemo rast v roku 10 let, če se ne priklopimo na "Zeleno"?</li>
   <li>Ponoviti analize za sosednje države, če obstaja kakšen vzorec.</li>

## Analize
Izvedene analize:
### 1. Analiza - Temperatura v Sloveniji med letom 1981 in 2019
   
   Prebrali smo vse podatke iz baze za Slovenijo in izbrali spodnjo in zgornjo mejo podatkov in med njima naredili primerjavo. Izbrali smo 1981 in 2019, saj obe leti nista prestopna leta in ne bo težav pri izdelavi grafa.
   Najprej smo izračunali povprečno temperaturo na dan obeh let in to prikazali s pomočjo grafa. Graf je prikazan spodaj.
   
   ![image](https://github.com/hackecTim/PR24-ZM-TPZ-NC/assets/68116017/4e1e679e-ede6-4863-9094-4333b9b585df)

   Iz grafa je razvidno, da je bilo leto 2019 v povprečju toplejše. Posebej zanimivo je, da je med majem in julijem leta 1981 prišlo do padca temperatur, pri čemer je bila razlika med letom 1981 in 2019 v tem obdobju približno 20°C, čeprav bi v tem času pričakovali    najvišje temperature, kot v letu 2019. Prav tako je zanimivo, da je proti koncu leta, decembra 2019, prišlo do nenadnega segrevanja s približno 17°C razliko med letoma, čeprav bi bilo pričakovano ohlajanje.
   

### 2. Analiza - Povprečna temperatura mescev
   
   Pri drugi analizi smo želeli prikazati povprečno temperaturo za vse mesece, predvsem pa za hladne in tople mesece med leti 1980 in 2020.
   
   ![table](https://github.com/hackecTim/PR24-ZM-TPZ-NC/assets/68116017/6a3f11c5-2600-4c4a-a068-77a7a0ec2acb)
   Slika prikazuje povprečne temperature za vse mesece v obdobju od leta 1980 do 2020. Za Slovenijo je bil najhladnejši mesec januar, najtoplejši pa julij, kar je skladno s sezonskimi pričakovanji. Podobne ugotovitve smo opazili tudi pri drugih sosednjih državah. Italija se izkazuje kot najtoplejša država, saj prevladuje s svojimi visokimi temperaturami skozi vse mesece in letne čase. Nasprotno je Avstrija najhladnejša država, z najnižjimi povprečnimi temperaturami skozi celotno leto. Te ugotovitve potrjujejo znane geografske in podnebne značilnosti regije, kjer Italija zaradi svojega južnega položaja in mediteranskega podnebja uživa mile zime in vroča poletja, medtem ko Avstrija zaradi svojega alpskega reliefa in višje nadmorske višine doživlja bolj mrzle zime in milejša poletja.

   
   Izbrali smo podatke za hladne mesece od Slovenije in jih prikazali v grafu, ki prikazuje, kako se je povprečna temperatura najhladnejših mesecev spreminjala v obdobju od leta 1980 do 
   2020. Graf je prikazan spodaj.   
   ![image](https://github.com/hackecTim/PR24-ZM-TPZ-NC/assets/150348985/33842c6a-c645-43d3-be18-224a6c94b7ec)
   
   Graf razkriva povečanje povprečnih temperatur za december, januar in februar od leta 1980 do 2020, kar lahko nakazuje na vpliv globalnega segrevanja. Izraziti temperaturni padci in vzponi so vidni v letih 1985, 1996 in 2010. Posebej hladna obdobja v začetku 80-ih in sredi 90-ih izstopajo z izjemno nizkimi temperaturami. Čeprav je januar običajno najhladnejši mesec, to še ne pomeni, da ima najhladnejše dni. Opazimo tudi trend zvišanja minimalnih zimskih temperatur v zadnjih letih, kar kaže na manj ekstremno mrzle zime.
   
### 3. Analiza - hladni in topli meseci

   Pri tretji analizi smo preko podatkov poiskali najtoplejši in najhladnejši dan med letoma 1980 in 2020 za Slovenijo in njene sosednje države. Pregledali smo vsa dnevna povprečja ter identificirali najtoplejši in najhladnejši dan.
   Za Slovenijo je bil najhladnejši dan 7. januar 1985 s temperaturo -15,26°C, medtem ko je bil najtoplejši dan 4. avgust 2017 s temperaturo 28,77°C. Razlika med tema dvema dnevoma je približno 44°C.<br>

   Izvedli smo podobno analizo za Slovenijo in njene sosednje države:

   <b>Slovenija</b><br>
   Najhladnejši dan je bil 07.01.1985 s temperaturo -15.26 °C.<br>
   Najbolj vroč dan je bil 04.08.2017 s temperaturo 28.77 °C.<br>
   Razlika: 44.03°C<br>
   
   <b>Avstrija</b><br>
   Najhladnejši dan je bil 12.01.1987 s temperaturo -19.91 °C.<br>
   Najbolj vroč dan je bil 03.08.2013 s temperaturo 26.29 °C.<br>
   Razlika: 46.2°C<br>
   
   <b>Italija</b><br>
   Najhladnejši dan je bil 10.01.1985 s temperaturo -4.62 °C.<br>
   Najbolj vroč dan je bil 04.08.2017 s temperaturo 30.70 °C.<br>
   Razlika: 35.32°C<br>

   <b>Hrvaška</b><br>
   Najhladnejši dan je bil 31.01.1987 s temperaturo -13.02 °C<br>
   Najbolj vroč dan je bil 04.08.2017 s temperaturo 30.91 °C<br>
   Razlika: 43.93°C<br>
   
   <b>Madžarska</b><br>
   Najhladnejši dan je bil 13.01.1987 s temperaturo -19.72 °C.<br>
   Najbolj vroč dan je bil 20.07.2007 s temperaturo 32.15 °C.<br>
   Razlika: 51.87°C<br>

   Po dobljenih rezultatih je razvidno, da je največja razlika v temperaturah v Madžarski, kjer je razpon med najhladnejšim in najtoplejšim dnem kar 51,87°C.
   
### 4. Analiza - Rast temperature skozi leta
   
   Pri četrti analizi smo poskušali ugotoviti kakšen je bil potek potek rasti temperature za Slovenijo in sosednje države, identificirati smo želeli tudi katerega leta je prišlo do največjega preskoka temperature. 
   To smo dosegli tako, da smo za vsako državo izračunali povprečne letne temperature in začetno temperaturo postavili na vrednost 0.
   
   ![image](https://github.com/hackecTim/PR24-ZM-TPZ-NC/assets/68116017/61b7a9a9-5db8-45be-816a-695fc586e2d5)

   S pomočjo grafa smo poiskali največji preskok v temperaturi, ki se je zgodila iz leta v leto. Največji preskok se je zgodil iz leta 2010 na leto 
   2011 za 1,4 °C. Na grafu je zelo dobro razviden trend rasti temperature v sosednjih državah, nekaj odstopanj je tudi vidno, na katere so najverjetneje vplivale različne podnebne razmere.

   
### 5. Analiza - Napoved temperature za Slovenijo in sosednje države leta 2029<br>

   Pri peti analizi smo napovedali rast temperature čez 10 let. Glede na podatke iz četrte analize, smo izračunali povprečno rast temperature za vsako desetletje od 1980 do 2020. 
   ![image](https://github.com/hackecTim/PR24-ZM-TPZ-NC/assets/68116017/94ae6c8f-919e-49f4-9f44-2461c2269abd)<br>
   
   Glede na tabelo je razvidno, da lahko v Sloveniji pričakujemo povprečno rast temperature na desetletje za 0.93°C, sprememba rasti pa je v povprečju na desetletje večja za 0.05°C. 
   Glede na spremembe rasti v desetletjih smo napovedali temperaturo za leto 2029 tako, da smo povprečni temperaturi leta 2019 prišteli povprečno rast desetletja, ter upoštevali spremembo rasti na desetletje.
   
   ![image](https://github.com/hackecTim/PR24-ZM-TPZ-NC/assets/68116017/264cc53b-c548-4d5b-8224-1d380c4b9d50)<br>
   Za Slovenijo lahko pričakujemo leta 2029, da bo v povprečju temperatura 11.73°C.


## Glavne ugotovitve
   <li>S pomočjo analize podatkov smo ugotovili, kdaj se je začela sprememba ozračja in temperature v Sloveniji. To smo prikazali s pomočjo grafa in ugotovili, da se je temperatura začela konstantno spreminjati leta 2005, 2006.</li>
   
   <li>Z analizo povprečne temperature skozi leta 1980 do 2020 smo ugotovili, da se je ozračje Slovenije povišalo za 3°C, torej v povprečju 0.075°C na leto.</li>
   
   <li>Najvišja razlika povprečne temperature v Sloveniji se je zgodila med letoma 2010 in 2011 za 1.4°C.</li>
   
   <li>Najtoplejši dan v Sloveniji je bil 07.01.1985 s povprečno temperaturo -15.26°C in najhladnejši dan je bil 04.08.2017.
   S tem lahko tudi potrdimo, da so se dnevi povprečno ogreli.</li>
   
   <li>Pričakovana sprememba v temperaturi ozračja Slovenije do leta 2030 je za 0.93°C.</li>
   
   <li>V Sloveniji pričakujemo povprečno rast temperature na desetletje za 0.93°C</li>
   
   <li>Skozi analize smo tudi potrdili, da ni samo Slovenija žrtev globalnega segrevanja, ampak se tudi sosedne države segrevajo s podobnim trendom. Lahko sklepamo, da to tudi velja za vse ostale države na svetu</li>
      
   Najzanimivejši rezultati:<br>
      <li>Najzanimivejša je bila ugotovitev, da je poletje v povprečju le za 10°C toplejše, kot pa spomlad in jesen.</li>
      <li>Leta 2029 bo povprečna temperatura 11.7°C, kar je 0.5°C več kot pa sedaj.</li>
      <li>Leta 2029 se bo najbolj ogrela Hrvaška (za približno 1.19°C), kar je tudi logično, saj je najbolj južna država v raziskavi.</li>

