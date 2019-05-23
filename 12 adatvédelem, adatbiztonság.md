# Adatvédelem, adatbiztonság

## Fogalmak

Adat: Információ alapegysége

- önmagában nincs jelentésük
- számokkal leírható
- számítástechnikai eszközökkel rögzíthető, feldolgozható és kimutatható

Információ: ismerethiányt megszüntető adathalmaz

- emberek számára jelent valamit
- informatika alapfogalma

Információs rendszerek: adatokat létrehozó, feldolgozó és tároló eszközök csoportja

Szoftver: hardvereken futó protramok összessége

Hardver: számítási műveletek fizikai háttere

Számítógép-hálózat: számítógépek egymás közötti kommunikációja

Dokumentáció: informatikai rendszerek leírása, útmutatója, kézikönyve vagy terve

## IT biztonság vs információbiztonság

IT biztonság: eszközök (hardver/szoftver) védelme

Információbiztonság: az IT-eszközökön tárolt _adatok_ védelme

Információbiztonság része az IT-biztonság

## Információbiztonság - adatvédelem

Adatvédelem: személyes adatok jogszerű és etikus kezelésének elmélete
Részei:

- Bizalmasság: csak a jogosultak férhessenek az adathoz
- Sértetlenség (integritás): adat tartalma és formája egyenlő legyen az eredeti adattal
- Rendelkazésre állás: szükség szerinti adatellátás (ne menjen tönkre semmi, amikor az éppen kell)

Adatok fajtái adatvédelmi szempontból:

- Személyes adatok: konkét személy azonosítására használt adatok

  - név
  - születési dátum
  - lakcím
  - családi állapot

- Különleges személyes adatok: egy személy kínos adatai

  - faji eredet
  - nemzetiség
  - politikai vélemény, pártállás
  - vallásosság, világnézeti meggyőződés
  - szexuális élet
  - egészségi állapot
  - káros szenvedélyek

## Védelem kialakítása

### Bizalmasság

Információbiztonsági Szabályzat (IBSZ): adatvédelem szabályainak összefoglalása és Informatikai Katasztrófavédelem

Hitelesítés: védelem 1. szintje, jogos és jogosulatlan felhasználás elválasztása (általában felhasználónév és/vagy jelszó)

Titkosítás: védelem 2. szintje, használhatatlanná teszi az adatot, csak kulcssal vagy jelszóval lehet az eredeti adatot kinyerni

#### Bizalmasság az operációs rendszerben

Fájl-jogosultságok: Fájrendszerbe vagy operációs rendszerbe beépített jogosultságrendszer

Egy fájlrendszer korlátozhatja egy fájl _írását_ (szerkesztését), _olvasását_, _futtathatóságát_ (program esetében).

#### Merevlemezek, USB-lemezek titkosítása

Partíció: Egy adathordozó több részre felosztása, így az operációs rendszer úgy látja, mintha több adathordozó lenne

Rendszerindításra alkalmas adathordozóknál kell egy nem titkosított partíció.

#### Tömörített állományok titkosítása

A tömörített állományokat jelszavas védelemmel is el tudjuk látni.

#### Dokumentumok titkosítása

Irodai programcsomagok is képesek egy dokumentumot jelszavas védelemmel ellátni.

#### Hálózat és bizalmasság

Védett hálózatok: valamilyen korlátozást alkalmaz a hozzáféréshez
Nyílvános hálózatok: bárki csatlakozhat a hálózathoz

#### Hozzáférés-védelem, jelszavak és hitelesítés

1. Fizikai védelem (nem adunk fizikai hozzáférést a féltett hardverhez)
1. Jelszó
   1. Többször használatos jelszó
   1. Egyszer használatos jelszó (pl. SMS-ekben kapott megerősítő jelszó internetbankoknál)
   1. Biometriai jelszó (Ujjlenyomat, hang, retina stb.)

Kétfaktoros hitelesítés: Többszöri ÉS egyszeri jelszó megadása kell a hitelesítéshez

#### WiFi hálózatok védelme

Használjunk jelszót a WiFi hálózatunk védelmére, különben rossz szándékú emberek lehallgathatják a kommunikációnkat

Titkosítása: WPA, WPA2 és WPA3 (Wifi Protected Access)

#### Phishing

Egy népszerű oldal bejelentkező felületének imitálása, ahol a bejelentkezést követően a támadók megkapják a bejelentkezési adatainkat.
Mindeközben mi azt gondoljuk, hogy a hivatalos oldalon jelentkeztünk be.

Védekezés:

1. Figyeljük az URL-címet (pl. facebook helyett nem faceb00k van-e írva)
1. Győződjünk meg arról, hogy van-e zöld lakat az URL-sávtól balra
   - Ez jelenti, hogy az oldallal való kommunikáció titkosítva van
   - VAGY ellenőrizzük, hogy a weboldal címe `https://`-l kezdődik-e

#### Weboldalak aktív tartalmai

Weboldalak lágotatásakor a gépünkön futó mini-programok.
A weboldal dinamikusságát szolgálják.

Azonban a rossz indulatú weboldalak súlyos kárt tudnak okozni.

Ezért fontos pl. a Flash, a Java frissen tartása a rendszerünkön

Fajtái/programnyelvek:

- Javascript (meglehetősen biztonságos)
- Flash (2020-ban megszűnik a támogatottsága, magas sebezhetőség)
- Java appletek
- VBScript
- ActiveX

#### Internetezés következtében tárolt adatok a gépünkön (naplózás)

- Előzmények
- Űrlapadatok
- Sütik: személyes információt tároló (titkosítatlan) fájlok
- Jelszavak

#### Adatok végleges törlése

Amikor a számítógépünkön törlünk egy adatot, az csak 'üres tárhely'-ként fog megjelenni.
Legközelebbi írásnák ez az üres hely lesz felhasználva, átírva az eredeti adatot

- Fizikai megsemmisítés
- Formatálás
  - Új fájlrendszert rakhatunk az adathordozóra (választhatjuk a régit is)
  - Opcionálisan minden tárolt 0-t, vagy 1-t (melyek az információt rakják ki) csak 0-ra, vagy csak 1-re ki lehet cserélni

### Sértetlenség

Sértetlenség vagy integritás: Valami ami megfelel az eredeti állapotának és teljes

Digitális aláírás: Titkosított kód, mely egy személy azonosságát azonosítja egy fájlhoz, tehát hitelesíti

Digitális tanúsítvány: Egy harmadik féltől (aláírás-létrehozó) származó tanúsítvány az üzenet küldőjének hitelességéről

### Rendelkezésre állás

#### Biztonsági mentések

Adatvesztés ellen a _biztonsági másolatok_ jelentenek megoldást

Számtalan szoftver áll rendelkezésünkre a biztonsági mentések kezelésére

#### Áramellátás hibái ellen való védekezés

Szünetmentes tápegység: Elektromos elosztó akkumulátorral

Ha elmegy az áram és szeretnénk használni a gépet, kössünk be szünetmentes tápegységeket, így akksiról működik a gép
