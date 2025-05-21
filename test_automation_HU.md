# Tesztautomatizálási kérdések

## Tesztelési alapok (ISTQB-hez kapcsolódó)
<img src="https://www.mindsmapped.com/wp-content/uploads/2016/06/ISTQB.jpg" alt="image" width="300" height="220">

#### ✅ Mi a tesztelés célja? Mi nem az?
Cél: Hibák megtalálása, minőség biztosítása, követelmények ellenőrzése.
Nem az: Nem csak hibakeresés, és nem helyettesíti a jó fejlesztést.
#### ✅ Mik a tesztelési alapelvek?
A tesztelés hibák jelenlétét mutatja.
Teljes tesztelés lehetetlen.
Korai tesztelés hasznos.
Hibák általában koncentrálódnak.
Ugyanaz a teszt kevés új hibát talál.
A tesztelés környezetfüggő.
Hibamentes ≠ hasznos termék.
#### ✅ Mi az egységtesztelés (unit testing)? Ki felelős az egységtesztek írásáért?
Egységtesztelés: Egyéni függvények vagy modulok tesztelése.
Felelős: A fejlesztő.
#### ✅ Mik a tesztszintek, és mi a különbség köztük?
Egységteszt – Egyes kódrészek.
Integrációs teszt – Modulok együttműködése.
Rendszerteszt – Teljes rendszer.
Elfogadási teszt – Üzleti igények, felhasználó által.
#### ✅ Mi a különbség a verifikáció és a validáció között?
Verifikáció: Jól csináljuk a terméket?
Validáció: A megfelelő terméket csináljuk?
#### ✅ Mik a tesztelési típusok, és mi a különbség köztük?
Funkcionális: Mit csinál a rendszer.
Nem-funkcionális: Hogyan (pl. teljesítmény).
Manuális: Kézzel végzett tesztelés.
Automatizált: Eszközzel futtatott teszt.
#### ✅ Mi a különbség a fehér doboz, szürke doboz és fekete doboz tesztelés között?
Fehér doboz: Belső kód ismert.
Fekete doboz: Csak bemenet és kimenet ismert.
Szürke doboz: Részleges ismeret.
#### ✅ Mi a különbség a felhasználói elfogadási teszt (UAT) és a rendszerteszt között?
UAT: Felhasználó tesztel, üzleti igények alapján.
Rendszerteszt: Tesztelők végzik, teljes rendszer funkcionalitására.
#### ✅ Sorolj fel különbségeket a regressziós tesztelés, a füsttesztelés és az újratesztelés között!
Típus	Mikor használjuk?
Regresszió	Ellenőrizzük, nem romlott-e el semmi.
Füstteszt	Alapfunkciók gyors ellenőrzése.
Újrateszt	Egy konkrét hiba javítását ellenőrizzük.
#### ✅ Mi a különbség a statikus és dinamikus tesztelés között?
Statikus: Kód futtatása nélkül (pl. kódreview).
Dinamikus: Kód futtatásával történik (pl. manuális vagy automatizált tesztek).
### ✅ Hasonlítsd össze a V-modellt, a vízesés modellt és az Agile megközelítést a tesztelés szempontjából!
V-Modell
Tesztelés időpontja: Fejlesztéssel párhuzamosan.

Előnyök: Strukturált, korai tesztelés.

Hátrányok: Merev, nehezen alkalmazkodik változásokhoz.

Vízesés Modell
Tesztelés időpontja: Fejlesztés után.

Előnyök: Könnyen követhető.

Hátrányok: Késlekedés a hibák felfedezésében, nem rugalmas.

Agile Modell
Tesztelés időpontja: Folyamatosan, minden iterációban.

Előnyök: Rugalmas, gyors visszajelzés.

Hátrányok: Erőforrás igényes, ha nincs megfelelő csapat.

<img src="https://t4.ftcdn.net/jpg/03/90/15/65/360_F_390156585_8w1lsOyICIAOvDCU8tExXW2QwLCOFwXD.jpg" alt="image" width="550" height="400">


<img src="https://i.imgur.com/S38EBJw.png" alt="image" width="550" height="400">   <img src="https://segedletek.level14.hu/assets/img/modszertan-vizeses.svg" alt="image" width="550" height="400">


<img src="https://promanconsulting.hu/wp-content/uploads/2022/03/agilis-modszertanok-optimized.jpg" width="550" height="400">





## Reporting, Bugs
<img src="https://moolya.com/blog/wp-content/uploads/2023/05/Bug-Report.png" alt="image" width="300" height="220">

