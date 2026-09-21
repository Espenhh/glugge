# Glugge

En glugge inn i norske kart. Søk opp en adresse, og se stedet i flyfoto, skråfoto
fra fire himmelretninger, gateplan — og bakover i tid, til flyfoto fra 1937 og
kart fra 1887.

Mac-app, på norsk, laget for min egen utforskning av nabolaget.

[![Last ned Glugge](https://img.shields.io/badge/Last%20ned-Glugge.dmg-0a84ff?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/Espenhh/glugge/releases/latest/download/Glugge.dmg)

![Siste versjon](https://img.shields.io/github/v/release/Espenhh/glugge?label=siste%20versjon&color=555)
![Krever macOS 26](https://img.shields.io/badge/krever-macOS%2026-555)

## Les dette først

**Glugge er en demo-app, ikke et produkt.** Den ble laget for å finne ut hva som
egentlig finnes av kart-API-er i Norge, og hvor langt man kommer med dem. Den er
ikke en offisiell app fra noen, den har ingen support, og den kan slutte å virke
når som helst — den henger sammen så lenge tjenestene den snakker med gjør det.

**Noen av API-ene den bruker er åpne. Andre er ikke ment for dette.** Kartverket,
Geonorge, Oslo kommune, DigitaltMuseum og Digitalarkivet har åpne API-er som
hvem som helst kan bruke. Men kartflisene fra Norkart/1881, skråfotoene fra Blom
og gateplanbildene fra Google kommer fra udokumenterte endepunkter som
nettstedene deres bruker internt. De ligger åpent på nettet, men de er ikke en
gratis allmenning, og de er ikke ment for andre formål enn nettsidene de brukes
fra.

**Derfor:** Glugge er til privat, ikke-kommersiell utforskning fra din egen
maskin. All bruk skjer på eget ansvar og på dine egne vilkår. Du er selv
ansvarlig for at det du bruker appen til er i tråd med vilkårene til tjenestene
den henter fra. Laster du den ned, har du lest dette.

Appen samler ikke inn noe. Den snakker direkte fra maskinen din til tjenestene,
og det eneste som lagres er hvor du var sist.

## Hva den kan

- **Søk** i alle norske stedsnavn og adresser (Kartverket og Matrikkelen).
- **Bakgrunnskart** fra Kartverket, 1881, Google og Apple — kart, flyfoto, hybrid,
  sjøkart.
- **Historiske flyfoto og kart** lagt over dagens kart, med en tidsstripe som
  viser hvilke årganger som dekker stedet. Eldste flyfoto er fra 1937, eldste
  kart fra 1800-tallet.
- **Tidsreise**: spill av alle årgangene for utsnittet som en film, eller lagre
  den som video.
- **Sammenlign før og nå** med en loddrett linje du drar over flyfotoet.
- **Skråfoto** av adressen fra nord, øst, sør og vest, i flere årganger, med
  nabobilder du kan bla til.
- **Gateplan** fra Google — også gamle årganger, så du kan gå langs gata i 2009 —
  og Apples Look Around der det finnes.
- **Oslo planinnsyn**: reguleringsplaner, plansaker, byggesaker, gul liste,
  eiendomsgrenser og temakart, lagt rett på kartet. Klikk for å se hva som
  gjelder for en tomt.
- **Museum**: stedfestede fotografier fra norske museer (DigitaltMuseum), og
  folketellingene — hvem som bodde i huset i 1910, og oppslag tilbake til 1801.

## Installering

1. Last ned [Glugge.dmg](https://github.com/Espenhh/glugge/releases/latest/download/Glugge.dmg).
2. Åpne den og dra Glugge over i Programmer.
3. Start appen.

Krever **macOS 26 (Tahoe)** eller nyere. Appen er signert med Developer ID og
notarisert hos Apple, så den åpner uten advarsler.

## Kilder

Data og bilder kommer fra:

| Kilde | Hva |
| --- | --- |
| [Kartverket / Geonorge](https://www.geonorge.no) | Stedsnavn, adresser, topografiske kart, sjøkart (CC BY 4.0) |
| [Norkart / 1881](https://kart.1881.no) | 1881-kart, flyfoto, historiske flyfoto og kart |
| [Blom URBEX](https://www.blomurbex.com) | Skråfoto |
| Google | Kartfliser og Street View |
| Apple | MapKit-kart og Look Around |
| [Oslo kommune](https://od2.pbe.oslo.kommune.no) | Planinnsyn: reguleringsplaner, byggesaker, temakart |
| [DigitaltMuseum](https://digitaltmuseum.no) | Fotografier fra norske museer |
| [Digitalarkivet](https://www.digitalarkivet.no) | Folketellingene 1801–1920 |

Alle rettigheter til dataene ligger hos kildene. Glugge viser dem, den eier dem
ikke.

## Kildekoden

Kildekoden ligger i et privat repo. Dette repoet inneholder bare utgivelsene og
denne teksten.

---

Laget av [Espen Storm Herseth](https://github.com/Espenhh). Ingen garanti, ingen
support, ingen lisens — appen er som den er.
