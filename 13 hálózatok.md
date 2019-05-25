# Hálózatok

Hálózat: összekapcsolt gépek

Hálózatok előnyei:

1. Jobb kihasználtság
1. Gyorsabb emberi kommunikáció
1. Erőforrások megosztása: Pl. egy nyomtató több géphez van kapcsolva
1. Párhuzamos munka
1. Üzembiztonság fokozása (redundancia): Pl. több nyomtatónk van -> egyik elromlik, ott van a másik
1. Távoli számítógépek elérése
1. Terheléseloszlás
1. Könnyen növelhető rendszerteljesítmény (horizontális terjeszkedés): Pl. több nyomtatási sebesség kell? Csak szereljünk be egy másik nyomtatót, így nem kell a meglévőt lecserélni

## Hálózatok csoportosítása

### Zárt & nyílt rendszerek

1. Zárt rendszer: Gyártónak abszolút hatalma van a hálózat felett
1. Nyílt rendszer: Hardverfüggetlen

### Átviteli sebesség

1. Lassú
1. Közepes
1. Nagy sebességű

### Kommunikáció iránya

1. Szimplex: egyirányú, fix az adó és a vevő
1. Fél duplex: váltakozó irányú, egyidőben csak egy irányban áramlik információ
1. Duplex: kétirányú, adó és vevő szerep gyakran felcserélődik, egyszerre is áramolhat információ

### Kapcsolási technika

| Név            | Működés                                                                                                                                 | Előny                                                                               | Hátrány                                                                                      | Példa     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | --------- |
| Vonalkapcsolt  | Egy kapcsolat egy külön vonalat kap                                                                                                     | Adatvédelem                                                                         | Nagy hálózat nagy infrastruktúrát igényel                                                    | Telefon |
| Üzenetkapcsolt | Két fél között továbbítók vannak                                                                                                        | Korlátlan üzenethossz                                                               | Adatvédelem hiánya (titkosítás nélkül bárki elolvashatja az üzenet tartalmát)                | Posta     |
| Csomagkapcsolt | Továbbítók az üzenet részét (packet) továbbítják. A packetek akár több úton is elérhetik a címzettet, a packetek útját routerek segítik | Decentralizált (nincs központ) -> jobb terheléseloszlás, adatvédelem, üzembiztonság | Ha egy packet nem éri el a címzettet, értesíteni kell a feladót, hogy küldje újra a packetet | Internet  |

### Logikai felépítés

1. Kliens-szerver modell: Kliens adatot küld/válaszol, szerver kérésre tárol/kiszolgál
1. Egyenrangú (peer-to-peer, P2P) modell: Hálózat bármelyik tagja küldhet, fogadhat, kiszolgálhat és tárolhat

### Hozzáférés

1. Intranet: hálózat
1. Internet: hálózatok hálózata
1. Extranet: külső felhasználó által elérhető valamilyen intranetes szolgáltatás

### Területi kiterjedés

1. LAN, Local Area Network: általában egy épületen belül helyezkedik el, általában egy tulajdonosa van
1. MAN, Metropolitan Area Network: egy vagy több városnyi LAN-okat köt össze
1. WAN, Wide Area Network: több WAN-t köt össze, ebből áll az internetünk

- Egy kommunikáció gyorsasága a leglassabb kábeltől függ
  - Minél sokrétűbb a kábelezés (WAN) annál lassabb lesz
- Egy kommunikáció válaszideje a továbbító- és feldolgozó pontok számától függ
  - Minél több gép dolgozza át az üzenetünk, annál többet késik

## Hálózathoz szükséges rendszerek

1. Operációs rendszer, mely kezelni tudja a hálózati kommunikációt
1. Hálózati kártya: számítógép-nyelvre fordítja a közegen továbbított jelet
1. Átviteli közeg: továbbítja a jelet
1. Kapcsoló elemek: erősíti vagy illeszti a közeget

### Eszközök
1. Modem: helyi hálózatok (LAN) szélesebb körű hálózatra csatolása (MAN vagy WAN)
1. Repeater: jelerősítő
1. Switch: hálózati eszközök összekapcsolása
1. Router: hálózatok összekapcsolása
