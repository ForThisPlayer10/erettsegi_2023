## Szövegszerkesztés
### Betűtípusok és bekezdések
>**betűtípus:** azonos grafikai elvek szerint megtervezett ábécé
- formai szempontból három fő kategóriába sorolhatjuk:
	- **talpas betűk**: vonalvastagsága változó, a szárak talpakban végződnek
	- **talp nélküli betűtípusok**: nem rendelkeznek talpakkal, vonalvastagságuk sok esetben állandó
	- **dísz- vagy reklámbetűk**
- Egy adott betűtípus változatait **betűstílusoknak** nevezzük *(félkövér, dőlt, félkövér dőlt, aláhúzott, felső index, kiskapitális)*
- A betűk **méretének** egysége a pont

- A bekezdéseket a bekezdésjelek (¶) határolják
-  leggyakoribb bekezdésformátumok:
> **igazítás**: a bekezdés sorainak egymáshoz viszonyított helyzete
> **behúzás**: a bekezdés sorainak távolsága a margótól
> **térköz**: a bekezdés távolsága az előző, illetve következő bekezdéstől
> **sorköz**: a bekezdés sorainak távolsága
- egyéb formázások: *pl. iniciálé, háttérszín, szegély*
- Listák:
	- Ugyanaz a listajel
	- számozás:
		- betűk
		- római számok
		- arab számok
		- stb.
	- Többszintű lista

### Oldalbeállítások, fájlműveletek
- nyelvi beállítások:
	- nyelvi ellenőrzés
	- elválasztás
- oldalbeállítások:
	- papír mérete
	- tájolása
	- margók nagysága
> **szövegtükör**: margók által határolt területet

### Táblázatok és tabulátorok
- táblázatok formázása: szélesség, magasság, szegélyek, háttészín, cellák tartalmának igazítása, margók, cellaköz, cellák felosztása / egyesítése
<<<<<<< Updated upstream
- tabulátorok: igazítás, kitöltés

### Képek, szövegdobozok:
- Képek beállításai:
	- körbefuttatás szöveggel
	- elhelyezés szöveg elé vagy mögé
	- Igazítás
	- Kép és szöveg távolsága
	- Átméretezés
	- Elforgatás
- Szövegdobozok beállításai:
	- margó
	- Igazítás

### Alakzatok:
- Vektorgrafikus ábrák
- Beállításaik:
	- kitöltés
	- körvonal
	- szöveg hozzáadás
	- csoportba foglalás
	- megjelenésének módosítása: csomópontok mozgatása
=======
- képeknél igazítás lehet több féle ponthoz
>>>>>>> Stashed changes

### Kördokumentum
> **kördokumentum**: több címzett számára lényegében azonos tartalommal elkészített, de egyedi adatokkal kiegészített dokumentumhalmaz
- lépései: adatforrás (táblázat, amelynek első sora tartalmazza a mezőneveket) megadása, **törzsdokumentum** elkészítése, egyesítésük

### Nagy dokumentumok formázása
> **bekezdésstílus**: egy adott bekezdésre vonatkozó beállítások összessége, amelyet a stílus nevével azonosítunk
- stílusok hierarchikus rendszert alkotnak, amelyben egyes formázási beállítások öröklődnek, illetve felüldefiniálhatók
- tartalomjegyzék elkészítéséhez kellenek a címsorok

- élőfej, élőláb eltérhet dokumentum páros és páratlan oldalain
> **lábjegyzet**: az olvasó számára szolgáló kiegészítés, amelyet a dokumentum egy adott pontjához kapcsolva általában a szövegtükör alján helyeznek el
> *Néha ezeket a kiegészítéseket egyben, a dokumentum végére teszik, ilyenkor **végjegyzetről** beszélünk*

> **szakasz** a dokumentum formailag önálló része
- **az oldal jellemzőit** _–_ például margók, tájolás, élőfej, élőláb, oldalszámozás – szakaszonként külön-külön is beállíthatjuk
- **többhasábos** megoldással főleg újságokban találkozunk, ahol a szedéstükör olyan széles, hogy nehézkes a szemünkkel követni
- **Több szakaszra bontott dokumentum** esetén az élőfejet és az élőlábat beállíthatjuk szakaszonként, de lehetőségünk van arra is, hogy egy adott szakasz beállításai megegyezzenek az előzővel

