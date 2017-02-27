# Classroom Navigator

##Követelmény analízis

###Feladat célkitűzése

A program célja a felhasználó elnavigálása a kiinduló pozíciótól a kívánt teremig. Főbb feladatok
a kiindulási pozíció és a kívánt cél rögíztése, módosítása, legrövidebb útvonal meghatározása
minél rövidebb idő alatt, felhasználó folyamatos tájékoztatása, felhasználó navigálása.

###Funkcionális követelmények

* A termek adatai adatbáziban tároljuk
* A program indulásakor betölti a tantremek neveit és számait és ezeket elmenti
* Az adatok betöltése után a felhasználónak meg kell adnia a kiindulási pozíciót/termet majd azt a termet ahova el szeretne jutni (termek megadásakor alternatívák javaslása a beírt szöveg alapján)
* Az adatok megadása után a program meghatározza a legrövidebb utat az adott teremig, valmaint részletes leírást ad, hogy melyik ponton merre kell menni. Valamint mennyi lépést kell megtenni a következő pont eléréséig és ezt kilistázza pontonként, ahol a felhasználó áttekintheti az egyes pontokhoz tartozó instrukciókat.
* Mobil alkalmazás esetén: amennyiben a telefonban van giroszkóp, abban az esetben tudjuk számolni a megtett lépéseket, így pontosan tudni fogjuk, hogy mennyi lépést kell megtenni a következő pontig. Amint elértük a következő pontot akkor a program megadja a következő pont eléréséhez szükséges instrukciókat
* Webes alkalmazás esetén: pontokra bontva részletes leírást ad, hogy melyik ponton merre kell haladni a következő pontig valamint, hogy hány méterre van és a becsült idő amíg eléri a következőt

###Nem funkcionális követelmények

* Ergonomikus elrendezés, felhasználóbarát felület
* Könnyen megérhető és elsajátítható működés
* Könnyen karbantarthatóság és bővítehetőség
* Gyors működés
* Egyértemlű hibajelzés
* A funkciók mindig elérhetőek és végrehajtódnak
* Adatok bevitelének ellenőrzése, csak helyes adatokat fogad el
* Az indítás hosszabb időt vehet igénybe

###Use-case diagram
![][use_case]

###Vázlatok
####Mobil alkalmazás
![][phone_home]
![][phone_search]

####Weboldal
![][web_page]

[use_case]: Images/nomnoml_use_case.png
[phone_home]: Images/home_page.png
[phone_search]: Images/navigation_page.png
[web_page]: Images/web.png
