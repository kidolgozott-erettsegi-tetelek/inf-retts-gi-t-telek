# Infótöri

## 0. Generáció: Mechanikus és elektromechanikus számítógépek (19.sz eleje -> 20.sz közepe)

- Charles Babbage:

  - Difference Engine:

    - 1828
    - Hajózási táblázatok pontosítása

  - Analitical Engine:

    - Hatodfokú polinomok kezelése
    - Külső programvezérlés

  - Babbage-féle számítógép-elvek:
    1. Külső progamozás elve:
       - Bemeneti egységekkel való szám- és utasításbetáplálás
    1. Aritmetikai egység:
       - A műveletek elvégzéséért egy külön egység felel
    1. Vezérlő egység:
       - A műveletelvégzés sorrendjéért felel
    1. Átmeneti tároló:
       - Részeredmények tárolása (operatív memória nem RAM)
    1. Digitális kijelzés:
       - Számjegyeket használó egység jelzi az eredményeket

- Ada Byron:

  - Babbage-rajongó
    - Analitikus gépének terveit és programjait Babbage elmondásából készítette
  - Első programozó

- George **Bool**e & Augustus de Morg**an**:

  - Logikai műveletek matematizálása
    - Bool-algebra
    - Számítógépek működésének alapja

- Alan Turing:
  - Turing-gép:
    - Programok és a programozható számítógép modellje
    - 1930
  - Ballisztikai lőelemszámítások
  - Náci Enigma kód feltörése (Kódjátszma, 2015)

## 1. Generáció: Elektroncsöves számítógépek

- 1945 - 1958
- jellemző áramköri elem: **elektroncső**
- 300 - 5000 műv/s
- Programozás gépi kódban
- Több szobányi méret; hatalmas energiafelhasználás; gyakori hibásodás

Elektroncső:

- 1904
- Milliószor érzékenyebbek a reléknél

Maxwell H. A. Newmann & Thomas Harold Flowers:

- Colossus
  - Német titkosítás (Lorenz) megfejtése
  - 1943-ban kezdett el működni

John Mauchly & John Presper Eckert:

- ENIAC:
  - Teljesítményfelvétel: 174 kW
  - 30 m hosszú, 30 tonna 2000x MARK-1
  - Adatokat lyukkártyával, utasításokat kézzel vitték be

Neumann János & Herman Heine Goldstine:

- EDVAC:
  - 1949 - 1950
  - Belső programvezérlés
  - Elektronikus, digitális
- IAS:
  - 1952
  - Institute for Advanced Studies
  - Párhuzamos működés
- Neumann-elvek:

  1. A számítógép legyen teljesen elektronikus külön vezérlő- és végrehajtóegységgel

  1. Kettes számrendszert használjon

  1. Az adatok és a programok ugyanabban a belső tárban legyenek

  1. A számítógép legyen univerzális Turing-gép

- EDSAC:
  - 1949

## 2. Generáció: Tranzisztoros számítógépek

- 1958 - 1965
- Jellemző áramköri elem: **tranzisztor**
- Háttértár: mágnesszalag majd mágneslemez
- 50 000 - 1 000 000 műv/s
- Programnyelvek: Assembly
  - fordítás Assembler fordítóval
- I/O: lyukkártya, mágnesszalag (I), nyomtatott kivitel (O)

- Telefunken RAT-740:
  - 1960
  - ~ 1 000 000 műv/s
- IBM-1400:
  - 1961
  - eladás: > 17 000 db

## 3. Generáció: Integrált áramkörök

- 1965 - 1972
- Jellemző áramköri elem: **integrált áramkör (IC)**
- 1-2 000 000 műv/s
- Input: billentyűzet -> mágneslemez, mágnesszalag
- Output: nyomatatott lista, képernyő
- Grafikus monitor mejelenése
- Programnyelvek: Algol, Cobol, Basic, Fortran
- Operációs rendszerek: DOS, OS
- I/O processzor
- Integrált áramkör: csökkentett méret, hiba, ár

  - Kereslet: > 100 000 nagyszámítógép és > 100 000 miniszámítógép

- IBM-360
  - 1964
  - Bájtszervezés, IO processzor
  - Párhuzamosság

## 4. Generáció: Mikroprocesszor

- 1972 -
- Jellemző áramköri elem: **chip**
- Félvezető memória
- Mágneslemez háttértár: floppy, HDD
- Programozási nyelvek: Pascal, C nyelvek, Java, stb...
- Grafikus egységek (GPU)
- Grafikus felhasználói interfész, ablaktechnika (Windows)

- Intel

  - 1968: alapítás
  - 1972: 8008 megjelenése (32 bites architektúra)

- Advanced Micro Devices
  - 2003: első felhasználói 64 bites processzor (Athlon)
    - 64 bites architektúra kódneve: AMD64
  - 2005: első kétmagos CPU (Athlon 2X)

## 5. Generáció: ???

- 1993 -
- Eljárás-orientálság helyett programorientáltság (Prolog)
- Internet javulása
- Mesterséges Intelligencia
- IoT
- Cloud Computing
  - Számításhoz szükséges CPU helye nincs megkötve
- Sok lúd disznót győz
  - Sok lassú CPU mag > kevés gyors CPU mag
    - GPU > CPU
