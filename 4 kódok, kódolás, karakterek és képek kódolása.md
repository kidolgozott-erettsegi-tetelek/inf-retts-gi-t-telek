# Kódok és kódolás, karakterek és képek kódolása

Informatika az **információ**:

- megszerzésével
- feldolgozásával
- tárolásával

foglalkozik.

## Kód

Jelek vagy szimbólumok rendszere.

Segítségükkel valamely információ egyértelműen közölhető.

## Adatok a számítógépen

Információ legkisebb egysége a karakter (betűhely).

Betűk, számjegyek és írásjelek lehetnek karaketerek.

Az információ legkisebb, **önállóan értelmes** egységét elemi adatnak nevezzük.

Az elemi adat megjelenési formái:

| Név                                   | Példa             |
| ------------------------------------- | ----------------- |
| Szám                                  | 1, 2, 3, 4 ..., 9 |
| Szöveg (számokkal nem lehet számolni) | a, d, c, 9, 3     |
| Írásjelek                             | . , - ; ...       |
| Műveleti jelek                        | +, -, \*, /, ^    |
| Speciális karakterek                  | %, ",# , &, @     |
| Logikai adat                          | igaz, hamis       |

## Karakteres adatok tárolása

A számítógép csak számokat ismer, így ha karaktereket akarunk mi emberek, számokhoz kell azokat rendelni.

Íme, néhány ilyen számhoz-rendelés (karakterkódolási szabvány):

- ASCII (7 vagy 8-bites, alap latin betűk, ékezeteket nem tartalmaz)
- ISO 8859-x (8-bites, nemzetcsopotonként más számozást használ, magyar: ISO 8859-2)
- Unicode (legtöbbet használt, legnépszerűbb a 8-bites UTF-8, de létezik 16 és 32 bites változat)

## Képek kódolása

| Kódolás neve  | Műdökési elv                                    | Előnyök                                                                    | Hátrányok                                           | Használat                    |
| ------------- | ----------------------------------------------- | -------------------------------------------------------------------------- | --------------------------------------------------- | ---------------------------- |
| Pixelgrafika  | Minden pixelhez színt rendelünk                 | Bonyolult vonalakat könnyen tudunk ábrázolni                               | A kép nagyítása torzításhoz vezethet                | Fotográfia                   |
| Vektorgrafika | Vonalak, geometriai alakzatok alakítják a képet | A kép nagyítása nem vezet torzuláshoz, egyszerű képeknél kissebb fájlméret | Élethű képeket nem lehet vele egyszerűen visszaadni | Grafikus design, betűtípusok |

## Színek kódolása és színmódok

1. Additív színkeverés - RGB

   - Kijelzőknél használjuk
   - Piros (R), zöld (G), kék (B) összeadása

1. Szubsztraktív színkeverés - CMYK

   - Nyomtatásnál használjuk
   - Cián, magenta, citromsárga és fekete egymásból kivonása

## Képek tárolása fájlokban

- .bmp:

  - "bitmap" - bittérkép
  - Minden pixelhez egy-egy színt rendelünk
  - 24 bites színmélység
  - Nincs tömörítés

- .gif:

  - Jó tömörítés -> interneten népszerűség
  - Minőség viszont elhanyagolható
  - Animációk

- .jpg (=.jpeg):
  - 6-20 szoros tömörítés
  - Jó tömörítés-minőség arány (minőség < tömörítés)
  - 24 bites színmélység
- .png:

  - Veszteségmentes tömörítés (minőség > tömörítés)
  - Alfa csatorna - átlátszóság
  - 48 bites színmélység

- Képszerkesztők projektfájlkiterjesztése (Gimp: .xcf, Photoshop: .psd):
  - Nem képtekintésre való
  - Minden képszerkesztői tevékenységet elment
