# ByteFix – seznam funkcionalnosti

## Uvod

ByteFix je spletna rešitev servisa računalnikov, prenosnikov in gaming opreme, ki na enem mestu združuje naročilo servisa, spremljanje stanja popravila, sestavljanje računalnika po meri in nakup komponent. Pregled obstoječih rešitev (Anni, Funtech, Komponentko) je pokazal, da slovenski ponudniki dobro pokrivajo prodajo, servis pa je pri njih na spletu skoraj nedostopen. Spodnji seznam zato poleg osnovnih funkcionalnosti spletne trgovine poudarja spletno naročanje servisa, sledenje popravilu in konfigurator z vodenjem za začetnike.

Prioritete so ocenjene na lestvici:

- **Visoka** – nujno za prvo delujočo različico (MVP),
- **Srednja** – pomembno, implementiramo takoj po osnovnih funkcionalnostih,
- **Nizka** – dodatna vrednost, implementiramo, če ostane čas.

## Funkcionalnosti

| ID  | Ime | Opis | Prioriteta |
|-----|-----|------|------------|
| F01 | Registracija in prijava | Uporabnik si ustvari uporabniški račun in se vanj prijavi z e-pošto in geslom. Račun omogoča dostop do naročil, zahtevkov za servis in zgodovine. | Visoka |
| F02 | Spletno naročilo servisa | Uporabnik izpolni zahtevek za servis, v katerem izbere vrsto naprave in opiše težavo. Po oddaji prejme unikatno številko zahtevka. | Visoka |
| F03 | Izbira termina oddaje naprave | Uporabnik ob naročilu servisa izbere prost termin, ko bo napravo prinesel v servis. Sistem prikaže le termine, ki še niso zasedeni. | Srednja |
| F04 | Spremljanje stanja popravila | Uporabnik s številko zahtevka ali v svojem računu vidi trenutno stanje popravila (sprejeto, diagnostika, čaka na del, popravljeno, pripravljeno za prevzem). | Visoka |
| F05 | Upravljanje zahtevkov (serviser) | Serviser vidi seznam vseh zahtevkov, jim spreminja stanje in dodaja opombe o diagnostiki ter končni ceni popravila. | Visoka |
| F06 | Okvirni cenik storitev | Uporabnik si ogleda cenik pogostih storitev (npr. čiščenje, menjava diska, namestitev sistema), da ceno pozna že pred oddajo naprave. | Srednja |
| F07 | Katalog komponent s filtri | Uporabnik brska po katalogu komponent (procesorji, grafične kartice, pomnilnik, diski) in jih filtrira po proizvajalcu, ceni in zmogljivosti. Pri vsakem izdelku vidi specifikacije in stanje zaloge. | Visoka |
| F08 | Košarica in oddaja naročila | Uporabnik doda izdelke v košarico, izbere način plačila in prevzema (dostava ali osebni prevzem) ter odda naročilo. | Visoka |
| F09 | Konfigurator računalnika po meri | Uporabnik korak za korakom izbere komponente za svoj računalnik, sistem pa sproti preverja njihovo združljivost (npr. podnožje procesorja, moč napajalnika) in sešteva ceno. | Visoka |
| F10 | Vodenje glede na igre in proračun | Začetnik vnese proračun in igre, ki jih želi igrati, sistem pa mu predlaga ustrezno konfiguracijo, ki jo lahko nato še prilagodi v konfiguratorju. | Srednja |
| F11 | Pripravljene gaming konfiguracije | Uporabnik izbere eno od vnaprej pripravljenih gaming konfiguracij za različne cenovne razrede in jo naroči ali uporabi kot izhodišče za lastno sestavo. | Srednja |
| F12 | Zgodovina nakupov in popravil | Uporabnik v svojem računu pregleda vsa pretekla naročila in popravila skupaj s cenami in datumi. | Srednja |
| F13 | E-poštna obvestila | Uporabnik ob spremembi stanja popravila ali naročila samodejno prejme obvestilo po e-pošti. | Srednja |
| F14 | Odkup stare opreme | Uporabnik odda ponudbo za odkup svoje stare opreme in prejme okvirno vrednost, ki jo lahko uveljavi kot popust pri nakupu ali nadgradnji. | Nizka |
| F15 | Upravljanje kataloga (administrator) | Administrator dodaja, ureja in briše izdelke v katalogu ter posodablja njihove cene in zalogo. | Visoka |
