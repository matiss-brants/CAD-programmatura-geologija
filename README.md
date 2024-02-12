# 🏃 **"Quick start" pamācība kursā "CAD programmatūra ģeoloģijā"**

Šī pamācība ir palīgmateriāls kursam "CAD programmatūra ģeoloģijā", kas tiek pasniegta Latvijas Universitātes ģeoloģijas bakalaura programmas ietvaros. Tās mērķis ir nostiprināt esošās zināšanas un kalpot kā špikeris reizēs, kad aizmirstās konkrētas funkcijas vai darbības. 

`Matīss Brants 2024`✍️

> Atjaunināts:
> - 12.02.2024: izveidota otrā daļa, pievienotas pāris funkcijas pirmajā daļā, daži attēli aizvietoti ar animācijām;

# **1️⃣ PIRMĀ DAĻA - pamatlietas**

![ievadam](atteli/bob-ross.gif)

Šajā daļā atkārtosim pašus pamatus darbam ar CAD. Noderēs arī projektējot savu pirtiņu, plānojot istabas interjeru, vai veidojot rasējumu jaunam galdam. 🧐
Rasējuma uzlikšana uz lapas, mērogošana, eksportēšana utml. sekos tālākajās daļās.

## **☕ 1. Darba sākšana**

### 1.1 Faila atvēršana
Lai atvērtu jaunu failu, klikšķinām uz `New` augšējā kreisajā rīkjoslā (horizontāli pagriezta papīra lapa).
Kad atveras `Select template` logs, atstājam izvēlētu `acadiso.dwt` un spiežam `Open`. Ja darbavietā ir jābalstās uz specifisku noformējumu, var palūgt izveidot šādu template, vai arī vienkāršāk - atvērt vecu failu un būvēt jauno rasējumu, balstoties uz tā.

![Faila atvēršana](atteli/1-sakums.png)

### 1.2. Faila saglabāšana

Uzreiz saglabājam failu ar `Ctrl + S`. Izdomājam faila nosaukumu, un pārbaudam, kādā versijā glabājam failu - ja, piemēram, projektētājiem ir AutoCAD 2017 versija, tad būs jāsaglabā kā AutoCAD 2013 failu.

**❗❗❗ Atcerieties regulāri saglabāt failu ar `Ctrl + S` vai ar 💾, lai nebūtu atkal jāvaino suni, ka darbs tika apēsts! 🐕**

![Saglabāšanas iestatījumi](atteli/2-saglabasana.png)

### 1.3. Darba vides iestatījumi

Ja vēlamies noņemt fona tīklu - `F7`. Ja vēlaties uzlikt citu fona krāsu, klikšķinām uz sarkanās `ACAD` pogas ekrāna augšējā kreisajā stūrī, tad uz `Options`. Logā klikšķinām uz cilnes `Display` un `Colors`. Tad logā `Drawing Window Colors`, izvēloties `Uniform background` nomainām `Color` uz `Black` vai kaut vai rozā, ja tāda vēlme 🌈.

![Displeja iestatījumi](atteli/3-display.png)

## **🎨 2. Zīmēšana**

### 2.1. Pārvietošanās zīmējumā

- `Peles ritulis (MMB) uz priekšu/atpakaļ` - pietuvinām/attālinām
- `Turam MMB un kustinām peli` - pārvietojam skatu pa rasējumu
- `MMB dubultklikšķis` - iekļaut ekrānā visus elementus (noder, ja kafijas pauzē kaķis 🐈 spēlējies ar peli, un rasējums kaut kur aizmucis)

❗ Ar Mac datoriem ir citādāk, bet viss ir izdarāms. Tur gan jums pašiem jāmeklē šīs funkcijas.

### 2.2. Līnijas un figūras
Izmantojot klaviatūru, rakstām funkcijas (vai arī meklējam pogas augšējā rīkjoslā):

- `PL` jeb `POLYLINE` - polilīnija
- `REC` jeb `RECTANGLE` - taisnstūris
- `C` jeb `CIRCLE` - aplis
- `E` jeb `ELLIPSE` - elipse
- `SPL` jeb `SPLINE` - līklīnija

Katrai līnijai un figūrai varam norādīt izmērus. Līnijai tas ir garums, aplim tas ir rādiuss (bet šo var mainīt), taisnstūrim tās ir abas malas (otras malas garumu var norādīt, pārslēdzoties ar `Tab`), elipsei tās ir abas asis.