#### ✅ Milyen lépéseket követnél egy hiba megtalálásakor?
Reprodukálás – Ellenőrzöm, hogy újra előidézhető-e.
Dokumentálás – Jegyzetelem a lépéseket, környezetet, eredményt.
Rögzítés – Hibajelentés írása (pl. Jira-ban).
Prioritás meghatározás – Súlyosság és üzleti hatás alapján.
Kommunikáció – Fejlesztők értesítése, együttműködés a javításban.
Újratesztelés – Hibajavítás után tesztelem újra.
Regressziós teszt – Ellenőrzöm, hogy máshol nem okozott-e új hibát
#### ✅ Beszélj a gyakori tesztjelentésekről és részleteikről!
Tesztterv: Milyen teszteket végzünk, hogyan és mikor.
Napi/havi státuszjelentés: Folyamatban lévő tesztek, hibák száma, haladás.
Hibaösszegző riport: Nyitott, javított és új hibák listája.
Teszt lefedettségi jelentés: Mely követelmények lettek letesztelve.
Végső tesztjelentés: Teljes tesztelési eredmény, sikeres és sikertelen tesztek.
#### ✅ Mit tartalmaz egy hibajelentés?
Cím: Rövid, lényegre törő.
Lépések a hiba előidézéséhez.
Várt eredmény vs Tényleges eredmény.
Képernyőkép vagy log (ha van).
Környezeti információk: OS, böngésző, verziók.
Súlyosság és prioritás.
Állapot (új, folyamatban, javítva, lezárt).
Tesztelő neve.
#### ✅ Hogyan rangsorolnál egy hibát?
Súlyosság (Severity): Mennyire súlyos technikailag?
Critical: rendszerleállás
Major: fő funkció nem működik
Minor: kis hiba, nem akadályozó
Trivial: esztétikai vagy elírás
Prioritás (Priority): Mennyire sürgős a javítás?
High: azonnali javítást igényel
Medium: fontos, de nem sürgős
Low: később is javítható
## Test Automation, Selenium
<img src="https://media.licdn.com/dms/image/C4D12AQE3GOyVsZazOw/article-cover_image-shrink_600_2000/0/1583830696602?e=2147483647&v=beta&t=bYHbKyhMoWsMgtEug6eSf3m0db5ZtGEl437TeS1qkfI" alt="image" width="320" height="220">

#### ✅ Melyik teszteseteket érdemes automatizálni és melyiket nem?
Automatizálni érdemes:
Repetitív tesztek (pl. regisztrációs folyamat).
Kritikus funkciók, amelyek gyakran változnak.
Regressziós tesztek, ahol nem szeretnénk manuálisan újra lefuttatni mindent.
Teljesítmény tesztek, ahol nagy adatmennyiségre van szükség.
Nem érdemes automatizálni:
Egyedi tesztek, amelyek nem ismétlődnek.
Magas költségű fejlesztésű tesztek, ha a tesztelés nem térül meg.
UI tesztek, amelyek gyakran változnak, ha nem stabil a felület.
#### ✅ Írj le egy jó automatizált tesztet!

#### ✅ Mi a Selenium, Selenium IDE és Selenium WebDriver?
Selenium: Nyílt forráskódú tesztelési eszköz webalkalmazások automatizálására.

Selenium IDE: A Selenium grafikus felületű eszköze, amely segít automatizált tesztek rögzítésében és lejátszásában, de nem túl rugalmas és csak Firefoxra és Chrome-ra elérhető.

Selenium WebDriver: A Selenium programozható interfésze, amely több böngészőt (pl. Chrome, Firefox) képes irányítani és lehetővé teszi a részletesebb automatizálást.
#### ✅ Hogyan lehet azonosítani a webes elemeket?
ID: Az egyedi azonosító, amely a legjobb módszer.

Name: Az elem neve (pl. form mezők).

Class: Az osztálynév.

Tag Name: HTML tag (pl. <input>).

XPath: Az elem elérési útja a DOM-ban.

CSS Selector: Stílusok alapján történő azonosítás.
#### ✅ Hogyan lehet várni az elemekre, és mi lehet a probléma? Gyűjtsd össze a lehetséges hibákat és okokat!
Implicit Wait: Minden elem keresése előtt vár egy bizonyos időt.
Explicit Wait: Várakozás specifikus elemekre egy adott feltétellel.
Lehetséges hibák:

Túl rövid várakozási idő – Az oldal nem töltődött be teljesen.

ElementNotVisibleException – Az elem nem látható a képernyőn.

TimeoutException – Az elem nem jelenik meg a várt időn belül.

StaleElementReferenceException – Az elem már nem elérhető, mert az oldal frissült.

#### ✅ Hasonlítsd össze a POM és a Keyword Driven Testing megközelítéseket!
POM (Page Object Model)	Keyword Driven Testing
Minden oldal egy külön osztályban van, amely az oldalon lévő elemeket és interakciókat tartalmazza.	A tesztek kulcsszavak segítségével vannak leírva, amelyek az üzleti logikát tükrözik.
Jobb karbantarthatóság és olvashatóság.	Könnyen tanulható, de kevésbé karbantartható.
Kód és tesztelés szétválasztása.	Az üzleti szakemberek is könnyen írhatnak teszteket.
#### ✅ Mi a különbség a TDD és BDD között?
TDD (Test-Driven Development): Tesztek írása a kód megírása előtt. A teszt az elvárt viselkedést írja le.

BDD (Behavior-Driven Development): Tesztelés, amely a felhasználói történetekre és üzleti viselkedésre összpontosít, gyakran Given-When-Then formában.
#### ✅ Mi az API tesztelés és miért hasznos?
API tesztelés: Az alkalmazásprogramozási interfészek (API) tesztelése, hogy ellenőrizzük azok működését, teljesítményét és biztonságát.
Miért hasznos?:

Segít biztosítani, hogy az alkalmazás backend rendszerei hibamentesen kommunikálnak.

Tesztelhetők az adatátviteli sebességek és a hibakezelés.
#### ✅ Mi az adatvezérelt tesztelés és miért hasznos?
Adatvezérelt tesztelés: A tesztet különböző adatfájlokkal (pl. Excel, CSV) futtatjuk, hogy ugyanazt a tesztet többféle adatkombinációval végezhessük el.
Miért hasznos?:

Nagy mennyiségű adatot tesztelhetünk egyszerűbben.

Segít a különböző bemenetek és azok hatásainak tesztelésében.



url: https://chatgpt.com/