## Számítógépes grafika és képszerkesztés
### Pixelgrafika
> **Pixel vagy raszter-grafikus fájl:** egyes képpontok színkódjainak felsorolása
-   **1 képpont tárolása:** minden színre (red, blue, green) 8 bitnyi információval 256 különféle értéket vehet fel, így összesen 24 bit-en tárol 1 képpont információját

-   **Képnézegető (viewer) programok formátumai:**
	-   **JPG:** veszteség mentes képtömörítési eljárás, a legelterjedtebb formátum
	-   **PNG:** a PNG-hez hasonló veszteség mentes tömörítési eljárás, de JPG-vel ellentétben egy pixel információit **nem 24**, **hanem 32** biten tárolja, mivel az RGB színkód mellett **képes tárolni egyes képpontok átlászóságát** is
	-   **GIF:** az egyik legrégebbi kepkiterjesztés, ami 256\*256\*256 színből egy 256 színből álló palettára képzi. Képes mozgóképek tárolására. A GIF ellenfele lehet az **APNG** ami túllép a GIF hiányosságain 
	-   **TIFF:** többrétegű képek leírására használt formátum. Elterjedtebb a használata a nyomdászatban és a GIS-rendszerekben (földrajzi információs rendszer)

- **Szerkesztő programok formátumai:**
	-   Ilyen formátumok **tárolják az adott kép rétegeit, kijelöléseit, maskjait** veszteségmentesen
	-   A GIMP formátuma az **XCF** a Photoshopé **PSD** vagy PSDX
	-   Ezek a fájlokat célszerű a saját szerkesztőprogramjukkal megnyitni

- **Fényképezőgép saját formátuma:**
	-   Ebbe a formátumba menti a fényképezőgép a fájlt exponáláskor
	-   Közös nevük a **RAW** (nyers)
	-   Rengeteg információt tartalmaznak, ami a képeken nem is látszódik pl.: kép világosításával láthatóvá válnak a képen addig egyöntetű sötét feketének tűnő területek részletei
	-   Ezek megnyitására általában általános célú megtekintő nem használható, hanem képszerkesztők
	-   Utólagos munkát Adobe Lightroommal vagy ennek ingyenes alternatívájával a Darktable-el lehet
	-   A lényegesen bonyolultabb utómunkára van szükség akkor használják az Adobe Photoshopot vagy ennek ingyenes alternatíváját a GIMPet 

- **Mire használják a pixelgrafikus szerkesztőprogramokat:**
-   A pixelgrafikus képek utólagos módosításához:
	-   Egyes részek átrajzolása
	-   Színek megváltoztatása
	-   Képrészletek cseréje
	-   Eltűntetés
	-   Az alkalmazás szűrőivel végzett módosítások
	-   Retusálás
-   Régen használták képregényfigurák, művészi grafikák és festmények ábrázolásához

### Vektorgrafika
> **vektorgrafika**: központi fogalma az alakzat, más néven geometriai elem. 
> Az alakzatok alaptulajdonságokkal rendelkeznek. Ilyen például a **méret, a hely, a szín, a kitöltési tulajdonságok, az átlátszóság, a körvonal** stb. A vektorgrafikai programok az ábrák elkészítését alakzatok létrehozásával, tulajdonságainak módosításával, célszerű átalakításával és együttes felhasználásával teszik lehetővé

- úgy nagyíthatjuk, hogy pixelesedés nem látható (fontos: térkép, a navigáció, a műszaki terv, egy logó)
- vektorgrafikai eszközök a legtöbb olyan szoftverben rendelkezésre állnak, ahol szükség van grafikai elemekre (pl word, powerpoint)
	-   Irodai programok: *Microsoft Word és PowerPoint, LibreOffice Writer, Impress, Draw*
	-   Speciális célú programok: *GeoGebra, Euklides, Euler3D, Blender*
	-   Önálló vektorgrafikai szerkesztőprogramok: *Inkscape, CorelDraw, Adobe Illustrator*

**SVG fájlok:**
- kód első sora a használt XML verziószámát adja meg, amelyre a böngészőnek van szüksége
- tartalmát az `<svg>` jelölőben adjuk meg

