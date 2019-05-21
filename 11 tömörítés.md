# Tömörítés

Redundancia: adathalmazok ismétlése

Redundáns jelek előnye: adatvesztés esetén helyrehozható jel

Redundáns jelek hátránya: felesleges adatátvitel/tárolás

Tömörítés:

- adatok redundanciájának csökkentése
- ismétlődő jelek kevesebb jellel való kifejezése
- becsomagolás: tömörítés
- kicsomagolás: kitömörítés (tömörítet kód visszafejtése fájlokba)

## Fájlok tömörítése

| Előny                                           | Hátrány                |
| ----------------------------------------------- | ---------------------- |
| Fájlkiterjesztés módosítása                     | Érzékeny a sérülésekre |
| Egy fájl szeletelése                            |                        |
| Több fájl egybe csomagolása (email mellékletek) |                        |
| Jelszóvédelem                                   |                        |

Szükséges: tömörítő program:

- Windows: WinRAR (.rar, .zip)
- Mac/Linux: tar parancs (.gz, xz)

## Tömörítés típusok

| Tömörítéstípus            | Definíció                                                                 | Mikor használjuk                                                             | Példa                                   |
| ------------------------- | ------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | --------------------------------------- |
| Veszteségmentes tömörítés | Tömörített adatsorból az eredeti információ maradéktalanul visszafejthető | Ahol minden adat fontos                                                      | Szöveges fájlok, programok, adatbázisok |
| Veszteséges tömörítés     | Nem állítható vissza az eredeti információfolyam                          | Nem fontos minden részlet (pl. nem érzékeljük a tömörített fájl különbségét) | Képek, videók, hangok                   |

## Tömörítések és kiterjesztések

|                 | Képek tömörítése | Hangok tömörítése       | Videók tömörítése  |
| --------------- | ---------------- | ----------------------- | ------------------ |
| Eredeti         | BMP              | WAV (Windows)           | -                  |
| Veszteségmentes | PNG, JPEG 2000   | FLAC, ALAC (iTunes)     | -                  |
| Veszteséges     | JPG (JPEG)       | MP3, OGG (Spotify), AAC | M-JPEG (MPEG), AVI |
