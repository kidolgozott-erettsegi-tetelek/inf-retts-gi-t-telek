# Jel, zaj, adat, redundancia

Informatika az **információ**:

- megszerzésével
- feldolgozásával
- tárolásával

foglalkozik.

## Információ

- Olyan új ismeret, mely az érzékelő számára szükséges, kontextus alapján értelmezhető.

- Új tudás
  - meglévő bizonytalanságot szüntet meg

## Jel

**Jelek** az információ hordozásához alkalmas szimbólumok.

- Mérhető jelenség
- Jelentéssel bír
  - egyezmény szükséges a küldő és a befogadó között

Példák:

- magyar abc betűi
- brallie-írás

### Analóg jelek

- Értelmezési tartomány és értékkészlet folytonos
  - minden időpillanatra értelmezett
- Legtöbbször fizikai mennyiséget reprezentálja
  - áramerősség
  - hőmérséklet
  - idő
  - stb...

### Digitális jelek

- Analóg jel digitalizálva
  - bizonyos időnkénti mintavétel
- Diszkrét jelek: véges, sok jól megkülönböztethető értéket vesznek fel

#### Digitalizálás típusai

- Kép digitalizálása

  - Felbontás (DPI - dot per inch)
  - szkenner, fényképező, kamera

- Hang digitalizálása
  - mintavételezés -> kvantálás -> kódolás
  - ADC - Analog to Digital Converter

## Adat

**Adat** az információ megjelenített, rögzített formája

## Kommunikáció

Adó -> Kódolás -> Csatorna -> Dekódolás -> Vevő

- Csatorna által közvetített jelsorozat: **közlemény**
- A környezet **zaj** formájában kihat a kommunikációra
- Kódolás: jelek a csatorna számára továbbíthatóvá tétele
  - Dekódolás: jelek a fogadó fél számára értelmezhetővé tétele

### Redundancia

A kommunikációt zaj zavarja meg.

Hogy ne vesszen információ, a kelleténél **több jelet küldünk**.

Adatmennyiség jóval nagyobb, mint az információmennyiség -> tömörítés
