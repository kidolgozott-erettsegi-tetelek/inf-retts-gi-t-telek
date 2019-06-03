# Az internet szolgáltatásai

## Internet története

1. 60-es évek: ARPANet: redundáns katonai kommunikációs hálózat
1. 70-es évek: Több (ARPANet szerű) hálózat összekötve
1. 80-as évek: Egyetemek, főiskolák, kutatóintézetek és állami hivatalok is csatlakoznak, megjelentek az első magánfelhasználók
1. napjaink: exponenciális növekedés

## Protokollok

Protokoll: egy kommunikáció szabályai; a számítógépek (kommunikációs) nyelve

Kiszolgáló (szerver): egy internetes szolgáltatást lehetővé tévő számítógép (pl. Weboldal, Minecraft-szerver)

Port: egy szám, mely segítségével megadjuk, melyik szolgáltatást szeretnénk használni

| Protokoll rövidítése | Teljes neve                                     | Használat                                                                                                                                                                                                          | Alapértelmezett port-szám |
| -------------------- | ----------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------- |
| TCP/IP               | Transmission Control Protocol/Internet Protocol | Interneti kommunikáció alapja, kb. minden egyéb protokoll ezen alapszik                                                                                                                                            | -                         |
| HTTP/HTTPS           | HyperText Transfer Protocol (Secured)           | Mai WWW kommunikáció alapja, HTTP-n általában weblapokat (HTML fájlokat), egyéb weboldalhoz szükséges fájlokat és a válasz-információkat (pl. bejelentkezés, regisztráció, bejegyzés létrehozása) küldenek a gépek | HTTP: 80, HTTPS: 443      |
| FTP/SFTP             | (Secured) File Transfer Protocol                | Fájlok egyszerű fel/letöltése                                                                                                                                                                                      | FTP: 21, SFTP: 22         |
| SSH                  | Secure SHell                                    | UNIX-szerű OS-ekkel ellátott gépek (pl. szerverek) távoli elérése                                                                                                                                                  | 22                        |
| SMTP                 | Simple Mail Transfer Protocol                   | E-mailek továbbítása                                                                                                                                                                                               | 25                        |
| POP(3)               | Post Office Protocol                            | E-mailek fogadása                                                                                                                                                                                                  | POP3: 110                 |
| IMAP(4)              | Internet Message Access Protocol                | E-mailek fogadása (POP alternatíva)                                                                                                                                                                                | IMAP4: 143                |

Megjegyzés: a különböző portszámok használata jelentősen csökkent, ugyanik a HTTP(S) protokoll segítségével helyettesíteni tudjuk a többi protokollt. Például a HTTP(S) fájlokat is át tud küldeni, ezért helyettesítheti az (S)FTP-t. Jó példa erre hogy a Google Drive-szerű online tárhelyek jóval népszerűbbek az FTP-s megoldásoknál.