> **Moaré:** óriásplakátokon, a digitális fényképeken, a vonalas és a szabályos mintájú ábrákon megjelenő nem várt mintázatok

## Bemutatókészítés
### Alapok
- **Érvek mellette**
	- könnyebb befogadni képi információt, mint szöveget
	- a vetítés érdekesebbé teheti az előadást
	- hosszabb előadásoknál segítséget jelenthet a vetítőnek
- **Érvek ellene**
	- túlhasználás: szükségtelenül készítünk bemutatót
	- lassú és fájdalmassá válhat

### Előadás felépítése
- **előadás megtervezése**: 
	- előadóra figyeljen a közönség, a bemutató csak segítse az előadást
	- elmondott szöveg vázlatának kidolgozása
- **képeket kísérő szövegek**
	- gyakran nem szükséges szöveget írni
	- hangsúly legyen a képeken
	- hosszabb témáknál egy két szóval segíthető a közönség számára az előadás követése
	- egész mondatokat csak kivételes esetekben pl idézeteknél
	- olyan szöveget írjunk, amit nem olvasunk fel
	- szövegméret mindenki számára látható legyen
- **animációk**
	- nem szükségesek, könnyen lehetnek károsak
	- nélkülük is értelmezhető legyen a dia
- egyéb kiegészítőknél gondoljuk át, valóban **szükségesek-e**
### 

- Vizuális eszközök a szerkezet kialakítására
	- egyes fejezetek diáinál azonos hátteret, amely eltér a többi fejezetétől


### Konklúzió
Az előadásunkat kísérő bemutatók készítésekor
-   használjunk minél nagyobb képeket;
-   ne írjuk ki azt, amit el is mondhatunk;
-   ha mégis írunk, akkor minél kevesebbet;
-   ha úgy érezzük, hogy egy dia zsúfolt, erősen fontoljuk meg a különálló diák használatát;
-   használjunk nagy és jól olvasható formájú betűket;
-   ne olvassuk fel azt, amit kiírtunk, mert zavaró;
-   legyünk szűkmarkúak az animációkkal;
-   legyen tervünk arra az esetre, ha a vetítésre használt gép nem jeleníti meg megfelelően a bemutatónkat (pl pdf)

### Önálló feldolgozásra szánt bemutatók:
- Kisebb képek használata
- Amit elmondanánk azt ki kell írni
- A betűk lehetnek kisebb méretűek
- Hosszabb és bonyolultabb animációk használata sem probléma
- Hivatkozások használata a bemutató szövegeiben
- Médiaelemek használata
- Címdia használata
- Köszönődia használata (érdemes elérhetőséget is írni)
- A bemutató lehet hosszab kiterjedésű is
- A bemutató megértését segítő elemek használata:
	- Vizulális szerkezet kialakítása:
		- egyes fejezetek, témák diáinak azonos háttér
		- új betűtípust az új fejezetekben
		- a bemutatóban előzőleg már megismert képeket – például a fejezetek nyitóképei szerepelhetnek kicsiben a „tartalomjegyzékben”, vagy a fontosabb diák megjelenhetnek újra az összefoglalás részeként
		- fejezetcím a láblécben

## Publikálás a világhálón
### HTML5 alapstruktúra
- első sor tartalmazza a **dokumentumtípust**: `<!DOCTYPE html>`
- következő sorba kerül a `<html>` tag, amely jelzi a böngészőnek, hogy egy HTML-dokumentumról van szó
	- `lang` paraméterben az oldal nyelvét kell megadnia – magyar nyelvű tartalom esetén a `hu` értéket, angol nyelvű tartalom esetén pedig az `en` értéket
- `<title>` tagben az oldal címét kell megadni
A teljes HTML-dokumentum `<html></html>` tartalma a **fejre** `<head></head>` és a **törzsre** `<body></body>` tagolódik
- HTML-címkéket megjelenítés alapértelmezett módja szerint két csoportba lehet osztani (ezeket cssel lehet változtatni)
	- **blokkszintű elemek**: az előző elem alatt, külön blokkban jelennek meg
		- pl `p`, `li`
	- **sorbeli** elemek: soron belül jelennek meg
		- pl `b`, `i`
