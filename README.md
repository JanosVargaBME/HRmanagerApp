# IN PROGRESS....
# HRmanagerApp
HR Manager application with Blazor and ASP.NET

## Feladat

Egy olyan alkalmazás készítése, amelyben fel lehet cégeket és általános munka pozíciókat venni, illetve le lehet adni jelentkezésként önéletrajzokat. Majd a program egy algoritmus segítségével előállítja a beosztásokat, amely lementhető táblázatos formában.

## A kisháziban elérhető funkciók

- Cégek adatainak feltöltése, cégek törlése
- Pozíciók adatainak feltöltése, pozíciók törlése
- Önéletrajz feltöltés, módosítás, törlés - szöveges formátumó, amely tartalmazza a megjelölt cégeket és pozíciókat is
- Az algoritmus véletlenszerűen osztja be a jelentkezőket
- Az összepárosítások lementhetőek CSV formátumban, amely könnyen importálható excel-be is

## Adatbázis entitások

- Cég
- Pozíció (állás)
- Önéletrajz
- Párosítás

## Alkalmazott alaptechnológiák

- adatelérés: Entity Framework Core v6
- szerveroldal: ASP.NET Core v6
- kommunikáció: JSON segítségével
- kliensoldal: Blazor WebAssembly

## Továbbfejlesztési tervek

- Azure-ban való hosztolás
- Autentikáció megvalósítása
- Titkosított kommunikáció a szerver és kliens között
- Értelmes párosító algoritmus megvalósítása
