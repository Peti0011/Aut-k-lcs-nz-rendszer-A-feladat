Autókölcsönző Rendszer
Projekt leírás

Ez a projekt egy egyszerű konzolos autókölcsönző rendszer Python nyelven megvalósítva.
A program objektumorientált programozási elveket használ, például:

absztrakt osztályok
öröklődés
enkapszuláció
hibakezelés
adatvalidáció

A rendszer lehetővé teszi autók bérlését, bérlések lemondását és az aktuális bérlések listázását.

Fő osztályok
Auto

Absztrakt ősosztály, amely az autók közös adatait tartalmazza:

rendszám
típus
bérleti díj
Szemelyauto

Az Auto osztályból származik.
Személyautók kezelésére szolgál.

További attribútum:

férőhelyek száma
Teherauto

Az Auto osztályból származik.
Teherautók kezelésére szolgál.

További attribútum:

teherbírás
Berles

Egy autó egy napra történő bérlését tárolja.

Tárolt adatok:

autó
dátum
Autokolcsonzo

A kölcsönző működését kezeli.

Feladatai:

autók tárolása
bérlések kezelése
autó bérlése
bérlés lemondása
listázás
Funkciók
Autó bérlése

A felhasználó megadhatja:

az autó rendszámát
a bérlés dátumát

A rendszer:

ellenőrzi a dátum helyességét
ellenőrzi, hogy az autó szabad-e
sikeres bérlés esetén visszaadja az árat
Bérlés lemondása

A felhasználó lemondhat egy meglévő bérlést.

A rendszer:

ellenőrzi, hogy létezik-e a bérlés
törli a bérlést
Bérlések listázása

Megjeleníti az összes aktuális bérlést.

Hibakezelés és validáció

A program kezeli:

hibás dátumformátum
múltbeli dátum
nem létező autó
foglalt autó
nem létező bérlés
Előre betöltött adatok

A program indulásakor:

1 autókölcsönző
3 autó
4 bérlés

automatikusan betöltődik.
