# Thiosphere - Modulare Open-Source-Unterkünfte

[![CERN Open Hardware License v2](https://img.shields.io/badge/License-CERN%20OHL%20v2%20Strongly%20Reciprocal-blue.svg)](LICENSE.md)
[![Open Source Hardware](https://img.shields.io/badge/Open%20Source-Hardware-green.svg)](https://www.oshwa.org/)
[![Documentation](https://img.shields.io/badge/Documentation-Complete-brightgreen.svg)](docs/)

[🇺🇸 English](README.md) | [🇩🇪 Deutsch](README.de.md) | [🇪🇸 Español](README.es.md) | [🇫🇷 Français](README.fr.md) | [🇸🇪 Svenska](README.sv.md) | [🇫🇮 Suomi](README.fi.md)

---

# Modulare Open-Source-Unterkünfte

Wir haben unsere Welt für Autos formatiert, haben aber wenig anderes, um all den Platz zu nutzen, den wir diesen Maschinen überlassen haben. Ein Thiosphere™ wird geschaffen, um diese Lücke mit einem Zweck und einer Schönheit zu füllen, die sein kühnes und effizientes Design definiert. Es ist Open Source Hardware, die jeder nach seinen eigenen Bedürfnissen bauen und modifizieren kann.

## Einführung

Ein Thiosphere besteht aus der kleinstmöglichen Anzahl von Teilen und ergibt dennoch einen starken, leichten und geräumigen, modulare Unterkunft, die nur 1/2 eines Parkplatzes einnimmt. Er ist flach packbar und kann mit gewöhnlichen Werkzeugen montiert werden. Er ist modular, sodass Sie eine endlose Anzahl von Bauwerken schaffen können, von einem einfachen Unterschlupf bis zu einem komplexen Büro. Er ist sowohl funktional als auch schön und so konzipiert, dass er ein zweiter Ort ist, an dem das Leben gedeihen kann - was auch immer und wo auch immer diese Anforderungen sind.

![Thiosphere Grundlagen](_media/football.png)
![Thiosphere Grundlagen](_media/basics.png)
![Thiosphere Flachansicht](_media/flatten.png)

### Open Source Hardware Lizenz

Verständnis unserer Open Hardware Lizenz
Die CERN Open Hardware License (Version 2 - Strongly Reciprocal) stellt sicher, dass:

- Alle Designs und Modifikationen müssen offen geteilt werden
- Kommerzielle Nutzung ist mit ordnungsgemäßer Namensnennung erlaubt
- Modifizierte Versionen müssen unter derselben Lizenz geteilt werden
- Ursprüngliche Ersteller müssen anerkannt werden
- Dokumentation muss für alle Änderungen bereitgestellt werden

![Thiosphere Maßstab](_media/module.png)
![Thiosphere Maßstab](_media/scale.png)

## Die Vorteile

- **Stark gebaut**: Sphärische Geometrie = maximale Stärke, minimales Material
- **Bleibt kühl**: Natürliche Konvektion hält die Umgebung innen stabil
- **Passt perfekt**: Konzipiert für bestehende Parkplätze - keine Modifikationen erforderlich
- **Einfach zu bauen**: Einfache Geometrie bedeutet, Sie können es lokal mit grundlegenden Werkzeugen herstellen

## Was ist ein Thios?

> Die Zahl zwei wird im Griechischen als "δύο" geschrieben und mit einem weichen "th" Laut (thío) ausgesprochen, anstatt des harten "d", den man erwarten könnte. Dieses "thio" Präfix beschreibt perfekt das Dual-Sphären-Design des Thiosphere™, einen zweiten Ort für das Leben.

## Schnellstart

### 📋 Voraussetzungen

- Grundlegende Holzbearbeitungsfähigkeiten
- Zugang zu Standardwerkzeugen (siehe Bauanleitung)
- Verständnis der CERN Open Hardware License

### 🛠️ Erste Schritte

1. **Dokumentation prüfen**: Beginnen Sie mit dem [Design-Dokument](thiosphere-design-document.md)
2. **Materialien prüfen**: Überprüfen Sie die [Stückliste](Bill_of_Materials_v.0.1.csv)
3. **Lizenz verstehen**: Lesen Sie die [CERN Open Hardware License](LICENSE.md)
4. **Mit dem Bau beginnen**: Folgen Sie der Bauanleitung unten

## Bauanleitung

> **Woher diese Zahlen stammen.** Alle Werte unten sind am finalen Onshape-Modell
> *Thiosphere for prints* bei `#maxWidth` = 93,700 in gemessen (verifiziert am 2026-09-12). Wo das ältere
> [Designdokument](thiosphere-design-document.md) oder die
> [Stückliste v0.1](Bill_of_Materials_v.0.1.csv) abweichen, gilt diese Anleitung.

### Auf einen Blick

| | |
|---|---|
| Außendurchmesser | **93,700 in** (7 ft 9,7 in) |
| Kantenlänge, Außenschale | **18,906 in** |
| Kantenlänge, Innenschale | **16,701 in** |
| Wandstärke | **5,0 in** — ¼ Beplankung + 1½ Leiste + 1½ Klotz + 1½ Leiste + ¼ Beplankung |
| Lichte Höhe über dem fertigen Boden, am First | **79,829 in** |
| Bodendeck | 12-eckig, 88,543 × 91,773 in |
| Module | **23** |

Die Form ist ein abgestumpftes Ikosaeder (32 Flächen: 20 Sechsecke, 12 Fünfecke). Sie steht
auf einer Kante, nicht auf einer Fläche.

### Die 23 Module

Nur die 22 Flächen auf Höhe des unteren Sechseckrings und darüber sind Paneele. Die 10 Flächen
darunter werden nicht gebaut: Die Typen B, C und E reichen nach unten bis zum Deck und ersetzen sie.

| Typ | Modul | Anzahl | Aufbau |
|---|---|---:|---|
| A | Einfaches Sechseck | 8 | Regelmäßiges Sechseck |
| B | Tür | 4 | Sechseck, zwei senkrechte Seiten bis zum Deck verlängert |
| C | Seitenwand | 2 | Sechseck, zwei schräge Seiten bis zum Deck verlängert |
| D | Einfaches Fünfeck | 4 | Regelmäßiges Fünfeck |
| E | Eckdrachen | 4 | Fünfeck, zwei Seiten verlängert, bis sie sich treffen |
| FL | Bodendeck | 1 | 12-eckig, zwei Platten ¾ in Sperrholz |
| | **Summe** | **23** | |

### Was Sie brauchen

**Material:**
- **36** × 2×4-Kanthölzer, 96 in lang — jedes wird mittig aufgetrennt (inklusive 8,5% für Schnittfuge und Verschnitt)
- **16** × 4×8-Platten ¼ in Sperrholz — Außen- und Innenbeplankung, mit 35% für die Schachtelung
- **2** × 4×8-Platten ¾ in Sperrholz — Bodendeck
- Schrauben, Bolzen sowie Rollen, Anhänger oder ein Nivellier-Sockel — die Mengen werden für das aktuelle Modell neu ermittelt und erst nach der Prüfung angegeben

**Werkzeug:**
- Tischkreissäge mit schwenkbarem Sägeblatt (die Fase entsteht beim Auftrennen)
- Kapp- und Gehrungssäge
- Bohrschrauber
- Maßband und Bleistift
- Schutzausrüstung (Brille, Gehörschutz)

### Schritt-für-Schritt-Bau

#### 1. Holz sortieren, dann auftrennen

**Es gibt zwei Fasenwinkel, nicht einen.**

| Leiste liegt zwischen | Fase |
|---|---:|
| Sechseck ↔ Sechseck | **20,905°** |
| Sechseck ↔ Fünfeck | **18,689°** |

- Jedes 2×4 wird mit geschwenktem Sägeblatt mittig aufgetrennt. Ein Schnitt erzeugt die Fase und zwei Leisten.
- Bei ⅛ in Schnittfuge ist jede Hälfte 1,6875 in breit.
- Die Fase wird beim Auftrennen festgelegt, und eine Hälfte lässt sich nicht erneut auftrennen. **Legen Sie vor dem Auftrennen fest, welche Fase die Leisten jedes Kantholzes brauchen.**
- Ein Sechseckmodul braucht **beide** Fasen: Seine Kanten grenzen abwechselnd an Sechsecke und Fünfecke. Ein Fünfeckmodul hat an allen fünf Kanten 18,689°.

> ⚠️ **Verwenden Sie keine gemittelte Fase von etwa 19,8°.** Sie öffnet an jeder Verbindung
> eine Fuge von etwa 5⁄64 in, und die Fugen summieren sich an jeder Ecke, an der drei Leisten zusammentreffen.

#### 2. Leisten auf Länge schneiden

**Gehrungen:** 30° an Sechseckecken, 36° an Fünfeckecken, 36° an der Drachenspitze.

**Längen** (Spitze zu Spitze):

| Leiste | Außenschale | Innenschale |
|---|---:|---:|
| Einfache Kanten — Typen A und D sowie die nicht verlängerten Kanten von B, C und E | 18,906 in | 16,701 in |
| B · Tür, senkrechte Seite | 49,497 in | 49,056 in |
| B · Tür, Deckschwelle | 32,747 in | 31,218 in |
| C · Seitenwand, schräge Seite | 49,497 in | 49,497 in |
| C · Seitenwand, Deckschwelle | 68,403 in | 67,521 in |
| E · Eckdrachen, verlängerte Seite | 49,497 in | 43,724 in |

**Erzeugen Sie die Innenschale nicht durch Skalieren der Außenschale.** Die verlängerten Seiten
enden am Deck, und das Deck bewegt sich nicht, daher werden sie weniger oder gar nicht kürzer als
die einfachen Kanten. Deshalb hat die Innenschale sechs Leistenlängen und die Außenschale vier.

**Gesamter Leistenbedarf:** Außenschale 112 Leisten (240,3 ft), Innenschale 112 Leisten (218,3 ft),
Klötze 224 Stück (63,2 ft) — **521,8 laufende ft**.

**Bündeln Sie die Schnitte nach Fase über alle Module hinweg**, nicht Modul für Modul.

#### 3. Modulrahmen bauen

1. Bauen Sie jeden Modulrahmen flach
2. Verbinden Sie die Leisten an den Gehrungen und prüfen Sie jeden Winkel
3. Sichern Sie die Verbindungen mit GRK-Schrauben
4. Verbinden Sie äußere und innere Leisten mit der Klotzlage. Sie ergibt die 5,0 in Wandstärke
5. Passen Sie benachbarte Module trocken an, bevor Sie sie befestigen

#### 4. Auf dem Deck montieren

1. Bauen Sie zuerst das Bodendeck. Es ist die Ebene, an der jede verlängerte Seite endet
2. Stellen Sie die unteren Module (B, C, E) auf das Deck und arbeiten Sie sich nach oben
3. Halten Sie Module mit provisorischen Stützen in Position
4. Arbeiten Sie abschnittsweise, damit alles stabil bleibt

**Eckdurchlässe:** An jeder der vier inneren Ecken bleibt auf Bodenhöhe eine dreieckige Öffnung,
4,671 in hoch × 3,394 in breit. Sie ist ein Leitungsdurchlass in den Wandhohlraum (für 3-in-Rohr
oder ein Leitungsbündel). Schließen Sie sie mit einer abnehmbaren Abdeckung. Füllen Sie sie nicht aus.

#### 5. Paneele anbringen

**Außenbeplankung — Überlappungen leiten Wasser ab:**
- Das Paneel mit dem höher liegenden Mittelpunkt überlappt das tiefere. **Montieren Sie von unten nach oben.**
- Jede Überlappung ist 1,5 in breit, genau wie die Leistenstärke, liegt also vollständig auf der Leiste des Paneels darunter und lässt sich dort verschrauben.
- **Schneiden Sie an der Unterseite jeder überlappenden Kante eine Kapillarsperre:** eine Nut ⅛ in breit × ⅛ in tief, 0,5 in von der Kante. Ohne sie zieht Wasser zwischen den Platten nach oben, egal wie lang die Überlappung ist.
- Die acht Flächen am Äquator stehen senkrecht. Ihre senkrechten Fugen erhalten eine Dichtung oder Deckleiste, keine Überlappung.
- Der First ist die einzige Fuge ohne höher liegende Seite. Dichten Sie ihn mit einer Dichtung ab.

**Innenbeplankung:**
- Passend zum inneren Rahmen zuschneiden

**Montage:**
1. Kanten glatt schleifen
2. Silikon-Dichtmasse auf die Rahmenkanten auftragen
3. Paneele andrücken und rundum verschrauben
4. Überschüssige Dichtmasse abwischen

#### 6. Wetterfest machen

**Alle Fugen abdichten:**
- Silikon-Dichtmasse auf alle Außenfugen auftragen
- Besonders auf Paneelkanten achten
- 24 Stunden aushärten lassen

**Oberfläche behandeln:**
- Alle Holzflächen streichen oder versiegeln
- Für den Außenbereich wetterfeste Farbe verwenden
- Mehrere Schichten auftragen

### Profi-Tipps

- **Nach Fase bündeln**: Holz sortieren und Schnitte nach Fase gruppieren, nie nach Modul
- **Nehmen Sie sich Zeit**: Präzision bei den Winkeln entscheidet
- **Probe-Montage**: Abschnitte vor der Endmontage trocken zusammensetzen
- **Schablonen nutzen**: Einfache Vorrichtungen halten Teile im richtigen Winkel
- **Zu zweit arbeiten**: Manche Montageschritte gehen mit Hilfe leichter
- **Maße prüfen**: Jedes Teil vor dem Schnitt kontrollieren

### Ressourcen

- [Compound Miter Saw Calculator](https://jansson.us/jcompound.html) - Zur Berechnung präziser Winkel
- [GRK FIN/Trim™ Schrauben](https://grkfasteners.ca/product/fin-trim-finishing-trim-head-screw/) - Empfohlen für ein sauberes Finish
- [McMaster-Carr Hardware](https://www.mcmaster.com/90273A572/) - Für weitere Befestigungsteile

### Kurzreferenz

| | Wert |
|---|---:|
| Außendurchmesser | 93,700 in |
| Kantenlänge, außen / innen | 18,906 / 16,701 in |
| Fase, Sechseck ↔ Sechseck | 20,905° |
| Fase, Sechseck ↔ Fünfeck | 18,689° |
| Gehrung, Sechseck / Fünfeck / Drachenspitze | 30° / 36° / 36° |
| Breite einer aufgetrennten Hälfte (⅛ in Fuge) | 1,6875 in |
| Wandstärke | 5,0 in |
| Module | 23 |
| 2×4-Kanthölzer, 96 in | 36 |
| 4×8-Platten, ¼ in / ¾ in | 16 / 2 |

## 📁 Projektstruktur

```
Thiosphere-Open-Source-Repo/
├── README.md                    # Diese Datei (Englisch)
├── README.de.md                 # Deutsche Dokumentation
├── README.es.md                 # Spanische Dokumentation
├── README.fr.md                 # Französische Dokumentation
├── README.sv.md                 # Schwedische Dokumentation
├── README.fi.md                 # Finnische Dokumentation
├── LICENSE.md                   # CERN Open Hardware License v2
├── thiosphere-design-document.md # Vollständige Design-Dokumentation
├── Bill_of_Materials_v.0.1.csv  # Materialliste
├── src/                         # Quelldateien
│   ├── thiosphere_0.01.step     # CAD-Modell (STEP-Format)
│   └── thiosphere-fine.stl      # 3D-Modell (STL-Format)
├── _media/                      # Bilder und Medien
└── docs/                        # Zusätzliche Dokumentation
```

## 🤝 Beitragen

Wir begrüßen Beiträge zum Thiosphere-Projekt! Bitte lesen Sie unsere Beitragsrichtlinien:

1. **Repository forken**
2. **Feature-Branch erstellen** (`git checkout -b feature/amazing-feature`)
3. **Änderungen committen** (`git commit -m 'Add some amazing feature'`)
4. **Zum Branch pushen** (`git push origin feature/amazing-feature`)
5. **Pull Request öffnen**

### Beitragsrichtlinien

- Folgen Sie den CERN Open Hardware License v2 Anforderungen
- Dokumentieren Sie alle Modifikationen gründlich
- Fügen Sie aktualisierte Stückliste hinzu, wenn Änderungen Materialien betreffen
- Testen Sie Ihre Modifikationen vor der Einreichung
- Stellen Sie klare Dokumentation für alle neuen Funktionen bereit

## 📄 Lizenz

Dieses Projekt ist unter der **CERN Open Hardware License Version 2 - Strongly Reciprocal** lizenziert. Siehe die [LICENSE.md](LICENSE.md) Datei für Details.

## 🔗 Links

- **Website**: [https://thiosphere.org](https://thiosphere.org)
- **Design-Dokument**: [thiosphere-design-document.md](thiosphere-design-document.md)
- **Stückliste**: [Bill_of_Materials_v.0.1.csv](Bill_of_Materials_v.0.1.csv)
- **CAD-Modelle**: [src/](src/)

## 🙏 Danksagungen

- CERN für die Open Hardware License
- Die Open Source Hardware Community
- Alle Mitwirkenden und Bauherren, die bei der Entwicklung des Thiosphere geholfen haben

---

**Thiospheres - Domus Opus Est** (die Arbeit am Obdach endet nie).

*"Wir haben unsere Welt für Autos formatiert, haben aber wenig anderes, um all den Platz zu nutzen, den wir diesen Maschinen überlassen haben."*

---

*Dieses Projekt wird erstellt und gesponsert von [thios.co](https://thios.co)*
