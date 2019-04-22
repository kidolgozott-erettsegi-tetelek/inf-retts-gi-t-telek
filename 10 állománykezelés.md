# Állománykezelés

Állomány: számítógépen tárolt összefüggő adatok gyakorlati alapegysége.

Fájlazonosítás: fájlnév alapján

- Egy mappában nem lehet több ugyanolyan nevű állomány

# Állományrendszerek

Fájlrendszer: A fájlok és mappák háttértáron való tárolásának megvalósítása

- FAT, FAT12, FAT16, FAT32: Egyszerű fájlrendszer, nincsenek jogosultságok

| Fájlrendszer neve        | Leírás                                                                                                                                     | Operációs rendszer | Használat              |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------ | ------------------ | ---------------------- |
| FAT, FAT12, FAT16, FAT32 | Egyszerű fájlrendszer felhasználói jogosultságok nélkül                                                                                    | OS független       | Pendrive/Memóriakártya |
| NTFS                     | Windows modernebb fájlrendszere                                                                                                            | Windows            | OS-t hordozó háttértár |
| EXT2, EXT4               | Linux egyik fájlrendszere, minden folyamatot egy különleges fájlban jegyez (így ha a folyamat hirtelen megszakad, kevesebb az adatvesztés) | Linuxok            | Bármilyen háttértár    |
| ISO 9660                 | CD-k fájlrendszere                                                                                                                         | OS független       | CD-k                   |

## DOS-os és Windows-os kiterjesztések

Kiterjesztés: a fájlnévben egy pont után található (általában 3-4 karakterű) szöveg

Az operációs rendszer a kiterjesztésből tudja, mit csinál egy fájl és milyen programot indítson el, amikor megnyitjuk az állományt.

Windows-os kiterjesztések:

- .exe, .com: futtatható fájlok
- .bat: szöveges parancssorozat
- .dll: egy programhoz szüséges könyvtár
- .sys: operációs rendszernek szükséges fájlok
- .tmp: átmeneti adatok
- .bin: hasonló a .sys-hez
- .log: naplózási fájl

Szöveges fájlkiterjesztések:

- .txt: sima szöveg

| Kiterjesztés neve | Programnyelv      |
| ----------------- | ----------------- |
| .html             | HTML (weboldalak) |
| .py               | Python            |
| .rb               | Ruby              |
| .cpp              | C++               |
| .cs               | C#                |
| .c                | C                 |
| .java             | Java              |
| .js               | JavaScript        |
| .ts               | TypeScript        |
| .css              | CSS               |

Office állományok:

- .doc, .docx: Word-fájlok
- .ppt, .pptx: Powerpoint-fájlok
- .xls, .xlsx: Excel-fájlok

Képek és hangok formátumai:

- .bmp: egyszerű kép (nincs tömörítés)
- .jpg, .jpeg: tömörített kép
- .gif: nagyon tömörített kép vagy animáció
- .png: tömörített, átlászóságot tartalmazható képek
- .mp3: nagyon tömörített hang
- .flac: veszteség nélkül tömörített hang

## Keresés egy operációs rendszeren

Windows: fáljok program jobb felső sarkában van kereső

UNIX: `which` parancs

## Állomány megnyitása

OS társítja az állományt egy programmal, melyet egy kiterjesztéshez rendelt.
