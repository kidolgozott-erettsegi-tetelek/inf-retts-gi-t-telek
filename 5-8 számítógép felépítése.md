# Számítógép felépítése

## Neumann-elv

1. A számítógép legyen teljesen elektronikus külön vezérlő- és végrehajtóegységgel

1. Kettes számrendszert használjon

1. Az adatok és a programok ugyanabban a belső tárban legyenek

1. A számítógép legyen univerzális Turing-gép

## Számítógép részei

- Hardver: a számítógép műszaki megvalósítésa, a számítógép kézzel fogható része
- Szotfver: a számítépet működtető programok összessége

## Hardver tagozódása

- Alaplap
  - CPU
  - Memória
    - RAM
    - ROM
  - Vezérlőkártyák
    - Videokártyák
    - Hangkártyák
    - Hálózati kártyák
- Perifériák
  - Bemeneti eszközök
    - Billentyűzet
    - Egér
    - Mikrofon
    - Képolvasó
    - Webkamera
  - Kimeneti eszközök
    - Monitor
    - Nyomtató
    - Hangszóró
    - Projektor
    - Felhallgató
  - Háttértár
    - Merevlemez
    - Hajlékonylemez
    - CD/DVD-ROM
    - Pendrive
    - Memóriakártyák

## A központi feldolgozó egység (CPU)

Angolul Central Processing Unit.

Egy integrált áramkör, mely a fő számítási feladatokat hajtja végre.

### Processzor jellemzői:

- Sebesség:
  - Órajel frekvencia: Hz [herc]
    - Mhz [megaherc] = 1 000 000 Hz
    - Ghz [gigaherc] = 1 000 000 000 Hz
  - Teljesítményoldalról:
    - FLOPS - lebegőpontos művelet másodpercenként
    - MIPS - millió művelet másodpercenként
- Adatszó-hossz:
  - Egyszerre hány bitet képes a CPU feldolgozni
  - 32 vagy 64 bit

### Processzor felépítése

1. Vezérlőegység (Compute Unit - CU)
   - Utasítások feldolgozása
1. Aritmetikai-logikai feldolgozó egység (ALU)
   - Adatok számtani és logikai műveletfeldolgozása
1. Regiszterek
   - ALU és CU adatainak tárolása

## Központi tár & memória

ROM:

- Csak olvasoható memória (Read Only Memory)
- BIOS-t tárolja, mely program a számítógép elindítását kezeli

RAM:

- Egy lassabb, de nagyobb kapacitású regiszter a CPU-nak
- Random hozzáférésű memória (Random Access Memory)

## Vezérlő- és bővítőkáryák

Extra inputot, outputot, funkcionalitást biztosítő eszköz.

| Név                | Extra output          | Használat                                                   |
| ------------------ | --------------------- | ----------------------------------------------------------- |
| Videókártya        | HDMI/DVI/DP           | CPU által küldött videojelek monitorrá értelmessé alakítása |
| Winchester vezérlő | SATA/eSATA            | Extra merevlemezt tudunk a gépünkbe szerelni                |
| Hálózati kártya    | Ethernet/WiFi antenna | Extra hálózati kapcsolódási módot ad a gépünknek            |

## Alaplap részei

Nyomtatott áramköri lap, melyre a számítógép egyéb komponenseit rá tudjuk csatlakoztatni.

### Alaplap:

- Csatlakozók
- Órajelgenerátor: generált áramimpulzusok hangolják össze a központi egység részeit

### Buszok, tápegységek:

Buszok: alaplapi vezetékek, melyek a központi egység részeit kötik össze

### Tápegység:

- Váltóáram (220V) -> egyenáram (12, 5, 3.3V)

### Portok:

- Csatlakozók, melyekkel a számítógépet egy másik számítógéppel, ill. külső eszközzel össze lehet kötni
- Interfészek: kapcsolódási felület

##### Portok fajtái:

- Soros: az adat bitenként vándorol
- Párhuzamos: nyolc adatvonal -> az adat bájonként vándorol

#### Portok példái:

- USB: Univerzális Soros Busz
- SATA: Sorosan kapcsolt busz, leginkább háttértárak kapcsolásához használjuk
- SCSI: Régimódi adatátviteli busz (párhuzamos)
- SAS: Sorosan kapcsolt SCSI

## Perifériák

Számítógépekhez kapcsolt eszközök.

- Bemeneti eszközök:
  - Billentyűzet
  - Egér
  - Érintőpad (touchpad)
  - Fényképezőgép / Webkamera
  - Digitalizáló tábla
  - Érintőképernyő
  - Botkormány
- Kimeneti eszközök:
  - Monitorok:
    - Katódsugárcsöves (CRT)
    - Folyadékkristályos (LCD)
    - Aktív mátrixos LCD (TFT)
    - Gázplazmás (PDP)
  - Nyomtatók:
    - Mátrixnyomtató
    - Tintasugaras-
    - Lézer-
  - Head Up Display (HUD)
  - Hangszóró / Fül/Fejlhallgató
- Háttértárak:
  - Lyukszalag
  - Lyukkártya
  - Hajlékonylemez (floppy)
  - Merevlemez (HDD)
  - CD
  - DVD
  - Pendrive
  - SSD
  - Memóriakártyák