📏 Bet kādās mērvienībās zīmēt? [Jebkādās! AutoCAD izmanto bezdimensiju sistēmu.](https://www.autodesk.com/blogs/autocad/autocad-drawing-units/) Galvenais, pārliecināties, ka zīmējat pienācīgā mērogā. Ģeoloģijā ir maza jēga no kilometriem vai milimetriem, tādēļ labāk pieņemt ka bezdimensiju vienības ir metri vai centimetri. Ir iespējams iestatīt mērvienības, taču tās ir būtiskas tikai tad, kad atliekam izmērus rasējumā. Funkcionāli tās neko nemaina.

Ja vēlamies zīmēt vertikāli un horizontāli, ieslēdzam Ortogonālo režīmu ar `F8`. Apakšējā komandrindā (baltais logs) parādās `<Ortho on>`:

![Ortogonālais režīms](atteli/acad_NR2hZNXX8g.gif)

Ja vēlamies zīmēt polilīniju ar specifisku leņķi, tad, uzsākot tās zīmēšanu, noklikšķinām `Tab`, kas ļauj ievadīt leņķi: (bet, protams, jāizslēdz ortogonālo režīmu ar `F8`)

![Leņķa ievadīšana](atteli/acad_sfjLFuMrCQ.gif)

### 2.3. Elementu izvēle

Ar kursoru uzbraucot uz kādas līnijas vai elementa, tie izgaismojas. Ar kreiso peles klikšķi tos varam atlasīt. 

Taču atlasīt var arī ar rāmi, ja kursors neatrodas uz kāda elementa. Noklikšķinām ar kreiso peles taustiņu, un tad velkam:
- uz labo pusi, lai izvēlētos visus elementus *rāmja iekšpusē*:
- vai uz kreiso pusi, lai izvēlētos visus elementus *kam rāmis pieskarās*:
![Zaļais un zilais rāmis](atteli/acad_g5Awd0Phnv.gif)

- Ja divas līnijas pārklāj vienu otru, varam rotēt to izvēli, uzbraucot uz tām ar kursoru un tad turot `Shift` un klikšķinot `Space`.

### 2.4. Elementu pārveidošana

- Taustiņš `Delete` - izvēlētā elementa dzēšana
- `CO` jeb `COPY` - kopēt
- `M` jeb `MOVE` - pārvietot
- `RO` jeb `ROTATE` - pagriezt
- `SC` jeb `SCALE` - mērogot (palielināt/samazināt)
- `EX` jeb `EXTEND` - pagarināt līniju līdz nākamajai līnijai (ar šo var darboties arī advancētāk, taču pameklējiet paši)
- `TR` jeb `TRIM` - apgriezt līniju līdz tuvākajai šķērsojošai līnijai
- `J` jeb `JOIN` - apvienot atsevišķas līnijas vienā figūrā (līnijām ir jāsaskarās)
- `X` jeb `EXPLODE` - sadalīt saliktu elementu pa daļām
- `BR` jeb `BREAK` - atdalīt līniju divos punktos
- `Ctrl + Z` - darbība atpakaļ
- `Ctrl + Y` - darbība uz priekšu
- `OOPS` - atgriezt atpakaļ iepriekš izdzēstus elementus, pat ja ir jau uzzīmēti jauni

### 2.5. Līniju *snepošana* (snapping)

Lai *piesnepotu* līniju pie noteikta punkta uz cita elementa, jāieslēdz `Osnap` režīmu ar `F3`. Tad var izmantot komandu `OSNAP`, lai izvēlētos, kādas *snepošanas* iespējas mums vienmēr tiek piedāvātas.

Iesaku vienmēr atstāt **ie**slēgtu `Endpoint`, `Midpoint`, `Center` un `Node`. Ļoti iesaku **at**slēgt `Nearest`.

![Snepošanas iestatījumi](atteli/osnap.png)

Ja gadījumā esat jau uzvilkuši vai pārvietojat/kopējat līniju, un saprotiet, ka nav iespēja *piesnepoties* pie pareizā punkta, tad turiet `Shift` un noklikšķiniet peles labo taustiņu. Parādīsies logs ar *snepošanas* punktu izvēli. Ņemiet vērā, ka tie darbojas tikai **vienu** reizi - ja vēlaties izmantot vēlreiz, būs atkal jāatver to pašu logu.

![Ātrie snepošanas iestatījumi](atteli/quick-osnap.png)
 
## 🎛️ **3. Elementu iestatījumi (properties)**

### 3.1. Slāņi

Slāņus varam aplūkot caur `Layer Properties` augšējās rīkjoslas vidū vai ar komandu `LA` jeb `LAYER`.
Būtiskas funkcijas (cipari attēlā):
1. Pievienot jaunu slāni
2. Ieslēgt/izslēgt slāņa redzamību
3. Ieslēgt/izslēgt slāņa redzamību *uz printētas/eksportētas lapas*
4. Nomainīt slāņa krāsu
5. Nomainīt līnijas tipu (nepārtraukta, pārtraukta, punktveida utml.)
6. Nomainīt līnijas platumu
   
![Slāņu iestatījumi](atteli/slani.png)

❗ Lai līnijas platums būtu redzams rasēšanas skatā, ir jāatver `Lineweight Settings` ar komandu `LINEWEIGHT` un jāieķeksē `Display Lineweight`:

![Līniju platums iestatījumi](atteli/lineweight.png)

### 3.2. Atsevišķu elementu iestatījumi

Ja vēlaties izmainīt atsevišķa elementa iestatījumus, neatkarīgi no slāņa iestatījumiem, tad to jāizvēlas un jāspiež `Ctrl + 1`:

![Elementu iestatījumi](atteli/properties.png)

# **2️⃣ OTRĀ DAĻA - ģeoloģiskā urbuma apraksts**

## **📐 4. Ģeoloģiskā urbuma apraksta veidošana**

### 4.1. Urbuma apraksta tabulas karkasa veidošana

AutoCAD piedāvā iespēju veidot tabulu, izmantojot komandu `TABLE`, taču tai ir daudz ierobežojumu, tādēļ nāksies vien pašiem zīmēt tabulu līniju pa līnijai.

Lai darbotos efektīvi, izmantojam `F8` režīmu un atliekam galvenās līnijas ar `COPY` funkciju 1) atliekot zināmus attālumus vai 2) pārnesot tās no punkta uz punktu:

