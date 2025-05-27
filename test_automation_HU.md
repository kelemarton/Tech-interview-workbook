# Tesztautomatizálási kérdések

## Tesztelési alapok (ISTQB-hez kapcsolódó)
<img src="https://www.mindsmapped.com/wp-content/uploads/2016/06/ISTQB.jpg" alt="image" width="300" height="220">

#### ✅ Mi a tesztelés célja? Mi nem az?
# Célja a szoftver követelményeinek ellenőrzése, valamint hibák keresése és javítása.

#### ✅ Mik a tesztelési alapelvek?
# A tesztelés nem tudja bizonyítani hogy a softver hibamentes és hogy a tesztelés exponenciálisan növekvő idő- és erőforrásigényű.

#### ✅ Mi az egységtesztelés (unit testing)? Ki felelős az egységtesztek írásáért?
# Az egységtesztelás az a folyamat, amely alatt a szoftvernek csak egyetlen egységét teszteljük. Az egységtesztelésért általában a fejlesztők felelősek.

#### ✅ Mik a tesztszintek, és mi a különbség köztük?
# A tesztszintek teszttevékenységek olyan csoportjai, amelyeket együtt szerveznek és kezelnek.

#### ✅ Mi a különbség a verifikáció és a validáció között?
# A verifikáció ellenőrzi, hogy a szoftver megfelel-e a specifikációnak, míg a validáció ellenőrzi, hogy a szoftver megfelel-e a felhasználók elvárásainak.

#### ✅ Mik a tesztelési típusok, és mi a különbség köztük?
# A tesztelési típusok kategóriák, amelyekbe a tesztek besorolhatók, pl. funkcionális, nem funkcionális, fehér dobozos, fekete dobozos. A különbség az, hogy más-más szempontokat vizsgálnak.

#### ✅ Mi a különbség a fehér doboz, szürke doboz és fekete doboz tesztelés között?
# A fehér doboz tesztelés során a tesztelő ismeri a kód belső működését, a szürke doboz tesztelés során részleges ismeretekkel rendelkezik, míg a fekete doboz tesztelés során semmilyen ismeret nincs a kód belső működéséről.

#### ✅ Mi a különbség a felhasználói elfogadási teszt (UAT) és a rendszerteszt között?
# A felhasználói elfogadási teszt ellenőrzi, hogy a rendszer megfelel-e a felhasználói igényeknek, míg a rendszerteszt a rendszer teljes működését vizsgálja, beleértve a funkcionális és nem funkcionális követelményeket is.

#### ✅ Sorolj fel különbségeket a regressziós tesztelés, a füsttesztelés és az újratesztelés között!
# A regressziós tesztelés ellenőrzi, hogy a korábban működő funkciók továbbra is működnek-e. A füsttesztelés az gyors, felszínes tesztelés, amely ellenőrzi, hogy a rendszer alapvetően működik-e. Az újratesztelés pedig ismétli a teszteléseket, amely ellenőrzi, hogy a korábban hibás funkciók már működnek-e.

#### ✅ Mi a különbség a statikus és dinamikus tesztelés között?
# A statikus tesztelés a kód vizsgálata sprint nélkül, a hibák és problémák keresése. A dinamikus tesztelés a kód futtatása és vizsgálata, hibák és problémák keresése.

#### ✅ Hasonlítsd össze a V-modellt, a vízesés modellt és az Agile megközelítést a tesztelés szempontjából!
# A vízesés modellben a tesztelés csak a fejlesztési tevékenységek befejezése után kezdődik. A V-modellben a tesztelés korábban kezdődik, és integrálva van a fejlesztési folyamattal. Az Agile megközelítésben a tesztelés folyamatos, párhuzamosan a fejlesztéssel.

<img src="https://t4.ftcdn.net/jpg/03/90/15/65/360_F_390156585_8w1lsOyICIAOvDCU8tExXW2QwLCOFwXD.jpg" alt="image" width="550" height="400">


<img src="https://i.imgur.com/S38EBJw.png" alt="image" width="550" height="400">   <img src="https://segedletek.level14.hu/assets/img/modszertan-vizeses.svg" alt="image" width="550" height="400">


<img src="https://promanconsulting.hu/wp-content/uploads/2022/03/agilis-modszertanok-optimized.jpg" width="550" height="400">

## Reporting, Bugs
<img src="https://moolya.com/blog/wp-content/uploads/2023/05/Bug-Report.png" alt="image" width="300" height="220">

#### ✅ Milyen lépéseket követnél egy hiba megtalálásakor?
### Elsőnek is rögzíteném a hibát a hibajelentésben, majd megpróbálom reprodukálni és dokumentálni a lépéseit. Összehasonlítom a kívánt eredményt a hiba eredményével és meghatározom annak javításának fontosságát.

#### ✅ Beszélj a gyakori tesztjelentésekről és részleteikről!
### A tesztjelentések a tesztelési tevékenységek állapotáról és eredményeiről tájékoztatnak. Két részre oszthatjuk:
- ### Tesztelőrehaladási jelentés
  - Ez rendszeresen készül a projekt során, bemutatva az aktuális státuszt, a haladást gátló tényezőket és a tesztobjektum minőségét.
