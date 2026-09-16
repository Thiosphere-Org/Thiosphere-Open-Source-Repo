# Thiosphere - Modulära Open Source-skydd

[![CERN Open Hardware License v2](https://img.shields.io/badge/License-CERN%20OHL%20v2%20Strongly%20Reciprocal-blue.svg)](LICENSE.md)
[![Open Source Hardware](https://img.shields.io/badge/Open%20Source-Hardware-green.svg)](https://www.oshwa.org/)
[![Documentation](https://img.shields.io/badge/Documentation-Complete-brightgreen.svg)](docs/)

[🇺🇸 English](README.md) | [🇩🇪 Deutsch](README.de.md) | [🇪🇸 Español](README.es.md) | [🇫🇷 Français](README.fr.md) | [🇸🇪 Svenska](README.sv.md) | [🇫🇮 Suomi](README.fi.md)

---

# Modulära Open Source-skydd

Vi har formaterat vår värld för bilar, men har lite annat för att använda allt det utrymme vi har gett över till dessa maskiner. En Thiosphere™ skapas för att fylla det tomrummet med ett syfte och skönhet som definierar dess djärva och effektiva design. Det är Open Source-hårdvara som vem som helst kan bygga och modifiera efter sina egna behov.

## Introduktion

En thiosphere är tillverkad av det minsta möjliga antalet delar, men resulterar i ett starkt, lätt och rymligt modulärt skydd som bara tar upp 1/2 av en parkeringsplats. Den är platt packbar och kan monteras med vanliga verktyg. Den är modulär så du kan skapa ett oändligt antal konstruktioner, från ett enkelt skydd till ett komplext kontor. Den är både funktionell och vacker, och designad för att vara en andra plats där livet kan blomstra - vad det än är och var dessa krav finns.

![Thiosphere Grunderna](_media/football.png)
![Thiosphere Grunderna](_media/basics.png)
![Thiosphere Plattvy](_media/flatten.png)

### Open Source-hårdvarulicens

Förstå vår Open Hardware-licens
CERN Open Hardware License (Version 2 - Starkt Reciprok) säkerställer att:

- Alla design och modifieringar måste delas öppet
- Kommersiell användning tillåts med korrekt attribuering
- Modifierade versioner måste delas under samma licens
- Ursprungliga skapare måste erkännas
- Dokumentation måste tillhandahållas för alla ändringar

![Thiosphere Skala](_media/module.png)
![Thiosphere Skala](_media/scale.png)

## Fördelarna

- **Byggt Starkt**: Sfärisk geometri = maximal styrka, minimalt material
- **Håller sig Svalt**: Naturlig konvektion håller miljön stabil inuti
- **Passar Perfekt**: Designad för befintliga parkeringsplatser - inga modifieringar behövs
- **Enkelt att Bygga**: Enkel geometri betyder att du kan göra det lokalt med grundläggande verktyg

## Vad är en Thios?

> Siffran två på grekiska skrivs som "δύο" och uttalas med ett mjukt "th" ljud (thío), snarare än det hårda "d" man skulle förvänta sig. Detta "thio" prefix beskriver perfekt den dubbla sfärens design av Thiosphere™, en andra plats för livet.

## Snabbstart

### 📋 Förutsättningar

- Grundläggande träbearbetningsfärdigheter
- Tillgång till standardverktyg (se Byggguide)
- Förståelse för CERN Open Hardware License

### 🛠️ Komma Igång

1. **Granska Dokumentation**: Börja med [Design-dokumentet](thiosphere-design-document.md)
2. **Kontrollera Material**: Granska [Materiallistan](Bill_of_Materials_v.0.1.csv)
3. **Förstå Licensen**: Läs [CERN Open Hardware License](LICENSE.md)
4. **Börja Bygga**: Följ Byggguiden nedan

## Byggguide

> **Var siffrorna kommer ifrån.** Alla värden nedan är uppmätta i den slutliga Onshape-modellen
> *Thiosphere for prints* vid `#maxWidth` = 93,700 in (verifierat 2026-09-12). Där det äldre
> [Designdokumentet](thiosphere-design-document.md) eller
> [Materiallistan v0.1](Bill_of_Materials_v.0.1.csv) avviker gäller den här guiden.

### I Korthet

| | |
|---|---|
| Ytterdiameter | **93,700 in** (7 ft 9,7 in) |
| Kantlängd, yttre skal | **18,906 in** |
| Kantlängd, inre skal | **16,701 in** |
| Väggtjocklek | **5,0 in** — ¼ skiva + 1½ list + 1½ kloss + 1½ list + ¼ skiva |
| Fri höjd över färdigt golv, vid nocken | **79,829 in** |
| Golvbjälklag | 12-sidigt, 88,543 × 91,773 in |
| Moduler | **23** |

Formen är en trunkerad ikosaeder (32 ytor: 20 hexagoner, 12 pentagoner). Den vilar på en
kant, inte på en yta.

### De 23 Modulerna

Bara de 22 ytorna i höjd med den nedre hexagonringen eller ovanför är paneler. De 10 ytorna
under byggs inte: typ B, C och E förlängs ned till golvbjälklaget och tar deras plats.

| Typ | Modul | Antal | Hur den görs |
|---|---|---:|---|
| A | Enkel hexagon | 8 | Regelbunden hexagon |
| B | Dörr | 4 | Hexagon, två lodräta sidor förlängda till golvbjälklaget |
| C | Sidovägg | 2 | Hexagon, två lutande sidor förlängda till golvbjälklaget |
| D | Enkel pentagon | 4 | Regelbunden pentagon |
| E | Hörndrake | 4 | Pentagon, två sidor förlängda tills de möts |
| FL | Golvbjälklag | 1 | 12-sidigt, två skivor ¾ in plywood |
| | **Totalt** | **23** | |

### Det Här Behöver Du

**Material:**
- **36** × 2×4-reglar, 96 in långa — var och en klyvs på mitten (inklusive 8,5% för sågsnitt och spill)
- **16** × 4×8-skivor ¼ in plywood — yttre och inre skiva, med 35% för utläggning
- **2** × 4×8-skivor ¾ in plywood — golvbjälklag
- Skruv, bultar och hjul, släpvagn eller en nivelleringssockel — mängderna räknas om för den nuvarande modellen och anges inte förrän de är verifierade

**Verktyg:**
- Bordssåg med lutbart sågblad (fasen sågas vid klyvningen)
- Kap- och gersåg
- Borrskruvdragare
- Måttband och penna
- Skyddsutrustning (glasögon, hörselskydd)

### Steg-för-Steg-Bygge

#### 1. Sortera Virket, Klyv Sedan

**Det finns två fasvinklar, inte en.**

| Listen sitter mellan | Fas |
|---|---:|
| Hexagon ↔ hexagon | **20,905°** |
| Hexagon ↔ pentagon | **18,689°** |

- Varje 2×4 klyvs på mitten med sågbladet lutat till fasvinkeln. Ett snitt ger fasen och två lister.
- Med ⅛ in sågsnitt blir varje halva 1,6875 in bred.
- Fasen bestäms vid klyvningen, och en halva kan inte klyvas om. **Bestäm vilken fas varje regels lister behöver innan du klyver den.**
- En hexagonmodul behöver **båda** fasvinklarna: dess kanter växlar mellan hexagon- och pentagongrannar. En pentagonmodul har 18,689° på alla fem kanter.

> ⚠️ **Använd inte en enda medelvärdesfas på cirka 19,8°.** Den öppnar en glipa på cirka 5⁄64 in i
> varje fog, och glipor läggs ihop i varje hörn där tre lister möts.

#### 2. Kapa Listerna i Längd

**Geringar:** 30° i hexagonhörn, 36° i pentagonhörn, 36° i drakens spets.

**Längder** (spets till spets):

| List | Yttre skal | Inre skal |
|---|---:|---:|
| Enkla kanter — typ A och D samt de kanter på B, C och E som inte är förlängda | 18,906 in | 16,701 in |
| B · dörr, lodrät sida | 49,497 in | 49,056 in |
| B · dörr, syll | 32,747 in | 31,218 in |
| C · sidovägg, lutande sida | 49,497 in | 49,497 in |
| C · sidovägg, syll | 68,403 in | 67,521 in |
| E · hörndrake, förlängd sida | 49,497 in | 43,724 in |

**Gör inte det inre skalet genom att skala ned det yttre.** De förlängda sidorna slutar vid
golvbjälklaget, och det flyttar sig inte, så de blir mindre kortare än de enkla kanterna eller inte
kortare alls. Därför har det inre skalet sex listlängder och det yttre fyra.

**Total listmängd:** yttre skal 112 lister (240,3 ft), inre skal 112 lister (218,3 ft),
klossar 224 st (63,2 ft) — **521,8 löpfot**.

**Samla kapningarna per fas över alla moduler**, inte modul för modul.

#### 3. Bygg Modulramarna

1. Bygg varje modulram plant
2. Foga ihop listerna vid geringarna och kontrollera varje vinkel
3. Fäst fogarna med GRK-skruv
4. Förbind yttre och inre lister med klosslagret. Det ger den 5,0 in tjocka väggen
5. Provpassa grannmoduler innan du fäster dem

#### 4. Montera på Golvbjälklaget

1. Bygg golvbjälklaget först. Det är planet där varje förlängd sida slutar
2. Ställ de nedre modulerna (B, C, E) på golvbjälklaget och arbeta uppåt
3. Håll modulerna på plats med tillfälliga stöd
4. Arbeta i sektioner så att det blir stabilt

**Hörngenomföringar:** i vart och ett av de fyra inre hörnen blir det en triangulär öppning i golvhöjd,
4,671 in hög × 3,394 in bred. Den är en installationsgenomföring in i väggens hålrum (rymmer ett 3 in-rör
eller en kabelbunt). Stäng den med ett avtagbart lock. Fyll inte igen den.

#### 5. Sätt Panelerna

**Yttre skiva — överlapp leder bort vatten:**
- Panelen vars mittpunkt sitter högre överlappar den lägre. **Montera nerifrån och upp.**
- Varje överlapp är 1,5 in, samma som listens tjocklek, så den vilar helt på listen hos panelen under och kan skruvas i den.
- **Såga ett kapillärbrott på undersidan av varje överlappande kant:** ett spår ⅛ in brett × ⅛ in djupt, 0,5 in in från kanten. Utan det sugs vatten uppåt mellan skivorna, oavsett överlappets längd.
- De åtta ekvatoriella ytorna är lodräta. Deras lodräta fogar får en tätningslist eller täcklist, inte överlapp.
- Nocken är den enda fogen utan högre sida. Täta den med en tätningslist.

**Inre skiva:**
- Kapa så att den passar den inre ramen

**Montering:**
1. Slipa kanterna släta
2. Stryk silikonfog på ramkanterna
3. Tryck panelerna på plats och skruva fast dem runt om
4. Torka bort överflödig fog

#### 6. Väderskydda

**Täta alla fogar:**
- Stryk silikonfog på alla yttre fogar
- Var särskilt noga med panelkanterna
- Låt härda i 24 timmar

**Ytbehandla:**
- Måla eller försegla alla träytor
- Använd utomhusfärg för bruk utomhus
- Stryk flera lager för hållbarhet

### Proffstips

- **Samla per fas**: sortera virket och gruppera kapningar per fas, aldrig per modul
- **Ta god tid**: Precision i vinklarna är avgörande
- **Provpassa**: Torrmontera sektioner före slutmontering
- **Använd jiggar**: Gör enkla jiggar som håller delarna i rätt vinkel
- **Arbeta två och två**: Vissa monteringssteg går lättare med hjälp
- **Kontrollera måtten**: Kontrollera varje del innan du kapar

### Resurser

- [Compound Miter Saw Calculator](https://jansson.us/jcompound.html) - För att räkna ut exakta vinklar
- [GRK FIN/Trim™-skruv](https://grkfasteners.ca/product/fin-trim-finishing-trim-head-screw/) - Rekommenderas för en ren finish
- [McMaster-Carr Hardware](https://www.mcmaster.com/90273A572/) - För fler fästelement

### Snabbreferens

| | Värde |
|---|---:|
| Ytterdiameter | 93,700 in |
| Kantlängd, yttre / inre | 18,906 / 16,701 in |
| Fas, hexagon ↔ hexagon | 20,905° |
| Fas, hexagon ↔ pentagon | 18,689° |
| Gering, hexagon / pentagon / drakspets | 30° / 36° / 36° |
| Bredd på kluven halva (⅛ in snitt) | 1,6875 in |
| Väggtjocklek | 5,0 in |
| Moduler | 23 |
| 2×4-reglar, 96 in | 36 |
| 4×8-skivor, ¼ in / ¾ in | 16 / 2 |

## 📁 Projektstruktur

```
Thiosphere-Open-Source-Repo/
├── README.md                    # Denna fil (Engelska)
├── README.de.md                 # Tysk dokumentation
├── README.es.md                 # Spansk dokumentation
├── README.fr.md                 # Fransk dokumentation
├── README.sv.md                 # Svensk dokumentation
├── README.fi.md                 # Finsk dokumentation
├── LICENSE.md                   # CERN Open Hardware License v2
├── thiosphere-design-document.md # Komplett designdokumentation
├── Bill_of_Materials_v.0.1.csv  # Materiallista
├── src/                         # Källfiler
│   ├── thiosphere_0.01.step     # CAD-modell (STEP-format)
│   └── thiosphere-fine.stl      # 3D-modell (STL-format)
├── _media/                      # Bilder och media
└── docs/                        # Ytterligare dokumentation
```

## 🤝 Bidra

Vi välkomnar bidrag till Thiosphere-projektet! Läs våra bidragsriktlinjer:

1. **Forka repository**
2. **Skapa en funktionsgren** (`git checkout -b feature/amazing-feature`)
3. **Committa dina ändringar** (`git commit -m 'Add some amazing feature'`)
4. **Pusha till grenen** (`git push origin feature/amazing-feature`)
5. **Öppna en Pull Request**

### Bidragsriktlinjer

- Följ CERN Open Hardware License v2-kraven
- Dokumentera alla modifieringar grundligt
- Inkludera uppdaterad materiallista om ändringar påverkar material
- Testa dina modifieringar före inlämning
- Tillhandahåll tydlig dokumentation för alla nya funktioner

## 📄 Licens

Detta projekt är licensierad under **CERN Open Hardware License Version 2 - Starkt Reciprok**. Se filen [LICENSE.md](LICENSE.md) för detaljer.

## 🔗 Länkar

- **Webbplats**: [https://thiosphere.org](https://thiosphere.org)
- **Design-dokument**: [thiosphere-design-document.md](thiosphere-design-document.md)
- **Materiallista**: [Bill_of_Materials_v.0.0.1.csv](Bill_of_Materials_v.0.1.csv)
- **CAD-modeller**: [src/](src/)

## 🙏 Tacksägelser

- CERN för Open Hardware License
- Open Source-hårdvarusamhället
- Alla bidragsgivare och byggare som har hjälpt till att utveckla Thiosphere

---

**Thiospheres - Domus Opus Est** (arbetet med skydd tar aldrig slut).

*"Vi har formaterat vår värld för bilar, men har lite annat för att använda allt det utrymme vi har gett över till dessa maskiner."*

---

*Detta projekt skapas och sponsras av [thios.co](https://thios.co)*
