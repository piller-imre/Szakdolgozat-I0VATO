# Szakdolgozat

cím: _JavaScript technológiák összehasonlítása_

## Bevezetés

* Elég csak a végén.
* Témakört nagyjából betájolni.
* Át kell tekinteni, hogy mire számíthat majd az olvasó.

## JavaScript keretrendszerek

* Témakört pontosan megadni.
* MVC (komplex-es dokumentumból)
* Hogyan alakult ki, hogy pont a JavaScript legyen?
* Mi a különbség a JavaScript és ECMAScript között?
* TypeScript, CoffeScript, Clojure (JS) és hasonlók, legalább említés szintjén.
* JavaScript implementációk (rövid áttekintéssel, hivatkozásokkal)
* HTML5, DOM, jQuery -> DOM manipuláció
* SPA

## Mintapélda

* Az a példa, ami majd a jelentős keretrendszerekben implementálásra kerül.
* Legyen benne CRUD, fájlkezelés, REST API támogatást jól be lehessen rajta mutatni, template-ek (inkább többféle, de nem kell sok), routing.

### A mintapélda fő elemei

A specifikációban a következőknek kellene szerepelni valamilyen formában.

Megrendelő szemszögéből leírni, hogy mit kellene tudnia az alkalmazásnak.

* CRUD megvalósítása
* REST API, resource kezelés (a backend az kötött)
* Útvonalak, routing megvalósítása, állapotkezelés (A nem REST jellegű változatokra kellene itt kitérni), Felhasználóbarát URL-ek
* Template-ezés, változók megadása, kezelése, vezérlési szerkezetek, szűrők/direktívák, pl.: dátumok megjelenítése, nyers adatok kiírása, egyszerűbb formázások
* Menük, lapok megvalósítása (DOM-al és úgy HTML-el való illeszkedés vizsgálatáról van inkább szó.), Ez gyakorlatilag az MVC View részére vonatkozik.
* Form-ok létrehozása, validálása
* DOM manipuláció
* Fájlok, képek feltöltése. Feltöltési állapot jelzése
* Authentikáció
* Többnyelvűsítés

Ahol a specifikációban kényelmetlennek tünne, hogy többféle megoldás szerepeljen, ott elég csak az implementációban kezelni külön. Például az útvonalak megadásánál lehet REST-es és metódusnév jelletű routing.

(A későbbiekben mindegyik esetében lehet emlegetni kiegészítő, kvázi szabványos modulokat is.)

## Összehasonlító táblázat

* Egy nagy táblázatba összeszedni, hogy mik a konkrétan megvalósítandó/összehasonlítandó dolgok.
* Sorokba kerülnek a keretrendszerek, oszlopokba a funkciók/feature-ök.

## AngularJS

* Története, verziók, fő jellemzői (featúrák)
* Előnyök, hátrányok
* AngularJS 1, Angular 2, Angular 4

## ReactJS

* Saját template-ező nyelv bemutatása
* Virtual DOM

## ...

## Fejlesztőeszközök

* NPM
* Szerkesztők: Sublime, NotePad++, Visual Studio Code, GitHub Atom, WebStorm
* JavaScript-es kódkiegészítés (a problematikáját is érdemes magyarázgatni; dinamikus nyelv, gyengén típusos)
* Tesztkörnyezetek (pl.: Jasmine)
* Build eszköz: Gulp, Grunt
* Csomagkezelők: Bower
* Mindegyiknél lehet több alternatíva is.
* A JS alkalmazások telepítését és konfigurálását is érdemes részletezni (amalgenizálás, obfuscation, minimalizálás, source maps)

## Összehasonlító elemzés

* Összehasonlító táblázatok, timeline-ok, teljesítményvizsgálat, népszerűség (pl.: google találatok száma), kódméret, támogatottság (pl. új verziók, hibajavítások), elérhető irodalmak.
* Megnézni minél több "vs" jellegű leírást, például "AngularJS vs ReactJS".
* API minősége, olvashatóság, karbantarthatóság
* Dokumentáltság, tesztlefedettség
* Külső függőségek száma
* Konvenciók (kódolási, elnevezési, struktúrális, dokumentálási esetleg tesztek)

## Összegzés

* Mi került a dolgozatba.
* Rövid értékelés ezekkel kapcsolatban.
* További tervek, ötletek

## Hivatkozások

* Webböngészővel, szkriptekkel kapcsolatos irodalmak
* NodeJS
* AngularJS: hivatalos oldal, tutorial, könyvek
* ReactJS
* BackboneJS
* Vue
* EmberJS
* ...
* CRUD
* REST API