- ### Összefoglaló tesztjelentés
  - A tesztelési fázis végén összegzi a teljes folyamatot, az eltéréseket, a kockázatokat és a termékminőséget.


#### ✅ Mit tartalmaz egy hibajelentés?
- ### Egyedi azonosító vagy cím
- ### Hiba rövid leírása
- ### Hiba dátuma
- ### Hiba megtalálójának a neve
- ### futtatási környezet
- ### Reprodukálásának részletes leírása
- ### Elvárt eredmény és a hiba eredménye
- ### Hiba fontossága
- ### Hiba állapota (Lezárt vagy Aktuális)

#### ✅ Hogyan rangsorolnál egy hibát?
- ### Súlyosság szerint: Jelzi, hogy a hiba milyen súlyossággal befolyásolja a szoftver működését.
- ### Prioritás szerint: Jelzi, hogy a hibát milyen sűrgősen kell kijavítani.


## Test Automation, Selenium
<img src="https://media.licdn.com/dms/image/C4D12AQE3GOyVsZazOw/article-cover_image-shrink_600_2000/0/1583830696602?e=2147483647&v=beta&t=bYHbKyhMoWsMgtEug6eSf3m0db5ZtGEl437TeS1qkfI" alt="image" width="320" height="220">

#### ✅ Melyik teszteseteket érdemes automatizálni és melyiket nem?
- ### Érdemes:
  - Gyakran ismétlődő tesztek
  - Nagy adatmennyiséggel dolgozó tesztek
  - Időigényes vagy Bonyolult tesztek
  - Stabil funkcionalitást lefedő tesztek
  - Smoke tesztek (Kritikus üzleti folyamatok és alapvető funkciók)
- ### Nem Érdemes:
  - Ritkán vagy Egyszer futatott tesztek
  - Gyakran változó tesztek
  - Szubjektív tesztek (Pl. Vizuális élény, felhasználói élmény)
  - Felderítő tesztek
  
#### ✅ Írj le egy jó automatizált tesztet!
### -|-

#### ✅ Mi a Selenium, Selenium IDE és Selenium WebDriver?
- A Selenium egy népszerű, nyílt forráskódú library, amit elsősorban webalkalmazások automatizált tesztelésére használnak.
- A Selenium IDE egy böngészőbe épülő eszköz, amivel egyszerűen lehet teszteket rögzíteni és visszajátszani. Főleg ismétlődő tesztek automatizálására használt.
- A Selenium WebDriver egy aPI, ami lehetővé teszi, hogy különböző programozási nyelvekben írjunk tesztszkripteket, amik közvetlenűl vezérlik a böngészőt.

#### ✅ Hogyan lehet azonosítani a webes elemeket?
### Meg kell mondani a szkriptnek, hogy melyik gombra kattintson, vagy hova írjon. Ezt lehet ID, név, CSS class, vagy akár a link szövege alapján. Az XPath egy összetettebb, de mindent megtaláló módszer.

#### ✅ Hogyan lehet várni az elemekre, és mi lehet a probléma? Gyűjtsd össze a lehetséges hibákat és okokat!
### A weboldal elemei nem mindig egyből töltődnek be vagy nem interaktívak. A Selenium library ezekre a problémákra több várakozási és kezelési mechanizmust biztosít.

#### ✅ Hasonlítsd össze a POM és a Keyword Driven Testing megközelítéseket!
### Mindkettő célja az automatizált scriptek karbantartása, de más szempontból közelítik meg:
- POM: Itt minden weboldalhoz egy külön osztály tartozik, ami tartalmazza az elemekhez tartozó adatokat.
- KDT: A teszteseteket kulcsszavak sorozataként definiálják. Ezek mögött egy függvény áll, ami az adott műveletet végrehajtja.

#### ✅ Mi a különbség a TDD és BDD között?
### Mindkettő olyan fejlesztési gyakorlat, ahol a tesztírás megelőzi a kódírást.
- TDD (Tesztvezérelt fejlesztés): Célja a robosztus, jól tesztelt kód.
- BDD (Viselkedésvezérelt fejlesztés): Célja a szoftver az üzleti elvárásoknak megfelelően viselkedjen.

#### ✅ Mi az API tesztelés és miért hasznos?
### Az API tesztelés során az alkalmazás API végpontjait teszteljük közvetlenül, így az alkalmazás különböző komponensei közötti kommunikációt és adatcserét ellenőrizzük. Előnyei:
- Korai hibafelismerés
- Gyorsabb és hatékonyabb
- Stabilabb és könyebben karbantartható
- Lehetővé teszi a háttérrendszerek tesztelését
- Szélesebb körű lefedettség

#### ✅ Mi az adatvezérelt tesztelés és miért hasznos?
### Az adatvezérelt tesztelés egy automatizálási stratégia, ahol a tesztszkript végrehajtási logikája elválik a tesztadatoktól (bemenetek és elvárt kimenetek). Előnyei:
- Növeli a tesztlefedettséget
- Könnyíti a tesztadatok karbantartását
- Csökkenti a redundáns szkriptek számát