![Līniju kopēšana](atteli/acad_BIMpx8w49m.gif)

Varam arī izmantot īslaicīgas palīglīnijas, lai, piem., atrastu rindas viduspunktu. Pēc tam palīglīniju varam izdzēst. Atceramies, par *snepošanās* iestatījumiem, izmantojot komandu `OSNAP`, lai varētu *snepoties* līniju viduspunktos, galos u.c.

![Viduslīniju veidošana](atteli/acad_CDNesHX4en.gif)

### 4.2. Tabulas aizpildīšana ar tekstu

Kārtīgai un pārskatāmai tabulai, mēģinām sakārtot tekstu vienādā pozīcijā, ko varam izdarīt gudri izvēloties kopēšanas *rokturi*.

![Teksta kopēšana](atteli/acad_WjyN293LCH.gif)

Tekstu varam pagriezt, izmantojot komandu `ROTATE` vai arī izmainot `Rotation` vērtību pie objekta `Properties`.

![Teksta rotēšana](atteli/text-rotate.png)

### 4.3. Laukumu iekrāsošana (*hatching*)

Lai iekrāsotu *noslēgtu* laukumu, izmantojam komandu `H` jeb `HATCH` un tad ieklikšķinām krāsojamajā laukumā. Parasti iekrāsojums nav pareizajā mērogā, tādēļ to varam regulēt ar `Hatch Pattern Scale` augšējā rīkjoslā, kad ir izvēlēts laukums.

![Laukumu iekrāsošana](atteli/acad_u0mt3aSaEd.gif)

Turpat varam izvēlēties arī rakstu jeb *pattern*.

❗ *Hatch* rīki AutoCADā mēdz uzkārties un/vai nefunkcionēt kā vajag, tādēļ reizēm var nākties izdzēst esošo iekrāsojumu un iezīmēt no jauna.

Ja laukumā ir jāievieto arī piemēram, elipses, kas attēlo oļus, tad tos varam norādīt kā neaizpildāmus laukumus ar `Select` rīku Hatch Editor rīkjoslā:

![Laukumu iekrāsošana](atteli/acad_d90DPHnBp9.gif)

## ⏸️ Otrās daļas beigas.

Tas pagaidām viss, bet turpinājums sekos! Veiksmi un galvenais - trenējieties!

![atvadām](atteli/bob-ross-3.gif)
