# Thiosphere - Abris Modulaires Open Source

[![CERN Open Hardware License v2](https://img.shields.io/badge/License-CERN%20OHL%20v2%20Strongly%20Reciprocal-blue.svg)](LICENSE.md)
[![Open Source Hardware](https://img.shields.io/badge/Open%20Source-Hardware-green.svg)](https://www.oshwa.org/)
[![Documentation](https://img.shields.io/badge/Documentation-Complete-brightgreen.svg)](docs/)

[🇺🇸 English](README.md) | [🇩🇪 Deutsch](README.de.md) | [🇪🇸 Español](README.es.md) | [🇫🇷 Français](README.fr.md) | [🇸🇪 Svenska](README.sv.md) | [🇫🇮 Suomi](README.fi.md)

---

# Abris Modulaires Open Source

Nous avons formaté notre monde pour les voitures, mais nous avons peu d'autre chose pour utiliser tout cet espace que nous avons cédé à ces machines. Un Thiosphere™ est créé pour combler ce vide avec un but et une beauté qui définissent son design audacieux et efficace. C'est du Hardware Open Source que n'importe qui peut construire et modifier selon ses propres besoins.

## Introduction

Un thiosphere est fabriqué avec le minimum de pièces possible, mais résulte en un abri modulaire fort, léger et spacieux qui n'occupe que 1/2 d'une place de stationnement. Il est emballable à plat et peut être assemblé avec des outils communs. Il est modulaire pour que vous puissiez créer un nombre infini de structures, d'un simple abri à un bureau complexe. Il est à la fois fonctionnel et beau, et conçu pour être un second lieu où la vie peut s'épanouir - quoi que ce soit et où que soient ces exigences.

![Bases du Thiosphere](_media/football.png)
![Bases du Thiosphere](_media/basics.png)
![Vue Aplatrie du Thiosphere](_media/flatten.png)

### Licence Hardware Open Source

Comprendre Notre Licence Hardware Open Source
La Licence Hardware Open Source de CERN (Version 2 - Fortement Réciproque) assure que :

- Tous les designs et modifications doivent être partagés ouvertement
- L'utilisation commerciale est permise avec l'attribution appropriée
- Les versions modifiées doivent être partagées sous la même licence
- Les créateurs originaux doivent être crédités
- La documentation doit être fournie pour tous les changements

![Échelle du Thiosphere](_media/module.png)
![Échelle du Thiosphere](_media/scale.png)

## Les Avantages

- **Construit Fort** : Géométrie sphérique = force maximale, matériau minimal
- **Reste Frais** : La convection naturelle maintient l'environnement stable à l'intérieur
- **S'Intègre Parfaitement** : Conçu pour les places de stationnement existantes - aucune modification nécessaire
- **Facile à Construire** : Géométrie simple signifie que vous pouvez le faire localement avec des outils de base

## Qu'est-ce qu'un Thios ?

> Le nombre deux en grec s'écrit "δύο" et se prononce avec un son "th" doux (thío), plutôt que le "d" dur qu'on pourrait attendre. Ce préfixe "thio" décrit parfaitement le design à double sphère du Thiosphere™, un second lieu pour la vie.

## Démarrage Rapide

### 📋 Prérequis

- Compétences de base en menuiserie
- Accès aux outils standard (voir Guide de Construction)
- Compréhension de la Licence Hardware Open Source de CERN

### 🛠️ Premiers Pas

1. **Examiner la Documentation** : Commencez par le [Document de Design](thiosphere-design-document.md)
2. **Vérifier les Matériaux** : Consultez la [Liste des Matériaux](Bill_of_Materials_v.0.1.csv)
3. **Comprendre la Licence** : Lisez la [Licence Hardware Open Source de CERN](LICENSE.md)
4. **Commencer la Construction** : Suivez le Guide de Construction ci-dessous

## Guide de Construction

> **D'où viennent ces chiffres.** Toutes les valeurs ci-dessous sont mesurées sur le modèle Onshape
> final *Thiosphere for prints* avec `#maxWidth` = 93,700 in (vérifié le 2026-09-12). Là où l'ancien
> [Document de Conception](thiosphere-design-document.md) ou la
> [Nomenclature v0.1](Bill_of_Materials_v.0.1.csv) diffèrent, ce guide fait foi.

### En un Coup d'Œil

| | |
|---|---|
| Diamètre extérieur | **93,700 in** (7 ft 9,7 in) |
| Longueur d'arête, coque extérieure | **18,906 in** |
| Longueur d'arête, coque intérieure | **16,701 in** |
| Épaisseur de paroi | **5,0 in** — ¼ parement + 1½ tasseau + 1½ cale + 1½ tasseau + ¼ parement |
| Hauteur libre au-dessus du sol fini, au faîte | **79,829 in** |
| Plancher | 12 côtés, 88,543 × 91,773 in |
| Modules | **23** |

La forme est un icosaèdre tronqué (32 faces : 20 hexagones, 12 pentagones). Elle repose sur
une arête, pas sur une face.

### Les 23 Modules

Seules les 22 faces situées au niveau de l'anneau inférieur d'hexagones ou au-dessus sont des panneaux.
Les 10 faces en dessous ne sont pas construites : les types B, C et E descendent jusqu'au plancher et les remplacent.

| Type | Module | Nombre | Construction |
|---|---|---:|---|
| A | Hexagone simple | 8 | Hexagone régulier |
| B | Porte | 4 | Hexagone, deux côtés verticaux prolongés jusqu'au plancher |
| C | Paroi latérale | 2 | Hexagone, deux côtés inclinés prolongés jusqu'au plancher |
| D | Pentagone simple | 4 | Pentagone régulier |
| E | Cerf-volant d'angle | 4 | Pentagone, deux côtés prolongés jusqu'à se rejoindre |
| FL | Plancher | 1 | 12 côtés, deux panneaux de contreplaqué de ¾ in |
| | **Total** | **23** | |

### Ce Dont Vous Aurez Besoin

**Matériaux :**
- **36** × montants 2×4 de 96 in — chacun est refendu en son centre (8,5 % inclus pour le trait de scie et les chutes)
- **16** × panneaux 4×8 de contreplaqué ¼ in — parements extérieur et intérieur, avec 35 % pour l'imbrication
- **2** × panneaux 4×8 de contreplaqué ¾ in — plancher
- Vis, boulons, et roulettes, remorque ou socle de mise à niveau — les quantités sont en cours de recalcul pour le modèle actuel et ne sont pas indiquées tant qu'elles ne sont pas vérifiées

**Outils :**
- Scie sur table à lame inclinable (le biseau se fait pendant le refendage)
- Scie à onglet radiale
- Perceuse-visseuse
- Mètre ruban et crayon
- Équipement de sécurité (lunettes, protection auditive)

### Construction Étape par Étape

#### 1. Triez le Bois, Puis Refendez

**Il y a deux biseaux, pas un.**

| Le tasseau est entre | Biseau |
|---|---:|
| Hexagone ↔ hexagone | **20,905°** |
| Hexagone ↔ pentagone | **18,689°** |

- Chaque 2×4 est refendu en son centre, lame inclinée à l'angle du biseau. Une passe fait le biseau et deux tasseaux.
- Avec un trait de scie de ⅛ in, chaque moitié mesure 1,6875 in de large.
- Le biseau est fixé au refendage, et une moitié ne peut pas être refendue à nouveau. **Décidez quel biseau les tasseaux de chaque montant nécessitent avant de le refendre.**
- Un module hexagonal a besoin des **deux** biseaux : ses arêtes alternent entre voisins hexagones et pentagones. Un module pentagonal utilise 18,689° sur ses cinq arêtes.

> ⚠️ **N'utilisez pas un biseau moyen unique d'environ 19,8°.** Il ouvre un jeu d'environ 5⁄64 in à
> chaque assemblage, et ces jeux s'additionnent à chaque coin où trois tasseaux se rejoignent.

#### 2. Coupez les Tasseaux à Longueur

**Onglets :** 30° aux coins d'hexagone, 36° aux coins de pentagone, 36° à la pointe du cerf-volant.

**Longueurs** (de pointe à pointe) :

| Tasseau | Coque extérieure | Coque intérieure |
|---|---:|---:|
| Arêtes simples — types A et D, et les arêtes non prolongées de B, C et E | 18,906 in | 16,701 in |
| B · porte, côté vertical | 49,497 in | 48,395 in |
| B · porte, seuil | 32,747 in | 28,927 in |
| C · paroi latérale, côté incliné | 49,497 in | 49,497 in |
| C · paroi latérale, seuil | 68,403 in | 66,198 in |
| E · cerf-volant d'angle, côté prolongé | 49,497 in | 43,724 in |

**Ne réalisez pas la coque intérieure en réduisant la coque extérieure à l'échelle.** Les côtés
prolongés s'arrêtent sur le plancher, et le plancher ne bouge pas : ils raccourcissent donc moins que
les arêtes simples, voire pas du tout. C'est pourquoi la coque intérieure a six longueurs de tasseau et l'extérieure quatre.

**Total des tasseaux :** coque extérieure 112 tasseaux (240,3 ft), coque intérieure 112 tasseaux (218,3 ft),
cales 224 pièces (63,2 ft) — **521,8 ft linéaires**.

**Regroupez vos coupes par biseau sur l'ensemble des modules**, pas module par module.

#### 3. Construisez les Cadres des Modules

1. Construisez chaque cadre à plat
2. Assemblez les tasseaux par les onglets et vérifiez chaque angle
3. Fixez les assemblages avec des vis GRK
4. Reliez les tasseaux extérieurs et intérieurs par la couche de cales. Elle donne la paroi de 5,0 in
5. Faites un essai à blanc des modules voisins avant de les fixer

#### 4. Assemblez sur le Plancher

1. Construisez d'abord le plancher. C'est le plan où s'arrête chaque côté prolongé
2. Posez les modules inférieurs (B, C, E) sur le plancher, puis montez
3. Utilisez des supports temporaires pour maintenir les modules
4. Travaillez par sections pour que l'ensemble reste solide

**Passages d'angle :** à chacun des quatre coins intérieurs, un espace triangulaire reste au niveau du sol,
4,671 in de haut × 3,394 in de large. C'est un passage technique vers le vide de la paroi (il accepte une
gaine de 3 in ou un faisceau de câbles). Fermez-le avec un cache amovible. Ne le comblez pas.

#### 5. Posez les Panneaux

**Parement extérieur — les recouvrements évacuent l'eau :**
- Le panneau dont le centre est le plus haut recouvre le plus bas. **Posez de bas en haut.**
- Chaque recouvrement fait 1,5 in, comme l'épaisseur du tasseau : il repose entièrement sur le tasseau du panneau inférieur et peut y être vissé.
- **Faites une coupure de capillarité sous chaque bord qui recouvre :** une rainure de ⅛ in de large × ⅛ in de profondeur, à 0,5 in du bord. Sans elle, l'eau remonte entre les panneaux par capillarité, quelle que soit la longueur du recouvrement.
- Les huit faces équatoriales sont verticales. Leurs joints verticaux reçoivent un joint d'étanchéité ou un couvre-joint, pas un recouvrement.
- Le faîte est le seul joint sans côté plus haut. Scellez-le avec un joint d'étanchéité.

**Parement intérieur :**
- Coupez-le aux dimensions du cadre intérieur

**Pose :**
1. Poncez les bords
2. Appliquez du mastic silicone sur les bords du cadre
3. Pressez les panneaux en place et vissez-les sur tout le périmètre
4. Essuyez l'excédent de mastic

#### 6. Protégez des Intempéries

**Scellez tous les joints :**
- Appliquez du mastic silicone sur tous les joints extérieurs
- Portez une attention particulière aux bords des panneaux
- Laissez durcir 24 heures

**Appliquez la finition :**
- Peignez ou scellez toutes les surfaces en bois
- Utilisez une peinture extérieure pour un usage dehors
- Appliquez plusieurs couches pour la durabilité

### Conseils de Pro

- **Regroupez par biseau** : triez le bois et regroupez les coupes par biseau, jamais par module
- **Prenez votre temps** : La précision des angles est essentielle
- **Faites des essais** : Assemblez les sections à blanc avant l'assemblage final
- **Utilisez des gabarits** : Fabriquez des gabarits simples pour tenir les pièces au bon angle
- **Travaillez à deux** : Certaines étapes sont plus faciles avec de l'aide
- **Vérifiez les mesures** : Contrôlez chaque pièce avant de couper

### Ressources

- [Compound Miter Saw Calculator](https://jansson.us/jcompound.html) - Pour calculer des angles précis
- [Vis GRK FIN/Trim™](https://grkfasteners.ca/product/fin-trim-finishing-trim-head-screw/) - Recommandées pour une finition propre
- [McMaster-Carr Hardware](https://www.mcmaster.com/90273A572/) - Pour la quincaillerie supplémentaire

### Référence Rapide

| | Valeur |
|---|---:|
| Diamètre extérieur | 93,700 in |
| Longueur d'arête, extérieure / intérieure | 18,906 / 16,701 in |
| Biseau, hexagone ↔ hexagone | 20,905° |
| Biseau, hexagone ↔ pentagone | 18,689° |
| Onglet, hexagone / pentagone / pointe du cerf-volant | 30° / 36° / 36° |
| Largeur d'une moitié refendue (trait de ⅛ in) | 1,6875 in |
| Épaisseur de paroi | 5,0 in |
| Modules | 23 |
| Montants 2×4 de 96 in | 36 |
| Panneaux 4×8, ¼ in / ¾ in | 16 / 2 |

## 📁 Structure du Projet

```
Thiosphere-Open-Source-Repo/
├── README.md                    # Ce fichier (Anglais)
├── README.de.md                 # Documentation en Allemand
├── README.es.md                 # Documentation en Espagnol
├── README.fr.md                 # Documentation en Français
├── README.sv.md                 # Documentation en Suédois
├── README.fi.md                 # Documentation en Finnois
├── LICENSE.md                   # Licence Hardware Open Source de CERN v2
├── thiosphere-design-document.md # Documentation complète de design
├── Bill_of_Materials_v.0.1.csv  # Liste des matériaux
├── src/                         # Fichiers source
│   ├── thiosphere_0.01.step     # Modèle CAD (format STEP)
│   └── thiosphere-fine.stl      # Modèle 3D (format STL)
├── _media/                      # Images et médias
└── docs/                        # Documentation supplémentaire
```

## 🤝 Contribuer

Nous accueillons les contributions au projet Thiosphere ! Veuillez lire nos directives de contribution :

1. **Forker le repository**
2. **Créer une branche de fonctionnalité** (`git checkout -b feature/amazing-feature`)
3. **Commiter vos changements** (`git commit -m 'Add some amazing feature'`)
4. **Pousser vers la branche** (`git push origin feature/amazing-feature`)
5. **Ouvrir une Pull Request**

### Directives de Contribution

- Suivre les exigences de la Licence Hardware Open Source de CERN v2
- Documenter toutes les modifications de manière exhaustive
- Inclure une Liste des Matériaux mise à jour si les changements affectent les matériaux
- Tester vos modifications avant de soumettre
- Fournir une documentation claire pour toute nouvelle fonctionnalité

## 📄 Licence

Ce projet est sous licence **Licence Hardware Open Source de CERN Version 2 - Fortement Réciproque**. Voir le fichier [LICENSE.md](LICENSE.md) pour les détails.

## 🔗 Liens

- **Site Web** : [https://thiosphere.org](https://thiosphere.org)
- **Document de Design** : [thiosphere-design-document.md](thiosphere-design-document.md)
- **Liste des Matériaux** : [Bill_of_Materials_v.0.1.csv](Bill_of_Materials_v.0.1.csv)
- **Modèles CAD** : [src/](src/)

## 🙏 Remerciements

- CERN pour la Licence Hardware Open Source
- La communauté du hardware open source
- Tous les contributeurs et constructeurs qui ont aidé à développer le Thiosphere

---

**Thiospheres - Domus Opus Est** (le travail de l'abri ne finit jamais).

*"Nous avons formaté notre monde pour les voitures, mais nous avons peu d'autre chose pour utiliser tout cet espace que nous avons cédé à ces machines."*

---

*Ce projet est créé et sponsorisé par [thios.co](https://thios.co)*