- soron belüli elemek nem tartalmazhatnak blokkszintű elemeket kivéve `<a>`
- csoportosítóelemek:
	- `<div>` elem egy általános célú, **blokkszintű csoportosítóelem**, az ezzel körbezárt kód új blokkban fog megjelenni
	- `<span>` elem pedig egy általános célú, **sorbeli csoportosítóelem**, pl egy soron belül több karaktert vagy szót ugyanúgy lehet formázni
- bekezdések kialakításához a sorok elejére a `<p>`, a sorok végére a `</p>` taget kell elhelyezni
- hat címsorszintet használhatunk: 
	- legfelső (1-es szintű) címsor `<h1>`
	- alcímsorok `<h2>`, `<h3>`, ...
#### Szövegformázások
- félkövér: `<b>`
- dőlt: `<i>`
- olyan szövegeket emelhet ki, amelyen nagyon fontosak: `<strong>`
- hangsúlyos kiemelésre szolgál: `<em>`
- felsorolás: `<ul>` / számozás: `<ol>`
- listaelem: `<li>`
- sortörés: `<br>`
- kép beillesztés: `<img>`
- `<figure>` és `<figcaption>` (illusztráció)
- hivatkozás: `<a>`
- `<video>` és `<source>`
- `<audio>` és `<source>`

Táblázat:
```html
<table>  
	<caption>cím</caption>  
	<tr>  
		<th>header row</th>
	</tr>  
	<tr>  
	    <td>data</td>
	</tr>
</table>
```

