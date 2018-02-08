# grafika
Grafika házik - 2017 ősz

1. feladat
Készítsen programot, amely három kattintással bevitt pontra egy háromszög éleit rajzolja ki fehérrel egy olyan 2D geometriában, ahol a görbületeket egy tórusz felülete definiálja (a látható négyzetet tekintsük a tórusz paraméterterének, ahol két pont távolsága azon legrövidebb út, amit a tórusz felületén a két megfelelő pont között kell megtenni). A program háttérként a Gauss görbületet mutatja be, pozitív értékeket pirossal, a negatívokat zölddel. A háromszög oldalai egyenesek, azaz az adott geometriában a legrövidebb utak. Az utakat közelíthetjük másodfokú függvényekkel, pl. három kontrolpontos Bézier görbével. 
A háromszög szögeinek összegét printf-fel írja ki a sztenderd outputra. 
A specifikációban nem rögzített tulajdonságok szabadon megválaszthatók.

2.feladat
Egy véges magasságú, diffúz + spekuláris textúrázott henger belsejében szemlélődünk. A henger alakú szoba a látóterünkben még három optikailag sima, egymásba fonódó, darabonként max 40 háromszögre tesszellált, azaz „baltával faragott” tóruszt tartalmaz, az egyik arany, a másik üveg, a harmadik pedig ezüstből van. A tóruszok tengelyei nem párhuzamosak egyik koordinátatengellyel sem. A színteret három, nem fehér fényforrás világítja meg és ambiens fény is észlelhető. Számítsa ki a látható képet sugárkövetéssel és jelenítse meg a képernyőn egy textúrázott téglalapként:
Optikailag sima arany (n/k: 0.17/3.1, 0.35/2.7, 1.5/1.9 )
Optikailag sima üveg: (n/k: 1.5/0, 1.5/0, 1.5/0)
Optikailag sima ezüst (n/k: 0.14/4.1, 0.16/2.3, 0.13/3.1)
A szoba textúrája és diffúz/ambiens visszaverési együtthatói szabadon megválaszthatók. A fényforrások helye és intenzitása úgy választandó, hogy a kép szép és élvezhető legyen.

