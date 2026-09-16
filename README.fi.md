# Thiosphere - Modulaariset Open Source -suojat

[![CERN Open Hardware License v2](https://img.shields.io/badge/License-CERN%20OHL%20v2%20Strongly%20Reciprocal-blue.svg)](LICENSE.md)
[![Open Source Hardware](https://img.shields.io/badge/Open%20Source-Hardware-green.svg)](https://www.oshwa.org/)
[![Documentation](https://img.shields.io/badge/Documentation-Complete-brightgreen.svg)](docs/)

[🇺🇸 English](README.md) | [🇩🇪 Deutsch](README.de.md) | [🇪🇸 Español](README.es.md) | [🇫🇷 Français](README.fr.md) | [🇸🇪 Svenska](README.sv.md) | [🇫🇮 Suomi](README.fi.md)

---

# Modulaariset Open Source -suojat

Olemme muotoilleet maailmamme autoille, mutta meillä on vähän muuta käyttää kaikille niille tiloille, jotka olemme antaneet näille koneille. Thiosphere™ luodaan täyttämään tuo tyhjiö tarkoituksella ja kauneudella, jotka määrittelevät sen rohkean ja tehokkaan suunnittelun. Se on Open Source -laitteisto, jota kuka tahansa voi rakentaa ja muokata omiin tarpeisiinsa.

## Johdanto

Yksi thiosphere on valmistettu mahdollisimman vähästä osista, mutta tuloksena on vahva, kevyt ja tilava modulaarinen suoja, joka vie vain 1/2 pysäköintipaikasta. Se on litteä pakattavissa ja voidaan koota yleisillä työkaluilla. Se on modulaarinen, joten voit luoda loputtoman määrän rakennelmia, yksinkertaisesta suojasta monimutkaiseen toimistoon. Se on sekä toiminnallinen että kaunis, ja suunniteltu olemaan toinen paikka, jossa elämä voi kukoistaa - mitä tahansa ja missä tahansa nuo vaatimukset ovat.

![Thiosphere Perusteet](_media/football.png)
![Thiosphere Perusteet](_media/basics.png)
![Thiosphere Litteä Näkymä](_media/flatten.png)

### Open Source -laitteistolisenssi

Ymmärrämme Open Hardware -lisenssimme
CERN Open Hardware License (Version 2 - Vahvasti Vastavuoroinen) varmistaa, että:

- Kaikki suunnitelmien ja muutosten on jaettava avoimesti
- Kaupallinen käyttö on sallittu asianmukaisella viittauksella
- Muokatut versiot on jaettava samalla lisenssillä
- Alkuperäiset luojat on mainittava
- Dokumentaation on oltava saatavilla kaikille muutoksille

![Thiosphere Mittakaava](_media/module.png)
![Thiosphere Mittakaava](_media/scale.png)

## Edut

- **Rakennettu Vahvaksi**: Pallomainen geometria = maksimaalinen lujuus, minimaalinen materiaali
- **Pysyy Viileänä**: Luonnollinen konvektio pitää ympäristön sisällä vakaina
- **Sopii Täydellisesti**: Suunniteltu olemassa oleville pysäköintipaikoille - ei tarvita muutoksia
- **Helppo Rakentaa**: Yksinkertainen geometria tarkoittaa, että voit tehdä sen paikallisesti perustyökaluilla

## Mikä on Thios?

> Numero kaksi kreikaksi kirjoitetaan "δύο" ja äännetään pehmeällä "th" äänellä (thío), harkin kovaa "d" ääntä, jota voisi odottaa. Tämä "thio" etuliite kuvaa täydellisesti Thiosphere™:n kaksisferisen suunnittelun, toisen paikan elämälle.

## Nopea Aloitus

### 📋 Edellytykset

- Perustason puuntyöstötaidot
- Pääsy standardityökaluihin (katso Rakennusopas)
- CERN Open Hardware -lisenssin ymmärtäminen

### 🛠️ Aloittaminen

1. **Tarkista Dokumentaatio**: Aloita [Suunnitteludokumentista](thiosphere-design-document.md)
2. **Tarkista Materiaalit**: Tarkista [Materiaalilista](Bill_of_Materials_v.0.1.csv)
3. **Ymmärrä Lisenssi**: Lue [CERN Open Hardware License](LICENSE.md)
4. **Aloita Rakentaminen**: Seuraa Rakennusopasta alla

## Rakennusopas

> **Mistä luvut tulevat.** Kaikki alla olevat arvot on mitattu lopullisesta Onshape-mallista
> *Thiosphere for prints* arvolla `#maxWidth` = 93,700 in (tarkistettu 2026-09-12). Jos vanhempi
> [suunnitteludokumentti](thiosphere-design-document.md) tai
> [materiaaliluettelo v0.1](Bill_of_Materials_v.0.1.csv) poikkeaa, tämä opas on oikea.

### Lyhyesti

| | |
|---|---|
| Ulkohalkaisija | **93,700 in** (7 ft 9,7 in) |
| Särmän pituus, ulkokuori | **18,906 in** |
| Särmän pituus, sisäkuori | **16,701 in** |
| Seinän paksuus | **5,0 in** — ¼ levy + 1½ rima + 1½ kappale + 1½ rima + ¼ levy |
| Vapaa korkeus valmiin lattian yläpuolella, harjalla | **79,829 in** |
| Lattiataso | 12-kulmainen, 88,543 × 91,773 in |
| Moduulit | **23** |

Muoto on katkaistu ikosaedri (32 tahkoa: 20 kuusikulmiota, 12 viisikulmiota). Se lepää
särmän, ei tahkon, varassa.

### 23 Moduulia

Vain ne 22 tahkoa, jotka ovat alemman kuusikulmiorenkaan korkeudella tai sen yläpuolella, ovat paneeleja.
Alapuolen 10 tahkoa ei rakenneta: tyypit B, C ja E jatkuvat lattiatasoon asti ja korvaavat ne.

| Tyyppi | Moduuli | Määrä | Miten se tehdään |
|---|---|---:|---|
| A | Tavallinen kuusikulmio | 8 | Säännöllinen kuusikulmio |
| B | Ovi | 4 | Kuusikulmio, kaksi pystysivua jatkettu lattiatasoon |
| C | Sivuseinä | 2 | Kuusikulmio, kaksi vinoa sivua jatkettu lattiatasoon |
| D | Tavallinen viisikulmio | 4 | Säännöllinen viisikulmio |
| E | Kulmaleija | 4 | Viisikulmio, kaksi sivua jatkettu, kunnes ne kohtaavat |
| FL | Lattiataso | 1 | 12-kulmainen, kaksi ¾ in vanerilevyä |
| | **Yhteensä** | **23** | |

### Mitä Tarvitset

**Materiaalit:**
- **36** × 2×4-runkopuuta, 96 in pitkiä — jokainen halkaistaan keskeltä (sisältää 8,5% sahausrakoa ja hukkapaloja varten)
- **16** × 4×8-levyä ¼ in vaneria — ulko- ja sisäverhous, 35% sijoittelun hukkaa varten
- **2** × 4×8-levyä ¾ in vaneria — lattiataso
- Ruuvit, pultit sekä pyörät, peräkärry tai tasausalusta — määriä lasketaan uudelleen nykyiselle mallille, eikä niitä ilmoiteta ennen tarkistusta

**Työkalut:**
- Pöytäsirkkeli kallistettavalla terällä (viiste sahataan halkaisussa)
- Katkaisu- ja jiirisaha
- Porakone/ruuvinväännin
- Mittanauha ja kynä
- Suojavarusteet (lasit, kuulosuojaimet)

### Rakentaminen Vaihe Vaiheelta

#### 1. Lajittele Puutavara, Halkaise Sitten

**Viistekulmia on kaksi, ei yksi.**

| Rima on välissä | Viiste |
|---|---:|
| Kuusikulmio ↔ kuusikulmio | **20,905°** |
| Kuusikulmio ↔ viisikulmio | **18,689°** |

- Jokainen 2×4 halkaistaan keskeltä terä viistekulmaan kallistettuna. Yksi sahaus tekee viisteen ja kaksi rimaa.
- ⅛ in sahausraolla kumpikin puolikas on 1,6875 in leveä.
- Viiste määräytyy halkaisussa, eikä puolikasta voi halkaista uudelleen. **Päätä ennen halkaisua, mitä viistettä kunkin runkopuun rimat tarvitsevat.**
- Kuusikulmiomoduuli tarvitsee **molemmat** viisteet: sen särmien naapurit vuorottelevat kuusikulmion ja viisikulmion välillä. Viisikulmiomoduulin kaikissa viidessä särmässä on 18,689°.

> ⚠️ **Älä käytä yhtä noin 19,8°:n keskiarvoviistettä.** Se avaa jokaiseen liitokseen noin 5⁄64 in
> raon, ja raot kasautuvat jokaisessa kulmassa, jossa kolme rimaa kohtaa.

#### 2. Katkaise Rimat Mittaan

**Jiirit:** 30° kuusikulmion kulmissa, 36° viisikulmion kulmissa, 36° leijan kärjessä.

**Pituudet** (kärjestä kärkeen):

| Rima | Ulkokuori | Sisäkuori |
|---|---:|---:|
| Tavalliset särmät — tyypit A ja D sekä B:n, C:n ja E:n jatkamattomat särmät | 18,906 in | 16,701 in |
| B · ovi, pystysivu | 49,497 in | 49,056 in |
| B · ovi, kynnys | 32,747 in | 31,218 in |
| C · sivuseinä, vino sivu | 49,497 in | 49,497 in |
| C · sivuseinä, kynnys | 68,403 in | 67,521 in |
| E · kulmaleija, jatkettu sivu | 49,497 in | 43,724 in |

**Älä tee sisäkuorta skaalaamalla ulkokuorta.** Jatketut sivut päättyvät lattiatasoon, eikä
lattiataso liiku, joten ne lyhenevät vähemmän kuin tavalliset särmät tai eivät lainkaan. Siksi
sisäkuoressa on kuusi rimapituutta ja ulkokuoressa neljä.

**Rimaa yhteensä:** ulkokuori 112 rimaa (240,3 ft), sisäkuori 112 rimaa (218,3 ft),
kappaleet 224 kpl (63,2 ft) — **521,8 jalkaa**.

**Ryhmittele sahaukset viisteen mukaan kaikkien moduulien yli**, älä moduuli kerrallaan.

#### 3. Rakenna Moduulien Kehykset

1. Rakenna jokainen kehys tasaisella alustalla
2. Liitä rimat jiireistä ja tarkista jokainen kulma
3. Kiinnitä liitokset GRK-ruuveilla
4. Yhdistä ulko- ja sisärimat kappalekerroksella. Se muodostaa 5,0 in seinän
5. Sovita viereiset moduulit kuivana ennen kiinnitystä

#### 4. Kokoa Lattiatason Päälle

1. Rakenna ensin lattiataso. Se on taso, johon jokainen jatkettu sivu päättyy
2. Nosta alemmat moduulit (B, C, E) lattiatasolle ja etene ylöspäin
3. Tue moduulit paikalleen väliaikaisilla tuilla
4. Työskentele osissa, jotta rakenne pysyy tukevana

**Kulmaläpiviennit:** jokaiseen neljään sisäkulmaan jää lattian tasolle kolmion muotoinen aukko,
4,671 in korkea × 3,394 in leveä. Se on talotekniikan läpivienti seinän onteloon (siihen mahtuu 3 in
putki tai kaapelinippu). Sulje se irrotettavalla kannella. Älä täytä sitä.

#### 5. Asenna Paneelit

**Ulkoverhous — limitykset ohjaavat veden pois:**
- Paneeli, jonka keskipiste on ylempänä, limittyy alemman päälle. **Asenna alhaalta ylöspäin.**
- Jokainen limitys on 1,5 in, sama kuin riman paksuus, joten se lepää kokonaan alemman paneelin riman päällä ja siihen voi ruuvata.
- **Sahaa kapillaarikatko jokaisen limittyvän reunan alapintaan:** ⅛ in leveä × ⅛ in syvä ura, 0,5 in päässä reunasta. Ilman sitä vesi nousee levyjen väliin kapillaarisesti, oli limitys kuinka pitkä tahansa.
- Kahdeksan päiväntasaajan tahkoa ovat pystysuoria. Niiden pystysaumoihin tulee tiiviste tai peitelista, ei limitystä.
- Harja on ainoa sauma, jolla ei ole ylempää puolta. Tiivistä se tiivisteellä.

**Sisäverhous:**
- Leikkaa sopimaan sisäkehykseen

**Asennus:**
1. Hio reunat sileiksi
2. Levitä silikonimassaa kehyksen reunoille
3. Paina paneelit paikalleen ja ruuvaa ne kiinni koko kehältä
4. Pyyhi ylimääräinen massa pois

#### 6. Säänsuojaa

**Tiivistä kaikki saumat:**
- Levitä silikonimassaa kaikkiin ulkosaumoihin
- Kiinnitä erityistä huomiota paneelien reunoihin
- Anna kovettua 24 tuntia

**Viimeistele:**
- Maalaa tai käsittele kaikki puupinnat
- Käytä ulkomaalia ulkokäytössä
- Levitä useita kerroksia kestävyyden vuoksi

### Ammattilaisvinkit

- **Ryhmittele viisteen mukaan**: lajittele puutavara ja ryhmittele sahaukset viisteen mukaan, ei koskaan moduuleittain
- **Ota aikaa**: Kulmien tarkkuus on ratkaisevaa
- **Sovita kuivana**: Kokoa osat kuivana ennen lopullista kokoamista
- **Käytä jigejä**: Tee yksinkertaisia jigejä, jotka pitävät osat oikeassa kulmassa
- **Työskentele pareittain**: Jotkin kokoamisvaiheet ovat helpompia avustajan kanssa
- **Tarkista mitat**: Tarkista jokainen osa ennen sahausta

### Resurssit

- [Compound Miter Saw Calculator](https://jansson.us/jcompound.html) - Tarkkojen kulmien laskemiseen
- [GRK FIN/Trim™ -ruuvit](https://grkfasteners.ca/product/fin-trim-finishing-trim-head-screw/) - Suositellaan siistiin lopputulokseen
- [McMaster-Carr Hardware](https://www.mcmaster.com/90273A572/) - Lisäkiinnikkeisiin

### Pikaopas

| | Arvo |
|---|---:|
| Ulkohalkaisija | 93,700 in |
| Särmän pituus, ulko / sisä | 18,906 / 16,701 in |
| Viiste, kuusikulmio ↔ kuusikulmio | 20,905° |
| Viiste, kuusikulmio ↔ viisikulmio | 18,689° |
| Jiiri, kuusikulmio / viisikulmio / leijan kärki | 30° / 36° / 36° |
| Halkaistun puolikkaan leveys (⅛ in rako) | 1,6875 in |
| Seinän paksuus | 5,0 in |
| Moduulit | 23 |
| 2×4-runkopuut, 96 in | 36 |
| 4×8-levyt, ¼ in / ¾ in | 16 / 2 |

## 📁 Projektirakenne

```
Thiosphere-Open-Source-Repo/
├── README.md                    # Tämä tiedosto (Englanti)
├── README.de.md                 # Saksalainen dokumentaatio
├── README.es.md                 # Espanjalainen dokumentaatio
├── README.fr.md                 # Ranskalainen dokumentaatio
├── README.sv.md                 # Ruotsalainen dokumentaatio
├── README.fi.md                 # Suomalainen dokumentaatio
├── LICENSE.md                   # CERN Open Hardware License v2
├── thiosphere-design-document.md # Täydellinen suunnitteludokumentaatio
├── Bill_of_Materials_v.0.1.csv  # Materiaalilista
├── src/                         # Lähdetiedostot
│   ├── thiosphere_0.01.step     # CAD-malli (STEP-muoto)
│   └── thiosphere-fine.stl      # 3D-malli (STL-muoto)
├── _media/                      # Kuvat ja media
└── docs/                        # Lisädokumentaatio
```

## 🤝 Osallistuminen

Tervetuloa osallistumaan Thiosphere-projektiin! Lue osallistumisohjeemme:

1. **Forkkaa repository**
2. **Luo ominaisuus-haara** (`git checkout -b feature/amazing-feature`)
3. **Commitoi muutoksesi** (`git commit -m 'Add some amazing feature'`)
4. **Pushaa haaraan** (`git push origin feature/amazing-feature`)
5. **Avaa Pull Request**

### Osallistumisohjeet

- Noudata CERN Open Hardware License v2 -vaatimuksia
- Dokumentoi kaikki muutokset perusteellisesti
- Sisällytä päivitetty materiaalilista, jos muutokset vaikuttavat materiaaleihin
- Testaa muutoksesi ennen lähettämistä
- Anna selkeä dokumentaatio kaikille uusille ominaisuuksille

## 📄 Lisenssi

Tämä projekti on lisensoitu **CERN Open Hardware License Version 2 - Vahvasti Vastavuoroinen** -lisenssillä. Katso tiedosto [LICENSE.md](LICENSE.md) yksityiskohdista.

## 🔗 Linkit

- **Verkkosivusto**: [https://thiosphere.org](https://thiosphere.org)
- **Suunnitteludokumentti**: [thiosphere-design-document.md](thiosphere-design-document.md)
- **Materiaalilista**: [Bill_of_Materials_v.0.1.csv](Bill_of_Materials_v.0.1.csv)
- **CAD-mallit**: [src/](src/)

## 🙏 Kiitokset

- CERN Open Hardware -lisenssistä
- Open Source -laitteistoyhteisölle
- Kaikille osallistujille ja rakentajille, jotka ovat auttaneet kehittämään Thiospherea

---

**Thiospheres - Domus Opus Est** (suojan työ ei koskaan lopu).

*"Olemme muotoilleet maailmamme autoille, mutta meillä on vähän muuta käyttää kaikille niille tiloille, jotka olemme antaneet näille koneille."*

---

*Tämän projektin on luonut ja sponssaa [thios.co](https://thios.co)*
