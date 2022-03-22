# Additív gyártás
Faragó Péter
peter.farago@lang3d.com

számonkérés:
- zh1 - 7. hét
- zh2 - 13. hét
- pótzh - 14. hét

szoftverek:
- [fusion 360](https://www.autodesk.hu/products/fusion-360/overview)
- [octoprint ](https://octoprint.org/)

## bevezetés
- szuvtraktív: mikor elávolítjuk az anyagot: forgácsolás
- formatív: hajlítás, öntés: fröccsöntés
- additív: mikor hozzáadjuk az anyagot

anyagok:
- PLA: 140 év után lebomlik, kukorica alapú
- ABS: 110-200 C fok körülig bírja, van egy lágyulási pontja, cianid alapú összetevője miatt nem természetbarát
- TPU: termoplasztik 130C fok alatt rugalmas, 130-150 között felhabosodik: *pl szűrőnek*

## szeletelés
- minnél vastagabb a réteg annál erősebb
- minél vékonyabb annál részletgazdagabb

ezért fdm nyomtatónál érdemes a minta szélére kitenni a mintát

multijettinggel egy nyomtatás alatt képesek vagyunk növelni a hőfokot, változtatni a színen, és az állagon is

olvasztott anyagot mindig eggyel jobban megmelegítjük mint amilyen közegben használva lesz

# EA2
## FDM nyomtató
*ajánlott az amelyiknek a tálca mozog maximum Z irányban, a fej mozog X/Y iráynban*

![FDM nyomtató](https://www.researchgate.net/profile/Wenyao-Xu/publication/328324778/figure/fig2/AS:682531510829056@1539739601237/The-mechatronic-structure-of-an-FDM-3D-printer-with-inevitable-variations-arising-from.ppm)

# EA3
tintasugaras nyomtató elvű felépítés
komoly alapanyagtechnológia.: folyékony, szobahőmérsékleten mégis szilárd. UV fény hatására szilárdul.

## Alapanyag sugaras felrakás
Már a '90-es években 60 mikrométeres pontossággal képesek nyomtatni. Jelenleg már színesen is lehet nyomtatni vele. Anyagtól függően fél-egy éven belül el kell használni.  

## kötőanyag felrakás
Ez az SLS és az alapanyag keveréke. Egy porágyban a lézer egy kötőanyagot tesz be. Itt is van lehetőség 16 millió szín elérésére akár. 

Maga az alap termék nem erős. Kissé gipszes jellegű. Por részecskéket ragasztóval ragszt össze. A végtermék törékeny. 

A fém port ki lehet színterezni: hő hatására a felesleges részeket ki lehet olvasztani. A térfogatából ekkor veszít, de tovább színterezve összeragaszthatóak a részecskék. Egy elérhetőbb árú fémnyomtatás. 

Nem kell annyira finom por mint az SLS technológiánál. Olcsón könnyen lehet nyomtatni. Általános tárgyakhoz anynira nem megfelelő.

## Laminált gyártás
Előre legyártott papír/fa/fém/kerámia lemezeket helyezünk egymásra
- sok hulladékkal energiahatékony eljárás. Egy teljes réteghez itt nem kell a teljes felületet bejárni, elég csak az élek mentén. Akár hőbevitellel csak összeolvaszthatóak is a rétegek. Energiagazdaságos.

Ez egy hegesztés szerű eljárás, így nem árt ha heggesztés közben nem kerül be oxigén, tehát a gépek innergázos környezetben működnek vagy vákumban.

## Közvetlen energiabeviteles nyomtatás
Egy robotkarra tesszük a fejet és egy lézer sugárba szórjuk a port ami megolvad az adott ponton.
hasonlít az öntött vas alakatrészekhez. Nagyon porózus kell elgyen a végeredmény. 

Rozsdamentes, martenzites aacélokat/titánt/wolfram/tantal/réz/bronz lehet nyomtatni vele. *Hajócsavarokat* is gyártanak belőle. Nagyon gazdaságos.

# 3D nyomtató választás
- fokozatokban érdemes gondolkodni
- követelmények a termékkel szemben
- minősített anyagok a nyomtatóhoz és a termékhez is egyszerre

### fájlformátumok
STL helyett [3MF](https://blog.grabcad.com/blog/2020/04/21/3mf-vs-stl-file-types/)

### STL
- a háromszögeknek van iránya is

![STL fájl működése](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a6/The_differences_between_CAD_and_STL_Models.svg/1024px-The_differences_between_CAD_and_STL_Models.svg.png)

Smart materials:
- shape-memory alloy (SMA)
- shape-memory polymer (SPM)
- piezolectric
- [solid liquid](https://www.youtube.com/watch?v=jcwYFBeetH0)

**Topológia optimalizáció:** kiindul egy termékből amit aztán 



