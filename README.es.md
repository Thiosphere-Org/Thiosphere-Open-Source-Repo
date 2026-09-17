# Thiosphere - Refugios Modulares de Código Abierto

[![CERN Open Hardware License v2](https://img.shields.io/badge/License-CERN%20OHL%20v2%20Strongly%20Reciprocal-blue.svg)](LICENSE.md)
[![Open Source Hardware](https://img.shields.io/badge/Open%20Source-Hardware-green.svg)](https://www.oshwa.org/)
[![Documentation](https://img.shields.io/badge/Documentation-Complete-brightgreen.svg)](docs/)

[🇺🇸 English](README.md) | [🇩🇪 Deutsch](README.de.md) | [🇪🇸 Español](README.es.md) | [🇫🇷 Français](README.fr.md) | [🇸🇪 Svenska](README.sv.md) | [🇫🇮 Suomi](README.fi.md)

---

# Refugios Modulares de Código Abierto

Hemos formateado nuestro mundo para los automóviles, pero tenemos poco más para aprovechar todo ese espacio que hemos cedido a estas máquinas. Un Thiosphere™ se crea para llenar ese vacío con un propósito y belleza que define su diseño audaz y eficiente. Es Hardware de Código Abierto que cualquiera puede construir y modificar según sus propias necesidades.

## Introducción

Un thiosphere está hecho con el menor número posible de piezas, pero resulta en un refugio modular fuerte, ligero y espacioso que solo ocupa 1/2 de una plaza de estacionamiento. Es empaquetable plano y se puede ensamblar con herramientas comunes. Es modular para que puedas crear un número infinito de estructuras, desde un refugio simple hasta una oficina compleja. Es tanto funcional como hermoso, y está diseñado para ser un segundo lugar donde la vida pueda florecer - sea lo que sea y donde sea que estén esos requisitos.

![Conceptos Básicos del Thiosphere](_media/football.png)
![Conceptos Básicos del Thiosphere](_media/basics.png)
![Vista Aplanada del Thiosphere](_media/flatten.png)

### Licencia de Hardware de Código Abierto

Entendiendo Nuestra Licencia de Hardware Abierto
La Licencia de Hardware Abierto de CERN (Versión 2 - Fuerte Recíproca) asegura que:

- Todos los diseños y modificaciones deben compartirse abiertamente
- Se permite el uso comercial con la atribución apropiada
- Las versiones modificadas deben compartirse bajo la misma licencia
- Los creadores originales deben ser acreditados
- Se debe proporcionar documentación para todos los cambios

![Escala del Thiosphere](_media/module.png)
![Escala del Thiosphere](_media/scale.png)

## Las Ventajas

- **Construido Fuerte**: Geometría esférica = máxima resistencia, mínimo material
- **Se Mantiene Fresco**: La convección natural mantiene el ambiente estable adentro
- **Encaja Perfectamente**: Diseñado para espacios de estacionamiento existentes - no se necesitan modificaciones
- **Fácil de Construir**: Geometría simple significa que puedes hacerlo localmente con herramientas básicas

## ¿Qué es un Thios?

> El número dos en griego se escribe como "δύο" y se pronuncia con un sonido suave "th" (thío), en lugar del "d" duro que uno podría esperar. Este prefijo "thio" describe perfectamente el diseño de doble esfera del Thiosphere™, un segundo lugar para la vida.

## Inicio Rápido

### 📋 Prerrequisitos

- Habilidades básicas de carpintería
- Acceso a herramientas estándar (ver Guía de Construcción)
- Comprensión de la Licencia de Hardware Abierto de CERN

### 🛠️ Primeros Pasos

1. **Revisar Documentación**: Comienza con el [Documento de Diseño](thiosphere-design-document.md)
2. **Verificar Materiales**: Revisa la [Lista de Materiales](Bill_of_Materials_v.0.1.csv)
3. **Entender la Licencia**: Lee la [Licencia de Hardware Abierto de CERN](LICENSE.md)
4. **Comenzar a Construir**: Sigue la Guía de Construcción abajo

## Guía de Construcción

> **De dónde salen estas cifras.** Todos los valores de abajo están medidos en el modelo final de
> Onshape *Thiosphere for prints* con `#maxWidth` = 93.700 in (verificado el 2026-09-12). Donde el antiguo
> [Documento de Diseño](thiosphere-design-document.md) o la
> [Lista de Materiales v0.1](Bill_of_Materials_v.0.1.csv) no coincidan, esta guía es la correcta.

### De un Vistazo

| | |
|---|---|
| Diámetro exterior | **93.700 in** (7 ft 9.7 in) |
| Longitud de arista, carcasa exterior | **18.906 in** |
| Longitud de arista, carcasa interior | **16.701 in** |
| Grosor de pared | **5.0 in** — ¼ revestimiento + 1½ listón + 1½ taco + 1½ listón + ¼ revestimiento |
| Altura libre sobre el suelo terminado, en la cumbrera | **79.829 in** |
| Plataforma de suelo | 12 lados, 88.543 × 91.773 in |
| Módulos | **23** |

La forma es un icosaedro truncado (32 caras: 20 hexágonos, 12 pentágonos). Se apoya sobre
una arista, no sobre una cara.

### Los 23 Módulos

Solo las 22 caras situadas a la altura del anillo inferior de hexágonos o por encima son paneles. Las 10
caras de abajo no se construyen: los tipos B, C y E se prolongan hasta la plataforma y ocupan su lugar.

| Tipo | Módulo | Cantidad | Cómo se hace |
|---|---|---:|---|
| A | Hexágono simple | 8 | Hexágono regular |
| B | Puerta | 4 | Hexágono, dos lados verticales prolongados hasta la plataforma |
| C | Pared lateral | 2 | Hexágono, dos lados inclinados prolongados hasta la plataforma |
| D | Pentágono simple | 4 | Pentágono regular |
| E | Cometa de esquina | 4 | Pentágono, dos lados prolongados hasta que se unen |
| FL | Plataforma de suelo | 1 | 12 lados, dos tableros de contrachapado de ¾ in |
| | **Total** | **23** | |

### Lo que Necesitarás

**Materiales:**
- **36** × montantes 2×4 de 96 in — cada uno se corta al hilo por el centro (incluye un 8.5% por corte y despuntes)
- **16** × tableros 4×8 de contrachapado de ¼ in — revestimientos exterior e interior, con un 35% para el anidado
- **2** × tableros 4×8 de contrachapado de ¾ in — plataforma de suelo
- Tornillos, pernos y ruedas, un remolque o un zócalo nivelador — las cantidades se están recalculando para el modelo actual y no se indican hasta estar verificadas

**Herramientas:**
- Sierra de mesa con hoja inclinable (el bisel se hace al cortar al hilo)
- Ingletadora compuesta
- Taladro atornillador
- Cinta métrica y lápiz
- Equipo de seguridad (gafas, protección auditiva)

### Construcción Paso a Paso

#### 1. Clasifica la Madera y Después Corta al Hilo

**Hay dos biseles, no uno.**

| El listón está entre | Bisel |
|---|---:|
| Hexágono ↔ hexágono | **20.905°** |
| Hexágono ↔ pentágono | **18.689°** |

- Cada 2×4 se corta al hilo por el centro con la hoja inclinada al ángulo del bisel. Una pasada hace el bisel y dos listones.
- Con un corte de ⅛ in, cada mitad mide 1.6875 in de ancho.
- El bisel se fija al cortar al hilo, y una mitad no se puede volver a cortar. **Decide qué bisel necesitan los listones de cada montante antes de cortarlo.**
- Un módulo hexagonal necesita **los dos** biseles: sus aristas alternan vecinos hexágono y pentágono. Un módulo pentagonal usa 18.689° en sus cinco aristas.

> ⚠️ **No uses un único bisel promediado de unos 19.8°.** Abre una holgura de unos 5⁄64 in en
> cada unión, y las holguras se suman en cada esquina donde se juntan tres listones.

#### 2. Corta los Listones a Medida

**Ingletes:** 30° en las esquinas de hexágono, 36° en las de pentágono, 36° en la punta de la cometa.

**Longitudes** (de punta a punta):

| Listón | Carcasa exterior | Carcasa interior |
|---|---:|---:|
| Aristas simples — tipos A y D, y las aristas no prolongadas de B, C y E | 18.906 in | 16.701 in |
| B · puerta, lado vertical | 49.497 in | 48.395 in |
| B · puerta, solera | 32.747 in | 28.927 in |
| C · pared lateral, lado inclinado | 49.497 in | 49.497 in |
| C · pared lateral, solera | 68.403 in | 66.198 in |
| E · cometa de esquina, lado prolongado | 49.497 in | 43.724 in |

**No hagas la carcasa interior escalando la exterior.** Los lados prolongados terminan en la
plataforma, y la plataforma no se mueve, así que se acortan menos que las aristas simples o nada en
absoluto. Por eso la carcasa interior tiene seis longitudes de listón y la exterior cuatro.

**Listón total:** carcasa exterior 112 listones (240.3 ft), carcasa interior 112 listones (218.3 ft),
tacos 224 piezas (63.2 ft) — **521.8 ft lineales**.

**Agrupa los cortes por bisel en todos los módulos**, no módulo por módulo.

#### 3. Construye los Bastidores de los Módulos

1. Construye cada bastidor en plano
2. Une los listones por los ingletes y comprueba cada ángulo
3. Asegura las uniones con tornillos GRK
4. Une los listones exteriores e interiores con la capa de tacos. Esta fija la pared de 5.0 in
5. Presenta en seco los módulos vecinos antes de fijarlos

#### 4. Monta sobre la Plataforma

1. Construye primero la plataforma de suelo. Es el plano donde termina cada lado prolongado
2. Coloca los módulos inferiores (B, C, E) sobre la plataforma y avanza hacia arriba
3. Usa soportes temporales para sujetar los módulos
4. Trabaja por secciones para que quede firme

**Pasos de esquina:** en cada una de las cuatro esquinas interiores queda un hueco triangular a ras de
suelo, de 4.671 in de alto × 3.394 in de ancho. Es un paso de instalaciones hacia la cámara de la pared
(admite un conducto de 3 in o un mazo de cables). Ciérralo con una tapa desmontable. No lo rellenes.

#### 5. Coloca los Paneles

**Revestimiento exterior — los solapes evacuan el agua:**
- El panel cuyo centro está más alto solapa sobre el más bajo. **Instala de abajo arriba.**
- Cada solape mide 1.5 in, igual que el grosor del listón, así que apoya por completo en el listón del panel de abajo y se puede atornillar en él.
- **Haz un corte anticapilar en la cara inferior de cada borde que solapa:** una ranura de ⅛ in de ancho × ⅛ in de profundidad, a 0.5 in del borde. Sin ella, el agua sube entre los tableros por capilaridad, sea cual sea el solape.
- Las ocho caras ecuatoriales son verticales. Sus juntas verticales llevan junta de estanqueidad o tapajuntas, no solape.
- La cumbrera es la única junta sin lado más alto. Séllala con una junta de estanqueidad.

**Revestimiento interior:**
- Corta a medida del bastidor interior

**Instalación:**
1. Lija los bordes
2. Aplica silicona en los bordes del bastidor
3. Presiona los paneles en su sitio y atorníllalos por todo el perímetro
4. Limpia el exceso de silicona

#### 6. Impermeabiliza

**Sella todas las juntas:**
- Aplica silicona en todas las juntas exteriores
- Presta especial atención a los bordes de los paneles
- Deja curar 24 horas

**Aplica el acabado:**
- Pinta o sella todas las superficies de madera
- Usa pintura de exterior para uso a la intemperie
- Aplica varias capas para mayor durabilidad

### Consejos Profesionales

- **Agrupa por bisel**: clasifica la madera y agrupa los cortes por bisel, nunca por módulo
- **Tómate tu tiempo**: La precisión en los ángulos es clave
- **Prueba el ajuste**: Monta en seco las secciones antes del montaje final
- **Usa plantillas**: Haz plantillas sencillas para sujetar las piezas en el ángulo correcto
- **Trabaja en pareja**: Algunos pasos son más fáciles con ayuda
- **Comprueba las medidas**: Verifica cada pieza antes de cortar

### Recursos

- [Compound Miter Saw Calculator](https://jansson.us/jcompound.html) - Para calcular ángulos precisos
- [Tornillos GRK FIN/Trim™](https://grkfasteners.ca/product/fin-trim-finishing-trim-head-screw/) - Recomendados para un acabado limpio
- [McMaster-Carr Hardware](https://www.mcmaster.com/90273A572/) - Para herrajes y fijaciones adicionales

### Referencia Rápida

| | Valor |
|---|---:|
| Diámetro exterior | 93.700 in |
| Longitud de arista, exterior / interior | 18.906 / 16.701 in |
| Bisel, hexágono ↔ hexágono | 20.905° |
| Bisel, hexágono ↔ pentágono | 18.689° |
| Inglete, hexágono / pentágono / punta de cometa | 30° / 36° / 36° |
| Ancho de media pieza (corte de ⅛ in) | 1.6875 in |
| Grosor de pared | 5.0 in |
| Módulos | 23 |
| Montantes 2×4 de 96 in | 36 |
| Tableros 4×8, ¼ in / ¾ in | 16 / 2 |

## 📁 Estructura del Proyecto

```
Thiosphere-Open-Source-Repo/
├── README.md                    # Este archivo (Inglés)
├── README.de.md                 # Documentación en Alemán
├── README.es.md                 # Documentación en Español
├── README.fr.md                 # Documentación en Francés
├── README.sv.md                 # Documentación en Sueco
├── README.fi.md                 # Documentación en Finlandés
├── LICENSE.md                   # Licencia de Hardware Abierto de CERN v2
├── thiosphere-design-document.md # Documentación completa de diseño
├── Bill_of_Materials_v.0.1.csv  # Lista de materiales
├── src/                         # Archivos fuente
│   ├── thiosphere_0.01.step     # Modelo CAD (formato STEP)
│   └── thiosphere-fine.stl      # Modelo 3D (formato STL)
├── _media/                      # Imágenes y medios
└── docs/                        # Documentación adicional
```

## 🤝 Contribuir

¡Aceptamos contribuciones al proyecto Thiosphere! Por favor lee nuestras pautas de contribución:

1. **Hacer fork del repositorio**
2. **Crear una rama de características** (`git checkout -b feature/amazing-feature`)
3. **Hacer commit de tus cambios** (`git commit -m 'Add some amazing feature'`)
4. **Hacer push a la rama** (`git push origin feature/amazing-feature`)
5. **Abrir un Pull Request**

### Pautas de Contribución

- Seguir los requisitos de la Licencia de Hardware Abierto de CERN v2
- Documentar todas las modificaciones exhaustivamente
- Incluir Lista de Materiales actualizada si los cambios afectan materiales
- Probar tus modificaciones antes de enviar
- Proporcionar documentación clara para cualquier nueva característica

## 📄 Licencia

Este proyecto está licenciado bajo la **Licencia de Hardware Abierto de CERN Versión 2 - Fuerte Recíproca**. Ver el archivo [LICENSE.md](LICENSE.md) para detalles.

## 🔗 Enlaces

- **Sitio Web**: [https://thiosphere.org](https://thiosphere.org)
- **Documento de Diseño**: [thiosphere-design-document.md](thiosphere-design-document.md)
- **Lista de Materiales**: [Bill_of_Materials_v.0.1.csv](Bill_of_Materials_v.0.1.csv)
- **Modelos CAD**: [src/](src/)

## 🙏 Agradecimientos

- CERN por la Licencia de Hardware Abierto
- La comunidad de hardware de código abierto
- Todos los contribuyentes y constructores que han ayudado a desarrollar el Thiosphere

---

**Thiospheres - Domus Opus Est** (el trabajo del refugio nunca termina).

*"Hemos formateado nuestro mundo para los automóviles, pero tenemos poco más para aprovechar todo ese espacio que hemos cedido a estas máquinas."*

---

*Este proyecto es creado y patrocinado por [thios.co](https://thios.co)*