### CSS
- inline (elemközi stílus)
- külön css fájl
- beágyazott `<style>`
CSS-szabály két részből áll:
- **kijelölő** / szelektor: segítségével kijelölheti azokat az elemeket, amelyeket formázni szeretne
	- típus kijelölők, osztály kijelölők (.), azonosító kijelölő (#)
- **deklarációs blokk**: kapcsos zárójelek között helyezkedik el, bennbe **deklarációk** 
	- **tulajdonságok**  és azok **értékei**
- színeket lehet rgb alapján, angol színnevekkel, HTML színkódokkal
<<<<<<< Updated upstream
#### Tulajdonságok öröklődése
- Az egymásba ágyazott `HTML` cimkék között ős-leszármazott kapcsolat áll fenn
- Például a `<body>` tagben található bármelyik elem a `body` tag gyermeke amivel néhány tulajdonságát örökli
- *Öröklődő tulajdonságok:*
	- betűtípus
	- betűméret
	- szín
	- Betűstílus
	- betűvastagság
- *Nem öröklődő tulajdonságok:* 
	- szegély
	- szélesség
	- magasság
#### Kijelölők rangsorolása:
- A megegyező egyedigésű kijelölőknél számít a deklaráció sorrendje, amivel egy előző tulajdonságot felűl tudunk írni pl.: `h1{color : blue;} h1{color : red}`
- Ha a kijelölők egyedisége nem egyenlő akkor az adott elemre a legmagasabb egyediséggel rendelkező selector deklarációja fog érvényesülni
- *Kijelölők rangsora:*
	- típus kijelölés (ez a legalacsonyabb)
	- osztály szintű kijelölés
	- típus és osztály kijelölés együttes használata
	- Kijelölés azonosítóval
	- Típussal és azonosítóval való kijelölés
	- Inline stílus megadás (ez a legmagasabb)
- A sorrendet felül tudjuk írni a `! important` kulcsszóval amivel az adott deklaráció fog érvényesülni minden esetben
- *Használata* `h1 {color : blue ! important}`
#### Blokkszintű és sorbeli elemek:
- *blokkszintű elemek:*
	- Az előző elem alatt kezdődnek
	- Külön blokkot alkotnak
	- *ilyen elemek:*
		- `<p>`
		- `<li>`
		- `<div>`
- *Sorbeli (inline) elemek:*
	- Soron belül jelennek meg
	- Nem alkotnak külön blokkot
	- *ilyen elemek:*
		- `<b>`
		- `<i>`
#### Blokkszintű és sorbeli elemek egyásba ágyazása:
- A blokkszintű elemekbe ágyazhazók:
	- blokkszintű elemek
	- inline elemek
- Az inline elemekbe csak inline elemek ágyazhatók kivétel az `<a>` tag, ebbe ágyazható blokkszintű elem is

#### Csopotosításuk:
- *Blokkszintű elemek csoportosítása:*
	- `<div>` : általános célú blokkszintű csoportosító elem
- *Sorbeli elemek csoportosítása:*
	- `<span>` : általános célú inline csoportosító elem
		- Használata: Egy soron belül több szót vagy karaktert ugyanúgy formázzunk

Dobozmodell:
- *width / height:* 
	- tartalom szélessége / magassága
	- Megadható minimum és maximum magasság is
- *padding:* belső margó (tartalom és szegély között)
- *margin:* szegély és a többi elem közötti térköz
- *CSS-szabvány:* A szebb megjelenítés miatt az egymás alatti blokkoknak az alsó és felső margója összevonásra kerül olyan módon, hogy a nagyobb értékű lép érvénybe
- *border*:
	- Szegély
	- Tulajdonságai:
		- vastagsága
		- stílusa:
			- solid (folytonos)
			- dotted (pontozott)
			- dashed (szaggatott)
			- doudle (dupla)
		- színe
- *border-radius:*
	- Megadja a szegély lekerekítését
	- képpontban vagy százalékban adható meg
- *text-align*
	- szöveg igazítása
	- Beállítása:
		- left (bal)
		- center (közép)
		- right (jobb)
		- justify (sorkizárt)
- *Blokk igazítása:*
	- A `margin` beállításával lehetséges
	- `margin-right: auto` (balra)
	- `margin-left: auto` (jobbra)
	- `margin-left auto; margin-right: auto` (középre)
=======
- méreteket lehet abszolút és relatív mértékkel
- html dokumentumban **hierachikus** felépítés van:
- szülő kapcsolatnál **öröklődnek** bizonyos stílus beállítások:
	- **Öröklődő tulajdonság** például a *betűtípus, a betűméret, a szín, a betűstílus és a betűvastagság*
	- **Nem öröklődik** a *szegély, a szélesség és a magasságbeállítás*
- több kijelölőnél a későbbi lép érvénybe ha megegyezik az egyediségük
	- típus - osztály  - elem + osztály - azonosító - elem + azonosító - inline
	- a `! important` nagyobb prioritást ad
#### Dobozmodell:
- width / height: tartalom szélessége / magassága
- padding: belső margó (tartalom és szegély között)
- margin: szegély és a többi elem közötti térköz
	- szebb megjelenítés miatt az egymás alatti blokkoknak az alsó és felső margója összevonásra kerül olyan módon, hogy a nagyobb értékű lép érvénybe
>>>>>>> Stashed changes

## Táblázatkezelés 
#### Cellák tartalma
- **szám**: 
	- **számformátum**: tizedesjegyeinek száma változtatható a megjelenítésben
	- **százalékformátum**: a szám százszorosát jeleníti meg, és azt a százalék (%) jellel egészíti ki
	- **dátum- és időformátum**: a szám egészrészét dátumként, a törtrészét pedig időként jeleníti meg (1900. január 1 a kezdő)
	- **pénznemformátum**: a számot kiegészíti a pénznem jelével, amely a mértékegységhez hasonlóan jelenik meg
	- **egyéni formátum**
- **szöveg** (mindig balra igazítja)
- **logikai érték** (IGAZ / HAMIS)

#### Cellahivatkozások
> **Relatív cellahivatkozás:** A kifejezés másolásakor a másolás irányának megfelelően módosul
> **Abszolút cellahivatkozás**: A kifejezés másolásakor a cellahivatkozás nem változik, a táblázatkezelő program a cella tényleges helyét tárolja
> **Vegyes** **cellahivatkozás:** A kifejezés másolásakor a cellahivatkozásban az egyik koordináta abszolút, a másik relatív. A koordináta rögzítésétől függően vagy a vízszintes, vagy a függőleges irányú elmozdulásnak megfelelően változik a hivatkozás.

### Függvények
- függvények beszúrását függvényszerkesztő funkció segítifüggvények beszúrását függvényszerkesztő funkció segíti
- újraszámítást magunk is kezdeményezhetjük az F9 gomb megnyomásával
- kategóriák:
	- statisztikai
	- matematikai / trigonometriai
	- dátum és idő
	- logikai
	- keresési és hivatkozási
	- szöveg
	- adatbázis
	- *Pénzügyi, Műszaki vagy Web, stb...*
- cellát /  cellatartományt el lehet nevezni, így könnyebben lehet rájuk hivatkozni függvényeknél
- `...HATÖBB()` függvények esetén a kritériumok között mindig **ÉS** kapcsolat van

## Adatbázis-kezelés
### Alapfogalmak
> **adatbázis:** valóság egy szeletéről szóló ismereteket egymással logikai kapcsolatban álló adattáblákban tároljuk

> **adattáblák**: speciális táblázatok, a táblázat minden oszlopában azonos szerepű értékek találhatók, az egyes sorok értékei összefüggésben, más néven relációban vannak egymással

> **mező**: adattábla egy oszlopa
> **rekord**: adattábla egy sora
> **adat**: a rekord egy mezőjének értéke

>**kulcs**: az a mező (tulajdonság), amelynek értéke meghatározza a rekord többi adatát
- kulcs értéke az oszlopon belül egyedi
> **elsődleges kulcs:** kiválasztott kulcsjelölt
> **összetett kulcs:** több mezőt felhasználva alakítunk ki kulcsot
- egyik mezőt sem választhatjuk önmagában kulcsnak
> **idegen kulcs**: az a mező, amellyel egy másik tábla elsődleges kulcsára hivatkozunk, ezzel teremtjük meg két adattábla egy a többhöz típusú kapcsolatát
> **kapcsolótábla**: az az adattábla, amely két olyan adattáblát köt össze, melyek között több a többhöz kapcsolat van (tábla valamely rekordjához több rekord is tartozhat a másik táblában)
- ennek a két táblának az elsőleges kulcsa a kapcsolótáblában idegen kulcsként jelenik meg

### Adatbázis tervezés
Relációs adatbázis tervezéséhez meg kell határoznunk, mely adatok vannak relációban, azaz összefüggésben egymással.
- **Az azonos csoportba tartozó adatok alkotnak egy adattáblát**
- kell, hogy legyen **legalább egy kitüntetett szerepű tulajdonság,** amelyet **azonosítónak,** más néven **kulcsnak** nevezünk -> az adatsor összes adatát meghatározza
- a kulcs mezőben minden érték pontosan egyszer szerepel, az idegen kulcs mezőben pedig többször is előfordulhat
	- Ha az idegen kulcs mezőben nem lehet ismétlődés, akkor a kapcsolatot egy az egyhez (1:1), ha lehet, akkor egy a többhöz (1:N) típusúnak nevezzük

#### Típusok
| |**Típusnév**|**Magyarázat**|
|:-:|:-:|:-:|
|szöveg|_varchar (n)_|Az _n_ érték a mezőben eltárolható karakterek száma.|
|egész szám|_int_|4 bájtos egész, −231 … 231 − 1 (létezik 1, 2, 3 és 8 bájtos egész is)
|valós szám|_double_|Használata ritkán indokolt, mert általában azonos nagyságrendű, adott tizedesjegy pontosságú számokat tárolunk.
|decimális|_decimal (m, n)_|Az _m_ a szám számjegyeinek száma, _n_ pedig azt adja meg, hogy az _m_ darab számjegyből hány kerül a tizedesjel mögé.
|dátum|_date_|Alakja: YYYY-MM-DD; 1000-01-01 és 9999-12-31 között vehet fel értékeket.
|idő|_time_|Alakja alapvetően: hh:mm:ss.|
|dátumidő|_datetime_|Alakja: YYYY-MM-DD hh:mm:ss.|
|logikai|_tinyint(1)_|Beállításkor boolean-ként adhatjuk meg, de a valóságban egész számként van tárolva; 0 a hamis érték, minden más az igaznak felel meg. Ha a true és a false értékeket használjuk, 1 és 0 kerül rögzítésre.
|számláló|_int auto_increment_|Értéke automatikusan növekszik, nem változtatható.|

#### Joinok
|JOIN|HASZNÁLAT|
|:-:|:-:|
|`INNER JOIN`|metszet|
|`LEFT JOIN`|bal oldali táblába lévőket|
|`RIGHT JOIN`|jobb oldali táblába lévőket|
